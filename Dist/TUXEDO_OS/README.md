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

Total: 106

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [376e22722b](https://linux-hardware.org/?probe=376e22722b) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [388f380783](https://linux-hardware.org/?probe=388f380783) | Sep 02, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [c53e992822](https://linux-hardware.org/?probe=c53e992822) | Aug 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [679cf99998](https://linux-hardware.org/?probe=679cf99998) | Aug 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cd3074537b](https://linux-hardware.org/?probe=cd3074537b) | Aug 15, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [b6e2112ccb](https://linux-hardware.org/?probe=b6e2112ccb) | Aug 13, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| TUXEDO OS 22.04 | 82        | 100%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 82        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 6.1.0-1009-tuxedo   | 16        | 18.18%  |
| 6.2.0-10007-tuxedo  | 11        | 12.5%   |
| 6.2.0-10005-tuxedo  | 11        | 12.5%   |
| 6.2.0-10018-tuxedo  | 10        | 11.36%  |
| 6.2.0-10011-tuxedo  | 9         | 10.23%  |
| 5.15.0-10058-tuxedo | 7         | 7.95%   |
| 6.2.0-10010-tuxedo  | 6         | 6.82%   |
| 5.15.0-10048-tuxedo | 4         | 4.55%   |
| 5.15.0-10053-tuxedo | 3         | 3.41%   |
| 5.15.0-10052-tuxedo | 3         | 3.41%   |
| 5.15.0-10057-tuxedo | 2         | 2.27%   |
| 5.15.0-10056-tuxedo | 2         | 2.27%   |
| 5.15.0-10050-tuxedo | 2         | 2.27%   |
| 6.2.0-10014-tuxedo  | 1         | 1.14%   |
| 6.0.0-1010-oem      | 1         | 1.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 48        | 54.55%  |
| 5.15.0  | 23        | 26.14%  |
| 6.1.0   | 16        | 18.18%  |
| 6.0.0   | 1         | 1.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 48        | 54.55%  |
| 5.15    | 23        | 26.14%  |
| 6.1     | 16        | 18.18%  |
| 6.0     | 1         | 1.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 82        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| KDE5 | 82        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 79        | 95.18%  |
| Wayland | 4         | 4.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 69        | 82.14%  |
| SDDM    | 15        | 17.86%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| de_DE | 40        | 48.78%  |
| en_US | 17        | 20.73%  |
| en_GB | 6         | 7.32%   |
| pl_PL | 3         | 3.66%   |
| en_ZA | 3         | 3.66%   |
| fr_FR | 2         | 2.44%   |
| en_AG | 2         | 2.44%   |
| pt_PT | 1         | 1.22%   |
| pt_BR | 1         | 1.22%   |
| hu_HU | 1         | 1.22%   |
| es_ES | 1         | 1.22%   |
| en_DK | 1         | 1.22%   |
| en_CA | 1         | 1.22%   |
| en_AU | 1         | 1.22%   |
| de_CH | 1         | 1.22%   |
| de_AT | 1         | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 70        | 84.34%  |
| EFI  | 13        | 15.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 69        | 83.13%  |
| Btrfs   | 7         | 8.43%   |
| Tmpfs   | 3         | 3.61%   |
| Xfs     | 2         | 2.41%   |
| Overlay | 2         | 2.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 69        | 82.14%  |
| GPT     | 14        | 16.67%  |
| MBR     | 1         | 1.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 93.98%  |
| Yes       | 5         | 6.02%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 92.77%  |
| Yes       | 6         | 7.23%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| TUXEDO              | 27        | 32.93%  |
| Lenovo              | 11        | 13.41%  |
| ASUSTek Computer    | 10        | 12.2%   |
| Hewlett-Packard     | 9         | 10.98%  |
| Dell                | 8         | 9.76%   |
| MSI                 | 4         | 4.88%   |
| Apple               | 3         | 3.66%   |
| ASRock              | 2         | 2.44%   |
| Acer                | 2         | 2.44%   |
| Notebook            | 1         | 1.22%   |
| Gigabyte Technology | 1         | 1.22%   |
| Fujitsu             | 1         | 1.22%   |
| Fanless Mini PC     | 1         | 1.22%   |
| BESSTAR Tech        | 1         | 1.22%   |
| Unknown             | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| TUXEDO InfinityBook S 15/17 Gen7     | 4         | 4.88%   |
| Unknown                              | 3         | 3.66%   |
| TUXEDO Stellaris/Polaris AMD Gen4    | 2         | 2.44%   |
| TUXEDO Pulse 15 Gen2                 | 2         | 2.44%   |
| TUXEDO Pulse 15 Gen1                 | 2         | 2.44%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)   | 2         | 2.44%   |
| TUXEDO InfinityBook Pro 14 Gen6      | 2         | 2.44%   |
| MSI MS-7D17                          | 2         | 2.44%   |
| ASUS PRIME B450-PLUS                 | 2         | 2.44%   |
| Apple MacBookPro8,1                  | 2         | 2.44%   |
| TUXEDO XMG FUSION 15 (XFU15L19)      | 1         | 1.22%   |
| TUXEDO Stellaris AMD Gen3 (CZN)      | 1         | 1.22%   |
| TUXEDO Polaris AMD Gen3 (CZN)        | 1         | 1.22%   |
| TUXEDO Polaris 15 AMD Gen1           | 1         | 1.22%   |
| TUXEDO P64_HJ,HK1                    | 1         | 1.22%   |
| TUXEDO N7x0WU                        | 1         | 1.22%   |
| TUXEDO N13xWU                        | 1         | 1.22%   |
| TUXEDO InfinityBook S 15 Gen6        | 1         | 1.22%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)   | 1         | 1.22%   |
| TUXEDO Book XUX7 Gen13               | 1         | 1.22%   |
| TUXEDO Aura 15 Gen2                  | 1         | 1.22%   |
| Notebook W65_W67RB                   | 1         | 1.22%   |
| MSI MS-7D25                          | 1         | 1.22%   |
| MSI GE75 Raider 10SF                 | 1         | 1.22%   |
| Lenovo Yoga S740-15IRH 81NX          | 1         | 1.22%   |
| Lenovo ThinkPad X200 Tablet 7450WN9  | 1         | 1.22%   |
| Lenovo ThinkPad T490 20N3SBU219      | 1         | 1.22%   |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700  | 1         | 1.22%   |
| Lenovo ThinkPad E580 20KS003SUS      | 1         | 1.22%   |
| Lenovo ThinkPad 20JB002BUS           | 1         | 1.22%   |
| Lenovo ThinkCentre M700 10GSS05X48   | 1         | 1.22%   |
| Lenovo Legion 5 15ACH6H 82JU         | 1         | 1.22%   |
| Lenovo IdeaPad N581 7505             | 1         | 1.22%   |
| Lenovo G580 20150                    | 1         | 1.22%   |
| Lenovo G50-80 80E5                   | 1         | 1.22%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1         | 1.22%   |
| HP Pavilion dv6                      | 1         | 1.22%   |
| HP OMEN Laptop 15-en0xxx             | 1         | 1.22%   |
| HP Notebook                          | 1         | 1.22%   |
| HP Laptop 15-dw3xxx                  | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| TUXEDO InfinityBook   | 10        | 12.2%   |
| Lenovo ThinkPad       | 5         | 6.1%    |
| TUXEDO Pulse          | 4         | 4.88%   |
| TUXEDO Stellaris      | 3         | 3.66%   |
| ASUS PRIME            | 3         | 3.66%   |
| Unknown               | 3         | 3.66%   |
| TUXEDO Polaris        | 2         | 2.44%   |
| MSI MS-7D17           | 2         | 2.44%   |
| HP Pavilion           | 2         | 2.44%   |
| HP EliteBook          | 2         | 2.44%   |
| Dell Precision        | 2         | 2.44%   |
| Dell Latitude         | 2         | 2.44%   |
| ASUS ROG              | 2         | 2.44%   |
| Apple MacBookPro8     | 2         | 2.44%   |
| TUXEDO XMG            | 1         | 1.22%   |
| TUXEDO P64            | 1         | 1.22%   |
| TUXEDO N7x0WU         | 1         | 1.22%   |
| TUXEDO N13xWU         | 1         | 1.22%   |
| TUXEDO Book           | 1         | 1.22%   |
| TUXEDO Aura           | 1         | 1.22%   |
| Notebook W65          | 1         | 1.22%   |
| MSI MS-7D25           | 1         | 1.22%   |
| MSI GE75              | 1         | 1.22%   |
| Lenovo Yoga           | 1         | 1.22%   |
| Lenovo ThinkCentre    | 1         | 1.22%   |
| Lenovo Legion         | 1         | 1.22%   |
| Lenovo IdeaPad        | 1         | 1.22%   |
| Lenovo G580           | 1         | 1.22%   |
| Lenovo G50-80         | 1         | 1.22%   |
| HP OMEN               | 1         | 1.22%   |
| HP Notebook           | 1         | 1.22%   |
| HP Laptop             | 1         | 1.22%   |
| HP ENVY               | 1         | 1.22%   |
| HP 280                | 1         | 1.22%   |
| Gigabyte H81M-HD3     | 1         | 1.22%   |
| Fujitsu LIFEBOOK      | 1         | 1.22%   |
| Fanless Mini PC PCG35 | 1         | 1.22%   |
| Dell Vostro           | 1         | 1.22%   |
| Dell Venue            | 1         | 1.22%   |
| Dell OptiPlex         | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 18        | 21.95%  |
| 2020 | 12        | 14.63%  |
| 2021 | 11        | 13.41%  |
| 2015 | 8         | 9.76%   |
| 2019 | 6         | 7.32%   |
| 2012 | 5         | 6.1%    |
| 2017 | 4         | 4.88%   |
| 2011 | 4         | 4.88%   |
| 2018 | 3         | 3.66%   |
| 2023 | 2         | 2.44%   |
| 2016 | 2         | 2.44%   |
| 2014 | 2         | 2.44%   |
| 2013 | 2         | 2.44%   |
| 2010 | 1         | 1.22%   |
| 2009 | 1         | 1.22%   |
| 2008 | 1         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 63        | 76.83%  |
| Desktop     | 16        | 19.51%  |
| Tablet      | 1         | 1.22%   |
| Convertible | 1         | 1.22%   |
| Mini pc     | 1         | 1.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 82        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 82        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 18        | 21.95%  |
| 32.01-64.0  | 16        | 19.51%  |
| 8.01-16.0   | 16        | 19.51%  |
| 4.01-8.0    | 14        | 17.07%  |
| 64.01-256.0 | 8         | 9.76%   |
| 3.01-4.0    | 7         | 8.54%   |
| 24.01-32.0  | 3         | 3.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 26        | 29.89%  |
| 2.01-3.0   | 20        | 22.99%  |
| 1.01-2.0   | 20        | 22.99%  |
| 3.01-4.0   | 13        | 14.94%  |
| 8.01-16.0  | 6         | 6.9%    |
| 16.01-24.0 | 2         | 2.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 48.19%  |
| 2      | 33        | 39.76%  |
| 4      | 4         | 4.82%   |
| 5      | 3         | 3.61%   |
| 3      | 3         | 3.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 80.49%  |
| Yes       | 16        | 19.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 85.37%  |
| No        | 12        | 14.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 90.24%  |
| No        | 8         | 9.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 83.13%  |
| No        | 14        | 16.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 42        | 51.22%  |
| USA          | 9         | 10.98%  |
| UK           | 5         | 6.1%    |
| Switzerland  | 3         | 3.66%   |
| South Africa | 3         | 3.66%   |
| Poland       | 3         | 3.66%   |
| Portugal     | 2         | 2.44%   |
| France       | 2         | 2.44%   |
| Austria      | 2         | 2.44%   |
| Turkey       | 1         | 1.22%   |
| Spain        | 1         | 1.22%   |
| Romania      | 1         | 1.22%   |
| Netherlands  | 1         | 1.22%   |
| Egypt        | 1         | 1.22%   |
| Denmark      | 1         | 1.22%   |
| Czechia      | 1         | 1.22%   |
| Canada       | 1         | 1.22%   |
| Bulgaria     | 1         | 1.22%   |
| Brazil       | 1         | 1.22%   |
| Australia    | 1         | 1.22%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Zurich             | 2         | 2.41%   |
| Vienna             | 2         | 2.41%   |
| Schweinfurt        | 2         | 2.41%   |
| Munich             | 2         | 2.41%   |
| Leipzig            | 2         | 2.41%   |
| Johannesburg       | 2         | 2.41%   |
| Hürth             | 2         | 2.41%   |
| Berlin             | 2         | 2.41%   |
| Zalău             | 1         | 1.2%    |
| Zabrze             | 1         | 1.2%    |
| Wembley            | 1         | 1.2%    |
| Watertown          | 1         | 1.2%    |
| Warsaw             | 1         | 1.2%    |
| Walsall            | 1         | 1.2%    |
| Ulm                | 1         | 1.2%    |
| Stuttgart          | 1         | 1.2%    |
| Stockstadt am Main | 1         | 1.2%    |
| Solingen           | 1         | 1.2%    |
| Sistov             | 1         | 1.2%    |
| Seattle            | 1         | 1.2%    |
| Rio Maior          | 1         | 1.2%    |
| Reno               | 1         | 1.2%    |
| Rennes             | 1         | 1.2%    |
| Redcar             | 1         | 1.2%    |
| Pruem              | 1         | 1.2%    |
| Prague             | 1         | 1.2%    |
| Perrysburg         | 1         | 1.2%    |
| Peitz              | 1         | 1.2%    |
| Paris              | 1         | 1.2%    |
| Offenbach          | 1         | 1.2%    |
| Nuremberg          | 1         | 1.2%    |
| Neuwied            | 1         | 1.2%    |
| Nashville          | 1         | 1.2%    |
| Melton Mowbray     | 1         | 1.2%    |
| Mannheim           | 1         | 1.2%    |
| Lucerne            | 1         | 1.2%    |
| Lublin             | 1         | 1.2%    |
| Lippstadt          | 1         | 1.2%    |
| Lehre              | 1         | 1.2%    |
| Langenhagen        | 1         | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 43        | 59     | 34.13%  |
| Seagate                     | 14        | 19     | 11.11%  |
| Sandisk                     | 13        | 16     | 10.32%  |
| Kingston                    | 6         | 6      | 4.76%   |
| Hitachi                     | 6         | 9      | 4.76%   |
| WDC                         | 5         | 6      | 3.97%   |
| Unknown                     | 2         | 2      | 1.59%   |
| Toshiba                     | 2         | 2      | 1.59%   |
| SPCC                        | 2         | 2      | 1.59%   |
| SK hynix                    | 2         | 3      | 1.59%   |
| Phison Electronics          | 2         | 2      | 1.59%   |
| Micron Technology           | 2         | 2      | 1.59%   |
| GOODRAM                     | 2         | 2      | 1.59%   |
| USB3.0                      | 1         | 1      | 0.79%   |
| Transcend                   | 1         | 1      | 0.79%   |
| Silicon Motion              | 1         | 2      | 0.79%   |
| OWC                         | 1         | 1      | 0.79%   |
| Netac                       | 1         | 1      | 0.79%   |
| Micron/Crucial Technology   | 1         | 1      | 0.79%   |
| LITEONIT                    | 1         | 1      | 0.79%   |
| Lite-On Technology          | 1         | 1      | 0.79%   |
| Lenovo                      | 1         | 1      | 0.79%   |
| Kingston Technology Company | 1         | 1      | 0.79%   |
| Kingchuxing                 | 1         | 1      | 0.79%   |
| Intenso                     | 1         | 1      | 0.79%   |
| Intel                       | 1         | 1      | 0.79%   |
| HS-SSD-E100                 | 1         | 1      | 0.79%   |
| Hikvision                   | 1         | 2      | 0.79%   |
| HGST HTS                    | 1         | 1      | 0.79%   |
| HGST                        | 1         | 1      | 0.79%   |
| CT1000BX                    | 1         | 1      | 0.79%   |
| Crucial                     | 1         | 1      | 0.79%   |
| China                       | 1         | 1      | 0.79%   |
| ASMT                        | 1         | 1      | 0.79%   |
| Apple                       | 1         | 1      | 0.79%   |
| Apacer                      | 1         | 1      | 0.79%   |
| AMD                         | 1         | 2      | 0.79%   |
| Unknown                     | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 9         | 6.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 9         | 6.57%   |
| Samsung SSD 980 500GB                                 | 7         | 5.11%   |
| Samsung SSD 980 1TB                                   | 6         | 4.38%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 5         | 3.65%   |
| Seagate ST3500418AS 500GB                             | 2         | 1.46%   |
| Seagate ST1000VT001-1RE172 1TB                        | 2         | 1.46%   |
| Sandisk WD Black SN850 256GB                          | 2         | 1.46%   |
| SanDisk SSD PLUS 120GB                                | 2         | 1.46%   |
| Samsung SSD 980 PRO 500GB                             | 2         | 1.46%   |
| Samsung SSD 980 PRO 1TB                               | 2         | 1.46%   |
| Samsung SSD 970 EVO Plus 1TB                          | 2         | 1.46%   |
| Samsung SSD 850 EVO 500GB                             | 2         | 1.46%   |
| Kingston SA400S37240G 240GB SSD                       | 2         | 1.46%   |
| Hitachi HTS727550A9E364 500GB                         | 2         | 1.46%   |
| Hitachi HCS545050GLA380 500GB                         | 2         | 1.46%   |
| WDC WD80EAZZ-00BKLB0 8TB                              | 1         | 0.73%   |
| WDC WD3200BPVT-24JJ5T0 320GB                          | 1         | 0.73%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 1         | 0.73%   |
| WDC WD10JPVX-22JC3T0 1TB                              | 1         | 0.73%   |
| WDC WD10JPVX-11JC3T0 1TB                              | 1         | 0.73%   |
| WDC WD Elements SE SSD 1TB                            | 1         | 0.73%   |
| USB3.0 Super Speed 128GB                              | 1         | 0.73%   |
| Unknown MMC Card  64GB                                | 1         | 0.73%   |
| Unknown MMC Card  2GB                                 | 1         | 0.73%   |
| Transcend TS512GSSD230S 512GB                         | 1         | 0.73%   |
| Toshiba XG4 NVMe SSD Controller 256GB                 | 1         | 0.73%   |
| Toshiba MQ01ABD100 1TB                                | 1         | 0.73%   |
| SPCC M.2 SSD 256GB                                    | 1         | 0.73%   |
| SPCC M.2 PCIe SSD 1TB                                 | 1         | 0.73%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                  | 1         | 0.73%   |
| SK hynix SC311 SATA 256GB SSD                         | 1         | 0.73%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1024GB  | 1         | 0.73%   |
| Seagate ST500LT012-1DG142 500GB                       | 1         | 0.73%   |
| Seagate ST500LM034-2GH17A 500GB                       | 1         | 0.73%   |
| Seagate ST500DM002-1BD142 500GB                       | 1         | 0.73%   |
| Seagate ST3500413AS 500GB                             | 1         | 0.73%   |
| Seagate ST250LT003-9YG14C 250GB                       | 1         | 0.73%   |
| Seagate ST2000LM015-2E8174 2TB                        | 1         | 0.73%   |
| Seagate ST2000LM007-1R8174 2TB                        | 1         | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 13        | 18     | 48.15%  |
| Hitachi  | 6         | 9      | 22.22%  |
| WDC      | 4         | 5      | 14.81%  |
| USB3.0   | 1         | 1      | 3.7%    |
| Toshiba  | 1         | 1      | 3.7%    |
| HGST HTS | 1         | 1      | 3.7%    |
| HGST     | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 21.88%  |
| SanDisk             | 4         | 5      | 12.5%   |
| Kingston            | 4         | 4      | 12.5%   |
| GOODRAM             | 2         | 2      | 6.25%   |
| WDC                 | 1         | 1      | 3.13%   |
| Transcend           | 1         | 1      | 3.13%   |
| SPCC                | 1         | 1      | 3.13%   |
| SK hynix            | 1         | 2      | 3.13%   |
| OWC                 | 1         | 1      | 3.13%   |
| Netac               | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| LITEONIT            | 1         | 1      | 3.13%   |
| Intenso             | 1         | 1      | 3.13%   |
| CT1000BX            | 1         | 1      | 3.13%   |
| Crucial             | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |
| ASMT                | 1         | 1      | 3.13%   |
| Apple               | 1         | 1      | 3.13%   |
| Apacer              | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 55        | 82     | 49.11%  |
| SSD     | 27        | 35     | 24.11%  |
| HDD     | 25        | 36     | 22.32%  |
| MMC     | 3         | 3      | 2.68%   |
| Unknown | 2         | 2      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 55        | 82     | 52.88%  |
| SATA | 41        | 67     | 39.42%  |
| SAS  | 5         | 6      | 4.81%   |
| MMC  | 3         | 3      | 2.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 45     | 56.6%   |
| 0.51-1.0   | 18        | 21     | 33.96%  |
| 1.01-2.0   | 4         | 4      | 7.55%   |
| 4.01-10.0  | 1         | 1      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 23        | 27.71%  |
| 101-250        | 18        | 21.69%  |
| 251-500        | 17        | 20.48%  |
| 1001-2000      | 8         | 9.64%   |
| 2001-3000      | 5         | 6.02%   |
| 1-20           | 4         | 4.82%   |
| More than 3000 | 2         | 2.41%   |
| 21-50          | 2         | 2.41%   |
| 51-100         | 2         | 2.41%   |
| Unknown        | 2         | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 25        | 29.41%  |
| 21-50     | 24        | 28.24%  |
| 101-250   | 14        | 16.47%  |
| 51-100    | 7         | 8.24%   |
| 251-500   | 6         | 7.06%   |
| 501-1000  | 4         | 4.71%   |
| 1001-2000 | 3         | 3.53%   |
| Unknown   | 2         | 2.35%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 70        | 134    | 81.4%   |
| Works    | 16        | 24     | 18.6%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 44        | 37.93%  |
| Samsung Electronics          | 38        | 32.76%  |
| AMD                          | 11        | 9.48%   |
| SanDisk                      | 9         | 7.76%   |
| Kingston Technology Company  | 3         | 2.59%   |
| Silicon Motion               | 2         | 1.72%   |
| Phison Electronics           | 2         | 1.72%   |
| Toshiba America Info Systems | 1         | 0.86%   |
| SK hynix                     | 1         | 0.86%   |
| Seagate Technology           | 1         | 0.86%   |
| Micron/Crucial Technology    | 1         | 0.86%   |
| Micron Technology            | 1         | 0.86%   |
| Lite-On Technology           | 1         | 0.86%   |
| Lenovo                       | 1         | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980                                                | 13        | 10.48%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 9.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 8.87%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 8.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.84%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 3.23%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 3         | 2.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.42%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 2.42%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 2.42%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 1.61%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.61%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.81%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.81%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                      | 1         | 0.81%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 0.81%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.81%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.81%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.81%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.81%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 0.81%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.81%   |
| Lenovo LENSE30256GMSP34MEAT3TA                                                 | 1         | 0.81%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.81%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 0.81%   |
| Kingston Company NVMe Controller                                               | 1         | 0.81%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 0.81%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.81%   |
| Intel SSD 660P Series                                                          | 1         | 0.81%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 55        | 49.55%  |
| SATA | 49        | 44.14%  |
| RAID | 6         | 5.41%   |
| IDE  | 1         | 0.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 61        | 74.39%  |
| AMD    | 21        | 25.61%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H           | 3         | 3.66%   |
| Intel 12th Gen Core i7-1260P            | 3         | 3.66%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 3         | 3.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 2.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 2.44%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 2         | 2.44%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 2.44%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 2.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2         | 2.44%   |
| Intel 12th Gen Core i5-1240P            | 2         | 2.44%   |
| AMD Ryzen 7 6800H with Radeon Graphics  | 2         | 2.44%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 2.44%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 2.44%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2         | 2.44%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 2         | 2.44%   |
| Intel Xeon W-10855M CPU @ 2.80GHz       | 1         | 1.22%   |
| Intel Pentium CPU G3420 @ 3.20GHz       | 1         | 1.22%   |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 1.22%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz        | 1         | 1.22%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.22%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.22%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.22%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.22%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.22%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 1.22%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.22%   |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 1.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.22%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 1         | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.22%   |
| Intel Core i5-7600T CPU @ 2.80GHz       | 1         | 1.22%   |
| Intel Core i5-5250U CPU @ 1.60GHz       | 1         | 1.22%   |
| Intel Core i5-4590S CPU @ 3.00GHz       | 1         | 1.22%   |
| Intel Core i5-4300Y CPU @ 1.60GHz       | 1         | 1.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.22%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 1         | 1.22%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1         | 1.22%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 1         | 1.22%   |
| Intel Core i5 CPU M 540 @ 2.53GHz       | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Other            | 19        | 23.17%  |
| Intel Core i7    | 19        | 23.17%  |
| Intel Core i5    | 15        | 18.29%  |
| AMD Ryzen 7      | 10        | 12.2%   |
| AMD Ryzen 5      | 6         | 7.32%   |
| Intel Pentium    | 2         | 2.44%   |
| Intel Core i3    | 2         | 2.44%   |
| Intel Celeron    | 2         | 2.44%   |
| AMD Ryzen 9      | 2         | 2.44%   |
| Intel Xeon       | 1         | 1.22%   |
| Intel Core 2 Duo | 1         | 1.22%   |
| AMD Ryzen 5 PRO  | 1         | 1.22%   |
| AMD Ryzen 3      | 1         | 1.22%   |
| AMD A8           | 1         | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 26        | 31.71%  |
| 2      | 17        | 20.73%  |
| 6      | 15        | 18.29%  |
| 8      | 13        | 15.85%  |
| 12     | 6         | 7.32%   |
| 14     | 3         | 3.66%   |
| 16     | 1         | 1.22%   |
| 10     | 1         | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 82        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 72        | 87.8%   |
| 1      | 10        | 12.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 82        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 88.1%   |
| 0xa0653    | 1         | 1.19%   |
| 0x906ea    | 1         | 1.19%   |
| 0x906e9    | 1         | 1.19%   |
| 0x906a4    | 1         | 1.19%   |
| 0x906a3    | 1         | 1.19%   |
| 0x806c1    | 1         | 1.19%   |
| 0x306d4    | 1         | 1.19%   |
| 0x0a50000d | 1         | 1.19%   |
| 0x0a50000c | 1         | 1.19%   |
| 0x08608103 | 1         | 1.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 18        | 21.95%  |
| KabyLake         | 12        | 14.63%  |
| IvyBridge        | 8         | 9.76%   |
| Zen 3            | 6         | 7.32%   |
| Zen 2            | 6         | 7.32%   |
| CometLake        | 5         | 6.1%    |
| TigerLake        | 4         | 4.88%   |
| SandyBridge      | 4         | 4.88%   |
| Haswell          | 4         | 4.88%   |
| Skylake          | 3         | 3.66%   |
| Broadwell        | 3         | 3.66%   |
| Alderlake Hybrid | 3         | 3.66%   |
| Zen+             | 2         | 2.44%   |
| Westmere         | 1         | 1.22%   |
| Puma             | 1         | 1.22%   |
| Penryn           | 1         | 1.22%   |
| Goldmont plus    | 1         | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 56        | 52.34%  |
| Nvidia | 29        | 27.1%   |
| AMD    | 22        | 20.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P Integrated Graphics Controller                           | 8         | 7.48%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 5.61%   |
| AMD Renoir                                                                  | 5         | 4.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 4.67%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 4         | 3.74%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 4         | 3.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 3.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 3.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 3.74%   |
| Intel UHD Graphics 620                                                      | 3         | 2.8%    |
| Intel HD Graphics 630                                                       | 3         | 2.8%    |
| Intel HD Graphics 530                                                       | 3         | 2.8%    |
| AMD Rembrandt [Radeon 680M]                                                 | 3         | 2.8%    |
| AMD Lucienne                                                                | 3         | 2.8%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.87%   |
| Nvidia GF108M [GeForce GT 635M]                                             | 2         | 1.87%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                    | 2         | 1.87%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                               | 2         | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.87%   |
| Intel HD Graphics 5500                                                      | 2         | 1.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.93%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.93%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 1         | 0.93%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.93%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.93%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.93%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 1         | 0.93%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 1         | 0.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 0.93%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1         | 0.93%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 1         | 0.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 46.99%  |
| Intel + Nvidia | 13        | 15.66%  |
| 1 x AMD        | 12        | 14.46%  |
| 1 x Nvidia     | 8         | 9.64%   |
| AMD + Nvidia   | 8         | 9.64%   |
| Intel + AMD    | 3         | 3.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 56        | 68.29%  |
| Proprietary | 25        | 30.49%  |
| Unknown     | 1         | 1.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 69.88%  |
| 5.01-6.0   | 10        | 12.05%  |
| 7.01-8.0   | 5         | 6.02%   |
| 3.01-4.0   | 4         | 4.82%   |
| 1.01-2.0   | 3         | 3.61%   |
| 0.01-0.5   | 2         | 2.41%   |
| 8.01-16.0  | 1         | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 22        | 22.68%  |
| Samsung Electronics | 12        | 12.37%  |
| AU Optronics        | 12        | 12.37%  |
| Acer                | 7         | 7.22%   |
| LG Display          | 5         | 5.15%   |
| Dell                | 5         | 5.15%   |
| Chimei Innolux      | 5         | 5.15%   |
| CSO                 | 4         | 4.12%   |
| Apple               | 3         | 3.09%   |
| Lenovo              | 2         | 2.06%   |
| Iiyama              | 2         | 2.06%   |
| Hewlett-Packard     | 2         | 2.06%   |
| Goldstar            | 2         | 2.06%   |
| BenQ                | 2         | 2.06%   |
| AOC                 | 2         | 2.06%   |
| Yamaha              | 1         | 1.03%   |
| ViewSonic           | 1         | 1.03%   |
| Sharp               | 1         | 1.03%   |
| SGT                 | 1         | 1.03%   |
| RTK                 | 1         | 1.03%   |
| Philips             | 1         | 1.03%   |
| PANDA               | 1         | 1.03%   |
| InfoVision          | 1         | 1.03%   |
| Eizo                | 1         | 1.03%   |
| ASUSTek Computer    | 1         | 1.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 5         | 5%      |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 4         | 4%      |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 4%      |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                     | 2         | 2%      |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 2         | 2%      |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 2%      |
| Acer EK240Y ACR0758 1920x1080 527x296mm 23.8-inch                       | 2         | 2%      |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 1%      |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 1%      |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 1%      |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 1%      |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 1%      |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch       | 1         | 1%      |
| Samsung Electronics S27C36x SAM7315 1920x1080 598x336mm 27.0-inch       | 1         | 1%      |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC424D 2160x1440 254x169mm 12.0-inch   | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 1%      |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 1%      |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1%      |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 1%      |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 1%      |
| RTK Wimaxit FHD RTK5A5B 1920x1080 344x195mm 15.6-inch                   | 1         | 1%      |
| Philips 170S4 PHL0818 1280x1024 338x270mm 17.0-inch                     | 1         | 1%      |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 1%      |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch            | 1         | 1%      |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 1%      |
| LG Display LCD Monitor LGD0545 3200x1800 293x165mm 13.2-inch            | 1         | 1%      |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 1%      |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 1%      |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                | 1         | 1%      |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                 | 1         | 1%      |
| InfoVision LCD Monitor IVO3414 1920x1080 294x165mm 13.3-inch            | 1         | 1%      |
| Iiyama PL3466WQ IVM7627 3440x1440 795x334mm 33.9-inch                   | 1         | 1%      |
| Iiyama PL2290 IVM562C 1920x1080 476x268mm 21.5-inch                     | 1         | 1%      |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch              | 1         | 1%      |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch            | 1         | 1%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 43        | 47.25%  |
| 1366x768 (WXGA)    | 11        | 12.09%  |
| 2560x1440 (QHD)    | 10        | 10.99%  |
| 3840x2160 (4K)     | 5         | 5.49%   |
| 2880x1800          | 4         | 4.4%    |
| 1280x800 (WXGA)    | 3         | 3.3%    |
| 1920x1200 (WUXGA)  | 2         | 2.2%    |
| 1600x900 (HD+)     | 2         | 2.2%    |
| 1280x1024 (SXGA)   | 2         | 2.2%    |
| 3440x1440          | 1         | 1.1%    |
| 3200x1800 (QHD+)   | 1         | 1.1%    |
| 2560x1600          | 1         | 1.1%    |
| 2560x1080          | 1         | 1.1%    |
| 2240x1400          | 1         | 1.1%    |
| 2160x1440          | 1         | 1.1%    |
| 1920x540           | 1         | 1.1%    |
| 1680x1050 (WSXGA+) | 1         | 1.1%    |
| 1440x900 (WXGA+)   | 1         | 1.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 34        | 34.69%  |
| 27      | 8         | 8.16%   |
| 24      | 8         | 8.16%   |
| 17      | 8         | 8.16%   |
| 13      | 8         | 8.16%   |
| 14      | 5         | 5.1%    |
| 12      | 5         | 5.1%    |
| 16      | 3         | 3.06%   |
| 40      | 2         | 2.04%   |
| 31      | 2         | 2.04%   |
| 23      | 2         | 2.04%   |
| 22      | 2         | 2.04%   |
| 21      | 2         | 2.04%   |
| 20      | 2         | 2.04%   |
| 84      | 1         | 1.02%   |
| 43      | 1         | 1.02%   |
| 34      | 1         | 1.02%   |
| 33      | 1         | 1.02%   |
| 19      | 1         | 1.02%   |
| 18      | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 45.26%  |
| 501-600     | 16        | 16.84%  |
| 201-300     | 11        | 11.58%  |
| 351-400     | 9         | 9.47%   |
| 401-500     | 7         | 7.37%   |
| 801-900     | 3         | 3.16%   |
| 601-700     | 2         | 2.11%   |
| 701-800     | 1         | 1.05%   |
| 1501-2000   | 1         | 1.05%   |
| 901-1000    | 1         | 1.05%   |
| Unknown     | 1         | 1.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 66        | 75.86%  |
| 16/10 | 14        | 16.09%  |
| 5/4   | 2         | 2.3%    |
| 3/2   | 2         | 2.3%    |
| 21/9  | 2         | 2.3%    |
| 32/9  | 1         | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 34.69%  |
| 81-90          | 11        | 11.22%  |
| 201-250        | 9         | 9.18%   |
| 301-350        | 8         | 8.16%   |
| 121-130        | 7         | 7.14%   |
| 61-70          | 5         | 5.1%    |
| 151-200        | 5         | 5.1%    |
| 351-500        | 4         | 4.08%   |
| 251-300        | 3         | 3.06%   |
| 111-120        | 3         | 3.06%   |
| 501-1000       | 3         | 3.06%   |
| 71-80          | 2         | 2.04%   |
| 141-150        | 2         | 2.04%   |
| More than 1000 | 1         | 1.02%   |
| Unknown        | 1         | 1.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 36.17%  |
| 51-100        | 22        | 23.4%   |
| 101-120       | 20        | 21.28%  |
| 161-240       | 11        | 11.7%   |
| More than 240 | 6         | 6.38%   |
| Unknown       | 1         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 60        | 73.17%  |
| 2     | 19        | 23.17%  |
| 3     | 2         | 2.44%   |
| 0     | 1         | 1.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 58        | 41.73%  |
| Realtek Semiconductor             | 49        | 35.25%  |
| Qualcomm Atheros                  | 7         | 5.04%   |
| Broadcom                          | 5         | 3.6%    |
| Ralink Technology                 | 4         | 2.88%   |
| Broadcom Limited                  | 4         | 2.88%   |
| Huawei Technologies               | 3         | 2.16%   |
| DisplayLink                       | 2         | 1.44%   |
| TP-Link                           | 1         | 0.72%   |
| Sierra Wireless                   | 1         | 0.72%   |
| MediaTek                          | 1         | 0.72%   |
| Ericsson Business Mobile Networks | 1         | 0.72%   |
| Dell                              | 1         | 0.72%   |
| D-Link                            | 1         | 0.72%   |
| ASIX Electronics                  | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 23.42%  |
| Intel Wi-Fi 6 AX200                                               | 19        | 12.03%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 4.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 3.8%    |
| Intel Wireless 8265 / 8275                                        | 4         | 2.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3         | 1.9%    |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.9%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.27%   |
| Intel Wireless 3165                                               | 2         | 1.27%   |
| Intel Wireless 3160                                               | 2         | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.27%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.27%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                  | 2         | 1.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.27%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 1.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.63%   |
| Sierra Wireless EM7455                                            | 1         | 0.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.63%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.63%   |
| Realtek 802.11ac NIC                                              | 1         | 0.63%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.63%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.63%   |
| Intel Wireless-AC 9260                                            | 1         | 0.63%   |
| Intel Wireless 7260                                               | 1         | 0.63%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.63%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 66.67%  |
| Realtek Semiconductor | 7         | 8.97%   |
| Ralink Technology     | 4         | 5.13%   |
| Qualcomm Atheros      | 4         | 5.13%   |
| Broadcom              | 4         | 5.13%   |
| Broadcom Limited      | 3         | 3.85%   |
| TP-Link               | 1         | 1.28%   |
| Sierra Wireless       | 1         | 1.28%   |
| MediaTek              | 1         | 1.28%   |
| D-Link                | 1         | 1.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 19        | 24.36%  |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 6         | 7.69%   |
| Intel Wireless 8265 / 8275                                           | 4         | 5.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 3.85%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 3.85%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 2.56%   |
| Intel Wireless 3165                                                  | 2         | 2.56%   |
| Intel Wireless 3160                                                  | 2         | 2.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 2         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 2.56%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 2.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 2         | 2.56%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 1.28%   |
| Sierra Wireless EM7455                                               | 1         | 1.28%   |
| Realtek 802.11ac NIC                                                 | 1         | 1.28%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 1.28%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1         | 1.28%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 1         | 1.28%   |
| Intel Wireless-AC 9260                                               | 1         | 1.28%   |
| Intel Wireless 7260                                                  | 1         | 1.28%   |
| Intel Ultimate N WiFi Link 5300                                      | 1         | 1.28%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 1         | 1.28%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 1.28%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.28%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1         | 1.28%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1         | 1.28%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter           | 1         | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 1.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 47        | 64.38%  |
| Intel                 | 16        | 21.92%  |
| Qualcomm Atheros      | 3         | 4.11%   |
| Broadcom              | 3         | 4.11%   |
| DisplayLink           | 2         | 2.74%   |
| Broadcom Limited      | 1         | 1.37%   |
| ASIX Electronics      | 1         | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 49.33%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 9.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.67%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.67%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.33%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.33%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.33%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.33%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.33%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.33%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.33%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.33%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.33%   |
| DisplayLink USB 3.0 Dual 4K Displayport adapter                   | 1         | 1.33%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.33%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1         | 1.33%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 49.66%  |
| Ethernet | 70        | 46.98%  |
| Modem    | 5         | 3.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 62.2%   |
| Ethernet | 31        | 37.8%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 54        | 65.85%  |
| 1     | 23        | 28.05%  |
| 3     | 4         | 4.88%   |
| 0     | 1         | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 51.22%  |
| Yes  | 40        | 48.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 70%     |
| Realtek Semiconductor           | 5         | 7.14%   |
| Foxconn / Hon Hai               | 3         | 4.29%   |
| Cambridge Silicon Radio         | 3         | 4.29%   |
| Apple                           | 3         | 4.29%   |
| Broadcom                        | 2         | 2.86%   |
| Qualcomm Atheros Communications | 1         | 1.43%   |
| IMC Networks                    | 1         | 1.43%   |
| Dell                            | 1         | 1.43%   |
| ASUSTek Computer                | 1         | 1.43%   |
| Unknown                         | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 19        | 27.14%  |
| Intel Bluetooth wireless interface                  | 10        | 14.29%  |
| Intel AX201 Bluetooth                               | 9         | 12.86%  |
| Intel Bluetooth Device                              | 5         | 7.14%   |
| Realtek Bluetooth Radio                             | 3         | 4.29%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 4.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.86%   |
| Intel AX210 Bluetooth                               | 2         | 2.86%   |
| Apple Bluetooth Host Controller                     | 2         | 2.86%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.43%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.43%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.43%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.43%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.43%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.43%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.43%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.43%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.43%   |
| ASUS ASUS USB-BT500                                 | 1         | 1.43%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.43%   |
| Unknown                                             | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 59        | 53.15%  |
| Nvidia                                 | 24        | 21.62%  |
| AMD                                    | 22        | 19.82%  |
| Valve Software                         | 1         | 0.9%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.9%    |
| Logitech                               | 1         | 0.9%    |
| Kingston Technology                    | 1         | 0.9%    |
| JMTek                                  | 1         | 0.9%    |
| GN Netcom                              | 1         | 0.9%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 14.73%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 7.75%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 6.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 3.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 3.1%    |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 3.1%    |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 3.1%    |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 3.1%    |
| Intel Comet Lake PCH cAVS                                                  | 4         | 3.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.33%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.33%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.33%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 1.55%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.55%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.55%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.55%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.55%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1         | 0.78%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.78%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1         | 0.78%   |
| Kingston Technology HyperX QuadCast S                                      | 1         | 0.78%   |
| JMTek USB Audio Device                                                     | 1         | 0.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.78%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 0.78%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.78%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 0.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


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

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 3         | 12.5%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 8.33%   |
| Unknown                                                        | 2         | 8.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 4.17%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 4.17%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s      | 1         | 4.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 4.17%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 4.17%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 4.17%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 4.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 4.17%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 4.17%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 4.17%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s         | 1         | 4.17%   |
| Micron RAM MT52L1G32D4PG-107 8GB Chip LPDDR3 1867MT/s          | 1         | 4.17%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s            | 1         | 4.17%   |
| KLEVV RAM KD48GU880-32A160X 8GB DIMM DDR4 2666MT/s             | 1         | 4.17%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM 1067MT/s               | 1         | 4.17%   |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s         | 1         | 4.17%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s             | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


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

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 75%     |
| DIMM         | 3         | 15%     |
| Row Of Chips | 1         | 5%      |
| Chip         | 1         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


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

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


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

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 48.21%  |
| Bison Electronics                      | 7         | 12.5%   |
| Microdia                               | 4         | 7.14%   |
| Sunplus Innovation Technology          | 3         | 5.36%   |
| Suyin                                  | 2         | 3.57%   |
| IMC Networks                           | 2         | 3.57%   |
| Apple                                  | 2         | 3.57%   |
| Valve Software                         | 1         | 1.79%   |
| Sony Ericsson Mobile Communications AB | 1         | 1.79%   |
| Ricoh                                  | 1         | 1.79%   |
| Realtek Semiconductor                  | 1         | 1.79%   |
| Luxvisions Innotech Limited            | 1         | 1.79%   |
| Lite-On Technology                     | 1         | 1.79%   |
| Generalplus Technology                 | 1         | 1.79%   |
| Alpha Imaging Technology               | 1         | 1.79%   |
| Acer                                   | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated IR Camera                         | 6         | 10.71%  |
| Chicony USB2.0 Camera                                | 5         | 8.93%   |
| Chicony FHD Webcam                                   | 4         | 7.14%   |
| Chicony HD Webcam                                    | 3         | 5.36%   |
| IMC Networks Integrated Camera                       | 2         | 3.57%   |
| Chicony Integrated Camera                            | 2         | 3.57%   |
| Bison HD Webcam                                      | 2         | 3.57%   |
| Bison BisonCam,NB Pro                                | 2         | 3.57%   |
| Apple FaceTime HD Camera                             | 2         | 3.57%   |
| Valve Software 3D Camera                             | 1         | 1.79%   |
| Suyin RGBIR Camera                                   | 1         | 1.79%   |
| Suyin HP TrueVision HD                               | 1         | 1.79%   |
| Sunplus SPCA2281 Web Camera                          | 1         | 1.79%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.79%   |
| Sunplus Asus Webcam                                  | 1         | 1.79%   |
| Sony Ericsson Mobile AB XQ-CC54                      | 1         | 1.79%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 1.79%   |
| Realtek Integrated Webcam                            | 1         | 1.79%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 1.79%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 1.79%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.79%   |
| Microdia Integrated_Webcam_FHD                       | 1         | 1.79%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.79%   |
| Lite-On HP Wide Vision HD Camera                     | 1         | 1.79%   |
| Generalplus WEB CAM                                  | 1         | 1.79%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 1.79%   |
| Chicony USB 2.0 Camera                               | 1         | 1.79%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.79%   |
| Chicony HP Truevision HD                             | 1         | 1.79%   |
| Chicony FJ Camera                                    | 1         | 1.79%   |
| Chicony ACER FHD User Facing                         | 1         | 1.79%   |
| Chicony 1.3M Webcam                                  | 1         | 1.79%   |
| Bison SunplusIT Integrated Camera                    | 1         | 1.79%   |
| Bison Lenovo Integrated Webcam                       | 1         | 1.79%   |
| Bison Lenovo EasyCamera                              | 1         | 1.79%   |
| Alpha Imaging Integrated_Webcam_8M                   | 1         | 1.79%   |
| Acer Lenovo EasyCamera                               | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 7         | 58.33%  |
| Validity Sensors      | 4         | 33.33%  |
| LighTuning Technology | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 66.67%  |
| Alcor Micro | 2         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 49        | 59.76%  |
| 1     | 31        | 37.8%   |
| 3     | 1         | 1.22%   |
| 2     | 1         | 1.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 12        | 32.43%  |
| Multimedia controller | 9         | 24.32%  |
| Chipcard              | 6         | 16.22%  |
| Graphics card         | 5         | 13.51%  |
| Net/wireless          | 3         | 8.11%   |
| Modem                 | 1         | 2.7%    |
| Camera                | 1         | 2.7%    |

