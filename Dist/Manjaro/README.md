Manjaro - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Manjaro.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Manjaro/Desktop/README.md) and [notebooks](/Dist/Manjaro/Notebook/README.md).

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

Total: 8710

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | Notebook    | [1fdf6ffce7](https://linux-hardware.org/?probe=1fdf6ffce7) | Dec 01, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a203c920d4](https://linux-hardware.org/?probe=a203c920d4) | Dec 01, 2022 |
| Dell          | Precision 5540              | Notebook    | [030dbd45f0](https://linux-hardware.org/?probe=030dbd45f0) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [72ab240431](https://linux-hardware.org/?probe=72ab240431) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [8cf4925f08](https://linux-hardware.org/?probe=8cf4925f08) | Dec 01, 2022 |
| Acer          | TravelMate P614-51T-G2      | Notebook    | [952e89e25d](https://linux-hardware.org/?probe=952e89e25d) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9bd70d2025](https://linux-hardware.org/?probe=9bd70d2025) | Nov 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [bd0ca3e793](https://linux-hardware.org/?probe=bd0ca3e793) | Nov 30, 2022 |
| Toshiba       | TECRA S11                   | Notebook    | [3d2414e47b](https://linux-hardware.org/?probe=3d2414e47b) | Nov 30, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [ece7618688](https://linux-hardware.org/?probe=ece7618688) | Nov 30, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [f5f86becf7](https://linux-hardware.org/?probe=f5f86becf7) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [2c0cb92f23](https://linux-hardware.org/?probe=2c0cb92f23) | Nov 29, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [b34e3370f4](https://linux-hardware.org/?probe=b34e3370f4) | Nov 29, 2022 |
| Samsung       | 730QED                      | Convertible | [5d62977479](https://linux-hardware.org/?probe=5d62977479) | Nov 29, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [45097ff070](https://linux-hardware.org/?probe=45097ff070) | Nov 29, 2022 |
| HP            | Notebook                    | Notebook    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460s 20FAS16J0... | Notebook    | [142a1e8a94](https://linux-hardware.org/?probe=142a1e8a94) | Nov 29, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e0bdd2fbd2](https://linux-hardware.org/?probe=e0bdd2fbd2) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [69a6535286](https://linux-hardware.org/?probe=69a6535286) | Nov 28, 2022 |
| Razer         | Blade                       | Notebook    | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a1c088bc35](https://linux-hardware.org/?probe=a1c088bc35) | Nov 28, 2022 |
| Dell          | 09WH54 A00                  | Desktop     | [2700be5b4a](https://linux-hardware.org/?probe=2700be5b4a) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [0dcd2bdc50](https://linux-hardware.org/?probe=0dcd2bdc50) | Nov 28, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [620cab185f](https://linux-hardware.org/?probe=620cab185f) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| HP            | 3397                        | Desktop     | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [7e65f428cc](https://linux-hardware.org/?probe=7e65f428cc) | Nov 27, 2022 |
| MSI           | GL62 7QF                    | Notebook    | [abd74be332](https://linux-hardware.org/?probe=abd74be332) | Nov 27, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [bb0d4b34af](https://linux-hardware.org/?probe=bb0d4b34af) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [2626d57c13](https://linux-hardware.org/?probe=2626d57c13) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| Alienware     | 15                          | Notebook    | [3423725ae2](https://linux-hardware.org/?probe=3423725ae2) | Nov 24, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [b4c105c294](https://linux-hardware.org/?probe=b4c105c294) | Nov 24, 2022 |
| MSI           | GP63 Leopard 8RE            | Notebook    | [f8bb75758e](https://linux-hardware.org/?probe=f8bb75758e) | Nov 24, 2022 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [6b71a5917c](https://linux-hardware.org/?probe=6b71a5917c) | Nov 24, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [8ea3c120c6](https://linux-hardware.org/?probe=8ea3c120c6) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [c799c028af](https://linux-hardware.org/?probe=c799c028af) | Nov 23, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [6cd720c62c](https://linux-hardware.org/?probe=6cd720c62c) | Nov 23, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [fc53a66047](https://linux-hardware.org/?probe=fc53a66047) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [96205eb8d4](https://linux-hardware.org/?probe=96205eb8d4) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [97571585cd](https://linux-hardware.org/?probe=97571585cd) | Nov 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e9ba2ff234](https://linux-hardware.org/?probe=e9ba2ff234) | Nov 22, 2022 |
| ASUSTek       | PRIME Z690-P                | Notebook    | [436bd74a38](https://linux-hardware.org/?probe=436bd74a38) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | Desktop     | [62b0cb4c94](https://linux-hardware.org/?probe=62b0cb4c94) | Nov 22, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [bdf1794487](https://linux-hardware.org/?probe=bdf1794487) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | Desktop     | [26e7d04331](https://linux-hardware.org/?probe=26e7d04331) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [7e8b56ff73](https://linux-hardware.org/?probe=7e8b56ff73) | Nov 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [54d3eed278](https://linux-hardware.org/?probe=54d3eed278) | Nov 21, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [a22e271ac2](https://linux-hardware.org/?probe=a22e271ac2) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [60c1698203](https://linux-hardware.org/?probe=60c1698203) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6722142846](https://linux-hardware.org/?probe=6722142846) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [bb043b7575](https://linux-hardware.org/?probe=bb043b7575) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [ec1395a487](https://linux-hardware.org/?probe=ec1395a487) | Nov 20, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7d1d0390ba](https://linux-hardware.org/?probe=7d1d0390ba) | Nov 20, 2022 |
| MSI           | 970A-G43                    | Desktop     | [6c04d813ff](https://linux-hardware.org/?probe=6c04d813ff) | Nov 20, 2022 |
| Lenovo        | ThinkPad T490 20N3S7BC02    | Notebook    | [76a37f4e66](https://linux-hardware.org/?probe=76a37f4e66) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d40491a06a](https://linux-hardware.org/?probe=d40491a06a) | Nov 19, 2022 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [95686093ce](https://linux-hardware.org/?probe=95686093ce) | Nov 19, 2022 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [bebe890c96](https://linux-hardware.org/?probe=bebe890c96) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [c8fc039301](https://linux-hardware.org/?probe=c8fc039301) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [1ffee02fee](https://linux-hardware.org/?probe=1ffee02fee) | Nov 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [ebceee7ddf](https://linux-hardware.org/?probe=ebceee7ddf) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [144470ec16](https://linux-hardware.org/?probe=144470ec16) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [312da35b57](https://linux-hardware.org/?probe=312da35b57) | Nov 17, 2022 |
| ASUSTek       | Maximus VIII GENE           | Desktop     | [8b542ffc42](https://linux-hardware.org/?probe=8b542ffc42) | Nov 17, 2022 |
| Lenovo        | ThinkPad T430 2349KQ3       | Notebook    | [aacdefc31b](https://linux-hardware.org/?probe=aacdefc31b) | Nov 17, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | Desktop     | [7f7b7354b8](https://linux-hardware.org/?probe=7f7b7354b8) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | Desktop     | [42d08e1136](https://linux-hardware.org/?probe=42d08e1136) | Nov 17, 2022 |
| HP            | Compaq 15                   | Notebook    | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [922ce95539](https://linux-hardware.org/?probe=922ce95539) | Nov 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [07d80f1783](https://linux-hardware.org/?probe=07d80f1783) | Nov 16, 2022 |
| Google        | Boten                       | Notebook    | [105e91dd04](https://linux-hardware.org/?probe=105e91dd04) | Nov 16, 2022 |
| HP            | EliteBook x360 830 G6       | Convertible | [d4b09c09f0](https://linux-hardware.org/?probe=d4b09c09f0) | Nov 15, 2022 |
| Gigabyte      | GA-A75M-UD2H                | Desktop     | [4da8ff348a](https://linux-hardware.org/?probe=4da8ff348a) | Nov 15, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c8c74ea1ec](https://linux-hardware.org/?probe=c8c74ea1ec) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [3e46bbaa1b](https://linux-hardware.org/?probe=3e46bbaa1b) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [cf97226a28](https://linux-hardware.org/?probe=cf97226a28) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [612006bada](https://linux-hardware.org/?probe=612006bada) | Nov 15, 2022 |
| Dell          | Latitude E6220              | Notebook    | [b1270460e6](https://linux-hardware.org/?probe=b1270460e6) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [2e122b28c4](https://linux-hardware.org/?probe=2e122b28c4) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [dcffe478fe](https://linux-hardware.org/?probe=dcffe478fe) | Nov 14, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [e6ef3b56eb](https://linux-hardware.org/?probe=e6ef3b56eb) | Nov 14, 2022 |
| Lenovo        | ThinkPad T450s 20BW000DH... | Notebook    | [b9913c760a](https://linux-hardware.org/?probe=b9913c760a) | Nov 14, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [e53d77c404](https://linux-hardware.org/?probe=e53d77c404) | Nov 14, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [41dbab85c0](https://linux-hardware.org/?probe=41dbab85c0) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b3473a1862](https://linux-hardware.org/?probe=b3473a1862) | Nov 13, 2022 |
| HP            | Tablet 11m-be0xxx           | Tablet      | [65526a6a14](https://linux-hardware.org/?probe=65526a6a14) | Nov 13, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [ca85c59fad](https://linux-hardware.org/?probe=ca85c59fad) | Nov 13, 2022 |
| MSI           | Z97A GAMING 7               | Desktop     | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [cee6d10d17](https://linux-hardware.org/?probe=cee6d10d17) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [7a628290f2](https://linux-hardware.org/?probe=7a628290f2) | Nov 13, 2022 |
| Dell          | G15 5510                    | Notebook    | [641a09f9cc](https://linux-hardware.org/?probe=641a09f9cc) | Nov 13, 2022 |
| MSI           | B85M-P33 V2                 | Desktop     | [d633461307](https://linux-hardware.org/?probe=d633461307) | Nov 13, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [6b2e935e07](https://linux-hardware.org/?probe=6b2e935e07) | Nov 12, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [b071af765d](https://linux-hardware.org/?probe=b071af765d) | Nov 12, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [b156c32896](https://linux-hardware.org/?probe=b156c32896) | Nov 12, 2022 |
| AZW           | SER V01                     | Mini pc     | [5123518533](https://linux-hardware.org/?probe=5123518533) | Nov 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [87b7416681](https://linux-hardware.org/?probe=87b7416681) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f4ed581802](https://linux-hardware.org/?probe=f4ed581802) | Nov 11, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e06ab9c0b9](https://linux-hardware.org/?probe=e06ab9c0b9) | Nov 11, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [2172ca7325](https://linux-hardware.org/?probe=2172ca7325) | Nov 11, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [11344e1661](https://linux-hardware.org/?probe=11344e1661) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [7827dd0f86](https://linux-hardware.org/?probe=7827dd0f86) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [64d896b971](https://linux-hardware.org/?probe=64d896b971) | Nov 11, 2022 |
| MSI           | X79A-GD45                   | Desktop     | [cb82895374](https://linux-hardware.org/?probe=cb82895374) | Nov 11, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [c3612a66aa](https://linux-hardware.org/?probe=c3612a66aa) | Nov 10, 2022 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [950c263b8a](https://linux-hardware.org/?probe=950c263b8a) | Nov 10, 2022 |
| Dell          | Latitude E6330              | Notebook    | [04113ad3de](https://linux-hardware.org/?probe=04113ad3de) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [8dcd548e89](https://linux-hardware.org/?probe=8dcd548e89) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [e95608162f](https://linux-hardware.org/?probe=e95608162f) | Nov 10, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [4868cf87f5](https://linux-hardware.org/?probe=4868cf87f5) | Nov 09, 2022 |
| Acer          | Aspire V5-123               | Notebook    | [7e9ca0bb77](https://linux-hardware.org/?probe=7e9ca0bb77) | Nov 09, 2022 |
| HP            | ENVY 15                     | Notebook    | [716fe10a4a](https://linux-hardware.org/?probe=716fe10a4a) | Nov 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9571026291](https://linux-hardware.org/?probe=9571026291) | Nov 08, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d93bdbd43a](https://linux-hardware.org/?probe=d93bdbd43a) | Nov 07, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [7f372be9dc](https://linux-hardware.org/?probe=7f372be9dc) | Nov 07, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [1fee3f08a9](https://linux-hardware.org/?probe=1fee3f08a9) | Nov 07, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [6c4ff211d1](https://linux-hardware.org/?probe=6c4ff211d1) | Nov 07, 2022 |
| HP            | 844C                        | Desktop     | [5b8b05d13d](https://linux-hardware.org/?probe=5b8b05d13d) | Nov 07, 2022 |
| ASRock        | AB350M                      | Desktop     | [fae0de4ece](https://linux-hardware.org/?probe=fae0de4ece) | Nov 07, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [c55efc41db](https://linux-hardware.org/?probe=c55efc41db) | Nov 06, 2022 |
| HP            | 828A                        | Desktop     | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| Dell          | Inspiron 5379               | Notebook    | [f18d0b8b8a](https://linux-hardware.org/?probe=f18d0b8b8a) | Nov 06, 2022 |
| Dell          | Inspiron 5379               | Notebook    | [141de7e9a7](https://linux-hardware.org/?probe=141de7e9a7) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [3d53b3616f](https://linux-hardware.org/?probe=3d53b3616f) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [e5abd4f928](https://linux-hardware.org/?probe=e5abd4f928) | Nov 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [fb29e83d2d](https://linux-hardware.org/?probe=fb29e83d2d) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [204c296466](https://linux-hardware.org/?probe=204c296466) | Nov 04, 2022 |
| HP            | Spectre x360 Conv 15        | Convertible | [f1d5f7705f](https://linux-hardware.org/?probe=f1d5f7705f) | Nov 04, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [d70f962654](https://linux-hardware.org/?probe=d70f962654) | Nov 04, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3428f76054](https://linux-hardware.org/?probe=3428f76054) | Nov 04, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | Desktop     | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [ca5335acd5](https://linux-hardware.org/?probe=ca5335acd5) | Nov 03, 2022 |
| Dell          | Latitude 7280               | Notebook    | [ec1ac4ec28](https://linux-hardware.org/?probe=ec1ac4ec28) | Nov 03, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [8ab3b70362](https://linux-hardware.org/?probe=8ab3b70362) | Nov 03, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fecd8f06dd](https://linux-hardware.org/?probe=fecd8f06dd) | Nov 02, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [2b5c165e30](https://linux-hardware.org/?probe=2b5c165e30) | Nov 02, 2022 |
| HP            | 8054                        | Desktop     | [0f866b3605](https://linux-hardware.org/?probe=0f866b3605) | Nov 02, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [4ffebc50a0](https://linux-hardware.org/?probe=4ffebc50a0) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| Dell          | Precision 7530              | Notebook    | [b1b5f7678c](https://linux-hardware.org/?probe=b1b5f7678c) | Nov 01, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ce0b9271b](https://linux-hardware.org/?probe=8ce0b9271b) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| Acer          | Aspire A515-46              | Notebook    | [ef6bcab217](https://linux-hardware.org/?probe=ef6bcab217) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [9333be5120](https://linux-hardware.org/?probe=9333be5120) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6e577f6de5](https://linux-hardware.org/?probe=6e577f6de5) | Nov 01, 2022 |
| Lenovo        | ThinkPad L460 20FVS1Y500    | Notebook    | [5fc669ddbe](https://linux-hardware.org/?probe=5fc669ddbe) | Nov 01, 2022 |
| SANTECH       | NL5xRU                      | Notebook    | [63e1b4298d](https://linux-hardware.org/?probe=63e1b4298d) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [6a28e2929d](https://linux-hardware.org/?probe=6a28e2929d) | Oct 31, 2022 |
| HP            | 3397                        | Desktop     | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Lenovo        | ThinkPad T440p 20AW005BG... | Notebook    | [b25134edde](https://linux-hardware.org/?probe=b25134edde) | Oct 31, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [5355a5547a](https://linux-hardware.org/?probe=5355a5547a) | Oct 31, 2022 |
| Alienware     | 15 R3                       | Notebook    | [4659975000](https://linux-hardware.org/?probe=4659975000) | Oct 31, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | Notebook    | [0e06dcc642](https://linux-hardware.org/?probe=0e06dcc642) | Oct 31, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [83cd207e4e](https://linux-hardware.org/?probe=83cd207e4e) | Oct 30, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [d2407c253b](https://linux-hardware.org/?probe=d2407c253b) | Oct 30, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [41a0a441d3](https://linux-hardware.org/?probe=41a0a441d3) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [56e2dbb09b](https://linux-hardware.org/?probe=56e2dbb09b) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [06cb3f01ba](https://linux-hardware.org/?probe=06cb3f01ba) | Oct 29, 2022 |
| Lenovo        | MAHOBAY Win8 STD EM DPK ... | All in one  | [4b37b09299](https://linux-hardware.org/?probe=4b37b09299) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| ASUSTek       | PRIME B365M-C               | Desktop     | [ccf9650f9a](https://linux-hardware.org/?probe=ccf9650f9a) | Oct 29, 2022 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [d157bdbc2b](https://linux-hardware.org/?probe=d157bdbc2b) | Oct 29, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [cef88d9d62](https://linux-hardware.org/?probe=cef88d9d62) | Oct 29, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| Acer          | Aspire 4745Z                | Notebook    | [baf4fe6e63](https://linux-hardware.org/?probe=baf4fe6e63) | Oct 29, 2022 |
| Chuwi         | LapBook Pro                 | Notebook    | [d362ed14bf](https://linux-hardware.org/?probe=d362ed14bf) | Oct 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [806e4d754d](https://linux-hardware.org/?probe=806e4d754d) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [d6ccf0a2d8](https://linux-hardware.org/?probe=d6ccf0a2d8) | Oct 28, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [d5c2f29c22](https://linux-hardware.org/?probe=d5c2f29c22) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | Desktop     | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [aec6edc8a0](https://linux-hardware.org/?probe=aec6edc8a0) | Oct 28, 2022 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [58d46fb47f](https://linux-hardware.org/?probe=58d46fb47f) | Oct 28, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [f575803f23](https://linux-hardware.org/?probe=f575803f23) | Oct 28, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [c923b6d506](https://linux-hardware.org/?probe=c923b6d506) | Oct 27, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [664bf1184f](https://linux-hardware.org/?probe=664bf1184f) | Oct 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0e69671817](https://linux-hardware.org/?probe=0e69671817) | Oct 27, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [b9c616b406](https://linux-hardware.org/?probe=b9c616b406) | Oct 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [16b3338525](https://linux-hardware.org/?probe=16b3338525) | Oct 27, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [d9f63cbff8](https://linux-hardware.org/?probe=d9f63cbff8) | Oct 26, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [26d539c606](https://linux-hardware.org/?probe=26d539c606) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ffa2d93859](https://linux-hardware.org/?probe=ffa2d93859) | Oct 26, 2022 |
| RuggedPC      | RuggedBookJ87               | Tablet      | [74d39d268f](https://linux-hardware.org/?probe=74d39d268f) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [642cfbc2d7](https://linux-hardware.org/?probe=642cfbc2d7) | Oct 26, 2022 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [c9a59d0ee9](https://linux-hardware.org/?probe=c9a59d0ee9) | Oct 26, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [300126736b](https://linux-hardware.org/?probe=300126736b) | Oct 26, 2022 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [1ded224c69](https://linux-hardware.org/?probe=1ded224c69) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Unknown       | 1.0                         | Desktop     | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [bb90eb1ad1](https://linux-hardware.org/?probe=bb90eb1ad1) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b2bb88f27f](https://linux-hardware.org/?probe=b2bb88f27f) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | Desktop     | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [e5d5599bc7](https://linux-hardware.org/?probe=e5d5599bc7) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [9cc8a69671](https://linux-hardware.org/?probe=9cc8a69671) | Oct 25, 2022 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [7e6d814d87](https://linux-hardware.org/?probe=7e6d814d87) | Oct 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [15ced71b20](https://linux-hardware.org/?probe=15ced71b20) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [8994af98ff](https://linux-hardware.org/?probe=8994af98ff) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [fc7326f81b](https://linux-hardware.org/?probe=fc7326f81b) | Oct 24, 2022 |
| Acer          | Aspire MC605 v1.0           | Desktop     | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [4b88876126](https://linux-hardware.org/?probe=4b88876126) | Oct 24, 2022 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [37028111aa](https://linux-hardware.org/?probe=37028111aa) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [bc30c6555a](https://linux-hardware.org/?probe=bc30c6555a) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [667d235a8f](https://linux-hardware.org/?probe=667d235a8f) | Oct 24, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [bb06dc4756](https://linux-hardware.org/?probe=bb06dc4756) | Oct 24, 2022 |
| HP            | 828A                        | Desktop     | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| Tactus        | GeoBook_240                 | Notebook    | [5331bf15bd](https://linux-hardware.org/?probe=5331bf15bd) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | Desktop     | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | Desktop     | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | Notebook    | [efb2913d22](https://linux-hardware.org/?probe=efb2913d22) | Oct 23, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [d28d720a26](https://linux-hardware.org/?probe=d28d720a26) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | Desktop     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c75d0e252d](https://linux-hardware.org/?probe=c75d0e252d) | Oct 23, 2022 |
| HP            | 1489                        | All in one  | [3b3379c0e2](https://linux-hardware.org/?probe=3b3379c0e2) | Oct 23, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [7cb3500943](https://linux-hardware.org/?probe=7cb3500943) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7cafd024ea](https://linux-hardware.org/?probe=7cafd024ea) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| Global Dis... | W11651                      | Notebook    | [9cf1e2df07](https://linux-hardware.org/?probe=9cf1e2df07) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [9f16b5a7e2](https://linux-hardware.org/?probe=9f16b5a7e2) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [e1dedae10a](https://linux-hardware.org/?probe=e1dedae10a) | Oct 22, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Lenovo        | Legion 5 82B5               | Notebook    | [3d67f01531](https://linux-hardware.org/?probe=3d67f01531) | Oct 22, 2022 |
| HP            | ProBook 6550b               | Notebook    | [cc300bedc8](https://linux-hardware.org/?probe=cc300bedc8) | Oct 21, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [ab90111e61](https://linux-hardware.org/?probe=ab90111e61) | Oct 21, 2022 |
| Dell          | Latitude E6400              | Notebook    | [d899ab2ef4](https://linux-hardware.org/?probe=d899ab2ef4) | Oct 21, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| Medion        | S15449                      | Notebook    | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| HP            | ProBook 6550b               | Notebook    | [176fc347d2](https://linux-hardware.org/?probe=176fc347d2) | Oct 20, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [8e75bbadf5](https://linux-hardware.org/?probe=8e75bbadf5) | Oct 20, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [7f069e1021](https://linux-hardware.org/?probe=7f069e1021) | Oct 20, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [30bf540299](https://linux-hardware.org/?probe=30bf540299) | Oct 19, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [2413dd813b](https://linux-hardware.org/?probe=2413dd813b) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [56089b3625](https://linux-hardware.org/?probe=56089b3625) | Oct 19, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [e07159c158](https://linux-hardware.org/?probe=e07159c158) | Oct 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [f329d7485d](https://linux-hardware.org/?probe=f329d7485d) | Oct 19, 2022 |
| Dell          | Latitude E6220              | Notebook    | [66badd4e9a](https://linux-hardware.org/?probe=66badd4e9a) | Oct 18, 2022 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [419bdfa23d](https://linux-hardware.org/?probe=419bdfa23d) | Oct 18, 2022 |
| ASRock        | X670E PG Lightning          | Desktop     | [c3ce6dce01](https://linux-hardware.org/?probe=c3ce6dce01) | Oct 18, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [0910d29ded](https://linux-hardware.org/?probe=0910d29ded) | Oct 18, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | Notebook    | [8c97c331b9](https://linux-hardware.org/?probe=8c97c331b9) | Oct 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [7639ea3b73](https://linux-hardware.org/?probe=7639ea3b73) | Oct 18, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [469118097a](https://linux-hardware.org/?probe=469118097a) | Oct 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [2f27f08ce8](https://linux-hardware.org/?probe=2f27f08ce8) | Oct 17, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [98024d1066](https://linux-hardware.org/?probe=98024d1066) | Oct 17, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [91e4682f34](https://linux-hardware.org/?probe=91e4682f34) | Oct 17, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [732f4ea8fe](https://linux-hardware.org/?probe=732f4ea8fe) | Oct 17, 2022 |
| HP            | ENVY 15                     | Notebook    | [17681478e1](https://linux-hardware.org/?probe=17681478e1) | Oct 17, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [55f7f983c4](https://linux-hardware.org/?probe=55f7f983c4) | Oct 17, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [7de3eff9df](https://linux-hardware.org/?probe=7de3eff9df) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [460ceb1307](https://linux-hardware.org/?probe=460ceb1307) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [93e82a30ac](https://linux-hardware.org/?probe=93e82a30ac) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [eb9b7e329b](https://linux-hardware.org/?probe=eb9b7e329b) | Oct 16, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [e515cd0e66](https://linux-hardware.org/?probe=e515cd0e66) | Oct 15, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [bb58a322f3](https://linux-hardware.org/?probe=bb58a322f3) | Oct 14, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| HP            | 802E                        | Desktop     | [6231a344aa](https://linux-hardware.org/?probe=6231a344aa) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [a71fb08b36](https://linux-hardware.org/?probe=a71fb08b36) | Oct 14, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [fcf93f53f4](https://linux-hardware.org/?probe=fcf93f53f4) | Oct 13, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [2188336cf7](https://linux-hardware.org/?probe=2188336cf7) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7a1b08d912](https://linux-hardware.org/?probe=7a1b08d912) | Oct 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [8990bf0049](https://linux-hardware.org/?probe=8990bf0049) | Oct 13, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [abf7c780d2](https://linux-hardware.org/?probe=abf7c780d2) | Oct 13, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [f55bb836c3](https://linux-hardware.org/?probe=f55bb836c3) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3f808f36a0](https://linux-hardware.org/?probe=3f808f36a0) | Oct 13, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [8e564b93cb](https://linux-hardware.org/?probe=8e564b93cb) | Oct 13, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [705931711b](https://linux-hardware.org/?probe=705931711b) | Oct 13, 2022 |
| Dell          | Latitude E7250              | Notebook    | [f397f81353](https://linux-hardware.org/?probe=f397f81353) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [318b3ef82b](https://linux-hardware.org/?probe=318b3ef82b) | Oct 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [cbc3888844](https://linux-hardware.org/?probe=cbc3888844) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [17feafd680](https://linux-hardware.org/?probe=17feafd680) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e940ddf8a7](https://linux-hardware.org/?probe=e940ddf8a7) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [1bbc611d89](https://linux-hardware.org/?probe=1bbc611d89) | Oct 12, 2022 |
| AVITA         | NS14A6                      | Notebook    | [0ed9ac0a2b](https://linux-hardware.org/?probe=0ed9ac0a2b) | Oct 11, 2022 |
| AVITA         | NS14A6                      | Notebook    | [27412eff74](https://linux-hardware.org/?probe=27412eff74) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [10ab944320](https://linux-hardware.org/?probe=10ab944320) | Oct 11, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [36fc5f2c90](https://linux-hardware.org/?probe=36fc5f2c90) | Oct 10, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [c3dc2e33df](https://linux-hardware.org/?probe=c3dc2e33df) | Oct 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [943ee204e0](https://linux-hardware.org/?probe=943ee204e0) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [cc663da2bc](https://linux-hardware.org/?probe=cc663da2bc) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [05e8d3583c](https://linux-hardware.org/?probe=05e8d3583c) | Oct 10, 2022 |
| HP            | 8460                        | Desktop     | [08601807cc](https://linux-hardware.org/?probe=08601807cc) | Oct 10, 2022 |
| HP            | 8460                        | Desktop     | [5be586f271](https://linux-hardware.org/?probe=5be586f271) | Oct 10, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [f335fc684d](https://linux-hardware.org/?probe=f335fc684d) | Oct 09, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [09ba76a57e](https://linux-hardware.org/?probe=09ba76a57e) | Oct 09, 2022 |
| ASUSTek       | P6X58-E-WS                  | Desktop     | [786a8ba316](https://linux-hardware.org/?probe=786a8ba316) | Oct 09, 2022 |
| Gigabyte      | MC62-G40-00 01000100        | Server      | [a4d3ab40a5](https://linux-hardware.org/?probe=a4d3ab40a5) | Oct 09, 2022 |
| Dell          | Precision 5560              | Notebook    | [001c5b0c94](https://linux-hardware.org/?probe=001c5b0c94) | Oct 09, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [656b9369be](https://linux-hardware.org/?probe=656b9369be) | Oct 09, 2022 |
| Dell          | Latitude 5310               | Notebook    | [f694e6b10e](https://linux-hardware.org/?probe=f694e6b10e) | Oct 09, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [740a5f78d8](https://linux-hardware.org/?probe=740a5f78d8) | Oct 09, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Acer          | Extensa 215-32              | Notebook    | [3e6ce67bb5](https://linux-hardware.org/?probe=3e6ce67bb5) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [49802b54cd](https://linux-hardware.org/?probe=49802b54cd) | Oct 08, 2022 |
| Acer          | Extensa 215-32              | Notebook    | [366f0e7930](https://linux-hardware.org/?probe=366f0e7930) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [4afa1df235](https://linux-hardware.org/?probe=4afa1df235) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [d0584d3672](https://linux-hardware.org/?probe=d0584d3672) | Oct 08, 2022 |
| Dell          | 0NW73C A00                  | Desktop     | [2b0a3f91ea](https://linux-hardware.org/?probe=2b0a3f91ea) | Oct 08, 2022 |
| HP            | Pavilion dv6                | Notebook    | [0c2329c8d6](https://linux-hardware.org/?probe=0c2329c8d6) | Oct 07, 2022 |
| Dell          | 0M9KCM A01                  | Desktop     | [6fa93f6da5](https://linux-hardware.org/?probe=6fa93f6da5) | Oct 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2e020fe882](https://linux-hardware.org/?probe=2e020fe882) | Oct 07, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [829a14598f](https://linux-hardware.org/?probe=829a14598f) | Oct 07, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [8130af2fab](https://linux-hardware.org/?probe=8130af2fab) | Oct 06, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [9b8147c1f7](https://linux-hardware.org/?probe=9b8147c1f7) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| HP            | 87D6 SMVB                   | Desktop     | [03cf885086](https://linux-hardware.org/?probe=03cf885086) | Oct 05, 2022 |
| Toshiba       | Encore                      | Notebook    | [a11bf538ec](https://linux-hardware.org/?probe=a11bf538ec) | Oct 05, 2022 |
| CyberPower... | FANG Pro                    | Notebook    | [e8734135b0](https://linux-hardware.org/?probe=e8734135b0) | Oct 05, 2022 |
| Lenovo        | N23 80UR                    | Convertible | [f6bf19c41a](https://linux-hardware.org/?probe=f6bf19c41a) | Oct 05, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [4ba2e11c73](https://linux-hardware.org/?probe=4ba2e11c73) | Oct 05, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| Jumper        | Ezpad                       | Tablet      | [20a54bbe35](https://linux-hardware.org/?probe=20a54bbe35) | Oct 04, 2022 |
| Jumper        | Ezpad                       | Tablet      | [a887c036ac](https://linux-hardware.org/?probe=a887c036ac) | Oct 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| HP            | 21D0                        | Desktop     | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| Lenovo        | ThinkPad T490 20RYS07R00    | Notebook    | [d6be1b9cf9](https://linux-hardware.org/?probe=d6be1b9cf9) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [ca89628082](https://linux-hardware.org/?probe=ca89628082) | Oct 03, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [77776da6f7](https://linux-hardware.org/?probe=77776da6f7) | Oct 03, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [84d4748b3e](https://linux-hardware.org/?probe=84d4748b3e) | Oct 03, 2022 |
| GPD           | G1621-02                    | Notebook    | [1f88eb2bec](https://linux-hardware.org/?probe=1f88eb2bec) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [9c3f9bb60e](https://linux-hardware.org/?probe=9c3f9bb60e) | Oct 03, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [d433417836](https://linux-hardware.org/?probe=d433417836) | Oct 03, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [0d67980efe](https://linux-hardware.org/?probe=0d67980efe) | Oct 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [a9f0d894af](https://linux-hardware.org/?probe=a9f0d894af) | Oct 03, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [f58849d2c7](https://linux-hardware.org/?probe=f58849d2c7) | Oct 03, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [4283f9a4bd](https://linux-hardware.org/?probe=4283f9a4bd) | Oct 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [831cd8e80f](https://linux-hardware.org/?probe=831cd8e80f) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [668ad3e30a](https://linux-hardware.org/?probe=668ad3e30a) | Oct 02, 2022 |
| HP            | ProBook 6470b               | Notebook    | [10438199c4](https://linux-hardware.org/?probe=10438199c4) | Oct 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [402a7995c4](https://linux-hardware.org/?probe=402a7995c4) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| HP            | 250 G3                      | Notebook    | [753ef53a5a](https://linux-hardware.org/?probe=753ef53a5a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [e722d17a52](https://linux-hardware.org/?probe=e722d17a52) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [15a068e26b](https://linux-hardware.org/?probe=15a068e26b) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3a9d882d91](https://linux-hardware.org/?probe=3a9d882d91) | Oct 01, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [dda857d7e6](https://linux-hardware.org/?probe=dda857d7e6) | Oct 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [012add7349](https://linux-hardware.org/?probe=012add7349) | Oct 01, 2022 |
| Gigabyte      | Z170X-Gaming GT             | Desktop     | [991ea6c93f](https://linux-hardware.org/?probe=991ea6c93f) | Oct 01, 2022 |
| Sony          | SVF15N17CXB                 | Notebook    | [5082dde27d](https://linux-hardware.org/?probe=5082dde27d) | Oct 01, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [32a742b50d](https://linux-hardware.org/?probe=32a742b50d) | Oct 01, 2022 |
| Irbis         | NB121                       | Notebook    | [a2eb8c8af1](https://linux-hardware.org/?probe=a2eb8c8af1) | Sep 30, 2022 |
| Dell          | 07PR60 A01                  | Desktop     | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [9667dac801](https://linux-hardware.org/?probe=9667dac801) | Sep 30, 2022 |
| Irbis         | NB121                       | Notebook    | [90a0ae1cf9](https://linux-hardware.org/?probe=90a0ae1cf9) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [3ad60e2d21](https://linux-hardware.org/?probe=3ad60e2d21) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [5a8032ee05](https://linux-hardware.org/?probe=5a8032ee05) | Sep 30, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [6d7beecaf6](https://linux-hardware.org/?probe=6d7beecaf6) | Sep 30, 2022 |
| HP            | Notebook                    | Notebook    | [e172f83238](https://linux-hardware.org/?probe=e172f83238) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [4e9248b1eb](https://linux-hardware.org/?probe=4e9248b1eb) | Sep 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [353324cbfd](https://linux-hardware.org/?probe=353324cbfd) | Sep 30, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [c9126cd382](https://linux-hardware.org/?probe=c9126cd382) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [a1bee52021](https://linux-hardware.org/?probe=a1bee52021) | Sep 29, 2022 |
| ASRock        | X399M Taichi                | Desktop     | [b7943d1645](https://linux-hardware.org/?probe=b7943d1645) | Sep 29, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [dfea1c9f70](https://linux-hardware.org/?probe=dfea1c9f70) | Sep 29, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [25d3fc37f5](https://linux-hardware.org/?probe=25d3fc37f5) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [f5ddf4a2b4](https://linux-hardware.org/?probe=f5ddf4a2b4) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | Desktop     | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [72d80e02c9](https://linux-hardware.org/?probe=72d80e02c9) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [47b22afda2](https://linux-hardware.org/?probe=47b22afda2) | Sep 29, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [7b34a50df8](https://linux-hardware.org/?probe=7b34a50df8) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [6a9066019c](https://linux-hardware.org/?probe=6a9066019c) | Sep 28, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [0fce536c7d](https://linux-hardware.org/?probe=0fce536c7d) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [27ce89f701](https://linux-hardware.org/?probe=27ce89f701) | Sep 28, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [9b3a3858bc](https://linux-hardware.org/?probe=9b3a3858bc) | Sep 28, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [9a1e3a98ab](https://linux-hardware.org/?probe=9a1e3a98ab) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [ebfbdd37b8](https://linux-hardware.org/?probe=ebfbdd37b8) | Sep 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [30507c8461](https://linux-hardware.org/?probe=30507c8461) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [09d154c2f2](https://linux-hardware.org/?probe=09d154c2f2) | Sep 27, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [e27e7bfd76](https://linux-hardware.org/?probe=e27e7bfd76) | Sep 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d211ff97c6](https://linux-hardware.org/?probe=d211ff97c6) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [a31db51878](https://linux-hardware.org/?probe=a31db51878) | Sep 26, 2022 |
| Dell          | Latitude E6400              | Notebook    | [c1190109d0](https://linux-hardware.org/?probe=c1190109d0) | Sep 26, 2022 |
| Lenovo        | ThinkPad T460p 20FW000EG... | Notebook    | [60138ee2f9](https://linux-hardware.org/?probe=60138ee2f9) | Sep 26, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [533cc3b3ae](https://linux-hardware.org/?probe=533cc3b3ae) | Sep 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [e5b4fe8914](https://linux-hardware.org/?probe=e5b4fe8914) | Sep 25, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4b6ce98f70](https://linux-hardware.org/?probe=4b6ce98f70) | Sep 25, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [c65cbf84dc](https://linux-hardware.org/?probe=c65cbf84dc) | Sep 25, 2022 |
| ASUSTek       | N45SF                       | Notebook    | [7461bd2562](https://linux-hardware.org/?probe=7461bd2562) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [0d1b8fe301](https://linux-hardware.org/?probe=0d1b8fe301) | Sep 25, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2fa3578315](https://linux-hardware.org/?probe=2fa3578315) | Sep 24, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [ccba8f6c1a](https://linux-hardware.org/?probe=ccba8f6c1a) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e47b2b85dc](https://linux-hardware.org/?probe=e47b2b85dc) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [719b20fd4e](https://linux-hardware.org/?probe=719b20fd4e) | Sep 24, 2022 |
| HP            | ENVY x360 Convert13-ay00... | Convertible | [41abb17737](https://linux-hardware.org/?probe=41abb17737) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [f9c071cdd8](https://linux-hardware.org/?probe=f9c071cdd8) | Sep 23, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [321edce78d](https://linux-hardware.org/?probe=321edce78d) | Sep 23, 2022 |
| Huanan        | X99-TF                      | Desktop     | [1361d73bcd](https://linux-hardware.org/?probe=1361d73bcd) | Sep 22, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [5e91cc6f07](https://linux-hardware.org/?probe=5e91cc6f07) | Sep 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [af65739ccc](https://linux-hardware.org/?probe=af65739ccc) | Sep 21, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [6b012b0a87](https://linux-hardware.org/?probe=6b012b0a87) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2f16f0177f](https://linux-hardware.org/?probe=2f16f0177f) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [967110ef60](https://linux-hardware.org/?probe=967110ef60) | Sep 21, 2022 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [ba2eadfd53](https://linux-hardware.org/?probe=ba2eadfd53) | Sep 21, 2022 |
| HP            | Laptop                      | Notebook    | [0cbc7e4f5a](https://linux-hardware.org/?probe=0cbc7e4f5a) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [1faf714086](https://linux-hardware.org/?probe=1faf714086) | Sep 21, 2022 |
| HP            | ENVY 15                     | Notebook    | [388547d18c](https://linux-hardware.org/?probe=388547d18c) | Sep 21, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [6ffce551a0](https://linux-hardware.org/?probe=6ffce551a0) | Sep 21, 2022 |
| HP            | ProBook 4520s               | Notebook    | [af4a575c52](https://linux-hardware.org/?probe=af4a575c52) | Sep 20, 2022 |
| Minix         | NEO G41V-4 Max              | Desktop     | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [f9f1973349](https://linux-hardware.org/?probe=f9f1973349) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [6c7d6ef178](https://linux-hardware.org/?probe=6c7d6ef178) | Sep 20, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [635c6895e1](https://linux-hardware.org/?probe=635c6895e1) | Sep 20, 2022 |
| Gateway       | NV57H                       | Notebook    | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [25d7dc8f0d](https://linux-hardware.org/?probe=25d7dc8f0d) | Sep 19, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a3e30957c7](https://linux-hardware.org/?probe=a3e30957c7) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [75cc4fa084](https://linux-hardware.org/?probe=75cc4fa084) | Sep 19, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [97e2956728](https://linux-hardware.org/?probe=97e2956728) | Sep 19, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [1cbec0f70e](https://linux-hardware.org/?probe=1cbec0f70e) | Sep 19, 2022 |
| HP            | 212B                        | Desktop     | [c823e0060e](https://linux-hardware.org/?probe=c823e0060e) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ACH6 82QJ        | Notebook    | [e2c5e4775c](https://linux-hardware.org/?probe=e2c5e4775c) | Sep 19, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b0e746792f](https://linux-hardware.org/?probe=b0e746792f) | Sep 19, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [397f485cfc](https://linux-hardware.org/?probe=397f485cfc) | Sep 19, 2022 |
| Dell          | Precision M4800             | Notebook    | [73d00fe344](https://linux-hardware.org/?probe=73d00fe344) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [b0836f0c26](https://linux-hardware.org/?probe=b0836f0c26) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [a28b408f4a](https://linux-hardware.org/?probe=a28b408f4a) | Sep 19, 2022 |
| ASUSTek       | G752VT                      | Notebook    | [bbd1eb7810](https://linux-hardware.org/?probe=bbd1eb7810) | Sep 18, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [3b6b90fee6](https://linux-hardware.org/?probe=3b6b90fee6) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [13b23fabb7](https://linux-hardware.org/?probe=13b23fabb7) | Sep 18, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d11c4e27df](https://linux-hardware.org/?probe=d11c4e27df) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| Samsung       | 950QCG                      | Convertible | [92aaede7a0](https://linux-hardware.org/?probe=92aaede7a0) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [59369fa3fb](https://linux-hardware.org/?probe=59369fa3fb) | Sep 17, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [f045e1f138](https://linux-hardware.org/?probe=f045e1f138) | Sep 17, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [b136916fb3](https://linux-hardware.org/?probe=b136916fb3) | Sep 16, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [8d9f049d7e](https://linux-hardware.org/?probe=8d9f049d7e) | Sep 16, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [05b029f919](https://linux-hardware.org/?probe=05b029f919) | Sep 16, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [19a46a2f8e](https://linux-hardware.org/?probe=19a46a2f8e) | Sep 16, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [31c810e744](https://linux-hardware.org/?probe=31c810e744) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [8e62e03e0b](https://linux-hardware.org/?probe=8e62e03e0b) | Sep 15, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [00bcfb51bd](https://linux-hardware.org/?probe=00bcfb51bd) | Sep 15, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [45309244c3](https://linux-hardware.org/?probe=45309244c3) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | Desktop     | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [df5d5b4f0d](https://linux-hardware.org/?probe=df5d5b4f0d) | Sep 13, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [c9df1f2514](https://linux-hardware.org/?probe=c9df1f2514) | Sep 13, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [b62bd233c2](https://linux-hardware.org/?probe=b62bd233c2) | Sep 13, 2022 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [8c9013ec12](https://linux-hardware.org/?probe=8c9013ec12) | Sep 13, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [dee9d6b81f](https://linux-hardware.org/?probe=dee9d6b81f) | Sep 13, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [9745e99a08](https://linux-hardware.org/?probe=9745e99a08) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [82b9d1247e](https://linux-hardware.org/?probe=82b9d1247e) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | Desktop     | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b7eb07ec8d](https://linux-hardware.org/?probe=b7eb07ec8d) | Sep 12, 2022 |
| HP            | Pavilion dm1                | Notebook    | [eec30e7c48](https://linux-hardware.org/?probe=eec30e7c48) | Sep 12, 2022 |
| HP            | ENVY 15                     | Notebook    | [97caacee16](https://linux-hardware.org/?probe=97caacee16) | Sep 12, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [3767b84078](https://linux-hardware.org/?probe=3767b84078) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [3d1d8301c3](https://linux-hardware.org/?probe=3d1d8301c3) | Sep 12, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [1b43b0d291](https://linux-hardware.org/?probe=1b43b0d291) | Sep 11, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [20b9167fee](https://linux-hardware.org/?probe=20b9167fee) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | Notebook    | [0d1c08d02b](https://linux-hardware.org/?probe=0d1c08d02b) | Sep 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ecadc5740](https://linux-hardware.org/?probe=1ecadc5740) | Sep 11, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [c3ceb9c38b](https://linux-hardware.org/?probe=c3ceb9c38b) | Sep 11, 2022 |
| MSI           | B350M BAZOOKA               | Desktop     | [ff7d2e74a5](https://linux-hardware.org/?probe=ff7d2e74a5) | Sep 11, 2022 |
| ASRock        | J3160DC-ITX                 | Desktop     | [e854b82ab9](https://linux-hardware.org/?probe=e854b82ab9) | Sep 10, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [8df1767beb](https://linux-hardware.org/?probe=8df1767beb) | Sep 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [f145a7915c](https://linux-hardware.org/?probe=f145a7915c) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| Dell          | Latitude E6430              | Notebook    | [323203ec1c](https://linux-hardware.org/?probe=323203ec1c) | Sep 09, 2022 |
| ASUSTek       | P9D-M Series                | Server      | [209be79723](https://linux-hardware.org/?probe=209be79723) | Sep 09, 2022 |
| Lenovo        | ThinkPad T540p 20BFA05FU... | Notebook    | [e953e3c331](https://linux-hardware.org/?probe=e953e3c331) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [2f23958df0](https://linux-hardware.org/?probe=2f23958df0) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f752846656](https://linux-hardware.org/?probe=f752846656) | Sep 09, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [70f5e3d77c](https://linux-hardware.org/?probe=70f5e3d77c) | Sep 08, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [408b0d3fd7](https://linux-hardware.org/?probe=408b0d3fd7) | Sep 07, 2022 |
| HP            | 3397                        | Desktop     | [0ebeef29bf](https://linux-hardware.org/?probe=0ebeef29bf) | Sep 07, 2022 |
| CyberPower... | FANG Pro                    | Notebook    | [4bb2815c31](https://linux-hardware.org/?probe=4bb2815c31) | Sep 07, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [84b26ca406](https://linux-hardware.org/?probe=84b26ca406) | Sep 07, 2022 |
| Intel         | Unknown                     | Desktop     | [2758407d23](https://linux-hardware.org/?probe=2758407d23) | Sep 07, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [bd15d55792](https://linux-hardware.org/?probe=bd15d55792) | Sep 07, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [d35810173c](https://linux-hardware.org/?probe=d35810173c) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| ASUSTek       | P9D-M Series                | Server      | [04faeec9ab](https://linux-hardware.org/?probe=04faeec9ab) | Sep 06, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [58e55d314a](https://linux-hardware.org/?probe=58e55d314a) | Sep 06, 2022 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [775e007fc8](https://linux-hardware.org/?probe=775e007fc8) | Sep 05, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [e0bb6ae251](https://linux-hardware.org/?probe=e0bb6ae251) | Sep 05, 2022 |
| Intel         | B75                         | Desktop     | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [11bdade1e5](https://linux-hardware.org/?probe=11bdade1e5) | Sep 05, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [5b76bade7e](https://linux-hardware.org/?probe=5b76bade7e) | Sep 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [43267285d4](https://linux-hardware.org/?probe=43267285d4) | Sep 04, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [518aa50eb0](https://linux-hardware.org/?probe=518aa50eb0) | Sep 04, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [cc43cdda9a](https://linux-hardware.org/?probe=cc43cdda9a) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [4a27f8b033](https://linux-hardware.org/?probe=4a27f8b033) | Sep 04, 2022 |
| HP            | 8054                        | Desktop     | [878115f808](https://linux-hardware.org/?probe=878115f808) | Sep 04, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [8d611bed12](https://linux-hardware.org/?probe=8d611bed12) | Sep 04, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [f9881e0b9b](https://linux-hardware.org/?probe=f9881e0b9b) | Sep 03, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [3e057c7bbb](https://linux-hardware.org/?probe=3e057c7bbb) | Sep 03, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [65562b09e0](https://linux-hardware.org/?probe=65562b09e0) | Sep 03, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [5b5cc6b013](https://linux-hardware.org/?probe=5b5cc6b013) | Sep 03, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [ca761f1ee7](https://linux-hardware.org/?probe=ca761f1ee7) | Sep 03, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [74cdbd53f7](https://linux-hardware.org/?probe=74cdbd53f7) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [3c2359f16d](https://linux-hardware.org/?probe=3c2359f16d) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | Desktop     | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [9bc39724f8](https://linux-hardware.org/?probe=9bc39724f8) | Sep 02, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [b7de6bff83](https://linux-hardware.org/?probe=b7de6bff83) | Sep 02, 2022 |
| HP            | 8054                        | Desktop     | [1586ce33d1](https://linux-hardware.org/?probe=1586ce33d1) | Sep 02, 2022 |
| ASRock        | N68-S                       | Desktop     | [df5d34428a](https://linux-hardware.org/?probe=df5d34428a) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [5ba264dfb2](https://linux-hardware.org/?probe=5ba264dfb2) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [169c9af937](https://linux-hardware.org/?probe=169c9af937) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [9cabeefea8](https://linux-hardware.org/?probe=9cabeefea8) | Sep 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [37695eb7e5](https://linux-hardware.org/?probe=37695eb7e5) | Aug 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [cba954794c](https://linux-hardware.org/?probe=cba954794c) | Aug 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d816d2ade0](https://linux-hardware.org/?probe=d816d2ade0) | Aug 30, 2022 |
| ASRock        | N68-S                       | Desktop     | [6aabf89438](https://linux-hardware.org/?probe=6aabf89438) | Aug 30, 2022 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | Notebook    | [df1e70349c](https://linux-hardware.org/?probe=df1e70349c) | Aug 29, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [e05dcd4a08](https://linux-hardware.org/?probe=e05dcd4a08) | Aug 29, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [422af9d6b5](https://linux-hardware.org/?probe=422af9d6b5) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [6f169db96b](https://linux-hardware.org/?probe=6f169db96b) | Aug 29, 2022 |
| ASRock        | N68-S                       | Desktop     | [4fff0a6104](https://linux-hardware.org/?probe=4fff0a6104) | Aug 29, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [ec9f8ea30e](https://linux-hardware.org/?probe=ec9f8ea30e) | Aug 28, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [1d3dfbba56](https://linux-hardware.org/?probe=1d3dfbba56) | Aug 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [8c6b85a46c](https://linux-hardware.org/?probe=8c6b85a46c) | Aug 27, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [f4fe5fd168](https://linux-hardware.org/?probe=f4fe5fd168) | Aug 27, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [94e2f7cedc](https://linux-hardware.org/?probe=94e2f7cedc) | Aug 27, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [4384be22c4](https://linux-hardware.org/?probe=4384be22c4) | Aug 27, 2022 |
| Dell          | 0KWVT8 A02                  | Desktop     | [3f9c00b0da](https://linux-hardware.org/?probe=3f9c00b0da) | Aug 27, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [85e0bc5d57](https://linux-hardware.org/?probe=85e0bc5d57) | Aug 27, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [1813b94682](https://linux-hardware.org/?probe=1813b94682) | Aug 27, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [741abbfe3d](https://linux-hardware.org/?probe=741abbfe3d) | Aug 26, 2022 |
| Lenovo        | ThinkPad E580 20KS003GMH    | Notebook    | [5cadf3c5d2](https://linux-hardware.org/?probe=5cadf3c5d2) | Aug 26, 2022 |
| ASRock        | X99 WS                      | Desktop     | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [d988e1aeb9](https://linux-hardware.org/?probe=d988e1aeb9) | Aug 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [9e3b6f2140](https://linux-hardware.org/?probe=9e3b6f2140) | Aug 24, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [4ea2e79611](https://linux-hardware.org/?probe=4ea2e79611) | Aug 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [15960dc164](https://linux-hardware.org/?probe=15960dc164) | Aug 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [eed44ba087](https://linux-hardware.org/?probe=eed44ba087) | Aug 24, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| ASUSTek       | X202E                       | Notebook    | [b814b9f427](https://linux-hardware.org/?probe=b814b9f427) | Aug 24, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [e4f7ce1ec7](https://linux-hardware.org/?probe=e4f7ce1ec7) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [beb772b7f1](https://linux-hardware.org/?probe=beb772b7f1) | Aug 23, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [8b5fe2494e](https://linux-hardware.org/?probe=8b5fe2494e) | Aug 23, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [254b378771](https://linux-hardware.org/?probe=254b378771) | Aug 23, 2022 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [79169c7ab4](https://linux-hardware.org/?probe=79169c7ab4) | Aug 23, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [975461703e](https://linux-hardware.org/?probe=975461703e) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [bc23fbec2a](https://linux-hardware.org/?probe=bc23fbec2a) | Aug 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [47cae9ef99](https://linux-hardware.org/?probe=47cae9ef99) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [ae3bcc6b88](https://linux-hardware.org/?probe=ae3bcc6b88) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [b45c0fb9fa](https://linux-hardware.org/?probe=b45c0fb9fa) | Aug 22, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [230033da23](https://linux-hardware.org/?probe=230033da23) | Aug 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0dbe2c5dfd](https://linux-hardware.org/?probe=0dbe2c5dfd) | Aug 22, 2022 |
| HP            | ENVY m6 Notebook            | Notebook    | [c51af546e7](https://linux-hardware.org/?probe=c51af546e7) | Aug 22, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [64b9832653](https://linux-hardware.org/?probe=64b9832653) | Aug 22, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | Desktop     | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [3b799e56c6](https://linux-hardware.org/?probe=3b799e56c6) | Aug 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [77a2156c5a](https://linux-hardware.org/?probe=77a2156c5a) | Aug 21, 2022 |
| MSI           | P55-GD55                    | Desktop     | [89f2c92fa1](https://linux-hardware.org/?probe=89f2c92fa1) | Aug 21, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [32e59cda1c](https://linux-hardware.org/?probe=32e59cda1c) | Aug 20, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [3f6370f978](https://linux-hardware.org/?probe=3f6370f978) | Aug 20, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [bafc4d3392](https://linux-hardware.org/?probe=bafc4d3392) | Aug 20, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [7a8fee05aa](https://linux-hardware.org/?probe=7a8fee05aa) | Aug 20, 2022 |
| ASUSTek       | PRIME B365M-C               | Desktop     | [8ae386a7a0](https://linux-hardware.org/?probe=8ae386a7a0) | Aug 20, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [1679336e66](https://linux-hardware.org/?probe=1679336e66) | Aug 19, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [1e9f4acc7b](https://linux-hardware.org/?probe=1e9f4acc7b) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [1d1f39fd1b](https://linux-hardware.org/?probe=1d1f39fd1b) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d59342b7a4](https://linux-hardware.org/?probe=d59342b7a4) | Aug 19, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [c636c0401e](https://linux-hardware.org/?probe=c636c0401e) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [fdcb40d147](https://linux-hardware.org/?probe=fdcb40d147) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [cf5500d7b1](https://linux-hardware.org/?probe=cf5500d7b1) | Aug 18, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [95a5dd6af3](https://linux-hardware.org/?probe=95a5dd6af3) | Aug 18, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [0a9d130f45](https://linux-hardware.org/?probe=0a9d130f45) | Aug 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [6e13e6abe8](https://linux-hardware.org/?probe=6e13e6abe8) | Aug 18, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [e61c3cee8a](https://linux-hardware.org/?probe=e61c3cee8a) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [41b271c4e7](https://linux-hardware.org/?probe=41b271c4e7) | Aug 17, 2022 |
| Gigabyte      | H61M-S2P                    | Desktop     | [49aedf1cf8](https://linux-hardware.org/?probe=49aedf1cf8) | Aug 17, 2022 |
| HP            | Pavilion x360 m3 Convert... | Convertible | [bde621edc4](https://linux-hardware.org/?probe=bde621edc4) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [e04617befa](https://linux-hardware.org/?probe=e04617befa) | Aug 17, 2022 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [08e79a0a1c](https://linux-hardware.org/?probe=08e79a0a1c) | Aug 16, 2022 |
| HP            | Dratini                     | Notebook    | [134a2600be](https://linux-hardware.org/?probe=134a2600be) | Aug 16, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| Samsung       | 950QDA                      | Convertible | [e03a1c1a0d](https://linux-hardware.org/?probe=e03a1c1a0d) | Aug 16, 2022 |
| VS Company    | H61H2                       | Desktop     | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| HP            | EliteBook 755 G5            | Notebook    | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bdf5ba285f](https://linux-hardware.org/?probe=bdf5ba285f) | Aug 15, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [db7b7b3126](https://linux-hardware.org/?probe=db7b7b3126) | Aug 15, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [2fb0eea98c](https://linux-hardware.org/?probe=2fb0eea98c) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [76e185a2e5](https://linux-hardware.org/?probe=76e185a2e5) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [c3fee5819a](https://linux-hardware.org/?probe=c3fee5819a) | Aug 14, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [646169ae62](https://linux-hardware.org/?probe=646169ae62) | Aug 14, 2022 |
| HP            | EliteBook 2760p             | Notebook    | [bb4c1e4c3a](https://linux-hardware.org/?probe=bb4c1e4c3a) | Aug 13, 2022 |
| HP            | 82A2                        | Desktop     | [bc3d667d42](https://linux-hardware.org/?probe=bc3d667d42) | Aug 13, 2022 |
| Lenovo        | IdeaPad 3 15IML05 D1 81W... | Notebook    | [59b3324e73](https://linux-hardware.org/?probe=59b3324e73) | Aug 13, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6b83355dfa](https://linux-hardware.org/?probe=6b83355dfa) | Aug 13, 2022 |
| MSI           | GE75 Raider 10SF            | Notebook    | [0fafeaaa76](https://linux-hardware.org/?probe=0fafeaaa76) | Aug 13, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [b7418c601b](https://linux-hardware.org/?probe=b7418c601b) | Aug 13, 2022 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [ba65d9b67e](https://linux-hardware.org/?probe=ba65d9b67e) | Aug 13, 2022 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [a94fe940b1](https://linux-hardware.org/?probe=a94fe940b1) | Aug 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [601732f75e](https://linux-hardware.org/?probe=601732f75e) | Aug 13, 2022 |
| Dell          | Precision M6600             | Notebook    | [9c860085a8](https://linux-hardware.org/?probe=9c860085a8) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [41560e8e13](https://linux-hardware.org/?probe=41560e8e13) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [59892dec35](https://linux-hardware.org/?probe=59892dec35) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f82761570b](https://linux-hardware.org/?probe=f82761570b) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [5640964630](https://linux-hardware.org/?probe=5640964630) | Aug 12, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [2f45536688](https://linux-hardware.org/?probe=2f45536688) | Aug 12, 2022 |
| AZW           | U59                         | Desktop     | [344d4587f6](https://linux-hardware.org/?probe=344d4587f6) | Aug 12, 2022 |
| Lenovo        | Z710 20250                  | Notebook    | [8c7b1d0773](https://linux-hardware.org/?probe=8c7b1d0773) | Aug 11, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [e3006f6ca1](https://linux-hardware.org/?probe=e3006f6ca1) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6a07e79eb7](https://linux-hardware.org/?probe=6a07e79eb7) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [7e83b07cca](https://linux-hardware.org/?probe=7e83b07cca) | Aug 11, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [f8a688c41e](https://linux-hardware.org/?probe=f8a688c41e) | Aug 11, 2022 |
| HP            | 255 G4                      | Notebook    | [3ed3978b93](https://linux-hardware.org/?probe=3ed3978b93) | Aug 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [3219cc3946](https://linux-hardware.org/?probe=3219cc3946) | Aug 10, 2022 |
| Dell          | Latitude 5421               | Notebook    | [b088f6b599](https://linux-hardware.org/?probe=b088f6b599) | Aug 10, 2022 |
| HP            | 8053                        | Desktop     | [db80dc0ee1](https://linux-hardware.org/?probe=db80dc0ee1) | Aug 10, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| ASUSTek       | ROG Strix G513QR            | Notebook    | [3b19026468](https://linux-hardware.org/?probe=3b19026468) | Aug 09, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [20746ad23d](https://linux-hardware.org/?probe=20746ad23d) | Aug 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [e4c7906333](https://linux-hardware.org/?probe=e4c7906333) | Aug 09, 2022 |
| Lenovo        | Bantry CRB NOK              | Desktop     | [fbeb21c99a](https://linux-hardware.org/?probe=fbeb21c99a) | Aug 09, 2022 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [7dab66307c](https://linux-hardware.org/?probe=7dab66307c) | Aug 09, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [49f045d747](https://linux-hardware.org/?probe=49f045d747) | Aug 09, 2022 |
| ASUSTek       | ROG Strix G513QR            | Notebook    | [7aa074e467](https://linux-hardware.org/?probe=7aa074e467) | Aug 08, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e7a185eb28](https://linux-hardware.org/?probe=e7a185eb28) | Aug 08, 2022 |
| Razer         | Blade                       | Notebook    | [e2d9f80c98](https://linux-hardware.org/?probe=e2d9f80c98) | Aug 08, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7d20ee4549](https://linux-hardware.org/?probe=7d20ee4549) | Aug 08, 2022 |
| Framework     | Laptop                      | Notebook    | [da39a41b6b](https://linux-hardware.org/?probe=da39a41b6b) | Aug 08, 2022 |
| Framework     | Laptop                      | Notebook    | [f754ffd1d1](https://linux-hardware.org/?probe=f754ffd1d1) | Aug 08, 2022 |
| ASUSTek       | G10DK                       | Desktop     | [2401d4af44](https://linux-hardware.org/?probe=2401d4af44) | Aug 08, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [7cf010b820](https://linux-hardware.org/?probe=7cf010b820) | Aug 08, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d8486d3371](https://linux-hardware.org/?probe=d8486d3371) | Aug 07, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [5235533a87](https://linux-hardware.org/?probe=5235533a87) | Aug 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [c4a323d350](https://linux-hardware.org/?probe=c4a323d350) | Aug 06, 2022 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [24fbb2877c](https://linux-hardware.org/?probe=24fbb2877c) | Aug 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS3UW00    | Notebook    | [ddefadf8f1](https://linux-hardware.org/?probe=ddefadf8f1) | Aug 06, 2022 |
| Google        | Blorb                       | Notebook    | [b893b34702](https://linux-hardware.org/?probe=b893b34702) | Aug 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7151e1746a](https://linux-hardware.org/?probe=7151e1746a) | Aug 05, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [a3aa8d0879](https://linux-hardware.org/?probe=a3aa8d0879) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [a2733a0f87](https://linux-hardware.org/?probe=a2733a0f87) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [66c9a8d0f6](https://linux-hardware.org/?probe=66c9a8d0f6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [417c72557c](https://linux-hardware.org/?probe=417c72557c) | Aug 05, 2022 |
| GPD           | G1621-02                    | Notebook    | [58586a10a3](https://linux-hardware.org/?probe=58586a10a3) | Aug 04, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [2e069ba5c2](https://linux-hardware.org/?probe=2e069ba5c2) | Aug 04, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [bce50a8d8b](https://linux-hardware.org/?probe=bce50a8d8b) | Aug 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [e963ce265b](https://linux-hardware.org/?probe=e963ce265b) | Aug 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [0ef9fef16d](https://linux-hardware.org/?probe=0ef9fef16d) | Aug 04, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [22b43d3149](https://linux-hardware.org/?probe=22b43d3149) | Aug 04, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [840cb1763f](https://linux-hardware.org/?probe=840cb1763f) | Aug 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ed6b6ce93e](https://linux-hardware.org/?probe=ed6b6ce93e) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8f15b50066](https://linux-hardware.org/?probe=8f15b50066) | Aug 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [41189cd175](https://linux-hardware.org/?probe=41189cd175) | Aug 03, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [1dfd4fe5ba](https://linux-hardware.org/?probe=1dfd4fe5ba) | Aug 03, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [05e8b8d782](https://linux-hardware.org/?probe=05e8b8d782) | Aug 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0df5a838bf](https://linux-hardware.org/?probe=0df5a838bf) | Aug 03, 2022 |
| Timi          | RedmiBook 14                | Notebook    | [10c33f11cf](https://linux-hardware.org/?probe=10c33f11cf) | Aug 02, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [5951f66289](https://linux-hardware.org/?probe=5951f66289) | Aug 02, 2022 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [c2520e642a](https://linux-hardware.org/?probe=c2520e642a) | Aug 02, 2022 |
| HP            | Unknown                     | Notebook    | [bd6c9221e7](https://linux-hardware.org/?probe=bd6c9221e7) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [30e0a23365](https://linux-hardware.org/?probe=30e0a23365) | Aug 01, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | Notebook    | [7b597ebcc8](https://linux-hardware.org/?probe=7b597ebcc8) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [97a5e9c390](https://linux-hardware.org/?probe=97a5e9c390) | Aug 01, 2022 |
| Dell          | G15 Special Edition 5521    | Notebook    | [c680e6f144](https://linux-hardware.org/?probe=c680e6f144) | Aug 01, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [83a5caa66d](https://linux-hardware.org/?probe=83a5caa66d) | Jul 31, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [838be3a87a](https://linux-hardware.org/?probe=838be3a87a) | Jul 31, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [6367e245e6](https://linux-hardware.org/?probe=6367e245e6) | Jul 31, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [3061a63de7](https://linux-hardware.org/?probe=3061a63de7) | Jul 31, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [8693dca4f6](https://linux-hardware.org/?probe=8693dca4f6) | Jul 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [249d407b66](https://linux-hardware.org/?probe=249d407b66) | Jul 30, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [c08016125d](https://linux-hardware.org/?probe=c08016125d) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9ea9e6f737](https://linux-hardware.org/?probe=9ea9e6f737) | Jul 30, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [a4baade53f](https://linux-hardware.org/?probe=a4baade53f) | Jul 30, 2022 |
| MSI           | X470 GAMING PRO MAX         | Desktop     | [5651db0a63](https://linux-hardware.org/?probe=5651db0a63) | Jul 30, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [a2909a87b1](https://linux-hardware.org/?probe=a2909a87b1) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | Desktop     | [1fd9e0ca3a](https://linux-hardware.org/?probe=1fd9e0ca3a) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | Desktop     | [309df31c47](https://linux-hardware.org/?probe=309df31c47) | Jul 30, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [f2ced448f2](https://linux-hardware.org/?probe=f2ced448f2) | Jul 29, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [aa446a0409](https://linux-hardware.org/?probe=aa446a0409) | Jul 29, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [fa38197b4d](https://linux-hardware.org/?probe=fa38197b4d) | Jul 29, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | Desktop     | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [8d93753bc7](https://linux-hardware.org/?probe=8d93753bc7) | Jul 29, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [910241c92e](https://linux-hardware.org/?probe=910241c92e) | Jul 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [fdb481a551](https://linux-hardware.org/?probe=fdb481a551) | Jul 28, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [230cf1bf3d](https://linux-hardware.org/?probe=230cf1bf3d) | Jul 28, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f666b16fde](https://linux-hardware.org/?probe=f666b16fde) | Jul 28, 2022 |
| Lenovo        | IdeaPad U430 Touch 20270    | Notebook    | [d73469794d](https://linux-hardware.org/?probe=d73469794d) | Jul 28, 2022 |
| Alienware     | 17                          | Notebook    | [6a4212d19d](https://linux-hardware.org/?probe=6a4212d19d) | Jul 27, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [f84c29c4b6](https://linux-hardware.org/?probe=f84c29c4b6) | Jul 27, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [90656d8ef4](https://linux-hardware.org/?probe=90656d8ef4) | Jul 27, 2022 |
| Lenovo        | ThinkPad T480s 20L8S31T0... | Notebook    | [60449c872b](https://linux-hardware.org/?probe=60449c872b) | Jul 27, 2022 |
| Lenovo        | 3717 SDK0J40697 WIN 3305... | Desktop     | [701f519b4c](https://linux-hardware.org/?probe=701f519b4c) | Jul 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f4f4bdfefd](https://linux-hardware.org/?probe=f4f4bdfefd) | Jul 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [b41540a078](https://linux-hardware.org/?probe=b41540a078) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [6d42baa166](https://linux-hardware.org/?probe=6d42baa166) | Jul 26, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [803bd277e7](https://linux-hardware.org/?probe=803bd277e7) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [8f19252d3b](https://linux-hardware.org/?probe=8f19252d3b) | Jul 26, 2022 |
| Lenovo        | ThinkPad E585 20KV000YUS    | Notebook    | [0c8cde264e](https://linux-hardware.org/?probe=0c8cde264e) | Jul 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [85d557665e](https://linux-hardware.org/?probe=85d557665e) | Jul 25, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [78415dc6be](https://linux-hardware.org/?probe=78415dc6be) | Jul 25, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [a1346acc8a](https://linux-hardware.org/?probe=a1346acc8a) | Jul 25, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [7621729bff](https://linux-hardware.org/?probe=7621729bff) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [123fc55893](https://linux-hardware.org/?probe=123fc55893) | Jul 24, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [1a2403b95a](https://linux-hardware.org/?probe=1a2403b95a) | Jul 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [83e5824a05](https://linux-hardware.org/?probe=83e5824a05) | Jul 24, 2022 |
| ASUSTek       | Q504UA                      | Notebook    | [373dce5a6f](https://linux-hardware.org/?probe=373dce5a6f) | Jul 24, 2022 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [b03f1fee53](https://linux-hardware.org/?probe=b03f1fee53) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e512b2f9f2](https://linux-hardware.org/?probe=e512b2f9f2) | Jul 23, 2022 |
| Dell          | 0GM819                      | Desktop     | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [9002ca2e54](https://linux-hardware.org/?probe=9002ca2e54) | Jul 23, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| System76      | Serval WS                   | Notebook    | [18259132ff](https://linux-hardware.org/?probe=18259132ff) | Jul 22, 2022 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [8d7172fe7e](https://linux-hardware.org/?probe=8d7172fe7e) | Jul 22, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| ASUSTek       | X450LCP                     | Notebook    | [0617861116](https://linux-hardware.org/?probe=0617861116) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [4e47525879](https://linux-hardware.org/?probe=4e47525879) | Jul 22, 2022 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [1775f75940](https://linux-hardware.org/?probe=1775f75940) | Jul 22, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [51c2b5bc3b](https://linux-hardware.org/?probe=51c2b5bc3b) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [5ff04691ce](https://linux-hardware.org/?probe=5ff04691ce) | Jul 21, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [1bcee43b6e](https://linux-hardware.org/?probe=1bcee43b6e) | Jul 21, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [771428353e](https://linux-hardware.org/?probe=771428353e) | Jul 21, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [492529f973](https://linux-hardware.org/?probe=492529f973) | Jul 21, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [cb66716a63](https://linux-hardware.org/?probe=cb66716a63) | Jul 21, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [e632ef83da](https://linux-hardware.org/?probe=e632ef83da) | Jul 20, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [03afe0a303](https://linux-hardware.org/?probe=03afe0a303) | Jul 20, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [5859932a73](https://linux-hardware.org/?probe=5859932a73) | Jul 20, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [8327d57f7b](https://linux-hardware.org/?probe=8327d57f7b) | Jul 20, 2022 |
| Notebook      | W350STQ/W370ST              | Notebook    | [613b1f9d19](https://linux-hardware.org/?probe=613b1f9d19) | Jul 20, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [29847a6864](https://linux-hardware.org/?probe=29847a6864) | Jul 20, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [c47d31f0ae](https://linux-hardware.org/?probe=c47d31f0ae) | Jul 19, 2022 |
| Lenovo        | ThinkPad E585 20KVCTO1WW    | Notebook    | [0602b2d850](https://linux-hardware.org/?probe=0602b2d850) | Jul 19, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [63489ff6e5](https://linux-hardware.org/?probe=63489ff6e5) | Jul 19, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [27a607d6ba](https://linux-hardware.org/?probe=27a607d6ba) | Jul 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fd46c32d92](https://linux-hardware.org/?probe=fd46c32d92) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [4f1ce227b5](https://linux-hardware.org/?probe=4f1ce227b5) | Jul 18, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d4c15eb5fd](https://linux-hardware.org/?probe=d4c15eb5fd) | Jul 18, 2022 |
| Lenovo        | ThinkPad SL510 28479XU      | Notebook    | [092a752a62](https://linux-hardware.org/?probe=092a752a62) | Jul 18, 2022 |
| Lenovo        | ThinkPad SL510 28479XU      | Notebook    | [5eea2f8d37](https://linux-hardware.org/?probe=5eea2f8d37) | Jul 18, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | Notebook    | [75cfb6ffa8](https://linux-hardware.org/?probe=75cfb6ffa8) | Jul 17, 2022 |
| Dell          | Latitude 7490               | Notebook    | [bed5644964](https://linux-hardware.org/?probe=bed5644964) | Jul 17, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [84d62872f5](https://linux-hardware.org/?probe=84d62872f5) | Jul 17, 2022 |
| HP            | Laptop 15-dy0xxx            | Notebook    | [cfd2b5a69c](https://linux-hardware.org/?probe=cfd2b5a69c) | Jul 17, 2022 |
| Schenker      | XMG PRO (Late 2021)         | Notebook    | [a59796b464](https://linux-hardware.org/?probe=a59796b464) | Jul 17, 2022 |
| Schenker      | XMG PRO (Late 2021)         | Notebook    | [d739731ef5](https://linux-hardware.org/?probe=d739731ef5) | Jul 17, 2022 |
| Google        | Coral                       | Notebook    | [ebf34e57e6](https://linux-hardware.org/?probe=ebf34e57e6) | Jul 17, 2022 |
| HP            | ProBook 4520s               | Notebook    | [580f66ae82](https://linux-hardware.org/?probe=580f66ae82) | Jul 16, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [1bb517b788](https://linux-hardware.org/?probe=1bb517b788) | Jul 16, 2022 |
| ASUSTek       | N552VW                      | Notebook    | [b29b2f27df](https://linux-hardware.org/?probe=b29b2f27df) | Jul 16, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [aa025d852d](https://linux-hardware.org/?probe=aa025d852d) | Jul 16, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [27f6399025](https://linux-hardware.org/?probe=27f6399025) | Jul 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3b1f082065](https://linux-hardware.org/?probe=3b1f082065) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [3605f29c73](https://linux-hardware.org/?probe=3605f29c73) | Jul 16, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [c05a228555](https://linux-hardware.org/?probe=c05a228555) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [533392d790](https://linux-hardware.org/?probe=533392d790) | Jul 16, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [0d6d6728ba](https://linux-hardware.org/?probe=0d6d6728ba) | Jul 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [8f50476a9d](https://linux-hardware.org/?probe=8f50476a9d) | Jul 15, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [476ab880f4](https://linux-hardware.org/?probe=476ab880f4) | Jul 15, 2022 |
| Notebook      | W350STQ/W370ST              | Notebook    | [86daf7b30d](https://linux-hardware.org/?probe=86daf7b30d) | Jul 15, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [dfc64d417f](https://linux-hardware.org/?probe=dfc64d417f) | Jul 15, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [d6b737940e](https://linux-hardware.org/?probe=d6b737940e) | Jul 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [06992e615b](https://linux-hardware.org/?probe=06992e615b) | Jul 15, 2022 |
| BESSTAR Te... | TL50                        | Desktop     | [c77ff65710](https://linux-hardware.org/?probe=c77ff65710) | Jul 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [c7a2ebd9dc](https://linux-hardware.org/?probe=c7a2ebd9dc) | Jul 15, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [fe231e27cf](https://linux-hardware.org/?probe=fe231e27cf) | Jul 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [dcdc04db9f](https://linux-hardware.org/?probe=dcdc04db9f) | Jul 14, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [367adf8f50](https://linux-hardware.org/?probe=367adf8f50) | Jul 14, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| HP            | Laptop 15-dy0xxx            | Notebook    | [a7eb387b79](https://linux-hardware.org/?probe=a7eb387b79) | Jul 14, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [d76b0db2ca](https://linux-hardware.org/?probe=d76b0db2ca) | Jul 13, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [f764827707](https://linux-hardware.org/?probe=f764827707) | Jul 13, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [316285fb12](https://linux-hardware.org/?probe=316285fb12) | Jul 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8bdaa5b844](https://linux-hardware.org/?probe=8bdaa5b844) | Jul 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [3207d8f9e9](https://linux-hardware.org/?probe=3207d8f9e9) | Jul 12, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [0f3d24f508](https://linux-hardware.org/?probe=0f3d24f508) | Jul 12, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [ded0cc5604](https://linux-hardware.org/?probe=ded0cc5604) | Jul 12, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [109bec9fa8](https://linux-hardware.org/?probe=109bec9fa8) | Jul 12, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [4d9388058d](https://linux-hardware.org/?probe=4d9388058d) | Jul 12, 2022 |
| Lenovo        | ThinkPad L470 20J5S01L00    | Notebook    | [401e13e2a6](https://linux-hardware.org/?probe=401e13e2a6) | Jul 12, 2022 |
| ASUSTek       | X202E                       | Notebook    | [102f50d1a3](https://linux-hardware.org/?probe=102f50d1a3) | Jul 12, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [7437e30da5](https://linux-hardware.org/?probe=7437e30da5) | Jul 11, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [32cbf49371](https://linux-hardware.org/?probe=32cbf49371) | Jul 11, 2022 |
| MSI           | Z77A-G45                    | Desktop     | [ff2bae4518](https://linux-hardware.org/?probe=ff2bae4518) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [98d0043f0e](https://linux-hardware.org/?probe=98d0043f0e) | Jul 10, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [b0f6891a0b](https://linux-hardware.org/?probe=b0f6891a0b) | Jul 10, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [5d31b181fd](https://linux-hardware.org/?probe=5d31b181fd) | Jul 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5c8deeb62c](https://linux-hardware.org/?probe=5c8deeb62c) | Jul 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| MSI           | Z77A-G45                    | Desktop     | [2d4a011972](https://linux-hardware.org/?probe=2d4a011972) | Jul 10, 2022 |
| Timi          | TM1701                      | Notebook    | [8786fe1e91](https://linux-hardware.org/?probe=8786fe1e91) | Jul 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ec2174a329](https://linux-hardware.org/?probe=ec2174a329) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [b161f9e458](https://linux-hardware.org/?probe=b161f9e458) | Jul 10, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [3aee4d5b24](https://linux-hardware.org/?probe=3aee4d5b24) | Jul 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a9ff12a6e5](https://linux-hardware.org/?probe=a9ff12a6e5) | Jul 08, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [5dc09a66d8](https://linux-hardware.org/?probe=5dc09a66d8) | Jul 08, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [567077c28d](https://linux-hardware.org/?probe=567077c28d) | Jul 08, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [e464cd5823](https://linux-hardware.org/?probe=e464cd5823) | Jul 08, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [5fa7449343](https://linux-hardware.org/?probe=5fa7449343) | Jul 08, 2022 |
| HP            | ProBook 4540s               | Notebook    | [6b67ccac52](https://linux-hardware.org/?probe=6b67ccac52) | Jul 08, 2022 |
| Lenovo        | ThinkPad X230 2325TXB       | Notebook    | [1bf8e19c53](https://linux-hardware.org/?probe=1bf8e19c53) | Jul 08, 2022 |
| Dell          | Latitude E6430              | Notebook    | [9375063ae6](https://linux-hardware.org/?probe=9375063ae6) | Jul 08, 2022 |
| Acer          | Swift SF514-54GT            | Notebook    | [554171275d](https://linux-hardware.org/?probe=554171275d) | Jul 07, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [c9eb8f9a5f](https://linux-hardware.org/?probe=c9eb8f9a5f) | Jul 07, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b46404cc89](https://linux-hardware.org/?probe=b46404cc89) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | Desktop     | [6e17948aa5](https://linux-hardware.org/?probe=6e17948aa5) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | Desktop     | [56b772ade4](https://linux-hardware.org/?probe=56b772ade4) | Jul 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2e79e73885](https://linux-hardware.org/?probe=2e79e73885) | Jul 07, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [a93792aef3](https://linux-hardware.org/?probe=a93792aef3) | Jul 07, 2022 |
| Dell          | Inspiron 7572               | Notebook    | [e249d01b2b](https://linux-hardware.org/?probe=e249d01b2b) | Jul 06, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [9467db0d89](https://linux-hardware.org/?probe=9467db0d89) | Jul 06, 2022 |
| Toshiba       | Satellite A100              | Notebook    | [460363ac20](https://linux-hardware.org/?probe=460363ac20) | Jul 06, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d58dd09f25](https://linux-hardware.org/?probe=d58dd09f25) | Jul 06, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [d9dc513be7](https://linux-hardware.org/?probe=d9dc513be7) | Jul 06, 2022 |
| Fujitsu       | D2981-A1 S26361-D2981-A1    | Desktop     | [5e40d26a2b](https://linux-hardware.org/?probe=5e40d26a2b) | Jul 06, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [53417c8761](https://linux-hardware.org/?probe=53417c8761) | Jul 06, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [ac1652fd54](https://linux-hardware.org/?probe=ac1652fd54) | Jul 06, 2022 |
| Toshiba       | Satellite A100              | Notebook    | [2b25713a3d](https://linux-hardware.org/?probe=2b25713a3d) | Jul 05, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [4281fab7fd](https://linux-hardware.org/?probe=4281fab7fd) | Jul 05, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [61d8d4b071](https://linux-hardware.org/?probe=61d8d4b071) | Jul 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0cd693879d](https://linux-hardware.org/?probe=0cd693879d) | Jul 05, 2022 |
| Dell          | Latitude E6410              | Notebook    | [51fa58eb7d](https://linux-hardware.org/?probe=51fa58eb7d) | Jul 05, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [3fa5f4d0a8](https://linux-hardware.org/?probe=3fa5f4d0a8) | Jul 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d285ee1f39](https://linux-hardware.org/?probe=d285ee1f39) | Jul 05, 2022 |
| Sony          | VJF153                      | Notebook    | [a1efa9107c](https://linux-hardware.org/?probe=a1efa9107c) | Jul 05, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a5e8e3a046](https://linux-hardware.org/?probe=a5e8e3a046) | Jul 05, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [39803eaf94](https://linux-hardware.org/?probe=39803eaf94) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [7d1eafc534](https://linux-hardware.org/?probe=7d1eafc534) | Jul 04, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [747051c1fc](https://linux-hardware.org/?probe=747051c1fc) | Jul 04, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [fb76db49bd](https://linux-hardware.org/?probe=fb76db49bd) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [341512bec5](https://linux-hardware.org/?probe=341512bec5) | Jul 04, 2022 |
| LG Electro... | 17Z90N-V.AA55A1             | Notebook    | [272164819f](https://linux-hardware.org/?probe=272164819f) | Jul 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| ASRock        | IMB-1213                    | Desktop     | [6e1ba0ba69](https://linux-hardware.org/?probe=6e1ba0ba69) | Jul 04, 2022 |
| HP            | 0A9Ch                       | Desktop     | [3dafdd1a3f](https://linux-hardware.org/?probe=3dafdd1a3f) | Jul 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| ASUSTek       | X55U                        | Notebook    | [ed55b4ef39](https://linux-hardware.org/?probe=ed55b4ef39) | Jul 03, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a381b573f6](https://linux-hardware.org/?probe=a381b573f6) | Jul 03, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f5b850a82c](https://linux-hardware.org/?probe=f5b850a82c) | Jul 03, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [9e7e4a5d8d](https://linux-hardware.org/?probe=9e7e4a5d8d) | Jul 03, 2022 |
| Timi          | Mi NoteBook Pro             | Notebook    | [046a18dc14](https://linux-hardware.org/?probe=046a18dc14) | Jul 03, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1a729c627d](https://linux-hardware.org/?probe=1a729c627d) | Jul 03, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [c55ade019d](https://linux-hardware.org/?probe=c55ade019d) | Jul 02, 2022 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | Notebook    | [d90a910042](https://linux-hardware.org/?probe=d90a910042) | Jul 02, 2022 |
| Dell          | Latitude E6410              | Notebook    | [325a691029](https://linux-hardware.org/?probe=325a691029) | Jul 02, 2022 |
| TENKU         | SB14                        | Notebook    | [cbe2900f4f](https://linux-hardware.org/?probe=cbe2900f4f) | Jul 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [49c2f8c46a](https://linux-hardware.org/?probe=49c2f8c46a) | Jul 02, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [ffaa37530b](https://linux-hardware.org/?probe=ffaa37530b) | Jul 02, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c633887935](https://linux-hardware.org/?probe=c633887935) | Jul 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [5763cb4576](https://linux-hardware.org/?probe=5763cb4576) | Jul 01, 2022 |
| HP            | ProBook 4540s               | Notebook    | [c47e971697](https://linux-hardware.org/?probe=c47e971697) | Jul 01, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [21dd020507](https://linux-hardware.org/?probe=21dd020507) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [9034bf7260](https://linux-hardware.org/?probe=9034bf7260) | Jul 01, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [ed5f328d6a](https://linux-hardware.org/?probe=ed5f328d6a) | Jul 01, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [dd5c77d711](https://linux-hardware.org/?probe=dd5c77d711) | Jul 01, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [217dcb770c](https://linux-hardware.org/?probe=217dcb770c) | Jul 01, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [15b5edddd3](https://linux-hardware.org/?probe=15b5edddd3) | Jun 30, 2022 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [7f17faf180](https://linux-hardware.org/?probe=7f17faf180) | Jun 30, 2022 |
| HP            | 0B54h D                     | Desktop     | [bef89f554e](https://linux-hardware.org/?probe=bef89f554e) | Jun 30, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [dbe5fe496a](https://linux-hardware.org/?probe=dbe5fe496a) | Jun 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6a2f1d22f1](https://linux-hardware.org/?probe=6a2f1d22f1) | Jun 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0a976062da](https://linux-hardware.org/?probe=0a976062da) | Jun 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [53842b1b7d](https://linux-hardware.org/?probe=53842b1b7d) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [e8d5e4ff14](https://linux-hardware.org/?probe=e8d5e4ff14) | Jun 29, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| Dell          | Latitude 3590               | Notebook    | [b5d4509068](https://linux-hardware.org/?probe=b5d4509068) | Jun 29, 2022 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [3c8656100a](https://linux-hardware.org/?probe=3c8656100a) | Jun 29, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [5b091180ec](https://linux-hardware.org/?probe=5b091180ec) | Jun 28, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [be4dd3360f](https://linux-hardware.org/?probe=be4dd3360f) | Jun 28, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [1b58bbb69c](https://linux-hardware.org/?probe=1b58bbb69c) | Jun 28, 2022 |
| ASUSTek       | X507UB                      | Notebook    | [0ba0fc4089](https://linux-hardware.org/?probe=0ba0fc4089) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [ec155fca3f](https://linux-hardware.org/?probe=ec155fca3f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [016ee6ec73](https://linux-hardware.org/?probe=016ee6ec73) | Jun 28, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [c442dd3af1](https://linux-hardware.org/?probe=c442dd3af1) | Jun 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [95db2f9536](https://linux-hardware.org/?probe=95db2f9536) | Jun 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [0441b2cf28](https://linux-hardware.org/?probe=0441b2cf28) | Jun 27, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [78eaeff700](https://linux-hardware.org/?probe=78eaeff700) | Jun 27, 2022 |
| HP            | 212B                        | Desktop     | [687ca162d2](https://linux-hardware.org/?probe=687ca162d2) | Jun 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [ca055793c5](https://linux-hardware.org/?probe=ca055793c5) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [441cba3212](https://linux-hardware.org/?probe=441cba3212) | Jun 27, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [8fb8607282](https://linux-hardware.org/?probe=8fb8607282) | Jun 27, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [862d58f1a4](https://linux-hardware.org/?probe=862d58f1a4) | Jun 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [2595b295a9](https://linux-hardware.org/?probe=2595b295a9) | Jun 27, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [a801c7c2ba](https://linux-hardware.org/?probe=a801c7c2ba) | Jun 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [da1c9472bd](https://linux-hardware.org/?probe=da1c9472bd) | Jun 27, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [1a50f7c080](https://linux-hardware.org/?probe=1a50f7c080) | Jun 27, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [0e8993f232](https://linux-hardware.org/?probe=0e8993f232) | Jun 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [92d424a6b5](https://linux-hardware.org/?probe=92d424a6b5) | Jun 26, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [dde9afd7cb](https://linux-hardware.org/?probe=dde9afd7cb) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [4fd5881226](https://linux-hardware.org/?probe=4fd5881226) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [01e2541b47](https://linux-hardware.org/?probe=01e2541b47) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [6b2aa6c257](https://linux-hardware.org/?probe=6b2aa6c257) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [dae78cdc9e](https://linux-hardware.org/?probe=dae78cdc9e) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [b397f63621](https://linux-hardware.org/?probe=b397f63621) | Jun 26, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [6c9ee0dadd](https://linux-hardware.org/?probe=6c9ee0dadd) | Jun 26, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [f1e0998426](https://linux-hardware.org/?probe=f1e0998426) | Jun 25, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8a6b59bd5d](https://linux-hardware.org/?probe=8a6b59bd5d) | Jun 25, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [9d53805c9a](https://linux-hardware.org/?probe=9d53805c9a) | Jun 25, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [b2af243689](https://linux-hardware.org/?probe=b2af243689) | Jun 25, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [abdb925c2a](https://linux-hardware.org/?probe=abdb925c2a) | Jun 24, 2022 |
| Gigabyte      | MQLP5AP-00                  | Desktop     | [fad6b4b320](https://linux-hardware.org/?probe=fad6b4b320) | Jun 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [072acf05a0](https://linux-hardware.org/?probe=072acf05a0) | Jun 24, 2022 |
| Lenovo        | Legion 5 82B5               | Notebook    | [f0b00bb55e](https://linux-hardware.org/?probe=f0b00bb55e) | Jun 24, 2022 |
| Lenovo        | ThinkPad S2 20GJA00S00      | Notebook    | [44eb58334d](https://linux-hardware.org/?probe=44eb58334d) | Jun 24, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Manjaro        | 2382      | 37.64%  |
| Manjaro 20.1   | 291       | 4.6%    |
| Manjaro 20.2.1 | 283       | 4.47%   |
| Manjaro 20.2   | 243       | 3.84%   |
| Manjaro 20.0.3 | 223       | 3.52%   |
| Manjaro 22.0.0 | 198       | 3.13%   |
| Manjaro 21.2.6 | 176       | 2.78%   |
| Manjaro 21.1.0 | 149       | 2.35%   |
| Manjaro 18.1.5 | 143       | 2.26%   |
| Manjaro 21.2.0 | 127       | 2.01%   |
| Manjaro 21.2.5 | 126       | 1.99%   |
| Manjaro 21.1.6 | 114       | 1.8%    |
| Manjaro 21.0.7 | 112       | 1.77%   |
| Manjaro 20.0   | 101       | 1.6%    |
| Manjaro 19.0.2 | 97        | 1.53%   |
| Manjaro 18.0.4 | 96        | 1.52%   |
| Manjaro 21.0   | 87        | 1.37%   |
| Manjaro 21.0.5 | 80        | 1.26%   |
| Manjaro 20.1.2 | 80        | 1.26%   |
| Manjaro 21.2.3 | 74        | 1.17%   |
| Manjaro 21.2.1 | 73        | 1.15%   |
| Manjaro 20.1.1 | 71        | 1.12%   |
| Manjaro 20.0.1 | 69        | 1.09%   |
| Manjaro 21.3.7 | 53        | 0.84%   |
| Manjaro 21.0.4 | 50        | 0.79%   |
| Manjaro 21.3.6 | 49        | 0.77%   |
| Manjaro 21.2.2 | 46        | 0.73%   |
| Manjaro 21.2.4 | 45        | 0.71%   |
| Manjaro 21.1.2 | 41        | 0.65%   |
| Manjaro 21.1.4 | 37        | 0.58%   |
| Manjaro 21.0.1 | 36        | 0.57%   |
| Manjaro 21.0.2 | 34        | 0.54%   |
| Manjaro 21.3.1 | 32        | 0.51%   |
| Manjaro 21.3.0 | 31        | 0.49%   |
| Manjaro 21.0.3 | 31        | 0.49%   |
| Manjaro 21.1.1 | 30        | 0.47%   |
| Manjaro 21.1.3 | 29        | 0.46%   |
| Manjaro 21.2rc | 28        | 0.44%   |
| Manjaro 18.1.4 | 27        | 0.43%   |
| Manjaro 21.1.5 | 25        | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Manjaro | 5816      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 293       | 4.27%   |
| 5.13.19-2-MANJARO | 179       | 2.61%   |
| 5.8.6-1-MANJARO   | 140       | 2.04%   |
| 5.9.11-3-MANJARO  | 129       | 1.88%   |
| 5.8.11-1-MANJARO  | 122       | 1.78%   |
| 5.15.28-1-MANJARO | 118       | 1.72%   |
| 5.8.18-1-MANJARO  | 101       | 1.47%   |
| 5.10.42-1-MANJARO | 101       | 1.47%   |
| 5.15.32-1-MANJARO | 100       | 1.46%   |
| 5.15.12-1-MANJARO | 82        | 1.19%   |
| 5.6.16-1-MANJARO  | 74        | 1.08%   |
| 5.8.16-2-MANJARO  | 73        | 1.06%   |
| 5.15.60-1-MANJARO | 68        | 0.99%   |
| 5.10.2-2-MANJARO  | 65        | 0.95%   |
| 5.7.9-1-MANJARO   | 61        | 0.89%   |
| 5.15.65-1-MANJARO | 61        | 0.89%   |
| 5.10.36-2-MANJARO | 61        | 0.89%   |
| 5.6.19-2-MANJARO  | 60        | 0.87%   |
| 5.10.7-3-MANJARO  | 60        | 0.87%   |
| 5.7.0-3-MANJARO   | 58        | 0.84%   |
| 5.8.3-2-MANJARO   | 57        | 0.83%   |
| 5.6.15-1-MANJARO  | 57        | 0.83%   |
| 5.12.9-1-MANJARO  | 54        | 0.79%   |
| 5.7.17-2-MANJARO  | 52        | 0.76%   |
| 5.15.41-1-MANJARO | 51        | 0.74%   |
| 5.14.10-1-MANJARO | 51        | 0.74%   |
| 5.9.1-1-MANJARO   | 50        | 0.73%   |
| 5.17.1-3-MANJARO  | 49        | 0.71%   |
| 5.10.23-1-MANJARO | 49        | 0.71%   |
| 5.16.14-1-MANJARO | 48        | 0.7%    |
| 5.15.7-1-MANJARO  | 48        | 0.7%    |
| 5.11.6-1-MANJARO  | 47        | 0.68%   |
| 5.15.74-3-MANJARO | 46        | 0.67%   |
| 5.15.25-1-MANJARO | 45        | 0.66%   |
| 5.10.34-1-MANJARO | 45        | 0.66%   |
| 5.6.12-1-MANJARO  | 44        | 0.64%   |
| 5.6.7-1-MANJARO   | 43        | 0.63%   |
| 5.4.6-2-MANJARO   | 43        | 0.63%   |
| 5.10.53-1-MANJARO | 43        | 0.63%   |
| 5.4.15-2-MANJARO  | 42        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.16  | 293       | 4.27%   |
| 5.13.19 | 180       | 2.62%   |
| 5.8.6   | 140       | 2.04%   |
| 5.9.11  | 136       | 1.98%   |
| 5.8.11  | 123       | 1.79%   |
| 5.15.28 | 118       | 1.72%   |
| 5.8.18  | 101       | 1.47%   |
| 5.15.32 | 101       | 1.47%   |
| 5.10.42 | 101       | 1.47%   |
| 5.15.12 | 82        | 1.2%    |
| 5.8.16  | 74        | 1.08%   |
| 5.6.16  | 74        | 1.08%   |
| 5.7.0   | 73        | 1.06%   |
| 5.9.1   | 69        | 1.01%   |
| 5.15.60 | 68        | 0.99%   |
| 5.6.19  | 66        | 0.96%   |
| 5.10.2  | 65        | 0.95%   |
| 5.10.7  | 62        | 0.9%    |
| 5.7.9   | 61        | 0.89%   |
| 5.17.1  | 61        | 0.89%   |
| 5.15.65 | 61        | 0.89%   |
| 5.10.36 | 61        | 0.89%   |
| 5.8.3   | 58        | 0.85%   |
| 5.6.15  | 57        | 0.83%   |
| 5.12.9  | 54        | 0.79%   |
| 5.7.17  | 53        | 0.77%   |
| 5.15.41 | 51        | 0.74%   |
| 5.14.10 | 51        | 0.74%   |
| 5.15.7  | 50        | 0.73%   |
| 5.10.23 | 49        | 0.71%   |
| 5.16.14 | 48        | 0.7%    |
| 5.11.6  | 48        | 0.7%    |
| 5.6.12  | 46        | 0.67%   |
| 5.15.74 | 46        | 0.67%   |
| 5.15.2  | 46        | 0.67%   |
| 5.15.25 | 45        | 0.66%   |
| 5.10.34 | 45        | 0.66%   |
| 5.6.7   | 44        | 0.64%   |
| 5.4.6   | 43        | 0.63%   |
| 5.10.53 | 43        | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1040      | 16.04%  |
| 5.10    | 902       | 13.91%  |
| 5.4     | 627       | 9.67%   |
| 5.9     | 589       | 9.08%   |
| 5.8     | 553       | 8.53%   |
| 5.6     | 393       | 6.06%   |
| 5.13    | 357       | 5.51%   |
| 5.7     | 264       | 4.07%   |
| 4.19    | 197       | 3.04%   |
| 5.11    | 184       | 2.84%   |
| 5.16    | 173       | 2.67%   |
| 5.12    | 157       | 2.42%   |
| 5.14    | 151       | 2.33%   |
| 5.17    | 142       | 2.19%   |
| 5.18    | 128       | 1.97%   |
| 5.19    | 127       | 1.96%   |
| 5.5     | 109       | 1.68%   |
| 6.0     | 92        | 1.42%   |
| 5.3     | 92        | 1.42%   |
| 4.14    | 60        | 0.93%   |
| 5.2     | 41        | 0.63%   |
| 5.0     | 30        | 0.46%   |
| 5.1     | 26        | 0.4%    |
| 4.20    | 14        | 0.22%   |
| 4.18    | 12        | 0.19%   |
| 6.1     | 9         | 0.14%   |
| 4.9     | 4         | 0.06%   |
| 4.16    | 4         | 0.06%   |
| 4.17    | 3         | 0.05%   |
| 4.7     | 2         | 0.03%   |
| 4.4     | 2         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5813      | 99.95%  |
| i686    | 2         | 0.03%   |
| aarch64 | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| KDE5                     | 2022      | 33.55%  |
| XFCE                     | 1352      | 22.44%  |
| GNOME                    | 1266      | 21.01%  |
| KDE                      | 549       | 9.11%   |
| Unknown                  | 298       | 4.95%   |
| X-Cinnamon               | 154       | 2.56%   |
| i3                       | 120       | 1.99%   |
| MATE                     | 58        | 0.96%   |
| Cinnamon                 | 56        | 0.93%   |
| Deepin                   | 48        | 0.8%    |
| Budgie                   | 28        | 0.46%   |
| awesome                  | 16        | 0.27%   |
| LXQt                     | 15        | 0.25%   |
| sway                     | 8         | 0.13%   |
| LXDE                     | 7         | 0.12%   |
| Bspwm                    | 5         | 0.08%   |
| i3-with-shmlog           | 3         | 0.05%   |
| GNOME Classic            | 3         | 0.05%   |
| DWM                      | 3         | 0.05%   |
| leftwm                   | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNOME Flashback          | 2         | 0.03%   |
| Yaru:ubuntu:GNOME        | 1         | 0.02%   |
| xinitrc                  | 1         | 0.02%   |
| Unity                    | 1         | 0.02%   |
| swayLANG=en_CA.UTF-8     | 1         | 0.02%   |
| qtile                    | 1         | 0.02%   |
| openbox                  | 1         | 0.02%   |
| herbstluftwm             | 1         | 0.02%   |
| Enlightenment            | 1         | 0.02%   |
| /usr/bin/openbox-session | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5064      | 85.67%  |
| Wayland | 665       | 11.25%  |
| Unknown | 126       | 2.13%   |
| Tty     | 56        | 0.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2360      | 39.53%  |
| SDDM    | 1530      | 25.63%  |
| LightDM | 1065      | 17.84%  |
| GDM     | 777       | 13.02%  |
| TDM     | 218       | 3.65%   |
| LXDM    | 9         | 0.15%   |
| SLiM    | 3         | 0.05%   |
| GREETD  | 3         | 0.05%   |
| XDM     | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| CDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2446      | 41.45%  |
| de_DE   | 465       | 7.88%   |
| ru_RU   | 426       | 7.22%   |
| Unknown | 405       | 6.86%   |
| en_GB   | 378       | 6.41%   |
| pt_BR   | 233       | 3.95%   |
| fr_FR   | 151       | 2.56%   |
| en_CA   | 129       | 2.19%   |
| es_ES   | 127       | 2.15%   |
| it_IT   | 123       | 2.08%   |
| pl_PL   | 104       | 1.76%   |
| en_AU   | 76        | 1.29%   |
| en_IN   | 71        | 1.2%    |
| zh_CN   | 44        | 0.75%   |
| es_MX   | 44        | 0.75%   |
| ru_UA   | 39        | 0.66%   |
| de_AT   | 35        | 0.59%   |
| nl_NL   | 31        | 0.53%   |
| es_AR   | 29        | 0.49%   |
| en_IE   | 28        | 0.47%   |
| sv_SE   | 24        | 0.41%   |
| pt_PT   | 20        | 0.34%   |
| fi_FI   | 20        | 0.34%   |
| es_CL   | 20        | 0.34%   |
| en_ZA   | 19        | 0.32%   |
| cs_CZ   | 19        | 0.32%   |
| tr_TR   | 18        | 0.31%   |
| hu_HU   | 18        | 0.31%   |
| en_NZ   | 18        | 0.31%   |
| C       | 18        | 0.31%   |
| en_DK   | 17        | 0.29%   |
| de_CH   | 17        | 0.29%   |
| uk_UA   | 15        | 0.25%   |
| es_CO   | 15        | 0.25%   |
| en_PH   | 14        | 0.24%   |
| fr_CA   | 13        | 0.22%   |
| nl_BE   | 12        | 0.2%    |
| en_IL   | 12        | 0.2%    |
| el_GR   | 11        | 0.19%   |
| da_DK   | 11        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3252      | 54.93%  |
| EFI  | 2668      | 45.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4980      | 84.68%  |
| Btrfs    | 507       | 8.62%   |
| Overlay  | 131       | 2.23%   |
| Unknown  | 129       | 2.19%   |
| Xfs      | 71        | 1.21%   |
| F2fs     | 26        | 0.44%   |
| Tmpfs    | 18        | 0.31%   |
| Ext3     | 5         | 0.09%   |
| Zfs      | 4         | 0.07%   |
| Ext2     | 4         | 0.07%   |
| Reiserfs | 3         | 0.05%   |
| XXXX     | 1         | 0.02%   |
| XXXfs    | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2743      | 46.3%   |
| Unknown | 2628      | 44.35%  |
| MBR     | 554       | 9.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5143      | 87.11%  |
| Yes       | 761       | 12.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3946      | 66.71%  |
| Yes       | 1969      | 33.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 1084      | 18.64%  |
| Lenovo              | 950       | 16.33%  |
| Hewlett-Packard     | 748       | 12.86%  |
| Dell                | 620       | 10.66%  |
| Gigabyte Technology | 479       | 8.24%   |
| MSI                 | 449       | 7.72%   |
| Acer                | 293       | 5.04%   |
| ASRock              | 247       | 4.25%   |
| Apple               | 114       | 1.96%   |
| Intel               | 78        | 1.34%   |
| Samsung Electronics | 61        | 1.05%   |
| Toshiba             | 59        | 1.01%   |
| HUAWEI              | 52        | 0.89%   |
| Timi                | 36        | 0.62%   |
| Fujitsu             | 33        | 0.57%   |
| Unknown             | 33        | 0.57%   |
| Notebook            | 28        | 0.48%   |
| Sony                | 27        | 0.46%   |
| Google              | 24        | 0.41%   |
| Pegatron            | 17        | 0.29%   |
| Microsoft           | 17        | 0.29%   |
| Biostar             | 17        | 0.29%   |
| Alienware           | 16        | 0.28%   |
| Medion              | 15        | 0.26%   |
| TUXEDO              | 13        | 0.22%   |
| Razer               | 13        | 0.22%   |
| Huanan              | 12        | 0.21%   |
| AZW                 | 12        | 0.21%   |
| Schenker            | 10        | 0.17%   |
| Positivo            | 10        | 0.17%   |
| Packard Bell        | 10        | 0.17%   |
| Foxconn             | 10        | 0.17%   |
| LG Electronics      | 8         | 0.14%   |
| BESSTAR Tech        | 8         | 0.14%   |
| TrekStor            | 7         | 0.12%   |
| System76            | 7         | 0.12%   |
| Panasonic           | 7         | 0.12%   |
| HONOR               | 7         | 0.12%   |
| ECS                 | 7         | 0.12%   |
| Monster             | 6         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| ASUS All Series                     | 64        | 1.1%    |
| Unknown                             | 45        | 0.77%   |
| Gigabyte B450M DS3H                 | 26        | 0.45%   |
| MSI MS-7C37                         | 21        | 0.36%   |
| MSI MS-7C02                         | 21        | 0.36%   |
| HP Notebook                         | 20        | 0.34%   |
| ASUS TUF Gaming X570-PLUS           | 19        | 0.33%   |
| ASUS PRIME A320M-K                  | 18        | 0.31%   |
| MSI MS-7B79                         | 15        | 0.26%   |
| ASRock B450M Pro4                   | 15        | 0.26%   |
| MSI MS-7C91                         | 14        | 0.24%   |
| MSI MS-7B86                         | 13        | 0.22%   |
| Lenovo Legion 5 15ARH05 82B5        | 13        | 0.22%   |
| Lenovo IdeaPad 5 15ARE05 81YQ       | 13        | 0.22%   |
| Dell XPS 13 9310                    | 13        | 0.22%   |
| ASUS ROG STRIX B450-F GAMING        | 13        | 0.22%   |
| MSI MS-7A38                         | 12        | 0.21%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2   | 12        | 0.21%   |
| ASUS TUF Gaming B550M-PLUS          | 12        | 0.21%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 11        | 0.19%   |
| Gigabyte X570 AORUS ELITE           | 11        | 0.19%   |
| Dell XPS 15 9500                    | 11        | 0.19%   |
| ASUS PRIME B450M-A                  | 11        | 0.19%   |
| ASUS PRIME B350-PLUS                | 11        | 0.19%   |
| HP Pavilion Notebook                | 10        | 0.17%   |
| HP Laptop 15-bs0xx                  | 10        | 0.17%   |
| Gigabyte X570 AORUS MASTER          | 10        | 0.17%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 10        | 0.17%   |
| Gigabyte B450 AORUS M               | 10        | 0.17%   |
| Gigabyte 970A-DS3P                  | 10        | 0.17%   |
| Dell OptiPlex 9020                  | 10        | 0.17%   |
| ASUS ROG STRIX B550-F GAMING        | 10        | 0.17%   |
| MSI MS-7B89                         | 9         | 0.15%   |
| MSI MS-7693                         | 9         | 0.15%   |
| HP Pavilion dv7                     | 9         | 0.15%   |
| Dell XPS 15 9560                    | 9         | 0.15%   |
| Dell Inspiron 3542                  | 9         | 0.15%   |
| ASUS ROG STRIX X570-E GAMING        | 9         | 0.15%   |
| ASUS ROG CROSSHAIR VIII HERO        | 9         | 0.15%   |
| ASUS PRIME X470-PRO                 | 9         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 388       | 6.67%   |
| Lenovo IdeaPad     | 233       | 4.01%   |
| Dell Inspiron      | 186       | 3.2%    |
| Acer Aspire        | 185       | 3.18%   |
| ASUS ROG           | 167       | 2.87%   |
| HP Pavilion        | 149       | 2.56%   |
| ASUS PRIME         | 136       | 2.34%   |
| Dell Latitude      | 133       | 2.29%   |
| Dell XPS           | 100       | 1.72%   |
| ASUS TUF           | 98        | 1.69%   |
| HP ProBook         | 92        | 1.58%   |
| HP Laptop          | 83        | 1.43%   |
| HP EliteBook       | 82        | 1.41%   |
| Dell OptiPlex      | 67        | 1.15%   |
| ASUS VivoBook      | 66        | 1.13%   |
| HP ENVY            | 65        | 1.12%   |
| ASUS All           | 64        | 1.1%    |
| Lenovo Legion      | 63        | 1.08%   |
| Dell Precision     | 54        | 0.93%   |
| Toshiba Satellite  | 51        | 0.88%   |
| HP Compaq          | 47        | 0.81%   |
| Lenovo Yoga        | 46        | 0.79%   |
| Gigabyte X570      | 45        | 0.77%   |
| Unknown            | 45        | 0.77%   |
| Gigabyte B450M     | 41        | 0.7%    |
| Dell Vostro        | 38        | 0.65%   |
| ASUS ZenBook       | 33        | 0.57%   |
| Acer Swift         | 33        | 0.57%   |
| Gigabyte B450      | 30        | 0.52%   |
| Acer Nitro         | 25        | 0.43%   |
| Lenovo ThinkBook   | 24        | 0.41%   |
| HP OMEN            | 24        | 0.41%   |
| Lenovo ThinkCentre | 23        | 0.4%    |
| ASRock B450M       | 23        | 0.4%    |
| Fujitsu LIFEBOOK   | 22        | 0.38%   |
| MSI MS-7C37        | 21        | 0.36%   |
| MSI MS-7C02        | 21        | 0.36%   |
| Lenovo IdeaPadFlex | 21        | 0.36%   |
| HP Notebook        | 20        | 0.34%   |
| ASUS ASUS          | 20        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 803       | 13.81%  |
| 2018    | 762       | 13.1%   |
| 2020    | 743       | 12.78%  |
| 2017    | 507       | 8.72%   |
| 2012    | 443       | 7.62%   |
| 2021    | 377       | 6.48%   |
| 2013    | 357       | 6.14%   |
| 2014    | 328       | 5.64%   |
| 2016    | 311       | 5.35%   |
| 2015    | 308       | 5.3%    |
| 2011    | 307       | 5.28%   |
| 2010    | 189       | 3.25%   |
| 2009    | 119       | 2.05%   |
| 2008    | 113       | 1.94%   |
| 2007    | 63        | 1.08%   |
| 2022    | 57        | 0.98%   |
| 2006    | 19        | 0.33%   |
| 2005    | 5         | 0.09%   |
| Unknown | 5         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 3229      | 55.52%  |
| Desktop     | 2231      | 38.36%  |
| Convertible | 204       | 3.51%   |
| Mini pc     | 64        | 1.1%    |
| All in one  | 40        | 0.69%   |
| Tablet      | 39        | 0.67%   |
| Server      | 8         | 0.14%   |
| Phone       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5813      | 99.91%  |
| Enabled  | 5         | 0.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5775      | 99.3%   |
| Yes  | 41        | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1614      | 27.37%  |
| 4.01-8.0        | 1319      | 22.37%  |
| 8.01-16.0       | 1187      | 20.13%  |
| 3.01-4.0        | 696       | 11.8%   |
| 32.01-64.0      | 684       | 11.6%   |
| 64.01-256.0     | 141       | 2.39%   |
| 24.01-32.0      | 117       | 1.98%   |
| 1.01-2.0        | 103       | 1.75%   |
| 2.01-3.0        | 32        | 0.54%   |
| More than 256.0 | 2         | 0.03%   |
| 0.51-1.0        | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 1688      | 26.18%  |
| 1.01-2.0        | 1634      | 25.35%  |
| 4.01-8.0        | 1355      | 21.02%  |
| 3.01-4.0        | 1068      | 16.57%  |
| 8.01-16.0       | 400       | 6.2%    |
| 0.51-1.0        | 206       | 3.2%    |
| 16.01-24.0      | 50        | 0.78%   |
| 0.01-0.5        | 19        | 0.29%   |
| 24.01-32.0      | 14        | 0.22%   |
| 32.01-64.0      | 11        | 0.17%   |
| More than 256.0 | 1         | 0.02%   |
| 64.01-256.0     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3025      | 50.48%  |
| 2      | 1714      | 28.6%   |
| 3      | 606       | 10.11%  |
| 4      | 316       | 5.27%   |
| 5      | 175       | 2.92%   |
| 6      | 67        | 1.12%   |
| 7      | 36        | 0.6%    |
| 0      | 28        | 0.47%   |
| 8      | 11        | 0.18%   |
| 9      | 7         | 0.12%   |
| 11     | 4         | 0.07%   |
| 12     | 2         | 0.03%   |
| 10     | 2         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4183      | 71.22%  |
| Yes       | 1690      | 28.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4876      | 83.65%  |
| No        | 953       | 16.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4568      | 78.13%  |
| No        | 1279      | 21.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3845      | 65.49%  |
| No        | 2026      | 34.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 973       | 16.64%  |
| Germany      | 679       | 11.61%  |
| Russia       | 534       | 9.13%   |
| Brazil       | 336       | 5.74%   |
| France       | 211       | 3.61%   |
| UK           | 207       | 3.54%   |
| Canada       | 189       | 3.23%   |
| Italy        | 188       | 3.21%   |
| Spain        | 172       | 2.94%   |
| Poland       | 172       | 2.94%   |
| Ukraine      | 141       | 2.41%   |
| Netherlands  | 124       | 2.12%   |
| India        | 109       | 1.86%   |
| Australia    | 85        | 1.45%   |
| Mexico       | 83        | 1.42%   |
| Austria      | 82        | 1.4%    |
| Sweden       | 81        | 1.38%   |
| China        | 61        | 1.04%   |
| Belgium      | 57        | 0.97%   |
| Turkey       | 55        | 0.94%   |
| Switzerland  | 55        | 0.94%   |
| Finland      | 54        | 0.92%   |
| Romania      | 53        | 0.91%   |
| Portugal     | 48        | 0.82%   |
| Czechia      | 46        | 0.79%   |
| Greece       | 44        | 0.75%   |
| Norway       | 43        | 0.74%   |
| Indonesia    | 43        | 0.74%   |
| Hungary      | 42        | 0.72%   |
| Argentina    | 42        | 0.72%   |
| Bulgaria     | 38        | 0.65%   |
| Belarus      | 38        | 0.65%   |
| Denmark      | 33        | 0.56%   |
| Bangladesh   | 27        | 0.46%   |
| South Africa | 26        | 0.44%   |
| Colombia     | 26        | 0.44%   |
| Taiwan       | 25        | 0.43%   |
| Chile        | 25        | 0.43%   |
| Ireland      | 24        | 0.41%   |
| Israel       | 23        | 0.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 120       | 1.95%   |
| St Petersburg     | 68        | 1.11%   |
| Vienna            | 51        | 0.83%   |
| Paris             | 44        | 0.72%   |
| Berlin            | 43        | 0.7%    |
| Kyiv              | 41        | 0.67%   |
| Sao Paulo         | 38        | 0.62%   |
| Warsaw            | 37        | 0.6%    |
| Amsterdam         | 32        | 0.52%   |
| Toronto           | 28        | 0.46%   |
| Milan             | 28        | 0.46%   |
| Madrid            | 27        | 0.44%   |
| Frankfurt am Main | 26        | 0.42%   |
| Munich            | 25        | 0.41%   |
| Helsinki          | 25        | 0.41%   |
| Stockholm         | 24        | 0.39%   |
| Rome              | 24        | 0.39%   |
| Hamburg           | 24        | 0.39%   |
| Athens            | 24        | 0.39%   |
| Minsk             | 22        | 0.36%   |
| Barcelona         | 22        | 0.36%   |
| Novosibirsk       | 21        | 0.34%   |
| Istanbul          | 21        | 0.34%   |
| Melbourne         | 20        | 0.33%   |
| Krakow            | 20        | 0.33%   |
| Bucharest         | 20        | 0.33%   |
| Bengaluru         | 20        | 0.33%   |
| Sofia             | 19        | 0.31%   |
| Sydney            | 18        | 0.29%   |
| Dhaka             | 18        | 0.29%   |
| Cologne           | 18        | 0.29%   |
| Yekaterinburg     | 17        | 0.28%   |
| Rio de Janeiro    | 17        | 0.28%   |
| Prague            | 17        | 0.28%   |
| London            | 17        | 0.28%   |
| Montreal          | 16        | 0.26%   |
| Mexico City       | 16        | 0.26%   |
| Los Angeles       | 16        | 0.26%   |
| Budapest          | 16        | 0.26%   |
| Atlanta           | 16        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1656      | 2514   | 17.23%  |
| WDC                       | 1407      | 2100   | 14.64%  |
| Seagate                   | 1341      | 1998   | 13.96%  |
| Toshiba                   | 640       | 772    | 6.66%   |
| Kingston                  | 570       | 740    | 5.93%   |
| SanDisk                   | 529       | 675    | 5.51%   |
| Crucial                   | 416       | 582    | 4.33%   |
| Unknown                   | 299       | 389    | 3.11%   |
| Intel                     | 268       | 356    | 2.79%   |
| SK hynix                  | 264       | 315    | 2.75%   |
| Hitachi                   | 215       | 285    | 2.24%   |
| HGST                      | 193       | 254    | 2.01%   |
| Micron Technology         | 144       | 176    | 1.5%    |
| A-DATA Technology         | 132       | 169    | 1.37%   |
| Phison                    | 126       | 172    | 1.31%   |
| China                     | 77        | 100    | 0.8%    |
| Apple                     | 68        | 82     | 0.71%   |
| KIOXIA                    | 65        | 74     | 0.68%   |
| Silicon Motion            | 57        | 73     | 0.59%   |
| Transcend                 | 54        | 60     | 0.56%   |
| PNY                       | 49        | 71     | 0.51%   |
| OCZ                       | 47        | 59     | 0.49%   |
| Micron/Crucial Technology | 45        | 54     | 0.47%   |
| SPCC                      | 44        | 53     | 0.46%   |
| XPG                       | 43        | 54     | 0.45%   |
| Patriot                   | 43        | 49     | 0.45%   |
| Intenso                   | 42        | 58     | 0.44%   |
| GOODRAM                   | 40        | 60     | 0.42%   |
| JMicron Technology        | 38        | 46     | 0.4%    |
| Corsair                   | 34        | 45     | 0.35%   |
| Plextor                   | 33        | 44     | 0.34%   |
| LITEONIT                  | 32        | 37     | 0.33%   |
| LITEON                    | 30        | 33     | 0.31%   |
| Lexar                     | 22        | 24     | 0.23%   |
| Team                      | 21        | 27     | 0.22%   |
| Realtek Semiconductor     | 20        | 26     | 0.21%   |
| Apacer                    | 20        | 22     | 0.21%   |
| Hewlett-Packard           | 18        | 25     | 0.19%   |
| Phison Electronics        | 16        | 17     | 0.17%   |
| Fujitsu                   | 16        | 16     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 119       | 1.11%   |
| Seagate ST1000LM035-1RK172 1TB         | 98        | 0.91%   |
| Samsung SSD 860 EVO 500GB              | 98        | 0.91%   |
| Samsung NVMe SSD Drive 512GB           | 85        | 0.79%   |
| Samsung NVMe SSD Drive 500GB           | 83        | 0.77%   |
| Samsung NVMe SSD Drive 1TB             | 82        | 0.76%   |
| Samsung SSD 850 EVO 500GB              | 81        | 0.75%   |
| Kingston SA400S37120G 120GB SSD        | 76        | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB         | 73        | 0.68%   |
| Samsung SSD 850 EVO 250GB              | 73        | 0.68%   |
| Crucial CT500MX500SSD1 500GB           | 69        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB         | 65        | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 62        | 0.58%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 61        | 0.57%   |
| Samsung SSD 860 EVO 1TB                | 59        | 0.55%   |
| Toshiba MQ01ABD100 1TB                 | 58        | 0.54%   |
| Kingston SA400S37480G 480GB SSD        | 56        | 0.52%   |
| HGST HTS721010A9E630 1TB               | 56        | 0.52%   |
| SK hynix NVMe SSD Drive 512GB          | 55        | 0.51%   |
| Samsung SSD 860 EVO 250GB              | 55        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB            | 53        | 0.49%   |
| Toshiba MQ04ABF100 1TB                 | 52        | 0.48%   |
| Toshiba DT01ACA100 1TB                 | 52        | 0.48%   |
| SanDisk NVMe SSD Drive 512GB           | 52        | 0.48%   |
| Crucial CT240BX500SSD1 240GB           | 52        | 0.48%   |
| Seagate Expansion 1TB                  | 50        | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB               | 49        | 0.46%   |
| Toshiba MQ01ABF050 500GB               | 45        | 0.42%   |
| SanDisk NVMe SSD Drive 500GB           | 45        | 0.42%   |
| Unknown SD/MMC/MS PRO 8GB              | 44        | 0.41%   |
| Intel NVMe SSD Drive 512GB             | 44        | 0.41%   |
| SanDisk NVMe SSD Drive 1TB             | 42        | 0.39%   |
| Unknown MMC Card  64GB                 | 39        | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB         | 39        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD       | 39        | 0.36%   |
| Seagate ST500DM002-1BD142 500GB        | 38        | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB         | 38        | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB         | 38        | 0.35%   |
| SanDisk NVMe SSD Drive 256GB           | 36        | 0.33%   |
| WDC WD10EZEX-00BN5A0 1TB               | 35        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1314      | 1949   | 36.62%  |
| WDC                 | 1110      | 1645   | 30.94%  |
| Toshiba             | 469       | 566    | 13.07%  |
| Hitachi             | 215       | 285    | 5.99%   |
| HGST                | 192       | 253    | 5.35%   |
| Samsung Electronics | 144       | 213    | 4.01%   |
| Unknown             | 50        | 61     | 1.39%   |
| Apple               | 17        | 22     | 0.47%   |
| Fujitsu             | 16        | 16     | 0.45%   |
| Maxtor              | 12        | 14     | 0.33%   |
| ASMT                | 11        | 15     | 0.31%   |
| Intenso             | 6         | 9      | 0.17%   |
| JMicron Technology  | 4         | 7      | 0.11%   |
| ASMedia             | 4         | 4      | 0.11%   |
| HGST HTS            | 3         | 3      | 0.08%   |
| Hewlett-Packard     | 3         | 3      | 0.08%   |
| USB3.0              | 2         | 2      | 0.06%   |
| USB                 | 2         | 2      | 0.06%   |
| Maxone              | 2         | 2      | 0.06%   |
| Apricorn            | 2         | 2      | 0.06%   |
| SABRENT             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| Lenovo              | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| IBM/Hitachi         | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 825       | 1163   | 24.98%  |
| Kingston            | 463       | 595    | 14.02%  |
| Crucial             | 375       | 532    | 11.35%  |
| SanDisk             | 273       | 356    | 8.27%   |
| WDC                 | 204       | 267    | 6.18%   |
| A-DATA Technology   | 103       | 130    | 3.12%   |
| Intel               | 90        | 114    | 2.72%   |
| China               | 76        | 99     | 2.3%    |
| Micron Technology   | 67        | 80     | 2.03%   |
| Toshiba             | 51        | 61     | 1.54%   |
| SK hynix            | 48        | 57     | 1.45%   |
| Transcend           | 47        | 52     | 1.42%   |
| OCZ                 | 47        | 59     | 1.42%   |
| PNY                 | 43        | 65     | 1.3%    |
| Patriot             | 40        | 46     | 1.21%   |
| GOODRAM             | 38        | 58     | 1.15%   |
| Apple               | 37        | 42     | 1.12%   |
| SPCC                | 33        | 41     | 1%      |
| LITEONIT            | 32        | 37     | 0.97%   |
| Plextor             | 30        | 41     | 0.91%   |
| Intenso             | 29        | 40     | 0.88%   |
| LITEON              | 24        | 27     | 0.73%   |
| Corsair             | 23        | 32     | 0.7%    |
| Lexar               | 21        | 23     | 0.64%   |
| Apacer              | 19        | 21     | 0.58%   |
| Team                | 17        | 23     | 0.51%   |
| Seagate             | 15        | 22     | 0.45%   |
| JMicron Technology  | 15        | 16     | 0.45%   |
| KingSpec            | 13        | 14     | 0.39%   |
| KingDian            | 11        | 11     | 0.33%   |
| Gigabyte Technology | 9         | 13     | 0.27%   |
| TO Exter            | 8         | 10     | 0.24%   |
| Netac               | 8         | 13     | 0.24%   |
| Leven               | 8         | 9      | 0.24%   |
| Hewlett-Packard     | 8         | 11     | 0.24%   |
| Mushkin             | 7         | 8      | 0.21%   |
| NGFF                | 6         | 6      | 0.18%   |
| Hoodisk             | 6         | 6      | 0.18%   |
| Unknown             | 6         | 6      | 0.18%   |
| USB3.0              | 5         | 5      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2903      | 5083   | 34.53%  |
| SSD     | 2795      | 4364   | 33.25%  |
| NVMe    | 2343      | 3311   | 27.87%  |
| MMC     | 231       | 299    | 2.75%   |
| Unknown | 135       | 166    | 1.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4309      | 9075   | 59.25%  |
| NVMe | 2334      | 3282   | 32.09%  |
| SAS  | 399       | 567    | 5.49%   |
| MMC  | 231       | 299    | 3.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3153      | 5106   | 51.71%  |
| 0.51-1.0   | 1974      | 2860   | 32.37%  |
| 1.01-2.0   | 556       | 805    | 9.12%   |
| 3.01-4.0   | 155       | 247    | 2.54%   |
| 4.01-10.0  | 126       | 220    | 2.07%   |
| 2.01-3.0   | 120       | 185    | 1.97%   |
| 10.01-20.0 | 13        | 23     | 0.21%   |
| 20.01-50.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1442      | 23.66%  |
| 251-500        | 1343      | 22.04%  |
| 501-1000       | 964       | 15.82%  |
| 1001-2000      | 682       | 11.19%  |
| More than 3000 | 397       | 6.51%   |
| Unknown        | 335       | 5.5%    |
| 51-100         | 331       | 5.43%   |
| 2001-3000      | 262       | 4.3%    |
| 1-20           | 181       | 2.97%   |
| 21-50          | 157       | 2.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1296      | 20.42%  |
| 101-250        | 1047      | 16.5%   |
| 21-50          | 1029      | 16.21%  |
| 51-100         | 867       | 13.66%  |
| 251-500        | 667       | 10.51%  |
| 501-1000       | 521       | 8.21%   |
| Unknown        | 335       | 5.28%   |
| 1001-2000      | 309       | 4.87%   |
| More than 3000 | 160       | 2.52%   |
| 2001-3000      | 112       | 1.76%   |
| 0              | 4         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 11        | 12     | 2.13%   |
| HGST HTS545050A7E680 500GB                          | 9         | 9      | 1.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 8         | 8      | 1.55%   |
| HGST HTS721010A9E630 1TB                            | 8         | 8      | 1.55%   |
| Seagate ST500DM002-1BD142 500GB                     | 7         | 9      | 1.36%   |
| HGST HTS545050A7E380 500GB                          | 7         | 7      | 1.36%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 8      | 1.16%   |
| Toshiba MQ01ABD050 500GB                            | 6         | 6      | 1.16%   |
| WDC WD5000AAKX-001CA0 500GB                         | 5         | 7      | 0.97%   |
| WDC WD10EARS-00Y5B1 1TB                             | 5         | 5      | 0.97%   |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 22     | 0.97%   |
| Samsung Electronics HD103SJ 1TB                     | 5         | 5      | 0.97%   |
| Hitachi HDS721010CLA332 1TB                         | 5         | 5      | 0.97%   |
| Seagate ST9320325AS 320GB                           | 4         | 5      | 0.78%   |
| Seagate ST3500413AS 500GB                           | 4         | 5      | 0.78%   |
| Seagate ST1000DX001-1CM162 1TB                      | 4         | 6      | 0.78%   |
| Samsung Electronics SSD 960 EVO 250GB               | 4         | 5      | 0.78%   |
| Samsung Electronics HD103UJ 1TB                     | 4         | 6      | 0.78%   |
| Hitachi HTS723232A7A364 320GB                       | 4         | 4      | 0.78%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 0.78%   |
| HGST HTS541010A9E680 1TB                            | 4         | 4      | 0.78%   |
| Crucial CT525MX300SSD1 528GB                        | 4         | 4      | 0.78%   |
| WDC WD15EARS-00MVWB0 1TB                            | 3         | 3      | 0.58%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 0.58%   |
| WDC WD10EZEX-00RKKA0 1TB                            | 3         | 3      | 0.58%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3         | 3      | 0.58%   |
| WDC WD10EARX-00N0YB0 1TB                            | 3         | 4      | 0.58%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 3         | 3      | 0.58%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 3      | 0.58%   |
| Seagate ST9750420AS 752GB                           | 3         | 3      | 0.58%   |
| Seagate ST9500325AS 500GB                           | 3         | 4      | 0.58%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 0.58%   |
| Seagate ST4000DM000-1F2168 4TB                      | 3         | 7      | 0.58%   |
| Seagate ST2000DM001-1CH164 2TB                      | 3         | 3      | 0.58%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 3         | 3      | 0.58%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 3         | 3      | 0.58%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 0.58%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 3      | 0.58%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 3      | 0.58%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 0.58%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 134       | 197    | 26.69%  |
| WDC                 | 120       | 138    | 23.9%   |
| Hitachi             | 38        | 41     | 7.57%   |
| HGST                | 38        | 38     | 7.57%   |
| Samsung Electronics | 36        | 43     | 7.17%   |
| Toshiba             | 34        | 40     | 6.77%   |
| Crucial             | 15        | 18     | 2.99%   |
| Kingston            | 14        | 14     | 2.79%   |
| Intel               | 14        | 16     | 2.79%   |
| SanDisk             | 12        | 15     | 2.39%   |
| SK hynix            | 7         | 12     | 1.39%   |
| A-DATA Technology   | 7         | 8      | 1.39%   |
| Micron Technology   | 5         | 7      | 1%      |
| LITEON              | 3         | 3      | 0.6%    |
| Transcend           | 2         | 2      | 0.4%    |
| OCZ                 | 2         | 2      | 0.4%    |
| Corsair             | 2         | 6      | 0.4%    |
| ASMT                | 2         | 6      | 0.4%    |
| Apacer              | 2         | 2      | 0.4%    |
| SPCC                | 1         | 1      | 0.2%    |
| Phison              | 1         | 2      | 0.2%    |
| Patriot             | 1         | 1      | 0.2%    |
| Maxtor              | 1         | 1      | 0.2%    |
| MaxDigital          | 1         | 1      | 0.2%    |
| LITEONIT            | 1         | 1      | 0.2%    |
| KingSpec            | 1         | 1      | 0.2%    |
| Intenso             | 1         | 4      | 0.2%    |
| IM3D                | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| Fujitsu             | 1         | 1      | 0.2%    |
| Faspeed             | 1         | 1      | 0.2%    |
| Drevo               | 1         | 1      | 0.2%    |
| Apple               | 1         | 1      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 133       | 194    | 34.91%  |
| WDC                 | 118       | 136    | 30.97%  |
| Hitachi             | 38        | 41     | 9.97%   |
| HGST                | 38        | 38     | 9.97%   |
| Toshiba             | 30        | 36     | 7.87%   |
| Samsung Electronics | 20        | 25     | 5.25%   |
| Maxtor              | 1         | 1      | 0.26%   |
| MaxDigital          | 1         | 1      | 0.26%   |
| Fujitsu             | 1         | 1      | 0.26%   |
| ASMT                | 1         | 1      | 0.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 361       | 474    | 75.37%  |
| SSD  | 99        | 131    | 20.67%  |
| NVMe | 19        | 22     | 3.97%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB                     | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-24ZEST0 320GB                     | 1         | 1      | 6.67%   |
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 6.67%   |
| WDC WD1600AAJS-65WAA0 160GB                      | 1         | 1      | 6.67%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 6.67%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 6.67%   |
| Toshiba MK1059GSM 1TB                            | 1         | 1      | 6.67%   |
| Seagate ST9640320AS 640GB                        | 1         | 1      | 6.67%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 6.67%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 6.67%   |
| Seagate ST31000524AS 1TB                         | 1         | 2      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 6.67%   |
| Samsung Electronics HD321HJ 320GB                | 1         | 1      | 6.67%   |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 6.67%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 33.33%  |
| Seagate             | 4         | 5      | 26.67%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Kingston            | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3684      | 8004   | 56.96%  |
| Works    | 2308      | 4576   | 35.68%  |
| Malfunc  | 461       | 627    | 7.13%   |
| Failed   | 15        | 16     | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3522      | 45%     |
| AMD                              | 1548      | 19.78%  |
| Samsung Electronics              | 879       | 11.23%  |
| SanDisk                          | 387       | 4.94%   |
| SK hynix                         | 213       | 2.72%   |
| Phison Electronics               | 163       | 2.08%   |
| ASMedia Technology               | 145       | 1.85%   |
| Kingston Technology Company      | 122       | 1.56%   |
| Toshiba America Info Systems     | 114       | 1.46%   |
| Micron/Crucial Technology        | 87        | 1.11%   |
| KIOXIA                           | 77        | 0.98%   |
| Micron Technology                | 76        | 0.97%   |
| Silicon Motion                   | 74        | 0.95%   |
| Marvell Technology Group         | 69        | 0.88%   |
| ADATA Technology                 | 67        | 0.86%   |
| JMicron Technology               | 56        | 0.72%   |
| Nvidia                           | 55        | 0.7%    |
| Realtek Semiconductor            | 35        | 0.45%   |
| Union Memory (Shenzhen)          | 26        | 0.33%   |
| Lite-On Technology               | 16        | 0.2%    |
| Solid State Storage Technology   | 14        | 0.18%   |
| Apple                            | 14        | 0.18%   |
| Shenzhen Longsys Electronics     | 8         | 0.1%    |
| Seagate Technology               | 8         | 0.1%    |
| LSI Logic / Symbios Logic        | 8         | 0.1%    |
| VIA Technologies                 | 7         | 0.09%   |
| Silicon Image                    | 6         | 0.08%   |
| Lenovo                           | 5         | 0.06%   |
| Broadcom / LSI                   | 4         | 0.05%   |
| Adaptec                          | 4         | 0.05%   |
| Integrated Technology Express    | 3         | 0.04%   |
| Biwin Storage Technology         | 3         | 0.04%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| Transcend                        | 2         | 0.03%   |
| Silicon Integrated Systems [SiS] | 2         | 0.03%   |
| PMC-Sierra                       | 1         | 0.01%   |
| OCZ Technology Group             | 1         | 0.01%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.01%   |
| INNOGRIT                         | 1         | 0.01%   |
| HighPoint Technologies           | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1173      | 13.2%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 509       | 5.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 344       | 3.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 313       | 3.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 249       | 2.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 241       | 2.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 217       | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 154       | 1.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 151       | 1.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 148       | 1.67%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 143       | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 133       | 1.5%    |
| Samsung NVMe SSD Controller 980                                                | 129       | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 128       | 1.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 127       | 1.43%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 125       | 1.41%   |
| AMD 500 Series Chipset SATA Controller                                         | 123       | 1.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 118       | 1.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 117       | 1.32%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 109       | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 103       | 1.16%   |
| Intel SSD 660P Series                                                          | 101       | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 100       | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 98        | 1.1%    |
| AMD 300 Series Chipset SATA Controller                                         | 84        | 0.95%   |
| Phison E12 NVMe Controller                                                     | 82        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 79        | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 78        | 0.88%   |
| Intel Volume Management Device NVMe RAID Controller                            | 77        | 0.87%   |
| Intel SATA Controller [RAID mode]                                              | 77        | 0.87%   |
| Micron Non-Volatile memory controller                                          | 76        | 0.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 75        | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 74        | 0.83%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 65        | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 64        | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 62        | 0.7%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 60        | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 60        | 0.68%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 56        | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 54        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4477      | 58.14%  |
| NVMe | 2346      | 30.47%  |
| IDE  | 449       | 5.83%   |
| RAID | 409       | 5.31%   |
| SAS  | 16        | 0.21%   |
| SCSI | 3         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3966      | 68.19%  |
| AMD    | 1849      | 31.79%  |
| ARM    | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 113       | 1.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 89        | 1.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 73        | 1.25%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 73        | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 71        | 1.22%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 68        | 1.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 67        | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 67        | 1.15%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 67        | 1.15%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 62        | 1.06%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 60        | 1.03%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 57        | 0.98%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 55        | 0.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 54        | 0.93%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 52        | 0.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 51        | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 51        | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 46        | 0.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 45        | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 44        | 0.75%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 44        | 0.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 42        | 0.72%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 41        | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 38        | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 36        | 0.62%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 35        | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 34        | 0.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 33        | 0.57%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 32        | 0.55%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 30        | 0.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 30        | 0.51%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 28        | 0.48%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 27        | 0.46%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 27        | 0.46%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 27        | 0.46%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 27        | 0.46%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 27        | 0.46%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 27        | 0.46%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 27        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1354      | 23.24%  |
| Intel Core i7           | 1263      | 21.68%  |
| AMD Ryzen 5             | 611       | 10.49%  |
| AMD Ryzen 7             | 486       | 8.34%   |
| Intel Core i3           | 366       | 6.28%   |
| Other                   | 239       | 4.1%    |
| Intel Celeron           | 188       | 3.23%   |
| Intel Core 2 Duo        | 131       | 2.25%   |
| AMD Ryzen 9             | 127       | 2.18%   |
| Intel Pentium           | 114       | 1.96%   |
| Intel Xeon              | 113       | 1.94%   |
| AMD FX                  | 104       | 1.79%   |
| AMD Ryzen 3             | 91        | 1.56%   |
| Intel Atom              | 45        | 0.77%   |
| Intel Pentium Dual-Core | 40        | 0.69%   |
| AMD Ryzen 7 PRO         | 38        | 0.65%   |
| Intel Core i9           | 37        | 0.64%   |
| AMD A8                  | 37        | 0.64%   |
| AMD A10                 | 37        | 0.64%   |
| AMD A4                  | 33        | 0.57%   |
| AMD A6                  | 29        | 0.5%    |
| AMD Ryzen Threadripper  | 27        | 0.46%   |
| AMD Phenom II X4        | 25        | 0.43%   |
| Intel Core 2 Quad       | 23        | 0.39%   |
| Intel Core 2            | 20        | 0.34%   |
| AMD E1                  | 18        | 0.31%   |
| AMD Athlon II X2        | 18        | 0.31%   |
| AMD Athlon              | 18        | 0.31%   |
| AMD E                   | 17        | 0.29%   |
| Intel Pentium Silver    | 16        | 0.27%   |
| AMD Athlon 64 X2        | 12        | 0.21%   |
| AMD Ryzen 5 PRO         | 11        | 0.19%   |
| AMD Phenom II X6        | 11        | 0.19%   |
| Intel Pentium Gold      | 9         | 0.15%   |
| Intel Genuine           | 9         | 0.15%   |
| AMD Athlon II X4        | 9         | 0.15%   |
| AMD E2                  | 8         | 0.14%   |
| AMD Athlon X4           | 8         | 0.14%   |
| AMD Turion 64 X2 Mobile | 7         | 0.12%   |
| AMD Phenom              | 7         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2195      | 37.7%   |
| 2       | 1873      | 32.17%  |
| 6       | 856       | 14.7%   |
| 8       | 624       | 10.72%  |
| 12      | 100       | 1.72%   |
| 16      | 55        | 0.94%   |
| 3       | 41        | 0.7%    |
| 1       | 40        | 0.69%   |
| 10      | 17        | 0.29%   |
| 14      | 8         | 0.14%   |
| 32      | 5         | 0.09%   |
| 24      | 4         | 0.07%   |
| Unknown | 3         | 0.05%   |
| 20      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 5796      | 99.66%  |
| 2      | 19        | 0.33%   |
| 4      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4369      | 75.02%  |
| 1       | 1452      | 24.93%  |
| Unknown | 3         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5720      | 98.23%  |
| Unknown        | 102       | 1.75%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2866      | 47.65%  |
| 0x306a9    | 201       | 3.34%   |
| 0x906ea    | 170       | 2.83%   |
| 0x306c3    | 156       | 2.59%   |
| 0x206a7    | 137       | 2.28%   |
| 0x08701021 | 125       | 2.08%   |
| 0x806ea    | 120       | 2%      |
| 0x806ec    | 119       | 1.98%   |
| 0x0800820d | 97        | 1.61%   |
| 0x806c1    | 91        | 1.51%   |
| 0x806e9    | 88        | 1.46%   |
| 0x906e9    | 84        | 1.4%    |
| 0x506e3    | 80        | 1.33%   |
| 0x406e3    | 76        | 1.26%   |
| 0x08701013 | 75        | 1.25%   |
| 0x40651    | 74        | 1.23%   |
| 0x08108102 | 65        | 1.08%   |
| 0x1067a    | 62        | 1.03%   |
| 0x08600106 | 61        | 1.01%   |
| 0x306d4    | 59        | 0.98%   |
| 0x08108109 | 59        | 0.98%   |
| 0x0a50000c | 52        | 0.86%   |
| 0x706e5    | 46        | 0.76%   |
| 0x08600103 | 45        | 0.75%   |
| 0x06000852 | 45        | 0.75%   |
| 0x806eb    | 42        | 0.7%    |
| 0x08600104 | 42        | 0.7%    |
| 0xa0652    | 41        | 0.68%   |
| 0x20655    | 30        | 0.5%    |
| 0x08608103 | 30        | 0.5%    |
| 0x08001138 | 29        | 0.48%   |
| 0x0810100b | 26        | 0.43%   |
| 0x010000c8 | 25        | 0.42%   |
| 0x406c4    | 23        | 0.38%   |
| 0x08600102 | 23        | 0.38%   |
| 0x306f2    | 22        | 0.37%   |
| 0x06001119 | 22        | 0.37%   |
| 0x506c9    | 21        | 0.35%   |
| 0x0a201009 | 21        | 0.35%   |
| 0x906ed    | 19        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1160      | 19.92%  |
| Zen 2            | 553       | 9.5%    |
| Haswell          | 522       | 8.96%   |
| IvyBridge        | 392       | 6.73%   |
| Zen+             | 386       | 6.63%   |
| SandyBridge      | 344       | 5.91%   |
| Skylake          | 316       | 5.43%   |
| Zen 3            | 209       | 3.59%   |
| Zen              | 196       | 3.37%   |
| Penryn           | 177       | 3.04%   |
| TigerLake        | 150       | 2.58%   |
| Broadwell        | 150       | 2.58%   |
| CometLake        | 136       | 2.34%   |
| Piledriver       | 134       | 2.3%    |
| Unknown          | 123       | 2.11%   |
| Westmere         | 116       | 1.99%   |
| Silvermont       | 110       | 1.89%   |
| IceLake          | 93        | 1.6%    |
| K10              | 84        | 1.44%   |
| Core             | 68        | 1.17%   |
| Goldmont plus    | 64        | 1.1%    |
| Excavator        | 62        | 1.06%   |
| Goldmont         | 44        | 0.76%   |
| Nehalem          | 42        | 0.72%   |
| Bobcat           | 30        | 0.52%   |
| Steamroller      | 25        | 0.43%   |
| K8 Hammer        | 23        | 0.39%   |
| Puma             | 22        | 0.38%   |
| Jaguar           | 22        | 0.38%   |
| Bulldozer        | 17        | 0.29%   |
| K10 Llano        | 14        | 0.24%   |
| Alderlake Hybrid | 14        | 0.24%   |
| Bonnell          | 12        | 0.21%   |
| NetBurst         | 6         | 0.1%    |
| K8 & K10 hybrid  | 5         | 0.09%   |
| Tremont          | 3         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 3016      | 42.28%  |
| Nvidia                     | 2320      | 32.52%  |
| AMD                        | 1788      | 25.07%  |
| ASPEED Technology          | 5         | 0.07%   |
| ATI Technologies           | 3         | 0.04%   |
| Matrox Electronics Systems | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 238       | 3.26%   |
| AMD Renoir                                                                               | 233       | 3.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 223       | 3.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 207       | 2.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 197       | 2.7%    |
| Intel UHD Graphics 620                                                                   | 190       | 2.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 188       | 2.58%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 162       | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 160       | 2.19%   |
| Intel HD Graphics 620                                                                    | 138       | 1.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 132       | 1.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 118       | 1.62%   |
| Intel HD Graphics 5500                                                                   | 118       | 1.62%   |
| Intel HD Graphics 630                                                                    | 112       | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 105       | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 105       | 1.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 91        | 1.25%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 86        | 1.18%   |
| Intel HD Graphics 530                                                                    | 84        | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 83        | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 79        | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 76        | 1.04%   |
| Intel Core Processor Integrated Graphics Controller                                      | 69        | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 69        | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 66        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 66        | 0.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 60        | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 58        | 0.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 58        | 0.8%    |
| AMD Lucienne                                                                             | 58        | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 55        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 55        | 0.75%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 52        | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 51        | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 47        | 0.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 46        | 0.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 45        | 0.62%   |
| Nvidia GP108M [GeForce MX150]                                                            | 44        | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 43        | 0.59%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 41        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1896      | 32.36%  |
| 1 x AMD            | 1414      | 24.13%  |
| 1 x Nvidia         | 1203      | 20.53%  |
| Intel + Nvidia     | 926       | 15.8%   |
| AMD + Nvidia       | 161       | 2.75%   |
| Intel + AMD        | 130       | 2.22%   |
| 2 x AMD            | 91        | 1.55%   |
| 2 x Nvidia         | 27        | 0.46%   |
| 1 x ASPEED         | 4         | 0.07%   |
| Other              | 2         | 0.03%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| Nvidia + ASPEED    | 1         | 0.02%   |
| 1 x Matrox         | 1         | 0.02%   |
| Intel + 2 x AMD    | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4266      | 72.51%  |
| Proprietary | 1605      | 27.28%  |
| Unknown     | 12        | 0.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3675      | 61.95%  |
| 1.01-2.0   | 529       | 8.92%   |
| 7.01-8.0   | 383       | 6.46%   |
| 0.01-0.5   | 378       | 6.37%   |
| 3.01-4.0   | 349       | 5.88%   |
| 0.51-1.0   | 248       | 4.18%   |
| 5.01-6.0   | 222       | 3.74%   |
| 8.01-16.0  | 85        | 1.43%   |
| 2.01-3.0   | 51        | 0.86%   |
| 16.01-24.0 | 10        | 0.17%   |
| 4.01-5.0   | 2         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 754       | 10.95%  |
| AU Optronics            | 727       | 10.56%  |
| LG Display              | 623       | 9.05%   |
| BOE                     | 603       | 8.76%   |
| Chimei Innolux          | 597       | 8.67%   |
| Goldstar                | 412       | 5.98%   |
| Dell                    | 375       | 5.45%   |
| Acer                    | 259       | 3.76%   |
| BenQ                    | 206       | 2.99%   |
| AOC                     | 205       | 2.98%   |
| Ancor Communications    | 203       | 2.95%   |
| Hewlett-Packard         | 169       | 2.45%   |
| Philips                 | 156       | 2.27%   |
| Sharp                   | 144       | 2.09%   |
| Lenovo                  | 111       | 1.61%   |
| Apple                   | 102       | 1.48%   |
| LG Electronics          | 93        | 1.35%   |
| PANDA                   | 88        | 1.28%   |
| ViewSonic               | 82        | 1.19%   |
| Chi Mei Optoelectronics | 75        | 1.09%   |
| ASUSTek Computer        | 71        | 1.03%   |
| Iiyama                  | 54        | 0.78%   |
| Unknown                 | 43        | 0.62%   |
| Sony                    | 37        | 0.54%   |
| InfoVision              | 37        | 0.54%   |
| Vizio                   | 24        | 0.35%   |
| Panasonic               | 23        | 0.33%   |
| MSI                     | 21        | 0.3%    |
| Eizo                    | 21        | 0.3%    |
| CSO                     | 21        | 0.3%    |
| Unknown                 | 21        | 0.3%    |
| NEC Computers           | 19        | 0.28%   |
| Fujitsu Siemens         | 19        | 0.28%   |
| LGD                     | 17        | 0.25%   |
| AUS                     | 17        | 0.25%   |
| Sceptre Tech            | 16        | 0.23%   |
| TMX                     | 15        | 0.22%   |
| Toshiba                 | 14        | 0.2%    |
| Medion                  | 13        | 0.19%   |
| LG Philips              | 13        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 42        | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 41        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 35        | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 29        | 0.4%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 28        | 0.39%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 27        | 0.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 25        | 0.35%   |
| Unknown                                                                  | 21        | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 20        | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 20        | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 19        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 19        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 17        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 17        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 17        | 0.24%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 17        | 0.24%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 15        | 0.21%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 15        | 0.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 14        | 0.2%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 13        | 0.18%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 13        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 13        | 0.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.18%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 13        | 0.18%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.17%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.17%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 11        | 0.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 11        | 0.15%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 11        | 0.15%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                    | 11        | 0.15%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 11        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.15%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 11        | 0.15%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 11        | 0.15%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                       | 11        | 0.15%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 11        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3146      | 48.08%  |
| 1366x768 (WXGA)    | 987       | 15.08%  |
| 3840x2160 (4K)     | 436       | 6.66%   |
| 2560x1440 (QHD)    | 353       | 5.4%    |
| 1600x900 (HD+)     | 191       | 2.92%   |
| Unknown            | 163       | 2.49%   |
| 1680x1050 (WSXGA+) | 145       | 2.22%   |
| 1920x1200 (WUXGA)  | 141       | 2.15%   |
| 1280x1024 (SXGA)   | 126       | 1.93%   |
| 1440x900 (WXGA+)   | 119       | 1.82%   |
| 2560x1080          | 90        | 1.38%   |
| 3440x1440          | 80        | 1.22%   |
| 3840x1080          | 77        | 1.18%   |
| 1280x800 (WXGA)    | 77        | 1.18%   |
| 2560x1600          | 40        | 0.61%   |
| 1360x768           | 40        | 0.61%   |
| 2880x1800          | 29        | 0.44%   |
| 2160x1440          | 22        | 0.34%   |
| 3840x2400          | 20        | 0.31%   |
| 1920x540           | 16        | 0.24%   |
| 4480x1440          | 11        | 0.17%   |
| 3200x1800 (QHD+)   | 11        | 0.17%   |
| 1280x720 (HD)      | 11        | 0.17%   |
| 1024x768 (XGA)     | 10        | 0.15%   |
| 5120x1440          | 9         | 0.14%   |
| 3840x1600          | 9         | 0.14%   |
| 3456x2160          | 9         | 0.14%   |
| 3200x2000          | 9         | 0.14%   |
| 5760x1080          | 8         | 0.12%   |
| 2736x1824          | 8         | 0.12%   |
| 5760x2160          | 7         | 0.11%   |
| 3286x1080          | 7         | 0.11%   |
| 1600x1200          | 7         | 0.11%   |
| 3600x1080          | 6         | 0.09%   |
| 2256x1504          | 6         | 0.09%   |
| 1920x1280          | 6         | 0.09%   |
| 3200x1080          | 5         | 0.08%   |
| 3000x2000          | 5         | 0.08%   |
| 6400x2160          | 4         | 0.06%   |
| 3840x1200          | 4         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1733      | 25.61%  |
| 13      | 643       | 9.5%    |
| 24      | 531       | 7.85%   |
| 14      | 528       | 7.8%    |
| 27      | 525       | 7.76%   |
| Unknown | 511       | 7.55%   |
| 23      | 429       | 6.34%   |
| 21      | 355       | 5.25%   |
| 17      | 281       | 4.15%   |
| 31      | 149       | 2.2%    |
| 19      | 143       | 2.11%   |
| 34      | 133       | 1.97%   |
| 12      | 100       | 1.48%   |
| 22      | 95        | 1.4%    |
| 18      | 89        | 1.32%   |
| 20      | 74        | 1.09%   |
| 11      | 60        | 0.89%   |
| 84      | 47        | 0.69%   |
| 16      | 36        | 0.53%   |
| 32      | 31        | 0.46%   |
| 54      | 27        | 0.4%    |
| 72      | 26        | 0.38%   |
| 25      | 25        | 0.37%   |
| 48      | 17        | 0.25%   |
| 26      | 15        | 0.22%   |
| 49      | 14        | 0.21%   |
| 40      | 14        | 0.21%   |
| 37      | 12        | 0.18%   |
| 28      | 12        | 0.18%   |
| 65      | 11        | 0.16%   |
| 33      | 10        | 0.15%   |
| 43      | 9         | 0.13%   |
| 46      | 8         | 0.12%   |
| 35      | 7         | 0.1%    |
| 52      | 6         | 0.09%   |
| 42      | 6         | 0.09%   |
| 39      | 6         | 0.09%   |
| 29      | 6         | 0.09%   |
| 60      | 5         | 0.07%   |
| 36      | 5         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 2615      | 39.58%  |
| 501-600     | 1339      | 20.27%  |
| 401-500     | 666       | 10.08%  |
| Unknown     | 511       | 7.73%   |
| 201-300     | 481       | 7.28%   |
| 351-400     | 360       | 5.45%   |
| 601-700     | 217       | 3.28%   |
| 701-800     | 177       | 2.68%   |
| 1001-1500   | 96        | 1.45%   |
| 1501-2000   | 82        | 1.24%   |
| 801-900     | 44        | 0.67%   |
| 901-1000    | 15        | 0.23%   |
| 101-200     | 3         | 0.05%   |
| 1-100       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4545      | 75.45%  |
| 16/10   | 581       | 9.64%   |
| Unknown | 467       | 7.75%   |
| 21/9    | 150       | 2.49%   |
| 5/4     | 118       | 1.96%   |
| 3/2     | 80        | 1.33%   |
| 4/3     | 39        | 0.65%   |
| 32/9    | 26        | 0.43%   |
| 6/5     | 6         | 0.1%    |
| 0.62    | 3         | 0.05%   |
| 3.40    | 2         | 0.03%   |
| 3.20    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.80    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1738      | 25.93%  |
| 201-250        | 1133      | 16.9%   |
| 81-90          | 901       | 13.44%  |
| 301-350        | 534       | 7.97%   |
| Unknown        | 511       | 7.62%   |
| 351-500        | 343       | 5.12%   |
| 151-200        | 300       | 4.48%   |
| 71-80          | 273       | 4.07%   |
| 121-130        | 203       | 3.03%   |
| 251-300        | 188       | 2.8%    |
| More than 1000 | 147       | 2.19%   |
| 141-150        | 114       | 1.7%    |
| 61-70          | 86        | 1.28%   |
| 501-1000       | 85        | 1.27%   |
| 51-60          | 62        | 0.92%   |
| 131-140        | 36        | 0.54%   |
| 111-120        | 23        | 0.34%   |
| 91-100         | 17        | 0.25%   |
| 41-50          | 5         | 0.07%   |
| 1-40           | 4         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1916      | 29.5%   |
| 121-160       | 1900      | 29.25%  |
| 101-120       | 1467      | 22.59%  |
| Unknown       | 511       | 7.87%   |
| 161-240       | 403       | 6.2%    |
| More than 240 | 174       | 2.68%   |
| 1-50          | 124       | 1.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4595      | 77.41%  |
| 2     | 1143      | 19.26%  |
| 3     | 136       | 2.29%   |
| 0     | 53        | 0.89%   |
| 4     | 9         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3277      | 37.58%  |
| Intel                             | 2996      | 34.36%  |
| Qualcomm Atheros                  | 909       | 10.42%  |
| Broadcom                          | 366       | 4.2%    |
| Ralink Technology                 | 116       | 1.33%   |
| TP-Link                           | 110       | 1.26%   |
| Broadcom Limited                  | 87        | 1%      |
| MediaTek                          | 75        | 0.86%   |
| Ralink                            | 67        | 0.77%   |
| Marvell Technology Group          | 54        | 0.62%   |
| Microsoft                         | 47        | 0.54%   |
| Nvidia                            | 42        | 0.48%   |
| Xiaomi                            | 41        | 0.47%   |
| Samsung Electronics               | 32        | 0.37%   |
| ASIX Electronics                  | 30        | 0.34%   |
| Qualcomm Atheros Communications   | 29        | 0.33%   |
| Aquantia                          | 29        | 0.33%   |
| Huawei Technologies               | 26        | 0.3%    |
| Sierra Wireless                   | 25        | 0.29%   |
| ASUSTek Computer                  | 25        | 0.29%   |
| Lenovo                            | 22        | 0.25%   |
| Dell                              | 21        | 0.24%   |
| NetGear                           | 20        | 0.23%   |
| DisplayLink                       | 20        | 0.23%   |
| D-Link                            | 20        | 0.23%   |
| Linksys                           | 19        | 0.22%   |
| Qualcomm                          | 16        | 0.18%   |
| JMicron Technology                | 14        | 0.16%   |
| Hewlett-Packard                   | 14        | 0.16%   |
| Edimax Technology                 | 13        | 0.15%   |
| Ericsson Business Mobile Networks | 10        | 0.11%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.1%    |
| D-Link System                     | 9         | 0.1%    |
| Microchip Technology              | 8         | 0.09%   |
| Google                            | 7         | 0.08%   |
| Apple                             | 7         | 0.08%   |
| ZyXEL Communications              | 6         | 0.07%   |
| Motorola PCS                      | 6         | 0.07%   |
| Mellanox Technologies             | 5         | 0.06%   |
| Fibocom                           | 5         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2344      | 22.89%  |
| Intel Wi-Fi 6 AX200                                               | 447       | 4.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 325       | 3.17%   |
| Intel I211 Gigabit Network Connection                             | 260       | 2.54%   |
| Intel Wireless 8265 / 8275                                        | 205       | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 183       | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 170       | 1.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 158       | 1.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 151       | 1.47%   |
| Intel Wireless 7265                                               | 150       | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 140       | 1.37%   |
| Intel Wireless 7260                                               | 133       | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 127       | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 123       | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 119       | 1.16%   |
| Intel Ethernet Connection (2) I219-V                              | 118       | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 114       | 1.11%   |
| Intel Wi-Fi 6 AX201                                               | 114       | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 106       | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 104       | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 99        | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 92        | 0.9%    |
| Intel Wireless 8260                                               | 91        | 0.89%   |
| Intel Wireless 3165                                               | 90        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 89        | 0.87%   |
| Intel Wireless-AC 9260                                            | 87        | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 84        | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 77        | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 67        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 66        | 0.64%   |
| Intel Ethernet Controller I225-V                                  | 65        | 0.63%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 65        | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 56        | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 54        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 52        | 0.51%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 52        | 0.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 47        | 0.46%   |
| Intel Wireless 3160                                               | 45        | 0.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 42        | 0.41%   |
| Intel Ethernet Connection (2) I218-V                              | 41        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2346      | 48.41%  |
| Realtek Semiconductor                 | 823       | 16.98%  |
| Qualcomm Atheros                      | 714       | 14.73%  |
| Broadcom                              | 266       | 5.49%   |
| Ralink Technology                     | 116       | 2.39%   |
| TP-Link                               | 103       | 2.13%   |
| Ralink                                | 67        | 1.38%   |
| MediaTek                              | 67        | 1.38%   |
| Broadcom Limited                      | 65        | 1.34%   |
| Microsoft                             | 44        | 0.91%   |
| Qualcomm Atheros Communications       | 29        | 0.6%    |
| Sierra Wireless                       | 25        | 0.52%   |
| ASUSTek Computer                      | 23        | 0.47%   |
| NetGear                               | 20        | 0.41%   |
| D-Link                                | 20        | 0.41%   |
| Linksys                               | 18        | 0.37%   |
| Dell                                  | 15        | 0.31%   |
| Marvell Technology Group              | 14        | 0.29%   |
| Edimax Technology                     | 13        | 0.27%   |
| Hewlett-Packard                       | 7         | 0.14%   |
| ZyXEL Communications                  | 6         | 0.12%   |
| D-Link System                         | 6         | 0.12%   |
| Qualcomm                              | 5         | 0.1%    |
| Fibocom                               | 4         | 0.08%   |
| Belkin Components                     | 4         | 0.08%   |
| Quectel Wireless Solutions            | 3         | 0.06%   |
| Mercucys                              | 3         | 0.06%   |
| IMC Networks                          | 3         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.06%   |
| ZyDAS                                 | 2         | 0.04%   |
| Tenda                                 | 2         | 0.04%   |
| AVM                                   | 2         | 0.04%   |
| Xiaomi                                | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Fujitsu Siemens Computers             | 1         | 0.02%   |
| Encore Electronics                    | 1         | 0.02%   |
| Apple                                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 447       | 9.15%   |
| Intel Wireless 8265 / 8275                                     | 205       | 4.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 170       | 3.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 151       | 3.09%   |
| Intel Wireless 7265                                            | 150       | 3.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 140       | 2.86%   |
| Intel Wireless 7260                                            | 133       | 2.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 123       | 2.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 119       | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 114       | 2.33%   |
| Intel Wi-Fi 6 AX201                                            | 114       | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 106       | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 104       | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 99        | 2.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 92        | 1.88%   |
| Intel Wireless 8260                                            | 91        | 1.86%   |
| Intel Wireless 3165                                            | 90        | 1.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 89        | 1.82%   |
| Intel Wireless-AC 9260                                         | 87        | 1.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 84        | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 77        | 1.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 67        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 65        | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 52        | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 47        | 0.96%   |
| Intel Wireless 3160                                            | 45        | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 42        | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 41        | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 40        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 40        | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 37        | 0.76%   |
| Ralink MT7601U Wireless Adapter                                | 37        | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                  | 37        | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 36        | 0.74%   |
| Intel Centrino Wireless-N 2230                                 | 36        | 0.74%   |
| Realtek 802.11ac NIC                                           | 35        | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 35        | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 35        | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 33        | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 29        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2959      | 57.32%  |
| Intel                                  | 1379      | 26.71%  |
| Qualcomm Atheros                       | 275       | 5.33%   |
| Broadcom                               | 146       | 2.83%   |
| Nvidia                                 | 42        | 0.81%   |
| Marvell Technology Group               | 40        | 0.77%   |
| Xiaomi                                 | 39        | 0.76%   |
| Samsung Electronics                    | 31        | 0.6%    |
| ASIX Electronics                       | 30        | 0.58%   |
| Aquantia                               | 29        | 0.56%   |
| Broadcom Limited                       | 25        | 0.48%   |
| Lenovo                                 | 22        | 0.43%   |
| DisplayLink                            | 20        | 0.39%   |
| Huawei Technologies                    | 17        | 0.33%   |
| JMicron Technology                     | 14        | 0.27%   |
| Qualcomm                               | 10        | 0.19%   |
| TP-Link                                | 7         | 0.14%   |
| MediaTek                               | 7         | 0.14%   |
| Google                                 | 7         | 0.14%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.12%   |
| Apple                                  | 6         | 0.12%   |
| Mellanox Technologies                  | 5         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 4         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.08%   |
| T & A Mobile Phones                    | 3         | 0.06%   |
| Motorola PCS                           | 3         | 0.06%   |
| Microsoft                              | 3         | 0.06%   |
| D-Link System                          | 3         | 0.06%   |
| Spreadtrum Communications              | 2         | 0.04%   |
| OPPO Electronics                       | 2         | 0.04%   |
| National Semiconductor                 | 2         | 0.04%   |
| ICS Advent                             | 2         | 0.04%   |
| HMD Global                             | 2         | 0.04%   |
| Foxconn / Hon Hai                      | 2         | 0.04%   |
| Attansic Technology                    | 2         | 0.04%   |
| ASUSTek Computer                       | 2         | 0.04%   |
| VIA Technologies                       | 1         | 0.02%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.02%   |
| NetXen Incorporated                    | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2344      | 44.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 325       | 6.16%   |
| Intel I211 Gigabit Network Connection                             | 260       | 4.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 183       | 3.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 158       | 2.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 127       | 2.41%   |
| Intel Ethernet Connection (2) I219-V                              | 118       | 2.24%   |
| Intel Ethernet Connection I217-LM                                 | 66        | 1.25%   |
| Intel Ethernet Controller I225-V                                  | 65        | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 56        | 1.06%   |
| Intel Ethernet Connection (7) I219-V                              | 54        | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 52        | 0.99%   |
| Intel Ethernet Connection (2) I218-V                              | 41        | 0.78%   |
| Intel Ethernet Connection I217-V                                  | 40        | 0.76%   |
| Intel Ethernet Connection (4) I219-V                              | 40        | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 38        | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 37        | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 33        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 33        | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 31        | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 30        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 30        | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 29        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 28        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 25        | 0.47%   |
| Intel Ethernet Connection (10) I219-V                             | 25        | 0.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.44%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21        | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 0.4%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 21        | 0.4%    |
| ASIX AX88179 Gigabit Ethernet                                     | 21        | 0.4%    |
| Nvidia MCP61 Ethernet                                             | 19        | 0.36%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.36%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 0.36%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19        | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 18        | 0.34%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.34%   |
| Intel Ethernet Connection (6) I219-LM                             | 18        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4863      | 51.17%  |
| WiFi     | 4568      | 48.06%  |
| Modem    | 62        | 0.65%   |
| Unknown  | 11        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3601      | 59.17%  |
| Ethernet | 2485      | 40.83%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3077      | 52.71%  |
| 1     | 2559      | 43.83%  |
| 3     | 128       | 2.19%   |
| 0     | 60        | 1.03%   |
| 4     | 7         | 0.12%   |
| 5     | 5         | 0.09%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5031      | 85.21%  |
| Yes  | 873       | 14.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1984      | 50.91%  |
| Realtek Semiconductor           | 418       | 10.73%  |
| Qualcomm Atheros Communications | 309       | 7.93%   |
| Cambridge Silicon Radio         | 298       | 7.65%   |
| IMC Networks                    | 156       | 4%      |
| Broadcom                        | 140       | 3.59%   |
| Lite-On Technology              | 126       | 3.23%   |
| Apple                           | 100       | 2.57%   |
| ASUSTek Computer                | 92        | 2.36%   |
| Foxconn / Hon Hai               | 66        | 1.69%   |
| Realtek                         | 36        | 0.92%   |
| Dell                            | 24        | 0.62%   |
| Ralink                          | 23        | 0.59%   |
| Hewlett-Packard                 | 16        | 0.41%   |
| Toshiba                         | 13        | 0.33%   |
| MediaTek                        | 13        | 0.33%   |
| Marvell Semiconductor           | 11        | 0.28%   |
| Foxconn International           | 9         | 0.23%   |
| Dynex                           | 7         | 0.18%   |
| Ralink Technology               | 6         | 0.15%   |
| Opticis                         | 5         | 0.13%   |
| HTC (High Tech Computer)        | 5         | 0.13%   |
| Belkin Components               | 5         | 0.13%   |
| Alps Electric                   | 5         | 0.13%   |
| TP-Link                         | 4         | 0.1%    |
| SINO WEALTH                     | 4         | 0.1%    |
| Edimax Technology               | 4         | 0.1%    |
| Conwise Technology              | 4         | 0.1%    |
| Askey Computer                  | 4         | 0.1%    |
| Integrated System Solution      | 2         | 0.05%   |
| Fujitsu                         | 2         | 0.05%   |
| USI                             | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| D-Link                          | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 668       | 17.12%  |
| Intel AX200 Bluetooth                               | 422       | 10.81%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 311       | 7.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 298       | 7.64%   |
| Realtek Bluetooth Radio                             | 277       | 7.1%    |
| Intel AX201 Bluetooth                               | 276       | 7.07%   |
| Qualcomm Atheros  Bluetooth Device                  | 153       | 3.92%   |
| Realtek  Bluetooth 4.2 Adapter                      | 111       | 2.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 102       | 2.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 82        | 2.1%    |
| IMC Networks Bluetooth Radio                        | 66        | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 55        | 1.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 44        | 1.13%   |
| Intel AX210 Bluetooth                               | 44        | 1.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 43        | 1.1%    |
| Lite-On Bluetooth Device                            | 42        | 1.08%   |
| Apple Bluetooth USB Host Controller                 | 42        | 1.08%   |
| IMC Networks Bluetooth Device                       | 40        | 1.03%   |
| Apple Bluetooth Host Controller                     | 39        | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 38        | 0.97%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 38        | 0.97%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 37        | 0.95%   |
| Realtek Bluetooth Radio                             | 36        | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 34        | 0.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 31        | 0.79%   |
| Ralink RT3290 Bluetooth                             | 23        | 0.59%   |
| IMC Networks Wireless_Device                        | 23        | 0.59%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 20        | 0.51%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.41%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 16        | 0.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 16        | 0.41%   |
| Lite-On Atheros AR3012 Bluetooth                    | 14        | 0.36%   |
| ASUS Bluetooth Radio                                | 13        | 0.33%   |
| ASUS Bluetooth Adapter                              | 13        | 0.33%   |
| Intel Bluetooth Device                              | 12        | 0.31%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.31%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.31%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 12        | 0.31%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.28%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 11        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3860      | 44.51%  |
| AMD                                  | 2107      | 24.29%  |
| Nvidia                               | 1545      | 17.81%  |
| C-Media Electronics                  | 196       | 2.26%   |
| Logitech                             | 85        | 0.98%   |
| Creative Labs                        | 65        | 0.75%   |
| Kingston Technology                  | 52        | 0.6%    |
| JMTek                                | 49        | 0.56%   |
| Texas Instruments                    | 41        | 0.47%   |
| SteelSeries ApS                      | 37        | 0.43%   |
| Realtek Semiconductor                | 35        | 0.4%    |
| Corsair                              | 35        | 0.4%    |
| Generalplus Technology               | 30        | 0.35%   |
| Focusrite-Novation                   | 30        | 0.35%   |
| Creative Technology                  | 30        | 0.35%   |
| Blue Microphones                     | 27        | 0.31%   |
| Razer USA                            | 26        | 0.3%    |
| Plantronics                          | 25        | 0.29%   |
| GN Netcom                            | 24        | 0.28%   |
| BEHRINGER International              | 21        | 0.24%   |
| Lenovo                               | 20        | 0.23%   |
| ASUSTek Computer                     | 20        | 0.23%   |
| GYROCOM C&C                          | 15        | 0.17%   |
| Sony                                 | 14        | 0.16%   |
| Apple                                | 13        | 0.15%   |
| Sennheiser Communications            | 12        | 0.14%   |
| Samson Technologies                  | 11        | 0.13%   |
| M-Audio                              | 11        | 0.13%   |
| VIA Technologies                     | 10        | 0.12%   |
| RODE Microphones                     | 10        | 0.12%   |
| SAVITECH                             | 9         | 0.1%    |
| Giga-Byte Technology                 | 8         | 0.09%   |
| Yamaha                               | 7         | 0.08%   |
| Turtle Beach                         | 7         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.07%   |
| Astro Gaming                         | 6         | 0.07%   |
| Alesis                               | 6         | 0.07%   |
| Valve Software                       | 5         | 0.06%   |
| Elgato Systems                       | 5         | 0.06%   |
| Dell                                 | 5         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 716       | 6.84%   |
| Intel Sunrise Point-LP HD Audio                                            | 491       | 4.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 387       | 3.7%    |
| AMD Starship/Matisse HD Audio Controller                                   | 385       | 3.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 346       | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 307       | 2.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 294       | 2.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 281       | 2.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 270       | 2.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 248       | 2.37%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 223       | 2.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 188       | 1.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 175       | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 174       | 1.66%   |
| Intel 8 Series HD Audio Controller                                         | 166       | 1.59%   |
| Intel Haswell-ULT HD Audio Controller                                      | 165       | 1.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 164       | 1.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 150       | 1.43%   |
| AMD FCH Azalia Controller                                                  | 143       | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 139       | 1.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 138       | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 135       | 1.29%   |
| Nvidia GP106 High Definition Audio Controller                              | 134       | 1.28%   |
| Nvidia GP104 High Definition Audio Controller                              | 129       | 1.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 129       | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 124       | 1.18%   |
| Intel 200 Series PCH HD Audio                                              | 124       | 1.18%   |
| AMD Navi 10 HDMI Audio                                                     | 107       | 1.02%   |
| Intel CM238 HD Audio Controller                                            | 95        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                              | 90        | 0.86%   |
| Intel Comet Lake PCH cAVS                                                  | 90        | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 88        | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 86        | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 85        | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 81        | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 76        | 0.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 76        | 0.73%   |
| Nvidia GM204 High Definition Audio Controller                              | 75        | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 74        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 73        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 950       | 22.73%  |
| SK hynix            | 637       | 15.24%  |
| Kingston            | 500       | 11.96%  |
| Micron Technology   | 415       | 9.93%   |
| Corsair             | 314       | 7.51%   |
| Unknown             | 291       | 6.96%   |
| Crucial             | 261       | 6.25%   |
| G.Skill             | 235       | 5.62%   |
| A-DATA Technology   | 97        | 2.32%   |
| Ramaxel Technology  | 68        | 1.63%   |
| Elpida              | 50        | 1.2%    |
| Team                | 46        | 1.1%    |
| Patriot             | 44        | 1.05%   |
| Nanya Technology    | 39        | 0.93%   |
| Unknown (ABCD)      | 28        | 0.67%   |
| GOODRAM             | 23        | 0.55%   |
| Smart               | 22        | 0.53%   |
| Transcend           | 17        | 0.41%   |
| Unknown             | 12        | 0.29%   |
| Apacer              | 10        | 0.24%   |
| AMD                 | 9         | 0.22%   |
| Kllisre             | 7         | 0.17%   |
| ASint Technology    | 7         | 0.17%   |
| Silicon Power       | 5         | 0.12%   |
| GeIL                | 5         | 0.12%   |
| Teikon              | 4         | 0.1%    |
| Qumo                | 4         | 0.1%    |
| PNY                 | 4         | 0.1%    |
| Atermiter           | 4         | 0.1%    |
| Smart Brazil        | 3         | 0.07%   |
| SHARETRONIC         | 3         | 0.07%   |
| Neo Forza           | 3         | 0.07%   |
| Kingmax             | 3         | 0.07%   |
| Goldkey             | 3         | 0.07%   |
| CSX                 | 3         | 0.07%   |
| Avant               | 3         | 0.07%   |
| Unknown (08C8)      | 2         | 0.05%   |
| TwinMOS             | 2         | 0.05%   |
| Timetec             | 2         | 0.05%   |
| Qimonda             | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 56        | 1.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 53        | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 44        | 0.98%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 40        | 0.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 38        | 0.85%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 38        | 0.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 35        | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 34        | 0.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 32        | 0.71%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 30        | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 29        | 0.65%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 26        | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 25        | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 25        | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 0.56%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 24        | 0.54%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 23        | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.45%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 20        | 0.45%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 20        | 0.45%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 18        | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 17        | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 0.38%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s           | 17        | 0.38%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.36%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.36%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 16        | 0.36%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 15        | 0.33%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 15        | 0.33%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 15        | 0.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.31%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 14        | 0.31%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.31%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 14        | 0.31%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 14        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2032      | 56.32%  |
| DDR3    | 1060      | 29.38%  |
| LPDDR4  | 145       | 4.02%   |
| LPDDR3  | 113       | 3.13%   |
| Unknown | 80        | 2.22%   |
| DDR2    | 71        | 1.97%   |
| SDRAM   | 70        | 1.94%   |
| DDR     | 14        | 0.39%   |
| DDR5    | 11        | 0.3%    |
| LPDDR5  | 9         | 0.25%   |
| DRAM    | 3         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1949      | 54.2%   |
| DIMM         | 1308      | 36.37%  |
| Row Of Chips | 310       | 8.62%   |
| Chip         | 17        | 0.47%   |
| Unknown      | 8         | 0.22%   |
| FB-DIMM      | 3         | 0.08%   |
| RIMM         | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1734      | 44.26%  |
| 4096  | 1095      | 27.95%  |
| 16384 | 562       | 14.34%  |
| 2048  | 339       | 8.65%   |
| 32768 | 116       | 2.96%   |
| 1024  | 65        | 1.66%   |
| 512   | 5         | 0.13%   |
| 65536 | 1         | 0.03%   |
| 3072  | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 735       | 18.57%  |
| 2667    | 693       | 17.51%  |
| 3200    | 647       | 16.35%  |
| 2400    | 329       | 8.31%   |
| 2133    | 222       | 5.61%   |
| 1333    | 194       | 4.9%    |
| 3600    | 154       | 3.89%   |
| 1334    | 94        | 2.38%   |
| 1867    | 92        | 2.32%   |
| 4267    | 64        | 1.62%   |
| 800     | 56        | 1.42%   |
| 3466    | 54        | 1.36%   |
| 3266    | 54        | 1.36%   |
| 3400    | 48        | 1.21%   |
| 3000    | 48        | 1.21%   |
| 667     | 46        | 1.16%   |
| Unknown | 34        | 0.86%   |
| 1866    | 32        | 0.81%   |
| 1067    | 31        | 0.78%   |
| 3733    | 29        | 0.73%   |
| 3866    | 25        | 0.63%   |
| 4199    | 24        | 0.61%   |
| 3800    | 24        | 0.61%   |
| 1066    | 22        | 0.56%   |
| 2933    | 20        | 0.51%   |
| 4266    | 15        | 0.38%   |
| 2666    | 15        | 0.38%   |
| 4800    | 14        | 0.35%   |
| 2800    | 11        | 0.28%   |
| 2048    | 10        | 0.25%   |
| 1800    | 10        | 0.25%   |
| 975     | 9         | 0.23%   |
| 6400    | 8         | 0.2%    |
| 8400    | 7         | 0.18%   |
| 333     | 7         | 0.18%   |
| 3666    | 6         | 0.15%   |
| 3334    | 6         | 0.15%   |
| 3500    | 4         | 0.1%    |
| 3100    | 4         | 0.1%    |
| 2448    | 4         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 50        | 40.32%  |
| Brother Industries    | 23        | 18.55%  |
| Canon                 | 14        | 11.29%  |
| Seiko Epson           | 11        | 8.87%   |
| Samsung Electronics   | 8         | 6.45%   |
| Pantum                | 3         | 2.42%   |
| Xerox                 | 2         | 1.61%   |
| Prolific Technology   | 2         | 1.61%   |
| Dymo-CoStar           | 2         | 1.61%   |
| Apple                 | 2         | 1.61%   |
| Xiaomi                | 1         | 0.81%   |
| Sagem                 | 1         | 0.81%   |
| Ricoh                 | 1         | 0.81%   |
| QinHeng Electronics   | 1         | 0.81%   |
| Oki Data              | 1         | 0.81%   |
| Lexmark International | 1         | 0.81%   |
| Kyocera               | 1         | 0.81%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP OfficeJet 5200 series                               | 3         | 2.4%    |
| HP LaserJet 1300                                       | 3         | 2.4%    |
| HP ENVY 4520 series                                    | 3         | 2.4%    |
| Xerox Phaser 3020                                      | 2         | 1.6%    |
| Seiko Epson L120 Series                                | 2         | 1.6%    |
| Prolific PL2305 Parallel Port                          | 2         | 1.6%    |
| HP Officejet 2620 series                               | 2         | 1.6%    |
| HP DeskJet 2700 series                                 | 2         | 1.6%    |
| HP DeskJet 2130 series                                 | 2         | 1.6%    |
| HP Color LaserJet Pro M453-4                           | 2         | 1.6%    |
| Canon MG5700 series                                    | 2         | 1.6%    |
| Brother MFC-L2710DW series                             | 2         | 1.6%    |
| Brother HL-L2300D series                               | 2         | 1.6%    |
| Brother HL-5370DW series                               | 2         | 1.6%    |
| Brother DCP-7040                                       | 2         | 1.6%    |
| Apple Gamesir-G3s 2.15                                 | 2         | 1.6%    |
| Xiaomi MiMouse 2                                       | 1         | 0.8%    |
| Seiko Epson Stylus NX230/SX235W Series                 | 1         | 0.8%    |
| Seiko Epson Printer                                    | 1         | 0.8%    |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.8%    |
| Seiko Epson ME 320/330 Series [Stylus SX125]           | 1         | 0.8%    |
| Seiko Epson L805 Series                                | 1         | 0.8%    |
| Seiko Epson L365 Series                                | 1         | 0.8%    |
| Seiko Epson L355 Series                                | 1         | 0.8%    |
| Seiko Epson L3150 Series                               | 1         | 0.8%    |
| Seiko Epson ET-4760 Series                             | 1         | 0.8%    |
| Seiko Epson ET-3850 Series                             | 1         | 0.8%    |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.8%    |
| Samsung ML-1865                                        | 1         | 0.8%    |
| Samsung ML-1660 Series                                 | 1         | 0.8%    |
| Samsung ML-1640 Series Laser Printer                   | 1         | 0.8%    |
| Samsung M2020 Series                                   | 1         | 0.8%    |
| Samsung CLX-3300 Series                                | 1         | 0.8%    |
| Samsung CLX-3180 Series                                | 1         | 0.8%    |
| Samsung CLP-310 Color Laser Printer                    | 1         | 0.8%    |
| Sagem Laser Pro LL                                     | 1         | 0.8%    |
| Ricoh SP 112SU                                         | 1         | 0.8%    |
| QinHeng CH340S                                         | 1         | 0.8%    |
| Pantum P2500W series                                   | 1         | 0.8%    |
| Pantum P2200 series                                    | 1         | 0.8%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 19        | 63.33%  |
| Seiko Epson        | 5         | 16.67%  |
| Hewlett-Packard    | 2         | 6.67%   |
| Visioneer          | 1         | 3.33%   |
| Ultima Electronics | 1         | 3.33%   |
| Mustek Systems     | 1         | 3.33%   |
| AGFA-Gevaert NV    | 1         | 3.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                               | 5         | 16.67%  |
| Canon CanoScan LiDE 110                                                               | 5         | 16.67%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 2         | 6.67%   |
| Canon CanoScan LIDE 25                                                                | 2         | 6.67%   |
| Visioneer OneTouch 5300 USB                                                           | 1         | 3.33%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 3.33%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 3.33%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 3.33%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1         | 3.33%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 3.33%   |
| HP ScanJet 3500c                                                                      | 1         | 3.33%   |
| HP ScanJet 3400cse                                                                    | 1         | 3.33%   |
| Canon CanoScan LiDE 90                                                                | 1         | 3.33%   |
| Canon CanoScan LiDE 500F                                                              | 1         | 3.33%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1         | 3.33%   |
| Canon CanoScan LiDE 200                                                               | 1         | 3.33%   |
| Canon CanoScan LiDE 120                                                               | 1         | 3.33%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1         | 3.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 760       | 20.43%  |
| IMC Networks                           | 441       | 11.85%  |
| Realtek Semiconductor                  | 282       | 7.58%   |
| Acer                                   | 278       | 7.47%   |
| Microdia                               | 277       | 7.45%   |
| Logitech                               | 260       | 6.99%   |
| Quanta                                 | 177       | 4.76%   |
| Sunplus Innovation Technology          | 170       | 4.57%   |
| Cheng Uei Precision Industry (Foxlink) | 133       | 3.58%   |
| Lite-On Technology                     | 110       | 2.96%   |
| Syntek                                 | 109       | 2.93%   |
| Apple                                  | 88        | 2.37%   |
| Suyin                                  | 85        | 2.28%   |
| Microsoft                              | 63        | 1.69%   |
| Silicon Motion                         | 53        | 1.42%   |
| Alcor Micro                            | 50        | 1.34%   |
| Samsung Electronics                    | 40        | 1.08%   |
| Luxvisions Innotech Limited            | 34        | 0.91%   |
| Z-Star Microelectronics                | 22        | 0.59%   |
| Ricoh                                  | 18        | 0.48%   |
| Lenovo                                 | 14        | 0.38%   |
| Creative Technology                    | 14        | 0.38%   |
| Importek                               | 12        | 0.32%   |
| Sonix Technology                       | 11        | 0.3%    |
| MacroSilicon                           | 10        | 0.27%   |
| GEMBIRD                                | 10        | 0.27%   |
| Primax Electronics                     | 9         | 0.24%   |
| ARC International                      | 9         | 0.24%   |
| LG Electronics                         | 8         | 0.22%   |
| Google                                 | 8         | 0.22%   |
| Genesys Logic                          | 8         | 0.22%   |
| KYE Systems (Mouse Systems)            | 7         | 0.19%   |
| Generalplus Technology                 | 7         | 0.19%   |
| Unknown                                | 6         | 0.16%   |
| SunplusIT                              | 6         | 0.16%   |
| DigiTech                               | 6         | 0.16%   |
| Cubeternet                             | 6         | 0.16%   |
| ALi                                    | 6         | 0.16%   |
| Valve Software                         | 5         | 0.13%   |
| Intel                                  | 5         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 193       | 5.15%   |
| IMC Networks Integrated Camera          | 143       | 3.81%   |
| Microdia Integrated_Webcam_HD           | 121       | 3.23%   |
| IMC Networks USB2.0 HD UVC WebCam       | 111       | 2.96%   |
| Realtek Integrated_Webcam_HD            | 101       | 2.69%   |
| Acer Integrated Camera                  | 92        | 2.45%   |
| Chicony HD Webcam                       | 87        | 2.32%   |
| Syntek Integrated Camera                | 73        | 1.95%   |
| Logitech Webcam C270                    | 66        | 1.76%   |
| Sunplus Integrated_Webcam_HD            | 48        | 1.28%   |
| Logitech HD Pro Webcam C920             | 43        | 1.15%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 42        | 1.12%   |
| Samsung Galaxy series, misc. (MTP mode) | 40        | 1.07%   |
| Lite-On Integrated Camera               | 38        | 1.01%   |
| Acer HD Webcam                          | 32        | 0.85%   |
| Chicony HP Wide Vision HD Camera        | 31        | 0.83%   |
| Chicony HP HD Camera                    | 31        | 0.83%   |
| Apple iPhone 5/5C/5S/6/SE               | 30        | 0.8%    |
| Quanta HP TrueVision HD Camera          | 28        | 0.75%   |
| Acer Lenovo EasyCamera                  | 27        | 0.72%   |
| Realtek USB Camera                      | 26        | 0.69%   |
| Quanta HD User Facing                   | 26        | 0.69%   |
| Lite-On HP HD Camera                    | 26        | 0.69%   |
| Chicony USB2.0 Camera                   | 26        | 0.69%   |
| Microsoft LifeCam HD-3000               | 24        | 0.64%   |
| Chicony EasyCamera                      | 24        | 0.64%   |
| Acer EasyCamera                         | 24        | 0.64%   |
| Quanta HD Webcam                        | 23        | 0.61%   |
| Microdia Integrated Webcam              | 23        | 0.61%   |
| Chicony USB2.0 HD UVC WebCam            | 23        | 0.61%   |
| Chicony Lenovo EasyCamera               | 23        | 0.61%   |
| Acer SunplusIT Integrated Camera        | 22        | 0.59%   |
| Acer BisonCam, NB Pro                   | 22        | 0.59%   |
| Syntek Lenovo EasyCamera                | 21        | 0.56%   |
| Sunplus HD WebCam                       | 21        | 0.56%   |
| Quanta HP Wide Vision HD Camera         | 20        | 0.53%   |
| Microdia Laptop_Integrated_Webcam_HD    | 20        | 0.53%   |
| Chicony HD User Facing                  | 20        | 0.53%   |
| Realtek USB2.0 HD UVC WebCam            | 19        | 0.51%   |
| Realtek HD WebCam                       | 19        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 236       | 30.69%  |
| Validity Sensors           | 221       | 28.74%  |
| Shenzhen Goodix Technology | 158       | 20.55%  |
| Elan Microelectronics      | 58        | 7.54%   |
| LighTuning Technology      | 32        | 4.16%   |
| Upek                       | 26        | 3.38%   |
| AuthenTec                  | 19        | 2.47%   |
| STMicroelectronics         | 8         | 1.04%   |
| Samsung Electronics        | 5         | 0.65%   |
| Focal-systems.Corp         | 2         | 0.26%   |
| DigitalPersona             | 2         | 0.26%   |
| HOLTEK                     | 1         | 0.13%   |
| Futronic Technology        | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 87        | 11.31%  |
| Shenzhen Goodix  FingerPrint Device                                        | 76        | 9.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 56        | 7.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 56        | 7.28%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 48        | 6.24%   |
| Elan ELAN:Fingerprint                                                      | 39        | 5.07%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 32        | 4.16%   |
| Shenzhen Goodix FingerPrint                                                | 26        | 3.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 3.12%   |
| Synaptics  WBDI                                                            | 23        | 2.99%   |
| Validity Sensors Synaptics WBDI                                            | 22        | 2.86%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 21        | 2.73%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 2.73%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 2.47%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 2.21%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 16        | 2.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 1.95%   |
| Elan ELAN:ARM-M4                                                           | 15        | 1.95%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 1.82%   |
| Validity Sensors VFS491                                                    | 13        | 1.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 1.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.43%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.04%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 1.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.91%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.91%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 0.52%   |
| Synaptics WBDI Device                                                      | 4         | 0.52%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 4         | 0.52%   |
| AuthenTec AES2810                                                          | 4         | 0.52%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 0.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.39%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.39%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.39%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 0.39%   |
| AuthenTec AES1600                                                          | 3         | 0.39%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 79        | 33.47%  |
| Alcor Micro                       | 79        | 33.47%  |
| O2 Micro                          | 16        | 6.78%   |
| Lenovo                            | 16        | 6.78%   |
| Upek                              | 14        | 5.93%   |
| Yubico.com                        | 8         | 3.39%   |
| Gemalto (was Gemplus)             | 7         | 2.97%   |
| Realtek Semiconductor             | 4         | 1.69%   |
| OmniKey                           | 3         | 1.27%   |
| VASCO Data Security International | 2         | 0.85%   |
| SCM Microsystems                  | 1         | 0.42%   |
| Reiner SCT Kartensysteme          | 1         | 0.42%   |
| Hewlett-Packard                   | 1         | 0.42%   |
| Clay Logic                        | 1         | 0.42%   |
| Cherry                            | 1         | 0.42%   |
| C3PO                              | 1         | 0.42%   |
| BIT4ID                            | 1         | 0.42%   |
| Aladdin Knowledge Systems         | 1         | 0.42%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 78        | 33.05%  |
| Broadcom BCM5880 Secure Applications Processor                               | 33        | 13.98%  |
| Broadcom 5880                                                                | 22        | 9.32%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.78%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 6.36%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 5.93%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 5.08%   |
| Broadcom 58200                                                               | 12        | 5.08%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 2.97%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 1.69%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 1.69%   |
| OmniKey 3x21 Smart Card Reader                                               | 3         | 1.27%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.85%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.42%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.42%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.42%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.42%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.42%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.42%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.42%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.42%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.42%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.42%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.42%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.42%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.42%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.42%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4139      | 69.89%  |
| 1     | 1462      | 24.69%  |
| 2     | 293       | 4.95%   |
| 3     | 26        | 0.44%   |
| 4     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 754       | 36.55%  |
| Graphics card            | 353       | 17.11%  |
| Net/wireless             | 269       | 13.04%  |
| Chipcard                 | 206       | 9.99%   |
| Multimedia controller    | 150       | 7.27%   |
| Camera                   | 75        | 3.64%   |
| Net/ethernet             | 56        | 2.71%   |
| Unassigned class         | 46        | 2.23%   |
| Bluetooth                | 43        | 2.08%   |
| Sound                    | 23        | 1.11%   |
| Communication controller | 22        | 1.07%   |
| Storage                  | 19        | 0.92%   |
| Card reader              | 14        | 0.68%   |
| Dvb card                 | 12        | 0.58%   |
| Network                  | 7         | 0.34%   |
| Storage/raid             | 4         | 0.19%   |
| Modem                    | 4         | 0.19%   |
| Video                    | 2         | 0.1%    |
| Storage/ide              | 2         | 0.1%    |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |

