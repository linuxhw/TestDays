Linux in Tunisia - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Tunisia.

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

Total: 48

| Vendor   | Model                 | Probe                                                      | Date         |
|----------|-----------------------|------------------------------------------------------------|--------------|
| Dell     | 0HMX8D A01            | [36b8532260](https://linux-hardware.org/?probe=36b8532260) | Mar 31, 2023 |
| Pegatron | Eureka3               | [9a13411e08](https://linux-hardware.org/?probe=9a13411e08) | Mar 14, 2023 |
| Dell     | 0HN7XN A01            | [167394f685](https://linux-hardware.org/?probe=167394f685) | Mar 04, 2023 |
| ASUSTek  | PRIME B450-PLUS       | [4cb7a5f214](https://linux-hardware.org/?probe=4cb7a5f214) | Jan 30, 2023 |
| Dell     | 0WMJ54 A01            | [778a84af28](https://linux-hardware.org/?probe=778a84af28) | Nov 28, 2022 |
| ASRock   | 970 Extreme4          | [27756e9ad7](https://linux-hardware.org/?probe=27756e9ad7) | Nov 20, 2022 |
| Intel    | H81                   | [f99a623867](https://linux-hardware.org/?probe=f99a623867) | Nov 17, 2022 |
| Intel    | H81                   | [5bfd56a1f8](https://linux-hardware.org/?probe=5bfd56a1f8) | Nov 17, 2022 |
| AZW      | Gemini M              | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| Pegatron | Benicia               | [f345c0beb9](https://linux-hardware.org/?probe=f345c0beb9) | Nov 11, 2022 |
| MSI      | H310M PRO-VDH PLUS    | [7b65a89d4f](https://linux-hardware.org/?probe=7b65a89d4f) | Nov 04, 2022 |
| MSI      | MS-B0A41              | [a0d7f23a22](https://linux-hardware.org/?probe=a0d7f23a22) | Oct 05, 2022 |
| ASUSTek  | PRIME Z690-P WIFI D4  | [ad367d006a](https://linux-hardware.org/?probe=ad367d006a) | Sep 22, 2022 |
| MSI      | A320M-A PRO MAX       | [eed790913e](https://linux-hardware.org/?probe=eed790913e) | Sep 16, 2022 |
| HP       | 2AF7                  | [7605e926c4](https://linux-hardware.org/?probe=7605e926c4) | Aug 25, 2022 |
| Lenovo   | 36C5 NOK              | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo   | 36C5 NOK              | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| Dell     | 05842Y A00            | [7c67079823](https://linux-hardware.org/?probe=7c67079823) | May 19, 2022 |
| MSI      | H81M-P33              | [af0e50e873](https://linux-hardware.org/?probe=af0e50e873) | Apr 14, 2022 |
| MSI      | B550M PRO-VDH         | [9597b0a2d9](https://linux-hardware.org/?probe=9597b0a2d9) | Apr 09, 2022 |
| ASUSTek  | PRIME B450M-K         | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| Intel    | H61                   | [6d80839afa](https://linux-hardware.org/?probe=6d80839afa) | Feb 09, 2022 |
| ASUSTek  | PRIME B450M-K         | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| ASUSTek  | PRIME B450M-K         | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| MSI      | H110M PRO-VD PLUS     | [e6fd06720f](https://linux-hardware.org/?probe=e6fd06720f) | Nov 28, 2021 |
| Gigabyte | B75M-D3H              | [b882e1c0f7](https://linux-hardware.org/?probe=b882e1c0f7) | Sep 22, 2021 |
| HP       | 1494                  | [ae5165603a](https://linux-hardware.org/?probe=ae5165603a) | Sep 09, 2021 |
| HP       | 1494                  | [62e74e0c1a](https://linux-hardware.org/?probe=62e74e0c1a) | Sep 09, 2021 |
| Lenovo   | SHARKBAY NOK          | [e57d0a5518](https://linux-hardware.org/?probe=e57d0a5518) | Sep 01, 2021 |
| Dell     | 0M5DCD A00            | [77faf70869](https://linux-hardware.org/?probe=77faf70869) | Jun 14, 2021 |
| Lenovo   | 3138 NO DPK           | [8488c59a11](https://linux-hardware.org/?probe=8488c59a11) | May 18, 2021 |
| ASUSTek  | PRIME B450M-K         | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| ASUSTek  | PRIME B450M-K         | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| Dell     | 0TTDMJ A00            | [aef24f2346](https://linux-hardware.org/?probe=aef24f2346) | Oct 28, 2020 |
| ASUSTek  | M32CD_A_F_K20CD_K31CD | [cdce66a7de](https://linux-hardware.org/?probe=cdce66a7de) | Jul 07, 2020 |
| Foxconn  | 2ABF                  | [65d6dca78e](https://linux-hardware.org/?probe=65d6dca78e) | May 27, 2020 |
| MSI      | MS-7502 Fab D         | [242c5b8d0d](https://linux-hardware.org/?probe=242c5b8d0d) | Mar 30, 2020 |
| Foxconn  | 2ABF                  | [7c6e2d2c29](https://linux-hardware.org/?probe=7c6e2d2c29) | Mar 10, 2020 |
| Pegatron | Eureka3               | [77bc52c3d9](https://linux-hardware.org/?probe=77bc52c3d9) | Mar 02, 2020 |
| Pegatron | Eureka3               | [84ee26b4e7](https://linux-hardware.org/?probe=84ee26b4e7) | Mar 02, 2020 |
| Pegatron | Eureka3               | [33ae5ebabc](https://linux-hardware.org/?probe=33ae5ebabc) | Feb 18, 2020 |
| Lenovo   | 3138 NO DPK           | [7878eb9e27](https://linux-hardware.org/?probe=7878eb9e27) | Dec 30, 2019 |
| Lenovo   | 3138 NO DPK           | [21f916c3ef](https://linux-hardware.org/?probe=21f916c3ef) | Dec 30, 2019 |
| Unknown  | Pine Trail - M CRB    | [ef1e6295a8](https://linux-hardware.org/?probe=ef1e6295a8) | Oct 30, 2019 |
| Foxconn  | 2ABF                  | [4521f814c9](https://linux-hardware.org/?probe=4521f814c9) | Sep 17, 2019 |
| Foxconn  | 2ABF                  | [6a57b2ea85](https://linux-hardware.org/?probe=6a57b2ea85) | Sep 17, 2019 |
| Pegatron | 2A94h                 | [3b6656bb11](https://linux-hardware.org/?probe=3b6656bb11) | Jul 04, 2019 |
| Foxconn  | 2ABF                  | [f6873739a8](https://linux-hardware.org/?probe=f6873739a8) | Mar 03, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 22.04       | 6        | 16.22%  |
| Ubuntu 18.04       | 5        | 13.51%  |
| Ubuntu 20.04       | 4        | 10.81%  |
| OpenMandriva 4.3   | 3        | 8.11%   |
| OpenMandriva 4.2   | 3        | 8.11%   |
| Ubuntu 19.10       | 2        | 5.41%   |
| Ubuntu 21.10       | 1        | 2.7%    |
| Ubuntu 19.04       | 1        | 2.7%    |
| Ubuntu 16.04       | 1        | 2.7%    |
| ROSA R10           | 1        | 2.7%    |
| ROSA 12.3          | 1        | 2.7%    |
| Pop!_OS 22.04      | 1        | 2.7%    |
| OpenMandriva 23.03 | 1        | 2.7%    |
| Linux Mint 21.1    | 1        | 2.7%    |
| Kali 2022.3        | 1        | 2.7%    |
| Gentoo 2.8         | 1        | 2.7%    |
| Gentoo 2.7         | 1        | 2.7%    |
| Debian 11          | 1        | 2.7%    |
| ArcoLinux Rolling  | 1        | 2.7%    |
| Arch               | 1        | 2.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 17       | 50%     |
| OpenMandriva | 7        | 20.59%  |
| ROSA         | 2        | 5.88%   |
| Gentoo       | 2        | 5.88%   |
| Pop!_OS      | 1        | 2.94%   |
| Linux Mint   | 1        | 2.94%   |
| Kali         | 1        | 2.94%   |
| Debian       | 1        | 2.94%   |
| ArcoLinux    | 1        | 2.94%   |
| Arch         | 1        | 2.94%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003            | 3        | 7.69%   |
| 5.10.14-desktop-1omv4002           | 3        | 7.69%   |
| 5.15.0-53-generic                  | 2        | 5.13%   |
| 6.2.6-desktop-1omv2390             | 1        | 2.56%   |
| 5.9.1-arch1-1                      | 1        | 2.56%   |
| 5.8.0-55-generic                   | 1        | 2.56%   |
| 5.4.0-73-generic                   | 1        | 2.56%   |
| 5.4.0-40-generic                   | 1        | 2.56%   |
| 5.4.0-31-generic                   | 1        | 2.56%   |
| 5.4.0-124-generic                  | 1        | 2.56%   |
| 5.3.0-40-generic                   | 1        | 2.56%   |
| 5.3.0-26-generic                   | 1        | 2.56%   |
| 5.3.0-19-generic                   | 1        | 2.56%   |
| 5.18.0-kali5-amd64                 | 1        | 2.56%   |
| 5.17.15-76051715-generic           | 1        | 2.56%   |
| 5.15.77-generic-1rosa2021.1-x86_64 | 1        | 2.56%   |
| 5.15.75-gentoo-dist                | 1        | 2.56%   |
| 5.15.5-arch1-1                     | 1        | 2.56%   |
| 5.15.11-gentoo                     | 1        | 2.56%   |
| 5.15.0-68-generic                  | 1        | 2.56%   |
| 5.15.0-60-generic                  | 1        | 2.56%   |
| 5.15.0-58-generic                  | 1        | 2.56%   |
| 5.15.0-48-generic                  | 1        | 2.56%   |
| 5.15.0-47-generic                  | 1        | 2.56%   |
| 5.13.0-39-generic                  | 1        | 2.56%   |
| 5.11.0-27-generic                  | 1        | 2.56%   |
| 5.10.27-gentoo                     | 1        | 2.56%   |
| 5.10.0-12-amd64                    | 1        | 2.56%   |
| 5.0.0-13-generic                   | 1        | 2.56%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 1        | 2.56%   |
| 4.4.0-176-generic                  | 1        | 2.56%   |
| 4.18.0-25-generic                  | 1        | 2.56%   |
| 4.15.0-91-generic                  | 1        | 2.56%   |
| 4.15.0-89-generic                  | 1        | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 7        | 17.95%  |
| 5.4.0   | 4        | 10.26%  |
| 5.3.0   | 3        | 7.69%   |
| 5.16.7  | 3        | 7.69%   |
| 5.10.14 | 3        | 7.69%   |
| 4.15.0  | 2        | 5.13%   |
| 6.2.6   | 1        | 2.56%   |
| 5.9.1   | 1        | 2.56%   |
| 5.8.0   | 1        | 2.56%   |
| 5.18.0  | 1        | 2.56%   |
| 5.17.15 | 1        | 2.56%   |
| 5.15.77 | 1        | 2.56%   |
| 5.15.75 | 1        | 2.56%   |
| 5.15.5  | 1        | 2.56%   |
| 5.15.11 | 1        | 2.56%   |
| 5.13.0  | 1        | 2.56%   |
| 5.11.0  | 1        | 2.56%   |
| 5.10.27 | 1        | 2.56%   |
| 5.10.0  | 1        | 2.56%   |
| 5.0.0   | 1        | 2.56%   |
| 4.9.60  | 1        | 2.56%   |
| 4.4.0   | 1        | 2.56%   |
| 4.18.0  | 1        | 2.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 11       | 28.21%  |
| 5.10    | 5        | 12.82%  |
| 5.4     | 4        | 10.26%  |
| 5.3     | 3        | 7.69%   |
| 5.16    | 3        | 7.69%   |
| 4.15    | 2        | 5.13%   |
| 6.2     | 1        | 2.56%   |
| 5.9     | 1        | 2.56%   |
| 5.8     | 1        | 2.56%   |
| 5.18    | 1        | 2.56%   |
| 5.17    | 1        | 2.56%   |
| 5.13    | 1        | 2.56%   |
| 5.11    | 1        | 2.56%   |
| 5.0     | 1        | 2.56%   |
| 4.9     | 1        | 2.56%   |
| 4.4     | 1        | 2.56%   |
| 4.18    | 1        | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 33       | 97.06%  |
| i686   | 1        | 2.94%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 17       | 47.22%  |
| KDE5            | 8        | 22.22%  |
| Unknown         | 5        | 13.89%  |
| XFCE            | 1        | 2.78%   |
| X-Cinnamon      | 1        | 2.78%   |
| KDE4            | 1        | 2.78%   |
| i3              | 1        | 2.78%   |
| GNOME Flashback | 1        | 2.78%   |
| Cinnamon        | 1        | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 24       | 68.57%  |
| Wayland | 10       | 28.57%  |
| Tty     | 1        | 2.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 33.33%  |
| SDDM    | 9        | 25%     |
| GDM3    | 8        | 22.22%  |
| GDM     | 5        | 13.89%  |
| LightDM | 1        | 2.78%   |
| KDM     | 1        | 2.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 15       | 42.86%  |
| fr_FR   | 12       | 34.29%  |
| Unknown | 4        | 11.43%  |
| fr_CA   | 1        | 2.86%   |
| en_AG   | 1        | 2.86%   |
| de_DE   | 1        | 2.86%   |
| ar_TN   | 1        | 2.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 18       | 51.43%  |
| BIOS | 17       | 48.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 27       | 79.41%  |
| Overlay | 6        | 17.65%  |
| Unknown | 1        | 2.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 15       | 41.67%  |
| Unknown | 15       | 41.67%  |
| MBR     | 6        | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 74.29%  |
| Yes       | 9        | 25.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 52.94%  |
| Yes       | 16       | 47.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 7        | 20.59%  |
| Dell                | 6        | 17.65%  |
| Pegatron            | 4        | 11.76%  |
| ASUSTek Computer    | 4        | 11.76%  |
| Lenovo              | 3        | 8.82%   |
| Intel               | 2        | 5.88%   |
| Hewlett-Packard     | 2        | 5.88%   |
| Foxconn             | 2        | 5.88%   |
| Gigabyte Technology | 1        | 2.94%   |
| AZW                 | 1        | 2.94%   |
| ASRock              | 1        | 2.94%   |
| Unknown             | 1        | 2.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Pegatron VS342AA-AB6 m9801af           | 2        | 5.88%   |
| Foxconn Pro 3400 Series MT             | 2        | 5.88%   |
| Pegatron Pro 3010 Microtower PC        | 1        | 2.94%   |
| Pegatron FL437AA-ABF a6641af           | 1        | 2.94%   |
| MSI PRO H510 DP21 (MS-B0A4)            | 1        | 2.94%   |
| MSI MS-7C95                            | 1        | 2.94%   |
| MSI MS-7C52                            | 1        | 2.94%   |
| MSI MS-7C09                            | 1        | 2.94%   |
| MSI MS-7A15                            | 1        | 2.94%   |
| MSI MS-7817                            | 1        | 2.94%   |
| MSI MS-7502                            | 1        | 2.94%   |
| Lenovo ThinkStation P330 30C6S33L00    | 1        | 2.94%   |
| Lenovo IdeaCentre 510-15IKL 90G8008EAL | 1        | 2.94%   |
| Lenovo H50-50 90B70040AL               | 1        | 2.94%   |
| Intel H81                              | 1        | 2.94%   |
| Intel H61                              | 1        | 2.94%   |
| HP Compaq 8200 Elite CMT PC            | 1        | 2.94%   |
| HP 500-440nkm                          | 1        | 2.94%   |
| Gigabyte B75M-D3H                      | 1        | 2.94%   |
| Dell OptiPlex 390                      | 1        | 2.94%   |
| Dell OptiPlex 380                      | 1        | 2.94%   |
| Dell OptiPlex 3090                     | 1        | 2.94%   |
| Dell OptiPlex 3070                     | 1        | 2.94%   |
| Dell OptiPlex 3040                     | 1        | 2.94%   |
| Dell OptiPlex 3020                     | 1        | 2.94%   |
| AZW Gemini M                           | 1        | 2.94%   |
| ASUS PRIME Z690-P WIFI D4              | 1        | 2.94%   |
| ASUS PRIME B450M-K                     | 1        | 2.94%   |
| ASUS PRIME B450-PLUS                   | 1        | 2.94%   |
| ASUS M32CD_A_F_K20CD_K31CD             | 1        | 2.94%   |
| ASRock 970 Extreme4                    | 1        | 2.94%   |
| Unknown                                | 1        | 2.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 6        | 17.65%  |
| ASUS PRIME           | 3        | 8.82%   |
| Pegatron VS342AA-AB6 | 2        | 5.88%   |
| Foxconn Pro          | 2        | 5.88%   |
| Pegatron Pro         | 1        | 2.94%   |
| Pegatron FL437AA-ABF | 1        | 2.94%   |
| MSI PRO              | 1        | 2.94%   |
| MSI MS-7C95          | 1        | 2.94%   |
| MSI MS-7C52          | 1        | 2.94%   |
| MSI MS-7C09          | 1        | 2.94%   |
| MSI MS-7A15          | 1        | 2.94%   |
| MSI MS-7817          | 1        | 2.94%   |
| MSI MS-7502          | 1        | 2.94%   |
| Lenovo ThinkStation  | 1        | 2.94%   |
| Lenovo IdeaCentre    | 1        | 2.94%   |
| Lenovo H50-50        | 1        | 2.94%   |
| Intel H81            | 1        | 2.94%   |
| Intel H61            | 1        | 2.94%   |
| HP Compaq            | 1        | 2.94%   |
| HP 500-440nkm        | 1        | 2.94%   |
| Gigabyte B75M-D3H    | 1        | 2.94%   |
| AZW Gemini           | 1        | 2.94%   |
| ASUS M32CD           | 1        | 2.94%   |
| ASRock 970           | 1        | 2.94%   |
| Unknown              | 1        | 2.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 5        | 14.71%  |
| 2011 | 5        | 14.71%  |
| 2021 | 3        | 8.82%   |
| 2018 | 3        | 8.82%   |
| 2009 | 3        | 8.82%   |
| 2020 | 2        | 5.88%   |
| 2016 | 2        | 5.88%   |
| 2015 | 2        | 5.88%   |
| 2014 | 2        | 5.88%   |
| 2012 | 2        | 5.88%   |
| 2017 | 1        | 2.94%   |
| 2013 | 1        | 2.94%   |
| 2010 | 1        | 2.94%   |
| 2008 | 1        | 2.94%   |
| 2007 | 1        | 2.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 34       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 32       | 94.12%  |
| Enabled  | 2        | 5.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 10       | 29.41%  |
| 16.01-24.0 | 7        | 20.59%  |
| 8.01-16.0  | 7        | 20.59%  |
| 1.01-2.0   | 5        | 14.71%  |
| 3.01-4.0   | 4        | 11.76%  |
| 32.01-64.0 | 1        | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 12       | 31.58%  |
| 1.01-2.0 | 12       | 31.58%  |
| 4.01-8.0 | 5        | 13.16%  |
| 3.01-4.0 | 5        | 13.16%  |
| 0.51-1.0 | 2        | 5.26%   |
| 0.01-0.5 | 2        | 5.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 60%     |
| 2      | 10       | 28.57%  |
| 4      | 2        | 5.71%   |
| 3      | 1        | 2.86%   |
| 0      | 1        | 2.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 55.88%  |
| Yes       | 15       | 44.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 57.14%  |
| Yes       | 15       | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 70.59%  |
| Yes       | 10       | 29.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Tunisia | 34       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Desktops | Percent |
|------------|----------|---------|
| Tunis      | 17       | 43.59%  |
| Aryanah    | 5        | 12.82%  |
| Sousse     | 2        | 5.13%   |
| Bizerte    | 2        | 5.13%   |
| Ben Arous  | 2        | 5.13%   |
| Sidi Abbes | 1        | 2.56%   |
| Sfax       | 1        | 2.56%   |
| Nabeul     | 1        | 2.56%   |
| Monastir   | 1        | 2.56%   |
| Mateur     | 1        | 2.56%   |
| Mahdia     | 1        | 2.56%   |
| Hammamet   | 1        | 2.56%   |
| Carthage   | 1        | 2.56%   |
| Beja       | 1        | 2.56%   |
| As Sanad   | 1        | 2.56%   |
| Akouda     | 1        | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 18     | 26.09%  |
| WDC                 | 11       | 14     | 23.91%  |
| Toshiba             | 5        | 5      | 10.87%  |
| Samsung Electronics | 4        | 6      | 8.7%    |
| Team                | 2        | 2      | 4.35%   |
| SanDisk             | 2        | 3      | 4.35%   |
| Kingston            | 2        | 2      | 4.35%   |
| PNY                 | 1        | 1      | 2.17%   |
| KVST                | 1        | 1      | 2.17%   |
| HS-SSD-E100         | 1        | 1      | 2.17%   |
| Hitachi             | 1        | 1      | 2.17%   |
| HGST                | 1        | 1      | 2.17%   |
| Emtec               | 1        | 3      | 2.17%   |
| China               | 1        | 1      | 2.17%   |
| addlink             | 1        | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB       | 4        | 7.84%   |
| WDC WD10EADS-65M2B0 1TB              | 2        | 3.92%   |
| Toshiba DT01ACA050 500GB             | 2        | 3.92%   |
| Seagate ST1000DM003-1SB102 1TB       | 2        | 3.92%   |
| WDC WD6400AAKS-65A7B0 640GB          | 1        | 1.96%   |
| WDC WD5000AVDS-63U7B1 500GB          | 1        | 1.96%   |
| WDC WD5000AAKS-402AA0 500GB          | 1        | 1.96%   |
| WDC WD5000AACS-00ZUB0 500GB          | 1        | 1.96%   |
| WDC WD3200AAJS-60M0A1 320GB          | 1        | 1.96%   |
| WDC WD2500AAJS-75M0A0 250GB          | 1        | 1.96%   |
| WDC WD10PURZ-85U8XY0 1TB             | 1        | 1.96%   |
| WDC WD10EZEX-75WN4A1 1TB             | 1        | 1.96%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 1.96%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1        | 1.96%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB | 1        | 1.96%   |
| Toshiba HDWD110 1TB                  | 1        | 1.96%   |
| Toshiba DT01ACA100 1TB               | 1        | 1.96%   |
| Toshiba DT01ABA200 2TB               | 1        | 1.96%   |
| Team T253X1480G 480GB SSD            | 1        | 1.96%   |
| Team T253X1240G 240GB SSD            | 1        | 1.96%   |
| Seagate ST500DM002-1SB10A 500GB      | 1        | 1.96%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 1.96%   |
| Seagate ST3500418AS 500GB            | 1        | 1.96%   |
| Seagate ST3500413AS 500GB            | 1        | 1.96%   |
| Seagate ST3320813AS 320GB            | 1        | 1.96%   |
| Seagate ST1000LM048-2E7172 1TB       | 1        | 1.96%   |
| Seagate ST1000DX001-1CM162 1TB       | 1        | 1.96%   |
| Seagate ST1000DM003-1ER162 1TB       | 1        | 1.96%   |
| SanDisk SDSSDA120G 120GB             | 1        | 1.96%   |
| SanDisk NVMe SSD Drive 512GB         | 1        | 1.96%   |
| Samsung SSD 980 500GB                | 1        | 1.96%   |
| Samsung SSD 860 EVO 500GB            | 1        | 1.96%   |
| Samsung SSD 850 EVO 250GB            | 1        | 1.96%   |
| Samsung PM991a NVMe 256GB            | 1        | 1.96%   |
| Samsung HD503HI 500GB                | 1        | 1.96%   |
| PNY CS900 960GB SSD                  | 1        | 1.96%   |
| KVST SSD 240GB                       | 1        | 1.96%   |
| Kingston SV300S37A120G 120GB SSD     | 1        | 1.96%   |
| Kingston SA400S37120G 120GB SSD      | 1        | 1.96%   |
| HS-SSD-E100 SSD 512G                 | 1        | 1.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 18     | 41.38%  |
| WDC                 | 9        | 12     | 31.03%  |
| Toshiba             | 5        | 5      | 17.24%  |
| Samsung Electronics | 1        | 1      | 3.45%   |
| Hitachi             | 1        | 1      | 3.45%   |
| HGST                | 1        | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Team                | 2        | 2      | 16.67%  |
| Kingston            | 2        | 2      | 16.67%  |
| SanDisk             | 1        | 1      | 8.33%   |
| Samsung Electronics | 1        | 3      | 8.33%   |
| PNY                 | 1        | 1      | 8.33%   |
| KVST                | 1        | 1      | 8.33%   |
| HS-SSD-E100         | 1        | 1      | 8.33%   |
| Emtec               | 1        | 3      | 8.33%   |
| China               | 1        | 1      | 8.33%   |
| addlink             | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 38     | 64.29%  |
| SSD  | 11       | 16     | 26.19%  |
| NVMe | 4        | 6      | 9.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 32       | 54     | 88.89%  |
| NVMe | 4        | 6      | 11.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 27     | 55.26%  |
| 0.51-1.0   | 16       | 26     | 42.11%  |
| 1.01-2.0   | 1        | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 10       | 28.57%  |
| 101-250    | 9        | 25.71%  |
| 501-1000   | 7        | 20%     |
| 1001-2000  | 3        | 8.57%   |
| 21-50      | 2        | 5.71%   |
| 2001-3000  | 1        | 2.86%   |
| 1-20       | 1        | 2.86%   |
| 51-100     | 1        | 2.86%   |
| Unknown    | 1        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 16       | 42.11%  |
| 21-50     | 9        | 23.68%  |
| 101-250   | 5        | 13.16%  |
| 51-100    | 4        | 10.53%  |
| 251-500   | 1        | 2.63%   |
| 1001-2000 | 1        | 2.63%   |
| 501-1000  | 1        | 2.63%   |
| Unknown   | 1        | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD6400AAKS-65A7B0 640GB    | 1        | 1      | 14.29%  |
| Seagate ST3500413AS 500GB      | 1        | 1      | 14.29%  |
| Seagate ST3320813AS 320GB      | 1        | 1      | 14.29%  |
| Seagate ST1000DM010-2EP102 1TB | 1        | 1      | 14.29%  |
| Hitachi HTS547575A9E384 752GB  | 1        | 1      | 14.29%  |
| HGST HTS545050A7E380 500GB     | 1        | 1      | 14.29%  |
| Emtec X250 512GB               | 1        | 2      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 42.86%  |
| WDC     | 1        | 1      | 14.29%  |
| Hitachi | 1        | 1      | 14.29%  |
| HGST    | 1        | 1      | 14.29%  |
| Emtec   | 1        | 2      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 50%     |
| WDC     | 1        | 1      | 16.67%  |
| Hitachi | 1        | 1      | 16.67%  |
| HGST    | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 6      | 85.71%  |
| SSD  | 1        | 2      | 14.29%  |

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
| Works    | 18       | 30     | 47.37%  |
| Detected | 13       | 22     | 34.21%  |
| Malfunc  | 7        | 8      | 18.42%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 29       | 76.32%  |
| AMD                 | 5        | 13.16%  |
| SanDisk             | 2        | 5.26%   |
| Samsung Electronics | 2        | 5.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 8.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 6.12%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 6.12%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 6.12%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 4.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 4.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 4.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 4.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 4.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 2.04%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 2.04%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 2.04%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 2.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 2.04%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 2.04%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 2.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 2.04%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 2.04%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 2.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 2.04%   |
| AMD FCH SATA Controller D                                                               | 1        | 2.04%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 23       | 57.5%   |
| IDE  | 11       | 27.5%   |
| NVMe | 4        | 10%     |
| RAID | 2        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 29       | 85.29%  |
| AMD    | 5        | 14.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Pentium CPU G4560 @ 3.50GHz               | 2        | 5.88%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz           | 2        | 5.88%   |
| Intel Xeon E-2144G CPU @ 3.60GHz                | 1        | 2.94%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1        | 2.94%   |
| Intel Pentium CPU G630 @ 2.70GHz                | 1        | 2.94%   |
| Intel Pentium CPU G3250 @ 3.20GHz               | 1        | 2.94%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1        | 2.94%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1        | 2.94%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 2.94%   |
| Intel Core i7-4790S CPU @ 3.20GHz               | 1        | 2.94%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1        | 2.94%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 2.94%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1        | 2.94%   |
| Intel Core i5-4460S CPU @ 2.90GHz               | 1        | 2.94%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 2.94%   |
| Intel Core i3-6100 CPU @ 3.70GHz                | 1        | 2.94%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 2.94%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 2.94%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 2.94%   |
| Intel Core i3-10105T CPU @ 3.00GHz              | 1        | 2.94%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz           | 1        | 2.94%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz           | 1        | 2.94%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 2.94%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1        | 2.94%   |
| Intel Atom CPU N455 @ 1.66GHz                   | 1        | 2.94%   |
| Intel 12th Gen Core i7-12700K                   | 1        | 2.94%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 1        | 2.94%   |
| AMD Ryzen 5 PRO 3400G with Radeon Vega Graphics | 1        | 2.94%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1        | 2.94%   |
| AMD Ryzen 5 3600XT 6-Core Processor             | 1        | 2.94%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 2.94%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium           | 5        | 14.71%  |
| Intel Core i7           | 5        | 14.71%  |
| Intel Core i3           | 5        | 14.71%  |
| Intel Core 2 Quad       | 5        | 14.71%  |
| Intel Core i5           | 3        | 8.82%   |
| AMD Ryzen 5             | 3        | 8.82%   |
| Other                   | 2        | 5.88%   |
| Intel Xeon              | 1        | 2.94%   |
| Intel Pentium Dual-Core | 1        | 2.94%   |
| Intel Celeron           | 1        | 2.94%   |
| Intel Atom              | 1        | 2.94%   |
| AMD Ryzen 5 PRO         | 1        | 2.94%   |
| AMD FX                  | 1        | 2.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 15       | 44.12%  |
| 2       | 10       | 29.41%  |
| 6       | 4        | 11.76%  |
| 8       | 2        | 5.88%   |
| 12      | 1        | 2.94%   |
| 1       | 1        | 2.94%   |
| Unknown | 1        | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 34       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 20       | 57.14%  |
| 1       | 14       | 40%     |
| Unknown | 1        | 2.86%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 34       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 18.92%  |
| 0x206a7    | 5        | 13.51%  |
| 0x1067a    | 4        | 10.81%  |
| 0x306c3    | 3        | 8.11%   |
| 0x906ea    | 2        | 5.41%   |
| 0x506e3    | 2        | 5.41%   |
| 0xa0671    | 1        | 2.7%    |
| 0xa0653    | 1        | 2.7%    |
| 0x906e9    | 1        | 2.7%    |
| 0x90672    | 1        | 2.7%    |
| 0x706a8    | 1        | 2.7%    |
| 0x6fb      | 1        | 2.7%    |
| 0x306a9    | 1        | 2.7%    |
| 0x106ca    | 1        | 2.7%    |
| 0x10677    | 1        | 2.7%    |
| 0x08701013 | 1        | 2.7%    |
| 0x08108109 | 1        | 2.7%    |
| 0x0800820d | 1        | 2.7%    |
| 0x06000852 | 1        | 2.7%    |
| 0x00000000 | 1        | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 5        | 14.71%  |
| Penryn           | 5        | 14.71%  |
| KabyLake         | 5        | 14.71%  |
| Haswell          | 5        | 14.71%  |
| Zen+             | 2        | 5.88%   |
| Skylake          | 2        | 5.88%   |
| Zen 3            | 1        | 2.94%   |
| Zen 2            | 1        | 2.94%   |
| Piledriver       | 1        | 2.94%   |
| IvyBridge        | 1        | 2.94%   |
| Icelake          | 1        | 2.94%   |
| Goldmont plus    | 1        | 2.94%   |
| Core             | 1        | 2.94%   |
| CometLake        | 1        | 2.94%   |
| Bonnell          | 1        | 2.94%   |
| Alderlake Hybrid | 1        | 2.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 17       | 47.22%  |
| Intel  | 16       | 44.44%  |
| AMD    | 3        | 8.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GT218 [GeForce 210]                                                  | 3        | 8.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 8.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 5.56%   |
| Nvidia GF119 [GeForce GT 520]                                               | 2        | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 5.56%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.78%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 2.78%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 2.78%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 2.78%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 2.78%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 2.78%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 2.78%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.78%   |
| Nvidia G96 [GeForce 9500 GS]                                                | 1        | 2.78%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 2.78%   |
| Intel HD Graphics 610                                                       | 1        | 2.78%   |
| Intel HD Graphics 530                                                       | 1        | 2.78%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 2.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                  | 1        | 2.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.78%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 2.78%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 2.78%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 2.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 17       | 50%     |
| 1 x Intel  | 14       | 41.18%  |
| 1 x AMD    | 3        | 8.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 27       | 77.14%  |
| Proprietary | 7        | 20%     |
| Unknown     | 1        | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 45.95%  |
| 1.01-2.0   | 10       | 27.03%  |
| 5.01-6.0   | 4        | 10.81%  |
| 0.51-1.0   | 3        | 8.11%   |
| 3.01-4.0   | 2        | 5.41%   |
| 0.01-0.5   | 1        | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 13       | 37.14%  |
| Hewlett-Packard     | 9        | 25.71%  |
| MSI                 | 2        | 5.71%   |
| S2-Tek              | 1        | 2.86%   |
| PKB                 | 1        | 2.86%   |
| Philips             | 1        | 2.86%   |
| Packard Bell        | 1        | 2.86%   |
| Medion              | 1        | 2.86%   |
| Lenovo              | 1        | 2.86%   |
| HPN                 | 1        | 2.86%   |
| GDH                 | 1        | 2.86%   |
| Dell                | 1        | 2.86%   |
| BenQ                | 1        | 2.86%   |
| AU Optronics        | 1        | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 5        | 13.51%  |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2        | 5.41%   |
| Hewlett-Packard x20LED HWP2910 1600x900 443x249mm 20.0-inch          | 2        | 5.41%   |
| Hewlett-Packard P224 HPN361E 1920x1080 527x296mm 23.8-inch           | 2        | 5.41%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch | 1        | 2.7%    |
| Samsung Electronics SyncMaster SAM0284 1280x1024 338x270mm 17.0-inch | 1        | 2.7%    |
| Samsung Electronics SMB2240 SAM06AD 1920x1080 477x268mm 21.5-inch    | 1        | 2.7%    |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch | 1        | 2.7%    |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch     | 1        | 2.7%    |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 1        | 2.7%    |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 1        | 2.7%    |
| S2-Tek TV STK531A 1920x1080 930x530mm 42.1-inch                      | 1        | 2.7%    |
| PKB LCD Monitor VIS220WS 1680x1050                                   | 1        | 2.7%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1        | 2.7%    |
| Packard Bell PKB VIS220WS PKB5064 1680x1050 460x290mm 21.4-inch      | 1        | 2.7%    |
| MSI MP271 MSI30A2 1920x1080 598x336mm 27.0-inch                      | 1        | 2.7%    |
| MSI MP242 MSI30A1 1920x1080 527x296mm 23.8-inch                      | 1        | 2.7%    |
| Medion MD30422PV MED86F6 1680x1050 474x296mm 22.0-inch               | 1        | 2.7%    |
| Lenovo T24v-10 LEN61BC 1920x1080 527x296mm 23.8-inch                 | 1        | 2.7%    |
| HPN LCD Monitor HP Z23n G2                                           | 1        | 2.7%    |
| Hewlett-Packard LE2001w HWP2841 1600x900 440x250mm 19.9-inch         | 1        | 2.7%    |
| Hewlett-Packard LCD Monitor 2011 1600x900                            | 1        | 2.7%    |
| Hewlett-Packard L1940T HWP2682 1280x1024 376x301mm 19.0-inch         | 1        | 2.7%    |
| Hewlett-Packard E24i G4 HPN368F 1920x1200 518x324mm 24.1-inch        | 1        | 2.7%    |
| Hewlett-Packard 2011 HWP2935 1600x900 443x249mm 20.0-inch            | 1        | 2.7%    |
| Hewlett-Packard 2011 HWP2934 1600x900 443x249mm 20.0-inch            | 1        | 2.7%    |
| GDH Digital TV GDH0030 1920x540                                      | 1        | 2.7%    |
| Dell S2721HGF DEL41E8 1920x1080 600x340mm 27.2-inch                  | 1        | 2.7%    |
| BenQ T201W BNQ7719 1680x1050 433x271mm 20.1-inch                     | 1        | 2.7%    |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch        | 1        | 2.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 51.52%  |
| 1600x900 (HD+)     | 6        | 18.18%  |
| 1680x1050 (WSXGA+) | 3        | 9.09%   |
| 1366x768 (WXGA)    | 2        | 6.06%   |
| 1280x1024 (SXGA)   | 2        | 6.06%   |
| 3840x2160 (4K)     | 1        | 3.03%   |
| 1024x600           | 1        | 3.03%   |
| Unknown            | 1        | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 10       | 28.57%  |
| 20      | 5        | 14.29%  |
| 24      | 3        | 8.57%   |
| 21      | 3        | 8.57%   |
| Unknown | 3        | 8.57%   |
| 27      | 2        | 5.71%   |
| 22      | 2        | 5.71%   |
| 19      | 2        | 5.71%   |
| 52      | 1        | 2.86%   |
| 42      | 1        | 2.86%   |
| 18      | 1        | 2.86%   |
| 17      | 1        | 2.86%   |
| 10      | 1        | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 42.42%  |
| 401-500     | 11       | 33.33%  |
| Unknown     | 3        | 9.09%   |
| 351-400     | 1        | 3.03%   |
| 301-350     | 1        | 3.03%   |
| 201-300     | 1        | 3.03%   |
| 1001-1500   | 1        | 3.03%   |
| 901-1000    | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 25       | 73.53%  |
| 16/10   | 4        | 11.76%  |
| Unknown | 3        | 8.82%   |
| 5/4     | 2        | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 16       | 45.71%  |
| 151-200        | 8        | 22.86%  |
| Unknown        | 3        | 8.57%   |
| 301-350        | 2        | 5.71%   |
| 141-150        | 2        | 5.71%   |
| More than 1000 | 1        | 2.86%   |
| 41-50          | 1        | 2.86%   |
| 251-300        | 1        | 2.86%   |
| 501-1000       | 1        | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 26       | 78.79%  |
| 101-120 | 3        | 9.09%   |
| Unknown | 3        | 9.09%   |
| 1-50    | 1        | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 85.29%  |
| 2     | 4        | 11.76%  |
| 0     | 1        | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 30       | 62.5%   |
| Intel                 | 8        | 16.67%  |
| Ralink Technology     | 4        | 8.33%   |
| Ralink                | 3        | 6.25%   |
| Samsung Electronics   | 1        | 2.08%   |
| IMC Networks          | 1        | 2.08%   |
| Broadcom              | 1        | 2.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 26       | 48.15%  |
| Ralink MT7601U Wireless Adapter                                        | 4        | 7.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 5.56%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2        | 3.7%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1        | 1.85%   |
| Intel Wireless 7265                                                    | 1        | 1.85%   |
| Intel Wireless 3165                                                    | 1        | 1.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1        | 1.85%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.85%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1        | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 1.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 1.85%   |
| Intel 82562V-2 10/100 Network Connection                               | 1        | 1.85%   |
| IMC Networks AW-NU222 802.11bgn Wireless Module [Ralink RT2770+RT2720] | 1        | 1.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1        | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 29.41%  |
| Realtek Semiconductor | 4        | 23.53%  |
| Ralink Technology     | 4        | 23.53%  |
| Ralink                | 3        | 17.65%  |
| IMC Networks          | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                        | 4        | 23.53%  |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2        | 11.76%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 5.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 5.88%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 5.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 5.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1        | 5.88%   |
| Intel Wireless 7265                                                    | 1        | 5.88%   |
| Intel Wireless 3165                                                    | 1        | 5.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1        | 5.88%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 5.88%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 5.88%   |
| IMC Networks AW-NU222 802.11bgn Wireless Module [Ralink RT2770+RT2720] | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 30       | 83.33%  |
| Intel                 | 4        | 11.11%  |
| Samsung Electronics   | 1        | 2.78%   |
| Broadcom              | 1        | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26       | 70.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 8.11%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.7%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.7%    |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.7%    |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 2.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 34       | 69.39%  |
| WiFi     | 15       | 30.61%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 77.78%  |
| WiFi     | 8        | 22.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 64.71%  |
| 2     | 12       | 35.29%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 5        | 50%     |
| Cambridge Silicon Radio | 3        | 30%     |
| Ralink                  | 1        | 10%     |
| IMC Networks            | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX201 Bluetooth                               | 3        | 30%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 30%     |
| Intel Bluetooth wireless interface                  | 2        | 20%     |
| Ralink RT3290 Bluetooth                             | 1        | 10%     |
| IMC Networks Bluetooth Radio                        | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 30       | 54.55%  |
| Nvidia                  | 16       | 29.09%  |
| AMD                     | 7        | 12.73%  |
| Xiamen VBeT Electronics | 1        | 1.82%   |
| Lenovo                  | 1        | 1.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5        | 8.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5        | 8.62%   |
| Nvidia High Definition Audio Controller                                           | 3        | 5.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 5.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 5.17%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 3.45%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 3.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 3.45%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 3.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 3.45%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 3.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 3.45%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 3.45%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 3.45%   |
| Xiamen VBeT Electronics VT X208                                                   | 1        | 1.72%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 1.72%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 1.72%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 1.72%   |
| Lenovo ThinkVision T24v Wide Monitor for USB-Audio                                | 1        | 1.72%   |
| Intel USB PnP Sound Device                                                        | 1        | 1.72%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1        | 1.72%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 1.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 1.72%   |
| Intel Alder Lake-S HD Audio Controller                                            | 1        | 1.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 1.72%   |
| AMD Family 17h/19h HD Audio Controller                                            | 1        | 1.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 1.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 1.72%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 1.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 4        | 14.81%  |
| SK hynix            | 4        | 14.81%  |
| Samsung Electronics | 4        | 14.81%  |
| Micron Technology   | 3        | 11.11%  |
| TwinMOS             | 2        | 7.41%   |
| Team                | 2        | 7.41%   |
| Unknown (ABCD)      | 1        | 3.7%    |
| PNY                 | 1        | 3.7%    |
| Patriot             | 1        | 3.7%    |
| Melco               | 1        | 3.7%    |
| GOODRAM             | 1        | 3.7%    |
| Elpida              | 1        | 3.7%    |
| Crucial             | 1        | 3.7%    |
| 0BBA00000000        | 1        | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 3.7%    |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 3.7%    |
| Unknown RAM Module 4GB DIMM DDR3                               | 1        | 3.7%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                         | 1        | 3.7%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 3.7%    |
| TwinMOS RAM 9DSDBNZB-5AMP 4GB DIMM DDR3 1333MT/s               | 1        | 3.7%    |
| TwinMOS RAM 9D7TBNZB-TATP 4096MB DIMM DDR3 1066MT/s            | 1        | 3.7%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s            | 1        | 3.7%    |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s             | 1        | 3.7%    |
| SK hynix RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1        | 3.7%    |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s          | 1        | 3.7%    |
| SK hynix RAM HMA82GU7CJR8N-VK 16384MB DIMM DDR4 2667MT/s       | 1        | 3.7%    |
| SK hynix RAM HMA81GU6CJR8N-VK 8192MB DIMM DDR4 2667MT/s        | 1        | 3.7%    |
| Samsung RAM Module 4096MB DIMM DDR3 1333MT/s                   | 1        | 3.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1        | 3.7%    |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s            | 1        | 3.7%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 3.7%    |
| PNY RAM 8GBF1X08LIII43-12-K 8GB DIMM DDR4 2667MT/s             | 1        | 3.7%    |
| Patriot RAM 3000 C15 Series 8GB DIMM DDR4 3000MT/s             | 1        | 3.7%    |
| Micron RAM ITC 1024MB DIMM DDR2 1648MT/s                       | 1        | 3.7%    |
| Micron RAM 8JTF25664AZ-1G4M1 2048MB DIMM DDR3 1333MT/s         | 1        | 3.7%    |
| Micron RAM 4ATF1G64HZ-3G2B2 8GB SODIMM DDR4 3200MT/s           | 1        | 3.7%    |
| Melco RAM Module 2GB DIMM DDR2 667MT/s                         | 1        | 3.7%    |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s             | 1        | 3.7%    |
| Elpida RAM HMT451S6AFR8C-H9 4GB DIMM DDR3                      | 1        | 3.7%    |
| Crucial RAM BL16G32C16U4B.16FE 16384MB DIMM DDR4 3200MT/s      | 1        | 3.7%    |
| 0BBA00000000 RAM KBN1333D3N9/4G 4096MB DIMM DDR3 1066MT/s      | 1        | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 9        | 42.86%  |
| DDR3    | 8        | 38.1%   |
| SDRAM   | 1        | 4.76%   |
| LPDDR4  | 1        | 4.76%   |
| DDR2    | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 18       | 90%     |
| SODIMM | 2        | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 6        | 28.57%  |
| 8192  | 5        | 23.81%  |
| 16384 | 4        | 19.05%  |
| 2048  | 4        | 19.05%  |
| 32768 | 1        | 4.76%   |
| 1024  | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 4        | 17.39%  |
| 3200    | 3        | 13.04%  |
| 2667    | 3        | 13.04%  |
| 2400    | 2        | 8.7%    |
| 1600    | 2        | 8.7%    |
| 1066    | 2        | 8.7%    |
| 667     | 2        | 8.7%    |
| 49926   | 1        | 4.35%   |
| 3800    | 1        | 4.35%   |
| 3000    | 1        | 4.35%   |
| 1648    | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 75%     |
| Seiko Epson     | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP LaserJet P1005       | 2        | 50%     |
| Seiko Epson L365 Series | 1        | 25%     |
| HP DeskJet 5810 series  | 1        | 25%     |

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


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| Syntek     | 1        | 50%     |
| Cubeternet | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Syntek Integrated RGB Camera | 1        | 50%     |
| Cubeternet WebCam            | 1        | 50%     |

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
| 0     | 30       | 81.08%  |
| 1     | 5        | 13.51%  |
| 2     | 2        | 5.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 5        | 62.5%   |
| Net/wireless  | 1        | 12.5%   |
| Net/ethernet  | 1        | 12.5%   |
| Bluetooth     | 1        | 12.5%   |

