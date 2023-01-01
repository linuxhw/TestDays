Deepin - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Deepin.

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

Total: 85

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [98e2d17193](https://linux-hardware.org/?probe=98e2d17193) | Jul 21, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | [843d2132ad](https://linux-hardware.org/?probe=843d2132ad) | Jun 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [486b6a5d64](https://linux-hardware.org/?probe=486b6a5d64) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ec3689ffdc](https://linux-hardware.org/?probe=ec3689ffdc) | Apr 10, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [3e37ded7e2](https://linux-hardware.org/?probe=3e37ded7e2) | Jan 04, 2022 |
| TSINGHUA T... | B460M-HDV                   | [8447bd4156](https://linux-hardware.org/?probe=8447bd4156) | Dec 22, 2021 |
| TSINGHUA T... | B460M-HDV                   | [1146dc777c](https://linux-hardware.org/?probe=1146dc777c) | Dec 15, 2021 |
| Dell          | 07N90W A02                  | [43a5aec999](https://linux-hardware.org/?probe=43a5aec999) | Dec 07, 2021 |
| ECS           | H81H3-M4                    | [cdaf4b1031](https://linux-hardware.org/?probe=cdaf4b1031) | Dec 07, 2021 |
| TSINGHUA T... | B460M-HDV                   | [bc175433f9](https://linux-hardware.org/?probe=bc175433f9) | Sep 18, 2021 |
| TSINGHUA T... | B460M-HDV                   | [80017bc79b](https://linux-hardware.org/?probe=80017bc79b) | Sep 18, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [a428f57f6a](https://linux-hardware.org/?probe=a428f57f6a) | Sep 17, 2021 |
| TSINGHUA T... | B460-N2                     | [59d9384348](https://linux-hardware.org/?probe=59d9384348) | Aug 09, 2021 |
| Gigabyte      | B550M DS3H                  | [418d6ee68f](https://linux-hardware.org/?probe=418d6ee68f) | Jul 23, 2021 |
| Toshiba       | STI 005492G                 | [d7fe511a9e](https://linux-hardware.org/?probe=d7fe511a9e) | Jul 19, 2021 |
| AMD           | BL2 V2.3                    | [1053adf355](https://linux-hardware.org/?probe=1053adf355) | Jul 12, 2021 |
| ECS           | H81H3-M4                    | [838f10c576](https://linux-hardware.org/?probe=838f10c576) | Jun 25, 2021 |
| ECS           | H81H3-M4                    | [bfc9a4d537](https://linux-hardware.org/?probe=bfc9a4d537) | Jun 25, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [70d8ede642](https://linux-hardware.org/?probe=70d8ede642) | Jun 23, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [8431bcbed8](https://linux-hardware.org/?probe=8431bcbed8) | Jun 22, 2021 |
| Loongson      | LS3A3000-7A1000-1w-V1.2-... | [014bdabb68](https://linux-hardware.org/?probe=014bdabb68) | Jun 16, 2021 |
| Toshiba       | STI 005492G                 | [e28291b9ed](https://linux-hardware.org/?probe=e28291b9ed) | Jun 13, 2021 |
| MSI           | H81I                        | [a0f0f9e7e8](https://linux-hardware.org/?probe=a0f0f9e7e8) | May 06, 2021 |
| Huanan        | X99-8M-F V1.1               | [13daa2d4a6](https://linux-hardware.org/?probe=13daa2d4a6) | Apr 23, 2021 |
| ASUSTek       | P8H61-MX                    | [9212747e6a](https://linux-hardware.org/?probe=9212747e6a) | Apr 08, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [e6db1c79cc](https://linux-hardware.org/?probe=e6db1c79cc) | Mar 25, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [edb786e43a](https://linux-hardware.org/?probe=edb786e43a) | Mar 25, 2021 |
| ASUSTek       | PRIME A320M-K               | [1db414e1cd](https://linux-hardware.org/?probe=1db414e1cd) | Mar 21, 2021 |
| Gigabyte      | H81M-D2V                    | [d62d3a2dad](https://linux-hardware.org/?probe=d62d3a2dad) | Mar 19, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [b165cd04ce](https://linux-hardware.org/?probe=b165cd04ce) | Feb 25, 2021 |
| Dell          | 0KWVT8 A00                  | [56f1d17280](https://linux-hardware.org/?probe=56f1d17280) | Feb 04, 2021 |
| Dell          | 00V62H A00                  | [863c1d64fe](https://linux-hardware.org/?probe=863c1d64fe) | Jan 23, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [842703dc6b](https://linux-hardware.org/?probe=842703dc6b) | Jan 20, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [5b9e365258](https://linux-hardware.org/?probe=5b9e365258) | Jan 19, 2021 |
| Gigabyte      | B365M D3H-CF                | [0bfbe639fc](https://linux-hardware.org/?probe=0bfbe639fc) | Jan 18, 2021 |
| Gigabyte      | H81M-D2V                    | [49bd67196b](https://linux-hardware.org/?probe=49bd67196b) | Nov 20, 2020 |
| Foxconn       | 2ADA                        | [2c76ab07eb](https://linux-hardware.org/?probe=2c76ab07eb) | Nov 12, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [0b46341e31](https://linux-hardware.org/?probe=0b46341e31) | Nov 07, 2020 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [a4fa363ca9](https://linux-hardware.org/?probe=a4fa363ca9) | Oct 29, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | [181ccd5686](https://linux-hardware.org/?probe=181ccd5686) | Oct 10, 2020 |
| Toshiba       | STI 013442                  | [25aa1737df](https://linux-hardware.org/?probe=25aa1737df) | Oct 02, 2020 |
| Toshiba       | STI 013442                  | [325dccb021](https://linux-hardware.org/?probe=325dccb021) | Oct 01, 2020 |
| Toshiba       | STI 013442                  | [d878c17ac5](https://linux-hardware.org/?probe=d878c17ac5) | Oct 01, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | [d5c18b2ad2](https://linux-hardware.org/?probe=d5c18b2ad2) | Sep 27, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | [27f0cbcbfa](https://linux-hardware.org/?probe=27f0cbcbfa) | Sep 27, 2020 |
| ASUSTek       | P8H77-M PRO                 | [7318b0893d](https://linux-hardware.org/?probe=7318b0893d) | Sep 22, 2020 |
| Gigabyte      | H81M-D2V                    | [c46dd29f7a](https://linux-hardware.org/?probe=c46dd29f7a) | Sep 17, 2020 |
| Gigabyte      | Z77-DS3H                    | [d7f43611eb](https://linux-hardware.org/?probe=d7f43611eb) | Sep 13, 2020 |
| HP            | 81B4                        | [9e3aa00a36](https://linux-hardware.org/?probe=9e3aa00a36) | Aug 21, 2020 |
| HP            | 81B4                        | [03c849fcd2](https://linux-hardware.org/?probe=03c849fcd2) | Jul 26, 2020 |
| Foxconn       | 2ADA                        | [035b1fd159](https://linux-hardware.org/?probe=035b1fd159) | Jul 24, 2020 |
| ASUSTek       | AM1M-A/BR                   | [dafd042867](https://linux-hardware.org/?probe=dafd042867) | Jul 22, 2020 |
| ASUSTek       | H110M-A/M.2                 | [a3dc30f185](https://linux-hardware.org/?probe=a3dc30f185) | Jul 21, 2020 |
| Positivo      | POS-PQ45AU                  | [056dd1ec51](https://linux-hardware.org/?probe=056dd1ec51) | Jul 15, 2020 |
| ASUSTek       | H110I-PLUS                  | [116754d157](https://linux-hardware.org/?probe=116754d157) | Jul 11, 2020 |
| ASUSTek       | H110I-PLUS                  | [4a0dcf77f1](https://linux-hardware.org/?probe=4a0dcf77f1) | Jun 24, 2020 |
| MSI           | P67A-GD65                   | [c0df14bdee](https://linux-hardware.org/?probe=c0df14bdee) | Jun 22, 2020 |
| ASRock        | Z77 Extreme4                | [2e074b7913](https://linux-hardware.org/?probe=2e074b7913) | May 30, 2020 |
| Gigabyte      | 990XA-UD3                   | [cc7c6da435](https://linux-hardware.org/?probe=cc7c6da435) | May 19, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [b8f32a998c](https://linux-hardware.org/?probe=b8f32a998c) | Mar 31, 2020 |
| Dell          | 0M863N A00                  | [39201e0067](https://linux-hardware.org/?probe=39201e0067) | Mar 30, 2020 |
| Dell          | 07C0H8 A00                  | [6863933279](https://linux-hardware.org/?probe=6863933279) | Mar 18, 2020 |
| ASRock        | J5005-ITX                   | [94c7463689](https://linux-hardware.org/?probe=94c7463689) | Mar 16, 2020 |
| ASRock        | J5005-ITX                   | [12e2c41514](https://linux-hardware.org/?probe=12e2c41514) | Mar 08, 2020 |
| ASRock        | J5005-ITX                   | [77ca797332](https://linux-hardware.org/?probe=77ca797332) | Mar 04, 2020 |
| ASRock        | J5005-ITX                   | [455989807e](https://linux-hardware.org/?probe=455989807e) | Mar 04, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [c8e114bee8](https://linux-hardware.org/?probe=c8e114bee8) | Feb 14, 2020 |
| Medion        | MS-7728                     | [645a7667ce](https://linux-hardware.org/?probe=645a7667ce) | Feb 07, 2020 |
| Medion        | MS-7728                     | [c55f5705f3](https://linux-hardware.org/?probe=c55f5705f3) | Feb 07, 2020 |
| ASUSTek       | Z170-AR                     | [cd4ef749f3](https://linux-hardware.org/?probe=cd4ef749f3) | Feb 03, 2020 |
| ASUSTek       | Z170-AR                     | [74934afe78](https://linux-hardware.org/?probe=74934afe78) | Feb 03, 2020 |
| ASRock        | N68-S3 FX                   | [ddf39244d2](https://linux-hardware.org/?probe=ddf39244d2) | Dec 24, 2019 |
| ASRock        | N68-S3 FX                   | [5f2a15fa54](https://linux-hardware.org/?probe=5f2a15fa54) | Dec 24, 2019 |
| Lenovo        | 3107 NOK                    | [8545691fd8](https://linux-hardware.org/?probe=8545691fd8) | Oct 24, 2019 |
| ASUSTek       | Z97-A                       | [1c2f2dd0b9](https://linux-hardware.org/?probe=1c2f2dd0b9) | Aug 06, 2019 |
| ASUSTek       | P5G41T-M LX2/BR             | [834659c2b7](https://linux-hardware.org/?probe=834659c2b7) | Jun 18, 2019 |
| ASUSTek       | P8H61-M LX2 R2.0            | [883fb20fad](https://linux-hardware.org/?probe=883fb20fad) | Jun 18, 2019 |
| ASUSTek       | P5Q-E                       | [f16456d590](https://linux-hardware.org/?probe=f16456d590) | Mar 28, 2019 |
| ASUSTek       | P5G41T-M LX2/BR             | [dacef5f8e5](https://linux-hardware.org/?probe=dacef5f8e5) | Mar 28, 2019 |
| Positivo      | POS-EINM70CS POSITIVO       | [296a0cde2c](https://linux-hardware.org/?probe=296a0cde2c) | Mar 27, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [175525d48c](https://linux-hardware.org/?probe=175525d48c) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [dccca67c2e](https://linux-hardware.org/?probe=dccca67c2e) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [d0787d5045](https://linux-hardware.org/?probe=d0787d5045) | Mar 25, 2019 |
| Gigabyte      | H110M-H-CF                  | [730a46747b](https://linux-hardware.org/?probe=730a46747b) | Nov 07, 2018 |
| Gigabyte      | H110M-H-CF                  | [0e7a915eb4](https://linux-hardware.org/?probe=0e7a915eb4) | Oct 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Deepin         | 14       | 25%     |
| Deepin 20      | 10       | 17.86%  |
| UOS 20         | 6        | 10.71%  |
| Deepin 20 beta | 4        | 7.14%   |
| Deepin 15.9.2  | 4        | 7.14%   |
| Deepin 20.1    | 3        | 5.36%   |
| Deepin 15.11   | 3        | 5.36%   |
| Deepin 20.6    | 2        | 3.57%   |
| Deepin 20.3    | 2        | 3.57%   |
| Deepin 20.2.2  | 2        | 3.57%   |
| Deepin 15.10.1 | 2        | 3.57%   |
| Deepin 20.2.4  | 1        | 1.79%   |
| Deepin 20.2.3  | 1        | 1.79%   |
| Deepin 20.2    | 1        | 1.79%   |
| Deepin 15.7    | 1        | 1.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Deepin | 52       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.4.70-amd64-desktop      | 7        | 12.5%   |
| 4.15.0-30deepin-generic   | 7        | 12.5%   |
| 4.15.0-29deepin-generic   | 7        | 12.5%   |
| 5.4.50-amd64-desktop      | 6        | 10.71%  |
| 5.3.0-3-amd64             | 6        | 10.71%  |
| 5.10.60-amd64-desktop     | 3        | 5.36%   |
| 5.10.36-amd64-desktop     | 3        | 5.36%   |
| 5.7.7-amd64-desktop       | 2        | 3.57%   |
| 5.10.29-amd64-desktop     | 2        | 3.57%   |
| 5.10.18-amd64-desktop     | 2        | 3.57%   |
| 4.19.0-amd64-desktop      | 2        | 3.57%   |
| 5.8.14-amd64-desktop      | 1        | 1.79%   |
| 5.5.4-xanmod3             | 1        | 1.79%   |
| 5.15.24-amd64-desktop     | 1        | 1.79%   |
| 5.14.0-rc3-amd64-desktop  | 1        | 1.79%   |
| 5.10.50-amd64-desktop     | 1        | 1.79%   |
| 5.10.5-amd64-desktop+     | 1        | 1.79%   |
| 5.10.101-amd64-desktop    | 1        | 1.79%   |
| 4.19.90-1.lns7.2.mips64el | 1        | 1.79%   |
| 4.19.0-5-amd64            | 1        | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 14       | 25%     |
| 5.4.70   | 7        | 12.5%   |
| 5.4.50   | 6        | 10.71%  |
| 5.3.0    | 6        | 10.71%  |
| 5.10.60  | 3        | 5.36%   |
| 5.10.36  | 3        | 5.36%   |
| 4.19.0   | 3        | 5.36%   |
| 5.7.7    | 2        | 3.57%   |
| 5.10.29  | 2        | 3.57%   |
| 5.10.18  | 2        | 3.57%   |
| 5.8.14   | 1        | 1.79%   |
| 5.5.4    | 1        | 1.79%   |
| 5.15.24  | 1        | 1.79%   |
| 5.14.0   | 1        | 1.79%   |
| 5.10.50  | 1        | 1.79%   |
| 5.10.5   | 1        | 1.79%   |
| 5.10.101 | 1        | 1.79%   |
| 4.19.90  | 1        | 1.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15    | 14       | 26.42%  |
| 5.4     | 12       | 22.64%  |
| 5.10    | 11       | 20.75%  |
| 5.3     | 6        | 11.32%  |
| 4.19    | 4        | 7.55%   |
| 5.7     | 2        | 3.77%   |
| 5.8     | 1        | 1.89%   |
| 5.5     | 1        | 1.89%   |
| 5.15    | 1        | 1.89%   |
| 5.14    | 1        | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 51       | 98.08%  |
| mips64 | 1        | 1.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Deepin  | 44       | 83.02%  |
| Unknown | 8        | 15.09%  |
| MATE    | 1        | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 51       | 98.08%  |
| Tty  | 1        | 1.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 55.77%  |
| LightDM | 12       | 23.08%  |
| TDM     | 11       | 21.15%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 11       | 20.37%  |
| pt_BR   | 10       | 18.52%  |
| zh_CN   | 8        | 14.81%  |
| Unknown | 8        | 14.81%  |
| es_ES   | 7        | 12.96%  |
| de_DE   | 3        | 5.56%   |
| ru_RU   | 1        | 1.85%   |
| pl_PL   | 1        | 1.85%   |
| lt_LT   | 1        | 1.85%   |
| it_IT   | 1        | 1.85%   |
| id_ID   | 1        | 1.85%   |
| fr_FR   | 1        | 1.85%   |
| en_GB   | 1        | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 31       | 59.62%  |
| EFI  | 21       | 40.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 48       | 92.31%  |
| Unknown | 4        | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 50%     |
| GPT     | 20       | 37.04%  |
| MBR     | 7        | 12.96%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 73.58%  |
| Yes       | 14       | 26.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 81.13%  |
| Yes       | 10       | 18.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 13       | 25%     |
| Gigabyte Technology        | 9        | 17.31%  |
| TSINGHUA TONGFANG COMPUTER | 4        | 7.69%   |
| Dell                       | 4        | 7.69%   |
| ASRock                     | 4        | 7.69%   |
| MSI                        | 3        | 5.77%   |
| Semp Toshiba               | 2        | 3.85%   |
| Positivo                   | 2        | 3.85%   |
| Lenovo                     | 2        | 3.85%   |
| ECS                        | 2        | 3.85%   |
| Medion                     | 1        | 1.92%   |
| Loongson                   | 1        | 1.92%   |
| Huanan                     | 1        | 1.92%   |
| Hewlett-Packard            | 1        | 1.92%   |
| Foxconn                    | 1        | 1.92%   |
| AMD                        | 1        | 1.92%   |
| Unknown                    | 1        | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500          | 4        | 7.69%   |
| Semp Toshiba STI                         | 2        | 3.85%   |
| ECS H81H3-M4                             | 2        | 3.85%   |
| ASUS All Series                          | 2        | 3.85%   |
| Positivo POS-PQ45AU                      | 1        | 1.92%   |
| Positivo POS-EINM70CS                    | 1        | 1.92%   |
| MSI MS-7C83                              | 1        | 1.92%   |
| MSI MS-7851                              | 1        | 1.92%   |
| MSI MS-7681                              | 1        | 1.92%   |
| Medion MS-7728                           | 1        | 1.92%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev     | 1        | 1.92%   |
| Lenovo ThinkCentre M910t-N000 10N9CTO1WW | 1        | 1.92%   |
| Lenovo ThinkCentre M82 2929AJ2           | 1        | 1.92%   |
| Huanan X99-8M-F V1.1                     | 1        | 1.92%   |
| HP 260-P020il                            | 1        | 1.92%   |
| Gigabyte Z77-DS3H                        | 1        | 1.92%   |
| Gigabyte Z170X-Gaming 7                  | 1        | 1.92%   |
| Gigabyte H81M-D2V                        | 1        | 1.92%   |
| Gigabyte H110M-H                         | 1        | 1.92%   |
| Gigabyte GA-78LMT-USB3                   | 1        | 1.92%   |
| Gigabyte B550M DS3H                      | 1        | 1.92%   |
| Gigabyte B365M D3H                       | 1        | 1.92%   |
| Gigabyte B360M AORUS Gaming 3            | 1        | 1.92%   |
| Gigabyte 990XA-UD3                       | 1        | 1.92%   |
| Foxconn p7-1430br                        | 1        | 1.92%   |
| Dell Vostro 230                          | 1        | 1.92%   |
| Dell OptiPlex 9020                       | 1        | 1.92%   |
| Dell OptiPlex 760                        | 1        | 1.92%   |
| Dell Inspiron One 2020                   | 1        | 1.92%   |
| ASUS ROG Maximus XII HERO                | 1        | 1.92%   |
| ASUS PRIME B450M-GAMING/BR               | 1        | 1.92%   |
| ASUS PRIME B350-PLUS                     | 1        | 1.92%   |
| ASUS PRIME A320M-K                       | 1        | 1.92%   |
| ASUS P8H77-M PRO                         | 1        | 1.92%   |
| ASUS P8H61-MX                            | 1        | 1.92%   |
| ASUS P8H61-M LX2 R2.0                    | 1        | 1.92%   |
| ASUS P5Q-E                               | 1        | 1.92%   |
| ASUS P5G41T-M LX2/BR                     | 1        | 1.92%   |
| ASUS M5A78L-M/USB3                       | 1        | 1.92%   |
| ASUS H110I-PLUS                          | 1        | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500      | 4        | 7.69%   |
| ASUS PRIME                           | 3        | 5.77%   |
| Semp Toshiba STI                     | 2        | 3.85%   |
| Lenovo ThinkCentre                   | 2        | 3.85%   |
| ECS H81H3-M4                         | 2        | 3.85%   |
| Dell OptiPlex                        | 2        | 3.85%   |
| ASUS All                             | 2        | 3.85%   |
| Positivo POS-PQ45AU                  | 1        | 1.92%   |
| Positivo POS-EINM70CS                | 1        | 1.92%   |
| MSI MS-7C83                          | 1        | 1.92%   |
| MSI MS-7851                          | 1        | 1.92%   |
| MSI MS-7681                          | 1        | 1.92%   |
| Medion MS-7728                       | 1        | 1.92%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev | 1        | 1.92%   |
| Huanan X99-8M-F                      | 1        | 1.92%   |
| HP 260-P020il                        | 1        | 1.92%   |
| Gigabyte Z77-DS3H                    | 1        | 1.92%   |
| Gigabyte Z170X-Gaming                | 1        | 1.92%   |
| Gigabyte H81M-D2V                    | 1        | 1.92%   |
| Gigabyte H110M-H                     | 1        | 1.92%   |
| Gigabyte GA-78LMT-USB3               | 1        | 1.92%   |
| Gigabyte B550M                       | 1        | 1.92%   |
| Gigabyte B365M                       | 1        | 1.92%   |
| Gigabyte B360M                       | 1        | 1.92%   |
| Gigabyte 990XA-UD3                   | 1        | 1.92%   |
| Foxconn p7-1430br                    | 1        | 1.92%   |
| Dell Vostro                          | 1        | 1.92%   |
| Dell Inspiron                        | 1        | 1.92%   |
| ASUS ROG                             | 1        | 1.92%   |
| ASUS P8H77-M                         | 1        | 1.92%   |
| ASUS P8H61-MX                        | 1        | 1.92%   |
| ASUS P8H61-M                         | 1        | 1.92%   |
| ASUS P5Q-E                           | 1        | 1.92%   |
| ASUS P5G41T-M                        | 1        | 1.92%   |
| ASUS M5A78L-M                        | 1        | 1.92%   |
| ASUS H110I-PLUS                      | 1        | 1.92%   |
| ASRock Z77                           | 1        | 1.92%   |
| ASRock Z68                           | 1        | 1.92%   |
| ASRock N68-S3                        | 1        | 1.92%   |
| ASRock J5005-ITX                     | 1        | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 8        | 15.38%  |
| 2012 | 7        | 13.46%  |
| 2021 | 5        | 9.62%   |
| 2020 | 5        | 9.62%   |
| 2018 | 5        | 9.62%   |
| 2011 | 5        | 9.62%   |
| 2014 | 4        | 7.69%   |
| 2017 | 3        | 5.77%   |
| 2016 | 3        | 5.77%   |
| 2009 | 3        | 5.77%   |
| 2010 | 2        | 3.85%   |
| 2019 | 1        | 1.92%   |
| 2008 | 1        | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 52       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 51       | 98.08%  |
| Enabled  | 1        | 1.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 52       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 20       | 38.46%  |
| 8.01-16.0   | 13       | 25%     |
| 4.01-8.0    | 9        | 17.31%  |
| 3.01-4.0    | 7        | 13.46%  |
| 32.01-64.0  | 1        | 1.92%   |
| 64.01-256.0 | 1        | 1.92%   |
| 1.01-2.0    | 1        | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 16       | 27.59%  |
| 1.01-2.0  | 16       | 27.59%  |
| 2.01-3.0  | 12       | 20.69%  |
| 3.01-4.0  | 9        | 15.52%  |
| 0.51-1.0  | 4        | 6.9%    |
| 8.01-16.0 | 1        | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 39.62%  |
| 2      | 20       | 37.74%  |
| 4      | 7        | 13.21%  |
| 3      | 4        | 7.55%   |
| 5      | 1        | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 62.96%  |
| Yes       | 20       | 37.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 52       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 69.23%  |
| Yes       | 16       | 30.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 69.23%  |
| Yes       | 16       | 30.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Brazil      | 15       | 28.85%  |
| China       | 8        | 15.38%  |
| USA         | 5        | 9.62%   |
| Panama      | 2        | 3.85%   |
| Mexico      | 2        | 3.85%   |
| Germany     | 2        | 3.85%   |
| Argentina   | 2        | 3.85%   |
| Ukraine     | 1        | 1.92%   |
| UK          | 1        | 1.92%   |
| Spain       | 1        | 1.92%   |
| Russia      | 1        | 1.92%   |
| Romania     | 1        | 1.92%   |
| Poland      | 1        | 1.92%   |
| New Zealand | 1        | 1.92%   |
| Namibia     | 1        | 1.92%   |
| Lithuania   | 1        | 1.92%   |
| Italy       | 1        | 1.92%   |
| Indonesia   | 1        | 1.92%   |
| India       | 1        | 1.92%   |
| Colombia    | 1        | 1.92%   |
| Belgium     | 1        | 1.92%   |
| Bangladesh  | 1        | 1.92%   |
| Austria     | 1        | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Sao Paulo               | 3        | 5.56%   |
| Nanjing                 | 3        | 5.56%   |
| San Francisco           | 2        | 3.7%    |
| David                   | 2        | 3.7%    |
| Beijing                 | 2        | 3.7%    |
| Wuhan                   | 1        | 1.85%   |
| Windhoek                | 1        | 1.85%   |
| Voluntari               | 1        | 1.85%   |
| Tychy                   | 1        | 1.85%   |
| Toluca                  | 1        | 1.85%   |
| Taua                    | 1        | 1.85%   |
| Surakarta               | 1        | 1.85%   |
| St Petersburg           | 1        | 1.85%   |
| Socorro                 | 1        | 1.85%   |
| Shanghai                | 1        | 1.85%   |
| Seesen                  | 1        | 1.85%   |
| Sao Caetano do Sul      | 1        | 1.85%   |
| Santa Clarita           | 1        | 1.85%   |
| Rome                    | 1        | 1.85%   |
| Rio de Janeiro          | 1        | 1.85%   |
| Ransart                 | 1        | 1.85%   |
| Para de Minas           | 1        | 1.85%   |
| Olinda                  | 1        | 1.85%   |
| Niterói                | 1        | 1.85%   |
| Naucalpan               | 1        | 1.85%   |
| Mesa                    | 1        | 1.85%   |
| Medellín               | 1        | 1.85%   |
| Marília                | 1        | 1.85%   |
| Lviv                    | 1        | 1.85%   |
| Leipzig                 | 1        | 1.85%   |
| Krakow                  | 1        | 1.85%   |
| Klagenfurt              | 1        | 1.85%   |
| Jaboatao dos Guararapes | 1        | 1.85%   |
| Itapevi                 | 1        | 1.85%   |
| Guangzhou               | 1        | 1.85%   |
| Grand Bourg             | 1        | 1.85%   |
| Gilly                   | 1        | 1.85%   |
| Getxo                   | 1        | 1.85%   |
| Elektrėnai             | 1        | 1.85%   |
| Dhaka                   | 1        | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 18       | 24     | 18.56%  |
| Seagate               | 15       | 18     | 15.46%  |
| SanDisk               | 7        | 11     | 7.22%   |
| Samsung Electronics   | 7        | 8      | 7.22%   |
| Toshiba               | 6        | 7      | 6.19%   |
| Kingston              | 5        | 9      | 5.15%   |
| Crucial               | 4        | 5      | 4.12%   |
| China                 | 4        | 4      | 4.12%   |
| A-DATA Technology     | 4        | 5      | 4.12%   |
| Hitachi               | 3        | 3      | 3.09%   |
| SPCC                  | 2        | 2      | 2.06%   |
| Silicon Motion        | 2        | 2      | 2.06%   |
| Maxtor                | 2        | 4      | 2.06%   |
| Hewlett-Packard       | 2        | 3      | 2.06%   |
| FORESEE               | 2        | 2      | 2.06%   |
| Vaseky                | 1        | 1      | 1.03%   |
| Unknown               | 1        | 2      | 1.03%   |
| Realtek Semiconductor | 1        | 1      | 1.03%   |
| Phison                | 1        | 1      | 1.03%   |
| Mushkin               | 1        | 1      | 1.03%   |
| Maxtor 6              | 1        | 1      | 1.03%   |
| LaCie                 | 1        | 2      | 1.03%   |
| KingDian              | 1        | 1      | 1.03%   |
| KINGBANK              | 1        | 1      | 1.03%   |
| JMicron Technology    | 1        | 1      | 1.03%   |
| Intenso               | 1        | 2      | 1.03%   |
| Gigabyte Technology   | 1        | 1      | 1.03%   |
| Beijing Starblaze     | 1        | 1      | 1.03%   |
| Apacer                | 1        | 3      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB      | 3        | 2.86%   |
| WDC WD5000AAKX-003CA0 500GB         | 2        | 1.9%    |
| Seagate ST1000DM003-1SB102 1TB      | 2        | 1.9%    |
| SanDisk SDSSDH3512G 512GB           | 2        | 1.9%    |
| Kingston SV300S37A120G 120GB SSD    | 2        | 1.9%    |
| FORESEE P900F256GBH                 | 2        | 1.9%    |
| WDC WDS500G2B0C-00PXH0 500GB        | 1        | 0.95%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1        | 0.95%   |
| WDC WDS120G1G0A-00SS50 120GB SSD    | 1        | 0.95%   |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 1        | 0.95%   |
| WDC WD80 0BEVE-11UYT0 80GB          | 1        | 0.95%   |
| WDC WD7500BPKX-22HPJT0 752GB        | 1        | 0.95%   |
| WDC WD6400AAKS-75A7B0 640GB         | 1        | 0.95%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 0.95%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1        | 0.95%   |
| WDC WD5000AAJS-57TKA0 500GB         | 1        | 0.95%   |
| WDC WD3200AAKS-00VYA0 320GB         | 1        | 0.95%   |
| WDC WD20PURX-64P6ZY0 2TB            | 1        | 0.95%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 0.95%   |
| WDC WD1600AAJS-00L7A0 160GB         | 1        | 0.95%   |
| WDC WD10EZEX-22MFCA0 1TB            | 1        | 0.95%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 0.95%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 0.95%   |
| WDC WD10EFRX-68FYTN0 1TB            | 1        | 0.95%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 0.95%   |
| Vaseky V800/256G 256GB SSD          | 1        | 0.95%   |
| Unknown SD/MMC/MS PRO 64GB          | 1        | 0.95%   |
| Toshiba MQ01ABF050 500GB            | 1        | 0.95%   |
| Toshiba MQ01ABD075 752GB            | 1        | 0.95%   |
| Toshiba DT01ACA200 2TB              | 1        | 0.95%   |
| Toshiba DT01ACA100 LENOVO 1TB       | 1        | 0.95%   |
| Toshiba DT01ACA100 1TB              | 1        | 0.95%   |
| Toshiba DT01ACA050 500GB            | 1        | 0.95%   |
| SPCC Solid State Disk 512GB         | 1        | 0.95%   |
| SPCC Solid State Disk 120GB         | 1        | 0.95%   |
| Silicon Motion NVME SSD 128GB       | 1        | 0.95%   |
| Silicon Motion DC 256G              | 1        | 0.95%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 0.95%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 0.95%   |
| Seagate ST3750528AS 752GB           | 1        | 0.95%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 20     | 32.61%  |
| Seagate             | 15       | 18     | 32.61%  |
| Toshiba             | 6        | 7      | 13.04%  |
| Hitachi             | 3        | 3      | 6.52%   |
| Samsung Electronics | 2        | 2      | 4.35%   |
| Maxtor              | 2        | 4      | 4.35%   |
| Unknown             | 1        | 2      | 2.17%   |
| Maxtor 6            | 1        | 1      | 2.17%   |
| Hewlett-Packard     | 1        | 2      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 7        | 11     | 18.42%  |
| Kingston            | 5        | 9      | 13.16%  |
| Samsung Electronics | 4        | 5      | 10.53%  |
| China               | 4        | 4      | 10.53%  |
| WDC                 | 3        | 3      | 7.89%   |
| Crucial             | 3        | 4      | 7.89%   |
| A-DATA Technology   | 3        | 4      | 7.89%   |
| SPCC                | 2        | 2      | 5.26%   |
| Vaseky              | 1        | 1      | 2.63%   |
| KingDian            | 1        | 1      | 2.63%   |
| KINGBANK            | 1        | 1      | 2.63%   |
| JMicron Technology  | 1        | 1      | 2.63%   |
| Intenso             | 1        | 2      | 2.63%   |
| Hewlett-Packard     | 1        | 1      | 2.63%   |
| Apacer              | 1        | 3      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 36       | 59     | 46.15%  |
| SSD     | 30       | 52     | 38.46%  |
| NVMe    | 11       | 13     | 14.1%   |
| Unknown | 1        | 2      | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 50       | 106    | 76.92%  |
| NVMe | 11       | 13     | 16.92%  |
| SAS  | 4        | 7      | 6.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 38       | 71     | 55.07%  |
| 0.51-1.0   | 25       | 32     | 36.23%  |
| 1.01-2.0   | 6        | 8      | 8.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 15       | 28.3%   |
| 501-1000       | 11       | 20.75%  |
| 251-500        | 10       | 18.87%  |
| 101-250        | 8        | 15.09%  |
| 2001-3000      | 3        | 5.66%   |
| 51-100         | 3        | 5.66%   |
| More than 3000 | 2        | 3.77%   |
| Unknown        | 1        | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 101-250   | 16       | 28.07%  |
| 501-1000  | 12       | 21.05%  |
| 21-50     | 9        | 15.79%  |
| 1-20      | 6        | 10.53%  |
| 251-500   | 5        | 8.77%   |
| 51-100    | 4        | 7.02%   |
| 1001-2000 | 3        | 5.26%   |
| 2001-3000 | 1        | 1.75%   |
| Unknown   | 1        | 1.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1      | 16.67%  |
| Seagate ST3750528AS 752GB          | 1        | 1      | 16.67%  |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 16.67%  |
| Seagate ST1000DL002-9TT153 1TB     | 1        | 1      | 16.67%  |
| Samsung Electronics HD502HJ 500GB  | 1        | 1      | 16.67%  |
| Samsung Electronics HD250HJ 250GB  | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 3      | 40%     |
| Samsung Electronics | 2        | 2      | 40%     |
| WDC                 | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 3      | 40%     |
| Samsung Electronics | 2        | 2      | 40%     |
| WDC                 | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 6      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Hitachi HUA722010CLA330 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 29       | 68     | 46.03%  |
| Works    | 28       | 51     | 44.44%  |
| Malfunc  | 5        | 6      | 7.94%   |
| Failed   | 1        | 1      | 1.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 40       | 54.79%  |
| AMD                          | 10       | 13.7%   |
| ASMedia Technology           | 5        | 6.85%   |
| Silicon Motion               | 3        | 4.11%   |
| Marvell Technology Group     | 3        | 4.11%   |
| Shenzhen Longsys Electronics | 2        | 2.74%   |
| Phison Electronics           | 2        | 2.74%   |
| SanDisk                      | 1        | 1.37%   |
| Samsung Electronics          | 1        | 1.37%   |
| Realtek Semiconductor        | 1        | 1.37%   |
| Nvidia                       | 1        | 1.37%   |
| Micron/Crucial Technology    | 1        | 1.37%   |
| Loongson Technology          | 1        | 1.37%   |
| JMicron Technology           | 1        | 1.37%   |
| Beijing Starblaze Technology | 1        | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 5.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 5.81%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 5.81%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 5.81%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 5.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 4.65%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 4.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 3.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 3.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 2.33%   |
| Shenzhen Longsys Non-Volatile memory controller                                         | 2        | 2.33%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 2.33%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.33%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.16%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.16%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 1.16%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 1.16%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.16%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.16%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.16%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.16%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 1.16%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 1.16%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.16%   |
| Loongson SATA AHCI Controller                                                           | 1        | 1.16%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 1.16%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.16%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.16%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 1.16%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 43       | 64.18%  |
| IDE  | 12       | 17.91%  |
| NVMe | 10       | 14.93%  |
| RAID | 2        | 2.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 40       | 76.92%  |
| AMD     | 11       | 21.15%  |
| Unknown | 1        | 1.92%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 7.69%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 7.69%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 3        | 5.77%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 3.85%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 3.85%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 3.85%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 3.85%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 1.92%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 1.92%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 1.92%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.92%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 1.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.92%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.92%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.92%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.92%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.92%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.92%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.92%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 1        | 1.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.92%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 1        | 1.92%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 1.92%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 1        | 1.92%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.92%   |
| Intel Core i3-3240T CPU @ 2.90GHz           | 1        | 1.92%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.92%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 1.92%   |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 1.92%   |
| Intel Celeron CPU G1840 @ 2.80GHz           | 1        | 1.92%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 1        | 1.92%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 1.92%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 1        | 1.92%   |
| AMD FX-6100 Six-Core Processor              | 1        | 1.92%   |
| AMD FX-4130 Quad-Core Processor             | 1        | 1.92%   |
| AMD C-60 APU with Radeon HD Graphics        | 1        | 1.92%   |
| AMD Athlon 5150 APU with Radeon R3          | 1        | 1.92%   |
| AMD A9-9820 Processor                       | 1        | 1.92%   |
|                                             | 1        | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 14       | 26.92%  |
| Intel Core i3           | 7        | 13.46%  |
| Intel Core i5           | 6        | 11.54%  |
| Intel Core 2 Duo        | 4        | 7.69%   |
| Intel Celeron           | 4        | 7.69%   |
| AMD FX                  | 4        | 7.69%   |
| AMD Ryzen 5             | 3        | 5.77%   |
| Other                   | 2        | 3.85%   |
| Intel Xeon              | 2        | 3.85%   |
| Intel Pentium Silver    | 1        | 1.92%   |
| Intel Pentium Dual-Core | 1        | 1.92%   |
| Intel Core i9           | 1        | 1.92%   |
| AMD Ryzen 3             | 1        | 1.92%   |
| AMD C-60                | 1        | 1.92%   |
| AMD Athlon              | 1        | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 27       | 51.92%  |
| 2      | 14       | 26.92%  |
| 6      | 5        | 9.62%   |
| 8      | 4        | 7.69%   |
| 10     | 1        | 1.92%   |
| 3      | 1        | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 52       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 29       | 55.77%  |
| 1      | 23       | 44.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 47       | 90.38%  |
| Unknown        | 5        | 9.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 30.19%  |
| 0x306a9    | 7        | 13.21%  |
| 0x306c3    | 6        | 11.32%  |
| 0x1067a    | 4        | 7.55%   |
| 0xa0655    | 3        | 5.66%   |
| 0x906e9    | 2        | 3.77%   |
| 0x206a7    | 2        | 3.77%   |
| 0xa0653    | 1        | 1.89%   |
| 0x906eb    | 1        | 1.89%   |
| 0x706a8    | 1        | 1.89%   |
| 0x506e3    | 1        | 1.89%   |
| 0x306f2    | 1        | 1.89%   |
| 0x08701013 | 1        | 1.89%   |
| 0x08001138 | 1        | 1.89%   |
| 0x08001137 | 1        | 1.89%   |
| 0x07026101 | 1        | 1.89%   |
| 0x06000822 | 1        | 1.89%   |
| 0x06000629 | 1        | 1.89%   |
| 0x06000626 | 1        | 1.89%   |
| 0x0500010d | 1        | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 9        | 17.31%  |
| Haswell       | 7        | 13.46%  |
| Penryn        | 6        | 11.54%  |
| CometLake     | 6        | 11.54%  |
| KabyLake      | 4        | 7.69%   |
| Skylake       | 3        | 5.77%   |
| SandyBridge   | 3        | 5.77%   |
| Zen 2         | 2        | 3.85%   |
| Zen           | 2        | 3.85%   |
| Piledriver    | 2        | 3.85%   |
| Goldmont plus | 2        | 3.85%   |
| Bulldozer     | 2        | 3.85%   |
| Unknown       | 2        | 3.85%   |
| Jaguar        | 1        | 1.92%   |
| Bobcat        | 1        | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Nvidia              | 22       | 40%     |
| Intel               | 16       | 29.09%  |
| AMD                 | 16       | 29.09%  |
| Loongson Technology | 1        | 1.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 5.36%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 5.36%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 3.57%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 3.57%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 3.57%   |
| Intel HD Graphics 630                                                       | 2        | 3.57%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 3.57%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 3.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 3.57%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.79%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.79%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.79%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.79%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.79%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.79%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.79%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.79%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.79%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.79%   |
| Nvidia GF116 [GeForce GT 545]                                               | 1        | 1.79%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 1.79%   |
| Loongson Technology Vivante GPU (Graphics Processing Unit)                  | 1        | 1.79%   |
| Loongson Technology DC (Display Controller)                                 | 1        | 1.79%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 1.79%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.79%   |
| AMD Wrestler [Radeon HD 6290]                                               | 1        | 1.79%   |
| AMD Whistler LE [Radeon HD 6610M/7610M]                                     | 1        | 1.79%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.79%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 1        | 1.79%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.79%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 1.79%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.79%   |
| AMD Kryptos [Radeon RX 350]                                                 | 1        | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Nvidia              | 22       | 42.31%  |
| 1 x AMD                 | 15       | 28.85%  |
| 1 x Intel               | 13       | 25%     |
| 1 x Loongson Technology | 1        | 1.92%   |
| Intel + AMD             | 1        | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 37       | 71.15%  |
| Proprietary | 13       | 25%     |
| Unknown     | 2        | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 46.3%   |
| 1.01-2.0   | 13       | 24.07%  |
| 3.01-4.0   | 6        | 11.11%  |
| 7.01-8.0   | 3        | 5.56%   |
| 0.51-1.0   | 3        | 5.56%   |
| 5.01-6.0   | 2        | 3.7%    |
| 0.01-0.5   | 2        | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 20.37%  |
| Goldstar             | 7        | 12.96%  |
| Hewlett-Packard      | 5        | 9.26%   |
| Dell                 | 3        | 5.56%   |
| Ancor Communications | 3        | 5.56%   |
| ViewSonic            | 2        | 3.7%    |
| Philips              | 2        | 3.7%    |
| Lenovo               | 2        | 3.7%    |
| Iiyama               | 2        | 3.7%    |
| AOC                  | 2        | 3.7%    |
| Acer                 | 2        | 3.7%    |
| Unknown              | 1        | 1.85%   |
| Toshiba              | 1        | 1.85%   |
| TFC                  | 1        | 1.85%   |
| SKY                  | 1        | 1.85%   |
| RTK                  | 1        | 1.85%   |
| Positivo             | 1        | 1.85%   |
| MSI                  | 1        | 1.85%   |
| Hisense              | 1        | 1.85%   |
| Gateway              | 1        | 1.85%   |
| DTV                  | 1        | 1.85%   |
| BOE                  | 1        | 1.85%   |
| BenQ                 | 1        | 1.85%   |
| ASUSTek Computer     | 1        | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                    | 2        | 3.33%   |
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch              | 1        | 1.67%   |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch              | 1        | 1.67%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 1.67%   |
| Toshiba TV TSB0108 1440x900 700x390mm 31.5-inch                         | 1        | 1.67%   |
| TFC TF2411 TFC0238 1920x1080 527x296mm 23.8-inch                        | 1        | 1.67%   |
| SKY 24X1Q SKY2380 2560x1440 520x290mm 23.4-inch                         | 1        | 1.67%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch    | 1        | 1.67%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                         | 1        | 1.67%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch     | 1        | 1.67%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch    | 1        | 1.67%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 530x300mm 24.0-inch     | 1        | 1.67%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch       | 1        | 1.67%   |
| Samsung Electronics LCD Monitor SMS23A350H 1920x1080                    | 1        | 1.67%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 1.67%   |
| Samsung Electronics LCD Monitor SAM0E90 1366x768 700x390mm 31.5-inch    | 1        | 1.67%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch   | 1        | 1.67%   |
| Samsung Electronics LCD Monitor S24E390 1920x1080                       | 1        | 1.67%   |
| Samsung Electronics LCD Monitor S24E360 1920x1080                       | 1        | 1.67%   |
| Samsung Electronics LCD Monitor S24E310 3840x1080                       | 1        | 1.67%   |
| Samsung Electronics LCD Monitor S24E310                                 | 1        | 1.67%   |
| RTK HDMI RTKBC32 2560x1600 347x215mm 16.1-inch                          | 1        | 1.67%   |
| Positivo LCD Monitor NON1801 1360x768 410x230mm 18.5-inch               | 1        | 1.67%   |
| Philips FTV PHL04C2 1920x1080 1440x810mm 65.0-inch                      | 1        | 1.67%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                      | 1        | 1.67%   |
| MSI MAG271C MSI3FA6 1920x1080 598x336mm 27.0-inch                       | 1        | 1.67%   |
| Lenovo LEN T2324C LEN60F2 1920x1080 510x287mm 23.0-inch                 | 1        | 1.67%   |
| Lenovo E1922s Wide LEN60BD 1366x768 410x230mm 18.5-inch                 | 1        | 1.67%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                    | 1        | 1.67%   |
| Iiyama PL2792Q IVM662F 2560x1440 597x336mm 27.0-inch                    | 1        | 1.67%   |
| Hisense LCD Monitor HDMI 1360x768                                       | 1        | 1.67%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 530x300mm 24.0-inch            | 1        | 1.67%   |
| Hewlett-Packard Compaq F191 HWP3177 1366x768 410x230mm 18.5-inch        | 1        | 1.67%   |
| Hewlett-Packard 2511 HWP293E 1920x1080 550x310mm 24.9-inch              | 1        | 1.67%   |
| Hewlett-Packard 2311 HWP293A 1920x1080 509x286mm 23.0-inch              | 1        | 1.67%   |
| Hewlett-Packard 22fw HPN3542 1920x1080 476x267mm 21.5-inch              | 1        | 1.67%   |
| Goldstar M227WD GSM56D4 1920x1080 476x268mm 21.5-inch                   | 1        | 1.67%   |
| Goldstar L196WTQ GSM4B50 1440x900 408x255mm 18.9-inch                   | 1        | 1.67%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch               | 1        | 1.67%   |
| Goldstar E2360 GSM57E4 1920x1080 510x290mm 23.1-inch                    | 1        | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 29       | 50.88%  |
| 2560x1440 (QHD)    | 5        | 8.77%   |
| 1600x900 (HD+)     | 4        | 7.02%   |
| 1366x768 (WXGA)    | 3        | 5.26%   |
| 3840x2160 (4K)     | 2        | 3.51%   |
| 3840x1080          | 2        | 3.51%   |
| 1440x900 (WXGA+)   | 2        | 3.51%   |
| 1360x768           | 2        | 3.51%   |
| Unknown            | 2        | 3.51%   |
| 2560x1600          | 1        | 1.75%   |
| 2288x1287          | 1        | 1.75%   |
| 1920x540           | 1        | 1.75%   |
| 1920x1200 (WUXGA)  | 1        | 1.75%   |
| 1680x1050 (WSXGA+) | 1        | 1.75%   |
| 1280x1024 (SXGA)   | 1        | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 14       | 24.56%  |
| 24      | 8        | 14.04%  |
| Unknown | 7        | 12.28%  |
| 27      | 5        | 8.77%   |
| 21      | 4        | 7.02%   |
| 18      | 4        | 7.02%   |
| 20      | 3        | 5.26%   |
| 84      | 2        | 3.51%   |
| 19      | 2        | 3.51%   |
| 142     | 1        | 1.75%   |
| 72      | 1        | 1.75%   |
| 65      | 1        | 1.75%   |
| 32      | 1        | 1.75%   |
| 31      | 1        | 1.75%   |
| 25      | 1        | 1.75%   |
| 22      | 1        | 1.75%   |
| 12      | 1        | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 27       | 48.21%  |
| 401-500        | 14       | 25%     |
| Unknown        | 7        | 12.5%   |
| 1501-2000      | 3        | 5.36%   |
| More than 2000 | 1        | 1.79%   |
| 701-800        | 1        | 1.79%   |
| 601-700        | 1        | 1.79%   |
| 201-300        | 1        | 1.79%   |
| 1001-1500      | 1        | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 42       | 79.25%  |
| Unknown | 6        | 11.32%  |
| 16/10   | 4        | 7.55%   |
| 1.00    | 1        | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 38.6%   |
| 151-200        | 9        | 15.79%  |
| Unknown        | 7        | 12.28%  |
| More than 1000 | 5        | 8.77%   |
| 301-350        | 5        | 8.77%   |
| 251-300        | 3        | 5.26%   |
| 141-150        | 3        | 5.26%   |
| 351-500        | 2        | 3.51%   |
| 61-70          | 1        | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 35       | 63.64%  |
| 101-120 | 7        | 12.73%  |
| Unknown | 7        | 12.73%  |
| 1-50    | 4        | 7.27%   |
| 161-240 | 1        | 1.82%   |
| 121-160 | 1        | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 45       | 84.91%  |
| 2     | 8        | 15.09%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 35       | 50.72%  |
| Intel                    | 13       | 18.84%  |
| TP-Link                  | 3        | 4.35%   |
| Qualcomm Atheros         | 3        | 4.35%   |
| Broadcom                 | 3        | 4.35%   |
| MediaTek                 | 2        | 2.9%    |
| Xiaomi                   | 1        | 1.45%   |
| Unknown                  | 1        | 1.45%   |
| Ralink                   | 1        | 1.45%   |
| NXP Semiconductors       | 1        | 1.45%   |
| Nvidia                   | 1        | 1.45%   |
| NetGear                  | 1        | 1.45%   |
| Marvell Technology Group | 1        | 1.45%   |
| Loongson Technology      | 1        | 1.45%   |
| IMC Networks             | 1        | 1.45%   |
| Aquantia                 | 1        | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31       | 40.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 2.6%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.6%    |
| Intel Ethernet Connection (12) I219-V                             | 2        | 2.6%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.6%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 2.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.3%    |
| Unknown Network controller                                        | 1        | 1.3%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 1.3%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 1.3%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 1.3%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 1.3%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 1.3%    |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 1        | 1.3%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 1.3%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 1.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.3%    |
| Nvidia MCP61 Ethernet                                             | 1        | 1.3%    |
| NetGear A6210                                                     | 1        | 1.3%    |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter               | 1        | 1.3%    |
| MediaTek Infinix NOTE 11                                          | 1        | 1.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.3%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.3%    |
| Loongson Gigabit Ethernet Controller                              | 1        | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.3%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.3%    |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.3%    |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.3%    |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]              | 1        | 1.3%    |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.3%    |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 6        | 37.5%   |
| TP-Link               | 3        | 18.75%  |
| Intel                 | 2        | 12.5%   |
| Ralink                | 1        | 6.25%   |
| Qualcomm Atheros      | 1        | 6.25%   |
| NetGear               | 1        | 6.25%   |
| MediaTek              | 1        | 6.25%   |
| IMC Networks          | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 6.25%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 6.25%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1        | 6.25%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1        | 6.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 6.25%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1        | 6.25%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)  | 1        | 6.25%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 6.25%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 6.25%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1        | 6.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 6.25%   |
| NetGear A6210                                              | 1        | 6.25%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter        | 1        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 6.25%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1        | 6.25%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]       | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 35       | 60.34%  |
| Intel                    | 12       | 20.69%  |
| Broadcom                 | 3        | 5.17%   |
| Qualcomm Atheros         | 2        | 3.45%   |
| Xiaomi                   | 1        | 1.72%   |
| Nvidia                   | 1        | 1.72%   |
| MediaTek                 | 1        | 1.72%   |
| Marvell Technology Group | 1        | 1.72%   |
| Loongson Technology      | 1        | 1.72%   |
| Aquantia                 | 1        | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31       | 52.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 3.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 3.39%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.39%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 3.39%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 3.39%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 3.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.69%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.69%   |
| MediaTek Infinix NOTE 11                                          | 1        | 1.69%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.69%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.69%   |
| Loongson Gigabit Ethernet Controller                              | 1        | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.69%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.69%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.69%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.69%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.69%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 52       | 74.29%  |
| WiFi     | 16       | 22.86%  |
| Modem    | 1        | 1.43%   |
| Unknown  | 1        | 1.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 84.62%  |
| WiFi     | 8        | 15.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 73.58%  |
| 2     | 12       | 22.64%  |
| 3     | 2        | 3.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 51       | 98.08%  |
| Yes  | 1        | 1.92%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 10       | 58.82%  |
| Intel                           | 2        | 11.76%  |
| Realtek Semiconductor           | 1        | 5.88%   |
| Qualcomm Atheros Communications | 1        | 5.88%   |
| MediaTek                        | 1        | 5.88%   |
| Dynex                           | 1        | 5.88%   |
| ASUSTek Computer                | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 10       | 58.82%  |
| Realtek Bluetooth Radio                                  | 1        | 5.88%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 5.88%   |
| MediaTek BT                                              | 1        | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                         | 1        | 5.88%   |
| Intel AX201 Bluetooth                                    | 1        | 5.88%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 5.88%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 40       | 44.94%  |
| Nvidia                                       | 21       | 23.6%   |
| AMD                                          | 21       | 23.6%   |
| C-Media Electronics                          | 2        | 2.25%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 1.12%   |
| XMOS                                         | 1        | 1.12%   |
| Microdia                                     | 1        | 1.12%   |
| Loongson Technology                          | 1        | 1.12%   |
| BEHRINGER International                      | 1        | 1.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 7.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6        | 6.25%   |
| Intel Comet Lake PCH-V cAVS                                                       | 5        | 5.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5        | 5.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 4.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 4.17%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 3.13%   |
| Nvidia GF116 High Definition Audio Controller                                     | 3        | 3.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 3.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 3.13%   |
| Nvidia High Definition Audio Controller                                           | 2        | 2.08%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 2.08%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 2.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2        | 2.08%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 2.08%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 2.08%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 2.08%   |
| AMD FCH Azalia Controller                                                         | 2        | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 2.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 2.08%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 2.08%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 1        | 1.04%   |
| XMOS iFi (by AMR) HD USB Audio                                                    | 1        | 1.04%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 1.04%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 1.04%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1        | 1.04%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 1.04%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1        | 1.04%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 1.04%   |
| Microdia USB Audio                                                                | 1        | 1.04%   |
| Loongson Technology HDA (High Definition Audio) Controller                        | 1        | 1.04%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 1.04%   |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1        | 1.04%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 1.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 34.62%  |
| Unknown             | 5        | 19.23%  |
| Corsair             | 3        | 11.54%  |
| G.Skill             | 2        | 7.69%   |
| Team                | 1        | 3.85%   |
| Samsung Electronics | 1        | 3.85%   |
| Ramaxel Technology  | 1        | 3.85%   |
| Nanya Technology    | 1        | 3.85%   |
| CSX                 | 1        | 3.85%   |
| Apacer              | 1        | 3.85%   |
| A-DATA Technology   | 1        | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Kingston RAM TF32D4U2S1MEH-8 8GB DIMM DDR4 3200MT/s        | 2        | 7.14%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                  | 1        | 3.57%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s               | 1        | 3.57%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                     | 1        | 3.57%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1        | 3.57%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s         | 1        | 3.57%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s        | 1        | 3.57%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s        | 1        | 3.57%   |
| Ramaxel RAM RMSA3230KE68H9F213 4096MB SODIMM DDR4 2133MT/s | 1        | 3.57%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s         | 1        | 3.57%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s             | 1        | 3.57%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 3.57%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s       | 1        | 3.57%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s        | 1        | 3.57%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s        | 1        | 3.57%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s     | 1        | 3.57%   |
| Kingston RAM BRAP1G48GB16C1600 8192MB DIMM DDR3 1600MT/s   | 1        | 3.57%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 3.57%   |
| Kingston RAM 99U5403-034.A00LF 4GB DIMM 1333MT/s           | 1        | 3.57%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s         | 1        | 3.57%   |
| G.Skill RAM F3-14900CL10-8GBXL 8GB DIMM DDR3 1867MT/s      | 1        | 3.57%   |
| CSX RAM V01D3LF4GB26826813 4GB DIMM DDR3 1333MT/s          | 1        | 3.57%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s       | 1        | 3.57%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s      | 1        | 3.57%   |
| Corsair RAM CMK16GX4M1B3000C15 16GB DIMM DDR4 3400MT/s     | 1        | 3.57%   |
| Apacer RAM 76.C346G.C850C 8192MB SODIMM DDR3 1600MT/s      | 1        | 3.57%   |
| A-DATA RAM DDR4 2400 2OZ 8GB DIMM DDR4 3000MT/s            | 1        | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 13       | 54.17%  |
| DDR3    | 9        | 37.5%   |
| SDRAM   | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 22       | 91.67%  |
| SODIMM | 2        | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 66.67%  |
| 4096  | 4        | 16.67%  |
| 32768 | 1        | 4.17%   |
| 16384 | 1        | 4.17%   |
| 2048  | 1        | 4.17%   |
| 1024  | 1        | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1867    | 3        | 11.54%  |
| 1600    | 3        | 11.54%  |
| 3466    | 2        | 7.69%   |
| 3400    | 2        | 7.69%   |
| 3200    | 2        | 7.69%   |
| 2667    | 2        | 7.69%   |
| 2133    | 2        | 7.69%   |
| 1333    | 2        | 7.69%   |
| 3800    | 1        | 3.85%   |
| 3500    | 1        | 3.85%   |
| 3000    | 1        | 3.85%   |
| 2800    | 1        | 3.85%   |
| 2400    | 1        | 3.85%   |
| 1067    | 1        | 3.85%   |
| 667     | 1        | 3.85%   |
| Unknown | 1        | 3.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1        | 100%    |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 5        | 55.56%  |
| Microdia               | 1        | 11.11%  |
| HD 2MP WEBCAM          | 1        | 11.11%  |
| Generalplus Technology | 1        | 11.11%  |
| Arkmicro Technologies  | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech Webcam C270          | 3        | 33.33%  |
| Microdia Integrated_Webcam_HD | 1        | 11.11%  |
| Logitech Webcam C200          | 1        | 11.11%  |
| Logitech HD Pro Webcam C920   | 1        | 11.11%  |
| HD 2MP WEBCAM HD 2MP WEBCAM   | 1        | 11.11%  |
| Generalplus GENERAL WEBCAM    | 1        | 11.11%  |
| Arkmicro USB2.0 PC CAMERA     | 1        | 11.11%  |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 49       | 94.23%  |
| 1     | 2        | 3.85%   |
| 2     | 1        | 1.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 3        | 75%     |
| Graphics card | 1        | 25%     |

