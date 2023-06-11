EndeavourOS - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/EndeavourOS/Desktop/README.md) and [notebooks](/Dist/EndeavourOS/Notebook/README.md).

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

Total: 1387

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6510              | Notebook    | [e7c1e59ac7](https://linux-hardware.org/?probe=e7c1e59ac7) | Jun 10, 2023 |
| Dell          | 0DWPVW A00                  | Desktop     | [ffad802816](https://linux-hardware.org/?probe=ffad802816) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [a597fc235e](https://linux-hardware.org/?probe=a597fc235e) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [6a368b8ecc](https://linux-hardware.org/?probe=6a368b8ecc) | Jun 09, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [2f0f8eb596](https://linux-hardware.org/?probe=2f0f8eb596) | Jun 09, 2023 |
| VIT           | P2402                       | Notebook    | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [52df878410](https://linux-hardware.org/?probe=52df878410) | Jun 08, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [0f41ab04b6](https://linux-hardware.org/?probe=0f41ab04b6) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [3e38c53463](https://linux-hardware.org/?probe=3e38c53463) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [0e24e0ad6c](https://linux-hardware.org/?probe=0e24e0ad6c) | Jun 07, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [33fb312b6d](https://linux-hardware.org/?probe=33fb312b6d) | Jun 05, 2023 |
| Dell          | 0D24M8 A00                  | Desktop     | [92fe930ecf](https://linux-hardware.org/?probe=92fe930ecf) | Jun 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [bfe6623b23](https://linux-hardware.org/?probe=bfe6623b23) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [c3dae64ee6](https://linux-hardware.org/?probe=c3dae64ee6) | Jun 03, 2023 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [1b01df33d2](https://linux-hardware.org/?probe=1b01df33d2) | Jun 03, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [04830d213f](https://linux-hardware.org/?probe=04830d213f) | Jun 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [4ccfddd671](https://linux-hardware.org/?probe=4ccfddd671) | Jun 02, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [becb85a201](https://linux-hardware.org/?probe=becb85a201) | Jun 02, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [c4cd05b00f](https://linux-hardware.org/?probe=c4cd05b00f) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [7d35807036](https://linux-hardware.org/?probe=7d35807036) | Jun 01, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3de415ea72](https://linux-hardware.org/?probe=3de415ea72) | Jun 01, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [8bc281486e](https://linux-hardware.org/?probe=8bc281486e) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c198463bc3](https://linux-hardware.org/?probe=c198463bc3) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [a1f825f4e5](https://linux-hardware.org/?probe=a1f825f4e5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | Notebook    | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | Notebook    | [0b04d3bf20](https://linux-hardware.org/?probe=0b04d3bf20) | May 28, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [574e88c4f3](https://linux-hardware.org/?probe=574e88c4f3) | May 28, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [af33101302](https://linux-hardware.org/?probe=af33101302) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| HP            | 86EE                        | All in one  | [ba49672c5b](https://linux-hardware.org/?probe=ba49672c5b) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4362f979b8](https://linux-hardware.org/?probe=4362f979b8) | May 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a36e1c1d5](https://linux-hardware.org/?probe=2a36e1c1d5) | May 26, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [4c22ef876f](https://linux-hardware.org/?probe=4c22ef876f) | May 26, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [46cb91a74d](https://linux-hardware.org/?probe=46cb91a74d) | May 25, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [48bd340a09](https://linux-hardware.org/?probe=48bd340a09) | May 24, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [7f5d36cc34](https://linux-hardware.org/?probe=7f5d36cc34) | May 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b7fbda70d3](https://linux-hardware.org/?probe=b7fbda70d3) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a605d12e2d](https://linux-hardware.org/?probe=a605d12e2d) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a1770c45b0](https://linux-hardware.org/?probe=a1770c45b0) | May 23, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [0cba90ce8e](https://linux-hardware.org/?probe=0cba90ce8e) | May 23, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [a48977a871](https://linux-hardware.org/?probe=a48977a871) | May 22, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| HP            | 18E4                        | Desktop     | [5601900c8b](https://linux-hardware.org/?probe=5601900c8b) | May 22, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [1125a4111e](https://linux-hardware.org/?probe=1125a4111e) | May 19, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [1edee9f902](https://linux-hardware.org/?probe=1edee9f902) | May 18, 2023 |
| Lenovo        | 3734 SDK0R32862 WIN 3258... | All in one  | [da9ebc680a](https://linux-hardware.org/?probe=da9ebc680a) | May 16, 2023 |
| HP            | 18E4                        | Desktop     | [7560196205](https://linux-hardware.org/?probe=7560196205) | May 16, 2023 |
| HP            | 18E4                        | Desktop     | [4dc91feab7](https://linux-hardware.org/?probe=4dc91feab7) | May 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [59a9ba6e16](https://linux-hardware.org/?probe=59a9ba6e16) | May 13, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [4fd655c0aa](https://linux-hardware.org/?probe=4fd655c0aa) | May 13, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [e4bfe14f2d](https://linux-hardware.org/?probe=e4bfe14f2d) | May 13, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [bc0dacd119](https://linux-hardware.org/?probe=bc0dacd119) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [35d056f8bd](https://linux-hardware.org/?probe=35d056f8bd) | May 11, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| HP            | 18E4                        | Desktop     | [2a528dc758](https://linux-hardware.org/?probe=2a528dc758) | May 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b81c403545](https://linux-hardware.org/?probe=b81c403545) | May 09, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [3346a6a326](https://linux-hardware.org/?probe=3346a6a326) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [2a7a243899](https://linux-hardware.org/?probe=2a7a243899) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [c7a298018f](https://linux-hardware.org/?probe=c7a298018f) | May 08, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [a916fc6080](https://linux-hardware.org/?probe=a916fc6080) | May 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7a1ffd8bd2](https://linux-hardware.org/?probe=7a1ffd8bd2) | May 07, 2023 |
| Timi          | TM1701                      | Notebook    | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [7ab24c2d1a](https://linux-hardware.org/?probe=7ab24c2d1a) | May 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [df58b07032](https://linux-hardware.org/?probe=df58b07032) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [91c6b0d769](https://linux-hardware.org/?probe=91c6b0d769) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| HP            | 1589                        | Desktop     | [dd3e55b423](https://linux-hardware.org/?probe=dd3e55b423) | May 05, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8ff62a5045](https://linux-hardware.org/?probe=8ff62a5045) | May 05, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [bac25fa124](https://linux-hardware.org/?probe=bac25fa124) | May 04, 2023 |
| Lenovo        | ThinkPad W530 24473F2       | Notebook    | [937dddbff0](https://linux-hardware.org/?probe=937dddbff0) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e49682836a](https://linux-hardware.org/?probe=e49682836a) | May 04, 2023 |
| HP            | 18E4                        | Desktop     | [d1344e36dd](https://linux-hardware.org/?probe=d1344e36dd) | May 03, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [9984dd7707](https://linux-hardware.org/?probe=9984dd7707) | May 03, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [16ac84221b](https://linux-hardware.org/?probe=16ac84221b) | May 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [96402fa64a](https://linux-hardware.org/?probe=96402fa64a) | May 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [07324ae678](https://linux-hardware.org/?probe=07324ae678) | May 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [24363c23cf](https://linux-hardware.org/?probe=24363c23cf) | May 01, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1a343a4622](https://linux-hardware.org/?probe=1a343a4622) | Apr 30, 2023 |
| Dell          | Latitude 5580               | Notebook    | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [54f8ed91cf](https://linux-hardware.org/?probe=54f8ed91cf) | Apr 30, 2023 |
| HP            | 18E4                        | Desktop     | [da858ea464](https://linux-hardware.org/?probe=da858ea464) | Apr 30, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [8c4352985e](https://linux-hardware.org/?probe=8c4352985e) | Apr 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c1e0f0fa03](https://linux-hardware.org/?probe=c1e0f0fa03) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| HP            | 8715                        | Mini pc     | [8d210cce39](https://linux-hardware.org/?probe=8d210cce39) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f1d5d361d5](https://linux-hardware.org/?probe=f1d5d361d5) | Apr 27, 2023 |
| MSI           | Modern 14 C7M               | Notebook    | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [17ae2e245a](https://linux-hardware.org/?probe=17ae2e245a) | Apr 22, 2023 |
| Notebook      | W65_W67RB                   | Notebook    | [f34e442b8b](https://linux-hardware.org/?probe=f34e442b8b) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | Notebook    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [00f7379c8f](https://linux-hardware.org/?probe=00f7379c8f) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [c27abc2880](https://linux-hardware.org/?probe=c27abc2880) | Apr 17, 2023 |
| ASUSTek       | X55A                        | Notebook    | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | Notebook    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f6a652b68d](https://linux-hardware.org/?probe=f6a652b68d) | Apr 14, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [8eaac4a62d](https://linux-hardware.org/?probe=8eaac4a62d) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [47f2ba894b](https://linux-hardware.org/?probe=47f2ba894b) | Apr 12, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [07353da9f6](https://linux-hardware.org/?probe=07353da9f6) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d9f95c9169](https://linux-hardware.org/?probe=d9f95c9169) | Apr 11, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [0e074bebcf](https://linux-hardware.org/?probe=0e074bebcf) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59db7a4f11](https://linux-hardware.org/?probe=59db7a4f11) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [01cae1e152](https://linux-hardware.org/?probe=01cae1e152) | Apr 10, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| HP            | 18E4                        | Desktop     | [54c681affc](https://linux-hardware.org/?probe=54c681affc) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [15d7d40bed](https://linux-hardware.org/?probe=15d7d40bed) | Apr 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | Notebook    | [aee22ee8b3](https://linux-hardware.org/?probe=aee22ee8b3) | Apr 08, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [d1167f66b8](https://linux-hardware.org/?probe=d1167f66b8) | Apr 08, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [a6c5efe560](https://linux-hardware.org/?probe=a6c5efe560) | Apr 07, 2023 |
| HP            | 250 G4                      | Notebook    | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| HP            | Unknown                     | Notebook    | [0af30fd642](https://linux-hardware.org/?probe=0af30fd642) | Apr 06, 2023 |
| Gigabyte      | H87M-D3H                    | Desktop     | [b9c169025d](https://linux-hardware.org/?probe=b9c169025d) | Apr 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5012c822d7](https://linux-hardware.org/?probe=5012c822d7) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [33eb81c75e](https://linux-hardware.org/?probe=33eb81c75e) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | Notebook    | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [546e8e3742](https://linux-hardware.org/?probe=546e8e3742) | Apr 04, 2023 |
| Samsung       | 950QDB                      | Convertible | [967646c481](https://linux-hardware.org/?probe=967646c481) | Apr 04, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [5035f094da](https://linux-hardware.org/?probe=5035f094da) | Apr 03, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [d3a27ee996](https://linux-hardware.org/?probe=d3a27ee996) | Apr 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [9ba99b597e](https://linux-hardware.org/?probe=9ba99b597e) | Apr 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [d64af320d7](https://linux-hardware.org/?probe=d64af320d7) | Apr 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [3400bd9412](https://linux-hardware.org/?probe=3400bd9412) | Apr 02, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | Notebook    | [edb6e927bd](https://linux-hardware.org/?probe=edb6e927bd) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | Notebook    | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [bfba694531](https://linux-hardware.org/?probe=bfba694531) | Apr 01, 2023 |
| HP            | 8715                        | Mini pc     | [bcd377dcb7](https://linux-hardware.org/?probe=bcd377dcb7) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [4169f13182](https://linux-hardware.org/?probe=4169f13182) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [3ac0a9cc94](https://linux-hardware.org/?probe=3ac0a9cc94) | Mar 31, 2023 |
| GPD           | G1621-02                    | Notebook    | [7d000ab41b](https://linux-hardware.org/?probe=7d000ab41b) | Mar 31, 2023 |
| HP            | 8715                        | Mini pc     | [222fde0a83](https://linux-hardware.org/?probe=222fde0a83) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [008eb6ad60](https://linux-hardware.org/?probe=008eb6ad60) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4dd142ab8f](https://linux-hardware.org/?probe=4dd142ab8f) | Mar 31, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [d1295d9d1e](https://linux-hardware.org/?probe=d1295d9d1e) | Mar 30, 2023 |
| AWOW          | AL34                        | Notebook    | [19f60f27c8](https://linux-hardware.org/?probe=19f60f27c8) | Mar 29, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [65671e15cb](https://linux-hardware.org/?probe=65671e15cb) | Mar 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [b165f54c80](https://linux-hardware.org/?probe=b165f54c80) | Mar 28, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [d80388d7ef](https://linux-hardware.org/?probe=d80388d7ef) | Mar 27, 2023 |
| HP            | 18E4                        | Desktop     | [5d10e73e1d](https://linux-hardware.org/?probe=5d10e73e1d) | Mar 26, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a8d31fc431](https://linux-hardware.org/?probe=a8d31fc431) | Mar 26, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [4253088a92](https://linux-hardware.org/?probe=4253088a92) | Mar 25, 2023 |
| Samsung       | 550XDA                      | Notebook    | [058982f7d8](https://linux-hardware.org/?probe=058982f7d8) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [18cd806803](https://linux-hardware.org/?probe=18cd806803) | Mar 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E6C... | Notebook    | [3042a430c0](https://linux-hardware.org/?probe=3042a430c0) | Mar 24, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e923cf7edb](https://linux-hardware.org/?probe=e923cf7edb) | Mar 24, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [5bd922e142](https://linux-hardware.org/?probe=5bd922e142) | Mar 23, 2023 |
| AZW           | GK35                        | Desktop     | [bd935978b7](https://linux-hardware.org/?probe=bd935978b7) | Mar 22, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| GPD           | G1619-04                    | Notebook    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [e0ec2e73be](https://linux-hardware.org/?probe=e0ec2e73be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Acer          | Swift SF315-52G             | Notebook    | [f6042580d0](https://linux-hardware.org/?probe=f6042580d0) | Mar 20, 2023 |
| Notebook      | N150ZU                      | Notebook    | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [a911c14f22](https://linux-hardware.org/?probe=a911c14f22) | Mar 19, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5f14b733bb](https://linux-hardware.org/?probe=5f14b733bb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| ASUSTek       | UX301LAA                    | Notebook    | [882d4d095b](https://linux-hardware.org/?probe=882d4d095b) | Mar 18, 2023 |
| HP            | 8715                        | Mini pc     | [1c2c765978](https://linux-hardware.org/?probe=1c2c765978) | Mar 18, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [a3e8bcd9dd](https://linux-hardware.org/?probe=a3e8bcd9dd) | Mar 18, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [ae4d8ba68c](https://linux-hardware.org/?probe=ae4d8ba68c) | Mar 18, 2023 |
| AZW           | U59                         | Desktop     | [ce6bd37711](https://linux-hardware.org/?probe=ce6bd37711) | Mar 18, 2023 |
| HP            | 8715                        | Mini pc     | [cd9310c350](https://linux-hardware.org/?probe=cd9310c350) | Mar 17, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [b43ea7bb6e](https://linux-hardware.org/?probe=b43ea7bb6e) | Mar 17, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [c6ef926aa6](https://linux-hardware.org/?probe=c6ef926aa6) | Mar 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d95b09eda0](https://linux-hardware.org/?probe=d95b09eda0) | Mar 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [066f0cd17b](https://linux-hardware.org/?probe=066f0cd17b) | Mar 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | Notebook    | [b588252431](https://linux-hardware.org/?probe=b588252431) | Mar 14, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [0f3b7bd317](https://linux-hardware.org/?probe=0f3b7bd317) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Notebook    | [7f58d0d0a0](https://linux-hardware.org/?probe=7f58d0d0a0) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Notebook    | [0c58b8ebad](https://linux-hardware.org/?probe=0c58b8ebad) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [fc04961aef](https://linux-hardware.org/?probe=fc04961aef) | Mar 11, 2023 |
| Unknown       | HX90                        | Desktop     | [51aca581e4](https://linux-hardware.org/?probe=51aca581e4) | Mar 11, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [bf6081f2af](https://linux-hardware.org/?probe=bf6081f2af) | Mar 09, 2023 |
| Dell          | Precision 7720              | Notebook    | [6132f690aa](https://linux-hardware.org/?probe=6132f690aa) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [8a33917a89](https://linux-hardware.org/?probe=8a33917a89) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [f4d71dcbd0](https://linux-hardware.org/?probe=f4d71dcbd0) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0fdb67b9d2](https://linux-hardware.org/?probe=0fdb67b9d2) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2e48f233a0](https://linux-hardware.org/?probe=2e48f233a0) | Mar 09, 2023 |
| Dell          | Precision 7720              | Notebook    | [e4a1149bcb](https://linux-hardware.org/?probe=e4a1149bcb) | Mar 08, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [af171db9dc](https://linux-hardware.org/?probe=af171db9dc) | Mar 08, 2023 |
| Timi          | TM1701                      | Notebook    | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [f363dca8ca](https://linux-hardware.org/?probe=f363dca8ca) | Mar 07, 2023 |
| HP            | 8860 A                      | Desktop     | [78c9aa9174](https://linux-hardware.org/?probe=78c9aa9174) | Mar 07, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3519073f46](https://linux-hardware.org/?probe=3519073f46) | Mar 07, 2023 |
| Dell          | Latitude 5289               | Notebook    | [dcac5b8ebc](https://linux-hardware.org/?probe=dcac5b8ebc) | Mar 06, 2023 |
| Google        | Rammus                      | Notebook    | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| HP            | 18E4                        | Desktop     | [a277b636c1](https://linux-hardware.org/?probe=a277b636c1) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
| HP            | 18E4                        | Desktop     | [8e76736e7e](https://linux-hardware.org/?probe=8e76736e7e) | Mar 02, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [80dca547fc](https://linux-hardware.org/?probe=80dca547fc) | Mar 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [89fb184b09](https://linux-hardware.org/?probe=89fb184b09) | Mar 01, 2023 |
| HP            | 18E4                        | Desktop     | [cab6d807e9](https://linux-hardware.org/?probe=cab6d807e9) | Feb 27, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1412fd5885](https://linux-hardware.org/?probe=1412fd5885) | Feb 26, 2023 |
| HP            | 18E4                        | Desktop     | [5c7c3413c9](https://linux-hardware.org/?probe=5c7c3413c9) | Feb 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [ccff1403b0](https://linux-hardware.org/?probe=ccff1403b0) | Feb 24, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [32f4f192fa](https://linux-hardware.org/?probe=32f4f192fa) | Feb 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [576a0fc8f5](https://linux-hardware.org/?probe=576a0fc8f5) | Feb 23, 2023 |
| Medion        | Akoya E6412T                | Notebook    | [2915d1c409](https://linux-hardware.org/?probe=2915d1c409) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [e8963c4e59](https://linux-hardware.org/?probe=e8963c4e59) | Feb 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d5f5531b82](https://linux-hardware.org/?probe=d5f5531b82) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [6234395029](https://linux-hardware.org/?probe=6234395029) | Feb 18, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7af4d238e8](https://linux-hardware.org/?probe=7af4d238e8) | Feb 18, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [09b0c2bf17](https://linux-hardware.org/?probe=09b0c2bf17) | Feb 17, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f594570a77](https://linux-hardware.org/?probe=f594570a77) | Feb 16, 2023 |
| Google        | Helios                      | Notebook    | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [b0693958a6](https://linux-hardware.org/?probe=b0693958a6) | Feb 15, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [c84212b39c](https://linux-hardware.org/?probe=c84212b39c) | Feb 15, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [6c540405e8](https://linux-hardware.org/?probe=6c540405e8) | Feb 15, 2023 |
| GPD           | G1621-02                    | Notebook    | [5d584fa1cf](https://linux-hardware.org/?probe=5d584fa1cf) | Feb 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4b0331863e](https://linux-hardware.org/?probe=4b0331863e) | Feb 14, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [d8ed5d5e88](https://linux-hardware.org/?probe=d8ed5d5e88) | Feb 14, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [820aa2bf49](https://linux-hardware.org/?probe=820aa2bf49) | Feb 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM    | Notebook    | [9e0e0bef82](https://linux-hardware.org/?probe=9e0e0bef82) | Feb 13, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [debdb17904](https://linux-hardware.org/?probe=debdb17904) | Feb 12, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8133fc11b8](https://linux-hardware.org/?probe=8133fc11b8) | Feb 12, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [05d11c4fe3](https://linux-hardware.org/?probe=05d11c4fe3) | Feb 12, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| HP            | Compaq 6820s                | Notebook    | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [0c6da36f9d](https://linux-hardware.org/?probe=0c6da36f9d) | Feb 11, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [059d515c3c](https://linux-hardware.org/?probe=059d515c3c) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Dell          | 0Y5FXV A00                  | Desktop     | [692b7eab6b](https://linux-hardware.org/?probe=692b7eab6b) | Feb 08, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2LN0... | Notebook    | [4fdb5d662c](https://linux-hardware.org/?probe=4fdb5d662c) | Feb 08, 2023 |
| HP            | ENVY Notebook PC            | Convertible | [a8165997b7](https://linux-hardware.org/?probe=a8165997b7) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [43c3e4d160](https://linux-hardware.org/?probe=43c3e4d160) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [f2a6af1f7e](https://linux-hardware.org/?probe=f2a6af1f7e) | Feb 06, 2023 |
| HP            | Setzer                      | Notebook    | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [e523dbd162](https://linux-hardware.org/?probe=e523dbd162) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [96847498e3](https://linux-hardware.org/?probe=96847498e3) | Feb 02, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [ecf260f299](https://linux-hardware.org/?probe=ecf260f299) | Feb 01, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [de7f0840d1](https://linux-hardware.org/?probe=de7f0840d1) | Feb 01, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [455825998f](https://linux-hardware.org/?probe=455825998f) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4251ab2f9a](https://linux-hardware.org/?probe=4251ab2f9a) | Feb 01, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [bcaa2e6b1a](https://linux-hardware.org/?probe=bcaa2e6b1a) | Jan 30, 2023 |
| Dell          | Latitude 5400               | Notebook    | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [3e957e185d](https://linux-hardware.org/?probe=3e957e185d) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [849d901314](https://linux-hardware.org/?probe=849d901314) | Jan 28, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [b15899ef80](https://linux-hardware.org/?probe=b15899ef80) | Jan 27, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [357a0cd22d](https://linux-hardware.org/?probe=357a0cd22d) | Jan 27, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Dell          | Latitude E5410              | Notebook    | [22df8731a9](https://linux-hardware.org/?probe=22df8731a9) | Jan 26, 2023 |
| Google        | Magpie                      | Notebook    | [34506f260e](https://linux-hardware.org/?probe=34506f260e) | Jan 26, 2023 |
| HP            | 86EE                        | All in one  | [2632541785](https://linux-hardware.org/?probe=2632541785) | Jan 25, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [55b2bf8aea](https://linux-hardware.org/?probe=55b2bf8aea) | Jan 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [56a9b7ad32](https://linux-hardware.org/?probe=56a9b7ad32) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [f371c1c8b6](https://linux-hardware.org/?probe=f371c1c8b6) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Notebook    | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [1153793fd9](https://linux-hardware.org/?probe=1153793fd9) | Jan 22, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [10796ad8f6](https://linux-hardware.org/?probe=10796ad8f6) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [f1d22db1d7](https://linux-hardware.org/?probe=f1d22db1d7) | Jan 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [2c44f8275e](https://linux-hardware.org/?probe=2c44f8275e) | Jan 17, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [25cbbcfc98](https://linux-hardware.org/?probe=25cbbcfc98) | Jan 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [2e40c15660](https://linux-hardware.org/?probe=2e40c15660) | Jan 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [8b1ccef51d](https://linux-hardware.org/?probe=8b1ccef51d) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [154dafff1e](https://linux-hardware.org/?probe=154dafff1e) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [ce588e0413](https://linux-hardware.org/?probe=ce588e0413) | Jan 14, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [1681bdc38e](https://linux-hardware.org/?probe=1681bdc38e) | Jan 14, 2023 |
| Dell          | Precision M4800             | Notebook    | [c5deb205c7](https://linux-hardware.org/?probe=c5deb205c7) | Jan 14, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [425fb5340d](https://linux-hardware.org/?probe=425fb5340d) | Jan 13, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [4fc1f3aff0](https://linux-hardware.org/?probe=4fc1f3aff0) | Jan 11, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [878c92decc](https://linux-hardware.org/?probe=878c92decc) | Jan 11, 2023 |
| HP            | 18E4                        | Desktop     | [600d82b264](https://linux-hardware.org/?probe=600d82b264) | Jan 11, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| HP            | 18E4                        | Desktop     | [3386d53667](https://linux-hardware.org/?probe=3386d53667) | Jan 10, 2023 |
| HP            | 2179                        | Desktop     | [ad75cc2104](https://linux-hardware.org/?probe=ad75cc2104) | Jan 10, 2023 |
| Dell          | 0NRKPK A01                  | Desktop     | [f5bdf45b4a](https://linux-hardware.org/?probe=f5bdf45b4a) | Jan 08, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [c18913a39e](https://linux-hardware.org/?probe=c18913a39e) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [28ed8a48bd](https://linux-hardware.org/?probe=28ed8a48bd) | Jan 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4947d17a2b](https://linux-hardware.org/?probe=4947d17a2b) | Jan 06, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [b2dfc2437e](https://linux-hardware.org/?probe=b2dfc2437e) | Jan 06, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [81431f1578](https://linux-hardware.org/?probe=81431f1578) | Jan 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [cef6a9db45](https://linux-hardware.org/?probe=cef6a9db45) | Jan 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [8defa5d641](https://linux-hardware.org/?probe=8defa5d641) | Jan 05, 2023 |
| Dell          | XPS 9320                    | Notebook    | [8684c6d86b](https://linux-hardware.org/?probe=8684c6d86b) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c84118baf](https://linux-hardware.org/?probe=0c84118baf) | Jan 03, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [be6730b67b](https://linux-hardware.org/?probe=be6730b67b) | Jan 03, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [2d0530b779](https://linux-hardware.org/?probe=2d0530b779) | Jan 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [bc57a904f7](https://linux-hardware.org/?probe=bc57a904f7) | Jan 03, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [d94e8b5637](https://linux-hardware.org/?probe=d94e8b5637) | Jan 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1be42c9032](https://linux-hardware.org/?probe=1be42c9032) | Jan 02, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [b613cd1179](https://linux-hardware.org/?probe=b613cd1179) | Jan 02, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [8f923bc065](https://linux-hardware.org/?probe=8f923bc065) | Jan 01, 2023 |
| Toshiba       | EQUIUM A100                 | Notebook    | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [6def847114](https://linux-hardware.org/?probe=6def847114) | Jan 01, 2023 |
| HP            | 18E4                        | Desktop     | [c83c8341e3](https://linux-hardware.org/?probe=c83c8341e3) | Jan 01, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [20eb2d93e2](https://linux-hardware.org/?probe=20eb2d93e2) | Jan 01, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [e0cb4d278d](https://linux-hardware.org/?probe=e0cb4d278d) | Dec 31, 2022 |
| HP            | 18E4                        | Desktop     | [1b1eccbbe1](https://linux-hardware.org/?probe=1b1eccbbe1) | Dec 31, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [9aba0ac647](https://linux-hardware.org/?probe=9aba0ac647) | Dec 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [30e1303337](https://linux-hardware.org/?probe=30e1303337) | Dec 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4d915292f4](https://linux-hardware.org/?probe=4d915292f4) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [b38e3cc51e](https://linux-hardware.org/?probe=b38e3cc51e) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ce45aaceaf](https://linux-hardware.org/?probe=ce45aaceaf) | Dec 29, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [adb13e2649](https://linux-hardware.org/?probe=adb13e2649) | Dec 29, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [e422b934d0](https://linux-hardware.org/?probe=e422b934d0) | Dec 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b8099c7a94](https://linux-hardware.org/?probe=b8099c7a94) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [475b76e98a](https://linux-hardware.org/?probe=475b76e98a) | Dec 28, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [cd90f1782c](https://linux-hardware.org/?probe=cd90f1782c) | Dec 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [78418bfaa6](https://linux-hardware.org/?probe=78418bfaa6) | Dec 25, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | Notebook    | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [416b0bb4e1](https://linux-hardware.org/?probe=416b0bb4e1) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [244ad65a78](https://linux-hardware.org/?probe=244ad65a78) | Dec 24, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [348c431775](https://linux-hardware.org/?probe=348c431775) | Dec 23, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [262a879a99](https://linux-hardware.org/?probe=262a879a99) | Dec 19, 2022 |
| Sony          | VGN-FW11E                   | Notebook    | [2d57afaa38](https://linux-hardware.org/?probe=2d57afaa38) | Dec 19, 2022 |
| HP            | 15                          | Notebook    | [cce5eb4078](https://linux-hardware.org/?probe=cce5eb4078) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [54e81a596c](https://linux-hardware.org/?probe=54e81a596c) | Dec 18, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0a486ca67b](https://linux-hardware.org/?probe=0a486ca67b) | Dec 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [c5adff1ad5](https://linux-hardware.org/?probe=c5adff1ad5) | Dec 17, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [8c87fc340b](https://linux-hardware.org/?probe=8c87fc340b) | Dec 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e69127d249](https://linux-hardware.org/?probe=e69127d249) | Dec 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [57ecebdc0f](https://linux-hardware.org/?probe=57ecebdc0f) | Dec 15, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8968e6816e](https://linux-hardware.org/?probe=8968e6816e) | Dec 15, 2022 |
| HP            | 18E4                        | Desktop     | [26757adc9d](https://linux-hardware.org/?probe=26757adc9d) | Dec 15, 2022 |
| HP            | 18E4                        | Desktop     | [ba6bef79d5](https://linux-hardware.org/?probe=ba6bef79d5) | Dec 15, 2022 |
| Lenovo        | Yoga 510-15IKB 80VC         | Convertible | [cb1e09289e](https://linux-hardware.org/?probe=cb1e09289e) | Dec 15, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [de70f43070](https://linux-hardware.org/?probe=de70f43070) | Dec 14, 2022 |
| HP            | 18E4                        | Desktop     | [00f1e4a14a](https://linux-hardware.org/?probe=00f1e4a14a) | Dec 14, 2022 |
| PC Special... | Elimina Iv 17               | Notebook    | [66a5d6dd6a](https://linux-hardware.org/?probe=66a5d6dd6a) | Dec 13, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [502792fe8a](https://linux-hardware.org/?probe=502792fe8a) | Dec 12, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [65c6c18ffe](https://linux-hardware.org/?probe=65c6c18ffe) | Dec 12, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [97691e3dca](https://linux-hardware.org/?probe=97691e3dca) | Dec 11, 2022 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [2a1d9a153b](https://linux-hardware.org/?probe=2a1d9a153b) | Dec 11, 2022 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [280f28a486](https://linux-hardware.org/?probe=280f28a486) | Dec 11, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [48ccfd51b4](https://linux-hardware.org/?probe=48ccfd51b4) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6ae6d710b7](https://linux-hardware.org/?probe=6ae6d710b7) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [b56f450d6d](https://linux-hardware.org/?probe=b56f450d6d) | Dec 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [5f3e259429](https://linux-hardware.org/?probe=5f3e259429) | Dec 10, 2022 |
| HP            | 18E4                        | Desktop     | [418a689ae5](https://linux-hardware.org/?probe=418a689ae5) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [963477cf57](https://linux-hardware.org/?probe=963477cf57) | Dec 07, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [46a6e9e722](https://linux-hardware.org/?probe=46a6e9e722) | Dec 07, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [ebf5cc9d6e](https://linux-hardware.org/?probe=ebf5cc9d6e) | Dec 06, 2022 |
| HP            | 18E4                        | Desktop     | [e897549786](https://linux-hardware.org/?probe=e897549786) | Dec 06, 2022 |
| HP            | 18E4                        | Desktop     | [b12969b62f](https://linux-hardware.org/?probe=b12969b62f) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [dcd57e5862](https://linux-hardware.org/?probe=dcd57e5862) | Dec 04, 2022 |
| MSI           | GS75 Stealth 8SG            | Notebook    | [8741c9175e](https://linux-hardware.org/?probe=8741c9175e) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | Notebook    | [c3b6dada9d](https://linux-hardware.org/?probe=c3b6dada9d) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | Notebook    | [70be467762](https://linux-hardware.org/?probe=70be467762) | Dec 01, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [eff3d877bc](https://linux-hardware.org/?probe=eff3d877bc) | Nov 30, 2022 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [b6af703e1a](https://linux-hardware.org/?probe=b6af703e1a) | Nov 28, 2022 |
| HP            | ENVY 17                     | Notebook    | [4a784f4642](https://linux-hardware.org/?probe=4a784f4642) | Nov 27, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [3ce1a2c42a](https://linux-hardware.org/?probe=3ce1a2c42a) | Nov 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [4e7809f7f6](https://linux-hardware.org/?probe=4e7809f7f6) | Nov 27, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1deadcff69](https://linux-hardware.org/?probe=1deadcff69) | Nov 27, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d5d04cf0f9](https://linux-hardware.org/?probe=d5d04cf0f9) | Nov 26, 2022 |
| HP            | 18E4                        | Desktop     | [d72a174606](https://linux-hardware.org/?probe=d72a174606) | Nov 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f76927c5ef](https://linux-hardware.org/?probe=f76927c5ef) | Nov 26, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [63521d3e8d](https://linux-hardware.org/?probe=63521d3e8d) | Nov 26, 2022 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [5b19381bf6](https://linux-hardware.org/?probe=5b19381bf6) | Nov 26, 2022 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [1878ce00d7](https://linux-hardware.org/?probe=1878ce00d7) | Nov 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [123efdf4df](https://linux-hardware.org/?probe=123efdf4df) | Nov 26, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f05943013c](https://linux-hardware.org/?probe=f05943013c) | Nov 25, 2022 |
| Lenovo        | ThinkPad T440s 20ARA12UM... | Notebook    | [5e1b88160e](https://linux-hardware.org/?probe=5e1b88160e) | Nov 25, 2022 |
| HP            | 18E4                        | Desktop     | [4a4ac150b6](https://linux-hardware.org/?probe=4a4ac150b6) | Nov 24, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [2b2778b81a](https://linux-hardware.org/?probe=2b2778b81a) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [0200afcfb3](https://linux-hardware.org/?probe=0200afcfb3) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [077cd77583](https://linux-hardware.org/?probe=077cd77583) | Nov 24, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1986287453](https://linux-hardware.org/?probe=1986287453) | Nov 24, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [415fd12650](https://linux-hardware.org/?probe=415fd12650) | Nov 22, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4ed396ae3f](https://linux-hardware.org/?probe=4ed396ae3f) | Nov 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [aca01ed633](https://linux-hardware.org/?probe=aca01ed633) | Nov 21, 2022 |
| HP            | 15                          | Notebook    | [ab7c1e3bfd](https://linux-hardware.org/?probe=ab7c1e3bfd) | Nov 21, 2022 |
| HP            | 18E4                        | Desktop     | [ff954b29c9](https://linux-hardware.org/?probe=ff954b29c9) | Nov 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [6c896ef17e](https://linux-hardware.org/?probe=6c896ef17e) | Nov 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0b0d1f6427](https://linux-hardware.org/?probe=0b0d1f6427) | Nov 19, 2022 |
| MSI           | B360 GAMING PLUS            | Desktop     | [6552f5cfc9](https://linux-hardware.org/?probe=6552f5cfc9) | Nov 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [01810a4098](https://linux-hardware.org/?probe=01810a4098) | Nov 17, 2022 |
| HP            | 18E4                        | Desktop     | [37dd18c268](https://linux-hardware.org/?probe=37dd18c268) | Nov 17, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [8c63644200](https://linux-hardware.org/?probe=8c63644200) | Nov 14, 2022 |
| HP            | 3397                        | Desktop     | [035eb81bdf](https://linux-hardware.org/?probe=035eb81bdf) | Nov 13, 2022 |
| HP            | 18E4                        | Desktop     | [be545cc91f](https://linux-hardware.org/?probe=be545cc91f) | Nov 13, 2022 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [112508759b](https://linux-hardware.org/?probe=112508759b) | Nov 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [7aeba8b69a](https://linux-hardware.org/?probe=7aeba8b69a) | Nov 10, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AJ00    | Notebook    | [ec16a4b3c5](https://linux-hardware.org/?probe=ec16a4b3c5) | Nov 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fba0c1a99c](https://linux-hardware.org/?probe=fba0c1a99c) | Nov 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [0527a7a983](https://linux-hardware.org/?probe=0527a7a983) | Nov 07, 2022 |
| Lenovo        | ThinkPad T520 42406AG       | Notebook    | [1038487513](https://linux-hardware.org/?probe=1038487513) | Nov 06, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d137598aff](https://linux-hardware.org/?probe=d137598aff) | Nov 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [31cae1e989](https://linux-hardware.org/?probe=31cae1e989) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [226d8de9bb](https://linux-hardware.org/?probe=226d8de9bb) | Nov 04, 2022 |
| HP            | 18E4                        | Desktop     | [66463ac87d](https://linux-hardware.org/?probe=66463ac87d) | Nov 04, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [08a8e0079a](https://linux-hardware.org/?probe=08a8e0079a) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0235661dbe](https://linux-hardware.org/?probe=0235661dbe) | Nov 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU    | Notebook    | [9e1b981f01](https://linux-hardware.org/?probe=9e1b981f01) | Nov 03, 2022 |
| HP            | 18E4                        | Desktop     | [1b1339be3d](https://linux-hardware.org/?probe=1b1339be3d) | Nov 02, 2022 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [973b498b3f](https://linux-hardware.org/?probe=973b498b3f) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [cd300a0714](https://linux-hardware.org/?probe=cd300a0714) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | Notebook    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [45a2f4473b](https://linux-hardware.org/?probe=45a2f4473b) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| HP            | 18E7                        | Desktop     | [d4a4ad62cb](https://linux-hardware.org/?probe=d4a4ad62cb) | Oct 29, 2022 |
| Acer          | Predator PO3-620            | Desktop     | [e737f3b4bd](https://linux-hardware.org/?probe=e737f3b4bd) | Oct 29, 2022 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [5e32f7b38b](https://linux-hardware.org/?probe=5e32f7b38b) | Oct 28, 2022 |
| HP            | 18E4                        | Desktop     | [9d0444b1b8](https://linux-hardware.org/?probe=9d0444b1b8) | Oct 28, 2022 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [22ec61d307](https://linux-hardware.org/?probe=22ec61d307) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [ed6d5efa84](https://linux-hardware.org/?probe=ed6d5efa84) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [6263763f01](https://linux-hardware.org/?probe=6263763f01) | Oct 27, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [264d164669](https://linux-hardware.org/?probe=264d164669) | Oct 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7be37b6a2d](https://linux-hardware.org/?probe=7be37b6a2d) | Oct 27, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [7e1a95e569](https://linux-hardware.org/?probe=7e1a95e569) | Oct 26, 2022 |
| Acer          | Extensa 2540                | Notebook    | [367660309f](https://linux-hardware.org/?probe=367660309f) | Oct 26, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [3848afd2c8](https://linux-hardware.org/?probe=3848afd2c8) | Oct 26, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [cc0b502ddf](https://linux-hardware.org/?probe=cc0b502ddf) | Oct 25, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [be4e6c1903](https://linux-hardware.org/?probe=be4e6c1903) | Oct 25, 2022 |
| HP            | 650                         | Notebook    | [d7b73bebc7](https://linux-hardware.org/?probe=d7b73bebc7) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3ab5922ddf](https://linux-hardware.org/?probe=3ab5922ddf) | Oct 25, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [aa4a86445a](https://linux-hardware.org/?probe=aa4a86445a) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [95707c7cd5](https://linux-hardware.org/?probe=95707c7cd5) | Oct 25, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [17a0e006d0](https://linux-hardware.org/?probe=17a0e006d0) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [c6966a0df9](https://linux-hardware.org/?probe=c6966a0df9) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [5b4ecfb7e9](https://linux-hardware.org/?probe=5b4ecfb7e9) | Oct 25, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [d9590e8d45](https://linux-hardware.org/?probe=d9590e8d45) | Oct 24, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [9023ea833f](https://linux-hardware.org/?probe=9023ea833f) | Oct 24, 2022 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [f81e674faf](https://linux-hardware.org/?probe=f81e674faf) | Oct 21, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [0312fb4d88](https://linux-hardware.org/?probe=0312fb4d88) | Oct 21, 2022 |
| HP            | 18E4                        | Desktop     | [dfbdab6987](https://linux-hardware.org/?probe=dfbdab6987) | Oct 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [d6275970a0](https://linux-hardware.org/?probe=d6275970a0) | Oct 21, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [0fd75382e9](https://linux-hardware.org/?probe=0fd75382e9) | Oct 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [facb462239](https://linux-hardware.org/?probe=facb462239) | Oct 20, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [bda1da1137](https://linux-hardware.org/?probe=bda1da1137) | Oct 20, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [c8997eb831](https://linux-hardware.org/?probe=c8997eb831) | Oct 20, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8105425af8](https://linux-hardware.org/?probe=8105425af8) | Oct 20, 2022 |
| MSI           | GE75 Raider 10SF            | Notebook    | [dd4102e2e7](https://linux-hardware.org/?probe=dd4102e2e7) | Oct 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [01338c4f3c](https://linux-hardware.org/?probe=01338c4f3c) | Oct 19, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [d7784759fb](https://linux-hardware.org/?probe=d7784759fb) | Oct 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [5e31cc470c](https://linux-hardware.org/?probe=5e31cc470c) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00fece9d77](https://linux-hardware.org/?probe=00fece9d77) | Oct 18, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d79e9be41b](https://linux-hardware.org/?probe=d79e9be41b) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [09a4ac981b](https://linux-hardware.org/?probe=09a4ac981b) | Oct 17, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [28d9942c9f](https://linux-hardware.org/?probe=28d9942c9f) | Oct 17, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3a6855c328](https://linux-hardware.org/?probe=3a6855c328) | Oct 15, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bf1677e47c](https://linux-hardware.org/?probe=bf1677e47c) | Oct 14, 2022 |
| Google        | Liara                       | Notebook    | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [1927ae6949](https://linux-hardware.org/?probe=1927ae6949) | Oct 12, 2022 |
| Lenovo        | V110-15AST 80TD             | Notebook    | [9d4b6fafb6](https://linux-hardware.org/?probe=9d4b6fafb6) | Oct 12, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [261f171b10](https://linux-hardware.org/?probe=261f171b10) | Oct 12, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [90661c40a3](https://linux-hardware.org/?probe=90661c40a3) | Oct 12, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [95daf6fc30](https://linux-hardware.org/?probe=95daf6fc30) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| HP            | 18E4                        | Desktop     | [6603067eba](https://linux-hardware.org/?probe=6603067eba) | Oct 10, 2022 |
| Acer          | Swift SF314-51              | Notebook    | [cfc56878f0](https://linux-hardware.org/?probe=cfc56878f0) | Oct 07, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [90c1d12ca3](https://linux-hardware.org/?probe=90c1d12ca3) | Oct 07, 2022 |
| Packard Be... | EasyNote TJ65               | Notebook    | [bb815f037b](https://linux-hardware.org/?probe=bb815f037b) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| HP            | 18E4                        | Desktop     | [53c6bf7af4](https://linux-hardware.org/?probe=53c6bf7af4) | Oct 06, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1f77699521](https://linux-hardware.org/?probe=1f77699521) | Oct 03, 2022 |
| iRU           | v1.0                        | Mini pc     | [388d438bbc](https://linux-hardware.org/?probe=388d438bbc) | Oct 03, 2022 |
| HP            | 250 G4                      | Notebook    | [7c892fab7a](https://linux-hardware.org/?probe=7c892fab7a) | Oct 03, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1a2e047ca1](https://linux-hardware.org/?probe=1a2e047ca1) | Oct 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [75e1aeaff5](https://linux-hardware.org/?probe=75e1aeaff5) | Oct 02, 2022 |
| Dell          | 0JYH5J A00                  | All in one  | [348bc23246](https://linux-hardware.org/?probe=348bc23246) | Oct 01, 2022 |
| MSI           | GF65 Thin 9SD               | Notebook    | [a761de487d](https://linux-hardware.org/?probe=a761de487d) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1570daf698](https://linux-hardware.org/?probe=1570daf698) | Sep 29, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [81ddb430e3](https://linux-hardware.org/?probe=81ddb430e3) | Sep 28, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [f9eecf6781](https://linux-hardware.org/?probe=f9eecf6781) | Sep 28, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [658f9b891f](https://linux-hardware.org/?probe=658f9b891f) | Sep 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [c0d2617a28](https://linux-hardware.org/?probe=c0d2617a28) | Sep 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2c69225287](https://linux-hardware.org/?probe=2c69225287) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [479dfeae74](https://linux-hardware.org/?probe=479dfeae74) | Sep 25, 2022 |
| Huanan        | X99-8M-F V1.3               | Desktop     | [6e96f4620a](https://linux-hardware.org/?probe=6e96f4620a) | Sep 25, 2022 |
| Huanan        | X99-8M-F V1.3               | Desktop     | [acb677ddeb](https://linux-hardware.org/?probe=acb677ddeb) | Sep 25, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [fe99b8a461](https://linux-hardware.org/?probe=fe99b8a461) | Sep 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [2b3c66f0ee](https://linux-hardware.org/?probe=2b3c66f0ee) | Sep 24, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [164ad85233](https://linux-hardware.org/?probe=164ad85233) | Sep 23, 2022 |
| HP            | 250 G4                      | Notebook    | [5d4c56fe14](https://linux-hardware.org/?probe=5d4c56fe14) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8e7a7a914c](https://linux-hardware.org/?probe=8e7a7a914c) | Sep 23, 2022 |
| AZW           | SEi                         | Desktop     | [579b2be420](https://linux-hardware.org/?probe=579b2be420) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [031f4bb4f1](https://linux-hardware.org/?probe=031f4bb4f1) | Sep 23, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d852d9e0dd](https://linux-hardware.org/?probe=d852d9e0dd) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [6f43da7fb4](https://linux-hardware.org/?probe=6f43da7fb4) | Sep 22, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [e6cb381fd2](https://linux-hardware.org/?probe=e6cb381fd2) | Sep 21, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [d0f94bde46](https://linux-hardware.org/?probe=d0f94bde46) | Sep 21, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [7ae4855566](https://linux-hardware.org/?probe=7ae4855566) | Sep 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f4f33e2362](https://linux-hardware.org/?probe=f4f33e2362) | Sep 20, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [e8f0a018c9](https://linux-hardware.org/?probe=e8f0a018c9) | Sep 19, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [579f73fc88](https://linux-hardware.org/?probe=579f73fc88) | Sep 19, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [543fad9f1c](https://linux-hardware.org/?probe=543fad9f1c) | Sep 18, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [434b1869d7](https://linux-hardware.org/?probe=434b1869d7) | Sep 16, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4f1e683ced](https://linux-hardware.org/?probe=4f1e683ced) | Sep 16, 2022 |
| HP            | 1998                        | Desktop     | [f3ef7a85fe](https://linux-hardware.org/?probe=f3ef7a85fe) | Sep 16, 2022 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [465e8d2c86](https://linux-hardware.org/?probe=465e8d2c86) | Sep 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [13cd2039a1](https://linux-hardware.org/?probe=13cd2039a1) | Sep 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S58700    | Notebook    | [9d9d51e924](https://linux-hardware.org/?probe=9d9d51e924) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | Notebook    | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [bfcf5bab5f](https://linux-hardware.org/?probe=bfcf5bab5f) | Sep 12, 2022 |
| Gigabyte      | AORUS 15G XC                | Notebook    | [4b0e97e947](https://linux-hardware.org/?probe=4b0e97e947) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [cf9447ce8c](https://linux-hardware.org/?probe=cf9447ce8c) | Sep 10, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [39c0297cb1](https://linux-hardware.org/?probe=39c0297cb1) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Timi          | TM1703                      | Notebook    | [5c30ece6ff](https://linux-hardware.org/?probe=5c30ece6ff) | Sep 08, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [07dfc865cf](https://linux-hardware.org/?probe=07dfc865cf) | Sep 08, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [df80ca89ee](https://linux-hardware.org/?probe=df80ca89ee) | Sep 08, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9690933a68](https://linux-hardware.org/?probe=9690933a68) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| Timi          | TM1703                      | Notebook    | [fb7386017f](https://linux-hardware.org/?probe=fb7386017f) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [dd3b771e55](https://linux-hardware.org/?probe=dd3b771e55) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e8887916fa](https://linux-hardware.org/?probe=e8887916fa) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | Notebook    | [a75fed8b3f](https://linux-hardware.org/?probe=a75fed8b3f) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | Notebook    | [cd613ebcd2](https://linux-hardware.org/?probe=cd613ebcd2) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | Notebook    | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [0e4f12b377](https://linux-hardware.org/?probe=0e4f12b377) | Sep 04, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | Notebook    | [2667cd1609](https://linux-hardware.org/?probe=2667cd1609) | Sep 03, 2022 |
| Dell          | 0HMF7C A01                  | Desktop     | [292123f83b](https://linux-hardware.org/?probe=292123f83b) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [05221c6c18](https://linux-hardware.org/?probe=05221c6c18) | Sep 03, 2022 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [2fb52eb1a8](https://linux-hardware.org/?probe=2fb52eb1a8) | Sep 03, 2022 |
| ASUSTek       | X580VN                      | Notebook    | [fe8f1a7e6f](https://linux-hardware.org/?probe=fe8f1a7e6f) | Sep 03, 2022 |
| HP            | OMEN by Laptop 16z-c000     | Notebook    | [edc4a4ce85](https://linux-hardware.org/?probe=edc4a4ce85) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | Notebook    | [3a8cfc8781](https://linux-hardware.org/?probe=3a8cfc8781) | Sep 01, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [297cab0eb2](https://linux-hardware.org/?probe=297cab0eb2) | Sep 01, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [18822e9fbe](https://linux-hardware.org/?probe=18822e9fbe) | Sep 01, 2022 |
| HP            | 18E7                        | Desktop     | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [94b00f5da5](https://linux-hardware.org/?probe=94b00f5da5) | Aug 27, 2022 |
| Google        | Peppy                       | Notebook    | [be4ecba4dc](https://linux-hardware.org/?probe=be4ecba4dc) | Aug 26, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [de2984c01a](https://linux-hardware.org/?probe=de2984c01a) | Aug 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [005afabbff](https://linux-hardware.org/?probe=005afabbff) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [782466213a](https://linux-hardware.org/?probe=782466213a) | Aug 19, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9b5ba9f755](https://linux-hardware.org/?probe=9b5ba9f755) | Aug 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [eec78b1552](https://linux-hardware.org/?probe=eec78b1552) | Aug 17, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fb77adfb99](https://linux-hardware.org/?probe=fb77adfb99) | Aug 16, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [2aa966d8af](https://linux-hardware.org/?probe=2aa966d8af) | Aug 14, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [94fb37c745](https://linux-hardware.org/?probe=94fb37c745) | Aug 14, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [94579c3a70](https://linux-hardware.org/?probe=94579c3a70) | Aug 13, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [b391d570ba](https://linux-hardware.org/?probe=b391d570ba) | Aug 12, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [9e297d5dde](https://linux-hardware.org/?probe=9e297d5dde) | Aug 11, 2022 |
| ASUSTek       | GL502VT                     | Notebook    | [5e95e514a4](https://linux-hardware.org/?probe=5e95e514a4) | Aug 11, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [a76e460266](https://linux-hardware.org/?probe=a76e460266) | Aug 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [d76760ffa4](https://linux-hardware.org/?probe=d76760ffa4) | Aug 11, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9c257fb6e7](https://linux-hardware.org/?probe=9c257fb6e7) | Aug 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9c5e5976db](https://linux-hardware.org/?probe=9c5e5976db) | Aug 08, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [ddbb081e21](https://linux-hardware.org/?probe=ddbb081e21) | Aug 08, 2022 |
| AZW           | U59                         | Desktop     | [33aea75ff4](https://linux-hardware.org/?probe=33aea75ff4) | Aug 07, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3ef9c93317](https://linux-hardware.org/?probe=3ef9c93317) | Aug 06, 2022 |
| Dell          | 0JYH5J A00                  | All in one  | [7940378ce2](https://linux-hardware.org/?probe=7940378ce2) | Aug 06, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [5373247b06](https://linux-hardware.org/?probe=5373247b06) | Aug 05, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [d1079f3fba](https://linux-hardware.org/?probe=d1079f3fba) | Aug 04, 2022 |
| Positivo      | S14BW01                     | Notebook    | [28c70dfa85](https://linux-hardware.org/?probe=28c70dfa85) | Aug 04, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [ec13dcb17f](https://linux-hardware.org/?probe=ec13dcb17f) | Aug 01, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [0bcc9863e3](https://linux-hardware.org/?probe=0bcc9863e3) | Jul 31, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [7a5337e18d](https://linux-hardware.org/?probe=7a5337e18d) | Jul 28, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [b6dea628df](https://linux-hardware.org/?probe=b6dea628df) | Jul 27, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [60b06048f3](https://linux-hardware.org/?probe=60b06048f3) | Jul 24, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [06dd902359](https://linux-hardware.org/?probe=06dd902359) | Jul 23, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [00f490c5d0](https://linux-hardware.org/?probe=00f490c5d0) | Jul 22, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [b3f65d7c35](https://linux-hardware.org/?probe=b3f65d7c35) | Jul 21, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [d7e2758b93](https://linux-hardware.org/?probe=d7e2758b93) | Jul 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| Samsung       | DeskTop System              | Desktop     | [d0d33ec330](https://linux-hardware.org/?probe=d0d33ec330) | Jul 19, 2022 |
| Samsung       | DeskTop System              | Desktop     | [3af9bcc9cb](https://linux-hardware.org/?probe=3af9bcc9cb) | Jul 19, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [76b994344e](https://linux-hardware.org/?probe=76b994344e) | Jul 19, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [e8156cb24f](https://linux-hardware.org/?probe=e8156cb24f) | Jul 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [10be1cd329](https://linux-hardware.org/?probe=10be1cd329) | Jul 18, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | Notebook    | [1a394fdf59](https://linux-hardware.org/?probe=1a394fdf59) | Jul 18, 2022 |
| Lenovo        | ThinkPad E595 20NF001HGE    | Notebook    | [9d3a54dbcf](https://linux-hardware.org/?probe=9d3a54dbcf) | Jul 17, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [85a02f5d41](https://linux-hardware.org/?probe=85a02f5d41) | Jul 15, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| HP            | 158B                        | Desktop     | [1f3ebf7ecf](https://linux-hardware.org/?probe=1f3ebf7ecf) | Jul 07, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| Gigabyte      | N3160TN                     | Desktop     | [b92830b100](https://linux-hardware.org/?probe=b92830b100) | Jul 03, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [36dcdacdb1](https://linux-hardware.org/?probe=36dcdacdb1) | Jul 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5dd727cd5e](https://linux-hardware.org/?probe=5dd727cd5e) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [9aa0a38b17](https://linux-hardware.org/?probe=9aa0a38b17) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [b9b09609b8](https://linux-hardware.org/?probe=b9b09609b8) | Jul 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [7528e47074](https://linux-hardware.org/?probe=7528e47074) | Jun 24, 2022 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [9816b1d616](https://linux-hardware.org/?probe=9816b1d616) | Jun 23, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [834bed6eda](https://linux-hardware.org/?probe=834bed6eda) | Jun 21, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b9a8ce148e](https://linux-hardware.org/?probe=b9a8ce148e) | Jun 21, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [16d7a07f8f](https://linux-hardware.org/?probe=16d7a07f8f) | Jun 20, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [a4091a0526](https://linux-hardware.org/?probe=a4091a0526) | Jun 19, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b0cc04798d](https://linux-hardware.org/?probe=b0cc04798d) | Jun 18, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [dc04d6eb1a](https://linux-hardware.org/?probe=dc04d6eb1a) | Jun 18, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [5c9a2e5312](https://linux-hardware.org/?probe=5c9a2e5312) | Jun 16, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [82a66444ec](https://linux-hardware.org/?probe=82a66444ec) | Jun 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| Dell          | Latitude XT                 | Notebook    | [6ca0e5ca92](https://linux-hardware.org/?probe=6ca0e5ca92) | Jun 14, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9275d3d785](https://linux-hardware.org/?probe=9275d3d785) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ab0ad88b31](https://linux-hardware.org/?probe=ab0ad88b31) | Jun 10, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [ed5235f3f4](https://linux-hardware.org/?probe=ed5235f3f4) | Jun 09, 2022 |
| Dell          | Latitude E6440              | Notebook    | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| Lenovo        | SKYBAY No DPK               | All in one  | [c27da0faa9](https://linux-hardware.org/?probe=c27da0faa9) | Jun 06, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [343315ec17](https://linux-hardware.org/?probe=343315ec17) | Jun 06, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [5c7a9690cf](https://linux-hardware.org/?probe=5c7a9690cf) | Jun 05, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [cb5ea65a1d](https://linux-hardware.org/?probe=cb5ea65a1d) | Jun 04, 2022 |
| ASUSTek       | UX461UN                     | Convertible | [e75c214872](https://linux-hardware.org/?probe=e75c214872) | Jun 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [eaff4f6db6](https://linux-hardware.org/?probe=eaff4f6db6) | Jun 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4a055cff40](https://linux-hardware.org/?probe=4a055cff40) | Jun 02, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [fb18d30478](https://linux-hardware.org/?probe=fb18d30478) | Jun 02, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [e9721391d2](https://linux-hardware.org/?probe=e9721391d2) | Jun 01, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [394d112de5](https://linux-hardware.org/?probe=394d112de5) | May 31, 2022 |
| Dell          | Latitude 5289               | Notebook    | [f9e3e0fa57](https://linux-hardware.org/?probe=f9e3e0fa57) | May 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [462a42a8c9](https://linux-hardware.org/?probe=462a42a8c9) | May 28, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [0075e2d9df](https://linux-hardware.org/?probe=0075e2d9df) | May 28, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [4ef7645f2d](https://linux-hardware.org/?probe=4ef7645f2d) | May 28, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [d17aaf4cc5](https://linux-hardware.org/?probe=d17aaf4cc5) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 81X2          | Convertible | [df65cb7a9e](https://linux-hardware.org/?probe=df65cb7a9e) | May 26, 2022 |
| Sony          | VPCCA17FX                   | Notebook    | [4ced9d5222](https://linux-hardware.org/?probe=4ced9d5222) | May 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [52b94e68a9](https://linux-hardware.org/?probe=52b94e68a9) | May 23, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4495957eae](https://linux-hardware.org/?probe=4495957eae) | May 23, 2022 |
| HP            | 0A08h                       | Desktop     | [86c65b6b1f](https://linux-hardware.org/?probe=86c65b6b1f) | May 21, 2022 |
| HP            | 0A08h                       | Desktop     | [18b2ce1297](https://linux-hardware.org/?probe=18b2ce1297) | May 21, 2022 |
| Timi          | A35S                        | Notebook    | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| ASRock        | A320M/ac                    | Desktop     | [78ee9c8853](https://linux-hardware.org/?probe=78ee9c8853) | May 20, 2022 |
| HP            | 3647h                       | Desktop     | [eccb82bec8](https://linux-hardware.org/?probe=eccb82bec8) | May 20, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [0bc568827c](https://linux-hardware.org/?probe=0bc568827c) | May 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [bc731dc190](https://linux-hardware.org/?probe=bc731dc190) | May 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [aa810f6e41](https://linux-hardware.org/?probe=aa810f6e41) | May 18, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [798bcbfce3](https://linux-hardware.org/?probe=798bcbfce3) | May 17, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [c4e15012d5](https://linux-hardware.org/?probe=c4e15012d5) | May 15, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [33dbac4352](https://linux-hardware.org/?probe=33dbac4352) | May 15, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [5dea5cd6ff](https://linux-hardware.org/?probe=5dea5cd6ff) | May 14, 2022 |
| HP            | Notebook                    | Notebook    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [34272a60d1](https://linux-hardware.org/?probe=34272a60d1) | May 10, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b5145fe094](https://linux-hardware.org/?probe=b5145fe094) | May 08, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [3d921b618b](https://linux-hardware.org/?probe=3d921b618b) | May 07, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [6a3cbcae26](https://linux-hardware.org/?probe=6a3cbcae26) | May 06, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [3dbf93ec7f](https://linux-hardware.org/?probe=3dbf93ec7f) | May 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [9264c80f15](https://linux-hardware.org/?probe=9264c80f15) | May 05, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [7354dedb38](https://linux-hardware.org/?probe=7354dedb38) | May 03, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [bcc65ca336](https://linux-hardware.org/?probe=bcc65ca336) | May 03, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [e40e784775](https://linux-hardware.org/?probe=e40e784775) | May 03, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [1d4a595342](https://linux-hardware.org/?probe=1d4a595342) | May 02, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [b212517217](https://linux-hardware.org/?probe=b212517217) | May 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [79a3d8d3f6](https://linux-hardware.org/?probe=79a3d8d3f6) | May 01, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [06b533396d](https://linux-hardware.org/?probe=06b533396d) | Apr 30, 2022 |
| ASUSTek       | X71Vn                       | Notebook    | [b31a7dce8b](https://linux-hardware.org/?probe=b31a7dce8b) | Apr 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e45e120b35](https://linux-hardware.org/?probe=e45e120b35) | Apr 29, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [5754b2db0d](https://linux-hardware.org/?probe=5754b2db0d) | Apr 29, 2022 |
| Lenovo        | SKYBAY No DPK               | All in one  | [41f38e1f81](https://linux-hardware.org/?probe=41f38e1f81) | Apr 28, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a7eeea4f7c](https://linux-hardware.org/?probe=a7eeea4f7c) | Apr 27, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [0199a1bcec](https://linux-hardware.org/?probe=0199a1bcec) | Apr 24, 2022 |
| Dell          | Latitude 7280               | Notebook    | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [3d667e4edf](https://linux-hardware.org/?probe=3d667e4edf) | Apr 21, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [5fdc5a8e7b](https://linux-hardware.org/?probe=5fdc5a8e7b) | Apr 21, 2022 |
| Google        | Celes                       | Notebook    | [a1a2262b88](https://linux-hardware.org/?probe=a1a2262b88) | Apr 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [5a58c1f799](https://linux-hardware.org/?probe=5a58c1f799) | Apr 18, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [583693a1a9](https://linux-hardware.org/?probe=583693a1a9) | Apr 17, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | Notebook    | [10a97e42a3](https://linux-hardware.org/?probe=10a97e42a3) | Apr 17, 2022 |
| Google        | Candy                       | Notebook    | [77b6731597](https://linux-hardware.org/?probe=77b6731597) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [2b3ac63766](https://linux-hardware.org/?probe=2b3ac63766) | Apr 16, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [a892a2412c](https://linux-hardware.org/?probe=a892a2412c) | Apr 15, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a2947cf99b](https://linux-hardware.org/?probe=a2947cf99b) | Apr 15, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a6c14df869](https://linux-hardware.org/?probe=a6c14df869) | Apr 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8350598ef6](https://linux-hardware.org/?probe=8350598ef6) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [939dbc38d3](https://linux-hardware.org/?probe=939dbc38d3) | Apr 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| Acer          | Swift SF314-57G             | Notebook    | [b9b31b0528](https://linux-hardware.org/?probe=b9b31b0528) | Apr 14, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8ea05feeaf](https://linux-hardware.org/?probe=8ea05feeaf) | Apr 13, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [1a48a9a11d](https://linux-hardware.org/?probe=1a48a9a11d) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1ff04268cf](https://linux-hardware.org/?probe=1ff04268cf) | Apr 13, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [d90283da2d](https://linux-hardware.org/?probe=d90283da2d) | Apr 13, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [c3202f68fc](https://linux-hardware.org/?probe=c3202f68fc) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [32f07398c4](https://linux-hardware.org/?probe=32f07398c4) | Apr 12, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [bbaa6e145b](https://linux-hardware.org/?probe=bbaa6e145b) | Apr 12, 2022 |
| ILLEGEAR      | ROGUE                       | Notebook    | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [13df82ae45](https://linux-hardware.org/?probe=13df82ae45) | Apr 12, 2022 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [69f81b5d41](https://linux-hardware.org/?probe=69f81b5d41) | Apr 11, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [31aefcd602](https://linux-hardware.org/?probe=31aefcd602) | Apr 10, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [64ac971253](https://linux-hardware.org/?probe=64ac971253) | Apr 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [183521cdae](https://linux-hardware.org/?probe=183521cdae) | Apr 07, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [febbb5b9a2](https://linux-hardware.org/?probe=febbb5b9a2) | Apr 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [3327822265](https://linux-hardware.org/?probe=3327822265) | Apr 06, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9170392920](https://linux-hardware.org/?probe=9170392920) | Apr 04, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [87acd223c9](https://linux-hardware.org/?probe=87acd223c9) | Apr 04, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [0127833323](https://linux-hardware.org/?probe=0127833323) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [b8d47c54c3](https://linux-hardware.org/?probe=b8d47c54c3) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [53da5b2d7c](https://linux-hardware.org/?probe=53da5b2d7c) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| Samsung       | 930QCA                      | Convertible | [d5991ba91f](https://linux-hardware.org/?probe=d5991ba91f) | Apr 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [376167460b](https://linux-hardware.org/?probe=376167460b) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [58413a83b2](https://linux-hardware.org/?probe=58413a83b2) | Mar 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [ee491ed7f4](https://linux-hardware.org/?probe=ee491ed7f4) | Mar 29, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [f9c192cd71](https://linux-hardware.org/?probe=f9c192cd71) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [dc38374e42](https://linux-hardware.org/?probe=dc38374e42) | Mar 26, 2022 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [50bcf21472](https://linux-hardware.org/?probe=50bcf21472) | Mar 23, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [921004463e](https://linux-hardware.org/?probe=921004463e) | Mar 23, 2022 |
| Samsung       | 950QDB                      | Convertible | [97642a3dca](https://linux-hardware.org/?probe=97642a3dca) | Mar 23, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3500cd92bf](https://linux-hardware.org/?probe=3500cd92bf) | Mar 19, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [4b3b3cfc11](https://linux-hardware.org/?probe=4b3b3cfc11) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [59bd959d3e](https://linux-hardware.org/?probe=59bd959d3e) | Mar 19, 2022 |
| Acer          | Extensa 2520                | Notebook    | [f070f33060](https://linux-hardware.org/?probe=f070f33060) | Mar 19, 2022 |
| Acer          | Extensa 2520                | Notebook    | [f2003c1f90](https://linux-hardware.org/?probe=f2003c1f90) | Mar 19, 2022 |
| ASUSTek       | G752VT                      | Notebook    | [632814d6a3](https://linux-hardware.org/?probe=632814d6a3) | Mar 18, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [7e64ef177c](https://linux-hardware.org/?probe=7e64ef177c) | Mar 18, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [d742a1c2fa](https://linux-hardware.org/?probe=d742a1c2fa) | Mar 16, 2022 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [ad8e612da5](https://linux-hardware.org/?probe=ad8e612da5) | Mar 15, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [a0a0ba299e](https://linux-hardware.org/?probe=a0a0ba299e) | Mar 15, 2022 |
| Google        | Akemi                       | Notebook    | [6a52c103e9](https://linux-hardware.org/?probe=6a52c103e9) | Mar 14, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [88296140c2](https://linux-hardware.org/?probe=88296140c2) | Mar 11, 2022 |
| Dell          | Precision M6800             | Notebook    | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [e8f9fb7d24](https://linux-hardware.org/?probe=e8f9fb7d24) | Mar 09, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | Notebook    | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2d2bd57c8b](https://linux-hardware.org/?probe=2d2bd57c8b) | Mar 06, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [677fa0d0a3](https://linux-hardware.org/?probe=677fa0d0a3) | Mar 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [e81420b85c](https://linux-hardware.org/?probe=e81420b85c) | Mar 01, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [d3cc5d36be](https://linux-hardware.org/?probe=d3cc5d36be) | Feb 27, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Eluktronic... | Prometheus XVII             | Notebook    | [0797cebf2d](https://linux-hardware.org/?probe=0797cebf2d) | Feb 26, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f4bc34ce43](https://linux-hardware.org/?probe=f4bc34ce43) | Feb 23, 2022 |
| Dell          | Latitude 3420               | Notebook    | [fb586744c3](https://linux-hardware.org/?probe=fb586744c3) | Feb 22, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [655c17b9ff](https://linux-hardware.org/?probe=655c17b9ff) | Feb 20, 2022 |
| Radxa         | ROCK Pi X v1.4              | Notebook    | [dd6d9dc630](https://linux-hardware.org/?probe=dd6d9dc630) | Feb 19, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [4f87ec9849](https://linux-hardware.org/?probe=4f87ec9849) | Feb 19, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [973e1c8d91](https://linux-hardware.org/?probe=973e1c8d91) | Feb 19, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [90e932e714](https://linux-hardware.org/?probe=90e932e714) | Feb 19, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [7ad21cbc90](https://linux-hardware.org/?probe=7ad21cbc90) | Feb 19, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [2bfd36f050](https://linux-hardware.org/?probe=2bfd36f050) | Feb 18, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [d98a594e28](https://linux-hardware.org/?probe=d98a594e28) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | Notebook    | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Eluktronic... | Prometheus XVII             | Notebook    | [36436d1aff](https://linux-hardware.org/?probe=36436d1aff) | Feb 17, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [63d492d4bb](https://linux-hardware.org/?probe=63d492d4bb) | Feb 16, 2022 |
| ASUSTek       | UX490UA                     | Notebook    | [5e40078555](https://linux-hardware.org/?probe=5e40078555) | Feb 14, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [879969adee](https://linux-hardware.org/?probe=879969adee) | Feb 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f84892675f](https://linux-hardware.org/?probe=f84892675f) | Feb 12, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [dda932e1ae](https://linux-hardware.org/?probe=dda932e1ae) | Feb 11, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c79fe1743d](https://linux-hardware.org/?probe=c79fe1743d) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a8c18662ff](https://linux-hardware.org/?probe=a8c18662ff) | Feb 10, 2022 |
| Dell          | G3 3500                     | Notebook    | [92ee625013](https://linux-hardware.org/?probe=92ee625013) | Feb 09, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [1228be8404](https://linux-hardware.org/?probe=1228be8404) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c408e51e91](https://linux-hardware.org/?probe=c408e51e91) | Feb 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [f2719a9d26](https://linux-hardware.org/?probe=f2719a9d26) | Feb 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Dell          | Latitude E4310              | Notebook    | [ef92697af7](https://linux-hardware.org/?probe=ef92697af7) | Feb 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [919eb44cc5](https://linux-hardware.org/?probe=919eb44cc5) | Feb 07, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [28bb1241de](https://linux-hardware.org/?probe=28bb1241de) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [64e32a1354](https://linux-hardware.org/?probe=64e32a1354) | Feb 02, 2022 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| HP            | 1905                        | Desktop     | [8014fae46e](https://linux-hardware.org/?probe=8014fae46e) | Feb 02, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [4998bf6630](https://linux-hardware.org/?probe=4998bf6630) | Feb 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c2b7d7cdd1](https://linux-hardware.org/?probe=c2b7d7cdd1) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [ee91c21eb4](https://linux-hardware.org/?probe=ee91c21eb4) | Feb 01, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b8f0614b9c](https://linux-hardware.org/?probe=b8f0614b9c) | Feb 01, 2022 |
| HP            | Pavilion g6                 | Notebook    | [be25fc4f46](https://linux-hardware.org/?probe=be25fc4f46) | Feb 01, 2022 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [de0d67e8c4](https://linux-hardware.org/?probe=de0d67e8c4) | Jan 31, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [ecb2fdb4a3](https://linux-hardware.org/?probe=ecb2fdb4a3) | Jan 29, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [4108d2071b](https://linux-hardware.org/?probe=4108d2071b) | Jan 28, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [670589ec65](https://linux-hardware.org/?probe=670589ec65) | Jan 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5c5ac9fe1d](https://linux-hardware.org/?probe=5c5ac9fe1d) | Jan 26, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [317ebaa644](https://linux-hardware.org/?probe=317ebaa644) | Jan 26, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [215b5c3802](https://linux-hardware.org/?probe=215b5c3802) | Jan 23, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [cc0c86531b](https://linux-hardware.org/?probe=cc0c86531b) | Jan 22, 2022 |
| MSI           | B150M ECO                   | Desktop     | [d484e899ef](https://linux-hardware.org/?probe=d484e899ef) | Jan 22, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [56e21b8bd6](https://linux-hardware.org/?probe=56e21b8bd6) | Jan 22, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [6586f2d78f](https://linux-hardware.org/?probe=6586f2d78f) | Jan 22, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [a8cf42152e](https://linux-hardware.org/?probe=a8cf42152e) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [3b7c230363](https://linux-hardware.org/?probe=3b7c230363) | Jan 21, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [b09195fb3c](https://linux-hardware.org/?probe=b09195fb3c) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [211aac7b59](https://linux-hardware.org/?probe=211aac7b59) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | Notebook    | [206ce8c174](https://linux-hardware.org/?probe=206ce8c174) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | Notebook    | [6eafcfd89d](https://linux-hardware.org/?probe=6eafcfd89d) | Jan 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [57e7500f2a](https://linux-hardware.org/?probe=57e7500f2a) | Jan 17, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Acer          | Swift SF514-54T             | Notebook    | [dffa1b1708](https://linux-hardware.org/?probe=dffa1b1708) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | Notebook    | [cf529c7ad0](https://linux-hardware.org/?probe=cf529c7ad0) | Jan 14, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [e1f153a5e6](https://linux-hardware.org/?probe=e1f153a5e6) | Jan 14, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5ca44fe54c](https://linux-hardware.org/?probe=5ca44fe54c) | Jan 10, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [0462560ab2](https://linux-hardware.org/?probe=0462560ab2) | Jan 10, 2022 |
| ASRock        | FM2A88X Pro3+               | Desktop     | [1cc054ed3f](https://linux-hardware.org/?probe=1cc054ed3f) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [568c503df0](https://linux-hardware.org/?probe=568c503df0) | Jan 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fb627691ce](https://linux-hardware.org/?probe=fb627691ce) | Jan 07, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [2542ffac8a](https://linux-hardware.org/?probe=2542ffac8a) | Jan 06, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | Notebook    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [c22ba841f6](https://linux-hardware.org/?probe=c22ba841f6) | Jan 06, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [2e5c796311](https://linux-hardware.org/?probe=2e5c796311) | Jan 06, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [be76fa91bc](https://linux-hardware.org/?probe=be76fa91bc) | Jan 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8e11cb731a](https://linux-hardware.org/?probe=8e11cb731a) | Jan 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b58f7257b9](https://linux-hardware.org/?probe=b58f7257b9) | Jan 05, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [be129c3a7a](https://linux-hardware.org/?probe=be129c3a7a) | Jan 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | Notebook    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| MSI           | GP66 Leopard 10UH           | Notebook    | [e9689e292c](https://linux-hardware.org/?probe=e9689e292c) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [aa4f09754b](https://linux-hardware.org/?probe=aa4f09754b) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [411cf580b4](https://linux-hardware.org/?probe=411cf580b4) | Jan 04, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [5ce6cac5cb](https://linux-hardware.org/?probe=5ce6cac5cb) | Jan 04, 2022 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [608af1b572](https://linux-hardware.org/?probe=608af1b572) | Jan 04, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c804b37a93](https://linux-hardware.org/?probe=c804b37a93) | Jan 04, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [c10faa4e15](https://linux-hardware.org/?probe=c10faa4e15) | Jan 04, 2022 |
| ASUSTek       | N43SL                       | Notebook    | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [9b8e2862e0](https://linux-hardware.org/?probe=9b8e2862e0) | Jan 04, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [ab40f6782f](https://linux-hardware.org/?probe=ab40f6782f) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [56db8627d8](https://linux-hardware.org/?probe=56db8627d8) | Jan 04, 2022 |
| Positivo      | POS-PIH81DI                 | Desktop     | [c2f06752f5](https://linux-hardware.org/?probe=c2f06752f5) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5ce8d98461](https://linux-hardware.org/?probe=5ce8d98461) | Jan 04, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [4020ca9754](https://linux-hardware.org/?probe=4020ca9754) | Jan 04, 2022 |
| Timi          | A35S                        | Notebook    | [2dafd53d09](https://linux-hardware.org/?probe=2dafd53d09) | Jan 04, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [12ce36d52f](https://linux-hardware.org/?probe=12ce36d52f) | Jan 03, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [2edffdea76](https://linux-hardware.org/?probe=2edffdea76) | Jan 03, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [1ebd581629](https://linux-hardware.org/?probe=1ebd581629) | Jan 01, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [a611e12778](https://linux-hardware.org/?probe=a611e12778) | Dec 31, 2021 |
| Dell          | Precision 5560              | Notebook    | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89d144f949](https://linux-hardware.org/?probe=89d144f949) | Dec 31, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [9a67c15230](https://linux-hardware.org/?probe=9a67c15230) | Dec 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [211b09522f](https://linux-hardware.org/?probe=211b09522f) | Dec 31, 2021 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [e4d3f29412](https://linux-hardware.org/?probe=e4d3f29412) | Dec 30, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [c85d7c78e7](https://linux-hardware.org/?probe=c85d7c78e7) | Dec 28, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [b608797946](https://linux-hardware.org/?probe=b608797946) | Dec 28, 2021 |
| LattePanda    | Alpha                       | Desktop     | [497e370fc3](https://linux-hardware.org/?probe=497e370fc3) | Dec 26, 2021 |
| Biostar       | G31-M7 TE                   | Desktop     | [abb80ccd85](https://linux-hardware.org/?probe=abb80ccd85) | Dec 25, 2021 |
| LattePanda    | Alpha                       | Desktop     | [442f08d351](https://linux-hardware.org/?probe=442f08d351) | Dec 24, 2021 |
| Gigabyte      | M68M-S2P                    | Desktop     | [c06c8838d2](https://linux-hardware.org/?probe=c06c8838d2) | Dec 24, 2021 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [a4a8130a06](https://linux-hardware.org/?probe=a4a8130a06) | Dec 24, 2021 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [c460e492aa](https://linux-hardware.org/?probe=c460e492aa) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [756df875af](https://linux-hardware.org/?probe=756df875af) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [cd01eec1a8](https://linux-hardware.org/?probe=cd01eec1a8) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [4d153ddb81](https://linux-hardware.org/?probe=4d153ddb81) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [deb1a17957](https://linux-hardware.org/?probe=deb1a17957) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [ca89ed6eab](https://linux-hardware.org/?probe=ca89ed6eab) | Dec 23, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [17067982ca](https://linux-hardware.org/?probe=17067982ca) | Dec 23, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [384617e5a7](https://linux-hardware.org/?probe=384617e5a7) | Dec 22, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [8c9fc05c39](https://linux-hardware.org/?probe=8c9fc05c39) | Dec 22, 2021 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [aa7388fdd1](https://linux-hardware.org/?probe=aa7388fdd1) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [f51d57d3bc](https://linux-hardware.org/?probe=f51d57d3bc) | Dec 21, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [7a6594a954](https://linux-hardware.org/?probe=7a6594a954) | Dec 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ac70723f1b](https://linux-hardware.org/?probe=ac70723f1b) | Dec 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Unknown       | Intel X79                   | Desktop     | [767fb84ac9](https://linux-hardware.org/?probe=767fb84ac9) | Dec 17, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0LU0... | Notebook    | [ab6c683160](https://linux-hardware.org/?probe=ab6c683160) | Dec 16, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [16daa16444](https://linux-hardware.org/?probe=16daa16444) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [bc313ce031](https://linux-hardware.org/?probe=bc313ce031) | Dec 15, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [8c9d779e45](https://linux-hardware.org/?probe=8c9d779e45) | Dec 14, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a34aa5357b](https://linux-hardware.org/?probe=a34aa5357b) | Dec 14, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [6d5612f136](https://linux-hardware.org/?probe=6d5612f136) | Dec 13, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [641af2bfa6](https://linux-hardware.org/?probe=641af2bfa6) | Dec 13, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [bdfec258d5](https://linux-hardware.org/?probe=bdfec258d5) | Dec 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [96e7ac029b](https://linux-hardware.org/?probe=96e7ac029b) | Dec 10, 2021 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [939be3ba51](https://linux-hardware.org/?probe=939be3ba51) | Dec 10, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [706fc926ca](https://linux-hardware.org/?probe=706fc926ca) | Dec 08, 2021 |
| Dell          | Latitude 7480               | Notebook    | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [2070780ca9](https://linux-hardware.org/?probe=2070780ca9) | Dec 07, 2021 |
| Framework     | Laptop                      | Notebook    | [c1a31372f4](https://linux-hardware.org/?probe=c1a31372f4) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [b49088935d](https://linux-hardware.org/?probe=b49088935d) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [7cdf0f8f44](https://linux-hardware.org/?probe=7cdf0f8f44) | Dec 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [78c796c1fc](https://linux-hardware.org/?probe=78c796c1fc) | Dec 02, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | Bravo 15 B5DD               | Notebook    | [fc7c1ff3c8](https://linux-hardware.org/?probe=fc7c1ff3c8) | Nov 24, 2021 |
| Unknown       | Unknown                     | Notebook    | [b862ee20d9](https://linux-hardware.org/?probe=b862ee20d9) | Nov 24, 2021 |
| Unknown       | Unknown                     | Notebook    | [0555569b70](https://linux-hardware.org/?probe=0555569b70) | Nov 24, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [7fbe80215d](https://linux-hardware.org/?probe=7fbe80215d) | Nov 24, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [2b67e46016](https://linux-hardware.org/?probe=2b67e46016) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| MSI           | GS63VR 6RF                  | Notebook    | [2d9061c72e](https://linux-hardware.org/?probe=2d9061c72e) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [e6eb602b05](https://linux-hardware.org/?probe=e6eb602b05) | Nov 22, 2021 |
| HP            | 15 TS                       | Notebook    | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [a3d3e0eecd](https://linux-hardware.org/?probe=a3d3e0eecd) | Nov 20, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [89ea080ce0](https://linux-hardware.org/?probe=89ea080ce0) | Nov 20, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [ec54ffae7a](https://linux-hardware.org/?probe=ec54ffae7a) | Nov 18, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [505925412f](https://linux-hardware.org/?probe=505925412f) | Nov 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [778d32ce4b](https://linux-hardware.org/?probe=778d32ce4b) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [9fc3f12603](https://linux-hardware.org/?probe=9fc3f12603) | Nov 16, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/EndeavourOS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 796       | 83.79%  |
| EndeavourOS         | 154       | 16.21%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| EndeavourOS | 940       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 5.15.12-arch1-1  | 20        | 1.83%   |
| 6.2.8-arch1-1    | 18        | 1.65%   |
| 6.1.1-arch1-1    | 16        | 1.47%   |
| 6.3.1-arch1-1    | 13        | 1.19%   |
| 6.1.12-arch1-1   | 13        | 1.19%   |
| 6.2.2-arch1-1    | 11        | 1.01%   |
| 6.0.9-arch1-1    | 11        | 1.01%   |
| 6.0.2-arch1-1    | 11        | 1.01%   |
| 5.17.1-arch1-1   | 11        | 1.01%   |
| 6.2.13-arch1-1   | 10        | 0.92%   |
| 6.2.10-arch1-1   | 10        | 0.92%   |
| 5.17.5-arch1-1   | 10        | 0.92%   |
| 6.3.4-arch1-1    | 9         | 0.82%   |
| 6.0.2-zen1-1-zen | 9         | 0.82%   |
| 6.0.12-arch1-1   | 9         | 0.82%   |
| 5.19.7-arch1-1   | 9         | 0.82%   |
| 5.15.10-arch1-1  | 9         | 0.82%   |
| 6.2.9-arch1-1    | 8         | 0.73%   |
| 5.17.9-arch1-1   | 8         | 0.73%   |
| 5.15.7-arch1-1   | 8         | 0.73%   |
| 5.14.9-arch2-1   | 8         | 0.73%   |
| 5.13.13-arch1-1  | 8         | 0.73%   |
| 5.11.11-arch1-1  | 8         | 0.73%   |
| 6.1.11-arch1-1   | 7         | 0.64%   |
| 5.9.14-arch1-1   | 7         | 0.64%   |
| 5.19.12-arch1-1  | 7         | 0.64%   |
| 5.18.16-arch1-1  | 7         | 0.64%   |
| 5.18.12-arch1-1  | 7         | 0.64%   |
| 5.16.10-arch1-1  | 7         | 0.64%   |
| 6.2.12-arch1-1   | 6         | 0.55%   |
| 6.1.9-arch1-2    | 6         | 0.55%   |
| 6.1.8-arch1-1    | 6         | 0.55%   |
| 6.1.7-arch1-1    | 6         | 0.55%   |
| 6.1.4-arch1-1    | 6         | 0.55%   |
| 6.0.6-arch1-1    | 6         | 0.55%   |
| 5.9.1-arch1-1    | 6         | 0.55%   |
| 5.7.7-arch1-1    | 6         | 0.55%   |
| 5.19.11-arch1-1  | 6         | 0.55%   |
| 5.16.2-arch1-1   | 6         | 0.55%   |
| 5.15.4-arch1-1   | 6         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.12 | 28        | 2.57%   |
| 6.1.1   | 23        | 2.11%   |
| 6.0.2   | 22        | 2.02%   |
| 6.3.1   | 20        | 1.83%   |
| 6.2.8   | 20        | 1.83%   |
| 6.1.12  | 15        | 1.37%   |
| 6.0.9   | 15        | 1.37%   |
| 5.17.1  | 15        | 1.37%   |
| 6.2.2   | 14        | 1.28%   |
| 5.17.5  | 14        | 1.28%   |
| 6.3.4   | 13        | 1.19%   |
| 6.2.13  | 13        | 1.19%   |
| 6.2.10  | 12        | 1.1%    |
| 6.0.6   | 12        | 1.1%    |
| 6.0.12  | 12        | 1.1%    |
| 5.13.13 | 12        | 1.1%    |
| 6.2.9   | 11        | 1.01%   |
| 5.19.7  | 11        | 1.01%   |
| 5.18.12 | 11        | 1.01%   |
| 5.17.9  | 11        | 1.01%   |
| 5.19.9  | 10        | 0.92%   |
| 5.14.9  | 10        | 0.92%   |
| 6.3.5   | 9         | 0.82%   |
| 6.1.9   | 9         | 0.82%   |
| 5.19.13 | 9         | 0.82%   |
| 5.18.16 | 9         | 0.82%   |
| 5.15.7  | 9         | 0.82%   |
| 5.15.4  | 9         | 0.82%   |
| 5.15.10 | 9         | 0.82%   |
| 5.11.11 | 9         | 0.82%   |
| 6.1.8   | 8         | 0.73%   |
| 6.1.7   | 8         | 0.73%   |
| 6.1.4   | 8         | 0.73%   |
| 5.9.1   | 8         | 0.73%   |
| 5.19.12 | 8         | 0.73%   |
| 5.16.16 | 8         | 0.73%   |
| 5.15.2  | 8         | 0.73%   |
| 5.12.13 | 8         | 0.73%   |
| 5.11.16 | 8         | 0.73%   |
| 6.3.2   | 7         | 0.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 139       | 13.19%  |
| 6.1     | 109       | 10.34%  |
| 6.2     | 100       | 9.49%   |
| 6.0     | 83        | 7.87%   |
| 5.19    | 78        | 7.4%    |
| 5.16    | 66        | 6.26%   |
| 5.17    | 64        | 6.07%   |
| 5.18    | 60        | 5.69%   |
| 6.3     | 56        | 5.31%   |
| 5.14    | 52        | 4.93%   |
| 5.12    | 38        | 3.61%   |
| 5.10    | 38        | 3.61%   |
| 5.11    | 37        | 3.51%   |
| 5.9     | 35        | 3.32%   |
| 5.13    | 35        | 3.32%   |
| 5.8     | 24        | 2.28%   |
| 5.7     | 21        | 1.99%   |
| 5.4     | 7         | 0.66%   |
| 5.6     | 5         | 0.47%   |
| 5.5     | 2         | 0.19%   |
| 4.19    | 2         | 0.19%   |
| 5.2     | 1         | 0.09%   |
| 5.17.1  | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 939       | 99.89%  |
| aarch64 | 1         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 354       | 36.12%  |
| GNOME           | 210       | 21.43%  |
| XFCE            | 192       | 19.59%  |
| X-Cinnamon      | 42        | 4.29%   |
| i3              | 40        | 4.08%   |
| KDE             | 25        | 2.55%   |
| Budgie          | 20        | 2.04%   |
| Unknown         | 20        | 2.04%   |
| Cinnamon        | 15        | 1.53%   |
| sway            | 11        | 1.12%   |
| MATE            | 10        | 1.02%   |
| LXQt            | 9         | 0.92%   |
| Deepin          | 5         | 0.51%   |
| openbox         | 4         | 0.41%   |
| GNOME Flashback | 4         | 0.41%   |
| bspwm           | 4         | 0.41%   |
| Hyprland        | 3         | 0.31%   |
| awesome         | 3         | 0.31%   |
| qtile           | 2         | 0.2%    |
| LXDE            | 2         | 0.2%    |
| xmonad          | 1         | 0.1%    |
| LeftWM          | 1         | 0.1%    |
| jwm             | 1         | 0.1%    |
| herbstluftwm    | 1         | 0.1%    |
| GNOME Classic   | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 724       | 75.42%  |
| Wayland | 187       | 19.48%  |
| Tty     | 34        | 3.54%   |
| Unknown | 14        | 1.46%   |
| Web     | 1         | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 312       | 32.26%  |
| Unknown | 240       | 24.82%  |
| SDDM    | 236       | 24.41%  |
| GDM     | 128       | 13.24%  |
| TDM     | 48        | 4.96%   |
| GREETD  | 2         | 0.21%   |
| LY-DM   | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 473       | 50.05%  |
| en_GB   | 69        | 7.3%    |
| it_IT   | 55        | 5.82%   |
| de_DE   | 54        | 5.71%   |
| en_CA   | 41        | 4.34%   |
| fr_FR   | 22        | 2.33%   |
| ru_RU   | 20        | 2.12%   |
| en_IN   | 20        | 2.12%   |
| en_AU   | 16        | 1.69%   |
| es_ES   | 13        | 1.38%   |
| pt_BR   | 12        | 1.27%   |
| pl_PL   | 12        | 1.27%   |
| Unknown | 12        | 1.27%   |
| nl_NL   | 10        | 1.06%   |
| fi_FI   | 8         | 0.85%   |
| de_AT   | 8         | 0.85%   |
| tr_TR   | 7         | 0.74%   |
| es_MX   | 7         | 0.74%   |
| es_AR   | 7         | 0.74%   |
| en_DK   | 7         | 0.74%   |
| en_AG   | 6         | 0.63%   |
| sv_SE   | 5         | 0.53%   |
| nl_BE   | 5         | 0.53%   |
| en_NZ   | 5         | 0.53%   |
| pt_PT   | 4         | 0.42%   |
| en_PH   | 4         | 0.42%   |
| de_CH   | 4         | 0.42%   |
| en_SG   | 3         | 0.32%   |
| en_HK   | 3         | 0.32%   |
| cs_CZ   | 3         | 0.32%   |
| zh_CN   | 2         | 0.21%   |
| ru_UA   | 2         | 0.21%   |
| hu_HU   | 2         | 0.21%   |
| en_ZA   | 2         | 0.21%   |
| C       | 2         | 0.21%   |
| sr_RS   | 1         | 0.11%   |
| sl_SI   | 1         | 0.11%   |
| sk_SK   | 1         | 0.11%   |
| ko_KR   | 1         | 0.11%   |
| id_ID   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 620       | 65.19%  |
| BIOS | 331       | 34.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 662       | 70.05%  |
| Btrfs   | 238       | 25.19%  |
| Overlay | 21        | 2.22%   |
| Xfs     | 10        | 1.06%   |
| Tmpfs   | 7         | 0.74%   |
| F2fs    | 3         | 0.32%   |
| Unknown | 2         | 0.21%   |
| XXX4    | 1         | 0.11%   |
| Ext2    | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 640       | 67.3%   |
| Unknown | 241       | 25.34%  |
| MBR     | 70        | 7.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 812       | 85.47%  |
| Yes       | 138       | 14.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 642       | 66.94%  |
| Yes       | 317       | 33.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 186       | 19.79%  |
| ASUSTek Computer                     | 173       | 18.4%   |
| Hewlett-Packard                      | 114       | 12.13%  |
| MSI                                  | 89        | 9.47%   |
| Dell                                 | 85        | 9.04%   |
| Gigabyte Technology                  | 67        | 7.13%   |
| Acer                                 | 42        | 4.47%   |
| ASRock                               | 29        | 3.09%   |
| Apple                                | 24        | 2.55%   |
| HUAWEI                               | 14        | 1.49%   |
| Timi                                 | 10        | 1.06%   |
| Samsung Electronics                  | 9         | 0.96%   |
| Microsoft                            | 9         | 0.96%   |
| Google                               | 9         | 0.96%   |
| Toshiba                              | 7         | 0.74%   |
| Unknown                              | 7         | 0.74%   |
| Notebook                             | 6         | 0.64%   |
| Intel                                | 4         | 0.43%   |
| TUXEDO                               | 3         | 0.32%   |
| Sony                                 | 3         | 0.32%   |
| Schenker                             | 3         | 0.32%   |
| Positivo                             | 3         | 0.32%   |
| AZW                                  | 3         | 0.32%   |
| ZOTAC                                | 2         | 0.21%   |
| TrekStor                             | 2         | 0.21%   |
| Razer                                | 2         | 0.21%   |
| Packard Bell                         | 2         | 0.21%   |
| Huanan                               | 2         | 0.21%   |
| GPD                                  | 2         | 0.21%   |
| Fujitsu                              | 2         | 0.21%   |
| Chuwi                                | 2         | 0.21%   |
| Biostar                              | 2         | 0.21%   |
| AMI                                  | 2         | 0.21%   |
| Alienware                            | 2         | 0.21%   |
| VIT                                  | 1         | 0.11%   |
| UMAX                                 | 1         | 0.11%   |
| Shinelon Computer                    | 1         | 0.11%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.11%   |
| Radxa                                | 1         | 0.11%   |
| Pine Microsystems                    | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7C37                           | 10        | 1.06%   |
| ASUS All Series                       | 9         | 0.96%   |
| Unknown                               | 8         | 0.85%   |
| Apple MacBookAir7,2                   | 6         | 0.64%   |
| MSI MS-7C02                           | 5         | 0.53%   |
| ASUS TUF Gaming X570-PLUS             | 5         | 0.53%   |
| ASUS ROG STRIX X570-E GAMING          | 5         | 0.53%   |
| Gigabyte B450 AORUS ELITE             | 4         | 0.43%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 4         | 0.43%   |
| ASRock B450M Pro4                     | 4         | 0.43%   |
| ASRock B450 Pro4                      | 4         | 0.43%   |
| MSI MS-7C91                           | 3         | 0.32%   |
| MSI MS-7A38                           | 3         | 0.32%   |
| MSI Modern 14 B5M                     | 3         | 0.32%   |
| Microsoft Surface Laptop Go           | 3         | 0.32%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.32%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 3         | 0.32%   |
| Lenovo Legion 5 15ACH6H 82JU          | 3         | 0.32%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 3         | 0.32%   |
| HUAWEI KLVL-WXX9                      | 3         | 0.32%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 3         | 0.32%   |
| Gigabyte B550M AORUS PRO              | 3         | 0.32%   |
| Gigabyte B450M DS3H                   | 3         | 0.32%   |
| Acer Aspire E5-575G                   | 3         | 0.32%   |
| Timi TM1701                           | 2         | 0.21%   |
| Timi A35S                             | 2         | 0.21%   |
| Samsung 950QDB                        | 2         | 0.21%   |
| Samsung 340XAA/350XAA/550XAA          | 2         | 0.21%   |
| Positivo S14BW01                      | 2         | 0.21%   |
| MSI MS-7D25                           | 2         | 0.21%   |
| MSI MS-7C84                           | 2         | 0.21%   |
| MSI MS-7C56                           | 2         | 0.21%   |
| MSI MS-7C52                           | 2         | 0.21%   |
| MSI MS-7B86                           | 2         | 0.21%   |
| MSI MS-7B85                           | 2         | 0.21%   |
| MSI MS-7A74                           | 2         | 0.21%   |
| MSI MS-7A34                           | 2         | 0.21%   |
| MSI MS-7850                           | 2         | 0.21%   |
| MSI MS-7798                           | 2         | 0.21%   |
| Microsoft Surface Go                  | 2         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 85        | 9.04%   |
| ASUS ROG           | 43        | 4.57%   |
| Lenovo IdeaPad     | 38        | 4.04%   |
| Acer Aspire        | 26        | 2.77%   |
| HP Pavilion        | 24        | 2.55%   |
| Dell Inspiron      | 24        | 2.55%   |
| Dell Latitude      | 22        | 2.34%   |
| ASUS TUF           | 21        | 2.23%   |
| Lenovo Yoga        | 16        | 1.7%    |
| HP EliteBook       | 16        | 1.7%    |
| ASUS PRIME         | 16        | 1.7%    |
| HP Laptop          | 15        | 1.6%    |
| ASUS VivoBook      | 13        | 1.38%   |
| Dell OptiPlex      | 12        | 1.28%   |
| Lenovo Legion      | 11        | 1.17%   |
| HP ENVY            | 11        | 1.17%   |
| MSI MS-7C37        | 10        | 1.06%   |
| Lenovo ThinkBook   | 10        | 1.06%   |
| Microsoft Surface  | 9         | 0.96%   |
| ASUS All           | 9         | 0.96%   |
| MSI Modern         | 8         | 0.85%   |
| Dell Precision     | 8         | 0.85%   |
| Unknown            | 8         | 0.85%   |
| Gigabyte B450      | 7         | 0.74%   |
| Dell XPS           | 7         | 0.74%   |
| ASUS Zenbook       | 7         | 0.74%   |
| ASUS ASUS          | 7         | 0.74%   |
| Toshiba Satellite  | 6         | 0.64%   |
| Gigabyte X570      | 6         | 0.64%   |
| ASRock B450        | 6         | 0.64%   |
| Apple MacBookAir7  | 6         | 0.64%   |
| Acer Swift         | 6         | 0.64%   |
| MSI MS-7C02        | 5         | 0.53%   |
| Lenovo ThinkCentre | 5         | 0.53%   |
| HP 255             | 5         | 0.53%   |
| Gigabyte B550      | 5         | 0.53%   |
| Gigabyte B450M     | 5         | 0.53%   |
| Lenovo IdeaPadFlex | 4         | 0.43%   |
| Lenovo IdeaCentre  | 4         | 0.43%   |
| HP ZBook           | 4         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 133       | 14.15%  |
| 2020    | 133       | 14.15%  |
| 2019    | 124       | 13.19%  |
| 2018    | 117       | 12.45%  |
| 2017    | 64        | 6.81%   |
| 2022    | 63        | 6.7%    |
| 2013    | 55        | 5.85%   |
| 2016    | 49        | 5.21%   |
| 2015    | 48        | 5.11%   |
| 2012    | 44        | 4.68%   |
| 2014    | 38        | 4.04%   |
| 2011    | 25        | 2.66%   |
| 2010    | 13        | 1.38%   |
| 2009    | 12        | 1.28%   |
| 2008    | 12        | 1.28%   |
| 2007    | 7         | 0.74%   |
| 2023    | 2         | 0.21%   |
| Unknown | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 549       | 58.4%   |
| Desktop     | 311       | 33.09%  |
| Convertible | 45        | 4.79%   |
| All in one  | 14        | 1.49%   |
| Tablet      | 10        | 1.06%   |
| Mini pc     | 10        | 1.06%   |
| Server      | 1         | 0.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 936       | 99.57%  |
| Enabled  | 4         | 0.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 930       | 98.94%  |
| Yes  | 10        | 1.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 244       | 25.77%  |
| 4.01-8.0    | 209       | 22.07%  |
| 8.01-16.0   | 208       | 21.96%  |
| 32.01-64.0  | 146       | 15.42%  |
| 3.01-4.0    | 77        | 8.13%   |
| 24.01-32.0  | 32        | 3.38%   |
| 64.01-256.0 | 22        | 2.32%   |
| 1.01-2.0    | 6         | 0.63%   |
| 2.01-3.0    | 3         | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 263       | 25.71%  |
| 4.01-8.0   | 238       | 23.26%  |
| 1.01-2.0   | 228       | 22.29%  |
| 3.01-4.0   | 182       | 17.79%  |
| 8.01-16.0  | 71        | 6.94%   |
| 0.51-1.0   | 26        | 2.54%   |
| 16.01-24.0 | 10        | 0.98%   |
| 24.01-32.0 | 3         | 0.29%   |
| 0.01-0.5   | 2         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 515       | 53.2%   |
| 2      | 257       | 26.55%  |
| 3      | 91        | 9.4%    |
| 4      | 58        | 5.99%   |
| 5      | 28        | 2.89%   |
| 6      | 9         | 0.93%   |
| 7      | 4         | 0.41%   |
| 0      | 3         | 0.31%   |
| 8      | 2         | 0.21%   |
| 9      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 758       | 80.21%  |
| Yes       | 187       | 19.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 760       | 80.51%  |
| No        | 184       | 19.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 791       | 83.79%  |
| No        | 153       | 16.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 744       | 78.4%   |
| No        | 205       | 21.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 210       | 22.2%   |
| Germany     | 87        | 9.2%    |
| Italy       | 81        | 8.56%   |
| Canada      | 45        | 4.76%   |
| France      | 36        | 3.81%   |
| Poland      | 29        | 3.07%   |
| Netherlands | 29        | 3.07%   |
| India       | 27        | 2.85%   |
| Brazil      | 25        | 2.64%   |
| UK          | 24        | 2.54%   |
| Russia      | 24        | 2.54%   |
| Spain       | 21        | 2.22%   |
| Finland     | 20        | 2.11%   |
| Australia   | 19        | 2.01%   |
| Turkey      | 16        | 1.69%   |
| Belgium     | 16        | 1.69%   |
| Austria     | 16        | 1.69%   |
| Sweden      | 15        | 1.59%   |
| Mexico      | 11        | 1.16%   |
| Indonesia   | 9         | 0.95%   |
| Argentina   | 9         | 0.95%   |
| Romania     | 8         | 0.85%   |
| Switzerland | 7         | 0.74%   |
| Hong Kong   | 7         | 0.74%   |
| Denmark     | 7         | 0.74%   |
| Ukraine     | 6         | 0.63%   |
| Portugal    | 6         | 0.63%   |
| Greece      | 6         | 0.63%   |
| Czechia     | 6         | 0.63%   |
| Bangladesh  | 6         | 0.63%   |
| Vietnam     | 5         | 0.53%   |
| Slovenia    | 5         | 0.53%   |
| Norway      | 5         | 0.53%   |
| New Zealand | 5         | 0.53%   |
| Malaysia    | 5         | 0.53%   |
| Hungary     | 5         | 0.53%   |
| Croatia     | 5         | 0.53%   |
| Singapore   | 4         | 0.42%   |
| Serbia      | 4         | 0.42%   |
| Philippines | 4         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Montreal          | 13        | 1.31%   |
| Helsinki          | 12        | 1.21%   |
| Berlin            | 12        | 1.21%   |
| Amsterdam         | 10        | 1.01%   |
| Sydney            | 8         | 0.8%    |
| St Petersburg     | 8         | 0.8%    |
| Milan             | 8         | 0.8%    |
| Warsaw            | 7         | 0.7%    |
| Toms River        | 7         | 0.7%    |
| Paris             | 7         | 0.7%    |
| Istanbul          | 7         | 0.7%    |
| Hamburg           | 7         | 0.7%    |
| Rome              | 6         | 0.6%    |
| Moscow            | 6         | 0.6%    |
| Turin             | 5         | 0.5%    |
| Toronto           | 5         | 0.5%    |
| Madrid            | 5         | 0.5%    |
| Frankfurt am Main | 5         | 0.5%    |
| Barberton         | 5         | 0.5%    |
| Zurich            | 4         | 0.4%    |
| Wroclaw           | 4         | 0.4%    |
| Vienna            | 4         | 0.4%    |
| Victoria          | 4         | 0.4%    |
| Singapore         | 4         | 0.4%    |
| Portland          | 4         | 0.4%    |
| Ottawa            | 4         | 0.4%    |
| Melbourne         | 4         | 0.4%    |
| London            | 4         | 0.4%    |
| Leipzig           | 4         | 0.4%    |
| Jacksonville      | 4         | 0.4%    |
| Brussels          | 4         | 0.4%    |
| Belgrade          | 4         | 0.4%    |
| Zirl              | 3         | 0.3%    |
| Villa Ballester   | 3         | 0.3%    |
| Sofia             | 3         | 0.3%    |
| Severna Park      | 3         | 0.3%    |
| Seattle           | 3         | 0.3%    |
| Schiedam          | 3         | 0.3%    |
| Rotterdam         | 3         | 0.3%    |
| Phoenix           | 3         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 315       | 471    | 20.71%  |
| Seagate                        | 183       | 256    | 12.03%  |
| WDC                            | 173       | 268    | 11.37%  |
| Kingston                       | 104       | 147    | 6.84%   |
| SanDisk                        | 101       | 120    | 6.64%   |
| Crucial                        | 71        | 100    | 4.67%   |
| Toshiba                        | 60        | 70     | 3.94%   |
| SK hynix                       | 51        | 61     | 3.35%   |
| Micron Technology              | 37        | 39     | 2.43%   |
| Intel                          | 37        | 48     | 2.43%   |
| Unknown                        | 35        | 48     | 2.3%    |
| HGST                           | 25        | 32     | 1.64%   |
| KIOXIA                         | 21        | 22     | 1.38%   |
| Hitachi                        | 20        | 21     | 1.31%   |
| Phison                         | 19        | 20     | 1.25%   |
| Apple                          | 18        | 25     | 1.18%   |
| A-DATA Technology              | 18        | 26     | 1.18%   |
| Phison Electronics             | 15        | 16     | 0.99%   |
| Kingston Technology Company    | 13        | 15     | 0.85%   |
| China                          | 12        | 12     | 0.79%   |
| Corsair                        | 9         | 9      | 0.59%   |
| PNY                            | 8         | 9      | 0.53%   |
| LITEONIT                       | 7         | 8      | 0.46%   |
| SPCC                           | 6         | 6      | 0.39%   |
| Patriot                        | 6         | 8      | 0.39%   |
| OCZ                            | 6         | 6      | 0.39%   |
| XPG                            | 5         | 5      | 0.33%   |
| Transcend                      | 5         | 6      | 0.33%   |
| Silicon Motion                 | 5         | 5      | 0.33%   |
| Mushkin                        | 5         | 5      | 0.33%   |
| Micron/Crucial Technology      | 5         | 12     | 0.33%   |
| Intenso                        | 5         | 7      | 0.33%   |
| Gigabyte Technology            | 5         | 7      | 0.33%   |
| SABRENT                        | 4         | 6      | 0.26%   |
| LITEON                         | 4         | 6      | 0.26%   |
| JMicron Technology             | 4         | 4      | 0.26%   |
| Union Memory (Shenzhen)        | 3         | 3      | 0.2%    |
| Solid State Storage Technology | 3         | 4      | 0.2%    |
| Realtek                        | 3         | 4      | 0.2%    |
| Netac                          | 3         | 4      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 43        | 2.53%   |
| Seagate ST2000DM008-2FR102 2TB                      | 23        | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB                      | 19        | 1.12%   |
| Samsung SSD 860 EVO 1TB                             | 19        | 1.12%   |
| Crucial CT500MX500SSD1 500GB                        | 18        | 1.06%   |
| Kingston SA400S37240G 240GB SSD                     | 17        | 1%      |
| Samsung SSD 860 EVO 500GB                           | 16        | 0.94%   |
| Samsung SSD 850 EVO 250GB                           | 16        | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 16        | 0.94%   |
| Kingston SA400S37120G 120GB SSD                     | 15        | 0.88%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 14        | 0.82%   |
| Samsung SSD 850 EVO 500GB                           | 13        | 0.77%   |
| Samsung SSD 870 QVO 1TB                             | 12        | 0.71%   |
| Kingston SA400S37480G 480GB SSD                     | 12        | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB                      | 11        | 0.65%   |
| HGST HTS721010A9E630 1TB                            | 11        | 0.65%   |
| Seagate ST4000DM004-2CV104 4TB                      | 10        | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 10        | 0.59%   |
| Samsung SSD 860 EVO 250GB                           | 10        | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 9         | 0.53%   |
| Samsung SSD 970 EVO 500GB                           | 9         | 0.53%   |
| Crucial CT240BX500SSD1 240GB                        | 9         | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                         | 9         | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 8         | 0.47%   |
| Seagate ST500LT012-1DG142 500GB                     | 8         | 0.47%   |
| Unknown SD/MMC/MS PRO 64GB                          | 7         | 0.41%   |
| Seagate ST2000DM006-2DM164 2TB                      | 7         | 0.41%   |
| Seagate Expansion Desk 4TB                          | 7         | 0.41%   |
| Samsung SSD 980 500GB                               | 7         | 0.41%   |
| Samsung NVMe SSD Drive 512GB                        | 7         | 0.41%   |
| Samsung NVMe SSD Drive 1TB                          | 7         | 0.41%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 7         | 0.41%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 6         | 0.35%   |
| Unknown MMC Card  64GB                              | 6         | 0.35%   |
| Unknown MMC Card  128GB                             | 6         | 0.35%   |
| SK hynix HFM001TD3JX013N 1TB                        | 6         | 0.35%   |
| Seagate Expansion 1TB                               | 6         | 0.35%   |
| Samsung SSD 870 EVO 250GB                           | 6         | 0.35%   |
| KIOXIA KBG40ZNV512G 512GB                           | 6         | 0.35%   |
| Apple SSD SM0128G 121GB                             | 6         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 174       | 243    | 42.23%  |
| WDC                 | 118       | 177    | 28.64%  |
| Toshiba             | 37        | 41     | 8.98%   |
| HGST                | 25        | 32     | 6.07%   |
| Hitachi             | 20        | 21     | 4.85%   |
| Samsung Electronics | 11        | 26     | 2.67%   |
| Unknown             | 7         | 7      | 1.7%    |
| Maxone              | 3         | 3      | 0.73%   |
| Fujitsu             | 3         | 3      | 0.73%   |
| ASMT                | 2         | 4      | 0.49%   |
| USB3.0              | 1         | 1      | 0.24%   |
| StoreJet            | 1         | 1      | 0.24%   |
| RSH-319             | 1         | 2      | 0.24%   |
| PI-041              | 1         | 1      | 0.24%   |
| Maxtor              | 1         | 1      | 0.24%   |
| JMicron Technology  | 1         | 1      | 0.24%   |
| HPE                 | 1         | 1      | 0.24%   |
| Generic-            | 1         | 1      | 0.24%   |
| Fantom              | 1         | 2      | 0.24%   |
| ASMedia             | 1         | 1      | 0.24%   |
| Apple               | 1         | 1      | 0.24%   |
| Unknown             | 1         | 1      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 162       | 222    | 29.03%  |
| Kingston            | 73        | 107    | 13.08%  |
| Crucial             | 64        | 84     | 11.47%  |
| SanDisk             | 40        | 47     | 7.17%   |
| WDC                 | 39        | 50     | 6.99%   |
| Micron Technology   | 12        | 14     | 2.15%   |
| China               | 12        | 12     | 2.15%   |
| Intel               | 11        | 14     | 1.97%   |
| Apple               | 11        | 14     | 1.97%   |
| A-DATA Technology   | 11        | 12     | 1.97%   |
| Toshiba             | 9         | 11     | 1.61%   |
| SK hynix            | 7         | 8      | 1.25%   |
| LITEONIT            | 7         | 8      | 1.25%   |
| Patriot             | 6         | 8      | 1.08%   |
| OCZ                 | 6         | 6      | 1.08%   |
| Seagate             | 5         | 7      | 0.9%    |
| PNY                 | 5         | 6      | 0.9%    |
| Intenso             | 5         | 7      | 0.9%    |
| Corsair             | 5         | 5      | 0.9%    |
| Transcend           | 4         | 4      | 0.72%   |
| SPCC                | 4         | 4      | 0.72%   |
| SABRENT             | 4         | 6      | 0.72%   |
| Mushkin             | 4         | 4      | 0.72%   |
| Gigabyte Technology | 4         | 5      | 0.72%   |
| LITEON              | 3         | 4      | 0.54%   |
| WDC WDS             | 2         | 2      | 0.36%   |
| Phison              | 2         | 2      | 0.36%   |
| Netac               | 2         | 3      | 0.36%   |
| Leven               | 2         | 3      | 0.36%   |
| KingSpec            | 2         | 2      | 0.36%   |
| GOODRAM             | 2         | 2      | 0.36%   |
| Emtec               | 2         | 2      | 0.36%   |
| Zheino              | 1         | 1      | 0.18%   |
| WALTON              | 1         | 2      | 0.18%   |
| V-GeN               | 1         | 1      | 0.18%   |
| Unknown             | 1         | 2      | 0.18%   |
| UMAX                | 1         | 1      | 0.18%   |
| Timetec             | 1         | 8      | 0.18%   |
| Teclast             | 1         | 3      | 0.18%   |
| Team                | 1         | 2      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 501       | 695    | 37.67%  |
| SSD     | 442       | 732    | 33.23%  |
| HDD     | 343       | 571    | 25.79%  |
| MMC     | 27        | 36     | 2.03%   |
| Unknown | 17        | 23     | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 585       | 1218   | 49.28%  |
| NVMe | 500       | 688    | 42.12%  |
| SAS  | 75        | 115    | 6.32%   |
| MMC  | 27        | 36     | 2.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 418       | 708    | 49.06%  |
| 0.51-1.0   | 268       | 365    | 31.46%  |
| 1.01-2.0   | 91        | 133    | 10.68%  |
| 3.01-4.0   | 34        | 49     | 3.99%   |
| 2.01-3.0   | 17        | 18     | 2%      |
| 4.01-10.0  | 17        | 21     | 2%      |
| 10.01-20.0 | 7         | 9      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 200       | 20.45%  |
| 251-500        | 171       | 17.48%  |
| 1001-2000      | 158       | 16.16%  |
| 501-1000       | 142       | 14.52%  |
| More than 3000 | 90        | 9.2%    |
| Unknown        | 61        | 6.24%   |
| 2001-3000      | 55        | 5.62%   |
| 1-20           | 44        | 4.5%    |
| 51-100         | 38        | 3.89%   |
| 21-50          | 19        | 1.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 221       | 21.65%  |
| 101-250        | 160       | 15.67%  |
| 21-50          | 148       | 14.5%   |
| 51-100         | 131       | 12.83%  |
| 251-500        | 96        | 9.4%    |
| 501-1000       | 86        | 8.42%   |
| 1001-2000      | 76        | 7.44%   |
| Unknown        | 61        | 5.97%   |
| More than 3000 | 25        | 2.45%   |
| 2001-3000      | 13        | 1.27%   |
| 0              | 4         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 4.55%   |
| HGST HTS545050A7E680 500GB               | 4         | 8      | 4.55%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 3      | 3.41%   |
| WDC WD20EARX-00PASB0 2TB                 | 2         | 2      | 2.27%   |
| Seagate ST9320325AS 320GB                | 2         | 5      | 2.27%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 2.27%   |
| Seagate ST500LM021-1KJ152 500GB          | 2         | 7      | 2.27%   |
| XPG GAMMIX S11 240GB                     | 1         | 1      | 1.14%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 1.14%   |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 1         | 1      | 1.14%   |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1      | 1.14%   |
| WDC WD5000LPLX-75ZNTT0 500GB             | 1         | 1      | 1.14%   |
| WDC WD5000AZRX-00A8LB0 500GB             | 1         | 1      | 1.14%   |
| WDC WD5000AVDS-63U7B1 500GB              | 1         | 1      | 1.14%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1         | 2      | 1.14%   |
| WDC WD2003FZEX-00Z4SA0 2TB               | 1         | 1      | 1.14%   |
| WDC WD2002FYPS-01U1B0 2TB                | 1         | 1      | 1.14%   |
| WDC WD10SPZX-24Z10T0 1TB                 | 1         | 1      | 1.14%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.14%   |
| WDC WD10EARS-00MVWB0 1TB                 | 1         | 1      | 1.14%   |
| WDC WD10EACS-00D6B1 1TB                  | 1         | 1      | 1.14%   |
| WDC WD1003FBYZ-010FB0 1TB                | 1         | 2      | 1.14%   |
| WDC WD Blue SA510 2.5 1TB SSD            | 1         | 1      | 1.14%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB     | 1         | 1      | 1.14%   |
| Transcend TS240GMTS420S 240GB SSD        | 1         | 1      | 1.14%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 1.14%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 1.14%   |
| Toshiba MK5055GSXF 500GB                 | 1         | 1      | 1.14%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1      | 1.14%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 1.14%   |
| SK hynix SC308 SATA 128GB SSD            | 1         | 1      | 1.14%   |
| SK hynix HFS512G39TND-N210A 512GB SSD    | 1         | 1      | 1.14%   |
| SK hynix HFS128G39TND-N210A 128GB SSD    | 1         | 1      | 1.14%   |
| Seagate ST6000VX0023-2EF110 6TB          | 1         | 1      | 1.14%   |
| Seagate ST500LX012-SSHD-8GB              | 1         | 1      | 1.14%   |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 1      | 1.14%   |
| Seagate ST3320620AS 320GB                | 1         | 1      | 1.14%   |
| Seagate ST2000LX001-1RG174 2TB           | 1         | 1      | 1.14%   |
| Seagate ST2000DX002-2DV164 2TB           | 1         | 1      | 1.14%   |
| Seagate ST2000DM001-1ER164 2TB           | 1         | 1      | 1.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 20     | 19.77%  |
| Seagate             | 17        | 28     | 19.77%  |
| Samsung Electronics | 8         | 10     | 9.3%    |
| HGST                | 8         | 12     | 9.3%    |
| Toshiba             | 5         | 5      | 5.81%   |
| Hitachi             | 5         | 5      | 5.81%   |
| SK hynix            | 3         | 3      | 3.49%   |
| SanDisk             | 3         | 4      | 3.49%   |
| Intel               | 3         | 3      | 3.49%   |
| Crucial             | 3         | 10     | 3.49%   |
| Kingston            | 2         | 2      | 2.33%   |
| Apple               | 2         | 2      | 2.33%   |
| XPG                 | 1         | 1      | 1.16%   |
| Transcend           | 1         | 1      | 1.16%   |
| Patriot             | 1         | 1      | 1.16%   |
| OCZ                 | 1         | 1      | 1.16%   |
| Micron Technology   | 1         | 1      | 1.16%   |
| Fujitsu             | 1         | 1      | 1.16%   |
| Drevo               | 1         | 1      | 1.16%   |
| Corsair             | 1         | 1      | 1.16%   |
| ASMT                | 1         | 2      | 1.16%   |
| A-DATA Technology   | 1         | 1      | 1.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 28     | 34%     |
| WDC                 | 14        | 16     | 28%     |
| HGST                | 8         | 12     | 16%     |
| Hitachi             | 5         | 5      | 10%     |
| Toshiba             | 3         | 3      | 6%      |
| Samsung Electronics | 1         | 1      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |
| ASMT                | 1         | 2      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 68     | 59.04%  |
| SSD  | 28        | 39     | 33.73%  |
| NVMe | 6         | 8      | 7.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 33.33%  |
| Samsung Electronics HD252HJ 250GB | 1         | 1      | 33.33%  |
| LITEON CA3-8D512 512GB            | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| LITEON              | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 655       | 1278   | 62.14%  |
| Detected | 317       | 660    | 30.08%  |
| Malfunc  | 79        | 115    | 7.5%    |
| Failed   | 3         | 4      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 501       | 37.84%  |
| AMD                            | 235       | 17.75%  |
| Samsung Electronics            | 183       | 13.82%  |
| SanDisk                        | 94        | 7.1%    |
| Kingston Technology Company    | 46        | 3.47%   |
| SK hynix                       | 43        | 3.25%   |
| Phison Electronics             | 40        | 3.02%   |
| ASMedia Technology             | 30        | 2.27%   |
| Micron Technology              | 26        | 1.96%   |
| KIOXIA                         | 23        | 1.74%   |
| Toshiba America Info Systems   | 14        | 1.06%   |
| Micron/Crucial Technology      | 12        | 0.91%   |
| ADATA Technology               | 10        | 0.76%   |
| Silicon Motion                 | 8         | 0.6%    |
| Solid State Storage Technology | 7         | 0.53%   |
| Marvell Technology Group       | 7         | 0.53%   |
| Realtek Semiconductor          | 6         | 0.45%   |
| JMicron Technology             | 6         | 0.45%   |
| Apple                          | 6         | 0.45%   |
| Nvidia                         | 5         | 0.38%   |
| Union Memory (Shenzhen)        | 4         | 0.3%    |
| Seagate Technology             | 4         | 0.3%    |
| Lenovo                         | 3         | 0.23%   |
| Transcend                      | 2         | 0.15%   |
| Shenzhen Longsys Electronics   | 2         | 0.15%   |
| Lite-On Technology             | 2         | 0.15%   |
| Yangtze Memory Technologies    | 1         | 0.08%   |
| LSI Logic / Symbios Logic      | 1         | 0.08%   |
| INNOGRIT                       | 1         | 0.08%   |
| Broadcom / LSI                 | 1         | 0.08%   |
| Biwin Storage Technology       | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 180       | 12.53%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 92        | 6.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 60        | 4.18%   |
| AMD 400 Series Chipset SATA Controller                                         | 51        | 3.55%   |
| Samsung NVMe SSD Controller 980                                                | 45        | 3.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 41        | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 30        | 2.09%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 29        | 2.02%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 26        | 1.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 25        | 1.74%   |
| Intel Volume Management Device NVMe RAID Controller                            | 25        | 1.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 25        | 1.74%   |
| Micron NVMe Storage Controller                                                 | 24        | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 24        | 1.67%   |
| AMD 500 Series Chipset SATA Controller                                         | 24        | 1.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 23        | 1.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 22        | 1.53%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 18        | 1.25%   |
| Phison E12 NVMe Controller                                                     | 17        | 1.18%   |
| Kingston Company Company Non-Volatile memory controller                        | 17        | 1.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 17        | 1.18%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 16        | 1.11%   |
| Intel Comet Lake SATA AHCI Controller                                          | 16        | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 16        | 1.11%   |
| Phison E16 PCIe4 NVMe Controller                                               | 15        | 1.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 15        | 1.04%   |
| Intel SSD 660P Series                                                          | 15        | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 15        | 1.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 14        | 0.97%   |
| Intel Tiger Lake-LP SATA Controller                                            | 13        | 0.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 13        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 0.91%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 12        | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 0.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 0.77%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 11        | 0.77%   |
| Kingston Company A2000 NVMe SSD                                                | 10        | 0.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 10        | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 9         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 665       | 52.53%  |
| NVMe | 498       | 39.34%  |
| RAID | 68        | 5.37%   |
| IDE  | 31        | 2.45%   |
| SAS  | 4         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 606       | 64.47%  |
| AMD    | 333       | 35.43%  |
| ARM    | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor            | 16        | 1.7%    |
| AMD Ryzen 5 3600 6-Core Processor             | 16        | 1.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 1.6%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 14        | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 1.38%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 13        | 1.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 1.28%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 1.28%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 1.28%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 12        | 1.28%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 11        | 1.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 1.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.96%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 9         | 0.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 9         | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 0.96%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 9         | 0.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.85%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 8         | 0.85%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 0.85%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.74%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 7         | 0.74%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 0.74%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.74%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 7         | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.64%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 0.64%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.64%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 6         | 0.64%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 6         | 0.64%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 0.64%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 0.53%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.53%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 220       | 23.4%   |
| Intel Core i7           | 176       | 18.72%  |
| AMD Ryzen 5             | 114       | 12.13%  |
| AMD Ryzen 7             | 111       | 11.81%  |
| Other                   | 82        | 8.72%   |
| Intel Core i3           | 43        | 4.57%   |
| AMD Ryzen 9             | 41        | 4.36%   |
| Intel Celeron           | 30        | 3.19%   |
| Intel Core 2 Duo        | 17        | 1.81%   |
| Intel Xeon              | 16        | 1.7%    |
| AMD Ryzen 7 PRO         | 14        | 1.49%   |
| AMD Ryzen 3             | 11        | 1.17%   |
| Intel Pentium           | 9         | 0.96%   |
| AMD A4                  | 8         | 0.85%   |
| AMD FX                  | 6         | 0.64%   |
| Intel Core m3           | 4         | 0.43%   |
| AMD A8                  | 4         | 0.43%   |
| Intel Core i9           | 3         | 0.32%   |
| Intel Core 2 Quad       | 3         | 0.32%   |
| AMD Ryzen Threadripper  | 3         | 0.32%   |
| AMD Ryzen 5 PRO         | 3         | 0.32%   |
| AMD A10                 | 3         | 0.32%   |
| Intel Pentium Dual-Core | 2         | 0.21%   |
| Intel Core 2            | 2         | 0.21%   |
| Intel Atom              | 2         | 0.21%   |
| AMD E1                  | 2         | 0.21%   |
| AMD Athlon              | 2         | 0.21%   |
| Intel Pentium Gold      | 1         | 0.11%   |
| Intel Pentium Dual      | 1         | 0.11%   |
| Intel Core m5           | 1         | 0.11%   |
| Intel Core 2 Extreme    | 1         | 0.11%   |
| AMD Phenom II X4        | 1         | 0.11%   |
| AMD E                   | 1         | 0.11%   |
| AMD Athlon X4           | 1         | 0.11%   |
| AMD Athlon II X4        | 1         | 0.11%   |
| AMD Athlon II           | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 331       | 35.18%  |
| 2      | 247       | 26.25%  |
| 8      | 163       | 17.32%  |
| 6      | 142       | 15.09%  |
| 12     | 27        | 2.87%   |
| 14     | 11        | 1.17%   |
| 10     | 8         | 0.85%   |
| 16     | 7         | 0.74%   |
| 3      | 3         | 0.32%   |
| 32     | 1         | 0.11%   |
| 1      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 935       | 99.36%  |
| 2      | 6         | 0.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 758       | 80.64%  |
| 1      | 182       | 19.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 937       | 99.68%  |
| Unknown        | 2         | 0.21%   |
| 64-bit         | 1         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 352       | 36.55%  |
| 0x0a50000c | 33        | 3.43%   |
| 0x306c3    | 31        | 3.22%   |
| 0x08701021 | 28        | 2.91%   |
| 0x306a9    | 24        | 2.49%   |
| 0x806ea    | 23        | 2.39%   |
| 0x406e3    | 22        | 2.28%   |
| 0x906ea    | 20        | 2.08%   |
| 0x806e9    | 20        | 2.08%   |
| 0x08600106 | 19        | 1.97%   |
| 0x806ec    | 18        | 1.87%   |
| 0x506e3    | 18        | 1.87%   |
| 0x806c1    | 17        | 1.77%   |
| 0x40651    | 16        | 1.66%   |
| 0x08600104 | 16        | 1.66%   |
| 0x08108109 | 16        | 1.66%   |
| 0x906e9    | 15        | 1.56%   |
| 0x08608103 | 15        | 1.56%   |
| 0x706e5    | 12        | 1.25%   |
| 0x206a7    | 11        | 1.14%   |
| 0x0a201009 | 11        | 1.14%   |
| 0x08701013 | 11        | 1.14%   |
| 0x08108102 | 10        | 1.04%   |
| 0x706a1    | 9         | 0.93%   |
| 0x306d4    | 9         | 0.93%   |
| 0x906a3    | 7         | 0.73%   |
| 0x406c4    | 7         | 0.73%   |
| 0x1067a    | 7         | 0.73%   |
| 0x0a404102 | 7         | 0.73%   |
| 0x0a201016 | 7         | 0.73%   |
| 0xa0652    | 6         | 0.62%   |
| 0x806d1    | 6         | 0.62%   |
| 0x0a50000d | 6         | 0.62%   |
| 0x0a20120a | 6         | 0.62%   |
| 0x0800820d | 6         | 0.62%   |
| 0x06006705 | 6         | 0.62%   |
| 0xa0655    | 5         | 0.52%   |
| 0x20655    | 5         | 0.52%   |
| 0x08001138 | 5         | 0.52%   |
| 0xa0653    | 4         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 182       | 19.34%  |
| Zen 2            | 107       | 11.37%  |
| Zen 3            | 88        | 9.35%   |
| Haswell          | 81        | 8.61%   |
| Skylake          | 58        | 6.16%   |
| Unknown          | 56        | 5.95%   |
| Zen+             | 45        | 4.78%   |
| IvyBridge        | 43        | 4.57%   |
| TigerLake        | 36        | 3.83%   |
| CometLake        | 28        | 2.98%   |
| IceLake          | 26        | 2.76%   |
| SandyBridge      | 24        | 2.55%   |
| Broadwell        | 22        | 2.34%   |
| Alderlake Hybrid | 19        | 2.02%   |
| Zen              | 18        | 1.91%   |
| Penryn           | 17        | 1.81%   |
| Silvermont       | 14        | 1.49%   |
| Westmere         | 12        | 1.28%   |
| Goldmont plus    | 12        | 1.28%   |
| Excavator        | 12        | 1.28%   |
| Core             | 10        | 1.06%   |
| Piledriver       | 7         | 0.74%   |
| Jaguar           | 6         | 0.64%   |
| Nehalem          | 5         | 0.53%   |
| Tremont          | 2         | 0.21%   |
| Puma             | 2         | 0.21%   |
| K10              | 2         | 0.21%   |
| Goldmont         | 2         | 0.21%   |
| Bulldozer        | 2         | 0.21%   |
| Steamroller      | 1         | 0.11%   |
| K10 Llano        | 1         | 0.11%   |
| Bobcat           | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 474       | 41.15%  |
| Nvidia | 358       | 31.08%  |
| AMD    | 320       | 27.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 52        | 4.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 3.3%    |
| Intel UHD Graphics 620                                                                   | 38        | 3.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 34        | 2.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 32        | 2.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 31        | 2.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 27        | 2.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 2.2%    |
| Intel HD Graphics 620                                                                    | 25        | 2.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 1.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 1.78%   |
| AMD Lucienne                                                                             | 20        | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 19        | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.35%   |
| AMD Rembrandt [Radeon 680M]                                                              | 16        | 1.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 15        | 1.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.27%   |
| Intel HD Graphics 630                                                                    | 15        | 1.27%   |
| Intel HD Graphics 5500                                                                   | 15        | 1.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 1.1%    |
| Intel HD Graphics 530                                                                    | 13        | 1.1%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 13        | 1.1%    |
| Nvidia GP108M [GeForce MX150]                                                            | 12        | 1.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 1.02%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 12        | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.93%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 11        | 0.93%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 11        | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 10        | 0.85%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 10        | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 0.85%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 9         | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.76%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 8         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 305       | 32.28%  |
| 1 x AMD                  | 236       | 24.97%  |
| 1 x Nvidia               | 172       | 18.2%   |
| Intel + Nvidia           | 140       | 14.81%  |
| AMD + Nvidia             | 41        | 4.34%   |
| 2 x AMD                  | 24        | 2.54%   |
| Intel + AMD              | 20        | 2.12%   |
| 2 x Nvidia               | 3         | 0.32%   |
| 2 x Intel                | 2         | 0.21%   |
| Other                    | 1         | 0.11%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 672       | 71.26%  |
| Proprietary | 270       | 28.63%  |
| Unknown     | 1         | 0.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 519       | 54.23%  |
| 0.01-0.5   | 106       | 11.08%  |
| 1.01-2.0   | 80        | 8.36%   |
| 7.01-8.0   | 76        | 7.94%   |
| 3.01-4.0   | 65        | 6.79%   |
| 5.01-6.0   | 36        | 3.76%   |
| 8.01-16.0  | 32        | 3.34%   |
| 0.51-1.0   | 31        | 3.24%   |
| 2.01-3.0   | 7         | 0.73%   |
| 16.01-24.0 | 5         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 136       | 11.88%  |
| Samsung Electronics     | 119       | 10.39%  |
| BOE                     | 115       | 10.04%  |
| Chimei Innolux          | 102       | 8.91%   |
| LG Display              | 88        | 7.69%   |
| Goldstar                | 56        | 4.89%   |
| Dell                    | 52        | 4.54%   |
| Acer                    | 48        | 4.19%   |
| AOC                     | 39        | 3.41%   |
| Ancor Communications    | 34        | 2.97%   |
| Lenovo                  | 29        | 2.53%   |
| BenQ                    | 29        | 2.53%   |
| Hewlett-Packard         | 26        | 2.27%   |
| Apple                   | 24        | 2.1%    |
| PANDA                   | 22        | 1.92%   |
| ASUSTek Computer        | 21        | 1.83%   |
| Sharp                   | 19        | 1.66%   |
| Philips                 | 15        | 1.31%   |
| ViewSonic               | 14        | 1.22%   |
| InfoVision              | 12        | 1.05%   |
| Iiyama                  | 12        | 1.05%   |
| Gigabyte Technology     | 9         | 0.79%   |
| Vizio                   | 8         | 0.7%    |
| TMX                     | 6         | 0.52%   |
| LG Electronics          | 6         | 0.52%   |
| Sony                    | 5         | 0.44%   |
| CSO                     | 5         | 0.44%   |
| Chi Mei Optoelectronics | 5         | 0.44%   |
| Pixio                   | 4         | 0.35%   |
| Valve                   | 3         | 0.26%   |
| Toshiba                 | 3         | 0.26%   |
| RTK                     | 3         | 0.26%   |
| Panasonic               | 3         | 0.26%   |
| MSI                     | 3         | 0.26%   |
| LG Philips              | 3         | 0.26%   |
| JDI                     | 3         | 0.26%   |
| Fujitsu Siemens         | 3         | 0.26%   |
| Eizo                    | 3         | 0.26%   |
| Unknown (XXX)           | 2         | 0.17%   |
| Unknown                 | 2         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 9         | 0.76%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 7         | 0.59%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 7         | 0.59%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.51%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 6         | 0.51%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.51%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 5         | 0.42%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5         | 0.42%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 5         | 0.42%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 5         | 0.42%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 5         | 0.42%   |
| Lenovo P24q-10 LEN61A5 2560x1440 530x300mm 24.0-inch                  | 5         | 0.42%   |
| AOC 27P2DG5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 5         | 0.42%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 4         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 4         | 0.34%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4         | 0.34%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.34%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 0.34%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.34%   |
| Valve Index HMD VLV91A8                                               | 3         | 0.25%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 3         | 0.25%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 3         | 0.25%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.25%   |
| Pixio U29I WAM2900 2560x1080 690x260mm 29.0-inch                      | 3         | 0.25%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 3         | 0.25%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch          | 3         | 0.25%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.25%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.25%   |
| InfoVision LCD Monitor IVO8544 1920x1080 294x165mm 13.3-inch          | 3         | 0.25%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                  | 3         | 0.25%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 3         | 0.25%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 3         | 0.25%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 600x330mm 27.0-inch        | 3         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 532       | 49.26%  |
| 1366x768 (WXGA)    | 136       | 12.59%  |
| 2560x1440 (QHD)    | 99        | 9.17%   |
| 3840x2160 (4K)     | 78        | 7.22%   |
| 1920x1200 (WUXGA)  | 24        | 2.22%   |
| 2560x1600          | 23        | 2.13%   |
| 1440x900 (WXGA+)   | 23        | 2.13%   |
| 2560x1080          | 17        | 1.57%   |
| 1600x900 (HD+)     | 17        | 1.57%   |
| 1280x1024 (SXGA)   | 15        | 1.39%   |
| 1680x1050 (WSXGA+) | 13        | 1.2%    |
| 2880x1800          | 12        | 1.11%   |
| Unknown            | 12        | 1.11%   |
| 3440x1440          | 9         | 0.83%   |
| 1280x800 (WXGA)    | 8         | 0.74%   |
| 2160x1440          | 7         | 0.65%   |
| 3840x2400          | 5         | 0.46%   |
| 2736x1824          | 5         | 0.46%   |
| 1360x768           | 5         | 0.46%   |
| 3840x1080          | 4         | 0.37%   |
| 3200x2000          | 4         | 0.37%   |
| 3840x1600          | 2         | 0.19%   |
| 3456x2160          | 2         | 0.19%   |
| 3200x1800 (QHD+)   | 2         | 0.19%   |
| 3000x2000          | 2         | 0.19%   |
| 1920x540           | 2         | 0.19%   |
| 1800x1200          | 2         | 0.19%   |
| 1024x768 (XGA)     | 2         | 0.19%   |
| 9840x3840          | 1         | 0.09%   |
| 5760x1080          | 1         | 0.09%   |
| 4480x1440          | 1         | 0.09%   |
| 3840x2560          | 1         | 0.09%   |
| 3840x1440          | 1         | 0.09%   |
| 3840x1200          | 1         | 0.09%   |
| 3840x1100          | 1         | 0.09%   |
| 3520x1080          | 1         | 0.09%   |
| 3240x2160          | 1         | 0.09%   |
| 3200x1080          | 1         | 0.09%   |
| 3072x1920          | 1         | 0.09%   |
| 2880x1920          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 267       | 23.3%   |
| 13      | 127       | 11.08%  |
| 27      | 116       | 10.12%  |
| 24      | 112       | 9.77%   |
| 14      | 98        | 8.55%   |
| 23      | 57        | 4.97%   |
| 21      | 52        | 4.54%   |
| 17      | 44        | 3.84%   |
| 31      | 34        | 2.97%   |
| Unknown | 33        | 2.88%   |
| 34      | 24        | 2.09%   |
| 16      | 20        | 1.75%   |
| 12      | 20        | 1.75%   |
| 19      | 15        | 1.31%   |
| 18      | 14        | 1.22%   |
| 22      | 12        | 1.05%   |
| 11      | 11        | 0.96%   |
| 54      | 10        | 0.87%   |
| 20      | 10        | 0.87%   |
| 32      | 7         | 0.61%   |
| 84      | 5         | 0.44%   |
| 40      | 5         | 0.44%   |
| 10      | 5         | 0.44%   |
| 28      | 4         | 0.35%   |
| 72      | 3         | 0.26%   |
| 49      | 3         | 0.26%   |
| 46      | 3         | 0.26%   |
| 42      | 3         | 0.26%   |
| 29      | 3         | 0.26%   |
| 26      | 3         | 0.26%   |
| 25      | 3         | 0.26%   |
| 74      | 2         | 0.17%   |
| 69      | 2         | 0.17%   |
| 65      | 2         | 0.17%   |
| 58      | 2         | 0.17%   |
| 52      | 2         | 0.17%   |
| 37      | 2         | 0.17%   |
| 36      | 2         | 0.17%   |
| 35      | 2         | 0.17%   |
| 60      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 441       | 39.95%  |
| 501-600     | 253       | 22.92%  |
| 201-300     | 104       | 9.42%   |
| 401-500     | 93        | 8.42%   |
| 351-400     | 51        | 4.62%   |
| 601-700     | 45        | 4.08%   |
| 701-800     | 34        | 3.08%   |
| Unknown     | 33        | 2.99%   |
| 1001-1500   | 25        | 2.26%   |
| 1501-2000   | 12        | 1.09%   |
| 801-900     | 9         | 0.82%   |
| 901-1000    | 3         | 0.27%   |
| 101-200     | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 765       | 77.66%  |
| 16/10   | 116       | 11.78%  |
| Unknown | 29        | 2.94%   |
| 21/9    | 26        | 2.64%   |
| 3/2     | 22        | 2.23%   |
| 5/4     | 11        | 1.12%   |
| 4/3     | 6         | 0.61%   |
| 32/9    | 3         | 0.3%    |
| 2.65    | 3         | 0.3%    |
| 6/5     | 2         | 0.2%    |
| 3.40    | 1         | 0.1%    |
| 0.62    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 266       | 23.64%  |
| 201-250        | 175       | 15.56%  |
| 81-90          | 171       | 15.2%   |
| 301-350        | 119       | 10.58%  |
| 351-500        | 67        | 5.96%   |
| 71-80          | 58        | 5.16%   |
| 251-300        | 39        | 3.47%   |
| 151-200        | 35        | 3.11%   |
| 121-130        | 34        | 3.02%   |
| Unknown        | 33        | 2.93%   |
| More than 1000 | 31        | 2.76%   |
| 501-1000       | 20        | 1.78%   |
| 141-150        | 19        | 1.69%   |
| 111-120        | 19        | 1.69%   |
| 61-70          | 13        | 1.16%   |
| 51-60          | 12        | 1.07%   |
| 131-140        | 6         | 0.53%   |
| 41-50          | 5         | 0.44%   |
| 91-100         | 2         | 0.18%   |
| 1-40           | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 349       | 32.43%  |
| 51-100        | 300       | 27.88%  |
| 101-120       | 226       | 21%     |
| 161-240       | 102       | 9.48%   |
| More than 240 | 39        | 3.62%   |
| Unknown       | 33        | 3.07%   |
| 1-50          | 27        | 2.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 730       | 76.12%  |
| 2     | 195       | 20.33%  |
| 3     | 29        | 3.02%   |
| 0     | 3         | 0.31%   |
| 4     | 2         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 554       | 38.42%  |
| Intel                             | 531       | 36.82%  |
| Qualcomm Atheros                  | 108       | 7.49%   |
| Broadcom                          | 46        | 3.19%   |
| MediaTek                          | 45        | 3.12%   |
| ASIX Electronics                  | 18        | 1.25%   |
| TP-Link                           | 14        | 0.97%   |
| Microsoft                         | 12        | 0.83%   |
| Broadcom Limited                  | 12        | 0.83%   |
| D-Link                            | 9         | 0.62%   |
| Sierra Wireless                   | 6         | 0.42%   |
| Ralink                            | 6         | 0.42%   |
| Lenovo                            | 6         | 0.42%   |
| DisplayLink                       | 6         | 0.42%   |
| Ralink Technology                 | 5         | 0.35%   |
| Marvell Technology Group          | 5         | 0.35%   |
| Samsung Electronics               | 4         | 0.28%   |
| Hewlett-Packard                   | 4         | 0.28%   |
| Google                            | 4         | 0.28%   |
| Cypress Semiconductor             | 4         | 0.28%   |
| Aquantia                          | 4         | 0.28%   |
| Nvidia                            | 3         | 0.21%   |
| Huawei Technologies               | 3         | 0.21%   |
| Apple                             | 3         | 0.21%   |
| Xiaomi                            | 2         | 0.14%   |
| Qualcomm                          | 2         | 0.14%   |
| OPPO Electronics                  | 2         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.14%   |
| NetGear                           | 2         | 0.14%   |
| Microchip Technology              | 2         | 0.14%   |
| Ericsson Business Mobile Networks | 2         | 0.14%   |
| Dell                              | 2         | 0.14%   |
| ZyXEL Communications              | 1         | 0.07%   |
| Wilocity                          | 1         | 0.07%   |
| Qualcomm Atheros Communications   | 1         | 0.07%   |
| Motorola PCS                      | 1         | 0.07%   |
| Linksys                           | 1         | 0.07%   |
| InterBiometrics                   | 1         | 0.07%   |
| ICS Advent                        | 1         | 0.07%   |
| Fibocom                           | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 378       | 22.12%  |
| Intel Wi-Fi 6 AX200                                               | 87        | 5.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 50        | 2.93%   |
| Intel Wireless 8265 / 8275                                        | 40        | 2.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 2.05%   |
| Intel I211 Gigabit Network Connection                             | 33        | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 32        | 1.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 30        | 1.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 29        | 1.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 27        | 1.58%   |
| Intel Wireless 7265                                               | 27        | 1.58%   |
| Intel Wi-Fi 6 AX201                                               | 25        | 1.46%   |
| Intel Wireless 7260                                               | 22        | 1.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 1.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 19        | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 1.11%   |
| Intel Wireless 3165                                               | 18        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 1.05%   |
| Intel Wireless-AC 9260                                            | 17        | 0.99%   |
| Intel Wireless 8260                                               | 17        | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 17        | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 16        | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 0.94%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 15        | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 15        | 0.88%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 0.82%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 13        | 0.76%   |
| Realtek 802.11ac NIC                                              | 12        | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 0.7%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 12        | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 0.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 11        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 454       | 53.92%  |
| Realtek Semiconductor                 | 141       | 16.75%  |
| Qualcomm Atheros                      | 89        | 10.57%  |
| MediaTek                              | 44        | 5.23%   |
| Broadcom                              | 37        | 4.39%   |
| TP-Link                               | 11        | 1.31%   |
| Microsoft                             | 11        | 1.31%   |
| Broadcom Limited                      | 11        | 1.31%   |
| D-Link                                | 9         | 1.07%   |
| Sierra Wireless                       | 6         | 0.71%   |
| Ralink                                | 6         | 0.71%   |
| Ralink Technology                     | 5         | 0.59%   |
| Marvell Technology Group              | 4         | 0.48%   |
| Qualcomm                              | 2         | 0.24%   |
| ZyXEL Communications                  | 1         | 0.12%   |
| Wilocity                              | 1         | 0.12%   |
| Qualcomm Atheros Communications       | 1         | 0.12%   |
| NetGear                               | 1         | 0.12%   |
| Linksys                               | 1         | 0.12%   |
| Fibocom                               | 1         | 0.12%   |
| Edimax Technology                     | 1         | 0.12%   |
| Dell                                  | 1         | 0.12%   |
| D-Link System                         | 1         | 0.12%   |
| Belkin Components                     | 1         | 0.12%   |
| AVM                                   | 1         | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 87        | 10.2%   |
| Intel Wireless 8265 / 8275                                    | 40        | 4.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 32        | 3.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 30        | 3.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 29        | 3.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 27        | 3.17%   |
| Intel Wireless 7265                                           | 27        | 3.17%   |
| Intel Wi-Fi 6 AX201                                           | 25        | 2.93%   |
| Intel Wireless 7260                                           | 22        | 2.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 19        | 2.23%   |
| Intel Wireless 3165                                           | 18        | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 18        | 2.11%   |
| Intel Wireless-AC 9260                                        | 17        | 1.99%   |
| Intel Wireless 8260                                           | 17        | 1.99%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 17        | 1.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 16        | 1.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 15        | 1.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 15        | 1.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 13        | 1.52%   |
| Realtek 802.11ac NIC                                          | 12        | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 12        | 1.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 12        | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 12        | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                | 12        | 1.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 11        | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 10        | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 10        | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                 | 9         | 1.06%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 8         | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 8         | 0.94%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 8         | 0.94%   |
| Intel Wireless 3160                                           | 8         | 0.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 8         | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 8         | 0.94%   |
| D-Link 802.11ac NIC                                           | 8         | 0.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 8         | 0.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 6         | 0.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 6         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 6         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 6         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 492       | 59.93%  |
| Intel                         | 217       | 26.43%  |
| Qualcomm Atheros              | 31        | 3.78%   |
| ASIX Electronics              | 18        | 2.19%   |
| Broadcom                      | 15        | 1.83%   |
| DisplayLink                   | 6         | 0.73%   |
| Lenovo                        | 5         | 0.61%   |
| Google                        | 4         | 0.49%   |
| Cypress Semiconductor         | 4         | 0.49%   |
| Aquantia                      | 4         | 0.49%   |
| TP-Link                       | 3         | 0.37%   |
| Nvidia                        | 3         | 0.37%   |
| Apple                         | 3         | 0.37%   |
| Xiaomi                        | 2         | 0.24%   |
| Samsung Electronics           | 2         | 0.24%   |
| OPPO Electronics              | 2         | 0.24%   |
| OnePlus Technology (Shenzhen) | 1         | 0.12%   |
| NetGear                       | 1         | 0.12%   |
| Motorola PCS                  | 1         | 0.12%   |
| Microsoft                     | 1         | 0.12%   |
| MediaTek                      | 1         | 0.12%   |
| Marvell Technology Group      | 1         | 0.12%   |
| ICS Advent                    | 1         | 0.12%   |
| Hewlett-Packard               | 1         | 0.12%   |
| D-Link                        | 1         | 0.12%   |
| Broadcom Limited              | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 378       | 45.11%  |
| Realtek RTL8125 2.5GbE Controller                                 | 50        | 5.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 4.18%   |
| Intel I211 Gigabit Network Connection                             | 33        | 3.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 3.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 2.63%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 2.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 1.91%   |
| Intel Ethernet Controller I225-V                                  | 15        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 1.43%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 1.31%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.07%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.6%    |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.48%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.48%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.48%   |
| Cypress K38231_03                                                 | 4         | 0.48%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 3         | 0.36%   |
| Realtek PCIe GbE Family Controller                                | 3         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.36%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.36%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.36%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.36%   |
| Intel Ethernet Connection (16) I219-V                             | 3         | 0.36%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.36%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.36%   |
| Apple iBridge                                                     | 3         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 788       | 50.42%  |
| Ethernet | 757       | 48.43%  |
| Modem    | 16        | 1.02%   |
| Unknown  | 2         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 636       | 63.54%  |
| Ethernet | 365       | 36.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 512       | 54.18%  |
| 1     | 397       | 42.01%  |
| 3     | 27        | 2.86%   |
| 0     | 5         | 0.53%   |
| 4     | 4         | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 746       | 77.79%  |
| Yes  | 213       | 22.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 408       | 53.06%  |
| Realtek Semiconductor           | 91        | 11.83%  |
| Qualcomm Atheros Communications | 40        | 5.2%    |
| Cambridge Silicon Radio         | 37        | 4.81%   |
| IMC Networks                    | 29        | 3.77%   |
| Broadcom                        | 29        | 3.77%   |
| Lite-On Technology              | 24        | 3.12%   |
| Foxconn / Hon Hai               | 23        | 2.99%   |
| Apple                           | 18        | 2.34%   |
| ASUSTek Computer                | 17        | 2.21%   |
| MediaTek                        | 12        | 1.56%   |
| Realtek                         | 9         | 1.17%   |
| TP-Link                         | 6         | 0.78%   |
| Dell                            | 5         | 0.65%   |
| Toshiba                         | 4         | 0.52%   |
| Ralink                          | 3         | 0.39%   |
| Marvell Semiconductor           | 3         | 0.39%   |
| USI                             | 2         | 0.26%   |
| Opticis                         | 2         | 0.26%   |
| HTC (High Tech Computer)        | 2         | 0.26%   |
| Hewlett-Packard                 | 2         | 0.26%   |
| Foxconn International           | 1         | 0.13%   |
| Dynex                           | 1         | 0.13%   |
| Alps Electric                   | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 142       | 18.42%  |
| Intel AX200 Bluetooth                               | 84        | 10.89%  |
| Intel AX201 Bluetooth                               | 68        | 8.82%   |
| Realtek Bluetooth Radio                             | 66        | 8.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 42        | 5.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 37        | 4.8%    |
| Intel AX210 Bluetooth                               | 30        | 3.89%   |
| Qualcomm Atheros  Bluetooth Device                  | 26        | 3.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 17        | 2.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 1.95%   |
| MediaTek Wireless_Device                            | 12        | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 1.56%   |
| Intel Bluetooth Device                              | 12        | 1.56%   |
| IMC Networks Wireless_Device                        | 11        | 1.43%   |
| IMC Networks Bluetooth Radio                        | 11        | 1.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 1.3%    |
| Apple Bluetooth USB Host Controller                 | 10        | 1.3%    |
| Realtek Bluetooth Radio                             | 9         | 1.17%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 1.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 8         | 1.04%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 0.91%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 7         | 0.91%   |
| TP-Link UB500 Adapter                               | 6         | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 0.65%   |
| Lite-On Bluetooth Device                            | 5         | 0.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 0.65%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.52%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 0.52%   |
| Apple Bluetooth Host Controller                     | 4         | 0.52%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.39%   |
| Ralink RT3290 Bluetooth                             | 3         | 0.39%   |
| Marvell Bluetooth and Wireless LAN Composite        | 3         | 0.39%   |
| Lite-On Bluetooth Radio                             | 3         | 0.39%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.39%   |
| IMC Networks Bluetooth Device                       | 3         | 0.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.39%   |
| ASUS ASUS USB-BT500                                 | 3         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 594       | 39.03%  |
| AMD                                             | 372       | 24.44%  |
| Nvidia                                          | 269       | 17.67%  |
| C-Media Electronics                             | 33        | 2.17%   |
| Logitech                                        | 21        | 1.38%   |
| Texas Instruments                               | 17        | 1.12%   |
| SteelSeries ApS                                 | 17        | 1.12%   |
| Kingston Technology                             | 15        | 0.99%   |
| JMTek                                           | 10        | 0.66%   |
| Creative Labs                                   | 10        | 0.66%   |
| Creative Technology                             | 9         | 0.59%   |
| Sony                                            | 8         | 0.53%   |
| Razer USA                                       | 7         | 0.46%   |
| Lenovo                                          | 7         | 0.46%   |
| Corsair                                         | 7         | 0.46%   |
| Blue Microphones                                | 7         | 0.46%   |
| RODE Microphones                                | 6         | 0.39%   |
| Realtek Semiconductor                           | 6         | 0.39%   |
| KORG                                            | 6         | 0.39%   |
| Focusrite-Novation                              | 6         | 0.39%   |
| NAD Electronics                                 | 5         | 0.33%   |
| Micro Star International                        | 5         | 0.33%   |
| Generalplus Technology                          | 5         | 0.33%   |
| AKAI                                            | 5         | 0.33%   |
| XMOS                                            | 4         | 0.26%   |
| Valve Software                                  | 4         | 0.26%   |
| Samson Technologies                             | 4         | 0.26%   |
| KTMicro                                         | 3         | 0.2%    |
| GYROCOM C&C                                     | 3         | 0.2%    |
| Apple                                           | 3         | 0.2%    |
| Thesycon Systemsoftware & Consulting            | 2         | 0.13%   |
| M-Audio                                         | 2         | 0.13%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.13%   |
| Hewlett-Packard                                 | 2         | 0.13%   |
| Guangzhou FiiO Electronics                      | 2         | 0.13%   |
| Giga-Byte Technology                            | 2         | 0.13%   |
| Elgato Systems                                  | 2         | 0.13%   |
| Cambridge Silicon Radio                         | 2         | 0.13%   |
| BEHRINGER International                         | 2         | 0.13%   |
| AKAI Professional M.I.                          | 2         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 182       | 9.75%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 111       | 5.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 103       | 5.52%   |
| AMD Starship/Matisse HD Audio Controller                                   | 86        | 4.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 47        | 2.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 41        | 2.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 38        | 2.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 36        | 1.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 35        | 1.88%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 35        | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 34        | 1.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 32        | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 30        | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 28        | 1.5%    |
| Nvidia GA104 High Definition Audio Controller                              | 25        | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                              | 24        | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 24        | 1.29%   |
| Intel 8 Series HD Audio Controller                                         | 24        | 1.29%   |
| Nvidia GP104 High Definition Audio Controller                              | 22        | 1.18%   |
| Intel Broadwell-U Audio Controller                                         | 22        | 1.18%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22        | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 21        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 1.13%   |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 1.07%   |
| Nvidia TU116 High Definition Audio Controller                              | 18        | 0.96%   |
| Nvidia GA106 High Definition Audio Controller                              | 18        | 0.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 18        | 0.96%   |
| Intel 200 Series PCH HD Audio                                              | 18        | 0.96%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 18        | 0.96%   |
| AMD Navi 10 HDMI Audio                                                     | 18        | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 17        | 0.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 17        | 0.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 15        | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 15        | 0.8%    |
| Nvidia GP106 High Definition Audio Controller                              | 14        | 0.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 14        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 0.7%    |
| Intel CM238 HD Audio Controller                                            | 13        | 0.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 0.7%    |
| AMD FCH Azalia Controller                                                  | 13        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 218       | 26.11%  |
| SK hynix            | 154       | 18.44%  |
| Micron Technology   | 91        | 10.9%   |
| Kingston            | 68        | 8.14%   |
| Corsair             | 58        | 6.95%   |
| G.Skill             | 57        | 6.83%   |
| Crucial             | 51        | 6.11%   |
| Unknown             | 31        | 3.71%   |
| A-DATA Technology   | 13        | 1.56%   |
| Ramaxel Technology  | 12        | 1.44%   |
| Team                | 11        | 1.32%   |
| Patriot             | 11        | 1.32%   |
| Elpida              | 7         | 0.84%   |
| Unknown             | 7         | 0.84%   |
| Unknown (ABCD)      | 6         | 0.72%   |
| Nanya Technology    | 4         | 0.48%   |
| Kllisre             | 3         | 0.36%   |
| GOODRAM             | 3         | 0.36%   |
| Teikon              | 2         | 0.24%   |
| Shenzhen Mic        | 2         | 0.24%   |
| Hikvision           | 2         | 0.24%   |
| Golden Empire       | 2         | 0.24%   |
| Apacer              | 2         | 0.24%   |
| Wilk                | 1         | 0.12%   |
| V-GeN               | 1         | 0.12%   |
| Unknown (0x5846)    | 1         | 0.12%   |
| Transcend           | 1         | 0.12%   |
| Toshiba             | 1         | 0.12%   |
| Strontium           | 1         | 0.12%   |
| Smart Brazil        | 1         | 0.12%   |
| Smart               | 1         | 0.12%   |
| Sesame              | 1         | 0.12%   |
| Qimonda             | 1         | 0.12%   |
| PNY                 | 1         | 0.12%   |
| Neo Forza           | 1         | 0.12%   |
| Magnum Tech         | 1         | 0.12%   |
| KLEVV               | 1         | 0.12%   |
| Kingmax             | 1         | 0.12%   |
| Juhor               | 1         | 0.12%   |
| GeIL                | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 18        | 1.99%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 1.33%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 11        | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.99%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 8         | 0.88%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.77%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.77%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.77%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.77%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 0.77%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.77%   |
| Unknown                                                          | 7         | 0.77%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 0.66%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.66%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 6         | 0.66%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 6         | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.55%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.55%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 5         | 0.55%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.55%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.44%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.44%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.44%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.44%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 4         | 0.44%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 4         | 0.44%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 4         | 0.44%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 4         | 0.44%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 3         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 449       | 62.02%  |
| DDR3    | 158       | 21.82%  |
| LPDDR4  | 36        | 4.97%   |
| LPDDR3  | 27        | 3.73%   |
| DDR5    | 14        | 1.93%   |
| DDR2    | 13        | 1.8%    |
| SDRAM   | 10        | 1.38%   |
| LPDDR5  | 9         | 1.24%   |
| Unknown | 7         | 0.97%   |
| DDR     | 1         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 422       | 58.53%  |
| DIMM         | 210       | 29.13%  |
| Row Of Chips | 78        | 10.82%  |
| Chip         | 7         | 0.97%   |
| Unknown      | 2         | 0.28%   |
| RIMM         | 1         | 0.14%   |
| FB-DIMM      | 1         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 385       | 49.49%  |
| 4096  | 184       | 23.65%  |
| 16384 | 126       | 16.2%   |
| 2048  | 48        | 6.17%   |
| 32768 | 30        | 3.86%   |
| 1024  | 5         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 195       | 25%     |
| 1600    | 126       | 16.15%  |
| 2667    | 122       | 15.64%  |
| 3600    | 44        | 5.64%   |
| 2400    | 44        | 5.64%   |
| 2133    | 36        | 4.62%   |
| 3266    | 23        | 2.95%   |
| 1333    | 23        | 2.95%   |
| 1867    | 21        | 2.69%   |
| 4267    | 13        | 1.67%   |
| 4800    | 12        | 1.54%   |
| 6400    | 10        | 1.28%   |
| 1334    | 8         | 1.03%   |
| 3733    | 7         | 0.9%    |
| 3533    | 7         | 0.9%    |
| 3866    | 6         | 0.77%   |
| 800     | 6         | 0.77%   |
| 667     | 6         | 0.77%   |
| 3400    | 5         | 0.64%   |
| 3000    | 5         | 0.64%   |
| 1800    | 5         | 0.64%   |
| Unknown | 5         | 0.64%   |
| 3800    | 4         | 0.51%   |
| 4266    | 3         | 0.38%   |
| 2048    | 3         | 0.38%   |
| 1067    | 3         | 0.38%   |
| 6000    | 2         | 0.26%   |
| 4199    | 2         | 0.26%   |
| 3534    | 2         | 0.26%   |
| 3500    | 2         | 0.26%   |
| 3466    | 2         | 0.26%   |
| 2933    | 2         | 0.26%   |
| 2733    | 2         | 0.26%   |
| 2666    | 2         | 0.26%   |
| 1648    | 2         | 0.26%   |
| 1066    | 2         | 0.26%   |
| 65535   | 1         | 0.13%   |
| 49926   | 1         | 0.13%   |
| 5800    | 1         | 0.13%   |
| 4333    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 5         | 33.33%  |
| Hewlett-Packard     | 4         | 26.67%  |
| Prolific Technology | 2         | 13.33%  |
| Xerox               | 1         | 6.67%   |
| Seiko Epson         | 1         | 6.67%   |
| Pantum              | 1         | 6.67%   |
| Canon               | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 2         | 13.33%  |
| Xerox B210                    | 1         | 6.67%   |
| Seiko Epson WF-2010 Series    | 1         | 6.67%   |
| Pantum P2500W series          | 1         | 6.67%   |
| HP OfficeJet Pro 8020 series  | 1         | 6.67%   |
| HP ENVY 5540 series           | 1         | 6.67%   |
| HP DeskJet 2130 series        | 1         | 6.67%   |
| HP ColorLaserJet M253-M254    | 1         | 6.67%   |
| Canon PIXMA MG2500 Series     | 1         | 6.67%   |
| Brother Printer               | 1         | 6.67%   |
| Brother MFC-L2710DW series    | 1         | 6.67%   |
| Brother MFC-J4535DW           | 1         | 6.67%   |
| Brother HL-2130 series        | 1         | 6.67%   |
| Brother DCP-9015CDW           | 1         | 6.67%   |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 129       | 19.31%  |
| IMC Networks                           | 91        | 13.62%  |
| Logitech                               | 59        | 8.83%   |
| Microdia                               | 41        | 6.14%   |
| Realtek Semiconductor                  | 31        | 4.64%   |
| Quanta                                 | 31        | 4.64%   |
| Bison Electronics                      | 31        | 4.64%   |
| Acer                                   | 30        | 4.49%   |
| Sunplus Innovation Technology          | 28        | 4.19%   |
| Cheng Uei Precision Industry (Foxlink) | 28        | 4.19%   |
| Apple                                  | 24        | 3.59%   |
| Syntek                                 | 23        | 3.44%   |
| Lite-On Technology                     | 21        | 3.14%   |
| Luxvisions Innotech Limited            | 12        | 1.8%    |
| Microsoft                              | 7         | 1.05%   |
| Suyin                                  | 5         | 0.75%   |
| Sonix Technology                       | 5         | 0.75%   |
| Samsung Electronics                    | 5         | 0.75%   |
| Valve Software                         | 4         | 0.6%    |
| Silicon Motion                         | 4         | 0.6%    |
| MacroSilicon                           | 4         | 0.6%    |
| Lenovo                                 | 4         | 0.6%    |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.45%   |
| Primax Electronics                     | 3         | 0.45%   |
| Hewlett-Packard                        | 3         | 0.45%   |
| Google                                 | 3         | 0.45%   |
| GEMBIRD                                | 3         | 0.45%   |
| Alcor Micro                            | 3         | 0.45%   |
| Sunplus IT                             | 2         | 0.3%    |
| Ricoh                                  | 2         | 0.3%    |
| Intel                                  | 2         | 0.3%    |
| Huawei Technologies                    | 2         | 0.3%    |
| Y Media                                | 1         | 0.15%   |
| Xiaomi                                 | 1         | 0.15%   |
| WCM_USB                                | 1         | 0.15%   |
| Trust                                  | 1         | 0.15%   |
| Tripath Technology                     | 1         | 0.15%   |
| Tobii Technology AB                    | 1         | 0.15%   |
| Sony                                   | 1         | 0.15%   |
| SN0002                                 | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 38        | 5.66%   |
| IMC Networks Integrated Camera                   | 35        | 5.22%   |
| IMC Networks USB2.0 HD UVC WebCam                | 33        | 4.92%   |
| Chicony HD WebCam                                | 17        | 2.53%   |
| Logitech HD Pro Webcam C920                      | 16        | 2.38%   |
| Bison Integrated Camera                          | 15        | 2.24%   |
| Syntek Integrated Camera                         | 14        | 2.09%   |
| Microdia Integrated_Webcam_HD                    | 13        | 1.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 12        | 1.79%   |
| Realtek Integrated_Webcam_HD                     | 11        | 1.64%   |
| Logitech Webcam C270                             | 11        | 1.64%   |
| Acer HD Webcam                                   | 10        | 1.49%   |
| Sunplus Integrated_Webcam_HD                     | 8         | 1.19%   |
| Apple FaceTime HD Camera (Built-in)              | 8         | 1.19%   |
| Logitech C922 Pro Stream Webcam                  | 7         | 1.04%   |
| Lite-On Integrated Camera                        | 7         | 1.04%   |
| Chicony HP Wide Vision HD Camera                 | 7         | 1.04%   |
| Acer Integrated Camera                           | 7         | 1.04%   |
| Quanta USB2.0 HD UVC WebCam                      | 6         | 0.89%   |
| Microdia Webcam Vitade AF                        | 6         | 0.89%   |
| Microdia Integrated Webcam                       | 6         | 0.89%   |
| Chicony USB2.0 HD UVC WebCam                     | 6         | 0.89%   |
| Chicony HD User Facing                           | 6         | 0.89%   |
| Sunplus HD WebCam                                | 5         | 0.75%   |
| Samsung Galaxy series, misc. (MTP mode)          | 5         | 0.75%   |
| Quanta HP TrueVision HD Camera                   | 5         | 0.75%   |
| Quanta HP HD Camera                              | 5         | 0.75%   |
| IMC Networks ov9734_azurewave_camera             | 5         | 0.75%   |
| Chicony VGA WebCam                               | 5         | 0.75%   |
| Chicony HP TrueVision HD Camera                  | 5         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 5         | 0.75%   |
| Valve Software 3D Camera                         | 4         | 0.6%    |
| Syntek Lenovo EasyCamera                         | 4         | 0.6%    |
| Syntek EasyCamera                                | 4         | 0.6%    |
| Sunplus Asus Webcam                              | 4         | 0.6%    |
| Sonix USB2.0 HD UVC WebCam                       | 4         | 0.6%    |
| Microdia USB 2.0 Camera                          | 4         | 0.6%    |
| MacroSilicon usb video                           | 4         | 0.6%    |
| Logitech HD Webcam C615                          | 4         | 0.6%    |
| Lite-On HP Webcam                                | 4         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 48        | 37.21%  |
| Validity Sensors                   | 31        | 24.03%  |
| Shenzhen Goodix Technology         | 22        | 17.05%  |
| Elan Microelectronics              | 14        | 10.85%  |
| LighTuning Technology              | 6         | 4.65%   |
| Upek                               | 3         | 2.33%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.33%   |
| Samsung Electronics                | 1         | 0.78%   |
| AuthenTec                          | 1         | 0.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 8.53%   |
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 8.53%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 8.53%   |
| Elan ELAN:Fingerprint                                                      | 9         | 6.98%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 6.2%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 6.2%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 4.65%   |
| Synaptics WBDI                                                             | 6         | 4.65%   |
| Synaptics  WBDI                                                            | 6         | 4.65%   |
| Synaptics UWP WBDI                                                         | 5         | 3.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.88%   |
| Elan ELAN:ARM-M4                                                           | 5         | 3.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.1%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 3.1%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 2.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 2.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.55%   |
| Validity Sensors VFS491                                                    | 2         | 1.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.55%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.55%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.55%   |
| Unknown                                                                    | 2         | 1.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.78%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.78%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.78%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.78%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.78%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.78%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.78%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.78%   |
| AuthenTec AES2810                                                          | 1         | 0.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 18        | 45%     |
| Alcor Micro | 14        | 35%     |
| Lenovo      | 3         | 7.5%    |
| Upek        | 2         | 5%      |
| O2 Micro    | 2         | 5%      |
| HID Global  | 1         | 2.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 31.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 26.83%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 7.32%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 7.32%   |
| Broadcom 58200                                                               | 3         | 7.32%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.88%   |
| Broadcom 5880                                                                | 2         | 4.88%   |
| HID Global USB Reader V3                                                     | 1         | 2.44%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 2.44%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 652       | 67.56%  |
| 1     | 257       | 26.63%  |
| 2     | 53        | 5.49%   |
| 3     | 2         | 0.21%   |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 129       | 36.65%  |
| Net/ethernet             | 43        | 12.22%  |
| Chipcard                 | 39        | 11.08%  |
| Multimedia controller    | 36        | 10.23%  |
| Graphics card            | 33        | 9.38%   |
| Net/wireless             | 28        | 7.95%   |
| Camera                   | 16        | 4.55%   |
| Bluetooth                | 10        | 2.84%   |
| Network                  | 7         | 1.99%   |
| Unassigned class         | 2         | 0.57%   |
| Storage                  | 2         | 0.57%   |
| Sound                    | 2         | 0.57%   |
| Dvb card                 | 2         | 0.57%   |
| Modem                    | 1         | 0.28%   |
| Communication controller | 1         | 0.28%   |
| Card reader              | 1         | 0.28%   |

