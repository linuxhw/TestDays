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

Total: 53

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.0-52-generic      | 4        | 8.89%   |
| 5.15.0-57-generic      | 3        | 6.67%   |
| 5.15.0-46-generic      | 3        | 6.67%   |
| 5.15.0-43-generic      | 3        | 6.67%   |
| 5.15.0-30-generic      | 3        | 6.67%   |
| 5.19.0-45-generic      | 2        | 4.44%   |
| 5.19.0-40-generic      | 2        | 4.44%   |
| 5.15.0-33-generic      | 2        | 4.44%   |
| 5.15.0-27-generic      | 2        | 4.44%   |
| 5.15.0-25-generic      | 2        | 4.44%   |
| 6.2.0-39-generic       | 1        | 2.22%   |
| 6.2.0-37-generic       | 1        | 2.22%   |
| 6.2.0-36-generic       | 1        | 2.22%   |
| 6.2.0-35-generic       | 1        | 2.22%   |
| 6.2.0-33-generic       | 1        | 2.22%   |
| 6.2.0-26-generic       | 1        | 2.22%   |
| 5.19.0-46-generic      | 1        | 2.22%   |
| 5.17.2-051702-generic  | 1        | 2.22%   |
| 5.15.92-051592-generic | 1        | 2.22%   |
| 5.15.0-84-generic      | 1        | 2.22%   |
| 5.15.0-73-generic      | 1        | 2.22%   |
| 5.15.0-71-generic      | 1        | 2.22%   |
| 5.15.0-60-generic      | 1        | 2.22%   |
| 5.15.0-56-generic      | 1        | 2.22%   |
| 5.15.0-50-generic      | 1        | 2.22%   |
| 5.15.0-48-generic      | 1        | 2.22%   |
| 5.15.0-47-generic      | 1        | 2.22%   |
| 5.15.0-41-generic      | 1        | 2.22%   |
| 5.13.0-44-generic      | 1        | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 29       | 69.05%  |
| 6.2.0   | 5        | 11.9%   |
| 5.19.0  | 5        | 11.9%   |
| 5.17.2  | 1        | 2.38%   |
| 5.15.92 | 1        | 2.38%   |
| 5.13.0  | 1        | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 30       | 71.43%  |
| 6.2     | 5        | 11.9%   |
| 5.19    | 5        | 11.9%   |
| 5.17    | 1        | 2.38%   |
| 5.13    | 1        | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 41       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 41       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 41       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 31       | 75.61%  |
| Unknown | 9        | 21.95%  |
| GDM     | 1        | 2.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 17       | 41.46%  |
| de_DE | 6        | 14.63%  |
| pt_BR | 4        | 9.76%   |
| es_ES | 3        | 7.32%   |
| fr_FR | 2        | 4.88%   |
| en_GB | 2        | 4.88%   |
| es_MX | 1        | 2.44%   |
| es_AR | 1        | 2.44%   |
| en_ZA | 1        | 2.44%   |
| en_SG | 1        | 2.44%   |
| en_CA | 1        | 2.44%   |
| en_AU | 1        | 2.44%   |
| el_GR | 1        | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 30       | 71.43%  |
| EFI  | 12       | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 32       | 78.05%  |
| Tmpfs   | 4        | 9.76%   |
| Overlay | 3        | 7.32%   |
| Zfs     | 1        | 2.44%   |
| Btrfs   | 1        | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 25       | 59.52%  |
| Unknown | 16       | 38.1%   |
| MBR     | 1        | 2.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 80.49%  |
| Yes       | 8        | 19.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 56.1%   |
| Yes       | 18       | 43.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 11       | 26.83%  |
| MSI                 | 7        | 17.07%  |
| Hewlett-Packard     | 4        | 9.76%   |
| ASUSTek Computer    | 4        | 9.76%   |
| Intel               | 3        | 7.32%   |
| Fujitsu             | 3        | 7.32%   |
| Dell                | 3        | 7.32%   |
| ASRock              | 3        | 7.32%   |
| Semp Toshiba        | 1        | 2.44%   |
| Lenovo              | 1        | 2.44%   |
| Biostar             | 1        | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Semp Toshiba STI                   | 1        | 2.44%   |
| MSI MS-7C95                        | 1        | 2.44%   |
| MSI MS-7C51                        | 1        | 2.44%   |
| MSI MS-7B86                        | 1        | 2.44%   |
| MSI MS-7A38                        | 1        | 2.44%   |
| MSI MS-7A32                        | 1        | 2.44%   |
| MSI MS-7885                        | 1        | 2.44%   |
| MSI MS-7721                        | 1        | 2.44%   |
| Lenovo ThinkStation C20 4263BA7    | 1        | 2.44%   |
| Intel STK1A32SC                    | 1        | 2.44%   |
| Intel H61                          | 1        | 2.44%   |
| Intel DP55WB AAE64798-206          | 1        | 2.44%   |
| HP Z440 Workstation                | 1        | 2.44%   |
| HP EliteDesk 800 G2 SFF            | 1        | 2.44%   |
| HP EliteDesk 800 G1 DM             | 1        | 2.44%   |
| HP 750-417c                        | 1        | 2.44%   |
| Gigabyte X570S AORUS PRO AX        | 1        | 2.44%   |
| Gigabyte M68MT-S2                  | 1        | 2.44%   |
| Gigabyte H410M S2H V3              | 1        | 2.44%   |
| Gigabyte H310MHD2                  | 1        | 2.44%   |
| Gigabyte GA-890GPA-UD3H            | 1        | 2.44%   |
| Gigabyte F2A78M-HD2                | 1        | 2.44%   |
| Gigabyte B75M-D3P                  | 1        | 2.44%   |
| Gigabyte B75M-D3H                  | 1        | 2.44%   |
| Gigabyte B650M AORUS ELITE AX      | 1        | 2.44%   |
| Gigabyte B550 AORUS ELITE AX V2    | 1        | 2.44%   |
| Gigabyte B450 I AORUS PRO WIFI     | 1        | 2.44%   |
| Fujitsu ESPRIMO Q920               | 1        | 2.44%   |
| Fujitsu ESPRIMO Q910               | 1        | 2.44%   |
| Fujitsu D3348-B2                   | 1        | 2.44%   |
| Dell Precision WorkStation T7400   | 1        | 2.44%   |
| Dell OptiPlex 780                  | 1        | 2.44%   |
| Dell OptiPlex 390                  | 1        | 2.44%   |
| Biostar A960D+V3                   | 1        | 2.44%   |
| ASUS ROG STRIX X670E-E GAMING WIFI | 1        | 2.44%   |
| ASUS PRIME B560M-A                 | 1        | 2.44%   |
| ASUS All Series                    | 1        | 2.44%   |
| ASUS A88X-PRO                      | 1        | 2.44%   |
| ASRock FM2A88X Extreme4+           | 1        | 2.44%   |
| ASRock B450M Steel Legend          | 1        | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| HP EliteDesk            | 2        | 4.88%   |
| Fujitsu ESPRIMO         | 2        | 4.88%   |
| Dell OptiPlex           | 2        | 4.88%   |
| Semp Toshiba STI        | 1        | 2.44%   |
| MSI MS-7C95             | 1        | 2.44%   |
| MSI MS-7C51             | 1        | 2.44%   |
| MSI MS-7B86             | 1        | 2.44%   |
| MSI MS-7A38             | 1        | 2.44%   |
| MSI MS-7A32             | 1        | 2.44%   |
| MSI MS-7885             | 1        | 2.44%   |
| MSI MS-7721             | 1        | 2.44%   |
| Lenovo ThinkStation     | 1        | 2.44%   |
| Intel STK1A32SC         | 1        | 2.44%   |
| Intel H61               | 1        | 2.44%   |
| Intel DP55WB            | 1        | 2.44%   |
| HP Z440                 | 1        | 2.44%   |
| HP 750-417c             | 1        | 2.44%   |
| Gigabyte X570S          | 1        | 2.44%   |
| Gigabyte M68MT-S2       | 1        | 2.44%   |
| Gigabyte H410M          | 1        | 2.44%   |
| Gigabyte H310MHD2       | 1        | 2.44%   |
| Gigabyte GA-890GPA-UD3H | 1        | 2.44%   |
| Gigabyte F2A78M-HD2     | 1        | 2.44%   |
| Gigabyte B75M-D3P       | 1        | 2.44%   |
| Gigabyte B75M-D3H       | 1        | 2.44%   |
| Gigabyte B650M          | 1        | 2.44%   |
| Gigabyte B550           | 1        | 2.44%   |
| Gigabyte B450           | 1        | 2.44%   |
| Fujitsu D3348-B2        | 1        | 2.44%   |
| Dell Precision          | 1        | 2.44%   |
| Biostar A960D+V3        | 1        | 2.44%   |
| ASUS ROG                | 1        | 2.44%   |
| ASUS PRIME              | 1        | 2.44%   |
| ASUS All                | 1        | 2.44%   |
| ASUS A88X-PRO           | 1        | 2.44%   |
| ASRock FM2A88X          | 1        | 2.44%   |
| ASRock B450M            | 1        | 2.44%   |
| ASRock A300M-STX        | 1        | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 7        | 17.07%  |
| 2018 | 5        | 12.2%   |
| 2021 | 3        | 7.32%   |
| 2019 | 3        | 7.32%   |
| 2017 | 3        | 7.32%   |
| 2015 | 3        | 7.32%   |
| 2011 | 3        | 7.32%   |
| 2010 | 3        | 7.32%   |
| 2022 | 2        | 4.88%   |
| 2020 | 2        | 4.88%   |
| 2016 | 2        | 4.88%   |
| 2012 | 2        | 4.88%   |
| 2013 | 1        | 2.44%   |
| 2009 | 1        | 2.44%   |
| 2008 | 1        | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 41       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 40       | 97.56%  |
| Enabled  | 1        | 2.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 13       | 31.71%  |
| 8.01-16.0       | 11       | 26.83%  |
| 4.01-8.0        | 8        | 19.51%  |
| 32.01-64.0      | 3        | 7.32%   |
| 24.01-32.0      | 2        | 4.88%   |
| 64.01-256.0     | 2        | 4.88%   |
| More than 256.0 | 1        | 2.44%   |
| 1.01-2.0        | 1        | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 15       | 33.33%  |
| 2.01-3.0   | 14       | 31.11%  |
| 4.01-8.0   | 9        | 20%     |
| 3.01-4.0   | 4        | 8.89%   |
| 8.01-16.0  | 2        | 4.44%   |
| 16.01-24.0 | 1        | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 14       | 34.15%  |
| 1      | 12       | 29.27%  |
| 4      | 6        | 14.63%  |
| 3      | 5        | 12.2%   |
| 6      | 2        | 4.88%   |
| 8      | 1        | 2.44%   |
| 7      | 1        | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 58.54%  |
| Yes       | 17       | 41.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 40       | 97.56%  |
| No        | 1        | 2.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 51.22%  |
| Yes       | 20       | 48.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 68.29%  |
| Yes       | 13       | 31.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 10       | 24.39%  |
| Germany      | 5        | 12.2%   |
| Brazil       | 5        | 12.2%   |
| Spain        | 3        | 7.32%   |
| UK           | 2        | 4.88%   |
| Switzerland  | 2        | 4.88%   |
| France       | 2        | 4.88%   |
| Argentina    | 2        | 4.88%   |
| South Africa | 1        | 2.44%   |
| Slovenia     | 1        | 2.44%   |
| Singapore    | 1        | 2.44%   |
| Romania      | 1        | 2.44%   |
| Norway       | 1        | 2.44%   |
| Mexico       | 1        | 2.44%   |
| Greece       | 1        | 2.44%   |
| Croatia      | 1        | 2.44%   |
| Austria      | 1        | 2.44%   |
| Australia    | 1        | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Brasília                 | 3        | 6.82%   |
| Milwaukee                 | 2        | 4.55%   |
| Zurich                    | 1        | 2.27%   |
| Walled Lake               | 1        | 2.27%   |
| Trondheim                 | 1        | 2.27%   |
| Tocantins                 | 1        | 2.27%   |
| Tann                      | 1        | 2.27%   |
| Singapore                 | 1        | 2.27%   |
| Seattle                   | 1        | 2.27%   |
| San Luis Potosí City     | 1        | 2.27%   |
| San Francisco de Santa Fe | 1        | 2.27%   |
| San Francisco             | 1        | 2.27%   |
| San Diego                 | 1        | 2.27%   |
| Rueil-Malmaison           | 1        | 2.27%   |
| Pula                      | 1        | 2.27%   |
| Pine Island               | 1        | 2.27%   |
| New York                  | 1        | 2.27%   |
| Maribor                   | 1        | 2.27%   |
| Manaus                    | 1        | 2.27%   |
| Madrid                    | 1        | 2.27%   |
| London                    | 1        | 2.27%   |
| Limay                     | 1        | 2.27%   |
| Kittsee                   | 1        | 2.27%   |
| Kirkcaldy                 | 1        | 2.27%   |
| Houston                   | 1        | 2.27%   |
| Hamburg                   | 1        | 2.27%   |
| Granada                   | 1        | 2.27%   |
| Eugene                    | 1        | 2.27%   |
| Ennepetal                 | 1        | 2.27%   |
| Dortmund                  | 1        | 2.27%   |
| Delbrueck                 | 1        | 2.27%   |
| Colon                     | 1        | 2.27%   |
| Caslano                   | 1        | 2.27%   |
| Cape Town                 | 1        | 2.27%   |
| Camp Hill                 | 1        | 2.27%   |
| Brisbane                  | 1        | 2.27%   |
| Brenes                    | 1        | 2.27%   |
| Bradenton                 | 1        | 2.27%   |
| Berlin                    | 1        | 2.27%   |
| Baia Mare                 | 1        | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 16       | 24     | 19.05%  |
| WDC                       | 13       | 16     | 15.48%  |
| Samsung Electronics       | 11       | 32     | 13.1%   |
| Sandisk                   | 5        | 6      | 5.95%   |
| Toshiba                   | 4        | 4      | 4.76%   |
| Crucial                   | 4        | 4      | 4.76%   |
| Kingston                  | 3        | 4      | 3.57%   |
| Transcend                 | 2        | 2      | 2.38%   |
| PNY                       | 2        | 2      | 2.38%   |
| OCZ                       | 2        | 2      | 2.38%   |
| Micron/Crucial Technology | 2        | 2      | 2.38%   |
| Micron Technology         | 2        | 2      | 2.38%   |
| China                     | 2        | 2      | 2.38%   |
| A-DATA Technology         | 2        | 2      | 2.38%   |
| Zheino                    | 1        | 1      | 1.19%   |
| Unknown                   | 1        | 1      | 1.19%   |
| SPCC                      | 1        | 1      | 1.19%   |
| SK hynix                  | 1        | 1      | 1.19%   |
| Phison                    | 1        | 1      | 1.19%   |
| Mushkin                   | 1        | 1      | 1.19%   |
| MicroFrom                 | 1        | 1      | 1.19%   |
| Maxtor                    | 1        | 1      | 1.19%   |
| JMicron Technology        | 1        | 1      | 1.19%   |
| Intenso                   | 1        | 1      | 1.19%   |
| Intel                     | 1        | 1      | 1.19%   |
| HGST                      | 1        | 1      | 1.19%   |
| ASMT109x                  | 1        | 1      | 1.19%   |
| 4Life                     | 1        | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB      | 2        | 2.02%   |
| Seagate ST3500418AS 500GB         | 2        | 2.02%   |
| Seagate ST1000LM048-2E7172 1TB    | 2        | 2.02%   |
| SanDisk SDSSDA120G 120GB          | 2        | 2.02%   |
| Samsung SSD 870 EVO 250GB         | 2        | 2.02%   |
| Samsung SSD 850 PRO 256GB         | 2        | 2.02%   |
| Samsung SSD 840 EVO 250GB         | 2        | 2.02%   |
| Zheino CHN-25SATAC3-120 120GB SSD | 1        | 1.01%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1.01%   |
| WDC WDS100T2B0C 1TB               | 1        | 1.01%   |
| WDC WD40PURZ-85TTDY0 4TB          | 1        | 1.01%   |
| WDC WD40EZAZ-00SF3B0 4TB          | 1        | 1.01%   |
| WDC WD40EFAX-68JH4N1 4TB          | 1        | 1.01%   |
| WDC WD3200LPVX-22V0TT0 320GB      | 1        | 1.01%   |
| WDC WD20EARX-00PASB0 2TB          | 1        | 1.01%   |
| WDC WD1600AAJS-60WAA0 160GB       | 1        | 1.01%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 1.01%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1.01%   |
| WDC WD10EADS-00M2B0 1TB           | 1        | 1.01%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1.01%   |
| WDC WD Green 2.5 240GB SSD        | 1        | 1.01%   |
| Unknown SD/MMC/MS PRO 256GB       | 1        | 1.01%   |
| Transcend TS480GMTS820S 480GB SSD | 1        | 1.01%   |
| Transcend TS128GMTE110S 128GB     | 1        | 1.01%   |
| Toshiba MD04ACA400 4TB            | 1        | 1.01%   |
| Toshiba HDWD240 4TB               | 1        | 1.01%   |
| Toshiba HDWD220 2TB               | 1        | 1.01%   |
| Toshiba DT01ACA050 500GB          | 1        | 1.01%   |
| SPCC Solid State Disk 256GB       | 1        | 1.01%   |
| SK hynix SC210 2.5 7MM 128GB SSD  | 1        | 1.01%   |
| Seagate ST9500325AS 500GB         | 1        | 1.01%   |
| Seagate ST8000VN0022-2EL112 8TB   | 1        | 1.01%   |
| Seagate ST500LT012-1DG142 500GB   | 1        | 1.01%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1.01%   |
| Seagate ST4000DM004-2CV104 4TB    | 1        | 1.01%   |
| Seagate ST380815AS 80GB           | 1        | 1.01%   |
| Seagate ST3500413AS 500GB         | 1        | 1.01%   |
| Seagate ST3500412AS 500GB         | 1        | 1.01%   |
| Seagate ST3160815AS 160GB         | 1        | 1.01%   |
| Seagate ST2000DM008-2FR102 2TB    | 1        | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 23     | 42.11%  |
| WDC                 | 11       | 13     | 28.95%  |
| Toshiba             | 4        | 4      | 10.53%  |
| Samsung Electronics | 2        | 4      | 5.26%   |
| Unknown             | 1        | 1      | 2.63%   |
| Maxtor              | 1        | 1      | 2.63%   |
| JMicron Technology  | 1        | 1      | 2.63%   |
| HGST                | 1        | 1      | 2.63%   |
| ASMT109x            | 1        | 1      | 2.63%   |

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
| Kingston            | 2        | 3      | 6.25%   |
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
| 4Life               | 1        | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 27       | 48     | 38.57%  |
| HDD     | 27       | 49     | 38.57%  |
| NVMe    | 14       | 19     | 20%     |
| MMC     | 1        | 1      | 1.43%   |
| Unknown | 1        | 1      | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 38       | 95     | 67.86%  |
| NVMe | 14       | 19     | 25%     |
| SAS  | 3        | 3      | 5.36%   |
| MMC  | 1        | 1      | 1.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 34       | 61     | 56.67%  |
| 0.51-1.0   | 13       | 19     | 21.67%  |
| 3.01-4.0   | 7        | 8      | 11.67%  |
| 1.01-2.0   | 5        | 7      | 8.33%   |
| 4.01-10.0  | 1        | 2      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 31.71%  |
| More than 3000 | 5        | 12.2%   |
| 251-500        | 5        | 12.2%   |
| 1001-2000      | 4        | 9.76%   |
| 1-20           | 4        | 9.76%   |
| 51-100         | 4        | 9.76%   |
| 501-1000       | 3        | 7.32%   |
| 2001-3000      | 2        | 4.88%   |
| 21-50          | 1        | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 12       | 27.91%  |
| 1-20           | 12       | 27.91%  |
| 51-100         | 8        | 18.6%   |
| 101-250        | 4        | 9.3%    |
| 1001-2000      | 3        | 6.98%   |
| More than 3000 | 2        | 4.65%   |
| 251-500        | 1        | 2.33%   |
| 2001-3000      | 1        | 2.33%   |

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
| Detected | 29       | 81     | 63.04%  |
| Works    | 14       | 34     | 30.43%  |
| Malfunc  | 3        | 3      | 6.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 22       | 37.29%  |
| AMD                         | 18       | 30.51%  |
| Samsung Electronics         | 5        | 8.47%   |
| SanDisk                     | 3        | 5.08%   |
| Micron/Crucial Technology   | 2        | 3.39%   |
| Transcend                   | 1        | 1.69%   |
| Seagate Technology          | 1        | 1.69%   |
| Phison Electronics          | 1        | 1.69%   |
| OCZ Technology Group        | 1        | 1.69%   |
| Nvidia                      | 1        | 1.69%   |
| Micron Technology           | 1        | 1.69%   |
| Marvell Technology Group    | 1        | 1.69%   |
| Kingston Technology Company | 1        | 1.69%   |
| JMicron Technology          | 1        | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 9.72%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 5.56%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2        | 2.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 2.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 2.78%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 2.78%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 2.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 2.78%   |
| AMD FCH IDE Controller                                                         | 2        | 2.78%   |
| AMD 600 Series Chipset SATA Controller                                         | 2        | 2.78%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 2.78%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 1        | 1.39%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                      | 1        | 1.39%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1        | 1.39%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1        | 1.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1        | 1.39%   |
| Samsung NVMe SSD Controller 172X                                               | 1        | 1.39%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 1.39%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 1.39%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.39%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 1.39%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 1.39%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 1        | 1.39%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.39%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1        | 1.39%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 1.39%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1        | 1.39%   |
| Intel sSATA Controller [RAID Mode]                                             | 1        | 1.39%   |
| Intel SATA Controller [RAID Mode]                                              | 1        | 1.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.39%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 1.39%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.39%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 1.39%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                     | 1        | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 35       | 58.33%  |
| NVMe | 14       | 23.33%  |
| IDE  | 10       | 16.67%  |
| RAID | 1        | 1.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 22       | 53.66%  |
| AMD    | 19       | 46.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-4590T CPU @ 2.00GHz               | 2        | 4.88%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 4.88%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 2        | 4.88%   |
| Intel Xeon CPU X5492 @ 3.40GHz                  | 1        | 2.44%   |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 1        | 2.44%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz            | 1        | 2.44%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz             | 1        | 2.44%   |
| Intel Pentium CPU G620 @ 2.60GHz                | 1        | 2.44%   |
| Intel Core i7-5820K CPU @ 3.30GHz               | 1        | 2.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 2.44%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 2.44%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 2.44%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1        | 2.44%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 2.44%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 2.44%   |
| Intel Core i5-3470T CPU @ 2.90GHz               | 1        | 2.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 2.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 2.44%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1        | 2.44%   |
| Intel Core i3-3225 CPU @ 3.30GHz                | 1        | 2.44%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 2.44%   |
| Intel Atom x5-Z8330 CPU @ 1.44GHz               | 1        | 2.44%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz          | 1        | 2.44%   |
| AMD Ryzen 9 7900X 12-Core Processor             | 1        | 2.44%   |
| AMD Ryzen 9 7900 12-Core Processor              | 1        | 2.44%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 2.44%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 2.44%   |
| AMD Ryzen 5 5600 6-Core Processor               | 1        | 2.44%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 2.44%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1        | 2.44%   |
| AMD Phenom II X4 965 Processor                  | 1        | 2.44%   |
| AMD FX-8150 Eight-Core Processor                | 1        | 2.44%   |
| AMD Athlon X4 845 Quad Core Processor           | 1        | 2.44%   |
| AMD Athlon II X3 445 Processor                  | 1        | 2.44%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 1        | 2.44%   |
| AMD A4-6300 APU with Radeon HD Graphics         | 1        | 2.44%   |
| AMD A4-4000 APU with Radeon HD Graphics         | 1        | 2.44%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 9        | 21.95%  |
| AMD Ryzen 5       | 6        | 14.63%  |
| Intel Xeon        | 4        | 9.76%   |
| Intel Core i7     | 4        | 9.76%   |
| AMD Ryzen 9       | 3        | 7.32%   |
| AMD A4            | 2        | 4.88%   |
| Other             | 1        | 2.44%   |
| Intel Pentium     | 1        | 2.44%   |
| Intel Core i3     | 1        | 2.44%   |
| Intel Core 2 Quad | 1        | 2.44%   |
| Intel Atom        | 1        | 2.44%   |
| AMD Ryzen 7       | 1        | 2.44%   |
| AMD Ryzen 3       | 1        | 2.44%   |
| AMD Phenom II X4  | 1        | 2.44%   |
| AMD FX            | 1        | 2.44%   |
| AMD Athlon X4     | 1        | 2.44%   |
| AMD Athlon II X3  | 1        | 2.44%   |
| AMD Athlon        | 1        | 2.44%   |
| AMD A10           | 1        | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 17       | 41.46%  |
| 6      | 8        | 19.51%  |
| 2      | 6        | 14.63%  |
| 12     | 3        | 7.32%   |
| 8      | 3        | 7.32%   |
| 1      | 2        | 4.88%   |
| 16     | 1        | 2.44%   |
| 3      | 1        | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 39       | 95.12%  |
| 2      | 2        | 4.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 65.85%  |
| 1      | 14       | 34.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 41       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 60.47%  |
| 0x306a9    | 3        | 6.98%   |
| 0x406f1    | 2        | 4.65%   |
| 0xa0671    | 1        | 2.33%   |
| 0x506e3    | 1        | 2.33%   |
| 0x406c4    | 1        | 2.33%   |
| 0x306c3    | 1        | 2.33%   |
| 0x10677    | 1        | 2.33%   |
| 0x0a601206 | 1        | 2.33%   |
| 0x0a50000c | 1        | 2.33%   |
| 0x0a201205 | 1        | 2.33%   |
| 0x0a201016 | 1        | 2.33%   |
| 0x08108109 | 1        | 2.33%   |
| 0x08108102 | 1        | 2.33%   |
| 0x06001119 | 1        | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 5        | 12.2%   |
| Zen 3       | 5        | 12.2%   |
| Haswell     | 4        | 9.76%   |
| SandyBridge | 3        | 7.32%   |
| IvyBridge   | 3        | 7.32%   |
| Skylake     | 2        | 4.88%   |
| Piledriver  | 2        | 4.88%   |
| Penryn      | 2        | 4.88%   |
| K10         | 2        | 4.88%   |
| Broadwell   | 2        | 4.88%   |
| Unknown     | 2        | 4.88%   |
| Westmere    | 1        | 2.44%   |
| Steamroller | 1        | 2.44%   |
| Silvermont  | 1        | 2.44%   |
| Nehalem     | 1        | 2.44%   |
| KabyLake    | 1        | 2.44%   |
| Icelake     | 1        | 2.44%   |
| Excavator   | 1        | 2.44%   |
| CometLake   | 1        | 2.44%   |
| Bulldozer   | 1        | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 17       | 38.64%  |
| Nvidia | 15       | 34.09%  |
| Intel  | 12       | 27.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 9.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 6.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 4.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 4.55%   |
| Intel HD Graphics 530                                                                    | 2        | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 4.55%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                                           | 2        | 4.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 4.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 4.55%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 4.55%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 2.27%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 2.27%   |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 2.27%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 2.27%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 2.27%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 2.27%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1        | 2.27%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 2.27%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1        | 2.27%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 2.27%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1        | 2.27%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 2.27%   |
| Nvidia AD102 [GeForce RTX 4090]                                                          | 1        | 2.27%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 2.27%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.27%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 2.27%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1        | 2.27%   |
| AMD Juniper PRO [Radeon HD 5750]                                                         | 1        | 2.27%   |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 2.27%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 16       | 39.02%  |
| 1 x Nvidia   | 14       | 34.15%  |
| 1 x Intel    | 10       | 24.39%  |
| AMD + Nvidia | 1        | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 76.19%  |
| Proprietary | 9        | 21.43%  |
| Unknown     | 1        | 2.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 60.98%  |
| 3.01-4.0   | 5        | 12.2%   |
| 7.01-8.0   | 3        | 7.32%   |
| 1.01-2.0   | 3        | 7.32%   |
| 16.01-24.0 | 2        | 4.88%   |
| 0.01-0.5   | 2        | 4.88%   |
| 0.51-1.0   | 1        | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 14       | 34.15%  |
| AOC                  | 4        | 9.76%   |
| Hewlett-Packard      | 3        | 7.32%   |
| Goldstar             | 3        | 7.32%   |
| SANYO                | 2        | 4.88%   |
| Philips              | 2        | 4.88%   |
| Fujitsu Siemens      | 2        | 4.88%   |
| Ancor Communications | 2        | 4.88%   |
| Vizio                | 1        | 2.44%   |
| Unknown (XXX)        | 1        | 2.44%   |
| Sony                 | 1        | 2.44%   |
| RTK                  | 1        | 2.44%   |
| Panasonic            | 1        | 2.44%   |
| LG Electronics       | 1        | 2.44%   |
| HKC                  | 1        | 2.44%   |
| Dell                 | 1        | 2.44%   |
| BenQ                 | 1        | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio E320-A0 VIZ0095 1366x768 697x392mm 31.5-inch                    | 1        | 2.27%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 2.27%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 2.27%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1        | 2.27%   |
| SANYO LCD SAN0A12 1920x540                                            | 1        | 2.27%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1        | 2.27%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1        | 2.27%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch  | 1        | 2.27%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch   | 1        | 2.27%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch     | 1        | 2.27%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 2.27%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch     | 1        | 2.27%   |
| Samsung Electronics Odyssey G7 SAM72BF 3840x2160 697x392mm 31.5-inch  | 1        | 2.27%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1        | 2.27%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 2.27%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 1        | 2.27%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 2.27%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch     | 1        | 2.27%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 2.27%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1        | 2.27%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch              | 1        | 2.27%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch               | 1        | 2.27%   |
| Philips 273EL PHLC07C 1920x1080 600x340mm 27.2-inch                   | 1        | 2.27%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                               | 1        | 2.27%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                      | 1        | 2.27%   |
| HKC '' HKC2160 1920x1080 360x270mm 17.7-inch                          | 1        | 2.27%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 1        | 2.27%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1        | 2.27%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 2.27%   |
| Goldstar W2343 GSM5701 1920x1080 510x290mm 23.1-inch                  | 1        | 2.27%   |
| Goldstar W2052 GSM4E89 1680x1050 474x296mm 22.0-inch                  | 1        | 2.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1        | 2.27%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch               | 1        | 2.27%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 1        | 2.27%   |
| Fujitsu Siemens B27T-7 Pro FUS0891 1920x1080 598x336mm 27.0-inch      | 1        | 2.27%   |
| Dell LCD Monitor 1704FPV 1280x1024                                    | 1        | 2.27%   |
| BenQ GW2750H BNQ78C3 1920x1080 598x336mm 27.0-inch                    | 1        | 2.27%   |
| AOC U34G2G4R3 AOC3402 3440x1440 797x334mm 34.0-inch                   | 1        | 2.27%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 2.27%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 1        | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 51.22%  |
| 3840x2160 (4K)     | 4        | 9.76%   |
| 1920x540           | 3        | 7.32%   |
| 3440x1440          | 2        | 4.88%   |
| 2560x1440 (QHD)    | 2        | 4.88%   |
| 1920x1200 (WUXGA)  | 2        | 4.88%   |
| 1680x1050 (WSXGA+) | 2        | 4.88%   |
| 1366x768 (WXGA)    | 2        | 4.88%   |
| 2560x1080          | 1        | 2.44%   |
| 1600x900 (HD+)     | 1        | 2.44%   |
| 1280x1024 (SXGA)   | 1        | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 8        | 18.6%   |
| 23      | 6        | 13.95%  |
| 27      | 5        | 11.63%  |
| 31      | 4        | 9.3%    |
| 34      | 3        | 6.98%   |
| 21      | 3        | 6.98%   |
| Unknown | 3        | 6.98%   |
| 54      | 2        | 4.65%   |
| 72      | 1        | 2.33%   |
| 46      | 1        | 2.33%   |
| 40      | 1        | 2.33%   |
| 33      | 1        | 2.33%   |
| 28      | 1        | 2.33%   |
| 22      | 1        | 2.33%   |
| 20      | 1        | 2.33%   |
| 18      | 1        | 2.33%   |
| 17      | 1        | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 41.46%  |
| 401-500     | 6        | 14.63%  |
| 601-700     | 5        | 12.2%   |
| 701-800     | 4        | 9.76%   |
| 1001-1500   | 3        | 7.32%   |
| Unknown     | 3        | 7.32%   |
| 801-900     | 1        | 2.44%   |
| 351-400     | 1        | 2.44%   |
| 1501-2000   | 1        | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 28       | 71.79%  |
| 16/10   | 4        | 10.26%  |
| 21/9    | 3        | 7.69%   |
| Unknown | 2        | 5.13%   |
| 4/3     | 1        | 2.56%   |
| 32/9    | 1        | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 32.5%   |
| 351-500        | 9        | 22.5%   |
| 301-350        | 5        | 12.5%   |
| More than 1000 | 3        | 7.5%    |
| Unknown        | 3        | 7.5%    |
| 251-300        | 2        | 5%      |
| 151-200        | 2        | 5%      |
| 501-1000       | 2        | 5%      |
| 141-150        | 1        | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 60%     |
| 1-50    | 5        | 12.5%   |
| 121-160 | 4        | 10%     |
| 101-120 | 4        | 10%     |
| Unknown | 3        | 7.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 85.37%  |
| 2     | 6        | 14.63%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 39.29%  |
| Intel                 | 22       | 39.29%  |
| Qualcomm Atheros      | 2        | 3.57%   |
| Broadcom              | 2        | 3.57%   |
| T & A Mobile Phones   | 1        | 1.79%   |
| Raspberry Pi          | 1        | 1.79%   |
| Ralink Technology     | 1        | 1.79%   |
| Nvidia                | 1        | 1.79%   |
| Microsoft             | 1        | 1.79%   |
| MediaTek              | 1        | 1.79%   |
| Broadcom Limited      | 1        | 1.79%   |
| ASUSTek Computer      | 1        | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16       | 25%     |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3        | 4.69%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 4.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 4.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 3.13%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 3.13%   |
| Intel Ethernet Controller I225-V                                       | 2        | 3.13%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 3.13%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 3.13%   |
| T & A Mobile Phones TCL 20E                                            | 1        | 1.56%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 1.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 1.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 1.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 1.56%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 1.56%   |
| Realtek 802.11ac NIC                                                   | 1        | 1.56%   |
| Raspberry Pi Pico                                                      | 1        | 1.56%   |
| Ralink RT3072 Wireless Adapter                                         | 1        | 1.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.56%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 1.56%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 1        | 1.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1        | 1.56%   |
| Intel Wireless 7265                                                    | 1        | 1.56%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 1.56%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 1.56%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 1.56%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 1.56%   |
| Intel 82578DC Gigabit Network Connection                               | 1        | 1.56%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 1.56%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 1        | 1.56%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 1        | 1.56%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 1        | 1.56%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]              | 1        | 1.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 9        | 45%     |
| Realtek Semiconductor | 6        | 30%     |
| Ralink Technology     | 1        | 5%      |
| Microsoft             | 1        | 5%      |
| MediaTek              | 1        | 5%      |
| Broadcom              | 1        | 5%      |
| ASUSTek Computer      | 1        | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]    | 3        | 15%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]             | 3        | 15%     |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter          | 1        | 5%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter      | 1        | 5%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter        | 1        | 5%      |
| Realtek RTL8188EE Wireless Network Adapter                   | 1        | 5%      |
| Realtek RTL8188CUS 802.11n WLAN Adapter                      | 1        | 5%      |
| Realtek 802.11ac NIC                                         | 1        | 5%      |
| Ralink RT3072 Wireless Adapter                               | 1        | 5%      |
| Microsoft Xbox Wireless Adapter for Windows                  | 1        | 5%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                      | 1        | 5%      |
| Intel Wireless 7265                                          | 1        | 5%      |
| Intel Wi-Fi 6 AX200                                          | 1        | 5%      |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]      | 1        | 5%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter | 1        | 5%      |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]    | 1        | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 46.34%  |
| Intel                 | 16       | 39.02%  |
| Qualcomm Atheros      | 2        | 4.88%   |
| T & A Mobile Phones   | 1        | 2.44%   |
| Nvidia                | 1        | 2.44%   |
| Broadcom Limited      | 1        | 2.44%   |
| Broadcom              | 1        | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16       | 37.21%  |
| Intel Ethernet Connection I217-LM                                      | 3        | 6.98%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 4.65%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 4.65%   |
| Intel Ethernet Controller I225-V                                       | 2        | 4.65%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 4.65%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 4.65%   |
| T & A Mobile Phones TCL 20E                                            | 1        | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 2.33%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 2.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 2.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 2.33%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 2.33%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 2.33%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 2.33%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 2.33%   |
| Intel 82578DC Gigabit Network Connection                               | 1        | 2.33%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 2.33%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 1        | 2.33%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 1        | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 40       | 65.57%  |
| WiFi     | 20       | 32.79%  |
| Modem    | 1        | 1.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 76.19%  |
| WiFi     | 10       | 23.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 68.29%  |
| 2     | 13       | 31.71%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 33       | 80.49%  |
| Yes  | 8        | 19.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 8        | 61.54%  |
| Cambridge Silicon Radio | 3        | 23.08%  |
| MediaTek                | 1        | 7.69%   |
| Broadcom                | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX210 Bluetooth                               | 3        | 23.08%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 23.08%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 15.38%  |
| MediaTek Wireless_Device                            | 1        | 7.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 7.69%   |
| Intel Bluetooth wireless interface                  | 1        | 7.69%   |
| Intel AX200 Bluetooth                               | 1        | 7.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| AMD                     | 22       | 33.33%  |
| Intel                   | 20       | 30.3%   |
| Nvidia                  | 15       | 22.73%  |
| Logitech                | 2        | 3.03%   |
| Texas Instruments       | 1        | 1.52%   |
| Shure                   | 1        | 1.52%   |
| Realtek Semiconductor   | 1        | 1.52%   |
| GN Netcom               | 1        | 1.52%   |
| DSEA A/S                | 1        | 1.52%   |
| ClearOne Communications | 1        | 1.52%   |
| ASUSTek Computer        | 1        | 1.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 8.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 4.94%   |
| AMD FCH Azalia Controller                                                  | 4        | 4.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 3.7%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 3.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 3.7%    |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 3.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.47%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 2.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 2.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.47%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 2.47%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 2        | 2.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.47%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.23%   |
| Shure MV88+                                                                | 1        | 1.23%   |
| Realtek Semiconductor USB Audio                                            | 1        | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.23%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.23%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 1.23%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1        | 1.23%   |
| Logitech Blue Microphones                                                  | 1        | 1.23%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.23%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 1.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.23%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.23%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.23%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 5        | 22.73%  |
| Crucial             | 4        | 18.18%  |
| Samsung Electronics | 3        | 13.64%  |
| SK hynix            | 2        | 9.09%   |
| Micron Technology   | 2        | 9.09%   |
| Corsair             | 2        | 9.09%   |
| Transcend           | 1        | 4.55%   |
| G.Skill             | 1        | 4.55%   |
| Elpida              | 1        | 4.55%   |
| A-DATA Technology   | 1        | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 8.33%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s     | 1        | 4.17%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s             | 1        | 4.17%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 4.17%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s              | 1        | 4.17%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s   | 1        | 4.17%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s    | 1        | 4.17%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 1        | 4.17%   |
| Micron RAM 16JTF51264AZ-1G4D1 4GB DIMM DDR3 1333MT/s   | 1        | 4.17%   |
| Kingston RAM KHX3000C15D4/4GX 4GB DIMM DDR4 3000MT/s   | 1        | 4.17%   |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s      | 1        | 4.17%   |
| Kingston RAM 9905403-011.A02LF 2GB DIMM DDR3 1333MT/s  | 1        | 4.17%   |
| G.Skill RAM F5-6000J3238F16G 16GB DIMM DDR5 6000MT/s   | 1        | 4.17%   |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2GB DIMM DDR3 1333MT/s    | 1        | 4.17%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s | 1        | 4.17%   |
| Crucial RAM CT8G4DFD8213.C16FAD 8GB DIMM DDR4 2133MT/s | 1        | 4.17%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s  | 1        | 4.17%   |
| Crucial RAM BLS8G4D26BFSBK.8FD 8GB DIMM DDR4 2933MT/s  | 1        | 4.17%   |
| Crucial RAM BL8G26C16U4B.8FD 8GB DIMM DDR4 2667MT/s    | 1        | 4.17%   |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s    | 1        | 4.17%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s    | 1        | 4.17%   |
| Corsair RAM CMP8GX3M2A1600C9 4GB DIMM DDR3 1333MT/s    | 1        | 4.17%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s           | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 10       | 55.56%  |
| DDR3  | 6        | 33.33%  |
| SDRAM | 1        | 5.56%   |
| DDR5  | 1        | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 15       | 88.24%  |
| SODIMM | 2        | 11.76%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 36.84%  |
| 4096  | 5        | 26.32%  |
| 16384 | 4        | 21.05%  |
| 2048  | 2        | 10.53%  |
| 32768 | 1        | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 23.81%  |
| 1333  | 3        | 14.29%  |
| 3200  | 2        | 9.52%   |
| 2667  | 2        | 9.52%   |
| 2400  | 2        | 9.52%   |
| 2133  | 2        | 9.52%   |
| 6000  | 1        | 4.76%   |
| 3600  | 1        | 4.76%   |
| 3000  | 1        | 4.76%   |
| 2933  | 1        | 4.76%   |
| 1066  | 1        | 4.76%   |

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


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 2        | 22.22%  |
| WaveRider USB 2.0 Camera                | 1        | 11.11%  |
| ValueHD Konftel Cam20                   | 1        | 11.11%  |
| Sunplus FHD Camera Microphone           | 1        | 11.11%  |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 11.11%  |
| Microdia Camera                         | 1        | 11.11%  |
| Logitech BRIO Ultra HD Webcam           | 1        | 11.11%  |
| Generalplus 808 Camera                  | 1        | 11.11%  |

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
| 0     | 34       | 80.95%  |
| 1     | 5        | 11.9%   |
| 2     | 2        | 4.76%   |
| 4     | 1        | 2.38%   |

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

