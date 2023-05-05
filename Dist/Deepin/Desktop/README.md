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

Total: 90

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Maximus Z790 HERO       | [a22f7f4309](https://linux-hardware.org/?probe=a22f7f4309) | Mar 13, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [d4f6b075c4](https://linux-hardware.org/?probe=d4f6b075c4) | Mar 13, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [44a3952ccf](https://linux-hardware.org/?probe=44a3952ccf) | Feb 15, 2023 |
| OEM           | KX-01 V1.0                  | [75d9dc396c](https://linux-hardware.org/?probe=75d9dc396c) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [510b879339](https://linux-hardware.org/?probe=510b879339) | Jan 26, 2023 |
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
| Deepin         | 14       | 23.33%  |
| Deepin 20      | 10       | 16.67%  |
| UOS 20         | 8        | 13.33%  |
| Deepin 20 beta | 4        | 6.67%   |
| Deepin 15.9.2  | 4        | 6.67%   |
| Deepin 20.1    | 3        | 5%      |
| Deepin 15.11   | 3        | 5%      |
| Deepin 23      | 2        | 3.33%   |
| Deepin 20.6    | 2        | 3.33%   |
| Deepin 20.3    | 2        | 3.33%   |
| Deepin 20.2.2  | 2        | 3.33%   |
| Deepin 15.10.1 | 2        | 3.33%   |
| Deepin 20.2.4  | 1        | 1.67%   |
| Deepin 20.2.3  | 1        | 1.67%   |
| Deepin 20.2    | 1        | 1.67%   |
| Deepin 15.7    | 1        | 1.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Deepin | 56       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.4.70-amd64-desktop      | 7        | 11.67%  |
| 4.15.0-30deepin-generic   | 7        | 11.67%  |
| 4.15.0-29deepin-generic   | 7        | 11.67%  |
| 5.4.50-amd64-desktop      | 6        | 10%     |
| 5.3.0-3-amd64             | 6        | 10%     |
| 5.10.60-amd64-desktop     | 3        | 5%      |
| 5.10.36-amd64-desktop     | 3        | 5%      |
| 4.19.0-amd64-desktop      | 3        | 5%      |
| 5.7.7-amd64-desktop       | 2        | 3.33%   |
| 5.10.29-amd64-desktop     | 2        | 3.33%   |
| 5.10.18-amd64-desktop     | 2        | 3.33%   |
| 6.1.12-1-liquorix-amd64   | 1        | 1.67%   |
| 5.8.14-amd64-desktop      | 1        | 1.67%   |
| 5.5.4-xanmod3             | 1        | 1.67%   |
| 5.18.17-amd64-desktop-hwe | 1        | 1.67%   |
| 5.15.24-amd64-desktop     | 1        | 1.67%   |
| 5.14.0-rc3-amd64-desktop  | 1        | 1.67%   |
| 5.10.50-amd64-desktop     | 1        | 1.67%   |
| 5.10.5-amd64-desktop+     | 1        | 1.67%   |
| 5.10.101-amd64-desktop    | 1        | 1.67%   |
| 5.10.0-amd64-desktop      | 1        | 1.67%   |
| 4.19.90-1.lns7.2.mips64el | 1        | 1.67%   |
| 4.19.0-5-amd64            | 1        | 1.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 14       | 23.33%  |
| 5.4.70   | 7        | 11.67%  |
| 5.4.50   | 6        | 10%     |
| 5.3.0    | 6        | 10%     |
| 4.19.0   | 4        | 6.67%   |
| 5.10.60  | 3        | 5%      |
| 5.10.36  | 3        | 5%      |
| 5.7.7    | 2        | 3.33%   |
| 5.10.29  | 2        | 3.33%   |
| 5.10.18  | 2        | 3.33%   |
| 6.1.12   | 1        | 1.67%   |
| 5.8.14   | 1        | 1.67%   |
| 5.5.4    | 1        | 1.67%   |
| 5.18.17  | 1        | 1.67%   |
| 5.15.24  | 1        | 1.67%   |
| 5.14.0   | 1        | 1.67%   |
| 5.10.50  | 1        | 1.67%   |
| 5.10.5   | 1        | 1.67%   |
| 5.10.101 | 1        | 1.67%   |
| 5.10.0   | 1        | 1.67%   |
| 4.19.90  | 1        | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15    | 14       | 24.56%  |
| 5.4     | 12       | 21.05%  |
| 5.10    | 12       | 21.05%  |
| 5.3     | 6        | 10.53%  |
| 4.19    | 5        | 8.77%   |
| 5.7     | 2        | 3.51%   |
| 6.1     | 1        | 1.75%   |
| 5.8     | 1        | 1.75%   |
| 5.5     | 1        | 1.75%   |
| 5.18    | 1        | 1.75%   |
| 5.15    | 1        | 1.75%   |
| 5.14    | 1        | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 55       | 98.21%  |
| mips64 | 1        | 1.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Deepin  | 48       | 84.21%  |
| Unknown | 8        | 14.04%  |
| MATE    | 1        | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 54       | 96.43%  |
| Wayland | 1        | 1.79%   |
| Tty     | 1        | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 53.57%  |
| LightDM | 15       | 26.79%  |
| TDM     | 11       | 19.64%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 12       | 20.69%  |
| zh_CN   | 10       | 17.24%  |
| pt_BR   | 10       | 17.24%  |
| Unknown | 8        | 13.79%  |
| es_ES   | 7        | 12.07%  |
| de_DE   | 4        | 6.9%    |
| ru_RU   | 1        | 1.72%   |
| pl_PL   | 1        | 1.72%   |
| lt_LT   | 1        | 1.72%   |
| it_IT   | 1        | 1.72%   |
| id_ID   | 1        | 1.72%   |
| fr_FR   | 1        | 1.72%   |
| en_GB   | 1        | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 32       | 57.14%  |
| EFI  | 24       | 42.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 52       | 92.86%  |
| Unknown | 4        | 7.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 48.28%  |
| GPT     | 22       | 37.93%  |
| MBR     | 8        | 13.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 71.93%  |
| Yes       | 16       | 28.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 80.7%   |
| Yes       | 11       | 19.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 16       | 28.57%  |
| Gigabyte Technology        | 9        | 16.07%  |
| TSINGHUA TONGFANG COMPUTER | 4        | 7.14%   |
| Dell                       | 4        | 7.14%   |
| ASRock                     | 4        | 7.14%   |
| MSI                        | 3        | 5.36%   |
| Semp Toshiba               | 2        | 3.57%   |
| Positivo                   | 2        | 3.57%   |
| Lenovo                     | 2        | 3.57%   |
| ECS                        | 2        | 3.57%   |
| OEM                        | 1        | 1.79%   |
| Medion                     | 1        | 1.79%   |
| Loongson                   | 1        | 1.79%   |
| Huanan                     | 1        | 1.79%   |
| Hewlett-Packard            | 1        | 1.79%   |
| Foxconn                    | 1        | 1.79%   |
| AMD                        | 1        | 1.79%   |
| Unknown                    | 1        | 1.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500          | 4        | 7.14%   |
| Semp Toshiba STI                         | 2        | 3.57%   |
| ECS H81H3-M4                             | 2        | 3.57%   |
| ASUS All Series                          | 2        | 3.57%   |
| Positivo POS-PQ45AU                      | 1        | 1.79%   |
| Positivo POS-EINM70CS                    | 1        | 1.79%   |
| OEM ZXE CRB                              | 1        | 1.79%   |
| MSI MS-7C83                              | 1        | 1.79%   |
| MSI MS-7851                              | 1        | 1.79%   |
| MSI MS-7681                              | 1        | 1.79%   |
| Medion MS-7728                           | 1        | 1.79%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev     | 1        | 1.79%   |
| Lenovo ThinkCentre M910t-N000 10N9CTO1WW | 1        | 1.79%   |
| Lenovo ThinkCentre M82 2929AJ2           | 1        | 1.79%   |
| Huanan X99-8M-F V1.1                     | 1        | 1.79%   |
| HP 260-P020il                            | 1        | 1.79%   |
| Gigabyte Z77-DS3H                        | 1        | 1.79%   |
| Gigabyte Z170X-Gaming 7                  | 1        | 1.79%   |
| Gigabyte H81M-D2V                        | 1        | 1.79%   |
| Gigabyte H110M-H                         | 1        | 1.79%   |
| Gigabyte GA-78LMT-USB3                   | 1        | 1.79%   |
| Gigabyte B550M DS3H                      | 1        | 1.79%   |
| Gigabyte B365M D3H                       | 1        | 1.79%   |
| Gigabyte B360M AORUS Gaming 3            | 1        | 1.79%   |
| Gigabyte 990XA-UD3                       | 1        | 1.79%   |
| Foxconn p7-1430br                        | 1        | 1.79%   |
| Dell Vostro 230                          | 1        | 1.79%   |
| Dell OptiPlex 9020                       | 1        | 1.79%   |
| Dell OptiPlex 760                        | 1        | 1.79%   |
| Dell Inspiron One 2020                   | 1        | 1.79%   |
| ASUS TUF Gaming B550M-PLUS               | 1        | 1.79%   |
| ASUS ROG Maximus Z790 HERO               | 1        | 1.79%   |
| ASUS ROG Maximus XII HERO                | 1        | 1.79%   |
| ASUS PRIME B450M-GAMING/BR               | 1        | 1.79%   |
| ASUS PRIME B350-PLUS                     | 1        | 1.79%   |
| ASUS PRIME A320M-K                       | 1        | 1.79%   |
| ASUS P8H77-M PRO                         | 1        | 1.79%   |
| ASUS P8H61-MX                            | 1        | 1.79%   |
| ASUS P8H61-M LX2 R2.0                    | 1        | 1.79%   |
| ASUS P5Q-E                               | 1        | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500      | 4        | 7.14%   |
| ASUS PRIME                           | 3        | 5.36%   |
| Semp Toshiba STI                     | 2        | 3.57%   |
| Lenovo ThinkCentre                   | 2        | 3.57%   |
| ECS H81H3-M4                         | 2        | 3.57%   |
| Dell OptiPlex                        | 2        | 3.57%   |
| ASUS ROG                             | 2        | 3.57%   |
| ASUS All                             | 2        | 3.57%   |
| Positivo POS-PQ45AU                  | 1        | 1.79%   |
| Positivo POS-EINM70CS                | 1        | 1.79%   |
| OEM ZXE                              | 1        | 1.79%   |
| MSI MS-7C83                          | 1        | 1.79%   |
| MSI MS-7851                          | 1        | 1.79%   |
| MSI MS-7681                          | 1        | 1.79%   |
| Medion MS-7728                       | 1        | 1.79%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev | 1        | 1.79%   |
| Huanan X99-8M-F                      | 1        | 1.79%   |
| HP 260-P020il                        | 1        | 1.79%   |
| Gigabyte Z77-DS3H                    | 1        | 1.79%   |
| Gigabyte Z170X-Gaming                | 1        | 1.79%   |
| Gigabyte H81M-D2V                    | 1        | 1.79%   |
| Gigabyte H110M-H                     | 1        | 1.79%   |
| Gigabyte GA-78LMT-USB3               | 1        | 1.79%   |
| Gigabyte B550M                       | 1        | 1.79%   |
| Gigabyte B365M                       | 1        | 1.79%   |
| Gigabyte B360M                       | 1        | 1.79%   |
| Gigabyte 990XA-UD3                   | 1        | 1.79%   |
| Foxconn p7-1430br                    | 1        | 1.79%   |
| Dell Vostro                          | 1        | 1.79%   |
| Dell Inspiron                        | 1        | 1.79%   |
| ASUS TUF                             | 1        | 1.79%   |
| ASUS P8H77-M                         | 1        | 1.79%   |
| ASUS P8H61-MX                        | 1        | 1.79%   |
| ASUS P8H61-M                         | 1        | 1.79%   |
| ASUS P5Q-E                           | 1        | 1.79%   |
| ASUS P5G41T-M                        | 1        | 1.79%   |
| ASUS M5A78L-M                        | 1        | 1.79%   |
| ASUS K30AD                           | 1        | 1.79%   |
| ASUS H110I-PLUS                      | 1        | 1.79%   |
| ASRock Z77                           | 1        | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 8        | 14.29%  |
| 2021 | 6        | 10.71%  |
| 2020 | 6        | 10.71%  |
| 2012 | 6        | 10.71%  |
| 2011 | 6        | 10.71%  |
| 2018 | 5        | 8.93%   |
| 2014 | 5        | 8.93%   |
| 2017 | 3        | 5.36%   |
| 2016 | 3        | 5.36%   |
| 2009 | 3        | 5.36%   |
| 2010 | 2        | 3.57%   |
| 2022 | 1        | 1.79%   |
| 2019 | 1        | 1.79%   |
| 2008 | 1        | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 56       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 54       | 96.43%  |
| Enabled  | 2        | 3.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 56       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 20       | 35.71%  |
| 8.01-16.0   | 15       | 26.79%  |
| 4.01-8.0    | 10       | 17.86%  |
| 3.01-4.0    | 7        | 12.5%   |
| 32.01-64.0  | 2        | 3.57%   |
| 64.01-256.0 | 1        | 1.79%   |
| 1.01-2.0    | 1        | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 17       | 27.42%  |
| 4.01-8.0  | 16       | 25.81%  |
| 2.01-3.0  | 14       | 22.58%  |
| 3.01-4.0  | 9        | 14.52%  |
| 0.51-1.0  | 5        | 8.06%   |
| 8.01-16.0 | 1        | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 42.11%  |
| 2      | 20       | 35.09%  |
| 4      | 7        | 12.28%  |
| 3      | 5        | 8.77%   |
| 5      | 1        | 1.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 65.52%  |
| Yes       | 20       | 34.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 56       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 64.29%  |
| Yes       | 20       | 35.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 66.07%  |
| Yes       | 19       | 33.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Brazil      | 15       | 26.79%  |
| China       | 10       | 17.86%  |
| USA         | 6        | 10.71%  |
| Germany     | 3        | 5.36%   |
| Panama      | 2        | 3.57%   |
| Mexico      | 2        | 3.57%   |
| Argentina   | 2        | 3.57%   |
| Ukraine     | 1        | 1.79%   |
| UK          | 1        | 1.79%   |
| Spain       | 1        | 1.79%   |
| Russia      | 1        | 1.79%   |
| Romania     | 1        | 1.79%   |
| Poland      | 1        | 1.79%   |
| New Zealand | 1        | 1.79%   |
| Namibia     | 1        | 1.79%   |
| Lithuania   | 1        | 1.79%   |
| Italy       | 1        | 1.79%   |
| Indonesia   | 1        | 1.79%   |
| India       | 1        | 1.79%   |
| Colombia    | 1        | 1.79%   |
| Belgium     | 1        | 1.79%   |
| Bangladesh  | 1        | 1.79%   |
| Austria     | 1        | 1.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Sao Paulo               | 3        | 5.17%   |
| Nanjing                 | 3        | 5.17%   |
| Wuhan                   | 2        | 3.45%   |
| San Francisco           | 2        | 3.45%   |
| David                   | 2        | 3.45%   |
| Beijing                 | 2        | 3.45%   |
| Windhoek                | 1        | 1.72%   |
| Voluntari               | 1        | 1.72%   |
| Tychy                   | 1        | 1.72%   |
| Toluca                  | 1        | 1.72%   |
| Taua                    | 1        | 1.72%   |
| Surakarta               | 1        | 1.72%   |
| St Petersburg           | 1        | 1.72%   |
| Socorro                 | 1        | 1.72%   |
| Shanghai                | 1        | 1.72%   |
| Seesen                  | 1        | 1.72%   |
| Sao Caetano do Sul      | 1        | 1.72%   |
| Santa Clarita           | 1        | 1.72%   |
| Rome                    | 1        | 1.72%   |
| Rio de Janeiro          | 1        | 1.72%   |
| Ransart                 | 1        | 1.72%   |
| Para de Minas           | 1        | 1.72%   |
| Olinda                  | 1        | 1.72%   |
| Niterói                | 1        | 1.72%   |
| Naucalpan               | 1        | 1.72%   |
| Mesa                    | 1        | 1.72%   |
| Medellín               | 1        | 1.72%   |
| Marília                | 1        | 1.72%   |
| Lviv                    | 1        | 1.72%   |
| Leipzig                 | 1        | 1.72%   |
| Krakow                  | 1        | 1.72%   |
| Klagenfurt              | 1        | 1.72%   |
| Jaboatao dos Guararapes | 1        | 1.72%   |
| Itapevi                 | 1        | 1.72%   |
| Guangzhou               | 1        | 1.72%   |
| Grand Bourg             | 1        | 1.72%   |
| Gilly                   | 1        | 1.72%   |
| Getxo                   | 1        | 1.72%   |
| Fort Lauderdale         | 1        | 1.72%   |
| Elektrėnai             | 1        | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 19       | 25     | 18.45%  |
| Seagate               | 16       | 19     | 15.53%  |
| Samsung Electronics   | 8        | 9      | 7.77%   |
| Toshiba               | 7        | 8      | 6.8%    |
| SanDisk               | 7        | 11     | 6.8%    |
| Kingston              | 6        | 10     | 5.83%   |
| Crucial               | 4        | 5      | 3.88%   |
| China                 | 4        | 4      | 3.88%   |
| A-DATA Technology     | 4        | 5      | 3.88%   |
| Hitachi               | 3        | 3      | 2.91%   |
| FORESEE               | 3        | 3      | 2.91%   |
| SPCC                  | 2        | 2      | 1.94%   |
| Silicon Motion        | 2        | 2      | 1.94%   |
| Maxtor                | 2        | 4      | 1.94%   |
| Hewlett-Packard       | 2        | 3      | 1.94%   |
| Vaseky                | 1        | 1      | 0.97%   |
| Unknown               | 1        | 2      | 0.97%   |
| Realtek Semiconductor | 1        | 1      | 0.97%   |
| Phison                | 1        | 1      | 0.97%   |
| Mushkin               | 1        | 1      | 0.97%   |
| Maxtor 6              | 1        | 1      | 0.97%   |
| LaCie                 | 1        | 2      | 0.97%   |
| KingDian              | 1        | 1      | 0.97%   |
| KINGBANK              | 1        | 1      | 0.97%   |
| JMicron Technology    | 1        | 1      | 0.97%   |
| Intenso               | 1        | 2      | 0.97%   |
| Gigabyte Technology   | 1        | 1      | 0.97%   |
| Beijing Starblaze     | 1        | 1      | 0.97%   |
| Apacer                | 1        | 3      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB      | 3        | 2.7%    |
| WDC WD5000AAKX-003CA0 500GB         | 2        | 1.8%    |
| Toshiba DT01ACA200 2TB              | 2        | 1.8%    |
| Seagate ST1000DM003-1SB102 1TB      | 2        | 1.8%    |
| SanDisk SDSSDH3512G 512GB           | 2        | 1.8%    |
| Kingston SV300S37A120G 120GB SSD    | 2        | 1.8%    |
| FORESEE P900F256GBH                 | 2        | 1.8%    |
| WDC WDS500G2B0C-00PXH0 500GB        | 1        | 0.9%    |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1        | 0.9%    |
| WDC WDS120G1G0A-00SS50 120GB SSD    | 1        | 0.9%    |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 1        | 0.9%    |
| WDC WD80 0BEVE-11UYT0 80GB          | 1        | 0.9%    |
| WDC WD7500BPKX-22HPJT0 752GB        | 1        | 0.9%    |
| WDC WD6400AAKS-75A7B0 640GB         | 1        | 0.9%    |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 0.9%    |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 0.9%    |
| WDC WD5000AAKS-00A7B2 500GB         | 1        | 0.9%    |
| WDC WD5000AAJS-57TKA0 500GB         | 1        | 0.9%    |
| WDC WD3200AAKS-00VYA0 320GB         | 1        | 0.9%    |
| WDC WD20PURX-64P6ZY0 2TB            | 1        | 0.9%    |
| WDC WD20EARX-00PASB0 2TB            | 1        | 0.9%    |
| WDC WD1600AAJS-00L7A0 160GB         | 1        | 0.9%    |
| WDC WD10EZEX-22MFCA0 1TB            | 1        | 0.9%    |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 0.9%    |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 0.9%    |
| WDC WD10EFRX-68FYTN0 1TB            | 1        | 0.9%    |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 0.9%    |
| Vaseky V800/256G 256GB SSD          | 1        | 0.9%    |
| Unknown SD/MMC/MS PRO 249GB         | 1        | 0.9%    |
| Toshiba MQ01ABF050 500GB            | 1        | 0.9%    |
| Toshiba MQ01ABD075 752GB            | 1        | 0.9%    |
| Toshiba DT01ACA100 LENOVO 1TB       | 1        | 0.9%    |
| Toshiba DT01ACA100 1TB              | 1        | 0.9%    |
| Toshiba DT01ACA050 500GB            | 1        | 0.9%    |
| SPCC Solid State Disk 512GB         | 1        | 0.9%    |
| SPCC Solid State Disk 120GB         | 1        | 0.9%    |
| Silicon Motion NVME SSD 128GB       | 1        | 0.9%    |
| Silicon Motion DC 256G              | 1        | 0.9%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 0.9%    |
| Seagate ST500DM002-1BD142 500GB     | 1        | 0.9%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 21     | 32%     |
| Seagate             | 16       | 19     | 32%     |
| Toshiba             | 7        | 8      | 14%     |
| Hitachi             | 3        | 3      | 6%      |
| Samsung Electronics | 2        | 2      | 4%      |
| Maxtor              | 2        | 4      | 4%      |
| Unknown             | 1        | 2      | 2%      |
| Maxtor 6            | 1        | 1      | 2%      |
| JMicron Technology  | 1        | 1      | 2%      |
| Hewlett-Packard     | 1        | 2      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 7        | 11     | 18.92%  |
| Kingston            | 5        | 9      | 13.51%  |
| Samsung Electronics | 4        | 5      | 10.81%  |
| China               | 4        | 4      | 10.81%  |
| WDC                 | 3        | 3      | 8.11%   |
| Crucial             | 3        | 4      | 8.11%   |
| A-DATA Technology   | 3        | 4      | 8.11%   |
| SPCC                | 2        | 2      | 5.41%   |
| Vaseky              | 1        | 1      | 2.7%    |
| KingDian            | 1        | 1      | 2.7%    |
| KINGBANK            | 1        | 1      | 2.7%    |
| Intenso             | 1        | 2      | 2.7%    |
| Hewlett-Packard     | 1        | 1      | 2.7%    |
| Apacer              | 1        | 3      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 37       | 63     | 45.12%  |
| SSD     | 30       | 51     | 36.59%  |
| NVMe    | 14       | 16     | 17.07%  |
| Unknown | 1        | 2      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 51       | 109    | 73.91%  |
| NVMe | 14       | 16     | 20.29%  |
| SAS  | 4        | 7      | 5.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 39       | 71     | 54.93%  |
| 0.51-1.0   | 25       | 33     | 35.21%  |
| 1.01-2.0   | 7        | 10     | 9.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 16       | 28.07%  |
| 251-500        | 11       | 19.3%   |
| 501-1000       | 11       | 19.3%   |
| 101-250        | 9        | 15.79%  |
| 51-100         | 4        | 7.02%   |
| 2001-3000      | 3        | 5.26%   |
| More than 3000 | 2        | 3.51%   |
| Unknown        | 1        | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 101-250   | 16       | 26.23%  |
| 501-1000  | 12       | 19.67%  |
| 21-50     | 10       | 16.39%  |
| 1-20      | 9        | 14.75%  |
| 251-500   | 5        | 8.2%    |
| 51-100    | 4        | 6.56%   |
| 1001-2000 | 3        | 4.92%   |
| 2001-3000 | 1        | 1.64%   |
| Unknown   | 1        | 1.64%   |

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
| Works    | 31       | 56     | 46.27%  |
| Detected | 30       | 69     | 44.78%  |
| Malfunc  | 5        | 6      | 7.46%   |
| Failed   | 1        | 1      | 1.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 41       | 51.25%  |
| AMD                          | 11       | 13.75%  |
| ASMedia Technology           | 6        | 7.5%    |
| Silicon Motion               | 4        | 5%      |
| Marvell Technology Group     | 3        | 3.75%   |
| Shenzhen Longsys Electronics | 2        | 2.5%    |
| Samsung Electronics          | 2        | 2.5%    |
| Phison Electronics           | 2        | 2.5%    |
| Zhaoxin                      | 1        | 1.25%   |
| SanDisk                      | 1        | 1.25%   |
| Realtek Semiconductor        | 1        | 1.25%   |
| Nvidia                       | 1        | 1.25%   |
| Micron/Crucial Technology    | 1        | 1.25%   |
| Loongson Technology          | 1        | 1.25%   |
| Kingston Technology Company  | 1        | 1.25%   |
| JMicron Technology           | 1        | 1.25%   |
| Beijing Starblaze Technology | 1        | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 6.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 5.38%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 5.38%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 5.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 4.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 4.3%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 3.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 3.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 3.23%   |
| Shenzhen Longsys Non-Volatile memory controller                                         | 2        | 2.15%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 2.15%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.15%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.15%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G StorX AHCI Controller                            | 1        | 1.08%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.08%   |
| Samsung Electronics Non-Volatile memory controller                                      | 1        | 1.08%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 1.08%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 1.08%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.08%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.08%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.08%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.08%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 1.08%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 1.08%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.08%   |
| Loongson SATA AHCI Controller                                                           | 1        | 1.08%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1        | 1.08%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.08%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.08%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 47       | 63.51%  |
| NVMe | 13       | 17.57%  |
| IDE  | 12       | 16.22%  |
| RAID | 2        | 2.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 42       | 75%     |
| AMD          | 12       | 21.43%  |
| CentaurHauls | 1        | 1.79%   |
| Unknown      | 1        | 1.79%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz             | 4        | 7.14%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz         | 4        | 7.14%   |
| Intel Core i7-10700 CPU @ 2.90GHz            | 3        | 5.36%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 2        | 3.57%   |
| Intel Core i3-10100 CPU @ 3.60GHz            | 2        | 3.57%   |
| AMD Ryzen 5 3600 6-Core Processor            | 2        | 3.57%   |
| AMD FX-8320 Eight-Core Processor             | 2        | 3.57%   |
| Intel Xeon CPU E5450 @ 3.00GHz               | 1        | 1.79%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz          | 1        | 1.79%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz     | 1        | 1.79%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz  | 1        | 1.79%   |
| Intel Core i9-10900K CPU @ 3.70GHz           | 1        | 1.79%   |
| Intel Core i7-7700K CPU @ 4.20GHz            | 1        | 1.79%   |
| Intel Core i7-7700 CPU @ 3.60GHz             | 1        | 1.79%   |
| Intel Core i7-6700 CPU @ 3.40GHz             | 1        | 1.79%   |
| Intel Core i7-4790K CPU @ 4.00GHz            | 1        | 1.79%   |
| Intel Core i7-4770S CPU @ 3.10GHz            | 1        | 1.79%   |
| Intel Core i7-2600K CPU @ 3.40GHz            | 1        | 1.79%   |
| Intel Core i5-9400F CPU @ 2.90GHz            | 1        | 1.79%   |
| Intel Core i5-4690 CPU @ 3.50GHz             | 1        | 1.79%   |
| Intel Core i5-4460 CPU @ 3.20GHz             | 1        | 1.79%   |
| Intel Core i5-3550 CPU @ 3.30GHz             | 1        | 1.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 1        | 1.79%   |
| Intel Core i5-2300 CPU @ 2.80GHz             | 1        | 1.79%   |
| Intel Core i3-9100 CPU @ 3.60GHz             | 1        | 1.79%   |
| Intel Core i3-6100T CPU @ 3.20GHz            | 1        | 1.79%   |
| Intel Core i3-6100 CPU @ 3.70GHz             | 1        | 1.79%   |
| Intel Core i3-3240T CPU @ 2.90GHz            | 1        | 1.79%   |
| Intel Core i3-3220 CPU @ 3.30GHz             | 1        | 1.79%   |
| Intel Celeron J4125 CPU @ 2.00GHz            | 1        | 1.79%   |
| Intel Celeron CPU G530 @ 2.40GHz             | 1        | 1.79%   |
| Intel Celeron CPU G1840 @ 2.80GHz            | 1        | 1.79%   |
| Intel Celeron CPU 1007U @ 1.50GHz            | 1        | 1.79%   |
| Intel 13th Gen Core i9-13900K                | 1        | 1.79%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640A@2.6GHz | 1        | 1.79%   |
| AMD Ryzen 5 5600G with Radeon Graphics       | 1        | 1.79%   |
| AMD Ryzen 5 1600 Six-Core Processor          | 1        | 1.79%   |
| AMD Ryzen 3 1200 Quad-Core Processor         | 1        | 1.79%   |
| AMD FX-6100 Six-Core Processor               | 1        | 1.79%   |
| AMD FX-4130 Quad-Core Processor              | 1        | 1.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 15       | 26.79%  |
| Intel Core i3           | 7        | 12.5%   |
| Intel Core i5           | 6        | 10.71%  |
| Other                   | 4        | 7.14%   |
| Intel Core 2 Duo        | 4        | 7.14%   |
| Intel Celeron           | 4        | 7.14%   |
| AMD Ryzen 5             | 4        | 7.14%   |
| AMD FX                  | 4        | 7.14%   |
| Intel Xeon              | 2        | 3.57%   |
| Intel Pentium Silver    | 1        | 1.79%   |
| Intel Pentium Dual-Core | 1        | 1.79%   |
| Intel Core i9           | 1        | 1.79%   |
| AMD Ryzen 3             | 1        | 1.79%   |
| AMD C-60                | 1        | 1.79%   |
| AMD Athlon              | 1        | 1.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 29       | 51.79%  |
| 2      | 14       | 25%     |
| 6      | 6        | 10.71%  |
| 8      | 4        | 7.14%   |
| 24     | 1        | 1.79%   |
| 10     | 1        | 1.79%   |
| 3      | 1        | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 32       | 57.14%  |
| 1      | 24       | 42.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 51       | 91.07%  |
| Unknown        | 5        | 8.93%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 29.82%  |
| 0x306c3    | 7        | 12.28%  |
| 0x306a9    | 7        | 12.28%  |
| 0x1067a    | 4        | 7.02%   |
| 0xa0655    | 3        | 5.26%   |
| 0x906e9    | 2        | 3.51%   |
| 0x206a7    | 2        | 3.51%   |
| 0xb0671    | 1        | 1.75%   |
| 0xa0653    | 1        | 1.75%   |
| 0x906eb    | 1        | 1.75%   |
| 0x706a8    | 1        | 1.75%   |
| 0x506e3    | 1        | 1.75%   |
| 0x306f2    | 1        | 1.75%   |
| 0x0a50000d | 1        | 1.75%   |
| 0x08701013 | 1        | 1.75%   |
| 0x08001138 | 1        | 1.75%   |
| 0x08001137 | 1        | 1.75%   |
| 0x07026101 | 1        | 1.75%   |
| 0x06000822 | 1        | 1.75%   |
| 0x06000629 | 1        | 1.75%   |
| 0x06000626 | 1        | 1.75%   |
| 0x0500010d | 1        | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 9        | 16.07%  |
| Haswell          | 8        | 14.29%  |
| Penryn           | 6        | 10.71%  |
| CometLake        | 6        | 10.71%  |
| KabyLake         | 4        | 7.14%   |
| Skylake          | 3        | 5.36%   |
| SandyBridge      | 3        | 5.36%   |
| Unknown          | 3        | 5.36%   |
| Zen 2            | 2        | 3.57%   |
| Zen              | 2        | 3.57%   |
| Piledriver       | 2        | 3.57%   |
| Goldmont plus    | 2        | 3.57%   |
| Bulldozer        | 2        | 3.57%   |
| Zen 3            | 1        | 1.79%   |
| Jaguar           | 1        | 1.79%   |
| Bobcat           | 1        | 1.79%   |
| Alderlake Hybrid | 1        | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Nvidia              | 24       | 40%     |
| Intel               | 17       | 28.33%  |
| AMD                 | 17       | 28.33%  |
| Zhaoxin             | 1        | 1.67%   |
| Loongson Technology | 1        | 1.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 4.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 4.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 4.92%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 3.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.28%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 3.28%   |
| Intel HD Graphics 630                                                       | 2        | 3.28%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 3.28%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 3.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 3.28%   |
| Zhaoxin ZX-E C-960 GPU                                                      | 1        | 1.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.64%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.64%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.64%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.64%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.64%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.64%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.64%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.64%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.64%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.64%   |
| Nvidia GK104 [GeForce GTX 760 OEM]                                          | 1        | 1.64%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.64%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.64%   |
| Nvidia GF116 [GeForce GT 545]                                               | 1        | 1.64%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 1.64%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 1.64%   |
| Loongson Technology Vivante GPU (Graphics Processing Unit)                  | 1        | 1.64%   |
| Loongson Technology DC (Display Controller)                                 | 1        | 1.64%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 1.64%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.64%   |
| AMD Wrestler [Radeon HD 6290]                                               | 1        | 1.64%   |
| AMD Whistler LE [Radeon HD 6610M/7610M]                                     | 1        | 1.64%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.64%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 1        | 1.64%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Nvidia              | 23       | 41.07%  |
| 1 x AMD                 | 16       | 28.57%  |
| 1 x Intel               | 13       | 23.21%  |
| 1 x Zhaoxin             | 1        | 1.79%   |
| 1 x Loongson Technology | 1        | 1.79%   |
| Intel + Nvidia          | 1        | 1.79%   |
| Intel + AMD             | 1        | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 39       | 69.64%  |
| Proprietary | 14       | 25%     |
| Unknown     | 3        | 5.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 46.55%  |
| 1.01-2.0   | 13       | 22.41%  |
| 3.01-4.0   | 6        | 10.34%  |
| 7.01-8.0   | 4        | 6.9%    |
| 0.51-1.0   | 3        | 5.17%   |
| 0.01-0.5   | 3        | 5.17%   |
| 5.01-6.0   | 2        | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 19.64%  |
| Goldstar             | 7        | 12.5%   |
| Hewlett-Packard      | 5        | 8.93%   |
| ViewSonic            | 3        | 5.36%   |
| Dell                 | 3        | 5.36%   |
| Philips              | 2        | 3.57%   |
| Iiyama               | 2        | 3.57%   |
| BenQ                 | 2        | 3.57%   |
| AOC                  | 2        | 3.57%   |
| Ancor Communications | 2        | 3.57%   |
| Acer                 | 2        | 3.57%   |
| Xiaomi               | 1        | 1.79%   |
| Unknown              | 1        | 1.79%   |
| Toshiba              | 1        | 1.79%   |
| TFC                  | 1        | 1.79%   |
| SKY                  | 1        | 1.79%   |
| RTK                  | 1        | 1.79%   |
| Positivo             | 1        | 1.79%   |
| MSI                  | 1        | 1.79%   |
| Lenovo               | 1        | 1.79%   |
| HKC                  | 1        | 1.79%   |
| Hisense              | 1        | 1.79%   |
| Gateway              | 1        | 1.79%   |
| DTV                  | 1        | 1.79%   |
| BOE                  | 1        | 1.79%   |
| ASUSTek Computer     | 1        | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch              | 2        | 3.23%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                    | 2        | 3.23%   |
| Xiaomi Mi TV XMD0076 3840x2160 800x450mm 36.1-inch                      | 1        | 1.61%   |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch              | 1        | 1.61%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 1.61%   |
| Toshiba TV TSB0108 1360x768 576x324mm 26.0-inch                         | 1        | 1.61%   |
| TFC TF2411 TFC0238 1920x1080 527x296mm 23.8-inch                        | 1        | 1.61%   |
| SKY 24X1Q SKY2380 2560x1440 520x290mm 23.4-inch                         | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch    | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                         | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch     | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch    | 1        | 1.61%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch     | 1        | 1.61%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch       | 1        | 1.61%   |
| Samsung Electronics LCD Monitor SMS23A350H 1920x1080                    | 1        | 1.61%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1        | 1.61%   |
| Samsung Electronics LCD Monitor SAM0E90 1366x768 609x347mm 27.6-inch    | 1        | 1.61%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 1872x1053mm 84.6-inch | 1        | 1.61%   |
| Samsung Electronics LCD Monitor S24E390 1920x1080                       | 1        | 1.61%   |
| Samsung Electronics LCD Monitor S24E360 1920x1080                       | 1        | 1.61%   |
| Samsung Electronics LCD Monitor S24E310 3840x1080                       | 1        | 1.61%   |
| Samsung Electronics LCD Monitor S24E310                                 | 1        | 1.61%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                       | 1        | 1.61%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                    | 1        | 1.61%   |
| Philips FTV PHL04C2 1920x1080 1440x810mm 65.0-inch                      | 1        | 1.61%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                      | 1        | 1.61%   |
| MSI MAG271C MSI3FA6 1920x1080 598x336mm 27.0-inch                       | 1        | 1.61%   |
| Lenovo LEN T2324C LEN60F2 1920x1080 510x287mm 23.0-inch                 | 1        | 1.61%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                    | 1        | 1.61%   |
| Iiyama PL2792Q IVM662F 2560x1440 597x336mm 27.0-inch                    | 1        | 1.61%   |
| HKC 27E6QC HKC274F 2560x1440 597x336mm 27.0-inch                        | 1        | 1.61%   |
| Hisense LCD Monitor HDMI 1360x768                                       | 1        | 1.61%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch            | 1        | 1.61%   |
| Hewlett-Packard Compaq F191 HWP3177 1366x768 410x230mm 18.5-inch        | 1        | 1.61%   |
| Hewlett-Packard 2511 HWP293E 1920x1080 550x310mm 24.9-inch              | 1        | 1.61%   |
| Hewlett-Packard 2311x HWP293A 1920x1080 510x287mm 23.0-inch             | 1        | 1.61%   |
| Hewlett-Packard 22fw HPN3542 1920x1080 476x267mm 21.5-inch              | 1        | 1.61%   |
| Goldstar M227WD GSM56D4 1920x1080 476x268mm 21.5-inch                   | 1        | 1.61%   |
| Goldstar L196WTQ GSM4B50 1440x900 408x255mm 18.9-inch                   | 1        | 1.61%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch               | 1        | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 29       | 49.15%  |
| 2560x1440 (QHD)    | 6        | 10.17%  |
| 3840x2160 (4K)     | 4        | 6.78%   |
| 1600x900 (HD+)     | 4        | 6.78%   |
| 3840x1080          | 2        | 3.39%   |
| 1440x900 (WXGA+)   | 2        | 3.39%   |
| 1366x768 (WXGA)    | 2        | 3.39%   |
| 1360x768           | 2        | 3.39%   |
| Unknown            | 2        | 3.39%   |
| 2560x1600          | 1        | 1.69%   |
| 2288x1287          | 1        | 1.69%   |
| 1920x540           | 1        | 1.69%   |
| 1920x1200 (WUXGA)  | 1        | 1.69%   |
| 1680x1050 (WSXGA+) | 1        | 1.69%   |
| 1280x1024 (SXGA)   | 1        | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 14       | 23.73%  |
| 24      | 8        | 13.56%  |
| Unknown | 8        | 13.56%  |
| 27      | 6        | 10.17%  |
| 21      | 4        | 6.78%   |
| 20      | 3        | 5.08%   |
| 18      | 3        | 5.08%   |
| 84      | 2        | 3.39%   |
| 19      | 2        | 3.39%   |
| 142     | 1        | 1.69%   |
| 72      | 1        | 1.69%   |
| 65      | 1        | 1.69%   |
| 54      | 1        | 1.69%   |
| 32      | 1        | 1.69%   |
| 31      | 1        | 1.69%   |
| 25      | 1        | 1.69%   |
| 22      | 1        | 1.69%   |
| 12      | 1        | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 28       | 48.28%  |
| 401-500        | 13       | 22.41%  |
| Unknown        | 8        | 13.79%  |
| 1501-2000      | 3        | 5.17%   |
| 1001-1500      | 2        | 3.45%   |
| More than 2000 | 1        | 1.72%   |
| 701-800        | 1        | 1.72%   |
| 601-700        | 1        | 1.72%   |
| 201-300        | 1        | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 44       | 78.57%  |
| Unknown | 7        | 12.5%   |
| 16/10   | 4        | 7.14%   |
| 1.00    | 1        | 1.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 37.29%  |
| 151-200        | 9        | 15.25%  |
| Unknown        | 8        | 13.56%  |
| More than 1000 | 6        | 10.17%  |
| 301-350        | 6        | 10.17%  |
| 251-300        | 3        | 5.08%   |
| 351-500        | 2        | 3.39%   |
| 141-150        | 2        | 3.39%   |
| 61-70          | 1        | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 35       | 61.4%   |
| 101-120 | 8        | 14.04%  |
| Unknown | 8        | 14.04%  |
| 1-50    | 4        | 7.02%   |
| 161-240 | 1        | 1.75%   |
| 121-160 | 1        | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 85.96%  |
| 2     | 8        | 14.04%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 37       | 48.68%  |
| Intel                    | 16       | 21.05%  |
| Qualcomm Atheros         | 4        | 5.26%   |
| TP-Link                  | 3        | 3.95%   |
| Broadcom                 | 3        | 3.95%   |
| MediaTek                 | 2        | 2.63%   |
| Xiaomi                   | 1        | 1.32%   |
| Unknown                  | 1        | 1.32%   |
| Ralink Technology        | 1        | 1.32%   |
| Ralink                   | 1        | 1.32%   |
| NXP Semiconductors       | 1        | 1.32%   |
| Nvidia                   | 1        | 1.32%   |
| NetGear                  | 1        | 1.32%   |
| Marvell Technology Group | 1        | 1.32%   |
| Loongson Technology      | 1        | 1.32%   |
| IMC Networks             | 1        | 1.32%   |
| Aquantia                 | 1        | 1.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 37.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 2.33%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.33%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 2.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.33%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.16%   |
| Unknown Network controller                                        | 1        | 1.16%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 1.16%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 1.16%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 1.16%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 1.16%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 1.16%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 1        | 1.16%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.16%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.16%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 1.16%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.16%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.16%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.16%   |
| NetGear A6210                                                     | 1        | 1.16%   |
| MediaTek PRESIDENT_GOLD_10                                        | 1        | 1.16%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter               | 1        | 1.16%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.16%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.16%   |
| Loongson Gigabit Ethernet Controller                              | 1        | 1.16%   |
| Intel Ethernet Controller I226-V                                  | 1        | 1.16%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.16%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.16%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.16%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 6        | 30%     |
| Intel                 | 4        | 20%     |
| TP-Link               | 3        | 15%     |
| Qualcomm Atheros      | 2        | 10%     |
| Ralink Technology     | 1        | 5%      |
| Ralink                | 1        | 5%      |
| NetGear               | 1        | 5%      |
| MediaTek              | 1        | 5%      |
| IMC Networks          | 1        | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 5%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 5%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1        | 5%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1        | 5%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 5%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1        | 5%      |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)  | 1        | 5%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 5%      |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 5%      |
| Ralink MT7601U Wireless Adapter                            | 1        | 5%      |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1        | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 5%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1        | 5%      |
| NetGear A6210                                              | 1        | 5%      |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter        | 1        | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 5%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1        | 5%      |
| Intel Comet Lake PCH CNVi WiFi                             | 1        | 5%      |
| Intel 700 Series Chipset Family Wi-Fi                      | 1        | 5%      |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]       | 1        | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 37       | 59.68%  |
| Intel                    | 14       | 22.58%  |
| Broadcom                 | 3        | 4.84%   |
| Qualcomm Atheros         | 2        | 3.23%   |
| Xiaomi                   | 1        | 1.61%   |
| Nvidia                   | 1        | 1.61%   |
| MediaTek                 | 1        | 1.61%   |
| Marvell Technology Group | 1        | 1.61%   |
| Loongson Technology      | 1        | 1.61%   |
| Aquantia                 | 1        | 1.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 3.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 3.13%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.13%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 3.13%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 3.13%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 3.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.56%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.56%   |
| MediaTek PRESIDENT_GOLD_10                                        | 1        | 1.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.56%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.56%   |
| Loongson Gigabit Ethernet Controller                              | 1        | 1.56%   |
| Intel Ethernet Controller I226-V                                  | 1        | 1.56%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.56%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.56%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.56%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.56%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 1.56%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.56%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 56       | 71.79%  |
| WiFi     | 20       | 25.64%  |
| Modem    | 1        | 1.28%   |
| Unknown  | 1        | 1.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 47       | 83.93%  |
| WiFi     | 9        | 16.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 70.18%  |
| 2     | 13       | 22.81%  |
| 3     | 3        | 5.26%   |
| 4     | 1        | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 94.64%  |
| Yes  | 3        | 5.36%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 10       | 50%     |
| Intel                           | 4        | 20%     |
| Realtek Semiconductor           | 1        | 5%      |
| Qualcomm Atheros Communications | 1        | 5%      |
| MediaTek                        | 1        | 5%      |
| Lite-On Technology              | 1        | 5%      |
| Dynex                           | 1        | 5%      |
| ASUSTek Computer                | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 10       | 50%     |
| Realtek Bluetooth Radio                                  | 1        | 5%      |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 5%      |
| MediaTek BT                                              | 1        | 5%      |
| Lite-On Bluetooth Device                                 | 1        | 5%      |
| Intel Wireless-AC 3168 Bluetooth                         | 1        | 5%      |
| Intel Bluetooth wireless interface                       | 1        | 5%      |
| Intel Bluetooth Device                                   | 1        | 5%      |
| Intel AX201 Bluetooth                                    | 1        | 5%      |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 5%      |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 42       | 43.75%  |
| Nvidia                                       | 23       | 23.96%  |
| AMD                                          | 22       | 22.92%  |
| C-Media Electronics                          | 2        | 2.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 1.04%   |
| Zhaoxin                                      | 1        | 1.04%   |
| XMOS                                         | 1        | 1.04%   |
| Microdia                                     | 1        | 1.04%   |
| Loongson Technology                          | 1        | 1.04%   |
| BEHRINGER International                      | 1        | 1.04%   |
| ASUSTek Computer                             | 1        | 1.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 7        | 6.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 6.6%    |
| Intel Comet Lake PCH-V cAVS                                                       | 5        | 4.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5        | 4.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 3.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 3.77%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 2.83%   |
| Nvidia GF116 High Definition Audio Controller                                     | 3        | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 2.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 2.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 2.83%   |
| Nvidia High Definition Audio Controller                                           | 2        | 1.89%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 1.89%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 1.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2        | 1.89%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 1.89%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 1.89%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 1.89%   |
| AMD FCH Azalia Controller                                                         | 2        | 1.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 1.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.89%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.89%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 1        | 0.94%   |
| Zhaoxin ZX-E High Definition Audio Controller                                     | 1        | 0.94%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller          | 1        | 0.94%   |
| XMOS iFi (by AMR) HD USB Audio                                                    | 1        | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 0.94%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.94%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 0.94%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1        | 0.94%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 0.94%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1        | 0.94%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.94%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 0.94%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 0.94%   |
| Microdia USB Audio                                                                | 1        | 0.94%   |
| Loongson Technology HDA (High Definition Audio) Controller                        | 1        | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston                           | 9        | 31.03%  |
| Unknown                            | 5        | 17.24%  |
| Corsair                            | 3        | 10.34%  |
| Samsung Electronics                | 2        | 6.9%    |
| G.Skill                            | 2        | 6.9%    |
| Team                               | 1        | 3.45%   |
| Ramaxel Technology                 | 1        | 3.45%   |
| Nanya Technology                   | 1        | 3.45%   |
| KINGBANK                           | 1        | 3.45%   |
| Kimtigo Semiconductor (HK) Limited | 1        | 3.45%   |
| CSX                                | 1        | 3.45%   |
| Apacer                             | 1        | 3.45%   |
| A-DATA Technology                  | 1        | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Kingston RAM TF32D4U2S1MEH-8 8GB DIMM DDR4 3200MT/s        | 2        | 6.25%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                  | 1        | 3.13%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s               | 1        | 3.13%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                     | 1        | 3.13%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1        | 3.13%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s         | 1        | 3.13%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s         | 1        | 3.13%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 3.13%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s        | 1        | 3.13%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s        | 1        | 3.13%   |
| Ramaxel RAM RMSA3230KE68H9F213 4096MB SODIMM DDR4 2133MT/s | 1        | 3.13%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s         | 1        | 3.13%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s             | 1        | 3.13%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 3.13%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s          | 1        | 3.13%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s        | 1        | 3.13%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s        | 1        | 3.13%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s        | 1        | 3.13%   |
| Kingston RAM BRAP1G48GB16C1600 8192MB DIMM DDR3 1600MT/s   | 1        | 3.13%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 3.13%   |
| Kingston RAM 99U5403-034.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 3.13%   |
| KINGBANK RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 3.13%   |
| Kimtigo (HK) Limited RAM Module 8192MB DIMM DDR4 2666MT/s  | 1        | 3.13%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s         | 1        | 3.13%   |
| G.Skill RAM F3-14900CL10-8GBXL 8GB DIMM DDR3 1867MT/s      | 1        | 3.13%   |
| CSX RAM V01D3LF4GB26826813 4GB DIMM DDR3 1333MT/s          | 1        | 3.13%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s       | 1        | 3.13%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s   | 1        | 3.13%   |
| Corsair RAM CMK16GX4M1B3000C15 16GB DIMM DDR4 3400MT/s     | 1        | 3.13%   |
| Apacer RAM 76.C346G.C850C 8192MB SODIMM DDR3 1600MT/s      | 1        | 3.13%   |
| A-DATA RAM DDR4 2400 2OZ 8GB DIMM DDR4 3000MT/s            | 1        | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 15       | 55.56%  |
| DDR3    | 10       | 37.04%  |
| SDRAM   | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 25       | 92.59%  |
| SODIMM | 2        | 7.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 19       | 67.86%  |
| 4096  | 5        | 17.86%  |
| 32768 | 1        | 3.57%   |
| 16384 | 1        | 3.57%   |
| 2048  | 1        | 3.57%   |
| 1024  | 1        | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 13.33%  |
| 2133    | 3        | 10%     |
| 1867    | 3        | 10%     |
| 3466    | 2        | 6.67%   |
| 3400    | 2        | 6.67%   |
| 3200    | 2        | 6.67%   |
| 2667    | 2        | 6.67%   |
| 2666    | 2        | 6.67%   |
| 1333    | 2        | 6.67%   |
| 3800    | 1        | 3.33%   |
| 3500    | 1        | 3.33%   |
| 3000    | 1        | 3.33%   |
| 2800    | 1        | 3.33%   |
| 2400    | 1        | 3.33%   |
| 1067    | 1        | 3.33%   |
| 667     | 1        | 3.33%   |
| Unknown | 1        | 3.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 1        | 50%     |
| Hewlett-Packard | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1        | 50%     |
| HP Deskjet 3520 series                        | 1        | 50%     |

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
| Logitech               | 6        | 60%     |
| Microdia               | 1        | 10%     |
| Generalplus Technology | 1        | 10%     |
| Arkmicro Technologies  | 1        | 10%     |
| 2M UVC CAMERA          | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Logitech Webcam C270                | 4        | 40%     |
| Microdia Integrated_Webcam_HD       | 1        | 10%     |
| Logitech Webcam C200                | 1        | 10%     |
| Logitech HD Pro Webcam C920         | 1        | 10%     |
| Generalplus GENERAL WEBCAM          | 1        | 10%     |
| Arkmicro USB2.0 PC CAMERA           | 1        | 10%     |
| 2M UVC CAMERA NexiGo N60 FHD Webcam | 1        | 10%     |

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
| 0     | 51       | 91.07%  |
| 1     | 4        | 7.14%   |
| 2     | 1        | 1.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 4        | 66.67%  |
| Graphics card | 2        | 33.33%  |

