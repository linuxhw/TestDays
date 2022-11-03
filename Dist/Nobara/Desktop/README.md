Nobara - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Nobara.

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

Total: 93

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ECS       | H61H2-CM                    | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| ASRock    | Z77 Pro4                    | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock    | Z77 Pro4                    | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| HP        | 8653 A                      | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| ASRock    | X570 Taichi                 | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| Dell      | 09KPNV A00                  | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Gigabyte  | 970A-DS3P                   | [7e31b6af67](https://linux-hardware.org/?probe=7e31b6af67) | Oct 27, 2022 |
| Gigabyte  | 970A-DS3P                   | [6823943242](https://linux-hardware.org/?probe=6823943242) | Oct 27, 2022 |
| Intel     | B75                         | [eb7c27f1e5](https://linux-hardware.org/?probe=eb7c27f1e5) | Oct 26, 2022 |
| HP        | 3029h                       | [c278953154](https://linux-hardware.org/?probe=c278953154) | Oct 25, 2022 |
| Gigabyte  | Z590I VISION D              | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| ASUSTek   | PRIME A320M-K               | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| ASUSTek   | ROG STRIX Z390-E GAMING     | [7e40be1c82](https://linux-hardware.org/?probe=7e40be1c82) | Oct 23, 2022 |
| Gigabyte  | Z97-HD3                     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| ASUSTek   | TUF Gaming X570-PRO WIFI... | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| Gigabyte  | B450M DS3H-CF               | [c901f6927c](https://linux-hardware.org/?probe=c901f6927c) | Oct 18, 2022 |
| MSI       | MPG Z390 GAMING PLUS        | [624be3f0f3](https://linux-hardware.org/?probe=624be3f0f3) | Oct 17, 2022 |
| ASUSTek   | TUF Gaming B450M-PLUS II    | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| MSI       | MPG Z390 GAMING PRO CARB... | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| MSI       | Z87 XPOWER                  | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| ASUSTek   | PRIME X370-PRO              | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| MSI       | MPG Z390 GAMING PRO CARB... | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| Dell      | 0F6X5P A00                  | [49baafbc65](https://linux-hardware.org/?probe=49baafbc65) | Oct 10, 2022 |
| MSI       | PRO Z690-A DDR4             | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | [05dfea29df](https://linux-hardware.org/?probe=05dfea29df) | Oct 07, 2022 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | [24471f06da](https://linux-hardware.org/?probe=24471f06da) | Oct 07, 2022 |
| Gigabyte  | X570 I AORUS PRO WIFI       | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| HP        | 1998                        | [f2b9957fdd](https://linux-hardware.org/?probe=f2b9957fdd) | Oct 06, 2022 |
| MSI       | B450-A PRO MAX              | [b161553abb](https://linux-hardware.org/?probe=b161553abb) | Oct 05, 2022 |
| ASRock    | B450M Steel Legend          | [4f4352de45](https://linux-hardware.org/?probe=4f4352de45) | Oct 04, 2022 |
| ASUSTek   | H61M-K                      | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI       | B350 PC MATE                | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| Dell      | 0M5DCD A00                  | [3cc1e139dc](https://linux-hardware.org/?probe=3cc1e139dc) | Oct 02, 2022 |
| MSI       | MEG X570 UNIFY              | [4d2e449699](https://linux-hardware.org/?probe=4d2e449699) | Sep 30, 2022 |
| ASRock    | X470 Master SLI             | [47c190b6e9](https://linux-hardware.org/?probe=47c190b6e9) | Sep 30, 2022 |
| Gigabyte  | H270-Gaming 3               | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte  | H270-Gaming 3               | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| Gigabyte  | AB350-Gaming 3-CF           | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| Intel     | B75                         | [af5aef869c](https://linux-hardware.org/?probe=af5aef869c) | Sep 28, 2022 |
| Gigabyte  | AB350-Gaming 3-CF           | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| MSI       | MAG X570 TOMAHAWK WIFI      | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| MSI       | A68HM-E33 V2                | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| ASUSTek   | 970 PRO GAMING/AURA         | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek   | 970 PRO GAMING/AURA         | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| ASUSTek   | PRIME H410M-A               | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| MSI       | 970 GAMING                  | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Dell      | 0G785M A00                  | [c461ec42d6](https://linux-hardware.org/?probe=c461ec42d6) | Sep 24, 2022 |
| ASUSTek   | PRIME A320M-K               | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| Gigabyte  | EP45-UD3L                   | [71c630ea03](https://linux-hardware.org/?probe=71c630ea03) | Sep 22, 2022 |
| ASUSTek   | PRIME H310M-E R2.0          | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| HP        | 8594                        | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| Gigabyte  | EP45-UD3L                   | [2b90168b71](https://linux-hardware.org/?probe=2b90168b71) | Sep 21, 2022 |
| ASRock    | X470 Master SLI             | [3c8fefe578](https://linux-hardware.org/?probe=3c8fefe578) | Sep 20, 2022 |
| ASRock    | X470 Master SLI             | [1975320cad](https://linux-hardware.org/?probe=1975320cad) | Sep 20, 2022 |
| Dell      | 0G785M A00                  | [8b8c41b401](https://linux-hardware.org/?probe=8b8c41b401) | Sep 19, 2022 |
| Unknown   | T3 MRD                      | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| MSI       | X570-A PRO                  | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| Gigabyte  | A320M-S2H-CF                | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| Unknown   | T3 MRD                      | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| Biostar   | H410MH S2                   | [832dd81851](https://linux-hardware.org/?probe=832dd81851) | Sep 17, 2022 |
| Lenovo    | MAHOBAY NOK                 | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek   | TUF Gaming B550M-PLUS WI... | [d9e9ec9afa](https://linux-hardware.org/?probe=d9e9ec9afa) | Sep 09, 2022 |
| ASUSTek   | TUF Gaming B550M-PLUS WI... | [1cdd7cda15](https://linux-hardware.org/?probe=1cdd7cda15) | Sep 09, 2022 |
| ASUSTek   | TUF Gaming X570-PRO         | [6eae76b5d0](https://linux-hardware.org/?probe=6eae76b5d0) | Sep 01, 2022 |
| ASRock    | FM2A55M-HD+                 | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| Gigabyte  | H110M-H-CF                  | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Alienware | 01NYPT A00                  | [cd95b79270](https://linux-hardware.org/?probe=cd95b79270) | Aug 29, 2022 |
| ASRock    | B560 Steel Legend           | [c64907de8d](https://linux-hardware.org/?probe=c64907de8d) | Aug 27, 2022 |
| ASUSTek   | P8Z68-V PRO                 | [37ae937f4d](https://linux-hardware.org/?probe=37ae937f4d) | Aug 26, 2022 |
| ASUSTek   | PRIME X570-PRO              | [663509c999](https://linux-hardware.org/?probe=663509c999) | Aug 24, 2022 |
| ASUSTek   | PRIME X570-PRO              | [2b7d1d59a1](https://linux-hardware.org/?probe=2b7d1d59a1) | Aug 24, 2022 |
| ASUSTek   | PRIME A320M-K               | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ASRock    | H61M-VG3                    | [a3cd7ba2c1](https://linux-hardware.org/?probe=a3cd7ba2c1) | Aug 22, 2022 |
| ASUSTek   | B85M-E                      | [0b5044dacf](https://linux-hardware.org/?probe=0b5044dacf) | Aug 19, 2022 |
| Gigabyte  | B450M DS3H-CF               | [a2b6c2ae17](https://linux-hardware.org/?probe=a2b6c2ae17) | Aug 19, 2022 |
| ASRock    | X470 Master SLI             | [ce62975b20](https://linux-hardware.org/?probe=ce62975b20) | Aug 15, 2022 |
| ASUSTek   | PRIME B350-PLUS             | [b2bbce2845](https://linux-hardware.org/?probe=b2bbce2845) | Aug 15, 2022 |
| ASRock    | Z97 Extreme6                | [31d7973a9d](https://linux-hardware.org/?probe=31d7973a9d) | Aug 14, 2022 |
| ASRock    | 760GM-HDV                   | [beabb7dd99](https://linux-hardware.org/?probe=beabb7dd99) | Aug 14, 2022 |
| MSI       | B450 TOMAHAWK MAX           | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| HP        | 8906 SMVB                   | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| HP        | 8054                        | [469b765fe0](https://linux-hardware.org/?probe=469b765fe0) | Aug 10, 2022 |
| ASUSTek   | G20AJ                       | [613f8a0c36](https://linux-hardware.org/?probe=613f8a0c36) | Aug 08, 2022 |
| Gigabyte  | X570 AORUS ELITE            | [f65ba77de3](https://linux-hardware.org/?probe=f65ba77de3) | Aug 07, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [7a60eede9a](https://linux-hardware.org/?probe=7a60eede9a) | Aug 04, 2022 |
| MSI       | B450-A PRO MAX              | [e142cf5c91](https://linux-hardware.org/?probe=e142cf5c91) | Aug 04, 2022 |
| MSI       | B450 TOMAHAWK MAX           | [7c4355417f](https://linux-hardware.org/?probe=7c4355417f) | Aug 03, 2022 |
| MSI       | X570-A PRO                  | [f034a02e69](https://linux-hardware.org/?probe=f034a02e69) | Aug 01, 2022 |
| MSI       | 970 GAMING                  | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| Dell      | 0J8H4R A01                  | [3d7d06475c](https://linux-hardware.org/?probe=3d7d06475c) | Jul 23, 2022 |
| ASUSTek   | PRIME B450-PLUS             | [7d6b6d93d3](https://linux-hardware.org/?probe=7d6b6d93d3) | Jul 21, 2022 |
| eMachines | EL1870                      | [58e76fb684](https://linux-hardware.org/?probe=58e76fb684) | Jul 19, 2022 |
| MSI       | X570-A PRO                  | [c9683ea265](https://linux-hardware.org/?probe=c9683ea265) | Jul 19, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Nobara 36 | 76       | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Nobara | 76       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 5.19.9-201.fsync.fc36.x86_64  | 8        | 10.39%  |
| 5.19.7-204.fsync.fc36.x86_64  | 7        | 9.09%   |
| 5.19.16-201.fsync.fc36.x86_64 | 7        | 9.09%   |
| 5.19.14-201.fsync.fc36.x86_64 | 7        | 9.09%   |
| 5.18.13-201.fsync.fc36.x86_64 | 7        | 9.09%   |
| 5.19.10-201.fsync.fc36.x86_64 | 6        | 7.79%   |
| 5.19.4-201.fsync.fc36.x86_64  | 4        | 5.19%   |
| 5.19.15-202.fsync.fc36.x86_64 | 4        | 5.19%   |
| 5.18.17-201.fsync.fc36.x86_64 | 4        | 5.19%   |
| 5.18.16-201.fsync.fc36.x86_64 | 4        | 5.19%   |
| 5.19.12-201.fsync.fc36.x86_64 | 3        | 3.9%    |
| 5.18.19-201.fsync.fc36.x86_64 | 3        | 3.9%    |
| 5.18.11-201.fsync.fc36.x86_64 | 3        | 3.9%    |
| 6.0.5-201.fsync.fc36.x86_64   | 2        | 2.6%    |
| 5.19.11-201.fsync.fc36.x86_64 | 2        | 2.6%    |
| 5.19.7-203.fsync.fc36.x86_64  | 1        | 1.3%    |
| 5.19.2-602.inttf.fc36.x86_64  | 1        | 1.3%    |
| 5.19.13-202.fsync.fc36.x86_64 | 1        | 1.3%    |
| 5.19.13-201.fsync.fc36.x86_64 | 1        | 1.3%    |
| 5.18.9-201.fsync.fc36.x86_64  | 1        | 1.3%    |
| 5.18.18-201.fsync.fc36.x86_64 | 1        | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19.9  | 8        | 10.39%  |
| 5.19.7  | 8        | 10.39%  |
| 5.19.16 | 7        | 9.09%   |
| 5.19.14 | 7        | 9.09%   |
| 5.18.13 | 7        | 9.09%   |
| 5.19.10 | 6        | 7.79%   |
| 5.19.4  | 4        | 5.19%   |
| 5.19.15 | 4        | 5.19%   |
| 5.18.17 | 4        | 5.19%   |
| 5.18.16 | 4        | 5.19%   |
| 5.19.12 | 3        | 3.9%    |
| 5.18.19 | 3        | 3.9%    |
| 5.18.11 | 3        | 3.9%    |
| 6.0.5   | 2        | 2.6%    |
| 5.19.13 | 2        | 2.6%    |
| 5.19.11 | 2        | 2.6%    |
| 5.19.2  | 1        | 1.3%    |
| 5.18.9  | 1        | 1.3%    |
| 5.18.18 | 1        | 1.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19    | 52       | 67.53%  |
| 5.18    | 23       | 29.87%  |
| 6.0     | 2        | 2.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 76       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 56       | 73.68%  |
| KDE5       | 19       | 25%     |
| X-Cinnamon | 1        | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 52       | 67.53%  |
| X11     | 25       | 32.47%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 65       | 85.53%  |
| GDM     | 7        | 9.21%   |
| SDDM    | 3        | 3.95%   |
| LightDM | 1        | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 43       | 55.84%  |
| en_GB   | 5        | 6.49%   |
| es_ES   | 4        | 5.19%   |
| en_CA   | 3        | 3.9%    |
| de_DE   | 3        | 3.9%    |
| fr_FR   | 2        | 2.6%    |
| es_MX   | 2        | 2.6%    |
| es_AR   | 2        | 2.6%    |
| en_AU   | 2        | 2.6%    |
| sk_SK   | 1        | 1.3%    |
| ru_RU   | 1        | 1.3%    |
| pt_BR   | 1        | 1.3%    |
| nl_NL   | 1        | 1.3%    |
| es_GT   | 1        | 1.3%    |
| es_EC   | 1        | 1.3%    |
| es_CO   | 1        | 1.3%    |
| en_NZ   | 1        | 1.3%    |
| cs_CZ   | 1        | 1.3%    |
| C       | 1        | 1.3%    |
| Unknown | 1        | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 54       | 71.05%  |
| BIOS | 22       | 28.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 50       | 65.79%  |
| Btrfs | 26       | 34.21%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 64       | 84.21%  |
| GPT     | 9        | 11.84%  |
| MBR     | 3        | 3.95%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 72       | 94.74%  |
| Yes       | 4        | 5.26%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 93.42%  |
| Yes       | 5        | 6.58%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 27.63%  |
| MSI                 | 16       | 21.05%  |
| Gigabyte Technology | 12       | 15.79%  |
| ASRock              | 9        | 11.84%  |
| Hewlett-Packard     | 6        | 7.89%   |
| Dell                | 5        | 6.58%   |
| Lenovo              | 1        | 1.32%   |
| Intel               | 1        | 1.32%   |
| eMachines           | 1        | 1.32%   |
| ECS                 | 1        | 1.32%   |
| Biostar             | 1        | 1.32%   |
| Alienware           | 1        | 1.32%   |
| Unknown             | 1        | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS PRIME A320M-K                   | 3        | 3.95%   |
| MSI MS-7C37                          | 2        | 2.63%   |
| MSI MS-7C02                          | 2        | 2.63%   |
| MSI MS-7B86                          | 2        | 2.63%   |
| MSI MS-7693                          | 2        | 2.63%   |
| Gigabyte B450M DS3H                  | 2        | 2.63%   |
| Dell OptiPlex 390                    | 2        | 2.63%   |
| MSI MS-7D25                          | 1        | 1.32%   |
| MSI MS-7C84                          | 1        | 1.32%   |
| MSI MS-7C35                          | 1        | 1.32%   |
| MSI MS-7B51                          | 1        | 1.32%   |
| MSI MS-7B17                          | 1        | 1.32%   |
| MSI MS-7A34                          | 1        | 1.32%   |
| MSI MS-7811                          | 1        | 1.32%   |
| MSI MS-7721                          | 1        | 1.32%   |
| Lenovo ThinkCentre M92p 3238E5U      | 1        | 1.32%   |
| Intel B75                            | 1        | 1.32%   |
| HP Pavilion Gaming Desktop TG01-0xxx | 1        | 1.32%   |
| HP Pavilion Desktop TP01-2xxx        | 1        | 1.32%   |
| HP EliteDesk 800 G5 Desktop Mini     | 1        | 1.32%   |
| HP EliteDesk 800 G2 SFF              | 1        | 1.32%   |
| HP EliteDesk 800 G1 SFF              | 1        | 1.32%   |
| HP Compaq dc5850 Small Form Factor   | 1        | 1.32%   |
| Gigabyte Z97-HD3                     | 1        | 1.32%   |
| Gigabyte Z590I VISION D              | 1        | 1.32%   |
| Gigabyte X570 I AORUS PRO WIFI       | 1        | 1.32%   |
| Gigabyte X570 AORUS ELITE            | 1        | 1.32%   |
| Gigabyte H270-Gaming 3               | 1        | 1.32%   |
| Gigabyte H110M-H                     | 1        | 1.32%   |
| Gigabyte EP45-UD3L                   | 1        | 1.32%   |
| Gigabyte AB350-Gaming 3              | 1        | 1.32%   |
| Gigabyte A320M-S2H                   | 1        | 1.32%   |
| Gigabyte 970A-DS3P                   | 1        | 1.32%   |
| eMachines EL1870                     | 1        | 1.32%   |
| ECS H61H2-CM                         | 1        | 1.32%   |
| Dell Precision WorkStation T3500     | 1        | 1.32%   |
| Dell OptiPlex 780                    | 1        | 1.32%   |
| Dell ASM100                          | 1        | 1.32%   |
| Biostar H410MH S2                    | 1        | 1.32%   |
| ASUS TUF Gaming X570-PRO WIFI II     | 1        | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 9        | 11.84%  |
| ASUS TUF              | 4        | 5.26%   |
| HP EliteDesk          | 3        | 3.95%   |
| Dell OptiPlex         | 3        | 3.95%   |
| MSI MS-7C37           | 2        | 2.63%   |
| MSI MS-7C02           | 2        | 2.63%   |
| MSI MS-7B86           | 2        | 2.63%   |
| MSI MS-7693           | 2        | 2.63%   |
| HP Pavilion           | 2        | 2.63%   |
| Gigabyte X570         | 2        | 2.63%   |
| Gigabyte B450M        | 2        | 2.63%   |
| ASUS ROG              | 2        | 2.63%   |
| MSI MS-7D25           | 1        | 1.32%   |
| MSI MS-7C84           | 1        | 1.32%   |
| MSI MS-7C35           | 1        | 1.32%   |
| MSI MS-7B51           | 1        | 1.32%   |
| MSI MS-7B17           | 1        | 1.32%   |
| MSI MS-7A34           | 1        | 1.32%   |
| MSI MS-7811           | 1        | 1.32%   |
| MSI MS-7721           | 1        | 1.32%   |
| Lenovo ThinkCentre    | 1        | 1.32%   |
| Intel B75             | 1        | 1.32%   |
| HP Compaq             | 1        | 1.32%   |
| Gigabyte Z97-HD3      | 1        | 1.32%   |
| Gigabyte Z590I        | 1        | 1.32%   |
| Gigabyte H270-Gaming  | 1        | 1.32%   |
| Gigabyte H110M-H      | 1        | 1.32%   |
| Gigabyte EP45-UD3L    | 1        | 1.32%   |
| Gigabyte AB350-Gaming | 1        | 1.32%   |
| Gigabyte A320M-S2H    | 1        | 1.32%   |
| Gigabyte 970A-DS3P    | 1        | 1.32%   |
| eMachines EL1870      | 1        | 1.32%   |
| ECS H61H2-CM          | 1        | 1.32%   |
| Dell Precision        | 1        | 1.32%   |
| Dell ASM100           | 1        | 1.32%   |
| Biostar H410MH        | 1        | 1.32%   |
| ASUS SABERTOOTH       | 1        | 1.32%   |
| ASUS PRO451459        | 1        | 1.32%   |
| ASUS P8Z68-V          | 1        | 1.32%   |
| ASUS H61M-K           | 1        | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 17       | 22.37%  |
| 2018 | 10       | 13.16%  |
| 2017 | 8        | 10.53%  |
| 2021 | 7        | 9.21%   |
| 2014 | 6        | 7.89%   |
| 2013 | 6        | 7.89%   |
| 2011 | 5        | 6.58%   |
| 2020 | 4        | 5.26%   |
| 2016 | 4        | 5.26%   |
| 2012 | 3        | 3.95%   |
| 2015 | 2        | 2.63%   |
| 2008 | 2        | 2.63%   |
| 2022 | 1        | 1.32%   |
| 2010 | 1        | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 76       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 76       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 76       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 30       | 39.47%  |
| 32.01-64.0  | 16       | 21.05%  |
| 8.01-16.0   | 16       | 21.05%  |
| 4.01-8.0    | 7        | 9.21%   |
| 3.01-4.0    | 5        | 6.58%   |
| 24.01-32.0  | 1        | 1.32%   |
| 64.01-256.0 | 1        | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 35       | 44.87%  |
| 3.01-4.0   | 21       | 26.92%  |
| 2.01-3.0   | 10       | 12.82%  |
| 8.01-16.0  | 7        | 8.97%   |
| 1.01-2.0   | 3        | 3.85%   |
| 24.01-32.0 | 1        | 1.28%   |
| 16.01-24.0 | 1        | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 31.17%  |
| 2      | 21       | 27.27%  |
| 3      | 17       | 22.08%  |
| 5      | 9        | 11.69%  |
| 4      | 4        | 5.19%   |
| 10     | 1        | 1.3%    |
| 6      | 1        | 1.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 76.32%  |
| Yes       | 18       | 23.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 76       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 41       | 53.95%  |
| No        | 35       | 46.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 53.25%  |
| Yes       | 36       | 46.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 25       | 32.89%  |
| Germany      | 5        | 6.58%   |
| France       | 5        | 6.58%   |
| Canada       | 5        | 6.58%   |
| UK           | 3        | 3.95%   |
| Spain        | 3        | 3.95%   |
| Argentina    | 3        | 3.95%   |
| Serbia       | 2        | 2.63%   |
| Netherlands  | 2        | 2.63%   |
| Mexico       | 2        | 2.63%   |
| Chile        | 2        | 2.63%   |
| Brazil       | 2        | 2.63%   |
| Australia    | 2        | 2.63%   |
| Venezuela    | 1        | 1.32%   |
| South Korea  | 1        | 1.32%   |
| South Africa | 1        | 1.32%   |
| Slovakia     | 1        | 1.32%   |
| Russia       | 1        | 1.32%   |
| Norway       | 1        | 1.32%   |
| New Zealand  | 1        | 1.32%   |
| Hungary      | 1        | 1.32%   |
| Guatemala    | 1        | 1.32%   |
| Georgia      | 1        | 1.32%   |
| Ecuador      | 1        | 1.32%   |
| Czechia      | 1        | 1.32%   |
| Croatia      | 1        | 1.32%   |
| Colombia     | 1        | 1.32%   |
| Belgium      | 1        | 1.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Philadelphia      | 2        | 2.6%    |
| Atlanta           | 2        | 2.6%    |
| Zagreb            | 1        | 1.3%    |
| Wooster           | 1        | 1.3%    |
| Wiesbaden         | 1        | 1.3%    |
| Wellington        | 1        | 1.3%    |
| Waldorf           | 1        | 1.3%    |
| Vineland          | 1        | 1.3%    |
| Villa Nueva       | 1        | 1.3%    |
| Tamworth          | 1        | 1.3%    |
| Szeged            | 1        | 1.3%    |
| Sao Paulo         | 1        | 1.3%    |
| Santiago          | 1        | 1.3%    |
| San Jose          | 1        | 1.3%    |
| San Antonio       | 1        | 1.3%    |
| Salon-de-Provence | 1        | 1.3%    |
| Rotterdam         | 1        | 1.3%    |
| Raleigh           | 1        | 1.3%    |
| Quito             | 1        | 1.3%    |
| Prague            | 1        | 1.3%    |
| Philipsburg       | 1        | 1.3%    |
| Paris             | 1        | 1.3%    |
| Osa               | 1        | 1.3%    |
| North Vancouver   | 1        | 1.3%    |
| Mount Pleasant    | 1        | 1.3%    |
| Mendoza           | 1        | 1.3%    |
| Melbourne         | 1        | 1.3%    |
| Martigues         | 1        | 1.3%    |
| Marin             | 1        | 1.3%    |
| Lünen            | 1        | 1.3%    |
| Loznica           | 1        | 1.3%    |
| Los Mochis        | 1        | 1.3%    |
| Lake Elsinore     | 1        | 1.3%    |
| La Serena         | 1        | 1.3%    |
| Koblenz           | 1        | 1.3%    |
| K'alak'i T'bilisi | 1        | 1.3%    |
| Johannesburg      | 1        | 1.3%    |
| Istres            | 1        | 1.3%    |
| Hermosillo        | 1        | 1.3%    |
| Grande Prairie    | 1        | 1.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 31       | 43     | 19.87%  |
| Samsung Electronics       | 27       | 44     | 17.31%  |
| Seagate                   | 20       | 26     | 12.82%  |
| Crucial                   | 14       | 18     | 8.97%   |
| Toshiba                   | 12       | 12     | 7.69%   |
| Sandisk                   | 11       | 11     | 7.05%   |
| Kingston                  | 8        | 10     | 5.13%   |
| Phison                    | 4        | 5      | 2.56%   |
| PNY                       | 3        | 6      | 1.92%   |
| Phison Electronics        | 3        | 3      | 1.92%   |
| Intel                     | 2        | 3      | 1.28%   |
| Hitachi                   | 2        | 2      | 1.28%   |
| XPG                       | 1        | 1      | 0.64%   |
| Verbatim                  | 1        | 1      | 0.64%   |
| Unknown                   | 1        | 1      | 0.64%   |
| Team                      | 1        | 1      | 0.64%   |
| SuperSSpeed               | 1        | 1      | 0.64%   |
| SPCC                      | 1        | 1      | 0.64%   |
| SK hynix                  | 1        | 1      | 0.64%   |
| Silicon Motion            | 1        | 1      | 0.64%   |
| Realtek Semiconductor     | 1        | 1      | 0.64%   |
| OCZ                       | 1        | 1      | 0.64%   |
| MyDigitalSSD              | 1        | 1      | 0.64%   |
| Mushkin                   | 1        | 1      | 0.64%   |
| Micron/Crucial Technology | 1        | 1      | 0.64%   |
| Micron Technology         | 1        | 1      | 0.64%   |
| KIOXIA                    | 1        | 1      | 0.64%   |
| JMicron Technology        | 1        | 1      | 0.64%   |
| China                     | 1        | 1      | 0.64%   |
| ADATA Technology          | 1        | 1      | 0.64%   |
| A-DATA Technology         | 1        | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Toshiba HDWD110 1TB              | 4        | 2.14%   |
| WDC WDBNCE5000PNC 500GB SSD      | 3        | 1.6%    |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 1.6%    |
| Toshiba DT01ACA100 1TB           | 3        | 1.6%    |
| Samsung SSD 860 EVO 500GB        | 3        | 1.6%    |
| Samsung SSD 850 EVO 500GB        | 3        | 1.6%    |
| Phison E12 NVMe Controller 2TB   | 3        | 1.6%    |
| WDC WDS480G2G0A-00JH30 480GB SSD | 2        | 1.07%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 1.07%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 1.07%   |
| WDC WD5000BEVT-75ZAT0 500GB      | 2        | 1.07%   |
| Seagate ST2000DX002-2DV164 2TB   | 2        | 1.07%   |
| SanDisk SSD PLUS 240GB           | 2        | 1.07%   |
| Samsung SSD 980 500GB            | 2        | 1.07%   |
| Samsung SSD 860 EVO 1TB          | 2        | 1.07%   |
| Samsung SSD 850 EVO 250GB        | 2        | 1.07%   |
| Samsung NVMe SSD Drive 1TB       | 2        | 1.07%   |
| PNY CS900 500GB SSD              | 2        | 1.07%   |
| Phison NVMe SSD Drive 2TB        | 2        | 1.07%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 1.07%   |
| Kingston NVMe SSD Drive 500GB    | 2        | 1.07%   |
| Intel SSD 660P Series 1024GB     | 2        | 1.07%   |
| Crucial CT240BX500SSD1 240GB     | 2        | 1.07%   |
| Crucial CT1000MX500SSD1 1TB      | 2        | 1.07%   |
| Crucial CT1000BX500SSD1 1TB      | 2        | 1.07%   |
| XPG SPECTRIX S40G 256GB          | 1        | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.53%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.53%   |
| WDC WD6400AAKS-65A7B2 640GB      | 1        | 0.53%   |
| WDC WD40PURZ-74AKKY0 4TB         | 1        | 0.53%   |
| WDC WD4005FZBX-00K5WB0 4TB       | 1        | 0.53%   |
| WDC WD30EZAZ-00SF3B0 3TB         | 1        | 0.53%   |
| WDC WD2500JS-22NCB1 250GB        | 1        | 0.53%   |
| WDC WD20EZBX-00AYRA0 2TB         | 1        | 0.53%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 1        | 0.53%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.53%   |
| WDC WD2002FAEX-007BA0 2TB        | 1        | 0.53%   |
| WDC WD1600AAJS-08L7A0 160GB      | 1        | 0.53%   |
| WDC WD1600AABS-00H4A0 160GB      | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 31     | 37.7%   |
| Seagate             | 20       | 24     | 32.79%  |
| Toshiba             | 11       | 11     | 18.03%  |
| Samsung Electronics | 5        | 7      | 8.2%    |
| Hitachi             | 2        | 2      | 3.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 21     | 24.64%  |
| Crucial             | 14       | 18     | 20.29%  |
| WDC                 | 11       | 12     | 15.94%  |
| SanDisk             | 7        | 7      | 10.14%  |
| Kingston            | 6        | 8      | 8.7%    |
| PNY                 | 3        | 6      | 4.35%   |
| Verbatim            | 1        | 1      | 1.45%   |
| Toshiba             | 1        | 1      | 1.45%   |
| Team                | 1        | 1      | 1.45%   |
| SuperSSpeed         | 1        | 1      | 1.45%   |
| SPCC                | 1        | 1      | 1.45%   |
| Seagate             | 1        | 1      | 1.45%   |
| OCZ                 | 1        | 1      | 1.45%   |
| MyDigitalSSD        | 1        | 1      | 1.45%   |
| Mushkin             | 1        | 1      | 1.45%   |
| China               | 1        | 1      | 1.45%   |
| A-DATA Technology   | 1        | 1      | 1.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 52       | 83     | 39.39%  |
| HDD     | 48       | 75     | 36.36%  |
| NVMe    | 30       | 42     | 22.73%  |
| MMC     | 1        | 1      | 0.76%   |
| Unknown | 1        | 1      | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 69       | 155    | 66.35%  |
| NVMe | 29       | 41     | 27.88%  |
| SAS  | 5        | 5      | 4.81%   |
| MMC  | 1        | 1      | 0.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 50       | 72     | 43.1%   |
| 0.51-1.0   | 40       | 54     | 34.48%  |
| 1.01-2.0   | 15       | 21     | 12.93%  |
| 3.01-4.0   | 5        | 5      | 4.31%   |
| 2.01-3.0   | 3        | 3      | 2.59%   |
| 10.01-20.0 | 2        | 2      | 1.72%   |
| 4.01-10.0  | 1        | 1      | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 19       | 25%     |
| 251-500        | 18       | 23.68%  |
| 1001-2000      | 15       | 19.74%  |
| 501-1000       | 10       | 13.16%  |
| More than 3000 | 6        | 7.89%   |
| 2001-3000      | 4        | 5.26%   |
| 51-100         | 2        | 2.63%   |
| 21-50          | 1        | 1.32%   |
| 1-20           | 1        | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 22       | 28.57%  |
| 1-20           | 20       | 25.97%  |
| 501-1000       | 9        | 11.69%  |
| 51-100         | 9        | 11.69%  |
| 251-500        | 6        | 7.79%   |
| 101-250        | 6        | 7.79%   |
| 2001-3000      | 3        | 3.9%    |
| More than 3000 | 1        | 1.3%    |
| 1001-2000      | 1        | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB         | 2        | 2      | 28.57%  |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 1      | 14.29%  |
| Seagate ST2000DX002-2DV164 2TB      | 1        | 1      | 14.29%  |
| Seagate ST1000DM003-9YN162 1TB      | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 970 EVO 1TB | 1        | 1      | 14.29%  |
| Samsung Electronics HD161GJ 160GB   | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 42.86%  |
| Seagate             | 2        | 2      | 28.57%  |
| Samsung Electronics | 2        | 2      | 28.57%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 50%     |
| Seagate             | 2        | 2      | 33.33%  |
| Samsung Electronics | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 6      | 85.71%  |
| NVMe | 1        | 1      | 14.29%  |

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
| Detected | 64       | 163    | 79.01%  |
| Works    | 10       | 32     | 12.35%  |
| Malfunc  | 7        | 7      | 8.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 40       | 33.61%  |
| Intel                       | 36       | 30.25%  |
| Samsung Electronics         | 12       | 10.08%  |
| Phison Electronics          | 7        | 5.88%   |
| ASMedia Technology          | 6        | 5.04%   |
| SanDisk                     | 4        | 3.36%   |
| Realtek Semiconductor       | 2        | 1.68%   |
| Kingston Technology Company | 2        | 1.68%   |
| JMicron Technology          | 2        | 1.68%   |
| SK hynix                    | 1        | 0.84%   |
| Silicon Motion              | 1        | 0.84%   |
| Silicon Image               | 1        | 0.84%   |
| Micron/Crucial Technology   | 1        | 0.84%   |
| Micron Technology           | 1        | 0.84%   |
| Marvell Technology Group    | 1        | 0.84%   |
| KIOXIA                      | 1        | 0.84%   |
| ADATA Technology            | 1        | 0.84%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27       | 19.15%  |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 7.8%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 4.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 4.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 3.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 3.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 2.84%   |
| AMD FCH SATA Controller D                                                               | 4        | 2.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 2.13%   |
| Phison E12 NVMe Controller                                                              | 3        | 2.13%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 2.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 2.13%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.13%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 1.42%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2        | 1.42%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.42%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.42%   |
| Intel SSD 660P Series                                                                   | 2        | 1.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.42%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.42%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.42%   |
| SK hynix Gold P31 SSD                                                                   | 1        | 0.71%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.71%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.71%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.71%   |
| SanDisk WD Blue SN570 NVMe SSD                                                          | 1        | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.71%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.71%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.71%   |
| Samsung NVMe SSD Controller 172X                                                        | 1        | 0.71%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.71%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 1        | 0.71%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 70       | 64.22%  |
| NVMe | 29       | 26.61%  |
| IDE  | 7        | 6.42%   |
| RAID | 3        | 2.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 40       | 52.63%  |
| Intel  | 36       | 47.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 5.26%   |
| AMD FX-8350 Eight-Core Processor            | 4        | 5.26%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 3.95%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 3.95%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 3.95%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 2.63%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 2.63%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 2.63%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 2.63%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 2.63%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 2.63%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 2.63%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 2.63%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 2.63%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 1.32%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1        | 1.32%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 1.32%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.32%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 1.32%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.32%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.32%   |
| Intel Core i7-10700F CPU @ 2.90GHz          | 1        | 1.32%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 1        | 1.32%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.32%   |
| Intel Core i5-7600 CPU @ 3.50GHz            | 1        | 1.32%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.32%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.32%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 1.32%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.32%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1        | 1.32%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.32%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.32%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.32%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.32%   |
| Intel Celeron CPU G3900 @ 2.80GHz           | 1        | 1.32%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1        | 1.32%   |
| Intel 12th Gen Core i5-12600K               | 1        | 1.32%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz      | 1        | 1.32%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 1        | 1.32%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 1        | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| AMD Ryzen 5          | 19       | 25%     |
| Intel Core i5        | 10       | 13.16%  |
| Intel Core i7        | 8        | 10.53%  |
| Intel Core i3        | 6        | 7.89%   |
| AMD Ryzen 9          | 6        | 7.89%   |
| AMD FX               | 5        | 6.58%   |
| Other                | 3        | 3.95%   |
| AMD Ryzen 7          | 3        | 3.95%   |
| AMD Ryzen 3          | 3        | 3.95%   |
| Intel Xeon           | 2        | 2.63%   |
| Intel Core i9        | 2        | 2.63%   |
| Intel Core 2 Duo     | 2        | 2.63%   |
| Intel Pentium        | 1        | 1.32%   |
| Intel Celeron        | 1        | 1.32%   |
| Intel Atom           | 1        | 1.32%   |
| AMD Phenom II X6     | 1        | 1.32%   |
| AMD Athlon X4        | 1        | 1.32%   |
| AMD Athlon Dual Core | 1        | 1.32%   |
| AMD A10              | 1        | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 24       | 31.58%  |
| 4      | 24       | 31.58%  |
| 2      | 14       | 18.42%  |
| 8      | 6        | 7.89%   |
| 12     | 5        | 6.58%   |
| 16     | 1        | 1.32%   |
| 10     | 1        | 1.32%   |
| 3      | 1        | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 57       | 75%     |
| 1      | 19       | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 76       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 10       | 13.16%  |
| 0x306c3    | 7        | 9.21%   |
| 0x306a9    | 5        | 6.58%   |
| 0x0800820d | 5        | 6.58%   |
| 0x06000822 | 5        | 6.58%   |
| 0x206a7    | 4        | 5.26%   |
| 0x08001138 | 4        | 5.26%   |
| Unknown    | 4        | 5.26%   |
| 0x906ea    | 3        | 3.95%   |
| 0x506e3    | 3        | 3.95%   |
| 0x0a201016 | 3        | 3.95%   |
| 0x08108109 | 3        | 3.95%   |
| 0x906ec    | 2        | 2.63%   |
| 0x1067a    | 2        | 2.63%   |
| 0x0a50000c | 2        | 2.63%   |
| 0x0a201204 | 2        | 2.63%   |
| 0xa0671    | 1        | 1.32%   |
| 0xa0655    | 1        | 1.32%   |
| 0xa0653    | 1        | 1.32%   |
| 0x906e9    | 1        | 1.32%   |
| 0x90672    | 1        | 1.32%   |
| 0x406c4    | 1        | 1.32%   |
| 0x106a5    | 1        | 1.32%   |
| 0x0a50000d | 1        | 1.32%   |
| 0x08108102 | 1        | 1.32%   |
| 0x06003106 | 1        | 1.32%   |
| 0x06001119 | 1        | 1.32%   |
| 0x010000bf | 1        | 1.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 10       | 13.16%  |
| Zen+             | 9        | 11.84%  |
| Zen 3            | 8        | 10.53%  |
| KabyLake         | 7        | 9.21%   |
| Haswell          | 7        | 9.21%   |
| Piledriver       | 6        | 7.89%   |
| SandyBridge      | 5        | 6.58%   |
| IvyBridge        | 5        | 6.58%   |
| Zen              | 4        | 5.26%   |
| Skylake          | 3        | 3.95%   |
| Penryn           | 2        | 2.63%   |
| CometLake        | 2        | 2.63%   |
| Steamroller      | 1        | 1.32%   |
| Silvermont       | 1        | 1.32%   |
| Nehalem          | 1        | 1.32%   |
| K8 Hammer        | 1        | 1.32%   |
| K10              | 1        | 1.32%   |
| Icelake          | 1        | 1.32%   |
| Alderlake Hybrid | 1        | 1.32%   |
| Unknown          | 1        | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 37       | 46.25%  |
| AMD    | 31       | 38.75%  |
| Intel  | 12       | 15%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10       | 12.35%  |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 3        | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 3.7%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 3        | 3.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2        | 2.47%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2        | 2.47%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 2        | 2.47%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 2.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 2.47%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2        | 2.47%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 2        | 2.47%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 2        | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 2.47%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 2.47%   |
| Intel HD Graphics 530                                                                    | 2        | 2.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 2.47%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2        | 2.47%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2        | 2.47%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 2.47%   |
| AMD Cezanne                                                                              | 2        | 2.47%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 1.23%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 1.23%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 1.23%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 1.23%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 1.23%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.23%   |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                                      | 1        | 1.23%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1        | 1.23%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.23%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1        | 1.23%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1        | 1.23%   |
| Nvidia GK106 [GeForce GTX 650 OEM]                                                       | 1        | 1.23%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 1.23%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1        | 1.23%   |
| Nvidia GF106GL [Quadro 2000]                                                             | 1        | 1.23%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1        | 1.23%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 1        | 1.23%   |
| Nvidia G96 [GeForce 9500 GS]                                                             | 1        | 1.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 36       | 47.37%  |
| 1 x AMD      | 29       | 38.16%  |
| 1 x Intel    | 9        | 11.84%  |
| 2 x AMD      | 1        | 1.32%   |
| AMD + Nvidia | 1        | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 47       | 61.84%  |
| Proprietary | 28       | 36.84%  |
| Unknown     | 1        | 1.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 34.21%  |
| 7.01-8.0   | 15       | 19.74%  |
| 3.01-4.0   | 9        | 11.84%  |
| 1.01-2.0   | 9        | 11.84%  |
| 8.01-16.0  | 6        | 7.89%   |
| 0.51-1.0   | 5        | 6.58%   |
| 0.01-0.5   | 4        | 5.26%   |
| 5.01-6.0   | 1        | 1.32%   |
| 2.01-3.0   | 1        | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 15.58%  |
| Goldstar             | 8        | 10.39%  |
| Acer                 | 7        | 9.09%   |
| Dell                 | 6        | 7.79%   |
| Vizio                | 5        | 6.49%   |
| Hewlett-Packard      | 5        | 6.49%   |
| BenQ                 | 5        | 6.49%   |
| AOC                  | 4        | 5.19%   |
| Philips              | 3        | 3.9%    |
| MSI                  | 3        | 3.9%    |
| ASUSTek Computer     | 3        | 3.9%    |
| Ancor Communications | 3        | 3.9%    |
| ViewSonic            | 2        | 2.6%    |
| Sony                 | 2        | 2.6%    |
| Sceptre Tech         | 2        | 2.6%    |
| Lenovo               | 2        | 2.6%    |
| Toshiba              | 1        | 1.3%    |
| SNC                  | 1        | 1.3%    |
| SFX                  | 1        | 1.3%    |
| MStar                | 1        | 1.3%    |
| GDH                  | 1        | 1.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ASUSTek Computer PA278QV AUS2700 2560x1440 597x336mm 27.0-inch          | 2        | 2.38%   |
| Vizio VX42L HDTV10A VIZ0030 1280x720 930x523mm 42.0-inch                | 1        | 1.19%   |
| Vizio M50Q6-J01 VIZ1039 3840x2160 1095x616mm 49.5-inch                  | 1        | 1.19%   |
| Vizio E500i-B1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 1        | 1.19%   |
| Vizio E3D420VX VIZ0092 1920x1080 930x523mm 42.0-inch                    | 1        | 1.19%   |
| Vizio D24h-G9 VIZ1028 1366x768 521x293mm 23.5-inch                      | 1        | 1.19%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch           | 1        | 1.19%   |
| ViewSonic VX3218-PC-mhd VSCEB3A 1920x1080 609x348mm 27.6-inch           | 1        | 1.19%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch                | 1        | 1.19%   |
| Sony TV SNY8F03 1360x768                                                | 1        | 1.19%   |
| Sony TV *00 SNYF303 1920x1080 1439x809mm 65.0-inch                      | 1        | 1.19%   |
| SNC SKP_E20-32 SNC3200 1920x1080 477x268mm 21.5-inch                    | 1        | 1.19%   |
| SFX HDMI2.0 KVM SFX0100 1920x1080 708x398mm 32.0-inch                   | 1        | 1.19%   |
| Sceptre Tech Sceptre Y40 SPT0FCD 2560x1440 852x480mm 38.5-inch          | 1        | 1.19%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch          | 1        | 1.19%   |
| Sceptre Tech Sceptre M27 SPT0ACD 1920x1080 598x336mm 27.0-inch          | 1        | 1.19%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch       | 1        | 1.19%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch       | 1        | 1.19%   |
| Samsung Electronics SyncMaster SAM0422 1920x1200 518x324mm 24.1-inch    | 1        | 1.19%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 1        | 1.19%   |
| Samsung Electronics SyncMaster SAM0168 1280x1024 338x270mm 17.0-inch    | 1        | 1.19%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 1        | 1.19%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch       | 1        | 1.19%   |
| Samsung Electronics LCD Monitor SAM7129 3840x2160 1020x570mm 46.0-inch  | 1        | 1.19%   |
| Samsung Electronics LCD Monitor SAM0FA5 3840x2160 1872x1053mm 84.6-inch | 1        | 1.19%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch   | 1        | 1.19%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch    | 1        | 1.19%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch  | 1        | 1.19%   |
| Samsung Electronics C34H89x SAM0E26 3440x1440 797x333mm 34.0-inch       | 1        | 1.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1        | 1.19%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 1        | 1.19%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch                 | 1        | 1.19%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                | 1        | 1.19%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                 | 1        | 1.19%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                        | 1        | 1.19%   |
| MSI G32C4 MSI3DA6 1920x1080 698x393mm 31.5-inch                         | 1        | 1.19%   |
| MSI G273 MSI3CA7 1920x1080 597x336mm 27.0-inch                          | 1        | 1.19%   |
| MSI G24C MSI3EA0 1920x1080 521x293mm 23.5-inch                          | 1        | 1.19%   |
| MSI AG321CQR MSI3DB4 2560x1440 700x390mm 31.5-inch                      | 1        | 1.19%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch                | 1        | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 38       | 49.35%  |
| 3840x2160 (4K)     | 13       | 16.88%  |
| 2560x1440 (QHD)    | 12       | 15.58%  |
| 1680x1050 (WSXGA+) | 3        | 3.9%    |
| 3440x1440          | 2        | 2.6%    |
| 1600x900 (HD+)     | 2        | 2.6%    |
| 1366x768 (WXGA)    | 2        | 2.6%    |
| 2560x1080          | 1        | 1.3%    |
| 1920x1200 (WUXGA)  | 1        | 1.3%    |
| 1440x900 (WXGA+)   | 1        | 1.3%    |
| 1360x768           | 1        | 1.3%    |
| 1280x1024 (SXGA)   | 1        | 1.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 19       | 23.17%  |
| 23      | 10       | 12.2%   |
| 24      | 9        | 10.98%  |
| 21      | 9        | 10.98%  |
| 31      | 8        | 9.76%   |
| 84      | 2        | 2.44%   |
| 52      | 2        | 2.44%   |
| 38      | 2        | 2.44%   |
| 34      | 2        | 2.44%   |
| 22      | 2        | 2.44%   |
| 19      | 2        | 2.44%   |
| 75      | 1        | 1.22%   |
| 72      | 1        | 1.22%   |
| 69      | 1        | 1.22%   |
| 60      | 1        | 1.22%   |
| 49      | 1        | 1.22%   |
| 48      | 1        | 1.22%   |
| 42      | 1        | 1.22%   |
| 40      | 1        | 1.22%   |
| 33      | 1        | 1.22%   |
| 32      | 1        | 1.22%   |
| 29      | 1        | 1.22%   |
| 20      | 1        | 1.22%   |
| 18      | 1        | 1.22%   |
| 17      | 1        | 1.22%   |
| Unknown | 1        | 1.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 32       | 41.03%  |
| 401-500     | 15       | 19.23%  |
| 601-700     | 11       | 14.1%   |
| 1501-2000   | 5        | 6.41%   |
| 1001-1500   | 5        | 6.41%   |
| 701-800     | 4        | 5.13%   |
| 801-900     | 3        | 3.85%   |
| 301-350     | 1        | 1.28%   |
| 901-1000    | 1        | 1.28%   |
| Unknown     | 1        | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 57       | 85.07%  |
| 16/10 | 6        | 8.96%   |
| 21/9  | 3        | 4.48%   |
| 5/4   | 1        | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 26       | 32.5%   |
| 301-350        | 19       | 23.75%  |
| 351-500        | 12       | 15%     |
| More than 1000 | 10       | 12.5%   |
| 151-200        | 5        | 6.25%   |
| 501-1000       | 4        | 5%      |
| 251-300        | 2        | 2.5%    |
| 141-150        | 1        | 1.25%   |
| Unknown        | 1        | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 44       | 58.67%  |
| 101-120 | 17       | 22.67%  |
| 1-50    | 8        | 10.67%  |
| 121-160 | 3        | 4%      |
| 161-240 | 2        | 2.67%   |
| Unknown | 1        | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 52       | 68.42%  |
| 2     | 19       | 25%     |
| 0     | 3        | 3.95%   |
| 3     | 2        | 2.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 49       | 43.75%  |
| Intel                 | 35       | 31.25%  |
| TP-Link               | 7        | 6.25%   |
| Qualcomm Atheros      | 6        | 5.36%   |
| Broadcom              | 3        | 2.68%   |
| Microsoft             | 2        | 1.79%   |
| MediaTek              | 2        | 1.79%   |
| T & A Mobile Phones   | 1        | 0.89%   |
| Ralink Technology     | 1        | 0.89%   |
| Ralink                | 1        | 0.89%   |
| ICS Advent            | 1        | 0.89%   |
| Holtek Semiconductor  | 1        | 0.89%   |
| D-Link                | 1        | 0.89%   |
| Broadcom Limited      | 1        | 0.89%   |
| ASUSTek Computer      | 1        | 0.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42       | 32.81%  |
| Intel Wi-Fi 6 AX200                                               | 14       | 10.94%  |
| Intel I211 Gigabit Network Connection                             | 8        | 6.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 3.91%   |
| Intel Ethernet Controller I225-V                                  | 4        | 3.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 2.34%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.34%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2        | 1.56%   |
| TP-Link 802.11ac NIC                                              | 2        | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.56%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.56%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 1.56%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.78%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.78%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 1        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 0.78%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1        | 0.78%   |
| Realtek 802.11ac NIC                                              | 1        | 0.78%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.78%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 0.78%   |
| Microsoft Wireless XBox Controller Dongle                         | 1        | 0.78%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1        | 0.78%   |
| Intel Wireless 7265                                               | 1        | 0.78%   |
| Intel Wireless 3165                                               | 1        | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.78%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 17       | 37.78%  |
| Realtek Semiconductor | 10       | 22.22%  |
| TP-Link               | 7        | 15.56%  |
| Microsoft             | 2        | 4.44%   |
| MediaTek              | 2        | 4.44%   |
| Broadcom              | 2        | 4.44%   |
| Ralink Technology     | 1        | 2.22%   |
| Ralink                | 1        | 2.22%   |
| Qualcomm Atheros      | 1        | 2.22%   |
| D-Link                | 1        | 2.22%   |
| ASUSTek Computer      | 1        | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 14       | 31.11%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 2        | 4.44%   |
| TP-Link 802.11ac NIC                                          | 2        | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2        | 4.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 2        | 4.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2        | 4.44%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 2        | 4.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1        | 2.22%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 1        | 2.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1        | 2.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1        | 2.22%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1        | 2.22%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1        | 2.22%   |
| Realtek 802.11ac NIC                                          | 1        | 2.22%   |
| Ralink MT7601U Wireless Adapter                               | 1        | 2.22%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                     | 1        | 2.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1        | 2.22%   |
| Microsoft Xbox 360 Wireless Adapter                           | 1        | 2.22%   |
| Microsoft Wireless XBox Controller Dongle                     | 1        | 2.22%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1        | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1        | 2.22%   |
| Intel Wireless 7265                                           | 1        | 2.22%   |
| Intel Wireless 3165                                           | 1        | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1        | 2.22%   |
| D-Link 802.11ac NIC                                           | 1        | 2.22%   |
| ASUS 802.11ac WLAN                                            | 1        | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 47       | 58.02%  |
| Intel                 | 25       | 30.86%  |
| Qualcomm Atheros      | 5        | 6.17%   |
| T & A Mobile Phones   | 1        | 1.23%   |
| ICS Advent            | 1        | 1.23%   |
| Broadcom Limited      | 1        | 1.23%   |
| Broadcom              | 1        | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42       | 51.22%  |
| Intel I211 Gigabit Network Connection                             | 8        | 9.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 6.1%    |
| Intel Ethernet Controller I225-V                                  | 4        | 4.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 3.66%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 3.66%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.44%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.44%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 1        | 1.22%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1        | 1.22%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.22%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.22%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.22%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.22%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.22%   |
| ICS Advent 10/100M LAN                                            | 1        | 1.22%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.22%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1        | 1.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 76       | 64.41%  |
| WiFi     | 41       | 34.75%  |
| Unknown  | 1        | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 59       | 71.95%  |
| WiFi     | 23       | 28.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 60.53%  |
| 2     | 29       | 38.16%  |
| 3     | 1        | 1.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 47       | 61.04%  |
| Yes  | 30       | 38.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 17       | 47.22%  |
| Cambridge Silicon Radio | 6        | 16.67%  |
| Realtek Semiconductor   | 3        | 8.33%   |
| IMC Networks            | 2        | 5.56%   |
| Broadcom                | 2        | 5.56%   |
| ASUSTek Computer        | 2        | 5.56%   |
| TP-Link                 | 1        | 2.78%   |
| MediaTek                | 1        | 2.78%   |
| Foxconn / Hon Hai       | 1        | 2.78%   |
| Unknown                 | 1        | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 14       | 38.89%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 16.67%  |
| Realtek Bluetooth Radio                             | 2        | 5.56%   |
| Intel Bluetooth wireless interface                  | 2        | 5.56%   |
| ASUS ASUS USB-BT500                                 | 2        | 5.56%   |
| TP-Link TPuLink UB500 Adapter                       | 1        | 2.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 2.78%   |
| MediaTek Wireless_Device                            | 1        | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2.78%   |
| IMC Networks Wireless_Device                        | 1        | 2.78%   |
| IMC Networks Bluetooth Radio                        | 1        | 2.78%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 2.78%   |
| Broadcom Bluetooth Device                           | 1        | 2.78%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 2.78%   |
| Unknown                                             | 1        | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| AMD                    | 47       | 31.33%  |
| Nvidia                 | 36       | 24%     |
| Intel                  | 34       | 22.67%  |
| C-Media Electronics    | 6        | 4%      |
| Razer USA              | 3        | 2%      |
| Plantronics            | 3        | 2%      |
| Samson Technologies    | 2        | 1.33%   |
| Kingston Technology    | 2        | 1.33%   |
| JMTek                  | 2        | 1.33%   |
| Focusrite-Novation     | 2        | 1.33%   |
| Creative Technology    | 2        | 1.33%   |
| Creative Labs          | 2        | 1.33%   |
| SteelSeries ApS        | 1        | 0.67%   |
| Realtek Semiconductor  | 1        | 0.67%   |
| Logitech               | 1        | 0.67%   |
| Generalplus Technology | 1        | 0.67%   |
| Elgato Systems         | 1        | 0.67%   |
| Corsair                | 1        | 0.67%   |
| Blue Microphones       | 1        | 0.67%   |
| Audio-Technica         | 1        | 0.67%   |
| ASUSTek Computer       | 1        | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 15       | 8.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10       | 5.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9        | 5.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 3.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 3.98%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 3.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 2.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 2.27%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.7%    |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.7%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 1.14%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.14%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.14%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 1.14%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.14%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1.14%   |
| JMTek USB PnP Audio Device                                                 | 2        | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 1.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.14%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.14%   |
| C-Media Electronics Blue Snowball                                          | 2        | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.14%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 1.14%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.14%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 1        | 0.57%   |
| Samson Technologies Q2U handheld mic with XLR                              | 1        | 0.57%   |
| Samson Technologies G-Track Pro microphone                                 | 1        | 0.57%   |
| Realtek Semiconductor Realtek Audio USB                                    | 1        | 0.57%   |
| Razer USA Razer USB Sound Card                                             | 1        | 0.57%   |
| Razer USA Razer Seiren Mini                                                | 1        | 0.57%   |
| Razer USA Razer Kraken V3 X                                                | 1        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 4        | 28.57%  |
| Unknown             | 2        | 14.29%  |
| G.Skill             | 2        | 14.29%  |
| Team                | 1        | 7.14%   |
| Samsung Electronics | 1        | 7.14%   |
| Ramaxel Technology  | 1        | 7.14%   |
| Kingston            | 1        | 7.14%   |
| Crucial             | 1        | 7.14%   |
| Asgard              | 1        | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 2        | 13.33%  |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                | 1        | 6.67%   |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s   | 1        | 6.67%   |
| Team RAM TEAMGROUP-UD3 8GB DIMM DDR3 1600MT/s            | 1        | 6.67%   |
| Samsung RAM M3 78T2863QZS-CF7 1GB DIMM DDR2 800MT/s      | 1        | 6.67%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s    | 1        | 6.67%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 6.67%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s     | 1        | 6.67%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 1        | 6.67%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s   | 1        | 6.67%   |
| Corsair RAM CMZ16GX3M4A2133C11 4GB DIMM DDR3 1600MT/s    | 1        | 6.67%   |
| Corsair RAM CMY16GX3M2A1866C9 8GB DIMM DDR3 2400MT/s     | 1        | 6.67%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 1        | 6.67%   |
| Asgard RAM VMA45UG-MEC1U2AW2 8GB DIMM DDR4 2400MT/s      | 1        | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 8        | 61.54%  |
| DDR3  | 4        | 30.77%  |
| SDRAM | 1        | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 13       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 61.54%  |
| 16384 | 2        | 15.38%  |
| 4096  | 1        | 7.69%   |
| 2048  | 1        | 7.69%   |
| 1024  | 1        | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 3        | 20%     |
| 2400  | 3        | 20%     |
| 1600  | 3        | 20%     |
| 3866  | 1        | 6.67%   |
| 3800  | 1        | 6.67%   |
| 3466  | 1        | 6.67%   |
| 3200  | 1        | 6.67%   |
| 1066  | 1        | 6.67%   |
| 800   | 1        | 6.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| HP ScanJet 2400c | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 9        | 50%     |
| Microsoft           | 2        | 11.11%  |
| Hewlett-Packard     | 2        | 11.11%  |
| Apple               | 2        | 11.11%  |
| Samsung Electronics | 1        | 5.56%   |
| Microdia            | 1        | 5.56%   |
| Lenovo              | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 3        | 16.67%  |
| Logitech C922 Pro Stream Webcam         | 3        | 16.67%  |
| Apple iPhone 5/5C/5S/6/SE               | 2        | 11.11%  |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 5.56%   |
| Microsoft Xbox NUI Camera               | 1        | 5.56%   |
| Microsoft LifeCam Cinema                | 1        | 5.56%   |
| Microdia Integrated Camera              | 1        | 5.56%   |
| Logitech StreamCam                      | 1        | 5.56%   |
| Logitech QuickCam Pro 9000              | 1        | 5.56%   |
| Logitech HD Pro Webcam C920             | 1        | 5.56%   |
| Lenovo 500 RGB Camera                   | 1        | 5.56%   |
| HP Webcam HD-2200                       | 1        | 5.56%   |
| HP Webcam HD 2300                       | 1        | 5.56%   |

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
| 0     | 67       | 88.16%  |
| 1     | 8        | 10.53%  |
| 2     | 1        | 1.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 5        | 55.56%  |
| Sound                    | 1        | 11.11%  |
| Multimedia controller    | 1        | 11.11%  |
| Graphics card            | 1        | 11.11%  |
| Communication controller | 1        | 11.11%  |

