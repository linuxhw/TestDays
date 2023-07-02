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

Total: 1422

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [916b60f6f7](https://linux-hardware.org/?probe=916b60f6f7) | Jun 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f3cb4dc749](https://linux-hardware.org/?probe=f3cb4dc749) | Jun 29, 2023 |
| eMachines     | eME728                      | Notebook    | [37dc0ef617](https://linux-hardware.org/?probe=37dc0ef617) | Jun 29, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [89f1647ea1](https://linux-hardware.org/?probe=89f1647ea1) | Jun 29, 2023 |
| MSI           | A320M PRO-VH                | Desktop     | [1a84c61bd4](https://linux-hardware.org/?probe=1a84c61bd4) | Jun 27, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [c147d5716d](https://linux-hardware.org/?probe=c147d5716d) | Jun 27, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d0d602b518](https://linux-hardware.org/?probe=d0d602b518) | Jun 27, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [f664b455eb](https://linux-hardware.org/?probe=f664b455eb) | Jun 26, 2023 |
| Google        | Sasuke                      | Notebook    | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e0f5116d38](https://linux-hardware.org/?probe=e0f5116d38) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7ac67acfed](https://linux-hardware.org/?probe=7ac67acfed) | Jun 21, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [481ef14837](https://linux-hardware.org/?probe=481ef14837) | Jun 21, 2023 |
| MSI           | B450M PRO-VDH               | Desktop     | [ed8ee7af2c](https://linux-hardware.org/?probe=ed8ee7af2c) | Jun 19, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [78207fbf49](https://linux-hardware.org/?probe=78207fbf49) | Jun 19, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [90720c3820](https://linux-hardware.org/?probe=90720c3820) | Jun 18, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [4b184d1037](https://linux-hardware.org/?probe=4b184d1037) | Jun 18, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [2bcd63ec1e](https://linux-hardware.org/?probe=2bcd63ec1e) | Jun 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [bc3ba9b05e](https://linux-hardware.org/?probe=bc3ba9b05e) | Jun 15, 2023 |
| ZOTAC         | ZBOX-EN760                  | Mini pc     | [e36c953da7](https://linux-hardware.org/?probe=e36c953da7) | Jun 14, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [1050576987](https://linux-hardware.org/?probe=1050576987) | Jun 14, 2023 |
| Dell          | Latitude E5570              | Notebook    | [43171e0f19](https://linux-hardware.org/?probe=43171e0f19) | Jun 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e8ed28dba0](https://linux-hardware.org/?probe=e8ed28dba0) | Jun 14, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [3528d095e0](https://linux-hardware.org/?probe=3528d095e0) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2db1bbb316](https://linux-hardware.org/?probe=2db1bbb316) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [507d8cc765](https://linux-hardware.org/?probe=507d8cc765) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21a8144a2e](https://linux-hardware.org/?probe=21a8144a2e) | Jun 13, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [51a3b444dd](https://linux-hardware.org/?probe=51a3b444dd) | Jun 13, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c433d533f0](https://linux-hardware.org/?probe=c433d533f0) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3c7683dfc4](https://linux-hardware.org/?probe=3c7683dfc4) | Jun 11, 2023 |
| ASUSTek       | CM6850                      | Desktop     | [33579719ed](https://linux-hardware.org/?probe=33579719ed) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1d46e48d92](https://linux-hardware.org/?probe=1d46e48d92) | Jun 10, 2023 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/EndeavourOS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 818       | 84.16%  |
| EndeavourOS         | 154       | 15.84%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| EndeavourOS | 962       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 5.15.12-arch1-1  | 20        | 1.79%   |
| 6.2.8-arch1-1    | 19        | 1.7%    |
| 6.1.1-arch1-1    | 16        | 1.43%   |
| 6.3.1-arch1-1    | 13        | 1.16%   |
| 6.1.12-arch1-1   | 13        | 1.16%   |
| 6.2.2-arch1-1    | 11        | 0.98%   |
| 6.2.10-arch1-1   | 11        | 0.98%   |
| 6.0.9-arch1-1    | 11        | 0.98%   |
| 6.0.2-arch1-1    | 11        | 0.98%   |
| 5.17.1-arch1-1   | 11        | 0.98%   |
| 6.3.4-arch1-1    | 10        | 0.9%    |
| 6.2.13-arch1-1   | 10        | 0.9%    |
| 5.19.7-arch1-1   | 10        | 0.9%    |
| 5.17.5-arch1-1   | 10        | 0.9%    |
| 6.0.2-zen1-1-zen | 9         | 0.81%   |
| 6.0.12-arch1-1   | 9         | 0.81%   |
| 5.15.10-arch1-1  | 9         | 0.81%   |
| 6.2.9-arch1-1    | 8         | 0.72%   |
| 5.17.9-arch1-1   | 8         | 0.72%   |
| 5.15.7-arch1-1   | 8         | 0.72%   |
| 5.14.9-arch2-1   | 8         | 0.72%   |
| 5.13.13-arch1-1  | 8         | 0.72%   |
| 5.11.11-arch1-1  | 8         | 0.72%   |
| 6.1.11-arch1-1   | 7         | 0.63%   |
| 5.9.14-arch1-1   | 7         | 0.63%   |
| 5.19.12-arch1-1  | 7         | 0.63%   |
| 5.18.16-arch1-1  | 7         | 0.63%   |
| 5.18.12-arch1-1  | 7         | 0.63%   |
| 5.16.10-arch1-1  | 7         | 0.63%   |
| 6.3.9-arch1-1    | 6         | 0.54%   |
| 6.3.5-arch1-1    | 6         | 0.54%   |
| 6.2.12-arch1-1   | 6         | 0.54%   |
| 6.1.9-arch1-2    | 6         | 0.54%   |
| 6.1.8-arch1-1    | 6         | 0.54%   |
| 6.1.7-arch1-1    | 6         | 0.54%   |
| 6.1.4-arch1-1    | 6         | 0.54%   |
| 6.0.6-arch1-1    | 6         | 0.54%   |
| 5.9.1-arch1-1    | 6         | 0.54%   |
| 5.7.7-arch1-1    | 6         | 0.54%   |
| 5.19.11-arch1-1  | 6         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.12 | 28        | 2.51%   |
| 6.1.1   | 23        | 2.06%   |
| 6.3.1   | 22        | 1.97%   |
| 6.0.2   | 22        | 1.97%   |
| 6.2.8   | 21        | 1.88%   |
| 6.1.12  | 15        | 1.34%   |
| 6.0.9   | 15        | 1.34%   |
| 5.17.1  | 15        | 1.34%   |
| 6.3.4   | 14        | 1.25%   |
| 6.2.2   | 14        | 1.25%   |
| 5.17.5  | 14        | 1.25%   |
| 6.2.13  | 13        | 1.16%   |
| 6.2.10  | 13        | 1.16%   |
| 6.0.6   | 12        | 1.07%   |
| 6.0.12  | 12        | 1.07%   |
| 5.19.7  | 12        | 1.07%   |
| 5.13.13 | 12        | 1.07%   |
| 6.2.9   | 11        | 0.98%   |
| 5.18.12 | 11        | 0.98%   |
| 5.17.9  | 11        | 0.98%   |
| 6.3.5   | 10        | 0.9%    |
| 5.19.9  | 10        | 0.9%    |
| 5.14.9  | 10        | 0.9%    |
| 6.1.9   | 9         | 0.81%   |
| 5.19.13 | 9         | 0.81%   |
| 5.18.16 | 9         | 0.81%   |
| 5.15.7  | 9         | 0.81%   |
| 5.15.4  | 9         | 0.81%   |
| 5.15.10 | 9         | 0.81%   |
| 5.11.11 | 9         | 0.81%   |
| 6.1.8   | 8         | 0.72%   |
| 6.1.7   | 8         | 0.72%   |
| 6.1.4   | 8         | 0.72%   |
| 5.9.1   | 8         | 0.72%   |
| 5.19.12 | 8         | 0.72%   |
| 5.16.16 | 8         | 0.72%   |
| 5.15.2  | 8         | 0.72%   |
| 5.12.13 | 8         | 0.72%   |
| 5.11.16 | 8         | 0.72%   |
| 6.3.9   | 7         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 139       | 12.88%  |
| 6.1     | 114       | 10.57%  |
| 6.2     | 102       | 9.45%   |
| 6.0     | 83        | 7.69%   |
| 5.19    | 79        | 7.32%   |
| 6.3     | 73        | 6.77%   |
| 5.16    | 66        | 6.12%   |
| 5.17    | 64        | 5.93%   |
| 5.18    | 60        | 5.56%   |
| 5.14    | 52        | 4.82%   |
| 5.12    | 38        | 3.52%   |
| 5.10    | 38        | 3.52%   |
| 5.11    | 37        | 3.43%   |
| 5.9     | 35        | 3.24%   |
| 5.13    | 35        | 3.24%   |
| 5.8     | 24        | 2.22%   |
| 5.7     | 21        | 1.95%   |
| 5.4     | 7         | 0.65%   |
| 5.6     | 5         | 0.46%   |
| 5.5     | 2         | 0.19%   |
| 4.19    | 2         | 0.19%   |
| 5.2     | 1         | 0.09%   |
| 5.17.1  | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 961       | 99.9%   |
| aarch64 | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 363       | 36.23%  |
| GNOME           | 213       | 21.26%  |
| XFCE            | 198       | 19.76%  |
| X-Cinnamon      | 42        | 4.19%   |
| i3              | 41        | 4.09%   |
| KDE             | 25        | 2.5%    |
| Budgie          | 21        | 2.1%    |
| Unknown         | 20        | 2%      |
| Cinnamon        | 15        | 1.5%    |
| sway            | 12        | 1.2%    |
| MATE            | 9         | 0.9%    |
| LXQt            | 9         | 0.9%    |
| Deepin          | 5         | 0.5%    |
| bspwm           | 5         | 0.5%    |
| openbox         | 4         | 0.4%    |
| Hyprland        | 4         | 0.4%    |
| GNOME Flashback | 4         | 0.4%    |
| awesome         | 3         | 0.3%    |
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

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 737       | 74.97%  |
| Wayland | 193       | 19.63%  |
| Tty     | 37        | 3.76%   |
| Unknown | 15        | 1.53%   |
| Web     | 1         | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 324       | 32.73%  |
| SDDM    | 243       | 24.55%  |
| Unknown | 241       | 24.34%  |
| GDM     | 131       | 13.23%  |
| TDM     | 48        | 4.85%   |
| GREETD  | 2         | 0.2%    |
| LY-DM   | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 488       | 50.47%  |
| en_GB   | 70        | 7.24%   |
| it_IT   | 56        | 5.79%   |
| de_DE   | 53        | 5.48%   |
| en_CA   | 41        | 4.24%   |
| ru_RU   | 22        | 2.28%   |
| fr_FR   | 22        | 2.28%   |
| en_IN   | 21        | 2.17%   |
| en_AU   | 17        | 1.76%   |
| es_ES   | 13        | 1.34%   |
| pt_BR   | 12        | 1.24%   |
| pl_PL   | 12        | 1.24%   |
| Unknown | 12        | 1.24%   |
| nl_NL   | 10        | 1.03%   |
| fi_FI   | 8         | 0.83%   |
| de_AT   | 8         | 0.83%   |
| tr_TR   | 7         | 0.72%   |
| es_MX   | 7         | 0.72%   |
| es_AR   | 7         | 0.72%   |
| en_DK   | 7         | 0.72%   |
| en_NZ   | 6         | 0.62%   |
| en_AG   | 6         | 0.62%   |
| sv_SE   | 5         | 0.52%   |
| nl_BE   | 5         | 0.52%   |
| en_PH   | 5         | 0.52%   |
| pt_PT   | 4         | 0.41%   |
| de_CH   | 4         | 0.41%   |
| en_SG   | 3         | 0.31%   |
| en_HK   | 3         | 0.31%   |
| cs_CZ   | 3         | 0.31%   |
| zh_CN   | 2         | 0.21%   |
| ru_UA   | 2         | 0.21%   |
| hu_HU   | 2         | 0.21%   |
| en_ZA   | 2         | 0.21%   |
| C       | 2         | 0.21%   |
| sr_RS   | 1         | 0.1%    |
| sl_SI   | 1         | 0.1%    |
| sk_SK   | 1         | 0.1%    |
| ko_KR   | 1         | 0.1%    |
| id_ID   | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 634       | 65.09%  |
| BIOS | 340       | 34.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 675       | 69.73%  |
| Btrfs   | 245       | 25.31%  |
| Overlay | 24        | 2.48%   |
| Xfs     | 10        | 1.03%   |
| Tmpfs   | 7         | 0.72%   |
| F2fs    | 3         | 0.31%   |
| Unknown | 2         | 0.21%   |
| XXX4    | 1         | 0.1%    |
| Ext2    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 658       | 67.63%  |
| Unknown | 242       | 24.87%  |
| MBR     | 73        | 7.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 828       | 85.1%   |
| Yes       | 145       | 14.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 655       | 66.7%   |
| Yes       | 327       | 33.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 190       | 19.75%  |
| ASUSTek Computer                     | 178       | 18.5%   |
| Hewlett-Packard                      | 114       | 11.85%  |
| MSI                                  | 95        | 9.88%   |
| Dell                                 | 84        | 8.73%   |
| Gigabyte Technology                  | 68        | 7.07%   |
| Acer                                 | 42        | 4.37%   |
| ASRock                               | 30        | 3.12%   |
| Apple                                | 26        | 2.7%    |
| HUAWEI                               | 14        | 1.46%   |
| Timi                                 | 10        | 1.04%   |
| Google                               | 10        | 1.04%   |
| Samsung Electronics                  | 9         | 0.94%   |
| Microsoft                            | 9         | 0.94%   |
| Toshiba                              | 7         | 0.73%   |
| Unknown                              | 7         | 0.73%   |
| Notebook                             | 6         | 0.62%   |
| Sony                                 | 4         | 0.42%   |
| Intel                                | 4         | 0.42%   |
| ZOTAC                                | 3         | 0.31%   |
| TUXEDO                               | 3         | 0.31%   |
| Schenker                             | 3         | 0.31%   |
| Positivo                             | 3         | 0.31%   |
| AZW                                  | 3         | 0.31%   |
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
| VIT                                  | 1         | 0.1%    |
| UMAX                                 | 1         | 0.1%    |
| Shinelon Computer                    | 1         | 0.1%    |
| Shenzhen Meigao Electronic Equipment | 1         | 0.1%    |
| Radxa                                | 1         | 0.1%    |
| Pine Microsystems                    | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7C37                           | 11        | 1.14%   |
| ASUS All Series                       | 9         | 0.94%   |
| Unknown                               | 8         | 0.83%   |
| Apple MacBookAir7,2                   | 6         | 0.62%   |
| MSI MS-7C02                           | 5         | 0.52%   |
| MSI MS-7A38                           | 5         | 0.52%   |
| ASUS TUF Gaming X570-PLUS             | 5         | 0.52%   |
| ASUS ROG STRIX X570-E GAMING          | 5         | 0.52%   |
| Gigabyte B450 AORUS ELITE             | 4         | 0.42%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 4         | 0.42%   |
| ASRock B450M Pro4                     | 4         | 0.42%   |
| ASRock B450 Pro4                      | 4         | 0.42%   |
| MSI MS-7C91                           | 3         | 0.31%   |
| MSI MS-7C52                           | 3         | 0.31%   |
| MSI Modern 14 B5M                     | 3         | 0.31%   |
| Microsoft Surface Laptop Go           | 3         | 0.31%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.31%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 3         | 0.31%   |
| Lenovo Legion 5 15ACH6H 82JU          | 3         | 0.31%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5      | 3         | 0.31%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 3         | 0.31%   |
| HUAWEI KLVL-WXX9                      | 3         | 0.31%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 3         | 0.31%   |
| Gigabyte B550M AORUS PRO              | 3         | 0.31%   |
| Gigabyte B550 AORUS ELITE V2          | 3         | 0.31%   |
| Gigabyte B450M DS3H                   | 3         | 0.31%   |
| Apple MacBookPro16,2                  | 3         | 0.31%   |
| Acer Aspire E5-575G                   | 3         | 0.31%   |
| Timi TM1701                           | 2         | 0.21%   |
| Timi A35S                             | 2         | 0.21%   |
| Samsung 950QDB                        | 2         | 0.21%   |
| Samsung 340XAA/350XAA/550XAA          | 2         | 0.21%   |
| Positivo S14BW01                      | 2         | 0.21%   |
| MSI MS-7D25                           | 2         | 0.21%   |
| MSI MS-7C84                           | 2         | 0.21%   |
| MSI MS-7C56                           | 2         | 0.21%   |
| MSI MS-7B86                           | 2         | 0.21%   |
| MSI MS-7B85                           | 2         | 0.21%   |
| MSI MS-7A74                           | 2         | 0.21%   |
| MSI MS-7A34                           | 2         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 85        | 8.84%   |
| ASUS ROG           | 44        | 4.57%   |
| Lenovo IdeaPad     | 42        | 4.37%   |
| Acer Aspire        | 26        | 2.7%    |
| HP Pavilion        | 24        | 2.49%   |
| Dell Inspiron      | 24        | 2.49%   |
| Dell Latitude      | 22        | 2.29%   |
| ASUS TUF           | 22        | 2.29%   |
| Lenovo Yoga        | 16        | 1.66%   |
| HP EliteBook       | 16        | 1.66%   |
| ASUS PRIME         | 16        | 1.66%   |
| HP Laptop          | 15        | 1.56%   |
| ASUS VivoBook      | 13        | 1.35%   |
| MSI MS-7C37        | 11        | 1.14%   |
| Lenovo Legion      | 11        | 1.14%   |
| HP ENVY            | 11        | 1.14%   |
| Dell OptiPlex      | 11        | 1.14%   |
| Lenovo ThinkBook   | 10        | 1.04%   |
| Microsoft Surface  | 9         | 0.94%   |
| ASUS All           | 9         | 0.94%   |
| MSI Modern         | 8         | 0.83%   |
| Dell Precision     | 8         | 0.83%   |
| ASUS ASUS          | 8         | 0.83%   |
| Unknown            | 8         | 0.83%   |
| Gigabyte B450      | 7         | 0.73%   |
| Dell XPS           | 7         | 0.73%   |
| ASUS ZenBook       | 7         | 0.73%   |
| Toshiba Satellite  | 6         | 0.62%   |
| Gigabyte X570      | 6         | 0.62%   |
| Gigabyte B550      | 6         | 0.62%   |
| ASRock B450        | 6         | 0.62%   |
| Apple MacBookAir7  | 6         | 0.62%   |
| Acer Swift         | 6         | 0.62%   |
| MSI MS-7C02        | 5         | 0.52%   |
| MSI MS-7A38        | 5         | 0.52%   |
| Lenovo ThinkCentre | 5         | 0.52%   |
| HP 255             | 5         | 0.52%   |
| Gigabyte B450M     | 5         | 0.52%   |
| Lenovo IdeaPadFlex | 4         | 0.42%   |
| Lenovo IdeaCentre  | 4         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 137       | 14.24%  |
| 2021    | 134       | 13.93%  |
| 2019    | 127       | 13.2%   |
| 2018    | 119       | 12.37%  |
| 2022    | 67        | 6.96%   |
| 2017    | 65        | 6.76%   |
| 2013    | 55        | 5.72%   |
| 2016    | 50        | 5.2%    |
| 2015    | 48        | 4.99%   |
| 2012    | 46        | 4.78%   |
| 2014    | 40        | 4.16%   |
| 2011    | 26        | 2.7%    |
| 2010    | 14        | 1.46%   |
| 2009    | 12        | 1.25%   |
| 2008    | 12        | 1.25%   |
| 2007    | 7         | 0.73%   |
| 2023    | 2         | 0.21%   |
| Unknown | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 561       | 58.32%  |
| Desktop     | 319       | 33.16%  |
| Convertible | 45        | 4.68%   |
| All in one  | 15        | 1.56%   |
| Mini pc     | 11        | 1.14%   |
| Tablet      | 10        | 1.04%   |
| Server      | 1         | 0.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 958       | 99.58%  |
| Enabled  | 4         | 0.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 951       | 98.86%  |
| Yes  | 11        | 1.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 248       | 25.59%  |
| 8.01-16.0   | 214       | 22.08%  |
| 4.01-8.0    | 212       | 21.88%  |
| 32.01-64.0  | 152       | 15.69%  |
| 3.01-4.0    | 79        | 8.15%   |
| 24.01-32.0  | 33        | 3.41%   |
| 64.01-256.0 | 22        | 2.27%   |
| 1.01-2.0    | 6         | 0.62%   |
| 2.01-3.0    | 3         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 267       | 25.53%  |
| 4.01-8.0   | 242       | 23.14%  |
| 1.01-2.0   | 235       | 22.47%  |
| 3.01-4.0   | 186       | 17.78%  |
| 8.01-16.0  | 75        | 7.17%   |
| 0.51-1.0   | 26        | 2.49%   |
| 16.01-24.0 | 10        | 0.96%   |
| 24.01-32.0 | 3         | 0.29%   |
| 0.01-0.5   | 2         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 524       | 52.93%  |
| 2      | 263       | 26.57%  |
| 3      | 95        | 9.6%    |
| 4      | 61        | 6.16%   |
| 5      | 28        | 2.83%   |
| 6      | 9         | 0.91%   |
| 7      | 4         | 0.4%    |
| 0      | 3         | 0.3%    |
| 8      | 2         | 0.2%    |
| 9      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 777       | 80.35%  |
| Yes       | 190       | 19.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 776       | 80.33%  |
| No        | 190       | 19.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 809       | 83.75%  |
| No        | 157       | 16.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 761       | 78.37%  |
| No        | 210       | 21.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 212       | 21.9%   |
| Germany     | 86        | 8.88%   |
| Italy       | 84        | 8.68%   |
| Canada      | 45        | 4.65%   |
| France      | 39        | 4.03%   |
| Poland      | 30        | 3.1%    |
| Netherlands | 30        | 3.1%    |
| India       | 28        | 2.89%   |
| Russia      | 27        | 2.79%   |
| Brazil      | 25        | 2.58%   |
| UK          | 24        | 2.48%   |
| Spain       | 21        | 2.17%   |
| Finland     | 20        | 2.07%   |
| Australia   | 19        | 1.96%   |
| Turkey      | 18        | 1.86%   |
| Sweden      | 16        | 1.65%   |
| Belgium     | 16        | 1.65%   |
| Austria     | 16        | 1.65%   |
| Mexico      | 11        | 1.14%   |
| Indonesia   | 10        | 1.03%   |
| Argentina   | 9         | 0.93%   |
| Switzerland | 8         | 0.83%   |
| Romania     | 8         | 0.83%   |
| Hong Kong   | 7         | 0.72%   |
| Denmark     | 7         | 0.72%   |
| Ukraine     | 6         | 0.62%   |
| Portugal    | 6         | 0.62%   |
| New Zealand | 6         | 0.62%   |
| Malaysia    | 6         | 0.62%   |
| Hungary     | 6         | 0.62%   |
| Greece      | 6         | 0.62%   |
| Czechia     | 6         | 0.62%   |
| Bangladesh  | 6         | 0.62%   |
| Vietnam     | 5         | 0.52%   |
| Slovenia    | 5         | 0.52%   |
| Philippines | 5         | 0.52%   |
| Norway      | 5         | 0.52%   |
| Croatia     | 5         | 0.52%   |
| Singapore   | 4         | 0.41%   |
| Serbia      | 4         | 0.41%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Montreal          | 13        | 1.28%   |
| Helsinki          | 12        | 1.18%   |
| Berlin            | 11        | 1.08%   |
| Milan             | 10        | 0.98%   |
| Amsterdam         | 10        | 0.98%   |
| Sydney            | 8         | 0.79%   |
| St Petersburg     | 8         | 0.79%   |
| Paris             | 8         | 0.79%   |
| Warsaw            | 7         | 0.69%   |
| Toms River        | 7         | 0.69%   |
| Istanbul          | 7         | 0.69%   |
| Hamburg           | 7         | 0.69%   |
| Turin             | 6         | 0.59%   |
| Rome              | 6         | 0.59%   |
| Moscow            | 6         | 0.59%   |
| Wroclaw           | 5         | 0.49%   |
| Toronto           | 5         | 0.49%   |
| Madrid            | 5         | 0.49%   |
| Frankfurt am Main | 5         | 0.49%   |
| Barberton         | 5         | 0.49%   |
| Zurich            | 4         | 0.39%   |
| Vienna            | 4         | 0.39%   |
| Victoria          | 4         | 0.39%   |
| Singapore         | 4         | 0.39%   |
| Portland          | 4         | 0.39%   |
| Ottawa            | 4         | 0.39%   |
| Melbourne         | 4         | 0.39%   |
| Malmo             | 4         | 0.39%   |
| London            | 4         | 0.39%   |
| Leipzig           | 4         | 0.39%   |
| Jacksonville      | 4         | 0.39%   |
| Brussels          | 4         | 0.39%   |
| Belgrade          | 4         | 0.39%   |
| Zirl              | 3         | 0.29%   |
| Villa Ballester   | 3         | 0.29%   |
| Sofia             | 3         | 0.29%   |
| Severna Park      | 3         | 0.29%   |
| Seattle           | 3         | 0.29%   |
| Schiedam          | 3         | 0.29%   |
| Rotterdam         | 3         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 323       | 483    | 20.72%  |
| Seagate                        | 187       | 260    | 11.99%  |
| WDC                            | 176       | 274    | 11.29%  |
| Kingston                       | 106       | 150    | 6.8%    |
| SanDisk                        | 102       | 123    | 6.54%   |
| Crucial                        | 72        | 102    | 4.62%   |
| Toshiba                        | 62        | 72     | 3.98%   |
| SK hynix                       | 53        | 63     | 3.4%    |
| Micron Technology              | 39        | 42     | 2.5%    |
| Intel                          | 39        | 51     | 2.5%    |
| Unknown                        | 36        | 49     | 2.31%   |
| HGST                           | 25        | 32     | 1.6%    |
| KIOXIA                         | 21        | 22     | 1.35%   |
| Hitachi                        | 20        | 21     | 1.28%   |
| Phison                         | 19        | 20     | 1.22%   |
| Apple                          | 19        | 26     | 1.22%   |
| A-DATA Technology              | 18        | 26     | 1.15%   |
| Phison Electronics             | 16        | 17     | 1.03%   |
| China                          | 13        | 13     | 0.83%   |
| Kingston Technology Company    | 12        | 14     | 0.77%   |
| Corsair                        | 9         | 9      | 0.58%   |
| PNY                            | 8         | 9      | 0.51%   |
| SPCC                           | 7         | 7      | 0.45%   |
| LITEONIT                       | 7         | 8      | 0.45%   |
| Patriot                        | 6         | 8      | 0.38%   |
| OCZ                            | 6         | 6      | 0.38%   |
| Micron/Crucial Technology      | 6         | 13     | 0.38%   |
| Gigabyte Technology            | 6         | 8      | 0.38%   |
| XPG                            | 5         | 5      | 0.32%   |
| Transcend                      | 5         | 6      | 0.32%   |
| Silicon Motion                 | 5         | 5      | 0.32%   |
| Mushkin                        | 5         | 5      | 0.32%   |
| LITEON                         | 5         | 7      | 0.32%   |
| Intenso                        | 5         | 7      | 0.32%   |
| SABRENT                        | 4         | 6      | 0.26%   |
| JMicron Technology             | 4         | 4      | 0.26%   |
| Union Memory (Shenzhen)        | 3         | 3      | 0.19%   |
| SSSTC                          | 3         | 3      | 0.19%   |
| Solid State Storage Technology | 3         | 5      | 0.19%   |
| Realtek Semiconductor          | 3         | 3      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 44        | 2.53%   |
| Seagate ST2000DM008-2FR102 2TB                      | 24        | 1.38%   |
| Seagate ST1000LM035-1RK172 1TB                      | 19        | 1.09%   |
| Samsung SSD 860 EVO 1TB                             | 19        | 1.09%   |
| Crucial CT500MX500SSD1 500GB                        | 18        | 1.03%   |
| Samsung SSD 860 EVO 500GB                           | 17        | 0.98%   |
| Samsung SSD 850 EVO 250GB                           | 17        | 0.98%   |
| Kingston SA400S37240G 240GB SSD                     | 17        | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 16        | 0.92%   |
| Kingston SA400S37120G 120GB SSD                     | 15        | 0.86%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 14        | 0.8%    |
| Samsung SSD 850 EVO 500GB                           | 13        | 0.75%   |
| Kingston SA400S37480G 480GB SSD                     | 13        | 0.75%   |
| Samsung SSD 870 QVO 1TB                             | 12        | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB                      | 11        | 0.63%   |
| HGST HTS721010A9E630 1TB                            | 11        | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB                      | 10        | 0.57%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 10        | 0.57%   |
| Samsung SSD 860 EVO 250GB                           | 10        | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 9         | 0.52%   |
| Samsung SSD 970 EVO 500GB                           | 9         | 0.52%   |
| Crucial CT240BX500SSD1 240GB                        | 9         | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                         | 9         | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 8         | 0.46%   |
| Seagate ST500LT012-1DG142 500GB                     | 8         | 0.46%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 8         | 0.46%   |
| Unknown SD/MMC/MS PRO 250GB                         | 7         | 0.4%    |
| Unknown MMC Card  64GB                              | 7         | 0.4%    |
| Seagate ST2000DM006-2DM164 2TB                      | 7         | 0.4%    |
| Seagate Expansion Desk 5TB                          | 7         | 0.4%    |
| Samsung SSD 980 500GB                               | 7         | 0.4%    |
| Samsung NVMe SSD Drive 512GB                        | 7         | 0.4%    |
| Samsung NVMe SSD Drive 1TB                          | 7         | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 6         | 0.34%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 6         | 0.34%   |
| Unknown MMC Card  128GB                             | 6         | 0.34%   |
| SK hynix HFM001TD3JX013N 1TB                        | 6         | 0.34%   |
| Seagate Expansion 1TB                               | 6         | 0.34%   |
| Samsung SSD 980 1TB                                 | 6         | 0.34%   |
| Samsung SSD 870 EVO 250GB                           | 6         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 178       | 247    | 42.38%  |
| WDC                 | 121       | 181    | 28.81%  |
| Toshiba             | 38        | 42     | 9.05%   |
| HGST                | 25        | 32     | 5.95%   |
| Hitachi             | 20        | 21     | 4.76%   |
| Samsung Electronics | 11        | 26     | 2.62%   |
| Unknown             | 7         | 7      | 1.67%   |
| Maxone              | 3         | 3      | 0.71%   |
| Fujitsu             | 3         | 3      | 0.71%   |
| ASMT                | 2         | 4      | 0.48%   |
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

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 167       | 230    | 29.2%   |
| Kingston            | 75        | 109    | 13.11%  |
| Crucial             | 65        | 86     | 11.36%  |
| WDC                 | 40        | 52     | 6.99%   |
| SanDisk             | 40        | 47     | 6.99%   |
| Micron Technology   | 13        | 15     | 2.27%   |
| China               | 13        | 13     | 2.27%   |
| Intel               | 12        | 15     | 2.1%    |
| Apple               | 11        | 14     | 1.92%   |
| A-DATA Technology   | 11        | 12     | 1.92%   |
| Toshiba             | 9         | 11     | 1.57%   |
| SK hynix            | 8         | 9      | 1.4%    |
| LITEONIT            | 7         | 8      | 1.22%   |
| Patriot             | 6         | 8      | 1.05%   |
| OCZ                 | 6         | 6      | 1.05%   |
| SPCC                | 5         | 5      | 0.87%   |
| Seagate             | 5         | 7      | 0.87%   |
| PNY                 | 5         | 6      | 0.87%   |
| Intenso             | 5         | 7      | 0.87%   |
| Gigabyte Technology | 5         | 6      | 0.87%   |
| Corsair             | 5         | 5      | 0.87%   |
| Transcend           | 4         | 4      | 0.7%    |
| Mushkin             | 4         | 4      | 0.7%    |
| LITEON              | 4         | 5      | 0.7%    |
| WDC WDS             | 2         | 2      | 0.35%   |
| Phison              | 2         | 2      | 0.35%   |
| Netac               | 2         | 3      | 0.35%   |
| Leven               | 2         | 3      | 0.35%   |
| KingSpec            | 2         | 2      | 0.35%   |
| GOODRAM             | 2         | 2      | 0.35%   |
| Emtec               | 2         | 2      | 0.35%   |
| Zheino              | 1         | 1      | 0.17%   |
| WALTON              | 1         | 2      | 0.17%   |
| V-GeN               | 1         | 1      | 0.17%   |
| Unknown             | 1         | 2      | 0.17%   |
| UMAX                | 1         | 1      | 0.17%   |
| Timetec             | 1         | 8      | 0.17%   |
| Teclast             | 1         | 3      | 0.17%   |
| Team                | 1         | 2      | 0.17%   |
| TAMMUZ              | 1         | 2      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 516       | 720    | 37.77%  |
| SSD     | 456       | 750    | 33.38%  |
| HDD     | 349       | 580    | 25.55%  |
| MMC     | 28        | 37     | 2.05%   |
| Unknown | 17        | 23     | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 600       | 1250   | 49.3%   |
| NVMe | 512       | 706    | 42.07%  |
| SAS  | 77        | 117    | 6.33%   |
| MMC  | 28        | 37     | 2.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 431       | 729    | 49.77%  |
| 0.51-1.0   | 272       | 373    | 31.41%  |
| 1.01-2.0   | 92        | 135    | 10.62%  |
| 3.01-4.0   | 30        | 44     | 3.46%   |
| 4.01-10.0  | 21        | 28     | 2.42%   |
| 2.01-3.0   | 17        | 18     | 1.96%   |
| 10.01-20.0 | 3         | 3      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 207       | 20.66%  |
| 251-500        | 172       | 17.17%  |
| 1001-2000      | 163       | 16.27%  |
| 501-1000       | 144       | 14.37%  |
| More than 3000 | 93        | 9.28%   |
| Unknown        | 61        | 6.09%   |
| 2001-3000      | 56        | 5.59%   |
| 1-20           | 48        | 4.79%   |
| 51-100         | 38        | 3.79%   |
| 21-50          | 20        | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 228       | 21.8%   |
| 101-250        | 160       | 15.3%   |
| 21-50          | 151       | 14.44%  |
| 51-100         | 136       | 13%     |
| 251-500        | 101       | 9.66%   |
| 501-1000       | 88        | 8.41%   |
| 1001-2000      | 76        | 7.27%   |
| Unknown        | 61        | 5.83%   |
| More than 3000 | 27        | 2.58%   |
| 2001-3000      | 14        | 1.34%   |
| 0              | 4         | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 4.4%    |
| HGST HTS545050A7E680 500GB               | 4         | 8      | 4.4%    |
| Hitachi HTS545050A7E380 500GB            | 3         | 3      | 3.3%    |
| WDC WD20EARX-00PASB0 2TB                 | 2         | 2      | 2.2%    |
| Seagate ST9320325AS 320GB                | 2         | 5      | 2.2%    |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 2.2%    |
| Seagate ST500LM021-1KJ152 500GB          | 2         | 7      | 2.2%    |
| XPG GAMMIX S11 240GB                     | 1         | 1      | 1.1%    |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 1.1%    |
| WDC WDS120G2G0A-00JH30 128GB SSD         | 1         | 1      | 1.1%    |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1      | 1.1%    |
| WDC WD5000AZRX-00A8LB0 500GB             | 1         | 1      | 1.1%    |
| WDC WD5000AVDS-63U7B1 500GB              | 1         | 1      | 1.1%    |
| WDC WD40EFRX-68WT0N0 4TB                 | 1         | 2      | 1.1%    |
| WDC WD2003FZEX-00Z4SA0 2TB               | 1         | 1      | 1.1%    |
| WDC WD2002FYPS-01U1B0 2TB                | 1         | 1      | 1.1%    |
| WDC WD10SPZX-24Z10T0 1TB                 | 1         | 1      | 1.1%    |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.1%    |
| WDC WD10EARS-00MVWB0 1TB                 | 1         | 1      | 1.1%    |
| WDC WD10EACS-00D6B1 1TB                  | 1         | 1      | 1.1%    |
| WDC WD1003FBYZ-010FB0 1TB                | 1         | 2      | 1.1%    |
| WDC WD Blue SA510 2.5 1TB SSD            | 1         | 2      | 1.1%    |
| WDC PC SA530 SDASN8Y-256G-1006 256GB     | 1         | 1      | 1.1%    |
| Transcend TS240GMTS420S 240GB SSD        | 1         | 1      | 1.1%    |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 1.1%    |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 1.1%    |
| Toshiba MQ01ABD050 500GB                 | 1         | 1      | 1.1%    |
| Toshiba MK5055GSXF 500GB                 | 1         | 1      | 1.1%    |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1      | 1.1%    |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 1.1%    |
| SSSTC CV8-8E128-HP 128GB SSD             | 1         | 1      | 1.1%    |
| SK hynix SC308 SATA 128GB SSD            | 1         | 1      | 1.1%    |
| SK hynix HFS512G39TND-N210A 512GB SSD    | 1         | 1      | 1.1%    |
| SK hynix HFS128G39TND-N210A 128GB SSD    | 1         | 1      | 1.1%    |
| Seagate ST6000VX0023-2EF110 6TB          | 1         | 1      | 1.1%    |
| Seagate ST500LX012-SSHD-8GB              | 1         | 1      | 1.1%    |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 1      | 1.1%    |
| Seagate ST3320620AS 320GB                | 1         | 1      | 1.1%    |
| Seagate ST2000LX001-1RG174 2TB           | 1         | 1      | 1.1%    |
| Seagate ST2000DX002-2DV164 2TB           | 1         | 1      | 1.1%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 28     | 19.1%   |
| WDC                 | 16        | 20     | 17.98%  |
| Samsung Electronics | 8         | 10     | 8.99%   |
| HGST                | 8         | 12     | 8.99%   |
| Toshiba             | 6         | 6      | 6.74%   |
| Hitachi             | 5         | 5      | 5.62%   |
| Crucial             | 4         | 11     | 4.49%   |
| SK hynix            | 3         | 3      | 3.37%   |
| SanDisk             | 3         | 4      | 3.37%   |
| Intel               | 3         | 3      | 3.37%   |
| Kingston            | 2         | 2      | 2.25%   |
| Apple               | 2         | 2      | 2.25%   |
| XPG                 | 1         | 1      | 1.12%   |
| Transcend           | 1         | 1      | 1.12%   |
| SSSTC               | 1         | 1      | 1.12%   |
| Patriot             | 1         | 1      | 1.12%   |
| OCZ                 | 1         | 1      | 1.12%   |
| Micron Technology   | 1         | 1      | 1.12%   |
| Fujitsu             | 1         | 1      | 1.12%   |
| Drevo               | 1         | 1      | 1.12%   |
| Corsair             | 1         | 1      | 1.12%   |
| China               | 1         | 1      | 1.12%   |
| ASMT                | 1         | 2      | 1.12%   |
| A-DATA Technology   | 1         | 1      | 1.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 28     | 34%     |
| WDC                 | 13        | 15     | 26%     |
| HGST                | 8         | 12     | 16%     |
| Hitachi             | 5         | 5      | 10%     |
| Toshiba             | 4         | 4      | 8%      |
| Samsung Electronics | 1         | 1      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |
| ASMT                | 1         | 2      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 68     | 56.98%  |
| SSD  | 31        | 43     | 36.05%  |
| NVMe | 6         | 8      | 6.98%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 33.33%  |
| Samsung Electronics HD252HJ 250GB | 1         | 1      | 33.33%  |
| LITEON CA3-8D512 512GB            | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| LITEON              | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 673       | 1317   | 62.31%  |
| Detected | 322       | 670    | 29.81%  |
| Malfunc  | 82        | 119    | 7.59%   |
| Failed   | 3         | 4      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 509       | 37.54%  |
| AMD                            | 245       | 18.07%  |
| Samsung Electronics            | 187       | 13.79%  |
| SanDisk                        | 95        | 7.01%   |
| Kingston Technology Company    | 46        | 3.39%   |
| SK hynix                       | 44        | 3.24%   |
| Phison Electronics             | 41        | 3.02%   |
| ASMedia Technology             | 32        | 2.36%   |
| Micron Technology              | 27        | 1.99%   |
| KIOXIA                         | 23        | 1.7%    |
| Toshiba America Info Systems   | 15        | 1.11%   |
| Micron/Crucial Technology      | 13        | 0.96%   |
| ADATA Technology               | 10        | 0.74%   |
| Silicon Motion                 | 8         | 0.59%   |
| Solid State Storage Technology | 7         | 0.52%   |
| Realtek Semiconductor          | 7         | 0.52%   |
| Marvell Technology Group       | 7         | 0.52%   |
| Apple                          | 7         | 0.52%   |
| JMicron Technology             | 6         | 0.44%   |
| Nvidia                         | 5         | 0.37%   |
| Union Memory (Shenzhen)        | 4         | 0.29%   |
| Seagate Technology             | 4         | 0.29%   |
| Lenovo                         | 3         | 0.22%   |
| Transcend                      | 2         | 0.15%   |
| Shenzhen Longsys Electronics   | 2         | 0.15%   |
| Lite-On Technology             | 2         | 0.15%   |
| Yangtze Memory Technologies    | 1         | 0.07%   |
| LSI Logic / Symbios Logic      | 1         | 0.07%   |
| INNOGRIT                       | 1         | 0.07%   |
| Broadcom / LSI                 | 1         | 0.07%   |
| Biwin Storage Technology       | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 188       | 12.76%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 93        | 6.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 60        | 4.07%   |
| AMD 400 Series Chipset SATA Controller                                         | 53        | 3.6%    |
| Samsung NVMe SSD Controller 980                                                | 48        | 3.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 41        | 2.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 31        | 2.1%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 31        | 2.1%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 26        | 1.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 1.77%   |
| AMD 500 Series Chipset SATA Controller                                         | 26        | 1.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 25        | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 25        | 1.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 24        | 1.63%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 23        | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 23        | 1.56%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 19        | 1.29%   |
| Phison E12 NVMe Controller                                                     | 17        | 1.15%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 17        | 1.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 17        | 1.15%   |
| Phison E16 PCIe4 NVMe Controller                                               | 16        | 1.09%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 16        | 1.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 16        | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                          | 16        | 1.09%   |
| Intel SSD 660P Series                                                          | 15        | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 15        | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 14        | 0.95%   |
| Micron NVMe Storage Controller                                                 | 13        | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                            | 13        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 13        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 0.88%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 12        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 0.81%   |
| Kingston Company Company Non-Volatile memory controller                        | 12        | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 0.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 11        | 0.75%   |
| Kingston Company A2000 NVMe SSD                                                | 10        | 0.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 10        | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 9         | 0.61%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 9         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 680       | 52.51%  |
| NVMe | 510       | 39.38%  |
| RAID | 69        | 5.33%   |
| IDE  | 32        | 2.47%   |
| SAS  | 4         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 615       | 63.93%  |
| AMD    | 346       | 35.97%  |
| ARM    | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor            | 16        | 1.66%   |
| AMD Ryzen 5 3600 6-Core Processor             | 16        | 1.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 1.56%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 14        | 1.46%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 1.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 13        | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 1.25%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 1.25%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 1.25%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 12        | 1.25%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 11        | 1.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 11        | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.94%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 9         | 0.94%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 9         | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 9         | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 0.94%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 9         | 0.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 0.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.83%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 8         | 0.83%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 0.83%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 8         | 0.83%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 0.83%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 0.73%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.73%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 7         | 0.73%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 0.73%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.62%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 0.62%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.62%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 6         | 0.62%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 6         | 0.62%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 6         | 0.62%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 0.62%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 0.52%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 220       | 22.87%  |
| Intel Core i7           | 180       | 18.71%  |
| AMD Ryzen 5             | 120       | 12.47%  |
| AMD Ryzen 7             | 115       | 11.95%  |
| Other                   | 82        | 8.52%   |
| Intel Core i3           | 45        | 4.68%   |
| AMD Ryzen 9             | 42        | 4.37%   |
| Intel Celeron           | 31        | 3.22%   |
| Intel Core 2 Duo        | 18        | 1.87%   |
| Intel Xeon              | 16        | 1.66%   |
| AMD Ryzen 7 PRO         | 14        | 1.46%   |
| AMD Ryzen 3             | 12        | 1.25%   |
| Intel Pentium           | 10        | 1.04%   |
| AMD A4                  | 8         | 0.83%   |
| AMD FX                  | 6         | 0.62%   |
| Intel Core m3           | 4         | 0.42%   |
| AMD A8                  | 4         | 0.42%   |
| Intel Core i9           | 3         | 0.31%   |
| Intel Core 2 Quad       | 3         | 0.31%   |
| AMD Ryzen Threadripper  | 3         | 0.31%   |
| AMD Ryzen 5 PRO         | 3         | 0.31%   |
| AMD Athlon              | 3         | 0.31%   |
| AMD A10                 | 3         | 0.31%   |
| Intel Pentium Dual-Core | 2         | 0.21%   |
| Intel Core 2            | 2         | 0.21%   |
| Intel Atom              | 2         | 0.21%   |
| AMD E1                  | 2         | 0.21%   |
| Intel Pentium Gold      | 1         | 0.1%    |
| Intel Pentium Dual      | 1         | 0.1%    |
| Intel Core m5           | 1         | 0.1%    |
| Intel Core 2 Extreme    | 1         | 0.1%    |
| AMD Phenom II X4        | 1         | 0.1%    |
| AMD E                   | 1         | 0.1%    |
| AMD Athlon X4           | 1         | 0.1%    |
| AMD Athlon II X4        | 1         | 0.1%    |
| AMD Athlon II           | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 336       | 34.89%  |
| 2      | 255       | 26.48%  |
| 8      | 168       | 17.45%  |
| 6      | 146       | 15.16%  |
| 12     | 27        | 2.8%    |
| 14     | 11        | 1.14%   |
| 10     | 8         | 0.83%   |
| 16     | 7         | 0.73%   |
| 3      | 3         | 0.31%   |
| 32     | 1         | 0.1%    |
| 1      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 957       | 99.38%  |
| 2      | 6         | 0.62%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 778       | 80.87%  |
| 1      | 184       | 19.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 959       | 99.69%  |
| Unknown        | 2         | 0.21%   |
| 64-bit         | 1         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 361       | 36.61%  |
| 0x0a50000c | 34        | 3.45%   |
| 0x306c3    | 31        | 3.14%   |
| 0x08701021 | 28        | 2.84%   |
| 0x306a9    | 24        | 2.43%   |
| 0x806ea    | 23        | 2.33%   |
| 0x406e3    | 22        | 2.23%   |
| 0x906ea    | 20        | 2.03%   |
| 0x806e9    | 20        | 2.03%   |
| 0x08600106 | 19        | 1.93%   |
| 0x806ec    | 18        | 1.83%   |
| 0x506e3    | 18        | 1.83%   |
| 0x08108109 | 18        | 1.83%   |
| 0x806c1    | 17        | 1.72%   |
| 0x40651    | 17        | 1.72%   |
| 0x08600104 | 16        | 1.62%   |
| 0x906e9    | 15        | 1.52%   |
| 0x08608103 | 15        | 1.52%   |
| 0x706e5    | 12        | 1.22%   |
| 0x206a7    | 11        | 1.12%   |
| 0x0a201009 | 11        | 1.12%   |
| 0x08701013 | 11        | 1.12%   |
| 0x08108102 | 11        | 1.12%   |
| 0x706a1    | 9         | 0.91%   |
| 0x306d4    | 9         | 0.91%   |
| 0x1067a    | 8         | 0.81%   |
| 0x0a404102 | 8         | 0.81%   |
| 0x0a20120a | 8         | 0.81%   |
| 0x906a3    | 7         | 0.71%   |
| 0x406c4    | 7         | 0.71%   |
| 0x0a201016 | 7         | 0.71%   |
| 0x0800820d | 7         | 0.71%   |
| 0xa0652    | 6         | 0.61%   |
| 0x806d1    | 6         | 0.61%   |
| 0x0a50000d | 6         | 0.61%   |
| 0x06006705 | 6         | 0.61%   |
| 0xa0655    | 5         | 0.51%   |
| 0x20655    | 5         | 0.51%   |
| 0x0a404101 | 5         | 0.51%   |
| 0x08001138 | 5         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 182       | 18.9%   |
| Zen 2            | 108       | 11.21%  |
| Zen 3            | 90        | 9.35%   |
| Haswell          | 82        | 8.52%   |
| Unknown          | 60        | 6.23%   |
| Skylake          | 59        | 6.13%   |
| Zen+             | 49        | 5.09%   |
| IvyBridge        | 45        | 4.67%   |
| TigerLake        | 36        | 3.74%   |
| CometLake        | 28        | 2.91%   |
| Icelake          | 27        | 2.8%    |
| SandyBridge      | 25        | 2.6%    |
| Broadwell        | 23        | 2.39%   |
| Zen              | 20        | 2.08%   |
| Alderlake Hybrid | 19        | 1.97%   |
| Penryn           | 18        | 1.87%   |
| Silvermont       | 14        | 1.45%   |
| Westmere         | 12        | 1.25%   |
| Goldmont plus    | 12        | 1.25%   |
| Excavator        | 12        | 1.25%   |
| Core             | 10        | 1.04%   |
| Piledriver       | 7         | 0.73%   |
| Jaguar           | 6         | 0.62%   |
| Nehalem          | 5         | 0.52%   |
| Tremont          | 3         | 0.31%   |
| Puma             | 2         | 0.21%   |
| K10              | 2         | 0.21%   |
| Goldmont         | 2         | 0.21%   |
| Bulldozer        | 2         | 0.21%   |
| Steamroller      | 1         | 0.1%    |
| K10 Llano        | 1         | 0.1%    |
| Bobcat           | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 479       | 40.66%  |
| Nvidia | 366       | 31.07%  |
| AMD    | 333       | 28.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 52        | 4.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 3.23%   |
| Intel UHD Graphics 620                                                                   | 38        | 3.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 36        | 2.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 34        | 2.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 31        | 2.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 2.32%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 2.24%   |
| Intel HD Graphics 620                                                                    | 25        | 2.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 1.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 22        | 1.82%   |
| AMD Lucienne                                                                             | 21        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 19        | 1.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 1.57%   |
| AMD Rembrandt [Radeon 680M]                                                              | 19        | 1.57%   |
| Intel HD Graphics 5500                                                                   | 16        | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 15        | 1.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.24%   |
| Intel HD Graphics 630                                                                    | 15        | 1.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 1.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 1.08%   |
| Intel HD Graphics 530                                                                    | 13        | 1.08%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 13        | 1.08%   |
| Nvidia GP108M [GeForce MX150]                                                            | 12        | 0.99%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 0.99%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 12        | 0.99%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 12        | 0.99%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 12        | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 10        | 0.83%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 10        | 0.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 9         | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 0.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 8         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 307       | 31.75%  |
| 1 x AMD                  | 247       | 25.54%  |
| 1 x Nvidia               | 176       | 18.2%   |
| Intel + Nvidia           | 142       | 14.68%  |
| AMD + Nvidia             | 43        | 4.45%   |
| 2 x AMD                  | 24        | 2.48%   |
| Intel + AMD              | 20        | 2.07%   |
| 2 x Nvidia               | 3         | 0.31%   |
| 2 x Intel                | 3         | 0.31%   |
| Other                    | 1         | 0.1%    |
| Intel + AMD + 1 x Nvidia | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 688       | 71.3%   |
| Proprietary | 276       | 28.6%   |
| Unknown     | 1         | 0.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 528       | 53.88%  |
| 0.01-0.5   | 108       | 11.02%  |
| 1.01-2.0   | 86        | 8.78%   |
| 7.01-8.0   | 77        | 7.86%   |
| 3.01-4.0   | 65        | 6.63%   |
| 5.01-6.0   | 38        | 3.88%   |
| 8.01-16.0  | 35        | 3.57%   |
| 0.51-1.0   | 31        | 3.16%   |
| 2.01-3.0   | 7         | 0.71%   |
| 16.01-24.0 | 5         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 138       | 11.74%  |
| Samsung Electronics     | 122       | 10.38%  |
| BOE                     | 116       | 9.87%   |
| Chimei Innolux          | 107       | 9.11%   |
| LG Display              | 89        | 7.57%   |
| Goldstar                | 59        | 5.02%   |
| Dell                    | 53        | 4.51%   |
| Acer                    | 49        | 4.17%   |
| AOC                     | 40        | 3.4%    |
| Ancor Communications    | 34        | 2.89%   |
| Lenovo                  | 31        | 2.64%   |
| BenQ                    | 29        | 2.47%   |
| Hewlett-Packard         | 28        | 2.38%   |
| Apple                   | 26        | 2.21%   |
| PANDA                   | 22        | 1.87%   |
| ASUSTek Computer        | 21        | 1.79%   |
| Sharp                   | 19        | 1.62%   |
| Philips                 | 15        | 1.28%   |
| ViewSonic               | 14        | 1.19%   |
| Iiyama                  | 13        | 1.11%   |
| InfoVision              | 12        | 1.02%   |
| Gigabyte Technology     | 9         | 0.77%   |
| Vizio                   | 8         | 0.68%   |
| CSO                     | 7         | 0.6%    |
| TMX                     | 6         | 0.51%   |
| LG Electronics          | 6         | 0.51%   |
| Sony                    | 5         | 0.43%   |
| Chi Mei Optoelectronics | 5         | 0.43%   |
| Pixio                   | 4         | 0.34%   |
| Valve                   | 3         | 0.26%   |
| Toshiba                 | 3         | 0.26%   |
| RTK                     | 3         | 0.26%   |
| Panasonic               | 3         | 0.26%   |
| MSI                     | 3         | 0.26%   |
| Mi                      | 3         | 0.26%   |
| LG Philips              | 3         | 0.26%   |
| JDI                     | 3         | 0.26%   |
| Fujitsu Siemens         | 3         | 0.26%   |
| Eizo                    | 3         | 0.26%   |
| Unknown (XXX)           | 2         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 9         | 0.74%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.66%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 7         | 0.58%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 7         | 0.58%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 7         | 0.58%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.49%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                  | 6         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.49%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 5         | 0.41%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5         | 0.41%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 5         | 0.41%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 5         | 0.41%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 5         | 0.41%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 5         | 0.41%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 4         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 4         | 0.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4         | 0.33%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.33%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 0.33%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.33%   |
| Valve Index HMD VLV91A8 2880x1600                                     | 3         | 0.25%   |
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

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 544       | 49.05%  |
| 1366x768 (WXGA)    | 139       | 12.53%  |
| 2560x1440 (QHD)    | 103       | 9.29%   |
| 3840x2160 (4K)     | 80        | 7.21%   |
| 2560x1600          | 27        | 2.43%   |
| 1440x900 (WXGA+)   | 24        | 2.16%   |
| 1920x1200 (WUXGA)  | 23        | 2.07%   |
| 2560x1080          | 19        | 1.71%   |
| 1600x900 (HD+)     | 17        | 1.53%   |
| 1280x1024 (SXGA)   | 15        | 1.35%   |
| 1680x1050 (WSXGA+) | 13        | 1.17%   |
| 2880x1800          | 12        | 1.08%   |
| Unknown            | 12        | 1.08%   |
| 3440x1440          | 10        | 0.9%    |
| 1280x800 (WXGA)    | 8         | 0.72%   |
| 2160x1440          | 7         | 0.63%   |
| 1360x768           | 6         | 0.54%   |
| 3840x2400          | 5         | 0.45%   |
| 2736x1824          | 5         | 0.45%   |
| 3840x1080          | 4         | 0.36%   |
| 3200x2000          | 4         | 0.36%   |
| 3840x1600          | 2         | 0.18%   |
| 3456x2160          | 2         | 0.18%   |
| 3200x1800 (QHD+)   | 2         | 0.18%   |
| 3000x2000          | 2         | 0.18%   |
| 1920x540           | 2         | 0.18%   |
| 1800x1200          | 2         | 0.18%   |
| 1024x768 (XGA)     | 2         | 0.18%   |
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

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 271       | 22.99%  |
| 13      | 129       | 10.94%  |
| 27      | 116       | 9.84%   |
| 24      | 115       | 9.75%   |
| 14      | 100       | 8.48%   |
| 23      | 62        | 5.26%   |
| 21      | 55        | 4.66%   |
| 17      | 45        | 3.82%   |
| 31      | 35        | 2.97%   |
| Unknown | 34        | 2.88%   |
| 34      | 26        | 2.21%   |
| 16      | 23        | 1.95%   |
| 12      | 20        | 1.7%    |
| 19      | 16        | 1.36%   |
| 18      | 15        | 1.27%   |
| 22      | 12        | 1.02%   |
| 11      | 11        | 0.93%   |
| 54      | 10        | 0.85%   |
| 20      | 10        | 0.85%   |
| 32      | 7         | 0.59%   |
| 84      | 6         | 0.51%   |
| 40      | 5         | 0.42%   |
| 10      | 5         | 0.42%   |
| 46      | 4         | 0.34%   |
| 29      | 4         | 0.34%   |
| 28      | 4         | 0.34%   |
| 72      | 3         | 0.25%   |
| 49      | 3         | 0.25%   |
| 42      | 3         | 0.25%   |
| 26      | 3         | 0.25%   |
| 25      | 3         | 0.25%   |
| 74      | 2         | 0.17%   |
| 69      | 2         | 0.17%   |
| 65      | 2         | 0.17%   |
| 58      | 2         | 0.17%   |
| 52      | 2         | 0.17%   |
| 37      | 2         | 0.17%   |
| 36      | 2         | 0.17%   |
| 35      | 2         | 0.17%   |
| 33      | 2         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 451       | 39.74%  |
| 501-600     | 260       | 22.91%  |
| 201-300     | 105       | 9.25%   |
| 401-500     | 97        | 8.55%   |
| 351-400     | 52        | 4.58%   |
| 601-700     | 47        | 4.14%   |
| 701-800     | 37        | 3.26%   |
| Unknown     | 34        | 3%      |
| 1001-1500   | 26        | 2.29%   |
| 1501-2000   | 13        | 1.15%   |
| 801-900     | 9         | 0.79%   |
| 901-1000    | 3         | 0.26%   |
| 101-200     | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 784       | 77.55%  |
| 16/10   | 120       | 11.87%  |
| 21/9    | 29        | 2.87%   |
| Unknown | 29        | 2.87%   |
| 3/2     | 22        | 2.18%   |
| 5/4     | 11        | 1.09%   |
| 4/3     | 6         | 0.59%   |
| 32/9    | 3         | 0.3%    |
| 2.65    | 3         | 0.3%    |
| 6/5     | 2         | 0.2%    |
| 3.40    | 1         | 0.1%    |
| 0.62    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 270       | 23.34%  |
| 201-250        | 183       | 15.82%  |
| 81-90          | 174       | 15.04%  |
| 301-350        | 120       | 10.37%  |
| 351-500        | 71        | 6.14%   |
| 71-80          | 59        | 5.1%    |
| 251-300        | 40        | 3.46%   |
| 151-200        | 37        | 3.2%    |
| 121-130        | 35        | 3.03%   |
| Unknown        | 34        | 2.94%   |
| More than 1000 | 32        | 2.77%   |
| 111-120        | 22        | 1.9%    |
| 501-1000       | 21        | 1.82%   |
| 141-150        | 20        | 1.73%   |
| 61-70          | 13        | 1.12%   |
| 51-60          | 12        | 1.04%   |
| 131-140        | 6         | 0.52%   |
| 41-50          | 5         | 0.43%   |
| 91-100         | 2         | 0.17%   |
| 1-40           | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 356       | 32.25%  |
| 51-100        | 311       | 28.17%  |
| 101-120       | 231       | 20.92%  |
| 161-240       | 105       | 9.51%   |
| More than 240 | 39        | 3.53%   |
| Unknown       | 34        | 3.08%   |
| 1-50          | 28        | 2.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 745       | 75.79%  |
| 2     | 204       | 20.75%  |
| 3     | 29        | 2.95%   |
| 0     | 3         | 0.31%   |
| 4     | 2         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 569       | 38.52%  |
| Intel                             | 535       | 36.22%  |
| Qualcomm Atheros                  | 114       | 7.72%   |
| Broadcom                          | 48        | 3.25%   |
| MediaTek                          | 46        | 3.11%   |
| ASIX Electronics                  | 19        | 1.29%   |
| TP-Link                           | 15        | 1.02%   |
| Microsoft                         | 12        | 0.81%   |
| Broadcom Limited                  | 12        | 0.81%   |
| D-Link                            | 11        | 0.74%   |
| Lenovo                            | 7         | 0.47%   |
| Sierra Wireless                   | 6         | 0.41%   |
| Ralink                            | 6         | 0.41%   |
| DisplayLink                       | 6         | 0.41%   |
| Ralink Technology                 | 5         | 0.34%   |
| Marvell Technology Group          | 5         | 0.34%   |
| Samsung Electronics               | 4         | 0.27%   |
| Hewlett-Packard                   | 4         | 0.27%   |
| Google                            | 4         | 0.27%   |
| Cypress Semiconductor             | 4         | 0.27%   |
| Aquantia                          | 4         | 0.27%   |
| Apple                             | 4         | 0.27%   |
| OPPO Electronics                  | 3         | 0.2%    |
| Nvidia                            | 3         | 0.2%    |
| Huawei Technologies               | 3         | 0.2%    |
| Xiaomi                            | 2         | 0.14%   |
| Qualcomm                          | 2         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.14%   |
| NetGear                           | 2         | 0.14%   |
| Microchip Technology              | 2         | 0.14%   |
| Linksys                           | 2         | 0.14%   |
| Ericsson Business Mobile Networks | 2         | 0.14%   |
| Wilocity                          | 1         | 0.07%   |
| Qualcomm Atheros Communications   | 1         | 0.07%   |
| Oculus VR                         | 1         | 0.07%   |
| Motorola PCS                      | 1         | 0.07%   |
| InterBiometrics                   | 1         | 0.07%   |
| ICS Advent                        | 1         | 0.07%   |
| Fibocom                           | 1         | 0.07%   |
| Exar                              | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 389       | 22.27%  |
| Intel Wi-Fi 6 AX200                                               | 88        | 5.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 51        | 2.92%   |
| Intel Wireless 8265 / 8275                                        | 40        | 2.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 33        | 1.89%   |
| Intel I211 Gigabit Network Connection                             | 33        | 1.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 31        | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 30        | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 28        | 1.6%    |
| Intel Wireless 7265                                               | 27        | 1.55%   |
| Intel Wi-Fi 6 AX201                                               | 25        | 1.43%   |
| Intel Wireless 7260                                               | 22        | 1.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 1.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 20        | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 1.09%   |
| Intel Wireless 8260                                               | 18        | 1.03%   |
| Intel Wireless 3165                                               | 18        | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 1.03%   |
| Intel Wireless-AC 9260                                            | 17        | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 17        | 0.97%   |
| ASIX AX88179 Gigabit Ethernet                                     | 17        | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 16        | 0.92%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 15        | 0.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 15        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 13        | 0.74%   |
| Realtek 802.11ac NIC                                              | 12        | 0.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 12        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 11        | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 0.63%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.57%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 9         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 459       | 53.37%  |
| Realtek Semiconductor                 | 144       | 16.74%  |
| Qualcomm Atheros                      | 94        | 10.93%  |
| MediaTek                              | 45        | 5.23%   |
| Broadcom                              | 37        | 4.3%    |
| TP-Link                               | 13        | 1.51%   |
| Microsoft                             | 11        | 1.28%   |
| D-Link                                | 11        | 1.28%   |
| Broadcom Limited                      | 11        | 1.28%   |
| Sierra Wireless                       | 6         | 0.7%    |
| Ralink                                | 6         | 0.7%    |
| Ralink Technology                     | 5         | 0.58%   |
| Marvell Technology Group              | 4         | 0.47%   |
| Qualcomm                              | 2         | 0.23%   |
| Linksys                               | 2         | 0.23%   |
| Wilocity                              | 1         | 0.12%   |
| Qualcomm Atheros Communications       | 1         | 0.12%   |
| NetGear                               | 1         | 0.12%   |
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

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 88        | 10.1%   |
| Intel Wireless 8265 / 8275                                    | 40        | 4.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 33        | 3.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 31        | 3.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 30        | 3.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 28        | 3.21%   |
| Intel Wireless 7265                                           | 27        | 3.1%    |
| Intel Wi-Fi 6 AX201                                           | 25        | 2.87%   |
| Intel Wireless 7260                                           | 22        | 2.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 20        | 2.3%    |
| Intel Wireless 8260                                           | 18        | 2.07%   |
| Intel Wireless 3165                                           | 18        | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 18        | 2.07%   |
| Intel Wireless-AC 9260                                        | 17        | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 17        | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 16        | 1.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 15        | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 15        | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 13        | 1.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 13        | 1.49%   |
| Realtek 802.11ac NIC                                          | 12        | 1.38%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 12        | 1.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 12        | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                | 12        | 1.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 11        | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 11        | 1.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 10        | 1.15%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 9         | 1.03%   |
| Intel Wireless 3160                                           | 9         | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                 | 9         | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 8         | 0.92%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 8         | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 8         | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 8         | 0.92%   |
| D-Link 802.11ac NIC                                           | 8         | 0.92%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 8         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 7         | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 6         | 0.69%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 6         | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 6         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 504       | 60.07%  |
| Intel                         | 216       | 25.74%  |
| Qualcomm Atheros              | 33        | 3.93%   |
| ASIX Electronics              | 19        | 2.26%   |
| Broadcom                      | 17        | 2.03%   |
| Lenovo                        | 6         | 0.72%   |
| DisplayLink                   | 6         | 0.72%   |
| Google                        | 4         | 0.48%   |
| Cypress Semiconductor         | 4         | 0.48%   |
| Aquantia                      | 4         | 0.48%   |
| Apple                         | 4         | 0.48%   |
| OPPO Electronics              | 3         | 0.36%   |
| Nvidia                        | 3         | 0.36%   |
| Xiaomi                        | 2         | 0.24%   |
| TP-Link                       | 2         | 0.24%   |
| Samsung Electronics           | 2         | 0.24%   |
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

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 389       | 45.34%  |
| Realtek RTL8125 2.5GbE Controller                                 | 51        | 5.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 4.08%   |
| Intel I211 Gigabit Network Connection                             | 33        | 3.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 3.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 2.56%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 2.21%   |
| ASIX AX88179 Gigabit Ethernet                                     | 17        | 1.98%   |
| Intel Ethernet Controller I225-V                                  | 15        | 1.75%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 1.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 1.4%    |
| Intel Ethernet Connection (7) I219-V                              | 11        | 1.28%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.58%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.58%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.47%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.47%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.47%   |
| Cypress K38231_03                                                 | 4         | 0.47%   |
| Apple iBridge                                                     | 4         | 0.47%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 3         | 0.35%   |
| Realtek PCIe GbE Family Controller                                | 3         | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.35%   |
| OPPO CPH2411                                                      | 3         | 0.35%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.35%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.35%   |
| Intel Ethernet Connection (16) I219-V                             | 3         | 0.35%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.35%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 806       | 50.44%  |
| Ethernet | 774       | 48.44%  |
| Modem    | 16        | 1%      |
| Unknown  | 2         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 649       | 63.19%  |
| Ethernet | 378       | 36.81%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 518       | 53.57%  |
| 1     | 412       | 42.61%  |
| 3     | 28        | 2.9%    |
| 0     | 5         | 0.52%   |
| 4     | 4         | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 761       | 77.57%  |
| Yes  | 220       | 22.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 413       | 52.48%  |
| Realtek Semiconductor           | 94        | 11.94%  |
| Qualcomm Atheros Communications | 42        | 5.34%   |
| Cambridge Silicon Radio         | 41        | 5.21%   |
| IMC Networks                    | 31        | 3.94%   |
| Broadcom                        | 29        | 3.68%   |
| Foxconn / Hon Hai               | 25        | 3.18%   |
| Lite-On Technology              | 24        | 3.05%   |
| Apple                           | 19        | 2.41%   |
| ASUSTek Computer                | 17        | 2.16%   |
| MediaTek                        | 12        | 1.52%   |
| Realtek                         | 9         | 1.14%   |
| TP-Link                         | 6         | 0.76%   |
| Toshiba                         | 4         | 0.51%   |
| Dell                            | 4         | 0.51%   |
| Ralink                          | 3         | 0.38%   |
| Marvell Semiconductor           | 3         | 0.38%   |
| USI                             | 2         | 0.25%   |
| Opticis                         | 2         | 0.25%   |
| HTC (High Tech Computer)        | 2         | 0.25%   |
| Hewlett-Packard                 | 2         | 0.25%   |
| Foxconn International           | 1         | 0.13%   |
| Dynex                           | 1         | 0.13%   |
| Alps Electric                   | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 144       | 18.25%  |
| Intel AX200 Bluetooth                               | 85        | 10.77%  |
| Realtek Bluetooth Radio                             | 69        | 8.75%   |
| Intel AX201 Bluetooth                               | 69        | 8.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 42        | 5.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 41        | 5.2%    |
| Intel AX210 Bluetooth                               | 31        | 3.93%   |
| Qualcomm Atheros  Bluetooth Device                  | 28        | 3.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 17        | 2.15%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 1.9%    |
| MediaTek Wireless_Device                            | 12        | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 1.52%   |
| Intel Bluetooth Device                              | 12        | 1.52%   |
| IMC Networks Bluetooth Radio                        | 12        | 1.52%   |
| Apple Bluetooth USB Host Controller                 | 12        | 1.52%   |
| IMC Networks Wireless_Device                        | 11        | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 1.27%   |
| Realtek Bluetooth Radio                             | 9         | 1.14%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 1.14%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 8         | 1.01%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 0.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 7         | 0.89%   |
| TP-Link UB500 Adapter                               | 6         | 0.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 0.63%   |
| Lite-On Bluetooth Device                            | 5         | 0.63%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 0.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 5         | 0.63%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.51%   |
| IMC Networks Bluetooth Device                       | 4         | 0.51%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.51%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.38%   |
| Ralink RT3290 Bluetooth                             | 3         | 0.38%   |
| Marvell Bluetooth and Wireless LAN Composite        | 3         | 0.38%   |
| Lite-On Bluetooth Radio                             | 3         | 0.38%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.38%   |
| ASUS ASUS USB-BT500                                 | 3         | 0.38%   |
| USI Bluetooth Device                                | 2         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 603       | 38.65%  |
| AMD                                             | 386       | 24.74%  |
| Nvidia                                          | 277       | 17.76%  |
| C-Media Electronics                             | 34        | 2.18%   |
| Logitech                                        | 21        | 1.35%   |
| Texas Instruments                               | 17        | 1.09%   |
| SteelSeries ApS                                 | 17        | 1.09%   |
| Kingston Technology                             | 15        | 0.96%   |
| Creative Labs                                   | 11        | 0.71%   |
| JMTek                                           | 10        | 0.64%   |
| Creative Technology                             | 10        | 0.64%   |
| Sony                                            | 8         | 0.51%   |
| Razer USA                                       | 8         | 0.51%   |
| Lenovo                                          | 7         | 0.45%   |
| Corsair                                         | 7         | 0.45%   |
| Blue Microphones                                | 7         | 0.45%   |
| RODE Microphones                                | 6         | 0.38%   |
| Realtek Semiconductor                           | 6         | 0.38%   |
| KORG                                            | 6         | 0.38%   |
| NAD Electronics                                 | 5         | 0.32%   |
| Micro Star International                        | 5         | 0.32%   |
| Generalplus Technology                          | 5         | 0.32%   |
| AKAI                                            | 5         | 0.32%   |
| XMOS                                            | 4         | 0.26%   |
| Valve Software                                  | 4         | 0.26%   |
| Samson Technologies                             | 4         | 0.26%   |
| Focusrite-Novation                              | 4         | 0.26%   |
| Apple                                           | 4         | 0.26%   |
| KTMicro                                         | 3         | 0.19%   |
| GYROCOM C&C                                     | 3         | 0.19%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.13%   |
| Sennheiser Communications                       | 2         | 0.13%   |
| Scarlett                                        | 2         | 0.13%   |
| M-Audio                                         | 2         | 0.13%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.13%   |
| Hewlett-Packard                                 | 2         | 0.13%   |
| Giga-Byte Technology                            | 2         | 0.13%   |
| FiiO Electronics Technology                     | 2         | 0.13%   |
| Elgato Systems                                  | 2         | 0.13%   |
| Cambridge Silicon Radio                         | 2         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 188       | 9.82%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 112       | 5.85%   |
| Intel Sunrise Point-LP HD Audio                                            | 104       | 5.43%   |
| AMD Starship/Matisse HD Audio Controller                                   | 88        | 4.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 47        | 2.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 43        | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 38        | 1.99%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 37        | 1.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 36        | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 36        | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 35        | 1.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 35        | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 30        | 1.57%   |
| Nvidia GP107GL High Definition Audio Controller                            | 28        | 1.46%   |
| Nvidia GA104 High Definition Audio Controller                              | 26        | 1.36%   |
| Intel 8 Series HD Audio Controller                                         | 25        | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 25        | 1.31%   |
| Nvidia TU106 High Definition Audio Controller                              | 24        | 1.25%   |
| Intel Haswell-ULT HD Audio Controller                                      | 24        | 1.25%   |
| Intel Broadwell-U Audio Controller                                         | 23        | 1.2%    |
| Nvidia GP104 High Definition Audio Controller                              | 22        | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 22        | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 22        | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 1.04%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 20        | 1.04%   |
| Nvidia TU116 High Definition Audio Controller                              | 19        | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 18        | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 18        | 0.94%   |
| Intel 200 Series PCH HD Audio                                              | 18        | 0.94%   |
| AMD Navi 10 HDMI Audio                                                     | 18        | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 17        | 0.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 17        | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 15        | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 15        | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 15        | 0.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 15        | 0.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 0.68%   |
| Intel CM238 HD Audio Controller                                            | 13        | 0.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 0.68%   |
| AMD FCH Azalia Controller                                                  | 13        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 224       | 26.08%  |
| SK hynix            | 155       | 18.04%  |
| Micron Technology   | 94        | 10.94%  |
| Kingston            | 74        | 8.61%   |
| Corsair             | 61        | 7.1%    |
| G.Skill             | 59        | 6.87%   |
| Crucial             | 51        | 5.94%   |
| Unknown             | 33        | 3.84%   |
| A-DATA Technology   | 13        | 1.51%   |
| Ramaxel Technology  | 12        | 1.4%    |
| Team                | 11        | 1.28%   |
| Patriot             | 11        | 1.28%   |
| Elpida              | 7         | 0.81%   |
| Unknown             | 7         | 0.81%   |
| Unknown (ABCD)      | 6         | 0.7%    |
| Nanya Technology    | 4         | 0.47%   |
| Kllisre             | 3         | 0.35%   |
| GOODRAM             | 3         | 0.35%   |
| Teikon              | 2         | 0.23%   |
| Shenzhen Mic        | 2         | 0.23%   |
| Hikvision           | 2         | 0.23%   |
| Golden Empire       | 2         | 0.23%   |
| Apacer              | 2         | 0.23%   |
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
| MAXSUN              | 1         | 0.12%   |
| Magnum Tech         | 1         | 0.12%   |
| KLEVV               | 1         | 0.12%   |
| Kingmax             | 1         | 0.12%   |
| Juhor               | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 2.04%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 1.4%    |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 11        | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.07%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.97%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.86%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 8         | 0.86%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.75%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.75%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.75%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.75%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 0.75%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.75%   |
| Unknown                                                          | 7         | 0.75%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 0.64%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 6         | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.64%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.64%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 6         | 0.64%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.64%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 6         | 0.64%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.54%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 5         | 0.54%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.54%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 5         | 0.54%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 4         | 0.43%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.43%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.43%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.43%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.43%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 4         | 0.43%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 4         | 0.43%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 4         | 0.43%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 3         | 0.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 460       | 61.74%  |
| DDR3    | 163       | 21.88%  |
| LPDDR4  | 38        | 5.1%    |
| LPDDR3  | 27        | 3.62%   |
| DDR5    | 16        | 2.15%   |
| DDR2    | 13        | 1.74%   |
| LPDDR5  | 10        | 1.34%   |
| SDRAM   | 9         | 1.21%   |
| Unknown | 8         | 1.07%   |
| DDR     | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 431       | 58.01%  |
| DIMM         | 218       | 29.34%  |
| Row Of Chips | 82        | 11.04%  |
| Chip         | 7         | 0.94%   |
| Unknown      | 3         | 0.4%    |
| RIMM         | 1         | 0.13%   |
| FB-DIMM      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 396       | 49.44%  |
| 4096  | 192       | 23.97%  |
| 16384 | 131       | 16.35%  |
| 2048  | 47        | 5.87%   |
| 32768 | 30        | 3.75%   |
| 1024  | 5         | 0.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 200       | 24.84%  |
| 1600    | 129       | 16.02%  |
| 2667    | 125       | 15.53%  |
| 2400    | 46        | 5.71%   |
| 3600    | 45        | 5.59%   |
| 2133    | 36        | 4.47%   |
| 3266    | 24        | 2.98%   |
| 1333    | 23        | 2.86%   |
| 1867    | 22        | 2.73%   |
| 4800    | 14        | 1.74%   |
| 4267    | 14        | 1.74%   |
| 6400    | 11        | 1.37%   |
| 1334    | 8         | 0.99%   |
| 3733    | 7         | 0.87%   |
| 3533    | 7         | 0.87%   |
| 3866    | 6         | 0.75%   |
| 3400    | 6         | 0.75%   |
| 800     | 6         | 0.75%   |
| 667     | 6         | 0.75%   |
| Unknown | 6         | 0.75%   |
| 3800    | 5         | 0.62%   |
| 3000    | 5         | 0.62%   |
| 1800    | 5         | 0.62%   |
| 4266    | 3         | 0.37%   |
| 2933    | 3         | 0.37%   |
| 2048    | 3         | 0.37%   |
| 1067    | 3         | 0.37%   |
| 1066    | 3         | 0.37%   |
| 6000    | 2         | 0.25%   |
| 3534    | 2         | 0.25%   |
| 3500    | 2         | 0.25%   |
| 3466    | 2         | 0.25%   |
| 2733    | 2         | 0.25%   |
| 2666    | 2         | 0.25%   |
| 1648    | 2         | 0.25%   |
| 65535   | 1         | 0.12%   |
| 49926   | 1         | 0.12%   |
| 5800    | 1         | 0.12%   |
| 4333    | 1         | 0.12%   |
| 4199    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


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

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 132       | 19.3%   |
| IMC Networks                           | 92        | 13.45%  |
| Logitech                               | 59        | 8.63%   |
| Microdia                               | 41        | 5.99%   |
| Bison Electronics                      | 34        | 4.97%   |
| Quanta                                 | 32        | 4.68%   |
| Realtek Semiconductor                  | 31        | 4.53%   |
| Sunplus Innovation Technology          | 29        | 4.24%   |
| Acer                                   | 29        | 4.24%   |
| Cheng Uei Precision Industry (Foxlink) | 28        | 4.09%   |
| Apple                                  | 26        | 3.8%    |
| Syntek                                 | 25        | 3.65%   |
| Lite-On Technology                     | 21        | 3.07%   |
| Luxvisions Innotech Limited            | 12        | 1.75%   |
| Microsoft                              | 8         | 1.17%   |
| Suyin                                  | 6         | 0.88%   |
| Sonix Technology                       | 6         | 0.88%   |
| Samsung Electronics                    | 5         | 0.73%   |
| Valve Software                         | 4         | 0.58%   |
| Silicon Motion                         | 4         | 0.58%   |
| MacroSilicon                           | 4         | 0.58%   |
| Lenovo                                 | 4         | 0.58%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.44%   |
| Primax Electronics                     | 3         | 0.44%   |
| Hewlett-Packard                        | 3         | 0.44%   |
| Google                                 | 3         | 0.44%   |
| GEMBIRD                                | 3         | 0.44%   |
| Alcor Micro                            | 3         | 0.44%   |
| Sunplus IT                             | 2         | 0.29%   |
| Ricoh                                  | 2         | 0.29%   |
| KYE Systems (Mouse Systems)            | 2         | 0.29%   |
| Intel                                  | 2         | 0.29%   |
| Huawei Technologies                    | 2         | 0.29%   |
| Y Media                                | 1         | 0.15%   |
| Xiaomi                                 | 1         | 0.15%   |
| WCM_USB                                | 1         | 0.15%   |
| Trust                                  | 1         | 0.15%   |
| Tripath Technology                     | 1         | 0.15%   |
| Tobii Technology AB                    | 1         | 0.15%   |
| Sony                                   | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 39        | 5.68%   |
| IMC Networks Integrated Camera                   | 36        | 5.24%   |
| IMC Networks USB2.0 HD UVC WebCam                | 33        | 4.8%    |
| Chicony HD WebCam                                | 17        | 2.47%   |
| Syntek Integrated Camera                         | 16        | 2.33%   |
| Microdia Integrated_Webcam_HD                    | 13        | 1.89%   |
| Logitech HD Pro Webcam C920                      | 12        | 1.75%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 12        | 1.75%   |
| Acer Integrated Camera                           | 12        | 1.75%   |
| Realtek Integrated_Webcam_HD                     | 11        | 1.6%    |
| Logitech Webcam C270                             | 11        | 1.6%    |
| Acer HD Webcam                                   | 11        | 1.6%    |
| Bison Integrated Camera                          | 10        | 1.46%   |
| Apple FaceTime HD Camera (Built-in)              | 9         | 1.31%   |
| Sunplus Integrated_Webcam_HD                     | 8         | 1.16%   |
| Quanta USB2.0 HD UVC WebCam                      | 7         | 1.02%   |
| Logitech C922 Pro Stream Webcam                  | 7         | 1.02%   |
| Lite-On Integrated Camera                        | 7         | 1.02%   |
| Chicony HP Wide Vision HD Camera                 | 7         | 1.02%   |
| Sonix USB2.0 HD UVC WebCam                       | 6         | 0.87%   |
| Microdia Webcam Vitade AF                        | 6         | 0.87%   |
| Microdia Integrated Webcam                       | 6         | 0.87%   |
| Chicony USB2.0 HD UVC WebCam                     | 6         | 0.87%   |
| Chicony HD User Facing                           | 6         | 0.87%   |
| Sunplus HD WebCam                                | 5         | 0.73%   |
| Samsung Galaxy A5 (MTP)                          | 5         | 0.73%   |
| Quanta HP TrueVision HD Camera                   | 5         | 0.73%   |
| Quanta HP HD Camera                              | 5         | 0.73%   |
| IMC Networks ov9734_azurewave_camera             | 5         | 0.73%   |
| Chicony VGA WebCam                               | 5         | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam                    | 5         | 0.73%   |
| Chicony HP TrueVision HD Camera                  | 5         | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 5         | 0.73%   |
| Valve Software 3D Camera                         | 4         | 0.58%   |
| Syntek Lenovo EasyCamera                         | 4         | 0.58%   |
| Syntek EasyCamera                                | 4         | 0.58%   |
| Sunplus Asus Webcam                              | 4         | 0.58%   |
| MacroSilicon USB Video                           | 4         | 0.58%   |
| Logitech HD Webcam C615                          | 4         | 0.58%   |
| Logitech C920 PRO HD Webcam                      | 4         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 48        | 37.5%   |
| Validity Sensors                   | 31        | 24.22%  |
| Shenzhen Goodix Technology         | 22        | 17.19%  |
| Elan Microelectronics              | 14        | 10.94%  |
| LighTuning Technology              | 6         | 4.69%   |
| Upek                               | 3         | 2.34%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.56%   |
| Samsung Electronics                | 1         | 0.78%   |
| AuthenTec                          | 1         | 0.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 8.59%   |
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 8.59%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 8.59%   |
| Elan ELAN:Fingerprint                                                      | 9         | 7.03%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 4.69%   |
| Synaptics WBDI                                                             | 6         | 4.69%   |
| Synaptics  WBDI                                                            | 6         | 4.69%   |
| Synaptics UWP WBDI                                                         | 5         | 3.91%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.91%   |
| Elan ELAN:ARM-M4                                                           | 5         | 3.91%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 3.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.34%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 2.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.56%   |
| Validity Sensors VFS491                                                    | 2         | 1.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.56%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.56%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.56%   |
| Unknown                                                                    | 2         | 1.56%   |
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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 31.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 24.39%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 7.32%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 7.32%   |
| Broadcom 5880                                                                | 3         | 7.32%   |
| Broadcom 58200                                                               | 3         | 7.32%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.88%   |
| HID Global USB Reader V3                                                     | 1         | 2.44%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 2.44%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 675       | 68.39%  |
| 1     | 257       | 26.04%  |
| 2     | 52        | 5.27%   |
| 3     | 2         | 0.2%    |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 128       | 36.47%  |
| Net/ethernet             | 43        | 12.25%  |
| Chipcard                 | 39        | 11.11%  |
| Multimedia controller    | 36        | 10.26%  |
| Graphics card            | 32        | 9.12%   |
| Net/wireless             | 29        | 8.26%   |
| Camera                   | 16        | 4.56%   |
| Bluetooth                | 10        | 2.85%   |
| Network                  | 7         | 1.99%   |
| Unassigned class         | 2         | 0.57%   |
| Storage                  | 2         | 0.57%   |
| Sound                    | 2         | 0.57%   |
| Dvb card                 | 2         | 0.57%   |
| Modem                    | 1         | 0.28%   |
| Communication controller | 1         | 0.28%   |
| Card reader              | 1         | 0.28%   |

