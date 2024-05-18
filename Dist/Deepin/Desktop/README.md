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

Total: 110

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ac24b8ae8b](https://linux-hardware.org/?probe=ac24b8ae8b) | Mar 06, 2024 |
| ASUSTek       | B85M-K                      | [dc3ec9e412](https://linux-hardware.org/?probe=dc3ec9e412) | Feb 03, 2024 |
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
| Deepin         | 14       | 18.92%  |
| Deepin 23      | 11       | 14.86%  |
| UOS 20         | 10       | 13.51%  |
| Deepin 20      | 10       | 13.51%  |
| Deepin 20 beta | 4        | 5.41%   |
| Deepin 15.9.2  | 4        | 5.41%   |
| Deepin 20.9    | 3        | 4.05%   |
| Deepin 20.1    | 3        | 4.05%   |
| Deepin 15.11   | 3        | 4.05%   |
| Deepin 20.6    | 2        | 2.7%    |
| Deepin 20.3    | 2        | 2.7%    |
| Deepin 20.2.2  | 2        | 2.7%    |
| Deepin 15.10.1 | 2        | 2.7%    |
| Deepin 20.2.4  | 1        | 1.35%   |
| Deepin 20.2.3  | 1        | 1.35%   |
| Deepin 20.2    | 1        | 1.35%   |
| Deepin 15.7    | 1        | 1.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Deepin | 70       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.4.70-amd64-desktop      | 7        | 9.46%   |
| 4.15.0-30deepin-generic   | 7        | 9.46%   |
| 4.15.0-29deepin-generic   | 7        | 9.46%   |
| 5.4.50-amd64-desktop      | 6        | 8.11%   |
| 5.3.0-3-amd64             | 6        | 8.11%   |
| 6.1.32-amd64-desktop-hwe  | 3        | 4.05%   |
| 5.15.45-amd64-desktop     | 3        | 4.05%   |
| 5.10.60-amd64-desktop     | 3        | 4.05%   |
| 5.10.36-amd64-desktop     | 3        | 4.05%   |
| 5.10.0-amd64-desktop      | 3        | 4.05%   |
| 4.19.0-amd64-desktop      | 3        | 4.05%   |
| 6.3.0-rc4-amd64-exton     | 2        | 2.7%    |
| 5.7.7-amd64-desktop       | 2        | 2.7%    |
| 5.15.77-amd64-desktop     | 2        | 2.7%    |
| 5.10.29-amd64-desktop     | 2        | 2.7%    |
| 5.10.18-amd64-desktop     | 2        | 2.7%    |
| 6.1.12-1-liquorix-amd64   | 1        | 1.35%   |
| 6.1.11-amd64-desktop-hwe  | 1        | 1.35%   |
| 5.8.14-amd64-desktop      | 1        | 1.35%   |
| 5.5.4-xanmod3             | 1        | 1.35%   |
| 5.18.17-amd64-desktop-hwe | 1        | 1.35%   |
| 5.15.34-amd64-desktop     | 1        | 1.35%   |
| 5.15.24-amd64-desktop     | 1        | 1.35%   |
| 5.14.0-rc3-amd64-desktop  | 1        | 1.35%   |
| 5.10.50-amd64-desktop     | 1        | 1.35%   |
| 5.10.5-amd64-desktop+     | 1        | 1.35%   |
| 5.10.101-amd64-desktop    | 1        | 1.35%   |
| 4.19.90-1.lns7.2.mips64el | 1        | 1.35%   |
| 4.19.0-5-amd64            | 1        | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 14       | 18.92%  |
| 5.4.70   | 7        | 9.46%   |
| 5.4.50   | 6        | 8.11%   |
| 5.3.0    | 6        | 8.11%   |
| 4.19.0   | 4        | 5.41%   |
| 6.1.32   | 3        | 4.05%   |
| 5.15.45  | 3        | 4.05%   |
| 5.10.60  | 3        | 4.05%   |
| 5.10.36  | 3        | 4.05%   |
| 5.10.0   | 3        | 4.05%   |
| 6.3.0    | 2        | 2.7%    |
| 5.7.7    | 2        | 2.7%    |
| 5.15.77  | 2        | 2.7%    |
| 5.10.29  | 2        | 2.7%    |
| 5.10.18  | 2        | 2.7%    |
| 6.1.12   | 1        | 1.35%   |
| 6.1.11   | 1        | 1.35%   |
| 5.8.14   | 1        | 1.35%   |
| 5.5.4    | 1        | 1.35%   |
| 5.18.17  | 1        | 1.35%   |
| 5.15.34  | 1        | 1.35%   |
| 5.15.24  | 1        | 1.35%   |
| 5.14.0   | 1        | 1.35%   |
| 5.10.50  | 1        | 1.35%   |
| 5.10.5   | 1        | 1.35%   |
| 5.10.101 | 1        | 1.35%   |
| 4.19.90  | 1        | 1.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 14       | 19.72%  |
| 4.15    | 14       | 19.72%  |
| 5.4     | 12       | 16.9%   |
| 5.15    | 7        | 9.86%   |
| 5.3     | 6        | 8.45%   |
| 6.1     | 5        | 7.04%   |
| 4.19    | 5        | 7.04%   |
| 6.3     | 2        | 2.82%   |
| 5.7     | 2        | 2.82%   |
| 5.8     | 1        | 1.41%   |
| 5.5     | 1        | 1.41%   |
| 5.18    | 1        | 1.41%   |
| 5.14    | 1        | 1.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 69       | 98.57%  |
| mips64 | 1        | 1.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Deepin  | 55       | 77.46%  |
| Unknown | 9        | 12.68%  |
| DDE     | 6        | 8.45%   |
| MATE    | 1        | 1.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 64       | 91.43%  |
| Wayland | 4        | 5.71%   |
| Tty     | 2        | 2.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 50%     |
| LightDM | 24       | 34.29%  |
| TDM     | 11       | 15.71%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 18       | 25%     |
| zh_CN   | 15       | 20.83%  |
| pt_BR   | 11       | 15.28%  |
| es_ES   | 8        | 11.11%  |
| Unknown | 8        | 11.11%  |
| de_DE   | 4        | 5.56%   |
| tr_TR   | 1        | 1.39%   |
| ru_RU   | 1        | 1.39%   |
| pl_PL   | 1        | 1.39%   |
| lt_LT   | 1        | 1.39%   |
| it_IT   | 1        | 1.39%   |
| id_ID   | 1        | 1.39%   |
| fr_FR   | 1        | 1.39%   |
| en_GB   | 1        | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 36       | 51.43%  |
| EFI  | 34       | 48.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 64       | 91.43%  |
| Unknown | 4        | 5.71%   |
| Btrfs   | 2        | 2.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 32       | 44.44%  |
| GPT     | 30       | 41.67%  |
| MBR     | 10       | 13.89%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 71.83%  |
| Yes       | 20       | 28.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 77.46%  |
| Yes       | 16       | 22.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 18       | 25.71%  |
| Gigabyte Technology        | 10       | 14.29%  |
| TSINGHUA TONGFANG COMPUTER | 7        | 10%     |
| Dell                       | 7        | 10%     |
| MSI                        | 4        | 5.71%   |
| ASRock                     | 4        | 5.71%   |
| Semp Toshiba               | 2        | 2.86%   |
| Positivo                   | 2        | 2.86%   |
| Lenovo                     | 2        | 2.86%   |
| Intel                      | 2        | 2.86%   |
| Hewlett-Packard            | 2        | 2.86%   |
| ECS                        | 2        | 2.86%   |
| OEM                        | 1        | 1.43%   |
| Medion                     | 1        | 1.43%   |
| Loongson                   | 1        | 1.43%   |
| Koloe                      | 1        | 1.43%   |
| Huanan                     | 1        | 1.43%   |
| Foxconn                    | 1        | 1.43%   |
| AMD                        | 1        | 1.43%   |
| Unknown                    | 1        | 1.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500          | 7        | 10%     |
| ASUS All Series                          | 3        | 4.29%   |
| Semp Toshiba STI                         | 2        | 2.86%   |
| ECS H81H3-M4                             | 2        | 2.86%   |
| Positivo POS-PQ45AU                      | 1        | 1.43%   |
| Positivo POS-EINM70CS                    | 1        | 1.43%   |
| OEM ZXE CRB                              | 1        | 1.43%   |
| MSI MS-7C84                              | 1        | 1.43%   |
| MSI MS-7C83                              | 1        | 1.43%   |
| MSI MS-7851                              | 1        | 1.43%   |
| MSI MS-7681                              | 1        | 1.43%   |
| Medion MS-7728                           | 1        | 1.43%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev     | 1        | 1.43%   |
| Lenovo ThinkCentre M910t-N000 10N9CTO1WW | 1        | 1.43%   |
| Lenovo ThinkCentre M82 2929AJ2           | 1        | 1.43%   |
| Koloe Thurley                            | 1        | 1.43%   |
| Intel DX58SO AAE29331-504                | 1        | 1.43%   |
| Intel DH77EB AAG39073-304                | 1        | 1.43%   |
| Huanan X99-8M-F V1.1                     | 1        | 1.43%   |
| HP ProOne 400 G1 AiO                     | 1        | 1.43%   |
| HP 260-P020il                            | 1        | 1.43%   |
| Gigabyte Z77-DS3H                        | 1        | 1.43%   |
| Gigabyte Z170X-Gaming 7                  | 1        | 1.43%   |
| Gigabyte H81M-D2V                        | 1        | 1.43%   |
| Gigabyte H110M-H                         | 1        | 1.43%   |
| Gigabyte GA-78LMT-USB3                   | 1        | 1.43%   |
| Gigabyte B550M DS3H                      | 1        | 1.43%   |
| Gigabyte B450 I AORUS PRO WIFI           | 1        | 1.43%   |
| Gigabyte B365M D3H                       | 1        | 1.43%   |
| Gigabyte B360M AORUS Gaming 3            | 1        | 1.43%   |
| Gigabyte 990XA-UD3                       | 1        | 1.43%   |
| Foxconn p7-1430br                        | 1        | 1.43%   |
| Dell Vostro 270                          | 1        | 1.43%   |
| Dell Vostro 230                          | 1        | 1.43%   |
| Dell Precision WorkStation T3500         | 1        | 1.43%   |
| Dell OptiPlex 9020                       | 1        | 1.43%   |
| Dell OptiPlex 760                        | 1        | 1.43%   |
| Dell OptiPlex 7050                       | 1        | 1.43%   |
| Dell Inspiron One 2020                   | 1        | 1.43%   |
| ASUS TUF Gaming B550M-PLUS               | 1        | 1.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500      | 7        | 10%     |
| Dell OptiPlex                        | 3        | 4.29%   |
| ASUS ROG                             | 3        | 4.29%   |
| ASUS PRIME                           | 3        | 4.29%   |
| ASUS All                             | 3        | 4.29%   |
| Semp Toshiba STI                     | 2        | 2.86%   |
| Lenovo ThinkCentre                   | 2        | 2.86%   |
| ECS H81H3-M4                         | 2        | 2.86%   |
| Dell Vostro                          | 2        | 2.86%   |
| Positivo POS-PQ45AU                  | 1        | 1.43%   |
| Positivo POS-EINM70CS                | 1        | 1.43%   |
| OEM ZXE                              | 1        | 1.43%   |
| MSI MS-7C84                          | 1        | 1.43%   |
| MSI MS-7C83                          | 1        | 1.43%   |
| MSI MS-7851                          | 1        | 1.43%   |
| MSI MS-7681                          | 1        | 1.43%   |
| Medion MS-7728                       | 1        | 1.43%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev | 1        | 1.43%   |
| Koloe Thurley                        | 1        | 1.43%   |
| Intel DX58SO                         | 1        | 1.43%   |
| Intel DH77EB                         | 1        | 1.43%   |
| Huanan X99-8M-F                      | 1        | 1.43%   |
| HP ProOne                            | 1        | 1.43%   |
| HP 260-P020il                        | 1        | 1.43%   |
| Gigabyte Z77-DS3H                    | 1        | 1.43%   |
| Gigabyte Z170X-Gaming                | 1        | 1.43%   |
| Gigabyte H81M-D2V                    | 1        | 1.43%   |
| Gigabyte H110M-H                     | 1        | 1.43%   |
| Gigabyte GA-78LMT-USB3               | 1        | 1.43%   |
| Gigabyte B550M                       | 1        | 1.43%   |
| Gigabyte B450                        | 1        | 1.43%   |
| Gigabyte B365M                       | 1        | 1.43%   |
| Gigabyte B360M                       | 1        | 1.43%   |
| Gigabyte 990XA-UD3                   | 1        | 1.43%   |
| Foxconn p7-1430br                    | 1        | 1.43%   |
| Dell Precision                       | 1        | 1.43%   |
| Dell Inspiron                        | 1        | 1.43%   |
| ASUS TUF                             | 1        | 1.43%   |
| ASUS P8H77-M                         | 1        | 1.43%   |
| ASUS P8H61-MX                        | 1        | 1.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 9        | 12.86%  |
| 2013 | 9        | 12.86%  |
| 2012 | 8        | 11.43%  |
| 2021 | 7        | 10%     |
| 2018 | 6        | 8.57%   |
| 2014 | 6        | 8.57%   |
| 2011 | 6        | 8.57%   |
| 2017 | 4        | 5.71%   |
| 2009 | 4        | 5.71%   |
| 2016 | 3        | 4.29%   |
| 2010 | 3        | 4.29%   |
| 2019 | 2        | 2.86%   |
| 2022 | 1        | 1.43%   |
| 2015 | 1        | 1.43%   |
| 2008 | 1        | 1.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 70       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 67       | 95.71%  |
| Enabled  | 3        | 4.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 70       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 24       | 34.29%  |
| 8.01-16.0   | 18       | 25.71%  |
| 4.01-8.0    | 12       | 17.14%  |
| 3.01-4.0    | 7        | 10%     |
| 32.01-64.0  | 5        | 7.14%   |
| 24.01-32.0  | 2        | 2.86%   |
| 64.01-256.0 | 1        | 1.43%   |
| 1.01-2.0    | 1        | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 20       | 26.32%  |
| 2.01-3.0  | 18       | 23.68%  |
| 1.01-2.0  | 18       | 23.68%  |
| 3.01-4.0  | 11       | 14.47%  |
| 0.51-1.0  | 6        | 7.89%   |
| 8.01-16.0 | 3        | 3.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 29       | 40.85%  |
| 2      | 25       | 35.21%  |
| 3      | 8        | 11.27%  |
| 4      | 7        | 9.86%   |
| 5      | 2        | 2.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 68.06%  |
| Yes       | 23       | 31.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 70       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 62.86%  |
| Yes       | 26       | 37.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 65.71%  |
| Yes       | 24       | 34.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| China       | 16       | 22.86%  |
| Brazil      | 16       | 22.86%  |
| USA         | 7        | 10%     |
| Germany     | 3        | 4.29%   |
| Panama      | 2        | 2.86%   |
| Mexico      | 2        | 2.86%   |
| Colombia    | 2        | 2.86%   |
| Argentina   | 2        | 2.86%   |
| Ukraine     | 1        | 1.43%   |
| UK          | 1        | 1.43%   |
| Turkey      | 1        | 1.43%   |
| Spain       | 1        | 1.43%   |
| Russia      | 1        | 1.43%   |
| Romania     | 1        | 1.43%   |
| Poland      | 1        | 1.43%   |
| New Zealand | 1        | 1.43%   |
| Namibia     | 1        | 1.43%   |
| Lithuania   | 1        | 1.43%   |
| Kenya       | 1        | 1.43%   |
| Italy       | 1        | 1.43%   |
| Indonesia   | 1        | 1.43%   |
| India       | 1        | 1.43%   |
| Iceland     | 1        | 1.43%   |
| Belgium     | 1        | 1.43%   |
| Bangladesh  | 1        | 1.43%   |
| Austria     | 1        | 1.43%   |
| Australia   | 1        | 1.43%   |
| Albania     | 1        | 1.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Wuhan              | 4        | 5.56%   |
| Sao Paulo          | 3        | 4.17%   |
| Nanjing            | 3        | 4.17%   |
| Beijing            | 3        | 4.17%   |
| San Francisco      | 2        | 2.78%   |
| David              | 2        | 2.78%   |
| Zhongshan          | 1        | 1.39%   |
| Windhoek           | 1        | 1.39%   |
| Voluntari          | 1        | 1.39%   |
| Tychy              | 1        | 1.39%   |
| Toluca             | 1        | 1.39%   |
| Tirana             | 1        | 1.39%   |
| Taua               | 1        | 1.39%   |
| Sydney             | 1        | 1.39%   |
| Surakarta          | 1        | 1.39%   |
| St Petersburg      | 1        | 1.39%   |
| Socorro            | 1        | 1.39%   |
| Shenzhen           | 1        | 1.39%   |
| Shanghai           | 1        | 1.39%   |
| Seesen             | 1        | 1.39%   |
| Sao Caetano do Sul | 1        | 1.39%   |
| Santo André       | 1        | 1.39%   |
| Santa Clarita      | 1        | 1.39%   |
| Rome               | 1        | 1.39%   |
| Rio de Janeiro     | 1        | 1.39%   |
| Reykjavik          | 1        | 1.39%   |
| Ransart            | 1        | 1.39%   |
| Qingdao            | 1        | 1.39%   |
| Para de Minas      | 1        | 1.39%   |
| Olinda             | 1        | 1.39%   |
| Oerlinghausen      | 1        | 1.39%   |
| Niterói           | 1        | 1.39%   |
| Naucalpan          | 1        | 1.39%   |
| Mesa               | 1        | 1.39%   |
| Medellín          | 1        | 1.39%   |
| Marília           | 1        | 1.39%   |
| Lviv               | 1        | 1.39%   |
| Leipzig            | 1        | 1.39%   |
| Krakow             | 1        | 1.39%   |
| Konya              | 1        | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 27       | 35     | 20.77%  |
| Seagate               | 19       | 22     | 14.62%  |
| Samsung Electronics   | 10       | 11     | 7.69%   |
| Kingston              | 9        | 14     | 6.92%   |
| Toshiba               | 8        | 9      | 6.15%   |
| SanDisk               | 8        | 12     | 6.15%   |
| Crucial               | 5        | 6      | 3.85%   |
| Hitachi               | 4        | 4      | 3.08%   |
| China                 | 4        | 4      | 3.08%   |
| A-DATA Technology     | 4        | 5      | 3.08%   |
| Phison                | 3        | 3      | 2.31%   |
| FORESEE               | 3        | 3      | 2.31%   |
| SPCC                  | 2        | 2      | 1.54%   |
| Silicon Motion        | 2        | 2      | 1.54%   |
| Maxtor                | 2        | 4      | 1.54%   |
| Hewlett-Packard       | 2        | 3      | 1.54%   |
| Vaseky                | 1        | 1      | 0.77%   |
| Unknown               | 1        | 2      | 0.77%   |
| Realtek Semiconductor | 1        | 1      | 0.77%   |
| Phytium               | 1        | 1      | 0.77%   |
| Phison Electronics    | 1        | 2      | 0.77%   |
| Mushkin               | 1        | 1      | 0.77%   |
| Maxtor 6              | 1        | 1      | 0.77%   |
| LaCie                 | 1        | 2      | 0.77%   |
| KingDian              | 1        | 1      | 0.77%   |
| KINGBANK              | 1        | 1      | 0.77%   |
| JMicron Technology    | 1        | 1      | 0.77%   |
| Intenso               | 1        | 2      | 0.77%   |
| Intel                 | 1        | 1      | 0.77%   |
| HGST                  | 1        | 1      | 0.77%   |
| Gigabyte Technology   | 1        | 1      | 0.77%   |
| Beijing Starblaze     | 1        | 1      | 0.77%   |
| Apacer                | 1        | 3      | 0.77%   |
| ADATA Technology      | 1        | 1      | 0.77%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB   | 4        | 2.86%   |
| Phison ESO256GMFCH-E3C-2 256GB   | 3        | 2.14%   |
| WDC WDS120G1G0A-00SS50 120GB SSD | 2        | 1.43%   |
| WDC WD5000AAKX-003CA0 500GB      | 2        | 1.43%   |
| WDC WD10EZEX-22MFCA0 1TB         | 2        | 1.43%   |
| Toshiba DT01ACA200 2TB           | 2        | 1.43%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 1.43%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 1.43%   |
| SanDisk SDSSDH3512G 512GB        | 2        | 1.43%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 1.43%   |
| Kingston SA400S37480G 480GB SSD  | 2        | 1.43%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 1.43%   |
| FORESEE P900F256GBH              | 2        | 1.43%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.71%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.71%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1        | 0.71%   |
| WDC WD80 0BEVE-11UYT0 80GB       | 1        | 0.71%   |
| WDC WD7500BPKX-22HPJT0 752GB     | 1        | 0.71%   |
| WDC WD6400AAKS-75A7B0 640GB      | 1        | 0.71%   |
| WDC WD5000LPLX-66ZNTT1 500GB     | 1        | 0.71%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.71%   |
| WDC WD5000AAKX-00U6AA0 500GB     | 1        | 0.71%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.71%   |
| WDC WD5000AAKS-00A7B2 500GB      | 1        | 0.71%   |
| WDC WD5000AAJS-57TKA0 500GB      | 1        | 0.71%   |
| WDC WD3200AAKS-61L9A0 320GB      | 1        | 0.71%   |
| WDC WD3200AAKS-00VYA0 320GB      | 1        | 0.71%   |
| WDC WD30EZRX-22D8PB0 3TB         | 1        | 0.71%   |
| WDC WD20PURX-64P6ZY0 2TB         | 1        | 0.71%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.71%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1        | 0.71%   |
| WDC WD1600AAJS-00L7A0 160GB      | 1        | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 0.71%   |
| WDC WD10EZEX-08M2NA0 1TB         | 1        | 0.71%   |
| WDC WD10EZEX-00WN4A0 1TB         | 1        | 0.71%   |
| WDC WD10EZEX-00KUWA0 1TB         | 1        | 0.71%   |
| WDC WD10EFRX-68FYTN0 1TB         | 1        | 0.71%   |
| WDC WD10EARS-00Y5B1 1TB          | 1        | 0.71%   |
| Vaseky V800/256G 256GB           | 1        | 0.71%   |
| Unknown SD/MMC/MS PRO 128GB      | 1        | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 30     | 36.51%  |
| Seagate             | 19       | 22     | 30.16%  |
| Toshiba             | 8        | 9      | 12.7%   |
| Hitachi             | 4        | 4      | 6.35%   |
| Samsung Electronics | 2        | 2      | 3.17%   |
| Maxtor              | 2        | 4      | 3.17%   |
| Unknown             | 1        | 2      | 1.59%   |
| Maxtor 6            | 1        | 1      | 1.59%   |
| JMicron Technology  | 1        | 1      | 1.59%   |
| HGST                | 1        | 1      | 1.59%   |
| Hewlett-Packard     | 1        | 2      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 8        | 12     | 18.18%  |
| Kingston            | 7        | 12     | 15.91%  |
| Samsung Electronics | 5        | 6      | 11.36%  |
| WDC                 | 4        | 4      | 9.09%   |
| Crucial             | 4        | 5      | 9.09%   |
| China               | 4        | 4      | 9.09%   |
| A-DATA Technology   | 3        | 4      | 6.82%   |
| SPCC                | 2        | 2      | 4.55%   |
| Vaseky              | 1        | 1      | 2.27%   |
| KingDian            | 1        | 1      | 2.27%   |
| KINGBANK            | 1        | 1      | 2.27%   |
| Intenso             | 1        | 2      | 2.27%   |
| Intel               | 1        | 1      | 2.27%   |
| Hewlett-Packard     | 1        | 1      | 2.27%   |
| Apacer              | 1        | 3      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 49       | 78     | 45.79%  |
| SSD     | 37       | 59     | 34.58%  |
| NVMe    | 20       | 24     | 18.69%  |
| Unknown | 1        | 2      | 0.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 66       | 132    | 73.33%  |
| NVMe | 20       | 24     | 22.22%  |
| SAS  | 4        | 7      | 4.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 49       | 84     | 53.85%  |
| 0.51-1.0   | 34       | 42     | 37.36%  |
| 1.01-2.0   | 7        | 10     | 7.69%   |
| 2.01-3.0   | 1        | 1      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 19       | 26.76%  |
| 501-1000       | 14       | 19.72%  |
| 101-250        | 13       | 18.31%  |
| 251-500        | 12       | 16.9%   |
| More than 3000 | 4        | 5.63%   |
| 2001-3000      | 4        | 5.63%   |
| 51-100         | 4        | 5.63%   |
| Unknown        | 1        | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 16       | 21.33%  |
| 501-1000       | 15       | 20%     |
| 21-50          | 13       | 17.33%  |
| 1-20           | 11       | 14.67%  |
| 251-500        | 9        | 12%     |
| 51-100         | 4        | 5.33%   |
| 1001-2000      | 3        | 4%      |
| 2001-3000      | 2        | 2.67%   |
| More than 3000 | 1        | 1.33%   |
| Unknown        | 1        | 1.33%   |

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
| Works    | 40       | 70     | 47.62%  |
| Detected | 34       | 82     | 40.48%  |
| Malfunc  | 9        | 10     | 10.71%  |
| Failed   | 1        | 1      | 1.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 52       | 50.98%  |
| AMD                          | 14       | 13.73%  |
| ASMedia Technology           | 6        | 5.88%   |
| Phison Electronics           | 5        | 4.9%    |
| Silicon Motion               | 4        | 3.92%   |
| Marvell Technology Group     | 4        | 3.92%   |
| Samsung Electronics          | 3        | 2.94%   |
| Shenzhen Longsys Electronics | 2        | 1.96%   |
| Kingston Technology Company  | 2        | 1.96%   |
| Beijing Starblaze Technology | 2        | 1.96%   |
| Zhaoxin                      | 1        | 0.98%   |
| SanDisk                      | 1        | 0.98%   |
| Realtek Semiconductor        | 1        | 0.98%   |
| Nvidia                       | 1        | 0.98%   |
| Micron/Crucial Technology    | 1        | 0.98%   |
| Loongson Technology          | 1        | 0.98%   |
| JMicron Technology           | 1        | 0.98%   |
| ADATA Technology             | 1        | 0.98%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 6.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8        | 6.78%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 6.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 5.08%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 6        | 5.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 4.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.39%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 2.54%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 2.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 2.54%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 2.54%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 2.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.54%   |
| Shenzhen Longsys FORESEE P900 BGA NVMe SSD (DRAM-less)                                  | 2        | 1.69%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 1.69%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 1.69%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.69%   |
| Beijing Starblaze STAR1200C NVMe SSD                                                    | 2        | 1.69%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 1.69%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G/KH-40000/KX-7000 StorX AHCI Controller           | 1        | 0.85%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.85%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 1        | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.85%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 1        | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.85%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1        | 0.85%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.85%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.85%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.85%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 0.85%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.85%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 0.85%   |
| Loongson SATA AHCI Controller                                                           | 1        | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 59       | 62.77%  |
| NVMe | 19       | 20.21%  |
| IDE  | 14       | 14.89%  |
| RAID | 2        | 2.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 53       | 75.71%  |
| AMD          | 15       | 21.43%  |
| CentaurHauls | 1        | 1.43%   |
| Unknown      | 1        | 1.43%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-10700 CPU @ 2.90GHz           | 6        | 8.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 5.71%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 5.71%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 2.86%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 2.86%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 2.86%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 2.86%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 2.86%   |
| Intel Xeon CPU W3503 @ 2.40GHz              | 1        | 1.43%   |
| Intel Xeon CPU L5640 @ 2.27GHz              | 1        | 1.43%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 1.43%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 1.43%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 1.43%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.43%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 1.43%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.43%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.43%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.43%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.43%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 1.43%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.43%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.43%   |
| Intel Core i7 CPU 975 @ 3.33GHz             | 1        | 1.43%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.43%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.43%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.43%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.43%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.43%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 1        | 1.43%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.43%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 1        | 1.43%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 1.43%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 1        | 1.43%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.43%   |
| Intel Core i3-4160T CPU @ 3.10GHz           | 1        | 1.43%   |
| Intel Core i3-3240T CPU @ 2.90GHz           | 1        | 1.43%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 1.43%   |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 1.43%   |
| Intel Celeron CPU G1840 @ 2.80GHz           | 1        | 1.43%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 1        | 1.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 20       | 28.57%  |
| Intel Core i3           | 9        | 12.86%  |
| Intel Core i5           | 8        | 11.43%  |
| AMD Ryzen 5             | 5        | 7.14%   |
| Other                   | 4        | 5.71%   |
| Intel Xeon              | 4        | 5.71%   |
| Intel Core 2 Duo        | 4        | 5.71%   |
| Intel Celeron           | 4        | 5.71%   |
| AMD FX                  | 4        | 5.71%   |
| AMD Ryzen 9             | 2        | 2.86%   |
| Intel Pentium Silver    | 1        | 1.43%   |
| Intel Pentium Dual-Core | 1        | 1.43%   |
| Intel Core i9           | 1        | 1.43%   |
| AMD Ryzen 3             | 1        | 1.43%   |
| AMD C-60                | 1        | 1.43%   |
| AMD Athlon              | 1        | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 34       | 48.57%  |
| 2      | 17       | 24.29%  |
| 8      | 7        | 10%     |
| 6      | 7        | 10%     |
| 24     | 1        | 1.43%   |
| 16     | 1        | 1.43%   |
| 12     | 1        | 1.43%   |
| 10     | 1        | 1.43%   |
| 3      | 1        | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 70       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 43       | 61.43%  |
| 1      | 27       | 38.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 65       | 92.86%  |
| Unknown        | 5        | 7.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 28.17%  |
| 0x306c3    | 9        | 12.68%  |
| 0x306a9    | 9        | 12.68%  |
| 0xa0655    | 5        | 7.04%   |
| 0x1067a    | 4        | 5.63%   |
| 0x906e9    | 3        | 4.23%   |
| 0x206a7    | 2        | 2.82%   |
| 0xb0671    | 1        | 1.41%   |
| 0xa0653    | 1        | 1.41%   |
| 0x906eb    | 1        | 1.41%   |
| 0x706a8    | 1        | 1.41%   |
| 0x506e3    | 1        | 1.41%   |
| 0x306f2    | 1        | 1.41%   |
| 0x206c2    | 1        | 1.41%   |
| 0x0a50000d | 1        | 1.41%   |
| 0x0a201016 | 1        | 1.41%   |
| 0x08701021 | 1        | 1.41%   |
| 0x08701013 | 1        | 1.41%   |
| 0x08101016 | 1        | 1.41%   |
| 0x08001138 | 1        | 1.41%   |
| 0x08001137 | 1        | 1.41%   |
| 0x07026101 | 1        | 1.41%   |
| 0x06000822 | 1        | 1.41%   |
| 0x06000629 | 1        | 1.41%   |
| 0x06000626 | 1        | 1.41%   |
| 0x0500010d | 1        | 1.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 11       | 15.71%  |
| Haswell          | 10       | 14.29%  |
| CometLake        | 9        | 12.86%  |
| Penryn           | 6        | 8.57%   |
| KabyLake         | 5        | 7.14%   |
| Zen 2            | 3        | 4.29%   |
| Zen              | 3        | 4.29%   |
| Skylake          | 3        | 4.29%   |
| SandyBridge      | 3        | 4.29%   |
| Unknown          | 3        | 4.29%   |
| Zen 3            | 2        | 2.86%   |
| Piledriver       | 2        | 2.86%   |
| Nehalem          | 2        | 2.86%   |
| Goldmont plus    | 2        | 2.86%   |
| Bulldozer        | 2        | 2.86%   |
| Westmere         | 1        | 1.43%   |
| Jaguar           | 1        | 1.43%   |
| Bobcat           | 1        | 1.43%   |
| Alderlake Hybrid | 1        | 1.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Nvidia              | 30       | 38.46%  |
| Intel               | 23       | 29.49%  |
| AMD                 | 23       | 29.49%  |
| Zhaoxin             | 1        | 1.28%   |
| Loongson Technology | 1        | 1.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 6.33%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 5        | 6.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 5.06%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 3.8%    |
| Intel HD Graphics 630                                                       | 3        | 3.8%    |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.53%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.53%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 2.53%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.53%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.53%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.53%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 2.53%   |
| Zhaoxin KX-6000 C-960 GPU                                                   | 1        | 1.27%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.27%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.27%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.27%   |
| Nvidia GP106 [P106-100]                                                     | 1        | 1.27%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.27%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.27%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.27%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.27%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.27%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.27%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.27%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.27%   |
| Nvidia GK104 [GeForce GTX 760 OEM]                                          | 1        | 1.27%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.27%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 1.27%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.27%   |
| Nvidia GF116 [GeForce GT 545]                                               | 1        | 1.27%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 1.27%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.27%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 1        | 1.27%   |
| Loongson Technology Vivante GPU (Graphics Processing Unit)                  | 1        | 1.27%   |
| Loongson Technology DC (Display Controller)                                 | 1        | 1.27%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 1.27%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Nvidia              | 27       | 38.57%  |
| 1 x AMD                 | 20       | 28.57%  |
| 1 x Intel               | 16       | 22.86%  |
| Intel + Nvidia          | 2        | 2.86%   |
| Intel + AMD             | 2        | 2.86%   |
| 1 x Zhaoxin             | 1        | 1.43%   |
| 1 x Loongson Technology | 1        | 1.43%   |
| AMD + Nvidia            | 1        | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 47       | 67.14%  |
| Proprietary | 18       | 25.71%  |
| Unknown     | 5        | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 45.83%  |
| 1.01-2.0   | 17       | 23.61%  |
| 3.01-4.0   | 6        | 8.33%   |
| 7.01-8.0   | 5        | 6.94%   |
| 0.51-1.0   | 4        | 5.56%   |
| 5.01-6.0   | 3        | 4.17%   |
| 0.01-0.5   | 3        | 4.17%   |
| 16.01-24.0 | 1        | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 14       | 20%     |
| Goldstar             | 8        | 11.43%  |
| Hewlett-Packard      | 5        | 7.14%   |
| ViewSonic            | 4        | 5.71%   |
| Dell                 | 4        | 5.71%   |
| AOC                  | 4        | 5.71%   |
| Philips              | 3        | 4.29%   |
| Ancor Communications | 3        | 4.29%   |
| Lenovo               | 2        | 2.86%   |
| Iiyama               | 2        | 2.86%   |
| HKC                  | 2        | 2.86%   |
| BenQ                 | 2        | 2.86%   |
| Acer                 | 2        | 2.86%   |
| Xiaomi               | 1        | 1.43%   |
| Unknown              | 1        | 1.43%   |
| Toshiba              | 1        | 1.43%   |
| TFC                  | 1        | 1.43%   |
| SKY                  | 1        | 1.43%   |
| RTK                  | 1        | 1.43%   |
| Positivo             | 1        | 1.43%   |
| Packard Bell         | 1        | 1.43%   |
| MSI                  | 1        | 1.43%   |
| Hisense              | 1        | 1.43%   |
| HannStar             | 1        | 1.43%   |
| Gateway              | 1        | 1.43%   |
| DTV                  | 1        | 1.43%   |
| BOE                  | 1        | 1.43%   |
| ASUSTek Computer     | 1        | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch              | 3        | 3.9%    |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 1872x1053mm 84.6-inch | 2        | 2.6%    |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                    | 2        | 2.6%    |
| Xiaomi Mi TV XMD0076 3840x2160 800x450mm 36.1-inch                      | 1        | 1.3%    |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch              | 1        | 1.3%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 1.3%    |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                         | 1        | 1.3%    |
| TFC TF2411 TFC0238 1920x1080 527x296mm 23.8-inch                        | 1        | 1.3%    |
| SKY 24X1Q SKY2380 2560x1440 520x290mm 23.4-inch                         | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch    | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM0601 1600x900                         | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch     | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch    | 1        | 1.3%    |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch     | 1        | 1.3%    |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch       | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SMS23A350H 1920x1080                    | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM0E90 1366x768 609x347mm 27.6-inch    | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 1210x680mm 54.6-inch  | 1        | 1.3%    |
| Samsung Electronics LCD Monitor S24E390 1920x1080                       | 1        | 1.3%    |
| Samsung Electronics LCD Monitor S24E360 1920x1080                       | 1        | 1.3%    |
| Samsung Electronics LCD Monitor S24E310 3840x1080                       | 1        | 1.3%    |
| Samsung Electronics LCD Monitor S24E310                                 | 1        | 1.3%    |
| Samsung Electronics LCD Monitor LC49G95T 3840x1080                      | 1        | 1.3%    |
| RTK QHD HDR RTKBC32 2560x1440 597x336mm 27.0-inch                       | 1        | 1.3%    |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                    | 1        | 1.3%    |
| Philips FTV PHL04C2 1920x1080 1440x810mm 65.0-inch                      | 1        | 1.3%    |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                     | 1        | 1.3%    |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                      | 1        | 1.3%    |
| Packard Bell Viseo223DX PKB0385 1920x1080 477x268mm 21.5-inch           | 1        | 1.3%    |
| MSI MAG271C MSI3FA6 1920x1080 598x336mm 27.0-inch                       | 1        | 1.3%    |
| Lenovo T24s-28 LEN62C7 1920x1080 527x296mm 23.8-inch                    | 1        | 1.3%    |
| Lenovo LEN T2324C LEN60F2 1920x1080 510x287mm 23.0-inch                 | 1        | 1.3%    |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                    | 1        | 1.3%    |
| Iiyama PL2792Q IVM662F 2560x1440 597x336mm 27.0-inch                    | 1        | 1.3%    |
| HKC PL24V2 HKC0238 1920x1080 527x296mm 23.8-inch                        | 1        | 1.3%    |
| HKC 27E6QC HKC274F 2560x1440 597x336mm 27.0-inch                        | 1        | 1.3%    |
| Hisense LCD Monitor HDMI 1360x768                                       | 1        | 1.3%    |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch            | 1        | 1.3%    |
| Hewlett-Packard Compaq F191 HWP3177 1366x768 410x230mm 18.5-inch        | 1        | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 35       | 49.3%   |
| 3840x2160 (4K)     | 8        | 11.27%  |
| 2560x1440 (QHD)    | 6        | 8.45%   |
| 1600x900 (HD+)     | 4        | 5.63%   |
| 3840x1080          | 3        | 4.23%   |
| 1440x900 (WXGA+)   | 3        | 4.23%   |
| 1680x1050 (WSXGA+) | 2        | 2.82%   |
| 1366x768 (WXGA)    | 2        | 2.82%   |
| 1360x768           | 2        | 2.82%   |
| Unknown            | 2        | 2.82%   |
| 2288x1287          | 1        | 1.41%   |
| 1920x540           | 1        | 1.41%   |
| 1920x1200 (WUXGA)  | 1        | 1.41%   |
| 1280x1024 (SXGA)   | 1        | 1.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 19       | 26.39%  |
| Unknown | 10       | 13.89%  |
| 24      | 8        | 11.11%  |
| 27      | 7        | 9.72%   |
| 21      | 5        | 6.94%   |
| 84      | 4        | 5.56%   |
| 20      | 3        | 4.17%   |
| 19      | 3        | 4.17%   |
| 18      | 3        | 4.17%   |
| 22      | 2        | 2.78%   |
| 142     | 1        | 1.39%   |
| 72      | 1        | 1.39%   |
| 65      | 1        | 1.39%   |
| 54      | 1        | 1.39%   |
| 32      | 1        | 1.39%   |
| 31      | 1        | 1.39%   |
| 25      | 1        | 1.39%   |
| 12      | 1        | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 34       | 48.57%  |
| 401-500        | 15       | 21.43%  |
| Unknown        | 10       | 14.29%  |
| 1501-2000      | 5        | 7.14%   |
| 1001-1500      | 2        | 2.86%   |
| More than 2000 | 1        | 1.43%   |
| 701-800        | 1        | 1.43%   |
| 601-700        | 1        | 1.43%   |
| 201-300        | 1        | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 52       | 77.61%  |
| Unknown | 9        | 13.43%  |
| 16/10   | 5        | 7.46%   |
| 1.00    | 1        | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 28       | 40%     |
| Unknown        | 10       | 14.29%  |
| 151-200        | 9        | 12.86%  |
| More than 1000 | 8        | 11.43%  |
| 301-350        | 7        | 10%     |
| 251-300        | 3        | 4.29%   |
| 351-500        | 2        | 2.86%   |
| 141-150        | 2        | 2.86%   |
| 61-70          | 1        | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 44       | 63.77%  |
| Unknown | 10       | 14.49%  |
| 101-120 | 9        | 13.04%  |
| 1-50    | 4        | 5.8%    |
| 161-240 | 1        | 1.45%   |
| 121-160 | 1        | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 57       | 80.28%  |
| 2     | 12       | 16.9%   |
| 0     | 2        | 2.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 45       | 47.37%  |
| Intel                    | 24       | 25.26%  |
| Broadcom                 | 5        | 5.26%   |
| Qualcomm Atheros         | 4        | 4.21%   |
| TP-Link                  | 3        | 3.16%   |
| Xiaomi                   | 2        | 2.11%   |
| MediaTek                 | 2        | 2.11%   |
| Unknown                  | 1        | 1.05%   |
| Ralink Technology        | 1        | 1.05%   |
| Ralink                   | 1        | 1.05%   |
| NXP Semiconductors       | 1        | 1.05%   |
| Nvidia                   | 1        | 1.05%   |
| NetGear                  | 1        | 1.05%   |
| Marvell Technology Group | 1        | 1.05%   |
| Loongson Technology      | 1        | 1.05%   |
| IMC Networks             | 1        | 1.05%   |
| Aquantia                 | 1        | 1.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 37       | 34.26%  |
| Intel Ethernet Connection (12) I219-V                                  | 4        | 3.7%    |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 2.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 1.85%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)              | 2        | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 1.85%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 1.85%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 1.85%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 1.85%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 1.85%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 2        | 1.85%   |
| Unknown Network controller                                             | 1        | 0.93%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 0.93%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.93%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 0.93%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.93%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 0.93%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                 | 1        | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.93%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 0.93%   |
| NetGear A6210                                                          | 1        | 0.93%   |
| MediaTek RMX3085                                                       | 1        | 0.93%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                    | 1        | 0.93%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.93%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 0.93%   |
| Loongson Gigabit Ethernet Controller                                   | 1        | 0.93%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 0.93%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 1        | 0.93%   |
| Intel Ethernet Controller I226-V                                       | 1        | 0.93%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.93%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 30.77%  |
| Intel                 | 7        | 26.92%  |
| TP-Link               | 3        | 11.54%  |
| Qualcomm Atheros      | 2        | 7.69%   |
| Ralink Technology     | 1        | 3.85%   |
| Ralink                | 1        | 3.85%   |
| NetGear               | 1        | 3.85%   |
| MediaTek              | 1        | 3.85%   |
| IMC Networks          | 1        | 3.85%   |
| Broadcom              | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)  | 2        | 7.69%   |
| Intel Wi-Fi 6 AX200                                        | 2        | 7.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 3.85%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 3.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1        | 3.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 3.85%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1        | 3.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 3.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1        | 3.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 3.85%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 3.85%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 3.85%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1        | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 3.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1        | 3.85%   |
| NetGear A6210                                              | 1        | 3.85%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter        | 1        | 3.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]    | 1        | 3.85%   |
| Intel Raptor Lake-S PCH CNVi WiFi                          | 1        | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 3.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1        | 3.85%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1        | 3.85%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]       | 1        | 3.85%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 44       | 56.41%  |
| Intel                    | 21       | 26.92%  |
| Broadcom                 | 4        | 5.13%   |
| Xiaomi                   | 2        | 2.56%   |
| Qualcomm Atheros         | 2        | 2.56%   |
| Nvidia                   | 1        | 1.28%   |
| MediaTek                 | 1        | 1.28%   |
| Marvell Technology Group | 1        | 1.28%   |
| Loongson Technology      | 1        | 1.28%   |
| Aquantia                 | 1        | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 37       | 46.25%  |
| Intel Ethernet Connection (12) I219-V                                  | 4        | 5%      |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 3.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 2.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 2.5%    |
| Intel I211 Gigabit Network Connection                                  | 2        | 2.5%    |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 2.5%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 2.5%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 2        | 2.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 1.25%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 1.25%   |
| MediaTek RMX3085                                                       | 1        | 1.25%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 1.25%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 1.25%   |
| Loongson Gigabit Ethernet Controller                                   | 1        | 1.25%   |
| Intel Ethernet Controller I226-V                                       | 1        | 1.25%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.25%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 1.25%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.25%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1        | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 1.25%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 1.25%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 1.25%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 1.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 1.25%   |
| Intel 82575EB Gigabit Network Connection                               | 1        | 1.25%   |
| Intel 82567LM-2 Gigabit Network Connection                             | 1        | 1.25%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 1.25%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 1        | 1.25%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]      | 1        | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 70       | 71.43%  |
| WiFi     | 26       | 26.53%  |
| Modem    | 1        | 1.02%   |
| Unknown  | 1        | 1.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 58       | 82.86%  |
| WiFi     | 12       | 17.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 50       | 70.42%  |
| 2     | 16       | 22.54%  |
| 3     | 4        | 5.63%   |
| 4     | 1        | 1.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 91.43%  |
| Yes  | 6        | 8.57%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 11       | 44%     |
| Intel                           | 7        | 28%     |
| Realtek Semiconductor           | 1        | 4%      |
| Qualcomm Atheros Communications | 1        | 4%      |
| MediaTek                        | 1        | 4%      |
| Lite-On Technology              | 1        | 4%      |
| Dynex                           | 1        | 4%      |
| Broadcom                        | 1        | 4%      |
| ASUSTek Computer                | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 11       | 44%     |
| Intel AX200 Bluetooth                                    | 2        | 8%      |
| Realtek Bluetooth Radio                                  | 1        | 4%      |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 4%      |
| MediaTek BT                                              | 1        | 4%      |
| Lite-On Bluetooth Device                                 | 1        | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1        | 4%      |
| Intel Wireless-AC 3168 Bluetooth                         | 1        | 4%      |
| Intel Bluetooth wireless interface                       | 1        | 4%      |
| Intel AX211 Bluetooth                                    | 1        | 4%      |
| Intel AX201 Bluetooth                                    | 1        | 4%      |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 4%      |
| Broadcom HP Portable Bumble Bee                          | 1        | 4%      |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 53       | 44.17%  |
| AMD                                          | 30       | 25%     |
| Nvidia                                       | 27       | 22.5%   |
| C-Media Electronics                          | 2        | 1.67%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.83%   |
| Zhaoxin                                      | 1        | 0.83%   |
| XMOS                                         | 1        | 0.83%   |
| Microdia                                     | 1        | 0.83%   |
| Loongson Technology                          | 1        | 0.83%   |
| Generalplus Technology                       | 1        | 0.83%   |
| BEHRINGER International                      | 1        | 0.83%   |
| ASUSTek Computer                             | 1        | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                     | Desktops | Percent |
|-------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                       | 9        | 6.82%   |
| Intel Comet Lake PCH-V cAVS                                                               | 8        | 6.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                       | 7        | 5.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                | 7        | 5.3%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                   | 7        | 5.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                          | 4        | 3.03%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                          | 4        | 3.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                           | 4        | 3.03%   |
| AMD Starship/Matisse HD Audio Controller                                                  | 4        | 3.03%   |
| Nvidia GM204 High Definition Audio Controller                                             | 3        | 2.27%   |
| Nvidia GF116 High Definition Audio Controller                                             | 3        | 2.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                   | 3        | 2.27%   |
| Intel 200 Series PCH HD Audio                                                             | 3        | 2.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                              | 3        | 2.27%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]         | 3        | 2.27%   |
| Nvidia High Definition Audio Controller                                                   | 2        | 1.52%   |
| Nvidia GP106 High Definition Audio Controller                                             | 2        | 1.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                     | 2        | 1.52%   |
| Nvidia GK107 HDMI Audio Controller                                                        | 2        | 1.52%   |
| Nvidia GF119 HDMI Audio Controller                                                        | 2        | 1.52%   |
| Nvidia GA104 High Definition Audio Controller                                             | 2        | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                              | 2        | 1.52%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                       | 2        | 1.52%   |
| AMD FCH Azalia Controller                                                                 | 2        | 1.52%   |
| AMD Family 17h/19h HD Audio Controller                                                    | 2        | 1.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                       | 2        | 1.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                | 2        | 1.52%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                            | 1        | 0.76%   |
| Zhaoxin ZX-E High Definition Audio Controller                                             | 1        | 0.76%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller | 1        | 0.76%   |
| XMOS iFi (by AMR) HD USB Audio                                                            | 1        | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                                             | 1        | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                            | 1        | 0.76%   |
| Nvidia MCP61 High Definition Audio                                                        | 1        | 0.76%   |
| Nvidia GP108 High Definition Audio Controller                                             | 1        | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                                           | 1        | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                                             | 1        | 0.76%   |
| Nvidia GM206 High Definition Audio Controller                                             | 1        | 0.76%   |
| Nvidia GK106 HDMI Audio Controller                                                        | 1        | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                                        | 1        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston                           | 13       | 31.71%  |
| Unknown                            | 5        | 12.2%   |
| Samsung Electronics                | 3        | 7.32%   |
| G.Skill                            | 3        | 7.32%   |
| Corsair                            | 3        | 7.32%   |
| SK hynix                           | 2        | 4.88%   |
| Unknown                            | 2        | 4.88%   |
| Team                               | 1        | 2.44%   |
| Ramaxel Technology                 | 1        | 2.44%   |
| Nanya Technology                   | 1        | 2.44%   |
| KINGBANK                           | 1        | 2.44%   |
| Kimtigo Semiconductor (HK) Limited | 1        | 2.44%   |
| Elpida                             | 1        | 2.44%   |
| CSX                                | 1        | 2.44%   |
| Crucial                            | 1        | 2.44%   |
| Apacer                             | 1        | 2.44%   |
| A-DATA Technology                  | 1        | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Kingston RAM TF32D4U2S1MEH-8 8192MB DIMM DDR4 3200MT/s     | 3        | 6.67%   |
| Unknown                                                    | 2        | 4.44%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                  | 1        | 2.22%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s               | 1        | 2.22%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                     | 1        | 2.22%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1        | 2.22%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s         | 1        | 2.22%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s         | 1        | 2.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1        | 2.22%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s       | 1        | 2.22%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 1        | 2.22%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 2.22%   |
| Samsung RAM M378B1G73DB0-CK0 8192MB DIMM DDR3 2133MT/s     | 1        | 2.22%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s        | 1        | 2.22%   |
| Ramaxel RAM RMSA3230KE68H9F213 4096MB SODIMM DDR4 2133MT/s | 1        | 2.22%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s         | 1        | 2.22%   |
| Kingston RAM Module 4GB DIMM DDR3 1067MT/s                 | 1        | 2.22%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s             | 1        | 2.22%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 1        | 2.22%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 2.22%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s          | 1        | 2.22%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s        | 1        | 2.22%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s        | 1        | 2.22%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s        | 1        | 2.22%   |
| Kingston RAM BRAP1G48GB16C1600 8192MB DIMM DDR3 1600MT/s   | 1        | 2.22%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 2.22%   |
| Kingston RAM 99U5403-034.A00LF 4096MB DIMM DDR3 1333MT/s   | 1        | 2.22%   |
| Kingston RAM 99P5471-048.A00LF 8192MB DIMM DDR3 1600MT/s   | 1        | 2.22%   |
| Kingston RAM 99P5471-016.A00LF 8192MB DIMM DDR3 1600MT/s   | 1        | 2.22%   |
| KINGBANK RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 2.22%   |
| Kimtigo (HK) Limited RAM Module 8192MB DIMM DDR4 2666MT/s  | 1        | 2.22%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s       | 1        | 2.22%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s         | 1        | 2.22%   |
| G.Skill RAM F3-14900CL10-8GBXL 8GB DIMM DDR3 1867MT/s      | 1        | 2.22%   |
| Elpida RAM EBJ10UE8BBF0-AE-F 1GB DIMM DDR3 1066MT/s        | 1        | 2.22%   |
| CSX RAM V01D3LF4GB26826813 4GB DIMM DDR3                   | 1        | 2.22%   |
| Crucial RAM Module 4GB DIMM DDR3 1600MT/s                  | 1        | 2.22%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s       | 1        | 2.22%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s      | 1        | 2.22%   |
| Corsair RAM CMK16GX4M1B3000C15 16GB DIMM DDR4 3400MT/s     | 1        | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 19       | 52.78%  |
| DDR3    | 14       | 38.89%  |
| Unknown | 2        | 5.56%   |
| SDRAM   | 1        | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 33       | 91.67%  |
| SODIMM | 3        | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 21       | 53.85%  |
| 4096  | 9        | 23.08%  |
| 16384 | 5        | 12.82%  |
| 1024  | 2        | 5.13%   |
| 32768 | 1        | 2.56%   |
| 2048  | 1        | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 7        | 16.67%  |
| 3600    | 3        | 7.14%   |
| 3200    | 3        | 7.14%   |
| 2667    | 3        | 7.14%   |
| 2133    | 3        | 7.14%   |
| 1867    | 3        | 7.14%   |
| 3400    | 2        | 4.76%   |
| 2666    | 2        | 4.76%   |
| 2400    | 2        | 4.76%   |
| 1333    | 2        | 4.76%   |
| 1067    | 2        | 4.76%   |
| 4266    | 1        | 2.38%   |
| 3800    | 1        | 2.38%   |
| 3500    | 1        | 2.38%   |
| 3466    | 1        | 2.38%   |
| 3066    | 1        | 2.38%   |
| 3000    | 1        | 2.38%   |
| 1866    | 1        | 2.38%   |
| 1066    | 1        | 2.38%   |
| 667     | 1        | 2.38%   |
| Unknown | 1        | 2.38%   |

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
| Microdia               | 1        | 9.09%   |
| Generalplus Technology | 1        | 9.09%   |
| Chicony Electronics    | 1        | 9.09%   |
| Arkmicro Technologies  | 1        | 9.09%   |
| 2M UVC CAMERA          | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 4        | 36.36%  |
| Microdia Integrated_Webcam_HD         | 1        | 9.09%   |
| Logitech Webcam C200                  | 1        | 9.09%   |
| Logitech HD Pro Webcam C920           | 1        | 9.09%   |
| Generalplus CAMERA - UVC              | 1        | 9.09%   |
| Chicony HP High Definition 1MP Webcam | 1        | 9.09%   |
| Arkmicro USB2.0 PC CAMERA             | 1        | 9.09%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam   | 1        | 9.09%   |

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
| 0     | 62       | 88.57%  |
| 1     | 6        | 8.57%   |
| 2     | 2        | 2.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 5        | 55.56%  |
| Net/wireless  | 4        | 44.44%  |

