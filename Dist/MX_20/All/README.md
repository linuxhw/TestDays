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

Total: 84

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock   | H370M-ITX/ac                | Desktop     | [fa925dcefb](https://linux-hardware.org/?probe=fa925dcefb) | Oct 24, 2022 |
| ASRock   | H370M-ITX/ac                | Desktop     | [1a577be107](https://linux-hardware.org/?probe=1a577be107) | Sep 04, 2022 |
| UMAX     | VisionBook-N12R             | Notebook    | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
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
| Medion   | Akoya E1318T                | Notebook    | [d6be35c8af](https://linux-hardware.org/?probe=d6be35c8af) | Mar 20, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 4.19.0-6-amd64             | 13        | 16.88%  |
| 5.10.0-5mx-amd64           | 9         | 11.69%  |
| 5.8.0-3-amd64              | 7         | 9.09%   |
| 4.19.0-17-amd64            | 5         | 6.49%   |
| 4.19.0-16-amd64            | 5         | 6.49%   |
| 5.6.0-2-amd64              | 4         | 5.19%   |
| 4.19.0-11-amd64            | 3         | 3.9%    |
| 5.5.0-9.1-liquorix-amd64   | 2         | 2.6%    |
| 5.10.0-8mx-amd64           | 2         | 2.6%    |
| 4.19.0-14-amd64            | 2         | 2.6%    |
| 4.19.0-12-amd64            | 2         | 2.6%    |
| 4.19.0-10-amd64            | 2         | 2.6%    |
| 5.8.16-antix.1-amd64-smp   | 1         | 1.3%    |
| 5.6.0-15.2-liquorix-amd64  | 1         | 1.3%    |
| 5.6.0-12.1-liquorix-amd64  | 1         | 1.3%    |
| 5.5.0-5.1-liquorix-amd64   | 1         | 1.3%    |
| 5.4.7-antix.1-amd64-smp    | 1         | 1.3%    |
| 5.4.0-3-amd64              | 1         | 1.3%    |
| 5.15.0-1mx-amd64           | 1         | 1.3%    |
| 5.11.0-16.1-liquorix-amd64 | 1         | 1.3%    |
| 5.10.0-6.2-liquorix-amd64  | 1         | 1.3%    |
| 5.10.0-4mx-amd64           | 1         | 1.3%    |
| 5.10.0-10mx-amd64          | 1         | 1.3%    |
| 4.19.174                   | 1         | 1.3%    |
| 4.19.0-9-amd64             | 1         | 1.3%    |
| 4.19.0-9-686-pae           | 1         | 1.3%    |
| 4.19.0-22-amd64            | 1         | 1.3%    |
| 4.19.0-21-amd64            | 1         | 1.3%    |
| 4.19.0-18-amd64            | 1         | 1.3%    |
| 4.19.0-17-686-pae          | 1         | 1.3%    |
| 4.19.0-16-686-pae          | 1         | 1.3%    |
| 4.19.0-13-amd64            | 1         | 1.3%    |
| 4.19.0-10-686-pae          | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.19.0   | 40        | 52.63%  |
| 5.10.0   | 14        | 18.42%  |
| 5.8.0    | 7         | 9.21%   |
| 5.6.0    | 6         | 7.89%   |
| 5.5.0    | 3         | 3.95%   |
| 5.8.16   | 1         | 1.32%   |
| 5.4.7    | 1         | 1.32%   |
| 5.4.0    | 1         | 1.32%   |
| 5.15.0   | 1         | 1.32%   |
| 5.11.0   | 1         | 1.32%   |
| 4.19.174 | 1         | 1.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 41        | 53.95%  |
| 5.10    | 14        | 18.42%  |
| 5.8     | 8         | 10.53%  |
| 5.6     | 6         | 7.89%   |
| 5.5     | 3         | 3.95%   |
| 5.4     | 2         | 2.63%   |
| 5.15    | 1         | 1.32%   |
| 5.11    | 1         | 1.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 70        | 94.59%  |
| i686   | 4         | 5.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| XFCE     | 58        | 78.38%  |
| KDE5     | 9         | 12.16%  |
| i3       | 2         | 2.7%    |
| Trinity  | 1         | 1.35%   |
| spectrwm | 1         | 1.35%   |
| MATE     | 1         | 1.35%   |
| LXQt     | 1         | 1.35%   |
| Budgie   | 1         | 1.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 73        | 98.65%  |
| Tty  | 1         | 1.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 60        | 81.08%  |
| SDDM    | 7         | 9.46%   |
| TDM     | 6         | 8.11%   |
| Unknown | 1         | 1.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 45        | 60%     |
| en_US   | 16        | 21.33%  |
| es_ES   | 5         | 6.67%   |
| en_GB   | 2         | 2.67%   |
| de_DE   | 2         | 2.67%   |
| ru_RU   | 1         | 1.33%   |
| it_IT   | 1         | 1.33%   |
| es_VE   | 1         | 1.33%   |
| es_CO   | 1         | 1.33%   |
| en_IE   | 1         | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 39        | 52.7%   |
| BIOS | 35        | 47.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 65        | 87.84%  |
| Overlay | 6         | 8.11%   |
| Btrfs   | 2         | 2.7%    |
| Xfs     | 1         | 1.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 46        | 61.33%  |
| MBR  | 29        | 38.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 76.62%  |
| Yes       | 18        | 23.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 63.51%  |
| Yes       | 27        | 36.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 15        | 20.27%  |
| Hewlett-Packard     | 15        | 20.27%  |
| Dell                | 8         | 10.81%  |
| ASUSTek Computer    | 7         | 9.46%   |
| Acer                | 6         | 8.11%   |
| MSI                 | 4         | 5.41%   |
| Gigabyte Technology | 4         | 5.41%   |
| ASRock              | 4         | 5.41%   |
| Apple               | 2         | 2.7%    |
| UMAX                | 1         | 1.35%   |
| Teclast             | 1         | 1.35%   |
| Sony                | 1         | 1.35%   |
| Notebook            | 1         | 1.35%   |
| Medion              | 1         | 1.35%   |
| Irbis               | 1         | 1.35%   |
| IBM                 | 1         | 1.35%   |
| Clevo               | 1         | 1.35%   |
| Unknown             | 1         | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| UMAX VisionBook-N12R                     | 1         | 1.35%   |
| Teclast F5                               | 1         | 1.35%   |
| Sony VGN-NR310FH                         | 1         | 1.35%   |
| Notebook W65_W67RZ1                      | 1         | 1.35%   |
| MSI MS-7C94                              | 1         | 1.35%   |
| MSI MS-7B86                              | 1         | 1.35%   |
| MSI MS-7641                              | 1         | 1.35%   |
| MSI GEG                                  | 1         | 1.35%   |
| Medion Akoya E1318T                      | 1         | 1.35%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR0013AU | 1         | 1.35%   |
| Lenovo ThinkPad T60 20085TG              | 1         | 1.35%   |
| Lenovo ThinkPad T530 2394CJ9             | 1         | 1.35%   |
| Lenovo ThinkPad T440s 20AQ007SGE         | 1         | 1.35%   |
| Lenovo ThinkPad T440s 20AQ006HUS         | 1         | 1.35%   |
| Lenovo ThinkPad T400 2768WGB             | 1         | 1.35%   |
| Lenovo ThinkPad P51 20HJS0TP00           | 1         | 1.35%   |
| Lenovo ThinkPad L520 78595VG             | 1         | 1.35%   |
| Lenovo ThinkPad L490 20Q5S0PR00          | 1         | 1.35%   |
| Lenovo ThinkPad E480 20KNCTO1WW          | 1         | 1.35%   |
| Lenovo ThinkPad E425 1198CTO             | 1         | 1.35%   |
| Lenovo MIIX 3-1030 80HV                  | 1         | 1.35%   |
| Lenovo IdeaPad 110-15IBR 80T7            | 1         | 1.35%   |
| Lenovo B590 20206                        | 1         | 1.35%   |
| Lenovo B40-45 20394                      | 1         | 1.35%   |
| Irbis TW94                               | 1         | 1.35%   |
| IBM 8183B2U                              | 1         | 1.35%   |
| HP ZBook 17 G6                           | 1         | 1.35%   |
| HP Z230 Tower Workstation                | 1         | 1.35%   |
| HP Z220 CMT Workstation                  | 1         | 1.35%   |
| HP Spectre x360 Convertible 13-ae0xx     | 1         | 1.35%   |
| HP ProLiant DL380 G6                     | 1         | 1.35%   |
| HP ProDesk 600 G1 DM                     | 1         | 1.35%   |
| HP ProBook 650 G1                        | 1         | 1.35%   |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 1.35%   |
| HP Pavilion 15                           | 1         | 1.35%   |
| HP Notebook                              | 1         | 1.35%   |
| HP Mini 110-3500                         | 1         | 1.35%   |
| HP Falco                                 | 1         | 1.35%   |
| HP ENVY Laptop 13-ba0xxx                 | 1         | 1.35%   |
| HP Compaq 8510p (KM229AV)                | 1         | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 11        | 14.86%  |
| Acer Aspire          | 5         | 6.76%   |
| Dell Latitude        | 4         | 5.41%   |
| HP Pavilion          | 2         | 2.7%    |
| Dell Inspiron        | 2         | 2.7%    |
| ASUS VivoBook        | 2         | 2.7%    |
| UMAX VisionBook-N12R | 1         | 1.35%   |
| Teclast F5           | 1         | 1.35%   |
| Sony VGN-NR310FH     | 1         | 1.35%   |
| Notebook W65         | 1         | 1.35%   |
| MSI MS-7C94          | 1         | 1.35%   |
| MSI MS-7B86          | 1         | 1.35%   |
| MSI MS-7641          | 1         | 1.35%   |
| MSI GEG              | 1         | 1.35%   |
| Medion Akoya         | 1         | 1.35%   |
| Lenovo MIIX          | 1         | 1.35%   |
| Lenovo IdeaPad       | 1         | 1.35%   |
| Lenovo B590          | 1         | 1.35%   |
| Lenovo B40-45        | 1         | 1.35%   |
| Irbis TW94           | 1         | 1.35%   |
| IBM 8183B2U          | 1         | 1.35%   |
| HP ZBook             | 1         | 1.35%   |
| HP Z230              | 1         | 1.35%   |
| HP Z220              | 1         | 1.35%   |
| HP Spectre           | 1         | 1.35%   |
| HP ProLiant          | 1         | 1.35%   |
| HP ProDesk           | 1         | 1.35%   |
| HP ProBook           | 1         | 1.35%   |
| HP Notebook          | 1         | 1.35%   |
| HP Mini              | 1         | 1.35%   |
| HP Falco             | 1         | 1.35%   |
| HP ENVY              | 1         | 1.35%   |
| HP Compaq            | 1         | 1.35%   |
| HP 2000              | 1         | 1.35%   |
| Gigabyte Z390        | 1         | 1.35%   |
| Gigabyte X470        | 1         | 1.35%   |
| Gigabyte H110M-S2H   | 1         | 1.35%   |
| Gigabyte F2A88X-UP4  | 1         | 1.35%   |
| Dell PowerEdge       | 1         | 1.35%   |
| Dell OptiPlex        | 1         | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 9         | 12.16%  |
| 2014 | 9         | 12.16%  |
| 2013 | 8         | 10.81%  |
| 2019 | 7         | 9.46%   |
| 2017 | 6         | 8.11%   |
| 2012 | 6         | 8.11%   |
| 2020 | 4         | 5.41%   |
| 2011 | 4         | 5.41%   |
| 2010 | 4         | 5.41%   |
| 2008 | 4         | 5.41%   |
| 2021 | 3         | 4.05%   |
| 2016 | 3         | 4.05%   |
| 2015 | 2         | 2.7%    |
| 2006 | 2         | 2.7%    |
| 2009 | 1         | 1.35%   |
| 2007 | 1         | 1.35%   |
| 2005 | 1         | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 43        | 58.11%  |
| Desktop     | 22        | 29.73%  |
| Convertible | 4         | 5.41%   |
| Tablet      | 2         | 2.7%    |
| Server      | 2         | 2.7%    |
| Mini pc     | 1         | 1.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 74        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 73        | 98.65%  |
| Yes  | 1         | 1.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 21.62%  |
| 3.01-4.0   | 15        | 20.27%  |
| 16.01-24.0 | 13        | 17.57%  |
| 8.01-16.0  | 13        | 17.57%  |
| 1.01-2.0   | 7         | 9.46%   |
| 32.01-64.0 | 5         | 6.76%   |
| 24.01-32.0 | 3         | 4.05%   |
| 2.01-3.0   | 2         | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 30        | 38.96%  |
| 2.01-3.0  | 15        | 19.48%  |
| 3.01-4.0  | 14        | 18.18%  |
| 4.01-8.0  | 8         | 10.39%  |
| 0.51-1.0  | 8         | 10.39%  |
| 8.01-16.0 | 2         | 2.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 64.47%  |
| 2      | 14        | 18.42%  |
| 3      | 8         | 10.53%  |
| 5      | 2         | 2.63%   |
| 4      | 2         | 2.63%   |
| 0      | 1         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 58.11%  |
| Yes       | 31        | 41.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 86.49%  |
| No        | 10        | 13.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 81.08%  |
| No        | 14        | 18.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 55.41%  |
| No        | 33        | 44.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 18        | 24.32%  |
| Germany     | 7         | 9.46%   |
| Spain       | 6         | 8.11%   |
| Russia      | 4         | 5.41%   |
| India       | 4         | 5.41%   |
| Italy       | 3         | 4.05%   |
| Canada      | 3         | 4.05%   |
| UK          | 2         | 2.7%    |
| Sweden      | 2         | 2.7%    |
| Netherlands | 2         | 2.7%    |
| Mexico      | 2         | 2.7%    |
| Finland     | 2         | 2.7%    |
| Vietnam     | 1         | 1.35%   |
| Venezuela   | 1         | 1.35%   |
| Turkey      | 1         | 1.35%   |
| Syria       | 1         | 1.35%   |
| Slovakia    | 1         | 1.35%   |
| Serbia      | 1         | 1.35%   |
| Portugal    | 1         | 1.35%   |
| Poland      | 1         | 1.35%   |
| Philippines | 1         | 1.35%   |
| Norway      | 1         | 1.35%   |
| Indonesia   | 1         | 1.35%   |
| Hungary     | 1         | 1.35%   |
| France      | 1         | 1.35%   |
| Denmark     | 1         | 1.35%   |
| Czechia     | 1         | 1.35%   |
| Colombia    | 1         | 1.35%   |
| Brazil      | 1         | 1.35%   |
| Australia   | 1         | 1.35%   |
| Angola      | 1         | 1.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Patna         | 3         | 3.95%   |
| Madrid        | 3         | 3.95%   |
| Munich        | 2         | 2.63%   |
| Wadsworth     | 1         | 1.32%   |
| Trivandrum    | 1         | 1.32%   |
| Tampa         | 1         | 1.32%   |
| Tacoma        | 1         | 1.32%   |
| Stockholm     | 1         | 1.32%   |
| Södertälje  | 1         | 1.32%   |
| Siegen        | 1         | 1.32%   |
| Sibulan       | 1         | 1.32%   |
| Rusko         | 1         | 1.32%   |
| Rensselaer    | 1         | 1.32%   |
| Prague        | 1         | 1.32%   |
| Porto         | 1         | 1.32%   |
| Podolsk       | 1         | 1.32%   |
| Perm          | 1         | 1.32%   |
| Ooltewah      | 1         | 1.32%   |
| Omsk          | 1         | 1.32%   |
| Oakland       | 1         | 1.32%   |
| Novi Knezevac | 1         | 1.32%   |
| Newmarket     | 1         | 1.32%   |
| Nashville     | 1         | 1.32%   |
| Münster      | 1         | 1.32%   |
| Mount Pocono  | 1         | 1.32%   |
| Montreal      | 1         | 1.32%   |
| Monterrey     | 1         | 1.32%   |
| Milton Keynes | 1         | 1.32%   |
| Milan         | 1         | 1.32%   |
| Mexico City   | 1         | 1.32%   |
| Mechanicsburg | 1         | 1.32%   |
| Manado        | 1         | 1.32%   |
| Madison       | 1         | 1.32%   |
| Lucca         | 1         | 1.32%   |
| Lublin        | 1         | 1.32%   |
| Luanda        | 1         | 1.32%   |
| Los Angeles   | 1         | 1.32%   |
| Lobnya        | 1         | 1.32%   |
| Livorno       | 1         | 1.32%   |
| Lille         | 1         | 1.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 22     | 17.31%  |
| Seagate             | 16        | 21     | 15.38%  |
| Samsung Electronics | 16        | 22     | 15.38%  |
| Kingston            | 8         | 8      | 7.69%   |
| SanDisk             | 6         | 6      | 5.77%   |
| Hitachi             | 5         | 6      | 4.81%   |
| Toshiba             | 4         | 5      | 3.85%   |
| HGST                | 3         | 3      | 2.88%   |
| Crucial             | 3         | 4      | 2.88%   |
| A-DATA Technology   | 3         | 3      | 2.88%   |
| Unknown             | 2         | 2      | 1.92%   |
| SPCC                | 2         | 2      | 1.92%   |
| SK hynix            | 2         | 2      | 1.92%   |
| Intel               | 2         | 2      | 1.92%   |
| Yeyian              | 1         | 1      | 0.96%   |
| WDC WDS1            | 1         | 1      | 0.96%   |
| Teclast             | 1         | 1      | 0.96%   |
| PNY                 | 1         | 1      | 0.96%   |
| LITEON              | 1         | 1      | 0.96%   |
| Lenovo              | 1         | 1      | 0.96%   |
| Intenso             | 1         | 1      | 0.96%   |
| Indilinx            | 1         | 2      | 0.96%   |
| HUAWEI              | 1         | 1      | 0.96%   |
| HS-SSD-C100         | 1         | 1      | 0.96%   |
| GOODRAM             | 1         | 1      | 0.96%   |
| Gigabyte Technology | 1         | 1      | 0.96%   |
| Fujitsu             | 1         | 1      | 0.96%   |
| Unknown             | 1         | 1      | 0.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 3         | 2.65%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2         | 1.77%   |
| SK hynix SC311 SATA 256GB SSD        | 2         | 1.77%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 1.77%   |
| Yeyian VALK 1000 120GB SSD           | 1         | 0.88%   |
| WDC WDS500G2B0A 500GB SSD            | 1         | 0.88%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD     | 1         | 0.88%   |
| WDC WDS250G2B0A-00SM50 250GB SSD     | 1         | 0.88%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.88%   |
| WDC WDS1 20G2G0A-00JH30 120GB SSD    | 1         | 0.88%   |
| WDC WD800JD-00MSA1 80GB              | 1         | 0.88%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.88%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.88%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 0.88%   |
| WDC WD3200LPVT-08G33T1 320GB         | 1         | 0.88%   |
| WDC WD3200AAJS-00L7A0 320GB          | 1         | 0.88%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.88%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.88%   |
| WDC WD10TPVT-00U4RT1 1TB             | 1         | 0.88%   |
| WDC WD10SPZX-80Z10T2 1TB             | 1         | 0.88%   |
| WDC WD10EADS-65M2B0 1TB              | 1         | 0.88%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.88%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB | 1         | 0.88%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB | 1         | 0.88%   |
| Unknown SDW32G  32GB                 | 1         | 0.88%   |
| Unknown 064G30  64GB                 | 1         | 0.88%   |
| Toshiba THNSFJ256GCSU 256GB SSD      | 1         | 0.88%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.88%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB    | 1         | 0.88%   |
| Toshiba DT01ACA050 500GB             | 1         | 0.88%   |
| Teclast 256GB NS550-2242 SSD         | 1         | 0.88%   |
| SPCC Solid State Disk 512GB          | 1         | 0.88%   |
| SPCC Solid State Disk 240GB          | 1         | 0.88%   |
| Seagate ST9500420AS 500GB            | 1         | 0.88%   |
| Seagate ST9500325AS 500GB            | 1         | 0.88%   |
| Seagate ST500NM0011 500GB            | 1         | 0.88%   |
| Seagate ST4000LM024-2U817V 4TB       | 1         | 0.88%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 0.88%   |
| Seagate ST3750330NS 752GB            | 1         | 0.88%   |
| Seagate ST3500830AS 500GB            | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 20     | 41.03%  |
| WDC     | 12        | 14     | 30.77%  |
| Hitachi | 5         | 6      | 12.82%  |
| HGST    | 3         | 3      | 7.69%   |
| Toshiba | 2         | 3      | 5.13%   |
| Fujitsu | 1         | 1      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 17     | 24.49%  |
| Kingston            | 7         | 7      | 14.29%  |
| SanDisk             | 5         | 5      | 10.2%   |
| WDC                 | 4         | 5      | 8.16%   |
| Crucial             | 3         | 4      | 6.12%   |
| SPCC                | 2         | 2      | 4.08%   |
| SK hynix            | 2         | 2      | 4.08%   |
| A-DATA Technology   | 2         | 2      | 4.08%   |
| Yeyian              | 1         | 1      | 2.04%   |
| WDC WDS1            | 1         | 1      | 2.04%   |
| Toshiba             | 1         | 1      | 2.04%   |
| Teclast             | 1         | 1      | 2.04%   |
| PNY                 | 1         | 1      | 2.04%   |
| LITEON              | 1         | 1      | 2.04%   |
| Intenso             | 1         | 1      | 2.04%   |
| Intel               | 1         | 1      | 2.04%   |
| Indilinx            | 1         | 2      | 2.04%   |
| HS-SSD-C100         | 1         | 1      | 2.04%   |
| GOODRAM             | 1         | 1      | 2.04%   |
| Gigabyte Technology | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 41        | 57     | 44.09%  |
| HDD     | 34        | 47     | 36.56%  |
| NVMe    | 12        | 13     | 12.9%   |
| MMC     | 4         | 4      | 4.3%    |
| Unknown | 2         | 2      | 2.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 61        | 102    | 75.31%  |
| NVMe | 12        | 13     | 14.81%  |
| SAS  | 4         | 4      | 4.94%   |
| MMC  | 4         | 4      | 4.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 52        | 73     | 68.42%  |
| 0.51-1.0   | 14        | 18     | 18.42%  |
| 1.01-2.0   | 6         | 7      | 7.89%   |
| 3.01-4.0   | 3         | 4      | 3.95%   |
| 2.01-3.0   | 1         | 2      | 1.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 20        | 26.32%  |
| 101-250        | 19        | 25%     |
| 51-100         | 11        | 14.47%  |
| 501-1000       | 8         | 10.53%  |
| 21-50          | 6         | 7.89%   |
| More than 3000 | 4         | 5.26%   |
| 1001-2000      | 4         | 5.26%   |
| 1-20           | 3         | 3.95%   |
| 2001-3000      | 1         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 26        | 34.67%  |
| 21-50          | 12        | 16%     |
| 51-100         | 11        | 14.67%  |
| 101-250        | 10        | 13.33%  |
| 251-500        | 7         | 9.33%   |
| 501-1000       | 4         | 5.33%   |
| More than 3000 | 3         | 4%      |
| 2001-3000      | 1         | 1.33%   |
| 1001-2000      | 1         | 1.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 62        | 102    | 75.61%  |
| Malfunc  | 12        | 13     | 14.63%  |
| Detected | 8         | 8      | 9.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 52        | 65%     |
| AMD                          | 13        | 16.25%  |
| Samsung Electronics          | 4         | 5%      |
| SanDisk                      | 3         | 3.75%   |
| Nvidia                       | 2         | 2.5%    |
| Toshiba America Info Systems | 1         | 1.25%   |
| Lenovo                       | 1         | 1.25%   |
| Kingston Technology Company  | 1         | 1.25%   |
| JMicron Technology           | 1         | 1.25%   |
| Hewlett-Packard              | 1         | 1.25%   |
| ADATA Technology             | 1         | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 10.99%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 4.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 4.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 4.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 3.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 3.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 3.3%    |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 3.3%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 2.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 2.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 2.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.2%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 2.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2         | 2.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 2.2%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 1.1%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 1.1%    |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 1.1%    |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.1%    |
| Lenovo Non-Volatile memory controller                                            | 1         | 1.1%    |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 1.1%    |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.1%    |
| Intel SSD 660P Series                                                            | 1         | 1.1%    |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.1%    |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 1.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.1%    |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 1         | 1.1%    |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                         | 1         | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 59        | 69.41%  |
| NVMe | 11        | 12.94%  |
| IDE  | 10        | 11.76%  |
| RAID | 5         | 5.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 61        | 82.43%  |
| AMD    | 13        | 17.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz    | 3         | 4.05%   |
| Intel Core i7-4600U CPU @ 2.10GHz    | 2         | 2.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 2.7%    |
| Intel Core i3-4000M CPU @ 2.40GHz    | 2         | 2.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 2         | 2.7%    |
| Intel Xeon CPU X5550 @ 2.67GHz       | 1         | 1.35%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz   | 1         | 1.35%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz  | 1         | 1.35%   |
| Intel Pentium D CPU 3.40GHz          | 1         | 1.35%   |
| Intel Pentium CPU N4200 @ 1.10GHz    | 1         | 1.35%   |
| Intel Pentium CPU N3710 @ 1.60GHz    | 1         | 1.35%   |
| Intel Pentium CPU G3240T @ 2.70GHz   | 1         | 1.35%   |
| Intel Pentium CPU 2020M @ 2.40GHz    | 1         | 1.35%   |
| Intel Pentium 4 CPU 3.20GHz          | 1         | 1.35%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz     | 1         | 1.35%   |
| Intel Core i9-9900K CPU @ 3.60GHz    | 1         | 1.35%   |
| Intel Core i7-9850H CPU @ 2.60GHz    | 1         | 1.35%   |
| Intel Core i7-9700K CPU @ 3.60GHz    | 1         | 1.35%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz   | 1         | 1.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz    | 1         | 1.35%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz   | 1         | 1.35%   |
| Intel Core i7-5500U CPU @ 2.40GHz    | 1         | 1.35%   |
| Intel Core i7-3770 CPU @ 3.40GHz     | 1         | 1.35%   |
| Intel Core i7-3720QM CPU @ 2.60GHz   | 1         | 1.35%   |
| Intel Core i5-8365U CPU @ 1.60GHz    | 1         | 1.35%   |
| Intel Core i5-7400 CPU @ 3.00GHz     | 1         | 1.35%   |
| Intel Core i5-6600 CPU @ 3.30GHz     | 1         | 1.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz    | 1         | 1.35%   |
| Intel Core i5-4590 CPU @ 3.30GHz     | 1         | 1.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 1         | 1.35%   |
| Intel Core i5-3570 CPU @ 3.40GHz     | 1         | 1.35%   |
| Intel Core i5-3330 CPU @ 3.00GHz     | 1         | 1.35%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 1         | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 1         | 1.35%   |
| Intel Core i5-10400 CPU @ 2.90GHz    | 1         | 1.35%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz   | 1         | 1.35%   |
| Intel Core i3-2350M CPU @ 2.30GHz    | 1         | 1.35%   |
| Intel Core i3 CPU M 330 @ 2.13GHz    | 1         | 1.35%   |
| Intel Core Duo CPU T2500 @ 2.00GHz   | 1         | 1.35%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz | 1         | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 14        | 18.92%  |
| Intel Core i7    | 13        | 17.57%  |
| Intel Celeron    | 6         | 8.11%   |
| Intel Core 2 Duo | 5         | 6.76%   |
| Intel Pentium    | 4         | 5.41%   |
| Intel Core i3    | 4         | 5.41%   |
| Intel Atom       | 4         | 5.41%   |
| AMD Ryzen 5      | 4         | 5.41%   |
| Other            | 3         | 4.05%   |
| Intel Xeon       | 3         | 4.05%   |
| AMD Ryzen 7      | 2         | 2.7%    |
| AMD A4           | 2         | 2.7%    |
| Intel Pentium D  | 1         | 1.35%   |
| Intel Pentium 4  | 1         | 1.35%   |
| Intel Core m5    | 1         | 1.35%   |
| Intel Core i9    | 1         | 1.35%   |
| Intel Core Duo   | 1         | 1.35%   |
| AMD E1           | 1         | 1.35%   |
| AMD E            | 1         | 1.35%   |
| AMD Athlon II X2 | 1         | 1.35%   |
| AMD A8           | 1         | 1.35%   |
| AMD A10          | 1         | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 33        | 44.59%  |
| 4      | 26        | 35.14%  |
| 6      | 7         | 9.46%   |
| 8      | 5         | 6.76%   |
| 1      | 3         | 4.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 73        | 98.65%  |
| 2      | 1         | 1.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 56.76%  |
| 1      | 32        | 43.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 71        | 95.95%  |
| 32-bit         | 3         | 4.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 9.46%   |
| 0x306a9    | 6         | 8.11%   |
| 0x306c3    | 5         | 6.76%   |
| 0x806ea    | 4         | 5.41%   |
| 0x40651    | 4         | 5.41%   |
| 0x1067a    | 3         | 4.05%   |
| 0xa0671    | 2         | 2.7%    |
| 0x906ed    | 2         | 2.7%    |
| 0x706a1    | 2         | 2.7%    |
| 0x406c4    | 2         | 2.7%    |
| 0x306d4    | 2         | 2.7%    |
| 0x206a7    | 2         | 2.7%    |
| 0x08701021 | 2         | 2.7%    |
| 0xf64      | 1         | 1.35%   |
| 0xf29      | 1         | 1.35%   |
| 0xa0653    | 1         | 1.35%   |
| 0x906e9    | 1         | 1.35%   |
| 0x806e9    | 1         | 1.35%   |
| 0x806c1    | 1         | 1.35%   |
| 0x706e5    | 1         | 1.35%   |
| 0x706a8    | 1         | 1.35%   |
| 0x6fb      | 1         | 1.35%   |
| 0x6ec      | 1         | 1.35%   |
| 0x506e3    | 1         | 1.35%   |
| 0x506c9    | 1         | 1.35%   |
| 0x406e3    | 1         | 1.35%   |
| 0x30678    | 1         | 1.35%   |
| 0x206d7    | 1         | 1.35%   |
| 0x20652    | 1         | 1.35%   |
| 0x106ca    | 1         | 1.35%   |
| 0x106c2    | 1         | 1.35%   |
| 0x106a5    | 1         | 1.35%   |
| 0x10676    | 1         | 1.35%   |
| 0x10661    | 1         | 1.35%   |
| 0x08108102 | 1         | 1.35%   |
| 0x0810100b | 1         | 1.35%   |
| 0x0800820d | 1         | 1.35%   |
| 0x0800820b | 1         | 1.35%   |
| 0x07030105 | 1         | 1.35%   |
| 0x07030104 | 1         | 1.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 16.22%  |
| Haswell       | 9         | 12.16%  |
| IvyBridge     | 6         | 8.11%   |
| Silvermont    | 4         | 5.41%   |
| Penryn        | 4         | 5.41%   |
| Zen+          | 3         | 4.05%   |
| Skylake       | 3         | 4.05%   |
| SandyBridge   | 3         | 4.05%   |
| Goldmont plus | 3         | 4.05%   |
| Zen 2         | 2         | 2.7%    |
| Puma          | 2         | 2.7%    |
| NetBurst      | 2         | 2.7%    |
| Icelake       | 2         | 2.7%    |
| Core          | 2         | 2.7%    |
| Broadwell     | 2         | 2.7%    |
| Bonnell       | 2         | 2.7%    |
| Zen           | 1         | 1.35%   |
| Westmere      | 1         | 1.35%   |
| TigerLake     | 1         | 1.35%   |
| Steamroller   | 1         | 1.35%   |
| P6            | 1         | 1.35%   |
| Nehalem       | 1         | 1.35%   |
| K10 Llano     | 1         | 1.35%   |
| K10           | 1         | 1.35%   |
| Jaguar        | 1         | 1.35%   |
| Goldmont      | 1         | 1.35%   |
| CometLake     | 1         | 1.35%   |
| Bobcat        | 1         | 1.35%   |
| Unknown       | 1         | 1.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 47        | 54.65%  |
| Nvidia | 20        | 23.26%  |
| AMD    | 19        | 22.09%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 5         | 5.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 4.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 3.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 3.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.27%   |
| Intel HD Graphics 630                                                                    | 2         | 2.27%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.27%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 2.27%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 1.14%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 1.14%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 1.14%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                         | 1         | 1.14%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 1.14%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 1.14%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.14%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 1.14%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 1.14%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.14%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.14%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 1.14%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.14%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1         | 1.14%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 1.14%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 1         | 1.14%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.14%   |
| Nvidia GF114M [GeForce GTX 675M]                                                         | 1         | 1.14%   |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.14%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1         | 1.14%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 1         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.14%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.14%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 47.3%   |
| 1 x AMD        | 15        | 20.27%  |
| 1 x Nvidia     | 13        | 17.57%  |
| Intel + Nvidia | 7         | 9.46%   |
| Intel + AMD    | 4         | 5.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 64        | 86.49%  |
| Proprietary | 9         | 12.16%  |
| Unknown     | 1         | 1.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 60.81%  |
| 0.01-0.5   | 9         | 12.16%  |
| 0.51-1.0   | 8         | 10.81%  |
| 3.01-4.0   | 4         | 5.41%   |
| 1.01-2.0   | 4         | 5.41%   |
| 5.01-6.0   | 3         | 4.05%   |
| 7.01-8.0   | 1         | 1.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 10        | 12.05%  |
| Samsung Electronics     | 9         | 10.84%  |
| AU Optronics            | 9         | 10.84%  |
| LG Display              | 8         | 9.64%   |
| Goldstar                | 6         | 7.23%   |
| Chimei Innolux          | 5         | 6.02%   |
| Lenovo                  | 4         | 4.82%   |
| Chi Mei Optoelectronics | 4         | 4.82%   |
| Acer                    | 4         | 4.82%   |
| Hewlett-Packard         | 3         | 3.61%   |
| Dell                    | 3         | 3.61%   |
| Philips                 | 2         | 2.41%   |
| HannStar                | 2         | 2.41%   |
| ASUSTek Computer        | 2         | 2.41%   |
| ViewSonic               | 1         | 1.2%    |
| Videoseven              | 1         | 1.2%    |
| Vestel Elektronik       | 1         | 1.2%    |
| Sony                    | 1         | 1.2%    |
| Sceptre Tech            | 1         | 1.2%    |
| RIS                     | 1         | 1.2%    |
| PANDA                   | 1         | 1.2%    |
| LG Philips              | 1         | 1.2%    |
| InfoVision              | 1         | 1.2%    |
| Iiyama                  | 1         | 1.2%    |
| BenQ                    | 1         | 1.2%    |
| Apple                   | 1         | 1.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 2.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 2.41%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                   | 1         | 1.2%    |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch                  | 1         | 1.2%    |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch     | 1         | 1.2%    |
| Sony TV SNY0801 1360x768                                                 | 1         | 1.2%    |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch           | 1         | 1.2%    |
| Samsung Electronics SyncMaster SAM04E6 1920x1080 477x268mm 21.5-inch     | 1         | 1.2%    |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch     | 1         | 1.2%    |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch     | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 950x540mm 43.0-inch    | 1         | 1.2%    |
| Samsung Electronics C27JG5x SAM0F57 1680x1050 600x340mm 27.2-inch        | 1         | 1.2%    |
| RIS photo19 RIS0839 1366x768 410x230mm 18.5-inch                         | 1         | 1.2%    |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch                | 1         | 1.2%    |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch                 | 1         | 1.2%    |
| PANDA LM116LF3L01 NCP000A 1920x1080 256x144mm 11.6-inch                  | 1         | 1.2%    |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch             | 1         | 1.2%    |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 1         | 1.2%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 1         | 1.2%    |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch             | 1         | 1.2%    |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 1         | 1.2%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 1         | 1.2%    |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 1.2%    |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch             | 1         | 1.2%    |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch              | 1         | 1.2%    |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 600x340mm 27.2-inch                 | 1         | 1.2%    |
| Lenovo LEN L192p LEN24CB 1280x1024 376x301mm 19.0-inch                   | 1         | 1.2%    |
| Lenovo LCD Monitor LEN4043 1400x1050 305x228mm 15.0-inch                 | 1         | 1.2%    |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                  | 1         | 1.2%    |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch              | 1         | 1.2%    |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                     | 1         | 1.2%    |
| Hewlett-Packard L1506 HWP265B 1024x768 304x228mm 15.0-inch               | 1         | 1.2%    |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch               | 1         | 1.2%    |
| Hewlett-Packard 2011 HWP2934 1600x900 443x249mm 20.0-inch                | 1         | 1.2%    |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 1         | 1.2%    |
| HannStar HL161ABB HSD61C7 1366x768 344x193mm 15.5-inch                   | 1         | 1.2%    |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 1         | 1.2%    |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                     | 1         | 1.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 36        | 45%     |
| 1366x768 (WXGA)    | 20        | 25%     |
| 3840x2160 (4K)     | 4         | 5%      |
| 1680x1050 (WSXGA+) | 3         | 3.75%   |
| 2560x1440 (QHD)    | 2         | 2.5%    |
| 2560x1080          | 2         | 2.5%    |
| 1440x900 (WXGA+)   | 2         | 2.5%    |
| 1360x768           | 2         | 2.5%    |
| 1280x1024 (SXGA)   | 2         | 2.5%    |
| 1024x600           | 2         | 2.5%    |
| 3440x1440          | 1         | 1.25%   |
| 1600x900 (HD+)     | 1         | 1.25%   |
| 1400x1050          | 1         | 1.25%   |
| 1280x800 (WXGA)    | 1         | 1.25%   |
| 1024x768 (XGA)     | 1         | 1.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 21        | 25.61%  |
| 13     | 10        | 12.2%   |
| 27     | 8         | 9.76%   |
| 21     | 7         | 8.54%   |
| 14     | 7         | 8.54%   |
| 24     | 4         | 4.88%   |
| 23     | 4         | 4.88%   |
| 17     | 4         | 4.88%   |
| 34     | 3         | 3.66%   |
| 10     | 3         | 3.66%   |
| 84     | 2         | 2.44%   |
| 20     | 2         | 2.44%   |
| 18     | 2         | 2.44%   |
| 11     | 2         | 2.44%   |
| 72     | 1         | 1.22%   |
| 43     | 1         | 1.22%   |
| 22     | 1         | 1.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 41.25%  |
| 501-600     | 13        | 16.25%  |
| 401-500     | 11        | 13.75%  |
| 201-300     | 10        | 12.5%   |
| 351-400     | 5         | 6.25%   |
| 701-800     | 3         | 3.75%   |
| 1501-2000   | 3         | 3.75%   |
| 601-700     | 1         | 1.25%   |
| 901-1000    | 1         | 1.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 63        | 82.89%  |
| 16/10 | 6         | 7.89%   |
| 21/9  | 3         | 3.95%   |
| 5/4   | 2         | 2.63%   |
| 4/3   | 2         | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 25.93%  |
| 81-90          | 13        | 16.05%  |
| 201-250        | 13        | 16.05%  |
| 301-350        | 8         | 9.88%   |
| 151-200        | 5         | 6.17%   |
| 71-80          | 4         | 4.94%   |
| More than 1000 | 3         | 3.7%    |
| 351-500        | 3         | 3.7%    |
| 41-50          | 3         | 3.7%    |
| 121-130        | 3         | 3.7%    |
| 51-60          | 2         | 2.47%   |
| 141-150        | 2         | 2.47%   |
| 501-1000       | 1         | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 29        | 36.71%  |
| 51-100  | 25        | 31.65%  |
| 121-160 | 19        | 24.05%  |
| 161-240 | 5         | 6.33%   |
| 1-50    | 1         | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 62        | 83.78%  |
| 2     | 11        | 14.86%  |
| 0     | 1         | 1.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 39        | 33.91%  |
| Realtek Semiconductor    | 34        | 29.57%  |
| Qualcomm Atheros         | 14        | 12.17%  |
| Broadcom                 | 9         | 7.83%   |
| TP-Link                  | 3         | 2.61%   |
| Sierra Wireless          | 2         | 1.74%   |
| Ralink Technology        | 2         | 1.74%   |
| Nvidia                   | 2         | 1.74%   |
| Marvell Technology Group | 2         | 1.74%   |
| U-Blox                   | 1         | 0.87%   |
| NetGear                  | 1         | 0.87%   |
| Huawei Technologies      | 1         | 0.87%   |
| Hewlett-Packard          | 1         | 0.87%   |
| Google                   | 1         | 0.87%   |
| Edimax Technology        | 1         | 0.87%   |
| Broadcom Limited         | 1         | 0.87%   |
| ASIX Electronics         | 1         | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 18        | 13.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 7         | 5.11%   |
| Intel Wireless 8265 / 8275                                                                    | 4         | 2.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4         | 2.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 2.19%   |
| Intel Wireless 7260                                                                           | 3         | 2.19%   |
| Intel Wireless 3165                                                                           | 3         | 2.19%   |
| Intel Ethernet Connection I218-LM                                                             | 3         | 2.19%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2         | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 1.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 2         | 1.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2         | 1.46%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 2         | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 1.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 2         | 1.46%   |
| Intel Wireless 8260                                                                           | 2         | 1.46%   |
| Intel Wi-Fi 6 AX200                                                                           | 2         | 1.46%   |
| Intel I211 Gigabit Network Connection                                                         | 2         | 1.46%   |
| Intel Ethernet Connection I217-LM                                                             | 2         | 1.46%   |
| Intel Ethernet Connection (7) I219-V                                                          | 2         | 1.46%   |
| Intel Ethernet Connection (11) I219-V                                                         | 2         | 1.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 1.46%   |
| Intel Centrino Advanced-N 6235                                                                | 2         | 1.46%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.46%   |
| U-Blox [u-blox 8]                                                                             | 1         | 0.73%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 0.73%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                                           | 1         | 0.73%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.73%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.73%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 0.73%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1         | 0.73%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.73%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 0.73%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 0.73%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 37.88%  |
| Qualcomm Atheros      | 12        | 18.18%  |
| Realtek Semiconductor | 11        | 16.67%  |
| Broadcom              | 7         | 10.61%  |
| TP-Link               | 3         | 4.55%   |
| Sierra Wireless       | 2         | 3.03%   |
| Ralink Technology     | 2         | 3.03%   |
| NetGear               | 1         | 1.52%   |
| Hewlett-Packard       | 1         | 1.52%   |
| Edimax Technology     | 1         | 1.52%   |
| Broadcom Limited      | 1         | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                                    | 4         | 6.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 4.55%   |
| Intel Wireless 7260                                                                           | 3         | 4.55%   |
| Intel Wireless 3165                                                                           | 3         | 4.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2         | 3.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 3.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 2         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 3.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 2         | 3.03%   |
| Intel Wireless 8260                                                                           | 2         | 3.03%   |
| Intel Wi-Fi 6 AX200                                                                           | 2         | 3.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 3.03%   |
| Intel Centrino Advanced-N 6235                                                                | 2         | 3.03%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 3.03%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 1.52%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                                           | 1         | 1.52%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 1.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 1.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.52%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 1.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 1.52%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.52%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 1.52%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 1.52%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.52%   |
| NetGear A6210                                                                                 | 1         | 1.52%   |
| Intel Wireless-AC 9260                                                                        | 1         | 1.52%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 1         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 1.52%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 1.52%   |
| HP lt4112 Gobi 4G Module Network Device                                                       | 1         | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 43.94%  |
| Intel                    | 27        | 40.91%  |
| Qualcomm Atheros         | 3         | 4.55%   |
| Nvidia                   | 2         | 3.03%   |
| Marvell Technology Group | 2         | 3.03%   |
| Broadcom                 | 2         | 3.03%   |
| ASIX Electronics         | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 26.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 10.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 5.88%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 4.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.94%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.94%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.94%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 2.94%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.47%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.47%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.47%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.47%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.47%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.47%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.47%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.47%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.47%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.47%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.47%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.47%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1         | 1.47%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.47%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.47%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1         | 1.47%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1.47%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.47%   |
| ASIX AX88772B                                                     | 1         | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 64        | 50.39%  |
| WiFi     | 60        | 47.24%  |
| Modem    | 2         | 1.57%   |
| Unknown  | 1         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 61.64%  |
| Ethernet | 27        | 36.99%  |
| Unknown  | 1         | 1.37%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 41        | 55.41%  |
| 1     | 27        | 36.49%  |
| 0     | 3         | 4.05%   |
| 3     | 2         | 2.7%    |
| 12    | 1         | 1.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 69        | 92%     |
| Yes  | 6         | 8%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 48.78%  |
| Broadcom                        | 5         | 12.2%   |
| Realtek Semiconductor           | 3         | 7.32%   |
| Qualcomm Atheros Communications | 3         | 7.32%   |
| Lite-On Technology              | 2         | 4.88%   |
| IMC Networks                    | 2         | 4.88%   |
| Cambridge Silicon Radio         | 2         | 4.88%   |
| Apple                           | 2         | 4.88%   |
| Hewlett-Packard                 | 1         | 2.44%   |
| Foxconn / Hon Hai               | 1         | 2.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13        | 31.71%  |
| Realtek Bluetooth Radio                             | 2         | 4.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.88%   |
| Intel AX201 Bluetooth                               | 2         | 4.88%   |
| Intel AX200 Bluetooth                               | 2         | 4.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.88%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.44%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.44%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.44%   |
| IMC Networks Bluetooth Device                       | 1         | 2.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 2.44%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.44%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 2.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.44%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.44%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.44%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 2.44%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.44%   |
| Apple Bluetooth Host Controller                     | 1         | 2.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 54        | 56.25%  |
| Nvidia              | 17        | 17.71%  |
| AMD                 | 16        | 16.67%  |
| Focusrite-Novation  | 2         | 2.08%   |
| Texas Instruments   | 1         | 1.04%   |
| SteelSeries ApS     | 1         | 1.04%   |
| Mark of the Unicorn | 1         | 1.04%   |
| Kingston Technology | 1         | 1.04%   |
| JMTek               | 1         | 1.04%   |
| GN Netcom           | 1         | 1.04%   |
| Creative Labs       | 1         | 1.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 6.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 5.22%   |
| AMD FCH Azalia Controller                                                                         | 6         | 5.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 3.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.48%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.74%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.74%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.74%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.74%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.74%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.87%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 1         | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.87%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.87%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.87%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.87%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.87%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.87%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.87%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 15        | 17.65%  |
| Samsung Electronics          | 12        | 14.12%  |
| Kingston                     | 12        | 14.12%  |
| Micron Technology            | 9         | 10.59%  |
| Unknown                      | 8         | 9.41%   |
| Crucial                      | 6         | 7.06%   |
| Corsair                      | 6         | 7.06%   |
| Ramaxel Technology           | 3         | 3.53%   |
| Nanya Technology             | 3         | 3.53%   |
| Unknown (ABCD)               | 2         | 2.35%   |
| G.Skill                      | 2         | 2.35%   |
| Transcend                    | 1         | 1.18%   |
| Teikon                       | 1         | 1.18%   |
| Smart                        | 1         | 1.18%   |
| PNY                          | 1         | 1.18%   |
| Patriot Memory (PDP Systems) | 1         | 1.18%   |
| Elpida                       | 1         | 1.18%   |
| A-DATA Technology            | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.2%    |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 2         | 2.2%    |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 2         | 2.2%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 2.2%    |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s                     | 1         | 1.1%    |
| Unknown RAM Module 512MB DIMM SDRAM                              | 1         | 1.1%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 1         | 1.1%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1.1%    |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 1.1%    |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                       | 1         | 1.1%    |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.1%    |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 1.1%    |
| Unknown RAM Module 1024MB DIMM DDR                               | 1         | 1.1%    |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s           | 1         | 1.1%    |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 1         | 1.1%    |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| SK hynix RAM Module 2048MB SODIMM DDR3 800MT/s                   | 1         | 1.1%    |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 1         | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.1%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.1%    |
| SK hynix RAM HMT351U7EFR8C-PB 4096MB DIMM DDR3 1600MT/s          | 1         | 1.1%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.1%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.1%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.1%    |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.1%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.1%    |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.1%    |
| SK hynix RAM H5AN8G6NCJR-XNC 4GB SODIMM DDR4 3200MT/s            | 1         | 1.1%    |
| Samsung RAM Module 2048MB SODIMM DDR2 533MT/s                    | 1         | 1.1%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.1%    |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 1.1%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.1%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.1%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.1%    |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 36        | 49.32%  |
| DDR4   | 25        | 34.25%  |
| DDR2   | 4         | 5.48%   |
| LPDDR3 | 3         | 4.11%   |
| LPDDR4 | 2         | 2.74%   |
| DDR    | 2         | 2.74%   |
| SDRAM  | 1         | 1.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 62.67%  |
| DIMM         | 23        | 30.67%  |
| Row Of Chips | 3         | 4%      |
| Chip         | 2         | 2.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 34.57%  |
| 4096  | 26        | 32.1%   |
| 2048  | 14        | 17.28%  |
| 16384 | 7         | 8.64%   |
| 1024  | 5         | 6.17%   |
| 512   | 1         | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 22        | 28.57%  |
| 2667    | 7         | 9.09%   |
| 3200    | 6         | 7.79%   |
| 2400    | 5         | 6.49%   |
| 2133    | 5         | 6.49%   |
| 1333    | 5         | 6.49%   |
| 1334    | 4         | 5.19%   |
| Unknown | 4         | 5.19%   |
| 1067    | 3         | 3.9%    |
| 3000    | 2         | 2.6%    |
| 2933    | 2         | 2.6%    |
| 1867    | 2         | 2.6%    |
| 1800    | 2         | 2.6%    |
| 667     | 2         | 2.6%    |
| 3733    | 1         | 1.3%    |
| 3600    | 1         | 1.3%    |
| 3466    | 1         | 1.3%    |
| 3100    | 1         | 1.3%    |
| 800     | 1         | 1.3%    |
| 533     | 1         | 1.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Lexmark International | 1         | 50%     |
| Brother Industries    | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 22.5%   |
| Acer                                   | 7         | 17.5%   |
| Realtek Semiconductor                  | 4         | 10%     |
| Quanta                                 | 3         | 7.5%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 7.5%    |
| Sunplus Innovation Technology          | 2         | 5%      |
| Lite-On Technology                     | 2         | 5%      |
| IMC Networks                           | 2         | 5%      |
| USB Camera                             | 1         | 2.5%    |
| Suyin                                  | 1         | 2.5%    |
| Sunplus Technology                     | 1         | 2.5%    |
| Microsoft                              | 1         | 2.5%    |
| Luxvisions Innotech Limited            | 1         | 2.5%    |
| Lenovo                                 | 1         | 2.5%    |
| GEMBIRD                                | 1         | 2.5%    |
| Apple                                  | 1         | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 3         | 7.5%    |
| Quanta VGA WebCam                                           | 2         | 5%      |
| Lite-On Integrated Camera                                   | 2         | 5%      |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 5%      |
| Acer Lenovo Integrated Webcam                               | 2         | 5%      |
| Acer BisonCam, NB Pro                                       | 2         | 5%      |
| USB Camera USB Camera                                       | 1         | 2.5%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 2.5%    |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode)     | 1         | 2.5%    |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 2.5%    |
| Sunplus Integrated_Webcam_HD                                | 1         | 2.5%    |
| Realtek USB2.0 camera                                       | 1         | 2.5%    |
| Realtek USB Camera                                          | 1         | 2.5%    |
| Realtek Integrated_Webcam_HD                                | 1         | 2.5%    |
| Realtek HD WebCam                                           | 1         | 2.5%    |
| Quanta HP Wide Vision FHD Camera                            | 1         | 2.5%    |
| Microsoft LifeCam HD-3000                                   | 1         | 2.5%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 1         | 2.5%    |
| Lenovo Integrated Webcam                                    | 1         | 2.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 2.5%    |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 2.5%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]           | 1         | 2.5%    |
| Chicony Webcam                                              | 1         | 2.5%    |
| Chicony USB 2.0 Camera                                      | 1         | 2.5%    |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 2.5%    |
| Chicony HP Truevision HD                                    | 1         | 2.5%    |
| Chicony HP Full-HD Camera                                   | 1         | 2.5%    |
| Chicony HD WebCam                                           | 1         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 1         | 2.5%    |
| Apple Built-in iSight                                       | 1         | 2.5%    |
| Acer Lenovo EasyCamera                                      | 1         | 2.5%    |
| Acer Integrated Camera                                      | 1         | 2.5%    |
| Acer EasyCamera                                             | 1         | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 2         | 50%     |
| Broadcom    | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 54        | 72.97%  |
| 1     | 14        | 18.92%  |
| 2     | 6         | 8.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 10        | 38.46%  |
| Fingerprint reader       | 10        | 38.46%  |
| Chipcard                 | 4         | 15.38%  |
| Multimedia controller    | 1         | 3.85%   |
| Communication controller | 1         | 3.85%   |

