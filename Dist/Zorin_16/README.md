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
| Toshiba       | Satellite C850D-11C         | Notebook    | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | 1497                        | Desktop     | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [3c88709f8a](https://linux-hardware.org/?probe=3c88709f8a) | Sep 01, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | Notebook    | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| Insyde        | i101c                       | Notebook    | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [baa289fe51](https://linux-hardware.org/?probe=baa289fe51) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [cc326a093e](https://linux-hardware.org/?probe=cc326a093e) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [4c711d446d](https://linux-hardware.org/?probe=4c711d446d) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [efb9bccc60](https://linux-hardware.org/?probe=efb9bccc60) | Aug 31, 2021 |
| HP            | Pavilion 15                 | Notebook    | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | Notebook    | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [000d760a55](https://linux-hardware.org/?probe=000d760a55) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [3b05a7b317](https://linux-hardware.org/?probe=3b05a7b317) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | Notebook    | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | Notebook    | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | Notebook    | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| MSI           | Z87-G43                     | Desktop     | [a219ff197d](https://linux-hardware.org/?probe=a219ff197d) | Aug 29, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [01a43874df](https://linux-hardware.org/?probe=01a43874df) | Aug 28, 2021 |
| Acer          | Aspire 5100                 | Notebook    | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | Notebook    | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | Notebook    | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [5cd3f43e28](https://linux-hardware.org/?probe=5cd3f43e28) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-27-generic | 84        | 56%     |
| 5.8.0-53-generic  | 13        | 8.67%   |
| 5.8.0-50-generic  | 12        | 8%      |
| 5.11.0-25-generic | 12        | 8%      |
| 5.8.0-55-generic  | 10        | 6.67%   |
| 5.8.0-59-generic  | 8         | 5.33%   |
| 5.8.0-63-generic  | 4         | 2.67%   |
| 5.8.0-49-generic  | 4         | 2.67%   |
| 5.8.0-45-generic  | 1         | 0.67%   |
| 5.4.0-42-generic  | 1         | 0.67%   |
| 5.10.0-1044-oem   | 1         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 96        | 64.43%  |
| 5.8.0   | 51        | 34.23%  |
| 5.4.0   | 1         | 0.67%   |
| 5.10.0  | 1         | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 96        | 64.43%  |
| 5.8     | 51        | 34.23%  |
| 5.4     | 1         | 0.67%   |
| 5.10    | 1         | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 147       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME    | 145       | 97.97%  |
| XFCE     | 1         | 0.68%   |
| Cinnamon | 1         | 0.68%   |
| Unknown  | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 144       | 97.96%  |
| Wayland | 2         | 1.36%   |
| Unknown | 1         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 129       | 87.76%  |
| GDM     | 17        | 11.56%  |
| TDM     | 1         | 0.68%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 46        | 31.29%  |
| de_DE | 20        | 13.61%  |
| pt_BR | 14        | 9.52%   |
| en_GB | 13        | 8.84%   |
| es_ES | 8         | 5.44%   |
| en_IN | 6         | 4.08%   |
| pl_PL | 5         | 3.4%    |
| es_MX | 5         | 3.4%    |
| nl_NL | 3         | 2.04%   |
| hu_HU | 3         | 2.04%   |
| es_CL | 3         | 2.04%   |
| en_CA | 3         | 2.04%   |
| it_IT | 2         | 1.36%   |
| fr_FR | 2         | 1.36%   |
| es_PE | 2         | 1.36%   |
| en_ZA | 2         | 1.36%   |
| zh_TW | 1         | 0.68%   |
| ru_UA | 1         | 0.68%   |
| nl_BE | 1         | 0.68%   |
| ja_JP | 1         | 0.68%   |
| es_CO | 1         | 0.68%   |
| en_SG | 1         | 0.68%   |
| en_PH | 1         | 0.68%   |
| en_NZ | 1         | 0.68%   |
| cs_CZ | 1         | 0.68%   |
| bg_BG | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 97        | 65.54%  |
| BIOS | 51        | 34.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 140       | 95.24%  |
| Overlay | 4         | 2.72%   |
| Zfs     | 1         | 0.68%   |
| Ext3    | 1         | 0.68%   |
| Btrfs   | 1         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 129       | 87.76%  |
| GPT     | 17        | 11.56%  |
| MBR     | 1         | 0.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 144       | 97.3%   |
| Yes       | 4         | 2.7%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 127       | 86.39%  |
| Yes       | 20        | 13.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 28        | 19.05%  |
| Lenovo              | 24        | 16.33%  |
| Hewlett-Packard     | 19        | 12.93%  |
| Dell                | 18        | 12.24%  |
| Acer                | 13        | 8.84%   |
| Gigabyte Technology | 9         | 6.12%   |
| Apple               | 7         | 4.76%   |
| MSI                 | 6         | 4.08%   |
| Intel               | 4         | 2.72%   |
| LG Electronics      | 3         | 2.04%   |
| Toshiba             | 2         | 1.36%   |
| Fujitsu             | 2         | 1.36%   |
| ASRock              | 2         | 1.36%   |
| TianBei             | 1         | 0.68%   |
| Sony                | 1         | 0.68%   |
| Razer               | 1         | 0.68%   |
| Quanta              | 1         | 0.68%   |
| Positivo            | 1         | 0.68%   |
| Pegatron            | 1         | 0.68%   |
| Packard Bell        | 1         | 0.68%   |
| Insyde              | 1         | 0.68%   |
| Biostar             | 1         | 0.68%   |
| Unknown             | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ASUS All Series                         | 3         | 2.04%   |
| Dell OptiPlex 990                       | 2         | 1.36%   |
| Dell Inspiron 5566                      | 2         | 1.36%   |
| ASUS M5A78L-M/USB3                      | 2         | 1.36%   |
| Unknown                                 | 2         | 1.36%   |
| Toshiba Satellite S75Dt-A               | 1         | 0.68%   |
| Toshiba Satellite C850D-11C             | 1         | 0.68%   |
| TianBei TB-H7                           | 1         | 0.68%   |
| Sony VGN-SR5                            | 1         | 0.68%   |
| Razer Book 13 - RZ09-0357               | 1         | 0.68%   |
| Quanta CA27                             | 1         | 0.68%   |
| Positivo POS-PIH81DI                    | 1         | 0.68%   |
| Pegatron NE502AV-ABA a6750t             | 1         | 0.68%   |
| Packard Bell DOT S                      | 1         | 0.68%   |
| MSI Pro 3515 Series                     | 1         | 0.68%   |
| MSI MS-7C37                             | 1         | 0.68%   |
| MSI MS-7B84                             | 1         | 0.68%   |
| MSI MS-7A71                             | 1         | 0.68%   |
| MSI MS-7914                             | 1         | 0.68%   |
| MSI MS-7816                             | 1         | 0.68%   |
| LG S460-G.BG31P1                        | 1         | 0.68%   |
| LG A410-K.BE47P1                        | 1         | 0.68%   |
| LG 17U70N-R.AAS7U1                      | 1         | 0.68%   |
| Lenovo Yoga C740-15IML 81TD             | 1         | 0.68%   |
| Lenovo Yoga 730-13IWL 81JR              | 1         | 0.68%   |
| Lenovo Yoga 330-11IGM 81A6              | 1         | 0.68%   |
| Lenovo Yoga 3 Pro-1370 80HE             | 1         | 0.68%   |
| Lenovo ThinkPad Yoga 11e 20DAS0SF00     | 1         | 0.68%   |
| Lenovo ThinkPad X131e 3371AL2           | 1         | 0.68%   |
| Lenovo ThinkPad T520 4242W4F            | 1         | 0.68%   |
| Lenovo ThinkPad T440p 20AWS1CH00        | 1         | 0.68%   |
| Lenovo ThinkPad E15 Gen 2 20TD000HZA    | 1         | 0.68%   |
| Lenovo ThinkCentre M83 MT-M 10AJ-0003MB | 1         | 0.68%   |
| Lenovo ThinkCentre M78 10BTA00ELM       | 1         | 0.68%   |
| Lenovo SHARKBAY SDK0E50510 WIN          | 1         | 0.68%   |
| Lenovo IdeaPad Z510 20287               | 1         | 0.68%   |
| Lenovo IdeaPad Y570 0862                | 1         | 0.68%   |
| Lenovo IdeaPad S540-14API 81NH          | 1         | 0.68%   |
| Lenovo IdeaPad 5 15ALC05 82LN           | 1         | 0.68%   |
| Lenovo IdeaPad 330-15IKB 81DE           | 1         | 0.68%   |
| Lenovo IdeaPad 3 14ADA05 81W0           | 1         | 0.68%   |
| Lenovo IdeaPad 100-15IBD 80QQ           | 1         | 0.68%   |
| Lenovo IdeaCentre 510S-08IKL 90GB004RUS | 1         | 0.68%   |
| Lenovo G50-70 20351                     | 1         | 0.68%   |
| Lenovo G50-30 80G0                      | 1         | 0.68%   |
| Lenovo Board                            | 1         | 0.68%   |
| Lenovo B50-70 80EU                      | 1         | 0.68%   |
| Intel NUC7PJYH                          | 1         | 0.68%   |
| Intel NUC11PAHi7                        | 1         | 0.68%   |
| Intel DQ77MK-R01                        | 1         | 0.68%   |
| Intel DB75EN AAG39650-303               | 1         | 0.68%   |
| Insyde i101c                            | 1         | 0.68%   |
| HP Z240 SFF Workstation                 | 1         | 0.68%   |
| HP Z1 Entry Tower G5                    | 1         | 0.68%   |
| HP ProBook 650 G2                       | 1         | 0.68%   |
| HP ProBook 450 G2                       | 1         | 0.68%   |
| HP ProBook 430 G6                       | 1         | 0.68%   |
| HP Pavilion All-in-One 24-xa0xxx        | 1         | 0.68%   |
| HP Pavilion 15                          | 1         | 0.68%   |
| HP Notebook                             | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 9         | 6.12%   |
| Dell Inspiron         | 8         | 5.44%   |
| Lenovo IdeaPad        | 7         | 4.76%   |
| Lenovo ThinkPad       | 5         | 3.4%    |
| Lenovo Yoga           | 4         | 2.72%   |
| HP ENVY               | 4         | 2.72%   |
| Dell XPS              | 4         | 2.72%   |
| HP ProBook            | 3         | 2.04%   |
| ASUS PRIME            | 3         | 2.04%   |
| ASUS All              | 3         | 2.04%   |
| Toshiba Satellite     | 2         | 1.36%   |
| Lenovo ThinkCentre    | 2         | 1.36%   |
| HP Pavilion           | 2         | 1.36%   |
| HP Compaq             | 2         | 1.36%   |
| Gigabyte B550M        | 2         | 1.36%   |
| Dell OptiPlex         | 2         | 1.36%   |
| ASUS TUF              | 2         | 1.36%   |
| ASUS P8Z77-V          | 2         | 1.36%   |
| ASUS P8H61-M          | 2         | 1.36%   |
| ASUS M5A97            | 2         | 1.36%   |
| ASUS M5A78L-M         | 2         | 1.36%   |
| Apple MacBookPro11    | 2         | 1.36%   |
| Acer Swift            | 2         | 1.36%   |
| Unknown               | 2         | 1.36%   |
| TianBei TB-H7         | 1         | 0.68%   |
| Sony VGN-SR5          | 1         | 0.68%   |
| Razer Book            | 1         | 0.68%   |
| Quanta CA27           | 1         | 0.68%   |
| Positivo POS-PIH81DI  | 1         | 0.68%   |
| Pegatron NE502AV-ABA  | 1         | 0.68%   |
| Packard Bell DOT      | 1         | 0.68%   |
| MSI Pro               | 1         | 0.68%   |
| MSI MS-7C37           | 1         | 0.68%   |
| MSI MS-7B84           | 1         | 0.68%   |
| MSI MS-7A71           | 1         | 0.68%   |
| MSI MS-7914           | 1         | 0.68%   |
| MSI MS-7816           | 1         | 0.68%   |
| LG S460-G.BG31P1      | 1         | 0.68%   |
| LG A410-K.BE47P1      | 1         | 0.68%   |
| LG 17U70N-R.AAS7U1    | 1         | 0.68%   |
| Lenovo SHARKBAY       | 1         | 0.68%   |
| Lenovo IdeaCentre     | 1         | 0.68%   |
| Lenovo G50-70         | 1         | 0.68%   |
| Lenovo G50-30         | 1         | 0.68%   |
| Lenovo Board          | 1         | 0.68%   |
| Lenovo B50-70         | 1         | 0.68%   |
| Intel NUC7PJYH        | 1         | 0.68%   |
| Intel NUC11PAHi7      | 1         | 0.68%   |
| Intel DQ77MK-R01      | 1         | 0.68%   |
| Intel DB75EN          | 1         | 0.68%   |
| Insyde i101c          | 1         | 0.68%   |
| HP Z240               | 1         | 0.68%   |
| HP Z1                 | 1         | 0.68%   |
| HP Notebook           | 1         | 0.68%   |
| HP EliteBook          | 1         | 0.68%   |
| HP 870-158ng          | 1         | 0.68%   |
| HP 290                | 1         | 0.68%   |
| HP 15                 | 1         | 0.68%   |
| Gigabyte Komputer     | 1         | 0.68%   |
| Gigabyte H61M-USB3-B3 | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 25        | 17.01%  |
| 2020 | 23        | 15.65%  |
| 2019 | 16        | 10.88%  |
| 2014 | 16        | 10.88%  |
| 2018 | 13        | 8.84%   |
| 2012 | 11        | 7.48%   |
| 2015 | 9         | 6.12%   |
| 2013 | 7         | 4.76%   |
| 2011 | 7         | 4.76%   |
| 2016 | 5         | 3.4%    |
| 2017 | 4         | 2.72%   |
| 2008 | 4         | 2.72%   |
| 2009 | 3         | 2.04%   |
| 2010 | 2         | 1.36%   |
| 2007 | 1         | 0.68%   |
| 2006 | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 76        | 51.7%   |
| Desktop     | 59        | 40.14%  |
| All in one  | 6         | 4.08%   |
| Convertible | 4         | 2.72%   |
| Mini pc     | 2         | 1.36%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 127       | 86.39%  |
| Enabled  | 20        | 13.61%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 147       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 37        | 24.83%  |
| 8.01-16.0   | 36        | 24.16%  |
| 16.01-24.0  | 29        | 19.46%  |
| 3.01-4.0    | 27        | 18.12%  |
| 32.01-64.0  | 13        | 8.72%   |
| 1.01-2.0    | 5         | 3.36%   |
| 64.01-256.0 | 2         | 1.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 73        | 48.34%  |
| 2.01-3.0 | 48        | 31.79%  |
| 3.01-4.0 | 16        | 10.6%   |
| 4.01-8.0 | 11        | 7.28%   |
| 0.51-1.0 | 3         | 1.99%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 79        | 53.74%  |
| 2      | 40        | 27.21%  |
| 3      | 12        | 8.16%   |
| 4      | 9         | 6.12%   |
| 5      | 3         | 2.04%   |
| 8      | 2         | 1.36%   |
| 6      | 1         | 0.68%   |
| 0      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 52.03%  |
| Yes       | 71        | 47.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 89.86%  |
| No        | 15        | 10.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 76.19%  |
| No        | 35        | 23.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 60.54%  |
| No        | 58        | 39.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 29        | 19.73%  |
| Germany      | 23        | 15.65%  |
| Brazil       | 17        | 11.56%  |
| UK           | 11        | 7.48%   |
| Spain        | 8         | 5.44%   |
| India        | 7         | 4.76%   |
| Mexico       | 6         | 4.08%   |
| Hungary      | 5         | 3.4%    |
| Poland       | 4         | 2.72%   |
| Netherlands  | 3         | 2.04%   |
| Chile        | 3         | 2.04%   |
| Canada       | 3         | 2.04%   |
| Taiwan       | 2         | 1.36%   |
| South Africa | 2         | 1.36%   |
| Italy        | 2         | 1.36%   |
| France       | 2         | 1.36%   |
| Colombia     | 2         | 1.36%   |
| Australia    | 2         | 1.36%   |
| Vietnam      | 1         | 0.68%   |
| Ukraine      | 1         | 0.68%   |
| Switzerland  | 1         | 0.68%   |
| Romania      | 1         | 0.68%   |
| Philippines  | 1         | 0.68%   |
| Peru         | 1         | 0.68%   |
| New Zealand  | 1         | 0.68%   |
| Malaysia     | 1         | 0.68%   |
| Madagascar   | 1         | 0.68%   |
| Kenya        | 1         | 0.68%   |
| Japan        | 1         | 0.68%   |
| Denmark      | 1         | 0.68%   |
| Czechia      | 1         | 0.68%   |
| Bulgaria     | 1         | 0.68%   |
| Belgium      | 1         | 0.68%   |
| Austria      | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Vancouver                | 2         | 1.35%   |
| S??o Lu?­s               | 2         | 1.35%   |
| Rome                     | 2         | 1.35%   |
| Rio de Janeiro           | 2         | 1.35%   |
| Madrid                   | 2         | 1.35%   |
| Hyderabad                | 2         | 1.35%   |
| Dortmund                 | 2         | 1.35%   |
| Contagem                 | 2         | 1.35%   |
| Zurich                   | 1         | 0.68%   |
| Zabrze                   | 1         | 0.68%   |
| Yokohama                 | 1         | 0.68%   |
| Xalapa                   | 1         | 0.68%   |
| Wylie                    | 1         | 0.68%   |
| Vienna                   | 1         | 0.68%   |
| Vespasiano               | 1         | 0.68%   |
| Veracruz                 | 1         | 0.68%   |
| Trujillo                 | 1         | 0.68%   |
| Taboao da Serra          | 1         | 0.68%   |
| SÃ£o Bernardo do Campo   | 1         | 0.68%   |
| Szombathely              | 1         | 0.68%   |
| Szigetvar                | 1         | 0.68%   |
| Szczecin                 | 1         | 0.68%   |
| Sutton Coldfield         | 1         | 0.68%   |
| Stadskanaal              | 1         | 0.68%   |
| St. Cloud                | 1         | 0.68%   |
| Spremberg                | 1         | 0.68%   |
| Sheffield                | 1         | 0.68%   |
| Seville                  | 1         | 0.68%   |
| S??o Jo??o del Rei       | 1         | 0.68%   |
| Santiago                 | 1         | 0.68%   |
| Santa Cruz do Rio Pardo  | 1         | 0.68%   |
| Santa Cruz de Tenerife   | 1         | 0.68%   |
| Sant Carles de la Rapita | 1         | 0.68%   |
| San Francisco            | 1         | 0.68%   |
| Sainte-Marie             | 1         | 0.68%   |
| Sacramento               | 1         | 0.68%   |
| R??sselsheim am Main     | 1         | 0.68%   |
| Rancagua                 | 1         | 0.68%   |
| Quezon City              | 1         | 0.68%   |
| Pretoria                 | 1         | 0.68%   |
| Porto Seguro             | 1         | 0.68%   |
| P?™?­bram                | 1         | 0.68%   |
| Pascoag                  | 1         | 0.68%   |
| Paris                    | 1         | 0.68%   |
| Palm Coast               | 1         | 0.68%   |
| Oscoda                   | 1         | 0.68%   |
| Ohmbach                  | 1         | 0.68%   |
| Oak Creek                | 1         | 0.68%   |
| Nyiregyhaza              | 1         | 0.68%   |
| Nottingham               | 1         | 0.68%   |
| Noblesville              | 1         | 0.68%   |
| Niter??i                 | 1         | 0.68%   |
| New York                 | 1         | 0.68%   |
| New Taipei               | 1         | 0.68%   |
| Naumburg                 | 1         | 0.68%   |
| Nairobi                  | 1         | 0.68%   |
| MÃ©rida                  | 1         | 0.68%   |
| Mumbai                   | 1         | 0.68%   |
| Morro do Chapeu          | 1         | 0.68%   |
| Montreal                 | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 44        | 54     | 19.05%  |
| Samsung Electronics       | 34        | 43     | 14.72%  |
| WDC                       | 28        | 37     | 12.12%  |
| SanDisk                   | 20        | 24     | 8.66%   |
| Kingston                  | 16        | 19     | 6.93%   |
| Toshiba                   | 15        | 15     | 6.49%   |
| Unknown                   | 7         | 9      | 3.03%   |
| Hitachi                   | 6         | 8      | 2.6%    |
| Crucial                   | 6         | 8      | 2.6%    |
| Phison                    | 5         | 6      | 2.16%   |
| Apple                     | 5         | 5      | 2.16%   |
| HGST                      | 4         | 4      | 1.73%   |
| China                     | 4         | 4      | 1.73%   |
| A-DATA Technology         | 4         | 4      | 1.73%   |
| Intel                     | 3         | 3      | 1.3%    |
| Silicon Motion            | 2         | 4      | 0.87%   |
| Micron/Crucial Technology | 2         | 2      | 0.87%   |
| Micron Technology         | 2         | 2      | 0.87%   |
| LITEONIT                  | 2         | 3      | 0.87%   |
| Intenso                   | 2         | 2      | 0.87%   |
| Fujitsu                   | 2         | 2      | 0.87%   |
| XPG                       | 1         | 1      | 0.43%   |
| Vaseky                    | 1         | 1      | 0.43%   |
| USB30                     | 1         | 2      | 0.43%   |
| SPCC                      | 1         | 1      | 0.43%   |
| SK Hynix                  | 1         | 1      | 0.43%   |
| PNY                       | 1         | 1      | 0.43%   |
| Patriot                   | 1         | 1      | 0.43%   |
| OCZ                       | 1         | 1      | 0.43%   |
| Maxtor                    | 1         | 1      | 0.43%   |
| Lexar                     | 1         | 1      | 0.43%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.43%   |
| KIOXIA                    | 1         | 1      | 0.43%   |
| KingSpec                  | 1         | 1      | 0.43%   |
| KingFast                  | 1         | 1      | 0.43%   |
| JMicron                   | 1         | 1      | 0.43%   |
| Hewlett-Packard           | 1         | 1      | 0.43%   |
| BUFFALO                   | 1         | 1      | 0.43%   |
| Apacer                    | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 5         | 1.94%   |
| Unknown SD/MMC/MS PRO 128GB         | 4         | 1.55%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 1.55%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3         | 1.16%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 1.16%   |
| Seagate ST2000DM001-9YN164 2TB      | 3         | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 1.16%   |
| SanDisk SSD PLUS 1000GB             | 3         | 1.16%   |
| Samsung SSD 860 EVO 500GB           | 3         | 1.16%   |
| Samsung NVMe SSD Drive 500GB        | 3         | 1.16%   |
| Phison NVMe SSD Drive 1TB           | 3         | 1.16%   |
| Kingston SV300S37A120G 120GB SSD    | 3         | 1.16%   |
| Kingston SA400S37240G 240GB SSD     | 3         | 1.16%   |
| Kingston SA400S37120G 120GB SSD     | 3         | 1.16%   |
| WDC WD10EZEX-60M2NA0 1TB            | 2         | 0.78%   |
| Toshiba MQ02ABD100H 1TB             | 2         | 0.78%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.78%   |
| Toshiba MK3265GSX 320GB             | 2         | 0.78%   |
| Toshiba HDWD110 1TB                 | 2         | 0.78%   |
| Silicon Motion NVMe SSD Drive 128GB | 2         | 0.78%   |
| Seagate ST9500325AS 500GB           | 2         | 0.78%   |
| Seagate ST1000DM003-1CH162 1TB      | 2         | 0.78%   |
| SanDisk SSD PLUS 480GB              | 2         | 0.78%   |
| Sandisk NVMe SSD Drive 256GB        | 2         | 0.78%   |
| Samsung SSD 860 EVO 1TB             | 2         | 0.78%   |
| Samsung SSD 840 EVO 250GB           | 2         | 0.78%   |
| Samsung SSD 840 EVO 120GB           | 2         | 0.78%   |
| Samsung NVMe SSD Drive 512GB        | 2         | 0.78%   |
| Samsung HD103UJ 1TB                 | 2         | 0.78%   |
| Samsung HD103SJ 1TB                 | 2         | 0.78%   |
| Kingston SV300S37A240G 240GB SSD    | 2         | 0.78%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.78%   |
| Intenso SSD SATAIII 960GB           | 2         | 0.78%   |
| HGST HTS725050A7E630 500GB          | 2         | 0.78%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 0.78%   |
| XPG NVMe SSD Drive 1024GB           | 1         | 0.39%   |
| WDC WDS250G2B0A-00SM50 250GB SSD    | 1         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.39%   |
| WDC WD7500AARS-00Y5B1 752GB         | 1         | 0.39%   |
| WDC WD6400AAKS-65A7B0 640GB         | 1         | 0.39%   |
| WDC WD5000LPVT-22G33T0 500GB        | 1         | 0.39%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 0.39%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 1         | 0.39%   |
| WDC WD5000AAKS-00YGA0 500GB         | 1         | 0.39%   |
| WDC WD5000AADS-00S9B0 500GB         | 1         | 0.39%   |
| WDC WD40EZAZ-00SF3B0 4TB            | 1         | 0.39%   |
| WDC WD3200BUCT-63TWBY0 320GB        | 1         | 0.39%   |
| WDC WD30EZRX-00D8PB0 3TB            | 1         | 0.39%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1         | 0.39%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1         | 0.39%   |
| WDC WD20EURX-61T0FY0 2TB            | 1         | 0.39%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 0.39%   |
| WDC WD1600AAJS-75M0A0 160GB         | 1         | 0.39%   |
| WDC WD1600AAJS-22PSA0 160GB         | 1         | 0.39%   |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 0.39%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 0.39%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 0.39%   |
| WDC WD10EZEX-75M2NA0 1TB            | 1         | 0.39%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 51     | 41.75%  |
| WDC                 | 27        | 34     | 26.21%  |
| Toshiba             | 10        | 10     | 9.71%   |
| Samsung Electronics | 7         | 9      | 6.8%    |
| Hitachi             | 6         | 8      | 5.83%   |
| HGST                | 4         | 4      | 3.88%   |
| Fujitsu             | 2         | 2      | 1.94%   |
| Apple               | 2         | 2      | 1.94%   |
| Maxtor              | 1         | 1      | 0.97%   |
| Hewlett-Packard     | 1         | 1      | 0.97%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 22     | 21.18%  |
| Kingston            | 15        | 18     | 17.65%  |
| SanDisk             | 13        | 16     | 15.29%  |
| Crucial             | 6         | 8      | 7.06%   |
| China               | 4         | 4      | 4.71%   |
| Apple               | 3         | 3      | 3.53%   |
| A-DATA Technology   | 3         | 3      | 3.53%   |
| WDC                 | 2         | 2      | 2.35%   |
| Toshiba             | 2         | 2      | 2.35%   |
| Micron Technology   | 2         | 2      | 2.35%   |
| LITEONIT            | 2         | 3      | 2.35%   |
| Intenso             | 2         | 2      | 2.35%   |
| USB30               | 1         | 2      | 1.18%   |
| SPCC                | 1         | 1      | 1.18%   |
| Seagate             | 1         | 1      | 1.18%   |
| PNY                 | 1         | 1      | 1.18%   |
| PHISON              | 1         | 1      | 1.18%   |
| Patriot             | 1         | 1      | 1.18%   |
| OCZ                 | 1         | 1      | 1.18%   |
| Lexar               | 1         | 1      | 1.18%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.18%   |
| KingSpec            | 1         | 1      | 1.18%   |
| Intel               | 1         | 1      | 1.18%   |
| BUFFALO             | 1         | 1      | 1.18%   |
| Apacer              | 1         | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 87        | 122    | 42.86%  |
| SSD     | 68        | 99     | 33.5%   |
| NVMe    | 36        | 42     | 17.73%  |
| Unknown | 9         | 10     | 4.43%   |
| MMC     | 3         | 4      | 1.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 123       | 219    | 71.51%  |
| NVMe | 36        | 42     | 20.93%  |
| SAS  | 10        | 12     | 5.81%   |
| MMC  | 3         | 4      | 1.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 91        | 125    | 56.52%  |
| 0.51-1.0   | 54        | 74     | 33.54%  |
| 1.01-2.0   | 11        | 16     | 6.83%   |
| 3.01-4.0   | 3         | 3      | 1.86%   |
| 2.01-3.0   | 1         | 2      | 0.62%   |
| 4.01-10.0  | 1         | 1      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 40        | 27.21%  |
| 101-250        | 39        | 26.53%  |
| 501-1000       | 24        | 16.33%  |
| 51-100         | 15        | 10.2%   |
| 1001-2000      | 13        | 8.84%   |
| 21-50          | 5         | 3.4%    |
| 1-20           | 4         | 2.72%   |
| More than 3000 | 3         | 2.04%   |
| 2001-3000      | 3         | 2.04%   |
| Unknown        | 1         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 73        | 48.67%  |
| 21-50          | 33        | 22%     |
| 101-250        | 12        | 8%      |
| 51-100         | 12        | 8%      |
| 251-500        | 7         | 4.67%   |
| 501-1000       | 6         | 4%      |
| 1001-2000      | 3         | 2%      |
| More than 3000 | 2         | 1.33%   |
| 2001-3000      | 1         | 0.67%   |
| Unknown        | 1         | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB    | 2         | 2      | 40%     |
| WDC WD10EZEX-21M2NA0 1TB   | 1         | 2      | 20%     |
| Toshiba MK3265GSX 320GB    | 1         | 1      | 20%     |
| HGST HTS725050A7E630 500GB | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 60%     |
| WDC     | 1         | 2      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 60%     |
| WDC     | 1         | 2      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                 | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 130       | 254    | 86.09%  |
| Works    | 15        | 16     | 9.93%   |
| Malfunc  | 5         | 6      | 3.31%   |
| Failed   | 1         | 1      | 0.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 102       | 56.04%  |
| AMD                              | 33        | 18.13%  |
| Samsung Electronics              | 12        | 6.59%   |
| Sandisk                          | 8         | 4.4%    |
| Phison Electronics               | 5         | 2.75%   |
| ASMedia Technology               | 4         | 2.2%    |
| Toshiba America Info Systems     | 2         | 1.1%    |
| Silicon Motion                   | 2         | 1.1%    |
| Silicon Image                    | 2         | 1.1%    |
| Micron/Crucial Technology        | 2         | 1.1%    |
| KIOXIA                           | 2         | 1.1%    |
| ADATA Technology                 | 2         | 1.1%    |
| VIA Technologies                 | 1         | 0.55%   |
| SK Hynix                         | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| Marvell Technology Group         | 1         | 0.55%   |
| Kingston Technology Company      | 1         | 0.55%   |
| JMicron Technology               | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 21        | 10.4%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14        | 6.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 3.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 3.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 2.48%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 2.48%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 2.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 1.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 1.98%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4         | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 1.98%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 1.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 1.49%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3         | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.49%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.49%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 3         | 1.49%   |
| AMD FCH SATA Controller D                                                               | 3         | 1.49%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.99%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.99%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 0.99%   |
| Samsung NVMe Controller                                                                 | 2         | 0.99%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 0.99%   |
| Intel SSD 660P Series                                                                   | 2         | 0.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 0.99%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 0.99%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 0.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 0.99%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2         | 0.99%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.5%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 0.5%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.5%    |
| SK Hynix BC511                                                                          | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1         | 0.5%    |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1         | 0.5%    |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 1         | 0.5%    |
| Sandisk PC SN520 NVMe SSD                                                               | 1         | 0.5%    |
| Samsung Electronics SATA controller                                                     | 1         | 0.5%    |
| Samsung Apple PCIe SSD                                                                  | 1         | 0.5%    |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.5%    |
| Phison E12 NVMe Controller                                                              | 1         | 0.5%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1         | 0.5%    |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.5%    |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 115       | 63.89%  |
| NVMe | 36        | 20%     |
| IDE  | 17        | 9.44%   |
| RAID | 12        | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 111       | 75.51%  |
| AMD    | 36        | 24.49%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 2.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 2.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 2.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.36%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.36%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 1.36%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 1.36%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.36%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.36%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2         | 1.36%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 1.36%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 1.36%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 1.36%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 1.36%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.36%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 1.36%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.36%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.36%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 2         | 1.36%   |
| AMD FX-8320E Eight-Core Processor             | 2         | 1.36%   |
| Intel Xeon CPU X3220 @ 2.40GHz                | 1         | 0.68%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.68%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.68%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.68%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz        | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.68%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 1         | 0.68%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.68%   |
| Intel Pentium CPU 3550M @ 2.30GHz             | 1         | 0.68%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.68%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.68%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.68%   |
| Intel Core i7-4940MX CPU @ 3.10GHz            | 1         | 0.68%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 1         | 0.68%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.68%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.68%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.68%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.68%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.68%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.68%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 0.68%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.68%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.68%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 1         | 0.68%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 1         | 0.68%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 0.68%   |
| Intel Core i5-4570R CPU @ 2.70GHz             | 1         | 0.68%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 0.68%   |
| Intel Core i5-4430 CPU @ 3.00GHz              | 1         | 0.68%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 0.68%   |
| Intel Core i5-4258U CPU @ 2.40GHz             | 1         | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 29.25%  |
| Intel Core i7           | 24        | 16.33%  |
| Intel Core i3           | 16        | 10.88%  |
| AMD Ryzen 5             | 7         | 4.76%   |
| Other                   | 6         | 4.08%   |
| AMD Ryzen 7             | 6         | 4.08%   |
| AMD FX                  | 6         | 4.08%   |
| Intel Celeron           | 5         | 3.4%    |
| Intel Core 2 Duo        | 4         | 2.72%   |
| AMD Ryzen 3             | 4         | 2.72%   |
| Intel Pentium Silver    | 2         | 1.36%   |
| Intel Pentium Dual-Core | 2         | 1.36%   |
| Intel Pentium           | 2         | 1.36%   |
| Intel Core 2 Quad       | 2         | 1.36%   |
| Intel Atom              | 2         | 1.36%   |
| AMD A6                  | 2         | 1.36%   |
| Intel Xeon              | 1         | 0.68%   |
| Intel Pentium Gold      | 1         | 0.68%   |
| Intel Pentium Dual      | 1         | 0.68%   |
| Intel Core i9           | 1         | 0.68%   |
| AMD Turion 64 Mobile    | 1         | 0.68%   |
| AMD Ryzen 9             | 1         | 0.68%   |
| AMD Phenom II X4        | 1         | 0.68%   |
| AMD E2                  | 1         | 0.68%   |
| AMD E1                  | 1         | 0.68%   |
| AMD E                   | 1         | 0.68%   |
| AMD C-60                | 1         | 0.68%   |
| AMD Athlon              | 1         | 0.68%   |
| AMD A4                  | 1         | 0.68%   |
| AMD A10                 | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 71        | 48.3%   |
| 2      | 58        | 39.46%  |
| 8      | 7         | 4.76%   |
| 6      | 4         | 2.72%   |
| 1      | 3         | 2.04%   |
| 3      | 2         | 1.36%   |
| 12     | 1         | 0.68%   |
| 10     | 1         | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 147       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 94        | 63.95%  |
| 1      | 53        | 36.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 147       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 17        | 11.49%  |
| 0x306a9    | 14        | 9.46%   |
| Unknown    | 10        | 6.76%   |
| 0x40651    | 9         | 6.08%   |
| 0x206a7    | 9         | 6.08%   |
| 0x806ea    | 5         | 3.38%   |
| 0x08701021 | 5         | 3.38%   |
| 0x06000852 | 5         | 3.38%   |
| 0x806ec    | 4         | 2.7%    |
| 0x806c1    | 4         | 2.7%    |
| 0x6fb      | 4         | 2.7%    |
| 0x506e3    | 4         | 2.7%    |
| 0x306d4    | 4         | 2.7%    |
| 0x08108109 | 4         | 2.7%    |
| 0x706a1    | 3         | 2.03%   |
| 0x30678    | 3         | 2.03%   |
| 0x1067a    | 3         | 2.03%   |
| 0x06001119 | 3         | 2.03%   |
| 0x05000119 | 3         | 2.03%   |
| 0x906eb    | 2         | 1.35%   |
| 0x806e9    | 2         | 1.35%   |
| 0x6fd      | 2         | 1.35%   |
| 0x40661    | 2         | 1.35%   |
| 0x20655    | 2         | 1.35%   |
| 0x0800820d | 2         | 1.35%   |
| 0xa0655    | 1         | 0.68%   |
| 0xa0653    | 1         | 0.68%   |
| 0xa0652    | 1         | 0.68%   |
| 0x906ec    | 1         | 0.68%   |
| 0x906ea    | 1         | 0.68%   |
| 0x906e9    | 1         | 0.68%   |
| 0x906c0    | 1         | 0.68%   |
| 0x806eb    | 1         | 0.68%   |
| 0x30661    | 1         | 0.68%   |
| 0x106e5    | 1         | 0.68%   |
| 0x10676    | 1         | 0.68%   |
| 0x08701013 | 1         | 0.68%   |
| 0x08608102 | 1         | 0.68%   |
| 0x08600106 | 1         | 0.68%   |
| 0x08600104 | 1         | 0.68%   |
| 0x08108102 | 1         | 0.68%   |
| 0x08101016 | 1         | 0.68%   |
| 0x08001138 | 1         | 0.68%   |
| 0x07030106 | 1         | 0.68%   |
| 0x0700010f | 1         | 0.68%   |
| 0x06006705 | 1         | 0.68%   |
| 0x06003106 | 1         | 0.68%   |
| 0x010000c8 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 28        | 19.05%  |
| KabyLake      | 20        | 13.61%  |
| IvyBridge     | 14        | 9.52%   |
| SandyBridge   | 10        | 6.8%    |
| Zen 2         | 8         | 5.44%   |
| Piledriver    | 8         | 5.44%   |
| Zen+          | 7         | 4.76%   |
| Core          | 6         | 4.08%   |
| Skylake       | 5         | 3.4%    |
| TigerLake     | 4         | 2.72%   |
| Silvermont    | 4         | 2.72%   |
| Penryn        | 4         | 2.72%   |
| Broadwell     | 4         | 2.72%   |
| Zen           | 3         | 2.04%   |
| Goldmont plus | 3         | 2.04%   |
| CometLake     | 3         | 2.04%   |
| Bobcat        | 3         | 2.04%   |
| Westmere      | 2         | 1.36%   |
| Nehalem       | 2         | 1.36%   |
| Tremont       | 1         | 0.68%   |
| Steamroller   | 1         | 0.68%   |
| Puma          | 1         | 0.68%   |
| K8 Hammer     | 1         | 0.68%   |
| K10           | 1         | 0.68%   |
| Jaguar        | 1         | 0.68%   |
| Excavator     | 1         | 0.68%   |
| Bonnell       | 1         | 0.68%   |
| Unknown       | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 81        | 47.65%  |
| Nvidia                           | 48        | 28.24%  |
| AMD                              | 40        | 23.53%  |
| Silicon Integrated Systems [SiS] | 1         | 0.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                            | 9         | 5.2%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 4.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7         | 4.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 3.47%   |
| Intel UHD Graphics 620                                                      | 5         | 2.89%   |
| AMD Picasso                                                                 | 5         | 2.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 2.31%   |
| Intel HD Graphics 620                                                       | 4         | 2.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 4         | 2.31%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.73%   |
| Intel HD Graphics 5500                                                      | 3         | 1.73%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 1.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 1.73%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3         | 1.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.16%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.16%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2         | 1.16%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 1.16%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2         | 1.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 1.16%   |
| Intel HD Graphics 630                                                       | 2         | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 1.16%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.16%   |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 2         | 1.16%   |
| AMD RS780L [Radeon 3000]                                                    | 2         | 1.16%   |
| AMD Renoir                                                                  | 2         | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2         | 1.16%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2         | 1.16%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1         | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.58%   |
| Nvidia TU117M                                                               | 1         | 0.58%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 0.58%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.58%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.58%   |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 0.58%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.58%   |
| Nvidia GT216M [GeForce GT 240M]                                             | 1         | 0.58%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.58%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.58%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.58%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.58%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 0.58%   |
| Nvidia GM107GL [Quadro K1200]                                               | 1         | 0.58%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.58%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 0.58%   |
| Nvidia GK208BM [GeForce 920M]                                               | 1         | 0.58%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1         | 0.58%   |
| Nvidia GK107M [GeForce GT 750M]                                             | 1         | 0.58%   |
| Nvidia GK107M [GeForce GT 640M LE]                                          | 1         | 0.58%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 1         | 0.58%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 0.58%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1         | 0.58%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1         | 0.58%   |
| Nvidia GK104M [GeForce GTX 680MX]                                           | 1         | 0.58%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1         | 0.58%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.58%   |
| Nvidia GF108M [GeForce GT 555M]                                             | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 60        | 40.54%  |
| 1 x AMD        | 34        | 22.97%  |
| 1 x Nvidia     | 33        | 22.3%   |
| Intel + Nvidia | 13        | 8.78%   |
| Intel + AMD    | 3         | 2.03%   |
| 2 x AMD        | 2         | 1.35%   |
| AMD + Nvidia   | 2         | 1.35%   |
| 1 x SiS        | 1         | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 108       | 73.47%  |
| Proprietary | 37        | 25.17%  |
| Unknown     | 2         | 1.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 47.62%  |
| 1.01-2.0   | 28        | 19.05%  |
| 0.01-0.5   | 16        | 10.88%  |
| 0.51-1.0   | 12        | 8.16%   |
| 3.01-4.0   | 9         | 6.12%   |
| 7.01-8.0   | 5         | 3.4%    |
| 5.01-6.0   | 4         | 2.72%   |
| 2.01-3.0   | 2         | 1.36%   |
| 16.01-24.0 | 1         | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 23        | 14.84%  |
| Chimei Innolux          | 14        | 9.03%   |
| AU Optronics            | 13        | 8.39%   |
| LG Display              | 11        | 7.1%    |
| BOE                     | 10        | 6.45%   |
| Acer                    | 8         | 5.16%   |
| Apple                   | 6         | 3.87%   |
| AOC                     | 6         | 3.87%   |
| Philips                 | 5         | 3.23%   |
| Hewlett-Packard         | 5         | 3.23%   |
| Dell                    | 5         | 3.23%   |
| Vizio                   | 4         | 2.58%   |
| Sharp                   | 4         | 2.58%   |
| Lenovo                  | 4         | 2.58%   |
| Goldstar                | 4         | 2.58%   |
| Chi Mei Optoelectronics | 4         | 2.58%   |
| Sony                    | 3         | 1.94%   |
| Ancor Communications    | 3         | 1.94%   |
| PANDA                   | 2         | 1.29%   |
| NEC Computers           | 2         | 1.29%   |
| LG Electronics          | 2         | 1.29%   |
| InfoVision              | 2         | 1.29%   |
| BenQ                    | 2         | 1.29%   |
| Xiaomi                  | 1         | 0.65%   |
| ViewSonic               | 1         | 0.65%   |
| Vestel                  | 1         | 0.65%   |
| Unknown                 | 1         | 0.65%   |
| Sceptre Tech            | 1         | 0.65%   |
| LGD                     | 1         | 0.65%   |
| LG Philips              | 1         | 0.65%   |
| Iiyama                  | 1         | 0.65%   |
| HPN                     | 1         | 0.65%   |
| Gigabyte Technology     | 1         | 0.65%   |
| Gateway                 | 1         | 0.65%   |
| Fujitsu Siemens         | 1         | 0.65%   |
| AUS                     | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch         | 3         | 1.89%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch             | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch           | 2         | 1.26%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                      | 1         | 0.63%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch               | 1         | 0.63%   |
| Vizio PC VIZCA27 1920x1080 597x336mm 27.0-inch                          | 1         | 0.63%   |
| Vizio E43u-D2 VIZ1018 3840x2160 953x543mm 43.2-inch                     | 1         | 0.63%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 0.63%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                           | 1         | 0.63%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 1         | 0.63%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                               | 1         | 0.63%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                      | 1         | 0.63%   |
| Sony TV *00 SNYA405 3840x2160 952x535mm 43.0-inch                       | 1         | 0.63%   |
| Sony AVAMP SNY9301 1280x720 708x398mm 32.0-inch                         | 1         | 0.63%   |
| Sharp LQ134R1JX48 SHP1528 3840x2400 288x180mm 13.4-inch                 | 1         | 0.63%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                 | 1         | 0.63%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                 | 1         | 0.63%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                 | 1         | 0.63%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1         | 0.63%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1         | 0.63%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1         | 0.63%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0604 1920x1080                        | 1         | 0.63%   |
| Samsung Electronics S27R65x SAM1046 1920x1080 600x340mm 27.2-inch       | 1         | 0.63%   |
| Samsung Electronics S27R65 SAM1045 1920x1080 598x336mm 27.0-inch        | 1         | 0.63%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch       | 1         | 0.63%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 256x144mm 11.6-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0C3C 1920x1080 700x390mm 31.5-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 700x390mm 31.5-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor C27R50x 1920x1080                       | 1         | 0.63%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch      | 1         | 0.63%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 598x336mm 27.0-inch                | 1         | 0.63%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                 | 1         | 0.63%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1         | 0.63%   |
| Philips LCD Monitor 240B 1920x1200                                      | 1         | 0.63%   |
| Philips LCD Monitor 227EQPH 1920x1080                                   | 1         | 0.63%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.63%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                 | 1         | 0.63%   |
| NEC Computers LCD Monitor E231W 3840x1080                               | 1         | 0.63%   |
| NEC Computers LCD Monitor E231W                                         | 1         | 0.63%   |
| NEC Computers EA244WMi NEC68D7 1920x1080 520x320mm 24.0-inch            | 1         | 0.63%   |
| LGD LCD Monitor 3840x1200                                               | 1         | 0.63%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch             | 1         | 0.63%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                         | 1         | 0.63%   |
| LG Electronics LCD Monitor EW224 1920x1080                              | 1         | 0.63%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch            | 1         | 0.63%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 0.63%   |
| LG Display LCD Monitor LGD0468 1366x768 340x190mm 15.3-inch             | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 62        | 41.61%  |
| 1366x768 (WXGA)    | 36        | 24.16%  |
| 3840x2160 (4K)     | 13        | 8.72%   |
| 1600x900 (HD+)     | 6         | 4.03%   |
| 3840x1080          | 3         | 2.01%   |
| 2560x1440 (QHD)    | 3         | 2.01%   |
| 1280x800 (WXGA)    | 3         | 2.01%   |
| Unknown            | 3         | 2.01%   |
| 3840x2400          | 2         | 1.34%   |
| 2560x1600          | 2         | 1.34%   |
| 1920x1200 (WUXGA)  | 2         | 1.34%   |
| 1680x1050 (WSXGA+) | 2         | 1.34%   |
| 1280x1024 (SXGA)   | 2         | 1.34%   |
| 3840x1200          | 1         | 0.67%   |
| 3440x1440          | 1         | 0.67%   |
| 3200x1800 (QHD+)   | 1         | 0.67%   |
| 3120x1050          | 1         | 0.67%   |
| 2880x1800          | 1         | 0.67%   |
| 1600x1200          | 1         | 0.67%   |
| 1440x900 (WXGA+)   | 1         | 0.67%   |
| 1280x720 (HD)      | 1         | 0.67%   |
| 1024x768 (XGA)     | 1         | 0.67%   |
| 1024x600           | 1         | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 42        | 27.63%  |
| Unknown | 23        | 15.13%  |
| 13      | 16        | 10.53%  |
| 27      | 10        | 6.58%   |
| 24      | 8         | 5.26%   |
| 14      | 7         | 4.61%   |
| 31      | 5         | 3.29%   |
| 23      | 5         | 3.29%   |
| 21      | 5         | 3.29%   |
| 17      | 5         | 3.29%   |
| 19      | 3         | 1.97%   |
| 18      | 3         | 1.97%   |
| 11      | 3         | 1.97%   |
| 48      | 2         | 1.32%   |
| 25      | 2         | 1.32%   |
| 22      | 2         | 1.32%   |
| 84      | 1         | 0.66%   |
| 74      | 1         | 0.66%   |
| 55      | 1         | 0.66%   |
| 46      | 1         | 0.66%   |
| 43      | 1         | 0.66%   |
| 41      | 1         | 0.66%   |
| 40      | 1         | 0.66%   |
| 36      | 1         | 0.66%   |
| 34      | 1         | 0.66%   |
| 32      | 1         | 0.66%   |
| 10      | 1         | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 37.58%  |
| Unknown     | 23        | 15.44%  |
| 501-600     | 22        | 14.77%  |
| 201-300     | 14        | 9.4%    |
| 401-500     | 11        | 7.38%   |
| 601-700     | 6         | 4.03%   |
| 351-400     | 5         | 3.36%   |
| 1001-1500   | 4         | 2.68%   |
| 701-800     | 3         | 2.01%   |
| 1501-2000   | 2         | 1.34%   |
| 901-1000    | 2         | 1.34%   |
| 801-900     | 1         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 100       | 71.43%  |
| Unknown | 22        | 15.71%  |
| 16/10   | 13        | 9.29%   |
| 4/3     | 2         | 1.43%   |
| 5/4     | 1         | 0.71%   |
| 32/9    | 1         | 0.71%   |
| 21/9    | 1         | 0.71%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 42        | 27.63%  |
| Unknown        | 23        | 15.13%  |
| 201-250        | 18        | 11.84%  |
| 81-90          | 14        | 9.21%   |
| 301-350        | 10        | 6.58%   |
| 71-80          | 9         | 5.92%   |
| 351-500        | 7         | 4.61%   |
| 501-1000       | 6         | 3.95%   |
| More than 1000 | 4         | 2.63%   |
| 151-200        | 4         | 2.63%   |
| 121-130        | 4         | 2.63%   |
| 51-60          | 3         | 1.97%   |
| 251-300        | 3         | 1.97%   |
| 141-150        | 3         | 1.97%   |
| 41-50          | 1         | 0.66%   |
| 91-100         | 1         | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 48        | 32.43%  |
| 51-100        | 35        | 23.65%  |
| 121-160       | 25        | 16.89%  |
| Unknown       | 23        | 15.54%  |
| 161-240       | 7         | 4.73%   |
| More than 240 | 5         | 3.38%   |
| 1-50          | 5         | 3.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 127       | 85.81%  |
| 2     | 19        | 12.84%  |
| 0     | 2         | 1.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 91        | 39.22%  |
| Intel                            | 58        | 25%     |
| Qualcomm Atheros                 | 28        | 12.07%  |
| Broadcom                         | 14        | 6.03%   |
| Ralink                           | 6         | 2.59%   |
| Broadcom Limited                 | 6         | 2.59%   |
| TP-Link                          | 5         | 2.16%   |
| Ralink Technology                | 4         | 1.72%   |
| Marvell Technology Group         | 3         | 1.29%   |
| Samsung Electronics              | 2         | 0.86%   |
| DisplayLink                      | 2         | 0.86%   |
| D-Link System                    | 2         | 0.86%   |
| T & A Mobile Phones              | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] | 1         | 0.43%   |
| Qualcomm                         | 1         | 0.43%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.43%   |
| NetGear                          | 1         | 0.43%   |
| Motorola PCS                     | 1         | 0.43%   |
| MediaTek                         | 1         | 0.43%   |
| ICS Advent                       | 1         | 0.43%   |
| Google                           | 1         | 0.43%   |
| Edimax Technology                | 1         | 0.43%   |
| ASIX Electronics                 | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 24.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 4.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.69%   |
| Intel Wireless 7260                                               | 6         | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.15%   |
| Realtek 802.11ac NIC                                              | 3         | 1.15%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.15%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.15%   |
| Intel WiFi Link 5100                                              | 3         | 1.15%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.15%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.15%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.15%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2         | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.77%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2         | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.77%   |
| Intel Wireless-AC 9260                                            | 2         | 0.77%   |
| Intel Wireless 3160                                               | 2         | 0.77%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.77%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.77%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.77%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.77%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 0.77%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.38%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.38%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.38%   |
| T & A Mobile Phones TCL T790S                                     | 1         | 0.38%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.38%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.38%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.38%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.38%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.38%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.38%   |
| Ralink RT5592 PCIe Wireless Network Adapter                       | 1         | 0.38%   |
| Ralink RT2600 802.11 MIMO                                         | 1         | 0.38%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 34.75%  |
| Qualcomm Atheros      | 22        | 18.64%  |
| Realtek Semiconductor | 21        | 17.8%   |
| Broadcom              | 11        | 9.32%   |
| Ralink                | 6         | 5.08%   |
| TP-Link               | 5         | 4.24%   |
| Ralink Technology     | 4         | 3.39%   |
| Broadcom Limited      | 4         | 3.39%   |
| Qualcomm              | 1         | 0.85%   |
| NetGear               | 1         | 0.85%   |
| Edimax Technology     | 1         | 0.85%   |
| D-Link System         | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 7         | 5.88%   |
| Intel Wireless 7260                                                           | 6         | 5.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 4         | 3.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4         | 3.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 2.52%   |
| Realtek 802.11ac NIC                                                          | 3         | 2.52%   |
| Ralink MT7601U Wireless Adapter                                               | 3         | 2.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 3         | 2.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3         | 2.52%   |
| Intel WiFi Link 5100                                                          | 3         | 2.52%   |
| Intel Wi-Fi 6 AX201                                                           | 3         | 2.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 2.52%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 3         | 2.52%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 2         | 1.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2         | 1.68%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 2         | 1.68%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 1.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.68%   |
| Intel Wireless-AC 9260                                                        | 2         | 1.68%   |
| Intel Wireless 3160                                                           | 2         | 1.68%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 1.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 1.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 1.68%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 1.68%   |
| Intel Centrino Wireless-N 2230                                                | 2         | 1.68%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 1.68%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 2         | 1.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.84%   |
| TP-Link Archer T4U ver.3                                                      | 1         | 0.84%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.84%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.84%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 0.84%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1         | 0.84%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.84%   |
| Ralink RT5592 PCIe Wireless Network Adapter                                   | 1         | 0.84%   |
| Ralink RT2600 802.11 MIMO                                                     | 1         | 0.84%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 1         | 0.84%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]                   | 1         | 0.84%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.84%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.84%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                   | 1         | 0.84%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 0.84%   |
| Intel Wireless 8260                                                           | 1         | 0.84%   |
| Intel Wireless 7265                                                           | 1         | 0.84%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.84%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 0.84%   |
| Intel Centrino Wireless-N 130                                                 | 1         | 0.84%   |
| Intel Centrino Wireless-N 105                                                 | 1         | 0.84%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1         | 0.84%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 0.84%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870]          | 1         | 0.84%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 1         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 82        | 59.42%  |
| Intel                            | 26        | 18.84%  |
| Qualcomm Atheros                 | 8         | 5.8%    |
| Broadcom                         | 5         | 3.62%   |
| Marvell Technology Group         | 3         | 2.17%   |
| Samsung Electronics              | 2         | 1.45%   |
| DisplayLink                      | 2         | 1.45%   |
| Broadcom Limited                 | 2         | 1.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.72%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.72%   |
| Motorola PCS                     | 1         | 0.72%   |
| MediaTek                         | 1         | 0.72%   |
| ICS Advent                       | 1         | 0.72%   |
| Google                           | 1         | 0.72%   |
| D-Link System                    | 1         | 0.72%   |
| ASIX Electronics                 | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 45.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 7.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.29%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 2.14%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 2.14%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 2.14%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.43%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.43%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.71%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.71%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.71%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.71%   |
| OnePlus (Shenzhen) IN2011                                         | 1         | 0.71%   |
| Motorola PCS moto g(30)                                           | 1         | 0.71%   |
| MediaTek Armor X5                                                 | 1         | 0.71%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.71%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.71%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.71%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.71%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.71%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.71%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.71%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 0.71%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.71%   |
| ICS Advent 10/100M LAN                                            | 1         | 0.71%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.71%   |
| DisplayLink USB 3.0 Dual Video Dock                               | 1         | 0.71%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.71%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.71%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 0.71%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 133       | 54.07%  |
| WiFi     | 112       | 45.53%  |
| Unknown  | 1         | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 124       | 55.36%  |
| WiFi     | 99        | 44.2%   |
| Unknown  | 1         | 0.45%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 78        | 53.06%  |
| 1     | 67        | 45.58%  |
| 3     | 1         | 0.68%   |
| 0     | 1         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 99        | 66.44%  |
| Yes  | 50        | 33.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 36.67%  |
| Qualcomm Atheros Communications | 10        | 11.11%  |
| Realtek Semiconductor           | 8         | 8.89%   |
| Apple                           | 7         | 7.78%   |
| Lite-On Technology              | 6         | 6.67%   |
| IMC Networks                    | 5         | 5.56%   |
| Cambridge Silicon Radio         | 5         | 5.56%   |
| Broadcom                        | 5         | 5.56%   |
| Ralink                          | 3         | 3.33%   |
| Foxconn / Hon Hai               | 3         | 3.33%   |
| Foxconn International           | 2         | 2.22%   |
| Dell                            | 1         | 1.11%   |
| ASUSTek Computer                | 1         | 1.11%   |
| Alps Electric                   | 1         | 1.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 15.56%  |
| Intel Bluetooth Device                              | 9         | 10%     |
| Realtek Bluetooth Radio                             | 7         | 7.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 4.44%   |
| Ralink RT3290 Bluetooth                             | 3         | 3.33%   |
| Apple Bluetooth USB Host Controller                 | 3         | 3.33%   |
| Lite-On Bluetooth Device                            | 2         | 2.22%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.22%   |
| Intel AX200 Bluetooth                               | 2         | 2.22%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.22%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 2.22%   |
| Apple Bluetooth Host Controller                     | 2         | 2.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.11%   |
| Qualcomm Atheros Bluetooth                          | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.11%   |
| Lite-On BCM43142A0                                  | 1         | 1.11%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.11%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.11%   |
| IMC Networks Bluetooth Device                       | 1         | 1.11%   |
| IMC Networks Bluetooth                              | 1         | 1.11%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.11%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.11%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.11%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.11%   |
| Dell BT Mini-Receiver                               | 1         | 1.11%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module            | 1         | 1.11%   |
| Broadcom Bluetooth                                  | 1         | 1.11%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.11%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.11%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.11%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.11%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.11%   |
| Apple Bluetooth HCI                                 | 1         | 1.11%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 108       | 52.17%  |
| AMD                              | 44        | 21.26%  |
| Nvidia                           | 39        | 18.84%  |
| Texas Instruments                | 2         | 0.97%   |
| JMTek                            | 2         | 0.97%   |
| Creative Labs                    | 2         | 0.97%   |
| C-Media Electronics              | 2         | 0.97%   |
| XMOS                             | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] | 1         | 0.48%   |
| Razer USA                        | 1         | 0.48%   |
| Numark                           | 1         | 0.48%   |
| Logitech                         | 1         | 0.48%   |
| Klipsch Audio                    | 1         | 0.48%   |
| iConnectivity                    | 1         | 0.48%   |
| GN Netcom                        | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 5.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 5.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 4.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 4.28%   |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 3.89%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 10        | 3.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 3.5%    |
| Intel 8 Series HD Audio Controller                                         | 9         | 3.5%    |
| AMD FCH Azalia Controller                                                  | 8         | 3.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7         | 2.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 2.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 1.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.56%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.17%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.17%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.17%   |
| AMD Wrestler HDMI Audio                                                    | 3         | 1.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.78%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.78%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.78%   |
| JMTek USB PnP Audio Device                                                 | 2         | 0.78%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.78%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.78%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.78%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 2         | 0.78%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 0.78%   |
| XMOS Gustard USB Audio 2.0                                                 | 1         | 0.39%   |
| Texas Instruments PCM2901 Audio Codec                                      | 1         | 0.39%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.39%   |
| Razer USA Razer USB Sound Card                                             | 1         | 0.39%   |
| Razer USA Razer Seiren Mini                                                | 1         | 0.39%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.39%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.39%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.39%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.39%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.39%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.39%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 22.22%  |
| Unknown             | 4         | 14.81%  |
| Micron Technology   | 4         | 14.81%  |
| SK Hynix            | 3         | 11.11%  |
| Kingston            | 2         | 7.41%   |
| Crucial             | 2         | 7.41%   |
| A-DATA Technology   | 2         | 7.41%   |
| Team                | 1         | 3.7%    |
| Strontium           | 1         | 3.7%    |
| Ramaxel Technology  | 1         | 3.7%    |
| Corsair             | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| A-DATA RAM AE4S240038G17-BHYA 8192MB SODIMM DDR4 2400MT/s         | 2         | 6.45%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s           | 1         | 3.23%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                         | 1         | 3.23%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1         | 3.23%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                    | 1         | 3.23%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                      | 1         | 3.23%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s                | 1         | 3.23%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s                | 1         | 3.23%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s              | 1         | 3.23%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 3.23%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 3.23%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 3.23%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s     | 1         | 3.23%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s          | 1         | 3.23%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s             | 1         | 3.23%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s             | 1         | 3.23%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s          | 1         | 3.23%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 1         | 3.23%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s    | 1         | 3.23%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s          | 1         | 3.23%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 3.23%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 3.23%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s          | 1         | 3.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s        | 1         | 3.23%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s         | 1         | 3.23%   |
| Kingston RAM K821PJ-MID 16384MB SODIMM DDR4 2400MT/s              | 1         | 3.23%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 3.23%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s            | 1         | 3.23%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s        | 1         | 3.23%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s            | 1         | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 12        | 48%     |
| DDR3    | 9         | 36%     |
| SDRAM   | 1         | 4%      |
| LPDDR4  | 1         | 4%      |
| LPDDR3  | 1         | 4%      |
| Unknown | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 16        | 64%     |
| DIMM         | 5         | 20%     |
| Row Of Chips | 4         | 16%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 11        | 42.31%  |
| 8192  | 8         | 30.77%  |
| 2048  | 4         | 15.38%  |
| 32768 | 2         | 7.69%   |
| 16384 | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 7         | 26.92%  |
| 2667  | 6         | 23.08%  |
| 2400  | 4         | 15.38%  |
| 3200  | 3         | 11.54%  |
| 1333  | 3         | 11.54%  |
| 4267  | 1         | 3.85%   |
| 4199  | 1         | 3.85%   |
| 1867  | 1         | 3.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Canon               | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SCX-3400 Series         | 1         | 20%     |
| HP OfficeJet 4650 series        | 1         | 20%     |
| HP LaserJet Professional P1102w | 1         | 20%     |
| Canon PIXMA MG2500 Series       | 1         | 20%     |
| Canon LiDE 400                  | 1         | 20%     |

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
| Chicony Electronics                    | 13        | 15.48%  |
| IMC Networks                           | 10        | 11.9%   |
| Realtek Semiconductor                  | 8         | 9.52%   |
| Microdia                               | 8         | 9.52%   |
| Acer                                   | 8         | 9.52%   |
| Sunplus Innovation Technology          | 5         | 5.95%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 5.95%   |
| Apple                                  | 4         | 4.76%   |
| Suyin                                  | 3         | 3.57%   |
| Quanta                                 | 3         | 3.57%   |
| Lite-On Technology                     | 3         | 3.57%   |
| Syntek                                 | 2         | 2.38%   |
| Generalplus Technology                 | 2         | 2.38%   |
| Teslong Camera                         | 1         | 1.19%   |
| Samsung Electronics                    | 1         | 1.19%   |
| Ricoh                                  | 1         | 1.19%   |
| Razer USA                              | 1         | 1.19%   |
| Microsoft                              | 1         | 1.19%   |
| Logitech                               | 1         | 1.19%   |
| Jieli Technology                       | 1         | 1.19%   |
| ARC International                      | 1         | 1.19%   |
| ALi                                    | 1         | 1.19%   |
| Alcor Micro                            | 1         | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                             | 4         | 4.76%   |
| Apple FaceTime HD Camera (Built-in)                                      | 4         | 4.76%   |
| Microdia Integrated_Webcam_HD                                            | 3         | 3.57%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 3         | 3.57%   |
| IMC Networks Integrated Camera                                           | 3         | 3.57%   |
| Acer Lenovo EasyCamera                                                   | 3         | 3.57%   |
| Acer Integrated Camera                                                   | 3         | 3.57%   |
| Sunplus Integrated_Webcam_HD                                             | 2         | 2.38%   |
| Quanta HD User Facing                                                    | 2         | 2.38%   |
| Generalplus GENERAL WEBCAM                                               | 2         | 2.38%   |
| Chicony TOSHIBA Web Camera - HD                                          | 2         | 2.38%   |
| Chicony HP Truevision HD                                                 | 2         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 2         | 2.38%   |
| Teslong Camera Teslong Camera                                            | 1         | 1.19%   |
| Syntek USB Camera Device                                                 | 1         | 1.19%   |
| Syntek Integrated Camera                                                 | 1         | 1.19%   |
| Suyin HP Truevision HD                                                   | 1         | 1.19%   |
| Suyin HD Video WebCam                                                    | 1         | 1.19%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 1.19%   |
| Sunplus Integrated Webcam                                                | 1         | 1.19%   |
| Sunplus HD WebCam                                                        | 1         | 1.19%   |
| Sunplus HD User Facing                                                   | 1         | 1.19%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 1         | 1.19%   |
| Ricoh Visual Communication Camera VGP-VCC9 [R5U870]                      | 1         | 1.19%   |
| Realtek USB Camera                                                       | 1         | 1.19%   |
| Realtek Lenovo EasyCamera                                                | 1         | 1.19%   |
| Realtek Integrated Webcam                                                | 1         | 1.19%   |
| Realtek HD WebCam                                                        | 1         | 1.19%   |
| Razer USA Razer Kiyo                                                     | 1         | 1.19%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                     | 1         | 1.19%   |
| Microsoft Microsoft?‚ LifeCam Cinema                                     | 1         | 1.19%   |
| Microdia Webcam Vitade AF                                                | 1         | 1.19%   |
| Microdia PC Camera (SN9C110)                                             | 1         | 1.19%   |
| Microdia Lenovo EasyCamera                                               | 1         | 1.19%   |
| Microdia Integrated Webcam                                               | 1         | 1.19%   |
| Microdia Integrated HD Webcam                                            | 1         | 1.19%   |
| Logitech HD Pro Webcam C920                                              | 1         | 1.19%   |
| Lite-On HP HD Webcam                                                     | 1         | 1.19%   |
| Lite-On HP HD Camera                                                     | 1         | 1.19%   |
| Lite-On HP 2.0MP High Definition Webcam                                  | 1         | 1.19%   |
| Jieli USB PHY 2.0                                                        | 1         | 1.19%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 1.19%   |
| IMC Networks USB Camera                                                  | 1         | 1.19%   |
| IMC Networks Lenovo EasyCamera                                           | 1         | 1.19%   |
| IMC Networks EasyCamera                                                  | 1         | 1.19%   |
| Chicony WebCam                                                           | 1         | 1.19%   |
| Chicony VGA Webcam                                                       | 1         | 1.19%   |
| Chicony LG HD WebCam                                                     | 1         | 1.19%   |
| Chicony Integrated Camera                                                | 1         | 1.19%   |
| Chicony HP Wide Vision HD Camera                                         | 1         | 1.19%   |
| Chicony HD WebCam (Acer)                                                 | 1         | 1.19%   |
| Chicony HD WebCam                                                        | 1         | 1.19%   |
| Chicony FJ Camera                                                        | 1         | 1.19%   |
| Chicony EasyCamera                                                       | 1         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) USB HD webcam                     | 1         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 1         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.19%   |
| ARC International Camera                                                 | 1         | 1.19%   |
| ALi Gateway Webcam                                                       | 1         | 1.19%   |
| Alcor Micro Asus Integrated Webcam                                       | 1         | 1.19%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 43.75%  |
| Shenzhen Goodix Technology | 5         | 31.25%  |
| LighTuning Technology      | 2         | 12.5%   |
| Upek                       | 1         | 6.25%   |
| Focal-systems.Corp         | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 18.75%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 12.5%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 12.5%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 6.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 6.25%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 6.25%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 6.25%   |
| LighTuning Fingerprint Reader                                              | 1         | 6.25%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 6.25%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 110       | 74.83%  |
| 1     | 29        | 19.73%  |
| 2     | 8         | 5.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 35.56%  |
| Net/wireless             | 11        | 24.44%  |
| Graphics card            | 6         | 13.33%  |
| Bluetooth                | 3         | 6.67%   |
| Multimedia controller    | 2         | 4.44%   |
| Chipcard                 | 2         | 4.44%   |
| Net/ethernet             | 1         | 2.22%   |
| Flash memory             | 1         | 2.22%   |
| Dvb card                 | 1         | 2.22%   |
| Communication controller | 1         | 2.22%   |
| Camera                   | 1         | 2.22%   |

