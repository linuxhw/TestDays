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

Total: 111

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P50 20EQS42M00     | [f4761a87e1](https://linux-hardware.org/?probe=f4761a87e1) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [4a5e89566c](https://linux-hardware.org/?probe=4a5e89566c) | Nov 05, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [0845a0ec43](https://linux-hardware.org/?probe=0845a0ec43) | Nov 03, 2023 |
| TUXEDO        | Aura 15 Gen2                | [ca743b4e40](https://linux-hardware.org/?probe=ca743b4e40) | Nov 01, 2023 |
| Dell          | Precision 5480              | [0d66f24fe1](https://linux-hardware.org/?probe=0d66f24fe1) | Oct 25, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | [017d43654d](https://linux-hardware.org/?probe=017d43654d) | Oct 22, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [af44d01ae9](https://linux-hardware.org/?probe=af44d01ae9) | Oct 19, 2023 |
| Dell          | Latitude E6540              | [78c4b71781](https://linux-hardware.org/?probe=78c4b71781) | Oct 04, 2023 |
| Dell          | Latitude E6540              | [290b4bd42e](https://linux-hardware.org/?probe=290b4bd42e) | Oct 03, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [886b5140ec](https://linux-hardware.org/?probe=886b5140ec) | Oct 03, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3Y60... | [294e5069a4](https://linux-hardware.org/?probe=294e5069a4) | Oct 01, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3Y60... | [9452219aa3](https://linux-hardware.org/?probe=9452219aa3) | Oct 01, 2023 |
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
| TUXEDO OS 22.04 | 86        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 86        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 6.1.0-1009-tuxedo    | 13        | 13.98%  |
| 6.2.0-10022-tuxedo   | 11        | 11.83%  |
| 6.2.0-10018-tuxedo   | 10        | 10.75%  |
| 6.2.0-10005-tuxedo   | 9         | 9.68%   |
| 6.2.0-10011-tuxedo   | 8         | 8.6%    |
| 6.2.0-10007-tuxedo   | 8         | 8.6%    |
| 6.2.0-10010-tuxedo   | 6         | 6.45%   |
| 6.5.0-10006-tuxedo   | 4         | 4.3%    |
| 5.15.0-10058-tuxedo  | 4         | 4.3%    |
| 5.15.0-10048-tuxedo  | 4         | 4.3%    |
| 6.2.0-10027-tuxedo   | 3         | 3.23%   |
| 5.15.0-10053-tuxedo  | 3         | 3.23%   |
| 5.15.0-10052-tuxedo  | 3         | 3.23%   |
| 5.15.0-10050-tuxedo  | 2         | 2.15%   |
| 6.5.4-060504-generic | 1         | 1.08%   |
| 6.2.0-10014-tuxedo   | 1         | 1.08%   |
| 6.0.0-1010-oem       | 1         | 1.08%   |
| 5.15.0-10057-tuxedo  | 1         | 1.08%   |
| 5.15.0-10056-tuxedo  | 1         | 1.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 56        | 60.22%  |
| 5.15.0  | 18        | 19.35%  |
| 6.1.0   | 13        | 13.98%  |
| 6.5.0   | 4         | 4.3%    |
| 6.5.4   | 1         | 1.08%   |
| 6.0.0   | 1         | 1.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 56        | 60.22%  |
| 5.15    | 18        | 19.35%  |
| 6.1     | 13        | 13.98%  |
| 6.5     | 5         | 5.38%   |
| 6.0     | 1         | 1.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 86        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| KDE5 | 86        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 85        | 97.7%   |
| Wayland | 2         | 2.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 67        | 76.14%  |
| SDDM    | 21        | 23.86%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| de_DE | 39        | 45.35%  |
| en_US | 22        | 25.58%  |
| en_GB | 6         | 6.98%   |
| en_AU | 3         | 3.49%   |
| pl_PL | 2         | 2.33%   |
| nb_NO | 2         | 2.33%   |
| it_IT | 2         | 2.33%   |
| fr_FR | 2         | 2.33%   |
| en_AG | 2         | 2.33%   |
| pt_PT | 1         | 1.16%   |
| pt_BR | 1         | 1.16%   |
| hu_HU | 1         | 1.16%   |
| es_ES | 1         | 1.16%   |
| en_ZA | 1         | 1.16%   |
| en_DK | 1         | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 69        | 79.31%  |
| EFI  | 18        | 20.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 74        | 86.05%  |
| Btrfs   | 6         | 6.98%   |
| Tmpfs   | 4         | 4.65%   |
| Overlay | 2         | 2.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 67        | 76.14%  |
| GPT     | 19        | 21.59%  |
| MBR     | 2         | 2.27%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 95.4%   |
| Yes       | 4         | 4.6%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 81        | 93.1%   |
| Yes       | 6         | 6.9%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| TUXEDO           | 32        | 37.21%  |
| Lenovo           | 14        | 16.28%  |
| Dell             | 11        | 12.79%  |
| Hewlett-Packard  | 9         | 10.47%  |
| ASUSTek Computer | 4         | 4.65%   |
| Apple            | 4         | 4.65%   |
| Notebook         | 2         | 2.33%   |
| MSI              | 2         | 2.33%   |
| Acer             | 2         | 2.33%   |
| Schenker         | 1         | 1.16%   |
| Metabox          | 1         | 1.16%   |
| Fujitsu          | 1         | 1.16%   |
| Chuwi            | 1         | 1.16%   |
| BESSTAR Tech     | 1         | 1.16%   |
| Unknown          | 1         | 1.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| TUXEDO InfinityBook S 15/17 Gen7    | 4         | 4.65%   |
| Unknown                             | 3         | 3.49%   |
| TUXEDO XMG FUSION 15 (XFU15L19)     | 2         | 2.33%   |
| TUXEDO Stellaris/Polaris AMD Gen4   | 2         | 2.33%   |
| TUXEDO Stellaris Intel Gen5         | 2         | 2.33%   |
| TUXEDO Pulse 15 Gen2                | 2         | 2.33%   |
| TUXEDO Pulse 15 Gen1                | 2         | 2.33%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)  | 2         | 2.33%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 2         | 2.33%   |
| TUXEDO InfinityBook Pro 14 Gen6     | 2         | 2.33%   |
| TUXEDO Aura 15 Gen2                 | 2         | 2.33%   |
| Dell Latitude E6540                 | 2         | 2.33%   |
| Apple MacBookPro8,1                 | 2         | 2.33%   |
| TUXEDO Stellaris AMD Gen3 (CZN)     | 1         | 1.16%   |
| TUXEDO Polaris AMD Gen3 (CZN)       | 1         | 1.16%   |
| TUXEDO Polaris 15 AMD Gen1          | 1         | 1.16%   |
| TUXEDO P64_HJ,HK1                   | 1         | 1.16%   |
| TUXEDO N7x0WU                       | 1         | 1.16%   |
| TUXEDO N13xWU                       | 1         | 1.16%   |
| TUXEDO InfinityBook S 15 Gen6       | 1         | 1.16%   |
| TUXEDO Book XUX7 Gen13              | 1         | 1.16%   |
| Schenker VISION 15 E23 (SVS15E23)   | 1         | 1.16%   |
| Notebook W65_W67RB                  | 1         | 1.16%   |
| Notebook NP5x_NP6x_NP7xHP           | 1         | 1.16%   |
| MSI Prestige 15 A10SC               | 1         | 1.16%   |
| MSI GE75 Raider 10SF                | 1         | 1.16%   |
| Metabox Prime-X X170KM              | 1         | 1.16%   |
| Lenovo Yoga S740-15IRH 81NX         | 1         | 1.16%   |
| Lenovo ThinkPad X200 Tablet 7450WN9 | 1         | 1.16%   |
| Lenovo ThinkPad T490s 20NYS3Y600    | 1         | 1.16%   |
| Lenovo ThinkPad T490 20N3SBU219     | 1         | 1.16%   |
| Lenovo ThinkPad P50 20EQS42M00      | 1         | 1.16%   |
| Lenovo ThinkPad P50 20EQS37F00      | 1         | 1.16%   |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700 | 1         | 1.16%   |
| Lenovo ThinkPad E580 20KS003SUS     | 1         | 1.16%   |
| Lenovo ThinkBook 14 G2 ARE 20VF     | 1         | 1.16%   |
| Lenovo Legion 5 15ACH6H 82JU        | 1         | 1.16%   |
| Lenovo IdeaPad Pro 5 14APH8 83AM    | 1         | 1.16%   |
| Lenovo IdeaPad N581 7505            | 1         | 1.16%   |
| Lenovo G580 20150                   | 1         | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 11        | 12.79%  |
| Lenovo ThinkPad     | 7         | 8.14%   |
| TUXEDO Stellaris    | 5         | 5.81%   |
| TUXEDO Pulse        | 4         | 4.65%   |
| Dell Latitude       | 4         | 4.65%   |
| Dell Precision      | 3         | 3.49%   |
| Unknown             | 3         | 3.49%   |
| TUXEDO XMG          | 2         | 2.33%   |
| TUXEDO Polaris      | 2         | 2.33%   |
| TUXEDO Aura         | 2         | 2.33%   |
| Lenovo IdeaPad      | 2         | 2.33%   |
| HP Pavilion         | 2         | 2.33%   |
| HP Laptop           | 2         | 2.33%   |
| HP EliteBook        | 2         | 2.33%   |
| Dell Inspiron       | 2         | 2.33%   |
| Apple MacBookPro8   | 2         | 2.33%   |
| TUXEDO P64          | 1         | 1.16%   |
| TUXEDO N7x0WU       | 1         | 1.16%   |
| TUXEDO N13xWU       | 1         | 1.16%   |
| TUXEDO Book         | 1         | 1.16%   |
| Schenker VISION     | 1         | 1.16%   |
| Notebook W65        | 1         | 1.16%   |
| Notebook NP5x       | 1         | 1.16%   |
| MSI Prestige        | 1         | 1.16%   |
| MSI GE75            | 1         | 1.16%   |
| Metabox Prime-X     | 1         | 1.16%   |
| Lenovo Yoga         | 1         | 1.16%   |
| Lenovo ThinkBook    | 1         | 1.16%   |
| Lenovo Legion       | 1         | 1.16%   |
| Lenovo G580         | 1         | 1.16%   |
| Lenovo G50-80       | 1         | 1.16%   |
| HP ZBook            | 1         | 1.16%   |
| HP OMEN             | 1         | 1.16%   |
| HP Notebook         | 1         | 1.16%   |
| Fujitsu LIFEBOOK    | 1         | 1.16%   |
| Dell Vostro         | 1         | 1.16%   |
| Dell Venue          | 1         | 1.16%   |
| Chuwi MiniBook      | 1         | 1.16%   |
| BESSTAR Tech X400   | 1         | 1.16%   |
| ASUS Zephyrus       | 1         | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 21        | 24.42%  |
| 2020 | 12        | 13.95%  |
| 2019 | 8         | 9.3%    |
| 2015 | 8         | 9.3%    |
| 2023 | 7         | 8.14%   |
| 2021 | 7         | 8.14%   |
| 2012 | 6         | 6.98%   |
| 2017 | 4         | 4.65%   |
| 2011 | 3         | 3.49%   |
| 2018 | 2         | 2.33%   |
| 2014 | 2         | 2.33%   |
| 2013 | 2         | 2.33%   |
| 2008 | 2         | 2.33%   |
| 2010 | 1         | 1.16%   |
| 2009 | 1         | 1.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 86        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 86        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 86        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 21        | 24.42%  |
| 16.01-24.0  | 18        | 20.93%  |
| 8.01-16.0   | 16        | 18.6%   |
| 4.01-8.0    | 13        | 15.12%  |
| 64.01-256.0 | 12        | 13.95%  |
| 3.01-4.0    | 4         | 4.65%   |
| 24.01-32.0  | 2         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 36        | 39.13%  |
| 2.01-3.0   | 18        | 19.57%  |
| 1.01-2.0   | 17        | 18.48%  |
| 3.01-4.0   | 12        | 13.04%  |
| 8.01-16.0  | 6         | 6.52%   |
| 16.01-24.0 | 3         | 3.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 57.47%  |
| 2      | 29        | 33.33%  |
| 3      | 6         | 6.9%    |
| 4      | 1         | 1.15%   |
| 0      | 1         | 1.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 83.72%  |
| Yes       | 14        | 16.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 82.56%  |
| No        | 15        | 17.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 98.84%  |
| No        | 1         | 1.16%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 90.7%   |
| No        | 8         | 9.3%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 44        | 51.16%  |
| USA          | 13        | 15.12%  |
| UK           | 4         | 4.65%   |
| Switzerland  | 3         | 3.49%   |
| Australia    | 3         | 3.49%   |
| Spain        | 2         | 2.33%   |
| Portugal     | 2         | 2.33%   |
| Poland       | 2         | 2.33%   |
| Norway       | 2         | 2.33%   |
| France       | 2         | 2.33%   |
| Austria      | 2         | 2.33%   |
| Turkey       | 1         | 1.16%   |
| South Africa | 1         | 1.16%   |
| Netherlands  | 1         | 1.16%   |
| Denmark      | 1         | 1.16%   |
| Czechia      | 1         | 1.16%   |
| Bulgaria     | 1         | 1.16%   |
| Brazil       | 1         | 1.16%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Munich                 | 6         | 6.9%    |
| Vienna                 | 2         | 2.3%    |
| Schweinfurt            | 2         | 2.3%    |
| Nuremberg              | 2         | 2.3%    |
| Lucerne                | 2         | 2.3%    |
| Langevag               | 2         | 2.3%    |
| Hamburg                | 2         | 2.3%    |
| Brisbane               | 2         | 2.3%    |
| Berlin                 | 2         | 2.3%    |
| Zurich                 | 1         | 1.15%   |
| Zabrze                 | 1         | 1.15%   |
| Wembley                | 1         | 1.15%   |
| Watertown              | 1         | 1.15%   |
| Warsaw                 | 1         | 1.15%   |
| Walsall                | 1         | 1.15%   |
| Venlo                  | 1         | 1.15%   |
| Vallejo                | 1         | 1.15%   |
| Stuttgart              | 1         | 1.15%   |
| Stockstadt am Main     | 1         | 1.15%   |
| Solingen               | 1         | 1.15%   |
| Sistov                 | 1         | 1.15%   |
| Seattle                | 1         | 1.15%   |
| Schwarzenberg          | 1         | 1.15%   |
| Santa Cruz de Tenerife | 1         | 1.15%   |
| San Diego              | 1         | 1.15%   |
| Rio Maior              | 1         | 1.15%   |
| Reno                   | 1         | 1.15%   |
| Rennes                 | 1         | 1.15%   |
| Redcar                 | 1         | 1.15%   |
| Pruem                  | 1         | 1.15%   |
| Prague                 | 1         | 1.15%   |
| Perth                  | 1         | 1.15%   |
| Perrysburg             | 1         | 1.15%   |
| Paris                  | 1         | 1.15%   |
| Paderborn              | 1         | 1.15%   |
| Neuwied                | 1         | 1.15%   |
| Nashville              | 1         | 1.15%   |
| Melton Mowbray         | 1         | 1.15%   |
| Meiningen              | 1         | 1.15%   |
| Mannheim               | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 47        | 65     | 41.96%  |
| Sandisk                     | 11        | 13     | 9.82%   |
| Seagate                     | 7         | 7      | 6.25%   |
| Kingston                    | 7         | 7      | 6.25%   |
| Hitachi                     | 4         | 6      | 3.57%   |
| WDC                         | 3         | 3      | 2.68%   |
| Toshiba                     | 3         | 4      | 2.68%   |
| SK hynix                    | 3         | 4      | 2.68%   |
| Unknown                     | 2         | 2      | 1.79%   |
| SPCC                        | 2         | 2      | 1.79%   |
| Phison Electronics          | 2         | 2      | 1.79%   |
| Micron Technology           | 2         | 2      | 1.79%   |
| Intel                       | 2         | 2      | 1.79%   |
| USB3.0                      | 1         | 1      | 0.89%   |
| Transcend                   | 1         | 1      | 0.89%   |
| Phison                      | 1         | 3      | 0.89%   |
| OWC                         | 1         | 1      | 0.89%   |
| Netac                       | 1         | 1      | 0.89%   |
| Micron/Crucial Technology   | 1         | 1      | 0.89%   |
| LITEONIT                    | 1         | 1      | 0.89%   |
| Lenovo                      | 1         | 1      | 0.89%   |
| KIOXIA                      | 1         | 1      | 0.89%   |
| Kingston Technology Company | 1         | 1      | 0.89%   |
| Kingchuxing                 | 1         | 1      | 0.89%   |
| Intenso                     | 1         | 1      | 0.89%   |
| CT1000BX                    | 1         | 1      | 0.89%   |
| Crucial                     | 1         | 1      | 0.89%   |
| ASMedia                     | 1         | 2      | 0.89%   |
| Apple                       | 1         | 1      | 0.89%   |
| ADATA Technology            | 1         | 1      | 0.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 10        | 8.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 9         | 7.63%   |
| Samsung SSD 980 1TB                                | 6         | 5.08%   |
| Samsung SSD 980 500GB                              | 5         | 4.24%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB  | 3         | 2.54%   |
| Samsung SSD 970 EVO Plus 1TB                       | 3         | 2.54%   |
| Kingston SA400S37240G 240GB SSD                    | 3         | 2.54%   |
| Sandisk WD Blue SN570 1TB                          | 2         | 1.69%   |
| SanDisk SDSSDA240G 240GB                           | 2         | 1.69%   |
| Samsung SSD 980 PRO 500GB                          | 2         | 1.69%   |
| Samsung SSD 980 PRO 1TB                            | 2         | 1.69%   |
| Samsung SSD 850 EVO 1TB                            | 2         | 1.69%   |
| Hitachi HTS727550A9E364 500GB                      | 2         | 1.69%   |
| WDC WD3200BPVT-24JJ5T0 320GB                       | 1         | 0.85%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 0.85%   |
| WDC WD Elements SE SSD 1TB                         | 1         | 0.85%   |
| USB3.0 Super Speed 2TB                             | 1         | 0.85%   |
| Unknown MMC Card  64GB                             | 1         | 0.85%   |
| Unknown MMC Card  2GB                              | 1         | 0.85%   |
| Transcend TS512GSSD230S 512GB                      | 1         | 0.85%   |
| Toshiba XG4 NVMe SSD Controller 256GB              | 1         | 0.85%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 0.85%   |
| Toshiba BG3 NVMe SSD Controller 128GB              | 1         | 0.85%   |
| SPCC M.2 SSD 256GB                                 | 1         | 0.85%   |
| SPCC M.2 PCIe SSD 1TB                              | 1         | 0.85%   |
| SK hynix SKHynix_HFS512GEJ4X112N 512GB             | 1         | 0.85%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB               | 1         | 0.85%   |
| SK hynix SC311 SATA 256GB SSD                      | 1         | 0.85%   |
| Seagate ST500LT012-1DG142 500GB                    | 1         | 0.85%   |
| Seagate ST500LM034-2GH17A 500GB                    | 1         | 0.85%   |
| Seagate ST250LT003-9YG14C 250GB                    | 1         | 0.85%   |
| Seagate ST2000LM015-2E8174 2TB                     | 1         | 0.85%   |
| Seagate ST1000LM048-2E7172 1TB                     | 1         | 0.85%   |
| Seagate Expansion 1TB                              | 1         | 0.85%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB            | 1         | 0.85%   |
| Sandisk WDC PC SN530 SDBPMPZ-512G-1101 512GB       | 1         | 0.85%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1024GB       | 1         | 0.85%   |
| Sandisk WD Black SN850 1TB                         | 1         | 0.85%   |
| Sandisk Ultra 3D NVMe 1TB                          | 1         | 0.85%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                | 1         | 0.85%   |

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
| Samsung Electronics | 9         | 10     | 31.03%  |
| Kingston            | 5         | 5      | 17.24%  |
| SanDisk             | 3         | 3      | 10.34%  |
| WDC                 | 1         | 1      | 3.45%   |
| Transcend           | 1         | 1      | 3.45%   |
| SPCC                | 1         | 1      | 3.45%   |
| SK hynix            | 1         | 2      | 3.45%   |
| OWC                 | 1         | 1      | 3.45%   |
| Netac               | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| LITEONIT            | 1         | 1      | 3.45%   |
| Intenso             | 1         | 1      | 3.45%   |
| CT1000BX            | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 59        | 87     | 57.28%  |
| SSD     | 26        | 31     | 25.24%  |
| HDD     | 14        | 16     | 13.59%  |
| MMC     | 2         | 2      | 1.94%   |
| Unknown | 2         | 3      | 1.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 59        | 87     | 58.42%  |
| SATA | 35        | 44     | 34.65%  |
| SAS  | 5         | 6      | 4.95%   |
| MMC  | 2         | 2      | 1.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 29     | 58.54%  |
| 0.51-1.0   | 15        | 16     | 36.59%  |
| 1.01-2.0   | 2         | 2      | 4.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 24        | 27.59%  |
| 251-500        | 17        | 19.54%  |
| 101-250        | 17        | 19.54%  |
| 1001-2000      | 12        | 13.79%  |
| 1-20           | 6         | 6.9%    |
| 2001-3000      | 4         | 4.6%    |
| More than 3000 | 3         | 3.45%   |
| Unknown        | 2         | 2.3%    |
| 21-50          | 1         | 1.15%   |
| 51-100         | 1         | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 30        | 33.33%  |
| 21-50     | 25        | 27.78%  |
| 101-250   | 13        | 14.44%  |
| 51-100    | 7         | 7.78%   |
| 251-500   | 6         | 6.67%   |
| 501-1000  | 4         | 4.44%   |
| 1001-2000 | 3         | 3.33%   |
| Unknown   | 2         | 2.22%   |

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
| Detected | 66        | 108    | 75%     |
| Works    | 22        | 31     | 25%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 40        | 34.48%  |
| Intel                        | 40        | 34.48%  |
| AMD                          | 11        | 9.48%   |
| SanDisk                      | 8         | 6.9%    |
| Phison Electronics           | 3         | 2.59%   |
| Kingston Technology Company  | 3         | 2.59%   |
| Toshiba America Info Systems | 2         | 1.72%   |
| SK hynix                     | 2         | 1.72%   |
| Silicon Motion               | 1         | 0.86%   |
| Seagate Technology           | 1         | 0.86%   |
| Micron/Crucial Technology    | 1         | 0.86%   |
| Micron Technology            | 1         | 0.86%   |
| Lenovo                       | 1         | 0.86%   |
| KIOXIA                       | 1         | 0.86%   |
| ADATA Technology             | 1         | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 13        | 10.66%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 13        | 10.66%  |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 11        | 9.02%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 10        | 8.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 5.74%   |
| Intel Volume Management Device NVMe RAID Controller                           | 4         | 3.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 4         | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 4         | 3.28%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 3         | 2.46%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 3         | 2.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 2.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 1.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 1.64%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.82%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)           | 1         | 0.82%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 1         | 0.82%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                             | 1         | 0.82%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 0.82%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                     | 1         | 0.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 0.82%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                         | 1         | 0.82%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                         | 1         | 0.82%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 1         | 0.82%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                   | 1         | 0.82%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                           | 1         | 0.82%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1         | 0.82%   |
| Phison E12 NVMe Controller                                                    | 1         | 0.82%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1         | 0.82%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 1         | 0.82%   |
| Lenovo LENSE30256GMSP34MEAT3TA                                                | 1         | 0.82%   |
| KIOXIA NVMe SSD Controller XG8                                                | 1         | 0.82%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                 | 1         | 0.82%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                        | 1         | 0.82%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                        | 1         | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation         | 1         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 59        | 52.21%  |
| SATA | 44        | 38.94%  |
| RAID | 9         | 7.96%   |
| IDE  | 1         | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 75.58%  |
| AMD    | 21        | 24.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H           | 4         | 4.65%   |
| Intel 12th Gen Core i7-1260P            | 4         | 4.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 3.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 3.49%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 3         | 3.49%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 2         | 2.33%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 2         | 2.33%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 2.33%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 2.33%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 2         | 2.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 2.33%   |
| Intel 13th Gen Core i9-13900HX          | 2         | 2.33%   |
| Intel 12th Gen Core i7-1255U            | 2         | 2.33%   |
| Intel 12th Gen Core i5-1240P            | 2         | 2.33%   |
| AMD Ryzen 7 6800H with Radeon Graphics  | 2         | 2.33%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 2.33%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 2.33%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 2         | 2.33%   |
| Intel Xeon W-10855M CPU @ 2.80GHz       | 1         | 1.16%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz    | 1         | 1.16%   |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 1.16%   |
| Intel N100                              | 1         | 1.16%   |
| Intel Core i9-10900KF CPU @ 3.70GHz     | 1         | 1.16%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.16%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 1.16%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.16%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.16%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.16%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.16%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 1.16%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.16%   |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 1.16%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.16%   |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.16%   |
| Intel Core i5-5250U CPU @ 1.60GHz       | 1         | 1.16%   |
| Intel Core i5-4300Y CPU @ 1.60GHz       | 1         | 1.16%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 1         | 1.16%   |
| Intel Core i5 CPU M 540 @ 2.53GHz       | 1         | 1.16%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 24        | 27.91%  |
| Intel Core i7    | 24        | 27.91%  |
| Intel Core i5    | 11        | 12.79%  |
| AMD Ryzen 7      | 10        | 11.63%  |
| AMD Ryzen 5      | 5         | 5.81%   |
| Intel Xeon       | 2         | 2.33%   |
| AMD Ryzen 9      | 2         | 2.33%   |
| Intel Pentium    | 1         | 1.16%   |
| Intel Core i9    | 1         | 1.16%   |
| Intel Core 2 Duo | 1         | 1.16%   |
| Intel Celeron    | 1         | 1.16%   |
| AMD Turion II    | 1         | 1.16%   |
| AMD Ryzen 5 PRO  | 1         | 1.16%   |
| AMD Ryzen 3      | 1         | 1.16%   |
| AMD A8           | 1         | 1.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 28        | 32.56%  |
| 2      | 15        | 17.44%  |
| 8      | 13        | 15.12%  |
| 6      | 13        | 15.12%  |
| 12     | 7         | 8.14%   |
| 14     | 5         | 5.81%   |
| 10     | 3         | 3.49%   |
| 24     | 2         | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 86        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 79        | 91.86%  |
| 1      | 7         | 8.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 86        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 87.5%   |
| 0x906a4    | 2         | 2.27%   |
| 0x906ea    | 1         | 1.14%   |
| 0x906e9    | 1         | 1.14%   |
| 0x906a3    | 1         | 1.14%   |
| 0x806c1    | 1         | 1.14%   |
| 0x306d4    | 1         | 1.14%   |
| 0x0a704101 | 1         | 1.14%   |
| 0x0a50000c | 1         | 1.14%   |
| 0x08608103 | 1         | 1.14%   |
| 0x010000c8 | 1         | 1.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 20        | 23.26%  |
| KabyLake         | 13        | 15.12%  |
| IvyBridge        | 7         | 8.14%   |
| Alderlake Hybrid | 7         | 8.14%   |
| Zen 2            | 6         | 6.98%   |
| CometLake        | 5         | 5.81%   |
| TigerLake        | 4         | 4.65%   |
| SandyBridge      | 4         | 4.65%   |
| Haswell          | 4         | 4.65%   |
| Zen 3            | 3         | 3.49%   |
| Skylake          | 3         | 3.49%   |
| Broadwell        | 3         | 3.49%   |
| Zen+             | 2         | 2.33%   |
| Westmere         | 1         | 1.16%   |
| Puma             | 1         | 1.16%   |
| Penryn           | 1         | 1.16%   |
| K10              | 1         | 1.16%   |
| Gracemont        | 1         | 1.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 50.82%  |
| Nvidia | 34        | 27.87%  |
| AMD    | 26        | 21.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 10        | 8.2%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 5.74%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 6         | 4.92%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 5         | 4.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 5         | 4.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 5         | 4.1%    |
| Intel UHD Graphics 620                                                    | 4         | 3.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 3.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.28%   |
| AMD Lucienne                                                              | 4         | 3.28%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 3         | 2.46%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 3         | 2.46%   |
| AMD Rembrandt [Radeon 680M]                                               | 3         | 2.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.64%   |
| Nvidia GF108M [GeForce GT 635M]                                           | 2         | 1.64%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                           | 2         | 1.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.64%   |
| Intel Raptor Lake-S UHD Graphics                                          | 2         | 1.64%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 2         | 1.64%   |
| Intel HD Graphics 630                                                     | 2         | 1.64%   |
| Intel HD Graphics 5500                                                    | 2         | 1.64%   |
| Intel HD Graphics 530                                                     | 2         | 1.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.64%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 2         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.64%   |
| AMD Mars XTX [Radeon HD 8790M]                                            | 2         | 1.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.64%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                             | 1         | 0.82%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.82%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.82%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 1         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.82%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.82%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 0.82%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.82%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.82%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 0.82%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.82%   |
| Nvidia AD107GLM [RTX 2000 Ada Generation Laptop GPU]                      | 1         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 39.08%  |
| Intel + Nvidia | 22        | 25.29%  |
| 1 x AMD        | 13        | 14.94%  |
| AMD + Nvidia   | 8         | 9.2%    |
| Intel + AMD    | 6         | 6.9%    |
| 1 x Nvidia     | 4         | 4.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 57        | 66.28%  |
| Proprietary | 28        | 32.56%  |
| Unknown     | 1         | 1.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 67.82%  |
| 5.01-6.0   | 10        | 11.49%  |
| 7.01-8.0   | 7         | 8.05%   |
| 3.01-4.0   | 5         | 5.75%   |
| 1.01-2.0   | 3         | 3.45%   |
| 8.01-16.0  | 2         | 2.3%    |
| 0.01-0.5   | 1         | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 31        | 28.97%  |
| AU Optronics        | 16        | 14.95%  |
| Samsung Electronics | 9         | 8.41%   |
| LG Display          | 8         | 7.48%   |
| Chimei Innolux      | 8         | 7.48%   |
| CSO                 | 5         | 4.67%   |
| Apple               | 4         | 3.74%   |
| Goldstar            | 3         | 2.8%    |
| Dell                | 3         | 2.8%    |
| Acer                | 3         | 2.8%    |
| Sharp               | 2         | 1.87%   |
| Lenovo              | 2         | 1.87%   |
| BenQ                | 2         | 1.87%   |
| AOC                 | 2         | 1.87%   |
| Yamaha              | 1         | 0.93%   |
| Sony                | 1         | 0.93%   |
| SGT                 | 1         | 0.93%   |
| RTK                 | 1         | 0.93%   |
| PANDA               | 1         | 0.93%   |
| Iiyama              | 1         | 0.93%   |
| Hewlett-Packard     | 1         | 0.93%   |
| Fujitsu Siemens     | 1         | 0.93%   |
| ASUSTek Computer    | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 5         | 4.55%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 4         | 3.64%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 3.64%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 3         | 2.73%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch        | 2         | 1.82%   |
| BOE LCD Monitor BOE0AF0 2560x1600 344x215mm 16.0-inch                   | 2         | 1.82%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                   | 2         | 1.82%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                   | 2         | 1.82%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                   | 2         | 1.82%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 1.82%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                  | 2         | 1.82%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.91%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                           | 1         | 0.91%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.91%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                 | 1         | 0.91%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 0.91%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 0.91%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch       | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.91%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 0.91%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 1         | 0.91%   |
| RTK Wimaxit FHD RTK5A5B 1920x1080 344x195mm 15.6-inch                   | 1         | 0.91%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.91%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD0545 3200x1800 293x165mm 13.2-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 0.91%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 0.91%   |
| LG Display LCD Monitor LGD0293 1366x768 321x181mm 14.5-inch             | 1         | 0.91%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.91%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                 | 1         | 0.91%   |
| Iiyama PL3466WQ IVM7627 3440x1440 795x334mm 33.9-inch                   | 1         | 0.91%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 46.46%  |
| 1366x768 (WXGA)    | 12        | 12.12%  |
| 2560x1440 (QHD)    | 9         | 9.09%   |
| 3840x2160 (4K)     | 8         | 8.08%   |
| 2880x1800          | 5         | 5.05%   |
| 2560x1600          | 4         | 4.04%   |
| 1280x800 (WXGA)    | 4         | 4.04%   |
| 1920x1200 (WUXGA)  | 3         | 3.03%   |
| 3440x1440          | 1         | 1.01%   |
| 3200x1800 (QHD+)   | 1         | 1.01%   |
| 2240x1400          | 1         | 1.01%   |
| 1920x540           | 1         | 1.01%   |
| 1680x1050 (WSXGA+) | 1         | 1.01%   |
| 1600x900 (HD+)     | 1         | 1.01%   |
| 1440x900 (WXGA+)   | 1         | 1.01%   |
| 1280x1024 (SXGA)   | 1         | 1.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 43        | 39.81%  |
| 14      | 11        | 10.19%  |
| 17      | 9         | 8.33%   |
| 13      | 9         | 8.33%   |
| 16      | 6         | 5.56%   |
| 27      | 5         | 4.63%   |
| 24      | 4         | 3.7%    |
| 12      | 4         | 3.7%    |
| 40      | 2         | 1.85%   |
| 31      | 2         | 1.85%   |
| 22      | 2         | 1.85%   |
| 21      | 2         | 1.85%   |
| 84      | 1         | 0.93%   |
| 60      | 1         | 0.93%   |
| 43      | 1         | 0.93%   |
| 33      | 1         | 0.93%   |
| 23      | 1         | 0.93%   |
| 20      | 1         | 0.93%   |
| 19      | 1         | 0.93%   |
| 18      | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 61        | 57.55%  |
| 351-400     | 11        | 10.38%  |
| 201-300     | 10        | 9.43%   |
| 501-600     | 9         | 8.49%   |
| 401-500     | 6         | 5.66%   |
| 801-900     | 2         | 1.89%   |
| 601-700     | 2         | 1.89%   |
| 701-800     | 1         | 0.94%   |
| 1501-2000   | 1         | 0.94%   |
| 1001-1500   | 1         | 0.94%   |
| 901-1000    | 1         | 0.94%   |
| Unknown     | 1         | 0.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 71        | 75.53%  |
| 16/10 | 19        | 20.21%  |
| 5/4   | 1         | 1.06%   |
| 32/9  | 1         | 1.06%   |
| 3/2   | 1         | 1.06%   |
| 21/9  | 1         | 1.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 43        | 39.81%  |
| 81-90          | 19        | 17.59%  |
| 121-130        | 9         | 8.33%   |
| 111-120        | 6         | 5.56%   |
| 301-350        | 5         | 4.63%   |
| 61-70          | 4         | 3.7%    |
| 201-250        | 4         | 3.7%    |
| 151-200        | 4         | 3.7%    |
| 351-500        | 3         | 2.78%   |
| 251-300        | 3         | 2.78%   |
| 501-1000       | 3         | 2.78%   |
| More than 1000 | 2         | 1.85%   |
| 71-80          | 1         | 0.93%   |
| 141-150        | 1         | 0.93%   |
| Unknown        | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 46        | 43.81%  |
| 101-120       | 21        | 20%     |
| 161-240       | 14        | 13.33%  |
| 51-100        | 13        | 12.38%  |
| More than 240 | 9         | 8.57%   |
| 1-50          | 1         | 0.95%   |
| Unknown       | 1         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 61        | 70.93%  |
| 2     | 21        | 24.42%  |
| 3     | 3         | 3.49%   |
| 0     | 1         | 1.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 67        | 45.58%  |
| Realtek Semiconductor             | 48        | 32.65%  |
| Qualcomm Atheros                  | 7         | 4.76%   |
| Broadcom                          | 5         | 3.4%    |
| Ralink Technology                 | 4         | 2.72%   |
| Huawei Technologies               | 4         | 2.72%   |
| Broadcom Limited                  | 4         | 2.72%   |
| MediaTek                          | 2         | 1.36%   |
| DisplayLink                       | 2         | 1.36%   |
| TP-Link                           | 1         | 0.68%   |
| Ericsson Business Mobile Networks | 1         | 0.68%   |
| Dell                              | 1         | 0.68%   |
| ASIX Electronics                  | 1         | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 20.12%  |
| Intel Wi-Fi 6 AX200                                               | 23        | 13.61%  |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 9         | 5.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 4.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.96%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3         | 1.78%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.78%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                  | 3         | 1.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.18%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.18%   |
| Intel Wireless 8260                                               | 2         | 1.18%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 2         | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.18%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.18%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.18%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 2         | 1.18%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 1.18%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.59%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.59%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.59%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.59%   |
| Intel Wireless-AC 9260                                            | 1         | 0.59%   |
| Intel Wireless 7260                                               | 1         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 64        | 72.73%  |
| Realtek Semiconductor | 5         | 5.68%   |
| Broadcom              | 5         | 5.68%   |
| Ralink Technology     | 4         | 4.55%   |
| Qualcomm Atheros      | 4         | 4.55%   |
| Broadcom Limited      | 3         | 3.41%   |
| MediaTek              | 2         | 2.27%   |
| TP-Link               | 1         | 1.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 23        | 26.14%  |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 9         | 10.23%  |
| Intel Wireless 8265 / 8275                                           | 4         | 4.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 3.41%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 3.41%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 3.41%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 3.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 2.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2         | 2.27%   |
| Intel Wireless 8260                                                  | 2         | 2.27%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 2.27%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 2.27%   |
| Intel 700 Series Chipset Family Wi-Fi                                | 2         | 2.27%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 2.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.14%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 1.14%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 1.14%   |
| Intel Wireless-AC 9260                                               | 1         | 1.14%   |
| Intel Wireless 7260                                                  | 1         | 1.14%   |
| Intel Wireless 3165                                                  | 1         | 1.14%   |
| Intel Wireless 3160                                                  | 1         | 1.14%   |
| Intel Ultimate N WiFi Link 5300                                      | 1         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 1.14%   |
| Intel CNVi: Wi-Fi                                                    | 1         | 1.14%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 1.14%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.14%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 1.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 48        | 64.86%  |
| Intel                 | 16        | 21.62%  |
| Qualcomm Atheros      | 3         | 4.05%   |
| Broadcom              | 3         | 4.05%   |
| DisplayLink           | 2         | 2.7%    |
| Broadcom Limited      | 1         | 1.35%   |
| ASIX Electronics      | 1         | 1.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 45.33%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 9.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 6.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 4%      |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.67%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.67%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.33%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.33%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.33%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.33%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.33%   |
| DisplayLink USB-C Dual-4K Dock                                    | 1         | 1.33%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.33%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 52.47%  |
| Ethernet | 71        | 43.83%  |
| Modem    | 6         | 3.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 71.11%  |
| Ethernet | 26        | 28.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 63        | 73.26%  |
| 1     | 20        | 23.26%  |
| 3     | 2         | 2.33%   |
| 0     | 1         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| Yes  | 45        | 52.33%  |
| No   | 41        | 47.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 75.95%  |
| Realtek Semiconductor           | 4         | 5.06%   |
| Foxconn / Hon Hai               | 4         | 5.06%   |
| Apple                           | 4         | 5.06%   |
| Broadcom                        | 2         | 2.53%   |
| Qualcomm Atheros Communications | 1         | 1.27%   |
| IMC Networks                    | 1         | 1.27%   |
| Dell                            | 1         | 1.27%   |
| Cambridge Silicon Radio         | 1         | 1.27%   |
| ASUSTek Computer                | 1         | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 23        | 29.11%  |
| Intel AX201 Bluetooth                               | 12        | 15.19%  |
| Intel Bluetooth Device                              | 10        | 12.66%  |
| Intel Bluetooth wireless interface                  | 9         | 11.39%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 3.8%    |
| Realtek Bluetooth Radio                             | 2         | 2.53%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.53%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 2.53%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.53%   |
| Apple Bluetooth Host Controller                     | 2         | 2.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.27%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.27%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.27%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.27%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.27%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.27%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.27%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.27%   |
| ASUS ASUS USB-BT500                                 | 1         | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 63        | 53.39%  |
| Nvidia                                 | 27        | 22.88%  |
| AMD                                    | 22        | 18.64%  |
| Sony Ericsson Mobile Communications AB | 1         | 0.85%   |
| Razer USA                              | 1         | 0.85%   |
| Logitech                               | 1         | 0.85%   |
| Lenovo                                 | 1         | 0.85%   |
| Kingston Technology                    | 1         | 0.85%   |
| GN Netcom                              | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 13.77%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 13        | 9.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 5.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 4.35%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 3.62%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 3.62%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 2.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.9%    |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 2.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.17%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 2.17%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.45%   |
| Nvidia Audio device                                                        | 2         | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.45%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.45%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 1.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.45%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.45%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.45%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 2         | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.45%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 0.72%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 1         | 0.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.72%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1         | 0.72%   |
| Lenovo USB Headset                                                         | 1         | 0.72%   |
| Kingston Technology HyperX QuadCast S                                      | 1         | 0.72%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 0.72%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.72%   |
| Intel Alder Lake-N HD Graphics SGPC                                        | 1         | 0.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 41.94%  |
| SK hynix            | 8         | 25.81%  |
| Micron Technology   | 4         | 12.9%   |
| Unknown             | 3         | 9.68%   |
| Team                | 1         | 3.23%   |
| Elpida              | 1         | 3.23%   |
| ASint Technology    | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 9.38%   |
| Unknown                                                          | 3         | 9.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 6.25%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 6.25%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 3.13%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 3.13%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s           | 1         | 3.13%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 3.13%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 3.13%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s              | 1         | 3.13%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 3.13%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 3.13%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 3.13%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.13%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 1         | 3.13%   |
| Micron RAM MT62F1G32D2DS-026 WT 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 3.13%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 1         | 3.13%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 1         | 3.13%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 3.13%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s               | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 15        | 55.56%  |
| LPDDR5 | 5         | 18.52%  |
| DDR3   | 5         | 18.52%  |
| DDR5   | 2         | 7.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 81.48%  |
| Row Of Chips | 5         | 18.52%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 9         | 30%     |
| 32768 | 6         | 20%     |
| 16384 | 6         | 20%     |
| 4096  | 4         | 13.33%  |
| 2048  | 4         | 13.33%  |
| 3072  | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 10        | 34.48%  |
| 6400  | 5         | 17.24%  |
| 1600  | 4         | 13.79%  |
| 2667  | 3         | 10.34%  |
| 8400  | 2         | 6.9%    |
| 5600  | 1         | 3.45%   |
| 4800  | 1         | 3.45%   |
| 2400  | 1         | 3.45%   |
| 2133  | 1         | 3.45%   |
| 1067  | 1         | 3.45%   |

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
| Chicony Electronics           | 35        | 47.3%   |
| Bison Electronics             | 11        | 14.86%  |
| Microdia                      | 6         | 8.11%   |
| IMC Networks                  | 3         | 4.05%   |
| Apple                         | 3         | 4.05%   |
| Suyin                         | 2         | 2.7%    |
| Sunplus Innovation Technology | 2         | 2.7%    |
| Lite-On Technology            | 2         | 2.7%    |
| Unknown                       | 1         | 1.35%   |
| Syntek                        | 1         | 1.35%   |
| Ricoh                         | 1         | 1.35%   |
| Realtek Semiconductor         | 1         | 1.35%   |
| Luxvisions Innotech Limited   | 1         | 1.35%   |
| Logitech                      | 1         | 1.35%   |
| Importek                      | 1         | 1.35%   |
| HYGD-220831-A                 | 1         | 1.35%   |
| Generalplus Technology        | 1         | 1.35%   |
| Alpha Imaging Technology      | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                    | 10        | 13.51%  |
| Chicony FHD Webcam                                   | 7         | 9.46%   |
| Chicony USB2.0 Camera                                | 6         | 8.11%   |
| Bison BisonCam,NB Pro                                | 4         | 5.41%   |
| IMC Networks Integrated Camera                       | 3         | 4.05%   |
| Chicony Integrated Camera                            | 3         | 4.05%   |
| Bison HD Webcam                                      | 3         | 4.05%   |
| Apple FaceTime HD Camera                             | 3         | 4.05%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 2.7%    |
| Microdia Integrated_Webcam_FHD                       | 2         | 2.7%    |
| Bison Lenovo EasyCamera                              | 2         | 2.7%    |
| Unknown HD camera                                    | 1         | 1.35%   |
| Syntek Integrated Camera                             | 1         | 1.35%   |
| Suyin RGBIR Camera                                   | 1         | 1.35%   |
| Suyin HP TrueVision HD                               | 1         | 1.35%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.35%   |
| Sunplus Asus Webcam                                  | 1         | 1.35%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 1.35%   |
| Realtek Integrated Webcam                            | 1         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 1.35%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.35%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.35%   |
| Logitech Brio 500                                    | 1         | 1.35%   |
| Lite-On Integrated Camera                            | 1         | 1.35%   |
| Lite-On HP Webcam                                    | 1         | 1.35%   |
| Importek HP Webcam                                   | 1         | 1.35%   |
| HYGD-220831-A Hy-Usb2.0-1*MIC                        | 1         | 1.35%   |
| Generalplus WEB CAM                                  | 1         | 1.35%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 1.35%   |
| Chicony USB 2.0 Camera                               | 1         | 1.35%   |
| Chicony ThinkPad T490 Webcam                         | 1         | 1.35%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.35%   |
| Chicony HP Truevision HD                             | 1         | 1.35%   |
| Chicony HP HD Camera                                 | 1         | 1.35%   |
| Chicony FJ Camera                                    | 1         | 1.35%   |
| Chicony ACER FHD User Facing                         | 1         | 1.35%   |
| Chicony 1.3M Webcam                                  | 1         | 1.35%   |
| Bison SunplusIT Integrated Camera                    | 1         | 1.35%   |
| Bison Lenovo Integrated Webcam                       | 1         | 1.35%   |
| Alpha Imaging Integrated_Webcam_8M                   | 1         | 1.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 9         | 52.94%  |
| Validity Sensors      | 7         | 41.18%  |
| LighTuning Technology | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 17.65%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 11.76%  |
| Unknown                                                                    | 2         | 11.76%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 5.88%   |
| Validity Sensors VFS491                                                    | 1         | 5.88%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 5.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.88%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 5.88%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 5.88%   |
| Synaptics WBDI                                                             | 1         | 5.88%   |
| Synaptics TouchPad                                                         | 1         | 5.88%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 5.88%   |
| LighTuning Fingerprint Reader                                              | 1         | 5.88%   |

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
| 0     | 47        | 54.65%  |
| 1     | 37        | 43.02%  |
| 3     | 1         | 1.16%   |
| 2     | 1         | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 17        | 39.53%  |
| Multimedia controller | 13        | 30.23%  |
| Chipcard              | 6         | 13.95%  |
| Graphics card         | 4         | 9.3%    |
| Net/wireless          | 2         | 4.65%   |
| Modem                 | 1         | 2.33%   |

