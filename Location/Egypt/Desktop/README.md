Linux in Egypt - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Egypt.

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

Total: 203

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte  | G41MT-S2P                   | [abb09d2f8e](https://linux-hardware.org/?probe=abb09d2f8e) | Mar 17, 2023 |
| Dell      | 073MMW A02                  | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| Gigabyte  | H87M-HD3                    | [778b7898e3](https://linux-hardware.org/?probe=778b7898e3) | Feb 17, 2023 |
| HP        | 2B34                        | [3376fc38b3](https://linux-hardware.org/?probe=3376fc38b3) | Feb 05, 2023 |
| HP        | 802F                        | [b36a46a944](https://linux-hardware.org/?probe=b36a46a944) | Feb 03, 2023 |
| Gigabyte  | GA-MA78G-DS3H               | [9a1bab8f2c](https://linux-hardware.org/?probe=9a1bab8f2c) | Jan 26, 2023 |
| Lenovo    | ThinkCentre M58 6258D3G     | [8bc1c22b23](https://linux-hardware.org/?probe=8bc1c22b23) | Jan 25, 2023 |
| Gigabyte  | F2A68HM-HD2                 | [fc8a27e6c5](https://linux-hardware.org/?probe=fc8a27e6c5) | Jan 17, 2023 |
| ASRock    | X570 Phantom Gaming 4       | [482cc76bce](https://linux-hardware.org/?probe=482cc76bce) | Jan 14, 2023 |
| ASRock    | X570 Phantom Gaming 4       | [662223c5f6](https://linux-hardware.org/?probe=662223c5f6) | Jan 14, 2023 |
| HP        | 3047h                       | [0dd7c7c08f](https://linux-hardware.org/?probe=0dd7c7c08f) | Jan 11, 2023 |
| Lenovo    | SHARKBAY 0B98401 PRO        | [cedf3a8ef8](https://linux-hardware.org/?probe=cedf3a8ef8) | Jan 07, 2023 |
| Gigabyte  | GA-990FXA-D3                | [30822e6e18](https://linux-hardware.org/?probe=30822e6e18) | Dec 22, 2022 |
| Lenovo    | ThinkCentre M58 6258D3G     | [1613228bb2](https://linux-hardware.org/?probe=1613228bb2) | Dec 08, 2022 |
| Lenovo    | ThinkCentre M58 6258D3G     | [04a09baf04](https://linux-hardware.org/?probe=04a09baf04) | Dec 08, 2022 |
| ASUSTek   | P6T                         | [8268d853c9](https://linux-hardware.org/?probe=8268d853c9) | Dec 06, 2022 |
| HP        | 1850                        | [1d0a3a4461](https://linux-hardware.org/?probe=1d0a3a4461) | Nov 29, 2022 |
| Pegatron  | 2A94h                       | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| Acer      | Predator PO3-630            | [aae61f30c7](https://linux-hardware.org/?probe=aae61f30c7) | Oct 20, 2022 |
| HP        | 18E7                        | [98b59ebfce](https://linux-hardware.org/?probe=98b59ebfce) | Oct 13, 2022 |
| HP        | 0AA0h                       | [f4a69ac6f5](https://linux-hardware.org/?probe=f4a69ac6f5) | Oct 13, 2022 |
| ASUSTek   | TUF Gaming B450M-PRO S      | [6f0af51d33](https://linux-hardware.org/?probe=6f0af51d33) | Oct 06, 2022 |
| ASUSTek   | TUF Gaming B450M-PRO S      | [843cabf6e6](https://linux-hardware.org/?probe=843cabf6e6) | Oct 06, 2022 |
| HP        | 1850                        | [f111f19884](https://linux-hardware.org/?probe=f111f19884) | Oct 04, 2022 |
| MSI       | B450 TOMAHAWK MAX           | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| HP        | 843C                        | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| Dell      | 0D441T A01                  | [c315329853](https://linux-hardware.org/?probe=c315329853) | Sep 20, 2022 |
| Gigabyte  | H510M S2H                   | [f004b06a17](https://linux-hardware.org/?probe=f004b06a17) | Sep 12, 2022 |
| Gigabyte  | G31M-S2C                    | [91001df765](https://linux-hardware.org/?probe=91001df765) | Sep 04, 2022 |
| Gigabyte  | G31M-S2C                    | [9281a357e0](https://linux-hardware.org/?probe=9281a357e0) | Sep 04, 2022 |
| Gigabyte  | G31M-S2C                    | [ac5ecfc107](https://linux-hardware.org/?probe=ac5ecfc107) | Sep 04, 2022 |
| Gigabyte  | H61M-S2P                    | [49aedf1cf8](https://linux-hardware.org/?probe=49aedf1cf8) | Aug 17, 2022 |
| HP        | 18E7                        | [06374a6240](https://linux-hardware.org/?probe=06374a6240) | Aug 14, 2022 |
| HP        | 1850                        | [33933e3e5d](https://linux-hardware.org/?probe=33933e3e5d) | Aug 12, 2022 |
| HP        | 18E4                        | [d13265fa57](https://linux-hardware.org/?probe=d13265fa57) | Jul 29, 2022 |
| HP        | 3647h                       | [ed98e07a47](https://linux-hardware.org/?probe=ed98e07a47) | Jul 26, 2022 |
| Dell      | 0200DY A01                  | [99eacb5700](https://linux-hardware.org/?probe=99eacb5700) | Jul 11, 2022 |
| MSI       | B450 TOMAHAWK MAX           | [21dd020507](https://linux-hardware.org/?probe=21dd020507) | Jul 01, 2022 |
| ASUSTek   | P5GC-MX/1333                | [428eebd42f](https://linux-hardware.org/?probe=428eebd42f) | Jun 13, 2022 |
| Dell      | 0GY6Y8 A03                  | [4668e3772e](https://linux-hardware.org/?probe=4668e3772e) | Jun 05, 2022 |
| Dell      | 040DDP A01                  | [208a2ee137](https://linux-hardware.org/?probe=208a2ee137) | Jun 02, 2022 |
| HP        | 0A80h                       | [7e5c6cf61e](https://linux-hardware.org/?probe=7e5c6cf61e) | May 27, 2022 |
| Dell      | 03NVJ6 A04                  | [ebacf887d7](https://linux-hardware.org/?probe=ebacf887d7) | May 04, 2022 |
| Dell      | 08WKV3 A00                  | [e6ef37e2a0](https://linux-hardware.org/?probe=e6ef37e2a0) | Apr 24, 2022 |
| HP        | 8053                        | [f214dbdf74](https://linux-hardware.org/?probe=f214dbdf74) | Apr 23, 2022 |
| Lenovo    | ThinkCentre M58 6258D3G     | [b84eab559e](https://linux-hardware.org/?probe=b84eab559e) | Apr 21, 2022 |
| HP        | 18E7                        | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| HP        | 8265                        | [6a7abd0db8](https://linux-hardware.org/?probe=6a7abd0db8) | Apr 19, 2022 |
| Dell      | 08WKV3 A00                  | [f3afe20dae](https://linux-hardware.org/?probe=f3afe20dae) | Apr 16, 2022 |
| Dell      | 0WK833                      | [efee7c0ec6](https://linux-hardware.org/?probe=efee7c0ec6) | Apr 02, 2022 |
| Dell      | 0WK833                      | [a8703c7598](https://linux-hardware.org/?probe=a8703c7598) | Apr 02, 2022 |
| Lenovo    | ThinkCentre M58 6258D3G     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo    | ThinkCentre M58 6258D3G     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| ASUSTek   | B250 MINING EXPERT          | [2da8f96ad8](https://linux-hardware.org/?probe=2da8f96ad8) | Mar 29, 2022 |
| Gigabyte  | H110M-S2PT-CF               | [506afdf9c7](https://linux-hardware.org/?probe=506afdf9c7) | Mar 09, 2022 |
| Intel     | DQ965MT AAD36265-505        | [93758c64fa](https://linux-hardware.org/?probe=93758c64fa) | Mar 07, 2022 |
| Dell      | 0XG309                      | [535c8e4e2e](https://linux-hardware.org/?probe=535c8e4e2e) | Feb 28, 2022 |
| Dell      | 0XG309                      | [d9f753df89](https://linux-hardware.org/?probe=d9f753df89) | Feb 28, 2022 |
| MSI       | MAG X570 TOMAHAWK WIFI      | [f0692aebbe](https://linux-hardware.org/?probe=f0692aebbe) | Feb 25, 2022 |
| Gigabyte  | Z87-HD3                     | [d1fd917c74](https://linux-hardware.org/?probe=d1fd917c74) | Feb 24, 2022 |
| HP        | 3397                        | [de499e61b9](https://linux-hardware.org/?probe=de499e61b9) | Feb 22, 2022 |
| Gigabyte  | G41MT-S2PT                  | [2ddf4948c9](https://linux-hardware.org/?probe=2ddf4948c9) | Feb 19, 2022 |
| Gigabyte  | GA-MA78G-DS3H               | [d799c9b2f2](https://linux-hardware.org/?probe=d799c9b2f2) | Feb 18, 2022 |
| Dell      | 0C27VV A01                  | [5760b6c177](https://linux-hardware.org/?probe=5760b6c177) | Feb 14, 2022 |
| HP        | 3397                        | [06f2eef752](https://linux-hardware.org/?probe=06f2eef752) | Feb 13, 2022 |
| HP        | 1906                        | [c2107ad290](https://linux-hardware.org/?probe=c2107ad290) | Feb 08, 2022 |
| HP        | 1906                        | [9f08673e43](https://linux-hardware.org/?probe=9f08673e43) | Feb 08, 2022 |
| Lenovo    | BRASWELL NOK                | [0b12f54345](https://linux-hardware.org/?probe=0b12f54345) | Dec 26, 2021 |
| HP        | 3047h                       | [71b6f0abea](https://linux-hardware.org/?probe=71b6f0abea) | Dec 25, 2021 |
| Dell      | Precision WorkStation 49... | [b40b65db05](https://linux-hardware.org/?probe=b40b65db05) | Nov 07, 2021 |
| Dell      | 0CRH6C A01                  | [ff796824d2](https://linux-hardware.org/?probe=ff796824d2) | Oct 30, 2021 |
| HP        | 1850                        | [b155e888a5](https://linux-hardware.org/?probe=b155e888a5) | Oct 24, 2021 |
| Gigabyte  | G41MT-S2P                   | [e66a1ae149](https://linux-hardware.org/?probe=e66a1ae149) | Oct 21, 2021 |
| Gigabyte  | G41MT-S2P                   | [7339dc6e79](https://linux-hardware.org/?probe=7339dc6e79) | Oct 21, 2021 |
| ASUSTek   | B250 MINING EXPERT          | [8c1989ae75](https://linux-hardware.org/?probe=8c1989ae75) | Oct 16, 2021 |
| ASUSTek   | B250 MINING EXPERT          | [6c2357c3a8](https://linux-hardware.org/?probe=6c2357c3a8) | Oct 16, 2021 |
| Alienware | 0P0JWX A00                  | [bc2b8a4fa5](https://linux-hardware.org/?probe=bc2b8a4fa5) | Oct 11, 2021 |
| Alienware | 0P0JWX A00                  | [879496302d](https://linux-hardware.org/?probe=879496302d) | Oct 11, 2021 |
| Alienware | 0P0JWX A00                  | [bbe7dc3f56](https://linux-hardware.org/?probe=bbe7dc3f56) | Oct 11, 2021 |
| Gigabyte  | H510M S2H                   | [77205a87c4](https://linux-hardware.org/?probe=77205a87c4) | Oct 09, 2021 |
| ASUSTek   | TUF B450M-PLUS GAMING       | [6df5eb55f0](https://linux-hardware.org/?probe=6df5eb55f0) | Oct 03, 2021 |
| HP        | 1632                        | [269b4ad58e](https://linux-hardware.org/?probe=269b4ad58e) | Aug 22, 2021 |
| MSI       | MAG X570 TOMAHAWK WIFI      | [3eb5c512ad](https://linux-hardware.org/?probe=3eb5c512ad) | Aug 19, 2021 |
| Gigabyte  | G31M-ES2L                   | [26cae4bb7a](https://linux-hardware.org/?probe=26cae4bb7a) | Aug 16, 2021 |
| Intel     | DG31PR AAD97573-205         | [9bda168dc6](https://linux-hardware.org/?probe=9bda168dc6) | Aug 04, 2021 |
| Dell      | 0DR845                      | [1714388038](https://linux-hardware.org/?probe=1714388038) | Aug 03, 2021 |
| HP        | 3047h                       | [58b480757e](https://linux-hardware.org/?probe=58b480757e) | Jul 18, 2021 |
| HP        | 3047h                       | [40a25f223c](https://linux-hardware.org/?probe=40a25f223c) | Jul 18, 2021 |
| HP        | 0AE8h C                     | [b8b861a13d](https://linux-hardware.org/?probe=b8b861a13d) | Jul 13, 2021 |
| MSI       | MS-7507                     | [ede4b6fc34](https://linux-hardware.org/?probe=ede4b6fc34) | Jul 11, 2021 |
| HP        | 0A54h                       | [c8d8757784](https://linux-hardware.org/?probe=c8d8757784) | Jul 02, 2021 |
| Lenovo    | 0B98401 WIN                 | [c432c046f1](https://linux-hardware.org/?probe=c432c046f1) | Jun 04, 2021 |
| HP        | 158B                        | [cc2472f216](https://linux-hardware.org/?probe=cc2472f216) | Jun 03, 2021 |
| HP        | 83E1                        | [a10433a3cb](https://linux-hardware.org/?probe=a10433a3cb) | Jun 03, 2021 |
| Dell      | 09KPNV A01                  | [ace51e66cb](https://linux-hardware.org/?probe=ace51e66cb) | May 31, 2021 |
| HP        | 2129                        | [3991895525](https://linux-hardware.org/?probe=3991895525) | May 23, 2021 |
| Dell      | 09KPNV A01                  | [b902c359da](https://linux-hardware.org/?probe=b902c359da) | Apr 30, 2021 |
| Gigabyte  | H55M-S2V                    | [9170ec8194](https://linux-hardware.org/?probe=9170ec8194) | Apr 20, 2021 |
| HP        | 3397                        | [bb31fb43b4](https://linux-hardware.org/?probe=bb31fb43b4) | Apr 17, 2021 |
| Dell      | 09KPNV A01                  | [b7fe68e060](https://linux-hardware.org/?probe=b7fe68e060) | Apr 17, 2021 |
| HP        | 3397                        | [aa5cc70dda](https://linux-hardware.org/?probe=aa5cc70dda) | Apr 12, 2021 |
| Dell      | 0F5C5X A00                  | [7eda600c97](https://linux-hardware.org/?probe=7eda600c97) | Apr 05, 2021 |
| Dell      | 09KPNV A01                  | [10aaa9110b](https://linux-hardware.org/?probe=10aaa9110b) | Mar 23, 2021 |
| Gigabyte  | H61M-S2P                    | [280d47279c](https://linux-hardware.org/?probe=280d47279c) | Mar 23, 2021 |
| Gigabyte  | H61M-S2P                    | [a33947d95c](https://linux-hardware.org/?probe=a33947d95c) | Mar 23, 2021 |
| HP        | 2215                        | [baefda0ada](https://linux-hardware.org/?probe=baefda0ada) | Mar 22, 2021 |
| Dell      | 06D7TR A00                  | [d48c515893](https://linux-hardware.org/?probe=d48c515893) | Mar 20, 2021 |
| Gigabyte  | G41MT-S2P                   | [ca4e78877a](https://linux-hardware.org/?probe=ca4e78877a) | Mar 12, 2021 |
| Dell      | 09KPNV A01                  | [8f9a642417](https://linux-hardware.org/?probe=8f9a642417) | Feb 22, 2021 |
| HP        | 3397                        | [d20792e0ea](https://linux-hardware.org/?probe=d20792e0ea) | Feb 17, 2021 |
| Gigabyte  | H61M-S2P                    | [93bf0c5ca7](https://linux-hardware.org/?probe=93bf0c5ca7) | Feb 16, 2021 |
| Dell      | 09KPNV A01                  | [80ffaa3d5b](https://linux-hardware.org/?probe=80ffaa3d5b) | Feb 07, 2021 |
| Dell      | 09KPNV A01                  | [ed032a4225](https://linux-hardware.org/?probe=ed032a4225) | Feb 07, 2021 |
| Gigabyte  | G41MT-S2PT                  | [835511d4d7](https://linux-hardware.org/?probe=835511d4d7) | Jan 21, 2021 |
| HP        | 18E7                        | [627983aa9a](https://linux-hardware.org/?probe=627983aa9a) | Jan 08, 2021 |
| HP        | 18E7                        | [84402293e1](https://linux-hardware.org/?probe=84402293e1) | Jan 08, 2021 |
| Acer      | Veriton ES2735G V:2.0       | [c7f3ccb243](https://linux-hardware.org/?probe=c7f3ccb243) | Jan 03, 2021 |
| Gigabyte  | G41MT-S2PT                  | [91e7e7c14e](https://linux-hardware.org/?probe=91e7e7c14e) | Dec 27, 2020 |
| Gigabyte  | G41MT-S2PT                  | [3f73a22244](https://linux-hardware.org/?probe=3f73a22244) | Dec 27, 2020 |
| ASUSTek   | ROG STRIX X570-F GAMING     | [ed8e771bf5](https://linux-hardware.org/?probe=ed8e771bf5) | Dec 15, 2020 |
| Dell      | 0WWJRX A00                  | [79bddf0f48](https://linux-hardware.org/?probe=79bddf0f48) | Nov 17, 2020 |
| MSI       | B450 TOMAHAWK               | [59b28e7f27](https://linux-hardware.org/?probe=59b28e7f27) | Oct 29, 2020 |
| MSI       | B450 TOMAHAWK               | [812301310e](https://linux-hardware.org/?probe=812301310e) | Oct 29, 2020 |
| Gigabyte  | G41MT-S2PT                  | [183944533e](https://linux-hardware.org/?probe=183944533e) | Oct 19, 2020 |
| HP        | 304Ah                       | [a304d64545](https://linux-hardware.org/?probe=a304d64545) | Oct 14, 2020 |
| HP        | 304Ah                       | [539e24cc37](https://linux-hardware.org/?probe=539e24cc37) | Oct 13, 2020 |
| ASUSTek   | P6T                         | [3dd96c341e](https://linux-hardware.org/?probe=3dd96c341e) | Oct 08, 2020 |
| HP        | 304Ah                       | [720e05d59c](https://linux-hardware.org/?probe=720e05d59c) | Oct 04, 2020 |
| HP        | 304Ah                       | [e8bf5f6700](https://linux-hardware.org/?probe=e8bf5f6700) | Oct 04, 2020 |
| Gigabyte  | G41MT-S2PT                  | [cfddb029a9](https://linux-hardware.org/?probe=cfddb029a9) | Oct 01, 2020 |
| Gigabyte  | P61-DS3-B3                  | [3e2d37b04f](https://linux-hardware.org/?probe=3e2d37b04f) | Sep 30, 2020 |
| Gigabyte  | P61-DS3-B3                  | [a8eb27996e](https://linux-hardware.org/?probe=a8eb27996e) | Sep 30, 2020 |
| HP        | 304Ah                       | [11dc9e4238](https://linux-hardware.org/?probe=11dc9e4238) | Sep 28, 2020 |
| HP        | 2215                        | [4251c60f57](https://linux-hardware.org/?probe=4251c60f57) | Sep 28, 2020 |
| Dell      | 0C27VV A00                  | [63ac37dbe0](https://linux-hardware.org/?probe=63ac37dbe0) | Sep 09, 2020 |
| HP        | 1850                        | [b4067f01b9](https://linux-hardware.org/?probe=b4067f01b9) | Aug 28, 2020 |
| HP        | 0AA8h                       | [1d5b0d8069](https://linux-hardware.org/?probe=1d5b0d8069) | Aug 18, 2020 |
| Gigabyte  | G41MT-S2PT                  | [2c424580ec](https://linux-hardware.org/?probe=2c424580ec) | Aug 15, 2020 |
| Gigabyte  | G41MT-S2PT                  | [8b2bb78e5e](https://linux-hardware.org/?probe=8b2bb78e5e) | Aug 15, 2020 |
| Gigabyte  | H55M-S2V                    | [07f217e703](https://linux-hardware.org/?probe=07f217e703) | Aug 03, 2020 |
| Gigabyte  | H55M-S2V                    | [ed1664a437](https://linux-hardware.org/?probe=ed1664a437) | Aug 03, 2020 |
| Gigabyte  | Z97-D3H-CF                  | [fd308ae7e8](https://linux-hardware.org/?probe=fd308ae7e8) | Aug 03, 2020 |
| Lenovo    | ThinkCentre M55p 8811Y4U    | [0aea737b4e](https://linux-hardware.org/?probe=0aea737b4e) | Jul 14, 2020 |
| ECS       | G41T-M6                     | [c053fd66c4](https://linux-hardware.org/?probe=c053fd66c4) | Jun 20, 2020 |
| Gigabyte  | H61M-S2V-B3                 | [c0a0033c02](https://linux-hardware.org/?probe=c0a0033c02) | Jun 19, 2020 |
| Gigabyte  | GA-MA78LMT-S2               | [1785e9c758](https://linux-hardware.org/?probe=1785e9c758) | Jun 09, 2020 |
| HP        | 0AA8h                       | [7bc753da45](https://linux-hardware.org/?probe=7bc753da45) | Jun 01, 2020 |
| Gigabyte  | B450 AORUS PRO-CF           | [cad337153c](https://linux-hardware.org/?probe=cad337153c) | May 30, 2020 |
| HP        | 0A64h                       | [2bd2c492f2](https://linux-hardware.org/?probe=2bd2c492f2) | May 19, 2020 |
| Gigabyte  | GA-MA78LMT-S2               | [143dc371cc](https://linux-hardware.org/?probe=143dc371cc) | May 13, 2020 |
| Dell      | 0F5C5X A00                  | [7249cfd353](https://linux-hardware.org/?probe=7249cfd353) | May 11, 2020 |
| Dell      | 0M863N A01                  | [9d837a84d6](https://linux-hardware.org/?probe=9d837a84d6) | May 06, 2020 |
| Gigabyte  | GA-MA78LMT-S2               | [3cc9bc0ca6](https://linux-hardware.org/?probe=3cc9bc0ca6) | May 02, 2020 |
| Gigabyte  | GA-MA78LMT-S2               | [ca61693f79](https://linux-hardware.org/?probe=ca61693f79) | May 02, 2020 |
| ASUSTek   | TUF Z390M-PRO GAMING        | [aa0e93d8ea](https://linux-hardware.org/?probe=aa0e93d8ea) | May 01, 2020 |
| ASUSTek   | TUF Z390M-PRO GAMING        | [ec80a4e6c4](https://linux-hardware.org/?probe=ec80a4e6c4) | May 01, 2020 |
| HP        | 0A64h                       | [33c495a402](https://linux-hardware.org/?probe=33c495a402) | Apr 29, 2020 |
| HP        | 0A64h                       | [fa43db5ed0](https://linux-hardware.org/?probe=fa43db5ed0) | Apr 29, 2020 |
| HP        | 3029h                       | [79951d69d3](https://linux-hardware.org/?probe=79951d69d3) | Apr 03, 2020 |
| HP        | 0B54h D                     | [90835f49e4](https://linux-hardware.org/?probe=90835f49e4) | Apr 01, 2020 |
| HP        | 0B54h D                     | [ccfbb22390](https://linux-hardware.org/?probe=ccfbb22390) | Apr 01, 2020 |
| HP        | 304Ah                       | [6b3da5e7b3](https://linux-hardware.org/?probe=6b3da5e7b3) | Mar 02, 2020 |
| ASUSTek   | P8B75-M                     | [56ae5142e3](https://linux-hardware.org/?probe=56ae5142e3) | Feb 24, 2020 |
| Gigabyte  | G41MT-S2PT                  | [d9e2a26971](https://linux-hardware.org/?probe=d9e2a26971) | Feb 11, 2020 |
| Gigabyte  | G41MT-S2PT                  | [3b89d35524](https://linux-hardware.org/?probe=3b89d35524) | Feb 11, 2020 |
| Lenovo    | ThinkCentre M55p 8811Y4U    | [ad3e13542c](https://linux-hardware.org/?probe=ad3e13542c) | Jan 15, 2020 |
| Lenovo    | ThinkCentre M55p 8811Y4U    | [9658459b91](https://linux-hardware.org/?probe=9658459b91) | Jan 14, 2020 |
| IBM       | 81713FG                     | [53dead81c6](https://linux-hardware.org/?probe=53dead81c6) | Jan 03, 2020 |
| IBM       | 81713FG                     | [d8e454de5c](https://linux-hardware.org/?probe=d8e454de5c) | Jan 03, 2020 |
| ASUSTek   | H61M-K                      | [60762839f9](https://linux-hardware.org/?probe=60762839f9) | Nov 28, 2019 |
| ASUSTek   | H61M-K                      | [7ab32a09a5](https://linux-hardware.org/?probe=7ab32a09a5) | Nov 20, 2019 |
| Dell      | 0G214D A00                  | [9ed0af6e0a](https://linux-hardware.org/?probe=9ed0af6e0a) | Oct 11, 2019 |
| Gigabyte  | H61M-S2PT                   | [63cd905908](https://linux-hardware.org/?probe=63cd905908) | Oct 10, 2019 |
| HP        | 2820h                       | [11ccf345fc](https://linux-hardware.org/?probe=11ccf345fc) | Oct 06, 2019 |
| Gigabyte  | 8I848P-G                    | [dc8d0265cd](https://linux-hardware.org/?probe=dc8d0265cd) | Sep 29, 2019 |
| Gigabyte  | 8I848P-G                    | [ab92c43036](https://linux-hardware.org/?probe=ab92c43036) | Sep 28, 2019 |
| Dell      | 0G214D A00                  | [e8c153f59c](https://linux-hardware.org/?probe=e8c153f59c) | Sep 09, 2019 |
| Dell      | 0G214D A00                  | [16230f6527](https://linux-hardware.org/?probe=16230f6527) | Aug 10, 2019 |
| HP        | 0AA8h                       | [590f9d42ea](https://linux-hardware.org/?probe=590f9d42ea) | Aug 09, 2019 |
| HP        | 0AA8h                       | [822e83d86b](https://linux-hardware.org/?probe=822e83d86b) | Aug 09, 2019 |
| Dell      | 0RW199                      | [dfb1809733](https://linux-hardware.org/?probe=dfb1809733) | Aug 05, 2019 |
| HP        | 0AA8h                       | [e4137ad45b](https://linux-hardware.org/?probe=e4137ad45b) | Jul 31, 2019 |
| HP        | 0AA8h                       | [22921b3801](https://linux-hardware.org/?probe=22921b3801) | Jul 31, 2019 |
| Gigabyte  | H61M-S2PT                   | [0beb4b51ba](https://linux-hardware.org/?probe=0beb4b51ba) | Jul 12, 2019 |
| Gigabyte  | H61M-S2PT                   | [8a7237435e](https://linux-hardware.org/?probe=8a7237435e) | Jun 28, 2019 |
| Gigabyte  | G41MT-S2PT                  | [ada1dd6ed6](https://linux-hardware.org/?probe=ada1dd6ed6) | May 25, 2019 |
| HP        | 339A                        | [5b75c30305](https://linux-hardware.org/?probe=5b75c30305) | May 07, 2019 |
| HP        | 339A                        | [8d28878fde](https://linux-hardware.org/?probe=8d28878fde) | Apr 24, 2019 |
| Acer      | RS880M05                    | [17c0c75b39](https://linux-hardware.org/?probe=17c0c75b39) | Apr 23, 2019 |
| HP        | 158A                        | [61be039d0f](https://linux-hardware.org/?probe=61be039d0f) | Apr 02, 2019 |
| Gigabyte  | Z97X-Gaming GT              | [7a92794877](https://linux-hardware.org/?probe=7a92794877) | Apr 01, 2019 |
| Gigabyte  | Z97X-Gaming GT              | [db8cfde0fc](https://linux-hardware.org/?probe=db8cfde0fc) | Feb 15, 2019 |
| Gigabyte  | Z97X-Gaming GT              | [2c4a8b9bfc](https://linux-hardware.org/?probe=2c4a8b9bfc) | Feb 14, 2019 |
| Gigabyte  | Z97X-Gaming GT              | [4bd60c5d00](https://linux-hardware.org/?probe=4bd60c5d00) | Feb 13, 2019 |
| Dell      | 0W0CHX A00                  | [84777ce1be](https://linux-hardware.org/?probe=84777ce1be) | Feb 05, 2019 |
| Gigabyte  | H61M-S2V-B3                 | [4ea628d244](https://linux-hardware.org/?probe=4ea628d244) | Nov 27, 2018 |
| MSI       | MS-7309                     | [dcfb685544](https://linux-hardware.org/?probe=dcfb685544) | Nov 16, 2018 |
| Gigabyte  | P31-DS3L                    | [5e5236f775](https://linux-hardware.org/?probe=5e5236f775) | May 31, 2018 |
| Gigabyte  | P31-DS3L                    | [cb1a0d9cdd](https://linux-hardware.org/?probe=cb1a0d9cdd) | Jan 30, 2018 |
| Gigabyte  | P31-DS3L                    | [a3bd2e39bb](https://linux-hardware.org/?probe=a3bd2e39bb) | Jan 05, 2018 |
| MSI       | MS-7309                     | [bfa74baa2d](https://linux-hardware.org/?probe=bfa74baa2d) | Oct 30, 2017 |
| Gigabyte  | GA-MA78G-DS3H               | [d033ac1daf](https://linux-hardware.org/?probe=d033ac1daf) | Jun 18, 2017 |
| Gigabyte  | GA-MA78G-DS3H               | [89a443e757](https://linux-hardware.org/?probe=89a443e757) | Jun 15, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Ubuntu 20.04         | 17       | 11.72%  |
| OpenMandriva 4.3     | 13       | 8.97%   |
| Ubuntu 18.04         | 10       | 6.9%    |
| Zorin 16             | 8        | 5.52%   |
| OpenMandriva 4.2     | 7        | 4.83%   |
| OpenMandriva 23.01   | 5        | 3.45%   |
| Ubuntu 22.04         | 4        | 2.76%   |
| Arch Rolling         | 4        | 2.76%   |
| ROSA R10             | 3        | 2.07%   |
| Linux Mint 20        | 3        | 2.07%   |
| BlackPanther 18.1    | 3        | 2.07%   |
| Ubuntu 19.04         | 2        | 1.38%   |
| ROSA R9              | 2        | 1.38%   |
| ROSA R11             | 2        | 1.38%   |
| Pop!_OS 21.04        | 2        | 1.38%   |
| Pop!_OS 20.10        | 2        | 1.38%   |
| OpenMandriva 4.90    | 2        | 1.38%   |
| Manjaro              | 2        | 1.38%   |
| Kali 2022.1          | 2        | 1.38%   |
| Fedora 35            | 2        | 1.38%   |
| Fedora 32            | 2        | 1.38%   |
| Fedora 30            | 2        | 1.38%   |
| Arch                 | 2        | 1.38%   |
| Zorin 15             | 1        | 0.69%   |
| Xubuntu 20.04        | 1        | 0.69%   |
| Xubuntu 18.04        | 1        | 0.69%   |
| Xubuntu 16.04        | 1        | 0.69%   |
| Ultramarine Linux 37 | 1        | 0.69%   |
| Ubuntu Unity 16.04   | 1        | 0.69%   |
| Ubuntu 22.10         | 1        | 0.69%   |
| Ubuntu 21.10         | 1        | 0.69%   |
| TUXEDO OS 22.04      | 1        | 0.69%   |
| ROSA R11.1           | 1        | 0.69%   |
| ROSA 12.2            | 1        | 0.69%   |
| RHEL 8               | 1        | 0.69%   |
| Reborn OS Rolling    | 1        | 0.69%   |
| Pop!_OS 20.04        | 1        | 0.69%   |
| Parrot 5.0           | 1        | 0.69%   |
| Manjaro 21.3.7       | 1        | 0.69%   |
| Manjaro 21.2.0       | 1        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu            | 35       | 25.36%  |
| OpenMandriva      | 26       | 18.84%  |
| Linux Mint        | 10       | 7.25%   |
| Zorin             | 9        | 6.52%   |
| ROSA              | 7        | 5.07%   |
| Fedora            | 7        | 5.07%   |
| Manjaro           | 6        | 4.35%   |
| Arch              | 6        | 4.35%   |
| Pop!_OS           | 5        | 3.62%   |
| Elementary        | 4        | 2.9%    |
| Xubuntu           | 3        | 2.17%   |
| Kali              | 3        | 2.17%   |
| Debian            | 3        | 2.17%   |
| BlackPanther      | 3        | 2.17%   |
| ArcoLinux         | 2        | 1.45%   |
| Ultramarine Linux | 1        | 0.72%   |
| Ubuntu Unity      | 1        | 0.72%   |
| TUXEDO OS         | 1        | 0.72%   |
| RHEL              | 1        | 0.72%   |
| Reborn OS         | 1        | 0.72%   |
| Parrot            | 1        | 0.72%   |
| LMDE              | 1        | 0.72%   |
| KDE neon          | 1        | 0.72%   |
| Endless           | 1        | 0.72%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003        | 11       | 7.1%    |
| 5.10.14-desktop-1omv4002       | 7        | 4.52%   |
| 6.1.1-desktop-1omv2290         | 5        | 3.23%   |
| 5.4.0-42-generic               | 4        | 2.58%   |
| 5.15.0-48-generic              | 3        | 1.94%   |
| 5.11.0-37-generic              | 3        | 1.94%   |
| 5.9.1-arch1-1                  | 2        | 1.29%   |
| 5.4.0-48-generic               | 2        | 1.29%   |
| 5.4.0-37-generic               | 2        | 1.29%   |
| 5.4.0-33-generic               | 2        | 1.29%   |
| 5.4.0-26-generic               | 2        | 1.29%   |
| 5.3.0-51-generic               | 2        | 1.29%   |
| 5.18.12-desktop-3omv4090       | 2        | 1.29%   |
| 5.16.13-desktop-1omv4003       | 2        | 1.29%   |
| 5.15.0-50-generic              | 2        | 1.29%   |
| 5.13.0-39-generic              | 2        | 1.29%   |
| 5.13.0-30-generic              | 2        | 1.29%   |
| 5.11.0-7620-generic            | 2        | 1.29%   |
| 4.18.16-desktop-1bP            | 2        | 1.29%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2        | 1.29%   |
| 4.15.0-55-generic              | 2        | 1.29%   |
| 4.15.0-46-generic              | 2        | 1.29%   |
| 6.1.7-200.fc37.x86_64          | 1        | 0.65%   |
| 6.1.5-273-tkg-pds              | 1        | 0.65%   |
| 6.0.11-arch1-1                 | 1        | 0.65%   |
| 5.9.0-kali5-amd64              | 1        | 0.65%   |
| 5.8.14-arch1-1                 | 1        | 0.65%   |
| 5.8.0-7642-generic             | 1        | 0.65%   |
| 5.8.0-7630-generic             | 1        | 0.65%   |
| 5.8.0-14-generic               | 1        | 0.65%   |
| 5.7.7-200.fc32.x86_64          | 1        | 0.65%   |
| 5.6.14-desktop-2bP             | 1        | 0.65%   |
| 5.6.10-300.fc32.x86_64         | 1        | 0.65%   |
| 5.5.13-1-MANJARO               | 1        | 0.65%   |
| 5.4.8-200.fc31.x86_64          | 1        | 0.65%   |
| 5.4.40-generic-1rosa-x86_64    | 1        | 0.65%   |
| 5.4.0-89-generic               | 1        | 0.65%   |
| 5.4.0-88-generic               | 1        | 0.65%   |
| 5.4.0-77-generic               | 1        | 0.65%   |
| 5.4.0-73-generic               | 1        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 22       | 15.07%  |
| 5.16.7  | 11       | 7.53%   |
| 5.15.0  | 10       | 6.85%   |
| 4.15.0  | 10       | 6.85%   |
| 5.13.0  | 8        | 5.48%   |
| 5.11.0  | 7        | 4.79%   |
| 5.10.14 | 7        | 4.79%   |
| 6.1.1   | 5        | 3.42%   |
| 5.3.0   | 5        | 3.42%   |
| 5.0.0   | 4        | 2.74%   |
| 5.8.0   | 3        | 2.05%   |
| 5.9.1   | 2        | 1.37%   |
| 5.19.0  | 2        | 1.37%   |
| 5.18.12 | 2        | 1.37%   |
| 5.16.13 | 2        | 1.37%   |
| 5.16.0  | 2        | 1.37%   |
| 5.10.0  | 2        | 1.37%   |
| 4.9.60  | 2        | 1.37%   |
| 4.19.0  | 2        | 1.37%   |
| 4.18.16 | 2        | 1.37%   |
| 4.18.0  | 2        | 1.37%   |
| 6.1.7   | 1        | 0.68%   |
| 6.1.5   | 1        | 0.68%   |
| 6.0.11  | 1        | 0.68%   |
| 5.9.0   | 1        | 0.68%   |
| 5.8.14  | 1        | 0.68%   |
| 5.7.7   | 1        | 0.68%   |
| 5.6.14  | 1        | 0.68%   |
| 5.6.10  | 1        | 0.68%   |
| 5.5.13  | 1        | 0.68%   |
| 5.4.8   | 1        | 0.68%   |
| 5.4.40  | 1        | 0.68%   |
| 5.3.3   | 1        | 0.68%   |
| 5.2.11  | 1        | 0.68%   |
| 5.19.12 | 1        | 0.68%   |
| 5.19.1  | 1        | 0.68%   |
| 5.17.9  | 1        | 0.68%   |
| 5.16.9  | 1        | 0.68%   |
| 5.16.18 | 1        | 0.68%   |
| 5.16.12 | 1        | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 24       | 16.67%  |
| 5.16    | 18       | 12.5%   |
| 5.10    | 13       | 9.03%   |
| 5.15    | 12       | 8.33%   |
| 4.15    | 10       | 6.94%   |
| 5.13    | 9        | 6.25%   |
| 5.11    | 8        | 5.56%   |
| 6.1     | 7        | 4.86%   |
| 5.3     | 6        | 4.17%   |
| 4.9     | 5        | 3.47%   |
| 5.8     | 4        | 2.78%   |
| 5.19    | 4        | 2.78%   |
| 5.0     | 4        | 2.78%   |
| 4.18    | 4        | 2.78%   |
| 5.9     | 3        | 2.08%   |
| 5.6     | 2        | 1.39%   |
| 5.18    | 2        | 1.39%   |
| 4.19    | 2        | 1.39%   |
| 6.0     | 1        | 0.69%   |
| 5.7     | 1        | 0.69%   |
| 5.5     | 1        | 0.69%   |
| 5.2     | 1        | 0.69%   |
| 5.17    | 1        | 0.69%   |
| 4.4     | 1        | 0.69%   |
| 4.13    | 1        | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 125      | 96.15%  |
| i686   | 5        | 3.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 53       | 39.55%  |
| KDE5            | 39       | 29.1%   |
| Unknown         | 13       | 9.7%    |
| X-Cinnamon      | 7        | 5.22%   |
| XFCE            | 6        | 4.48%   |
| KDE4            | 4        | 2.99%   |
| Pantheon        | 3        | 2.24%   |
| Cinnamon        | 2        | 1.49%   |
| Unity           | 1        | 0.75%   |
| MATE            | 1        | 0.75%   |
| LXDE            | 1        | 0.75%   |
| KDE             | 1        | 0.75%   |
| GNOME Flashback | 1        | 0.75%   |
| GNOME Classic   | 1        | 0.75%   |
| Budgie          | 1        | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 110      | 83.33%  |
| Wayland | 14       | 10.61%  |
| Unknown | 6        | 4.55%   |
| Tty     | 2        | 1.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 58       | 43.94%  |
| SDDM    | 33       | 25%     |
| GDM     | 14       | 10.61%  |
| GDM3    | 12       | 9.09%   |
| LightDM | 6        | 4.55%   |
| TDM     | 5        | 3.79%   |
| KDM     | 4        | 3.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 93       | 69.92%  |
| Unknown | 23       | 17.29%  |
| ar_EG   | 10       | 7.52%   |
| en_GB   | 5        | 3.76%   |
| C       | 2        | 1.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 95       | 73.64%  |
| EFI  | 34       | 26.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 95       | 69.34%  |
| Overlay | 25       | 18.25%  |
| Unknown | 6        | 4.38%   |
| Btrfs   | 5        | 3.65%   |
| Xfs     | 4        | 2.92%   |
| Zfs     | 2        | 1.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 62       | 46.97%  |
| MBR     | 36       | 27.27%  |
| GPT     | 34       | 25.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 77.44%  |
| Yes       | 30       | 22.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 50.75%  |
| Yes       | 66       | 49.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 42       | 32.56%  |
| Gigabyte Technology | 32       | 24.81%  |
| Dell                | 24       | 18.6%   |
| ASUSTek Computer    | 10       | 7.75%   |
| MSI                 | 5        | 3.88%   |
| Lenovo              | 5        | 3.88%   |
| Acer                | 3        | 2.33%   |
| Intel               | 2        | 1.55%   |
| Alienware           | 2        | 1.55%   |
| Pegatron            | 1        | 0.78%   |
| IBM                 | 1        | 0.78%   |
| ECS                 | 1        | 0.78%   |
| ASRock              | 1        | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte G41MT-S2PT                | 7        | 5.43%   |
| Dell OptiPlex 780                  | 4        | 3.1%    |
| HP Compaq Pro 6305 SFF             | 3        | 2.33%   |
| Gigabyte H61M-S2P                  | 3        | 2.33%   |
| Dell OptiPlex 760                  | 3        | 2.33%   |
| Dell OptiPlex 7020                 | 3        | 2.33%   |
| MSI MS-7C02                        | 2        | 1.55%   |
| HP Z600 Workstation                | 2        | 1.55%   |
| HP ProDesk 600 G1 TWR              | 2        | 1.55%   |
| HP ProDesk 600 G1 SFF              | 2        | 1.55%   |
| HP Compaq Elite 8300 SFF           | 2        | 1.55%   |
| HP Compaq dc7800                   | 2        | 1.55%   |
| HP Compaq 6005 Pro SFF PC          | 2        | 1.55%   |
| Gigabyte H61M-S2V-B3               | 2        | 1.55%   |
| Gigabyte G41MT-S2P                 | 2        | 1.55%   |
| ASUS B250 MINING EXPERT            | 2        | 1.55%   |
| Alienware Aurora R12               | 2        | 1.55%   |
| Pegatron Pro 3010 Microtower PC    | 1        | 0.78%   |
| MSI MS-7C84                        | 1        | 0.78%   |
| MSI MS-7507                        | 1        | 0.78%   |
| MSI MS-7309                        | 1        | 0.78%   |
| Lenovo ThinkStation S30 4351D32    | 1        | 0.78%   |
| Lenovo ThinkCentre M93p 10A8000WUS | 1        | 0.78%   |
| Lenovo ThinkCentre M600 10KGS0J000 | 1        | 0.78%   |
| Lenovo ThinkCentre M58 6258D3G     | 1        | 0.78%   |
| Lenovo ThinkCentre M55p 8811Y4U    | 1        | 0.78%   |
| Intel E4610                        | 1        | 0.78%   |
| Intel DG31PR AAD97573-205          | 1        | 0.78%   |
| IBM 81713FG                        | 1        | 0.78%   |
| HP Z840 Workstation                | 1        | 0.78%   |
| HP Z820 Workstation                | 1        | 0.78%   |
| HP Z620 Workstation                | 1        | 0.78%   |
| HP Z240 Tower Workstation          | 1        | 0.78%   |
| HP Z230 SFF Workstation            | 1        | 0.78%   |
| HP xw4600 Workstation              | 1        | 0.78%   |
| HP rp5800                          | 1        | 0.78%   |
| HP rp5700 Business System          | 1        | 0.78%   |
| HP EliteDesk 880 G1 TWR            | 1        | 0.78%   |
| HP EliteDesk 800 G4 SFF            | 1        | 0.78%   |
| HP EliteDesk 800 G2 TWR            | 1        | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Compaq            | 19       | 14.73%  |
| Dell OptiPlex        | 19       | 14.73%  |
| Gigabyte G41MT-S2PT  | 7        | 5.43%   |
| HP EliteDesk         | 6        | 4.65%   |
| Dell Precision       | 5        | 3.88%   |
| Lenovo ThinkCentre   | 4        | 3.1%    |
| HP ProDesk           | 4        | 3.1%    |
| Gigabyte H61M-S2P    | 3        | 2.33%   |
| ASUS TUF             | 3        | 2.33%   |
| MSI MS-7C02          | 2        | 1.55%   |
| HP Z600              | 2        | 1.55%   |
| Gigabyte H61M-S2V-B3 | 2        | 1.55%   |
| Gigabyte G41MT-S2P   | 2        | 1.55%   |
| ASUS B250            | 2        | 1.55%   |
| Alienware Aurora     | 2        | 1.55%   |
| Acer Veriton         | 2        | 1.55%   |
| Pegatron Pro         | 1        | 0.78%   |
| MSI MS-7C84          | 1        | 0.78%   |
| MSI MS-7507          | 1        | 0.78%   |
| MSI MS-7309          | 1        | 0.78%   |
| Lenovo ThinkStation  | 1        | 0.78%   |
| Intel E4610          | 1        | 0.78%   |
| Intel DG31PR         | 1        | 0.78%   |
| IBM 81713FG          | 1        | 0.78%   |
| HP Z840              | 1        | 0.78%   |
| HP Z820              | 1        | 0.78%   |
| HP Z620              | 1        | 0.78%   |
| HP Z240              | 1        | 0.78%   |
| HP Z230              | 1        | 0.78%   |
| HP xw4600            | 1        | 0.78%   |
| HP rp5800            | 1        | 0.78%   |
| HP rp5700            | 1        | 0.78%   |
| HP 290               | 1        | 0.78%   |
| HP 280               | 1        | 0.78%   |
| HP 1850              | 1        | 0.78%   |
| Gigabyte Z97X-Gaming | 1        | 0.78%   |
| Gigabyte Z97-D3H     | 1        | 0.78%   |
| Gigabyte Z87-HD3     | 1        | 0.78%   |
| Gigabyte P61-DS3-B3  | 1        | 0.78%   |
| Gigabyte P31-DS3L    | 1        | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 16       | 12.4%   |
| 2012 | 14       | 10.85%  |
| 2009 | 14       | 10.85%  |
| 2013 | 12       | 9.3%    |
| 2008 | 12       | 9.3%    |
| 2014 | 8        | 6.2%    |
| 2010 | 8        | 6.2%    |
| 2007 | 8        | 6.2%    |
| 2018 | 7        | 5.43%   |
| 2017 | 5        | 3.88%   |
| 2021 | 4        | 3.1%    |
| 2019 | 4        | 3.1%    |
| 2016 | 4        | 3.1%    |
| 2015 | 4        | 3.1%    |
| 2020 | 3        | 2.33%   |
| 2006 | 3        | 2.33%   |
| 2005 | 3        | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 129      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 128      | 99.22%  |
| Enabled  | 1        | 0.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 129      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 37       | 28.46%  |
| 4.01-8.0    | 27       | 20.77%  |
| 8.01-16.0   | 25       | 19.23%  |
| 16.01-24.0  | 19       | 14.62%  |
| 2.01-3.0    | 6        | 4.62%   |
| 32.01-64.0  | 5        | 3.85%   |
| 1.01-2.0    | 5        | 3.85%   |
| 24.01-32.0  | 2        | 1.54%   |
| 64.01-256.0 | 2        | 1.54%   |
| 0.51-1.0    | 1        | 0.77%   |
| 0.01-0.5    | 1        | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 53       | 37.06%  |
| 2.01-3.0    | 41       | 28.67%  |
| 3.01-4.0    | 12       | 8.39%   |
| 0.51-1.0    | 12       | 8.39%   |
| 4.01-8.0    | 10       | 6.99%   |
| 0.01-0.5    | 8        | 5.59%   |
| 8.01-16.0   | 6        | 4.2%    |
| 64.01-256.0 | 1        | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 66       | 48.89%  |
| 2       | 45       | 33.33%  |
| 3       | 15       | 11.11%  |
| 4       | 4        | 2.96%   |
| 9       | 2        | 1.48%   |
| 5       | 1        | 0.74%   |
| 0       | 1        | 0.74%   |
| Unknown | 1        | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 67       | 51.54%  |
| No        | 63       | 48.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 128      | 99.22%  |
| No        | 1        | 0.78%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 63.64%  |
| Yes       | 48       | 36.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 115      | 88.46%  |
| Yes       | 15       | 11.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Egypt   | 129      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Cairo               | 77       | 55.8%   |
| Giza                | 9        | 6.52%   |
| Alexandria          | 9        | 6.52%   |
| Al Mansurah         | 7        | 5.07%   |
| Tanta               | 4        | 2.9%    |
| Port Said           | 3        | 2.17%   |
| Zagazig             | 2        | 1.45%   |
| Suez                | 2        | 1.45%   |
| Mohandessin         | 2        | 1.45%   |
| Minya               | 2        | 1.45%   |
| Aswan               | 2        | 1.45%   |
| Assiut              | 2        | 1.45%   |
| Al Ma`adi           | 2        | 1.45%   |
| Zefta               | 1        | 0.72%   |
| Sharqia             | 1        | 0.72%   |
| Sharm el Sheikh     | 1        | 0.72%   |
| New Cairo           | 1        | 0.72%   |
| Mallawi             | 1        | 0.72%   |
| Luxor               | 1        | 0.72%   |
| Kafr ash Shaykh     | 1        | 0.72%   |
| Ismailia            | 1        | 0.72%   |
| Hurghada            | 1        | 0.72%   |
| Helwan              | 1        | 0.72%   |
| Faiyum              | 1        | 0.72%   |
| Bilbeis             | 1        | 0.72%   |
| Al Qalyubiyah       | 1        | 0.72%   |
| Akhmim              | 1        | 0.72%   |
| 6th of October City | 1        | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 75       | 117    | 38.46%  |
| Seagate                     | 47       | 66     | 24.1%   |
| Samsung Electronics         | 20       | 28     | 10.26%  |
| Kingston                    | 12       | 22     | 6.15%   |
| Toshiba                     | 10       | 11     | 5.13%   |
| Crucial                     | 6        | 9      | 3.08%   |
| Hitachi                     | 4        | 4      | 2.05%   |
| SanDisk                     | 2        | 2      | 1.03%   |
| LITEONIT                    | 2        | 2      | 1.03%   |
| KingSpec                    | 2        | 2      | 1.03%   |
| HS-SSD-E100                 | 2        | 2      | 1.03%   |
| Hewlett-Packard             | 2        | 2      | 1.03%   |
| ZOTAC                       | 1        | 1      | 0.51%   |
| TwinMOS                     | 1        | 1      | 0.51%   |
| Transcend                   | 1        | 1      | 0.51%   |
| Maxtor                      | 1        | 2      | 0.51%   |
| Lite-On Technology          | 1        | 1      | 0.51%   |
| Kingston Technology Company | 1        | 1      | 0.51%   |
| JMicron Technology          | 1        | 1      | 0.51%   |
| Intel                       | 1        | 1      | 0.51%   |
| HS-SSD-C100                 | 1        | 1      | 0.51%   |
| Hikvision                   | 1        | 1      | 0.51%   |
| Fujitsu                     | 1        | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 7        | 3.18%   |
| Seagate ST3500414CS 500GB        | 7        | 3.18%   |
| Toshiba DT01ACA050 500GB         | 5        | 2.27%   |
| Seagate ST3500312CS 500GB        | 5        | 2.27%   |
| Seagate ST3500413AS 500GB        | 4        | 1.82%   |
| Kingston SA400S37480G 480GB SSD  | 4        | 1.82%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 3        | 1.36%   |
| WDC WD5000AAKX-001CA0 500GB      | 3        | 1.36%   |
| WDC WD5000AADS-00S9B0 500GB      | 3        | 1.36%   |
| WDC WD3200AAJS-00L7A0 320GB      | 3        | 1.36%   |
| WDC WD2500AAKX-75U6AA0 250GB     | 3        | 1.36%   |
| WDC WD1600AABS-00PRA0 160GB      | 3        | 1.36%   |
| WDC WD1600AABS-00H4A0 160GB      | 3        | 1.36%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 1.36%   |
| WDC WD10EZEX-00BN5A0 1TB         | 3        | 1.36%   |
| WDC WD10EARS-00Y5B1 1TB          | 3        | 1.36%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.36%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 1.36%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2        | 0.91%   |
| WDC WD800BD-22MRA1 80GB          | 2        | 0.91%   |
| WDC WD5000AVVS-63H0B1 500GB      | 2        | 0.91%   |
| WDC WD5000AVDS-63U7B1 500GB      | 2        | 0.91%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 2        | 0.91%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 2        | 0.91%   |
| WDC WD10EZEX-22MFCA0 1TB         | 2        | 0.91%   |
| Seagate ST380815AS 80GB          | 2        | 0.91%   |
| Seagate ST3320311CS 320GB        | 2        | 0.91%   |
| Seagate ST3250318AS 250GB        | 2        | 0.91%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 0.91%   |
| Seagate ST1000VM002-1CT162 1TB   | 2        | 0.91%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.91%   |
| Samsung PM9A1 NVMe 256GB         | 2        | 0.91%   |
| Kingston SUV400S37240G 240GB SSD | 2        | 0.91%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 0.91%   |
| Crucial CT240BX500SSD1 240GB     | 2        | 0.91%   |
| ZOTAC ZTSSD-A4P-120G             | 1        | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.45%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.45%   |
| WDC WD800JD-60LSA5 80GB          | 1        | 0.45%   |
| WDC WD6400AADS-00M2B0 640GB      | 1        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 72       | 113    | 50.7%   |
| Seagate             | 47       | 66     | 33.1%   |
| Toshiba             | 9        | 10     | 6.34%   |
| Samsung Electronics | 7        | 10     | 4.93%   |
| Hitachi             | 4        | 4      | 2.82%   |
| Maxtor              | 1        | 2      | 0.7%    |
| Hewlett-Packard     | 1        | 1      | 0.7%    |
| Fujitsu             | 1        | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 12       | 21     | 27.91%  |
| Samsung Electronics | 8        | 8      | 18.6%   |
| Crucial             | 6        | 9      | 13.95%  |
| WDC                 | 4        | 4      | 9.3%    |
| LITEONIT            | 2        | 2      | 4.65%   |
| KingSpec            | 2        | 2      | 4.65%   |
| ZOTAC               | 1        | 1      | 2.33%   |
| TwinMOS             | 1        | 1      | 2.33%   |
| Transcend           | 1        | 1      | 2.33%   |
| Toshiba             | 1        | 1      | 2.33%   |
| SanDisk             | 1        | 1      | 2.33%   |
| JMicron Technology  | 1        | 1      | 2.33%   |
| Intel               | 1        | 1      | 2.33%   |
| Hikvision           | 1        | 1      | 2.33%   |
| Hewlett-Packard     | 1        | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 119      | 207    | 70.83%  |
| SSD     | 36       | 55     | 21.43%  |
| NVMe    | 10       | 14     | 5.95%   |
| Unknown | 3        | 3      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 125      | 264    | 91.91%  |
| NVMe | 10       | 14     | 7.35%   |
| SAS  | 1        | 1      | 0.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 109      | 200    | 71.71%  |
| 0.51-1.0   | 32       | 41     | 21.05%  |
| 1.01-2.0   | 8        | 11     | 5.26%   |
| 3.01-4.0   | 2        | 4      | 1.32%   |
| 4.01-10.0  | 1        | 6      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 30       | 21.13%  |
| 101-250        | 28       | 19.72%  |
| 1-20           | 19       | 13.38%  |
| 51-100         | 19       | 13.38%  |
| 501-1000       | 17       | 11.97%  |
| 21-50          | 13       | 9.15%   |
| 1001-2000      | 6        | 4.23%   |
| Unknown        | 4        | 2.82%   |
| More than 3000 | 3        | 2.11%   |
| 2001-3000      | 3        | 2.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 62       | 44.29%  |
| 101-250        | 23       | 16.43%  |
| 21-50          | 16       | 11.43%  |
| 251-500        | 13       | 9.29%   |
| 51-100         | 10       | 7.14%   |
| 501-1000       | 8        | 5.71%   |
| Unknown        | 4        | 2.86%   |
| More than 3000 | 2        | 1.43%   |
| 2001-3000      | 1        | 0.71%   |
| 1001-2000      | 1        | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63H0B1 500GB           | 2        | 2      | 4.55%   |
| WDC WD5000AVDS-63U7B1 500GB           | 2        | 2      | 4.55%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 3      | 4.55%   |
| WDC WD1600AABS-00H4A0 160GB           | 2        | 2      | 4.55%   |
| Seagate ST380815AS 80GB               | 2        | 2      | 4.55%   |
| Seagate ST3500413AS 500GB             | 2        | 2      | 4.55%   |
| WDC WD800JD-60LSA5 80GB               | 1        | 1      | 2.27%   |
| WDC WD800BD-22MRA1 80GB               | 1        | 1      | 2.27%   |
| WDC WD5000AAVS-22G9B1 500GB           | 1        | 1      | 2.27%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 1        | 2      | 2.27%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1        | 2      | 2.27%   |
| WDC WD5000AAKX-009FA0 500GB           | 1        | 1      | 2.27%   |
| WDC WD5000AAKS-00V6A0 500GB           | 1        | 1      | 2.27%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 1      | 2.27%   |
| WDC WD5000AADS-00M2B0 500GB           | 1        | 1      | 2.27%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1        | 1      | 2.27%   |
| WDC WD3200AAJS-56B4A0 320GB           | 1        | 1      | 2.27%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1        | 1      | 2.27%   |
| WDC WD3200AAJS-00B4A0 320GB           | 1        | 1      | 2.27%   |
| WDC WD3200A 320GB                     | 1        | 1      | 2.27%   |
| WDC WD2500AAJS-00VTA0 250GB           | 1        | 1      | 2.27%   |
| WDC WD1600AVVS-63L2B0 160GB           | 1        | 1      | 2.27%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1        | 1      | 2.27%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 2.27%   |
| WDC WD10EARS-00Y5B1 1TB               | 1        | 1      | 2.27%   |
| Toshiba MQ01ABF050 500GB              | 1        | 2      | 2.27%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 3      | 2.27%   |
| Seagate ST3500312CS 500GB             | 1        | 1      | 2.27%   |
| Seagate ST3320613AS 320GB             | 1        | 1      | 2.27%   |
| Seagate ST3160211AS 160GB             | 1        | 2      | 2.27%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 2.27%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 2.27%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 2.27%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 2.27%   |
| Samsung Electronics HD256GJ 250GB     | 1        | 1      | 2.27%   |
| Kingston SUV400S37240G 240GB SSD      | 1        | 2      | 2.27%   |
| Intel SSDSC2BW120H6 120GB             | 1        | 1      | 2.27%   |
| Hewlett-Packard VB0250EAVER 250GB     | 1        | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 30     | 60.53%  |
| Seagate             | 9        | 14     | 23.68%  |
| Samsung Electronics | 2        | 2      | 5.26%   |
| Toshiba             | 1        | 2      | 2.63%   |
| Kingston            | 1        | 2      | 2.63%   |
| Intel               | 1        | 1      | 2.63%   |
| Hewlett-Packard     | 1        | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 30     | 65.71%  |
| Seagate             | 9        | 14     | 25.71%  |
| Toshiba             | 1        | 2      | 2.86%   |
| Samsung Electronics | 1        | 1      | 2.86%   |
| Hewlett-Packard     | 1        | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 48     | 91.67%  |
| SSD  | 3        | 4      | 8.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD3200AAJS-00L7A0 320GB                      | 1        | 2      | 33.33%  |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 33.33%  |
| Samsung Electronics MZ7PC128HAFU-000H1 128GB SSD | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 66.67%  |
| WDC                 | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 68       | 129    | 45.03%  |
| Works    | 44       | 94     | 29.14%  |
| Malfunc  | 36       | 52     | 23.84%  |
| Failed   | 3        | 4      | 1.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 101      | 70.14%  |
| AMD                         | 26       | 18.06%  |
| Samsung Electronics         | 6        | 4.17%   |
| Marvell Technology Group    | 2        | 1.39%   |
| Kingston Technology Company | 2        | 1.39%   |
| Broadcom / LSI              | 2        | 1.39%   |
| SanDisk                     | 1        | 0.69%   |
| Nvidia                      | 1        | 0.69%   |
| LSI Logic / Symbios Logic   | 1        | 0.69%   |
| Lite-On Technology          | 1        | 0.69%   |
| JMicron Technology          | 1        | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 17       | 8.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 6.06%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 6.06%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 4.04%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 3.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.53%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.53%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 2.02%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 4        | 2.02%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 4        | 2.02%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 2.02%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 2.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 2.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 1.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.52%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 1.52%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 1.52%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 1.52%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.52%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 1.01%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.01%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 1.01%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 2        | 1.01%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2        | 1.01%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.01%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 74       | 47.74%  |
| IDE  | 55       | 35.48%  |
| RAID | 11       | 7.1%    |
| NVMe | 10       | 6.45%   |
| SAS  | 4        | 2.58%   |
| SCSI | 1        | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 102      | 79.07%  |
| AMD    | 27       | 20.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 6        | 4.62%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 3.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 3.08%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 3.08%   |
| Intel Pentium D CPU 3.00GHz                 | 3        | 2.31%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.31%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 3        | 2.31%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 2.31%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 2.31%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz     | 3        | 2.31%   |
| AMD A4-5300B APU with Radeon HD Graphics    | 3        | 2.31%   |
| Intel Pentium 4 CPU 3.20GHz                 | 2        | 1.54%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 1.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.54%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.54%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.54%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.54%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 2        | 1.54%   |
| Intel Core 2 Duo CPU E4400 @ 2.00GHz        | 2        | 1.54%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 2        | 1.54%   |
| Intel Celeron D CPU 3.06GHz                 | 2        | 1.54%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.54%   |
| AMD Phenom II X4 B95 Processor              | 2        | 1.54%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.77%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1        | 0.77%   |
| Intel Xeon CPU E5640 @ 2.67GHz              | 1        | 0.77%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.77%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.77%   |
| Intel Xeon CPU E5-2690 v2 @ 3.00GHz         | 1        | 0.77%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz         | 1        | 0.77%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz          | 1        | 0.77%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1        | 0.77%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 0.77%   |
| Intel Xeon CPU 3.20GHz                      | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.77%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.77%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.77%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.77%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 22       | 16.92%  |
| Intel Core 2 Duo        | 21       | 16.15%  |
| Intel Core i7           | 13       | 10%     |
| Intel Xeon              | 11       | 8.46%   |
| Intel Core i3           | 10       | 7.69%   |
| AMD Ryzen 5             | 6        | 4.62%   |
| Other                   | 4        | 3.08%   |
| Intel Core 2 Quad       | 4        | 3.08%   |
| Intel Core 2            | 4        | 3.08%   |
| AMD A4                  | 4        | 3.08%   |
| Intel Pentium D         | 3        | 2.31%   |
| Intel Pentium 4         | 3        | 2.31%   |
| Intel Pentium Dual-Core | 2        | 1.54%   |
| Intel Pentium           | 2        | 1.54%   |
| Intel Celeron D         | 2        | 1.54%   |
| Intel Celeron           | 2        | 1.54%   |
| AMD Phenom II X4        | 2        | 1.54%   |
| AMD Phenom              | 2        | 1.54%   |
| AMD A8                  | 2        | 1.54%   |
| AMD Sempron             | 1        | 0.77%   |
| AMD Ryzen 9             | 1        | 0.77%   |
| AMD Ryzen 7             | 1        | 0.77%   |
| AMD PRO A10             | 1        | 0.77%   |
| AMD FX                  | 1        | 0.77%   |
| AMD Athlon II X3        | 1        | 0.77%   |
| AMD Athlon II X2        | 1        | 0.77%   |
| AMD Athlon 64 X2        | 1        | 0.77%   |
| AMD Athlon 64           | 1        | 0.77%   |
| AMD A6                  | 1        | 0.77%   |
| AMD A10                 | 1        | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 50       | 38.46%  |
| 4      | 42       | 32.31%  |
| 1      | 13       | 10%     |
| 6      | 9        | 6.92%   |
| 8      | 8        | 6.15%   |
| 3      | 3        | 2.31%   |
| 16     | 2        | 1.54%   |
| 24     | 1        | 0.77%   |
| 12     | 1        | 0.77%   |
| 10     | 1        | 0.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 122      | 94.57%  |
| 2      | 7        | 5.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 58.02%  |
| 2      | 55       | 41.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 127      | 97.69%  |
| 32-bit         | 2        | 1.54%   |
| Unknown        | 1        | 0.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 21.64%  |
| 0x1067a    | 15       | 11.19%  |
| 0x306c3    | 14       | 10.45%  |
| 0x206a7    | 7        | 5.22%   |
| 0x306a9    | 6        | 4.48%   |
| 0x6fb      | 5        | 3.73%   |
| 0xf65      | 4        | 2.99%   |
| 0x06001119 | 4        | 2.99%   |
| 0xa0671    | 3        | 2.24%   |
| 0x906ea    | 3        | 2.24%   |
| 0x6fd      | 3        | 2.24%   |
| 0x506e3    | 3        | 2.24%   |
| 0x206c2    | 3        | 2.24%   |
| 0x0800820d | 3        | 2.24%   |
| 0xf41      | 2        | 1.49%   |
| 0x906e9    | 2        | 1.49%   |
| 0x6f6      | 2        | 1.49%   |
| 0x306e4    | 2        | 1.49%   |
| 0x106a5    | 2        | 1.49%   |
| 0x10676    | 2        | 1.49%   |
| 0x010000c8 | 2        | 1.49%   |
| 0x01000095 | 2        | 1.49%   |
| 0xf64      | 1        | 0.75%   |
| 0xf43      | 1        | 0.75%   |
| 0x906ed    | 1        | 0.75%   |
| 0x6f2      | 1        | 0.75%   |
| 0x406c4    | 1        | 0.75%   |
| 0x306f2    | 1        | 0.75%   |
| 0x206d7    | 1        | 0.75%   |
| 0x20655    | 1        | 0.75%   |
| 0x20652    | 1        | 0.75%   |
| 0x106e5    | 1        | 0.75%   |
| 0x0a201009 | 1        | 0.75%   |
| 0x08701021 | 1        | 0.75%   |
| 0x08701013 | 1        | 0.75%   |
| 0x0600063e | 1        | 0.75%   |
| 0x010000db | 1        | 0.75%   |
| 0x010000b6 | 1        | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 19       | 14.5%   |
| Haswell     | 18       | 13.74%  |
| Core        | 13       | 9.92%   |
| SandyBridge | 10       | 7.63%   |
| NetBurst    | 10       | 7.63%   |
| IvyBridge   | 9        | 6.87%   |
| KabyLake    | 8        | 6.11%   |
| K10         | 7        | 5.34%   |
| Piledriver  | 6        | 4.58%   |
| Westmere    | 5        | 3.82%   |
| Zen+        | 3        | 2.29%   |
| Zen 2       | 3        | 2.29%   |
| Skylake     | 3        | 2.29%   |
| Nehalem     | 3        | 2.29%   |
| Icelake     | 3        | 2.29%   |
| Zen 3       | 2        | 1.53%   |
| Steamroller | 2        | 1.53%   |
| K8 Hammer   | 2        | 1.53%   |
| Unknown     | 2        | 1.53%   |
| Silvermont  | 1        | 0.76%   |
| Excavator   | 1        | 0.76%   |
| Bulldozer   | 1        | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 65       | 46.76%  |
| Nvidia | 38       | 27.34%  |
| AMD    | 36       | 25.9%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 15       | 10.64%  |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 15       | 10.64%  |
| Nvidia GT218 [GeForce 210]                                                  | 8        | 5.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 4.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 3.55%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 5        | 3.55%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 2.84%   |
| Nvidia GF119 [NVS 315]                                                      | 3        | 2.13%   |
| Nvidia GF108GL [Quadro 600]                                                 | 3        | 2.13%   |
| Intel HD Graphics 630                                                       | 3        | 2.13%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 3        | 2.13%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2.13%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 2.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.13%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 3        | 2.13%   |
| AMD RS880 [Radeon HD 4200]                                                  | 3        | 2.13%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 2.13%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.42%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 2        | 1.42%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.42%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.42%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.71%   |
| Nvidia NV18 [GeForce4 MX 4000]                                              | 1        | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.71%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.71%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.71%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.71%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.71%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.71%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.71%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.71%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 0.71%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 0.71%   |
| Nvidia G92 [GeForce 9800 GTX / 9800 GTX+]                                   | 1        | 0.71%   |
| Nvidia G86 [Quadro NVS 290]                                                 | 1        | 0.71%   |
| Nvidia G84GL [Quadro FX 1700]                                               | 1        | 0.71%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 0.71%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 55       | 42.31%  |
| 1 x Nvidia     | 35       | 26.92%  |
| 1 x AMD        | 29       | 22.31%  |
| Intel + AMD    | 4        | 3.08%   |
| Intel + Nvidia | 3        | 2.31%   |
| 3 x AMD        | 1        | 0.77%   |
| 2 x Intel      | 1        | 0.77%   |
| 2 x AMD        | 1        | 0.77%   |
| AMD + Nvidia   | 1        | 0.77%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 103      | 77.44%  |
| Proprietary | 18       | 13.53%  |
| Unknown     | 12       | 9.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 71       | 52.99%  |
| 0.01-0.5   | 19       | 14.18%  |
| 0.51-1.0   | 16       | 11.94%  |
| 1.01-2.0   | 11       | 8.21%   |
| 7.01-8.0   | 9        | 6.72%   |
| 3.01-4.0   | 6        | 4.48%   |
| 8.01-16.0  | 2        | 1.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 27       | 25%     |
| Dell                    | 22       | 20.37%  |
| Hewlett-Packard         | 20       | 18.52%  |
| Lenovo                  | 6        | 5.56%   |
| Goldstar                | 6        | 5.56%   |
| NEC Computers           | 3        | 2.78%   |
| Philips                 | 2        | 1.85%   |
| Fujitsu Siemens         | 2        | 1.85%   |
| Eizo                    | 2        | 1.85%   |
| BenQ                    | 2        | 1.85%   |
| ASUSTek Computer        | 2        | 1.85%   |
| ViewSonic               | 1        | 0.93%   |
| Unknown                 | 1        | 0.93%   |
| Sun                     | 1        | 0.93%   |
| Sony                    | 1        | 0.93%   |
| Planar                  | 1        | 0.93%   |
| MStar                   | 1        | 0.93%   |
| JWY                     | 1        | 0.93%   |
| Gigabyte Technology     | 1        | 0.93%   |
| eMachines               | 1        | 0.93%   |
| Chi Mei Optoelectronics | 1        | 0.93%   |
| AUS                     | 1        | 0.93%   |
| AOC                     | 1        | 0.93%   |
| Ancor Communications    | 1        | 0.93%   |
| Acer                    | 1        | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                     | 5        | 4.42%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch     | 3        | 2.65%   |
| Lenovo LEN T2454pA LEN60C9 1920x1080 518x324mm 24.1-inch             | 3        | 2.65%   |
| Hewlett-Packard L1950 HWP26E7 1280x1024 380x300mm 19.1-inch          | 3        | 2.65%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 2        | 1.77%   |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch  | 2        | 1.77%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 2        | 1.77%   |
| Hewlett-Packard LA2206 HWP2948 1920x1080 476x268mm 21.5-inch         | 2        | 1.77%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch         | 2        | 1.77%   |
| Hewlett-Packard LA2006 HWP2943 1600x900 443x249mm 20.0-inch          | 2        | 1.77%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch        | 1        | 0.88%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                 | 1        | 0.88%   |
| Sun PN17JO SUN0589 1280x1024 295x236mm 14.9-inch                     | 1        | 0.88%   |
| Sony KDL-23S2000 SNY9900 1360x768                                    | 1        | 0.88%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM0590 1600x900 443x249mm 20.0-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch | 1        | 0.88%   |
| Samsung Electronics SMBX2031 SAM076A 1600x900 443x249mm 20.0-inch    | 1        | 0.88%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch    | 1        | 0.88%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1        | 0.88%   |
| Samsung Electronics S23B300 SAM08AE 1920x1080 510x287mm 23.0-inch    | 1        | 0.88%   |
| Samsung Electronics S22E200 SAM0C6D 1920x1080 477x268mm 21.5-inch    | 1        | 0.88%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1        | 0.88%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 1        | 0.88%   |
| Samsung Electronics S19B300 SAM08A4 1366x768 410x230mm 18.5-inch     | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SMBX2350 1920x1080                   | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                   | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SA300/SA350 1366x768                 | 1        | 0.88%   |
| Samsung Electronics LCD Monitor S24D330 1920x1080                    | 1        | 0.88%   |
| Samsung Electronics LCD Monitor S22D300 1920x1080                    | 1        | 0.88%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch   | 1        | 0.88%   |
| Samsung Electronics C24FG7x SAM0E43 1920x1080 532x304mm 24.1-inch    | 1        | 0.88%   |
| Planar PE2010 PLN2010 1400x1050 400x300mm 19.7-inch                  | 1        | 0.88%   |
| Philips 190CW PHLC023 1440x900 408x255mm 18.9-inch                   | 1        | 0.88%   |
| Philips 170CW PHLC01D 1440x900 367x230mm 17.1-inch                   | 1        | 0.88%   |
| NEC Computers LCD2090UXi NEC66B0 1600x1200 408x306mm 20.1-inch       | 1        | 0.88%   |
| NEC Computers EA234WMi NEC6921 1920x1080 509x286mm 23.0-inch         | 1        | 0.88%   |
| NEC Computers EA223WM NEC688F 1680x1050 470x300mm 22.0-inch          | 1        | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 36       | 33.96%  |
| 1280x1024 (SXGA)   | 22       | 20.75%  |
| 1366x768 (WXGA)    | 10       | 9.43%   |
| 1440x900 (WXGA+)   | 9        | 8.49%   |
| 1680x1050 (WSXGA+) | 7        | 6.6%    |
| 1600x900 (HD+)     | 7        | 6.6%    |
| 3840x2160 (4K)     | 3        | 2.83%   |
| 2560x1440 (QHD)    | 2        | 1.89%   |
| 1600x1200          | 2        | 1.89%   |
| 3440x1440          | 1        | 0.94%   |
| 2560x1600          | 1        | 0.94%   |
| 1920x540           | 1        | 0.94%   |
| 1920x1200 (WUXGA)  | 1        | 0.94%   |
| 1400x1050          | 1        | 0.94%   |
| 1360x768           | 1        | 0.94%   |
| 1280x720 (HD)      | 1        | 0.94%   |
| 1024x768 (XGA)     | 1        | 0.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 16       | 14.81%  |
| 19      | 13       | 12.04%  |
| 24      | 10       | 9.26%   |
| 18      | 10       | 9.26%   |
| 21      | 9        | 8.33%   |
| 20      | 9        | 8.33%   |
| Unknown | 9        | 8.33%   |
| 27      | 6        | 5.56%   |
| 23      | 6        | 5.56%   |
| 22      | 6        | 5.56%   |
| 15      | 4        | 3.7%    |
| 32      | 2        | 1.85%   |
| 31      | 2        | 1.85%   |
| 54      | 1        | 0.93%   |
| 34      | 1        | 0.93%   |
| 29      | 1        | 0.93%   |
| 25      | 1        | 0.93%   |
| 16      | 1        | 0.93%   |
| 14      | 1        | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 40       | 37.38%  |
| 501-600     | 20       | 18.69%  |
| 301-350     | 16       | 14.95%  |
| 351-400     | 12       | 11.21%  |
| Unknown     | 9        | 8.41%   |
| 601-700     | 5        | 4.67%   |
| 701-800     | 3        | 2.8%    |
| 201-300     | 1        | 0.93%   |
| 1001-1500   | 1        | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 50       | 47.62%  |
| 16/10   | 20       | 19.05%  |
| 5/4     | 19       | 18.1%   |
| Unknown | 8        | 7.62%   |
| 4/3     | 7        | 6.67%   |
| 21/9    | 1        | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 28       | 26.17%  |
| 201-250        | 21       | 19.63%  |
| 141-150        | 21       | 19.63%  |
| Unknown        | 9        | 8.41%   |
| 351-500        | 6        | 5.61%   |
| 301-350        | 6        | 5.61%   |
| 251-300        | 6        | 5.61%   |
| 131-140        | 3        | 2.8%    |
| 101-110        | 3        | 2.8%    |
| 111-120        | 2        | 1.87%   |
| More than 1000 | 1        | 0.93%   |
| 121-130        | 1        | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 76       | 73.08%  |
| 101-120 | 15       | 14.42%  |
| Unknown | 9        | 8.65%   |
| 121-160 | 3        | 2.88%   |
| 1-50    | 1        | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 110      | 80.88%  |
| 0     | 15       | 11.03%  |
| 2     | 11       | 8.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 55       | 30.39%  |
| Intel                             | 55       | 30.39%  |
| Qualcomm Atheros                  | 16       | 8.84%   |
| Broadcom                          | 15       | 8.29%   |
| Ralink Technology                 | 12       | 6.63%   |
| Broadcom Limited                  | 7        | 3.87%   |
| TP-Link                           | 4        | 2.21%   |
| Qualcomm Atheros Communications   | 4        | 2.21%   |
| Samsung Electronics               | 2        | 1.1%    |
| Ralink                            | 2        | 1.1%    |
| Edimax Technology                 | 2        | 1.1%    |
| Sundance Technology Inc / IC Plus | 1        | 0.55%   |
| Qualcomm                          | 1        | 0.55%   |
| Nvidia                            | 1        | 0.55%   |
| Motorola                          | 1        | 0.55%   |
| Lenovo                            | 1        | 0.55%   |
| D-Link                            | 1        | 0.55%   |
| 3Com                              | 1        | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 34       | 17.8%   |
| Intel Ethernet Connection I217-LM                                             | 11       | 5.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 5.24%   |
| Ralink RT5370 Wireless Adapter                                                | 9        | 4.71%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 9        | 4.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 8        | 4.19%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 7        | 3.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 6        | 3.14%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 5        | 2.62%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                      | 5        | 2.62%   |
| Ralink MT7601U Wireless Adapter                                               | 4        | 2.09%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 4        | 2.09%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 3        | 1.57%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 3        | 1.57%   |
| Intel I211 Gigabit Network Connection                                         | 3        | 1.57%   |
| Intel 82566DM Gigabit Network Connection                                      | 3        | 1.57%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 3        | 1.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 1.05%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 1.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.05%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 1.05%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2        | 1.05%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 2        | 1.05%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 1.05%   |
| Intel 82578DM Gigabit Network Connection                                      | 2        | 1.05%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.05%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2        | 1.05%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 1.05%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 2        | 1.05%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.52%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 0.52%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 0.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 0.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 16       | 32%     |
| Ralink Technology               | 12       | 24%     |
| Intel                           | 5        | 10%     |
| TP-Link                         | 4        | 8%      |
| Qualcomm Atheros Communications | 4        | 8%      |
| Qualcomm Atheros                | 4        | 8%      |
| Ralink                          | 2        | 4%      |
| Edimax Technology               | 2        | 4%      |
| D-Link                          | 1        | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Ralink RT5370 Wireless Adapter                                                | 9        | 17.65%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 7        | 13.73%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 6        | 11.76%  |
| Ralink MT7601U Wireless Adapter                                               | 4        | 7.84%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 3        | 5.88%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 3        | 5.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 3.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 3.92%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2        | 3.92%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 3.92%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2        | 3.92%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 1.96%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 1.96%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 1.96%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 1.96%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 1        | 1.96%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 1.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 1.96%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]          | 1        | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 51       | 37.78%  |
| Realtek Semiconductor             | 42       | 31.11%  |
| Broadcom                          | 15       | 11.11%  |
| Qualcomm Atheros                  | 13       | 9.63%   |
| Broadcom Limited                  | 7        | 5.19%   |
| Samsung Electronics               | 2        | 1.48%   |
| Sundance Technology Inc / IC Plus | 1        | 0.74%   |
| Qualcomm                          | 1        | 0.74%   |
| Nvidia                            | 1        | 0.74%   |
| Lenovo                            | 1        | 0.74%   |
| 3Com                              | 1        | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 34       | 24.46%  |
| Intel Ethernet Connection I217-LM                                          | 11       | 7.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 10       | 7.19%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 9        | 6.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 8        | 5.76%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 5        | 3.6%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 5        | 3.6%    |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 2.88%   |
| Intel I211 Gigabit Network Connection                                      | 3        | 2.16%   |
| Intel 82566DM Gigabit Network Connection                                   | 3        | 2.16%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                           | 3        | 2.16%   |
| Realtek RTL8125 2.5GbE Controller                                          | 2        | 1.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 1.44%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 2        | 1.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 2        | 1.44%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.44%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 1.44%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 1.44%   |
| Intel 82574L Gigabit Network Connection                                    | 2        | 1.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2        | 1.44%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 1.44%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 0.72%   |
| Qualcomm Fairphone 4 5G                                                    | 1        | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.72%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.72%   |
| Nvidia MCP61 Ethernet                                                      | 1        | 0.72%   |
| Lenovo Lenovo                                                              | 1        | 0.72%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.72%   |
| Intel Ethernet Connection I217-V                                           | 1        | 0.72%   |
| Intel Ethernet Connection (7) I219-V                                       | 1        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                      | 1        | 0.72%   |
| Intel Ethernet Connection (5) I219-V                                       | 1        | 0.72%   |
| Intel Ethernet Connection (2) I218-LM                                      | 1        | 0.72%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                 | 1        | 0.72%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                    | 1        | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 128      | 72.73%  |
| WiFi     | 47       | 26.7%   |
| Modem    | 1        | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 105      | 80.15%  |
| WiFi     | 26       | 19.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 108      | 83.72%  |
| 2     | 18       | 13.95%  |
| 0     | 2        | 1.55%   |
| 3     | 1        | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 129      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 9        | 60%     |
| Intel                   | 5        | 33.33%  |
| Realtek Semiconductor   | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 60%     |
| Intel AX201 Bluetooth                               | 3        | 20%     |
| Realtek RTL8821A Bluetooth                          | 1        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 6.67%   |
| Intel AX200 Bluetooth                               | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 101      | 55.8%   |
| AMD                 | 41       | 22.65%  |
| Nvidia              | 31       | 17.13%  |
| JMTek               | 2        | 1.1%    |
| C-Media Electronics | 2        | 1.1%    |
| Thermaltake         | 1        | 0.55%   |
| Tenx Technology     | 1        | 0.55%   |
| Logitech            | 1        | 0.55%   |
| Kingston Technology | 1        | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15       | 7.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15       | 7.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15       | 7.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 4.74%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 9        | 4.27%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9        | 4.27%   |
| Nvidia High Definition Audio Controller                                    | 8        | 3.79%   |
| AMD FCH Azalia Controller                                                  | 8        | 3.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 3.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 2.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 2.84%   |
| AMD Trinity HDMI Audio Controller                                          | 6        | 2.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5        | 2.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5        | 2.37%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 2.37%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 2.37%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 1.9%    |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 1.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 1.42%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.42%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 1.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.42%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1.42%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.95%   |
| JMTek USB PnP Audio Device                                                 | 2        | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 0.95%   |
| Intel HD Graphics SGPC                                                     | 2        | 0.95%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.95%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 2        | 0.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 0.95%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 0.95%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 0.95%   |
| Thermaltake Tt eSPORTS SHOCK PRO RGB 7.1                                   | 1        | 0.47%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.47%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.47%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.47%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 23       | 20.54%  |
| Samsung Electronics          | 22       | 19.64%  |
| Kingston                     | 17       | 15.18%  |
| SK hynix                     | 16       | 14.29%  |
| Micron Technology            | 9        | 8.04%   |
| Crucial                      | 6        | 5.36%   |
| Corsair                      | 4        | 3.57%   |
| Nanya Technology             | 3        | 2.68%   |
| M                            | 3        | 2.68%   |
| Ramaxel Technology           | 2        | 1.79%   |
| MINPO                        | 2        | 1.79%   |
| Unknown (E)                  | 1        | 0.89%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 0.89%   |
| S                            | 1        | 0.89%   |
| Kingmax                      | 1        | 0.89%   |
| Elpida                       | 1        | 0.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s             | 5        | 4.03%   |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 3        | 2.42%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s             | 3        | 2.42%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s             | 3        | 2.42%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s             | 3        | 2.42%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s             | 3        | 2.42%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s            | 3        | 2.42%   |
| Unknown RAM Module 4GB DIMM 400MT/s                             | 2        | 1.61%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                          | 2        | 1.61%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                          | 2        | 1.61%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                          | 2        | 1.61%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR2 1331MT/s            | 2        | 1.61%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s            | 2        | 1.61%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s             | 2        | 1.61%   |
| M RAM Module 2048MB DIMM DDR3 667MT/s                           | 2        | 1.61%   |
| Kingston RAM XK2M26-MIE 16384MB DIMM DDR4 3467MT/s              | 2        | 1.61%   |
| Crucial RAM CB16GU2666.C8ET 16GB DIMM DDR4 2667MT/s             | 2        | 1.61%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 512MB DIMM DDR 667MT/s                       | 1        | 0.81%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                            | 1        | 0.81%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s                     | 1        | 0.81%   |
| Unknown RAM Module 4096MB DIMM DDR2                             | 1        | 0.81%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM SDRAM                               | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM 667MT/s                             | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM 400MT/s                             | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                     | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                    | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM DDR2                             | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 1GB DIMM SDRAM                               | 1        | 0.81%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                        | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                     | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                          | 1        | 0.81%   |
| Unknown (E) RAM Module 4096MB DIMM DDR3 667MT/s                 | 1        | 0.81%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 512MB DIMM DDR2 533MT/s | 1        | 0.81%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                   | 1        | 0.81%   |
| SK hynix RAM Module 1GB DIMM DDR2 533MT/s                       | 1        | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 35       | 42.17%  |
| Unknown | 14       | 16.87%  |
| SDRAM   | 12       | 14.46%  |
| DDR4    | 12       | 14.46%  |
| DDR2    | 8        | 9.64%   |
| DDR     | 2        | 2.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 73       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 31       | 33.33%  |
| 2048  | 30       | 32.26%  |
| 8192  | 16       | 17.2%   |
| 1024  | 8        | 8.6%    |
| 16384 | 6        | 6.45%   |
| 512   | 2        | 2.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 23       | 23.47%  |
| 1333    | 11       | 11.22%  |
| 667     | 9        | 9.18%   |
| 800     | 8        | 8.16%   |
| 400     | 7        | 7.14%   |
| 3200    | 4        | 4.08%   |
| 2400    | 4        | 4.08%   |
| 1867    | 4        | 4.08%   |
| 1866    | 4        | 4.08%   |
| 2667    | 3        | 3.06%   |
| 1066    | 3        | 3.06%   |
| Unknown | 3        | 3.06%   |
| 3467    | 2        | 2.04%   |
| 1331    | 2        | 2.04%   |
| 533     | 2        | 2.04%   |
| 49926   | 1        | 1.02%   |
| 3600    | 1        | 1.02%   |
| 3466    | 1        | 1.02%   |
| 3000    | 1        | 1.02%   |
| 2133    | 1        | 1.02%   |
| 2048    | 1        | 1.02%   |
| 2000    | 1        | 1.02%   |
| 1800    | 1        | 1.02%   |
| 1648    | 1        | 1.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 66.67%  |
| Seiko Epson     | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson Printer | 1        | 33.33%  |
| HP LaserJet P3005   | 1        | 33.33%  |
| HP LaserJet 1018    | 1        | 33.33%  |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 3        | 27.27%  |
| Logitech                | 2        | 18.18%  |
| Cubeternet              | 2        | 18.18%  |
| Z-Star Microelectronics | 1        | 9.09%   |
| OPPO Electronics        | 1        | 9.09%   |
| eMPIA Technology        | 1        | 9.09%   |
| Chicony Electronics     | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)            | 3        | 27.27%  |
| Logitech Webcam C270               | 2        | 18.18%  |
| Z-Star Vimicro USB Camera (Altair) | 1        | 9.09%   |
| OPPO SM4250-QRD _SN:C0CE5FDA       | 1        | 9.09%   |
| eMPIA M035 Compact Web Cam         | 1        | 9.09%   |
| Cubeternet USB2.0 Camera           | 1        | 9.09%   |
| Cubeternet GL-UPC822 UVC WebCam    | 1        | 9.09%   |
| Chicony HP 720p HD Monitor Webcam  | 1        | 9.09%   |

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


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Hewlett-Packard SC Keyboard - Apollo (Liteon) | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 106      | 79.1%   |
| 1     | 25       | 18.66%  |
| 2     | 2        | 1.49%   |
| 4     | 1        | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 16       | 51.61%  |
| Net/wireless             | 7        | 22.58%  |
| Camera                   | 2        | 6.45%   |
| Unassigned class         | 1        | 3.23%   |
| Storage/ide              | 1        | 3.23%   |
| Sound                    | 1        | 3.23%   |
| Multimedia controller    | 1        | 3.23%   |
| Modem                    | 1        | 3.23%   |
| Communication controller | 1        | 3.23%   |

