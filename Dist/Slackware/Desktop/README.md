Slackware - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Slackware.

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

Total: 70

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock     | B550 Taichi                 | [469f9d71e2](https://linux-hardware.org/?probe=469f9d71e2) | Dec 29, 2022 |
| Dell       | 0MY171 A00                  | [055bc4ea78](https://linux-hardware.org/?probe=055bc4ea78) | Dec 13, 2022 |
| ASUSTek    | SABERTOOTH X99              | [c0bf1336d5](https://linux-hardware.org/?probe=c0bf1336d5) | Dec 12, 2022 |
| HP         | 8906 SMVB                   | [d000e4e926](https://linux-hardware.org/?probe=d000e4e926) | Dec 02, 2022 |
| Lenovo     | 31900058 STD                | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
| HP         | 3031h                       | [b6849a29a2](https://linux-hardware.org/?probe=b6849a29a2) | Sep 24, 2022 |
| HP         | 3031h                       | [40160588bb](https://linux-hardware.org/?probe=40160588bb) | Sep 20, 2022 |
| MSI        | H110M PRO-VD                | [2299dc1786](https://linux-hardware.org/?probe=2299dc1786) | Sep 17, 2022 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [a954ba4e86](https://linux-hardware.org/?probe=a954ba4e86) | Aug 26, 2022 |
| Gigabyte   | X570 AORUS MASTER           | [9bfc03d98e](https://linux-hardware.org/?probe=9bfc03d98e) | Aug 20, 2022 |
| Dell       | 0200DY A03                  | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| Gigabyte   | N3160TN                     | [e2f44a8274](https://linux-hardware.org/?probe=e2f44a8274) | May 31, 2022 |
| ASUSTek    | TUF B450-PLUS GAMING        | [533b8a9f83](https://linux-hardware.org/?probe=533b8a9f83) | Apr 13, 2022 |
| MSI        | 970 GAMING                  | [25d8968f19](https://linux-hardware.org/?probe=25d8968f19) | Apr 13, 2022 |
| ASRock     | N68-S3 FX                   | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| MSI        | MS-7365                     | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown    | X79-P3                      | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| HP         | 0A08h                       | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| ASRock     | H410M-ITX/ac                | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| ASUSTek    | PRIME Z390-A                | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| Acer       | FMCP7A-ION-LE               | [bbce73c6d6](https://linux-hardware.org/?probe=bbce73c6d6) | Mar 14, 2022 |
| ASRock     | H270 Pro4                   | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| Lenovo     | 31900058 STD                | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| Biostar    | X470GTA                     | [8d400b49f8](https://linux-hardware.org/?probe=8d400b49f8) | Feb 13, 2022 |
| MSI        | G31TM-P21                   | [dda6a57223](https://linux-hardware.org/?probe=dda6a57223) | Feb 07, 2022 |
| HP         | 212B                        | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI        | B450 TOMAHAWK MAX           | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| MSI        | G31TM-P21                   | [25d668ee95](https://linux-hardware.org/?probe=25d668ee95) | Jan 10, 2022 |
| MSI        | H61M-P31                    | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| HP         | 21B4 A01                    | [871b196cc2](https://linux-hardware.org/?probe=871b196cc2) | Nov 21, 2021 |
| HP         | 21B4 A01                    | [259232d98b](https://linux-hardware.org/?probe=259232d98b) | Nov 21, 2021 |
| Supermicro | X9DA7/E                     | [3fc1ef2b58](https://linux-hardware.org/?probe=3fc1ef2b58) | Nov 09, 2021 |
| MSI        | B450M-A PRO MAX             | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek    | SABERTOOTH X99              | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI        | B450M-A PRO MAX             | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |
| Intel      | DZ77RE-75K AAG39010-302     | [069c508e80](https://linux-hardware.org/?probe=069c508e80) | Sep 25, 2021 |
| Shuttle    | NC03U                       | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| ASUSTek    | SABERTOOTH X79              | [5d6732e14c](https://linux-hardware.org/?probe=5d6732e14c) | Aug 09, 2021 |
| HPE        | ProLiant MicroServer Gen... | [9ac798b737](https://linux-hardware.org/?probe=9ac798b737) | Aug 05, 2021 |
| HPE        | ProLiant MicroServer Gen... | [095745e5fb](https://linux-hardware.org/?probe=095745e5fb) | Jul 06, 2021 |
| HP         | 158A                        | [d612124939](https://linux-hardware.org/?probe=d612124939) | Jun 21, 2021 |
| ASRock     | H310CM-HDV                  | [3291e5d2de](https://linux-hardware.org/?probe=3291e5d2de) | Jun 19, 2021 |
| ASRock     | H87M Pro4                   | [8d4b7f121d](https://linux-hardware.org/?probe=8d4b7f121d) | Jun 02, 2021 |
| ASUSTek    | Pro WS X570-ACE             | [6e60025ac5](https://linux-hardware.org/?probe=6e60025ac5) | May 25, 2021 |
| ASUSTek    | PRIME X370-PRO              | [3e5f76719a](https://linux-hardware.org/?probe=3e5f76719a) | May 24, 2021 |
| ASUSTek    | PRIME X370-PRO              | [c75f9d5c0d](https://linux-hardware.org/?probe=c75f9d5c0d) | May 23, 2021 |
| Dell       | 0PTTT9 A00                  | [e5b81a0da1](https://linux-hardware.org/?probe=e5b81a0da1) | May 20, 2021 |
| Gigabyte   | N3160TN                     | [2fd537312f](https://linux-hardware.org/?probe=2fd537312f) | May 14, 2021 |
| MSI        | G31TM-P21                   | [91c11ae82e](https://linux-hardware.org/?probe=91c11ae82e) | May 07, 2021 |
| Foxconn    | 2ADA                        | [425d15a5ce](https://linux-hardware.org/?probe=425d15a5ce) | Mar 09, 2021 |
| Dell       | 0TP412                      | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| ASRock     | B450M Steel Legend          | [e1424f6de3](https://linux-hardware.org/?probe=e1424f6de3) | Dec 31, 2020 |
| NetGear    | ReadyDATA 5200              | [96607f4270](https://linux-hardware.org/?probe=96607f4270) | Nov 12, 2020 |
| ASRock     | Z390M-ITX/ac                | [06eb8afdbc](https://linux-hardware.org/?probe=06eb8afdbc) | Oct 19, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [d42d44dd82](https://linux-hardware.org/?probe=d42d44dd82) | Jul 23, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [888f105221](https://linux-hardware.org/?probe=888f105221) | Jul 23, 2020 |
| ASUSTek    | M5A97 R2.0                  | [2eb600bb96](https://linux-hardware.org/?probe=2eb600bb96) | Jul 10, 2020 |
| ASUSTek    | M5A97 R2.0                  | [232221bf45](https://linux-hardware.org/?probe=232221bf45) | Jul 10, 2020 |
| Huanan     | X79-8D VAA31                | [bbfc99d048](https://linux-hardware.org/?probe=bbfc99d048) | Jan 22, 2020 |
| ASUSTek    | A68HM-PLUS                  | [505df04abc](https://linux-hardware.org/?probe=505df04abc) | Oct 27, 2019 |
| ASUSTek    | PRIME B350M-A               | [0b246f9623](https://linux-hardware.org/?probe=0b246f9623) | Oct 27, 2019 |
| ASUSTek    | ROG STRIX X470-F GAMING     | [21d76cde28](https://linux-hardware.org/?probe=21d76cde28) | Oct 22, 2019 |
| ASUSTek    | Z97-A                       | [482c60ec21](https://linux-hardware.org/?probe=482c60ec21) | Oct 21, 2019 |
| Gigabyte   | M61SME-S2                   | [10469f1659](https://linux-hardware.org/?probe=10469f1659) | Oct 21, 2019 |
| HP         | 2B35                        | [45c5e4afbe](https://linux-hardware.org/?probe=45c5e4afbe) | Oct 21, 2019 |
| Gigabyte   | 970A-DS3P                   | [70ea4f97bf](https://linux-hardware.org/?probe=70ea4f97bf) | Oct 21, 2019 |
| ASUSTek    | Maximus VII HERO            | [4751f76aa2](https://linux-hardware.org/?probe=4751f76aa2) | Oct 20, 2019 |
| ASUSTek    | Maximus VII RANGER          | [71121ccd6f](https://linux-hardware.org/?probe=71121ccd6f) | Oct 20, 2019 |
| ASUSTek    | P5QLD PRO                   | [dabc1ee203](https://linux-hardware.org/?probe=dabc1ee203) | Oct 20, 2019 |
| Gigabyte   | X150M-PRO ECC-CF            | [39987c5d8e](https://linux-hardware.org/?probe=39987c5d8e) | Oct 10, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Slackware 14.2  | 32       | 53.33%  |
| Slackware 15.0  | 26       | 43.33%  |
| Slackware 14.2+ | 2        | 3.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Slackware | 58       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.10.28-Unraid       | 5        | 8.06%   |
| 5.15.19              | 4        | 6.45%   |
| 4.19.80              | 4        | 6.45%   |
| 5.19.17              | 3        | 4.84%   |
| 4.4.190              | 3        | 4.84%   |
| 5.15.63              | 2        | 3.23%   |
| 5.15.30-Unraid       | 2        | 3.23%   |
| 5.15.27              | 2        | 3.23%   |
| 4.4.240              | 2        | 3.23%   |
| 5.4.77               | 1        | 1.61%   |
| 5.4.53-APRL          | 1        | 1.61%   |
| 5.4.43               | 1        | 1.61%   |
| 5.4.0-rc2-vto        | 1        | 1.61%   |
| 5.19.16              | 1        | 1.61%   |
| 5.17.2               | 1        | 1.61%   |
| 5.17.0-custom        | 1        | 1.61%   |
| 5.16.18              | 1        | 1.61%   |
| 5.16.13              | 1        | 1.61%   |
| 5.16.11              | 1        | 1.61%   |
| 5.15.6               | 1        | 1.61%   |
| 5.15.50-cwl          | 1        | 1.61%   |
| 5.15.38              | 1        | 1.61%   |
| 5.15.14              | 1        | 1.61%   |
| 5.15.13              | 1        | 1.61%   |
| 5.14.15-Unraid       | 1        | 1.61%   |
| 5.14.15              | 1        | 1.61%   |
| 5.14.12              | 1        | 1.61%   |
| 5.14.11              | 1        | 1.61%   |
| 5.13.9-jw            | 1        | 1.61%   |
| 5.13.12              | 1        | 1.61%   |
| 5.12.12              | 1        | 1.61%   |
| 5.10.44-slack64-host | 1        | 1.61%   |
| 5.10.40              | 1        | 1.61%   |
| 5.10.3               | 1        | 1.61%   |
| 4.9.248.a            | 1        | 1.61%   |
| 4.9.118              | 1        | 1.61%   |
| 4.4.261              | 1        | 1.61%   |
| 4.4.189              | 1        | 1.61%   |
| 4.4.14               | 1        | 1.61%   |
| 4.20.11              | 1        | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.28 | 5        | 8.06%   |
| 5.15.19 | 4        | 6.45%   |
| 4.19.80 | 4        | 6.45%   |
| 5.19.17 | 3        | 4.84%   |
| 4.4.190 | 3        | 4.84%   |
| 5.15.63 | 2        | 3.23%   |
| 5.15.30 | 2        | 3.23%   |
| 5.15.27 | 2        | 3.23%   |
| 5.14.15 | 2        | 3.23%   |
| 4.4.240 | 2        | 3.23%   |
| 5.4.77  | 1        | 1.61%   |
| 5.4.53  | 1        | 1.61%   |
| 5.4.43  | 1        | 1.61%   |
| 5.4.0   | 1        | 1.61%   |
| 5.19.16 | 1        | 1.61%   |
| 5.17.2  | 1        | 1.61%   |
| 5.17.0  | 1        | 1.61%   |
| 5.16.18 | 1        | 1.61%   |
| 5.16.13 | 1        | 1.61%   |
| 5.16.11 | 1        | 1.61%   |
| 5.15.6  | 1        | 1.61%   |
| 5.15.50 | 1        | 1.61%   |
| 5.15.38 | 1        | 1.61%   |
| 5.15.14 | 1        | 1.61%   |
| 5.15.13 | 1        | 1.61%   |
| 5.14.12 | 1        | 1.61%   |
| 5.14.11 | 1        | 1.61%   |
| 5.13.9  | 1        | 1.61%   |
| 5.13.12 | 1        | 1.61%   |
| 5.12.12 | 1        | 1.61%   |
| 5.10.44 | 1        | 1.61%   |
| 5.10.40 | 1        | 1.61%   |
| 5.10.3  | 1        | 1.61%   |
| 4.9.248 | 1        | 1.61%   |
| 4.9.118 | 1        | 1.61%   |
| 4.4.261 | 1        | 1.61%   |
| 4.4.189 | 1        | 1.61%   |
| 4.4.14  | 1        | 1.61%   |
| 4.20.11 | 1        | 1.61%   |
| 4.19.98 | 1        | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 15       | 24.19%  |
| 5.10    | 8        | 12.9%   |
| 4.4     | 8        | 12.9%   |
| 4.19    | 8        | 12.9%   |
| 5.4     | 4        | 6.45%   |
| 5.19    | 4        | 6.45%   |
| 5.14    | 4        | 6.45%   |
| 5.16    | 3        | 4.84%   |
| 5.17    | 2        | 3.23%   |
| 5.13    | 2        | 3.23%   |
| 4.9     | 2        | 3.23%   |
| 5.12    | 1        | 1.61%   |
| 4.20    | 1        | 1.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 58       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Unknown   | 23       | 38.98%  |
| XFCE      | 16       | 27.12%  |
| KDE5      | 15       | 25.42%  |
| FVWM      | 2        | 3.39%   |
| X-Generic | 1        | 1.69%   |
| MATE      | 1        | 1.69%   |
| KDE       | 1        | 1.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 37       | 61.67%  |
| Tty     | 12       | 20%     |
| Unknown | 9        | 15%     |
| Wayland | 2        | 3.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 40%     |
| SDDM    | 17       | 28.33%  |
| XDM     | 15       | 25%     |
| SLiM    | 2        | 3.33%   |
| LightDM | 2        | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 26       | 44.83%  |
| Unknown     | 20       | 34.48%  |
| ru_RU       | 2        | 3.45%   |
| it_IT       | 2        | 3.45%   |
| en_GB       | 2        | 3.45%   |
| sr_RS@latin | 1        | 1.72%   |
| pt_PT       | 1        | 1.72%   |
| es_ES.UTF8  | 1        | 1.72%   |
| en_US.ASCII | 1        | 1.72%   |
| en_AU       | 1        | 1.72%   |
| C           | 1        | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 34       | 58.62%  |
| EFI  | 24       | 41.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 37       | 63.79%  |
| Btrfs    | 8        | 13.79%  |
| Xfs      | 5        | 8.62%   |
| Rootfs   | 3        | 5.17%   |
| Overlay  | 2        | 3.45%   |
| Reiserfs | 1        | 1.72%   |
| F2fs     | 1        | 1.72%   |
| Ext3     | 1        | 1.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 40       | 66.67%  |
| MBR     | 17       | 28.33%  |
| Unknown | 3        | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 52.54%  |
| Yes       | 28       | 47.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 67.24%  |
| Yes       | 19       | 32.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 27.59%  |
| ASRock              | 8        | 13.79%  |
| MSI                 | 7        | 12.07%  |
| Hewlett-Packard     | 7        | 12.07%  |
| Gigabyte Technology | 5        | 8.62%   |
| Dell                | 4        | 6.9%    |
| Supermicro          | 1        | 1.72%   |
| Shuttle             | 1        | 1.72%   |
| NetGear             | 1        | 1.72%   |
| Lenovo              | 1        | 1.72%   |
| Intel               | 1        | 1.72%   |
| Huanan              | 1        | 1.72%   |
| HPE                 | 1        | 1.72%   |
| Foxconn             | 1        | 1.72%   |
| Biostar             | 1        | 1.72%   |
| Acer                | 1        | 1.72%   |
| Unknown             | 1        | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 4        | 6.9%    |
| Supermicro X9DA7/E                   | 1        | 1.72%   |
| Shuttle NC03U                        | 1        | 1.72%   |
| NetGear ReadyDATA 5200               | 1        | 1.72%   |
| MSI MS-7C52                          | 1        | 1.72%   |
| MSI MS-7C02                          | 1        | 1.72%   |
| MSI MS-7996                          | 1        | 1.72%   |
| MSI MS-7788                          | 1        | 1.72%   |
| MSI MS-7693                          | 1        | 1.72%   |
| MSI MS-7529                          | 1        | 1.72%   |
| MSI MS-7365                          | 1        | 1.72%   |
| Lenovo H50-05 90BH001WIX             | 1        | 1.72%   |
| Intel DZ77RE-75K AAG39010-302        | 1        | 1.72%   |
| Huanan X79-8D VAA31                  | 1        | 1.72%   |
| HPE ProLiant MicroServer Gen10 Plus  | 1        | 1.72%   |
| HP Z620 Workstation                  | 1        | 1.72%   |
| HP Z440 Workstation                  | 1        | 1.72%   |
| HP xw8400 Workstation                | 1        | 1.72%   |
| HP t620 Quad Core TC                 | 1        | 1.72%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 1.72%   |
| HP Compaq dc7900 Small Form Factor   | 1        | 1.72%   |
| HP 500-515na                         | 1        | 1.72%   |
| Gigabyte X570 AORUS MASTER           | 1        | 1.72%   |
| Gigabyte X150M-PRO ECC               | 1        | 1.72%   |
| Gigabyte N3160TN                     | 1        | 1.72%   |
| Gigabyte M61SME-S2                   | 1        | 1.72%   |
| Gigabyte 970A-DS3P                   | 1        | 1.72%   |
| Foxconn p6-2390                      | 1        | 1.72%   |
| Dell Precision WorkStation T3400     | 1        | 1.72%   |
| Dell Precision WorkStation 690       | 1        | 1.72%   |
| Dell Precision T3600                 | 1        | 1.72%   |
| Dell OptiPlex 780                    | 1        | 1.72%   |
| Biostar X470GTA                      | 1        | 1.72%   |
| ASUS TUF B450-PLUS GAMING            | 1        | 1.72%   |
| ASUS SABERTOOTH X79                  | 1        | 1.72%   |
| ASUS ROG STRIX X470-F GAMING         | 1        | 1.72%   |
| ASUS ROG CROSSHAIR VIII HERO         | 1        | 1.72%   |
| ASUS Pro WS X570-ACE                 | 1        | 1.72%   |
| ASUS PRIME Z390-A                    | 1        | 1.72%   |
| ASUS PRIME X370-PRO                  | 1        | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 4        | 6.9%    |
| ASUS All           | 4        | 6.9%    |
| Dell Precision     | 3        | 5.17%   |
| ASUS ROG           | 2        | 3.45%   |
| Supermicro X9DA7   | 1        | 1.72%   |
| Shuttle NC03U      | 1        | 1.72%   |
| NetGear ReadyDATA  | 1        | 1.72%   |
| MSI MS-7C52        | 1        | 1.72%   |
| MSI MS-7C02        | 1        | 1.72%   |
| MSI MS-7996        | 1        | 1.72%   |
| MSI MS-7788        | 1        | 1.72%   |
| MSI MS-7693        | 1        | 1.72%   |
| MSI MS-7529        | 1        | 1.72%   |
| MSI MS-7365        | 1        | 1.72%   |
| Lenovo H50-05      | 1        | 1.72%   |
| Intel DZ77RE-75K   | 1        | 1.72%   |
| Huanan X79-8D      | 1        | 1.72%   |
| HPE ProLiant       | 1        | 1.72%   |
| HP Z620            | 1        | 1.72%   |
| HP Z440            | 1        | 1.72%   |
| HP xw8400          | 1        | 1.72%   |
| HP t620            | 1        | 1.72%   |
| HP Pavilion        | 1        | 1.72%   |
| HP Compaq          | 1        | 1.72%   |
| HP 500-515na       | 1        | 1.72%   |
| Gigabyte X570      | 1        | 1.72%   |
| Gigabyte X150M-PRO | 1        | 1.72%   |
| Gigabyte N3160TN   | 1        | 1.72%   |
| Gigabyte M61SME-S2 | 1        | 1.72%   |
| Gigabyte 970A-DS3P | 1        | 1.72%   |
| Foxconn p6-2390    | 1        | 1.72%   |
| Dell OptiPlex      | 1        | 1.72%   |
| Biostar X470GTA    | 1        | 1.72%   |
| ASUS TUF           | 1        | 1.72%   |
| ASUS SABERTOOTH    | 1        | 1.72%   |
| ASUS Pro           | 1        | 1.72%   |
| ASUS P5QLD         | 1        | 1.72%   |
| ASUS M5A97         | 1        | 1.72%   |
| ASUS A68HM-PLUS    | 1        | 1.72%   |
| ASRock Z390M-ITX   | 1        | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 9        | 15.52%  |
| 2018 | 6        | 10.34%  |
| 2017 | 5        | 8.62%   |
| 2014 | 5        | 8.62%   |
| 2012 | 5        | 8.62%   |
| 2015 | 4        | 6.9%    |
| 2011 | 4        | 6.9%    |
| 2008 | 4        | 6.9%    |
| 2020 | 3        | 5.17%   |
| 2016 | 3        | 5.17%   |
| 2009 | 3        | 5.17%   |
| 2022 | 2        | 3.45%   |
| 2013 | 2        | 3.45%   |
| 2007 | 2        | 3.45%   |
| 2021 | 1        | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 58       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 58       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 16       | 27.12%  |
| 32.01-64.0  | 10       | 16.95%  |
| 64.01-256.0 | 8        | 13.56%  |
| 8.01-16.0   | 8        | 13.56%  |
| 4.01-8.0    | 6        | 10.17%  |
| 3.01-4.0    | 6        | 10.17%  |
| 24.01-32.0  | 3        | 5.08%   |
| 1.01-2.0    | 2        | 3.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 15       | 24.59%  |
| 4.01-8.0    | 14       | 22.95%  |
| 2.01-3.0    | 12       | 19.67%  |
| 3.01-4.0    | 6        | 9.84%   |
| 0.51-1.0    | 4        | 6.56%   |
| 8.01-16.0   | 3        | 4.92%   |
| 24.01-32.0  | 2        | 3.28%   |
| 0.01-0.5    | 2        | 3.28%   |
| 32.01-64.0  | 1        | 1.64%   |
| 64.01-256.0 | 1        | 1.64%   |
| 16.01-24.0  | 1        | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 14       | 22.95%  |
| 1      | 14       | 22.95%  |
| 2      | 10       | 16.39%  |
| 4      | 7        | 11.48%  |
| 6      | 5        | 8.2%    |
| 5      | 5        | 8.2%    |
| 0      | 2        | 3.28%   |
| 13     | 1        | 1.64%   |
| 9      | 1        | 1.64%   |
| 8      | 1        | 1.64%   |
| 7      | 1        | 1.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 55.93%  |
| No        | 26       | 44.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 58       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 62.07%  |
| Yes       | 22       | 37.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 62.07%  |
| Yes       | 22       | 37.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 14       | 24.14%  |
| UK           | 8        | 13.79%  |
| Russia       | 4        | 6.9%    |
| Italy        | 4        | 6.9%    |
| Kazakhstan   | 3        | 5.17%   |
| Hong Kong    | 3        | 5.17%   |
| Germany      | 3        | 5.17%   |
| Canada       | 3        | 5.17%   |
| Sweden       | 2        | 3.45%   |
| Spain        | 2        | 3.45%   |
| Portugal     | 2        | 3.45%   |
| Japan        | 2        | 3.45%   |
| France       | 2        | 3.45%   |
| Brazil       | 2        | 3.45%   |
| South Africa | 1        | 1.72%   |
| Serbia       | 1        | 1.72%   |
| Bulgaria     | 1        | 1.72%   |
| Australia    | 1        | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Yekaterinburg     | 3        | 5.08%   |
| Ust-Kamenogorsk   | 2        | 3.39%   |
| Paris             | 2        | 3.39%   |
| Winter Springs    | 1        | 1.69%   |
| Weilheim          | 1        | 1.69%   |
| Tsukuba           | 1        | 1.69%   |
| Toronto           | 1        | 1.69%   |
| Tiffin            | 1        | 1.69%   |
| Tendo             | 1        | 1.69%   |
| Stockholm         | 1        | 1.69%   |
| St Petersburg     | 1        | 1.69%   |
| Springfield       | 1        | 1.69%   |
| Southend-on-Sea   | 1        | 1.69%   |
| Shrewsbury        | 1        | 1.69%   |
| Sham Shui Po      | 1        | 1.69%   |
| Senhora da Hora   | 1        | 1.69%   |
| Santa Cruz do Sul | 1        | 1.69%   |
| Saint Paul        | 1        | 1.69%   |
| Rome              | 1        | 1.69%   |
| Rock              | 1        | 1.69%   |
| Porto Alegre      | 1        | 1.69%   |
| Plovdiv           | 1        | 1.69%   |
| Palma             | 1        | 1.69%   |
| Ottawa            | 1        | 1.69%   |
| Oldham            | 1        | 1.69%   |
| Naples            | 1        | 1.69%   |
| Moscow            | 1        | 1.69%   |
| Milwaukee         | 1        | 1.69%   |
| Milan             | 1        | 1.69%   |
| Mead              | 1        | 1.69%   |
| McKinney          | 1        | 1.69%   |
| Mason             | 1        | 1.69%   |
| London            | 1        | 1.69%   |
| Lisbon            | 1        | 1.69%   |
| Lexington         | 1        | 1.69%   |
| Kowloon           | 1        | 1.69%   |
| Koblenz           | 1        | 1.69%   |
| Karaganda         | 1        | 1.69%   |
| Hampstead         | 1        | 1.69%   |
| Granada           | 1        | 1.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 25       | 55     | 21.74%  |
| Seagate             | 23       | 48     | 20%     |
| Samsung Electronics | 15       | 27     | 13.04%  |
| Toshiba             | 10       | 20     | 8.7%    |
| Hitachi             | 8        | 11     | 6.96%   |
| Kingston            | 5        | 8      | 4.35%   |
| Intel               | 3        | 4      | 2.61%   |
| Crucial             | 3        | 3      | 2.61%   |
| A-DATA Technology   | 3        | 3      | 2.61%   |
| HGST                | 2        | 2      | 1.74%   |
| Hewlett-Packard     | 2        | 2      | 1.74%   |
| China               | 2        | 3      | 1.74%   |
| ZHITAI              | 1        | 2      | 0.87%   |
| Team                | 1        | 1      | 0.87%   |
| SK hynix            | 1        | 1      | 0.87%   |
| SanDisk             | 1        | 1      | 0.87%   |
| PNY                 | 1        | 1      | 0.87%   |
| Phison Electronics  | 1        | 1      | 0.87%   |
| Patriot             | 1        | 1      | 0.87%   |
| Maxtor              | 1        | 1      | 0.87%   |
| KIOXIA              | 1        | 1      | 0.87%   |
| Intenso             | 1        | 1      | 0.87%   |
| Gigabyte Technology | 1        | 1      | 0.87%   |
| Fujitsu             | 1        | 1      | 0.87%   |
| DUEX                | 1        | 1      | 0.87%   |
| Apple               | 1        | 2      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD20EFRX-68EUZN0 2TB         | 3        | 1.9%    |
| WDC WD1003FZEX-00MK2A0 1TB       | 3        | 1.9%    |
| Samsung SSD 970 EVO 250GB        | 3        | 1.9%    |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 1.27%   |
| WDC WD10EZEX-00RKKA0 1TB         | 2        | 1.27%   |
| Toshiba MQ01ABD100 1TB           | 2        | 1.27%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 1.27%   |
| Seagate ST4000VN008-2DR166 4TB   | 2        | 1.27%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 1.27%   |
| Seagate ST31000524AS 1TB         | 2        | 1.27%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 1.27%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 1.27%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 1.27%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 1.27%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 1.27%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 1.27%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 1.27%   |
| ZHITAI SC001 Active 1TB SSD      | 1        | 0.63%   |
| ZHITAI PC005 Active 512GB        | 1        | 0.63%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.63%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1        | 0.63%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.63%   |
| WDC WD5000BPVT-2 500GB           | 1        | 0.63%   |
| WDC WD5000BPKX-60HPJT0 500GB     | 1        | 0.63%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1        | 0.63%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.63%   |
| WDC WD5000AAKS-00V0A0 500GB      | 1        | 0.63%   |
| WDC WD5000AAKS-00A7B2 500GB      | 1        | 0.63%   |
| WDC WD40EJRX-89T1XY0 4TB         | 1        | 0.63%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.63%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.63%   |
| WDC WD400BD-60LTA0 40GB          | 1        | 0.63%   |
| WDC WD3200AAJS-65B4A0 320GB      | 1        | 0.63%   |
| WDC WD30EZRX-00SPEB0 3TB         | 1        | 0.63%   |
| WDC WD30EZRX-00M                 | 1        | 0.63%   |
| WDC WD30EFRX-68EUZN0 3TB         | 1        | 0.63%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1        | 0.63%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.63%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.63%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 25       | 52     | 34.25%  |
| Seagate             | 23       | 44     | 31.51%  |
| Toshiba             | 9        | 17     | 12.33%  |
| Hitachi             | 8        | 11     | 10.96%  |
| Samsung Electronics | 3        | 3      | 4.11%   |
| HGST                | 2        | 2      | 2.74%   |
| Maxtor              | 1        | 1      | 1.37%   |
| Hewlett-Packard     | 1        | 1      | 1.37%   |
| Fujitsu             | 1        | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 15     | 25%     |
| Kingston            | 5        | 8      | 15.63%  |
| Crucial             | 3        | 3      | 9.38%   |
| Intel               | 2        | 3      | 6.25%   |
| China               | 2        | 3      | 6.25%   |
| ZHITAI              | 1        | 1      | 3.13%   |
| WDC                 | 1        | 2      | 3.13%   |
| Toshiba             | 1        | 1      | 3.13%   |
| Team                | 1        | 1      | 3.13%   |
| SanDisk             | 1        | 1      | 3.13%   |
| PNY                 | 1        | 1      | 3.13%   |
| Patriot             | 1        | 1      | 3.13%   |
| Intenso             | 1        | 1      | 3.13%   |
| Hewlett-Packard     | 1        | 1      | 3.13%   |
| DUEX                | 1        | 1      | 3.13%   |
| Apple               | 1        | 2      | 3.13%   |
| A-DATA Technology   | 1        | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 46       | 132    | 50%     |
| SSD     | 29       | 46     | 31.52%  |
| NVMe    | 16       | 20     | 17.39%  |
| Unknown | 1        | 4      | 1.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 52       | 173    | 74.29%  |
| NVMe | 16       | 20     | 22.86%  |
| SAS  | 2        | 9      | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 38       | 66     | 40.43%  |
| 0.51-1.0   | 23       | 50     | 24.47%  |
| 1.01-2.0   | 12       | 18     | 12.77%  |
| 3.01-4.0   | 8        | 20     | 8.51%   |
| 2.01-3.0   | 7        | 15     | 7.45%   |
| 4.01-10.0  | 4        | 4      | 4.26%   |
| 10.01-20.0 | 2        | 5      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 12       | 19.67%  |
| Unknown        | 11       | 18.03%  |
| 101-250        | 9        | 14.75%  |
| 2001-3000      | 7        | 11.48%  |
| 1001-2000      | 7        | 11.48%  |
| 251-500        | 5        | 8.2%    |
| More than 3000 | 4        | 6.56%   |
| 1-20           | 3        | 4.92%   |
| 51-100         | 2        | 3.28%   |
| 21-50          | 1        | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 14       | 23.33%  |
| Unknown        | 11       | 18.33%  |
| 501-1000       | 9        | 15%     |
| 1-20           | 6        | 10%     |
| 251-500        | 5        | 8.33%   |
| 1001-2000      | 5        | 8.33%   |
| 51-100         | 4        | 6.67%   |
| More than 3000 | 3        | 5%      |
| 21-50          | 3        | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1        | 1      | 3.33%   |
| WDC WD5000BPKX-60HPJT0 500GB       | 1        | 1      | 3.33%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 1        | 1      | 3.33%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 1      | 3.33%   |
| WDC WD5000AAKS-00A7B2 500GB        | 1        | 1      | 3.33%   |
| WDC WD40EFRX-68WT0N0 4TB           | 1        | 2      | 3.33%   |
| WDC WD3200AAJS-65B4A0 320GB        | 1        | 1      | 3.33%   |
| WDC WD30EZRX-00M                   | 1        | 1      | 3.33%   |
| WDC WD30EFRX-68AX9N0 3TB           | 1        | 4      | 3.33%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 2      | 3.33%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 1      | 3.33%   |
| WDC WD10EALS-00Z8A0 1TB            | 1        | 2      | 3.33%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 1        | 2      | 3.33%   |
| Seagate ST380011A 80GB             | 1        | 2      | 3.33%   |
| Seagate ST3500418AS 500GB          | 1        | 1      | 3.33%   |
| Seagate ST3500410AS 500GB          | 1        | 1      | 3.33%   |
| Seagate ST31000524AS 1TB           | 1        | 1      | 3.33%   |
| Seagate ST3000VX006-1HH166 3TB     | 1        | 1      | 3.33%   |
| Seagate ST2000DL003-9VT166 2TB     | 1        | 1      | 3.33%   |
| Seagate ST1000VM002-1SD102 1TB     | 1        | 1      | 3.33%   |
| Seagate ST1000NM0011 1TB           | 1        | 2      | 3.33%   |
| Seagate ST1000DM003-1ER162 1TB     | 1        | 2      | 3.33%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1        | 1      | 3.33%   |
| Maxtor 4G120J6 128GB               | 1        | 1      | 3.33%   |
| Intel SSDSA2M080G2GC 80GB          | 1        | 1      | 3.33%   |
| Hitachi HUA723030ALA640 3TB        | 1        | 1      | 3.33%   |
| Hitachi HDS721050CLA660 500GB      | 1        | 1      | 3.33%   |
| Hitachi HDS721016CLA382 160GB      | 1        | 1      | 3.33%   |
| HGST HDN726040ALE614 4TB           | 1        | 1      | 3.33%   |
| DUEX DX300256A5xnEMLC 256GB SSD    | 1        | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 11       | 20     | 40.74%  |
| Seagate | 8        | 12     | 29.63%  |
| Hitachi | 3        | 3      | 11.11%  |
| SanDisk | 1        | 1      | 3.7%    |
| Maxtor  | 1        | 1      | 3.7%    |
| Intel   | 1        | 1      | 3.7%    |
| HGST    | 1        | 1      | 3.7%    |
| DUEX    | 1        | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 10       | 19     | 43.48%  |
| Seagate | 8        | 12     | 34.78%  |
| Hitachi | 3        | 3      | 13.04%  |
| Maxtor  | 1        | 1      | 4.35%   |
| HGST    | 1        | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 36     | 83.33%  |
| SSD  | 4        | 4      | 16.67%  |

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
| Works    | 48       | 140    | 61.54%  |
| Malfunc  | 24       | 40     | 30.77%  |
| Detected | 6        | 22     | 7.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 33       | 35.87%  |
| AMD                          | 21       | 22.83%  |
| Samsung Electronics          | 9        | 9.78%   |
| Marvell Technology Group     | 5        | 5.43%   |
| ASMedia Technology           | 5        | 5.43%   |
| Nvidia                       | 3        | 3.26%   |
| Realtek Semiconductor        | 2        | 2.17%   |
| JMicron Technology           | 2        | 2.17%   |
| Broadcom / LSI               | 2        | 2.17%   |
| Yangtze Memory Technologies  | 1        | 1.09%   |
| Toshiba America Info Systems | 1        | 1.09%   |
| SK hynix                     | 1        | 1.09%   |
| Silicon Image                | 1        | 1.09%   |
| SanDisk                      | 1        | 1.09%   |
| Phison Electronics           | 1        | 1.09%   |
| LSI Logic / Symbios Logic    | 1        | 1.09%   |
| KIOXIA                       | 1        | 1.09%   |
| Adaptec                      | 1        | 1.09%   |
| 3ware                        | 1        | 1.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 16       | 13.33%  |
| AMD 400 Series Chipset SATA Controller                                        | 8        | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 6        | 5%      |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 6        | 5%      |
| ASMedia ASM1062 Serial ATA Controller                                         | 4        | 3.33%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 3        | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 3        | 2.5%    |
| Realtek Realtek Non-Volatile memory controller                                | 2        | 1.67%   |
| Nvidia MCP61 SATA Controller                                                  | 2        | 1.67%   |
| Nvidia MCP61 IDE                                                              | 2        | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2        | 1.67%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 2        | 1.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 2        | 1.67%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 2        | 1.67%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                          | 2        | 1.67%   |
| Intel 631xESB/632xESB IDE Controller                                          | 2        | 1.67%   |
| Intel 4 Series Chipset PT IDER Controller                                     | 2        | 1.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2        | 1.67%   |
| Yangtze Memory Non-Volatile memory controller                                 | 1        | 0.83%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1        | 0.83%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                | 1        | 0.83%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller              | 1        | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1        | 0.83%   |
| Samsung Electronics SATA controller                                           | 1        | 0.83%   |
| Samsung Apple PCIe SSD                                                        | 1        | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1        | 0.83%   |
| Nvidia MCP79 AHCI Controller                                                  | 1        | 0.83%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller              | 1        | 0.83%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                  | 1        | 0.83%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo         | 1        | 0.83%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                       | 1        | 0.83%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                         | 1        | 0.83%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI         | 1        | 0.83%   |
| KIOXIA NVMe SSD Controller BG4                                                | 1        | 0.83%   |
| JMicron JMB58x AHCI SATA controller                                           | 1        | 0.83%   |
| JMicron JMB368 IDE controller                                                 | 1        | 0.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1        | 0.83%   |
| Intel SSD 600P Series                                                         | 1        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 49       | 56.32%  |
| NVMe | 16       | 18.39%  |
| IDE  | 12       | 13.79%  |
| RAID | 4        | 4.6%    |
| SAS  | 4        | 4.6%    |
| SCSI | 2        | 2.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 35       | 60.34%  |
| AMD    | 23       | 39.66%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Xeon CPU E5-2670 0 @ 2.60GHz     | 2        | 3.39%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2        | 3.39%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 2        | 3.39%   |
| AMD Ryzen 7 3800X 8-Core Processor     | 2        | 3.39%   |
| AMD Ryzen 5 3600 6-Core Processor      | 2        | 3.39%   |
| AMD FX-8350 Eight-Core Processor       | 2        | 3.39%   |
| Intel Xeon CPU X5355 @ 2.66GHz         | 1        | 1.69%   |
| Intel Xeon CPU X3450 @ 2.67GHz         | 1        | 1.69%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz    | 1        | 1.69%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz    | 1        | 1.69%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz    | 1        | 1.69%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz     | 1        | 1.69%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz     | 1        | 1.69%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz    | 1        | 1.69%   |
| Intel Xeon CPU 5160 @ 3.00GHz          | 1        | 1.69%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz | 1        | 1.69%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz | 1        | 1.69%   |
| Intel Pentium CPU G640 @ 2.80GHz       | 1        | 1.69%   |
| Intel Pentium CPU G4560 @ 3.50GHz      | 1        | 1.69%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 1        | 1.69%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 1        | 1.69%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 1.69%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 1        | 1.69%   |
| Intel Core i7-3930K CPU @ 3.20GHz      | 1        | 1.69%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 1        | 1.69%   |
| Intel Core i5-8600K CPU @ 3.60GHz      | 1        | 1.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1        | 1.69%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 1        | 1.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1        | 1.69%   |
| Intel Core i5-3330 CPU @ 3.00GHz       | 1        | 1.69%   |
| Intel Core i3-10105 CPU @ 3.70GHz      | 1        | 1.69%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz  | 1        | 1.69%   |
| Intel Core 2 Quad CPU Q6700 @ 2.66GHz  | 1        | 1.69%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz   | 1        | 1.69%   |
| Intel Celeron CPU N3160 @ 1.60GHz      | 1        | 1.69%   |
| Intel Atom CPU 330 @ 1.60GHz           | 1        | 1.69%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 1        | 1.69%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 1        | 1.69%   |
| AMD Ryzen 9 3950X 16-Core Processor    | 1        | 1.69%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 1        | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 11       | 18.64%  |
| Intel Core i7      | 7        | 11.86%  |
| Intel Core i5      | 6        | 10.17%  |
| AMD Ryzen 5        | 5        | 8.47%   |
| AMD Ryzen 9        | 4        | 6.78%   |
| AMD Ryzen 7        | 4        | 6.78%   |
| AMD FX             | 4        | 6.78%   |
| Intel Core 2 Duo   | 3        | 5.08%   |
| Intel Pentium      | 2        | 3.39%   |
| Intel Core 2 Quad  | 2        | 3.39%   |
| Intel Pentium Gold | 1        | 1.69%   |
| Intel Pentium Dual | 1        | 1.69%   |
| Intel Core i3      | 1        | 1.69%   |
| Intel Celeron      | 1        | 1.69%   |
| Intel Atom         | 1        | 1.69%   |
| AMD Ryzen 7 PRO    | 1        | 1.69%   |
| AMD GX             | 1        | 1.69%   |
| AMD Athlon 64 X2   | 1        | 1.69%   |
| AMD A8             | 1        | 1.69%   |
| AMD A4             | 1        | 1.69%   |
| AMD A10            | 1        | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 35.59%  |
| 2      | 11       | 18.64%  |
| 8      | 8        | 13.56%  |
| 6      | 8        | 13.56%  |
| 16     | 4        | 6.78%   |
| 12     | 3        | 5.08%   |
| 14     | 1        | 1.69%   |
| 10     | 1        | 1.69%   |
| 3      | 1        | 1.69%   |
| 1      | 1        | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 91.38%  |
| 2      | 5        | 8.62%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 39       | 67.24%  |
| 1      | 19       | 32.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 58       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 17.24%  |
| 0x206d7    | 4        | 6.9%    |
| 0x306c3    | 3        | 5.17%   |
| 0x1067a    | 3        | 5.17%   |
| 0x08701013 | 3        | 5.17%   |
| 0x906ed    | 2        | 3.45%   |
| 0x906ea    | 2        | 3.45%   |
| 0x306f2    | 2        | 3.45%   |
| 0x306a9    | 2        | 3.45%   |
| 0x0a50000c | 2        | 3.45%   |
| 0x0a201016 | 2        | 3.45%   |
| 0x08701021 | 2        | 3.45%   |
| 0x06001119 | 2        | 3.45%   |
| 0x06000822 | 2        | 3.45%   |
| 0xa0653    | 1        | 1.72%   |
| 0x906e9    | 1        | 1.72%   |
| 0x6fd      | 1        | 1.72%   |
| 0x6fb      | 1        | 1.72%   |
| 0x506e3    | 1        | 1.72%   |
| 0x406c4    | 1        | 1.72%   |
| 0x306e4    | 1        | 1.72%   |
| 0x206a7    | 1        | 1.72%   |
| 0x106e5    | 1        | 1.72%   |
| 0x106c2    | 1        | 1.72%   |
| 0x08108109 | 1        | 1.72%   |
| 0x0810100b | 1        | 1.72%   |
| 0x08001138 | 1        | 1.72%   |
| 0x07030105 | 1        | 1.72%   |
| 0x07000110 | 1        | 1.72%   |
| 0x06000852 | 1        | 1.72%   |
| 0x00000000 | 1        | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 7        | 12.07%  |
| KabyLake    | 7        | 12.07%  |
| SandyBridge | 6        | 10.34%  |
| Piledriver  | 6        | 10.34%  |
| Haswell     | 6        | 10.34%  |
| Zen 3       | 4        | 6.9%    |
| Penryn      | 4        | 6.9%    |
| Core        | 4        | 6.9%    |
| IvyBridge   | 3        | 5.17%   |
| Zen         | 2        | 3.45%   |
| Zen+        | 1        | 1.72%   |
| Skylake     | 1        | 1.72%   |
| Silvermont  | 1        | 1.72%   |
| Puma        | 1        | 1.72%   |
| Nehalem     | 1        | 1.72%   |
| K8 Hammer   | 1        | 1.72%   |
| Jaguar      | 1        | 1.72%   |
| CometLake   | 1        | 1.72%   |
| Bonnell     | 1        | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 23       | 39.66%  |
| Nvidia                     | 22       | 37.93%  |
| Intel                      | 11       | 18.97%  |
| Matrox Electronics Systems | 2        | 3.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5        | 8.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 3.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 3.28%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 3.28%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 3.28%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2        | 3.28%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 3.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 3.28%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 1.64%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1        | 1.64%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 1.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.64%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.64%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.64%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.64%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.64%   |
| Nvidia GK110GL [Quadro K5200]                                                            | 1        | 1.64%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 1.64%   |
| Nvidia GK104GL [Quadro K5000]                                                            | 1        | 1.64%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1        | 1.64%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1        | 1.64%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 1.64%   |
| Nvidia G80GL [Quadro FX 4600]                                                            | 1        | 1.64%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1        | 1.64%   |
| Nvidia C79 [ION]                                                                         | 1        | 1.64%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.64%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.64%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1        | 1.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.64%   |
| Intel HD Graphics 620                                                                    | 1        | 1.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.64%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.64%   |
| AMD Richland [Radeon HD 8470D]                                                           | 1        | 1.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 1.64%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 22       | 37.93%  |
| 1 x Nvidia     | 20       | 34.48%  |
| 1 x Intel      | 10       | 17.24%  |
| 1 x Matrox     | 2        | 3.45%   |
| Other          | 1        | 1.72%   |
| 2 x Nvidia     | 1        | 1.72%   |
| 2 x AMD        | 1        | 1.72%   |
| Intel + Nvidia | 1        | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 36       | 62.07%  |
| Proprietary | 16       | 27.59%  |
| Unknown     | 6        | 10.34%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 34.48%  |
| 0.51-1.0   | 10       | 17.24%  |
| 3.01-4.0   | 8        | 13.79%  |
| 1.01-2.0   | 6        | 10.34%  |
| 7.01-8.0   | 5        | 8.62%   |
| 8.01-16.0  | 3        | 5.17%   |
| 0.01-0.5   | 3        | 5.17%   |
| 5.01-6.0   | 2        | 3.45%   |
| 2.01-3.0   | 1        | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 9        | 15%     |
| Dell                 | 9        | 15%     |
| Hewlett-Packard      | 6        | 10%     |
| BenQ                 | 5        | 8.33%   |
| Goldstar             | 4        | 6.67%   |
| Ancor Communications | 4        | 6.67%   |
| Acer                 | 4        | 6.67%   |
| ViewSonic            | 2        | 3.33%   |
| Lenovo               | 2        | 3.33%   |
| Xiaomi               | 1        | 1.67%   |
| Wacom                | 1        | 1.67%   |
| Unknown              | 1        | 1.67%   |
| Toshiba              | 1        | 1.67%   |
| ONN                  | 1        | 1.67%   |
| NEC Computers        | 1        | 1.67%   |
| JVC                  | 1        | 1.67%   |
| IOD                  | 1        | 1.67%   |
| Iiyama               | 1        | 1.67%   |
| Gigabyte Technology  | 1        | 1.67%   |
| GDH                  | 1        | 1.67%   |
| Eizo                 | 1        | 1.67%   |
| ASUSTek Computer     | 1        | 1.67%   |
| AOC                  | 1        | 1.67%   |
| Unknown              | 1        | 1.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                   | 1        | 1.61%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch             | 1        | 1.61%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                        | 1        | 1.61%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                        | 1        | 1.61%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 1.61%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 380x300mm 19.1-inch | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch | 1        | 1.61%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch   | 1        | 1.61%   |
| Samsung Electronics SMB2430L SAM0644 1920x1080 521x293mm 23.5-inch   | 1        | 1.61%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch    | 1        | 1.61%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch    | 1        | 1.61%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch    | 1        | 1.61%   |
| ONN ONA18HO015 ONN0101 1920x1080 470x290mm 21.7-inch                 | 1        | 1.61%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch      | 1        | 1.61%   |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch               | 1        | 1.61%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 1        | 1.61%   |
| JVC FPDEUFT3 JVC21BE 1920x540                                        | 1        | 1.61%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                 | 1        | 1.61%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch               | 1        | 1.61%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch        | 1        | 1.61%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch           | 1        | 1.61%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch         | 1        | 1.61%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch         | 1        | 1.61%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch            | 1        | 1.61%   |
| Hewlett-Packard 2309 HWP2823 1920x1080 510x287mm 23.0-inch           | 1        | 1.61%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                 | 1        | 1.61%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                 | 1        | 1.61%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch               | 1        | 1.61%   |
| Goldstar E1641 GSM8B3E 1366x768 344x194mm 15.5-inch                  | 1        | 1.61%   |
| Goldstar BK750Y GSM5B3E 1920x1080 600x340mm 27.2-inch                | 1        | 1.61%   |
| Goldstar BK750Y GSM5B3D 1920x1080 480x270mm 21.7-inch                | 1        | 1.61%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch       | 1        | 1.61%   |
| GDH CHHWJT GDH0030 1440x900 1150x650mm 52.0-inch                     | 1        | 1.61%   |
| Eizo M1700 ENC1788 1280x1024 338x271mm 17.1-inch                     | 1        | 1.61%   |
| Dell U2722D DEL422D 2560x1440 597x336mm 27.0-inch                    | 1        | 1.61%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1        | 1.61%   |
| Dell SP2208WFP DEL4038 1680x1050 473x296mm 22.0-inch                 | 1        | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 28       | 47.46%  |
| 1280x1024 (SXGA)   | 7        | 11.86%  |
| 2560x1440 (QHD)    | 4        | 6.78%   |
| 1920x1200 (WUXGA)  | 4        | 6.78%   |
| 1680x1050 (WSXGA+) | 4        | 6.78%   |
| 1366x768 (WXGA)    | 3        | 5.08%   |
| 3840x2160 (4K)     | 2        | 3.39%   |
| 3440x1440          | 2        | 3.39%   |
| 3200x1080          | 1        | 1.69%   |
| 2288x1287          | 1        | 1.69%   |
| 1920x540           | 1        | 1.69%   |
| 1600x1200          | 1        | 1.69%   |
| Unknown            | 1        | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 11       | 18.33%  |
| 27      | 9        | 15%     |
| 21      | 8        | 13.33%  |
| 23      | 7        | 11.67%  |
| Unknown | 5        | 8.33%   |
| 17      | 4        | 6.67%   |
| 22      | 3        | 5%      |
| 19      | 3        | 5%      |
| 20      | 2        | 3.33%   |
| 18      | 2        | 3.33%   |
| 15      | 2        | 3.33%   |
| 142     | 1        | 1.67%   |
| 74      | 1        | 1.67%   |
| 52      | 1        | 1.67%   |
| 34      | 1        | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 25       | 42.37%  |
| 401-500        | 15       | 25.42%  |
| 301-350        | 6        | 10.17%  |
| Unknown        | 5        | 8.47%   |
| 351-400        | 3        | 5.08%   |
| More than 2000 | 1        | 1.69%   |
| 701-800        | 1        | 1.69%   |
| 601-700        | 1        | 1.69%   |
| 1501-2000      | 1        | 1.69%   |
| 1001-1500      | 1        | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 30       | 54.55%  |
| 16/10   | 9        | 16.36%  |
| 5/4     | 5        | 9.09%   |
| Unknown | 4        | 7.27%   |
| 6/5     | 2        | 3.64%   |
| 4/3     | 1        | 1.82%   |
| 32/9    | 1        | 1.82%   |
| 3/2     | 1        | 1.82%   |
| 21/9    | 1        | 1.82%   |
| 1.00    | 1        | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 37.93%  |
| 301-350        | 9        | 15.52%  |
| 141-150        | 6        | 10.34%  |
| 251-300        | 5        | 8.62%   |
| 151-200        | 5        | 8.62%   |
| Unknown        | 5        | 8.62%   |
| More than 1000 | 3        | 5.17%   |
| 101-110        | 2        | 3.45%   |
| 351-500        | 1        | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 35       | 58.33%  |
| 101-120 | 13       | 21.67%  |
| Unknown | 5        | 8.33%   |
| 121-160 | 4        | 6.67%   |
| 1-50    | 3        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 65.52%  |
| 2     | 9        | 15.52%  |
| 0     | 8        | 13.79%  |
| 3     | 3        | 5.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 31       | 38.27%  |
| Intel                    | 29       | 35.8%   |
| Qualcomm Atheros         | 4        | 4.94%   |
| TP-Link                  | 3        | 3.7%    |
| Broadcom                 | 3        | 3.7%    |
| Ralink Technology        | 2        | 2.47%   |
| Nvidia                   | 2        | 2.47%   |
| VIA Technologies         | 1        | 1.23%   |
| Ralink                   | 1        | 1.23%   |
| Qualcomm                 | 1        | 1.23%   |
| Micro Star International | 1        | 1.23%   |
| Mellanox Technologies    | 1        | 1.23%   |
| Chelsio Communications   | 1        | 1.23%   |
| Broadcom Limited         | 1        | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 22       | 22.92%  |
| Intel I211 Gigabit Network Connection                                      | 7        | 7.29%   |
| Intel Ethernet Connection (2) I218-V                                       | 4        | 4.17%   |
| Intel 82574L Gigabit Network Connection                                    | 4        | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 2        | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                          | 2        | 2.08%   |
| Ralink MT7601U Wireless Adapter                                            | 2        | 2.08%   |
| Intel Wi-Fi 6 AX200                                                        | 2        | 2.08%   |
| Intel Ethernet Connection (7) I219-V                                       | 2        | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 2.08%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 2        | 2.08%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 2.08%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                    | 2        | 2.08%   |
| VIA VT6105/VT6106S [Rhine-III]                                             | 1        | 1.04%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1        | 1.04%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                      | 1        | 1.04%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1        | 1.04%   |
| Realtek USB 10/100/1G/2.5G LAN                                             | 1        | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 1        | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 1.04%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 1.04%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1        | 1.04%   |
| Qualcomm MegaFon M150-4                                                    | 1        | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 1.04%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1        | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 1.04%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 1.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 1.04%   |
| Nvidia MCP79 Ethernet                                                      | 1        | 1.04%   |
| Nvidia MCP61 Ethernet                                                      | 1        | 1.04%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 1.04%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                      | 1        | 1.04%   |
| Intel Wireless-AC 9260                                                     | 1        | 1.04%   |
| Intel Wireless 7260                                                        | 1        | 1.04%   |
| Intel I350 Gigabit Network Connection                                      | 1        | 1.04%   |
| Intel Ethernet Controller I225-V                                           | 1        | 1.04%   |
| Intel Ethernet Connection I217-V                                           | 1        | 1.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 7        | 31.82%  |
| Realtek Semiconductor    | 5        | 22.73%  |
| TP-Link                  | 3        | 13.64%  |
| Qualcomm Atheros         | 3        | 13.64%  |
| Ralink Technology        | 2        | 9.09%   |
| Ralink                   | 1        | 4.55%   |
| Micro Star International | 1        | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EE Wireless Network Adapter                                 | 2        | 9.09%   |
| Ralink MT7601U Wireless Adapter                                            | 2        | 9.09%   |
| Intel Wi-Fi 6 AX200                                                        | 2        | 9.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 9.09%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1        | 4.55%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                      | 1        | 4.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1        | 4.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 1        | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 4.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 4.55%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1        | 4.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1        | 4.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 4.55%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 4.55%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 4.55%   |
| Intel Wireless-AC 9260                                                     | 1        | 4.55%   |
| Intel Wireless 7260                                                        | 1        | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Realtek Semiconductor  | 29       | 42.65%  |
| Intel                  | 27       | 39.71%  |
| Broadcom               | 3        | 4.41%   |
| Qualcomm Atheros       | 2        | 2.94%   |
| Nvidia                 | 2        | 2.94%   |
| VIA Technologies       | 1        | 1.47%   |
| Qualcomm               | 1        | 1.47%   |
| Mellanox Technologies  | 1        | 1.47%   |
| Chelsio Communications | 1        | 1.47%   |
| Broadcom Limited       | 1        | 1.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 22       | 29.73%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 9.46%   |
| Intel Ethernet Connection (2) I218-V                                          | 4        | 5.41%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 5.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 4.05%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 2.7%    |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2.7%    |
| Intel 82579V Gigabit Network Connection                                       | 2        | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 2.7%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 2.7%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 2        | 2.7%    |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 1.35%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.35%   |
| Qualcomm MegaFon M150-4                                                       | 1        | 1.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 1.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 1.35%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 1.35%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 1.35%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 1.35%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.35%   |
| Intel Ethernet Controller I225-V                                              | 1        | 1.35%   |
| Intel Ethernet Connection I217-V                                              | 1        | 1.35%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 1.35%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 1.35%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 1.35%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 1.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.35%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 1.35%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1        | 1.35%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 1.35%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 1.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 58       | 72.5%   |
| WiFi     | 22       | 27.5%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 85.71%  |
| WiFi     | 8        | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 55%     |
| 2     | 17       | 28.33%  |
| 3     | 5        | 8.33%   |
| 4     | 3        | 5%      |
| 5     | 1        | 1.67%   |
| 0     | 1        | 1.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 89.83%  |
| Yes  | 6        | 10.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Cambridge Silicon Radio  | 11       | 50%     |
| Intel                    | 6        | 27.27%  |
| Micro Star International | 2        | 9.09%   |
| TP-Link                  | 1        | 4.55%   |
| Realtek Semiconductor    | 1        | 4.55%   |
| Broadcom                 | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 50%     |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 9.09%   |
| Intel AX200 Bluetooth                               | 2        | 9.09%   |
| TP-Link UB500 Adapter                               | 1        | 4.55%   |
| Realtek Bluetooth Radio                             | 1        | 4.55%   |
| Micro Star International Bluetooth Dongle           | 1        | 4.55%   |
| Micro Star International Bluetooth Device           | 1        | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.55%   |
| Intel Bluetooth wireless interface                  | 1        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 28       | 31.82%  |
| AMD                 | 27       | 30.68%  |
| Nvidia              | 19       | 21.59%  |
| Creative Labs       | 7        | 7.95%   |
| VIA Technologies    | 1        | 1.14%   |
| Texas Instruments   | 1        | 1.14%   |
| RME                 | 1        | 1.14%   |
| M-Audio             | 1        | 1.14%   |
| EGO SYStems         | 1        | 1.14%   |
| C-Media Electronics | 1        | 1.14%   |
| ASUSTek Computer    | 1        | 1.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 9        | 8.26%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                  | 6        | 5.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 5        | 4.59%   |
| AMD FCH Azalia Controller                                                                       | 4        | 3.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 3        | 2.75%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 3        | 2.75%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 3        | 2.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 3        | 2.75%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 3        | 2.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 3        | 2.75%   |
| AMD Navi 10 HDMI Audio                                                                          | 3        | 2.75%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 3        | 2.75%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 3        | 2.75%   |
| Nvidia MCP61 High Definition Audio                                                              | 2        | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 2        | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                                      | 2        | 1.83%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 2        | 1.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 2        | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2        | 1.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 2        | 1.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 2        | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 2        | 1.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 2        | 1.83%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                     | 1        | 0.92%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 1        | 0.92%   |
| RME ADI-2 DAC (57750520)                                                                        | 1        | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 1        | 0.92%   |
| Nvidia MCP79 High Definition Audio                                                              | 1        | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 0.92%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 1        | 0.92%   |
| Nvidia GM204 High Definition Audio Controller                                                   | 1        | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 1        | 0.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 1        | 0.92%   |
| Nvidia GK110 High Definition Audio Controller                                                   | 1        | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 1        | 0.92%   |
| Nvidia GK104 HDMI Audio Controller                                                              | 1        | 0.92%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 1        | 0.92%   |
| M-Audio M-Audio MobilePre                                                                       | 1        | 0.92%   |
| Intel Sunrise Point-LP HD Audio                                                                 | 1        | 0.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 15       | 23.08%  |
| Corsair             | 9        | 13.85%  |
| Unknown             | 6        | 9.23%   |
| SK hynix            | 6        | 9.23%   |
| Samsung Electronics | 6        | 9.23%   |
| Crucial             | 5        | 7.69%   |
| Team                | 4        | 6.15%   |
| Transcend           | 2        | 3.08%   |
| Micron Technology   | 2        | 3.08%   |
| Unknown             | 2        | 3.08%   |
| Strontium           | 1        | 1.54%   |
| Silicon Power       | 1        | 1.54%   |
| HPE                 | 1        | 1.54%   |
| GLOWAY              | 1        | 1.54%   |
| G.Skill             | 1        | 1.54%   |
| AMD                 | 1        | 1.54%   |
| A-DATA Technology   | 1        | 1.54%   |
| A Force             | 1        | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2        | 2.74%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s         | 2        | 2.74%   |
| Unknown                                                     | 2        | 2.74%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                   | 1        | 1.37%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s               | 1        | 1.37%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                  | 1        | 1.37%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                      | 1        | 1.37%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 1.37%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 1.37%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s           | 1        | 1.37%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s       | 1        | 1.37%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s          | 1        | 1.37%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s         | 1        | 1.37%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s       | 1        | 1.37%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s | 1        | 1.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1        | 1.37%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s        | 1        | 1.37%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s     | 1        | 1.37%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1        | 1.37%   |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s        | 1        | 1.37%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s   | 1        | 1.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1        | 1.37%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1        | 1.37%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.37%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s        | 1        | 1.37%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 1.37%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 1.37%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.37%   |
| Micron RAM 36KSF1G72PZ-1G4K1 8192MB DIMM DDR3 1333MT/s      | 1        | 1.37%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s         | 1        | 1.37%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s        | 1        | 1.37%   |
| Kingston RAM Module 2048MB FB-DIMM DDR2 667MT/s             | 1        | 1.37%   |
| Kingston RAM KHX3600C17D4/8GX 8GB DIMM DDR4 3600MT/s        | 1        | 1.37%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s        | 1        | 1.37%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s        | 1        | 1.37%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 1        | 1.37%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s      | 1        | 1.37%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s         | 1        | 1.37%   |
| Kingston RAM HP32D4U2S8MR-8 8GB DIMM DDR4 3200MT/s          | 1        | 1.37%   |
| Kingston RAM ACR128X64D2S800C6 1GB SODIMM DDR2 975MT/s      | 1        | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 24       | 43.64%  |
| DDR3    | 24       | 43.64%  |
| DDR2    | 3        | 5.45%   |
| SDRAM   | 2        | 3.64%   |
| DDR     | 1        | 1.82%   |
| Unknown | 1        | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 51       | 91.07%  |
| SODIMM  | 3        | 5.36%   |
| RIMM    | 1        | 1.79%   |
| FB-DIMM | 1        | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 22       | 36.07%  |
| 4096  | 15       | 24.59%  |
| 16384 | 8        | 13.11%  |
| 32768 | 6        | 9.84%   |
| 2048  | 6        | 9.84%   |
| 1024  | 4        | 6.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 21.31%  |
| 3600    | 6        | 9.84%   |
| 2400    | 5        | 8.2%    |
| 1333    | 5        | 8.2%    |
| 667     | 4        | 6.56%   |
| 3800    | 3        | 4.92%   |
| 3200    | 3        | 4.92%   |
| 2667    | 2        | 3.28%   |
| 2666    | 2        | 3.28%   |
| 2133    | 2        | 3.28%   |
| 1867    | 2        | 3.28%   |
| 1866    | 2        | 3.28%   |
| Unknown | 2        | 3.28%   |
| 65535   | 1        | 1.64%   |
| 3733    | 1        | 1.64%   |
| 2933    | 1        | 1.64%   |
| 2800    | 1        | 1.64%   |
| 2472    | 1        | 1.64%   |
| 2187    | 1        | 1.64%   |
| 2000    | 1        | 1.64%   |
| 1066    | 1        | 1.64%   |
| 975     | 1        | 1.64%   |
| 800     | 1        | 1.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 37.5%   |
| Brother Industries  | 2        | 25%     |
| QinHeng Electronics | 1        | 12.5%   |
| Dell                | 1        | 12.5%   |
| Canon               | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| QinHeng CH340S               | 1        | 12.5%   |
| HP OfficeJet Pro 9010 series | 1        | 12.5%   |
| HP ENVY 4520 series          | 1        | 12.5%   |
| HP ENVY 4500 series          | 1        | 12.5%   |
| Dell 2330d Laser Printer     | 1        | 12.5%   |
| Canon CanoScan LiDE 300      | 1        | 12.5%   |
| Brother Printer              | 1        | 12.5%   |
| Brother HL-L2320D series     | 1        | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 1        | 50%     |
| Hewlett-Packard | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 50%     |
| HP ScanJet 5590                               | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Logitech  | 9        | 81.82%  |
| Microsoft | 1        | 9.09%   |
| Microdia  | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 2        | 18.18%  |
| Microsoft LifeCam HD-3000       | 1        | 9.09%   |
| Microdia Camera                 | 1        | 9.09%   |
| Logitech Webcam C310            | 1        | 9.09%   |
| Logitech Webcam C300            | 1        | 9.09%   |
| Logitech Webcam C170            | 1        | 9.09%   |
| Logitech QuickCam Pro 9000      | 1        | 9.09%   |
| Logitech HD Webcam C525         | 1        | 9.09%   |
| Logitech HD Pro Webcam C920     | 1        | 9.09%   |
| Logitech C922 Pro Stream Webcam | 1        | 9.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| STMicroelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 38       | 65.52%  |
| 1     | 9        | 15.52%  |
| 4     | 4        | 6.9%    |
| 2     | 4        | 6.9%    |
| 3     | 3        | 5.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 10       | 27.03%  |
| Graphics card            | 7        | 18.92%  |
| Communication controller | 6        | 16.22%  |
| Net/wireless             | 4        | 10.81%  |
| Unassigned class         | 3        | 8.11%   |
| Bluetooth                | 2        | 5.41%   |
| Storage/ata              | 1        | 2.7%    |
| Net/ethernet             | 1        | 2.7%    |
| Fingerprint reader       | 1        | 2.7%    |
| Chipcard                 | 1        | 2.7%    |
| Card reader              | 1        | 2.7%    |

