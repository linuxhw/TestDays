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

Total: 187

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 17       | 12.98%  |
| OpenMandriva 4.3   | 12       | 9.16%   |
| Ubuntu 18.04       | 10       | 7.63%   |
| Zorin 16           | 8        | 6.11%   |
| OpenMandriva 4.2   | 7        | 5.34%   |
| Ubuntu 22.04       | 3        | 2.29%   |
| ROSA R10           | 3        | 2.29%   |
| Linux Mint 20      | 3        | 2.29%   |
| BlackPanther 18.1  | 3        | 2.29%   |
| Arch Rolling       | 3        | 2.29%   |
| Ubuntu 19.04       | 2        | 1.53%   |
| ROSA R9            | 2        | 1.53%   |
| ROSA R11           | 2        | 1.53%   |
| Pop!_OS 21.04      | 2        | 1.53%   |
| Pop!_OS 20.10      | 2        | 1.53%   |
| Manjaro            | 2        | 1.53%   |
| Kali 2022.1        | 2        | 1.53%   |
| Fedora 35          | 2        | 1.53%   |
| Fedora 32          | 2        | 1.53%   |
| Fedora 30          | 2        | 1.53%   |
| Arch               | 2        | 1.53%   |
| Zorin 15           | 1        | 0.76%   |
| Xubuntu 20.04      | 1        | 0.76%   |
| Xubuntu 18.04      | 1        | 0.76%   |
| Xubuntu 16.04      | 1        | 0.76%   |
| Ubuntu Unity 16.04 | 1        | 0.76%   |
| Ubuntu 22.10       | 1        | 0.76%   |
| Ubuntu 21.10       | 1        | 0.76%   |
| ROSA R11.1         | 1        | 0.76%   |
| ROSA 12.2          | 1        | 0.76%   |
| RHEL 8             | 1        | 0.76%   |
| Reborn OS Rolling  | 1        | 0.76%   |
| Pop!_OS 20.04      | 1        | 0.76%   |
| Parrot 5.0         | 1        | 0.76%   |
| OpenMandriva 4.90  | 1        | 0.76%   |
| Manjaro 21.3.7     | 1        | 0.76%   |
| Manjaro 21.2.0     | 1        | 0.76%   |
| Manjaro 20.2.1     | 1        | 0.76%   |
| Manjaro 19.0.2     | 1        | 0.76%   |
| LMDE 4             | 1        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 34       | 27.2%   |
| OpenMandriva | 20       | 16%     |
| Zorin        | 9        | 7.2%    |
| Linux Mint   | 9        | 7.2%    |
| ROSA         | 7        | 5.6%    |
| Fedora       | 7        | 5.6%    |
| Manjaro      | 6        | 4.8%    |
| Pop!_OS      | 5        | 4%      |
| Arch         | 5        | 4%      |
| Elementary   | 4        | 3.2%    |
| Xubuntu      | 3        | 2.4%    |
| Kali         | 3        | 2.4%    |
| BlackPanther | 3        | 2.4%    |
| Debian       | 2        | 1.6%    |
| Ubuntu Unity | 1        | 0.8%    |
| RHEL         | 1        | 0.8%    |
| Reborn OS    | 1        | 0.8%    |
| Parrot       | 1        | 0.8%    |
| LMDE         | 1        | 0.8%    |
| KDE neon     | 1        | 0.8%    |
| Endless      | 1        | 0.8%    |
| ArcoLinux    | 1        | 0.8%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003        | 11       | 7.8%    |
| 5.10.14-desktop-1omv4002       | 7        | 4.96%   |
| 5.4.0-42-generic               | 4        | 2.84%   |
| 5.15.0-48-generic              | 3        | 2.13%   |
| 5.11.0-37-generic              | 3        | 2.13%   |
| 5.9.1-arch1-1                  | 2        | 1.42%   |
| 5.4.0-48-generic               | 2        | 1.42%   |
| 5.4.0-37-generic               | 2        | 1.42%   |
| 5.4.0-33-generic               | 2        | 1.42%   |
| 5.4.0-26-generic               | 2        | 1.42%   |
| 5.3.0-51-generic               | 2        | 1.42%   |
| 5.15.0-50-generic              | 2        | 1.42%   |
| 5.13.0-39-generic              | 2        | 1.42%   |
| 5.13.0-30-generic              | 2        | 1.42%   |
| 5.11.0-7620-generic            | 2        | 1.42%   |
| 4.18.16-desktop-1bP            | 2        | 1.42%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2        | 1.42%   |
| 4.15.0-55-generic              | 2        | 1.42%   |
| 4.15.0-46-generic              | 2        | 1.42%   |
| 5.9.0-kali5-amd64              | 1        | 0.71%   |
| 5.8.14-arch1-1                 | 1        | 0.71%   |
| 5.8.0-7642-generic             | 1        | 0.71%   |
| 5.8.0-7630-generic             | 1        | 0.71%   |
| 5.8.0-14-generic               | 1        | 0.71%   |
| 5.7.7-200.fc32.x86_64          | 1        | 0.71%   |
| 5.6.14-desktop-2bP             | 1        | 0.71%   |
| 5.6.10-300.fc32.x86_64         | 1        | 0.71%   |
| 5.5.13-1-MANJARO               | 1        | 0.71%   |
| 5.4.8-200.fc31.x86_64          | 1        | 0.71%   |
| 5.4.40-generic-1rosa-x86_64    | 1        | 0.71%   |
| 5.4.0-89-generic               | 1        | 0.71%   |
| 5.4.0-88-generic               | 1        | 0.71%   |
| 5.4.0-77-generic               | 1        | 0.71%   |
| 5.4.0-73-generic               | 1        | 0.71%   |
| 5.4.0-70-generic               | 1        | 0.71%   |
| 5.4.0-67-generic               | 1        | 0.71%   |
| 5.4.0-64-generic               | 1        | 0.71%   |
| 5.4.0-59-generic               | 1        | 0.71%   |
| 5.4.0-58-generic               | 1        | 0.71%   |
| 5.4.0-45-generic               | 1        | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 22       | 16.67%  |
| 5.16.7  | 11       | 8.33%   |
| 4.15.0  | 10       | 7.58%   |
| 5.15.0  | 8        | 6.06%   |
| 5.13.0  | 8        | 6.06%   |
| 5.11.0  | 7        | 5.3%    |
| 5.10.14 | 7        | 5.3%    |
| 5.3.0   | 5        | 3.79%   |
| 5.0.0   | 4        | 3.03%   |
| 5.8.0   | 3        | 2.27%   |
| 5.9.1   | 2        | 1.52%   |
| 5.16.0  | 2        | 1.52%   |
| 4.9.60  | 2        | 1.52%   |
| 4.19.0  | 2        | 1.52%   |
| 4.18.16 | 2        | 1.52%   |
| 4.18.0  | 2        | 1.52%   |
| 5.9.0   | 1        | 0.76%   |
| 5.8.14  | 1        | 0.76%   |
| 5.7.7   | 1        | 0.76%   |
| 5.6.14  | 1        | 0.76%   |
| 5.6.10  | 1        | 0.76%   |
| 5.5.13  | 1        | 0.76%   |
| 5.4.8   | 1        | 0.76%   |
| 5.4.40  | 1        | 0.76%   |
| 5.3.3   | 1        | 0.76%   |
| 5.2.11  | 1        | 0.76%   |
| 5.19.12 | 1        | 0.76%   |
| 5.19.1  | 1        | 0.76%   |
| 5.19.0  | 1        | 0.76%   |
| 5.18.12 | 1        | 0.76%   |
| 5.17.9  | 1        | 0.76%   |
| 5.16.9  | 1        | 0.76%   |
| 5.16.18 | 1        | 0.76%   |
| 5.16.13 | 1        | 0.76%   |
| 5.16.12 | 1        | 0.76%   |
| 5.15.74 | 1        | 0.76%   |
| 5.15.65 | 1        | 0.76%   |
| 5.15.49 | 1        | 0.76%   |
| 5.13.9  | 1        | 0.76%   |
| 5.11.6  | 1        | 0.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 24       | 18.46%  |
| 5.16    | 17       | 13.08%  |
| 5.10    | 12       | 9.23%   |
| 5.15    | 10       | 7.69%   |
| 4.15    | 10       | 7.69%   |
| 5.13    | 9        | 6.92%   |
| 5.11    | 8        | 6.15%   |
| 5.3     | 6        | 4.62%   |
| 4.9     | 5        | 3.85%   |
| 5.8     | 4        | 3.08%   |
| 5.0     | 4        | 3.08%   |
| 4.18    | 4        | 3.08%   |
| 5.9     | 3        | 2.31%   |
| 5.19    | 3        | 2.31%   |
| 5.6     | 2        | 1.54%   |
| 4.19    | 2        | 1.54%   |
| 5.7     | 1        | 0.77%   |
| 5.5     | 1        | 0.77%   |
| 5.2     | 1        | 0.77%   |
| 5.18    | 1        | 0.77%   |
| 5.17    | 1        | 0.77%   |
| 4.4     | 1        | 0.77%   |
| 4.13    | 1        | 0.77%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 116      | 95.87%  |
| i686   | 5        | 4.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 51       | 41.46%  |
| KDE5            | 33       | 26.83%  |
| Unknown         | 12       | 9.76%   |
| XFCE            | 6        | 4.88%   |
| X-Cinnamon      | 6        | 4.88%   |
| KDE4            | 4        | 3.25%   |
| Pantheon        | 3        | 2.44%   |
| Cinnamon        | 2        | 1.63%   |
| Unity           | 1        | 0.81%   |
| MATE            | 1        | 0.81%   |
| LXDE            | 1        | 0.81%   |
| KDE             | 1        | 0.81%   |
| GNOME Flashback | 1        | 0.81%   |
| GNOME Classic   | 1        | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 104      | 84.55%  |
| Wayland | 12       | 9.76%   |
| Unknown | 6        | 4.88%   |
| Tty     | 1        | 0.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 55       | 45.08%  |
| SDDM    | 28       | 22.95%  |
| GDM     | 13       | 10.66%  |
| GDM3    | 11       | 9.02%   |
| LightDM | 6        | 4.92%   |
| TDM     | 5        | 4.1%    |
| KDM     | 4        | 3.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 85       | 69.11%  |
| Unknown | 23       | 18.7%   |
| ar_EG   | 9        | 7.32%   |
| en_GB   | 4        | 3.25%   |
| C       | 2        | 1.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 88       | 73.33%  |
| EFI  | 32       | 26.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 89       | 71.2%   |
| Overlay | 20       | 16%     |
| Unknown | 6        | 4.8%    |
| Xfs     | 4        | 3.2%    |
| Btrfs   | 4        | 3.2%    |
| Zfs     | 2        | 1.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 60       | 48.78%  |
| MBR     | 33       | 26.83%  |
| GPT     | 30       | 24.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 78.86%  |
| Yes       | 26       | 21.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 52.42%  |
| Yes       | 59       | 47.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 39       | 32.5%   |
| Gigabyte Technology | 29       | 24.17%  |
| Dell                | 23       | 19.17%  |
| ASUSTek Computer    | 10       | 8.33%   |
| MSI                 | 5        | 4.17%   |
| Lenovo              | 4        | 3.33%   |
| Acer                | 3        | 2.5%    |
| Intel               | 2        | 1.67%   |
| Alienware           | 2        | 1.67%   |
| Pegatron            | 1        | 0.83%   |
| IBM                 | 1        | 0.83%   |
| ECS                 | 1        | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte G41MT-S2PT                | 7        | 5.83%   |
| Dell OptiPlex 780                  | 4        | 3.33%   |
| HP Compaq Pro 6305 SFF             | 3        | 2.5%    |
| Gigabyte H61M-S2P                  | 3        | 2.5%    |
| Dell OptiPlex 760                  | 3        | 2.5%    |
| Dell OptiPlex 7020                 | 3        | 2.5%    |
| MSI MS-7C02                        | 2        | 1.67%   |
| HP Z600 Workstation                | 2        | 1.67%   |
| HP ProDesk 600 G1 TWR              | 2        | 1.67%   |
| HP ProDesk 600 G1 SFF              | 2        | 1.67%   |
| HP Compaq Elite 8300 SFF           | 2        | 1.67%   |
| HP Compaq dc7800                   | 2        | 1.67%   |
| Gigabyte H61M-S2V-B3               | 2        | 1.67%   |
| Gigabyte G41MT-S2P                 | 2        | 1.67%   |
| ASUS B250 MINING EXPERT            | 2        | 1.67%   |
| Alienware Aurora R12               | 2        | 1.67%   |
| Pegatron Pro 3010 Microtower PC    | 1        | 0.83%   |
| MSI MS-7C84                        | 1        | 0.83%   |
| MSI MS-7507                        | 1        | 0.83%   |
| MSI MS-7309                        | 1        | 0.83%   |
| Lenovo ThinkStation S30 4351D32    | 1        | 0.83%   |
| Lenovo ThinkCentre M600 10KGS0J000 | 1        | 0.83%   |
| Lenovo ThinkCentre M58 6258D3G     | 1        | 0.83%   |
| Lenovo ThinkCentre M55p 8811Y4U    | 1        | 0.83%   |
| Intel E4610                        | 1        | 0.83%   |
| Intel DG31PR AAD97573-205          | 1        | 0.83%   |
| IBM 81713FG                        | 1        | 0.83%   |
| HP Z840 Workstation                | 1        | 0.83%   |
| HP Z820 Workstation                | 1        | 0.83%   |
| HP Z620 Workstation                | 1        | 0.83%   |
| HP Z230 SFF Workstation            | 1        | 0.83%   |
| HP xw4600 Workstation              | 1        | 0.83%   |
| HP rp5800                          | 1        | 0.83%   |
| HP rp5700 Business System          | 1        | 0.83%   |
| HP EliteDesk 880 G1 TWR            | 1        | 0.83%   |
| HP EliteDesk 800 G4 SFF            | 1        | 0.83%   |
| HP EliteDesk 800 G2 TWR            | 1        | 0.83%   |
| HP EliteDesk 705 G3 SFF            | 1        | 0.83%   |
| HP EliteDesk 705 G1 SFF            | 1        | 0.83%   |
| HP EliteDesk 705 G1 MT             | 1        | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 19       | 15.83%  |
| HP Compaq            | 18       | 15%     |
| Gigabyte G41MT-S2PT  | 7        | 5.83%   |
| HP EliteDesk         | 6        | 5%      |
| HP ProDesk           | 4        | 3.33%   |
| Dell Precision       | 4        | 3.33%   |
| Lenovo ThinkCentre   | 3        | 2.5%    |
| Gigabyte H61M-S2P    | 3        | 2.5%    |
| ASUS TUF             | 3        | 2.5%    |
| MSI MS-7C02          | 2        | 1.67%   |
| HP Z600              | 2        | 1.67%   |
| Gigabyte H61M-S2V-B3 | 2        | 1.67%   |
| Gigabyte G41MT-S2P   | 2        | 1.67%   |
| ASUS B250            | 2        | 1.67%   |
| Alienware Aurora     | 2        | 1.67%   |
| Acer Veriton         | 2        | 1.67%   |
| Pegatron Pro         | 1        | 0.83%   |
| MSI MS-7C84          | 1        | 0.83%   |
| MSI MS-7507          | 1        | 0.83%   |
| MSI MS-7309          | 1        | 0.83%   |
| Lenovo ThinkStation  | 1        | 0.83%   |
| Intel E4610          | 1        | 0.83%   |
| Intel DG31PR         | 1        | 0.83%   |
| IBM 81713FG          | 1        | 0.83%   |
| HP Z840              | 1        | 0.83%   |
| HP Z820              | 1        | 0.83%   |
| HP Z620              | 1        | 0.83%   |
| HP Z230              | 1        | 0.83%   |
| HP xw4600            | 1        | 0.83%   |
| HP rp5800            | 1        | 0.83%   |
| HP rp5700            | 1        | 0.83%   |
| HP 290               | 1        | 0.83%   |
| HP 1850              | 1        | 0.83%   |
| Gigabyte Z97X-Gaming | 1        | 0.83%   |
| Gigabyte Z97-D3H     | 1        | 0.83%   |
| Gigabyte Z87-HD3     | 1        | 0.83%   |
| Gigabyte P61-DS3-B3  | 1        | 0.83%   |
| Gigabyte P31-DS3L    | 1        | 0.83%   |
| Gigabyte H61M-S2PT   | 1        | 0.83%   |
| Gigabyte H55M-S2V    | 1        | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 15       | 12.5%   |
| 2012 | 14       | 11.67%  |
| 2009 | 13       | 10.83%  |
| 2008 | 12       | 10%     |
| 2013 | 9        | 7.5%    |
| 2018 | 8        | 6.67%   |
| 2010 | 8        | 6.67%   |
| 2007 | 8        | 6.67%   |
| 2014 | 6        | 5%      |
| 2017 | 5        | 4.17%   |
| 2021 | 4        | 3.33%   |
| 2020 | 3        | 2.5%    |
| 2019 | 3        | 2.5%    |
| 2016 | 3        | 2.5%    |
| 2015 | 3        | 2.5%    |
| 2006 | 3        | 2.5%    |
| 2005 | 3        | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 120      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 119      | 99.17%  |
| Enabled  | 1        | 0.83%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 120      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 35       | 28.93%  |
| 4.01-8.0    | 24       | 19.83%  |
| 8.01-16.0   | 23       | 19.01%  |
| 16.01-24.0  | 18       | 14.88%  |
| 2.01-3.0    | 6        | 4.96%   |
| 32.01-64.0  | 5        | 4.13%   |
| 1.01-2.0    | 5        | 4.13%   |
| 64.01-256.0 | 2        | 1.65%   |
| 24.01-32.0  | 1        | 0.83%   |
| 0.51-1.0    | 1        | 0.83%   |
| 0.01-0.5    | 1        | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 46       | 34.85%  |
| 2.01-3.0    | 39       | 29.55%  |
| 3.01-4.0    | 12       | 9.09%   |
| 0.51-1.0    | 11       | 8.33%   |
| 4.01-8.0    | 10       | 7.58%   |
| 0.01-0.5    | 8        | 6.06%   |
| 8.01-16.0   | 5        | 3.79%   |
| 64.01-256.0 | 1        | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 62       | 49.21%  |
| 2       | 42       | 33.33%  |
| 3       | 14       | 11.11%  |
| 4       | 4        | 3.17%   |
| 9       | 1        | 0.79%   |
| 5       | 1        | 0.79%   |
| 0       | 1        | 0.79%   |
| Unknown | 1        | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 64       | 52.89%  |
| No        | 57       | 47.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 119      | 99.17%  |
| No        | 1        | 0.83%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 63.11%  |
| Yes       | 45       | 36.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 107      | 88.43%  |
| Yes       | 14       | 11.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Egypt   | 120      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Cairo               | 71       | 56.35%  |
| Giza                | 8        | 6.35%   |
| Alexandria          | 8        | 6.35%   |
| Al Mansurah         | 5        | 3.97%   |
| Tanta               | 4        | 3.17%   |
| Port Said           | 3        | 2.38%   |
| Suez                | 2        | 1.59%   |
| Mohandessin         | 2        | 1.59%   |
| Minya               | 2        | 1.59%   |
| Aswan               | 2        | 1.59%   |
| Assiut              | 2        | 1.59%   |
| Al Ma`adi           | 2        | 1.59%   |
| Zefta               | 1        | 0.79%   |
| Zagazig             | 1        | 0.79%   |
| Sharm el Sheikh     | 1        | 0.79%   |
| New Cairo           | 1        | 0.79%   |
| Mallawi             | 1        | 0.79%   |
| Luxor               | 1        | 0.79%   |
| Kafr ash Shaykh     | 1        | 0.79%   |
| Ismailia            | 1        | 0.79%   |
| Hurghada            | 1        | 0.79%   |
| Helwan              | 1        | 0.79%   |
| Faiyum              | 1        | 0.79%   |
| Bilbeis             | 1        | 0.79%   |
| Al Qalyubiyah       | 1        | 0.79%   |
| Akhmim              | 1        | 0.79%   |
| 6th of October City | 1        | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 69       | 107    | 38.33%  |
| Seagate                     | 42       | 56     | 23.33%  |
| Samsung Electronics         | 19       | 27     | 10.56%  |
| Kingston                    | 11       | 17     | 6.11%   |
| Toshiba                     | 10       | 11     | 5.56%   |
| Crucial                     | 6        | 8      | 3.33%   |
| Hitachi                     | 4        | 4      | 2.22%   |
| SanDisk                     | 2        | 2      | 1.11%   |
| KingSpec                    | 2        | 2      | 1.11%   |
| Hewlett-Packard             | 2        | 2      | 1.11%   |
| ZOTAC                       | 1        | 1      | 0.56%   |
| TwinMOS                     | 1        | 1      | 0.56%   |
| Transcend                   | 1        | 1      | 0.56%   |
| Maxtor                      | 1        | 2      | 0.56%   |
| LITEONIT                    | 1        | 1      | 0.56%   |
| Lite-On Technology          | 1        | 1      | 0.56%   |
| Kingston Technology Company | 1        | 1      | 0.56%   |
| JMicron Technology          | 1        | 1      | 0.56%   |
| Intel                       | 1        | 1      | 0.56%   |
| HS-SSD-E100                 | 1        | 1      | 0.56%   |
| HS-SSD-C100                 | 1        | 1      | 0.56%   |
| Hikvision                   | 1        | 1      | 0.56%   |
| Fujitsu                     | 1        | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 7        | 3.48%   |
| Seagate ST3500414CS 500GB        | 7        | 3.48%   |
| Toshiba DT01ACA050 500GB         | 5        | 2.49%   |
| Seagate ST3500312CS 500GB        | 5        | 2.49%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 3        | 1.49%   |
| WDC WD5000AAKX-001CA0 500GB      | 3        | 1.49%   |
| WDC WD5000AADS-00S9B0 500GB      | 3        | 1.49%   |
| WDC WD2500AAKX-75U6AA0 250GB     | 3        | 1.49%   |
| WDC WD1600AABS-00PRA0 160GB      | 3        | 1.49%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 1.49%   |
| WDC WD10EZEX-00BN5A0 1TB         | 3        | 1.49%   |
| WDC WD10EARS-00Y5B1 1TB          | 3        | 1.49%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.49%   |
| Seagate ST3500413AS 500GB        | 3        | 1.49%   |
| Kingston SA400S37480G 480GB SSD  | 3        | 1.49%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 1.49%   |
| WDC WD5000AVVS-63H0B1 500GB      | 2        | 1%      |
| WDC WD5000AVDS-63U7B1 500GB      | 2        | 1%      |
| WDC WD5000AAKX-08U6AA0 500GB     | 2        | 1%      |
| WDC WD5000AAKX-00ERMA0 500GB     | 2        | 1%      |
| WDC WD3200AAJS-00L7A0 320GB      | 2        | 1%      |
| WDC WD1600AABS-00H4A0 160GB      | 2        | 1%      |
| WDC WD10EZEX-22MFCA0 1TB         | 2        | 1%      |
| Seagate ST380815AS 80GB          | 2        | 1%      |
| Seagate ST3320311CS 320GB        | 2        | 1%      |
| Seagate ST3250318AS 250GB        | 2        | 1%      |
| Samsung SSD 860 EVO 500GB        | 2        | 1%      |
| Samsung PM9A1 NVMe 256GB         | 2        | 1%      |
| Kingston SUV400S37240G 240GB SSD | 2        | 1%      |
| Kingston SA400S37120G 120GB SSD  | 2        | 1%      |
| Crucial CT240BX500SSD1 240GB     | 2        | 1%      |
| ZOTAC ZTSSD-A4P-120G             | 1        | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.5%    |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.5%    |
| WDC WD800JD-60LSA5 80GB          | 1        | 0.5%    |
| WDC WD800BD-22MRA1 80GB          | 1        | 0.5%    |
| WDC WD6400AADS-00M2B0 640GB      | 1        | 0.5%    |
| WDC WD6003FZBX-00K5WB0 6TB       | 1        | 0.5%    |
| WDC WD5000AZLX-00K4KA0 500GB     | 1        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 67       | 104    | 50.76%  |
| Seagate             | 42       | 56     | 31.82%  |
| Toshiba             | 9        | 10     | 6.82%   |
| Samsung Electronics | 7        | 10     | 5.3%    |
| Hitachi             | 4        | 4      | 3.03%   |
| Maxtor              | 1        | 2      | 0.76%   |
| Hewlett-Packard     | 1        | 1      | 0.76%   |
| Fujitsu             | 1        | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 11       | 17     | 28.21%  |
| Samsung Electronics | 7        | 7      | 17.95%  |
| Crucial             | 6        | 8      | 15.38%  |
| WDC                 | 3        | 3      | 7.69%   |
| KingSpec            | 2        | 2      | 5.13%   |
| ZOTAC               | 1        | 1      | 2.56%   |
| TwinMOS             | 1        | 1      | 2.56%   |
| Transcend           | 1        | 1      | 2.56%   |
| Toshiba             | 1        | 1      | 2.56%   |
| SanDisk             | 1        | 1      | 2.56%   |
| LITEONIT            | 1        | 1      | 2.56%   |
| JMicron Technology  | 1        | 1      | 2.56%   |
| Intel               | 1        | 1      | 2.56%   |
| Hikvision           | 1        | 1      | 2.56%   |
| Hewlett-Packard     | 1        | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 112      | 188    | 71.79%  |
| SSD     | 33       | 47     | 21.15%  |
| NVMe    | 9        | 13     | 5.77%   |
| Unknown | 2        | 2      | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 116      | 236    | 92.06%  |
| NVMe | 9        | 13     | 7.14%   |
| SAS  | 1        | 1      | 0.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 100      | 175    | 70.92%  |
| 0.51-1.0   | 31       | 40     | 21.99%  |
| 1.01-2.0   | 7        | 10     | 4.96%   |
| 3.01-4.0   | 2        | 4      | 1.42%   |
| 4.01-10.0  | 1        | 6      | 0.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 30       | 23.26%  |
| 101-250        | 26       | 20.16%  |
| 1-20           | 18       | 13.95%  |
| 501-1000       | 16       | 12.4%   |
| 51-100         | 15       | 11.63%  |
| 21-50          | 9        | 6.98%   |
| 1001-2000      | 6        | 4.65%   |
| Unknown        | 4        | 3.1%    |
| 2001-3000      | 3        | 2.33%   |
| More than 3000 | 2        | 1.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 55       | 42.31%  |
| 101-250        | 23       | 17.69%  |
| 21-50          | 15       | 11.54%  |
| 251-500        | 12       | 9.23%   |
| 51-100         | 10       | 7.69%   |
| 501-1000       | 8        | 6.15%   |
| Unknown        | 4        | 3.08%   |
| More than 3000 | 2        | 1.54%   |
| 1001-2000      | 1        | 0.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63H0B1 500GB           | 2        | 2      | 5.13%   |
| WDC WD5000AVDS-63U7B1 500GB           | 2        | 2      | 5.13%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 3      | 5.13%   |
| WDC WD1600AABS-00H4A0 160GB           | 2        | 2      | 5.13%   |
| Seagate ST380815AS 80GB               | 2        | 2      | 5.13%   |
| WDC WD800JD-60LSA5 80GB               | 1        | 1      | 2.56%   |
| WDC WD800BD-22MRA1 80GB               | 1        | 1      | 2.56%   |
| WDC WD5000AAVS-22G9B1 500GB           | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-009FA0 500GB           | 1        | 1      | 2.56%   |
| WDC WD5000AAKS-00V6A0 500GB           | 1        | 1      | 2.56%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 1      | 2.56%   |
| WDC WD5000AADS-00M2B0 500GB           | 1        | 1      | 2.56%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1        | 1      | 2.56%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1        | 1      | 2.56%   |
| WDC WD3200AAJS-00B4A0 320GB           | 1        | 1      | 2.56%   |
| WDC WD3200A 320GB                     | 1        | 1      | 2.56%   |
| WDC WD2500AAJS-00VTA0 250GB           | 1        | 1      | 2.56%   |
| WDC WD1600AVVS-63L2B0 160GB           | 1        | 1      | 2.56%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1        | 1      | 2.56%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 2.56%   |
| WDC WD10EARS-00Y5B1 1TB               | 1        | 1      | 2.56%   |
| Toshiba MQ01ABF050 500GB              | 1        | 2      | 2.56%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 3      | 2.56%   |
| Seagate ST3500413AS 500GB             | 1        | 1      | 2.56%   |
| Seagate ST3500312CS 500GB             | 1        | 1      | 2.56%   |
| Seagate ST3320613AS 320GB             | 1        | 1      | 2.56%   |
| Seagate ST3160211AS 160GB             | 1        | 2      | 2.56%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 2.56%   |
| Samsung Electronics HD256GJ 250GB     | 1        | 1      | 2.56%   |
| Kingston SUV400S37240G 240GB SSD      | 1        | 2      | 2.56%   |
| Intel SSDSC2BW120H6 120GB             | 1        | 1      | 2.56%   |
| Hewlett-Packard VB0250EAVER 250GB     | 1        | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 27     | 62.86%  |
| Seagate             | 7        | 10     | 20%     |
| Samsung Electronics | 2        | 2      | 5.71%   |
| Toshiba             | 1        | 2      | 2.86%   |
| Kingston            | 1        | 2      | 2.86%   |
| Intel               | 1        | 1      | 2.86%   |
| Hewlett-Packard     | 1        | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 27     | 68.75%  |
| Seagate             | 7        | 10     | 21.88%  |
| Toshiba             | 1        | 2      | 3.13%   |
| Samsung Electronics | 1        | 1      | 3.13%   |
| Hewlett-Packard     | 1        | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 30       | 41     | 90.91%  |
| SSD  | 3        | 4      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD3200AAJS-00L7A0 320GB                      | 1        | 2      | 50%     |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 2      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 65       | 121    | 46.43%  |
| Works    | 40       | 81     | 28.57%  |
| Malfunc  | 33       | 45     | 23.57%  |
| Failed   | 2        | 3      | 1.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 96       | 71.64%  |
| AMD                         | 22       | 16.42%  |
| Samsung Electronics         | 6        | 4.48%   |
| Marvell Technology Group    | 2        | 1.49%   |
| Broadcom / LSI              | 2        | 1.49%   |
| SanDisk                     | 1        | 0.75%   |
| Nvidia                      | 1        | 0.75%   |
| LSI Logic / Symbios Logic   | 1        | 0.75%   |
| Lite-On Technology          | 1        | 0.75%   |
| Kingston Technology Company | 1        | 0.75%   |
| JMicron Technology          | 1        | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 17       | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 5.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 4.81%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 3.74%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 3.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 3.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 3.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.67%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.67%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 2.14%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 4        | 2.14%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 4        | 2.14%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 2.14%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 2.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 2.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 1.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.6%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 1.6%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 1.6%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 1.6%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 1.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 1.07%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 1.07%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.07%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.07%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 1.07%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 1.07%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 2        | 1.07%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2        | 1.07%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.07%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.07%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.07%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 67       | 46.53%  |
| IDE  | 54       | 37.5%   |
| RAID | 9        | 6.25%   |
| NVMe | 9        | 6.25%   |
| SAS  | 4        | 2.78%   |
| SCSI | 1        | 0.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 97       | 80.83%  |
| AMD    | 23       | 19.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 6        | 4.96%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 4.13%   |
| Intel Pentium D CPU 3.00GHz                 | 3        | 2.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.48%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 3        | 2.48%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 2.48%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 2.48%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz     | 3        | 2.48%   |
| AMD A4-5300B APU with Radeon HD Graphics    | 3        | 2.48%   |
| Intel Pentium 4 CPU 3.20GHz                 | 2        | 1.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.65%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.65%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.65%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.65%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.65%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 2        | 1.65%   |
| Intel Core 2 Duo CPU E4400 @ 2.00GHz        | 2        | 1.65%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 2        | 1.65%   |
| Intel Celeron D CPU 3.06GHz                 | 2        | 1.65%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.65%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.83%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5640 @ 2.67GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5-2690 v2 @ 3.00GHz         | 1        | 0.83%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz         | 1        | 0.83%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz          | 1        | 0.83%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1        | 0.83%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 0.83%   |
| Intel Xeon CPU 3.20GHz                      | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.83%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.83%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.83%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.83%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.83%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.83%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core 2 Duo        | 21       | 17.36%  |
| Intel Core i5           | 19       | 15.7%   |
| Intel Xeon              | 11       | 9.09%   |
| Intel Core i7           | 11       | 9.09%   |
| Intel Core i3           | 10       | 8.26%   |
| AMD Ryzen 5             | 5        | 4.13%   |
| Other                   | 4        | 3.31%   |
| Intel Core 2 Quad       | 4        | 3.31%   |
| Intel Core 2            | 4        | 3.31%   |
| Intel Pentium D         | 3        | 2.48%   |
| Intel Pentium 4         | 3        | 2.48%   |
| AMD A4                  | 3        | 2.48%   |
| Intel Pentium Dual-Core | 2        | 1.65%   |
| Intel Pentium           | 2        | 1.65%   |
| Intel Celeron D         | 2        | 1.65%   |
| Intel Celeron           | 2        | 1.65%   |
| AMD Phenom              | 2        | 1.65%   |
| AMD A8                  | 2        | 1.65%   |
| AMD Sempron             | 1        | 0.83%   |
| AMD Ryzen 9             | 1        | 0.83%   |
| AMD Ryzen 7             | 1        | 0.83%   |
| AMD PRO A10             | 1        | 0.83%   |
| AMD Phenom II X4        | 1        | 0.83%   |
| AMD Athlon II X3        | 1        | 0.83%   |
| AMD Athlon II X2        | 1        | 0.83%   |
| AMD Athlon 64 X2        | 1        | 0.83%   |
| AMD Athlon 64           | 1        | 0.83%   |
| AMD A6                  | 1        | 0.83%   |
| AMD A10                 | 1        | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 49       | 40.5%   |
| 4      | 36       | 29.75%  |
| 1      | 12       | 9.92%   |
| 8      | 8        | 6.61%   |
| 6      | 8        | 6.61%   |
| 3      | 3        | 2.48%   |
| 16     | 2        | 1.65%   |
| 24     | 1        | 0.83%   |
| 12     | 1        | 0.83%   |
| 10     | 1        | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 113      | 94.17%  |
| 2      | 7        | 5.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 72       | 59.02%  |
| 2      | 50       | 40.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 118      | 97.52%  |
| 32-bit         | 2        | 1.65%   |
| Unknown        | 1        | 0.83%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 22.4%   |
| 0x1067a    | 15       | 12%     |
| 0x306c3    | 11       | 8.8%    |
| 0x206a7    | 7        | 5.6%    |
| 0x306a9    | 6        | 4.8%    |
| 0x6fb      | 5        | 4%      |
| 0xf65      | 4        | 3.2%    |
| 0xa0671    | 3        | 2.4%    |
| 0x906ea    | 3        | 2.4%    |
| 0x6fd      | 3        | 2.4%    |
| 0x206c2    | 3        | 2.4%    |
| 0x0800820d | 3        | 2.4%    |
| 0x06001119 | 3        | 2.4%    |
| 0xf41      | 2        | 1.6%    |
| 0x906e9    | 2        | 1.6%    |
| 0x6f6      | 2        | 1.6%    |
| 0x506e3    | 2        | 1.6%    |
| 0x306e4    | 2        | 1.6%    |
| 0x106a5    | 2        | 1.6%    |
| 0x10676    | 2        | 1.6%    |
| 0x010000c8 | 2        | 1.6%    |
| 0x01000095 | 2        | 1.6%    |
| 0xf64      | 1        | 0.8%    |
| 0xf43      | 1        | 0.8%    |
| 0x906ed    | 1        | 0.8%    |
| 0x6f2      | 1        | 0.8%    |
| 0x406c4    | 1        | 0.8%    |
| 0x306f2    | 1        | 0.8%    |
| 0x206d7    | 1        | 0.8%    |
| 0x20655    | 1        | 0.8%    |
| 0x20652    | 1        | 0.8%    |
| 0x106e5    | 1        | 0.8%    |
| 0x0a201009 | 1        | 0.8%    |
| 0x08701013 | 1        | 0.8%    |
| 0x010000db | 1        | 0.8%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 19       | 15.57%  |
| Haswell     | 14       | 11.48%  |
| Core        | 13       | 10.66%  |
| SandyBridge | 10       | 8.2%    |
| NetBurst    | 10       | 8.2%    |
| IvyBridge   | 9        | 7.38%   |
| KabyLake    | 8        | 6.56%   |
| K10         | 6        | 4.92%   |
| Westmere    | 5        | 4.1%    |
| Piledriver  | 5        | 4.1%    |
| Zen+        | 3        | 2.46%   |
| Nehalem     | 3        | 2.46%   |
| Icelake     | 3        | 2.46%   |
| Zen 3       | 2        | 1.64%   |
| Zen 2       | 2        | 1.64%   |
| Steamroller | 2        | 1.64%   |
| Skylake     | 2        | 1.64%   |
| K8 Hammer   | 2        | 1.64%   |
| Unknown     | 2        | 1.64%   |
| Silvermont  | 1        | 0.82%   |
| Excavator   | 1        | 0.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 60       | 46.51%  |
| Nvidia | 38       | 29.46%  |
| AMD    | 31       | 24.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 14       | 10.77%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 8.46%   |
| Nvidia GT218 [GeForce 210]                                                  | 8        | 6.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 5.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 3.85%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 5        | 3.85%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 3.08%   |
| Nvidia GF119 [NVS 315]                                                      | 3        | 2.31%   |
| Nvidia GF108GL [Quadro 600]                                                 | 3        | 2.31%   |
| Intel HD Graphics 630                                                       | 3        | 2.31%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 3        | 2.31%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2.31%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 2.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.31%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 3        | 2.31%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 2.31%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.54%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 2        | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.54%   |
| AMD RS880 [Radeon HD 4200]                                                  | 2        | 1.54%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.54%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.77%   |
| Nvidia NV18 [GeForce4 MX 4000]                                              | 1        | 0.77%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.77%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.77%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.77%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.77%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.77%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.77%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.77%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.77%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.77%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 0.77%   |
| Nvidia G92 [GeForce 9800 GTX / 9800 GTX+]                                   | 1        | 0.77%   |
| Nvidia G86 [Quadro NVS 290]                                                 | 1        | 0.77%   |
| Nvidia G84GL [Quadro FX 1700]                                               | 1        | 0.77%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 0.77%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 0.77%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 51       | 42.5%   |
| 1 x Nvidia     | 35       | 29.17%  |
| 1 x AMD        | 24       | 20%     |
| Intel + AMD    | 4        | 3.33%   |
| Intel + Nvidia | 2        | 1.67%   |
| 3 x AMD        | 1        | 0.83%   |
| 2 x Intel      | 1        | 0.83%   |
| 2 x AMD        | 1        | 0.83%   |
| AMD + Nvidia   | 1        | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 93       | 75.61%  |
| Proprietary | 18       | 14.63%  |
| Unknown     | 12       | 9.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 54.47%  |
| 0.01-0.5   | 18       | 14.63%  |
| 0.51-1.0   | 12       | 9.76%   |
| 1.01-2.0   | 11       | 8.94%   |
| 7.01-8.0   | 7        | 5.69%   |
| 3.01-4.0   | 6        | 4.88%   |
| 8.01-16.0  | 2        | 1.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 27       | 27.55%  |
| Hewlett-Packard         | 18       | 18.37%  |
| Dell                    | 17       | 17.35%  |
| Lenovo                  | 6        | 6.12%   |
| Goldstar                | 5        | 5.1%    |
| Philips                 | 2        | 2.04%   |
| Fujitsu Siemens         | 2        | 2.04%   |
| Eizo                    | 2        | 2.04%   |
| BenQ                    | 2        | 2.04%   |
| ASUSTek Computer        | 2        | 2.04%   |
| ViewSonic               | 1        | 1.02%   |
| Unknown                 | 1        | 1.02%   |
| Sun                     | 1        | 1.02%   |
| Sony                    | 1        | 1.02%   |
| Planar                  | 1        | 1.02%   |
| NEC Computers           | 1        | 1.02%   |
| MStar                   | 1        | 1.02%   |
| JWY                     | 1        | 1.02%   |
| Gigabyte Technology     | 1        | 1.02%   |
| eMachines               | 1        | 1.02%   |
| Chi Mei Optoelectronics | 1        | 1.02%   |
| AUS                     | 1        | 1.02%   |
| AOC                     | 1        | 1.02%   |
| Ancor Communications    | 1        | 1.02%   |
| Acer                    | 1        | 1.02%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                     | 4        | 3.88%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch     | 3        | 2.91%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch             | 3        | 2.91%   |
| Hewlett-Packard L1950 HWP26E7 1280x1024 380x300mm 19.1-inch          | 3        | 2.91%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 2        | 1.94%   |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch  | 2        | 1.94%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 2        | 1.94%   |
| Hewlett-Packard LA2206 HWP2948 1920x1080 476x268mm 21.5-inch         | 2        | 1.94%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch        | 1        | 0.97%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                 | 1        | 0.97%   |
| Sun PN17JO SUN0589 1280x1024 295x236mm 14.9-inch                     | 1        | 0.97%   |
| Sony KDL-23S2000 SNY9900 1360x768                                    | 1        | 0.97%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch    | 1        | 0.97%   |
| Samsung Electronics SyncMaster SAM0590 1600x900 443x249mm 20.0-inch  | 1        | 0.97%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 1        | 0.97%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch  | 1        | 0.97%   |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch | 1        | 0.97%   |
| Samsung Electronics SMBX2031 SAM076A 1600x900 443x249mm 20.0-inch    | 1        | 0.97%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch    | 1        | 0.97%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1        | 0.97%   |
| Samsung Electronics S23B300 SAM08AE 1920x1080 510x287mm 23.0-inch    | 1        | 0.97%   |
| Samsung Electronics S22E200 SAM0C6D 1920x1080 477x268mm 21.5-inch    | 1        | 0.97%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1        | 0.97%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 1        | 0.97%   |
| Samsung Electronics S19B300 SAM08A4 1366x768 410x230mm 18.5-inch     | 1        | 0.97%   |
| Samsung Electronics LCD Monitor SMBX2350 1920x1080                   | 1        | 0.97%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                   | 1        | 0.97%   |
| Samsung Electronics LCD Monitor SA300/SA350 1366x768                 | 1        | 0.97%   |
| Samsung Electronics LCD Monitor S24D330 1920x1080                    | 1        | 0.97%   |
| Samsung Electronics LCD Monitor S22D300 1920x1080                    | 1        | 0.97%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch   | 1        | 0.97%   |
| Samsung Electronics C24FG7x SAM0E43 1920x1080 532x304mm 24.1-inch    | 1        | 0.97%   |
| Planar PE2010 PLN2010 1400x1050 400x300mm 19.7-inch                  | 1        | 0.97%   |
| Philips LCD Monitor PHLC01D 1440x900 370x230mm 17.2-inch             | 1        | 0.97%   |
| Philips 190CW PHLC023 1440x900 408x255mm 18.9-inch                   | 1        | 0.97%   |
| NEC Computers EA223WM NEC688F 1680x1050 470x300mm 22.0-inch          | 1        | 0.97%   |
| MStar PROJECTORS MST0B01 1920x540 708x398mm 32.0-inch                | 1        | 0.97%   |
| Lenovo LT2252p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch            | 1        | 0.97%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch             | 1        | 0.97%   |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch               | 1        | 0.97%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 32.29%  |
| 1280x1024 (SXGA)   | 21       | 21.88%  |
| 1366x768 (WXGA)    | 10       | 10.42%  |
| 1440x900 (WXGA+)   | 9        | 9.38%   |
| 1600x900 (HD+)     | 6        | 6.25%   |
| 1680x1050 (WSXGA+) | 5        | 5.21%   |
| 3840x2160 (4K)     | 3        | 3.13%   |
| 2560x1440 (QHD)    | 2        | 2.08%   |
| 3440x1440          | 1        | 1.04%   |
| 2560x1600          | 1        | 1.04%   |
| 1920x540           | 1        | 1.04%   |
| 1920x1200 (WUXGA)  | 1        | 1.04%   |
| 1600x1200          | 1        | 1.04%   |
| 1400x1050          | 1        | 1.04%   |
| 1360x768           | 1        | 1.04%   |
| 1280x720 (HD)      | 1        | 1.04%   |
| 1024x768 (XGA)     | 1        | 1.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 15       | 15.31%  |
| 19      | 13       | 13.27%  |
| 18      | 10       | 10.2%   |
| 24      | 9        | 9.18%   |
| Unknown | 9        | 9.18%   |
| 21      | 7        | 7.14%   |
| 20      | 6        | 6.12%   |
| 27      | 5        | 5.1%    |
| 23      | 5        | 5.1%    |
| 22      | 5        | 5.1%    |
| 15      | 4        | 4.08%   |
| 32      | 2        | 2.04%   |
| 31      | 2        | 2.04%   |
| 54      | 1        | 1.02%   |
| 34      | 1        | 1.02%   |
| 29      | 1        | 1.02%   |
| 25      | 1        | 1.02%   |
| 16      | 1        | 1.02%   |
| 14      | 1        | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 34       | 35.05%  |
| 501-600     | 17       | 17.53%  |
| 301-350     | 15       | 15.46%  |
| 351-400     | 12       | 12.37%  |
| Unknown     | 9        | 9.28%   |
| 601-700     | 5        | 5.15%   |
| 701-800     | 3        | 3.09%   |
| 201-300     | 1        | 1.03%   |
| 1001-1500   | 1        | 1.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 44       | 46.32%  |
| 5/4     | 18       | 18.95%  |
| 16/10   | 18       | 18.95%  |
| Unknown | 8        | 8.42%   |
| 4/3     | 6        | 6.32%   |
| 21/9    | 1        | 1.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 25       | 25.77%  |
| 141-150        | 20       | 20.62%  |
| 201-250        | 16       | 16.49%  |
| Unknown        | 9        | 9.28%   |
| 351-500        | 6        | 6.19%   |
| 251-300        | 6        | 6.19%   |
| 301-350        | 5        | 5.15%   |
| 131-140        | 3        | 3.09%   |
| 101-110        | 3        | 3.09%   |
| 111-120        | 2        | 2.06%   |
| More than 1000 | 1        | 1.03%   |
| 121-130        | 1        | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 68       | 72.34%  |
| 101-120 | 13       | 13.83%  |
| Unknown | 9        | 9.57%   |
| 121-160 | 3        | 3.19%   |
| 1-50    | 1        | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 100      | 79.37%  |
| 0     | 15       | 11.9%   |
| 2     | 11       | 8.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 51       | 30.18%  |
| Realtek Semiconductor             | 49       | 28.99%  |
| Qualcomm Atheros                  | 16       | 9.47%   |
| Broadcom                          | 14       | 8.28%   |
| Ralink Technology                 | 12       | 7.1%    |
| Broadcom Limited                  | 7        | 4.14%   |
| Qualcomm Atheros Communications   | 4        | 2.37%   |
| TP-Link                           | 3        | 1.78%   |
| Samsung Electronics               | 2        | 1.18%   |
| Ralink                            | 2        | 1.18%   |
| Edimax Technology                 | 2        | 1.18%   |
| Sundance Technology Inc / IC Plus | 1        | 0.59%   |
| Qualcomm                          | 1        | 0.59%   |
| Nvidia                            | 1        | 0.59%   |
| Motorola                          | 1        | 0.59%   |
| Lenovo                            | 1        | 0.59%   |
| D-Link                            | 1        | 0.59%   |
| 3Com                              | 1        | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 30       | 16.95%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 5.65%   |
| Ralink RT5370 Wireless Adapter                                                | 9        | 5.08%   |
| Intel Ethernet Connection I217-LM                                             | 9        | 5.08%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 9        | 5.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 8        | 4.52%   |
| Realtek 802.11n                                                               | 6        | 3.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5        | 2.82%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                      | 5        | 2.82%   |
| Ralink MT7601U Wireless Adapter                                               | 4        | 2.26%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 4        | 2.26%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 4        | 2.26%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 3        | 1.69%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 3        | 1.69%   |
| Intel 82566DM Gigabit Network Connection                                      | 3        | 1.69%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 3        | 1.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 1.13%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 1.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.13%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 1.13%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2        | 1.13%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 2        | 1.13%   |
| Intel I211 Gigabit Network Connection                                         | 2        | 1.13%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 1.13%   |
| Intel 82578DM Gigabit Network Connection                                      | 2        | 1.13%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.13%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2        | 1.13%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 1.13%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 2        | 1.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.56%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 0.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.56%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1        | 0.56%   |
| Qualcomm Redmi Note 8                                                         | 1        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 13       | 28.26%  |
| Ralink Technology               | 12       | 26.09%  |
| Intel                           | 5        | 10.87%  |
| Qualcomm Atheros Communications | 4        | 8.7%    |
| Qualcomm Atheros                | 4        | 8.7%    |
| TP-Link                         | 3        | 6.52%   |
| Ralink                          | 2        | 4.35%   |
| Edimax Technology               | 2        | 4.35%   |
| D-Link                          | 1        | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Ralink RT5370 Wireless Adapter                                                | 9        | 19.15%  |
| Realtek 802.11n                                                               | 6        | 12.77%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5        | 10.64%  |
| Ralink MT7601U Wireless Adapter                                               | 4        | 8.51%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 3        | 6.38%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 3        | 6.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 4.26%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2        | 4.26%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 4.26%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2        | 4.26%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 2.13%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 2.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 2.13%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 1        | 2.13%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 2.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 2.13%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]          | 1        | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 47       | 37.3%   |
| Realtek Semiconductor             | 38       | 30.16%  |
| Broadcom                          | 14       | 11.11%  |
| Qualcomm Atheros                  | 13       | 10.32%  |
| Broadcom Limited                  | 7        | 5.56%   |
| Samsung Electronics               | 2        | 1.59%   |
| Sundance Technology Inc / IC Plus | 1        | 0.79%   |
| Qualcomm                          | 1        | 0.79%   |
| Nvidia                            | 1        | 0.79%   |
| Lenovo                            | 1        | 0.79%   |
| 3Com                              | 1        | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 30       | 23.26%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 10       | 7.75%   |
| Intel Ethernet Connection I217-LM                                          | 9        | 6.98%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 9        | 6.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 8        | 6.2%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 5        | 3.88%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 3.1%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 4        | 3.1%    |
| Intel 82566DM Gigabit Network Connection                                   | 3        | 2.33%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                           | 3        | 2.33%   |
| Realtek RTL8125 2.5GbE Controller                                          | 2        | 1.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 1.55%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 2        | 1.55%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 2        | 1.55%   |
| Intel I211 Gigabit Network Connection                                      | 2        | 1.55%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.55%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 1.55%   |
| Intel 82574L Gigabit Network Connection                                    | 2        | 1.55%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2        | 1.55%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 1.55%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 0.78%   |
| Qualcomm Redmi Note 8                                                      | 1        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.78%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.78%   |
| Nvidia MCP61 Ethernet                                                      | 1        | 0.78%   |
| Lenovo Lenovo                                                              | 1        | 0.78%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.78%   |
| Intel Ethernet Connection I217-V                                           | 1        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                       | 1        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                                      | 1        | 0.78%   |
| Intel Ethernet Connection (5) I219-V                                       | 1        | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 0.78%   |
| Intel Ethernet Connection (2) I218-LM                                      | 1        | 0.78%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                    | 1        | 0.78%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                    | 1        | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 119      | 72.56%  |
| WiFi     | 44       | 26.83%  |
| Modem    | 1        | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 97       | 80.17%  |
| WiFi     | 24       | 19.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 101      | 84.17%  |
| 2     | 17       | 14.17%  |
| 0     | 2        | 1.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 120      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 8        | 57.14%  |
| Intel                   | 5        | 35.71%  |
| Realtek Semiconductor   | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 57.14%  |
| Intel AX201 Bluetooth                               | 3        | 21.43%  |
| Realtek RTL8821A Bluetooth                          | 1        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 7.14%   |
| Intel AX200 Bluetooth                               | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 96       | 56.8%   |
| AMD                 | 36       | 21.3%   |
| Nvidia              | 31       | 18.34%  |
| JMTek               | 2        | 1.18%   |
| Thermaltake         | 1        | 0.59%   |
| Tenx Technology     | 1        | 0.59%   |
| Logitech            | 1        | 0.59%   |
| C-Media Electronics | 1        | 0.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15       | 7.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 6.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 5.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 5.18%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 9        | 4.66%   |
| Nvidia High Definition Audio Controller                                    | 8        | 4.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 3.63%   |
| AMD FCH Azalia Controller                                                  | 7        | 3.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 3.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 3.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 3.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5        | 2.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5        | 2.59%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 2.59%   |
| AMD Trinity HDMI Audio Controller                                          | 5        | 2.59%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 2.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 2.07%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 2.07%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 1.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.55%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.55%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1.55%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.04%   |
| JMTek USB PnP Audio Device                                                 | 2        | 1.04%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 1.04%   |
| Intel Audio device                                                         | 2        | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.04%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 2        | 1.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.04%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 1.04%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 1.04%   |
| Thermaltake Tt eSPORTS SHOCK PRO RGB 7.1                                   | 1        | 0.52%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.52%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.52%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.52%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 23       | 23%     |
| Samsung Electronics          | 18       | 18%     |
| Kingston                     | 15       | 15%     |
| SK hynix                     | 13       | 13%     |
| Micron Technology            | 8        | 8%      |
| Crucial                      | 5        | 5%      |
| Nanya Technology             | 3        | 3%      |
| M                            | 3        | 3%      |
| Corsair                      | 3        | 3%      |
| Ramaxel Technology           | 2        | 2%      |
| MINPO                        | 2        | 2%      |
| Unknown (E)                  | 1        | 1%      |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 1%      |
| S                            | 1        | 1%      |
| Kingmax                      | 1        | 1%      |
| Elpida                       | 1        | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s             | 4        | 3.6%    |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 3        | 2.7%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s             | 3        | 2.7%    |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s            | 3        | 2.7%    |
| Unknown RAM Module 4GB DIMM 400MT/s                             | 2        | 1.8%    |
| Unknown RAM Module 4096MB DIMM 400MT/s                          | 2        | 1.8%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                          | 2        | 1.8%    |
| Unknown RAM Module 2048MB DIMM 400MT/s                          | 2        | 1.8%    |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR 667MT/s              | 2        | 1.8%    |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s             | 2        | 1.8%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s                  | 2        | 1.8%    |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s             | 2        | 1.8%    |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1600MT/s          | 2        | 1.8%    |
| M RAM Module 2048MB DIMM DDR3 667MT/s                           | 2        | 1.8%    |
| Kingston RAM XK2M26-MIE 16384MB DIMM DDR4 3467MT/s              | 2        | 1.8%    |
| Unknown RAM Module 8192MB DIMM 1066MT/s                         | 1        | 0.9%    |
| Unknown RAM Module 512MB DIMM DDR 667MT/s                       | 1        | 0.9%    |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s                     | 1        | 0.9%    |
| Unknown RAM Module 4096MB DIMM DDR2                             | 1        | 0.9%    |
| Unknown RAM Module 4096MB DIMM 1066MT/s                         | 1        | 0.9%    |
| Unknown RAM Module 2GB DIMM SDRAM                               | 1        | 0.9%    |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                         | 1        | 0.9%    |
| Unknown RAM Module 2GB DIMM 667MT/s                             | 1        | 0.9%    |
| Unknown RAM Module 2GB DIMM 400MT/s                             | 1        | 0.9%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1        | 0.9%    |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                     | 1        | 0.9%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                    | 1        | 0.9%    |
| Unknown RAM Module 2048MB DIMM DDR2                             | 1        | 0.9%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                         | 1        | 0.9%    |
| Unknown RAM Module 1GB DIMM SDRAM                               | 1        | 0.9%    |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                        | 1        | 0.9%    |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                     | 1        | 0.9%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                          | 1        | 0.9%    |
| Unknown (E) RAM Module 4096MB DIMM DDR3 667MT/s                 | 1        | 0.9%    |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 512MB DIMM DDR2 533MT/s | 1        | 0.9%    |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                   | 1        | 0.9%    |
| SK hynix RAM Module 1GB DIMM DDR2 533MT/s                       | 1        | 0.9%    |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s           | 1        | 0.9%    |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s             | 1        | 0.9%    |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s            | 1        | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 30       | 40.54%  |
| Unknown | 14       | 18.92%  |
| SDRAM   | 10       | 13.51%  |
| DDR4    | 10       | 13.51%  |
| DDR2    | 8        | 10.81%  |
| DDR     | 2        | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 66       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 29       | 34.52%  |
| 4096  | 26       | 30.95%  |
| 8192  | 14       | 16.67%  |
| 1024  | 8        | 9.52%   |
| 16384 | 5        | 5.95%   |
| 512   | 2        | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 18       | 20.93%  |
| 1333    | 11       | 12.79%  |
| 667     | 10       | 11.63%  |
| 800     | 8        | 9.3%    |
| 400     | 7        | 8.14%   |
| 3200    | 4        | 4.65%   |
| 2400    | 4        | 4.65%   |
| 1867    | 3        | 3.49%   |
| 1866    | 3        | 3.49%   |
| 1066    | 3        | 3.49%   |
| Unknown | 3        | 3.49%   |
| 3467    | 2        | 2.33%   |
| 533     | 2        | 2.33%   |
| 49926   | 1        | 1.16%   |
| 3600    | 1        | 1.16%   |
| 3000    | 1        | 1.16%   |
| 2667    | 1        | 1.16%   |
| 2666    | 1        | 1.16%   |
| 2048    | 1        | 1.16%   |
| 2000    | 1        | 1.16%   |
| 1800    | 1        | 1.16%   |

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
| Samsung Electronics     | 3        | 30%     |
| Logitech                | 2        | 20%     |
| Cubeternet              | 2        | 20%     |
| Z-Star Microelectronics | 1        | 10%     |
| eMPIA Technology        | 1        | 10%     |
| Chicony Electronics     | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 3        | 30%     |
| Logitech Webcam C270                    | 2        | 20%     |
| Z-Star Vimicro USB Camera (Altair)      | 1        | 10%     |
| eMPIA M035 Compact Web Cam              | 1        | 10%     |
| Cubeternet USB2.0 Camera                | 1        | 10%     |
| Cubeternet GL-UPC822 UVC WebCam         | 1        | 10%     |
| Chicony HP 720p HD Monitor Webcam       | 1        | 10%     |

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
| 0     | 102      | 82.26%  |
| 1     | 19       | 15.32%  |
| 2     | 2        | 1.61%   |
| 5     | 1        | 0.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 13       | 50%     |
| Net/wireless             | 6        | 23.08%  |
| Unassigned class         | 1        | 3.85%   |
| Storage/ide              | 1        | 3.85%   |
| Sound                    | 1        | 3.85%   |
| Multimedia controller    | 1        | 3.85%   |
| Modem                    | 1        | 3.85%   |
| Communication controller | 1        | 3.85%   |
| Camera                   | 1        | 3.85%   |

