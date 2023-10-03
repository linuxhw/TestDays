TUXEDO OS - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for TUXEDO OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 99

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Prestige 15 A10SC           | [6e53cd8a65](https://linux-hardware.org/?probe=6e53cd8a65) | Sep 30, 2023 |
| Metabox       | Prime-X X170KM              | [8ab33a8bd3](https://linux-hardware.org/?probe=8ab33a8bd3) | Sep 30, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [6d981e4890](https://linux-hardware.org/?probe=6d981e4890) | Sep 29, 2023 |
| Dell          | Inspiron 14 5420            | [ade3d11822](https://linux-hardware.org/?probe=ade3d11822) | Sep 24, 2023 |
| Schenker      | VISION 15 E23 (SVS15E23)    | [d905d3589d](https://linux-hardware.org/?probe=d905d3589d) | Sep 24, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [147b087f20](https://linux-hardware.org/?probe=147b087f20) | Sep 23, 2023 |
| Chuwi         | MiniBook X                  | [50d0819b3b](https://linux-hardware.org/?probe=50d0819b3b) | Sep 20, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [a4f7b61af6](https://linux-hardware.org/?probe=a4f7b61af6) | Sep 18, 2023 |
| HP            | Laptop 15-db1xxx            | [804223592d](https://linux-hardware.org/?probe=804223592d) | Sep 17, 2023 |
| HP            | Pavilion dv5                | [2c55682860](https://linux-hardware.org/?probe=2c55682860) | Sep 15, 2023 |
| HP            | Pavilion dv5                | [8d25f8969b](https://linux-hardware.org/?probe=8d25f8969b) | Sep 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS37F00     | [0eaf502e28](https://linux-hardware.org/?probe=0eaf502e28) | Sep 12, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [a28ff634a0](https://linux-hardware.org/?probe=a28ff634a0) | Sep 11, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [28283f9fcf](https://linux-hardware.org/?probe=28283f9fcf) | Sep 11, 2023 |
| HP            | ZBook 14u G5                | [9ff135c2a6](https://linux-hardware.org/?probe=9ff135c2a6) | Sep 09, 2023 |
| Apple         | MacBookPro9,2               | [abb6dcaeb2](https://linux-hardware.org/?probe=abb6dcaeb2) | Sep 09, 2023 |
| Apple         | MacBookPro9,2               | [1e6219cb6e](https://linux-hardware.org/?probe=1e6219cb6e) | Sep 09, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [c53e992822](https://linux-hardware.org/?probe=c53e992822) | Aug 26, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [b6e2112ccb](https://linux-hardware.org/?probe=b6e2112ccb) | Aug 13, 2023 |
| Dell          | Precision 7750              | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| TUXEDO        | N7x0WU                      | [1c2cb06178](https://linux-hardware.org/?probe=1c2cb06178) | Aug 06, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [64e640ff2b](https://linux-hardware.org/?probe=64e640ff2b) | Aug 04, 2023 |
| TUXEDO        | Aura 15 Gen2                | [07d668ee3d](https://linux-hardware.org/?probe=07d668ee3d) | Aug 03, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [c6078d0836](https://linux-hardware.org/?probe=c6078d0836) | Aug 02, 2023 |
| Lenovo        | ThinkPad E580 20KS003SUS    | [9b8485b740](https://linux-hardware.org/?probe=9b8485b740) | Aug 01, 2023 |
| HP            | Notebook                    | [beef8e7fce](https://linux-hardware.org/?probe=beef8e7fce) | Jul 25, 2023 |
| HP            | Notebook                    | [4746f66332](https://linux-hardware.org/?probe=4746f66332) | Jul 23, 2023 |
| Lenovo        | G580 20150                  | [bcd1c01ad6](https://linux-hardware.org/?probe=bcd1c01ad6) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | [390008fe3c](https://linux-hardware.org/?probe=390008fe3c) | Jul 15, 2023 |
| HP            | Laptop 15-dw3xxx            | [fd0926d15b](https://linux-hardware.org/?probe=fd0926d15b) | Jul 14, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [26fda3b894](https://linux-hardware.org/?probe=26fda3b894) | Jul 14, 2023 |
| Dell          | Latitude E6530              | [25cbd87821](https://linux-hardware.org/?probe=25cbd87821) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | [29a9ad60a6](https://linux-hardware.org/?probe=29a9ad60a6) | Jul 13, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [2015dd83cb](https://linux-hardware.org/?probe=2015dd83cb) | Jul 12, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| TUXEDO        | Book XUX7 Gen13             | [e480e61359](https://linux-hardware.org/?probe=e480e61359) | Jul 06, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [3d599df965](https://linux-hardware.org/?probe=3d599df965) | Jul 02, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [b15b3b6025](https://linux-hardware.org/?probe=b15b3b6025) | Jun 30, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [ed4a581e3e](https://linux-hardware.org/?probe=ed4a581e3e) | Jun 28, 2023 |
| MSI           | GE75 Raider 10SF            | [c2a5aeb291](https://linux-hardware.org/?probe=c2a5aeb291) | Jun 28, 2023 |
| TUXEDO        | P64_HJ,HK1                  | [4c542d50e7](https://linux-hardware.org/?probe=4c542d50e7) | Jun 27, 2023 |
| BESSTAR Te... | X400                        | [8e98b345cf](https://linux-hardware.org/?probe=8e98b345cf) | Jun 26, 2023 |
| Acer          | Swift SFX14-51G             | [c8f3981a52](https://linux-hardware.org/?probe=c8f3981a52) | Jun 23, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [6fb60cf84a](https://linux-hardware.org/?probe=6fb60cf84a) | Jun 18, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [c47936b50c](https://linux-hardware.org/?probe=c47936b50c) | Jun 09, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [c16266c1c9](https://linux-hardware.org/?probe=c16266c1c9) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | [f75fb35204](https://linux-hardware.org/?probe=f75fb35204) | May 28, 2023 |
| ASUSTek       | K55VJ                       | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek       | K55VJ                       | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Lenovo        | G580 20150                  | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| Lenovo        | IdeaPad N581 7505           | [5d340c1aa2](https://linux-hardware.org/?probe=5d340c1aa2) | May 04, 2023 |
| HP            | Pavilion dv6                | [be01072653](https://linux-hardware.org/?probe=be01072653) | May 03, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [756500f10b](https://linux-hardware.org/?probe=756500f10b) | May 03, 2023 |
| HP            | Pavilion dv6                | [87f0c054fa](https://linux-hardware.org/?probe=87f0c054fa) | May 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Dell          | Inspiron 16 5630            | [7bfe5bb892](https://linux-hardware.org/?probe=7bfe5bb892) | Apr 27, 2023 |
| Dell          | Latitude 7530               | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| Dell          | Vostro 3550                 | [3b77631ed6](https://linux-hardware.org/?probe=3b77631ed6) | Apr 04, 2023 |
| Unknown       | Unknown                     | [22c0e4cdec](https://linux-hardware.org/?probe=22c0e4cdec) | Apr 02, 2023 |
| Lenovo        | ThinkPad T490 20N3SBU219    | [b8e8125150](https://linux-hardware.org/?probe=b8e8125150) | Mar 27, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [885b757cdc](https://linux-hardware.org/?probe=885b757cdc) | Mar 24, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [5e01f2c134](https://linux-hardware.org/?probe=5e01f2c134) | Mar 22, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [0db668b5ec](https://linux-hardware.org/?probe=0db668b5ec) | Mar 18, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [094b530ce7](https://linux-hardware.org/?probe=094b530ce7) | Mar 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [3fcbfecb5a](https://linux-hardware.org/?probe=3fcbfecb5a) | Mar 14, 2023 |
| Dell          | Precision 7720              | [dbe0d4c5c4](https://linux-hardware.org/?probe=dbe0d4c5c4) | Mar 12, 2023 |
| Dell          | Vostro 3550                 | [40a0328a5f](https://linux-hardware.org/?probe=40a0328a5f) | Mar 11, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK U7412              | [980dd72471](https://linux-hardware.org/?probe=980dd72471) | Mar 06, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [7a21cf8349](https://linux-hardware.org/?probe=7a21cf8349) | Mar 05, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [20d14c7576](https://linux-hardware.org/?probe=20d14c7576) | Mar 04, 2023 |
| Lenovo        | G50-80 80E5                 | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| Dell          | Vostro 3550                 | [1e1da6a575](https://linux-hardware.org/?probe=1e1da6a575) | Feb 24, 2023 |
| Dell          | Vostro 3550                 | [497a8d66e5](https://linux-hardware.org/?probe=497a8d66e5) | Feb 22, 2023 |
| Dell          | Precision 7720              | [2f7837d5b6](https://linux-hardware.org/?probe=2f7837d5b6) | Feb 21, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| HP            | EliteBook 2570p             | [ed14b057dd](https://linux-hardware.org/?probe=ed14b057dd) | Feb 09, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [e163d98802](https://linux-hardware.org/?probe=e163d98802) | Jan 28, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [fa53a29f7e](https://linux-hardware.org/?probe=fa53a29f7e) | Jan 01, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [731b31c845](https://linux-hardware.org/?probe=731b31c845) | Dec 02, 2022 |
| TUXEDO        | N13xWU                      | [55935f091d](https://linux-hardware.org/?probe=55935f091d) | Dec 01, 2022 |
| TUXEDO        | Unknown                     | [fd06ca029c](https://linux-hardware.org/?probe=fd06ca029c) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [5043f6c54e](https://linux-hardware.org/?probe=5043f6c54e) | Nov 20, 2022 |
| HP            | EliteBook 820 G2            | [5d82e9f6ac](https://linux-hardware.org/?probe=5d82e9f6ac) | Nov 19, 2022 |
| HP            | EliteBook 820 G2            | [9d20af2c30](https://linux-hardware.org/?probe=9d20af2c30) | Nov 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | [d58eb8b2f0](https://linux-hardware.org/?probe=d58eb8b2f0) | Oct 30, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | [032bc01698](https://linux-hardware.org/?probe=032bc01698) | Oct 30, 2022 |
| TUXEDO        | Unknown                     | [99555fc4eb](https://linux-hardware.org/?probe=99555fc4eb) | Oct 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| ASUSTek       | BU201LAV                    | [9d1fe7cb6f](https://linux-hardware.org/?probe=9d1fe7cb6f) | Oct 19, 2022 |
| Apple         | MacBookPro8,1               | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| Acer          | TravelMate 8572T            | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| TUXEDO OS 22.04 | 77        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 77        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 6.1.0-1009-tuxedo    | 13        | 15.66%  |
| 6.2.0-10018-tuxedo   | 10        | 12.05%  |
| 6.2.0-10005-tuxedo   | 9         | 10.84%  |
| 6.2.0-10022-tuxedo   | 8         | 9.64%   |
| 6.2.0-10011-tuxedo   | 8         | 9.64%   |
| 6.2.0-10007-tuxedo   | 8         | 9.64%   |
| 6.2.0-10010-tuxedo   | 6         | 7.23%   |
| 5.15.0-10058-tuxedo  | 4         | 4.82%   |
| 5.15.0-10048-tuxedo  | 4         | 4.82%   |
| 5.15.0-10053-tuxedo  | 3         | 3.61%   |
| 5.15.0-10052-tuxedo  | 3         | 3.61%   |
| 5.15.0-10050-tuxedo  | 2         | 2.41%   |
| 6.5.4-060504-generic | 1         | 1.2%    |
| 6.2.0-10014-tuxedo   | 1         | 1.2%    |
| 6.0.0-1010-oem       | 1         | 1.2%    |
| 5.15.0-10057-tuxedo  | 1         | 1.2%    |
| 5.15.0-10056-tuxedo  | 1         | 1.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 50        | 60.24%  |
| 5.15.0  | 18        | 21.69%  |
| 6.1.0   | 13        | 15.66%  |
| 6.5.4   | 1         | 1.2%    |
| 6.0.0   | 1         | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 50        | 60.24%  |
| 5.15    | 18        | 21.69%  |
| 6.1     | 13        | 15.66%  |
| 6.5     | 1         | 1.2%    |
| 6.0     | 1         | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 77        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| KDE5 | 77        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 77        | 98.72%  |
| Wayland | 1         | 1.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 61        | 77.22%  |
| SDDM    | 18        | 22.78%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| de_DE | 36        | 46.75%  |
| en_US | 18        | 23.38%  |
| en_GB | 6         | 7.79%   |
| en_AU | 3         | 3.9%    |
| pl_PL | 2         | 2.6%    |
| it_IT | 2         | 2.6%    |
| fr_FR | 2         | 2.6%    |
| en_AG | 2         | 2.6%    |
| pt_PT | 1         | 1.3%    |
| pt_BR | 1         | 1.3%    |
| hu_HU | 1         | 1.3%    |
| es_ES | 1         | 1.3%    |
| en_ZA | 1         | 1.3%    |
| en_DK | 1         | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 63        | 80.77%  |
| EFI  | 15        | 19.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 66        | 85.71%  |
| Btrfs   | 6         | 7.79%   |
| Tmpfs   | 3         | 3.9%    |
| Overlay | 2         | 2.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 61        | 77.22%  |
| GPT     | 16        | 20.25%  |
| MBR     | 2         | 2.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 94.87%  |
| Yes       | 4         | 5.13%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 93.59%  |
| Yes       | 5         | 6.41%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| TUXEDO           | 30        | 38.96%  |
| Lenovo           | 11        | 14.29%  |
| Hewlett-Packard  | 9         | 11.69%  |
| Dell             | 8         | 10.39%  |
| ASUSTek Computer | 4         | 5.19%   |
| Apple            | 4         | 5.19%   |
| MSI              | 2         | 2.6%    |
| Acer             | 2         | 2.6%    |
| Schenker         | 1         | 1.3%    |
| Notebook         | 1         | 1.3%    |
| Metabox          | 1         | 1.3%    |
| Fujitsu          | 1         | 1.3%    |
| Chuwi            | 1         | 1.3%    |
| BESSTAR Tech     | 1         | 1.3%    |
| Unknown          | 1         | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| TUXEDO InfinityBook S 15/17 Gen7    | 4         | 5.19%   |
| Unknown                             | 3         | 3.9%    |
| TUXEDO Stellaris/Polaris AMD Gen4   | 2         | 2.6%    |
| TUXEDO Stellaris Intel Gen5         | 2         | 2.6%    |
| TUXEDO Pulse 15 Gen2                | 2         | 2.6%    |
| TUXEDO Pulse 15 Gen1                | 2         | 2.6%    |
| TUXEDO InfinityBook Pro Gen7 (MK2)  | 2         | 2.6%    |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 2         | 2.6%    |
| TUXEDO InfinityBook Pro 14 Gen6     | 2         | 2.6%    |
| Apple MacBookPro8,1                 | 2         | 2.6%    |
| TUXEDO XMG FUSION 15 (XFU15L19)     | 1         | 1.3%    |
| TUXEDO Stellaris AMD Gen3 (CZN)     | 1         | 1.3%    |
| TUXEDO Polaris AMD Gen3 (CZN)       | 1         | 1.3%    |
| TUXEDO Polaris 15 AMD Gen1          | 1         | 1.3%    |
| TUXEDO P64_HJ,HK1                   | 1         | 1.3%    |
| TUXEDO N7x0WU                       | 1         | 1.3%    |
| TUXEDO N13xWU                       | 1         | 1.3%    |
| TUXEDO InfinityBook S 15 Gen6       | 1         | 1.3%    |
| TUXEDO Book XUX7 Gen13              | 1         | 1.3%    |
| TUXEDO Aura 15 Gen2                 | 1         | 1.3%    |
| Schenker VISION 15 E23 (SVS15E23)   | 1         | 1.3%    |
| Notebook W65_W67RB                  | 1         | 1.3%    |
| MSI Prestige 15 A10SC               | 1         | 1.3%    |
| MSI GE75 Raider 10SF                | 1         | 1.3%    |
| Metabox Prime-X X170KM              | 1         | 1.3%    |
| Lenovo Yoga S740-15IRH 81NX         | 1         | 1.3%    |
| Lenovo ThinkPad X200 Tablet 7450WN9 | 1         | 1.3%    |
| Lenovo ThinkPad T490 20N3SBU219     | 1         | 1.3%    |
| Lenovo ThinkPad P50 20EQS37F00      | 1         | 1.3%    |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700 | 1         | 1.3%    |
| Lenovo ThinkPad E580 20KS003SUS     | 1         | 1.3%    |
| Lenovo ThinkBook 14 G2 ARE 20VF     | 1         | 1.3%    |
| Lenovo Legion 5 15ACH6H 82JU        | 1         | 1.3%    |
| Lenovo IdeaPad N581 7505            | 1         | 1.3%    |
| Lenovo G580 20150                   | 1         | 1.3%    |
| Lenovo G50-80 80E5                  | 1         | 1.3%    |
| HP ZBook 14u G5                     | 1         | 1.3%    |
| HP Pavilion dv6                     | 1         | 1.3%    |
| HP Pavilion dv5                     | 1         | 1.3%    |
| HP OMEN Laptop 15-en0xxx            | 1         | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 11        | 14.29%  |
| TUXEDO Stellaris    | 5         | 6.49%   |
| Lenovo ThinkPad     | 5         | 6.49%   |
| TUXEDO Pulse        | 4         | 5.19%   |
| Unknown             | 3         | 3.9%    |
| TUXEDO Polaris      | 2         | 2.6%    |
| HP Pavilion         | 2         | 2.6%    |
| HP Laptop           | 2         | 2.6%    |
| HP EliteBook        | 2         | 2.6%    |
| Dell Precision      | 2         | 2.6%    |
| Dell Latitude       | 2         | 2.6%    |
| Dell Inspiron       | 2         | 2.6%    |
| Apple MacBookPro8   | 2         | 2.6%    |
| TUXEDO XMG          | 1         | 1.3%    |
| TUXEDO P64          | 1         | 1.3%    |
| TUXEDO N7x0WU       | 1         | 1.3%    |
| TUXEDO N13xWU       | 1         | 1.3%    |
| TUXEDO Book         | 1         | 1.3%    |
| TUXEDO Aura         | 1         | 1.3%    |
| Schenker VISION     | 1         | 1.3%    |
| Notebook W65        | 1         | 1.3%    |
| MSI Prestige        | 1         | 1.3%    |
| MSI GE75            | 1         | 1.3%    |
| Metabox Prime-X     | 1         | 1.3%    |
| Lenovo Yoga         | 1         | 1.3%    |
| Lenovo ThinkBook    | 1         | 1.3%    |
| Lenovo Legion       | 1         | 1.3%    |
| Lenovo IdeaPad      | 1         | 1.3%    |
| Lenovo G580         | 1         | 1.3%    |
| Lenovo G50-80       | 1         | 1.3%    |
| HP ZBook            | 1         | 1.3%    |
| HP OMEN             | 1         | 1.3%    |
| HP Notebook         | 1         | 1.3%    |
| Fujitsu LIFEBOOK    | 1         | 1.3%    |
| Dell Vostro         | 1         | 1.3%    |
| Dell Venue          | 1         | 1.3%    |
| Chuwi MiniBook      | 1         | 1.3%    |
| BESSTAR Tech X400   | 1         | 1.3%    |
| ASUS Zephyrus       | 1         | 1.3%    |
| ASUS ROG            | 1         | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 20        | 25.97%  |
| 2020 | 10        | 12.99%  |
| 2021 | 7         | 9.09%   |
| 2019 | 7         | 9.09%   |
| 2015 | 7         | 9.09%   |
| 2012 | 6         | 7.79%   |
| 2023 | 5         | 6.49%   |
| 2017 | 4         | 5.19%   |
| 2011 | 3         | 3.9%    |
| 2018 | 2         | 2.6%    |
| 2014 | 2         | 2.6%    |
| 2008 | 2         | 2.6%    |
| 2010 | 1         | 1.3%    |
| 2009 | 1         | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 77        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 77        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 17        | 22.08%  |
| 16.01-24.0  | 16        | 20.78%  |
| 8.01-16.0   | 15        | 19.48%  |
| 4.01-8.0    | 12        | 15.58%  |
| 64.01-256.0 | 11        | 14.29%  |
| 3.01-4.0    | 4         | 5.19%   |
| 24.01-32.0  | 2         | 2.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 31        | 38.27%  |
| 2.01-3.0   | 16        | 19.75%  |
| 1.01-2.0   | 16        | 19.75%  |
| 3.01-4.0   | 11        | 13.58%  |
| 8.01-16.0  | 5         | 6.17%   |
| 16.01-24.0 | 2         | 2.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 56.41%  |
| 2      | 28        | 35.9%   |
| 3      | 5         | 6.41%   |
| 4      | 1         | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 84.42%  |
| Yes       | 12        | 15.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 81.82%  |
| No        | 14        | 18.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 98.7%   |
| No        | 1         | 1.3%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 90.91%  |
| No        | 7         | 9.09%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 40        | 51.95%  |
| USA          | 10        | 12.99%  |
| UK           | 4         | 5.19%   |
| Switzerland  | 3         | 3.9%    |
| Australia    | 3         | 3.9%    |
| Spain        | 2         | 2.6%    |
| Portugal     | 2         | 2.6%    |
| Poland       | 2         | 2.6%    |
| France       | 2         | 2.6%    |
| Austria      | 2         | 2.6%    |
| Turkey       | 1         | 1.3%    |
| South Africa | 1         | 1.3%    |
| Netherlands  | 1         | 1.3%    |
| Denmark      | 1         | 1.3%    |
| Czechia      | 1         | 1.3%    |
| Bulgaria     | 1         | 1.3%    |
| Brazil       | 1         | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Munich                 | 5         | 6.41%   |
| Vienna                 | 2         | 2.56%   |
| Schweinfurt            | 2         | 2.56%   |
| Nuremberg              | 2         | 2.56%   |
| Lucerne                | 2         | 2.56%   |
| Brisbane               | 2         | 2.56%   |
| Berlin                 | 2         | 2.56%   |
| Zurich                 | 1         | 1.28%   |
| Zabrze                 | 1         | 1.28%   |
| Wembley                | 1         | 1.28%   |
| Watertown              | 1         | 1.28%   |
| Warsaw                 | 1         | 1.28%   |
| Walsall                | 1         | 1.28%   |
| Venlo                  | 1         | 1.28%   |
| Vallejo                | 1         | 1.28%   |
| Stuttgart              | 1         | 1.28%   |
| Stockstadt am Main     | 1         | 1.28%   |
| Solingen               | 1         | 1.28%   |
| Sistov                 | 1         | 1.28%   |
| Seattle                | 1         | 1.28%   |
| Schwarzenberg          | 1         | 1.28%   |
| Santa Cruz de Tenerife | 1         | 1.28%   |
| Rio Maior              | 1         | 1.28%   |
| Reno                   | 1         | 1.28%   |
| Rennes                 | 1         | 1.28%   |
| Redcar                 | 1         | 1.28%   |
| Pruem                  | 1         | 1.28%   |
| Prague                 | 1         | 1.28%   |
| Perth                  | 1         | 1.28%   |
| Perrysburg             | 1         | 1.28%   |
| Paris                  | 1         | 1.28%   |
| Paderborn              | 1         | 1.28%   |
| Neuwied                | 1         | 1.28%   |
| Nashville              | 1         | 1.28%   |
| Melton Mowbray         | 1         | 1.28%   |
| Mannheim               | 1         | 1.28%   |
| Lippstadt              | 1         | 1.28%   |
| Leipzig                | 1         | 1.28%   |
| Lehre                  | 1         | 1.28%   |
| Langenhagen            | 1         | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 44        | 58     | 42.72%  |
| Sandisk                     | 10        | 11     | 9.71%   |
| Seagate                     | 7         | 7      | 6.8%    |
| Kingston                    | 5         | 5      | 4.85%   |
| Hitachi                     | 4         | 6      | 3.88%   |
| WDC                         | 3         | 3      | 2.91%   |
| Toshiba                     | 3         | 4      | 2.91%   |
| Unknown                     | 2         | 2      | 1.94%   |
| SPCC                        | 2         | 2      | 1.94%   |
| SK hynix                    | 2         | 3      | 1.94%   |
| Phison Electronics          | 2         | 2      | 1.94%   |
| Micron Technology           | 2         | 2      | 1.94%   |
| USB3.0                      | 1         | 1      | 0.97%   |
| Transcend                   | 1         | 1      | 0.97%   |
| Phison                      | 1         | 3      | 0.97%   |
| OWC                         | 1         | 1      | 0.97%   |
| Netac                       | 1         | 1      | 0.97%   |
| Micron/Crucial Technology   | 1         | 1      | 0.97%   |
| LITEONIT                    | 1         | 1      | 0.97%   |
| Lenovo                      | 1         | 1      | 0.97%   |
| Kingston Technology Company | 1         | 1      | 0.97%   |
| Kingchuxing                 | 1         | 1      | 0.97%   |
| Intenso                     | 1         | 1      | 0.97%   |
| Intel                       | 1         | 1      | 0.97%   |
| CT1000BX                    | 1         | 1      | 0.97%   |
| Crucial                     | 1         | 1      | 0.97%   |
| ASMedia                     | 1         | 1      | 0.97%   |
| Apple                       | 1         | 1      | 0.97%   |
| ADATA Technology            | 1         | 1      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 10        | 9.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 7         | 6.48%   |
| Samsung SSD 980 500GB                               | 5         | 4.63%   |
| Samsung SSD 980 1TB                                 | 5         | 4.63%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 3         | 2.78%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 2.78%   |
| SanDisk SDSSDA240G 240GB                            | 2         | 1.85%   |
| Samsung SSD 980 PRO 500GB                           | 2         | 1.85%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 1.85%   |
| Samsung SSD 850 EVO 1TB                             | 2         | 1.85%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.85%   |
| Hitachi HTS727550A9E364 500GB                       | 2         | 1.85%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 1         | 0.93%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.93%   |
| WDC WD Elements SE SSD 1TB                          | 1         | 0.93%   |
| USB3.0 Super Speed 500GB                            | 1         | 0.93%   |
| Unknown MMC Card  64GB                              | 1         | 0.93%   |
| Unknown MMC Card  2GB                               | 1         | 0.93%   |
| Transcend TS512GSSD230S 512GB                       | 1         | 0.93%   |
| Toshiba XG4 NVMe SSD Controller 512GB               | 1         | 0.93%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.93%   |
| Toshiba BG3 NVMe SSD Controller 512GB               | 1         | 0.93%   |
| SPCC M.2 SSD 256GB                                  | 1         | 0.93%   |
| SPCC M.2 PCIe SSD 1TB                               | 1         | 0.93%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 1         | 0.93%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 0.93%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 0.93%   |
| Seagate ST500LM034-2GH17A 500GB                     | 1         | 0.93%   |
| Seagate ST250LT003-9YG14C 250GB                     | 1         | 0.93%   |
| Seagate ST2000LM015-2E8174 2TB                      | 1         | 0.93%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 0.93%   |
| Seagate Expansion 1TB                               | 1         | 0.93%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB             | 1         | 0.93%   |
| Sandisk WDC PC SN530 SDBPMPZ-512G-1101 512GB        | 1         | 0.93%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1TB           | 1         | 0.93%   |
| Sandisk WD Blue SN570 1TB                           | 1         | 0.93%   |
| Sandisk WD Black SN850 1TB                          | 1         | 0.93%   |
| Sandisk Ultra 3D NVMe 1TB                           | 1         | 0.93%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 0.93%   |
| Samsung SSD 990 PRO 1TB                             | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 42.86%  |
| Hitachi | 4         | 6      | 28.57%  |
| WDC     | 2         | 2      | 14.29%  |
| USB3.0  | 1         | 1      | 7.14%   |
| Toshiba | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 33.33%  |
| SanDisk             | 3         | 3      | 11.11%  |
| Kingston            | 3         | 3      | 11.11%  |
| WDC                 | 1         | 1      | 3.7%    |
| Transcend           | 1         | 1      | 3.7%    |
| SPCC                | 1         | 1      | 3.7%    |
| SK hynix            | 1         | 2      | 3.7%    |
| OWC                 | 1         | 1      | 3.7%    |
| Netac               | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |
| LITEONIT            | 1         | 1      | 3.7%    |
| Intenso             | 1         | 1      | 3.7%    |
| CT1000BX            | 1         | 1      | 3.7%    |
| Crucial             | 1         | 1      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 52        | 76     | 55.32%  |
| SSD     | 24        | 28     | 25.53%  |
| HDD     | 14        | 16     | 14.89%  |
| MMC     | 2         | 2      | 2.13%   |
| Unknown | 2         | 2      | 2.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 52        | 76     | 56.52%  |
| SATA | 33        | 41     | 35.87%  |
| SAS  | 5         | 5      | 5.43%   |
| MMC  | 2         | 2      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 29     | 60.53%  |
| 0.51-1.0   | 14        | 14     | 36.84%  |
| 1.01-2.0   | 1         | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 22        | 28.57%  |
| 251-500        | 16        | 20.78%  |
| 101-250        | 16        | 20.78%  |
| 1001-2000      | 9         | 11.69%  |
| 1-20           | 4         | 5.19%   |
| More than 3000 | 3         | 3.9%    |
| 2001-3000      | 3         | 3.9%    |
| Unknown        | 2         | 2.6%    |
| 21-50          | 1         | 1.3%    |
| 51-100         | 1         | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 24        | 30.38%  |
| 1-20      | 24        | 30.38%  |
| 101-250   | 12        | 15.19%  |
| 251-500   | 6         | 7.59%   |
| 51-100    | 6         | 7.59%   |
| 501-1000  | 3         | 3.8%    |
| 1001-2000 | 2         | 2.53%   |
| Unknown   | 2         | 2.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 61        | 98     | 76.25%  |
| Works    | 19        | 26     | 23.75%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 37        | 35.58%  |
| Intel                        | 35        | 33.65%  |
| AMD                          | 10        | 9.62%   |
| SanDisk                      | 7         | 6.73%   |
| Phison Electronics           | 3         | 2.88%   |
| Kingston Technology Company  | 3         | 2.88%   |
| Toshiba America Info Systems | 2         | 1.92%   |
| SK hynix                     | 1         | 0.96%   |
| Silicon Motion               | 1         | 0.96%   |
| Seagate Technology           | 1         | 0.96%   |
| Micron/Crucial Technology    | 1         | 0.96%   |
| Micron Technology            | 1         | 0.96%   |
| Lenovo                       | 1         | 0.96%   |
| ADATA Technology             | 1         | 0.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 13        | 12.15%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 11        | 10.28%  |
| Samsung NVMe SSD Controller 980                                               | 10        | 9.35%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 9         | 8.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 6.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 4         | 3.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 3         | 2.8%    |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 2.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 3         | 2.8%    |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                            | 2         | 1.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.87%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 1.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.87%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 1.87%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.93%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1         | 0.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 1         | 0.93%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 0.93%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                     | 1         | 0.93%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 0.93%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                         | 1         | 0.93%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                         | 1         | 0.93%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 0.93%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                   | 1         | 0.93%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1         | 0.93%   |
| Phison E12 NVMe Controller                                                    | 1         | 0.93%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1         | 0.93%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 1         | 0.93%   |
| Lenovo LENSE30256GMSP34MEAT3TA                                                | 1         | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 0.93%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                 | 1         | 0.93%   |
| Kingston Company NVMe Controller                                              | 1         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation         | 1         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 0.93%   |
| Intel SSD 660P Series                                                         | 1         | 0.93%   |
| Intel SATA Controller [RAID mode]                                             | 1         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 52        | 52.53%  |
| SATA | 40        | 40.4%   |
| RAID | 6         | 6.06%   |
| IDE  | 1         | 1.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 75.32%  |
| AMD    | 19        | 24.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H           | 4         | 5.19%   |
| Intel 12th Gen Core i7-1260P            | 4         | 5.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 3.9%    |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 3         | 3.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 2.6%    |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 2         | 2.6%    |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 2.6%    |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 2.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 2.6%    |
| Intel 13th Gen Core i9-13900HX          | 2         | 2.6%    |
| Intel 12th Gen Core i7-1255U            | 2         | 2.6%    |
| Intel 12th Gen Core i5-1240P            | 2         | 2.6%    |
| AMD Ryzen 7 6800H with Radeon Graphics  | 2         | 2.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 2.6%    |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 2.6%    |
| AMD Ryzen 5 4600H with Radeon Graphics  | 2         | 2.6%    |
| Intel Xeon W-10855M CPU @ 2.80GHz       | 1         | 1.3%    |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 1.3%    |
| Intel N100                              | 1         | 1.3%    |
| Intel Core i9-10900KF CPU @ 3.70GHz     | 1         | 1.3%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1.3%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.3%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 1.3%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.3%    |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.3%    |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.3%    |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.3%    |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 1.3%    |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.3%    |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 1.3%    |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.3%    |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 1.3%    |
| Intel Core i5-8365U CPU @ 1.60GHz       | 1         | 1.3%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.3%    |
| Intel Core i5-5250U CPU @ 1.60GHz       | 1         | 1.3%    |
| Intel Core i5-4300Y CPU @ 1.60GHz       | 1         | 1.3%    |
| Intel Core i5-2450M CPU @ 2.50GHz       | 1         | 1.3%    |
| Intel Core i5 CPU M 540 @ 2.53GHz       | 1         | 1.3%    |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz    | 1         | 1.3%    |
| Intel Celeron CPU 1037U @ 1.80GHz       | 1         | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 22        | 28.57%  |
| Intel Core i7    | 21        | 27.27%  |
| Intel Core i5    | 10        | 12.99%  |
| AMD Ryzen 7      | 9         | 11.69%  |
| AMD Ryzen 5      | 4         | 5.19%   |
| AMD Ryzen 9      | 2         | 2.6%    |
| Intel Xeon       | 1         | 1.3%    |
| Intel Pentium    | 1         | 1.3%    |
| Intel Core i9    | 1         | 1.3%    |
| Intel Core 2 Duo | 1         | 1.3%    |
| Intel Celeron    | 1         | 1.3%    |
| AMD Turion II    | 1         | 1.3%    |
| AMD Ryzen 5 PRO  | 1         | 1.3%    |
| AMD Ryzen 3      | 1         | 1.3%    |
| AMD A8           | 1         | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 24        | 31.17%  |
| 2      | 15        | 19.48%  |
| 8      | 11        | 14.29%  |
| 6      | 11        | 14.29%  |
| 12     | 7         | 9.09%   |
| 14     | 4         | 5.19%   |
| 10     | 3         | 3.9%    |
| 24     | 2         | 2.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 77        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 70        | 90.91%  |
| 1      | 7         | 9.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 77        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 87.34%  |
| 0x906a4    | 2         | 2.53%   |
| 0x906ea    | 1         | 1.27%   |
| 0x906e9    | 1         | 1.27%   |
| 0x906a3    | 1         | 1.27%   |
| 0x806c1    | 1         | 1.27%   |
| 0x306d4    | 1         | 1.27%   |
| 0x0a50000c | 1         | 1.27%   |
| 0x08608103 | 1         | 1.27%   |
| 0x010000c8 | 1         | 1.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 17        | 22.08%  |
| KabyLake         | 11        | 14.29%  |
| IvyBridge        | 7         | 9.09%   |
| Zen 2            | 6         | 7.79%   |
| Alderlake Hybrid | 6         | 7.79%   |
| CometLake        | 5         | 6.49%   |
| TigerLake        | 4         | 5.19%   |
| SandyBridge      | 4         | 5.19%   |
| Zen 3            | 3         | 3.9%    |
| Broadwell        | 3         | 3.9%    |
| Zen+             | 2         | 2.6%    |
| Skylake          | 2         | 2.6%    |
| Haswell          | 2         | 2.6%    |
| Westmere         | 1         | 1.3%    |
| Puma             | 1         | 1.3%    |
| Penryn           | 1         | 1.3%    |
| K10              | 1         | 1.3%    |
| Gracemont        | 1         | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 55        | 51.4%   |
| Nvidia | 30        | 28.04%  |
| AMD    | 22        | 20.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P Integrated Graphics Controller                         | 10        | 9.35%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 6.54%   |
| AMD Renoir                                                                | 6         | 5.61%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 4         | 3.74%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 4         | 3.74%   |
| Intel UHD Graphics 620                                                    | 4         | 3.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 3.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 3.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.74%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 3         | 2.8%    |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 3         | 2.8%    |
| AMD Rembrandt [Radeon 680M]                                               | 3         | 2.8%    |
| AMD Lucienne                                                              | 3         | 2.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.87%   |
| Nvidia GF108M [GeForce GT 635M]                                           | 2         | 1.87%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                           | 2         | 1.87%   |
| Intel Raptor Lake-S UHD Graphics                                          | 2         | 1.87%   |
| Intel HD Graphics 630                                                     | 2         | 1.87%   |
| Intel HD Graphics 5500                                                    | 2         | 1.87%   |
| Intel HD Graphics 530                                                     | 2         | 1.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.87%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 2         | 1.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.87%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                             | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.93%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.93%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.93%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.93%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 0.93%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 0.93%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 1         | 0.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 0.93%   |
| Intel HD Graphics 6000                                                    | 1         | 0.93%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]            | 1         | 0.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 42.31%  |
| Intel + Nvidia | 18        | 23.08%  |
| 1 x AMD        | 11        | 14.1%   |
| AMD + Nvidia   | 8         | 10.26%  |
| 1 x Nvidia     | 4         | 5.13%   |
| Intel + AMD    | 4         | 5.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 52        | 67.53%  |
| Proprietary | 24        | 31.17%  |
| Unknown     | 1         | 1.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 67.95%  |
| 5.01-6.0   | 9         | 11.54%  |
| 7.01-8.0   | 6         | 7.69%   |
| 3.01-4.0   | 5         | 6.41%   |
| 1.01-2.0   | 2         | 2.56%   |
| 8.01-16.0  | 2         | 2.56%   |
| 0.01-0.5   | 1         | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 28        | 29.17%  |
| AU Optronics        | 15        | 15.63%  |
| Samsung Electronics | 9         | 9.38%   |
| LG Display          | 7         | 7.29%   |
| Chimei Innolux      | 6         | 6.25%   |
| CSO                 | 4         | 4.17%   |
| Apple               | 4         | 4.17%   |
| Goldstar            | 3         | 3.13%   |
| Dell                | 3         | 3.13%   |
| Acer                | 3         | 3.13%   |
| Lenovo              | 2         | 2.08%   |
| AOC                 | 2         | 2.08%   |
| Yamaha              | 1         | 1.04%   |
| Sony                | 1         | 1.04%   |
| Sharp               | 1         | 1.04%   |
| SGT                 | 1         | 1.04%   |
| RTK                 | 1         | 1.04%   |
| PANDA               | 1         | 1.04%   |
| Iiyama              | 1         | 1.04%   |
| Hewlett-Packard     | 1         | 1.04%   |
| BenQ                | 1         | 1.04%   |
| ASUSTek Computer    | 1         | 1.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 5         | 5.1%    |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 4         | 4.08%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 4.08%   |
| BOE LCD Monitor BOE0AF0 2560x1600 344x215mm 16.0-inch                   | 2         | 2.04%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                   | 2         | 2.04%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 2         | 2.04%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 2.04%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                  | 2         | 2.04%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 1.02%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                           | 1         | 1.02%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 1.02%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 1.02%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 1.02%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch       | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1.02%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 1.02%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 1         | 1.02%   |
| RTK Wimaxit FHD RTK5A5B 1920x1080 344x195mm 15.6-inch                   | 1         | 1.02%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 1.02%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch            | 1         | 1.02%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 1.02%   |
| LG Display LCD Monitor LGD0545 3200x1800 293x165mm 13.2-inch            | 1         | 1.02%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch            | 1         | 1.02%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 1.02%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 1.02%   |
| LG Display LCD Monitor LGD0293 1366x768 321x181mm 14.5-inch             | 1         | 1.02%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                | 1         | 1.02%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                 | 1         | 1.02%   |
| Iiyama PL3466WQ IVM7627 3440x1440 795x334mm 33.9-inch                   | 1         | 1.02%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch              | 1         | 1.02%   |
| Goldstar W2261 GSM56CF 1920x1080 477x268mm 21.5-inch                    | 1         | 1.02%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 1         | 1.02%   |
| Goldstar E2411 GSM583A 1920x1080 477x268mm 21.5-inch                    | 1         | 1.02%   |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                       | 1         | 1.02%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 40        | 44.94%  |
| 1366x768 (WXGA)    | 12        | 13.48%  |
| 2560x1440 (QHD)    | 8         | 8.99%   |
| 3840x2160 (4K)     | 7         | 7.87%   |
| 2880x1800          | 4         | 4.49%   |
| 2560x1600          | 4         | 4.49%   |
| 1280x800 (WXGA)    | 4         | 4.49%   |
| 1920x1200 (WUXGA)  | 2         | 2.25%   |
| 3440x1440          | 1         | 1.12%   |
| 3200x1800 (QHD+)   | 1         | 1.12%   |
| 2240x1400          | 1         | 1.12%   |
| 1920x540           | 1         | 1.12%   |
| 1680x1050 (WSXGA+) | 1         | 1.12%   |
| 1600x900 (HD+)     | 1         | 1.12%   |
| 1440x900 (WXGA+)   | 1         | 1.12%   |
| 1280x1024 (SXGA)   | 1         | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 38        | 39.58%  |
| 14      | 9         | 9.38%   |
| 17      | 8         | 8.33%   |
| 13      | 8         | 8.33%   |
| 16      | 6         | 6.25%   |
| 27      | 4         | 4.17%   |
| 12      | 4         | 4.17%   |
| 40      | 2         | 2.08%   |
| 31      | 2         | 2.08%   |
| 24      | 2         | 2.08%   |
| 22      | 2         | 2.08%   |
| 21      | 2         | 2.08%   |
| 84      | 1         | 1.04%   |
| 60      | 1         | 1.04%   |
| 43      | 1         | 1.04%   |
| 33      | 1         | 1.04%   |
| 23      | 1         | 1.04%   |
| 20      | 1         | 1.04%   |
| 19      | 1         | 1.04%   |
| 18      | 1         | 1.04%   |
| Unknown | 1         | 1.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 55.79%  |
| 351-400     | 10        | 10.53%  |
| 201-300     | 10        | 10.53%  |
| 501-600     | 7         | 7.37%   |
| 401-500     | 6         | 6.32%   |
| 801-900     | 2         | 2.11%   |
| 601-700     | 2         | 2.11%   |
| 701-800     | 1         | 1.05%   |
| 1501-2000   | 1         | 1.05%   |
| 1001-1500   | 1         | 1.05%   |
| 901-1000    | 1         | 1.05%   |
| Unknown     | 1         | 1.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 63        | 75%     |
| 16/10 | 17        | 20.24%  |
| 5/4   | 1         | 1.19%   |
| 32/9  | 1         | 1.19%   |
| 3/2   | 1         | 1.19%   |
| 21/9  | 1         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 39.58%  |
| 81-90          | 16        | 16.67%  |
| 121-130        | 8         | 8.33%   |
| 111-120        | 6         | 6.25%   |
| 61-70          | 4         | 4.17%   |
| 301-350        | 4         | 4.17%   |
| 201-250        | 4         | 4.17%   |
| 151-200        | 4         | 4.17%   |
| 351-500        | 3         | 3.13%   |
| 501-1000       | 3         | 3.13%   |
| More than 1000 | 2         | 2.08%   |
| 71-80          | 1         | 1.04%   |
| 251-300        | 1         | 1.04%   |
| 141-150        | 1         | 1.04%   |
| Unknown        | 1         | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 43.01%  |
| 101-120       | 20        | 21.51%  |
| 161-240       | 13        | 13.98%  |
| 51-100        | 11        | 11.83%  |
| More than 240 | 7         | 7.53%   |
| 1-50          | 1         | 1.08%   |
| Unknown       | 1         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 54        | 70.13%  |
| 2     | 20        | 25.97%  |
| 3     | 2         | 2.6%    |
| 0     | 1         | 1.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 59        | 44.36%  |
| Realtek Semiconductor             | 44        | 33.08%  |
| Qualcomm Atheros                  | 7         | 5.26%   |
| Broadcom                          | 5         | 3.76%   |
| Ralink Technology                 | 4         | 3.01%   |
| Broadcom Limited                  | 4         | 3.01%   |
| Huawei Technologies               | 3         | 2.26%   |
| DisplayLink                       | 2         | 1.5%    |
| TP-Link                           | 1         | 0.75%   |
| MediaTek                          | 1         | 0.75%   |
| Ericsson Business Mobile Networks | 1         | 0.75%   |
| Dell                              | 1         | 0.75%   |
| ASIX Electronics                  | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 20.53%  |
| Intel Wi-Fi 6 AX200                                               | 20        | 13.25%  |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 9         | 5.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 4.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.65%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3         | 1.99%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.99%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.32%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.32%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 2         | 1.32%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                  | 2         | 1.32%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 1.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.66%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.66%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.66%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.66%   |
| Intel Wireless-AC 9260                                            | 1         | 0.66%   |
| Intel Wireless 8260                                               | 1         | 0.66%   |
| Intel Wireless 7260                                               | 1         | 0.66%   |
| Intel Wireless 3165                                               | 1         | 0.66%   |
| Intel Wireless 3160                                               | 1         | 0.66%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.66%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1         | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.66%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 56        | 70.89%  |
| Realtek Semiconductor | 5         | 6.33%   |
| Broadcom              | 5         | 6.33%   |
| Ralink Technology     | 4         | 5.06%   |
| Qualcomm Atheros      | 4         | 5.06%   |
| Broadcom Limited      | 3         | 3.8%    |
| TP-Link               | 1         | 1.27%   |
| MediaTek              | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 20        | 25.32%  |
| Intel Alder Lake-P PCH CNVi WiFi                               | 9         | 11.39%  |
| Intel Wireless 8265 / 8275                                     | 4         | 5.06%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 3.8%    |
| Intel Wi-Fi 6 AX201                                            | 3         | 3.8%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 3.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 3.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 2.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 2.53%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 2         | 2.53%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 2.53%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.27%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.27%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.27%   |
| Intel Wireless-AC 9260                                         | 1         | 1.27%   |
| Intel Wireless 8260                                            | 1         | 1.27%   |
| Intel Wireless 7260                                            | 1         | 1.27%   |
| Intel Wireless 3165                                            | 1         | 1.27%   |
| Intel Wireless 3160                                            | 1         | 1.27%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.27%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 1         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.27%   |
| Intel CNVi: Wi-Fi                                              | 1         | 1.27%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.27%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.27%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 44        | 66.67%  |
| Intel                 | 12        | 18.18%  |
| Qualcomm Atheros      | 3         | 4.55%   |
| Broadcom              | 3         | 4.55%   |
| DisplayLink           | 2         | 3.03%   |
| Broadcom Limited      | 1         | 1.52%   |
| ASIX Electronics      | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 46.27%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 10.45%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 5.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 4.48%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.49%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.49%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.49%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.49%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.49%   |
| DisplayLink USB-C Triple-4K Dock                                  | 1         | 1.49%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.49%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 1.49%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 52.78%  |
| Ethernet | 63        | 43.75%  |
| Modem    | 5         | 3.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 69.14%  |
| Ethernet | 25        | 30.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 56        | 72.73%  |
| 1     | 18        | 23.38%  |
| 3     | 2         | 2.6%    |
| 0     | 1         | 1.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| Yes  | 41        | 53.25%  |
| No   | 36        | 46.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 74.65%  |
| Realtek Semiconductor           | 4         | 5.63%   |
| Apple                           | 4         | 5.63%   |
| Foxconn / Hon Hai               | 3         | 4.23%   |
| Broadcom                        | 2         | 2.82%   |
| Qualcomm Atheros Communications | 1         | 1.41%   |
| IMC Networks                    | 1         | 1.41%   |
| Dell                            | 1         | 1.41%   |
| Cambridge Silicon Radio         | 1         | 1.41%   |
| ASUSTek Computer                | 1         | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 20        | 28.17%  |
| Intel AX201 Bluetooth                               | 12        | 16.9%   |
| Intel Bluetooth wireless interface                  | 9         | 12.68%  |
| Intel Bluetooth Device                              | 8         | 11.27%  |
| Realtek Bluetooth Radio                             | 2         | 2.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.82%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.82%   |
| Apple Bluetooth Host Controller                     | 2         | 2.82%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.41%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.41%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.41%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.41%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.41%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.41%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.41%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.41%   |
| ASUS ASUS USB-BT500                                 | 1         | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 56        | 52.83%  |
| Nvidia                                 | 24        | 22.64%  |
| AMD                                    | 20        | 18.87%  |
| Sony Ericsson Mobile Communications AB | 1         | 0.94%   |
| Razer USA                              | 1         | 0.94%   |
| Logitech                               | 1         | 0.94%   |
| Lenovo                                 | 1         | 0.94%   |
| Kingston Technology                    | 1         | 0.94%   |
| GN Netcom                              | 1         | 0.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 13.93%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 13        | 10.66%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 5.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 4.92%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 3.28%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 3.28%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.28%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 2.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.46%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.46%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.46%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.64%   |
| Nvidia Audio device                                                        | 2         | 1.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.64%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.64%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.64%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 2         | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.64%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 0.82%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 1         | 0.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.82%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1         | 0.82%   |
| Lenovo USB Headset                                                         | 1         | 0.82%   |
| Kingston Technology HyperX QuadCast S                                      | 1         | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.82%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 0.82%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 0.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.82%   |
| Intel Alder Lake-N HD Graphics SGPC                                        | 1         | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 0.82%   |
| GN Netcom Jabra Link 380                                                   | 1         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 44.44%  |
| SK hynix            | 7         | 25.93%  |
| Micron Technology   | 3         | 11.11%  |
| Unknown             | 2         | 7.41%   |
| Team                | 1         | 3.7%    |
| Elpida              | 1         | 3.7%    |
| ASint Technology    | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s    | 3         | 10.71%  |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s    | 2         | 7.14%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 7.14%   |
| Unknown                                                   | 2         | 7.14%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s     | 1         | 3.57%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 3.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 3.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 3.57%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s    | 1         | 3.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 3.57%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 3.57%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 3.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 1         | 3.57%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s       | 1         | 3.57%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s    | 1         | 3.57%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s | 1         | 3.57%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s     | 1         | 3.57%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s  | 1         | 3.57%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s        | 1         | 3.57%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s      | 1         | 3.57%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 1         | 3.57%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s     | 1         | 3.57%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s        | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 58.33%  |
| DDR3   | 5         | 20.83%  |
| LPDDR5 | 3         | 12.5%   |
| DDR5   | 2         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 21        | 87.5%   |
| Row Of Chips | 3         | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 9         | 33.33%  |
| 32768 | 6         | 22.22%  |
| 16384 | 5         | 18.52%  |
| 2048  | 4         | 14.81%  |
| 4096  | 2         | 7.41%   |
| 3072  | 1         | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 10        | 40%     |
| 1600  | 4         | 16%     |
| 6400  | 3         | 12%     |
| 8400  | 2         | 8%      |
| 2667  | 2         | 8%      |
| 5600  | 1         | 4%      |
| 4800  | 1         | 4%      |
| 2400  | 1         | 4%      |
| 1067  | 1         | 4%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 31        | 46.97%  |
| Bison Electronics             | 7         | 10.61%  |
| Microdia                      | 4         | 6.06%   |
| IMC Networks                  | 3         | 4.55%   |
| Apple                         | 3         | 4.55%   |
| Acer                          | 3         | 4.55%   |
| Suyin                         | 2         | 3.03%   |
| Sunplus Innovation Technology | 2         | 3.03%   |
| Lite-On Technology            | 2         | 3.03%   |
| Unknown                       | 1         | 1.52%   |
| Ricoh                         | 1         | 1.52%   |
| Realtek Semiconductor         | 1         | 1.52%   |
| Luxvisions Innotech Limited   | 1         | 1.52%   |
| Logitech                      | 1         | 1.52%   |
| Importek                      | 1         | 1.52%   |
| HYGD-220831-A                 | 1         | 1.52%   |
| Generalplus Technology        | 1         | 1.52%   |
| Alpha Imaging Technology      | 1         | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony FHD Webcam                                   | 7         | 10.61%  |
| Chicony Integrated IR Camera                         | 6         | 9.09%   |
| Chicony USB2.0 Camera                                | 5         | 7.58%   |
| IMC Networks Integrated Camera                       | 3         | 4.55%   |
| Chicony HD Webcam                                    | 3         | 4.55%   |
| Bison HD Webcam                                      | 3         | 4.55%   |
| Apple FaceTime HD Camera                             | 3         | 4.55%   |
| Acer BisonCam,NB Pro                                 | 3         | 4.55%   |
| Microdia Integrated_Webcam_FHD                       | 2         | 3.03%   |
| Chicony Integrated Camera                            | 2         | 3.03%   |
| Bison Lenovo EasyCamera                              | 2         | 3.03%   |
| Unknown HD camera                                    | 1         | 1.52%   |
| Suyin RGBIR Camera                                   | 1         | 1.52%   |
| Suyin HP TrueVision HD                               | 1         | 1.52%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.52%   |
| Sunplus Asus Webcam                                  | 1         | 1.52%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 1.52%   |
| Realtek Integrated Webcam                            | 1         | 1.52%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 1.52%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.52%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.52%   |
| Logitech Brio 500                                    | 1         | 1.52%   |
| Lite-On Integrated Camera                            | 1         | 1.52%   |
| Lite-On HP Webcam                                    | 1         | 1.52%   |
| Importek HP Webcam                                   | 1         | 1.52%   |
| HYGD-220831-A Hy-Usb2.0-1*MIC                        | 1         | 1.52%   |
| Generalplus WEB CAM                                  | 1         | 1.52%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 1.52%   |
| Chicony USB 2.0 Camera                               | 1         | 1.52%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.52%   |
| Chicony HP Truevision HD                             | 1         | 1.52%   |
| Chicony HP HD Camera                                 | 1         | 1.52%   |
| Chicony FJ Camera                                    | 1         | 1.52%   |
| Chicony ACER FHD User Facing                         | 1         | 1.52%   |
| Chicony 1.3M Webcam                                  | 1         | 1.52%   |
| Bison SunplusIT Integrated Camera                    | 1         | 1.52%   |
| Bison Lenovo Integrated Webcam                       | 1         | 1.52%   |
| Alpha Imaging Integrated_Webcam_8M                   | 1         | 1.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 8         | 53.33%  |
| Validity Sensors      | 6         | 40%     |
| LighTuning Technology | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 13.33%  |
| Unknown                                                                    | 2         | 13.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 6.67%   |
| Validity Sensors VFS491                                                    | 1         | 6.67%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 6.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 6.67%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 6.67%   |
| Synaptics WBDI                                                             | 1         | 6.67%   |
| Synaptics UWP WBDI                                                         | 1         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 6.67%   |
| LighTuning Fingerprint Reader                                              | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 66.67%  |
| Alcor Micro | 2         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 41        | 53.25%  |
| 1     | 34        | 44.16%  |
| 3     | 1         | 1.3%    |
| 2     | 1         | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 37.5%   |
| Multimedia controller | 11        | 27.5%   |
| Chipcard              | 6         | 15%     |
| Graphics card         | 5         | 12.5%   |
| Net/wireless          | 2         | 5%      |
| Modem                 | 1         | 2.5%    |

