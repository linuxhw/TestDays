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

Total: 227

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte  | X470 AORUS GAMING 7 WIFI... | [a28ca9b2fb](https://linux-hardware.org/?probe=a28ca9b2fb) | Sep 04, 2023 |
| HP        | 8061                        | [31a0fa50a3](https://linux-hardware.org/?probe=31a0fa50a3) | Aug 29, 2023 |
| Gigabyte  | F2A68HM-HD2                 | [8735b5577b](https://linux-hardware.org/?probe=8735b5577b) | Aug 18, 2023 |
| HP        | 3047h                       | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| HP        | 18E4                        | [6d3964fd1b](https://linux-hardware.org/?probe=6d3964fd1b) | Jul 05, 2023 |
| HP        | 18E4                        | [8a382f8911](https://linux-hardware.org/?probe=8a382f8911) | Jul 05, 2023 |
| HP        | 18E7                        | [1ae4c92b7f](https://linux-hardware.org/?probe=1ae4c92b7f) | Jun 26, 2023 |
| Gigabyte  | Z590 AORUS ELITE AX         | [0f64e88f33](https://linux-hardware.org/?probe=0f64e88f33) | Jun 23, 2023 |
| Gigabyte  | G1.Sniper Z87               | [8df9a683cb](https://linux-hardware.org/?probe=8df9a683cb) | Jun 23, 2023 |
| Gigabyte  | G1.Sniper Z87               | [4d419c5b63](https://linux-hardware.org/?probe=4d419c5b63) | Jun 23, 2023 |
| Gigabyte  | GA-990FXA-D3                | [44f21e0f7e](https://linux-hardware.org/?probe=44f21e0f7e) | Jun 17, 2023 |
| Dell      | 0HMX8D A01                  | [e96dd04034](https://linux-hardware.org/?probe=e96dd04034) | Jun 15, 2023 |
| HP        | 1494                        | [7e431c0351](https://linux-hardware.org/?probe=7e431c0351) | Jun 08, 2023 |
| HP        | 1494                        | [0f032c101b](https://linux-hardware.org/?probe=0f032c101b) | Jun 07, 2023 |
| Gigabyte  | Z590 AORUS ELITE AX         | [183ee8e37a](https://linux-hardware.org/?probe=183ee8e37a) | May 27, 2023 |
| Pegatron  | 2A94h                       | [b17003f11e](https://linux-hardware.org/?probe=b17003f11e) | May 27, 2023 |
| Dell      | 0GY6Y8 A02                  | [6a031fd8a6](https://linux-hardware.org/?probe=6a031fd8a6) | May 13, 2023 |
| Gigabyte  | Z590 AORUS ELITE AX         | [25c4b5fe60](https://linux-hardware.org/?probe=25c4b5fe60) | May 07, 2023 |
| Gigabyte  | Z590 AORUS ELITE AX         | [a2f3590a6a](https://linux-hardware.org/?probe=a2f3590a6a) | May 04, 2023 |
| Gigabyte  | Z590 AORUS ELITE AX         | [bf317c9241](https://linux-hardware.org/?probe=bf317c9241) | May 01, 2023 |
| Dell      | 0773VG A01                  | [40cf2f15c2](https://linux-hardware.org/?probe=40cf2f15c2) | Apr 25, 2023 |
| Gigabyte  | Z590 AORUS ELITE AX         | [ed8414c493](https://linux-hardware.org/?probe=ed8414c493) | Apr 24, 2023 |
| Gigabyte  | Z590 AORUS ELITE AX         | [695220be38](https://linux-hardware.org/?probe=695220be38) | Apr 24, 2023 |
| MSI       | B450 TOMAHAWK               | [fb3d31599f](https://linux-hardware.org/?probe=fb3d31599f) | Apr 18, 2023 |
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


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 19       | 11.95%  |
| OpenMandriva 4.3   | 13       | 8.18%   |
| Ubuntu 18.04       | 10       | 6.29%   |
| Zorin 16           | 9        | 5.66%   |
| OpenMandriva 4.2   | 7        | 4.4%    |
| OpenMandriva 23.01 | 7        | 4.4%    |
| Ubuntu 22.04       | 6        | 3.77%   |
| Arch Rolling       | 6        | 3.77%   |
| ROSA R10           | 3        | 1.89%   |
| Linux Mint 20      | 3        | 1.89%   |
| BlackPanther 18.1  | 3        | 1.89%   |
| Ubuntu 19.04       | 2        | 1.26%   |
| ROSA R9            | 2        | 1.26%   |
| ROSA R11           | 2        | 1.26%   |
| Pop!_OS 21.04      | 2        | 1.26%   |
| Pop!_OS 20.10      | 2        | 1.26%   |
| OpenMandriva 4.90  | 2        | 1.26%   |
| Manjaro            | 2        | 1.26%   |
| Linux Mint 21.1    | 2        | 1.26%   |
| Kali 2022.1        | 2        | 1.26%   |
| Fedora 35          | 2        | 1.26%   |
| Fedora 32          | 2        | 1.26%   |
| Fedora 30          | 2        | 1.26%   |
| ArcoLinux Rolling  | 2        | 1.26%   |
| Arch               | 2        | 1.26%   |
| Zorin 15           | 1        | 0.63%   |
| Xubuntu 20.04      | 1        | 0.63%   |
| Xubuntu 18.04      | 1        | 0.63%   |
| Xubuntu 16.04      | 1        | 0.63%   |
| Ultramarine 37     | 1        | 0.63%   |
| Ubuntu Unity 16.04 | 1        | 0.63%   |
| Ubuntu 22.10       | 1        | 0.63%   |
| Ubuntu 21.10       | 1        | 0.63%   |
| TUXEDO OS 22.04    | 1        | 0.63%   |
| ROSA R11.1         | 1        | 0.63%   |
| ROSA 12.2          | 1        | 0.63%   |
| RHEL 8             | 1        | 0.63%   |
| Reborn OS Rolling  | 1        | 0.63%   |
| Pop!_OS 20.04      | 1        | 0.63%   |
| Parrot 5.0         | 1        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 39       | 26%     |
| OpenMandriva | 28       | 18.67%  |
| Linux Mint   | 11       | 7.33%   |
| Zorin        | 10       | 6.67%   |
| Arch         | 8        | 5.33%   |
| ROSA         | 7        | 4.67%   |
| Fedora       | 7        | 4.67%   |
| Manjaro      | 6        | 4%      |
| Pop!_OS      | 5        | 3.33%   |
| Elementary   | 4        | 2.67%   |
| ArcoLinux    | 4        | 2.67%   |
| Xubuntu      | 3        | 2%      |
| Kali         | 3        | 2%      |
| Debian       | 3        | 2%      |
| BlackPanther | 3        | 2%      |
| Ultramarine  | 1        | 0.67%   |
| Ubuntu Unity | 1        | 0.67%   |
| TUXEDO OS    | 1        | 0.67%   |
| RHEL         | 1        | 0.67%   |
| Reborn OS    | 1        | 0.67%   |
| Parrot       | 1        | 0.67%   |
| LMDE         | 1        | 0.67%   |
| KDE neon     | 1        | 0.67%   |
| Endless      | 1        | 0.67%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003        | 11       | 6.43%   |
| 5.10.14-desktop-1omv4002       | 7        | 4.09%   |
| 6.1.1-desktop-1omv2290         | 6        | 3.51%   |
| 5.4.0-42-generic               | 4        | 2.34%   |
| 5.15.0-48-generic              | 3        | 1.75%   |
| 5.11.0-37-generic              | 3        | 1.75%   |
| 6.4.12-arch1-1                 | 2        | 1.17%   |
| 5.9.1-arch1-1                  | 2        | 1.17%   |
| 5.4.0-48-generic               | 2        | 1.17%   |
| 5.4.0-37-generic               | 2        | 1.17%   |
| 5.4.0-33-generic               | 2        | 1.17%   |
| 5.4.0-26-generic               | 2        | 1.17%   |
| 5.3.0-51-generic               | 2        | 1.17%   |
| 5.19.0-45-generic              | 2        | 1.17%   |
| 5.18.12-desktop-3omv4090       | 2        | 1.17%   |
| 5.16.13-desktop-1omv4003       | 2        | 1.17%   |
| 5.15.0-56-generic              | 2        | 1.17%   |
| 5.15.0-50-generic              | 2        | 1.17%   |
| 5.13.0-39-generic              | 2        | 1.17%   |
| 5.13.0-30-generic              | 2        | 1.17%   |
| 5.11.0-7620-generic            | 2        | 1.17%   |
| 4.18.16-desktop-1bP            | 2        | 1.17%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2        | 1.17%   |
| 4.15.0-55-generic              | 2        | 1.17%   |
| 4.15.0-46-generic              | 2        | 1.17%   |
| 6.4.8-desktop-2omv2390         | 1        | 0.58%   |
| 6.3.9-zen1-1-zen               | 1        | 0.58%   |
| 6.3.9-arch1-1                  | 1        | 0.58%   |
| 6.2.6-desktop-1omv2390         | 1        | 0.58%   |
| 6.1.7-200.fc37.x86_64          | 1        | 0.58%   |
| 6.1.5-273-tkg-pds              | 1        | 0.58%   |
| 6.1.4-desktop-1omv2301         | 1        | 0.58%   |
| 6.0.11-arch1-1                 | 1        | 0.58%   |
| 5.9.0-kali5-amd64              | 1        | 0.58%   |
| 5.8.14-arch1-1                 | 1        | 0.58%   |
| 5.8.0-7642-generic             | 1        | 0.58%   |
| 5.8.0-7630-generic             | 1        | 0.58%   |
| 5.8.0-14-generic               | 1        | 0.58%   |
| 5.7.7-200.fc32.x86_64          | 1        | 0.58%   |
| 5.6.14-desktop-2bP             | 1        | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 22       | 13.66%  |
| 5.15.0  | 15       | 9.32%   |
| 5.16.7  | 11       | 6.83%   |
| 4.15.0  | 10       | 6.21%   |
| 5.13.0  | 8        | 4.97%   |
| 5.11.0  | 7        | 4.35%   |
| 5.10.14 | 7        | 4.35%   |
| 6.1.1   | 6        | 3.73%   |
| 5.3.0   | 5        | 3.11%   |
| 5.19.0  | 4        | 2.48%   |
| 5.0.0   | 4        | 2.48%   |
| 5.8.0   | 3        | 1.86%   |
| 6.4.12  | 2        | 1.24%   |
| 6.3.9   | 2        | 1.24%   |
| 5.9.1   | 2        | 1.24%   |
| 5.18.12 | 2        | 1.24%   |
| 5.16.13 | 2        | 1.24%   |
| 5.16.0  | 2        | 1.24%   |
| 5.10.0  | 2        | 1.24%   |
| 4.9.60  | 2        | 1.24%   |
| 4.19.0  | 2        | 1.24%   |
| 4.18.16 | 2        | 1.24%   |
| 4.18.0  | 2        | 1.24%   |
| 6.4.8   | 1        | 0.62%   |
| 6.2.6   | 1        | 0.62%   |
| 6.1.7   | 1        | 0.62%   |
| 6.1.5   | 1        | 0.62%   |
| 6.1.4   | 1        | 0.62%   |
| 6.0.11  | 1        | 0.62%   |
| 5.9.0   | 1        | 0.62%   |
| 5.8.14  | 1        | 0.62%   |
| 5.7.7   | 1        | 0.62%   |
| 5.6.14  | 1        | 0.62%   |
| 5.6.10  | 1        | 0.62%   |
| 5.5.13  | 1        | 0.62%   |
| 5.4.8   | 1        | 0.62%   |
| 5.4.40  | 1        | 0.62%   |
| 5.3.3   | 1        | 0.62%   |
| 5.2.11  | 1        | 0.62%   |
| 5.19.12 | 1        | 0.62%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 24       | 15.09%  |
| 5.16    | 18       | 11.32%  |
| 5.15    | 17       | 10.69%  |
| 5.10    | 13       | 8.18%   |
| 4.15    | 10       | 6.29%   |
| 6.1     | 9        | 5.66%   |
| 5.13    | 9        | 5.66%   |
| 5.11    | 8        | 5.03%   |
| 5.3     | 6        | 3.77%   |
| 5.19    | 6        | 3.77%   |
| 4.9     | 5        | 3.14%   |
| 5.8     | 4        | 2.52%   |
| 5.0     | 4        | 2.52%   |
| 4.18    | 4        | 2.52%   |
| 6.4     | 3        | 1.89%   |
| 5.9     | 3        | 1.89%   |
| 6.3     | 2        | 1.26%   |
| 5.6     | 2        | 1.26%   |
| 5.18    | 2        | 1.26%   |
| 4.19    | 2        | 1.26%   |
| 6.2     | 1        | 0.63%   |
| 6.0     | 1        | 0.63%   |
| 5.7     | 1        | 0.63%   |
| 5.5     | 1        | 0.63%   |
| 5.2     | 1        | 0.63%   |
| 5.17    | 1        | 0.63%   |
| 4.4     | 1        | 0.63%   |
| 4.13    | 1        | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 137      | 96.48%  |
| i686   | 5        | 3.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 59       | 40.41%  |
| KDE5            | 41       | 28.08%  |
| Unknown         | 14       | 9.59%   |
| X-Cinnamon      | 8        | 5.48%   |
| XFCE            | 6        | 4.11%   |
| KDE4            | 4        | 2.74%   |
| Pantheon        | 3        | 2.05%   |
| i3              | 2        | 1.37%   |
| Cinnamon        | 2        | 1.37%   |
| Unity           | 1        | 0.68%   |
| MATE            | 1        | 0.68%   |
| LXDE            | 1        | 0.68%   |
| KDE             | 1        | 0.68%   |
| GNOME Flashback | 1        | 0.68%   |
| GNOME Classic   | 1        | 0.68%   |
| Budgie          | 1        | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 120      | 82.76%  |
| Wayland | 17       | 11.72%  |
| Unknown | 6        | 4.14%   |
| Tty     | 2        | 1.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 62       | 43.06%  |
| SDDM    | 36       | 25%     |
| GDM3    | 16       | 11.11%  |
| GDM     | 14       | 9.72%   |
| LightDM | 7        | 4.86%   |
| TDM     | 5        | 3.47%   |
| KDM     | 4        | 2.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 103      | 71.03%  |
| Unknown | 23       | 15.86%  |
| ar_EG   | 11       | 7.59%   |
| en_GB   | 5        | 3.45%   |
| C       | 3        | 2.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 101      | 71.13%  |
| EFI  | 41       | 28.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 102      | 68%     |
| Overlay | 25       | 16.67%  |
| Btrfs   | 6        | 4%      |
| Unknown | 6        | 4%      |
| Xfs     | 4        | 2.67%   |
| Tmpfs   | 4        | 2.67%   |
| Zfs     | 2        | 1.33%   |
| Ext2    | 1        | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 65       | 45.14%  |
| GPT     | 42       | 29.17%  |
| MBR     | 37       | 25.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 114      | 78.62%  |
| Yes       | 31       | 21.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 50.34%  |
| Yes       | 73       | 49.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 47       | 33.33%  |
| Gigabyte Technology | 35       | 24.82%  |
| Dell                | 27       | 19.15%  |
| ASUSTek Computer    | 10       | 7.09%   |
| MSI                 | 6        | 4.26%   |
| Lenovo              | 5        | 3.55%   |
| Acer                | 3        | 2.13%   |
| Intel               | 2        | 1.42%   |
| Alienware           | 2        | 1.42%   |
| Pegatron            | 1        | 0.71%   |
| IBM                 | 1        | 0.71%   |
| ECS                 | 1        | 0.71%   |
| ASRock              | 1        | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte G41MT-S2PT                | 7        | 4.96%   |
| Dell OptiPlex 780                  | 4        | 2.84%   |
| MSI MS-7C02                        | 3        | 2.13%   |
| HP ProDesk 600 G1 TWR              | 3        | 2.13%   |
| HP Compaq Pro 6305 SFF             | 3        | 2.13%   |
| HP Compaq 6005 Pro SFF PC          | 3        | 2.13%   |
| Gigabyte H61M-S2P                  | 3        | 2.13%   |
| Dell OptiPlex 760                  | 3        | 2.13%   |
| Dell OptiPlex 7020                 | 3        | 2.13%   |
| Dell OptiPlex 7010                 | 3        | 2.13%   |
| HP Z600 Workstation                | 2        | 1.42%   |
| HP ProDesk 600 G1 SFF              | 2        | 1.42%   |
| HP Compaq Elite 8300 SFF           | 2        | 1.42%   |
| HP Compaq dc7800                   | 2        | 1.42%   |
| Gigabyte H61M-S2V-B3               | 2        | 1.42%   |
| Gigabyte G41MT-S2P                 | 2        | 1.42%   |
| ASUS B250 MINING EXPERT            | 2        | 1.42%   |
| Alienware Aurora R12               | 2        | 1.42%   |
| Pegatron Pro 3010 Microtower PC    | 1        | 0.71%   |
| MSI MS-7C84                        | 1        | 0.71%   |
| MSI MS-7507                        | 1        | 0.71%   |
| MSI MS-7309                        | 1        | 0.71%   |
| Lenovo ThinkStation S30 4351D32    | 1        | 0.71%   |
| Lenovo ThinkCentre M93p 10A8000WUS | 1        | 0.71%   |
| Lenovo ThinkCentre M600 10KGS0J000 | 1        | 0.71%   |
| Lenovo ThinkCentre M58 6258D3G     | 1        | 0.71%   |
| Lenovo ThinkCentre M55p 8811Y4U    | 1        | 0.71%   |
| Intel E4610                        | 1        | 0.71%   |
| Intel DG31PR AAD97573-205          | 1        | 0.71%   |
| IBM 81713FG                        | 1        | 0.71%   |
| HP Z840 Workstation                | 1        | 0.71%   |
| HP Z820 Workstation                | 1        | 0.71%   |
| HP Z620 Workstation                | 1        | 0.71%   |
| HP Z240 Tower Workstation          | 1        | 0.71%   |
| HP Z230 SFF Workstation            | 1        | 0.71%   |
| HP xw4600 Workstation              | 1        | 0.71%   |
| HP rp5800                          | 1        | 0.71%   |
| HP rp5700 Business System          | 1        | 0.71%   |
| HP ProDesk 400 G3 MT               | 1        | 0.71%   |
| HP EliteDesk 880 G1 TWR            | 1        | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 22       | 15.6%   |
| HP Compaq            | 21       | 14.89%  |
| HP EliteDesk         | 7        | 4.96%   |
| Gigabyte G41MT-S2PT  | 7        | 4.96%   |
| HP ProDesk           | 6        | 4.26%   |
| Dell Precision       | 5        | 3.55%   |
| Lenovo ThinkCentre   | 4        | 2.84%   |
| MSI MS-7C02          | 3        | 2.13%   |
| Gigabyte H61M-S2P    | 3        | 2.13%   |
| ASUS TUF             | 3        | 2.13%   |
| HP Z600              | 2        | 1.42%   |
| Gigabyte H61M-S2V-B3 | 2        | 1.42%   |
| Gigabyte G41MT-S2P   | 2        | 1.42%   |
| ASUS B250            | 2        | 1.42%   |
| Alienware Aurora     | 2        | 1.42%   |
| Acer Veriton         | 2        | 1.42%   |
| Pegatron Pro         | 1        | 0.71%   |
| MSI MS-7C84          | 1        | 0.71%   |
| MSI MS-7507          | 1        | 0.71%   |
| MSI MS-7309          | 1        | 0.71%   |
| Lenovo ThinkStation  | 1        | 0.71%   |
| Intel E4610          | 1        | 0.71%   |
| Intel DG31PR         | 1        | 0.71%   |
| IBM 81713FG          | 1        | 0.71%   |
| HP Z840              | 1        | 0.71%   |
| HP Z820              | 1        | 0.71%   |
| HP Z620              | 1        | 0.71%   |
| HP Z240              | 1        | 0.71%   |
| HP Z230              | 1        | 0.71%   |
| HP xw4600            | 1        | 0.71%   |
| HP rp5800            | 1        | 0.71%   |
| HP rp5700            | 1        | 0.71%   |
| HP 290               | 1        | 0.71%   |
| HP 280               | 1        | 0.71%   |
| HP 1850              | 1        | 0.71%   |
| Gigabyte Z97X-Gaming | 1        | 0.71%   |
| Gigabyte Z97-D3H     | 1        | 0.71%   |
| Gigabyte Z87-HD3     | 1        | 0.71%   |
| Gigabyte Z590        | 1        | 0.71%   |
| Gigabyte X470        | 1        | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 17       | 12.06%  |
| 2013 | 16       | 11.35%  |
| 2012 | 15       | 10.64%  |
| 2009 | 15       | 10.64%  |
| 2008 | 12       | 8.51%   |
| 2018 | 9        | 6.38%   |
| 2014 | 8        | 5.67%   |
| 2010 | 8        | 5.67%   |
| 2007 | 8        | 5.67%   |
| 2021 | 5        | 3.55%   |
| 2019 | 5        | 3.55%   |
| 2017 | 5        | 3.55%   |
| 2016 | 5        | 3.55%   |
| 2015 | 4        | 2.84%   |
| 2020 | 3        | 2.13%   |
| 2006 | 3        | 2.13%   |
| 2005 | 3        | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 141      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 139      | 98.58%  |
| Enabled  | 2        | 1.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 141      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 37       | 26.06%  |
| 4.01-8.0    | 29       | 20.42%  |
| 8.01-16.0   | 29       | 20.42%  |
| 16.01-24.0  | 22       | 15.49%  |
| 32.01-64.0  | 7        | 4.93%   |
| 2.01-3.0    | 6        | 4.23%   |
| 1.01-2.0    | 5        | 3.52%   |
| 64.01-256.0 | 3        | 2.11%   |
| 24.01-32.0  | 2        | 1.41%   |
| 0.51-1.0    | 1        | 0.7%    |
| 0.01-0.5    | 1        | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 56       | 35.44%  |
| 2.01-3.0    | 44       | 27.85%  |
| 4.01-8.0    | 16       | 10.13%  |
| 3.01-4.0    | 13       | 8.23%   |
| 0.51-1.0    | 13       | 8.23%   |
| 0.01-0.5    | 8        | 5.06%   |
| 8.01-16.0   | 6        | 3.8%    |
| 64.01-256.0 | 1        | 0.63%   |
| 16.01-24.0  | 1        | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 70       | 47.3%   |
| 2       | 51       | 34.46%  |
| 3       | 17       | 11.49%  |
| 4       | 5        | 3.38%   |
| 9       | 2        | 1.35%   |
| 5       | 1        | 0.68%   |
| 0       | 1        | 0.68%   |
| Unknown | 1        | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 71       | 50%     |
| No        | 71       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 140      | 99.29%  |
| No        | 1        | 0.71%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 61.11%  |
| Yes       | 56       | 38.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 87.32%  |
| Yes       | 18       | 12.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Egypt   | 141      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Cairo               | 82       | 54.3%   |
| Giza                | 13       | 8.61%   |
| Alexandria          | 10       | 6.62%   |
| Al Mansurah         | 7        | 4.64%   |
| Tanta               | 4        | 2.65%   |
| Port Said           | 3        | 1.99%   |
| Zagazig             | 2        | 1.32%   |
| Suez                | 2        | 1.32%   |
| Mohandessin         | 2        | 1.32%   |
| Minya               | 2        | 1.32%   |
| Kafr ash Shaykh     | 2        | 1.32%   |
| Aswan               | 2        | 1.32%   |
| Assiut              | 2        | 1.32%   |
| Al Ma`adi           | 2        | 1.32%   |
| Zefta               | 1        | 0.66%   |
| Tukh                | 1        | 0.66%   |
| Sharqia             | 1        | 0.66%   |
| Sharm el Sheikh     | 1        | 0.66%   |
| New Cairo           | 1        | 0.66%   |
| Mallawi             | 1        | 0.66%   |
| Madinat an Nasr     | 1        | 0.66%   |
| Luxor               | 1        | 0.66%   |
| Ismailia            | 1        | 0.66%   |
| Hurghada            | 1        | 0.66%   |
| Helwan              | 1        | 0.66%   |
| Faiyum              | 1        | 0.66%   |
| Bilbeis             | 1        | 0.66%   |
| Al Qalyubiyah       | 1        | 0.66%   |
| Akhmim              | 1        | 0.66%   |
| 6th of October City | 1        | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 79       | 124    | 36.41%  |
| Seagate                     | 54       | 79     | 24.88%  |
| Samsung Electronics         | 23       | 32     | 10.6%   |
| Kingston                    | 14       | 24     | 6.45%   |
| Toshiba                     | 10       | 12     | 4.61%   |
| Crucial                     | 7        | 10     | 3.23%   |
| Hitachi                     | 4        | 4      | 1.84%   |
| Sandisk                     | 2        | 2      | 0.92%   |
| LITEONIT                    | 2        | 2      | 0.92%   |
| KingSpec                    | 2        | 2      | 0.92%   |
| JMicron Technology          | 2        | 2      | 0.92%   |
| HS-SSD-E100                 | 2        | 2      | 0.92%   |
| Hewlett-Packard             | 2        | 2      | 0.92%   |
| ZOTAC                       | 1        | 1      | 0.46%   |
| TwinMOS                     | 1        | 1      | 0.46%   |
| Transcend                   | 1        | 1      | 0.46%   |
| Phison Electronics          | 1        | 2      | 0.46%   |
| Micron/Crucial Technology   | 1        | 1      | 0.46%   |
| Maxtor                      | 1        | 2      | 0.46%   |
| Lite-On Technology          | 1        | 1      | 0.46%   |
| Lexar                       | 1        | 1      | 0.46%   |
| Kingston Technology Company | 1        | 1      | 0.46%   |
| Intel                       | 1        | 1      | 0.46%   |
| HS-SSD-C100                 | 1        | 1      | 0.46%   |
| Hikvision                   | 1        | 1      | 0.46%   |
| Fujitsu                     | 1        | 1      | 0.46%   |
| Apple                       | 1        | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 7        | 2.86%   |
| Seagate ST3500414CS 500GB                           | 7        | 2.86%   |
| Toshiba DT01ACA050 500GB                            | 5        | 2.04%   |
| Seagate ST3500312CS 500GB                           | 5        | 2.04%   |
| Seagate ST3500413AS 500GB                           | 4        | 1.63%   |
| Kingston SA400S37480G 480GB SSD                     | 4        | 1.63%   |
| Kingston SA400S37240G 240GB SSD                     | 4        | 1.63%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 3        | 1.22%   |
| WDC WD5000AAKX-001CA0 500GB                         | 3        | 1.22%   |
| WDC WD5000AADS-00S9B0 500GB                         | 3        | 1.22%   |
| WDC WD3200AAJS-00L7A0 320GB                         | 3        | 1.22%   |
| WDC WD2500AAKX-75U6AA0 250GB                        | 3        | 1.22%   |
| WDC WD1600AABS-00PRA0 160GB                         | 3        | 1.22%   |
| WDC WD1600AABS-00H4A0 160GB                         | 3        | 1.22%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 1.22%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3        | 1.22%   |
| WDC WD10EARS-00Y5B1 1TB                             | 3        | 1.22%   |
| Toshiba DT01ACA100 1TB                              | 3        | 1.22%   |
| Seagate ST3320311CS 320GB                           | 3        | 1.22%   |
| Kingston SA400S37120G 120GB SSD                     | 3        | 1.22%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 2        | 0.82%   |
| WDC WD800BD-22MRA1 80GB                             | 2        | 0.82%   |
| WDC WD5000AVVS-63H0B1 500GB                         | 2        | 0.82%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 2        | 0.82%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 2        | 0.82%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 2        | 0.82%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 2        | 0.82%   |
| Seagate ST500DM002-1SB10A 500GB                     | 2        | 0.82%   |
| Seagate ST380815AS 80GB                             | 2        | 0.82%   |
| Seagate ST3250318AS 250GB                           | 2        | 0.82%   |
| Seagate ST3160815AS 160GB                           | 2        | 0.82%   |
| Seagate ST250DM000-1BD141 250GB                     | 2        | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 0.82%   |
| Seagate ST1000VM002-1CT162 1TB                      | 2        | 0.82%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2        | 0.82%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2        | 0.82%   |
| Samsung SSD 860 EVO 500GB                           | 2        | 0.82%   |
| Samsung PM9A1 NVMe 256GB                            | 2        | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2        | 0.82%   |
| Samsung HD503HI 500GB                               | 2        | 0.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 75       | 119    | 48.7%   |
| Seagate             | 54       | 79     | 35.06%  |
| Toshiba             | 9        | 11     | 5.84%   |
| Samsung Electronics | 8        | 11     | 5.19%   |
| Hitachi             | 4        | 4      | 2.6%    |
| Maxtor              | 1        | 2      | 0.65%   |
| Hewlett-Packard     | 1        | 1      | 0.65%   |
| Fujitsu             | 1        | 1      | 0.65%   |
| Apple               | 1        | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 14       | 23     | 27.45%  |
| Samsung Electronics | 10       | 10     | 19.61%  |
| Crucial             | 7        | 10     | 13.73%  |
| WDC                 | 5        | 5      | 9.8%    |
| LITEONIT            | 2        | 2      | 3.92%   |
| KingSpec            | 2        | 2      | 3.92%   |
| JMicron Technology  | 2        | 2      | 3.92%   |
| ZOTAC               | 1        | 1      | 1.96%   |
| TwinMOS             | 1        | 1      | 1.96%   |
| Transcend           | 1        | 1      | 1.96%   |
| Toshiba             | 1        | 1      | 1.96%   |
| SanDisk             | 1        | 1      | 1.96%   |
| Lexar               | 1        | 1      | 1.96%   |
| Intel               | 1        | 1      | 1.96%   |
| Hikvision           | 1        | 1      | 1.96%   |
| Hewlett-Packard     | 1        | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 130      | 229    | 69.15%  |
| SSD     | 43       | 63     | 22.87%  |
| NVMe    | 12       | 18     | 6.38%   |
| Unknown | 3        | 3      | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 136      | 291    | 90.07%  |
| NVMe | 12       | 18     | 7.95%   |
| SAS  | 3        | 4      | 1.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 117      | 216    | 69.64%  |
| 0.51-1.0   | 37       | 50     | 22.02%  |
| 1.01-2.0   | 11       | 16     | 6.55%   |
| 3.01-4.0   | 2        | 4      | 1.19%   |
| 4.01-10.0  | 1        | 6      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 33       | 21.15%  |
| 101-250        | 33       | 21.15%  |
| 51-100         | 20       | 12.82%  |
| 1-20           | 19       | 12.18%  |
| 501-1000       | 18       | 11.54%  |
| 21-50          | 14       | 8.97%   |
| 1001-2000      | 8        | 5.13%   |
| More than 3000 | 4        | 2.56%   |
| Unknown        | 4        | 2.56%   |
| 2001-3000      | 3        | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 67       | 43.51%  |
| 101-250        | 26       | 16.88%  |
| 21-50          | 18       | 11.69%  |
| 251-500        | 15       | 9.74%   |
| 51-100         | 11       | 7.14%   |
| 501-1000       | 8        | 5.19%   |
| Unknown        | 4        | 2.6%    |
| More than 3000 | 2        | 1.3%    |
| 1001-2000      | 2        | 1.3%    |
| 2001-3000      | 1        | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63H0B1 500GB                      | 2        | 2      | 4.08%   |
| WDC WD5000AVDS-63U7B1 500GB                      | 2        | 2      | 4.08%   |
| WDC WD5000AAKX-00ERMA0 500GB                     | 2        | 3      | 4.08%   |
| WDC WD1600AABS-00H4A0 160GB                      | 2        | 2      | 4.08%   |
| Seagate ST380815AS 80GB                          | 2        | 2      | 4.08%   |
| Seagate ST3500413AS 500GB                        | 2        | 2      | 4.08%   |
| WDC WD800JD-60LSA5 80GB                          | 1        | 1      | 2.04%   |
| WDC WD800BD-22MRA1 80GB                          | 1        | 1      | 2.04%   |
| WDC WD5000AAVS-22G9B1 500GB                      | 1        | 1      | 2.04%   |
| WDC WD5000AAKX-75U6AA0 500GB                     | 1        | 2      | 2.04%   |
| WDC WD5000AAKX-08U6AA0 500GB                     | 1        | 2      | 2.04%   |
| WDC WD5000AAKX-009FA0 500GB                      | 1        | 1      | 2.04%   |
| WDC WD5000AAKS-00V6A0 500GB                      | 1        | 1      | 2.04%   |
| WDC WD5000AADS-00S9B0 500GB                      | 1        | 1      | 2.04%   |
| WDC WD5000AADS-00M2B0 500GB                      | 1        | 1      | 2.04%   |
| WDC WD3200AAJS-56M0A0 320GB                      | 1        | 1      | 2.04%   |
| WDC WD3200AAJS-56B4A0 320GB                      | 1        | 2      | 2.04%   |
| WDC WD3200AAJS-00L7A0 320GB                      | 1        | 1      | 2.04%   |
| WDC WD3200AAJS-00B4A0 320GB                      | 1        | 1      | 2.04%   |
| WDC WD3200A 320GB                                | 1        | 1      | 2.04%   |
| WDC WD2500AAJS-00VTA0 250GB                      | 1        | 1      | 2.04%   |
| WDC WD1600AVVS-63L2B0 160GB                      | 1        | 1      | 2.04%   |
| WDC WD1600AAJS-00L7A0 160GB                      | 1        | 1      | 2.04%   |
| WDC WD10EZEX-08M2NA0 1TB                         | 1        | 1      | 2.04%   |
| WDC WD10EZEX-00BN5A0 1TB                         | 1        | 1      | 2.04%   |
| WDC WD10EARS-00Y5B1 1TB                          | 1        | 1      | 2.04%   |
| Toshiba MQ01ABF050 500GB                         | 1        | 2      | 2.04%   |
| Seagate ST500DM002-1SB10A 500GB                  | 1        | 1      | 2.04%   |
| Seagate ST500DM002-1BD142 500GB                  | 1        | 3      | 2.04%   |
| Seagate ST3500312CS 500GB                        | 1        | 1      | 2.04%   |
| Seagate ST3320613AS 320GB                        | 1        | 1      | 2.04%   |
| Seagate ST3320311CS 320GB                        | 1        | 1      | 2.04%   |
| Seagate ST3160211AS 160GB                        | 1        | 2      | 2.04%   |
| Seagate ST250DM000-1BD141 250GB                  | 1        | 1      | 2.04%   |
| Seagate ST2000DM008-2FR102 2TB                   | 1        | 2      | 2.04%   |
| Seagate ST2000DM001-1ER164 2TB                   | 1        | 1      | 2.04%   |
| Seagate ST1000DM003-1CH162 1TB                   | 1        | 1      | 2.04%   |
| Samsung Electronics SSD 870 EVO 500GB            | 1        | 1      | 2.04%   |
| Samsung Electronics MZ7TD128HAFV-000L1 128GB SSD | 1        | 1      | 2.04%   |
| Samsung Electronics HD256GJ 250GB                | 1        | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 32     | 55.81%  |
| Seagate             | 12       | 18     | 27.91%  |
| Samsung Electronics | 3        | 3      | 6.98%   |
| Toshiba             | 1        | 2      | 2.33%   |
| Kingston            | 1        | 2      | 2.33%   |
| Intel               | 1        | 1      | 2.33%   |
| Hewlett-Packard     | 1        | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 32     | 61.54%  |
| Seagate             | 12       | 18     | 30.77%  |
| Toshiba             | 1        | 2      | 2.56%   |
| Samsung Electronics | 1        | 1      | 2.56%   |
| Hewlett-Packard     | 1        | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 37       | 54     | 90.24%  |
| SSD  | 4        | 5      | 9.76%   |

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
| Detected | 75       | 150    | 45.45%  |
| Works    | 47       | 100    | 28.48%  |
| Malfunc  | 40       | 59     | 24.24%  |
| Failed   | 3        | 4      | 1.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 110      | 69.18%  |
| AMD                         | 29       | 18.24%  |
| Samsung Electronics         | 7        | 4.4%    |
| Marvell Technology Group    | 2        | 1.26%   |
| Kingston Technology Company | 2        | 1.26%   |
| Broadcom / LSI              | 2        | 1.26%   |
| SanDisk                     | 1        | 0.63%   |
| Phison Electronics          | 1        | 0.63%   |
| Nvidia                      | 1        | 0.63%   |
| Micron/Crucial Technology   | 1        | 0.63%   |
| LSI Logic / Symbios Logic   | 1        | 0.63%   |
| Lite-On Technology          | 1        | 0.63%   |
| JMicron Technology          | 1        | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 17       | 7.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 6.94%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 6.48%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 4.17%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 3.24%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 3.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 2.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 1.85%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.85%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 4        | 1.85%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 4        | 1.85%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.85%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.39%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 1.39%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 1.39%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 1.39%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.39%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.93%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.93%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.93%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.93%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 2        | 0.93%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2        | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.93%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 84       | 49.41%  |
| IDE  | 56       | 32.94%  |
| RAID | 13       | 7.65%   |
| NVMe | 12       | 7.06%   |
| SAS  | 4        | 2.35%   |
| SCSI | 1        | 0.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 111      | 78.72%  |
| AMD    | 30       | 21.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 6        | 4.23%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 3.52%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 3.52%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 2.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 2.82%   |
| Intel Pentium D CPU 3.00GHz                 | 3        | 2.11%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.11%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 3        | 2.11%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 2.11%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 2.11%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz     | 3        | 2.11%   |
| AMD A4-5300B APU with Radeon HD Graphics    | 3        | 2.11%   |
| Intel Pentium 4 CPU 3.20GHz                 | 2        | 1.41%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 1.41%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.41%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.41%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.41%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.41%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.41%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 2        | 1.41%   |
| Intel Core 2 Duo CPU E4400 @ 2.00GHz        | 2        | 1.41%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 2        | 1.41%   |
| Intel Celeron D CPU 3.06GHz                 | 2        | 1.41%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.41%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.41%   |
| AMD Phenom II X4 B95 Processor              | 2        | 1.41%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.7%    |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5640 @ 2.67GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5-2690 v2 @ 3.00GHz         | 1        | 0.7%    |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz         | 1        | 0.7%    |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz          | 1        | 0.7%    |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1        | 0.7%    |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 0.7%    |
| Intel Xeon CPU 3.20GHz                      | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.7%    |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 28       | 19.72%  |
| Intel Core 2 Duo        | 21       | 14.79%  |
| Intel Core i7           | 15       | 10.56%  |
| Intel Xeon              | 11       | 7.75%   |
| Intel Core i3           | 10       | 7.04%   |
| AMD Ryzen 5             | 6        | 4.23%   |
| Other                   | 5        | 3.52%   |
| Intel Core 2 Quad       | 4        | 2.82%   |
| Intel Core 2            | 4        | 2.82%   |
| AMD A4                  | 4        | 2.82%   |
| Intel Pentium D         | 3        | 2.11%   |
| Intel Pentium 4         | 3        | 2.11%   |
| AMD Ryzen 7             | 3        | 2.11%   |
| Intel Pentium Dual-Core | 2        | 1.41%   |
| Intel Pentium           | 2        | 1.41%   |
| Intel Celeron D         | 2        | 1.41%   |
| Intel Celeron           | 2        | 1.41%   |
| AMD Phenom II X4        | 2        | 1.41%   |
| AMD Phenom              | 2        | 1.41%   |
| AMD Athlon II X2        | 2        | 1.41%   |
| AMD A8                  | 2        | 1.41%   |
| AMD Sempron             | 1        | 0.7%    |
| AMD Ryzen 9             | 1        | 0.7%    |
| AMD PRO A10             | 1        | 0.7%    |
| AMD FX                  | 1        | 0.7%    |
| AMD Athlon II X3        | 1        | 0.7%    |
| AMD Athlon 64 X2        | 1        | 0.7%    |
| AMD Athlon 64           | 1        | 0.7%    |
| AMD A6                  | 1        | 0.7%    |
| AMD A10                 | 1        | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 51       | 35.92%  |
| 4      | 49       | 34.51%  |
| 1      | 13       | 9.15%   |
| 8      | 11       | 7.75%   |
| 6      | 10       | 7.04%   |
| 3      | 3        | 2.11%   |
| 16     | 2        | 1.41%   |
| 24     | 1        | 0.7%    |
| 12     | 1        | 0.7%    |
| 10     | 1        | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 134      | 95.04%  |
| 2      | 7        | 4.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 83       | 58.04%  |
| 2      | 60       | 41.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 139      | 97.89%  |
| 32-bit         | 2        | 1.41%   |
| Unknown        | 1        | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 34       | 23.29%  |
| 0x306c3    | 15       | 10.27%  |
| 0x1067a    | 15       | 10.27%  |
| 0x306a9    | 8        | 5.48%   |
| 0x206a7    | 8        | 5.48%   |
| 0x6fb      | 5        | 3.42%   |
| 0xf65      | 4        | 2.74%   |
| 0x06001119 | 4        | 2.74%   |
| 0xa0671    | 3        | 2.05%   |
| 0x906ea    | 3        | 2.05%   |
| 0x6fd      | 3        | 2.05%   |
| 0x506e3    | 3        | 2.05%   |
| 0x206c2    | 3        | 2.05%   |
| 0x0800820d | 3        | 2.05%   |
| 0x010000c8 | 3        | 2.05%   |
| 0xf41      | 2        | 1.37%   |
| 0x906e9    | 2        | 1.37%   |
| 0x6f6      | 2        | 1.37%   |
| 0x306e4    | 2        | 1.37%   |
| 0x106a5    | 2        | 1.37%   |
| 0x10676    | 2        | 1.37%   |
| 0x01000095 | 2        | 1.37%   |
| 0xf64      | 1        | 0.68%   |
| 0xf43      | 1        | 0.68%   |
| 0x906ed    | 1        | 0.68%   |
| 0x6f2      | 1        | 0.68%   |
| 0x406c4    | 1        | 0.68%   |
| 0x306f2    | 1        | 0.68%   |
| 0x206d7    | 1        | 0.68%   |
| 0x20655    | 1        | 0.68%   |
| 0x20652    | 1        | 0.68%   |
| 0x106e5    | 1        | 0.68%   |
| 0x0a201009 | 1        | 0.68%   |
| 0x08701021 | 1        | 0.68%   |
| 0x08701013 | 1        | 0.68%   |
| 0x08701012 | 1        | 0.68%   |
| 0x08008204 | 1        | 0.68%   |
| 0x0600063e | 1        | 0.68%   |
| 0x010000db | 1        | 0.68%   |
| 0x010000b6 | 1        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 21       | 14.69%  |
| Penryn      | 19       | 13.29%  |
| Core        | 13       | 9.09%   |
| SandyBridge | 11       | 7.69%   |
| IvyBridge   | 11       | 7.69%   |
| NetBurst    | 10       | 6.99%   |
| KabyLake    | 9        | 6.29%   |
| K10         | 8        | 5.59%   |
| Piledriver  | 6        | 4.2%    |
| Westmere    | 5        | 3.5%    |
| Zen+        | 4        | 2.8%    |
| Zen 2       | 4        | 2.8%    |
| Skylake     | 4        | 2.8%    |
| Nehalem     | 3        | 2.1%    |
| Icelake     | 3        | 2.1%    |
| Unknown     | 3        | 2.1%    |
| Zen 3       | 2        | 1.4%    |
| Steamroller | 2        | 1.4%    |
| K8 Hammer   | 2        | 1.4%    |
| Silvermont  | 1        | 0.7%    |
| Excavator   | 1        | 0.7%    |
| Bulldozer   | 1        | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 71       | 46.71%  |
| Nvidia | 43       | 28.29%  |
| AMD    | 38       | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 17       | 10.83%  |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 15       | 9.55%   |
| Nvidia GT218 [GeForce 210]                                                  | 8        | 5.1%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 4.46%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 3.82%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 5        | 3.18%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 2.55%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.91%   |
| Nvidia GF119 [NVS 315]                                                      | 3        | 1.91%   |
| Nvidia GF108GL [Quadro 600]                                                 | 3        | 1.91%   |
| Intel HD Graphics 630                                                       | 3        | 1.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.91%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 3        | 1.91%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.91%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 1.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.91%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 3        | 1.91%   |
| AMD RS880 [Radeon HD 4200]                                                  | 3        | 1.91%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.91%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.27%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 2        | 1.27%   |
| Intel HD Graphics 530                                                       | 2        | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.27%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1.27%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.27%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.64%   |
| Nvidia NV18 [GeForce4 MX 4000]                                              | 1        | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.64%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.64%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.64%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.64%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.64%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.64%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.64%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.64%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.64%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.64%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.64%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| 1 x Intel              | 60       | 41.67%  |
| 1 x Nvidia             | 39       | 27.08%  |
| 1 x AMD                | 31       | 21.53%  |
| Intel + AMD            | 4        | 2.78%   |
| Intel + Nvidia         | 3        | 2.08%   |
| 2 x Intel              | 2        | 1.39%   |
| 3 x AMD                | 1        | 0.69%   |
| 2 x Nvidia             | 1        | 0.69%   |
| 2 x AMD                | 1        | 0.69%   |
| 1 x Intel + 3 x Nvidia | 1        | 0.69%   |
| AMD + Nvidia           | 1        | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 111      | 76.55%  |
| Proprietary | 22       | 15.17%  |
| Unknown     | 12       | 8.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 76       | 52.05%  |
| 0.01-0.5   | 19       | 13.01%  |
| 0.51-1.0   | 18       | 12.33%  |
| 1.01-2.0   | 14       | 9.59%   |
| 7.01-8.0   | 9        | 6.16%   |
| 3.01-4.0   | 6        | 4.11%   |
| 8.01-16.0  | 4        | 2.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 29       | 24.17%  |
| Dell                    | 26       | 21.67%  |
| Hewlett-Packard         | 21       | 17.5%   |
| Lenovo                  | 7        | 5.83%   |
| Goldstar                | 7        | 5.83%   |
| NEC Computers           | 3        | 2.5%    |
| ASUSTek Computer        | 3        | 2.5%    |
| Philips                 | 2        | 1.67%   |
| Fujitsu Siemens         | 2        | 1.67%   |
| Eizo                    | 2        | 1.67%   |
| BenQ                    | 2        | 1.67%   |
| AOC                     | 2        | 1.67%   |
| Acer                    | 2        | 1.67%   |
| ViewSonic               | 1        | 0.83%   |
| Unknown                 | 1        | 0.83%   |
| Sun                     | 1        | 0.83%   |
| Sony                    | 1        | 0.83%   |
| Planar                  | 1        | 0.83%   |
| MStar                   | 1        | 0.83%   |
| JWY                     | 1        | 0.83%   |
| Gigabyte Technology     | 1        | 0.83%   |
| eMachines               | 1        | 0.83%   |
| Chi Mei Optoelectronics | 1        | 0.83%   |
| AUS                     | 1        | 0.83%   |
| Ancor Communications    | 1        | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                     | 5        | 3.97%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch     | 3        | 2.38%   |
| Lenovo LEN T2454pA LEN60C9 1920x1080 518x324mm 24.1-inch             | 3        | 2.38%   |
| Hewlett-Packard L1950 HWP26E7 1280x1024 380x300mm 19.1-inch          | 3        | 2.38%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 2        | 1.59%   |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch  | 2        | 1.59%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 2        | 1.59%   |
| Hewlett-Packard LA2206 HWP2948 1920x1080 476x268mm 21.5-inch         | 2        | 1.59%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch         | 2        | 1.59%   |
| Hewlett-Packard LA2006 HWP2943 1600x900 443x249mm 20.0-inch          | 2        | 1.59%   |
| Dell P2211H DEL4060 1920x1080 480x270mm 21.7-inch                    | 2        | 1.59%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                     | 2        | 1.59%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch        | 1        | 0.79%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                 | 1        | 0.79%   |
| Sun PN17JO SUN0589 1280x1024 295x236mm 14.9-inch                     | 1        | 0.79%   |
| Sony KDL-23S2000 SNY9900 1360x768                                    | 1        | 0.79%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM0590 1600x900 443x249mm 20.0-inch  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch | 1        | 0.79%   |
| Samsung Electronics SMBX2031 SAM076A 1600x900 443x249mm 20.0-inch    | 1        | 0.79%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch    | 1        | 0.79%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1        | 0.79%   |
| Samsung Electronics S23B300 SAM08AE 1920x1080 510x287mm 23.0-inch    | 1        | 0.79%   |
| Samsung Electronics S22E200 SAM0C6D 1920x1080 477x268mm 21.5-inch    | 1        | 0.79%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1        | 0.79%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 1        | 0.79%   |
| Samsung Electronics S19B300 SAM08A4 1366x768 410x230mm 18.5-inch     | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SMBX2350 1920x1080                   | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                   | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SA300/SA350 1366x768                 | 1        | 0.79%   |
| Samsung Electronics LCD Monitor S24D330 1920x1080                    | 1        | 0.79%   |
| Samsung Electronics LCD Monitor S22D300 5760x1080                    | 1        | 0.79%   |
| Samsung Electronics LCD Monitor S22D300 1920x1080                    | 1        | 0.79%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 597x336mm 27.0-inch   | 1        | 0.79%   |
| Samsung Electronics C24FG7x SAM0E43 1920x1080 532x304mm 24.1-inch    | 1        | 0.79%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1        | 0.79%   |
| Planar PE2010 PLN2010 1400x1050 400x300mm 19.7-inch                  | 1        | 0.79%   |
| Philips 190CW PHLC023 1440x900 408x255mm 18.9-inch                   | 1        | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 42       | 35.59%  |
| 1280x1024 (SXGA)   | 22       | 18.64%  |
| 1440x900 (WXGA+)   | 11       | 9.32%   |
| 1366x768 (WXGA)    | 10       | 8.47%   |
| 1600x900 (HD+)     | 8        | 6.78%   |
| 1680x1050 (WSXGA+) | 7        | 5.93%   |
| 3840x2160 (4K)     | 3        | 2.54%   |
| 2560x1440 (QHD)    | 3        | 2.54%   |
| 1600x1200          | 2        | 1.69%   |
| 5760x1080          | 1        | 0.85%   |
| 3440x1440          | 1        | 0.85%   |
| 2560x1600          | 1        | 0.85%   |
| 1920x540           | 1        | 0.85%   |
| 1920x1200 (WUXGA)  | 1        | 0.85%   |
| 1400x1050          | 1        | 0.85%   |
| 1360x768           | 1        | 0.85%   |
| 1280x720 (HD)      | 1        | 0.85%   |
| 1024x768 (XGA)     | 1        | 0.85%   |
| Unknown            | 1        | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 17       | 14.29%  |
| 19      | 15       | 12.61%  |
| 24      | 12       | 10.08%  |
| 21      | 12       | 10.08%  |
| 18      | 10       | 8.4%    |
| Unknown | 10       | 8.4%    |
| 20      | 9        | 7.56%   |
| 27      | 7        | 5.88%   |
| 23      | 7        | 5.88%   |
| 22      | 6        | 5.04%   |
| 15      | 4        | 3.36%   |
| 32      | 2        | 1.68%   |
| 31      | 2        | 1.68%   |
| 54      | 1        | 0.84%   |
| 34      | 1        | 0.84%   |
| 29      | 1        | 0.84%   |
| 25      | 1        | 0.84%   |
| 16      | 1        | 0.84%   |
| 14      | 1        | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 45       | 38.14%  |
| 501-600     | 24       | 20.34%  |
| 301-350     | 16       | 13.56%  |
| 351-400     | 13       | 11.02%  |
| Unknown     | 10       | 8.47%   |
| 601-700     | 5        | 4.24%   |
| 701-800     | 3        | 2.54%   |
| 201-300     | 1        | 0.85%   |
| 1001-1500   | 1        | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 57       | 49.14%  |
| 16/10   | 23       | 19.83%  |
| 5/4     | 19       | 16.38%  |
| Unknown | 9        | 7.76%   |
| 4/3     | 7        | 6.03%   |
| 21/9    | 1        | 0.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 30       | 25.42%  |
| 201-250        | 26       | 22.03%  |
| 141-150        | 21       | 17.8%   |
| Unknown        | 10       | 8.47%   |
| 301-350        | 7        | 5.93%   |
| 251-300        | 7        | 5.93%   |
| 351-500        | 6        | 5.08%   |
| 131-140        | 4        | 3.39%   |
| 101-110        | 3        | 2.54%   |
| 111-120        | 2        | 1.69%   |
| More than 1000 | 1        | 0.85%   |
| 121-130        | 1        | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 82       | 71.3%   |
| 101-120 | 19       | 16.52%  |
| Unknown | 10       | 8.7%    |
| 121-160 | 3        | 2.61%   |
| 1-50    | 1        | 0.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 121      | 81.76%  |
| 0     | 15       | 10.14%  |
| 2     | 12       | 8.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 62       | 31%     |
| Realtek Semiconductor             | 61       | 30.5%   |
| Qualcomm Atheros                  | 17       | 8.5%    |
| Broadcom                          | 16       | 8%      |
| Ralink Technology                 | 15       | 7.5%    |
| Broadcom Limited                  | 7        | 3.5%    |
| TP-Link                           | 5        | 2.5%    |
| Qualcomm Atheros Communications   | 4        | 2%      |
| Samsung Electronics               | 2        | 1%      |
| Ralink                            | 2        | 1%      |
| Edimax Technology                 | 2        | 1%      |
| Sundance Technology Inc / IC Plus | 1        | 0.5%    |
| Qualcomm                          | 1        | 0.5%    |
| Nvidia                            | 1        | 0.5%    |
| Motorola                          | 1        | 0.5%    |
| Lenovo                            | 1        | 0.5%    |
| D-Link                            | 1        | 0.5%    |
| 3Com                              | 1        | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 37       | 17.29%  |
| Intel Ethernet Connection I217-LM                                             | 13       | 6.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13       | 6.07%   |
| Ralink RT5370 Wireless Adapter                                                | 11       | 5.14%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 9        | 4.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 8        | 3.74%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 7        | 3.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 7        | 3.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 6        | 2.8%    |
| Ralink MT7601U Wireless Adapter                                               | 5        | 2.34%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                      | 5        | 2.34%   |
| Intel I211 Gigabit Network Connection                                         | 4        | 1.87%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 4        | 1.87%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.4%    |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 3        | 1.4%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 3        | 1.4%    |
| Intel 82566DM Gigabit Network Connection                                      | 3        | 1.4%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 3        | 1.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 0.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 0.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.93%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 0.93%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2        | 0.93%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 0.93%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 2        | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 0.93%   |
| Intel 82578DM Gigabit Network Connection                                      | 2        | 0.93%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 0.93%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2        | 0.93%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.93%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 2        | 0.93%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.47%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 0.47%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.47%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 21       | 34.43%  |
| Ralink Technology               | 15       | 24.59%  |
| Intel                           | 7        | 11.48%  |
| TP-Link                         | 5        | 8.2%    |
| Qualcomm Atheros Communications | 4        | 6.56%   |
| Qualcomm Atheros                | 4        | 6.56%   |
| Ralink                          | 2        | 3.28%   |
| Edimax Technology               | 2        | 3.28%   |
| D-Link                          | 1        | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Ralink RT5370 Wireless Adapter                                                | 11       | 17.74%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 7        | 11.29%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 7        | 11.29%  |
| Ralink MT7601U Wireless Adapter                                               | 5        | 8.06%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 3        | 4.84%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 3        | 4.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 3.23%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 3.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 3.23%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2        | 3.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 3.23%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2        | 3.23%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 1.61%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 1.61%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 1.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 1.61%   |
| Realtek RTL8187 Wireless Adapter                                              | 1        | 1.61%   |
| Realtek 802.11ac NIC                                                          | 1        | 1.61%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 1.61%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 1        | 1.61%   |
| Intel Wireless-AC 9260                                                        | 1        | 1.61%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 1.61%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]          | 1        | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 57       | 38.78%  |
| Realtek Semiconductor             | 46       | 31.29%  |
| Broadcom                          | 16       | 10.88%  |
| Qualcomm Atheros                  | 14       | 9.52%   |
| Broadcom Limited                  | 7        | 4.76%   |
| Samsung Electronics               | 2        | 1.36%   |
| Sundance Technology Inc / IC Plus | 1        | 0.68%   |
| Qualcomm                          | 1        | 0.68%   |
| Nvidia                            | 1        | 0.68%   |
| Lenovo                            | 1        | 0.68%   |
| 3Com                              | 1        | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 37       | 24.5%   |
| Intel Ethernet Connection I217-LM                                          | 13       | 8.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 13       | 8.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 9        | 5.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 8        | 5.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 6        | 3.97%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 5        | 3.31%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 2.65%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 2.65%   |
| Realtek RTL8125 2.5GbE Controller                                          | 3        | 1.99%   |
| Intel 82566DM Gigabit Network Connection                                   | 3        | 1.99%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                           | 3        | 1.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 1.32%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 2        | 1.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1.32%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 2        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 1.32%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 1.32%   |
| Intel 82574L Gigabit Network Connection                                    | 2        | 1.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2        | 1.32%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 1.32%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.66%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.66%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 0.66%   |
| Qualcomm Redmi Note 8                                                      | 1        | 0.66%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.66%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.66%   |
| Nvidia MCP61 Ethernet                                                      | 1        | 0.66%   |
| Lenovo Lenovo                                                              | 1        | 0.66%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.66%   |
| Intel Ethernet Connection I217-V                                           | 1        | 0.66%   |
| Intel Ethernet Connection (7) I219-V                                       | 1        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                      | 1        | 0.66%   |
| Intel Ethernet Connection (5) I219-V                                       | 1        | 0.66%   |
| Intel Ethernet Connection (2) I218-LM                                      | 1        | 0.66%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                 | 1        | 0.66%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                    | 1        | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 140      | 71.43%  |
| WiFi     | 55       | 28.06%  |
| Modem    | 1        | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 113      | 77.93%  |
| WiFi     | 32       | 22.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 116      | 82.27%  |
| 2     | 22       | 15.6%   |
| 0     | 2        | 1.42%   |
| 3     | 1        | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 140      | 98.59%  |
| Yes  | 2        | 1.41%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 11       | 57.89%  |
| Intel                   | 7        | 36.84%  |
| Realtek Semiconductor   | 1        | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 57.89%  |
| Intel AX201 Bluetooth                               | 4        | 21.05%  |
| Realtek RTL8821A Bluetooth                          | 1        | 5.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 5.26%   |
| Intel AX200 Bluetooth                               | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 110      | 55%     |
| AMD                 | 45       | 22.5%   |
| Nvidia              | 36       | 18%     |
| JMTek               | 2        | 1%      |
| C-Media Electronics | 2        | 1%      |
| Thermaltake         | 1        | 0.5%    |
| Tenx Technology     | 1        | 0.5%    |
| Logitech            | 1        | 0.5%    |
| Kingston Technology | 1        | 0.5%    |
| Astro Gaming        | 1        | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18       | 7.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17       | 7.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15       | 6.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 4.66%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10       | 4.24%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 9        | 3.81%   |
| Nvidia High Definition Audio Controller                                    | 8        | 3.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 3.39%   |
| AMD FCH Azalia Controller                                                  | 8        | 3.39%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 3.39%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 2.54%   |
| AMD Trinity HDMI Audio Controller                                          | 6        | 2.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 2.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5        | 2.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5        | 2.12%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 2.12%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 1.69%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 1.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 1.69%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 1.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 1.27%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.27%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.27%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1.27%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.85%   |
| JMTek USB PnP Audio Device                                                 | 2        | 0.85%   |
| Intel HD Graphics SGPC                                                     | 2        | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.85%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 2        | 0.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 0.85%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 0.85%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 0.85%   |
| Thermaltake Tt eSPORTS SHOCK PRO RGB 7.1                                   | 1        | 0.42%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 24       | 20%     |
| Samsung Electronics          | 23       | 19.17%  |
| Kingston                     | 18       | 15%     |
| SK hynix                     | 17       | 14.17%  |
| Micron Technology            | 10       | 8.33%   |
| Crucial                      | 6        | 5%      |
| Corsair                      | 5        | 4.17%   |
| Ramaxel Technology           | 3        | 2.5%    |
| Nanya Technology             | 3        | 2.5%    |
| M                            | 3        | 2.5%    |
| MINPO                        | 2        | 1.67%   |
| Unknown (E)                  | 1        | 0.83%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 0.83%   |
| S                            | 1        | 0.83%   |
| Kingmax                      | 1        | 0.83%   |
| G.Skill                      | 1        | 0.83%   |
| Elpida                       | 1        | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s             | 6        | 4.51%   |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 3        | 2.26%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s             | 3        | 2.26%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s             | 3        | 2.26%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s             | 3        | 2.26%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s             | 3        | 2.26%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s            | 3        | 2.26%   |
| Unknown RAM Module 4GB DIMM 400MT/s                             | 2        | 1.5%    |
| Unknown RAM Module 4096MB DIMM 400MT/s                          | 2        | 1.5%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                          | 2        | 1.5%    |
| Unknown RAM Module 2048MB DIMM 400MT/s                          | 2        | 1.5%    |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR2 1331MT/s            | 2        | 1.5%    |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s            | 2        | 1.5%    |
| Samsung RAM M378B5773DH0-CK0 2048MB DIMM DDR3 1600MT/s          | 2        | 1.5%    |
| M RAM Module 2048MB DIMM DDR3 667MT/s                           | 2        | 1.5%    |
| Kingston RAM XK2M26-MIE 16384MB DIMM DDR4 3467MT/s              | 2        | 1.5%    |
| Crucial RAM CB16GU2666.C8ET 16GB DIMM DDR4 2667MT/s             | 2        | 1.5%    |
| Unknown RAM Module 8192MB DIMM 1066MT/s                         | 1        | 0.75%   |
| Unknown RAM Module 512MB DIMM DDR 667MT/s                       | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                       | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                            | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM DDR2                             | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                         | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM SDRAM                               | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                         | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM 667MT/s                             | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM 400MT/s                             | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                    | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR2                             | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                         | 1        | 0.75%   |
| Unknown RAM Module 1GB DIMM SDRAM                               | 1        | 0.75%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                        | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                          | 1        | 0.75%   |
| Unknown (E) RAM Module 4096MB DIMM DDR3 667MT/s                 | 1        | 0.75%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 512MB DIMM DDR2 533MT/s | 1        | 0.75%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                   | 1        | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 38       | 42.7%   |
| DDR4    | 15       | 16.85%  |
| Unknown | 14       | 15.73%  |
| SDRAM   | 12       | 13.48%  |
| DDR2    | 8        | 8.99%   |
| DDR     | 2        | 2.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 79       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 34       | 34.34%  |
| 2048  | 30       | 30.3%   |
| 8192  | 19       | 19.19%  |
| 1024  | 8        | 8.08%   |
| 16384 | 6        | 6.06%   |
| 512   | 2        | 2.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 25       | 24.04%  |
| 1333    | 12       | 11.54%  |
| 667     | 9        | 8.65%   |
| 800     | 8        | 7.69%   |
| 400     | 7        | 6.73%   |
| 3200    | 4        | 3.85%   |
| 2400    | 4        | 3.85%   |
| 1867    | 4        | 3.85%   |
| 1866    | 4        | 3.85%   |
| 2667    | 3        | 2.88%   |
| 1066    | 3        | 2.88%   |
| Unknown | 3        | 2.88%   |
| 3600    | 2        | 1.92%   |
| 3467    | 2        | 1.92%   |
| 2133    | 2        | 1.92%   |
| 1331    | 2        | 1.92%   |
| 533     | 2        | 1.92%   |
| 49926   | 1        | 0.96%   |
| 3533    | 1        | 0.96%   |
| 3400    | 1        | 0.96%   |
| 3000    | 1        | 0.96%   |
| 2048    | 1        | 0.96%   |
| 2000    | 1        | 0.96%   |
| 1800    | 1        | 0.96%   |
| 1648    | 1        | 0.96%   |

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


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 3        | 27.27%  |
| Logitech Webcam C270                    | 2        | 18.18%  |
| Z-Star Vimicro USB Camera (Altair)      | 1        | 9.09%   |
| OPPO SM6375-QRD _SN:20E26CB1            | 1        | 9.09%   |
| eMPIA M035 Compact Web Cam              | 1        | 9.09%   |
| Cubeternet USB2.0 Camera                | 1        | 9.09%   |
| Cubeternet GL-UPC822 UVC WebCam         | 1        | 9.09%   |
| Chicony HP 720p HD Monitor Webcam       | 1        | 9.09%   |

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
| 0     | 121      | 82.31%  |
| 1     | 22       | 14.97%  |
| 2     | 3        | 2.04%   |
| 5     | 1        | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 14       | 46.67%  |
| Net/wireless             | 8        | 26.67%  |
| Camera                   | 2        | 6.67%   |
| Unassigned class         | 1        | 3.33%   |
| Storage/ide              | 1        | 3.33%   |
| Sound                    | 1        | 3.33%   |
| Multimedia controller    | 1        | 3.33%   |
| Modem                    | 1        | 3.33%   |
| Communication controller | 1        | 3.33%   |

