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

Total: 46

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-52-generic      | 4        | 10.53%  |
| 5.15.0-57-generic      | 3        | 7.89%   |
| 5.15.0-46-generic      | 3        | 7.89%   |
| 5.15.0-43-generic      | 3        | 7.89%   |
| 5.15.0-30-generic      | 3        | 7.89%   |
| 5.19.0-40-generic      | 2        | 5.26%   |
| 5.15.0-33-generic      | 2        | 5.26%   |
| 5.15.0-27-generic      | 2        | 5.26%   |
| 5.15.0-25-generic      | 2        | 5.26%   |
| 6.2.0-33-generic       | 1        | 2.63%   |
| 5.19.0-46-generic      | 1        | 2.63%   |
| 5.19.0-45-generic      | 1        | 2.63%   |
| 5.17.2-051702-generic  | 1        | 2.63%   |
| 5.15.92-051592-generic | 1        | 2.63%   |
| 5.15.0-84-generic      | 1        | 2.63%   |
| 5.15.0-73-generic      | 1        | 2.63%   |
| 5.15.0-71-generic      | 1        | 2.63%   |
| 5.15.0-56-generic      | 1        | 2.63%   |
| 5.15.0-50-generic      | 1        | 2.63%   |
| 5.15.0-48-generic      | 1        | 2.63%   |
| 5.15.0-47-generic      | 1        | 2.63%   |
| 5.15.0-41-generic      | 1        | 2.63%   |
| 5.13.0-44-generic      | 1        | 2.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 28       | 77.78%  |
| 5.19.0  | 4        | 11.11%  |
| 6.2.0   | 1        | 2.78%   |
| 5.17.2  | 1        | 2.78%   |
| 5.15.92 | 1        | 2.78%   |
| 5.13.0  | 1        | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 29       | 80.56%  |
| 5.19    | 4        | 11.11%  |
| 6.2     | 1        | 2.78%   |
| 5.17    | 1        | 2.78%   |
| 5.13    | 1        | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 35       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 35       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 35       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 26       | 74.29%  |
| Unknown | 8        | 22.86%  |
| GDM     | 1        | 2.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 15       | 42.86%  |
| de_DE | 6        | 17.14%  |
| pt_BR | 3        | 8.57%   |
| fr_FR | 2        | 5.71%   |
| es_ES | 2        | 5.71%   |
| en_GB | 2        | 5.71%   |
| es_MX | 1        | 2.86%   |
| en_ZA | 1        | 2.86%   |
| en_CA | 1        | 2.86%   |
| en_AU | 1        | 2.86%   |
| el_GR | 1        | 2.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 25       | 69.44%  |
| EFI  | 11       | 30.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 28       | 80%     |
| Overlay | 3        | 8.57%   |
| Tmpfs   | 2        | 5.71%   |
| Zfs     | 1        | 2.86%   |
| Btrfs   | 1        | 2.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 21       | 58.33%  |
| Unknown | 15       | 41.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 80%     |
| Yes       | 7        | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 60%     |
| Yes       | 14       | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 10       | 28.57%  |
| MSI                 | 5        | 14.29%  |
| ASUSTek Computer    | 4        | 11.43%  |
| Intel               | 3        | 8.57%   |
| Hewlett-Packard     | 3        | 8.57%   |
| Fujitsu             | 3        | 8.57%   |
| ASRock              | 3        | 8.57%   |
| Dell                | 2        | 5.71%   |
| Lenovo              | 1        | 2.86%   |
| Biostar             | 1        | 2.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| MSI MS-7C95                        | 1        | 2.86%   |
| MSI MS-7C51                        | 1        | 2.86%   |
| MSI MS-7B86                        | 1        | 2.86%   |
| MSI MS-7A32                        | 1        | 2.86%   |
| MSI MS-7885                        | 1        | 2.86%   |
| Lenovo ThinkStation C20 4263BA7    | 1        | 2.86%   |
| Intel STK1A32SC                    | 1        | 2.86%   |
| Intel H61                          | 1        | 2.86%   |
| Intel DP55WB AAE64798-206          | 1        | 2.86%   |
| HP Z440 Workstation                | 1        | 2.86%   |
| HP EliteDesk 800 G1 DM             | 1        | 2.86%   |
| HP 750-417c                        | 1        | 2.86%   |
| Gigabyte X570S AORUS PRO AX        | 1        | 2.86%   |
| Gigabyte M68MT-S2                  | 1        | 2.86%   |
| Gigabyte H410M S2H V3              | 1        | 2.86%   |
| Gigabyte H310MHD2                  | 1        | 2.86%   |
| Gigabyte GA-890GPA-UD3H            | 1        | 2.86%   |
| Gigabyte F2A78M-HD2                | 1        | 2.86%   |
| Gigabyte B75M-D3P                  | 1        | 2.86%   |
| Gigabyte B75M-D3H                  | 1        | 2.86%   |
| Gigabyte B550 AORUS ELITE AX V2    | 1        | 2.86%   |
| Gigabyte B450 I AORUS PRO WIFI     | 1        | 2.86%   |
| Fujitsu ESPRIMO Q920               | 1        | 2.86%   |
| Fujitsu ESPRIMO Q910               | 1        | 2.86%   |
| Fujitsu D3348-B2                   | 1        | 2.86%   |
| Dell Precision WorkStation T7400   | 1        | 2.86%   |
| Dell OptiPlex 780                  | 1        | 2.86%   |
| Biostar A960D+V3                   | 1        | 2.86%   |
| ASUS ROG STRIX X670E-E GAMING WIFI | 1        | 2.86%   |
| ASUS PRIME B560M-A                 | 1        | 2.86%   |
| ASUS All Series                    | 1        | 2.86%   |
| ASUS A88X-PRO                      | 1        | 2.86%   |
| ASRock FM2A88X Extreme4+           | 1        | 2.86%   |
| ASRock B450M Steel Legend          | 1        | 2.86%   |
| ASRock A300M-STX                   | 1        | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Fujitsu ESPRIMO         | 2        | 5.71%   |
| MSI MS-7C95             | 1        | 2.86%   |
| MSI MS-7C51             | 1        | 2.86%   |
| MSI MS-7B86             | 1        | 2.86%   |
| MSI MS-7A32             | 1        | 2.86%   |
| MSI MS-7885             | 1        | 2.86%   |
| Lenovo ThinkStation     | 1        | 2.86%   |
| Intel STK1A32SC         | 1        | 2.86%   |
| Intel H61               | 1        | 2.86%   |
| Intel DP55WB            | 1        | 2.86%   |
| HP Z440                 | 1        | 2.86%   |
| HP EliteDesk            | 1        | 2.86%   |
| HP 750-417c             | 1        | 2.86%   |
| Gigabyte X570S          | 1        | 2.86%   |
| Gigabyte M68MT-S2       | 1        | 2.86%   |
| Gigabyte H410M          | 1        | 2.86%   |
| Gigabyte H310MHD2       | 1        | 2.86%   |
| Gigabyte GA-890GPA-UD3H | 1        | 2.86%   |
| Gigabyte F2A78M-HD2     | 1        | 2.86%   |
| Gigabyte B75M-D3P       | 1        | 2.86%   |
| Gigabyte B75M-D3H       | 1        | 2.86%   |
| Gigabyte B550           | 1        | 2.86%   |
| Gigabyte B450           | 1        | 2.86%   |
| Fujitsu D3348-B2        | 1        | 2.86%   |
| Dell Precision          | 1        | 2.86%   |
| Dell OptiPlex           | 1        | 2.86%   |
| Biostar A960D+V3        | 1        | 2.86%   |
| ASUS ROG                | 1        | 2.86%   |
| ASUS PRIME              | 1        | 2.86%   |
| ASUS All                | 1        | 2.86%   |
| ASUS A88X-PRO           | 1        | 2.86%   |
| ASRock FM2A88X          | 1        | 2.86%   |
| ASRock B450M            | 1        | 2.86%   |
| ASRock A300M-STX        | 1        | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 7        | 20%     |
| 2018 | 4        | 11.43%  |
| 2021 | 3        | 8.57%   |
| 2019 | 3        | 8.57%   |
| 2017 | 3        | 8.57%   |
| 2010 | 3        | 8.57%   |
| 2020 | 2        | 5.71%   |
| 2016 | 2        | 5.71%   |
| 2012 | 2        | 5.71%   |
| 2022 | 1        | 2.86%   |
| 2015 | 1        | 2.86%   |
| 2013 | 1        | 2.86%   |
| 2011 | 1        | 2.86%   |
| 2009 | 1        | 2.86%   |
| 2008 | 1        | 2.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 35       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 35       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 35       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 12       | 34.29%  |
| 8.01-16.0       | 9        | 25.71%  |
| 4.01-8.0        | 6        | 17.14%  |
| 32.01-64.0      | 2        | 5.71%   |
| 24.01-32.0      | 2        | 5.71%   |
| 64.01-256.0     | 2        | 5.71%   |
| More than 256.0 | 1        | 2.86%   |
| 1.01-2.0        | 1        | 2.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 13       | 34.21%  |
| 2.01-3.0   | 11       | 28.95%  |
| 4.01-8.0   | 7        | 18.42%  |
| 3.01-4.0   | 4        | 10.53%  |
| 8.01-16.0  | 2        | 5.26%   |
| 16.01-24.0 | 1        | 2.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 31.43%  |
| 2      | 10       | 28.57%  |
| 4      | 5        | 14.29%  |
| 3      | 5        | 14.29%  |
| 6      | 2        | 5.71%   |
| 8      | 1        | 2.86%   |
| 7      | 1        | 2.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 57.14%  |
| Yes       | 15       | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 97.14%  |
| No        | 1        | 2.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 18       | 51.43%  |
| No        | 17       | 48.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 68.57%  |
| Yes       | 11       | 31.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 9        | 25.71%  |
| Germany      | 5        | 14.29%  |
| Brazil       | 4        | 11.43%  |
| UK           | 2        | 5.71%   |
| Switzerland  | 2        | 5.71%   |
| France       | 2        | 5.71%   |
| Spain        | 1        | 2.86%   |
| South Africa | 1        | 2.86%   |
| Slovenia     | 1        | 2.86%   |
| Romania      | 1        | 2.86%   |
| Norway       | 1        | 2.86%   |
| Mexico       | 1        | 2.86%   |
| Greece       | 1        | 2.86%   |
| Croatia      | 1        | 2.86%   |
| Austria      | 1        | 2.86%   |
| Australia    | 1        | 2.86%   |
| Argentina    | 1        | 2.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milwaukee             | 2        | 5.41%   |
| Brasília             | 2        | 5.41%   |
| Zurich                | 1        | 2.7%    |
| Walled Lake           | 1        | 2.7%    |
| Trondheim             | 1        | 2.7%    |
| Tocantins             | 1        | 2.7%    |
| Tann                  | 1        | 2.7%    |
| Seattle               | 1        | 2.7%    |
| San Luis Potosí City | 1        | 2.7%    |
| San Diego             | 1        | 2.7%    |
| Rueil-Malmaison       | 1        | 2.7%    |
| Pula                  | 1        | 2.7%    |
| Pine Island           | 1        | 2.7%    |
| New York              | 1        | 2.7%    |
| Maribor               | 1        | 2.7%    |
| Manaus                | 1        | 2.7%    |
| Madrid                | 1        | 2.7%    |
| London                | 1        | 2.7%    |
| Limay                 | 1        | 2.7%    |
| Kittsee               | 1        | 2.7%    |
| Kirkcaldy             | 1        | 2.7%    |
| Houston               | 1        | 2.7%    |
| Hamburg               | 1        | 2.7%    |
| Ennepetal             | 1        | 2.7%    |
| Dortmund              | 1        | 2.7%    |
| Delbrueck             | 1        | 2.7%    |
| Colon                 | 1        | 2.7%    |
| Caslano               | 1        | 2.7%    |
| Cape Town             | 1        | 2.7%    |
| Camp Hill             | 1        | 2.7%    |
| Brisbane              | 1        | 2.7%    |
| Bradenton             | 1        | 2.7%    |
| Berlin                | 1        | 2.7%    |
| Baia Mare             | 1        | 2.7%    |
| Athens                | 1        | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 15       | 23     | 20.83%  |
| WDC                       | 9        | 10     | 12.5%   |
| Samsung Electronics       | 8        | 28     | 11.11%  |
| SanDisk                   | 5        | 6      | 6.94%   |
| Crucial                   | 4        | 4      | 5.56%   |
| Toshiba                   | 3        | 3      | 4.17%   |
| Transcend                 | 2        | 2      | 2.78%   |
| OCZ                       | 2        | 2      | 2.78%   |
| Micron Technology         | 2        | 2      | 2.78%   |
| Kingston                  | 2        | 3      | 2.78%   |
| China                     | 2        | 2      | 2.78%   |
| A-DATA Technology         | 2        | 2      | 2.78%   |
| Zheino                    | 1        | 1      | 1.39%   |
| Unknown                   | 1        | 1      | 1.39%   |
| SPCC                      | 1        | 1      | 1.39%   |
| SK hynix                  | 1        | 1      | 1.39%   |
| PNY                       | 1        | 1      | 1.39%   |
| Phison                    | 1        | 1      | 1.39%   |
| Mushkin                   | 1        | 1      | 1.39%   |
| Micron/Crucial Technology | 1        | 1      | 1.39%   |
| MicroFrom                 | 1        | 1      | 1.39%   |
| Maxtor                    | 1        | 1      | 1.39%   |
| JMicron Technology        | 1        | 1      | 1.39%   |
| Intenso                   | 1        | 1      | 1.39%   |
| Intel                     | 1        | 1      | 1.39%   |
| HGST                      | 1        | 1      | 1.39%   |
| ASMT109x                  | 1        | 1      | 1.39%   |
| 4Life                     | 1        | 1      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 2        | 2.33%   |
| Seagate ST3500418AS 500GB          | 2        | 2.33%   |
| Seagate ST1000LM048-2E7172 1TB     | 2        | 2.33%   |
| SanDisk SDSSDA120G 120GB           | 2        | 2.33%   |
| Samsung SSD 870 EVO 250GB          | 2        | 2.33%   |
| Samsung SSD 850 PRO 256GB          | 2        | 2.33%   |
| Samsung SSD 840 EVO 250GB          | 2        | 2.33%   |
| Zheino CHN-25SATAC3-120 120GB SSD  | 1        | 1.16%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 1.16%   |
| WDC WD40PURZ-85TTDY0 4TB           | 1        | 1.16%   |
| WDC WD3200LPVX-22V0TT0 320GB       | 1        | 1.16%   |
| WDC WD1600AAJS-60WAA0 160GB        | 1        | 1.16%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 1.16%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1.16%   |
| WDC WD10EADS-00M2B0 1TB            | 1        | 1.16%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 1        | 1.16%   |
| Unknown SD/MMC/MS PRO 128GB        | 1        | 1.16%   |
| Transcend TS480GMTS820S 480GB SSD  | 1        | 1.16%   |
| Transcend TS128GMTE110S 128GB      | 1        | 1.16%   |
| Toshiba MD04ACA400 4TB             | 1        | 1.16%   |
| Toshiba HDWD240 4TB                | 1        | 1.16%   |
| Toshiba HDWD220 2TB                | 1        | 1.16%   |
| SPCC Solid State Disk 256GB        | 1        | 1.16%   |
| SK hynix SC210 2.5 7MM 128GB SSD   | 1        | 1.16%   |
| Seagate ST9500325AS 500GB          | 1        | 1.16%   |
| Seagate ST8000VN0022-2EL112 8TB    | 1        | 1.16%   |
| Seagate ST500LT012-1DG142 500GB    | 1        | 1.16%   |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 1.16%   |
| Seagate ST380815AS 80GB            | 1        | 1.16%   |
| Seagate ST3500413AS 500GB          | 1        | 1.16%   |
| Seagate ST3500412AS 500GB          | 1        | 1.16%   |
| Seagate ST3160815AS 160GB          | 1        | 1.16%   |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 1.16%   |
| Seagate ST2000DM006-2DM164 2TB     | 1        | 1.16%   |
| Seagate ST2000DM001-1ER164 2TB     | 1        | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB     | 1        | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1.16%   |
| Seagate ST1000LM014-1EJ164 1TB     | 1        | 1.16%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1.16%   |
| Seagate ST1000DM003-1SB10C 1TB     | 1        | 1.16%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 22     | 48.39%  |
| WDC                 | 8        | 9      | 25.81%  |
| Toshiba             | 3        | 3      | 9.68%   |
| Unknown             | 1        | 1      | 3.23%   |
| Samsung Electronics | 1        | 2      | 3.23%   |
| Maxtor              | 1        | 1      | 3.23%   |
| HGST                | 1        | 1      | 3.23%   |
| ASMT109x            | 1        | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 21     | 20.69%  |
| Crucial             | 4        | 4      | 13.79%  |
| SanDisk             | 2        | 2      | 6.9%    |
| China               | 2        | 2      | 6.9%    |
| A-DATA Technology   | 2        | 2      | 6.9%    |
| Zheino              | 1        | 1      | 3.45%   |
| WDC                 | 1        | 1      | 3.45%   |
| Transcend           | 1        | 1      | 3.45%   |
| SPCC                | 1        | 1      | 3.45%   |
| SK hynix            | 1        | 1      | 3.45%   |
| PNY                 | 1        | 1      | 3.45%   |
| OCZ                 | 1        | 1      | 3.45%   |
| Mushkin             | 1        | 1      | 3.45%   |
| Micron Technology   | 1        | 1      | 3.45%   |
| MicroFrom           | 1        | 1      | 3.45%   |
| Kingston            | 1        | 2      | 3.45%   |
| JMicron Technology  | 1        | 1      | 3.45%   |
| 4Life               | 1        | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 23       | 45     | 38.33%  |
| HDD     | 23       | 40     | 38.33%  |
| NVMe    | 12       | 16     | 20%     |
| MMC     | 1        | 1      | 1.67%   |
| Unknown | 1        | 1      | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 33       | 83     | 67.35%  |
| NVMe | 12       | 16     | 24.49%  |
| SAS  | 3        | 3      | 6.12%   |
| MMC  | 1        | 1      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 30       | 54     | 57.69%  |
| 0.51-1.0   | 12       | 18     | 23.08%  |
| 3.01-4.0   | 5        | 6      | 9.62%   |
| 1.01-2.0   | 4        | 5      | 7.69%   |
| 4.01-10.0  | 1        | 2      | 1.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 11       | 31.43%  |
| More than 3000 | 4        | 11.43%  |
| 251-500        | 4        | 11.43%  |
| 1001-2000      | 4        | 11.43%  |
| 1-20           | 4        | 11.43%  |
| 51-100         | 4        | 11.43%  |
| 2001-3000      | 2        | 5.71%   |
| 21-50          | 1        | 2.86%   |
| 501-1000       | 1        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 10       | 27.78%  |
| 21-50          | 9        | 25%     |
| 51-100         | 7        | 19.44%  |
| 101-250        | 4        | 11.11%  |
| 1001-2000      | 3        | 8.33%   |
| More than 3000 | 1        | 2.78%   |
| 251-500        | 1        | 2.78%   |
| 2001-3000      | 1        | 2.78%   |

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
| Detected | 26       | 73     | 66.67%  |
| Works    | 11       | 28     | 28.21%  |
| Malfunc  | 2        | 2      | 5.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 19       | 38%     |
| AMD                         | 15       | 30%     |
| Samsung Electronics         | 4        | 8%      |
| SanDisk                     | 2        | 4%      |
| Transcend                   | 1        | 2%      |
| Seagate Technology          | 1        | 2%      |
| Phison Electronics          | 1        | 2%      |
| OCZ Technology Group        | 1        | 2%      |
| Nvidia                      | 1        | 2%      |
| Micron/Crucial Technology   | 1        | 2%      |
| Micron Technology           | 1        | 2%      |
| Marvell Technology Group    | 1        | 2%      |
| Kingston Technology Company | 1        | 2%      |
| JMicron Technology          | 1        | 2%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 11.29%  |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 4.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 3.23%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 3.23%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 3.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 3.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 3.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 3.23%   |
| AMD FCH IDE Controller                                                         | 2        | 3.23%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 3.23%   |
| Transcend NVMe PCIe SSD 120S/112S (DRAM-less)                                  | 1        | 1.61%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                      | 1        | 1.61%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 1.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 1.61%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.61%   |
| Samsung NVMe SSD Controller 172X                                               | 1        | 1.61%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 1.61%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 1.61%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.61%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 1.61%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 1        | 1.61%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.61%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 1.61%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 1.61%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1        | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.61%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                     | 1        | 1.61%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 1.61%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 1.61%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.61%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 1.61%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                     | 1        | 1.61%   |
| Intel 631xESB/632xESB IDE Controller                                           | 1        | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 1.61%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1        | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 30       | 57.69%  |
| NVMe | 12       | 23.08%  |
| IDE  | 9        | 17.31%  |
| RAID | 1        | 1.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 54.29%  |
| AMD    | 16       | 45.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-4590T CPU @ 2.00GHz               | 2        | 5.71%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 5.71%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 2        | 5.71%   |
| Intel Xeon CPU X5492 @ 3.40GHz                  | 1        | 2.86%   |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 1        | 2.86%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz            | 1        | 2.86%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz             | 1        | 2.86%   |
| Intel Core i7-5820K CPU @ 3.30GHz               | 1        | 2.86%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 2.86%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 2.86%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 2.86%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1        | 2.86%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 2.86%   |
| Intel Core i5-3470T CPU @ 2.90GHz               | 1        | 2.86%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 2.86%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1        | 2.86%   |
| Intel Core i3-3225 CPU @ 3.30GHz                | 1        | 2.86%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 2.86%   |
| Intel Atom x5-Z8330 CPU @ 1.44GHz               | 1        | 2.86%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz          | 1        | 2.86%   |
| AMD Ryzen 9 7900X 12-Core Processor             | 1        | 2.86%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 2.86%   |
| AMD Ryzen 5 5600 6-Core Processor               | 1        | 2.86%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 2.86%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1        | 2.86%   |
| AMD Phenom II X4 965 Processor                  | 1        | 2.86%   |
| AMD FX-8150 Eight-Core Processor                | 1        | 2.86%   |
| AMD Athlon X4 845 Quad Core Processor           | 1        | 2.86%   |
| AMD Athlon II X3 445 Processor                  | 1        | 2.86%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 1        | 2.86%   |
| AMD A4-4000 APU with Radeon HD Graphics         | 1        | 2.86%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 7        | 20%     |
| AMD Ryzen 5       | 6        | 17.14%  |
| Intel Xeon        | 4        | 11.43%  |
| Intel Core i7     | 4        | 11.43%  |
| AMD Ryzen 9       | 2        | 5.71%   |
| Other             | 1        | 2.86%   |
| Intel Core i3     | 1        | 2.86%   |
| Intel Core 2 Quad | 1        | 2.86%   |
| Intel Atom        | 1        | 2.86%   |
| AMD Ryzen 3       | 1        | 2.86%   |
| AMD Phenom II X4  | 1        | 2.86%   |
| AMD FX            | 1        | 2.86%   |
| AMD Athlon X4     | 1        | 2.86%   |
| AMD Athlon II X3  | 1        | 2.86%   |
| AMD Athlon        | 1        | 2.86%   |
| AMD A4            | 1        | 2.86%   |
| AMD A10           | 1        | 2.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 15       | 42.86%  |
| 6      | 8        | 22.86%  |
| 2      | 5        | 14.29%  |
| 12     | 2        | 5.71%   |
| 8      | 2        | 5.71%   |
| 16     | 1        | 2.86%   |
| 3      | 1        | 2.86%   |
| 1      | 1        | 2.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 33       | 94.29%  |
| 2      | 2        | 5.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 24       | 68.57%  |
| 1      | 11       | 31.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 35       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 62.16%  |
| 0x306a9    | 3        | 8.11%   |
| 0x406f1    | 2        | 5.41%   |
| 0xa0671    | 1        | 2.7%    |
| 0x406c4    | 1        | 2.7%    |
| 0x306c3    | 1        | 2.7%    |
| 0x10677    | 1        | 2.7%    |
| 0x0a50000c | 1        | 2.7%    |
| 0x0a201205 | 1        | 2.7%    |
| 0x08108109 | 1        | 2.7%    |
| 0x08108102 | 1        | 2.7%    |
| 0x06001119 | 1        | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 5        | 14.29%  |
| Zen 3       | 4        | 11.43%  |
| Haswell     | 4        | 11.43%  |
| IvyBridge   | 3        | 8.57%   |
| Penryn      | 2        | 5.71%   |
| K10         | 2        | 5.71%   |
| Broadwell   | 2        | 5.71%   |
| Westmere    | 1        | 2.86%   |
| Steamroller | 1        | 2.86%   |
| Skylake     | 1        | 2.86%   |
| Silvermont  | 1        | 2.86%   |
| SandyBridge | 1        | 2.86%   |
| Piledriver  | 1        | 2.86%   |
| Nehalem     | 1        | 2.86%   |
| KabyLake    | 1        | 2.86%   |
| Icelake     | 1        | 2.86%   |
| Excavator   | 1        | 2.86%   |
| CometLake   | 1        | 2.86%   |
| Bulldozer   | 1        | 2.86%   |
| Unknown     | 1        | 2.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 15       | 39.47%  |
| Nvidia | 13       | 34.21%  |
| Intel  | 10       | 26.32%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 10.53%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 7.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 5.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 5.26%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 5.26%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 2.63%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 2.63%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 2.63%   |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 2.63%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 2.63%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 2.63%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1        | 2.63%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 2.63%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1        | 2.63%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 2.63%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1        | 2.63%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 2.63%   |
| Nvidia AD102 [GeForce RTX 4090]                                                          | 1        | 2.63%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 2.63%   |
| Intel HD Graphics 530                                                                    | 1        | 2.63%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 2.63%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 2.63%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                                 | 1        | 2.63%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1        | 2.63%   |
| AMD Juniper PRO [Radeon HD 5750]                                                         | 1        | 2.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 2.63%   |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 2.63%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 14       | 40%     |
| 1 x Nvidia   | 12       | 34.29%  |
| 1 x Intel    | 8        | 22.86%  |
| AMD + Nvidia | 1        | 2.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 27       | 75%     |
| Proprietary | 8        | 22.22%  |
| Unknown     | 1        | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 62.86%  |
| 7.01-8.0   | 3        | 8.57%   |
| 3.01-4.0   | 3        | 8.57%   |
| 1.01-2.0   | 3        | 8.57%   |
| 0.01-0.5   | 2        | 5.71%   |
| 16.01-24.0 | 1        | 2.86%   |
| 0.51-1.0   | 1        | 2.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 34.29%  |
| AOC                  | 4        | 11.43%  |
| Hewlett-Packard      | 3        | 8.57%   |
| SANYO                | 2        | 5.71%   |
| Philips              | 2        | 5.71%   |
| Goldstar             | 2        | 5.71%   |
| Fujitsu Siemens      | 2        | 5.71%   |
| Unknown (XXX)        | 1        | 2.86%   |
| Sony                 | 1        | 2.86%   |
| Panasonic            | 1        | 2.86%   |
| LG Electronics       | 1        | 2.86%   |
| HKC                  | 1        | 2.86%   |
| Dell                 | 1        | 2.86%   |
| BenQ                 | 1        | 2.86%   |
| Ancor Communications | 1        | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 2.63%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 2.63%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1        | 2.63%   |
| SANYO LCD SAN0A12 1920x540                                            | 1        | 2.63%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1        | 2.63%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1        | 2.63%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch  | 1        | 2.63%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch   | 1        | 2.63%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 2.63%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch     | 1        | 2.63%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1        | 2.63%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 2.63%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 1        | 2.63%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 2.63%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 800x330mm 34.1-inch     | 1        | 2.63%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 2.63%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch              | 1        | 2.63%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch               | 1        | 2.63%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                   | 1        | 2.63%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                               | 1        | 2.63%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                      | 1        | 2.63%   |
| HKC '' HKC2160 1920x1080 360x270mm 17.7-inch                          | 1        | 2.63%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 1        | 2.63%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1        | 2.63%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 2.63%   |
| Goldstar W2343 GSM5701 1920x1080 510x290mm 23.1-inch                  | 1        | 2.63%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1        | 2.63%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch               | 1        | 2.63%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 1        | 2.63%   |
| Fujitsu Siemens B27T-7 Pro FUS0891 1920x1080 598x336mm 27.0-inch      | 1        | 2.63%   |
| Dell LCD Monitor 1704FPV 1280x1024                                    | 1        | 2.63%   |
| BenQ GW2750H BNQ78C3 1920x1080 600x340mm 27.2-inch                    | 1        | 2.63%   |
| AOC U34G2G1 AOC3402 3440x1440 797x334mm 34.0-inch                     | 1        | 2.63%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 2.63%   |
| AOC LE22H138 AOC2218 1920x1080 480x270mm 21.7-inch                    | 1        | 2.63%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 1        | 2.63%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 1        | 2.63%   |
| Ancor Communications ASUS VS239 ACI23D2 1920x1080 509x286mm 23.0-inch | 1        | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 20       | 57.14%  |
| 3840x2160 (4K)     | 3        | 8.57%   |
| 1920x540           | 3        | 8.57%   |
| 3440x1440          | 2        | 5.71%   |
| 1920x1200 (WUXGA)  | 2        | 5.71%   |
| 2560x1440 (QHD)    | 1        | 2.86%   |
| 2560x1080          | 1        | 2.86%   |
| 1680x1050 (WSXGA+) | 1        | 2.86%   |
| 1366x768 (WXGA)    | 1        | 2.86%   |
| 1280x1024 (SXGA)   | 1        | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 8        | 21.62%  |
| 23      | 6        | 16.22%  |
| 27      | 4        | 10.81%  |
| 34      | 3        | 8.11%   |
| 21      | 3        | 8.11%   |
| Unknown | 3        | 8.11%   |
| 54      | 2        | 5.41%   |
| 31      | 2        | 5.41%   |
| 72      | 1        | 2.7%    |
| 40      | 1        | 2.7%    |
| 33      | 1        | 2.7%    |
| 28      | 1        | 2.7%    |
| 18      | 1        | 2.7%    |
| 17      | 1        | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 45.71%  |
| 701-800     | 4        | 11.43%  |
| 401-500     | 4        | 11.43%  |
| 601-700     | 3        | 8.57%   |
| Unknown     | 3        | 8.57%   |
| 1001-1500   | 2        | 5.71%   |
| 801-900     | 1        | 2.86%   |
| 351-400     | 1        | 2.86%   |
| 1501-2000   | 1        | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 24       | 70.59%  |
| 21/9    | 3        | 8.82%   |
| 16/10   | 3        | 8.82%   |
| Unknown | 2        | 5.88%   |
| 4/3     | 1        | 2.94%   |
| 32/9    | 1        | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 35.29%  |
| 351-500        | 7        | 20.59%  |
| 301-350        | 4        | 11.76%  |
| More than 1000 | 3        | 8.82%   |
| Unknown        | 3        | 8.82%   |
| 251-300        | 2        | 5.88%   |
| 151-200        | 1        | 2.94%   |
| 141-150        | 1        | 2.94%   |
| 501-1000       | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 22       | 64.71%  |
| 1-50    | 3        | 8.82%   |
| 121-160 | 3        | 8.82%   |
| 101-120 | 3        | 8.82%   |
| Unknown | 3        | 8.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 88.57%  |
| 2     | 4        | 11.43%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 20       | 42.55%  |
| Realtek Semiconductor | 18       | 38.3%   |
| Broadcom              | 2        | 4.26%   |
| Ralink Technology     | 1        | 2.13%   |
| Qualcomm Atheros      | 1        | 2.13%   |
| Nvidia                | 1        | 2.13%   |
| Microsoft             | 1        | 2.13%   |
| MediaTek              | 1        | 2.13%   |
| Broadcom Limited      | 1        | 2.13%   |
| ASUSTek Computer      | 1        | 2.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14       | 25.93%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 5.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 5.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 3.7%    |
| Intel I211 Gigabit Network Connection                             | 2        | 3.7%    |
| Intel Ethernet Controller I225-V                                  | 2        | 3.7%    |
| Intel Ethernet Connection (2) I218-V                              | 2        | 3.7%    |
| Intel Ethernet Connection (14) I219-V                             | 2        | 3.7%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 1.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 1.85%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 1.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.85%   |
| Realtek 802.11ac NIC                                              | 1        | 1.85%   |
| Ralink RT3072 Wireless Adapter                                    | 1        | 1.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.85%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.85%   |
| Microsoft Wireless XBox Controller Dongle                         | 1        | 1.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.85%   |
| Intel Wireless-AC 9260                                            | 1        | 1.85%   |
| Intel Wireless 7265                                               | 1        | 1.85%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.85%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.85%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.85%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.85%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.85%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 1.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 1.85%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]         | 1        | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 44.44%  |
| Realtek Semiconductor | 5        | 27.78%  |
| Ralink Technology     | 1        | 5.56%   |
| Microsoft             | 1        | 5.56%   |
| MediaTek              | 1        | 5.56%   |
| Broadcom              | 1        | 5.56%   |
| ASUSTek Computer      | 1        | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]          | 3        | 16.67%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                    | 2        | 11.11%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter       | 1        | 5.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter     | 1        | 5.56%   |
| Realtek RTL8188EE Wireless Network Adapter                | 1        | 5.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                   | 1        | 5.56%   |
| Realtek 802.11ac NIC                                      | 1        | 5.56%   |
| Ralink RT3072 Wireless Adapter                            | 1        | 5.56%   |
| Microsoft Wireless XBox Controller Dongle                 | 1        | 5.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                   | 1        | 5.56%   |
| Intel Wireless-AC 9260                                    | 1        | 5.56%   |
| Intel Wireless 7265                                       | 1        | 5.56%   |
| Intel Wi-Fi 6 AX200                                       | 1        | 5.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter        | 1        | 5.56%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU] | 1        | 5.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 44.12%  |
| Intel                 | 15       | 44.12%  |
| Qualcomm Atheros      | 1        | 2.94%   |
| Nvidia                | 1        | 2.94%   |
| Broadcom Limited      | 1        | 2.94%   |
| Broadcom              | 1        | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14       | 38.89%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 8.33%   |
| Intel I211 Gigabit Network Connection                             | 2        | 5.56%   |
| Intel Ethernet Controller I225-V                                  | 2        | 5.56%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 5.56%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.78%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.78%   |
| Intel I210 Gigabit Network Connection                             | 1        | 2.78%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.78%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.78%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 2.78%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 34       | 65.38%  |
| WiFi     | 18       | 34.62%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 72.97%  |
| WiFi     | 10       | 27.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 23       | 65.71%  |
| 2     | 12       | 34.29%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 80%     |
| Yes  | 7        | 20%     |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AMD                   | 19       | 35.19%  |
| Intel                 | 17       | 31.48%  |
| Nvidia                | 13       | 24.07%  |
| Texas Instruments     | 1        | 1.85%   |
| Shure                 | 1        | 1.85%   |
| Realtek Semiconductor | 1        | 1.85%   |
| DSEA A/S              | 1        | 1.85%   |
| ASUSTek Computer      | 1        | 1.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 8.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 5.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 4.48%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 4.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 4.48%   |
| AMD FCH Azalia Controller                                                  | 3        | 4.48%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 2.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 2.99%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.99%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 2.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.99%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.49%   |
| Shure MV88+                                                                | 1        | 1.49%   |
| Realtek Semiconductor USB Audio                                            | 1        | 1.49%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.49%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.49%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.49%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.49%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.49%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1.49%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 1.49%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.49%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 1.49%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.49%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.49%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.49%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.49%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.49%   |
| DSEA A/S BTD-800                                                           | 1        | 1.49%   |
| ASUSTek Computer USB Audio                                                 | 1        | 1.49%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 1.49%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 1        | 1.49%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 1.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 22.22%  |
| Crucial             | 4        | 22.22%  |
| SK hynix            | 2        | 11.11%  |
| Samsung Electronics | 2        | 11.11%  |
| Micron Technology   | 2        | 11.11%  |
| Transcend           | 1        | 5.56%   |
| Elpida              | 1        | 5.56%   |
| Corsair             | 1        | 5.56%   |
| A-DATA Technology   | 1        | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 10%     |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s     | 1        | 5%      |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s             | 1        | 5%      |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 5%      |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s   | 1        | 5%      |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s    | 1        | 5%      |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 1        | 5%      |
| Micron RAM 16JTF51264AZ-1G4D1 4GB DIMM DDR3 1333MT/s   | 1        | 5%      |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s      | 1        | 5%      |
| Kingston RAM 9905403-011.A02LF 2GB DIMM DDR3 1333MT/s  | 1        | 5%      |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2048MB DIMM DDR3 1333MT/s | 1        | 5%      |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s | 1        | 5%      |
| Crucial RAM CT8G4DFD8213.C16FAD 8GB DIMM DDR4 2133MT/s | 1        | 5%      |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s  | 1        | 5%      |
| Crucial RAM BLS8G4D26BFSBK.8FD 8GB DIMM DDR4 2933MT/s  | 1        | 5%      |
| Crucial RAM BL8G26C16U4B.8FD 8GB DIMM DDR4 2667MT/s    | 1        | 5%      |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s    | 1        | 5%      |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s    | 1        | 5%      |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 1        | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 8        | 57.14%  |
| DDR3  | 5        | 35.71%  |
| SDRAM | 1        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 11       | 84.62%  |
| SODIMM | 2        | 15.38%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 40%     |
| 16384 | 3        | 20%     |
| 4096  | 3        | 20%     |
| 2048  | 2        | 13.33%  |
| 32768 | 1        | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 29.41%  |
| 3200  | 2        | 11.76%  |
| 2667  | 2        | 11.76%  |
| 2400  | 2        | 11.76%  |
| 1333  | 2        | 11.76%  |
| 3600  | 1        | 5.88%   |
| 2933  | 1        | 5.88%   |
| 2133  | 1        | 5.88%   |
| 1066  | 1        | 5.88%   |

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
| Logitech                      | 2        | 33.33%  |
| Sunplus Innovation Technology | 1        | 16.67%  |
| Samsung Electronics           | 1        | 16.67%  |
| Microdia                      | 1        | 16.67%  |
| Generalplus Technology        | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 2        | 33.33%  |
| Sunplus Integrated_Webcam_HD            | 1        | 16.67%  |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 16.67%  |
| Microdia Camera                         | 1        | 16.67%  |
| Generalplus 808 Camera                  | 1        | 16.67%  |

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
| 0     | 29       | 80.56%  |
| 1     | 4        | 11.11%  |
| 2     | 2        | 5.56%   |
| 4     | 1        | 2.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 3        | 30%     |
| Sound            | 2        | 20%     |
| Net/wireless     | 2        | 20%     |
| Net/ethernet     | 1        | 10%     |
| Graphics card    | 1        | 10%     |
| Bluetooth        | 1        | 10%     |

