Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 3967

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0PV3YR A05                  | Server      | [11731e6ece](https://linux-hardware.org/?probe=11731e6ece) | Apr 01, 2022 |
| ASRock        | G31M-S                      | Desktop     | [33737ec5ba](https://linux-hardware.org/?probe=33737ec5ba) | Apr 01, 2022 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [5f95e49b5f](https://linux-hardware.org/?probe=5f95e49b5f) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4dccfefe8a](https://linux-hardware.org/?probe=4dccfefe8a) | Mar 31, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [5215972642](https://linux-hardware.org/?probe=5215972642) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c226f684e8](https://linux-hardware.org/?probe=c226f684e8) | Mar 31, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [6096184486](https://linux-hardware.org/?probe=6096184486) | Mar 31, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [f646cb03d2](https://linux-hardware.org/?probe=f646cb03d2) | Mar 31, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c8236dd974](https://linux-hardware.org/?probe=c8236dd974) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M91p 4524AS3    | Desktop     | [c338f4ffd4](https://linux-hardware.org/?probe=c338f4ffd4) | Mar 31, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [ea7372d041](https://linux-hardware.org/?probe=ea7372d041) | Mar 31, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [f330902df9](https://linux-hardware.org/?probe=f330902df9) | Mar 31, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9a7f8f2cf8](https://linux-hardware.org/?probe=9a7f8f2cf8) | Mar 31, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [38772371c1](https://linux-hardware.org/?probe=38772371c1) | Mar 31, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [ec255331c0](https://linux-hardware.org/?probe=ec255331c0) | Mar 31, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [c6d64363b9](https://linux-hardware.org/?probe=c6d64363b9) | Mar 31, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f2dc785121](https://linux-hardware.org/?probe=f2dc785121) | Mar 31, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [cbdf6cd38b](https://linux-hardware.org/?probe=cbdf6cd38b) | Mar 31, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [54ebfbd580](https://linux-hardware.org/?probe=54ebfbd580) | Mar 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [2c37064716](https://linux-hardware.org/?probe=2c37064716) | Mar 31, 2022 |
| Dell          | 0MN1TX A02                  | Desktop     | [f9be94fa9b](https://linux-hardware.org/?probe=f9be94fa9b) | Mar 31, 2022 |
| Dell          | OptiPlex 7010               | Desktop     | [f1167c797e](https://linux-hardware.org/?probe=f1167c797e) | Mar 31, 2022 |
| ASUSTek       | Zephyrus M GU502GW          | Notebook    | [9d604c46d4](https://linux-hardware.org/?probe=9d604c46d4) | Mar 30, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [edf21d564c](https://linux-hardware.org/?probe=edf21d564c) | Mar 30, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [d19fa42706](https://linux-hardware.org/?probe=d19fa42706) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [bf34d64bea](https://linux-hardware.org/?probe=bf34d64bea) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [c230fd441f](https://linux-hardware.org/?probe=c230fd441f) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [11b3bf1895](https://linux-hardware.org/?probe=11b3bf1895) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [f83d4681a5](https://linux-hardware.org/?probe=f83d4681a5) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [760130a724](https://linux-hardware.org/?probe=760130a724) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [0eba3f5110](https://linux-hardware.org/?probe=0eba3f5110) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [9031594389](https://linux-hardware.org/?probe=9031594389) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [70136a8a52](https://linux-hardware.org/?probe=70136a8a52) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [4b33b74c8d](https://linux-hardware.org/?probe=4b33b74c8d) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [ba75246f7d](https://linux-hardware.org/?probe=ba75246f7d) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [23c567f8ae](https://linux-hardware.org/?probe=23c567f8ae) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [c98ccf97ad](https://linux-hardware.org/?probe=c98ccf97ad) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [44539860bb](https://linux-hardware.org/?probe=44539860bb) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [2620b02831](https://linux-hardware.org/?probe=2620b02831) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [61f09eb46a](https://linux-hardware.org/?probe=61f09eb46a) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [7752026321](https://linux-hardware.org/?probe=7752026321) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [ab864365bf](https://linux-hardware.org/?probe=ab864365bf) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [e05e42cfe8](https://linux-hardware.org/?probe=e05e42cfe8) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [01a45d419a](https://linux-hardware.org/?probe=01a45d419a) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [933efd1329](https://linux-hardware.org/?probe=933efd1329) | Mar 30, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [9359d0549c](https://linux-hardware.org/?probe=9359d0549c) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [b3fbea8036](https://linux-hardware.org/?probe=b3fbea8036) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [cab2537c84](https://linux-hardware.org/?probe=cab2537c84) | Mar 30, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [d42d4a24cd](https://linux-hardware.org/?probe=d42d4a24cd) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [9cdc782ae4](https://linux-hardware.org/?probe=9cdc782ae4) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [82626bd1a6](https://linux-hardware.org/?probe=82626bd1a6) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [cd13aaa811](https://linux-hardware.org/?probe=cd13aaa811) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [62d19db44d](https://linux-hardware.org/?probe=62d19db44d) | Mar 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [c6726e85ab](https://linux-hardware.org/?probe=c6726e85ab) | Mar 30, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [e299a5abe8](https://linux-hardware.org/?probe=e299a5abe8) | Mar 30, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d466363fa3](https://linux-hardware.org/?probe=d466363fa3) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [4f76df5f21](https://linux-hardware.org/?probe=4f76df5f21) | Mar 30, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [cefeb9762e](https://linux-hardware.org/?probe=cefeb9762e) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [a26bba474b](https://linux-hardware.org/?probe=a26bba474b) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [e29a05bc98](https://linux-hardware.org/?probe=e29a05bc98) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [3577dffc4a](https://linux-hardware.org/?probe=3577dffc4a) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [8c3096482b](https://linux-hardware.org/?probe=8c3096482b) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [d479b367f3](https://linux-hardware.org/?probe=d479b367f3) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [5f02f56ad9](https://linux-hardware.org/?probe=5f02f56ad9) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [b15259b9b9](https://linux-hardware.org/?probe=b15259b9b9) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [781cfeebd7](https://linux-hardware.org/?probe=781cfeebd7) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [3c1da81190](https://linux-hardware.org/?probe=3c1da81190) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [64fefc70d1](https://linux-hardware.org/?probe=64fefc70d1) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [38ef312ce4](https://linux-hardware.org/?probe=38ef312ce4) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [80fbb03d04](https://linux-hardware.org/?probe=80fbb03d04) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c561ead77d](https://linux-hardware.org/?probe=c561ead77d) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [8fb97ff64b](https://linux-hardware.org/?probe=8fb97ff64b) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [64849cb92f](https://linux-hardware.org/?probe=64849cb92f) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [71c9be4b4e](https://linux-hardware.org/?probe=71c9be4b4e) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [8c96659249](https://linux-hardware.org/?probe=8c96659249) | Mar 30, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ade49f5201](https://linux-hardware.org/?probe=ade49f5201) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [1db213284b](https://linux-hardware.org/?probe=1db213284b) | Mar 30, 2022 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [d4352ae69d](https://linux-hardware.org/?probe=d4352ae69d) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [b36ea3eb7b](https://linux-hardware.org/?probe=b36ea3eb7b) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [731fe969ef](https://linux-hardware.org/?probe=731fe969ef) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [354d8402cf](https://linux-hardware.org/?probe=354d8402cf) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [c2ceaea91f](https://linux-hardware.org/?probe=c2ceaea91f) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [ec7465ab62](https://linux-hardware.org/?probe=ec7465ab62) | Mar 30, 2022 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [9c5ceb2c7d](https://linux-hardware.org/?probe=9c5ceb2c7d) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [a7bbd66733](https://linux-hardware.org/?probe=a7bbd66733) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [b981a3ff94](https://linux-hardware.org/?probe=b981a3ff94) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [21fb011d5a](https://linux-hardware.org/?probe=21fb011d5a) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [97d8bc4ad6](https://linux-hardware.org/?probe=97d8bc4ad6) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [4ce8485084](https://linux-hardware.org/?probe=4ce8485084) | Mar 30, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [8167ee62f2](https://linux-hardware.org/?probe=8167ee62f2) | Mar 30, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [39d3a3ac9d](https://linux-hardware.org/?probe=39d3a3ac9d) | Mar 30, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [50780eda28](https://linux-hardware.org/?probe=50780eda28) | Mar 30, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [078946745f](https://linux-hardware.org/?probe=078946745f) | Mar 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f46afcf627](https://linux-hardware.org/?probe=f46afcf627) | Mar 30, 2022 |
| Getac         | B300G5                      | Notebook    | [9a1ef08d85](https://linux-hardware.org/?probe=9a1ef08d85) | Mar 30, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [3e182ccdbe](https://linux-hardware.org/?probe=3e182ccdbe) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [2515533d52](https://linux-hardware.org/?probe=2515533d52) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [f9f0d59a6a](https://linux-hardware.org/?probe=f9f0d59a6a) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [5d91344a23](https://linux-hardware.org/?probe=5d91344a23) | Mar 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [048725554b](https://linux-hardware.org/?probe=048725554b) | Mar 29, 2022 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [9424649aa5](https://linux-hardware.org/?probe=9424649aa5) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [df356ba664](https://linux-hardware.org/?probe=df356ba664) | Mar 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [3cadd2951c](https://linux-hardware.org/?probe=3cadd2951c) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [3ab0308776](https://linux-hardware.org/?probe=3ab0308776) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [0a003d8ab8](https://linux-hardware.org/?probe=0a003d8ab8) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [cacdb5e357](https://linux-hardware.org/?probe=cacdb5e357) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [95abe0d79d](https://linux-hardware.org/?probe=95abe0d79d) | Mar 29, 2022 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [b9b4a49da0](https://linux-hardware.org/?probe=b9b4a49da0) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [9a53450a67](https://linux-hardware.org/?probe=9a53450a67) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [0a51e9f7e3](https://linux-hardware.org/?probe=0a51e9f7e3) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [d2fdc4290a](https://linux-hardware.org/?probe=d2fdc4290a) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [3881639f77](https://linux-hardware.org/?probe=3881639f77) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [0c1586c75f](https://linux-hardware.org/?probe=0c1586c75f) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [506d1ce2f4](https://linux-hardware.org/?probe=506d1ce2f4) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [f8ce95fcf1](https://linux-hardware.org/?probe=f8ce95fcf1) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2441749cc0](https://linux-hardware.org/?probe=2441749cc0) | Mar 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [47040a16f3](https://linux-hardware.org/?probe=47040a16f3) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0394259b79](https://linux-hardware.org/?probe=0394259b79) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [bf18a492d3](https://linux-hardware.org/?probe=bf18a492d3) | Mar 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [6a9aeeecb7](https://linux-hardware.org/?probe=6a9aeeecb7) | Mar 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [d132380ec5](https://linux-hardware.org/?probe=d132380ec5) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [6e07849e21](https://linux-hardware.org/?probe=6e07849e21) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [1bd6fc632b](https://linux-hardware.org/?probe=1bd6fc632b) | Mar 29, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b38fbe5154](https://linux-hardware.org/?probe=b38fbe5154) | Mar 29, 2022 |
| BUYMPC Mic... | EU3G00                      | Notebook    | [28ad16f130](https://linux-hardware.org/?probe=28ad16f130) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [660ce58e45](https://linux-hardware.org/?probe=660ce58e45) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bd0fe415fe](https://linux-hardware.org/?probe=bd0fe415fe) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8fc2c1595f](https://linux-hardware.org/?probe=8fc2c1595f) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f1cbe3ec83](https://linux-hardware.org/?probe=f1cbe3ec83) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [345d3921c7](https://linux-hardware.org/?probe=345d3921c7) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [3278bd5768](https://linux-hardware.org/?probe=3278bd5768) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bf479b678d](https://linux-hardware.org/?probe=bf479b678d) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9a7a8222ac](https://linux-hardware.org/?probe=9a7a8222ac) | Mar 29, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [519c65be70](https://linux-hardware.org/?probe=519c65be70) | Mar 29, 2022 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [dbf958a815](https://linux-hardware.org/?probe=dbf958a815) | Mar 29, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [f21f3af1ca](https://linux-hardware.org/?probe=f21f3af1ca) | Mar 29, 2022 |
| MSI           | H81M-P33                    | Desktop     | [853b5b2236](https://linux-hardware.org/?probe=853b5b2236) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [74b5af8c0c](https://linux-hardware.org/?probe=74b5af8c0c) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a07c0e57cc](https://linux-hardware.org/?probe=a07c0e57cc) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2313250bcb](https://linux-hardware.org/?probe=2313250bcb) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c689323c11](https://linux-hardware.org/?probe=c689323c11) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ab646d59d1](https://linux-hardware.org/?probe=ab646d59d1) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [018c06cb92](https://linux-hardware.org/?probe=018c06cb92) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d2588cac79](https://linux-hardware.org/?probe=d2588cac79) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2b871b3da9](https://linux-hardware.org/?probe=2b871b3da9) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [aa39d43d92](https://linux-hardware.org/?probe=aa39d43d92) | Mar 29, 2022 |
| MicronPc_M... | EU3G00                      | Notebook    | [2d442b0016](https://linux-hardware.org/?probe=2d442b0016) | Mar 29, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [3c24d3510d](https://linux-hardware.org/?probe=3c24d3510d) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d7da50d464](https://linux-hardware.org/?probe=d7da50d464) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5c562b0228](https://linux-hardware.org/?probe=5c562b0228) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8c1d82154a](https://linux-hardware.org/?probe=8c1d82154a) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9e4fb8b26d](https://linux-hardware.org/?probe=9e4fb8b26d) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [38d65a3bc2](https://linux-hardware.org/?probe=38d65a3bc2) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d4733c58dd](https://linux-hardware.org/?probe=d4733c58dd) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [eaf3a98419](https://linux-hardware.org/?probe=eaf3a98419) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6a6bb9ee06](https://linux-hardware.org/?probe=6a6bb9ee06) | Mar 29, 2022 |
| Foxconn       | H61MXL-K                    | Desktop     | [50b743dab8](https://linux-hardware.org/?probe=50b743dab8) | Mar 29, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [0ff3da859e](https://linux-hardware.org/?probe=0ff3da859e) | Mar 29, 2022 |
| ASUSTek       | P6T                         | Desktop     | [00868ae20c](https://linux-hardware.org/?probe=00868ae20c) | Mar 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [cc40a0b5fc](https://linux-hardware.org/?probe=cc40a0b5fc) | Mar 29, 2022 |
| Acer          | Aspire 1640                 | Notebook    | [93f44fda5e](https://linux-hardware.org/?probe=93f44fda5e) | Mar 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [e9097a9cd4](https://linux-hardware.org/?probe=e9097a9cd4) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [440e0a4b6a](https://linux-hardware.org/?probe=440e0a4b6a) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [12f752cfc8](https://linux-hardware.org/?probe=12f752cfc8) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a974509dee](https://linux-hardware.org/?probe=a974509dee) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d7a5ae41f2](https://linux-hardware.org/?probe=d7a5ae41f2) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [008012c088](https://linux-hardware.org/?probe=008012c088) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [17805ee544](https://linux-hardware.org/?probe=17805ee544) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [54e0481249](https://linux-hardware.org/?probe=54e0481249) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4d81d40f34](https://linux-hardware.org/?probe=4d81d40f34) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c7ff0867fc](https://linux-hardware.org/?probe=c7ff0867fc) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e216cbf213](https://linux-hardware.org/?probe=e216cbf213) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5709a6e5d0](https://linux-hardware.org/?probe=5709a6e5d0) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0e99c719be](https://linux-hardware.org/?probe=0e99c719be) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f32dd8d233](https://linux-hardware.org/?probe=f32dd8d233) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fd4baa1c1e](https://linux-hardware.org/?probe=fd4baa1c1e) | Mar 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [7c1a584c98](https://linux-hardware.org/?probe=7c1a584c98) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d3d93cf582](https://linux-hardware.org/?probe=d3d93cf582) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [456c7e3e39](https://linux-hardware.org/?probe=456c7e3e39) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [be84a067b1](https://linux-hardware.org/?probe=be84a067b1) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f0d0126345](https://linux-hardware.org/?probe=f0d0126345) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c8d9b1bbbb](https://linux-hardware.org/?probe=c8d9b1bbbb) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [1c3b0cc9e8](https://linux-hardware.org/?probe=1c3b0cc9e8) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a8ef2cbae1](https://linux-hardware.org/?probe=a8ef2cbae1) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [719f1a8407](https://linux-hardware.org/?probe=719f1a8407) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [956cfe6d5c](https://linux-hardware.org/?probe=956cfe6d5c) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4b6a0f5fd2](https://linux-hardware.org/?probe=4b6a0f5fd2) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6d24b5808d](https://linux-hardware.org/?probe=6d24b5808d) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f4fea2bd15](https://linux-hardware.org/?probe=f4fea2bd15) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a9c2095b0b](https://linux-hardware.org/?probe=a9c2095b0b) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f5176d36d5](https://linux-hardware.org/?probe=f5176d36d5) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e23415449a](https://linux-hardware.org/?probe=e23415449a) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [02740e983b](https://linux-hardware.org/?probe=02740e983b) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2c0ff98f42](https://linux-hardware.org/?probe=2c0ff98f42) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7bde6013e3](https://linux-hardware.org/?probe=7bde6013e3) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6659ce53aa](https://linux-hardware.org/?probe=6659ce53aa) | Mar 28, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [7fe672d3a9](https://linux-hardware.org/?probe=7fe672d3a9) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ddac67a3a6](https://linux-hardware.org/?probe=ddac67a3a6) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fc280527ac](https://linux-hardware.org/?probe=fc280527ac) | Mar 28, 2022 |
| HP            | Pavilion g7                 | Notebook    | [44a6ea06b0](https://linux-hardware.org/?probe=44a6ea06b0) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2283ac732b](https://linux-hardware.org/?probe=2283ac732b) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0cc32ff2fb](https://linux-hardware.org/?probe=0cc32ff2fb) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [dae44fb976](https://linux-hardware.org/?probe=dae44fb976) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [63946e4ce7](https://linux-hardware.org/?probe=63946e4ce7) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f9282ec588](https://linux-hardware.org/?probe=f9282ec588) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e51526c34e](https://linux-hardware.org/?probe=e51526c34e) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ebc5c80b22](https://linux-hardware.org/?probe=ebc5c80b22) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b9443a4996](https://linux-hardware.org/?probe=b9443a4996) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d98f1e1341](https://linux-hardware.org/?probe=d98f1e1341) | Mar 28, 2022 |
| Radxa         | ROCK Pi 4B                  | Soc         | [9ae359b8f0](https://linux-hardware.org/?probe=9ae359b8f0) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f384fccae7](https://linux-hardware.org/?probe=f384fccae7) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [22132403ff](https://linux-hardware.org/?probe=22132403ff) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4f653f41d0](https://linux-hardware.org/?probe=4f653f41d0) | Mar 28, 2022 |
| Radxa         | ROCK Pi 4B                  | Soc         | [a8c2931b5a](https://linux-hardware.org/?probe=a8c2931b5a) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ab1880f222](https://linux-hardware.org/?probe=ab1880f222) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [77fa32cd21](https://linux-hardware.org/?probe=77fa32cd21) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cc5db0e4f8](https://linux-hardware.org/?probe=cc5db0e4f8) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [50d7e4493e](https://linux-hardware.org/?probe=50d7e4493e) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2e4fe83644](https://linux-hardware.org/?probe=2e4fe83644) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2d7895b0fc](https://linux-hardware.org/?probe=2d7895b0fc) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c6baccbb87](https://linux-hardware.org/?probe=c6baccbb87) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6636104d38](https://linux-hardware.org/?probe=6636104d38) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c3380865d9](https://linux-hardware.org/?probe=c3380865d9) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [1bd520a5d4](https://linux-hardware.org/?probe=1bd520a5d4) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [637b3b139a](https://linux-hardware.org/?probe=637b3b139a) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [389c81b3ba](https://linux-hardware.org/?probe=389c81b3ba) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c0f7394bf5](https://linux-hardware.org/?probe=c0f7394bf5) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e6fbc3ef69](https://linux-hardware.org/?probe=e6fbc3ef69) | Mar 28, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c2ae1d8052](https://linux-hardware.org/?probe=c2ae1d8052) | Mar 28, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [2c06de39ad](https://linux-hardware.org/?probe=2c06de39ad) | Mar 28, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [94a20fae0d](https://linux-hardware.org/?probe=94a20fae0d) | Mar 28, 2022 |
| Lenovo        | ThinkPad T61 7661WE7        | Notebook    | [30fce12920](https://linux-hardware.org/?probe=30fce12920) | Mar 27, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [44913af0e4](https://linux-hardware.org/?probe=44913af0e4) | Mar 27, 2022 |
| Dell          | Latitude 3410               | Notebook    | [503bb0a712](https://linux-hardware.org/?probe=503bb0a712) | Mar 27, 2022 |
| Dell          | Latitude 3410               | Notebook    | [5590356e12](https://linux-hardware.org/?probe=5590356e12) | Mar 27, 2022 |
| Apple         | Mac-CFF7D910A743CAAF iMa... | All in one  | [bf70acd34b](https://linux-hardware.org/?probe=bf70acd34b) | Mar 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a8cacc7845](https://linux-hardware.org/?probe=a8cacc7845) | Mar 27, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [11e1d2297b](https://linux-hardware.org/?probe=11e1d2297b) | Mar 27, 2022 |
| Lenovo        | ThinkPad T495 20NKS13Q00    | Notebook    | [95d0d1e82a](https://linux-hardware.org/?probe=95d0d1e82a) | Mar 27, 2022 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [0bf3028253](https://linux-hardware.org/?probe=0bf3028253) | Mar 27, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [a356a33d0a](https://linux-hardware.org/?probe=a356a33d0a) | Mar 27, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [09b7586491](https://linux-hardware.org/?probe=09b7586491) | Mar 27, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [17724c0c21](https://linux-hardware.org/?probe=17724c0c21) | Mar 27, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [aeb87f174c](https://linux-hardware.org/?probe=aeb87f174c) | Mar 27, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [2c4815fb69](https://linux-hardware.org/?probe=2c4815fb69) | Mar 26, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [dc35b742d2](https://linux-hardware.org/?probe=dc35b742d2) | Mar 26, 2022 |
| Lenovo        | ThinkCentre M91p 4524AS3    | Desktop     | [7e1b536f6b](https://linux-hardware.org/?probe=7e1b536f6b) | Mar 26, 2022 |
| HP            | ProBook 6470b               | Notebook    | [02dd6d658c](https://linux-hardware.org/?probe=02dd6d658c) | Mar 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d23f0ea2dc](https://linux-hardware.org/?probe=d23f0ea2dc) | Mar 26, 2022 |
| Biostar       | B450MH                      | Desktop     | [9152345747](https://linux-hardware.org/?probe=9152345747) | Mar 26, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [c8a76eb9ae](https://linux-hardware.org/?probe=c8a76eb9ae) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7807908b58](https://linux-hardware.org/?probe=7807908b58) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [dde1d560f2](https://linux-hardware.org/?probe=dde1d560f2) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f434655dac](https://linux-hardware.org/?probe=f434655dac) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8a36194692](https://linux-hardware.org/?probe=8a36194692) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [65ba230e9d](https://linux-hardware.org/?probe=65ba230e9d) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0c1eb0be3b](https://linux-hardware.org/?probe=0c1eb0be3b) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [33fca0b8e8](https://linux-hardware.org/?probe=33fca0b8e8) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2c807078d7](https://linux-hardware.org/?probe=2c807078d7) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6b32ecb341](https://linux-hardware.org/?probe=6b32ecb341) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b437d8da72](https://linux-hardware.org/?probe=b437d8da72) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5125c0521c](https://linux-hardware.org/?probe=5125c0521c) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [abc708b290](https://linux-hardware.org/?probe=abc708b290) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [1e1bb4af73](https://linux-hardware.org/?probe=1e1bb4af73) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9704e96de5](https://linux-hardware.org/?probe=9704e96de5) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e7330e61bb](https://linux-hardware.org/?probe=e7330e61bb) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c27e4bc406](https://linux-hardware.org/?probe=c27e4bc406) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bc3f554cff](https://linux-hardware.org/?probe=bc3f554cff) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c5ee11038e](https://linux-hardware.org/?probe=c5ee11038e) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9a61f61544](https://linux-hardware.org/?probe=9a61f61544) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fcdb43fa91](https://linux-hardware.org/?probe=fcdb43fa91) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9d79605905](https://linux-hardware.org/?probe=9d79605905) | Mar 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [24664b0486](https://linux-hardware.org/?probe=24664b0486) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [aa99f96a44](https://linux-hardware.org/?probe=aa99f96a44) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [df8eb24e3c](https://linux-hardware.org/?probe=df8eb24e3c) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c657a9d192](https://linux-hardware.org/?probe=c657a9d192) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4336eaee74](https://linux-hardware.org/?probe=4336eaee74) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [74fcf8c949](https://linux-hardware.org/?probe=74fcf8c949) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8d3414ad53](https://linux-hardware.org/?probe=8d3414ad53) | Mar 25, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [d809ca0f7a](https://linux-hardware.org/?probe=d809ca0f7a) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [78578266ad](https://linux-hardware.org/?probe=78578266ad) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7d91fcf80d](https://linux-hardware.org/?probe=7d91fcf80d) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cf2a01ff9c](https://linux-hardware.org/?probe=cf2a01ff9c) | Mar 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [1cb13706a4](https://linux-hardware.org/?probe=1cb13706a4) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [82faeea830](https://linux-hardware.org/?probe=82faeea830) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cf84791e1f](https://linux-hardware.org/?probe=cf84791e1f) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ba101b1005](https://linux-hardware.org/?probe=ba101b1005) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c36888e0db](https://linux-hardware.org/?probe=c36888e0db) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4d1111031e](https://linux-hardware.org/?probe=4d1111031e) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c581266c76](https://linux-hardware.org/?probe=c581266c76) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9744a2e3db](https://linux-hardware.org/?probe=9744a2e3db) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b7d0c4f4c3](https://linux-hardware.org/?probe=b7d0c4f4c3) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e4f0fbf6c3](https://linux-hardware.org/?probe=e4f0fbf6c3) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b530d04a82](https://linux-hardware.org/?probe=b530d04a82) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b322ce7a81](https://linux-hardware.org/?probe=b322ce7a81) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f7b8fa68ec](https://linux-hardware.org/?probe=f7b8fa68ec) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [215f7f551f](https://linux-hardware.org/?probe=215f7f551f) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ac11ee21c5](https://linux-hardware.org/?probe=ac11ee21c5) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [62c53df9ac](https://linux-hardware.org/?probe=62c53df9ac) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8f3bdec5eb](https://linux-hardware.org/?probe=8f3bdec5eb) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [279defcae0](https://linux-hardware.org/?probe=279defcae0) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [3263f3eee4](https://linux-hardware.org/?probe=3263f3eee4) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e1dfe6c51c](https://linux-hardware.org/?probe=e1dfe6c51c) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [84ee0b4519](https://linux-hardware.org/?probe=84ee0b4519) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d835835c89](https://linux-hardware.org/?probe=d835835c89) | Mar 25, 2022 |
| Dell          | Inspiron 1521               | Notebook    | [546a428d9d](https://linux-hardware.org/?probe=546a428d9d) | Mar 25, 2022 |
| Intel         | B75                         | Desktop     | [9f73efdcc8](https://linux-hardware.org/?probe=9f73efdcc8) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [73117249bd](https://linux-hardware.org/?probe=73117249bd) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [40d76c9602](https://linux-hardware.org/?probe=40d76c9602) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c4062b3cd1](https://linux-hardware.org/?probe=c4062b3cd1) | Mar 25, 2022 |
| Dell          | Latitude E6320              | Notebook    | [9f34afdd61](https://linux-hardware.org/?probe=9f34afdd61) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [34a1bfdb97](https://linux-hardware.org/?probe=34a1bfdb97) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7b5dde6c42](https://linux-hardware.org/?probe=7b5dde6c42) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fcc6373f81](https://linux-hardware.org/?probe=fcc6373f81) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6c83d2fc1a](https://linux-hardware.org/?probe=6c83d2fc1a) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [21864991c1](https://linux-hardware.org/?probe=21864991c1) | Mar 25, 2022 |
| Lenovo        | E31-80 80MX                 | Notebook    | [8dc93e34e9](https://linux-hardware.org/?probe=8dc93e34e9) | Mar 25, 2022 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [8c732f5ec8](https://linux-hardware.org/?probe=8c732f5ec8) | Mar 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f32a9d892c](https://linux-hardware.org/?probe=f32a9d892c) | Mar 25, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d51166d2be](https://linux-hardware.org/?probe=d51166d2be) | Mar 25, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [496d2fd146](https://linux-hardware.org/?probe=496d2fd146) | Mar 25, 2022 |
| Supermicro    | X11SSH-F                    | Server      | [a50c6c203e](https://linux-hardware.org/?probe=a50c6c203e) | Mar 25, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [19cb24e20c](https://linux-hardware.org/?probe=19cb24e20c) | Mar 25, 2022 |
| Dell          | Latitude E6420              | Notebook    | [bcf7ead91d](https://linux-hardware.org/?probe=bcf7ead91d) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [aab65645ee](https://linux-hardware.org/?probe=aab65645ee) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [62cb62ab87](https://linux-hardware.org/?probe=62cb62ab87) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ae6ec4d664](https://linux-hardware.org/?probe=ae6ec4d664) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f2dffc79e4](https://linux-hardware.org/?probe=f2dffc79e4) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [15754d5c95](https://linux-hardware.org/?probe=15754d5c95) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ee8a7cd57e](https://linux-hardware.org/?probe=ee8a7cd57e) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [94c7609895](https://linux-hardware.org/?probe=94c7609895) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0d4426b790](https://linux-hardware.org/?probe=0d4426b790) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7102173ac3](https://linux-hardware.org/?probe=7102173ac3) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [62af595883](https://linux-hardware.org/?probe=62af595883) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bb744f9763](https://linux-hardware.org/?probe=bb744f9763) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2ccfbd59d3](https://linux-hardware.org/?probe=2ccfbd59d3) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [65cb054464](https://linux-hardware.org/?probe=65cb054464) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d734538c37](https://linux-hardware.org/?probe=d734538c37) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bf707614f0](https://linux-hardware.org/?probe=bf707614f0) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [28be54345a](https://linux-hardware.org/?probe=28be54345a) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6e466ec146](https://linux-hardware.org/?probe=6e466ec146) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [995b41ef83](https://linux-hardware.org/?probe=995b41ef83) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e09f56c996](https://linux-hardware.org/?probe=e09f56c996) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a0ada25db4](https://linux-hardware.org/?probe=a0ada25db4) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [47936430a1](https://linux-hardware.org/?probe=47936430a1) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [37c1241c1c](https://linux-hardware.org/?probe=37c1241c1c) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [41d33f527a](https://linux-hardware.org/?probe=41d33f527a) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f136c79dbc](https://linux-hardware.org/?probe=f136c79dbc) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [128118c93d](https://linux-hardware.org/?probe=128118c93d) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e87cdc1828](https://linux-hardware.org/?probe=e87cdc1828) | Mar 24, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [9cad677222](https://linux-hardware.org/?probe=9cad677222) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8f1306f636](https://linux-hardware.org/?probe=8f1306f636) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6635105391](https://linux-hardware.org/?probe=6635105391) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cc133ffbd7](https://linux-hardware.org/?probe=cc133ffbd7) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b86ea04329](https://linux-hardware.org/?probe=b86ea04329) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [baab66b8b3](https://linux-hardware.org/?probe=baab66b8b3) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [05e7265b57](https://linux-hardware.org/?probe=05e7265b57) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fe835fdaef](https://linux-hardware.org/?probe=fe835fdaef) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [90c5855c40](https://linux-hardware.org/?probe=90c5855c40) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a67d7b4b52](https://linux-hardware.org/?probe=a67d7b4b52) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2122efb62f](https://linux-hardware.org/?probe=2122efb62f) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [dff3a1e5e0](https://linux-hardware.org/?probe=dff3a1e5e0) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [28c45e2dc9](https://linux-hardware.org/?probe=28c45e2dc9) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fb057065f3](https://linux-hardware.org/?probe=fb057065f3) | Mar 24, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [53ed9f8c5e](https://linux-hardware.org/?probe=53ed9f8c5e) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fe472b0e78](https://linux-hardware.org/?probe=fe472b0e78) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b7a00a8bde](https://linux-hardware.org/?probe=b7a00a8bde) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [53b374ae77](https://linux-hardware.org/?probe=53b374ae77) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f6ed637eb2](https://linux-hardware.org/?probe=f6ed637eb2) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bb47dbf24f](https://linux-hardware.org/?probe=bb47dbf24f) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [392e41cec2](https://linux-hardware.org/?probe=392e41cec2) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [58f1f922d2](https://linux-hardware.org/?probe=58f1f922d2) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [367de3521a](https://linux-hardware.org/?probe=367de3521a) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cd3f77fcf2](https://linux-hardware.org/?probe=cd3f77fcf2) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6a59e4c1b2](https://linux-hardware.org/?probe=6a59e4c1b2) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [93e3bd611b](https://linux-hardware.org/?probe=93e3bd611b) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8102e35a3d](https://linux-hardware.org/?probe=8102e35a3d) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ab53fea207](https://linux-hardware.org/?probe=ab53fea207) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5868e6209c](https://linux-hardware.org/?probe=5868e6209c) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c510eb8c99](https://linux-hardware.org/?probe=c510eb8c99) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2a93c0b48a](https://linux-hardware.org/?probe=2a93c0b48a) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9a536804c6](https://linux-hardware.org/?probe=9a536804c6) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fde5826e36](https://linux-hardware.org/?probe=fde5826e36) | Mar 24, 2022 |
| Dell          | Latitude E6420              | Notebook    | [bb8709d24f](https://linux-hardware.org/?probe=bb8709d24f) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d4144cc441](https://linux-hardware.org/?probe=d4144cc441) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5d45d7b64f](https://linux-hardware.org/?probe=5d45d7b64f) | Mar 24, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3c0bae87d1](https://linux-hardware.org/?probe=3c0bae87d1) | Mar 24, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [00fe92cee0](https://linux-hardware.org/?probe=00fe92cee0) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c291d8eef5](https://linux-hardware.org/?probe=c291d8eef5) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8f415cbd99](https://linux-hardware.org/?probe=8f415cbd99) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6460babd10](https://linux-hardware.org/?probe=6460babd10) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6d4bd09da1](https://linux-hardware.org/?probe=6d4bd09da1) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [794e2f8f7d](https://linux-hardware.org/?probe=794e2f8f7d) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b3241d1c46](https://linux-hardware.org/?probe=b3241d1c46) | Mar 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [9da89c589d](https://linux-hardware.org/?probe=9da89c589d) | Mar 24, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [9590cc2288](https://linux-hardware.org/?probe=9590cc2288) | Mar 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [b5fff905c8](https://linux-hardware.org/?probe=b5fff905c8) | Mar 24, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [4b955479cc](https://linux-hardware.org/?probe=4b955479cc) | Mar 24, 2022 |
| Biostar       | G31D-M7                     | Desktop     | [9882f292ea](https://linux-hardware.org/?probe=9882f292ea) | Mar 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9612c1e4bd](https://linux-hardware.org/?probe=9612c1e4bd) | Mar 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [08c4b3b7a5](https://linux-hardware.org/?probe=08c4b3b7a5) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4b51a85bb4](https://linux-hardware.org/?probe=4b51a85bb4) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [508ed60efb](https://linux-hardware.org/?probe=508ed60efb) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0b3b856a53](https://linux-hardware.org/?probe=0b3b856a53) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [18547acdd1](https://linux-hardware.org/?probe=18547acdd1) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f85ce6fe0c](https://linux-hardware.org/?probe=f85ce6fe0c) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [637e407924](https://linux-hardware.org/?probe=637e407924) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2616ad6b02](https://linux-hardware.org/?probe=2616ad6b02) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2e6b70998b](https://linux-hardware.org/?probe=2e6b70998b) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4626c38970](https://linux-hardware.org/?probe=4626c38970) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [eaf6dbd4f8](https://linux-hardware.org/?probe=eaf6dbd4f8) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e6f7fdf843](https://linux-hardware.org/?probe=e6f7fdf843) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8c6409aaba](https://linux-hardware.org/?probe=8c6409aaba) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bc27c043c5](https://linux-hardware.org/?probe=bc27c043c5) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [430a34c792](https://linux-hardware.org/?probe=430a34c792) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [1e4b172f54](https://linux-hardware.org/?probe=1e4b172f54) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6bf3e48b09](https://linux-hardware.org/?probe=6bf3e48b09) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [582db03602](https://linux-hardware.org/?probe=582db03602) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5e68d6cb5c](https://linux-hardware.org/?probe=5e68d6cb5c) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [50bc4ca517](https://linux-hardware.org/?probe=50bc4ca517) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e16f90e260](https://linux-hardware.org/?probe=e16f90e260) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [85a1ede47b](https://linux-hardware.org/?probe=85a1ede47b) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d47415dd08](https://linux-hardware.org/?probe=d47415dd08) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d7de78e9e1](https://linux-hardware.org/?probe=d7de78e9e1) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4853561da5](https://linux-hardware.org/?probe=4853561da5) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [418c2622f2](https://linux-hardware.org/?probe=418c2622f2) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a88309b4bf](https://linux-hardware.org/?probe=a88309b4bf) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [08dbb01903](https://linux-hardware.org/?probe=08dbb01903) | Mar 23, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [2376c46c04](https://linux-hardware.org/?probe=2376c46c04) | Mar 23, 2022 |
| Dell          | Latitude E7450              | Notebook    | [57111f23b4](https://linux-hardware.org/?probe=57111f23b4) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ffeb6952f6](https://linux-hardware.org/?probe=ffeb6952f6) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [22bb81595e](https://linux-hardware.org/?probe=22bb81595e) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [be978d1795](https://linux-hardware.org/?probe=be978d1795) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d9c9b752b6](https://linux-hardware.org/?probe=d9c9b752b6) | Mar 23, 2022 |
| Dell          | Latitude E7450              | Notebook    | [ad41ea623a](https://linux-hardware.org/?probe=ad41ea623a) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [17b58d5660](https://linux-hardware.org/?probe=17b58d5660) | Mar 23, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [847b9e1fbb](https://linux-hardware.org/?probe=847b9e1fbb) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [401373809f](https://linux-hardware.org/?probe=401373809f) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2b95b80b3c](https://linux-hardware.org/?probe=2b95b80b3c) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a6bb3d9848](https://linux-hardware.org/?probe=a6bb3d9848) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7c85c90d78](https://linux-hardware.org/?probe=7c85c90d78) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2a2cf984ae](https://linux-hardware.org/?probe=2a2cf984ae) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cb79c4afd7](https://linux-hardware.org/?probe=cb79c4afd7) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [3d143aaa23](https://linux-hardware.org/?probe=3d143aaa23) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0a88a77844](https://linux-hardware.org/?probe=0a88a77844) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [74de92b5d5](https://linux-hardware.org/?probe=74de92b5d5) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4be2205977](https://linux-hardware.org/?probe=4be2205977) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a50b453324](https://linux-hardware.org/?probe=a50b453324) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d822d3976a](https://linux-hardware.org/?probe=d822d3976a) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bf779a4e15](https://linux-hardware.org/?probe=bf779a4e15) | Mar 23, 2022 |
| Dell          | Inspiron 7400               | Notebook    | [a17dc3be48](https://linux-hardware.org/?probe=a17dc3be48) | Mar 23, 2022 |
| Dell          | 0NT78X A08                  | Server      | [99cdcd7a9d](https://linux-hardware.org/?probe=99cdcd7a9d) | Mar 23, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [31b072eae1](https://linux-hardware.org/?probe=31b072eae1) | Mar 23, 2022 |
| Apple         | Mac-F2218EC8                | All in one  | [eed3af8969](https://linux-hardware.org/?probe=eed3af8969) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [285d6800fc](https://linux-hardware.org/?probe=285d6800fc) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [33d0891c50](https://linux-hardware.org/?probe=33d0891c50) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8317fd0383](https://linux-hardware.org/?probe=8317fd0383) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b06e223c59](https://linux-hardware.org/?probe=b06e223c59) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [76aa9f3f9e](https://linux-hardware.org/?probe=76aa9f3f9e) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ab9b2cba96](https://linux-hardware.org/?probe=ab9b2cba96) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4a729eb987](https://linux-hardware.org/?probe=4a729eb987) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [34676db3b2](https://linux-hardware.org/?probe=34676db3b2) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d84c579f5d](https://linux-hardware.org/?probe=d84c579f5d) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2a7bb7679e](https://linux-hardware.org/?probe=2a7bb7679e) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [aafc2871d3](https://linux-hardware.org/?probe=aafc2871d3) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fcad1031fe](https://linux-hardware.org/?probe=fcad1031fe) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [04d444e019](https://linux-hardware.org/?probe=04d444e019) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [245849a085](https://linux-hardware.org/?probe=245849a085) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7e271264aa](https://linux-hardware.org/?probe=7e271264aa) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c557216143](https://linux-hardware.org/?probe=c557216143) | Mar 22, 2022 |
| Dell          | Latitude E6330              | Notebook    | [a8d483108b](https://linux-hardware.org/?probe=a8d483108b) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d510106ed6](https://linux-hardware.org/?probe=d510106ed6) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [74c5cea3d3](https://linux-hardware.org/?probe=74c5cea3d3) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [eaf7658e60](https://linux-hardware.org/?probe=eaf7658e60) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9b259c8e34](https://linux-hardware.org/?probe=9b259c8e34) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [46f732ce06](https://linux-hardware.org/?probe=46f732ce06) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [75f9b4edf4](https://linux-hardware.org/?probe=75f9b4edf4) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [245f481ab3](https://linux-hardware.org/?probe=245f481ab3) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ccce01ca4d](https://linux-hardware.org/?probe=ccce01ca4d) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fb4b10e80f](https://linux-hardware.org/?probe=fb4b10e80f) | Mar 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7a02e1b55c](https://linux-hardware.org/?probe=7a02e1b55c) | Mar 22, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [ccb3b312a1](https://linux-hardware.org/?probe=ccb3b312a1) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7662580f58](https://linux-hardware.org/?probe=7662580f58) | Mar 22, 2022 |
| HP            | 1589                        | Desktop     | [a97fa22164](https://linux-hardware.org/?probe=a97fa22164) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b2bd27f11b](https://linux-hardware.org/?probe=b2bd27f11b) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4133dff23f](https://linux-hardware.org/?probe=4133dff23f) | Mar 22, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [edaf75da5f](https://linux-hardware.org/?probe=edaf75da5f) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [3b0fd0ec8b](https://linux-hardware.org/?probe=3b0fd0ec8b) | Mar 22, 2022 |
| Aquarius      | NS585                       | Notebook    | [2cc901ad54](https://linux-hardware.org/?probe=2cc901ad54) | Mar 22, 2022 |
| Digiboard     | MPxx                        | Desktop     | [b3bb9ff288](https://linux-hardware.org/?probe=b3bb9ff288) | Mar 22, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7561e02794](https://linux-hardware.org/?probe=7561e02794) | Mar 22, 2022 |
| Dell          | Latitude 3410               | Notebook    | [d81534df3a](https://linux-hardware.org/?probe=d81534df3a) | Mar 22, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [7b2ab61a6e](https://linux-hardware.org/?probe=7b2ab61a6e) | Mar 21, 2022 |
| MSI           | 760GM -E51                  | Desktop     | [fd746ce3ee](https://linux-hardware.org/?probe=fd746ce3ee) | Mar 21, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [069849c461](https://linux-hardware.org/?probe=069849c461) | Mar 21, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [26a88b6d1f](https://linux-hardware.org/?probe=26a88b6d1f) | Mar 21, 2022 |
| Dell          | Latitude 3410               | Notebook    | [6d78749bd6](https://linux-hardware.org/?probe=6d78749bd6) | Mar 21, 2022 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [fcf20188d2](https://linux-hardware.org/?probe=fcf20188d2) | Mar 21, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [0aa28d1e37](https://linux-hardware.org/?probe=0aa28d1e37) | Mar 21, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [9c0d4c37d8](https://linux-hardware.org/?probe=9c0d4c37d8) | Mar 21, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [d8f482f916](https://linux-hardware.org/?probe=d8f482f916) | Mar 21, 2022 |
| Aquarius      | NS585                       | Notebook    | [c0f64e7b67](https://linux-hardware.org/?probe=c0f64e7b67) | Mar 21, 2022 |
| Aquarius      | NS585                       | Notebook    | [2bd62b79af](https://linux-hardware.org/?probe=2bd62b79af) | Mar 21, 2022 |
| Aquarius      | NS585                       | Notebook    | [77fe07b69f](https://linux-hardware.org/?probe=77fe07b69f) | Mar 21, 2022 |
| Lenovo        | ThinkPad P51s 20HB000URT    | Notebook    | [595bf8f0af](https://linux-hardware.org/?probe=595bf8f0af) | Mar 21, 2022 |
| Dell          | 07T4MC A09                  | Desktop     | [ef5f0dcfe7](https://linux-hardware.org/?probe=ef5f0dcfe7) | Mar 21, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [c004cff4ed](https://linux-hardware.org/?probe=c004cff4ed) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [18294dd367](https://linux-hardware.org/?probe=18294dd367) | Mar 21, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [8ff982fca7](https://linux-hardware.org/?probe=8ff982fca7) | Mar 21, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [543e44c95a](https://linux-hardware.org/?probe=543e44c95a) | Mar 20, 2022 |
| Dell          | Latitude 7300               | Notebook    | [751dc53e2b](https://linux-hardware.org/?probe=751dc53e2b) | Mar 20, 2022 |
| HP            | 18E7                        | Desktop     | [727446a2df](https://linux-hardware.org/?probe=727446a2df) | Mar 20, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [b5abf934a3](https://linux-hardware.org/?probe=b5abf934a3) | Mar 20, 2022 |
| Lenovo        | ThinkPad P53 20QQA004CD     | Notebook    | [c99fae499f](https://linux-hardware.org/?probe=c99fae499f) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b8b480e048](https://linux-hardware.org/?probe=b8b480e048) | Mar 20, 2022 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [1b9131d30f](https://linux-hardware.org/?probe=1b9131d30f) | Mar 19, 2022 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [e5e77babce](https://linux-hardware.org/?probe=e5e77babce) | Mar 19, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [9cc0fc6cd0](https://linux-hardware.org/?probe=9cc0fc6cd0) | Mar 19, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [9719c4cdeb](https://linux-hardware.org/?probe=9719c4cdeb) | Mar 19, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [b77a3343c9](https://linux-hardware.org/?probe=b77a3343c9) | Mar 19, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [ad3e8cb6c8](https://linux-hardware.org/?probe=ad3e8cb6c8) | Mar 19, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [9ad3eef70b](https://linux-hardware.org/?probe=9ad3eef70b) | Mar 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [28d7818dd8](https://linux-hardware.org/?probe=28d7818dd8) | Mar 19, 2022 |
| Unknown       | MNT Reform 2                | Soc         | [e76c7cf9c8](https://linux-hardware.org/?probe=e76c7cf9c8) | Mar 19, 2022 |
| Samsung       | R509                        | Notebook    | [f557f45389](https://linux-hardware.org/?probe=f557f45389) | Mar 19, 2022 |
| Dell          | MXG071                      | Notebook    | [aefb0e99b0](https://linux-hardware.org/?probe=aefb0e99b0) | Mar 18, 2022 |
| ASUSTek       | X751MD                      | Notebook    | [28ea617ca1](https://linux-hardware.org/?probe=28ea617ca1) | Mar 18, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [d581be232a](https://linux-hardware.org/?probe=d581be232a) | Mar 18, 2022 |
| Lenovo        | Unknown                     | Notebook    | [661ddbd0df](https://linux-hardware.org/?probe=661ddbd0df) | Mar 18, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [b9822ea50b](https://linux-hardware.org/?probe=b9822ea50b) | Mar 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [434de4f3ce](https://linux-hardware.org/?probe=434de4f3ce) | Mar 18, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e9ebe9f2cd](https://linux-hardware.org/?probe=e9ebe9f2cd) | Mar 18, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [959aaa3f2d](https://linux-hardware.org/?probe=959aaa3f2d) | Mar 18, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0762474e5f](https://linux-hardware.org/?probe=0762474e5f) | Mar 18, 2022 |
| ASRock        | Z87 Pro4                    | Desktop     | [7c46cc65dc](https://linux-hardware.org/?probe=7c46cc65dc) | Mar 18, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c5e201fa28](https://linux-hardware.org/?probe=c5e201fa28) | Mar 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4730bac7be](https://linux-hardware.org/?probe=4730bac7be) | Mar 17, 2022 |
| Lenovo        | MIIX 2 10 20359             | Tablet      | [212388e78b](https://linux-hardware.org/?probe=212388e78b) | Mar 17, 2022 |
| ASUSTek       | P5K/EPU                     | Desktop     | [38de085421](https://linux-hardware.org/?probe=38de085421) | Mar 17, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [90b9116ab3](https://linux-hardware.org/?probe=90b9116ab3) | Mar 17, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [45a830000a](https://linux-hardware.org/?probe=45a830000a) | Mar 17, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [d71d1c794b](https://linux-hardware.org/?probe=d71d1c794b) | Mar 17, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [3190c29544](https://linux-hardware.org/?probe=3190c29544) | Mar 17, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [cec081c2b6](https://linux-hardware.org/?probe=cec081c2b6) | Mar 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aaee68ff4](https://linux-hardware.org/?probe=1aaee68ff4) | Mar 16, 2022 |
| MSI           | 760GM -E51                  | Desktop     | [0d9d56531d](https://linux-hardware.org/?probe=0d9d56531d) | Mar 16, 2022 |
| Dell          | Latitude E7470              | Notebook    | [2eca1925d5](https://linux-hardware.org/?probe=2eca1925d5) | Mar 16, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XRT    | Notebook    | [54a5b7d556](https://linux-hardware.org/?probe=54a5b7d556) | Mar 16, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [228a532955](https://linux-hardware.org/?probe=228a532955) | Mar 16, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [a62b3060e7](https://linux-hardware.org/?probe=a62b3060e7) | Mar 16, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b10d8b3a00](https://linux-hardware.org/?probe=b10d8b3a00) | Mar 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [e7fb180535](https://linux-hardware.org/?probe=e7fb180535) | Mar 16, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [fedff7063c](https://linux-hardware.org/?probe=fedff7063c) | Mar 16, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [c187336160](https://linux-hardware.org/?probe=c187336160) | Mar 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [68aaea88ba](https://linux-hardware.org/?probe=68aaea88ba) | Mar 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0553e8f35e](https://linux-hardware.org/?probe=0553e8f35e) | Mar 16, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [11bc08ed1f](https://linux-hardware.org/?probe=11bc08ed1f) | Mar 16, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [9da39d2356](https://linux-hardware.org/?probe=9da39d2356) | Mar 15, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [bc07a3de3d](https://linux-hardware.org/?probe=bc07a3de3d) | Mar 15, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [ddbc85ab3a](https://linux-hardware.org/?probe=ddbc85ab3a) | Mar 15, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [539ebb7dd9](https://linux-hardware.org/?probe=539ebb7dd9) | Mar 15, 2022 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [c4ce1fa83f](https://linux-hardware.org/?probe=c4ce1fa83f) | Mar 15, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [8070a2b368](https://linux-hardware.org/?probe=8070a2b368) | Mar 15, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | Notebook    | [c0fcc559b7](https://linux-hardware.org/?probe=c0fcc559b7) | Mar 15, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [9d51869d37](https://linux-hardware.org/?probe=9d51869d37) | Mar 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [aa7912e58f](https://linux-hardware.org/?probe=aa7912e58f) | Mar 15, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [b7cf53ebcc](https://linux-hardware.org/?probe=b7cf53ebcc) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [25c0bbffe2](https://linux-hardware.org/?probe=25c0bbffe2) | Mar 15, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [89baa8a149](https://linux-hardware.org/?probe=89baa8a149) | Mar 14, 2022 |
| Apple         | Mac-CFF7D910A743CAAF iMa... | All in one  | [58d2e77531](https://linux-hardware.org/?probe=58d2e77531) | Mar 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [510f8a2d24](https://linux-hardware.org/?probe=510f8a2d24) | Mar 14, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | Notebook    | [a503416ccd](https://linux-hardware.org/?probe=a503416ccd) | Mar 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [cc44f7c610](https://linux-hardware.org/?probe=cc44f7c610) | Mar 14, 2022 |
| Dell          | Latitude D830               | Notebook    | [d1059491da](https://linux-hardware.org/?probe=d1059491da) | Mar 14, 2022 |
| AQUARIUS      | AQH310CM                    | Desktop     | [e2d2a06fac](https://linux-hardware.org/?probe=e2d2a06fac) | Mar 14, 2022 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [f78973af80](https://linux-hardware.org/?probe=f78973af80) | Mar 14, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [dc759490e1](https://linux-hardware.org/?probe=dc759490e1) | Mar 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a15fc5e821](https://linux-hardware.org/?probe=a15fc5e821) | Mar 14, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [4d32980028](https://linux-hardware.org/?probe=4d32980028) | Mar 14, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7f4d5a9689](https://linux-hardware.org/?probe=7f4d5a9689) | Mar 14, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [2ea48b8569](https://linux-hardware.org/?probe=2ea48b8569) | Mar 14, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [7cdec0f827](https://linux-hardware.org/?probe=7cdec0f827) | Mar 14, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [0cd9132f27](https://linux-hardware.org/?probe=0cd9132f27) | Mar 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [2e828331f3](https://linux-hardware.org/?probe=2e828331f3) | Mar 14, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7b964bbd1f](https://linux-hardware.org/?probe=7b964bbd1f) | Mar 14, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [3a5b71395a](https://linux-hardware.org/?probe=3a5b71395a) | Mar 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [8cfd0e9795](https://linux-hardware.org/?probe=8cfd0e9795) | Mar 13, 2022 |
| Lenovo        | ThinkPad T410 2522DK2       | Notebook    | [9990e887c2](https://linux-hardware.org/?probe=9990e887c2) | Mar 13, 2022 |
| Dell          | Precision 5510              | Notebook    | [50ca449b34](https://linux-hardware.org/?probe=50ca449b34) | Mar 13, 2022 |
| Fujitsu       | LIFEBOOK E546               | Notebook    | [247dd3e47c](https://linux-hardware.org/?probe=247dd3e47c) | Mar 13, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [595ba4af42](https://linux-hardware.org/?probe=595ba4af42) | Mar 13, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [0141fa64e7](https://linux-hardware.org/?probe=0141fa64e7) | Mar 13, 2022 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [6acfb59dd3](https://linux-hardware.org/?probe=6acfb59dd3) | Mar 13, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [1dac441515](https://linux-hardware.org/?probe=1dac441515) | Mar 12, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [3dcc73772f](https://linux-hardware.org/?probe=3dcc73772f) | Mar 12, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [70a5dc4f94](https://linux-hardware.org/?probe=70a5dc4f94) | Mar 12, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [8fdeae3b33](https://linux-hardware.org/?probe=8fdeae3b33) | Mar 12, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [85920b5b34](https://linux-hardware.org/?probe=85920b5b34) | Mar 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2f53098049](https://linux-hardware.org/?probe=2f53098049) | Mar 12, 2022 |
| MSI           | H81M-P33                    | Desktop     | [0f103bcb15](https://linux-hardware.org/?probe=0f103bcb15) | Mar 12, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [a89e3579bb](https://linux-hardware.org/?probe=a89e3579bb) | Mar 12, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [ba5f39003e](https://linux-hardware.org/?probe=ba5f39003e) | Mar 11, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [d98e8dd76d](https://linux-hardware.org/?probe=d98e8dd76d) | Mar 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a7ca755c8e](https://linux-hardware.org/?probe=a7ca755c8e) | Mar 11, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [ec0e6e5114](https://linux-hardware.org/?probe=ec0e6e5114) | Mar 11, 2022 |
| ASUSTek       | P5KPL-AM IN/GB              | Desktop     | [927be27436](https://linux-hardware.org/?probe=927be27436) | Mar 11, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e3c4fb5a9c](https://linux-hardware.org/?probe=e3c4fb5a9c) | Mar 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [304738db66](https://linux-hardware.org/?probe=304738db66) | Mar 11, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [37c37094b9](https://linux-hardware.org/?probe=37c37094b9) | Mar 11, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [2d3f5f0f14](https://linux-hardware.org/?probe=2d3f5f0f14) | Mar 11, 2022 |
| Lenovo        | ThinkPad T440s 20ARS08Q0... | Notebook    | [10655c6e60](https://linux-hardware.org/?probe=10655c6e60) | Mar 11, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [11b61d2b8a](https://linux-hardware.org/?probe=11b61d2b8a) | Mar 11, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [c10003c041](https://linux-hardware.org/?probe=c10003c041) | Mar 11, 2022 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [436904eae3](https://linux-hardware.org/?probe=436904eae3) | Mar 11, 2022 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [4fd151ada5](https://linux-hardware.org/?probe=4fd151ada5) | Mar 11, 2022 |
| HP            | HDX18                       | Notebook    | [a6788bfe93](https://linux-hardware.org/?probe=a6788bfe93) | Mar 11, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [859b5c10cd](https://linux-hardware.org/?probe=859b5c10cd) | Mar 10, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [f094b510c8](https://linux-hardware.org/?probe=f094b510c8) | Mar 10, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [db28c629ec](https://linux-hardware.org/?probe=db28c629ec) | Mar 10, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [e3ff8d781a](https://linux-hardware.org/?probe=e3ff8d781a) | Mar 10, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [d3ad998dfa](https://linux-hardware.org/?probe=d3ad998dfa) | Mar 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [30aa9c3047](https://linux-hardware.org/?probe=30aa9c3047) | Mar 09, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [0b30878d3e](https://linux-hardware.org/?probe=0b30878d3e) | Mar 09, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [fcde4dafe3](https://linux-hardware.org/?probe=fcde4dafe3) | Mar 09, 2022 |
| MSI           | H81M-P33                    | Desktop     | [cf152def87](https://linux-hardware.org/?probe=cf152def87) | Mar 09, 2022 |
| ASUSTek       | BU401LA                     | Notebook    | [2df54ef02e](https://linux-hardware.org/?probe=2df54ef02e) | Mar 08, 2022 |
| MSI           | 3664h                       | Desktop     | [e5eaec6553](https://linux-hardware.org/?probe=e5eaec6553) | Mar 08, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ed11376acd](https://linux-hardware.org/?probe=ed11376acd) | Mar 08, 2022 |
| HP            | ProBook 4540s               | Notebook    | [2665d70122](https://linux-hardware.org/?probe=2665d70122) | Mar 08, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [5b31db42d4](https://linux-hardware.org/?probe=5b31db42d4) | Mar 08, 2022 |
| Dell          | Latitude 7400               | Notebook    | [85fb049c80](https://linux-hardware.org/?probe=85fb049c80) | Mar 08, 2022 |
| HP            | 1589                        | Desktop     | [5a3c3065d0](https://linux-hardware.org/?probe=5a3c3065d0) | Mar 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [546746c825](https://linux-hardware.org/?probe=546746c825) | Mar 07, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [6765f9623b](https://linux-hardware.org/?probe=6765f9623b) | Mar 07, 2022 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [35e716f504](https://linux-hardware.org/?probe=35e716f504) | Mar 07, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [bf7c2c6d9b](https://linux-hardware.org/?probe=bf7c2c6d9b) | Mar 07, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [2819c9e72e](https://linux-hardware.org/?probe=2819c9e72e) | Mar 07, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [4fc79fb935](https://linux-hardware.org/?probe=4fc79fb935) | Mar 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [493fe1a76a](https://linux-hardware.org/?probe=493fe1a76a) | Mar 07, 2022 |
| HP            | 3399                        | Desktop     | [60fa2f3867](https://linux-hardware.org/?probe=60fa2f3867) | Mar 07, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [38c484b64e](https://linux-hardware.org/?probe=38c484b64e) | Mar 07, 2022 |
| HP            | ProBook 455 G3              | Notebook    | [7ad342e02e](https://linux-hardware.org/?probe=7ad342e02e) | Mar 07, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [5e63db91a1](https://linux-hardware.org/?probe=5e63db91a1) | Mar 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [eccfe5b35c](https://linux-hardware.org/?probe=eccfe5b35c) | Mar 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [af11e24c3a](https://linux-hardware.org/?probe=af11e24c3a) | Mar 07, 2022 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [c75eb0d27f](https://linux-hardware.org/?probe=c75eb0d27f) | Mar 07, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [852b569ef5](https://linux-hardware.org/?probe=852b569ef5) | Mar 06, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [a02da9c610](https://linux-hardware.org/?probe=a02da9c610) | Mar 06, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [04d9923f43](https://linux-hardware.org/?probe=04d9923f43) | Mar 06, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [fe6d3d8eaf](https://linux-hardware.org/?probe=fe6d3d8eaf) | Mar 06, 2022 |
| Acer          | EG43M                       | Desktop     | [3df7717081](https://linux-hardware.org/?probe=3df7717081) | Mar 06, 2022 |
| MSI           | H81M-P33                    | Desktop     | [731850ebaf](https://linux-hardware.org/?probe=731850ebaf) | Mar 06, 2022 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [87bffb084f](https://linux-hardware.org/?probe=87bffb084f) | Mar 06, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b57d637fce](https://linux-hardware.org/?probe=b57d637fce) | Mar 06, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [b78185d870](https://linux-hardware.org/?probe=b78185d870) | Mar 06, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [a630a0c13c](https://linux-hardware.org/?probe=a630a0c13c) | Mar 06, 2022 |
| Dell          | Latitude E6330              | Notebook    | [f4491d2da7](https://linux-hardware.org/?probe=f4491d2da7) | Mar 06, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [2df5098230](https://linux-hardware.org/?probe=2df5098230) | Mar 05, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [49093d0be0](https://linux-hardware.org/?probe=49093d0be0) | Mar 05, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [aff575b483](https://linux-hardware.org/?probe=aff575b483) | Mar 05, 2022 |
| Elife         | series                      | Notebook    | [dddf04aa69](https://linux-hardware.org/?probe=dddf04aa69) | Mar 05, 2022 |
| Elife         | series                      | Notebook    | [979e43c05a](https://linux-hardware.org/?probe=979e43c05a) | Mar 05, 2022 |
| ASUSTek       | H87M-PRO                    | Desktop     | [99effa6921](https://linux-hardware.org/?probe=99effa6921) | Mar 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ac671d5e38](https://linux-hardware.org/?probe=ac671d5e38) | Mar 05, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [90e4cc2972](https://linux-hardware.org/?probe=90e4cc2972) | Mar 05, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [a786074185](https://linux-hardware.org/?probe=a786074185) | Mar 05, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [b5678eb9d3](https://linux-hardware.org/?probe=b5678eb9d3) | Mar 05, 2022 |
| Avell High... | A40 LIV                     | Notebook    | [6056996dfb](https://linux-hardware.org/?probe=6056996dfb) | Mar 05, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [fae9412031](https://linux-hardware.org/?probe=fae9412031) | Mar 05, 2022 |
| System76      | Kudu Professional           | Notebook    | [6dd5d90fae](https://linux-hardware.org/?probe=6dd5d90fae) | Mar 04, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3345ff19cd](https://linux-hardware.org/?probe=3345ff19cd) | Mar 04, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [015cea29f4](https://linux-hardware.org/?probe=015cea29f4) | Mar 04, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [5fa0d18666](https://linux-hardware.org/?probe=5fa0d18666) | Mar 04, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [4702dab234](https://linux-hardware.org/?probe=4702dab234) | Mar 04, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [058cafa79c](https://linux-hardware.org/?probe=058cafa79c) | Mar 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [8c13511a03](https://linux-hardware.org/?probe=8c13511a03) | Mar 03, 2022 |
| Gigabyte      | B450M S2H V2                | Desktop     | [000ae29fb1](https://linux-hardware.org/?probe=000ae29fb1) | Mar 03, 2022 |
| Fujitsu       | D3090-A1 S26361-D3090-A1    | Server      | [ee54bb96c5](https://linux-hardware.org/?probe=ee54bb96c5) | Mar 03, 2022 |
| Foxconn       | Irvine HP P/N               | Desktop     | [1d37020507](https://linux-hardware.org/?probe=1d37020507) | Mar 03, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [0195fe9da4](https://linux-hardware.org/?probe=0195fe9da4) | Mar 03, 2022 |
| Dell          | 0RM5DR A00                  | Desktop     | [2a8f42bdc3](https://linux-hardware.org/?probe=2a8f42bdc3) | Mar 03, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [c67a313947](https://linux-hardware.org/?probe=c67a313947) | Mar 03, 2022 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [0e75969d4d](https://linux-hardware.org/?probe=0e75969d4d) | Mar 03, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [435c237f8f](https://linux-hardware.org/?probe=435c237f8f) | Mar 02, 2022 |
| HP            | 2140                        | Notebook    | [6956607bfd](https://linux-hardware.org/?probe=6956607bfd) | Mar 02, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [547e8c2e0b](https://linux-hardware.org/?probe=547e8c2e0b) | Mar 02, 2022 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [a4145828e3](https://linux-hardware.org/?probe=a4145828e3) | Mar 02, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [9b5ba1cd95](https://linux-hardware.org/?probe=9b5ba1cd95) | Mar 02, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a90b7bb57e](https://linux-hardware.org/?probe=a90b7bb57e) | Mar 02, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [67241eca45](https://linux-hardware.org/?probe=67241eca45) | Mar 02, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [5a235f718e](https://linux-hardware.org/?probe=5a235f718e) | Mar 01, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3f1e43c90c](https://linux-hardware.org/?probe=3f1e43c90c) | Mar 01, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6e98976f1a](https://linux-hardware.org/?probe=6e98976f1a) | Mar 01, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [3e10ea1487](https://linux-hardware.org/?probe=3e10ea1487) | Mar 01, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [e683855566](https://linux-hardware.org/?probe=e683855566) | Mar 01, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [65a2479cda](https://linux-hardware.org/?probe=65a2479cda) | Mar 01, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [c5b8c08527](https://linux-hardware.org/?probe=c5b8c08527) | Mar 01, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4bc0114fa0](https://linux-hardware.org/?probe=4bc0114fa0) | Mar 01, 2022 |
| Dell          | 04JN2K A09                  | Server      | [dfc56ee37b](https://linux-hardware.org/?probe=dfc56ee37b) | Mar 01, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [e61dde5545](https://linux-hardware.org/?probe=e61dde5545) | Mar 01, 2022 |
| Acer          | Aspire 1640                 | Notebook    | [0296f1869b](https://linux-hardware.org/?probe=0296f1869b) | Mar 01, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [daef2e33ab](https://linux-hardware.org/?probe=daef2e33ab) | Mar 01, 2022 |
| Philco        | O E M                       | Notebook    | [47cc99022d](https://linux-hardware.org/?probe=47cc99022d) | Mar 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [6cec0db416](https://linux-hardware.org/?probe=6cec0db416) | Mar 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [c88c351a35](https://linux-hardware.org/?probe=c88c351a35) | Mar 01, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [03394e745c](https://linux-hardware.org/?probe=03394e745c) | Feb 28, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [23c2a93047](https://linux-hardware.org/?probe=23c2a93047) | Feb 28, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [87083d1a0f](https://linux-hardware.org/?probe=87083d1a0f) | Feb 28, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [efcd8651f8](https://linux-hardware.org/?probe=efcd8651f8) | Feb 28, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [332a3f936b](https://linux-hardware.org/?probe=332a3f936b) | Feb 28, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [0bb471d9a2](https://linux-hardware.org/?probe=0bb471d9a2) | Feb 28, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [a032cb00cd](https://linux-hardware.org/?probe=a032cb00cd) | Feb 28, 2022 |
| MSI           | H81M-P33                    | Desktop     | [4595a12a77](https://linux-hardware.org/?probe=4595a12a77) | Feb 28, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [5485738b5a](https://linux-hardware.org/?probe=5485738b5a) | Feb 28, 2022 |
| HP            | 09F8h                       | Desktop     | [19dc89049d](https://linux-hardware.org/?probe=19dc89049d) | Feb 28, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [7f7cbc5231](https://linux-hardware.org/?probe=7f7cbc5231) | Feb 28, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [905f4927f5](https://linux-hardware.org/?probe=905f4927f5) | Feb 28, 2022 |
| ASUSTek       | X401A                       | Notebook    | [e97f529634](https://linux-hardware.org/?probe=e97f529634) | Feb 28, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [21165232d6](https://linux-hardware.org/?probe=21165232d6) | Feb 28, 2022 |
| Lenovo        | ThinkPad T490 20RXS0VX00    | Notebook    | [8f42f6fd5f](https://linux-hardware.org/?probe=8f42f6fd5f) | Feb 28, 2022 |
| Fujitsu       | FMVA05007                   | Notebook    | [21c7863329](https://linux-hardware.org/?probe=21c7863329) | Feb 27, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [9a13daf94a](https://linux-hardware.org/?probe=9a13daf94a) | Feb 27, 2022 |
| MSI           | H81M-P33                    | Desktop     | [60e41d668b](https://linux-hardware.org/?probe=60e41d668b) | Feb 27, 2022 |
| Intel         | H81                         | Desktop     | [a62759e3c8](https://linux-hardware.org/?probe=a62759e3c8) | Feb 27, 2022 |
| Intel         | H81                         | Desktop     | [d1f816774f](https://linux-hardware.org/?probe=d1f816774f) | Feb 27, 2022 |
| Digiboard     | MPxx                        | Desktop     | [9ad44a5962](https://linux-hardware.org/?probe=9ad44a5962) | Feb 26, 2022 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [4f5cd3d750](https://linux-hardware.org/?probe=4f5cd3d750) | Feb 26, 2022 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [cc86c9d580](https://linux-hardware.org/?probe=cc86c9d580) | Feb 26, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [39389b9ddf](https://linux-hardware.org/?probe=39389b9ddf) | Feb 26, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | Desktop     | [4492e8dd58](https://linux-hardware.org/?probe=4492e8dd58) | Feb 26, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | Desktop     | [6bb6bfa47a](https://linux-hardware.org/?probe=6bb6bfa47a) | Feb 26, 2022 |
| Clientron ... | L700                        | Desktop     | [c2cebca02b](https://linux-hardware.org/?probe=c2cebca02b) | Feb 26, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [bedf3d3105](https://linux-hardware.org/?probe=bedf3d3105) | Feb 26, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [c8dd47fb82](https://linux-hardware.org/?probe=c8dd47fb82) | Feb 26, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c4d875ab4f](https://linux-hardware.org/?probe=c4d875ab4f) | Feb 25, 2022 |
| ASUSTek       | N82JV                       | Notebook    | [30b9ccdcc9](https://linux-hardware.org/?probe=30b9ccdcc9) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [279a26d7e5](https://linux-hardware.org/?probe=279a26d7e5) | Feb 25, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [8e06c09393](https://linux-hardware.org/?probe=8e06c09393) | Feb 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [647a154bd6](https://linux-hardware.org/?probe=647a154bd6) | Feb 25, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [50f19dd349](https://linux-hardware.org/?probe=50f19dd349) | Feb 25, 2022 |
| Gigabyte      | 8I945GZME-RH                | Desktop     | [4afdb1534e](https://linux-hardware.org/?probe=4afdb1534e) | Feb 25, 2022 |
| Lenovo        | B50-80 80LT                 | Notebook    | [b5dd44876a](https://linux-hardware.org/?probe=b5dd44876a) | Feb 25, 2022 |
| Lenovo        | B50-80 80LT                 | Notebook    | [d4775df51b](https://linux-hardware.org/?probe=d4775df51b) | Feb 25, 2022 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [e97bd26a11](https://linux-hardware.org/?probe=e97bd26a11) | Feb 25, 2022 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [a8f77b99e9](https://linux-hardware.org/?probe=a8f77b99e9) | Feb 25, 2022 |
| ECS           | G31T-M9                     | Desktop     | [4de828bf82](https://linux-hardware.org/?probe=4de828bf82) | Feb 25, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [b3086480e5](https://linux-hardware.org/?probe=b3086480e5) | Feb 25, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [cd0609e2cc](https://linux-hardware.org/?probe=cd0609e2cc) | Feb 25, 2022 |
| Apple         | MacBook8,1                  | Notebook    | [b7b8d7f677](https://linux-hardware.org/?probe=b7b8d7f677) | Feb 24, 2022 |
| Lenovo        | ThinkPad T410 2537A12       | Notebook    | [ec01c23749](https://linux-hardware.org/?probe=ec01c23749) | Feb 24, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [f576f08ecb](https://linux-hardware.org/?probe=f576f08ecb) | Feb 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [64955f775b](https://linux-hardware.org/?probe=64955f775b) | Feb 24, 2022 |
| ASUSTek       | BU203UA                     | Notebook    | [20764e8ede](https://linux-hardware.org/?probe=20764e8ede) | Feb 24, 2022 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [621999b245](https://linux-hardware.org/?probe=621999b245) | Feb 24, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [0b5555f2ed](https://linux-hardware.org/?probe=0b5555f2ed) | Feb 24, 2022 |
| Gigabyte      | 8I945GZME-RH                | Desktop     | [a7414ad5c1](https://linux-hardware.org/?probe=a7414ad5c1) | Feb 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [be7b7ac530](https://linux-hardware.org/?probe=be7b7ac530) | Feb 24, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [5e687a3ff4](https://linux-hardware.org/?probe=5e687a3ff4) | Feb 24, 2022 |
| ECS           | G31T-M9                     | Desktop     | [a5898e6474](https://linux-hardware.org/?probe=a5898e6474) | Feb 24, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [00e3cebb2f](https://linux-hardware.org/?probe=00e3cebb2f) | Feb 24, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [cbf876b408](https://linux-hardware.org/?probe=cbf876b408) | Feb 24, 2022 |
| Dell          | Latitude E4300              | Notebook    | [bfa3fa7218](https://linux-hardware.org/?probe=bfa3fa7218) | Feb 24, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [f82673bb20](https://linux-hardware.org/?probe=f82673bb20) | Feb 24, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [71de12f898](https://linux-hardware.org/?probe=71de12f898) | Feb 24, 2022 |
| Clientron ... | L700                        | Desktop     | [0a16915d4f](https://linux-hardware.org/?probe=0a16915d4f) | Feb 23, 2022 |
| Clientron ... | L700                        | Desktop     | [64f361f774](https://linux-hardware.org/?probe=64f361f774) | Feb 23, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [399a541ed9](https://linux-hardware.org/?probe=399a541ed9) | Feb 23, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [98a6706e6a](https://linux-hardware.org/?probe=98a6706e6a) | Feb 23, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [46cf1eb748](https://linux-hardware.org/?probe=46cf1eb748) | Feb 23, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [dd889a3b3e](https://linux-hardware.org/?probe=dd889a3b3e) | Feb 23, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [ad30c9f5ed](https://linux-hardware.org/?probe=ad30c9f5ed) | Feb 23, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6a686b1a1d](https://linux-hardware.org/?probe=6a686b1a1d) | Feb 23, 2022 |
| Dell          | 0DRR0P A08                  | Server      | [5011114071](https://linux-hardware.org/?probe=5011114071) | Feb 23, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [da9c47ddfc](https://linux-hardware.org/?probe=da9c47ddfc) | Feb 22, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [779dfa3e78](https://linux-hardware.org/?probe=779dfa3e78) | Feb 22, 2022 |
| Supermicro    | X8DTL                       | Server      | [89d676af03](https://linux-hardware.org/?probe=89d676af03) | Feb 22, 2022 |
| Supermicro    | X8DTL                       | Server      | [a1bb16c84f](https://linux-hardware.org/?probe=a1bb16c84f) | Feb 22, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [8580399323](https://linux-hardware.org/?probe=8580399323) | Feb 22, 2022 |
| ASUSTek       | M70Vn                       | Notebook    | [ae56cd459a](https://linux-hardware.org/?probe=ae56cd459a) | Feb 22, 2022 |
| HP            | ZBook Studio G3             | Notebook    | [4d97cb439b](https://linux-hardware.org/?probe=4d97cb439b) | Feb 22, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [611cfcfbaa](https://linux-hardware.org/?probe=611cfcfbaa) | Feb 22, 2022 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [286998a230](https://linux-hardware.org/?probe=286998a230) | Feb 22, 2022 |
| Google        | Barla                       | Notebook    | [12180ab1ff](https://linux-hardware.org/?probe=12180ab1ff) | Feb 22, 2022 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [838f13e574](https://linux-hardware.org/?probe=838f13e574) | Feb 21, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [6921a2b793](https://linux-hardware.org/?probe=6921a2b793) | Feb 21, 2022 |
| ECS           | G31T-M9                     | Desktop     | [a1c64c22b2](https://linux-hardware.org/?probe=a1c64c22b2) | Feb 21, 2022 |
| ASUSTek       | K52F                        | Notebook    | [51504b5b77](https://linux-hardware.org/?probe=51504b5b77) | Feb 21, 2022 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [d4f94f7b98](https://linux-hardware.org/?probe=d4f94f7b98) | Feb 21, 2022 |
| Foxconn       | H61MXL-K                    | Desktop     | [2a9136e1ad](https://linux-hardware.org/?probe=2a9136e1ad) | Feb 21, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [62161a1c28](https://linux-hardware.org/?probe=62161a1c28) | Feb 21, 2022 |
| Lenovo        | 3172 SDK0J40697 WIN 3305... | Mini pc     | [c419233c03](https://linux-hardware.org/?probe=c419233c03) | Feb 21, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [aeba2103e0](https://linux-hardware.org/?probe=aeba2103e0) | Feb 21, 2022 |
| Timi          | RedmiBook 16                | Notebook    | [cca94f2eda](https://linux-hardware.org/?probe=cca94f2eda) | Feb 21, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [29f68fd73c](https://linux-hardware.org/?probe=29f68fd73c) | Feb 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [41a38c1e60](https://linux-hardware.org/?probe=41a38c1e60) | Feb 21, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [cf906c0ca1](https://linux-hardware.org/?probe=cf906c0ca1) | Feb 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [2a57fc9391](https://linux-hardware.org/?probe=2a57fc9391) | Feb 20, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [807790386b](https://linux-hardware.org/?probe=807790386b) | Feb 20, 2022 |
| ASUSTek       | X751LK                      | Notebook    | [59056d9df8](https://linux-hardware.org/?probe=59056d9df8) | Feb 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [129c8a24d9](https://linux-hardware.org/?probe=129c8a24d9) | Feb 20, 2022 |
| Notebook      | W65_W670SR                  | Notebook    | [53c885fa6e](https://linux-hardware.org/?probe=53c885fa6e) | Feb 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [b355ea1ff3](https://linux-hardware.org/?probe=b355ea1ff3) | Feb 20, 2022 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [06b52bc271](https://linux-hardware.org/?probe=06b52bc271) | Feb 20, 2022 |
| ASRock        | J4205-ITX                   | Desktop     | [e7e09c80fa](https://linux-hardware.org/?probe=e7e09c80fa) | Feb 20, 2022 |
| Lenovo        | ThinkPad T410 2537A12       | Notebook    | [7326d20b88](https://linux-hardware.org/?probe=7326d20b88) | Feb 19, 2022 |
| HP            | 158A                        | Desktop     | [f31e70e834](https://linux-hardware.org/?probe=f31e70e834) | Feb 19, 2022 |
| Dell          | 0PU052                      | Desktop     | [20d5c30034](https://linux-hardware.org/?probe=20d5c30034) | Feb 19, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [811ec775f8](https://linux-hardware.org/?probe=811ec775f8) | Feb 19, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [074c993361](https://linux-hardware.org/?probe=074c993361) | Feb 19, 2022 |
| ASUSTek       | X756UXK                     | Notebook    | [b71ec18dba](https://linux-hardware.org/?probe=b71ec18dba) | Feb 19, 2022 |
| Lenovo        | ThinkPad X220 4291Q50       | Notebook    | [600a3137e2](https://linux-hardware.org/?probe=600a3137e2) | Feb 19, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [fc3b92e02f](https://linux-hardware.org/?probe=fc3b92e02f) | Feb 19, 2022 |
| Dell          | XPS L521X                   | Notebook    | [1826f26221](https://linux-hardware.org/?probe=1826f26221) | Feb 19, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6cbb067e83](https://linux-hardware.org/?probe=6cbb067e83) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ef345f036b](https://linux-hardware.org/?probe=ef345f036b) | Feb 19, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [6678e3ba4a](https://linux-hardware.org/?probe=6678e3ba4a) | Feb 18, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8d1aba98b7](https://linux-hardware.org/?probe=8d1aba98b7) | Feb 18, 2022 |
| Gigabyte      | M52L-S3P                    | Desktop     | [b8aecf78e9](https://linux-hardware.org/?probe=b8aecf78e9) | Feb 18, 2022 |
| MSI           | H81M-P33                    | Desktop     | [ee22059bf7](https://linux-hardware.org/?probe=ee22059bf7) | Feb 18, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [0c75e0962a](https://linux-hardware.org/?probe=0c75e0962a) | Feb 18, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [3eb9652b7e](https://linux-hardware.org/?probe=3eb9652b7e) | Feb 18, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [a59f3617da](https://linux-hardware.org/?probe=a59f3617da) | Feb 18, 2022 |
| Acer          | Aspire F5-771G              | Notebook    | [056c9c48f6](https://linux-hardware.org/?probe=056c9c48f6) | Feb 18, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [37b0807b22](https://linux-hardware.org/?probe=37b0807b22) | Feb 18, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [c1b7bc8432](https://linux-hardware.org/?probe=c1b7bc8432) | Feb 18, 2022 |
| HP            | 0AACh                       | Desktop     | [5a45fe2b9b](https://linux-hardware.org/?probe=5a45fe2b9b) | Feb 18, 2022 |
| sunxi         | Banana Pi BPI-M2-Plus H3    | Soc         | [1f12724cce](https://linux-hardware.org/?probe=1f12724cce) | Feb 18, 2022 |
| HP            | Presario CQ61               | Notebook    | [92054824d8](https://linux-hardware.org/?probe=92054824d8) | Feb 18, 2022 |
| HP            | Presario CQ61               | Notebook    | [bb314dee54](https://linux-hardware.org/?probe=bb314dee54) | Feb 18, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [784eb9d04f](https://linux-hardware.org/?probe=784eb9d04f) | Feb 18, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [f37110c1d5](https://linux-hardware.org/?probe=f37110c1d5) | Feb 18, 2022 |
| VIT           | P3400                       | Notebook    | [b90c32748d](https://linux-hardware.org/?probe=b90c32748d) | Feb 18, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [5323885713](https://linux-hardware.org/?probe=5323885713) | Feb 17, 2022 |
| ASUSTek       | TP550LAB                    | Notebook    | [96c969a4b4](https://linux-hardware.org/?probe=96c969a4b4) | Feb 17, 2022 |
| ECS           | G31T-M9                     | Desktop     | [c239ee9817](https://linux-hardware.org/?probe=c239ee9817) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [eb1d4cf9d8](https://linux-hardware.org/?probe=eb1d4cf9d8) | Feb 17, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [9dca95891f](https://linux-hardware.org/?probe=9dca95891f) | Feb 17, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [ffd9891203](https://linux-hardware.org/?probe=ffd9891203) | Feb 17, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [b1ab92368d](https://linux-hardware.org/?probe=b1ab92368d) | Feb 17, 2022 |
| ASUSTek       | H61M-E                      | Desktop     | [8500cd1a03](https://linux-hardware.org/?probe=8500cd1a03) | Feb 17, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [e162c17653](https://linux-hardware.org/?probe=e162c17653) | Feb 17, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [89cecb62bc](https://linux-hardware.org/?probe=89cecb62bc) | Feb 17, 2022 |
| Lenovo        | ThinkPad X200 7459ZC2       | Notebook    | [897152c39c](https://linux-hardware.org/?probe=897152c39c) | Feb 16, 2022 |
| ASRock        | G41M-VGS3                   | Desktop     | [b0d8f9faed](https://linux-hardware.org/?probe=b0d8f9faed) | Feb 16, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [1fa5e259f5](https://linux-hardware.org/?probe=1fa5e259f5) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [41039ffe41](https://linux-hardware.org/?probe=41039ffe41) | Feb 16, 2022 |
| Gigabyte      | P55-UD3L                    | Desktop     | [e7318489dd](https://linux-hardware.org/?probe=e7318489dd) | Feb 16, 2022 |
| HP            | 2B2F MVB,A                  | All in one  | [06be58f9b6](https://linux-hardware.org/?probe=06be58f9b6) | Feb 16, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [92ccebcc90](https://linux-hardware.org/?probe=92ccebcc90) | Feb 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [88a943ec80](https://linux-hardware.org/?probe=88a943ec80) | Feb 16, 2022 |
| HP            | 8433 11                     | Desktop     | [3e76b8876b](https://linux-hardware.org/?probe=3e76b8876b) | Feb 16, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [84171dc3cd](https://linux-hardware.org/?probe=84171dc3cd) | Feb 16, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [c9b5c461da](https://linux-hardware.org/?probe=c9b5c461da) | Feb 15, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [bd330ce757](https://linux-hardware.org/?probe=bd330ce757) | Feb 15, 2022 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [849a97d8c3](https://linux-hardware.org/?probe=849a97d8c3) | Feb 15, 2022 |
| HP            | Pavilion TS 15              | Notebook    | [6248023e72](https://linux-hardware.org/?probe=6248023e72) | Feb 15, 2022 |
| System76      | Gazelle Professional        | Notebook    | [bd2eeafecc](https://linux-hardware.org/?probe=bd2eeafecc) | Feb 15, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [b11d43558e](https://linux-hardware.org/?probe=b11d43558e) | Feb 15, 2022 |
| MSI           | GP72M 7RDX                  | Notebook    | [2a55fc3b23](https://linux-hardware.org/?probe=2a55fc3b23) | Feb 15, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [f014fcba4f](https://linux-hardware.org/?probe=f014fcba4f) | Feb 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [a533f0d469](https://linux-hardware.org/?probe=a533f0d469) | Feb 14, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [84d678da21](https://linux-hardware.org/?probe=84d678da21) | Feb 14, 2022 |
| Gigabyte      | P55-UD3L                    | Desktop     | [bf852c386f](https://linux-hardware.org/?probe=bf852c386f) | Feb 14, 2022 |
| Medion        | Z370H4-EM                   | Desktop     | [254b8351a1](https://linux-hardware.org/?probe=254b8351a1) | Feb 14, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [9e7bbafd9c](https://linux-hardware.org/?probe=9e7bbafd9c) | Feb 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3971fd709d](https://linux-hardware.org/?probe=3971fd709d) | Feb 13, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [0303c5a132](https://linux-hardware.org/?probe=0303c5a132) | Feb 13, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [c034584d73](https://linux-hardware.org/?probe=c034584d73) | Feb 13, 2022 |
| MSI           | MS-7053                     | Desktop     | [2ee97bf0a8](https://linux-hardware.org/?probe=2ee97bf0a8) | Feb 13, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [d5ba9deed5](https://linux-hardware.org/?probe=d5ba9deed5) | Feb 13, 2022 |
| Gateway       | SX2865 V1.0                 | Desktop     | [890768bebd](https://linux-hardware.org/?probe=890768bebd) | Feb 12, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [e7c108139b](https://linux-hardware.org/?probe=e7c108139b) | Feb 12, 2022 |
| ASRock        | K8A780LM                    | Desktop     | [4ad26b4255](https://linux-hardware.org/?probe=4ad26b4255) | Feb 12, 2022 |
| ASRock        | K8A780LM                    | Desktop     | [d9641143f2](https://linux-hardware.org/?probe=d9641143f2) | Feb 12, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [393686a6c4](https://linux-hardware.org/?probe=393686a6c4) | Feb 12, 2022 |
| HP            | 829A                        | Mini pc     | [dfd0cb667c](https://linux-hardware.org/?probe=dfd0cb667c) | Feb 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [068bd73cb9](https://linux-hardware.org/?probe=068bd73cb9) | Feb 12, 2022 |
| ASUSTek       | ROG STRIX B560-E GAMING ... | Desktop     | [9b5ea5d470](https://linux-hardware.org/?probe=9b5ea5d470) | Feb 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [daa132c040](https://linux-hardware.org/?probe=daa132c040) | Feb 12, 2022 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | Desktop     | [51095189f7](https://linux-hardware.org/?probe=51095189f7) | Feb 12, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [92246486de](https://linux-hardware.org/?probe=92246486de) | Feb 12, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [5d4b14e3e0](https://linux-hardware.org/?probe=5d4b14e3e0) | Feb 12, 2022 |
| Dell          | Latitude 3410               | Notebook    | [5dfcbcab80](https://linux-hardware.org/?probe=5dfcbcab80) | Feb 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [64cfd66662](https://linux-hardware.org/?probe=64cfd66662) | Feb 11, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [9db0010267](https://linux-hardware.org/?probe=9db0010267) | Feb 11, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [7ffdca7ea4](https://linux-hardware.org/?probe=7ffdca7ea4) | Feb 11, 2022 |
| Positivo      | POS-EAA75DE                 | Desktop     | [1b14cace5c](https://linux-hardware.org/?probe=1b14cace5c) | Feb 11, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [1b6bf699a8](https://linux-hardware.org/?probe=1b6bf699a8) | Feb 11, 2022 |
| Lenovo        | ThinkPad X230 2325V4D       | Notebook    | [a6d2aed78b](https://linux-hardware.org/?probe=a6d2aed78b) | Feb 11, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [565dc78c67](https://linux-hardware.org/?probe=565dc78c67) | Feb 11, 2022 |
| Lenovo        | ThinkPad X230 2325V4D       | Notebook    | [48f266c11e](https://linux-hardware.org/?probe=48f266c11e) | Feb 11, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [16157beba6](https://linux-hardware.org/?probe=16157beba6) | Feb 11, 2022 |
| HP            | 2B34                        | Desktop     | [1281e2e4dd](https://linux-hardware.org/?probe=1281e2e4dd) | Feb 10, 2022 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c462619a26](https://linux-hardware.org/?probe=c462619a26) | Feb 10, 2022 |
| HP            | 83E0                        | Desktop     | [12a6ad4f59](https://linux-hardware.org/?probe=12a6ad4f59) | Feb 10, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [44a8558637](https://linux-hardware.org/?probe=44a8558637) | Feb 10, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [de6408497a](https://linux-hardware.org/?probe=de6408497a) | Feb 10, 2022 |
| ASUSTek       | P5B SE                      | Desktop     | [cf067d000a](https://linux-hardware.org/?probe=cf067d000a) | Feb 10, 2022 |
| Lenovo        | ThinkPad L530 24813QG       | Notebook    | [c051e2ad9b](https://linux-hardware.org/?probe=c051e2ad9b) | Feb 09, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [8e73dc39ab](https://linux-hardware.org/?probe=8e73dc39ab) | Feb 09, 2022 |
| Intel         | NUC5CPYB H61145-402         | Mini pc     | [762d0d5c0b](https://linux-hardware.org/?probe=762d0d5c0b) | Feb 09, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [7360a72c44](https://linux-hardware.org/?probe=7360a72c44) | Feb 09, 2022 |
| ASRock        | G31M-VS2                    | Desktop     | [9ec5d393d6](https://linux-hardware.org/?probe=9ec5d393d6) | Feb 09, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [516754657f](https://linux-hardware.org/?probe=516754657f) | Feb 09, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [d0bfe3fa56](https://linux-hardware.org/?probe=d0bfe3fa56) | Feb 09, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [54e246f496](https://linux-hardware.org/?probe=54e246f496) | Feb 09, 2022 |
| eMachines     | eME728                      | Notebook    | [345b9ef3cd](https://linux-hardware.org/?probe=345b9ef3cd) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [0de3e1022e](https://linux-hardware.org/?probe=0de3e1022e) | Feb 09, 2022 |
| Dell          | XPS L421X                   | Notebook    | [f84aa1d978](https://linux-hardware.org/?probe=f84aa1d978) | Feb 09, 2022 |
| Dell          | XPS L421X                   | Notebook    | [e869731d45](https://linux-hardware.org/?probe=e869731d45) | Feb 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f826957241](https://linux-hardware.org/?probe=f826957241) | Feb 08, 2022 |
| Unknown       | Amlogic Meson GXL (S905X... | Soc         | [71f0e328a1](https://linux-hardware.org/?probe=71f0e328a1) | Feb 08, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [44d65a3073](https://linux-hardware.org/?probe=44d65a3073) | Feb 08, 2022 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [c62c19ef52](https://linux-hardware.org/?probe=c62c19ef52) | Feb 08, 2022 |
| MSI           | G41M-P28                    | Desktop     | [bf1ae3ecc9](https://linux-hardware.org/?probe=bf1ae3ecc9) | Feb 08, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0b17c19b0f](https://linux-hardware.org/?probe=0b17c19b0f) | Feb 08, 2022 |
| Intel         | DZ68DB AAG27985-104         | Desktop     | [bc0462d8e3](https://linux-hardware.org/?probe=bc0462d8e3) | Feb 08, 2022 |
| eMachines     | eME728                      | Notebook    | [c04471203f](https://linux-hardware.org/?probe=c04471203f) | Feb 08, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [e159605a22](https://linux-hardware.org/?probe=e159605a22) | Feb 08, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [fb079a5d70](https://linux-hardware.org/?probe=fb079a5d70) | Feb 08, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [99626fa6fd](https://linux-hardware.org/?probe=99626fa6fd) | Feb 08, 2022 |
| ASRock        | J4125M                      | Desktop     | [fa6797fc35](https://linux-hardware.org/?probe=fa6797fc35) | Feb 08, 2022 |
| HP            | Pavilion 17                 | Notebook    | [6343416eef](https://linux-hardware.org/?probe=6343416eef) | Feb 07, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [4ceccc2e76](https://linux-hardware.org/?probe=4ceccc2e76) | Feb 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3ce22a5559](https://linux-hardware.org/?probe=3ce22a5559) | Feb 07, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [c329b2c380](https://linux-hardware.org/?probe=c329b2c380) | Feb 07, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [8291648326](https://linux-hardware.org/?probe=8291648326) | Feb 07, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [0e264c593f](https://linux-hardware.org/?probe=0e264c593f) | Feb 07, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [c0ddaf9205](https://linux-hardware.org/?probe=c0ddaf9205) | Feb 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [05e8132fd3](https://linux-hardware.org/?probe=05e8132fd3) | Feb 07, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [7d8714b9f8](https://linux-hardware.org/?probe=7d8714b9f8) | Feb 07, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [136f9d4c89](https://linux-hardware.org/?probe=136f9d4c89) | Feb 07, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [20b4867308](https://linux-hardware.org/?probe=20b4867308) | Feb 07, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [bac2b2959d](https://linux-hardware.org/?probe=bac2b2959d) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [aaceb070e8](https://linux-hardware.org/?probe=aaceb070e8) | Feb 07, 2022 |
| HP            | 81B3                        | Desktop     | [aecaad32ad](https://linux-hardware.org/?probe=aecaad32ad) | Feb 07, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [72a1b5ae56](https://linux-hardware.org/?probe=72a1b5ae56) | Feb 07, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [09e661535f](https://linux-hardware.org/?probe=09e661535f) | Feb 07, 2022 |
| HP            | 250 G3                      | Notebook    | [c54f59d942](https://linux-hardware.org/?probe=c54f59d942) | Feb 06, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [d6f8f41bc5](https://linux-hardware.org/?probe=d6f8f41bc5) | Feb 06, 2022 |
| Dell          | Latitude E6410              | Notebook    | [e8e62d3cde](https://linux-hardware.org/?probe=e8e62d3cde) | Feb 06, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [9ac652a7bf](https://linux-hardware.org/?probe=9ac652a7bf) | Feb 06, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [3dbd4103ce](https://linux-hardware.org/?probe=3dbd4103ce) | Feb 06, 2022 |
| Dell          | 06CV2N A00                  | Desktop     | [b3be05cbce](https://linux-hardware.org/?probe=b3be05cbce) | Feb 06, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [6d6a3d2ac4](https://linux-hardware.org/?probe=6d6a3d2ac4) | Feb 06, 2022 |
| Dell          | Latitude D630               | Notebook    | [b2d5d4aa5a](https://linux-hardware.org/?probe=b2d5d4aa5a) | Feb 05, 2022 |
| Dell          | Latitude E6330              | Notebook    | [41ba1619f5](https://linux-hardware.org/?probe=41ba1619f5) | Feb 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5a11c55e55](https://linux-hardware.org/?probe=5a11c55e55) | Feb 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [711d2a668d](https://linux-hardware.org/?probe=711d2a668d) | Feb 05, 2022 |
| ASRock        | G31M-S                      | Desktop     | [2b4d2d640f](https://linux-hardware.org/?probe=2b4d2d640f) | Feb 05, 2022 |
| Google        | Guado                       | Desktop     | [bfe64f10a1](https://linux-hardware.org/?probe=bfe64f10a1) | Feb 05, 2022 |
| Toshiba       | Satellite E45DW-C           | Notebook    | [e106d541e5](https://linux-hardware.org/?probe=e106d541e5) | Feb 05, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [f979fa1136](https://linux-hardware.org/?probe=f979fa1136) | Feb 05, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [5520691017](https://linux-hardware.org/?probe=5520691017) | Feb 05, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [6d5ae4cd37](https://linux-hardware.org/?probe=6d5ae4cd37) | Feb 05, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [b11a458ecb](https://linux-hardware.org/?probe=b11a458ecb) | Feb 04, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [b961721ed1](https://linux-hardware.org/?probe=b961721ed1) | Feb 04, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [09f190d4b4](https://linux-hardware.org/?probe=09f190d4b4) | Feb 04, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [37c0fc9564](https://linux-hardware.org/?probe=37c0fc9564) | Feb 04, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [417bb2f526](https://linux-hardware.org/?probe=417bb2f526) | Feb 04, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [8c7f779c9f](https://linux-hardware.org/?probe=8c7f779c9f) | Feb 04, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [abe18af5e7](https://linux-hardware.org/?probe=abe18af5e7) | Feb 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [38b8a1408d](https://linux-hardware.org/?probe=38b8a1408d) | Feb 04, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [b0c6fdf764](https://linux-hardware.org/?probe=b0c6fdf764) | Feb 04, 2022 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [cc04fe990c](https://linux-hardware.org/?probe=cc04fe990c) | Feb 03, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [ebc65d68d9](https://linux-hardware.org/?probe=ebc65d68d9) | Feb 03, 2022 |
| ASRock        | FM2A68M-HD+ R2.0            | Desktop     | [2f5f68141f](https://linux-hardware.org/?probe=2f5f68141f) | Feb 03, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | Desktop     | [f8f89a9a55](https://linux-hardware.org/?probe=f8f89a9a55) | Feb 03, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [8c7268f192](https://linux-hardware.org/?probe=8c7268f192) | Feb 03, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [a3590999f3](https://linux-hardware.org/?probe=a3590999f3) | Feb 03, 2022 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [f9b5b8a8a6](https://linux-hardware.org/?probe=f9b5b8a8a6) | Feb 03, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [8a892ea268](https://linux-hardware.org/?probe=8a892ea268) | Feb 03, 2022 |
| MSI           | MS-7309                     | Desktop     | [75c2bc30ee](https://linux-hardware.org/?probe=75c2bc30ee) | Feb 03, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [7795931f5c](https://linux-hardware.org/?probe=7795931f5c) | Feb 02, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [bed385cef6](https://linux-hardware.org/?probe=bed385cef6) | Feb 02, 2022 |
| ABIT          | IP35 PRO                    | Desktop     | [fb20f8b8dd](https://linux-hardware.org/?probe=fb20f8b8dd) | Feb 02, 2022 |
| HP            | 1587h                       | Desktop     | [92625959b4](https://linux-hardware.org/?probe=92625959b4) | Feb 02, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [a7b8841235](https://linux-hardware.org/?probe=a7b8841235) | Feb 02, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [f8f690a2b4](https://linux-hardware.org/?probe=f8f690a2b4) | Feb 02, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7808ed67c3](https://linux-hardware.org/?probe=7808ed67c3) | Feb 02, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [9d8d2dafa1](https://linux-hardware.org/?probe=9d8d2dafa1) | Feb 02, 2022 |
| Lenovo        | ThinkPad R61e 7649AL6       | Notebook    | [e7595e9b45](https://linux-hardware.org/?probe=e7595e9b45) | Feb 02, 2022 |
| Dell          | 0Y1861 A00                  | Desktop     | [cb60a2e337](https://linux-hardware.org/?probe=cb60a2e337) | Feb 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [55dc5e6e08](https://linux-hardware.org/?probe=55dc5e6e08) | Feb 01, 2022 |
| Dell          | 0Y1861 A00                  | Desktop     | [1a05a6ca0e](https://linux-hardware.org/?probe=1a05a6ca0e) | Feb 01, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8e65cfd2b2](https://linux-hardware.org/?probe=8e65cfd2b2) | Feb 01, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [d541cf4375](https://linux-hardware.org/?probe=d541cf4375) | Feb 01, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [7b6c2d4857](https://linux-hardware.org/?probe=7b6c2d4857) | Feb 01, 2022 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [b3cfaa23eb](https://linux-hardware.org/?probe=b3cfaa23eb) | Feb 01, 2022 |
| Digiboard     | MPxx                        | Desktop     | [1ea5e5205c](https://linux-hardware.org/?probe=1ea5e5205c) | Feb 01, 2022 |
| HP            | 158A                        | Desktop     | [1f77d0f211](https://linux-hardware.org/?probe=1f77d0f211) | Feb 01, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [ac9ed3224d](https://linux-hardware.org/?probe=ac9ed3224d) | Feb 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [2a3b959f49](https://linux-hardware.org/?probe=2a3b959f49) | Feb 01, 2022 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [ee7ecf2967](https://linux-hardware.org/?probe=ee7ecf2967) | Jan 31, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [512c8c256a](https://linux-hardware.org/?probe=512c8c256a) | Jan 31, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [98dc82b4af](https://linux-hardware.org/?probe=98dc82b4af) | Jan 31, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [8d478b1936](https://linux-hardware.org/?probe=8d478b1936) | Jan 31, 2022 |
| EPoX Compu... | nForce3 DDR: 8KDA3I Seri... | Desktop     | [29b8359b05](https://linux-hardware.org/?probe=29b8359b05) | Jan 31, 2022 |
| EPoX Compu... | nForce3 DDR: 8KDA3I Seri... | Desktop     | [c9e2f8c425](https://linux-hardware.org/?probe=c9e2f8c425) | Jan 31, 2022 |
| ASUSTek       | ZenBook 13 UX331UAL         | Notebook    | [1202dc6569](https://linux-hardware.org/?probe=1202dc6569) | Jan 31, 2022 |
| HP            | 3031h                       | Desktop     | [6d72e2608a](https://linux-hardware.org/?probe=6d72e2608a) | Jan 31, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [b80429c5fe](https://linux-hardware.org/?probe=b80429c5fe) | Jan 31, 2022 |
| HP            | 3031h                       | Desktop     | [dcda450860](https://linux-hardware.org/?probe=dcda450860) | Jan 31, 2022 |
| HP            | 158A                        | Desktop     | [da426c258f](https://linux-hardware.org/?probe=da426c258f) | Jan 31, 2022 |
| Dell          | 096PH3 A00                  | Mini pc     | [74450c0224](https://linux-hardware.org/?probe=74450c0224) | Jan 31, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [d60beb8456](https://linux-hardware.org/?probe=d60beb8456) | Jan 31, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [cd91d445e6](https://linux-hardware.org/?probe=cd91d445e6) | Jan 30, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [c1703ee8ee](https://linux-hardware.org/?probe=c1703ee8ee) | Jan 30, 2022 |
| MSI           | GE70 2OC\2OD\2OE            | Notebook    | [f9efba7bbf](https://linux-hardware.org/?probe=f9efba7bbf) | Jan 30, 2022 |
| ASRock        | N68C-S                      | Desktop     | [a53e0201fe](https://linux-hardware.org/?probe=a53e0201fe) | Jan 30, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [a10cf02e71](https://linux-hardware.org/?probe=a10cf02e71) | Jan 30, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [aa29a61907](https://linux-hardware.org/?probe=aa29a61907) | Jan 30, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [6f8044dd04](https://linux-hardware.org/?probe=6f8044dd04) | Jan 30, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [b7b77abd4a](https://linux-hardware.org/?probe=b7b77abd4a) | Jan 30, 2022 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [9c94c598d3](https://linux-hardware.org/?probe=9c94c598d3) | Jan 30, 2022 |
| Toshiba       | TECRA R950                  | Notebook    | [53fc5e9542](https://linux-hardware.org/?probe=53fc5e9542) | Jan 29, 2022 |
| Lenovo        | ThinkStation S20 4105L1U    | Desktop     | [f34d9d82dd](https://linux-hardware.org/?probe=f34d9d82dd) | Jan 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [6158642c8d](https://linux-hardware.org/?probe=6158642c8d) | Jan 29, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d06c6f8577](https://linux-hardware.org/?probe=d06c6f8577) | Jan 29, 2022 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [e4bbe42b5a](https://linux-hardware.org/?probe=e4bbe42b5a) | Jan 29, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [9816a8594b](https://linux-hardware.org/?probe=9816a8594b) | Jan 29, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [eaef3cbdab](https://linux-hardware.org/?probe=eaef3cbdab) | Jan 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [579b23602f](https://linux-hardware.org/?probe=579b23602f) | Jan 29, 2022 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [79073707f7](https://linux-hardware.org/?probe=79073707f7) | Jan 29, 2022 |
| Packard Be... | EasyNote LM98               | Notebook    | [92ea2431b4](https://linux-hardware.org/?probe=92ea2431b4) | Jan 29, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [c6bbc9eee8](https://linux-hardware.org/?probe=c6bbc9eee8) | Jan 29, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [efd35e8a46](https://linux-hardware.org/?probe=efd35e8a46) | Jan 28, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b22a0ac0be](https://linux-hardware.org/?probe=b22a0ac0be) | Jan 28, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [5dbc003da9](https://linux-hardware.org/?probe=5dbc003da9) | Jan 28, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [64400dd3d5](https://linux-hardware.org/?probe=64400dd3d5) | Jan 28, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [5e934e6551](https://linux-hardware.org/?probe=5e934e6551) | Jan 28, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [fb7e1fcf47](https://linux-hardware.org/?probe=fb7e1fcf47) | Jan 28, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [fa25de8775](https://linux-hardware.org/?probe=fa25de8775) | Jan 27, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [4ba7714220](https://linux-hardware.org/?probe=4ba7714220) | Jan 27, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [cf83c49673](https://linux-hardware.org/?probe=cf83c49673) | Jan 27, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [f741575389](https://linux-hardware.org/?probe=f741575389) | Jan 27, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [b994601640](https://linux-hardware.org/?probe=b994601640) | Jan 27, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [9fed64bb7e](https://linux-hardware.org/?probe=9fed64bb7e) | Jan 27, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [343ab23f97](https://linux-hardware.org/?probe=343ab23f97) | Jan 27, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [b491c2ea72](https://linux-hardware.org/?probe=b491c2ea72) | Jan 27, 2022 |
| Positivo      | Harrison                    | Notebook    | [320f20f33d](https://linux-hardware.org/?probe=320f20f33d) | Jan 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [dc0ea304b7](https://linux-hardware.org/?probe=dc0ea304b7) | Jan 26, 2022 |
| Gigabyte      | 2AC8                        | Desktop     | [dddbfc539d](https://linux-hardware.org/?probe=dddbfc539d) | Jan 26, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [2d908d8204](https://linux-hardware.org/?probe=2d908d8204) | Jan 26, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [11f5908f13](https://linux-hardware.org/?probe=11f5908f13) | Jan 26, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f7c5fb7450](https://linux-hardware.org/?probe=f7c5fb7450) | Jan 26, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [62e942ea94](https://linux-hardware.org/?probe=62e942ea94) | Jan 26, 2022 |
| Sony          | SVE15127CDS                 | Notebook    | [b3908594f0](https://linux-hardware.org/?probe=b3908594f0) | Jan 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [04c45929e9](https://linux-hardware.org/?probe=04c45929e9) | Jan 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f38245d80d](https://linux-hardware.org/?probe=f38245d80d) | Jan 25, 2022 |
| HP            | 3647h                       | Desktop     | [6d141f0ee8](https://linux-hardware.org/?probe=6d141f0ee8) | Jan 25, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [f2eb94b9ee](https://linux-hardware.org/?probe=f2eb94b9ee) | Jan 25, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [718b441098](https://linux-hardware.org/?probe=718b441098) | Jan 25, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [7500a45a9c](https://linux-hardware.org/?probe=7500a45a9c) | Jan 25, 2022 |
| HP            | ProBook 650 G5              | Notebook    | [fe61272ae2](https://linux-hardware.org/?probe=fe61272ae2) | Jan 25, 2022 |
| Lenovo        | B475 Sabine                 | Notebook    | [2093f6f299](https://linux-hardware.org/?probe=2093f6f299) | Jan 25, 2022 |
| Unknown       | T3 MRD                      | Notebook    | [2a812850f1](https://linux-hardware.org/?probe=2a812850f1) | Jan 25, 2022 |
| Acer          | Aspire 1640                 | Notebook    | [f46c03801f](https://linux-hardware.org/?probe=f46c03801f) | Jan 24, 2022 |
| Biostar       | TA970                       | Desktop     | [cf3df73bc5](https://linux-hardware.org/?probe=cf3df73bc5) | Jan 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7b46c1043e](https://linux-hardware.org/?probe=7b46c1043e) | Jan 24, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [bda0e1f7eb](https://linux-hardware.org/?probe=bda0e1f7eb) | Jan 24, 2022 |
| HP            | 83E2                        | Desktop     | [1f0f221e5b](https://linux-hardware.org/?probe=1f0f221e5b) | Jan 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1364acf470](https://linux-hardware.org/?probe=1364acf470) | Jan 24, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [346d44071e](https://linux-hardware.org/?probe=346d44071e) | Jan 24, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ebd7350895](https://linux-hardware.org/?probe=ebd7350895) | Jan 24, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f90526243e](https://linux-hardware.org/?probe=f90526243e) | Jan 24, 2022 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [095fa0909e](https://linux-hardware.org/?probe=095fa0909e) | Jan 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [032ee6d6c0](https://linux-hardware.org/?probe=032ee6d6c0) | Jan 24, 2022 |
| Unknown       | 0XWDCF A01                  | Server      | [f5f07bffc2](https://linux-hardware.org/?probe=f5f07bffc2) | Jan 24, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [9ea2007217](https://linux-hardware.org/?probe=9ea2007217) | Jan 24, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [7f69220928](https://linux-hardware.org/?probe=7f69220928) | Jan 24, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [d89e0eaac6](https://linux-hardware.org/?probe=d89e0eaac6) | Jan 24, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [1f1008ad86](https://linux-hardware.org/?probe=1f1008ad86) | Jan 24, 2022 |
| Lenovo        | ThinkPad T580 20LAS4KG0Q    | Notebook    | [b552b967e4](https://linux-hardware.org/?probe=b552b967e4) | Jan 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9f5905c095](https://linux-hardware.org/?probe=9f5905c095) | Jan 24, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [a3aa535c25](https://linux-hardware.org/?probe=a3aa535c25) | Jan 24, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [dae0e58890](https://linux-hardware.org/?probe=dae0e58890) | Jan 23, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [8ee01c475e](https://linux-hardware.org/?probe=8ee01c475e) | Jan 23, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [739904e65c](https://linux-hardware.org/?probe=739904e65c) | Jan 23, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [276caa5169](https://linux-hardware.org/?probe=276caa5169) | Jan 23, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [d0ecbeff52](https://linux-hardware.org/?probe=d0ecbeff52) | Jan 23, 2022 |
| ASUSTek       | B85M-G PLUS/USB             | Desktop     | [f02501a8a9](https://linux-hardware.org/?probe=f02501a8a9) | Jan 23, 2022 |
| HP            | 17E2                        | Mini pc     | [ae54c309d5](https://linux-hardware.org/?probe=ae54c309d5) | Jan 23, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96f97ed2d6](https://linux-hardware.org/?probe=96f97ed2d6) | Jan 23, 2022 |
| Dell          | Latitude 5310               | Notebook    | [424fadc888](https://linux-hardware.org/?probe=424fadc888) | Jan 23, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [5832d766ab](https://linux-hardware.org/?probe=5832d766ab) | Jan 23, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [3fd790d682](https://linux-hardware.org/?probe=3fd790d682) | Jan 23, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [586c28a98a](https://linux-hardware.org/?probe=586c28a98a) | Jan 23, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [310b719b15](https://linux-hardware.org/?probe=310b719b15) | Jan 23, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [515465fd5a](https://linux-hardware.org/?probe=515465fd5a) | Jan 22, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [012cafbe22](https://linux-hardware.org/?probe=012cafbe22) | Jan 22, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [794a06d193](https://linux-hardware.org/?probe=794a06d193) | Jan 22, 2022 |
| Dell          | Inspiron 6000               | Notebook    | [9bbb0b47c9](https://linux-hardware.org/?probe=9bbb0b47c9) | Jan 22, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [c706f6dd55](https://linux-hardware.org/?probe=c706f6dd55) | Jan 21, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [b736a56c19](https://linux-hardware.org/?probe=b736a56c19) | Jan 21, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [1f5146de0a](https://linux-hardware.org/?probe=1f5146de0a) | Jan 21, 2022 |
| Dell          | Latitude 7410               | Convertible | [e738a67125](https://linux-hardware.org/?probe=e738a67125) | Jan 21, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [ab31e5f54c](https://linux-hardware.org/?probe=ab31e5f54c) | Jan 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [05e17dc297](https://linux-hardware.org/?probe=05e17dc297) | Jan 21, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [164b959848](https://linux-hardware.org/?probe=164b959848) | Jan 21, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [01c29c2e8c](https://linux-hardware.org/?probe=01c29c2e8c) | Jan 21, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c2bec0fc16](https://linux-hardware.org/?probe=c2bec0fc16) | Jan 21, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [16dc35d7f3](https://linux-hardware.org/?probe=16dc35d7f3) | Jan 21, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e211c03111](https://linux-hardware.org/?probe=e211c03111) | Jan 21, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [bb336e025c](https://linux-hardware.org/?probe=bb336e025c) | Jan 21, 2022 |
| ASUSTek       | M4A77TD                     | Desktop     | [def5a2ab70](https://linux-hardware.org/?probe=def5a2ab70) | Jan 21, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [913bcfdde8](https://linux-hardware.org/?probe=913bcfdde8) | Jan 21, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0962dc3d31](https://linux-hardware.org/?probe=0962dc3d31) | Jan 21, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [76589eb682](https://linux-hardware.org/?probe=76589eb682) | Jan 21, 2022 |
| HP            | 158A                        | Desktop     | [98a8d6a378](https://linux-hardware.org/?probe=98a8d6a378) | Jan 21, 2022 |
| HP            | 158A                        | Desktop     | [c889f7be59](https://linux-hardware.org/?probe=c889f7be59) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [f9deb1d329](https://linux-hardware.org/?probe=f9deb1d329) | Jan 20, 2022 |
| Lenovo        | B475 Sabine                 | Notebook    | [4f40d723c5](https://linux-hardware.org/?probe=4f40d723c5) | Jan 20, 2022 |
| HP            | Pavilion g7                 | Notebook    | [f789fa0e4b](https://linux-hardware.org/?probe=f789fa0e4b) | Jan 20, 2022 |
| Dell          | Latitude E6410              | Notebook    | [2e43a65524](https://linux-hardware.org/?probe=2e43a65524) | Jan 20, 2022 |
| Supermicro    | X11SAE                      | Server      | [79e6eafc82](https://linux-hardware.org/?probe=79e6eafc82) | Jan 20, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [c1b18abd63](https://linux-hardware.org/?probe=c1b18abd63) | Jan 20, 2022 |
| HP            | Pavilion g7                 | Notebook    | [064474c7e0](https://linux-hardware.org/?probe=064474c7e0) | Jan 20, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [4b8a587819](https://linux-hardware.org/?probe=4b8a587819) | Jan 20, 2022 |
| Intel         | S1200RP G62251-406          | Server      | [f257c969da](https://linux-hardware.org/?probe=f257c969da) | Jan 20, 2022 |
| Intel         | S1200RP G62251-406          | Server      | [981732655f](https://linux-hardware.org/?probe=981732655f) | Jan 20, 2022 |
| Alienware     | 17 R3                       | Notebook    | [032772ad42](https://linux-hardware.org/?probe=032772ad42) | Jan 20, 2022 |
| Supermicro    | X8DA3                       | Server      | [67816634d5](https://linux-hardware.org/?probe=67816634d5) | Jan 20, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [8433f6a685](https://linux-hardware.org/?probe=8433f6a685) | Jan 20, 2022 |
| ASRock        | G31M-S                      | Desktop     | [9d338d58c9](https://linux-hardware.org/?probe=9d338d58c9) | Jan 20, 2022 |
| AZW           | GK55                        | Desktop     | [f7fbdb5987](https://linux-hardware.org/?probe=f7fbdb5987) | Jan 19, 2022 |
| Dell          | Latitude E6330              | Notebook    | [2c94023cca](https://linux-hardware.org/?probe=2c94023cca) | Jan 19, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [e236263783](https://linux-hardware.org/?probe=e236263783) | Jan 19, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [6a311bab4a](https://linux-hardware.org/?probe=6a311bab4a) | Jan 19, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [8e66dbbe5c](https://linux-hardware.org/?probe=8e66dbbe5c) | Jan 19, 2022 |
| Dell          | Precision 3561              | Notebook    | [05b06d8c48](https://linux-hardware.org/?probe=05b06d8c48) | Jan 19, 2022 |
| HP            | Pavilion g6                 | Notebook    | [2acc56ff71](https://linux-hardware.org/?probe=2acc56ff71) | Jan 19, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [700b09fbb1](https://linux-hardware.org/?probe=700b09fbb1) | Jan 19, 2022 |
| Dell          | Precision 5560              | Notebook    | [4404c43852](https://linux-hardware.org/?probe=4404c43852) | Jan 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [c4465062c7](https://linux-hardware.org/?probe=c4465062c7) | Jan 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [efdc064669](https://linux-hardware.org/?probe=efdc064669) | Jan 19, 2022 |
| Sony          | VPCF12C5E                   | Notebook    | [7c8ee2ed3b](https://linux-hardware.org/?probe=7c8ee2ed3b) | Jan 19, 2022 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [1158cbfeaa](https://linux-hardware.org/?probe=1158cbfeaa) | Jan 18, 2022 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [53b6312ff6](https://linux-hardware.org/?probe=53b6312ff6) | Jan 18, 2022 |
| Lenovo        | B475 Sabine                 | Notebook    | [68b04eef9d](https://linux-hardware.org/?probe=68b04eef9d) | Jan 18, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [1d5ac9894a](https://linux-hardware.org/?probe=1d5ac9894a) | Jan 18, 2022 |
| Lenovo        | G580                        | Notebook    | [b575a14a10](https://linux-hardware.org/?probe=b575a14a10) | Jan 18, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [eea8c3a5c3](https://linux-hardware.org/?probe=eea8c3a5c3) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [c021e3bb40](https://linux-hardware.org/?probe=c021e3bb40) | Jan 18, 2022 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [fc313a8f4a](https://linux-hardware.org/?probe=fc313a8f4a) | Jan 18, 2022 |
| HP            | Notebook                    | Notebook    | [782c51f796](https://linux-hardware.org/?probe=782c51f796) | Jan 17, 2022 |
| Dell          | Latitude 5420               | Notebook    | [dd45d8465d](https://linux-hardware.org/?probe=dd45d8465d) | Jan 17, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [a28c50c71f](https://linux-hardware.org/?probe=a28c50c71f) | Jan 17, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [a3133c9aab](https://linux-hardware.org/?probe=a3133c9aab) | Jan 17, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [d897de368d](https://linux-hardware.org/?probe=d897de368d) | Jan 17, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [5052313cdf](https://linux-hardware.org/?probe=5052313cdf) | Jan 17, 2022 |
| Lenovo        | G580                        | Notebook    | [554ee0ef82](https://linux-hardware.org/?probe=554ee0ef82) | Jan 17, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [72d6b552aa](https://linux-hardware.org/?probe=72d6b552aa) | Jan 17, 2022 |
| HP            | 2B2F MVB,A                  | All in one  | [f6f22d94e8](https://linux-hardware.org/?probe=f6f22d94e8) | Jan 17, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [957331295f](https://linux-hardware.org/?probe=957331295f) | Jan 17, 2022 |
| IBM           | 2647QU6                     | Notebook    | [41283220a2](https://linux-hardware.org/?probe=41283220a2) | Jan 17, 2022 |
| Dell          | Latitude E5570              | Notebook    | [5c4c02c6f4](https://linux-hardware.org/?probe=5c4c02c6f4) | Jan 16, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [07f1a949ab](https://linux-hardware.org/?probe=07f1a949ab) | Jan 16, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [ee6c3d4eef](https://linux-hardware.org/?probe=ee6c3d4eef) | Jan 16, 2022 |
| Lenovo        | ThinkPad T480 20L6A0UGCL    | Notebook    | [e9dbb29c83](https://linux-hardware.org/?probe=e9dbb29c83) | Jan 16, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [86b8b64223](https://linux-hardware.org/?probe=86b8b64223) | Jan 16, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [c0f3709a57](https://linux-hardware.org/?probe=c0f3709a57) | Jan 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [dae8d10589](https://linux-hardware.org/?probe=dae8d10589) | Jan 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [fb799bb9f5](https://linux-hardware.org/?probe=fb799bb9f5) | Jan 15, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [bae7c1cd50](https://linux-hardware.org/?probe=bae7c1cd50) | Jan 15, 2022 |
| ASUSTek       | P5QL PRO                    | Desktop     | [18abe058ad](https://linux-hardware.org/?probe=18abe058ad) | Jan 15, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [aec7aaa74d](https://linux-hardware.org/?probe=aec7aaa74d) | Jan 15, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [96b0a9dbdc](https://linux-hardware.org/?probe=96b0a9dbdc) | Jan 14, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [5c41a54599](https://linux-hardware.org/?probe=5c41a54599) | Jan 14, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [9f0d682171](https://linux-hardware.org/?probe=9f0d682171) | Jan 14, 2022 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [53c16c3d57](https://linux-hardware.org/?probe=53c16c3d57) | Jan 14, 2022 |
| ASUSTek       | M4A77TD                     | Desktop     | [f9f3b0fe25](https://linux-hardware.org/?probe=f9f3b0fe25) | Jan 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a1eece283c](https://linux-hardware.org/?probe=a1eece283c) | Jan 14, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [eb4e0295d3](https://linux-hardware.org/?probe=eb4e0295d3) | Jan 14, 2022 |
| MSI           | MS-1454                     | Notebook    | [1cb9a056e7](https://linux-hardware.org/?probe=1cb9a056e7) | Jan 14, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [57fe150494](https://linux-hardware.org/?probe=57fe150494) | Jan 14, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [79e884f81e](https://linux-hardware.org/?probe=79e884f81e) | Jan 14, 2022 |
| Lex BayTra... | 3I380A                      | Notebook    | [7f59432801](https://linux-hardware.org/?probe=7f59432801) | Jan 14, 2022 |
| Lenovo        | ThinkPad P53 20QQA004CD     | Notebook    | [9d63aff476](https://linux-hardware.org/?probe=9d63aff476) | Jan 14, 2022 |
| HP            | Mini 110-1100               | Notebook    | [10271759b0](https://linux-hardware.org/?probe=10271759b0) | Jan 14, 2022 |
| MSI           | MS-7255                     | Desktop     | [bf4604061a](https://linux-hardware.org/?probe=bf4604061a) | Jan 14, 2022 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [3a0dfc604b](https://linux-hardware.org/?probe=3a0dfc604b) | Jan 14, 2022 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [fe9a417d5d](https://linux-hardware.org/?probe=fe9a417d5d) | Jan 14, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [5cb4bc2ed8](https://linux-hardware.org/?probe=5cb4bc2ed8) | Jan 14, 2022 |
| Medion        | Z370H4-EM                   | Desktop     | [a4bb231aa7](https://linux-hardware.org/?probe=a4bb231aa7) | Jan 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [8eab984583](https://linux-hardware.org/?probe=8eab984583) | Jan 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3050abff3a](https://linux-hardware.org/?probe=3050abff3a) | Jan 13, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [a68454eff9](https://linux-hardware.org/?probe=a68454eff9) | Jan 13, 2022 |
| Acer          | AOD255E                     | Notebook    | [cf1f3ab0e0](https://linux-hardware.org/?probe=cf1f3ab0e0) | Jan 13, 2022 |
| MSI           | MS-7309                     | Desktop     | [b980404ce1](https://linux-hardware.org/?probe=b980404ce1) | Jan 13, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [8f8b9d9cc5](https://linux-hardware.org/?probe=8f8b9d9cc5) | Jan 13, 2022 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [ef676712a0](https://linux-hardware.org/?probe=ef676712a0) | Jan 12, 2022 |
| ASRock        | B85M-HDS                    | Desktop     | [77cb3218a8](https://linux-hardware.org/?probe=77cb3218a8) | Jan 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9f68c2c102](https://linux-hardware.org/?probe=9f68c2c102) | Jan 12, 2022 |
| Samsung       | 535U3C                      | Notebook    | [c18e5d660d](https://linux-hardware.org/?probe=c18e5d660d) | Jan 12, 2022 |
| HP            | 82B4                        | Desktop     | [79444cc816](https://linux-hardware.org/?probe=79444cc816) | Jan 12, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [9c5f9bb3c6](https://linux-hardware.org/?probe=9c5f9bb3c6) | Jan 12, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [46d42db225](https://linux-hardware.org/?probe=46d42db225) | Jan 12, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [5c58aa5b86](https://linux-hardware.org/?probe=5c58aa5b86) | Jan 12, 2022 |
| Compal        | NCL60/61                    | Notebook    | [3f71d0d088](https://linux-hardware.org/?probe=3f71d0d088) | Jan 12, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [fb5417c823](https://linux-hardware.org/?probe=fb5417c823) | Jan 12, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [d0e05a158d](https://linux-hardware.org/?probe=d0e05a158d) | Jan 11, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [fa5b04fccd](https://linux-hardware.org/?probe=fa5b04fccd) | Jan 11, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [4168195256](https://linux-hardware.org/?probe=4168195256) | Jan 11, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [f45f45197a](https://linux-hardware.org/?probe=f45f45197a) | Jan 11, 2022 |
| Aquarius      | NS585                       | Notebook    | [05fa3aee01](https://linux-hardware.org/?probe=05fa3aee01) | Jan 11, 2022 |
| Aquarius      | NS585                       | Notebook    | [00bdbd3175](https://linux-hardware.org/?probe=00bdbd3175) | Jan 11, 2022 |
| Aquarius      | NS585                       | Notebook    | [ff9e56cc49](https://linux-hardware.org/?probe=ff9e56cc49) | Jan 11, 2022 |
| Aquarius      | NS585                       | Notebook    | [4225f64fae](https://linux-hardware.org/?probe=4225f64fae) | Jan 11, 2022 |
| Aquarius      | NS585                       | Notebook    | [fc09ae03e2](https://linux-hardware.org/?probe=fc09ae03e2) | Jan 11, 2022 |
| Toshiba       | Satellite C660D             | Notebook    | [99758d2a73](https://linux-hardware.org/?probe=99758d2a73) | Jan 11, 2022 |
| Aquarius      | NS585                       | Notebook    | [e892be3b29](https://linux-hardware.org/?probe=e892be3b29) | Jan 11, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [fd57c1981b](https://linux-hardware.org/?probe=fd57c1981b) | Jan 11, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f21bede8f0](https://linux-hardware.org/?probe=f21bede8f0) | Jan 11, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [19857c8f84](https://linux-hardware.org/?probe=19857c8f84) | Jan 11, 2022 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [dcd83fe037](https://linux-hardware.org/?probe=dcd83fe037) | Jan 10, 2022 |
| MOTION        | KEX00                       | Notebook    | [8ff3554d7d](https://linux-hardware.org/?probe=8ff3554d7d) | Jan 10, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [e9f4084086](https://linux-hardware.org/?probe=e9f4084086) | Jan 10, 2022 |
| Medion        | MS-7708                     | Desktop     | [730133d40b](https://linux-hardware.org/?probe=730133d40b) | Jan 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [a046d0cd96](https://linux-hardware.org/?probe=a046d0cd96) | Jan 10, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [ec14408cbe](https://linux-hardware.org/?probe=ec14408cbe) | Jan 10, 2022 |
| MSI           | B360M PRO-VDH               | Desktop     | [bd136c19e0](https://linux-hardware.org/?probe=bd136c19e0) | Jan 10, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [57fc8e39d7](https://linux-hardware.org/?probe=57fc8e39d7) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [7ce7a30da1](https://linux-hardware.org/?probe=7ce7a30da1) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [ac620bc1b6](https://linux-hardware.org/?probe=ac620bc1b6) | Jan 10, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [b874d96145](https://linux-hardware.org/?probe=b874d96145) | Jan 10, 2022 |
| HP            | 1589                        | Desktop     | [fea389a369](https://linux-hardware.org/?probe=fea389a369) | Jan 10, 2022 |
| Lenovo        | B490 37722LP                | Notebook    | [c36fa4c158](https://linux-hardware.org/?probe=c36fa4c158) | Jan 10, 2022 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [7e26a217f2](https://linux-hardware.org/?probe=7e26a217f2) | Jan 09, 2022 |
| HP            | Presario CQ56               | Notebook    | [17e7a9c9d1](https://linux-hardware.org/?probe=17e7a9c9d1) | Jan 09, 2022 |
| Sony          | VPCS13V9E                   | Notebook    | [609e1c504a](https://linux-hardware.org/?probe=609e1c504a) | Jan 09, 2022 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [fdcf291970](https://linux-hardware.org/?probe=fdcf291970) | Jan 09, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [4df70f0938](https://linux-hardware.org/?probe=4df70f0938) | Jan 09, 2022 |
| Gigabyte      | W480M VISION W              | Desktop     | [dca115751f](https://linux-hardware.org/?probe=dca115751f) | Jan 09, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [2bb43fbbb1](https://linux-hardware.org/?probe=2bb43fbbb1) | Jan 09, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [5de9fddbf7](https://linux-hardware.org/?probe=5de9fddbf7) | Jan 09, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [29f18e6869](https://linux-hardware.org/?probe=29f18e6869) | Jan 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [99a245965c](https://linux-hardware.org/?probe=99a245965c) | Jan 09, 2022 |
| Dell          | Latitude E5420              | Notebook    | [28c33b9e71](https://linux-hardware.org/?probe=28c33b9e71) | Jan 09, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [c6da06ae31](https://linux-hardware.org/?probe=c6da06ae31) | Jan 09, 2022 |
| Sony          | SVS13A1C5E                  | Notebook    | [891a2d4782](https://linux-hardware.org/?probe=891a2d4782) | Jan 09, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [aa059ae8f8](https://linux-hardware.org/?probe=aa059ae8f8) | Jan 09, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [56ebb4b643](https://linux-hardware.org/?probe=56ebb4b643) | Jan 09, 2022 |
| HP            | 18E7                        | Desktop     | [a46399c837](https://linux-hardware.org/?probe=a46399c837) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [c290fc6fc3](https://linux-hardware.org/?probe=c290fc6fc3) | Jan 08, 2022 |
| Dell          | Latitude E6330              | Notebook    | [da29c6f100](https://linux-hardware.org/?probe=da29c6f100) | Jan 08, 2022 |
| ASUSTek       | P8H61-I                     | Desktop     | [261ea10bf8](https://linux-hardware.org/?probe=261ea10bf8) | Jan 08, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [e96ad6257b](https://linux-hardware.org/?probe=e96ad6257b) | Jan 08, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [8401b2859b](https://linux-hardware.org/?probe=8401b2859b) | Jan 08, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [877aa77469](https://linux-hardware.org/?probe=877aa77469) | Jan 08, 2022 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [120f2dd1c4](https://linux-hardware.org/?probe=120f2dd1c4) | Jan 08, 2022 |
| Sony          | VPCEB3S1E                   | Notebook    | [6f78e2d423](https://linux-hardware.org/?probe=6f78e2d423) | Jan 07, 2022 |
| Acer          | Aspire 7720G                | Notebook    | [61e120f622](https://linux-hardware.org/?probe=61e120f622) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f09949e50f](https://linux-hardware.org/?probe=f09949e50f) | Jan 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [ee6b48f115](https://linux-hardware.org/?probe=ee6b48f115) | Jan 07, 2022 |
| Dell          | Latitude E5420              | Notebook    | [89617aa917](https://linux-hardware.org/?probe=89617aa917) | Jan 07, 2022 |
| ASUSTek       | K53U                        | Notebook    | [62410e0adc](https://linux-hardware.org/?probe=62410e0adc) | Jan 07, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [a38592dcaf](https://linux-hardware.org/?probe=a38592dcaf) | Jan 06, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [d22f32f071](https://linux-hardware.org/?probe=d22f32f071) | Jan 06, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [bd3b3a2b3e](https://linux-hardware.org/?probe=bd3b3a2b3e) | Jan 06, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [22e51b8b41](https://linux-hardware.org/?probe=22e51b8b41) | Jan 06, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [52db8d0bbf](https://linux-hardware.org/?probe=52db8d0bbf) | Jan 06, 2022 |
| HP            | 3396                        | Desktop     | [939dc1ef96](https://linux-hardware.org/?probe=939dc1ef96) | Jan 06, 2022 |
| HP            | 3396                        | Desktop     | [39df16b288](https://linux-hardware.org/?probe=39df16b288) | Jan 06, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [110935722f](https://linux-hardware.org/?probe=110935722f) | Jan 05, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [78ea49cf6a](https://linux-hardware.org/?probe=78ea49cf6a) | Jan 05, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [f691531281](https://linux-hardware.org/?probe=f691531281) | Jan 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [0d69dca8f3](https://linux-hardware.org/?probe=0d69dca8f3) | Jan 04, 2022 |
| ASUSTek       | X751LK                      | Notebook    | [c155fbdd7b](https://linux-hardware.org/?probe=c155fbdd7b) | Jan 04, 2022 |
| Medion        | P6620                       | Notebook    | [dbf6822c89](https://linux-hardware.org/?probe=dbf6822c89) | Jan 04, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [d7ed8aaee8](https://linux-hardware.org/?probe=d7ed8aaee8) | Jan 04, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [2d698abe0e](https://linux-hardware.org/?probe=2d698abe0e) | Jan 04, 2022 |
| ASUSTek       | P5QL-VM DO                  | Desktop     | [924ba5ac94](https://linux-hardware.org/?probe=924ba5ac94) | Jan 04, 2022 |
| HP            | 0AACh                       | Desktop     | [fb95b0029a](https://linux-hardware.org/?probe=fb95b0029a) | Jan 04, 2022 |
| Unknown       | Unknown                     | Soc         | [5649de254b](https://linux-hardware.org/?probe=5649de254b) | Jan 04, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [1cdd36f612](https://linux-hardware.org/?probe=1cdd36f612) | Jan 04, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [36f0adee44](https://linux-hardware.org/?probe=36f0adee44) | Jan 04, 2022 |
| Fujitsu       | D3446-S1 S26361-D3446-S1    | Desktop     | [8b38b529e9](https://linux-hardware.org/?probe=8b38b529e9) | Jan 03, 2022 |
| Lenovo        | 3178 NOK                    | Desktop     | [38785dd89c](https://linux-hardware.org/?probe=38785dd89c) | Jan 03, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [3e6d1befd6](https://linux-hardware.org/?probe=3e6d1befd6) | Jan 03, 2022 |
| Compal        | QAL51                       | Notebook    | [28d555a161](https://linux-hardware.org/?probe=28d555a161) | Jan 03, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [da4d6def3d](https://linux-hardware.org/?probe=da4d6def3d) | Jan 03, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [19b1fdc5cd](https://linux-hardware.org/?probe=19b1fdc5cd) | Jan 02, 2022 |
| Lenovo        | ThinkPad W530 24382HU       | Notebook    | [5a4cc794e4](https://linux-hardware.org/?probe=5a4cc794e4) | Jan 02, 2022 |
| HP            | 15 TS                       | Notebook    | [f65f0315ec](https://linux-hardware.org/?probe=f65f0315ec) | Jan 02, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [de0e6691cd](https://linux-hardware.org/?probe=de0e6691cd) | Jan 02, 2022 |
| Samsung       | 750XDA                      | Notebook    | [86824eb8ff](https://linux-hardware.org/?probe=86824eb8ff) | Jan 02, 2022 |
| Jumper        | EZbook                      | Notebook    | [2a9ea409b3](https://linux-hardware.org/?probe=2a9ea409b3) | Jan 01, 2022 |
| Medion        | Akoya P7818                 | Notebook    | [3fcc005174](https://linux-hardware.org/?probe=3fcc005174) | Jan 01, 2022 |
| Samsung       | 750XDA                      | Notebook    | [2b99263c43](https://linux-hardware.org/?probe=2b99263c43) | Jan 01, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [a73a640600](https://linux-hardware.org/?probe=a73a640600) | Jan 01, 2022 |
| HP            | ProBook 650 G5              | Notebook    | [10c33cbcd2](https://linux-hardware.org/?probe=10c33cbcd2) | Jan 01, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [eede59cbf0](https://linux-hardware.org/?probe=eede59cbf0) | Jan 01, 2022 |
| ASUSTek       | X756UXK                     | Notebook    | [3f565d70fe](https://linux-hardware.org/?probe=3f565d70fe) | Jan 01, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [1fbd5a6a63](https://linux-hardware.org/?probe=1fbd5a6a63) | Jan 01, 2022 |
| Dell          | 0RW203                      | Desktop     | [7d16607324](https://linux-hardware.org/?probe=7d16607324) | Dec 31, 2021 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [66aea34547](https://linux-hardware.org/?probe=66aea34547) | Dec 31, 2021 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [d88a39fa09](https://linux-hardware.org/?probe=d88a39fa09) | Dec 31, 2021 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [563f0e150e](https://linux-hardware.org/?probe=563f0e150e) | Dec 31, 2021 |
| HP            | Presario CQ56               | Notebook    | [aacf56218d](https://linux-hardware.org/?probe=aacf56218d) | Dec 31, 2021 |
| HP            | ProBook 650 G5              | Notebook    | [668c6a4644](https://linux-hardware.org/?probe=668c6a4644) | Dec 31, 2021 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [4302dae812](https://linux-hardware.org/?probe=4302dae812) | Dec 31, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [28e0273758](https://linux-hardware.org/?probe=28e0273758) | Dec 31, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b46dd6fe7c](https://linux-hardware.org/?probe=b46dd6fe7c) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ce459e852d](https://linux-hardware.org/?probe=ce459e852d) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5c67e4e3bd](https://linux-hardware.org/?probe=5c67e4e3bd) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a2bd289576](https://linux-hardware.org/?probe=a2bd289576) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [492b0e06e2](https://linux-hardware.org/?probe=492b0e06e2) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [06ae302e2c](https://linux-hardware.org/?probe=06ae302e2c) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [16ac2d8530](https://linux-hardware.org/?probe=16ac2d8530) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9c80ecde0d](https://linux-hardware.org/?probe=9c80ecde0d) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [08b6f7de90](https://linux-hardware.org/?probe=08b6f7de90) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c27c575717](https://linux-hardware.org/?probe=c27c575717) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2af6ebb15f](https://linux-hardware.org/?probe=2af6ebb15f) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ac341e402f](https://linux-hardware.org/?probe=ac341e402f) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d2e6dd499a](https://linux-hardware.org/?probe=d2e6dd499a) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1a5ee2fdfa](https://linux-hardware.org/?probe=1a5ee2fdfa) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [834af2e153](https://linux-hardware.org/?probe=834af2e153) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5ef10ade6e](https://linux-hardware.org/?probe=5ef10ade6e) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3289475362](https://linux-hardware.org/?probe=3289475362) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [86e5ed0024](https://linux-hardware.org/?probe=86e5ed0024) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [db70be245e](https://linux-hardware.org/?probe=db70be245e) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ea5bb3ee0a](https://linux-hardware.org/?probe=ea5bb3ee0a) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [68f7492a1f](https://linux-hardware.org/?probe=68f7492a1f) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7812a54aab](https://linux-hardware.org/?probe=7812a54aab) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [55150c95b1](https://linux-hardware.org/?probe=55150c95b1) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6a086f8303](https://linux-hardware.org/?probe=6a086f8303) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d8b54e410d](https://linux-hardware.org/?probe=d8b54e410d) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [443df520f1](https://linux-hardware.org/?probe=443df520f1) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [705872a6fc](https://linux-hardware.org/?probe=705872a6fc) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ecb3e93176](https://linux-hardware.org/?probe=ecb3e93176) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [883dce039c](https://linux-hardware.org/?probe=883dce039c) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [77ab95cab9](https://linux-hardware.org/?probe=77ab95cab9) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1678263e8a](https://linux-hardware.org/?probe=1678263e8a) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5ff3ac789a](https://linux-hardware.org/?probe=5ff3ac789a) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f3704e4853](https://linux-hardware.org/?probe=f3704e4853) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [81168d8409](https://linux-hardware.org/?probe=81168d8409) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ab418c0482](https://linux-hardware.org/?probe=ab418c0482) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [666990bc32](https://linux-hardware.org/?probe=666990bc32) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fcd57877d1](https://linux-hardware.org/?probe=fcd57877d1) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [39c4bc12bd](https://linux-hardware.org/?probe=39c4bc12bd) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d65d38e313](https://linux-hardware.org/?probe=d65d38e313) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [db59f8af69](https://linux-hardware.org/?probe=db59f8af69) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [86678b10ea](https://linux-hardware.org/?probe=86678b10ea) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9a706fad29](https://linux-hardware.org/?probe=9a706fad29) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [56dc48a07b](https://linux-hardware.org/?probe=56dc48a07b) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d3056d4f3d](https://linux-hardware.org/?probe=d3056d4f3d) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [13809c5b01](https://linux-hardware.org/?probe=13809c5b01) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f555d2cfac](https://linux-hardware.org/?probe=f555d2cfac) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [db46172aea](https://linux-hardware.org/?probe=db46172aea) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f8462800a6](https://linux-hardware.org/?probe=f8462800a6) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9d09a311fd](https://linux-hardware.org/?probe=9d09a311fd) | Dec 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [579801daae](https://linux-hardware.org/?probe=579801daae) | Dec 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [c08374a615](https://linux-hardware.org/?probe=c08374a615) | Dec 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [cbe80d8c24](https://linux-hardware.org/?probe=cbe80d8c24) | Dec 30, 2021 |
| Dell          | Latitude E5420              | Notebook    | [dc28d41913](https://linux-hardware.org/?probe=dc28d41913) | Dec 30, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [8a1a113e52](https://linux-hardware.org/?probe=8a1a113e52) | Dec 30, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [a38b433d5e](https://linux-hardware.org/?probe=a38b433d5e) | Dec 30, 2021 |
| HP            | 8906 SMVB                   | Desktop     | [be19f6df45](https://linux-hardware.org/?probe=be19f6df45) | Dec 29, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [9d363caf9e](https://linux-hardware.org/?probe=9d363caf9e) | Dec 29, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [a7f26d9823](https://linux-hardware.org/?probe=a7f26d9823) | Dec 29, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [02f8579bf3](https://linux-hardware.org/?probe=02f8579bf3) | Dec 29, 2021 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [d2544fc8dc](https://linux-hardware.org/?probe=d2544fc8dc) | Dec 29, 2021 |
| Lenovo        | ThinkPad A485 20MU000CMH    | Notebook    | [ec36ac81a4](https://linux-hardware.org/?probe=ec36ac81a4) | Dec 29, 2021 |
| ASUSTek       | UX303LAB                    | Notebook    | [196ff1f41f](https://linux-hardware.org/?probe=196ff1f41f) | Dec 29, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [51d4addbb3](https://linux-hardware.org/?probe=51d4addbb3) | Dec 29, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [209e15690e](https://linux-hardware.org/?probe=209e15690e) | Dec 29, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [b44ab55a4d](https://linux-hardware.org/?probe=b44ab55a4d) | Dec 28, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [9679415e5e](https://linux-hardware.org/?probe=9679415e5e) | Dec 28, 2021 |
| ASRock        | J4105M                      | Desktop     | [37f37bbbfd](https://linux-hardware.org/?probe=37f37bbbfd) | Dec 28, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [10ec2e2912](https://linux-hardware.org/?probe=10ec2e2912) | Dec 28, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [47497df950](https://linux-hardware.org/?probe=47497df950) | Dec 28, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [896ea31fe5](https://linux-hardware.org/?probe=896ea31fe5) | Dec 28, 2021 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [d644ed8f37](https://linux-hardware.org/?probe=d644ed8f37) | Dec 28, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [98bccb86b2](https://linux-hardware.org/?probe=98bccb86b2) | Dec 28, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [f0d7556c6b](https://linux-hardware.org/?probe=f0d7556c6b) | Dec 28, 2021 |
| ASUSTek       | A7V                         | Notebook    | [33b743a9bc](https://linux-hardware.org/?probe=33b743a9bc) | Dec 28, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [01df3a24cd](https://linux-hardware.org/?probe=01df3a24cd) | Dec 28, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4a40c7a706](https://linux-hardware.org/?probe=4a40c7a706) | Dec 28, 2021 |
| ASRock        | X370 Pro4                   | Desktop     | [701f9ae732](https://linux-hardware.org/?probe=701f9ae732) | Dec 28, 2021 |
| ASRock        | X370 Pro4                   | Desktop     | [d6585bd061](https://linux-hardware.org/?probe=d6585bd061) | Dec 28, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [34bc7aa429](https://linux-hardware.org/?probe=34bc7aa429) | Dec 27, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [8fdd3d78c9](https://linux-hardware.org/?probe=8fdd3d78c9) | Dec 27, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [a2eed27aed](https://linux-hardware.org/?probe=a2eed27aed) | Dec 27, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [f022aa3706](https://linux-hardware.org/?probe=f022aa3706) | Dec 27, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [d02d1bb775](https://linux-hardware.org/?probe=d02d1bb775) | Dec 27, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [252503762f](https://linux-hardware.org/?probe=252503762f) | Dec 27, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [5be0d36fa8](https://linux-hardware.org/?probe=5be0d36fa8) | Dec 27, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [8262ba8f4a](https://linux-hardware.org/?probe=8262ba8f4a) | Dec 27, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [a940c31cf7](https://linux-hardware.org/?probe=a940c31cf7) | Dec 27, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [86bd37c584](https://linux-hardware.org/?probe=86bd37c584) | Dec 27, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [eb08ea9851](https://linux-hardware.org/?probe=eb08ea9851) | Dec 27, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [359493a8bf](https://linux-hardware.org/?probe=359493a8bf) | Dec 27, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [64e387d031](https://linux-hardware.org/?probe=64e387d031) | Dec 27, 2021 |
| Lenovo        | ThinkPad X220 4291W99       | Notebook    | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Lenovo        | ThinkPad T450 20BUS09X01    | Notebook    | [acce80e775](https://linux-hardware.org/?probe=acce80e775) | Dec 26, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [2151771a0d](https://linux-hardware.org/?probe=2151771a0d) | Dec 26, 2021 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [e3a3030886](https://linux-hardware.org/?probe=e3a3030886) | Dec 26, 2021 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [c7612aac66](https://linux-hardware.org/?probe=c7612aac66) | Dec 26, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [2c33c2931e](https://linux-hardware.org/?probe=2c33c2931e) | Dec 26, 2021 |
| Toshiba       | Satellite L775D             | Notebook    | [1ad6310748](https://linux-hardware.org/?probe=1ad6310748) | Dec 26, 2021 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [73d605f4e5](https://linux-hardware.org/?probe=73d605f4e5) | Dec 26, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [0477f867f5](https://linux-hardware.org/?probe=0477f867f5) | Dec 25, 2021 |
| JGINYUE       | X99-D8 Server V1.0          | Desktop     | [d1548e5cd1](https://linux-hardware.org/?probe=d1548e5cd1) | Dec 25, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [7bd51b12d6](https://linux-hardware.org/?probe=7bd51b12d6) | Dec 25, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [0929a4f988](https://linux-hardware.org/?probe=0929a4f988) | Dec 25, 2021 |
| Dell          | 07T4MC A09                  | Desktop     | [68af9c7556](https://linux-hardware.org/?probe=68af9c7556) | Dec 25, 2021 |
| HUAWEI        | HKD-WXX                     | Notebook    | [9e77c08b95](https://linux-hardware.org/?probe=9e77c08b95) | Dec 24, 2021 |
| ASUSTek       | X542UA                      | Notebook    | [c103fc5e33](https://linux-hardware.org/?probe=c103fc5e33) | Dec 24, 2021 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [7d0eeda884](https://linux-hardware.org/?probe=7d0eeda884) | Dec 24, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [ea7511ce8d](https://linux-hardware.org/?probe=ea7511ce8d) | Dec 24, 2021 |
| Toshiba       | Satellite E205              | Notebook    | [92431da366](https://linux-hardware.org/?probe=92431da366) | Dec 24, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [fa1d026542](https://linux-hardware.org/?probe=fa1d026542) | Dec 23, 2021 |
| AZW           | Gemini X45                  | Desktop     | [84dd0d27a1](https://linux-hardware.org/?probe=84dd0d27a1) | Dec 23, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [1dbb28ea7e](https://linux-hardware.org/?probe=1dbb28ea7e) | Dec 23, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [d14dc298c0](https://linux-hardware.org/?probe=d14dc298c0) | Dec 23, 2021 |
| MSI           | 870S-C45                    | Desktop     | [ac4454681e](https://linux-hardware.org/?probe=ac4454681e) | Dec 23, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3c497749b6](https://linux-hardware.org/?probe=3c497749b6) | Dec 23, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b097a62c18](https://linux-hardware.org/?probe=b097a62c18) | Dec 22, 2021 |
| Framework     | Laptop                      | Notebook    | [eac24b722b](https://linux-hardware.org/?probe=eac24b722b) | Dec 22, 2021 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [5fa9087a0f](https://linux-hardware.org/?probe=5fa9087a0f) | Dec 22, 2021 |
| HP            | G61                         | Notebook    | [d3f48fd2b2](https://linux-hardware.org/?probe=d3f48fd2b2) | Dec 22, 2021 |
| MSI           | X299 RAIDER                 | Desktop     | [305fffd6f2](https://linux-hardware.org/?probe=305fffd6f2) | Dec 22, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [302a05ab29](https://linux-hardware.org/?probe=302a05ab29) | Dec 22, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [1fe380a7d3](https://linux-hardware.org/?probe=1fe380a7d3) | Dec 22, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [ba81e8114e](https://linux-hardware.org/?probe=ba81e8114e) | Dec 22, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [c56f06be0f](https://linux-hardware.org/?probe=c56f06be0f) | Dec 22, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [11c6b9c8f3](https://linux-hardware.org/?probe=11c6b9c8f3) | Dec 22, 2021 |
| Advent        | Tacto Purple                | Notebook    | [ac9fd78933](https://linux-hardware.org/?probe=ac9fd78933) | Dec 22, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [60dacbeece](https://linux-hardware.org/?probe=60dacbeece) | Dec 22, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [72ba2d0d17](https://linux-hardware.org/?probe=72ba2d0d17) | Dec 22, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [0a0df8aeb4](https://linux-hardware.org/?probe=0a0df8aeb4) | Dec 22, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [d57782238c](https://linux-hardware.org/?probe=d57782238c) | Dec 22, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [00603cca0e](https://linux-hardware.org/?probe=00603cca0e) | Dec 22, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [6f933f3515](https://linux-hardware.org/?probe=6f933f3515) | Dec 21, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [0f65d7798c](https://linux-hardware.org/?probe=0f65d7798c) | Dec 21, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [d2e57452db](https://linux-hardware.org/?probe=d2e57452db) | Dec 21, 2021 |
| Acer          | Switch SW312-31             | Tablet      | [af71cff698](https://linux-hardware.org/?probe=af71cff698) | Dec 21, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [e6d6c1a347](https://linux-hardware.org/?probe=e6d6c1a347) | Dec 21, 2021 |
| Google        | Barla                       | Notebook    | [cfdb4935cd](https://linux-hardware.org/?probe=cfdb4935cd) | Dec 21, 2021 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [541618076f](https://linux-hardware.org/?probe=541618076f) | Dec 21, 2021 |
| Google        | Barla                       | Notebook    | [0629410759](https://linux-hardware.org/?probe=0629410759) | Dec 21, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [4bc10ff46d](https://linux-hardware.org/?probe=4bc10ff46d) | Dec 21, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [fcd4727186](https://linux-hardware.org/?probe=fcd4727186) | Dec 21, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [4c0f81d1b6](https://linux-hardware.org/?probe=4c0f81d1b6) | Dec 21, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [a48a676fb3](https://linux-hardware.org/?probe=a48a676fb3) | Dec 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [655f1beaae](https://linux-hardware.org/?probe=655f1beaae) | Dec 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [ba03646dce](https://linux-hardware.org/?probe=ba03646dce) | Dec 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [18425a0c0d](https://linux-hardware.org/?probe=18425a0c0d) | Dec 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [19ffe60b26](https://linux-hardware.org/?probe=19ffe60b26) | Dec 20, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [450425f52d](https://linux-hardware.org/?probe=450425f52d) | Dec 20, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [95261c40a2](https://linux-hardware.org/?probe=95261c40a2) | Dec 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [18fbcba790](https://linux-hardware.org/?probe=18fbcba790) | Dec 20, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [54cb3818f3](https://linux-hardware.org/?probe=54cb3818f3) | Dec 20, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [ce7e7de4b4](https://linux-hardware.org/?probe=ce7e7de4b4) | Dec 20, 2021 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [619d113667](https://linux-hardware.org/?probe=619d113667) | Dec 20, 2021 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [8032915451](https://linux-hardware.org/?probe=8032915451) | Dec 20, 2021 |
| ASUSTek       | 1015CX                      | Notebook    | [e146dc65ee](https://linux-hardware.org/?probe=e146dc65ee) | Dec 19, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [8962cfd1c6](https://linux-hardware.org/?probe=8962cfd1c6) | Dec 19, 2021 |
| Toshiba       | Satellite L755D             | Notebook    | [1f2f21825c](https://linux-hardware.org/?probe=1f2f21825c) | Dec 19, 2021 |
| Dell          | Inspiron N4050              | Notebook    | [069b0b5d94](https://linux-hardware.org/?probe=069b0b5d94) | Dec 19, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [aa65cbb14e](https://linux-hardware.org/?probe=aa65cbb14e) | Dec 19, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [e94f13d236](https://linux-hardware.org/?probe=e94f13d236) | Dec 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [398e67d90d](https://linux-hardware.org/?probe=398e67d90d) | Dec 19, 2021 |
| CompuLab      | fitlet2                     | Mini pc     | [1c6c1f4c45](https://linux-hardware.org/?probe=1c6c1f4c45) | Dec 19, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [ded54cb08c](https://linux-hardware.org/?probe=ded54cb08c) | Dec 19, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [627db696e0](https://linux-hardware.org/?probe=627db696e0) | Dec 18, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [dd7447cb0e](https://linux-hardware.org/?probe=dd7447cb0e) | Dec 18, 2021 |
| TYAN Compu... | S7002                       | Server      | [7636863c25](https://linux-hardware.org/?probe=7636863c25) | Dec 18, 2021 |
| TYAN Compu... | S7002                       | Server      | [8cf4b6b014](https://linux-hardware.org/?probe=8cf4b6b014) | Dec 18, 2021 |
| Lenovo        | ThinkPad T450 20BV000EUS    | Notebook    | [cb3d066fe3](https://linux-hardware.org/?probe=cb3d066fe3) | Dec 17, 2021 |
| Acer          | EG43M                       | Desktop     | [6f5d9e50df](https://linux-hardware.org/?probe=6f5d9e50df) | Dec 17, 2021 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [1e938fa2cb](https://linux-hardware.org/?probe=1e938fa2cb) | Dec 17, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [52f6aa4a91](https://linux-hardware.org/?probe=52f6aa4a91) | Dec 17, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [17e733167d](https://linux-hardware.org/?probe=17e733167d) | Dec 17, 2021 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [28d02842a6](https://linux-hardware.org/?probe=28d02842a6) | Dec 17, 2021 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [dd2a38b869](https://linux-hardware.org/?probe=dd2a38b869) | Dec 17, 2021 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [218235b0b1](https://linux-hardware.org/?probe=218235b0b1) | Dec 17, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [080e441056](https://linux-hardware.org/?probe=080e441056) | Dec 17, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [0470e28c02](https://linux-hardware.org/?probe=0470e28c02) | Dec 17, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [7fdeb45dde](https://linux-hardware.org/?probe=7fdeb45dde) | Dec 17, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [8ba18843cb](https://linux-hardware.org/?probe=8ba18843cb) | Dec 17, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [526e490544](https://linux-hardware.org/?probe=526e490544) | Dec 17, 2021 |
| HP            | ZBook 15u G6                | Notebook    | [78134b6880](https://linux-hardware.org/?probe=78134b6880) | Dec 17, 2021 |
| HP            | ZBook 15u G6                | Notebook    | [5a2146eb12](https://linux-hardware.org/?probe=5a2146eb12) | Dec 17, 2021 |
| Dell          | 07T4MC A05                  | Desktop     | [c54a28e0a8](https://linux-hardware.org/?probe=c54a28e0a8) | Dec 16, 2021 |
| Lenovo        | ThinkPad T590 20N4001NUS    | Notebook    | [7328745d31](https://linux-hardware.org/?probe=7328745d31) | Dec 16, 2021 |
| Xunlong       | Orange Pi PC                | Soc         | [e112a02e93](https://linux-hardware.org/?probe=e112a02e93) | Dec 16, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [e498196491](https://linux-hardware.org/?probe=e498196491) | Dec 16, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [a77249c08b](https://linux-hardware.org/?probe=a77249c08b) | Dec 16, 2021 |
| Gigabyte      | H410M S2H V3                | Desktop     | [afff6656ae](https://linux-hardware.org/?probe=afff6656ae) | Dec 16, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [0a7ab91f41](https://linux-hardware.org/?probe=0a7ab91f41) | Dec 16, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [ab117d0139](https://linux-hardware.org/?probe=ab117d0139) | Dec 16, 2021 |
| Maibenben     | E5100                       | Notebook    | [862244e859](https://linux-hardware.org/?probe=862244e859) | Dec 16, 2021 |
| Maibenben     | E5100                       | Notebook    | [cb5e47da58](https://linux-hardware.org/?probe=cb5e47da58) | Dec 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7d95335599](https://linux-hardware.org/?probe=7d95335599) | Dec 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [81c5e26bcf](https://linux-hardware.org/?probe=81c5e26bcf) | Dec 16, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [811e5bd5fb](https://linux-hardware.org/?probe=811e5bd5fb) | Dec 15, 2021 |
| Toshiba       | Satellite L775D             | Notebook    | [6f85a331cc](https://linux-hardware.org/?probe=6f85a331cc) | Dec 15, 2021 |
| HP            | 18E7                        | Desktop     | [c600f1f2bb](https://linux-hardware.org/?probe=c600f1f2bb) | Dec 15, 2021 |
| HP            | Notebook                    | Notebook    | [28a73cd53a](https://linux-hardware.org/?probe=28a73cd53a) | Dec 15, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [14467dd4b9](https://linux-hardware.org/?probe=14467dd4b9) | Dec 15, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [8b1901d7dc](https://linux-hardware.org/?probe=8b1901d7dc) | Dec 15, 2021 |
| ASUSTek       | Q170M2                      | Desktop     | [83811b886e](https://linux-hardware.org/?probe=83811b886e) | Dec 15, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [466da9344c](https://linux-hardware.org/?probe=466da9344c) | Dec 15, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [86eb1ce765](https://linux-hardware.org/?probe=86eb1ce765) | Dec 15, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [603a6f5087](https://linux-hardware.org/?probe=603a6f5087) | Dec 15, 2021 |
| Unknown       | CN700-8237                  | Desktop     | [c55be123a1](https://linux-hardware.org/?probe=c55be123a1) | Dec 15, 2021 |
| HONOR         | HLYL-WXX9                   | Notebook    | [0b6a9394b4](https://linux-hardware.org/?probe=0b6a9394b4) | Dec 15, 2021 |
| CSL-Comput... | R Evolve C14i               | Notebook    | [63c7f1d48e](https://linux-hardware.org/?probe=63c7f1d48e) | Dec 14, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [6a1aefdd40](https://linux-hardware.org/?probe=6a1aefdd40) | Dec 14, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [4f0b004478](https://linux-hardware.org/?probe=4f0b004478) | Dec 14, 2021 |
| ASUSTek       | X756UQ                      | Notebook    | [04d25be08d](https://linux-hardware.org/?probe=04d25be08d) | Dec 13, 2021 |
| ASUSTek       | X756UQ                      | Notebook    | [21aac3ed33](https://linux-hardware.org/?probe=21aac3ed33) | Dec 13, 2021 |
| Intel         | Eaglelake Fab D             | Desktop     | [354a223fbd](https://linux-hardware.org/?probe=354a223fbd) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [bf19b30902](https://linux-hardware.org/?probe=bf19b30902) | Dec 13, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [1a1ad9435a](https://linux-hardware.org/?probe=1a1ad9435a) | Dec 13, 2021 |
| HP            | 09F8h                       | Desktop     | [c70b669376](https://linux-hardware.org/?probe=c70b669376) | Dec 13, 2021 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [73ba7a03d3](https://linux-hardware.org/?probe=73ba7a03d3) | Dec 13, 2021 |
| ASUSTek       | X542UA                      | Notebook    | [920ca90cbe](https://linux-hardware.org/?probe=920ca90cbe) | Dec 13, 2021 |
| Huanan        | X58 V1.0                    | Desktop     | [6cb5c8da29](https://linux-hardware.org/?probe=6cb5c8da29) | Dec 12, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [bd72de2067](https://linux-hardware.org/?probe=bd72de2067) | Dec 12, 2021 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [51dfe24c10](https://linux-hardware.org/?probe=51dfe24c10) | Dec 12, 2021 |
| Dell          | Precision M6500             | Notebook    | [5b825d4133](https://linux-hardware.org/?probe=5b825d4133) | Dec 11, 2021 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [3faa0a2aad](https://linux-hardware.org/?probe=3faa0a2aad) | Dec 11, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [d5ec843ea7](https://linux-hardware.org/?probe=d5ec843ea7) | Dec 11, 2021 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [03ba9fdf17](https://linux-hardware.org/?probe=03ba9fdf17) | Dec 11, 2021 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [f2bfaaf185](https://linux-hardware.org/?probe=f2bfaaf185) | Dec 11, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [8c952bfc3d](https://linux-hardware.org/?probe=8c952bfc3d) | Dec 11, 2021 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [7d2780ae1a](https://linux-hardware.org/?probe=7d2780ae1a) | Dec 11, 2021 |
| HP            | EliteBook 2540p (VB841AV... | Notebook    | [c0406366e7](https://linux-hardware.org/?probe=c0406366e7) | Dec 10, 2021 |
| HP            | 09F8h                       | Desktop     | [b01b09b7a4](https://linux-hardware.org/?probe=b01b09b7a4) | Dec 10, 2021 |
| Lenovo        | ThinkPad P51s 20HB000URT    | Notebook    | [e4f3353735](https://linux-hardware.org/?probe=e4f3353735) | Dec 10, 2021 |
| ASUSTek       | X542UA                      | Notebook    | [e463e37acd](https://linux-hardware.org/?probe=e463e37acd) | Dec 10, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [7319c92561](https://linux-hardware.org/?probe=7319c92561) | Dec 10, 2021 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [f53267338f](https://linux-hardware.org/?probe=f53267338f) | Dec 10, 2021 |
| Packard Be... | EasyNote TM85               | Notebook    | [6a064fb13c](https://linux-hardware.org/?probe=6a064fb13c) | Dec 10, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [a46a3aab04](https://linux-hardware.org/?probe=a46a3aab04) | Dec 10, 2021 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [3b7e64aebf](https://linux-hardware.org/?probe=3b7e64aebf) | Dec 10, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [3cd23b929b](https://linux-hardware.org/?probe=3cd23b929b) | Dec 10, 2021 |
| Dell          | Precision M6500             | Notebook    | [eff4bd68bc](https://linux-hardware.org/?probe=eff4bd68bc) | Dec 10, 2021 |
| IBM           | ThinkPad T43 2668BU7        | Notebook    | [30bc16722a](https://linux-hardware.org/?probe=30bc16722a) | Dec 10, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d0f4c6c32f](https://linux-hardware.org/?probe=d0f4c6c32f) | Dec 09, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [c7c63c686c](https://linux-hardware.org/?probe=c7c63c686c) | Dec 09, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [877095541e](https://linux-hardware.org/?probe=877095541e) | Dec 09, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b38577891e](https://linux-hardware.org/?probe=b38577891e) | Dec 09, 2021 |
| Lenovo        | G585 2181                   | Notebook    | [392cee4b42](https://linux-hardware.org/?probe=392cee4b42) | Dec 09, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [d1d8529d39](https://linux-hardware.org/?probe=d1d8529d39) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f9ada169fd](https://linux-hardware.org/?probe=f9ada169fd) | Dec 09, 2021 |
| HP            | 3048h                       | Desktop     | [b583a7dd31](https://linux-hardware.org/?probe=b583a7dd31) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d39826b60](https://linux-hardware.org/?probe=7d39826b60) | Dec 09, 2021 |
| Dell          | 081N4V A02                  | Server      | [b689a1c943](https://linux-hardware.org/?probe=b689a1c943) | Dec 09, 2021 |
| Dell          | Latitude 5500               | Notebook    | [d293fa8753](https://linux-hardware.org/?probe=d293fa8753) | Dec 09, 2021 |
| Dell          | Latitude 5500               | Notebook    | [a2b09ae92d](https://linux-hardware.org/?probe=a2b09ae92d) | Dec 09, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [1cea605cac](https://linux-hardware.org/?probe=1cea605cac) | Dec 08, 2021 |
| Dell          | 0WG864                      | Desktop     | [59d9c69b35](https://linux-hardware.org/?probe=59d9c69b35) | Dec 08, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [6eab211fad](https://linux-hardware.org/?probe=6eab211fad) | Dec 08, 2021 |
| ECS           | G31T-M9                     | Desktop     | [ec3bb13ae2](https://linux-hardware.org/?probe=ec3bb13ae2) | Dec 08, 2021 |
| HP            | 09F8h                       | Desktop     | [fe41d0247b](https://linux-hardware.org/?probe=fe41d0247b) | Dec 08, 2021 |
| Lenovo        | ThinkPad W520 4284D47       | Notebook    | [a48239fba8](https://linux-hardware.org/?probe=a48239fba8) | Dec 08, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [c72fc0c384](https://linux-hardware.org/?probe=c72fc0c384) | Dec 08, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [fbc33ca9af](https://linux-hardware.org/?probe=fbc33ca9af) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [610d56a10a](https://linux-hardware.org/?probe=610d56a10a) | Dec 08, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [0a1d0c4e9b](https://linux-hardware.org/?probe=0a1d0c4e9b) | Dec 07, 2021 |
| Google        | Enguarde                    | Notebook    | [75bc922bae](https://linux-hardware.org/?probe=75bc922bae) | Dec 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [dde283bed5](https://linux-hardware.org/?probe=dde283bed5) | Dec 07, 2021 |
| Lenovo        | G585 2181                   | Notebook    | [9f1eb2ede7](https://linux-hardware.org/?probe=9f1eb2ede7) | Dec 07, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [4f0e1458f2](https://linux-hardware.org/?probe=4f0e1458f2) | Dec 07, 2021 |
| Dell          | Latitude 7490               | Notebook    | [187ce36374](https://linux-hardware.org/?probe=187ce36374) | Dec 07, 2021 |
| Lenovo        | G585 2181                   | Notebook    | [c03b3fab75](https://linux-hardware.org/?probe=c03b3fab75) | Dec 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4173a9406a](https://linux-hardware.org/?probe=4173a9406a) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [45c6fce683](https://linux-hardware.org/?probe=45c6fce683) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [b630c2b983](https://linux-hardware.org/?probe=b630c2b983) | Dec 07, 2021 |
| HP            | Laptop 15                   | Notebook    | [da76eec83a](https://linux-hardware.org/?probe=da76eec83a) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [0a6e6fb2e6](https://linux-hardware.org/?probe=0a6e6fb2e6) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [f2a731f5bc](https://linux-hardware.org/?probe=f2a731f5bc) | Dec 07, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c2e3c75ed0](https://linux-hardware.org/?probe=c2e3c75ed0) | Dec 07, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [d7c59ade1e](https://linux-hardware.org/?probe=d7c59ade1e) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [438e75161a](https://linux-hardware.org/?probe=438e75161a) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [8e20af97d9](https://linux-hardware.org/?probe=8e20af97d9) | Dec 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [830882c4e6](https://linux-hardware.org/?probe=830882c4e6) | Dec 07, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [2df4a34321](https://linux-hardware.org/?probe=2df4a34321) | Dec 07, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [c448dd4b0b](https://linux-hardware.org/?probe=c448dd4b0b) | Dec 07, 2021 |
| Acer          | Aspire 5741G                | Notebook    | [885dd449b6](https://linux-hardware.org/?probe=885dd449b6) | Dec 07, 2021 |
| Google        | Enguarde                    | Notebook    | [310a80f4c5](https://linux-hardware.org/?probe=310a80f4c5) | Dec 06, 2021 |
| HP            | EliteBook x360 1030 G8 N... | Convertible | [7ffe6f1ac8](https://linux-hardware.org/?probe=7ffe6f1ac8) | Dec 06, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [caaaef312c](https://linux-hardware.org/?probe=caaaef312c) | Dec 06, 2021 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b3f7681477](https://linux-hardware.org/?probe=b3f7681477) | Dec 06, 2021 |
| Unknown       | Unknown                     | Tablet      | [8bc0024182](https://linux-hardware.org/?probe=8bc0024182) | Dec 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [ee3ed8982f](https://linux-hardware.org/?probe=ee3ed8982f) | Dec 06, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [0f3fd91a00](https://linux-hardware.org/?probe=0f3fd91a00) | Dec 06, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [f67e3e407c](https://linux-hardware.org/?probe=f67e3e407c) | Dec 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [be3e1f65e6](https://linux-hardware.org/?probe=be3e1f65e6) | Dec 06, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [8a01b0cd81](https://linux-hardware.org/?probe=8a01b0cd81) | Dec 06, 2021 |
| Gigabyte      | P55-USB3                    | Desktop     | [6cbec7b450](https://linux-hardware.org/?probe=6cbec7b450) | Dec 06, 2021 |
| Supermicro    | X10DRL-i                    | Server      | [e7819a0518](https://linux-hardware.org/?probe=e7819a0518) | Dec 06, 2021 |
| Dell          | Inspiron 5580               | Notebook    | [29d56d5a5e](https://linux-hardware.org/?probe=29d56d5a5e) | Dec 06, 2021 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [8287f923da](https://linux-hardware.org/?probe=8287f923da) | Dec 06, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [7f5adb4cb3](https://linux-hardware.org/?probe=7f5adb4cb3) | Dec 06, 2021 |
| Fujitsu       | D3446-S1 S26361-D3446-S1    | Desktop     | [077673c895](https://linux-hardware.org/?probe=077673c895) | Dec 05, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [d78c027940](https://linux-hardware.org/?probe=d78c027940) | Dec 05, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [2694c27280](https://linux-hardware.org/?probe=2694c27280) | Dec 05, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [4a20a593d0](https://linux-hardware.org/?probe=4a20a593d0) | Dec 05, 2021 |
| sunxi         | FriendlyARM NanoPi NEO      | Soc         | [031d844c3a](https://linux-hardware.org/?probe=031d844c3a) | Dec 05, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [a859413f86](https://linux-hardware.org/?probe=a859413f86) | Dec 05, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [a6e257304d](https://linux-hardware.org/?probe=a6e257304d) | Dec 05, 2021 |
| ASRockRack    | C3558D4I-4L                 | Desktop     | [d563eb82ae](https://linux-hardware.org/?probe=d563eb82ae) | Dec 04, 2021 |
| Lenovo        | ThinkPad T450 20BUS46900    | Notebook    | [980d2b1409](https://linux-hardware.org/?probe=980d2b1409) | Dec 04, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [97aec623b3](https://linux-hardware.org/?probe=97aec623b3) | Dec 04, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [25ca2e2c75](https://linux-hardware.org/?probe=25ca2e2c75) | Dec 04, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | Desktop     | [0784c5596b](https://linux-hardware.org/?probe=0784c5596b) | Dec 04, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [5f7a6857d1](https://linux-hardware.org/?probe=5f7a6857d1) | Dec 04, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [cdd02a2ffa](https://linux-hardware.org/?probe=cdd02a2ffa) | Dec 04, 2021 |
| Lenovo        | ThinkCentre A58e 0841A2U    | Desktop     | [d8d9d0cf7a](https://linux-hardware.org/?probe=d8d9d0cf7a) | Dec 04, 2021 |
| Dell          | 0VHRW1 A03                  | Desktop     | [ebfaaee6ef](https://linux-hardware.org/?probe=ebfaaee6ef) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410 2522Y15       | Notebook    | [8b9bc362b3](https://linux-hardware.org/?probe=8b9bc362b3) | Dec 04, 2021 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [d1843d03ba](https://linux-hardware.org/?probe=d1843d03ba) | Dec 04, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [a94e228ed4](https://linux-hardware.org/?probe=a94e228ed4) | Dec 03, 2021 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [ec05196354](https://linux-hardware.org/?probe=ec05196354) | Dec 03, 2021 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [d6c8bae58f](https://linux-hardware.org/?probe=d6c8bae58f) | Dec 03, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [4029822099](https://linux-hardware.org/?probe=4029822099) | Dec 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1adcfe3e5e](https://linux-hardware.org/?probe=1adcfe3e5e) | Dec 03, 2021 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [0ae648efae](https://linux-hardware.org/?probe=0ae648efae) | Dec 03, 2021 |
| Dell          | Latitude E6400              | Notebook    | [b8e56749b8](https://linux-hardware.org/?probe=b8e56749b8) | Dec 03, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b7a0fe35eb](https://linux-hardware.org/?probe=b7a0fe35eb) | Dec 03, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | Notebook    | [0da495ab3b](https://linux-hardware.org/?probe=0da495ab3b) | Dec 02, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [d75361564f](https://linux-hardware.org/?probe=d75361564f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [0e099c0bdd](https://linux-hardware.org/?probe=0e099c0bdd) | Dec 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [f102e6537d](https://linux-hardware.org/?probe=f102e6537d) | Dec 02, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [039bbca776](https://linux-hardware.org/?probe=039bbca776) | Dec 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [92c4d0059f](https://linux-hardware.org/?probe=92c4d0059f) | Dec 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [42575594c3](https://linux-hardware.org/?probe=42575594c3) | Dec 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4459608572](https://linux-hardware.org/?probe=4459608572) | Dec 02, 2021 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [6432830846](https://linux-hardware.org/?probe=6432830846) | Dec 02, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [37d28d8425](https://linux-hardware.org/?probe=37d28d8425) | Dec 02, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [31b2f0fc9a](https://linux-hardware.org/?probe=31b2f0fc9a) | Dec 02, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | Desktop     | [50a026d588](https://linux-hardware.org/?probe=50a026d588) | Dec 02, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [e6f6525ecd](https://linux-hardware.org/?probe=e6f6525ecd) | Dec 01, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [477e2949fe](https://linux-hardware.org/?probe=477e2949fe) | Dec 01, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [bdd0f25735](https://linux-hardware.org/?probe=bdd0f25735) | Dec 01, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [a193d7ccae](https://linux-hardware.org/?probe=a193d7ccae) | Dec 01, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [933ffd0145](https://linux-hardware.org/?probe=933ffd0145) | Dec 01, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [8289b6f249](https://linux-hardware.org/?probe=8289b6f249) | Dec 01, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [b12e3b7ad0](https://linux-hardware.org/?probe=b12e3b7ad0) | Dec 01, 2021 |
| Lenovo        | ThinkPad T410 2522Y15       | Notebook    | [c57f5d2453](https://linux-hardware.org/?probe=c57f5d2453) | Nov 30, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [4ae50a5146](https://linux-hardware.org/?probe=4ae50a5146) | Nov 30, 2021 |
| Tablet        | 8                           | Notebook    | [36164d26c8](https://linux-hardware.org/?probe=36164d26c8) | Nov 30, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f547e66aff](https://linux-hardware.org/?probe=f547e66aff) | Nov 30, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [915ab51632](https://linux-hardware.org/?probe=915ab51632) | Nov 30, 2021 |
| Celestica     | D4040                       | Notebook    | [109f886f1d](https://linux-hardware.org/?probe=109f886f1d) | Nov 30, 2021 |
| ECS           | G31T-M9                     | Desktop     | [54a394adb1](https://linux-hardware.org/?probe=54a394adb1) | Nov 30, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [22d048c93d](https://linux-hardware.org/?probe=22d048c93d) | Nov 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [3395298923](https://linux-hardware.org/?probe=3395298923) | Nov 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [427480c39a](https://linux-hardware.org/?probe=427480c39a) | Nov 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [f92e797aea](https://linux-hardware.org/?probe=f92e797aea) | Nov 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [bfe63a9c60](https://linux-hardware.org/?probe=bfe63a9c60) | Nov 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [dc21f1680a](https://linux-hardware.org/?probe=dc21f1680a) | Nov 30, 2021 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [1bc2e1056c](https://linux-hardware.org/?probe=1bc2e1056c) | Nov 30, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [81e0d1f84c](https://linux-hardware.org/?probe=81e0d1f84c) | Nov 30, 2021 |
| ECS           | B85H3-M4R                   | Desktop     | [fb85d32462](https://linux-hardware.org/?probe=fb85d32462) | Nov 30, 2021 |
| Supermicro    | X11SCL-F                    | Server      | [34b9b698cd](https://linux-hardware.org/?probe=34b9b698cd) | Nov 30, 2021 |
| Dell          | 0VHRW1 A03                  | Desktop     | [19fd4c2057](https://linux-hardware.org/?probe=19fd4c2057) | Nov 30, 2021 |
| Acer          | Swift SF314-56              | Notebook    | [6c60445d08](https://linux-hardware.org/?probe=6c60445d08) | Nov 29, 2021 |
| Panasonic     | CF-54-1                     | Notebook    | [8f2224d84d](https://linux-hardware.org/?probe=8f2224d84d) | Nov 29, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | Desktop     | [7493408721](https://linux-hardware.org/?probe=7493408721) | Nov 29, 2021 |
| Dell          | 0VHRW1 A03                  | Desktop     | [637bba1c58](https://linux-hardware.org/?probe=637bba1c58) | Nov 29, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [a07a68ba43](https://linux-hardware.org/?probe=a07a68ba43) | Nov 29, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [e643c12a79](https://linux-hardware.org/?probe=e643c12a79) | Nov 29, 2021 |
| Foxconn       | H61MXL-K                    | Desktop     | [271670f758](https://linux-hardware.org/?probe=271670f758) | Nov 29, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [12b910d10b](https://linux-hardware.org/?probe=12b910d10b) | Nov 29, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [592b77242d](https://linux-hardware.org/?probe=592b77242d) | Nov 29, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [d5aae23742](https://linux-hardware.org/?probe=d5aae23742) | Nov 29, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [593d86b4d2](https://linux-hardware.org/?probe=593d86b4d2) | Nov 29, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [70954353f3](https://linux-hardware.org/?probe=70954353f3) | Nov 29, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [cca6a99387](https://linux-hardware.org/?probe=cca6a99387) | Nov 29, 2021 |
| MSI           | MS-N014                     | Notebook    | [f98cf89699](https://linux-hardware.org/?probe=f98cf89699) | Nov 29, 2021 |
| MSI           | MS-N014                     | Notebook    | [a90d5979be](https://linux-hardware.org/?probe=a90d5979be) | Nov 29, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [4f34b82346](https://linux-hardware.org/?probe=4f34b82346) | Nov 29, 2021 |
| Lenovo        | ThinkCentre A58e 0841A2U    | Desktop     | [123b071e52](https://linux-hardware.org/?probe=123b071e52) | Nov 29, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [2360f50367](https://linux-hardware.org/?probe=2360f50367) | Nov 29, 2021 |
| IBM           | ThinkPad T43 2668BU7        | Notebook    | [594b3488d6](https://linux-hardware.org/?probe=594b3488d6) | Nov 29, 2021 |
| ASRock        | G31M-S                      | Desktop     | [48ad510e26](https://linux-hardware.org/?probe=48ad510e26) | Nov 29, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [48d70742bb](https://linux-hardware.org/?probe=48d70742bb) | Nov 28, 2021 |
| ASRock        | G31M-S                      | Desktop     | [5f87bf3b90](https://linux-hardware.org/?probe=5f87bf3b90) | Nov 28, 2021 |
| Lenovo        | ThinkCentre M58p 6137BG5    | Desktop     | [f5f0997eca](https://linux-hardware.org/?probe=f5f0997eca) | Nov 28, 2021 |
| Acer          | Aspire 5610                 | Notebook    | [853aee060d](https://linux-hardware.org/?probe=853aee060d) | Nov 28, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [af5f461e74](https://linux-hardware.org/?probe=af5f461e74) | Nov 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4fa0a94620](https://linux-hardware.org/?probe=4fa0a94620) | Nov 28, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [6e1ecfa79e](https://linux-hardware.org/?probe=6e1ecfa79e) | Nov 28, 2021 |
| Intel         | X79G V2.x                   | Desktop     | [a04ccc0b10](https://linux-hardware.org/?probe=a04ccc0b10) | Nov 28, 2021 |
| Dell          | Vostro 3400                 | Notebook    | [d8946eaf3c](https://linux-hardware.org/?probe=d8946eaf3c) | Nov 28, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [d031ddee30](https://linux-hardware.org/?probe=d031ddee30) | Nov 28, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [555032936f](https://linux-hardware.org/?probe=555032936f) | Nov 28, 2021 |
| Acer          | TravelMate P214-52          | Notebook    | [bea2d6c254](https://linux-hardware.org/?probe=bea2d6c254) | Nov 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [3b55838cb6](https://linux-hardware.org/?probe=3b55838cb6) | Nov 27, 2021 |
| HP            | ZBook Studio G4             | Notebook    | [eb3da87330](https://linux-hardware.org/?probe=eb3da87330) | Nov 27, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e81d5a7298](https://linux-hardware.org/?probe=e81d5a7298) | Nov 27, 2021 |
| HP            | Pavilion dv6                | Notebook    | [02376f3101](https://linux-hardware.org/?probe=02376f3101) | Nov 27, 2021 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [50608748f0](https://linux-hardware.org/?probe=50608748f0) | Nov 27, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c6289480ca](https://linux-hardware.org/?probe=c6289480ca) | Nov 27, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [7984741863](https://linux-hardware.org/?probe=7984741863) | Nov 27, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [46a63cf369](https://linux-hardware.org/?probe=46a63cf369) | Nov 27, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [d8109a1195](https://linux-hardware.org/?probe=d8109a1195) | Nov 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [16be623c84](https://linux-hardware.org/?probe=16be623c84) | Nov 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [f08b8241b0](https://linux-hardware.org/?probe=f08b8241b0) | Nov 26, 2021 |
| HP            | ProBook 635 Aero G7 Note... | Notebook    | [bef33ffa93](https://linux-hardware.org/?probe=bef33ffa93) | Nov 26, 2021 |
| PCWare        | IPMH61R3                    | Desktop     | [9d69282e7a](https://linux-hardware.org/?probe=9d69282e7a) | Nov 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [ec7596ddfa](https://linux-hardware.org/?probe=ec7596ddfa) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [921493c5de](https://linux-hardware.org/?probe=921493c5de) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [372ecff863](https://linux-hardware.org/?probe=372ecff863) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [c2e9888262](https://linux-hardware.org/?probe=c2e9888262) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [3210708d2b](https://linux-hardware.org/?probe=3210708d2b) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [af6a185f57](https://linux-hardware.org/?probe=af6a185f57) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [e993ed0b0f](https://linux-hardware.org/?probe=e993ed0b0f) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [47f77bc2b9](https://linux-hardware.org/?probe=47f77bc2b9) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [d6812643cf](https://linux-hardware.org/?probe=d6812643cf) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [96558bdade](https://linux-hardware.org/?probe=96558bdade) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [535b83e569](https://linux-hardware.org/?probe=535b83e569) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [699315cb63](https://linux-hardware.org/?probe=699315cb63) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [d792605965](https://linux-hardware.org/?probe=d792605965) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [30a358041c](https://linux-hardware.org/?probe=30a358041c) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [64dcda1fa3](https://linux-hardware.org/?probe=64dcda1fa3) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [e2b310a3f2](https://linux-hardware.org/?probe=e2b310a3f2) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [f5d837e417](https://linux-hardware.org/?probe=f5d837e417) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [c525b3d17b](https://linux-hardware.org/?probe=c525b3d17b) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [d500b1e29f](https://linux-hardware.org/?probe=d500b1e29f) | Nov 26, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [04c11c5b5f](https://linux-hardware.org/?probe=04c11c5b5f) | Nov 26, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [5e57df0c06](https://linux-hardware.org/?probe=5e57df0c06) | Nov 26, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [474255a405](https://linux-hardware.org/?probe=474255a405) | Nov 26, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [7569ef6338](https://linux-hardware.org/?probe=7569ef6338) | Nov 26, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [00f73ea6c2](https://linux-hardware.org/?probe=00f73ea6c2) | Nov 26, 2021 |
| Intel         | S1200SP H57532-210          | Server      | [9ca6bb3f17](https://linux-hardware.org/?probe=9ca6bb3f17) | Nov 26, 2021 |
| Intel         | S1200SP H57532-210          | Server      | [b15baad163](https://linux-hardware.org/?probe=b15baad163) | Nov 26, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [caf3c5f8f2](https://linux-hardware.org/?probe=caf3c5f8f2) | Nov 25, 2021 |
| AXDIA Inte... | Wintab 10                   | Notebook    | [9db3481488](https://linux-hardware.org/?probe=9db3481488) | Nov 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [5f3cfbdd91](https://linux-hardware.org/?probe=5f3cfbdd91) | Nov 25, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [88af62cd43](https://linux-hardware.org/?probe=88af62cd43) | Nov 25, 2021 |
| HP            | Presario CQ56               | Notebook    | [a9203b72bb](https://linux-hardware.org/?probe=a9203b72bb) | Nov 25, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [8fad7fe107](https://linux-hardware.org/?probe=8fad7fe107) | Nov 25, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [cd148d2d45](https://linux-hardware.org/?probe=cd148d2d45) | Nov 25, 2021 |
| Compal        | QAL51                       | Notebook    | [d7e7cedc5c](https://linux-hardware.org/?probe=d7e7cedc5c) | Nov 25, 2021 |
| Acer          | EG43M                       | Desktop     | [328e16606e](https://linux-hardware.org/?probe=328e16606e) | Nov 25, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [ea4dbbbf15](https://linux-hardware.org/?probe=ea4dbbbf15) | Nov 25, 2021 |
| A10 Networ... | TH4435                      | Desktop     | [46267dfe86](https://linux-hardware.org/?probe=46267dfe86) | Nov 25, 2021 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [90d994abcd](https://linux-hardware.org/?probe=90d994abcd) | Nov 24, 2021 |
| AXDIA Inte... | Wintab 10                   | Notebook    | [04f77c36b0](https://linux-hardware.org/?probe=04f77c36b0) | Nov 24, 2021 |
| Lenovo        | ThinkPad W540 20BG0042FR    | Notebook    | [02b8528d76](https://linux-hardware.org/?probe=02b8528d76) | Nov 24, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [b9c8e3ec8f](https://linux-hardware.org/?probe=b9c8e3ec8f) | Nov 24, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [31c566f4ac](https://linux-hardware.org/?probe=31c566f4ac) | Nov 24, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [9b0bfd9c19](https://linux-hardware.org/?probe=9b0bfd9c19) | Nov 24, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [8e627fb473](https://linux-hardware.org/?probe=8e627fb473) | Nov 24, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [ef54a544fc](https://linux-hardware.org/?probe=ef54a544fc) | Nov 24, 2021 |
| Dell          | Latitude 7480               | Notebook    | [75937fb177](https://linux-hardware.org/?probe=75937fb177) | Nov 24, 2021 |
| Dell          | Latitude 7480               | Notebook    | [019d4a4604](https://linux-hardware.org/?probe=019d4a4604) | Nov 24, 2021 |
| HP            | Presario CQ56               | Notebook    | [b50968704d](https://linux-hardware.org/?probe=b50968704d) | Nov 24, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [6d61fe8c06](https://linux-hardware.org/?probe=6d61fe8c06) | Nov 24, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [d13563df7f](https://linux-hardware.org/?probe=d13563df7f) | Nov 24, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [4e07143fc9](https://linux-hardware.org/?probe=4e07143fc9) | Nov 23, 2021 |
| Acer          | Aspire 5610                 | Notebook    | [8fa3c5f33c](https://linux-hardware.org/?probe=8fa3c5f33c) | Nov 23, 2021 |
| MSI           | MS-7030                     | Desktop     | [dc2b0207b3](https://linux-hardware.org/?probe=dc2b0207b3) | Nov 23, 2021 |
| Dell          | Inspiron 11-3168            | Notebook    | [b7b3b8ef38](https://linux-hardware.org/?probe=b7b3b8ef38) | Nov 23, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [b01da81848](https://linux-hardware.org/?probe=b01da81848) | Nov 23, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [bbb91b2f5f](https://linux-hardware.org/?probe=bbb91b2f5f) | Nov 23, 2021 |
| Lenovo        | 36EB SDK0R32862 WIN 3258... | Desktop     | [ab35c5c468](https://linux-hardware.org/?probe=ab35c5c468) | Nov 23, 2021 |
| ASUSTek       | P5K/EPU                     | Desktop     | [4b0e227f6f](https://linux-hardware.org/?probe=4b0e227f6f) | Nov 22, 2021 |
| ASUSTek       | P5K/EPU                     | Desktop     | [44ed7fe92e](https://linux-hardware.org/?probe=44ed7fe92e) | Nov 22, 2021 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [d279b3f946](https://linux-hardware.org/?probe=d279b3f946) | Nov 22, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [4f0dc5afbf](https://linux-hardware.org/?probe=4f0dc5afbf) | Nov 22, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6c9a78f854](https://linux-hardware.org/?probe=6c9a78f854) | Nov 22, 2021 |
| Lenovo        | ThinkPad X250 20CM004UGE    | Notebook    | [26bd0cd883](https://linux-hardware.org/?probe=26bd0cd883) | Nov 22, 2021 |
| Packard Be... | FMP55                       | Desktop     | [13e6b9ef4c](https://linux-hardware.org/?probe=13e6b9ef4c) | Nov 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d5a663555f](https://linux-hardware.org/?probe=d5a663555f) | Nov 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2b69fd787e](https://linux-hardware.org/?probe=2b69fd787e) | Nov 21, 2021 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [2e109e9059](https://linux-hardware.org/?probe=2e109e9059) | Nov 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [dc4a084ef6](https://linux-hardware.org/?probe=dc4a084ef6) | Nov 21, 2021 |
| Dell          | Latitude E6330              | Notebook    | [843131a308](https://linux-hardware.org/?probe=843131a308) | Nov 21, 2021 |
| Gigabyte      | P55-UD3                     | Desktop     | [6fbfc34971](https://linux-hardware.org/?probe=6fbfc34971) | Nov 21, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [b151b05476](https://linux-hardware.org/?probe=b151b05476) | Nov 21, 2021 |
| Intel         | powered classmate PC        | Tablet      | [aea7e0243a](https://linux-hardware.org/?probe=aea7e0243a) | Nov 21, 2021 |
| HP            | ENVY m7                     | Notebook    | [97fae6afa0](https://linux-hardware.org/?probe=97fae6afa0) | Nov 21, 2021 |
| Intel         | powered classmate PC        | Tablet      | [444812feb3](https://linux-hardware.org/?probe=444812feb3) | Nov 21, 2021 |
| Lenovo        | ThinkPad T480s 20L8S31E0... | Notebook    | [5015d88753](https://linux-hardware.org/?probe=5015d88753) | Nov 21, 2021 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [f66705283e](https://linux-hardware.org/?probe=f66705283e) | Nov 21, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [9a66408c2e](https://linux-hardware.org/?probe=9a66408c2e) | Nov 21, 2021 |
| IBM           | ThinkPad T43 2668BU7        | Notebook    | [12017f88c5](https://linux-hardware.org/?probe=12017f88c5) | Nov 21, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [c357da262c](https://linux-hardware.org/?probe=c357da262c) | Nov 20, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [09039121c2](https://linux-hardware.org/?probe=09039121c2) | Nov 20, 2021 |
| Sony          | VGN-NS30E_S                 | Notebook    | [a36535818d](https://linux-hardware.org/?probe=a36535818d) | Nov 20, 2021 |
| IBM           | ThinkPad T43 26686ZG        | Notebook    | [837bd8895e](https://linux-hardware.org/?probe=837bd8895e) | Nov 20, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [2c0279ade5](https://linux-hardware.org/?probe=2c0279ade5) | Nov 20, 2021 |
| Dell          | Precision 5520              | Notebook    | [0ca00fe3e9](https://linux-hardware.org/?probe=0ca00fe3e9) | Nov 20, 2021 |
| IBM           | ThinkPad T43 26688AG        | Notebook    | [f0e357cf85](https://linux-hardware.org/?probe=f0e357cf85) | Nov 20, 2021 |
| IBM           | ThinkPad T43 26688AG        | Notebook    | [26b7c2dab9](https://linux-hardware.org/?probe=26b7c2dab9) | Nov 20, 2021 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [d8f2089df2](https://linux-hardware.org/?probe=d8f2089df2) | Nov 20, 2021 |
| ASUSTek       | P8H61-I                     | Desktop     | [bb8c25b299](https://linux-hardware.org/?probe=bb8c25b299) | Nov 20, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | Notebook    | [065770fe24](https://linux-hardware.org/?probe=065770fe24) | Nov 19, 2021 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [016b9e8521](https://linux-hardware.org/?probe=016b9e8521) | Nov 19, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [32a54aa260](https://linux-hardware.org/?probe=32a54aa260) | Nov 19, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | Notebook    | [d68e11bb6f](https://linux-hardware.org/?probe=d68e11bb6f) | Nov 19, 2021 |
| Acer          | TravelMate 4220             | Notebook    | [154009efd2](https://linux-hardware.org/?probe=154009efd2) | Nov 19, 2021 |
| Acer          | TravelMate 4220             | Notebook    | [b437a6cdee](https://linux-hardware.org/?probe=b437a6cdee) | Nov 19, 2021 |
| HP            | ProBook 4530s               | Notebook    | [de11d1bb53](https://linux-hardware.org/?probe=de11d1bb53) | Nov 19, 2021 |
| Compal        | QAL51                       | Notebook    | [9922147938](https://linux-hardware.org/?probe=9922147938) | Nov 19, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [fa7d35906a](https://linux-hardware.org/?probe=fa7d35906a) | Nov 19, 2021 |
| ECS           | H81H3-M3                    | Desktop     | [019a8bc90a](https://linux-hardware.org/?probe=019a8bc90a) | Nov 19, 2021 |
| Shuttle       | FS81                        | Desktop     | [ac6138c9d7](https://linux-hardware.org/?probe=ac6138c9d7) | Nov 19, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [15916ce478](https://linux-hardware.org/?probe=15916ce478) | Nov 19, 2021 |
| Datto         | SSD                         | Desktop     | [ab058b04af](https://linux-hardware.org/?probe=ab058b04af) | Nov 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [4a24670ff6](https://linux-hardware.org/?probe=4a24670ff6) | Nov 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [86767db090](https://linux-hardware.org/?probe=86767db090) | Nov 19, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [1604bcdd0d](https://linux-hardware.org/?probe=1604bcdd0d) | Nov 19, 2021 |
| Shuttle       | FS81                        | Desktop     | [d889090212](https://linux-hardware.org/?probe=d889090212) | Nov 18, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [b97a7f7688](https://linux-hardware.org/?probe=b97a7f7688) | Nov 18, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [5edbaed472](https://linux-hardware.org/?probe=5edbaed472) | Nov 18, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [f3bd0e1fa6](https://linux-hardware.org/?probe=f3bd0e1fa6) | Nov 18, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [2b3ac03929](https://linux-hardware.org/?probe=2b3ac03929) | Nov 18, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [736657999a](https://linux-hardware.org/?probe=736657999a) | Nov 18, 2021 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7f0992aae9](https://linux-hardware.org/?probe=7f0992aae9) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [6da7601574](https://linux-hardware.org/?probe=6da7601574) | Nov 18, 2021 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [11abeb4513](https://linux-hardware.org/?probe=11abeb4513) | Nov 18, 2021 |
| ASRock        | X570 PG Velocita            | Desktop     | [98a028263b](https://linux-hardware.org/?probe=98a028263b) | Nov 18, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [c7762271da](https://linux-hardware.org/?probe=c7762271da) | Nov 18, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [bc9da19934](https://linux-hardware.org/?probe=bc9da19934) | Nov 18, 2021 |
| Google        | Stout                       | Notebook    | [2201cceced](https://linux-hardware.org/?probe=2201cceced) | Nov 17, 2021 |
| Lenovo        | ThinkPad 20J10046US         | Notebook    | [1597db42c1](https://linux-hardware.org/?probe=1597db42c1) | Nov 17, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [a1c2626420](https://linux-hardware.org/?probe=a1c2626420) | Nov 17, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [3025843274](https://linux-hardware.org/?probe=3025843274) | Nov 17, 2021 |
| Sony          | SVE1712E1RB                 | Notebook    | [4be9dde00d](https://linux-hardware.org/?probe=4be9dde00d) | Nov 17, 2021 |
| Gigabyte      | B550M S2H                   | Desktop     | [b242137617](https://linux-hardware.org/?probe=b242137617) | Nov 17, 2021 |
| Dell          | System XPS L502X            | Notebook    | [8d247d71f2](https://linux-hardware.org/?probe=8d247d71f2) | Nov 17, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [66fd774069](https://linux-hardware.org/?probe=66fd774069) | Nov 17, 2021 |
| Gigabyte      | Z170M-D3H DDR3-CF           | Desktop     | [729de8e04c](https://linux-hardware.org/?probe=729de8e04c) | Nov 17, 2021 |
| Sony          | SVE1712E1RB                 | Notebook    | [2416868324](https://linux-hardware.org/?probe=2416868324) | Nov 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [c0cb61a9fc](https://linux-hardware.org/?probe=c0cb61a9fc) | Nov 17, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [52a4eecaa3](https://linux-hardware.org/?probe=52a4eecaa3) | Nov 17, 2021 |
| ASUSTek       | 1015PE                      | Notebook    | [9735619dd6](https://linux-hardware.org/?probe=9735619dd6) | Nov 17, 2021 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [e8f5452c3a](https://linux-hardware.org/?probe=e8f5452c3a) | Nov 16, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | Notebook    | [72ac73a219](https://linux-hardware.org/?probe=72ac73a219) | Nov 16, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [706587b8f3](https://linux-hardware.org/?probe=706587b8f3) | Nov 16, 2021 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [4288c7ddbf](https://linux-hardware.org/?probe=4288c7ddbf) | Nov 16, 2021 |
| Lenovo        | ThinkPad T430 2347G61       | Notebook    | [12ee1cee2b](https://linux-hardware.org/?probe=12ee1cee2b) | Nov 16, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [f65310e00b](https://linux-hardware.org/?probe=f65310e00b) | Nov 16, 2021 |
| Acer          | TravelMate 8371             | Notebook    | [312ed52708](https://linux-hardware.org/?probe=312ed52708) | Nov 16, 2021 |
| Acer          | TravelMate 8371             | Notebook    | [78b196a98c](https://linux-hardware.org/?probe=78b196a98c) | Nov 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6051ccd1cc](https://linux-hardware.org/?probe=6051ccd1cc) | Nov 16, 2021 |
| Lenovo        | 3168 NOK                    | Desktop     | [28a3c13b73](https://linux-hardware.org/?probe=28a3c13b73) | Nov 16, 2021 |
| HP            | 3397                        | Desktop     | [be170ea3c0](https://linux-hardware.org/?probe=be170ea3c0) | Nov 15, 2021 |
| HP            | 3397                        | Desktop     | [33500b1506](https://linux-hardware.org/?probe=33500b1506) | Nov 15, 2021 |
| MSI           | GE60 2PL                    | Notebook    | [7287f7a1ae](https://linux-hardware.org/?probe=7287f7a1ae) | Nov 15, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [fc04d52b16](https://linux-hardware.org/?probe=fc04d52b16) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [74ce7d98c6](https://linux-hardware.org/?probe=74ce7d98c6) | Nov 15, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [2a2d9fc8f1](https://linux-hardware.org/?probe=2a2d9fc8f1) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [180bbba91c](https://linux-hardware.org/?probe=180bbba91c) | Nov 15, 2021 |
| Acer          | Aspire A517-51G             | Notebook    | [a580b8a73f](https://linux-hardware.org/?probe=a580b8a73f) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [52eef25506](https://linux-hardware.org/?probe=52eef25506) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [7252f23e5f](https://linux-hardware.org/?probe=7252f23e5f) | Nov 15, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [8c23aaf339](https://linux-hardware.org/?probe=8c23aaf339) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [1a20afde4b](https://linux-hardware.org/?probe=1a20afde4b) | Nov 15, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [d1e04ead11](https://linux-hardware.org/?probe=d1e04ead11) | Nov 15, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [67a90a8265](https://linux-hardware.org/?probe=67a90a8265) | Nov 14, 2021 |
| Lenovo        | ThinkPad E450 20DCS01J00    | Notebook    | [ce5eb49ae7](https://linux-hardware.org/?probe=ce5eb49ae7) | Nov 14, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [1c302d3d99](https://linux-hardware.org/?probe=1c302d3d99) | Nov 14, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [5574978db2](https://linux-hardware.org/?probe=5574978db2) | Nov 14, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [8406ced05c](https://linux-hardware.org/?probe=8406ced05c) | Nov 14, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [f035cd561e](https://linux-hardware.org/?probe=f035cd561e) | Nov 14, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [4d129ac049](https://linux-hardware.org/?probe=4d129ac049) | Nov 14, 2021 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [b19a68b774](https://linux-hardware.org/?probe=b19a68b774) | Nov 13, 2021 |
| Dell          | Latitude E6330              | Notebook    | [a03858cc87](https://linux-hardware.org/?probe=a03858cc87) | Nov 13, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [b362dd3f20](https://linux-hardware.org/?probe=b362dd3f20) | Nov 13, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [c1a976d644](https://linux-hardware.org/?probe=c1a976d644) | Nov 13, 2021 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [6c1708134f](https://linux-hardware.org/?probe=6c1708134f) | Nov 13, 2021 |
| Datto         | SSD                         | Desktop     | [49001aa936](https://linux-hardware.org/?probe=49001aa936) | Nov 13, 2021 |
| Lenovo        | ThinkPad X201 3626GG3       | Notebook    | [78619d2639](https://linux-hardware.org/?probe=78619d2639) | Nov 12, 2021 |
| Compal        | QAL51                       | Notebook    | [431d587da7](https://linux-hardware.org/?probe=431d587da7) | Nov 12, 2021 |
| HP            | 821D                        | Desktop     | [4227f76ab4](https://linux-hardware.org/?probe=4227f76ab4) | Nov 12, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [56dd47d979](https://linux-hardware.org/?probe=56dd47d979) | Nov 12, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [768c187f40](https://linux-hardware.org/?probe=768c187f40) | Nov 12, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [2574fae667](https://linux-hardware.org/?probe=2574fae667) | Nov 12, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [924d961707](https://linux-hardware.org/?probe=924d961707) | Nov 12, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [be11374c4b](https://linux-hardware.org/?probe=be11374c4b) | Nov 12, 2021 |
| Intel         | ChiefRiver                  | Desktop     | [4490bddeed](https://linux-hardware.org/?probe=4490bddeed) | Nov 12, 2021 |
| Lenovo        | ThinkPad L13 Yoga 20R500... | Convertible | [7bf691f7c7](https://linux-hardware.org/?probe=7bf691f7c7) | Nov 12, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [a119684a3e](https://linux-hardware.org/?probe=a119684a3e) | Nov 11, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [3215112be3](https://linux-hardware.org/?probe=3215112be3) | Nov 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [79e78d0c90](https://linux-hardware.org/?probe=79e78d0c90) | Nov 11, 2021 |
| MSI           | G41M-P28                    | Desktop     | [2586b84980](https://linux-hardware.org/?probe=2586b84980) | Nov 11, 2021 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [edb83bd184](https://linux-hardware.org/?probe=edb83bd184) | Nov 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [00e34bc46e](https://linux-hardware.org/?probe=00e34bc46e) | Nov 11, 2021 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [55b02178a3](https://linux-hardware.org/?probe=55b02178a3) | Nov 11, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [867e0388ae](https://linux-hardware.org/?probe=867e0388ae) | Nov 11, 2021 |
| Intel         | H55                         | Desktop     | [7fc34476de](https://linux-hardware.org/?probe=7fc34476de) | Nov 10, 2021 |
| Intel         | H55                         | Desktop     | [0364a82ed9](https://linux-hardware.org/?probe=0364a82ed9) | Nov 10, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [1bdbee29eb](https://linux-hardware.org/?probe=1bdbee29eb) | Nov 10, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [e4961a7cfc](https://linux-hardware.org/?probe=e4961a7cfc) | Nov 10, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [20898da2a5](https://linux-hardware.org/?probe=20898da2a5) | Nov 10, 2021 |
| Gigabyte      | Q170TN-T20                  | Desktop     | [28a80f5aa9](https://linux-hardware.org/?probe=28a80f5aa9) | Nov 10, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [e41c568cf3](https://linux-hardware.org/?probe=e41c568cf3) | Nov 10, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | Notebook    | [f9f140b132](https://linux-hardware.org/?probe=f9f140b132) | Nov 10, 2021 |
| Gigabyte      | Q170TN-T20                  | Desktop     | [8fce727047](https://linux-hardware.org/?probe=8fce727047) | Nov 10, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | Notebook    | [258574fc87](https://linux-hardware.org/?probe=258574fc87) | Nov 10, 2021 |
| ASUSTek       | 1011PX                      | Notebook    | [2d96503388](https://linux-hardware.org/?probe=2d96503388) | Nov 10, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [689a981891](https://linux-hardware.org/?probe=689a981891) | Nov 10, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [d7635d487f](https://linux-hardware.org/?probe=d7635d487f) | Nov 10, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [2acec5d06c](https://linux-hardware.org/?probe=2acec5d06c) | Nov 10, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [6e415a1506](https://linux-hardware.org/?probe=6e415a1506) | Nov 10, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [e67fcb38c6](https://linux-hardware.org/?probe=e67fcb38c6) | Nov 10, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [ed50a31f1a](https://linux-hardware.org/?probe=ed50a31f1a) | Nov 10, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [188d241df7](https://linux-hardware.org/?probe=188d241df7) | Nov 10, 2021 |
| Dell          | Inspiron 7472               | Notebook    | [2508fadf63](https://linux-hardware.org/?probe=2508fadf63) | Nov 10, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [7463b38c9c](https://linux-hardware.org/?probe=7463b38c9c) | Nov 10, 2021 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [4427467cb5](https://linux-hardware.org/?probe=4427467cb5) | Nov 10, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [5b3b6a8e90](https://linux-hardware.org/?probe=5b3b6a8e90) | Nov 10, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [606263f5e9](https://linux-hardware.org/?probe=606263f5e9) | Nov 10, 2021 |
| MSI           | GS65 Stealth 9SE            | Notebook    | [bef876576b](https://linux-hardware.org/?probe=bef876576b) | Nov 09, 2021 |
| ASRockRack    | EPYCD8-2T                   | Desktop     | [0f80e3768e](https://linux-hardware.org/?probe=0f80e3768e) | Nov 09, 2021 |
| Lenovo        | 14w 81MQ00AHAR              | Notebook    | [17785cda04](https://linux-hardware.org/?probe=17785cda04) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [107c6e9840](https://linux-hardware.org/?probe=107c6e9840) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [006454048e](https://linux-hardware.org/?probe=006454048e) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [466c86045e](https://linux-hardware.org/?probe=466c86045e) | Nov 09, 2021 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [9b7fba5c1a](https://linux-hardware.org/?probe=9b7fba5c1a) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e9818fe37e](https://linux-hardware.org/?probe=e9818fe37e) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [eeb1d38579](https://linux-hardware.org/?probe=eeb1d38579) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [deab410735](https://linux-hardware.org/?probe=deab410735) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [1ab4a1aebc](https://linux-hardware.org/?probe=1ab4a1aebc) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6d39af3a58](https://linux-hardware.org/?probe=6d39af3a58) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e8bbdb29d1](https://linux-hardware.org/?probe=e8bbdb29d1) | Nov 09, 2021 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [71a272c9a3](https://linux-hardware.org/?probe=71a272c9a3) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [ccd62944b4](https://linux-hardware.org/?probe=ccd62944b4) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [125724b6a0](https://linux-hardware.org/?probe=125724b6a0) | Nov 09, 2021 |
| MSI           | H81M-P33                    | Desktop     | [091f7e066b](https://linux-hardware.org/?probe=091f7e066b) | Nov 09, 2021 |
| HP            | 8433 11                     | Desktop     | [737e98b3e9](https://linux-hardware.org/?probe=737e98b3e9) | Nov 09, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [8378557eb5](https://linux-hardware.org/?probe=8378557eb5) | Nov 09, 2021 |
| HP            | 8433 11                     | Desktop     | [ad7a603e07](https://linux-hardware.org/?probe=ad7a603e07) | Nov 09, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [f27ce2e38a](https://linux-hardware.org/?probe=f27ce2e38a) | Nov 09, 2021 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | Desktop     | [a7ba011636](https://linux-hardware.org/?probe=a7ba011636) | Nov 09, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [66654fe284](https://linux-hardware.org/?probe=66654fe284) | Nov 09, 2021 |
| HP            | ProBook 645 G2              | Notebook    | [beada5c26b](https://linux-hardware.org/?probe=beada5c26b) | Nov 09, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9dc24197f3](https://linux-hardware.org/?probe=9dc24197f3) | Nov 09, 2021 |
| HP            | ProBook 645 G2              | Notebook    | [64b38adff8](https://linux-hardware.org/?probe=64b38adff8) | Nov 09, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [72f1028535](https://linux-hardware.org/?probe=72f1028535) | Nov 09, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [2e75320963](https://linux-hardware.org/?probe=2e75320963) | Nov 09, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [e43d36b3cf](https://linux-hardware.org/?probe=e43d36b3cf) | Nov 09, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [31ffcb5018](https://linux-hardware.org/?probe=31ffcb5018) | Nov 09, 2021 |
| Acer          | Spin SP313-51N              | Convertible | [3e9090f557](https://linux-hardware.org/?probe=3e9090f557) | Nov 09, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [f59ff36e50](https://linux-hardware.org/?probe=f59ff36e50) | Nov 09, 2021 |
| Dell          | Latitude E5570              | Notebook    | [b2398623fc](https://linux-hardware.org/?probe=b2398623fc) | Nov 09, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [8efc2ed27a](https://linux-hardware.org/?probe=8efc2ed27a) | Nov 08, 2021 |
| Lenovo        | ThinkPad E450 20DCS01J00    | Notebook    | [ee83aa5751](https://linux-hardware.org/?probe=ee83aa5751) | Nov 08, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [b247ac9f61](https://linux-hardware.org/?probe=b247ac9f61) | Nov 08, 2021 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [ca32959cf7](https://linux-hardware.org/?probe=ca32959cf7) | Nov 08, 2021 |
| MSI           | 990XA-GD55                  | Desktop     | [461ac78561](https://linux-hardware.org/?probe=461ac78561) | Nov 08, 2021 |
| MSI           | MS-7369                     | Desktop     | [670cc450d8](https://linux-hardware.org/?probe=670cc450d8) | Nov 08, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [c25ef7b482](https://linux-hardware.org/?probe=c25ef7b482) | Nov 08, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c7342485d4](https://linux-hardware.org/?probe=c7342485d4) | Nov 08, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [a2e80395f1](https://linux-hardware.org/?probe=a2e80395f1) | Nov 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [142203c854](https://linux-hardware.org/?probe=142203c854) | Nov 08, 2021 |
| Dell          | Precision M4800             | Notebook    | [30a32fb8df](https://linux-hardware.org/?probe=30a32fb8df) | Nov 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [e34b11f673](https://linux-hardware.org/?probe=e34b11f673) | Nov 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [87e5aa3c2c](https://linux-hardware.org/?probe=87e5aa3c2c) | Nov 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [58f187feb7](https://linux-hardware.org/?probe=58f187feb7) | Nov 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [2229fe93fb](https://linux-hardware.org/?probe=2229fe93fb) | Nov 08, 2021 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [c7b52e35cf](https://linux-hardware.org/?probe=c7b52e35cf) | Nov 08, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [4b834a3bff](https://linux-hardware.org/?probe=4b834a3bff) | Nov 07, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [8c6816916c](https://linux-hardware.org/?probe=8c6816916c) | Nov 07, 2021 |
| HP            | 3031h                       | Desktop     | [66af9f5944](https://linux-hardware.org/?probe=66af9f5944) | Nov 07, 2021 |
| Samsung       | 950QCG                      | Convertible | [1e901e419e](https://linux-hardware.org/?probe=1e901e419e) | Nov 07, 2021 |
| Unknown       | Amlogic Meson GXL (S905X... | Soc         | [c12f791f17](https://linux-hardware.org/?probe=c12f791f17) | Nov 07, 2021 |
| Dell          | 0WWJRX A01                  | Desktop     | [4fa10e9d4b](https://linux-hardware.org/?probe=4fa10e9d4b) | Nov 06, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [9c14e4d461](https://linux-hardware.org/?probe=9c14e4d461) | Nov 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [cafb5e6e80](https://linux-hardware.org/?probe=cafb5e6e80) | Nov 05, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [bfe89af8ab](https://linux-hardware.org/?probe=bfe89af8ab) | Nov 04, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [28366fcde0](https://linux-hardware.org/?probe=28366fcde0) | Nov 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [31f91364c1](https://linux-hardware.org/?probe=31f91364c1) | Nov 04, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [8d24d56a03](https://linux-hardware.org/?probe=8d24d56a03) | Nov 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [cd9efb14b2](https://linux-hardware.org/?probe=cd9efb14b2) | Nov 04, 2021 |
| Aquarius      | NS585                       | Notebook    | [8d7faba1cb](https://linux-hardware.org/?probe=8d7faba1cb) | Nov 04, 2021 |
| Aquarius      | NS585                       | Notebook    | [99b57214d1](https://linux-hardware.org/?probe=99b57214d1) | Nov 04, 2021 |
| Dell          | Latitude 5511               | Notebook    | [6dca737664](https://linux-hardware.org/?probe=6dca737664) | Nov 04, 2021 |
| Dell          | Latitude 5511               | Notebook    | [f2ef4f8e35](https://linux-hardware.org/?probe=f2ef4f8e35) | Nov 04, 2021 |
| Lenovo        | ThinkPad T460s 20FACTO1W... | Notebook    | [1d6e8a6521](https://linux-hardware.org/?probe=1d6e8a6521) | Nov 04, 2021 |
| HP            | Pavilion dv4                | Notebook    | [7e9733638c](https://linux-hardware.org/?probe=7e9733638c) | Nov 04, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [a7629cdfd1](https://linux-hardware.org/?probe=a7629cdfd1) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480 20L50009MX    | Notebook    | [349faf5242](https://linux-hardware.org/?probe=349faf5242) | Nov 03, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [2e08c10fec](https://linux-hardware.org/?probe=2e08c10fec) | Nov 02, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [6eb01124a7](https://linux-hardware.org/?probe=6eb01124a7) | Nov 02, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1869db225e](https://linux-hardware.org/?probe=1869db225e) | Nov 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8b2a91de37](https://linux-hardware.org/?probe=8b2a91de37) | Nov 01, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [5de4d7d11a](https://linux-hardware.org/?probe=5de4d7d11a) | Nov 01, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3040be6e81](https://linux-hardware.org/?probe=3040be6e81) | Nov 01, 2021 |
| Dell          | 0WWJRX A01                  | Desktop     | [a03dcb58fb](https://linux-hardware.org/?probe=a03dcb58fb) | Nov 01, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a3fe4bd135](https://linux-hardware.org/?probe=a3fe4bd135) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d68eea1b12](https://linux-hardware.org/?probe=d68eea1b12) | Nov 01, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [8182230d1d](https://linux-hardware.org/?probe=8182230d1d) | Nov 01, 2021 |
| Ugoos         | UT2                         | Mini pc     | [3d5e473688](https://linux-hardware.org/?probe=3d5e473688) | Oct 31, 2021 |
| Rockchip      | Unknown                     | Soc         | [342ccd2ecf](https://linux-hardware.org/?probe=342ccd2ecf) | Oct 31, 2021 |
| Lenovo        | ThinkPad W530 244743G       | Notebook    | [69a252ccd6](https://linux-hardware.org/?probe=69a252ccd6) | Oct 31, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [e58d33df6b](https://linux-hardware.org/?probe=e58d33df6b) | Oct 31, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [70d528a8fc](https://linux-hardware.org/?probe=70d528a8fc) | Oct 31, 2021 |
| Unknown       | MT8117                      | Notebook    | [b579146661](https://linux-hardware.org/?probe=b579146661) | Oct 31, 2021 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [5adc857043](https://linux-hardware.org/?probe=5adc857043) | Oct 31, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [38b4ba227c](https://linux-hardware.org/?probe=38b4ba227c) | Oct 30, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [b6302b710d](https://linux-hardware.org/?probe=b6302b710d) | Oct 30, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [60f4ac8cc5](https://linux-hardware.org/?probe=60f4ac8cc5) | Oct 30, 2021 |
| Chuwi         | Hi8 Air                     | Tablet      | [a2b23f7796](https://linux-hardware.org/?probe=a2b23f7796) | Oct 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5be083edab](https://linux-hardware.org/?probe=5be083edab) | Oct 29, 2021 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [83857e3215](https://linux-hardware.org/?probe=83857e3215) | Oct 29, 2021 |
| Gigabyte      | P55M-UD2                    | Desktop     | [b14c0e8dd2](https://linux-hardware.org/?probe=b14c0e8dd2) | Oct 29, 2021 |
| HP            | 1998                        | Desktop     | [b9e492678d](https://linux-hardware.org/?probe=b9e492678d) | Oct 29, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [ce2c332b33](https://linux-hardware.org/?probe=ce2c332b33) | Oct 29, 2021 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [58dfae44e0](https://linux-hardware.org/?probe=58dfae44e0) | Oct 29, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [83a2d81e1c](https://linux-hardware.org/?probe=83a2d81e1c) | Oct 29, 2021 |
| Dell          | Latitude E7240              | Notebook    | [dbf0fd04c3](https://linux-hardware.org/?probe=dbf0fd04c3) | Oct 28, 2021 |
| AZW           | SEi                         | Mini pc     | [1155d58828](https://linux-hardware.org/?probe=1155d58828) | Oct 28, 2021 |
| Compal        | QAL51                       | Notebook    | [ffffaf4799](https://linux-hardware.org/?probe=ffffaf4799) | Oct 28, 2021 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [085ef9e58d](https://linux-hardware.org/?probe=085ef9e58d) | Oct 28, 2021 |
| HP            | 0AECh D                     | Desktop     | [15a01d5e13](https://linux-hardware.org/?probe=15a01d5e13) | Oct 28, 2021 |
| HP            | 3047h                       | Desktop     | [eedab3769c](https://linux-hardware.org/?probe=eedab3769c) | Oct 28, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [d85a5ada85](https://linux-hardware.org/?probe=d85a5ada85) | Oct 28, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [a7cc3183f2](https://linux-hardware.org/?probe=a7cc3183f2) | Oct 28, 2021 |
| HP            | Notebook                    | Notebook    | [0ba26ccc72](https://linux-hardware.org/?probe=0ba26ccc72) | Oct 28, 2021 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [6ad4929a33](https://linux-hardware.org/?probe=6ad4929a33) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| Intel         | D945GCCR AAD78647-300       | Desktop     | [d41d75c998](https://linux-hardware.org/?probe=d41d75c998) | Oct 28, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [369b39d1be](https://linux-hardware.org/?probe=369b39d1be) | Oct 28, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [5b7faf1cc6](https://linux-hardware.org/?probe=5b7faf1cc6) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [7c73c4e6f0](https://linux-hardware.org/?probe=7c73c4e6f0) | Oct 27, 2021 |
| ASUSTek       | M4A77T                      | Desktop     | [07942589ae](https://linux-hardware.org/?probe=07942589ae) | Oct 27, 2021 |
| Intel         | H55                         | Desktop     | [b32e64a698](https://linux-hardware.org/?probe=b32e64a698) | Oct 27, 2021 |
| HP            | Laptop 17-by1xxx            | Notebook    | [e6406f34f8](https://linux-hardware.org/?probe=e6406f34f8) | Oct 27, 2021 |
| Dell          | Latitude E6330              | Notebook    | [872cfff7da](https://linux-hardware.org/?probe=872cfff7da) | Oct 26, 2021 |
| Lenovo        | ThinkPad T540p 20BFS05B0... | Notebook    | [5026826dbe](https://linux-hardware.org/?probe=5026826dbe) | Oct 26, 2021 |
| Lenovo        | ThinkPad T540p 20BFS05B0... | Notebook    | [f644310091](https://linux-hardware.org/?probe=f644310091) | Oct 26, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [2f188b606a](https://linux-hardware.org/?probe=2f188b606a) | Oct 25, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b47e0921b6](https://linux-hardware.org/?probe=b47e0921b6) | Oct 25, 2021 |
| Dell          | Latitude E6330              | Notebook    | [c3e7f97c42](https://linux-hardware.org/?probe=c3e7f97c42) | Oct 25, 2021 |
| Dell          | Latitude E6330              | Notebook    | [0e88df3ae7](https://linux-hardware.org/?probe=0e88df3ae7) | Oct 25, 2021 |
| HP            | Pavilion g6                 | Notebook    | [2c2d7620f9](https://linux-hardware.org/?probe=2c2d7620f9) | Oct 25, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [3e6b56c5f9](https://linux-hardware.org/?probe=3e6b56c5f9) | Oct 25, 2021 |
| Acer          | AOA150                      | Notebook    | [1380638bb1](https://linux-hardware.org/?probe=1380638bb1) | Oct 25, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [88030b7fcb](https://linux-hardware.org/?probe=88030b7fcb) | Oct 25, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [ae0cd83502](https://linux-hardware.org/?probe=ae0cd83502) | Oct 25, 2021 |
| Dell          | Latitude E6540              | Notebook    | [df9262f810](https://linux-hardware.org/?probe=df9262f810) | Oct 25, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [487d0f0e12](https://linux-hardware.org/?probe=487d0f0e12) | Oct 24, 2021 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [fd2f79c5fc](https://linux-hardware.org/?probe=fd2f79c5fc) | Oct 24, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [1e4856a770](https://linux-hardware.org/?probe=1e4856a770) | Oct 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [be67e01a7d](https://linux-hardware.org/?probe=be67e01a7d) | Oct 24, 2021 |
| Dell          | 0MD99X A07                  | Server      | [246f93c093](https://linux-hardware.org/?probe=246f93c093) | Oct 24, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [09f6196e70](https://linux-hardware.org/?probe=09f6196e70) | Oct 23, 2021 |
| Dell          | Latitude E6330              | Notebook    | [e7a19ad923](https://linux-hardware.org/?probe=e7a19ad923) | Oct 23, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [6954277377](https://linux-hardware.org/?probe=6954277377) | Oct 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [7aac95cd60](https://linux-hardware.org/?probe=7aac95cd60) | Oct 23, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [c8f19e95d8](https://linux-hardware.org/?probe=c8f19e95d8) | Oct 23, 2021 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [7354eacfc5](https://linux-hardware.org/?probe=7354eacfc5) | Oct 23, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [117223995c](https://linux-hardware.org/?probe=117223995c) | Oct 23, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [e97646cc2e](https://linux-hardware.org/?probe=e97646cc2e) | Oct 23, 2021 |
| Jumper        | EZbook                      | Notebook    | [557738cd7d](https://linux-hardware.org/?probe=557738cd7d) | Oct 23, 2021 |
| HP            | EliteBook 840 Aero G8 No... | Notebook    | [713c29aa23](https://linux-hardware.org/?probe=713c29aa23) | Oct 22, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [bcc008e381](https://linux-hardware.org/?probe=bcc008e381) | Oct 22, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [55dcb690c5](https://linux-hardware.org/?probe=55dcb690c5) | Oct 22, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [08a5e38790](https://linux-hardware.org/?probe=08a5e38790) | Oct 22, 2021 |
| Dell          | Inspiron N4050              | Notebook    | [85a514f622](https://linux-hardware.org/?probe=85a514f622) | Oct 22, 2021 |
| LG Electro... | X120-L.C7L1A9               | Notebook    | [42b7007a7e](https://linux-hardware.org/?probe=42b7007a7e) | Oct 21, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [c7a2305704](https://linux-hardware.org/?probe=c7a2305704) | Oct 21, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [c36147b6a6](https://linux-hardware.org/?probe=c36147b6a6) | Oct 21, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [2815629b34](https://linux-hardware.org/?probe=2815629b34) | Oct 21, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [8d1ec3a3b6](https://linux-hardware.org/?probe=8d1ec3a3b6) | Oct 21, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [0c016119e3](https://linux-hardware.org/?probe=0c016119e3) | Oct 21, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [3cdf9d520e](https://linux-hardware.org/?probe=3cdf9d520e) | Oct 21, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [fe4c73ce24](https://linux-hardware.org/?probe=fe4c73ce24) | Oct 21, 2021 |
| Dell          | 02YRK5 A01                  | Desktop     | [d7c89a5f6a](https://linux-hardware.org/?probe=d7c89a5f6a) | Oct 21, 2021 |
| HP            | 250 G1                      | Notebook    | [b34fa14c55](https://linux-hardware.org/?probe=b34fa14c55) | Oct 21, 2021 |
| ASRock        | B365M Pro4                  | Desktop     | [ec939fb289](https://linux-hardware.org/?probe=ec939fb289) | Oct 20, 2021 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [7039c3e31f](https://linux-hardware.org/?probe=7039c3e31f) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [b5f8d33cc4](https://linux-hardware.org/?probe=b5f8d33cc4) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [920a47f107](https://linux-hardware.org/?probe=920a47f107) | Oct 20, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [e8b00fa29b](https://linux-hardware.org/?probe=e8b00fa29b) | Oct 20, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [cd4a22e83b](https://linux-hardware.org/?probe=cd4a22e83b) | Oct 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2c5f518cc8](https://linux-hardware.org/?probe=2c5f518cc8) | Oct 20, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4899fa0cab](https://linux-hardware.org/?probe=4899fa0cab) | Oct 19, 2021 |
| Digiboard     | MPxx                        | Desktop     | [138c2ef6fb](https://linux-hardware.org/?probe=138c2ef6fb) | Oct 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [0290c2ca6d](https://linux-hardware.org/?probe=0290c2ca6d) | Oct 19, 2021 |
| Lenovo        | ThinkPad 20J10046US         | Notebook    | [cad3a5eb69](https://linux-hardware.org/?probe=cad3a5eb69) | Oct 18, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | Notebook    | [ea23d24f90](https://linux-hardware.org/?probe=ea23d24f90) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [ea22908ff7](https://linux-hardware.org/?probe=ea22908ff7) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [daf0f8d357](https://linux-hardware.org/?probe=daf0f8d357) | Oct 18, 2021 |
| MSI           | GF75 Thin 9SC               | Notebook    | [1f4a66b99a](https://linux-hardware.org/?probe=1f4a66b99a) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [0f5ea2eb9a](https://linux-hardware.org/?probe=0f5ea2eb9a) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [08f117fdcb](https://linux-hardware.org/?probe=08f117fdcb) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [3921dda159](https://linux-hardware.org/?probe=3921dda159) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [22c808750d](https://linux-hardware.org/?probe=22c808750d) | Oct 18, 2021 |
| HP            | ProLiant DL360 Gen9         | Server      | [cfffe6aa63](https://linux-hardware.org/?probe=cfffe6aa63) | Oct 18, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [b5f275b4c4](https://linux-hardware.org/?probe=b5f275b4c4) | Oct 17, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [5c4edf2e8d](https://linux-hardware.org/?probe=5c4edf2e8d) | Oct 17, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [66d1015de7](https://linux-hardware.org/?probe=66d1015de7) | Oct 17, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [43bfef3bcd](https://linux-hardware.org/?probe=43bfef3bcd) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [1f4f861804](https://linux-hardware.org/?probe=1f4f861804) | Oct 17, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [d13426531e](https://linux-hardware.org/?probe=d13426531e) | Oct 17, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [c17c589af5](https://linux-hardware.org/?probe=c17c589af5) | Oct 17, 2021 |
| Supermicro    | M11SDV-8CT-LN4F             | Server      | [10f1608197](https://linux-hardware.org/?probe=10f1608197) | Oct 17, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [68ac15eeda](https://linux-hardware.org/?probe=68ac15eeda) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [69fc64df8b](https://linux-hardware.org/?probe=69fc64df8b) | Oct 16, 2021 |
| Lenovo        | S10-3                       | Notebook    | [acb07e4c72](https://linux-hardware.org/?probe=acb07e4c72) | Oct 16, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5e79417ff5](https://linux-hardware.org/?probe=5e79417ff5) | Oct 16, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [7735f49c62](https://linux-hardware.org/?probe=7735f49c62) | Oct 16, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [34fc60e37e](https://linux-hardware.org/?probe=34fc60e37e) | Oct 16, 2021 |
| Dell          | 0D6H9T A01                  | Desktop     | [795b03a6f8](https://linux-hardware.org/?probe=795b03a6f8) | Oct 16, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [b59ab42003](https://linux-hardware.org/?probe=b59ab42003) | Oct 16, 2021 |
| Acer          | TravelMate P215-53          | Notebook    | [3d398d4b58](https://linux-hardware.org/?probe=3d398d4b58) | Oct 16, 2021 |
| Dell          | Latitude 7410               | Convertible | [20fa4b73d7](https://linux-hardware.org/?probe=20fa4b73d7) | Oct 15, 2021 |
| Lenovo        | ThinkPad X60 17068GG        | Notebook    | [2f3b34aac4](https://linux-hardware.org/?probe=2f3b34aac4) | Oct 15, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [dc7e454319](https://linux-hardware.org/?probe=dc7e454319) | Oct 15, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [bf9482b190](https://linux-hardware.org/?probe=bf9482b190) | Oct 15, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [a7045defdf](https://linux-hardware.org/?probe=a7045defdf) | Oct 15, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [ff55772306](https://linux-hardware.org/?probe=ff55772306) | Oct 15, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [d54d095b0d](https://linux-hardware.org/?probe=d54d095b0d) | Oct 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [9005e4d86d](https://linux-hardware.org/?probe=9005e4d86d) | Oct 15, 2021 |
| HP            | 84FD 10                     | Desktop     | [fb32fc7215](https://linux-hardware.org/?probe=fb32fc7215) | Oct 14, 2021 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [3d41f5d139](https://linux-hardware.org/?probe=3d41f5d139) | Oct 14, 2021 |
| Lenovo        | ThinkPad 20J10046US         | Notebook    | [2d46a44cca](https://linux-hardware.org/?probe=2d46a44cca) | Oct 14, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [f78b91b7de](https://linux-hardware.org/?probe=f78b91b7de) | Oct 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [f8f343d12b](https://linux-hardware.org/?probe=f8f343d12b) | Oct 14, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [c3cdfe0336](https://linux-hardware.org/?probe=c3cdfe0336) | Oct 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [7345eddec4](https://linux-hardware.org/?probe=7345eddec4) | Oct 14, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [22a831db3d](https://linux-hardware.org/?probe=22a831db3d) | Oct 14, 2021 |
| Intel         | DP43BF AAE78171-301         | Desktop     | [42df25414b](https://linux-hardware.org/?probe=42df25414b) | Oct 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [d42e0a77d4](https://linux-hardware.org/?probe=d42e0a77d4) | Oct 14, 2021 |
| Intel         | DP43BF AAE78171-301         | Desktop     | [b08c85ef1a](https://linux-hardware.org/?probe=b08c85ef1a) | Oct 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [7b0dd9fe28](https://linux-hardware.org/?probe=7b0dd9fe28) | Oct 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [ea53e809fd](https://linux-hardware.org/?probe=ea53e809fd) | Oct 14, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [7555392d34](https://linux-hardware.org/?probe=7555392d34) | Oct 14, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [7facc39e0e](https://linux-hardware.org/?probe=7facc39e0e) | Oct 14, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [65477965f4](https://linux-hardware.org/?probe=65477965f4) | Oct 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [aaca557699](https://linux-hardware.org/?probe=aaca557699) | Oct 14, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [6847e8306e](https://linux-hardware.org/?probe=6847e8306e) | Oct 14, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [6bd5cc2d9b](https://linux-hardware.org/?probe=6bd5cc2d9b) | Oct 14, 2021 |
| Sony          | VAIO                        | Notebook    | [22a4b460cc](https://linux-hardware.org/?probe=22a4b460cc) | Oct 14, 2021 |
| Unknown       | Generic RK322x TV Box       | Mini pc     | [b1424d1c42](https://linux-hardware.org/?probe=b1424d1c42) | Oct 14, 2021 |
| Dell          | 0773VG A02                  | Desktop     | [ecd9b7c720](https://linux-hardware.org/?probe=ecd9b7c720) | Oct 14, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [2ae81cd94f](https://linux-hardware.org/?probe=2ae81cd94f) | Oct 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [000ac750e0](https://linux-hardware.org/?probe=000ac750e0) | Oct 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [69b1046c6e](https://linux-hardware.org/?probe=69b1046c6e) | Oct 13, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [0175c5181a](https://linux-hardware.org/?probe=0175c5181a) | Oct 13, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [cdb34ca184](https://linux-hardware.org/?probe=cdb34ca184) | Oct 13, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [923479d039](https://linux-hardware.org/?probe=923479d039) | Oct 13, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [82de48bc60](https://linux-hardware.org/?probe=82de48bc60) | Oct 13, 2021 |
| Pegatron      | IPXCR-VN1                   | Desktop     | [695f542c6c](https://linux-hardware.org/?probe=695f542c6c) | Oct 13, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e3a92a65f5](https://linux-hardware.org/?probe=e3a92a65f5) | Oct 13, 2021 |
| Unknown       | LakePort                    | Desktop     | [24159c8d9e](https://linux-hardware.org/?probe=24159c8d9e) | Oct 13, 2021 |
| ASUSTek       | TP201SA                     | Notebook    | [504956d2e9](https://linux-hardware.org/?probe=504956d2e9) | Oct 13, 2021 |
| ASUSTek       | UX303LAB                    | Notebook    | [97b9f51735](https://linux-hardware.org/?probe=97b9f51735) | Oct 13, 2021 |
| MSI           | GF75 Thin 9SC               | Notebook    | [db0ef927e0](https://linux-hardware.org/?probe=db0ef927e0) | Oct 13, 2021 |
| MSI           | GF75 Thin 9SC               | Notebook    | [be82875929](https://linux-hardware.org/?probe=be82875929) | Oct 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [f2690f5ec4](https://linux-hardware.org/?probe=f2690f5ec4) | Oct 13, 2021 |
| Lenovo        | SHARKBAY 0B98405 STD        | Desktop     | [6d09c42ade](https://linux-hardware.org/?probe=6d09c42ade) | Oct 12, 2021 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [ec7ba8e11a](https://linux-hardware.org/?probe=ec7ba8e11a) | Oct 12, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [34774c0428](https://linux-hardware.org/?probe=34774c0428) | Oct 12, 2021 |
| HP            | G62                         | Notebook    | [7873481ecb](https://linux-hardware.org/?probe=7873481ecb) | Oct 12, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [b01543c6b8](https://linux-hardware.org/?probe=b01543c6b8) | Oct 12, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [34fe4b38c7](https://linux-hardware.org/?probe=34fe4b38c7) | Oct 12, 2021 |
| MSI           | P43 Neo-F                   | Desktop     | [d79f0f85c1](https://linux-hardware.org/?probe=d79f0f85c1) | Oct 12, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [2a96c0566a](https://linux-hardware.org/?probe=2a96c0566a) | Oct 12, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [69938c221e](https://linux-hardware.org/?probe=69938c221e) | Oct 12, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [4e86b85a4d](https://linux-hardware.org/?probe=4e86b85a4d) | Oct 12, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [59f755658e](https://linux-hardware.org/?probe=59f755658e) | Oct 12, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [6476999787](https://linux-hardware.org/?probe=6476999787) | Oct 12, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [3638982195](https://linux-hardware.org/?probe=3638982195) | Oct 12, 2021 |
| Lenovo        | ThinkPad T520 4242W9B       | Notebook    | [3947636b4d](https://linux-hardware.org/?probe=3947636b4d) | Oct 12, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [e551d622a8](https://linux-hardware.org/?probe=e551d622a8) | Oct 11, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [8ab9e5cc4b](https://linux-hardware.org/?probe=8ab9e5cc4b) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [dce9cc60d3](https://linux-hardware.org/?probe=dce9cc60d3) | Oct 11, 2021 |
| Acer          | Veriton Z4710G              | All in one  | [d5825127bf](https://linux-hardware.org/?probe=d5825127bf) | Oct 11, 2021 |
| Sun Micros... | Ultra 27 52                 | Desktop     | [144b473603](https://linux-hardware.org/?probe=144b473603) | Oct 11, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [e776648230](https://linux-hardware.org/?probe=e776648230) | Oct 11, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [46f9cbae92](https://linux-hardware.org/?probe=46f9cbae92) | Oct 11, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c97f94ce2f](https://linux-hardware.org/?probe=c97f94ce2f) | Oct 10, 2021 |
| HP            | 1589                        | Desktop     | [bb8d8d60cf](https://linux-hardware.org/?probe=bb8d8d60cf) | Oct 10, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [598d90e6b6](https://linux-hardware.org/?probe=598d90e6b6) | Oct 10, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [2a83508f22](https://linux-hardware.org/?probe=2a83508f22) | Oct 10, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [f6a1aece80](https://linux-hardware.org/?probe=f6a1aece80) | Oct 10, 2021 |
| MSI           | B150M Night Elf             | Desktop     | [ed3f4e9937](https://linux-hardware.org/?probe=ed3f4e9937) | Oct 09, 2021 |
| HP            | TouchSmart tm2              | Notebook    | [4a04d297c6](https://linux-hardware.org/?probe=4a04d297c6) | Oct 09, 2021 |
| ASRock        | H110M-ITX/ac                | Desktop     | [261f3477ea](https://linux-hardware.org/?probe=261f3477ea) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [31ae42bc51](https://linux-hardware.org/?probe=31ae42bc51) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5b47e8efcb](https://linux-hardware.org/?probe=5b47e8efcb) | Oct 09, 2021 |
| ASRock        | B75 Pro3-M                  | Desktop     | [62522e187a](https://linux-hardware.org/?probe=62522e187a) | Oct 09, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e709e42b6e](https://linux-hardware.org/?probe=e709e42b6e) | Oct 09, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [3ab285ffb2](https://linux-hardware.org/?probe=3ab285ffb2) | Oct 09, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [cbbb88337f](https://linux-hardware.org/?probe=cbbb88337f) | Oct 09, 2021 |
| Dell          | 0RW199                      | Desktop     | [265977f345](https://linux-hardware.org/?probe=265977f345) | Oct 08, 2021 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [d6391c098d](https://linux-hardware.org/?probe=d6391c098d) | Oct 08, 2021 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [00a9d32484](https://linux-hardware.org/?probe=00a9d32484) | Oct 08, 2021 |
| ASUSTek       | N501VW                      | Notebook    | [40231fbffa](https://linux-hardware.org/?probe=40231fbffa) | Oct 08, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [3c5d005ffb](https://linux-hardware.org/?probe=3c5d005ffb) | Oct 08, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [f180e5db7d](https://linux-hardware.org/?probe=f180e5db7d) | Oct 07, 2021 |
| Dell          | Latitude 7480               | Notebook    | [e4d0ecb120](https://linux-hardware.org/?probe=e4d0ecb120) | Oct 07, 2021 |
| Lenovo        | ThinkPad T490 20N2000KGE    | Notebook    | [cb7f37874e](https://linux-hardware.org/?probe=cb7f37874e) | Oct 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [d76a0d7ff1](https://linux-hardware.org/?probe=d76a0d7ff1) | Oct 07, 2021 |
| Dell          | Latitude E6520              | Notebook    | [18591f972c](https://linux-hardware.org/?probe=18591f972c) | Oct 07, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [7f07c3d457](https://linux-hardware.org/?probe=7f07c3d457) | Oct 07, 2021 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | Desktop     | [b8531e8039](https://linux-hardware.org/?probe=b8531e8039) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9ed170f601](https://linux-hardware.org/?probe=9ed170f601) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [97f69ae3fa](https://linux-hardware.org/?probe=97f69ae3fa) | Oct 07, 2021 |
| HP            | 1998                        | Desktop     | [1a06c2831b](https://linux-hardware.org/?probe=1a06c2831b) | Oct 07, 2021 |
| HP            | 1998                        | Desktop     | [152a505ffd](https://linux-hardware.org/?probe=152a505ffd) | Oct 07, 2021 |
| HP            | 1998                        | Desktop     | [639a06485d](https://linux-hardware.org/?probe=639a06485d) | Oct 07, 2021 |
| Dell          | Vostro A860                 | Notebook    | [02a4dade57](https://linux-hardware.org/?probe=02a4dade57) | Oct 07, 2021 |
| Dell          | Vostro A860                 | Notebook    | [67da5c585b](https://linux-hardware.org/?probe=67da5c585b) | Oct 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [cbb2ea622b](https://linux-hardware.org/?probe=cbb2ea622b) | Oct 07, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [06efedbf24](https://linux-hardware.org/?probe=06efedbf24) | Oct 07, 2021 |
| Pegatron      | 2A99                        | Desktop     | [10f364b4ef](https://linux-hardware.org/?probe=10f364b4ef) | Oct 07, 2021 |
| MSI           | GF63 8RD                    | Notebook    | [42dfecd0fb](https://linux-hardware.org/?probe=42dfecd0fb) | Oct 06, 2021 |
| ASUSTek       | 1015PE                      | Notebook    | [1a2d7bc306](https://linux-hardware.org/?probe=1a2d7bc306) | Oct 06, 2021 |
| MSI           | GF63 8RD                    | Notebook    | [1c72d1e5d7](https://linux-hardware.org/?probe=1c72d1e5d7) | Oct 06, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [9578e01f5b](https://linux-hardware.org/?probe=9578e01f5b) | Oct 06, 2021 |
| ASRock        | AM1B-ITX                    | Desktop     | [417050a11e](https://linux-hardware.org/?probe=417050a11e) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [41ff21e8e8](https://linux-hardware.org/?probe=41ff21e8e8) | Oct 06, 2021 |
| Dell          | Latitude 7480               | Notebook    | [89d642f54a](https://linux-hardware.org/?probe=89d642f54a) | Oct 06, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [eb4d94004c](https://linux-hardware.org/?probe=eb4d94004c) | Oct 06, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [1e7ca025e2](https://linux-hardware.org/?probe=1e7ca025e2) | Oct 06, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [b5e3aaff19](https://linux-hardware.org/?probe=b5e3aaff19) | Oct 06, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [3c8835ecc1](https://linux-hardware.org/?probe=3c8835ecc1) | Oct 05, 2021 |
| HP            | 650                         | Notebook    | [bbe8e793b8](https://linux-hardware.org/?probe=bbe8e793b8) | Oct 05, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [555befb01f](https://linux-hardware.org/?probe=555befb01f) | Oct 05, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [dca9b0f592](https://linux-hardware.org/?probe=dca9b0f592) | Oct 05, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [9a8833b9c4](https://linux-hardware.org/?probe=9a8833b9c4) | Oct 04, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [95f6633ea0](https://linux-hardware.org/?probe=95f6633ea0) | Oct 04, 2021 |
| Dell          | Latitude 7480               | Notebook    | [e8c50a7dbb](https://linux-hardware.org/?probe=e8c50a7dbb) | Oct 04, 2021 |
| Dell          | Latitude E6520              | Notebook    | [b9f0ad8ced](https://linux-hardware.org/?probe=b9f0ad8ced) | Oct 04, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a0fffdb381](https://linux-hardware.org/?probe=a0fffdb381) | Oct 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [572e073021](https://linux-hardware.org/?probe=572e073021) | Oct 04, 2021 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [69ac6e6156](https://linux-hardware.org/?probe=69ac6e6156) | Oct 04, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [bcdf58bee3](https://linux-hardware.org/?probe=bcdf58bee3) | Oct 04, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [6654adaf99](https://linux-hardware.org/?probe=6654adaf99) | Oct 04, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [9622936906](https://linux-hardware.org/?probe=9622936906) | Oct 04, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [ccc383c91f](https://linux-hardware.org/?probe=ccc383c91f) | Oct 03, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [8a9c0fa053](https://linux-hardware.org/?probe=8a9c0fa053) | Oct 03, 2021 |
| Acer          | TMP645-M                    | Notebook    | [c3daab516f](https://linux-hardware.org/?probe=c3daab516f) | Oct 03, 2021 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [52d91383da](https://linux-hardware.org/?probe=52d91383da) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [153c60004b](https://linux-hardware.org/?probe=153c60004b) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [0c7f8d9bc1](https://linux-hardware.org/?probe=0c7f8d9bc1) | Oct 03, 2021 |
| HP            | Laptop 15-ra0xx             | Notebook    | [f053eed9e5](https://linux-hardware.org/?probe=f053eed9e5) | Oct 02, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [5dff50e4bf](https://linux-hardware.org/?probe=5dff50e4bf) | Oct 02, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [eae46e3544](https://linux-hardware.org/?probe=eae46e3544) | Oct 02, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [8169f29a6a](https://linux-hardware.org/?probe=8169f29a6a) | Oct 02, 2021 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [3040e45974](https://linux-hardware.org/?probe=3040e45974) | Oct 02, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [f5565dfb2a](https://linux-hardware.org/?probe=f5565dfb2a) | Oct 01, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [f248667e17](https://linux-hardware.org/?probe=f248667e17) | Oct 01, 2021 |
| HP            | Pavilion g6                 | Notebook    | [ca85ba36e3](https://linux-hardware.org/?probe=ca85ba36e3) | Oct 01, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [85242c59b6](https://linux-hardware.org/?probe=85242c59b6) | Oct 01, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [090eee57b7](https://linux-hardware.org/?probe=090eee57b7) | Oct 01, 2021 |
| TrekStor      | Surfbook A13                | Notebook    | [e393d9bc10](https://linux-hardware.org/?probe=e393d9bc10) | Oct 01, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [666c41eb03](https://linux-hardware.org/?probe=666c41eb03) | Oct 01, 2021 |
| MSI           | GF75 Thin 9SC               | Notebook    | [b62cc852e9](https://linux-hardware.org/?probe=b62cc852e9) | Oct 01, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [0228744a56](https://linux-hardware.org/?probe=0228744a56) | Oct 01, 2021 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [689bc2e25f](https://linux-hardware.org/?probe=689bc2e25f) | Oct 01, 2021 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [29ae8992b5](https://linux-hardware.org/?probe=29ae8992b5) | Sep 30, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [de498adb08](https://linux-hardware.org/?probe=de498adb08) | Sep 30, 2021 |
| HP            | 3047h                       | Desktop     | [89b3f0a1ad](https://linux-hardware.org/?probe=89b3f0a1ad) | Sep 30, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e68e81c986](https://linux-hardware.org/?probe=e68e81c986) | Sep 30, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f273082d09](https://linux-hardware.org/?probe=f273082d09) | Sep 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8fa4158350](https://linux-hardware.org/?probe=8fa4158350) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [201d45c8e0](https://linux-hardware.org/?probe=201d45c8e0) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [508593e110](https://linux-hardware.org/?probe=508593e110) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [0a0b3ced3f](https://linux-hardware.org/?probe=0a0b3ced3f) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [b083b87cc1](https://linux-hardware.org/?probe=b083b87cc1) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [6bf4c617bf](https://linux-hardware.org/?probe=6bf4c617bf) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [2891a2fc4e](https://linux-hardware.org/?probe=2891a2fc4e) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [1969de09f1](https://linux-hardware.org/?probe=1969de09f1) | Sep 30, 2021 |
| Dell          | Latitude 7480               | Notebook    | [edecedab9c](https://linux-hardware.org/?probe=edecedab9c) | Sep 30, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b8b2183bc1](https://linux-hardware.org/?probe=b8b2183bc1) | Sep 30, 2021 |
| Intel Clie... | LAPBC710                    | Notebook    | [f2535939a1](https://linux-hardware.org/?probe=f2535939a1) | Sep 29, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [75eb93bbe0](https://linux-hardware.org/?probe=75eb93bbe0) | Sep 29, 2021 |
| MSI           | H81M-P33                    | Desktop     | [c7540ecd61](https://linux-hardware.org/?probe=c7540ecd61) | Sep 29, 2021 |
| Timi          | TM1613                      | Notebook    | [f6bb688e77](https://linux-hardware.org/?probe=f6bb688e77) | Sep 29, 2021 |
| Dell          | Precision 3561              | Notebook    | [59bbb944c2](https://linux-hardware.org/?probe=59bbb944c2) | Sep 29, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [885bbac853](https://linux-hardware.org/?probe=885bbac853) | Sep 29, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b8e7519557](https://linux-hardware.org/?probe=b8e7519557) | Sep 29, 2021 |
| Dell          | 07PXPY A02                  | Server      | [9320e12a9a](https://linux-hardware.org/?probe=9320e12a9a) | Sep 29, 2021 |
| Dell          | 07PXPY A02                  | Server      | [5093f7c3c8](https://linux-hardware.org/?probe=5093f7c3c8) | Sep 29, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [d277db28c5](https://linux-hardware.org/?probe=d277db28c5) | Sep 29, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [f7a5bd6c04](https://linux-hardware.org/?probe=f7a5bd6c04) | Sep 29, 2021 |
| Dell          | Latitude D630               | Notebook    | [5e7edac95e](https://linux-hardware.org/?probe=5e7edac95e) | Sep 29, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [01ccd7b321](https://linux-hardware.org/?probe=01ccd7b321) | Sep 28, 2021 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [748880a78e](https://linux-hardware.org/?probe=748880a78e) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [36df7d61be](https://linux-hardware.org/?probe=36df7d61be) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [4514b06137](https://linux-hardware.org/?probe=4514b06137) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [ac6c9be38a](https://linux-hardware.org/?probe=ac6c9be38a) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [36532b595e](https://linux-hardware.org/?probe=36532b595e) | Sep 28, 2021 |
| HP            | Pavilion g6                 | Notebook    | [a349ae4420](https://linux-hardware.org/?probe=a349ae4420) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [b4273a32be](https://linux-hardware.org/?probe=b4273a32be) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [0b6cac4bce](https://linux-hardware.org/?probe=0b6cac4bce) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [3ebd210998](https://linux-hardware.org/?probe=3ebd210998) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [8ad08b2012](https://linux-hardware.org/?probe=8ad08b2012) | Sep 28, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [b8706044ce](https://linux-hardware.org/?probe=b8706044ce) | Sep 28, 2021 |
| Digiboard     | MPxx                        | Desktop     | [bad4baa7aa](https://linux-hardware.org/?probe=bad4baa7aa) | Sep 28, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [997cfe39d2](https://linux-hardware.org/?probe=997cfe39d2) | Sep 28, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [b633c9e1d1](https://linux-hardware.org/?probe=b633c9e1d1) | Sep 28, 2021 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [55315b68ec](https://linux-hardware.org/?probe=55315b68ec) | Sep 28, 2021 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [5849e72724](https://linux-hardware.org/?probe=5849e72724) | Sep 28, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [05ad040f44](https://linux-hardware.org/?probe=05ad040f44) | Sep 27, 2021 |
| ASUSTek       | X556UAK                     | Notebook    | [6cd310a2c4](https://linux-hardware.org/?probe=6cd310a2c4) | Sep 27, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [6af7a7f851](https://linux-hardware.org/?probe=6af7a7f851) | Sep 27, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [eca410ddc4](https://linux-hardware.org/?probe=eca410ddc4) | Sep 27, 2021 |
| Lenovo        | ThinkPad T430 2349N7G       | Notebook    | [d82d96a0ce](https://linux-hardware.org/?probe=d82d96a0ce) | Sep 27, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [b8427dd0a9](https://linux-hardware.org/?probe=b8427dd0a9) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [61fb50bdf0](https://linux-hardware.org/?probe=61fb50bdf0) | Sep 27, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [029b85826d](https://linux-hardware.org/?probe=029b85826d) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [af3fbbd82c](https://linux-hardware.org/?probe=af3fbbd82c) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [28c82e6c3c](https://linux-hardware.org/?probe=28c82e6c3c) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7a75c1404b](https://linux-hardware.org/?probe=7a75c1404b) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [79aa111080](https://linux-hardware.org/?probe=79aa111080) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [99b52f5b1a](https://linux-hardware.org/?probe=99b52f5b1a) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7e50f2bf77](https://linux-hardware.org/?probe=7e50f2bf77) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d516cbbc97](https://linux-hardware.org/?probe=d516cbbc97) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [825770fd12](https://linux-hardware.org/?probe=825770fd12) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8e6770f9bd](https://linux-hardware.org/?probe=8e6770f9bd) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a022c3ec02](https://linux-hardware.org/?probe=a022c3ec02) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [991e447de1](https://linux-hardware.org/?probe=991e447de1) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3470189758](https://linux-hardware.org/?probe=3470189758) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8a23b4112f](https://linux-hardware.org/?probe=8a23b4112f) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1843bfdb65](https://linux-hardware.org/?probe=1843bfdb65) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bc4d5fd16b](https://linux-hardware.org/?probe=bc4d5fd16b) | Sep 27, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a01dd88bfb](https://linux-hardware.org/?probe=a01dd88bfb) | Sep 27, 2021 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [c0104aa33d](https://linux-hardware.org/?probe=c0104aa33d) | Sep 27, 2021 |
| Lenovo        | IdeaPad U510 4941           | Notebook    | [f0f189cfc9](https://linux-hardware.org/?probe=f0f189cfc9) | Sep 27, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [9870240430](https://linux-hardware.org/?probe=9870240430) | Sep 27, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [85925128ef](https://linux-hardware.org/?probe=85925128ef) | Sep 27, 2021 |
| HP            | G61                         | Notebook    | [348bab0a1b](https://linux-hardware.org/?probe=348bab0a1b) | Sep 27, 2021 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [ee4f0f6f02](https://linux-hardware.org/?probe=ee4f0f6f02) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | Notebook    | [721c266b6b](https://linux-hardware.org/?probe=721c266b6b) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | Notebook    | [00d9651c96](https://linux-hardware.org/?probe=00d9651c96) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [f290c9b80f](https://linux-hardware.org/?probe=f290c9b80f) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [82bd2ec7eb](https://linux-hardware.org/?probe=82bd2ec7eb) | Sep 27, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [f11ad64d60](https://linux-hardware.org/?probe=f11ad64d60) | Sep 26, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [5236361305](https://linux-hardware.org/?probe=5236361305) | Sep 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8f8f724934](https://linux-hardware.org/?probe=8f8f724934) | Sep 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3b68a00361](https://linux-hardware.org/?probe=3b68a00361) | Sep 26, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [6500bed04d](https://linux-hardware.org/?probe=6500bed04d) | Sep 26, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [abf2c60d3f](https://linux-hardware.org/?probe=abf2c60d3f) | Sep 26, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [97a2a90138](https://linux-hardware.org/?probe=97a2a90138) | Sep 26, 2021 |
| ASUSTek       | TUF GAMING H570-PRO         | Desktop     | [97c090583f](https://linux-hardware.org/?probe=97c090583f) | Sep 26, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [26897714a0](https://linux-hardware.org/?probe=26897714a0) | Sep 26, 2021 |
| Dell          | 018D1Y A00                  | Desktop     | [7ffbeea841](https://linux-hardware.org/?probe=7ffbeea841) | Sep 26, 2021 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [4949f4edef](https://linux-hardware.org/?probe=4949f4edef) | Sep 26, 2021 |
| Toshiba       | Satellite C655D             | Notebook    | [7742f4cfe0](https://linux-hardware.org/?probe=7742f4cfe0) | Sep 26, 2021 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [1f56f02f1d](https://linux-hardware.org/?probe=1f56f02f1d) | Sep 26, 2021 |
| Acer          | TravelMate 2490             | Notebook    | [b09a0d7779](https://linux-hardware.org/?probe=b09a0d7779) | Sep 25, 2021 |
| ECS           | G31T-M9                     | Desktop     | [e0cdbe10a3](https://linux-hardware.org/?probe=e0cdbe10a3) | Sep 25, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [0c67accead](https://linux-hardware.org/?probe=0c67accead) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [10ce8f4e5e](https://linux-hardware.org/?probe=10ce8f4e5e) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b62637ba85](https://linux-hardware.org/?probe=b62637ba85) | Sep 25, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [3b61d0a304](https://linux-hardware.org/?probe=3b61d0a304) | Sep 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [2762c5237d](https://linux-hardware.org/?probe=2762c5237d) | Sep 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [7a1202630f](https://linux-hardware.org/?probe=7a1202630f) | Sep 25, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [4d798633db](https://linux-hardware.org/?probe=4d798633db) | Sep 25, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a97e17fc48](https://linux-hardware.org/?probe=a97e17fc48) | Sep 25, 2021 |
| Dell          | G3 3590                     | Notebook    | [519cea3f38](https://linux-hardware.org/?probe=519cea3f38) | Sep 25, 2021 |
| Dell          | G3 3590                     | Notebook    | [bb25c895cf](https://linux-hardware.org/?probe=bb25c895cf) | Sep 25, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [11ebd06d5f](https://linux-hardware.org/?probe=11ebd06d5f) | Sep 25, 2021 |
| HP            | ProBook 4530s               | Notebook    | [0fc1845cd7](https://linux-hardware.org/?probe=0fc1845cd7) | Sep 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [e9d692e16d](https://linux-hardware.org/?probe=e9d692e16d) | Sep 24, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [76445d703b](https://linux-hardware.org/?probe=76445d703b) | Sep 24, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [c654d6756a](https://linux-hardware.org/?probe=c654d6756a) | Sep 24, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [22132026c3](https://linux-hardware.org/?probe=22132026c3) | Sep 24, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [64af4c4882](https://linux-hardware.org/?probe=64af4c4882) | Sep 24, 2021 |
| Intel         | S1200RP G62251-405          | Server      | [20bb0a8951](https://linux-hardware.org/?probe=20bb0a8951) | Sep 24, 2021 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [652a4e63cd](https://linux-hardware.org/?probe=652a4e63cd) | Sep 24, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | Notebook    | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Dell          | Precision M4800             | Notebook    | [1d4a25cfec](https://linux-hardware.org/?probe=1d4a25cfec) | Sep 24, 2021 |
| Acer          | Revo 70                     | Desktop     | [beb207e679](https://linux-hardware.org/?probe=beb207e679) | Sep 24, 2021 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [5e1a7fc6bc](https://linux-hardware.org/?probe=5e1a7fc6bc) | Sep 24, 2021 |
| ASRock        | AM1B-ITX                    | Desktop     | [5ffe158a0b](https://linux-hardware.org/?probe=5ffe158a0b) | Sep 24, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [166930508c](https://linux-hardware.org/?probe=166930508c) | Sep 24, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [fbe6b1147d](https://linux-hardware.org/?probe=fbe6b1147d) | Sep 24, 2021 |
| Acer          | TravelMate P273             | Notebook    | [125707a56f](https://linux-hardware.org/?probe=125707a56f) | Sep 24, 2021 |
| Lenovo        | ThinkStation S20 4105L1U    | Desktop     | [593eda37d7](https://linux-hardware.org/?probe=593eda37d7) | Sep 23, 2021 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [daab62b41a](https://linux-hardware.org/?probe=daab62b41a) | Sep 23, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [11cfe1c6c6](https://linux-hardware.org/?probe=11cfe1c6c6) | Sep 23, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a9d4d9e61b](https://linux-hardware.org/?probe=a9d4d9e61b) | Sep 23, 2021 |
| Acer          | Revo 70                     | Desktop     | [138db946a6](https://linux-hardware.org/?probe=138db946a6) | Sep 23, 2021 |
| MSI           | GE70 2QE                    | Notebook    | [b1cbbbd78f](https://linux-hardware.org/?probe=b1cbbbd78f) | Sep 23, 2021 |
| ASUSTek       | 1015BXO                     | Notebook    | [0f2bd07e92](https://linux-hardware.org/?probe=0f2bd07e92) | Sep 23, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [5ddd391946](https://linux-hardware.org/?probe=5ddd391946) | Sep 23, 2021 |
| Acer          | Aspire Z3771                | All in one  | [b31e4d7238](https://linux-hardware.org/?probe=b31e4d7238) | Sep 23, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [b77c25619c](https://linux-hardware.org/?probe=b77c25619c) | Sep 23, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [8d162e55d8](https://linux-hardware.org/?probe=8d162e55d8) | Sep 23, 2021 |
| Acer          | Aspire Z3771                | All in one  | [b5fc5f1ee1](https://linux-hardware.org/?probe=b5fc5f1ee1) | Sep 23, 2021 |
| ASRock        | 760GM-HD                    | Desktop     | [3e95020892](https://linux-hardware.org/?probe=3e95020892) | Sep 23, 2021 |
| ASRock        | 760GM-HD                    | Desktop     | [f43227bf66](https://linux-hardware.org/?probe=f43227bf66) | Sep 23, 2021 |
| ASRock        | AM1B-ITX                    | Desktop     | [5896638049](https://linux-hardware.org/?probe=5896638049) | Sep 22, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [f214b7efbe](https://linux-hardware.org/?probe=f214b7efbe) | Sep 22, 2021 |
| HP            | 15                          | Notebook    | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b1fd2fc90a](https://linux-hardware.org/?probe=b1fd2fc90a) | Sep 22, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e36127ceb6](https://linux-hardware.org/?probe=e36127ceb6) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [beea39044c](https://linux-hardware.org/?probe=beea39044c) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [48b0ac8f13](https://linux-hardware.org/?probe=48b0ac8f13) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e7e1e964b7](https://linux-hardware.org/?probe=e7e1e964b7) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [74924ea2e4](https://linux-hardware.org/?probe=74924ea2e4) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5ff0a78d73](https://linux-hardware.org/?probe=5ff0a78d73) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [daf72e6a78](https://linux-hardware.org/?probe=daf72e6a78) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b6b9dd27e1](https://linux-hardware.org/?probe=b6b9dd27e1) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [359496edc0](https://linux-hardware.org/?probe=359496edc0) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [da848bd94a](https://linux-hardware.org/?probe=da848bd94a) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b49beb821b](https://linux-hardware.org/?probe=b49beb821b) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9d5d7d92f2](https://linux-hardware.org/?probe=9d5d7d92f2) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [24924d259f](https://linux-hardware.org/?probe=24924d259f) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [cabfc0b798](https://linux-hardware.org/?probe=cabfc0b798) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7bd83fb3a6](https://linux-hardware.org/?probe=7bd83fb3a6) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d3c7607377](https://linux-hardware.org/?probe=d3c7607377) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a14febce4c](https://linux-hardware.org/?probe=a14febce4c) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0ceb88188b](https://linux-hardware.org/?probe=0ceb88188b) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [04cecd0992](https://linux-hardware.org/?probe=04cecd0992) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [259707c0a4](https://linux-hardware.org/?probe=259707c0a4) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [366475c03d](https://linux-hardware.org/?probe=366475c03d) | Sep 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [72f179ec58](https://linux-hardware.org/?probe=72f179ec58) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [95ba69ad89](https://linux-hardware.org/?probe=95ba69ad89) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [972685a299](https://linux-hardware.org/?probe=972685a299) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [48dc96e8fa](https://linux-hardware.org/?probe=48dc96e8fa) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4dab5d9a57](https://linux-hardware.org/?probe=4dab5d9a57) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [50f1e050a8](https://linux-hardware.org/?probe=50f1e050a8) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [37c5e8334c](https://linux-hardware.org/?probe=37c5e8334c) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [581dba008c](https://linux-hardware.org/?probe=581dba008c) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [635bf47b02](https://linux-hardware.org/?probe=635bf47b02) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [8a38fba20f](https://linux-hardware.org/?probe=8a38fba20f) | Sep 22, 2021 |
| ASUSTek       | P8B75-V                     | Desktop     | [84fc3eb5f2](https://linux-hardware.org/?probe=84fc3eb5f2) | Sep 22, 2021 |
| Lenovo        | Mixx-700-12ISK 80QL         | Notebook    | [090e25b77c](https://linux-hardware.org/?probe=090e25b77c) | Sep 22, 2021 |
| HP            | 8298                        | Desktop     | [5517c4780d](https://linux-hardware.org/?probe=5517c4780d) | Sep 22, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [09083b7dad](https://linux-hardware.org/?probe=09083b7dad) | Sep 22, 2021 |
| ASUSTek       | P8B75-V                     | Desktop     | [cf5436e8a1](https://linux-hardware.org/?probe=cf5436e8a1) | Sep 22, 2021 |
| ECS           | G31T-M9                     | Desktop     | [92ecc52d2f](https://linux-hardware.org/?probe=92ecc52d2f) | Sep 22, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [1e8858844a](https://linux-hardware.org/?probe=1e8858844a) | Sep 22, 2021 |
| Dell          | Latitude E7240              | Notebook    | [7048aa6e8b](https://linux-hardware.org/?probe=7048aa6e8b) | Sep 22, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [ff5e9a45c3](https://linux-hardware.org/?probe=ff5e9a45c3) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0f855cbebc](https://linux-hardware.org/?probe=0f855cbebc) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [57b1733974](https://linux-hardware.org/?probe=57b1733974) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b27cdffcdf](https://linux-hardware.org/?probe=b27cdffcdf) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4fe24a3a03](https://linux-hardware.org/?probe=4fe24a3a03) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b662e38e3e](https://linux-hardware.org/?probe=b662e38e3e) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [19bd58d8fd](https://linux-hardware.org/?probe=19bd58d8fd) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [64b5e6acaf](https://linux-hardware.org/?probe=64b5e6acaf) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [57c15e2ce4](https://linux-hardware.org/?probe=57c15e2ce4) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2376be9dc6](https://linux-hardware.org/?probe=2376be9dc6) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [58bdb95875](https://linux-hardware.org/?probe=58bdb95875) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a578c1a29a](https://linux-hardware.org/?probe=a578c1a29a) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1d02729da0](https://linux-hardware.org/?probe=1d02729da0) | Sep 21, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [5e6cd3a827](https://linux-hardware.org/?probe=5e6cd3a827) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d95d7f2e13](https://linux-hardware.org/?probe=d95d7f2e13) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7b0e4f28fa](https://linux-hardware.org/?probe=7b0e4f28fa) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ac53f68bab](https://linux-hardware.org/?probe=ac53f68bab) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4f1ab6ca31](https://linux-hardware.org/?probe=4f1ab6ca31) | Sep 21, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [0dcd3691cd](https://linux-hardware.org/?probe=0dcd3691cd) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [00785cdd23](https://linux-hardware.org/?probe=00785cdd23) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0a46f82c2e](https://linux-hardware.org/?probe=0a46f82c2e) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [11a2d1bf7a](https://linux-hardware.org/?probe=11a2d1bf7a) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [83c6fbb8a4](https://linux-hardware.org/?probe=83c6fbb8a4) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [aa05fd9839](https://linux-hardware.org/?probe=aa05fd9839) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b58a27a7e6](https://linux-hardware.org/?probe=b58a27a7e6) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [47aabdfd32](https://linux-hardware.org/?probe=47aabdfd32) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f49d1d8152](https://linux-hardware.org/?probe=f49d1d8152) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [242501bd61](https://linux-hardware.org/?probe=242501bd61) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [67a23aca3c](https://linux-hardware.org/?probe=67a23aca3c) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [569ef69c19](https://linux-hardware.org/?probe=569ef69c19) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [906d6fd6f3](https://linux-hardware.org/?probe=906d6fd6f3) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a9789fc53b](https://linux-hardware.org/?probe=a9789fc53b) | Sep 21, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [4ce9cddd8f](https://linux-hardware.org/?probe=4ce9cddd8f) | Sep 21, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [c2a3074723](https://linux-hardware.org/?probe=c2a3074723) | Sep 21, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [8d112d9531](https://linux-hardware.org/?probe=8d112d9531) | Sep 21, 2021 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [65802f1a29](https://linux-hardware.org/?probe=65802f1a29) | Sep 21, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [f2e1fbb30c](https://linux-hardware.org/?probe=f2e1fbb30c) | Sep 21, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [d6e37b9488](https://linux-hardware.org/?probe=d6e37b9488) | Sep 21, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [14ea1aaa38](https://linux-hardware.org/?probe=14ea1aaa38) | Sep 21, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [b767020eb6](https://linux-hardware.org/?probe=b767020eb6) | Sep 21, 2021 |
| Intel         | DQ35JO AAD82085-800         | Desktop     | [3751d2399e](https://linux-hardware.org/?probe=3751d2399e) | Sep 21, 2021 |
| Lenovo        | ThinkPad T480S 20L7002HC... | Notebook    | [18b74e9f12](https://linux-hardware.org/?probe=18b74e9f12) | Sep 21, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [ab40e7b1de](https://linux-hardware.org/?probe=ab40e7b1de) | Sep 21, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [13687ea608](https://linux-hardware.org/?probe=13687ea608) | Sep 21, 2021 |
| ASUSTek       | K50IN                       | Notebook    | [7cdaef32aa](https://linux-hardware.org/?probe=7cdaef32aa) | Sep 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [203ccd91be](https://linux-hardware.org/?probe=203ccd91be) | Sep 20, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [e8748906aa](https://linux-hardware.org/?probe=e8748906aa) | Sep 20, 2021 |
| MSI           | GE70 2QE                    | Notebook    | [a8b9147ea7](https://linux-hardware.org/?probe=a8b9147ea7) | Sep 20, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [22262e98a5](https://linux-hardware.org/?probe=22262e98a5) | Sep 20, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [c266841471](https://linux-hardware.org/?probe=c266841471) | Sep 20, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [81802596f8](https://linux-hardware.org/?probe=81802596f8) | Sep 20, 2021 |
| HP            | Pavilion g6                 | Notebook    | [d7ce22ebcb](https://linux-hardware.org/?probe=d7ce22ebcb) | Sep 20, 2021 |
| HP            | Pavilion g6                 | Notebook    | [3c060f3910](https://linux-hardware.org/?probe=3c060f3910) | Sep 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0UM0... | Notebook    | [bcb44edae6](https://linux-hardware.org/?probe=bcb44edae6) | Sep 20, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7e46c0bea0](https://linux-hardware.org/?probe=7e46c0bea0) | Sep 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0UM0... | Notebook    | [d623d8381b](https://linux-hardware.org/?probe=d623d8381b) | Sep 20, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| Lenovo        | ThinkPad P53 20QQA004CD     | Notebook    | [50b6533131](https://linux-hardware.org/?probe=50b6533131) | Sep 20, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d5776c4fd0](https://linux-hardware.org/?probe=d5776c4fd0) | Sep 20, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [7be63eda40](https://linux-hardware.org/?probe=7be63eda40) | Sep 20, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [72c81ecb73](https://linux-hardware.org/?probe=72c81ecb73) | Sep 19, 2021 |
| HP            | 8433 11                     | Desktop     | [5c7a7c98e8](https://linux-hardware.org/?probe=5c7a7c98e8) | Sep 19, 2021 |
| HP            | 225E                        | Desktop     | [eadad0eb90](https://linux-hardware.org/?probe=eadad0eb90) | Sep 19, 2021 |
| MSI           | U270 series                 | Notebook    | [6b98f78732](https://linux-hardware.org/?probe=6b98f78732) | Sep 19, 2021 |
| Acer          | AOA110                      | Notebook    | [a54c248743](https://linux-hardware.org/?probe=a54c248743) | Sep 19, 2021 |
| HP            | Pavilion dv6                | Notebook    | [b4d25f6f3a](https://linux-hardware.org/?probe=b4d25f6f3a) | Sep 19, 2021 |
| Sony          | VGN-CR21Z_N                 | Notebook    | [6fc19f4c67](https://linux-hardware.org/?probe=6fc19f4c67) | Sep 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [5dabdbd945](https://linux-hardware.org/?probe=5dabdbd945) | Sep 19, 2021 |
| Gigabyte      | GB-BLCE-4105R               | Desktop     | [3a1284b530](https://linux-hardware.org/?probe=3a1284b530) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [61fd64b037](https://linux-hardware.org/?probe=61fd64b037) | Sep 19, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [7a0ce4b17e](https://linux-hardware.org/?probe=7a0ce4b17e) | Sep 19, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [10c1838b9d](https://linux-hardware.org/?probe=10c1838b9d) | Sep 19, 2021 |
| MSI           | U270 series                 | Notebook    | [725e0a6a36](https://linux-hardware.org/?probe=725e0a6a36) | Sep 18, 2021 |
| Acer          | Aspire 5560                 | Notebook    | [f35af81d19](https://linux-hardware.org/?probe=f35af81d19) | Sep 18, 2021 |
| ASUSTek       | PN62S                       | Mini pc     | [7a01c63401](https://linux-hardware.org/?probe=7a01c63401) | Sep 18, 2021 |
| Gigabyte      | P35-DS3                     | Desktop     | [32413546ce](https://linux-hardware.org/?probe=32413546ce) | Sep 18, 2021 |
| Dell          | Latitude E7450              | Notebook    | [f5963dc359](https://linux-hardware.org/?probe=f5963dc359) | Sep 18, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [6dcb59c0e5](https://linux-hardware.org/?probe=6dcb59c0e5) | Sep 18, 2021 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [6ce6f8e7f7](https://linux-hardware.org/?probe=6ce6f8e7f7) | Sep 17, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1ca8880edb](https://linux-hardware.org/?probe=1ca8880edb) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [ebc7aac8d2](https://linux-hardware.org/?probe=ebc7aac8d2) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [cc91d3d293](https://linux-hardware.org/?probe=cc91d3d293) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [cf7b743325](https://linux-hardware.org/?probe=cf7b743325) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [58efd773fc](https://linux-hardware.org/?probe=58efd773fc) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [6f61a4bed1](https://linux-hardware.org/?probe=6f61a4bed1) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [2847b27014](https://linux-hardware.org/?probe=2847b27014) | Sep 17, 2021 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [f6cde497b4](https://linux-hardware.org/?probe=f6cde497b4) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [ca5062256b](https://linux-hardware.org/?probe=ca5062256b) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [8b0908956f](https://linux-hardware.org/?probe=8b0908956f) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [35b84b3b23](https://linux-hardware.org/?probe=35b84b3b23) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [fd3abf36d9](https://linux-hardware.org/?probe=fd3abf36d9) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [49001d8064](https://linux-hardware.org/?probe=49001d8064) | Sep 17, 2021 |
| Lenovo        | IdeaPad U510 4941           | Notebook    | [f5774645c1](https://linux-hardware.org/?probe=f5774645c1) | Sep 17, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0f6db66354](https://linux-hardware.org/?probe=0f6db66354) | Sep 17, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3fde672bb3](https://linux-hardware.org/?probe=3fde672bb3) | Sep 17, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [2179e59b37](https://linux-hardware.org/?probe=2179e59b37) | Sep 17, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [84394a400e](https://linux-hardware.org/?probe=84394a400e) | Sep 17, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [726f5ed51f](https://linux-hardware.org/?probe=726f5ed51f) | Sep 17, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [e0307085f3](https://linux-hardware.org/?probe=e0307085f3) | Sep 17, 2021 |
| MSI           | GE70 2QE                    | Notebook    | [e7b42c85f1](https://linux-hardware.org/?probe=e7b42c85f1) | Sep 17, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [abd7f0d0a1](https://linux-hardware.org/?probe=abd7f0d0a1) | Sep 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c8208bc767](https://linux-hardware.org/?probe=c8208bc767) | Sep 17, 2021 |
| MSI           | GF75 Thin 9SC               | Notebook    | [47a6cd4031](https://linux-hardware.org/?probe=47a6cd4031) | Sep 17, 2021 |
| MSI           | GE70 2QE                    | Notebook    | [8d4eff5ca2](https://linux-hardware.org/?probe=8d4eff5ca2) | Sep 17, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [f226485da3](https://linux-hardware.org/?probe=f226485da3) | Sep 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [643fafdceb](https://linux-hardware.org/?probe=643fafdceb) | Sep 17, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [381f6460b0](https://linux-hardware.org/?probe=381f6460b0) | Sep 17, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [77f32a8e42](https://linux-hardware.org/?probe=77f32a8e42) | Sep 17, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [e801613095](https://linux-hardware.org/?probe=e801613095) | Sep 17, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [fb0c3317e3](https://linux-hardware.org/?probe=fb0c3317e3) | Sep 17, 2021 |
| MSI           | Z370 PC PRO                 | Desktop     | [c79178e6db](https://linux-hardware.org/?probe=c79178e6db) | Sep 17, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [5282f852aa](https://linux-hardware.org/?probe=5282f852aa) | Sep 17, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [dd5496fa35](https://linux-hardware.org/?probe=dd5496fa35) | Sep 17, 2021 |
| Timi          | TM1801                      | Notebook    | [d0919977cb](https://linux-hardware.org/?probe=d0919977cb) | Sep 17, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [722f184570](https://linux-hardware.org/?probe=722f184570) | Sep 17, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [1fe7a4c597](https://linux-hardware.org/?probe=1fe7a4c597) | Sep 17, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [cbe5d18ac2](https://linux-hardware.org/?probe=cbe5d18ac2) | Sep 17, 2021 |
| Libretrend    | LT1000                      | Desktop     | [781fa86fea](https://linux-hardware.org/?probe=781fa86fea) | Sep 17, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fb9a8ab054](https://linux-hardware.org/?probe=fb9a8ab054) | Sep 16, 2021 |
| ECS           | G31T-M9                     | Desktop     | [ba4a294b69](https://linux-hardware.org/?probe=ba4a294b69) | Sep 16, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [d1a7e38fc8](https://linux-hardware.org/?probe=d1a7e38fc8) | Sep 16, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [10c9991f0b](https://linux-hardware.org/?probe=10c9991f0b) | Sep 16, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3ef71721e0](https://linux-hardware.org/?probe=3ef71721e0) | Sep 16, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [df29a592fb](https://linux-hardware.org/?probe=df29a592fb) | Sep 16, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [e8ac4691b0](https://linux-hardware.org/?probe=e8ac4691b0) | Sep 16, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [6b7410fa5c](https://linux-hardware.org/?probe=6b7410fa5c) | Sep 16, 2021 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [6056c96428](https://linux-hardware.org/?probe=6056c96428) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4bb2af8998](https://linux-hardware.org/?probe=4bb2af8998) | Sep 16, 2021 |
| HP            | 83EB                        | All in one  | [cc989948af](https://linux-hardware.org/?probe=cc989948af) | Sep 16, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [233ad54ef9](https://linux-hardware.org/?probe=233ad54ef9) | Sep 16, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [d4e804931a](https://linux-hardware.org/?probe=d4e804931a) | Sep 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ee258307b1](https://linux-hardware.org/?probe=ee258307b1) | Sep 15, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [bec4c36c67](https://linux-hardware.org/?probe=bec4c36c67) | Sep 15, 2021 |
| PC Special... | Standard                    | Notebook    | [1454a60100](https://linux-hardware.org/?probe=1454a60100) | Sep 15, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [af6b84e00b](https://linux-hardware.org/?probe=af6b84e00b) | Sep 15, 2021 |
| Lenovo        | ThinkPad E460 20EUA00AAC    | Notebook    | [c7d8dc11ca](https://linux-hardware.org/?probe=c7d8dc11ca) | Sep 15, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [576b90b734](https://linux-hardware.org/?probe=576b90b734) | Sep 15, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [e9c177240a](https://linux-hardware.org/?probe=e9c177240a) | Sep 15, 2021 |
| Acer          | AO725                       | Notebook    | [68eeff0c2f](https://linux-hardware.org/?probe=68eeff0c2f) | Sep 15, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [730c0eebf9](https://linux-hardware.org/?probe=730c0eebf9) | Sep 14, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [a062985645](https://linux-hardware.org/?probe=a062985645) | Sep 14, 2021 |
| HP            | 8446                        | All in one  | [7744251d76](https://linux-hardware.org/?probe=7744251d76) | Sep 14, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [7e486cd179](https://linux-hardware.org/?probe=7e486cd179) | Sep 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [7f88a77812](https://linux-hardware.org/?probe=7f88a77812) | Sep 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e606ccc75f](https://linux-hardware.org/?probe=e606ccc75f) | Sep 14, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8622681e00](https://linux-hardware.org/?probe=8622681e00) | Sep 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [f2363c7d5e](https://linux-hardware.org/?probe=f2363c7d5e) | Sep 14, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [db3a48e82e](https://linux-hardware.org/?probe=db3a48e82e) | Sep 14, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f6f26d4c8e](https://linux-hardware.org/?probe=f6f26d4c8e) | Sep 14, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [54e89a0f5a](https://linux-hardware.org/?probe=54e89a0f5a) | Sep 14, 2021 |
| Positivo      | POS-PIQ77CL                 | Desktop     | [87ec217aed](https://linux-hardware.org/?probe=87ec217aed) | Sep 14, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [7f6f4bedd3](https://linux-hardware.org/?probe=7f6f4bedd3) | Sep 14, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0561b8a369](https://linux-hardware.org/?probe=0561b8a369) | Sep 13, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [01008b3cfd](https://linux-hardware.org/?probe=01008b3cfd) | Sep 13, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [cd3844f542](https://linux-hardware.org/?probe=cd3844f542) | Sep 13, 2021 |
| MSI           | H81M-P33                    | Desktop     | [b5b64471de](https://linux-hardware.org/?probe=b5b64471de) | Sep 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eb55a1f000](https://linux-hardware.org/?probe=eb55a1f000) | Sep 13, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [3be45aba31](https://linux-hardware.org/?probe=3be45aba31) | Sep 13, 2021 |
| ASRock        | AM1B-ITX                    | Desktop     | [b15ebc1577](https://linux-hardware.org/?probe=b15ebc1577) | Sep 13, 2021 |
| HP            | Notebook                    | Notebook    | [17f4133e28](https://linux-hardware.org/?probe=17f4133e28) | Sep 13, 2021 |
| Supermicro    | X8DTN                       | Server      | [535e5f1d58](https://linux-hardware.org/?probe=535e5f1d58) | Sep 13, 2021 |
| Supermicro    | X8DTN                       | Server      | [39ace40ad6](https://linux-hardware.org/?probe=39ace40ad6) | Sep 13, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [51cf32f87c](https://linux-hardware.org/?probe=51cf32f87c) | Sep 12, 2021 |
| MSI           | Z170-A PRO                  | Desktop     | [5b702a6c05](https://linux-hardware.org/?probe=5b702a6c05) | Sep 12, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [8109d84e42](https://linux-hardware.org/?probe=8109d84e42) | Sep 12, 2021 |
| Lenovo        | ThinkPad E14 20RB0028BR     | Notebook    | [8b1b3a98ba](https://linux-hardware.org/?probe=8b1b3a98ba) | Sep 12, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [cf7cbe9ec0](https://linux-hardware.org/?probe=cf7cbe9ec0) | Sep 12, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [1fc1622a64](https://linux-hardware.org/?probe=1fc1622a64) | Sep 12, 2021 |
| ASUSTek       | M3N                         | Notebook    | [28a5b48a05](https://linux-hardware.org/?probe=28a5b48a05) | Sep 12, 2021 |
| ASUSTek       | M3N                         | Notebook    | [04307947ae](https://linux-hardware.org/?probe=04307947ae) | Sep 12, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | Desktop     | [f81450ac96](https://linux-hardware.org/?probe=f81450ac96) | Sep 11, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c9bcb0db96](https://linux-hardware.org/?probe=c9bcb0db96) | Sep 11, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | Desktop     | [0e9729a88b](https://linux-hardware.org/?probe=0e9729a88b) | Sep 11, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b6d09ad044](https://linux-hardware.org/?probe=b6d09ad044) | Sep 10, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [035ee1f7ec](https://linux-hardware.org/?probe=035ee1f7ec) | Sep 10, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2136b1f58c](https://linux-hardware.org/?probe=2136b1f58c) | Sep 10, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [da3f4572d1](https://linux-hardware.org/?probe=da3f4572d1) | Sep 10, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5598608780](https://linux-hardware.org/?probe=5598608780) | Sep 10, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [795f6bba58](https://linux-hardware.org/?probe=795f6bba58) | Sep 10, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Acer          | Aspire M3420                | Desktop     | [dfd381db06](https://linux-hardware.org/?probe=dfd381db06) | Sep 10, 2021 |
| Acer          | Aspire M3420                | Desktop     | [7a4ab56f68](https://linux-hardware.org/?probe=7a4ab56f68) | Sep 10, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [10c0154577](https://linux-hardware.org/?probe=10c0154577) | Sep 10, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b95c1b013e](https://linux-hardware.org/?probe=b95c1b013e) | Sep 10, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [bbdd0a3b8c](https://linux-hardware.org/?probe=bbdd0a3b8c) | Sep 10, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2377281799](https://linux-hardware.org/?probe=2377281799) | Sep 09, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [13d65a1a4e](https://linux-hardware.org/?probe=13d65a1a4e) | Sep 09, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c2b2ebce62](https://linux-hardware.org/?probe=c2b2ebce62) | Sep 09, 2021 |
| ASUSTek       | X540NA                      | Notebook    | [f14257cc20](https://linux-hardware.org/?probe=f14257cc20) | Sep 09, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8433dfbbb9](https://linux-hardware.org/?probe=8433dfbbb9) | Sep 09, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [3fa68fe391](https://linux-hardware.org/?probe=3fa68fe391) | Sep 09, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8bc230f7dc](https://linux-hardware.org/?probe=8bc230f7dc) | Sep 09, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fb3d977ed2](https://linux-hardware.org/?probe=fb3d977ed2) | Sep 09, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [488fd18d85](https://linux-hardware.org/?probe=488fd18d85) | Sep 09, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [19d6905d9a](https://linux-hardware.org/?probe=19d6905d9a) | Sep 09, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [1ff67401db](https://linux-hardware.org/?probe=1ff67401db) | Sep 09, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [7add887914](https://linux-hardware.org/?probe=7add887914) | Sep 08, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5c6f3696b2](https://linux-hardware.org/?probe=5c6f3696b2) | Sep 08, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [0baa540bf5](https://linux-hardware.org/?probe=0baa540bf5) | Sep 08, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d21daec9ea](https://linux-hardware.org/?probe=d21daec9ea) | Sep 08, 2021 |
| Lenovo        | ThinkPad T430 2349D10       | Notebook    | [11ab5d413d](https://linux-hardware.org/?probe=11ab5d413d) | Sep 08, 2021 |
| Foxconn       | nT-A3000 series FAB         | Desktop     | [9e22d6dc70](https://linux-hardware.org/?probe=9e22d6dc70) | Sep 08, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [f8aae7ade2](https://linux-hardware.org/?probe=f8aae7ade2) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a826f2f4c9](https://linux-hardware.org/?probe=a826f2f4c9) | Sep 08, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [5aa6e46608](https://linux-hardware.org/?probe=5aa6e46608) | Sep 08, 2021 |
| Lenovo        | ThinkPad X230 2325B12       | Notebook    | [a55f42da78](https://linux-hardware.org/?probe=a55f42da78) | Sep 08, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [2626e29c5f](https://linux-hardware.org/?probe=2626e29c5f) | Sep 08, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [04ecb299d9](https://linux-hardware.org/?probe=04ecb299d9) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [b521805956](https://linux-hardware.org/?probe=b521805956) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [c4f6c7da11](https://linux-hardware.org/?probe=c4f6c7da11) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a4acb4b4d7](https://linux-hardware.org/?probe=a4acb4b4d7) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [33ae3adcc6](https://linux-hardware.org/?probe=33ae3adcc6) | Sep 08, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [cb2158566c](https://linux-hardware.org/?probe=cb2158566c) | Sep 08, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [65e545345d](https://linux-hardware.org/?probe=65e545345d) | Sep 07, 2021 |
| ASUSTek       | K52F                        | Notebook    | [b1f04036d8](https://linux-hardware.org/?probe=b1f04036d8) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | Notebook    | [19cfc85441](https://linux-hardware.org/?probe=19cfc85441) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [55f595b53f](https://linux-hardware.org/?probe=55f595b53f) | Sep 07, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [41ab6b2f21](https://linux-hardware.org/?probe=41ab6b2f21) | Sep 07, 2021 |
| ASUSTek       | K52F                        | Notebook    | [0d72cf73ac](https://linux-hardware.org/?probe=0d72cf73ac) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | Notebook    | [498dd20152](https://linux-hardware.org/?probe=498dd20152) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6fc35e97d8](https://linux-hardware.org/?probe=6fc35e97d8) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [5acaf42867](https://linux-hardware.org/?probe=5acaf42867) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [4d6ad821df](https://linux-hardware.org/?probe=4d6ad821df) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [511d2e120b](https://linux-hardware.org/?probe=511d2e120b) | Sep 07, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [13256468d1](https://linux-hardware.org/?probe=13256468d1) | Sep 07, 2021 |
| ASUSTek       | P5Q3                        | Desktop     | [3f08e7bf37](https://linux-hardware.org/?probe=3f08e7bf37) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [bcd1f7553d](https://linux-hardware.org/?probe=bcd1f7553d) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [0c0ccb21d8](https://linux-hardware.org/?probe=0c0ccb21d8) | Sep 07, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [cf59508b79](https://linux-hardware.org/?probe=cf59508b79) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [1c85c31f57](https://linux-hardware.org/?probe=1c85c31f57) | Sep 07, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [0183fb8d78](https://linux-hardware.org/?probe=0183fb8d78) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [6cf8ebc24c](https://linux-hardware.org/?probe=6cf8ebc24c) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [bf328adcb8](https://linux-hardware.org/?probe=bf328adcb8) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [09e28c958c](https://linux-hardware.org/?probe=09e28c958c) | Sep 07, 2021 |
| HP            | 212A                        | Desktop     | [7f51e384f7](https://linux-hardware.org/?probe=7f51e384f7) | Sep 07, 2021 |
| HP            | 212A                        | Desktop     | [c89a2196ab](https://linux-hardware.org/?probe=c89a2196ab) | Sep 07, 2021 |
| Dell          | Latitude 7480               | Notebook    | [844ab8df38](https://linux-hardware.org/?probe=844ab8df38) | Sep 06, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [9256f3fece](https://linux-hardware.org/?probe=9256f3fece) | Sep 06, 2021 |
| ASUSTek       | STRIX B250H GAMING          | Desktop     | [265822ee2e](https://linux-hardware.org/?probe=265822ee2e) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [7f6c0d6337](https://linux-hardware.org/?probe=7f6c0d6337) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [e6ea97df06](https://linux-hardware.org/?probe=e6ea97df06) | Sep 06, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [a0d1d9b2e6](https://linux-hardware.org/?probe=a0d1d9b2e6) | Sep 06, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [4aec08beef](https://linux-hardware.org/?probe=4aec08beef) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [3aedb68952](https://linux-hardware.org/?probe=3aedb68952) | Sep 06, 2021 |
| Samsung       | NC10                        | Notebook    | [98ba59d155](https://linux-hardware.org/?probe=98ba59d155) | Sep 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e42726b566](https://linux-hardware.org/?probe=e42726b566) | Sep 06, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [b6e28c84c8](https://linux-hardware.org/?probe=b6e28c84c8) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2a4adea555](https://linux-hardware.org/?probe=2a4adea555) | Sep 05, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [28c59930e4](https://linux-hardware.org/?probe=28c59930e4) | Sep 05, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [20f947223f](https://linux-hardware.org/?probe=20f947223f) | Sep 05, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [fe8833475a](https://linux-hardware.org/?probe=fe8833475a) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [0a1850f760](https://linux-hardware.org/?probe=0a1850f760) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [4ba7363e9e](https://linux-hardware.org/?probe=4ba7363e9e) | Sep 05, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [18fe596fba](https://linux-hardware.org/?probe=18fe596fba) | Sep 04, 2021 |
| HP            | Presario CQ62               | Notebook    | [4cdec89015](https://linux-hardware.org/?probe=4cdec89015) | Sep 04, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [af5a140c2e](https://linux-hardware.org/?probe=af5a140c2e) | Sep 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [9e235c4228](https://linux-hardware.org/?probe=9e235c4228) | Sep 04, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [0e32e6945b](https://linux-hardware.org/?probe=0e32e6945b) | Sep 03, 2021 |
| ASRock        | TRX40 Creator               | Desktop     | [0734c9bbd0](https://linux-hardware.org/?probe=0734c9bbd0) | Sep 03, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [db35296aa1](https://linux-hardware.org/?probe=db35296aa1) | Sep 03, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [fafd031d1f](https://linux-hardware.org/?probe=fafd031d1f) | Sep 03, 2021 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [ced0e47579](https://linux-hardware.org/?probe=ced0e47579) | Sep 02, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1449c0a9cd](https://linux-hardware.org/?probe=1449c0a9cd) | Sep 02, 2021 |
| ASUSTek       | UX303LNB                    | Notebook    | [e0756d7ae6](https://linux-hardware.org/?probe=e0756d7ae6) | Sep 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5d183d4587](https://linux-hardware.org/?probe=5d183d4587) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [666c4fef08](https://linux-hardware.org/?probe=666c4fef08) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [d6ee033eb7](https://linux-hardware.org/?probe=d6ee033eb7) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [28fbb3d82d](https://linux-hardware.org/?probe=28fbb3d82d) | Sep 02, 2021 |
| ECS           | G31T-M9                     | Desktop     | [0757de543d](https://linux-hardware.org/?probe=0757de543d) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [27c2ebc917](https://linux-hardware.org/?probe=27c2ebc917) | Sep 02, 2021 |
| Gigabyte      | 8I945P-G                    | Desktop     | [a1eb33a5f1](https://linux-hardware.org/?probe=a1eb33a5f1) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [1d9e3a7503](https://linux-hardware.org/?probe=1d9e3a7503) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [97c9e2dc1f](https://linux-hardware.org/?probe=97c9e2dc1f) | Sep 02, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d4c78cc3c4](https://linux-hardware.org/?probe=d4c78cc3c4) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ca0e00bc0f](https://linux-hardware.org/?probe=ca0e00bc0f) | Sep 01, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | Notebook    | [f1cad98694](https://linux-hardware.org/?probe=f1cad98694) | Sep 01, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [e96ab5fb39](https://linux-hardware.org/?probe=e96ab5fb39) | Sep 01, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [78fafc3314](https://linux-hardware.org/?probe=78fafc3314) | Sep 01, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [d542a6b8f9](https://linux-hardware.org/?probe=d542a6b8f9) | Sep 01, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [d8083308fc](https://linux-hardware.org/?probe=d8083308fc) | Sep 01, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [12a5a0f9c5](https://linux-hardware.org/?probe=12a5a0f9c5) | Sep 01, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [450ffd830c](https://linux-hardware.org/?probe=450ffd830c) | Sep 01, 2021 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [dadb397ef1](https://linux-hardware.org/?probe=dadb397ef1) | Sep 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3267eec643](https://linux-hardware.org/?probe=3267eec643) | Sep 01, 2021 |
| Pegatron      | TRUCKEE                     | Desktop     | [68f16e9542](https://linux-hardware.org/?probe=68f16e9542) | Sep 01, 2021 |
| Dell          | 094MXG A00                  | All in one  | [7fe3c46d72](https://linux-hardware.org/?probe=7fe3c46d72) | Sep 01, 2021 |
| Timi          | TM1613                      | Notebook    | [f25eeca060](https://linux-hardware.org/?probe=f25eeca060) | Sep 01, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | Notebook    | [bc224fb15f](https://linux-hardware.org/?probe=bc224fb15f) | Aug 31, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [9510c18df6](https://linux-hardware.org/?probe=9510c18df6) | Aug 31, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [6521e0d6be](https://linux-hardware.org/?probe=6521e0d6be) | Aug 31, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [783955d696](https://linux-hardware.org/?probe=783955d696) | Aug 31, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | Notebook    | [db94fcaf10](https://linux-hardware.org/?probe=db94fcaf10) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [9c31643811](https://linux-hardware.org/?probe=9c31643811) | Aug 31, 2021 |
| ASUSTek       | P7P55D-E                    | Desktop     | [4c05b36e94](https://linux-hardware.org/?probe=4c05b36e94) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [baf38e8736](https://linux-hardware.org/?probe=baf38e8736) | Aug 31, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [33a45018fc](https://linux-hardware.org/?probe=33a45018fc) | Aug 31, 2021 |
| Pine Micro... | Pine64+                     | Soc         | [433d54a30d](https://linux-hardware.org/?probe=433d54a30d) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [37c3e457bc](https://linux-hardware.org/?probe=37c3e457bc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [0d38048f46](https://linux-hardware.org/?probe=0d38048f46) | Aug 31, 2021 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [d7eaf975a0](https://linux-hardware.org/?probe=d7eaf975a0) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [df9b303eec](https://linux-hardware.org/?probe=df9b303eec) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [d9af23fb86](https://linux-hardware.org/?probe=d9af23fb86) | Aug 31, 2021 |
| AOpen         | D1001 C26361-D1001          | Desktop     | [e27239d870](https://linux-hardware.org/?probe=e27239d870) | Aug 31, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [1470c8cc7f](https://linux-hardware.org/?probe=1470c8cc7f) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [ba7144c0dc](https://linux-hardware.org/?probe=ba7144c0dc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [7204a77b38](https://linux-hardware.org/?probe=7204a77b38) | Aug 31, 2021 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [b26e82328a](https://linux-hardware.org/?probe=b26e82328a) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [70835c3aa7](https://linux-hardware.org/?probe=70835c3aa7) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [3e22f55c7b](https://linux-hardware.org/?probe=3e22f55c7b) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b73b366bb6](https://linux-hardware.org/?probe=b73b366bb6) | Aug 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [c6a754129a](https://linux-hardware.org/?probe=c6a754129a) | Aug 30, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [e1b2dc4810](https://linux-hardware.org/?probe=e1b2dc4810) | Aug 30, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e94ab065a3](https://linux-hardware.org/?probe=e94ab065a3) | Aug 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [a251dca266](https://linux-hardware.org/?probe=a251dca266) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [b1425fa900](https://linux-hardware.org/?probe=b1425fa900) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b5a84f215b](https://linux-hardware.org/?probe=b5a84f215b) | Aug 30, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [f2dbdea931](https://linux-hardware.org/?probe=f2dbdea931) | Aug 30, 2021 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [b7b3f489f2](https://linux-hardware.org/?probe=b7b3f489f2) | Aug 30, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [ca46b71791](https://linux-hardware.org/?probe=ca46b71791) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [d255f48a39](https://linux-hardware.org/?probe=d255f48a39) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [dc0abe4fcd](https://linux-hardware.org/?probe=dc0abe4fcd) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [fc61c24624](https://linux-hardware.org/?probe=fc61c24624) | Aug 30, 2021 |
| Dell          | Latitude E6330              | Notebook    | [95d65375e2](https://linux-hardware.org/?probe=95d65375e2) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [9d1b86643e](https://linux-hardware.org/?probe=9d1b86643e) | Aug 30, 2021 |
| Lenovo        | ThinkPad T61 7661BF3        | Notebook    | [69b6d76471](https://linux-hardware.org/?probe=69b6d76471) | Aug 30, 2021 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [acbb96ba48](https://linux-hardware.org/?probe=acbb96ba48) | Aug 29, 2021 |
| ASUSTek       | K56CB                       | Notebook    | [1a44fc7e8f](https://linux-hardware.org/?probe=1a44fc7e8f) | Aug 29, 2021 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [6fcfbde79d](https://linux-hardware.org/?probe=6fcfbde79d) | Aug 29, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [17ae4593ea](https://linux-hardware.org/?probe=17ae4593ea) | Aug 28, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b9595196ea](https://linux-hardware.org/?probe=b9595196ea) | Aug 28, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [8625d6f2f1](https://linux-hardware.org/?probe=8625d6f2f1) | Aug 28, 2021 |
| Jetway        | 1.0                         | Desktop     | [9c4b8ad466](https://linux-hardware.org/?probe=9c4b8ad466) | Aug 28, 2021 |
| HP            | 0B50 Rev.A                  | All in one  | [4701ae6e71](https://linux-hardware.org/?probe=4701ae6e71) | Aug 27, 2021 |
| MSI           | B150A GAMING PRO            | Desktop     | [06de6cd826](https://linux-hardware.org/?probe=06de6cd826) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [46eacf8d5c](https://linux-hardware.org/?probe=46eacf8d5c) | Aug 27, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [202fe67100](https://linux-hardware.org/?probe=202fe67100) | Aug 27, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [321f53f711](https://linux-hardware.org/?probe=321f53f711) | Aug 27, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [06f4334a82](https://linux-hardware.org/?probe=06f4334a82) | Aug 27, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [d215521170](https://linux-hardware.org/?probe=d215521170) | Aug 27, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [2c85ec0205](https://linux-hardware.org/?probe=2c85ec0205) | Aug 27, 2021 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [7f3a68dd2a](https://linux-hardware.org/?probe=7f3a68dd2a) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [2737cfb67d](https://linux-hardware.org/?probe=2737cfb67d) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [dc9428d8b4](https://linux-hardware.org/?probe=dc9428d8b4) | Aug 27, 2021 |
| Lenovo        | ThinkPad T440p 20AN006GU... | Notebook    | [bca7704bb0](https://linux-hardware.org/?probe=bca7704bb0) | Aug 27, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [14747d88b3](https://linux-hardware.org/?probe=14747d88b3) | Aug 26, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [87904cbe92](https://linux-hardware.org/?probe=87904cbe92) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1c2e910793](https://linux-hardware.org/?probe=1c2e910793) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4a69118897](https://linux-hardware.org/?probe=4a69118897) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [474216fba9](https://linux-hardware.org/?probe=474216fba9) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [76d9383f33](https://linux-hardware.org/?probe=76d9383f33) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [213d3f817b](https://linux-hardware.org/?probe=213d3f817b) | Aug 26, 2021 |
| HP            | 0B0Ch                       | Desktop     | [b5933fde35](https://linux-hardware.org/?probe=b5933fde35) | Aug 26, 2021 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [8c051a0ce9](https://linux-hardware.org/?probe=8c051a0ce9) | Aug 26, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [f26ade88cd](https://linux-hardware.org/?probe=f26ade88cd) | Aug 26, 2021 |
| Dell          | 0WR7PY A00                  | Desktop     | [cb25b1811b](https://linux-hardware.org/?probe=cb25b1811b) | Aug 26, 2021 |
| Gigabyte      | AORUS 15G KB                | Notebook    | [6afefe68d7](https://linux-hardware.org/?probe=6afefe68d7) | Aug 26, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [8dd8862b4b](https://linux-hardware.org/?probe=8dd8862b4b) | Aug 26, 2021 |
| HP            | ProBook 4530s               | Notebook    | [2b4cab4d7c](https://linux-hardware.org/?probe=2b4cab4d7c) | Aug 25, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [7bab6dd9db](https://linux-hardware.org/?probe=7bab6dd9db) | Aug 25, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [a2f161dee0](https://linux-hardware.org/?probe=a2f161dee0) | Aug 25, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [e1e5a14c77](https://linux-hardware.org/?probe=e1e5a14c77) | Aug 25, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [16f399259c](https://linux-hardware.org/?probe=16f399259c) | Aug 25, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [d37f13917f](https://linux-hardware.org/?probe=d37f13917f) | Aug 25, 2021 |
| ASRock        | C2750D4I                    | Desktop     | [6daa3c26bf](https://linux-hardware.org/?probe=6daa3c26bf) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0a79171c9e](https://linux-hardware.org/?probe=0a79171c9e) | Aug 25, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [feed9e2921](https://linux-hardware.org/?probe=feed9e2921) | Aug 25, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [3da8591ac6](https://linux-hardware.org/?probe=3da8591ac6) | Aug 25, 2021 |
| HP            | 630                         | Notebook    | [004d2b364d](https://linux-hardware.org/?probe=004d2b364d) | Aug 25, 2021 |
| Biostar       | Hi-Fi A85W                  | Desktop     | [ffb66dafd4](https://linux-hardware.org/?probe=ffb66dafd4) | Aug 25, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [b06c4079a7](https://linux-hardware.org/?probe=b06c4079a7) | Aug 25, 2021 |
| Dell          | Latitude 7490               | Notebook    | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2882cf9963](https://linux-hardware.org/?probe=2882cf9963) | Aug 25, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [557d74beb9](https://linux-hardware.org/?probe=557d74beb9) | Aug 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [65d82bc8e7](https://linux-hardware.org/?probe=65d82bc8e7) | Aug 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [e1bd0ec7fd](https://linux-hardware.org/?probe=e1bd0ec7fd) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [e5c92fe4ad](https://linux-hardware.org/?probe=e5c92fe4ad) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8a72f87e7b](https://linux-hardware.org/?probe=8a72f87e7b) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [441b8b892e](https://linux-hardware.org/?probe=441b8b892e) | Aug 24, 2021 |
| ASRock        | P4i65G                      | Desktop     | [43ce3e711f](https://linux-hardware.org/?probe=43ce3e711f) | Aug 24, 2021 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [c2179206a9](https://linux-hardware.org/?probe=c2179206a9) | Aug 24, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [1f257714a9](https://linux-hardware.org/?probe=1f257714a9) | Aug 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [102aea0211](https://linux-hardware.org/?probe=102aea0211) | Aug 24, 2021 |
| Unknown       | 1.0                         | Desktop     | [5e638360a8](https://linux-hardware.org/?probe=5e638360a8) | Aug 24, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f755838fd8](https://linux-hardware.org/?probe=f755838fd8) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5cc74103a8](https://linux-hardware.org/?probe=5cc74103a8) | Aug 24, 2021 |
| HP            | 250 G4                      | Notebook    | [5d47aa9804](https://linux-hardware.org/?probe=5d47aa9804) | Aug 24, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [77ce457de4](https://linux-hardware.org/?probe=77ce457de4) | Aug 24, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [df0fa8e968](https://linux-hardware.org/?probe=df0fa8e968) | Aug 24, 2021 |
| ASUSTek       | GA35DX                      | Desktop     | [3843ea048e](https://linux-hardware.org/?probe=3843ea048e) | Aug 24, 2021 |
| Sony          | VPCF115FM                   | Notebook    | [9f9abf79b2](https://linux-hardware.org/?probe=9f9abf79b2) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8a88eabb1c](https://linux-hardware.org/?probe=8a88eabb1c) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c4ecd51a21](https://linux-hardware.org/?probe=c4ecd51a21) | Aug 23, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [1c9d3bb8b4](https://linux-hardware.org/?probe=1c9d3bb8b4) | Aug 23, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [e92004f46a](https://linux-hardware.org/?probe=e92004f46a) | Aug 23, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [14af647cc5](https://linux-hardware.org/?probe=14af647cc5) | Aug 23, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [06c9a1ed3a](https://linux-hardware.org/?probe=06c9a1ed3a) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5bc9372587](https://linux-hardware.org/?probe=5bc9372587) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8bcb9e62e1](https://linux-hardware.org/?probe=8bcb9e62e1) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [6c44c4f7e3](https://linux-hardware.org/?probe=6c44c4f7e3) | Aug 23, 2021 |
| Google        | Enguarde                    | Notebook    | [12a2003770](https://linux-hardware.org/?probe=12a2003770) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [7f190e4ed2](https://linux-hardware.org/?probe=7f190e4ed2) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2db5cafda3](https://linux-hardware.org/?probe=2db5cafda3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [abcab36e0c](https://linux-hardware.org/?probe=abcab36e0c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f3ccb91568](https://linux-hardware.org/?probe=f3ccb91568) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [0d8fa16f47](https://linux-hardware.org/?probe=0d8fa16f47) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [680e8106ec](https://linux-hardware.org/?probe=680e8106ec) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c18b0215e9](https://linux-hardware.org/?probe=c18b0215e9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fcc821b941](https://linux-hardware.org/?probe=fcc821b941) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [59f760dbb9](https://linux-hardware.org/?probe=59f760dbb9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e22a8e2ea4](https://linux-hardware.org/?probe=e22a8e2ea4) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4fc69342da](https://linux-hardware.org/?probe=4fc69342da) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f2fcae5696](https://linux-hardware.org/?probe=f2fcae5696) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2f823b2f52](https://linux-hardware.org/?probe=2f823b2f52) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [adf5b71331](https://linux-hardware.org/?probe=adf5b71331) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [618c1c7838](https://linux-hardware.org/?probe=618c1c7838) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [0dff1056d5](https://linux-hardware.org/?probe=0dff1056d5) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fb0cf0a7a3](https://linux-hardware.org/?probe=fb0cf0a7a3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6b9f550210](https://linux-hardware.org/?probe=6b9f550210) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4b22440e91](https://linux-hardware.org/?probe=4b22440e91) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6bab7cdc7c](https://linux-hardware.org/?probe=6bab7cdc7c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [d2a08022bd](https://linux-hardware.org/?probe=d2a08022bd) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f39d94cf1b](https://linux-hardware.org/?probe=f39d94cf1b) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e35bbfda2d](https://linux-hardware.org/?probe=e35bbfda2d) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [60170675ca](https://linux-hardware.org/?probe=60170675ca) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [64a6aa27db](https://linux-hardware.org/?probe=64a6aa27db) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [06b1dab7a0](https://linux-hardware.org/?probe=06b1dab7a0) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [cec5c36945](https://linux-hardware.org/?probe=cec5c36945) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6f38e35f9a](https://linux-hardware.org/?probe=6f38e35f9a) | Aug 23, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [06234ebe05](https://linux-hardware.org/?probe=06234ebe05) | Aug 23, 2021 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [3c03ce796f](https://linux-hardware.org/?probe=3c03ce796f) | Aug 23, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [73b14ecca0](https://linux-hardware.org/?probe=73b14ecca0) | Aug 23, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [4a647bfabc](https://linux-hardware.org/?probe=4a647bfabc) | Aug 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [e70b15e489](https://linux-hardware.org/?probe=e70b15e489) | Aug 22, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [ebe40b3244](https://linux-hardware.org/?probe=ebe40b3244) | Aug 22, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d98bdb0d1c](https://linux-hardware.org/?probe=d98bdb0d1c) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [d688bffa01](https://linux-hardware.org/?probe=d688bffa01) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [3d52884b6e](https://linux-hardware.org/?probe=3d52884b6e) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | Notebook    | [57b847b12c](https://linux-hardware.org/?probe=57b847b12c) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | Notebook    | [db4b9878fa](https://linux-hardware.org/?probe=db4b9878fa) | Aug 22, 2021 |
| Dell          | Inspiron 6000               | Notebook    | [67c6b36361](https://linux-hardware.org/?probe=67c6b36361) | Aug 22, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [eea45758b7](https://linux-hardware.org/?probe=eea45758b7) | Aug 22, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [dfed5d8b7a](https://linux-hardware.org/?probe=dfed5d8b7a) | Aug 21, 2021 |
| HP            | 085Ch                       | Desktop     | [2e649d07a0](https://linux-hardware.org/?probe=2e649d07a0) | Aug 21, 2021 |
| Dell          | Latitude E7470              | Notebook    | [e954672cb2](https://linux-hardware.org/?probe=e954672cb2) | Aug 21, 2021 |
| HP            | 085Ch                       | Desktop     | [c5b36c5187](https://linux-hardware.org/?probe=c5b36c5187) | Aug 21, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [4d43bca615](https://linux-hardware.org/?probe=4d43bca615) | Aug 21, 2021 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [0f9abf9c63](https://linux-hardware.org/?probe=0f9abf9c63) | Aug 21, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [7f83e1b3c8](https://linux-hardware.org/?probe=7f83e1b3c8) | Aug 21, 2021 |
| HP            | 14s-dq2003nw                | Notebook    | [f4dcd70da5](https://linux-hardware.org/?probe=f4dcd70da5) | Aug 21, 2021 |
| Lenovo        | ThinkPad E570 20H500B4GE    | Notebook    | [be964b556b](https://linux-hardware.org/?probe=be964b556b) | Aug 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [5ecdc39ac1](https://linux-hardware.org/?probe=5ecdc39ac1) | Aug 21, 2021 |
| ASUSTek       | P5B SE                      | Desktop     | [81634fcb22](https://linux-hardware.org/?probe=81634fcb22) | Aug 21, 2021 |
| Dell          | Precision 7520              | Notebook    | [372d627a69](https://linux-hardware.org/?probe=372d627a69) | Aug 21, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [e59c9482f6](https://linux-hardware.org/?probe=e59c9482f6) | Aug 21, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [daa01f79aa](https://linux-hardware.org/?probe=daa01f79aa) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [a96a7ada4f](https://linux-hardware.org/?probe=a96a7ada4f) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c8305c0d4c](https://linux-hardware.org/?probe=c8305c0d4c) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [77359352d0](https://linux-hardware.org/?probe=77359352d0) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5312257240](https://linux-hardware.org/?probe=5312257240) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [75e262ddba](https://linux-hardware.org/?probe=75e262ddba) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [bd216572a3](https://linux-hardware.org/?probe=bd216572a3) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e57aeadfef](https://linux-hardware.org/?probe=e57aeadfef) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [7211565d4a](https://linux-hardware.org/?probe=7211565d4a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [1c490522df](https://linux-hardware.org/?probe=1c490522df) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [16f0b9c14a](https://linux-hardware.org/?probe=16f0b9c14a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [691bb379e5](https://linux-hardware.org/?probe=691bb379e5) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fe880ac0c8](https://linux-hardware.org/?probe=fe880ac0c8) | Aug 20, 2021 |
| Supermicro    | X10SLM-F                    | Server      | [801ee74858](https://linux-hardware.org/?probe=801ee74858) | Aug 20, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [a5a146e42a](https://linux-hardware.org/?probe=a5a146e42a) | Aug 20, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [580838bf3c](https://linux-hardware.org/?probe=580838bf3c) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [cba7d82942](https://linux-hardware.org/?probe=cba7d82942) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [62068f391f](https://linux-hardware.org/?probe=62068f391f) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c60ef3fa1e](https://linux-hardware.org/?probe=c60ef3fa1e) | Aug 20, 2021 |
| Supermicro    | X10DRW-iT                   | Server      | [aaeee85be7](https://linux-hardware.org/?probe=aaeee85be7) | Aug 20, 2021 |
| Timi          | TM1612                      | Notebook    | [485caf5846](https://linux-hardware.org/?probe=485caf5846) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [c980f2d201](https://linux-hardware.org/?probe=c980f2d201) | Aug 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [2a61705899](https://linux-hardware.org/?probe=2a61705899) | Aug 20, 2021 |
| Dell          | 0Y2K8N A01                  | Desktop     | [6b0fd02c91](https://linux-hardware.org/?probe=6b0fd02c91) | Aug 20, 2021 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [17c70c7886](https://linux-hardware.org/?probe=17c70c7886) | Aug 19, 2021 |
| SLIMBOOK      | TITAN                       | Notebook    | [a2abd981d1](https://linux-hardware.org/?probe=a2abd981d1) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1ce6738560](https://linux-hardware.org/?probe=1ce6738560) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [e134a1f7c3](https://linux-hardware.org/?probe=e134a1f7c3) | Aug 19, 2021 |
| HP            | 339A                        | Desktop     | [57d5bbd1e4](https://linux-hardware.org/?probe=57d5bbd1e4) | Aug 19, 2021 |
| RuggedPC      | Caterpillar T20             | Tablet      | [1bf2275be4](https://linux-hardware.org/?probe=1bf2275be4) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [87fa430aab](https://linux-hardware.org/?probe=87fa430aab) | Aug 19, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2151b5cdae](https://linux-hardware.org/?probe=2151b5cdae) | Aug 19, 2021 |
| HP            | 1587h                       | Desktop     | [3ddbdb3101](https://linux-hardware.org/?probe=3ddbdb3101) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [0489699bc4](https://linux-hardware.org/?probe=0489699bc4) | Aug 19, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [cc54b8955c](https://linux-hardware.org/?probe=cc54b8955c) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [757e261c56](https://linux-hardware.org/?probe=757e261c56) | Aug 19, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [df15656fce](https://linux-hardware.org/?probe=df15656fce) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c989eac16b](https://linux-hardware.org/?probe=c989eac16b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [3169e477dd](https://linux-hardware.org/?probe=3169e477dd) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5fcb7fdb26](https://linux-hardware.org/?probe=5fcb7fdb26) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [7afbba35b0](https://linux-hardware.org/?probe=7afbba35b0) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [f1d159bbd1](https://linux-hardware.org/?probe=f1d159bbd1) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [38e8211556](https://linux-hardware.org/?probe=38e8211556) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [bd587e5998](https://linux-hardware.org/?probe=bd587e5998) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [3fa54711ec](https://linux-hardware.org/?probe=3fa54711ec) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [4a7f287161](https://linux-hardware.org/?probe=4a7f287161) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6f5485edfc](https://linux-hardware.org/?probe=6f5485edfc) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [fed5f28778](https://linux-hardware.org/?probe=fed5f28778) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [0ba8599928](https://linux-hardware.org/?probe=0ba8599928) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [e31d43b39d](https://linux-hardware.org/?probe=e31d43b39d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [703cdcf766](https://linux-hardware.org/?probe=703cdcf766) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [9b8ce55c3d](https://linux-hardware.org/?probe=9b8ce55c3d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2b4af51f46](https://linux-hardware.org/?probe=2b4af51f46) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b802b4a25b](https://linux-hardware.org/?probe=b802b4a25b) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [cb421b796b](https://linux-hardware.org/?probe=cb421b796b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [f6c7230675](https://linux-hardware.org/?probe=f6c7230675) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [7116839a4b](https://linux-hardware.org/?probe=7116839a4b) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [04817bfb7f](https://linux-hardware.org/?probe=04817bfb7f) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [1fce0ab0e8](https://linux-hardware.org/?probe=1fce0ab0e8) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [92b401a705](https://linux-hardware.org/?probe=92b401a705) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [f2a438a9be](https://linux-hardware.org/?probe=f2a438a9be) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c9239b499b](https://linux-hardware.org/?probe=c9239b499b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b708a97ef1](https://linux-hardware.org/?probe=b708a97ef1) | Aug 18, 2021 |
| Lenovo        | Board                       | Desktop     | [3de8569fe7](https://linux-hardware.org/?probe=3de8569fe7) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [31dc792a8b](https://linux-hardware.org/?probe=31dc792a8b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [76a48b344d](https://linux-hardware.org/?probe=76a48b344d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [244aba47d4](https://linux-hardware.org/?probe=244aba47d4) | Aug 18, 2021 |
| ASUSTek       | H81M-R                      | Desktop     | [8598ad2248](https://linux-hardware.org/?probe=8598ad2248) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [b2391216c6](https://linux-hardware.org/?probe=b2391216c6) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [53b311c24c](https://linux-hardware.org/?probe=53b311c24c) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [61de56951c](https://linux-hardware.org/?probe=61de56951c) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [7fd7f1ea77](https://linux-hardware.org/?probe=7fd7f1ea77) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [2a090f8b2a](https://linux-hardware.org/?probe=2a090f8b2a) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [62e4ff915a](https://linux-hardware.org/?probe=62e4ff915a) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [eada085a33](https://linux-hardware.org/?probe=eada085a33) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [474e20b9f2](https://linux-hardware.org/?probe=474e20b9f2) | Aug 18, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [61b641914c](https://linux-hardware.org/?probe=61b641914c) | Aug 18, 2021 |
| ASUSTek       | B150M-K                     | Desktop     | [3f706a2a69](https://linux-hardware.org/?probe=3f706a2a69) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [9f3381d34c](https://linux-hardware.org/?probe=9f3381d34c) | Aug 18, 2021 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [85cfabd795](https://linux-hardware.org/?probe=85cfabd795) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [765f5d340e](https://linux-hardware.org/?probe=765f5d340e) | Aug 18, 2021 |
| ASRock        | J4205-ITX                   | Desktop     | [30de75d2c8](https://linux-hardware.org/?probe=30de75d2c8) | Aug 18, 2021 |
| ASUSTek       | UX305CA                     | Notebook    | [6ab6beca67](https://linux-hardware.org/?probe=6ab6beca67) | Aug 18, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [c7155dfa07](https://linux-hardware.org/?probe=c7155dfa07) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [451fe761a6](https://linux-hardware.org/?probe=451fe761a6) | Aug 18, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [b2ed4bc6fe](https://linux-hardware.org/?probe=b2ed4bc6fe) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [dd0de8b832](https://linux-hardware.org/?probe=dd0de8b832) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [a6ac2782a6](https://linux-hardware.org/?probe=a6ac2782a6) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [d32e974941](https://linux-hardware.org/?probe=d32e974941) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [fe90c1da98](https://linux-hardware.org/?probe=fe90c1da98) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c3d98780bf](https://linux-hardware.org/?probe=c3d98780bf) | Aug 17, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [4b38b9e598](https://linux-hardware.org/?probe=4b38b9e598) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2c30321150](https://linux-hardware.org/?probe=2c30321150) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2f6317ebc5](https://linux-hardware.org/?probe=2f6317ebc5) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [707606ff5e](https://linux-hardware.org/?probe=707606ff5e) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [0c43bb89c0](https://linux-hardware.org/?probe=0c43bb89c0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fcb540b848](https://linux-hardware.org/?probe=fcb540b848) | Aug 17, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [46240d5ef9](https://linux-hardware.org/?probe=46240d5ef9) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6e85db6058](https://linux-hardware.org/?probe=6e85db6058) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2e26440865](https://linux-hardware.org/?probe=2e26440865) | Aug 17, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [5ad65197ad](https://linux-hardware.org/?probe=5ad65197ad) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c185e120f1](https://linux-hardware.org/?probe=c185e120f1) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [ee22c0dcc0](https://linux-hardware.org/?probe=ee22c0dcc0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [b3fd5bee39](https://linux-hardware.org/?probe=b3fd5bee39) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [d68e571cd0](https://linux-hardware.org/?probe=d68e571cd0) | Aug 17, 2021 |
| Dell          | Latitude 7480               | Notebook    | [49272ed382](https://linux-hardware.org/?probe=49272ed382) | Aug 17, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [be9383850e](https://linux-hardware.org/?probe=be9383850e) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [28c2f85e9c](https://linux-hardware.org/?probe=28c2f85e9c) | Aug 17, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-8-amd64             | 960       | 30.98%  |
| 5.10.0-10-amd64            | 535       | 17.26%  |
| 5.10.0-7-amd64             | 401       | 12.94%  |
| 5.10.0-9-amd64             | 318       | 10.26%  |
| 5.10.0-11-amd64            | 181       | 5.84%   |
| 5.10.0-2-amd64             | 106       | 3.42%   |
| 5.10.0-12-amd64            | 56        | 1.81%   |
| 5.10.0-6-amd64             | 46        | 1.48%   |
| 5.15.0-2-amd64             | 35        | 1.13%   |
| 5.14.0-0.bpo.2-amd64       | 23        | 0.74%   |
| 5.10.0-13-amd64            | 23        | 0.74%   |
| 5.10.0-8-arm64             | 18        | 0.58%   |
| 5.10.0-8-686-pae           | 14        | 0.45%   |
| 5.10.0-3-amd64             | 14        | 0.45%   |
| 5.13.19-2-pve              | 12        | 0.39%   |
| 5.10.92-v8+                | 12        | 0.39%   |
| 5.10.0-9-686-pae           | 11        | 0.35%   |
| 5.10.0-9-686               | 11        | 0.35%   |
| 5.15.0-0.bpo.2-amd64       | 10        | 0.32%   |
| 5.10.0-4-amd64             | 10        | 0.32%   |
| 5.10.0-13-686-pae          | 10        | 0.32%   |
| 5.15.0-3-amd64             | 8         | 0.26%   |
| 5.11.22-4-pve              | 8         | 0.26%   |
| 5.10.0-5-amd64             | 8         | 0.26%   |
| 5.10.0-10-686-pae          | 8         | 0.26%   |
| 5.15.0-0.bpo.3-amd64       | 7         | 0.23%   |
| 5.10.0-8-686               | 7         | 0.23%   |
| 5.13.19-3-pve              | 6         | 0.19%   |
| 5.13.19-1-pve              | 6         | 0.19%   |
| 5.10.63-v8+                | 6         | 0.19%   |
| 5.10.0-11-686-pae          | 6         | 0.19%   |
| 5.10.0-1-amd64             | 6         | 0.19%   |
| 5.15.0-1-amd64             | 5         | 0.16%   |
| 5.13.19-4-pve              | 5         | 0.16%   |
| 5.11.22-5-pve              | 5         | 0.16%   |
| 5.11.22-1-pve              | 5         | 0.16%   |
| 5.16.0-5-amd64             | 4         | 0.13%   |
| 5.16.0-1-amd64             | 4         | 0.13%   |
| 5.10-sunxi64               | 4         | 0.13%   |
| 5.9.0-arm-64               | 3         | 0.1%    |
| 5.16.0-3-amd64             | 3         | 0.1%    |
| 5.14.0-4mx-amd64           | 3         | 0.1%    |
| 5.13.0-13.1-liquorix-amd64 | 3         | 0.1%    |
| 5.12.0-19.3-liquorix-amd64 | 3         | 0.1%    |
| 5.11.22-2-pve              | 3         | 0.1%    |
| 5.10.60-sunxi              | 3         | 0.1%    |
| 5.10.103-v8+               | 3         | 0.1%    |
| 5.10.0-8-rt-amd64          | 3         | 0.1%    |
| 5.10.0-8-armmp-lpae        | 3         | 0.1%    |
| 5.10.0-11-686              | 3         | 0.1%    |
| 5.10.0-10-686              | 3         | 0.1%    |
| 5.14.0-3mx-amd64           | 2         | 0.06%   |
| 5.14.0-2-amd64             | 2         | 0.06%   |
| 5.13.19-6-pve              | 2         | 0.06%   |
| 5.13.13                    | 2         | 0.06%   |
| 5.11.22-7-pve              | 2         | 0.06%   |
| 5.11.22-3-pve              | 2         | 0.06%   |
| 5.10.81+truenas            | 2         | 0.06%   |
| 5.10.42+truenas            | 2         | 0.06%   |
| 4.19.0-6-amd64             | 2         | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version   | Computers | Percent |
|-----------|-----------|---------|
| 5.10.0    | 2657      | 89.43%  |
| 5.15.0    | 69        | 2.32%   |
| 5.14.0    | 38        | 1.28%   |
| 5.13.19   | 29        | 0.98%   |
| 5.11.22   | 25        | 0.84%   |
| 5.16.0    | 19        | 0.64%   |
| 5.10.92   | 12        | 0.4%    |
| 4.19.0    | 10        | 0.34%   |
| 5.13.0    | 7         | 0.24%   |
| 5.10.63   | 7         | 0.24%   |
| 5.12.0    | 5         | 0.17%   |
| 5.11.0    | 4         | 0.13%   |
| 5.10      | 4         | 0.13%   |
| 5.9.0     | 3         | 0.1%    |
| 5.13.8    | 3         | 0.1%    |
| 5.13.13   | 3         | 0.1%    |
| 5.10.60   | 3         | 0.1%    |
| 5.10.103  | 3         | 0.1%    |
| 5.4.0     | 2         | 0.07%   |
| 5.15.11   | 2         | 0.07%   |
| 5.14.6    | 2         | 0.07%   |
| 5.14.21   | 2         | 0.07%   |
| 5.13.4    | 2         | 0.07%   |
| 5.11.15   | 2         | 0.07%   |
| 5.10.81   | 2         | 0.07%   |
| 5.10.42   | 2         | 0.07%   |
| 5.10.10   | 2         | 0.07%   |
| 5.1.0     | 2         | 0.07%   |
| 5.8.0     | 1         | 0.03%   |
| 5.4.18    | 1         | 0.03%   |
| 5.4.148   | 1         | 0.03%   |
| 5.16.5    | 1         | 0.03%   |
| 5.16.15   | 1         | 0.03%   |
| 5.16.14   | 1         | 0.03%   |
| 5.15.8    | 1         | 0.03%   |
| 5.15.7    | 1         | 0.03%   |
| 5.15.6.1  | 1         | 0.03%   |
| 5.15.30   | 1         | 0.03%   |
| 5.15.3    | 1         | 0.03%   |
| 5.15.27   | 1         | 0.03%   |
| 5.15.17   | 1         | 0.03%   |
| 5.15.13   | 1         | 0.03%   |
| 5.14.9    | 1         | 0.03%   |
| 5.14.7    | 1         | 0.03%   |
| 5.14.12.1 | 1         | 0.03%   |
| 5.13.5    | 1         | 0.03%   |
| 5.13.3    | 1         | 0.03%   |
| 5.13.18   | 1         | 0.03%   |
| 5.13.15   | 1         | 0.03%   |
| 5.13.1    | 1         | 0.03%   |
| 5.12.4    | 1         | 0.03%   |
| 5.12.18   | 1         | 0.03%   |
| 5.12.14   | 1         | 0.03%   |
| 5.12.10   | 1         | 0.03%   |
| 5.12.1    | 1         | 0.03%   |
| 5.11.9    | 1         | 0.03%   |
| 5.11.14   | 1         | 0.03%   |
| 5.10.93   | 1         | 0.03%   |
| 5.10.78   | 1         | 0.03%   |
| 5.10.70   | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 2701      | 91.03%  |
| 5.15    | 77        | 2.6%    |
| 5.13    | 48        | 1.62%   |
| 5.14    | 44        | 1.48%   |
| 5.11    | 33        | 1.11%   |
| 5.16    | 21        | 0.71%   |
| 4.19    | 12        | 0.4%    |
| 5.12    | 10        | 0.34%   |
| 5.4     | 4         | 0.13%   |
| 5       | 4         | 0.13%   |
| 5.9     | 3         | 0.1%    |
| 5.1     | 3         | 0.1%    |
| 4.4     | 2         | 0.07%   |
| 5.8     | 1         | 0.03%   |
| 5.15.6  | 1         | 0.03%   |
| 5.14.12 | 1         | 0.03%   |
| 4.9     | 1         | 0.03%   |
| 3.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2787      | 94.96%  |
| i686    | 80        | 2.73%   |
| aarch64 | 57        | 1.94%   |
| armv7l  | 11        | 0.37%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 1371      | 46.24%  |
| GNOME            | 565       | 19.06%  |
| KDE5             | 302       | 10.19%  |
| XFCE             | 250       | 8.43%   |
| MATE             | 97        | 3.27%   |
| LXDE             | 72        | 2.43%   |
| X-Cinnamon       | 69        | 2.33%   |
| Cinnamon         | 57        | 1.92%   |
| i3               | 33        | 1.11%   |
| KDE              | 32        | 1.08%   |
| LXQt             | 26        | 0.88%   |
| lightdm-xsession | 21        | 0.71%   |
| Openbox          | 15        | 0.51%   |
| GNOME Flashback  | 15        | 0.51%   |
| trinity          | 11        | 0.37%   |
| GNOME Classic    | 6         | 0.2%    |
| Budgie           | 5         | 0.17%   |
| awesome          | 4         | 0.13%   |
| sway             | 3         | 0.1%    |
| Enlightenment    | 2         | 0.07%   |
| DWM              | 2         | 0.07%   |
| wmaker-common    | 1         | 0.03%   |
| UKUI             | 1         | 0.03%   |
| ICEWM            | 1         | 0.03%   |
| GNUstep          | 1         | 0.03%   |
| default          | 1         | 0.03%   |
| Deepin           | 1         | 0.03%   |
| Cutefish         | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1192      | 40.27%  |
| X11     | 1163      | 39.29%  |
| Wayland | 396       | 13.38%  |
| Tty     | 209       | 7.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1658      | 56.11%  |
| GDM     | 461       | 15.6%   |
| LightDM | 354       | 11.98%  |
| SDDM    | 289       | 9.78%   |
| TDM     | 153       | 5.18%   |
| GDM3    | 24        | 0.81%   |
| SLiM    | 8         | 0.27%   |
| XDM     | 5         | 0.17%   |
| NODM    | 2         | 0.07%   |
| KDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 766       | 25.97%  |
| Unknown     | 752       | 25.5%   |
| ru_RU       | 483       | 16.38%  |
| de_DE       | 138       | 4.68%   |
| en_GB       | 120       | 4.07%   |
| fr_FR       | 97        | 3.29%   |
| es_ES       | 73        | 2.48%   |
| pt_BR       | 66        | 2.24%   |
| it_IT       | 56        | 1.9%    |
| pl_PL       | 49        | 1.66%   |
| en_AU       | 26        | 0.88%   |
| en_CA       | 25        | 0.85%   |
| es_MX       | 21        | 0.71%   |
| C           | 18        | 0.61%   |
| zh_CN       | 15        | 0.51%   |
| hu_HU       | 15        | 0.51%   |
| es_AR       | 13        | 0.44%   |
| ja_JP       | 12        | 0.41%   |
| es_VE       | 11        | 0.37%   |
| en_IN       | 11        | 0.37%   |
| de_AT       | 11        | 0.37%   |
| sv_SE       | 10        | 0.34%   |
| pt_PT       | 9         | 0.31%   |
| nl_NL       | 9         | 0.31%   |
| de_CH       | 8         | 0.27%   |
| uk_UA       | 7         | 0.24%   |
| tr_TR       | 7         | 0.24%   |
| es_CL       | 7         | 0.24%   |
| en_ZA       | 7         | 0.24%   |
| en_IE       | 7         | 0.24%   |
| ru_UA       | 6         | 0.2%    |
| nl_BE       | 6         | 0.2%    |
| es_CO       | 6         | 0.2%    |
| cs_CZ       | 6         | 0.2%    |
| hr_HR       | 4         | 0.14%   |
| fi_FI       | 4         | 0.14%   |
| es_EC       | 4         | 0.14%   |
| bg_BG       | 4         | 0.14%   |
| nn_NO       | 3         | 0.1%    |
| fr_CA       | 3         | 0.1%    |
| fr_BE       | 3         | 0.1%    |
| en_SG       | 3         | 0.1%    |
| en_NZ       | 3         | 0.1%    |
| en_HK       | 3         | 0.1%    |
| en_DK       | 3         | 0.1%    |
| ca_ES       | 3         | 0.1%    |
| zh_TW       | 2         | 0.07%   |
| sk_SK       | 2         | 0.07%   |
| ro_RO       | 2         | 0.07%   |
| nb_NO       | 2         | 0.07%   |
| fr_CH       | 2         | 0.07%   |
| et_EE       | 2         | 0.07%   |
| es_US       | 2         | 0.07%   |
| es_PE       | 2         | 0.07%   |
| da_DK       | 2         | 0.07%   |
| sr_RS       | 1         | 0.03%   |
| sl_SI       | 1         | 0.03%   |
| ko_KR       | 1         | 0.03%   |
| ja_JP.utf-8 | 1         | 0.03%   |
| gl_ES       | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1762      | 59.45%  |
| BIOS | 1202      | 40.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1564      | 53.23%  |
| Overlay | 1214      | 41.32%  |
| Btrfs   | 88        | 3%      |
| Zfs     | 31        | 1.06%   |
| Xfs     | 20        | 0.68%   |
| Ext3    | 7         | 0.24%   |
| Tmpfs   | 4         | 0.14%   |
| Ext2    | 4         | 0.14%   |
| Unknown | 4         | 0.14%   |
| Rootfs  | 2         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1803      | 60.77%  |
| MBR     | 780       | 26.29%  |
| Unknown | 384       | 12.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2326      | 78.87%  |
| Yes       | 623       | 21.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2083      | 70.56%  |
| Yes       | 869       | 29.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 542       | 18.48%  |
| Lenovo                  | 492       | 16.77%  |
| ASUSTek Computer        | 380       | 12.96%  |
| Hewlett-Packard         | 272       | 9.27%   |
| Dell                    | 233       | 7.94%   |
| Gigabyte Technology     | 166       | 5.66%   |
| ASRock                  | 116       | 3.95%   |
| MSI                     | 115       | 3.92%   |
| Acer                    | 99        | 3.38%   |
| Intel                   | 57        | 1.94%   |
| Google                  | 52        | 1.77%   |
| Raspberry Pi Foundation | 42        | 1.43%   |
| ECS                     | 29        | 0.99%   |
| Aquarius                | 21        | 0.72%   |
| Unknown                 | 21        | 0.72%   |
| Samsung Electronics     | 19        | 0.65%   |
| Fujitsu                 | 19        | 0.65%   |
| Supermicro              | 17        | 0.58%   |
| Toshiba                 | 16        | 0.55%   |
| Foxconn                 | 15        | 0.51%   |
| Sony                    | 13        | 0.44%   |
| HUAWEI                  | 11        | 0.38%   |
| Notebook                | 8         | 0.27%   |
| Pegatron                | 7         | 0.24%   |
| Packard Bell            | 6         | 0.2%    |
| Fujitsu Siemens         | 6         | 0.2%    |
| AMI                     | 6         | 0.2%    |
| Timi                    | 5         | 0.17%   |
| sunxi                   | 5         | 0.17%   |
| Microsoft               | 5         | 0.17%   |
| Medion                  | 5         | 0.17%   |
| IBM                     | 5         | 0.17%   |
| ASRockRack              | 5         | 0.17%   |
| ZOTAC                   | 4         | 0.14%   |
| Positivo                | 4         | 0.14%   |
| Pine Microsystems       | 4         | 0.14%   |
| Hardkernel              | 4         | 0.14%   |
| Clevo                   | 4         | 0.14%   |
| Biostar                 | 4         | 0.14%   |
| TUXEDO                  | 3         | 0.1%    |
| Shuttle                 | 3         | 0.1%    |
| Huanan                  | 3         | 0.1%    |
| HPE                     | 3         | 0.1%    |
| Chuwi                   | 3         | 0.1%    |
| AZW                     | 3         | 0.1%    |
| System76                | 2         | 0.07%   |
| SLIMBOOK                | 2         | 0.07%   |
| Semp Toshiba            | 2         | 0.07%   |
| Phytium                 | 2         | 0.07%   |
| PC Specialist           | 2         | 0.07%   |
| Panasonic               | 2         | 0.07%   |
| LG Electronics          | 2         | 0.07%   |
| Jumper                  | 2         | 0.07%   |
| GPU Company             | 2         | 0.07%   |
| CompuLab                | 2         | 0.07%   |
| Compal                  | 2         | 0.07%   |
| AXDIA International     | 2         | 0.07%   |
| YJKC                    | 1         | 0.03%   |
| Xunlong                 | 1         | 0.03%   |
| UNOWHY                  | 1         | 0.03%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 285       | 9.72%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 110       | 3.75%   |
| Apple MacBookAir7,1                       | 75        | 2.56%   |
| Apple MacBookAir7,2                       | 69        | 2.35%   |
| ASUS All Series                           | 53        | 1.81%   |
| Apple MacBook2,1                          | 52        | 1.77%   |
| Google Enguarde                           | 47        | 1.6%    |
| Unknown                                   | 26        | 0.89%   |
| RPi Raspberry Pi                          | 23        | 0.78%   |
| Lenovo ThinkPad E475 20H40006US           | 23        | 0.78%   |
| Apple MacBook4,1                          | 21        | 0.72%   |
| ASRock H470M-HVS                          | 20        | 0.68%   |
| Aquarius NS585                            | 20        | 0.68%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.55%   |
| ECS H61H2-M13                             | 15        | 0.51%   |
| ASUS PRIME H510M-A                        | 15        | 0.51%   |
| Acer Aspire A315-23                       | 15        | 0.51%   |
| Gigabyte H81M-S2V                         | 11        | 0.38%   |
| ASUS P8H61-M LX3 R2.0                     | 11        | 0.38%   |
| ECS G31T-M9                               | 9         | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 8         | 0.27%   |
| MSI MS-7996                               | 8         | 0.27%   |
| MSI MS-7817                               | 8         | 0.27%   |
| HP Pavilion g6                            | 7         | 0.24%   |
| HP EliteBook 8460p                        | 7         | 0.24%   |
| Fujitsu ESPRIMO P720                      | 7         | 0.24%   |
| Dell OptiPlex 7010                        | 7         | 0.24%   |
| ASUS P8H67-M                              | 7         | 0.24%   |
| ASUS P8H61-M LX3 PLUS R2.0                | 7         | 0.24%   |
| Supermicro Super Server                   | 6         | 0.2%    |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 6         | 0.2%    |
| HP Pavilion Gaming Laptop 15-ec1xxx       | 6         | 0.2%    |
| HP Laptop 15-db1xxx                       | 6         | 0.2%    |
| Dell XPS 13 9310                          | 6         | 0.2%    |
| Dell Inspiron 5100                        | 6         | 0.2%    |
| ASUS S20 K29                              | 6         | 0.2%    |
| ASUS PRIME B450M-A                        | 6         | 0.2%    |
| ASUS PRIME A320M-K                        | 6         | 0.2%    |
| ASRock H61M-VG4                           | 6         | 0.2%    |
| Apple MacBook7,1                          | 6         | 0.2%    |
| HP Pavilion Gaming Laptop 15-ec2xxx       | 5         | 0.17%   |
| HP Laptop 15-db0xxx                       | 5         | 0.17%   |
| Gigabyte H61M-DS2 REV 1.2                 | 5         | 0.17%   |
| Gigabyte B360M H                          | 5         | 0.17%   |
| Dell Latitude 7480                        | 5         | 0.17%   |
| ASRock G31M-VS2                           | 5         | 0.17%   |
| MSI MS-7C56                               | 4         | 0.14%   |
| MSI MS-7721                               | 4         | 0.14%   |
| Lenovo IdeaPad L340-15API 81LW            | 4         | 0.14%   |
| Lenovo B50-30 20382                       | 4         | 0.14%   |
| Intel Pro, Std, Elt Series                | 4         | 0.14%   |
| HP Z620 Workstation                       | 4         | 0.14%   |
| HP Z420 Workstation                       | 4         | 0.14%   |
| HP Notebook                               | 4         | 0.14%   |
| HP Laptop 15-bw0xx                        | 4         | 0.14%   |
| HP Compaq nx6110 (PZ065UA#ABA)            | 4         | 0.14%   |
| Gigabyte B85M-D3H                         | 4         | 0.14%   |
| Gigabyte B550I AORUS PRO AX               | 4         | 0.14%   |
| Dell Latitude E6420                       | 4         | 0.14%   |
| ASUS X555LD                               | 4         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 342       | 11.66%  |
| Apple MacBook5        | 285       | 9.72%   |
| Apple MacBookAir7     | 144       | 4.91%   |
| Dell Inspiron         | 69        | 2.35%   |
| Acer Aspire           | 69        | 2.35%   |
| ASUS PRIME            | 59        | 2.01%   |
| Lenovo IdeaPad        | 57        | 1.94%   |
| ASUS All              | 53        | 1.81%   |
| Apple MacBook2        | 52        | 1.77%   |
| Dell Latitude         | 50        | 1.7%    |
| Google Enguarde       | 47        | 1.6%    |
| RPi Raspberry         | 42        | 1.43%   |
| HP Pavilion           | 42        | 1.43%   |
| HP Laptop             | 35        | 1.19%   |
| HP EliteBook          | 33        | 1.13%   |
| HP Compaq             | 31        | 1.06%   |
| HP ProBook            | 29        | 0.99%   |
| Dell OptiPlex         | 28        | 0.95%   |
| Dell XPS              | 27        | 0.92%   |
| Dell Precision        | 26        | 0.89%   |
| Unknown               | 26        | 0.89%   |
| ASUS ROG              | 23        | 0.78%   |
| ASUS P8H61-M          | 22        | 0.75%   |
| Apple MacBook4        | 21        | 0.72%   |
| Lenovo ThinkCentre    | 20        | 0.68%   |
| ASRock H470M-HVS      | 20        | 0.68%   |
| Aquarius NS585        | 20        | 0.68%   |
| ASUS TUF              | 19        | 0.65%   |
| ECS H61H2-M13         | 15        | 0.51%   |
| ASUS ZenBook          | 15        | 0.51%   |
| Toshiba Satellite     | 14        | 0.48%   |
| Dell Vostro           | 14        | 0.48%   |
| Gigabyte H81M-S2V     | 11        | 0.38%   |
| Dell PowerEdge        | 11        | 0.38%   |
| Gigabyte B450M        | 10        | 0.34%   |
| ASUS VivoBook         | 10        | 0.34%   |
| Lenovo Yoga           | 9         | 0.31%   |
| HP ZBook              | 9         | 0.31%   |
| HP EliteDesk          | 9         | 0.31%   |
| HP 250                | 9         | 0.31%   |
| Fujitsu ESPRIMO       | 9         | 0.31%   |
| ECS G31T-M9           | 9         | 0.31%   |
| ASUS P8H67-M          | 9         | 0.31%   |
| Acer TravelMate       | 9         | 0.31%   |
| MSI MS-7996           | 8         | 0.27%   |
| MSI MS-7817           | 8         | 0.27%   |
| HP ProLiant           | 7         | 0.24%   |
| Gigabyte H61M-DS2     | 7         | 0.24%   |
| ASUS Pro              | 7         | 0.24%   |
| ASUS ASUS             | 7         | 0.24%   |
| Supermicro Super      | 6         | 0.2%    |
| HP ENVY               | 6         | 0.2%    |
| Fujitsu LIFEBOOK      | 6         | 0.2%    |
| ASUS S20              | 6         | 0.2%    |
| ASRock H61M-VG4       | 6         | 0.2%    |
| ASRock B450M          | 6         | 0.2%    |
| ASRock B450           | 6         | 0.2%    |
| Apple MacBook7        | 6         | 0.2%    |
| Acer Swift            | 6         | 0.2%    |
| Packard Bell EasyNote | 5         | 0.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 387       | 13.19%  |
| 2009    | 377       | 12.85%  |
| 2016    | 237       | 8.08%   |
| 2021    | 231       | 7.88%   |
| 2019    | 216       | 7.36%   |
| 2012    | 204       | 6.96%   |
| 2018    | 198       | 6.75%   |
| 2011    | 160       | 5.46%   |
| 2017    | 154       | 5.25%   |
| 2013    | 152       | 5.18%   |
| 2014    | 122       | 4.16%   |
| 2015    | 113       | 3.85%   |
| 2007    | 94        | 3.2%    |
| 2010    | 92        | 3.14%   |
| 2008    | 90        | 3.07%   |
| Unknown | 59        | 2.01%   |
| 2005    | 19        | 0.65%   |
| 2006    | 13        | 0.44%   |
| 2003    | 9         | 0.31%   |
| 2004    | 3         | 0.1%    |
| 2022    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |
| 2001    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1657      | 56.5%   |
| Desktop        | 956       | 32.59%  |
| Convertible    | 142       | 4.84%   |
| System on chip | 60        | 2.05%   |
| Mini pc        | 43        | 1.47%   |
| Server         | 37        | 1.26%   |
| All in one     | 20        | 0.68%   |
| Tablet         | 15        | 0.51%   |
| Phone          | 3         | 0.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2781      | 94.56%  |
| Enabled  | 160       | 5.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2877      | 98.09%  |
| Yes  | 56        | 1.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 653       | 22.16%  |
| 16.01-24.0      | 539       | 18.29%  |
| 3.01-4.0        | 531       | 18.02%  |
| 1.01-2.0        | 438       | 14.86%  |
| 8.01-16.0       | 347       | 11.77%  |
| 32.01-64.0      | 204       | 6.92%   |
| 64.01-256.0     | 79        | 2.68%   |
| 2.01-3.0        | 59        | 2%      |
| 0.51-1.0        | 45        | 1.53%   |
| 24.01-32.0      | 32        | 1.09%   |
| 0.01-0.5        | 12        | 0.41%   |
| More than 256.0 | 8         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1247      | 41.03%  |
| 0.51-1.0    | 563       | 18.53%  |
| 2.01-3.0    | 422       | 13.89%  |
| 4.01-8.0    | 314       | 10.33%  |
| 3.01-4.0    | 235       | 7.73%   |
| 0.01-0.5    | 122       | 4.01%   |
| 8.01-16.0   | 86        | 2.83%   |
| 16.01-24.0  | 25        | 0.82%   |
| 32.01-64.0  | 10        | 0.33%   |
| 24.01-32.0  | 10        | 0.33%   |
| 64.01-256.0 | 5         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2138      | 72.28%  |
| 2      | 475       | 16.06%  |
| 3      | 140       | 4.73%   |
| 4      | 83        | 2.81%   |
| 5      | 40        | 1.35%   |
| 0      | 22        | 0.74%   |
| 6      | 19        | 0.64%   |
| 8      | 13        | 0.44%   |
| 7      | 12        | 0.41%   |
| 10     | 5         | 0.17%   |
| 9      | 3         | 0.1%    |
| 28     | 2         | 0.07%   |
| 13     | 2         | 0.07%   |
| 12     | 2         | 0.07%   |
| 11     | 2         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1872      | 63.76%  |
| Yes       | 1064      | 36.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2493      | 84.97%  |
| No        | 441       | 15.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2090      | 71.11%  |
| No        | 849       | 28.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1794      | 60.94%  |
| No        | 1150      | 39.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1030      | 35.06%  |
| Russia       | 490       | 16.68%  |
| Germany      | 198       | 6.74%   |
| France       | 129       | 4.39%   |
| Spain        | 91        | 3.1%    |
| Brazil       | 82        | 2.79%   |
| UK           | 70        | 2.38%   |
| Italy        | 68        | 2.31%   |
| Poland       | 67        | 2.28%   |
| Switzerland  | 47        | 1.6%    |
| Ukraine      | 42        | 1.43%   |
| Canada       | 40        | 1.36%   |
| Netherlands  | 35        | 1.19%   |
| Mexico       | 32        | 1.09%   |
| Australia    | 30        | 1.02%   |
| Sweden       | 29        | 0.99%   |
| Hungary      | 24        | 0.82%   |
| Austria      | 24        | 0.82%   |
| Argentina    | 24        | 0.82%   |
| China        | 23        | 0.78%   |
| Turkey       | 20        | 0.68%   |
| Czechia      | 19        | 0.65%   |
| Portugal     | 18        | 0.61%   |
| Belgium      | 18        | 0.61%   |
| Norway       | 15        | 0.51%   |
| Japan        | 15        | 0.51%   |
| India        | 14        | 0.48%   |
| Venezuela    | 12        | 0.41%   |
| Bulgaria     | 12        | 0.41%   |
| Romania      | 10        | 0.34%   |
| Finland      | 10        | 0.34%   |
| Croatia      | 9         | 0.31%   |
| Chile        | 9         | 0.31%   |
| Belarus      | 9         | 0.31%   |
| Indonesia    | 8         | 0.27%   |
| Greece       | 8         | 0.27%   |
| Colombia     | 8         | 0.27%   |
| South Africa | 7         | 0.24%   |
| Pakistan     | 7         | 0.24%   |
| Ecuador      | 7         | 0.24%   |
| Slovenia     | 6         | 0.2%    |
| Singapore    | 6         | 0.2%    |
| Morocco      | 6         | 0.2%    |
| Kazakhstan   | 6         | 0.2%    |
| Thailand     | 5         | 0.17%   |
| Latvia       | 5         | 0.17%   |
| Ireland      | 5         | 0.17%   |
| Denmark      | 5         | 0.17%   |
| Bangladesh   | 5         | 0.17%   |
| Slovakia     | 4         | 0.14%   |
| New Zealand  | 4         | 0.14%   |
| Vietnam      | 3         | 0.1%    |
| Taiwan       | 3         | 0.1%    |
| Saudi Arabia | 3         | 0.1%    |
| Philippines  | 3         | 0.1%    |
| Israel       | 3         | 0.1%    |
| Iran         | 3         | 0.1%    |
| Hong Kong    | 3         | 0.1%    |
| Guatemala    | 3         | 0.1%    |
| Costa Rica   | 3         | 0.1%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangor            | 467       | 15.38%  |
| Voronezh          | 383       | 12.61%  |
| Portland          | 249       | 8.2%    |
| Dover-Foxcroft    | 49        | 1.61%   |
| Warsaw            | 29        | 0.95%   |
| St Petersburg     | 27        | 0.89%   |
| Paris             | 25        | 0.82%   |
| Eliot             | 24        | 0.79%   |
| Berlin            | 24        | 0.79%   |
| Zurich            | 21        | 0.69%   |
| MÃ¡laga         | 21        | 0.69%   |
| Moscow            | 16        | 0.53%   |
| London            | 15        | 0.49%   |
| Vienna            | 13        | 0.43%   |
| Sao Paulo         | 13        | 0.43%   |
| Lyon              | 13        | 0.43%   |
| Milan             | 12        | 0.4%    |
| Barcelona         | 12        | 0.4%    |
| Prague            | 11        | 0.36%   |
| Kyiv              | 10        | 0.33%   |
| Amsterdam         | 10        | 0.33%   |
| Munich            | 9         | 0.3%    |
| Hampden           | 9         | 0.3%    |
| Frankfort         | 9         | 0.3%    |
| Valencia          | 8         | 0.26%   |
| Stockholm         | 8         | 0.26%   |
| Sofia             | 8         | 0.26%   |
| Madrid            | 8         | 0.26%   |
| Istanbul          | 8         | 0.26%   |
| Hamburg           | 8         | 0.26%   |
| Zagreb            | 7         | 0.23%   |
| Perm              | 7         | 0.23%   |
| Melbourne         | 7         | 0.23%   |
| Sydney            | 6         | 0.2%    |
| Ocala             | 6         | 0.2%    |
| Manchester        | 6         | 0.2%    |
| Leipzig           | 6         | 0.2%    |
| Leimen            | 6         | 0.2%    |
| Budapest          | 6         | 0.2%    |
| Athens            | 6         | 0.2%    |
| Toronto           | 5         | 0.16%   |
| Singapore         | 5         | 0.16%   |
| San Jose          | 5         | 0.16%   |
| Rome              | 5         | 0.16%   |
| Oslo              | 5         | 0.16%   |
| Mesa              | 5         | 0.16%   |
| Lahore            | 5         | 0.16%   |
| Kalamazoo         | 5         | 0.16%   |
| Iasi              | 5         | 0.16%   |
| Helsinki          | 5         | 0.16%   |
| Frankfurt am Main | 5         | 0.16%   |
| Bengaluru         | 5         | 0.16%   |
| Bangkok           | 5         | 0.16%   |
| Yekaterinburg     | 4         | 0.13%   |
| Vladivostok       | 4         | 0.13%   |
| Turin             | 4         | 0.13%   |
| Toulouse          | 4         | 0.13%   |
| The Hague         | 4         | 0.13%   |
| Sunnyvale         | 4         | 0.13%   |
| Sevastopol        | 4         | 0.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 613       | 791    | 15.87%  |
| WDC                 | 504       | 754    | 13.05%  |
| Seagate             | 490       | 756    | 12.68%  |
| Toshiba             | 317       | 438    | 8.21%   |
| Kingston            | 221       | 257    | 5.72%   |
| Fujitsu             | 221       | 228    | 5.72%   |
| Unknown             | 182       | 237    | 4.71%   |
| Apple               | 160       | 188    | 4.14%   |
| Crucial             | 148       | 177    | 3.83%   |
| Hitachi             | 126       | 144    | 3.26%   |
| SanDisk             | 119       | 144    | 3.08%   |
| Intel               | 86        | 101    | 2.23%   |
| SK Hynix            | 70        | 83     | 1.81%   |
| A-DATA Technology   | 66        | 86     | 1.71%   |
| HGST                | 47        | 64     | 1.22%   |
| Micron Technology   | 41        | 42     | 1.06%   |
| China               | 26        | 29     | 0.67%   |
| Netac               | 25        | 57     | 0.65%   |
| SABRENT             | 24        | 25     | 0.62%   |
| KIOXIA              | 20        | 23     | 0.52%   |
| Transcend           | 19        | 21     | 0.49%   |
| SPCC                | 17        | 19     | 0.44%   |
| PNY                 | 15        | 18     | 0.39%   |
| Phison              | 14        | 18     | 0.36%   |
| Intenso             | 14        | 21     | 0.36%   |
| Patriot             | 12        | 13     | 0.31%   |
| LITEON              | 12        | 13     | 0.31%   |
| JMicron             | 12        | 12     | 0.31%   |
| Silicon Motion      | 11        | 12     | 0.28%   |
| GOODRAM             | 11        | 17     | 0.28%   |
| Hewlett-Packard     | 10        | 19     | 0.26%   |
| Corsair             | 10        | 13     | 0.26%   |
| Unknown             | 10        | 10     | 0.26%   |
| XPG                 | 9         | 11     | 0.23%   |
| MAXTOR              | 9         | 12     | 0.23%   |
| OCZ                 | 8         | 11     | 0.21%   |
| Gigabyte Technology | 8         | 9      | 0.21%   |
| Team                | 7         | 8      | 0.18%   |
| LITEONIT            | 7         | 8      | 0.18%   |
| Lexar               | 6         | 8      | 0.16%   |
| Apacer              | 6         | 6      | 0.16%   |
| Lenovo              | 5         | 7      | 0.13%   |
| Xinhaike            | 4         | 6      | 0.1%    |
| Union Memory        | 4         | 4      | 0.1%    |
| SSSTC               | 4         | 4      | 0.1%    |
| PLEXTOR             | 4         | 6      | 0.1%    |
| Mushkin             | 4         | 4      | 0.1%    |
| KIOXIA-EXCERIA      | 4         | 4      | 0.1%    |
| Hikvision           | 4         | 4      | 0.1%    |
| Hajaan              | 4         | 5      | 0.1%    |
| FOXLINE             | 4         | 4      | 0.1%    |
| UMIS                | 3         | 3      | 0.08%   |
| Phison Electronics  | 3         | 4      | 0.08%   |
| ASMT                | 3         | 4      | 0.08%   |
| ZTC                 | 2         | 6      | 0.05%   |
| USB3.0              | 2         | 2      | 0.05%   |
| T-FORCE             | 2         | 2      | 0.05%   |
| Solid State Storage | 2         | 2      | 0.05%   |
| Realtek             | 2         | 2      | 0.05%   |
| Pioneer             | 2         | 2      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 185       | 4.41%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 111       | 2.65%   |
| Apple SSD AP0128H 121GB            | 75        | 1.79%   |
| Apple SSD SM0128G 121GB            | 68        | 1.62%   |
| Seagate ST500DM002-1BD142 500GB    | 46        | 1.1%    |
| Toshiba MK1655GSXF 160GB           | 44        | 1.05%   |
| Kingston SA400S37240G 240GB SSD    | 43        | 1.03%   |
| Kingston SA400S37120G 120GB SSD    | 42        | 1%      |
| Toshiba MK1653GSX 160GB            | 40        | 0.95%   |
| Samsung SSD 860 EVO 250GB          | 34        | 0.81%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 30        | 0.72%   |
| Seagate ST1000LM035-1RK172 1TB     | 30        | 0.72%   |
| Toshiba DT01ACA050 500GB           | 26        | 0.62%   |
| Unknown AGND3R  16GB               | 25        | 0.6%    |
| Toshiba HDWD110 1TB                | 25        | 0.6%    |
| Samsung SSD 860 EVO 500GB          | 24        | 0.57%   |
| SABRENT Disk 1TB                   | 24        | 0.57%   |
| Kingston SV300S37A120G 120GB SSD   | 24        | 0.57%   |
| Kingston SA400S37480G 480GB SSD    | 24        | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB     | 23        | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB       | 23        | 0.55%   |
| Samsung SSD 860 EVO 1TB            | 23        | 0.55%   |
| Samsung SSD 850 EVO 250GB          | 23        | 0.55%   |
| A-DATA SU800 512GB SSD             | 23        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB     | 20        | 0.48%   |
| Netac SSD 240GB                    | 20        | 0.48%   |
| Crucial CT500MX500SSD1 500GB       | 20        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB        | 20        | 0.48%   |
| Unknown HAG2e  16GB                | 19        | 0.45%   |
| Seagate ST2000DM008-2FR102 2TB     | 18        | 0.43%   |
| SanDisk SD8SBAT128G1122 128GB SSD  | 18        | 0.43%   |
| Toshiba DT01ACA100 1TB             | 17        | 0.41%   |
| Samsung SSD 870 EVO 500GB          | 17        | 0.41%   |
| WDC WD1600BUDT-63DPZY0 160GB       | 16        | 0.38%   |
| Unknown MMC Card  32GB             | 15        | 0.36%   |
| Toshiba MQ01ABF050 500GB           | 15        | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB     | 15        | 0.36%   |
| Samsung SSD 850 EVO 500GB          | 15        | 0.36%   |
| Crucial CT480BX500SSD1 480GB       | 15        | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 14        | 0.33%   |
| WDC WD10EZEX-08WN4A0 1TB           | 13        | 0.31%   |
| Hitachi HDS721050CLA362 500GB      | 13        | 0.31%   |
| Crucial CT240BX500SSD1 240GB       | 13        | 0.31%   |
| Toshiba MQ04ABF100 1TB             | 12        | 0.29%   |
| Seagate ST1000DM003-9YN162 1TB     | 11        | 0.26%   |
| SanDisk SSD PLUS 240GB             | 11        | 0.26%   |
| HGST HTS721010A9E630 1TB           | 11        | 0.26%   |
| Crucial CT120BX500SSD1 120GB       | 11        | 0.26%   |
| Unknown MMC Card  128GB            | 10        | 0.24%   |
| Toshiba DT01ACA200 2TB             | 10        | 0.24%   |
| Seagate ST980811AS 80GB            | 10        | 0.24%   |
| Seagate ST4000DM004-2CV104 4TB     | 10        | 0.24%   |
| Seagate ST250DM000-1BD141 250GB    | 10        | 0.24%   |
| Seagate ST1000DM003-1CH162 1TB     | 10        | 0.24%   |
| Kingston SUV400S37120G 120GB SSD   | 10        | 0.24%   |
| Hitachi HDS721050DLE630 500GB      | 10        | 0.24%   |
| Fujitsu MHY2120BH 120GB            | 10        | 0.24%   |
| Unknown                            | 10        | 0.24%   |
| WDC WD2500AAKX-00ERMA0 250GB       | 9         | 0.21%   |
| Unknown SD/MMC/MS PRO 32GB         | 9         | 0.21%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 479       | 735    | 29.46%  |
| WDC                 | 374       | 567    | 23%     |
| Toshiba             | 275       | 389    | 16.91%  |
| Fujitsu             | 221       | 228    | 13.59%  |
| Hitachi             | 126       | 144    | 7.75%   |
| HGST                | 47        | 64     | 2.89%   |
| Samsung Electronics | 35        | 40     | 2.15%   |
| SABRENT             | 24        | 25     | 1.48%   |
| Unknown             | 11        | 13     | 0.68%   |
| MAXTOR              | 8         | 8      | 0.49%   |
| Hewlett-Packard     | 5         | 12     | 0.31%   |
| Apple               | 4         | 6      | 0.25%   |
| JMicron             | 3         | 3      | 0.18%   |
| ASMT                | 2         | 3      | 0.12%   |
| USB3.0              | 1         | 1      | 0.06%   |
| SILICONMOTION       | 1         | 1      | 0.06%   |
| Pear 2TB            | 1         | 1      | 0.06%   |
| NAS                 | 1         | 5      | 0.06%   |
| Maxone              | 1         | 1      | 0.06%   |
| MaxDigital          | 1         | 2      | 0.06%   |
| MARSHAL             | 1         | 1      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| IBM/Hitachi         | 1         | 1      | 0.06%   |
| IBM-ESXS            | 1         | 2      | 0.06%   |
| asmedia             | 1         | 1      | 0.06%   |
| 128MB               | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 288       | 378    | 23.34%  |
| Kingston            | 194       | 227    | 15.72%  |
| Crucial             | 131       | 156    | 10.62%  |
| SanDisk             | 98        | 119    | 7.94%   |
| Apple               | 76        | 80     | 6.16%   |
| A-DATA Technology   | 53        | 63     | 4.29%   |
| WDC                 | 48        | 62     | 3.89%   |
| Intel               | 29        | 33     | 2.35%   |
| Netac               | 25        | 57     | 2.03%   |
| China               | 25        | 28     | 2.03%   |
| Micron Technology   | 20        | 21     | 1.62%   |
| Transcend           | 18        | 20     | 1.46%   |
| SK Hynix            | 16        | 18     | 1.3%    |
| Toshiba             | 14        | 16     | 1.13%   |
| SPCC                | 14        | 14     | 1.13%   |
| PNY                 | 13        | 16     | 1.05%   |
| Patriot             | 12        | 13     | 0.97%   |
| Intenso             | 11        | 13     | 0.89%   |
| GOODRAM             | 10        | 12     | 0.81%   |
| LITEON              | 9         | 10     | 0.73%   |
| OCZ                 | 8         | 11     | 0.65%   |
| Team                | 7         | 8      | 0.57%   |
| LITEONIT            | 7         | 8      | 0.57%   |
| Unknown             | 6         | 9      | 0.49%   |
| Lexar               | 6         | 8      | 0.49%   |
| Seagate             | 5         | 5      | 0.41%   |
| JMicron             | 5         | 5      | 0.41%   |
| Gigabyte Technology | 5         | 5      | 0.41%   |
| Apacer              | 5         | 5      | 0.41%   |
| Xinhaike            | 4         | 6      | 0.32%   |
| PLEXTOR             | 4         | 6      | 0.32%   |
| Mushkin             | 4         | 4      | 0.32%   |
| Hajaan              | 4         | 5      | 0.32%   |
| FOXLINE             | 4         | 4      | 0.32%   |
| Corsair             | 4         | 5      | 0.32%   |
| Unknown             | 4         | 4      | 0.32%   |
| ZTC                 | 2         | 6      | 0.16%   |
| Pioneer             | 2         | 2      | 0.16%   |
| LDLC                | 2         | 2      | 0.16%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.16%   |
| KingSpec            | 2         | 2      | 0.16%   |
| DOGFISH             | 2         | 2      | 0.16%   |
| WDC WDS             | 1         | 1      | 0.08%   |
| walram              | 1         | 1      | 0.08%   |
| Vaseky              | 1         | 2      | 0.08%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Union Memory        | 1         | 1      | 0.08%   |
| TrueNAS             | 1         | 1      | 0.08%   |
| TrekStor            | 1         | 1      | 0.08%   |
| Teclast             | 1         | 1      | 0.08%   |
| T-FORCE             | 1         | 1      | 0.08%   |
| Smartbuy            | 1         | 1      | 0.08%   |
| SMART               | 1         | 1      | 0.08%   |
| RDM-II              | 1         | 1      | 0.08%   |
| PNY USB             | 1         | 1      | 0.08%   |
| MyDigitalSSD        | 1         | 1      | 0.08%   |
| MAXTOR              | 1         | 4      | 0.08%   |
| Maximus             | 1         | 1      | 0.08%   |
| M4-CT256            | 1         | 1      | 0.08%   |
| Lenovo              | 1         | 1      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1433      | 2255   | 40.2%   |
| SSD     | 1113      | 1511   | 31.22%  |
| NVMe    | 813       | 1017   | 22.81%  |
| MMC     | 170       | 221    | 4.77%   |
| Unknown | 36        | 56     | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2150      | 3591   | 65.77%  |
| NVMe | 812       | 1014   | 24.84%  |
| MMC  | 170       | 221    | 5.2%    |
| SAS  | 137       | 234    | 4.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 1753      | 2294   | 65.95%  |
| 0.51-1.0    | 581       | 803    | 21.86%  |
| 1.01-2.0    | 159       | 250    | 5.98%   |
| 3.01-4.0    | 72        | 162    | 2.71%   |
| 4.01-10.0   | 50        | 142    | 1.88%   |
| 2.01-3.0    | 31        | 51     | 1.17%   |
| 10.01-20.0  | 11        | 60     | 0.41%   |
| 50.01-100.0 | 1         | 4      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 853       | 28.65%  |
| 101-250        | 663       | 22.27%  |
| 251-500        | 502       | 16.86%  |
| 501-1000       | 260       | 8.73%   |
| 1-20           | 171       | 5.74%   |
| 1001-2000      | 144       | 4.84%   |
| More than 3000 | 127       | 4.27%   |
| 51-100         | 124       | 4.17%   |
| 21-50          | 87        | 2.92%   |
| 2001-3000      | 46        | 1.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1032      | 34.24%  |
| Unknown        | 853       | 28.3%   |
| 21-50          | 249       | 8.26%   |
| 101-250        | 248       | 8.23%   |
| 51-100         | 213       | 7.07%   |
| 251-500        | 152       | 5.04%   |
| 501-1000       | 108       | 3.58%   |
| 1001-2000      | 60        | 1.99%   |
| More than 3000 | 59        | 1.96%   |
| 2001-3000      | 26        | 0.86%   |
| 0              | 14        | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB               | 19        | 19     | 4.63%   |
| WDC WD5000AAKX-60U6AA0 500GB                 | 17        | 19     | 4.15%   |
| Seagate ST500DM002-1BD142 500GB              | 11        | 11     | 2.68%   |
| Toshiba MK1653GSX 160GB                      | 9         | 9      | 2.2%    |
| Toshiba MK1655GSXF 160GB                     | 7         | 7      | 1.71%   |
| Hitachi HTS543216L9SA02 160GB                | 6         | 6      | 1.46%   |
| Seagate ST250DM000-1BD141 250GB              | 5         | 5      | 1.22%   |
| Seagate ST1000DM003-9YN162 1TB               | 5         | 6      | 1.22%   |
| Hitachi HTS542512K9SA00 120GB                | 5         | 6      | 1.22%   |
| Hitachi HDS721050DLE630 500GB                | 5         | 5      | 1.22%   |
| Hitachi HDS721050CLA362 500GB                | 5         | 5      | 1.22%   |
| WDC WD20EARS-00MVWB0 2TB                     | 4         | 4      | 0.98%   |
| WDC WD1600BUDT-63DPZY0 160GB                 | 4         | 4      | 0.98%   |
| Seagate ST9500325AS 500GB                    | 4         | 6      | 0.98%   |
| Kingston SV300S37A120G 120GB SSD             | 4         | 4      | 0.98%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 3         | 3      | 0.73%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 3         | 3      | 0.73%   |
| Seagate ST9500420AS 500GB                    | 3         | 3      | 0.73%   |
| Seagate ST500LT012-9WS142 500GB              | 3         | 3      | 0.73%   |
| Seagate ST31500341AS 1TB                     | 3         | 5      | 0.73%   |
| Seagate ST31000528AS 1TB                     | 3         | 3      | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 3         | 3      | 0.73%   |
| Kingston SHFS37A120G 120GB SSD               | 3         | 3      | 0.73%   |
| Hitachi HTS547575A9E384 752GB                | 3         | 3      | 0.73%   |
| HGST HTS725050A7E630 500GB                   | 3         | 3      | 0.73%   |
| WDC WD5000AAKX-08U6AA0 500GB                 | 2         | 2      | 0.49%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 2         | 3      | 0.49%   |
| WDC WD3200AAJS-08L7A0 320GB                  | 2         | 2      | 0.49%   |
| WDC WD2500AAJS-00B4A0 250GB                  | 2         | 2      | 0.49%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 2         | 2      | 0.49%   |
| Toshiba MQ04ABF100 1TB                       | 2         | 2      | 0.49%   |
| Toshiba MQ01ABF050 500GB                     | 2         | 2      | 0.49%   |
| SK Hynix PC711 HFS512GDE9X073N 512GB         | 2         | 2      | 0.49%   |
| SK Hynix HFS256G39MND-2300A 256GB SSD        | 2         | 2      | 0.49%   |
| Seagate ST980811AS 80GB                      | 2         | 2      | 0.49%   |
| Seagate ST94811A 40GB                        | 2         | 2      | 0.49%   |
| Seagate ST500LT012-1DG142 500GB              | 2         | 2      | 0.49%   |
| Seagate ST500LM000-SSHD-8GB                  | 2         | 2      | 0.49%   |
| Seagate ST3500418AS 500GB                    | 2         | 2      | 0.49%   |
| Seagate ST3320613AS 320GB                    | 2         | 2      | 0.49%   |
| Seagate ST3250318AS 250GB                    | 2         | 2      | 0.49%   |
| Seagate ST3250310AS 250GB                    | 2         | 2      | 0.49%   |
| Seagate ST3160813AS 160GB                    | 2         | 2      | 0.49%   |
| Seagate ST3120827AS 120GB                    | 2         | 3      | 0.49%   |
| Seagate ST1000LM035-1RK172 1TB               | 2         | 2      | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB               | 2         | 2      | 0.49%   |
| Samsung Electronics SSD 970 EVO 250GB        | 2         | 2      | 0.49%   |
| Samsung Electronics SSD 840 PRO Series 128GB | 2         | 3      | 0.49%   |
| Intel SSDSC2KW120H6 120GB                    | 2         | 2      | 0.49%   |
| Intel SSDPEKKW128G7 128GB                    | 2         | 3      | 0.49%   |
| Hitachi HTS545050B9A300 500GB                | 2         | 2      | 0.49%   |
| Hitachi HTS545032B9A300 320GB                | 2         | 3      | 0.49%   |
| Hitachi HTS542516K9SA00 160GB                | 2         | 2      | 0.49%   |
| Hitachi HTS541060G9AT00 64GB                 | 2         | 3      | 0.49%   |
| Hitachi HDS722020ALA330 2TB                  | 2         | 2      | 0.49%   |
| Hitachi HDP725050GLA360 500GB                | 2         | 2      | 0.49%   |
| Hitachi HDP725025GLA380 250GB                | 2         | 2      | 0.49%   |
| HGST HTS545050A7E680 500GB                   | 2         | 2      | 0.49%   |
| Fujitsu MHZ2160BH G2 160GB                   | 2         | 3      | 0.49%   |
| Crucial CT275MX300SSD1 275GB                 | 2         | 2      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 100       | 125    | 25%     |
| WDC                 | 89        | 106    | 22.25%  |
| Hitachi             | 58        | 65     | 14.5%   |
| Toshiba             | 31        | 31     | 7.75%   |
| Fujitsu             | 25        | 26     | 6.25%   |
| Samsung Electronics | 16        | 18     | 4%      |
| Intel               | 15        | 19     | 3.75%   |
| Kingston            | 11        | 11     | 2.75%   |
| SK Hynix            | 9         | 14     | 2.25%   |
| Crucial             | 9         | 10     | 2.25%   |
| A-DATA Technology   | 8         | 9      | 2%      |
| HGST                | 7         | 7      | 1.75%   |
| Micron Technology   | 6         | 6      | 1.5%    |
| SanDisk             | 4         | 4      | 1%      |
| MAXTOR              | 2         | 2      | 0.5%    |
| LITEONIT            | 2         | 2      | 0.5%    |
| PNY                 | 1         | 1      | 0.25%   |
| LITEON              | 1         | 1      | 0.25%   |
| KingDian            | 1         | 1      | 0.25%   |
| JMicron             | 1         | 1      | 0.25%   |
| IBM/Hitachi         | 1         | 1      | 0.25%   |
| Hewlett-Packard     | 1         | 2      | 0.25%   |
| GOODRAM             | 1         | 1      | 0.25%   |
| China               | 1         | 1      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 100       | 125    | 31.15%  |
| WDC                 | 87        | 103    | 27.1%   |
| Hitachi             | 58        | 65     | 18.07%  |
| Toshiba             | 31        | 31     | 9.66%   |
| Fujitsu             | 25        | 26     | 7.79%   |
| Samsung Electronics | 8         | 8      | 2.49%   |
| HGST                | 7         | 7      | 2.18%   |
| MAXTOR              | 2         | 2      | 0.62%   |
| JMicron             | 1         | 1      | 0.31%   |
| IBM/Hitachi         | 1         | 1      | 0.31%   |
| Hewlett-Packard     | 1         | 2      | 0.31%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 308       | 371    | 79.38%  |
| SSD  | 66        | 72     | 17.01%  |
| NVMe | 14        | 21     | 3.61%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB     | 1         | 1      | 20%     |
| Seagate ST500LT012-1DG142 500GB  | 1         | 1      | 20%     |
| Seagate ST500DM005 HD502HJ 500GB | 1         | 1      | 20%     |
| Seagate ST3500830AS 500GB        | 1         | 1      | 20%     |
| HGST HDN724040ALE640 4TB         | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 60%     |
| WDC     | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2194      | 3458   | 69.39%  |
| Detected | 583       | 1131   | 18.44%  |
| Malfunc  | 378       | 464    | 11.95%  |
| Failed   | 5         | 5      | 0.16%   |
| Limited  | 2         | 2      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1606      | 47.68%  |
| AMD                              | 420       | 12.47%  |
| Samsung Electronics              | 397       | 11.79%  |
| Nvidia                           | 317       | 9.41%   |
| Sandisk                          | 111       | 3.3%    |
| Apple                            | 80        | 2.38%   |
| SK Hynix                         | 53        | 1.57%   |
| Marvell Technology Group         | 40        | 1.19%   |
| ASMedia Technology               | 39        | 1.16%   |
| Phison Electronics               | 33        | 0.98%   |
| Kingston Technology Company      | 30        | 0.89%   |
| JMicron Technology               | 28        | 0.83%   |
| Toshiba America Info Systems     | 27        | 0.8%    |
| KIOXIA                           | 22        | 0.65%   |
| Silicon Motion                   | 21        | 0.62%   |
| Micron Technology                | 21        | 0.62%   |
| Micron/Crucial Technology        | 20        | 0.59%   |
| ADATA Technology                 | 18        | 0.53%   |
| LSI Logic / Symbios Logic        | 17        | 0.5%    |
| VIA Technologies                 | 16        | 0.48%   |
| Broadcom / LSI                   | 10        | 0.3%    |
| Union Memory (Shenzhen)          | 6         | 0.18%   |
| Solid State Storage Technology   | 6         | 0.18%   |
| Seagate Technology               | 3         | 0.09%   |
| Realtek Semiconductor            | 3         | 0.09%   |
| Lite-On Technology               | 3         | 0.09%   |
| Lenovo                           | 3         | 0.09%   |
| Adaptec                          | 3         | 0.09%   |
| ULi Electronics                  | 2         | 0.06%   |
| Silicon Image                    | 2         | 0.06%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| OCZ Technology Group             | 1         | 0.03%   |
| Integrated Technology Express    | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Broadcom                         | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| 3ware                            | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 311       | 8.01%   |
| Nvidia MCP79 AHCI Controller                                                            | 291       | 7.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 241       | 6.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 146       | 3.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 113       | 2.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 98        | 2.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 97        | 2.5%    |
| Apple S1X NVMe Controller                                                               | 77        | 1.98%   |
| Samsung Electronics SATA controller                                                     | 73        | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 64        | 1.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 61        | 1.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 60        | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 59        | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 54        | 1.39%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 52        | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 51        | 1.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 49        | 1.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 47        | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 44        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 44        | 1.13%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 43        | 1.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 42        | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 41        | 1.06%   |
| Samsung NVMe SSD Controller 980                                                         | 40        | 1.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 38        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 38        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 38        | 0.98%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 36        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 35        | 0.9%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 34        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 34        | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 33        | 0.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 33        | 0.85%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 32        | 0.82%   |
| AMD 500 Series Chipset SATA Controller                                                  | 31        | 0.8%    |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 29        | 0.75%   |
| Intel SSD 660P Series                                                                   | 26        | 0.67%   |
| Intel SATA Controller [RAID mode]                                                       | 25        | 0.64%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 24        | 0.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 24        | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 23        | 0.59%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 23        | 0.59%   |
| KIOXIA Non-Volatile memory controller                                                   | 22        | 0.57%   |
| Micron Non-Volatile memory controller                                                   | 21        | 0.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 21        | 0.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 21        | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 19        | 0.49%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 19        | 0.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 19        | 0.49%   |
| SK Hynix Gold P31 SSD                                                                   | 18        | 0.46%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 18        | 0.46%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 18        | 0.46%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 17        | 0.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 17        | 0.44%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 17        | 0.44%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 17        | 0.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 17        | 0.44%   |
| Sandisk Non-Volatile memory controller                                                  | 15        | 0.39%   |
| Phison E12 NVMe Controller                                                              | 15        | 0.39%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 15        | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2069      | 59.27%  |
| NVMe | 811       | 23.23%  |
| IDE  | 429       | 12.29%  |
| RAID | 149       | 4.27%   |
| SAS  | 26        | 0.74%   |
| SCSI | 7         | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2361      | 80.47%  |
| AMD          | 502       | 17.11%  |
| ARM          | 66        | 2.25%   |
| CentaurHauls | 3         | 0.1%    |
| Phytium      | 2         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 285       | 9.71%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 142       | 4.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 139       | 4.74%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 53        | 1.81%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 53        | 1.81%   |
| ARM Processor                                 | 53        | 1.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 38        | 1.29%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 31        | 1.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 30        | 1.02%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 23        | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 23        | 0.78%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 23        | 0.78%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 21        | 0.72%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 21        | 0.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 19        | 0.65%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 18        | 0.61%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 18        | 0.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 17        | 0.58%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 17        | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 17        | 0.58%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 17        | 0.58%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 17        | 0.58%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 16        | 0.55%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 16        | 0.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 16        | 0.55%   |
| AMD Ryzen 5 3600 6-Core Processor             | 16        | 0.55%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 14        | 0.48%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 0.48%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 14        | 0.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 13        | 0.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.41%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 12        | 0.41%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 12        | 0.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.37%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 11        | 0.37%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 11        | 0.37%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 11        | 0.37%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 11        | 0.37%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 11        | 0.37%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 11        | 0.37%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 10        | 0.34%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 10        | 0.34%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 0.34%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 10        | 0.34%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 10        | 0.34%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 10        | 0.34%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 9         | 0.31%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 9         | 0.31%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 9         | 0.31%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 9         | 0.31%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.31%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 0.27%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 8         | 0.27%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 0.27%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 8         | 0.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.27%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 8         | 0.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 601       | 20.48%  |
| Intel Core 2 Duo        | 400       | 13.63%  |
| Intel Core i7           | 342       | 11.65%  |
| Other                   | 299       | 10.19%  |
| Intel Core i3           | 207       | 7.05%   |
| Intel Celeron           | 159       | 5.42%   |
| AMD Ryzen 5             | 143       | 4.87%   |
| Intel Pentium           | 126       | 4.29%   |
| Intel Xeon              | 80        | 2.73%   |
| AMD Ryzen 7             | 68        | 2.32%   |
| Intel Core 2            | 62        | 2.11%   |
| Intel Atom              | 47        | 1.6%    |
| Intel Pentium Dual-Core | 31        | 1.06%   |
| AMD Ryzen 9             | 28        | 0.95%   |
| AMD FX                  | 28        | 0.95%   |
| AMD Ryzen 3             | 25        | 0.85%   |
| Intel Core 2 Quad       | 20        | 0.68%   |
| AMD A6                  | 16        | 0.55%   |
| AMD A10                 | 14        | 0.48%   |
| Intel Pentium 4         | 13        | 0.44%   |
| AMD Ryzen Threadripper  | 13        | 0.44%   |
| AMD Ryzen 7 PRO         | 13        | 0.44%   |
| Intel Pentium M         | 12        | 0.41%   |
| AMD Athlon              | 12        | 0.41%   |
| AMD A8                  | 11        | 0.37%   |
| Intel Pentium Gold      | 10        | 0.34%   |
| Intel Core i9           | 10        | 0.34%   |
| Intel Pentium Dual      | 9         | 0.31%   |
| AMD Phenom II X4        | 9         | 0.31%   |
| AMD E1                  | 8         | 0.27%   |
| AMD Athlon II X2        | 8         | 0.27%   |
| AMD A4                  | 8         | 0.27%   |
| Intel Genuine           | 7         | 0.24%   |
| AMD Ryzen 5 PRO         | 7         | 0.24%   |
| AMD Sempron             | 6         | 0.2%    |
| AMD E                   | 5         | 0.17%   |
| Intel Celeron M         | 4         | 0.14%   |
| ARM Allwinner           | 4         | 0.14%   |
| AMD Athlon 64 X2        | 4         | 0.14%   |
| AMD A12                 | 4         | 0.14%   |
| Intel Pentium Silver    | 3         | 0.1%    |
| AMD PRO A8              | 3         | 0.1%    |
| AMD Phenom II X6        | 3         | 0.1%    |
| AMD Opteron             | 3         | 0.1%    |
| AMD EPYC                | 3         | 0.1%    |
| AMD Athlon X4           | 3         | 0.1%    |
| Intel Mobile Pentium 4  | 2         | 0.07%   |
| Intel Core m7           | 2         | 0.07%   |
| Intel Core m3           | 2         | 0.07%   |
| CentaurHauls VIA Eden   | 2         | 0.07%   |
| ARM AArch64             | 2         | 0.07%   |
| AMD Turion 64 Mobile    | 2         | 0.07%   |
| AMD Phenom II X3        | 2         | 0.07%   |
| AMD GX                  | 2         | 0.07%   |
| AMD C-60                | 2         | 0.07%   |
| AMD C-50                | 2         | 0.07%   |
| AMD Athlon XP           | 2         | 0.07%   |
| AMD Athlon II X3        | 2         | 0.07%   |
| AMD Athlon 64           | 2         | 0.07%   |
| Intel Xeon Silver       | 1         | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1471      | 50.12%  |
| 4       | 933       | 31.79%  |
| 6       | 199       | 6.78%   |
| 8       | 157       | 5.35%   |
| 1       | 100       | 3.41%   |
| 16      | 25        | 0.85%   |
| 12      | 22        | 0.75%   |
| 3       | 10        | 0.34%   |
| 24      | 5         | 0.17%   |
| 32      | 3         | 0.1%    |
| 14      | 2         | 0.07%   |
| 10      | 2         | 0.07%   |
| Unknown | 2         | 0.07%   |
| 64      | 1         | 0.03%   |
| 44      | 1         | 0.03%   |
| 28      | 1         | 0.03%   |
| 20      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2897      | 98.77%  |
| 2       | 34        | 1.16%   |
| Unknown | 2         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1667      | 56.84%  |
| 1       | 1264      | 43.1%   |
| Unknown | 2         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2862      | 97.58%  |
| 32-bit         | 46        | 1.57%   |
| Unknown        | 17        | 0.58%   |
| 64-bit         | 8         | 0.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 479       | 16.18%  |
| 0x1067a    | 371       | 12.53%  |
| 0x306d4    | 179       | 6.05%   |
| 0x806c1    | 175       | 5.91%   |
| 0x306c3    | 141       | 4.76%   |
| 0x206a7    | 132       | 4.46%   |
| 0x306a9    | 119       | 4.02%   |
| 0x30678    | 66        | 2.23%   |
| 0x806ec    | 60        | 2.03%   |
| 0x806e9    | 59        | 1.99%   |
| 0x6f6      | 57        | 1.93%   |
| 0x906ea    | 51        | 1.72%   |
| 0x506e3    | 46        | 1.55%   |
| 0x08108109 | 46        | 1.55%   |
| 0x806ea    | 40        | 1.35%   |
| 0x406e3    | 36        | 1.22%   |
| 0xa0653    | 34        | 1.15%   |
| 0x10676    | 34        | 1.15%   |
| 0x906e9    | 33        | 1.11%   |
| 0x08701021 | 31        | 1.05%   |
| 0x40651    | 30        | 1.01%   |
| 0x20655    | 30        | 1.01%   |
| 0xa0655    | 29        | 0.98%   |
| 0x906eb    | 28        | 0.95%   |
| 0x0600611a | 28        | 0.95%   |
| 0x08600106 | 23        | 0.78%   |
| 0x6fd      | 22        | 0.74%   |
| 0xa0652    | 20        | 0.68%   |
| 0x706e5    | 19        | 0.64%   |
| 0x0a201016 | 17        | 0.57%   |
| 0x706a8    | 16        | 0.54%   |
| 0x6fb      | 15        | 0.51%   |
| 0x506c9    | 15        | 0.51%   |
| 0x406c4    | 15        | 0.51%   |
| 0x206d7    | 15        | 0.51%   |
| 0x0a50000c | 14        | 0.47%   |
| 0x08608103 | 14        | 0.47%   |
| 0x0800820d | 14        | 0.47%   |
| 0xa0671    | 13        | 0.44%   |
| 0xf29      | 12        | 0.41%   |
| 0x6d8      | 12        | 0.41%   |
| 0x08108102 | 12        | 0.41%   |
| 0x06006705 | 12        | 0.41%   |
| 0x010000c8 | 12        | 0.41%   |
| 0x906ed    | 11        | 0.37%   |
| 0x806eb    | 11        | 0.37%   |
| 0x08600104 | 11        | 0.37%   |
| 0x06003106 | 11        | 0.37%   |
| 0x206c2    | 10        | 0.34%   |
| 0x106c2    | 10        | 0.34%   |
| 0x0a201009 | 10        | 0.34%   |
| 0x20652    | 9         | 0.3%    |
| 0x0810100b | 9         | 0.3%    |
| 0x306f2    | 8         | 0.27%   |
| 0x106e5    | 8         | 0.27%   |
| 0x08101016 | 8         | 0.27%   |
| 0x406c3    | 7         | 0.24%   |
| 0x30673    | 7         | 0.24%   |
| 0x106ca    | 7         | 0.24%   |
| 0x106a5    | 7         | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 424       | 14.45%  |
| KabyLake         | 356       | 12.13%  |
| Haswell          | 221       | 7.53%   |
| Broadwell        | 192       | 6.54%   |
| TigerLake        | 191       | 6.51%   |
| SandyBridge      | 175       | 5.96%   |
| IvyBridge        | 159       | 5.42%   |
| Core             | 111       | 3.78%   |
| Silvermont       | 107       | 3.65%   |
| Skylake          | 106       | 3.61%   |
| Unknown          | 102       | 3.48%   |
| Zen 2            | 101       | 3.44%   |
| Zen+             | 98        | 3.34%   |
| CometLake        | 89        | 3.03%   |
| Westmere         | 66        | 2.25%   |
| Zen 3            | 56        | 1.91%   |
| Excavator        | 52        | 1.77%   |
| Zen              | 42        | 1.43%   |
| K10              | 32        | 1.09%   |
| Piledriver       | 28        | 0.95%   |
| IceLake          | 28        | 0.95%   |
| Goldmont plus    | 25        | 0.85%   |
| P6               | 20        | 0.68%   |
| Nehalem          | 20        | 0.68%   |
| Bonnell          | 20        | 0.68%   |
| NetBurst         | 18        | 0.61%   |
| Goldmont         | 18        | 0.61%   |
| Steamroller      | 14        | 0.48%   |
| Bobcat           | 14        | 0.48%   |
| K8 Hammer        | 13        | 0.44%   |
| Puma             | 9         | 0.31%   |
| K10 Llano        | 8         | 0.27%   |
| Bulldozer        | 8         | 0.27%   |
| Jaguar           | 7         | 0.24%   |
| K6               | 2         | 0.07%   |
| Tremont          | 1         | 0.03%   |
| Alderlake Hybrid | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1682      | 52.66%  |
| Nvidia                           | 915       | 28.65%  |
| AMD                              | 548       | 17.16%  |
| Matrox Electronics Systems       | 21        | 0.66%   |
| ASPEED Technology                | 21        | 0.66%   |
| VIA Technologies                 | 4         | 0.13%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| S3 Graphics                      | 1         | 0.03%   |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 285       | 8.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 184       | 5.52%   |
| Intel HD Graphics 6000                                                                   | 145       | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 112       | 3.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 83        | 2.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 78        | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 77        | 2.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 75        | 2.25%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 66        | 1.98%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 57        | 1.71%   |
| Intel UHD Graphics 620                                                                   | 54        | 1.62%   |
| AMD Renoir                                                                               | 52        | 1.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 49        | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 43        | 1.29%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 43        | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 43        | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 43        | 1.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 42        | 1.26%   |
| Intel HD Graphics 620                                                                    | 41        | 1.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 38        | 1.14%   |
| Intel HD Graphics 5500                                                                   | 38        | 1.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 38        | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 37        | 1.11%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 37        | 1.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 36        | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 33        | 0.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 29        | 0.87%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 29        | 0.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 29        | 0.87%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 26        | 0.78%   |
| Intel HD Graphics 630                                                                    | 26        | 0.78%   |
| Intel HD Graphics 530                                                                    | 26        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 24        | 0.72%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 23        | 0.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 23        | 0.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 23        | 0.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 23        | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22        | 0.66%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 21        | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 20        | 0.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 0.6%    |
| AMD Cezanne                                                                              | 20        | 0.6%    |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 19        | 0.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 16        | 0.48%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 16        | 0.48%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 16        | 0.48%   |
| AMD Lucienne                                                                             | 16        | 0.48%   |
| Nvidia GT218 [GeForce 210]                                                               | 15        | 0.45%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 15        | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 0.45%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 14        | 0.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 13        | 0.39%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 13        | 0.39%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 12        | 0.36%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 12        | 0.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 0.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 11        | 0.33%   |
| Nvidia TU117M                                                                            | 10        | 0.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 1394      | 47.38%  |
| 1 x Nvidia                        | 664       | 22.57%  |
| 1 x AMD                           | 454       | 15.43%  |
| Intel + Nvidia                    | 218       | 7.41%   |
| Other                             | 70        | 2.38%   |
| Intel + AMD                       | 42        | 1.43%   |
| AMD + Nvidia                      | 27        | 0.92%   |
| 2 x AMD                           | 20        | 0.68%   |
| 1 x Matrox                        | 20        | 0.68%   |
| 1 x ASPEED                        | 17        | 0.58%   |
| 1 x VIA                           | 4         | 0.14%   |
| AMD + ASPEED                      | 3         | 0.1%    |
| 2 x Nvidia                        | 2         | 0.07%   |
| Intel + 2 x Nvidia                | 2         | 0.07%   |
| 3 x AMD                           | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.03%   |
| 1 x SiS                           | 1         | 0.03%   |
| 1 x S3 Graphics                   | 1         | 0.03%   |
| Nvidia + Matrox                   | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2170      | 73.61%  |
| Unknown     | 542       | 18.39%  |
| Proprietary | 236       | 8.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2049      | 69.46%  |
| 0.01-0.5   | 479       | 16.24%  |
| 1.01-2.0   | 131       | 4.44%   |
| 3.01-4.0   | 99        | 3.36%   |
| 0.51-1.0   | 92        | 3.12%   |
| 7.01-8.0   | 46        | 1.56%   |
| 5.01-6.0   | 34        | 1.15%   |
| 8.01-16.0  | 9         | 0.31%   |
| 2.01-3.0   | 8         | 0.27%   |
| 16.01-24.0 | 2         | 0.07%   |
| 24.01-32.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 534       | 20.08%  |
| AU Optronics            | 340       | 12.79%  |
| Samsung Electronics     | 226       | 8.5%    |
| BOE                     | 221       | 8.31%   |
| Chimei Innolux          | 173       | 6.51%   |
| LG Display              | 163       | 6.13%   |
| Dell                    | 122       | 4.59%   |
| Goldstar                | 98        | 3.69%   |
| BenQ                    | 60        | 2.26%   |
| Hewlett-Packard         | 58        | 2.18%   |
| Ancor Communications    | 56        | 2.11%   |
| Lenovo                  | 53        | 1.99%   |
| Acer                    | 52        | 1.96%   |
| Philips                 | 45        | 1.69%   |
| AOC                     | 43        | 1.62%   |
| Sharp                   | 41        | 1.54%   |
| Unknown                 | 30        | 1.13%   |
| Chi Mei Optoelectronics | 29        | 1.09%   |
| InfoVision              | 24        | 0.9%    |
| ViewSonic               | 23        | 0.86%   |
| Iiyama                  | 18        | 0.68%   |
| NEC Computers           | 17        | 0.64%   |
| Eizo                    | 17        | 0.64%   |
| PANDA                   | 16        | 0.6%    |
| ASUSTek Computer        | 14        | 0.53%   |
| Sony                    | 12        | 0.45%   |
| HannStar                | 11        | 0.41%   |
| LG Philips              | 10        | 0.38%   |
| LG Electronics          | 9         | 0.34%   |
| CSO                     | 8         | 0.3%    |
| Vestel Elektronik       | 6         | 0.23%   |
| Toshiba                 | 5         | 0.19%   |
| Panasonic               | 4         | 0.15%   |
| Medion                  | 4         | 0.15%   |
| Grundig                 | 4         | 0.15%   |
| Fujitsu Siemens         | 4         | 0.15%   |
| CPT                     | 4         | 0.15%   |
| Unknown                 | 4         | 0.15%   |
| Vizio                   | 3         | 0.11%   |
| MStar                   | 3         | 0.11%   |
| MSI                     | 3         | 0.11%   |
| IOD                     | 3         | 0.11%   |
| Idek Iiyama             | 3         | 0.11%   |
| Hitachi                 | 3         | 0.11%   |
| ___                     | 2         | 0.08%   |
| Xiaomi                  | 2         | 0.08%   |
| Sanyo                   | 2         | 0.08%   |
| SAC                     | 2         | 0.08%   |
| Quanta Display          | 2         | 0.08%   |
| Planar                  | 2         | 0.08%   |
| ONN                     | 2         | 0.08%   |
| ITL                     | 2         | 0.08%   |
| Compaq Computer         | 2         | 0.08%   |
| Belinea                 | 2         | 0.08%   |
| WTC                     | 1         | 0.04%   |
| VMO                     | 1         | 0.04%   |
| VIE                     | 1         | 0.04%   |
| UGD                     | 1         | 0.04%   |
| TXD                     | 1         | 0.04%   |
| TPU                     | 1         | 0.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                      | 188       | 6.91%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 141       | 5.18%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch            | 108       | 3.97%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 40        | 1.47%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 40        | 1.47%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                      | 35        | 1.29%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 30        | 1.1%    |
| BOE LCD Monitor BOE06B3 1920x1080                                         | 24        | 0.88%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 23        | 0.84%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 23        | 0.84%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                      | 19        | 0.7%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 17        | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 11        | 0.4%    |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 11        | 0.4%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 11        | 0.4%    |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                      | 11        | 0.4%    |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                    | 10        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 10        | 0.37%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 10        | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 9         | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 9         | 0.33%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch               | 8         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 8         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 8         | 0.29%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 8         | 0.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 8         | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 8         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 256x144mm 11.6-inch      | 7         | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 7         | 0.26%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                             | 6         | 0.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 6         | 0.22%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 6         | 0.22%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 6         | 0.22%   |
| BenQ GW2470 BNQ78E4 1920x1080 530x300mm 24.0-inch                         | 6         | 0.22%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 6         | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 5         | 0.18%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch               | 5         | 0.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 5         | 0.18%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 5         | 0.18%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                         | 5         | 0.18%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 5         | 0.18%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 5         | 0.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 5         | 0.18%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 5         | 0.18%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 5         | 0.18%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 5         | 0.18%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch             | 5         | 0.18%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch     | 5         | 0.18%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 4         | 0.15%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch         | 4         | 0.15%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 4         | 0.15%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch     | 4         | 0.15%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 4         | 0.15%   |
| NEC Computers LCD1550V NEC65C6 1024x768 304x228mm 15.0-inch               | 4         | 0.15%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 4         | 0.15%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch               | 4         | 0.15%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                  | 4         | 0.15%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                   | 4         | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 963       | 37.28%  |
| 1366x768 (WXGA)    | 440       | 17.03%  |
| 1280x800 (WXGA)    | 406       | 15.72%  |
| 3840x2160 (4K)     | 119       | 4.61%   |
| 1440x900 (WXGA+)   | 104       | 4.03%   |
| 1280x1024 (SXGA)   | 88        | 3.41%   |
| 2560x1440 (QHD)    | 86        | 3.33%   |
| 1600x900 (HD+)     | 74        | 2.86%   |
| 1920x1200 (WUXGA)  | 49        | 1.9%    |
| 1680x1050 (WSXGA+) | 44        | 1.7%    |
| Unknown            | 24        | 0.93%   |
| 2288x1287          | 23        | 0.89%   |
| 1024x768 (XGA)     | 21        | 0.81%   |
| 1024x600           | 16        | 0.62%   |
| 1360x768           | 12        | 0.46%   |
| 2560x1600          | 11        | 0.43%   |
| 2560x1080          | 11        | 0.43%   |
| 3440x1440          | 10        | 0.39%   |
| 1600x1200          | 10        | 0.39%   |
| 3840x1080          | 7         | 0.27%   |
| 1920x540           | 7         | 0.27%   |
| 2880x1800          | 6         | 0.23%   |
| 3840x2400          | 5         | 0.19%   |
| 2160x1440          | 5         | 0.19%   |
| 2736x1824          | 4         | 0.15%   |
| 4480x1440          | 3         | 0.12%   |
| 5360x1440          | 2         | 0.08%   |
| 3840x1100          | 2         | 0.08%   |
| 3360x1050          | 2         | 0.08%   |
| 3200x1800 (QHD+)   | 2         | 0.08%   |
| 2256x1504          | 2         | 0.08%   |
| 1800x1200          | 2         | 0.08%   |
| 7680x4320          | 1         | 0.04%   |
| 6400x2160          | 1         | 0.04%   |
| 5760x2160          | 1         | 0.04%   |
| 5760x1080          | 1         | 0.04%   |
| 5120x2160          | 1         | 0.04%   |
| 5120x1440          | 1         | 0.04%   |
| 5120x1080          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3360x1080          | 1         | 0.04%   |
| 3200x1080          | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2880x1620          | 1         | 0.04%   |
| 2560x1024          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2048x1536          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |
| 1920x515           | 1         | 0.04%   |
| 1800x1440          | 1         | 0.04%   |
| 1792x768           | 1         | 0.04%   |
| 1400x1050          | 1         | 0.04%   |
| 1280x960           | 1         | 0.04%   |
| 1024x576           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 768       | 29.06%  |
| 15      | 440       | 16.65%  |
| 14      | 172       | 6.51%   |
| 24      | 161       | 6.09%   |
| 11      | 149       | 5.64%   |
| 27      | 128       | 4.84%   |
| 23      | 126       | 4.77%   |
| 17      | 107       | 4.05%   |
| 21      | 106       | 4.01%   |
| Unknown | 66        | 2.5%    |
| 12      | 62        | 2.35%   |
| 19      | 60        | 2.27%   |
| 18      | 44        | 1.66%   |
| 31      | 35        | 1.32%   |
| 22      | 33        | 1.25%   |
| 142     | 23        | 0.87%   |
| 20      | 23        | 0.87%   |
| 10      | 18        | 0.68%   |
| 34      | 17        | 0.64%   |
| 84      | 13        | 0.49%   |
| 25      | 12        | 0.45%   |
| 72      | 9         | 0.34%   |
| 32      | 9         | 0.34%   |
| 54      | 8         | 0.3%    |
| 16      | 7         | 0.26%   |
| 52      | 6         | 0.23%   |
| 28      | 6         | 0.23%   |
| 40      | 5         | 0.19%   |
| 65      | 4         | 0.15%   |
| 33      | 4         | 0.15%   |
| 29      | 4         | 0.15%   |
| 55      | 2         | 0.08%   |
| 49      | 2         | 0.08%   |
| 48      | 2         | 0.08%   |
| 47      | 2         | 0.08%   |
| 26      | 2         | 0.08%   |
| 8       | 2         | 0.08%   |
| 74      | 1         | 0.04%   |
| 50      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 43      | 1         | 0.04%   |
| 38      | 1         | 0.04%   |
| 35      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 201-300        | 865       | 33.21%  |
| 301-350        | 777       | 29.83%  |
| 501-600        | 385       | 14.78%  |
| 401-500        | 220       | 8.45%   |
| 351-400        | 117       | 4.49%   |
| Unknown        | 66        | 2.53%   |
| 601-700        | 62        | 2.38%   |
| 701-800        | 29        | 1.11%   |
| 1001-1500      | 29        | 1.11%   |
| More than 2000 | 23        | 0.88%   |
| 1501-2000      | 23        | 0.88%   |
| 801-900        | 7         | 0.27%   |
| 101-200        | 2         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1568      | 64%     |
| 16/10   | 628       | 25.63%  |
| 5/4     | 84        | 3.43%   |
| Unknown | 55        | 2.24%   |
| 4/3     | 37        | 1.51%   |
| 1.00    | 24        | 0.98%   |
| 3/2     | 22        | 0.9%    |
| 21/9    | 21        | 0.86%   |
| 6/5     | 3         | 0.12%   |
| 32/9    | 2         | 0.08%   |
| 3.40    | 2         | 0.08%   |
| 3.73    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 2.65    | 1         | 0.04%   |
| 1.96    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 691       | 26.39%  |
| 101-110        | 440       | 16.81%  |
| 201-250        | 337       | 12.87%  |
| 71-80          | 248       | 9.47%   |
| 51-60          | 151       | 5.77%   |
| 301-350        | 129       | 4.93%   |
| 151-200        | 117       | 4.47%   |
| 141-150        | 79        | 3.02%   |
| 351-500        | 71        | 2.71%   |
| More than 1000 | 68        | 2.6%    |
| Unknown        | 66        | 2.52%   |
| 251-300        | 59        | 2.25%   |
| 61-70          | 58        | 2.22%   |
| 121-130        | 54        | 2.06%   |
| 41-50          | 18        | 0.69%   |
| 501-1000       | 12        | 0.46%   |
| 131-140        | 9         | 0.34%   |
| 91-100         | 5         | 0.19%   |
| 111-120        | 4         | 0.15%   |
| 1-40           | 2         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 810       | 31.46%  |
| 121-160       | 748       | 29.05%  |
| 51-100        | 637       | 24.74%  |
| 161-240       | 219       | 8.5%    |
| Unknown       | 66        | 2.56%   |
| 1-50          | 60        | 2.33%   |
| More than 240 | 35        | 1.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2057      | 69.49%  |
| 0     | 556       | 18.78%  |
| 2     | 315       | 10.64%  |
| 3     | 29        | 0.98%   |
| 4     | 2         | 0.07%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1266      | 29.83%  |
| Intel                             | 1182      | 27.85%  |
| Broadcom                          | 478       | 11.26%  |
| Qualcomm Atheros                  | 403       | 9.5%    |
| Nvidia                            | 313       | 7.38%   |
| Broadcom Limited                  | 186       | 4.38%   |
| Marvell Technology Group          | 101       | 2.38%   |
| Ralink Technology                 | 26        | 0.61%   |
| Ralink                            | 26        | 0.61%   |
| TP-Link                           | 22        | 0.52%   |
| MEDIATEK                          | 17        | 0.4%    |
| Dell                              | 11        | 0.26%   |
| Qualcomm Atheros Communications   | 10        | 0.24%   |
| Sierra Wireless                   | 9         | 0.21%   |
| Samsung Electronics               | 9         | 0.21%   |
| Microsoft                         | 9         | 0.21%   |
| Microchip Technology              | 9         | 0.21%   |
| D-Link                            | 9         | 0.21%   |
| DisplayLink                       | 8         | 0.19%   |
| NetGear                           | 7         | 0.16%   |
| ASIX Electronics                  | 7         | 0.16%   |
| Xiaomi                            | 6         | 0.14%   |
| JMicron Technology                | 6         | 0.14%   |
| D-Link System                     | 6         | 0.14%   |
| ASUSTek Computer                  | 6         | 0.14%   |
| Mellanox Technologies             | 5         | 0.12%   |
| Lenovo                            | 5         | 0.12%   |
| Huawei Technologies               | 5         | 0.12%   |
| Hewlett-Packard                   | 5         | 0.12%   |
| Ericsson Business Mobile Networks | 5         | 0.12%   |
| ICS Advent                        | 4         | 0.09%   |
| Fibocom                           | 4         | 0.09%   |
| Edimax Technology                 | 4         | 0.09%   |
| Attansic Technology               | 4         | 0.09%   |
| Aquantia                          | 4         | 0.09%   |
| VIA Technologies                  | 3         | 0.07%   |
| Qualcomm                          | 3         | 0.07%   |
| Dresden Elektronik                | 3         | 0.07%   |
| Cypress Semiconductor             | 3         | 0.07%   |
| Belkin Components                 | 3         | 0.07%   |
| AMD                               | 3         | 0.07%   |
| 3Com                              | 3         | 0.07%   |
| ULi Electronics                   | 2         | 0.05%   |
| U-Blox                            | 2         | 0.05%   |
| Standard Microsystems             | 2         | 0.05%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.05%   |
| QLogic                            | 2         | 0.05%   |
| OPPO Electronics                  | 2         | 0.05%   |
| National Semiconductor            | 2         | 0.05%   |
| IMC Networks                      | 2         | 0.05%   |
| Google                            | 2         | 0.05%   |
| Gemtek                            | 2         | 0.05%   |
| American Megatrends               | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.02%   |
| Z-Com                             | 1         | 0.02%   |
| Winbond Electronics               | 1         | 0.02%   |
| Wilocity                          | 1         | 0.02%   |
| Texas Instruments                 | 1         | 0.02%   |
| Sundance Technology Inc / IC Plus | 1         | 0.02%   |
| STMicroelectronics                | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 917       | 18.71%  |
| Nvidia MCP79 Ethernet                                                                 | 292       | 5.96%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 287       | 5.86%   |
| Intel Wi-Fi 6 AX201                                                                   | 161       | 3.29%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 146       | 2.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 136       | 2.77%   |
| Intel Ethernet Connection (13) I219-V                                                 | 119       | 2.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 97        | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 97        | 1.98%   |
| Intel Wi-Fi 6 AX200                                                                   | 88        | 1.8%    |
| Intel Wireless 7260                                                                   | 81        | 1.65%   |
| Intel Wireless 8265 / 8275                                                            | 74        | 1.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 62        | 1.27%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 53        | 1.08%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 52        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 43        | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 42        | 0.86%   |
| Intel I211 Gigabit Network Connection                                                 | 40        | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 40        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 39        | 0.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 38        | 0.78%   |
| Intel Wireless 8260                                                                   | 36        | 0.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 35        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 35        | 0.71%   |
| Intel Wireless 7265                                                                   | 35        | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 34        | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                                  | 34        | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 29        | 0.59%   |
| Intel Wireless 3165                                                                   | 28        | 0.57%   |
| Intel I210 Gigabit Network Connection                                                 | 27        | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 26        | 0.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 26        | 0.53%   |
| Intel Ethernet Connection I217-LM                                                     | 24        | 0.49%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 24        | 0.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 23        | 0.47%   |
| Intel Ethernet Connection (14) I219-V                                                 | 23        | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 22        | 0.45%   |
| Intel Ethernet Connection (2) I219-V                                                  | 22        | 0.45%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 22        | 0.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 20        | 0.41%   |
| Intel 82579V Gigabit Network Connection                                               | 20        | 0.41%   |
| Intel 82574L Gigabit Network Connection                                               | 20        | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 18        | 0.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 17        | 0.35%   |
| Intel Ethernet Connection (6) I219-V                                                  | 17        | 0.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 16        | 0.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 16        | 0.33%   |
| Intel Ethernet Connection I217-V                                                      | 16        | 0.33%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 16        | 0.33%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 16        | 0.33%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                         | 15        | 0.31%   |
| Intel Wireless-AC 9260                                                                | 15        | 0.31%   |
| Intel Ethernet Connection I219-LM                                                     | 15        | 0.31%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 15        | 0.31%   |
| Intel 82577LM Gigabit Network Connection                                              | 15        | 0.31%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 15        | 0.31%   |
| Intel Wireless 3160                                                                   | 14        | 0.29%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 14        | 0.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 13        | 0.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 13        | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 868       | 40.17%  |
| Broadcom                          | 394       | 18.23%  |
| Qualcomm Atheros                  | 337       | 15.59%  |
| Realtek Semiconductor             | 233       | 10.78%  |
| Broadcom Limited                  | 164       | 7.59%   |
| Ralink Technology                 | 26        | 1.2%    |
| Ralink                            | 26        | 1.2%    |
| TP-Link                           | 18        | 0.83%   |
| MEDIATEK                          | 15        | 0.69%   |
| Qualcomm Atheros Communications   | 10        | 0.46%   |
| Sierra Wireless                   | 9         | 0.42%   |
| NetGear                           | 7         | 0.32%   |
| D-Link                            | 7         | 0.32%   |
| Microsoft                         | 6         | 0.28%   |
| Dell                              | 6         | 0.28%   |
| ASUSTek Computer                  | 6         | 0.28%   |
| Edimax Technology                 | 4         | 0.19%   |
| Qualcomm                          | 3         | 0.14%   |
| FIBOCOM                           | 3         | 0.14%   |
| Belkin Components                 | 3         | 0.14%   |
| Marvell Technology Group          | 2         | 0.09%   |
| IMC Networks                      | 2         | 0.09%   |
| D-Link System                     | 2         | 0.09%   |
| Z-Com                             | 1         | 0.05%   |
| Wilocity                          | 1         | 0.05%   |
| Sitecom Europe                    | 1         | 0.05%   |
| Micro Star International          | 1         | 0.05%   |
| Linksys                           | 1         | 0.05%   |
| Gemtek                            | 1         | 0.05%   |
| Ericsson Business Mobile Networks | 1         | 0.05%   |
| BUFFALO                           | 1         | 0.05%   |
| AVM                               | 1         | 0.05%   |
| 3Com                              | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 287       | 13.21%  |
| Intel Wi-Fi 6 AX201                                                                   | 161       | 7.41%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 146       | 6.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 97        | 4.47%   |
| Intel Wi-Fi 6 AX200                                                                   | 88        | 4.05%   |
| Intel Wireless 7260                                                                   | 81        | 3.73%   |
| Intel Wireless 8265 / 8275                                                            | 74        | 3.41%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 53        | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 43        | 1.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 42        | 1.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 40        | 1.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 39        | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 38        | 1.75%   |
| Intel Wireless 8260                                                                   | 36        | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 35        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 35        | 1.61%   |
| Intel Wireless 7265                                                                   | 35        | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 29        | 1.34%   |
| Intel Wireless 3165                                                                   | 28        | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 26        | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 26        | 1.2%    |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 24        | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 22        | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 22        | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 20        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 17        | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 16        | 0.74%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                         | 15        | 0.69%   |
| Intel Wireless-AC 9260                                                                | 15        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 15        | 0.69%   |
| Intel Wireless 3160                                                                   | 14        | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 14        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 13        | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 13        | 0.6%    |
| Intel Centrino Wireless-N 2230                                                        | 13        | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 12        | 0.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 12        | 0.55%   |
| Intel Centrino Advanced-N 6200                                                        | 12        | 0.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 11        | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 10        | 0.46%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 10        | 0.46%   |
| Realtek 802.11ac NIC                                                                  | 10        | 0.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 10        | 0.46%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 10        | 0.46%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 10        | 0.46%   |
| Intel Centrino Ultimate-N 6300                                                        | 10        | 0.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 10        | 0.46%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 9         | 0.41%   |
| Ralink RT5370 Wireless Adapter                                                        | 9         | 0.41%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 9         | 0.41%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 9         | 0.41%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 9         | 0.41%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 8         | 0.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 8         | 0.37%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 8         | 0.37%   |
| Ralink MT7601U Wireless Adapter                                                       | 7         | 0.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 7         | 0.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 7         | 0.32%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 7         | 0.32%   |
| Sierra Wireless EM7345 4G LTE                                                         | 6         | 0.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1175      | 44.97%  |
| Intel                             | 704       | 26.94%  |
| Nvidia                            | 313       | 11.98%  |
| Broadcom                          | 100       | 3.83%   |
| Marvell Technology Group          | 99        | 3.79%   |
| Qualcomm Atheros                  | 85        | 3.25%   |
| Broadcom Limited                  | 23        | 0.88%   |
| Samsung Electronics               | 9         | 0.34%   |
| Microchip Technology              | 9         | 0.34%   |
| DisplayLink                       | 8         | 0.31%   |
| ASIX Electronics                  | 7         | 0.27%   |
| Xiaomi                            | 6         | 0.23%   |
| JMicron Technology                | 6         | 0.23%   |
| Lenovo                            | 5         | 0.19%   |
| TP-Link                           | 4         | 0.15%   |
| Mellanox Technologies             | 4         | 0.15%   |
| ICS Advent                        | 4         | 0.15%   |
| D-Link System                     | 4         | 0.15%   |
| Attansic Technology               | 4         | 0.15%   |
| Aquantia                          | 4         | 0.15%   |
| VIA Technologies                  | 3         | 0.11%   |
| Microsoft                         | 3         | 0.11%   |
| Huawei Technologies               | 3         | 0.11%   |
| Cypress Semiconductor             | 3         | 0.11%   |
| Standard Microsystems             | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.08%   |
| QLogic                            | 2         | 0.08%   |
| OPPO Electronics                  | 2         | 0.08%   |
| National Semiconductor            | 2         | 0.08%   |
| D-Link                            | 2         | 0.08%   |
| American Megatrends               | 2         | 0.08%   |
| 3Com                              | 2         | 0.08%   |
| Sundance Technology Inc / IC Plus | 1         | 0.04%   |
| Spreadtrum Communications         | 1         | 0.04%   |
| Motorola PCS                      | 1         | 0.04%   |
| MediaTek                          | 1         | 0.04%   |
| IBM                               | 1         | 0.04%   |
| HMD Global                        | 1         | 0.04%   |
| Hewlett-Packard                   | 1         | 0.04%   |
| Google                            | 1         | 0.04%   |
| Gemtek                            | 1         | 0.04%   |
| Fibocom                           | 1         | 0.04%   |
| Davicom Semiconductor             | 1         | 0.04%   |
| ADMtek                            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 917       | 34.29%  |
| Nvidia MCP79 Ethernet                                             | 292       | 10.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 136       | 5.09%   |
| Intel Ethernet Connection (13) I219-V                             | 119       | 4.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 97        | 3.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 2.32%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 52        | 1.94%   |
| Intel I211 Gigabit Network Connection                             | 40        | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 34        | 1.27%   |
| Intel Ethernet Connection (4) I219-V                              | 34        | 1.27%   |
| Intel I210 Gigabit Network Connection                             | 27        | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 24        | 0.9%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 23        | 0.86%   |
| Intel Ethernet Connection (14) I219-V                             | 23        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 22        | 0.82%   |
| Intel 82579V Gigabit Network Connection                           | 20        | 0.75%   |
| Intel 82574L Gigabit Network Connection                           | 20        | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 18        | 0.67%   |
| Intel Ethernet Connection (6) I219-V                              | 17        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 16        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 15        | 0.56%   |
| Intel 82577LM Gigabit Network Connection                          | 15        | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.49%   |
| Nvidia MCP61 Ethernet                                             | 12        | 0.45%   |
| Intel Ethernet Controller I225-V                                  | 12        | 0.45%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.45%   |
| Intel Ethernet Connection (10) I219-V                             | 11        | 0.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10        | 0.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10        | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 9         | 0.34%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 9         | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.3%    |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 8         | 0.3%    |
| Intel Ethernet Connection I219-V                                  | 8         | 0.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.3%    |
| Intel Ethernet Connection (2) I218-V                              | 8         | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.26%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 7         | 0.26%   |
| Intel I350 Gigabit Network Connection                             | 7         | 0.26%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 7         | 0.26%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.26%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.26%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 7         | 0.26%   |
| Broadcom BCM4401 100Base-T                                        | 7         | 0.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6         | 0.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 6         | 0.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.22%   |
| Nvidia MCP89 Ethernet                                             | 6         | 0.22%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 6         | 0.22%   |
| Intel Ethernet Connection (5) I219-LM                             | 6         | 0.22%   |
| Intel Ethernet Connection (11) I219-LM                            | 6         | 0.22%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 6         | 0.22%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.22%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 6         | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2492      | 53.78%  |
| WiFi     | 2087      | 45.04%  |
| Modem    | 53        | 1.14%   |
| Unknown  | 2         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1847      | 50.56%  |
| WiFi     | 1801      | 49.3%   |
| Modem    | 5         | 0.14%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1598      | 54.43%  |
| 1     | 1162      | 39.58%  |
| 0     | 88        | 3%      |
| 3     | 52        | 1.77%   |
| 4     | 25        | 0.85%   |
| 6     | 5         | 0.17%   |
| 5     | 4         | 0.14%   |
| 13    | 1         | 0.03%   |
| 8     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2535      | 85.96%  |
| Yes  | 414       | 14.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 708       | 39.16%  |
| Apple                           | 531       | 29.37%  |
| Realtek Semiconductor           | 123       | 6.8%    |
| Qualcomm Atheros Communications | 123       | 6.8%    |
| Cambridge Silicon Radio         | 64        | 3.54%   |
| Broadcom                        | 61        | 3.37%   |
| Lite-On Technology              | 52        | 2.88%   |
| IMC Networks                    | 41        | 2.27%   |
| Foxconn / Hon Hai               | 28        | 1.55%   |
| ASUSTek Computer                | 16        | 0.88%   |
| Dell                            | 13        | 0.72%   |
| Hewlett-Packard                 | 12        | 0.66%   |
| Realtek                         | 8         | 0.44%   |
| Toshiba                         | 7         | 0.39%   |
| Ralink                          | 7         | 0.39%   |
| Taiyo Yuden                     | 3         | 0.17%   |
| Belkin Components               | 2         | 0.11%   |
| USI                             | 1         | 0.06%   |
| Sitecom Europe                  | 1         | 0.06%   |
| Ralink Technology               | 1         | 0.06%   |
| Qcom                            | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| Fujitsu                         | 1         | 0.06%   |
| Foxconn International           | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |
| Alps Electric                   | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 287       | 15.84%  |
| Intel Bluetooth wireless interface                                                  | 257       | 14.18%  |
| Intel AX201 Bluetooth                                                               | 211       | 11.64%  |
| Apple Bluetooth USB Host Controller                                                 | 152       | 8.39%   |
| Intel AX200 Bluetooth                                                               | 89        | 4.91%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 88        | 4.86%   |
| Realtek Bluetooth Radio                                                             | 83        | 4.58%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 80        | 4.42%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                                           | 73        | 4.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 64        | 3.53%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 26        | 1.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 24        | 1.32%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 19        | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 17        | 0.94%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 0.88%   |
| Apple Bluetooth Host Controller                                                     | 16        | 0.88%   |
| Intel Bluetooth Device                                                              | 14        | 0.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 14        | 0.77%   |
| IMC Networks Bluetooth Device                                                       | 12        | 0.66%   |
| IMC Networks Bluetooth Radio                                                        | 11        | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 9         | 0.5%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 9         | 0.5%    |
| Intel AX210 Bluetooth                                                               | 9         | 0.5%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 9         | 0.5%    |
| Realtek RTL8723B Bluetooth                                                          | 8         | 0.44%   |
| Realtek Bluetooth Radio                                                             | 8         | 0.44%   |
| Lite-On Bluetooth Device                                                            | 8         | 0.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 8         | 0.44%   |
| Ralink RT3290 Bluetooth                                                             | 7         | 0.39%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 7         | 0.39%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 7         | 0.39%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 7         | 0.39%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 6         | 0.33%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 6         | 0.33%   |
| Lite-On Wireless_Device                                                             | 5         | 0.28%   |
| IMC Networks Wireless_Device                                                        | 5         | 0.28%   |
| IMC Networks Bluetooth                                                              | 5         | 0.28%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 0.28%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 0.28%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 5         | 0.28%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 0.22%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.22%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 4         | 0.22%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 0.22%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 4         | 0.22%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.17%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 3         | 0.17%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 0.17%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 3         | 0.17%   |
| Broadcom BCM2045 Bluetooth                                                          | 3         | 0.17%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.17%   |
| Realtek RTL8723A Bluetooth                                                          | 2         | 0.11%   |
| Lite-On BCM43142A0                                                                  | 2         | 0.11%   |
| IMC Networks Bluetooth USB Host Controller                                          | 2         | 0.11%   |
| IMC Networks Bluetooth module                                                       | 2         | 0.11%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.11%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                                          | 2         | 0.11%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1976      | 56.1%   |
| Nvidia                           | 750       | 21.29%  |
| AMD                              | 565       | 16.04%  |
| C-Media Electronics              | 33        | 0.94%   |
| Logitech                         | 22        | 0.62%   |
| Generalplus Technology           | 18        | 0.51%   |
| Creative Labs                    | 11        | 0.31%   |
| Texas Instruments                | 10        | 0.28%   |
| Creative Technology              | 10        | 0.28%   |
| Plantronics                      | 7         | 0.2%    |
| GN Netcom                        | 7         | 0.2%    |
| VIA Technologies                 | 6         | 0.17%   |
| RODE Microphones                 | 6         | 0.17%   |
| Lenovo                           | 6         | 0.17%   |
| JMTek                            | 6         | 0.17%   |
| GYROCOM C&C                      | 6         | 0.17%   |
| ASUSTek Computer                 | 5         | 0.14%   |
| Unknown                          | 4         | 0.11%   |
| SteelSeries ApS                  | 4         | 0.11%   |
| Sennheiser Communications        | 4         | 0.11%   |
| Realtek Semiconductor            | 4         | 0.11%   |
| Focusrite-Novation               | 4         | 0.11%   |
| Yamaha                           | 3         | 0.09%   |
| Samson Technologies              | 3         | 0.09%   |
| Hewlett-Packard                  | 3         | 0.09%   |
| Cambridge Silicon Radio          | 3         | 0.09%   |
| BEHRINGER International          | 3         | 0.09%   |
| XMOS                             | 2         | 0.06%   |
| ULi Electronics                  | 2         | 0.06%   |
| Razer USA                        | 2         | 0.06%   |
| Microsoft                        | 2         | 0.06%   |
| Micro Star International         | 2         | 0.06%   |
| Kingston Technology              | 2         | 0.06%   |
| CMX Systems                      | 2         | 0.06%   |
| Apple                            | 2         | 0.06%   |
| Thomann                          | 1         | 0.03%   |
| TerraTec Electronic              | 1         | 0.03%   |
| TEAC                             | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| SAVITECH                         | 1         | 0.03%   |
| Samsung Electronics              | 1         | 0.03%   |
| ROCCAT                           | 1         | 0.03%   |
| PreSonus Audio Electronics       | 1         | 0.03%   |
| Pixart Imaging                   | 1         | 0.03%   |
| Musical Fidelity                 | 1         | 0.03%   |
| Micronas                         | 1         | 0.03%   |
| Microdia                         | 1         | 0.03%   |
| Mackie Designs                   | 1         | 0.03%   |
| M-Audio                          | 1         | 0.03%   |
| Hangzhou Worlde                  | 1         | 0.03%   |
| ESS Technology                   | 1         | 0.03%   |
| Ensoniq                          | 1         | 0.03%   |
| DisplayLink                      | 1         | 0.03%   |
| Dell                             | 1         | 0.03%   |
| DCMT Technology                  | 1         | 0.03%   |
| Blue Microphones                 | 1         | 0.03%   |
| B & W Group                      | 1         | 0.03%   |
| AXELVOX                          | 1         | 0.03%   |
| AVID Technology                  | 1         | 0.03%   |
| Audioengine                      | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 High Definition Audio                                                                | 293       | 6.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 191       | 4.52%   |
| Intel Broadwell-U Audio Controller                                                                | 187       | 4.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 185       | 4.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 185       | 4.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 169       | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 159       | 3.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 151       | 3.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 147       | 3.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 126       | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 116       | 2.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 95        | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 79        | 1.87%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 76        | 1.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 72        | 1.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 70        | 1.66%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 66        | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 63        | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 60        | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 57        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 57        | 1.35%   |
| Intel Comet Lake PCH cAVS                                                                         | 55        | 1.3%    |
| AMD FCH Azalia Controller                                                                         | 54        | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                                          | 52        | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 48        | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 47        | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 47        | 1.11%   |
| Intel 200 Series PCH HD Audio                                                                     | 44        | 1.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 43        | 1.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 40        | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 38        | 0.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 38        | 0.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 38        | 0.9%    |
| Intel 8 Series HD Audio Controller                                                                | 38        | 0.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 36        | 0.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 34        | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 30        | 0.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 27        | 0.64%   |
| Nvidia High Definition Audio Controller                                                           | 26        | 0.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 25        | 0.59%   |
| Intel Audio device                                                                                | 22        | 0.52%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 21        | 0.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 21        | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 20        | 0.47%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 19        | 0.45%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 18        | 0.43%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 18        | 0.43%   |
| Generalplus Technology USB Audio Device                                                           | 18        | 0.43%   |
| AMD Navi 10 HDMI Audio                                                                            | 18        | 0.43%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 17        | 0.4%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 16        | 0.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 0.38%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 15        | 0.36%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 15        | 0.36%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 15        | 0.36%   |
| Nvidia MCP61 High Definition Audio                                                                | 13        | 0.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 0.31%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 13        | 0.31%   |
| AMD High Definition Audio Controller                                                              | 13        | 0.31%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 12        | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 702       | 24.64%  |
| Samsung Electronics | 662       | 23.24%  |
| Kingston            | 295       | 10.35%  |
| Unknown             | 233       | 8.18%   |
| Crucial             | 216       | 7.58%   |
| Micron Technology   | 186       | 6.53%   |
| Corsair             | 89        | 3.12%   |
| Elpida              | 71        | 2.49%   |
| G.Skill             | 62        | 2.18%   |
| Patriot             | 49        | 1.72%   |
| Ramaxel Technology  | 43        | 1.51%   |
| A-DATA Technology   | 36        | 1.26%   |
| Nanya Technology    | 27        | 0.95%   |
| Hikvision           | 20        | 0.7%    |
| GOODRAM             | 17        | 0.6%    |
| Unknown (ABCD)      | 14        | 0.49%   |
| Smart               | 14        | 0.49%   |
| Team                | 13        | 0.46%   |
| Transcend           | 11        | 0.39%   |
| AMD                 | 9         | 0.32%   |
| Unknown             | 6         | 0.21%   |
| ASint Technology    | 4         | 0.14%   |
| Unifosa             | 3         | 0.11%   |
| Silicon Power       | 3         | 0.11%   |
| Qimonda             | 3         | 0.11%   |
| PNY                 | 3         | 0.11%   |
| Kllisre             | 3         | 0.11%   |
| Infineon            | 3         | 0.11%   |
| Hewlett-Packard     | 3         | 0.11%   |
| Avant               | 3         | 0.11%   |
| Apacer              | 3         | 0.11%   |
| 48spaces            | 3         | 0.11%   |
| Wilk                | 2         | 0.07%   |
| Unknown (0x07D5)    | 2         | 0.07%   |
| Unknown (08C8)      | 2         | 0.07%   |
| Toshiba             | 2         | 0.07%   |
| TIMETEC             | 2         | 0.07%   |
| Teikon              | 2         | 0.07%   |
| SMART Brazil        | 2         | 0.07%   |
| Kingmax             | 2         | 0.07%   |
| Goldkey             | 2         | 0.07%   |
| GeIL                | 2         | 0.07%   |
| Wilk Elektronik     | 1         | 0.04%   |
| V-Color             | 1         | 0.04%   |
| Unknown (836D)      | 1         | 0.04%   |
| TwinMOS             | 1         | 0.04%   |
| Sesame              | 1         | 0.04%   |
| SemsoTai            | 1         | 0.04%   |
| OCZ                 | 1         | 0.04%   |
| Novatech            | 1         | 0.04%   |
| Neo Forza           | 1         | 0.04%   |
| Klevv               | 1         | 0.04%   |
| KETECH              | 1         | 0.04%   |
| Hyundai lnc         | 1         | 0.04%   |
| HPE                 | 1         | 0.04%   |
| Foxline             | 1         | 0.04%   |
| Exceleram           | 1         | 0.04%   |
| AXIOM               | 1         | 0.04%   |
| ATP                 | 1         | 0.04%   |
| A-TECH              | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM Module 1GB SODIMM DDR2 800MT/s                         | 239       | 7.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 126       | 4.14%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 667MT/s                         | 66        | 2.17%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                         | 61        | 2%      |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s            | 39        | 1.28%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 33        | 1.08%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                          | 29        | 0.95%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s               | 29        | 0.95%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 24        | 0.79%   |
| SK Hynix RAM Module 2GB SODIMM DDR2 800MT/s                         | 24        | 0.79%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s              | 24        | 0.79%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 23        | 0.76%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 20        | 0.66%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s             | 20        | 0.66%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s             | 20        | 0.66%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 17        | 0.56%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 17        | 0.56%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 17        | 0.56%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                     | 15        | 0.49%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                          | 15        | 0.49%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 13        | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 13        | 0.43%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s               | 12        | 0.39%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 11        | 0.36%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 11        | 0.36%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 11        | 0.36%   |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s                      | 11        | 0.36%   |
| Crucial RAM CT8G4DFRA32A.M4FE 8GB DIMM DDR4 3200MT/s                | 11        | 0.36%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 10        | 0.33%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 10        | 0.33%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 10        | 0.33%   |
| Micron RAM 4KTF25664HZ-1G6E 2048MB SODIMM DDR3 1333MT/s             | 10        | 0.33%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 9         | 0.3%    |
| Unknown RAM Module 1GB DIMM SDRAM                                   | 9         | 0.3%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 8         | 0.26%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 8         | 0.26%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 8         | 0.26%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 8         | 0.26%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 8         | 0.26%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 8         | 0.26%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 8         | 0.26%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 8         | 0.26%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 8         | 0.26%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 8         | 0.26%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 8         | 0.26%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 8         | 0.26%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 8         | 0.26%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s            | 8         | 0.26%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 7         | 0.23%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 7         | 0.23%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 7         | 0.23%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 0.23%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 7         | 0.23%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s             | 7         | 0.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 7         | 0.23%   |
| Kingston RAM 99U5474-025.A00LF 2GB DIMM DDR3 1333MT/s               | 7         | 0.23%   |
| Kingston RAM 99U5474-013.A00LF 2GB DIMM DDR3 1600MT/s               | 7         | 0.23%   |
| Kingston RAM 9905474-012.A00LF 2048MB DIMM DDR3 1333MT/s            | 7         | 0.23%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s              | 7         | 0.23%   |
| Crucial RAM CT25664BA160B.D8FE 2GB DIMM DDR3 1600MT/s               | 7         | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 968       | 37.92%  |
| DDR3    | 888       | 34.78%  |
| DDR2    | 445       | 17.43%  |
| Unknown | 67        | 2.62%   |
| SDRAM   | 64        | 2.51%   |
| LPDDR4  | 51        | 2%      |
| LPDDR3  | 37        | 1.45%   |
| DDR     | 30        | 1.18%   |
| DRAM    | 3         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1613      | 63.21%  |
| DIMM         | 831       | 32.56%  |
| Row Of Chips | 87        | 3.41%   |
| Chip         | 15        | 0.59%   |
| Unknown      | 3         | 0.12%   |
| FB-DIMM      | 2         | 0.08%   |
| RIMM         | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 787       | 28.73%  |
| 4096  | 684       | 24.97%  |
| 2048  | 451       | 16.47%  |
| 1024  | 441       | 16.1%   |
| 16384 | 264       | 9.64%   |
| 32768 | 64        | 2.34%   |
| 512   | 32        | 1.17%   |
| 256   | 13        | 0.47%   |
| 65536 | 3         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 603       | 22.23%  |
| 3200    | 366       | 13.5%   |
| 800     | 338       | 12.46%  |
| 2667    | 334       | 12.32%  |
| 1333    | 180       | 6.64%   |
| 2400    | 144       | 5.31%   |
| 667     | 122       | 4.5%    |
| 2133    | 81        | 2.99%   |
| Unknown | 68        | 2.51%   |
| 1334    | 59        | 2.18%   |
| 1866    | 48        | 1.77%   |
| 3600    | 38        | 1.4%    |
| 1067    | 36        | 1.33%   |
| 1867    | 32        | 1.18%   |
| 4267    | 25        | 0.92%   |
| 1066    | 24        | 0.88%   |
| 2666    | 20        | 0.74%   |
| 3266    | 17        | 0.63%   |
| 3000    | 16        | 0.59%   |
| 4199    | 11        | 0.41%   |
| 3466    | 11        | 0.41%   |
| 3400    | 11        | 0.41%   |
| 2933    | 11        | 0.41%   |
| 533     | 11        | 0.41%   |
| 1800    | 8         | 0.29%   |
| 400     | 8         | 0.29%   |
| 333     | 8         | 0.29%   |
| 2048    | 7         | 0.26%   |
| 266     | 7         | 0.26%   |
| 4333    | 6         | 0.22%   |
| 3733    | 6         | 0.22%   |
| 975     | 6         | 0.22%   |
| 3066    | 5         | 0.18%   |
| 4266    | 4         | 0.15%   |
| 3100    | 4         | 0.15%   |
| 2465    | 3         | 0.11%   |
| 3800    | 2         | 0.07%   |
| 3533    | 2         | 0.07%   |
| 3500    | 2         | 0.07%   |
| 3334    | 2         | 0.07%   |
| 3333    | 2         | 0.07%   |
| 2668    | 2         | 0.07%   |
| 2200    | 2         | 0.07%   |
| 2000    | 2         | 0.07%   |
| 1400    | 2         | 0.07%   |
| 66      | 2         | 0.07%   |
| 8400    | 1         | 0.04%   |
| 4800    | 1         | 0.04%   |
| 4000    | 1         | 0.04%   |
| 3866    | 1         | 0.04%   |
| 2866    | 1         | 0.04%   |
| 2800    | 1         | 0.04%   |
| 2733    | 1         | 0.04%   |
| 2267    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 1777    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 1367    | 1         | 0.04%   |
| 1033    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 25        | 45.45%  |
| Brother Industries  | 9         | 16.36%  |
| Samsung Electronics | 6         | 10.91%  |
| Canon               | 5         | 9.09%   |
| Zebra               | 2         | 3.64%   |
| Xerox               | 2         | 3.64%   |
| Prolific Technology | 2         | 3.64%   |
| Seiko Epson         | 1         | 1.82%   |
| Konica Minolta      | 1         | 1.82%   |
| GODEX INTERNATIONAL | 1         | 1.82%   |
| Dymo-CoStar         | 1         | 1.82%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP LaserJet M101-M106                | 3         | 5.45%   |
| Xerox B205                           | 2         | 3.64%   |
| Prolific PL2305 Parallel Port        | 2         | 3.64%   |
| HP LaserJet 1200                     | 2         | 3.64%   |
| HP ENVY 4520 series                  | 2         | 3.64%   |
| Zebra ZTC ZP 500 (ZPL)               | 1         | 1.82%   |
| Zebra ZTC ZD420-203dpi ZPL           | 1         | 1.82%   |
| Seiko Epson L4150 Series             | 1         | 1.82%   |
| Samsung SCX-4650 4x21S Series        | 1         | 1.82%   |
| Samsung SCX-3200 Series              | 1         | 1.82%   |
| Samsung ML-216x Series Laser Printer | 1         | 1.82%   |
| Samsung ML-2010P Mono Laser Printer  | 1         | 1.82%   |
| Samsung ML-1660 Series               | 1         | 1.82%   |
| Samsung ML-1520 Laser Printer        | 1         | 1.82%   |
| Konica Minolta bizhub 4402P          | 1         | 1.82%   |
| HP Officejet J4500 series            | 1         | 1.82%   |
| HP Officejet 7110 series             | 1         | 1.82%   |
| HP LaserJet Pro M404-M405            | 1         | 1.82%   |
| HP LaserJet P2055 series             | 1         | 1.82%   |
| HP LaserJet P1006                    | 1         | 1.82%   |
| HP LaserJet M14-M17                  | 1         | 1.82%   |
| HP LaserJet 400 M401dne              | 1         | 1.82%   |
| HP LaserJet 1300                     | 1         | 1.82%   |
| HP LaserJet 1150                     | 1         | 1.82%   |
| HP LaserJet 1020                     | 1         | 1.82%   |
| HP LaserJet 1015                     | 1         | 1.82%   |
| HP Ink Tank 110 series               | 1         | 1.82%   |
| HP ENVY Photo 6200 series            | 1         | 1.82%   |
| HP ENVY 5000 series                  | 1         | 1.82%   |
| HP DeskJet Plus 4100 series          | 1         | 1.82%   |
| HP Deskjet 4640 series               | 1         | 1.82%   |
| HP DeskJet 2620 All-in-One Printer   | 1         | 1.82%   |
| HP DeskJet 2130 series               | 1         | 1.82%   |
| GODEX INTERNATIONAL DT2              | 1         | 1.82%   |
| Dymo-CoStar LabelWriter 450          | 1         | 1.82%   |
| Canon PIXMA MX920 Series             | 1         | 1.82%   |
| Canon MF4100 series                  | 1         | 1.82%   |
| Canon LiDE 400                       | 1         | 1.82%   |
| Canon LBP3010/LBP3018/LBP3050        | 1         | 1.82%   |
| Canon iP2700 series                  | 1         | 1.82%   |
| Brother PT-9500PC                    | 1         | 1.82%   |
| Brother Printer                      | 1         | 1.82%   |
| Brother MFC-L2710DW series           | 1         | 1.82%   |
| Brother MFC-L2707DW                  | 1         | 1.82%   |
| Brother HL-5370DW series             | 1         | 1.82%   |
| Brother HL-2240 series               | 1         | 1.82%   |
| Brother HL-2030 Laser Printer        | 1         | 1.82%   |
| Brother FAX-2940                     | 1         | 1.82%   |
| Brother DCP-L2500D                   | 1         | 1.82%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 8         | 47.06%  |
| Seiko Epson     | 5         | 29.41%  |
| Hewlett-Packard | 3         | 17.65%  |
| AGFA-Gevaert NV | 1         | 5.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 11.76%  |
| Canon CanoScan LiDE 120                                  | 2         | 11.76%  |
| Canon CanoScan LiDE 110                                  | 2         | 11.76%  |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1         | 5.88%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 5.88%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 1         | 5.88%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]            | 1         | 5.88%   |
| Seiko Epson GT-7700U [Perfection 1240U]                  | 1         | 5.88%   |
| HP ScanJet Pro 2500 f1                                   | 1         | 5.88%   |
| HP ScanJet 3970c                                         | 1         | 5.88%   |
| HP Scanjet 300                                           | 1         | 5.88%   |
| Canon CanoScan LIDE 25                                   | 1         | 5.88%   |
| Canon CanoScan LiDE 220                                  | 1         | 5.88%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                       | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 344       | 24.29%  |
| Acer                                   | 227       | 16.03%  |
| IMC Networks                           | 119       | 8.4%    |
| Quanta                                 | 105       | 7.42%   |
| Microdia                               | 95        | 6.71%   |
| Realtek Semiconductor                  | 83        | 5.86%   |
| Logitech                               | 74        | 5.23%   |
| Sunplus Innovation Technology          | 48        | 3.39%   |
| Apple                                  | 41        | 2.9%    |
| Cheng Uei Precision Industry (Foxlink) | 40        | 2.82%   |
| Suyin                                  | 31        | 2.19%   |
| Lite-On Technology                     | 26        | 1.84%   |
| Syntek                                 | 22        | 1.55%   |
| Luxvisions Innotech Limited            | 20        | 1.41%   |
| Silicon Motion                         | 12        | 0.85%   |
| Lenovo                                 | 11        | 0.78%   |
| Generalplus Technology                 | 10        | 0.71%   |
| Z-Star Microelectronics                | 9         | 0.64%   |
| Alcor Micro                            | 9         | 0.64%   |
| Ricoh                                  | 8         | 0.56%   |
| Samsung Electronics                    | 6         | 0.42%   |
| Microsoft                              | 6         | 0.42%   |
| Primax Electronics                     | 5         | 0.35%   |
| KYE Systems (Mouse Systems)            | 4         | 0.28%   |
| Creative Technology                    | 4         | 0.28%   |
| SunplusIT                              | 3         | 0.21%   |
| Mimaki Engineering                     | 3         | 0.21%   |
| Intel                                  | 3         | 0.21%   |
| Importek                               | 3         | 0.21%   |
| Genesys Logic                          | 3         | 0.21%   |
| ARC International                      | 3         | 0.21%   |
| Xiongmai                               | 2         | 0.14%   |
| Unknown                                | 2         | 0.14%   |
| Sonix Technology                       | 2         | 0.14%   |
| OmniVision Technologies                | 2         | 0.14%   |
| Novatek Microelectronics               | 2         | 0.14%   |
| Jieli Technology                       | 2         | 0.14%   |
| eMPIA Technology                       | 2         | 0.14%   |
| ALi                                    | 2         | 0.14%   |
| Y Media                                | 1         | 0.07%   |
| Xiaomi                                 | 1         | 0.07%   |
| USB Camera                             | 1         | 0.07%   |
| U0AS01A-0                              | 1         | 0.07%   |
| Sunplus Technology                     | 1         | 0.07%   |
| SiGma Micro                            | 1         | 0.07%   |
| Ruision                                | 1         | 0.07%   |
| Razer USA                              | 1         | 0.07%   |
| Pixart Imaging                         | 1         | 0.07%   |
| Philips (or NXP)                       | 1         | 0.07%   |
| Nintendo                               | 1         | 0.07%   |
| MacroSilicon                           | 1         | 0.07%   |
| LG Electronics                         | 1         | 0.07%   |
| Huawei Technologies                    | 1         | 0.07%   |
| Holitech                               | 1         | 0.07%   |
| Hewlett-Packard                        | 1         | 0.07%   |
| HD 2MP WEBCAM                          | 1         | 0.07%   |
| Google                                 | 1         | 0.07%   |
| DJKANA1BIFZTDM                         | 1         | 0.07%   |
| AVerMedia Technologies                 | 1         | 0.07%   |
| Arkmicro Technologies                  | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 137       | 9.45%   |
| Acer Integrated Camera                                                     | 111       | 7.66%   |
| Acer Integrated 5M Camera                                                  | 68        | 4.69%   |
| IMC Networks Integrated Camera                                             | 44        | 3.03%   |
| Microdia Integrated_Webcam_HD                                              | 43        | 2.97%   |
| Chicony Integrated 5M Camera                                               | 43        | 2.97%   |
| Quanta Chromebook HD Camera                                                | 37        | 2.55%   |
| Realtek Integrated_Webcam_HD                                               | 28        | 1.93%   |
| Chicony HD Webcam                                                          | 28        | 1.93%   |
| Acer BisonCam, NB Pro                                                      | 25        | 1.72%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 24        | 1.66%   |
| Logitech Webcam C270                                                       | 21        | 1.45%   |
| Sunplus Integrated_Webcam_HD                                               | 19        | 1.31%   |
| Quanta VGA WebCam                                                          | 18        | 1.24%   |
| Apple Built-in iSight                                                      | 17        | 1.17%   |
| Quanta HP TrueVision HD Camera                                             | 15        | 1.03%   |
| Syntek Integrated Camera                                                   | 12        | 0.83%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 12        | 0.83%   |
| Chicony HP HD Camera                                                       | 12        | 0.83%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 12        | 0.83%   |
| Acer SunplusIT Integrated Camera                                           | 12        | 0.83%   |
| Lite-On Integrated Camera                                                  | 11        | 0.76%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 11        | 0.76%   |
| Logitech HD Pro Webcam C920                                                | 10        | 0.69%   |
| Chicony Chromebook HD Camera                                               | 10        | 0.69%   |
| Acer Lenovo EasyCamera                                                     | 10        | 0.69%   |
| Realtek USB Camera                                                         | 9         | 0.62%   |
| Quanta HD User Facing                                                      | 8         | 0.55%   |
| Logitech C922 Pro Stream Webcam                                            | 8         | 0.55%   |
| Chicony Integrated Camera (1280x720@30)                                    | 8         | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 8         | 0.55%   |
| Quanta HP HD Camera                                                        | 7         | 0.48%   |
| Quanta HD Webcam                                                           | 7         | 0.48%   |
| Microdia Webcam Vitade AF                                                  | 7         | 0.48%   |
| Lite-On HP HD Camera                                                       | 7         | 0.48%   |
| Lenovo Integrated Webcam                                                   | 7         | 0.48%   |
| Chicony Lenovo EasyCamera                                                  | 7         | 0.48%   |
| Chicony HD User Facing                                                     | 7         | 0.48%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 6         | 0.41%   |
| Realtek Lenovo EasyCamera                                                  | 6         | 0.41%   |
| Realtek Integrated Webcam                                                  | 6         | 0.41%   |
| Quanta HP Webcam                                                           | 6         | 0.41%   |
| Microdia Integrated Webcam                                                 | 6         | 0.41%   |
| Logitech Webcam C170                                                       | 6         | 0.41%   |
| Generalplus GENERAL WEBCAM                                                 | 6         | 0.41%   |
| Chicony HP Webcam                                                          | 6         | 0.41%   |
| Chicony HP Truevision HD                                                   | 6         | 0.41%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 6         | 0.41%   |
| Acer Lenovo Integrated Webcam                                              | 6         | 0.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 5         | 0.34%   |
| Sunplus HD WebCam                                                          | 5         | 0.34%   |
| Realtek EasyCamera                                                         | 5         | 0.34%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 5         | 0.34%   |
| Microdia Hy-HD-Camera                                                      | 5         | 0.34%   |
| Logitech HD Webcam C615                                                    | 5         | 0.34%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 5         | 0.34%   |
| IMC Networks HD Camera                                                     | 5         | 0.34%   |
| Chicony USB2.0 HD UVC WebCam                                               | 5         | 0.34%   |
| Chicony USB2.0 Camera                                                      | 5         | 0.34%   |
| Chicony EasyCamera                                                         | 5         | 0.34%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 185       | 53.16%  |
| Validity Sensors           | 80        | 22.99%  |
| Shenzhen Goodix Technology | 33        | 9.48%   |
| Upek                       | 14        | 4.02%   |
| Elan Microelectronics      | 11        | 3.16%   |
| AuthenTec                  | 10        | 2.87%   |
| LighTuning Technology      | 9         | 2.59%   |
| STMicroelectronics         | 5         | 1.44%   |
| Samsung Electronics        | 1         | 0.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 140       | 40.23%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 28        | 8.05%   |
| Shenzhen Goodix  Fingerprint Device                                        | 18        | 5.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 4.31%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 4.31%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 3.74%   |
| Unknown                                                                    | 13        | 3.74%   |
| Shenzhen Goodix FingerPrint                                                | 9         | 2.59%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 2.3%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.3%    |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.01%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 1.72%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.72%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.44%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.44%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.15%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.15%   |
| Synaptics  WBDI                                                            | 4         | 1.15%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.15%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.15%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.86%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.86%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.57%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.57%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.57%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.57%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.57%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.57%   |
| Validity Sensors VFS491                                                    | 1         | 0.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.29%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.29%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.29%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.29%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.29%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.29%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.29%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.29%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.29%   |
| AuthenTec AES1600                                                          | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 41        | 33.88%  |
| Broadcom                  | 38        | 31.4%   |
| Upek                      | 14        | 11.57%  |
| Lenovo                    | 10        | 8.26%   |
| O2 Micro                  | 7         | 5.79%   |
| Gemalto (was Gemplus)     | 3         | 2.48%   |
| Aladdin Knowledge Systems | 2         | 1.65%   |
| Yubico.com                | 1         | 0.83%   |
| SCM Microsystems          | 1         | 0.83%   |
| OmniKey                   | 1         | 0.83%   |
| Clay Logic                | 1         | 0.83%   |
| Chicony Electronics       | 1         | 0.83%   |
| Cherry                    | 1         | 0.83%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 41        | 33.88%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 11.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 8.26%   |
| Broadcom 5880                                                                | 10        | 8.26%   |
| Broadcom 58200                                                               | 10        | 8.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 5.79%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 4.96%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.65%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.65%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.83%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.83%   |
| OmniKey CardMan 4321                                                         | 1         | 0.83%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.83%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.83%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.83%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.83%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.83%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1717      | 58.09%  |
| 1     | 1040      | 35.18%  |
| 2     | 159       | 5.38%   |
| 3     | 33        | 1.12%   |
| 4     | 5         | 0.17%   |
| 5     | 2         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 560       | 40.06%  |
| Fingerprint reader       | 345       | 24.68%  |
| Multimedia controller    | 180       | 12.88%  |
| Chipcard                 | 106       | 7.58%   |
| Net/wireless             | 75        | 5.36%   |
| Communication controller | 31        | 2.22%   |
| Bluetooth                | 24        | 1.72%   |
| Unassigned class         | 16        | 1.14%   |
| Card reader              | 13        | 0.93%   |
| Storage                  | 12        | 0.86%   |
| Sound                    | 10        | 0.72%   |
| Net/ethernet             | 5         | 0.36%   |
| Camera                   | 5         | 0.36%   |
| Network                  | 4         | 0.29%   |
| Tv card                  | 3         | 0.21%   |
| Modem                    | 3         | 0.21%   |
| Flash memory             | 2         | 0.14%   |
| Dvb card                 | 2         | 0.14%   |
| Storage/ide              | 1         | 0.07%   |
| Firewire controller      | 1         | 0.07%   |

