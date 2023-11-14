openSUSE Leap-15.4 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.4.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 96

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Medion   | MS-7848                     | [ab89c9cc22](https://linux-hardware.org/?probe=ab89c9cc22) | Oct 26, 2023 |
| Gigabyte | F2A78M-HD2                  | [4e83b42f8d](https://linux-hardware.org/?probe=4e83b42f8d) | Oct 11, 2023 |
| Gigabyte | F2A78M-HD2                  | [e9b2c833e0](https://linux-hardware.org/?probe=e9b2c833e0) | Oct 08, 2023 |
| Fujitsu  | D3401-A1 S26361-D3401-A1    | [5d41b45d45](https://linux-hardware.org/?probe=5d41b45d45) | Sep 30, 2023 |
| Fujitsu  | D3401-A1 S26361-D3401-A1    | [65643e78ef](https://linux-hardware.org/?probe=65643e78ef) | Sep 30, 2023 |
| HP       | 0B4Ch D                     | [1521626729](https://linux-hardware.org/?probe=1521626729) | Sep 02, 2023 |
| ASUSTek  | P5Q-PRO                     | [625ff7df38](https://linux-hardware.org/?probe=625ff7df38) | Aug 22, 2023 |
| Dell     | 0427JK A00                  | [857e3132c1](https://linux-hardware.org/?probe=857e3132c1) | Aug 19, 2023 |
| ASRock   | Z270 Pro4                   | [de0587ccf3](https://linux-hardware.org/?probe=de0587ccf3) | Aug 19, 2023 |
| HP       | 0B4Ch D                     | [e21dbce888](https://linux-hardware.org/?probe=e21dbce888) | Aug 17, 2023 |
| HP       | 0B4Ch D                     | [35e4fef6c6](https://linux-hardware.org/?probe=35e4fef6c6) | Aug 07, 2023 |
| HP       | 0B4Ch D                     | [297a14921c](https://linux-hardware.org/?probe=297a14921c) | Aug 04, 2023 |
| HP       | 0B4Ch D                     | [46e96687a1](https://linux-hardware.org/?probe=46e96687a1) | Aug 04, 2023 |
| Dell     | 09M8Y8 A01                  | [e5649696d0](https://linux-hardware.org/?probe=e5649696d0) | Aug 03, 2023 |
| HP       | 0B4Ch D                     | [270ce3344c](https://linux-hardware.org/?probe=270ce3344c) | Jul 28, 2023 |
| ASUSTek  | P5E Deluxe                  | [895759fa79](https://linux-hardware.org/?probe=895759fa79) | Jul 01, 2023 |
| Gigabyte | Z97-HD3                     | [731b4a6479](https://linux-hardware.org/?probe=731b4a6479) | Jun 26, 2023 |
| ASUSTek  | P8H61-M LX                  | [23b64edd39](https://linux-hardware.org/?probe=23b64edd39) | Jun 17, 2023 |
| ASUSTek  | P5Q-PRO                     | [df63208f37](https://linux-hardware.org/?probe=df63208f37) | Jun 15, 2023 |
| ASUSTek  | PRIME B350-PLUS             | [cc1f571000](https://linux-hardware.org/?probe=cc1f571000) | Jun 09, 2023 |
| Lenovo   | 1036 SDK0K17763 WIN 1801... | [1d36e85f27](https://linux-hardware.org/?probe=1d36e85f27) | Jun 07, 2023 |
| ASUSTek  | P5Q-PRO                     | [76cd01b045](https://linux-hardware.org/?probe=76cd01b045) | Jun 03, 2023 |
| HP       | 0B4Ch D                     | [5352a94049](https://linux-hardware.org/?probe=5352a94049) | May 20, 2023 |
| Gigabyte | P55-UD3                     | [12da248164](https://linux-hardware.org/?probe=12da248164) | May 19, 2023 |
| Dell     | 0GY6Y8 A02                  | [99ad79383e](https://linux-hardware.org/?probe=99ad79383e) | May 11, 2023 |
| Lenovo   | 1036 SDK0K17763 WIN 1801... | [eeb37c9c4f](https://linux-hardware.org/?probe=eeb37c9c4f) | May 07, 2023 |
| ASRock   | B550M-ITX/ac                | [0295ab04a7](https://linux-hardware.org/?probe=0295ab04a7) | Apr 28, 2023 |
| Gigabyte | Z97-HD3                     | [ec41184680](https://linux-hardware.org/?probe=ec41184680) | Apr 27, 2023 |
| ASRock   | B550M-ITX/ac                | [4fad4d4a09](https://linux-hardware.org/?probe=4fad4d4a09) | Apr 21, 2023 |
| Gigabyte | H55M-S2H                    | [f44b68cf93](https://linux-hardware.org/?probe=f44b68cf93) | Apr 16, 2023 |
| ASRock   | X670E Pro RS                | [0f078152ca](https://linux-hardware.org/?probe=0f078152ca) | Apr 10, 2023 |
| ASRock   | B450 Gaming K4              | [dcf97ad331](https://linux-hardware.org/?probe=dcf97ad331) | Apr 05, 2023 |
| MSI      | P67A-C43                    | [f3e7913310](https://linux-hardware.org/?probe=f3e7913310) | Apr 01, 2023 |
| ASUSTek  | ROG CROSSHAIR X670E HERO    | [f78ca791e0](https://linux-hardware.org/?probe=f78ca791e0) | Mar 25, 2023 |
| Wortmann | Terra 3100                  | [126586f434](https://linux-hardware.org/?probe=126586f434) | Mar 12, 2023 |
| Lenovo   | 102F SDK0J40697 WIN 3305... | [97741c600c](https://linux-hardware.org/?probe=97741c600c) | Mar 11, 2023 |
| Gigabyte | Z97-HD3                     | [5cb06ca8ce](https://linux-hardware.org/?probe=5cb06ca8ce) | Mar 10, 2023 |
| Dell     | 0427JK A00                  | [4b47face39](https://linux-hardware.org/?probe=4b47face39) | Mar 05, 2023 |
| Lenovo   | Bantry CRB 31900058 STD     | [268413a47c](https://linux-hardware.org/?probe=268413a47c) | Mar 01, 2023 |
| Lenovo   | Bantry CRB 31900058 STD     | [169e938f25](https://linux-hardware.org/?probe=169e938f25) | Mar 01, 2023 |
| Dell     | 0427JK A00                  | [ca878d6577](https://linux-hardware.org/?probe=ca878d6577) | Feb 27, 2023 |
| ASRock   | B550M-ITX/ac                | [79204339d0](https://linux-hardware.org/?probe=79204339d0) | Feb 11, 2023 |
| HP       | 1494                        | [ba7c61bf23](https://linux-hardware.org/?probe=ba7c61bf23) | Feb 07, 2023 |
| HP       | 0B54h D                     | [fa38931f1f](https://linux-hardware.org/?probe=fa38931f1f) | Feb 06, 2023 |
| Gigabyte | Z690 GAMING X DDR4          | [f2636de53b](https://linux-hardware.org/?probe=f2636de53b) | Jan 31, 2023 |
| ASUSTek  | CROSSHAIR V FORMULA-Z       | [32dfb5ebe2](https://linux-hardware.org/?probe=32dfb5ebe2) | Jan 31, 2023 |
| Gigabyte | Z690 GAMING X DDR4          | [6bf8eb9c73](https://linux-hardware.org/?probe=6bf8eb9c73) | Jan 30, 2023 |
| ASUSTek  | PRIME A320M-K               | [17fd020689](https://linux-hardware.org/?probe=17fd020689) | Jan 16, 2023 |
| Dell     | 0WG261                      | [c994d9e8ee](https://linux-hardware.org/?probe=c994d9e8ee) | Jan 13, 2023 |
| Dell     | 0WG261                      | [5d1fe40a1f](https://linux-hardware.org/?probe=5d1fe40a1f) | Jan 13, 2023 |
| MSI      | X470 GAMING PRO CARBON      | [947534b3be](https://linux-hardware.org/?probe=947534b3be) | Dec 09, 2022 |
| ASUSTek  | PRIME B350M-A               | [31ae5769eb](https://linux-hardware.org/?probe=31ae5769eb) | Dec 07, 2022 |
| MSI      | B85-G41 PC Mate             | [a54611689d](https://linux-hardware.org/?probe=a54611689d) | Dec 06, 2022 |
| Dell     | 0C522T A01                  | [efee8139b0](https://linux-hardware.org/?probe=efee8139b0) | Nov 01, 2022 |
| Gigabyte | GA-770TA-UD3                | [4833a609c3](https://linux-hardware.org/?probe=4833a609c3) | Oct 31, 2022 |
| Lenovo   | 1036 SDK0K17763 WIN 1801... | [94f3d7aa9d](https://linux-hardware.org/?probe=94f3d7aa9d) | Oct 22, 2022 |
| ASUSTek  | P5P43TD PRO                 | [a29fae2a74](https://linux-hardware.org/?probe=a29fae2a74) | Oct 14, 2022 |
| MSI      | Z170-A PRO                  | [50b8cde0ed](https://linux-hardware.org/?probe=50b8cde0ed) | Oct 10, 2022 |
| MSI      | B450-A PRO MAX              | [c12ce7288b](https://linux-hardware.org/?probe=c12ce7288b) | Oct 05, 2022 |
| MSI      | B450-A PRO MAX              | [c3306965d6](https://linux-hardware.org/?probe=c3306965d6) | Oct 05, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII EXTRE... | [6e0984d7ff](https://linux-hardware.org/?probe=6e0984d7ff) | Sep 06, 2022 |
| ASUSTek  | P5P43TD PRO                 | [f79c38f9ff](https://linux-hardware.org/?probe=f79c38f9ff) | Sep 02, 2022 |
| Lenovo   | 1036 SDK0K17763 WIN 1801... | [3772ec2911](https://linux-hardware.org/?probe=3772ec2911) | Sep 02, 2022 |
| ASRock   | J3355B-ITX                  | [e27f786190](https://linux-hardware.org/?probe=e27f786190) | Aug 28, 2022 |
| Gigabyte | 965P-DS3                    | [38a4407789](https://linux-hardware.org/?probe=38a4407789) | Aug 25, 2022 |
| HP       | 802F                        | [2c52215323](https://linux-hardware.org/?probe=2c52215323) | Aug 23, 2022 |
| HP       | 802F                        | [e181d03426](https://linux-hardware.org/?probe=e181d03426) | Aug 23, 2022 |
| ASRock   | Z490 Phantom Gaming 4       | [7b66b20b9f](https://linux-hardware.org/?probe=7b66b20b9f) | Aug 17, 2022 |
| ASRock   | J3355B-ITX                  | [99f7986364](https://linux-hardware.org/?probe=99f7986364) | Aug 02, 2022 |
| ASUSTek  | PRIME B550M-K               | [df5bd62f9a](https://linux-hardware.org/?probe=df5bd62f9a) | Jul 23, 2022 |
| Biostar  | B450MH                      | [f69c4e3a03](https://linux-hardware.org/?probe=f69c4e3a03) | Jul 21, 2022 |
| Biostar  | B450MH                      | [79084ef4c9](https://linux-hardware.org/?probe=79084ef4c9) | Jul 21, 2022 |
| ASUSTek  | TUF Gaming X570-PRO         | [f2cda5634e](https://linux-hardware.org/?probe=f2cda5634e) | Jul 18, 2022 |
| MSI      | B450 GAMING PRO CARBON A... | [03d7fde009](https://linux-hardware.org/?probe=03d7fde009) | Jul 18, 2022 |
| Dell     | 0Y2YM6 A00                  | [8b5480a55e](https://linux-hardware.org/?probe=8b5480a55e) | Jul 16, 2022 |
| MSI      | X399 GAMING PRO CARBON A... | [153a698b74](https://linux-hardware.org/?probe=153a698b74) | Jul 01, 2022 |
| Dell     | 0J3C2F A03                  | [6f5f6a7417](https://linux-hardware.org/?probe=6f5f6a7417) | Jun 26, 2022 |
| ASRock   | J3355B-ITX                  | [a00111330b](https://linux-hardware.org/?probe=a00111330b) | Jun 24, 2022 |
| ASUSTek  | TUF Gaming Z590-PLUS        | [520f9b42b8](https://linux-hardware.org/?probe=520f9b42b8) | Jun 20, 2022 |
| HP       | 87C3                        | [1383f85e70](https://linux-hardware.org/?probe=1383f85e70) | Jun 09, 2022 |
| ASUSTek  | TUF Gaming B550M-E          | [06e496124a](https://linux-hardware.org/?probe=06e496124a) | Jun 08, 2022 |
| ASUSTek  | TUF Gaming B550M-E          | [fd421da52b](https://linux-hardware.org/?probe=fd421da52b) | Jun 08, 2022 |
| MSI      | B450 TOMAHAWK               | [0020802901](https://linux-hardware.org/?probe=0020802901) | May 30, 2022 |
| ASUSTek  | TUF Gaming B550M-E          | [e01bfd360d](https://linux-hardware.org/?probe=e01bfd360d) | May 14, 2022 |
| ASUSTek  | PRIME B550M-A WIFI II       | [2e8f888ca3](https://linux-hardware.org/?probe=2e8f888ca3) | May 11, 2022 |
| ASUSTek  | M5A78L-M/USB3               | [ace8669bdd](https://linux-hardware.org/?probe=ace8669bdd) | May 10, 2022 |
| ASUSTek  | TUF Gaming B550M-E          | [99078d316d](https://linux-hardware.org/?probe=99078d316d) | May 10, 2022 |
| ASUSTek  | TUF Gaming B550M-E          | [a3c1257116](https://linux-hardware.org/?probe=a3c1257116) | May 09, 2022 |
| ASUSTek  | TUF Gaming B550M-E WIFI     | [27b384c114](https://linux-hardware.org/?probe=27b384c114) | May 08, 2022 |
| ASUSTek  | TUF Gaming B550M-E WIFI     | [d427368abd](https://linux-hardware.org/?probe=d427368abd) | May 08, 2022 |
| ASUSTek  | M4A785TD-V EVO              | [622ff28b28](https://linux-hardware.org/?probe=622ff28b28) | May 05, 2022 |
| ASUSTek  | CROSSHAIR V FORMULA-Z       | [e5a11e0fdd](https://linux-hardware.org/?probe=e5a11e0fdd) | May 04, 2022 |
| ASUSTek  | CROSSHAIR V FORMULA-Z       | [34dcc7bc0c](https://linux-hardware.org/?probe=34dcc7bc0c) | May 04, 2022 |
| ASUSTek  | M4A785TD-V EVO              | [aea37c880d](https://linux-hardware.org/?probe=aea37c880d) | May 04, 2022 |
| Intel    | DG965RY AAD41691-301        | [c2d30af3ce](https://linux-hardware.org/?probe=c2d30af3ce) | Dec 25, 2021 |
| Intel    | DG965RY AAD41691-301        | [586e536e6c](https://linux-hardware.org/?probe=586e536e6c) | Dec 25, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.14.21-150400.22-default           | 11       | 14.86%  |
| 5.14.21-150400.24.46-default        | 7        | 9.46%   |
| 5.14.21-150400.24.63-default        | 6        | 8.11%   |
| 5.14.21-150400.24.21-default        | 6        | 8.11%   |
| 5.14.21-150400.24.18-default        | 6        | 8.11%   |
| 5.14.21-150400.19-default           | 6        | 8.11%   |
| 5.14.21-150400.24.55-default        | 5        | 6.76%   |
| 5.14.21-150400.24.41-default        | 5        | 6.76%   |
| 5.14.21-150400.24.69-default        | 3        | 4.05%   |
| 5.14.21-150400.24.60-default        | 3        | 4.05%   |
| 5.14.21-150400.24.38-default        | 3        | 4.05%   |
| 5.14.21-150400.24.33-default        | 3        | 4.05%   |
| 5.18.0-rc6-lp153.2.ged50f8f-default | 2        | 2.7%    |
| 5.14.21-150400.24.84-default        | 2        | 2.7%    |
| 5.18.2-lp153.4.g6d13af9-default     | 1        | 1.35%   |
| 5.14.21-150500.43-default           | 1        | 1.35%   |
| 5.14.21-150400.24.88-default        | 1        | 1.35%   |
| 5.14.21-150400.24.81-default        | 1        | 1.35%   |
| 5.14.21-150400.24.11-default        | 1        | 1.35%   |
| 5.14.19-150400.1-default            | 1        | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.21 | 59       | 93.65%  |
| 5.18.0  | 2        | 3.17%   |
| 5.18.2  | 1        | 1.59%   |
| 5.14.19 | 1        | 1.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 60       | 95.24%  |
| 5.18    | 3        | 4.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 62       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KDE5        | 46       | 73.02%  |
| GNOME       | 7        | 11.11%  |
| Unknown     | 6        | 9.52%   |
| XFCE        | 3        | 4.76%   |
| WindowMaker | 1        | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 52       | 83.87%  |
| Wayland | 6        | 9.68%   |
| Tty     | 2        | 3.23%   |
| Unknown | 2        | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 48.39%  |
| SDDM    | 20       | 32.26%  |
| LightDM | 11       | 17.74%  |
| XDM     | 1        | 1.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 21       | 33.33%  |
| de_DE   | 12       | 19.05%  |
| POSIX   | 10       | 15.87%  |
| pt_BR   | 4        | 6.35%   |
| nl_NL   | 3        | 4.76%   |
| fr_FR   | 3        | 4.76%   |
| en_GB   | 2        | 3.17%   |
| ru_RU   | 1        | 1.59%   |
| ro_RO   | 1        | 1.59%   |
| pl_PL   | 1        | 1.59%   |
| es_ES   | 1        | 1.59%   |
| el_GR   | 1        | 1.59%   |
| de_CH   | 1        | 1.59%   |
| ca_ES   | 1        | 1.59%   |
| Unknown | 1        | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 43       | 68.25%  |
| EFI  | 20       | 31.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 39       | 62.9%   |
| Ext4  | 21       | 33.87%  |
| Xfs   | 1        | 1.61%   |
| Ext3  | 1        | 1.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 28       | 44.44%  |
| Unknown | 27       | 42.86%  |
| MBR     | 8        | 12.7%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 84.13%  |
| Yes       | 10       | 15.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 80.65%  |
| Yes       | 12       | 19.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 33.87%  |
| MSI                 | 8        | 12.9%   |
| Gigabyte Technology | 7        | 11.29%  |
| Dell                | 7        | 11.29%  |
| ASRock              | 6        | 9.68%   |
| Hewlett-Packard     | 5        | 8.06%   |
| Lenovo              | 3        | 4.84%   |
| Wortmann AG         | 1        | 1.61%   |
| Medion              | 1        | 1.61%   |
| Intel               | 1        | 1.61%   |
| Fujitsu             | 1        | 1.61%   |
| Biostar             | 1        | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS TUF Gaming B550M-E             | 2        | 3.23%   |
| ASUS P5Q-PRO                        | 2        | 3.23%   |
| ASUS M4A785TD-V EVO                 | 2        | 3.23%   |
| ASUS CROSSHAIR V FORMULA-Z          | 2        | 3.23%   |
| Wortmann AG Terra 3100              | 1        | 1.61%   |
| MSI MS-7C02                         | 1        | 1.61%   |
| MSI MS-7B86                         | 1        | 1.61%   |
| MSI MS-7B85                         | 1        | 1.61%   |
| MSI MS-7B78                         | 1        | 1.61%   |
| MSI MS-7B09                         | 1        | 1.61%   |
| MSI MS-7971                         | 1        | 1.61%   |
| MSI MS-7850                         | 1        | 1.61%   |
| MSI MS-7673                         | 1        | 1.61%   |
| Medion MS-7848                      | 1        | 1.61%   |
| Lenovo ThinkStation P520 30BE008VGE | 1        | 1.61%   |
| Lenovo ThinkStation P500 30A6S4JU00 | 1        | 1.61%   |
| Lenovo H50-55 90BF001SUK            | 1        | 1.61%   |
| Intel DG965RY AAD41691-301          | 1        | 1.61%   |
| HP Z600 Workstation                 | 1        | 1.61%   |
| HP Z400 Workstation                 | 1        | 1.61%   |
| HP Z240 Tower Workstation           | 1        | 1.61%   |
| HP OMEN 30L Desktop GT13-0xxx       | 1        | 1.61%   |
| HP Compaq 8200 Elite CMT PC         | 1        | 1.61%   |
| Gigabyte Z97-HD3                    | 1        | 1.61%   |
| Gigabyte Z690 GAMING X DDR4         | 1        | 1.61%   |
| Gigabyte P55-UD3                    | 1        | 1.61%   |
| Gigabyte H55M-S2H                   | 1        | 1.61%   |
| Gigabyte GA-770TA-UD3               | 1        | 1.61%   |
| Gigabyte F2A78M-HD2                 | 1        | 1.61%   |
| Gigabyte 965P-DS3                   | 1        | 1.61%   |
| Fujitsu ESPRIMO_P756                | 1        | 1.61%   |
| Dell XPS 8940                       | 1        | 1.61%   |
| Dell Vostro 3268                    | 1        | 1.61%   |
| Dell Precision T3610                | 1        | 1.61%   |
| Dell OptiPlex 980                   | 1        | 1.61%   |
| Dell OptiPlex 790                   | 1        | 1.61%   |
| Dell OptiPlex 7010                  | 1        | 1.61%   |
| Dell DM051                          | 1        | 1.61%   |
| Biostar B450MH                      | 1        | 1.61%   |
| ASUS TUF Gaming Z590-PLUS           | 1        | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS TUF              | 5        | 8.06%   |
| ASUS PRIME            | 5        | 8.06%   |
| Dell OptiPlex         | 3        | 4.84%   |
| Lenovo ThinkStation   | 2        | 3.23%   |
| ASUS ROG              | 2        | 3.23%   |
| ASUS P5Q-PRO          | 2        | 3.23%   |
| ASUS M4A785TD-V       | 2        | 3.23%   |
| ASUS CROSSHAIR        | 2        | 3.23%   |
| Wortmann AG Terra     | 1        | 1.61%   |
| MSI MS-7C02           | 1        | 1.61%   |
| MSI MS-7B86           | 1        | 1.61%   |
| MSI MS-7B85           | 1        | 1.61%   |
| MSI MS-7B78           | 1        | 1.61%   |
| MSI MS-7B09           | 1        | 1.61%   |
| MSI MS-7971           | 1        | 1.61%   |
| MSI MS-7850           | 1        | 1.61%   |
| MSI MS-7673           | 1        | 1.61%   |
| Medion MS-7848        | 1        | 1.61%   |
| Lenovo H50-55         | 1        | 1.61%   |
| Intel DG965RY         | 1        | 1.61%   |
| HP Z600               | 1        | 1.61%   |
| HP Z400               | 1        | 1.61%   |
| HP Z240               | 1        | 1.61%   |
| HP OMEN               | 1        | 1.61%   |
| HP Compaq             | 1        | 1.61%   |
| Gigabyte Z97-HD3      | 1        | 1.61%   |
| Gigabyte Z690         | 1        | 1.61%   |
| Gigabyte P55-UD3      | 1        | 1.61%   |
| Gigabyte H55M-S2H     | 1        | 1.61%   |
| Gigabyte GA-770TA-UD3 | 1        | 1.61%   |
| Gigabyte F2A78M-HD2   | 1        | 1.61%   |
| Gigabyte 965P-DS3     | 1        | 1.61%   |
| Fujitsu ESPRIMO       | 1        | 1.61%   |
| Dell XPS              | 1        | 1.61%   |
| Dell Vostro           | 1        | 1.61%   |
| Dell Precision        | 1        | 1.61%   |
| Dell DM051            | 1        | 1.61%   |
| Biostar B450MH        | 1        | 1.61%   |
| ASUS P5P43TD          | 1        | 1.61%   |
| ASUS P5E              | 1        | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2017 | 7        | 11.29%  |
| 2021 | 6        | 9.68%   |
| 2022 | 5        | 8.06%   |
| 2020 | 5        | 8.06%   |
| 2009 | 5        | 8.06%   |
| 2018 | 4        | 6.45%   |
| 2015 | 4        | 6.45%   |
| 2013 | 4        | 6.45%   |
| 2011 | 4        | 6.45%   |
| 2010 | 4        | 6.45%   |
| 2014 | 3        | 4.84%   |
| 2008 | 3        | 4.84%   |
| 2016 | 2        | 3.23%   |
| 2012 | 2        | 3.23%   |
| 2019 | 1        | 1.61%   |
| 2007 | 1        | 1.61%   |
| 2006 | 1        | 1.61%   |
| 2005 | 1        | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 62       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 62       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 16       | 25%     |
| 8.01-16.0       | 14       | 21.88%  |
| 16.01-24.0      | 13       | 20.31%  |
| 64.01-256.0     | 8        | 12.5%   |
| 4.01-8.0        | 6        | 9.38%   |
| 3.01-4.0        | 3        | 4.69%   |
| 24.01-32.0      | 3        | 4.69%   |
| More than 256.0 | 1        | 1.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 22       | 32.84%  |
| 4.01-8.0  | 16       | 23.88%  |
| 3.01-4.0  | 12       | 17.91%  |
| 1.01-2.0  | 10       | 14.93%  |
| 8.01-16.0 | 5        | 7.46%   |
| 0.51-1.0  | 2        | 2.99%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 30.77%  |
| 1      | 16       | 24.62%  |
| 3      | 15       | 23.08%  |
| 5      | 6        | 9.23%   |
| 4      | 3        | 4.62%   |
| 7      | 2        | 3.08%   |
| 6      | 2        | 3.08%   |
| 9      | 1        | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 36       | 58.06%  |
| No        | 26       | 41.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 61       | 98.39%  |
| No        | 1        | 1.61%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 64.52%  |
| Yes       | 22       | 35.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 63.49%  |
| Yes       | 23       | 36.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 22       | 35.48%  |
| USA          | 8        | 12.9%   |
| Brazil       | 4        | 6.45%   |
| Russia       | 3        | 4.84%   |
| Netherlands  | 3        | 4.84%   |
| France       | 3        | 4.84%   |
| UK           | 2        | 3.23%   |
| Switzerland  | 2        | 3.23%   |
| Spain        | 2        | 3.23%   |
| South Africa | 1        | 1.61%   |
| Serbia       | 1        | 1.61%   |
| Romania      | 1        | 1.61%   |
| Poland       | 1        | 1.61%   |
| Norway       | 1        | 1.61%   |
| Martinique   | 1        | 1.61%   |
| Kazakhstan   | 1        | 1.61%   |
| Italy        | 1        | 1.61%   |
| India        | 1        | 1.61%   |
| Greece       | 1        | 1.61%   |
| Finland      | 1        | 1.61%   |
| Bulgaria     | 1        | 1.61%   |
| Australia    | 1        | 1.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Haßfurt              | 5        | 7.46%   |
| Stuttgart             | 2        | 2.99%   |
| Rio de Janeiro        | 2        | 2.99%   |
| Moscow                | 2        | 2.99%   |
| Bergisch Gladbach     | 2        | 2.99%   |
| Almere Stad           | 2        | 2.99%   |
| Zierikzee             | 1        | 1.49%   |
| West Bend             | 1        | 1.49%   |
| Ulyanovsk             | 1        | 1.49%   |
| Stadthagen            | 1        | 1.49%   |
| Santa Rosa            | 1        | 1.49%   |
| Sainte-Tulle          | 1        | 1.49%   |
| Saint-Andre-le-Puy    | 1        | 1.49%   |
| Rostock               | 1        | 1.49%   |
| Roslindale            | 1        | 1.49%   |
| Riviere Salee         | 1        | 1.49%   |
| Rattelsdorf           | 1        | 1.49%   |
| Ocala                 | 1        | 1.49%   |
| Nesebar               | 1        | 1.49%   |
| Mo i Rana             | 1        | 1.49%   |
| Milan                 | 1        | 1.49%   |
| Melbourne             | 1        | 1.49%   |
| Lyss                  | 1        | 1.49%   |
| Ludwigshafen am Rhein | 1        | 1.49%   |
| Louisville            | 1        | 1.49%   |
| Le Lamentin           | 1        | 1.49%   |
| Lausanne              | 1        | 1.49%   |
| Kurten                | 1        | 1.49%   |
| Kulmbach              | 1        | 1.49%   |
| Kouvola               | 1        | 1.49%   |
| Kluszkowce            | 1        | 1.49%   |
| Kiel                  | 1        | 1.49%   |
| Johannesburg          | 1        | 1.49%   |
| Jegenstorf            | 1        | 1.49%   |
| Hyvinkaeae            | 1        | 1.49%   |
| Hyderabad             | 1        | 1.49%   |
| Hildesheim            | 1        | 1.49%   |
| Helpsen               | 1        | 1.49%   |
| Heilbronn             | 1        | 1.49%   |
| Hartenstein           | 1        | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 33       | 51     | 26.4%   |
| Samsung Electronics         | 23       | 40     | 18.4%   |
| WDC                         | 20       | 42     | 16%     |
| Kingston                    | 9        | 13     | 7.2%    |
| Crucial                     | 7        | 8      | 5.6%    |
| Toshiba                     | 6        | 7      | 4.8%    |
| SanDisk                     | 3        | 5      | 2.4%    |
| Patriot                     | 2        | 2      | 1.6%    |
| Maxtor                      | 2        | 2      | 1.6%    |
| Intenso                     | 2        | 3      | 1.6%    |
| Intel                       | 2        | 2      | 1.6%    |
| Hitachi                     | 2        | 2      | 1.6%    |
| Team                        | 1        | 1      | 0.8%    |
| StoreJet                    | 1        | 1      | 0.8%    |
| SPCC                        | 1        | 2      | 0.8%    |
| Smartbuy                    | 1        | 2      | 0.8%    |
| Silicon Motion              | 1        | 1      | 0.8%    |
| PNY                         | 1        | 1      | 0.8%    |
| Plextor                     | 1        | 3      | 0.8%    |
| Phison Electronics          | 1        | 1      | 0.8%    |
| MATSHITA                    | 1        | 1      | 0.8%    |
| Leven                       | 1        | 1      | 0.8%    |
| Kingston Technology Company | 1        | 1      | 0.8%    |
| HGST                        | 1        | 1      | 0.8%    |
| Fujitsu                     | 1        | 1      | 0.8%    |
| ADATA Technology            | 1        | 1      | 0.8%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 840 EVO 120GB                           | 5        | 3.25%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3        | 1.95%   |
| Samsung SSD 860 EVO 500GB                           | 3        | 1.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 3        | 1.95%   |
| Kingston SA400S37480G 480GB SSD                     | 3        | 1.95%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2        | 1.3%    |
| WDC WD10EZEX-08M2NA0 1TB                            | 2        | 1.3%    |
| WDC WD1003FZEX-00MK2A0 1TB                          | 2        | 1.3%    |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 1.3%    |
| Seagate ST3500418AS 500GB                           | 2        | 1.3%    |
| Seagate ST3000NM0053 3TB                            | 2        | 1.3%    |
| Seagate ST1000VX000-1CU162 1TB                      | 2        | 1.3%    |
| Seagate ST1000DM003-1CH162 1TB                      | 2        | 1.3%    |
| Seagate Expansion 1TB                               | 2        | 1.3%    |
| SanDisk NVMe SSD Drive 240GB                        | 2        | 1.3%    |
| Samsung SSD 870 QVO 2TB                             | 2        | 1.3%    |
| Samsung SSD 860 EVO 250GB                           | 2        | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB | 2        | 1.3%    |
| Kingston SA400S37960G 960GB SSD                     | 2        | 1.3%    |
| Kingston SA400S37240G 240GB SSD                     | 2        | 1.3%    |
| Crucial CT1000MX500SSD1 1TB                         | 2        | 1.3%    |
| WDC WDS500G1B0B-00AS40 500GB SSD                    | 1        | 0.65%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                    | 1        | 0.65%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 0.65%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1        | 0.65%   |
| WDC WD5000AZRX-00L4HB0 500GB                        | 1        | 0.65%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 1        | 0.65%   |
| WDC WD40EFRX-68WT0N0 4TB                            | 1        | 0.65%   |
| WDC WD4003FRYZ-01F0DB0 4TB                          | 1        | 0.65%   |
| WDC WD3200AAKX-00ERMA0 320GB                        | 1        | 0.65%   |
| WDC WD30EZRX-00SPEB0 3TB                            | 1        | 0.65%   |
| WDC WD20SPZX-22UA7T0 2TB                            | 1        | 0.65%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 0.65%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 1        | 0.65%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 1        | 0.65%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 1        | 0.65%   |
| WDC WD20EARX-00PASB0 2TB                            | 1        | 0.65%   |
| WDC WD20EARS-00MVWB0 2TB                            | 1        | 0.65%   |
| WDC WD120EDAZ-11F3RA0 12TB                          | 1        | 0.65%   |
| WDC WD10EZRX-00A8LB0 1TB                            | 1        | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 32       | 46     | 49.23%  |
| WDC                 | 19       | 36     | 29.23%  |
| Toshiba             | 4        | 5      | 6.15%   |
| Samsung Electronics | 4        | 4      | 6.15%   |
| Maxtor              | 2        | 2      | 3.08%   |
| Hitachi             | 2        | 2      | 3.08%   |
| HGST                | 1        | 1      | 1.54%   |
| Fujitsu             | 1        | 1      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 19     | 33.33%  |
| Kingston            | 7        | 9      | 13.73%  |
| Crucial             | 7        | 8      | 13.73%  |
| WDC                 | 5        | 5      | 9.8%    |
| Toshiba             | 2        | 2      | 3.92%   |
| Patriot             | 2        | 2      | 3.92%   |
| Intenso             | 2        | 3      | 3.92%   |
| Team                | 1        | 1      | 1.96%   |
| StoreJet            | 1        | 1      | 1.96%   |
| SPCC                | 1        | 2      | 1.96%   |
| Smartbuy            | 1        | 2      | 1.96%   |
| SanDisk             | 1        | 3      | 1.96%   |
| PNY                 | 1        | 1      | 1.96%   |
| Plextor             | 1        | 3      | 1.96%   |
| Leven               | 1        | 1      | 1.96%   |
| Intel               | 1        | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 50       | 97     | 45.05%  |
| SSD     | 41       | 63     | 36.94%  |
| NVMe    | 18       | 33     | 16.22%  |
| Unknown | 2        | 2      | 1.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 61       | 155    | 70.93%  |
| NVMe | 18       | 33     | 20.93%  |
| SAS  | 7        | 7      | 8.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 46       | 68     | 46.46%  |
| 0.51-1.0   | 24       | 48     | 24.24%  |
| 1.01-2.0   | 14       | 21     | 14.14%  |
| 2.01-3.0   | 6        | 7      | 6.06%   |
| 3.01-4.0   | 5        | 9      | 5.05%   |
| 4.01-10.0  | 3        | 6      | 3.03%   |
| 10.01-20.0 | 1        | 1      | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 25       | 40.32%  |
| 1001-2000      | 12       | 19.35%  |
| 2001-3000      | 9        | 14.52%  |
| 501-1000       | 7        | 11.29%  |
| 251-500        | 6        | 9.68%   |
| 21-50          | 1        | 1.61%   |
| 101-250        | 1        | 1.61%   |
| Unknown        | 1        | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 11       | 17.46%  |
| 501-1000       | 11       | 17.46%  |
| 51-100         | 11       | 17.46%  |
| 1001-2000      | 10       | 15.87%  |
| 251-500        | 8        | 12.7%   |
| More than 3000 | 5        | 7.94%   |
| 2001-3000      | 4        | 6.35%   |
| 21-50          | 1        | 1.59%   |
| 1-20           | 1        | 1.59%   |
| Unknown        | 1        | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 840 EVO 120GB | 4        | 5      | 33.33%  |
| WDC WD20EZRX-00D8PB0 2TB              | 1        | 1      | 8.33%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 1      | 8.33%   |
| Seagate ST9500420AS 500GB             | 1        | 1      | 8.33%   |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 8.33%   |
| Samsung Electronics SSD 850 PRO 256GB | 1        | 1      | 8.33%   |
| Maxtor 6L250S0 256GB                  | 1        | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 8.33%   |
| Intel SSD 600P Series 256GB           | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 6      | 41.67%  |
| WDC                 | 2        | 2      | 16.67%  |
| Seagate             | 2        | 2      | 16.67%  |
| Maxtor              | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Intel               | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 40%     |
| Seagate | 2        | 2      | 40%     |
| Maxtor  | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 6        | 7      | 54.55%  |
| HDD  | 4        | 5      | 36.36%  |
| NVMe | 1        | 1      | 9.09%   |

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
| Works    | 33       | 83     | 45.83%  |
| Detected | 28       | 99     | 38.89%  |
| Malfunc  | 11       | 13     | 15.28%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 34       | 33.33%  |
| AMD                         | 29       | 28.43%  |
| Samsung Electronics         | 8        | 7.84%   |
| ASMedia Technology          | 6        | 5.88%   |
| JMicron Technology          | 5        | 4.9%    |
| Marvell Technology Group    | 4        | 3.92%   |
| Kingston Technology Company | 4        | 3.92%   |
| SanDisk                     | 3        | 2.94%   |
| Seagate Technology          | 2        | 1.96%   |
| LSI Logic / Symbios Logic   | 2        | 1.96%   |
| Silicon Motion              | 1        | 0.98%   |
| Silicon Image               | 1        | 0.98%   |
| Promise Technology          | 1        | 0.98%   |
| Phison Electronics          | 1        | 0.98%   |
| ADATA Technology            | 1        | 0.98%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 11.2%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 5.6%    |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 4.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 4%      |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 4%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 4%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 3.2%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 2.4%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 2.4%    |
| Seagate FireCuda 530 SSD                                                                | 2        | 1.6%    |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 2        | 1.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.6%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.6%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.6%    |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                                 | 2        | 1.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.6%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.6%    |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.6%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 0.8%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.8%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.8%    |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.8%    |
| Promise PDC40719 [FastTrak TX4300/TX4310]                                               | 1        | 0.8%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 1        | 0.8%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.8%    |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.8%    |
| Marvell Group 88SE9125 PCIe SATA 6.0 Gb/s controller                                    | 1        | 0.8%    |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.8%    |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1        | 0.8%    |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 0.8%    |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 1        | 0.8%    |
| Kingston Company NV2 NVMe SSD E21T                                                      | 1        | 0.8%    |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 1        | 0.8%    |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 1        | 0.8%    |
| JMicron JMB368 IDE controller                                                           | 1        | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 56       | 58.95%  |
| NVMe | 18       | 18.95%  |
| IDE  | 17       | 17.89%  |
| RAID | 3        | 3.16%   |
| SCSI | 1        | 1.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 33       | 53.23%  |
| AMD    | 29       | 46.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 7 5700G with Radeon Graphics         | 4        | 6.45%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 3        | 4.84%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 2        | 3.23%   |
| Intel Core i5 CPU 750 @ 2.67GHz                | 2        | 3.23%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz          | 2        | 3.23%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 3.23%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 3.23%   |
| AMD Phenom II X6 1100T Processor               | 2        | 3.23%   |
| AMD FX-8350 Eight-Core Processor               | 2        | 3.23%   |
| Intel Xeon W-2135 CPU @ 3.70GHz                | 1        | 1.61%   |
| Intel Xeon CPU X5675 @ 3.07GHz                 | 1        | 1.61%   |
| Intel Xeon CPU W3530 @ 2.80GHz                 | 1        | 1.61%   |
| Intel Xeon CPU E5450 @ 3.00GHz                 | 1        | 1.61%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz            | 1        | 1.61%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz            | 1        | 1.61%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz            | 1        | 1.61%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz    | 1        | 1.61%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 1.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 1.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 1.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1        | 1.61%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 1.61%   |
| Intel Core i5-4430 CPU @ 3.00GHz               | 1        | 1.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 1.61%   |
| Intel Core i5-2500 CPU @ 3.30GHz               | 1        | 1.61%   |
| Intel Core i5-2400S CPU @ 2.50GHz              | 1        | 1.61%   |
| Intel Core i5-10500 CPU @ 3.10GHz              | 1        | 1.61%   |
| Intel Core i3-4150T CPU @ 3.00GHz              | 1        | 1.61%   |
| Intel Core i3 CPU 540 @ 3.07GHz                | 1        | 1.61%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz          | 1        | 1.61%   |
| Intel Core 2 CPU 6700 @ 2.66GHz                | 1        | 1.61%   |
| Intel Celeron CPU J3355 @ 2.00GHz              | 1        | 1.61%   |
| Intel Atom CPU D525 @ 1.80GHz                  | 1        | 1.61%   |
| Intel 12th Gen Core i7-12700KF                 | 1        | 1.61%   |
| Intel 11th Gen Core i9-11900 @ 2.50GHz         | 1        | 1.61%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz        | 1        | 1.61%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 1.61%   |
| AMD Ryzen 9 7950X 16-Core Processor            | 1        | 1.61%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 1.61%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 11       | 17.74%  |
| AMD Ryzen 7             | 8        | 12.9%   |
| AMD Ryzen 5             | 8        | 12.9%   |
| Intel Xeon              | 7        | 11.29%  |
| Other                   | 3        | 4.84%   |
| Intel Core 2 Quad       | 3        | 4.84%   |
| AMD Ryzen 9             | 3        | 4.84%   |
| Intel Core i7           | 2        | 3.23%   |
| Intel Core i3           | 2        | 3.23%   |
| AMD Phenom II X6        | 2        | 3.23%   |
| AMD Phenom II X4        | 2        | 3.23%   |
| AMD FX                  | 2        | 3.23%   |
| Intel Pentium Dual-Core | 1        | 1.61%   |
| Intel Pentium 4         | 1        | 1.61%   |
| Intel Core 2            | 1        | 1.61%   |
| Intel Celeron           | 1        | 1.61%   |
| Intel Atom              | 1        | 1.61%   |
| AMD Ryzen Threadripper  | 1        | 1.61%   |
| AMD Ryzen 3             | 1        | 1.61%   |
| AMD A6                  | 1        | 1.61%   |
| AMD A10                 | 1        | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 25       | 40.32%  |
| 6      | 11       | 17.74%  |
| 8      | 10       | 16.13%  |
| 2      | 7        | 11.29%  |
| 16     | 3        | 4.84%   |
| 12     | 3        | 4.84%   |
| 1      | 3        | 4.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 61       | 98.39%  |
| 2      | 1        | 1.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 39       | 62.9%   |
| 1      | 23       | 37.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 62       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 40.63%  |
| 0x0a50000c | 3        | 4.69%   |
| 0x906e9    | 2        | 3.13%   |
| 0x506e3    | 2        | 3.13%   |
| 0x306c3    | 2        | 3.13%   |
| 0x106e5    | 2        | 3.13%   |
| 0x0a50000d | 2        | 3.13%   |
| 0x0800820d | 2        | 3.13%   |
| 0x06000852 | 2        | 3.13%   |
| 0x010000dc | 2        | 3.13%   |
| 0x010000c8 | 2        | 3.13%   |
| 0xf4a      | 1        | 1.56%   |
| 0xa0671    | 1        | 1.56%   |
| 0x90672    | 1        | 1.56%   |
| 0x6f6      | 1        | 1.56%   |
| 0x50654    | 1        | 1.56%   |
| 0x306e4    | 1        | 1.56%   |
| 0x206a7    | 1        | 1.56%   |
| 0x106ca    | 1        | 1.56%   |
| 0x1067a    | 1        | 1.56%   |
| 0x0a601201 | 1        | 1.56%   |
| 0x0a50000b | 1        | 1.56%   |
| 0x0a201016 | 1        | 1.56%   |
| 0x08701021 | 1        | 1.56%   |
| 0x08001138 | 1        | 1.56%   |
| 0x08001129 | 1        | 1.56%   |
| 0x06003106 | 1        | 1.56%   |
| 0x06001119 | 1        | 1.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen+             | 6        | 9.68%   |
| Zen 3            | 6        | 9.68%   |
| Penryn           | 5        | 8.06%   |
| Zen 2            | 4        | 6.45%   |
| Skylake          | 4        | 6.45%   |
| K10              | 4        | 6.45%   |
| Haswell          | 4        | 6.45%   |
| Zen              | 3        | 4.84%   |
| SandyBridge      | 3        | 4.84%   |
| Piledriver       | 3        | 4.84%   |
| Nehalem          | 3        | 4.84%   |
| Unknown          | 3        | 4.84%   |
| Westmere         | 2        | 3.23%   |
| KabyLake         | 2        | 3.23%   |
| IvyBridge        | 2        | 3.23%   |
| Steamroller      | 1        | 1.61%   |
| NetBurst         | 1        | 1.61%   |
| Icelake          | 1        | 1.61%   |
| Goldmont         | 1        | 1.61%   |
| Core             | 1        | 1.61%   |
| CometLake        | 1        | 1.61%   |
| Bonnell          | 1        | 1.61%   |
| Alderlake Hybrid | 1        | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Nvidia      | 29       | 43.94%  |
| AMD         | 29       | 43.94%  |
| Intel       | 7        | 10.61%  |
| S3 Graphics | 1        | 1.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 7.25%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 4.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 4.35%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 4.35%   |
| Nvidia GK107 [GeForce GT 640]                                               | 2        | 2.9%    |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 2.9%    |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 2.9%    |
| AMD RS880 [Radeon HD 4200]                                                  | 2        | 2.9%    |
| AMD Raphael                                                                 | 2        | 2.9%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 2.9%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.9%    |
| S3 Graphics 86c764/765 [Trio32/64/64V+]                                     | 1        | 1.45%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.45%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.45%   |
| Nvidia GT218M [ION]                                                         | 1        | 1.45%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 1.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.45%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.45%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.45%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.45%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 1.45%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.45%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.45%   |
| Nvidia GK107 [GeForce GT 640 OEM]                                           | 1        | 1.45%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 1.45%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.45%   |
| Nvidia GF110 [GeForce GTX 560 Ti 448 Cores]                                 | 1        | 1.45%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.45%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.45%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 1.45%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.45%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 1        | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.45%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.45%   |
| Intel HD Graphics 630                                                       | 1        | 1.45%   |
| Intel HD Graphics 530                                                       | 1        | 1.45%   |
| Intel HD Graphics 500                                                       | 1        | 1.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 25       | 40.32%  |
| 1 x AMD         | 24       | 38.71%  |
| 1 x Intel       | 5        | 8.06%   |
| 2 x AMD         | 2        | 3.23%   |
| AMD + Nvidia    | 2        | 3.23%   |
| 2 x Nvidia      | 1        | 1.61%   |
| 1 x S3 Graphics | 1        | 1.61%   |
| Intel + Nvidia  | 1        | 1.61%   |
| Intel + AMD     | 1        | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 43       | 69.35%  |
| Proprietary | 18       | 29.03%  |
| Unknown     | 1        | 1.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 38.71%  |
| 0.01-0.5   | 11       | 17.74%  |
| 1.01-2.0   | 9        | 14.52%  |
| 3.01-4.0   | 7        | 11.29%  |
| 7.01-8.0   | 3        | 4.84%   |
| 8.01-16.0  | 3        | 4.84%   |
| 0.51-1.0   | 3        | 4.84%   |
| 2.01-3.0   | 2        | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 15.15%  |
| Dell                 | 9        | 13.64%  |
| Fujitsu Siemens      | 7        | 10.61%  |
| Goldstar             | 6        | 9.09%   |
| Ancor Communications | 4        | 6.06%   |
| Acer                 | 4        | 6.06%   |
| Philips              | 3        | 4.55%   |
| LG Electronics       | 3        | 4.55%   |
| Iiyama               | 3        | 4.55%   |
| Hewlett-Packard      | 3        | 4.55%   |
| AOC                  | 3        | 4.55%   |
| BenQ                 | 2        | 3.03%   |
| ViewSonic            | 1        | 1.52%   |
| Unknown              | 1        | 1.52%   |
| NEC Computers        | 1        | 1.52%   |
| Lenovo               | 1        | 1.52%   |
| Hitachi              | 1        | 1.52%   |
| HannStar             | 1        | 1.52%   |
| Gigabyte Technology  | 1        | 1.52%   |
| Eizo                 | 1        | 1.52%   |
| ASUSTek Computer     | 1        | 1.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Fujitsu Siemens P19-2 FUS0552 1280x1024 376x301mm 19.0-inch           | 6        | 8.33%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 1920x1080                     | 2        | 2.78%   |
| Dell DELL3007WFPHC DEL4016 2560x1600 646x406mm 30.0-inch              | 2        | 2.78%   |
| ViewSonic EP3220T VSC33F3 1920x1080 700x390mm 31.5-inch               | 1        | 1.39%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1        | 1.39%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 1.39%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 477x268mm 21.5-inch  | 1        | 1.39%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1        | 1.39%   |
| Samsung Electronics SMS24A850 SAM0825 1920x1200 518x324mm 24.1-inch   | 1        | 1.39%   |
| Samsung Electronics SMS24A450 SAM0839 1920x1200 520x320mm 24.0-inch   | 1        | 1.39%   |
| Samsung Electronics S27E450 SAM0C83 1920x1080 598x336mm 27.0-inch     | 1        | 1.39%   |
| Samsung Electronics S24E650 SAM0C85 1920x1200 518x324mm 24.1-inch     | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SAM07C3 1920x1080 700x390mm 31.5-inch | 1        | 1.39%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1        | 1.39%   |
| Samsung Electronics C32JG5x SAM0F55 2560x1440 697x392mm 31.5-inch     | 1        | 1.39%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 1.39%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 1        | 1.39%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 1        | 1.39%   |
| Philips 190X PHL084C 1280x1024 376x301mm 19.0-inch                    | 1        | 1.39%   |
| NEC Computers LCD1960NX NEC661F 1280x1024 376x301mm 19.0-inch         | 1        | 1.39%   |
| LG Electronics LCD Monitor E2260 1920x1080                            | 1        | 1.39%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 1        | 1.39%   |
| Iiyama PL2592H IVM6135 1920x1080 544x303mm 24.5-inch                  | 1        | 1.39%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1        | 1.39%   |
| Iiyama PL2274HD IVM5619 1920x1080 477x268mm 21.5-inch                 | 1        | 1.39%   |
| Hitachi X90W D-sub HIT6008 1440x900 410x257mm 19.1-inch               | 1        | 1.39%   |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch          | 1        | 1.39%   |
| Hewlett-Packard L1740 HWP2649 1280x1024 338x270mm 17.0-inch           | 1        | 1.39%   |
| Hewlett-Packard E231 HWP3065 1920x1080 509x286mm 23.0-inch            | 1        | 1.39%   |
| HannStar HH251 HSD2211 1920x1080 543x305mm 24.5-inch                  | 1        | 1.39%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                  | 1        | 1.39%   |
| Goldstar ULTRAWIDE GSM76FC 3840x1600 874x366mm 37.3-inch              | 1        | 1.39%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 1        | 1.39%   |
| Goldstar M2380D GSM57BC 1920x1080 598x336mm 27.0-inch                 | 1        | 1.39%   |
| Goldstar L227W GSM566E 1680x1050 474x296mm 22.0-inch                  | 1        | 1.39%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 1        | 1.39%   |
| Goldstar 27MB85R GSM5A8B 2560x1440 597x336mm 27.0-inch                | 1        | 1.39%   |
| Gigabyte Technology AORUS CV27Q GBT2705 2560x1440 600x340mm 27.2-inch | 1        | 1.39%   |
| Fujitsu Siemens B19-5 ECO FUS07C0 1280x1024 376x301mm 19.0-inch       | 1        | 1.39%   |
| Eizo S2433W ENC2112 1920x1200 519x324mm 24.1-inch                     | 1        | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 26       | 39.39%  |
| 1280x1024 (SXGA)   | 12       | 18.18%  |
| 2560x1440 (QHD)    | 10       | 15.15%  |
| 1920x1200 (WUXGA)  | 3        | 4.55%   |
| 1680x1050 (WSXGA+) | 3        | 4.55%   |
| 1366x768 (WXGA)    | 3        | 4.55%   |
| 2560x1600          | 2        | 3.03%   |
| 1440x900 (WXGA+)   | 2        | 3.03%   |
| 3840x2160 (4K)     | 1        | 1.52%   |
| 3840x1600          | 1        | 1.52%   |
| 3440x1440          | 1        | 1.52%   |
| 1600x900 (HD+)     | 1        | 1.52%   |
| 1600x1200          | 1        | 1.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 12       | 17.39%  |
| 19      | 12       | 17.39%  |
| 27      | 11       | 15.94%  |
| 23      | 7        | 10.14%  |
| 21      | 5        | 7.25%   |
| 31      | 4        | 5.8%    |
| Unknown | 3        | 4.35%   |
| 54      | 2        | 2.9%    |
| 30      | 2        | 2.9%    |
| 22      | 2        | 2.9%    |
| 18      | 2        | 2.9%    |
| 17      | 2        | 2.9%    |
| 37      | 1        | 1.45%   |
| 34      | 1        | 1.45%   |
| 32      | 1        | 1.45%   |
| 20      | 1        | 1.45%   |
| 15      | 1        | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 24       | 36.36%  |
| 401-500     | 13       | 19.7%   |
| 351-400     | 11       | 16.67%  |
| 601-700     | 7        | 10.61%  |
| 301-350     | 3        | 4.55%   |
| Unknown     | 3        | 4.55%   |
| 701-800     | 2        | 3.03%   |
| 1001-1500   | 2        | 3.03%   |
| 801-900     | 1        | 1.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 34       | 53.97%  |
| 5/4     | 11       | 17.46%  |
| 16/10   | 10       | 15.87%  |
| Unknown | 3        | 4.76%   |
| 21/9    | 2        | 3.17%   |
| 6/5     | 1        | 1.59%   |
| 4/3     | 1        | 1.59%   |
| 3/2     | 1        | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 26.47%  |
| 151-200        | 14       | 20.59%  |
| 301-350        | 11       | 16.18%  |
| 351-500        | 9        | 13.24%  |
| 251-300        | 6        | 8.82%   |
| 141-150        | 4        | 5.88%   |
| Unknown        | 3        | 4.41%   |
| More than 1000 | 2        | 2.94%   |
| 101-110        | 1        | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 41       | 66.13%  |
| 101-120 | 15       | 24.19%  |
| Unknown | 3        | 4.84%   |
| 1-50    | 2        | 3.23%   |
| 121-160 | 1        | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 51       | 80.95%  |
| 2     | 7        | 11.11%  |
| 3     | 3        | 4.76%   |
| 0     | 2        | 3.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 40       | 44.44%  |
| Intel                    | 27       | 30%     |
| Qualcomm Atheros         | 5        | 5.56%   |
| Broadcom                 | 3        | 3.33%   |
| MediaTek                 | 2        | 2.22%   |
| Marvell Technology Group | 2        | 2.22%   |
| TP-Link                  | 1        | 1.11%   |
| Samsung Electronics      | 1        | 1.11%   |
| Ralink Technology        | 1        | 1.11%   |
| Ralink                   | 1        | 1.11%   |
| NetGear                  | 1        | 1.11%   |
| Microchip Technology     | 1        | 1.11%   |
| Linksys                  | 1        | 1.11%   |
| JMicron Technology       | 1        | 1.11%   |
| AVM                      | 1        | 1.11%   |
| Atmel                    | 1        | 1.11%   |
| Aquantia                 | 1        | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 30       | 30.93%  |
| Intel Ethernet Controller I225-V                                       | 4        | 4.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 4.12%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3        | 3.09%   |
| Intel Wi-Fi 6 AX200                                                    | 3        | 3.09%   |
| Intel I211 Gigabit Network Connection                                  | 3        | 3.09%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 2.06%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 2.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 2.06%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 2.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 2        | 2.06%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 2.06%   |
| Intel 82583V Gigabit Network Connection                                | 2        | 2.06%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2        | 2.06%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 1.03%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                       | 1        | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.03%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 1.03%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                       | 1        | 1.03%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 1.03%   |
| Ralink RT5392 PCIe Wireless Network Adapter                            | 1        | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 1.03%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                       | 1        | 1.03%   |
| NetGear A6150                                                          | 1        | 1.03%   |
| Microchip SPROG 3 DCC Programmer                                       | 1        | 1.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1        | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1        | 1.03%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1        | 1.03%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1        | 1.03%   |
| Intel Wireless-AC 9260                                                 | 1        | 1.03%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 1.03%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 1.03%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 1.03%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 33.33%  |
| Realtek Semiconductor | 5        | 20.83%  |
| Qualcomm Atheros      | 2        | 8.33%   |
| MediaTek              | 2        | 8.33%   |
| TP-Link               | 1        | 4.17%   |
| Samsung Electronics   | 1        | 4.17%   |
| Ralink Technology     | 1        | 4.17%   |
| Ralink                | 1        | 4.17%   |
| NetGear               | 1        | 4.17%   |
| Linksys               | 1        | 4.17%   |
| AVM                   | 1        | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 3        | 12.5%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 2        | 8.33%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 4.17%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                       | 1        | 4.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 4.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1        | 4.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 4.17%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 4.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 4.17%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 4.17%   |
| Ralink RT5392 PCIe Wireless Network Adapter                            | 1        | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 4.17%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                       | 1        | 4.17%   |
| NetGear A6150                                                          | 1        | 4.17%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1        | 4.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1        | 4.17%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1        | 4.17%   |
| Intel Wireless-AC 9260                                                 | 1        | 4.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 4.17%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 4.17%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                   | 1        | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 37       | 52.86%  |
| Intel                    | 23       | 32.86%  |
| Qualcomm Atheros         | 3        | 4.29%   |
| Broadcom                 | 3        | 4.29%   |
| Marvell Technology Group | 2        | 2.86%   |
| JMicron Technology       | 1        | 1.43%   |
| Aquantia                 | 1        | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 30       | 42.25%  |
| Intel Ethernet Controller I225-V                                    | 4        | 5.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 4        | 5.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 3        | 4.23%   |
| Intel I211 Gigabit Network Connection                               | 3        | 4.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 2        | 2.82%   |
| Realtek RTL8125 2.5GbE Controller                                   | 2        | 2.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 2        | 2.82%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 2        | 2.82%   |
| Intel Ethernet Connection (2) I219-V                                | 2        | 2.82%   |
| Intel 82583V Gigabit Network Connection                             | 2        | 2.82%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 2        | 2.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 1.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 1.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller              | 1        | 1.41%   |
| Intel NM10/ICH7 Family LAN Controller                               | 1        | 1.41%   |
| Intel I350 Gigabit Network Connection                               | 1        | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 1.41%   |
| Intel Ethernet Connection (2) I218-LM                               | 1        | 1.41%   |
| Intel Ethernet Connection (11) I219-V                               | 1        | 1.41%   |
| Intel 82578DM Gigabit Network Connection                            | 1        | 1.41%   |
| Intel 82566DC Gigabit Network Connection                            | 1        | 1.41%   |
| Intel 82541PI Gigabit Ethernet Controller                           | 1        | 1.41%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                    | 1        | 1.41%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 61       | 72.62%  |
| WiFi     | 22       | 26.19%  |
| Modem    | 1        | 1.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 58       | 92.06%  |
| WiFi     | 5        | 7.94%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 56.45%  |
| 2     | 22       | 35.48%  |
| 3     | 3        | 4.84%   |
| 4     | 1        | 1.61%   |
| 0     | 1        | 1.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 42       | 65.63%  |
| Yes  | 22       | 34.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 33.33%  |
| Cambridge Silicon Radio         | 6        | 25%     |
| Realtek Semiconductor           | 3        | 12.5%   |
| Broadcom                        | 2        | 8.33%   |
| Qualcomm Atheros Communications | 1        | 4.17%   |
| MediaTek                        | 1        | 4.17%   |
| IMC Networks                    | 1        | 4.17%   |
| Belkin Components               | 1        | 4.17%   |
| ASUSTek Computer                | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 6        | 25%     |
| Intel AX200 Bluetooth                                 | 3        | 12.5%   |
| Realtek Bluetooth Radio                               | 2        | 8.33%   |
| Intel AX210 Bluetooth                                 | 2        | 8.33%   |
| Realtek RTL8821A Bluetooth                            | 1        | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 4.17%   |
| MediaTek Wireless_Device                              | 1        | 4.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 4.17%   |
| Intel AX201 Bluetooth                                 | 1        | 4.17%   |
| IMC Networks Wireless_Device                          | 1        | 4.17%   |
| Broadcom Bluetooth Controller                         | 1        | 4.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 4.17%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 34       | 31.19%  |
| Intel                       | 31       | 28.44%  |
| Nvidia                      | 28       | 25.69%  |
| C-Media Electronics         | 4        | 3.67%   |
| Creative Labs               | 3        | 2.75%   |
| Ensoniq                     | 2        | 1.83%   |
| VIA Technologies            | 1        | 0.92%   |
| Texas Instruments           | 1        | 0.92%   |
| Microsoft                   | 1        | 0.92%   |
| JMTek                       | 1        | 0.92%   |
| GN Netcom                   | 1        | 0.92%   |
| FiiO Electronics Technology | 1        | 0.92%   |
| ASUSTek Computer            | 1        | 0.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                      | 7        | 5.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 7        | 5.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 6        | 4.48%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 5        | 3.73%   |
| AMD Starship/Matisse HD Audio Controller                                    | 5        | 3.73%   |
| AMD Renoir Radeon High Definition Audio Controller                          | 5        | 3.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 4        | 2.99%   |
| Nvidia GP107GL High Definition Audio Controller                             | 3        | 2.24%   |
| Nvidia GK107 HDMI Audio Controller                                          | 3        | 2.24%   |
| Nvidia GF119 HDMI Audio Controller                                          | 3        | 2.24%   |
| Nvidia GF108 High Definition Audio Controller                               | 3        | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 3        | 2.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 3        | 2.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                     | 3        | 2.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 3        | 2.24%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 3        | 2.24%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                | 3        | 2.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 2        | 1.49%   |
| Nvidia GA106 High Definition Audio Controller                               | 2        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 2        | 1.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 2        | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                              | 2        | 1.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 2        | 1.49%   |
| Ensoniq 5880B / Creative Labs CT5880                                        | 2        | 1.49%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                   | 2        | 1.49%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                | 2        | 1.49%   |
| AMD Rembrandt Radeon High Definition Audio Controller                       | 2        | 1.49%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]     | 2        | 1.49%   |
| AMD FCH Azalia Controller                                                   | 2        | 1.49%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.75%   |
| Texas Instruments PCM2902 Audio Codec                                       | 1        | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller              | 1        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                               | 1        | 0.75%   |
| Nvidia High Definition Audio Controller                                     | 1        | 0.75%   |
| Nvidia GT216 HDMI Audio Controller                                          | 1        | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                               | 1        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                               | 1        | 0.75%   |
| Nvidia GP102 HDMI Audio Controller                                          | 1        | 0.75%   |
| Nvidia GM206 High Definition Audio Controller                               | 1        | 0.75%   |
| Nvidia GM204 High Definition Audio Controller                               | 1        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 11       | 26.83%  |
| Unknown             | 7        | 17.07%  |
| G.Skill             | 7        | 17.07%  |
| Corsair             | 5        | 12.2%   |
| SK hynix            | 4        | 9.76%   |
| Micron Technology   | 2        | 4.88%   |
| TakeMS              | 1        | 2.44%   |
| Samsung Electronics | 1        | 2.44%   |
| CSX                 | 1        | 2.44%   |
| Avant               | 1        | 2.44%   |
| Unknown             | 1        | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s     | 3        | 6.98%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 2        | 4.65%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 2        | 4.65%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                | 1        | 2.33%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 2.33%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 2.33%   |
| TakeMS RAM Module 2048MB DIMM DDR2 800MT/s                | 1        | 2.33%   |
| SK hynix RAM Module 32GB DIMM DDR4 2400MT/s               | 1        | 2.33%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 2.33%   |
| SK hynix RAM HMT451R7AFR8C-RD 4GB DIMM DDR3 1866MT/s      | 1        | 2.33%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s      | 1        | 2.33%   |
| SK hynix RAM HMA82GU6AFR8N-UH 16GB DIMM DDR4 2400MT/s     | 1        | 2.33%   |
| Samsung RAM Module 32GB DIMM DDR4 2400MT/s                | 1        | 2.33%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s       | 1        | 2.33%   |
| Micron RAM 16ATF2G64AZ-2G1A1 16GB DIMM DDR4 2133MT/s      | 1        | 2.33%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 2.33%   |
| Kingston RAM KP223C-ELD 2048MB DIMM DDR3 1600MT/s         | 1        | 2.33%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 2.33%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 1        | 2.33%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 1        | 2.33%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 1        | 2.33%   |
| Kingston RAM 9965684-009.A00G 8GB DIMM DDR4 2133MT/s      | 1        | 2.33%   |
| Kingston RAM 9965669-023.A00G 8GB DIMM DDR4 2133MT/s      | 1        | 2.33%   |
| Kingston RAM 9905471-061.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 2.33%   |
| G.Skill RAM F4-3600C14-16GTZNA 16384MB DIMM DDR4 2133MT/s | 1        | 2.33%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s      | 1        | 2.33%   |
| G.Skill RAM F4-3200C15-16GTZKY 16384MB DIMM DDR4 3200MT/s | 1        | 2.33%   |
| G.Skill RAM F4-2400C15-8GFX 8GB DIMM DDR4 3000MT/s        | 1        | 2.33%   |
| G.Skill RAM F4-2400C15-16GVR 16GB DIMM DDR4 2400MT/s      | 1        | 2.33%   |
| G.Skill RAM F4-2133C15-8GNT 8GB DIMM DDR4 2133MT/s        | 1        | 2.33%   |
| G.Skill RAM F3-1600C11-4G 4GB DIMM DDR3 1600MT/s          | 1        | 2.33%   |
| CSX RAM V01D2LF1GB18864867 1GB DIMM DDR 533MT/s           | 1        | 2.33%   |
| Corsair RAM CMW32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s     | 1        | 2.33%   |
| Corsair RAM CML16GX3M2A1600C9 8192MB DIMM DDR3 2133MT/s   | 1        | 2.33%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s    | 1        | 2.33%   |
| Corsair RAM CMK32GX5M2B6400C32 16GB DIMM DDR5 4800MT/s    | 1        | 2.33%   |
| Corsair RAM CMK16GX4M1E3200C16 16GB DIMM DDR4 3200MT/s    | 1        | 2.33%   |
| Avant RAM F641GU67F9333G 8192MB DIMM DDR3 1333MT/s        | 1        | 2.33%   |
| Unknown                                                   | 1        | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 18       | 50%     |
| DDR3    | 8        | 22.22%  |
| Unknown | 5        | 13.89%  |
| DDR2    | 3        | 8.33%   |
| DDR5    | 1        | 2.78%   |
| DDR     | 1        | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 35       | 97.22%  |
| SODIMM | 1        | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 10       | 27.03%  |
| 8192  | 9        | 24.32%  |
| 4096  | 7        | 18.92%  |
| 32768 | 5        | 13.51%  |
| 2048  | 5        | 13.51%  |
| 1024  | 1        | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2133  | 6        | 16.22%  |
| 3200  | 5        | 13.51%  |
| 1600  | 5        | 13.51%  |
| 1333  | 5        | 13.51%  |
| 3933  | 3        | 8.11%   |
| 2400  | 3        | 8.11%   |
| 800   | 3        | 8.11%   |
| 3600  | 2        | 5.41%   |
| 4800  | 1        | 2.7%    |
| 3000  | 1        | 2.7%    |
| 2667  | 1        | 2.7%    |
| 1866  | 1        | 2.7%    |
| 533   | 1        | 2.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 2        | 50%     |
| Samsung Electronics | 1        | 25%     |
| Hewlett-Packard     | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung ML-191x/ML-252x Laser Printer | 1        | 25%     |
| HP Color LaserJet CP1215              | 1        | 25%     |
| Brother Printer                       | 1        | 25%     |
| Brother HL-4150CDN series             | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Seiko Epson    | 2        | 66.67%  |
| Mustek Systems | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 1        | 33.33%  |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 33.33%  |
| Mustek Systems ScanExpress A3 USB                             | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 4        | 33.33%  |
| Microdia               | 2        | 16.67%  |
| Microsoft              | 1        | 8.33%   |
| Huawei Technologies    | 1        | 8.33%   |
| HD 2MP WEBCAM          | 1        | 8.33%   |
| Generalplus Technology | 1        | 8.33%   |
| eMeet                  | 1        | 8.33%   |
| ARC International      | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Microsoft LifeCam VX-700      | 1        | 8.33%   |
| Microdia USB 2.0 Camera       | 1        | 8.33%   |
| Microdia Camera               | 1        | 8.33%   |
| Logitech Webcam C270          | 1        | 8.33%   |
| Logitech Webcam C170          | 1        | 8.33%   |
| Logitech HD Pro Webcam C920   | 1        | 8.33%   |
| Logitech BRIO Ultra HD Webcam | 1        | 8.33%   |
| Huawei UVC Camera             | 1        | 8.33%   |
| HD 2MP WEBCAM HD 2MP WEBCAM   | 1        | 8.33%   |
| Generalplus WEB CAM           | 1        | 8.33%   |
| eMeet HD Webcam C950          | 1        | 8.33%   |
| ARC International Camera      | 1        | 8.33%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 54       | 85.71%  |
| 1     | 7        | 11.11%  |
| 3     | 1        | 1.59%   |
| 2     | 1        | 1.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 3        | 25%     |
| Graphics card            | 3        | 25%     |
| Card reader              | 2        | 16.67%  |
| Unassigned class         | 1        | 8.33%   |
| Multimedia controller    | 1        | 8.33%   |
| Communication controller | 1        | 8.33%   |
| Chipcard                 | 1        | 8.33%   |

