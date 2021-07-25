Debian 11 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linux-bsd)
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

* [ Printers & scanners ](#printers-scanners)
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

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte   | H61MS                       | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Gigabyte   | H81M-S2H GSM                | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell       | 09KPNV A01                  | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| ASUSTek    | PRIME A320I-K               | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| ASUSTek    | H61M-K                      | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell       | 0NK5PH A00                  | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte   | Z77-D3H                     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| Intel      | DP55WB AAE64798-206         | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Protectli  | FW6                         | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek    | ROG STRIX Z390-F GAMING     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte   | X570 I AORUS PRO WIFI       | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek    | Z170-DELUXE                 | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte   | 970A-D3P                    | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Dell       | 0D441T A03                  | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| MSI        | H110I PRO AC                | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek    | PRIME Z370-A                | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek    | H87-PRO                     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI        | Z77MA-G45                   | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| ASRock     | FM2A68M-DG3+                | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Gigabyte   | B560M D3H                   | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| ASUSTek    | ROG STRIX Z370-H GAMING     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek    | P8Z68-V                     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| HP         | ProLiant MicroServer        | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| MSI        | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Huanan     | X99-F8 V2.0                 | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell       | 0M863N A00                  | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| MSI        | MPG B550 GAMING PLUS        | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek    | H81M-E                      | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP         | 2215                        | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| HP         | 2215                        | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| MSI        | MS-6712                     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| ASRock     | H77 Pro4-M                  | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte   | B550I AORUS PRO AX          | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Gigabyte   | AX370-Gaming K7             | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| MSI        | B85M-G43                    | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| Huanan     | X99-8M-F V1.1               | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| ASRock     | FM2A68M-HD+                 | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Gigabyte   | Z370 AORUS Gaming 5-CF      | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte   | Z370 AORUS Gaming 5-CF      | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock     | B550 Pro4                   | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock     | X399 Taichi                 | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL | ODROID-H2                   | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING ... | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Gigabyte   | AB350M-Gaming 3-CF          | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| MSI        | B450M MORTAR MAX            | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING ... | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| ASUSTek    | PRIME B450M-A               | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Gigabyte   | MCMLUAB-00                  | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| ASUSTek    | PRIME A320M-K               | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| Dell       | 0Y7WYT A00                  | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| ASUSTek    | Z97-AR                      | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| ASRock     | B450M Pro4                  | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| ASUSTek    | PRIME A320M-K               | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| ASRock     | B450M Pro4                  | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| ASUSTek    | M4A88T-M/USB3               | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Dell       | 0YXT71 A02                  | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| ASUSTek    | PRIME B550-PLUS             | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| ASUSTek    | P5B-Deluxe                  | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Gigabyte   | B450 AORUS PRO WIFI-CF      | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI        | B250M BAZOOKA               | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| MSI        | B450I GAMING PLUS AC        | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Gigabyte   | AB350M-D3H-CF               | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Gigabyte   | Z170X-GamingG1              | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Gigabyte   | Z77-D3H                     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo     | MAHOBAY                     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| Biostar    | B450MH                      | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| Gigabyte   | EG41MF-US2H                 | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.0-7-amd64                 | 29       | 44.62%  |
| 5.10.0-8-amd64                 | 18       | 27.69%  |
| 5.10.0-6-amd64                 | 9        | 13.85%  |
| 5.8.0-3-amd64                  | 1        | 1.54%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1        | 1.54%   |
| 5.11.22-2-pve                  | 1        | 1.54%   |
| 5.11.22-1-pve                  | 1        | 1.54%   |
| 5.11.0-21.1-liquorix-amd64     | 1        | 1.54%   |
| 5.11.0-16.1-liquorix-amd64     | 1        | 1.54%   |
| 5.10.0-7-686-pae               | 1        | 1.54%   |
| 5.10.0-3-amd64                 | 1        | 1.54%   |
| 5.10.0-2-amd64                 | 1        | 1.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 59       | 90.77%  |
| 5.11.22 | 2        | 3.08%   |
| 5.11.0  | 2        | 3.08%   |
| 5.8.0   | 1        | 1.54%   |
| 5.13.0  | 1        | 1.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 59       | 90.77%  |
| 5.11    | 4        | 6.15%   |
| 5.8     | 1        | 1.54%   |
| 5.13    | 1        | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 64       | 98.46%  |
| i686   | 1        | 1.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 14       | 21.54%  |
| KDE5            | 13       | 20%     |
| MATE            | 8        | 12.31%  |
| XFCE            | 7        | 10.77%  |
| Unknown         | 6        | 9.23%   |
| KDE             | 4        | 6.15%   |
| i3              | 3        | 4.62%   |
| Cinnamon        | 3        | 4.62%   |
| X-Cinnamon      | 2        | 3.08%   |
| sway            | 1        | 1.54%   |
| LXQt            | 1        | 1.54%   |
| GNUstep         | 1        | 1.54%   |
| GNOME Flashback | 1        | 1.54%   |
| Budgie          | 1        | 1.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 47       | 72.31%  |
| Wayland | 9        | 13.85%  |
| Tty     | 7        | 10.77%  |
| Unknown | 2        | 3.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 19       | 29.23%  |
| Unknown | 17       | 26.15%  |
| GDM     | 13       | 20%     |
| SDDM    | 10       | 15.38%  |
| LightDM | 4        | 6.15%   |
| XDM     | 1        | 1.54%   |
| SLiM    | 1        | 1.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 28       | 43.08%  |
| fr_FR   | 7        | 10.77%  |
| de_DE   | 4        | 6.15%   |
| pt_BR   | 3        | 4.62%   |
| en_CA   | 3        | 4.62%   |
| C       | 3        | 4.62%   |
| pl_PL   | 2        | 3.08%   |
| es_ES   | 2        | 3.08%   |
| en_AU   | 2        | 3.08%   |
| Unknown | 2        | 3.08%   |
| sr_RS   | 1        | 1.54%   |
| ru_UA   | 1        | 1.54%   |
| ru_RU   | 1        | 1.54%   |
| ro_RO   | 1        | 1.54%   |
| nl_BE   | 1        | 1.54%   |
| es_AR   | 1        | 1.54%   |
| en_PH   | 1        | 1.54%   |
| en_IN   | 1        | 1.54%   |
| en_GB   | 1        | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 33       | 50.77%  |
| EFI  | 32       | 49.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 55       | 84.62%  |
| Btrfs   | 4        | 6.15%   |
| Ext3    | 3        | 4.62%   |
| Zfs     | 2        | 3.08%   |
| Overlay | 1        | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 39       | 60%     |
| MBR     | 13       | 20%     |
| Unknown | 13       | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 80%     |
| Yes       | 13       | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 75.38%  |
| Yes       | 16       | 24.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 17       | 26.15%  |
| ASUSTek Computer    | 17       | 26.15%  |
| MSI                 | 9        | 13.85%  |
| ASRock              | 7        | 10.77%  |
| Dell                | 6        | 9.23%   |
| Huanan              | 2        | 3.08%   |
| Hewlett-Packard     | 2        | 3.08%   |
| Protectli           | 1        | 1.54%   |
| Lenovo              | 1        | 1.54%   |
| Intel               | 1        | 1.54%   |
| HARDKERNEL          | 1        | 1.54%   |
| Biostar             | 1        | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 3        | 4.62%   |
| Gigabyte Z77-D3H                 | 2        | 3.08%   |
| Gigabyte Z370 AORUS Gaming 5     | 2        | 3.08%   |
| ASRock B450M Pro4                | 2        | 3.08%   |
| Protectli FW6                    | 1        | 1.54%   |
| MSI MS-7C56                      | 1        | 1.54%   |
| MSI MS-7B89                      | 1        | 1.54%   |
| MSI MS-7A70                      | 1        | 1.54%   |
| MSI MS-7A40                      | 1        | 1.54%   |
| MSI MS-7995                      | 1        | 1.54%   |
| MSI MS-7823                      | 1        | 1.54%   |
| MSI MS-7759                      | 1        | 1.54%   |
| MSI MS-7721                      | 1        | 1.54%   |
| MSI MS-6712                      | 1        | 1.54%   |
| Lenovo ThinkCentre M92p 3209EK4  | 1        | 1.54%   |
| Intel DP55WB AAE64798-206        | 1        | 1.54%   |
| Huanan X99-F8                    | 1        | 1.54%   |
| Huanan X99-8M-F V1.1             | 1        | 1.54%   |
| HP ProLiant MicroServer          | 1        | 1.54%   |
| HP EliteDesk 705 G1 SFF          | 1        | 1.54%   |
| HARDKERNEL ODROID-H2             | 1        | 1.54%   |
| Gigabyte Z170X-GamingG1          | 1        | 1.54%   |
| Gigabyte X570 I AORUS PRO WIFI   | 1        | 1.54%   |
| Gigabyte H81M-S2H GSM            | 1        | 1.54%   |
| Gigabyte H61MS                   | 1        | 1.54%   |
| Gigabyte EG41MF-US2H             | 1        | 1.54%   |
| Gigabyte BRi7(H)-10710           | 1        | 1.54%   |
| Gigabyte B560M D3H               | 1        | 1.54%   |
| Gigabyte B550I AORUS PRO AX      | 1        | 1.54%   |
| Gigabyte B450 AORUS PRO WIFI     | 1        | 1.54%   |
| Gigabyte AX370-Gaming K7         | 1        | 1.54%   |
| Gigabyte AB350M-Gaming 3         | 1        | 1.54%   |
| Gigabyte AB350M-D3H              | 1        | 1.54%   |
| Gigabyte 970A-D3P                | 1        | 1.54%   |
| Dell Precision WorkStation T3500 | 1        | 1.54%   |
| Dell Precision Tower 7910        | 1        | 1.54%   |
| Dell OptiPlex 980                | 1        | 1.54%   |
| Dell OptiPlex 760                | 1        | 1.54%   |
| Dell OptiPlex 7040               | 1        | 1.54%   |
| Dell OptiPlex 7010               | 1        | 1.54%   |
| Biostar B450MH                   | 1        | 1.54%   |
| ASUS Z170-DELUXE                 | 1        | 1.54%   |
| ASUS ROG STRIX Z390-F GAMING     | 1        | 1.54%   |
| ASUS ROG STRIX Z370-H GAMING     | 1        | 1.54%   |
| ASUS ROG STRIX B450-F GAMING II  | 1        | 1.54%   |
| ASUS ROG STRIX B450-F GAMING     | 1        | 1.54%   |
| ASUS PRIME Z370-A                | 1        | 1.54%   |
| ASUS PRIME B550-PLUS             | 1        | 1.54%   |
| ASUS PRIME B450M-A               | 1        | 1.54%   |
| ASUS PRIME A320M-K               | 1        | 1.54%   |
| ASUS PRIME A320I-K               | 1        | 1.54%   |
| ASUS P8Z68-V                     | 1        | 1.54%   |
| ASUS P5B-Deluxe                  | 1        | 1.54%   |
| ASUS M4A88T-M/USB3               | 1        | 1.54%   |
| ASUS H61M-K                      | 1        | 1.54%   |
| ASRock X399 Taichi               | 1        | 1.54%   |
| ASRock H77 Pro4-M                | 1        | 1.54%   |
| ASRock FM2A68M-HD+               | 1        | 1.54%   |
| ASRock FM2A68M-DG3+              | 1        | 1.54%   |
| ASRock B550 Pro4                 | 1        | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 5        | 7.69%   |
| Dell OptiPlex           | 4        | 6.15%   |
| ASUS ROG                | 4        | 6.15%   |
| ASUS All                | 3        | 4.62%   |
| Gigabyte Z77-D3H        | 2        | 3.08%   |
| Gigabyte Z370           | 2        | 3.08%   |
| Dell Precision          | 2        | 3.08%   |
| ASRock B450M            | 2        | 3.08%   |
| Protectli FW6           | 1        | 1.54%   |
| MSI MS-7C56             | 1        | 1.54%   |
| MSI MS-7B89             | 1        | 1.54%   |
| MSI MS-7A70             | 1        | 1.54%   |
| MSI MS-7A40             | 1        | 1.54%   |
| MSI MS-7995             | 1        | 1.54%   |
| MSI MS-7823             | 1        | 1.54%   |
| MSI MS-7759             | 1        | 1.54%   |
| MSI MS-7721             | 1        | 1.54%   |
| MSI MS-6712             | 1        | 1.54%   |
| Lenovo ThinkCentre      | 1        | 1.54%   |
| Intel DP55WB            | 1        | 1.54%   |
| Huanan X99-F8           | 1        | 1.54%   |
| Huanan X99-8M-F         | 1        | 1.54%   |
| HP ProLiant             | 1        | 1.54%   |
| HP EliteDesk            | 1        | 1.54%   |
| HARDKERNEL ODROID-H2    | 1        | 1.54%   |
| Gigabyte Z170X-GamingG1 | 1        | 1.54%   |
| Gigabyte X570           | 1        | 1.54%   |
| Gigabyte H81M-S2H       | 1        | 1.54%   |
| Gigabyte H61MS          | 1        | 1.54%   |
| Gigabyte EG41MF-US2H    | 1        | 1.54%   |
| Gigabyte BRi7(H)-10710  | 1        | 1.54%   |
| Gigabyte B560M          | 1        | 1.54%   |
| Gigabyte B550I          | 1        | 1.54%   |
| Gigabyte B450           | 1        | 1.54%   |
| Gigabyte AX370-Gaming   | 1        | 1.54%   |
| Gigabyte AB350M-Gaming  | 1        | 1.54%   |
| Gigabyte AB350M-D3H     | 1        | 1.54%   |
| Gigabyte 970A-D3P       | 1        | 1.54%   |
| Biostar B450MH          | 1        | 1.54%   |
| ASUS Z170-DELUXE        | 1        | 1.54%   |
| ASUS P8Z68-V            | 1        | 1.54%   |
| ASUS P5B-Deluxe         | 1        | 1.54%   |
| ASUS M4A88T-M           | 1        | 1.54%   |
| ASUS H61M-K             | 1        | 1.54%   |
| ASRock X399             | 1        | 1.54%   |
| ASRock H77              | 1        | 1.54%   |
| ASRock FM2A68M-HD+      | 1        | 1.54%   |
| ASRock FM2A68M-DG3+     | 1        | 1.54%   |
| ASRock B550             | 1        | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 14       | 21.54%  |
| 2019 | 10       | 15.38%  |
| 2021 | 8        | 12.31%  |
| 2018 | 6        | 9.23%   |
| 2014 | 6        | 9.23%   |
| 2012 | 5        | 7.69%   |
| 2016 | 4        | 6.15%   |
| 2010 | 3        | 4.62%   |
| 2015 | 2        | 3.08%   |
| 2013 | 2        | 3.08%   |
| 2017 | 1        | 1.54%   |
| 2011 | 1        | 1.54%   |
| 2009 | 1        | 1.54%   |
| 2007 | 1        | 1.54%   |
| 2001 | 1        | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 65       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 63       | 96.92%  |
| Enabled  | 2        | 3.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 98.46%  |
| Yes  | 1        | 1.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 20       | 30.77%  |
| 8.01-16.0       | 12       | 18.46%  |
| 32.01-64.0      | 11       | 16.92%  |
| 64.01-256.0     | 9        | 13.85%  |
| 4.01-8.0        | 7        | 10.77%  |
| 3.01-4.0        | 3        | 4.62%   |
| More than 256.0 | 1        | 1.54%   |
| 2.01-3.0        | 1        | 1.54%   |
| 1.01-2.0        | 1        | 1.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 14       | 21.54%  |
| 4.01-8.0   | 13       | 20%     |
| 2.01-3.0   | 10       | 15.38%  |
| 8.01-16.0  | 7        | 10.77%  |
| 1.01-2.0   | 6        | 9.23%   |
| 0.51-1.0   | 5        | 7.69%   |
| 16.01-24.0 | 4        | 6.15%   |
| 24.01-32.0 | 3        | 4.62%   |
| 32.01-64.0 | 2        | 3.08%   |
| 0.01-0.5   | 1        | 1.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 32.31%  |
| 3      | 15       | 23.08%  |
| 1      | 14       | 21.54%  |
| 5      | 5        | 7.69%   |
| 4      | 5        | 7.69%   |
| 8      | 3        | 4.62%   |
| 9      | 1        | 1.54%   |
| 6      | 1        | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 50.77%  |
| No        | 32       | 49.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 64       | 98.46%  |
| No        | 1        | 1.54%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 60%     |
| Yes       | 26       | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 70.77%  |
| Yes       | 19       | 29.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country       | Desktops | Percent |
|---------------|----------|---------|
| USA           | 17       | 26.15%  |
| France        | 8        | 12.31%  |
| Germany       | 6        | 9.23%   |
| Spain         | 4        | 6.15%   |
| Poland        | 4        | 6.15%   |
| Brazil        | 3        | 4.62%   |
| Australia     | 3        | 4.62%   |
| Canada        | 2        | 3.08%   |
| Bulgaria      | 2        | 3.08%   |
| Argentina     | 2        | 3.08%   |
| Ukraine       | 1        | 1.54%   |
| UK            | 1        | 1.54%   |
| Syria         | 1        | 1.54%   |
| Singapore     | 1        | 1.54%   |
| Serbia        | 1        | 1.54%   |
| Russia        | 1        | 1.54%   |
| Norway        | 1        | 1.54%   |
| New Caledonia | 1        | 1.54%   |
| Netherlands   | 1        | 1.54%   |
| Madagascar    | 1        | 1.54%   |
| Italy         | 1        | 1.54%   |
| India         | 1        | 1.54%   |
| Hungary       | 1        | 1.54%   |
| Belgium       | 1        | 1.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Lyon                        | 3        | 4.62%   |
| Warsaw                      | 2        | 3.08%   |
| Sofia                       | 2        | 3.08%   |
| New York                    | 2        | 3.08%   |
| Las Vegas                   | 2        | 3.08%   |
| Érd                        | 1        | 1.54%   |
| Woolloongabba               | 1        | 1.54%   |
| Woodstock                   | 1        | 1.54%   |
| Waregem                     | 1        | 1.54%   |
| Vancouver                   | 1        | 1.54%   |
| Toulouse                    | 1        | 1.54%   |
| Thionville                  | 1        | 1.54%   |
| Stavanger                   | 1        | 1.54%   |
| Sosnowiec                   | 1        | 1.54%   |
| Singapore                   | 1        | 1.54%   |
| San Francisco               | 1        | 1.54%   |
| San Cristóbal de La Laguna | 1        | 1.54%   |
| Saint-Denis                 | 1        | 1.54%   |
| Rochester                   | 1        | 1.54%   |
| Ribeirao Pires              | 1        | 1.54%   |
| Perth                       | 1        | 1.54%   |
| Noumea                      | 1        | 1.54%   |
| Noblesville                 | 1        | 1.54%   |
| Mesa                        | 1        | 1.54%   |
| Mannheim                    | 1        | 1.54%   |
| Mairena del Aljarafe        | 1        | 1.54%   |
| Madrid                      | 1        | 1.54%   |
| Kozhikode                   | 1        | 1.54%   |
| Kiel                        | 1        | 1.54%   |
| Kharkiv                     | 1        | 1.54%   |
| Khabarovsk                  | 1        | 1.54%   |
| Great Malvern               | 1        | 1.54%   |
| Glienicke                   | 1        | 1.54%   |
| Gdansk                      | 1        | 1.54%   |
| Garching bei Munchen        | 1        | 1.54%   |
| Forest City                 | 1        | 1.54%   |
| Floresta                    | 1        | 1.54%   |
| Flanders                    | 1        | 1.54%   |
| Ettlingen                   | 1        | 1.54%   |
| Englishtown                 | 1        | 1.54%   |
| East Orange                 | 1        | 1.54%   |
| Dourados                    | 1        | 1.54%   |
| Delft                       | 1        | 1.54%   |
| Damascus                    | 1        | 1.54%   |
| Córdoba                    | 1        | 1.54%   |
| Costa Mesa                  | 1        | 1.54%   |
| Chapel Hill                 | 1        | 1.54%   |
| Chaligny                    | 1        | 1.54%   |
| Carthage                    | 1        | 1.54%   |
| Canberra                    | 1        | 1.54%   |
| Buena Park                  | 1        | 1.54%   |
| Bonn                        | 1        | 1.54%   |
| Bologna                     | 1        | 1.54%   |
| Bloomfield                  | 1        | 1.54%   |
| Belgrade                    | 1        | 1.54%   |
| Barueri                     | 1        | 1.54%   |
| Barcelona                   | 1        | 1.54%   |
| Aulnay-sous-Bois            | 1        | 1.54%   |
| Antananarivo                | 1        | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 31       | 53     | 24.6%   |
| WDC                 | 26       | 40     | 20.63%  |
| Samsung Electronics | 15       | 23     | 11.9%   |
| Toshiba             | 9        | 14     | 7.14%   |
| Crucial             | 8        | 9      | 6.35%   |
| Kingston            | 6        | 7      | 4.76%   |
| Intel               | 6        | 13     | 4.76%   |
| SanDisk             | 5        | 5      | 3.97%   |
| A-DATA Technology   | 3        | 3      | 2.38%   |
| Unknown             | 2        | 2      | 1.59%   |
| PNY                 | 2        | 2      | 1.59%   |
| Phison Electronics  | 2        | 2      | 1.59%   |
| Hitachi             | 2        | 2      | 1.59%   |
| Gigabyte Technology | 2        | 2      | 1.59%   |
| Team                | 1        | 1      | 0.79%   |
| SPCC                | 1        | 1      | 0.79%   |
| Phison              | 1        | 1      | 0.79%   |
| Patriot             | 1        | 1      | 0.79%   |
| Intenso             | 1        | 1      | 0.79%   |
| Corsair             | 1        | 1      | 0.79%   |
| China               | 1        | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WDS120G2G0A-00JH30 120GB SSD | 3        | 1.97%   |
| Toshiba HDWD110 1TB              | 3        | 1.97%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 2        | 1.32%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2        | 1.32%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 1.32%   |
| Toshiba DT01ACA300 3TB           | 2        | 1.32%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 1.32%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 1.32%   |
| Seagate ST3000DM001-1CH166 3TB   | 2        | 1.32%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 1.32%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 1.32%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 1.32%   |
| Seagate BUP Slim BL 2TB          | 2        | 1.32%   |
| Sandisk NVMe SSD Drive 1TB       | 2        | 1.32%   |
| Samsung SSD 860 EVO 2TB          | 2        | 1.32%   |
| Samsung SSD 860 EVO 250GB        | 2        | 1.32%   |
| Samsung SSD 860 EVO 1TB          | 2        | 1.32%   |
| Samsung SSD 840 PRO Series 256GB | 2        | 1.32%   |
| Samsung HD103SJ 1TB              | 2        | 1.32%   |
| Phison PCIe SSD 512GB            | 2        | 1.32%   |
| Kingston SV300S37A240G 240GB SSD | 2        | 1.32%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 1.32%   |
| Intel NVMe SSD Drive 1024GB      | 2        | 1.32%   |
| Intel MEMPEK1J016GAL 16GB        | 2        | 1.32%   |
| WDC WUH721414ALE6L4 14TB         | 1        | 0.66%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.66%   |
| WDC WDBRPG5000ANC-WRSN 500GB     | 1        | 0.66%   |
| WDC WD5003ABYX-18WERA0 500GB     | 1        | 0.66%   |
| WDC WD5000AZRX-00A8LB0 500GB     | 1        | 0.66%   |
| WDC WD5000AVCS-632DY1 500GB      | 1        | 0.66%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.66%   |
| WDC WD5000AAKS-22V1A0 500GB      | 1        | 0.66%   |
| WDC WD5000A 500GB                | 1        | 0.66%   |
| WDC WD400BB-00DEA0 40GB          | 1        | 0.66%   |
| WDC WD30EZRX-22D8PB0 3TB         | 1        | 0.66%   |
| WDC WD30EZRX-00MMMB0 3TB         | 1        | 0.66%   |
| WDC WD2500AAKX-00ERMA0 250GB     | 1        | 0.66%   |
| WDC WD2500AAJS-75M0A0 250GB      | 1        | 0.66%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.66%   |
| WDC WD20EZRX-22D8PB0 2TB         | 1        | 0.66%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 1        | 0.66%   |
| WDC WD1600AAJS-00L7A0 160GB      | 1        | 0.66%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1        | 0.66%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 1        | 0.66%   |
| WDC WD10EZEX-75WN4A1 1TB         | 1        | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 0.66%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 0.66%   |
| WDC WD10EVDS-63N5B1 1TB          | 1        | 0.66%   |
| WDC WD10EURX-63C57Y0 1TB         | 1        | 0.66%   |
| WDC WD10EFRX-68FYTN0 1TB         | 1        | 0.66%   |
| WDC WD10EALX-009BA0 1TB          | 1        | 0.66%   |
| WDC WD1001FALS-75J7B0 1TB        | 1        | 0.66%   |
| Unknown ZA480NM10001 480GB SSD   | 1        | 0.66%   |
| Unknown BJTD4R  32GB             | 1        | 0.66%   |
| Toshiba TR150 960GB SSD          | 1        | 0.66%   |
| Toshiba MQ01ACF032 320GB         | 1        | 0.66%   |
| Toshiba MK2565GSX 250GB          | 1        | 0.66%   |
| Toshiba HDWD120 2TB              | 1        | 0.66%   |
| Toshiba DT01ACA200 2TB           | 1        | 0.66%   |
| Toshiba A100 240GB SSD           | 1        | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 30       | 44     | 46.88%  |
| WDC                 | 21       | 31     | 32.81%  |
| Toshiba             | 7        | 12     | 10.94%  |
| Samsung Electronics | 4        | 5      | 6.25%   |
| Hitachi             | 2        | 2      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 13     | 23.68%  |
| Crucial             | 7        | 7      | 18.42%  |
| Kingston            | 6        | 7      | 15.79%  |
| WDC                 | 4        | 5      | 10.53%  |
| A-DATA Technology   | 3        | 3      | 7.89%   |
| Toshiba             | 2        | 2      | 5.26%   |
| SanDisk             | 2        | 2      | 5.26%   |
| Unknown             | 1        | 1      | 2.63%   |
| Team                | 1        | 1      | 2.63%   |
| PNY                 | 1        | 1      | 2.63%   |
| Patriot             | 1        | 1      | 2.63%   |
| China               | 1        | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 49       | 94     | 42.98%  |
| SSD     | 36       | 44     | 31.58%  |
| NVMe    | 24       | 34     | 21.05%  |
| Unknown | 4        | 11     | 3.51%   |
| MMC     | 1        | 1      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 56       | 133    | 62.92%  |
| NVMe | 24       | 34     | 26.97%  |
| SAS  | 8        | 16     | 8.99%   |
| MMC  | 1        | 1      | 1.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 36       | 52     | 38.3%   |
| 0.51-1.0   | 27       | 38     | 28.72%  |
| 1.01-2.0   | 18       | 22     | 19.15%  |
| 2.01-3.0   | 5        | 9      | 5.32%   |
| 3.01-4.0   | 4        | 4      | 4.26%   |
| 4.01-10.0  | 3        | 12     | 3.19%   |
| 10.01-20.0 | 1        | 1      | 1.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 14       | 21.54%  |
| 251-500        | 13       | 20%     |
| 501-1000       | 10       | 15.38%  |
| 1001-2000      | 9        | 13.85%  |
| 2001-3000      | 7        | 10.77%  |
| 101-250        | 7        | 10.77%  |
| Unknown        | 2        | 3.08%   |
| 21-50          | 1        | 1.54%   |
| 1-20           | 1        | 1.54%   |
| 51-100         | 1        | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 12       | 18.46%  |
| 251-500        | 8        | 12.31%  |
| 1-20           | 8        | 12.31%  |
| 1001-2000      | 7        | 10.77%  |
| 51-100         | 7        | 10.77%  |
| 2001-3000      | 6        | 9.23%   |
| 501-1000       | 6        | 9.23%   |
| 21-50          | 5        | 7.69%   |
| More than 3000 | 4        | 6.15%   |
| Unknown        | 2        | 3.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5003ABYX-18WERA0 500GB          | 1        | 2      | 5.26%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 5.26%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1        | 1      | 5.26%   |
| WDC WD400BB-00DEA0 40GB               | 1        | 1      | 5.26%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 5.26%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1        | 1      | 5.26%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 5.26%   |
| WDC WD1001FALS-75J7B0 1TB             | 1        | 1      | 5.26%   |
| Toshiba MK2565GSX 250GB               | 1        | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 5.26%   |
| Seagate ST32000542AS 2TB              | 1        | 1      | 5.26%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 5.26%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 5.26%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 5.26%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 5.26%   |
| Intel SSDPEKKW010T7 1TB               | 1        | 2      | 5.26%   |
| Hitachi HDS722525VLAT80 250GB         | 1        | 1      | 5.26%   |
| A-DATA Technology SSD DP900 128GB-DL3 | 1        | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 8        | 9      | 42.11%  |
| Seagate           | 6        | 6      | 31.58%  |
| Toshiba           | 1        | 1      | 5.26%   |
| Kingston          | 1        | 1      | 5.26%   |
| Intel             | 1        | 2      | 5.26%   |
| Hitachi           | 1        | 1      | 5.26%   |
| A-DATA Technology | 1        | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 8        | 9      | 50%     |
| Seagate | 6        | 6      | 37.5%   |
| Toshiba | 1        | 1      | 6.25%   |
| Hitachi | 1        | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 17     | 83.33%  |
| SSD  | 2        | 2      | 11.11%  |
| NVMe | 1        | 2      | 5.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500830AS 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 50       | 120    | 58.14%  |
| Detected | 18       | 42     | 20.93%  |
| Malfunc  | 17       | 21     | 19.77%  |
| Failed   | 1        | 1      | 1.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 39       | 41.05%  |
| AMD                       | 27       | 28.42%  |
| Phison Electronics        | 7        | 7.37%   |
| Sandisk                   | 6        | 6.32%   |
| Samsung Electronics       | 5        | 5.26%   |
| ASMedia Technology        | 4        | 4.21%   |
| Micron/Crucial Technology | 2        | 2.11%   |
| VIA Technologies          | 1        | 1.05%   |
| Marvell Technology Group  | 1        | 1.05%   |
| JMicron Technology        | 1        | 1.05%   |
| Broadcom / LSI            | 1        | 1.05%   |
| Adaptec                   | 1        | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 19       | 15.7%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 7.44%   |
| Phison E12 NVMe Controller                                                              | 5        | 4.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 4.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 4.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 3.31%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 3.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.31%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 4        | 3.31%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 3        | 2.48%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.48%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.65%   |
| Intel SSD 600P Series                                                                   | 2        | 1.65%   |
| Intel NVMe Optane Memory Series                                                         | 2        | 1.65%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.65%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.65%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.65%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.83%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.83%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.83%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.83%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                                   | 1        | 0.83%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.83%   |
| Intel SSD 660P Series                                                                   | 1        | 0.83%   |
| Intel PCIe Data Center SSD                                                              | 1        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.83%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.83%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.83%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 0.83%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.83%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.83%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.83%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                                     | 1        | 0.83%   |
| ASMedia ASM1061 SATA IDE Controller                                                     | 1        | 0.83%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 0.83%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 0.83%   |
| Adaptec Series 8 12G SAS/PCIe 3                                                         | 1        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 57       | 58.76%  |
| NVMe | 24       | 24.74%  |
| IDE  | 10       | 10.31%  |
| RAID | 5        | 5.15%   |
| SAS  | 1        | 1.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 37       | 56.92%  |
| AMD    | 28       | 43.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 4        | 6.15%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 3        | 4.62%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 2        | 3.08%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 2        | 3.08%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2        | 3.08%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 2        | 3.08%   |
| Intel Xeon CPU W3503 @ 2.40GHz                  | 1        | 1.54%   |
| Intel Xeon CPU E5-2699 v4 @ 2.20GHz             | 1        | 1.54%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz             | 1        | 1.54%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz             | 1        | 1.54%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1        | 1.54%   |
| Intel Core i9-9900K CPU @ 3.60GHz               | 1        | 1.54%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 1.54%   |
| Intel Core i7-8086K CPU @ 4.00GHz               | 1        | 1.54%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 1.54%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1        | 1.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 1.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 1.54%   |
| Intel Core i7-10710U CPU @ 1.10GHz              | 1        | 1.54%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1        | 1.54%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 1        | 1.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 1.54%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 1.54%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 1.54%   |
| Intel Core i5-3570K CPU @ 3.40GHz               | 1        | 1.54%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 1        | 1.54%   |
| Intel Core i5-3550 CPU @ 3.30GHz                | 1        | 1.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.54%   |
| Intel Core i5-3450 CPU @ 3.10GHz                | 1        | 1.54%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1        | 1.54%   |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 1        | 1.54%   |
| Intel Core i3-4170 CPU @ 3.70GHz                | 1        | 1.54%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.54%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 1.54%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 1        | 1.54%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz            | 1        | 1.54%   |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1        | 1.54%   |
| Intel 11th Gen Core i5-11500 @ 2.70GHz          | 1        | 1.54%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1        | 1.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 1.54%   |
| AMD Ryzen 7 1700X Eight-Core Processor          | 1        | 1.54%   |
| AMD Ryzen 5 3600X 6-Core Processor              | 1        | 1.54%   |
| AMD Ryzen 5 3500X 6-Core Processor              | 1        | 1.54%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1        | 1.54%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 1        | 1.54%   |
| AMD Ryzen 3 1300X Quad-Core Processor           | 1        | 1.54%   |
| AMD Ryzen 3 1200 Quad-Core Processor            | 1        | 1.54%   |
| AMD Phenom II X4 965 Processor                  | 1        | 1.54%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 1.54%   |
| AMD Athlon XP 1500+                             | 1        | 1.54%   |
| AMD Athlon X4 840 Quad Core Processor           | 1        | 1.54%   |
| AMD Athlon II Neo N36L Dual-Core Processor      | 1        | 1.54%   |
| AMD A8 PRO-7600B R7, 10 Compute Cores 4C+6G     | 1        | 1.54%   |
| AMD A6 PRO-7400B R5, 6 Compute Cores 2C+4G      | 1        | 1.54%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 14       | 21.54%  |
| Intel Core i7          | 10       | 15.38%  |
| AMD Ryzen 5            | 10       | 15.38%  |
| AMD Ryzen 7            | 5        | 7.69%   |
| Intel Xeon             | 4        | 6.15%   |
| Intel Core i3          | 2        | 3.08%   |
| Intel Core 2 Duo       | 2        | 3.08%   |
| AMD Ryzen 9            | 2        | 3.08%   |
| AMD Ryzen 3            | 2        | 3.08%   |
| Other                  | 1        | 1.54%   |
| Intel Pentium          | 1        | 1.54%   |
| Intel Core i9          | 1        | 1.54%   |
| Intel Core 2 Quad      | 1        | 1.54%   |
| Intel Celeron          | 1        | 1.54%   |
| AMD Ryzen Threadripper | 1        | 1.54%   |
| AMD Phenom II X4       | 1        | 1.54%   |
| AMD FX                 | 1        | 1.54%   |
| AMD Athlon XP          | 1        | 1.54%   |
| AMD Athlon X4          | 1        | 1.54%   |
| AMD Athlon II Neo      | 1        | 1.54%   |
| AMD A8                 | 1        | 1.54%   |
| AMD A6                 | 1        | 1.54%   |
| AMD A10                | 1        | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 23       | 35.38%  |
| 6      | 16       | 24.62%  |
| 2      | 12       | 18.46%  |
| 8      | 7        | 10.77%  |
| 12     | 3        | 4.62%   |
| 1      | 2        | 3.08%   |
| 44     | 1        | 1.54%   |
| 32     | 1        | 1.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 64       | 98.46%  |
| 2      | 1        | 1.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 40       | 61.54%  |
| 1      | 25       | 38.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 64       | 98.46%  |
| 32-bit         | 1        | 1.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 32.31%  |
| 0x306c3    | 5        | 7.69%   |
| 0x306a9    | 5        | 7.69%   |
| 0x08701021 | 5        | 7.69%   |
| 0x506e3    | 3        | 4.62%   |
| 0x06003106 | 3        | 4.62%   |
| 0x306f2    | 2        | 3.08%   |
| 0x206a7    | 2        | 3.08%   |
| 0x0800820d | 2        | 3.08%   |
| 0x08001138 | 2        | 3.08%   |
| 0xa0671    | 1        | 1.54%   |
| 0xa0660    | 1        | 1.54%   |
| 0x906ec    | 1        | 1.54%   |
| 0x906ea    | 1        | 1.54%   |
| 0x906e9    | 1        | 1.54%   |
| 0x806e9    | 1        | 1.54%   |
| 0x706a1    | 1        | 1.54%   |
| 0x6fb      | 1        | 1.54%   |
| 0x406f1    | 1        | 1.54%   |
| 0x106e5    | 1        | 1.54%   |
| 0x106a5    | 1        | 1.54%   |
| 0x0a201009 | 1        | 1.54%   |
| 0x08701013 | 1        | 1.54%   |
| 0x0800820b | 1        | 1.54%   |
| 0x010000c8 | 1        | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 11       | 16.92%  |
| KabyLake      | 7        | 10.77%  |
| IvyBridge     | 7        | 10.77%  |
| Haswell       | 7        | 10.77%  |
| Zen+          | 5        | 7.69%   |
| Steamroller   | 4        | 6.15%   |
| Skylake       | 4        | 6.15%   |
| Zen 3         | 2        | 3.08%   |
| Zen           | 2        | 3.08%   |
| SandyBridge   | 2        | 3.08%   |
| Nehalem       | 2        | 3.08%   |
| K10           | 2        | 3.08%   |
| Core          | 2        | 3.08%   |
| Westmere      | 1        | 1.54%   |
| Piledriver    | 1        | 1.54%   |
| Penryn        | 1        | 1.54%   |
| K6            | 1        | 1.54%   |
| Goldmont plus | 1        | 1.54%   |
| CometLake     | 1        | 1.54%   |
| Broadwell     | 1        | 1.54%   |
| Unknown       | 1        | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 28       | 42.42%  |
| AMD    | 20       | 30.3%   |
| Intel  | 18       | 27.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 8.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 5.97%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 5.97%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 4.48%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.99%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 2.99%   |
| Intel HD Graphics 530                                                       | 2        | 2.99%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 2.99%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.49%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.49%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.49%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 1.49%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.49%   |
| Nvidia GV100GL [Quadro GV100]                                               | 1        | 1.49%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.49%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.49%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.49%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.49%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.49%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.49%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.49%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.49%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.49%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 1.49%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.49%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.49%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 1.49%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 1.49%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                       | 1        | 1.49%   |
| Nvidia GF110 [GeForce GTX 560 Ti 448 Cores]                                 | 1        | 1.49%   |
| Nvidia G98 [Quadro NVS 295]                                                 | 1        | 1.49%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.49%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.49%   |
| Intel HD Graphics 620                                                       | 1        | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.49%   |
| Intel Comet Lake UHD Graphics                                               | 1        | 1.49%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.49%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.49%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.49%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 1        | 1.49%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                      | 1        | 1.49%   |
| AMD RV280 [Radeon 9200 SE]                                                  | 1        | 1.49%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                   | 1        | 1.49%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 1.49%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.49%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.49%   |
| AMD Kaveri [Radeon R5 Graphics]                                             | 1        | 1.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 27       | 41.54%  |
| 1 x AMD        | 19       | 29.23%  |
| 1 x Intel      | 17       | 26.15%  |
| 2 x AMD        | 1        | 1.54%   |
| Intel + Nvidia | 1        | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 45       | 69.23%  |
| Proprietary | 20       | 30.77%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 43.08%  |
| 7.01-8.0   | 9        | 13.85%  |
| 1.01-2.0   | 7        | 10.77%  |
| 3.01-4.0   | 6        | 9.23%   |
| 0.51-1.0   | 5        | 7.69%   |
| 5.01-6.0   | 4        | 6.15%   |
| 0.01-0.5   | 4        | 6.15%   |
| 24.01-32.0 | 1        | 1.54%   |
| 2.01-3.0   | 1        | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 14.81%  |
| Goldstar             | 11       | 13.58%  |
| Acer                 | 10       | 12.35%  |
| Ancor Communications | 9        | 11.11%  |
| Dell                 | 8        | 9.88%   |
| Hewlett-Packard      | 7        | 8.64%   |
| BenQ                 | 5        | 6.17%   |
| AOC                  | 4        | 4.94%   |
| LG Electronics       | 2        | 2.47%   |
| Vestel Elektronik    | 1        | 1.23%   |
| Unknown              | 1        | 1.23%   |
| Sony                 | 1        | 1.23%   |
| Philips              | 1        | 1.23%   |
| ODH                  | 1        | 1.23%   |
| Medion               | 1        | 1.23%   |
| JVC                  | 1        | 1.23%   |
| INFOTRONIC           | 1        | 1.23%   |
| Iiyama               | 1        | 1.23%   |
| Idek Iiyama          | 1        | 1.23%   |
| Hitachi              | 1        | 1.23%   |
| Eizo                 | 1        | 1.23%   |
| Belinea              | 1        | 1.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2        | 2.3%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2        | 2.3%    |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 2        | 2.3%    |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2        | 2.3%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 1.15%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 1.15%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1        | 1.15%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1        | 1.15%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 1.15%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 1        | 1.15%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 1        | 1.15%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1        | 1.15%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch      | 1        | 1.15%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 1.15%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch       | 1        | 1.15%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 1.15%   |
| Samsung Electronics LCD Monitor SyncMaster 5760x1080                   | 1        | 1.15%   |
| Samsung Electronics LCD Monitor SMB2430L                               | 1        | 1.15%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 1.15%   |
| Samsung Electronics LCD Monitor C24F390 3360x1080                      | 1        | 1.15%   |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch      | 1        | 1.15%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1        | 1.15%   |
| ODH LM24 ODH2492 1920x1080 345x259mm 17.0-inch                         | 1        | 1.15%   |
| Medion MD41077EA MED078B 1280x1024 330x270mm 16.8-inch                 | 1        | 1.15%   |
| LG Electronics LCD Monitor LG IPS FULLHD                               | 1        | 1.15%   |
| LG Electronics LCD Monitor LG HDR QHD 4480x1440                        | 1        | 1.15%   |
| LG Electronics LCD Monitor 27GL850 2560x1440                           | 1        | 1.15%   |
| JVC EM32FL AMR1007 1920x1080 700x390mm 31.5-inch                       | 1        | 1.15%   |
| INFOTRONIC L2130 ITR8852 1600x1200 432x324mm 21.3-inch                 | 1        | 1.15%   |
| Iiyama PL2480H IVM610B 1920x1080 520x290mm 23.4-inch                   | 1        | 1.15%   |
| Idek Iiyama LCD Monitor PL2492H                                        | 1        | 1.15%   |
| Hitachi HDMI    HEC0088 1920x1080 1100x560mm 48.6-inch                 | 1        | 1.15%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch             | 1        | 1.15%   |
| Hewlett-Packard Z23i HWP308F 1920x1080 509x286mm 23.0-inch             | 1        | 1.15%   |
| Hewlett-Packard V20 HPN36B3 1600x900 440x240mm 19.7-inch               | 1        | 1.15%   |
| Hewlett-Packard LCD Monitor w2007 1680x1050                            | 1        | 1.15%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 1        | 1.15%   |
| Goldstar WX942 GSM4B80 1440x900 408x255mm 18.9-inch                    | 1        | 1.15%   |
| Goldstar W2363 GSM572E 1680x1050 510x290mm 23.1-inch                   | 1        | 1.15%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                   | 1        | 1.15%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch               | 1        | 1.15%   |
| Goldstar ULTRAGEAR GSM775C 1920x1080 698x393mm 31.5-inch               | 1        | 1.15%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 1        | 1.15%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                  | 1        | 1.15%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 1        | 1.15%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1        | 1.15%   |
| Goldstar 27GL850 GSM5B80 2560x1440 697x392mm 31.5-inch                 | 1        | 1.15%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 1        | 1.15%   |
| Eizo S2100 ENC1803 1600x1200 432x324mm 21.3-inch                       | 1        | 1.15%   |
| Dell U2713HM DEL407E 2560x1440 597x336mm 27.0-inch                     | 1        | 1.15%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                    | 1        | 1.15%   |
| Dell P2414H DELA09A 1920x1080 527x297mm 23.8-inch                      | 1        | 1.15%   |
| Dell LCD Monitor UP3218K 7680x4320                                     | 1        | 1.15%   |
| Dell LCD Monitor UP3218K                                               | 1        | 1.15%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 1        | 1.15%   |
| Dell LCD Monitor E1911                                                 | 1        | 1.15%   |
| Dell E198WFP DELF005 1440x900 408x255mm 18.9-inch                      | 1        | 1.15%   |
| Dell 2408WFP DELA02C 1920x1200 519x324mm 24.1-inch                     | 1        | 1.15%   |
| BenQ ZOWIE XL LCD BNQ7F32 1920x1080 531x298mm 24.0-inch                | 1        | 1.15%   |
| BenQ GW2765 BNQ78D6 1920x1080 600x340mm 27.2-inch                      | 1        | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 28       | 35.9%   |
| 3840x2160 (4K)     | 9        | 11.54%  |
| 2560x1440 (QHD)    | 7        | 8.97%   |
| 1366x768 (WXGA)    | 4        | 5.13%   |
| 1280x1024 (SXGA)   | 4        | 5.13%   |
| Unknown            | 4        | 5.13%   |
| 1680x1050 (WSXGA+) | 3        | 3.85%   |
| 1600x900 (HD+)     | 3        | 3.85%   |
| 1440x900 (WXGA+)   | 3        | 3.85%   |
| 2560x1600          | 2        | 2.56%   |
| 1920x1200 (WUXGA)  | 2        | 2.56%   |
| 1600x1200          | 2        | 2.56%   |
| 7680x4320          | 1        | 1.28%   |
| 5760x1080          | 1        | 1.28%   |
| 4480x1440          | 1        | 1.28%   |
| 3360x1080          | 1        | 1.28%   |
| 2560x1080          | 1        | 1.28%   |
| 2288x1287          | 1        | 1.28%   |
| 1920x540           | 1        | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 13       | 16.67%  |
| 24      | 12       | 15.38%  |
| Unknown | 10       | 12.82%  |
| 27      | 9        | 11.54%  |
| 18      | 6        | 7.69%   |
| 31      | 5        | 6.41%   |
| 21      | 5        | 6.41%   |
| 20      | 3        | 3.85%   |
| 19      | 3        | 3.85%   |
| 17      | 3        | 3.85%   |
| 29      | 2        | 2.56%   |
| 142     | 1        | 1.28%   |
| 84      | 1        | 1.28%   |
| 55      | 1        | 1.28%   |
| 48      | 1        | 1.28%   |
| 34      | 1        | 1.28%   |
| 28      | 1        | 1.28%   |
| 16      | 1        | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 30       | 40.54%  |
| 401-500        | 16       | 21.62%  |
| Unknown        | 10       | 13.51%  |
| 601-700        | 8        | 10.81%  |
| 301-350        | 4        | 5.41%   |
| 1001-1500      | 2        | 2.7%    |
| More than 2000 | 1        | 1.35%   |
| 701-800        | 1        | 1.35%   |
| 351-400        | 1        | 1.35%   |
| 1501-2000      | 1        | 1.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 44       | 61.97%  |
| Unknown | 9        | 12.68%  |
| 16/10   | 7        | 9.86%   |
| 5/4     | 3        | 4.23%   |
| 4/3     | 3        | 4.23%   |
| 6/5     | 1        | 1.41%   |
| 3/2     | 1        | 1.41%   |
| 21/9    | 1        | 1.41%   |
| 1.96    | 1        | 1.41%   |
| 1.00    | 1        | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 29.73%  |
| Unknown        | 10       | 13.51%  |
| 351-500        | 9        | 12.16%  |
| 301-350        | 9        | 12.16%  |
| 151-200        | 9        | 12.16%  |
| 141-150        | 6        | 8.11%   |
| More than 1000 | 3        | 4.05%   |
| 251-300        | 3        | 4.05%   |
| 131-140        | 2        | 2.7%    |
| 501-1000       | 1        | 1.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 43       | 61.43%  |
| Unknown | 10       | 14.29%  |
| 101-120 | 7        | 10%     |
| 161-240 | 4        | 5.71%   |
| 121-160 | 4        | 5.71%   |
| 1-50    | 2        | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 64.62%  |
| 2     | 17       | 26.15%  |
| 3     | 3        | 4.62%   |
| 0     | 2        | 3.08%   |
| 4     | 1        | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 37       | 43.53%  |
| Intel                      | 30       | 35.29%  |
| Qualcomm Atheros           | 6        | 7.06%   |
| Broadcom                   | 4        | 4.71%   |
| Ralink Technology          | 2        | 2.35%   |
| ZTE WCDMA Technologies MSM | 1        | 1.18%   |
| TP-Link                    | 1        | 1.18%   |
| Microsoft                  | 1        | 1.18%   |
| Marvell Technology Group   | 1        | 1.18%   |
| D-Link                     | 1        | 1.18%   |
| Broadcom Limited           | 1        | 1.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 31       | 31.31%  |
| Intel I211 Gigabit Network Connection                                   | 7        | 7.07%   |
| Intel Ethernet Connection (2) I219-V                                    | 5        | 5.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4        | 4.04%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2        | 2.02%   |
| Intel Wireless 8260                                                     | 2        | 2.02%   |
| Intel Wireless 3165                                                     | 2        | 2.02%   |
| Intel Wi-Fi 6 AX200                                                     | 2        | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2        | 2.02%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                           | 1        | 1.01%   |
| TP-Link Archer T4U ver.3                                                | 1        | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 1.01%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1        | 1.01%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.01%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 1.01%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 1.01%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1        | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1        | 1.01%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 1.01%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 1.01%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1        | 1.01%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1        | 1.01%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1        | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 1.01%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 1.01%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1        | 1.01%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 1.01%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                 | 1        | 1.01%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                       | 1        | 1.01%   |
| Intel Wireless-AC 9260                                                  | 1        | 1.01%   |
| Intel Wireless 7260                                                     | 1        | 1.01%   |
| Intel I350 Gigabit Network Connection                                   | 1        | 1.01%   |
| Intel I210 Gigabit Network Connection                                   | 1        | 1.01%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                           | 1        | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                    | 1        | 1.01%   |
| Intel Ethernet Connection (6) I219-V                                    | 1        | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1        | 1.01%   |
| Intel Ethernet Connection (2) I218-V                                    | 1        | 1.01%   |
| Intel Ethernet Connection (14) I219-V                                   | 1        | 1.01%   |
| Intel 82583V Gigabit Network Connection                                 | 1        | 1.01%   |
| Intel 82579V Gigabit Network Connection                                 | 1        | 1.01%   |
| Intel 82578DM Gigabit Network Connection                                | 1        | 1.01%   |
| Intel 82578DC Gigabit Network Connection                                | 1        | 1.01%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 1        | 1.01%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 1.01%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                        | 1        | 1.01%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                        | 1        | 1.01%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                        | 1        | 1.01%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express         | 1        | 1.01%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1        | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 46.15%  |
| Realtek Semiconductor | 5        | 19.23%  |
| Qualcomm Atheros      | 3        | 11.54%  |
| Ralink Technology     | 2        | 7.69%   |
| TP-Link               | 1        | 3.85%   |
| Microsoft             | 1        | 3.85%   |
| D-Link                | 1        | 3.85%   |
| Broadcom              | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4        | 15.38%  |
| Intel Wireless 8260                                                     | 2        | 7.69%   |
| Intel Wireless 3165                                                     | 2        | 7.69%   |
| Intel Wi-Fi 6 AX200                                                     | 2        | 7.69%   |
| TP-Link Archer T4U ver.3                                                | 1        | 3.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 3.85%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1        | 3.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 3.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 3.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 3.85%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 3.85%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 3.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 3.85%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 3.85%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1        | 3.85%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 3.85%   |
| Intel Wireless-AC 9260                                                  | 1        | 3.85%   |
| Intel Wireless 7260                                                     | 1        | 3.85%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 3.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 35       | 50.72%  |
| Intel                    | 25       | 36.23%  |
| Qualcomm Atheros         | 4        | 5.8%    |
| Broadcom                 | 3        | 4.35%   |
| Marvell Technology Group | 1        | 1.45%   |
| Broadcom Limited         | 1        | 1.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31       | 43.06%  |
| Intel I211 Gigabit Network Connection                             | 7        | 9.72%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 6.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.78%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.39%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.39%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.39%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.39%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.39%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.39%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.39%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.39%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.39%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.39%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.39%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.39%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.39%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.39%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 1.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.39%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 1.39%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 64       | 70.33%  |
| WiFi     | 26       | 28.57%  |
| Modem    | 1        | 1.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 54       | 76.06%  |
| WiFi     | 17       | 23.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 53.85%  |
| 2     | 24       | 36.92%  |
| 3     | 4        | 6.15%   |
| 6     | 1        | 1.54%   |
| 0     | 1        | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 75.38%  |
| Yes  | 16       | 24.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 50%     |
| Cambridge Silicon Radio         | 5        | 25%     |
| ASUSTek Computer                | 2        | 10%     |
| Realtek Semiconductor           | 1        | 5%      |
| Qualcomm Atheros Communications | 1        | 5%      |
| Broadcom                        | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 25%     |
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 20%     |
| Intel Bluetooth wireless interface                  | 3        | 15%     |
| Intel AX200 Bluetooth                               | 2        | 10%     |
| Realtek Bluetooth Radio                             | 1        | 5%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 5%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 5%      |
| Broadcom BCM2035 Bluetooth dongle                   | 1        | 5%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5%      |
| ASUS Bluetooth Adapter                              | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 35       | 31.25%  |
| AMD                        | 29       | 25.89%  |
| Nvidia                     | 26       | 23.21%  |
| C-Media Electronics        | 8        | 7.14%   |
| Samson Technologies        | 2        | 1.79%   |
| GYROCOM C&C                | 2        | 1.79%   |
| Generalplus Technology     | 2        | 1.79%   |
| VIA Technologies           | 1        | 0.89%   |
| ROCCAT                     | 1        | 0.89%   |
| PreSonus Audio Electronics | 1        | 0.89%   |
| Logitech                   | 1        | 0.89%   |
| GN Netcom                  | 1        | 0.89%   |
| Creative Labs              | 1        | 0.89%   |
| Blue Microphones           | 1        | 0.89%   |
| Alesis                     | 1        | 0.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 13       | 10.16%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 4.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 4.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 4.69%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 3.91%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 3.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 3.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 3.13%   |
| AMD FCH Azalia Controller                                                  | 4        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 2.34%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 3        | 2.34%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.56%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.56%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 1.56%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.56%   |
| GYROCOM C&C Fiio E10                                                       | 2        | 1.56%   |
| Generalplus Technology USB Audio Device                                    | 2        | 1.56%   |
| C-Media Electronics USB Audio Device                                       | 2        | 1.56%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.56%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 0.78%   |
| Samson Technologies Q1U dynamic microphone                                 | 1        | 0.78%   |
| Samson Technologies Meteorite condenser microphone                         | 1        | 0.78%   |
| ROCCAT Juke                                                                | 1        | 0.78%   |
| PreSonus Audio Electronics PreSonus AudioBox iTwo                          | 1        | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.78%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.78%   |
| Nvidia GV100 TITAN V High Definition Audio Controller                      | 1        | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.78%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.78%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.78%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.78%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.78%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 0.78%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1        | 0.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1        | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.78%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 0.78%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 0.78%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 0.78%   |
| GN Netcom Jabra EVOLVE 20                                                  | 1        | 0.78%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 0.78%   |
| C-Media Electronics Multimedia Headset [Gigaware by Ignition L.P.]         | 1        | 0.78%   |
| C-Media Electronics CM106 Like Sound Device                                | 1        | 0.78%   |
| C-Media Electronics Blue Snowball                                          | 1        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 13       | 20.97%  |
| Corsair             | 10       | 16.13%  |
| Unknown             | 9        | 14.52%  |
| G.Skill             | 8        | 12.9%   |
| Crucial             | 7        | 11.29%  |
| SK Hynix            | 3        | 4.84%   |
| Samsung Electronics | 3        | 4.84%   |
| Team                | 2        | 3.23%   |
| A-DATA Technology   | 2        | 3.23%   |
| V-Color             | 1        | 1.61%   |
| Unknown (ABCD)      | 1        | 1.61%   |
| Kllisre             | 1        | 1.61%   |
| GeIL                | 1        | 1.61%   |
| Elpida              | 1        | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2        | 2.99%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s            | 2        | 2.99%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s         | 2        | 2.99%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 2        | 2.99%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s               | 1        | 1.49%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s     | 1        | 1.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 1.49%   |
| Unknown RAM Module 4GB DIMM 800MT/s                            | 1        | 1.49%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                     | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 1.49%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                     | 1        | 1.49%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                     | 1        | 1.49%   |
| Unknown RAM 7EH64AA# 8GB DIMM DDR4 2667MT/s                    | 1        | 1.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 1        | 1.49%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s             | 1        | 1.49%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                     | 1        | 1.49%   |
| SK Hynix RAM S949A4UUH-ITR 16GB DIMM DDR4 2400MT/s             | 1        | 1.49%   |
| SK Hynix RAM HMT325U7CFR8A-H9 2GB DIMM DDR3 1333MT/s           | 1        | 1.49%   |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s           | 1        | 1.49%   |
| Samsung RAM M386A8K40BM1-CRC 64GB RIMM DDR4 2400MT/s           | 1        | 1.49%   |
| Samsung RAM M378B5673FH0-CF8 2GB DIMM DDR3 1067MT/s            | 1        | 1.49%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 1        | 1.49%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s             | 1        | 1.49%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                     | 1        | 1.49%   |
| Kingston RAM KHX3333C16D4/16GX 16GB DIMM DDR4 2933MT/s         | 1        | 1.49%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 1        | 1.49%   |
| Kingston RAM KHX3000C15/16GX 16GB DIMM DDR4 3200MT/s           | 1        | 1.49%   |
| Kingston RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 1.49%   |
| Kingston RAM CL16-18-18 D4-3000 8192MB DIMM DDR4 3000MT/s      | 1        | 1.49%   |
| Kingston RAM 99U5584-017.A00LF 4096MB DIMM DDR3 1600MT/s       | 1        | 1.49%   |
| Kingston RAM 99U5471-039.A00LF 8GB DIMM DDR3 1600MT/s          | 1        | 1.49%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s          | 1        | 1.49%   |
| Kingston RAM 99U5471-032.A 4GB DIMM DDR3 800MT/s               | 1        | 1.49%   |
| Kingston RAM 9965684-013.A00G 8192MB DIMM DDR4 2667MT/s        | 1        | 1.49%   |
| Kingston RAM 9905744-067.A00G 32GB SODIMM DDR4 2667MT/s        | 1        | 1.49%   |
| Kingston RAM 9905670-012.A00G 8GB DIMM DDR4 2400MT/s           | 1        | 1.49%   |
| Kingston RAM 9905474-040.A00LF 4096MB DIMM DDR3 1333MT/s       | 1        | 1.49%   |
| GeIL RAM CL11-11-11 D3-1600 4096MB DIMM DDR3 1600MT/s          | 1        | 1.49%   |
| G.Skill RAM F4-3600C16-8GVKC 8GB DIMM DDR4 3600MT/s            | 1        | 1.49%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s         | 1        | 1.49%   |
| G.Skill RAM F3-1333C9-8GAO 8GB DIMM DDR3 1333MT/s              | 1        | 1.49%   |
| G.Skill RAM F3-12800CL9-4GBXL 4096MB DIMM DDR3 1600MT/s        | 1        | 1.49%   |
| Elpida RAM EBJ21UE8BDF0-AE-F 2GB DIMM DDR3 1067MT/s            | 1        | 1.49%   |
| Crucial RAM CT8G4SFS824A.C8FN 8GB SODIMM DDR4 2400MT/s         | 1        | 1.49%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s          | 1        | 1.49%   |
| Crucial RAM CT51264BA160B 4GB DIMM DDR3 1600MT/s               | 1        | 1.49%   |
| Crucial RAM CT4G4DFS6266.C4FJ 4GB DIMM DDR4 2666MT/s           | 1        | 1.49%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s          | 1        | 1.49%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s          | 1        | 1.49%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s       | 1        | 1.49%   |
| Crucial RAM BL8G32C16U4B.M8FE1 8GB DIMM DDR4 3200MT/s          | 1        | 1.49%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 1        | 1.49%   |
| Corsair RAM CMX4GX3M2A1600C9 2GB DIMM DDR3 1600MT/s            | 1        | 1.49%   |
| Corsair RAM CMV8GX4M1A2133C15 8GB DIMM DDR4 2133MT/s           | 1        | 1.49%   |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s            | 1        | 1.49%   |
| Corsair RAM CMV4GX4M1A2133C15 4GB DIMM DDR4 2133MT/s           | 1        | 1.49%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s            | 1        | 1.49%   |
| Corsair RAM CMK32GX4M2D3000C16 16384MB DIMM DDR4 3066MT/s      | 1        | 1.49%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 1        | 1.49%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s          | 1        | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 55.77%  |
| DDR3    | 19       | 36.54%  |
| Unknown | 3        | 5.77%   |
| LPDDR4  | 1        | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 49       | 94.23%  |
| SODIMM | 2        | 3.85%   |
| RIMM   | 1        | 1.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 21       | 36.84%  |
| 16384 | 14       | 24.56%  |
| 4096  | 13       | 22.81%  |
| 2048  | 5        | 8.77%   |
| 32768 | 3        | 5.26%   |
| 65536 | 1        | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 12       | 19.67%  |
| 1333  | 10       | 16.39%  |
| 3200  | 9        | 14.75%  |
| 2400  | 6        | 9.84%   |
| 2667  | 5        | 8.2%    |
| 3600  | 3        | 4.92%   |
| 3000  | 2        | 3.28%   |
| 2133  | 2        | 3.28%   |
| 1866  | 2        | 3.28%   |
| 800   | 2        | 3.28%   |
| 3500  | 1        | 1.64%   |
| 3466  | 1        | 1.64%   |
| 3066  | 1        | 1.64%   |
| 2933  | 1        | 1.64%   |
| 2666  | 1        | 1.64%   |
| 2465  | 1        | 1.64%   |
| 1867  | 1        | 1.64%   |
| 1067  | 1        | 1.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 75%     |
| Samsung Electronics | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Samsung ML-1660 Series | 1        | 25%     |
| HP LaserJet P1006      | 1        | 25%     |
| HP LaserJet M101-M106  | 1        | 25%     |
| HP LaserJet 1200       | 1        | 25%     |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 5        | 25%     |
| Microdia               | 4        | 20%     |
| Samsung Electronics    | 2        | 10%     |
| Generalplus Technology | 2        | 10%     |
| Xiongmai               | 1        | 5%      |
| Razer USA              | 1        | 5%      |
| Huawei Technologies    | 1        | 5%      |
| Hewlett-Packard        | 1        | 5%      |
| eMPIA Technology       | 1        | 5%      |
| AVerMedia Technologies | 1        | 5%      |
| ARC International      | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)  | 2        | 10%     |
| Microdia USB 2.0 Camera                  | 2        | 10%     |
| Logitech HD Pro Webcam C920              | 2        | 10%     |
| Xiongmai web camera                      | 1        | 5%      |
| Razer USA Razer Kiyo                     | 1        | 5%      |
| Microdia USB Live camera                 | 1        | 5%      |
| Microdia Integrated Camera               | 1        | 5%      |
| Logitech Webcam C260                     | 1        | 5%      |
| Logitech HD Webcam C615                  | 1        | 5%      |
| Logitech BRIO                            | 1        | 5%      |
| Huawei UVC Camera                        | 1        | 5%      |
| HP Webcam 3110                           | 1        | 5%      |
| Generalplus GENERAL WEBCAM               | 1        | 5%      |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 5%      |
| eMPIA M035 Compact Web Cam               | 1        | 5%      |
| AVerMedia Live Gamer Ultra-Video         | 1        | 5%      |
| ARC International Camera                 | 1        | 5%      |

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
| 0     | 60       | 92.31%  |
| 1     | 4        | 6.15%   |
| 5     | 1        | 1.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Unassigned class      | 2        | 40%     |
| Net/wireless          | 1        | 20%     |
| Multimedia controller | 1        | 20%     |
| Graphics card         | 1        | 20%     |

