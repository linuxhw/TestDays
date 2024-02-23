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

Total: 108

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MAG X570 TOMAHAWK WIFI      | [8b1e8e6fe4](https://linux-hardware.org/?probe=8b1e8e6fe4) | Jan 08, 2024 |
| Dell          | 0XPDFK A01                  | [6990382d8a](https://linux-hardware.org/?probe=6990382d8a) | Dec 14, 2023 |
| Dell          | 0XPDFK A01                  | [da80cd5bbd](https://linux-hardware.org/?probe=da80cd5bbd) | Dec 14, 2023 |
| Dell          | 0XR1GT A00                  | [17b5d35090](https://linux-hardware.org/?probe=17b5d35090) | Nov 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [12d30e16b4](https://linux-hardware.org/?probe=12d30e16b4) | Nov 07, 2023 |
| Dell          | 0XR1GT A00                  | [f01a35c9a7](https://linux-hardware.org/?probe=f01a35c9a7) | Nov 06, 2023 |
| Intel         | DX58SO AAE29331-504         | [33d7713b52](https://linux-hardware.org/?probe=33d7713b52) | Oct 21, 2023 |
| Intel         | DX58SO AAE29331-504         | [afe13c52df](https://linux-hardware.org/?probe=afe13c52df) | Oct 11, 2023 |
| Dell          | 0NW6H5 A00                  | [e337e05dff](https://linux-hardware.org/?probe=e337e05dff) | Oct 08, 2023 |
| Dell          | 0NW6H5 A00                  | [dc4ec4e72a](https://linux-hardware.org/?probe=dc4ec4e72a) | Oct 02, 2023 |
| TSINGHUA T... | B460M-HDV                   | [f82a030bce](https://linux-hardware.org/?probe=f82a030bce) | Aug 30, 2023 |
| TSINGHUA T... | B460M-HDV                   | [815cb59889](https://linux-hardware.org/?probe=815cb59889) | Aug 16, 2023 |
| TSINGHUA T... | B460-N2                     | [f7f87f7a07](https://linux-hardware.org/?probe=f7f87f7a07) | Aug 16, 2023 |
| HP            | 18EA                        | [d6e48a99e7](https://linux-hardware.org/?probe=d6e48a99e7) | Jun 08, 2023 |
| MSI           | A55M-E35                    | [fa4eba3787](https://linux-hardware.org/?probe=fa4eba3787) | Jun 08, 2023 |
| Intel         | DH77EB AAG39073-304         | [8310aaaa78](https://linux-hardware.org/?probe=8310aaaa78) | May 27, 2023 |
| Intel         | DH77EB AAG39073-304         | [86545c89c0](https://linux-hardware.org/?probe=86545c89c0) | May 27, 2023 |
| Koloe         | X58                         | [7c1acc3b84](https://linux-hardware.org/?probe=7c1acc3b84) | May 08, 2023 |
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
| Deepin         | 14       | 19.44%  |
| UOS 20         | 10       | 13.89%  |
| Deepin 23      | 10       | 13.89%  |
| Deepin 20      | 10       | 13.89%  |
| Deepin 20 beta | 4        | 5.56%   |
| Deepin 15.9.2  | 4        | 5.56%   |
| Deepin 20.1    | 3        | 4.17%   |
| Deepin 15.11   | 3        | 4.17%   |
| Deepin 20.9    | 2        | 2.78%   |
| Deepin 20.6    | 2        | 2.78%   |
| Deepin 20.3    | 2        | 2.78%   |
| Deepin 20.2.2  | 2        | 2.78%   |
| Deepin 15.10.1 | 2        | 2.78%   |
| Deepin 20.2.4  | 1        | 1.39%   |
| Deepin 20.2.3  | 1        | 1.39%   |
| Deepin 20.2    | 1        | 1.39%   |
| Deepin 15.7    | 1        | 1.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Deepin | 68       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.4.70-amd64-desktop      | 7        | 9.72%   |
| 4.15.0-30deepin-generic   | 7        | 9.72%   |
| 4.15.0-29deepin-generic   | 7        | 9.72%   |
| 5.4.50-amd64-desktop      | 6        | 8.33%   |
| 5.3.0-3-amd64             | 6        | 8.33%   |
| 5.15.45-amd64-desktop     | 3        | 4.17%   |
| 5.10.60-amd64-desktop     | 3        | 4.17%   |
| 5.10.36-amd64-desktop     | 3        | 4.17%   |
| 5.10.0-amd64-desktop      | 3        | 4.17%   |
| 4.19.0-amd64-desktop      | 3        | 4.17%   |
| 6.3.0-rc4-amd64-exton     | 2        | 2.78%   |
| 6.1.32-amd64-desktop-hwe  | 2        | 2.78%   |
| 5.7.7-amd64-desktop       | 2        | 2.78%   |
| 5.15.77-amd64-desktop     | 2        | 2.78%   |
| 5.10.29-amd64-desktop     | 2        | 2.78%   |
| 5.10.18-amd64-desktop     | 2        | 2.78%   |
| 6.1.12-1-liquorix-amd64   | 1        | 1.39%   |
| 6.1.11-amd64-desktop-hwe  | 1        | 1.39%   |
| 5.8.14-amd64-desktop      | 1        | 1.39%   |
| 5.5.4-xanmod3             | 1        | 1.39%   |
| 5.18.17-amd64-desktop-hwe | 1        | 1.39%   |
| 5.15.24-amd64-desktop     | 1        | 1.39%   |
| 5.14.0-rc3-amd64-desktop  | 1        | 1.39%   |
| 5.10.50-amd64-desktop     | 1        | 1.39%   |
| 5.10.5-amd64-desktop+     | 1        | 1.39%   |
| 5.10.101-amd64-desktop    | 1        | 1.39%   |
| 4.19.90-1.lns7.2.mips64el | 1        | 1.39%   |
| 4.19.0-5-amd64            | 1        | 1.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 14       | 19.44%  |
| 5.4.70   | 7        | 9.72%   |
| 5.4.50   | 6        | 8.33%   |
| 5.3.0    | 6        | 8.33%   |
| 4.19.0   | 4        | 5.56%   |
| 5.15.45  | 3        | 4.17%   |
| 5.10.60  | 3        | 4.17%   |
| 5.10.36  | 3        | 4.17%   |
| 5.10.0   | 3        | 4.17%   |
| 6.3.0    | 2        | 2.78%   |
| 6.1.32   | 2        | 2.78%   |
| 5.7.7    | 2        | 2.78%   |
| 5.15.77  | 2        | 2.78%   |
| 5.10.29  | 2        | 2.78%   |
| 5.10.18  | 2        | 2.78%   |
| 6.1.12   | 1        | 1.39%   |
| 6.1.11   | 1        | 1.39%   |
| 5.8.14   | 1        | 1.39%   |
| 5.5.4    | 1        | 1.39%   |
| 5.18.17  | 1        | 1.39%   |
| 5.15.24  | 1        | 1.39%   |
| 5.14.0   | 1        | 1.39%   |
| 5.10.50  | 1        | 1.39%   |
| 5.10.5   | 1        | 1.39%   |
| 5.10.101 | 1        | 1.39%   |
| 4.19.90  | 1        | 1.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 14       | 20.29%  |
| 4.15    | 14       | 20.29%  |
| 5.4     | 12       | 17.39%  |
| 5.3     | 6        | 8.7%    |
| 5.15    | 6        | 8.7%    |
| 4.19    | 5        | 7.25%   |
| 6.1     | 4        | 5.8%    |
| 6.3     | 2        | 2.9%    |
| 5.7     | 2        | 2.9%    |
| 5.8     | 1        | 1.45%   |
| 5.5     | 1        | 1.45%   |
| 5.18    | 1        | 1.45%   |
| 5.14    | 1        | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 67       | 98.53%  |
| mips64 | 1        | 1.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Deepin  | 53       | 76.81%  |
| Unknown | 9        | 13.04%  |
| DDE     | 6        | 8.7%    |
| MATE    | 1        | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 62       | 91.18%  |
| Wayland | 4        | 5.88%   |
| Tty     | 2        | 2.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 51.47%  |
| LightDM | 22       | 32.35%  |
| TDM     | 11       | 16.18%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 18       | 25.71%  |
| zh_CN   | 13       | 18.57%  |
| pt_BR   | 11       | 15.71%  |
| es_ES   | 8        | 11.43%  |
| Unknown | 8        | 11.43%  |
| de_DE   | 4        | 5.71%   |
| tr_TR   | 1        | 1.43%   |
| ru_RU   | 1        | 1.43%   |
| pl_PL   | 1        | 1.43%   |
| lt_LT   | 1        | 1.43%   |
| it_IT   | 1        | 1.43%   |
| id_ID   | 1        | 1.43%   |
| fr_FR   | 1        | 1.43%   |
| en_GB   | 1        | 1.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 35       | 51.47%  |
| EFI  | 33       | 48.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 63       | 92.65%  |
| Unknown | 4        | 5.88%   |
| Btrfs   | 1        | 1.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 32       | 45.71%  |
| GPT     | 29       | 41.43%  |
| MBR     | 9        | 12.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 71.01%  |
| Yes       | 20       | 28.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 78.26%  |
| Yes       | 15       | 21.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 17       | 25%     |
| Gigabyte Technology        | 9        | 13.24%  |
| TSINGHUA TONGFANG COMPUTER | 7        | 10.29%  |
| Dell                       | 7        | 10.29%  |
| MSI                        | 4        | 5.88%   |
| ASRock                     | 4        | 5.88%   |
| Semp Toshiba               | 2        | 2.94%   |
| Positivo                   | 2        | 2.94%   |
| Lenovo                     | 2        | 2.94%   |
| Intel                      | 2        | 2.94%   |
| Hewlett-Packard            | 2        | 2.94%   |
| ECS                        | 2        | 2.94%   |
| OEM                        | 1        | 1.47%   |
| Medion                     | 1        | 1.47%   |
| Loongson                   | 1        | 1.47%   |
| Koloe                      | 1        | 1.47%   |
| Huanan                     | 1        | 1.47%   |
| Foxconn                    | 1        | 1.47%   |
| AMD                        | 1        | 1.47%   |
| Unknown                    | 1        | 1.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500          | 7        | 10.29%  |
| Semp Toshiba STI                         | 2        | 2.94%   |
| ECS H81H3-M4                             | 2        | 2.94%   |
| ASUS All Series                          | 2        | 2.94%   |
| Positivo POS-PQ45AU                      | 1        | 1.47%   |
| Positivo POS-EINM70CS                    | 1        | 1.47%   |
| OEM ZXE CRB                              | 1        | 1.47%   |
| MSI MS-7C84                              | 1        | 1.47%   |
| MSI MS-7C83                              | 1        | 1.47%   |
| MSI MS-7851                              | 1        | 1.47%   |
| MSI MS-7681                              | 1        | 1.47%   |
| Medion MS-7728                           | 1        | 1.47%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev     | 1        | 1.47%   |
| Lenovo ThinkCentre M910t-N000 10N9CTO1WW | 1        | 1.47%   |
| Lenovo ThinkCentre M82 2929AJ2           | 1        | 1.47%   |
| Koloe Thurley                            | 1        | 1.47%   |
| Intel DX58SO AAE29331-504                | 1        | 1.47%   |
| Intel DH77EB AAG39073-304                | 1        | 1.47%   |
| Huanan X99-8M-F V1.1                     | 1        | 1.47%   |
| HP ProOne 400 G1 AiO                     | 1        | 1.47%   |
| HP 260-P020il                            | 1        | 1.47%   |
| Gigabyte Z77-DS3H                        | 1        | 1.47%   |
| Gigabyte Z170X-Gaming 7                  | 1        | 1.47%   |
| Gigabyte H81M-D2V                        | 1        | 1.47%   |
| Gigabyte H110M-H                         | 1        | 1.47%   |
| Gigabyte GA-78LMT-USB3                   | 1        | 1.47%   |
| Gigabyte B550M DS3H                      | 1        | 1.47%   |
| Gigabyte B365M D3H                       | 1        | 1.47%   |
| Gigabyte B360M AORUS Gaming 3            | 1        | 1.47%   |
| Gigabyte 990XA-UD3                       | 1        | 1.47%   |
| Foxconn p7-1430br                        | 1        | 1.47%   |
| Dell Vostro 270                          | 1        | 1.47%   |
| Dell Vostro 230                          | 1        | 1.47%   |
| Dell Precision WorkStation T3500         | 1        | 1.47%   |
| Dell OptiPlex 9020                       | 1        | 1.47%   |
| Dell OptiPlex 760                        | 1        | 1.47%   |
| Dell OptiPlex 7050                       | 1        | 1.47%   |
| Dell Inspiron One 2020                   | 1        | 1.47%   |
| ASUS TUF Gaming B550M-PLUS               | 1        | 1.47%   |
| ASUS ROG STRIX X570-E GAMING             | 1        | 1.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500      | 7        | 10.29%  |
| Dell OptiPlex                        | 3        | 4.41%   |
| ASUS ROG                             | 3        | 4.41%   |
| ASUS PRIME                           | 3        | 4.41%   |
| Semp Toshiba STI                     | 2        | 2.94%   |
| Lenovo ThinkCentre                   | 2        | 2.94%   |
| ECS H81H3-M4                         | 2        | 2.94%   |
| Dell Vostro                          | 2        | 2.94%   |
| ASUS All                             | 2        | 2.94%   |
| Positivo POS-PQ45AU                  | 1        | 1.47%   |
| Positivo POS-EINM70CS                | 1        | 1.47%   |
| OEM ZXE                              | 1        | 1.47%   |
| MSI MS-7C84                          | 1        | 1.47%   |
| MSI MS-7C83                          | 1        | 1.47%   |
| MSI MS-7851                          | 1        | 1.47%   |
| MSI MS-7681                          | 1        | 1.47%   |
| Medion MS-7728                       | 1        | 1.47%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev | 1        | 1.47%   |
| Koloe Thurley                        | 1        | 1.47%   |
| Intel DX58SO                         | 1        | 1.47%   |
| Intel DH77EB                         | 1        | 1.47%   |
| Huanan X99-8M-F                      | 1        | 1.47%   |
| HP ProOne                            | 1        | 1.47%   |
| HP 260-P020il                        | 1        | 1.47%   |
| Gigabyte Z77-DS3H                    | 1        | 1.47%   |
| Gigabyte Z170X-Gaming                | 1        | 1.47%   |
| Gigabyte H81M-D2V                    | 1        | 1.47%   |
| Gigabyte H110M-H                     | 1        | 1.47%   |
| Gigabyte GA-78LMT-USB3               | 1        | 1.47%   |
| Gigabyte B550M                       | 1        | 1.47%   |
| Gigabyte B365M                       | 1        | 1.47%   |
| Gigabyte B360M                       | 1        | 1.47%   |
| Gigabyte 990XA-UD3                   | 1        | 1.47%   |
| Foxconn p7-1430br                    | 1        | 1.47%   |
| Dell Precision                       | 1        | 1.47%   |
| Dell Inspiron                        | 1        | 1.47%   |
| ASUS TUF                             | 1        | 1.47%   |
| ASUS P8H77-M                         | 1        | 1.47%   |
| ASUS P8H61-MX                        | 1        | 1.47%   |
| ASUS P8H61-M                         | 1        | 1.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 9        | 13.24%  |
| 2013 | 9        | 13.24%  |
| 2012 | 8        | 11.76%  |
| 2021 | 7        | 10.29%  |
| 2011 | 6        | 8.82%   |
| 2018 | 5        | 7.35%   |
| 2014 | 5        | 7.35%   |
| 2017 | 4        | 5.88%   |
| 2009 | 4        | 5.88%   |
| 2016 | 3        | 4.41%   |
| 2010 | 3        | 4.41%   |
| 2019 | 2        | 2.94%   |
| 2022 | 1        | 1.47%   |
| 2015 | 1        | 1.47%   |
| 2008 | 1        | 1.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 68       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 65       | 95.59%  |
| Enabled  | 3        | 4.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 23       | 33.82%  |
| 8.01-16.0   | 18       | 26.47%  |
| 4.01-8.0    | 12       | 17.65%  |
| 3.01-4.0    | 7        | 10.29%  |
| 32.01-64.0  | 5        | 7.35%   |
| 24.01-32.0  | 1        | 1.47%   |
| 64.01-256.0 | 1        | 1.47%   |
| 1.01-2.0    | 1        | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 20       | 27.03%  |
| 1.01-2.0  | 18       | 24.32%  |
| 2.01-3.0  | 17       | 22.97%  |
| 3.01-4.0  | 10       | 13.51%  |
| 0.51-1.0  | 6        | 8.11%   |
| 8.01-16.0 | 3        | 4.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 28       | 40.58%  |
| 2      | 25       | 36.23%  |
| 4      | 7        | 10.14%  |
| 3      | 7        | 10.14%  |
| 5      | 2        | 2.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 67.14%  |
| Yes       | 23       | 32.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 68       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 63.24%  |
| Yes       | 25       | 36.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 66.18%  |
| Yes       | 23       | 33.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Brazil      | 16       | 23.53%  |
| China       | 14       | 20.59%  |
| USA         | 7        | 10.29%  |
| Germany     | 3        | 4.41%   |
| Panama      | 2        | 2.94%   |
| Mexico      | 2        | 2.94%   |
| Colombia    | 2        | 2.94%   |
| Argentina   | 2        | 2.94%   |
| Ukraine     | 1        | 1.47%   |
| UK          | 1        | 1.47%   |
| Turkey      | 1        | 1.47%   |
| Spain       | 1        | 1.47%   |
| Russia      | 1        | 1.47%   |
| Romania     | 1        | 1.47%   |
| Poland      | 1        | 1.47%   |
| New Zealand | 1        | 1.47%   |
| Namibia     | 1        | 1.47%   |
| Lithuania   | 1        | 1.47%   |
| Kenya       | 1        | 1.47%   |
| Italy       | 1        | 1.47%   |
| Indonesia   | 1        | 1.47%   |
| India       | 1        | 1.47%   |
| Iceland     | 1        | 1.47%   |
| Belgium     | 1        | 1.47%   |
| Bangladesh  | 1        | 1.47%   |
| Austria     | 1        | 1.47%   |
| Australia   | 1        | 1.47%   |
| Albania     | 1        | 1.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Wuhan              | 4        | 5.71%   |
| Sao Paulo          | 3        | 4.29%   |
| Nanjing            | 3        | 4.29%   |
| Beijing            | 3        | 4.29%   |
| San Francisco      | 2        | 2.86%   |
| David              | 2        | 2.86%   |
| Windhoek           | 1        | 1.43%   |
| Voluntari          | 1        | 1.43%   |
| Tychy              | 1        | 1.43%   |
| Toluca             | 1        | 1.43%   |
| Tirana             | 1        | 1.43%   |
| Taua               | 1        | 1.43%   |
| Sydney             | 1        | 1.43%   |
| Surakarta          | 1        | 1.43%   |
| St Petersburg      | 1        | 1.43%   |
| Socorro            | 1        | 1.43%   |
| Shanghai           | 1        | 1.43%   |
| Seesen             | 1        | 1.43%   |
| Sao Caetano do Sul | 1        | 1.43%   |
| Santo André       | 1        | 1.43%   |
| Santa Clarita      | 1        | 1.43%   |
| Rome               | 1        | 1.43%   |
| Rio de Janeiro     | 1        | 1.43%   |
| Reykjavik          | 1        | 1.43%   |
| Ransart            | 1        | 1.43%   |
| Qingdao            | 1        | 1.43%   |
| Para de Minas      | 1        | 1.43%   |
| Olinda             | 1        | 1.43%   |
| Oerlinghausen      | 1        | 1.43%   |
| Niterói           | 1        | 1.43%   |
| Naucalpan          | 1        | 1.43%   |
| Mesa               | 1        | 1.43%   |
| Medellín          | 1        | 1.43%   |
| Marília           | 1        | 1.43%   |
| Lviv               | 1        | 1.43%   |
| Leipzig            | 1        | 1.43%   |
| Krakow             | 1        | 1.43%   |
| Konya              | 1        | 1.43%   |
| Klagenfurt         | 1        | 1.43%   |
| Kericho            | 1        | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 26       | 33     | 20.47%  |
| Seagate               | 19       | 22     | 14.96%  |
| Samsung Electronics   | 9        | 10     | 7.09%   |
| Toshiba               | 8        | 9      | 6.3%    |
| SanDisk               | 8        | 12     | 6.3%    |
| Kingston              | 8        | 13     | 6.3%    |
| Crucial               | 5        | 6      | 3.94%   |
| Hitachi               | 4        | 4      | 3.15%   |
| China                 | 4        | 4      | 3.15%   |
| A-DATA Technology     | 4        | 5      | 3.15%   |
| Phison                | 3        | 3      | 2.36%   |
| FORESEE               | 3        | 3      | 2.36%   |
| SPCC                  | 2        | 2      | 1.57%   |
| Silicon Motion        | 2        | 2      | 1.57%   |
| Maxtor                | 2        | 4      | 1.57%   |
| Hewlett-Packard       | 2        | 3      | 1.57%   |
| Vaseky                | 1        | 1      | 0.79%   |
| Unknown               | 1        | 2      | 0.79%   |
| Realtek Semiconductor | 1        | 1      | 0.79%   |
| Phytium               | 1        | 1      | 0.79%   |
| Phison Electronics    | 1        | 2      | 0.79%   |
| Mushkin               | 1        | 1      | 0.79%   |
| Maxtor 6              | 1        | 1      | 0.79%   |
| LaCie                 | 1        | 2      | 0.79%   |
| KingDian              | 1        | 1      | 0.79%   |
| KINGBANK              | 1        | 1      | 0.79%   |
| JMicron Technology    | 1        | 1      | 0.79%   |
| Intenso               | 1        | 2      | 0.79%   |
| Intel                 | 1        | 1      | 0.79%   |
| HGST                  | 1        | 1      | 0.79%   |
| Gigabyte Technology   | 1        | 1      | 0.79%   |
| Beijing Starblaze     | 1        | 1      | 0.79%   |
| Apacer                | 1        | 3      | 0.79%   |
| ADATA Technology      | 1        | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB   | 4        | 2.92%   |
| Phison ESO256GMFCH-E3C-2 256GB   | 3        | 2.19%   |
| WDC WDS120G1G0A-00SS50 120GB SSD | 2        | 1.46%   |
| WDC WD5000AAKX-003CA0 500GB      | 2        | 1.46%   |
| WDC WD10EZEX-22MFCA0 1TB         | 2        | 1.46%   |
| Toshiba DT01ACA200 2TB           | 2        | 1.46%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 1.46%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 1.46%   |
| SanDisk SDSSDH3512G 512GB        | 2        | 1.46%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 1.46%   |
| Kingston SA400S37480G 480GB SSD  | 2        | 1.46%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 1.46%   |
| FORESEE P900F256GBH              | 2        | 1.46%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.73%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.73%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1        | 0.73%   |
| WDC WD80 0BEVE-11UYT0 80GB       | 1        | 0.73%   |
| WDC WD7500BPKX-22HPJT0 752GB     | 1        | 0.73%   |
| WDC WD6400AAKS-75A7B0 640GB      | 1        | 0.73%   |
| WDC WD5000LPLX-66ZNTT1 500GB     | 1        | 0.73%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.73%   |
| WDC WD5000AAKX-00U6AA0 500GB     | 1        | 0.73%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.73%   |
| WDC WD5000AAKS-00A7B2 500GB      | 1        | 0.73%   |
| WDC WD5000AAJS-57TKA0 500GB      | 1        | 0.73%   |
| WDC WD3200AAKS-61L9A0 320GB      | 1        | 0.73%   |
| WDC WD3200AAKS-00VYA0 320GB      | 1        | 0.73%   |
| WDC WD30EZRX-22D8PB0 3TB         | 1        | 0.73%   |
| WDC WD20PURX-64P6ZY0 2TB         | 1        | 0.73%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.73%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1        | 0.73%   |
| WDC WD1600AAJS-00L7A0 160GB      | 1        | 0.73%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 0.73%   |
| WDC WD10EZEX-08M2NA0 1TB         | 1        | 0.73%   |
| WDC WD10EZEX-00WN4A0 1TB         | 1        | 0.73%   |
| WDC WD10EFRX-68FYTN0 1TB         | 1        | 0.73%   |
| WDC WD10EARS-00Y5B1 1TB          | 1        | 0.73%   |
| Vaseky V800/256G 256GB           | 1        | 0.73%   |
| Unknown SD/MMC/MS PRO 256GB      | 1        | 0.73%   |
| Toshiba MQ01ABF050 500GB         | 1        | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 28     | 35.48%  |
| Seagate             | 19       | 22     | 30.65%  |
| Toshiba             | 8        | 9      | 12.9%   |
| Hitachi             | 4        | 4      | 6.45%   |
| Samsung Electronics | 2        | 2      | 3.23%   |
| Maxtor              | 2        | 4      | 3.23%   |
| Unknown             | 1        | 2      | 1.61%   |
| Maxtor 6            | 1        | 1      | 1.61%   |
| JMicron Technology  | 1        | 1      | 1.61%   |
| HGST                | 1        | 1      | 1.61%   |
| Hewlett-Packard     | 1        | 2      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 8        | 12     | 18.6%   |
| Kingston            | 7        | 12     | 16.28%  |
| WDC                 | 4        | 4      | 9.3%    |
| Samsung Electronics | 4        | 5      | 9.3%    |
| Crucial             | 4        | 5      | 9.3%    |
| China               | 4        | 4      | 9.3%    |
| A-DATA Technology   | 3        | 4      | 6.98%   |
| SPCC                | 2        | 2      | 4.65%   |
| Vaseky              | 1        | 1      | 2.33%   |
| KingDian            | 1        | 1      | 2.33%   |
| KINGBANK            | 1        | 1      | 2.33%   |
| Intenso             | 1        | 2      | 2.33%   |
| Intel               | 1        | 1      | 2.33%   |
| Hewlett-Packard     | 1        | 1      | 2.33%   |
| Apacer              | 1        | 3      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 48       | 76     | 46.15%  |
| SSD     | 36       | 58     | 34.62%  |
| NVMe    | 19       | 23     | 18.27%  |
| Unknown | 1        | 2      | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 64       | 129    | 73.56%  |
| NVMe | 19       | 23     | 21.84%  |
| SAS  | 4        | 7      | 4.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 48       | 83     | 53.93%  |
| 0.51-1.0   | 33       | 40     | 37.08%  |
| 1.01-2.0   | 7        | 10     | 7.87%   |
| 2.01-3.0   | 1        | 1      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 19       | 27.54%  |
| 501-1000       | 14       | 20.29%  |
| 251-500        | 12       | 17.39%  |
| 101-250        | 12       | 17.39%  |
| 2001-3000      | 4        | 5.8%    |
| 51-100         | 4        | 5.8%    |
| More than 3000 | 3        | 4.35%   |
| Unknown        | 1        | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 101-250   | 16       | 21.92%  |
| 501-1000  | 15       | 20.55%  |
| 21-50     | 13       | 17.81%  |
| 1-20      | 10       | 13.7%   |
| 251-500   | 9        | 12.33%  |
| 51-100    | 4        | 5.48%   |
| 1001-2000 | 3        | 4.11%   |
| 2001-3000 | 2        | 2.74%   |
| Unknown   | 1        | 1.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000LPLX-66ZNTT1 500GB       | 1        | 1      | 10%     |
| WDC WD3200AAKS-61L9A0 320GB        | 1        | 1      | 10%     |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1      | 10%     |
| Toshiba MK8052GSX 80GB             | 1        | 1      | 10%     |
| Seagate ST3750528AS 752GB          | 1        | 1      | 10%     |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 10%     |
| Seagate ST1000DL002-9TT153 1TB     | 1        | 1      | 10%     |
| Samsung Electronics HD502HJ 500GB  | 1        | 1      | 10%     |
| Samsung Electronics HD250HJ 250GB  | 1        | 1      | 10%     |
| Hitachi HDP725050GLA360 500GB      | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 33.33%  |
| Seagate             | 2        | 3      | 22.22%  |
| Samsung Electronics | 2        | 2      | 22.22%  |
| Toshiba             | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 33.33%  |
| Seagate             | 2        | 3      | 22.22%  |
| Samsung Electronics | 2        | 2      | 22.22%  |
| Toshiba             | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 10     | 100%    |

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
| Works    | 38       | 66     | 46.34%  |
| Detected | 34       | 82     | 41.46%  |
| Malfunc  | 9        | 10     | 10.98%  |
| Failed   | 1        | 1      | 1.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 51       | 51.52%  |
| AMD                          | 13       | 13.13%  |
| ASMedia Technology           | 6        | 6.06%   |
| Phison Electronics           | 5        | 5.05%   |
| Silicon Motion               | 4        | 4.04%   |
| Marvell Technology Group     | 4        | 4.04%   |
| Samsung Electronics          | 3        | 3.03%   |
| Shenzhen Longsys Electronics | 2        | 2.02%   |
| Beijing Starblaze Technology | 2        | 2.02%   |
| Zhaoxin                      | 1        | 1.01%   |
| SanDisk                      | 1        | 1.01%   |
| Realtek Semiconductor        | 1        | 1.01%   |
| Nvidia                       | 1        | 1.01%   |
| Micron/Crucial Technology    | 1        | 1.01%   |
| Loongson Technology          | 1        | 1.01%   |
| Kingston Technology Company  | 1        | 1.01%   |
| JMicron Technology           | 1        | 1.01%   |
| ADATA Technology             | 1        | 1.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8        | 7.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 6.14%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 6.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 5.26%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 6        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 4.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.51%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 2.63%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 2.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 2.63%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 2.63%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.63%   |
| Shenzhen Longsys FORESEE P900 BGA NVMe SSD (DRAM-less)                                  | 2        | 1.75%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 1.75%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 1.75%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.75%   |
| Beijing Starblaze STAR1200C NVMe SSD                                                    | 2        | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.75%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G/KH-40000/KX-7000 StorX AHCI Controller           | 1        | 0.88%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.88%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 1        | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.88%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 1        | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.88%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1        | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.88%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.88%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.88%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.88%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 0.88%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.88%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 0.88%   |
| Loongson SATA AHCI Controller                                                           | 1        | 0.88%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                          | 1        | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 57       | 62.64%  |
| NVMe | 18       | 19.78%  |
| IDE  | 14       | 15.38%  |
| RAID | 2        | 2.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 52       | 76.47%  |
| AMD          | 14       | 20.59%  |
| CentaurHauls | 1        | 1.47%   |
| Unknown      | 1        | 1.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-10700 CPU @ 2.90GHz           | 6        | 8.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 5.88%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 5.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 2.94%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 2.94%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 2.94%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 2.94%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 2.94%   |
| Intel Xeon CPU W3503 @ 2.40GHz              | 1        | 1.47%   |
| Intel Xeon CPU L5640 @ 2.27GHz              | 1        | 1.47%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 1.47%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 1.47%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 1.47%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.47%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 1.47%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.47%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.47%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.47%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.47%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 1.47%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.47%   |
| Intel Core i7 CPU 975 @ 3.33GHz             | 1        | 1.47%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.47%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.47%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.47%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.47%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.47%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 1        | 1.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.47%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 1        | 1.47%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 1.47%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 1        | 1.47%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.47%   |
| Intel Core i3-4160T CPU @ 3.10GHz           | 1        | 1.47%   |
| Intel Core i3-3240T CPU @ 2.90GHz           | 1        | 1.47%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 1.47%   |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 1.47%   |
| Intel Celeron CPU G1840 @ 2.80GHz           | 1        | 1.47%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 1        | 1.47%   |
| Intel 13th Gen Core i9-13900K               | 1        | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 19       | 27.94%  |
| Intel Core i3           | 9        | 13.24%  |
| Intel Core i5           | 8        | 11.76%  |
| Other                   | 4        | 5.88%   |
| Intel Xeon              | 4        | 5.88%   |
| Intel Core 2 Duo        | 4        | 5.88%   |
| Intel Celeron           | 4        | 5.88%   |
| AMD Ryzen 5             | 4        | 5.88%   |
| AMD FX                  | 4        | 5.88%   |
| AMD Ryzen 9             | 2        | 2.94%   |
| Intel Pentium Silver    | 1        | 1.47%   |
| Intel Pentium Dual-Core | 1        | 1.47%   |
| Intel Core i9           | 1        | 1.47%   |
| AMD Ryzen 3             | 1        | 1.47%   |
| AMD C-60                | 1        | 1.47%   |
| AMD Athlon              | 1        | 1.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 32       | 47.06%  |
| 2      | 17       | 25%     |
| 8      | 7        | 10.29%  |
| 6      | 7        | 10.29%  |
| 24     | 1        | 1.47%   |
| 16     | 1        | 1.47%   |
| 12     | 1        | 1.47%   |
| 10     | 1        | 1.47%   |
| 3      | 1        | 1.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 68       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 41       | 60.29%  |
| 1      | 27       | 39.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 63       | 92.65%  |
| Unknown        | 5        | 7.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 28.99%  |
| 0x306a9    | 9        | 13.04%  |
| 0x306c3    | 8        | 11.59%  |
| 0xa0655    | 5        | 7.25%   |
| 0x1067a    | 4        | 5.8%    |
| 0x906e9    | 3        | 4.35%   |
| 0x206a7    | 2        | 2.9%    |
| 0xb0671    | 1        | 1.45%   |
| 0xa0653    | 1        | 1.45%   |
| 0x906eb    | 1        | 1.45%   |
| 0x706a8    | 1        | 1.45%   |
| 0x506e3    | 1        | 1.45%   |
| 0x306f2    | 1        | 1.45%   |
| 0x206c2    | 1        | 1.45%   |
| 0x0a50000d | 1        | 1.45%   |
| 0x0a201016 | 1        | 1.45%   |
| 0x08701021 | 1        | 1.45%   |
| 0x08701013 | 1        | 1.45%   |
| 0x08001138 | 1        | 1.45%   |
| 0x08001137 | 1        | 1.45%   |
| 0x07026101 | 1        | 1.45%   |
| 0x06000822 | 1        | 1.45%   |
| 0x06000629 | 1        | 1.45%   |
| 0x06000626 | 1        | 1.45%   |
| 0x0500010d | 1        | 1.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 11       | 16.18%  |
| Haswell          | 9        | 13.24%  |
| CometLake        | 9        | 13.24%  |
| Penryn           | 6        | 8.82%   |
| KabyLake         | 5        | 7.35%   |
| Zen 2            | 3        | 4.41%   |
| Skylake          | 3        | 4.41%   |
| SandyBridge      | 3        | 4.41%   |
| Unknown          | 3        | 4.41%   |
| Zen 3            | 2        | 2.94%   |
| Zen              | 2        | 2.94%   |
| Piledriver       | 2        | 2.94%   |
| Nehalem          | 2        | 2.94%   |
| Goldmont plus    | 2        | 2.94%   |
| Bulldozer        | 2        | 2.94%   |
| Westmere         | 1        | 1.47%   |
| Jaguar           | 1        | 1.47%   |
| Bobcat           | 1        | 1.47%   |
| Alderlake Hybrid | 1        | 1.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Nvidia              | 29       | 38.67%  |
| Intel               | 22       | 29.33%  |
| AMD                 | 22       | 29.33%  |
| Zhaoxin             | 1        | 1.33%   |
| Loongson Technology | 1        | 1.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 6.58%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 5        | 6.58%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 3.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 3.95%   |
| Intel HD Graphics 630                                                       | 3        | 3.95%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.63%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 2.63%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.63%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.63%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.63%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 2.63%   |
| Zhaoxin KX-6000 C-960 GPU                                                   | 1        | 1.32%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.32%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.32%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.32%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.32%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.32%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.32%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.32%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.32%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.32%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.32%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.32%   |
| Nvidia GK104 [GeForce GTX 760 OEM]                                          | 1        | 1.32%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.32%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 1.32%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.32%   |
| Nvidia GF116 [GeForce GT 545]                                               | 1        | 1.32%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 1.32%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.32%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 1        | 1.32%   |
| Loongson Technology Vivante GPU (Graphics Processing Unit)                  | 1        | 1.32%   |
| Loongson Technology DC (Display Controller)                                 | 1        | 1.32%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.32%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.32%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Nvidia              | 27       | 39.71%  |
| 1 x AMD                 | 19       | 27.94%  |
| 1 x Intel               | 16       | 23.53%  |
| Intel + AMD             | 2        | 2.94%   |
| 1 x Zhaoxin             | 1        | 1.47%   |
| 1 x Loongson Technology | 1        | 1.47%   |
| Intel + Nvidia          | 1        | 1.47%   |
| AMD + Nvidia            | 1        | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 46       | 67.65%  |
| Proprietary | 17       | 25%     |
| Unknown     | 5        | 7.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 47.14%  |
| 1.01-2.0   | 16       | 22.86%  |
| 3.01-4.0   | 6        | 8.57%   |
| 7.01-8.0   | 5        | 7.14%   |
| 0.51-1.0   | 4        | 5.71%   |
| 0.01-0.5   | 3        | 4.29%   |
| 5.01-6.0   | 2        | 2.86%   |
| 16.01-24.0 | 1        | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 14       | 20.59%  |
| Goldstar             | 8        | 11.76%  |
| Hewlett-Packard      | 5        | 7.35%   |
| ViewSonic            | 4        | 5.88%   |
| Dell                 | 4        | 5.88%   |
| Philips              | 3        | 4.41%   |
| Ancor Communications | 3        | 4.41%   |
| Lenovo               | 2        | 2.94%   |
| Iiyama               | 2        | 2.94%   |
| HKC                  | 2        | 2.94%   |
| BenQ                 | 2        | 2.94%   |
| AOC                  | 2        | 2.94%   |
| Acer                 | 2        | 2.94%   |
| Xiaomi               | 1        | 1.47%   |
| Unknown              | 1        | 1.47%   |
| Toshiba              | 1        | 1.47%   |
| TFC                  | 1        | 1.47%   |
| SKY                  | 1        | 1.47%   |
| RTK                  | 1        | 1.47%   |
| Positivo             | 1        | 1.47%   |
| Packard Bell         | 1        | 1.47%   |
| MSI                  | 1        | 1.47%   |
| Hisense              | 1        | 1.47%   |
| HannStar             | 1        | 1.47%   |
| Gateway              | 1        | 1.47%   |
| DTV                  | 1        | 1.47%   |
| BOE                  | 1        | 1.47%   |
| ASUSTek Computer     | 1        | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch            | 3        | 4.05%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 950x540mm 43.0-inch | 2        | 2.7%    |
| Goldstar 20EN33 GSM4EE1 1600x900 440x250mm 19.9-inch                  | 2        | 2.7%    |
| Xiaomi Mi TV XMD0076 3840x2160 800x450mm 36.1-inch                    | 1        | 1.35%   |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch            | 1        | 1.35%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 1.35%   |
| Toshiba TV TSB0108 1920x540                                           | 1        | 1.35%   |
| TFC TF2411 TFC0238 1920x1080 527x296mm 23.8-inch                      | 1        | 1.35%   |
| SKY 24X1Q SKY2380 2560x1440 520x290mm 23.4-inch                       | 1        | 1.35%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch  | 1        | 1.35%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1        | 1.35%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch   | 1        | 1.35%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch  | 1        | 1.35%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch   | 1        | 1.35%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch     | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SMS23A350H 1920x1080                  | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SAM0E90 1366x768 609x347mm 27.6-inch  | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch | 1        | 1.35%   |
| Samsung Electronics LCD Monitor S24E390 1920x1080                     | 1        | 1.35%   |
| Samsung Electronics LCD Monitor S24E360 1920x1080                     | 1        | 1.35%   |
| Samsung Electronics LCD Monitor S24E310 3840x1080                     | 1        | 1.35%   |
| Samsung Electronics LCD Monitor S24E310                               | 1        | 1.35%   |
| Samsung Electronics LCD Monitor LC49G95T 3840x1080                    | 1        | 1.35%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                     | 1        | 1.35%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                  | 1        | 1.35%   |
| Philips FTV PHL04C2 1920x1080 1440x810mm 65.0-inch                    | 1        | 1.35%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                   | 1        | 1.35%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                    | 1        | 1.35%   |
| Packard Bell Viseo223DX PKB0385 1920x1080 477x268mm 21.5-inch         | 1        | 1.35%   |
| MSI MAG271CR MSI3FA6 1920x1080 598x336mm 27.0-inch                    | 1        | 1.35%   |
| Lenovo T24s-28 LEN62C7 1920x1080 527x296mm 23.8-inch                  | 1        | 1.35%   |
| Lenovo LEN T2324C LEN60F2 1920x1080 510x287mm 23.0-inch               | 1        | 1.35%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                  | 1        | 1.35%   |
| Iiyama PL2792Q IVM662F 2560x1440 597x336mm 27.0-inch                  | 1        | 1.35%   |
| HKC PL24V2 HKC0238 1920x1080 527x296mm 23.8-inch                      | 1        | 1.35%   |
| HKC 27E6QC HKC274F 2560x1440 597x336mm 27.0-inch                      | 1        | 1.35%   |
| Hisense LCD Monitor HDMI 1360x768                                     | 1        | 1.35%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch          | 1        | 1.35%   |
| Hewlett-Packard Compaq F191 HWP3177 1366x768 410x230mm 18.5-inch      | 1        | 1.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 34       | 49.28%  |
| 3840x2160 (4K)     | 6        | 8.7%    |
| 2560x1440 (QHD)    | 6        | 8.7%    |
| 1600x900 (HD+)     | 4        | 5.8%    |
| 3840x1080          | 3        | 4.35%   |
| 1440x900 (WXGA+)   | 3        | 4.35%   |
| 1680x1050 (WSXGA+) | 2        | 2.9%    |
| 1366x768 (WXGA)    | 2        | 2.9%    |
| 1360x768           | 2        | 2.9%    |
| Unknown            | 2        | 2.9%    |
| 2560x1600          | 1        | 1.45%   |
| 2288x1287          | 1        | 1.45%   |
| 1920x540           | 1        | 1.45%   |
| 1920x1200 (WUXGA)  | 1        | 1.45%   |
| 1280x1024 (SXGA)   | 1        | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 18       | 25.71%  |
| Unknown | 10       | 14.29%  |
| 24      | 8        | 11.43%  |
| 27      | 6        | 8.57%   |
| 21      | 5        | 7.14%   |
| 84      | 4        | 5.71%   |
| 20      | 3        | 4.29%   |
| 19      | 3        | 4.29%   |
| 18      | 3        | 4.29%   |
| 22      | 2        | 2.86%   |
| 142     | 1        | 1.43%   |
| 72      | 1        | 1.43%   |
| 65      | 1        | 1.43%   |
| 54      | 1        | 1.43%   |
| 32      | 1        | 1.43%   |
| 31      | 1        | 1.43%   |
| 25      | 1        | 1.43%   |
| 12      | 1        | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 32       | 47.06%  |
| 401-500        | 15       | 22.06%  |
| Unknown        | 10       | 14.71%  |
| 1501-2000      | 5        | 7.35%   |
| 1001-1500      | 2        | 2.94%   |
| More than 2000 | 1        | 1.47%   |
| 701-800        | 1        | 1.47%   |
| 601-700        | 1        | 1.47%   |
| 201-300        | 1        | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 50       | 76.92%  |
| Unknown | 9        | 13.85%  |
| 16/10   | 5        | 7.69%   |
| 1.00    | 1        | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 27       | 39.71%  |
| Unknown        | 10       | 14.71%  |
| 151-200        | 9        | 13.24%  |
| More than 1000 | 8        | 11.76%  |
| 301-350        | 6        | 8.82%   |
| 251-300        | 3        | 4.41%   |
| 351-500        | 2        | 2.94%   |
| 141-150        | 2        | 2.94%   |
| 61-70          | 1        | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 42       | 62.69%  |
| Unknown | 10       | 14.93%  |
| 101-120 | 9        | 13.43%  |
| 1-50    | 4        | 5.97%   |
| 161-240 | 1        | 1.49%   |
| 121-160 | 1        | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 56       | 81.16%  |
| 2     | 11       | 15.94%  |
| 0     | 2        | 2.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 44       | 47.83%  |
| Intel                    | 23       | 25%     |
| Broadcom                 | 5        | 5.43%   |
| Qualcomm Atheros         | 4        | 4.35%   |
| TP-Link                  | 3        | 3.26%   |
| MediaTek                 | 2        | 2.17%   |
| Xiaomi                   | 1        | 1.09%   |
| Unknown                  | 1        | 1.09%   |
| Ralink Technology        | 1        | 1.09%   |
| Ralink                   | 1        | 1.09%   |
| NXP Semiconductors       | 1        | 1.09%   |
| Nvidia                   | 1        | 1.09%   |
| NetGear                  | 1        | 1.09%   |
| Marvell Technology Group | 1        | 1.09%   |
| Loongson Technology      | 1        | 1.09%   |
| IMC Networks             | 1        | 1.09%   |
| Aquantia                 | 1        | 1.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 36       | 34.62%  |
| Intel Ethernet Connection (12) I219-V                                  | 4        | 3.85%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 2.88%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)              | 2        | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 1.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 1.92%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 1.92%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 1.92%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 1.92%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 2        | 1.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.96%   |
| Unknown Network controller                                             | 1        | 0.96%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 0.96%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.96%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 0.96%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 0.96%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 0.96%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.96%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 0.96%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                 | 1        | 0.96%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.96%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 0.96%   |
| NetGear A6210                                                          | 1        | 0.96%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                    | 1        | 0.96%   |
| MediaTek File-CD Gadget                                                | 1        | 0.96%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.96%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 0.96%   |
| Loongson Gigabit Ethernet Controller                                   | 1        | 0.96%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 1        | 0.96%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 0.96%   |
| Intel Ethernet Controller I226-V                                       | 1        | 0.96%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.96%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 32%     |
| Intel                 | 6        | 24%     |
| TP-Link               | 3        | 12%     |
| Qualcomm Atheros      | 2        | 8%      |
| Ralink Technology     | 1        | 4%      |
| Ralink                | 1        | 4%      |
| NetGear               | 1        | 4%      |
| MediaTek              | 1        | 4%      |
| IMC Networks          | 1        | 4%      |
| Broadcom              | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)  | 2        | 8%      |
| Intel Wi-Fi 6 AX200                                        | 2        | 8%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 4%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 4%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1        | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 4%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1        | 4%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 4%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1        | 4%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 4%      |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 4%      |
| Ralink MT7601U Wireless Adapter                            | 1        | 4%      |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1        | 4%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 4%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1        | 4%      |
| NetGear A6210                                              | 1        | 4%      |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter        | 1        | 4%      |
| Intel Raptor Lake-S PCH CNVi WiFi                          | 1        | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 4%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1        | 4%      |
| Intel Comet Lake PCH CNVi WiFi                             | 1        | 4%      |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]       | 1        | 4%      |
| Broadcom BCM43228 802.11a/b/g/n                            | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 43       | 57.33%  |
| Intel                    | 20       | 26.67%  |
| Broadcom                 | 4        | 5.33%   |
| Qualcomm Atheros         | 2        | 2.67%   |
| Xiaomi                   | 1        | 1.33%   |
| Nvidia                   | 1        | 1.33%   |
| MediaTek                 | 1        | 1.33%   |
| Marvell Technology Group | 1        | 1.33%   |
| Loongson Technology      | 1        | 1.33%   |
| Aquantia                 | 1        | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 36       | 46.75%  |
| Intel Ethernet Connection (12) I219-V                                  | 4        | 5.19%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 3.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 2.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 2.6%    |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 2.6%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 2.6%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 2        | 2.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 1.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 1.3%    |
| Nvidia MCP61 Ethernet                                                  | 1        | 1.3%    |
| MediaTek File-CD Gadget                                                | 1        | 1.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 1.3%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 1.3%    |
| Loongson Gigabit Ethernet Controller                                   | 1        | 1.3%    |
| Intel I211 Gigabit Network Connection                                  | 1        | 1.3%    |
| Intel Ethernet Controller I226-V                                       | 1        | 1.3%    |
| Intel Ethernet Connection I217-V                                       | 1        | 1.3%    |
| Intel Ethernet Connection I217-LM                                      | 1        | 1.3%    |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.3%    |
| Intel Ethernet Connection (5) I219-LM                                  | 1        | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 1.3%    |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 1.3%    |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 1.3%    |
| Intel 82579V Gigabit Network Connection                                | 1        | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 1.3%    |
| Intel 82575EB Gigabit Network Connection                               | 1        | 1.3%    |
| Intel 82567LM-2 Gigabit Network Connection                             | 1        | 1.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 1.3%    |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 1        | 1.3%    |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]      | 1        | 1.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 68       | 71.58%  |
| WiFi     | 25       | 26.32%  |
| Modem    | 1        | 1.05%   |
| Unknown  | 1        | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 56       | 82.35%  |
| WiFi     | 12       | 17.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 71.01%  |
| 2     | 15       | 21.74%  |
| 3     | 4        | 5.8%    |
| 4     | 1        | 1.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 63       | 92.65%  |
| Yes  | 5        | 7.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 11       | 45.83%  |
| Intel                           | 6        | 25%     |
| Realtek Semiconductor           | 1        | 4.17%   |
| Qualcomm Atheros Communications | 1        | 4.17%   |
| MediaTek                        | 1        | 4.17%   |
| Lite-On Technology              | 1        | 4.17%   |
| Dynex                           | 1        | 4.17%   |
| Broadcom                        | 1        | 4.17%   |
| ASUSTek Computer                | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 11       | 45.83%  |
| Intel AX200 Bluetooth                                    | 2        | 8.33%   |
| Realtek Bluetooth Radio                                  | 1        | 4.17%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 4.17%   |
| MediaTek BT                                              | 1        | 4.17%   |
| Lite-On Bluetooth Device                                 | 1        | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                         | 1        | 4.17%   |
| Intel Bluetooth wireless interface                       | 1        | 4.17%   |
| Intel Bluetooth Device                                   | 1        | 4.17%   |
| Intel AX201 Bluetooth                                    | 1        | 4.17%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 4.17%   |
| Broadcom HP Portable Bumble Bee                          | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 52       | 44.44%  |
| AMD                                          | 29       | 24.79%  |
| Nvidia                                       | 27       | 23.08%  |
| C-Media Electronics                          | 2        | 1.71%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.85%   |
| Zhaoxin                                      | 1        | 0.85%   |
| XMOS                                         | 1        | 0.85%   |
| Microdia                                     | 1        | 0.85%   |
| Loongson Technology                          | 1        | 0.85%   |
| BEHRINGER International                      | 1        | 0.85%   |
| ASUSTek Computer                             | 1        | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                     | Desktops | Percent |
|-------------------------------------------------------------------------------------------|----------|---------|
| Intel Comet Lake PCH-V cAVS                                                               | 8        | 6.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                       | 8        | 6.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                       | 7        | 5.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                | 7        | 5.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                   | 7        | 5.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                          | 4        | 3.13%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                          | 4        | 3.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                           | 4        | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                                                  | 4        | 3.13%   |
| Nvidia GM204 High Definition Audio Controller                                             | 3        | 2.34%   |
| Nvidia GF116 High Definition Audio Controller                                             | 3        | 2.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                   | 3        | 2.34%   |
| Intel 200 Series PCH HD Audio                                                             | 3        | 2.34%   |
| AMD SBx00 Azalia (Intel HDA)                                                              | 3        | 2.34%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]         | 3        | 2.34%   |
| Nvidia High Definition Audio Controller                                                   | 2        | 1.56%   |
| Nvidia GP106 High Definition Audio Controller                                             | 2        | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                     | 2        | 1.56%   |
| Nvidia GK107 HDMI Audio Controller                                                        | 2        | 1.56%   |
| Nvidia GF119 HDMI Audio Controller                                                        | 2        | 1.56%   |
| Nvidia GA104 High Definition Audio Controller                                             | 2        | 1.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                              | 2        | 1.56%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                       | 2        | 1.56%   |
| AMD FCH Azalia Controller                                                                 | 2        | 1.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                       | 2        | 1.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                | 2        | 1.56%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                            | 1        | 0.78%   |
| Zhaoxin ZX-E High Definition Audio Controller                                             | 1        | 0.78%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller | 1        | 0.78%   |
| XMOS iFi (by AMR) HD USB Audio                                                            | 1        | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                             | 1        | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                            | 1        | 0.78%   |
| Nvidia MCP61 High Definition Audio                                                        | 1        | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                                             | 1        | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                                           | 1        | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                                             | 1        | 0.78%   |
| Nvidia GM206 High Definition Audio Controller                                             | 1        | 0.78%   |
| Nvidia GK106 HDMI Audio Controller                                                        | 1        | 0.78%   |
| Nvidia GK104 HDMI Audio Controller                                                        | 1        | 0.78%   |
| Nvidia AD102 High Definition Audio Controller                                             | 1        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston                           | 12       | 30.77%  |
| Unknown                            | 5        | 12.82%  |
| Samsung Electronics                | 3        | 7.69%   |
| G.Skill                            | 3        | 7.69%   |
| Corsair                            | 3        | 7.69%   |
| SK hynix                           | 2        | 5.13%   |
| Team                               | 1        | 2.56%   |
| Ramaxel Technology                 | 1        | 2.56%   |
| Nanya Technology                   | 1        | 2.56%   |
| KINGBANK                           | 1        | 2.56%   |
| Kimtigo Semiconductor (HK) Limited | 1        | 2.56%   |
| Elpida                             | 1        | 2.56%   |
| CSX                                | 1        | 2.56%   |
| Crucial                            | 1        | 2.56%   |
| Apacer                             | 1        | 2.56%   |
| A-DATA Technology                  | 1        | 2.56%   |
| Unknown                            | 1        | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Kingston RAM TF32D4U2S1MEH-8 8192MB DIMM DDR4 3200MT/s     | 3        | 7.14%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                  | 1        | 2.38%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s               | 1        | 2.38%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                     | 1        | 2.38%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1        | 2.38%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s         | 1        | 2.38%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s        | 1        | 2.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1        | 2.38%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s       | 1        | 2.38%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s   | 1        | 2.38%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 2.38%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s        | 1        | 2.38%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s        | 1        | 2.38%   |
| Ramaxel RAM RMSA3230KE68H9F213 4096MB SODIMM DDR4 2133MT/s | 1        | 2.38%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s         | 1        | 2.38%   |
| Kingston RAM Module 4GB DIMM DDR3 1067MT/s                 | 1        | 2.38%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s             | 1        | 2.38%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 1        | 2.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 2.38%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s          | 1        | 2.38%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s        | 1        | 2.38%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s        | 1        | 2.38%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s        | 1        | 2.38%   |
| Kingston RAM BRAP1G48GB16C1600 8192MB DIMM DDR3 1600MT/s   | 1        | 2.38%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 2.38%   |
| Kingston RAM 99U5403-034.A00LF 4096MB DIMM DDR3 1333MT/s   | 1        | 2.38%   |
| KINGBANK RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 2.38%   |
| Kimtigo (HK) Limited RAM Module 8192MB DIMM DDR4 2666MT/s  | 1        | 2.38%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s       | 1        | 2.38%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s         | 1        | 2.38%   |
| G.Skill RAM F3-14900CL10-8GBXL 8GB DIMM DDR3 1867MT/s      | 1        | 2.38%   |
| Elpida RAM EBJ10UE8BBF0-AE-F 1GB DIMM DDR3 1066MT/s        | 1        | 2.38%   |
| CSX RAM V01D3LF4GB26826813 4GB DIMM DDR3                   | 1        | 2.38%   |
| Crucial RAM Module 4GB DIMM DDR3 1600MT/s                  | 1        | 2.38%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s       | 1        | 2.38%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s      | 1        | 2.38%   |
| Corsair RAM CMK16GX4M1B3000C15 16GB DIMM DDR4 3400MT/s     | 1        | 2.38%   |
| Apacer RAM 76.C346G.C850C 8192MB SODIMM DDR3 1600MT/s      | 1        | 2.38%   |
| A-DATA RAM DDR4 2400 2OZ 8GB DIMM DDR4 3000MT/s            | 1        | 2.38%   |
| Unknown                                                    | 1        | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 18       | 52.94%  |
| DDR3    | 13       | 38.24%  |
| Unknown | 2        | 5.88%   |
| SDRAM   | 1        | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 31       | 91.18%  |
| SODIMM | 3        | 8.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 21       | 56.76%  |
| 4096  | 9        | 24.32%  |
| 16384 | 3        | 8.11%   |
| 1024  | 2        | 5.41%   |
| 32768 | 1        | 2.7%    |
| 2048  | 1        | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6        | 15.38%  |
| 3200    | 3        | 7.69%   |
| 2133    | 3        | 7.69%   |
| 1867    | 3        | 7.69%   |
| 3600    | 2        | 5.13%   |
| 3400    | 2        | 5.13%   |
| 2667    | 2        | 5.13%   |
| 2666    | 2        | 5.13%   |
| 2400    | 2        | 5.13%   |
| 1333    | 2        | 5.13%   |
| 1067    | 2        | 5.13%   |
| 4266    | 1        | 2.56%   |
| 3800    | 1        | 2.56%   |
| 3533    | 1        | 2.56%   |
| 3500    | 1        | 2.56%   |
| 3466    | 1        | 2.56%   |
| 3066    | 1        | 2.56%   |
| 3000    | 1        | 2.56%   |
| 1066    | 1        | 2.56%   |
| 667     | 1        | 2.56%   |
| Unknown | 1        | 2.56%   |

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
| Logitech               | 6        | 54.55%  |
| webcamvendor           | 1        | 9.09%   |
| Microdia               | 1        | 9.09%   |
| Generalplus Technology | 1        | 9.09%   |
| Chicony Electronics    | 1        | 9.09%   |
| Arkmicro Technologies  | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 4        | 36.36%  |
| webcamvendor webcamproduct            | 1        | 9.09%   |
| Microdia Integrated_Webcam_HD         | 1        | 9.09%   |
| Logitech Webcam C200                  | 1        | 9.09%   |
| Logitech HD Pro Webcam C920           | 1        | 9.09%   |
| Generalplus GENERAL WEBCAM            | 1        | 9.09%   |
| Chicony HP High Definition 1MP Webcam | 1        | 9.09%   |
| Arkmicro USB2.0 PC CAMERA             | 1        | 9.09%   |

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
| 0     | 59       | 86.76%  |
| 1     | 7        | 10.29%  |
| 2     | 2        | 2.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 6        | 60%     |
| Net/wireless  | 4        | 40%     |

