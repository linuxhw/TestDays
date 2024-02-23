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

Total: 55

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ECS           | G31T-M9                     | [30204f2a00](https://linux-hardware.org/?probe=30204f2a00) | Dec 14, 2023 |
| ECS           | G31T-M9                     | [783af811f2](https://linux-hardware.org/?probe=783af811f2) | Nov 16, 2023 |
| Intel         | H81                         | [34f1a336e3](https://linux-hardware.org/?probe=34f1a336e3) | Sep 14, 2023 |
| Dell          | 0J8G6F A03                  | [490dd7a710](https://linux-hardware.org/?probe=490dd7a710) | Sep 04, 2023 |
| Intel         | H81                         | [98f445e831](https://linux-hardware.org/?probe=98f445e831) | Sep 03, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [3e63b3dec0](https://linux-hardware.org/?probe=3e63b3dec0) | Aug 09, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [a036ddad16](https://linux-hardware.org/?probe=a036ddad16) | Aug 09, 2023 |
| Dell          | 0HMX8D A01                  | [36b8532260](https://linux-hardware.org/?probe=36b8532260) | Mar 31, 2023 |
| Pegatron      | Eureka3                     | [9a13411e08](https://linux-hardware.org/?probe=9a13411e08) | Mar 14, 2023 |
| Dell          | 0HN7XN A01                  | [167394f685](https://linux-hardware.org/?probe=167394f685) | Mar 04, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [4cb7a5f214](https://linux-hardware.org/?probe=4cb7a5f214) | Jan 30, 2023 |
| Dell          | 0WMJ54 A01                  | [778a84af28](https://linux-hardware.org/?probe=778a84af28) | Nov 28, 2022 |
| ASRock        | 970 Extreme4                | [27756e9ad7](https://linux-hardware.org/?probe=27756e9ad7) | Nov 20, 2022 |
| Intel         | H81                         | [f99a623867](https://linux-hardware.org/?probe=f99a623867) | Nov 17, 2022 |
| Intel         | H81                         | [5bfd56a1f8](https://linux-hardware.org/?probe=5bfd56a1f8) | Nov 17, 2022 |
| AZW           | Gemini M                    | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| Pegatron      | Benicia                     | [f345c0beb9](https://linux-hardware.org/?probe=f345c0beb9) | Nov 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [7b65a89d4f](https://linux-hardware.org/?probe=7b65a89d4f) | Nov 04, 2022 |
| MSI           | MS-B0A41                    | [a0d7f23a22](https://linux-hardware.org/?probe=a0d7f23a22) | Oct 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [ad367d006a](https://linux-hardware.org/?probe=ad367d006a) | Sep 22, 2022 |
| MSI           | A320M-A PRO MAX             | [eed790913e](https://linux-hardware.org/?probe=eed790913e) | Sep 16, 2022 |
| HP            | 2AF7                        | [7605e926c4](https://linux-hardware.org/?probe=7605e926c4) | Aug 25, 2022 |
| Lenovo        | 36C5 NOK                    | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| Dell          | 05842Y A00                  | [7c67079823](https://linux-hardware.org/?probe=7c67079823) | May 19, 2022 |
| MSI           | H81M-P33                    | [af0e50e873](https://linux-hardware.org/?probe=af0e50e873) | Apr 14, 2022 |
| MSI           | B550M PRO-VDH               | [9597b0a2d9](https://linux-hardware.org/?probe=9597b0a2d9) | Apr 09, 2022 |
| ASUSTek       | PRIME B450M-K               | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| Intel         | H61                         | [6d80839afa](https://linux-hardware.org/?probe=6d80839afa) | Feb 09, 2022 |
| ASUSTek       | PRIME B450M-K               | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| MSI           | H110M PRO-VD PLUS           | [e6fd06720f](https://linux-hardware.org/?probe=e6fd06720f) | Nov 28, 2021 |
| Gigabyte      | B75M-D3H                    | [b882e1c0f7](https://linux-hardware.org/?probe=b882e1c0f7) | Sep 22, 2021 |
| HP            | 1494                        | [ae5165603a](https://linux-hardware.org/?probe=ae5165603a) | Sep 09, 2021 |
| HP            | 1494                        | [62e74e0c1a](https://linux-hardware.org/?probe=62e74e0c1a) | Sep 09, 2021 |
| Lenovo        | SHARKBAY NOK                | [e57d0a5518](https://linux-hardware.org/?probe=e57d0a5518) | Sep 01, 2021 |
| Dell          | 0M5DCD A00                  | [77faf70869](https://linux-hardware.org/?probe=77faf70869) | Jun 14, 2021 |
| Lenovo        | 3138 NO DPK                 | [8488c59a11](https://linux-hardware.org/?probe=8488c59a11) | May 18, 2021 |
| ASUSTek       | PRIME B450M-K               | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| ASUSTek       | PRIME B450M-K               | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| Dell          | 0TTDMJ A00                  | [aef24f2346](https://linux-hardware.org/?probe=aef24f2346) | Oct 28, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [cdce66a7de](https://linux-hardware.org/?probe=cdce66a7de) | Jul 07, 2020 |
| Foxconn       | 2ABF                        | [65d6dca78e](https://linux-hardware.org/?probe=65d6dca78e) | May 27, 2020 |
| MSI           | MS-7502 Fab D               | [242c5b8d0d](https://linux-hardware.org/?probe=242c5b8d0d) | Mar 30, 2020 |
| Foxconn       | 2ABF                        | [7c6e2d2c29](https://linux-hardware.org/?probe=7c6e2d2c29) | Mar 10, 2020 |
| Pegatron      | Eureka3                     | [77bc52c3d9](https://linux-hardware.org/?probe=77bc52c3d9) | Mar 02, 2020 |
| Pegatron      | Eureka3                     | [84ee26b4e7](https://linux-hardware.org/?probe=84ee26b4e7) | Mar 02, 2020 |
| Pegatron      | Eureka3                     | [33ae5ebabc](https://linux-hardware.org/?probe=33ae5ebabc) | Feb 18, 2020 |
| Lenovo        | 3138 NO DPK                 | [7878eb9e27](https://linux-hardware.org/?probe=7878eb9e27) | Dec 30, 2019 |
| Lenovo        | 3138 NO DPK                 | [21f916c3ef](https://linux-hardware.org/?probe=21f916c3ef) | Dec 30, 2019 |
| Unknown       | Pine Trail - M CRB          | [ef1e6295a8](https://linux-hardware.org/?probe=ef1e6295a8) | Oct 30, 2019 |
| Foxconn       | 2ABF                        | [4521f814c9](https://linux-hardware.org/?probe=4521f814c9) | Sep 17, 2019 |
| Foxconn       | 2ABF                        | [6a57b2ea85](https://linux-hardware.org/?probe=6a57b2ea85) | Sep 17, 2019 |
| Pegatron      | 2A94h                       | [3b6656bb11](https://linux-hardware.org/?probe=3b6656bb11) | Jul 04, 2019 |
| Foxconn       | 2ABF                        | [f6873739a8](https://linux-hardware.org/?probe=f6873739a8) | Mar 03, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 22.04       | 6        | 14.29%  |
| Ubuntu 18.04       | 5        | 11.9%   |
| Ubuntu 20.04       | 4        | 9.52%   |
| OpenMandriva 4.3   | 3        | 7.14%   |
| OpenMandriva 4.2   | 3        | 7.14%   |
| OpenMandriva 23.08 | 3        | 7.14%   |
| Ubuntu 19.10       | 2        | 4.76%   |
| Ubuntu 21.10       | 1        | 2.38%   |
| Ubuntu 19.04       | 1        | 2.38%   |
| Ubuntu 16.04       | 1        | 2.38%   |
| ROSA R10           | 1        | 2.38%   |
| ROSA 12.3          | 1        | 2.38%   |
| Pop!_OS 22.04      | 1        | 2.38%   |
| OpenMandriva 23.03 | 1        | 2.38%   |
| Linux Mint 21.2    | 1        | 2.38%   |
| Linux Mint 21.1    | 1        | 2.38%   |
| Kali 2022.3        | 1        | 2.38%   |
| Gentoo 2.8         | 1        | 2.38%   |
| Gentoo 2.7         | 1        | 2.38%   |
| Devuan 3           | 1        | 2.38%   |
| Debian 11          | 1        | 2.38%   |
| ArcoLinux Rolling  | 1        | 2.38%   |
| Arch               | 1        | 2.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 17       | 43.59%  |
| OpenMandriva | 10       | 25.64%  |
| ROSA         | 2        | 5.13%   |
| Linux Mint   | 2        | 5.13%   |
| Gentoo       | 2        | 5.13%   |
| Pop!_OS      | 1        | 2.56%   |
| Kali         | 1        | 2.56%   |
| Devuan       | 1        | 2.56%   |
| Debian       | 1        | 2.56%   |
| ArcoLinux    | 1        | 2.56%   |
| Arch         | 1        | 2.56%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 6.4.11-desktop-1omv2390            | 3        | 6.82%   |
| 5.16.7-desktop-1omv4003            | 3        | 6.82%   |
| 5.10.14-desktop-1omv4002           | 3        | 6.82%   |
| 5.15.0-53-generic                  | 2        | 4.55%   |
| 6.2.6-desktop-1omv2390             | 1        | 2.27%   |
| 6.2.0-36-generic                   | 1        | 2.27%   |
| 5.9.1-arch1-1                      | 1        | 2.27%   |
| 5.8.0-55-generic                   | 1        | 2.27%   |
| 5.4.0-73-generic                   | 1        | 2.27%   |
| 5.4.0-40-generic                   | 1        | 2.27%   |
| 5.4.0-31-generic                   | 1        | 2.27%   |
| 5.4.0-124-generic                  | 1        | 2.27%   |
| 5.3.0-40-generic                   | 1        | 2.27%   |
| 5.3.0-26-generic                   | 1        | 2.27%   |
| 5.3.0-19-generic                   | 1        | 2.27%   |
| 5.18.0-kali5-amd64                 | 1        | 2.27%   |
| 5.17.15-76051715-generic           | 1        | 2.27%   |
| 5.15.77-generic-1rosa2021.1-x86_64 | 1        | 2.27%   |
| 5.15.75-gentoo-dist                | 1        | 2.27%   |
| 5.15.5-arch1-1                     | 1        | 2.27%   |
| 5.15.11-gentoo                     | 1        | 2.27%   |
| 5.15.0-68-generic                  | 1        | 2.27%   |
| 5.15.0-60-generic                  | 1        | 2.27%   |
| 5.15.0-58-generic                  | 1        | 2.27%   |
| 5.15.0-48-generic                  | 1        | 2.27%   |
| 5.15.0-47-generic                  | 1        | 2.27%   |
| 5.13.0-39-generic                  | 1        | 2.27%   |
| 5.11.0-27-generic                  | 1        | 2.27%   |
| 5.10.27-gentoo                     | 1        | 2.27%   |
| 5.10.0-12-amd64                    | 1        | 2.27%   |
| 5.0.0-13-generic                   | 1        | 2.27%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 1        | 2.27%   |
| 4.4.0-176-generic                  | 1        | 2.27%   |
| 4.19.0-10-amd64                    | 1        | 2.27%   |
| 4.18.0-25-generic                  | 1        | 2.27%   |
| 4.15.0-91-generic                  | 1        | 2.27%   |
| 4.15.0-89-generic                  | 1        | 2.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 7        | 15.91%  |
| 5.4.0   | 4        | 9.09%   |
| 6.4.11  | 3        | 6.82%   |
| 5.3.0   | 3        | 6.82%   |
| 5.16.7  | 3        | 6.82%   |
| 5.10.14 | 3        | 6.82%   |
| 4.15.0  | 2        | 4.55%   |
| 6.2.6   | 1        | 2.27%   |
| 6.2.0   | 1        | 2.27%   |
| 5.9.1   | 1        | 2.27%   |
| 5.8.0   | 1        | 2.27%   |
| 5.18.0  | 1        | 2.27%   |
| 5.17.15 | 1        | 2.27%   |
| 5.15.77 | 1        | 2.27%   |
| 5.15.75 | 1        | 2.27%   |
| 5.15.5  | 1        | 2.27%   |
| 5.15.11 | 1        | 2.27%   |
| 5.13.0  | 1        | 2.27%   |
| 5.11.0  | 1        | 2.27%   |
| 5.10.27 | 1        | 2.27%   |
| 5.10.0  | 1        | 2.27%   |
| 5.0.0   | 1        | 2.27%   |
| 4.9.60  | 1        | 2.27%   |
| 4.4.0   | 1        | 2.27%   |
| 4.19.0  | 1        | 2.27%   |
| 4.18.0  | 1        | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 11       | 25%     |
| 5.10    | 5        | 11.36%  |
| 5.4     | 4        | 9.09%   |
| 6.4     | 3        | 6.82%   |
| 5.3     | 3        | 6.82%   |
| 5.16    | 3        | 6.82%   |
| 6.2     | 2        | 4.55%   |
| 4.15    | 2        | 4.55%   |
| 5.9     | 1        | 2.27%   |
| 5.8     | 1        | 2.27%   |
| 5.18    | 1        | 2.27%   |
| 5.17    | 1        | 2.27%   |
| 5.13    | 1        | 2.27%   |
| 5.11    | 1        | 2.27%   |
| 5.0     | 1        | 2.27%   |
| 4.9     | 1        | 2.27%   |
| 4.4     | 1        | 2.27%   |
| 4.19    | 1        | 2.27%   |
| 4.18    | 1        | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 37       | 97.37%  |
| i686   | 1        | 2.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 18       | 45%     |
| KDE5            | 9        | 22.5%   |
| Unknown         | 5        | 12.5%   |
| XFCE            | 2        | 5%      |
| X-Cinnamon      | 1        | 2.5%    |
| MATE            | 1        | 2.5%    |
| KDE4            | 1        | 2.5%    |
| i3              | 1        | 2.5%    |
| GNOME Flashback | 1        | 2.5%    |
| Cinnamon        | 1        | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 26       | 66.67%  |
| Wayland | 12       | 30.77%  |
| Tty     | 1        | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 35%     |
| SDDM    | 10       | 25%     |
| GDM3    | 8        | 20%     |
| GDM     | 6        | 15%     |
| LightDM | 1        | 2.5%    |
| KDM     | 1        | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 17       | 43.59%  |
| fr_FR   | 14       | 35.9%   |
| Unknown | 4        | 10.26%  |
| fr_CA   | 1        | 2.56%   |
| en_AG   | 1        | 2.56%   |
| de_DE   | 1        | 2.56%   |
| ar_TN   | 1        | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 20       | 51.28%  |
| EFI  | 19       | 48.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 30       | 78.95%  |
| Overlay | 7        | 18.42%  |
| Unknown | 1        | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 18       | 43.9%   |
| Unknown | 16       | 39.02%  |
| MBR     | 7        | 17.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 71.79%  |
| Yes       | 11       | 28.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 57.89%  |
| Yes       | 16       | 42.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 7        | 18.42%  |
| Dell                | 7        | 18.42%  |
| Pegatron            | 4        | 10.53%  |
| ASUSTek Computer    | 4        | 10.53%  |
| Lenovo              | 3        | 7.89%   |
| Intel               | 3        | 7.89%   |
| Hewlett-Packard     | 2        | 5.26%   |
| Foxconn             | 2        | 5.26%   |
| LORD ELECTRONICS    | 1        | 2.63%   |
| Gigabyte Technology | 1        | 2.63%   |
| ECS                 | 1        | 2.63%   |
| AZW                 | 1        | 2.63%   |
| ASRock              | 1        | 2.63%   |
| Unknown             | 1        | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Pegatron VS342AA-AB6 m9801af                      | 2        | 5.26%   |
| Intel H81                                         | 2        | 5.26%   |
| Foxconn Pro 3400 Series MT                        | 2        | 5.26%   |
| Pegatron Pro 3010 Microtower PC                   | 1        | 2.63%   |
| Pegatron FL437AA-ABF a6641af                      | 1        | 2.63%   |
| MSI PRO H510 DP21 (MS-B0A4)                       | 1        | 2.63%   |
| MSI MS-7C95                                       | 1        | 2.63%   |
| MSI MS-7C52                                       | 1        | 2.63%   |
| MSI MS-7C09                                       | 1        | 2.63%   |
| MSI MS-7A15                                       | 1        | 2.63%   |
| MSI MS-7817                                       | 1        | 2.63%   |
| MSI MS-7502                                       | 1        | 2.63%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 1        | 2.63%   |
| Lenovo ThinkStation P330 30C6S33L00               | 1        | 2.63%   |
| Lenovo IdeaCentre 510-15IKL 90G8008EAL            | 1        | 2.63%   |
| Lenovo H50-50 90B70040AL                          | 1        | 2.63%   |
| Intel H61                                         | 1        | 2.63%   |
| HP Compaq 8200 Elite CMT PC                       | 1        | 2.63%   |
| HP 500-440nkm                                     | 1        | 2.63%   |
| Gigabyte B75M-D3H                                 | 1        | 2.63%   |
| ECS G31T-M9                                       | 1        | 2.63%   |
| Dell OptiPlex 5060                                | 1        | 2.63%   |
| Dell OptiPlex 390                                 | 1        | 2.63%   |
| Dell OptiPlex 380                                 | 1        | 2.63%   |
| Dell OptiPlex 3090                                | 1        | 2.63%   |
| Dell OptiPlex 3070                                | 1        | 2.63%   |
| Dell OptiPlex 3040                                | 1        | 2.63%   |
| Dell OptiPlex 3020                                | 1        | 2.63%   |
| AZW Gemini M                                      | 1        | 2.63%   |
| ASUS PRIME Z690-P WIFI D4                         | 1        | 2.63%   |
| ASUS PRIME B450M-K                                | 1        | 2.63%   |
| ASUS PRIME B450-PLUS                              | 1        | 2.63%   |
| ASUS M32CD_A_F_K20CD_K31CD                        | 1        | 2.63%   |
| ASRock 970 Extreme4                               | 1        | 2.63%   |
| Unknown                                           | 1        | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 7        | 18.42%  |
| ASUS PRIME            | 3        | 7.89%   |
| Pegatron VS342AA-AB6  | 2        | 5.26%   |
| Intel H81             | 2        | 5.26%   |
| Foxconn Pro           | 2        | 5.26%   |
| Pegatron Pro          | 1        | 2.63%   |
| Pegatron FL437AA-ABF  | 1        | 2.63%   |
| MSI PRO               | 1        | 2.63%   |
| MSI MS-7C95           | 1        | 2.63%   |
| MSI MS-7C52           | 1        | 2.63%   |
| MSI MS-7C09           | 1        | 2.63%   |
| MSI MS-7A15           | 1        | 2.63%   |
| MSI MS-7817           | 1        | 2.63%   |
| MSI MS-7502           | 1        | 2.63%   |
| LORD ELECTRONICS LORD | 1        | 2.63%   |
| Lenovo ThinkStation   | 1        | 2.63%   |
| Lenovo IdeaCentre     | 1        | 2.63%   |
| Lenovo H50-50         | 1        | 2.63%   |
| Intel H61             | 1        | 2.63%   |
| HP Compaq             | 1        | 2.63%   |
| HP 500-440nkm         | 1        | 2.63%   |
| Gigabyte B75M-D3H     | 1        | 2.63%   |
| ECS G31T-M9           | 1        | 2.63%   |
| AZW Gemini            | 1        | 2.63%   |
| ASUS M32CD            | 1        | 2.63%   |
| ASRock 970            | 1        | 2.63%   |
| Unknown               | 1        | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 6        | 15.79%  |
| 2011 | 5        | 13.16%  |
| 2021 | 4        | 10.53%  |
| 2009 | 4        | 10.53%  |
| 2018 | 3        | 7.89%   |
| 2016 | 3        | 7.89%   |
| 2020 | 2        | 5.26%   |
| 2015 | 2        | 5.26%   |
| 2014 | 2        | 5.26%   |
| 2012 | 2        | 5.26%   |
| 2017 | 1        | 2.63%   |
| 2013 | 1        | 2.63%   |
| 2010 | 1        | 2.63%   |
| 2008 | 1        | 2.63%   |
| 2007 | 1        | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 38       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 36       | 94.74%  |
| Enabled  | 2        | 5.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 11       | 28.95%  |
| 8.01-16.0  | 8        | 21.05%  |
| 16.01-24.0 | 7        | 18.42%  |
| 3.01-4.0   | 5        | 13.16%  |
| 1.01-2.0   | 5        | 13.16%  |
| 32.01-64.0 | 1        | 2.63%   |
| 2.01-3.0   | 1        | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 16       | 36.36%  |
| 2.01-3.0 | 13       | 29.55%  |
| 4.01-8.0 | 5        | 11.36%  |
| 3.01-4.0 | 5        | 11.36%  |
| 0.51-1.0 | 3        | 6.82%   |
| 0.01-0.5 | 2        | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 57.5%   |
| 2      | 12       | 30%     |
| 4      | 3        | 7.5%    |
| 3      | 1        | 2.5%    |
| 0      | 1        | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 58.97%  |
| Yes       | 16       | 41.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 38       | 100%    |

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
| No        | 27       | 71.05%  |
| Yes       | 11       | 28.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Tunisia | 38       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| Tunis       | 18       | 40%     |
| Aryanah     | 6        | 13.33%  |
| Nabeul      | 3        | 6.67%   |
| Sousse      | 2        | 4.44%   |
| Bizerte     | 2        | 4.44%   |
| Ben Arous   | 2        | 4.44%   |
| Sidi Abbes  | 1        | 2.22%   |
| Sfax        | 1        | 2.22%   |
| Monastir    | 1        | 2.22%   |
| Mateur      | 1        | 2.22%   |
| Mahdia      | 1        | 2.22%   |
| Ksar Hellal | 1        | 2.22%   |
| Hammamet    | 1        | 2.22%   |
| Ezzouhour   | 1        | 2.22%   |
| Carthage    | 1        | 2.22%   |
| Beja        | 1        | 2.22%   |
| As Sanad    | 1        | 2.22%   |
| Akouda      | 1        | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 17     | 25%     |
| Seagate             | 12       | 18     | 23.08%  |
| Toshiba             | 7        | 9      | 13.46%  |
| Samsung Electronics | 4        | 6      | 7.69%   |
| Team                | 2        | 2      | 3.85%   |
| SanDisk             | 2        | 4      | 3.85%   |
| PNY                 | 2        | 2      | 3.85%   |
| Kingston            | 2        | 2      | 3.85%   |
| Lexar               | 1        | 1      | 1.92%   |
| KVST                | 1        | 1      | 1.92%   |
| HS-SSD-E100         | 1        | 2      | 1.92%   |
| Hitachi             | 1        | 1      | 1.92%   |
| HGST                | 1        | 1      | 1.92%   |
| Emtec               | 1        | 3      | 1.92%   |
| China               | 1        | 1      | 1.92%   |
| addlink             | 1        | 1      | 1.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB       | 4        | 6.9%    |
| WDC WD10EADS-65M2B0 1TB              | 2        | 3.45%   |
| Toshiba MQ01ABD075 752GB             | 2        | 3.45%   |
| Toshiba DT01ACA050 500GB             | 2        | 3.45%   |
| Seagate ST1000DM003-1SB102 1TB       | 2        | 3.45%   |
| WDC WD6400AAKS-65A7B0 640GB          | 1        | 1.72%   |
| WDC WD5000AVDS-63U7B1 500GB          | 1        | 1.72%   |
| WDC WD5000AAKS-402AA0 500GB          | 1        | 1.72%   |
| WDC WD5000AACS-00ZUB0 500GB          | 1        | 1.72%   |
| WDC WD3200AAJS-60M0A1 320GB          | 1        | 1.72%   |
| WDC WD2500AAJS-75M0A0 249GB          | 1        | 1.72%   |
| WDC WD1600AVVS-63L2B0 160GB          | 1        | 1.72%   |
| WDC WD10PURZ-85U8XY0 1TB             | 1        | 1.72%   |
| WDC WD10EZEX-75WN4A1 1TB             | 1        | 1.72%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 1.72%   |
| WDC WD10EZEX-00BBHA0 1TB             | 1        | 1.72%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1        | 1.72%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB | 1        | 1.72%   |
| Toshiba HDWD120 2TB                  | 1        | 1.72%   |
| Toshiba HDWD110 1TB                  | 1        | 1.72%   |
| Toshiba DT01ACA100 1TB               | 1        | 1.72%   |
| Toshiba DT01ABA200 2TB               | 1        | 1.72%   |
| Team T253X1480G 480GB SSD            | 1        | 1.72%   |
| Team T253X1240G 240GB SSD            | 1        | 1.72%   |
| Seagate ST500DM002-1SB10A 500GB      | 1        | 1.72%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 1.72%   |
| Seagate ST3500418AS 500GB            | 1        | 1.72%   |
| Seagate ST3500413AS 500GB            | 1        | 1.72%   |
| Seagate ST3320813AS 320GB            | 1        | 1.72%   |
| Seagate ST1000LM048-2E7172 1TB       | 1        | 1.72%   |
| Seagate ST1000DX001-1CM162 1TB       | 1        | 1.72%   |
| Seagate ST1000DM003-1ER162 1TB       | 1        | 1.72%   |
| SanDisk SDSSDA120G 120GB             | 1        | 1.72%   |
| SanDisk NVMe SSD Drive 512GB         | 1        | 1.72%   |
| Samsung SSD 980 500GB                | 1        | 1.72%   |
| Samsung SSD 860 EVO 500GB            | 1        | 1.72%   |
| Samsung SSD 850 EVO 250GB            | 1        | 1.72%   |
| Samsung PM991a NVMe 256GB            | 1        | 1.72%   |
| Samsung HD503HI 500GB                | 1        | 1.72%   |
| PNY CS900 960GB SSD                  | 1        | 1.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 18     | 36.36%  |
| WDC                 | 11       | 15     | 33.33%  |
| Toshiba             | 7        | 9      | 21.21%  |
| Samsung Electronics | 1        | 1      | 3.03%   |
| Hitachi             | 1        | 1      | 3.03%   |
| HGST                | 1        | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Team                | 2        | 2      | 14.29%  |
| PNY                 | 2        | 2      | 14.29%  |
| Kingston            | 2        | 2      | 14.29%  |
| SanDisk             | 1        | 2      | 7.14%   |
| Samsung Electronics | 1        | 3      | 7.14%   |
| Lexar               | 1        | 1      | 7.14%   |
| KVST                | 1        | 1      | 7.14%   |
| HS-SSD-E100         | 1        | 2      | 7.14%   |
| Emtec               | 1        | 3      | 7.14%   |
| China               | 1        | 1      | 7.14%   |
| addlink             | 1        | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 31       | 45     | 64.58%  |
| SSD  | 13       | 20     | 27.08%  |
| NVMe | 4        | 6      | 8.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 35       | 64     | 87.5%   |
| NVMe | 4        | 6      | 10%     |
| SAS  | 1        | 1      | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 32     | 54.55%  |
| 0.51-1.0   | 18       | 30     | 40.91%  |
| 1.01-2.0   | 2        | 3      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 13       | 32.5%   |
| 251-500    | 10       | 25%     |
| 501-1000   | 8        | 20%     |
| 1001-2000  | 3        | 7.5%    |
| 21-50      | 2        | 5%      |
| 2001-3000  | 1        | 2.5%    |
| 1-20       | 1        | 2.5%    |
| 51-100     | 1        | 2.5%    |
| Unknown    | 1        | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 18       | 40.91%  |
| 21-50     | 12       | 27.27%  |
| 101-250   | 5        | 11.36%  |
| 51-100    | 5        | 11.36%  |
| 251-500   | 1        | 2.27%   |
| 1001-2000 | 1        | 2.27%   |
| 501-1000  | 1        | 2.27%   |
| Unknown   | 1        | 2.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD6400AAKS-65A7B0 640GB    | 1        | 1      | 12.5%   |
| Toshiba MQ01ABD075 752GB       | 1        | 1      | 12.5%   |
| Seagate ST3500413AS 500GB      | 1        | 1      | 12.5%   |
| Seagate ST3320813AS 320GB      | 1        | 1      | 12.5%   |
| Seagate ST1000DM010-2EP102 1TB | 1        | 1      | 12.5%   |
| Hitachi HTS547575A9E384 752GB  | 1        | 1      | 12.5%   |
| HGST HTS545050A7E380 500GB     | 1        | 1      | 12.5%   |
| Emtec X250 512GB               | 1        | 2      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 37.5%   |
| WDC     | 1        | 1      | 12.5%   |
| Toshiba | 1        | 1      | 12.5%   |
| Hitachi | 1        | 1      | 12.5%   |
| HGST    | 1        | 1      | 12.5%   |
| Emtec   | 1        | 2      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 42.86%  |
| WDC     | 1        | 1      | 14.29%  |
| Toshiba | 1        | 1      | 14.29%  |
| Hitachi | 1        | 1      | 14.29%  |
| HGST    | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 7      | 87.5%   |
| SSD  | 1        | 2      | 12.5%   |

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
| Works    | 20       | 37     | 46.51%  |
| Detected | 15       | 25     | 34.88%  |
| Malfunc  | 8        | 9      | 18.6%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 32       | 78.05%  |
| AMD                 | 5        | 12.2%   |
| SanDisk             | 2        | 4.88%   |
| Samsung Electronics | 2        | 4.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 7.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 7.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 5.56%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 5.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 5.56%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 5.56%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 2        | 3.7%    |
| Intel SATA Controller [RAID mode]                                                       | 2        | 3.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 3.7%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 3.7%    |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 3.7%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 1        | 1.85%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 1        | 1.85%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 1.85%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.85%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.85%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 1.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.85%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.85%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 23       | 53.49%  |
| IDE  | 13       | 30.23%  |
| NVMe | 4        | 9.3%    |
| RAID | 3        | 6.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 33       | 86.84%  |
| AMD    | 5        | 13.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Pentium CPU G4560 @ 3.50GHz               | 2        | 5.26%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz           | 2        | 5.26%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz           | 2        | 5.26%   |
| Intel Xeon E-2144G CPU @ 3.60GHz                | 1        | 2.63%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1        | 2.63%   |
| Intel Pentium CPU G630 @ 2.70GHz                | 1        | 2.63%   |
| Intel Pentium CPU G3250 @ 3.20GHz               | 1        | 2.63%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1        | 2.63%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1        | 2.63%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 2.63%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 2.63%   |
| Intel Core i7-4790S CPU @ 3.20GHz               | 1        | 2.63%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1        | 2.63%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 2.63%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1        | 2.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 2.63%   |
| Intel Core i5-4460S CPU @ 2.90GHz               | 1        | 2.63%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 2.63%   |
| Intel Core i3-6100 CPU @ 3.70GHz                | 1        | 2.63%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 2.63%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 2.63%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 2.63%   |
| Intel Core i3-10105T CPU @ 3.00GHz              | 1        | 2.63%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 2.63%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz           | 1        | 2.63%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 2.63%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1        | 2.63%   |
| Intel Atom CPU N455 @ 1.66GHz                   | 1        | 2.63%   |
| Intel 12th Gen Core i7-12700K                   | 1        | 2.63%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 1        | 2.63%   |
| AMD Ryzen 5 PRO 3400G with Radeon Vega Graphics | 1        | 2.63%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1        | 2.63%   |
| AMD Ryzen 5 3600XT 6-Core Processor             | 1        | 2.63%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 2.63%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core 2 Quad       | 7        | 18.42%  |
| Intel Core i7           | 6        | 15.79%  |
| Intel Pentium           | 5        | 13.16%  |
| Intel Core i3           | 5        | 13.16%  |
| Intel Core i5           | 4        | 10.53%  |
| AMD Ryzen 5             | 3        | 7.89%   |
| Other                   | 2        | 5.26%   |
| Intel Xeon              | 1        | 2.63%   |
| Intel Pentium Dual-Core | 1        | 2.63%   |
| Intel Celeron           | 1        | 2.63%   |
| Intel Atom              | 1        | 2.63%   |
| AMD Ryzen 5 PRO         | 1        | 2.63%   |
| AMD FX                  | 1        | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 18       | 47.37%  |
| 2       | 10       | 26.32%  |
| 6       | 5        | 13.16%  |
| 8       | 2        | 5.26%   |
| 12      | 1        | 2.63%   |
| 1       | 1        | 2.63%   |
| Unknown | 1        | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 38       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 21       | 53.85%  |
| 1       | 17       | 43.59%  |
| Unknown | 1        | 2.56%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 38       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 26.19%  |
| 0x206a7    | 5        | 11.9%   |
| 0x1067a    | 5        | 11.9%   |
| 0x306c3    | 3        | 7.14%   |
| 0x906ea    | 2        | 4.76%   |
| 0x506e3    | 2        | 4.76%   |
| 0xa0671    | 1        | 2.38%   |
| 0xa0653    | 1        | 2.38%   |
| 0x906e9    | 1        | 2.38%   |
| 0x90672    | 1        | 2.38%   |
| 0x706a8    | 1        | 2.38%   |
| 0x6fb      | 1        | 2.38%   |
| 0x306a9    | 1        | 2.38%   |
| 0x106ca    | 1        | 2.38%   |
| 0x10677    | 1        | 2.38%   |
| 0x08701013 | 1        | 2.38%   |
| 0x08108109 | 1        | 2.38%   |
| 0x0800820d | 1        | 2.38%   |
| 0x06000852 | 1        | 2.38%   |
| 0x00000000 | 1        | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 7        | 18.42%  |
| KabyLake         | 6        | 15.79%  |
| Haswell          | 6        | 15.79%  |
| SandyBridge      | 5        | 13.16%  |
| Zen+             | 2        | 5.26%   |
| Skylake          | 2        | 5.26%   |
| Zen 3            | 1        | 2.63%   |
| Zen 2            | 1        | 2.63%   |
| Piledriver       | 1        | 2.63%   |
| IvyBridge        | 1        | 2.63%   |
| Icelake          | 1        | 2.63%   |
| Goldmont plus    | 1        | 2.63%   |
| Core             | 1        | 2.63%   |
| CometLake        | 1        | 2.63%   |
| Bonnell          | 1        | 2.63%   |
| Alderlake Hybrid | 1        | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 47.5%   |
| Nvidia | 18       | 45%     |
| AMD    | 3        | 7.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 10%     |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 7.5%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 5%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 5%      |
| Nvidia GF119 [GeForce GT 520]                                               | 2        | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 5%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.5%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 2.5%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 2.5%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 2.5%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 2.5%    |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 2.5%    |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 2.5%    |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.5%    |
| Nvidia G96 [GeForce 9500 GS]                                                | 1        | 2.5%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 2.5%    |
| Intel HD Graphics 610                                                       | 1        | 2.5%    |
| Intel HD Graphics 530                                                       | 1        | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 2.5%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                  | 1        | 2.5%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 2.5%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 2.5%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 2.5%    |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 18       | 47.37%  |
| 1 x Intel  | 17       | 44.74%  |
| 1 x AMD    | 3        | 7.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 80%     |
| Proprietary | 7        | 17.5%   |
| Unknown     | 1        | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 48.78%  |
| 1.01-2.0   | 11       | 26.83%  |
| 5.01-6.0   | 4        | 9.76%   |
| 0.51-1.0   | 3        | 7.32%   |
| 3.01-4.0   | 2        | 4.88%   |
| 0.01-0.5   | 1        | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 14       | 35.9%   |
| Hewlett-Packard     | 10       | 25.64%  |
| Philips             | 2        | 5.13%   |
| MSI                 | 2        | 5.13%   |
| Dell                | 2        | 5.13%   |
| S2-Tek              | 1        | 2.56%   |
| PKB                 | 1        | 2.56%   |
| Packard Bell        | 1        | 2.56%   |
| Medion              | 1        | 2.56%   |
| Lenovo              | 1        | 2.56%   |
| HPN                 | 1        | 2.56%   |
| GDH                 | 1        | 2.56%   |
| BenQ                | 1        | 2.56%   |
| AU Optronics        | 1        | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 6        | 14.63%  |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2        | 4.88%   |
| Hewlett-Packard x20LED HWP2910 1600x900 443x249mm 20.0-inch          | 2        | 4.88%   |
| Hewlett-Packard P224 HPN361E 1920x1080 527x296mm 23.8-inch           | 2        | 4.88%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM0284 1280x1024 338x270mm 17.0-inch | 1        | 2.44%   |
| Samsung Electronics SMB2240 SAM06AD 1920x1080 477x268mm 21.5-inch    | 1        | 2.44%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch | 1        | 2.44%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch     | 1        | 2.44%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 1        | 2.44%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 1        | 2.44%   |
| S2-Tek TV STK531A 1920x1080 930x530mm 42.1-inch                      | 1        | 2.44%   |
| PKB LCD Monitor VIS220WS 1680x1050                                   | 1        | 2.44%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1        | 2.44%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                    | 1        | 2.44%   |
| Packard Bell PKB VIS220WS PKB5064 1680x1050 460x290mm 21.4-inch      | 1        | 2.44%   |
| MSI MP271 MSI30A2 1920x1080 598x336mm 27.0-inch                      | 1        | 2.44%   |
| MSI MP242 MSI30A1 1920x1080 527x296mm 23.8-inch                      | 1        | 2.44%   |
| Medion MD30422PV MED86F6 1680x1050 474x296mm 22.0-inch               | 1        | 2.44%   |
| Lenovo T24v-10 LEN61BC 1920x1080 527x296mm 23.8-inch                 | 1        | 2.44%   |
| HPN LCD Monitor HP Z23n G2                                           | 1        | 2.44%   |
| Hewlett-Packard LE2001w HWP2841 1600x900 440x250mm 19.9-inch         | 1        | 2.44%   |
| Hewlett-Packard LCD Monitor 2011 1600x900                            | 1        | 2.44%   |
| Hewlett-Packard L1940T HWP2682 1280x1024 338x270mm 17.0-inch         | 1        | 2.44%   |
| Hewlett-Packard E24i G4 HPN368F 1920x1200 518x324mm 24.1-inch        | 1        | 2.44%   |
| Hewlett-Packard E241i HWP3123 1920x1200 518x324mm 24.1-inch          | 1        | 2.44%   |
| Hewlett-Packard 2011 HWP2935 1600x900 443x249mm 20.0-inch            | 1        | 2.44%   |
| Hewlett-Packard 2011 HWP2934 1600x900 443x249mm 20.0-inch            | 1        | 2.44%   |
| GDH Digital TV GDH0030 1920x540                                      | 1        | 2.44%   |
| Dell S2721HGF DEL41E8 1920x1080 600x340mm 27.2-inch                  | 1        | 2.44%   |
| Dell E193FP DEL700E 1280x1024 338x270mm 17.0-inch                    | 1        | 2.44%   |
| BenQ T201W BNQ7719 1680x1050 433x271mm 20.1-inch                     | 1        | 2.44%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch        | 1        | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 51.35%  |
| 1600x900 (HD+)     | 6        | 16.22%  |
| 1280x1024 (SXGA)   | 4        | 10.81%  |
| 1680x1050 (WSXGA+) | 3        | 8.11%   |
| 1366x768 (WXGA)    | 2        | 5.41%   |
| 3840x2160 (4K)     | 1        | 2.7%    |
| 1024x600           | 1        | 2.7%    |
| Unknown            | 1        | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 11       | 28.21%  |
| 20      | 5        | 12.82%  |
| 24      | 4        | 10.26%  |
| 21      | 3        | 7.69%   |
| 19      | 3        | 7.69%   |
| Unknown | 3        | 7.69%   |
| 27      | 2        | 5.13%   |
| 22      | 2        | 5.13%   |
| 17      | 2        | 5.13%   |
| 52      | 1        | 2.56%   |
| 42      | 1        | 2.56%   |
| 18      | 1        | 2.56%   |
| 10      | 1        | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 43.24%  |
| 401-500     | 11       | 29.73%  |
| Unknown     | 3        | 8.11%   |
| 351-400     | 2        | 5.41%   |
| 301-350     | 2        | 5.41%   |
| 201-300     | 1        | 2.7%    |
| 1001-1500   | 1        | 2.7%    |
| 901-1000    | 1        | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 26       | 68.42%  |
| 16/10   | 5        | 13.16%  |
| 5/4     | 4        | 10.53%  |
| Unknown | 3        | 7.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 17       | 43.59%  |
| 151-200        | 9        | 23.08%  |
| 141-150        | 3        | 7.69%   |
| Unknown        | 3        | 7.69%   |
| 301-350        | 2        | 5.13%   |
| 251-300        | 2        | 5.13%   |
| More than 1000 | 1        | 2.56%   |
| 41-50          | 1        | 2.56%   |
| 501-1000       | 1        | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 81.08%  |
| 101-120 | 3        | 8.11%   |
| Unknown | 3        | 8.11%   |
| 1-50    | 1        | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 86.84%  |
| 2     | 4        | 10.53%  |
| 0     | 1        | 2.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 33       | 60%     |
| Intel                 | 10       | 18.18%  |
| Ralink Technology     | 5        | 9.09%   |
| Ralink                | 3        | 5.45%   |
| Samsung Electronics   | 1        | 1.82%   |
| Qualcomm Atheros      | 1        | 1.82%   |
| IMC Networks          | 1        | 1.82%   |
| Broadcom              | 1        | 1.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 26       | 41.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6        | 9.68%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 6.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2        | 3.23%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2        | 3.23%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.61%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 1.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.61%   |
| Ralink RT5370 Wireless Adapter                                         | 1        | 1.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.61%   |
| Intel Wireless 7265                                                    | 1        | 1.61%   |
| Intel Wireless 3165                                                    | 1        | 1.61%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1        | 1.61%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.61%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.61%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1        | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 1.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 1.61%   |
| Intel 82562V-2 10/100 Network Connection                               | 1        | 1.61%   |
| IMC Networks AW-NU222 802.11bgn Wireless Module [Ralink RT2770+RT2720] | 1        | 1.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1        | 1.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 28.57%  |
| Realtek Semiconductor | 5        | 23.81%  |
| Ralink Technology     | 5        | 23.81%  |
| Ralink                | 3        | 14.29%  |
| Qualcomm Atheros      | 1        | 4.76%   |
| IMC Networks          | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                        | 4        | 19.05%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2        | 9.52%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2        | 9.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 4.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 4.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 4.76%   |
| Ralink RT5370 Wireless Adapter                                         | 1        | 4.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1        | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 4.76%   |
| Intel Wireless 7265                                                    | 1        | 4.76%   |
| Intel Wireless 3165                                                    | 1        | 4.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 4.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1        | 4.76%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 4.76%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 4.76%   |
| IMC Networks AW-NU222 802.11bgn Wireless Module [Ralink RT2770+RT2720] | 1        | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 33       | 82.5%   |
| Intel                 | 5        | 12.5%   |
| Samsung Electronics   | 1        | 2.5%    |
| Broadcom              | 1        | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 26       | 63.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6        | 14.63%  |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 2.44%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 2.44%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 2.44%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 2.44%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1        | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 2.44%   |
| Intel 82562V-2 10/100 Network Connection                               | 1        | 2.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1        | 2.44%   |

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
| Ethernet | 29       | 70.73%  |
| WiFi     | 12       | 29.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 63.16%  |
| 2     | 14       | 36.84%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 54.55%  |
| Cambridge Silicon Radio | 3        | 27.27%  |
| Ralink                  | 1        | 9.09%   |
| IMC Networks            | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX201 Bluetooth                               | 3        | 27.27%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 27.27%  |
| Intel Bluetooth wireless interface                  | 2        | 18.18%  |
| Ralink RT3290 Bluetooth                             | 1        | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 9.09%   |
| IMC Networks Bluetooth Radio                        | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 34       | 56.67%  |
| Nvidia                  | 17       | 28.33%  |
| AMD                     | 7        | 11.67%  |
| Xiamen VBeT Electronics | 1        | 1.67%   |
| Lenovo                  | 1        | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6        | 9.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5        | 7.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4        | 6.35%   |
| Nvidia High Definition Audio Controller                                           | 3        | 4.76%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 4.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 4.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 4.76%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 3.17%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 3.17%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 3.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 3.17%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 3.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 3.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 3.17%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 3.17%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 3.17%   |
| Xiamen VBeT Electronics VT X208                                                   | 1        | 1.59%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 1.59%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 1.59%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 1.59%   |
| Lenovo ThinkVision T24v Wide Monitor for USB-Audio                                | 1        | 1.59%   |
| Intel USB PnP Sound Device                                                        | 1        | 1.59%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1        | 1.59%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 1.59%   |
| Intel Alder Lake-S HD Audio Controller                                            | 1        | 1.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 1.59%   |
| AMD Family 17h/19h HD Audio Controller                                            | 1        | 1.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 1.59%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 1.59%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 1.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 5        | 17.24%  |
| Unknown             | 4        | 13.79%  |
| Samsung Electronics | 4        | 13.79%  |
| Micron Technology   | 3        | 10.34%  |
| TwinMOS             | 2        | 6.9%    |
| Team                | 2        | 6.9%    |
| Unknown (ABCD)      | 1        | 3.45%   |
| Transcend           | 1        | 3.45%   |
| PNY                 | 1        | 3.45%   |
| Patriot             | 1        | 3.45%   |
| Melco               | 1        | 3.45%   |
| GOODRAM             | 1        | 3.45%   |
| Elpida              | 1        | 3.45%   |
| Crucial             | 1        | 3.45%   |
| 0BBA00000000        | 1        | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 3.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 3.45%   |
| Unknown RAM Module 4GB DIMM DDR3                               | 1        | 3.45%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                         | 1        | 3.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 3.45%   |
| TwinMOS RAM 9DSDBNZB-5AMP 4GB DIMM DDR3 1333MT/s               | 1        | 3.45%   |
| TwinMOS RAM 9D7TBNZB-TATP 4096MB DIMM DDR3 1066MT/s            | 1        | 3.45%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s              | 1        | 3.45%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s            | 1        | 3.45%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s            | 1        | 3.45%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1        | 3.45%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s          | 1        | 3.45%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s           | 1        | 3.45%   |
| SK hynix RAM HMA82GU7CJR8N-VK 16GB DIMM DDR4 2667MT/s          | 1        | 3.45%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s           | 1        | 3.45%   |
| Samsung RAM Module 4096MB DIMM DDR3 1333MT/s                   | 1        | 3.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1        | 3.45%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s            | 1        | 3.45%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 3.45%   |
| PNY RAM 8GBF1X08LIII43-12-K 8GB DIMM DDR4 2667MT/s             | 1        | 3.45%   |
| Patriot RAM 3000 C15 Series 8GB DIMM DDR4 3000MT/s             | 1        | 3.45%   |
| Micron RAM ITC 4096MB DIMM DDR3 1648MT/s                       | 1        | 3.45%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s            | 1        | 3.45%   |
| Micron RAM 4ATF1G64HZ-3G2B2 8GB SODIMM DDR4 3200MT/s           | 1        | 3.45%   |
| Melco RAM Module 2GB DIMM DDR2 667MT/s                         | 1        | 3.45%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s             | 1        | 3.45%   |
| Elpida RAM HMT451S6AFR8C-H9 4GB DIMM DDR3                      | 1        | 3.45%   |
| Crucial RAM BL16G32C16U4B.16FE 16384MB DIMM DDR4 3200MT/s      | 1        | 3.45%   |
| 0BBA00000000 RAM KBN1333D3N9/4G 4096MB DIMM DDR3 1066MT/s      | 1        | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 10       | 43.48%  |
| DDR3    | 8        | 34.78%  |
| SDRAM   | 2        | 8.7%    |
| LPDDR4  | 1        | 4.35%   |
| DDR2    | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 90.91%  |
| SODIMM | 2        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 8        | 34.78%  |
| 8192  | 5        | 21.74%  |
| 16384 | 4        | 17.39%  |
| 2048  | 4        | 17.39%  |
| 32768 | 1        | 4.35%   |
| 1024  | 1        | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 4        | 16%     |
| 1333    | 4        | 16%     |
| 3200    | 3        | 12%     |
| 1600    | 3        | 12%     |
| 2400    | 2        | 8%      |
| 1066    | 2        | 8%      |
| 667     | 2        | 8%      |
| 49926   | 1        | 4%      |
| 3800    | 1        | 4%      |
| 3000    | 1        | 4%      |
| 1648    | 1        | 4%      |
| Unknown | 1        | 4%      |

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
| Syntek     | 1        | 33.33%  |
| Cubeternet | 1        | 33.33%  |
| A4Tech     | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Syntek Integrated RGB Camera | 1        | 33.33%  |
| Cubeternet WebCam            | 1        | 33.33%  |
| A4Tech USB Live camera       | 1        | 33.33%  |

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
| 0     | 35       | 85.37%  |
| 1     | 5        | 12.2%   |
| 2     | 1        | 2.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 2        | 33.33%  |
| Graphics card | 2        | 33.33%  |
| Net/ethernet  | 1        | 16.67%  |
| Bluetooth     | 1        | 16.67%  |

