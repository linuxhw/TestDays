MX 20 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 20.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_20/Desktop/README.md) and [notebooks](/Dist/MX_20/Notebook/README.md).

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

Total: 82

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek  | PRIME H510M-A               | Desktop     | [4521c22268](https://linux-hardware.org/?probe=4521c22268) | Mar 06, 2022 |
| Acer     | Spin SP111-31               | Convertible | [21bfc2a904](https://linux-hardware.org/?probe=21bfc2a904) | Jan 16, 2022 |
| IBM      | 8183B2U                     | Desktop     | [d070680dfb](https://linux-hardware.org/?probe=d070680dfb) | Jan 14, 2022 |
| Gigabyte | F2A88X-UP4                  | Desktop     | [52e09bab91](https://linux-hardware.org/?probe=52e09bab91) | Jan 02, 2022 |
| HP       | 2000                        | Notebook    | [5d64fe5b92](https://linux-hardware.org/?probe=5d64fe5b92) | Jan 01, 2022 |
| Unknown  | Unknown                     | Notebook    | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| Dell     | Inspiron 3576               | Notebook    | [ad9fb758a6](https://linux-hardware.org/?probe=ad9fb758a6) | Nov 09, 2021 |
| Lenovo   | ThinkPad L520 78595VG       | Notebook    | [4aff5a6a0c](https://linux-hardware.org/?probe=4aff5a6a0c) | Oct 24, 2021 |
| Dell     | 00F82W A01                  | Desktop     | [08e803937e](https://linux-hardware.org/?probe=08e803937e) | Oct 18, 2021 |
| HP       | 21D0                        | Desktop     | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| Lenovo   | ThinkPad T530 2394CJ9       | Notebook    | [b36a94241d](https://linux-hardware.org/?probe=b36a94241d) | Oct 05, 2021 |
| Lenovo   | ThinkPad X1 Carbon 5th 2... | Notebook    | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Apple    | Mac-F22C86C8                | Mini pc     | [8699437e9e](https://linux-hardware.org/?probe=8699437e9e) | Oct 01, 2021 |
| Lenovo   | ThinkPad L490 20Q5S0PR00    | Notebook    | [bbf6b89f02](https://linux-hardware.org/?probe=bbf6b89f02) | Oct 01, 2021 |
| Acer     | Aspire 4820T                | Notebook    | [a91911ca90](https://linux-hardware.org/?probe=a91911ca90) | Oct 01, 2021 |
| ASRock   | H470M-ITX/ac                | Desktop     | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| Lenovo   | ThinkPad P51 20HJS0TP00     | Notebook    | [2774c819ea](https://linux-hardware.org/?probe=2774c819ea) | Sep 18, 2021 |
| Lenovo   | B40-45 20394                | Notebook    | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| HP       | Pavilion Laptop 15-eg0xx... | Notebook    | [e76ffa7805](https://linux-hardware.org/?probe=e76ffa7805) | Sep 06, 2021 |
| HP       | Spectre x360 Convertible... | Convertible | [3c5ac88729](https://linux-hardware.org/?probe=3c5ac88729) | Aug 08, 2021 |
| ASRock   | H170M Pro4                  | Desktop     | [f291edbc4a](https://linux-hardware.org/?probe=f291edbc4a) | Jul 18, 2021 |
| Dell     | Latitude 3340               | Notebook    | [c47b83476b](https://linux-hardware.org/?probe=c47b83476b) | Jul 12, 2021 |
| Gigabyte | H110M-S2H-CF                | Desktop     | [192043ebbd](https://linux-hardware.org/?probe=192043ebbd) | Jul 12, 2021 |
| Acer     | Aspire one                  | Notebook    | [2c266e91ae](https://linux-hardware.org/?probe=2c266e91ae) | Jul 09, 2021 |
| Dell     | 00F82W A01                  | Desktop     | [b85b636b73](https://linux-hardware.org/?probe=b85b636b73) | Jun 26, 2021 |
| Irbis    | TW94                        | Notebook    | [dc56e23810](https://linux-hardware.org/?probe=dc56e23810) | May 15, 2021 |
| ASUSTek  | TUF B450M-PRO GAMING        | Desktop     | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| Dell     | Latitude E6320              | Notebook    | [fa8bcef5a9](https://linux-hardware.org/?probe=fa8bcef5a9) | May 09, 2021 |
| MSI      | B450-A PRO MAX              | Desktop     | [506efba999](https://linux-hardware.org/?probe=506efba999) | May 02, 2021 |
| Lenovo   | ThinkPad T440s 20AQ007SG... | Notebook    | [73f2bd0075](https://linux-hardware.org/?probe=73f2bd0075) | Apr 16, 2021 |
| Lenovo   | ThinkPad T440s 20AQ007SG... | Notebook    | [75e60ebdf4](https://linux-hardware.org/?probe=75e60ebdf4) | Apr 16, 2021 |
| Lenovo   | ThinkPad E480 20KNCTO1WW    | Notebook    | [7159579bb8](https://linux-hardware.org/?probe=7159579bb8) | Apr 12, 2021 |
| ASRock   | B560M Pro4                  | Desktop     | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| ASUSTek  | G751JT                      | Notebook    | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| Lenovo   | Yoga 7 14ITL5 82BH          | Convertible | [6d6b869b27](https://linux-hardware.org/?probe=6d6b869b27) | Apr 08, 2021 |
| HP       | Falco                       | Notebook    | [9bb0bf9ac8](https://linux-hardware.org/?probe=9bb0bf9ac8) | Apr 07, 2021 |
| ASUSTek  | P5K-E                       | Desktop     | [f0c435ead1](https://linux-hardware.org/?probe=f0c435ead1) | Apr 01, 2021 |
| Dell     | 0W7H8C A02                  | Server      | [1a32b081a7](https://linux-hardware.org/?probe=1a32b081a7) | Mar 30, 2021 |
| Dell     | 0XR1GT A00                  | Desktop     | [04145c0b36](https://linux-hardware.org/?probe=04145c0b36) | Mar 29, 2021 |
| ASUSTek  | TUF B450M-PRO GAMING        | Desktop     | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| MSI      | MS-7210 100                 | Desktop     | [e8723eb58b](https://linux-hardware.org/?probe=e8723eb58b) | Mar 17, 2021 |
| HP       | ZBook 17 G6                 | Notebook    | [046176e590](https://linux-hardware.org/?probe=046176e590) | Mar 16, 2021 |
| Lenovo   | ThinkPad E425 1198CTO       | Notebook    | [67304f1ffa](https://linux-hardware.org/?probe=67304f1ffa) | Feb 22, 2021 |
| HP       | Mini 110-3500               | Notebook    | [bb5cf4031b](https://linux-hardware.org/?probe=bb5cf4031b) | Feb 13, 2021 |
| HP       | Notebook                    | Notebook    | [69f70d7a09](https://linux-hardware.org/?probe=69f70d7a09) | Feb 10, 2021 |
| MSI      | MAG B550M MORTAR WIFI       | Desktop     | [4789c5df48](https://linux-hardware.org/?probe=4789c5df48) | Feb 06, 2021 |
| Apple    | MacBook7,1                  | Notebook    | [a6324a9e06](https://linux-hardware.org/?probe=a6324a9e06) | Feb 05, 2021 |
| Clevo    | P170EM                      | Notebook    | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| HP       | Mini 110-3500               | Notebook    | [3c2a01636e](https://linux-hardware.org/?probe=3c2a01636e) | Jan 19, 2021 |
| HP       | 1905                        | Desktop     | [03a91e7ecc](https://linux-hardware.org/?probe=03a91e7ecc) | Nov 27, 2020 |
| HP       | ENVY Laptop 13-ba0xxx       | Notebook    | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| Acer     | Aspire E5-571G              | Notebook    | [7f5f7e9fff](https://linux-hardware.org/?probe=7f5f7e9fff) | Nov 17, 2020 |
| Lenovo   | IdeaPad 110-15IBR 80T7      | Notebook    | [470c0ca72b](https://linux-hardware.org/?probe=470c0ca72b) | Oct 23, 2020 |
| Dell     | Latitude 5175               | Tablet      | [5144248c79](https://linux-hardware.org/?probe=5144248c79) | Oct 19, 2020 |
| HP       | Compaq 8510p (KM229AV)      | Notebook    | [30634ffde6](https://linux-hardware.org/?probe=30634ffde6) | Oct 12, 2020 |
| HP       | Pavilion 15                 | Notebook    | [8e6632f1a3](https://linux-hardware.org/?probe=8e6632f1a3) | Oct 06, 2020 |
| Lenovo   | ThinkPad T400 2768WGB       | Notebook    | [995b1a3a3d](https://linux-hardware.org/?probe=995b1a3a3d) | Sep 29, 2020 |
| Lenovo   | ThinkPad T60 20085TG        | Notebook    | [31cd0f06c2](https://linux-hardware.org/?probe=31cd0f06c2) | Sep 16, 2020 |
| Teclast  | F5                          | Convertible | [1003072bc5](https://linux-hardware.org/?probe=1003072bc5) | Sep 06, 2020 |
| Samsung  | 350V5C/351V5C/3540VC/344... | Notebook    | [356bacc97a](https://linux-hardware.org/?probe=356bacc97a) | Aug 27, 2020 |
| Samsung  | 350V5C/351V5C/3540VC/344... | Notebook    | [f16c9341a8](https://linux-hardware.org/?probe=f16c9341a8) | Aug 21, 2020 |
| Acer     | Aspire A114-32              | Notebook    | [7f178a7089](https://linux-hardware.org/?probe=7f178a7089) | Aug 20, 2020 |
| Samsung  | 350V5C/351V5C/3540VC/344... | Notebook    | [9b4d2c057e](https://linux-hardware.org/?probe=9b4d2c057e) | Aug 19, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | Notebook    | [57e274292b](https://linux-hardware.org/?probe=57e274292b) | Aug 16, 2020 |
| HP       | ProLiant DL380 G6           | Server      | [e01126d9bd](https://linux-hardware.org/?probe=e01126d9bd) | Aug 06, 2020 |
| HP       | ProLiant DL380 G6           | Server      | [7a48a3ced3](https://linux-hardware.org/?probe=7a48a3ced3) | Aug 06, 2020 |
| HP       | ProBook 650 G1              | Notebook    | [9a488079c3](https://linux-hardware.org/?probe=9a488079c3) | Jul 23, 2020 |
| Lenovo   | ThinkPad T440s 20AQ006HU... | Notebook    | [54a69351ae](https://linux-hardware.org/?probe=54a69351ae) | Jun 17, 2020 |
| Sony     | VGN-NR310FH                 | Notebook    | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| Acer     | Aspire A315-41              | Notebook    | [665b2837c7](https://linux-hardware.org/?probe=665b2837c7) | May 27, 2020 |
| ASUSTek  | VivoBook_ASUSLaptop X712... | Notebook    | [c85746245d](https://linux-hardware.org/?probe=c85746245d) | May 26, 2020 |
| Lenovo   | B590 20206                  | Notebook    | [8f4a7e2b6e](https://linux-hardware.org/?probe=8f4a7e2b6e) | May 26, 2020 |
| Lenovo   | MIIX 3-1030 80HV            | Tablet      | [34335c5fb5](https://linux-hardware.org/?probe=34335c5fb5) | Apr 24, 2020 |
| Dell     | Latitude 3390 2-in-1        | Convertible | [60ae29c5ac](https://linux-hardware.org/?probe=60ae29c5ac) | Apr 04, 2020 |
| ASUSTek  | Z97-E                       | Desktop     | [42c2810369](https://linux-hardware.org/?probe=42c2810369) | Apr 03, 2020 |
| MSI      | 760GM-P23                   | Desktop     | [67de432cb4](https://linux-hardware.org/?probe=67de432cb4) | Apr 01, 2020 |
| Gigabyte | Z390 GAMING X-CF            | Desktop     | [104b035076](https://linux-hardware.org/?probe=104b035076) | Apr 01, 2020 |
| ASUSTek  | X455LAB                     | Notebook    | [4a5174a726](https://linux-hardware.org/?probe=4a5174a726) | Mar 24, 2020 |
| Notebook | W65_W67RZ1                  | Notebook    | [aaffd10ebf](https://linux-hardware.org/?probe=aaffd10ebf) | Mar 24, 2020 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | Desktop     | [1243c4a0d9](https://linux-hardware.org/?probe=1243c4a0d9) | Mar 24, 2020 |
| HP       | 1790                        | Desktop     | [68a167efd3](https://linux-hardware.org/?probe=68a167efd3) | Mar 24, 2020 |
| Medion   | AKOYA E1318T                | Notebook    | [d6be35c8af](https://linux-hardware.org/?probe=d6be35c8af) | Mar 20, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 4.19.0-6-amd64             | 13        | 17.57%  |
| 5.10.0-5mx-amd64           | 9         | 12.16%  |
| 5.8.0-3-amd64              | 6         | 8.11%   |
| 4.19.0-17-amd64            | 5         | 6.76%   |
| 4.19.0-16-amd64            | 5         | 6.76%   |
| 5.6.0-2-amd64              | 4         | 5.41%   |
| 4.19.0-11-amd64            | 3         | 4.05%   |
| 5.5.0-9.1-liquorix-amd64   | 2         | 2.7%    |
| 5.10.0-8mx-amd64           | 2         | 2.7%    |
| 4.19.0-14-amd64            | 2         | 2.7%    |
| 4.19.0-12-amd64            | 2         | 2.7%    |
| 4.19.0-10-amd64            | 2         | 2.7%    |
| 5.8.16-antix.1-amd64-smp   | 1         | 1.35%   |
| 5.6.0-15.2-liquorix-amd64  | 1         | 1.35%   |
| 5.6.0-12.1-liquorix-amd64  | 1         | 1.35%   |
| 5.5.0-5.1-liquorix-amd64   | 1         | 1.35%   |
| 5.4.7-antix.1-amd64-smp    | 1         | 1.35%   |
| 5.4.0-3-amd64              | 1         | 1.35%   |
| 5.15.0-1mx-amd64           | 1         | 1.35%   |
| 5.11.0-16.1-liquorix-amd64 | 1         | 1.35%   |
| 5.10.0-6.2-liquorix-amd64  | 1         | 1.35%   |
| 5.10.0-4mx-amd64           | 1         | 1.35%   |
| 5.10.0-10mx-amd64          | 1         | 1.35%   |
| 4.19.174                   | 1         | 1.35%   |
| 4.19.0-9-amd64             | 1         | 1.35%   |
| 4.19.0-9-686-pae           | 1         | 1.35%   |
| 4.19.0-18-amd64            | 1         | 1.35%   |
| 4.19.0-17-686-pae          | 1         | 1.35%   |
| 4.19.0-16-686-pae          | 1         | 1.35%   |
| 4.19.0-13-amd64            | 1         | 1.35%   |
| 4.19.0-10-686-pae          | 1         | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.19.0   | 39        | 52.7%   |
| 5.10.0   | 14        | 18.92%  |
| 5.8.0    | 6         | 8.11%   |
| 5.6.0    | 6         | 8.11%   |
| 5.5.0    | 3         | 4.05%   |
| 5.8.16   | 1         | 1.35%   |
| 5.4.7    | 1         | 1.35%   |
| 5.4.0    | 1         | 1.35%   |
| 5.15.0   | 1         | 1.35%   |
| 5.11.0   | 1         | 1.35%   |
| 4.19.174 | 1         | 1.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 40        | 54.05%  |
| 5.10    | 14        | 18.92%  |
| 5.8     | 7         | 9.46%   |
| 5.6     | 6         | 8.11%   |
| 5.5     | 3         | 4.05%   |
| 5.4     | 2         | 2.7%    |
| 5.15    | 1         | 1.35%   |
| 5.11    | 1         | 1.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 68        | 94.44%  |
| i686   | 4         | 5.56%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| XFCE     | 56        | 77.78%  |
| KDE5     | 9         | 12.5%   |
| i3       | 2         | 2.78%   |
| Trinity  | 1         | 1.39%   |
| spectrwm | 1         | 1.39%   |
| MATE     | 1         | 1.39%   |
| LXQt     | 1         | 1.39%   |
| Budgie   | 1         | 1.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 71        | 98.61%  |
| Tty  | 1         | 1.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 63        | 87.5%   |
| SDDM    | 7         | 9.72%   |
| TDM     | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 43        | 58.9%   |
| en_US   | 16        | 21.92%  |
| es_ES   | 5         | 6.85%   |
| en_GB   | 2         | 2.74%   |
| de_DE   | 2         | 2.74%   |
| ru_RU   | 1         | 1.37%   |
| it_IT   | 1         | 1.37%   |
| es_VE   | 1         | 1.37%   |
| es_CO   | 1         | 1.37%   |
| en_IE   | 1         | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 38        | 52.78%  |
| BIOS | 34        | 47.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 65        | 90.28%  |
| Overlay | 5         | 6.94%   |
| Xfs     | 1         | 1.39%   |
| Btrfs   | 1         | 1.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 44        | 61.11%  |
| MBR  | 28        | 38.89%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 78.38%  |
| Yes       | 16        | 21.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 62.5%   |
| Yes       | 27        | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 15        | 20.83%  |
| Hewlett-Packard     | 15        | 20.83%  |
| Dell                | 8         | 11.11%  |
| ASUSTek Computer    | 7         | 9.72%   |
| Acer                | 6         | 8.33%   |
| MSI                 | 4         | 5.56%   |
| Gigabyte Technology | 4         | 5.56%   |
| ASRock              | 3         | 4.17%   |
| Apple               | 2         | 2.78%   |
| Teclast             | 1         | 1.39%   |
| Sony                | 1         | 1.39%   |
| Notebook            | 1         | 1.39%   |
| Medion              | 1         | 1.39%   |
| Irbis               | 1         | 1.39%   |
| IBM                 | 1         | 1.39%   |
| Clevo               | 1         | 1.39%   |
| Unknown             | 1         | 1.39%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Teclast F5                               | 1         | 1.39%   |
| Sony VGN-NR310FH                         | 1         | 1.39%   |
| Notebook W65_W67RZ1                      | 1         | 1.39%   |
| MSI MS-7C94                              | 1         | 1.39%   |
| MSI MS-7B86                              | 1         | 1.39%   |
| MSI MS-7641                              | 1         | 1.39%   |
| MSI GEG                                  | 1         | 1.39%   |
| Medion AKOYA E1318T                      | 1         | 1.39%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR0013AU | 1         | 1.39%   |
| Lenovo ThinkPad T60 20085TG              | 1         | 1.39%   |
| Lenovo ThinkPad T530 2394CJ9             | 1         | 1.39%   |
| Lenovo ThinkPad T440s 20AQ007SGE         | 1         | 1.39%   |
| Lenovo ThinkPad T440s 20AQ006HUS         | 1         | 1.39%   |
| Lenovo ThinkPad T400 2768WGB             | 1         | 1.39%   |
| Lenovo ThinkPad P51 20HJS0TP00           | 1         | 1.39%   |
| Lenovo ThinkPad L520 78595VG             | 1         | 1.39%   |
| Lenovo ThinkPad L490 20Q5S0PR00          | 1         | 1.39%   |
| Lenovo ThinkPad E480 20KNCTO1WW          | 1         | 1.39%   |
| Lenovo ThinkPad E425 1198CTO             | 1         | 1.39%   |
| Lenovo MIIX 3-1030 80HV                  | 1         | 1.39%   |
| Lenovo IdeaPad 110-15IBR 80T7            | 1         | 1.39%   |
| Lenovo B590 20206                        | 1         | 1.39%   |
| Lenovo B40-45 20394                      | 1         | 1.39%   |
| Irbis TW94                               | 1         | 1.39%   |
| IBM 8183B2U                              | 1         | 1.39%   |
| HP ZBook 17 G6                           | 1         | 1.39%   |
| HP Z230 Tower Workstation                | 1         | 1.39%   |
| HP Z220 CMT Workstation                  | 1         | 1.39%   |
| HP Spectre x360 Convertible 13-ae0xx     | 1         | 1.39%   |
| HP ProLiant DL380 G6                     | 1         | 1.39%   |
| HP ProDesk 600 G1 DM                     | 1         | 1.39%   |
| HP ProBook 650 G1                        | 1         | 1.39%   |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 1.39%   |
| HP Pavilion 15                           | 1         | 1.39%   |
| HP Notebook                              | 1         | 1.39%   |
| HP Mini 110-3500                         | 1         | 1.39%   |
| HP Falco                                 | 1         | 1.39%   |
| HP ENVY Laptop 13-ba0xxx                 | 1         | 1.39%   |
| HP Compaq 8510p (KM229AV)                | 1         | 1.39%   |
| HP 2000                                  | 1         | 1.39%   |
| Gigabyte Z390 GAMING X                   | 1         | 1.39%   |
| Gigabyte X470 AORUS ULTRA GAMING         | 1         | 1.39%   |
| Gigabyte H110M-S2H                       | 1         | 1.39%   |
| Gigabyte F2A88X-UP4                      | 1         | 1.39%   |
| Dell PowerEdge T320                      | 1         | 1.39%   |
| Dell OptiPlex 9010                       | 1         | 1.39%   |
| Dell Latitude E6320                      | 1         | 1.39%   |
| Dell Latitude 5175                       | 1         | 1.39%   |
| Dell Latitude 3390 2-in-1                | 1         | 1.39%   |
| Dell Latitude 3340                       | 1         | 1.39%   |
| Dell Inspiron 660                        | 1         | 1.39%   |
| Dell Inspiron 3576                       | 1         | 1.39%   |
| Clevo P170EM                             | 1         | 1.39%   |
| ASUS X455LAB                             | 1         | 1.39%   |
| ASUS VivoBook_ASUSLaptop X712DA_M712DA   | 1         | 1.39%   |
| ASUS VivoBook 15_ASUS Laptop X542UF      | 1         | 1.39%   |
| ASUS TUF B450M-PRO GAMING                | 1         | 1.39%   |
| ASUS PRIME H510M-A                       | 1         | 1.39%   |
| ASUS P5K-E                               | 1         | 1.39%   |
| ASUS All Series                          | 1         | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 11        | 15.28%  |
| Acer Aspire         | 5         | 6.94%   |
| Dell Latitude       | 4         | 5.56%   |
| HP Pavilion         | 2         | 2.78%   |
| Dell Inspiron       | 2         | 2.78%   |
| ASUS VivoBook       | 2         | 2.78%   |
| Teclast F5          | 1         | 1.39%   |
| Sony VGN-NR310FH    | 1         | 1.39%   |
| Notebook W65        | 1         | 1.39%   |
| MSI MS-7C94         | 1         | 1.39%   |
| MSI MS-7B86         | 1         | 1.39%   |
| MSI MS-7641         | 1         | 1.39%   |
| MSI GEG             | 1         | 1.39%   |
| Medion AKOYA        | 1         | 1.39%   |
| Lenovo MIIX         | 1         | 1.39%   |
| Lenovo IdeaPad      | 1         | 1.39%   |
| Lenovo B590         | 1         | 1.39%   |
| Lenovo B40-45       | 1         | 1.39%   |
| Irbis TW94          | 1         | 1.39%   |
| IBM 8183B2U         | 1         | 1.39%   |
| HP ZBook            | 1         | 1.39%   |
| HP Z230             | 1         | 1.39%   |
| HP Z220             | 1         | 1.39%   |
| HP Spectre          | 1         | 1.39%   |
| HP ProLiant         | 1         | 1.39%   |
| HP ProDesk          | 1         | 1.39%   |
| HP ProBook          | 1         | 1.39%   |
| HP Notebook         | 1         | 1.39%   |
| HP Mini             | 1         | 1.39%   |
| HP Falco            | 1         | 1.39%   |
| HP ENVY             | 1         | 1.39%   |
| HP Compaq           | 1         | 1.39%   |
| HP 2000             | 1         | 1.39%   |
| Gigabyte Z390       | 1         | 1.39%   |
| Gigabyte X470       | 1         | 1.39%   |
| Gigabyte H110M-S2H  | 1         | 1.39%   |
| Gigabyte F2A88X-UP4 | 1         | 1.39%   |
| Dell PowerEdge      | 1         | 1.39%   |
| Dell OptiPlex       | 1         | 1.39%   |
| Clevo P170EM        | 1         | 1.39%   |
| ASUS X455LAB        | 1         | 1.39%   |
| ASUS TUF            | 1         | 1.39%   |
| ASUS PRIME          | 1         | 1.39%   |
| ASUS P5K-E          | 1         | 1.39%   |
| ASUS All            | 1         | 1.39%   |
| ASRock H470M-ITX    | 1         | 1.39%   |
| ASRock H170M        | 1         | 1.39%   |
| ASRock B560M        | 1         | 1.39%   |
| Apple Macmini3      | 1         | 1.39%   |
| Apple MacBook7      | 1         | 1.39%   |
| Acer Spin           | 1         | 1.39%   |
| Unknown             | 1         | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2014 | 11        | 15.28%  |
| 2018 | 8         | 11.11%  |
| 2019 | 7         | 9.72%   |
| 2017 | 6         | 8.33%   |
| 2013 | 6         | 8.33%   |
| 2012 | 6         | 8.33%   |
| 2020 | 4         | 5.56%   |
| 2011 | 4         | 5.56%   |
| 2010 | 4         | 5.56%   |
| 2008 | 4         | 5.56%   |
| 2016 | 3         | 4.17%   |
| 2021 | 2         | 2.78%   |
| 2015 | 2         | 2.78%   |
| 2006 | 2         | 2.78%   |
| 2009 | 1         | 1.39%   |
| 2007 | 1         | 1.39%   |
| 2005 | 1         | 1.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 42        | 58.33%  |
| Desktop     | 21        | 29.17%  |
| Convertible | 4         | 5.56%   |
| Tablet      | 2         | 2.78%   |
| Server      | 2         | 2.78%   |
| Mini pc     | 1         | 1.39%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 72        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 71        | 98.61%  |
| Yes  | 1         | 1.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 22.22%  |
| 3.01-4.0   | 14        | 19.44%  |
| 8.01-16.0  | 13        | 18.06%  |
| 16.01-24.0 | 12        | 16.67%  |
| 1.01-2.0   | 7         | 9.72%   |
| 32.01-64.0 | 5         | 6.94%   |
| 24.01-32.0 | 3         | 4.17%   |
| 2.01-3.0   | 2         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 30        | 40.54%  |
| 3.01-4.0  | 13        | 17.57%  |
| 2.01-3.0  | 13        | 17.57%  |
| 4.01-8.0  | 8         | 10.81%  |
| 0.51-1.0  | 8         | 10.81%  |
| 8.01-16.0 | 2         | 2.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 65.75%  |
| 2      | 13        | 17.81%  |
| 3      | 7         | 9.59%   |
| 5      | 2         | 2.74%   |
| 4      | 2         | 2.74%   |
| 0      | 1         | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 56.94%  |
| Yes       | 31        | 43.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 87.5%   |
| No        | 9         | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 80.56%  |
| No        | 14        | 19.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 55.56%  |
| No        | 32        | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 18        | 25%     |
| Germany     | 7         | 9.72%   |
| Spain       | 6         | 8.33%   |
| Russia      | 4         | 5.56%   |
| India       | 4         | 5.56%   |
| Canada      | 3         | 4.17%   |
| UK          | 2         | 2.78%   |
| Sweden      | 2         | 2.78%   |
| Netherlands | 2         | 2.78%   |
| Mexico      | 2         | 2.78%   |
| Italy       | 2         | 2.78%   |
| Finland     | 2         | 2.78%   |
| Vietnam     | 1         | 1.39%   |
| Venezuela   | 1         | 1.39%   |
| Turkey      | 1         | 1.39%   |
| Syria       | 1         | 1.39%   |
| Serbia      | 1         | 1.39%   |
| Portugal    | 1         | 1.39%   |
| Poland      | 1         | 1.39%   |
| Philippines | 1         | 1.39%   |
| Norway      | 1         | 1.39%   |
| Indonesia   | 1         | 1.39%   |
| Hungary     | 1         | 1.39%   |
| France      | 1         | 1.39%   |
| Denmark     | 1         | 1.39%   |
| Czechia     | 1         | 1.39%   |
| Colombia    | 1         | 1.39%   |
| Brazil      | 1         | 1.39%   |
| Australia   | 1         | 1.39%   |
| Angola      | 1         | 1.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Madrid                    | 3         | 4.05%   |
| Asansol                   | 3         | 4.05%   |
| Wadsworth                 | 1         | 1.35%   |
| Tuusula                   | 1         | 1.35%   |
| Trivandrum                | 1         | 1.35%   |
| Torrevieja                | 1         | 1.35%   |
| Torquay                   | 1         | 1.35%   |
| Tobyhanna                 | 1         | 1.35%   |
| Tampa                     | 1         | 1.35%   |
| Stockholm                 | 1         | 1.35%   |
| SÃ¶dertÃ¤lje          | 1         | 1.35%   |
| Rensselaer                | 1         | 1.35%   |
| Prague                    | 1         | 1.35%   |
| Porto                     | 1         | 1.35%   |
| Podolsk                   | 1         | 1.35%   |
| Pocono Summit             | 1         | 1.35%   |
| Piszczac                  | 1         | 1.35%   |
| Perm                      | 1         | 1.35%   |
| Ooltewah                  | 1         | 1.35%   |
| Omsk                      | 1         | 1.35%   |
| Oakland                   | 1         | 1.35%   |
| Nuremberg                 | 1         | 1.35%   |
| Novi Knezevac             | 1         | 1.35%   |
| Nashville                 | 1         | 1.35%   |
| Munich                    | 1         | 1.35%   |
| Montreal                  | 1         | 1.35%   |
| Monterrey                 | 1         | 1.35%   |
| Milan                     | 1         | 1.35%   |
| Mexico City               | 1         | 1.35%   |
| Meriden                   | 1         | 1.35%   |
| Mechanicsburg             | 1         | 1.35%   |
| MÃ¼nster                | 1         | 1.35%   |
| Marbella                  | 1         | 1.35%   |
| Manado                    | 1         | 1.35%   |
| Madison                   | 1         | 1.35%   |
| Luanda                    | 1         | 1.35%   |
| Los Puertos de Altagracia | 1         | 1.35%   |
| Los Angeles               | 1         | 1.35%   |
| Lobnya                    | 1         | 1.35%   |
| Lille                     | 1         | 1.35%   |
| Leipzig                   | 1         | 1.35%   |
| Lebanon                   | 1         | 1.35%   |
| Kreuztal                  | 1         | 1.35%   |
| Kent                      | 1         | 1.35%   |
| Kartal                    | 1         | 1.35%   |
| Iowa City                 | 1         | 1.35%   |
| Huntsville                | 1         | 1.35%   |
| Ho Chi Minh City          | 1         | 1.35%   |
| Hendon                    | 1         | 1.35%   |
| Helsinki                  | 1         | 1.35%   |
| Gargan                    | 1         | 1.35%   |
| Damascus                  | 1         | 1.35%   |
| Comox                     | 1         | 1.35%   |
| Chesapeake                | 1         | 1.35%   |
| Cebu City                 | 1         | 1.35%   |
| Carl Junction             | 1         | 1.35%   |
| Caldicot                  | 1         | 1.35%   |
| Budapest                  | 1         | 1.35%   |
| Breedenbroek              | 1         | 1.35%   |
| BogotÃ¡                 | 1         | 1.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 20     | 17%     |
| Samsung Electronics | 16        | 22     | 16%     |
| Seagate             | 15        | 20     | 15%     |
| Kingston            | 8         | 8      | 8%      |
| SanDisk             | 6         | 6      | 6%      |
| Hitachi             | 5         | 6      | 5%      |
| Toshiba             | 4         | 5      | 4%      |
| HGST                | 3         | 3      | 3%      |
| A-DATA Technology   | 3         | 3      | 3%      |
| Unknown             | 2         | 2      | 2%      |
| SPCC                | 2         | 2      | 2%      |
| SK Hynix            | 2         | 2      | 2%      |
| Intel               | 2         | 2      | 2%      |
| Crucial             | 2         | 2      | 2%      |
| Yeyian              | 1         | 1      | 1%      |
| WDC WDS1            | 1         | 1      | 1%      |
| Teclast             | 1         | 1      | 1%      |
| PNY                 | 1         | 1      | 1%      |
| LITEON              | 1         | 1      | 1%      |
| Lenovo              | 1         | 1      | 1%      |
| Intenso             | 1         | 1      | 1%      |
| Indilinx            | 1         | 2      | 1%      |
| HUAWEI              | 1         | 1      | 1%      |
| HS-SSD-C100         | 1         | 1      | 1%      |
| GOODRAM             | 1         | 1      | 1%      |
| Gigabyte Technology | 1         | 1      | 1%      |
| Fujitsu             | 1         | 1      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 3         | 2.75%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2         | 1.83%   |
| SK Hynix SC311 SATA 256GB SSD        | 2         | 1.83%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 1.83%   |
| Yeyian VALK 1000 120GB               | 1         | 0.92%   |
| WDC WDS500G2B0A 500GB SSD            | 1         | 0.92%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD     | 1         | 0.92%   |
| WDC WDS250G2B0A-00SM50 250GB SSD     | 1         | 0.92%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.92%   |
| WDC WDS1 20G2G0A-00JH30 120GB SSD    | 1         | 0.92%   |
| WDC WD800JD-00MSA1 80GB              | 1         | 0.92%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.92%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.92%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 0.92%   |
| WDC WD3200LPVT-08G33T1 320GB         | 1         | 0.92%   |
| WDC WD3200AAJS-00L7A0 320GB          | 1         | 0.92%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.92%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.92%   |
| WDC WD10SPZX-80Z10T2 1TB             | 1         | 0.92%   |
| WDC WD10EADS-65M2B0 1TB              | 1         | 0.92%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.92%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB | 1         | 0.92%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB | 1         | 0.92%   |
| Unknown SDW32G  32GB                 | 1         | 0.92%   |
| Unknown 064G30  64GB                 | 1         | 0.92%   |
| Toshiba THNSFJ256GCSU 256GB SSD      | 1         | 0.92%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.92%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB    | 1         | 0.92%   |
| Toshiba DT01ACA050 500GB             | 1         | 0.92%   |
| Teclast 256GB NS550-2242 SSD         | 1         | 0.92%   |
| SPCC Solid State Disk 512GB          | 1         | 0.92%   |
| SPCC Solid State Disk 240GB          | 1         | 0.92%   |
| Seagate ST9500420AS 500GB            | 1         | 0.92%   |
| Seagate ST9500325AS 500GB            | 1         | 0.92%   |
| Seagate ST500NM0011 500GB            | 1         | 0.92%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 0.92%   |
| Seagate ST3750330NS 752GB            | 1         | 0.92%   |
| Seagate ST3500830AS 500GB            | 1         | 0.92%   |
| Seagate ST3320620AS 320GB            | 1         | 0.92%   |
| Seagate ST31500341AS 1TB             | 1         | 0.92%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 0.92%   |
| Seagate ST2000DX001-1CM164 2TB       | 1         | 0.92%   |
| Seagate ST2000DM001-1CH164 2TB       | 1         | 0.92%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 0.92%   |
| Seagate BUP BK 4TB                   | 1         | 0.92%   |
| Seagate Backup+ Desk 5TB             | 1         | 0.92%   |
| SanDisk SSD PLUS 480G                | 1         | 0.92%   |
| SanDisk SSD PLUS 1000GB              | 1         | 0.92%   |
| SanDisk SSD G5 BICS4 500GB           | 1         | 0.92%   |
| SanDisk SDSSDHII120G 120GB           | 1         | 0.92%   |
| SanDisk SDSSDA120G 120GB             | 1         | 0.92%   |
| SanDisk DF4064  64GB                 | 1         | 0.92%   |
| Samsung SSD 970 EVO Plus 500GB       | 1         | 0.92%   |
| Samsung SSD 870 EVO 500GB            | 1         | 0.92%   |
| Samsung SSD 870 EVO 1TB              | 1         | 0.92%   |
| Samsung SSD 860 QVO 1TB              | 1         | 0.92%   |
| Samsung SSD 860 EVO mSATA 500GB      | 1         | 0.92%   |
| Samsung SSD 860 EVO M.2 250GB        | 1         | 0.92%   |
| Samsung SSD 860 EVO 250GB            | 1         | 0.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 19     | 40.54%  |
| WDC     | 11        | 12     | 29.73%  |
| Hitachi | 5         | 6      | 13.51%  |
| HGST    | 3         | 3      | 8.11%   |
| Toshiba | 2         | 3      | 5.41%   |
| Fujitsu | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 17     | 25%     |
| Kingston            | 7         | 7      | 14.58%  |
| SanDisk             | 5         | 5      | 10.42%  |
| WDC                 | 4         | 5      | 8.33%   |
| SPCC                | 2         | 2      | 4.17%   |
| SK Hynix            | 2         | 2      | 4.17%   |
| Crucial             | 2         | 2      | 4.17%   |
| A-DATA Technology   | 2         | 2      | 4.17%   |
| Yeyian              | 1         | 1      | 2.08%   |
| WDC WDS1            | 1         | 1      | 2.08%   |
| Toshiba             | 1         | 1      | 2.08%   |
| Teclast             | 1         | 1      | 2.08%   |
| PNY                 | 1         | 1      | 2.08%   |
| LITEON              | 1         | 1      | 2.08%   |
| Intenso             | 1         | 1      | 2.08%   |
| Intel               | 1         | 1      | 2.08%   |
| Indilinx            | 1         | 2      | 2.08%   |
| HS-SSD-C100         | 1         | 1      | 2.08%   |
| GOODRAM             | 1         | 1      | 2.08%   |
| Gigabyte Technology | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 40        | 55     | 44.44%  |
| HDD     | 33        | 44     | 36.67%  |
| NVMe    | 12        | 13     | 13.33%  |
| MMC     | 3         | 3      | 3.33%   |
| Unknown | 2         | 2      | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 60        | 97     | 75.95%  |
| NVMe | 12        | 13     | 15.19%  |
| SAS  | 4         | 4      | 5.06%   |
| MMC  | 3         | 3      | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 52        | 73     | 70.27%  |
| 0.51-1.0   | 13        | 14     | 17.57%  |
| 1.01-2.0   | 6         | 7      | 8.11%   |
| 3.01-4.0   | 2         | 3      | 2.7%    |
| 2.01-3.0   | 1         | 2      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 20        | 27.4%   |
| 101-250        | 19        | 26.03%  |
| 51-100         | 10        | 13.7%   |
| 501-1000       | 7         | 9.59%   |
| 21-50          | 6         | 8.22%   |
| More than 3000 | 4         | 5.48%   |
| 1001-2000      | 3         | 4.11%   |
| 1-20           | 3         | 4.11%   |
| 2001-3000      | 1         | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 34.72%  |
| 21-50          | 12        | 16.67%  |
| 51-100         | 11        | 15.28%  |
| 101-250        | 10        | 13.89%  |
| 251-500        | 6         | 8.33%   |
| 501-1000       | 4         | 5.56%   |
| More than 3000 | 3         | 4.17%   |
| 2001-3000      | 1         | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-22ZCT0 160GB      | 1         | 1      | 8.33%   |
| SPCC Solid State Disk 512GB      | 1         | 1      | 8.33%   |
| Seagate ST9500420AS 500GB        | 1         | 1      | 8.33%   |
| Seagate ST9500325AS 500GB        | 1         | 1      | 8.33%   |
| Seagate ST3750330NS 752GB        | 1         | 1      | 8.33%   |
| Seagate ST31500341AS 1TB         | 1         | 1      | 8.33%   |
| Seagate ST1000LM035-1RK172 1TB   | 1         | 1      | 8.33%   |
| Indilinx IND-S325S120G 120GB SSD | 1         | 2      | 8.33%   |
| Hitachi HTS542516K9SA00 160GB    | 1         | 1      | 8.33%   |
| HGST HTS545050A7E680 500GB       | 1         | 1      | 8.33%   |
| HGST HTS545032A7E380 320GB       | 1         | 1      | 8.33%   |
| Fujitsu MHZ2160BH G2 160GB       | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 5      | 41.67%  |
| HGST     | 2         | 2      | 16.67%  |
| WDC      | 1         | 1      | 8.33%   |
| SPCC     | 1         | 1      | 8.33%   |
| Indilinx | 1         | 2      | 8.33%   |
| Hitachi  | 1         | 1      | 8.33%   |
| Fujitsu  | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 50%     |
| HGST    | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 83.33%  |
| SSD  | 2         | 3      | 16.67%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 61        | 97     | 76.25%  |
| Malfunc  | 12        | 13     | 15%     |
| Detected | 7         | 7      | 8.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 50        | 64.1%   |
| AMD                          | 13        | 16.67%  |
| Samsung Electronics          | 4         | 5.13%   |
| Sandisk                      | 3         | 3.85%   |
| Nvidia                       | 2         | 2.56%   |
| Toshiba America Info Systems | 1         | 1.28%   |
| Lenovo                       | 1         | 1.28%   |
| Kingston Technology Company  | 1         | 1.28%   |
| JMicron Technology           | 1         | 1.28%   |
| Hewlett-Packard              | 1         | 1.28%   |
| ADATA Technology             | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 11.24%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 4.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 4.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 4.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 3.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 3.37%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 3.37%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 2.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 2.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 2.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 2.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 2.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2         | 2.25%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 2.25%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 1.12%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 1.12%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 1.12%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.12%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 1.12%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 1.12%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 1.12%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.12%   |
| Intel SSD 660P Series                                                            | 1         | 1.12%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.12%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.12%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 1         | 1.12%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                         | 1         | 1.12%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.12%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 1.12%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 1.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.12%   |
| Intel 82801EB (ICH5) SATA Controller                                             | 1         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.12%   |
| HP Smart Array G6 controllers                                                    | 1         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.12%   |
| AMD 500 Series Chipset SATA Controller                                           | 1         | 1.12%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.12%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 57        | 68.67%  |
| NVMe | 11        | 13.25%  |
| IDE  | 10        | 12.05%  |
| RAID | 5         | 6.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 59        | 81.94%  |
| AMD    | 13        | 18.06%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 4.17%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 2.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.78%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 2.78%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 2.78%   |
| Intel Xeon CPU X5550 @ 2.67GHz                | 1         | 1.39%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz            | 1         | 1.39%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz           | 1         | 1.39%   |
| Intel Pentium D CPU 3.40GHz                   | 1         | 1.39%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 1.39%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.39%   |
| Intel Pentium CPU G3240T @ 2.70GHz            | 1         | 1.39%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 1.39%   |
| Intel Pentium 4 CPU 3.20GHz                   | 1         | 1.39%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 1.39%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 1.39%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 1.39%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.39%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.39%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 1.39%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.39%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.39%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 1.39%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 1         | 1.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.39%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 1.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.39%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 1         | 1.39%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 1         | 1.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.39%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 1.39%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 1         | 1.39%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 1.39%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 1.39%   |
| Intel Core Duo CPU T2500 @ 2.00GHz            | 1         | 1.39%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 1.39%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 1         | 1.39%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz          | 1         | 1.39%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 1.39%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.39%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.39%   |
| Intel Celeron CPU 550 @ 2.00GHz               | 1         | 1.39%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 1.39%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 1.39%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 1         | 1.39%   |
| Intel Atom CPU N550 @ 1.50GHz                 | 1         | 1.39%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 1.39%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz        | 1         | 1.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.39%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 1         | 1.39%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 1.39%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.39%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1         | 1.39%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 1         | 1.39%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 1.39%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 1         | 1.39%   |
| AMD E1-6010 APU with AMD Radeon R2 Graphics   | 1         | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 14        | 19.44%  |
| Intel Core i7    | 13        | 18.06%  |
| Intel Core 2 Duo | 5         | 6.94%   |
| Intel Celeron    | 5         | 6.94%   |
| Intel Pentium    | 4         | 5.56%   |
| Intel Core i3    | 4         | 5.56%   |
| Intel Atom       | 4         | 5.56%   |
| AMD Ryzen 5      | 4         | 5.56%   |
| Other            | 3         | 4.17%   |
| Intel Xeon       | 3         | 4.17%   |
| AMD Ryzen 7      | 2         | 2.78%   |
| AMD A4           | 2         | 2.78%   |
| Intel Pentium D  | 1         | 1.39%   |
| Intel Pentium 4  | 1         | 1.39%   |
| Intel Core m5    | 1         | 1.39%   |
| Intel Core Duo   | 1         | 1.39%   |
| AMD E1           | 1         | 1.39%   |
| AMD E            | 1         | 1.39%   |
| AMD Athlon II X2 | 1         | 1.39%   |
| AMD A8           | 1         | 1.39%   |
| AMD A10          | 1         | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 32        | 44.44%  |
| 4      | 26        | 36.11%  |
| 6      | 7         | 9.72%   |
| 8      | 4         | 5.56%   |
| 1      | 3         | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 98.61%  |
| 2      | 1         | 1.39%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 41        | 56.94%  |
| 1      | 31        | 43.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 69        | 95.83%  |
| 32-bit         | 3         | 4.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 6         | 8.33%   |
| Unknown    | 6         | 8.33%   |
| 0x306c3    | 5         | 6.94%   |
| 0x806ea    | 4         | 5.56%   |
| 0x40651    | 4         | 5.56%   |
| 0x1067a    | 3         | 4.17%   |
| 0xa0671    | 2         | 2.78%   |
| 0x906ed    | 2         | 2.78%   |
| 0x706a1    | 2         | 2.78%   |
| 0x406c4    | 2         | 2.78%   |
| 0x306d4    | 2         | 2.78%   |
| 0x206a7    | 2         | 2.78%   |
| 0x08701021 | 2         | 2.78%   |
| 0xf64      | 1         | 1.39%   |
| 0xf29      | 1         | 1.39%   |
| 0xa0653    | 1         | 1.39%   |
| 0x906e9    | 1         | 1.39%   |
| 0x806e9    | 1         | 1.39%   |
| 0x806c1    | 1         | 1.39%   |
| 0x706e5    | 1         | 1.39%   |
| 0x6fb      | 1         | 1.39%   |
| 0x6ec      | 1         | 1.39%   |
| 0x506e3    | 1         | 1.39%   |
| 0x506c9    | 1         | 1.39%   |
| 0x406e3    | 1         | 1.39%   |
| 0x30678    | 1         | 1.39%   |
| 0x206d7    | 1         | 1.39%   |
| 0x20652    | 1         | 1.39%   |
| 0x106ca    | 1         | 1.39%   |
| 0x106c2    | 1         | 1.39%   |
| 0x106a5    | 1         | 1.39%   |
| 0x10676    | 1         | 1.39%   |
| 0x10661    | 1         | 1.39%   |
| 0x08108102 | 1         | 1.39%   |
| 0x0810100b | 1         | 1.39%   |
| 0x0800820d | 1         | 1.39%   |
| 0x0800820b | 1         | 1.39%   |
| 0x07030105 | 1         | 1.39%   |
| 0x07030104 | 1         | 1.39%   |
| 0x0700010f | 1         | 1.39%   |
| 0x0500010d | 1         | 1.39%   |
| 0x03000027 | 1         | 1.39%   |
| 0x010000c8 | 1         | 1.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 15.28%  |
| Haswell       | 9         | 12.5%   |
| IvyBridge     | 6         | 8.33%   |
| Silvermont    | 4         | 5.56%   |
| Penryn        | 4         | 5.56%   |
| Zen+          | 3         | 4.17%   |
| Skylake       | 3         | 4.17%   |
| SandyBridge   | 3         | 4.17%   |
| Zen 2         | 2         | 2.78%   |
| Puma          | 2         | 2.78%   |
| NetBurst      | 2         | 2.78%   |
| IceLake       | 2         | 2.78%   |
| Goldmont plus | 2         | 2.78%   |
| Core          | 2         | 2.78%   |
| Broadwell     | 2         | 2.78%   |
| Bonnell       | 2         | 2.78%   |
| Zen           | 1         | 1.39%   |
| Westmere      | 1         | 1.39%   |
| TigerLake     | 1         | 1.39%   |
| Steamroller   | 1         | 1.39%   |
| P6            | 1         | 1.39%   |
| Nehalem       | 1         | 1.39%   |
| K10 Llano     | 1         | 1.39%   |
| K10           | 1         | 1.39%   |
| Jaguar        | 1         | 1.39%   |
| Goldmont      | 1         | 1.39%   |
| CometLake     | 1         | 1.39%   |
| Bobcat        | 1         | 1.39%   |
| Unknown       | 1         | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 45        | 53.57%  |
| Nvidia | 20        | 23.81%  |
| AMD    | 19        | 22.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 5         | 5.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 4.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 3.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.33%   |
| Intel HD Graphics 630                                                                    | 2         | 2.33%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.33%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 2.33%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 1.16%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 1.16%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 1.16%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                         | 1         | 1.16%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 1.16%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.16%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.16%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 1.16%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 1.16%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.16%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.16%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 1.16%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.16%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1         | 1.16%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 1.16%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 1         | 1.16%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.16%   |
| Nvidia GF114M [GeForce GTX 675M]                                                         | 1         | 1.16%   |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.16%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1         | 1.16%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 1         | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.16%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.16%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 1.16%   |
| Intel HD Graphics 620                                                                    | 1         | 1.16%   |
| Intel HD Graphics 530                                                                    | 1         | 1.16%   |
| Intel HD Graphics 515                                                                    | 1         | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.16%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.16%   |
| Intel 82865G Integrated Graphics Controller                                              | 1         | 1.16%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.16%   |
| AMD Sumo [Radeon HD 6480G]                                                               | 1         | 1.16%   |
| AMD RV630/M76 [Mobility Radeon HD 2600]                                                  | 1         | 1.16%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 1.16%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.16%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1         | 1.16%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1         | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 45.83%  |
| 1 x AMD        | 15        | 20.83%  |
| 1 x Nvidia     | 13        | 18.06%  |
| Intel + Nvidia | 7         | 9.72%   |
| Intel + AMD    | 4         | 5.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 62        | 86.11%  |
| Proprietary | 9         | 12.5%   |
| Unknown     | 1         | 1.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 59.72%  |
| 0.01-0.5   | 9         | 12.5%   |
| 0.51-1.0   | 8         | 11.11%  |
| 3.01-4.0   | 4         | 5.56%   |
| 1.01-2.0   | 4         | 5.56%   |
| 5.01-6.0   | 3         | 4.17%   |
| 7.01-8.0   | 1         | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 10        | 12.35%  |
| Samsung Electronics     | 9         | 11.11%  |
| AU Optronics            | 9         | 11.11%  |
| LG Display              | 8         | 9.88%   |
| Goldstar                | 5         | 6.17%   |
| Chimei Innolux          | 5         | 6.17%   |
| Lenovo                  | 4         | 4.94%   |
| Chi Mei Optoelectronics | 4         | 4.94%   |
| Acer                    | 4         | 4.94%   |
| Hewlett-Packard         | 3         | 3.7%    |
| Dell                    | 3         | 3.7%    |
| Philips                 | 2         | 2.47%   |
| HannStar                | 2         | 2.47%   |
| ASUSTek Computer        | 2         | 2.47%   |
| ViewSonic               | 1         | 1.23%   |
| Videoseven              | 1         | 1.23%   |
| Vestel Elektronik       | 1         | 1.23%   |
| Sony                    | 1         | 1.23%   |
| Sceptre Tech            | 1         | 1.23%   |
| RIS                     | 1         | 1.23%   |
| LG Philips              | 1         | 1.23%   |
| InfoVision              | 1         | 1.23%   |
| Iiyama                  | 1         | 1.23%   |
| BenQ                    | 1         | 1.23%   |
| Apple                   | 1         | 1.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 2         | 2.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 2.47%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                    | 1         | 1.23%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch                   | 1         | 1.23%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch      | 1         | 1.23%   |
| Sony TV SNY0801 1360x768                                                  | 1         | 1.23%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                    | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM04E6 1920x1080 477x268mm 21.5-inch      | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch      | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch     | 1         | 1.23%   |
| Samsung Electronics C27JG5x SAM0F57 2560x1440 600x340mm 27.2-inch         | 1         | 1.23%   |
| RIS photo19 RIS0839 1366x768 410x230mm 18.5-inch                          | 1         | 1.23%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch                 | 1         | 1.23%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch                  | 1         | 1.23%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch              | 1         | 1.23%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch             | 1         | 1.23%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch               | 1         | 1.23%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch                  | 1         | 1.23%   |
| Lenovo LEN L192p LEN24CB 1280x1024 376x301mm 19.0-inch                    | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4043 1400x1050 305x228mm 15.0-inch                  | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                   | 1         | 1.23%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch               | 1         | 1.23%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                      | 1         | 1.23%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch                | 1         | 1.23%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch                | 1         | 1.23%   |
| Hewlett-Packard 2011 HWP2934 1600x900 443x249mm 20.0-inch                 | 1         | 1.23%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                  | 1         | 1.23%   |
| HannStar HL161ABB HSD61C7 1366x768 344x193mm 15.5-inch                    | 1         | 1.23%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                      | 1         | 1.23%   |
| Goldstar L1715S GSM436F 1280x1024 338x270mm 17.0-inch                     | 1         | 1.23%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 1         | 1.23%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                    | 1         | 1.23%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                       | 1         | 1.23%   |
| Dell ST2220L DELA063 1920x1080 477x268mm 21.5-inch                        | 1         | 1.23%   |
| Dell S2409W DELA039 1920x1080 530x300mm 24.0-inch                         | 1         | 1.23%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                         | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1376 1920x1080 293x165mm 13.2-inch          | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 1         | 1.23%   |
| BOE LCD Monitor BOE089D 1920x1080 294x165mm 13.3-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE0742 1920x1080 309x173mm 13.9-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                      | 1         | 1.23%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                      | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 35        | 44.87%  |
| 1366x768 (WXGA)    | 20        | 25.64%  |
| 3840x2160 (4K)     | 4         | 5.13%   |
| 1680x1050 (WSXGA+) | 3         | 3.85%   |
| 2560x1440 (QHD)    | 2         | 2.56%   |
| 1440x900 (WXGA+)   | 2         | 2.56%   |
| 1360x768           | 2         | 2.56%   |
| 1280x1024 (SXGA)   | 2         | 2.56%   |
| 1024x600           | 2         | 2.56%   |
| 3440x1440          | 1         | 1.28%   |
| 2560x1080          | 1         | 1.28%   |
| 1600x900 (HD+)     | 1         | 1.28%   |
| 1400x1050          | 1         | 1.28%   |
| 1280x800 (WXGA)    | 1         | 1.28%   |
| 1024x768 (XGA)     | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 21        | 26.25%  |
| 13     | 10        | 12.5%   |
| 27     | 8         | 10%     |
| 21     | 7         | 8.75%   |
| 14     | 7         | 8.75%   |
| 24     | 4         | 5%      |
| 23     | 4         | 5%      |
| 17     | 4         | 5%      |
| 10     | 3         | 3.75%   |
| 84     | 2         | 2.5%    |
| 34     | 2         | 2.5%    |
| 20     | 2         | 2.5%    |
| 18     | 2         | 2.5%    |
| 72     | 1         | 1.25%   |
| 43     | 1         | 1.25%   |
| 22     | 1         | 1.25%   |
| 11     | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 42.31%  |
| 501-600     | 13        | 16.67%  |
| 401-500     | 11        | 14.1%   |
| 201-300     | 9         | 11.54%  |
| 351-400     | 5         | 6.41%   |
| 1501-2000   | 3         | 3.85%   |
| 701-800     | 2         | 2.56%   |
| 601-700     | 1         | 1.28%   |
| 901-1000    | 1         | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 62        | 83.78%  |
| 16/10 | 6         | 8.11%   |
| 5/4   | 2         | 2.7%    |
| 4/3   | 2         | 2.7%    |
| 21/9  | 2         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 26.58%  |
| 81-90          | 13        | 16.46%  |
| 201-250        | 13        | 16.46%  |
| 301-350        | 8         | 10.13%  |
| 151-200        | 5         | 6.33%   |
| 71-80          | 4         | 5.06%   |
| More than 1000 | 3         | 3.8%    |
| 41-50          | 3         | 3.8%    |
| 121-130        | 3         | 3.8%    |
| 351-500        | 2         | 2.53%   |
| 141-150        | 2         | 2.53%   |
| 51-60          | 1         | 1.27%   |
| 501-1000       | 1         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 29        | 37.66%  |
| 51-100  | 24        | 31.17%  |
| 121-160 | 19        | 24.68%  |
| 161-240 | 4         | 5.19%   |
| 1-50    | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 60        | 83.33%  |
| 2     | 11        | 15.28%  |
| 0     | 1         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 38        | 33.63%  |
| Realtek Semiconductor    | 33        | 29.2%   |
| Qualcomm Atheros         | 14        | 12.39%  |
| Broadcom                 | 9         | 7.96%   |
| TP-Link                  | 3         | 2.65%   |
| Sierra Wireless          | 2         | 1.77%   |
| Ralink Technology        | 2         | 1.77%   |
| Nvidia                   | 2         | 1.77%   |
| Marvell Technology Group | 2         | 1.77%   |
| U-Blox                   | 1         | 0.88%   |
| NetGear                  | 1         | 0.88%   |
| Huawei Technologies      | 1         | 0.88%   |
| Hewlett-Packard          | 1         | 0.88%   |
| Google                   | 1         | 0.88%   |
| Edimax Technology        | 1         | 0.88%   |
| Broadcom Limited         | 1         | 0.88%   |
| ASIX Electronics         | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 18        | 13.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 7         | 5.26%   |
| Intel Wireless 8265 / 8275                                                                    | 4         | 3.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4         | 3.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 2.26%   |
| Intel Wireless 7260                                                                           | 3         | 2.26%   |
| Intel Wireless 3165                                                                           | 3         | 2.26%   |
| Intel Ethernet Connection I218-LM                                                             | 3         | 2.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2         | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 2         | 1.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2         | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                                             | 2         | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 1.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 2         | 1.5%    |
| Intel Wireless 8260                                                                           | 2         | 1.5%    |
| Intel Wi-Fi 6 AX200                                                                           | 2         | 1.5%    |
| Intel Ethernet Connection I217-LM                                                             | 2         | 1.5%    |
| Intel Ethernet Connection (11) I219-V                                                         | 2         | 1.5%    |
| Intel Centrino Advanced-N 6235                                                                | 2         | 1.5%    |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 1.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.5%    |
| U-Blox [u-blox 8]                                                                             | 1         | 0.75%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 0.75%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                                           | 1         | 0.75%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1         | 0.75%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.75%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 0.75%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                                 | 1         | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1         | 0.75%   |
| Nvidia MCP89 Ethernet                                                                         | 1         | 0.75%   |
| Nvidia MCP79 Ethernet                                                                         | 1         | 0.75%   |
| NetGear A6210                                                                                 | 1         | 0.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.75%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                                          | 1         | 0.75%   |
| Intel Wireless-AC 9260                                                                        | 1         | 0.75%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 0.75%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 1         | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 1         | 0.75%   |
| Intel I211 Gigabit Network Connection                                                         | 1         | 0.75%   |
| Intel Ethernet Connection I217-V                                                              | 1         | 0.75%   |
| Intel Ethernet Connection (7) I219-V                                                          | 1         | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                                         | 1         | 0.75%   |
| Intel Ethernet Connection (6) I219-LM                                                         | 1         | 0.75%   |
| Intel Ethernet Connection (5) I219-LM                                                         | 1         | 0.75%   |
| Intel Ethernet Connection (4) I219-V                                                          | 1         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                                                          | 1         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 37.5%   |
| Qualcomm Atheros      | 12        | 18.75%  |
| Realtek Semiconductor | 10        | 15.63%  |
| Broadcom              | 7         | 10.94%  |
| TP-Link               | 3         | 4.69%   |
| Sierra Wireless       | 2         | 3.13%   |
| Ralink Technology     | 2         | 3.13%   |
| NetGear               | 1         | 1.56%   |
| Hewlett-Packard       | 1         | 1.56%   |
| Edimax Technology     | 1         | 1.56%   |
| Broadcom Limited      | 1         | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                                    | 4         | 6.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 4.69%   |
| Intel Wireless 7260                                                                           | 3         | 4.69%   |
| Intel Wireless 3165                                                                           | 3         | 4.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2         | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 3.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 2         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 3.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 2         | 3.13%   |
| Intel Wireless 8260                                                                           | 2         | 3.13%   |
| Intel Wi-Fi 6 AX200                                                                           | 2         | 3.13%   |
| Intel Centrino Advanced-N 6235                                                                | 2         | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 3.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 3.13%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 1.56%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                                           | 1         | 1.56%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 1.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 1.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.56%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 1.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 1.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 1.56%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.56%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 1.56%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.56%   |
| NetGear A6210                                                                                 | 1         | 1.56%   |
| Intel Wireless-AC 9260                                                                        | 1         | 1.56%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 1         | 1.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 1         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 1.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 1.56%   |
| HP lt4112 Gobi 4G Module Network Device                                                       | 1         | 1.56%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                                | 1         | 1.56%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                                        | 1         | 1.56%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1         | 1.56%   |
| Broadcom BCM43224 802.11a/b/g/n                                                               | 1         | 1.56%   |
| Broadcom BCM4311 802.11a/b/g                                                                  | 1         | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 44.62%  |
| Intel                    | 26        | 40%     |
| Qualcomm Atheros         | 3         | 4.62%   |
| Nvidia                   | 2         | 3.08%   |
| Marvell Technology Group | 2         | 3.08%   |
| Broadcom                 | 2         | 3.08%   |
| ASIX Electronics         | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 27.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 10.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 6.06%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 4.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.03%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 3.03%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.52%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.52%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.52%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.52%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.52%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.52%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.52%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.52%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.52%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.52%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.52%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.52%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.52%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.52%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.52%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1         | 1.52%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.52%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.52%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1         | 1.52%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1.52%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.52%   |
| ASIX AX88772B                                                     | 1         | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 63        | 50.81%  |
| WiFi     | 58        | 46.77%  |
| Modem    | 2         | 1.61%   |
| Unknown  | 1         | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 55        | 51.4%   |
| WiFi     | 51        | 47.66%  |
| Unknown  | 1         | 0.93%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 41        | 56.94%  |
| 1     | 27        | 37.5%   |
| 0     | 2         | 2.78%   |
| 12    | 1         | 1.39%   |
| 3     | 1         | 1.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 67        | 91.78%  |
| Yes  | 6         | 8.22%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 47.5%   |
| Broadcom                        | 5         | 12.5%   |
| Realtek Semiconductor           | 3         | 7.5%    |
| Qualcomm Atheros Communications | 3         | 7.5%    |
| Lite-On Technology              | 2         | 5%      |
| IMC Networks                    | 2         | 5%      |
| Cambridge Silicon Radio         | 2         | 5%      |
| Apple                           | 2         | 5%      |
| Hewlett-Packard                 | 1         | 2.5%    |
| Foxconn / Hon Hai               | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13        | 32.5%   |
| Realtek Bluetooth Radio                             | 2         | 5%      |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5%      |
| Intel Bluetooth Device                              | 2         | 5%      |
| Intel AX200 Bluetooth                               | 2         | 5%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5%      |
| Realtek RTL8821A Bluetooth                          | 1         | 2.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.5%    |
| Lite-On Bluetooth Device                            | 1         | 2.5%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.5%    |
| IMC Networks Bluetooth Radio                        | 1         | 2.5%    |
| IMC Networks Bluetooth Device                       | 1         | 2.5%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 2.5%    |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.5%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 2.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.5%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.5%    |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.5%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 2.5%    |
| Apple Bluetooth USB Host Controller                 | 1         | 2.5%    |
| Apple Bluetooth Host Controller                     | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 52        | 55.32%  |
| Nvidia              | 17        | 18.09%  |
| AMD                 | 16        | 17.02%  |
| Focusrite-Novation  | 2         | 2.13%   |
| Texas Instruments   | 1         | 1.06%   |
| SteelSeries ApS     | 1         | 1.06%   |
| Mark of the Unicorn | 1         | 1.06%   |
| Kingston Technology | 1         | 1.06%   |
| JMTek               | 1         | 1.06%   |
| GN Netcom           | 1         | 1.06%   |
| Creative Labs       | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 6.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 5.31%   |
| AMD FCH Azalia Controller                                                                         | 6         | 5.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 3.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.54%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.65%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.77%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.77%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.77%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.77%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.77%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.77%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.77%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.77%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.88%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 1         | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.88%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.88%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.88%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.88%   |
| Mark of the Unicorn M Series                                                                      | 1         | 0.88%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.88%   |
| JMTek Widget C                                                                                    | 1         | 0.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.88%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.88%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.88%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 1         | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.88%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.88%   |
| Focusrite-Novation Scarlett Solo USB                                                              | 1         | 0.88%   |
| Focusrite-Novation Scarlett 2i4 USB                                                               | 1         | 0.88%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                                        | 1         | 0.88%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.88%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK Hynix                     | 15        | 18.07%  |
| Samsung Electronics          | 12        | 14.46%  |
| Kingston                     | 11        | 13.25%  |
| Micron Technology            | 9         | 10.84%  |
| Unknown                      | 8         | 9.64%   |
| Crucial                      | 6         | 7.23%   |
| Corsair                      | 6         | 7.23%   |
| Ramaxel Technology           | 3         | 3.61%   |
| Nanya Technology             | 3         | 3.61%   |
| G.Skill                      | 2         | 2.41%   |
| Unknown (ABCD)               | 1         | 1.2%    |
| Transcend                    | 1         | 1.2%    |
| Teikon                       | 1         | 1.2%    |
| Smart                        | 1         | 1.2%    |
| PNY                          | 1         | 1.2%    |
| Patriot Memory (PDP Systems) | 1         | 1.2%    |
| Elpida                       | 1         | 1.2%    |
| A-DATA Technology            | 1         | 1.2%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                 | 2         | 2.25%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                 | 2         | 2.25%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s              | 2         | 2.25%   |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s                         | 1         | 1.12%   |
| Unknown RAM Module 512MB DIMM SDRAM                                  | 1         | 1.12%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                         | 1         | 1.12%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                       | 1         | 1.12%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                | 1         | 1.12%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                           | 1         | 1.12%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                | 1         | 1.12%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                 | 1         | 1.12%   |
| Unknown RAM Module 1024MB DIMM DDR                                   | 1         | 1.12%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s     | 1         | 1.12%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s               | 1         | 1.12%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s               | 1         | 1.12%   |
| Smart RAM SH564128FJ8NWRNSQR 4096MB SODIMM DDR3 1600MT/s             | 1         | 1.12%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 800MT/s                       | 1         | 1.12%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 1         | 1.12%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |
| SK Hynix RAM HMT351U7EFR8C-PB 4096MB DIMM DDR3 1600MT/s              | 1         | 1.12%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s              | 1         | 1.12%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 1.12%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s               | 1         | 1.12%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s            | 1         | 1.12%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s               | 1         | 1.12%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.12%   |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.12%   |
| SK Hynix RAM H5AN8G6NCJR-XNC 4GB SODIMM DDR4 3200MT/s                | 1         | 1.12%   |
| Samsung RAM Module 2048MB SODIMM DDR2 533MT/s                        | 1         | 1.12%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s                | 1         | 1.12%   |
| Samsung RAM M471B5674EB0-YK0 2048MB SODIMM DDR3 1600MT/s             | 1         | 1.12%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                | 1         | 1.12%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s             | 1         | 1.12%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                | 1         | 1.12%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 1.12%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                | 1         | 1.12%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                | 1         | 1.12%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s               | 1         | 1.12%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s               | 1         | 1.12%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                | 1         | 1.12%   |
| Samsung RAM M391B5273DH0-YK0 4GB DIMM DDR3 1600MT/s                  | 1         | 1.12%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s              | 1         | 1.12%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16384MB SODIMM DDR4 2667MT/s        | 1         | 1.12%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.12%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s                 | 1         | 1.12%   |
| Patriot Memory (PDP Systems) RAM PSD48G320081 8GB DIMM DDR4 3200MT/s | 1         | 1.12%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s                   | 1         | 1.12%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                 | 1         | 1.12%   |
| Nanya RAM NT1GT64UH8D0FN-3C 1024MB SODIMM DDR2 667MT/s               | 1         | 1.12%   |
| Micron RAM Module 4GB SODIMM DDR3 1067MT/s                           | 1         | 1.12%   |
| Micron RAM Module 4096MB SODIMM DDR4 2400MT/s                        | 1         | 1.12%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                        | 1         | 1.12%   |
| Micron RAM Module 1024MB SODIMM DDR3 1067MT/s                        | 1         | 1.12%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s                 | 1         | 1.12%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s          | 1         | 1.12%   |
| Micron RAM 4ATF51264HZ-2G3E1 4096MB SODIMM DDR4 2667MT/s             | 1         | 1.12%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s           | 1         | 1.12%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s                | 1         | 1.12%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s                 | 1         | 1.12%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 36        | 50.7%   |
| DDR4   | 24        | 33.8%   |
| DDR2   | 4         | 5.63%   |
| LPDDR3 | 3         | 4.23%   |
| DDR    | 2         | 2.82%   |
| SDRAM  | 1         | 1.41%   |
| LPDDR4 | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 63.01%  |
| DIMM         | 22        | 30.14%  |
| Row Of Chips | 3         | 4.11%   |
| Chip         | 2         | 2.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 27        | 34.18%  |
| 8192  | 26        | 32.91%  |
| 2048  | 14        | 17.72%  |
| 16384 | 6         | 7.59%   |
| 1024  | 5         | 6.33%   |
| 512   | 1         | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 22        | 29.33%  |
| 2667    | 7         | 9.33%   |
| 3200    | 5         | 6.67%   |
| 2133    | 5         | 6.67%   |
| 1333    | 5         | 6.67%   |
| 2400    | 4         | 5.33%   |
| 1334    | 4         | 5.33%   |
| Unknown | 4         | 5.33%   |
| 1067    | 3         | 4%      |
| 3000    | 2         | 2.67%   |
| 2933    | 2         | 2.67%   |
| 1867    | 2         | 2.67%   |
| 1800    | 2         | 2.67%   |
| 667     | 2         | 2.67%   |
| 3600    | 1         | 1.33%   |
| 3466    | 1         | 1.33%   |
| 3266    | 1         | 1.33%   |
| 3100    | 1         | 1.33%   |
| 800     | 1         | 1.33%   |
| 533     | 1         | 1.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Lexmark International | 1         | 50%     |
| Brother Industries    | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Lexmark International CS417dn | 1         | 50%     |
| Brother DCP-L2540DW           | 1         | 50%     |

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
| Chicony Electronics                    | 9         | 23.68%  |
| Acer                                   | 7         | 18.42%  |
| Realtek Semiconductor                  | 4         | 10.53%  |
| Quanta                                 | 3         | 7.89%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 7.89%   |
| Sunplus Innovation Technology          | 2         | 5.26%   |
| Lite-On Technology                     | 2         | 5.26%   |
| IMC Networks                           | 2         | 5.26%   |
| Suyin                                  | 1         | 2.63%   |
| Sunplus Technology                     | 1         | 2.63%   |
| Luxvisions Innotech Limited            | 1         | 2.63%   |
| Lenovo                                 | 1         | 2.63%   |
| GEMBIRD                                | 1         | 2.63%   |
| Apple                                  | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 3         | 7.89%   |
| Quanta VGA WebCam                                           | 2         | 5.26%   |
| Lite-On Integrated Camera                                   | 2         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 5.26%   |
| Acer Lenovo Integrated Webcam                               | 2         | 5.26%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 2.63%   |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode)     | 1         | 2.63%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 2.63%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 2.63%   |
| Realtek USB Camera                                          | 1         | 2.63%   |
| Realtek Integrated_Webcam_HD                                | 1         | 2.63%   |
| Realtek Integrated Camera 2M                                | 1         | 2.63%   |
| Realtek HD WebCam                                           | 1         | 2.63%   |
| Quanta HP Wide Vision FHD Camera                            | 1         | 2.63%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 1         | 2.63%   |
| Lenovo Integrated Webcam                                    | 1         | 2.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 2.63%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 2.63%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]           | 1         | 2.63%   |
| Chicony Webcam                                              | 1         | 2.63%   |
| Chicony USB 2.0 Camera                                      | 1         | 2.63%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 2.63%   |
| Chicony HP Truevision HD                                    | 1         | 2.63%   |
| Chicony HP Full-HD Camera                                   | 1         | 2.63%   |
| Chicony HD WebCam                                           | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 1         | 2.63%   |
| Apple Built-in iSight                                       | 1         | 2.63%   |
| Acer Lenovo EasyCamera                                      | 1         | 2.63%   |
| Acer Integrated Camera                                      | 1         | 2.63%   |
| Acer HP Webcam                                              | 1         | 2.63%   |
| Acer EasyCamera                                             | 1         | 2.63%   |
| Acer BisonCam, NB Pro                                       | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 30%     |
| Synaptics                  | 3         | 30%     |
| Upek                       | 1         | 10%     |
| STMicroelectronics         | 1         | 10%     |
| Shenzhen Goodix Technology | 1         | 10%     |
| AuthenTec                  | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                            | 2         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 10%     |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 10%     |
| STMicroelectronics Fingerprint Reader                      | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 10%     |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 10%     |
| Unknown                                                    | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 2         | 50%     |
| Broadcom    | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 52        | 72.22%  |
| 1     | 14        | 19.44%  |
| 2     | 6         | 8.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 10        | 38.46%  |
| Fingerprint reader       | 10        | 38.46%  |
| Chipcard                 | 4         | 15.38%  |
| Multimedia controller    | 1         | 3.85%   |
| Communication controller | 1         | 3.85%   |

