TUXEDO OS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for TUXEDO OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/TUXEDO_OS/Desktop/README.md) and [notebooks](/Dist/TUXEDO_OS/Notebook/README.md).

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

Total: 100

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Precision 7750              | Notebook    | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| TUXEDO        | N7x0WU                      | Notebook    | [1c2cb06178](https://linux-hardware.org/?probe=1c2cb06178) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [01846991de](https://linux-hardware.org/?probe=01846991de) | Aug 04, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [64e640ff2b](https://linux-hardware.org/?probe=64e640ff2b) | Aug 04, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [07d668ee3d](https://linux-hardware.org/?probe=07d668ee3d) | Aug 03, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [c6078d0836](https://linux-hardware.org/?probe=c6078d0836) | Aug 02, 2023 |
| Lenovo        | ThinkPad E580 20KS003SUS    | Notebook    | [9b8485b740](https://linux-hardware.org/?probe=9b8485b740) | Aug 01, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fde0e0e94f](https://linux-hardware.org/?probe=fde0e0e94f) | Jul 29, 2023 |
| HP            | Notebook                    | Notebook    | [beef8e7fce](https://linux-hardware.org/?probe=beef8e7fce) | Jul 25, 2023 |
| HP            | Notebook                    | Notebook    | [4746f66332](https://linux-hardware.org/?probe=4746f66332) | Jul 23, 2023 |
| Lenovo        | ThinkPad 20JB002BUS         | Tablet      | [ac659620e6](https://linux-hardware.org/?probe=ac659620e6) | Jul 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [bcd1c01ad6](https://linux-hardware.org/?probe=bcd1c01ad6) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [390008fe3c](https://linux-hardware.org/?probe=390008fe3c) | Jul 15, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [fd0926d15b](https://linux-hardware.org/?probe=fd0926d15b) | Jul 14, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [26fda3b894](https://linux-hardware.org/?probe=26fda3b894) | Jul 14, 2023 |
| Dell          | Latitude E6530              | Notebook    | [25cbd87821](https://linux-hardware.org/?probe=25cbd87821) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [29a9ad60a6](https://linux-hardware.org/?probe=29a9ad60a6) | Jul 13, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [2015dd83cb](https://linux-hardware.org/?probe=2015dd83cb) | Jul 12, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| TUXEDO        | Book XUX7 Gen13             | Notebook    | [e480e61359](https://linux-hardware.org/?probe=e480e61359) | Jul 06, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [3d599df965](https://linux-hardware.org/?probe=3d599df965) | Jul 02, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b15b3b6025](https://linux-hardware.org/?probe=b15b3b6025) | Jun 30, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [ed4a581e3e](https://linux-hardware.org/?probe=ed4a581e3e) | Jun 28, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [c2a5aeb291](https://linux-hardware.org/?probe=c2a5aeb291) | Jun 28, 2023 |
| TUXEDO        | P64_HJ,HK1                  | Notebook    | [4c542d50e7](https://linux-hardware.org/?probe=4c542d50e7) | Jun 27, 2023 |
| BESSTAR Te... | X400                        | Notebook    | [8e98b345cf](https://linux-hardware.org/?probe=8e98b345cf) | Jun 26, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [c8f3981a52](https://linux-hardware.org/?probe=c8f3981a52) | Jun 23, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [6fb60cf84a](https://linux-hardware.org/?probe=6fb60cf84a) | Jun 18, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [818c9bc358](https://linux-hardware.org/?probe=818c9bc358) | Jun 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [c47936b50c](https://linux-hardware.org/?probe=c47936b50c) | Jun 09, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c16266c1c9](https://linux-hardware.org/?probe=c16266c1c9) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f75fb35204](https://linux-hardware.org/?probe=f75fb35204) | May 28, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7332acbb0e](https://linux-hardware.org/?probe=7332acbb0e) | May 15, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| Lenovo        | IdeaPad N581 7505           | Notebook    | [5d340c1aa2](https://linux-hardware.org/?probe=5d340c1aa2) | May 04, 2023 |
| HP            | Pavilion dv6                | Notebook    | [be01072653](https://linux-hardware.org/?probe=be01072653) | May 03, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [756500f10b](https://linux-hardware.org/?probe=756500f10b) | May 03, 2023 |
| HP            | Pavilion dv6                | Notebook    | [87f0c054fa](https://linux-hardware.org/?probe=87f0c054fa) | May 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Dell          | Inspiron 16 5630            | Notebook    | [7bfe5bb892](https://linux-hardware.org/?probe=7bfe5bb892) | Apr 27, 2023 |
| Dell          | Latitude 7530               | Notebook    | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [04a458482b](https://linux-hardware.org/?probe=04a458482b) | Apr 19, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3b77631ed6](https://linux-hardware.org/?probe=3b77631ed6) | Apr 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [22c0e4cdec](https://linux-hardware.org/?probe=22c0e4cdec) | Apr 02, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aabb4d79b8](https://linux-hardware.org/?probe=aabb4d79b8) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490 20N3SBU219    | Notebook    | [b8e8125150](https://linux-hardware.org/?probe=b8e8125150) | Mar 27, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [885b757cdc](https://linux-hardware.org/?probe=885b757cdc) | Mar 24, 2023 |
| HP            | 2B3E                        | All in one  | [c6dd260a92](https://linux-hardware.org/?probe=c6dd260a92) | Mar 22, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [5e01f2c134](https://linux-hardware.org/?probe=5e01f2c134) | Mar 22, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [8aaef31933](https://linux-hardware.org/?probe=8aaef31933) | Mar 19, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [0db668b5ec](https://linux-hardware.org/?probe=0db668b5ec) | Mar 18, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [094b530ce7](https://linux-hardware.org/?probe=094b530ce7) | Mar 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [3fcbfecb5a](https://linux-hardware.org/?probe=3fcbfecb5a) | Mar 14, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| Dell          | Precision 7720              | Notebook    | [dbe0d4c5c4](https://linux-hardware.org/?probe=dbe0d4c5c4) | Mar 12, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [40a0328a5f](https://linux-hardware.org/?probe=40a0328a5f) | Mar 11, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [769cd87ebd](https://linux-hardware.org/?probe=769cd87ebd) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [e1846f2a68](https://linux-hardware.org/?probe=e1846f2a68) | Mar 07, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [886aa04456](https://linux-hardware.org/?probe=886aa04456) | Mar 07, 2023 |
| Fujitsu       | LIFEBOOK U7412              | Notebook    | [980dd72471](https://linux-hardware.org/?probe=980dd72471) | Mar 06, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [9088ef4d11](https://linux-hardware.org/?probe=9088ef4d11) | Mar 06, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [7a21cf8349](https://linux-hardware.org/?probe=7a21cf8349) | Mar 05, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [20d14c7576](https://linux-hardware.org/?probe=20d14c7576) | Mar 04, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [01f7386d8c](https://linux-hardware.org/?probe=01f7386d8c) | Mar 02, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [1e1da6a575](https://linux-hardware.org/?probe=1e1da6a575) | Feb 24, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [497a8d66e5](https://linux-hardware.org/?probe=497a8d66e5) | Feb 22, 2023 |
| Dell          | Precision 7720              | Notebook    | [2f7837d5b6](https://linux-hardware.org/?probe=2f7837d5b6) | Feb 21, 2023 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [4f507f4e5a](https://linux-hardware.org/?probe=4f507f4e5a) | Feb 20, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [ed14b057dd](https://linux-hardware.org/?probe=ed14b057dd) | Feb 09, 2023 |
| HP            | 2B34                        | Desktop     | [3376fc38b3](https://linux-hardware.org/?probe=3376fc38b3) | Feb 05, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [e163d98802](https://linux-hardware.org/?probe=e163d98802) | Jan 28, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [fa53a29f7e](https://linux-hardware.org/?probe=fa53a29f7e) | Jan 01, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [aeb826326b](https://linux-hardware.org/?probe=aeb826326b) | Dec 20, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [731b31c845](https://linux-hardware.org/?probe=731b31c845) | Dec 02, 2022 |
| TUXEDO        | N13xWU                      | Notebook    | [55935f091d](https://linux-hardware.org/?probe=55935f091d) | Dec 01, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [fd06ca029c](https://linux-hardware.org/?probe=fd06ca029c) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [5043f6c54e](https://linux-hardware.org/?probe=5043f6c54e) | Nov 20, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [5d82e9f6ac](https://linux-hardware.org/?probe=5d82e9f6ac) | Nov 19, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [9d20af2c30](https://linux-hardware.org/?probe=9d20af2c30) | Nov 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | Notebook    | [d58eb8b2f0](https://linux-hardware.org/?probe=d58eb8b2f0) | Oct 30, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | Notebook    | [032bc01698](https://linux-hardware.org/?probe=032bc01698) | Oct 30, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [99555fc4eb](https://linux-hardware.org/?probe=99555fc4eb) | Oct 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| ASUSTek       | BU201LAV                    | Notebook    | [9d1fe7cb6f](https://linux-hardware.org/?probe=9d1fe7cb6f) | Oct 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | Notebook    | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| TUXEDO OS 22.04 | 79        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 79        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 6.1.0-1009-tuxedo   | 16        | 19.05%  |
| 6.2.0-10007-tuxedo  | 11        | 13.1%   |
| 6.2.0-10005-tuxedo  | 11        | 13.1%   |
| 6.2.0-10011-tuxedo  | 9         | 10.71%  |
| 5.15.0-10058-tuxedo | 7         | 8.33%   |
| 6.2.0-10018-tuxedo  | 6         | 7.14%   |
| 6.2.0-10010-tuxedo  | 6         | 7.14%   |
| 5.15.0-10048-tuxedo | 4         | 4.76%   |
| 5.15.0-10053-tuxedo | 3         | 3.57%   |
| 5.15.0-10052-tuxedo | 3         | 3.57%   |
| 5.15.0-10057-tuxedo | 2         | 2.38%   |
| 5.15.0-10056-tuxedo | 2         | 2.38%   |
| 5.15.0-10050-tuxedo | 2         | 2.38%   |
| 6.2.0-10014-tuxedo  | 1         | 1.19%   |
| 6.0.0-1010-oem      | 1         | 1.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 44        | 52.38%  |
| 5.15.0  | 23        | 27.38%  |
| 6.1.0   | 16        | 19.05%  |
| 6.0.0   | 1         | 1.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 44        | 52.38%  |
| 5.15    | 23        | 27.38%  |
| 6.1     | 16        | 19.05%  |
| 6.0     | 1         | 1.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 79        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| KDE5 | 79        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 77        | 96.25%  |
| Wayland | 3         | 3.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 66        | 81.48%  |
| SDDM    | 15        | 18.52%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| de_DE | 37        | 46.84%  |
| en_US | 17        | 21.52%  |
| en_GB | 6         | 7.59%   |
| pl_PL | 3         | 3.8%    |
| en_ZA | 3         | 3.8%    |
| fr_FR | 2         | 2.53%   |
| en_AG | 2         | 2.53%   |
| pt_PT | 1         | 1.27%   |
| pt_BR | 1         | 1.27%   |
| hu_HU | 1         | 1.27%   |
| es_ES | 1         | 1.27%   |
| en_DK | 1         | 1.27%   |
| en_CA | 1         | 1.27%   |
| en_AU | 1         | 1.27%   |
| de_CH | 1         | 1.27%   |
| de_AT | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 67        | 83.75%  |
| EFI  | 13        | 16.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 68        | 86.08%  |
| Btrfs   | 6         | 7.59%   |
| Tmpfs   | 2         | 2.53%   |
| Overlay | 2         | 2.53%   |
| Xfs     | 1         | 1.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 66        | 81.48%  |
| GPT     | 14        | 17.28%  |
| MBR     | 1         | 1.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 93.75%  |
| Yes       | 5         | 6.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 92.5%   |
| Yes       | 6         | 7.5%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| TUXEDO              | 26        | 32.91%  |
| Lenovo              | 11        | 13.92%  |
| Hewlett-Packard     | 9         | 11.39%  |
| ASUSTek Computer    | 9         | 11.39%  |
| Dell                | 8         | 10.13%  |
| MSI                 | 3         | 3.8%    |
| Apple               | 3         | 3.8%    |
| ASRock              | 2         | 2.53%   |
| Acer                | 2         | 2.53%   |
| Notebook            | 1         | 1.27%   |
| Gigabyte Technology | 1         | 1.27%   |
| Fujitsu             | 1         | 1.27%   |
| Fanless Mini PC     | 1         | 1.27%   |
| BESSTAR Tech        | 1         | 1.27%   |
| Unknown             | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| TUXEDO InfinityBook S 15/17 Gen7     | 4         | 5.06%   |
| Unknown                              | 3         | 3.8%    |
| TUXEDO Stellaris/Polaris AMD Gen4    | 2         | 2.53%   |
| TUXEDO Pulse 15 Gen2                 | 2         | 2.53%   |
| TUXEDO Pulse 15 Gen1                 | 2         | 2.53%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)   | 2         | 2.53%   |
| TUXEDO InfinityBook Pro 14 Gen6      | 2         | 2.53%   |
| Apple MacBookPro8,1                  | 2         | 2.53%   |
| TUXEDO XMG FUSION 15 (XFU15L19)      | 1         | 1.27%   |
| TUXEDO Stellaris AMD Gen3 (CZN)      | 1         | 1.27%   |
| TUXEDO Polaris AMD Gen3 (CZN)        | 1         | 1.27%   |
| TUXEDO Polaris 15 AMD Gen1           | 1         | 1.27%   |
| TUXEDO P64_HJ,HK1                    | 1         | 1.27%   |
| TUXEDO N7x0WU                        | 1         | 1.27%   |
| TUXEDO N13xWU                        | 1         | 1.27%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)   | 1         | 1.27%   |
| TUXEDO Book XUX7 Gen13               | 1         | 1.27%   |
| TUXEDO Aura 15 Gen2                  | 1         | 1.27%   |
| Notebook W65_W67RB                   | 1         | 1.27%   |
| MSI MS-7D25                          | 1         | 1.27%   |
| MSI MS-7D17                          | 1         | 1.27%   |
| MSI GE75 Raider 10SF                 | 1         | 1.27%   |
| Lenovo Yoga S740-15IRH 81NX          | 1         | 1.27%   |
| Lenovo ThinkPad X200 Tablet 7450WN9  | 1         | 1.27%   |
| Lenovo ThinkPad T490 20N3SBU219      | 1         | 1.27%   |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700  | 1         | 1.27%   |
| Lenovo ThinkPad E580 20KS003SUS      | 1         | 1.27%   |
| Lenovo ThinkPad 20JB002BUS           | 1         | 1.27%   |
| Lenovo ThinkCentre M700 10GSS05X48   | 1         | 1.27%   |
| Lenovo Legion 5 15ACH6H 82JU         | 1         | 1.27%   |
| Lenovo IdeaPad N581 7505             | 1         | 1.27%   |
| Lenovo G580 20150                    | 1         | 1.27%   |
| Lenovo G50-80 80E5                   | 1         | 1.27%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1         | 1.27%   |
| HP Pavilion dv6                      | 1         | 1.27%   |
| HP OMEN Laptop 15-en0xxx             | 1         | 1.27%   |
| HP Notebook                          | 1         | 1.27%   |
| HP Laptop 15-dw3xxx                  | 1         | 1.27%   |
| HP ENVY x360 Convertible 13-ar0xxx   | 1         | 1.27%   |
| HP EliteBook 820 G2                  | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| TUXEDO InfinityBook   | 9         | 11.39%  |
| Lenovo ThinkPad       | 5         | 6.33%   |
| TUXEDO Pulse          | 4         | 5.06%   |
| TUXEDO Stellaris      | 3         | 3.8%    |
| Unknown               | 3         | 3.8%    |
| TUXEDO Polaris        | 2         | 2.53%   |
| HP Pavilion           | 2         | 2.53%   |
| HP EliteBook          | 2         | 2.53%   |
| Dell Precision        | 2         | 2.53%   |
| Dell Latitude         | 2         | 2.53%   |
| ASUS ROG              | 2         | 2.53%   |
| ASUS PRIME            | 2         | 2.53%   |
| Apple MacBookPro8     | 2         | 2.53%   |
| TUXEDO XMG            | 1         | 1.27%   |
| TUXEDO P64            | 1         | 1.27%   |
| TUXEDO N7x0WU         | 1         | 1.27%   |
| TUXEDO N13xWU         | 1         | 1.27%   |
| TUXEDO Book           | 1         | 1.27%   |
| TUXEDO Aura           | 1         | 1.27%   |
| Notebook W65          | 1         | 1.27%   |
| MSI MS-7D25           | 1         | 1.27%   |
| MSI MS-7D17           | 1         | 1.27%   |
| MSI GE75              | 1         | 1.27%   |
| Lenovo Yoga           | 1         | 1.27%   |
| Lenovo ThinkCentre    | 1         | 1.27%   |
| Lenovo Legion         | 1         | 1.27%   |
| Lenovo IdeaPad        | 1         | 1.27%   |
| Lenovo G580           | 1         | 1.27%   |
| Lenovo G50-80         | 1         | 1.27%   |
| HP OMEN               | 1         | 1.27%   |
| HP Notebook           | 1         | 1.27%   |
| HP Laptop             | 1         | 1.27%   |
| HP ENVY               | 1         | 1.27%   |
| HP 280                | 1         | 1.27%   |
| Gigabyte H81M-HD3     | 1         | 1.27%   |
| Fujitsu LIFEBOOK      | 1         | 1.27%   |
| Fanless Mini PC PCG35 | 1         | 1.27%   |
| Dell Vostro           | 1         | 1.27%   |
| Dell Venue            | 1         | 1.27%   |
| Dell OptiPlex         | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 18        | 22.78%  |
| 2020 | 11        | 13.92%  |
| 2021 | 10        | 12.66%  |
| 2015 | 8         | 10.13%  |
| 2019 | 6         | 7.59%   |
| 2012 | 5         | 6.33%   |
| 2017 | 4         | 5.06%   |
| 2011 | 4         | 5.06%   |
| 2023 | 2         | 2.53%   |
| 2018 | 2         | 2.53%   |
| 2016 | 2         | 2.53%   |
| 2014 | 2         | 2.53%   |
| 2013 | 2         | 2.53%   |
| 2010 | 1         | 1.27%   |
| 2009 | 1         | 1.27%   |
| 2008 | 1         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 62        | 78.48%  |
| Desktop     | 14        | 17.72%  |
| Tablet      | 1         | 1.27%   |
| Convertible | 1         | 1.27%   |
| Mini pc     | 1         | 1.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 79        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 17        | 21.52%  |
| 32.01-64.0  | 15        | 18.99%  |
| 8.01-16.0   | 15        | 18.99%  |
| 4.01-8.0    | 14        | 17.72%  |
| 64.01-256.0 | 8         | 10.13%  |
| 3.01-4.0    | 7         | 8.86%   |
| 24.01-32.0  | 3         | 3.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 24        | 29.27%  |
| 2.01-3.0   | 20        | 24.39%  |
| 1.01-2.0   | 20        | 24.39%  |
| 3.01-4.0   | 13        | 15.85%  |
| 8.01-16.0  | 3         | 3.66%   |
| 16.01-24.0 | 2         | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 47.5%   |
| 2      | 33        | 41.25%  |
| 4      | 4         | 5%      |
| 3      | 3         | 3.75%   |
| 5      | 2         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 63        | 79.75%  |
| Yes       | 16        | 20.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 84.81%  |
| No        | 12        | 15.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 91.14%  |
| No        | 7         | 8.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 83.54%  |
| No        | 13        | 16.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 39        | 49.37%  |
| USA          | 9         | 11.39%  |
| UK           | 5         | 6.33%   |
| Switzerland  | 3         | 3.8%    |
| South Africa | 3         | 3.8%    |
| Poland       | 3         | 3.8%    |
| Portugal     | 2         | 2.53%   |
| France       | 2         | 2.53%   |
| Austria      | 2         | 2.53%   |
| Turkey       | 1         | 1.27%   |
| Spain        | 1         | 1.27%   |
| Romania      | 1         | 1.27%   |
| Netherlands  | 1         | 1.27%   |
| Egypt        | 1         | 1.27%   |
| Denmark      | 1         | 1.27%   |
| Czechia      | 1         | 1.27%   |
| Canada       | 1         | 1.27%   |
| Bulgaria     | 1         | 1.27%   |
| Brazil       | 1         | 1.27%   |
| Australia    | 1         | 1.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Zurich             | 2         | 2.53%   |
| Vienna             | 2         | 2.53%   |
| Schweinfurt        | 2         | 2.53%   |
| Munich             | 2         | 2.53%   |
| Leipzig            | 2         | 2.53%   |
| Johannesburg       | 2         | 2.53%   |
| Berlin             | 2         | 2.53%   |
| Zalău             | 1         | 1.27%   |
| Zabrze             | 1         | 1.27%   |
| Wembley            | 1         | 1.27%   |
| Watertown          | 1         | 1.27%   |
| Warsaw             | 1         | 1.27%   |
| Walsall            | 1         | 1.27%   |
| Stuttgart          | 1         | 1.27%   |
| Stockstadt am Main | 1         | 1.27%   |
| Solingen           | 1         | 1.27%   |
| Sistov             | 1         | 1.27%   |
| Seattle            | 1         | 1.27%   |
| Rio Maior          | 1         | 1.27%   |
| Reno               | 1         | 1.27%   |
| Rennes             | 1         | 1.27%   |
| Redcar             | 1         | 1.27%   |
| Pruem              | 1         | 1.27%   |
| Prague             | 1         | 1.27%   |
| Perrysburg         | 1         | 1.27%   |
| Peitz              | 1         | 1.27%   |
| Paris              | 1         | 1.27%   |
| Offenbach          | 1         | 1.27%   |
| Nuremberg          | 1         | 1.27%   |
| Neuwied            | 1         | 1.27%   |
| Nashville          | 1         | 1.27%   |
| Melton Mowbray     | 1         | 1.27%   |
| Mannheim           | 1         | 1.27%   |
| Lucerne            | 1         | 1.27%   |
| Lublin             | 1         | 1.27%   |
| Lippstadt          | 1         | 1.27%   |
| Langenhagen        | 1         | 1.27%   |
| Laage              | 1         | 1.27%   |
| Kiel               | 1         | 1.27%   |
| Jessen             | 1         | 1.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 41        | 56     | 34.17%  |
| Seagate                     | 13        | 15     | 10.83%  |
| Sandisk                     | 12        | 14     | 10%     |
| Kingston                    | 6         | 6      | 5%      |
| WDC                         | 5         | 6      | 4.17%   |
| Hitachi                     | 5         | 7      | 4.17%   |
| Unknown                     | 2         | 2      | 1.67%   |
| Toshiba                     | 2         | 2      | 1.67%   |
| SPCC                        | 2         | 2      | 1.67%   |
| SK hynix                    | 2         | 3      | 1.67%   |
| Phison Electronics          | 2         | 2      | 1.67%   |
| Micron Technology           | 2         | 2      | 1.67%   |
| GOODRAM                     | 2         | 2      | 1.67%   |
| USB3.0                      | 1         | 1      | 0.83%   |
| Transcend                   | 1         | 1      | 0.83%   |
| Silicon Motion              | 1         | 2      | 0.83%   |
| OWC                         | 1         | 1      | 0.83%   |
| Netac                       | 1         | 1      | 0.83%   |
| LITEONIT                    | 1         | 1      | 0.83%   |
| Lite-On Technology          | 1         | 1      | 0.83%   |
| Lenovo                      | 1         | 1      | 0.83%   |
| Kingston Technology Company | 1         | 1      | 0.83%   |
| Kingchuxing                 | 1         | 1      | 0.83%   |
| Intenso                     | 1         | 1      | 0.83%   |
| Intel                       | 1         | 1      | 0.83%   |
| HS-SSD-E100                 | 1         | 1      | 0.83%   |
| Hikvision                   | 1         | 2      | 0.83%   |
| HGST HTS                    | 1         | 1      | 0.83%   |
| HGST                        | 1         | 1      | 0.83%   |
| CT1000BX                    | 1         | 1      | 0.83%   |
| Crucial                     | 1         | 1      | 0.83%   |
| China                       | 1         | 1      | 0.83%   |
| ASMT                        | 1         | 1      | 0.83%   |
| Apple                       | 1         | 1      | 0.83%   |
| Apacer                      | 1         | 1      | 0.83%   |
| AMD                         | 1         | 1      | 0.83%   |
| Unknown                     | 1         | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 9         | 6.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 8         | 6.15%   |
| Samsung SSD 980 500GB                               | 6         | 4.62%   |
| Samsung SSD 980 1TB                                 | 6         | 4.62%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 5         | 3.85%   |
| Sandisk WD Black SN850 1TB                          | 2         | 1.54%   |
| Samsung SSD 980 PRO 500GB                           | 2         | 1.54%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 1.54%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2         | 1.54%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 1.54%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.54%   |
| Hitachi HTS727550A9E364 500GB                       | 2         | 1.54%   |
| WDC WD80EAZZ-00BKLB0 8TB                            | 1         | 0.77%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 1         | 0.77%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1         | 0.77%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.77%   |
| WDC WD10JPVX-11JC3T0 1TB                            | 1         | 0.77%   |
| WDC WD Elements SE SSD 1TB                          | 1         | 0.77%   |
| USB3.0 Super Speed 500GB                            | 1         | 0.77%   |
| Unknown MMC Card  64GB                              | 1         | 0.77%   |
| Unknown MMC Card  2GB                               | 1         | 0.77%   |
| Transcend TS512GSSD230S 512GB                       | 1         | 0.77%   |
| Toshiba XG4 NVMe SSD Controller 256GB               | 1         | 0.77%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.77%   |
| SPCC M.2 SSD 256GB                                  | 1         | 0.77%   |
| SPCC M.2 PCIe SSD 1TB                               | 1         | 0.77%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 1         | 0.77%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 0.77%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 512GB | 1         | 0.77%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 0.77%   |
| Seagate ST500LM034-2GH17A 500GB                     | 1         | 0.77%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 0.77%   |
| Seagate ST3500418AS 500GB                           | 1         | 0.77%   |
| Seagate ST3500413AS 500GB                           | 1         | 0.77%   |
| Seagate ST250LT003-9YG14C 250GB                     | 1         | 0.77%   |
| Seagate ST2000LM015-2E8174 2TB                      | 1         | 0.77%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 0.77%   |
| Seagate ST1000VT001-1RE172 1TB                      | 1         | 0.77%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 0.77%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 0.77%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 12        | 14     | 46.15%  |
| Hitachi  | 5         | 7      | 19.23%  |
| WDC      | 4         | 5      | 15.38%  |
| USB3.0   | 1         | 1      | 3.85%   |
| Toshiba  | 1         | 1      | 3.85%   |
| HGST HTS | 1         | 1      | 3.85%   |
| HGST     | 1         | 1      | 3.85%   |
| ASMT     | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 23.33%  |
| Kingston            | 4         | 4      | 13.33%  |
| SanDisk             | 3         | 3      | 10%     |
| GOODRAM             | 2         | 2      | 6.67%   |
| WDC                 | 1         | 1      | 3.33%   |
| Transcend           | 1         | 1      | 3.33%   |
| SPCC                | 1         | 1      | 3.33%   |
| SK hynix            | 1         | 2      | 3.33%   |
| OWC                 | 1         | 1      | 3.33%   |
| Netac               | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| LITEONIT            | 1         | 1      | 3.33%   |
| Intenso             | 1         | 1      | 3.33%   |
| CT1000BX            | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |
| China               | 1         | 1      | 3.33%   |
| Apple               | 1         | 1      | 3.33%   |
| Apacer              | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 52        | 77     | 48.6%   |
| SSD     | 26        | 32     | 24.3%   |
| HDD     | 24        | 31     | 22.43%  |
| MMC     | 3         | 3      | 2.8%    |
| Unknown | 2         | 2      | 1.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 52        | 77     | 52%     |
| SATA | 40        | 59     | 40%     |
| SAS  | 5         | 6      | 5%      |
| MMC  | 3         | 3      | 3%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 39     | 56.86%  |
| 0.51-1.0   | 18        | 20     | 35.29%  |
| 1.01-2.0   | 3         | 3      | 5.88%   |
| 4.01-10.0  | 1         | 1      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 22        | 27.85%  |
| 101-250        | 18        | 22.78%  |
| 251-500        | 16        | 20.25%  |
| 1001-2000      | 8         | 10.13%  |
| 2001-3000      | 4         | 5.06%   |
| 1-20           | 3         | 3.8%    |
| More than 3000 | 2         | 2.53%   |
| 21-50          | 2         | 2.53%   |
| 51-100         | 2         | 2.53%   |
| Unknown        | 2         | 2.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 24        | 29.63%  |
| 1-20      | 24        | 29.63%  |
| 101-250   | 14        | 17.28%  |
| 251-500   | 6         | 7.41%   |
| 51-100    | 6         | 7.41%   |
| 501-1000  | 3         | 3.7%    |
| 1001-2000 | 2         | 2.47%   |
| Unknown   | 2         | 2.47%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 67        | 121    | 80.72%  |
| Works    | 16        | 24     | 19.28%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 43        | 38.74%  |
| Samsung Electronics          | 36        | 32.43%  |
| AMD                          | 10        | 9.01%   |
| SanDisk                      | 9         | 8.11%   |
| Kingston Technology Company  | 3         | 2.7%    |
| Silicon Motion               | 2         | 1.8%    |
| Phison Electronics           | 2         | 1.8%    |
| Toshiba America Info Systems | 1         | 0.9%    |
| SK hynix                     | 1         | 0.9%    |
| Seagate Technology           | 1         | 0.9%    |
| Micron Technology            | 1         | 0.9%    |
| Lite-On Technology           | 1         | 0.9%    |
| Lenovo                       | 1         | 0.9%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 10.17%  |
| Samsung NVMe SSD Controller 980                                                | 12        | 10.17%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 8.47%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 7.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 5.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 4.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 3.39%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 3         | 2.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.54%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 1.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.69%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.69%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.85%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.85%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                      | 1         | 0.85%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 0.85%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.85%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.85%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.85%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 0.85%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.85%   |
| Lenovo LENSE30256GMSP34MEAT3TA                                                 | 1         | 0.85%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.85%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 0.85%   |
| Kingston Company NVMe Controller                                               | 1         | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 0.85%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.85%   |
| Intel SSD 660P Series                                                          | 1         | 0.85%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.85%   |
| Intel Comet Lake PCH-H RAID                                                    | 1         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 52        | 49.06%  |
| SATA | 47        | 44.34%  |
| RAID | 6         | 5.66%   |
| IDE  | 1         | 0.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 59        | 74.68%  |
| AMD    | 20        | 25.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H           | 3         | 3.8%    |
| Intel 12th Gen Core i7-1260P            | 3         | 3.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 2.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 2.53%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 2         | 2.53%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 2.53%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 2.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2         | 2.53%   |
| Intel 12th Gen Core i5-1240P            | 2         | 2.53%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 2         | 2.53%   |
| AMD Ryzen 7 6800H with Radeon Graphics  | 2         | 2.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 2.53%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 2.53%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 2         | 2.53%   |
| Intel Xeon W-10855M CPU @ 2.80GHz       | 1         | 1.27%   |
| Intel Pentium CPU G3420 @ 3.20GHz       | 1         | 1.27%   |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 1.27%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz        | 1         | 1.27%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.27%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.27%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.27%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.27%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.27%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 1.27%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.27%   |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 1.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.27%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 1         | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.27%   |
| Intel Core i5-7600T CPU @ 2.80GHz       | 1         | 1.27%   |
| Intel Core i5-5250U CPU @ 1.60GHz       | 1         | 1.27%   |
| Intel Core i5-4590S CPU @ 3.00GHz       | 1         | 1.27%   |
| Intel Core i5-4300Y CPU @ 1.60GHz       | 1         | 1.27%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.27%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 1         | 1.27%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1         | 1.27%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 1         | 1.27%   |
| Intel Core i5 CPU M 540 @ 2.53GHz       | 1         | 1.27%   |
| Intel Core i3-6300 CPU @ 3.80GHz        | 1         | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 19        | 24.05%  |
| Other            | 17        | 21.52%  |
| Intel Core i5    | 15        | 18.99%  |
| AMD Ryzen 7      | 10        | 12.66%  |
| AMD Ryzen 5      | 5         | 6.33%   |
| Intel Pentium    | 2         | 2.53%   |
| Intel Core i3    | 2         | 2.53%   |
| Intel Celeron    | 2         | 2.53%   |
| AMD Ryzen 9      | 2         | 2.53%   |
| Intel Xeon       | 1         | 1.27%   |
| Intel Core 2 Duo | 1         | 1.27%   |
| AMD Ryzen 5 PRO  | 1         | 1.27%   |
| AMD Ryzen 3      | 1         | 1.27%   |
| AMD A8           | 1         | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 25        | 31.65%  |
| 2      | 17        | 21.52%  |
| 8      | 13        | 16.46%  |
| 6      | 13        | 16.46%  |
| 12     | 6         | 7.59%   |
| 14     | 3         | 3.8%    |
| 16     | 1         | 1.27%   |
| 10     | 1         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 79        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 69        | 87.34%  |
| 1      | 10        | 12.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 79        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 87.65%  |
| 0xa0653    | 1         | 1.23%   |
| 0x906ea    | 1         | 1.23%   |
| 0x906e9    | 1         | 1.23%   |
| 0x906a4    | 1         | 1.23%   |
| 0x906a3    | 1         | 1.23%   |
| 0x806c1    | 1         | 1.23%   |
| 0x306d4    | 1         | 1.23%   |
| 0x0a50000d | 1         | 1.23%   |
| 0x0a50000c | 1         | 1.23%   |
| 0x08608103 | 1         | 1.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 17        | 21.52%  |
| KabyLake         | 12        | 15.19%  |
| IvyBridge        | 8         | 10.13%  |
| Zen 2            | 6         | 7.59%   |
| Zen 3            | 5         | 6.33%   |
| CometLake        | 5         | 6.33%   |
| SandyBridge      | 4         | 5.06%   |
| Haswell          | 4         | 5.06%   |
| TigerLake        | 3         | 3.8%    |
| Skylake          | 3         | 3.8%    |
| Broadwell        | 3         | 3.8%    |
| Alderlake Hybrid | 3         | 3.8%    |
| Zen+             | 2         | 2.53%   |
| Westmere         | 1         | 1.27%   |
| Puma             | 1         | 1.27%   |
| Penryn           | 1         | 1.27%   |
| Goldmont plus    | 1         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 54        | 52.43%  |
| Nvidia | 28        | 27.18%  |
| AMD    | 21        | 20.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P Integrated Graphics Controller                           | 8         | 7.77%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 5.83%   |
| AMD Renoir                                                                  | 5         | 4.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 4         | 3.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 4         | 3.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 3.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 3.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 3.88%   |
| Intel UHD Graphics 620                                                      | 3         | 2.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 2.91%   |
| Intel HD Graphics 630                                                       | 3         | 2.91%   |
| Intel HD Graphics 530                                                       | 3         | 2.91%   |
| AMD Rembrandt [Radeon 680M]                                                 | 3         | 2.91%   |
| AMD Lucienne                                                                | 3         | 2.91%   |
| Nvidia GF108M [GeForce GT 635M]                                             | 2         | 1.94%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                    | 2         | 1.94%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                               | 2         | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.94%   |
| Intel HD Graphics 5500                                                      | 2         | 1.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.97%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.97%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.97%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.97%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 1         | 0.97%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.97%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.97%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.97%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 1         | 0.97%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 1         | 0.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 0.97%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 1         | 0.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 0.97%   |
| Intel HD Graphics 615                                                       | 1         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 38        | 47.5%   |
| Intel + Nvidia | 13        | 16.25%  |
| 1 x AMD        | 11        | 13.75%  |
| AMD + Nvidia   | 8         | 10%     |
| 1 x Nvidia     | 7         | 8.75%   |
| Intel + AMD    | 3         | 3.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 54        | 68.35%  |
| Proprietary | 24        | 30.38%  |
| Unknown     | 1         | 1.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 68.75%  |
| 5.01-6.0   | 10        | 12.5%   |
| 7.01-8.0   | 5         | 6.25%   |
| 3.01-4.0   | 4         | 5%      |
| 1.01-2.0   | 3         | 3.75%   |
| 0.01-0.5   | 2         | 2.5%    |
| 8.01-16.0  | 1         | 1.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 21        | 22.83%  |
| AU Optronics        | 12        | 13.04%  |
| Samsung Electronics | 11        | 11.96%  |
| LG Display          | 5         | 5.43%   |
| Chimei Innolux      | 5         | 5.43%   |
| Acer                | 5         | 5.43%   |
| Dell                | 4         | 4.35%   |
| CSO                 | 4         | 4.35%   |
| Apple               | 3         | 3.26%   |
| Lenovo              | 2         | 2.17%   |
| Iiyama              | 2         | 2.17%   |
| Hewlett-Packard     | 2         | 2.17%   |
| Goldstar            | 2         | 2.17%   |
| BenQ                | 2         | 2.17%   |
| AOC                 | 2         | 2.17%   |
| Yamaha              | 1         | 1.09%   |
| ViewSonic           | 1         | 1.09%   |
| Sharp               | 1         | 1.09%   |
| SGT                 | 1         | 1.09%   |
| RTK                 | 1         | 1.09%   |
| Philips             | 1         | 1.09%   |
| PANDA               | 1         | 1.09%   |
| InfoVision          | 1         | 1.09%   |
| Eizo                | 1         | 1.09%   |
| ASUSTek Computer    | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 4         | 4.21%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 4.21%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 4         | 4.21%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 2         | 2.11%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 2.11%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 1.05%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 1.05%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 1.05%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 1.05%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 1.05%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch       | 1         | 1.05%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch   | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SDC424D 2160x1440 254x169mm 12.0-inch   | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch   | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1.05%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 1.05%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 1.05%   |
| RTK Wimaxit FHD RTK5A5B 1920x1080 344x195mm 15.6-inch                   | 1         | 1.05%   |
| Philips 170S4 PHL0818 1280x1024 338x270mm 17.0-inch                     | 1         | 1.05%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 1.05%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch            | 1         | 1.05%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 1.05%   |
| LG Display LCD Monitor LGD0545 3200x1800 293x165mm 13.2-inch            | 1         | 1.05%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 1.05%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 1.05%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                | 1         | 1.05%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                 | 1         | 1.05%   |
| InfoVision LCD Monitor IVO3414 1920x1080 294x165mm 13.3-inch            | 1         | 1.05%   |
| Iiyama PL3466WQ IVM7627 3440x1440 795x334mm 33.9-inch                   | 1         | 1.05%   |
| Iiyama PL2290 IVM562C 1920x1080 476x268mm 21.5-inch                     | 1         | 1.05%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch              | 1         | 1.05%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch            | 1         | 1.05%   |
| Goldstar W2261 GSM56CF 1920x1080 477x268mm 21.5-inch                    | 1         | 1.05%   |
| Goldstar E2041 GSM4EC9 1600x900 443x249mm 20.0-inch                     | 1         | 1.05%   |
| Eizo EV2736W ENC2383 2560x1440 597x336mm 27.0-inch                      | 1         | 1.05%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 40        | 45.45%  |
| 1366x768 (WXGA)    | 11        | 12.5%   |
| 2560x1440 (QHD)    | 10        | 11.36%  |
| 3840x2160 (4K)     | 5         | 5.68%   |
| 2880x1800          | 4         | 4.55%   |
| 1280x800 (WXGA)    | 3         | 3.41%   |
| 1920x1200 (WUXGA)  | 2         | 2.27%   |
| 1600x900 (HD+)     | 2         | 2.27%   |
| 1280x1024 (SXGA)   | 2         | 2.27%   |
| 3440x1440          | 1         | 1.14%   |
| 3200x1800 (QHD+)   | 1         | 1.14%   |
| 2560x1600          | 1         | 1.14%   |
| 2560x1080          | 1         | 1.14%   |
| 2240x1400          | 1         | 1.14%   |
| 2160x1440          | 1         | 1.14%   |
| 1920x540           | 1         | 1.14%   |
| 1680x1050 (WSXGA+) | 1         | 1.14%   |
| 1440x900 (WXGA+)   | 1         | 1.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 33        | 35.11%  |
| 17      | 8         | 8.51%   |
| 13      | 8         | 8.51%   |
| 27      | 7         | 7.45%   |
| 24      | 6         | 6.38%   |
| 14      | 5         | 5.32%   |
| 12      | 5         | 5.32%   |
| 16      | 3         | 3.19%   |
| 40      | 2         | 2.13%   |
| 31      | 2         | 2.13%   |
| 23      | 2         | 2.13%   |
| 22      | 2         | 2.13%   |
| 21      | 2         | 2.13%   |
| 20      | 2         | 2.13%   |
| 84      | 1         | 1.06%   |
| 43      | 1         | 1.06%   |
| 34      | 1         | 1.06%   |
| 33      | 1         | 1.06%   |
| 19      | 1         | 1.06%   |
| 18      | 1         | 1.06%   |
| Unknown | 1         | 1.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 45.65%  |
| 501-600     | 14        | 15.22%  |
| 201-300     | 11        | 11.96%  |
| 351-400     | 9         | 9.78%   |
| 401-500     | 7         | 7.61%   |
| 801-900     | 3         | 3.26%   |
| 601-700     | 2         | 2.17%   |
| 701-800     | 1         | 1.09%   |
| 1501-2000   | 1         | 1.09%   |
| 901-1000    | 1         | 1.09%   |
| Unknown     | 1         | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 63        | 75.9%   |
| 16/10 | 13        | 15.66%  |
| 5/4   | 2         | 2.41%   |
| 3/2   | 2         | 2.41%   |
| 21/9  | 2         | 2.41%   |
| 32/9  | 1         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 35.48%  |
| 81-90          | 11        | 11.83%  |
| 301-350        | 7         | 7.53%   |
| 201-250        | 7         | 7.53%   |
| 121-130        | 7         | 7.53%   |
| 61-70          | 5         | 5.38%   |
| 151-200        | 5         | 5.38%   |
| 351-500        | 4         | 4.3%    |
| 111-120        | 3         | 3.23%   |
| 501-1000       | 3         | 3.23%   |
| 71-80          | 2         | 2.15%   |
| 251-300        | 2         | 2.15%   |
| 141-150        | 2         | 2.15%   |
| More than 1000 | 1         | 1.08%   |
| Unknown        | 1         | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 33        | 36.26%  |
| 101-120       | 20        | 21.98%  |
| 51-100        | 20        | 21.98%  |
| 161-240       | 11        | 12.09%  |
| More than 240 | 6         | 6.59%   |
| Unknown       | 1         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 58        | 73.42%  |
| 2     | 19        | 24.05%  |
| 3     | 1         | 1.27%   |
| 0     | 1         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 56        | 41.79%  |
| Realtek Semiconductor             | 46        | 34.33%  |
| Qualcomm Atheros                  | 7         | 5.22%   |
| Broadcom                          | 5         | 3.73%   |
| Ralink Technology                 | 4         | 2.99%   |
| Broadcom Limited                  | 4         | 2.99%   |
| Huawei Technologies               | 3         | 2.24%   |
| DisplayLink                       | 2         | 1.49%   |
| TP-Link                           | 1         | 0.75%   |
| Sierra Wireless                   | 1         | 0.75%   |
| MediaTek                          | 1         | 0.75%   |
| Ericsson Business Mobile Networks | 1         | 0.75%   |
| Dell                              | 1         | 0.75%   |
| D-Link                            | 1         | 0.75%   |
| ASIX Electronics                  | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 23.03%  |
| Intel Wi-Fi 6 AX200                                               | 19        | 12.5%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 3.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 3.95%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3         | 1.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.32%   |
| Intel Wireless 3165                                               | 2         | 1.32%   |
| Intel Wireless 3160                                               | 2         | 1.32%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.32%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.32%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.32%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                  | 2         | 1.32%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.32%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 1.32%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.66%   |
| Sierra Wireless EM7455                                            | 1         | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.66%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.66%   |
| Realtek 802.11ac NIC                                              | 1         | 0.66%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.66%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.66%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.66%   |
| Intel Wireless-AC 9260                                            | 1         | 0.66%   |
| Intel Wireless 7260                                               | 1         | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.66%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.66%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 65.79%  |
| Realtek Semiconductor | 7         | 9.21%   |
| Ralink Technology     | 4         | 5.26%   |
| Qualcomm Atheros      | 4         | 5.26%   |
| Broadcom              | 4         | 5.26%   |
| Broadcom Limited      | 3         | 3.95%   |
| TP-Link               | 1         | 1.32%   |
| Sierra Wireless       | 1         | 1.32%   |
| MediaTek              | 1         | 1.32%   |
| D-Link                | 1         | 1.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 19        | 25%     |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 6         | 7.89%   |
| Intel Wireless 8265 / 8275                                           | 4         | 5.26%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 3.95%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 3.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 2.63%   |
| Intel Wireless 3165                                                  | 2         | 2.63%   |
| Intel Wireless 3160                                                  | 2         | 2.63%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 2.63%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 2.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 2         | 2.63%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 1.32%   |
| Sierra Wireless EM7455                                               | 1         | 1.32%   |
| Realtek 802.11ac NIC                                                 | 1         | 1.32%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 1.32%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1         | 1.32%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 1         | 1.32%   |
| Intel Wireless-AC 9260                                               | 1         | 1.32%   |
| Intel Wireless 7260                                                  | 1         | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1         | 1.32%   |
| Intel Ultimate N WiFi Link 5300                                      | 1         | 1.32%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 1         | 1.32%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 1.32%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.32%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1         | 1.32%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1         | 1.32%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter           | 1         | 1.32%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 44        | 62.86%  |
| Intel                 | 16        | 22.86%  |
| Qualcomm Atheros      | 3         | 4.29%   |
| Broadcom              | 3         | 4.29%   |
| DisplayLink           | 2         | 2.86%   |
| Broadcom Limited      | 1         | 1.43%   |
| ASIX Electronics      | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 49.3%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 8.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.23%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.82%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.41%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.41%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.41%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.41%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.41%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.41%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.41%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.41%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 1.41%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.41%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1         | 1.41%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 1.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 72        | 50%     |
| Ethernet | 67        | 46.53%  |
| Modem    | 5         | 3.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 50        | 62.5%   |
| Ethernet | 30        | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 52        | 65.82%  |
| 1     | 22        | 27.85%  |
| 3     | 4         | 5.06%   |
| 0     | 1         | 1.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 50.63%  |
| Yes  | 39        | 49.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 70.15%  |
| Realtek Semiconductor           | 5         | 7.46%   |
| Foxconn / Hon Hai               | 3         | 4.48%   |
| Cambridge Silicon Radio         | 3         | 4.48%   |
| Apple                           | 3         | 4.48%   |
| Broadcom                        | 2         | 2.99%   |
| Qualcomm Atheros Communications | 1         | 1.49%   |
| IMC Networks                    | 1         | 1.49%   |
| Dell                            | 1         | 1.49%   |
| ASUSTek Computer                | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 19        | 28.36%  |
| Intel Bluetooth wireless interface                  | 10        | 14.93%  |
| Intel AX201 Bluetooth                               | 8         | 11.94%  |
| Intel Bluetooth Device                              | 5         | 7.46%   |
| Realtek Bluetooth Radio                             | 3         | 4.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 4.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.99%   |
| Apple Bluetooth Host Controller                     | 2         | 2.99%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.49%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.49%   |
| Intel AX210 Bluetooth                               | 1         | 1.49%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.49%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.49%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.49%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.49%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.49%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.49%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.49%   |
| ASUS ASUS USB-BT500                                 | 1         | 1.49%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 58        | 53.7%   |
| Nvidia                                 | 23        | 21.3%   |
| AMD                                    | 21        | 19.44%  |
| Valve Software                         | 1         | 0.93%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.93%   |
| Logitech                               | 1         | 0.93%   |
| Kingston Technology                    | 1         | 0.93%   |
| JMTek                                  | 1         | 0.93%   |
| GN Netcom                              | 1         | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 18        | 14.4%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 8%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 6.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4%      |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 3.2%    |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 3.2%    |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 3.2%    |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 3.2%    |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 3.2%    |
| Intel Comet Lake PCH cAVS                                                  | 4         | 3.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.4%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.4%    |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.6%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.6%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.6%    |
| Intel CM238 HD Audio Controller                                            | 2         | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.6%    |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.6%    |
| Valve Software Valve VR Radio & HMD Mic                                    | 1         | 0.8%    |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.8%    |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.8%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.8%    |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.8%    |
| Logitech G430 Surround Sound Gaming Headset                                | 1         | 0.8%    |
| Kingston Technology HyperX QuadCast S                                      | 1         | 0.8%    |
| JMTek USB Audio Device                                                     | 1         | 0.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.8%    |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 0.8%    |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 0.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.8%    |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 0.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 34.78%  |
| SK hynix            | 6         | 26.09%  |
| Micron Technology   | 2         | 8.7%    |
| Unknown             | 2         | 8.7%    |
| Unknown (ABCD)      | 1         | 4.35%   |
| KLEVV               | 1         | 4.35%   |
| Elpida              | 1         | 4.35%   |
| Crucial             | 1         | 4.35%   |
| ASint Technology    | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s            | 3         | 12.5%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s          | 2         | 8.33%   |
| Unknown                                                           | 2         | 8.33%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1         | 4.17%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 4.17%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 4.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 4.17%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 1         | 4.17%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 4.17%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 4.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 1         | 4.17%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s            | 1         | 4.17%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s            | 1         | 4.17%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s            | 1         | 4.17%   |
| Micron RAM MT52L1G32D4PG-107 8GB Chip LPDDR3 1867MT/s             | 1         | 4.17%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s               | 1         | 4.17%   |
| KLEVV RAM KD48GU880-32A160X 8GB DIMM DDR4 2666MT/s                | 1         | 4.17%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s             | 1         | 4.17%   |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s            | 1         | 4.17%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s                | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 65%     |
| DDR3   | 4         | 20%     |
| LPDDR5 | 1         | 5%      |
| LPDDR4 | 1         | 5%      |
| LPDDR3 | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 75%     |
| DIMM         | 3         | 15%     |
| Row Of Chips | 1         | 5%      |
| Chip         | 1         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 8         | 36.36%  |
| 16384 | 6         | 27.27%  |
| 32768 | 3         | 13.64%  |
| 2048  | 3         | 13.64%  |
| 4096  | 2         | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 9         | 45%     |
| 1600  | 3         | 15%     |
| 2667  | 2         | 10%     |
| 8400  | 1         | 5%      |
| 6400  | 1         | 5%      |
| 2666  | 1         | 5%      |
| 2400  | 1         | 5%      |
| 1867  | 1         | 5%      |
| 1067  | 1         | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 100%    |

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
| Chicony Electronics                    | 27        | 49.09%  |
| Bison Electronics                      | 6         | 10.91%  |
| Microdia                               | 4         | 7.27%   |
| Suyin                                  | 2         | 3.64%   |
| Sunplus Innovation Technology          | 2         | 3.64%   |
| IMC Networks                           | 2         | 3.64%   |
| Apple                                  | 2         | 3.64%   |
| Acer                                   | 2         | 3.64%   |
| Valve Software                         | 1         | 1.82%   |
| Sony Ericsson Mobile Communications AB | 1         | 1.82%   |
| Ricoh                                  | 1         | 1.82%   |
| Realtek Semiconductor                  | 1         | 1.82%   |
| Luxvisions Innotech Limited            | 1         | 1.82%   |
| Lite-On Technology                     | 1         | 1.82%   |
| Generalplus Technology                 | 1         | 1.82%   |
| Alpha Imaging Technology               | 1         | 1.82%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated IR Camera                         | 6         | 10.91%  |
| Chicony USB2.0 Camera                                | 5         | 9.09%   |
| Chicony FHD Webcam                                   | 4         | 7.27%   |
| Chicony HD Webcam                                    | 3         | 5.45%   |
| IMC Networks Integrated Camera                       | 2         | 3.64%   |
| Chicony Integrated Camera                            | 2         | 3.64%   |
| Bison Lenovo EasyCamera                              | 2         | 3.64%   |
| Bison HD Webcam                                      | 2         | 3.64%   |
| Apple FaceTime HD Camera                             | 2         | 3.64%   |
| Acer BisonCam,NB Pro                                 | 2         | 3.64%   |
| Valve Software 3D Camera                             | 1         | 1.82%   |
| Suyin RGBIR Camera                                   | 1         | 1.82%   |
| Suyin HP TrueVision HD                               | 1         | 1.82%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.82%   |
| Sunplus Asus Webcam                                  | 1         | 1.82%   |
| Sony Ericsson Mobile AB XQ-CC54                      | 1         | 1.82%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 1.82%   |
| Realtek Integrated Webcam                            | 1         | 1.82%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 1.82%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 1.82%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.82%   |
| Microdia Integrated_Webcam_FHD                       | 1         | 1.82%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.82%   |
| Lite-On HP Wide Vision HD Camera                     | 1         | 1.82%   |
| Generalplus WEB CAM                                  | 1         | 1.82%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 1.82%   |
| Chicony USB 2.0 Camera                               | 1         | 1.82%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.82%   |
| Chicony HP Truevision HD                             | 1         | 1.82%   |
| Chicony FJ Camera                                    | 1         | 1.82%   |
| Chicony ACER FHD User Facing                         | 1         | 1.82%   |
| Chicony 1.3M Webcam                                  | 1         | 1.82%   |
| Bison SunplusIT Integrated Camera                    | 1         | 1.82%   |
| Bison Lenovo Integrated Webcam                       | 1         | 1.82%   |
| Alpha Imaging Integrated_Webcam_8M                   | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 7         | 58.33%  |
| Validity Sensors      | 4         | 33.33%  |
| LighTuning Technology | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics UWP WBDI                                | 2         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors VFS491                           | 1         | 8.33%   |
| Validity Sensors VFS Fingerprint sensor           | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner              | 1         | 8.33%   |
| Synaptics WBDI                                    | 1         | 8.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader  | 1         | 8.33%   |
| LighTuning Fingerprint Reader                     | 1         | 8.33%   |
| Unknown                                           | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 66.67%  |
| Alcor Micro | 2         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 47        | 59.49%  |
| 1     | 30        | 37.97%  |
| 3     | 1         | 1.27%   |
| 2     | 1         | 1.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 12        | 33.33%  |
| Multimedia controller | 9         | 25%     |
| Chipcard              | 6         | 16.67%  |
| Graphics card         | 4         | 11.11%  |
| Net/wireless          | 3         | 8.33%   |
| Modem                 | 1         | 2.78%   |
| Camera                | 1         | 2.78%   |

