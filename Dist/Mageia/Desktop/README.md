Mageia - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Mageia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | 1589                        | [41dbcb78cb](https://linux-hardware.org/?probe=41dbcb78cb) | Jan 30, 2022 |
| Gigabyte | H81M-DS2                    | [c0328d5402](https://linux-hardware.org/?probe=c0328d5402) | Jan 27, 2022 |
| Lenovo   | ThinkCentre M58e 7491B1G    | [568741947f](https://linux-hardware.org/?probe=568741947f) | Jan 12, 2022 |
| Gigabyte | B450 AORUS M                | [d9856d52b0](https://linux-hardware.org/?probe=d9856d52b0) | Jan 11, 2022 |
| Gigabyte | B450 AORUS M                | [8b8a13f3b4](https://linux-hardware.org/?probe=8b8a13f3b4) | Jan 11, 2022 |
| Gigabyte | B450 AORUS M                | [0fa4a81a77](https://linux-hardware.org/?probe=0fa4a81a77) | Jan 09, 2022 |
| Lenovo   | ThinkCentre M58e 7491B1G    | [a77218c72c](https://linux-hardware.org/?probe=a77218c72c) | Jan 09, 2022 |
| Gigabyte | Z87X-UD5H-CF                | [a1a7854f7a](https://linux-hardware.org/?probe=a1a7854f7a) | Jan 04, 2022 |
| Gigabyte | Z87X-UD5H-CF                | [c44573411d](https://linux-hardware.org/?probe=c44573411d) | Dec 27, 2021 |
| MSI      | MPG X570 GAMING EDGE WIF... | [c1d67915d0](https://linux-hardware.org/?probe=c1d67915d0) | Dec 26, 2021 |
| ASUSTek  | ROG ZENITH EXTREME          | [e3d82aebbe](https://linux-hardware.org/?probe=e3d82aebbe) | Dec 20, 2021 |
| MSI      | MPG X570 GAMING EDGE WIF... | [fdc65fea9d](https://linux-hardware.org/?probe=fdc65fea9d) | Dec 08, 2021 |
| Gigabyte | H81M-S2H                    | [ceefdd4eac](https://linux-hardware.org/?probe=ceefdd4eac) | Dec 06, 2021 |
| Dell     | 0TP412                      | [f759f2084b](https://linux-hardware.org/?probe=f759f2084b) | Nov 22, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [665331e075](https://linux-hardware.org/?probe=665331e075) | Nov 22, 2021 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [3e92c96ac0](https://linux-hardware.org/?probe=3e92c96ac0) | Nov 17, 2021 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [6e13fb31c9](https://linux-hardware.org/?probe=6e13fb31c9) | Oct 17, 2021 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [45d12f532c](https://linux-hardware.org/?probe=45d12f532c) | Oct 01, 2021 |
| Gigabyte | H170-D3H-CF                 | [e18761a6b2](https://linux-hardware.org/?probe=e18761a6b2) | Sep 28, 2021 |
| Gigabyte | H170-D3H-CF                 | [42784959b9](https://linux-hardware.org/?probe=42784959b9) | Sep 28, 2021 |
| Dell     | 0TP412                      | [25b9af915a](https://linux-hardware.org/?probe=25b9af915a) | Sep 09, 2021 |
| MSI      | MAG B460M MORTAR            | [6fa1f56407](https://linux-hardware.org/?probe=6fa1f56407) | Aug 30, 2021 |
| Gigabyte | H81M-S2H                    | [46740d8f33](https://linux-hardware.org/?probe=46740d8f33) | Aug 22, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [31e9013879](https://linux-hardware.org/?probe=31e9013879) | Aug 18, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [809f094941](https://linux-hardware.org/?probe=809f094941) | Aug 17, 2021 |
| Gigabyte | H81M-S2H                    | [894c915ecc](https://linux-hardware.org/?probe=894c915ecc) | Aug 17, 2021 |
| Gigabyte | B450 AORUS PRO WIFI-CF      | [4c28c43c28](https://linux-hardware.org/?probe=4c28c43c28) | Aug 10, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [88ddc09b9e](https://linux-hardware.org/?probe=88ddc09b9e) | Jul 28, 2021 |
| Gigabyte | H81M-S2H                    | [f52713e401](https://linux-hardware.org/?probe=f52713e401) | Jul 28, 2021 |
| Dell     | 0TP412                      | [8788d078a0](https://linux-hardware.org/?probe=8788d078a0) | Jul 19, 2021 |
| ASUSTek  | PRIME X399-A                | [a2b6af1a6a](https://linux-hardware.org/?probe=a2b6af1a6a) | Jul 14, 2021 |
| Gigabyte | Z68XP-UD3P                  | [259e2a4ac0](https://linux-hardware.org/?probe=259e2a4ac0) | Jun 24, 2021 |
| Gigabyte | B450M DS3H-CF               | [1be802a26e](https://linux-hardware.org/?probe=1be802a26e) | Apr 18, 2021 |
| ECS      | IC780M-A2                   | [e3cbd0879b](https://linux-hardware.org/?probe=e3cbd0879b) | Apr 17, 2021 |
| ASUSTek  | Z170-P                      | [1ebcf0ea2c](https://linux-hardware.org/?probe=1ebcf0ea2c) | Apr 16, 2021 |
| ASUSTek  | Z170-P                      | [a95896e05e](https://linux-hardware.org/?probe=a95896e05e) | Apr 16, 2021 |
| Medion   | Z370H4-EM                   | [57435ad8fb](https://linux-hardware.org/?probe=57435ad8fb) | Apr 16, 2021 |
| ASUSTek  | SABERTOOTH P67              | [6d81c9d615](https://linux-hardware.org/?probe=6d81c9d615) | Apr 16, 2021 |
| Gigabyte | H61M-S2PV                   | [dce1091d81](https://linux-hardware.org/?probe=dce1091d81) | Apr 15, 2021 |
| Medion   | Z370H4-EM                   | [b88834e15d](https://linux-hardware.org/?probe=b88834e15d) | Apr 15, 2021 |
| HP       | 212B                        | [697e2f24f0](https://linux-hardware.org/?probe=697e2f24f0) | Apr 03, 2021 |
| Intel    | STL2-bd A28808-302          | [d6b5151873](https://linux-hardware.org/?probe=d6b5151873) | Apr 01, 2021 |
| Gigabyte | B450M DS3H-CF               | [dbb3c1865f](https://linux-hardware.org/?probe=dbb3c1865f) | Mar 29, 2021 |
| HP       | 212B                        | [69f528da9b](https://linux-hardware.org/?probe=69f528da9b) | Mar 28, 2021 |
| ASUSTek  | PRIME A320M-K               | [2b381b3421](https://linux-hardware.org/?probe=2b381b3421) | Mar 24, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [d4570ea6b2](https://linux-hardware.org/?probe=d4570ea6b2) | Mar 12, 2021 |
| ASRock   | M3A UCC                     | [714da9501f](https://linux-hardware.org/?probe=714da9501f) | Feb 19, 2021 |
| HP       | 339A                        | [43e759b593](https://linux-hardware.org/?probe=43e759b593) | Feb 14, 2021 |
| HP       | 339A                        | [39d23c03ca](https://linux-hardware.org/?probe=39d23c03ca) | Feb 13, 2021 |
| Gigabyte | H81M-S2H                    | [f9e5b1d3c6](https://linux-hardware.org/?probe=f9e5b1d3c6) | Feb 08, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [aea262050c](https://linux-hardware.org/?probe=aea262050c) | Feb 04, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [adabf5b11e](https://linux-hardware.org/?probe=adabf5b11e) | Jan 31, 2021 |
| Gigabyte | B450M DS3H-CF               | [a399a43535](https://linux-hardware.org/?probe=a399a43535) | Jan 16, 2021 |
| Gigabyte | H81M-S2H                    | [0b7e0d2152](https://linux-hardware.org/?probe=0b7e0d2152) | Jan 15, 2021 |
| ASUSTek  | Z87-DELUXE                  | [e160eea25a](https://linux-hardware.org/?probe=e160eea25a) | Dec 28, 2020 |
| HP       | 339A                        | [ea7792c224](https://linux-hardware.org/?probe=ea7792c224) | Dec 26, 2020 |
| Gigabyte | Z87X-UD5H-CF                | [932603ce99](https://linux-hardware.org/?probe=932603ce99) | Dec 25, 2020 |
| ASUSTek  | ROG ZENITH EXTREME          | [5fd86e8c94](https://linux-hardware.org/?probe=5fd86e8c94) | Dec 22, 2020 |
| Lenovo   | ThinkServer TS140           | [ec475a7f9a](https://linux-hardware.org/?probe=ec475a7f9a) | Dec 09, 2020 |
| ASRock   | H87M Pro4                   | [12185c0c75](https://linux-hardware.org/?probe=12185c0c75) | Dec 07, 2020 |
| ASRock   | H87M Pro4                   | [747bc56208](https://linux-hardware.org/?probe=747bc56208) | Dec 07, 2020 |
| Gigabyte | F2A88XM-DS2                 | [1b5123770e](https://linux-hardware.org/?probe=1b5123770e) | Dec 06, 2020 |
| Gigabyte | H81M-S2H                    | [3f948a0756](https://linux-hardware.org/?probe=3f948a0756) | Dec 03, 2020 |
| Gigabyte | H81M-S2H                    | [009e2519cb](https://linux-hardware.org/?probe=009e2519cb) | Nov 22, 2020 |
| Gigabyte | GA-78LMT-USB3 R2            | [1aec57de3b](https://linux-hardware.org/?probe=1aec57de3b) | Nov 20, 2020 |
| Gigabyte | H81M-S2H                    | [8f031786c5](https://linux-hardware.org/?probe=8f031786c5) | Nov 16, 2020 |
| Gigabyte | Z87X-UD5H-CF                | [1bdc158142](https://linux-hardware.org/?probe=1bdc158142) | Nov 16, 2020 |
| ASUSTek  | PRIME B360-PLUS             | [dadbc2f1d7](https://linux-hardware.org/?probe=dadbc2f1d7) | Nov 15, 2020 |
| MSI      | MPG X570 GAMING EDGE WIF... | [fb717dc126](https://linux-hardware.org/?probe=fb717dc126) | Nov 05, 2020 |
| Gigabyte | H170-D3H-CF                 | [8220a96972](https://linux-hardware.org/?probe=8220a96972) | Nov 02, 2020 |
| Gigabyte | H81M-S2H                    | [a854973bf5](https://linux-hardware.org/?probe=a854973bf5) | Oct 25, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [e50d2bd553](https://linux-hardware.org/?probe=e50d2bd553) | Oct 18, 2020 |
| ZOTAC    | Unknown                     | [624888f3ab](https://linux-hardware.org/?probe=624888f3ab) | Oct 14, 2020 |
| Gigabyte | H170-D3H-CF                 | [c73f4878af](https://linux-hardware.org/?probe=c73f4878af) | Oct 04, 2020 |
| Gigabyte | H81M-S2H                    | [1a7d01552e](https://linux-hardware.org/?probe=1a7d01552e) | Oct 04, 2020 |
| Lenovo   | ThinkServer TS140           | [87f4eac666](https://linux-hardware.org/?probe=87f4eac666) | Sep 27, 2020 |
| Gigabyte | H81M-S2H                    | [8fa69c952c](https://linux-hardware.org/?probe=8fa69c952c) | Sep 15, 2020 |
| ASRock   | M3A UCC                     | [43182d8754](https://linux-hardware.org/?probe=43182d8754) | Sep 01, 2020 |
| ASRock   | M3A UCC                     | [50908c43f9](https://linux-hardware.org/?probe=50908c43f9) | Sep 01, 2020 |
| Gigabyte | Z87X-UD5H-CF                | [cbab4d3ea3](https://linux-hardware.org/?probe=cbab4d3ea3) | Aug 31, 2020 |
| Gigabyte | H81M-S2H                    | [f6c7b24ad6](https://linux-hardware.org/?probe=f6c7b24ad6) | Aug 31, 2020 |
| Gigabyte | Z87X-UD5H-CF                | [7fd8c75c95](https://linux-hardware.org/?probe=7fd8c75c95) | Aug 19, 2020 |
| Gigabyte | H81M-S2H                    | [14955a6413](https://linux-hardware.org/?probe=14955a6413) | Aug 19, 2020 |
| ASUSTek  | P8H61-M LE                  | [2ca048a380](https://linux-hardware.org/?probe=2ca048a380) | Jun 29, 2020 |
| ASRock   | H81M-VG4 R2.0               | [ed7fe704dd](https://linux-hardware.org/?probe=ed7fe704dd) | May 25, 2020 |
| HP       | 339A                        | [bbd2341205](https://linux-hardware.org/?probe=bbd2341205) | May 09, 2020 |
| HP       | 339A                        | [1334fcea56](https://linux-hardware.org/?probe=1334fcea56) | May 09, 2020 |
| MSI      | B360M MORTAR                | [d2215c28af](https://linux-hardware.org/?probe=d2215c28af) | Apr 26, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [f6e5343aa5](https://linux-hardware.org/?probe=f6e5343aa5) | Mar 31, 2020 |
| ASUSTek  | H170M-PLUS                  | [6dd350fc4a](https://linux-hardware.org/?probe=6dd350fc4a) | Mar 31, 2020 |
| ASUSTek  | PRIME A320M-K               | [cabb3f4266](https://linux-hardware.org/?probe=cabb3f4266) | Mar 29, 2020 |
| Vorke    | V1 Plus                     | [c49c2bb635](https://linux-hardware.org/?probe=c49c2bb635) | Mar 29, 2020 |
| Gigabyte | H81M-S2H                    | [c61a5bbb12](https://linux-hardware.org/?probe=c61a5bbb12) | Mar 05, 2020 |
| ASRock   | X470 Taichi                 | [5125778e67](https://linux-hardware.org/?probe=5125778e67) | Mar 02, 2020 |
| Gigabyte | B85M-D3H                    | [00442cfd17](https://linux-hardware.org/?probe=00442cfd17) | Feb 25, 2020 |
| Gigabyte | Z87X-UD5H-CF                | [71a967abf8](https://linux-hardware.org/?probe=71a967abf8) | Feb 22, 2020 |
| Gigabyte | H81M-S2H                    | [52c3f45c8f](https://linux-hardware.org/?probe=52c3f45c8f) | Feb 22, 2020 |
| ASUSTek  | H170M-PLUS                  | [0ae790ac85](https://linux-hardware.org/?probe=0ae790ac85) | Feb 01, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [506294e8e9](https://linux-hardware.org/?probe=506294e8e9) | Jan 13, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [16e8d236b4](https://linux-hardware.org/?probe=16e8d236b4) | Jan 12, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [7df7d9c296](https://linux-hardware.org/?probe=7df7d9c296) | Dec 20, 2019 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [0c42dfc62c](https://linux-hardware.org/?probe=0c42dfc62c) | Dec 08, 2019 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [2ef79b672c](https://linux-hardware.org/?probe=2ef79b672c) | Nov 15, 2019 |
| ASUSTek  | A55BM-K                     | [d58dbcdd06](https://linux-hardware.org/?probe=d58dbcdd06) | Nov 08, 2019 |
| MSI      | Z97-G43                     | [87e4cd50ce](https://linux-hardware.org/?probe=87e4cd50ce) | Apr 26, 2019 |
| ASRock   | X470 Taichi                 | [14a8808d2b](https://linux-hardware.org/?probe=14a8808d2b) | Apr 26, 2019 |
| Gigabyte | Z68X-UD3H-B3                | [28ea4213cb](https://linux-hardware.org/?probe=28ea4213cb) | Feb 25, 2019 |
| Gigabyte | Z68X-UD3H-B3                | [b9c55f2790](https://linux-hardware.org/?probe=b9c55f2790) | Feb 25, 2019 |
| ASRock   | X470 Taichi                 | [7b6ec43d58](https://linux-hardware.org/?probe=7b6ec43d58) | Jan 08, 2019 |
| ASRock   | X470 Taichi                 | [117cb09799](https://linux-hardware.org/?probe=117cb09799) | Dec 31, 2018 |
| Gigabyte | Z68X-UD3H-B3                | [0a61436f40](https://linux-hardware.org/?probe=0a61436f40) | Feb 15, 2018 |
| ASUSTek  | M5A97 R2.0                  | [304aa59840](https://linux-hardware.org/?probe=304aa59840) | Dec 14, 2017 |
| ASUSTek  | M4A78 PLUS                  | [ed9d8a148d](https://linux-hardware.org/?probe=ed9d8a148d) | Mar 06, 2016 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.7.19-desktop-3.mga7      | 10       | 11.63%  |
| 5.10.27-desktop-1.mga8     | 7        | 8.14%   |
| 5.7.19-desktop-1.mga7      | 4        | 4.65%   |
| 5.5.4-desktop-1.mga7       | 4        | 4.65%   |
| 5.5.9-desktop-1.mga7       | 3        | 3.49%   |
| 5.10.25-desktop-1.mga8     | 3        | 3.49%   |
| 5.10.12-desktop-1.mga7     | 3        | 3.49%   |
| 5.7.14-desktop-1.mga7      | 2        | 2.33%   |
| 5.6.14-desktop-2.mga7      | 2        | 2.33%   |
| 5.3.7-desktop-4.mga7       | 2        | 2.33%   |
| 5.15.11-desktop-3.mga8     | 2        | 2.33%   |
| 5.10.60-desktop-2.mga8     | 2        | 2.33%   |
| 5.10.56-desktop-1.mga8     | 2        | 2.33%   |
| 5.10.52-desktop-1.mga8     | 2        | 2.33%   |
| 5.10.14-desktop-1.mga7     | 2        | 2.33%   |
| 5.9.3-desktop-1.mga8       | 1        | 1.16%   |
| 5.9.1-desktop-1.mga8       | 1        | 1.16%   |
| 5.8.14-desktop-1.mga8      | 1        | 1.16%   |
| 5.6.8-desktop-1.mga7       | 1        | 1.16%   |
| 5.6.6-desktop-1.mga7       | 1        | 1.16%   |
| 5.5.6-desktop-2.mga7       | 1        | 1.16%   |
| 5.5.13-desktop-1.mga7      | 1        | 1.16%   |
| 5.4.8-desktop-1.mga7       | 1        | 1.16%   |
| 5.4.12-desktop-1.mga7      | 1        | 1.16%   |
| 5.3.13-desktop-2.mga7      | 1        | 1.16%   |
| 5.15.6-desktop-2.mga9      | 1        | 1.16%   |
| 5.15.6-desktop-2.mga8      | 1        | 1.16%   |
| 5.15.2-desktop-2.mga9      | 1        | 1.16%   |
| 5.15.16-desktop-1.mga8     | 1        | 1.16%   |
| 5.15.15-desktop-1.mga8     | 1        | 1.16%   |
| 5.15.10-desktop-1.mga9     | 1        | 1.16%   |
| 5.15.10-desktop-1.mga8     | 1        | 1.16%   |
| 5.14.9-desktop-1.mga9      | 1        | 1.16%   |
| 5.14.12-desktop-2.mga9     | 1        | 1.16%   |
| 5.14.10-desktop-1.mga8     | 1        | 1.16%   |
| 5.13.12-desktop-2.mga8     | 1        | 1.16%   |
| 5.12.15-desktop-1.mga8     | 1        | 1.16%   |
| 5.10.8-desktop-2.mga7      | 1        | 1.16%   |
| 5.10.78-desktop-1.mga8     | 1        | 1.16%   |
| 5.10.6-desktop-1.mga7      | 1        | 1.16%   |
| 5.10.48-desktop-1.mga8     | 1        | 1.16%   |
| 5.10.45-desktop-2.mga8     | 1        | 1.16%   |
| 5.10.20-desktop-2.mga7     | 1        | 1.16%   |
| 5.10.2-desktop-1.mga8      | 1        | 1.16%   |
| 5.1.0-desktop-0.rc6.1.mga7 | 1        | 1.16%   |
| 4.9.56-server-1.mga6       | 1        | 1.16%   |
| 4.19.13-desktop-1.mga7     | 1        | 1.16%   |
| 4.14.18-desktop-1.mga6     | 1        | 1.16%   |
| 4.14.106-desktop-1.mga6    | 1        | 1.16%   |
| 4.14.100-desktop-1.mga6    | 1        | 1.16%   |
| 4.1.15-desktop-2.mga5      | 1        | 1.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.7.19   | 11       | 13.25%  |
| 5.10.27  | 7        | 8.43%   |
| 5.5.4    | 4        | 4.82%   |
| 5.5.9    | 3        | 3.61%   |
| 5.10.25  | 3        | 3.61%   |
| 5.10.12  | 3        | 3.61%   |
| 5.7.14   | 2        | 2.41%   |
| 5.6.14   | 2        | 2.41%   |
| 5.3.7    | 2        | 2.41%   |
| 5.15.6   | 2        | 2.41%   |
| 5.15.11  | 2        | 2.41%   |
| 5.15.10  | 2        | 2.41%   |
| 5.10.60  | 2        | 2.41%   |
| 5.10.56  | 2        | 2.41%   |
| 5.10.52  | 2        | 2.41%   |
| 5.10.14  | 2        | 2.41%   |
| 5.9.3    | 1        | 1.2%    |
| 5.9.1    | 1        | 1.2%    |
| 5.8.14   | 1        | 1.2%    |
| 5.6.8    | 1        | 1.2%    |
| 5.6.6    | 1        | 1.2%    |
| 5.5.6    | 1        | 1.2%    |
| 5.5.13   | 1        | 1.2%    |
| 5.4.8    | 1        | 1.2%    |
| 5.4.12   | 1        | 1.2%    |
| 5.3.13   | 1        | 1.2%    |
| 5.15.2   | 1        | 1.2%    |
| 5.15.16  | 1        | 1.2%    |
| 5.15.15  | 1        | 1.2%    |
| 5.14.9   | 1        | 1.2%    |
| 5.14.12  | 1        | 1.2%    |
| 5.14.10  | 1        | 1.2%    |
| 5.13.12  | 1        | 1.2%    |
| 5.12.15  | 1        | 1.2%    |
| 5.10.8   | 1        | 1.2%    |
| 5.10.78  | 1        | 1.2%    |
| 5.10.6   | 1        | 1.2%    |
| 5.10.48  | 1        | 1.2%    |
| 5.10.45  | 1        | 1.2%    |
| 5.10.20  | 1        | 1.2%    |
| 5.10.2   | 1        | 1.2%    |
| 5.1.0    | 1        | 1.2%    |
| 4.9.56   | 1        | 1.2%    |
| 4.19.13  | 1        | 1.2%    |
| 4.14.18  | 1        | 1.2%    |
| 4.14.106 | 1        | 1.2%    |
| 4.14.100 | 1        | 1.2%    |
| 4.1.15   | 1        | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 19       | 27.54%  |
| 5.7     | 11       | 15.94%  |
| 5.5     | 8        | 11.59%  |
| 5.15    | 8        | 11.59%  |
| 5.6     | 4        | 5.8%    |
| 5.14    | 3        | 4.35%   |
| 4.14    | 3        | 4.35%   |
| 5.9     | 2        | 2.9%    |
| 5.4     | 2        | 2.9%    |
| 5.3     | 2        | 2.9%    |
| 5.8     | 1        | 1.45%   |
| 5.13    | 1        | 1.45%   |
| 5.12    | 1        | 1.45%   |
| 5.1     | 1        | 1.45%   |
| 4.9     | 1        | 1.45%   |
| 4.19    | 1        | 1.45%   |
| 4.1     | 1        | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 46       | 97.87%  |
| i686   | 1        | 2.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KDE5          | 17       | 30.91%  |
| KDE           | 16       | 29.09%  |
| Unknown       | 6        | 10.91%  |
| GNOME         | 5        | 9.09%   |
| Cinnamon      | 5        | 9.09%   |
| LXDE          | 3        | 5.45%   |
| LXQt          | 1        | 1.82%   |
| KDE4          | 1        | 1.82%   |
| GNOME Classic | 1        | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 46       | 95.83%  |
| Wayland | 1        | 2.08%   |
| Tty     | 1        | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 47.92%  |
| SDDM    | 20       | 41.67%  |
| LightDM | 2        | 4.17%   |
| XDM     | 1        | 2.08%   |
| TDM     | 1        | 2.08%   |
| GDM     | 1        | 2.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| fr_FR   | 9        | 18.37%  |
| en_US   | 8        | 16.33%  |
| Unknown | 8        | 16.33%  |
| de_DE   | 6        | 12.24%  |
| ru_RU   | 5        | 10.2%   |
| en_GB   | 3        | 6.12%   |
| sv_SE   | 2        | 4.08%   |
| sl_SI   | 1        | 2.04%   |
| pt_BR   | 1        | 2.04%   |
| pl_PL   | 1        | 2.04%   |
| it_IT   | 1        | 2.04%   |
| fr_BE   | 1        | 2.04%   |
| es_AR   | 1        | 2.04%   |
| en_CA   | 1        | 2.04%   |
| cs_CZ   | 1        | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 34       | 70.83%  |
| EFI  | 14       | 29.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 38       | 77.55%  |
| Unknown  | 6        | 12.24%  |
| Xfs      | 3        | 6.12%   |
| Reiserfs | 1        | 2.04%   |
| Btrfs    | 1        | 2.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 19       | 39.58%  |
| GPT     | 18       | 37.5%   |
| MBR     | 11       | 22.92%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 85.11%  |
| Yes       | 7        | 14.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 77.08%  |
| Yes       | 11       | 22.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 14       | 29.79%  |
| Gigabyte Technology | 13       | 27.66%  |
| MSI                 | 4        | 8.51%   |
| ASRock              | 4        | 8.51%   |
| Hewlett-Packard     | 3        | 6.38%   |
| Lenovo              | 2        | 4.26%   |
| Dell                | 2        | 4.26%   |
| ZOTAC               | 1        | 2.13%   |
| Vorke               | 1        | 2.13%   |
| Medion              | 1        | 2.13%   |
| Intel               | 1        | 2.13%   |
| ECS                 | 1        | 2.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Gigabyte Z68X-UD3H-B3               | 2        | 4.26%   |
| Dell Precision WorkStation T3400    | 2        | 4.26%   |
| ASUS SABERTOOTH 990FX R2.0          | 2        | 4.26%   |
| Vorke V1 Plus                       | 1        | 2.13%   |
| MSI MS-7C82                         | 1        | 2.13%   |
| MSI MS-7C37                         | 1        | 2.13%   |
| MSI MS-7B23                         | 1        | 2.13%   |
| MSI MS-7816                         | 1        | 2.13%   |
| Medion MD34161/C708                 | 1        | 2.13%   |
| Lenovo ThinkCentre M58e 7491B1G     | 1        | 2.13%   |
| Lenovo 70A4000HUX ThinkServer TS140 | 1        | 2.13%   |
| Intel STL2                          | 1        | 2.13%   |
| HP Z440 Workstation                 | 1        | 2.13%   |
| HP Z420 Workstation                 | 1        | 2.13%   |
| HP Compaq Pro 6300 SFF              | 1        | 2.13%   |
| Gigabyte Z87X-UD5H                  | 1        | 2.13%   |
| Gigabyte Z68XP-UD3P                 | 1        | 2.13%   |
| Gigabyte H81M-S2H                   | 1        | 2.13%   |
| Gigabyte H81M-DS2                   | 1        | 2.13%   |
| Gigabyte H61M-S2PV                  | 1        | 2.13%   |
| Gigabyte H170-D3H                   | 1        | 2.13%   |
| Gigabyte GA-78LMT-USB3 R2           | 1        | 2.13%   |
| Gigabyte F2A88XM-DS2                | 1        | 2.13%   |
| Gigabyte B85M-D3H                   | 1        | 2.13%   |
| Gigabyte B450M DS3H                 | 1        | 2.13%   |
| Gigabyte B450 AORUS PRO WIFI        | 1        | 2.13%   |
| ECS IC780M-A2                       | 1        | 2.13%   |
| ASUS Z170-P                         | 1        | 2.13%   |
| ASUS SABERTOOTH P67                 | 1        | 2.13%   |
| ASUS ROG ZENITH EXTREME             | 1        | 2.13%   |
| ASUS PRIME X399-A                   | 1        | 2.13%   |
| ASUS PRIME B360-PLUS                | 1        | 2.13%   |
| ASUS PRIME A320M-K                  | 1        | 2.13%   |
| ASUS P8H61-M LE                     | 1        | 2.13%   |
| ASUS M5A97 R2.0                     | 1        | 2.13%   |
| ASUS M4A78 PLUS                     | 1        | 2.13%   |
| ASUS H170M-PLUS                     | 1        | 2.13%   |
| ASUS All Series                     | 1        | 2.13%   |
| ASUS A55BM-K                        | 1        | 2.13%   |
| ASRock X470 Taichi                  | 1        | 2.13%   |
| ASRock M3A UCC                      | 1        | 2.13%   |
| ASRock H87M Pro4                    | 1        | 2.13%   |
| ASRock H81M-VG4 R2.0                | 1        | 2.13%   |
| Unknown                             | 1        | 2.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS SABERTOOTH        | 3        | 6.38%   |
| ASUS PRIME             | 3        | 6.38%   |
| Gigabyte Z68X-UD3H-B3  | 2        | 4.26%   |
| Dell Precision         | 2        | 4.26%   |
| Vorke V1               | 1        | 2.13%   |
| MSI MS-7C82            | 1        | 2.13%   |
| MSI MS-7C37            | 1        | 2.13%   |
| MSI MS-7B23            | 1        | 2.13%   |
| MSI MS-7816            | 1        | 2.13%   |
| Medion MD34161         | 1        | 2.13%   |
| Lenovo ThinkCentre     | 1        | 2.13%   |
| Lenovo 70A4000HUX      | 1        | 2.13%   |
| Intel STL2             | 1        | 2.13%   |
| HP Z440                | 1        | 2.13%   |
| HP Z420                | 1        | 2.13%   |
| HP Compaq              | 1        | 2.13%   |
| Gigabyte Z87X-UD5H     | 1        | 2.13%   |
| Gigabyte Z68XP-UD3P    | 1        | 2.13%   |
| Gigabyte H81M-S2H      | 1        | 2.13%   |
| Gigabyte H81M-DS2      | 1        | 2.13%   |
| Gigabyte H61M-S2PV     | 1        | 2.13%   |
| Gigabyte H170-D3H      | 1        | 2.13%   |
| Gigabyte GA-78LMT-USB3 | 1        | 2.13%   |
| Gigabyte F2A88XM-DS2   | 1        | 2.13%   |
| Gigabyte B85M-D3H      | 1        | 2.13%   |
| Gigabyte B450M         | 1        | 2.13%   |
| Gigabyte B450          | 1        | 2.13%   |
| ECS IC780M-A2          | 1        | 2.13%   |
| ASUS Z170-P            | 1        | 2.13%   |
| ASUS ROG               | 1        | 2.13%   |
| ASUS P8H61-M           | 1        | 2.13%   |
| ASUS M5A97             | 1        | 2.13%   |
| ASUS M4A78             | 1        | 2.13%   |
| ASUS H170M-PLUS        | 1        | 2.13%   |
| ASUS All               | 1        | 2.13%   |
| ASUS A55BM-K           | 1        | 2.13%   |
| ASRock X470            | 1        | 2.13%   |
| ASRock M3A             | 1        | 2.13%   |
| ASRock H87M            | 1        | 2.13%   |
| ASRock H81M-VG4        | 1        | 2.13%   |
| Unknown                | 1        | 2.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 10       | 21.28%  |
| 2018 | 6        | 12.77%  |
| 2012 | 6        | 12.77%  |
| 2017 | 5        | 10.64%  |
| 2015 | 4        | 8.51%   |
| 2014 | 3        | 6.38%   |
| 2011 | 3        | 6.38%   |
| 2009 | 3        | 6.38%   |
| 2019 | 2        | 4.26%   |
| 2008 | 2        | 4.26%   |
| 2020 | 1        | 2.13%   |
| 2010 | 1        | 2.13%   |
| 2002 | 1        | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 47       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 47       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 47       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 16       | 32%     |
| 8.01-16.0   | 10       | 20%     |
| 4.01-8.0    | 8        | 16%     |
| 32.01-64.0  | 8        | 16%     |
| 3.01-4.0    | 3        | 6%      |
| 64.01-256.0 | 3        | 6%      |
| 24.01-32.0  | 2        | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 17       | 27.42%  |
| 1.01-2.0   | 15       | 24.19%  |
| 4.01-8.0   | 13       | 20.97%  |
| 3.01-4.0   | 9        | 14.52%  |
| 8.01-16.0  | 5        | 8.06%   |
| 0.51-1.0   | 2        | 3.23%   |
| 16.01-24.0 | 1        | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 15       | 30%     |
| 3      | 14       | 28%     |
| 1      | 9        | 18%     |
| 5      | 5        | 10%     |
| 4      | 4        | 8%      |
| 8      | 1        | 2%      |
| 7      | 1        | 2%      |
| 6      | 1        | 2%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 51.06%  |
| No        | 23       | 48.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 45       | 95.74%  |
| No        | 2        | 4.26%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 72.92%  |
| Yes       | 13       | 27.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 59.57%  |
| Yes       | 19       | 40.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| France     | 10       | 21.28%  |
| USA        | 8        | 17.02%  |
| Germany    | 6        | 12.77%  |
| UK         | 4        | 8.51%   |
| Ukraine    | 3        | 6.38%   |
| Sweden     | 2        | 4.26%   |
| Russia     | 2        | 4.26%   |
| Canada     | 2        | 4.26%   |
| Slovenia   | 1        | 2.13%   |
| Poland     | 1        | 2.13%   |
| Luxembourg | 1        | 2.13%   |
| Kenya      | 1        | 2.13%   |
| Greece     | 1        | 2.13%   |
| Czechia    | 1        | 2.13%   |
| Brazil     | 1        | 2.13%   |
| Belgium    | 1        | 2.13%   |
| Belarus    | 1        | 2.13%   |
| Argentina  | 1        | 2.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Waterloo                   | 3        | 4.69%   |
| Mala Danylivka             | 3        | 4.69%   |
| Kharkiv                    | 3        | 4.69%   |
| Paris                      | 2        | 3.13%   |
| Oakland                    | 2        | 3.13%   |
| Kingston upon Thames       | 2        | 3.13%   |
| Grants Pass                | 2        | 3.13%   |
| Cologne                    | 2        | 3.13%   |
| Basingstoke                | 2        | 3.13%   |
| Yakutsk                    | 1        | 1.56%   |
| Werl                       | 1        | 1.56%   |
| Voronezh                   | 1        | 1.56%   |
| Volos                      | 1        | 1.56%   |
| Tresserve                  | 1        | 1.56%   |
| Teddington                 | 1        | 1.56%   |
| Strasbourg                 | 1        | 1.56%   |
| Sternberk                  | 1        | 1.56%   |
| Sartrouville               | 1        | 1.56%   |
| Sainte-Genevi??ve-des-Bois | 1        | 1.56%   |
| Saint-Michel-sur-Orge      | 1        | 1.56%   |
| Rio de Janeiro             | 1        | 1.56%   |
| Penmarch                   | 1        | 1.56%   |
| Palermo                    | 1        | 1.56%   |
| Nova Vodolaha              | 1        | 1.56%   |
| Nova Gorica                | 1        | 1.56%   |
| Nairobi                    | 1        | 1.56%   |
| Munich                     | 1        | 1.56%   |
| Mannheim                   | 1        | 1.56%   |
| Luxembourg                 | 1        | 1.56%   |
| Liège                     | 1        | 1.56%   |
| Kehychivka                 | 1        | 1.56%   |
| Kalisz                     | 1        | 1.56%   |
| Jena                       | 1        | 1.56%   |
| Huty                       | 1        | 1.56%   |
| Helsingborg                | 1        | 1.56%   |
| Hammersmith                | 1        | 1.56%   |
| Frankfurt am Main          | 1        | 1.56%   |
| Fort Bragg                 | 1        | 1.56%   |
| Farnborough                | 1        | 1.56%   |
| Erlangen                   | 1        | 1.56%   |
| Edinburgh                  | 1        | 1.56%   |
| Draveil                    | 1        | 1.56%   |
| Delta                      | 1        | 1.56%   |
| Concarneau                 | 1        | 1.56%   |
| Colindale                  | 1        | 1.56%   |
| Beurlay                    | 1        | 1.56%   |
| Berlezh                    | 1        | 1.56%   |
| Bamberg                    | 1        | 1.56%   |
| Arlington                  | 1        | 1.56%   |
| Arboga                     | 1        | 1.56%   |
| Angers                     | 1        | 1.56%   |
| Aix-les-Bains              | 1        | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 32       | 139    | 28.07%  |
| Seagate             | 18       | 30     | 15.79%  |
| Samsung Electronics | 13       | 16     | 11.4%   |
| Kingston            | 8        | 14     | 7.02%   |
| Sandisk             | 7        | 13     | 6.14%   |
| Toshiba             | 6        | 13     | 5.26%   |
| Hitachi             | 5        | 5      | 4.39%   |
| PNY                 | 3        | 4      | 2.63%   |
| HGST                | 3        | 3      | 2.63%   |
| Unknown             | 2        | 2      | 1.75%   |
| OCZ-VERTEX          | 2        | 2      | 1.75%   |
| OCZ                 | 2        | 2      | 1.75%   |
| Intel               | 2        | 2      | 1.75%   |
| Crucial             | 2        | 6      | 1.75%   |
| XPG                 | 1        | 4      | 0.88%   |
| Verbatim            | 1        | 1      | 0.88%   |
| Transcend           | 1        | 1      | 0.88%   |
| Team                | 1        | 1      | 0.88%   |
| SK Hynix            | 1        | 1      | 0.88%   |
| HUAWEI              | 1        | 1      | 0.88%   |
| FORESEE             | 1        | 1      | 0.88%   |
| Asmedia             | 1        | 1      | 0.88%   |
| A-DATA Technology   | 1        | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD2500BEVT-22ZCT0 250GB      | 3        | 2.26%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 2.26%   |
| Samsung SSD 860 EVO 250GB        | 3        | 2.26%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 2        | 1.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 1.5%    |
| WDC WD30EZRZ-00Z5HB0 3TB         | 2        | 1.5%    |
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 1.5%    |
| WDC WD10EZRZ-00HTKB0 1TB         | 2        | 1.5%    |
| WDC WD10EFRX-68PJCN0 1TB         | 2        | 1.5%    |
| Toshiba HDWD120 2TB              | 2        | 1.5%    |
| Seagate ST3500418AS 500GB        | 2        | 1.5%    |
| Seagate ST32000644NS 2TB         | 2        | 1.5%    |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 1.5%    |
| SanDisk SDSSDA120G 120GB         | 2        | 1.5%    |
| SanDisk Extreme SSD 500GB        | 2        | 1.5%    |
| Samsung SSD 860 EVO 500GB        | 2        | 1.5%    |
| Samsung SSD 850 EVO 500GB        | 2        | 1.5%    |
| OCZ-VERTEX PLUS R2 128GB SSD     | 2        | 1.5%    |
| Kingston SV300S37A240G 240GB SSD | 2        | 1.5%    |
| Kingston SA400S37120G 120GB SSD  | 2        | 1.5%    |
| Intel SSDSC2CW120A3 120GB        | 2        | 1.5%    |
| Hitachi HDS722020ALA330 2TB      | 2        | 1.5%    |
| HGST HUS726040ALE611 4TB         | 2        | 1.5%    |
| XPG NVMe SSD Drive 2TB           | 1        | 0.75%   |
| XPG NVMe SSD Drive 1024GB        | 1        | 0.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.75%   |
| WDC WDS100T2B0A 1TB SSD          | 1        | 0.75%   |
| WDC WD800BB-00JHC0 80GB          | 1        | 0.75%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.75%   |
| WDC WD5000AADS-00S9B0 500GB      | 1        | 0.75%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.75%   |
| WDC WD4000FYYZ-01UL1B2 4TB       | 1        | 0.75%   |
| WDC WD3200KS-00PFB0 320GB        | 1        | 0.75%   |
| WDC WD3200AAJS-00B4A0 320GB      | 1        | 0.75%   |
| WDC WD30PURX-64P6ZY0 3TB         | 1        | 0.75%   |
| WDC WD30EZRX-00DC0B0 3TB         | 1        | 0.75%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1        | 0.75%   |
| WDC WD3000GLFS-01F8U0 304GB      | 1        | 0.75%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.75%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.75%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.75%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 1        | 0.75%   |
| WDC WD141KRYZ-01C66B0 14TB       | 1        | 0.75%   |
| WDC WD10SPZX-00Z10T0 1TB         | 1        | 0.75%   |
| WDC WD10JPVX-60JC3T0 1TB         | 1        | 0.75%   |
| WDC WD10EZRX-00L4HB0 1TB         | 1        | 0.75%   |
| WDC WD10EZRX-00A8LB0 1TB         | 1        | 0.75%   |
| WDC WD10EZEX-22MFCA0 1TB         | 1        | 0.75%   |
| WDC WD10EARS-00Y5B1 1TB          | 1        | 0.75%   |
| WDC WD10EARS-00MVWB0 1TB         | 1        | 0.75%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 0.75%   |
| Verbatim USB External SSD 256GB  | 1        | 0.75%   |
| Unknown SD/MMC/MS PRO 128GB      | 1        | 0.75%   |
| Unknown L200 Hard drive 2TB      | 1        | 0.75%   |
| Transcend TS512GSSD370 512GB     | 1        | 0.75%   |
| Toshiba HDWD110 1TB              | 1        | 0.75%   |
| Toshiba DT01ACA300 3TB           | 1        | 0.75%   |
| Toshiba DT01ACA100 1TB           | 1        | 0.75%   |
| Toshiba DT01ABA300 3TB           | 1        | 0.75%   |
| Team T253X1240G 240GB SSD        | 1        | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 123    | 42.19%  |
| Seagate             | 18       | 30     | 28.13%  |
| Toshiba             | 6        | 13     | 9.38%   |
| Hitachi             | 5        | 5      | 7.81%   |
| HGST                | 3        | 3      | 4.69%   |
| Unknown             | 2        | 2      | 3.13%   |
| Samsung Electronics | 2        | 3      | 3.13%   |
| Asmedia             | 1        | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 11     | 22.22%  |
| Kingston            | 7        | 11     | 15.56%  |
| WDC                 | 6        | 16     | 13.33%  |
| SanDisk             | 5        | 7      | 11.11%  |
| PNY                 | 3        | 4      | 6.67%   |
| OCZ-VERTEX          | 2        | 2      | 4.44%   |
| OCZ                 | 2        | 2      | 4.44%   |
| Intel               | 2        | 2      | 4.44%   |
| Crucial             | 2        | 6      | 4.44%   |
| Verbatim            | 1        | 1      | 2.22%   |
| Transcend           | 1        | 1      | 2.22%   |
| Team                | 1        | 1      | 2.22%   |
| SK Hynix            | 1        | 1      | 2.22%   |
| FORESEE             | 1        | 1      | 2.22%   |
| A-DATA Technology   | 1        | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 43       | 180    | 54.43%  |
| SSD     | 30       | 67     | 37.97%  |
| NVMe    | 5        | 15     | 6.33%   |
| Unknown | 1        | 1      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 48       | 233    | 80%     |
| SAS  | 7        | 15     | 11.67%  |
| NVMe | 5        | 15     | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 39       | 82     | 43.82%  |
| 0.51-1.0   | 25       | 96     | 28.09%  |
| 1.01-2.0   | 12       | 18     | 13.48%  |
| 2.01-3.0   | 6        | 42     | 6.74%   |
| 3.01-4.0   | 5        | 7      | 5.62%   |
| 10.01-20.0 | 1        | 1      | 1.12%   |
| 4.01-10.0  | 1        | 1      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 13       | 25.49%  |
| 501-1000       | 13       | 25.49%  |
| 2001-3000      | 7        | 13.73%  |
| 1001-2000      | 6        | 11.76%  |
| 101-250        | 5        | 9.8%    |
| 251-500        | 4        | 7.84%   |
| 51-100         | 2        | 3.92%   |
| Unknown        | 1        | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 10       | 17.54%  |
| 101-250        | 10       | 17.54%  |
| 1001-2000      | 9        | 15.79%  |
| 501-1000       | 8        | 14.04%  |
| More than 3000 | 6        | 10.53%  |
| 51-100         | 6        | 10.53%  |
| 1-20           | 5        | 8.77%   |
| 21-50          | 1        | 1.75%   |
| 2001-3000      | 1        | 1.75%   |
| Unknown        | 1        | 1.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Intel SSDSC2CW120A3 120GB             | 2        | 2      | 20%     |
| WDC WD10EARS-00MVWB0 1TB              | 1        | 1      | 10%     |
| WDC WD1002FAEX-00Z3A0 1TB             | 1        | 1      | 10%     |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1        | 1      | 10%     |
| Seagate ST3500418AS 500GB             | 1        | 1      | 10%     |
| Seagate ST3250410AS 250GB             | 1        | 1      | 10%     |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 10%     |
| OCZ VERTEX3 120GB SSD                 | 1        | 1      | 10%     |
| HGST HTS725050A7E630 500GB            | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 3        | 3      | 33.33%  |
| Intel    | 2        | 2      | 22.22%  |
| WDC      | 1        | 2      | 11.11%  |
| SK Hynix | 1        | 1      | 11.11%  |
| OCZ      | 1        | 1      | 11.11%  |
| HGST     | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 60%     |
| WDC     | 1        | 2      | 20%     |
| HGST    | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 6      | 55.56%  |
| SSD  | 4        | 4      | 44.44%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 25       | 103    | 42.37%  |
| Works    | 25       | 150    | 42.37%  |
| Malfunc  | 9        | 10     | 15.25%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 30       | 45.45%  |
| AMD                         | 16       | 24.24%  |
| Marvell Technology Group    | 7        | 10.61%  |
| ASMedia Technology          | 5        | 7.58%   |
| Sandisk                     | 2        | 3.03%   |
| Samsung Electronics         | 1        | 1.52%   |
| Phison Electronics          | 1        | 1.52%   |
| Kingston Technology Company | 1        | 1.52%   |
| JMicron Technology          | 1        | 1.52%   |
| Broadcom                    | 1        | 1.52%   |
| ADATA Technology            | 1        | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 8.24%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 8.24%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 5.88%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 4        | 4.71%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4        | 4.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 4.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 4.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 4.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 3.53%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.53%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 2.35%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.35%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.35%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2        | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.18%   |
| Phison E7 NVMe Controller                                                               | 1        | 1.18%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 1.18%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 1.18%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 1.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 1.18%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 1.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.18%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 1.18%   |
| Intel C610/X99 series chipset 4-port SATA Controller [IDE mode]                         | 1        | 1.18%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.18%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.18%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.18%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.18%   |
| Broadcom OSB4 IDE Controller                                                            | 1        | 1.18%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 1        | 1.18%   |
| AMD SB600 IDE                                                                           | 1        | 1.18%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.18%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.18%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.18%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 65.57%  |
| IDE  | 12       | 19.67%  |
| NVMe | 5        | 8.2%    |
| RAID | 3        | 4.92%   |
| SAS  | 1        | 1.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 65.96%  |
| AMD    | 16       | 34.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz                | 2        | 4.17%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 2        | 4.17%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 2        | 4.17%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 4.17%   |
| AMD FX-8350 Eight-Core Processor                | 2        | 4.17%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz              | 1        | 2.08%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz             | 1        | 2.08%   |
| Intel Pentium III (Coppermine)                  | 1        | 2.08%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz          | 1        | 2.08%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 1        | 2.08%   |
| Intel Pentium CPU G3450 @ 3.40GHz               | 1        | 2.08%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 2.08%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 2.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 2.08%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1        | 2.08%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 2.08%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1        | 2.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1        | 2.08%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 1        | 2.08%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 2.08%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 1        | 2.08%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1        | 2.08%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1        | 2.08%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1        | 2.08%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 2.08%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 2.08%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1        | 2.08%   |
| Intel Celeron CPU G1830 @ 2.80GHz               | 1        | 2.08%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1        | 2.08%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1        | 2.08%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 2.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 2.08%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 2.08%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1        | 2.08%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 1        | 2.08%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1        | 2.08%   |
| AMD Phenom II X6 1100T Processor                | 1        | 2.08%   |
| AMD Phenom II X4 955 Processor                  | 1        | 2.08%   |
| AMD FX-8120 Eight-Core Processor                | 1        | 2.08%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 2.08%   |
| AMD Athlon II X3 455 Processor                  | 1        | 2.08%   |
| AMD A8-6600K APU with Radeon HD Graphics        | 1        | 2.08%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 9        | 19.15%  |
| Intel Core i5           | 7        | 14.89%  |
| Intel Core i3           | 5        | 10.64%  |
| AMD FX                  | 4        | 8.51%   |
| Intel Xeon              | 2        | 4.26%   |
| Intel Core 2 Duo        | 2        | 4.26%   |
| Intel Celeron           | 2        | 4.26%   |
| AMD Ryzen Threadripper  | 2        | 4.26%   |
| AMD Ryzen 5             | 2        | 4.26%   |
| Intel Pentium III       | 1        | 2.13%   |
| Intel Pentium Gold      | 1        | 2.13%   |
| Intel Pentium Dual-Core | 1        | 2.13%   |
| Intel Pentium           | 1        | 2.13%   |
| AMD Ryzen 9             | 1        | 2.13%   |
| AMD Ryzen 7             | 1        | 2.13%   |
| AMD Ryzen 3             | 1        | 2.13%   |
| AMD Phenom II X6        | 1        | 2.13%   |
| AMD Phenom II X4        | 1        | 2.13%   |
| AMD Athlon II X3        | 1        | 2.13%   |
| AMD A8                  | 1        | 2.13%   |
| AMD A10                 | 1        | 2.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 24       | 50%     |
| 2      | 13       | 27.08%  |
| 6      | 5        | 10.42%  |
| 3      | 2        | 4.17%   |
| 32     | 1        | 2.08%   |
| 16     | 1        | 2.08%   |
| 12     | 1        | 2.08%   |
| 8      | 1        | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 97.87%  |
| 2      | 1        | 2.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 29       | 61.7%   |
| 1      | 18       | 38.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 45       | 91.84%  |
| Unknown        | 3        | 6.12%   |
| 32-bit         | 1        | 2.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 20.75%  |
| 0x306c3    | 7        | 13.21%  |
| 0x206a7    | 5        | 9.43%   |
| 0x1067a    | 3        | 5.66%   |
| 0x306a9    | 2        | 3.77%   |
| 0x0800820d | 2        | 3.77%   |
| 0x06000852 | 2        | 3.77%   |
| 0x010000c8 | 2        | 3.77%   |
| 0xa0653    | 1        | 1.89%   |
| 0x906eb    | 1        | 1.89%   |
| 0x906ea    | 1        | 1.89%   |
| 0x906e9    | 1        | 1.89%   |
| 0x686      | 1        | 1.89%   |
| 0x506c9    | 1        | 1.89%   |
| 0x306f2    | 1        | 1.89%   |
| 0x206d7    | 1        | 1.89%   |
| 0x08701021 | 1        | 1.89%   |
| 0x08701013 | 1        | 1.89%   |
| 0x08108109 | 1        | 1.89%   |
| 0x08108102 | 1        | 1.89%   |
| 0x08101016 | 1        | 1.89%   |
| 0x0800820b | 1        | 1.89%   |
| 0x08001137 | 1        | 1.89%   |
| 0x06003104 | 1        | 1.89%   |
| 0x06001119 | 1        | 1.89%   |
| 0x0600084f | 1        | 1.89%   |
| 0x010000bf | 1        | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 10       | 20.83%  |
| SandyBridge | 6        | 12.5%   |
| KabyLake    | 5        | 10.42%  |
| Zen+        | 4        | 8.33%   |
| Piledriver  | 4        | 8.33%   |
| Penryn      | 3        | 6.25%   |
| K10         | 3        | 6.25%   |
| Zen 2       | 2        | 4.17%   |
| Zen         | 2        | 4.17%   |
| Skylake     | 2        | 4.17%   |
| IvyBridge   | 2        | 4.17%   |
| Steamroller | 1        | 2.08%   |
| P6          | 1        | 2.08%   |
| Goldmont    | 1        | 2.08%   |
| CometLake   | 1        | 2.08%   |
| Bulldozer   | 1        | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 27       | 51.92%  |
| Intel  | 14       | 26.92%  |
| AMD    | 11       | 21.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 7.69%   |
| Nvidia GF108 [GeForce GT 430]                                               | 4        | 7.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 5.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 5.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 5.77%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 3        | 5.77%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 3.85%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 3.85%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 3.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.85%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 2        | 3.85%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.92%   |
| Nvidia NV11 [GeForce2 MX/MX 400]                                            | 1        | 1.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.92%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.92%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.92%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 1.92%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 1.92%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.92%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.92%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.92%   |
| Intel UHD Graphics 620                                                      | 1        | 1.92%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.92%   |
| Intel HD Graphics 630                                                       | 1        | 1.92%   |
| Intel HD Graphics 500                                                       | 1        | 1.92%   |
| AMD Richland [Radeon HD 8570D]                                              | 1        | 1.92%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 1        | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.92%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 1.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 1.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 24       | 50%     |
| 1 x AMD        | 11       | 22.92%  |
| 1 x Intel      | 10       | 20.83%  |
| Intel + Nvidia | 3        | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 26       | 53.06%  |
| Unknown     | 13       | 26.53%  |
| Proprietary | 10       | 20.41%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 12       | 25%     |
| 0.51-1.0   | 11       | 22.92%  |
| Unknown    | 11       | 22.92%  |
| 5.01-6.0   | 3        | 6.25%   |
| 3.01-4.0   | 3        | 6.25%   |
| 0.01-0.5   | 3        | 6.25%   |
| 7.01-8.0   | 2        | 4.17%   |
| 2.01-3.0   | 2        | 4.17%   |
| 8.01-16.0  | 1        | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Ancor Communications | 6        | 10.71%  |
| Samsung Electronics  | 4        | 7.14%   |
| Goldstar             | 4        | 7.14%   |
| Dell                 | 4        | 7.14%   |
| BenQ                 | 4        | 7.14%   |
| AOC                  | 4        | 7.14%   |
| Acer                 | 4        | 7.14%   |
| ViewSonic            | 3        | 5.36%   |
| Sony                 | 3        | 5.36%   |
| SNC                  | 3        | 5.36%   |
| Philips              | 3        | 5.36%   |
| LG Electronics       | 3        | 5.36%   |
| Hewlett-Packard      | 2        | 3.57%   |
| RTK                  | 1        | 1.79%   |
| QBell                | 1        | 1.79%   |
| PKB                  | 1        | 1.79%   |
| ONKYO                | 1        | 1.79%   |
| Medion               | 1        | 1.79%   |
| HannStar             | 1        | 1.79%   |
| Eizo                 | 1        | 1.79%   |
| Compal               | 1        | 1.79%   |
| ASUSTek Computer     | 1        | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 3        | 4.69%   |
| Goldstar 27EA33 GSM59BC 1920x1080 598x337mm 27.0-inch                 | 2        | 3.13%   |
| Ancor Communications PA248 ACI24B1 1920x1200 546x352mm 25.6-inch      | 2        | 3.13%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 2        | 3.13%   |
| ViewSonic VX2409 SERIES VSC6C2E 1920x1080 521x293mm 23.5-inch         | 1        | 1.56%   |
| ViewSonic VA903-3Series VSC701E 1280x1024 376x301mm 19.0-inch         | 1        | 1.56%   |
| ViewSonic LCD Monitor VP2468 Series 3520x1080                         | 1        | 1.56%   |
| Sony TV SNYF301 1920x1080 1600x900mm 72.3-inch                        | 1        | 1.56%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                         | 1        | 1.56%   |
| Sony SDM-X72 SNY1E70 1280x1024 338x270mm 17.0-inch                    | 1        | 1.56%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1        | 1.56%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1        | 1.56%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 890x500mm 40.2-inch | 1        | 1.56%   |
| Samsung Electronics LCD Monitor S24D330 3840x1080                     | 1        | 1.56%   |
| Samsung Electronics LCD Monitor S24D330                               | 1        | 1.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 1.56%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1        | 1.56%   |
| QBell QB.19F-4WLHGB QBL3EC6 1440x900 410x257mm 19.1-inch              | 1        | 1.56%   |
| PKB LCD Monitor Viseo223DX 1920x1080                                  | 1        | 1.56%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch            | 1        | 1.56%   |
| Philips LCD Monitor FTV                                               | 1        | 1.56%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                    | 1        | 1.56%   |
| ONKYO LCD Monitor TX-SR608 5760x2160                                  | 1        | 1.56%   |
| ONKYO LCD Monitor TX-SR608                                            | 1        | 1.56%   |
| ONKYO LCD Monitor AV Receiver 5760x2160                               | 1        | 1.56%   |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                 | 1        | 1.56%   |
| LG Electronics LCD Monitor LG HDR 4K 5760x2160                        | 1        | 1.56%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 1        | 1.56%   |
| LG Electronics LCD Monitor 23MB35 1920x1080                           | 1        | 1.56%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch         | 1        | 1.56%   |
| Hewlett-Packard w22 HWP26AE 1680x1050 473x296mm 22.0-inch             | 1        | 1.56%   |
| Hewlett-Packard LP1965 HWP2693 1280x1024 380x300mm 19.1-inch          | 1        | 1.56%   |
| HannStar HF225 HSP18BB 1920x1080 477x268mm 21.5-inch                  | 1        | 1.56%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 1        | 1.56%   |
| Goldstar 22BK55 GSM5A30 1680x1050 480x300mm 22.3-inch                 | 1        | 1.56%   |
| Eizo EV2436W ENC2384 1920x1200 519x324mm 24.1-inch                    | 1        | 1.56%   |
| Dell P2719H DEL4185 1920x1080 600x340mm 27.2-inch                     | 1        | 1.56%   |
| Dell P2715Q DEL40BF 3840x2160 597x336mm 27.0-inch                     | 1        | 1.56%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                     | 1        | 1.56%   |
| Dell LCD Monitor ST2420L                                              | 1        | 1.56%   |
| Compal TERRA 2450W WOR2450 1920x1080 341x256mm 16.8-inch              | 1        | 1.56%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                    | 1        | 1.56%   |
| BenQ LCD Monitor LCD 4480x1440                                        | 1        | 1.56%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 1        | 1.56%   |
| BenQ G900 BNQ7804 1280x1024 376x301mm 19.0-inch                       | 1        | 1.56%   |
| ASUSTek Computer VG278 AUS27AF 1920x1080 598x336mm 27.0-inch          | 1        | 1.56%   |
| AOC LCD Monitor 2060W 3520x1080                                       | 1        | 1.56%   |
| AOC LCD Monitor 2060W 3200x900                                        | 1        | 1.56%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 1        | 1.56%   |
| AOC 2240w AOC2240 1920x1080 480x270mm 21.7-inch                       | 1        | 1.56%   |
| AOC 2060W AOC2060 1600x900 432x240mm 19.5-inch                        | 1        | 1.56%   |
| Ancor Communications LCD Monitor ASUS VE278 3840x1080                 | 1        | 1.56%   |
| Ancor Communications ASUS VH222 ACI22AB 1920x1080 477x268mm 21.5-inch | 1        | 1.56%   |
| Acer X203H ACR009D 1600x900 443x249mm 20.0-inch                       | 1        | 1.56%   |
| Acer S220HQL ACR0281 1920x1080 477x268mm 21.5-inch                    | 1        | 1.56%   |
| Acer LCD Monitor X203H                                                | 1        | 1.56%   |
| Acer LCD Monitor EK240Y 1920x1080                                     | 1        | 1.56%   |
| Acer LCD Monitor EK240Y                                               | 1        | 1.56%   |
| Acer EK240Y ACR0758 1920x1080 531x299mm 24.0-inch                     | 1        | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 42.86%  |
| Unknown            | 6        | 10.71%  |
| 3840x2160 (4K)     | 5        | 8.93%   |
| 1280x1024 (SXGA)   | 4        | 7.14%   |
| 1920x1200 (WUXGA)  | 3        | 5.36%   |
| 1366x768 (WXGA)    | 3        | 5.36%   |
| 3840x1080          | 2        | 3.57%   |
| 1680x1050 (WSXGA+) | 2        | 3.57%   |
| 1600x900 (HD+)     | 2        | 3.57%   |
| 5760x2160          | 1        | 1.79%   |
| 4480x1440          | 1        | 1.79%   |
| 3520x1080          | 1        | 1.79%   |
| 3200x900           | 1        | 1.79%   |
| 1440x900 (WXGA+)   | 1        | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 9        | 16.98%  |
| Unknown | 9        | 16.98%  |
| 21      | 8        | 15.09%  |
| 24      | 5        | 9.43%   |
| 19      | 5        | 9.43%   |
| 18      | 3        | 5.66%   |
| 46      | 2        | 3.77%   |
| 25      | 2        | 3.77%   |
| 23      | 2        | 3.77%   |
| 22      | 2        | 3.77%   |
| 72      | 1        | 1.89%   |
| 54      | 1        | 1.89%   |
| 42      | 1        | 1.89%   |
| 32      | 1        | 1.89%   |
| 20      | 1        | 1.89%   |
| 17      | 1        | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 32.69%  |
| 401-500     | 15       | 28.85%  |
| Unknown     | 9        | 17.31%  |
| 351-400     | 3        | 5.77%   |
| 1001-1500   | 3        | 5.77%   |
| 701-800     | 1        | 1.92%   |
| 601-700     | 1        | 1.92%   |
| 301-350     | 1        | 1.92%   |
| 1501-2000   | 1        | 1.92%   |
| 901-1000    | 1        | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 29       | 59.18%  |
| Unknown | 9        | 18.37%  |
| 16/10   | 7        | 14.29%  |
| 5/4     | 4        | 8.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 21.57%  |
| 301-350        | 9        | 17.65%  |
| Unknown        | 9        | 17.65%  |
| 151-200        | 8        | 15.69%  |
| 251-300        | 4        | 7.84%   |
| 141-150        | 4        | 7.84%   |
| 501-1000       | 3        | 5.88%   |
| More than 1000 | 2        | 3.92%   |
| 351-500        | 1        | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 26       | 52%     |
| Unknown | 9        | 18%     |
| 101-120 | 8        | 16%     |
| 1-50    | 4        | 8%      |
| 161-240 | 2        | 4%      |
| 121-160 | 1        | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 68.75%  |
| 2     | 15       | 31.25%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 27       | 41.54%  |
| Intel                    | 26       | 40%     |
| Broadcom                 | 3        | 4.62%   |
| Qualcomm Atheros         | 2        | 3.08%   |
| Wilocity                 | 1        | 1.54%   |
| Ultimarc                 | 1        | 1.54%   |
| MediaTek                 | 1        | 1.54%   |
| Marvell Technology Group | 1        | 1.54%   |
| Huawei Technologies      | 1        | 1.54%   |
| D-Link System            | 1        | 1.54%   |
| Aquantia                 | 1        | 1.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24       | 31.58%  |
| Intel I211 Gigabit Network Connection                             | 4        | 5.26%   |
| Intel Wireless 3165                                               | 3        | 3.95%   |
| Intel Ethernet Connection I217-V                                  | 3        | 3.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 3.95%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 2        | 2.63%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2        | 2.63%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2        | 2.63%   |
| Intel Wireless 7265                                               | 2        | 2.63%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.63%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 2.63%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 2.63%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1        | 1.32%   |
| Ultimarc A-PAC Arcade Control Interface                           | 1        | 1.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 1.32%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 1.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.32%   |
| MediaTek WiFi                                                     | 1        | 1.32%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 1.32%   |
| Intel Wireless 8260                                               | 1        | 1.32%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.32%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.32%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.32%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.32%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.32%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.32%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 1.32%   |
| Huawei Mass Storage                                               | 1        | 1.32%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.32%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 1.32%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 55.56%  |
| Realtek Semiconductor | 4        | 22.22%  |
| Wilocity              | 1        | 5.56%   |
| Qualcomm Atheros      | 1        | 5.56%   |
| MediaTek              | 1        | 5.56%   |
| Broadcom              | 1        | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                        | 3        | 13.64%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 3        | 13.64%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 2        | 9.09%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 2        | 9.09%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 2        | 9.09%   |
| Intel Wireless 7265                                        | 2        | 9.09%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 1        | 4.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1        | 4.55%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                     | 1        | 4.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1        | 4.55%   |
| MediaTek WiFi                                              | 1        | 4.55%   |
| Intel Wireless 8260                                        | 1        | 4.55%   |
| Intel Wi-Fi 6 AX200                                        | 1        | 4.55%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 26       | 52%     |
| Intel                    | 18       | 36%     |
| Broadcom                 | 2        | 4%      |
| Qualcomm Atheros         | 1        | 2%      |
| Marvell Technology Group | 1        | 2%      |
| D-Link System            | 1        | 2%      |
| Aquantia                 | 1        | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24       | 46.15%  |
| Intel I211 Gigabit Network Connection                             | 4        | 7.69%   |
| Intel Ethernet Connection I217-V                                  | 3        | 5.77%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.85%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 3.85%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 3.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.92%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 1.92%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.92%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.92%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.92%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.92%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.92%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 1.92%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.92%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 45       | 73.77%  |
| WiFi     | 14       | 22.95%  |
| Modem    | 1        | 1.64%   |
| Unknown  | 1        | 1.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 41       | 77.36%  |
| WiFi     | 11       | 20.75%  |
| Unknown  | 1        | 1.89%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 66.67%  |
| 2     | 11       | 21.57%  |
| 3     | 4        | 7.84%   |
| 4     | 1        | 1.96%   |
| 0     | 1        | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 44       | 91.67%  |
| Yes  | 4        | 8.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 45.45%  |
| Cambridge Silicon Radio | 6        | 27.27%  |
| ASUSTek Computer        | 3        | 13.64%  |
| Broadcom                | 2        | 9.09%   |
| Realtek Semiconductor   | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth Device                              | 6        | 27.27%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 27.27%  |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 13.64%  |
| Realtek Bluetooth Radio                             | 1        | 4.55%   |
| Intel Bluetooth wireless interface                  | 1        | 4.55%   |
| Broadcom Bluetooth dongle                           | 1        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.55%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4.55%   |
| ASUS Bluetooth Device                               | 1        | 4.55%   |
| ASUS BCM20702A0                                     | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 30       | 35.29%  |
| Nvidia                     | 26       | 30.59%  |
| AMD                        | 18       | 21.18%  |
| C-Media Electronics        | 5        | 5.88%   |
| Samsung Electronics        | 1        | 1.18%   |
| Mackie Designs             | 1        | 1.18%   |
| Logitech                   | 1        | 1.18%   |
| Corsair                    | 1        | 1.18%   |
| BEHRINGER International    | 1        | 1.18%   |
| Altec Lansing Technologies | 1        | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 8.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 6.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 4.26%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 4.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 4.26%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 4        | 4.26%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 3.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 3.19%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 3.19%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 3        | 3.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.19%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 2.13%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 2.13%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 2.13%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 2.13%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 2        | 2.13%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.13%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.13%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 2        | 2.13%   |
| Samsung Electronics USB C Earphones                                        | 1        | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.06%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 1.06%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.06%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.06%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 1.06%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 1.06%   |
| Mackie Designs ProFX                                                       | 1        | 1.06%   |
| Logitech Headset H340                                                      | 1        | 1.06%   |
| Intel USB PnP Sound Device                                                 | 1        | 1.06%   |
| Intel Sunrise Point-LP HD Audio                                            | 1        | 1.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.06%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 1.06%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.06%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 1.06%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.06%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.06%   |
| Corsair Corsair ST100 Headset Output                                      | 1        | 1.06%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 1.06%   |
| BEHRINGER International UMC404HD 192k                                      | 1        | 1.06%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 1.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.06%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.06%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.06%   |
| Altec Lansing Technologies ADA-305 Speakers                                | 1        | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 8        | 27.59%  |
| G.Skill             | 6        | 20.69%  |
| Unknown             | 4        | 13.79%  |
| Team                | 2        | 6.9%    |
| Samsung Electronics | 2        | 6.9%    |
| Corsair             | 2        | 6.9%    |
| Unknown (ABCD)      | 1        | 3.45%   |
| Nanya Technology    | 1        | 3.45%   |
| Micron Technology   | 1        | 3.45%   |
| GOODRAM             | 1        | 3.45%   |
| Crucial             | 1        | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s            | 2        | 6.45%   |
| G.Skill RAM F3-12800CL9-4GBXM 4096MB DIMM DDR3 1600MT/s        | 2        | 6.45%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                         | 1        | 3.23%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1        | 3.23%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                   | 1        | 3.23%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 3.23%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                         | 1        | 3.23%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 1        | 3.23%   |
| Team RAM Elite-16 8GB DIMM DDR3 1600MT/s                       | 1        | 3.23%   |
| Team RAM Elite-1333 2GB DIMM DDR3 1333MT/s                     | 1        | 3.23%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 2667MT/s           | 1        | 3.23%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 1        | 3.23%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4096MB DIMM DDR3 1600MT/s          | 1        | 3.23%   |
| Micron RAM 18JSF51272AZ-1G6M 4GB DIMM DDR3 1600MT/s            | 1        | 3.23%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s              | 1        | 3.23%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 1        | 3.23%   |
| Kingston RAM KHX2133C11D3/8GX 8192MB DIMM DDR3 2133MT/s        | 1        | 3.23%   |
| Kingston RAM KHX1600C9D3/8G 8192MB DIMM DDR3 1600MT/s          | 1        | 3.23%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1867MT/s         | 1        | 3.23%   |
| Kingston RAM 99U5584-009.A00LF 4GB DIMM 1600MT/s               | 1        | 3.23%   |
| Kingston RAM 9905624-054.A00G 8GB SODIMM DDR4 2400MT/s         | 1        | 3.23%   |
| GOODRAM RAM GY1600D364L10/8G 8192MB DIMM DDR3 1600MT/s         | 1        | 3.23%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s          | 1        | 3.23%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s             | 1        | 3.23%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 1        | 3.23%   |
| G.Skill RAM F4-2133C15-8GNT 8GB DIMM DDR4 2133MT/s             | 1        | 3.23%   |
| Crucial RAM CT51264BA1339.D16F 4096MB DIMM DDR3 1333MT/s       | 1        | 3.23%   |
| Corsair RAM CMZ32GX3M4A1600C9 8GB DIMM DDR3 1600MT/s           | 1        | 3.23%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s        | 1        | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 13       | 48.15%  |
| DDR4    | 10       | 37.04%  |
| Unknown | 2        | 7.41%   |
| LPDDR4  | 1        | 3.7%    |
| DDR2    | 1        | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 26       | 96.3%   |
| SODIMM | 1        | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 15       | 50%     |
| 4096  | 8        | 26.67%  |
| 16384 | 4        | 13.33%  |
| 2048  | 3        | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 9        | 31.03%  |
| 3200  | 3        | 10.34%  |
| 2133  | 3        | 10.34%  |
| 1333  | 3        | 10.34%  |
| 3334  | 2        | 6.9%    |
| 2400  | 2        | 6.9%    |
| 3733  | 1        | 3.45%   |
| 3500  | 1        | 3.45%   |
| 2933  | 1        | 3.45%   |
| 2667  | 1        | 3.45%   |
| 1867  | 1        | 3.45%   |
| 800   | 1        | 3.45%   |
| 667   | 1        | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Xerox               | 1        | 20%     |
| Samsung Electronics | 1        | 20%     |
| Hewlett-Packard     | 1        | 20%     |
| Canon               | 1        | 20%     |
| Brother Industries  | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Xerox Phaser 3140 and 3155   | 1        | 20%     |
| Samsung CLP-300 Series       | 1        | 20%     |
| HP OfficeJet 6950            | 1        | 20%     |
| Canon PIXMA MG3600 Series    | 1        | 20%     |
| Brother QL-570 Label Printer | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson Scanner                   | 1        | 50%     |
| Seiko Epson GT-X770 [Perfection V500] | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Microdia    | 3        | 33.33%  |
| Logitech    | 3        | 33.33%  |
| Microsoft   | 2        | 22.22%  |
| Leap Motion | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia Camera               | 2        | 22.22%  |
| Microsoft LifeCam VX-800      | 1        | 11.11%  |
| Microsoft LifeCam HD-3000     | 1        | 11.11%  |
| Microdia Sonix USB 2.0 Camera | 1        | 11.11%  |
| Logitech Webcam C210          | 1        | 11.11%  |
| Logitech Webcam C110          | 1        | 11.11%  |
| Logitech QuickCam Pro 9000    | 1        | 11.11%  |
| Leap Motion Controller        | 1        | 11.11%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Avtor  | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Avtor SecureToken | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 40       | 81.63%  |
| 1     | 8        | 16.33%  |
| 2     | 1        | 2.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 44.44%  |
| Unassigned class         | 1        | 11.11%  |
| Sound                    | 1        | 11.11%  |
| Multimedia controller    | 1        | 11.11%  |
| Communication controller | 1        | 11.11%  |
| Chipcard                 | 1        | 11.11%  |

