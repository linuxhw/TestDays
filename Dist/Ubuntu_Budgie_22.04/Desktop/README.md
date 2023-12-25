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

Total: 50

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.0-52-generic      | 4        | 9.52%   |
| 5.15.0-57-generic      | 3        | 7.14%   |
| 5.15.0-46-generic      | 3        | 7.14%   |
| 5.15.0-43-generic      | 3        | 7.14%   |
| 5.15.0-30-generic      | 3        | 7.14%   |
| 5.19.0-45-generic      | 2        | 4.76%   |
| 5.19.0-40-generic      | 2        | 4.76%   |
| 5.15.0-33-generic      | 2        | 4.76%   |
| 5.15.0-27-generic      | 2        | 4.76%   |
| 5.15.0-25-generic      | 2        | 4.76%   |
| 6.2.0-36-generic       | 1        | 2.38%   |
| 6.2.0-35-generic       | 1        | 2.38%   |
| 6.2.0-33-generic       | 1        | 2.38%   |
| 6.2.0-26-generic       | 1        | 2.38%   |
| 5.19.0-46-generic      | 1        | 2.38%   |
| 5.17.2-051702-generic  | 1        | 2.38%   |
| 5.15.92-051592-generic | 1        | 2.38%   |
| 5.15.0-84-generic      | 1        | 2.38%   |
| 5.15.0-73-generic      | 1        | 2.38%   |
| 5.15.0-71-generic      | 1        | 2.38%   |
| 5.15.0-56-generic      | 1        | 2.38%   |
| 5.15.0-50-generic      | 1        | 2.38%   |
| 5.15.0-48-generic      | 1        | 2.38%   |
| 5.15.0-47-generic      | 1        | 2.38%   |
| 5.15.0-41-generic      | 1        | 2.38%   |
| 5.13.0-44-generic      | 1        | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 28       | 70%     |
| 5.19.0  | 5        | 12.5%   |
| 6.2.0   | 4        | 10%     |
| 5.17.2  | 1        | 2.5%    |
| 5.15.92 | 1        | 2.5%    |
| 5.13.0  | 1        | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 29       | 72.5%   |
| 5.19    | 5        | 12.5%   |
| 6.2     | 4        | 10%     |
| 5.17    | 1        | 2.5%    |
| 5.13    | 1        | 2.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 39       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 39       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 39       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 29       | 74.36%  |
| Unknown | 9        | 23.08%  |
| GDM     | 1        | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 16       | 41.03%  |
| de_DE | 6        | 15.38%  |
| pt_BR | 4        | 10.26%  |
| es_ES | 3        | 7.69%   |
| fr_FR | 2        | 5.13%   |
| en_GB | 2        | 5.13%   |
| es_MX | 1        | 2.56%   |
| es_AR | 1        | 2.56%   |
| en_ZA | 1        | 2.56%   |
| en_CA | 1        | 2.56%   |
| en_AU | 1        | 2.56%   |
| el_GR | 1        | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 29       | 72.5%   |
| EFI  | 11       | 27.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 31       | 79.49%  |
| Tmpfs   | 3        | 7.69%   |
| Overlay | 3        | 7.69%   |
| Zfs     | 1        | 2.56%   |
| Btrfs   | 1        | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 23       | 57.5%   |
| Unknown | 16       | 40%     |
| MBR     | 1        | 2.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 79.49%  |
| Yes       | 8        | 20.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 58.97%  |
| Yes       | 16       | 41.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 10       | 25.64%  |
| MSI                 | 6        | 15.38%  |
| Hewlett-Packard     | 4        | 10.26%  |
| ASUSTek Computer    | 4        | 10.26%  |
| Intel               | 3        | 7.69%   |
| Fujitsu             | 3        | 7.69%   |
| Dell                | 3        | 7.69%   |
| ASRock              | 3        | 7.69%   |
| Semp Toshiba        | 1        | 2.56%   |
| Lenovo              | 1        | 2.56%   |
| Biostar             | 1        | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Semp Toshiba STI                   | 1        | 2.56%   |
| MSI MS-7C95                        | 1        | 2.56%   |
| MSI MS-7C51                        | 1        | 2.56%   |
| MSI MS-7B86                        | 1        | 2.56%   |
| MSI MS-7A32                        | 1        | 2.56%   |
| MSI MS-7885                        | 1        | 2.56%   |
| MSI MS-7721                        | 1        | 2.56%   |
| Lenovo ThinkStation C20 4263BA7    | 1        | 2.56%   |
| Intel STK1A32SC                    | 1        | 2.56%   |
| Intel H61                          | 1        | 2.56%   |
| Intel DP55WB AAE64798-206          | 1        | 2.56%   |
| HP Z440 Workstation                | 1        | 2.56%   |
| HP EliteDesk 800 G2 SFF            | 1        | 2.56%   |
| HP EliteDesk 800 G1 DM             | 1        | 2.56%   |
| HP 750-417c                        | 1        | 2.56%   |
| Gigabyte X570S AORUS PRO AX        | 1        | 2.56%   |
| Gigabyte M68MT-S2                  | 1        | 2.56%   |
| Gigabyte H410M S2H V3              | 1        | 2.56%   |
| Gigabyte H310MHD2                  | 1        | 2.56%   |
| Gigabyte GA-890GPA-UD3H            | 1        | 2.56%   |
| Gigabyte F2A78M-HD2                | 1        | 2.56%   |
| Gigabyte B75M-D3P                  | 1        | 2.56%   |
| Gigabyte B75M-D3H                  | 1        | 2.56%   |
| Gigabyte B550 AORUS ELITE AX V2    | 1        | 2.56%   |
| Gigabyte B450 I AORUS PRO WIFI     | 1        | 2.56%   |
| Fujitsu ESPRIMO Q920               | 1        | 2.56%   |
| Fujitsu ESPRIMO Q910               | 1        | 2.56%   |
| Fujitsu D3348-B2                   | 1        | 2.56%   |
| Dell Precision WorkStation T7400   | 1        | 2.56%   |
| Dell OptiPlex 780                  | 1        | 2.56%   |
| Dell OptiPlex 390                  | 1        | 2.56%   |
| Biostar A960D+V3                   | 1        | 2.56%   |
| ASUS ROG STRIX X670E-E GAMING WIFI | 1        | 2.56%   |
| ASUS PRIME B560M-A                 | 1        | 2.56%   |
| ASUS All Series                    | 1        | 2.56%   |
| ASUS A88X-PRO                      | 1        | 2.56%   |
| ASRock FM2A88X Extreme4+           | 1        | 2.56%   |
| ASRock B450M Steel Legend          | 1        | 2.56%   |
| ASRock A300M-STX                   | 1        | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| HP EliteDesk            | 2        | 5.13%   |
| Fujitsu ESPRIMO         | 2        | 5.13%   |
| Dell OptiPlex           | 2        | 5.13%   |
| Semp Toshiba STI        | 1        | 2.56%   |
| MSI MS-7C95             | 1        | 2.56%   |
| MSI MS-7C51             | 1        | 2.56%   |
| MSI MS-7B86             | 1        | 2.56%   |
| MSI MS-7A32             | 1        | 2.56%   |
| MSI MS-7885             | 1        | 2.56%   |
| MSI MS-7721             | 1        | 2.56%   |
| Lenovo ThinkStation     | 1        | 2.56%   |
| Intel STK1A32SC         | 1        | 2.56%   |
| Intel H61               | 1        | 2.56%   |
| Intel DP55WB            | 1        | 2.56%   |
| HP Z440                 | 1        | 2.56%   |
| HP 750-417c             | 1        | 2.56%   |
| Gigabyte X570S          | 1        | 2.56%   |
| Gigabyte M68MT-S2       | 1        | 2.56%   |
| Gigabyte H410M          | 1        | 2.56%   |
| Gigabyte H310MHD2       | 1        | 2.56%   |
| Gigabyte GA-890GPA-UD3H | 1        | 2.56%   |
| Gigabyte F2A78M-HD2     | 1        | 2.56%   |
| Gigabyte B75M-D3P       | 1        | 2.56%   |
| Gigabyte B75M-D3H       | 1        | 2.56%   |
| Gigabyte B550           | 1        | 2.56%   |
| Gigabyte B450           | 1        | 2.56%   |
| Fujitsu D3348-B2        | 1        | 2.56%   |
| Dell Precision          | 1        | 2.56%   |
| Biostar A960D+V3        | 1        | 2.56%   |
| ASUS ROG                | 1        | 2.56%   |
| ASUS PRIME              | 1        | 2.56%   |
| ASUS All                | 1        | 2.56%   |
| ASUS A88X-PRO           | 1        | 2.56%   |
| ASRock FM2A88X          | 1        | 2.56%   |
| ASRock B450M            | 1        | 2.56%   |
| ASRock A300M-STX        | 1        | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 7        | 17.95%  |
| 2018 | 4        | 10.26%  |
| 2021 | 3        | 7.69%   |
| 2019 | 3        | 7.69%   |
| 2017 | 3        | 7.69%   |
| 2015 | 3        | 7.69%   |
| 2011 | 3        | 7.69%   |
| 2010 | 3        | 7.69%   |
| 2020 | 2        | 5.13%   |
| 2016 | 2        | 5.13%   |
| 2012 | 2        | 5.13%   |
| 2022 | 1        | 2.56%   |
| 2013 | 1        | 2.56%   |
| 2009 | 1        | 2.56%   |
| 2008 | 1        | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 39       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 39       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 39       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 12       | 30.77%  |
| 8.01-16.0       | 11       | 28.21%  |
| 4.01-8.0        | 8        | 20.51%  |
| 32.01-64.0      | 2        | 5.13%   |
| 24.01-32.0      | 2        | 5.13%   |
| 64.01-256.0     | 2        | 5.13%   |
| More than 256.0 | 1        | 2.56%   |
| 1.01-2.0        | 1        | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 15       | 35.71%  |
| 2.01-3.0   | 13       | 30.95%  |
| 4.01-8.0   | 7        | 16.67%  |
| 3.01-4.0   | 4        | 9.52%   |
| 8.01-16.0  | 2        | 4.76%   |
| 16.01-24.0 | 1        | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 33.33%  |
| 1      | 12       | 30.77%  |
| 4      | 5        | 12.82%  |
| 3      | 5        | 12.82%  |
| 6      | 2        | 5.13%   |
| 8      | 1        | 2.56%   |
| 7      | 1        | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 56.41%  |
| Yes       | 17       | 43.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 38       | 97.44%  |
| No        | 1        | 2.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 51.28%  |
| Yes       | 19       | 48.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 71.79%  |
| Yes       | 11       | 28.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 10       | 25.64%  |
| Germany      | 5        | 12.82%  |
| Brazil       | 5        | 12.82%  |
| UK           | 2        | 5.13%   |
| Switzerland  | 2        | 5.13%   |
| Spain        | 2        | 5.13%   |
| France       | 2        | 5.13%   |
| Argentina    | 2        | 5.13%   |
| South Africa | 1        | 2.56%   |
| Slovenia     | 1        | 2.56%   |
| Romania      | 1        | 2.56%   |
| Norway       | 1        | 2.56%   |
| Mexico       | 1        | 2.56%   |
| Greece       | 1        | 2.56%   |
| Croatia      | 1        | 2.56%   |
| Austria      | 1        | 2.56%   |
| Australia    | 1        | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Brasília             | 3        | 7.32%   |
| Milwaukee             | 2        | 4.88%   |
| Zurich                | 1        | 2.44%   |
| Walled Lake           | 1        | 2.44%   |
| Trondheim             | 1        | 2.44%   |
| Tocantins             | 1        | 2.44%   |
| Tann                  | 1        | 2.44%   |
| Seattle               | 1        | 2.44%   |
| San Luis Potosí City | 1        | 2.44%   |
| San Francisco         | 1        | 2.44%   |
| San Diego             | 1        | 2.44%   |
| Rueil-Malmaison       | 1        | 2.44%   |
| Pula                  | 1        | 2.44%   |
| Pine Island           | 1        | 2.44%   |
| New York              | 1        | 2.44%   |
| Maribor               | 1        | 2.44%   |
| Manaus                | 1        | 2.44%   |
| Madrid                | 1        | 2.44%   |
| London                | 1        | 2.44%   |
| Limay                 | 1        | 2.44%   |
| Kittsee               | 1        | 2.44%   |
| Kirkcaldy             | 1        | 2.44%   |
| Houston               | 1        | 2.44%   |
| Hamburg               | 1        | 2.44%   |
| Granada               | 1        | 2.44%   |
| Eugene                | 1        | 2.44%   |
| Ennepetal             | 1        | 2.44%   |
| Dortmund              | 1        | 2.44%   |
| Delbrueck             | 1        | 2.44%   |
| Colon                 | 1        | 2.44%   |
| Caslano               | 1        | 2.44%   |
| Cape Town             | 1        | 2.44%   |
| Camp Hill             | 1        | 2.44%   |
| Brisbane              | 1        | 2.44%   |
| Bradenton             | 1        | 2.44%   |
| Berlin                | 1        | 2.44%   |
| Baia Mare             | 1        | 2.44%   |
| Athens                | 1        | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 15       | 23     | 18.99%  |
| WDC                       | 12       | 13     | 15.19%  |
| Samsung Electronics       | 10       | 30     | 12.66%  |
| SanDisk                   | 5        | 6      | 6.33%   |
| Toshiba                   | 4        | 4      | 5.06%   |
| Crucial                   | 4        | 4      | 5.06%   |
| Transcend                 | 2        | 2      | 2.53%   |
| PNY                       | 2        | 2      | 2.53%   |
| OCZ                       | 2        | 2      | 2.53%   |
| Micron Technology         | 2        | 2      | 2.53%   |
| Kingston                  | 2        | 3      | 2.53%   |
| China                     | 2        | 2      | 2.53%   |
| A-DATA Technology         | 2        | 2      | 2.53%   |
| Zheino                    | 1        | 1      | 1.27%   |
| Unknown                   | 1        | 1      | 1.27%   |
| SPCC                      | 1        | 1      | 1.27%   |
| SK hynix                  | 1        | 1      | 1.27%   |
| Phison                    | 1        | 1      | 1.27%   |
| Mushkin                   | 1        | 1      | 1.27%   |
| Micron/Crucial Technology | 1        | 1      | 1.27%   |
| MicroFrom                 | 1        | 1      | 1.27%   |
| Maxtor                    | 1        | 1      | 1.27%   |
| JMicron Technology        | 1        | 1      | 1.27%   |
| Intenso                   | 1        | 1      | 1.27%   |
| Intel                     | 1        | 1      | 1.27%   |
| HGST                      | 1        | 1      | 1.27%   |
| ASMT109x                  | 1        | 1      | 1.27%   |
| 4Life                     | 1        | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB      | 2        | 2.15%   |
| Seagate ST3500418AS 500GB         | 2        | 2.15%   |
| Seagate ST1000LM048-2E7172 1TB    | 2        | 2.15%   |
| SanDisk SDSSDA120G 120GB          | 2        | 2.15%   |
| Samsung SSD 870 EVO 250GB         | 2        | 2.15%   |
| Samsung SSD 850 PRO 256GB         | 2        | 2.15%   |
| Samsung SSD 840 EVO 250GB         | 2        | 2.15%   |
| Zheino CHN-25SATAC3-120 120GB SSD | 1        | 1.08%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1.08%   |
| WDC WD40PURZ-85TTDY0 4TB          | 1        | 1.08%   |
| WDC WD40EZAZ-00SF3B0 4TB          | 1        | 1.08%   |
| WDC WD3200LPVX-22V0TT0 320GB      | 1        | 1.08%   |
| WDC WD20EARX-00PASB0 2TB          | 1        | 1.08%   |
| WDC WD1600AAJS-60WAA0 160GB       | 1        | 1.08%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 1.08%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1.08%   |
| WDC WD10EADS-00M2B0 1TB           | 1        | 1.08%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1.08%   |
| WDC WD Green 2.5 240GB SSD        | 1        | 1.08%   |
| Unknown SD/MMC/MS PRO 128GB       | 1        | 1.08%   |
| Transcend TS480GMTS820S 480GB SSD | 1        | 1.08%   |
| Transcend TS128GMTE110S 128GB     | 1        | 1.08%   |
| Toshiba MD04ACA400 4TB            | 1        | 1.08%   |
| Toshiba HDWD240 4TB               | 1        | 1.08%   |
| Toshiba HDWD220 2TB               | 1        | 1.08%   |
| Toshiba DT01ACA050 500GB          | 1        | 1.08%   |
| SPCC Solid State Disk 256GB       | 1        | 1.08%   |
| SK hynix SC210 2.5 7MM 128GB SSD  | 1        | 1.08%   |
| Seagate ST9500325AS 500GB         | 1        | 1.08%   |
| Seagate ST8000VN0022-2EL112 8TB   | 1        | 1.08%   |
| Seagate ST500LT012-1DG142 500GB   | 1        | 1.08%   |
| Seagate ST4000DM004-2CV104 4TB    | 1        | 1.08%   |
| Seagate ST380815AS 80GB           | 1        | 1.08%   |
| Seagate ST3500413AS 500GB         | 1        | 1.08%   |
| Seagate ST3500412AS 500GB         | 1        | 1.08%   |
| Seagate ST3160815AS 160GB         | 1        | 1.08%   |
| Seagate ST2000DM008-2FR102 2TB    | 1        | 1.08%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1.08%   |
| Seagate ST2000DM001-1ER164 2TB    | 1        | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB    | 1        | 1.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 22     | 42.86%  |
| WDC                 | 10       | 11     | 28.57%  |
| Toshiba             | 4        | 4      | 11.43%  |
| Samsung Electronics | 2        | 3      | 5.71%   |
| Unknown             | 1        | 1      | 2.86%   |
| Maxtor              | 1        | 1      | 2.86%   |
| HGST                | 1        | 1      | 2.86%   |
| ASMT109x            | 1        | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 22     | 21.88%  |
| Crucial             | 4        | 4      | 12.5%   |
| WDC                 | 2        | 2      | 6.25%   |
| SanDisk             | 2        | 2      | 6.25%   |
| PNY                 | 2        | 2      | 6.25%   |
| China               | 2        | 2      | 6.25%   |
| A-DATA Technology   | 2        | 2      | 6.25%   |
| Zheino              | 1        | 1      | 3.13%   |
| Transcend           | 1        | 1      | 3.13%   |
| SPCC                | 1        | 1      | 3.13%   |
| SK hynix            | 1        | 1      | 3.13%   |
| OCZ                 | 1        | 1      | 3.13%   |
| Mushkin             | 1        | 1      | 3.13%   |
| Micron Technology   | 1        | 1      | 3.13%   |
| MicroFrom           | 1        | 1      | 3.13%   |
| Kingston            | 1        | 2      | 3.13%   |
| JMicron Technology  | 1        | 1      | 3.13%   |
| 4Life               | 1        | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 26       | 48     | 39.39%  |
| HDD     | 26       | 44     | 39.39%  |
| NVMe    | 12       | 16     | 18.18%  |
| MMC     | 1        | 1      | 1.52%   |
| Unknown | 1        | 1      | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 37       | 90     | 69.81%  |
| NVMe | 12       | 16     | 22.64%  |
| SAS  | 3        | 3      | 5.66%   |
| MMC  | 1        | 1      | 1.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 33       | 58     | 56.9%   |
| 0.51-1.0   | 13       | 19     | 22.41%  |
| 3.01-4.0   | 6        | 7      | 10.34%  |
| 1.01-2.0   | 5        | 6      | 8.62%   |
| 4.01-10.0  | 1        | 2      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 33.33%  |
| 251-500        | 5        | 12.82%  |
| More than 3000 | 4        | 10.26%  |
| 1001-2000      | 4        | 10.26%  |
| 1-20           | 4        | 10.26%  |
| 51-100         | 4        | 10.26%  |
| 2001-3000      | 2        | 5.13%   |
| 501-1000       | 2        | 5.13%   |
| 21-50          | 1        | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 11       | 27.5%   |
| 1-20           | 11       | 27.5%   |
| 51-100         | 8        | 20%     |
| 101-250        | 4        | 10%     |
| 1001-2000      | 3        | 7.5%    |
| More than 3000 | 1        | 2.5%    |
| 251-500        | 1        | 2.5%    |
| 2001-3000      | 1        | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1        | 1      | 50%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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
| Detected | 28       | 77     | 65.12%  |
| Works    | 13       | 31     | 30.23%  |
| Malfunc  | 2        | 2      | 4.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 22       | 40.74%  |
| AMD                         | 16       | 29.63%  |
| Samsung Electronics         | 4        | 7.41%   |
| SanDisk                     | 2        | 3.7%    |
| Transcend                   | 1        | 1.85%   |
| Seagate Technology          | 1        | 1.85%   |
| Phison Electronics          | 1        | 1.85%   |
| OCZ Technology Group        | 1        | 1.85%   |
| Nvidia                      | 1        | 1.85%   |
| Micron/Crucial Technology   | 1        | 1.85%   |
| Micron Technology           | 1        | 1.85%   |
| Marvell Technology Group    | 1        | 1.85%   |
| Kingston Technology Company | 1        | 1.85%   |
| JMicron Technology          | 1        | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 11.94%  |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 4.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 2.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.99%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 2.99%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 2.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 2.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.99%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 2.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 2.99%   |
| AMD FCH IDE Controller                                                                  | 2        | 2.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.99%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)             | 1        | 1.49%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                               | 1        | 1.49%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1        | 1.49%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 1        | 1.49%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 1.49%   |
| Samsung NVMe SSD Controller 172X                                                        | 1        | 1.49%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 1        | 1.49%   |
| OCZ Group RD400/400A SSD                                                                | 1        | 1.49%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.49%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 1.49%   |
| Micron 2300 NVMe SSD [Santana]                                                          | 1        | 1.49%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 1.49%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 1        | 1.49%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.49%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 1        | 1.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.49%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 1.49%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 1.49%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.49%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 1.49%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 1.49%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 1        | 1.49%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 33       | 58.93%  |
| NVMe | 12       | 21.43%  |
| IDE  | 10       | 17.86%  |
| RAID | 1        | 1.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 22       | 56.41%  |
| AMD    | 17       | 43.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-4590T CPU @ 2.00GHz               | 2        | 5.13%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 5.13%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 2        | 5.13%   |
| Intel Xeon CPU X5492 @ 3.40GHz                  | 1        | 2.56%   |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 1        | 2.56%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz            | 1        | 2.56%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz             | 1        | 2.56%   |
| Intel Pentium CPU G620 @ 2.60GHz                | 1        | 2.56%   |
| Intel Core i7-5820K CPU @ 3.30GHz               | 1        | 2.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 2.56%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 2.56%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 2.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1        | 2.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 2.56%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 2.56%   |
| Intel Core i5-3470T CPU @ 2.90GHz               | 1        | 2.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 2.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 2.56%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1        | 2.56%   |
| Intel Core i3-3225 CPU @ 3.30GHz                | 1        | 2.56%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 2.56%   |
| Intel Atom x5-Z8330 CPU @ 1.44GHz               | 1        | 2.56%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz          | 1        | 2.56%   |
| AMD Ryzen 9 7900X 12-Core Processor             | 1        | 2.56%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 2.56%   |
| AMD Ryzen 5 5600 6-Core Processor               | 1        | 2.56%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 2.56%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1        | 2.56%   |
| AMD Phenom II X4 965 Processor                  | 1        | 2.56%   |
| AMD FX-8150 Eight-Core Processor                | 1        | 2.56%   |
| AMD Athlon X4 845 Quad Core Processor           | 1        | 2.56%   |
| AMD Athlon II X3 445 Processor                  | 1        | 2.56%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 1        | 2.56%   |
| AMD A4-6300 APU with Radeon HD Graphics         | 1        | 2.56%   |
| AMD A4-4000 APU with Radeon HD Graphics         | 1        | 2.56%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 9        | 23.08%  |
| AMD Ryzen 5       | 6        | 15.38%  |
| Intel Xeon        | 4        | 10.26%  |
| Intel Core i7     | 4        | 10.26%  |
| AMD Ryzen 9       | 2        | 5.13%   |
| AMD A4            | 2        | 5.13%   |
| Other             | 1        | 2.56%   |
| Intel Pentium     | 1        | 2.56%   |
| Intel Core i3     | 1        | 2.56%   |
| Intel Core 2 Quad | 1        | 2.56%   |
| Intel Atom        | 1        | 2.56%   |
| AMD Ryzen 3       | 1        | 2.56%   |
| AMD Phenom II X4  | 1        | 2.56%   |
| AMD FX            | 1        | 2.56%   |
| AMD Athlon X4     | 1        | 2.56%   |
| AMD Athlon II X3  | 1        | 2.56%   |
| AMD Athlon        | 1        | 2.56%   |
| AMD A10           | 1        | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 17       | 43.59%  |
| 6      | 8        | 20.51%  |
| 2      | 6        | 15.38%  |
| 12     | 2        | 5.13%   |
| 8      | 2        | 5.13%   |
| 1      | 2        | 5.13%   |
| 16     | 1        | 2.56%   |
| 3      | 1        | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 37       | 94.87%  |
| 2      | 2        | 5.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 25       | 64.1%   |
| 1      | 14       | 35.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 39       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 63.41%  |
| 0x306a9    | 3        | 7.32%   |
| 0x406f1    | 2        | 4.88%   |
| 0xa0671    | 1        | 2.44%   |
| 0x506e3    | 1        | 2.44%   |
| 0x406c4    | 1        | 2.44%   |
| 0x306c3    | 1        | 2.44%   |
| 0x10677    | 1        | 2.44%   |
| 0x0a50000c | 1        | 2.44%   |
| 0x0a201205 | 1        | 2.44%   |
| 0x08108109 | 1        | 2.44%   |
| 0x08108102 | 1        | 2.44%   |
| 0x06001119 | 1        | 2.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 5        | 12.82%  |
| Zen 3       | 4        | 10.26%  |
| Haswell     | 4        | 10.26%  |
| SandyBridge | 3        | 7.69%   |
| IvyBridge   | 3        | 7.69%   |
| Skylake     | 2        | 5.13%   |
| Piledriver  | 2        | 5.13%   |
| Penryn      | 2        | 5.13%   |
| K10         | 2        | 5.13%   |
| Broadwell   | 2        | 5.13%   |
| Westmere    | 1        | 2.56%   |
| Steamroller | 1        | 2.56%   |
| Silvermont  | 1        | 2.56%   |
| Nehalem     | 1        | 2.56%   |
| KabyLake    | 1        | 2.56%   |
| Icelake     | 1        | 2.56%   |
| Excavator   | 1        | 2.56%   |
| CometLake   | 1        | 2.56%   |
| Bulldozer   | 1        | 2.56%   |
| Unknown     | 1        | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 15       | 35.71%  |
| AMD    | 15       | 35.71%  |
| Intel  | 12       | 28.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 9.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 7.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 4.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 4.76%   |
| Intel HD Graphics 530                                                                    | 2        | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 4.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 4.76%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 4.76%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 2.38%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 2.38%   |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 2.38%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 2.38%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 2.38%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 2.38%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1        | 2.38%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 2.38%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1        | 2.38%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 2.38%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1        | 2.38%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 2.38%   |
| Nvidia AD102 [GeForce RTX 4090]                                                          | 1        | 2.38%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 2.38%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.38%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 2.38%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                                 | 1        | 2.38%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1        | 2.38%   |
| AMD Juniper PRO [Radeon HD 5750]                                                         | 1        | 2.38%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 2.38%   |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 2.38%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 14       | 35.9%   |
| 1 x AMD      | 14       | 35.9%   |
| 1 x Intel    | 10       | 25.64%  |
| AMD + Nvidia | 1        | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 30       | 75%     |
| Proprietary | 9        | 22.5%   |
| Unknown     | 1        | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 64.1%   |
| 3.01-4.0   | 4        | 10.26%  |
| 7.01-8.0   | 3        | 7.69%   |
| 1.01-2.0   | 3        | 7.69%   |
| 0.01-0.5   | 2        | 5.13%   |
| 16.01-24.0 | 1        | 2.56%   |
| 0.51-1.0   | 1        | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 34.21%  |
| AOC                  | 4        | 10.53%  |
| Hewlett-Packard      | 3        | 7.89%   |
| Goldstar             | 3        | 7.89%   |
| SANYO                | 2        | 5.26%   |
| Philips              | 2        | 5.26%   |
| Fujitsu Siemens      | 2        | 5.26%   |
| Vizio                | 1        | 2.63%   |
| Unknown (XXX)        | 1        | 2.63%   |
| Sony                 | 1        | 2.63%   |
| Panasonic            | 1        | 2.63%   |
| LG Electronics       | 1        | 2.63%   |
| HKC                  | 1        | 2.63%   |
| Dell                 | 1        | 2.63%   |
| BenQ                 | 1        | 2.63%   |
| Ancor Communications | 1        | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio E320-B1 VIZ0095 1360x768 697x392mm 31.5-inch                    | 1        | 2.44%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 2.44%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 2.44%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1        | 2.44%   |
| SANYO LCD SAN0A12 1920x540                                            | 1        | 2.44%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch  | 1        | 2.44%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch   | 1        | 2.44%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch     | 1        | 2.44%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 2.44%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch     | 1        | 2.44%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1        | 2.44%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 2.44%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 2.44%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch     | 1        | 2.44%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 2.44%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch              | 1        | 2.44%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch               | 1        | 2.44%   |
| Philips 273EL PHLC07C 1920x1080 600x340mm 27.2-inch                   | 1        | 2.44%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                               | 1        | 2.44%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                      | 1        | 2.44%   |
| HKC '' HKC2160 1920x1080 360x270mm 17.7-inch                          | 1        | 2.44%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 1        | 2.44%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1        | 2.44%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 2.44%   |
| Goldstar W2343 GSM5701 1920x1080 510x290mm 23.1-inch                  | 1        | 2.44%   |
| Goldstar W2052 GSM4E89 1680x1050 474x296mm 22.0-inch                  | 1        | 2.44%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 1        | 2.44%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch               | 1        | 2.44%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 1        | 2.44%   |
| Fujitsu Siemens B27T-7 Pro FUS0891 1920x1080 598x336mm 27.0-inch      | 1        | 2.44%   |
| Dell LCD Monitor 1704FPV 1280x1024                                    | 1        | 2.44%   |
| BenQ GW2750H BNQ78C3 1920x1080 598x336mm 27.0-inch                    | 1        | 2.44%   |
| AOC U34G2G4R3 AOC3402 3440x1440 797x334mm 34.0-inch                   | 1        | 2.44%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 2.44%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 1        | 2.44%   |
| AOC 2218 AOC2218 1680x1050 526x296mm 23.8-inch                        | 1        | 2.44%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 1        | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 20       | 52.63%  |
| 3840x2160 (4K)     | 3        | 7.89%   |
| 1920x540           | 3        | 7.89%   |
| 3440x1440          | 2        | 5.26%   |
| 1920x1200 (WUXGA)  | 2        | 5.26%   |
| 1680x1050 (WSXGA+) | 2        | 5.26%   |
| 1366x768 (WXGA)    | 2        | 5.26%   |
| 2560x1440 (QHD)    | 1        | 2.63%   |
| 2560x1080          | 1        | 2.63%   |
| 1600x900 (HD+)     | 1        | 2.63%   |
| 1280x1024 (SXGA)   | 1        | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 8        | 20%     |
| 23      | 6        | 15%     |
| 27      | 4        | 10%     |
| 34      | 3        | 7.5%    |
| 31      | 3        | 7.5%    |
| 21      | 3        | 7.5%    |
| Unknown | 3        | 7.5%    |
| 54      | 2        | 5%      |
| 72      | 1        | 2.5%    |
| 40      | 1        | 2.5%    |
| 33      | 1        | 2.5%    |
| 28      | 1        | 2.5%    |
| 22      | 1        | 2.5%    |
| 20      | 1        | 2.5%    |
| 18      | 1        | 2.5%    |
| 17      | 1        | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 42.11%  |
| 401-500     | 6        | 15.79%  |
| 701-800     | 4        | 10.53%  |
| 601-700     | 4        | 10.53%  |
| Unknown     | 3        | 7.89%   |
| 1001-1500   | 2        | 5.26%   |
| 801-900     | 1        | 2.63%   |
| 351-400     | 1        | 2.63%   |
| 1501-2000   | 1        | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 26       | 70.27%  |
| 16/10   | 4        | 10.81%  |
| 21/9    | 3        | 8.11%   |
| Unknown | 2        | 5.41%   |
| 4/3     | 1        | 2.7%    |
| 32/9    | 1        | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 35.14%  |
| 351-500        | 8        | 21.62%  |
| 301-350        | 4        | 10.81%  |
| More than 1000 | 3        | 8.11%   |
| Unknown        | 3        | 8.11%   |
| 251-300        | 2        | 5.41%   |
| 151-200        | 2        | 5.41%   |
| 141-150        | 1        | 2.7%    |
| 501-1000       | 1        | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 64.86%  |
| 1-50    | 4        | 10.81%  |
| 121-160 | 3        | 8.11%   |
| 101-120 | 3        | 8.11%   |
| Unknown | 3        | 8.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 87.18%  |
| 2     | 5        | 12.82%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 21       | 40.38%  |
| Realtek Semiconductor | 20       | 38.46%  |
| Qualcomm Atheros      | 2        | 3.85%   |
| Broadcom              | 2        | 3.85%   |
| T & A Mobile Phones   | 1        | 1.92%   |
| Ralink Technology     | 1        | 1.92%   |
| Nvidia                | 1        | 1.92%   |
| Microsoft             | 1        | 1.92%   |
| MediaTek              | 1        | 1.92%   |
| Broadcom Limited      | 1        | 1.92%   |
| ASUSTek Computer      | 1        | 1.92%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16       | 26.67%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 5%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 3.33%   |
| Intel I211 Gigabit Network Connection                             | 2        | 3.33%   |
| Intel Ethernet Controller I225-V                                  | 2        | 3.33%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 3.33%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 3.33%   |
| T & A Mobile Phones TCL 20E                                       | 1        | 1.67%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 1.67%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 1.67%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 1.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 1.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.67%   |
| Realtek 802.11ac NIC                                              | 1        | 1.67%   |
| Ralink RT3072 Wireless Adapter                                    | 1        | 1.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.67%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.67%   |
| Microsoft Wireless XBox Controller Dongle                         | 1        | 1.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.67%   |
| Intel Wireless-AC 9260                                            | 1        | 1.67%   |
| Intel Wireless 7265                                               | 1        | 1.67%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.67%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.67%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.67%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.67%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.67%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.67%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 1.67%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 1        | 1.67%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]         | 1        | 1.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 42.11%  |
| Realtek Semiconductor | 6        | 31.58%  |
| Ralink Technology     | 1        | 5.26%   |
| Microsoft             | 1        | 5.26%   |
| MediaTek              | 1        | 5.26%   |
| Broadcom              | 1        | 5.26%   |
| ASUSTek Computer      | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]             | 3        | 15.79%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                       | 2        | 10.53%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter          | 1        | 5.26%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter      | 1        | 5.26%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter        | 1        | 5.26%   |
| Realtek RTL8188EE Wireless Network Adapter                   | 1        | 5.26%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                      | 1        | 5.26%   |
| Realtek 802.11ac NIC                                         | 1        | 5.26%   |
| Ralink RT3072 Wireless Adapter                               | 1        | 5.26%   |
| Microsoft Wireless XBox Controller Dongle                    | 1        | 5.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                      | 1        | 5.26%   |
| Intel Wireless-AC 9260                                       | 1        | 5.26%   |
| Intel Wireless 7265                                          | 1        | 5.26%   |
| Intel Wi-Fi 6 AX200                                          | 1        | 5.26%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter | 1        | 5.26%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]    | 1        | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 43.59%  |
| Intel                 | 16       | 41.03%  |
| Qualcomm Atheros      | 2        | 5.13%   |
| T & A Mobile Phones   | 1        | 2.56%   |
| Nvidia                | 1        | 2.56%   |
| Broadcom Limited      | 1        | 2.56%   |
| Broadcom              | 1        | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16       | 39.02%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 7.32%   |
| Intel I211 Gigabit Network Connection                             | 2        | 4.88%   |
| Intel Ethernet Controller I225-V                                  | 2        | 4.88%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 4.88%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 4.88%   |
| T & A Mobile Phones TCL 20E                                       | 1        | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.44%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.44%   |
| Intel I210 Gigabit Network Connection                             | 1        | 2.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.44%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.44%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.44%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 2.44%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 38       | 66.67%  |
| WiFi     | 19       | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 75%     |
| WiFi     | 10       | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 69.23%  |
| 2     | 12       | 30.77%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 82.05%  |
| Yes  | 7        | 17.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 7        | 63.64%  |
| Cambridge Silicon Radio | 2        | 18.18%  |
| MediaTek                | 1        | 9.09%   |
| Broadcom                | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 18.18%  |
| Intel AX210 Bluetooth                               | 2        | 18.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 18.18%  |
| MediaTek Wireless_Device                            | 1        | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 9.09%   |
| Intel Bluetooth wireless interface                  | 1        | 9.09%   |
| Intel AX200 Bluetooth                               | 1        | 9.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 20       | 32.26%  |
| AMD                     | 20       | 32.26%  |
| Nvidia                  | 15       | 24.19%  |
| Texas Instruments       | 1        | 1.61%   |
| Shure                   | 1        | 1.61%   |
| Realtek Semiconductor   | 1        | 1.61%   |
| Logitech                | 1        | 1.61%   |
| DSEA A/S                | 1        | 1.61%   |
| ClearOne Communications | 1        | 1.61%   |
| ASUSTek Computer        | 1        | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 8%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 5.33%   |
| AMD FCH Azalia Controller                                                  | 4        | 5.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 4%      |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 4%      |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.67%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 2.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 2.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 2.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.67%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.33%   |
| Shure MV88+                                                                | 1        | 1.33%   |
| Realtek Semiconductor USB Audio                                            | 1        | 1.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.33%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.33%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.33%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.33%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.33%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1.33%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 1.33%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.33%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 1.33%   |
| Logitech Blue Microphones                                                  | 1        | 1.33%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.33%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 1.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.33%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.33%   |
| DSEA A/S BTD-800                                                           | 1        | 1.33%   |
| ClearOne Communications Chat 150                                           | 1        | 1.33%   |
| ASUSTek Computer USB Audio                                                 | 1        | 1.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 20%     |
| Crucial             | 4        | 20%     |
| Samsung Electronics | 3        | 15%     |
| SK hynix            | 2        | 10%     |
| Micron Technology   | 2        | 10%     |
| Corsair             | 2        | 10%     |
| Transcend           | 1        | 5%      |
| Elpida              | 1        | 5%      |
| A-DATA Technology   | 1        | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 9.09%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s     | 1        | 4.55%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s             | 1        | 4.55%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 4.55%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s              | 1        | 4.55%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s   | 1        | 4.55%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s    | 1        | 4.55%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 1        | 4.55%   |
| Micron RAM 16JTF51264AZ-1G4D1 4GB DIMM DDR3 1333MT/s   | 1        | 4.55%   |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s      | 1        | 4.55%   |
| Kingston RAM 9905403-011.A02LF 2GB DIMM DDR3 1333MT/s  | 1        | 4.55%   |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2GB DIMM DDR3 1333MT/s    | 1        | 4.55%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s | 1        | 4.55%   |
| Crucial RAM CT8G4DFD8213.C16FAD 8GB DIMM DDR4 2133MT/s | 1        | 4.55%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s  | 1        | 4.55%   |
| Crucial RAM BLS8G4D26BFSBK.8FD 8GB DIMM DDR4 2933MT/s  | 1        | 4.55%   |
| Crucial RAM BL8G26C16U4B.8FD 8GB DIMM DDR4 2667MT/s    | 1        | 4.55%   |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s    | 1        | 4.55%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s    | 1        | 4.55%   |
| Corsair RAM CMP8GX3M2A1600C9 4GB DIMM DDR3 1333MT/s    | 1        | 4.55%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 1        | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 9        | 56.25%  |
| DDR3  | 6        | 37.5%   |
| SDRAM | 1        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 13       | 86.67%  |
| SODIMM | 2        | 13.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 41.18%  |
| 4096  | 4        | 23.53%  |
| 16384 | 3        | 17.65%  |
| 2048  | 2        | 11.76%  |
| 32768 | 1        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 26.32%  |
| 1333  | 3        | 15.79%  |
| 3200  | 2        | 10.53%  |
| 2667  | 2        | 10.53%  |
| 2400  | 2        | 10.53%  |
| 2133  | 2        | 10.53%  |
| 3600  | 1        | 5.26%   |
| 2933  | 1        | 5.26%   |
| 1066  | 1        | 5.26%   |

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
| Logitech                      | 2        | 25%     |
| WaveRider Communications      | 1        | 12.5%   |
| ValueHD                       | 1        | 12.5%   |
| Sunplus Innovation Technology | 1        | 12.5%   |
| Samsung Electronics           | 1        | 12.5%   |
| Microdia                      | 1        | 12.5%   |
| Generalplus Technology        | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920              | 2        | 25%     |
| WaveRider USB 2.0 Camera                 | 1        | 12.5%   |
| ValueHD Konftel Cam20                    | 1        | 12.5%   |
| Sunplus FHD Camera Microphone            | 1        | 12.5%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1        | 12.5%   |
| Microdia Camera                          | 1        | 12.5%   |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 12.5%   |

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
| 0     | 32       | 80%     |
| 1     | 5        | 12.5%   |
| 2     | 2        | 5%      |
| 4     | 1        | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 3        | 27.27%  |
| Net/wireless     | 3        | 27.27%  |
| Sound            | 2        | 18.18%  |
| Net/ethernet     | 1        | 9.09%   |
| Graphics card    | 1        | 9.09%   |
| Bluetooth        | 1        | 9.09%   |

