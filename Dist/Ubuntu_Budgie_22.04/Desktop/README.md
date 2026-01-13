Ubuntu Budgie 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

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

Total: 62

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| GMKtec   | NucBox K8 Plus              | [89b9a3fd58](https://linux-hardware.org/?probe=89b9a3fd58) | Oct 27, 2025 |
| ASUSTek  | A88X-PRO                    | [0e0bc97fa5](https://linux-hardware.org/?probe=0e0bc97fa5) | Dec 17, 2024 |
| ASUSTek  | A88X-PRO                    | [6c5b4b865c](https://linux-hardware.org/?probe=6c5b4b865c) | Aug 21, 2024 |
| ASUSTek  | A88X-PRO                    | [0d6421bb24](https://linux-hardware.org/?probe=0d6421bb24) | Aug 21, 2024 |
| ASUSTek  | H81T                        | [db12bb8871](https://linux-hardware.org/?probe=db12bb8871) | Aug 03, 2024 |
| Lenovo   | 1059 SDK0T76530 WIN 3556... | [39db39fb8a](https://linux-hardware.org/?probe=39db39fb8a) | Mar 30, 2024 |
| PCWare   | APM-A320G                   | [15ddb5b3fd](https://linux-hardware.org/?probe=15ddb5b3fd) | Feb 29, 2024 |
| HP       | 8169                        | [8aadb502eb](https://linux-hardware.org/?probe=8aadb502eb) | Feb 13, 2024 |
| MSI      | B450M GAMING PLUS           | [093c937aa6](https://linux-hardware.org/?probe=093c937aa6) | Feb 07, 2024 |
| MSI      | A68HM-E33 V2                | [462cb61dd3](https://linux-hardware.org/?probe=462cb61dd3) | Jan 05, 2024 |
| Gigabyte | B650M AORUS ELITE AX        | [03e7ada99a](https://linux-hardware.org/?probe=03e7ada99a) | Jan 04, 2024 |
| MSI      | B450M PRO-VDH V2            | [7efa5db123](https://linux-hardware.org/?probe=7efa5db123) | Dec 29, 2023 |
| Toshiba  | STI 010433                  | [c172f735d2](https://linux-hardware.org/?probe=c172f735d2) | Nov 15, 2023 |
| MSI      | A68HM-E33 V2                | [e1edc2410b](https://linux-hardware.org/?probe=e1edc2410b) | Nov 03, 2023 |
| Dell     | 0M5DCD A00                  | [b3a6489f94](https://linux-hardware.org/?probe=b3a6489f94) | Oct 20, 2023 |
| HP       | 8054                        | [66ad5550d1](https://linux-hardware.org/?probe=66ad5550d1) | Oct 10, 2023 |
| ASUSTek  | Z97M-PLUS                   | [01e90212e5](https://linux-hardware.org/?probe=01e90212e5) | Sep 20, 2023 |
| MSI      | A320M-A PRO                 | [6588973c54](https://linux-hardware.org/?probe=6588973c54) | Sep 19, 2023 |
| Gigabyte | H410M S2H V3                | [e31d121593](https://linux-hardware.org/?probe=e31d121593) | Jul 15, 2023 |
| Gigabyte | H410M S2H V3                | [9c3135decf](https://linux-hardware.org/?probe=9c3135decf) | Jul 10, 2023 |
| Fujitsu  | D3233-A1 S26361-D3233-A1    | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Gigabyte | GA-890GPA-UD3H              | [f04b28a0e5](https://linux-hardware.org/?probe=f04b28a0e5) | Jun 10, 2023 |
| ASRock   | B450M Steel Legend          | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| Gigabyte | H310M HD2                   | [b28787ecb7](https://linux-hardware.org/?probe=b28787ecb7) | Jun 04, 2023 |
| ASUSTek  | ROG STRIX X670E-E GAMING... | [f87233a295](https://linux-hardware.org/?probe=f87233a295) | Apr 29, 2023 |
| Intel    | H61                         | [b8f0acdf61](https://linux-hardware.org/?probe=b8f0acdf61) | Apr 28, 2023 |
| MSI      | X99S SLI PLUS               | [8c6fb84b12](https://linux-hardware.org/?probe=8c6fb84b12) | Feb 09, 2023 |
| ASRock   | FM2A88X Extreme4+           | [9f812fe2a7](https://linux-hardware.org/?probe=9f812fe2a7) | Feb 02, 2023 |
| Fujitsu  | D3183-A1 S26361-D3183-A1    | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| Lenovo   | 36F7 SDK0J40700 WIN 3258... | [831fd897ec](https://linux-hardware.org/?probe=831fd897ec) | Jan 25, 2023 |
| Lenovo   | ThinkStation C20 4263BA7    | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| Fujitsu  | D3348-B2 S26361-D3348-B2    | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu  | D3348-B2 S26361-D3348-B2    | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Fujitsu  | D3348-B2 S26361-D3348-B2    | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Dell     | 0RW199                      | [2a2fa5baf8](https://linux-hardware.org/?probe=2a2fa5baf8) | Nov 20, 2022 |
| MSI      | B550M PRO-VDH WIFI          | [afb716fb12](https://linux-hardware.org/?probe=afb716fb12) | Nov 18, 2022 |
| Dell     | 0C27VV A01                  | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI      | B450-A PRO MAX              | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| Dell     | 0C27VV A01                  | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell     | 0C27VV A01                  | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Gigabyte | M68MT-S2                    | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| Gigabyte | B75M-D3P                    | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte | M68MT-S2                    | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Gigabyte | X570S AORUS PRO AX          | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel    | DP55WB AAE64798-206         | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek  | A88X-PRO                    | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Intel    | X79M-S                      | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| HP       | 828A                        | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| Biostar  | A960D+V3                    | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock   | A300M-STX                   | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock   | A300M-STX                   | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Intel    | STK1A32SC H95551-301        | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Gigabyte | GA-890GPA-UD3H              | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP       | 212B                        | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| Gigabyte | B75M-D3H                    | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Gigabyte | F2A78M-HD2                  | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek  | PRIME B560M-A               | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| MSI      | X370 GAMING PRO CARBON      | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Gigabyte | B75M-D3H                    | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte | B450 I AORUS PRO WIFI-CF    | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| HP       | 1825                        | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Gigabyte | B550 AORUS ELITE AX V2      | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.15.0-52-generic       | 4        | 7.69%   |
| 5.15.0-57-generic       | 3        | 5.77%   |
| 5.15.0-46-generic       | 3        | 5.77%   |
| 5.15.0-43-generic       | 3        | 5.77%   |
| 5.15.0-30-generic       | 3        | 5.77%   |
| 5.19.0-45-generic       | 2        | 3.85%   |
| 5.19.0-40-generic       | 2        | 3.85%   |
| 5.15.0-33-generic       | 2        | 3.85%   |
| 5.15.0-27-generic       | 2        | 3.85%   |
| 5.15.0-25-generic       | 2        | 3.85%   |
| 6.8.0-40-generic        | 1        | 1.92%   |
| 6.6.0-060600rc4-generic | 1        | 1.92%   |
| 6.5.0-21-generic        | 1        | 1.92%   |
| 6.5.0-18-generic        | 1        | 1.92%   |
| 6.2.0-39-generic        | 1        | 1.92%   |
| 6.2.0-37-generic        | 1        | 1.92%   |
| 6.2.0-36-generic        | 1        | 1.92%   |
| 6.2.0-35-generic        | 1        | 1.92%   |
| 6.2.0-33-generic        | 1        | 1.92%   |
| 6.2.0-26-generic        | 1        | 1.92%   |
| 5.19.0-46-generic       | 1        | 1.92%   |
| 5.17.2-051702-generic   | 1        | 1.92%   |
| 5.15.92-051592-generic  | 1        | 1.92%   |
| 5.15.0-94-generic       | 1        | 1.92%   |
| 5.15.0-84-generic       | 1        | 1.92%   |
| 5.15.0-73-generic       | 1        | 1.92%   |
| 5.15.0-71-generic       | 1        | 1.92%   |
| 5.15.0-60-generic       | 1        | 1.92%   |
| 5.15.0-56-generic       | 1        | 1.92%   |
| 5.15.0-50-generic       | 1        | 1.92%   |
| 5.15.0-48-generic       | 1        | 1.92%   |
| 5.15.0-47-generic       | 1        | 1.92%   |
| 5.15.0-41-generic       | 1        | 1.92%   |
| 5.15.0-117-generic      | 1        | 1.92%   |
| 5.15.0-105-generic      | 1        | 1.92%   |
| 5.13.0-44-generic       | 1        | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 31       | 64.58%  |
| 6.2.0   | 5        | 10.42%  |
| 5.19.0  | 5        | 10.42%  |
| 6.5.0   | 2        | 4.17%   |
| 6.8.0   | 1        | 2.08%   |
| 6.6.0   | 1        | 2.08%   |
| 5.17.2  | 1        | 2.08%   |
| 5.15.92 | 1        | 2.08%   |
| 5.13.0  | 1        | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 32       | 66.67%  |
| 6.2     | 5        | 10.42%  |
| 5.19    | 5        | 10.42%  |
| 6.5     | 2        | 4.17%   |
| 6.8     | 1        | 2.08%   |
| 6.6     | 1        | 2.08%   |
| 5.17    | 1        | 2.08%   |
| 5.13    | 1        | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 47       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 47       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 47       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 35       | 74.47%  |
| Unknown | 10       | 21.28%  |
| SDDM    | 1        | 2.13%   |
| GDM     | 1        | 2.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 19       | 40.43%  |
| de_DE | 6        | 12.77%  |
| pt_BR | 5        | 10.64%  |
| es_ES | 3        | 6.38%   |
| fr_FR | 2        | 4.26%   |
| en_GB | 2        | 4.26%   |
| it_IT | 1        | 2.13%   |
| es_MX | 1        | 2.13%   |
| es_AR | 1        | 2.13%   |
| en_ZA | 1        | 2.13%   |
| en_SG | 1        | 2.13%   |
| en_IN | 1        | 2.13%   |
| en_CA | 1        | 2.13%   |
| en_AU | 1        | 2.13%   |
| el_GR | 1        | 2.13%   |
| C     | 1        | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 33       | 68.75%  |
| EFI  | 15       | 31.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 34       | 70.83%  |
| Tmpfs   | 7        | 14.58%  |
| Overlay | 5        | 10.42%  |
| Zfs     | 1        | 2.08%   |
| Btrfs   | 1        | 2.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 31       | 63.27%  |
| Unknown | 17       | 34.69%  |
| MBR     | 1        | 2.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 76.6%   |
| Yes       | 11       | 23.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 55.32%  |
| Yes       | 21       | 44.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 11       | 23.4%   |
| MSI                 | 8        | 17.02%  |
| Hewlett-Packard     | 5        | 10.64%  |
| ASUSTek Computer    | 5        | 10.64%  |
| Intel               | 3        | 6.38%   |
| Fujitsu             | 3        | 6.38%   |
| Dell                | 3        | 6.38%   |
| ASRock              | 3        | 6.38%   |
| Lenovo              | 2        | 4.26%   |
| Semp Toshiba        | 1        | 2.13%   |
| PCWare              | 1        | 2.13%   |
| GMKtec              | 1        | 2.13%   |
| Biostar             | 1        | 2.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| ASUS All Series                           | 2        | 4.26%   |
| Semp Toshiba STI                          | 1        | 2.13%   |
| PCWare APM-A320G                          | 1        | 2.13%   |
| MSI MS-7C95                               | 1        | 2.13%   |
| MSI MS-7C51                               | 1        | 2.13%   |
| MSI MS-7B87                               | 1        | 2.13%   |
| MSI MS-7B86                               | 1        | 2.13%   |
| MSI MS-7A38                               | 1        | 2.13%   |
| MSI MS-7A32                               | 1        | 2.13%   |
| MSI MS-7885                               | 1        | 2.13%   |
| MSI MS-7721                               | 1        | 2.13%   |
| Lenovo ThinkStation P360 Ultra 30G1001AUS | 1        | 2.13%   |
| Lenovo ThinkStation C20 4263BA7           | 1        | 2.13%   |
| Intel STK1A32SC                           | 1        | 2.13%   |
| Intel H61                                 | 1        | 2.13%   |
| Intel DP55WB AAE64798-206                 | 1        | 2.13%   |
| HP Z440 Workstation                       | 1        | 2.13%   |
| HP ProDesk 600 G2 DM                      | 1        | 2.13%   |
| HP EliteDesk 800 G2 SFF                   | 1        | 2.13%   |
| HP EliteDesk 800 G1 DM                    | 1        | 2.13%   |
| HP 750-417c                               | 1        | 2.13%   |
| GMKtec NucBox K8 Plus                     | 1        | 2.13%   |
| Gigabyte X570S AORUS PRO AX               | 1        | 2.13%   |
| Gigabyte M68MT-S2                         | 1        | 2.13%   |
| Gigabyte H410M S2H V3                     | 1        | 2.13%   |
| Gigabyte H310MHD2                         | 1        | 2.13%   |
| Gigabyte GA-890GPA-UD3H                   | 1        | 2.13%   |
| Gigabyte F2A78M-HD2                       | 1        | 2.13%   |
| Gigabyte B75M-D3P                         | 1        | 2.13%   |
| Gigabyte B75M-D3H                         | 1        | 2.13%   |
| Gigabyte B650M AORUS ELITE AX             | 1        | 2.13%   |
| Gigabyte B550 AORUS ELITE AX V2           | 1        | 2.13%   |
| Gigabyte B450 I AORUS PRO WIFI            | 1        | 2.13%   |
| Fujitsu ESPRIMO Q920                      | 1        | 2.13%   |
| Fujitsu ESPRIMO Q910                      | 1        | 2.13%   |
| Fujitsu D3348-B2                          | 1        | 2.13%   |
| Dell Precision WorkStation T7400          | 1        | 2.13%   |
| Dell OptiPlex 780                         | 1        | 2.13%   |
| Dell OptiPlex 390                         | 1        | 2.13%   |
| Biostar A960D+V3                          | 1        | 2.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Lenovo ThinkStation     | 2        | 4.26%   |
| HP EliteDesk            | 2        | 4.26%   |
| Fujitsu ESPRIMO         | 2        | 4.26%   |
| Dell OptiPlex           | 2        | 4.26%   |
| ASUS All                | 2        | 4.26%   |
| Semp Toshiba STI        | 1        | 2.13%   |
| PCWare APM-A320G        | 1        | 2.13%   |
| MSI MS-7C95             | 1        | 2.13%   |
| MSI MS-7C51             | 1        | 2.13%   |
| MSI MS-7B87             | 1        | 2.13%   |
| MSI MS-7B86             | 1        | 2.13%   |
| MSI MS-7A38             | 1        | 2.13%   |
| MSI MS-7A32             | 1        | 2.13%   |
| MSI MS-7885             | 1        | 2.13%   |
| MSI MS-7721             | 1        | 2.13%   |
| Intel STK1A32SC         | 1        | 2.13%   |
| Intel H61               | 1        | 2.13%   |
| Intel DP55WB            | 1        | 2.13%   |
| HP Z440                 | 1        | 2.13%   |
| HP ProDesk              | 1        | 2.13%   |
| HP 750-417c             | 1        | 2.13%   |
| GMKtec NucBox           | 1        | 2.13%   |
| Gigabyte X570S          | 1        | 2.13%   |
| Gigabyte M68MT-S2       | 1        | 2.13%   |
| Gigabyte H410M          | 1        | 2.13%   |
| Gigabyte H310MHD2       | 1        | 2.13%   |
| Gigabyte GA-890GPA-UD3H | 1        | 2.13%   |
| Gigabyte F2A78M-HD2     | 1        | 2.13%   |
| Gigabyte B75M-D3P       | 1        | 2.13%   |
| Gigabyte B75M-D3H       | 1        | 2.13%   |
| Gigabyte B650M          | 1        | 2.13%   |
| Gigabyte B550           | 1        | 2.13%   |
| Gigabyte B450           | 1        | 2.13%   |
| Fujitsu D3348-B2        | 1        | 2.13%   |
| Dell Precision          | 1        | 2.13%   |
| Biostar A960D+V3        | 1        | 2.13%   |
| ASUS ROG                | 1        | 2.13%   |
| ASUS PRIME              | 1        | 2.13%   |
| ASUS A88X-PRO           | 1        | 2.13%   |
| ASRock FM2A88X          | 1        | 2.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 7        | 14.89%  |
| 2014 | 7        | 14.89%  |
| 2022 | 3        | 6.38%   |
| 2021 | 3        | 6.38%   |
| 2019 | 3        | 6.38%   |
| 2016 | 3        | 6.38%   |
| 2013 | 3        | 6.38%   |
| 2011 | 3        | 6.38%   |
| 2009 | 3        | 6.38%   |
| 2020 | 2        | 4.26%   |
| 2017 | 2        | 4.26%   |
| 2015 | 2        | 4.26%   |
| 2012 | 2        | 4.26%   |
| 2010 | 2        | 4.26%   |
| 2024 | 1        | 2.13%   |
| 2008 | 1        | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 47       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 46       | 97.87%  |
| Enabled  | 1        | 2.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 47       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 14       | 29.79%  |
| 8.01-16.0       | 12       | 25.53%  |
| 4.01-8.0        | 11       | 23.4%   |
| 32.01-64.0      | 3        | 6.38%   |
| 24.01-32.0      | 3        | 6.38%   |
| 64.01-256.0     | 2        | 4.26%   |
| More than 256.0 | 1        | 2.13%   |
| 1.01-2.0        | 1        | 2.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 17       | 33.33%  |
| 1.01-2.0   | 16       | 31.37%  |
| 4.01-8.0   | 11       | 21.57%  |
| 3.01-4.0   | 4        | 7.84%   |
| 8.01-16.0  | 2        | 3.92%   |
| 16.01-24.0 | 1        | 1.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 15       | 31.91%  |
| 1      | 15       | 31.91%  |
| 3      | 7        | 14.89%  |
| 4      | 6        | 12.77%  |
| 6      | 2        | 4.26%   |
| 8      | 1        | 2.13%   |
| 7      | 1        | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 61.7%   |
| Yes       | 18       | 38.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 46       | 97.87%  |
| No        | 1        | 2.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 51.06%  |
| Yes       | 23       | 48.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 65.96%  |
| Yes       | 16       | 34.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 12       | 25.53%  |
| Brazil       | 6        | 12.77%  |
| Germany      | 5        | 10.64%  |
| Spain        | 3        | 6.38%   |
| UK           | 2        | 4.26%   |
| Switzerland  | 2        | 4.26%   |
| France       | 2        | 4.26%   |
| Argentina    | 2        | 4.26%   |
| South Africa | 1        | 2.13%   |
| Slovenia     | 1        | 2.13%   |
| Singapore    | 1        | 2.13%   |
| Romania      | 1        | 2.13%   |
| Norway       | 1        | 2.13%   |
| Mexico       | 1        | 2.13%   |
| Italy        | 1        | 2.13%   |
| India        | 1        | 2.13%   |
| Greece       | 1        | 2.13%   |
| Croatia      | 1        | 2.13%   |
| Canada       | 1        | 2.13%   |
| Austria      | 1        | 2.13%   |
| Australia    | 1        | 2.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Brasília                 | 3        | 6%      |
| Milwaukee                 | 2        | 4%      |
| Zurich                    | 1        | 2%      |
| Walled Lake               | 1        | 2%      |
| Trondheim                 | 1        | 2%      |
| Tocantins                 | 1        | 2%      |
| Tann                      | 1        | 2%      |
| Summerfield               | 1        | 2%      |
| Sooke                     | 1        | 2%      |
| Singapore                 | 1        | 2%      |
| Seattle                   | 1        | 2%      |
| San Luis Potosí City     | 1        | 2%      |
| San Francisco de Santa Fe | 1        | 2%      |
| San Francisco             | 1        | 2%      |
| San Diego                 | 1        | 2%      |
| Rueil-Malmaison           | 1        | 2%      |
| Pula                      | 1        | 2%      |
| Pine Island               | 1        | 2%      |
| New York                  | 1        | 2%      |
| Maribor                   | 1        | 2%      |
| Manaus                    | 1        | 2%      |
| Malalbergo                | 1        | 2%      |
| Madrid                    | 1        | 2%      |
| London                    | 1        | 2%      |
| Limay                     | 1        | 2%      |
| Kolkata                   | 1        | 2%      |
| Kittsee                   | 1        | 2%      |
| Kirkcaldy                 | 1        | 2%      |
| Houston                   | 1        | 2%      |
| Hamburg                   | 1        | 2%      |
| Guarulhos                 | 1        | 2%      |
| Granada                   | 1        | 2%      |
| Eugene                    | 1        | 2%      |
| Ennepetal                 | 1        | 2%      |
| Dortmund                  | 1        | 2%      |
| Delbrueck                 | 1        | 2%      |
| Colon                     | 1        | 2%      |
| Caslano                   | 1        | 2%      |
| Cape Town                 | 1        | 2%      |
| Camp Hill                 | 1        | 2%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 18       | 34     | 19.15%  |
| WDC                       | 14       | 17     | 14.89%  |
| Samsung Electronics       | 13       | 34     | 13.83%  |
| SanDisk                   | 7        | 8      | 7.45%   |
| Crucial                   | 5        | 5      | 5.32%   |
| Toshiba                   | 4        | 4      | 4.26%   |
| Kingston                  | 4        | 5      | 4.26%   |
| China                     | 3        | 3      | 3.19%   |
| Transcend                 | 2        | 2      | 2.13%   |
| PNY                       | 2        | 2      | 2.13%   |
| OCZ                       | 2        | 2      | 2.13%   |
| Micron/Crucial Technology | 2        | 2      | 2.13%   |
| Micron Technology         | 2        | 2      | 2.13%   |
| A-DATA Technology         | 2        | 2      | 2.13%   |
| Zheino                    | 1        | 1      | 1.06%   |
| Unknown                   | 1        | 1      | 1.06%   |
| SPCC                      | 1        | 1      | 1.06%   |
| SK hynix                  | 1        | 1      | 1.06%   |
| Phison                    | 1        | 1      | 1.06%   |
| Mushkin                   | 1        | 1      | 1.06%   |
| MicroFrom                 | 1        | 1      | 1.06%   |
| Maxtor                    | 1        | 1      | 1.06%   |
| JMicron Technology        | 1        | 1      | 1.06%   |
| Intenso                   | 1        | 1      | 1.06%   |
| Intel                     | 1        | 1      | 1.06%   |
| HGST                      | 1        | 1      | 1.06%   |
| ASMT109x                  | 1        | 1      | 1.06%   |
| 4Life                     | 1        | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB      | 2        | 1.8%    |
| Seagate ST3500418AS 500GB         | 2        | 1.8%    |
| Seagate ST3500413AS 500GB         | 2        | 1.8%    |
| Seagate ST1000LM048-2E7172 1TB    | 2        | 1.8%    |
| Seagate ST1000DM010-2EP102 1TB    | 2        | 1.8%    |
| SanDisk SDSSDA120G 120GB          | 2        | 1.8%    |
| Samsung SSD 870 EVO 250GB         | 2        | 1.8%    |
| Samsung SSD 850 PRO 256GB         | 2        | 1.8%    |
| Samsung SSD 840 EVO 250GB         | 2        | 1.8%    |
| Kingston SA400S37240G 240GB SSD   | 2        | 1.8%    |
| Zheino CHN-25SATAC3-120 120GB     | 1        | 0.9%    |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 0.9%    |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 1        | 0.9%    |
| WDC WDS100T2B0C 1TB               | 1        | 0.9%    |
| WDC WD40PURZ-85TTDY0 4TB          | 1        | 0.9%    |
| WDC WD40EZAZ-00SF3B0 4TB          | 1        | 0.9%    |
| WDC WD40EFAX-68JH4N1 4TB          | 1        | 0.9%    |
| WDC WD3200LPVX-22V0TT0 320GB      | 1        | 0.9%    |
| WDC WD20EARX-00PASB0 2TB          | 1        | 0.9%    |
| WDC WD1600AAJS-60WAA0 160GB       | 1        | 0.9%    |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 0.9%    |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 0.9%    |
| WDC WD10EADS-00M2B0 1TB           | 1        | 0.9%    |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 0.9%    |
| WDC WD Green 2.5 240GB            | 1        | 0.9%    |
| Unknown SD/MMC/MS PRO 2GB         | 1        | 0.9%    |
| Transcend TS480GMTS820S 480GB SSD | 1        | 0.9%    |
| Transcend TS128GMTE110S 128GB     | 1        | 0.9%    |
| Toshiba MD04ACA400 4TB            | 1        | 0.9%    |
| Toshiba HDWD240 4TB               | 1        | 0.9%    |
| Toshiba HDWD220 2TB               | 1        | 0.9%    |
| Toshiba DT01ACA050 500GB          | 1        | 0.9%    |
| SPCC Solid State Disk 256GB       | 1        | 0.9%    |
| SK hynix SC210 2.5 7MM 128GB SSD  | 1        | 0.9%    |
| Seagate ST9500325AS 500GB         | 1        | 0.9%    |
| Seagate ST8000VN0022-2EL112 8TB   | 1        | 0.9%    |
| Seagate ST500LT012-1DG142 500GB   | 1        | 0.9%    |
| Seagate ST500DM002-1BD142 500GB   | 1        | 0.9%    |
| Seagate ST4000DM004-2CV104 4TB    | 1        | 0.9%    |
| Seagate ST4000DM 004-2CV104 4TB   | 1        | 0.9%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 33     | 45%     |
| WDC                 | 11       | 13     | 27.5%   |
| Toshiba             | 4        | 4      | 10%     |
| Samsung Electronics | 2        | 4      | 5%      |
| Unknown             | 1        | 1      | 2.5%    |
| Maxtor              | 1        | 1      | 2.5%    |
| JMicron Technology  | 1        | 1      | 2.5%    |
| HGST                | 1        | 1      | 2.5%    |
| ASMT109x            | 1        | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 23     | 21.05%  |
| SanDisk             | 4        | 4      | 10.53%  |
| Crucial             | 4        | 4      | 10.53%  |
| WDC                 | 3        | 3      | 7.89%   |
| Kingston            | 3        | 4      | 7.89%   |
| China               | 3        | 3      | 7.89%   |
| PNY                 | 2        | 2      | 5.26%   |
| A-DATA Technology   | 2        | 2      | 5.26%   |
| Zheino              | 1        | 1      | 2.63%   |
| Transcend           | 1        | 1      | 2.63%   |
| SPCC                | 1        | 1      | 2.63%   |
| SK hynix            | 1        | 1      | 2.63%   |
| OCZ                 | 1        | 1      | 2.63%   |
| Mushkin             | 1        | 1      | 2.63%   |
| Micron Technology   | 1        | 1      | 2.63%   |
| MicroFrom           | 1        | 1      | 2.63%   |
| 4Life               | 1        | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 31       | 54     | 39.74%  |
| HDD     | 29       | 59     | 37.18%  |
| NVMe    | 16       | 21     | 20.51%  |
| MMC     | 1        | 1      | 1.28%   |
| Unknown | 1        | 1      | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 42       | 110    | 66.67%  |
| NVMe | 16       | 21     | 25.4%   |
| SAS  | 4        | 4      | 6.35%   |
| MMC  | 1        | 1      | 1.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 38       | 69     | 57.58%  |
| 0.51-1.0   | 14       | 22     | 21.21%  |
| 3.01-4.0   | 8        | 9      | 12.12%  |
| 1.01-2.0   | 5        | 11     | 7.58%   |
| 4.01-10.0  | 1        | 2      | 1.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 16       | 33.33%  |
| More than 3000 | 6        | 12.5%   |
| 251-500        | 6        | 12.5%   |
| 1-20           | 5        | 10.42%  |
| 1001-2000      | 4        | 8.33%   |
| 51-100         | 4        | 8.33%   |
| 501-1000       | 3        | 6.25%   |
| 2001-3000      | 2        | 4.17%   |
| 21-50          | 1        | 2.08%   |
| Unknown        | 1        | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 14       | 28%     |
| 1-20           | 13       | 26%     |
| 51-100         | 8        | 16%     |
| 101-250        | 5        | 10%     |
| 1001-2000      | 3        | 6%      |
| More than 3000 | 2        | 4%      |
| 251-500        | 2        | 4%      |
| 2001-3000      | 1        | 2%      |
| 501-1000       | 1        | 2%      |
| Unknown        | 1        | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1        | 1      | 33.33%  |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 33.33%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| WDC     | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| WDC     | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 100%    |

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
| Detected | 32       | 96     | 61.54%  |
| Works    | 17       | 37     | 32.69%  |
| Malfunc  | 3        | 3      | 5.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 25       | 37.88%  |
| AMD                         | 20       | 30.3%   |
| Samsung Electronics         | 6        | 9.09%   |
| SanDisk                     | 3        | 4.55%   |
| Micron/Crucial Technology   | 2        | 3.03%   |
| Micron Technology           | 2        | 3.03%   |
| Transcend                   | 1        | 1.52%   |
| Seagate Technology          | 1        | 1.52%   |
| Phison Electronics          | 1        | 1.52%   |
| OCZ Technology Group        | 1        | 1.52%   |
| Nvidia                      | 1        | 1.52%   |
| Marvell Technology Group    | 1        | 1.52%   |
| Kingston Technology Company | 1        | 1.52%   |
| JMicron Technology          | 1        | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9        | 11.11%  |
| AMD 400 Series Chipset SATA Controller                                         | 5        | 6.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 3.7%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2        | 2.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 2.47%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 2.47%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 2.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 2.47%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 2.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 2.47%   |
| AMD FCH IDE Controller                                                         | 2        | 2.47%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 2        | 2.47%   |
| AMD 600 Series Chipset SATA Controller                                         | 2        | 2.47%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 2.47%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 1        | 1.23%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                      | 1        | 1.23%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1        | 1.23%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1        | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1        | 1.23%   |
| Samsung NVMe SSD Controller 172X                                               | 1        | 1.23%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 1.23%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 1.23%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.23%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 1.23%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 1.23%   |
| Micron 2550 NVMe SSD (DRAM-less)                                               | 1        | 1.23%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 1        | 1.23%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.23%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                     | 1        | 1.23%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 1.23%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1        | 1.23%   |
| Intel sSATA Controller [RAID Mode]                                             | 1        | 1.23%   |
| Intel SATA Controller [RAID Mode]                                              | 1        | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.23%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 1.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 1.23%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 59.7%   |
| NVMe | 16       | 23.88%  |
| IDE  | 10       | 14.93%  |
| RAID | 1        | 1.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 25       | 53.19%  |
| AMD    | 22       | 46.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 4.26%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 4.26%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 4.26%   |
| Intel Xeon CPU X5492 @ 3.40GHz              | 1        | 2.13%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 2.13%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz        | 1        | 2.13%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz         | 1        | 2.13%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 2.13%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1        | 2.13%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 2.13%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 2.13%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 2.13%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 2.13%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 2.13%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 2.13%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 2.13%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 2.13%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 2.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 2.13%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 2.13%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 2.13%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 1        | 2.13%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 2.13%   |
| Intel Atom x5-Z8330 CPU @ 1.44GHz           | 1        | 2.13%   |
| Intel 12th Gen Core i7-12700                | 1        | 2.13%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz      | 1        | 2.13%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 1        | 2.13%   |
| AMD Ryzen 9 7900 12-Core Processor          | 1        | 2.13%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 2.13%   |
| AMD Ryzen 7 8845HS w/ Radeon 780M Graphics  | 1        | 2.13%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 1        | 2.13%   |
| AMD Ryzen 5 5600 6-Core Processor           | 1        | 2.13%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 2.13%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1        | 2.13%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 2.13%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 2.13%   |
| AMD Phenom II X4 965 Processor              | 1        | 2.13%   |
| AMD FX-8150 Eight-Core Processor            | 1        | 2.13%   |
| AMD Athlon X4 845 Quad Core Processor       | 1        | 2.13%   |
| AMD Athlon II X3 445 Processor              | 1        | 2.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 10       | 21.28%  |
| AMD Ryzen 5       | 7        | 14.89%  |
| Intel Xeon        | 4        | 8.51%   |
| Intel Core i7     | 4        | 8.51%   |
| AMD Ryzen 9       | 3        | 6.38%   |
| Other             | 2        | 4.26%   |
| Intel Core i3     | 2        | 4.26%   |
| AMD Ryzen 7       | 2        | 4.26%   |
| AMD Ryzen 3       | 2        | 4.26%   |
| AMD A4            | 2        | 4.26%   |
| Intel Pentium     | 1        | 2.13%   |
| Intel Core 2 Quad | 1        | 2.13%   |
| Intel Atom        | 1        | 2.13%   |
| AMD Phenom II X4  | 1        | 2.13%   |
| AMD FX            | 1        | 2.13%   |
| AMD Athlon X4     | 1        | 2.13%   |
| AMD Athlon II X3  | 1        | 2.13%   |
| AMD Athlon        | 1        | 2.13%   |
| AMD A10           | 1        | 2.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 19       | 40.43%  |
| 6      | 9        | 19.15%  |
| 2      | 7        | 14.89%  |
| 12     | 4        | 8.51%   |
| 8      | 4        | 8.51%   |
| 1      | 2        | 4.26%   |
| 16     | 1        | 2.13%   |
| 3      | 1        | 2.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 45       | 95.74%  |
| 2      | 2        | 4.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 31       | 65.96%  |
| 1      | 16       | 34.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 47       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 63.27%  |
| 0x306a9    | 3        | 6.12%   |
| 0x506e3    | 2        | 4.08%   |
| 0x406f1    | 2        | 4.08%   |
| 0xa0671    | 1        | 2.04%   |
| 0x406c4    | 1        | 2.04%   |
| 0x306c3    | 1        | 2.04%   |
| 0x10677    | 1        | 2.04%   |
| 0x0a601206 | 1        | 2.04%   |
| 0x0a50000c | 1        | 2.04%   |
| 0x0a201205 | 1        | 2.04%   |
| 0x0a201016 | 1        | 2.04%   |
| 0x08108109 | 1        | 2.04%   |
| 0x08108102 | 1        | 2.04%   |
| 0x06001119 | 1        | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen+             | 6        | 12.77%  |
| Zen 3            | 5        | 10.64%  |
| Haswell          | 5        | 10.64%  |
| Skylake          | 3        | 6.38%   |
| SandyBridge      | 3        | 6.38%   |
| IvyBridge        | 3        | 6.38%   |
| Unknown          | 3        | 6.38%   |
| Piledriver       | 2        | 4.26%   |
| Penryn           | 2        | 4.26%   |
| K10              | 2        | 4.26%   |
| Broadwell        | 2        | 4.26%   |
| Zen              | 1        | 2.13%   |
| Westmere         | 1        | 2.13%   |
| Steamroller      | 1        | 2.13%   |
| Silvermont       | 1        | 2.13%   |
| Nehalem          | 1        | 2.13%   |
| KabyLake         | 1        | 2.13%   |
| Icelake          | 1        | 2.13%   |
| Excavator        | 1        | 2.13%   |
| CometLake        | 1        | 2.13%   |
| Bulldozer        | 1        | 2.13%   |
| Alderlake Hybrid | 1        | 2.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 19       | 37.25%  |
| Nvidia | 17       | 33.33%  |
| Intel  | 15       | 29.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 7.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 5.88%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 3        | 5.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 3.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 3.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.92%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                                  | 2        | 3.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 3.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 3.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 3.92%   |
| Nvidia TU117GL [T400 4GB / T400E]                                                        | 1        | 1.96%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 1.96%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 1.96%   |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 1.96%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.96%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.96%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1        | 1.96%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 1.96%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1        | 1.96%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 1.96%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1        | 1.96%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 1.96%   |
| Nvidia AD102 [GeForce RTX 4090]                                                          | 1        | 1.96%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.96%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                                | 1        | 1.96%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.96%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 1.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.96%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1        | 1.96%   |
| AMD Juniper PRO [Radeon HD 5750]                                                         | 1        | 1.96%   |
| AMD HawkPoint1                                                                           | 1        | 1.96%   |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 1.96%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 18       | 38.3%   |
| 1 x Nvidia   | 16       | 34.04%  |
| 1 x Intel    | 12       | 25.53%  |
| AMD + Nvidia | 1        | 2.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 37       | 77.08%  |
| Proprietary | 9        | 18.75%  |
| Unknown     | 2        | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 63.83%  |
| 3.01-4.0   | 5        | 10.64%  |
| 7.01-8.0   | 3        | 6.38%   |
| 1.01-2.0   | 3        | 6.38%   |
| 16.01-24.0 | 2        | 4.26%   |
| 0.01-0.5   | 2        | 4.26%   |
| 2.01-3.0   | 1        | 2.13%   |
| 0.51-1.0   | 1        | 2.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 14       | 30.43%  |
| AOC                  | 4        | 8.7%    |
| Philips              | 3        | 6.52%   |
| Hewlett-Packard      | 3        | 6.52%   |
| Goldstar             | 3        | 6.52%   |
| SANYO                | 2        | 4.35%   |
| Fujitsu Siemens      | 2        | 4.35%   |
| Ancor Communications | 2        | 4.35%   |
| Acer                 | 2        | 4.35%   |
| Vizio                | 1        | 2.17%   |
| Unknown (XXX)        | 1        | 2.17%   |
| Sony                 | 1        | 2.17%   |
| RTK                  | 1        | 2.17%   |
| Panasonic            | 1        | 2.17%   |
| NEC Computers        | 1        | 2.17%   |
| MSI                  | 1        | 2.17%   |
| LG Electronics       | 1        | 2.17%   |
| HKC                  | 1        | 2.17%   |
| Dell                 | 1        | 2.17%   |
| BenQ                 | 1        | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio D24h-C1 VIZ0095 1360x768 521x293mm 23.5-inch                    | 1        | 1.96%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 1.96%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 1.96%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1        | 1.96%   |
| SANYO LCD SAN0A12 1920x540                                            | 1        | 1.96%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1        | 1.96%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 531x299mm 24.0-inch  | 1        | 1.96%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch  | 1        | 1.96%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch   | 1        | 1.96%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch     | 1        | 1.96%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 1.96%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch     | 1        | 1.96%   |
| Samsung Electronics Odyssey G7 SAM72BF 3840x2160 697x392mm 31.5-inch  | 1        | 1.96%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1        | 1.96%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 1.96%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 1        | 1.96%   |
| Samsung Electronics LCD Monitor SAM0E4C 1360x768 522x293mm 23.6-inch  | 1        | 1.96%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 1.96%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch     | 1        | 1.96%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 1.96%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1        | 1.96%   |
| Philips PHL 272V8 PHLC21A 1920x1080 598x336mm 27.0-inch               | 1        | 1.96%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch              | 1        | 1.96%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch               | 1        | 1.96%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                   | 1        | 1.96%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                               | 1        | 1.96%   |
| NEC Computers E224Wi NEC694F 1920x1080 476x267mm 21.5-inch            | 1        | 1.96%   |
| NEC Computers E224Wi NEC694E 1920x1080 476x267mm 21.5-inch            | 1        | 1.96%   |
| MSI G273CQ MSI3DC0 2560x1440 597x336mm 27.0-inch                      | 1        | 1.96%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                      | 1        | 1.96%   |
| HKC Monitor HKC2160 1920x1080 304x228mm 15.0-inch                     | 1        | 1.96%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 1        | 1.96%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1        | 1.96%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 1.96%   |
| Goldstar W2343 GSM5701 1920x1080 510x290mm 23.1-inch                  | 1        | 1.96%   |
| Goldstar W2052 GSM4E89 1680x1050 474x296mm 22.0-inch                  | 1        | 1.96%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 1        | 1.96%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch               | 1        | 1.96%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 1        | 1.96%   |
| Fujitsu Siemens B27T-7 Pro FUS0891 1920x1080 598x336mm 27.0-inch      | 1        | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 25       | 53.19%  |
| 3840x2160 (4K)     | 5        | 10.64%  |
| 1920x540           | 3        | 6.38%   |
| 1366x768 (WXGA)    | 3        | 6.38%   |
| 3440x1440          | 2        | 4.26%   |
| 2560x1440 (QHD)    | 2        | 4.26%   |
| 1920x1200 (WUXGA)  | 2        | 4.26%   |
| 1680x1050 (WSXGA+) | 2        | 4.26%   |
| 2560x1080          | 1        | 2.13%   |
| 1600x900 (HD+)     | 1        | 2.13%   |
| 1280x1024 (SXGA)   | 1        | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 9        | 18.37%  |
| 23      | 7        | 14.29%  |
| 27      | 6        | 12.24%  |
| 31      | 5        | 10.2%   |
| 21      | 5        | 10.2%   |
| 34      | 3        | 6.12%   |
| Unknown | 3        | 6.12%   |
| 54      | 2        | 4.08%   |
| 72      | 1        | 2.04%   |
| 46      | 1        | 2.04%   |
| 40      | 1        | 2.04%   |
| 33      | 1        | 2.04%   |
| 32      | 1        | 2.04%   |
| 28      | 1        | 2.04%   |
| 22      | 1        | 2.04%   |
| 20      | 1        | 2.04%   |
| 18      | 1        | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 42.55%  |
| 401-500     | 8        | 17.02%  |
| 601-700     | 6        | 12.77%  |
| 701-800     | 5        | 10.64%  |
| 1001-1500   | 3        | 6.38%   |
| Unknown     | 3        | 6.38%   |
| 801-900     | 1        | 2.13%   |
| 1501-2000   | 1        | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 34       | 77.27%  |
| 16/10   | 4        | 9.09%   |
| 21/9    | 3        | 6.82%   |
| Unknown | 2        | 4.55%   |
| 32/9    | 1        | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 16       | 34.78%  |
| 351-500        | 11       | 23.91%  |
| 301-350        | 6        | 13.04%  |
| More than 1000 | 3        | 6.52%   |
| Unknown        | 3        | 6.52%   |
| 251-300        | 2        | 4.35%   |
| 151-200        | 2        | 4.35%   |
| 501-1000       | 2        | 4.35%   |
| 141-150        | 1        | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 27       | 58.7%   |
| 1-50    | 6        | 13.04%  |
| 101-120 | 6        | 13.04%  |
| 121-160 | 4        | 8.7%    |
| Unknown | 3        | 6.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 82.98%  |
| 2     | 7        | 14.89%  |
| 0     | 1        | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 26       | 39.39%  |
| Realtek Semiconductor | 25       | 37.88%  |
| Qualcomm Atheros      | 2        | 3.03%   |
| Broadcom              | 2        | 3.03%   |
| T & A Mobile Phones   | 1        | 1.52%   |
| Raspberry Pi          | 1        | 1.52%   |
| Ralink Technology     | 1        | 1.52%   |
| Nvidia                | 1        | 1.52%   |
| Microsoft             | 1        | 1.52%   |
| Microchip Technology  | 1        | 1.52%   |
| MediaTek              | 1        | 1.52%   |
| Edimax Technology     | 1        | 1.52%   |
| Broadcom Limited      | 1        | 1.52%   |
| ASUSTek Computer      | 1        | 1.52%   |
| ASIX Electronics      | 1        | 1.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19       | 24.68%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3        | 3.9%    |
| Intel Ethernet Connection I217-LM                                      | 3        | 3.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 3.9%    |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 2.6%    |
| Intel Wi-Fi 6 AX200                                                    | 2        | 2.6%    |
| Intel I211 Gigabit Network Connection                                  | 2        | 2.6%    |
| Intel I210 Gigabit Network Connection                                  | 2        | 2.6%    |
| Intel Ethernet Controller I225-V                                       | 2        | 2.6%    |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 2.6%    |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 2.6%    |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 2.6%    |
| T & A Mobile Phones TCL 50 XL 5G                                       | 1        | 1.3%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 1.3%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 1.3%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 1.3%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 1.3%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 1.3%    |
| Realtek 802.11ac NIC                                                   | 1        | 1.3%    |
| Raspberry Pi Pico SSR Control                                          | 1        | 1.3%    |
| Ralink RT3072 Wireless Adapter                                         | 1        | 1.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.3%    |
| Nvidia MCP61 Ethernet                                                  | 1        | 1.3%    |
| Microsoft Wireless XBox Controller Dongle                              | 1        | 1.3%    |
| Microchip MCP2200 USB Serial Port Emulator                             | 1        | 1.3%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1        | 1.3%    |
| Intel Wireless 7265                                                    | 1        | 1.3%    |
| Intel Wireless 7260                                                    | 1        | 1.3%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 1.3%    |
| Intel Ethernet Controller I226-V                                       | 1        | 1.3%    |
| Intel Ethernet Controller I225-LM                                      | 1        | 1.3%    |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 1.3%    |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 1.3%    |
| Intel 82578DC Gigabit Network Connection                               | 1        | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 1.3%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]         | 1        | 1.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 50%     |
| Realtek Semiconductor | 6        | 25%     |
| Ralink Technology     | 1        | 4.17%   |
| Microsoft             | 1        | 4.17%   |
| MediaTek              | 1        | 4.17%   |
| Edimax Technology     | 1        | 4.17%   |
| Broadcom              | 1        | 4.17%   |
| ASUSTek Computer      | 1        | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 3        | 12.5%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3        | 12.5%   |
| Intel Wi-Fi 6 AX200                                            | 2        | 8.33%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1        | 4.17%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 4.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 4.17%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 4.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 4.17%   |
| Realtek 802.11ac NIC                                           | 1        | 4.17%   |
| Ralink RT3072 Wireless Adapter                                 | 1        | 4.17%   |
| Microsoft Wireless XBox Controller Dongle                      | 1        | 4.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1        | 4.17%   |
| Intel Wireless 7265                                            | 1        | 4.17%   |
| Intel Wireless 7260                                            | 1        | 4.17%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1        | 4.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 4.17%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 4.17%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1        | 4.17%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]      | 1        | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 45.83%  |
| Intel                 | 19       | 39.58%  |
| Qualcomm Atheros      | 2        | 4.17%   |
| T & A Mobile Phones   | 1        | 2.08%   |
| Nvidia                | 1        | 2.08%   |
| Broadcom Limited      | 1        | 2.08%   |
| Broadcom              | 1        | 2.08%   |
| ASIX Electronics      | 1        | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19       | 37.25%  |
| Intel Ethernet Connection I217-LM                                      | 3        | 5.88%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 3.92%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 3.92%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 3.92%   |
| Intel Ethernet Controller I225-V                                       | 2        | 3.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 3.92%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 3.92%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 3.92%   |
| T & A Mobile Phones TCL 50 XL 5G                                       | 1        | 1.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 1.96%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 1.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 1.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.96%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 1.96%   |
| Intel Ethernet Controller I226-V                                       | 1        | 1.96%   |
| Intel Ethernet Controller I225-LM                                      | 1        | 1.96%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 1.96%   |
| Intel 82578DC Gigabit Network Connection                               | 1        | 1.96%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 1.96%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 1        | 1.96%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 1        | 1.96%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1        | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 46       | 64.79%  |
| WiFi     | 23       | 32.39%  |
| Modem    | 2        | 2.82%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 38       | 77.55%  |
| WiFi     | 11       | 22.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 65.96%  |
| 2     | 14       | 29.79%  |
| 3     | 2        | 4.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 80.85%  |
| Yes  | 9        | 19.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 68.75%  |
| Cambridge Silicon Radio | 3        | 18.75%  |
| MediaTek                | 1        | 6.25%   |
| Broadcom                | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX210 Bluetooth                               | 3        | 18.75%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 18.75%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 12.5%   |
| Intel Bluetooth wireless interface                  | 2        | 12.5%   |
| Intel AX200 Bluetooth                               | 2        | 12.5%   |
| MediaTek Wireless_Device                            | 1        | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 6.25%   |
| Intel Bluetooth Device                              | 1        | 6.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| AMD                     | 25       | 33.78%  |
| Intel                   | 23       | 31.08%  |
| Nvidia                  | 17       | 22.97%  |
| Logitech                | 2        | 2.7%    |
| Texas Instruments       | 1        | 1.35%   |
| Shure                   | 1        | 1.35%   |
| Realtek Semiconductor   | 1        | 1.35%   |
| GN Netcom               | 1        | 1.35%   |
| DSEA A/S                | 1        | 1.35%   |
| ClearOne Communications | 1        | 1.35%   |
| ASUSTek Computer        | 1        | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Ryzen HD Audio Controller                                              | 9        | 9.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 5.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 4.35%   |
| AMD FCH Azalia Controller                                                  | 4        | 4.35%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 3.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 3.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 3.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 3.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 3.26%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 3.26%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.17%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.17%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 2        | 2.17%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 2        | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 2.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.17%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.17%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.09%   |
| Shure MV88+                                                                | 1        | 1.09%   |
| Realtek Semiconductor USB Audio                                            | 1        | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.09%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.09%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.09%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 1.09%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1        | 1.09%   |
| Logitech Blue Microphones                                                  | 1        | 1.09%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.09%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 1.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.09%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 20%     |
| Kingston            | 5        | 20%     |
| Crucial             | 4        | 16%     |
| SK hynix            | 2        | 8%      |
| Micron Technology   | 2        | 8%      |
| Corsair             | 2        | 8%      |
| A-DATA Technology   | 2        | 8%      |
| Transcend           | 1        | 4%      |
| G.Skill             | 1        | 4%      |
| Elpida              | 1        | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s    | 2        | 7.41%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s       | 1        | 3.7%    |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s               | 1        | 3.7%    |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s     | 1        | 3.7%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s              | 1        | 3.7%    |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                | 1        | 3.7%    |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s | 1        | 3.7%    |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s     | 1        | 3.7%    |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s      | 1        | 3.7%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s   | 1        | 3.7%    |
| Micron RAM 16JTF51264AZ-1G4D1 4GB DIMM DDR3 1333MT/s     | 1        | 3.7%    |
| Kingston RAM KHX3000C15D4/4GX 4GB DIMM DDR4 3000MT/s     | 1        | 3.7%    |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s        | 1        | 3.7%    |
| Kingston RAM 9905403-011.A02LF 2GB DIMM DDR3 1333MT/s    | 1        | 3.7%    |
| G.Skill RAM F5-6000J3238F16G 16GB DIMM DDR5 12800MT/s    | 1        | 3.7%    |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2GB DIMM DDR3 1333MT/s      | 1        | 3.7%    |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s   | 1        | 3.7%    |
| Crucial RAM CT8G4DFD8213.C16FAD 8GB DIMM DDR4 2133MT/s   | 1        | 3.7%    |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s    | 1        | 3.7%    |
| Crucial RAM BLS8G4D26BFSBK.8FD 8GB DIMM DDR4 2933MT/s    | 1        | 3.7%    |
| Crucial RAM BL8G26C16U4B.8FD 8GB DIMM DDR4 2667MT/s      | 1        | 3.7%    |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM SDRAM 1333MT/s     | 1        | 3.7%    |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s      | 1        | 3.7%    |
| Corsair RAM CMP8GX3M2A1600C9 4GB DIMM DDR3 1333MT/s      | 1        | 3.7%    |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s              | 1        | 3.7%    |
| A-DATA RAM CBDAD5S560016G-BAD 16GB SODIMM DDR5 5600MT/s  | 1        | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 10       | 50%     |
| DDR3  | 5        | 25%     |
| DDR5  | 3        | 15%     |
| SDRAM | 1        | 5%      |
| DRAM  | 1        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 15       | 75%     |
| SODIMM | 5        | 25%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 36.36%  |
| 16384 | 6        | 27.27%  |
| 4096  | 5        | 22.73%  |
| 2048  | 2        | 9.09%   |
| 32768 | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 20.83%  |
| 2133  | 3        | 12.5%   |
| 1333  | 3        | 12.5%   |
| 3733  | 2        | 8.33%   |
| 2667  | 2        | 8.33%   |
| 2400  | 2        | 8.33%   |
| 12800 | 1        | 4.17%   |
| 5600  | 1        | 4.17%   |
| 4800  | 1        | 4.17%   |
| 3600  | 1        | 4.17%   |
| 3000  | 1        | 4.17%   |
| 2933  | 1        | 4.17%   |
| 1066  | 1        | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP DeskJet 3700 series | 1        | 100%    |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 3        | 33.33%  |
| WaveRider Communications      | 1        | 11.11%  |
| ValueHD                       | 1        | 11.11%  |
| Sunplus Innovation Technology | 1        | 11.11%  |
| Samsung Electronics           | 1        | 11.11%  |
| Microdia                      | 1        | 11.11%  |
| Generalplus Technology        | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920              | 2        | 22.22%  |
| WaveRider USB 2.0 Camera                 | 1        | 11.11%  |
| ValueHD Konftel Cam20                    | 1        | 11.11%  |
| Sunplus Integrated Camera                | 1        | 11.11%  |
| Samsung Galaxy series, misc. (MTP mode)  | 1        | 11.11%  |
| Microdia Camera                          | 1        | 11.11%  |
| Logitech BRIO Ultra HD Webcam            | 1        | 11.11%  |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 11.11%  |

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
| 0     | 40       | 81.63%  |
| 1     | 6        | 12.24%  |
| 2     | 2        | 4.08%   |
| 4     | 1        | 2.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 3        | 25%     |
| Net/wireless     | 3        | 25%     |
| Sound            | 2        | 16.67%  |
| Graphics card    | 2        | 16.67%  |
| Net/ethernet     | 1        | 8.33%   |
| Bluetooth        | 1        | 8.33%   |

