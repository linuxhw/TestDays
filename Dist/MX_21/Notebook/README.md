MX 21 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 119

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 250 G6 Notebook PC          | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| Dell          | Inspiron 5521               | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| Apple         | MacBookAir7,2               | [d562164e67](https://linux-hardware.org/?probe=d562164e67) | Sep 12, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| Unknown       | Unknown                     | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| Unknown       | Unknown                     | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Dell          | System XPS 15Z              | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Dell          | Vostro 3550                 | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| Dell          | Latitude 3190               | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| Dell          | Latitude 3190               | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Alienware     | 13 R2                       | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| Dell          | Latitude 3190               | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| Dell          | Latitude 3190               | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Dell          | Latitude D520               | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| Sony          | VPCSB1V9R                   | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| Acer          | Aspire A515-56              | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Acer          | Nitro AN515-55              | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| HP            | ProBook 450 G4              | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | G5 KC                       | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | 1101HA                      | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| TUXEDO        | N7x0WU                      | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Sony          | SVE1513Q1ESI                | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| ASUSTek       | E402MA                      | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.0-9-amd64             | 14        | 15.38%  |
| 5.10.0-13-amd64            | 13        | 14.29%  |
| 5.10.0-16-amd64            | 9         | 9.89%   |
| 5.14.0-4mx-amd64           | 8         | 8.79%   |
| 5.10.0-14-amd64            | 6         | 6.59%   |
| 5.10.0-11-amd64            | 6         | 6.59%   |
| 5.16.0-5mx-amd64           | 4         | 4.4%    |
| 5.10.0-18-amd64            | 3         | 3.3%    |
| 5.10.0-17-amd64            | 3         | 3.3%    |
| 5.16.0-6mx-amd64           | 2         | 2.2%    |
| 5.10.0-8-amd64             | 2         | 2.2%    |
| 5.10.0-15-amd64            | 2         | 2.2%    |
| 5.10.0-13-686-pae          | 2         | 2.2%    |
| 5.10.0-11-686-pae          | 2         | 2.2%    |
| 5.10.0-10-amd64            | 2         | 2.2%    |
| 5.19.0-12.1-liquorix-amd64 | 1         | 1.1%    |
| 5.18.0-4mx-amd64           | 1         | 1.1%    |
| 5.18.0-3-amd64             | 1         | 1.1%    |
| 5.17.0-5.2-liquorix-amd64  | 1         | 1.1%    |
| 5.17.0-3mx-amd64           | 1         | 1.1%    |
| 5.17.0-2mx-amd64           | 1         | 1.1%    |
| 5.17.0-1-amd64             | 1         | 1.1%    |
| 5.16.0-4mx-amd64           | 1         | 1.1%    |
| 5.16.0-18.1-liquorix-amd64 | 1         | 1.1%    |
| 5.15.0-3mx-amd64           | 1         | 1.1%    |
| 5.10.0-5mx-amd64           | 1         | 1.1%    |
| 5.10.0-12-amd64            | 1         | 1.1%    |
| 5.10.0-11-686              | 1         | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 63        | 72.41%  |
| 5.16.0  | 8         | 9.2%    |
| 5.14.0  | 8         | 9.2%    |
| 5.17.0  | 4         | 4.6%    |
| 5.18.0  | 2         | 2.3%    |
| 5.19.0  | 1         | 1.15%   |
| 5.15.0  | 1         | 1.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 63        | 72.41%  |
| 5.16    | 8         | 9.2%    |
| 5.14    | 8         | 9.2%    |
| 5.17    | 4         | 4.6%    |
| 5.18    | 2         | 2.3%    |
| 5.19    | 1         | 1.15%   |
| 5.15    | 1         | 1.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 79        | 95.18%  |
| i686   | 4         | 4.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 55        | 66.27%  |
| KDE5          | 19        | 22.89%  |
| GNOME         | 2         | 2.41%   |
| Budgie        | 2         | 2.41%   |
| Unknown       | 2         | 2.41%   |
| LXQt          | 1         | 1.2%    |
| i3            | 1         | 1.2%    |
| GNOME Classic | 1         | 1.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 81        | 97.59%  |
| Tty  | 2         | 2.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 64        | 77.11%  |
| SDDM    | 18        | 21.69%  |
| Unknown | 1         | 1.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 43        | 51.19%  |
| de_DE   | 13        | 15.48%  |
| it_IT   | 4         | 4.76%   |
| ru_RU   | 3         | 3.57%   |
| Unknown | 3         | 3.57%   |
| pt_BR   | 2         | 2.38%   |
| fr_FR   | 2         | 2.38%   |
| es_ES   | 2         | 2.38%   |
| en_NZ   | 2         | 2.38%   |
| en_GB   | 2         | 2.38%   |
| tr_TR   | 1         | 1.19%   |
| sk_SK   | 1         | 1.19%   |
| nb_NO   | 1         | 1.19%   |
| id_ID   | 1         | 1.19%   |
| fi_FI   | 1         | 1.19%   |
| es_PE   | 1         | 1.19%   |
| en_AU   | 1         | 1.19%   |
| de_CH   | 1         | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 59        | 71.08%  |
| BIOS | 24        | 28.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 69        | 83.13%  |
| Overlay | 11        | 13.25%  |
| Btrfs   | 2         | 2.41%   |
| F2fs    | 1         | 1.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 61        | 73.49%  |
| MBR     | 21        | 25.3%   |
| Unknown | 1         | 1.2%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 73.81%  |
| Yes       | 22        | 26.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 51.19%  |
| No        | 41        | 48.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 18        | 21.69%  |
| Hewlett-Packard     | 10        | 12.05%  |
| Dell                | 10        | 12.05%  |
| ASUSTek Computer    | 9         | 10.84%  |
| Acer                | 6         | 7.23%   |
| Sony                | 5         | 6.02%   |
| Samsung Electronics | 3         | 3.61%   |
| MSI                 | 3         | 3.61%   |
| Apple               | 3         | 3.61%   |
| Alienware           | 3         | 3.61%   |
| Gigabyte Technology | 2         | 2.41%   |
| Fujitsu Siemens     | 2         | 2.41%   |
| Unknown             | 2         | 2.41%   |
| TUXEDO              | 1         | 1.2%    |
| Toshiba             | 1         | 1.2%    |
| Notebook            | 1         | 1.2%    |
| Medion              | 1         | 1.2%    |
| Framework           | 1         | 1.2%    |
| efirstview          | 1         | 1.2%    |
| Chuwi               | 1         | 1.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 3         | 3.61%   |
| TUXEDO N7x0WU                          | 1         | 1.2%    |
| Toshiba Satellite C845                 | 1         | 1.2%    |
| Sony VPCSB1V9R                         | 1         | 1.2%    |
| Sony VPCF119FX                         | 1         | 1.2%    |
| Sony VPCEH2N1E                         | 1         | 1.2%    |
| Sony VPCEC3S1E                         | 1         | 1.2%    |
| Sony SVE1513Q1ESI                      | 1         | 1.2%    |
| Samsung NC210/NC110                    | 1         | 1.2%    |
| Samsung 350V5C/351V5C/3540VC/3440VC    | 1         | 1.2%    |
| Samsung 340XAA/350XAA/550XAA           | 1         | 1.2%    |
| Notebook PD5x_7xPNP_PNN_PNT            | 1         | 1.2%    |
| MSI Modern 14 B11MOL                   | 1         | 1.2%    |
| MSI GV62 8RD                           | 1         | 1.2%    |
| MSI Alpha 15 B5EEK                     | 1         | 1.2%    |
| Medion E14304                          | 1         | 1.2%    |
| Lenovo V15-IGL 82C3                    | 1         | 1.2%    |
| Lenovo ThinkPad W541 20EG0005MS        | 1         | 1.2%    |
| Lenovo ThinkPad T560 20FJS0EP00        | 1         | 1.2%    |
| Lenovo ThinkPad T500 2241VL9           | 1         | 1.2%    |
| Lenovo ThinkPad T480 20L50004MZ        | 1         | 1.2%    |
| Lenovo ThinkPad T440p 20AW002VBR       | 1         | 1.2%    |
| Lenovo ThinkPad T430 23427YU           | 1         | 1.2%    |
| Lenovo ThinkPad T14s Gen 2i 20WM00A8GE | 1         | 1.2%    |
| Lenovo ThinkPad L512 44444WG           | 1         | 1.2%    |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS   | 1         | 1.2%    |
| Lenovo ThinkBook 13s-IWL 20R9          | 1         | 1.2%    |
| Lenovo S130-11IGM 81J1                 | 1         | 1.2%    |
| Lenovo Legion 5 15ACH6H 82JU           | 1         | 1.2%    |
| Lenovo IdeaPad Y700-15ISK 80NV         | 1         | 1.2%    |
| Lenovo IdeaPad 3 15IIL05 81WE          | 1         | 1.2%    |
| Lenovo G400s VILG1                     | 1         | 1.2%    |
| Lenovo B590 20208                      | 1         | 1.2%    |
| HP Stream Laptop 14-cb0XX              | 1         | 1.2%    |
| HP ProBook 450 G4                      | 1         | 1.2%    |
| HP ProBook 450 G1                      | 1         | 1.2%    |
| HP Pavilion g7                         | 1         | 1.2%    |
| HP Laptop 15-ef2xxx                    | 1         | 1.2%    |
| HP EliteBook 850 G3                    | 1         | 1.2%    |
| HP EliteBook 8440p                     | 1         | 1.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 9         | 10.84%  |
| HP EliteBook      | 3         | 3.61%   |
| Dell Latitude     | 3         | 3.61%   |
| Unknown           | 3         | 3.61%   |
| Lenovo IdeaPad    | 2         | 2.41%   |
| HP ProBook        | 2         | 2.41%   |
| Dell Precision    | 2         | 2.41%   |
| Dell Inspiron     | 2         | 2.41%   |
| ASUS ROG          | 2         | 2.41%   |
| Alienware m15     | 2         | 2.41%   |
| Acer Nitro        | 2         | 2.41%   |
| Acer Aspire       | 2         | 2.41%   |
| TUXEDO N7x0WU     | 1         | 1.2%    |
| Toshiba Satellite | 1         | 1.2%    |
| Sony VPCSB1V9R    | 1         | 1.2%    |
| Sony VPCF119FX    | 1         | 1.2%    |
| Sony VPCEH2N1E    | 1         | 1.2%    |
| Sony VPCEC3S1E    | 1         | 1.2%    |
| Sony SVE1513Q1ESI | 1         | 1.2%    |
| Samsung NC210     | 1         | 1.2%    |
| Samsung 350V5C    | 1         | 1.2%    |
| Samsung 340XAA    | 1         | 1.2%    |
| Notebook PD5x     | 1         | 1.2%    |
| MSI Modern        | 1         | 1.2%    |
| MSI GV62          | 1         | 1.2%    |
| MSI Alpha         | 1         | 1.2%    |
| Medion E14304     | 1         | 1.2%    |
| Lenovo V15-IGL    | 1         | 1.2%    |
| Lenovo ThinkBook  | 1         | 1.2%    |
| Lenovo S130-11IGM | 1         | 1.2%    |
| Lenovo Legion     | 1         | 1.2%    |
| Lenovo G400s      | 1         | 1.2%    |
| Lenovo B590       | 1         | 1.2%    |
| HP Stream         | 1         | 1.2%    |
| HP Pavilion       | 1         | 1.2%    |
| HP Laptop         | 1         | 1.2%    |
| HP Compaq         | 1         | 1.2%    |
| HP 250            | 1         | 1.2%    |
| Gigabyte P15FV5   | 1         | 1.2%    |
| Gigabyte G5       | 1         | 1.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 16        | 19.28%  |
| 2015    | 8         | 9.64%   |
| 2011    | 7         | 8.43%   |
| 2020    | 5         | 6.02%   |
| 2018    | 5         | 6.02%   |
| 2016    | 5         | 6.02%   |
| 2013    | 5         | 6.02%   |
| 2012    | 5         | 6.02%   |
| 2010    | 5         | 6.02%   |
| 2019    | 4         | 4.82%   |
| 2017    | 4         | 4.82%   |
| 2022    | 3         | 3.61%   |
| 2008    | 3         | 3.61%   |
| 2014    | 2         | 2.41%   |
| 2007    | 2         | 2.41%   |
| 2009    | 1         | 1.2%    |
| 2006    | 1         | 1.2%    |
| 2005    | 1         | 1.2%    |
| Unknown | 1         | 1.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 83        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 82        | 98.8%   |
| Enabled  | 1         | 1.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 27        | 32.53%  |
| 16.01-24.0  | 18        | 21.69%  |
| 3.01-4.0    | 12        | 14.46%  |
| 8.01-16.0   | 12        | 14.46%  |
| 32.01-64.0  | 4         | 4.82%   |
| 2.01-3.0    | 3         | 3.61%   |
| 1.01-2.0    | 3         | 3.61%   |
| 64.01-256.0 | 2         | 2.41%   |
| 24.01-32.0  | 1         | 1.2%    |
| 0.51-1.0    | 1         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 32        | 35.96%  |
| 2.01-3.0  | 24        | 26.97%  |
| 3.01-4.0  | 14        | 15.73%  |
| 4.01-8.0  | 10        | 11.24%  |
| 0.51-1.0  | 6         | 6.74%   |
| 8.01-16.0 | 2         | 2.25%   |
| 0.01-0.5  | 1         | 1.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 55        | 65.48%  |
| 2      | 20        | 23.81%  |
| 3      | 7         | 8.33%   |
| 4      | 1         | 1.19%   |
| 0      | 1         | 1.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 68.67%  |
| Yes       | 26        | 31.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 78.31%  |
| No        | 18        | 21.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 95.18%  |
| No        | 4         | 4.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 80.72%  |
| No        | 16        | 19.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 20        | 23.81%  |
| Germany     | 13        | 15.48%  |
| Italy       | 7         | 8.33%   |
| Canada      | 6         | 7.14%   |
| Brazil      | 4         | 4.76%   |
| Spain       | 2         | 2.38%   |
| Serbia      | 2         | 2.38%   |
| Russia      | 2         | 2.38%   |
| New Zealand | 2         | 2.38%   |
| Netherlands | 2         | 2.38%   |
| France      | 2         | 2.38%   |
| Belgium     | 2         | 2.38%   |
| Austria     | 2         | 2.38%   |
| UK          | 1         | 1.19%   |
| Turkey      | 1         | 1.19%   |
| Switzerland | 1         | 1.19%   |
| Slovakia    | 1         | 1.19%   |
| Romania     | 1         | 1.19%   |
| Poland      | 1         | 1.19%   |
| Peru        | 1         | 1.19%   |
| Norway      | 1         | 1.19%   |
| Malaysia    | 1         | 1.19%   |
| Indonesia   | 1         | 1.19%   |
| India       | 1         | 1.19%   |
| Ghana       | 1         | 1.19%   |
| Finland     | 1         | 1.19%   |
| Egypt       | 1         | 1.19%   |
| Czechia     | 1         | 1.19%   |
| Belarus     | 1         | 1.19%   |
| Azerbaijan  | 1         | 1.19%   |
| Australia   | 1         | 1.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Vienna                    | 2         | 2.3%    |
| Orange                    | 2         | 2.3%    |
| Montreal                  | 2         | 2.3%    |
| Doesburg                  | 2         | 2.3%    |
| Cambridge                 | 2         | 2.3%    |
| Zurich                    | 1         | 1.15%   |
| Waycross                  | 1         | 1.15%   |
| Warsaw                    | 1         | 1.15%   |
| Vasco da Gama             | 1         | 1.15%   |
| Vancouver                 | 1         | 1.15%   |
| Uelzen                    | 1         | 1.15%   |
| Tucson                    | 1         | 1.15%   |
| Taggia                    | 1         | 1.15%   |
| Tacoma                    | 1         | 1.15%   |
| Sydney                    | 1         | 1.15%   |
| Surprise                  | 1         | 1.15%   |
| Stadtilm                  | 1         | 1.15%   |
| St Petersburg             | 1         | 1.15%   |
| Soest                     | 1         | 1.15%   |
| Schaarbeek                | 1         | 1.15%   |
| Saskatoon                 | 1         | 1.15%   |
| Saarlouis                 | 1         | 1.15%   |
| Roseville                 | 1         | 1.15%   |
| Rome                      | 1         | 1.15%   |
| Rochester                 | 1         | 1.15%   |
| Reinbek                   | 1         | 1.15%   |
| Raleigh                   | 1         | 1.15%   |
| Prague                    | 1         | 1.15%   |
| Powder Springs            | 1         | 1.15%   |
| Postbauer-Heng            | 1         | 1.15%   |
| Portland                  | 1         | 1.15%   |
| Ottawa                    | 1         | 1.15%   |
| Oslo                      | 1         | 1.15%   |
| Osasco                    | 1         | 1.15%   |
| Obourg                    | 1         | 1.15%   |
| Neumarkt in der Oberpfalz | 1         | 1.15%   |
| Munich                    | 1         | 1.15%   |
| Moscow                    | 1         | 1.15%   |
| Montebelluna              | 1         | 1.15%   |
| Minsk                     | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 19     | 14.91%  |
| WDC                 | 14        | 14     | 12.28%  |
| Seagate             | 14        | 15     | 12.28%  |
| Crucial             | 10        | 18     | 8.77%   |
| Kingston            | 8         | 8      | 7.02%   |
| Unknown             | 7         | 8      | 6.14%   |
| SK hynix            | 6         | 7      | 5.26%   |
| Intel               | 5         | 5      | 4.39%   |
| Transcend           | 3         | 3      | 2.63%   |
| Toshiba             | 3         | 3      | 2.63%   |
| SanDisk             | 3         | 4      | 2.63%   |
| LITEON              | 3         | 3      | 2.63%   |
| Dogfish             | 3         | 3      | 2.63%   |
| Netac               | 2         | 2      | 1.75%   |
| Apple               | 2         | 4      | 1.75%   |
| Team                | 1         | 1      | 0.88%   |
| SPCC                | 1         | 1      | 0.88%   |
| SABRENT             | 1         | 1      | 0.88%   |
| PNY                 | 1         | 1      | 0.88%   |
| Phison              | 1         | 1      | 0.88%   |
| OCZ                 | 1         | 1      | 0.88%   |
| Micron Technology   | 1         | 1      | 0.88%   |
| KIOXIA              | 1         | 1      | 0.88%   |
| Indilinx            | 1         | 1      | 0.88%   |
| Hitachi             | 1         | 1      | 0.88%   |
| Gigabyte Technology | 1         | 1      | 0.88%   |
| GeIL                | 1         | 1      | 0.88%   |
| Fujitsu             | 1         | 1      | 0.88%   |
| Unknown             | 1         | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD           | 3         | 2.54%   |
| Unknown SD32G  32GB                       | 2         | 1.69%   |
| SK hynix HFM512GDJTNI-82A0A 512GB         | 2         | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 1.69%   |
| Samsung SSD 980 PRO 1TB                   | 2         | 1.69%   |
| Samsung SSD 860 EVO 500GB                 | 2         | 1.69%   |
| Kingston OM8PCP3512F-AI1 512GB            | 2         | 1.69%   |
| Dogfish SSD 128GB                         | 2         | 1.69%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 1.69%   |
| Crucial CT240BX500SSD1 240GB              | 2         | 1.69%   |
| Crucial CT120BX500SSD1 120GB              | 2         | 1.69%   |
| WDC WDS500G2B0B-00YS70 500GB SSD          | 1         | 0.85%   |
| WDC WDS100T1X0E-00AFY0 1TB                | 1         | 0.85%   |
| WDC WD5000LPVX-22V0TT0 500GB              | 1         | 0.85%   |
| WDC WD5000LPVX-08V0TT5 500GB              | 1         | 0.85%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 0.85%   |
| WDC WD5000LPCX-22VHAT0 500GB              | 1         | 0.85%   |
| WDC WD3200BEVT-22ZCT0 320GB               | 1         | 0.85%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 0.85%   |
| WDC WD1600BEVT-60ZCT1 160GB               | 1         | 0.85%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.85%   |
| WDC PC SN730 NVMe 1024GB                  | 1         | 0.85%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB        | 1         | 0.85%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 0.85%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB      | 1         | 0.85%   |
| Unknown SDW32G  32GB                      | 1         | 0.85%   |
| Unknown SD08G  8GB                        | 1         | 0.85%   |
| Unknown ISOCOM  64GB                      | 1         | 0.85%   |
| Unknown ED2S5  128GB                      | 1         | 0.85%   |
| Unknown DA4064  64GB                      | 1         | 0.85%   |
| Unknown BJTD4R  32GB                      | 1         | 0.85%   |
| Transcend TS256GSSD370S 256GB             | 1         | 0.85%   |
| Transcend TS1GSDOM22V 1GB SSD             | 1         | 0.85%   |
| Transcend TS128GMTS800 128GB SSD          | 1         | 0.85%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 0.85%   |
| Toshiba KXG50ZNV256G NVMe 256GB           | 1         | 0.85%   |
| Toshiba KBG40ZNT256G MEMORY 256GB         | 1         | 0.85%   |
| Team TM8FP6256G 256GB                     | 1         | 0.85%   |
| SPCC Solid State Disk 128GB               | 1         | 0.85%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 15     | 53.85%  |
| WDC                 | 8         | 8      | 30.77%  |
| Toshiba             | 1         | 1      | 3.85%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Hitachi             | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 19.57%  |
| Crucial             | 9         | 16     | 19.57%  |
| Kingston            | 4         | 4      | 8.7%    |
| Transcend           | 3         | 3      | 6.52%   |
| SanDisk             | 3         | 4      | 6.52%   |
| LITEON              | 3         | 3      | 6.52%   |
| Dogfish             | 3         | 3      | 6.52%   |
| Netac               | 2         | 2      | 4.35%   |
| Apple               | 2         | 4      | 4.35%   |
| WDC                 | 1         | 1      | 2.17%   |
| SPCC                | 1         | 1      | 2.17%   |
| PNY                 | 1         | 1      | 2.17%   |
| OCZ                 | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| Indilinx            | 1         | 1      | 2.17%   |
| Gigabyte Technology | 1         | 1      | 2.17%   |
| GeIL                | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 38        | 57     | 37.62%  |
| NVMe | 29        | 37     | 28.71%  |
| HDD  | 26        | 27     | 25.74%  |
| MMC  | 8         | 9      | 7.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 84     | 59.57%  |
| NVMe | 29        | 36     | 30.85%  |
| MMC  | 8         | 9      | 8.51%   |
| SAS  | 1         | 1      | 1.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 58     | 71.43%  |
| 0.51-1.0   | 16        | 24     | 25.4%   |
| 1.01-2.0   | 2         | 2      | 3.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 27.91%  |
| 251-500        | 19        | 22.09%  |
| 501-1000       | 14        | 16.28%  |
| 21-50          | 9         | 10.47%  |
| 1-20           | 6         | 6.98%   |
| 51-100         | 6         | 6.98%   |
| 1001-2000      | 4         | 4.65%   |
| More than 3000 | 2         | 2.33%   |
| 2001-3000      | 2         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 37        | 42.05%  |
| 21-50          | 16        | 18.18%  |
| 251-500        | 11        | 12.5%   |
| 101-250        | 9         | 10.23%  |
| 51-100         | 9         | 10.23%  |
| 501-1000       | 3         | 3.41%   |
| 1001-2000      | 2         | 2.27%   |
| More than 3000 | 1         | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 11.11%  |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 11.11%  |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 11.11%  |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 11.11%  |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 11.11%  |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 11.11%  |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 1      | 11.11%  |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 44.44%  |
| WDC                 | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Indilinx            | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 57.14%  |
| WDC     | 2         | 2      | 28.57%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 77.78%  |
| SSD  | 2         | 2      | 22.22%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 71        | 110    | 78.89%  |
| Detected | 10        | 11     | 11.11%  |
| Malfunc  | 9         | 9      | 10%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 61        | 61.62%  |
| Samsung Electronics          | 10        | 10.1%   |
| SK hynix                     | 6         | 6.06%   |
| SanDisk                      | 5         | 5.05%   |
| Kingston Technology Company  | 4         | 4.04%   |
| AMD                          | 3         | 3.03%   |
| Phison Electronics           | 2         | 2.02%   |
| Nvidia                       | 2         | 2.02%   |
| KIOXIA                       | 2         | 2.02%   |
| Toshiba America Info Systems | 1         | 1.01%   |
| Silicon Image                | 1         | 1.01%   |
| Micron/Crucial Technology    | 1         | 1.01%   |
| Micron Technology            | 1         | 1.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 9.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 6.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 3.77%   |
| SK hynix BC511                                                                   | 3         | 2.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 2.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.83%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 2.83%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 1.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.89%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.89%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 1.89%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.89%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.89%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.94%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.94%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.94%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.94%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1         | 0.94%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.94%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.94%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.94%   |
| Samsung Electronics SATA controller                                              | 1         | 0.94%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.94%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.94%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.94%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.94%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.94%   |
| Nvidia MCP67 IDE Controller                                                      | 1         | 0.94%   |
| Nvidia MCP67 AHCI Controller                                                     | 1         | 0.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 56        | 57.73%  |
| NVMe | 29        | 29.9%   |
| IDE  | 8         | 8.25%   |
| RAID | 4         | 4.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 71        | 85.54%  |
| AMD    | 12        | 14.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz        | 3         | 3.61%   |
| AMD Ryzen 7 5800H with Radeon Graphics   | 3         | 3.61%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 2         | 2.41%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 2         | 2.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 2         | 2.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 2.41%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 2         | 2.41%   |
| Intel Celeron CPU N3060 @ 1.60GHz        | 2         | 2.41%   |
| Intel 12th Gen Core i7-12700H            | 2         | 2.41%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 2         | 2.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 2.41%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 1.2%    |
| Intel Pentium M processor 1.80GHz        | 1         | 1.2%    |
| Intel Genuine CPU T2300 @ 1.66GHz        | 1         | 1.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz        | 1         | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz        | 1         | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz        | 1         | 1.2%    |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 1.2%    |
| Intel Core i7-6500U CPU @ 2.50GHz        | 1         | 1.2%    |
| Intel Core i7-4980HQ CPU @ 2.80GHz       | 1         | 1.2%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz       | 1         | 1.2%    |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 1.2%    |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 1         | 1.2%    |
| Intel Core i7-2640M CPU @ 2.80GHz        | 1         | 1.2%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz        | 1         | 1.2%    |
| Intel Core i7 CPU M 620 @ 2.67GHz        | 1         | 1.2%    |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 1.2%    |
| Intel Core i5-8300H CPU @ 2.30GHz        | 1         | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 1.2%    |
| Intel Core i5-5350U CPU @ 1.80GHz        | 1         | 1.2%    |
| Intel Core i5-4300M CPU @ 2.60GHz        | 1         | 1.2%    |
| Intel Core i5-3337U CPU @ 1.80GHz        | 1         | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz        | 1         | 1.2%    |
| Intel Core i5-2450M CPU @ 2.50GHz        | 1         | 1.2%    |
| Intel Core i5-2430M CPU @ 2.40GHz        | 1         | 1.2%    |
| Intel Core i5-2410M CPU @ 2.30GHz        | 1         | 1.2%    |
| Intel Core i5-10500H CPU @ 2.50GHz       | 1         | 1.2%    |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 1         | 1.2%    |
| Intel Core i5 CPU M 460 @ 2.53GHz        | 1         | 1.2%    |
| Intel Core i3-5005U CPU @ 2.00GHz        | 1         | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 21        | 25.3%   |
| Intel Core i5           | 17        | 20.48%  |
| Other                   | 8         | 9.64%   |
| Intel Core i3           | 8         | 9.64%   |
| Intel Celeron           | 8         | 9.64%   |
| AMD Ryzen 7             | 6         | 7.23%   |
| Intel Core 2 Duo        | 3         | 3.61%   |
| Intel Atom              | 3         | 3.61%   |
| AMD Ryzen 5             | 2         | 2.41%   |
| Intel Pentium Silver    | 1         | 1.2%    |
| Intel Pentium M         | 1         | 1.2%    |
| Intel Genuine           | 1         | 1.2%    |
| AMD Turion 64 X2 Mobile | 1         | 1.2%    |
| AMD Sempron             | 1         | 1.2%    |
| AMD Ryzen 9             | 1         | 1.2%    |
| AMD Ryzen 3             | 1         | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 39        | 46.99%  |
| 4      | 27        | 32.53%  |
| 8      | 7         | 8.43%   |
| 6      | 5         | 6.02%   |
| 1      | 3         | 3.61%   |
| 14     | 2         | 2.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 83        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 63        | 75.9%   |
| 1      | 20        | 24.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 80        | 96.39%  |
| 32-bit         | 3         | 3.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 8         | 9.41%   |
| Unknown    | 8         | 9.41%   |
| 0x306a9    | 5         | 5.88%   |
| 0x806c1    | 4         | 4.71%   |
| 0x506e3    | 4         | 4.71%   |
| 0x406e3    | 4         | 4.71%   |
| 0x0a50000c | 4         | 4.71%   |
| 0xa0652    | 3         | 3.53%   |
| 0x906ea    | 3         | 3.53%   |
| 0x806ea    | 3         | 3.53%   |
| 0x306c3    | 3         | 3.53%   |
| 0x20655    | 3         | 3.53%   |
| 0x906a3    | 2         | 2.35%   |
| 0x806e9    | 2         | 2.35%   |
| 0x706a8    | 2         | 2.35%   |
| 0x706a1    | 2         | 2.35%   |
| 0x406c4    | 2         | 2.35%   |
| 0x306d4    | 2         | 2.35%   |
| 0x30678    | 2         | 2.35%   |
| 0x08608103 | 2         | 2.35%   |
| 0x806eb    | 1         | 1.18%   |
| 0x806d1    | 1         | 1.18%   |
| 0x6fd      | 1         | 1.18%   |
| 0x6fb      | 1         | 1.18%   |
| 0x6e8      | 1         | 1.18%   |
| 0x6d6      | 1         | 1.18%   |
| 0x506c9    | 1         | 1.18%   |
| 0x40661    | 1         | 1.18%   |
| 0x106e5    | 1         | 1.18%   |
| 0x106ca    | 1         | 1.18%   |
| 0x106c2    | 1         | 1.18%   |
| 0x1067a    | 1         | 1.18%   |
| 0x0a50000b | 1         | 1.18%   |
| 0x08600106 | 1         | 1.18%   |
| 0x08108109 | 1         | 1.18%   |
| 0x08108102 | 1         | 1.18%   |
| 0x02000057 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 9         | 10.84%  |
| KabyLake         | 9         | 10.84%  |
| Skylake          | 8         | 9.64%   |
| IvyBridge        | 6         | 7.23%   |
| Zen 3            | 5         | 6.02%   |
| TigerLake        | 5         | 6.02%   |
| Westmere         | 4         | 4.82%   |
| Silvermont       | 4         | 4.82%   |
| Haswell          | 4         | 4.82%   |
| Goldmont plus    | 4         | 4.82%   |
| CometLake        | 3         | 3.61%   |
| Unknown          | 3         | 3.61%   |
| Zen+             | 2         | 2.41%   |
| P6               | 2         | 2.41%   |
| Icelake          | 2         | 2.41%   |
| Core             | 2         | 2.41%   |
| Broadwell        | 2         | 2.41%   |
| Bonnell          | 2         | 2.41%   |
| Zen 2            | 1         | 1.2%    |
| Penryn           | 1         | 1.2%    |
| Nehalem          | 1         | 1.2%    |
| K8 Hammer        | 1         | 1.2%    |
| K8 & K10 hybrid  | 1         | 1.2%    |
| Goldmont         | 1         | 1.2%    |
| Alderlake Hybrid | 1         | 1.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 67        | 60.91%  |
| Nvidia | 28        | 25.45%  |
| AMD    | 15        | 13.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 7.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 5.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 4.39%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 3.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.51%   |
| Intel HD Graphics 530                                                                    | 4         | 3.51%   |
| AMD Cezanne                                                                              | 4         | 3.51%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.75%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.75%   |
| Intel HD Graphics 620                                                                    | 2         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.75%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.75%   |
| AMD Lucienne                                                                             | 2         | 1.75%   |
| Nvidia TU117M                                                                            | 1         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.88%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.88%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.88%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.88%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.88%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.88%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.88%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.88%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.88%   |
| Nvidia GF108M [GeForce GT 550M]                                                          | 1         | 0.88%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 50.6%   |
| Intel + Nvidia | 20        | 24.1%   |
| 1 x AMD        | 7         | 8.43%   |
| 1 x Nvidia     | 5         | 6.02%   |
| Intel + AMD    | 4         | 4.82%   |
| AMD + Nvidia   | 3         | 3.61%   |
| 2 x Intel      | 1         | 1.2%    |
| 2 x AMD        | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 69        | 81.18%  |
| Proprietary | 12        | 14.12%  |
| Unknown     | 4         | 4.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 84.34%  |
| 0.01-0.5   | 6         | 7.23%   |
| 0.51-1.0   | 3         | 3.61%   |
| 1.01-2.0   | 2         | 2.41%   |
| 7.01-8.0   | 1         | 1.2%    |
| 3.01-4.0   | 1         | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 14        | 15.22%  |
| AU Optronics            | 14        | 15.22%  |
| Samsung Electronics     | 11        | 11.96%  |
| LG Display              | 11        | 11.96%  |
| BOE                     | 10        | 10.87%  |
| Sharp                   | 4         | 4.35%   |
| PANDA                   | 4         | 4.35%   |
| Lenovo                  | 3         | 3.26%   |
| Hewlett-Packard         | 3         | 3.26%   |
| Chi Mei Optoelectronics | 3         | 3.26%   |
| Apple                   | 3         | 3.26%   |
| Sony                    | 2         | 2.17%   |
| Ancor Communications    | 2         | 2.17%   |
| Sunplus                 | 1         | 1.09%   |
| Philips                 | 1         | 1.09%   |
| Panasonic               | 1         | 1.09%   |
| LTM                     | 1         | 1.09%   |
| InfoVision              | 1         | 1.09%   |
| Goldstar                | 1         | 1.09%   |
| Dell                    | 1         | 1.09%   |
| CPT                     | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 2.17%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 2.17%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 1.09%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 1.09%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 1.09%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 1.09%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.09%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 1.09%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 1.09%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 527x296mm 23.8-inch        | 1         | 1.09%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 1020x570mm 46.0-inch   | 1         | 1.09%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 1         | 1.09%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 1.09%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 1.09%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 1.09%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 1         | 1.09%   |
| LTM LCD_VGA LTM0659 1920x1080 886x498mm 40.0-inch                        | 1         | 1.09%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.09%   |
| LG Display LCD Monitor LGD06E2 1920x1080 344x194mm 15.5-inch             | 1         | 1.09%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch             | 1         | 1.09%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 1.09%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch             | 1         | 1.09%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD024D 1366x768 294x166mm 13.3-inch              | 1         | 1.09%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch                 | 1         | 1.09%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                 | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 44.19%  |
| 1366x768 (WXGA)    | 25        | 29.07%  |
| 3840x2160 (4K)     | 5         | 5.81%   |
| 1600x900 (HD+)     | 3         | 3.49%   |
| 1440x900 (WXGA+)   | 2         | 2.33%   |
| 1280x800 (WXGA)    | 2         | 2.33%   |
| 3840x2400          | 1         | 1.16%   |
| 2880x1800          | 1         | 1.16%   |
| 2560x1440 (QHD)    | 1         | 1.16%   |
| 2560x1080          | 1         | 1.16%   |
| 2256x1504          | 1         | 1.16%   |
| 2160x1440          | 1         | 1.16%   |
| 1920x1200 (WUXGA)  | 1         | 1.16%   |
| 1680x1050 (WSXGA+) | 1         | 1.16%   |
| 1400x1050          | 1         | 1.16%   |
| 1280x1024 (SXGA)   | 1         | 1.16%   |
| 1024x600           | 1         | 1.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 43        | 46.74%  |
| 13     | 10        | 10.87%  |
| 14     | 9         | 9.78%   |
| 17     | 7         | 7.61%   |
| 24     | 4         | 4.35%   |
| 11     | 4         | 4.35%   |
| 23     | 3         | 3.26%   |
| 19     | 3         | 3.26%   |
| 27     | 2         | 2.17%   |
| 84     | 1         | 1.09%   |
| 46     | 1         | 1.09%   |
| 40     | 1         | 1.09%   |
| 34     | 1         | 1.09%   |
| 25     | 1         | 1.09%   |
| 21     | 1         | 1.09%   |
| 10     | 1         | 1.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 60.44%  |
| 201-300     | 11        | 12.09%  |
| 351-400     | 10        | 10.99%  |
| 501-600     | 9         | 9.89%   |
| 401-500     | 2         | 2.2%    |
| 801-900     | 1         | 1.1%    |
| 701-800     | 1         | 1.1%    |
| 1501-2000   | 1         | 1.1%    |
| 1001-1500   | 1         | 1.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 68        | 80.95%  |
| 16/10 | 10        | 11.9%   |
| 5/4   | 2         | 2.38%   |
| 3/2   | 2         | 2.38%   |
| 4/3   | 1         | 1.19%   |
| 21/9  | 1         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 43        | 46.74%  |
| 81-90          | 17        | 18.48%  |
| 121-130        | 7         | 7.61%   |
| 201-250        | 6         | 6.52%   |
| 51-60          | 4         | 4.35%   |
| 151-200        | 4         | 4.35%   |
| 71-80          | 2         | 2.17%   |
| 301-350        | 2         | 2.17%   |
| 251-300        | 2         | 2.17%   |
| 501-1000       | 2         | 2.17%   |
| More than 1000 | 1         | 1.09%   |
| 351-500        | 1         | 1.09%   |
| 41-50          | 1         | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 38        | 43.18%  |
| 101-120       | 21        | 23.86%  |
| 51-100        | 19        | 21.59%  |
| 161-240       | 5         | 5.68%   |
| More than 240 | 4         | 4.55%   |
| 1-50          | 1         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 66        | 77.65%  |
| 2     | 12        | 14.12%  |
| 0     | 4         | 4.71%   |
| 3     | 3         | 3.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 45        | 34.35%  |
| Realtek Semiconductor    | 43        | 32.82%  |
| Qualcomm Atheros         | 19        | 14.5%   |
| Broadcom                 | 5         | 3.82%   |
| Marvell Technology Group | 4         | 3.05%   |
| MediaTek                 | 3         | 2.29%   |
| TP-Link                  | 2         | 1.53%   |
| Nvidia                   | 2         | 1.53%   |
| Broadcom Limited         | 2         | 1.53%   |
| Sierra Wireless          | 1         | 0.76%   |
| Samsung Electronics      | 1         | 0.76%   |
| Ralink Technology        | 1         | 0.76%   |
| Lenovo                   | 1         | 0.76%   |
| Dell                     | 1         | 0.76%   |
| ASUSTek Computer         | 1         | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 30        | 19.35%  |
| Intel Wi-Fi 6 AX200                                                     | 7         | 4.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.23%   |
| Intel Wireless 8265 / 8275                                              | 4         | 2.58%   |
| Intel Wireless 8260                                                     | 4         | 2.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.94%   |
| Intel Wireless 7260                                                     | 3         | 1.94%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.29%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.29%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.29%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.29%   |
| Intel Ethernet Connection I219-V                                        | 2         | 1.29%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 1.29%   |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 1.29%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.29%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.29%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.29%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.65%   |
| Sierra Wireless EM7455                                                  | 1         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.65%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.65%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 0.65%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.65%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 44        | 51.76%  |
| Realtek Semiconductor | 14        | 16.47%  |
| Qualcomm Atheros      | 14        | 16.47%  |
| Broadcom              | 4         | 4.71%   |
| MediaTek              | 3         | 3.53%   |
| Broadcom Limited      | 2         | 2.35%   |
| TP-Link               | 1         | 1.18%   |
| Sierra Wireless       | 1         | 1.18%   |
| Ralink Technology     | 1         | 1.18%   |
| ASUSTek Computer      | 1         | 1.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 7         | 8.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 5.88%   |
| Intel Wireless 8265 / 8275                                              | 4         | 4.71%   |
| Intel Wireless 8260                                                     | 4         | 4.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 3.53%   |
| Intel Wireless 7260                                                     | 3         | 3.53%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 3.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.35%   |
| Realtek 802.11ac NIC                                                    | 2         | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 2.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 2.35%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 2.35%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.18%   |
| Sierra Wireless EM7455                                                  | 1         | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 1.18%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 1.18%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.18%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.18%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.18%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.18%   |
| Intel Wireless 7265                                                     | 1         | 1.18%   |
| Intel Wireless 3165                                                     | 1         | 1.18%   |
| Intel Wireless 3160                                                     | 1         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.18%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.18%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.18%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.18%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.18%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.18%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 55.22%  |
| Intel                    | 13        | 19.4%   |
| Qualcomm Atheros         | 7         | 10.45%  |
| Marvell Technology Group | 4         | 5.97%   |
| Nvidia                   | 2         | 2.99%   |
| TP-Link                  | 1         | 1.49%   |
| Samsung Electronics      | 1         | 1.49%   |
| Lenovo                   | 1         | 1.49%   |
| Broadcom                 | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30        | 43.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 7.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 2.9%    |
| Intel Ethernet Connection I219-V                                               | 2         | 2.9%    |
| Intel Ethernet Connection I217-LM                                              | 2         | 2.9%    |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 2.9%    |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.9%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.45%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 1.45%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 1.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.45%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 1.45%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 1.45%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.45%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 1.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.45%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 1.45%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.45%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.45%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.45%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.45%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 1.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 54.48%  |
| Ethernet | 65        | 44.83%  |
| Modem    | 1         | 0.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 74.42%  |
| Ethernet | 22        | 25.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 60        | 72.29%  |
| 1     | 21        | 25.3%   |
| 0     | 2         | 2.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 62        | 73.81%  |
| Yes  | 22        | 26.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 50%     |
| Qualcomm Atheros Communications | 7         | 10.29%  |
| Realtek Semiconductor           | 6         | 8.82%   |
| Broadcom                        | 5         | 7.35%   |
| IMC Networks                    | 3         | 4.41%   |
| Foxconn / Hon Hai               | 3         | 4.41%   |
| Cambridge Silicon Radio         | 3         | 4.41%   |
| Apple                           | 3         | 4.41%   |
| Lite-On Technology              | 1         | 1.47%   |
| Hewlett-Packard                 | 1         | 1.47%   |
| Dell                            | 1         | 1.47%   |
| ASUSTek Computer                | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 13        | 19.12%  |
| Intel AX200 Bluetooth                                                               | 7         | 10.29%  |
| Intel AX201 Bluetooth                                                               | 6         | 8.82%   |
| Realtek Bluetooth Radio                                                             | 5         | 7.35%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 5.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 4.41%   |
| IMC Networks Wireless_Device                                                        | 2         | 2.94%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.47%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.47%   |
| Lite-On Wireless_Device                                                             | 1         | 1.47%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.47%   |
| Intel Bluetooth Device                                                              | 1         | 1.47%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.47%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.47%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.47%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.47%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.47%   |
| Broadcom HP Portable Valentine                                                      | 1         | 1.47%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.47%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.47%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.47%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.47%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 1.47%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.47%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.47%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 70        | 63.64%  |
| Nvidia                | 22        | 20%     |
| AMD                   | 11        | 10%     |
| Texas Instruments     | 1         | 0.91%   |
| Realtek Semiconductor | 1         | 0.91%   |
| Plantronics           | 1         | 0.91%   |
| Logitech              | 1         | 0.91%   |
| Lenovo                | 1         | 0.91%   |
| FIFINE 683 Microphone | 1         | 0.91%   |
| C-Media Electronics   | 1         | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 8.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 8.06%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 7.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 5.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.03%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 3.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 3.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.42%   |
| Nvidia Audio device                                                                               | 3         | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.42%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.42%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.61%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.61%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.61%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.61%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.81%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.81%   |
| Plantronics BT600                                                                                 | 1         | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.81%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.81%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.81%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.81%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.81%   |
| Logitech Zone Wired                                                                               | 1         | 0.81%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 0.81%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 23        | 23.23%  |
| Samsung Electronics | 22        | 22.22%  |
| Unknown             | 13        | 13.13%  |
| Kingston            | 11        | 11.11%  |
| Micron Technology   | 8         | 8.08%   |
| Crucial             | 7         | 7.07%   |
| Unknown (ABCD)      | 2         | 2.02%   |
| Smart               | 2         | 2.02%   |
| Corsair             | 2         | 2.02%   |
| Transcend           | 1         | 1.01%   |
| Team                | 1         | 1.01%   |
| Ramaxel Technology  | 1         | 1.01%   |
| PNY                 | 1         | 1.01%   |
| Nanya Technology    | 1         | 1.01%   |
| Innodisk            | 1         | 1.01%   |
| Avant               | 1         | 1.01%   |
| 48spaces            | 1         | 1.01%   |
| Unknown             | 1         | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 3.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.75%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 1.83%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.83%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 1.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.83%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.83%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 1.83%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.83%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.83%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.92%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.92%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.92%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.92%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.92%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 0.92%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.92%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s               | 1         | 0.92%   |
| Team RAM Elite-1600 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.92%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.92%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.92%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.92%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.92%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.92%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.92%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.92%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.92%   |
| SK hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.92%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 0.92%   |
| SK hynix RAM HMT351S6AFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.92%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.92%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.92%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.92%   |
| SK hynix RAM HMCG66MEBSA095N 8GB SODIMM DDR5 4800MT/s            | 1         | 0.92%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.92%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.92%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.92%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 35        | 41.67%  |
| DDR3   | 34        | 40.48%  |
| LPDDR4 | 5         | 5.95%   |
| DDR2   | 5         | 5.95%   |
| DDR    | 2         | 2.38%   |
| SDRAM  | 1         | 1.19%   |
| DRAM   | 1         | 1.19%   |
| DDR5   | 1         | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 79        | 94.05%  |
| Row Of Chips | 5         | 5.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 39        | 41.49%  |
| 4096  | 30        | 31.91%  |
| 2048  | 14        | 14.89%  |
| 16384 | 5         | 5.32%   |
| 1024  | 4         | 4.26%   |
| 32768 | 2         | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 19        | 21.35%  |
| 3200    | 17        | 19.1%   |
| 2400    | 11        | 12.36%  |
| 2667    | 10        | 11.24%  |
| 1333    | 7         | 7.87%   |
| Unknown | 7         | 7.87%   |
| 667     | 5         | 5.62%   |
| 2133    | 4         | 4.49%   |
| 1334    | 3         | 3.37%   |
| 4267    | 2         | 2.25%   |
| 4800    | 1         | 1.12%   |
| 4199    | 1         | 1.12%   |
| 1067    | 1         | 1.12%   |
| 166     | 1         | 1.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 66.67%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 33.33%  |
| HP LaserJet 1022         | 1         | 33.33%  |
| Brother DCP-L2540DW      | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 16        | 24.24%  |
| Acer                                   | 8         | 12.12%  |
| Microdia                               | 7         | 10.61%  |
| Realtek Semiconductor                  | 6         | 9.09%   |
| Sunplus Innovation Technology          | 3         | 4.55%   |
| Quanta                                 | 3         | 4.55%   |
| Lite-On Technology                     | 3         | 4.55%   |
| IMC Networks                           | 3         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.55%   |
| Suyin                                  | 2         | 3.03%   |
| Silicon Motion                         | 2         | 3.03%   |
| Ricoh                                  | 2         | 3.03%   |
| Z-Star Microelectronics                | 1         | 1.52%   |
| Y Media                                | 1         | 1.52%   |
| Primax Electronics                     | 1         | 1.52%   |
| Luxvisions Innotech Limited            | 1         | 1.52%   |
| Logitech                               | 1         | 1.52%   |
| Lenovo                                 | 1         | 1.52%   |
| Goodong Industry                       | 1         | 1.52%   |
| Alcor Micro                            | 1         | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 3         | 4.55%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 3.03%   |
| Quanta HD User Facing                         | 2         | 3.03%   |
| Microdia Integrated_Webcam_HD                 | 2         | 3.03%   |
| Chicony HD User Facing                        | 2         | 3.03%   |
| Acer BisonCam,NB Pro                          | 2         | 3.03%   |
| Acer BisonCam, NB Pro                         | 2         | 3.03%   |
| Z-Star Venus USB2.0 Camera                    | 1         | 1.52%   |
| Y Media USB Camera                            | 1         | 1.52%   |
| Suyin Sony Visual Communication Camera        | 1         | 1.52%   |
| Suyin Acer CrystalEye Webcam                  | 1         | 1.52%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 1.52%   |
| Silicon Motion WebCam SCB-0385N               | 1         | 1.52%   |
| Silicon Motion Web Camera                     | 1         | 1.52%   |
| Ricoh USB2.0 Camera                           | 1         | 1.52%   |
| Ricoh Integrated Webcam                       | 1         | 1.52%   |
| Realtek USB Camera                            | 1         | 1.52%   |
| Realtek Lenovo EasyCamera                     | 1         | 1.52%   |
| Realtek Integrated_Webcam_HD                  | 1         | 1.52%   |
| Realtek Integrated Webcam HD                  | 1         | 1.52%   |
| Realtek Integrated Webcam                     | 1         | 1.52%   |
| Realtek EasyCamera                            | 1         | 1.52%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.52%   |
| Primax Dell Laptop Integrated Webcam 2Mpix    | 1         | 1.52%   |
| Microdia Webcam Vitade AF                     | 1         | 1.52%   |
| Microdia WebCam SC-13HDL12639P                | 1         | 1.52%   |
| Microdia Webcam                               | 1         | 1.52%   |
| Microdia USB 2.0 Camera                       | 1         | 1.52%   |
| Microdia Laptop_Integrated_Webcam_2HDM        | 1         | 1.52%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.52%   |
| Logitech StreamCam                            | 1         | 1.52%   |
| Lite-On Integrated Camera                     | 1         | 1.52%   |
| Lite-On HP HD Webcam                          | 1         | 1.52%   |
| Lite-On HP HD Camera                          | 1         | 1.52%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.52%   |
| IMC Networks USB2.0 UVC 1.3M WebCam           | 1         | 1.52%   |
| IMC Networks USB2.0 HD UVC WebCam             | 1         | 1.52%   |
| IMC Networks Integrated Camera                | 1         | 1.52%   |
| Goodong Industry USB2.0 HD UVC WebCam         | 1         | 1.52%   |
| Chicony USB2.0 HD UVC WebCam                  | 1         | 1.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 45.45%  |
| Shenzhen Goodix Technology | 2         | 18.18%  |
| AuthenTec                  | 2         | 18.18%  |
| Upek                       | 1         | 9.09%   |
| Synaptics                  | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor     | 3         | 27.27%  |
| Validity Sensors VFS495 Fingerprint Reader       | 2         | 18.18%  |
| Shenzhen Goodix  FingerPrint Device              | 2         | 18.18%  |
| Upek TCS5B Fingerprint sensor                    | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 9.09%   |
| AuthenTec AES2810                                | 1         | 9.09%   |
| AuthenTec AES1660 Fingerprint Sensor             | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 3         | 50%     |
| Alcor Micro           | 2         | 33.33%  |
| Advanced Card Systems | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 16.67%  |
| Advanced Card Systems ACR122U                  | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 52        | 60.47%  |
| 1     | 25        | 29.07%  |
| 2     | 8         | 9.3%    |
| 3     | 1         | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 23        | 57.5%   |
| Fingerprint reader    | 11        | 27.5%   |
| Chipcard              | 5         | 12.5%   |
| Multimedia controller | 1         | 2.5%    |

