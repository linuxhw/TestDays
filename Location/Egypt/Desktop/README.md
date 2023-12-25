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

Total: 242

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | 18E7                        | [71f34bba13](https://linux-hardware.org/?probe=71f34bba13) | Dec 21, 2023 |
| Lenovo    | SHARKBAY 0B98401 PRO        | [f33ae0cc45](https://linux-hardware.org/?probe=f33ae0cc45) | Dec 14, 2023 |
| ASUSTek   | H61M-K                      | [15f1f8f029](https://linux-hardware.org/?probe=15f1f8f029) | Dec 13, 2023 |
| ASUSTek   | H61M-K                      | [d7a660dbef](https://linux-hardware.org/?probe=d7a660dbef) | Dec 13, 2023 |
| HP        | 1850                        | [903e4b5eb1](https://linux-hardware.org/?probe=903e4b5eb1) | Dec 11, 2023 |
| HP        | 3029h                       | [f7d6a9e2d4](https://linux-hardware.org/?probe=f7d6a9e2d4) | Dec 10, 2023 |
| HP        | 2215                        | [f29d88c563](https://linux-hardware.org/?probe=f29d88c563) | Dec 03, 2023 |
| ASUSTek   | PRIME X670-P                | [f7bf7a5dcc](https://linux-hardware.org/?probe=f7bf7a5dcc) | Dec 02, 2023 |
| ASUSTek   | PRIME H510M-K               | [cd95525dd4](https://linux-hardware.org/?probe=cd95525dd4) | Dec 01, 2023 |
| ASUSTek   | PRIME X670-P                | [2158fdddd7](https://linux-hardware.org/?probe=2158fdddd7) | Nov 14, 2023 |
| ASUSTek   | ROG STRIX X670E-E GAMING... | [a3eb4c9d76](https://linux-hardware.org/?probe=a3eb4c9d76) | Nov 04, 2023 |
| Dell      | 0TY915                      | [8ebe2fefc1](https://linux-hardware.org/?probe=8ebe2fefc1) | Oct 15, 2023 |
| Dell      | 0TY915                      | [736f520474](https://linux-hardware.org/?probe=736f520474) | Oct 15, 2023 |
| Dell      | 0WWJRX A00                  | [331ecd3ee8](https://linux-hardware.org/?probe=331ecd3ee8) | Oct 06, 2023 |
| Gigabyte  | H510M S2H                   | [75eb2afaca](https://linux-hardware.org/?probe=75eb2afaca) | Sep 09, 2023 |
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
| Ubuntu 20.04       | 19       | 11.05%  |
| OpenMandriva 4.3   | 13       | 7.56%   |
| Ubuntu 18.04       | 10       | 5.81%   |
| Zorin 16           | 9        | 5.23%   |
| OpenMandriva 4.2   | 7        | 4.07%   |
| OpenMandriva 23.01 | 7        | 4.07%   |
| Ubuntu 22.04       | 6        | 3.49%   |
| Arch Rolling       | 6        | 3.49%   |
| Fedora 39          | 4        | 2.33%   |
| ArcoLinux Rolling  | 4        | 2.33%   |
| ROSA R10           | 3        | 1.74%   |
| Linux Mint 20      | 3        | 1.74%   |
| BlackPanther 18.1  | 3        | 1.74%   |
| Ubuntu 21.10       | 2        | 1.16%   |
| Ubuntu 19.04       | 2        | 1.16%   |
| ROSA R9            | 2        | 1.16%   |
| ROSA R11           | 2        | 1.16%   |
| Pop!_OS 21.04      | 2        | 1.16%   |
| Pop!_OS 20.10      | 2        | 1.16%   |
| OpenMandriva 4.90  | 2        | 1.16%   |
| Manjaro            | 2        | 1.16%   |
| Linux Mint 21.1    | 2        | 1.16%   |
| Kali 2022.1        | 2        | 1.16%   |
| Fedora 35          | 2        | 1.16%   |
| Fedora 32          | 2        | 1.16%   |
| Fedora 30          | 2        | 1.16%   |
| Arch               | 2        | 1.16%   |
| Zorin 15           | 1        | 0.58%   |
| Xubuntu 20.04      | 1        | 0.58%   |
| Xubuntu 18.04      | 1        | 0.58%   |
| Xubuntu 16.04      | 1        | 0.58%   |
| Ultramarine 37     | 1        | 0.58%   |
| Ubuntu Unity 16.04 | 1        | 0.58%   |
| Ubuntu 23.10       | 1        | 0.58%   |
| Ubuntu 22.10       | 1        | 0.58%   |
| TUXEDO OS 22.04    | 1        | 0.58%   |
| ROSA R11.1         | 1        | 0.58%   |
| ROSA 12.2          | 1        | 0.58%   |
| RHEL 8             | 1        | 0.58%   |
| Reborn OS Rolling  | 1        | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 41       | 25.47%  |
| OpenMandriva | 29       | 18.01%  |
| Linux Mint   | 12       | 7.45%   |
| Fedora       | 12       | 7.45%   |
| Zorin        | 10       | 6.21%   |
| Arch         | 8        | 4.97%   |
| ROSA         | 7        | 4.35%   |
| Manjaro      | 6        | 3.73%   |
| Pop!_OS      | 5        | 3.11%   |
| ArcoLinux    | 5        | 3.11%   |
| Elementary   | 4        | 2.48%   |
| Xubuntu      | 3        | 1.86%   |
| Kali         | 3        | 1.86%   |
| Debian       | 3        | 1.86%   |
| BlackPanther | 3        | 1.86%   |
| Ultramarine  | 1        | 0.62%   |
| Ubuntu Unity | 1        | 0.62%   |
| TUXEDO OS    | 1        | 0.62%   |
| RHEL         | 1        | 0.62%   |
| Reborn OS    | 1        | 0.62%   |
| Parrot       | 1        | 0.62%   |
| LMDE         | 1        | 0.62%   |
| Linux Lite   | 1        | 0.62%   |
| KDE neon     | 1        | 0.62%   |
| Endless      | 1        | 0.62%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003        | 11       | 5.98%   |
| 5.10.14-desktop-1omv4002       | 7        | 3.8%    |
| 6.1.1-desktop-1omv2290         | 6        | 3.26%   |
| 5.4.0-42-generic               | 4        | 2.17%   |
| 5.15.0-48-generic              | 3        | 1.63%   |
| 5.11.0-37-generic              | 3        | 1.63%   |
| 6.6.2-desktop-1omv2390         | 2        | 1.09%   |
| 6.6.2-201.fc39.x86_64          | 2        | 1.09%   |
| 6.4.12-arch1-1                 | 2        | 1.09%   |
| 5.9.1-arch1-1                  | 2        | 1.09%   |
| 5.4.0-48-generic               | 2        | 1.09%   |
| 5.4.0-37-generic               | 2        | 1.09%   |
| 5.4.0-33-generic               | 2        | 1.09%   |
| 5.4.0-26-generic               | 2        | 1.09%   |
| 5.3.0-51-generic               | 2        | 1.09%   |
| 5.19.0-45-generic              | 2        | 1.09%   |
| 5.18.12-desktop-3omv4090       | 2        | 1.09%   |
| 5.16.13-desktop-1omv4003       | 2        | 1.09%   |
| 5.15.0-69-generic              | 2        | 1.09%   |
| 5.15.0-56-generic              | 2        | 1.09%   |
| 5.15.0-50-generic              | 2        | 1.09%   |
| 5.13.0-39-generic              | 2        | 1.09%   |
| 5.13.0-30-generic              | 2        | 1.09%   |
| 5.13.0-19-generic              | 2        | 1.09%   |
| 5.11.0-7620-generic            | 2        | 1.09%   |
| 4.18.16-desktop-1bP            | 2        | 1.09%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2        | 1.09%   |
| 4.15.0-55-generic              | 2        | 1.09%   |
| 4.15.0-46-generic              | 2        | 1.09%   |
| 6.6.5-arch1-1                  | 1        | 0.54%   |
| 6.6.0-cbrt1.0.fc39.x86_64      | 1        | 0.54%   |
| 6.5.6-300.fc39.x86_64          | 1        | 0.54%   |
| 6.5.5-arch1-1                  | 1        | 0.54%   |
| 6.5.0-13-generic               | 1        | 0.54%   |
| 6.4.8-desktop-2omv2390         | 1        | 0.54%   |
| 6.3.9-zen1-1-zen               | 1        | 0.54%   |
| 6.3.9-arch1-1                  | 1        | 0.54%   |
| 6.2.9-300.fc38.x86_64          | 1        | 0.54%   |
| 6.2.6-desktop-1omv2390         | 1        | 0.54%   |
| 6.1.7-200.fc37.x86_64          | 1        | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 22       | 12.64%  |
| 5.15.0  | 17       | 9.77%   |
| 5.16.7  | 11       | 6.32%   |
| 4.15.0  | 10       | 5.75%   |
| 5.13.0  | 9        | 5.17%   |
| 5.11.0  | 7        | 4.02%   |
| 5.10.14 | 7        | 4.02%   |
| 6.1.1   | 6        | 3.45%   |
| 5.3.0   | 5        | 2.87%   |
| 6.6.2   | 4        | 2.3%    |
| 5.19.0  | 4        | 2.3%    |
| 5.0.0   | 4        | 2.3%    |
| 5.8.0   | 3        | 1.72%   |
| 6.4.12  | 2        | 1.15%   |
| 6.3.9   | 2        | 1.15%   |
| 5.9.1   | 2        | 1.15%   |
| 5.18.12 | 2        | 1.15%   |
| 5.16.13 | 2        | 1.15%   |
| 5.16.0  | 2        | 1.15%   |
| 5.10.0  | 2        | 1.15%   |
| 4.9.60  | 2        | 1.15%   |
| 4.19.0  | 2        | 1.15%   |
| 4.18.16 | 2        | 1.15%   |
| 4.18.0  | 2        | 1.15%   |
| 6.6.5   | 1        | 0.57%   |
| 6.6.0   | 1        | 0.57%   |
| 6.5.6   | 1        | 0.57%   |
| 6.5.5   | 1        | 0.57%   |
| 6.5.0   | 1        | 0.57%   |
| 6.4.8   | 1        | 0.57%   |
| 6.2.9   | 1        | 0.57%   |
| 6.2.6   | 1        | 0.57%   |
| 6.1.7   | 1        | 0.57%   |
| 6.1.5   | 1        | 0.57%   |
| 6.1.4   | 1        | 0.57%   |
| 6.0.11  | 1        | 0.57%   |
| 5.9.0   | 1        | 0.57%   |
| 5.8.14  | 1        | 0.57%   |
| 5.7.7   | 1        | 0.57%   |
| 5.6.14  | 1        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 24       | 13.95%  |
| 5.15    | 19       | 11.05%  |
| 5.16    | 18       | 10.47%  |
| 5.10    | 13       | 7.56%   |
| 5.13    | 10       | 5.81%   |
| 4.15    | 10       | 5.81%   |
| 6.1     | 9        | 5.23%   |
| 5.11    | 8        | 4.65%   |
| 6.6     | 6        | 3.49%   |
| 5.3     | 6        | 3.49%   |
| 5.19    | 6        | 3.49%   |
| 4.9     | 5        | 2.91%   |
| 5.8     | 4        | 2.33%   |
| 5.0     | 4        | 2.33%   |
| 4.18    | 4        | 2.33%   |
| 6.5     | 3        | 1.74%   |
| 6.4     | 3        | 1.74%   |
| 5.9     | 3        | 1.74%   |
| 6.3     | 2        | 1.16%   |
| 6.2     | 2        | 1.16%   |
| 5.6     | 2        | 1.16%   |
| 5.18    | 2        | 1.16%   |
| 4.19    | 2        | 1.16%   |
| 6.0     | 1        | 0.58%   |
| 5.7     | 1        | 0.58%   |
| 5.5     | 1        | 0.58%   |
| 5.2     | 1        | 0.58%   |
| 5.17    | 1        | 0.58%   |
| 4.4     | 1        | 0.58%   |
| 4.13    | 1        | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 147      | 96.71%  |
| i686   | 5        | 3.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 66       | 41.77%  |
| KDE5            | 44       | 27.85%  |
| Unknown         | 14       | 8.86%   |
| X-Cinnamon      | 9        | 5.7%    |
| XFCE            | 7        | 4.43%   |
| KDE4            | 4        | 2.53%   |
| Pantheon        | 3        | 1.9%    |
| i3              | 2        | 1.27%   |
| Cinnamon        | 2        | 1.27%   |
| Unity           | 1        | 0.63%   |
| MATE            | 1        | 0.63%   |
| LXDE            | 1        | 0.63%   |
| KDE             | 1        | 0.63%   |
| GNOME Flashback | 1        | 0.63%   |
| GNOME Classic   | 1        | 0.63%   |
| Budgie          | 1        | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 123      | 78.85%  |
| Wayland | 25       | 16.03%  |
| Unknown | 6        | 3.85%   |
| Tty     | 2        | 1.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 69       | 44.23%  |
| SDDM    | 40       | 25.64%  |
| GDM3    | 17       | 10.9%   |
| GDM     | 14       | 8.97%   |
| LightDM | 7        | 4.49%   |
| TDM     | 5        | 3.21%   |
| KDM     | 4        | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 111      | 71.61%  |
| Unknown | 23       | 14.84%  |
| ar_EG   | 12       | 7.74%   |
| en_GB   | 6        | 3.87%   |
| C       | 3        | 1.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 107      | 70.39%  |
| EFI  | 45       | 29.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 108      | 66.67%  |
| Overlay | 26       | 16.05%  |
| Btrfs   | 10       | 6.17%   |
| Unknown | 6        | 3.7%    |
| Tmpfs   | 5        | 3.09%   |
| Xfs     | 4        | 2.47%   |
| Zfs     | 2        | 1.23%   |
| Ext2    | 1        | 0.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 72       | 46.75%  |
| GPT     | 43       | 27.92%  |
| MBR     | 39       | 25.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 78.06%  |
| Yes       | 34       | 21.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 52.23%  |
| Yes       | 75       | 47.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 51       | 33.77%  |
| Gigabyte Technology | 36       | 23.84%  |
| Dell                | 28       | 18.54%  |
| ASUSTek Computer    | 14       | 9.27%   |
| MSI                 | 6        | 3.97%   |
| Lenovo              | 5        | 3.31%   |
| Acer                | 3        | 1.99%   |
| Intel               | 2        | 1.32%   |
| Alienware           | 2        | 1.32%   |
| Pegatron            | 1        | 0.66%   |
| IBM                 | 1        | 0.66%   |
| ECS                 | 1        | 0.66%   |
| ASRock              | 1        | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte G41MT-S2PT                | 7        | 4.64%   |
| HP Compaq Pro 6305 SFF             | 4        | 2.65%   |
| Dell OptiPlex 780                  | 4        | 2.65%   |
| MSI MS-7C02                        | 3        | 1.99%   |
| HP ProDesk 600 G1 TWR              | 3        | 1.99%   |
| HP ProDesk 600 G1 SFF              | 3        | 1.99%   |
| HP Compaq 6005 Pro SFF PC          | 3        | 1.99%   |
| Gigabyte H61M-S2P                  | 3        | 1.99%   |
| Dell OptiPlex 760                  | 3        | 1.99%   |
| Dell OptiPlex 7020                 | 3        | 1.99%   |
| Dell OptiPlex 7010                 | 3        | 1.99%   |
| HP Z600 Workstation                | 2        | 1.32%   |
| HP EliteDesk 705 G1 SFF            | 2        | 1.32%   |
| HP Compaq Elite 8300 SFF           | 2        | 1.32%   |
| HP Compaq dc7800                   | 2        | 1.32%   |
| HP Compaq dc5850 Small Form Factor | 2        | 1.32%   |
| Gigabyte H61M-S2V-B3               | 2        | 1.32%   |
| Gigabyte H510M S2H                 | 2        | 1.32%   |
| Gigabyte G41MT-S2P                 | 2        | 1.32%   |
| ASUS H61M-K                        | 2        | 1.32%   |
| ASUS B250 MINING EXPERT            | 2        | 1.32%   |
| Alienware Aurora R12               | 2        | 1.32%   |
| Pegatron Pro 3010 Microtower PC    | 1        | 0.66%   |
| MSI MS-7C84                        | 1        | 0.66%   |
| MSI MS-7507                        | 1        | 0.66%   |
| MSI MS-7309                        | 1        | 0.66%   |
| Lenovo ThinkStation S30 4351D32    | 1        | 0.66%   |
| Lenovo ThinkCentre M93p 10A8000WUS | 1        | 0.66%   |
| Lenovo ThinkCentre M600 10KGS0J000 | 1        | 0.66%   |
| Lenovo ThinkCentre M58 6258D3G     | 1        | 0.66%   |
| Lenovo ThinkCentre M55p 8811Y4U    | 1        | 0.66%   |
| Intel E4610                        | 1        | 0.66%   |
| Intel DG31PR AAD97573-205          | 1        | 0.66%   |
| IBM 81713FG                        | 1        | 0.66%   |
| HP Z840 Workstation                | 1        | 0.66%   |
| HP Z820 Workstation                | 1        | 0.66%   |
| HP Z620 Workstation                | 1        | 0.66%   |
| HP Z240 Tower Workstation          | 1        | 0.66%   |
| HP Z230 SFF Workstation            | 1        | 0.66%   |
| HP xw4600 Workstation              | 1        | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Compaq            | 23       | 15.23%  |
| Dell OptiPlex        | 23       | 15.23%  |
| HP EliteDesk         | 8        | 5.3%    |
| HP ProDesk           | 7        | 4.64%   |
| Gigabyte G41MT-S2PT  | 7        | 4.64%   |
| Dell Precision       | 5        | 3.31%   |
| Lenovo ThinkCentre   | 4        | 2.65%   |
| MSI MS-7C02          | 3        | 1.99%   |
| Gigabyte H61M-S2P    | 3        | 1.99%   |
| ASUS TUF             | 3        | 1.99%   |
| HP Z600              | 2        | 1.32%   |
| Gigabyte H61M-S2V-B3 | 2        | 1.32%   |
| Gigabyte H510M       | 2        | 1.32%   |
| Gigabyte G41MT-S2P   | 2        | 1.32%   |
| ASUS ROG             | 2        | 1.32%   |
| ASUS PRIME           | 2        | 1.32%   |
| ASUS H61M-K          | 2        | 1.32%   |
| ASUS B250            | 2        | 1.32%   |
| Alienware Aurora     | 2        | 1.32%   |
| Acer Veriton         | 2        | 1.32%   |
| Pegatron Pro         | 1        | 0.66%   |
| MSI MS-7C84          | 1        | 0.66%   |
| MSI MS-7507          | 1        | 0.66%   |
| MSI MS-7309          | 1        | 0.66%   |
| Lenovo ThinkStation  | 1        | 0.66%   |
| Intel E4610          | 1        | 0.66%   |
| Intel DG31PR         | 1        | 0.66%   |
| IBM 81713FG          | 1        | 0.66%   |
| HP Z840              | 1        | 0.66%   |
| HP Z820              | 1        | 0.66%   |
| HP Z620              | 1        | 0.66%   |
| HP Z240              | 1        | 0.66%   |
| HP Z230              | 1        | 0.66%   |
| HP xw4600            | 1        | 0.66%   |
| HP rp5800            | 1        | 0.66%   |
| HP rp5700            | 1        | 0.66%   |
| HP 290               | 1        | 0.66%   |
| HP 280               | 1        | 0.66%   |
| HP 1850              | 1        | 0.66%   |
| Gigabyte Z97X-Gaming | 1        | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 18       | 11.92%  |
| 2011 | 17       | 11.26%  |
| 2012 | 16       | 10.6%   |
| 2009 | 15       | 9.93%   |
| 2008 | 13       | 8.61%   |
| 2014 | 11       | 7.28%   |
| 2018 | 9        | 5.96%   |
| 2007 | 9        | 5.96%   |
| 2010 | 8        | 5.3%    |
| 2021 | 7        | 4.64%   |
| 2019 | 5        | 3.31%   |
| 2017 | 5        | 3.31%   |
| 2016 | 5        | 3.31%   |
| 2015 | 3        | 1.99%   |
| 2006 | 3        | 1.99%   |
| 2005 | 3        | 1.99%   |
| 2022 | 2        | 1.32%   |
| 2020 | 2        | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 151      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 149      | 98.68%  |
| Enabled  | 2        | 1.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 151      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 39       | 25.66%  |
| 4.01-8.0    | 31       | 20.39%  |
| 8.01-16.0   | 31       | 20.39%  |
| 16.01-24.0  | 23       | 15.13%  |
| 32.01-64.0  | 8        | 5.26%   |
| 2.01-3.0    | 7        | 4.61%   |
| 1.01-2.0    | 5        | 3.29%   |
| 24.01-32.0  | 3        | 1.97%   |
| 64.01-256.0 | 3        | 1.97%   |
| 0.51-1.0    | 1        | 0.66%   |
| 0.01-0.5    | 1        | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 58       | 34.32%  |
| 2.01-3.0    | 47       | 27.81%  |
| 4.01-8.0    | 17       | 10.06%  |
| 3.01-4.0    | 16       | 9.47%   |
| 0.51-1.0    | 14       | 8.28%   |
| 0.01-0.5    | 8        | 4.73%   |
| 8.01-16.0   | 7        | 4.14%   |
| 64.01-256.0 | 1        | 0.59%   |
| 16.01-24.0  | 1        | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 73       | 46.2%   |
| 2       | 54       | 34.18%  |
| 3       | 19       | 12.03%  |
| 4       | 6        | 3.8%    |
| 9       | 2        | 1.27%   |
| 0       | 2        | 1.27%   |
| 5       | 1        | 0.63%   |
| Unknown | 1        | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 50.66%  |
| Yes       | 75       | 49.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 150      | 99.34%  |
| No        | 1        | 0.66%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 62.34%  |
| Yes       | 58       | 37.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 131      | 86.18%  |
| Yes       | 21       | 13.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Egypt   | 151      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Cairo                 | 87       | 53.37%  |
| Giza                  | 15       | 9.2%    |
| Alexandria            | 12       | 7.36%   |
| Al Mansurah           | 7        | 4.29%   |
| Tanta                 | 4        | 2.45%   |
| Port Said             | 3        | 1.84%   |
| Assiut                | 3        | 1.84%   |
| Zagazig               | 2        | 1.23%   |
| Suez                  | 2        | 1.23%   |
| Mohandessin           | 2        | 1.23%   |
| Minya                 | 2        | 1.23%   |
| Kafr ash Shaykh       | 2        | 1.23%   |
| Aswan                 | 2        | 1.23%   |
| Al Ma`adi             | 2        | 1.23%   |
| Zefta                 | 1        | 0.61%   |
| Tukh                  | 1        | 0.61%   |
| Sharqia               | 1        | 0.61%   |
| Sharm el Sheikh       | 1        | 0.61%   |
| New Cairo             | 1        | 0.61%   |
| Mallawi               | 1        | 0.61%   |
| Madinat an Nasr       | 1        | 0.61%   |
| Luxor                 | 1        | 0.61%   |
| Ismailia              | 1        | 0.61%   |
| Hurghada              | 1        | 0.61%   |
| Helwan                | 1        | 0.61%   |
| Faiyum                | 1        | 0.61%   |
| Bilbeis               | 1        | 0.61%   |
| Al Qalyubiyah         | 1        | 0.61%   |
| Al Qahirah al Jadidah | 1        | 0.61%   |
| Al Fayyum             | 1        | 0.61%   |
| Akhmim                | 1        | 0.61%   |
| 6th of October City   | 1        | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 82       | 130    | 35.19%  |
| Seagate                      | 58       | 85     | 24.89%  |
| Samsung Electronics          | 24       | 33     | 10.3%   |
| Kingston                     | 15       | 26     | 6.44%   |
| Toshiba                      | 10       | 12     | 4.29%   |
| Crucial                      | 8        | 12     | 3.43%   |
| Hitachi                      | 4        | 4      | 1.72%   |
| Hewlett-Packard              | 3        | 3      | 1.29%   |
| Sandisk                      | 2        | 2      | 0.86%   |
| LITEONIT                     | 2        | 2      | 0.86%   |
| Kingston Technology Company  | 2        | 3      | 0.86%   |
| KingSpec                     | 2        | 2      | 0.86%   |
| JMicron Technology           | 2        | 2      | 0.86%   |
| HS-SSD-E100                  | 2        | 2      | 0.86%   |
| ZOTAC                        | 1        | 1      | 0.43%   |
| TwinMOS                      | 1        | 1      | 0.43%   |
| Transcend                    | 1        | 1      | 0.43%   |
| SK hynix                     | 1        | 2      | 0.43%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.43%   |
| Phison Electronics           | 1        | 2      | 0.43%   |
| Micron/Crucial Technology    | 1        | 1      | 0.43%   |
| Maxtor                       | 1        | 2      | 0.43%   |
| MAXIO Technology (Hangzhou)  | 1        | 2      | 0.43%   |
| LITEON                       | 1        | 1      | 0.43%   |
| Lite-On Technology           | 1        | 1      | 0.43%   |
| Lexar                        | 1        | 1      | 0.43%   |
| Intel                        | 1        | 1      | 0.43%   |
| HS-SSD-C100                  | 1        | 1      | 0.43%   |
| Hikvision                    | 1        | 1      | 0.43%   |
| Fujitsu                      | 1        | 1      | 0.43%   |
| Apple                        | 1        | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 7        | 2.66%   |
| Seagate ST3500414CS 500GB        | 7        | 2.66%   |
| Seagate ST3500312CS 500GB        | 6        | 2.28%   |
| Toshiba DT01ACA050 500GB         | 5        | 1.9%    |
| Seagate ST3500413AS 500GB        | 4        | 1.52%   |
| Kingston SA400S37480G 480GB SSD  | 4        | 1.52%   |
| Kingston SA400S37240G 240GB SSD  | 4        | 1.52%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 3        | 1.14%   |
| WDC WD5000AAKX-001CA0 500GB      | 3        | 1.14%   |
| WDC WD5000AADS-00S9B0 500GB      | 3        | 1.14%   |
| WDC WD3200AAJS-00L7A0 320GB      | 3        | 1.14%   |
| WDC WD2500AAKX-75U6AA0 250GB     | 3        | 1.14%   |
| WDC WD1600AABS-00PRA0 160GB      | 3        | 1.14%   |
| WDC WD1600AABS-00H4A0 160GB      | 3        | 1.14%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 1.14%   |
| WDC WD10EZEX-00BN5A0 1TB         | 3        | 1.14%   |
| WDC WD10EARS-00Y5B1 1TB          | 3        | 1.14%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.14%   |
| Seagate ST3320311CS 320GB        | 3        | 1.14%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 1.14%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2        | 0.76%   |
| WDC WD800BD-22MRA1 80GB          | 2        | 0.76%   |
| WDC WD5000AVVS-63H0B1 500GB      | 2        | 0.76%   |
| WDC WD5000AVDS-63U7B1 500GB      | 2        | 0.76%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 2        | 0.76%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 2        | 0.76%   |
| WDC WD1600JS-61MHB1 160GB        | 2        | 0.76%   |
| WDC WD10EZEX-75WN4A1 1TB         | 2        | 0.76%   |
| WDC WD10EZEX-22MFCA0 1TB         | 2        | 0.76%   |
| Seagate ST500DM002-1SB10A 500GB  | 2        | 0.76%   |
| Seagate ST380815AS 80GB          | 2        | 0.76%   |
| Seagate ST3250318AS 250GB        | 2        | 0.76%   |
| Seagate ST3160815AS 160GB        | 2        | 0.76%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 0.76%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 0.76%   |
| Seagate ST1000VM002-1CT162 1TB   | 2        | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 0.76%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 0.76%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.76%   |
| Samsung PM9A1 NVMe 256GB         | 2        | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 78       | 125    | 48.45%  |
| Seagate             | 58       | 85     | 36.02%  |
| Toshiba             | 9        | 11     | 5.59%   |
| Samsung Electronics | 8        | 11     | 4.97%   |
| Hitachi             | 4        | 4      | 2.48%   |
| Maxtor              | 1        | 2      | 0.62%   |
| Hewlett-Packard     | 1        | 1      | 0.62%   |
| Fujitsu             | 1        | 1      | 0.62%   |
| Apple               | 1        | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 15       | 25     | 27.27%  |
| Samsung Electronics | 11       | 11     | 20%     |
| Crucial             | 8        | 12     | 14.55%  |
| WDC                 | 5        | 5      | 9.09%   |
| LITEONIT            | 2        | 2      | 3.64%   |
| KingSpec            | 2        | 2      | 3.64%   |
| JMicron Technology  | 2        | 2      | 3.64%   |
| ZOTAC               | 1        | 1      | 1.82%   |
| TwinMOS             | 1        | 1      | 1.82%   |
| Transcend           | 1        | 1      | 1.82%   |
| Toshiba             | 1        | 1      | 1.82%   |
| SanDisk             | 1        | 1      | 1.82%   |
| LITEON              | 1        | 1      | 1.82%   |
| Lexar               | 1        | 1      | 1.82%   |
| Intel               | 1        | 1      | 1.82%   |
| Hikvision           | 1        | 1      | 1.82%   |
| Hewlett-Packard     | 1        | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 137      | 241    | 67.82%  |
| SSD     | 47       | 69     | 23.27%  |
| NVMe    | 15       | 26     | 7.43%   |
| Unknown | 3        | 3      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 144      | 309    | 88.89%  |
| NVMe | 15       | 26     | 9.26%   |
| SAS  | 3        | 4      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 124      | 229    | 69.27%  |
| 0.51-1.0   | 41       | 56     | 22.91%  |
| 1.01-2.0   | 11       | 15     | 6.15%   |
| 3.01-4.0   | 2        | 4      | 1.12%   |
| 4.01-10.0  | 1        | 6      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 38       | 22.75%  |
| 251-500        | 34       | 20.36%  |
| 51-100         | 21       | 12.57%  |
| 1-20           | 19       | 11.38%  |
| 501-1000       | 18       | 10.78%  |
| 21-50          | 14       | 8.38%   |
| 1001-2000      | 9        | 5.39%   |
| More than 3000 | 6        | 3.59%   |
| Unknown        | 5        | 2.99%   |
| 2001-3000      | 3        | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 68       | 41.21%  |
| 101-250        | 28       | 16.97%  |
| 21-50          | 21       | 12.73%  |
| 251-500        | 16       | 9.7%    |
| 51-100         | 11       | 6.67%   |
| 501-1000       | 9        | 5.45%   |
| Unknown        | 5        | 3.03%   |
| 2001-3000      | 3        | 1.82%   |
| More than 3000 | 2        | 1.21%   |
| 1001-2000      | 2        | 1.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63H0B1 500GB                      | 2        | 2      | 4%      |
| WDC WD5000AVDS-63U7B1 500GB                      | 2        | 2      | 4%      |
| WDC WD5000AAKX-00ERMA0 500GB                     | 2        | 3      | 4%      |
| WDC WD1600AABS-00H4A0 160GB                      | 2        | 2      | 4%      |
| Seagate ST380815AS 80GB                          | 2        | 2      | 4%      |
| Seagate ST3500413AS 500GB                        | 2        | 3      | 4%      |
| Seagate ST3500312CS 500GB                        | 2        | 2      | 4%      |
| WDC WD800JD-60LSA5 80GB                          | 1        | 1      | 2%      |
| WDC WD800BD-22MRA1 80GB                          | 1        | 1      | 2%      |
| WDC WD5000AAVS-22G9B1 500GB                      | 1        | 1      | 2%      |
| WDC WD5000AAKX-75U6AA0 500GB                     | 1        | 2      | 2%      |
| WDC WD5000AAKX-08U6AA0 500GB                     | 1        | 2      | 2%      |
| WDC WD5000AAKX-009FA0 500GB                      | 1        | 1      | 2%      |
| WDC WD5000AAKS-00V6A0 500GB                      | 1        | 1      | 2%      |
| WDC WD5000AADS-00S9B0 500GB                      | 1        | 1      | 2%      |
| WDC WD5000AADS-00M2B0 500GB                      | 1        | 1      | 2%      |
| WDC WD3200AAJS-56M0A0 320GB                      | 1        | 1      | 2%      |
| WDC WD3200AAJS-56B4A0 320GB                      | 1        | 2      | 2%      |
| WDC WD3200AAJS-00L7A0 320GB                      | 1        | 1      | 2%      |
| WDC WD3200AAJS-00B4A0 320GB                      | 1        | 1      | 2%      |
| WDC WD3200A 320GB                                | 1        | 1      | 2%      |
| WDC WD2500AAJS-00VTA0 250GB                      | 1        | 1      | 2%      |
| WDC WD1600AVVS-63L2B0 160GB                      | 1        | 1      | 2%      |
| WDC WD1600AAJS-00L7A0 160GB                      | 1        | 1      | 2%      |
| WDC WD10EZEX-08M2NA0 1TB                         | 1        | 1      | 2%      |
| WDC WD10EZEX-00BN5A0 1TB                         | 1        | 1      | 2%      |
| WDC WD10EARS-00Y5B1 1TB                          | 1        | 1      | 2%      |
| Toshiba MQ01ABF050 500GB                         | 1        | 2      | 2%      |
| Seagate ST500DM002-1SB10A 500GB                  | 1        | 1      | 2%      |
| Seagate ST500DM002-1BD142 500GB                  | 1        | 3      | 2%      |
| Seagate ST3320613AS 320GB                        | 1        | 1      | 2%      |
| Seagate ST3320311CS 320GB                        | 1        | 1      | 2%      |
| Seagate ST3160211AS 160GB                        | 1        | 2      | 2%      |
| Seagate ST250DM000-1BD141 250GB                  | 1        | 2      | 2%      |
| Seagate ST2000DM008-2FR102 2TB                   | 1        | 2      | 2%      |
| Seagate ST2000DM001-1ER164 2TB                   | 1        | 1      | 2%      |
| Seagate ST1000DM003-1CH162 1TB                   | 1        | 1      | 2%      |
| Samsung Electronics SSD 870 EVO 500GB            | 1        | 1      | 2%      |
| Samsung Electronics MZ7TD128HAFV-000L1 128GB SSD | 1        | 1      | 2%      |
| Samsung Electronics HD256GJ 250GB                | 1        | 1      | 2%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 32     | 54.55%  |
| Seagate             | 13       | 21     | 29.55%  |
| Samsung Electronics | 3        | 3      | 6.82%   |
| Toshiba             | 1        | 2      | 2.27%   |
| Kingston            | 1        | 2      | 2.27%   |
| Intel               | 1        | 1      | 2.27%   |
| Hewlett-Packard     | 1        | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 32     | 60%     |
| Seagate             | 13       | 21     | 32.5%   |
| Toshiba             | 1        | 2      | 2.5%    |
| Samsung Electronics | 1        | 1      | 2.5%    |
| Hewlett-Packard     | 1        | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 38       | 57     | 90.48%  |
| SSD  | 4        | 5      | 9.52%   |

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
| Detected | 83       | 170    | 47.43%  |
| Works    | 48       | 103    | 27.43%  |
| Malfunc  | 41       | 62     | 23.43%  |
| Failed   | 3        | 4      | 1.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 113      | 65.32%  |
| AMD                          | 35       | 20.23%  |
| Samsung Electronics          | 7        | 4.05%   |
| Kingston Technology Company  | 3        | 1.73%   |
| Marvell Technology Group     | 2        | 1.16%   |
| Broadcom / LSI               | 2        | 1.16%   |
| SK hynix                     | 1        | 0.58%   |
| Shenzhen Longsys Electronics | 1        | 0.58%   |
| SanDisk                      | 1        | 0.58%   |
| Phison Electronics           | 1        | 0.58%   |
| Nvidia                       | 1        | 0.58%   |
| Micron/Crucial Technology    | 1        | 0.58%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.58%   |
| LSI Logic / Symbios Logic    | 1        | 0.58%   |
| Lite-On Technology           | 1        | 0.58%   |
| JMicron Technology           | 1        | 0.58%   |
| INNOGRIT                     | 1        | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18       | 7.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 17       | 7.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 6.49%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 3.9%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 3.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 3.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 2.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 2.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 1.73%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.73%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 4        | 1.73%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 4        | 1.73%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.73%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 1.73%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.3%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 1.3%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 1.3%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 1.3%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.3%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.87%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.87%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.87%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.87%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 2        | 0.87%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.87%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 93       | 50.82%  |
| IDE  | 57       | 31.15%  |
| NVMe | 15       | 8.2%    |
| RAID | 13       | 7.1%    |
| SAS  | 4        | 2.19%   |
| SCSI | 1        | 0.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 116      | 76.82%  |
| AMD    | 35       | 23.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz         | 6        | 3.95%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 5        | 3.29%   |
| Intel Core i5-4590 CPU @ 3.30GHz             | 5        | 3.29%   |
| Intel Core i5-4570 CPU @ 3.20GHz             | 5        | 3.29%   |
| Intel Core i5-2400 CPU @ 3.10GHz             | 4        | 2.63%   |
| Intel Pentium D CPU 3.00GHz                  | 3        | 1.97%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 3        | 1.97%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz         | 3        | 1.97%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 3        | 1.97%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz         | 3        | 1.97%   |
| Intel Core 2 CPU 6600 @ 2.40GHz              | 3        | 1.97%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz      | 3        | 1.97%   |
| AMD A4-5300B APU with Radeon HD Graphics     | 3        | 1.97%   |
| Intel Pentium CPU G2030 @ 3.00GHz            | 2        | 1.32%   |
| Intel Pentium 4 CPU 3.20GHz                  | 2        | 1.32%   |
| Intel Core i7-6700 CPU @ 3.40GHz             | 2        | 1.32%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 2        | 1.32%   |
| Intel Core i5-3570 CPU @ 3.40GHz             | 2        | 1.32%   |
| Intel Core i3-3220 CPU @ 3.30GHz             | 2        | 1.32%   |
| Intel Core i3-2120 CPU @ 3.30GHz             | 2        | 1.32%   |
| Intel Core i3-2100 CPU @ 3.10GHz             | 2        | 1.32%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz         | 2        | 1.32%   |
| Intel Core 2 Duo CPU E4400 @ 2.00GHz         | 2        | 1.32%   |
| Intel Celeron D CPU 3.06GHz                  | 2        | 1.32%   |
| AMD Ryzen 7 3700X 8-Core Processor           | 2        | 1.32%   |
| AMD Ryzen 5 2600 Six-Core Processor          | 2        | 1.32%   |
| AMD Phenom II X4 B95 Processor               | 2        | 1.32%   |
| AMD A8-5500B APU with Radeon HD Graphics     | 2        | 1.32%   |
| AMD A10 PRO-7800B R7, 12 Compute Cores 4C+8G | 2        | 1.32%   |
| Intel Xeon CPU X5650 @ 2.67GHz               | 1        | 0.66%   |
| Intel Xeon CPU W3550 @ 3.07GHz               | 1        | 0.66%   |
| Intel Xeon CPU E5640 @ 2.67GHz               | 1        | 0.66%   |
| Intel Xeon CPU E5620 @ 2.40GHz               | 1        | 0.66%   |
| Intel Xeon CPU E5450 @ 3.00GHz               | 1        | 0.66%   |
| Intel Xeon CPU E5-2690 v2 @ 3.00GHz          | 1        | 0.66%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz          | 1        | 0.66%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz           | 1        | 0.66%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz          | 1        | 0.66%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz          | 1        | 0.66%   |
| Intel Xeon CPU 3.20GHz                       | 1        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 31       | 20.39%  |
| Intel Core 2 Duo        | 21       | 13.82%  |
| Intel Core i7           | 15       | 9.87%   |
| Intel Xeon              | 11       | 7.24%   |
| Intel Core i3           | 10       | 6.58%   |
| AMD Ryzen 5             | 6        | 3.95%   |
| Other                   | 5        | 3.29%   |
| Intel Core 2            | 5        | 3.29%   |
| Intel Core 2 Quad       | 4        | 2.63%   |
| AMD Ryzen 7             | 4        | 2.63%   |
| AMD A4                  | 4        | 2.63%   |
| Intel Pentium D         | 3        | 1.97%   |
| Intel Pentium 4         | 3        | 1.97%   |
| Intel Pentium           | 3        | 1.97%   |
| AMD A8                  | 3        | 1.97%   |
| Intel Pentium Dual-Core | 2        | 1.32%   |
| Intel Celeron D         | 2        | 1.32%   |
| Intel Celeron           | 2        | 1.32%   |
| AMD Ryzen 9             | 2        | 1.32%   |
| AMD Phenom II X4        | 2        | 1.32%   |
| AMD Phenom              | 2        | 1.32%   |
| AMD Athlon II X2        | 2        | 1.32%   |
| AMD A10                 | 2        | 1.32%   |
| AMD Sempron             | 1        | 0.66%   |
| AMD PRO A10             | 1        | 0.66%   |
| AMD FX                  | 1        | 0.66%   |
| AMD Athlon II X3        | 1        | 0.66%   |
| AMD Athlon Dual Core    | 1        | 0.66%   |
| AMD Athlon 64 X2        | 1        | 0.66%   |
| AMD Athlon 64           | 1        | 0.66%   |
| AMD A6                  | 1        | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 56       | 36.84%  |
| 4      | 50       | 32.89%  |
| 1      | 13       | 8.55%   |
| 8      | 12       | 7.89%   |
| 6      | 12       | 7.89%   |
| 3      | 3        | 1.97%   |
| 16     | 2        | 1.32%   |
| 12     | 2        | 1.32%   |
| 24     | 1        | 0.66%   |
| 10     | 1        | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 144      | 95.36%  |
| 2      | 7        | 4.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 56.86%  |
| 2      | 66       | 43.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 149      | 98.03%  |
| 32-bit         | 2        | 1.32%   |
| Unknown        | 1        | 0.66%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 43       | 27.04%  |
| 0x306c3    | 15       | 9.43%   |
| 0x1067a    | 15       | 9.43%   |
| 0x306a9    | 8        | 5.03%   |
| 0x206a7    | 8        | 5.03%   |
| 0x6fb      | 5        | 3.14%   |
| 0xf65      | 4        | 2.52%   |
| 0x06001119 | 4        | 2.52%   |
| 0xa0671    | 3        | 1.89%   |
| 0x906ea    | 3        | 1.89%   |
| 0x6fd      | 3        | 1.89%   |
| 0x506e3    | 3        | 1.89%   |
| 0x206c2    | 3        | 1.89%   |
| 0x0800820d | 3        | 1.89%   |
| 0x010000c8 | 3        | 1.89%   |
| 0xf41      | 2        | 1.26%   |
| 0x906e9    | 2        | 1.26%   |
| 0x6f6      | 2        | 1.26%   |
| 0x306e4    | 2        | 1.26%   |
| 0x106a5    | 2        | 1.26%   |
| 0x10676    | 2        | 1.26%   |
| 0x01000095 | 2        | 1.26%   |
| 0xf64      | 1        | 0.63%   |
| 0xf43      | 1        | 0.63%   |
| 0x906ed    | 1        | 0.63%   |
| 0x6f2      | 1        | 0.63%   |
| 0x406c4    | 1        | 0.63%   |
| 0x306f2    | 1        | 0.63%   |
| 0x206d7    | 1        | 0.63%   |
| 0x20655    | 1        | 0.63%   |
| 0x20652    | 1        | 0.63%   |
| 0x106e5    | 1        | 0.63%   |
| 0x0a601206 | 1        | 0.63%   |
| 0x0a601203 | 1        | 0.63%   |
| 0x0a201009 | 1        | 0.63%   |
| 0x08701021 | 1        | 0.63%   |
| 0x08701013 | 1        | 0.63%   |
| 0x08701012 | 1        | 0.63%   |
| 0x08008204 | 1        | 0.63%   |
| 0x06003106 | 1        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 22       | 14.38%  |
| Penryn      | 19       | 12.42%  |
| Core        | 14       | 9.15%   |
| IvyBridge   | 12       | 7.84%   |
| SandyBridge | 11       | 7.19%   |
| NetBurst    | 10       | 6.54%   |
| KabyLake    | 9        | 5.88%   |
| K10         | 8        | 5.23%   |
| Piledriver  | 7        | 4.58%   |
| Westmere    | 5        | 3.27%   |
| Unknown     | 5        | 3.27%   |
| Zen+        | 4        | 2.61%   |
| Zen 2       | 4        | 2.61%   |
| Skylake     | 4        | 2.61%   |
| Steamroller | 3        | 1.96%   |
| Nehalem     | 3        | 1.96%   |
| K8 Hammer   | 3        | 1.96%   |
| Icelake     | 3        | 1.96%   |
| Zen 3       | 2        | 1.31%   |
| CometLake   | 2        | 1.31%   |
| Silvermont  | 1        | 0.65%   |
| Excavator   | 1        | 0.65%   |
| Bulldozer   | 1        | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 74       | 45.4%   |
| Nvidia | 46       | 28.22%  |
| AMD    | 43       | 26.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 18       | 10.71%  |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 15       | 8.93%   |
| Nvidia GT218 [GeForce 210]                                                  | 8        | 4.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 4.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 4.17%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 5        | 2.98%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 2.38%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.79%   |
| Nvidia GF119 [NVS 315]                                                      | 3        | 1.79%   |
| Nvidia GF108GL [Quadro 600]                                                 | 3        | 1.79%   |
| Intel HD Graphics 630                                                       | 3        | 1.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.79%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 3        | 1.79%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.79%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 1.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.79%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 3        | 1.79%   |
| AMD RS880 [Radeon HD 4200]                                                  | 3        | 1.79%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 3        | 1.79%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.19%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 2        | 1.19%   |
| Nvidia AD104 [GeForce RTX 4070]                                             | 2        | 1.19%   |
| Intel HD Graphics 530                                                       | 2        | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.19%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1.19%   |
| AMD Trinity [Radeon HD 7560D]                                               | 2        | 1.19%   |
| AMD RS780C [Radeon 3100]                                                    | 2        | 1.19%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2        | 1.19%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.6%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.6%    |
| Nvidia NV18 [GeForce4 MX 4000]                                              | 1        | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.6%    |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.6%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.6%    |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.6%    |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.6%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.6%    |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| 1 x Intel              | 63       | 40.65%  |
| 1 x Nvidia             | 41       | 26.45%  |
| 1 x AMD                | 35       | 22.58%  |
| Intel + Nvidia         | 4        | 2.58%   |
| Intel + AMD            | 4        | 2.58%   |
| 2 x Intel              | 2        | 1.29%   |
| AMD + Nvidia           | 2        | 1.29%   |
| 3 x AMD                | 1        | 0.65%   |
| 2 x Nvidia             | 1        | 0.65%   |
| 2 x AMD                | 1        | 0.65%   |
| 1 x Intel + 3 x Nvidia | 1        | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 119      | 75.8%   |
| Proprietary | 25       | 15.92%  |
| Unknown     | 13       | 8.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 81       | 51.59%  |
| 0.51-1.0   | 21       | 13.38%  |
| 0.01-0.5   | 20       | 12.74%  |
| 1.01-2.0   | 14       | 8.92%   |
| 7.01-8.0   | 9        | 5.73%   |
| 3.01-4.0   | 7        | 4.46%   |
| 8.01-16.0  | 5        | 3.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 30       | 23.62%  |
| Dell                    | 26       | 20.47%  |
| Hewlett-Packard         | 21       | 16.54%  |
| Lenovo                  | 8        | 6.3%    |
| Goldstar                | 7        | 5.51%   |
| Philips                 | 3        | 2.36%   |
| NEC Computers           | 3        | 2.36%   |
| BenQ                    | 3        | 2.36%   |
| ASUSTek Computer        | 3        | 2.36%   |
| AOC                     | 3        | 2.36%   |
| Acer                    | 3        | 2.36%   |
| Fujitsu Siemens         | 2        | 1.57%   |
| Eizo                    | 2        | 1.57%   |
| ViewSonic               | 1        | 0.79%   |
| Unknown                 | 1        | 0.79%   |
| Sun                     | 1        | 0.79%   |
| Sony                    | 1        | 0.79%   |
| Planar                  | 1        | 0.79%   |
| MStar                   | 1        | 0.79%   |
| MLT                     | 1        | 0.79%   |
| JWY                     | 1        | 0.79%   |
| Gigabyte Technology     | 1        | 0.79%   |
| eMachines               | 1        | 0.79%   |
| Chi Mei Optoelectronics | 1        | 0.79%   |
| AUS                     | 1        | 0.79%   |
| Ancor Communications    | 1        | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                     | 5        | 3.76%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch     | 3        | 2.26%   |
| Lenovo LEN T2454pA LEN60C9 1920x1080 518x324mm 24.1-inch             | 3        | 2.26%   |
| Hewlett-Packard L1950 HWP26E7 1280x1024 380x300mm 19.1-inch          | 3        | 2.26%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 2        | 1.5%    |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch  | 2        | 1.5%    |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 2        | 1.5%    |
| Hewlett-Packard LA2206 HWP2948 1920x1080 476x268mm 21.5-inch         | 2        | 1.5%    |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch         | 2        | 1.5%    |
| Hewlett-Packard LA2006 HWP2943 1600x900 443x249mm 20.0-inch          | 2        | 1.5%    |
| Dell P2211H DEL4060 1920x1080 477x268mm 21.5-inch                    | 2        | 1.5%    |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                     | 2        | 1.5%    |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch        | 1        | 0.75%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                 | 1        | 0.75%   |
| Sun PN17JO SUN0589 1280x1024 295x236mm 14.9-inch                     | 1        | 0.75%   |
| Sony KDL-23S2000 SNY9900 1360x768                                    | 1        | 0.75%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM0590 1600x900 443x249mm 20.0-inch  | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch  | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch | 1        | 0.75%   |
| Samsung Electronics SMBX2031 SAM076A 1600x900 443x249mm 20.0-inch    | 1        | 0.75%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch    | 1        | 0.75%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1        | 0.75%   |
| Samsung Electronics S23B300 SAM08AE 1920x1080 510x287mm 23.0-inch    | 1        | 0.75%   |
| Samsung Electronics S22E200 SAM0C6D 1920x1080 477x268mm 21.5-inch    | 1        | 0.75%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1        | 0.75%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 1        | 0.75%   |
| Samsung Electronics S19B300 SAM08A4 1366x768 410x230mm 18.5-inch     | 1        | 0.75%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch    | 1        | 0.75%   |
| Samsung Electronics LCD Monitor SMBX2350 1920x1080                   | 1        | 0.75%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                   | 1        | 0.75%   |
| Samsung Electronics LCD Monitor SA300/SA350 1366x768                 | 1        | 0.75%   |
| Samsung Electronics LCD Monitor S24D330 1920x1080                    | 1        | 0.75%   |
| Samsung Electronics LCD Monitor S22D300 5760x1080                    | 1        | 0.75%   |
| Samsung Electronics LCD Monitor S22D300 1920x1080                    | 1        | 0.75%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch   | 1        | 0.75%   |
| Samsung Electronics C24FG7x SAM0E43 1920x1080 532x304mm 24.1-inch    | 1        | 0.75%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1        | 0.75%   |
| Planar PE2010 PLN2010 1400x1050 400x300mm 19.7-inch                  | 1        | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 45       | 36%     |
| 1280x1024 (SXGA)   | 23       | 18.4%   |
| 1366x768 (WXGA)    | 12       | 9.6%    |
| 1440x900 (WXGA+)   | 11       | 8.8%    |
| 1600x900 (HD+)     | 8        | 6.4%    |
| 1680x1050 (WSXGA+) | 7        | 5.6%    |
| 3840x2160 (4K)     | 4        | 3.2%    |
| 2560x1440 (QHD)    | 3        | 2.4%    |
| 1600x1200          | 2        | 1.6%    |
| 5760x1080          | 1        | 0.8%    |
| 3440x1440          | 1        | 0.8%    |
| 2560x1600          | 1        | 0.8%    |
| 1920x540           | 1        | 0.8%    |
| 1920x1200 (WUXGA)  | 1        | 0.8%    |
| 1400x1050          | 1        | 0.8%    |
| 1360x768           | 1        | 0.8%    |
| 1280x720 (HD)      | 1        | 0.8%    |
| 1024x768 (XGA)     | 1        | 0.8%    |
| Unknown            | 1        | 0.8%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 18       | 14.29%  |
| 19      | 16       | 12.7%   |
| 24      | 13       | 10.32%  |
| 21      | 12       | 9.52%   |
| 27      | 10       | 7.94%   |
| 18      | 10       | 7.94%   |
| Unknown | 10       | 7.94%   |
| 20      | 9        | 7.14%   |
| 23      | 7        | 5.56%   |
| 22      | 6        | 4.76%   |
| 15      | 4        | 3.17%   |
| 32      | 3        | 2.38%   |
| 31      | 2        | 1.59%   |
| 54      | 1        | 0.79%   |
| 34      | 1        | 0.79%   |
| 29      | 1        | 0.79%   |
| 25      | 1        | 0.79%   |
| 16      | 1        | 0.79%   |
| 14      | 1        | 0.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 46       | 36.8%   |
| 501-600     | 28       | 22.4%   |
| 301-350     | 17       | 13.6%   |
| 351-400     | 13       | 10.4%   |
| Unknown     | 10       | 8%      |
| 601-700     | 5        | 4%      |
| 701-800     | 4        | 3.2%    |
| 201-300     | 1        | 0.8%    |
| 1001-1500   | 1        | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 63       | 51.22%  |
| 16/10   | 23       | 18.7%   |
| 5/4     | 20       | 16.26%  |
| Unknown | 9        | 7.32%   |
| 4/3     | 7        | 5.69%   |
| 21/9    | 1        | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 31       | 24.8%   |
| 201-250        | 27       | 21.6%   |
| 141-150        | 22       | 17.6%   |
| 301-350        | 10       | 8%      |
| Unknown        | 10       | 8%      |
| 351-500        | 7        | 5.6%    |
| 251-300        | 7        | 5.6%    |
| 131-140        | 4        | 3.2%    |
| 101-110        | 3        | 2.4%    |
| 111-120        | 2        | 1.6%    |
| More than 1000 | 1        | 0.8%    |
| 121-130        | 1        | 0.8%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 88       | 72.13%  |
| 101-120 | 19       | 15.57%  |
| Unknown | 10       | 8.2%    |
| 121-160 | 3        | 2.46%   |
| 1-50    | 2        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 130      | 81.76%  |
| 0     | 17       | 10.69%  |
| 2     | 12       | 7.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 65       | 30.81%  |
| Intel                             | 65       | 30.81%  |
| Qualcomm Atheros                  | 17       | 8.06%   |
| Broadcom                          | 17       | 8.06%   |
| Ralink Technology                 | 15       | 7.11%   |
| Broadcom Limited                  | 10       | 4.74%   |
| TP-Link                           | 5        | 2.37%   |
| Qualcomm Atheros Communications   | 4        | 1.9%    |
| Samsung Electronics               | 2        | 0.95%   |
| Ralink                            | 2        | 0.95%   |
| Edimax Technology                 | 2        | 0.95%   |
| Sundance Technology Inc / IC Plus | 1        | 0.47%   |
| Qualcomm                          | 1        | 0.47%   |
| Nvidia                            | 1        | 0.47%   |
| Motorola                          | 1        | 0.47%   |
| Lenovo                            | 1        | 0.47%   |
| D-Link                            | 1        | 0.47%   |
| 3Com                              | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 39       | 17.26%  |
| Intel Ethernet Connection I217-LM                                             | 14       | 6.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13       | 5.75%   |
| Ralink RT5370 Wireless Adapter                                                | 11       | 4.87%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 9        | 3.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 8        | 3.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 8        | 3.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 7        | 3.1%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 6        | 2.65%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                      | 6        | 2.65%   |
| Ralink MT7601U Wireless Adapter                                               | 5        | 2.21%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4        | 1.77%   |
| Intel I211 Gigabit Network Connection                                         | 4        | 1.77%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 4        | 1.77%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 4        | 1.77%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 3        | 1.33%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 3        | 1.33%   |
| Intel 82566DM Gigabit Network Connection                                      | 3        | 1.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 0.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.88%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 0.88%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2        | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 0.88%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 2        | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 0.88%   |
| Intel 82578DM Gigabit Network Connection                                      | 2        | 0.88%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 0.88%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2        | 0.88%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.88%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 2        | 0.88%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express               | 2        | 0.88%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.44%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 0.44%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.44%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 22       | 34.92%  |
| Ralink Technology               | 15       | 23.81%  |
| Intel                           | 8        | 12.7%   |
| TP-Link                         | 5        | 7.94%   |
| Qualcomm Atheros Communications | 4        | 6.35%   |
| Qualcomm Atheros                | 4        | 6.35%   |
| Ralink                          | 2        | 3.17%   |
| Edimax Technology               | 2        | 3.17%   |
| D-Link                          | 1        | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Ralink RT5370 Wireless Adapter                                                | 11       | 17.19%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 8        | 12.5%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 7        | 10.94%  |
| Ralink MT7601U Wireless Adapter                                               | 5        | 7.81%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 3        | 4.69%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 3        | 4.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 3.13%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 3.13%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2        | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 3.13%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 3.13%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2        | 3.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 1.56%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 1.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 1.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 1.56%   |
| Realtek RTL8187 Wireless Adapter                                              | 1        | 1.56%   |
| Realtek 802.11ac NIC                                                          | 1        | 1.56%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 1.56%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 1        | 1.56%   |
| Intel Wireless-AC 9260                                                        | 1        | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 1.56%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 1.56%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]          | 1        | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 60       | 38.46%  |
| Realtek Semiconductor             | 49       | 31.41%  |
| Broadcom                          | 17       | 10.9%   |
| Qualcomm Atheros                  | 14       | 8.97%   |
| Broadcom Limited                  | 10       | 6.41%   |
| Sundance Technology Inc / IC Plus | 1        | 0.64%   |
| Samsung Electronics               | 1        | 0.64%   |
| Qualcomm                          | 1        | 0.64%   |
| Nvidia                            | 1        | 0.64%   |
| Lenovo                            | 1        | 0.64%   |
| 3Com                              | 1        | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 39       | 24.38%  |
| Intel Ethernet Connection I217-LM                                          | 14       | 8.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 13       | 8.13%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 9        | 5.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 8        | 5%      |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 6        | 3.75%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 6        | 3.75%   |
| Realtek RTL8125 2.5GbE Controller                                          | 4        | 2.5%    |
| Intel I211 Gigabit Network Connection                                      | 4        | 2.5%    |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 2.5%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                           | 4        | 2.5%    |
| Intel 82566DM Gigabit Network Connection                                   | 3        | 1.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 1.25%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 2        | 1.25%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1.25%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 2        | 1.25%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 1.25%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 1.25%   |
| Intel 82574L Gigabit Network Connection                                    | 2        | 1.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2        | 1.25%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 1.25%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express            | 2        | 1.25%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 0.63%   |
| Qualcomm Redmi 9T                                                          | 1        | 0.63%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.63%   |
| Nvidia MCP61 Ethernet                                                      | 1        | 0.63%   |
| Lenovo Lenovo                                                              | 1        | 0.63%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.63%   |
| Intel Ethernet Controller I225-V                                           | 1        | 0.63%   |
| Intel Ethernet Connection I217-V                                           | 1        | 0.63%   |
| Intel Ethernet Connection (7) I219-V                                       | 1        | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                      | 1        | 0.63%   |
| Intel Ethernet Connection (5) I219-V                                       | 1        | 0.63%   |
| Intel Ethernet Connection (2) I218-LM                                      | 1        | 0.63%   |
| Intel Ethernet Connection (14) I219-V                                      | 1        | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 150      | 71.77%  |
| WiFi     | 57       | 27.27%  |
| Modem    | 2        | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 122      | 78.71%  |
| WiFi     | 33       | 21.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 125      | 82.78%  |
| 2     | 23       | 15.23%  |
| 0     | 2        | 1.32%   |
| 3     | 1        | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 150      | 98.68%  |
| Yes  | 2        | 1.32%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 13       | 59.09%  |
| Intel                   | 8        | 36.36%  |
| Realtek Semiconductor   | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13       | 59.09%  |
| Intel AX201 Bluetooth                               | 4        | 18.18%  |
| Realtek Bluetooth Radio                             | 1        | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.55%   |
| Intel AX210 Bluetooth                               | 1        | 4.55%   |
| Intel AX200 Bluetooth                               | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 114      | 53.52%  |
| AMD                 | 50       | 23.47%  |
| Nvidia              | 39       | 18.31%  |
| JMTek               | 2        | 0.94%   |
| C-Media Electronics | 2        | 0.94%   |
| Thermaltake         | 1        | 0.47%   |
| Tenx Technology     | 1        | 0.47%   |
| Logitech            | 1        | 0.47%   |
| Kingston Technology | 1        | 0.47%   |
| ASUSTek Computer    | 1        | 0.47%   |
| Astro Gaming        | 1        | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 19       | 7.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 18       | 7.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 15       | 5.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 12       | 4.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 12       | 4.72%   |
| AMD FCH Azalia Controller                                                         | 10       | 3.94%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 9        | 3.54%   |
| Nvidia High Definition Audio Controller                                           | 8        | 3.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8        | 3.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 8        | 3.15%   |
| AMD Trinity HDMI Audio Controller                                                 | 7        | 2.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6        | 2.36%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 2.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5        | 1.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 5        | 1.97%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 1.97%   |
| Nvidia GF119 HDMI Audio Controller                                                | 4        | 1.57%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4        | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 1.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 1.57%   |
| Nvidia GP102 HDMI Audio Controller                                                | 3        | 1.18%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 1.18%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 1.18%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 1.18%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3        | 1.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 1.18%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 3        | 1.18%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 1.18%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 0.79%   |
| Nvidia Audio device                                                               | 2        | 0.79%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 2        | 0.79%   |
| Intel HD Graphics SGPC                                                            | 2        | 0.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 0.79%   |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 2        | 0.79%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 0.79%   |
| AMD Navi 10 HDMI Audio                                                            | 2        | 0.79%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 24       | 19.67%  |
| Samsung Electronics          | 23       | 18.85%  |
| Kingston                     | 18       | 14.75%  |
| SK hynix                     | 17       | 13.93%  |
| Micron Technology            | 11       | 9.02%   |
| Crucial                      | 6        | 4.92%   |
| Corsair                      | 5        | 4.1%    |
| Ramaxel Technology           | 3        | 2.46%   |
| Nanya Technology             | 3        | 2.46%   |
| M                            | 3        | 2.46%   |
| MINPO                        | 2        | 1.64%   |
| Unknown (E)                  | 1        | 0.82%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 0.82%   |
| S                            | 1        | 0.82%   |
| Kingmax                      | 1        | 0.82%   |
| H                            | 1        | 0.82%   |
| G.Skill                      | 1        | 0.82%   |
| Elpida                       | 1        | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s             | 7        | 5.19%   |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 3        | 2.22%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s             | 3        | 2.22%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s             | 3        | 2.22%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s             | 3        | 2.22%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s             | 3        | 2.22%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s            | 3        | 2.22%   |
| Unknown RAM Module 4GB DIMM 400MT/s                             | 2        | 1.48%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                          | 2        | 1.48%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                          | 2        | 1.48%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                          | 2        | 1.48%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR2 1331MT/s            | 2        | 1.48%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s            | 2        | 1.48%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s             | 2        | 1.48%   |
| M RAM Module 2048MB DIMM DDR3 667MT/s                           | 2        | 1.48%   |
| Kingston RAM XK2M26-MIE 16384MB DIMM DDR4 3467MT/s              | 2        | 1.48%   |
| Crucial RAM CB16GU2666.C8ET 16GB DIMM DDR4 2667MT/s             | 2        | 1.48%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                         | 1        | 0.74%   |
| Unknown RAM Module 512MB DIMM DDR 667MT/s                       | 1        | 0.74%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                       | 1        | 0.74%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                            | 1        | 0.74%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s                     | 1        | 0.74%   |
| Unknown RAM Module 4096MB DIMM DDR2                             | 1        | 0.74%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                         | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM SDRAM                               | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                         | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM 667MT/s                             | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM 400MT/s                             | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1        | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                     | 1        | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                    | 1        | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR2                             | 1        | 0.74%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                         | 1        | 0.74%   |
| Unknown RAM Module 1GB DIMM SDRAM                               | 1        | 0.74%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                        | 1        | 0.74%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                     | 1        | 0.74%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                          | 1        | 0.74%   |
| Unknown (E) RAM Module 4096MB DIMM DDR3 667MT/s                 | 1        | 0.74%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 512MB DIMM DDR2 533MT/s | 1        | 0.74%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                   | 1        | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 40       | 43.96%  |
| DDR4    | 15       | 16.48%  |
| Unknown | 14       | 15.38%  |
| SDRAM   | 12       | 13.19%  |
| DDR2    | 8        | 8.79%   |
| DDR     | 2        | 2.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 81       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 36       | 35.64%  |
| 2048  | 30       | 29.7%   |
| 8192  | 19       | 18.81%  |
| 1024  | 8        | 7.92%   |
| 16384 | 6        | 5.94%   |
| 512   | 2        | 1.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 27       | 25.47%  |
| 1333    | 12       | 11.32%  |
| 667     | 9        | 8.49%   |
| 800     | 8        | 7.55%   |
| 400     | 7        | 6.6%    |
| 3200    | 4        | 3.77%   |
| 1867    | 4        | 3.77%   |
| 1866    | 4        | 3.77%   |
| 2667    | 3        | 2.83%   |
| 2400    | 3        | 2.83%   |
| 1066    | 3        | 2.83%   |
| Unknown | 3        | 2.83%   |
| 3600    | 2        | 1.89%   |
| 3467    | 2        | 1.89%   |
| 2133    | 2        | 1.89%   |
| 1331    | 2        | 1.89%   |
| 533     | 2        | 1.89%   |
| 49926   | 1        | 0.94%   |
| 3533    | 1        | 0.94%   |
| 3400    | 1        | 0.94%   |
| 3000    | 1        | 0.94%   |
| 2666    | 1        | 0.94%   |
| 2048    | 1        | 0.94%   |
| 2000    | 1        | 0.94%   |
| 1800    | 1        | 0.94%   |
| 1648    | 1        | 0.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 60%     |
| Seiko Epson     | 1        | 20%     |
| Kyocera         | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seiko Epson Printer             | 1        | 20%     |
| Kyocera UTAX_TA LP 3240_LP 4240 | 1        | 20%     |
| HP LaserJet P3005               | 1        | 20%     |
| HP LaserJet 1018                | 1        | 20%     |
| HP DeskJet F2492 All-in-One     | 1        | 20%     |

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
| Samsung Electronics     | 3        | 25%     |
| Logitech                | 2        | 16.67%  |
| Cubeternet              | 2        | 16.67%  |
| Z-Star Microelectronics | 1        | 8.33%   |
| OPPO Electronics        | 1        | 8.33%   |
| eMPIA Technology        | 1        | 8.33%   |
| Chicony Electronics     | 1        | 8.33%   |
| Apple                   | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 3        | 25%     |
| Logitech Webcam C270                    | 2        | 16.67%  |
| Z-Star A4 TECH USB2.0 PC Camera E       | 1        | 8.33%   |
| OPPO WAIPIO-MTP _SN:2B7F7E2C            | 1        | 8.33%   |
| eMPIA M035 Compact Web Cam              | 1        | 8.33%   |
| Cubeternet USB2.0 Camera                | 1        | 8.33%   |
| Cubeternet GL-UPC822 UVC WebCam         | 1        | 8.33%   |
| Chicony HP 720p HD Monitor Webcam       | 1        | 8.33%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 1        | 8.33%   |

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
| 0     | 126      | 79.75%  |
| 1     | 25       | 15.82%  |
| 2     | 6        | 3.8%    |
| 5     | 1        | 0.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 20       | 54.05%  |
| Net/wireless             | 9        | 24.32%  |
| Camera                   | 2        | 5.41%   |
| Unassigned class         | 1        | 2.7%    |
| Storage/ide              | 1        | 2.7%    |
| Sound                    | 1        | 2.7%    |
| Multimedia controller    | 1        | 2.7%    |
| Modem                    | 1        | 2.7%    |
| Communication controller | 1        | 2.7%    |

