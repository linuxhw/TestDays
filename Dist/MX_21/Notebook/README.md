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

Total: 100

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 14        | 17.5%   |
| 5.10.0-13-amd64           | 12        | 15%     |
| 5.14.0-4mx-amd64          | 8         | 10%     |
| 5.10.0-16-amd64           | 8         | 10%     |
| 5.10.0-14-amd64           | 6         | 7.5%    |
| 5.10.0-11-amd64           | 6         | 7.5%    |
| 5.16.0-5mx-amd64          | 4         | 5%      |
| 5.16.0-6mx-amd64          | 2         | 2.5%    |
| 5.10.0-8-amd64            | 2         | 2.5%    |
| 5.10.0-17-amd64           | 2         | 2.5%    |
| 5.10.0-15-amd64           | 2         | 2.5%    |
| 5.10.0-13-686-pae         | 2         | 2.5%    |
| 5.10.0-11-686-pae         | 2         | 2.5%    |
| 5.10.0-10-amd64           | 2         | 2.5%    |
| 5.18.0-3-amd64            | 1         | 1.25%   |
| 5.17.0-5.2-liquorix-amd64 | 1         | 1.25%   |
| 5.17.0-1-amd64            | 1         | 1.25%   |
| 5.16.0-4mx-amd64          | 1         | 1.25%   |
| 5.15.0-3mx-amd64          | 1         | 1.25%   |
| 5.10.0-5mx-amd64          | 1         | 1.25%   |
| 5.10.0-12-amd64           | 1         | 1.25%   |
| 5.10.0-11-686             | 1         | 1.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 57        | 75%     |
| 5.14.0  | 8         | 10.53%  |
| 5.16.0  | 7         | 9.21%   |
| 5.17.0  | 2         | 2.63%   |
| 5.18.0  | 1         | 1.32%   |
| 5.15.0  | 1         | 1.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 57        | 75%     |
| 5.14    | 8         | 10.53%  |
| 5.16    | 7         | 9.21%   |
| 5.17    | 2         | 2.63%   |
| 5.18    | 1         | 1.32%   |
| 5.15    | 1         | 1.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 69        | 94.52%  |
| i686   | 4         | 5.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 47        | 64.38%  |
| KDE5          | 18        | 24.66%  |
| GNOME         | 2         | 2.74%   |
| Budgie        | 2         | 2.74%   |
| Unknown       | 2         | 2.74%   |
| LXQt          | 1         | 1.37%   |
| GNOME Classic | 1         | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 71        | 97.26%  |
| Tty  | 2         | 2.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 55        | 75.34%  |
| SDDM    | 17        | 23.29%  |
| Unknown | 1         | 1.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 38        | 52.05%  |
| de_DE   | 10        | 13.7%   |
| ru_RU   | 3         | 4.11%   |
| it_IT   | 3         | 4.11%   |
| Unknown | 3         | 4.11%   |
| pt_BR   | 2         | 2.74%   |
| fr_FR   | 2         | 2.74%   |
| es_ES   | 2         | 2.74%   |
| en_GB   | 2         | 2.74%   |
| tr_TR   | 1         | 1.37%   |
| sk_SK   | 1         | 1.37%   |
| nb_NO   | 1         | 1.37%   |
| id_ID   | 1         | 1.37%   |
| fi_FI   | 1         | 1.37%   |
| es_PE   | 1         | 1.37%   |
| en_AU   | 1         | 1.37%   |
| de_CH   | 1         | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 53        | 72.6%   |
| BIOS | 20        | 27.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 61        | 83.56%  |
| Overlay | 9         | 12.33%  |
| Btrfs   | 2         | 2.74%   |
| F2fs    | 1         | 1.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 55        | 75.34%  |
| MBR     | 17        | 23.29%  |
| Unknown | 1         | 1.37%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 72.6%   |
| Yes       | 20        | 27.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 52.7%   |
| No        | 35        | 47.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 15        | 20.55%  |
| ASUSTek Computer    | 9         | 12.33%  |
| Hewlett-Packard     | 8         | 10.96%  |
| Dell                | 8         | 10.96%  |
| Sony                | 5         | 6.85%   |
| Acer                | 5         | 6.85%   |
| Samsung Electronics | 3         | 4.11%   |
| Apple               | 3         | 4.11%   |
| Alienware           | 3         | 4.11%   |
| MSI                 | 2         | 2.74%   |
| Gigabyte Technology | 2         | 2.74%   |
| Fujitsu Siemens     | 2         | 2.74%   |
| Unknown             | 2         | 2.74%   |
| TUXEDO              | 1         | 1.37%   |
| Toshiba             | 1         | 1.37%   |
| Medion              | 1         | 1.37%   |
| Framework           | 1         | 1.37%   |
| efirstview          | 1         | 1.37%   |
| Chuwi               | 1         | 1.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 4.11%   |
| TUXEDO N7x0WU                             | 1         | 1.37%   |
| Toshiba Satellite C845                    | 1         | 1.37%   |
| Sony VPCSB1V9R                            | 1         | 1.37%   |
| Sony VPCF119FX                            | 1         | 1.37%   |
| Sony VPCEH2N1E                            | 1         | 1.37%   |
| Sony VPCEC3S1E                            | 1         | 1.37%   |
| Sony SVE1513Q1ESI                         | 1         | 1.37%   |
| Samsung NC210/NC110                       | 1         | 1.37%   |
| Samsung 350V5C/351V5C/3540VC/3440VC       | 1         | 1.37%   |
| Samsung 340XAA/350XAA/550XAA              | 1         | 1.37%   |
| MSI GV62 8RD                              | 1         | 1.37%   |
| MSI Alpha 15 B5EEK                        | 1         | 1.37%   |
| Medion E14304                             | 1         | 1.37%   |
| Lenovo ThinkPad W541 20EG0005MS           | 1         | 1.37%   |
| Lenovo ThinkPad T560 20FJS0EP00           | 1         | 1.37%   |
| Lenovo ThinkPad T500 2241VL9              | 1         | 1.37%   |
| Lenovo ThinkPad T440p 20AW002VBR          | 1         | 1.37%   |
| Lenovo ThinkPad T430 23427YU              | 1         | 1.37%   |
| Lenovo ThinkPad L512 44444WG              | 1         | 1.37%   |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS      | 1         | 1.37%   |
| Lenovo ThinkBook 13s-IWL 20R9             | 1         | 1.37%   |
| Lenovo S130-11IGM 81J1                    | 1         | 1.37%   |
| Lenovo Legion 5 15ACH6H 82JU              | 1         | 1.37%   |
| Lenovo IdeaPad Y700-15ISK 80NV            | 1         | 1.37%   |
| Lenovo IdeaPad 3 15IIL05 81WE             | 1         | 1.37%   |
| Lenovo G400s VILG1                        | 1         | 1.37%   |
| Lenovo B590 20208                         | 1         | 1.37%   |
| HP Stream Laptop 14-cb0XX                 | 1         | 1.37%   |
| HP ProBook 450 G4                         | 1         | 1.37%   |
| HP ProBook 450 G1                         | 1         | 1.37%   |
| HP Laptop 15-ef2xxx                       | 1         | 1.37%   |
| HP EliteBook 850 G3                       | 1         | 1.37%   |
| HP EliteBook 8440p                        | 1         | 1.37%   |
| HP EliteBook 840 G3                       | 1         | 1.37%   |
| HP Compaq Presario CQ60                   | 1         | 1.37%   |
| Gigabyte P15FV5                           | 1         | 1.37%   |
| Gigabyte G5 KC                            | 1         | 1.37%   |
| Fujitsu Siemens LIFEBOOK E8010            | 1         | 1.37%   |
| Fujitsu Siemens ESPRIMO Mobile D9500      | 1         | 1.37%   |
| Framework Laptop                          | 1         | 1.37%   |
| efirstview v01099                         | 1         | 1.37%   |
| Dell XPS 17 9710                          | 1         | 1.37%   |
| Dell Vostro 3550                          | 1         | 1.37%   |
| Dell System XPS 15Z                       | 1         | 1.37%   |
| Dell Precision 7720                       | 1         | 1.37%   |
| Dell Latitude E4310                       | 1         | 1.37%   |
| Dell Latitude D520                        | 1         | 1.37%   |
| Dell Latitude 3190                        | 1         | 1.37%   |
| Dell Inspiron 15-3552                     | 1         | 1.37%   |
| Chuwi GemiBook Pro                        | 1         | 1.37%   |
| ASUS X550CC                               | 1         | 1.37%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 1         | 1.37%   |
| ASUS ROG Strix G712LU_G712LU              | 1         | 1.37%   |
| ASUS ROG Strix G513QC_G513QC              | 1         | 1.37%   |
| ASUS N53SN                                | 1         | 1.37%   |
| ASUS K55A                                 | 1         | 1.37%   |
| ASUS E402MA                               | 1         | 1.37%   |
| ASUS ASUS TUF Gaming A15 FA506QE_TUF506QE | 1         | 1.37%   |
| ASUS 1101HA                               | 1         | 1.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 7         | 9.59%   |
| HP EliteBook             | 3         | 4.11%   |
| Dell Latitude            | 3         | 4.11%   |
| Unknown                  | 3         | 4.11%   |
| Lenovo IdeaPad           | 2         | 2.74%   |
| HP ProBook               | 2         | 2.74%   |
| ASUS ROG                 | 2         | 2.74%   |
| Alienware m15            | 2         | 2.74%   |
| Acer Aspire              | 2         | 2.74%   |
| TUXEDO N7x0WU            | 1         | 1.37%   |
| Toshiba Satellite        | 1         | 1.37%   |
| Sony VPCSB1V9R           | 1         | 1.37%   |
| Sony VPCF119FX           | 1         | 1.37%   |
| Sony VPCEH2N1E           | 1         | 1.37%   |
| Sony VPCEC3S1E           | 1         | 1.37%   |
| Sony SVE1513Q1ESI        | 1         | 1.37%   |
| Samsung NC210            | 1         | 1.37%   |
| Samsung 350V5C           | 1         | 1.37%   |
| Samsung 340XAA           | 1         | 1.37%   |
| MSI GV62                 | 1         | 1.37%   |
| MSI Alpha                | 1         | 1.37%   |
| Medion E14304            | 1         | 1.37%   |
| Lenovo ThinkBook         | 1         | 1.37%   |
| Lenovo S130-11IGM        | 1         | 1.37%   |
| Lenovo Legion            | 1         | 1.37%   |
| Lenovo G400s             | 1         | 1.37%   |
| Lenovo B590              | 1         | 1.37%   |
| HP Stream                | 1         | 1.37%   |
| HP Laptop                | 1         | 1.37%   |
| HP Compaq                | 1         | 1.37%   |
| Gigabyte P15FV5          | 1         | 1.37%   |
| Gigabyte G5              | 1         | 1.37%   |
| Fujitsu Siemens LIFEBOOK | 1         | 1.37%   |
| Fujitsu Siemens ESPRIMO  | 1         | 1.37%   |
| Framework Laptop         | 1         | 1.37%   |
| efirstview v01099        | 1         | 1.37%   |
| Dell XPS                 | 1         | 1.37%   |
| Dell Vostro              | 1         | 1.37%   |
| Dell System              | 1         | 1.37%   |
| Dell Precision           | 1         | 1.37%   |
| Dell Inspiron            | 1         | 1.37%   |
| Chuwi GemiBook           | 1         | 1.37%   |
| ASUS X550CC              | 1         | 1.37%   |
| ASUS TUF                 | 1         | 1.37%   |
| ASUS N53SN               | 1         | 1.37%   |
| ASUS K55A                | 1         | 1.37%   |
| ASUS E402MA              | 1         | 1.37%   |
| ASUS ASUS                | 1         | 1.37%   |
| ASUS 1101HA              | 1         | 1.37%   |
| Apple MacBookPro11       | 1         | 1.37%   |
| Apple MacBookAir7        | 1         | 1.37%   |
| Apple MacBook3           | 1         | 1.37%   |
| Alienware 13             | 1         | 1.37%   |
| Acer Swift               | 1         | 1.37%   |
| Acer One                 | 1         | 1.37%   |
| Acer Nitro               | 1         | 1.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 13        | 17.81%  |
| 2015    | 8         | 10.96%  |
| 2011    | 6         | 8.22%   |
| 2020    | 5         | 6.85%   |
| 2016    | 5         | 6.85%   |
| 2013    | 5         | 6.85%   |
| 2010    | 5         | 6.85%   |
| 2018    | 4         | 5.48%   |
| 2012    | 4         | 5.48%   |
| 2019    | 3         | 4.11%   |
| 2008    | 3         | 4.11%   |
| 2022    | 2         | 2.74%   |
| 2017    | 2         | 2.74%   |
| 2014    | 2         | 2.74%   |
| 2007    | 2         | 2.74%   |
| 2009    | 1         | 1.37%   |
| 2006    | 1         | 1.37%   |
| 2005    | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 73        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 73        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 24        | 32.88%  |
| 16.01-24.0  | 15        | 20.55%  |
| 8.01-16.0   | 12        | 16.44%  |
| 3.01-4.0    | 11        | 15.07%  |
| 2.01-3.0    | 3         | 4.11%   |
| 1.01-2.0    | 3         | 4.11%   |
| 32.01-64.0  | 2         | 2.74%   |
| 24.01-32.0  | 1         | 1.37%   |
| 64.01-256.0 | 1         | 1.37%   |
| 0.51-1.0    | 1         | 1.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 28        | 35.9%   |
| 2.01-3.0  | 22        | 28.21%  |
| 3.01-4.0  | 12        | 15.38%  |
| 4.01-8.0  | 7         | 8.97%   |
| 0.51-1.0  | 6         | 7.69%   |
| 8.01-16.0 | 2         | 2.56%   |
| 0.01-0.5  | 1         | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 64.86%  |
| 2      | 18        | 24.32%  |
| 3      | 6         | 8.11%   |
| 4      | 1         | 1.35%   |
| 0      | 1         | 1.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 68.49%  |
| Yes       | 23        | 31.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 78.08%  |
| No        | 16        | 21.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 94.52%  |
| No        | 4         | 5.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 78.08%  |
| No        | 16        | 21.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 18        | 24.32%  |
| Germany     | 10        | 13.51%  |
| Canada      | 6         | 8.11%   |
| Italy       | 5         | 6.76%   |
| Brazil      | 4         | 5.41%   |
| Spain       | 2         | 2.7%    |
| Serbia      | 2         | 2.7%    |
| Russia      | 2         | 2.7%    |
| Netherlands | 2         | 2.7%    |
| France      | 2         | 2.7%    |
| Belgium     | 2         | 2.7%    |
| Austria     | 2         | 2.7%    |
| UK          | 1         | 1.35%   |
| Turkey      | 1         | 1.35%   |
| Switzerland | 1         | 1.35%   |
| Slovakia    | 1         | 1.35%   |
| Romania     | 1         | 1.35%   |
| Poland      | 1         | 1.35%   |
| Peru        | 1         | 1.35%   |
| Norway      | 1         | 1.35%   |
| Malaysia    | 1         | 1.35%   |
| Indonesia   | 1         | 1.35%   |
| India       | 1         | 1.35%   |
| Ghana       | 1         | 1.35%   |
| Finland     | 1         | 1.35%   |
| Czechia     | 1         | 1.35%   |
| Belarus     | 1         | 1.35%   |
| Azerbaijan  | 1         | 1.35%   |
| Australia   | 1         | 1.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Vienna                    | 2         | 2.63%   |
| Orange                    | 2         | 2.63%   |
| Montreal                  | 2         | 2.63%   |
| Doesburg                  | 2         | 2.63%   |
| Zurich                    | 1         | 1.32%   |
| Waycross                  | 1         | 1.32%   |
| Warsaw                    | 1         | 1.32%   |
| Vasco da Gama             | 1         | 1.32%   |
| Vancouver                 | 1         | 1.32%   |
| Uelzen                    | 1         | 1.32%   |
| Tucson                    | 1         | 1.32%   |
| Taggia                    | 1         | 1.32%   |
| Tacoma                    | 1         | 1.32%   |
| Sydney                    | 1         | 1.32%   |
| Surprise                  | 1         | 1.32%   |
| Stadtilm                  | 1         | 1.32%   |
| St Petersburg             | 1         | 1.32%   |
| Schaarbeek                | 1         | 1.32%   |
| Saskatoon                 | 1         | 1.32%   |
| Saarlouis                 | 1         | 1.32%   |
| Roseville                 | 1         | 1.32%   |
| Rochester                 | 1         | 1.32%   |
| Reinbek                   | 1         | 1.32%   |
| Prague                    | 1         | 1.32%   |
| Powder Springs            | 1         | 1.32%   |
| Postbauer-Heng            | 1         | 1.32%   |
| Portland                  | 1         | 1.32%   |
| Ottawa                    | 1         | 1.32%   |
| Oslo                      | 1         | 1.32%   |
| Osasco                    | 1         | 1.32%   |
| Obourg                    | 1         | 1.32%   |
| Neumarkt in der Oberpfalz | 1         | 1.32%   |
| Munich                    | 1         | 1.32%   |
| Moscow                    | 1         | 1.32%   |
| Montebelluna              | 1         | 1.32%   |
| Minsk                     | 1         | 1.32%   |
| Mestre                    | 1         | 1.32%   |
| Marion                    | 1         | 1.32%   |
| Lima                      | 1         | 1.32%   |
| Lannion                   | 1         | 1.32%   |
| Lahti                     | 1         | 1.32%   |
| Koblenz                   | 1         | 1.32%   |
| Kitchener                 | 1         | 1.32%   |
| Jambi City                | 1         | 1.32%   |
| Jagodina                  | 1         | 1.32%   |
| Istanbul                  | 1         | 1.32%   |
| Iasi                      | 1         | 1.32%   |
| Huercal Overa             | 1         | 1.32%   |
| Hamburg                   | 1         | 1.32%   |
| Graniteville              | 1         | 1.32%   |
| Florence                  | 1         | 1.32%   |
| El Provencio              | 1         | 1.32%   |
| Diss                      | 1         | 1.32%   |
| Diana                     | 1         | 1.32%   |
| Cyberjaya                 | 1         | 1.32%   |
| Curitiba                  | 1         | 1.32%   |
| Corsico                   | 1         | 1.32%   |
| Corona                    | 1         | 1.32%   |
| Chasseneuil-du-Poitou     | 1         | 1.32%   |
| Cambui                    | 1         | 1.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 14     | 14%     |
| Samsung Electronics | 13        | 15     | 13%     |
| Seagate             | 10        | 11     | 10%     |
| Crucial             | 10        | 17     | 10%     |
| Unknown             | 6         | 7      | 6%      |
| SK hynix            | 6         | 7      | 6%      |
| Kingston            | 6         | 6      | 6%      |
| Transcend           | 3         | 3      | 3%      |
| SanDisk             | 3         | 4      | 3%      |
| LITEON              | 3         | 3      | 3%      |
| Intel               | 3         | 3      | 3%      |
| Dogfish             | 3         | 3      | 3%      |
| Toshiba             | 2         | 2      | 2%      |
| Netac               | 2         | 2      | 2%      |
| Apple               | 2         | 3      | 2%      |
| Team                | 1         | 1      | 1%      |
| SPCC                | 1         | 1      | 1%      |
| SABRENT             | 1         | 1      | 1%      |
| PNY                 | 1         | 1      | 1%      |
| Phison              | 1         | 1      | 1%      |
| OCZ                 | 1         | 1      | 1%      |
| Micron Technology   | 1         | 1      | 1%      |
| KIOXIA              | 1         | 1      | 1%      |
| Indilinx            | 1         | 1      | 1%      |
| Hitachi             | 1         | 1      | 1%      |
| Gigabyte Technology | 1         | 1      | 1%      |
| GeIL                | 1         | 1      | 1%      |
| Fujitsu             | 1         | 1      | 1%      |
| Unknown             | 1         | 1      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD           | 3         | 2.88%   |
| Unknown SD32G  32GB                       | 2         | 1.92%   |
| SK hynix HFM512GDJTNI-82A0A 512GB         | 2         | 1.92%   |
| Samsung SSD 860 EVO 500GB                 | 2         | 1.92%   |
| Dogfish SSD 128GB                         | 2         | 1.92%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 1.92%   |
| Crucial CT240BX500SSD1 240GB              | 2         | 1.92%   |
| Crucial CT120BX500SSD1 120GB              | 2         | 1.92%   |
| WDC WDS500G2B0B-00YS70 500GB SSD          | 1         | 0.96%   |
| WDC WDS100T1X0E-00AFY0 1TB                | 1         | 0.96%   |
| WDC WD5000LPVX-22V0TT0 500GB              | 1         | 0.96%   |
| WDC WD5000LPVX-08V0TT5 500GB              | 1         | 0.96%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 0.96%   |
| WDC WD5000LPCX-22VHAT0 500GB              | 1         | 0.96%   |
| WDC WD3200BEVT-22ZCT0 320GB               | 1         | 0.96%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 0.96%   |
| WDC WD1600BEVT-60ZCT1 160GB               | 1         | 0.96%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.96%   |
| WDC PC SN730 NVMe 1024GB                  | 1         | 0.96%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB        | 1         | 0.96%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 0.96%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB      | 1         | 0.96%   |
| Unknown SDW32G  32GB                      | 1         | 0.96%   |
| Unknown SD08G  8GB                        | 1         | 0.96%   |
| Unknown ISOCOM  64GB                      | 1         | 0.96%   |
| Unknown DA4064  64GB                      | 1         | 0.96%   |
| Unknown BJTD4R  32GB                      | 1         | 0.96%   |
| Transcend TS256GSSD370S 256GB             | 1         | 0.96%   |
| Transcend TS1GSDOM22V 1GB SSD             | 1         | 0.96%   |
| Transcend TS128GMTS800 128GB SSD          | 1         | 0.96%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 0.96%   |
| Toshiba KBG40ZNT256G MEMORY 256GB         | 1         | 0.96%   |
| Team TM8FP6256G 256GB                     | 1         | 0.96%   |
| SPCC Solid State Disk 128GB               | 1         | 0.96%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 0.96%   |
| SK hynix PC601 NVMe 512GB                 | 1         | 0.96%   |
| SK hynix HFM512GD3JX013N 512GB            | 1         | 0.96%   |
| SK hynix HFM256GDJTNG-8310A 256GB         | 1         | 0.96%   |
| Seagate ST9320421AS 320GB                 | 1         | 0.96%   |
| Seagate ST9160821AS 160GB                 | 1         | 0.96%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 0.96%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 0.96%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 0.96%   |
| Seagate ST2000LM003 HN-M201RAD 2TB        | 1         | 0.96%   |
| Seagate ST1000LM048-2E7172 1TB            | 1         | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 0.96%   |
| Seagate ST1000LM014-1EJ164 1TB            | 1         | 0.96%   |
| SanDisk SD8TB8U256G1001 256GB SSD         | 1         | 0.96%   |
| SanDisk SD8SNAT-256G-1006 256GB SSD       | 1         | 0.96%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD       | 1         | 0.96%   |
| Samsung SSD 980 PRO 1TB                   | 1         | 0.96%   |
| Samsung SSD 970 EVO 1TB                   | 1         | 0.96%   |
| Samsung SSD 960 EVO 250GB                 | 1         | 0.96%   |
| Samsung SSD 860 EVO M.2 250GB             | 1         | 0.96%   |
| Samsung SSD 860 EVO M.2 1TB               | 1         | 0.96%   |
| Samsung SSD 860 EVO 1TB                   | 1         | 0.96%   |
| Samsung SSD 850 EVO 250GB                 | 1         | 0.96%   |
| Samsung SSD 840 PRO Series 256GB          | 1         | 0.96%   |
| Samsung PM9A1 NVMe 512GB                  | 1         | 0.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 43.48%  |
| WDC                 | 8         | 8      | 34.78%  |
| Toshiba             | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| SABRENT             | 1         | 1      | 4.35%   |
| Hitachi             | 1         | 1      | 4.35%   |
| Fujitsu             | 1         | 1      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 15     | 20%     |
| Samsung Electronics | 8         | 9      | 17.78%  |
| Kingston            | 4         | 4      | 8.89%   |
| Transcend           | 3         | 3      | 6.67%   |
| SanDisk             | 3         | 4      | 6.67%   |
| LITEON              | 3         | 3      | 6.67%   |
| Dogfish             | 3         | 3      | 6.67%   |
| Netac               | 2         | 2      | 4.44%   |
| Apple               | 2         | 3      | 4.44%   |
| WDC                 | 1         | 1      | 2.22%   |
| SPCC                | 1         | 1      | 2.22%   |
| PNY                 | 1         | 1      | 2.22%   |
| OCZ                 | 1         | 1      | 2.22%   |
| Intel               | 1         | 1      | 2.22%   |
| Indilinx            | 1         | 1      | 2.22%   |
| Gigabyte Technology | 1         | 1      | 2.22%   |
| GeIL                | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 37        | 54     | 41.57%  |
| HDD  | 23        | 24     | 25.84%  |
| NVMe | 22        | 28     | 24.72%  |
| MMC  | 7         | 8      | 7.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 51        | 77     | 62.96%  |
| NVMe | 22        | 28     | 27.16%  |
| MMC  | 7         | 8      | 8.64%   |
| SAS  | 1         | 1      | 1.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 44        | 56     | 74.58%  |
| 0.51-1.0   | 13        | 20     | 22.03%  |
| 1.01-2.0   | 2         | 2      | 3.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 29.33%  |
| 251-500        | 16        | 21.33%  |
| 501-1000       | 12        | 16%     |
| 21-50          | 8         | 10.67%  |
| 1-20           | 5         | 6.67%   |
| 51-100         | 5         | 6.67%   |
| 1001-2000      | 3         | 4%      |
| More than 3000 | 2         | 2.67%   |
| 2001-3000      | 2         | 2.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 42.86%  |
| 21-50          | 16        | 20.78%  |
| 251-500        | 8         | 10.39%  |
| 101-250        | 7         | 9.09%   |
| 51-100         | 7         | 9.09%   |
| 501-1000       | 3         | 3.9%    |
| 1001-2000      | 2         | 2.6%    |
| More than 3000 | 1         | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 12.5%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 12.5%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 12.5%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 12.5%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 12.5%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 1      | 12.5%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 37.5%   |
| WDC                 | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Indilinx            | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 50%     |
| WDC     | 2         | 2      | 33.33%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 75%     |
| SSD  | 2         | 2      | 25%     |

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
| Works    | 62        | 96     | 78.48%  |
| Detected | 9         | 10     | 11.39%  |
| Malfunc  | 8         | 8      | 10.13%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 54        | 62.79%  |
| Samsung Electronics         | 7         | 8.14%   |
| SK hynix                    | 6         | 6.98%   |
| SanDisk                     | 5         | 5.81%   |
| AMD                         | 3         | 3.49%   |
| Phison Electronics          | 2         | 2.33%   |
| Nvidia                      | 2         | 2.33%   |
| KIOXIA                      | 2         | 2.33%   |
| Kingston Technology Company | 2         | 2.33%   |
| Silicon Image               | 1         | 1.16%   |
| Micron/Crucial Technology   | 1         | 1.16%   |
| Micron Technology           | 1         | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 8         | 8.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 6.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 4.35%   |
| SK hynix BC511                                                                         | 3         | 3.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 3.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3.26%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 3         | 3.26%   |
| SanDisk Non-Volatile memory controller                                                 | 2         | 2.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 2.17%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 2         | 2.17%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 2.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 2.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 2.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 2.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 2.17%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 1.09%   |
| SK hynix Gold P31 SSD                                                                  | 1         | 1.09%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 1.09%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                   | 1         | 1.09%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                             | 1         | 1.09%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.09%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.09%   |
| Samsung Electronics SATA controller                                                    | 1         | 1.09%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 1.09%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.09%   |
| Phison E12 NVMe Controller                                                             | 1         | 1.09%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                           | 1         | 1.09%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                       | 1         | 1.09%   |
| Nvidia MCP67 IDE Controller                                                            | 1         | 1.09%   |
| Nvidia MCP67 AHCI Controller                                                           | 1         | 1.09%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 1.09%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.09%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1.09%   |
| Kingston Company KC2000 NVMe SSD                                                       | 1         | 1.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.09%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 1         | 1.09%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 1.09%   |
| Intel SSD 660P Series                                                                  | 1         | 1.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.09%   |
| Intel Non-Volatile memory controller                                                   | 1         | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 1.09%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.09%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.09%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.09%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 1         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.09%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 50        | 58.82%  |
| NVMe | 22        | 25.88%  |
| IDE  | 8         | 9.41%   |
| RAID | 5         | 5.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 61        | 83.56%  |
| AMD    | 12        | 16.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics   | 3         | 4.11%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 2.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 2         | 2.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 2         | 2.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 2.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 2         | 2.74%   |
| Intel Celeron CPU N3060 @ 1.60GHz        | 2         | 2.74%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 1.37%   |
| Intel Pentium M processor 1.80GHz        | 1         | 1.37%   |
| Intel Genuine CPU T2300 @ 1.66GHz        | 1         | 1.37%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 1         | 1.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 1         | 1.37%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 1         | 1.37%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 1         | 1.37%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 1.37%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 1         | 1.37%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz       | 1         | 1.37%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz       | 1         | 1.37%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 1.37%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 1         | 1.37%   |
| Intel Core i7-2640M CPU @ 2.80GHz        | 1         | 1.37%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz        | 1         | 1.37%   |
| Intel Core i7 CPU M 620 @ 2.67GHz        | 1         | 1.37%   |
| Intel Core i5-8300H CPU @ 2.30GHz        | 1         | 1.37%   |
| Intel Core i5-5350U CPU @ 1.80GHz        | 1         | 1.37%   |
| Intel Core i5-4300M CPU @ 2.60GHz        | 1         | 1.37%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 1         | 1.37%   |
| Intel Core i5-2450M CPU @ 2.50GHz        | 1         | 1.37%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 1         | 1.37%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 1         | 1.37%   |
| Intel Core i5-10500H CPU @ 2.50GHz       | 1         | 1.37%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 1         | 1.37%   |
| Intel Core i5 CPU M 460 @ 2.53GHz        | 1         | 1.37%   |
| Intel Core i3-5005U CPU @ 2.00GHz        | 1         | 1.37%   |
| Intel Core i3-4000M CPU @ 2.40GHz        | 1         | 1.37%   |
| Intel Core i3-3217U CPU @ 1.80GHz        | 1         | 1.37%   |
| Intel Core i3-2330M CPU @ 2.20GHz        | 1         | 1.37%   |
| Intel Core i3-2328M CPU @ 2.20GHz        | 1         | 1.37%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz       | 1         | 1.37%   |
| Intel Core i3 CPU M 380 @ 2.53GHz        | 1         | 1.37%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz     | 1         | 1.37%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz     | 1         | 1.37%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 1         | 1.37%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 1         | 1.37%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 1         | 1.37%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 1         | 1.37%   |
| Intel Celeron CPU N2840 @ 2.16GHz        | 1         | 1.37%   |
| Intel Celeron CPU 847 @ 1.10GHz          | 1         | 1.37%   |
| Intel Atom CPU Z520 @ 1.33GHz            | 1         | 1.37%   |
| Intel Atom CPU Z3735G @ 1.33GHz          | 1         | 1.37%   |
| Intel Atom CPU N570 @ 1.66GHz            | 1         | 1.37%   |
| Intel 12th Gen Core i7-12700H            | 1         | 1.37%   |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz | 1         | 1.37%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz  | 1         | 1.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 1         | 1.37%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 1         | 1.37%   |
| AMD Turion 64 X2 Mobile Technology TL-58 | 1         | 1.37%   |
| AMD Sempron SI-42                        | 1         | 1.37%   |
| AMD Ryzen 9 5900HX with Radeon Graphics  | 1         | 1.37%   |
| AMD Ryzen 7 5800U with Radeon Graphics   | 1         | 1.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 19        | 26.03%  |
| Intel Core i5           | 14        | 19.18%  |
| Intel Core i3           | 7         | 9.59%   |
| Intel Celeron           | 7         | 9.59%   |
| AMD Ryzen 7             | 6         | 8.22%   |
| Other                   | 5         | 6.85%   |
| Intel Core 2 Duo        | 3         | 4.11%   |
| Intel Atom              | 3         | 4.11%   |
| AMD Ryzen 5             | 2         | 2.74%   |
| Intel Pentium Silver    | 1         | 1.37%   |
| Intel Pentium M         | 1         | 1.37%   |
| Intel Genuine           | 1         | 1.37%   |
| AMD Turion 64 X2 Mobile | 1         | 1.37%   |
| AMD Sempron             | 1         | 1.37%   |
| AMD Ryzen 9             | 1         | 1.37%   |
| AMD Ryzen 3             | 1         | 1.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 35        | 47.95%  |
| 4      | 22        | 30.14%  |
| 8      | 7         | 9.59%   |
| 6      | 5         | 6.85%   |
| 1      | 3         | 4.11%   |
| 14     | 1         | 1.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 73        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 56        | 76.71%  |
| 1      | 17        | 23.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 70        | 95.89%  |
| 32-bit         | 3         | 4.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 7         | 9.46%   |
| Unknown    | 7         | 9.46%   |
| 0x306a9    | 5         | 6.76%   |
| 0x406e3    | 4         | 5.41%   |
| 0x0a50000c | 4         | 5.41%   |
| 0xa0652    | 3         | 4.05%   |
| 0x506e3    | 3         | 4.05%   |
| 0x306c3    | 3         | 4.05%   |
| 0x20655    | 3         | 4.05%   |
| 0x906ea    | 2         | 2.7%    |
| 0x806ea    | 2         | 2.7%    |
| 0x806c1    | 2         | 2.7%    |
| 0x706a1    | 2         | 2.7%    |
| 0x406c4    | 2         | 2.7%    |
| 0x30678    | 2         | 2.7%    |
| 0x08608103 | 2         | 2.7%    |
| 0x906a3    | 1         | 1.35%   |
| 0x806eb    | 1         | 1.35%   |
| 0x806e9    | 1         | 1.35%   |
| 0x806d1    | 1         | 1.35%   |
| 0x706a8    | 1         | 1.35%   |
| 0x6fd      | 1         | 1.35%   |
| 0x6fb      | 1         | 1.35%   |
| 0x6e8      | 1         | 1.35%   |
| 0x6d6      | 1         | 1.35%   |
| 0x506c9    | 1         | 1.35%   |
| 0x40661    | 1         | 1.35%   |
| 0x306d4    | 1         | 1.35%   |
| 0x106e5    | 1         | 1.35%   |
| 0x106ca    | 1         | 1.35%   |
| 0x106c2    | 1         | 1.35%   |
| 0x1067a    | 1         | 1.35%   |
| 0x0a50000b | 1         | 1.35%   |
| 0x08600106 | 1         | 1.35%   |
| 0x08108109 | 1         | 1.35%   |
| 0x08108102 | 1         | 1.35%   |
| 0x02000057 | 1         | 1.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 8         | 10.96%  |
| Skylake          | 7         | 9.59%   |
| KabyLake         | 6         | 8.22%   |
| Zen 3            | 5         | 6.85%   |
| IvyBridge        | 5         | 6.85%   |
| Westmere         | 4         | 5.48%   |
| Silvermont       | 4         | 5.48%   |
| Haswell          | 4         | 5.48%   |
| TigerLake        | 3         | 4.11%   |
| Goldmont plus    | 3         | 4.11%   |
| CometLake        | 3         | 4.11%   |
| Zen+             | 2         | 2.74%   |
| P6               | 2         | 2.74%   |
| Icelake          | 2         | 2.74%   |
| Core             | 2         | 2.74%   |
| Broadwell        | 2         | 2.74%   |
| Bonnell          | 2         | 2.74%   |
| Unknown          | 2         | 2.74%   |
| Zen 2            | 1         | 1.37%   |
| Penryn           | 1         | 1.37%   |
| Nehalem          | 1         | 1.37%   |
| K8 Hammer        | 1         | 1.37%   |
| K8 & K10 hybrid  | 1         | 1.37%   |
| Goldmont         | 1         | 1.37%   |
| Alderlake Hybrid | 1         | 1.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 57        | 59.38%  |
| Nvidia | 25        | 26.04%  |
| AMD    | 14        | 14.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 8%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5%      |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 4%      |
| AMD Cezanne                                                                              | 4         | 4%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 3%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3%      |
| Intel HD Graphics 530                                                                    | 3         | 3%      |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 3%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3%      |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 2%      |
| Intel UHD Graphics 620                                                                   | 2         | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2%      |
| AMD Lucienne                                                                             | 2         | 2%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1%      |
| Nvidia TU117M                                                                            | 1         | 1%      |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1%      |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 1%      |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1%      |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1%      |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1%      |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1%      |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 1%      |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 1%      |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1%      |
| Nvidia GF108M [GeForce GT 550M]                                                          | 1         | 1%      |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1%      |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1%      |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1%      |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                              | 1         | 1%      |
| Nvidia C77 [GeForce 8200M G]                                                             | 1         | 1%      |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                                 | 1         | 1%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1%      |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1%      |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1%      |
| Intel HD Graphics 620                                                                    | 1         | 1%      |
| Intel HD Graphics 6000                                                                   | 1         | 1%      |
| Intel HD Graphics 5500                                                                   | 1         | 1%      |
| Intel HD Graphics 500                                                                    | 1         | 1%      |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1%      |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1%      |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 1%      |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1%      |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1%      |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                            | 1         | 1%      |
| AMD Renoir                                                                               | 1         | 1%      |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 1%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 49.32%  |
| Intel + Nvidia | 17        | 23.29%  |
| 1 x AMD        | 7         | 9.59%   |
| 1 x Nvidia     | 5         | 6.85%   |
| Intel + AMD    | 3         | 4.11%   |
| AMD + Nvidia   | 3         | 4.11%   |
| 2 x Intel      | 1         | 1.37%   |
| 2 x AMD        | 1         | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 59        | 79.73%  |
| Proprietary | 12        | 16.22%  |
| Unknown     | 3         | 4.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 82.19%  |
| 0.01-0.5   | 6         | 8.22%   |
| 0.51-1.0   | 3         | 4.11%   |
| 1.01-2.0   | 2         | 2.74%   |
| 7.01-8.0   | 1         | 1.37%   |
| 3.01-4.0   | 1         | 1.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 14        | 17.5%   |
| AU Optronics            | 13        | 16.25%  |
| Samsung Electronics     | 9         | 11.25%  |
| LG Display              | 9         | 11.25%  |
| BOE                     | 5         | 6.25%   |
| PANDA                   | 4         | 5%      |
| Sharp                   | 3         | 3.75%   |
| Lenovo                  | 3         | 3.75%   |
| Chi Mei Optoelectronics | 3         | 3.75%   |
| Apple                   | 3         | 3.75%   |
| Sony                    | 2         | 2.5%    |
| Hewlett-Packard         | 2         | 2.5%    |
| Ancor Communications    | 2         | 2.5%    |
| Sunplus                 | 1         | 1.25%   |
| Philips                 | 1         | 1.25%   |
| Panasonic               | 1         | 1.25%   |
| LTM                     | 1         | 1.25%   |
| InfoVision              | 1         | 1.25%   |
| Goldstar                | 1         | 1.25%   |
| Dell                    | 1         | 1.25%   |
| CPT                     | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 2.5%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x174mm 14.0-inch          | 2         | 2.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 2.5%    |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 1.25%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 1.25%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 1.25%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 1.25%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.25%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 1.25%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch    | 1         | 1.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 1         | 1.25%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 1.25%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 1.25%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 1.25%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 382x215mm 17.3-inch              | 1         | 1.25%   |
| LTM LCD_VGA LTM0659 1920x1080 886x498mm 40.0-inch                        | 1         | 1.25%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD06E2 1920x1080 344x194mm 15.5-inch             | 1         | 1.25%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 1.25%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch             | 1         | 1.25%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 1.25%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 1         | 1.25%   |
| LG Display LCD Monitor LGD024D 1366x768 294x166mm 13.3-inch              | 1         | 1.25%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch                 | 1         | 1.25%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 1         | 1.25%   |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                 | 1         | 1.25%   |
| InfoVision LCD Monitor IVO048E 1366x768 256x144mm 11.6-inch              | 1         | 1.25%   |
| Hewlett-Packard LA2306 HWP294B 1920x1080 509x286mm 23.0-inch             | 1         | 1.25%   |
| Hewlett-Packard E222 HWP3263 1920x1080 476x268mm 21.5-inch               | 1         | 1.25%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 1         | 1.25%   |
| Dell 1907FP DEL4014 1280x1024 376x301mm 19.0-inch                        | 1         | 1.25%   |
| CPT LCD Monitor CPT1C21 1366x768 256x144mm 11.6-inch                     | 1         | 1.25%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15D6 1920x1080 344x193mm 15.5-inch         | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1526 1920x1080 344x193mm 15.5-inch         | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.25%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 1.25%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 1         | 1.25%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 1         | 1.25%   |
| BOE LCD Monitor BOE0630 1920x1080 344x194mm 15.5-inch                    | 1         | 1.25%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 1         | 1.25%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 1         | 1.25%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch           | 1         | 1.25%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 1         | 1.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 33        | 44.59%  |
| 1366x768 (WXGA)    | 22        | 29.73%  |
| 3840x2160 (4K)     | 4         | 5.41%   |
| 1600x900 (HD+)     | 2         | 2.7%    |
| 1440x900 (WXGA+)   | 2         | 2.7%    |
| 1280x800 (WXGA)    | 2         | 2.7%    |
| 3840x2400          | 1         | 1.35%   |
| 2880x1800          | 1         | 1.35%   |
| 2560x1080          | 1         | 1.35%   |
| 2256x1504          | 1         | 1.35%   |
| 2160x1440          | 1         | 1.35%   |
| 1680x1050 (WSXGA+) | 1         | 1.35%   |
| 1400x1050          | 1         | 1.35%   |
| 1280x1024 (SXGA)   | 1         | 1.35%   |
| 1024x600           | 1         | 1.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 38        | 47.5%   |
| 13     | 9         | 11.25%  |
| 14     | 7         | 8.75%   |
| 17     | 5         | 6.25%   |
| 11     | 4         | 5%      |
| 24     | 3         | 3.75%   |
| 23     | 3         | 3.75%   |
| 19     | 3         | 3.75%   |
| 27     | 2         | 2.5%    |
| 84     | 1         | 1.25%   |
| 46     | 1         | 1.25%   |
| 40     | 1         | 1.25%   |
| 34     | 1         | 1.25%   |
| 21     | 1         | 1.25%   |
| 10     | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 58.75%  |
| 201-300     | 11        | 13.75%  |
| 501-600     | 8         | 10%     |
| 351-400     | 8         | 10%     |
| 401-500     | 2         | 2.5%    |
| 801-900     | 1         | 1.25%   |
| 701-800     | 1         | 1.25%   |
| 1501-2000   | 1         | 1.25%   |
| 1001-1500   | 1         | 1.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 58        | 79.45%  |
| 16/10 | 9         | 12.33%  |
| 5/4   | 2         | 2.74%   |
| 3/2   | 2         | 2.74%   |
| 4/3   | 1         | 1.37%   |
| 21/9  | 1         | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 47.5%   |
| 81-90          | 14        | 17.5%   |
| 201-250        | 5         | 6.25%   |
| 121-130        | 5         | 6.25%   |
| 51-60          | 4         | 5%      |
| 151-200        | 4         | 5%      |
| 71-80          | 2         | 2.5%    |
| 301-350        | 2         | 2.5%    |
| 501-1000       | 2         | 2.5%    |
| More than 1000 | 1         | 1.25%   |
| 351-500        | 1         | 1.25%   |
| 41-50          | 1         | 1.25%   |
| 251-300        | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 33        | 42.86%  |
| 51-100        | 18        | 23.38%  |
| 101-120       | 17        | 22.08%  |
| 161-240       | 5         | 6.49%   |
| More than 240 | 3         | 3.9%    |
| 1-50          | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 57        | 77.03%  |
| 2     | 12        | 16.22%  |
| 0     | 3         | 4.05%   |
| 3     | 2         | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 38        | 33.04%  |
| Intel                    | 37        | 32.17%  |
| Qualcomm Atheros         | 18        | 15.65%  |
| Marvell Technology Group | 4         | 3.48%   |
| Broadcom                 | 4         | 3.48%   |
| MediaTek                 | 3         | 2.61%   |
| TP-Link                  | 2         | 1.74%   |
| Nvidia                   | 2         | 1.74%   |
| Broadcom Limited         | 2         | 1.74%   |
| Sierra Wireless          | 1         | 0.87%   |
| Samsung Electronics      | 1         | 0.87%   |
| Ralink Technology        | 1         | 0.87%   |
| Dell                     | 1         | 0.87%   |
| ASUSTek Computer         | 1         | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 27        | 19.85%  |
| Intel Wi-Fi 6 AX200                                                            | 5         | 3.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 2.94%   |
| Intel Wireless 8260                                                            | 4         | 2.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 2.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 2.21%   |
| Intel Wireless 7260                                                            | 3         | 2.21%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 2         | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 1.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 2         | 1.47%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 1.47%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.47%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.47%   |
| Intel Centrino Advanced-N 6200                                                 | 2         | 1.47%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.74%   |
| TP-Link TL-WN722N v2                                                           | 1         | 0.74%   |
| Sierra Wireless EM7455                                                         | 1         | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.74%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.74%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 1         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 1         | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.74%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.74%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 0.74%   |
| Ralink RT2070 Wireless Adapter                                                 | 1         | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1         | 0.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.74%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.74%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.74%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.74%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.74%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.74%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.74%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.74%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.74%   |
| Intel Wireless 7265                                                            | 1         | 0.74%   |
| Intel Wireless 3165                                                            | 1         | 0.74%   |
| Intel Wireless 3160                                                            | 1         | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 0.74%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.74%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 0.74%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 48%     |
| Realtek Semiconductor | 14        | 18.67%  |
| Qualcomm Atheros      | 13        | 17.33%  |
| MediaTek              | 3         | 4%      |
| Broadcom              | 3         | 4%      |
| Broadcom Limited      | 2         | 2.67%   |
| TP-Link               | 1         | 1.33%   |
| Sierra Wireless       | 1         | 1.33%   |
| Ralink Technology     | 1         | 1.33%   |
| ASUSTek Computer      | 1         | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 5         | 6.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 5.33%   |
| Intel Wireless 8260                                                     | 4         | 5.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 4%      |
| Intel Wireless 7260                                                     | 3         | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 2.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.67%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 2.67%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 2.67%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.67%   |
| TP-Link TL-WN722N v2                                                    | 1         | 1.33%   |
| Sierra Wireless EM7455                                                  | 1         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 1.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 1.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.33%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.33%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.33%   |
| Intel Wireless 7265                                                     | 1         | 1.33%   |
| Intel Wireless 3165                                                     | 1         | 1.33%   |
| Intel Wireless 3160                                                     | 1         | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.33%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.33%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.33%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.33%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.33%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.33%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.33%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 1.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.33%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.33%   |
| ASUS 802.11ac NIC                                                       | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 32        | 55.17%  |
| Intel                    | 10        | 17.24%  |
| Qualcomm Atheros         | 7         | 12.07%  |
| Marvell Technology Group | 4         | 6.9%    |
| Nvidia                   | 2         | 3.45%   |
| TP-Link                  | 1         | 1.72%   |
| Samsung Electronics      | 1         | 1.72%   |
| Broadcom                 | 1         | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 27        | 45%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 3.33%   |
| Intel Ethernet Connection I219-V                                               | 2         | 3.33%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 3.33%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 3.33%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.67%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 1.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.67%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.67%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 1.67%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 1.67%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.67%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.67%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 1.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.67%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.67%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 1.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.67%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.67%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 54.33%  |
| Ethernet | 57        | 44.88%  |
| Modem    | 1         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 72.37%  |
| Ethernet | 21        | 27.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 52        | 71.23%  |
| 1     | 19        | 26.03%  |
| 0     | 2         | 2.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 55        | 74.32%  |
| Yes  | 19        | 25.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 44.83%  |
| Realtek Semiconductor           | 6         | 10.34%  |
| Qualcomm Atheros Communications | 6         | 10.34%  |
| Broadcom                        | 4         | 6.9%    |
| IMC Networks                    | 3         | 5.17%   |
| Foxconn / Hon Hai               | 3         | 5.17%   |
| Cambridge Silicon Radio         | 3         | 5.17%   |
| Apple                           | 3         | 5.17%   |
| Lite-On Technology              | 1         | 1.72%   |
| Hewlett-Packard                 | 1         | 1.72%   |
| Dell                            | 1         | 1.72%   |
| ASUSTek Computer                | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 11        | 18.97%  |
| Realtek Bluetooth Radio                                                             | 5         | 8.62%   |
| Intel AX200 Bluetooth                                                               | 5         | 8.62%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 6.9%    |
| Intel AX201 Bluetooth                                                               | 4         | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 5.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 5.17%   |
| IMC Networks Wireless_Device                                                        | 2         | 3.45%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.72%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.72%   |
| Lite-On Wireless_Device                                                             | 1         | 1.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.72%   |
| Intel Bluetooth Device                                                              | 1         | 1.72%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.72%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.72%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.72%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.72%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.72%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.72%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.72%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.72%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.72%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 1.72%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.72%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.72%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 63.16%  |
| Nvidia                | 19        | 20%     |
| AMD                   | 11        | 11.58%  |
| Texas Instruments     | 1         | 1.05%   |
| Realtek Semiconductor | 1         | 1.05%   |
| Plantronics           | 1         | 1.05%   |
| FIFINE 683 Microphone | 1         | 1.05%   |
| C-Media Electronics   | 1         | 1.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 9.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 7.34%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 6.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 6.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 3.67%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 2.75%   |
| Nvidia Audio device                                                                               | 3         | 2.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.75%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 2.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.83%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.83%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.92%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.92%   |
| Plantronics BT600                                                                                 | 1         | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.92%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.92%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.92%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.92%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.92%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.92%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.92%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.92%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.92%   |
| FIFINE 683 Microphone FIFINE 683 Microphone                                                       | 1         | 0.92%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 1         | 0.92%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 0.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 22        | 25.58%  |
| Samsung Electronics | 18        | 20.93%  |
| Unknown             | 13        | 15.12%  |
| Kingston            | 9         | 10.47%  |
| Micron Technology   | 7         | 8.14%   |
| Crucial             | 5         | 5.81%   |
| Unknown (ABCD)      | 2         | 2.33%   |
| Smart               | 2         | 2.33%   |
| Corsair             | 2         | 2.33%   |
| Transcend           | 1         | 1.16%   |
| PNY                 | 1         | 1.16%   |
| Nanya Technology    | 1         | 1.16%   |
| Avant               | 1         | 1.16%   |
| 48spaces            | 1         | 1.16%   |
| Unknown             | 1         | 1.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                                  | 4         | 4.21%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 3.16%   |
| Unknown RAM Module 8GB SODIMM DDR3                                  | 2         | 2.11%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 2         | 2.11%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 2.11%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 2.11%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 2.11%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 2.11%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 2         | 2.11%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 2.11%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 2         | 2.11%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                          | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 1.05%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.05%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                         | 1         | 1.05%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 1.05%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s                  | 1         | 1.05%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 1         | 1.05%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s               | 1         | 1.05%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                        | 1         | 1.05%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 1.05%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT351S6AFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 1         | 1.05%   |
| SK hynix RAM HMCG66MEBSA095N 8GB SODIMM DDR5 4800MT/s               | 1         | 1.05%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 1.05%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.05%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 1.05%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 1.05%   |
| SK hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.05%   |
| SK hynix RAM 0000000000-00000 4GB SODIMM DDR4 2400MT/s              | 1         | 1.05%   |
| Samsung RAM Module 4GB SODIMM DDR2 667MT/s                          | 1         | 1.05%   |
| Samsung RAM M471B5773EB0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.05%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 1.05%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 1.05%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.05%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.05%   |
| Samsung RAM M471B1G73DHO-CH9 8GB SODIMM DDR3 1333MT/s               | 1         | 1.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s      | 1         | 1.05%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.05%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.05%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.05%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB SODIMM LPDDR4 2400MT/s              | 1         | 1.05%   |
| PNY RAM Module 8GB SODIMM DDR3 1333MT/s                             | 1         | 1.05%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 1         | 1.05%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                          | 1         | 1.05%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.05%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 1         | 1.05%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s               | 1         | 1.05%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 32        | 43.24%  |
| DDR4   | 28        | 37.84%  |
| DDR2   | 5         | 6.76%   |
| LPDDR4 | 4         | 5.41%   |
| DDR    | 2         | 2.7%    |
| SDRAM  | 1         | 1.35%   |
| DRAM   | 1         | 1.35%   |
| DDR5   | 1         | 1.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 71        | 95.95%  |
| Row Of Chips | 3         | 4.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 33        | 40.24%  |
| 4096  | 28        | 34.15%  |
| 2048  | 14        | 17.07%  |
| 1024  | 4         | 4.88%   |
| 16384 | 2         | 2.44%   |
| 32768 | 1         | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 17        | 21.79%  |
| 3200    | 15        | 19.23%  |
| 2400    | 8         | 10.26%  |
| 2667    | 7         | 8.97%   |
| 1333    | 7         | 8.97%   |
| Unknown | 7         | 8.97%   |
| 667     | 5         | 6.41%   |
| 2133    | 4         | 5.13%   |
| 1334    | 3         | 3.85%   |
| 4800    | 1         | 1.28%   |
| 4267    | 1         | 1.28%   |
| 4199    | 1         | 1.28%   |
| 1067    | 1         | 1.28%   |
| 166     | 1         | 1.28%   |

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
| Chicony Electronics                    | 12        | 21.43%  |
| Microdia                               | 6         | 10.71%  |
| Realtek Semiconductor                  | 5         | 8.93%   |
| Acer                                   | 5         | 8.93%   |
| Sunplus Innovation Technology          | 3         | 5.36%   |
| Quanta                                 | 3         | 5.36%   |
| Lite-On Technology                     | 3         | 5.36%   |
| IMC Networks                           | 3         | 5.36%   |
| Suyin                                  | 2         | 3.57%   |
| Silicon Motion                         | 2         | 3.57%   |
| Ricoh                                  | 2         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.57%   |
| Z-Star Microelectronics                | 1         | 1.79%   |
| Y Media                                | 1         | 1.79%   |
| Primax Electronics                     | 1         | 1.79%   |
| Luxvisions Innotech Limited            | 1         | 1.79%   |
| Logitech                               | 1         | 1.79%   |
| Lenovo                                 | 1         | 1.79%   |
| Goodong Industry                       | 1         | 1.79%   |
| Alcor Micro                            | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                        | 2         | 3.57%   |
| Quanta HD User Facing                               | 2         | 3.57%   |
| Chicony Integrated Camera                           | 2         | 3.57%   |
| Acer BisonCam, NB Pro                               | 2         | 3.57%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 1.79%   |
| Y Media USB Camera                                  | 1         | 1.79%   |
| Suyin Sony Visual Communication Camera              | 1         | 1.79%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.79%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.79%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 1.79%   |
| Silicon Motion Web Camera                           | 1         | 1.79%   |
| Ricoh USB2.0 Camera                                 | 1         | 1.79%   |
| Ricoh Integrated Webcam                             | 1         | 1.79%   |
| Realtek USB Camera                                  | 1         | 1.79%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.79%   |
| Realtek Integrated_Webcam_HD                        | 1         | 1.79%   |
| Realtek Integrated Webcam                           | 1         | 1.79%   |
| Realtek EasyCamera                                  | 1         | 1.79%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.79%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 1.79%   |
| Microdia Webcam Vitade AF                           | 1         | 1.79%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 1.79%   |
| Microdia Webcam                                     | 1         | 1.79%   |
| Microdia USB 2.0 Camera                             | 1         | 1.79%   |
| Microdia Laptop_Integrated_Webcam_2HDM              | 1         | 1.79%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.79%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 1.79%   |
| Logitech StreamCam                                  | 1         | 1.79%   |
| Lite-On Integrated Camera                           | 1         | 1.79%   |
| Lite-On HP HD Webcam                                | 1         | 1.79%   |
| Lite-On HP HD Camera                                | 1         | 1.79%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.79%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                 | 1         | 1.79%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.79%   |
| IMC Networks Integrated Camera                      | 1         | 1.79%   |
| Goodong Industry USB2.0 HD UVC WebCam               | 1         | 1.79%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.79%   |
| Chicony USB 2.0 Camera                              | 1         | 1.79%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 1.79%   |
| Chicony thinkpad t430s camera                       | 1         | 1.79%   |
| Chicony Sony Visual Communication Camera            | 1         | 1.79%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.79%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 1.79%   |
| Chicony HP HD Webcam                                | 1         | 1.79%   |
| Chicony HD User Facing                              | 1         | 1.79%   |
| Chicony 2.0M UVC WebCam                             | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 1.79%   |
| Alcor Micro USB 2.0 Camera                          | 1         | 1.79%   |
| Acer VGA Webcam                                     | 1         | 1.79%   |
| Acer SunplusIT INC. Integrated Camera               | 1         | 1.79%   |
| Acer BisonCam,NB Pro                                | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 50%     |
| Shenzhen Goodix Technology | 2         | 20%     |
| AuthenTec                  | 2         | 20%     |
| Upek                       | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 3         | 30%     |
| Validity Sensors VFS495 Fingerprint Reader   | 2         | 20%     |
| Shenzhen Goodix  FingerPrint Device          | 2         | 20%     |
| Upek TCS5B Fingerprint sensor                | 1         | 10%     |
| AuthenTec AES2810                            | 1         | 10%     |
| AuthenTec AES1660 Fingerprint Sensor         | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 2         | 50%     |
| Alcor Micro           | 1         | 25%     |
| Advanced Card Systems | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Broadcom 5880                                  | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 25%     |
| Advanced Card Systems ACR122U                  | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 48        | 64%     |
| 1     | 22        | 29.33%  |
| 2     | 4         | 5.33%   |
| 3     | 1         | 1.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 17        | 54.84%  |
| Fingerprint reader    | 10        | 32.26%  |
| Chipcard              | 3         | 9.68%   |
| Multimedia controller | 1         | 3.23%   |

