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
| Gigabyte | X570 AORUS ELITE WIFI       | [c11d937631](https://linux-hardware.org/?probe=c11d937631) | Feb 23, 2022 |
| ASRock   | M3A UCC                     | [eaa75fb3f4](https://linux-hardware.org/?probe=eaa75fb3f4) | Feb 20, 2022 |
| ASRock   | M3A UCC                     | [ce306a4c86](https://linux-hardware.org/?probe=ce306a4c86) | Feb 20, 2022 |
| MSI      | B250M BAZOOKA               | [4a8f0501a2](https://linux-hardware.org/?probe=4a8f0501a2) | Feb 11, 2022 |
| ASRock   | G41M-VS3                    | [825356bf6c](https://linux-hardware.org/?probe=825356bf6c) | Feb 02, 2022 |
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
| 5.7.19-desktop-3.mga7      | 10       | 11.11%  |
| 5.10.27-desktop-1.mga8     | 7        | 7.78%   |
| 5.7.19-desktop-1.mga7      | 4        | 4.44%   |
| 5.5.4-desktop-1.mga7       | 4        | 4.44%   |
| 5.5.9-desktop-1.mga7       | 3        | 3.33%   |
| 5.10.25-desktop-1.mga8     | 3        | 3.33%   |
| 5.10.12-desktop-1.mga7     | 3        | 3.33%   |
| 5.7.14-desktop-1.mga7      | 2        | 2.22%   |
| 5.6.14-desktop-2.mga7      | 2        | 2.22%   |
| 5.3.7-desktop-4.mga7       | 2        | 2.22%   |
| 5.15.23-desktop-1.mga8     | 2        | 2.22%   |
| 5.15.16-desktop-1.mga8     | 2        | 2.22%   |
| 5.15.11-desktop-3.mga8     | 2        | 2.22%   |
| 5.10.60-desktop-2.mga8     | 2        | 2.22%   |
| 5.10.56-desktop-1.mga8     | 2        | 2.22%   |
| 5.10.52-desktop-1.mga8     | 2        | 2.22%   |
| 5.10.14-desktop-1.mga7     | 2        | 2.22%   |
| 5.9.3-desktop-1.mga8       | 1        | 1.11%   |
| 5.9.1-desktop-1.mga8       | 1        | 1.11%   |
| 5.8.14-desktop-1.mga8      | 1        | 1.11%   |
| 5.6.8-desktop-1.mga7       | 1        | 1.11%   |
| 5.6.6-desktop-1.mga7       | 1        | 1.11%   |
| 5.5.6-desktop-2.mga7       | 1        | 1.11%   |
| 5.5.13-desktop-1.mga7      | 1        | 1.11%   |
| 5.4.8-desktop-1.mga7       | 1        | 1.11%   |
| 5.4.12-desktop-1.mga7      | 1        | 1.11%   |
| 5.3.13-desktop-2.mga7      | 1        | 1.11%   |
| 5.15.6-desktop-2.mga9      | 1        | 1.11%   |
| 5.15.6-desktop-2.mga8      | 1        | 1.11%   |
| 5.15.2-desktop-2.mga9      | 1        | 1.11%   |
| 5.15.18-desktop-2.mga8     | 1        | 1.11%   |
| 5.15.15-desktop-1.mga8     | 1        | 1.11%   |
| 5.15.10-desktop-1.mga9     | 1        | 1.11%   |
| 5.15.10-desktop-1.mga8     | 1        | 1.11%   |
| 5.14.9-desktop-1.mga9      | 1        | 1.11%   |
| 5.14.12-desktop-2.mga9     | 1        | 1.11%   |
| 5.14.10-desktop-1.mga8     | 1        | 1.11%   |
| 5.13.12-desktop-2.mga8     | 1        | 1.11%   |
| 5.12.15-desktop-1.mga8     | 1        | 1.11%   |
| 5.10.8-desktop-2.mga7      | 1        | 1.11%   |
| 5.10.78-desktop-1.mga8     | 1        | 1.11%   |
| 5.10.6-desktop-1.mga7      | 1        | 1.11%   |
| 5.10.48-desktop-1.mga8     | 1        | 1.11%   |
| 5.10.45-desktop-2.mga8     | 1        | 1.11%   |
| 5.10.20-desktop-2.mga7     | 1        | 1.11%   |
| 5.10.2-desktop-1.mga8      | 1        | 1.11%   |
| 5.1.0-desktop-0.rc6.1.mga7 | 1        | 1.11%   |
| 4.9.56-server-1.mga6       | 1        | 1.11%   |
| 4.19.13-desktop-1.mga7     | 1        | 1.11%   |
| 4.14.18-desktop-1.mga6     | 1        | 1.11%   |
| 4.14.106-desktop-1.mga6    | 1        | 1.11%   |
| 4.14.100-desktop-1.mga6    | 1        | 1.11%   |
| 4.1.15-desktop-2.mga5      | 1        | 1.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.7.19   | 11       | 12.64%  |
| 5.10.27  | 7        | 8.05%   |
| 5.5.4    | 4        | 4.6%    |
| 5.5.9    | 3        | 3.45%   |
| 5.10.25  | 3        | 3.45%   |
| 5.10.12  | 3        | 3.45%   |
| 5.7.14   | 2        | 2.3%    |
| 5.6.14   | 2        | 2.3%    |
| 5.3.7    | 2        | 2.3%    |
| 5.15.6   | 2        | 2.3%    |
| 5.15.23  | 2        | 2.3%    |
| 5.15.16  | 2        | 2.3%    |
| 5.15.11  | 2        | 2.3%    |
| 5.15.10  | 2        | 2.3%    |
| 5.10.60  | 2        | 2.3%    |
| 5.10.56  | 2        | 2.3%    |
| 5.10.52  | 2        | 2.3%    |
| 5.10.14  | 2        | 2.3%    |
| 5.9.3    | 1        | 1.15%   |
| 5.9.1    | 1        | 1.15%   |
| 5.8.14   | 1        | 1.15%   |
| 5.6.8    | 1        | 1.15%   |
| 5.6.6    | 1        | 1.15%   |
| 5.5.6    | 1        | 1.15%   |
| 5.5.13   | 1        | 1.15%   |
| 5.4.8    | 1        | 1.15%   |
| 5.4.12   | 1        | 1.15%   |
| 5.3.13   | 1        | 1.15%   |
| 5.15.2   | 1        | 1.15%   |
| 5.15.18  | 1        | 1.15%   |
| 5.15.15  | 1        | 1.15%   |
| 5.14.9   | 1        | 1.15%   |
| 5.14.12  | 1        | 1.15%   |
| 5.14.10  | 1        | 1.15%   |
| 5.13.12  | 1        | 1.15%   |
| 5.12.15  | 1        | 1.15%   |
| 5.10.8   | 1        | 1.15%   |
| 5.10.78  | 1        | 1.15%   |
| 5.10.6   | 1        | 1.15%   |
| 5.10.48  | 1        | 1.15%   |
| 5.10.45  | 1        | 1.15%   |
| 5.10.20  | 1        | 1.15%   |
| 5.10.2   | 1        | 1.15%   |
| 5.1.0    | 1        | 1.15%   |
| 4.9.56   | 1        | 1.15%   |
| 4.19.13  | 1        | 1.15%   |
| 4.14.18  | 1        | 1.15%   |
| 4.14.106 | 1        | 1.15%   |
| 4.14.100 | 1        | 1.15%   |
| 4.1.15   | 1        | 1.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 19       | 26.03%  |
| 5.15    | 12       | 16.44%  |
| 5.7     | 11       | 15.07%  |
| 5.5     | 8        | 10.96%  |
| 5.6     | 4        | 5.48%   |
| 5.14    | 3        | 4.11%   |
| 4.14    | 3        | 4.11%   |
| 5.9     | 2        | 2.74%   |
| 5.4     | 2        | 2.74%   |
| 5.3     | 2        | 2.74%   |
| 5.8     | 1        | 1.37%   |
| 5.13    | 1        | 1.37%   |
| 5.12    | 1        | 1.37%   |
| 5.1     | 1        | 1.37%   |
| 4.9     | 1        | 1.37%   |
| 4.19    | 1        | 1.37%   |
| 4.1     | 1        | 1.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 49       | 98%     |
| i686   | 1        | 2%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KDE5          | 20       | 33.9%   |
| KDE           | 16       | 27.12%  |
| GNOME         | 6        | 10.17%  |
| Unknown       | 6        | 10.17%  |
| Cinnamon      | 5        | 8.47%   |
| LXDE          | 3        | 5.08%   |
| LXQt          | 1        | 1.69%   |
| KDE4          | 1        | 1.69%   |
| GNOME Classic | 1        | 1.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 49       | 96.08%  |
| Wayland | 1        | 1.96%   |
| Tty     | 1        | 1.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 26       | 50.98%  |
| SDDM    | 20       | 39.22%  |
| LightDM | 2        | 3.92%   |
| XDM     | 1        | 1.96%   |
| TDM     | 1        | 1.96%   |
| GDM     | 1        | 1.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| fr_FR   | 10       | 19.23%  |
| en_US   | 8        | 15.38%  |
| Unknown | 8        | 15.38%  |
| de_DE   | 7        | 13.46%  |
| ru_RU   | 5        | 9.62%   |
| en_GB   | 3        | 5.77%   |
| sv_SE   | 2        | 3.85%   |
| zh_TW   | 1        | 1.92%   |
| sl_SI   | 1        | 1.92%   |
| pt_BR   | 1        | 1.92%   |
| pl_PL   | 1        | 1.92%   |
| it_IT   | 1        | 1.92%   |
| fr_BE   | 1        | 1.92%   |
| es_AR   | 1        | 1.92%   |
| en_CA   | 1        | 1.92%   |
| cs_CZ   | 1        | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 36       | 70.59%  |
| EFI  | 15       | 29.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 39       | 75%     |
| Unknown  | 6        | 11.54%  |
| Xfs      | 4        | 7.69%   |
| Btrfs    | 2        | 3.85%   |
| Reiserfs | 1        | 1.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 41.18%  |
| GPT     | 18       | 35.29%  |
| MBR     | 12       | 23.53%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 86%     |
| Yes       | 7        | 14%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 78.43%  |
| Yes       | 11       | 21.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 14       | 28%     |
| ASUSTek Computer    | 14       | 28%     |
| MSI                 | 5        | 10%     |
| ASRock              | 5        | 10%     |
| Hewlett-Packard     | 3        | 6%      |
| Lenovo              | 2        | 4%      |
| Dell                | 2        | 4%      |
| ZOTAC               | 1        | 2%      |
| Vorke               | 1        | 2%      |
| Medion              | 1        | 2%      |
| Intel               | 1        | 2%      |
| ECS                 | 1        | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Gigabyte Z68X-UD3H-B3               | 2        | 4%      |
| Dell Precision WorkStation T3400    | 2        | 4%      |
| ASUS SABERTOOTH 990FX R2.0          | 2        | 4%      |
| Vorke V1 Plus                       | 1        | 2%      |
| MSI MS-7C82                         | 1        | 2%      |
| MSI MS-7C37                         | 1        | 2%      |
| MSI MS-7B23                         | 1        | 2%      |
| MSI MS-7A70                         | 1        | 2%      |
| MSI MS-7816                         | 1        | 2%      |
| Medion MD34161/C708                 | 1        | 2%      |
| Lenovo ThinkCentre M58e 7491B1G     | 1        | 2%      |
| Lenovo 70A4000HUX ThinkServer TS140 | 1        | 2%      |
| Intel STL2                          | 1        | 2%      |
| HP Z440 Workstation                 | 1        | 2%      |
| HP Z420 Workstation                 | 1        | 2%      |
| HP Compaq Pro 6300 SFF              | 1        | 2%      |
| Gigabyte Z87X-UD5H                  | 1        | 2%      |
| Gigabyte Z68XP-UD3P                 | 1        | 2%      |
| Gigabyte X570 AORUS ELITE WIFI      | 1        | 2%      |
| Gigabyte H81M-S2H                   | 1        | 2%      |
| Gigabyte H81M-DS2                   | 1        | 2%      |
| Gigabyte H61M-S2PV                  | 1        | 2%      |
| Gigabyte H170-D3H                   | 1        | 2%      |
| Gigabyte GA-78LMT-USB3 R2           | 1        | 2%      |
| Gigabyte F2A88XM-DS2                | 1        | 2%      |
| Gigabyte B85M-D3H                   | 1        | 2%      |
| Gigabyte B450M DS3H                 | 1        | 2%      |
| Gigabyte B450 AORUS PRO WIFI        | 1        | 2%      |
| ECS IC780M-A2                       | 1        | 2%      |
| ASUS Z170-P                         | 1        | 2%      |
| ASUS SABERTOOTH P67                 | 1        | 2%      |
| ASUS ROG ZENITH EXTREME             | 1        | 2%      |
| ASUS PRIME X399-A                   | 1        | 2%      |
| ASUS PRIME B360-PLUS                | 1        | 2%      |
| ASUS PRIME A320M-K                  | 1        | 2%      |
| ASUS P8H61-M LE                     | 1        | 2%      |
| ASUS M5A97 R2.0                     | 1        | 2%      |
| ASUS M4A78 PLUS                     | 1        | 2%      |
| ASUS H170M-PLUS                     | 1        | 2%      |
| ASUS All Series                     | 1        | 2%      |
| ASUS A55BM-K                        | 1        | 2%      |
| ASRock X470 Taichi                  | 1        | 2%      |
| ASRock M3A UCC                      | 1        | 2%      |
| ASRock H87M Pro4                    | 1        | 2%      |
| ASRock H81M-VG4 R2.0                | 1        | 2%      |
| ASRock G41M-VS3                     | 1        | 2%      |
| Unknown                             | 1        | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS SABERTOOTH        | 3        | 6%      |
| ASUS PRIME             | 3        | 6%      |
| Gigabyte Z68X-UD3H-B3  | 2        | 4%      |
| Dell Precision         | 2        | 4%      |
| Vorke V1               | 1        | 2%      |
| MSI MS-7C82            | 1        | 2%      |
| MSI MS-7C37            | 1        | 2%      |
| MSI MS-7B23            | 1        | 2%      |
| MSI MS-7A70            | 1        | 2%      |
| MSI MS-7816            | 1        | 2%      |
| Medion MD34161         | 1        | 2%      |
| Lenovo ThinkCentre     | 1        | 2%      |
| Lenovo 70A4000HUX      | 1        | 2%      |
| Intel STL2             | 1        | 2%      |
| HP Z440                | 1        | 2%      |
| HP Z420                | 1        | 2%      |
| HP Compaq              | 1        | 2%      |
| Gigabyte Z87X-UD5H     | 1        | 2%      |
| Gigabyte Z68XP-UD3P    | 1        | 2%      |
| Gigabyte X570          | 1        | 2%      |
| Gigabyte H81M-S2H      | 1        | 2%      |
| Gigabyte H81M-DS2      | 1        | 2%      |
| Gigabyte H61M-S2PV     | 1        | 2%      |
| Gigabyte H170-D3H      | 1        | 2%      |
| Gigabyte GA-78LMT-USB3 | 1        | 2%      |
| Gigabyte F2A88XM-DS2   | 1        | 2%      |
| Gigabyte B85M-D3H      | 1        | 2%      |
| Gigabyte B450M         | 1        | 2%      |
| Gigabyte B450          | 1        | 2%      |
| ECS IC780M-A2          | 1        | 2%      |
| ASUS Z170-P            | 1        | 2%      |
| ASUS ROG               | 1        | 2%      |
| ASUS P8H61-M           | 1        | 2%      |
| ASUS M5A97             | 1        | 2%      |
| ASUS M4A78             | 1        | 2%      |
| ASUS H170M-PLUS        | 1        | 2%      |
| ASUS All               | 1        | 2%      |
| ASUS A55BM-K           | 1        | 2%      |
| ASRock X470            | 1        | 2%      |
| ASRock M3A             | 1        | 2%      |
| ASRock H87M            | 1        | 2%      |
| ASRock H81M-VG4        | 1        | 2%      |
| ASRock G41M-VS3        | 1        | 2%      |
| Unknown                | 1        | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 10       | 20%     |
| 2018 | 6        | 12%     |
| 2012 | 6        | 12%     |
| 2017 | 5        | 10%     |
| 2015 | 4        | 8%      |
| 2019 | 3        | 6%      |
| 2014 | 3        | 6%      |
| 2011 | 3        | 6%      |
| 2009 | 3        | 6%      |
| 2010 | 2        | 4%      |
| 2008 | 2        | 4%      |
| 2020 | 1        | 2%      |
| 2016 | 1        | 2%      |
| 2002 | 1        | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 50       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 50       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 50       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 17       | 32.08%  |
| 8.01-16.0   | 10       | 18.87%  |
| 4.01-8.0    | 8        | 15.09%  |
| 32.01-64.0  | 8        | 15.09%  |
| 3.01-4.0    | 4        | 7.55%   |
| 64.01-256.0 | 4        | 7.55%   |
| 24.01-32.0  | 2        | 3.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 18       | 27.27%  |
| 1.01-2.0   | 16       | 24.24%  |
| 4.01-8.0   | 13       | 19.7%   |
| 3.01-4.0   | 10       | 15.15%  |
| 8.01-16.0  | 6        | 9.09%   |
| 0.51-1.0   | 2        | 3.03%   |
| 16.01-24.0 | 1        | 1.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 15       | 28.3%   |
| 2      | 15       | 28.3%   |
| 1      | 10       | 18.87%  |
| 5      | 5        | 9.43%   |
| 4      | 4        | 7.55%   |
| 6      | 2        | 3.77%   |
| 8      | 1        | 1.89%   |
| 7      | 1        | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 50.98%  |
| Yes       | 25       | 49.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 96%     |
| No        | 2        | 4%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 72.55%  |
| Yes       | 14       | 27.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 58%     |
| Yes       | 21       | 42%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| France     | 11       | 22%     |
| USA        | 8        | 16%     |
| Germany    | 7        | 14%     |
| UK         | 4        | 8%      |
| Ukraine    | 3        | 6%      |
| Sweden     | 2        | 4%      |
| Russia     | 2        | 4%      |
| Canada     | 2        | 4%      |
| Taiwan     | 1        | 2%      |
| Slovenia   | 1        | 2%      |
| Poland     | 1        | 2%      |
| Luxembourg | 1        | 2%      |
| Kenya      | 1        | 2%      |
| Greece     | 1        | 2%      |
| Czechia    | 1        | 2%      |
| Brazil     | 1        | 2%      |
| Belgium    | 1        | 2%      |
| Belarus    | 1        | 2%      |
| Argentina  | 1        | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                         | Desktops | Percent |
|------------------------------|----------|---------|
| Waterloo                     | 3        | 4.41%   |
| Paris                        | 3        | 4.41%   |
| Mala Danylivka               | 3        | 4.41%   |
| Kharkiv                      | 3        | 4.41%   |
| Oakland                      | 2        | 2.94%   |
| Kingston upon Thames         | 2        | 2.94%   |
| Grants Pass                  | 2        | 2.94%   |
| Cologne                      | 2        | 2.94%   |
| Basingstoke                  | 2        | 2.94%   |
| Yakutsk                      | 1        | 1.47%   |
| Werl                         | 1        | 1.47%   |
| Voronezh                     | 1        | 1.47%   |
| Volos                        | 1        | 1.47%   |
| Tresserve                    | 1        | 1.47%   |
| Teddington                   | 1        | 1.47%   |
| Strasbourg                   | 1        | 1.47%   |
| Sternberk                    | 1        | 1.47%   |
| Sartrouville                 | 1        | 1.47%   |
| Sainte-GeneviÃ¨ve-des-Bois | 1        | 1.47%   |
| Saint-Michel-sur-Orge        | 1        | 1.47%   |
| Rio de Janeiro               | 1        | 1.47%   |
| Penmarch                     | 1        | 1.47%   |
| Palermo                      | 1        | 1.47%   |
| Nova Vodolaha                | 1        | 1.47%   |
| Nova Gorica                  | 1        | 1.47%   |
| Niedermodern                 | 1        | 1.47%   |
| New Taipei                   | 1        | 1.47%   |
| Nairobi                      | 1        | 1.47%   |
| Munich                       | 1        | 1.47%   |
| Mannheim                     | 1        | 1.47%   |
| Luxembourg                   | 1        | 1.47%   |
| LiГЁge                     | 1        | 1.47%   |
| Kehychivka                   | 1        | 1.47%   |
| Kalisz                       | 1        | 1.47%   |
| Jena                         | 1        | 1.47%   |
| Huty                         | 1        | 1.47%   |
| Helsingborg                  | 1        | 1.47%   |
| Hammersmith                  | 1        | 1.47%   |
| Frankfurt am Main            | 1        | 1.47%   |
| Fort Bragg                   | 1        | 1.47%   |
| Farnborough                  | 1        | 1.47%   |
| Essen                        | 1        | 1.47%   |
| Erlangen                     | 1        | 1.47%   |
| Edinburgh                    | 1        | 1.47%   |
| Draveil                      | 1        | 1.47%   |
| Delta                        | 1        | 1.47%   |
| Concarneau                   | 1        | 1.47%   |
| Colindale                    | 1        | 1.47%   |
| Beurlay                      | 1        | 1.47%   |
| Berlezh                      | 1        | 1.47%   |
| Bamberg                      | 1        | 1.47%   |
| Arlington                    | 1        | 1.47%   |
| Arboga                       | 1        | 1.47%   |
| Angers                       | 1        | 1.47%   |
| Aix-les-Bains                | 1        | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 34       | 141    | 28.1%   |
| Seagate             | 19       | 33     | 15.7%   |
| Samsung Electronics | 14       | 18     | 11.57%  |
| Kingston            | 9        | 17     | 7.44%   |
| SanDisk             | 7        | 13     | 5.79%   |
| Toshiba             | 6        | 13     | 4.96%   |
| Hitachi             | 5        | 5      | 4.13%   |
| PNY                 | 3        | 4      | 2.48%   |
| HGST                | 3        | 3      | 2.48%   |
| Unknown             | 2        | 2      | 1.65%   |
| OCZ-VERTEX          | 2        | 2      | 1.65%   |
| OCZ                 | 2        | 2      | 1.65%   |
| Intel               | 2        | 2      | 1.65%   |
| Crucial             | 2        | 6      | 1.65%   |
| XPG                 | 1        | 4      | 0.83%   |
| Verbatim            | 1        | 1      | 0.83%   |
| Transcend           | 1        | 1      | 0.83%   |
| Team                | 1        | 1      | 0.83%   |
| SK Hynix            | 1        | 1      | 0.83%   |
| Phison              | 1        | 1      | 0.83%   |
| HUAWEI              | 1        | 1      | 0.83%   |
| FORESEE             | 1        | 1      | 0.83%   |
| Corsair             | 1        | 1      | 0.83%   |
| Asmedia             | 1        | 1      | 0.83%   |
| A-DATA Technology   | 1        | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD2500BEVT-22ZCT0 250GB      | 4        | 2.84%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 2.13%   |
| Samsung SSD 860 EVO 250GB        | 3        | 2.13%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 2        | 1.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 1.42%   |
| WDC WD30EZRZ-00Z5HB0 3TB         | 2        | 1.42%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 1.42%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2        | 1.42%   |
| WDC WD10EFRX-68PJCN0 1TB         | 2        | 1.42%   |
| Toshiba HDWD120 2TB              | 2        | 1.42%   |
| Seagate ST3500418AS 500GB        | 2        | 1.42%   |
| Seagate ST32000644NS 2TB         | 2        | 1.42%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 1.42%   |
| SanDisk SDSSDA120G 120GB         | 2        | 1.42%   |
| SanDisk Extreme SSD 2TB          | 2        | 1.42%   |
| Samsung SSD 860 EVO 500GB        | 2        | 1.42%   |
| Samsung SSD 850 EVO 500GB        | 2        | 1.42%   |
| OCZ-VERTEX PLUS R2 247GB SSD     | 2        | 1.42%   |
| Kingston SV300S37A240G 240GB SSD | 2        | 1.42%   |
| Kingston SH103S3120G 120GB SSD   | 2        | 1.42%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 1.42%   |
| Intel SSDSC2CW120A3 120GB        | 2        | 1.42%   |
| Hitachi HDS722020ALA330 2TB      | 2        | 1.42%   |
| HGST HUS726040ALE611 4TB         | 2        | 1.42%   |
| XPG NVMe SSD Drive 2TB           | 1        | 0.71%   |
| XPG NVMe SSD Drive 1024GB        | 1        | 0.71%   |
| WDC WDS500G3XHC-00SJG0 500GB     | 1        | 0.71%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.71%   |
| WDC WDS100T2B0A 1TB SSD          | 1        | 0.71%   |
| WDC WD800BB-00JHC0 80GB          | 1        | 0.71%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.71%   |
| WDC WD5000AADS-00S9B0 500GB      | 1        | 0.71%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.71%   |
| WDC WD4000FYYZ-01UL1B2 4TB       | 1        | 0.71%   |
| WDC WD3200KS-00PFB0 320GB        | 1        | 0.71%   |
| WDC WD3200AAJS-00B4A0 320GB      | 1        | 0.71%   |
| WDC WD30PURX-64P6ZY0 3TB         | 1        | 0.71%   |
| WDC WD30EZRX-00DC0B0 3TB         | 1        | 0.71%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1        | 0.71%   |
| WDC WD3000GLFS-01F8U0 304GB      | 1        | 0.71%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.71%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.71%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.71%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 1        | 0.71%   |
| WDC WD141KRYZ-01C66B0 14TB       | 1        | 0.71%   |
| WDC WD10SPZX-00Z10T0 1TB         | 1        | 0.71%   |
| WDC WD10JPVX-60JC3T0 1TB         | 1        | 0.71%   |
| WDC WD10EZRX-00L4HB0 1TB         | 1        | 0.71%   |
| WDC WD10EZRX-00A8LB0 1TB         | 1        | 0.71%   |
| WDC WD10EZEX-22MFCA0 1TB         | 1        | 0.71%   |
| WDC WD10EARS-00Y5B1 1TB          | 1        | 0.71%   |
| WDC WD10EARS-00MVWB0 1TB         | 1        | 0.71%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 0.71%   |
| Verbatim USB External SSD 256GB  | 1        | 0.71%   |
| Unknown SD/MMC/MS PRO 64GB       | 1        | 0.71%   |
| Unknown L200 Hard drive 2TB      | 1        | 0.71%   |
| Transcend TS512GSSD370 512GB     | 1        | 0.71%   |
| Toshiba HDWD110 1TB              | 1        | 0.71%   |
| Toshiba DT01ACA300 3TB           | 1        | 0.71%   |
| Toshiba DT01ACA100 1TB           | 1        | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 28       | 124    | 42.42%  |
| Seagate             | 19       | 33     | 28.79%  |
| Toshiba             | 6        | 13     | 9.09%   |
| Hitachi             | 5        | 5      | 7.58%   |
| HGST                | 3        | 3      | 4.55%   |
| Unknown             | 2        | 2      | 3.03%   |
| Samsung Electronics | 2        | 4      | 3.03%   |
| Asmedia             | 1        | 1      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 12     | 22.92%  |
| Kingston            | 8        | 14     | 16.67%  |
| WDC                 | 6        | 16     | 12.5%   |
| SanDisk             | 5        | 7      | 10.42%  |
| PNY                 | 3        | 4      | 6.25%   |
| OCZ-VERTEX          | 2        | 2      | 4.17%   |
| OCZ                 | 2        | 2      | 4.17%   |
| Intel               | 2        | 2      | 4.17%   |
| Crucial             | 2        | 6      | 4.17%   |
| Verbatim            | 1        | 1      | 2.08%   |
| Transcend           | 1        | 1      | 2.08%   |
| Team                | 1        | 1      | 2.08%   |
| SK Hynix            | 1        | 1      | 2.08%   |
| FORESEE             | 1        | 1      | 2.08%   |
| Corsair             | 1        | 1      | 2.08%   |
| A-DATA Technology   | 1        | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 45       | 185    | 53.57%  |
| SSD     | 31       | 72     | 36.9%   |
| NVMe    | 7        | 17     | 8.33%   |
| Unknown | 1        | 1      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 51       | 243    | 78.46%  |
| SAS  | 7        | 15     | 10.77%  |
| NVMe | 7        | 17     | 10.77%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 41       | 87     | 42.71%  |
| 0.51-1.0   | 26       | 89     | 27.08%  |
| 1.01-2.0   | 15       | 28     | 15.63%  |
| 2.01-3.0   | 6        | 42     | 6.25%   |
| 3.01-4.0   | 5        | 7      | 5.21%   |
| 4.01-10.0  | 2        | 3      | 2.08%   |
| 10.01-20.0 | 1        | 1      | 1.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 14       | 25.93%  |
| 501-1000       | 13       | 24.07%  |
| 2001-3000      | 8        | 14.81%  |
| 101-250        | 6        | 11.11%  |
| 1001-2000      | 6        | 11.11%  |
| 251-500        | 4        | 7.41%   |
| 51-100         | 2        | 3.7%    |
| Unknown        | 1        | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 10       | 16.67%  |
| 101-250        | 10       | 16.67%  |
| 1001-2000      | 10       | 16.67%  |
| 501-1000       | 9        | 15%     |
| 51-100         | 7        | 11.67%  |
| More than 3000 | 6        | 10%     |
| 1-20           | 5        | 8.33%   |
| 21-50          | 1        | 1.67%   |
| 2001-3000      | 1        | 1.67%   |
| Unknown        | 1        | 1.67%   |

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
| Detected | 27       | 109    | 43.55%  |
| Works    | 26       | 156    | 41.94%  |
| Malfunc  | 9        | 10     | 14.52%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 32       | 45.07%  |
| AMD                         | 17       | 23.94%  |
| Marvell Technology Group    | 7        | 9.86%   |
| ASMedia Technology          | 5        | 7.04%   |
| Sandisk                     | 3        | 4.23%   |
| Phison Electronics          | 2        | 2.82%   |
| Samsung Electronics         | 1        | 1.41%   |
| Kingston Technology Company | 1        | 1.41%   |
| JMicron Technology          | 1        | 1.41%   |
| Broadcom                    | 1        | 1.41%   |
| ADATA Technology            | 1        | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 8.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 7.69%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 5.49%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 4        | 4.4%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4        | 4.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 4.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 4.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 4.4%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 3.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 3.3%    |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.3%    |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 2.2%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 2.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.2%    |
| AMD X399 Series Chipset SATA Controller                                                 | 2        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.1%    |
| Phison E7 NVMe Controller                                                               | 1        | 1.1%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.1%    |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 1.1%    |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 1.1%    |
| JMicron JMB362 SATA Controller                                                          | 1        | 1.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.1%    |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 1.1%    |
| Intel C610/X99 series chipset 4-port SATA Controller [IDE mode]                         | 1        | 1.1%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.1%    |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.1%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.1%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.1%    |
| Broadcom OSB4 IDE Controller                                                            | 1        | 1.1%    |
| AMD SB600 Non-Raid-5 SATA                                                               | 1        | 1.1%    |
| AMD SB600 IDE                                                                           | 1        | 1.1%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.1%    |
| AMD FCH SATA Controller D                                                               | 1        | 1.1%    |
| AMD FCH IDE Controller                                                                  | 1        | 1.1%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 42       | 63.64%  |
| IDE  | 13       | 19.7%   |
| NVMe | 7        | 10.61%  |
| RAID | 3        | 4.55%   |
| SAS  | 1        | 1.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 33       | 66%     |
| AMD    | 17       | 34%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz                | 2        | 3.92%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 2        | 3.92%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 2        | 3.92%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 3.92%   |
| AMD FX-8350 Eight-Core Processor                | 2        | 3.92%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz              | 1        | 1.96%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz             | 1        | 1.96%   |
| Intel Pentium III (Coppermine)                  | 1        | 1.96%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz          | 1        | 1.96%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 1        | 1.96%   |
| Intel Pentium CPU G3450 @ 3.40GHz               | 1        | 1.96%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 1.96%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 1.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 1.96%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1        | 1.96%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 1.96%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1        | 1.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1        | 1.96%   |
| Intel Core i5-7600K CPU @ 3.80GHz               | 1        | 1.96%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 1        | 1.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 1.96%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 1        | 1.96%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1        | 1.96%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1        | 1.96%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1        | 1.96%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 1.96%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.96%   |
| Intel Core 2 CPU 6600 @ 2.40GHz                 | 1        | 1.96%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1        | 1.96%   |
| Intel Celeron CPU G1830 @ 2.80GHz               | 1        | 1.96%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1        | 1.96%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1        | 1.96%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 1.96%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 1.96%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 1.96%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 1.96%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1        | 1.96%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 1        | 1.96%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1        | 1.96%   |
| AMD Phenom II X6 1100T Processor                | 1        | 1.96%   |
| AMD Phenom II X4 955 Processor                  | 1        | 1.96%   |
| AMD FX-8120 Eight-Core Processor                | 1        | 1.96%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 1.96%   |
| AMD Athlon II X3 455 Processor                  | 1        | 1.96%   |
| AMD A8-6600K APU with Radeon HD Graphics        | 1        | 1.96%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 9        | 18%     |
| Intel Core i5           | 8        | 16%     |
| Intel Core i3           | 5        | 10%     |
| AMD FX                  | 4        | 8%      |
| Intel Xeon              | 2        | 4%      |
| Intel Core 2 Duo        | 2        | 4%      |
| Intel Celeron           | 2        | 4%      |
| AMD Ryzen Threadripper  | 2        | 4%      |
| AMD Ryzen 7             | 2        | 4%      |
| AMD Ryzen 5             | 2        | 4%      |
| Intel Pentium III       | 1        | 2%      |
| Intel Pentium Gold      | 1        | 2%      |
| Intel Pentium Dual-Core | 1        | 2%      |
| Intel Pentium           | 1        | 2%      |
| Intel Core 2            | 1        | 2%      |
| AMD Ryzen 9             | 1        | 2%      |
| AMD Ryzen 3             | 1        | 2%      |
| AMD Phenom II X6        | 1        | 2%      |
| AMD Phenom II X4        | 1        | 2%      |
| AMD Athlon II X3        | 1        | 2%      |
| AMD A8                  | 1        | 2%      |
| AMD A10                 | 1        | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 25       | 49.02%  |
| 2      | 14       | 27.45%  |
| 6      | 5        | 9.8%    |
| 8      | 2        | 3.92%   |
| 3      | 2        | 3.92%   |
| 32     | 1        | 1.96%   |
| 16     | 1        | 1.96%   |
| 12     | 1        | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 98%     |
| 2      | 1        | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 30       | 60%     |
| 1      | 20       | 40%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 48       | 92.31%  |
| Unknown        | 3        | 5.77%   |
| 32-bit         | 1        | 1.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 21.43%  |
| 0x306c3    | 7        | 12.5%   |
| 0x206a7    | 5        | 8.93%   |
| 0x1067a    | 3        | 5.36%   |
| 0x306a9    | 2        | 3.57%   |
| 0x08701021 | 2        | 3.57%   |
| 0x0800820d | 2        | 3.57%   |
| 0x06000852 | 2        | 3.57%   |
| 0x010000c8 | 2        | 3.57%   |
| 0xa0653    | 1        | 1.79%   |
| 0x906eb    | 1        | 1.79%   |
| 0x906ea    | 1        | 1.79%   |
| 0x906e9    | 1        | 1.79%   |
| 0x6f6      | 1        | 1.79%   |
| 0x686      | 1        | 1.79%   |
| 0x506c9    | 1        | 1.79%   |
| 0x306f2    | 1        | 1.79%   |
| 0x206d7    | 1        | 1.79%   |
| 0x08701013 | 1        | 1.79%   |
| 0x08108109 | 1        | 1.79%   |
| 0x08108102 | 1        | 1.79%   |
| 0x08101016 | 1        | 1.79%   |
| 0x0800820b | 1        | 1.79%   |
| 0x08001137 | 1        | 1.79%   |
| 0x06003104 | 1        | 1.79%   |
| 0x06001119 | 1        | 1.79%   |
| 0x0600084f | 1        | 1.79%   |
| 0x010000bf | 1        | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 10       | 19.61%  |
| SandyBridge | 6        | 11.76%  |
| KabyLake    | 6        | 11.76%  |
| Zen+        | 4        | 7.84%   |
| Piledriver  | 4        | 7.84%   |
| Zen 2       | 3        | 5.88%   |
| Penryn      | 3        | 5.88%   |
| K10         | 3        | 5.88%   |
| Zen         | 2        | 3.92%   |
| Skylake     | 2        | 3.92%   |
| IvyBridge   | 2        | 3.92%   |
| Steamroller | 1        | 1.96%   |
| P6          | 1        | 1.96%   |
| Goldmont    | 1        | 1.96%   |
| Core        | 1        | 1.96%   |
| CometLake   | 1        | 1.96%   |
| Bulldozer   | 1        | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 29       | 52.73%  |
| Intel  | 15       | 27.27%  |
| AMD    | 11       | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 7.27%   |
| Nvidia GF108 [GeForce GT 430]                                               | 4        | 7.27%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 5.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 5.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 5.45%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 3        | 5.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 3.64%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 3.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 3.64%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 3.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 3.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.64%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 2        | 3.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.82%   |
| Nvidia NV11 [GeForce2 MX/MX 400]                                            | 1        | 1.82%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.82%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.82%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 1.82%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.82%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 1.82%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.82%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.82%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.82%   |
| Intel UHD Graphics 620                                                      | 1        | 1.82%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.82%   |
| Intel HD Graphics 630                                                       | 1        | 1.82%   |
| Intel HD Graphics 500                                                       | 1        | 1.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.82%   |
| AMD Richland [Radeon HD 8570D]                                              | 1        | 1.82%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 1        | 1.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.82%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 1.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 1.82%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 26       | 50.98%  |
| 1 x Intel      | 11       | 21.57%  |
| 1 x AMD        | 11       | 21.57%  |
| Intel + Nvidia | 3        | 5.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 27       | 51.92%  |
| Unknown     | 13       | 25%     |
| Proprietary | 12       | 23.08%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 13       | 25.49%  |
| Unknown    | 12       | 23.53%  |
| 0.51-1.0   | 11       | 21.57%  |
| 3.01-4.0   | 4        | 7.84%   |
| 5.01-6.0   | 3        | 5.88%   |
| 0.01-0.5   | 3        | 5.88%   |
| 7.01-8.0   | 2        | 3.92%   |
| 2.01-3.0   | 2        | 3.92%   |
| 8.01-16.0  | 1        | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 6        | 10.17%  |
| Ancor Communications | 6        | 10.17%  |
| SNC                  | 4        | 6.78%   |
| Samsung Electronics  | 4        | 6.78%   |
| Goldstar             | 4        | 6.78%   |
| BenQ                 | 4        | 6.78%   |
| AOC                  | 4        | 6.78%   |
| Acer                 | 4        | 6.78%   |
| ViewSonic            | 3        | 5.08%   |
| Sony                 | 3        | 5.08%   |
| Philips              | 3        | 5.08%   |
| LG Electronics       | 3        | 5.08%   |
| Hewlett-Packard      | 2        | 3.39%   |
| RTK                  | 1        | 1.69%   |
| QBell                | 1        | 1.69%   |
| PKB                  | 1        | 1.69%   |
| ONKYO                | 1        | 1.69%   |
| Medion               | 1        | 1.69%   |
| HannStar             | 1        | 1.69%   |
| Eizo                 | 1        | 1.69%   |
| Compal               | 1        | 1.69%   |
| ASUSTek Computer     | 1        | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                    | 4        | 5.88%   |
| Goldstar 27EA33 GSM59BC 1920x1080 598x337mm 27.0-inch                  | 2        | 2.94%   |
| Ancor Communications PA248 ACI24B1 1920x1200 546x352mm 25.6-inch       | 2        | 2.94%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch  | 2        | 2.94%   |
| ViewSonic VX2409 SERIES VSC6C2E 1920x1080 521x293mm 23.5-inch          | 1        | 1.47%   |
| ViewSonic VA903-3Series VSC701E 1280x1024 376x301mm 19.0-inch          | 1        | 1.47%   |
| ViewSonic LCD Monitor VP2468 Series 3520x1080                          | 1        | 1.47%   |
| Sony TV SNYF301 1920x1080 1600x900mm 72.3-inch                         | 1        | 1.47%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                          | 1        | 1.47%   |
| Sony SDM-X72 SNY1E70 1280x1024 338x270mm 17.0-inch                     | 1        | 1.47%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch   | 1        | 1.47%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1        | 1.47%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch | 1        | 1.47%   |
| Samsung Electronics LCD Monitor S24D330 3840x1080                      | 1        | 1.47%   |
| Samsung Electronics LCD Monitor S24D330                                | 1        | 1.47%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 1.47%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                 | 1        | 1.47%   |
| QBell QB.19F-4WLHGB QBL3EC6 1440x900 410x257mm 19.1-inch               | 1        | 1.47%   |
| PKB LCD Monitor Viseo223DX 1920x1080                                   | 1        | 1.47%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch             | 1        | 1.47%   |
| Philips LCD Monitor FTV                                                | 1        | 1.47%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                     | 1        | 1.47%   |
| ONKYO LCD Monitor TX-SR608 5760x2160                                   | 1        | 1.47%   |
| ONKYO LCD Monitor TX-SR608                                             | 1        | 1.47%   |
| ONKYO LCD Monitor AV Receiver 5760x2160                                | 1        | 1.47%   |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                  | 1        | 1.47%   |
| LG Electronics LCD Monitor LG HDR 4K 5760x2160                         | 1        | 1.47%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 1.47%   |
| LG Electronics LCD Monitor 23MB35 1920x1080                            | 1        | 1.47%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch          | 1        | 1.47%   |
| Hewlett-Packard w22 HWP26AE 1680x1050 473x296mm 22.0-inch              | 1        | 1.47%   |
| Hewlett-Packard LP1965 HWP2693 1280x1024 380x300mm 19.1-inch           | 1        | 1.47%   |
| HannStar HF225 HSP18BB 1920x1080 477x268mm 21.5-inch                   | 1        | 1.47%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 1.47%   |
| Goldstar 22BK55 GSM5A30 1680x1050 480x300mm 22.3-inch                  | 1        | 1.47%   |
| Eizo EV2436W ENC2384 1920x1200 519x324mm 24.1-inch                     | 1        | 1.47%   |
| Dell P2719H DEL4185 1920x1080 600x340mm 27.2-inch                      | 1        | 1.47%   |
| Dell P2715Q DEL40BF 3840x2160 597x336mm 27.0-inch                      | 1        | 1.47%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                      | 1        | 1.47%   |
| Dell LCD Monitor U2715H 2560x1440                                      | 1        | 1.47%   |
| Dell LCD Monitor ST2420L                                               | 1        | 1.47%   |
| Dell LCD Monitor SP2309W                                               | 1        | 1.47%   |
| Dell LCD Monitor P190S 2560x1024                                       | 1        | 1.47%   |
| Compal TERRA 2450W WOR2450 1920x1080 341x256mm 16.8-inch               | 1        | 1.47%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                     | 1        | 1.47%   |
| BenQ LCD Monitor LCD 4480x1440                                         | 1        | 1.47%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 1        | 1.47%   |
| BenQ G900 BNQ7804 1280x1024 376x301mm 19.0-inch                        | 1        | 1.47%   |
| ASUSTek Computer VG278 AUS27AF 1920x1080 598x336mm 27.0-inch           | 1        | 1.47%   |
| AOC LCD Monitor 2060W 3520x1080                                        | 1        | 1.47%   |
| AOC LCD Monitor 2060W 3200x900                                         | 1        | 1.47%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                        | 1        | 1.47%   |
| AOC 2240w AOC2240 1920x1080 480x270mm 21.7-inch                        | 1        | 1.47%   |
| AOC 2060W AOC2060 1600x900 432x240mm 19.5-inch                         | 1        | 1.47%   |
| Ancor Communications LCD Monitor ASUS VE278 3840x1080                  | 1        | 1.47%   |
| Ancor Communications ASUS VH222 ACI22AB 1920x1080 477x268mm 21.5-inch  | 1        | 1.47%   |
| Acer X203H ACR009D 1600x900 443x249mm 20.0-inch                        | 1        | 1.47%   |
| Acer S220HQL ACR0281 1920x1080 477x268mm 21.5-inch                     | 1        | 1.47%   |
| Acer LCD Monitor X203H                                                 | 1        | 1.47%   |
| Acer LCD Monitor EK240Y 1920x1080                                      | 1        | 1.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 40%     |
| Unknown            | 7        | 11.67%  |
| 3840x2160 (4K)     | 5        | 8.33%   |
| 1366x768 (WXGA)    | 4        | 6.67%   |
| 1280x1024 (SXGA)   | 4        | 6.67%   |
| 1920x1200 (WUXGA)  | 3        | 5%      |
| 3840x1080          | 2        | 3.33%   |
| 1680x1050 (WSXGA+) | 2        | 3.33%   |
| 1600x900 (HD+)     | 2        | 3.33%   |
| 5760x2160          | 1        | 1.67%   |
| 4480x1440          | 1        | 1.67%   |
| 3520x1080          | 1        | 1.67%   |
| 3200x900           | 1        | 1.67%   |
| 2560x1440 (QHD)    | 1        | 1.67%   |
| 2560x1024          | 1        | 1.67%   |
| 1440x900 (WXGA+)   | 1        | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 19.64%  |
| 27      | 9        | 16.07%  |
| 21      | 8        | 14.29%  |
| 24      | 5        | 8.93%   |
| 19      | 5        | 8.93%   |
| 18      | 4        | 7.14%   |
| 46      | 2        | 3.57%   |
| 25      | 2        | 3.57%   |
| 23      | 2        | 3.57%   |
| 22      | 2        | 3.57%   |
| 72      | 1        | 1.79%   |
| 54      | 1        | 1.79%   |
| 42      | 1        | 1.79%   |
| 32      | 1        | 1.79%   |
| 20      | 1        | 1.79%   |
| 17      | 1        | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 30.91%  |
| 401-500     | 16       | 29.09%  |
| Unknown     | 11       | 20%     |
| 351-400     | 3        | 5.45%   |
| 1001-1500   | 3        | 5.45%   |
| 701-800     | 1        | 1.82%   |
| 601-700     | 1        | 1.82%   |
| 301-350     | 1        | 1.82%   |
| 1501-2000   | 1        | 1.82%   |
| 901-1000    | 1        | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 30       | 57.69%  |
| Unknown | 11       | 21.15%  |
| 16/10   | 7        | 13.46%  |
| 5/4     | 4        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 20.37%  |
| Unknown        | 11       | 20.37%  |
| 301-350        | 9        | 16.67%  |
| 151-200        | 8        | 14.81%  |
| 141-150        | 5        | 9.26%   |
| 251-300        | 4        | 7.41%   |
| 501-1000       | 3        | 5.56%   |
| More than 1000 | 2        | 3.7%    |
| 351-500        | 1        | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 27       | 50.94%  |
| Unknown | 11       | 20.75%  |
| 101-120 | 8        | 15.09%  |
| 1-50    | 4        | 7.55%   |
| 161-240 | 2        | 3.77%   |
| 121-160 | 1        | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 68.63%  |
| 2     | 16       | 31.37%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 28       | 41.18%  |
| Intel                    | 27       | 39.71%  |
| Qualcomm Atheros         | 3        | 4.41%   |
| Broadcom                 | 3        | 4.41%   |
| Wilocity                 | 1        | 1.47%   |
| Ultimarc                 | 1        | 1.47%   |
| MediaTek                 | 1        | 1.47%   |
| Marvell Technology Group | 1        | 1.47%   |
| Huawei Technologies      | 1        | 1.47%   |
| D-Link System            | 1        | 1.47%   |
| Aquantia                 | 1        | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 31.25%  |
| Intel I211 Gigabit Network Connection                             | 5        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 5%      |
| Intel Wireless 3165                                               | 3        | 3.75%   |
| Intel Ethernet Connection I217-V                                  | 3        | 3.75%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 2        | 2.5%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2        | 2.5%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2        | 2.5%    |
| Intel Wireless 7265                                               | 2        | 2.5%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.5%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 2.5%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 2.5%    |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1        | 1.25%   |
| Ultimarc A-PAC Arcade Control Interface                           | 1        | 1.25%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 1.25%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 1.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 1.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.25%   |
| MediaTek WiFi                                                     | 1        | 1.25%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 1.25%   |
| Intel Wireless 8260                                               | 1        | 1.25%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.25%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.25%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.25%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.25%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.25%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 1.25%   |
| Huawei Mass Storage                                               | 1        | 1.25%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.25%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 1.25%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 57.89%  |
| Realtek Semiconductor | 4        | 21.05%  |
| Wilocity              | 1        | 5.26%   |
| Qualcomm Atheros      | 1        | 5.26%   |
| MediaTek              | 1        | 5.26%   |
| Broadcom              | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 4        | 17.39%  |
| Intel Wireless 3165                                        | 3        | 13.04%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 2        | 8.7%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 2        | 8.7%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 2        | 8.7%    |
| Intel Wireless 7265                                        | 2        | 8.7%    |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 1        | 4.35%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1        | 4.35%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                     | 1        | 4.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1        | 4.35%   |
| MediaTek WiFi                                              | 1        | 4.35%   |
| Intel Wireless 8260                                        | 1        | 4.35%   |
| Intel Wi-Fi 6 AX200                                        | 1        | 4.35%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 27       | 50.94%  |
| Intel                    | 19       | 35.85%  |
| Qualcomm Atheros         | 2        | 3.77%   |
| Broadcom                 | 2        | 3.77%   |
| Marvell Technology Group | 1        | 1.89%   |
| D-Link System            | 1        | 1.89%   |
| Aquantia                 | 1        | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 45.45%  |
| Intel I211 Gigabit Network Connection                             | 5        | 9.09%   |
| Intel Ethernet Connection I217-V                                  | 3        | 5.45%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.64%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 3.64%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 3.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.82%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 1.82%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.82%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.82%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.82%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.82%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.82%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 1.82%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 73.85%  |
| WiFi     | 15       | 23.08%  |
| Modem    | 1        | 1.54%   |
| Unknown  | 1        | 1.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 78.57%  |
| WiFi     | 11       | 19.64%  |
| Unknown  | 1        | 1.79%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 66.67%  |
| 2     | 12       | 22.22%  |
| 3     | 4        | 7.41%   |
| 4     | 1        | 1.85%   |
| 0     | 1        | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 46       | 88.46%  |
| Yes  | 6        | 11.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 45.83%  |
| Cambridge Silicon Radio | 7        | 29.17%  |
| ASUSTek Computer        | 3        | 12.5%   |
| Broadcom                | 2        | 8.33%   |
| Realtek Semiconductor   | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 29.17%  |
| Intel Bluetooth wireless interface                  | 5        | 20.83%  |
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 16.67%  |
| Realtek Bluetooth Radio                             | 1        | 4.17%   |
| Intel Bluetooth Device                              | 1        | 4.17%   |
| Intel AX200 Bluetooth                               | 1        | 4.17%   |
| Broadcom Bluetooth dongle                           | 1        | 4.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4.17%   |
| ASUS Bluetooth Device                               | 1        | 4.17%   |
| ASUS BCM20702A0                                     | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 32       | 35.56%  |
| Nvidia                     | 28       | 31.11%  |
| AMD                        | 19       | 21.11%  |
| C-Media Electronics        | 5        | 5.56%   |
| Samsung Electronics        | 1        | 1.11%   |
| Mackie Designs             | 1        | 1.11%   |
| Logitech                   | 1        | 1.11%   |
| Corsair                    | 1        | 1.11%   |
| BEHRINGER International    | 1        | 1.11%   |
| Altec Lansing Technologies | 1        | 1.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 8.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 6.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 5.05%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 4.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 4.04%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 4        | 4.04%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 3.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 3.03%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 3.03%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 3.03%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 3        | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.03%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 2.02%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.02%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 2.02%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 2.02%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 2.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 2.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 2.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 2.02%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 2.02%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 2        | 2.02%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.02%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 2.02%   |
| Samsung Electronics USB C Earphones                                        | 1        | 1.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.01%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 1.01%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.01%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 1.01%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 1.01%   |
| Mackie Designs ProFX                                                       | 1        | 1.01%   |
| Logitech Headset H340                                                      | 1        | 1.01%   |
| Intel USB PnP Sound Device                                                 | 1        | 1.01%   |
| Intel Sunrise Point-LP HD Audio                                            | 1        | 1.01%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 1.01%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.01%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 1.01%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.01%   |
| Corsair ST100 Headset Output                                              | 1        | 1.01%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 1.01%   |
| BEHRINGER International UMC404HD 192k                                      | 1        | 1.01%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.01%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.01%   |
| Altec Lansing Technologies ADA-305 Speakers                                | 1        | 1.01%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 30%     |
| G.Skill             | 6        | 20%     |
| Unknown             | 4        | 13.33%  |
| Team                | 2        | 6.67%   |
| Samsung Electronics | 2        | 6.67%   |
| Corsair             | 2        | 6.67%   |
| Unknown (ABCD)      | 1        | 3.33%   |
| Nanya Technology    | 1        | 3.33%   |
| Micron Technology   | 1        | 3.33%   |
| GOODRAM             | 1        | 3.33%   |
| Crucial             | 1        | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s          | 2        | 5.88%   |
| G.Skill RAM F3-12800CL9-4GBXM 4096MB DIMM DDR3 1600MT/s      | 2        | 5.88%   |
| Unknown RAM Module 4GB DIMM 667MT/s                          | 1        | 2.94%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                       | 1        | 2.94%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 1        | 2.94%   |
| Unknown RAM Module 2GB DIMM 667MT/s                          | 1        | 2.94%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                 | 1        | 2.94%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1        | 2.94%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                       | 1        | 2.94%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 2.94%   |
| Team RAM Elite-16 4GB DIMM DDR3 1600MT/s                     | 1        | 2.94%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                   | 1        | 2.94%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 2667MT/s         | 1        | 2.94%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s       | 1        | 2.94%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4096MB DIMM DDR3 1600MT/s        | 1        | 2.94%   |
| Micron RAM 18JSF51272AZ-1G6M 4GB DIMM DDR3 1600MT/s          | 1        | 2.94%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s            | 1        | 2.94%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s            | 1        | 2.94%   |
| Kingston RAM KHX2133C11D3/8GX 8192MB DIMM DDR3 2133MT/s      | 1        | 2.94%   |
| Kingston RAM KHX1600C9D3/8G 8192MB DIMM DDR3 1600MT/s        | 1        | 2.94%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s          | 1        | 2.94%   |
| Kingston RAM 99U5584-009.A00LF 4096MB DIMM DDR3 1600MT/s     | 1        | 2.94%   |
| Kingston RAM 9905625-062.A00G 8GB DIMM DDR4 2133MT/s         | 1        | 2.94%   |
| Kingston RAM 9905624-054.A00G 8GB SODIMM DDR4 2400MT/s       | 1        | 2.94%   |
| GOODRAM RAM GY1600D364L10/8G 8GB DIMM DDR3 1600MT/s          | 1        | 2.94%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s        | 1        | 2.94%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s           | 1        | 2.94%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 1        | 2.94%   |
| G.Skill RAM F4-2133C15-8GNT 8GB DIMM DDR4 2133MT/s           | 1        | 2.94%   |
| Crucial RAM CT51264BA1339.D16F 4096MB DIMM DDR3 1333MT/s     | 1        | 2.94%   |
| Corsair RAM CMZ32GX3M4A1600C9 8GB DIMM DDR3 1600MT/s         | 1        | 2.94%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s      | 1        | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 13       | 46.43%  |
| DDR4    | 11       | 39.29%  |
| Unknown | 2        | 7.14%   |
| LPDDR4  | 1        | 3.57%   |
| DDR2    | 1        | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 27       | 96.43%  |
| SODIMM | 1        | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 51.61%  |
| 4096  | 8        | 25.81%  |
| 16384 | 4        | 12.9%   |
| 2048  | 3        | 9.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 9        | 30%     |
| 2133  | 4        | 13.33%  |
| 3200  | 3        | 10%     |
| 1333  | 3        | 10%     |
| 3334  | 2        | 6.67%   |
| 2400  | 2        | 6.67%   |
| 3733  | 1        | 3.33%   |
| 3500  | 1        | 3.33%   |
| 2933  | 1        | 3.33%   |
| 2667  | 1        | 3.33%   |
| 1867  | 1        | 3.33%   |
| 800   | 1        | 3.33%   |
| 667   | 1        | 3.33%   |

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
| 0     | 43       | 82.69%  |
| 1     | 8        | 15.38%  |
| 2     | 1        | 1.92%   |

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

