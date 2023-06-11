Linux in Canada - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Canada/Desktop/README.md) and [notebooks](/Location/Canada/Notebook/README.md).

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

Total: 8596

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | F2A85-V PRO                 | Desktop     | [43991c533e](https://linux-hardware.org/?probe=43991c533e) | Jun 10, 2023 |
| MSI           | MS-B9321                    | Desktop     | [a7a878dbe6](https://linux-hardware.org/?probe=a7a878dbe6) | Jun 10, 2023 |
| ASRock        | B550AM Gaming               | Desktop     | [eca79c3bbb](https://linux-hardware.org/?probe=eca79c3bbb) | Jun 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [4c9c3d929b](https://linux-hardware.org/?probe=4c9c3d929b) | Jun 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8e10de95af](https://linux-hardware.org/?probe=8e10de95af) | Jun 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [1a36e2fa98](https://linux-hardware.org/?probe=1a36e2fa98) | Jun 10, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [42722d78d8](https://linux-hardware.org/?probe=42722d78d8) | Jun 10, 2023 |
| Sony          | VPCF120FD                   | Notebook    | [47f02bd498](https://linux-hardware.org/?probe=47f02bd498) | Jun 10, 2023 |
| Lenovo        | 3172 SDK0J40697 WIN 3305... | Mini pc     | [7f437dc929](https://linux-hardware.org/?probe=7f437dc929) | Jun 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0e34d2ee28](https://linux-hardware.org/?probe=0e34d2ee28) | Jun 09, 2023 |
| Sony          | VPCEB2AFD                   | Notebook    | [1d9d6ddd74](https://linux-hardware.org/?probe=1d9d6ddd74) | Jun 09, 2023 |
| Panasonic     | CF-S10CDHEDM                | Notebook    | [19b6085754](https://linux-hardware.org/?probe=19b6085754) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [6e5323aa42](https://linux-hardware.org/?probe=6e5323aa42) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [fc4b07cbb0](https://linux-hardware.org/?probe=fc4b07cbb0) | Jun 09, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [09344fa63e](https://linux-hardware.org/?probe=09344fa63e) | Jun 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8173a6e67f](https://linux-hardware.org/?probe=8173a6e67f) | Jun 08, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [52df878410](https://linux-hardware.org/?probe=52df878410) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [05973f7d9b](https://linux-hardware.org/?probe=05973f7d9b) | Jun 08, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [7775c4c871](https://linux-hardware.org/?probe=7775c4c871) | Jun 07, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [3a43778152](https://linux-hardware.org/?probe=3a43778152) | Jun 07, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [eb3fbddd2c](https://linux-hardware.org/?probe=eb3fbddd2c) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 4282AB9       | Notebook    | [790550e99f](https://linux-hardware.org/?probe=790550e99f) | Jun 06, 2023 |
| HP            | 83E1                        | Desktop     | [227e410c6f](https://linux-hardware.org/?probe=227e410c6f) | Jun 06, 2023 |
| Lenovo        | 30D0 NOK                    | Desktop     | [045b011b7a](https://linux-hardware.org/?probe=045b011b7a) | Jun 06, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [bbbe24d6b6](https://linux-hardware.org/?probe=bbbe24d6b6) | Jun 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9c282e76a6](https://linux-hardware.org/?probe=9c282e76a6) | Jun 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [1c99e1316c](https://linux-hardware.org/?probe=1c99e1316c) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [60fb09bf5e](https://linux-hardware.org/?probe=60fb09bf5e) | Jun 05, 2023 |
| MSI           | B250 GAMING PRO CARBON      | Desktop     | [32da3735d9](https://linux-hardware.org/?probe=32da3735d9) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4592ff63f3](https://linux-hardware.org/?probe=4592ff63f3) | Jun 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [aa2925f22f](https://linux-hardware.org/?probe=aa2925f22f) | Jun 05, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0DR0... | Notebook    | [6fad1535c3](https://linux-hardware.org/?probe=6fad1535c3) | Jun 04, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [fb0c1a4922](https://linux-hardware.org/?probe=fb0c1a4922) | Jun 04, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [a90856c944](https://linux-hardware.org/?probe=a90856c944) | Jun 04, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [3fc6303165](https://linux-hardware.org/?probe=3fc6303165) | Jun 03, 2023 |
| Dell          | Precision 5540              | Notebook    | [f9f2304792](https://linux-hardware.org/?probe=f9f2304792) | Jun 03, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| MSI           | B250 GAMING PRO CARBON      | Desktop     | [ef7acf6baa](https://linux-hardware.org/?probe=ef7acf6baa) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [21b7236d20](https://linux-hardware.org/?probe=21b7236d20) | Jun 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [e28ef4a6b7](https://linux-hardware.org/?probe=e28ef4a6b7) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| ASUSTek       | Maximus Formula             | Desktop     | [6a70fa0a86](https://linux-hardware.org/?probe=6a70fa0a86) | Jun 02, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [d75ea1f93f](https://linux-hardware.org/?probe=d75ea1f93f) | Jun 02, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [047bfb6e8e](https://linux-hardware.org/?probe=047bfb6e8e) | Jun 02, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [becb85a201](https://linux-hardware.org/?probe=becb85a201) | Jun 02, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [7789b12750](https://linux-hardware.org/?probe=7789b12750) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [29c4ba7312](https://linux-hardware.org/?probe=29c4ba7312) | Jun 01, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [57db123250](https://linux-hardware.org/?probe=57db123250) | Jun 01, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [7070e55aa0](https://linux-hardware.org/?probe=7070e55aa0) | Jun 01, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [28eec89b69](https://linux-hardware.org/?probe=28eec89b69) | Jun 01, 2023 |
| Lenovo        | ThinkPad W510 4391B49       | Notebook    | [1e1004a387](https://linux-hardware.org/?probe=1e1004a387) | Jun 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a28272d6e](https://linux-hardware.org/?probe=9a28272d6e) | Jun 01, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [b3eed1356b](https://linux-hardware.org/?probe=b3eed1356b) | Jun 01, 2023 |
| Dell          | Latitude E5540              | Notebook    | [83d7c0065d](https://linux-hardware.org/?probe=83d7c0065d) | Jun 01, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [8bc281486e](https://linux-hardware.org/?probe=8bc281486e) | May 31, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3b9639141c](https://linux-hardware.org/?probe=3b9639141c) | May 31, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [32a85827df](https://linux-hardware.org/?probe=32a85827df) | May 31, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [e45b1707bd](https://linux-hardware.org/?probe=e45b1707bd) | May 31, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [0b958e0c5c](https://linux-hardware.org/?probe=0b958e0c5c) | May 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [cffbd92b9f](https://linux-hardware.org/?probe=cffbd92b9f) | May 31, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [4a3e8c4d6f](https://linux-hardware.org/?probe=4a3e8c4d6f) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [698e3b5e35](https://linux-hardware.org/?probe=698e3b5e35) | May 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [399cce0d30](https://linux-hardware.org/?probe=399cce0d30) | May 30, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [67c96085bf](https://linux-hardware.org/?probe=67c96085bf) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [1793fc9d72](https://linux-hardware.org/?probe=1793fc9d72) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [94fda2dea0](https://linux-hardware.org/?probe=94fda2dea0) | May 30, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c98400b6eb](https://linux-hardware.org/?probe=c98400b6eb) | May 30, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [98e2096ab6](https://linux-hardware.org/?probe=98e2096ab6) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | Notebook    | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [26f783c383](https://linux-hardware.org/?probe=26f783c383) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [531455206b](https://linux-hardware.org/?probe=531455206b) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8b1445b47c](https://linux-hardware.org/?probe=8b1445b47c) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [06318d2354](https://linux-hardware.org/?probe=06318d2354) | May 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [a47a934500](https://linux-hardware.org/?probe=a47a934500) | May 29, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [c24eb2f7dd](https://linux-hardware.org/?probe=c24eb2f7dd) | May 29, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [52517395ca](https://linux-hardware.org/?probe=52517395ca) | May 29, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [6dc6a9d6f5](https://linux-hardware.org/?probe=6dc6a9d6f5) | May 29, 2023 |
| Lenovo        | ThinkCentre M58p 6137AU8    | Desktop     | [bd80dea70f](https://linux-hardware.org/?probe=bd80dea70f) | May 29, 2023 |
| Lenovo        | ThinkPad T420 4236N79       | Notebook    | [9908724093](https://linux-hardware.org/?probe=9908724093) | May 28, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [8bdf6722e2](https://linux-hardware.org/?probe=8bdf6722e2) | May 28, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [22cbc01649](https://linux-hardware.org/?probe=22cbc01649) | May 28, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [993b013d0a](https://linux-hardware.org/?probe=993b013d0a) | May 28, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e38da09f](https://linux-hardware.org/?probe=e2e38da09f) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| Dell          | Latitude E6330              | Notebook    | [dd302db25c](https://linux-hardware.org/?probe=dd302db25c) | May 27, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [741e0e805b](https://linux-hardware.org/?probe=741e0e805b) | May 27, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [b2672eb1db](https://linux-hardware.org/?probe=b2672eb1db) | May 27, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [906e585809](https://linux-hardware.org/?probe=906e585809) | May 27, 2023 |
| Dell          | Latitude E6330              | Notebook    | [f93b318d71](https://linux-hardware.org/?probe=f93b318d71) | May 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [f1b7ea69ea](https://linux-hardware.org/?probe=f1b7ea69ea) | May 27, 2023 |
| Lenovo        | Unknown                     | Notebook    | [dbf5c576b2](https://linux-hardware.org/?probe=dbf5c576b2) | May 27, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [33eb5df96b](https://linux-hardware.org/?probe=33eb5df96b) | May 26, 2023 |
| Samsung       | 910S3G/910S3T               | Notebook    | [e041a5365e](https://linux-hardware.org/?probe=e041a5365e) | May 26, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [d229a8eb01](https://linux-hardware.org/?probe=d229a8eb01) | May 26, 2023 |
| Dell          | 0K095G A02                  | Desktop     | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [5b0dffc2c3](https://linux-hardware.org/?probe=5b0dffc2c3) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| Acer          | Aspire M3910                | Desktop     | [f4dedc13f9](https://linux-hardware.org/?probe=f4dedc13f9) | May 25, 2023 |
| Acer          | Aspire V3-551               | Notebook    | [316db578fe](https://linux-hardware.org/?probe=316db578fe) | May 25, 2023 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [b00cde0e71](https://linux-hardware.org/?probe=b00cde0e71) | May 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [84756c6406](https://linux-hardware.org/?probe=84756c6406) | May 25, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [52e1964d2c](https://linux-hardware.org/?probe=52e1964d2c) | May 25, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [3a85770148](https://linux-hardware.org/?probe=3a85770148) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [9294d16ea5](https://linux-hardware.org/?probe=9294d16ea5) | May 25, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [1523787171](https://linux-hardware.org/?probe=1523787171) | May 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [89d040ffaf](https://linux-hardware.org/?probe=89d040ffaf) | May 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [0a2dc161fe](https://linux-hardware.org/?probe=0a2dc161fe) | May 24, 2023 |
| Alienware     | 17 R3                       | Notebook    | [a567b379a1](https://linux-hardware.org/?probe=a567b379a1) | May 24, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d99af6bab2](https://linux-hardware.org/?probe=d99af6bab2) | May 24, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [deff44e62e](https://linux-hardware.org/?probe=deff44e62e) | May 24, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [48bd340a09](https://linux-hardware.org/?probe=48bd340a09) | May 24, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ed936908c9](https://linux-hardware.org/?probe=ed936908c9) | May 23, 2023 |
| HP            | 81B3                        | Desktop     | [6b35d06402](https://linux-hardware.org/?probe=6b35d06402) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a605d12e2d](https://linux-hardware.org/?probe=a605d12e2d) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a1770c45b0](https://linux-hardware.org/?probe=a1770c45b0) | May 23, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [35a7542634](https://linux-hardware.org/?probe=35a7542634) | May 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [12a444a75a](https://linux-hardware.org/?probe=12a444a75a) | May 23, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [241bd90f1f](https://linux-hardware.org/?probe=241bd90f1f) | May 23, 2023 |
| Lenovo        | ThinkPad T540p 20BF001NU... | Notebook    | [2a770d2eac](https://linux-hardware.org/?probe=2a770d2eac) | May 23, 2023 |
| HP            | 0AECh D                     | Desktop     | [06f56df636](https://linux-hardware.org/?probe=06f56df636) | May 23, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [719fbbd5a5](https://linux-hardware.org/?probe=719fbbd5a5) | May 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [aa33ddd283](https://linux-hardware.org/?probe=aa33ddd283) | May 23, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [7978c97691](https://linux-hardware.org/?probe=7978c97691) | May 22, 2023 |
| Lenovo        | ThinkPad T490 20N3S4VV00    | Notebook    | [5c190a4d57](https://linux-hardware.org/?probe=5c190a4d57) | May 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0f9deafb62](https://linux-hardware.org/?probe=0f9deafb62) | May 22, 2023 |
| HP            | 18E4                        | Desktop     | [5601900c8b](https://linux-hardware.org/?probe=5601900c8b) | May 22, 2023 |
| Unknown       | DT138IB                     | Desktop     | [130e17f9e3](https://linux-hardware.org/?probe=130e17f9e3) | May 21, 2023 |
| Sony          | VPCF120FD                   | Notebook    | [a438459d06](https://linux-hardware.org/?probe=a438459d06) | May 21, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [1c5c9709dd](https://linux-hardware.org/?probe=1c5c9709dd) | May 21, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Dell          | 0YP9G7 A00                  | Desktop     | [18853bc139](https://linux-hardware.org/?probe=18853bc139) | May 21, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [7815f47a45](https://linux-hardware.org/?probe=7815f47a45) | May 21, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [867806192a](https://linux-hardware.org/?probe=867806192a) | May 21, 2023 |
| Dell          | 0H28RR A07                  | Server      | [1dd21b89e9](https://linux-hardware.org/?probe=1dd21b89e9) | May 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [298317e388](https://linux-hardware.org/?probe=298317e388) | May 21, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [a3a157f327](https://linux-hardware.org/?probe=a3a157f327) | May 21, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [b60db9bc14](https://linux-hardware.org/?probe=b60db9bc14) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [5ae19394fc](https://linux-hardware.org/?probe=5ae19394fc) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [14548bc77a](https://linux-hardware.org/?probe=14548bc77a) | May 20, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b07192ce16](https://linux-hardware.org/?probe=b07192ce16) | May 19, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [e168b46b94](https://linux-hardware.org/?probe=e168b46b94) | May 19, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b001b01a08](https://linux-hardware.org/?probe=b001b01a08) | May 19, 2023 |
| BOSGAME       | B95                         | Notebook    | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| HP            | HDX18                       | Notebook    | [fbfe87f9b5](https://linux-hardware.org/?probe=fbfe87f9b5) | May 19, 2023 |
| HP            | HDX18                       | Notebook    | [a0d050763b](https://linux-hardware.org/?probe=a0d050763b) | May 19, 2023 |
| MSI           | MS-B9311                    | Desktop     | [3cfc1fbb83](https://linux-hardware.org/?probe=3cfc1fbb83) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| HP            | 18E9                        | Desktop     | [2128541eb5](https://linux-hardware.org/?probe=2128541eb5) | May 18, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [e0ebac1371](https://linux-hardware.org/?probe=e0ebac1371) | May 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [a33efd912c](https://linux-hardware.org/?probe=a33efd912c) | May 18, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [85da02478a](https://linux-hardware.org/?probe=85da02478a) | May 17, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [d98feea8ad](https://linux-hardware.org/?probe=d98feea8ad) | May 17, 2023 |
| Acer          | Swift SF316-51              | Notebook    | [663e7fe745](https://linux-hardware.org/?probe=663e7fe745) | May 17, 2023 |
| ASUSTek       | D700SC                      | Desktop     | [eab212a67d](https://linux-hardware.org/?probe=eab212a67d) | May 17, 2023 |
| ASRock        | Z97 Professional            | Desktop     | [7d0ecd3359](https://linux-hardware.org/?probe=7d0ecd3359) | May 17, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [aa87f447d5](https://linux-hardware.org/?probe=aa87f447d5) | May 16, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [c7c487333a](https://linux-hardware.org/?probe=c7c487333a) | May 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [afbef25815](https://linux-hardware.org/?probe=afbef25815) | May 16, 2023 |
| Dell          | Precision 5540              | Notebook    | [a97a05dd0e](https://linux-hardware.org/?probe=a97a05dd0e) | May 16, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [a399b17822](https://linux-hardware.org/?probe=a399b17822) | May 16, 2023 |
| HP            | 18E4                        | Desktop     | [7560196205](https://linux-hardware.org/?probe=7560196205) | May 16, 2023 |
| MSI           | 3664h                       | Desktop     | [b45eee9c3a](https://linux-hardware.org/?probe=b45eee9c3a) | May 16, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [aeb8c0e04f](https://linux-hardware.org/?probe=aeb8c0e04f) | May 16, 2023 |
| Supermicro    | H12DSU-iN                   | Desktop     | [05b2b86f35](https://linux-hardware.org/?probe=05b2b86f35) | May 15, 2023 |
| HP            | 18E9                        | Desktop     | [59a47f84ec](https://linux-hardware.org/?probe=59a47f84ec) | May 15, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [4b60a3d942](https://linux-hardware.org/?probe=4b60a3d942) | May 15, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [5c97b405b5](https://linux-hardware.org/?probe=5c97b405b5) | May 15, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [465488c540](https://linux-hardware.org/?probe=465488c540) | May 15, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [a431f34e2b](https://linux-hardware.org/?probe=a431f34e2b) | May 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [a2c1fd19aa](https://linux-hardware.org/?probe=a2c1fd19aa) | May 14, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [2ab0709f22](https://linux-hardware.org/?probe=2ab0709f22) | May 14, 2023 |
| Acer          | Aspire Z3-705               | All in one  | [1198d368c9](https://linux-hardware.org/?probe=1198d368c9) | May 14, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [7380a83f05](https://linux-hardware.org/?probe=7380a83f05) | May 14, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [1f657b2f59](https://linux-hardware.org/?probe=1f657b2f59) | May 14, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [0f70383aab](https://linux-hardware.org/?probe=0f70383aab) | May 14, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [760b21cf70](https://linux-hardware.org/?probe=760b21cf70) | May 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [413d3b7b92](https://linux-hardware.org/?probe=413d3b7b92) | May 14, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [784de41090](https://linux-hardware.org/?probe=784de41090) | May 14, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e3dedcbd6a](https://linux-hardware.org/?probe=e3dedcbd6a) | May 14, 2023 |
| Dell          | Precision 5540              | Notebook    | [22e1b4dbd4](https://linux-hardware.org/?probe=22e1b4dbd4) | May 14, 2023 |
| Dell          | Latitude 5490               | Notebook    | [57e94dd4b7](https://linux-hardware.org/?probe=57e94dd4b7) | May 14, 2023 |
| HP            | 18E4                        | Desktop     | [4dc91feab7](https://linux-hardware.org/?probe=4dc91feab7) | May 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [59a9ba6e16](https://linux-hardware.org/?probe=59a9ba6e16) | May 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [5ce272e9ee](https://linux-hardware.org/?probe=5ce272e9ee) | May 13, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a69d13961](https://linux-hardware.org/?probe=2a69d13961) | May 13, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [79db0c9b3c](https://linux-hardware.org/?probe=79db0c9b3c) | May 13, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [71f1904bc6](https://linux-hardware.org/?probe=71f1904bc6) | May 13, 2023 |
| Google        | Kled                        | Notebook    | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| Panasonic     | CF-19-8                     | Notebook    | [1aa7d4071a](https://linux-hardware.org/?probe=1aa7d4071a) | May 12, 2023 |
| System76      | Gazelle                     | Notebook    | [83ef9e6d2d](https://linux-hardware.org/?probe=83ef9e6d2d) | May 12, 2023 |
| Samsung       | R430/R480                   | Notebook    | [076f13d198](https://linux-hardware.org/?probe=076f13d198) | May 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [208afe074a](https://linux-hardware.org/?probe=208afe074a) | May 12, 2023 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [0953c12312](https://linux-hardware.org/?probe=0953c12312) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c590339049](https://linux-hardware.org/?probe=c590339049) | May 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [9d7e434968](https://linux-hardware.org/?probe=9d7e434968) | May 12, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [f9a67e4a1f](https://linux-hardware.org/?probe=f9a67e4a1f) | May 11, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [18a4110763](https://linux-hardware.org/?probe=18a4110763) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0ae43bcc58](https://linux-hardware.org/?probe=0ae43bcc58) | May 11, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [96310a4cfe](https://linux-hardware.org/?probe=96310a4cfe) | May 11, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [ed6a0c4e82](https://linux-hardware.org/?probe=ed6a0c4e82) | May 11, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1e4f2a0daf](https://linux-hardware.org/?probe=1e4f2a0daf) | May 10, 2023 |
| HP            | Laptop 17-by2xxx            | Notebook    | [21faeddba9](https://linux-hardware.org/?probe=21faeddba9) | May 10, 2023 |
| Dell          | 0YTPH7 A01                  | All in one  | [e84bcda5c6](https://linux-hardware.org/?probe=e84bcda5c6) | May 10, 2023 |
| Google        | Edgar                       | Notebook    | [372d5c177f](https://linux-hardware.org/?probe=372d5c177f) | May 10, 2023 |
| HP            | 18E4                        | Desktop     | [2a528dc758](https://linux-hardware.org/?probe=2a528dc758) | May 10, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [deecc1260f](https://linux-hardware.org/?probe=deecc1260f) | May 10, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [3a9528f661](https://linux-hardware.org/?probe=3a9528f661) | May 10, 2023 |
| ASRock        | Z97 Extreme4                | Desktop     | [5803f15c1d](https://linux-hardware.org/?probe=5803f15c1d) | May 09, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [baa9914fa3](https://linux-hardware.org/?probe=baa9914fa3) | May 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [64bd100bb5](https://linux-hardware.org/?probe=64bd100bb5) | May 09, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [f173eb5463](https://linux-hardware.org/?probe=f173eb5463) | May 09, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [9726453f00](https://linux-hardware.org/?probe=9726453f00) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [47fea42b65](https://linux-hardware.org/?probe=47fea42b65) | May 09, 2023 |
| Acer          | Aspire TC-1760              | Desktop     | [24664f3383](https://linux-hardware.org/?probe=24664f3383) | May 09, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [eb9f5de2f5](https://linux-hardware.org/?probe=eb9f5de2f5) | May 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [8cc543c6af](https://linux-hardware.org/?probe=8cc543c6af) | May 09, 2023 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [0971c53d86](https://linux-hardware.org/?probe=0971c53d86) | May 09, 2023 |
| HP            | Laptop 15                   | Notebook    | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [c40e865226](https://linux-hardware.org/?probe=c40e865226) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d055c2e022](https://linux-hardware.org/?probe=d055c2e022) | May 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [28a1f44a1e](https://linux-hardware.org/?probe=28a1f44a1e) | May 08, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [baf643f95f](https://linux-hardware.org/?probe=baf643f95f) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [6bc581f37c](https://linux-hardware.org/?probe=6bc581f37c) | May 08, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [69dfa20c09](https://linux-hardware.org/?probe=69dfa20c09) | May 07, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d58e08c9ab](https://linux-hardware.org/?probe=d58e08c9ab) | May 07, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [d5f70fc2eb](https://linux-hardware.org/?probe=d5f70fc2eb) | May 07, 2023 |
| Datto         | SSD                         | Desktop     | [c086218bd4](https://linux-hardware.org/?probe=c086218bd4) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [8c5b603452](https://linux-hardware.org/?probe=8c5b603452) | May 07, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [33b7a6ba7c](https://linux-hardware.org/?probe=33b7a6ba7c) | May 06, 2023 |
| HP            | ENVY TS 17                  | Notebook    | [d18f9c3e77](https://linux-hardware.org/?probe=d18f9c3e77) | May 06, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [ebafddb3f1](https://linux-hardware.org/?probe=ebafddb3f1) | May 06, 2023 |
| Alienware     | 0R3FWM A00                  | Desktop     | [c6dbe0270a](https://linux-hardware.org/?probe=c6dbe0270a) | May 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1143344e93](https://linux-hardware.org/?probe=1143344e93) | May 06, 2023 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [d572509eb2](https://linux-hardware.org/?probe=d572509eb2) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [620d5955bb](https://linux-hardware.org/?probe=620d5955bb) | May 06, 2023 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | Notebook    | [21ef45e81c](https://linux-hardware.org/?probe=21ef45e81c) | May 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [308afd60ea](https://linux-hardware.org/?probe=308afd60ea) | May 06, 2023 |
| GPD           | G1618-04                    | All in one  | [1ac75759ce](https://linux-hardware.org/?probe=1ac75759ce) | May 06, 2023 |
| ASRock        | Z97 Extreme4                | Desktop     | [7b83def3e1](https://linux-hardware.org/?probe=7b83def3e1) | May 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [2f59970cf9](https://linux-hardware.org/?probe=2f59970cf9) | May 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f0bc6ca2dd](https://linux-hardware.org/?probe=f0bc6ca2dd) | May 05, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0da080327f](https://linux-hardware.org/?probe=0da080327f) | May 05, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [6ea350c49d](https://linux-hardware.org/?probe=6ea350c49d) | May 05, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [f688c82ff2](https://linux-hardware.org/?probe=f688c82ff2) | May 05, 2023 |
| Dell          | Latitude 5401               | Notebook    | [671e11d184](https://linux-hardware.org/?probe=671e11d184) | May 05, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [72336867ab](https://linux-hardware.org/?probe=72336867ab) | May 04, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [44c5b43b8d](https://linux-hardware.org/?probe=44c5b43b8d) | May 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e49682836a](https://linux-hardware.org/?probe=e49682836a) | May 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [424f0dca9d](https://linux-hardware.org/?probe=424f0dca9d) | May 04, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [1c26fc22d1](https://linux-hardware.org/?probe=1c26fc22d1) | May 04, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [6a70490cd6](https://linux-hardware.org/?probe=6a70490cd6) | May 03, 2023 |
| HP            | 18E4                        | Desktop     | [d1344e36dd](https://linux-hardware.org/?probe=d1344e36dd) | May 03, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [f677ec7e51](https://linux-hardware.org/?probe=f677ec7e51) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [ee72f0090b](https://linux-hardware.org/?probe=ee72f0090b) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [6d2d5b74d2](https://linux-hardware.org/?probe=6d2d5b74d2) | May 03, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [7beeddc27c](https://linux-hardware.org/?probe=7beeddc27c) | May 03, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| HP            | 198E                        | Desktop     | [9c02a85763](https://linux-hardware.org/?probe=9c02a85763) | May 02, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [6f015f949c](https://linux-hardware.org/?probe=6f015f949c) | May 02, 2023 |
| Dell          | 0D735T A00                  | Desktop     | [3070f4e7da](https://linux-hardware.org/?probe=3070f4e7da) | May 02, 2023 |
| Google        | Kip                         | Notebook    | [19b726ec68](https://linux-hardware.org/?probe=19b726ec68) | May 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [9cee4296b5](https://linux-hardware.org/?probe=9cee4296b5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [a9406a1851](https://linux-hardware.org/?probe=a9406a1851) | May 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2849b9a200](https://linux-hardware.org/?probe=2849b9a200) | May 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [1362f2e3df](https://linux-hardware.org/?probe=1362f2e3df) | May 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ecc18e59bc](https://linux-hardware.org/?probe=ecc18e59bc) | May 01, 2023 |
| HP            | 3031h                       | Desktop     | [84140549cd](https://linux-hardware.org/?probe=84140549cd) | May 01, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [5c00e2d415](https://linux-hardware.org/?probe=5c00e2d415) | May 01, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [b293ade39d](https://linux-hardware.org/?probe=b293ade39d) | May 01, 2023 |
| Lenovo        | ThinkCentre M71e 5033A1U    | Desktop     | [2e39bbf0cf](https://linux-hardware.org/?probe=2e39bbf0cf) | May 01, 2023 |
| HP            | 3033h                       | Desktop     | [31a4e00c60](https://linux-hardware.org/?probe=31a4e00c60) | May 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [5b8daf89b4](https://linux-hardware.org/?probe=5b8daf89b4) | May 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [0f39841ca1](https://linux-hardware.org/?probe=0f39841ca1) | May 01, 2023 |
| HP            | 3648h                       | Desktop     | [38ab69c4e2](https://linux-hardware.org/?probe=38ab69c4e2) | May 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [1605338d8f](https://linux-hardware.org/?probe=1605338d8f) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [e89da96576](https://linux-hardware.org/?probe=e89da96576) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0aa06876c7](https://linux-hardware.org/?probe=0aa06876c7) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Alienware     | m17 R5 AMD                  | Notebook    | [4e665db2b1](https://linux-hardware.org/?probe=4e665db2b1) | May 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [45dad4b8e9](https://linux-hardware.org/?probe=45dad4b8e9) | May 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [34e7df2c84](https://linux-hardware.org/?probe=34e7df2c84) | May 01, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [457abef5d3](https://linux-hardware.org/?probe=457abef5d3) | May 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2a2bf698ed](https://linux-hardware.org/?probe=2a2bf698ed) | May 01, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [a3c89effff](https://linux-hardware.org/?probe=a3c89effff) | May 01, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [1f1cb63edc](https://linux-hardware.org/?probe=1f1cb63edc) | May 01, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [1298b74530](https://linux-hardware.org/?probe=1298b74530) | Apr 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [3695c070f9](https://linux-hardware.org/?probe=3695c070f9) | Apr 30, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [f1db72cddb](https://linux-hardware.org/?probe=f1db72cddb) | Apr 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f46e9f6ba7](https://linux-hardware.org/?probe=f46e9f6ba7) | Apr 30, 2023 |
| HP            | 828A                        | Desktop     | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [a5fbe31c54](https://linux-hardware.org/?probe=a5fbe31c54) | Apr 30, 2023 |
| HP            | 18E4                        | Desktop     | [da858ea464](https://linux-hardware.org/?probe=da858ea464) | Apr 30, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e59a8bf7d1](https://linux-hardware.org/?probe=e59a8bf7d1) | Apr 30, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [c2e2e1d130](https://linux-hardware.org/?probe=c2e2e1d130) | Apr 30, 2023 |
| Acer          | Aspire Z5600                | All in one  | [8a9edf5a44](https://linux-hardware.org/?probe=8a9edf5a44) | Apr 29, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | Notebook    | [2545d9dd31](https://linux-hardware.org/?probe=2545d9dd31) | Apr 29, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [1d00cc1f78](https://linux-hardware.org/?probe=1d00cc1f78) | Apr 29, 2023 |
| Lenovo        | XXXX 3000 H210              | Desktop     | [96644846f5](https://linux-hardware.org/?probe=96644846f5) | Apr 29, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [9a9fdf0dd3](https://linux-hardware.org/?probe=9a9fdf0dd3) | Apr 29, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [59b9a9ceb3](https://linux-hardware.org/?probe=59b9a9ceb3) | Apr 29, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [033718212c](https://linux-hardware.org/?probe=033718212c) | Apr 28, 2023 |
| HP            | G62                         | Notebook    | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| ASUSTek       | N550JX                      | Notebook    | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| HP            | Pavilion dv7                | Notebook    | [346cbe0e48](https://linux-hardware.org/?probe=346cbe0e48) | Apr 28, 2023 |
| HP            | Pavilion dv7                | Notebook    | [afafdbce36](https://linux-hardware.org/?probe=afafdbce36) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f1679a62d0](https://linux-hardware.org/?probe=f1679a62d0) | Apr 28, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3342a295e8](https://linux-hardware.org/?probe=3342a295e8) | Apr 28, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [38c117ee87](https://linux-hardware.org/?probe=38c117ee87) | Apr 28, 2023 |
| ASRock        | H170A-X1                    | Desktop     | [a89448e417](https://linux-hardware.org/?probe=a89448e417) | Apr 28, 2023 |
| Dell          | 0XNNCJ A03                  | Server      | [ad555bfde2](https://linux-hardware.org/?probe=ad555bfde2) | Apr 27, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [49033dd76c](https://linux-hardware.org/?probe=49033dd76c) | Apr 27, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [ce35b62e32](https://linux-hardware.org/?probe=ce35b62e32) | Apr 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9fdfb825c7](https://linux-hardware.org/?probe=9fdfb825c7) | Apr 27, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [f3b21405ff](https://linux-hardware.org/?probe=f3b21405ff) | Apr 27, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [4363ca582a](https://linux-hardware.org/?probe=4363ca582a) | Apr 26, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [f5de49d5b3](https://linux-hardware.org/?probe=f5de49d5b3) | Apr 26, 2023 |
| HP            | 8309                        | Desktop     | [cde28bd710](https://linux-hardware.org/?probe=cde28bd710) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [96006a1098](https://linux-hardware.org/?probe=96006a1098) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [a3df65a55c](https://linux-hardware.org/?probe=a3df65a55c) | Apr 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b24f39801d](https://linux-hardware.org/?probe=b24f39801d) | Apr 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| Acer          | Swift SF313-53              | Notebook    | [b487229ea2](https://linux-hardware.org/?probe=b487229ea2) | Apr 25, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7967ed6e8f](https://linux-hardware.org/?probe=7967ed6e8f) | Apr 25, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [c897ecd954](https://linux-hardware.org/?probe=c897ecd954) | Apr 25, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e8318168c4](https://linux-hardware.org/?probe=e8318168c4) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [cc14ce03b0](https://linux-hardware.org/?probe=cc14ce03b0) | Apr 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f878b7d23a](https://linux-hardware.org/?probe=f878b7d23a) | Apr 25, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [135216cc27](https://linux-hardware.org/?probe=135216cc27) | Apr 25, 2023 |
| Acer          | Spin SP513-52N              | Convertible | [bdab97deeb](https://linux-hardware.org/?probe=bdab97deeb) | Apr 25, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [0cfe2b34f5](https://linux-hardware.org/?probe=0cfe2b34f5) | Apr 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [d9ad034d8c](https://linux-hardware.org/?probe=d9ad034d8c) | Apr 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b72361ca9e](https://linux-hardware.org/?probe=b72361ca9e) | Apr 24, 2023 |
| Alienware     | 13 R2                       | Notebook    | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [6531aafbfe](https://linux-hardware.org/?probe=6531aafbfe) | Apr 24, 2023 |
| Acer          | Aspire V5-552P              | Notebook    | [28c276f9da](https://linux-hardware.org/?probe=28c276f9da) | Apr 23, 2023 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [06859fe586](https://linux-hardware.org/?probe=06859fe586) | Apr 23, 2023 |
| HP            | Pavilion dv7                | Notebook    | [0ca422761e](https://linux-hardware.org/?probe=0ca422761e) | Apr 23, 2023 |
| HP            | Pavilion dv7                | Notebook    | [8b90982317](https://linux-hardware.org/?probe=8b90982317) | Apr 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [db614f561e](https://linux-hardware.org/?probe=db614f561e) | Apr 23, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [3321ccb912](https://linux-hardware.org/?probe=3321ccb912) | Apr 23, 2023 |
| Google        | Kefka                       | Notebook    | [2802d83837](https://linux-hardware.org/?probe=2802d83837) | Apr 23, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [cd11cc0e25](https://linux-hardware.org/?probe=cd11cc0e25) | Apr 23, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [acb9cde3d7](https://linux-hardware.org/?probe=acb9cde3d7) | Apr 23, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [9a0f95336c](https://linux-hardware.org/?probe=9a0f95336c) | Apr 23, 2023 |
| ASUSTek       | P8H77-I                     | Desktop     | [e2276c080b](https://linux-hardware.org/?probe=e2276c080b) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [ea9dd842c0](https://linux-hardware.org/?probe=ea9dd842c0) | Apr 22, 2023 |
| ASUSTek       | Zenbook UP6502ZD_UP6502Z... | Convertible | [9cd180c75a](https://linux-hardware.org/?probe=9cd180c75a) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [63599179ae](https://linux-hardware.org/?probe=63599179ae) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | Notebook    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [06bc639254](https://linux-hardware.org/?probe=06bc639254) | Apr 22, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [5eb2235e10](https://linux-hardware.org/?probe=5eb2235e10) | Apr 22, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [cc1233b9b9](https://linux-hardware.org/?probe=cc1233b9b9) | Apr 21, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [15cc4335c7](https://linux-hardware.org/?probe=15cc4335c7) | Apr 21, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [84a6fd49fa](https://linux-hardware.org/?probe=84a6fd49fa) | Apr 21, 2023 |
| HP            | 1905                        | Desktop     | [9e047f751d](https://linux-hardware.org/?probe=9e047f751d) | Apr 21, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [f2f6b7ab4e](https://linux-hardware.org/?probe=f2f6b7ab4e) | Apr 21, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [97eec10e18](https://linux-hardware.org/?probe=97eec10e18) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [f1345bd185](https://linux-hardware.org/?probe=f1345bd185) | Apr 21, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [8e7095e453](https://linux-hardware.org/?probe=8e7095e453) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [44459cbe3a](https://linux-hardware.org/?probe=44459cbe3a) | Apr 20, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6b5cc099a0](https://linux-hardware.org/?probe=6b5cc099a0) | Apr 20, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [1383ab9981](https://linux-hardware.org/?probe=1383ab9981) | Apr 20, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3e1880b375](https://linux-hardware.org/?probe=3e1880b375) | Apr 20, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f83e11ca39](https://linux-hardware.org/?probe=f83e11ca39) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [7310d7f91b](https://linux-hardware.org/?probe=7310d7f91b) | Apr 19, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [cc76c44731](https://linux-hardware.org/?probe=cc76c44731) | Apr 19, 2023 |
| HP            | Pavilion dv7                | Notebook    | [f5c84d7a1b](https://linux-hardware.org/?probe=f5c84d7a1b) | Apr 19, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [86e2d42f73](https://linux-hardware.org/?probe=86e2d42f73) | Apr 19, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [748e08d7c7](https://linux-hardware.org/?probe=748e08d7c7) | Apr 19, 2023 |
| Intel         | DH61AG AAG23736-504         | Desktop     | [9a853b9c86](https://linux-hardware.org/?probe=9a853b9c86) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [1a5add814c](https://linux-hardware.org/?probe=1a5add814c) | Apr 18, 2023 |
| Dell          | Latitude E5550              | Notebook    | [ce824f113c](https://linux-hardware.org/?probe=ce824f113c) | Apr 18, 2023 |
| Dell          | Latitude E5550              | Notebook    | [7611d6e018](https://linux-hardware.org/?probe=7611d6e018) | Apr 18, 2023 |
| Dell          | 0KRC95 A00                  | Desktop     | [99ea2c7790](https://linux-hardware.org/?probe=99ea2c7790) | Apr 18, 2023 |
| Lenovo        | ThinkPad Edge 031946U       | Notebook    | [f9d813509a](https://linux-hardware.org/?probe=f9d813509a) | Apr 18, 2023 |
| Dell          | 0XHYJF A00                  | All in one  | [9348834e54](https://linux-hardware.org/?probe=9348834e54) | Apr 18, 2023 |
| Dell          | 0XHYJF A00                  | All in one  | [c8804b1836](https://linux-hardware.org/?probe=c8804b1836) | Apr 18, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [9539ccfd4d](https://linux-hardware.org/?probe=9539ccfd4d) | Apr 18, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [7b3a68ca48](https://linux-hardware.org/?probe=7b3a68ca48) | Apr 18, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [152e32b151](https://linux-hardware.org/?probe=152e32b151) | Apr 17, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [40b6c3bad6](https://linux-hardware.org/?probe=40b6c3bad6) | Apr 17, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [f8a45caf43](https://linux-hardware.org/?probe=f8a45caf43) | Apr 17, 2023 |
| Biostar       | TA880GU3+                   | Desktop     | [ee629553e7](https://linux-hardware.org/?probe=ee629553e7) | Apr 17, 2023 |
| Biostar       | TA880GU3+                   | Desktop     | [3553ce4185](https://linux-hardware.org/?probe=3553ce4185) | Apr 17, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [6364dbb93a](https://linux-hardware.org/?probe=6364dbb93a) | Apr 16, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [2fd09b6ba5](https://linux-hardware.org/?probe=2fd09b6ba5) | Apr 16, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [5358f67a6d](https://linux-hardware.org/?probe=5358f67a6d) | Apr 16, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [cfc2be8311](https://linux-hardware.org/?probe=cfc2be8311) | Apr 16, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [be0c962cda](https://linux-hardware.org/?probe=be0c962cda) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [afc478cf27](https://linux-hardware.org/?probe=afc478cf27) | Apr 16, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [762ad80f82](https://linux-hardware.org/?probe=762ad80f82) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [3fb8069a1b](https://linux-hardware.org/?probe=3fb8069a1b) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cb21111c89](https://linux-hardware.org/?probe=cb21111c89) | Apr 16, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [35098c2748](https://linux-hardware.org/?probe=35098c2748) | Apr 16, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [872416fe62](https://linux-hardware.org/?probe=872416fe62) | Apr 16, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [c655afe860](https://linux-hardware.org/?probe=c655afe860) | Apr 15, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [f3b7c9c255](https://linux-hardware.org/?probe=f3b7c9c255) | Apr 14, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [d78a3541af](https://linux-hardware.org/?probe=d78a3541af) | Apr 14, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [c7b7e028e4](https://linux-hardware.org/?probe=c7b7e028e4) | Apr 14, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7cf2e649e1](https://linux-hardware.org/?probe=7cf2e649e1) | Apr 14, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [2236248ba0](https://linux-hardware.org/?probe=2236248ba0) | Apr 14, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [d4de10f812](https://linux-hardware.org/?probe=d4de10f812) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7c862e338c](https://linux-hardware.org/?probe=7c862e338c) | Apr 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [03e40fe2cd](https://linux-hardware.org/?probe=03e40fe2cd) | Apr 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [9f723bfac9](https://linux-hardware.org/?probe=9f723bfac9) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [15de4db91b](https://linux-hardware.org/?probe=15de4db91b) | Apr 14, 2023 |
| Dell          | Latitude 3590               | Notebook    | [eed6f4df10](https://linux-hardware.org/?probe=eed6f4df10) | Apr 14, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [df59296148](https://linux-hardware.org/?probe=df59296148) | Apr 13, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [3ac19a6abf](https://linux-hardware.org/?probe=3ac19a6abf) | Apr 13, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [c1f5858d5f](https://linux-hardware.org/?probe=c1f5858d5f) | Apr 13, 2023 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [ae144ff4c8](https://linux-hardware.org/?probe=ae144ff4c8) | Apr 12, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [76595cf176](https://linux-hardware.org/?probe=76595cf176) | Apr 12, 2023 |
| Dell          | 0XD433 A00                  | Desktop     | [e0a30bf441](https://linux-hardware.org/?probe=e0a30bf441) | Apr 12, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [9fbd01e856](https://linux-hardware.org/?probe=9fbd01e856) | Apr 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [9859e63f40](https://linux-hardware.org/?probe=9859e63f40) | Apr 12, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [3bb10a5574](https://linux-hardware.org/?probe=3bb10a5574) | Apr 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f5241c853f](https://linux-hardware.org/?probe=f5241c853f) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a2c9f95f36](https://linux-hardware.org/?probe=a2c9f95f36) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [26358515bc](https://linux-hardware.org/?probe=26358515bc) | Apr 12, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [c8473ad9e5](https://linux-hardware.org/?probe=c8473ad9e5) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [509dbf780c](https://linux-hardware.org/?probe=509dbf780c) | Apr 12, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [0daac07546](https://linux-hardware.org/?probe=0daac07546) | Apr 12, 2023 |
| Gateway       | NE56R                       | Notebook    | [39a33d998b](https://linux-hardware.org/?probe=39a33d998b) | Apr 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9dd9a74143](https://linux-hardware.org/?probe=9dd9a74143) | Apr 12, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [94372e3520](https://linux-hardware.org/?probe=94372e3520) | Apr 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [5c446957c5](https://linux-hardware.org/?probe=5c446957c5) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [14db4e6f1d](https://linux-hardware.org/?probe=14db4e6f1d) | Apr 11, 2023 |
| HP            | Pavilion dv7                | Notebook    | [7cec7666c8](https://linux-hardware.org/?probe=7cec7666c8) | Apr 11, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8eaf410d51](https://linux-hardware.org/?probe=8eaf410d51) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [1627e0654a](https://linux-hardware.org/?probe=1627e0654a) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [57aa7d103d](https://linux-hardware.org/?probe=57aa7d103d) | Apr 11, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e3583c2121](https://linux-hardware.org/?probe=e3583c2121) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d9f95c9169](https://linux-hardware.org/?probe=d9f95c9169) | Apr 11, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [b10bf3690e](https://linux-hardware.org/?probe=b10bf3690e) | Apr 11, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [4b50be64da](https://linux-hardware.org/?probe=4b50be64da) | Apr 11, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [b434d4a0b5](https://linux-hardware.org/?probe=b434d4a0b5) | Apr 11, 2023 |
| HP            | 18E4                        | Desktop     | [54c681affc](https://linux-hardware.org/?probe=54c681affc) | Apr 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e35ed3cb0d](https://linux-hardware.org/?probe=e35ed3cb0d) | Apr 10, 2023 |
| Lenovo        | B575 1450ABU                | Notebook    | [ef58d2e8e6](https://linux-hardware.org/?probe=ef58d2e8e6) | Apr 09, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [e762a4eb1d](https://linux-hardware.org/?probe=e762a4eb1d) | Apr 09, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [fe9976de62](https://linux-hardware.org/?probe=fe9976de62) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [fa54308baa](https://linux-hardware.org/?probe=fa54308baa) | Apr 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3b665833d1](https://linux-hardware.org/?probe=3b665833d1) | Apr 09, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [edbc0b98a4](https://linux-hardware.org/?probe=edbc0b98a4) | Apr 08, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [840f96a7df](https://linux-hardware.org/?probe=840f96a7df) | Apr 08, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [5125228dd1](https://linux-hardware.org/?probe=5125228dd1) | Apr 08, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [cf325779ee](https://linux-hardware.org/?probe=cf325779ee) | Apr 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [08f117749f](https://linux-hardware.org/?probe=08f117749f) | Apr 08, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [5a044a37f7](https://linux-hardware.org/?probe=5a044a37f7) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [81a8d7a1fc](https://linux-hardware.org/?probe=81a8d7a1fc) | Apr 07, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [cd157a6ebf](https://linux-hardware.org/?probe=cd157a6ebf) | Apr 06, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [11edc2be88](https://linux-hardware.org/?probe=11edc2be88) | Apr 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d699519c30](https://linux-hardware.org/?probe=d699519c30) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [ea7a921618](https://linux-hardware.org/?probe=ea7a921618) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [125f93468e](https://linux-hardware.org/?probe=125f93468e) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [fb8ef4b4af](https://linux-hardware.org/?probe=fb8ef4b4af) | Apr 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8b92d25f91](https://linux-hardware.org/?probe=8b92d25f91) | Apr 06, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [a17064a0db](https://linux-hardware.org/?probe=a17064a0db) | Apr 06, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [f1e8cec7f8](https://linux-hardware.org/?probe=f1e8cec7f8) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ca7faa89ba](https://linux-hardware.org/?probe=ca7faa89ba) | Apr 05, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [0d68e199a9](https://linux-hardware.org/?probe=0d68e199a9) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [2c3fa64234](https://linux-hardware.org/?probe=2c3fa64234) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [7dc5bea17c](https://linux-hardware.org/?probe=7dc5bea17c) | Apr 05, 2023 |
| Dell          | Precision 7670              | Notebook    | [b5e95f0d21](https://linux-hardware.org/?probe=b5e95f0d21) | Apr 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b9a5dadc44](https://linux-hardware.org/?probe=b9a5dadc44) | Apr 05, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [4505cd8ddc](https://linux-hardware.org/?probe=4505cd8ddc) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [d8dc8a37b1](https://linux-hardware.org/?probe=d8dc8a37b1) | Apr 04, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [9885a8adee](https://linux-hardware.org/?probe=9885a8adee) | Apr 04, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [056818267b](https://linux-hardware.org/?probe=056818267b) | Apr 04, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [60583d2cb0](https://linux-hardware.org/?probe=60583d2cb0) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a467a04489](https://linux-hardware.org/?probe=a467a04489) | Apr 04, 2023 |
| Pegatron      | Benicia                     | Desktop     | [96ba9b6040](https://linux-hardware.org/?probe=96ba9b6040) | Apr 04, 2023 |
| MSI           | H81M-E34                    | Desktop     | [5e24c6a44a](https://linux-hardware.org/?probe=5e24c6a44a) | Apr 03, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [c674243118](https://linux-hardware.org/?probe=c674243118) | Apr 03, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [dca6973952](https://linux-hardware.org/?probe=dca6973952) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [0b97a5a77a](https://linux-hardware.org/?probe=0b97a5a77a) | Apr 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [7355f06eb3](https://linux-hardware.org/?probe=7355f06eb3) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [734efd13d3](https://linux-hardware.org/?probe=734efd13d3) | Apr 03, 2023 |
| WeiBu         | ADL-N Prod                  | Desktop     | [9b96a245f1](https://linux-hardware.org/?probe=9b96a245f1) | Apr 02, 2023 |
| Lenovo        | ThinkCentre M91p 4518RH1    | Desktop     | [ead0ecfb3a](https://linux-hardware.org/?probe=ead0ecfb3a) | Apr 02, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [25c3fdc9f7](https://linux-hardware.org/?probe=25c3fdc9f7) | Apr 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [fbd686e3e2](https://linux-hardware.org/?probe=fbd686e3e2) | Apr 02, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [e2725a09c9](https://linux-hardware.org/?probe=e2725a09c9) | Apr 02, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [8b4f79808a](https://linux-hardware.org/?probe=8b4f79808a) | Apr 01, 2023 |
| Shenzhen W... | GB1                         | Mini pc     | [ca02164e4d](https://linux-hardware.org/?probe=ca02164e4d) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [dabe76e4ca](https://linux-hardware.org/?probe=dabe76e4ca) | Apr 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [2b25e4872f](https://linux-hardware.org/?probe=2b25e4872f) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [ad3ead1116](https://linux-hardware.org/?probe=ad3ead1116) | Apr 01, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [d6d1ab6c61](https://linux-hardware.org/?probe=d6d1ab6c61) | Apr 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [acb0f81194](https://linux-hardware.org/?probe=acb0f81194) | Apr 01, 2023 |
| ASUSTek       | P8Z77-V PREMIUM             | Desktop     | [d774a892d1](https://linux-hardware.org/?probe=d774a892d1) | Apr 01, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [f05009caac](https://linux-hardware.org/?probe=f05009caac) | Apr 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [a91aee62d3](https://linux-hardware.org/?probe=a91aee62d3) | Apr 01, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [f7c90851ac](https://linux-hardware.org/?probe=f7c90851ac) | Apr 01, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [53717700a1](https://linux-hardware.org/?probe=53717700a1) | Mar 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| ASUSTek       | TS10                        | Desktop     | [054de4f36a](https://linux-hardware.org/?probe=054de4f36a) | Mar 31, 2023 |
| Dell          | XPS M1330                   | Notebook    | [46b9a5cfde](https://linux-hardware.org/?probe=46b9a5cfde) | Mar 31, 2023 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [925759c41c](https://linux-hardware.org/?probe=925759c41c) | Mar 31, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [d729a0a559](https://linux-hardware.org/?probe=d729a0a559) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [5f163f6a24](https://linux-hardware.org/?probe=5f163f6a24) | Mar 31, 2023 |
| ASUSTek       | UN65U                       | Desktop     | [70d0f8f069](https://linux-hardware.org/?probe=70d0f8f069) | Mar 31, 2023 |
| Dell          | Latitude 7490               | Notebook    | [06928c624b](https://linux-hardware.org/?probe=06928c624b) | Mar 31, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f5e2675cdd](https://linux-hardware.org/?probe=f5e2675cdd) | Mar 30, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [41f23ded68](https://linux-hardware.org/?probe=41f23ded68) | Mar 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [4d6ae3ef0f](https://linux-hardware.org/?probe=4d6ae3ef0f) | Mar 30, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [c6cbeeb984](https://linux-hardware.org/?probe=c6cbeeb984) | Mar 30, 2023 |
| Shuttle       | FH270                       | Desktop     | [83c990d212](https://linux-hardware.org/?probe=83c990d212) | Mar 30, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [1e3ec03234](https://linux-hardware.org/?probe=1e3ec03234) | Mar 30, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [fe068bd78d](https://linux-hardware.org/?probe=fe068bd78d) | Mar 30, 2023 |
| MSI           | H81M-E34                    | Desktop     | [ac06c6037f](https://linux-hardware.org/?probe=ac06c6037f) | Mar 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [aaeb2f2269](https://linux-hardware.org/?probe=aaeb2f2269) | Mar 29, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [9a4f4be1ab](https://linux-hardware.org/?probe=9a4f4be1ab) | Mar 29, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [6024b90eea](https://linux-hardware.org/?probe=6024b90eea) | Mar 29, 2023 |
| Intel         | 945GCT-M                    | Desktop     | [d7e65e945e](https://linux-hardware.org/?probe=d7e65e945e) | Mar 29, 2023 |
| ECS           | G31T-M                      | Desktop     | [d6149cbd0d](https://linux-hardware.org/?probe=d6149cbd0d) | Mar 29, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [e27d6594a6](https://linux-hardware.org/?probe=e27d6594a6) | Mar 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [6de889ae8a](https://linux-hardware.org/?probe=6de889ae8a) | Mar 29, 2023 |
| HP            | 0AACh                       | Desktop     | [e313c99b98](https://linux-hardware.org/?probe=e313c99b98) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [19ffc63f56](https://linux-hardware.org/?probe=19ffc63f56) | Mar 28, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [20df1488bd](https://linux-hardware.org/?probe=20df1488bd) | Mar 28, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [999219f420](https://linux-hardware.org/?probe=999219f420) | Mar 28, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [ef684c34bb](https://linux-hardware.org/?probe=ef684c34bb) | Mar 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | All in one  | [fcd01e22d7](https://linux-hardware.org/?probe=fcd01e22d7) | Mar 28, 2023 |
| Dell          | Studio 1558                 | Notebook    | [955946c74d](https://linux-hardware.org/?probe=955946c74d) | Mar 28, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [11cb22743c](https://linux-hardware.org/?probe=11cb22743c) | Mar 27, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [cdb2c38b76](https://linux-hardware.org/?probe=cdb2c38b76) | Mar 27, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [14380327b0](https://linux-hardware.org/?probe=14380327b0) | Mar 27, 2023 |
| HP            | 0AACh                       | Desktop     | [f354a2f03e](https://linux-hardware.org/?probe=f354a2f03e) | Mar 27, 2023 |
| Lenovo        | 36EB SDK0R32862 WIN 3258... | Desktop     | [943075edf7](https://linux-hardware.org/?probe=943075edf7) | Mar 27, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [6f41d8a22c](https://linux-hardware.org/?probe=6f41d8a22c) | Mar 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d96c0cfcd9](https://linux-hardware.org/?probe=d96c0cfcd9) | Mar 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [58ccd5d7e0](https://linux-hardware.org/?probe=58ccd5d7e0) | Mar 27, 2023 |
| Acer          | Aspire M3910                | Desktop     | [8cc87c48d1](https://linux-hardware.org/?probe=8cc87c48d1) | Mar 27, 2023 |
| HP            | 18E4                        | Desktop     | [5d10e73e1d](https://linux-hardware.org/?probe=5d10e73e1d) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b084807397](https://linux-hardware.org/?probe=b084807397) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bc38c5ed22](https://linux-hardware.org/?probe=bc38c5ed22) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [8decb2b6c4](https://linux-hardware.org/?probe=8decb2b6c4) | Mar 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [7dbe4350b5](https://linux-hardware.org/?probe=7dbe4350b5) | Mar 26, 2023 |
| Lenovo        | ThinkPad X220 4290LR3       | Notebook    | [dffa03da18](https://linux-hardware.org/?probe=dffa03da18) | Mar 26, 2023 |
| Lenovo        | ThinkPad T430 4237ZC7       | Notebook    | [845a2ed117](https://linux-hardware.org/?probe=845a2ed117) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [3772f7397b](https://linux-hardware.org/?probe=3772f7397b) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [915cac124b](https://linux-hardware.org/?probe=915cac124b) | Mar 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [da489de02c](https://linux-hardware.org/?probe=da489de02c) | Mar 26, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [20d8516896](https://linux-hardware.org/?probe=20d8516896) | Mar 26, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b9095b98c4](https://linux-hardware.org/?probe=b9095b98c4) | Mar 25, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [513b14ace5](https://linux-hardware.org/?probe=513b14ace5) | Mar 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4f2d3a2402](https://linux-hardware.org/?probe=4f2d3a2402) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [811be842de](https://linux-hardware.org/?probe=811be842de) | Mar 25, 2023 |
| Dell          | 0PU052                      | Desktop     | [ccea2ad8e8](https://linux-hardware.org/?probe=ccea2ad8e8) | Mar 25, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [aeb58a6898](https://linux-hardware.org/?probe=aeb58a6898) | Mar 24, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [fea1e4cf50](https://linux-hardware.org/?probe=fea1e4cf50) | Mar 24, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [b5cecce6b9](https://linux-hardware.org/?probe=b5cecce6b9) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [ded37ac14c](https://linux-hardware.org/?probe=ded37ac14c) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [13046d5580](https://linux-hardware.org/?probe=13046d5580) | Mar 24, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [aeb25bc22b](https://linux-hardware.org/?probe=aeb25bc22b) | Mar 23, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c65fd15277](https://linux-hardware.org/?probe=c65fd15277) | Mar 23, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [7a3319972e](https://linux-hardware.org/?probe=7a3319972e) | Mar 23, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [c91fa425a5](https://linux-hardware.org/?probe=c91fa425a5) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [0c587f1f7f](https://linux-hardware.org/?probe=0c587f1f7f) | Mar 22, 2023 |
| HP            | 339A                        | Desktop     | [a09a5bd5a9](https://linux-hardware.org/?probe=a09a5bd5a9) | Mar 22, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [ebbb5efcbc](https://linux-hardware.org/?probe=ebbb5efcbc) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [90ef1729ef](https://linux-hardware.org/?probe=90ef1729ef) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [48f86bde7c](https://linux-hardware.org/?probe=48f86bde7c) | Mar 22, 2023 |
| Biostar       | TZ77A                       | Desktop     | [9484c73494](https://linux-hardware.org/?probe=9484c73494) | Mar 21, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [7165e2c0d0](https://linux-hardware.org/?probe=7165e2c0d0) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [87bce00c67](https://linux-hardware.org/?probe=87bce00c67) | Mar 21, 2023 |
| Framework     | Laptop                      | Notebook    | [a7dc7b28c9](https://linux-hardware.org/?probe=a7dc7b28c9) | Mar 21, 2023 |
| Fujitsu       | FMVNP8AE                    | Notebook    | [10efc9f976](https://linux-hardware.org/?probe=10efc9f976) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Nvidia        | Tegra                       | Soc         | [68ac87675a](https://linux-hardware.org/?probe=68ac87675a) | Mar 20, 2023 |
| Nvidia        | Tegra                       | Soc         | [e6398a18ac](https://linux-hardware.org/?probe=e6398a18ac) | Mar 20, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [db7d70cd41](https://linux-hardware.org/?probe=db7d70cd41) | Mar 20, 2023 |
| ASUSTek       | M51BC                       | Desktop     | [65db0797b0](https://linux-hardware.org/?probe=65db0797b0) | Mar 19, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [fdedfdf220](https://linux-hardware.org/?probe=fdedfdf220) | Mar 19, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d21d79ee06](https://linux-hardware.org/?probe=d21d79ee06) | Mar 19, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [63b182c7d6](https://linux-hardware.org/?probe=63b182c7d6) | Mar 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [22e0286a24](https://linux-hardware.org/?probe=22e0286a24) | Mar 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [0018c1237d](https://linux-hardware.org/?probe=0018c1237d) | Mar 19, 2023 |
| Intel         | 945GCT-M                    | Desktop     | [ac83eeefb9](https://linux-hardware.org/?probe=ac83eeefb9) | Mar 19, 2023 |
| ASUSTek       | P5K                         | Desktop     | [5f34498a89](https://linux-hardware.org/?probe=5f34498a89) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| HP            | 18E8                        | Desktop     | [bf7c3c9080](https://linux-hardware.org/?probe=bf7c3c9080) | Mar 18, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [a721b1b9d6](https://linux-hardware.org/?probe=a721b1b9d6) | Mar 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [17e455c4df](https://linux-hardware.org/?probe=17e455c4df) | Mar 18, 2023 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [33fb26b354](https://linux-hardware.org/?probe=33fb26b354) | Mar 17, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [0c7a43b36b](https://linux-hardware.org/?probe=0c7a43b36b) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [7df2952615](https://linux-hardware.org/?probe=7df2952615) | Mar 17, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [d21c2315d1](https://linux-hardware.org/?probe=d21c2315d1) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [40f92632ab](https://linux-hardware.org/?probe=40f92632ab) | Mar 16, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1b43670875](https://linux-hardware.org/?probe=1b43670875) | Mar 16, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [63893daa0f](https://linux-hardware.org/?probe=63893daa0f) | Mar 16, 2023 |
| Dell          | 0K9T56 A00                  | All in one  | [39994acde2](https://linux-hardware.org/?probe=39994acde2) | Mar 16, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [e89d2059c0](https://linux-hardware.org/?probe=e89d2059c0) | Mar 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [5d43e434bc](https://linux-hardware.org/?probe=5d43e434bc) | Mar 16, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [ae37b87da6](https://linux-hardware.org/?probe=ae37b87da6) | Mar 16, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [10e835b353](https://linux-hardware.org/?probe=10e835b353) | Mar 16, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [1674c37cf9](https://linux-hardware.org/?probe=1674c37cf9) | Mar 16, 2023 |
| Microsoft     | Surface Book                | Tablet      | [d5cd9be69a](https://linux-hardware.org/?probe=d5cd9be69a) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Matsushita... | CF-18KH2ZXBC                | Notebook    | [9aa73891cd](https://linux-hardware.org/?probe=9aa73891cd) | Mar 15, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [113fcf770d](https://linux-hardware.org/?probe=113fcf770d) | Mar 15, 2023 |
| Dell          | 0W0CHX A01                  | Desktop     | [29197fc6e4](https://linux-hardware.org/?probe=29197fc6e4) | Mar 15, 2023 |
| HP            | 21D0                        | Desktop     | [9b7d2f0a4f](https://linux-hardware.org/?probe=9b7d2f0a4f) | Mar 15, 2023 |
| Supermicro    | X9DRD-C/iT+                 | Desktop     | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [4707dc8ed6](https://linux-hardware.org/?probe=4707dc8ed6) | Mar 15, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e6033259b6](https://linux-hardware.org/?probe=e6033259b6) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [cd389d99a0](https://linux-hardware.org/?probe=cd389d99a0) | Mar 14, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [3ea59ee8c5](https://linux-hardware.org/?probe=3ea59ee8c5) | Mar 14, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4cad3cfe12](https://linux-hardware.org/?probe=4cad3cfe12) | Mar 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7fbe857344](https://linux-hardware.org/?probe=7fbe857344) | Mar 14, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [047e561901](https://linux-hardware.org/?probe=047e561901) | Mar 14, 2023 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [9332803ca3](https://linux-hardware.org/?probe=9332803ca3) | Mar 13, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [2b942e22c2](https://linux-hardware.org/?probe=2b942e22c2) | Mar 13, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [e2379c1008](https://linux-hardware.org/?probe=e2379c1008) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | Notebook    | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [1f67ba4519](https://linux-hardware.org/?probe=1f67ba4519) | Mar 13, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [1525ad44e2](https://linux-hardware.org/?probe=1525ad44e2) | Mar 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [7d42741fac](https://linux-hardware.org/?probe=7d42741fac) | Mar 12, 2023 |
| Google        | Droid                       | Notebook    | [b2a41c71ac](https://linux-hardware.org/?probe=b2a41c71ac) | Mar 12, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [2eb6d39ced](https://linux-hardware.org/?probe=2eb6d39ced) | Mar 12, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [01f61fad51](https://linux-hardware.org/?probe=01f61fad51) | Mar 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [d1336c09a0](https://linux-hardware.org/?probe=d1336c09a0) | Mar 11, 2023 |
| Gigabyte      | Z170X-UD3 Ultra-CF          | Desktop     | [fa2be7de30](https://linux-hardware.org/?probe=fa2be7de30) | Mar 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c5419b8b27](https://linux-hardware.org/?probe=c5419b8b27) | Mar 11, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [da8c40d88c](https://linux-hardware.org/?probe=da8c40d88c) | Mar 11, 2023 |
| HP            | 0AACh                       | Desktop     | [83f0c7df93](https://linux-hardware.org/?probe=83f0c7df93) | Mar 10, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [dbdadff4f2](https://linux-hardware.org/?probe=dbdadff4f2) | Mar 10, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [e4fe786b7a](https://linux-hardware.org/?probe=e4fe786b7a) | Mar 10, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [e183f14e7e](https://linux-hardware.org/?probe=e183f14e7e) | Mar 10, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [bf2d3857fd](https://linux-hardware.org/?probe=bf2d3857fd) | Mar 09, 2023 |
| Dell          | Latitude 3180               | Notebook    | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF       | Desktop     | [1140b33d95](https://linux-hardware.org/?probe=1140b33d95) | Mar 09, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [515a056886](https://linux-hardware.org/?probe=515a056886) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f658e58c98](https://linux-hardware.org/?probe=f658e58c98) | Mar 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [da38390eca](https://linux-hardware.org/?probe=da38390eca) | Mar 09, 2023 |
| libre-comp... | aml-s905x-cc                | Soc         | [fba90acf4d](https://linux-hardware.org/?probe=fba90acf4d) | Mar 09, 2023 |
| HP            | 8591                        | Desktop     | [1620787dc3](https://linux-hardware.org/?probe=1620787dc3) | Mar 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [b99222314c](https://linux-hardware.org/?probe=b99222314c) | Mar 08, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [1162f373d9](https://linux-hardware.org/?probe=1162f373d9) | Mar 08, 2023 |
| Lenovo        | ThinkCentre M91p 4524B61    | Desktop     | [ed46b4c885](https://linux-hardware.org/?probe=ed46b4c885) | Mar 07, 2023 |
| Lenovo        | ThinkCentre M91p 4524B61    | Desktop     | [87a3321cf9](https://linux-hardware.org/?probe=87a3321cf9) | Mar 07, 2023 |
| Lenovo        | 3000 N200 0769AUU           | Notebook    | [faaa24cfbf](https://linux-hardware.org/?probe=faaa24cfbf) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | Desktop     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| Dell          | Studio 1537                 | Notebook    | [2cadadec43](https://linux-hardware.org/?probe=2cadadec43) | Mar 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [5e7340faf5](https://linux-hardware.org/?probe=5e7340faf5) | Mar 07, 2023 |
| Lenovo        | 3000 N200 0769AUU           | Notebook    | [fe3f99601c](https://linux-hardware.org/?probe=fe3f99601c) | Mar 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [70b5b39ce8](https://linux-hardware.org/?probe=70b5b39ce8) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6493617e39](https://linux-hardware.org/?probe=6493617e39) | Mar 07, 2023 |
| Datto         | 1000                        | Notebook    | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c6f9f5a58d](https://linux-hardware.org/?probe=c6f9f5a58d) | Mar 06, 2023 |
| ECS           | X58B-A                      | Desktop     | [e074c61884](https://linux-hardware.org/?probe=e074c61884) | Mar 06, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [5f35f09385](https://linux-hardware.org/?probe=5f35f09385) | Mar 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [77ca3b430b](https://linux-hardware.org/?probe=77ca3b430b) | Mar 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [2194ce4568](https://linux-hardware.org/?probe=2194ce4568) | Mar 06, 2023 |
| MSI           | PS42 8RB                    | Notebook    | [57231416e1](https://linux-hardware.org/?probe=57231416e1) | Mar 06, 2023 |
| HP            | 18E4                        | Desktop     | [a277b636c1](https://linux-hardware.org/?probe=a277b636c1) | Mar 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [64d9894f5e](https://linux-hardware.org/?probe=64d9894f5e) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ccca18039f](https://linux-hardware.org/?probe=ccca18039f) | Mar 05, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [24373477d9](https://linux-hardware.org/?probe=24373477d9) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [f0b9f4e39f](https://linux-hardware.org/?probe=f0b9f4e39f) | Mar 05, 2023 |
| MSI           | PS42 8RB                    | Notebook    | [effde33b49](https://linux-hardware.org/?probe=effde33b49) | Mar 05, 2023 |
| HP            | 828A                        | Desktop     | [a6609046b5](https://linux-hardware.org/?probe=a6609046b5) | Mar 05, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [886fdbe7c9](https://linux-hardware.org/?probe=886fdbe7c9) | Mar 05, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [2fdc151d2f](https://linux-hardware.org/?probe=2fdc151d2f) | Mar 05, 2023 |
| Dell          | Precision M4800             | Notebook    | [b014753659](https://linux-hardware.org/?probe=b014753659) | Mar 05, 2023 |
| HP            | 0AA0h                       | Desktop     | [657f888891](https://linux-hardware.org/?probe=657f888891) | Mar 04, 2023 |
| HP            | Presario CQ61               | Notebook    | [912b79009b](https://linux-hardware.org/?probe=912b79009b) | Mar 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [6181549e93](https://linux-hardware.org/?probe=6181549e93) | Mar 04, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [b9a0465659](https://linux-hardware.org/?probe=b9a0465659) | Mar 04, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [8c0488a140](https://linux-hardware.org/?probe=8c0488a140) | Mar 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a750fc7c24](https://linux-hardware.org/?probe=a750fc7c24) | Mar 04, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [6258e45123](https://linux-hardware.org/?probe=6258e45123) | Mar 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e106ed41e](https://linux-hardware.org/?probe=0e106ed41e) | Mar 04, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9aebf534a5](https://linux-hardware.org/?probe=9aebf534a5) | Mar 04, 2023 |
| Lenovo        | ThinkPad X220 429035U       | Notebook    | [83266c1006](https://linux-hardware.org/?probe=83266c1006) | Mar 04, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [01de5e633e](https://linux-hardware.org/?probe=01de5e633e) | Mar 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a8904b4cc0](https://linux-hardware.org/?probe=a8904b4cc0) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
| HP            | ENVY 17                     | Notebook    | [52b43673bb](https://linux-hardware.org/?probe=52b43673bb) | Mar 03, 2023 |
| Acer          | Aspire M3970                | Desktop     | [2708d5fa99](https://linux-hardware.org/?probe=2708d5fa99) | Mar 03, 2023 |
| Win elemen... | M600                        | Desktop     | [36ce350e0c](https://linux-hardware.org/?probe=36ce350e0c) | Mar 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0a8ce98d46](https://linux-hardware.org/?probe=0a8ce98d46) | Mar 03, 2023 |
| HP            | 212B                        | Desktop     | [a64d1078d4](https://linux-hardware.org/?probe=a64d1078d4) | Mar 03, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [03db87f6d8](https://linux-hardware.org/?probe=03db87f6d8) | Mar 03, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [e8f0217102](https://linux-hardware.org/?probe=e8f0217102) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e08a9cdac6](https://linux-hardware.org/?probe=e08a9cdac6) | Mar 03, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [3cabf6cbe4](https://linux-hardware.org/?probe=3cabf6cbe4) | Mar 03, 2023 |
| Dell          | 0D6H9T A02                  | Desktop     | [0027e59622](https://linux-hardware.org/?probe=0027e59622) | Mar 02, 2023 |
| Microsoft     | Surface Book                | Tablet      | [cc3ad3e0d2](https://linux-hardware.org/?probe=cc3ad3e0d2) | Mar 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4d68c19c3e](https://linux-hardware.org/?probe=4d68c19c3e) | Mar 02, 2023 |
| HP            | 212B                        | Desktop     | [f771bfe252](https://linux-hardware.org/?probe=f771bfe252) | Mar 02, 2023 |
| HP            | 18E4                        | Desktop     | [8e76736e7e](https://linux-hardware.org/?probe=8e76736e7e) | Mar 02, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Dell          | Precision 5520              | Notebook    | [9ce4c56521](https://linux-hardware.org/?probe=9ce4c56521) | Mar 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [6525b5d0a4](https://linux-hardware.org/?probe=6525b5d0a4) | Mar 01, 2023 |
| Microsoft     | Surface Book                | Tablet      | [d58385d1e6](https://linux-hardware.org/?probe=d58385d1e6) | Mar 01, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [9abfe7631c](https://linux-hardware.org/?probe=9abfe7631c) | Mar 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [a6c009eb9c](https://linux-hardware.org/?probe=a6c009eb9c) | Mar 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [903b322b17](https://linux-hardware.org/?probe=903b322b17) | Mar 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [92300b45fe](https://linux-hardware.org/?probe=92300b45fe) | Mar 01, 2023 |
| AZW           | GTR V01                     | Mini pc     | [09e66839c3](https://linux-hardware.org/?probe=09e66839c3) | Mar 01, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [006fbf48e9](https://linux-hardware.org/?probe=006fbf48e9) | Mar 01, 2023 |
| Acer          | Aspire E1-532P              | Notebook    | [8a23f06db4](https://linux-hardware.org/?probe=8a23f06db4) | Mar 01, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c937edbfcd](https://linux-hardware.org/?probe=c937edbfcd) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [483db5a7bd](https://linux-hardware.org/?probe=483db5a7bd) | Feb 28, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [d0813971b9](https://linux-hardware.org/?probe=d0813971b9) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [d8b58a8ea1](https://linux-hardware.org/?probe=d8b58a8ea1) | Feb 28, 2023 |
| ASRockRack    | E3C246D4U2-2T               | Desktop     | [1ad2cb5102](https://linux-hardware.org/?probe=1ad2cb5102) | Feb 28, 2023 |
| Alienware     | x15 R2                      | Notebook    | [f0335542ce](https://linux-hardware.org/?probe=f0335542ce) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6ccb40f64d](https://linux-hardware.org/?probe=6ccb40f64d) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| ASRock        | Z790 PG Lightning           | Desktop     | [86c7144757](https://linux-hardware.org/?probe=86c7144757) | Feb 27, 2023 |
| HP            | 18E4                        | Desktop     | [cab6d807e9](https://linux-hardware.org/?probe=cab6d807e9) | Feb 27, 2023 |
| Unknown       | HX90                        | Desktop     | [bc8bed9135](https://linux-hardware.org/?probe=bc8bed9135) | Feb 27, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [6d9216b866](https://linux-hardware.org/?probe=6d9216b866) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| ASUSTek       | B150 PRO GAMING/AURA        | Desktop     | [618e3d30fc](https://linux-hardware.org/?probe=618e3d30fc) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [091e4e3188](https://linux-hardware.org/?probe=091e4e3188) | Feb 27, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [a9a8184201](https://linux-hardware.org/?probe=a9a8184201) | Feb 27, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [07f46e8e62](https://linux-hardware.org/?probe=07f46e8e62) | Feb 27, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [8de57c03d5](https://linux-hardware.org/?probe=8de57c03d5) | Feb 27, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [a3b8430bad](https://linux-hardware.org/?probe=a3b8430bad) | Feb 26, 2023 |
| HP            | 18E4                        | Desktop     | [5c7c3413c9](https://linux-hardware.org/?probe=5c7c3413c9) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [97b08529eb](https://linux-hardware.org/?probe=97b08529eb) | Feb 26, 2023 |
| Sapphire      | PE-AM2RS690V2               | Desktop     | [8aa6cda98e](https://linux-hardware.org/?probe=8aa6cda98e) | Feb 26, 2023 |
| Dell          | 0G3HR7 A00                  | Desktop     | [33723c8b80](https://linux-hardware.org/?probe=33723c8b80) | Feb 25, 2023 |
| Lenovo        | ThinkPad T460 20FMS35H02    | Notebook    | [a396e54378](https://linux-hardware.org/?probe=a396e54378) | Feb 25, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [c863d76de9](https://linux-hardware.org/?probe=c863d76de9) | Feb 25, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [fbb2478f8c](https://linux-hardware.org/?probe=fbb2478f8c) | Feb 25, 2023 |
| HP            | G60                         | Notebook    | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| Protectli     | VP2420                      | Desktop     | [ea5f851cf3](https://linux-hardware.org/?probe=ea5f851cf3) | Feb 25, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [59b7e1da6d](https://linux-hardware.org/?probe=59b7e1da6d) | Feb 25, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [6053547fd3](https://linux-hardware.org/?probe=6053547fd3) | Feb 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [fb42cba088](https://linux-hardware.org/?probe=fb42cba088) | Feb 25, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [79bb0eb4c9](https://linux-hardware.org/?probe=79bb0eb4c9) | Feb 25, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [3575d2e78d](https://linux-hardware.org/?probe=3575d2e78d) | Feb 25, 2023 |
| Intel         | JSL MRD                     | Desktop     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| Google        | Kefka                       | Notebook    | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [5070b384cc](https://linux-hardware.org/?probe=5070b384cc) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [ea8027e95b](https://linux-hardware.org/?probe=ea8027e95b) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [6db3a90234](https://linux-hardware.org/?probe=6db3a90234) | Feb 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [59ec61666a](https://linux-hardware.org/?probe=59ec61666a) | Feb 24, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [e162d5848c](https://linux-hardware.org/?probe=e162d5848c) | Feb 24, 2023 |
| AZW           | U59                         | Desktop     | [b574c32b53](https://linux-hardware.org/?probe=b574c32b53) | Feb 24, 2023 |
| Gateway       | SX2185                      | Desktop     | [32ab171e53](https://linux-hardware.org/?probe=32ab171e53) | Feb 23, 2023 |
| ASUSTek       | P5K                         | Desktop     | [2fb7f1713b](https://linux-hardware.org/?probe=2fb7f1713b) | Feb 23, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [e0687d11bb](https://linux-hardware.org/?probe=e0687d11bb) | Feb 23, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [49e71eb5b4](https://linux-hardware.org/?probe=49e71eb5b4) | Feb 22, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| Dell          | Latitude E6520              | Notebook    | [4a9371ec87](https://linux-hardware.org/?probe=4a9371ec87) | Feb 22, 2023 |
| Acer          | Aspire X3470                | Desktop     | [659a1f31bd](https://linux-hardware.org/?probe=659a1f31bd) | Feb 22, 2023 |
| AWOW          | NY PC BOX                   | Mini pc     | [3e9e7c877c](https://linux-hardware.org/?probe=3e9e7c877c) | Feb 22, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [7599e919d9](https://linux-hardware.org/?probe=7599e919d9) | Feb 22, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [d003c3ed81](https://linux-hardware.org/?probe=d003c3ed81) | Feb 22, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [7234bd12f6](https://linux-hardware.org/?probe=7234bd12f6) | Feb 22, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [a28282663a](https://linux-hardware.org/?probe=a28282663a) | Feb 22, 2023 |
| Dell          | 0PM2CW A05                  | Server      | [13c1bd9dcd](https://linux-hardware.org/?probe=13c1bd9dcd) | Feb 22, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [524153d219](https://linux-hardware.org/?probe=524153d219) | Feb 22, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [ade0244936](https://linux-hardware.org/?probe=ade0244936) | Feb 21, 2023 |
| Dell          | Inspiron 5493               | Notebook    | [ad7bee8a6e](https://linux-hardware.org/?probe=ad7bee8a6e) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [04130aaf41](https://linux-hardware.org/?probe=04130aaf41) | Feb 20, 2023 |
| Dell          | Latitude E5440              | Notebook    | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [40ae7724b9](https://linux-hardware.org/?probe=40ae7724b9) | Feb 20, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [08d8865fcf](https://linux-hardware.org/?probe=08d8865fcf) | Feb 20, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [924264cbec](https://linux-hardware.org/?probe=924264cbec) | Feb 20, 2023 |
| AZW           | GK mini                     | Desktop     | [6fc9af1346](https://linux-hardware.org/?probe=6fc9af1346) | Feb 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [d346153872](https://linux-hardware.org/?probe=d346153872) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58 8910B4U     | Desktop     | [03c8e6d135](https://linux-hardware.org/?probe=03c8e6d135) | Feb 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| Dell          | Precision M4500             | Notebook    | [b0d8bf3c56](https://linux-hardware.org/?probe=b0d8bf3c56) | Feb 19, 2023 |
| Panasonic     | CF-S10CDHEDM                | Notebook    | [7228f7a915](https://linux-hardware.org/?probe=7228f7a915) | Feb 19, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [b0941b8ef0](https://linux-hardware.org/?probe=b0941b8ef0) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [58ca93166c](https://linux-hardware.org/?probe=58ca93166c) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9978dc62b3](https://linux-hardware.org/?probe=9978dc62b3) | Feb 18, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [6b7a3b68f3](https://linux-hardware.org/?probe=6b7a3b68f3) | Feb 18, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| MSI           | Raider GE76 12UGS           | Notebook    | [041cf0d3d8](https://linux-hardware.org/?probe=041cf0d3d8) | Feb 18, 2023 |
| MSI           | Raider GE76 12UGS           | Notebook    | [20dc6d6c5c](https://linux-hardware.org/?probe=20dc6d6c5c) | Feb 18, 2023 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [af3167a0d4](https://linux-hardware.org/?probe=af3167a0d4) | Feb 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a2dfe19fc](https://linux-hardware.org/?probe=2a2dfe19fc) | Feb 18, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [feae434e9e](https://linux-hardware.org/?probe=feae434e9e) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [9ab628bcf2](https://linux-hardware.org/?probe=9ab628bcf2) | Feb 18, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [aaa83a4af0](https://linux-hardware.org/?probe=aaa83a4af0) | Feb 18, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [18b6274238](https://linux-hardware.org/?probe=18b6274238) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [33d9c73cb9](https://linux-hardware.org/?probe=33d9c73cb9) | Feb 17, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [7ef47e7131](https://linux-hardware.org/?probe=7ef47e7131) | Feb 17, 2023 |
| Google        | Coral                       | Notebook    | [7a9869ff50](https://linux-hardware.org/?probe=7a9869ff50) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| ASRock        | B360M Xtreme                | Desktop     | [0804d226b0](https://linux-hardware.org/?probe=0804d226b0) | Feb 17, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c913edda07](https://linux-hardware.org/?probe=c913edda07) | Feb 17, 2023 |
| HP            | 1825                        | Desktop     | [858ebd3baf](https://linux-hardware.org/?probe=858ebd3baf) | Feb 17, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4101f152f5](https://linux-hardware.org/?probe=4101f152f5) | Feb 17, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [395a5da0fb](https://linux-hardware.org/?probe=395a5da0fb) | Feb 17, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [92901492fc](https://linux-hardware.org/?probe=92901492fc) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [361eb28148](https://linux-hardware.org/?probe=361eb28148) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [0e694f49fe](https://linux-hardware.org/?probe=0e694f49fe) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [af47a30d6a](https://linux-hardware.org/?probe=af47a30d6a) | Feb 15, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [987c9b1854](https://linux-hardware.org/?probe=987c9b1854) | Feb 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [3db09e931e](https://linux-hardware.org/?probe=3db09e931e) | Feb 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [ed02038c00](https://linux-hardware.org/?probe=ed02038c00) | Feb 15, 2023 |
| IBM           | 811328U                     | Desktop     | [dc9536a0f2](https://linux-hardware.org/?probe=dc9536a0f2) | Feb 14, 2023 |
| IBM           | 811328U                     | Desktop     | [6ad9b1f22a](https://linux-hardware.org/?probe=6ad9b1f22a) | Feb 14, 2023 |
| Pegatron      | Narra6                      | Desktop     | [13f0acba4c](https://linux-hardware.org/?probe=13f0acba4c) | Feb 14, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [2b9a026876](https://linux-hardware.org/?probe=2b9a026876) | Feb 14, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [4262fa293e](https://linux-hardware.org/?probe=4262fa293e) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [9de6fe5d90](https://linux-hardware.org/?probe=9de6fe5d90) | Feb 14, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [43d2279955](https://linux-hardware.org/?probe=43d2279955) | Feb 14, 2023 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [500a5cf614](https://linux-hardware.org/?probe=500a5cf614) | Feb 14, 2023 |
| HP            | 83EE                        | Desktop     | [f83f333b3c](https://linux-hardware.org/?probe=f83f333b3c) | Feb 14, 2023 |
| ASUSTek       | Zenbook UN5401QAB_UN5401... | Convertible | [256f660b72](https://linux-hardware.org/?probe=256f660b72) | Feb 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [68463d6d4b](https://linux-hardware.org/?probe=68463d6d4b) | Feb 13, 2023 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [60ddb51b98](https://linux-hardware.org/?probe=60ddb51b98) | Feb 13, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [2d99eeaca6](https://linux-hardware.org/?probe=2d99eeaca6) | Feb 13, 2023 |
| Panasonic     | CF-C2CCEZXCM                | Notebook    | [c435502e6e](https://linux-hardware.org/?probe=c435502e6e) | Feb 13, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1VL0... | Notebook    | [d4b5ca228c](https://linux-hardware.org/?probe=d4b5ca228c) | Feb 13, 2023 |
| HP            | Pavilion dv2500             | Notebook    | [bea8c0162f](https://linux-hardware.org/?probe=bea8c0162f) | Feb 12, 2023 |
| Panasonic     | CF-C2CCEZXCM                | Notebook    | [3a0ce0730a](https://linux-hardware.org/?probe=3a0ce0730a) | Feb 12, 2023 |
| Lenovo        | 4030                        | Desktop     | [a0052fd936](https://linux-hardware.org/?probe=a0052fd936) | Feb 12, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bf986cc448](https://linux-hardware.org/?probe=bf986cc448) | Feb 12, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8133fc11b8](https://linux-hardware.org/?probe=8133fc11b8) | Feb 12, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [866ad6408c](https://linux-hardware.org/?probe=866ad6408c) | Feb 12, 2023 |
| Acer          | Aspire 8942G                | Notebook    | [d517f63625](https://linux-hardware.org/?probe=d517f63625) | Feb 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [10084e1b16](https://linux-hardware.org/?probe=10084e1b16) | Feb 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [3e048e046a](https://linux-hardware.org/?probe=3e048e046a) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3982ec4e74](https://linux-hardware.org/?probe=3982ec4e74) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a034121d24](https://linux-hardware.org/?probe=a034121d24) | Feb 12, 2023 |
| Pegatron      | Narra6                      | Desktop     | [77bed4b6f3](https://linux-hardware.org/?probe=77bed4b6f3) | Feb 12, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [7092ef977d](https://linux-hardware.org/?probe=7092ef977d) | Feb 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a81107301](https://linux-hardware.org/?probe=9a81107301) | Feb 11, 2023 |
| HP            | Presario V6000 (RN927UA#... | Notebook    | [0524b3b524](https://linux-hardware.org/?probe=0524b3b524) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [266a3eff3f](https://linux-hardware.org/?probe=266a3eff3f) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [18b84d9ea2](https://linux-hardware.org/?probe=18b84d9ea2) | Feb 10, 2023 |
| Google        | Droid                       | Notebook    | [33dbb43623](https://linux-hardware.org/?probe=33dbb43623) | Feb 10, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [663cbf83ff](https://linux-hardware.org/?probe=663cbf83ff) | Feb 10, 2023 |
| HP            | Notebook                    | Notebook    | [17664bf689](https://linux-hardware.org/?probe=17664bf689) | Feb 10, 2023 |
| Supermicro    | C7Z370-CG-IW                | Server      | [5145e7d26e](https://linux-hardware.org/?probe=5145e7d26e) | Feb 10, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [0a74293474](https://linux-hardware.org/?probe=0a74293474) | Feb 10, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [9b8563ab53](https://linux-hardware.org/?probe=9b8563ab53) | Feb 10, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [ed180eeb68](https://linux-hardware.org/?probe=ed180eeb68) | Feb 09, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fff827c027](https://linux-hardware.org/?probe=fff827c027) | Feb 09, 2023 |
| Acer          | Aspire M3970                | Desktop     | [718cc13462](https://linux-hardware.org/?probe=718cc13462) | Feb 09, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [91de8b5956](https://linux-hardware.org/?probe=91de8b5956) | Feb 09, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [d236f5fa51](https://linux-hardware.org/?probe=d236f5fa51) | Feb 09, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [aaa509fed7](https://linux-hardware.org/?probe=aaa509fed7) | Feb 09, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [148b3b0adc](https://linux-hardware.org/?probe=148b3b0adc) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7ad97f8b6d](https://linux-hardware.org/?probe=7ad97f8b6d) | Feb 09, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [7b17cbd936](https://linux-hardware.org/?probe=7b17cbd936) | Feb 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0593b2bac6](https://linux-hardware.org/?probe=0593b2bac6) | Feb 08, 2023 |
| ASUSTek       | B150 PRO GAMING D3          | Desktop     | [8178f6bf56](https://linux-hardware.org/?probe=8178f6bf56) | Feb 08, 2023 |
| Lenovo        | Unknown                     | Notebook    | [67c2761551](https://linux-hardware.org/?probe=67c2761551) | Feb 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [feeed093c0](https://linux-hardware.org/?probe=feeed093c0) | Feb 07, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [ebe5940bd7](https://linux-hardware.org/?probe=ebe5940bd7) | Feb 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a019143fe9](https://linux-hardware.org/?probe=a019143fe9) | Feb 07, 2023 |
| MSI           | GT72 6QE                    | Notebook    | [bd02e4c770](https://linux-hardware.org/?probe=bd02e4c770) | Feb 07, 2023 |
| MSI           | GT72 6QE                    | Notebook    | [43a7194d4b](https://linux-hardware.org/?probe=43a7194d4b) | Feb 07, 2023 |
| Acer          | Aspire TC-1760              | Desktop     | [b7fdb6cd73](https://linux-hardware.org/?probe=b7fdb6cd73) | Feb 06, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [70f715ffb4](https://linux-hardware.org/?probe=70f715ffb4) | Feb 06, 2023 |
| Acer          | Okinawa                     | Notebook    | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [f7ca9a94c5](https://linux-hardware.org/?probe=f7ca9a94c5) | Feb 06, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c73a4ad56a](https://linux-hardware.org/?probe=c73a4ad56a) | Feb 06, 2023 |
| Dell          | 0XNNCJ A03                  | Server      | [a0b1f2a7b4](https://linux-hardware.org/?probe=a0b1f2a7b4) | Feb 06, 2023 |
| AZW           | U59                         | Desktop     | [b97c4f6277](https://linux-hardware.org/?probe=b97c4f6277) | Feb 06, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [b452c164d0](https://linux-hardware.org/?probe=b452c164d0) | Feb 05, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [2543adebba](https://linux-hardware.org/?probe=2543adebba) | Feb 05, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c35fa9b7f5](https://linux-hardware.org/?probe=c35fa9b7f5) | Feb 05, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [f3f4d9fc40](https://linux-hardware.org/?probe=f3f4d9fc40) | Feb 04, 2023 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [486f19af99](https://linux-hardware.org/?probe=486f19af99) | Feb 04, 2023 |
| HP            | G60                         | Notebook    | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| MSI           | 870-G45                     | Desktop     | [92b840c75e](https://linux-hardware.org/?probe=92b840c75e) | Feb 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [768696d7b8](https://linux-hardware.org/?probe=768696d7b8) | Feb 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [d78de63927](https://linux-hardware.org/?probe=d78de63927) | Feb 04, 2023 |
| HP            | 0AACh                       | Desktop     | [86d994993f](https://linux-hardware.org/?probe=86d994993f) | Feb 03, 2023 |
| AZW           | SER                         | Mini pc     | [ce867dfcef](https://linux-hardware.org/?probe=ce867dfcef) | Feb 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6bb0e68672](https://linux-hardware.org/?probe=6bb0e68672) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [afadbdee59](https://linux-hardware.org/?probe=afadbdee59) | Feb 03, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [93630ab2ea](https://linux-hardware.org/?probe=93630ab2ea) | Feb 03, 2023 |
| Xunlong       | Orange Pi Zero              | Soc         | [3af57a322f](https://linux-hardware.org/?probe=3af57a322f) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [c122070f4f](https://linux-hardware.org/?probe=c122070f4f) | Feb 03, 2023 |
| ASRock        | H510M-HVS                   | Desktop     | [c2bdc49f09](https://linux-hardware.org/?probe=c2bdc49f09) | Feb 03, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [830188ba1b](https://linux-hardware.org/?probe=830188ba1b) | Feb 03, 2023 |
| Dell          | Latitude 3400               | Notebook    | [c954aad23a](https://linux-hardware.org/?probe=c954aad23a) | Feb 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f6ad918c7e](https://linux-hardware.org/?probe=f6ad918c7e) | Feb 02, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [78ea388883](https://linux-hardware.org/?probe=78ea388883) | Feb 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ef1817a829](https://linux-hardware.org/?probe=ef1817a829) | Feb 02, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [d2696b9042](https://linux-hardware.org/?probe=d2696b9042) | Feb 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f2919f7135](https://linux-hardware.org/?probe=f2919f7135) | Feb 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ab92a33bdf](https://linux-hardware.org/?probe=ab92a33bdf) | Feb 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [8bc290ef67](https://linux-hardware.org/?probe=8bc290ef67) | Feb 01, 2023 |
| HP            | 0AACh                       | Desktop     | [f41abcf7f9](https://linux-hardware.org/?probe=f41abcf7f9) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [5dcda0d3e5](https://linux-hardware.org/?probe=5dcda0d3e5) | Feb 01, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [1ce7db78c1](https://linux-hardware.org/?probe=1ce7db78c1) | Feb 01, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [1b880dbac2](https://linux-hardware.org/?probe=1b880dbac2) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [ffe1cabad7](https://linux-hardware.org/?probe=ffe1cabad7) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [bea57d418a](https://linux-hardware.org/?probe=bea57d418a) | Feb 01, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [455825998f](https://linux-hardware.org/?probe=455825998f) | Feb 01, 2023 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [c102edf6a0](https://linux-hardware.org/?probe=c102edf6a0) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4f8642280f](https://linux-hardware.org/?probe=4f8642280f) | Feb 01, 2023 |
| Dell          | 0PU052                      | Desktop     | [d2f241353d](https://linux-hardware.org/?probe=d2f241353d) | Feb 01, 2023 |
| Intel         | DG965OT AAD75595-200        | Desktop     | [8ab85c58be](https://linux-hardware.org/?probe=8ab85c58be) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [23b27dab7d](https://linux-hardware.org/?probe=23b27dab7d) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [1d212c67b2](https://linux-hardware.org/?probe=1d212c67b2) | Jan 31, 2023 |
| Dell          | Inspiron 15-7579            | Notebook    | [b5bd231bf3](https://linux-hardware.org/?probe=b5bd231bf3) | Jan 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [21b6d00ff2](https://linux-hardware.org/?probe=21b6d00ff2) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [32961ffb11](https://linux-hardware.org/?probe=32961ffb11) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [94baf3c57c](https://linux-hardware.org/?probe=94baf3c57c) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [d59770af38](https://linux-hardware.org/?probe=d59770af38) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [3a5ae3d1e8](https://linux-hardware.org/?probe=3a5ae3d1e8) | Jan 31, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [4dcc88b215](https://linux-hardware.org/?probe=4dcc88b215) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| Dell          | Latitude D630               | Notebook    | [ff0aa8c4ed](https://linux-hardware.org/?probe=ff0aa8c4ed) | Jan 31, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| Lenovo        | ThinkPad P51 20HJS0BR00     | Notebook    | [6c05048c9d](https://linux-hardware.org/?probe=6c05048c9d) | Jan 31, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [989e45d84b](https://linux-hardware.org/?probe=989e45d84b) | Jan 31, 2023 |
| MSI           | 870-G45                     | Desktop     | [cda1aade14](https://linux-hardware.org/?probe=cda1aade14) | Jan 31, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [6e7d6aae31](https://linux-hardware.org/?probe=6e7d6aae31) | Jan 31, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [6296345ebb](https://linux-hardware.org/?probe=6296345ebb) | Jan 31, 2023 |
| HP            | 339A                        | Desktop     | [e3078cd4d7](https://linux-hardware.org/?probe=e3078cd4d7) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [0eac708be5](https://linux-hardware.org/?probe=0eac708be5) | Jan 31, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [1196b501d5](https://linux-hardware.org/?probe=1196b501d5) | Jan 31, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [9edd1a1969](https://linux-hardware.org/?probe=9edd1a1969) | Jan 30, 2023 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [3e004045f7](https://linux-hardware.org/?probe=3e004045f7) | Jan 30, 2023 |
| HP            | Notebook                    | Notebook    | [fc93f8e357](https://linux-hardware.org/?probe=fc93f8e357) | Jan 30, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [cbfcb68cc6](https://linux-hardware.org/?probe=cbfcb68cc6) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f0000c6ae7](https://linux-hardware.org/?probe=f0000c6ae7) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [3fcf581653](https://linux-hardware.org/?probe=3fcf581653) | Jan 30, 2023 |
| Dell          | Vostro 7620                 | Notebook    | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [77c9cc065f](https://linux-hardware.org/?probe=77c9cc065f) | Jan 29, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [1ddc17833b](https://linux-hardware.org/?probe=1ddc17833b) | Jan 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [104fb04e91](https://linux-hardware.org/?probe=104fb04e91) | Jan 29, 2023 |
| ASUSTek       | B150M-C                     | Desktop     | [6eb1a5b38e](https://linux-hardware.org/?probe=6eb1a5b38e) | Jan 29, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [03171e1e33](https://linux-hardware.org/?probe=03171e1e33) | Jan 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [9f2e4066f6](https://linux-hardware.org/?probe=9f2e4066f6) | Jan 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [f2bf9c3c82](https://linux-hardware.org/?probe=f2bf9c3c82) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [2d2e42ae23](https://linux-hardware.org/?probe=2d2e42ae23) | Jan 28, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [3e7c902731](https://linux-hardware.org/?probe=3e7c902731) | Jan 28, 2023 |
| ASUSTek       | X555QA                      | Notebook    | [8eec8468fb](https://linux-hardware.org/?probe=8eec8468fb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [991bb71df8](https://linux-hardware.org/?probe=991bb71df8) | Jan 28, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [d86e915f12](https://linux-hardware.org/?probe=d86e915f12) | Jan 28, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [796df2715d](https://linux-hardware.org/?probe=796df2715d) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 811       | 13.72%  |
| Ubuntu 18.04       | 423       | 7.15%   |
| Ubuntu 22.04       | 278       | 4.7%    |
| Debian 11          | 128       | 2.17%   |
| Pop!_OS 22.04      | 127       | 2.15%   |
| OpenMandriva 4.3   | 117       | 1.98%   |
| OpenMandriva 4.2   | 116       | 1.96%   |
| Linux Mint 20.3    | 115       | 1.95%   |
| Zorin 16           | 114       | 1.93%   |
| Manjaro            | 100       | 1.69%   |
| KDE neon 20.04     | 100       | 1.69%   |
| Xubuntu 20.04      | 97        | 1.64%   |
| Arch Rolling       | 95        | 1.61%   |
| Pop!_OS 20.04      | 88        | 1.49%   |
| Pop!_OS 21.04      | 84        | 1.42%   |
| ArcoLinux Rolling  | 80        | 1.35%   |
| Arch               | 80        | 1.35%   |
| Linux Mint 20.1    | 78        | 1.32%   |
| Linux Mint 19.3    | 76        | 1.29%   |
| Ubuntu 19.10       | 71        | 1.2%    |
| Zorin 15           | 69        | 1.17%   |
| Ubuntu 21.10       | 69        | 1.17%   |
| Fedora 35          | 68        | 1.15%   |
| OpenMandriva 23.01 | 67        | 1.13%   |
| Ubuntu 20.10       | 66        | 1.12%   |
| Linux Mint 21.1    | 66        | 1.12%   |
| Pop!_OS 20.10      | 65        | 1.1%    |
| Linux Mint 20.2    | 64        | 1.08%   |
| Fedora 33          | 64        | 1.08%   |
| Fedora 37          | 62        | 1.05%   |
| Linux Mint 20      | 60        | 1.01%   |
| Fedora 32          | 56        | 0.95%   |
| Ubuntu 21.04       | 53        | 0.9%    |
| Ubuntu 22.10       | 51        | 0.86%   |
| Fedora 34          | 50        | 0.85%   |
| Ubuntu 19.04       | 48        | 0.81%   |
| Pop!_OS 21.10      | 48        | 0.81%   |
| Fedora 36          | 48        | 0.81%   |
| OpenMandriva 23.03 | 47        | 0.79%   |
| Linux Mint 21      | 47        | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1850      | 33.02%  |
| Linux Mint    | 510       | 9.1%    |
| Pop!_OS       | 396       | 7.07%   |
| Fedora        | 383       | 6.84%   |
| OpenMandriva  | 369       | 6.59%   |
| Manjaro       | 214       | 3.82%   |
| Debian        | 204       | 3.64%   |
| Zorin         | 192       | 3.43%   |
| Arch          | 169       | 3.02%   |
| Xubuntu       | 152       | 2.71%   |
| KDE neon      | 130       | 2.32%   |
| Kubuntu       | 97        | 1.73%   |
| ArcoLinux     | 85        | 1.52%   |
| ROSA          | 76        | 1.36%   |
| Gentoo        | 59        | 1.05%   |
| Elementary    | 48        | 0.86%   |
| EndeavourOS   | 45        | 0.8%    |
| openSUSE      | 42        | 0.75%   |
| SteamOS       | 38        | 0.68%   |
| Lubuntu       | 36        | 0.64%   |
| Endless       | 35        | 0.62%   |
| Ubuntu MATE   | 31        | 0.55%   |
| Clear Linux   | 28        | 0.5%    |
| CentOS        | 28        | 0.5%    |
| BlackPanther  | 28        | 0.5%    |
| Kali          | 27        | 0.48%   |
| Ubuntu Unity  | 26        | 0.46%   |
| LMDE          | 24        | 0.43%   |
| MX            | 23        | 0.41%   |
| Ubuntu Budgie | 21        | 0.37%   |
| Garuda Linux  | 18        | 0.32%   |
| Nobara        | 16        | 0.29%   |
| Peppermint    | 11        | 0.2%    |
| LinuxFX       | 11        | 0.2%    |
| Parrot        | 10        | 0.18%   |
| Alpine        | 10        | 0.18%   |
| Rocky Linux   | 9         | 0.16%   |
| RHEL          | 9         | 0.16%   |
| Reborn OS     | 8         | 0.14%   |
| Raspbian      | 7         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 113       | 1.71%   |
| 5.16.7-desktop-1omv4003  | 110       | 1.67%   |
| 5.4.0-42-generic         | 92        | 1.39%   |
| 5.15.0-56-generic        | 68        | 1.03%   |
| 6.1.1-desktop-1omv2290   | 61        | 0.92%   |
| 5.11.0-27-generic        | 59        | 0.89%   |
| 5.15.0-58-generic        | 54        | 0.82%   |
| 5.4.0-58-generic         | 53        | 0.8%    |
| 5.4.0-48-generic         | 50        | 0.76%   |
| 5.3.0-40-generic         | 50        | 0.76%   |
| 5.15.0-52-generic        | 45        | 0.68%   |
| 6.2.6-desktop-1omv2390   | 44        | 0.67%   |
| 5.4.0-52-generic         | 44        | 0.67%   |
| 5.4.0-29-generic         | 43        | 0.65%   |
| 5.8.0-7630-generic       | 42        | 0.64%   |
| 5.11.0-40-generic        | 42        | 0.64%   |
| 5.4.0-40-generic         | 38        | 0.58%   |
| 5.0.0-37-generic         | 38        | 0.58%   |
| 5.4.0-26-generic         | 36        | 0.55%   |
| 5.13.0-39-generic        | 36        | 0.55%   |
| 5.4.0-54-generic         | 35        | 0.53%   |
| 5.3.0-46-generic         | 35        | 0.53%   |
| 5.15.0-48-generic        | 35        | 0.53%   |
| 5.15.0-47-generic        | 33        | 0.5%    |
| 5.15.0-41-generic        | 33        | 0.5%    |
| 5.11.0-7620-generic      | 33        | 0.5%    |
| 5.4.0-37-generic         | 32        | 0.49%   |
| 5.8.0-50-generic         | 31        | 0.47%   |
| 5.4.0-66-generic         | 30        | 0.45%   |
| 5.15.0-46-generic        | 30        | 0.45%   |
| 5.4.0-45-generic         | 29        | 0.44%   |
| 5.15.0-69-generic        | 28        | 0.42%   |
| 5.4.0-47-generic         | 27        | 0.41%   |
| 5.15.0-60-generic        | 27        | 0.41%   |
| 5.11.0-38-generic        | 27        | 0.41%   |
| 5.4.0-91-generic         | 26        | 0.39%   |
| 5.4.0-7634-generic       | 26        | 0.39%   |
| 5.4.0-56-generic         | 26        | 0.39%   |
| 5.4.0-33-generic         | 26        | 0.39%   |
| 5.3.0-42-generic         | 26        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1071      | 17.4%   |
| 5.15.0  | 494       | 8.02%   |
| 5.11.0  | 352       | 5.72%   |
| 5.8.0   | 337       | 5.47%   |
| 4.15.0  | 321       | 5.21%   |
| 5.13.0  | 317       | 5.15%   |
| 5.3.0   | 272       | 4.42%   |
| 5.19.0  | 162       | 2.63%   |
| 5.0.0   | 151       | 2.45%   |
| 5.10.0  | 136       | 2.21%   |
| 5.10.14 | 115       | 1.87%   |
| 5.16.7  | 112       | 1.82%   |
| 4.18.0  | 110       | 1.79%   |
| 6.1.1   | 69        | 1.12%   |
| 6.2.6   | 67        | 1.09%   |
| 4.19.0  | 43        | 0.7%    |
| 6.2.0   | 30        | 0.49%   |
| 6.0.12  | 29        | 0.47%   |
| 5.14.0  | 28        | 0.45%   |
| 6.0.6   | 27        | 0.44%   |
| 6.0.0   | 27        | 0.44%   |
| 5.17.5  | 26        | 0.42%   |
| 5.15.5  | 23        | 0.37%   |
| 4.18.16 | 23        | 0.37%   |
| 4.9.20  | 20        | 0.32%   |
| 4.4.0   | 18        | 0.29%   |
| 6.2.9   | 17        | 0.28%   |
| 4.9.60  | 17        | 0.28%   |
| 5.12.4  | 16        | 0.26%   |
| 6.1.0   | 15        | 0.24%   |
| 5.18.0  | 15        | 0.24%   |
| 5.16.0  | 15        | 0.24%   |
| 5.15.11 | 15        | 0.24%   |
| 6.2.10  | 14        | 0.23%   |
| 5.9.16  | 14        | 0.23%   |
| 5.9.11  | 14        | 0.23%   |
| 5.17.9  | 14        | 0.23%   |
| 5.7.0   | 13        | 0.21%   |
| 5.16.13 | 13        | 0.21%   |
| 3.10.0  | 13        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1161      | 19.2%   |
| 5.15    | 681       | 11.26%  |
| 5.8     | 431       | 7.13%   |
| 5.11    | 407       | 6.73%   |
| 5.13    | 372       | 6.15%   |
| 5.10    | 357       | 5.9%    |
| 4.15    | 322       | 5.32%   |
| 5.3     | 294       | 4.86%   |
| 5.19    | 220       | 3.64%   |
| 5.16    | 218       | 3.6%    |
| 6.2     | 183       | 3.03%   |
| 5.0     | 160       | 2.65%   |
| 6.1     | 159       | 2.63%   |
| 6.0     | 150       | 2.48%   |
| 4.18    | 133       | 2.2%    |
| 5.17    | 97        | 1.6%    |
| 5.9     | 84        | 1.39%   |
| 5.14    | 82        | 1.36%   |
| 5.18    | 74        | 1.22%   |
| 5.12    | 72        | 1.19%   |
| 4.9     | 66        | 1.09%   |
| 5.6     | 61        | 1.01%   |
| 4.19    | 58        | 0.96%   |
| 5.7     | 51        | 0.84%   |
| 6.3     | 45        | 0.74%   |
| 5.5     | 29        | 0.48%   |
| 4.4     | 22        | 0.36%   |
| 3.10    | 16        | 0.26%   |
| 5.2     | 11        | 0.18%   |
| 4.1     | 6         | 0.1%    |
| 4.13    | 5         | 0.08%   |
| 5.1     | 4         | 0.07%   |
| 4.14    | 3         | 0.05%   |
| 4.8     | 2         | 0.03%   |
| 4.20    | 2         | 0.03%   |
| 4.16    | 2         | 0.03%   |
| 4.12    | 2         | 0.03%   |
| Unknown | 2         | 0.03%   |
| 5       | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5182      | 96.72%  |
| i686    | 114       | 2.13%   |
| aarch64 | 39        | 0.73%   |
| armv7l  | 19        | 0.35%   |
| mips64  | 2         | 0.04%   |
| armv8l  | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| GNOME                | 2474      | 43.9%   |
| KDE5                 | 906       | 16.08%  |
| Unknown              | 723       | 12.83%  |
| X-Cinnamon           | 413       | 7.33%   |
| XFCE                 | 399       | 7.08%   |
| KDE                  | 146       | 2.59%   |
| MATE                 | 128       | 2.27%   |
| Cinnamon             | 72        | 1.28%   |
| KDE4                 | 57        | 1.01%   |
| Pantheon             | 46        | 0.82%   |
| LXQt                 | 44        | 0.78%   |
| i3                   | 39        | 0.69%   |
| Budgie               | 33        | 0.59%   |
| LXDE                 | 30        | 0.53%   |
| Unity                | 29        | 0.51%   |
| GNOME Flashback      | 20        | 0.35%   |
| Deepin               | 13        | 0.23%   |
| GNOME Classic        | 8         | 0.14%   |
| qtile                | 7         | 0.12%   |
| DWM                  | 7         | 0.12%   |
| awesome              | 7         | 0.12%   |
| sway                 | 5         | 0.09%   |
| Openbox              | 4         | 0.07%   |
| Enlightenment        | 4         | 0.07%   |
| xmonad               | 3         | 0.05%   |
| Hyprland             | 3         | 0.05%   |
| chadwm               | 2         | 0.04%   |
| bspwm                | 2         | 0.04%   |
| xsession             | 1         | 0.02%   |
| wmaker-common        | 1         | 0.02%   |
| ubuntustudio         | 1         | 0.02%   |
| trinity              | 1         | 0.02%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.02%   |
| spectrwm             | 1         | 0.02%   |
| river                | 1         | 0.02%   |
| Lubuntu              | 1         | 0.02%   |
| lightdm-xsession     | 1         | 0.02%   |
| LeftWM               | 1         | 0.02%   |
| Jwm                  | 1         | 0.02%   |
| GNOME-Classic        | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4257      | 77.08%  |
| Wayland | 765       | 13.85%  |
| Unknown | 359       | 6.5%    |
| Tty     | 137       | 2.48%   |
| Web     | 5         | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3019      | 53.96%  |
| SDDM    | 783       | 13.99%  |
| GDM     | 573       | 10.24%  |
| GDM3    | 535       | 9.56%   |
| LightDM | 458       | 8.19%   |
| TDM     | 142       | 2.54%   |
| KDM     | 51        | 0.91%   |
| XDM     | 13        | 0.23%   |
| SLiM    | 7         | 0.13%   |
| Ly      | 6         | 0.11%   |
| LXDM    | 4         | 0.07%   |
| GREETD  | 2         | 0.04%   |
| NODM    | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_CA      | 2861      | 51.49%  |
| en_US      | 1462      | 26.31%  |
| Unknown    | 578       | 10.4%   |
| fr_CA      | 376       | 6.77%   |
| C          | 122       | 2.2%    |
| fr_FR      | 54        | 0.97%   |
| en_GB      | 31        | 0.56%   |
| en_AU      | 9         | 0.16%   |
| POSIX      | 8         | 0.14%   |
| C.UTF8     | 6         | 0.11%   |
| zh_CN      | 4         | 0.07%   |
| pt_BR      | 4         | 0.07%   |
| es_ES      | 4         | 0.07%   |
| en_IN      | 4         | 0.07%   |
| uk_UA      | 3         | 0.05%   |
| ru_RU      | 3         | 0.05%   |
| pa_IN      | 3         | 0.05%   |
| de_DE      | 3         | 0.05%   |
| zh_TW      | 2         | 0.04%   |
| pl_PL      | 2         | 0.04%   |
| hu_HU      | 2         | 0.04%   |
| ro_RO      | 1         | 0.02%   |
| nan_TW     | 1         | 0.02%   |
| iu_CA      | 1         | 0.02%   |
| hr_HR      | 1         | 0.02%   |
| ga_IE      | 1         | 0.02%   |
| es_CL      | 1         | 0.02%   |
| es_BO      | 1         | 0.02%   |
| en_ZM      | 1         | 0.02%   |
| en_ZA      | 1         | 0.02%   |
| en_US.UTF8 | 1         | 0.02%   |
| en_NZ      | 1         | 0.02%   |
| en_IE      | 1         | 0.02%   |
| en_FI      | 1         | 0.02%   |
| de_CH      | 1         | 0.02%   |
| co_FR      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2961      | 53.81%  |
| EFI  | 2542      | 46.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 4132      | 74.98%  |
| Btrfs   | 507       | 9.2%    |
| Overlay | 454       | 8.24%   |
| Unknown | 177       | 3.21%   |
| Xfs     | 95        | 1.72%   |
| Zfs     | 54        | 0.98%   |
| Tmpfs   | 42        | 0.76%   |
| Ext2    | 19        | 0.34%   |
| Ext3    | 10        | 0.18%   |
| F2fs    | 9         | 0.16%   |
| Aufs    | 8         | 0.15%   |
| Jfs     | 2         | 0.04%   |
| XXX4    | 1         | 0.02%   |
| Rootfs  | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3088      | 56.06%  |
| GPT     | 1874      | 34.02%  |
| MBR     | 546       | 9.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4588      | 83.62%  |
| Yes       | 899       | 16.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4012      | 73.36%  |
| Yes       | 1457      | 26.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1007      | 18.82%  |
| Dell                    | 784       | 14.65%  |
| Lenovo                  | 707       | 13.21%  |
| Hewlett-Packard         | 655       | 12.24%  |
| Acer                    | 391       | 7.31%   |
| MSI                     | 336       | 6.28%   |
| Gigabyte Technology     | 327       | 6.11%   |
| Apple                   | 188       | 3.51%   |
| ASRock                  | 141       | 2.63%   |
| Toshiba                 | 99        | 1.85%   |
| Intel                   | 79        | 1.48%   |
| Alienware               | 39        | 0.73%   |
| Raspberry Pi Foundation | 36        | 0.67%   |
| Sony                    | 35        | 0.65%   |
| Unknown                 | 35        | 0.65%   |
| Valve                   | 33        | 0.62%   |
| Microsoft               | 32        | 0.6%    |
| Pegatron                | 30        | 0.56%   |
| Supermicro              | 29        | 0.54%   |
| Google                  | 29        | 0.54%   |
| Gateway                 | 29        | 0.54%   |
| Samsung Electronics     | 27        | 0.5%    |
| Foxconn                 | 26        | 0.49%   |
| System76                | 19        | 0.36%   |
| Panasonic               | 18        | 0.34%   |
| ECS                     | 12        | 0.22%   |
| AZW                     | 12        | 0.22%   |
| Biostar                 | 11        | 0.21%   |
| ZOTAC                   | 9         | 0.17%   |
| Razer                   | 8         | 0.15%   |
| Fujitsu                 | 8         | 0.15%   |
| Framework               | 6         | 0.11%   |
| ASRockRack              | 6         | 0.11%   |
| Notebook                | 5         | 0.09%   |
| HUAWEI                  | 5         | 0.09%   |
| Fanless Mini PC         | 5         | 0.09%   |
| EVGA                    | 5         | 0.09%   |
| eMachines               | 5         | 0.09%   |
| AMI                     | 5         | 0.09%   |
| TYAN Computer           | 4         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 63        | 1.18%   |
| Unknown                            | 47        | 0.88%   |
| Valve Jupiter                      | 33        | 0.62%   |
| ASUS TUF Gaming X570-PLUS          | 23        | 0.43%   |
| HP Notebook                        | 22        | 0.41%   |
| HP Pavilion g6                     | 18        | 0.34%   |
| Acer Aspire A315-21                | 15        | 0.28%   |
| MSI MS-7C37                        | 14        | 0.26%   |
| ASUS PRIME B450M-A                 | 14        | 0.26%   |
| MSI MS-7C02                        | 13        | 0.24%   |
| Dell XPS 15 7590                   | 13        | 0.24%   |
| Dell OptiPlex 790                  | 13        | 0.24%   |
| Dell Latitude E6420                | 13        | 0.24%   |
| Dell Latitude E6410                | 13        | 0.24%   |
| ASRock B450M Pro4                  | 13        | 0.24%   |
| HP Z400 Workstation                | 12        | 0.22%   |
| HP Pavilion dv6                    | 12        | 0.22%   |
| Dell XPS 15 9500                   | 12        | 0.22%   |
| Apple MacBookPro8,1                | 12        | 0.22%   |
| RPi Raspberry Pi                   | 11        | 0.21%   |
| HP Pavilion 15                     | 11        | 0.21%   |
| Dell OptiPlex 7010                 | 11        | 0.21%   |
| Apple MacBookPro9,2                | 11        | 0.21%   |
| Apple iMac8,1                      | 11        | 0.21%   |
| MSI MS-7C95                        | 10        | 0.19%   |
| MSI MS-7C84                        | 10        | 0.19%   |
| MSI MS-7C56                        | 10        | 0.19%   |
| HP EliteBook 8460p                 | 10        | 0.19%   |
| Dell OptiPlex 9020                 | 10        | 0.19%   |
| Dell OptiPlex 780                  | 10        | 0.19%   |
| ASUS TP410UAR                      | 10        | 0.19%   |
| ASUS ROG STRIX B450-F GAMING       | 10        | 0.19%   |
| ASUS M5A97 LE R2.0                 | 10        | 0.19%   |
| Apple iMac7,1                      | 10        | 0.19%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 9         | 0.17%   |
| MSI MS-7693                        | 9         | 0.17%   |
| HP Pavilion Notebook               | 9         | 0.17%   |
| Gigabyte B450 AORUS PRO WIFI       | 9         | 0.17%   |
| ASUS M5A99FX PRO R2.0              | 9         | 0.17%   |
| ASUS M5A97 R2.0                    | 9         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 354       | 6.61%   |
| Acer Aspire         | 306       | 5.72%   |
| Dell Latitude       | 170       | 3.18%   |
| Dell Inspiron       | 166       | 3.1%    |
| Dell XPS            | 141       | 2.63%   |
| Dell OptiPlex       | 128       | 2.39%   |
| HP Pavilion         | 123       | 2.3%    |
| ASUS PRIME          | 123       | 2.3%    |
| ASUS ROG            | 120       | 2.24%   |
| Lenovo ThinkCentre  | 114       | 2.13%   |
| HP Compaq           | 88        | 1.64%   |
| Lenovo IdeaPad      | 86        | 1.61%   |
| Toshiba Satellite   | 84        | 1.57%   |
| HP EliteBook        | 83        | 1.55%   |
| ASUS All            | 63        | 1.18%   |
| Dell Precision      | 62        | 1.16%   |
| ASUS TUF            | 61        | 1.14%   |
| ASUS VivoBook       | 60        | 1.12%   |
| HP Laptop           | 52        | 0.97%   |
| Unknown             | 47        | 0.88%   |
| HP ENVY             | 43        | 0.8%    |
| HP ProBook          | 41        | 0.77%   |
| RPi Raspberry       | 36        | 0.67%   |
| Valve Jupiter       | 33        | 0.62%   |
| Microsoft Surface   | 32        | 0.6%    |
| Dell Vostro         | 32        | 0.6%    |
| Gigabyte X570       | 31        | 0.58%   |
| Dell Studio         | 27        | 0.5%    |
| HP EliteDesk        | 25        | 0.47%   |
| ASUS Zenbook        | 25        | 0.47%   |
| ASUS M5A97          | 24        | 0.45%   |
| HP Notebook         | 22        | 0.41%   |
| Acer Swift          | 22        | 0.41%   |
| Lenovo Yoga         | 21        | 0.39%   |
| Lenovo Legion       | 21        | 0.39%   |
| Gigabyte B450       | 21        | 0.39%   |
| Lenovo ThinkStation | 20        | 0.37%   |
| Dell PowerEdge      | 20        | 0.37%   |
| ASRock B450M        | 20        | 0.37%   |
| Acer Nitro          | 20        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 476       | 8.89%   |
| 2012    | 461       | 8.61%   |
| 2020    | 460       | 8.59%   |
| 2019    | 445       | 8.31%   |
| 2011    | 438       | 8.18%   |
| 2013    | 383       | 7.16%   |
| 2017    | 345       | 6.45%   |
| 2010    | 310       | 5.79%   |
| 2014    | 306       | 5.72%   |
| 2008    | 259       | 4.84%   |
| 2021    | 254       | 4.75%   |
| 2016    | 245       | 4.58%   |
| 2015    | 228       | 4.26%   |
| 2009    | 228       | 4.26%   |
| 2022    | 197       | 3.68%   |
| 2007    | 165       | 3.08%   |
| 2006    | 68        | 1.27%   |
| Unknown | 44        | 0.82%   |
| 2005    | 22        | 0.41%   |
| 2023    | 12        | 0.22%   |
| 2004    | 6         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2474      | 46.23%  |
| Desktop        | 2400      | 44.84%  |
| Convertible    | 148       | 2.77%   |
| All in one     | 102       | 1.91%   |
| Mini pc        | 67        | 1.25%   |
| Server         | 63        | 1.18%   |
| System on chip | 50        | 0.93%   |
| Tablet         | 45        | 0.84%   |
| Phone          | 3         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5053      | 93.7%   |
| Enabled  | 340       | 6.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5307      | 99.12%  |
| Yes  | 47        | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1177      | 21.61%  |
| 4.01-8.0        | 1157      | 21.24%  |
| 8.01-16.0       | 994       | 18.25%  |
| 3.01-4.0        | 833       | 15.3%   |
| 32.01-64.0      | 655       | 12.03%  |
| 1.01-2.0        | 198       | 3.64%   |
| 64.01-256.0     | 193       | 3.54%   |
| 24.01-32.0      | 109       | 2%      |
| 2.01-3.0        | 72        | 1.32%   |
| 0.51-1.0        | 37        | 0.68%   |
| More than 256.0 | 11        | 0.2%    |
| 0.01-0.5        | 8         | 0.15%   |
| Unknown         | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2059      | 34.25%  |
| 2.01-3.0        | 1458      | 24.25%  |
| 4.01-8.0        | 927       | 15.42%  |
| 3.01-4.0        | 769       | 12.79%  |
| 0.51-1.0        | 366       | 6.09%   |
| 8.01-16.0       | 260       | 4.32%   |
| 0.01-0.5        | 91        | 1.51%   |
| 16.01-24.0      | 26        | 0.43%   |
| 32.01-64.0      | 23        | 0.38%   |
| 24.01-32.0      | 23        | 0.38%   |
| 64.01-256.0     | 5         | 0.08%   |
| Unknown         | 4         | 0.07%   |
| More than 256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3129      | 55.95%  |
| 2       | 1310      | 23.43%  |
| 3       | 488       | 8.73%   |
| 4       | 285       | 5.1%    |
| 5       | 143       | 2.56%   |
| 6       | 72        | 1.29%   |
| 0       | 55        | 0.98%   |
| 7       | 39        | 0.7%    |
| 8       | 24        | 0.43%   |
| 9       | 13        | 0.23%   |
| 11      | 8         | 0.14%   |
| 10      | 8         | 0.14%   |
| 12      | 5         | 0.09%   |
| 13      | 4         | 0.07%   |
| Unknown | 4         | 0.07%   |
| 14      | 2         | 0.04%   |
| 26      | 1         | 0.02%   |
| 19      | 1         | 0.02%   |
| 16      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3110      | 57.48%  |
| Yes       | 2301      | 42.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4676      | 87.13%  |
| No        | 691       | 12.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3993      | 74.03%  |
| No        | 1401      | 25.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3084      | 56.69%  |
| No        | 2356      | 43.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Canada  | 5352      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Toronto         | 545       | 9.65%   |
| Montreal        | 533       | 9.44%   |
| Vancouver       | 238       | 4.22%   |
| Calgary         | 225       | 3.99%   |
| Ottawa          | 202       | 3.58%   |
| Edmonton        | 180       | 3.19%   |
| Québec         | 117       | 2.07%   |
| Winnipeg        | 115       | 2.04%   |
| Mississauga     | 82        | 1.45%   |
| Victoria        | 79        | 1.4%    |
| Surrey          | 67        | 1.19%   |
| Brampton        | 61        | 1.08%   |
| London          | 58        | 1.03%   |
| Laval           | 58        | 1.03%   |
| Regina          | 57        | 1.01%   |
| Kitchener       | 56        | 0.99%   |
| Saskatoon       | 49        | 0.87%   |
| Hamilton        | 49        | 0.87%   |
| Burnaby         | 49        | 0.87%   |
| Gatineau        | 46        | 0.81%   |
| Windsor         | 44        | 0.78%   |
| Halifax         | 41        | 0.73%   |
| Oshawa          | 40        | 0.71%   |
| Scarborough     | 39        | 0.69%   |
| Sherbrooke      | 35        | 0.62%   |
| Kingston        | 35        | 0.62%   |
| Richmond Hill   | 31        | 0.55%   |
| Trois-Rivières | 29        | 0.51%   |
| New Westminster | 29        | 0.51%   |
| Markham         | 29        | 0.51%   |
| Moncton         | 28        | 0.5%    |
| Barrie          | 27        | 0.48%   |
| Oakville        | 26        | 0.46%   |
| North Vancouver | 25        | 0.44%   |
| Kelowna         | 24        | 0.43%   |
| Waterloo        | 23        | 0.41%   |
| Fredericton     | 23        | 0.41%   |
| Red Deer        | 22        | 0.39%   |
| Dartmouth       | 22        | 0.39%   |
| Burlington      | 22        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 1484      | 2488   | 18.08%  |
| Seagate                     | 1448      | 2557   | 17.64%  |
| Samsung Electronics         | 1149      | 1823   | 14%     |
| Kingston                    | 512       | 704    | 6.24%   |
| Toshiba                     | 429       | 558    | 5.23%   |
| SanDisk                     | 389       | 504    | 4.74%   |
| Unknown                     | 345       | 474    | 4.2%    |
| Hitachi                     | 275       | 383    | 3.35%   |
| Intel                       | 244       | 370    | 2.97%   |
| Crucial                     | 228       | 324    | 2.78%   |
| A-DATA Technology           | 188       | 252    | 2.29%   |
| SK hynix                    | 171       | 210    | 2.08%   |
| HGST                        | 134       | 173    | 1.63%   |
| Micron Technology           | 88        | 124    | 1.07%   |
| Apple                       | 63        | 79     | 0.77%   |
| Phison                      | 57        | 84     | 0.69%   |
| SPCC                        | 44        | 61     | 0.54%   |
| Fujitsu                     | 43        | 56     | 0.52%   |
| OCZ                         | 39        | 51     | 0.48%   |
| KIOXIA                      | 39        | 44     | 0.48%   |
| Silicon Motion              | 34        | 57     | 0.41%   |
| PNY                         | 33        | 49     | 0.4%    |
| Corsair                     | 33        | 40     | 0.4%    |
| China                       | 33        | 37     | 0.4%    |
| Micron/Crucial Technology   | 31        | 48     | 0.38%   |
| LITEONIT                    | 31        | 35     | 0.38%   |
| Phison Electronics          | 25        | 30     | 0.3%    |
| Mushkin                     | 24        | 29     | 0.29%   |
| ASMT                        | 24        | 29     | 0.29%   |
| Patriot                     | 23        | 27     | 0.28%   |
| JMicron Technology          | 23        | 31     | 0.28%   |
| LITEON                      | 22        | 24     | 0.27%   |
| Team                        | 21        | 28     | 0.26%   |
| Unknown                     | 21        | 21     | 0.26%   |
| XPG                         | 20        | 29     | 0.24%   |
| Kingston Technology Company | 20        | 21     | 0.24%   |
| Hewlett-Packard             | 19        | 30     | 0.23%   |
| KingFast                    | 18        | 21     | 0.22%   |
| Maxtor                      | 17        | 23     | 0.21%   |
| SABRENT                     | 15        | 20     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 124       | 1.32%   |
| Samsung SSD 850 EVO 250GB                           | 88        | 0.94%   |
| Samsung SSD 860 EVO 500GB                           | 85        | 0.91%   |
| Seagate ST2000DM008-2FR102 2TB                      | 71        | 0.76%   |
| Samsung SSD 850 EVO 500GB                           | 65        | 0.69%   |
| Kingston SA400S37120G 120GB SSD                     | 64        | 0.68%   |
| Seagate ST1000DM010-2EP102 1TB                      | 59        | 0.63%   |
| Samsung SSD 860 EVO 1TB                             | 59        | 0.63%   |
| Kingston SA400S37480G 480GB SSD                     | 58        | 0.62%   |
| Unknown MMC Card  32GB                              | 55        | 0.59%   |
| Samsung NVMe SSD Drive 500GB                        | 54        | 0.58%   |
| Seagate ST4000DM004-2CV104 4TB                      | 53        | 0.57%   |
| SanDisk NVMe SSD Drive 500GB                        | 53        | 0.57%   |
| Unknown MMC Card  64GB                              | 52        | 0.55%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 51        | 0.54%   |
| Toshiba MQ01ABD100 1TB                              | 51        | 0.54%   |
| Unknown SD/MMC/MS PRO 64GB                          | 50        | 0.53%   |
| SanDisk NVMe SSD Drive 1TB                          | 49        | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB                      | 47        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 45        | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 44        | 0.47%   |
| Seagate ST500DM002-1BD142 500GB                     | 44        | 0.47%   |
| Samsung SSD 860 EVO 250GB                           | 44        | 0.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 44        | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                    | 44        | 0.47%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 43        | 0.46%   |
| Seagate ST1000LX015-1U7172 1TB                      | 43        | 0.46%   |
| Seagate ST2000DM006-2DM164 2TB                      | 41        | 0.44%   |
| Seagate ST2000DM001-1ER164 2TB                      | 41        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 40        | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB                      | 38        | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB                      | 37        | 0.39%   |
| Seagate Expansion Desk 4TB                          | 37        | 0.39%   |
| HGST HTS721010A9E630 1TB                            | 37        | 0.39%   |
| Toshiba DT01ACA200 2TB                              | 36        | 0.38%   |
| Seagate Expansion 1TB                               | 33        | 0.35%   |
| Toshiba DT01ACA100 1TB                              | 32        | 0.34%   |
| Seagate ST3500418AS 500GB                           | 32        | 0.34%   |
| Kingston SV300S37A240G 240GB SSD                    | 32        | 0.34%   |
| Seagate ST31000528AS 1TB                            | 30        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1399      | 2450   | 39.12%  |
| WDC                 | 1175      | 1971   | 32.86%  |
| Toshiba             | 345       | 457    | 9.65%   |
| Hitachi             | 275       | 383    | 7.69%   |
| HGST                | 134       | 173    | 3.75%   |
| Samsung Electronics | 56        | 76     | 1.57%   |
| Unknown             | 50        | 68     | 1.4%    |
| Fujitsu             | 43        | 56     | 1.2%    |
| Apple               | 24        | 26     | 0.67%   |
| Maxtor              | 17        | 23     | 0.48%   |
| External            | 14        | 21     | 0.39%   |
| ASMT                | 7         | 9      | 0.2%    |
| Maxone              | 6         | 8      | 0.17%   |
| JMicron Technology  | 5         | 8      | 0.14%   |
| QNAP                | 3         | 8      | 0.08%   |
| USB 3.0             | 2         | 6      | 0.06%   |
| SABRENT             | 2         | 2      | 0.06%   |
| Hewlett-Packard     | 2         | 9      | 0.06%   |
| DAS                 | 2         | 14     | 0.06%   |
| USB3.0              | 1         | 2      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| Maxtor 6            | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| KESU                | 1         | 2      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| DellEMC             | 1         | 8      | 0.03%   |
| DELLBOSS            | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 669       | 1014   | 25.09%  |
| Kingston            | 437       | 599    | 16.39%  |
| WDC                 | 229       | 324    | 8.59%   |
| Crucial             | 205       | 283    | 7.69%   |
| SanDisk             | 168       | 201    | 6.3%    |
| A-DATA Technology   | 165       | 223    | 6.19%   |
| Intel               | 107       | 145    | 4.01%   |
| Micron Technology   | 52        | 78     | 1.95%   |
| SPCC                | 40        | 57     | 1.5%    |
| OCZ                 | 38        | 47     | 1.43%   |
| Seagate             | 34        | 51     | 1.28%   |
| PNY                 | 33        | 49     | 1.24%   |
| China               | 33        | 37     | 1.24%   |
| Apple               | 33        | 39     | 1.24%   |
| SK hynix            | 32        | 40     | 1.2%    |
| LITEONIT            | 31        | 35     | 1.16%   |
| Toshiba             | 28        | 33     | 1.05%   |
| Patriot             | 23        | 27     | 0.86%   |
| Mushkin             | 22        | 27     | 0.83%   |
| Team                | 20        | 27     | 0.75%   |
| Corsair             | 20        | 23     | 0.75%   |
| LITEON              | 18        | 19     | 0.68%   |
| ASMT                | 15        | 18     | 0.56%   |
| Dogfish             | 14        | 18     | 0.53%   |
| TO Exter            | 13        | 15     | 0.49%   |
| SABRENT             | 12        | 17     | 0.45%   |
| Hewlett-Packard     | 11        | 14     | 0.41%   |
| OWC                 | 10        | 21     | 0.38%   |
| Lexar               | 9         | 11     | 0.34%   |
| NGFF                | 8         | 9      | 0.3%    |
| KingFast            | 8         | 8      | 0.3%    |
| JMicron Technology  | 8         | 11     | 0.3%    |
| Transcend           | 7         | 8      | 0.26%   |
| KingSpec            | 7         | 9      | 0.26%   |
| KingDian            | 7         | 7      | 0.26%   |
| Timetec             | 5         | 13     | 0.19%   |
| TCSUNBOW            | 5         | 6      | 0.19%   |
| T-FORCE             | 5         | 6      | 0.19%   |
| WDC WDS             | 4         | 5      | 0.15%   |
| Unknown             | 4         | 4      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2941      | 5792   | 40.9%   |
| SSD     | 2267      | 3672   | 31.53%  |
| NVMe    | 1554      | 2385   | 21.61%  |
| MMC     | 286       | 389    | 3.98%   |
| Unknown | 143       | 192    | 1.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4165      | 8907   | 64.32%  |
| NVMe | 1551      | 2373   | 23.95%  |
| SAS  | 473       | 761    | 7.31%   |
| MMC  | 286       | 389    | 4.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2973      | 4764   | 51.85%  |
| 0.51-1.0   | 1654      | 2643   | 28.85%  |
| 1.01-2.0   | 554       | 980    | 9.66%   |
| 3.01-4.0   | 212       | 377    | 3.7%    |
| 4.01-10.0  | 169       | 376    | 2.95%   |
| 2.01-3.0   | 146       | 276    | 2.55%   |
| 10.01-20.0 | 26        | 48     | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1318      | 22.87%  |
| 251-500        | 1241      | 21.54%  |
| 501-1000       | 905       | 15.71%  |
| 1001-2000      | 493       | 8.56%   |
| 1-20           | 448       | 7.78%   |
| More than 3000 | 428       | 7.43%   |
| 51-100         | 304       | 5.28%   |
| 21-50          | 214       | 3.71%   |
| Unknown        | 212       | 3.68%   |
| 2001-3000      | 199       | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2312      | 38.64%  |
| 21-50          | 999       | 16.69%  |
| 101-250        | 674       | 11.26%  |
| 51-100         | 623       | 10.41%  |
| 251-500        | 418       | 6.99%   |
| 501-1000       | 295       | 4.93%   |
| Unknown        | 212       | 3.54%   |
| 1001-2000      | 210       | 3.51%   |
| More than 3000 | 157       | 2.62%   |
| 2001-3000      | 83        | 1.39%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 8         | 9      | 1.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 8         | 9      | 1.56%   |
| Toshiba MQ01ABD100 1TB              | 6         | 8      | 1.17%   |
| Seagate ST9500325AS 500GB           | 6         | 6      | 1.17%   |
| Seagate ST500LM000-1EJ162 500GB     | 6         | 6      | 1.17%   |
| Seagate ST31000528AS 1TB            | 6         | 8      | 1.17%   |
| WDC WD2500HHTZ-04N21V0 250GB        | 5         | 5      | 0.98%   |
| WDC WD20EARS-00MVWB0 2TB            | 5         | 6      | 0.98%   |
| Seagate ST9500420AS 500GB           | 5         | 5      | 0.98%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 0.98%   |
| Seagate ST500LM021-1KJ152 500GB     | 5         | 13     | 0.98%   |
| Seagate ST3500418AS 500GB           | 5         | 6      | 0.98%   |
| Kingston SV300S37A120G 120GB SSD    | 5         | 7      | 0.98%   |
| HGST HTS725050A7E630 500GB          | 5         | 6      | 0.98%   |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 0.98%   |
| WDC WD40EFRX-68WT0N0 4TB            | 4         | 17     | 0.78%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 5      | 0.78%   |
| Seagate ST31500341AS 1TB            | 4         | 4      | 0.78%   |
| Samsung Electronics SSD 870 EVO 1TB | 4         | 5      | 0.78%   |
| Intel SSDSA1M080G2LE 80GB           | 4         | 4      | 0.78%   |
| Hitachi HDS721010CLA332 1TB         | 4         | 4      | 0.78%   |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 0.78%   |
| HGST HTS545050A7E680 500GB          | 4         | 4      | 0.78%   |
| WDC WD6400AAKS-22A7B2 640GB         | 3         | 3      | 0.59%   |
| WDC WD30EFRX-68EUZN0 3TB            | 3         | 4      | 0.59%   |
| WDC WD10EARX-00N0YB0 1TB            | 3         | 4      | 0.59%   |
| Toshiba MK3261GSYN 320GB            | 3         | 3      | 0.59%   |
| Toshiba MK2555GSXF 250GB            | 3         | 3      | 0.59%   |
| Seagate ST9320325AS 320GB           | 3         | 6      | 0.59%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 3      | 0.59%   |
| Seagate ST1000LX015-1U7172 1TB      | 3         | 4      | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 3      | 0.59%   |
| Seagate ST1000DM003-1ER162 1TB      | 3         | 4      | 0.59%   |
| Crucial CT1000P1SSD8 1TB            | 3         | 9      | 0.59%   |
| A-DATA Technology SX900 256GB SSD   | 3         | 3      | 0.59%   |
| WDC WD6400AAKS-65Z7B0 640GB         | 2         | 3      | 0.39%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 2         | 2      | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.39%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2         | 2      | 0.39%   |
| WDC WD30EZRX-00MMMB0 3TB            | 2         | 6      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 158       | 218    | 32.11%  |
| WDC                   | 124       | 169    | 25.2%   |
| Hitachi               | 40        | 42     | 8.13%   |
| Toshiba               | 33        | 35     | 6.71%   |
| Samsung Electronics   | 29        | 41     | 5.89%   |
| HGST                  | 19        | 20     | 3.86%   |
| Kingston              | 18        | 24     | 3.66%   |
| Intel                 | 15        | 17     | 3.05%   |
| Crucial               | 10        | 17     | 2.03%   |
| A-DATA Technology     | 10        | 11     | 2.03%   |
| SK hynix              | 3         | 3      | 0.61%   |
| Mushkin               | 3         | 3      | 0.61%   |
| LITEONIT              | 3         | 3      | 0.61%   |
| Fujitsu               | 3         | 6      | 0.61%   |
| Apple                 | 3         | 3      | 0.61%   |
| Sandisk               | 2         | 2      | 0.41%   |
| OCZ                   | 2         | 2      | 0.41%   |
| Maxtor                | 2         | 2      | 0.41%   |
| KingSpec              | 2         | 2      | 0.41%   |
| Hewlett-Packard       | 2         | 2      | 0.41%   |
| ASMT                  | 2         | 3      | 0.41%   |
| Super Talent          | 1         | 1      | 0.2%    |
| Realtek Semiconductor | 1         | 1      | 0.2%    |
| Micron Technology     | 1         | 1      | 0.2%    |
| LITEON                | 1         | 1      | 0.2%    |
| LaCie                 | 1         | 1      | 0.2%    |
| Drevo                 | 1         | 1      | 0.2%    |
| DAS                   | 1         | 3      | 0.2%    |
| Corsair               | 1         | 1      | 0.2%    |
| China                 | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 158       | 218    | 40.62%  |
| WDC                 | 124       | 169    | 31.88%  |
| Hitachi             | 40        | 42     | 10.28%  |
| Toshiba             | 31        | 33     | 7.97%   |
| HGST                | 19        | 20     | 4.88%   |
| Samsung Electronics | 8         | 16     | 2.06%   |
| Fujitsu             | 3         | 6      | 0.77%   |
| Maxtor              | 2         | 2      | 0.51%   |
| Apple               | 2         | 2      | 0.51%   |
| LaCie               | 1         | 1      | 0.26%   |
| DAS                 | 1         | 3      | 0.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 363       | 512    | 77.9%   |
| SSD  | 85        | 98     | 18.24%  |
| NVMe | 18        | 26     | 3.86%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2003FYYS-18W0B0 2TB         | 1         | 1      | 20%     |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 20%     |
| LITEON CA3-8D512 512GB            | 1         | 2      | 20%     |
| Intel SSDSA1M160G2HP 160GB        | 1         | 1      | 20%     |
| Hewlett-Packard EF0450FARMV 450GB | 1         | 4      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| LITEON              | 1         | 2      | 20%     |
| Intel               | 1         | 1      | 20%     |
| Hewlett-Packard     | 1         | 4      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3509      | 7889   | 59.62%  |
| Works    | 1922      | 3896   | 32.65%  |
| Malfunc  | 450       | 636    | 7.65%   |
| Failed   | 5         | 9      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3420      | 49.54%  |
| AMD                              | 1244      | 18.02%  |
| Samsung Electronics              | 551       | 7.98%   |
| SanDisk                          | 366       | 5.3%    |
| ASMedia Technology               | 161       | 2.33%   |
| SK hynix                         | 135       | 1.96%   |
| Marvell Technology Group         | 131       | 1.9%    |
| Nvidia                           | 116       | 1.68%   |
| JMicron Technology               | 96        | 1.39%   |
| Kingston Technology Company      | 95        | 1.38%   |
| Phison Electronics               | 93        | 1.35%   |
| Toshiba America Info Systems     | 59        | 0.85%   |
| Micron/Crucial Technology        | 54        | 0.78%   |
| ADATA Technology                 | 52        | 0.75%   |
| Silicon Motion                   | 46        | 0.67%   |
| LSI Logic / Symbios Logic        | 42        | 0.61%   |
| KIOXIA                           | 41        | 0.59%   |
| Micron Technology                | 38        | 0.55%   |
| Broadcom / LSI                   | 29        | 0.42%   |
| Realtek Semiconductor            | 17        | 0.25%   |
| Silicon Image                    | 16        | 0.23%   |
| Seagate Technology               | 16        | 0.23%   |
| VIA Technologies                 | 11        | 0.16%   |
| Union Memory (Shenzhen)          | 11        | 0.16%   |
| Lite-On Technology               | 7         | 0.1%    |
| Lenovo                           | 7         | 0.1%    |
| Hewlett-Packard                  | 7         | 0.1%    |
| Apple                            | 7         | 0.1%    |
| INNOGRIT                         | 5         | 0.07%   |
| HighPoint Technologies           | 4         | 0.06%   |
| Adaptec                          | 4         | 0.06%   |
| Solid State Storage Technology   | 3         | 0.04%   |
| Silicon Integrated Systems [SiS] | 3         | 0.04%   |
| Shenzhen Longsys Electronics     | 3         | 0.04%   |
| Integrated Technology Express    | 3         | 0.04%   |
| OCZ Technology Group             | 2         | 0.03%   |
| O2 Micro                         | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.01%   |
| ULi Electronics                  | 1         | 0.01%   |
| Promise Technology               | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 828       | 10.19%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 280       | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 244       | 3%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 215       | 2.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 180       | 2.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 176       | 2.17%   |
| AMD 400 Series Chipset SATA Controller                                         | 173       | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 171       | 2.11%   |
| Intel SATA Controller [RAID mode]                                              | 156       | 1.92%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 150       | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 143       | 1.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 141       | 1.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 124       | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 122       | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 107       | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 101       | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 99        | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 99        | 1.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 92        | 1.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 91        | 1.12%   |
| AMD 500 Series Chipset SATA Controller                                         | 91        | 1.12%   |
| Intel Volume Management Device NVMe RAID Controller                            | 89        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 89        | 1.1%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 85        | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 85        | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 85        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 81        | 1%      |
| Samsung NVMe SSD Controller 980                                                | 79        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 76        | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 75        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 74        | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 73        | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 71        | 0.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 67        | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 65        | 0.8%    |
| Intel SSD 660P Series                                                          | 60        | 0.74%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 51        | 0.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 50        | 0.62%   |
| JMicron JMB363 SATA/IDE Controller                                             | 49        | 0.6%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 48        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3888      | 56.42%  |
| NVMe | 1567      | 22.74%  |
| IDE  | 832       | 12.07%  |
| RAID | 539       | 7.82%   |
| SAS  | 52        | 0.75%   |
| SCSI | 13        | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 3831      | 71.58%  |
| AMD      | 1460      | 27.28%  |
| ARM      | 54        | 1.01%   |
| Unknown  | 6         | 0.11%   |
| QUALCOMM | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 58        | 1.08%   |
| AMD Ryzen 5 3600 6-Core Processor       | 50        | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 45        | 0.84%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 43        | 0.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 41        | 0.76%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 41        | 0.76%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 40        | 0.75%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 39        | 0.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 36        | 0.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 35        | 0.65%   |
| ARM Processor                           | 35        | 0.65%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 35        | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 34        | 0.63%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 34        | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 33        | 0.62%   |
| AMD Custom APU 0405                     | 33        | 0.62%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 32        | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz       | 31        | 0.58%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 31        | 0.58%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 30        | 0.56%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 29        | 0.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 28        | 0.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 28        | 0.52%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 28        | 0.52%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 28        | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 27        | 0.5%    |
| Intel Core i5-4570 CPU @ 3.20GHz        | 27        | 0.5%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 27        | 0.5%    |
| Intel Core i7-4770 CPU @ 3.40GHz        | 26        | 0.48%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 26        | 0.48%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 25        | 0.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 25        | 0.47%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 25        | 0.47%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 24        | 0.45%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 23        | 0.43%   |
| AMD FX-8350 Eight-Core Processor        | 23        | 0.43%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 22        | 0.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 22        | 0.41%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 22        | 0.41%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 22        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1132      | 21.11%  |
| Intel Core i7           | 1101      | 20.53%  |
| Other                   | 343       | 6.4%    |
| AMD Ryzen 5             | 284       | 5.3%    |
| AMD Ryzen 7             | 279       | 5.2%    |
| Intel Core i3           | 267       | 4.98%   |
| Intel Core 2 Duo        | 256       | 4.77%   |
| Intel Xeon              | 195       | 3.64%   |
| Intel Celeron           | 159       | 2.96%   |
| AMD Ryzen 9             | 112       | 2.09%   |
| AMD FX                  | 110       | 2.05%   |
| Intel Pentium           | 95        | 1.77%   |
| AMD A6                  | 75        | 1.4%    |
| AMD A10                 | 70        | 1.31%   |
| Intel Core 2 Quad       | 66        | 1.23%   |
| Intel Atom              | 63        | 1.17%   |
| Intel Pentium Dual-Core | 58        | 1.08%   |
| AMD Ryzen 3             | 48        | 0.9%    |
| Intel Core i9           | 46        | 0.86%   |
| AMD A8                  | 44        | 0.82%   |
| AMD Athlon 64 X2        | 41        | 0.76%   |
| Intel Pentium Dual      | 39        | 0.73%   |
| Intel Core 2            | 37        | 0.69%   |
| AMD A4                  | 37        | 0.69%   |
| Intel Genuine           | 22        | 0.41%   |
| AMD Phenom II X4        | 22        | 0.41%   |
| AMD Athlon II X2        | 22        | 0.41%   |
| AMD E                   | 19        | 0.35%   |
| AMD Phenom II X6        | 18        | 0.34%   |
| AMD Phenom              | 17        | 0.32%   |
| Intel Pentium Silver    | 16        | 0.3%    |
| Intel Pentium D         | 16        | 0.3%    |
| Intel Pentium 4         | 15        | 0.28%   |
| AMD Ryzen Threadripper  | 15        | 0.28%   |
| AMD Athlon              | 14        | 0.26%   |
| AMD E2                  | 13        | 0.24%   |
| AMD E1                  | 13        | 0.24%   |
| AMD Ryzen 5 PRO         | 11        | 0.21%   |
| AMD A12                 | 11        | 0.21%   |
| AMD Turion 64 X2 Mobile | 10        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1997      | 37.17%  |
| 2       | 1928      | 35.89%  |
| 6       | 557       | 10.37%  |
| 8       | 446       | 8.3%    |
| 12      | 117       | 2.18%   |
| 1       | 109       | 2.03%   |
| 16      | 64        | 1.19%   |
| 3       | 54        | 1.01%   |
| 10      | 34        | 0.63%   |
| 14      | 29        | 0.54%   |
| 24      | 13        | 0.24%   |
| Unknown | 11        | 0.2%    |
| 20      | 6         | 0.11%   |
| 56      | 2         | 0.04%   |
| 128     | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 52      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 7       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5258      | 98.17%  |
| 2       | 86        | 1.61%   |
| Unknown | 9         | 0.17%   |
| 3       | 3         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3491      | 65.09%  |
| 1       | 1859      | 34.66%  |
| Unknown | 11        | 0.21%   |
| 12      | 1         | 0.02%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5207      | 96.93%  |
| Unknown        | 118       | 2.2%    |
| 32-bit         | 38        | 0.71%   |
| 64-bit         | 9         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1520      | 27.21%  |
| 0x306a9    | 300       | 5.37%   |
| 0x206a7    | 284       | 5.08%   |
| 0x306c3    | 231       | 4.14%   |
| 0x1067a    | 184       | 3.29%   |
| 0x906ea    | 135       | 2.42%   |
| 0x506e3    | 103       | 1.84%   |
| 0x806ea    | 96        | 1.72%   |
| 0x40651    | 92        | 1.65%   |
| 0x08701021 | 92        | 1.65%   |
| 0x906e9    | 86        | 1.54%   |
| 0x20655    | 86        | 1.54%   |
| 0x6fd      | 74        | 1.32%   |
| 0x806e9    | 73        | 1.31%   |
| 0x406e3    | 72        | 1.29%   |
| 0x806ec    | 64        | 1.15%   |
| 0x06001119 | 60        | 1.07%   |
| 0x306d4    | 56        | 1%      |
| 0x20652    | 56        | 1%      |
| 0x806c1    | 53        | 0.95%   |
| 0x10676    | 53        | 0.95%   |
| 0x106e5    | 51        | 0.91%   |
| 0x08701013 | 51        | 0.91%   |
| 0x6fb      | 50        | 0.9%    |
| 0x0800820d | 49        | 0.88%   |
| 0x06000852 | 48        | 0.86%   |
| 0xa0652    | 46        | 0.82%   |
| 0x010000c8 | 45        | 0.81%   |
| 0x0a50000c | 41        | 0.73%   |
| 0x706e5    | 37        | 0.66%   |
| 0x30678    | 36        | 0.64%   |
| 0x206d7    | 36        | 0.64%   |
| 0x906ed    | 34        | 0.61%   |
| 0x906a3    | 34        | 0.61%   |
| 0x406c4    | 33        | 0.59%   |
| 0x08108109 | 33        | 0.59%   |
| 0x106a5    | 31        | 0.55%   |
| 0x206c2    | 29        | 0.52%   |
| 0x03000027 | 28        | 0.5%    |
| 0xa0655    | 26        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 700       | 13.06%  |
| Haswell          | 471       | 8.79%   |
| IvyBridge        | 411       | 7.67%   |
| SandyBridge      | 394       | 7.35%   |
| Penryn           | 297       | 5.54%   |
| Zen 2            | 269       | 5.02%   |
| Skylake          | 243       | 4.53%   |
| Unknown          | 223       | 4.16%   |
| Westmere         | 212       | 3.96%   |
| Core             | 201       | 3.75%   |
| Zen 3            | 165       | 3.08%   |
| Zen+             | 158       | 2.95%   |
| Piledriver       | 153       | 2.86%   |
| K10              | 130       | 2.43%   |
| CometLake        | 126       | 2.35%   |
| Silvermont       | 122       | 2.28%   |
| Zen              | 114       | 2.13%   |
| Nehalem          | 108       | 2.02%   |
| Broadwell        | 97        | 1.81%   |
| Excavator        | 89        | 1.66%   |
| TigerLake        | 86        | 1.6%    |
| Icelake          | 71        | 1.32%   |
| Alderlake Hybrid | 70        | 1.31%   |
| K8 Hammer        | 66        | 1.23%   |
| Goldmont plus    | 50        | 0.93%   |
| Puma             | 41        | 0.77%   |
| Bobcat           | 40        | 0.75%   |
| K10 Llano        | 38        | 0.71%   |
| NetBurst         | 36        | 0.67%   |
| Bulldozer        | 35        | 0.65%   |
| Bonnell          | 27        | 0.5%    |
| Jaguar           | 26        | 0.49%   |
| Goldmont         | 25        | 0.47%   |
| Steamroller      | 24        | 0.45%   |
| P6               | 23        | 0.43%   |
| K8 & K10 hybrid  | 12        | 0.22%   |
| Tremont          | 6         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2694      | 44.4%   |
| Nvidia                                       | 1750      | 28.84%  |
| AMD                                          | 1550      | 25.54%  |
| Matrox Electronics Systems                   | 40        | 0.66%   |
| ASPEED Technology                            | 25        | 0.41%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.03%   |
| VIA Technologies                             | 2         | 0.03%   |
| Loongson Technology                          | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 254       | 4.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 189       | 3%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 151       | 2.39%   |
| Intel UHD Graphics 620                                                                   | 136       | 2.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 128       | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 123       | 1.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 107       | 1.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 99        | 1.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 94        | 1.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 85        | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 85        | 1.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 83        | 1.32%   |
| Intel HD Graphics 530                                                                    | 83        | 1.32%   |
| Intel HD Graphics 620                                                                    | 76        | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 75        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 73        | 1.16%   |
| Intel HD Graphics 5500                                                                   | 69        | 1.09%   |
| AMD Renoir                                                                               | 68        | 1.08%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 65        | 1.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 65        | 1.03%   |
| Intel HD Graphics 630                                                                    | 64        | 1.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 62        | 0.98%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 60        | 0.95%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 60        | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 55        | 0.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 55        | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 53        | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 52        | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 52        | 0.82%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 49        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 47        | 0.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 47        | 0.75%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 45        | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 43        | 0.68%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 41        | 0.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 39        | 0.62%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 37        | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 36        | 0.57%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 36        | 0.57%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 36        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x Intel                 | 2044      | 37.8%   |
| 1 x AMD                   | 1309      | 24.2%   |
| 1 x Nvidia                | 1137      | 21.02%  |
| Intel + Nvidia            | 478       | 8.84%   |
| AMD + Nvidia              | 82        | 1.52%   |
| 2 x AMD                   | 78        | 1.44%   |
| Intel + AMD               | 77        | 1.42%   |
| Other                     | 67        | 1.24%   |
| 2 x Nvidia                | 40        | 0.74%   |
| 1 x Matrox                | 30        | 0.55%   |
| 1 x ASPEED                | 20        | 0.37%   |
| 2 x Intel                 | 15        | 0.28%   |
| Nvidia + Matrox           | 8         | 0.15%   |
| Intel + 2 x Nvidia        | 4         | 0.07%   |
| 1 x SiS                   | 3         | 0.06%   |
| Nvidia + ASPEED           | 3         | 0.06%   |
| 1 x VIA                   | 2         | 0.04%   |
| AMD + 2 x Nvidia          | 2         | 0.04%   |
| AMD + Matrox              | 2         | 0.04%   |
| 5 x Nvidia                | 1         | 0.02%   |
| 2 x Loongson Technology   | 1         | 0.02%   |
| 1 x XGI                   | 1         | 0.02%   |
| 1 x Intel + 3 x AMD       | 1         | 0.02%   |
| Intel + ASPEED            | 1         | 0.02%   |
| AMD + XGI                 | 1         | 0.02%   |
| AMD + Nvidia + 1 x ASPEED | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4173      | 76.64%  |
| Proprietary | 1015      | 18.64%  |
| Unknown     | 257       | 4.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2996      | 53.88%  |
| 0.01-0.5   | 662       | 11.9%   |
| 1.01-2.0   | 562       | 10.11%  |
| 0.51-1.0   | 401       | 7.21%   |
| 7.01-8.0   | 326       | 5.86%   |
| 3.01-4.0   | 313       | 5.63%   |
| 5.01-6.0   | 146       | 2.63%   |
| 8.01-16.0  | 96        | 1.73%   |
| 2.01-3.0   | 47        | 0.85%   |
| 16.01-24.0 | 7         | 0.13%   |
| 4.01-5.0   | 4         | 0.07%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 770       | 12.92%  |
| AU Optronics            | 582       | 9.77%   |
| LG Display              | 422       | 7.08%   |
| Dell                    | 408       | 6.85%   |
| Goldstar                | 359       | 6.02%   |
| Acer                    | 339       | 5.69%   |
| Chimei Innolux          | 327       | 5.49%   |
| BOE                     | 283       | 4.75%   |
| Hewlett-Packard         | 251       | 4.21%   |
| Ancor Communications    | 216       | 3.62%   |
| Sharp                   | 177       | 2.97%   |
| BenQ                    | 173       | 2.9%    |
| Apple                   | 164       | 2.75%   |
| Lenovo                  | 142       | 2.38%   |
| ViewSonic               | 119       | 2%      |
| ASUSTek Computer        | 118       | 1.98%   |
| Chi Mei Optoelectronics | 78        | 1.31%   |
| LG Electronics          | 67        | 1.12%   |
| Toshiba                 | 62        | 1.04%   |
| Unknown                 | 60        | 1.01%   |
| Philips                 | 60        | 1.01%   |
| Sony                    | 58        | 0.97%   |
| AOC                     | 53        | 0.89%   |
| PANDA                   | 47        | 0.79%   |
| LG Philips              | 31        | 0.52%   |
| MSI                     | 29        | 0.49%   |
| InfoVision              | 27        | 0.45%   |
| NEC Computers           | 24        | 0.4%    |
| Panasonic               | 23        | 0.39%   |
| Valve                   | 20        | 0.34%   |
| HannStar                | 19        | 0.32%   |
| Gigabyte Technology     | 19        | 0.32%   |
| Unknown                 | 17        | 0.29%   |
| Insignia                | 16        | 0.27%   |
| HKC                     | 16        | 0.27%   |
| Gateway                 | 15        | 0.25%   |
| Sceptre Tech            | 13        | 0.22%   |
| AUS                     | 13        | 0.22%   |
| Vizio                   | 12        | 0.2%    |
| CSO                     | 11        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 32        | 0.51%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 32        | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 31        | 0.49%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 25        | 0.4%    |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 22        | 0.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 19        | 0.3%    |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 19        | 0.3%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 18        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 18        | 0.29%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 18        | 0.29%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 17        | 0.27%   |
| Unknown                                                               | 17        | 0.27%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 16        | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 16        | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 15        | 0.24%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 15        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 15        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 15        | 0.24%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 15        | 0.24%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                | 14        | 0.22%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 14        | 0.22%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 13        | 0.21%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 13        | 0.21%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch        | 13        | 0.21%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 13        | 0.21%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 13        | 0.21%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 12        | 0.19%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 12        | 0.19%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 12        | 0.19%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 12        | 0.19%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 12        | 0.19%   |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                       | 11        | 0.18%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 11        | 0.18%   |
| Sharp HDMI SHP0FFB 1920x1080 820x460mm 37.0-inch                      | 11        | 0.18%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 11        | 0.18%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 11        | 0.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 11        | 0.18%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 11        | 0.18%   |
| Acer G276HL ACR0300 1920x1080 598x336mm 27.0-inch                     | 11        | 0.18%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 10        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2299      | 40.05%  |
| 1366x768 (WXGA)    | 871       | 15.17%  |
| 3840x2160 (4K)     | 388       | 6.76%   |
| 2560x1440 (QHD)    | 285       | 4.96%   |
| 1680x1050 (WSXGA+) | 274       | 4.77%   |
| 1600x900 (HD+)     | 247       | 4.3%    |
| 1280x1024 (SXGA)   | 192       | 3.34%   |
| 1920x1200 (WUXGA)  | 169       | 2.94%   |
| 1280x800 (WXGA)    | 155       | 2.7%    |
| 1440x900 (WXGA+)   | 137       | 2.39%   |
| Unknown            | 123       | 2.14%   |
| 1360x768           | 63        | 1.1%    |
| 3440x1440          | 62        | 1.08%   |
| 3840x1080          | 53        | 0.92%   |
| 2560x1080          | 38        | 0.66%   |
| 1920x540           | 35        | 0.61%   |
| 2880x1800          | 28        | 0.49%   |
| 2560x1600          | 26        | 0.45%   |
| 800x1280           | 20        | 0.35%   |
| 1600x1200          | 17        | 0.3%    |
| 1024x768 (XGA)     | 16        | 0.28%   |
| 3840x2400          | 15        | 0.26%   |
| 3200x1800 (QHD+)   | 14        | 0.24%   |
| 2736x1824          | 14        | 0.24%   |
| 1280x720 (HD)      | 14        | 0.24%   |
| 1024x600           | 13        | 0.23%   |
| 2256x1504          | 9         | 0.16%   |
| 5760x1080          | 7         | 0.12%   |
| 3840x1200          | 7         | 0.12%   |
| 3600x1080          | 7         | 0.12%   |
| 2160x1440          | 7         | 0.12%   |
| 7680x2160          | 6         | 0.1%    |
| 3200x2000          | 6         | 0.1%    |
| 2288x1287          | 6         | 0.1%    |
| 2048x1152          | 6         | 0.1%    |
| 3200x1080          | 5         | 0.09%   |
| 1920x1280          | 5         | 0.09%   |
| 4480x1440          | 4         | 0.07%   |
| 3456x2160          | 4         | 0.07%   |
| 3280x1080          | 4         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1270      | 21.45%  |
| 27      | 499       | 8.43%   |
| 13      | 443       | 7.48%   |
| 24      | 438       | 7.4%    |
| Unknown | 412       | 6.96%   |
| 23      | 399       | 6.74%   |
| 21      | 360       | 6.08%   |
| 14      | 345       | 5.83%   |
| 17      | 292       | 4.93%   |
| 19      | 182       | 3.07%   |
| 31      | 166       | 2.8%    |
| 22      | 160       | 2.7%    |
| 20      | 154       | 2.6%    |
| 34      | 83        | 1.4%    |
| 18      | 75        | 1.27%   |
| 12      | 74        | 1.25%   |
| 72      | 62        | 1.05%   |
| 84      | 58        | 0.98%   |
| 11      | 57        | 0.96%   |
| 32      | 37        | 0.62%   |
| 40      | 28        | 0.47%   |
| 25      | 24        | 0.41%   |
| 16      | 23        | 0.39%   |
| 74      | 22        | 0.37%   |
| 54      | 20        | 0.34%   |
| 26      | 20        | 0.34%   |
| 37      | 19        | 0.32%   |
| 10      | 19        | 0.32%   |
| 7       | 18        | 0.3%    |
| 28      | 17        | 0.29%   |
| 48      | 14        | 0.24%   |
| 43      | 13        | 0.22%   |
| 39      | 10        | 0.17%   |
| 36      | 10        | 0.17%   |
| 47      | 9         | 0.15%   |
| 49      | 8         | 0.14%   |
| 46      | 8         | 0.14%   |
| 52      | 6         | 0.1%    |
| 42      | 6         | 0.1%    |
| 35      | 6         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1857      | 32.13%  |
| 501-600        | 1207      | 20.88%  |
| 401-500        | 814       | 14.08%  |
| Unknown        | 412       | 7.13%   |
| 201-300        | 390       | 6.75%   |
| 351-400        | 373       | 6.45%   |
| 601-700        | 245       | 4.24%   |
| 1501-2000      | 151       | 2.61%   |
| 701-800        | 130       | 2.25%   |
| 1001-1500      | 89        | 1.54%   |
| 801-900        | 67        | 1.16%   |
| 901-1000       | 21        | 0.36%   |
| 1-100          | 20        | 0.35%   |
| More than 2000 | 3         | 0.05%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3679      | 69.56%  |
| 16/10   | 809       | 15.3%   |
| Unknown | 338       | 6.39%   |
| 5/4     | 177       | 3.35%   |
| 21/9    | 93        | 1.76%   |
| 3/2     | 73        | 1.38%   |
| 4/3     | 46        | 0.87%   |
| 32/9    | 23        | 0.43%   |
| 0.67    | 18        | 0.34%   |
| 6/5     | 16        | 0.3%    |
| 1.96    | 5         | 0.09%   |
| 1.00    | 3         | 0.06%   |
| 3.40    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 3.33    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 11/10   | 1         | 0.02%   |
| 0.89    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1248      | 21.45%  |
| 201-250        | 1086      | 18.67%  |
| 81-90          | 603       | 10.36%  |
| 301-350        | 513       | 8.82%   |
| 151-200        | 426       | 7.32%   |
| Unknown        | 412       | 7.08%   |
| 351-500        | 304       | 5.23%   |
| More than 1000 | 209       | 3.59%   |
| 71-80          | 184       | 3.16%   |
| 121-130        | 175       | 3.01%   |
| 251-300        | 145       | 2.49%   |
| 141-150        | 143       | 2.46%   |
| 501-1000       | 124       | 2.13%   |
| 51-60          | 60        | 1.03%   |
| 61-70          | 59        | 1.01%   |
| 111-120        | 40        | 0.69%   |
| 131-140        | 34        | 0.58%   |
| 1-40           | 21        | 0.36%   |
| 41-50          | 18        | 0.31%   |
| 91-100         | 14        | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2056      | 36.59%  |
| 101-120       | 1387      | 24.68%  |
| 121-160       | 1140      | 20.29%  |
| Unknown       | 412       | 7.33%   |
| 161-240       | 280       | 4.98%   |
| 1-50          | 214       | 3.81%   |
| More than 240 | 130       | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4153      | 75.41%  |
| 2     | 922       | 16.74%  |
| 0     | 263       | 4.78%   |
| 3     | 152       | 2.76%   |
| 4     | 14        | 0.25%   |
| 5     | 2         | 0.04%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2825      | 35.16%  |
| Realtek Semiconductor           | 2499      | 31.11%  |
| Qualcomm Atheros                | 888       | 11.05%  |
| Broadcom                        | 547       | 6.81%   |
| Broadcom Limited                | 134       | 1.67%   |
| Marvell Technology Group        | 126       | 1.57%   |
| Ralink                          | 104       | 1.29%   |
| Nvidia                          | 100       | 1.24%   |
| MediaTek                        | 79        | 0.98%   |
| Ralink Technology               | 74        | 0.92%   |
| TP-Link                         | 73        | 0.91%   |
| D-Link                          | 64        | 0.8%    |
| ASIX Electronics                | 63        | 0.78%   |
| Linksys                         | 48        | 0.6%    |
| Samsung Electronics             | 34        | 0.42%   |
| D-Link System                   | 34        | 0.42%   |
| ASUSTek Computer                | 33        | 0.41%   |
| Qualcomm Atheros Communications | 28        | 0.35%   |
| Aquantia                        | 23        | 0.29%   |
| Microsoft                       | 22        | 0.27%   |
| DisplayLink                     | 20        | 0.25%   |
| NetGear                         | 19        | 0.24%   |
| Lenovo                          | 17        | 0.21%   |
| Google                          | 12        | 0.15%   |
| Belkin Components               | 10        | 0.12%   |
| Sierra Wireless                 | 9         | 0.11%   |
| Qualcomm                        | 6         | 0.07%   |
| Motorola PCS                    | 6         | 0.07%   |
| Apple                           | 6         | 0.07%   |
| Microchip Technology            | 5         | 0.06%   |
| Micro Star International        | 5         | 0.06%   |
| Mellanox Technologies           | 5         | 0.06%   |
| Edimax Technology               | 5         | 0.06%   |
| Dell                            | 5         | 0.06%   |
| Arduino SA                      | 5         | 0.06%   |
| AMD                             | 5         | 0.06%   |
| VIA Technologies                | 4         | 0.05%   |
| LG Electronics                  | 4         | 0.05%   |
| Hewlett-Packard                 | 4         | 0.05%   |
| Gemtek                          | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1658      | 17.4%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 306       | 3.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 275       | 2.89%   |
| Intel Wi-Fi 6 AX200                                               | 267       | 2.8%    |
| Intel I211 Gigabit Network Connection                             | 170       | 1.78%   |
| Intel Wireless 8265 / 8275                                        | 167       | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 133       | 1.4%    |
| Intel Wireless 7260                                               | 123       | 1.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 122       | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 120       | 1.26%   |
| Intel Wireless 7265                                               | 111       | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 104       | 1.09%   |
| Intel Ethernet Connection (2) I219-V                              | 99        | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 96        | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 92        | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 91        | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 91        | 0.95%   |
| Intel Wireless 8260                                               | 90        | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 89        | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 85        | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 85        | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 76        | 0.8%    |
| Intel Ethernet Controller I225-V                                  | 75        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 75        | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 68        | 0.71%   |
| Intel Wi-Fi 6 AX201                                               | 67        | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 63        | 0.66%   |
| Intel Wireless-AC 9260                                            | 62        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                              | 56        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 53        | 0.56%   |
| Intel Wireless 3165                                               | 53        | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 53        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 52        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 50        | 0.52%   |
| Intel Centrino Ultimate-N 6300                                    | 50        | 0.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 50        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 50        | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 49        | 0.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 49        | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 48        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1934      | 45.14%  |
| Qualcomm Atheros                      | 706       | 16.48%  |
| Realtek Semiconductor                 | 584       | 13.63%  |
| Broadcom                              | 362       | 8.45%   |
| Ralink                                | 104       | 2.43%   |
| Broadcom Limited                      | 79        | 1.84%   |
| MediaTek                              | 77        | 1.8%    |
| Ralink Technology                     | 74        | 1.73%   |
| TP-Link                               | 63        | 1.47%   |
| D-Link                                | 62        | 1.45%   |
| Linksys                               | 46        | 1.07%   |
| ASUSTek Computer                      | 33        | 0.77%   |
| Qualcomm Atheros Communications       | 28        | 0.65%   |
| Marvell Technology Group              | 21        | 0.49%   |
| D-Link System                         | 21        | 0.49%   |
| NetGear                               | 19        | 0.44%   |
| Microsoft                             | 16        | 0.37%   |
| Belkin Components                     | 10        | 0.23%   |
| Sierra Wireless                       | 9         | 0.21%   |
| Qualcomm                              | 5         | 0.12%   |
| Micro Star International              | 5         | 0.12%   |
| Edimax Technology                     | 5         | 0.12%   |
| Gemtek                                | 4         | 0.09%   |
| ZyDAS                                 | 3         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.07%   |
| TRENDnet                              | 2         | 0.05%   |
| Dell                                  | 2         | 0.05%   |
| Wilocity                              | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Cypress Semiconductor                 | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| Belkin                                | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 267       | 6.17%   |
| Intel Wireless 8265 / 8275                                     | 167       | 3.86%   |
| Intel Wireless 7260                                            | 123       | 2.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 120       | 2.77%   |
| Intel Wireless 7265                                            | 111       | 2.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 96        | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 92        | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 91        | 2.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 91        | 2.1%    |
| Intel Wireless 8260                                            | 90        | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 89        | 2.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 85        | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 85        | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 76        | 1.76%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 75        | 1.73%   |
| Intel Wi-Fi 6 AX201                                            | 67        | 1.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 63        | 1.46%   |
| Intel Wireless-AC 9260                                         | 62        | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 53        | 1.22%   |
| Intel Wireless 3165                                            | 53        | 1.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 53        | 1.22%   |
| Intel Centrino Ultimate-N 6300                                 | 50        | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 50        | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 49        | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 49        | 1.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 48        | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 48        | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 43        | 0.99%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 41        | 0.95%   |
| Realtek 802.11ac NIC                                           | 40        | 0.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 37        | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 37        | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 35        | 0.81%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 35        | 0.81%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 35        | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 34        | 0.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 34        | 0.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 33        | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 32        | 0.74%   |
| Intel Centrino Wireless-N 2230                                 | 32        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2237      | 44.82%  |
| Intel                             | 1673      | 33.52%  |
| Broadcom                          | 286       | 5.73%   |
| Qualcomm Atheros                  | 275       | 5.51%   |
| Marvell Technology Group          | 105       | 2.1%    |
| Nvidia                            | 99        | 1.98%   |
| ASIX Electronics                  | 63        | 1.26%   |
| Broadcom Limited                  | 60        | 1.2%    |
| Aquantia                          | 23        | 0.46%   |
| Samsung Electronics               | 20        | 0.4%    |
| DisplayLink                       | 20        | 0.4%    |
| Lenovo                            | 16        | 0.32%   |
| D-Link System                     | 13        | 0.26%   |
| TP-Link                           | 12        | 0.24%   |
| Google                            | 10        | 0.2%    |
| Apple                             | 6         | 0.12%   |
| Mellanox Technologies             | 5         | 0.1%    |
| VIA Technologies                  | 4         | 0.08%   |
| Microsoft                         | 4         | 0.08%   |
| LG Electronics                    | 4         | 0.08%   |
| Hewlett-Packard                   | 4         | 0.08%   |
| Xiaomi                            | 3         | 0.06%   |
| Research In Motion                | 3         | 0.06%   |
| Microchip Technology              | 3         | 0.06%   |
| JMicron Technology                | 3         | 0.06%   |
| Dell                              | 3         | 0.06%   |
| D-Link                            | 3         | 0.06%   |
| American Megatrends               | 3         | 0.06%   |
| 3Com                              | 3         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.04%   |
| Motorola PCS                      | 2         | 0.04%   |
| MediaTek                          | 2         | 0.04%   |
| Linksys                           | 2         | 0.04%   |
| ICS Advent                        | 2         | 0.04%   |
| IBM                               | 2         | 0.04%   |
| Huawei Technologies               | 2         | 0.04%   |
| HMD Global                        | 2         | 0.04%   |
| Chelsio Communications            | 2         | 0.04%   |
| Sundance Technology Inc / IC Plus | 1         | 0.02%   |
| Sun Microsystems                  | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1658      | 32.34%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 306       | 5.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 275       | 5.36%   |
| Intel I211 Gigabit Network Connection                             | 170       | 3.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 133       | 2.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 122       | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 104       | 2.03%   |
| Intel Ethernet Connection (2) I219-V                              | 99        | 1.93%   |
| Intel Ethernet Controller I225-V                                  | 75        | 1.46%   |
| Intel 82579V Gigabit Network Connection                           | 68        | 1.33%   |
| Intel Ethernet Connection (7) I219-V                              | 56        | 1.09%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 52        | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                             | 50        | 0.98%   |
| ASIX AX88179 Gigabit Ethernet                                     | 50        | 0.98%   |
| Intel 82577LM Gigabit Network Connection                          | 48        | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 45        | 0.88%   |
| Intel 82574L Gigabit Network Connection                           | 45        | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 44        | 0.86%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 42        | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 39        | 0.76%   |
| Intel Ethernet Connection (2) I218-V                              | 38        | 0.74%   |
| Intel Ethernet Connection I217-V                                  | 36        | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 33        | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 33        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 32        | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 30        | 0.59%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.59%   |
| Intel Ethernet Connection I219-LM                                 | 30        | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 26        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25        | 0.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 25        | 0.49%   |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 24        | 0.47%   |
| Nvidia MCP79 Ethernet                                             | 24        | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 24        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 23        | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 22        | 0.43%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 22        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4670      | 53.49%  |
| WiFi     | 3987      | 45.66%  |
| Modem    | 62        | 0.71%   |
| Unknown  | 12        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2964      | 52.51%  |
| Ethernet | 2681      | 47.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2968      | 55.06%  |
| 1     | 2094      | 38.85%  |
| 3     | 166       | 3.08%   |
| 0     | 107       | 1.99%   |
| 4     | 31        | 0.58%   |
| 5     | 12        | 0.22%   |
| 6     | 6         | 0.11%   |
| 8     | 2         | 0.04%   |
| 22    | 1         | 0.02%   |
| 21    | 1         | 0.02%   |
| 12    | 1         | 0.02%   |
| 10    | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4662      | 85.76%  |
| Yes  | 774       | 14.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1519      | 48.16%  |
| Broadcom                        | 215       | 6.82%   |
| Qualcomm Atheros Communications | 213       | 6.75%   |
| Realtek Semiconductor           | 202       | 6.4%    |
| Apple                           | 174       | 5.52%   |
| Cambridge Silicon Radio         | 168       | 5.33%   |
| IMC Networks                    | 153       | 4.85%   |
| Lite-On Technology              | 129       | 4.09%   |
| ASUSTek Computer                | 86        | 2.73%   |
| Foxconn / Hon Hai               | 82        | 2.6%    |
| Dell                            | 42        | 1.33%   |
| Hewlett-Packard                 | 30        | 0.95%   |
| MediaTek                        | 19        | 0.6%    |
| Marvell Semiconductor           | 19        | 0.6%    |
| Ralink                          | 16        | 0.51%   |
| Toshiba                         | 14        | 0.44%   |
| Dynex                           | 14        | 0.44%   |
| Realtek                         | 10        | 0.32%   |
| TP-Link                         | 9         | 0.29%   |
| Alps Electric                   | 7         | 0.22%   |
| Micro Star International        | 5         | 0.16%   |
| Logitech                        | 5         | 0.16%   |
| Primax Electronics              | 3         | 0.1%    |
| Integrated System Solution      | 3         | 0.1%    |
| SINO WEALTH                     | 2         | 0.06%   |
| Ralink Technology               | 2         | 0.06%   |
| Zeevo                           | 1         | 0.03%   |
| USI                             | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Nintendo                        | 1         | 0.03%   |
| Kensington                      | 1         | 0.03%   |
| ISSC                            | 1         | 0.03%   |
| HTC (High Tech Computer)        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Foxconn International           | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| D-Link System                   | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 547       | 17.32%  |
| Intel AX200 Bluetooth                                    | 259       | 8.2%    |
| Intel AX201 Bluetooth                                    | 220       | 6.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 168       | 5.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 160       | 5.06%   |
| Realtek Bluetooth Radio                                  | 139       | 4.4%    |
| Qualcomm Atheros  Bluetooth Device                       | 102       | 3.23%   |
| Intel Wireless-AC 3168 Bluetooth                         | 96        | 3.04%   |
| IMC Networks Bluetooth Radio                             | 83        | 2.63%   |
| Apple Bluetooth Host Controller                          | 79        | 2.5%    |
| Intel Bluetooth Device                                   | 70        | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 61        | 1.93%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 58        | 1.84%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 58        | 1.84%   |
| Intel AX210 Bluetooth                                    | 53        | 1.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 49        | 1.55%   |
| Realtek  Bluetooth 4.2 Adapter                           | 38        | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device                       | 36        | 1.14%   |
| Lite-On Atheros AR3012 Bluetooth                         | 35        | 1.11%   |
| Apple Bluetooth USB Host Controller                      | 34        | 1.08%   |
| Apple Bluetooth HCI                                      | 33        | 1.04%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 32        | 1.01%   |
| Broadcom BCM2045B (BDC-2.1)                              | 31        | 0.98%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 30        | 0.95%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 27        | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 26        | 0.82%   |
| Lite-On Bluetooth Device                                 | 24        | 0.76%   |
| IMC Networks Wireless_Device                             | 22        | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 21        | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 20        | 0.63%   |
| IMC Networks Bluetooth Device                            | 20        | 0.63%   |
| MediaTek Wireless_Device                                 | 19        | 0.6%    |
| Broadcom HP Portable SoftSailing                         | 18        | 0.57%   |
| Ralink RT3290 Bluetooth                                  | 16        | 0.51%   |
| HP Broadcom 2070 Bluetooth Combo                         | 16        | 0.51%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 15        | 0.47%   |
| Marvell Bluetooth and Wireless LAN Composite             | 14        | 0.44%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 14        | 0.44%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 14        | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 13        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3633      | 46.68%  |
| AMD                                  | 1772      | 22.77%  |
| Nvidia                               | 1409      | 18.1%   |
| C-Media Electronics                  | 164       | 2.11%   |
| Logitech                             | 86        | 1.1%    |
| Creative Labs                        | 64        | 0.82%   |
| Corsair                              | 35        | 0.45%   |
| Realtek Semiconductor                | 34        | 0.44%   |
| JMTek                                | 30        | 0.39%   |
| Texas Instruments                    | 29        | 0.37%   |
| Blue Microphones                     | 27        | 0.35%   |
| SteelSeries ApS                      | 26        | 0.33%   |
| Razer USA                            | 25        | 0.32%   |
| Creative Technology                  | 25        | 0.32%   |
| Focusrite-Novation                   | 24        | 0.31%   |
| ASUSTek Computer                     | 22        | 0.28%   |
| Kingston Technology                  | 20        | 0.26%   |
| GN Netcom                            | 18        | 0.23%   |
| Plantronics                          | 17        | 0.22%   |
| Lenovo                               | 17        | 0.22%   |
| Samson Technologies                  | 14        | 0.18%   |
| GYROCOM C&C                          | 14        | 0.18%   |
| Sony                                 | 12        | 0.15%   |
| Generalplus Technology               | 12        | 0.15%   |
| VIA Technologies                     | 10        | 0.13%   |
| M-Audio                              | 10        | 0.13%   |
| Micro Star International             | 9         | 0.12%   |
| Dell                                 | 8         | 0.1%    |
| SAVITECH                             | 7         | 0.09%   |
| Audio-Technica                       | 7         | 0.09%   |
| Yamaha                               | 6         | 0.08%   |
| XMOS                                 | 6         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.08%   |
| Tenx Technology                      | 6         | 0.08%   |
| Hewlett-Packard                      | 6         | 0.08%   |
| DSEA A/S                             | 6         | 0.08%   |
| Cambridge Silicon Radio              | 6         | 0.08%   |
| Bose                                 | 6         | 0.08%   |
| Apple                                | 6         | 0.08%   |
| NAD Electronics                      | 5         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 387       | 4.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 340       | 3.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 333       | 3.63%   |
| Intel Sunrise Point-LP HD Audio                                            | 320       | 3.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 277       | 3.02%   |
| AMD Starship/Matisse HD Audio Controller                                   | 274       | 2.99%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 252       | 2.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 228       | 2.48%   |
| AMD FCH Azalia Controller                                                  | 216       | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 207       | 2.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 193       | 2.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 186       | 2.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 159       | 1.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 153       | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 141       | 1.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 139       | 1.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 114       | 1.24%   |
| Intel Haswell-ULT HD Audio Controller                                      | 111       | 1.21%   |
| Intel 8 Series HD Audio Controller                                         | 111       | 1.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 111       | 1.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 107       | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 104       | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 103       | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 103       | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                   | 101       | 1.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 98        | 1.07%   |
| Intel Comet Lake PCH cAVS                                                  | 89        | 0.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 89        | 0.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 86        | 0.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 86        | 0.94%   |
| Intel Broadwell-U Audio Controller                                         | 84        | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 83        | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                              | 82        | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 82        | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 76        | 0.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 76        | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                         | 73        | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 70        | 0.76%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 69        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 66        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 618       | 19.81%  |
| SK hynix                                         | 567       | 18.17%  |
| Kingston                                         | 375       | 12.02%  |
| Micron Technology                                | 303       | 9.71%   |
| Unknown                                          | 297       | 9.52%   |
| G.Skill                                          | 224       | 7.18%   |
| Corsair                                          | 206       | 6.6%    |
| Crucial                                          | 137       | 4.39%   |
| Elpida                                           | 59        | 1.89%   |
| Nanya Technology                                 | 56        | 1.79%   |
| Ramaxel Technology                               | 51        | 1.63%   |
| A-DATA Technology                                | 51        | 1.63%   |
| Patriot                                          | 30        | 0.96%   |
| Unknown                                          | 18        | 0.58%   |
| Team                                             | 14        | 0.45%   |
| Unknown (ABCD)                                   | 9         | 0.29%   |
| Unifosa                                          | 8         | 0.26%   |
| Transcend                                        | 8         | 0.26%   |
| ASint Technology                                 | 8         | 0.26%   |
| Timetec                                          | 7         | 0.22%   |
| Toshiba                                          | 6         | 0.19%   |
| Avant                                            | 5         | 0.16%   |
| Goldkey                                          | 4         | 0.13%   |
| Sesame                                           | 3         | 0.1%    |
| Qimonda                                          | 3         | 0.1%    |
| PNY                                              | 3         | 0.1%    |
| OCZ                                              | 3         | 0.1%    |
| Neo Forza                                        | 3         | 0.1%    |
| CSX                                              | 3         | 0.1%    |
| Unknown (7F7F7F94FFFFFFFF)                       | 2         | 0.06%   |
| SHARETRONIC                                      | 2         | 0.06%   |
| Mushkin                                          | 2         | 0.06%   |
| Hewlett-Packard                                  | 2         | 0.06%   |
| ff                                               | 2         | 0.06%   |
| Axiom                                            | 2         | 0.06%   |
| Apacer                                           | 2         | 0.06%   |
| 4ea5                                             | 2         | 0.06%   |
| Unknown (0x7F61)                                 | 1         | 0.03%   |
| Unknown (0x505344323247363637325300000000000000) | 1         | 0.03%   |
| Unknown (0x4D342037305432383634515A332D43453620) | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 33        | 0.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 21        | 0.62%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 21        | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.59%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 20        | 0.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 19        | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.56%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s          | 18        | 0.53%   |
| Unknown                                                          | 18        | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.5%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 16        | 0.47%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 15        | 0.44%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 15        | 0.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.41%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.38%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 13        | 0.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 13        | 0.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.38%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 13        | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.35%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 12        | 0.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.33%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 11        | 0.33%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 10        | 0.3%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.3%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 10        | 0.3%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 10        | 0.3%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 10        | 0.3%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.27%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 9         | 0.27%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 9         | 0.27%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 9         | 0.27%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR4            | 1142      | 42.93%  |
| DDR3            | 962       | 36.17%  |
| DDR2            | 152       | 5.71%   |
| LPDDR4          | 91        | 3.42%   |
| LPDDR3          | 75        | 2.82%   |
| SDRAM           | 74        | 2.78%   |
| Unknown         | 66        | 2.48%   |
| DDR5            | 46        | 1.73%   |
| DDR             | 34        | 1.28%   |
| LPDDR5          | 15        | 0.56%   |
| DRAM            | 2         | 0.08%   |
| Logical non-vol | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1269      | 48.23%  |
| DIMM            | 1155      | 43.9%   |
| Row Of Chips    | 174       | 6.61%   |
| Chip            | 18        | 0.68%   |
| Unknown         | 10        | 0.38%   |
| FB-DIMM         | 4         | 0.15%   |
| Proprietary Car | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1065      | 36.16%  |
| 4096   | 798       | 27.1%   |
| 16384  | 451       | 15.31%  |
| 2048   | 406       | 13.79%  |
| 1024   | 122       | 4.14%   |
| 32768  | 84        | 2.85%   |
| 512    | 13        | 0.44%   |
| 65536  | 3         | 0.1%    |
| 129408 | 1         | 0.03%   |
| 256    | 1         | 0.03%   |
| 64     | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 576       | 19.83%  |
| 3200    | 350       | 12.05%  |
| 2667    | 336       | 11.57%  |
| 1333    | 254       | 8.74%   |
| 2400    | 198       | 6.82%   |
| 2133    | 148       | 5.09%   |
| 3600    | 105       | 3.61%   |
| 667     | 83        | 2.86%   |
| 1334    | 77        | 2.65%   |
| 800     | 73        | 2.51%   |
| 1867    | 70        | 2.41%   |
| 1067    | 49        | 1.69%   |
| 4267    | 44        | 1.51%   |
| Unknown | 40        | 1.38%   |
| 1066    | 38        | 1.31%   |
| 4800    | 30        | 1.03%   |
| 3266    | 27        | 0.93%   |
| 3733    | 25        | 0.86%   |
| 1866    | 25        | 0.86%   |
| 3866    | 23        | 0.79%   |
| 6400    | 20        | 0.69%   |
| 3800    | 20        | 0.69%   |
| 2666    | 18        | 0.62%   |
| 2933    | 15        | 0.52%   |
| 3400    | 14        | 0.48%   |
| 3000    | 14        | 0.48%   |
| 533     | 14        | 0.48%   |
| 8400    | 13        | 0.45%   |
| 4199    | 13        | 0.45%   |
| 3533    | 13        | 0.45%   |
| 1800    | 13        | 0.45%   |
| 4266    | 10        | 0.34%   |
| 2800    | 9         | 0.31%   |
| 975     | 9         | 0.31%   |
| 2048    | 8         | 0.28%   |
| 1639    | 8         | 0.28%   |
| 3666    | 7         | 0.24%   |
| 3534    | 7         | 0.24%   |
| 3100    | 7         | 0.24%   |
| 2465    | 7         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Brother Industries       | 70        | 32.11%  |
| Hewlett-Packard          | 59        | 27.06%  |
| Samsung Electronics      | 34        | 15.6%   |
| Canon                    | 31        | 14.22%  |
| Seiko Epson              | 11        | 5.05%   |
| Lexmark International    | 4         | 1.83%   |
| Dymo-CoStar              | 3         | 1.38%   |
| Dell                     | 2         | 0.92%   |
| Zhuhai Poskey Technology | 1         | 0.46%   |
| Xerox                    | 1         | 0.46%   |
| QinHeng Electronics      | 1         | 0.46%   |
| Prolific Technology      | 1         | 0.46%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Brother Printer                      | 10        | 4.46%   |
| HP LaserJet 1020                     | 5         | 2.23%   |
| HP LaserJet 1018                     | 5         | 2.23%   |
| Brother HL-L2390DW                   | 5         | 2.23%   |
| Brother HL-L2320D series             | 5         | 2.23%   |
| Seiko Epson L6160 Series             | 4         | 1.79%   |
| Samsung ML-216x Series Laser Printer | 4         | 1.79%   |
| Brother MFC-J480DW                   | 4         | 1.79%   |
| Brother HL-5370DW series             | 4         | 1.79%   |
| Samsung ML-1670 Series               | 3         | 1.34%   |
| Samsung M267x 287x Series            | 3         | 1.34%   |
| HP LaserJet 4250                     | 3         | 1.34%   |
| HP ENVY 4520 series                  | 3         | 1.34%   |
| HP DeskJet 3630 series               | 3         | 1.34%   |
| HP DeskJet 2600 series               | 3         | 1.34%   |
| Canon PIXMA MX920 Series             | 3         | 1.34%   |
| Canon PIXMA MG2900 Series            | 3         | 1.34%   |
| Brother MFC-9130CW                   | 3         | 1.34%   |
| Brother HL-L2360D series             | 3         | 1.34%   |
| Brother HL-2270DW Laser Printer      | 3         | 1.34%   |
| Brother DCP-L2540DW                  | 3         | 1.34%   |
| Seiko Epson WF-3520 Series           | 2         | 0.89%   |
| Samsung ML-1660 Series               | 2         | 0.89%   |
| Samsung M2070 Series                 | 2         | 0.89%   |
| Samsung M2020 Series                 | 2         | 0.89%   |
| Samsung CLP-310 Color Laser Printer  | 2         | 0.89%   |
| Samsung C460 Series                  | 2         | 0.89%   |
| HP OfficeJet 3830 series             | 2         | 0.89%   |
| HP LaserJet Pro M201dw               | 2         | 0.89%   |
| HP LaserJet M101-M106                | 2         | 0.89%   |
| HP DeskJet 3700 series               | 2         | 0.89%   |
| Dymo-CoStar LabelWriter 450          | 2         | 0.89%   |
| Canon PIXMA MX530 Series             | 2         | 0.89%   |
| Canon MG2100 series                  | 2         | 0.89%   |
| Canon MF4410                         | 2         | 0.89%   |
| Canon MF3010                         | 2         | 0.89%   |
| Brother MFC-J485DW                   | 2         | 0.89%   |
| Brother MFC-9330CDW                  | 2         | 0.89%   |
| Brother HL-L3290CDW series           | 2         | 0.89%   |
| Brother HL-2140 series               | 2         | 0.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 21        | 58.33%  |
| Hewlett-Packard | 9         | 25%     |
| Seiko Epson     | 6         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                 | 5         | 13.89%  |
| Canon CanoScan LiDE 700F                                | 4         | 11.11%  |
| Canon CanoScan LiDE 220                                 | 4         | 11.11%  |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 2         | 5.56%   |
| HP ScanJet 82x0C                                        | 2         | 5.56%   |
| Canon CanoScan LiDE 120                                 | 2         | 5.56%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1         | 2.78%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 2.78%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]           | 1         | 2.78%   |
| Seiko Epson GT-6600U [Perfection 610]                   | 1         | 2.78%   |
| HP ScanJet G4050                                        | 1         | 2.78%   |
| HP ScanJet G4010                                        | 1         | 2.78%   |
| HP ScanJet 5590                                         | 1         | 2.78%   |
| HP ScanJet 5200c                                        | 1         | 2.78%   |
| HP ScanJet 3670                                         | 1         | 2.78%   |
| HP ScanJet 3400cse                                      | 1         | 2.78%   |
| HP ScanJet 2200c                                        | 1         | 2.78%   |
| Canon CanoScan LiDE 70                                  | 1         | 2.78%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 2.78%   |
| Canon CanoScan LiDE 200                                 | 1         | 2.78%   |
| Canon CanoScan LiDE 110                                 | 1         | 2.78%   |
| Canon CanoScan 4200F                                    | 1         | 2.78%   |
| Canon CanoScan                                          | 1         | 2.78%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 557       | 19.03%  |
| Microdia                               | 301       | 10.28%  |
| Logitech                               | 282       | 9.63%   |
| IMC Networks                           | 239       | 8.17%   |
| Realtek Semiconductor                  | 202       | 6.9%    |
| Apple                                  | 177       | 6.05%   |
| Sunplus Innovation Technology          | 154       | 5.26%   |
| Quanta                                 | 104       | 3.55%   |
| Bison Electronics                      | 104       | 3.55%   |
| Suyin                                  | 94        | 3.21%   |
| Acer                                   | 92        | 3.14%   |
| Microsoft                              | 77        | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 66        | 2.25%   |
| Syntek                                 | 40        | 1.37%   |
| Lite-On Technology                     | 39        | 1.33%   |
| Samsung Electronics                    | 38        | 1.3%    |
| Ricoh                                  | 30        | 1.02%   |
| Luxvisions Innotech Limited            | 30        | 1.02%   |
| Silicon Motion                         | 29        | 0.99%   |
| Lenovo                                 | 25        | 0.85%   |
| Z-Star Microelectronics                | 19        | 0.65%   |
| Importek                               | 19        | 0.65%   |
| AVerMedia Technologies                 | 17        | 0.58%   |
| MacroSilicon                           | 14        | 0.48%   |
| Alcor Micro                            | 14        | 0.48%   |
| Sonix Technology                       | 9         | 0.31%   |
| OmniVision Technologies                | 9         | 0.31%   |
| Generalplus Technology                 | 9         | 0.31%   |
| ALi                                    | 9         | 0.31%   |
| webcam                                 | 8         | 0.27%   |
| Cubeternet                             | 8         | 0.27%   |
| Primax Electronics                     | 7         | 0.24%   |
| LG Electronics                         | 7         | 0.24%   |
| Creative Technology                    | 7         | 0.24%   |
| Razer USA                              | 5         | 0.17%   |
| Huawei Technologies                    | 5         | 0.17%   |
| Hewlett-Packard                        | 5         | 0.17%   |
| Genesys Logic                          | 5         | 0.17%   |
| WaveRider Communications               | 4         | 0.14%   |
| Intel                                  | 4         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 127       | 4.3%    |
| Microdia Integrated_Webcam_HD           | 113       | 3.83%   |
| IMC Networks USB2.0 HD UVC WebCam       | 88        | 2.98%   |
| Logitech HD Pro Webcam C920             | 77        | 2.61%   |
| Realtek Integrated_Webcam_HD            | 76        | 2.57%   |
| Apple Built-in iSight                   | 61        | 2.07%   |
| Logitech Webcam C270                    | 59        | 2%      |
| Chicony HD WebCam                       | 51        | 1.73%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 51        | 1.73%   |
| IMC Networks Integrated Camera          | 48        | 1.63%   |
| Samsung Galaxy series, misc. (MTP mode) | 38        | 1.29%   |
| Sunplus Integrated_Webcam_HD            | 36        | 1.22%   |
| Microdia Integrated Webcam              | 33        | 1.12%   |
| Apple FaceTime HD Camera (Built-in)     | 33        | 1.12%   |
| Bison Integrated Camera                 | 32        | 1.08%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 31        | 1.05%   |
| Syntek Integrated Camera                | 28        | 0.95%   |
| Sunplus HD WebCam                       | 26        | 0.88%   |
| Apple FaceTime HD Camera                | 26        | 0.88%   |
| Microdia Webcam Vitade AF               | 25        | 0.85%   |
| Logitech C922 Pro Stream Webcam         | 25        | 0.85%   |
| Acer Integrated Camera                  | 24        | 0.81%   |
| Microsoft LifeCam HD-3000               | 23        | 0.78%   |
| Chicony VGA WebCam                      | 22        | 0.75%   |
| Quanta VGA WebCam                       | 20        | 0.68%   |
| Lite-On Integrated Camera               | 20        | 0.68%   |
| Chicony HP Truevision HD                | 20        | 0.68%   |
| Acer HD Webcam                          | 20        | 0.68%   |
| Quanta HD User Facing                   | 19        | 0.64%   |
| Chicony USB2.0 HD UVC WebCam            | 18        | 0.61%   |
| Chicony HP HD Camera                    | 17        | 0.58%   |
| Realtek USB Camera                      | 16        | 0.54%   |
| Chicony USB 2.0 Camera                  | 16        | 0.54%   |
| Bison SunplusIT Integrated Camera       | 16        | 0.54%   |
| Quanta HP TrueVision HD Camera          | 15        | 0.51%   |
| Chicony TOSHIBA Web Camera - HD         | 15        | 0.51%   |
| Chicony HD User Facing                  | 15        | 0.51%   |
| AVerMedia Live Streamer CAM 313         | 15        | 0.51%   |
| Sunplus HP HD Webcam [Fixed]            | 14        | 0.47%   |
| Logitech HD Webcam C615                 | 14        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 204       | 37.92%  |
| Synaptics                          | 125       | 23.23%  |
| Shenzhen Goodix Technology         | 52        | 9.67%   |
| Elan Microelectronics              | 41        | 7.62%   |
| Upek                               | 34        | 6.32%   |
| AuthenTec                          | 31        | 5.76%   |
| LighTuning Technology              | 24        | 4.46%   |
| STMicroelectronics                 | 16        | 2.97%   |
| Focal-systems.Corp                 | 4         | 0.74%   |
| Samsung Electronics                | 2         | 0.37%   |
| Microsoft                          | 2         | 0.37%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.19%   |
| HOLTEK                             | 1         | 0.19%   |
| Dell                               | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 47        | 8.74%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 34        | 6.32%   |
| Elan ELAN:Fingerprint                                                      | 34        | 6.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 6.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 33        | 6.13%   |
| Validity Sensors Synaptics WBDI                                            | 26        | 4.83%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 25        | 4.65%   |
| Shenzhen Goodix FingerPrint                                                | 24        | 4.46%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 3.53%   |
| Validity Sensors VFS491                                                    | 18        | 3.35%   |
| STMicroelectronics Fingerprint Reader                                      | 16        | 2.97%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 2.6%    |
| Shenzhen Goodix  FingerPrint Device                                        | 14        | 2.6%    |
| Shenzhen Goodix Fingerprint Reader                                         | 14        | 2.6%    |
| AuthenTec AES2810                                                          | 14        | 2.6%    |
| Synaptics  WBDI                                                            | 13        | 2.42%   |
| Synaptics WBDI                                                             | 12        | 2.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.04%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 1.67%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 1.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.49%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 1.49%   |
| Synaptics UWP WBDI                                                         | 8         | 1.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.3%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.3%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 1.3%    |
| Elan ELAN:ARM-M4                                                           | 6         | 1.12%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.12%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 0.93%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.93%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.74%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.74%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.56%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 3         | 0.56%   |
| AuthenTec AES1600                                                          | 3         | 0.56%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.37%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.37%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.37%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 87        | 44.16%  |
| Alcor Micro               | 38        | 19.29%  |
| O2 Micro                  | 25        | 12.69%  |
| Upek                      | 22        | 11.17%  |
| Lenovo                    | 12        | 6.09%   |
| Gemalto (was Gemplus)     | 4         | 2.03%   |
| Yubico.com                | 2         | 1.02%   |
| SCM Microsystems          | 2         | 1.02%   |
| Aladdin Knowledge Systems | 2         | 1.02%   |
| In Focus Systems          | 1         | 0.51%   |
| Giesecke & Devrient       | 1         | 0.51%   |
| Clay Logic                | 1         | 0.51%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 48        | 24.37%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 35        | 17.77%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 11.17%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 10.66%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 9.14%   |
| Broadcom 5880                                                                | 14        | 7.11%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 6.09%   |
| Broadcom 58200                                                               | 6         | 3.05%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 2.03%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 2.03%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.52%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.02%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.51%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.51%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.51%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.51%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.51%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.51%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.51%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.51%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3903      | 70.91%  |
| 1     | 1288      | 23.4%   |
| 2     | 252       | 4.58%   |
| 3     | 40        | 0.73%   |
| 4     | 12        | 0.22%   |
| 5     | 5         | 0.09%   |
| 8     | 2         | 0.04%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 530       | 27.85%  |
| Graphics card            | 413       | 21.7%   |
| Net/wireless             | 277       | 14.56%  |
| Chipcard                 | 179       | 9.41%   |
| Communication controller | 110       | 5.78%   |
| Multimedia controller    | 100       | 5.25%   |
| Unassigned class         | 46        | 2.42%   |
| Bluetooth                | 41        | 2.15%   |
| Camera                   | 38        | 2%      |
| Storage                  | 33        | 1.73%   |
| Sound                    | 33        | 1.73%   |
| Net/ethernet             | 26        | 1.37%   |
| Network                  | 15        | 0.79%   |
| Modem                    | 13        | 0.68%   |
| Card reader              | 9         | 0.47%   |
| Dvb card                 | 8         | 0.42%   |
| Storage/raid             | 7         | 0.37%   |
| Storage/ide              | 7         | 0.37%   |
| Firewire controller      | 7         | 0.37%   |
| Flash memory             | 4         | 0.21%   |
| Tv card                  | 3         | 0.16%   |
| Video                    | 1         | 0.05%   |
| Unclassified device      | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |

