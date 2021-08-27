Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6ed5f8c32b](https://linux-hardware.org/?probe=6ed5f8c32b) | Aug 27, 2021 |
| ASRock        | Z390 Phantom Gaming 4-IB    | Desktop     | [b01269fbc1](https://linux-hardware.org/?probe=b01269fbc1) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [c59a1fff0d](https://linux-hardware.org/?probe=c59a1fff0d) | Aug 26, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [accc3b9ebb](https://linux-hardware.org/?probe=accc3b9ebb) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| Acer          | AO722                       | Notebook    | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| HP            | 802E                        | Desktop     | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [8620323354](https://linux-hardware.org/?probe=8620323354) | Aug 25, 2021 |
| TianBei       | TB-H7                       | Notebook    | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Dell          | 0TP406                      | Desktop     | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| HP            | 2B4B                        | Desktop     | [4c5411522b](https://linux-hardware.org/?probe=4c5411522b) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | Notebook    | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | Notebook    | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [a720e3326a](https://linux-hardware.org/?probe=a720e3326a) | Aug 23, 2021 |
| Acer          | Aspire 8940G                | Notebook    | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | Notebook    | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | Notebook    | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [e6f053c5be](https://linux-hardware.org/?probe=e6f053c5be) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [8eed93b589](https://linux-hardware.org/?probe=8eed93b589) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [372a125910](https://linux-hardware.org/?probe=372a125910) | Aug 22, 2021 |
| Lenovo        | Board                       | Desktop     | [b4e9579228](https://linux-hardware.org/?probe=b4e9579228) | Aug 21, 2021 |
| Lenovo        | Board                       | Desktop     | [12088eed17](https://linux-hardware.org/?probe=12088eed17) | Aug 21, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [68c6a2734b](https://linux-hardware.org/?probe=68c6a2734b) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | Notebook    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | Notebook    | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | Notebook    | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | Notebook    | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [4bbb9f60f9](https://linux-hardware.org/?probe=4bbb9f60f9) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [0acfc1ab65](https://linux-hardware.org/?probe=0acfc1ab65) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [27898f0b8e](https://linux-hardware.org/?probe=27898f0b8e) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | Notebook    | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | Notebook    | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d78450d852](https://linux-hardware.org/?probe=d78450d852) | Aug 19, 2021 |
| Acer          | Aspire XC-605G              | Desktop     | [8bb6f8ef72](https://linux-hardware.org/?probe=8bb6f8ef72) | Aug 18, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [daf6bf889f](https://linux-hardware.org/?probe=daf6bf889f) | Aug 18, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [3be5b7f90e](https://linux-hardware.org/?probe=3be5b7f90e) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [06872ddde7](https://linux-hardware.org/?probe=06872ddde7) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [65567a1be4](https://linux-hardware.org/?probe=65567a1be4) | Aug 10, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | Desktop     | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [01e77d1c5f](https://linux-hardware.org/?probe=01e77d1c5f) | Aug 04, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [c5d61df0df](https://linux-hardware.org/?probe=c5d61df0df) | Aug 03, 2021 |
| Gigabyte      | B550M H                     | Desktop     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [733eb370f2](https://linux-hardware.org/?probe=733eb370f2) | Jul 27, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [79b20f33a0](https://linux-hardware.org/?probe=79b20f33a0) | Jul 24, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [94ef768b69](https://linux-hardware.org/?probe=94ef768b69) | Jul 24, 2021 |
| Acer          | Aspire E5-551G              | Notebook    | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [3bed53aab7](https://linux-hardware.org/?probe=3bed53aab7) | Jul 14, 2021 |
| Dell          | 0V8WGR A00                  | Desktop     | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Dell          | XPS L501X                   | Notebook    | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | Notebook    | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI           | 2AE0                        | Desktop     | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI           | 2AE0                        | Desktop     | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| Dell          | Inspiron 3582               | Notebook    | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [b9d86eb932](https://linux-hardware.org/?probe=b9d86eb932) | Jun 17, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [71de5617aa](https://linux-hardware.org/?probe=71de5617aa) | Jun 17, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | Notebook    | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| HP            | 843C                        | Desktop     | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | Notebook    | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP            | 8591                        | Desktop     | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP            | 8591                        | Desktop     | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| HP            | Unknown                     | Notebook    | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | Notebook    | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar       | A320MH                      | Desktop     | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar       | A320MH                      | Desktop     | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c41eec9cd3](https://linux-hardware.org/?probe=c41eec9cd3) | May 21, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | Notebook    | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Quanta        | XV1                         | All in one  | [d3b0fddedf](https://linux-hardware.org/?probe=d3b0fddedf) | May 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Quanta        | XV1                         | All in one  | [5d38d7934e](https://linux-hardware.org/?probe=5d38d7934e) | Apr 30, 2021 |
| Pegatron      | Benicia                     | Desktop     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [236ed4432a](https://linux-hardware.org/?probe=236ed4432a) | Apr 24, 2021 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek       | P5K                         | Desktop     | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell          | 0PGKWF A02                  | Desktop     | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0761ed6181](https://linux-hardware.org/?probe=0761ed6181) | Apr 16, 2021 |
| Acer          | Aspire XC-605G              | Desktop     | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-27-generic | 54        | 45%     |
| 5.8.0-53-generic  | 13        | 10.83%  |
| 5.8.0-50-generic  | 12        | 10%     |
| 5.11.0-25-generic | 12        | 10%     |
| 5.8.0-55-generic  | 10        | 8.33%   |
| 5.8.0-59-generic  | 8         | 6.67%   |
| 5.8.0-63-generic  | 4         | 3.33%   |
| 5.8.0-49-generic  | 4         | 3.33%   |
| 5.8.0-45-generic  | 1         | 0.83%   |
| 5.4.0-42-generic  | 1         | 0.83%   |
| 5.10.0-1044-oem   | 1         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 66        | 55.46%  |
| 5.8.0   | 51        | 42.86%  |
| 5.4.0   | 1         | 0.84%   |
| 5.10.0  | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 66        | 55.46%  |
| 5.8     | 51        | 42.86%  |
| 5.4     | 1         | 0.84%   |
| 5.10    | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 118       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME    | 117       | 98.32%  |
| XFCE     | 1         | 0.84%   |
| Cinnamon | 1         | 0.84%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 116       | 98.31%  |
| Wayland | 2         | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 105       | 88.98%  |
| GDM     | 12        | 10.17%  |
| TDM     | 1         | 0.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 41        | 34.75%  |
| de_DE | 16        | 13.56%  |
| pt_BR | 11        | 9.32%   |
| en_GB | 9         | 7.63%   |
| es_ES | 6         | 5.08%   |
| en_IN | 6         | 5.08%   |
| pl_PL | 4         | 3.39%   |
| nl_NL | 3         | 2.54%   |
| hu_HU | 3         | 2.54%   |
| es_PE | 2         | 1.69%   |
| es_MX | 2         | 1.69%   |
| en_ZA | 2         | 1.69%   |
| zh_TW | 1         | 0.85%   |
| ru_UA | 1         | 0.85%   |
| nl_BE | 1         | 0.85%   |
| ja_JP | 1         | 0.85%   |
| it_IT | 1         | 0.85%   |
| fr_FR | 1         | 0.85%   |
| es_CO | 1         | 0.85%   |
| es_CL | 1         | 0.85%   |
| en_SG | 1         | 0.85%   |
| en_PH | 1         | 0.85%   |
| en_NZ | 1         | 0.85%   |
| en_CA | 1         | 0.85%   |
| bg_BG | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 79        | 66.39%  |
| BIOS | 40        | 33.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 111       | 94.07%  |
| Overlay | 4         | 3.39%   |
| Zfs     | 1         | 0.85%   |
| Ext3    | 1         | 0.85%   |
| Btrfs   | 1         | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 105       | 88.98%  |
| GPT     | 12        | 10.17%  |
| MBR     | 1         | 0.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 116       | 97.48%  |
| Yes       | 3         | 2.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 103       | 87.29%  |
| Yes       | 15        | 12.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 22        | 18.64%  |
| ASUSTek Computer    | 22        | 18.64%  |
| Dell                | 16        | 13.56%  |
| Hewlett-Packard     | 14        | 11.86%  |
| Acer                | 10        | 8.47%   |
| Gigabyte Technology | 8         | 6.78%   |
| Apple               | 6         | 5.08%   |
| MSI                 | 4         | 3.39%   |
| LG Electronics      | 3         | 2.54%   |
| Intel               | 2         | 1.69%   |
| Fujitsu             | 2         | 1.69%   |
| ASRock              | 2         | 1.69%   |
| TianBei             | 1         | 0.85%   |
| Sony                | 1         | 0.85%   |
| Razer               | 1         | 0.85%   |
| Quanta              | 1         | 0.85%   |
| Pegatron            | 1         | 0.85%   |
| Biostar             | 1         | 0.85%   |
| Unknown             | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ASUS All Series                         | 3         | 2.54%   |
| Dell OptiPlex 990                       | 2         | 1.69%   |
| ASUS M5A78L-M/USB3                      | 2         | 1.69%   |
| Unknown                                 | 2         | 1.69%   |
| TianBei TB-H7                           | 1         | 0.85%   |
| Sony VGN-SR5                            | 1         | 0.85%   |
| Razer Book 13 - RZ09-0357               | 1         | 0.85%   |
| Quanta CA27                             | 1         | 0.85%   |
| Pegatron NE502AV-ABA a6750t             | 1         | 0.85%   |
| MSI Pro 3515 Series                     | 1         | 0.85%   |
| MSI MS-7B84                             | 1         | 0.85%   |
| MSI MS-7A71                             | 1         | 0.85%   |
| MSI MS-7914                             | 1         | 0.85%   |
| LG S460-G.BG31P1                        | 1         | 0.85%   |
| LG A410-K.BE47P1                        | 1         | 0.85%   |
| LG 17U70N-R.AAS7U1                      | 1         | 0.85%   |
| Lenovo Yoga C740-15IML 81TD             | 1         | 0.85%   |
| Lenovo Yoga 730-13IWL 81JR              | 1         | 0.85%   |
| Lenovo Yoga 330-11IGM 81A6              | 1         | 0.85%   |
| Lenovo Yoga 3 Pro-1370 80HE             | 1         | 0.85%   |
| Lenovo ThinkPad Yoga 11e 20DAS0SF00     | 1         | 0.85%   |
| Lenovo ThinkPad X131e 3371AL2           | 1         | 0.85%   |
| Lenovo ThinkPad T440p 20AWS1CH00        | 1         | 0.85%   |
| Lenovo ThinkPad E15 Gen 2 20TD000HZA    | 1         | 0.85%   |
| Lenovo ThinkCentre M83 MT-M 10AJ-0003MB | 1         | 0.85%   |
| Lenovo ThinkCentre M78 10BTA00ELM       | 1         | 0.85%   |
| Lenovo SHARKBAY SDK0E50510 WIN          | 1         | 0.85%   |
| Lenovo IdeaPad Z510 20287               | 1         | 0.85%   |
| Lenovo IdeaPad Y570 0862                | 1         | 0.85%   |
| Lenovo IdeaPad S540-14API 81NH          | 1         | 0.85%   |
| Lenovo IdeaPad 5 15ALC05 82LN           | 1         | 0.85%   |
| Lenovo IdeaPad 330-15IKB 81DE           | 1         | 0.85%   |
| Lenovo IdeaPad 3 14ADA05 81W0           | 1         | 0.85%   |
| Lenovo IdeaPad 100-15IBD 80QQ           | 1         | 0.85%   |
| Lenovo IdeaCentre 510S-08IKL 90GB004RUS | 1         | 0.85%   |
| Lenovo G50-70 20351                     | 1         | 0.85%   |
| Lenovo G50-30 80G0                      | 1         | 0.85%   |
| Lenovo Board                            | 1         | 0.85%   |
| Intel NUC11PAHi7                        | 1         | 0.85%   |
| Intel DB75EN AAG39650-303               | 1         | 0.85%   |
| HP Z240 SFF Workstation                 | 1         | 0.85%   |
| HP Z1 Entry Tower G5                    | 1         | 0.85%   |
| HP ProBook 650 G2                       | 1         | 0.85%   |
| HP ProBook 450 G2                       | 1         | 0.85%   |
| HP ProBook 430 G6                       | 1         | 0.85%   |
| HP Pavilion All-in-One 24-xa0xxx        | 1         | 0.85%   |
| HP Notebook                             | 1         | 0.85%   |
| HP ENVY x360 Convertible 15m-ee0xxx     | 1         | 0.85%   |
| HP ENVY Sleekbook 4 PC                  | 1         | 0.85%   |
| HP ENVY 14                              | 1         | 0.85%   |
| HP 870-158ng                            | 1         | 0.85%   |
| HP 290 G2 MT Business PC                | 1         | 0.85%   |
| HP 15                                   | 1         | 0.85%   |
| Gigabyte Komputer OPTIMUS               | 1         | 0.85%   |
| Gigabyte H61M-USB3-B3                   | 1         | 0.85%   |
| Gigabyte B85M-D3H                       | 1         | 0.85%   |
| Gigabyte B85-HD3                        | 1         | 0.85%   |
| Gigabyte B550M H                        | 1         | 0.85%   |
| Gigabyte B550M DS3H                     | 1         | 0.85%   |
| Gigabyte B450 AORUS ELITE               | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 7         | 5.93%   |
| Dell Inspiron         | 7         | 5.93%   |
| Acer Aspire           | 6         | 5.08%   |
| Lenovo Yoga           | 4         | 3.39%   |
| Lenovo ThinkPad       | 4         | 3.39%   |
| HP ProBook            | 3         | 2.54%   |
| HP ENVY               | 3         | 2.54%   |
| Dell XPS              | 3         | 2.54%   |
| ASUS PRIME            | 3         | 2.54%   |
| ASUS All              | 3         | 2.54%   |
| Lenovo ThinkCentre    | 2         | 1.69%   |
| Gigabyte B550M        | 2         | 1.69%   |
| Dell OptiPlex         | 2         | 1.69%   |
| ASUS P8Z77-V          | 2         | 1.69%   |
| ASUS M5A97            | 2         | 1.69%   |
| ASUS M5A78L-M         | 2         | 1.69%   |
| Acer Swift            | 2         | 1.69%   |
| Unknown               | 2         | 1.69%   |
| TianBei TB-H7         | 1         | 0.85%   |
| Sony VGN-SR5          | 1         | 0.85%   |
| Razer Book            | 1         | 0.85%   |
| Quanta CA27           | 1         | 0.85%   |
| Pegatron NE502AV-ABA  | 1         | 0.85%   |
| MSI Pro               | 1         | 0.85%   |
| MSI MS-7B84           | 1         | 0.85%   |
| MSI MS-7A71           | 1         | 0.85%   |
| MSI MS-7914           | 1         | 0.85%   |
| LG S460-G.BG31P1      | 1         | 0.85%   |
| LG A410-K.BE47P1      | 1         | 0.85%   |
| LG 17U70N-R.AAS7U1    | 1         | 0.85%   |
| Lenovo SHARKBAY       | 1         | 0.85%   |
| Lenovo IdeaCentre     | 1         | 0.85%   |
| Lenovo G50-70         | 1         | 0.85%   |
| Lenovo G50-30         | 1         | 0.85%   |
| Lenovo Board          | 1         | 0.85%   |
| Intel NUC11PAHi7      | 1         | 0.85%   |
| Intel DB75EN          | 1         | 0.85%   |
| HP Z240               | 1         | 0.85%   |
| HP Z1                 | 1         | 0.85%   |
| HP Pavilion           | 1         | 0.85%   |
| HP Notebook           | 1         | 0.85%   |
| HP 870-158ng          | 1         | 0.85%   |
| HP 290                | 1         | 0.85%   |
| HP 15                 | 1         | 0.85%   |
| Gigabyte Komputer     | 1         | 0.85%   |
| Gigabyte H61M-USB3-B3 | 1         | 0.85%   |
| Gigabyte B85M-D3H     | 1         | 0.85%   |
| Gigabyte B85-HD3      | 1         | 0.85%   |
| Gigabyte B450         | 1         | 0.85%   |
| Gigabyte A320M-S2H    | 1         | 0.85%   |
| Fujitsu LIFEBOOK      | 1         | 0.85%   |
| Fujitsu ESPRIMO       | 1         | 0.85%   |
| Dell XPS420           | 1         | 0.85%   |
| Dell Vostro           | 1         | 0.85%   |
| Dell Precision        | 1         | 0.85%   |
| Dell G3               | 1         | 0.85%   |
| Biostar A320MH        | 1         | 0.85%   |
| ASUS X550LD           | 1         | 0.85%   |
| ASUS X406UAR          | 1         | 0.85%   |
| ASUS UNLOCK           | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 21        | 17.8%   |
| 2020 | 20        | 16.95%  |
| 2019 | 15        | 12.71%  |
| 2014 | 15        | 12.71%  |
| 2018 | 10        | 8.47%   |
| 2015 | 7         | 5.93%   |
| 2012 | 6         | 5.08%   |
| 2011 | 6         | 5.08%   |
| 2016 | 4         | 3.39%   |
| 2008 | 4         | 3.39%   |
| 2013 | 3         | 2.54%   |
| 2009 | 3         | 2.54%   |
| 2010 | 2         | 1.69%   |
| 2017 | 1         | 0.85%   |
| 2007 | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 58        | 49.15%  |
| Desktop     | 49        | 41.53%  |
| All in one  | 6         | 5.08%   |
| Convertible | 4         | 3.39%   |
| Mini pc     | 1         | 0.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 101       | 85.59%  |
| Enabled  | 17        | 14.41%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 118       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 29        | 24.17%  |
| 4.01-8.0    | 27        | 22.5%   |
| 16.01-24.0  | 26        | 21.67%  |
| 3.01-4.0    | 23        | 19.17%  |
| 32.01-64.0  | 11        | 9.17%   |
| 64.01-256.0 | 2         | 1.67%   |
| 1.01-2.0    | 2         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 55        | 45.45%  |
| 2.01-3.0 | 38        | 31.4%   |
| 3.01-4.0 | 16        | 13.22%  |
| 4.01-8.0 | 9         | 7.44%   |
| 0.51-1.0 | 3         | 2.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 64        | 54.24%  |
| 2      | 31        | 26.27%  |
| 3      | 10        | 8.47%   |
| 4      | 8         | 6.78%   |
| 5      | 3         | 2.54%   |
| 8      | 1         | 0.85%   |
| 0      | 1         | 0.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 50.42%  |
| Yes       | 59        | 49.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 89.08%  |
| No        | 13        | 10.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 74.58%  |
| No        | 30        | 25.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 61.02%  |
| No        | 46        | 38.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25        | 21.19%  |
| Germany      | 20        | 16.95%  |
| Brazil       | 13        | 11.02%  |
| UK           | 8         | 6.78%   |
| India        | 7         | 5.93%   |
| Spain        | 6         | 5.08%   |
| Poland       | 3         | 2.54%   |
| Netherlands  | 3         | 2.54%   |
| Mexico       | 3         | 2.54%   |
| Hungary      | 3         | 2.54%   |
| Taiwan       | 2         | 1.69%   |
| South Africa | 2         | 1.69%   |
| Colombia     | 2         | 1.69%   |
| Canada       | 2         | 1.69%   |
| Australia    | 2         | 1.69%   |
| Vietnam      | 1         | 0.85%   |
| Ukraine      | 1         | 0.85%   |
| Switzerland  | 1         | 0.85%   |
| Romania      | 1         | 0.85%   |
| Philippines  | 1         | 0.85%   |
| Peru         | 1         | 0.85%   |
| New Zealand  | 1         | 0.85%   |
| Malaysia     | 1         | 0.85%   |
| Madagascar   | 1         | 0.85%   |
| Japan        | 1         | 0.85%   |
| Italy        | 1         | 0.85%   |
| France       | 1         | 0.85%   |
| Denmark      | 1         | 0.85%   |
| Chile        | 1         | 0.85%   |
| Bulgaria     | 1         | 0.85%   |
| Belgium      | 1         | 0.85%   |
| Austria      | 1         | 0.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Vancouver                | 2         | 1.69%   |
| Hyderabad                | 2         | 1.69%   |
| Zurich                   | 1         | 0.85%   |
| Yokohama                 | 1         | 0.85%   |
| Xalapa                   | 1         | 0.85%   |
| Vienna                   | 1         | 0.85%   |
| Vespasiano               | 1         | 0.85%   |
| Trujillo                 | 1         | 0.85%   |
| Taboao da Serra          | 1         | 0.85%   |
| São Bernardo do Campo   | 1         | 0.85%   |
| Szombathely              | 1         | 0.85%   |
| Szczecin                 | 1         | 0.85%   |
| Sutton Coldfield         | 1         | 0.85%   |
| Stadskanaal              | 1         | 0.85%   |
| St. Cloud                | 1         | 0.85%   |
| Spremberg                | 1         | 0.85%   |
| Seville                  | 1         | 0.85%   |
| S??o Lu?�s               | 1         | 0.85%   |
| S??o Jo??o del Rei       | 1         | 0.85%   |
| Santa Cruz de Tenerife   | 1         | 0.85%   |
| Sant Carles de la Rapita | 1         | 0.85%   |
| San Francisco            | 1         | 0.85%   |
| Sainte-Marie             | 1         | 0.85%   |
| Sacramento               | 1         | 0.85%   |
| Rome                     | 1         | 0.85%   |
| Rio de Janeiro           | 1         | 0.85%   |
| R??sselsheim am Main     | 1         | 0.85%   |
| Rancagua                 | 1         | 0.85%   |
| Quezon City              | 1         | 0.85%   |
| Pretoria                 | 1         | 0.85%   |
| Porto Seguro             | 1         | 0.85%   |
| Pascoag                  | 1         | 0.85%   |
| Palm Coast               | 1         | 0.85%   |
| Oscoda                   | 1         | 0.85%   |
| Ohmbach                  | 1         | 0.85%   |
| Oak Creek                | 1         | 0.85%   |
| Nyiregyhaza              | 1         | 0.85%   |
| Nottingham               | 1         | 0.85%   |
| Noblesville              | 1         | 0.85%   |
| Niter??i                 | 1         | 0.85%   |
| New Taipei               | 1         | 0.85%   |
| Mérida                  | 1         | 0.85%   |
| Mumbai                   | 1         | 0.85%   |
| Morro do Chapeu          | 1         | 0.85%   |
| Montana                  | 1         | 0.85%   |
| Monheim am Rhein         | 1         | 0.85%   |
| Miami                    | 1         | 0.85%   |
| Mexico City              | 1         | 0.85%   |
| Mentor                   | 1         | 0.85%   |
| Melbourne                | 1         | 0.85%   |
| Manchester               | 1         | 0.85%   |
| Madrid                   | 1         | 0.85%   |
| Macei??                  | 1         | 0.85%   |
| Ludwigsburg              | 1         | 0.85%   |
| London                   | 1         | 0.85%   |
| Littleton                | 1         | 0.85%   |
| Laziska Gorne            | 1         | 0.85%   |
| Lathen                   | 1         | 0.85%   |
| Landshut                 | 1         | 0.85%   |
| Kyiv                     | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 36        | 46     | 19.67%  |
| Samsung Electronics       | 27        | 32     | 14.75%  |
| WDC                       | 25        | 33     | 13.66%  |
| Sandisk                   | 17        | 20     | 9.29%   |
| Kingston                  | 14        | 17     | 7.65%   |
| Toshiba                   | 11        | 11     | 6.01%   |
| Unknown                   | 6         | 8      | 3.28%   |
| Apple                     | 4         | 4      | 2.19%   |
| Phison                    | 3         | 3      | 1.64%   |
| Intel                     | 3         | 3      | 1.64%   |
| HGST                      | 3         | 3      | 1.64%   |
| A-DATA Technology         | 3         | 3      | 1.64%   |
| Silicon Motion            | 2         | 4      | 1.09%   |
| Micron/Crucial Technology | 2         | 2      | 1.09%   |
| LITEONIT                  | 2         | 3      | 1.09%   |
| Intenso                   | 2         | 2      | 1.09%   |
| Fujitsu                   | 2         | 2      | 1.09%   |
| Crucial                   | 2         | 3      | 1.09%   |
| China                     | 2         | 2      | 1.09%   |
| XPG                       | 1         | 1      | 0.55%   |
| Vaseky                    | 1         | 1      | 0.55%   |
| USB30                     | 1         | 2      | 0.55%   |
| SK Hynix                  | 1         | 1      | 0.55%   |
| Patriot                   | 1         | 1      | 0.55%   |
| OCZ                       | 1         | 1      | 0.55%   |
| Maxtor                    | 1         | 1      | 0.55%   |
| Lexar                     | 1         | 1      | 0.55%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.55%   |
| KIOXIA                    | 1         | 1      | 0.55%   |
| KingSpec                  | 1         | 1      | 0.55%   |
| KingFast                  | 1         | 1      | 0.55%   |
| JMicron                   | 1         | 1      | 0.55%   |
| Hitachi                   | 1         | 2      | 0.55%   |
| Hewlett-Packard           | 1         | 1      | 0.55%   |
| BUFFALO                   | 1         | 1      | 0.55%   |
| Apacer                    | 1         | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 64GB           | 4         | 1.97%   |
| WDC WD10EZEX-08WN4A0 1TB             | 3         | 1.48%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 1.48%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.48%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 1.48%   |
| SanDisk SSD PLUS 1000GB              | 3         | 1.48%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.48%   |
| WDC WD10EZEX-60M2NA0 1TB             | 2         | 0.99%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.99%   |
| Silicon Motion NVMe SSD Drive 128GB  | 2         | 0.99%   |
| Seagate ST9500325AS 500GB            | 2         | 0.99%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 0.99%   |
| Seagate ST2000DM001-9YN164 2TB       | 2         | 0.99%   |
| SanDisk SSD PLUS 480GB               | 2         | 0.99%   |
| Sandisk NVMe SSD Drive 256GB         | 2         | 0.99%   |
| Samsung SSD 860 EVO 1TB              | 2         | 0.99%   |
| Samsung SSD 840 EVO 250GB            | 2         | 0.99%   |
| Samsung NVMe SSD Drive 512GB         | 2         | 0.99%   |
| Samsung NVMe SSD Drive 500GB         | 2         | 0.99%   |
| Phison NVMe SSD Drive 1TB            | 2         | 0.99%   |
| Kingston SV300S37A240G 240GB SSD     | 2         | 0.99%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.99%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.99%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.99%   |
| Intenso SSD SATAIII 960GB            | 2         | 0.99%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.99%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 0.99%   |
| XPG NVMe SSD Drive 1024GB            | 1         | 0.49%   |
| WDC WDS250G2B0A-00SM50 250GB SSD     | 1         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.49%   |
| WDC WD7500AARS-00Y5B1 752GB          | 1         | 0.49%   |
| WDC WD5000LPVT-22G33T0 500GB         | 1         | 0.49%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.49%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 1         | 0.49%   |
| WDC WD5000AAKS-00YGA0 500GB          | 1         | 0.49%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 0.49%   |
| WDC WD40EZAZ-00SF3B0 4TB             | 1         | 0.49%   |
| WDC WD3200BUCT-63TWBY0 320GB         | 1         | 0.49%   |
| WDC WD30EZRX-00D8PB0 3TB             | 1         | 0.49%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.49%   |
| WDC WD20EURX-61T0FY0 2TB             | 1         | 0.49%   |
| WDC WD20EFRX-68EUZN0 2TB             | 1         | 0.49%   |
| WDC WD1600AAJS-75M0A0 160GB          | 1         | 0.49%   |
| WDC WD1600AAJS-22PSA0 160GB          | 1         | 0.49%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.49%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.49%   |
| WDC WD10EZEX-75M2NA0 1TB             | 1         | 0.49%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1         | 0.49%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 0.49%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 0.49%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1         | 0.49%   |
| WDC WD1002FAEX-00Y9A0 1TB            | 1         | 0.49%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB | 1         | 0.49%   |
| Vaseky V820/256G 256GB               | 1         | 0.49%   |
| USB30 Disk 250GB                     | 1         | 0.49%   |
| Unknown MMC Card  32GB               | 1         | 0.49%   |
| Unknown MMC Card  128GB              | 1         | 0.49%   |
| Toshiba THNSNJ128GCSU 128GB SSD      | 1         | 0.49%   |
| Toshiba MQ02ABD100H 1TB              | 1         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 43     | 42.68%  |
| WDC                 | 24        | 30     | 29.27%  |
| Toshiba             | 7         | 7      | 8.54%   |
| Samsung Electronics | 6         | 6      | 7.32%   |
| HGST                | 3         | 3      | 3.66%   |
| Fujitsu             | 2         | 2      | 2.44%   |
| Apple               | 2         | 2      | 2.44%   |
| Maxtor              | 1         | 1      | 1.22%   |
| Hitachi             | 1         | 2      | 1.22%   |
| Hewlett-Packard     | 1         | 1      | 1.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 15     | 20.63%  |
| Kingston            | 13        | 16     | 20.63%  |
| SanDisk             | 11        | 13     | 17.46%  |
| WDC                 | 2         | 2      | 3.17%   |
| Toshiba             | 2         | 2      | 3.17%   |
| LITEONIT            | 2         | 3      | 3.17%   |
| Intenso             | 2         | 2      | 3.17%   |
| Crucial             | 2         | 3      | 3.17%   |
| China               | 2         | 2      | 3.17%   |
| Apple               | 2         | 2      | 3.17%   |
| A-DATA Technology   | 2         | 2      | 3.17%   |
| USB30               | 1         | 2      | 1.59%   |
| Seagate             | 1         | 1      | 1.59%   |
| Patriot             | 1         | 1      | 1.59%   |
| OCZ                 | 1         | 1      | 1.59%   |
| Lexar               | 1         | 1      | 1.59%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.59%   |
| KingSpec            | 1         | 1      | 1.59%   |
| Intel               | 1         | 1      | 1.59%   |
| BUFFALO             | 1         | 1      | 1.59%   |
| Apacer              | 1         | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 70        | 97     | 43.21%  |
| SSD     | 50        | 73     | 30.86%  |
| NVMe    | 31        | 37     | 19.14%  |
| Unknown | 9         | 10     | 5.56%   |
| MMC     | 2         | 3      | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 96        | 169    | 69.57%  |
| NVMe | 31        | 37     | 22.46%  |
| SAS  | 9         | 11     | 6.52%   |
| MMC  | 2         | 3      | 1.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 68        | 92     | 53.54%  |
| 0.51-1.0   | 46        | 60     | 36.22%  |
| 1.01-2.0   | 8         | 12     | 6.3%    |
| 3.01-4.0   | 3         | 3      | 2.36%   |
| 2.01-3.0   | 1         | 2      | 0.79%   |
| 4.01-10.0  | 1         | 1      | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 37        | 31.36%  |
| 101-250        | 29        | 24.58%  |
| 501-1000       | 17        | 14.41%  |
| 51-100         | 12        | 10.17%  |
| 1001-2000      | 10        | 8.47%   |
| 1-20           | 4         | 3.39%   |
| 21-50          | 3         | 2.54%   |
| 2001-3000      | 3         | 2.54%   |
| More than 3000 | 2         | 1.69%   |
| Unknown        | 1         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 59        | 48.76%  |
| 21-50          | 25        | 20.66%  |
| 101-250        | 11        | 9.09%   |
| 51-100         | 11        | 9.09%   |
| 251-500        | 5         | 4.13%   |
| 501-1000       | 5         | 4.13%   |
| More than 3000 | 2         | 1.65%   |
| 1001-2000      | 2         | 1.65%   |
| Unknown        | 1         | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| WDC WD10EZEX-21M2NA0 1TB   | 1         | 2      | 33.33%  |
| Toshiba MQ02ABD100H 1TB    | 1         | 1      | 33.33%  |
| HGST HTS725050A7E630 500GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 100%    |

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
| Detected | 105       | 203    | 87.5%   |
| Works    | 12        | 13     | 10%     |
| Malfunc  | 3         | 4      | 2.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 82        | 55.78%  |
| AMD                              | 26        | 17.69%  |
| Samsung Electronics              | 10        | 6.8%    |
| Sandisk                          | 7         | 4.76%   |
| Phison Electronics               | 3         | 2.04%   |
| Silicon Motion                   | 2         | 1.36%   |
| Silicon Image                    | 2         | 1.36%   |
| Micron/Crucial Technology        | 2         | 1.36%   |
| KIOXIA                           | 2         | 1.36%   |
| ASMedia Technology               | 2         | 1.36%   |
| ADATA Technology                 | 2         | 1.36%   |
| VIA Technologies                 | 1         | 0.68%   |
| Toshiba America Info Systems     | 1         | 0.68%   |
| SK Hynix                         | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] | 1         | 0.68%   |
| Marvell Technology Group         | 1         | 0.68%   |
| Kingston Technology Company      | 1         | 0.68%   |
| JMicron Technology               | 1         | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 9.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 6.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 3.07%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 3.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 3.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 3.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 2.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 2.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 2.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 2.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 2.45%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 1.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 1.84%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.84%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 1.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.84%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.84%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 1.23%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 1.23%   |
| Samsung NVMe Controller                                                                 | 2         | 1.23%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 1.23%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 1.23%   |
| Intel SSD 660P Series                                                                   | 2         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.23%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.23%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.23%   |
| AMD FCH SATA Controller D                                                               | 2         | 1.23%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2         | 1.23%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.61%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 0.61%   |
| SK Hynix BC511                                                                          | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1         | 0.61%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1         | 0.61%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 1         | 0.61%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.61%   |
| Sandisk PC SN520 NVMe SSD                                                               | 1         | 0.61%   |
| Samsung Electronics SATA controller                                                     | 1         | 0.61%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.61%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1         | 0.61%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.61%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 1         | 0.61%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 0.61%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1         | 0.61%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 0.61%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 0.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 91        | 61.9%   |
| NVMe | 31        | 21.09%  |
| IDE  | 13        | 8.84%   |
| RAID | 12        | 8.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 89        | 75.42%  |
| AMD    | 29        | 24.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 2.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.69%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.69%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 1.69%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 1.69%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 1.69%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2         | 1.69%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 1.69%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 1.69%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 1.69%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.69%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.69%   |
| AMD FX-8320E Eight-Core Processor             | 2         | 1.69%   |
| Intel Xeon CPU X3220 @ 2.40GHz                | 1         | 0.85%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.85%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.85%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 1         | 0.85%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.85%   |
| Intel Pentium CPU 3550M @ 2.30GHz             | 1         | 0.85%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.85%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.85%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.85%   |
| Intel Core i7-4940MX CPU @ 3.10GHz            | 1         | 0.85%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 1         | 0.85%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.85%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.85%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.85%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.85%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.85%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 0.85%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.85%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 1         | 0.85%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 1         | 0.85%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 0.85%   |
| Intel Core i5-4570R CPU @ 2.70GHz             | 1         | 0.85%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 0.85%   |
| Intel Core i5-4430 CPU @ 3.00GHz              | 1         | 0.85%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 1         | 0.85%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.85%   |
| Intel Core i5-2500S CPU @ 2.70GHz             | 1         | 0.85%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 1         | 0.85%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 0.85%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 0.85%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 1         | 0.85%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 0.85%   |
| Intel Core i3-4360T CPU @ 3.20GHz             | 1         | 0.85%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 32        | 27.12%  |
| Intel Core i7           | 21        | 17.8%   |
| Intel Core i3           | 12        | 10.17%  |
| Other                   | 6         | 5.08%   |
| AMD Ryzen 5             | 6         | 5.08%   |
| AMD FX                  | 6         | 5.08%   |
| Intel Celeron           | 5         | 4.24%   |
| AMD Ryzen 7             | 5         | 4.24%   |
| Intel Core 2 Duo        | 4         | 3.39%   |
| AMD Ryzen 3             | 3         | 2.54%   |
| Intel Pentium Dual-Core | 2         | 1.69%   |
| Intel Pentium           | 2         | 1.69%   |
| Intel Core 2 Quad       | 2         | 1.69%   |
| AMD A6                  | 2         | 1.69%   |
| Intel Xeon              | 1         | 0.85%   |
| Intel Pentium Silver    | 1         | 0.85%   |
| Intel Pentium Dual      | 1         | 0.85%   |
| Intel Core i9           | 1         | 0.85%   |
| AMD Ryzen 9             | 1         | 0.85%   |
| AMD Phenom II X4        | 1         | 0.85%   |
| AMD E2                  | 1         | 0.85%   |
| AMD E                   | 1         | 0.85%   |
| AMD C-60                | 1         | 0.85%   |
| AMD Athlon              | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 61        | 51.69%  |
| 2      | 42        | 35.59%  |
| 8      | 6         | 5.08%   |
| 6      | 3         | 2.54%   |
| 3      | 2         | 1.69%   |
| 1      | 2         | 1.69%   |
| 12     | 1         | 0.85%   |
| 10     | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 118       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 74        | 62.71%  |
| 1      | 44        | 37.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 118       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 14        | 11.76%  |
| 0x306a9    | 10        | 8.4%    |
| 0x206a7    | 6         | 5.04%   |
| Unknown    | 6         | 5.04%   |
| 0x806ea    | 5         | 4.2%    |
| 0x40651    | 5         | 4.2%    |
| 0x06000852 | 5         | 4.2%    |
| 0x806ec    | 4         | 3.36%   |
| 0x806c1    | 4         | 3.36%   |
| 0x6fb      | 4         | 3.36%   |
| 0x506e3    | 4         | 3.36%   |
| 0x306d4    | 4         | 3.36%   |
| 0x08108109 | 4         | 3.36%   |
| 0x30678    | 3         | 2.52%   |
| 0x1067a    | 3         | 2.52%   |
| 0x08701021 | 3         | 2.52%   |
| 0x906eb    | 2         | 1.68%   |
| 0x706a1    | 2         | 1.68%   |
| 0x6fd      | 2         | 1.68%   |
| 0x40661    | 2         | 1.68%   |
| 0x20655    | 2         | 1.68%   |
| 0x0800820d | 2         | 1.68%   |
| 0x06001119 | 2         | 1.68%   |
| 0x05000119 | 2         | 1.68%   |
| 0xa0655    | 1         | 0.84%   |
| 0xa0652    | 1         | 0.84%   |
| 0x906ec    | 1         | 0.84%   |
| 0x906ea    | 1         | 0.84%   |
| 0x906c0    | 1         | 0.84%   |
| 0x806eb    | 1         | 0.84%   |
| 0x106e5    | 1         | 0.84%   |
| 0x10676    | 1         | 0.84%   |
| 0x08701013 | 1         | 0.84%   |
| 0x08608102 | 1         | 0.84%   |
| 0x08600106 | 1         | 0.84%   |
| 0x08600104 | 1         | 0.84%   |
| 0x08108102 | 1         | 0.84%   |
| 0x08101016 | 1         | 0.84%   |
| 0x08001138 | 1         | 0.84%   |
| 0x07030106 | 1         | 0.84%   |
| 0x06006705 | 1         | 0.84%   |
| 0x06003106 | 1         | 0.84%   |
| 0x010000c8 | 1         | 0.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 21        | 17.8%   |
| KabyLake      | 16        | 13.56%  |
| IvyBridge     | 10        | 8.47%   |
| Zen+          | 7         | 5.93%   |
| SandyBridge   | 7         | 5.93%   |
| Piledriver    | 7         | 5.93%   |
| Zen 2         | 6         | 5.08%   |
| Core          | 6         | 5.08%   |
| Skylake       | 5         | 4.24%   |
| TigerLake     | 4         | 3.39%   |
| Penryn        | 4         | 3.39%   |
| Broadwell     | 4         | 3.39%   |
| Silvermont    | 3         | 2.54%   |
| Zen           | 2         | 1.69%   |
| Westmere      | 2         | 1.69%   |
| Nehalem       | 2         | 1.69%   |
| Goldmont plus | 2         | 1.69%   |
| CometLake     | 2         | 1.69%   |
| Bobcat        | 2         | 1.69%   |
| Tremont       | 1         | 0.85%   |
| Steamroller   | 1         | 0.85%   |
| Puma          | 1         | 0.85%   |
| K10           | 1         | 0.85%   |
| Excavator     | 1         | 0.85%   |
| Unknown       | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 65        | 46.76%  |
| Nvidia                           | 39        | 28.06%  |
| AMD                              | 34        | 24.46%  |
| Silicon Integrated Systems [SiS] | 1         | 0.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 4.23%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 4.23%   |
| Intel UHD Graphics 620                                                      | 5         | 3.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 3.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 3.52%   |
| AMD Picasso                                                                 | 5         | 3.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 2.82%   |
| Intel HD Graphics 5500                                                      | 3         | 2.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 2.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 2.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 2.11%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3         | 2.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.41%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 1.41%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 1.41%   |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 2         | 1.41%   |
| AMD RS780L [Radeon 3000]                                                    | 2         | 1.41%   |
| AMD Renoir                                                                  | 2         | 1.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2         | 1.41%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1         | 0.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.7%    |
| Nvidia TU117M                                                               | 1         | 0.7%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 0.7%    |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.7%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.7%    |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 0.7%    |
| Nvidia GT216M [GeForce GT 240M]                                             | 1         | 0.7%    |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.7%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.7%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.7%    |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 0.7%    |
| Nvidia GM107GL [Quadro K1200]                                               | 1         | 0.7%    |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 0.7%    |
| Nvidia GK208BM [GeForce 920M]                                               | 1         | 0.7%    |
| Nvidia GK107M [GeForce GT 750M]                                             | 1         | 0.7%    |
| Nvidia GK107M [GeForce GT 640M LE]                                          | 1         | 0.7%    |
| Nvidia GK107GLM [Quadro K1100M]                                             | 1         | 0.7%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 0.7%    |
| Nvidia GK107 [GeForce GT 640]                                               | 1         | 0.7%    |
| Nvidia GK106 [GeForce GTX 660]                                              | 1         | 0.7%    |
| Nvidia GK104M [GeForce GTX 680MX]                                           | 1         | 0.7%    |
| Nvidia GK104 [GeForce GTX 680]                                              | 1         | 0.7%    |
| Nvidia GF119 [GeForce GT 610]                                               | 1         | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.7%    |
| Nvidia GF108M [GeForce GT 555M]                                             | 1         | 0.7%    |
| Nvidia GF108M [GeForce GT 435M]                                             | 1         | 0.7%    |
| Nvidia GF108 [GeForce GT 730]                                               | 1         | 0.7%    |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1         | 0.7%    |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1         | 0.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 0.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 0.7%    |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                   | 1         | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 38.66%  |
| 1 x AMD        | 28        | 23.53%  |
| 1 x Nvidia     | 26        | 21.85%  |
| Intel + Nvidia | 11        | 9.24%   |
| Intel + AMD    | 3         | 2.52%   |
| 2 x AMD        | 2         | 1.68%   |
| AMD + Nvidia   | 2         | 1.68%   |
| 1 x SiS        | 1         | 0.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 86        | 72.88%  |
| Proprietary | 30        | 25.42%  |
| Unknown     | 2         | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 45.76%  |
| 1.01-2.0   | 26        | 22.03%  |
| 0.01-0.5   | 13        | 11.02%  |
| 3.01-4.0   | 9         | 7.63%   |
| 0.51-1.0   | 7         | 5.93%   |
| 7.01-8.0   | 4         | 3.39%   |
| 5.01-6.0   | 3         | 2.54%   |
| 2.01-3.0   | 1         | 0.85%   |
| 16.01-24.0 | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 16        | 13.01%  |
| AU Optronics            | 13        | 10.57%  |
| Chimei Innolux          | 11        | 8.94%   |
| BOE                     | 9         | 7.32%   |
| LG Display              | 8         | 6.5%    |
| Acer                    | 8         | 6.5%    |
| Hewlett-Packard         | 5         | 4.07%   |
| Apple                   | 5         | 4.07%   |
| AOC                     | 5         | 4.07%   |
| Philips                 | 4         | 3.25%   |
| Goldstar                | 4         | 3.25%   |
| Vizio                   | 3         | 2.44%   |
| Sharp                   | 3         | 2.44%   |
| Lenovo                  | 3         | 2.44%   |
| Dell                    | 3         | 2.44%   |
| PANDA                   | 2         | 1.63%   |
| NEC Computers           | 2         | 1.63%   |
| InfoVision              | 2         | 1.63%   |
| Chi Mei Optoelectronics | 2         | 1.63%   |
| Ancor Communications    | 2         | 1.63%   |
| Xiaomi                  | 1         | 0.81%   |
| ViewSonic               | 1         | 0.81%   |
| Unknown                 | 1         | 0.81%   |
| Sony                    | 1         | 0.81%   |
| Sceptre Tech            | 1         | 0.81%   |
| LGD                     | 1         | 0.81%   |
| LG Electronics          | 1         | 0.81%   |
| Iiyama                  | 1         | 0.81%   |
| Gigabyte Technology     | 1         | 0.81%   |
| Gateway                 | 1         | 0.81%   |
| Fujitsu Siemens         | 1         | 0.81%   |
| BenQ                    | 1         | 0.81%   |
| AUS                     | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch        | 2         | 1.57%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 1.57%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                     | 1         | 0.79%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch              | 1         | 0.79%   |
| Vizio PC VIZCA27 1920x1080 597x336mm 27.0-inch                         | 1         | 0.79%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1         | 0.79%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                          | 1         | 0.79%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                              | 1         | 0.79%   |
| Sony TV *00 SNYA405 3840x2160 952x535mm 43.0-inch                      | 1         | 0.79%   |
| Sharp LQ134R1JX48 SHP1528 3840x2400 288x180mm 13.4-inch                | 1         | 0.79%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                | 1         | 0.79%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                | 1         | 0.79%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                 | 1         | 0.79%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch      | 1         | 0.79%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 1         | 0.79%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch      | 1         | 0.79%   |
| Samsung Electronics S27R65x SAM1046 1920x1080 600x340mm 27.2-inch      | 1         | 0.79%   |
| Samsung Electronics S27R65 SAM1045 1920x1080 598x336mm 27.0-inch       | 1         | 0.79%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch      | 1         | 0.79%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 256x144mm 11.6-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM0C3C 1920x1080 700x390mm 31.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor C27R50x 1920x1080                      | 1         | 0.79%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch     | 1         | 0.79%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 598x336mm 27.0-inch               | 1         | 0.79%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 1         | 0.79%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1         | 0.79%   |
| Philips LCD Monitor 240B 1920x1200                                     | 1         | 0.79%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 1         | 0.79%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 1         | 0.79%   |
| NEC Computers LCD Monitor E231W 3840x1080                              | 1         | 0.79%   |
| NEC Computers LCD Monitor E231W                                        | 1         | 0.79%   |
| NEC Computers EA244WMi NEC68D7 1920x1080 520x320mm 24.0-inch           | 1         | 0.79%   |
| LGD LCD Monitor 3840x1200                                              | 1         | 0.79%   |
| LG Electronics LCD Monitor EW224 1920x1080                             | 1         | 0.79%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD0468 1366x768 340x190mm 15.3-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 1         | 0.79%   |
| Lenovo LEN T23i-10 LEN61AB 1920x1080 509x286mm 23.0-inch               | 1         | 0.79%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.79%   |
| Lenovo D22-20 LEN66AD 1920x1080 477x268mm 21.5-inch                    | 1         | 0.79%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch           | 1         | 0.79%   |
| InfoVision LCD Monitor IVO048E 1366x768 256x144mm 11.6-inch            | 1         | 0.79%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                  | 1         | 0.79%   |
| Hewlett-Packard w17e HWP26E0 1440x900 408x255mm 18.9-inch              | 1         | 0.79%   |
| Hewlett-Packard LCD Monitor w1907 3120x1050                            | 1         | 0.79%   |
| Hewlett-Packard LCD Monitor E241i                                      | 1         | 0.79%   |
| Hewlett-Packard Compaq WF1907 HWP26A5 1440x900 408x255mm 18.9-inch     | 1         | 0.79%   |
| Hewlett-Packard ALL-in-One HPN4024 1920x1080 527x296mm 23.8-inch       | 1         | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 55        | 46.22%  |
| 1366x768 (WXGA)    | 27        | 22.69%  |
| 3840x2160 (4K)     | 9         | 7.56%   |
| 2560x1440 (QHD)    | 3         | 2.52%   |
| Unknown            | 3         | 2.52%   |
| 3840x2400          | 2         | 1.68%   |
| 3840x1080          | 2         | 1.68%   |
| 1920x1200 (WUXGA)  | 2         | 1.68%   |
| 1680x1050 (WSXGA+) | 2         | 1.68%   |
| 1600x900 (HD+)     | 2         | 1.68%   |
| 1280x800 (WXGA)    | 2         | 1.68%   |
| 1280x1024 (SXGA)   | 2         | 1.68%   |
| 3840x1200          | 1         | 0.84%   |
| 3440x1440          | 1         | 0.84%   |
| 3200x1800 (QHD+)   | 1         | 0.84%   |
| 3120x1050          | 1         | 0.84%   |
| 2880x1800          | 1         | 0.84%   |
| 2560x1600          | 1         | 0.84%   |
| 1600x1200          | 1         | 0.84%   |
| 1440x900 (WXGA+)   | 1         | 0.84%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 30        | 24.79%  |
| Unknown | 17        | 14.05%  |
| 13      | 14        | 11.57%  |
| 27      | 10        | 8.26%   |
| 24      | 6         | 4.96%   |
| 14      | 6         | 4.96%   |
| 31      | 5         | 4.13%   |
| 23      | 5         | 4.13%   |
| 21      | 5         | 4.13%   |
| 19      | 3         | 2.48%   |
| 18      | 3         | 2.48%   |
| 17      | 3         | 2.48%   |
| 11      | 3         | 2.48%   |
| 48      | 2         | 1.65%   |
| 25      | 2         | 1.65%   |
| 22      | 2         | 1.65%   |
| 46      | 1         | 0.83%   |
| 43      | 1         | 0.83%   |
| 41      | 1         | 0.83%   |
| 36      | 1         | 0.83%   |
| 34      | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 35.59%  |
| 501-600     | 20        | 16.95%  |
| Unknown     | 17        | 14.41%  |
| 201-300     | 12        | 10.17%  |
| 401-500     | 11        | 9.32%   |
| 601-700     | 6         | 5.08%   |
| 351-400     | 3         | 2.54%   |
| 1001-1500   | 3         | 2.54%   |
| 701-800     | 2         | 1.69%   |
| 901-1000    | 2         | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 80        | 71.43%  |
| Unknown | 17        | 15.18%  |
| 16/10   | 11        | 9.82%   |
| 5/4     | 1         | 0.89%   |
| 4/3     | 1         | 0.89%   |
| 32/9    | 1         | 0.89%   |
| 21/9    | 1         | 0.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 24.79%  |
| Unknown        | 17        | 14.05%  |
| 201-250        | 16        | 13.22%  |
| 81-90          | 12        | 9.92%   |
| 301-350        | 10        | 8.26%   |
| 71-80          | 8         | 6.61%   |
| 351-500        | 6         | 4.96%   |
| 501-1000       | 5         | 4.13%   |
| 151-200        | 4         | 3.31%   |
| 51-60          | 3         | 2.48%   |
| 251-300        | 3         | 2.48%   |
| 141-150        | 3         | 2.48%   |
| 121-130        | 2         | 1.65%   |
| More than 1000 | 1         | 0.83%   |
| 91-100         | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 35        | 29.66%  |
| 51-100        | 29        | 24.58%  |
| 121-160       | 24        | 20.34%  |
| Unknown       | 17        | 14.41%  |
| 161-240       | 6         | 5.08%   |
| More than 240 | 4         | 3.39%   |
| 1-50          | 3         | 2.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 103       | 86.55%  |
| 2     | 14        | 11.76%  |
| 0     | 2         | 1.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 72        | 38.71%  |
| Intel                            | 50        | 26.88%  |
| Qualcomm Atheros                 | 21        | 11.29%  |
| Broadcom                         | 12        | 6.45%   |
| Broadcom Limited                 | 5         | 2.69%   |
| Ralink                           | 4         | 2.15%   |
| TP-Link                          | 3         | 1.61%   |
| Marvell Technology Group         | 3         | 1.61%   |
| Samsung Electronics              | 2         | 1.08%   |
| Ralink Technology                | 2         | 1.08%   |
| DisplayLink                      | 2         | 1.08%   |
| D-Link System                    | 2         | 1.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.54%   |
| Qualcomm                         | 1         | 0.54%   |
| OnePlus                          | 1         | 0.54%   |
| NetGear                          | 1         | 0.54%   |
| Motorola PCS                     | 1         | 0.54%   |
| Google                           | 1         | 0.54%   |
| Edimax Technology                | 1         | 0.54%   |
| ASIX Electronics                 | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 25.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 3.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.42%   |
| Intel Wireless 7260                                               | 5         | 2.42%   |
| Realtek 802.11ac NIC                                              | 4         | 1.93%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.45%   |
| Intel WiFi Link 5100                                              | 3         | 1.45%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.45%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.45%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 1.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.97%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.97%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.97%   |
| Intel Wireless-AC 9260                                            | 2         | 0.97%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.97%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.97%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.97%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.97%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.97%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.48%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.48%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.48%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.48%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.48%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.48%   |
| Realtek Realtek Network controller                                | 1         | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.48%   |
| Ralink RT5592 PCIe Wireless Network Adapter                       | 1         | 0.48%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.48%   |
| Ralink RT2600 802.11 MIMO                                         | 1         | 0.48%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1         | 0.48%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]       | 1         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.48%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.48%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.48%   |
| OnePlus SM8150-MTP _SN:79FDB63C                                   | 1         | 0.48%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 38.3%   |
| Realtek Semiconductor | 17        | 18.09%  |
| Qualcomm Atheros      | 16        | 17.02%  |
| Broadcom              | 9         | 9.57%   |
| Ralink                | 4         | 4.26%   |
| TP-Link               | 3         | 3.19%   |
| Broadcom Limited      | 3         | 3.19%   |
| Ralink Technology     | 2         | 2.13%   |
| Qualcomm              | 1         | 1.06%   |
| NetGear               | 1         | 1.06%   |
| Edimax Technology     | 1         | 1.06%   |
| D-Link System         | 1         | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 5         | 5.26%   |
| Intel Wireless 7260                                                  | 5         | 5.26%   |
| Realtek 802.11ac NIC                                                 | 4         | 4.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3         | 3.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 3.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 3.16%   |
| Intel WiFi Link 5100                                                 | 3         | 3.16%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 3.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 3         | 3.16%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 2         | 2.11%   |
| Ralink MT7601U Wireless Adapter                                      | 2         | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 2.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 2.11%   |
| Intel Wireless-AC 9260                                               | 2         | 2.11%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 2.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 2.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 2.11%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 2.11%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 2.11%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 2         | 2.11%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 2         | 2.11%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 2.11%   |
| TP-Link Archer T4U ver.3                                             | 1         | 1.05%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 1         | 1.05%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.05%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                      | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 1.05%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 1.05%   |
| Realtek Realtek Network controller                                   | 1         | 1.05%   |
| Ralink RT5592 PCIe Wireless Network Adapter                          | 1         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.05%   |
| Ralink RT2600 802.11 MIMO                                            | 1         | 1.05%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 1         | 1.05%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]          | 1         | 1.05%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 1         | 1.05%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]          | 1         | 1.05%   |
| Intel Wireless 8260                                                  | 1         | 1.05%   |
| Intel Wireless 7265                                                  | 1         | 1.05%   |
| Intel Wireless 3160                                                  | 1         | 1.05%   |
| Intel Wi-Fi 6 AX201 160MHz                                           | 1         | 1.05%   |
| Intel Centrino Wireless-N 130                                        | 1         | 1.05%   |
| Intel Centrino Wireless-N 105                                        | 1         | 1.05%   |
| Intel Centrino Ultimate-N 6300                                       | 1         | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.05%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 1         | 1.05%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870] | 1         | 1.05%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1         | 1.05%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                               | 1         | 1.05%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 1         | 1.05%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1         | 1.05%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1         | 1.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 1         | 1.05%   |
| Broadcom BCM4321 802.11a/b/g/n                                       | 1         | 1.05%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 1         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 64        | 57.66%  |
| Intel                            | 21        | 18.92%  |
| Qualcomm Atheros                 | 6         | 5.41%   |
| Broadcom                         | 5         | 4.5%    |
| Marvell Technology Group         | 3         | 2.7%    |
| Samsung Electronics              | 2         | 1.8%    |
| DisplayLink                      | 2         | 1.8%    |
| Broadcom Limited                 | 2         | 1.8%    |
| Silicon Integrated Systems [SiS] | 1         | 0.9%    |
| OnePlus                          | 1         | 0.9%    |
| Motorola PCS                     | 1         | 0.9%    |
| Google                           | 1         | 0.9%    |
| D-Link System                    | 1         | 0.9%    |
| ASIX Electronics                 | 1         | 0.9%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 46.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 6.25%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.57%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 2.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 2.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.79%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.79%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.89%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.89%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.89%   |
| OnePlus SM8150-MTP _SN:79FDB63C                                   | 1         | 0.89%   |
| Motorola PCS moto g(30)                                           | 1         | 0.89%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.89%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.89%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.89%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.89%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.89%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.89%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.89%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.89%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 0.89%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.89%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.89%   |
| DisplayLink USB 3.0 Dual Video Dock                               | 1         | 0.89%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.89%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 0.89%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.89%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 0.89%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 106       | 54.64%  |
| WiFi     | 88        | 45.36%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 101       | 57.06%  |
| WiFi     | 76        | 42.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 62        | 52.54%  |
| 1     | 55        | 46.61%  |
| 3     | 1         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 78        | 65.55%  |
| Yes  | 41        | 34.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 38.36%  |
| Realtek Semiconductor           | 8         | 10.96%  |
| Qualcomm Atheros Communications | 8         | 10.96%  |
| Apple                           | 6         | 8.22%   |
| Lite-On Technology              | 4         | 5.48%   |
| IMC Networks                    | 4         | 5.48%   |
| Broadcom                        | 4         | 5.48%   |
| Foxconn / Hon Hai               | 3         | 4.11%   |
| Cambridge Silicon Radio         | 3         | 4.11%   |
| Ralink                          | 1         | 1.37%   |
| Foxconn International           | 1         | 1.37%   |
| Dell                            | 1         | 1.37%   |
| ASUSTek Computer                | 1         | 1.37%   |
| Alps Electric                   | 1         | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 13.7%   |
| Intel Bluetooth Device                              | 9         | 12.33%  |
| Realtek Bluetooth Radio                             | 6         | 8.22%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 5.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 4.11%   |
| Apple Bluetooth USB Host Controller                 | 3         | 4.11%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.74%   |
| Lite-On Bluetooth Device                            | 2         | 2.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.74%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.74%   |
| Intel AX200 Bluetooth                               | 2         | 2.74%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.74%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.37%   |
| Qualcomm Atheros Bluetooth                          | 1         | 1.37%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.37%   |
| Lite-On BCM43142A0                                  | 1         | 1.37%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.37%   |
| IMC Networks Bluetooth Device                       | 1         | 1.37%   |
| IMC Networks Bluetooth                              | 1         | 1.37%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.37%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.37%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.37%   |
| Dell BT Mini-Receiver                               | 1         | 1.37%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module            | 1         | 1.37%   |
| Broadcom Bluetooth                                  | 1         | 1.37%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.37%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.37%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.37%   |
| Apple Bluetooth Host Controller                     | 1         | 1.37%   |
| Apple Bluetooth HCI                                 | 1         | 1.37%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 87        | 51.79%  |
| AMD                              | 37        | 22.02%  |
| Nvidia                           | 32        | 19.05%  |
| Texas Instruments                | 2         | 1.19%   |
| Creative Labs                    | 2         | 1.19%   |
| XMOS                             | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |
| Razer USA                        | 1         | 0.6%    |
| Numark                           | 1         | 0.6%    |
| Logitech                         | 1         | 0.6%    |
| Klipsch Audio                    | 1         | 0.6%    |
| JMTek                            | 1         | 0.6%    |
| GN Netcom                        | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 5.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 4.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 4.35%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 9         | 4.35%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 3.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 3.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 2.42%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.42%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.42%   |
| AMD FCH Azalia Controller                                                  | 5         | 2.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.93%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.45%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.45%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.45%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 1.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 1.45%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.97%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.97%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 0.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.97%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.97%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 2         | 0.97%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 0.97%   |
| XMOS Gustard USB Audio 2.0                                                 | 1         | 0.48%   |
| Texas Instruments PCM2901 Audio Codec                                      | 1         | 0.48%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.48%   |
| Razer USA Razer USB Sound Card                                             | 1         | 0.48%   |
| Razer USA Razer Seiren Mini                                                | 1         | 0.48%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.48%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.48%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.48%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.48%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.48%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia Audio device                                                        | 1         | 0.48%   |
| Numark MixTrack Pro                                                        | 1         | 0.48%   |
| Logitech H600 [Wireless Headset]                                           | 1         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 30%     |
| Micron Technology   | 4         | 20%     |
| Unknown             | 2         | 10%     |
| Crucial             | 2         | 10%     |
| Team                | 1         | 5%      |
| SK Hynix            | 1         | 5%      |
| Ramaxel Technology  | 1         | 5%      |
| Kingston            | 1         | 5%      |
| Corsair             | 1         | 5%      |
| A-DATA Technology   | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s           | 1         | 4.17%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                         | 1         | 4.17%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1         | 4.17%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s                | 1         | 4.17%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s                | 1         | 4.17%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 4.17%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s     | 1         | 4.17%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s          | 1         | 4.17%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s          | 1         | 4.17%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s          | 1         | 4.17%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 1         | 4.17%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 1         | 4.17%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 1         | 4.17%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s          | 1         | 4.17%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 4.17%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 4.17%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s          | 1         | 4.17%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s        | 1         | 4.17%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s         | 1         | 4.17%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 4.17%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s            | 1         | 4.17%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s        | 1         | 4.17%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s            | 1         | 4.17%   |
| A-DATA RAM AE4S240038G17-BHYA 8192MB SODIMM DDR4 2400MT/s         | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 10        | 52.63%  |
| DDR3    | 5         | 26.32%  |
| SDRAM   | 1         | 5.26%   |
| LPDDR4  | 1         | 5.26%   |
| LPDDR3  | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 57.89%  |
| Row Of Chips | 4         | 21.05%  |
| DIMM         | 4         | 21.05%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 9         | 45%     |
| 8192  | 7         | 35%     |
| 32768 | 2         | 10%     |
| 2048  | 2         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 6         | 30%     |
| 1600  | 5         | 25%     |
| 3200  | 3         | 15%     |
| 2400  | 2         | 10%     |
| 4267  | 1         | 5%      |
| 4199  | 1         | 5%      |
| 1867  | 1         | 5%      |
| 1333  | 1         | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 66.67%  |
| Samsung Electronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SCX-3400 Series         | 1         | 33.33%  |
| HP OfficeJet 4650 series        | 1         | 33.33%  |
| HP LaserJet Professional P1102w | 1         | 33.33%  |

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
| IMC Networks                           | 8         | 12.12%  |
| Chicony Electronics                    | 8         | 12.12%  |
| Acer                                   | 7         | 10.61%  |
| Realtek Semiconductor                  | 6         | 9.09%   |
| Microdia                               | 6         | 9.09%   |
| Sunplus Innovation Technology          | 5         | 7.58%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 7.58%   |
| Apple                                  | 4         | 6.06%   |
| Quanta                                 | 3         | 4.55%   |
| Syntek                                 | 2         | 3.03%   |
| Suyin                                  | 2         | 3.03%   |
| Lite-On Technology                     | 2         | 3.03%   |
| Samsung Electronics                    | 1         | 1.52%   |
| Ricoh                                  | 1         | 1.52%   |
| Razer USA                              | 1         | 1.52%   |
| Microsoft                              | 1         | 1.52%   |
| Logitech                               | 1         | 1.52%   |
| Jieli Technology                       | 1         | 1.52%   |
| Generalplus Technology                 | 1         | 1.52%   |
| ALi                                    | 1         | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Apple FaceTime HD Camera (Built-in)                  | 4         | 6.06%   |
| Realtek Integrated_Webcam_HD                         | 3         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 3         | 4.55%   |
| IMC Networks Integrated Camera                       | 3         | 4.55%   |
| Acer Integrated Camera                               | 3         | 4.55%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 3.03%   |
| Quanta HD User Facing                                | 2         | 3.03%   |
| Microdia Integrated_Webcam_HD                        | 2         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam        | 2         | 3.03%   |
| Acer Lenovo EasyCamera                               | 2         | 3.03%   |
| Syntek USB Camera Device                             | 1         | 1.52%   |
| Syntek Integrated Camera                             | 1         | 1.52%   |
| Suyin HD Video WebCam                                | 1         | 1.52%   |
| Suyin Acer/HP Integrated Webcam [CN0314]             | 1         | 1.52%   |
| Sunplus Integrated Webcam                            | 1         | 1.52%   |
| Sunplus HD Webcam                                    | 1         | 1.52%   |
| Sunplus HD User Facing                               | 1         | 1.52%   |
| Samsung Galaxy series, misc. (MTP mode)              | 1         | 1.52%   |
| Ricoh Visual Communication Camera VGP-VCC9 [R5U870]  | 1         | 1.52%   |
| Realtek USB Camera                                   | 1         | 1.52%   |
| Realtek Lenovo EasyCamera                            | 1         | 1.52%   |
| Realtek Integrated Webcam                            | 1         | 1.52%   |
| Razer USA Razer Kiyo                                 | 1         | 1.52%   |
| Quanta Laptop_Integrated_Webcam_2HDM                 | 1         | 1.52%   |
| Microsoft Microsoft?� LifeCam Cinema                 | 1         | 1.52%   |
| Microdia USB Camera                                  | 1         | 1.52%   |
| Microdia Lenovo EasyCamera                           | 1         | 1.52%   |
| Microdia Integrated Webcam                           | 1         | 1.52%   |
| Microdia Integrated HD Webcam                        | 1         | 1.52%   |
| Logitech HD Pro Webcam C920                          | 1         | 1.52%   |
| Lite-On HP HD Camera                                 | 1         | 1.52%   |
| Lite-On HP 2.0MP High Definition Webcam              | 1         | 1.52%   |
| Jieli USB PHY 2.0                                    | 1         | 1.52%   |
| IMC Networks Lenovo EasyCamera                       | 1         | 1.52%   |
| IMC Networks EasyCamera                              | 1         | 1.52%   |
| Generalplus GENERAL WEBCAM                           | 1         | 1.52%   |
| Chicony VGA Webcam                                   | 1         | 1.52%   |
| Chicony LG HD WebCam                                 | 1         | 1.52%   |
| Chicony Integrated Camera                            | 1         | 1.52%   |
| Chicony HP Wide Vision HD Camera                     | 1         | 1.52%   |
| Chicony HP TrueVision HD                             | 1         | 1.52%   |
| Chicony HD WebCam                                    | 1         | 1.52%   |
| Chicony FJ Camera                                    | 1         | 1.52%   |
| Chicony EasyCamera                                   | 1         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) USB HD webcam | 1         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 1         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 1         | 1.52%   |
| ALi Gateway Webcam                                   | 1         | 1.52%   |
| Acer SunplusIT INC. Integrated Camera                | 1         | 1.52%   |
| Acer Lenovo EasyCamera integrated webcam             | 1         | 1.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 5         | 38.46%  |
| Validity Sensors           | 4         | 30.77%  |
| LighTuning Technology      | 2         | 15.38%  |
| Upek                       | 1         | 7.69%   |
| Focal-systems.Corp         | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 23.08%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 7.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 7.69%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 7.69%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 7.69%   |
| LighTuning Fingerprint Reader                                              | 1         | 7.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 7.69%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 89        | 75.42%  |
| 1     | 23        | 19.49%  |
| 2     | 6         | 5.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 36.11%  |
| Net/wireless          | 10        | 27.78%  |
| Graphics card         | 6         | 16.67%  |
| Multimedia controller | 2         | 5.56%   |
| Chipcard              | 2         | 5.56%   |
| Net/ethernet          | 1         | 2.78%   |
| Dvb card              | 1         | 2.78%   |
| Bluetooth             | 1         | 2.78%   |

