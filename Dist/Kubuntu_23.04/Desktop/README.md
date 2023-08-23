Kubuntu 23.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 23.04.

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

Total: 71

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0HY9JP A00                  | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| ASUSTek       | PRIME Z270-K                | [838f543301](https://linux-hardware.org/?probe=838f543301) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | [1b9b10c938](https://linux-hardware.org/?probe=1b9b10c938) | Aug 04, 2023 |
| HP            | 158A                        | [ae8ecc3ee7](https://linux-hardware.org/?probe=ae8ecc3ee7) | Aug 04, 2023 |
| HP            | 158A                        | [bac95226bd](https://linux-hardware.org/?probe=bac95226bd) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [6519784d61](https://linux-hardware.org/?probe=6519784d61) | Aug 01, 2023 |
| Google        | Zako                        | [66946b6b49](https://linux-hardware.org/?probe=66946b6b49) | Jul 30, 2023 |
| ASUSTek       | PRIME B450M-A II            | [22b080cd6b](https://linux-hardware.org/?probe=22b080cd6b) | Jul 29, 2023 |
| ASUSTek       | PRIME Z390-A                | [8102a251ad](https://linux-hardware.org/?probe=8102a251ad) | Jul 29, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Acer          | Aspire X3990                | [7b6b27241f](https://linux-hardware.org/?probe=7b6b27241f) | Jul 24, 2023 |
| ASRock        | B560M Pro4                  | [881853b4dc](https://linux-hardware.org/?probe=881853b4dc) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [751e776113](https://linux-hardware.org/?probe=751e776113) | Jul 23, 2023 |
| HP            | 83E9                        | [35c7f631ac](https://linux-hardware.org/?probe=35c7f631ac) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| Gigabyte      | X570S UD                    | [8fb3c405c0](https://linux-hardware.org/?probe=8fb3c405c0) | Jul 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [87a3354fc2](https://linux-hardware.org/?probe=87a3354fc2) | Jul 13, 2023 |
| MSI           | B360M MORTAR TITANIUM       | [31b2aa5991](https://linux-hardware.org/?probe=31b2aa5991) | Jul 08, 2023 |
| Pegatron      | 2AC3                        | [a2981d590e](https://linux-hardware.org/?probe=a2981d590e) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| ASUSTek       | PRIME H510M-K               | [c0b828ddc4](https://linux-hardware.org/?probe=c0b828ddc4) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| Gigabyte      | B550 AORUS PRO              | [61c278235a](https://linux-hardware.org/?probe=61c278235a) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | [48f79dc803](https://linux-hardware.org/?probe=48f79dc803) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | [9d47ca40b8](https://linux-hardware.org/?probe=9d47ca40b8) | Jul 03, 2023 |
| Gigabyte      | X570S UD                    | [22ca0e18f4](https://linux-hardware.org/?probe=22ca0e18f4) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| Gateway       | IPISB-VR                    | [73ab7736ca](https://linux-hardware.org/?probe=73ab7736ca) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [51d5b7d342](https://linux-hardware.org/?probe=51d5b7d342) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [0571943e1f](https://linux-hardware.org/?probe=0571943e1f) | Jul 01, 2023 |
| Gigabyte      | B85-HD3                     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7e7099c099](https://linux-hardware.org/?probe=7e7099c099) | Jul 01, 2023 |
| Intel         | SHARKBAY                    | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| MSI           | H81M-P32                    | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | Maximus IX HERO             | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| ASRock        | A320M-HDV R4.0              | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| ASUSTek       | PRIME H610M-E D4            | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| Seco          | C40 C                       | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| Gigabyte      | GA-MA770-US3                | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| ASUSTek       | H81M-A                      | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| MSI           | B450M PRO-M2 V2             | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| ASUSTek       | H81M-A                      | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| Alienware     | 04VWF2 A00                  | [0d6c86d757](https://linux-hardware.org/?probe=0d6c86d757) | May 25, 2023 |
| ASRock        | X99 Extreme6/ac             | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Alienware     | 04VWF2 A00                  | [7c09c55150](https://linux-hardware.org/?probe=7c09c55150) | May 21, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| HP            | 3397                        | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [094fd8b39a](https://linux-hardware.org/?probe=094fd8b39a) | May 12, 2023 |
| Intel         | H61                         | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| Biostar       | AM1MHP                      | [1f21e13fcd](https://linux-hardware.org/?probe=1f21e13fcd) | May 07, 2023 |
| Gigabyte      | H87-HD3                     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| HP            | 828A                        | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [475a4d151d](https://linux-hardware.org/?probe=475a4d151d) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [3d241113f4](https://linux-hardware.org/?probe=3d241113f4) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Unknown       | Unknown                     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| Gigabyte      | B360M HD3                   | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 6.2.0-20-generic       | 17       | 30.91%  |
| 6.2.0-24-generic       | 8        | 14.55%  |
| 6.2.0-23-generic       | 6        | 10.91%  |
| 6.2.0-26-generic       | 5        | 9.09%   |
| 6.2.0-25-generic       | 5        | 9.09%   |
| 6.2.0-1003-lowlatency  | 3        | 5.45%   |
| 6.4.3-1-liquorix-amd64 | 1        | 1.82%   |
| 6.4.1-2-liquorix-amd64 | 1        | 1.82%   |
| 6.4.0-060400-generic   | 1        | 1.82%   |
| 6.3.5-060305-generic   | 1        | 1.82%   |
| 6.3.10                 | 1        | 1.82%   |
| 6.2.5-060205-generic   | 1        | 1.82%   |
| 6.2.0-1009-lowlatency  | 1        | 1.82%   |
| 6.2.0-1008-lowlatency  | 1        | 1.82%   |
| 6.1.0-16-generic       | 1        | 1.82%   |
| 5.19.0-28-generic      | 1        | 1.82%   |
| 5.19.0-1023-lowlatency | 1        | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 46       | 83.64%  |
| 5.19.0  | 2        | 3.64%   |
| 6.4.3   | 1        | 1.82%   |
| 6.4.1   | 1        | 1.82%   |
| 6.4.0   | 1        | 1.82%   |
| 6.3.5   | 1        | 1.82%   |
| 6.3.10  | 1        | 1.82%   |
| 6.2.5   | 1        | 1.82%   |
| 6.1.0   | 1        | 1.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 47       | 85.45%  |
| 6.4     | 3        | 5.45%   |
| 6.3     | 2        | 3.64%   |
| 5.19    | 2        | 3.64%   |
| 6.1     | 1        | 1.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 54       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 52       | 96.3%   |
| KDE  | 2        | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 43       | 79.63%  |
| Wayland | 10       | 18.52%  |
| Tty     | 1        | 1.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 34       | 61.82%  |
| Unknown | 19       | 34.55%  |
| LightDM | 1        | 1.82%   |
| GDM3    | 1        | 1.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 23       | 42.59%  |
| de_DE | 7        | 12.96%  |
| en_GB | 6        | 11.11%  |
| fr_FR | 3        | 5.56%   |
| pt_BR | 2        | 3.7%    |
| zh_TW | 1        | 1.85%   |
| sv_SE | 1        | 1.85%   |
| ru_RU | 1        | 1.85%   |
| pl_PL | 1        | 1.85%   |
| it_IT | 1        | 1.85%   |
| es_MX | 1        | 1.85%   |
| es_CO | 1        | 1.85%   |
| es_CL | 1        | 1.85%   |
| en_IN | 1        | 1.85%   |
| en_IL | 1        | 1.85%   |
| en_CA | 1        | 1.85%   |
| da_DK | 1        | 1.85%   |
| C     | 1        | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 29       | 53.7%   |
| EFI  | 25       | 46.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 36       | 66.67%  |
| Tmpfs   | 11       | 20.37%  |
| Btrfs   | 5        | 9.26%   |
| Overlay | 1        | 1.85%   |
| F2fs    | 1        | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 33       | 60%     |
| Unknown | 19       | 34.55%  |
| MBR     | 3        | 5.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 81.48%  |
| Yes       | 10       | 18.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 66.67%  |
| Yes       | 18       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 29.63%  |
| Gigabyte Technology | 10       | 18.52%  |
| MSI                 | 6        | 11.11%  |
| Hewlett-Packard     | 3        | 5.56%   |
| ASRock              | 3        | 5.56%   |
| Intel               | 2        | 3.7%    |
| Fujitsu             | 2        | 3.7%    |
| Seco                | 1        | 1.85%   |
| Pegatron            | 1        | 1.85%   |
| Huanan              | 1        | 1.85%   |
| Google              | 1        | 1.85%   |
| Gateway             | 1        | 1.85%   |
| Foxconn             | 1        | 1.85%   |
| Dell                | 1        | 1.85%   |
| Biostar             | 1        | 1.85%   |
| BESSTAR Tech        | 1        | 1.85%   |
| Alienware           | 1        | 1.85%   |
| Acer                | 1        | 1.85%   |
| Unknown             | 1        | 1.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seco C40                          | 1        | 1.85%   |
| Pegatron 520-1000nl               | 1        | 1.85%   |
| MSI MS-7D75                       | 1        | 1.85%   |
| MSI MS-7C95                       | 1        | 1.85%   |
| MSI MS-7B23                       | 1        | 1.85%   |
| MSI MS-7A32                       | 1        | 1.85%   |
| MSI MS-7846                       | 1        | 1.85%   |
| MSI MS-7693                       | 1        | 1.85%   |
| Intel SHARKBAY                    | 1        | 1.85%   |
| Intel H61                         | 1        | 1.85%   |
| Huanan X99-F8 GAMING V5.0         | 1        | 1.85%   |
| HP EliteDesk 705 G4 DM 35W (TAA)  | 1        | 1.85%   |
| HP Compaq Elite 8300 SFF          | 1        | 1.85%   |
| HP 870-119                        | 1        | 1.85%   |
| Google Zako                       | 1        | 1.85%   |
| Gigabyte X570S UD                 | 1        | 1.85%   |
| Gigabyte X570S AORUS ELITE AX     | 1        | 1.85%   |
| Gigabyte H87-HD3                  | 1        | 1.85%   |
| Gigabyte GA-MA770-US3             | 1        | 1.85%   |
| Gigabyte B550 AORUS PRO           | 1        | 1.85%   |
| Gigabyte B550 AORUS ELITE V2      | 1        | 1.85%   |
| Gigabyte B365M H                  | 1        | 1.85%   |
| Gigabyte B360M-HD3                | 1        | 1.85%   |
| Gigabyte A320M-S2H                | 1        | 1.85%   |
| Gigabyte 7200-5143A               | 1        | 1.85%   |
| Gateway DX4860                    | 1        | 1.85%   |
| Fujitsu ESPRIMO D538              | 1        | 1.85%   |
| Fujitsu D3222-B1                  | 1        | 1.85%   |
| Foxconn H67M-S/H67M-V/H67         | 1        | 1.85%   |
| Dell OptiPlex 790                 | 1        | 1.85%   |
| Biostar AM1MHP                    | 1        | 1.85%   |
| BESSTAR Tech UM700                | 1        | 1.85%   |
| ASUS TUF Gaming X570-PLUS         | 1        | 1.85%   |
| ASUS TUF Gaming B550-PLUS         | 1        | 1.85%   |
| ASUS ROG STRIX B560-A GAMING WIFI | 1        | 1.85%   |
| ASUS ROG STRIX B550-F GAMING      | 1        | 1.85%   |
| ASUS ROG STRIX B450-F GAMING II   | 1        | 1.85%   |
| ASUS PRIME Z390-A                 | 1        | 1.85%   |
| ASUS PRIME Z270-K                 | 1        | 1.85%   |
| ASUS PRIME H610M-E D4             | 1        | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 8        | 14.81%  |
| ASUS ROG              | 3        | 5.56%   |
| Gigabyte X570S        | 2        | 3.7%    |
| Gigabyte B550         | 2        | 3.7%    |
| ASUS TUF              | 2        | 3.7%    |
| Seco C40              | 1        | 1.85%   |
| Pegatron 520-1000nl   | 1        | 1.85%   |
| MSI MS-7D75           | 1        | 1.85%   |
| MSI MS-7C95           | 1        | 1.85%   |
| MSI MS-7B23           | 1        | 1.85%   |
| MSI MS-7A32           | 1        | 1.85%   |
| MSI MS-7846           | 1        | 1.85%   |
| MSI MS-7693           | 1        | 1.85%   |
| Intel SHARKBAY        | 1        | 1.85%   |
| Intel H61             | 1        | 1.85%   |
| Huanan X99-F8         | 1        | 1.85%   |
| HP EliteDesk          | 1        | 1.85%   |
| HP Compaq             | 1        | 1.85%   |
| HP 870-119            | 1        | 1.85%   |
| Google Zako           | 1        | 1.85%   |
| Gigabyte H87-HD3      | 1        | 1.85%   |
| Gigabyte GA-MA770-US3 | 1        | 1.85%   |
| Gigabyte B365M        | 1        | 1.85%   |
| Gigabyte B360M-HD3    | 1        | 1.85%   |
| Gigabyte A320M-S2H    | 1        | 1.85%   |
| Gigabyte 7200-5143A   | 1        | 1.85%   |
| Gateway DX4860        | 1        | 1.85%   |
| Fujitsu ESPRIMO       | 1        | 1.85%   |
| Fujitsu D3222-B1      | 1        | 1.85%   |
| Foxconn H67M-S        | 1        | 1.85%   |
| Dell OptiPlex         | 1        | 1.85%   |
| Biostar AM1MHP        | 1        | 1.85%   |
| BESSTAR Tech UM700    | 1        | 1.85%   |
| ASUS Maximus          | 1        | 1.85%   |
| ASUS M5A78L-M         | 1        | 1.85%   |
| ASUS All              | 1        | 1.85%   |
| ASRock X99            | 1        | 1.85%   |
| ASRock B560M          | 1        | 1.85%   |
| ASRock A320M-HDV      | 1        | 1.85%   |
| Alienware Aurora      | 1        | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 9        | 16.67%  |
| 2020 | 8        | 14.81%  |
| 2021 | 7        | 12.96%  |
| 2018 | 5        | 9.26%   |
| 2011 | 5        | 9.26%   |
| 2017 | 4        | 7.41%   |
| 2022 | 3        | 5.56%   |
| 2013 | 3        | 5.56%   |
| 2016 | 2        | 3.7%    |
| 2014 | 2        | 3.7%    |
| 2012 | 2        | 3.7%    |
| 2023 | 1        | 1.85%   |
| 2015 | 1        | 1.85%   |
| 2010 | 1        | 1.85%   |
| 2009 | 1        | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 54       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 53       | 98.15%  |
| Enabled  | 1        | 1.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 98.15%  |
| Yes  | 1        | 1.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 17       | 31.48%  |
| 16.01-24.0  | 13       | 24.07%  |
| 8.01-16.0   | 9        | 16.67%  |
| 4.01-8.0    | 7        | 12.96%  |
| 64.01-256.0 | 4        | 7.41%   |
| 3.01-4.0    | 3        | 5.56%   |
| 24.01-32.0  | 1        | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 19       | 33.93%  |
| 2.01-3.0  | 11       | 19.64%  |
| 1.01-2.0  | 11       | 19.64%  |
| 3.01-4.0  | 8        | 14.29%  |
| 8.01-16.0 | 7        | 12.5%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 15       | 27.78%  |
| 1      | 14       | 25.93%  |
| 3      | 12       | 22.22%  |
| 4      | 8        | 14.81%  |
| 7      | 2        | 3.7%    |
| 5      | 2        | 3.7%    |
| 6      | 1        | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 62.96%  |
| Yes       | 20       | 37.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 54       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 27       | 50%     |
| No        | 27       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 68.52%  |
| Yes       | 17       | 31.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 11       | 20.37%  |
| Germany      | 9        | 16.67%  |
| UK           | 7        | 12.96%  |
| France       | 4        | 7.41%   |
| Sweden       | 2        | 3.7%    |
| Serbia       | 2        | 3.7%    |
| Canada       | 2        | 3.7%    |
| Brazil       | 2        | 3.7%    |
| Taiwan       | 1        | 1.85%   |
| Spain        | 1        | 1.85%   |
| Saudi Arabia | 1        | 1.85%   |
| Russia       | 1        | 1.85%   |
| Romania      | 1        | 1.85%   |
| Poland       | 1        | 1.85%   |
| Netherlands  | 1        | 1.85%   |
| Mexico       | 1        | 1.85%   |
| Italy        | 1        | 1.85%   |
| Israel       | 1        | 1.85%   |
| Indonesia    | 1        | 1.85%   |
| India        | 1        | 1.85%   |
| Denmark      | 1        | 1.85%   |
| Colombia     | 1        | 1.85%   |
| Chile        | 1        | 1.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| London         | 3        | 5.56%   |
| Hamburg        | 2        | 3.7%    |
| Wiesmoor       | 1        | 1.85%   |
| West Valley    | 1        | 1.85%   |
| Weilmuenster   | 1        | 1.85%   |
| Virginia Beach | 1        | 1.85%   |
| The Hague      | 1        | 1.85%   |
| Taichung       | 1        | 1.85%   |
| Sutton         | 1        | 1.85%   |
| Sundsvall      | 1        | 1.85%   |
| Strasbourg     | 1        | 1.85%   |
| Sibiu          | 1        | 1.85%   |
| Sherbrooke     | 1        | 1.85%   |
| Santiago       | 1        | 1.85%   |
| San Jose       | 1        | 1.85%   |
| Rzeszów       | 1        | 1.85%   |
| Porto Alegre   | 1        | 1.85%   |
| Pasco          | 1        | 1.85%   |
| Pančevo       | 1        | 1.85%   |
| Orbassano      | 1        | 1.85%   |
| Oberursel      | 1        | 1.85%   |
| Niebla         | 1        | 1.85%   |
| Minneapolis    | 1        | 1.85%   |
| Middlesbrough  | 1        | 1.85%   |
| Metepec        | 1        | 1.85%   |
| Marshalltown   | 1        | 1.85%   |
| Marcoussis     | 1        | 1.85%   |
| Lucknow        | 1        | 1.85%   |
| Lübeck        | 1        | 1.85%   |
| Losning        | 1        | 1.85%   |
| Lexington      | 1        | 1.85%   |
| Leipzig        | 1        | 1.85%   |
| Lazarevac      | 1        | 1.85%   |
| La Mesa        | 1        | 1.85%   |
| Kaliningrad    | 1        | 1.85%   |
| Itaborai       | 1        | 1.85%   |
| Helsingborg    | 1        | 1.85%   |
| Ensdorf        | 1        | 1.85%   |
| Dudley         | 1        | 1.85%   |
| Dammam         | 1        | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 18       | 30     | 16.07%  |
| WDC                         | 16       | 20     | 14.29%  |
| Samsung Electronics         | 16       | 28     | 14.29%  |
| SanDisk                     | 6        | 6      | 5.36%   |
| Kingston                    | 6        | 8      | 5.36%   |
| Crucial                     | 4        | 6      | 3.57%   |
| Toshiba                     | 3        | 3      | 2.68%   |
| Intel                       | 3        | 3      | 2.68%   |
| HGST                        | 3        | 3      | 2.68%   |
| A-DATA Technology           | 3        | 3      | 2.68%   |
| Silicon Motion              | 2        | 2      | 1.79%   |
| PNY                         | 2        | 2      | 1.79%   |
| Phison Electronics          | 2        | 2      | 1.79%   |
| Maxtor                      | 2        | 2      | 1.79%   |
| Kingston Technology Company | 2        | 2      | 1.79%   |
| Hitachi                     | 2        | 2      | 1.79%   |
| China                       | 2        | 2      | 1.79%   |
| ADATA Technology            | 2        | 2      | 1.79%   |
| Vaseky                      | 1        | 1      | 0.89%   |
| Unknown                     | 1        | 1      | 0.89%   |
| Transcend                   | 1        | 1      | 0.89%   |
| Team                        | 1        | 1      | 0.89%   |
| SPCC                        | 1        | 5      | 0.89%   |
| Realtek Semiconductor       | 1        | 1      | 0.89%   |
| PHD 3.0                     | 1        | 1      | 0.89%   |
| Patriot                     | 1        | 1      | 0.89%   |
| Micron/Crucial Technology   | 1        | 2      | 0.89%   |
| Micron Technology           | 1        | 1      | 0.89%   |
| Lexar                       | 1        | 1      | 0.89%   |
| INNOVATION IT               | 1        | 1      | 0.89%   |
| Hoodisk                     | 1        | 1      | 0.89%   |
| Hewlett-Packard             | 1        | 1      | 0.89%   |
| Gigabyte Technology         | 1        | 1      | 0.89%   |
| CT1000MX                    | 1        | 1      | 0.89%   |
| Corsair                     | 1        | 1      | 0.89%   |
| Unknown                     | 1        | 1      | 0.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Seagate ST4000DM004-2CV104 4TB                                     | 3        | 2.19%   |
| Seagate ST1000DM003-1CH162 1TB                                     | 3        | 2.19%   |
| WDC WD5000AAKX-60U6AA0 500GB                                       | 2        | 1.46%   |
| Seagate ST2000DM008-2FR102 2TB                                     | 2        | 1.46%   |
| Seagate ST1000DM003-1ER162 1TB                                     | 2        | 1.46%   |
| Samsung SSD 980 PRO 2TB                                            | 2        | 1.46%   |
| Samsung SSD 980 1TB                                                | 2        | 1.46%   |
| Samsung SSD 870 QVO 2TB                                            | 2        | 1.46%   |
| Samsung SSD 850 EVO 250GB                                          | 2        | 1.46%   |
| Phison PS5013 E13 NVMe Controller 256GB                            | 2        | 1.46%   |
| Kingston SA400S37120G 120GB SSD                                    | 2        | 1.46%   |
| Hitachi HDP725050GLA360 500GB                                      | 2        | 1.46%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 2        | 1.46%   |
| WDC WUH721818ALE6L4 18TB                                           | 1        | 0.73%   |
| WDC WDS500G2B0A 500GB SSD                                          | 1        | 0.73%   |
| WDC WDS200T2B0A-00SM50 2TB SSD                                     | 1        | 0.73%   |
| WDC WD40EZAZ-00SF3B0 4TB                                           | 1        | 0.73%   |
| WDC WD3200AAJS-65M0A0 320GB                                        | 1        | 0.73%   |
| WDC WD20EURX-63T0FY0 2TB                                           | 1        | 0.73%   |
| WDC WD20EARX-00PASB0 2TB                                           | 1        | 0.73%   |
| WDC WD20EARS-60MVWB0 2TB                                           | 1        | 0.73%   |
| WDC WD10EZRZ-00HTKB0 1TB                                           | 1        | 0.73%   |
| WDC WD10EZEX-08M2NA0 1TB                                           | 1        | 0.73%   |
| WDC WD10EURX-63UY4Y0 1TB                                           | 1        | 0.73%   |
| WDC WD10EURX-63C57Y0 1TB                                           | 1        | 0.73%   |
| WDC WD10EFRX-68JCSN0 1TB                                           | 1        | 0.73%   |
| WDC WD10EAVS-32D7B1 1TB                                            | 1        | 0.73%   |
| WDC WD Green 2.5 1000GB                                            | 1        | 0.73%   |
| WDC WD Blue SA510 2.5 1000GB SSD                                   | 1        | 0.73%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB                               | 1        | 0.73%   |
| Vaseky V900/256G 256GB                                             | 1        | 0.73%   |
| Unknown SD/MMC/MS PRO 128GB                                        | 1        | 0.73%   |
| Transcend TS32GSSD420K 32GB                                        | 1        | 0.73%   |
| Toshiba MQ01ABD050 500GB                                           | 1        | 0.73%   |
| Toshiba HDWD110 1TB                                                | 1        | 0.73%   |
| Toshiba DT01ACA100 1TB                                             | 1        | 0.73%   |
| Team T2531TB 1024GB SSD                                            | 1        | 0.73%   |
| SPCC Solid State Disk 512GB                                        | 1        | 0.73%   |
| SPCC Solid State Disk 2TB                                          | 1        | 0.73%   |
| SPCC Solid State Disk 256GB                                        | 1        | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 29     | 40.91%  |
| WDC                 | 12       | 15     | 27.27%  |
| Toshiba             | 3        | 3      | 6.82%   |
| HGST                | 3        | 3      | 6.82%   |
| Samsung Electronics | 2        | 2      | 4.55%   |
| Maxtor              | 2        | 2      | 4.55%   |
| Hitachi             | 2        | 2      | 4.55%   |
| Unknown             | 1        | 1      | 2.27%   |
| PHD 3.0             | 1        | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 15     | 16.67%  |
| Kingston            | 5        | 7      | 11.9%   |
| WDC                 | 4        | 4      | 9.52%   |
| SanDisk             | 3        | 3      | 7.14%   |
| A-DATA Technology   | 3        | 3      | 7.14%   |
| PNY                 | 2        | 2      | 4.76%   |
| Intel               | 2        | 2      | 4.76%   |
| Crucial             | 2        | 4      | 4.76%   |
| China               | 2        | 2      | 4.76%   |
| Vaseky              | 1        | 1      | 2.38%   |
| Transcend           | 1        | 1      | 2.38%   |
| Team                | 1        | 1      | 2.38%   |
| SPCC                | 1        | 5      | 2.38%   |
| Seagate             | 1        | 1      | 2.38%   |
| Patriot             | 1        | 1      | 2.38%   |
| Micron Technology   | 1        | 1      | 2.38%   |
| INNOVATION IT       | 1        | 1      | 2.38%   |
| Hoodisk             | 1        | 1      | 2.38%   |
| Hewlett-Packard     | 1        | 1      | 2.38%   |
| Gigabyte Technology | 1        | 1      | 2.38%   |
| CT1000MX            | 1        | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 39       | 58     | 41.49%  |
| HDD     | 31       | 58     | 32.98%  |
| NVMe    | 23       | 32     | 24.47%  |
| Unknown | 1        | 1      | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 49       | 110    | 62.03%  |
| NVMe | 23       | 32     | 29.11%  |
| SAS  | 7        | 7      | 8.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 36       | 52     | 44.44%  |
| 0.51-1.0   | 24       | 36     | 29.63%  |
| 1.01-2.0   | 13       | 19     | 16.05%  |
| 3.01-4.0   | 5        | 6      | 6.17%   |
| 4.01-10.0  | 2        | 2      | 2.47%   |
| 10.01-20.0 | 1        | 1      | 1.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 11       | 20%     |
| 501-1000       | 11       | 20%     |
| 251-500        | 10       | 18.18%  |
| More than 3000 | 9        | 16.36%  |
| 2001-3000      | 5        | 9.09%   |
| 1001-2000      | 5        | 9.09%   |
| 1-20           | 2        | 3.64%   |
| 21-50          | 1        | 1.82%   |
| 51-100         | 1        | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 10       | 18.18%  |
| 21-50          | 10       | 18.18%  |
| 1-20           | 8        | 14.55%  |
| 501-1000       | 8        | 14.55%  |
| 101-250        | 7        | 12.73%  |
| More than 3000 | 5        | 9.09%   |
| 51-100         | 4        | 7.27%   |
| 1001-2000      | 3        | 5.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD3200AAJS-65M0A0 320GB                  | 1        | 1      | 10%     |
| WDC WD10EURX-63UY4Y0 1TB                     | 1        | 1      | 10%     |
| WDC WD Blue SA510 2.5 1000GB SSD             | 1        | 1      | 10%     |
| Seagate ST1000DM003-1CH162 1TB               | 1        | 1      | 10%     |
| Samsung Electronics SSD 850 EVO 250GB        | 1        | 1      | 10%     |
| Samsung Electronics SSD 840 PRO Series 256GB | 1        | 2      | 10%     |
| Samsung Electronics HD103SI 1TB              | 1        | 1      | 10%     |
| Maxtor STM3160215AS 160GB                    | 1        | 1      | 10%     |
| Intel SSDSCKKW240H6 240GB                    | 1        | 1      | 10%     |
| Intel SSDPEKNW512G8 512GB                    | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 30%     |
| Samsung Electronics | 3        | 4      | 30%     |
| Intel               | 2        | 2      | 20%     |
| Seagate             | 1        | 1      | 10%     |
| Maxtor              | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 40%     |
| Seagate             | 1        | 1      | 20%     |
| Samsung Electronics | 1        | 1      | 20%     |
| Maxtor              | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 3        | 5      | 42.86%  |
| HDD  | 3        | 5      | 42.86%  |
| NVMe | 1        | 1      | 14.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 960 EVO 250GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 34       | 92     | 52.31%  |
| Works    | 23       | 44     | 35.38%  |
| Malfunc  | 7        | 11     | 10.77%  |
| Failed   | 1        | 2      | 1.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 31       | 36.47%  |
| AMD                          | 23       | 27.06%  |
| Samsung Electronics          | 9        | 10.59%  |
| SanDisk                      | 4        | 4.71%   |
| Phison Electronics           | 3        | 3.53%   |
| Micron/Crucial Technology    | 3        | 3.53%   |
| Silicon Motion               | 2        | 2.35%   |
| Kingston Technology Company  | 2        | 2.35%   |
| ASMedia Technology           | 2        | 2.35%   |
| ADATA Technology             | 2        | 2.35%   |
| Silicon Image                | 1        | 1.18%   |
| Shenzhen Longsys Electronics | 1        | 1.18%   |
| Realtek Semiconductor        | 1        | 1.18%   |
| JMicron Technology           | 1        | 1.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 14       | 14.29%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 6.12%   |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 5.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4        | 4.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 4.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 3.06%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 3.06%   |
| AMD FCH SATA Controller D                                                      | 3        | 3.06%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 3.06%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2        | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 2.04%   |
| Samsung NVMe SSD Controller 980                                                | 2        | 2.04%   |
| Phison PS5013 E13 NVMe Controller                                              | 2        | 2.04%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 2.04%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 2.04%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 2.04%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2        | 2.04%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 1.02%   |
| Shenzhen Longsys Lexar NM760 NVME SSD (DRAM-less)                              | 1        | 1.02%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 1        | 1.02%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 1.02%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 1.02%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1        | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 1.02%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 1.02%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 1.02%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 1        | 1.02%   |
| Kingston Company Company Non-Volatile memory controller                        | 1        | 1.02%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1        | 1.02%   |
| Kingston Company NVMe Controller                                               | 1        | 1.02%   |
| JMicron JMB58x AHCI SATA controller                                            | 1        | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 1.02%   |
| Intel SSD 660P Series                                                          | 1        | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.02%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 1.02%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                     | 1        | 1.02%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 1.02%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 52       | 65%     |
| NVMe | 23       | 28.75%  |
| RAID | 3        | 3.75%   |
| IDE  | 2        | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 57.41%  |
| AMD    | 23       | 42.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz                | 2        | 3.7%    |
| Intel Core i7-7700K CPU @ 4.20GHz               | 2        | 3.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz                | 2        | 3.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz                | 2        | 3.7%    |
| AMD Ryzen 9 5900X 12-Core Processor             | 2        | 3.7%    |
| AMD Ryzen 7 5700X 8-Core Processor              | 2        | 3.7%    |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 3.7%    |
| Intel Xeon CPU E5-4627 v4 @ 2.60GHz             | 1        | 1.85%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz             | 1        | 1.85%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz          | 1        | 1.85%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 1        | 1.85%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1        | 1.85%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 1.85%   |
| Intel Core i7-5820K CPU @ 3.30GHz               | 1        | 1.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 1.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1        | 1.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 1.85%   |
| Intel Core i7 CPU 920 @ 2.67GHz                 | 1        | 1.85%   |
| Intel Core i5-9600KF CPU @ 3.70GHz              | 1        | 1.85%   |
| Intel Core i5-8500 CPU @ 3.00GHz                | 1        | 1.85%   |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 1.85%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 1.85%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1        | 1.85%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1        | 1.85%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 1.85%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.85%   |
| Intel Celeron N5105 @ 2.00GHz                   | 1        | 1.85%   |
| Intel 13th Gen Core i3-13100                    | 1        | 1.85%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz         | 1        | 1.85%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 1        | 1.85%   |
| AMD Ryzen Embedded V1605B with Radeon Vega Gfx  | 1        | 1.85%   |
| AMD Ryzen 9 7950X3D 16-Core Processor           | 1        | 1.85%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1        | 1.85%   |
| AMD Ryzen 7 5800X3D 8-Core Processor            | 1        | 1.85%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 1.85%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 1        | 1.85%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx   | 1        | 1.85%   |
| AMD Ryzen 5 PRO 3350G with Radeon Vega Graphics | 1        | 1.85%   |
| AMD Ryzen 5 PRO 2400GE w/ Radeon Vega Graphics  | 1        | 1.85%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1        | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i7      | 13       | 24.07%  |
| Intel Core i5      | 9        | 16.67%  |
| AMD Ryzen 7        | 6        | 11.11%  |
| AMD Ryzen 5        | 5        | 9.26%   |
| AMD Ryzen 9        | 4        | 7.41%   |
| Other              | 3        | 5.56%   |
| Intel Xeon         | 2        | 3.7%    |
| AMD Ryzen 5 PRO    | 2        | 3.7%    |
| AMD FX             | 2        | 3.7%    |
| Intel Pentium Gold | 1        | 1.85%   |
| Intel Pentium      | 1        | 1.85%   |
| Intel Core i3      | 1        | 1.85%   |
| Intel Celeron      | 1        | 1.85%   |
| AMD Ryzen Embedded | 1        | 1.85%   |
| AMD Ryzen 3 PRO    | 1        | 1.85%   |
| AMD Athlon II X3   | 1        | 1.85%   |
| AMD Athlon         | 1        | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 24       | 44.44%  |
| 6      | 12       | 22.22%  |
| 8      | 7        | 12.96%  |
| 2      | 4        | 7.41%   |
| 16     | 2        | 3.7%    |
| 12     | 2        | 3.7%    |
| 3      | 2        | 3.7%    |
| 10     | 1        | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 54       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 38       | 70.37%  |
| 1      | 16       | 29.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 54       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 44       | 80%     |
| 0x0a20120a | 2        | 3.64%   |
| 0x08701021 | 2        | 3.64%   |
| 0x0a601203 | 1        | 1.82%   |
| 0x0a50000d | 1        | 1.82%   |
| 0x0a201025 | 1        | 1.82%   |
| 0x0810100b | 1        | 1.82%   |
| 0x0800820d | 1        | 1.82%   |
| 0x0700010f | 1        | 1.82%   |
| 0x06000852 | 1        | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 9        | 16.67%  |
| KabyLake    | 8        | 14.81%  |
| Haswell     | 8        | 14.81%  |
| SandyBridge | 5        | 9.26%   |
| Zen+        | 4        | 7.41%   |
| Zen 2       | 3        | 5.56%   |
| Unknown     | 3        | 5.56%   |
| Zen         | 2        | 3.7%    |
| Piledriver  | 2        | 3.7%    |
| IvyBridge   | 2        | 3.7%    |
| Tremont     | 1        | 1.85%   |
| Skylake     | 1        | 1.85%   |
| Nehalem     | 1        | 1.85%   |
| K10         | 1        | 1.85%   |
| Jaguar      | 1        | 1.85%   |
| Icelake     | 1        | 1.85%   |
| CometLake   | 1        | 1.85%   |
| Broadwell   | 1        | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 25       | 42.37%  |
| Nvidia | 19       | 32.2%   |
| Intel  | 15       | 25.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 8.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 5.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 5.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 5.08%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 5.08%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 3.39%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 3.39%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 3.39%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2        | 3.39%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.69%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 1.69%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.69%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 1.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.69%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.69%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.69%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.69%   |
| Nvidia GF108 [GeForce GT 530]                                               | 1        | 1.69%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.69%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.69%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 1.69%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.69%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 1.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.69%   |
| Intel HD Graphics 630                                                       | 1        | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.69%   |
| Intel DG2 [Arc A380]                                                        | 1        | 1.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.69%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.69%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 1.69%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.69%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.69%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 1        | 1.69%   |
| AMD Navi 21 [Radeon RX 6950 XT]                                             | 1        | 1.69%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.69%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.69%   |
| AMD Cypress PRO [Radeon HD 5850]                                            | 1        | 1.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 22       | 40.74%  |
| 1 x Nvidia      | 18       | 33.33%  |
| 1 x Intel       | 11       | 20.37%  |
| Intel + AMD     | 2        | 3.7%    |
| Intel + 2 x AMD | 1        | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 40       | 74.07%  |
| Proprietary | 14       | 25.93%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 53.7%   |
| 7.01-8.0   | 7        | 12.96%  |
| 1.01-2.0   | 7        | 12.96%  |
| 3.01-4.0   | 4        | 7.41%   |
| 8.01-16.0  | 4        | 7.41%   |
| 5.01-6.0   | 2        | 3.7%    |
| 16.01-24.0 | 1        | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Iiyama               | 8        | 13.56%  |
| Dell                 | 7        | 11.86%  |
| Hewlett-Packard      | 6        | 10.17%  |
| Samsung Electronics  | 5        | 8.47%   |
| ASUSTek Computer     | 5        | 8.47%   |
| Philips              | 4        | 6.78%   |
| Acer                 | 4        | 6.78%   |
| AOC                  | 3        | 5.08%   |
| Ancor Communications | 3        | 5.08%   |
| Lenovo               | 2        | 3.39%   |
| Goldstar             | 2        | 3.39%   |
| BenQ                 | 2        | 3.39%   |
| VIZ                  | 1        | 1.69%   |
| RTK                  | 1        | 1.69%   |
| ONN                  | 1        | 1.69%   |
| Medion Akoya         | 1        | 1.69%   |
| INS                  | 1        | 1.69%   |
| Gigabyte Technology  | 1        | 1.69%   |
| GDH                  | 1        | 1.69%   |
| DENON                | 1        | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Iiyama PL3288UH IVM1176 3840x2160 698x393mm 31.5-inch                | 2        | 2.9%    |
| Iiyama PL2783Q IVM661E 2560x1440 597x336mm 27.0-inch                 | 2        | 2.9%    |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                    | 2        | 2.9%    |
| VIZ LCD Monitor D32h-J04 1920x1080                                   | 1        | 1.45%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch    | 1        | 1.45%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch | 1        | 1.45%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch   | 1        | 1.45%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch   | 1        | 1.45%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1        | 1.45%   |
| Samsung Electronics S24B150 SAM0983 1920x1080 521x293mm 23.5-inch    | 1        | 1.45%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1        | 1.45%   |
| Samsung Electronics LCD Monitor SAM0679 1360x768 410x256mm 19.0-inch | 1        | 1.45%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                    | 1        | 1.45%   |
| Philips PHL 241B8Q PHL0929 1920x1080 527x296mm 23.8-inch             | 1        | 1.45%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1        | 1.45%   |
| Philips 27M1N3200V PHLC279 1920x1080 598x336mm 27.0-inch             | 1        | 1.45%   |
| Philips 191V PHL0887 1366x768 409x230mm 18.5-inch                    | 1        | 1.45%   |
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                  | 1        | 1.45%   |
| Medion Akoya MD20491 MEC5201 1920x1080 521x293mm 23.5-inch           | 1        | 1.45%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch             | 1        | 1.45%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                | 1        | 1.45%   |
| INS WT70CA612 INS3694 3840x2160 1538x865mm 69.5-inch                 | 1        | 1.45%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                | 1        | 1.45%   |
| Iiyama PL2791Q IVM6647 2560x1440 597x336mm 27.0-inch                 | 1        | 1.45%   |
| Iiyama PL2791Q IVM6646 2560x1440 597x336mm 27.0-inch                 | 1        | 1.45%   |
| Iiyama PL2760Q IVM663D 2560x1440 597x336mm 27.0-inch                 | 1        | 1.45%   |
| Iiyama PL2480H IVM610B 1920x1080 521x293mm 23.5-inch                 | 1        | 1.45%   |
| Iiyama PL2451 IVM610A 1920x1080 521x293mm 23.5-inch                  | 1        | 1.45%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                | 1        | 1.45%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch           | 1        | 1.45%   |
| Hewlett-Packard V198bz HWP3317 1366x768 410x230mm 18.5-inch          | 1        | 1.45%   |
| Hewlett-Packard P204v HPN3633 1600x900 432x240mm 19.5-inch           | 1        | 1.45%   |
| Hewlett-Packard P204 HPN3630 1600x900 432x240mm 19.5-inch            | 1        | 1.45%   |
| Hewlett-Packard M24fw FHD HPN3708 1920x1080 527x296mm 23.8-inch      | 1        | 1.45%   |
| Hewlett-Packard 24m HPN3577 1920x1080 527x297mm 23.8-inch            | 1        | 1.45%   |
| Hewlett-Packard 2311 HWP2939 1920x1080 509x286mm 23.0-inch           | 1        | 1.45%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 1        | 1.45%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 1        | 1.45%   |
| Gigabyte Technology M34WQ GBT3402 3440x1440 800x335mm 34.1-inch      | 1        | 1.45%   |
| GDH PHILCO GDH0030 1440x900 708x398mm 32.0-inch                      | 1        | 1.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 28       | 45.9%   |
| 3840x2160 (4K)     | 9        | 14.75%  |
| 2560x1440 (QHD)    | 7        | 11.48%  |
| 1600x900 (HD+)     | 4        | 6.56%   |
| 1366x768 (WXGA)    | 3        | 4.92%   |
| 3440x1440          | 2        | 3.28%   |
| 1920x1200 (WUXGA)  | 2        | 3.28%   |
| 1440x900 (WXGA+)   | 2        | 3.28%   |
| 2560x1600          | 1        | 1.64%   |
| 2560x1080          | 1        | 1.64%   |
| 1680x1050 (WSXGA+) | 1        | 1.64%   |
| 1360x768           | 1        | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 13       | 20.63%  |
| 24      | 13       | 20.63%  |
| 31      | 7        | 11.11%  |
| 23      | 7        | 11.11%  |
| 19      | 6        | 9.52%   |
| 21      | 5        | 7.94%   |
| 34      | 3        | 4.76%   |
| 18      | 3        | 4.76%   |
| 69      | 1        | 1.59%   |
| 52      | 1        | 1.59%   |
| 33      | 1        | 1.59%   |
| 22      | 1        | 1.59%   |
| 20      | 1        | 1.59%   |
| Unknown | 1        | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 30       | 50%     |
| 401-500     | 14       | 23.33%  |
| 601-700     | 9        | 15%     |
| 701-800     | 4        | 6.67%   |
| 1501-2000   | 1        | 1.67%   |
| 1001-1500   | 1        | 1.67%   |
| Unknown     | 1        | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 45       | 81.82%  |
| 16/10   | 6        | 10.91%  |
| 21/9    | 3        | 5.45%   |
| Unknown | 1        | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 32.26%  |
| 301-350        | 13       | 20.97%  |
| 351-500        | 11       | 17.74%  |
| 151-200        | 8        | 12.9%   |
| 251-300        | 4        | 6.45%   |
| 141-150        | 3        | 4.84%   |
| More than 1000 | 2        | 3.23%   |
| Unknown        | 1        | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 34       | 61.82%  |
| 101-120 | 12       | 21.82%  |
| 121-160 | 6        | 10.91%  |
| 1-50    | 1        | 1.82%   |
| 161-240 | 1        | 1.82%   |
| Unknown | 1        | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 74.07%  |
| 2     | 11       | 20.37%  |
| 3     | 2        | 3.7%    |
| 4     | 1        | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 39       | 46.43%  |
| Intel                 | 19       | 22.62%  |
| TP-Link               | 4        | 4.76%   |
| Qualcomm Atheros      | 4        | 4.76%   |
| MediaTek              | 4        | 4.76%   |
| Ralink                | 3        | 3.57%   |
| Broadcom              | 3        | 3.57%   |
| ASUSTek Computer      | 3        | 3.57%   |
| Texas Instruments     | 1        | 1.19%   |
| QinHeng Electronics   | 1        | 1.19%   |
| Huawei Technologies   | 1        | 1.19%   |
| Google                | 1        | 1.19%   |
| Aquantia              | 1        | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 28       | 30.43%  |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 7.61%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 2.17%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 2        | 2.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 2.17%   |
| Intel Wireless 7265                                                           | 2        | 2.17%   |
| Intel I211 Gigabit Network Connection                                         | 2        | 2.17%   |
| Intel Ethernet Controller I225-V                                              | 2        | 2.17%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2.17%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 2.17%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 1.09%   |
| TP-Link 802.11n NIC                                                           | 1        | 1.09%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 1.09%   |
| Texas Instruments TI CC2540 USB CDC                                           | 1        | 1.09%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1        | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 1.09%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1        | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 1.09%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 1.09%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 1.09%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 1.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 1.09%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 1.09%   |
| QinHeng USB Single Serial                                                     | 1        | 1.09%   |
| MediaTek WiFi                                                                 | 1        | 1.09%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1        | 1.09%   |
| Intel Wireless-AC 9260                                                        | 1        | 1.09%   |
| Intel Wireless 8260                                                           | 1        | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 1.09%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 1.09%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 1.09%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 1.09%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 1.09%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 1.09%   |
| Huawei WLZ-AN00                                                               | 1        | 1.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 20.69%  |
| TP-Link               | 4        | 13.79%  |
| Realtek Semiconductor | 4        | 13.79%  |
| MediaTek              | 4        | 13.79%  |
| Ralink                | 3        | 10.34%  |
| Qualcomm Atheros      | 3        | 10.34%  |
| ASUSTek Computer      | 3        | 10.34%  |
| Broadcom              | 2        | 6.9%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 6.67%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 2        | 6.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 6.67%   |
| Intel Wireless 7265                                                           | 2        | 6.67%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 3.33%   |
| TP-Link 802.11n NIC                                                           | 1        | 3.33%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 3.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1        | 3.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 3.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1        | 3.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 3.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 3.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 3.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 3.33%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 3.33%   |
| MediaTek WiFi                                                                 | 1        | 3.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1        | 3.33%   |
| Intel Wireless-AC 9260                                                        | 1        | 3.33%   |
| Intel Wireless 8260                                                           | 1        | 3.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 3.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 3.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 3.33%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1        | 3.33%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]                | 1        | 3.33%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                | 1        | 3.33%   |
| ASUS 802.11ac NIC                                                             | 1        | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 38       | 64.41%  |
| Intel                 | 15       | 25.42%  |
| Qualcomm Atheros      | 2        | 3.39%   |
| Huawei Technologies   | 1        | 1.69%   |
| Google                | 1        | 1.69%   |
| Broadcom              | 1        | 1.69%   |
| Aquantia              | 1        | 1.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28       | 46.67%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 11.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 3.33%   |
| Intel I211 Gigabit Network Connection                             | 2        | 3.33%   |
| Intel Ethernet Controller I225-V                                  | 2        | 3.33%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 3.33%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.67%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.67%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.67%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.67%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.67%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.67%   |
| Huawei WLZ-AN00                                                   | 1        | 1.67%   |
| Google Pixel 7                                                    | 1        | 1.67%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 1.67%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 54       | 65.06%  |
| WiFi     | 27       | 32.53%  |
| Modem    | 2        | 2.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 73.33%  |
| WiFi     | 16       | 26.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 66.67%  |
| 2     | 17       | 31.48%  |
| 5     | 1        | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 35       | 63.64%  |
| Yes  | 20       | 36.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 36.84%  |
| Cambridge Silicon Radio         | 4        | 21.05%  |
| Realtek Semiconductor           | 2        | 10.53%  |
| MediaTek                        | 2        | 10.53%  |
| TP-Link                         | 1        | 5.26%   |
| Qualcomm Atheros Communications | 1        | 5.26%   |
| IMC Networks                    | 1        | 5.26%   |
| ASUSTek Computer                | 1        | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 21.05%  |
| Intel Bluetooth wireless interface                  | 3        | 15.79%  |
| Realtek Bluetooth Radio                             | 2        | 10.53%  |
| MediaTek Wireless_Device                            | 2        | 10.53%  |
| Intel AX210 Bluetooth                               | 2        | 10.53%  |
| TP-Link UB500 Adapter                               | 1        | 5.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 5.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 5.26%   |
| Intel AX201 Bluetooth                               | 1        | 5.26%   |
| IMC Networks BCM20702A0                             | 1        | 5.26%   |
| ASUS ASUS USB-BT500                                 | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 34       | 32.08%  |
| Intel                    | 32       | 30.19%  |
| Nvidia                   | 18       | 16.98%  |
| C-Media Electronics      | 5        | 4.72%   |
| Logitech                 | 3        | 2.83%   |
| Trust                    | 1        | 0.94%   |
| Texas Instruments        | 1        | 0.94%   |
| SteelSeries ApS          | 1        | 0.94%   |
| SAVITECH                 | 1        | 0.94%   |
| Mackie Designs           | 1        | 0.94%   |
| JMTek                    | 1        | 0.94%   |
| Generalplus Technology   | 1        | 0.94%   |
| Focusrite-Novation       | 1        | 0.94%   |
| Dell                     | 1        | 0.94%   |
| Creative Labs            | 1        | 0.94%   |
| Corsair                  | 1        | 0.94%   |
| AudioQuest               | 1        | 0.94%   |
| Asahi Kasei Microsystems | 1        | 0.94%   |
| 2.4G Composite Device    | 1        | 0.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 7.2%    |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 6.4%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 7        | 5.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 4.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 4.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 4%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 4%      |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 3.2%    |
| Intel 200 Series PCH HD Audio                                              | 4        | 3.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 2.4%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 2.4%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 2.4%    |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.6%    |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1.6%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.6%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.6%    |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.6%    |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.6%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 1.6%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.6%    |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2        | 1.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.6%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.6%    |
| Trust Microphone                                                           | 1        | 0.8%    |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1        | 0.8%    |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 0.8%    |
| SAVITECH SA9023 audio controller                                           | 1        | 0.8%    |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.8%    |
| Nvidia High Definition Audio Controller                                    | 1        | 0.8%    |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.8%    |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.8%    |
| Mackie Designs CHROMIUM Microphone                                         | 1        | 0.8%    |
| Logitech Yeti Nano                                                         | 1        | 0.8%    |
| Logitech G432 Gaming Headset                                               | 1        | 0.8%    |
| Logitech Blue Microphones                                                  | 1        | 0.8%    |
| JMTek UM10                                                                 | 1        | 0.8%    |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 0.8%    |
| Intel Jasper Lake HD Audio                                                 | 1        | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 6        | 19.35%  |
| G.Skill             | 4        | 12.9%   |
| Corsair             | 4        | 12.9%   |
| Unknown             | 2        | 6.45%   |
| Team                | 2        | 6.45%   |
| SK hynix            | 2        | 6.45%   |
| Samsung Electronics | 2        | 6.45%   |
| Micron Technology   | 2        | 6.45%   |
| Crucial             | 2        | 6.45%   |
| Patriot             | 1        | 3.23%   |
| Nanya Technology    | 1        | 3.23%   |
| Atermiter           | 1        | 3.23%   |
| A-DATA Technology   | 1        | 3.23%   |
| Unknown             | 1        | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 667MT/s                            | 1        | 3.03%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                     | 1        | 3.03%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s             | 1        | 3.03%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s             | 1        | 3.03%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s           | 1        | 3.03%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s           | 1        | 3.03%   |
| Samsung RAM M471B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 3.03%   |
| Samsung RAM 53D512M64D4RQ-046 4GB Row Of Chips LPDDR4 3733MT/s | 1        | 3.03%   |
| Patriot RAM 3200 C16 Series 8192MB DIMM DDR4 3266MT/s          | 1        | 3.03%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 3.03%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 1        | 3.03%   |
| Micron RAM 16KTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1        | 3.03%   |
| Micron RAM 16ATF2G64AZ-2G6J1 16GB DIMM DDR4 2667MT/s           | 1        | 3.03%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 1        | 3.03%   |
| Kingston RAM KF560C36-32 32GB DIMM DDR5 4800MT/s               | 1        | 3.03%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s          | 1        | 3.03%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 1        | 3.03%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s          | 1        | 3.03%   |
| Kingston RAM 9965646-035.B00G 8GB SODIMM DDR4 2933MT/s         | 1        | 3.03%   |
| G.Skill RAM F4-3600C18-16GVK 16384MB DIMM DDR4 3733MT/s        | 1        | 3.03%   |
| G.Skill RAM F4-3200C16-8GFX 8GB DIMM DDR4 3200MT/s             | 1        | 3.03%   |
| G.Skill RAM F4-3200C16-16GFX 16GB DIMM DDR4 3266MT/s           | 1        | 3.03%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s             | 1        | 3.03%   |
| G.Skill RAM F4-2400C15-4GRK 4GB DIMM DDR4 2400MT/s             | 1        | 3.03%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s          | 1        | 3.03%   |
| Crucial RAM BLS16G4D240FSE.16FBD 16384MB DIMM DDR4 2473MT/s    | 1        | 3.03%   |
| Corsair RAM CMW32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s         | 1        | 3.03%   |
| Corsair RAM CMU16GX4M2C3000C15 8GB DIMM DDR4 3200MT/s          | 1        | 3.03%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 1        | 3.03%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s          | 1        | 3.03%   |
| Atermiter RAM Module 16GB DIMM DDR4 2400MT/s                   | 1        | 3.03%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s                   | 1        | 3.03%   |
| Unknown                                                        | 1        | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 17       | 60.71%  |
| DDR3    | 8        | 28.57%  |
| LPDDR4  | 1        | 3.57%   |
| DDR5    | 1        | 3.57%   |
| Unknown | 1        | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 25       | 89.29%  |
| SODIMM       | 2        | 7.14%   |
| Row Of Chips | 1        | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 11       | 35.48%  |
| 16384 | 10       | 32.26%  |
| 4096  | 6        | 19.35%  |
| 32768 | 3        | 9.68%   |
| 2048  | 1        | 3.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 5        | 16.13%  |
| 3733  | 3        | 9.68%   |
| 3600  | 3        | 9.68%   |
| 2400  | 3        | 9.68%   |
| 3266  | 2        | 6.45%   |
| 2933  | 2        | 6.45%   |
| 2667  | 2        | 6.45%   |
| 1800  | 2        | 6.45%   |
| 1600  | 2        | 6.45%   |
| 1333  | 2        | 6.45%   |
| 4800  | 1        | 3.23%   |
| 3666  | 1        | 3.23%   |
| 3000  | 1        | 3.23%   |
| 2473  | 1        | 3.23%   |
| 667   | 1        | 3.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson XP-7100 Series | 1        | 50%     |
| Brother HL-L2310D series   | 1        | 50%     |

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
| Samsung Electronics           | 2        | 16.67%  |
| Microdia                      | 2        | 16.67%  |
| Logitech                      | 2        | 16.67%  |
| Sunplus Innovation Technology | 1        | 8.33%   |
| SN0002                        | 1        | 8.33%   |
| Generalplus Technology        | 1        | 8.33%   |
| GEMBIRD                       | 1        | 8.33%   |
| Chicony Electronics           | 1        | 8.33%   |
| AVerMedia Technologies        | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)           | 2        | 16.67%  |
| Sunplus 1080P Webcam                              | 1        | 8.33%   |
| SN0002 HIK 1080P USB CAMERA                       | 1        | 8.33%   |
| Microdia Webcam Vitade AF                         | 1        | 8.33%   |
| Microdia Camera                                   | 1        | 8.33%   |
| Logitech C920 PRO HD Webcam                       | 1        | 8.33%   |
| Logitech BRIO Ultra HD Webcam                     | 1        | 8.33%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 1        | 8.33%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 8.33%   |
| Chicony HP High Definition 1MP Webcam             | 1        | 8.33%   |
| AVerMedia PW310O Webcam                           | 1        | 8.33%   |

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
| 0     | 46       | 85.19%  |
| 1     | 6        | 11.11%  |
| 3     | 1        | 1.85%   |
| 2     | 1        | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 3        | 37.5%   |
| Unassigned class         | 2        | 25%     |
| Communication controller | 2        | 25%     |
| Sound                    | 1        | 12.5%   |

