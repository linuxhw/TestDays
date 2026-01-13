Oracle Linux - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Oracle Linux.

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

Total: 49

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| HP         | 158B                        | [12ee930c05](https://linux-hardware.org/?probe=12ee930c05) | Dec 08, 2025 |
| HP         | 158B                        | [b410504428](https://linux-hardware.org/?probe=b410504428) | Dec 02, 2025 |
| Acer       | FIH57                       | [e28af6bf25](https://linux-hardware.org/?probe=e28af6bf25) | Jul 26, 2025 |
| Huanan     | X99 F8D V2.1                | [d8d0977a39](https://linux-hardware.org/?probe=d8d0977a39) | Jun 05, 2025 |
| ASUSTek    | P8Z77-V LX                  | [0a78f8643e](https://linux-hardware.org/?probe=0a78f8643e) | Mar 25, 2025 |
| ASUSTek    | P8Z77-V LX                  | [ea6ae957b4](https://linux-hardware.org/?probe=ea6ae957b4) | Mar 14, 2025 |
| MSI        | MS-B9071                    | [64eee3f80e](https://linux-hardware.org/?probe=64eee3f80e) | Mar 07, 2025 |
| ASRock     | Z68 Extreme3 Gen3           | [deb0c2ec87](https://linux-hardware.org/?probe=deb0c2ec87) | Feb 24, 2025 |
| ASUSTek    | PRIME Z490-A                | [c7a92e755d](https://linux-hardware.org/?probe=c7a92e755d) | Dec 23, 2024 |
| ASUSTek    | PRIME Z490-A                | [7d25b9b02f](https://linux-hardware.org/?probe=7d25b9b02f) | Dec 23, 2024 |
| Gigabyte   | B450 AORUS ELITE            | [51f6c29054](https://linux-hardware.org/?probe=51f6c29054) | Dec 22, 2024 |
| Dell       | 0Y7WYT A00                  | [26470bb6ae](https://linux-hardware.org/?probe=26470bb6ae) | Sep 07, 2024 |
| Dell       | 0Y7WYT A00                  | [3fcfac6482](https://linux-hardware.org/?probe=3fcfac6482) | Sep 07, 2024 |
| Supermicro | X9SCL-II/X9SCM-II           | [a0c9c93180](https://linux-hardware.org/?probe=a0c9c93180) | May 20, 2024 |
| Supermicro | X9SCL-II/X9SCM-II           | [8373a09f6d](https://linux-hardware.org/?probe=8373a09f6d) | May 20, 2024 |
| Gigabyte   | X470 AORUS ULTRA GAMING-... | [af34317225](https://linux-hardware.org/?probe=af34317225) | May 14, 2024 |
| Unknown    | Unknown                     | [806e7d1dfa](https://linux-hardware.org/?probe=806e7d1dfa) | Apr 28, 2024 |
| Gigabyte   | B450M DS3H-CF               | [cf6c011819](https://linux-hardware.org/?probe=cf6c011819) | Apr 13, 2024 |
| Dell       | 0D28YY A03                  | [894b628494](https://linux-hardware.org/?probe=894b628494) | Apr 12, 2024 |
| ASUSTek    | PRIME B250M-A               | [5d12c5c26e](https://linux-hardware.org/?probe=5d12c5c26e) | Mar 31, 2024 |
| ASUSTek    | PRIME B250M-A               | [142a42435b](https://linux-hardware.org/?probe=142a42435b) | Mar 30, 2024 |
| HP         | ProLiant ML110 Gen9         | [c2f9d107ed](https://linux-hardware.org/?probe=c2f9d107ed) | Mar 02, 2024 |
| HP         | ProLiant ML310e Gen8 v2     | [1b3629654d](https://linux-hardware.org/?probe=1b3629654d) | Mar 02, 2024 |
| ASRock     | B760M-STX                   | [1648b583d6](https://linux-hardware.org/?probe=1648b583d6) | Jan 10, 2024 |
| ASUSTek    | G15CF                       | [c2b88beb62](https://linux-hardware.org/?probe=c2b88beb62) | Dec 02, 2023 |
| ASRock     | B550M Steel Legend          | [9cb8304240](https://linux-hardware.org/?probe=9cb8304240) | Nov 24, 2023 |
| ASRock     | B550M Steel Legend          | [8cfb18380e](https://linux-hardware.org/?probe=8cfb18380e) | Nov 24, 2023 |
| ASUSTek    | SABERTOOTH 990FX R3.0       | [b63af8760f](https://linux-hardware.org/?probe=b63af8760f) | Oct 03, 2023 |
| ASUSTek    | SABERTOOTH 990FX R3.0       | [5ac9728fe0](https://linux-hardware.org/?probe=5ac9728fe0) | Oct 01, 2023 |
| Cisco      | WAVE-694-K9 A0              | [26b9c3adb7](https://linux-hardware.org/?probe=26b9c3adb7) | Jun 27, 2023 |
| ASRock     | Z68 Extreme3 Gen3           | [7849965aa1](https://linux-hardware.org/?probe=7849965aa1) | Jun 11, 2023 |
| HP         | 1589                        | [c905464231](https://linux-hardware.org/?probe=c905464231) | May 11, 2023 |
| Gigabyte   | H81M-S2PV                   | [ac856abadc](https://linux-hardware.org/?probe=ac856abadc) | Mar 21, 2023 |
| ASUSTek    | PRIME B560M-A AC            | [d4cc718e46](https://linux-hardware.org/?probe=d4cc718e46) | Nov 29, 2022 |
| Dell       | 0DC48C A02                  | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| ASUSTek    | H81M-A                      | [a37e952875](https://linux-hardware.org/?probe=a37e952875) | Sep 04, 2022 |
| Dell       | 073Y7Y A00                  | [3bed97b23e](https://linux-hardware.org/?probe=3bed97b23e) | Jul 21, 2022 |
| MSI        | Z77A-G43                    | [909e3e3c2e](https://linux-hardware.org/?probe=909e3e3c2e) | Jun 29, 2022 |
| ASUSTek    | P8H67                       | [b194dad4cf](https://linux-hardware.org/?probe=b194dad4cf) | Jun 25, 2022 |
| Dell       | 0C522T A03                  | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Gigabyte   | Z490 AORUS ELITE AC         | [978ae6f2cb](https://linux-hardware.org/?probe=978ae6f2cb) | May 02, 2021 |
| Gigabyte   | X99-Designare EX-CF         | [5195396549](https://linux-hardware.org/?probe=5195396549) | Mar 06, 2021 |
| ASUSTek    | G11CD                       | [13961e12a8](https://linux-hardware.org/?probe=13961e12a8) | Feb 01, 2021 |
| HP         | 158B                        | [5e6b9531d7](https://linux-hardware.org/?probe=5e6b9531d7) | Feb 01, 2021 |
| Dell       | PowerEdge FC630             | [bcd33a41f0](https://linux-hardware.org/?probe=bcd33a41f0) | Jan 25, 2021 |
| Gigabyte   | X470 AORUS ULTRA GAMING-... | [71628a95b6](https://linux-hardware.org/?probe=71628a95b6) | Jan 13, 2021 |
| Foxconn    | 2ADA                        | [809e03aea5](https://linux-hardware.org/?probe=809e03aea5) | Dec 24, 2020 |
| ASUSTek    | G11CD                       | [d9d0f8fdf2](https://linux-hardware.org/?probe=d9d0f8fdf2) | Dec 20, 2020 |
| Dell       | 0C96W1 A01                  | [b5c14107bb](https://linux-hardware.org/?probe=b5c14107bb) | Feb 12, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Oracle Linux 8.3  | 6        | 14.63%  |
| Oracle Linux 9.5  | 5        | 12.2%   |
| Oracle Linux 9.3  | 5        | 12.2%   |
| Oracle Linux 8.9  | 5        | 12.2%   |
| Oracle Linux 8.6  | 4        | 9.76%   |
| Oracle Linux 9.2  | 3        | 7.32%   |
| Oracle Linux 9.6  | 2        | 4.88%   |
| Oracle Linux 9.4  | 2        | 4.88%   |
| Oracle Linux 8.7  | 2        | 4.88%   |
| Oracle Linux 9.7  | 1        | 2.44%   |
| Oracle Linux 9.0  | 1        | 2.44%   |
| Oracle Linux 8.5  | 1        | 2.44%   |
| Oracle Linux 8.4  | 1        | 2.44%   |
| Oracle Linux 7.7  | 1        | 2.44%   |
| Oracle Linux 7.4  | 1        | 2.44%   |
| Oracle Linux 6.10 | 1        | 2.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Oracle Linux | 39       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.4.17-2036.102.0.2.el8uek.x86_64  | 2        | 4.76%   |
| 5.4.17-2036.101.2.el8uek.x86_64    | 2        | 4.76%   |
| 5.15.0-305.176.4.el9uek.x86_64     | 2        | 4.76%   |
| 5.15.0-205.149.5.1.el9uek.x86_64   | 2        | 4.76%   |
| 6.12.0-100.28.2.2.el9uek.x86_64    | 1        | 2.38%   |
| 5.4.17-2136.330.7.1.el8uek.x86_64  | 1        | 2.38%   |
| 5.4.17-2136.313.6.el8uek.x86_64    | 1        | 2.38%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64  | 1        | 2.38%   |
| 5.4.17-2136.308.9.el8uek.x86_64    | 1        | 2.38%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64  | 1        | 2.38%   |
| 5.4.17-2136.300.7.el8uek.x86_64    | 1        | 2.38%   |
| 5.4.17-2102.202.5.el8uek.x86_64    | 1        | 2.38%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 1        | 2.38%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64  | 1        | 2.38%   |
| 5.4.11-1.el7.elrepo.x86_64         | 1        | 2.38%   |
| 5.15.0-308.179.6.3.el9uek.x86_64   | 1        | 2.38%   |
| 5.15.0-306.177.4.el9uek.x86_64     | 1        | 2.38%   |
| 5.15.0-303.171.5.2.el9uek.x86_64   | 1        | 2.38%   |
| 5.15.0-209.161.7.2.el9uek.x86_64   | 1        | 2.38%   |
| 5.15.0-205.149.5.4.el9uek.x86_64   | 1        | 2.38%   |
| 5.15.0-204.147.6.2.el8uek.x86_64   | 1        | 2.38%   |
| 5.15.0-201.135.6.el9uek.x86_64     | 1        | 2.38%   |
| 5.15.0-200.131.27.el9uek.x86_64    | 1        | 2.38%   |
| 5.15.0-200.131.27.1.el9uek.x86_64  | 1        | 2.38%   |
| 5.15.0-2.52.3.el9uek.x86_64        | 1        | 2.38%   |
| 5.15.0-105.125.6.2.2.el9uek.x86_64 | 1        | 2.38%   |
| 5.15.0-102.110.5.1.el9uek.x86_64   | 1        | 2.38%   |
| 5.15.0-101.103.2.1.el9uek.x86_64   | 1        | 2.38%   |
| 5.15.0-100.96.32.el8uek.x86_64     | 1        | 2.38%   |
| 5.14.0-611.9.1.el9_7.x86_64        | 1        | 2.38%   |
| 5.14.0-503.16.1.el9_5.x86_64       | 1        | 2.38%   |
| 4.18.0-513.9.1.el8_9.x86_64        | 1        | 2.38%   |
| 4.18.0-513.24.1.el8_9.x86_64       | 1        | 2.38%   |
| 4.18.0-513.18.0.1.el8_9.x86_64     | 1        | 2.38%   |
| 4.18.0-372.16.1.0.2.el8_6.x86_64   | 1        | 2.38%   |
| 4.18.0-240.15.1.el8_3.x86_64       | 1        | 2.38%   |
| 3.8.13-118.24.3.el6uek.x86_64      | 1        | 2.38%   |
| 3.10.0-693.11.6.el7.x86_64         | 1        | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 17       | 42.5%   |
| 5.4.17  | 12       | 30%     |
| 4.18.0  | 5        | 12.5%   |
| 5.14.0  | 2        | 5%      |
| 6.12.0  | 1        | 2.5%    |
| 5.4.11  | 1        | 2.5%    |
| 3.8.13  | 1        | 2.5%    |
| 3.10.0  | 1        | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 17       | 42.5%   |
| 5.4     | 13       | 32.5%   |
| 4.18    | 5        | 12.5%   |
| 5.14    | 2        | 5%      |
| 6.12    | 1        | 2.5%    |
| 3.8     | 1        | 2.5%    |
| 3.10    | 1        | 2.5%    |

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


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 25       | 64.1%   |
| Unknown       | 10       | 25.64%  |
| KDE5          | 2        | 5.13%   |
| GNOME Classic | 2        | 5.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 17       | 43.59%  |
| X11     | 13       | 33.33%  |
| Unknown | 7        | 17.95%  |
| Tty     | 2        | 5.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 26       | 66.67%  |
| GDM     | 10       | 25.64%  |
| SDDM    | 2        | 5.13%   |
| TDM     | 1        | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 16       | 41.03%  |
| ru_RU      | 5        | 12.82%  |
| en_GB      | 4        | 10.26%  |
| it_IT      | 3        | 7.69%   |
| pt_BR      | 2        | 5.13%   |
| de_DE      | 2        | 5.13%   |
| Unknown    | 2        | 5.13%   |
| zh_CN      | 1        | 2.56%   |
| pl_PL      | 1        | 2.56%   |
| es_MX      | 1        | 2.56%   |
| en_US.UTF8 | 1        | 2.56%   |
| en_IN      | 1        | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 21       | 52.5%   |
| BIOS | 19       | 47.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Xfs   | 30       | 76.92%  |
| Ext4  | 7        | 17.95%  |
| Zfs   | 1        | 2.56%   |
| Btrfs | 1        | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 46.15%  |
| GPT     | 16       | 41.03%  |
| MBR     | 5        | 12.82%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 87.18%  |
| Yes       | 5        | 12.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 92.31%  |
| Yes       | 3        | 7.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 23.08%  |
| Dell                | 7        | 17.95%  |
| Gigabyte Technology | 6        | 15.38%  |
| Hewlett-Packard     | 5        | 12.82%  |
| ASRock              | 3        | 7.69%   |
| Supermicro          | 2        | 5.13%   |
| MSI                 | 2        | 5.13%   |
| Huanan              | 1        | 2.56%   |
| Foxconn             | 1        | 2.56%   |
| Cisco               | 1        | 2.56%   |
| Acer                | 1        | 2.56%   |
| Unknown             | 1        | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Supermicro X9SCL-II/X9SCM-II             | 2        | 5.13%   |
| HP Z820 Workstation                      | 2        | 5.13%   |
| MSI MS-7758                              | 1        | 2.56%   |
| MSI B250 Gaming Nightblade MI3 (MS-B908) | 1        | 2.56%   |
| Huanan X99 F8D V2.1                      | 1        | 2.56%   |
| HP Z420 Workstation                      | 1        | 2.56%   |
| HP ProLiant ML310e Gen8 v2               | 1        | 2.56%   |
| HP ProLiant ML110 Gen9                   | 1        | 2.56%   |
| Gigabyte Z490 AORUS ELITE AC             | 1        | 2.56%   |
| Gigabyte X99-Designare EX-CF             | 1        | 2.56%   |
| Gigabyte X470 AORUS ULTRA GAMING         | 1        | 2.56%   |
| Gigabyte H81M-S2PV                       | 1        | 2.56%   |
| Gigabyte B450M DS3H                      | 1        | 2.56%   |
| Gigabyte B450 AORUS ELITE                | 1        | 2.56%   |
| Foxconn p6-2400el                        | 1        | 2.56%   |
| Dell PowerEdge FC630                     | 1        | 2.56%   |
| Dell OptiPlex 980                        | 1        | 2.56%   |
| Dell OptiPlex 790                        | 1        | 2.56%   |
| Dell OptiPlex 7090                       | 1        | 2.56%   |
| Dell OptiPlex 7060                       | 1        | 2.56%   |
| Dell OptiPlex 7040                       | 1        | 2.56%   |
| Dell OptiPlex 5000                       | 1        | 2.56%   |
| Cisco WAVE-694-K9                        | 1        | 2.56%   |
| ASUS SABERTOOTH 990FX R3.0               | 1        | 2.56%   |
| ASUS ROG STRIX G15CF_G15CF               | 1        | 2.56%   |
| ASUS PRIME Z490-A                        | 1        | 2.56%   |
| ASUS PRIME B560M-A AC                    | 1        | 2.56%   |
| ASUS PRIME B250M-A                       | 1        | 2.56%   |
| ASUS P8Z77-V LX                          | 1        | 2.56%   |
| ASUS P8H67                               | 1        | 2.56%   |
| ASUS G11CD                               | 1        | 2.56%   |
| ASUS All Series                          | 1        | 2.56%   |
| ASRock Z68 Extreme3 Gen3                 | 1        | 2.56%   |
| ASRock B760M-STX                         | 1        | 2.56%   |
| ASRock B550M Steel Legend                | 1        | 2.56%   |
| Acer Aspire X5950                        | 1        | 2.56%   |
| Unknown                                  | 1        | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 6        | 15.38%  |
| ASUS PRIME             | 3        | 7.69%   |
| Supermicro X9SCL-II    | 2        | 5.13%   |
| HP Z820                | 2        | 5.13%   |
| HP ProLiant            | 2        | 5.13%   |
| MSI MS-7758            | 1        | 2.56%   |
| MSI B250               | 1        | 2.56%   |
| Huanan X99             | 1        | 2.56%   |
| HP Z420                | 1        | 2.56%   |
| Gigabyte Z490          | 1        | 2.56%   |
| Gigabyte X99-Designare | 1        | 2.56%   |
| Gigabyte X470          | 1        | 2.56%   |
| Gigabyte H81M-S2PV     | 1        | 2.56%   |
| Gigabyte B450M         | 1        | 2.56%   |
| Gigabyte B450          | 1        | 2.56%   |
| Foxconn p6-2400el      | 1        | 2.56%   |
| Dell PowerEdge         | 1        | 2.56%   |
| Cisco WAVE-694-K9      | 1        | 2.56%   |
| ASUS SABERTOOTH        | 1        | 2.56%   |
| ASUS ROG               | 1        | 2.56%   |
| ASUS P8Z77-V           | 1        | 2.56%   |
| ASUS P8H67             | 1        | 2.56%   |
| ASUS G11CD             | 1        | 2.56%   |
| ASUS All               | 1        | 2.56%   |
| ASRock Z68             | 1        | 2.56%   |
| ASRock B760M-STX       | 1        | 2.56%   |
| ASRock B550M           | 1        | 2.56%   |
| Acer Aspire            | 1        | 2.56%   |
| Unknown                | 1        | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 8        | 20.51%  |
| 2020 | 4        | 10.26%  |
| 2018 | 4        | 10.26%  |
| 2016 | 4        | 10.26%  |
| 2013 | 4        | 10.26%  |
| 2010 | 3        | 7.69%   |
| 2022 | 2        | 5.13%   |
| 2021 | 2        | 5.13%   |
| 2015 | 2        | 5.13%   |
| 2011 | 2        | 5.13%   |
| 2024 | 1        | 2.56%   |
| 2023 | 1        | 2.56%   |
| 2017 | 1        | 2.56%   |
| 2014 | 1        | 2.56%   |

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
| Disabled | 38       | 97.44%  |
| Enabled  | 1        | 2.56%   |

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
| 8.01-16.0       | 11       | 28.21%  |
| 64.01-256.0     | 8        | 20.51%  |
| 32.01-64.0      | 6        | 15.38%  |
| 4.01-8.0        | 5        | 12.82%  |
| 24.01-32.0      | 3        | 7.69%   |
| 3.01-4.0        | 2        | 5.13%   |
| 16.01-24.0      | 2        | 5.13%   |
| More than 256.0 | 1        | 2.56%   |
| 1.01-2.0        | 1        | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 11       | 26.19%  |
| 3.01-4.0   | 8        | 19.05%  |
| 2.01-3.0   | 8        | 19.05%  |
| 1.01-2.0   | 6        | 14.29%  |
| 0.51-1.0   | 3        | 7.14%   |
| 8.01-16.0  | 2        | 4.76%   |
| 24.01-32.0 | 1        | 2.38%   |
| 16.01-24.0 | 1        | 2.38%   |
| 0.01-0.5   | 1        | 2.38%   |
| Unknown    | 1        | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 32.5%   |
| 2      | 10       | 25%     |
| 4      | 7        | 17.5%   |
| 3      | 5        | 12.5%   |
| 5      | 3        | 7.5%    |
| 25     | 1        | 2.5%    |
| 6      | 1        | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 71.79%  |
| Yes       | 11       | 28.21%  |

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
| No        | 23       | 58.97%  |
| Yes       | 16       | 41.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 64.1%   |
| Yes       | 14       | 35.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 6        | 15.38%  |
| Germany   | 6        | 15.38%  |
| Russia    | 4        | 10.26%  |
| Italy     | 4        | 10.26%  |
| Brazil    | 3        | 7.69%   |
| Vietnam   | 2        | 5.13%   |
| Moldova   | 2        | 5.13%   |
| India     | 2        | 5.13%   |
| UK        | 1        | 2.56%   |
| Slovakia  | 1        | 2.56%   |
| Romania   | 1        | 2.56%   |
| Poland    | 1        | 2.56%   |
| Mexico    | 1        | 2.56%   |
| Ireland   | 1        | 2.56%   |
| Finland   | 1        | 2.56%   |
| China     | 1        | 2.56%   |
| Bolivia   | 1        | 2.56%   |
| Australia | 1        | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Tiraspol        | 2        | 5%      |
| Sao Paulo       | 2        | 5%      |
| Moscow          | 2        | 5%      |
| Milan           | 2        | 5%      |
| Hanoi           | 2        | 5%      |
| Bengaluru       | 2        | 5%      |
| Zavar           | 1        | 2.5%    |
| Wexford         | 1        | 2.5%    |
| Weaverville     | 1        | 2.5%    |
| Warsaw          | 1        | 2.5%    |
| Veliky Novgorod | 1        | 2.5%    |
| Stuttgart       | 1        | 2.5%    |
| Santa Cruz      | 1        | 2.5%    |
| Riverside       | 1        | 2.5%    |
| Reading         | 1        | 2.5%    |
| Rahden          | 1        | 2.5%    |
| Porto Alegre    | 1        | 2.5%    |
| Pingdingshan    | 1        | 2.5%    |
| Petersberg      | 1        | 2.5%    |
| Perugia         | 1        | 2.5%    |
| Parker          | 1        | 2.5%    |
| Neunkirchen     | 1        | 2.5%    |
| Magdeburg       | 1        | 2.5%    |
| Kansas City     | 1        | 2.5%    |
| Ivanteyevka     | 1        | 2.5%    |
| Helsinki        | 1        | 2.5%    |
| Glenview        | 1        | 2.5%    |
| Glendale        | 1        | 2.5%    |
| Bucharest       | 1        | 2.5%    |
| Berlin          | 1        | 2.5%    |
| Asheville       | 1        | 2.5%    |
| Apodaca         | 1        | 2.5%    |
| Albairate       | 1        | 2.5%    |
| Adelaide        | 1        | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 16       | 82     | 21.92%  |
| WDC                         | 11       | 16     | 15.07%  |
| Samsung Electronics         | 8        | 13     | 10.96%  |
| Kingston                    | 7        | 8      | 9.59%   |
| Toshiba                     | 6        | 7      | 8.22%   |
| Sandisk                     | 5        | 7      | 6.85%   |
| Kingston Technology Company | 2        | 2      | 2.74%   |
| Hewlett-Packard             | 2        | 2      | 2.74%   |
| Crucial                     | 2        | 2      | 2.74%   |
| SK hynix                    | 1        | 1      | 1.37%   |
| Silicon Motion              | 1        | 1      | 1.37%   |
| Realtek Semiconductor       | 1        | 1      | 1.37%   |
| Plextor                     | 1        | 1      | 1.37%   |
| Phison Electronics          | 1        | 1      | 1.37%   |
| Phison                      | 1        | 1      | 1.37%   |
| Micron/Crucial Technology   | 1        | 1      | 1.37%   |
| Lexar                       | 1        | 1      | 1.37%   |
| KingSpec                    | 1        | 1      | 1.37%   |
| KingFast                    | 1        | 1      | 1.37%   |
| Intenso                     | 1        | 1      | 1.37%   |
| Intel                       | 1        | 1      | 1.37%   |
| Hitachi                     | 1        | 1      | 1.37%   |
| Apacer                      | 1        | 1      | 1.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 5        | 5.68%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3        | 3.41%   |
| Seagate ST2000DM001-1ER164 2TB                        | 2        | 2.27%   |
| Samsung SSD 860 EVO 250GB                             | 2        | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 2        | 2.27%   |
| Kingston Company SNV2S2000G 2TB                       | 2        | 2.27%   |
| WDC WDS500G2B0A-00SM50 500GB                          | 1        | 1.14%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                      | 1        | 1.14%   |
| WDC WD40PURX-64GVNY0 4TB                              | 1        | 1.14%   |
| WDC WD40PURX-64GVNY0 1 4TB                            | 1        | 1.14%   |
| WDC WD40EFRX-68N32N0 4TB                              | 1        | 1.14%   |
| WDC WD3200BEKT-08PVMT1 320GB                          | 1        | 1.14%   |
| WDC WD30EFRX-68AX9N0 3TB                              | 1        | 1.14%   |
| WDC WD2500AAKX-08U6AA0 250GB                          | 1        | 1.14%   |
| WDC WD20PURX-64P6ZY0 2TB                              | 1        | 1.14%   |
| WDC WD1600YS-23SHB0 160GB                             | 1        | 1.14%   |
| WDC WD10EZEX-60M2NA0 1TB                              | 1        | 1.14%   |
| WDC WD10EZEX-22MFCA0 1TB                              | 1        | 1.14%   |
| WDC WD10EARS-00Y5B1 1TB                               | 1        | 1.14%   |
| Toshiba NVMe SSD Drive 512GB                          | 1        | 1.14%   |
| Toshiba MG08ACA16TE 16TB                              | 1        | 1.14%   |
| Toshiba MG04ACA200E 2TB                               | 1        | 1.14%   |
| Toshiba HDWD110 1TB                                   | 1        | 1.14%   |
| Toshiba DT01ACA300 3TB                                | 1        | 1.14%   |
| Toshiba DT01ACA050 500GB                              | 1        | 1.14%   |
| SK hynix PC801 NVMe 512GB                             | 1        | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 1        | 1.14%   |
| Seagate ST91000640NS 1TB                              | 1        | 1.14%   |
| Seagate ST8000VN004-2M2101 8TB                        | 1        | 1.14%   |
| Seagate ST8000AS0002-1NA17Z 8TB                       | 1        | 1.14%   |
| Seagate ST500LX025-1U717D 500GB                       | 1        | 1.14%   |
| Seagate ST5000AS0011-1L5178 5TB                       | 1        | 1.14%   |
| Seagate ST3750528AS 752GB                             | 1        | 1.14%   |
| Seagate ST3500414CS 500GB                             | 1        | 1.14%   |
| Seagate ST3000DM001-1CH166 3TB                        | 1        | 1.14%   |
| Seagate ST2000NX0253 2TB                              | 1        | 1.14%   |
| Seagate ST2000NM0033-9ZM175 2TB                       | 1        | 1.14%   |
| Seagate ST1000VX000-1ES162 1TB                        | 1        | 1.14%   |
| Seagate ST1000NX0423 1TB                              | 1        | 1.14%   |
| Seagate ST1000LX015-1U7172 1TB                        | 1        | 1.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 82     | 45.71%  |
| WDC                 | 10       | 13     | 28.57%  |
| Toshiba             | 5        | 6      | 14.29%  |
| Samsung Electronics | 2        | 2      | 5.71%   |
| Hitachi             | 1        | 1      | 2.86%   |
| Hewlett-Packard     | 1        | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 7        | 8      | 28%     |
| Samsung Electronics | 6        | 8      | 24%     |
| WDC                 | 2        | 3      | 8%      |
| Crucial             | 2        | 2      | 8%      |
| SanDisk             | 1        | 3      | 4%      |
| Plextor             | 1        | 1      | 4%      |
| Lexar               | 1        | 1      | 4%      |
| KingSpec            | 1        | 1      | 4%      |
| Intenso             | 1        | 1      | 4%      |
| Intel               | 1        | 1      | 4%      |
| Hewlett-Packard     | 1        | 1      | 4%      |
| Apacer              | 1        | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 27       | 105    | 42.86%  |
| SSD     | 21       | 31     | 33.33%  |
| NVMe    | 14       | 16     | 22.22%  |
| Unknown | 1        | 1      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 35       | 137    | 71.43%  |
| NVMe | 14       | 16     | 28.57%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 22       | 34     | 41.51%  |
| 0.51-1.0   | 13       | 42     | 24.53%  |
| 1.01-2.0   | 9        | 49     | 16.98%  |
| 2.01-3.0   | 3        | 3      | 5.66%   |
| 4.01-10.0  | 3        | 4      | 5.66%   |
| 3.01-4.0   | 2        | 3      | 3.77%   |
| 10.01-20.0 | 1        | 1      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 9        | 23.08%  |
| 101-250        | 7        | 17.95%  |
| More than 3000 | 6        | 15.38%  |
| 501-1000       | 6        | 15.38%  |
| 1001-2000      | 5        | 12.82%  |
| 2001-3000      | 2        | 5.13%   |
| Unknown        | 2        | 5.13%   |
| 21-50          | 1        | 2.56%   |
| 51-100         | 1        | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 11       | 27.5%   |
| 1-20           | 9        | 22.5%   |
| 101-250        | 7        | 17.5%   |
| More than 3000 | 5        | 12.5%   |
| 1001-2000      | 2        | 5%      |
| 51-100         | 2        | 5%      |
| Unknown        | 2        | 5%      |
| 251-500        | 1        | 2.5%    |
| 501-1000       | 1        | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD40PURX-64GVNY0 4TB       | 1        | 1      | 25%     |
| WDC WD40PURX-64GVNY0 1 4TB     | 1        | 1      | 25%     |
| Seagate ST3000DM001-1CH166 3TB | 1        | 1      | 25%     |
| Hewlett-Packard SSD S700 120GB | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 1        | 2      | 33.33%  |
| Seagate         | 1        | 1      | 33.33%  |
| Hewlett-Packard | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 3      | 66.67%  |
| SSD  | 1        | 1      | 33.33%  |

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
| Works    | 20       | 102    | 50%     |
| Detected | 17       | 47     | 42.5%   |
| Malfunc  | 3        | 4      | 7.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 34       | 54.84%  |
| Broadcom / LSI               | 5        | 8.06%   |
| AMD                          | 5        | 8.06%   |
| Sandisk                      | 4        | 6.45%   |
| Samsung Electronics          | 3        | 4.84%   |
| Phison Electronics           | 2        | 3.23%   |
| Kingston Technology Company  | 2        | 3.23%   |
| VIA Technologies             | 1        | 1.61%   |
| Toshiba America Info Systems | 1        | 1.61%   |
| SK hynix                     | 1        | 1.61%   |
| Silicon Motion               | 1        | 1.61%   |
| Realtek Semiconductor        | 1        | 1.61%   |
| Micron/Crucial Technology    | 1        | 1.61%   |
| Adaptec                      | 1        | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel SATA Controller [RAID mode]                                                       | 5        | 6.41%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 5.13%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 3.85%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 3.85%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3        | 3.85%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 3.85%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 2.56%   |
| Phison E12 NVMe Controller                                                              | 2        | 2.56%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 2        | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.56%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 2.56%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.56%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 2.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 2.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.56%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 2.56%   |
| Broadcom / LSI MegaRAID SAS 2108 [Liberator]                                            | 2        | 2.56%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 1.28%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 1.28%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1        | 1.28%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 1.28%   |
| Sandisk WD Blue SN580 NVMe SSD (DRAM-less)                                              | 1        | 1.28%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 1        | 1.28%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1        | 1.28%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 1        | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.28%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1        | 1.28%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 1.28%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 1        | 1.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.28%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 1.28%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.28%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 1        | 1.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 31       | 47.69%  |
| NVMe | 14       | 21.54%  |
| RAID | 9        | 13.85%  |
| IDE  | 7        | 10.77%  |
| SAS  | 3        | 4.62%   |
| SCSI | 1        | 1.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 34       | 87.18%  |
| AMD    | 5        | 12.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz    | 2        | 5.13%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 2        | 5.13%   |
| Intel Core i7-10700K CPU @ 3.80GHz     | 2        | 5.13%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 2        | 5.13%   |
| Intel Xeon CPU X3450 @ 2.67GHz         | 1        | 2.56%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz    | 1        | 2.56%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz    | 1        | 2.56%   |
| Intel Xeon CPU E5-2666 v3 @ 2.90GHz    | 1        | 2.56%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz    | 1        | 2.56%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 1        | 2.56%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz    | 1        | 2.56%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz    | 1        | 2.56%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz    | 1        | 2.56%   |
| Intel Pentium CPU G3240 @ 3.10GHz      | 1        | 2.56%   |
| Intel Pentium CPU G2020 @ 2.90GHz      | 1        | 2.56%   |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 2.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 2.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 1        | 2.56%   |
| Intel Core i7-6800K CPU @ 3.40GHz      | 1        | 2.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 2.56%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1        | 2.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 1        | 2.56%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 1        | 2.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 1        | 2.56%   |
| Intel Core i5-10500 CPU @ 3.10GHz      | 1        | 2.56%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 1        | 2.56%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 1        | 2.56%   |
| Intel Core i3 CPU 550 @ 3.20GHz        | 1        | 2.56%   |
| Intel Core i3 CPU 540 @ 3.07GHz        | 1        | 2.56%   |
| Intel 13th Gen Core i5-13400T          | 1        | 2.56%   |
| Intel 12th Gen Core i9-12900K          | 1        | 2.56%   |
| Intel 12th Gen Core i7-12700           | 1        | 2.56%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 1        | 2.56%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 1        | 2.56%   |
| AMD FX-8350 Eight-Core Processor       | 1        | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Xeon    | 11       | 28.21%  |
| Intel Core i7 | 9        | 23.08%  |
| Intel Core i5 | 4        | 10.26%  |
| Intel Core i3 | 4        | 10.26%  |
| Other         | 3        | 7.69%   |
| AMD Ryzen 5   | 3        | 7.69%   |
| Intel Pentium | 2        | 5.13%   |
| Intel Core i9 | 1        | 2.56%   |
| AMD Ryzen 7   | 1        | 2.56%   |
| AMD FX        | 1        | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 14       | 35.9%   |
| 6      | 7        | 17.95%  |
| 2      | 6        | 15.38%  |
| 16     | 3        | 7.69%   |
| 10     | 3        | 7.69%   |
| 8      | 3        | 7.69%   |
| 20     | 1        | 2.56%   |
| 14     | 1        | 2.56%   |
| 12     | 1        | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 36       | 92.31%  |
| 2      | 3        | 7.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 32       | 82.05%  |
| 1      | 7        | 17.95%  |

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
| Unknown    | 10       | 25.64%  |
| 0x306a9    | 4        | 10.26%  |
| 0xa0655    | 2        | 5.13%   |
| 0x906e9    | 2        | 5.13%   |
| 0x506e3    | 2        | 5.13%   |
| 0x406f1    | 2        | 5.13%   |
| 0x306e4    | 2        | 5.13%   |
| 0x306c3    | 2        | 5.13%   |
| 0x206a7    | 2        | 5.13%   |
| 0xb06f2    | 1        | 2.56%   |
| 0xa0653    | 1        | 2.56%   |
| 0x906ea    | 1        | 2.56%   |
| 0x90672    | 1        | 2.56%   |
| 0x306f2    | 1        | 2.56%   |
| 0x20655    | 1        | 2.56%   |
| 0x106e5    | 1        | 2.56%   |
| 0x0a50000c | 1        | 2.56%   |
| 0x08701030 | 1        | 2.56%   |
| 0x08701013 | 1        | 2.56%   |
| 0x0800820d | 1        | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 8        | 20.51%  |
| Haswell          | 5        | 12.82%  |
| CometLake        | 4        | 10.26%  |
| SandyBridge      | 3        | 7.69%   |
| KabyLake         | 3        | 7.69%   |
| Broadwell        | 3        | 7.69%   |
| Zen 2            | 2        | 5.13%   |
| Westmere         | 2        | 5.13%   |
| Skylake          | 2        | 5.13%   |
| Unknown          | 2        | 5.13%   |
| Zen+             | 1        | 2.56%   |
| Zen 3            | 1        | 2.56%   |
| Piledriver       | 1        | 2.56%   |
| Nehalem          | 1        | 2.56%   |
| Alderlake Hybrid | 1        | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 18       | 40%     |
| Intel                      | 15       | 33.33%  |
| AMD                        | 6        | 13.33%  |
| Matrox Electronics Systems | 5        | 11.11%  |
| ASPEED Technology          | 1        | 2.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 6.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 4.44%   |
| Nvidia GK107GL [Quadro K2000]                                               | 2        | 4.44%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2        | 4.44%   |
| Matrox Electronics Systems MGA G200EH                                       | 2        | 4.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 4.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 4.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 4.44%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 2.22%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 2.22%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.22%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 2.22%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 2.22%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.22%   |
| Nvidia GK110GL [Quadro K6000]                                               | 1        | 2.22%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 2.22%   |
| Nvidia GF110GL [Tesla C2050 / C2075]                                        | 1        | 2.22%   |
| Nvidia GF100GL [Quadro 4000]                                                | 1        | 2.22%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 2.22%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 2.22%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 2.22%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 1        | 2.22%   |
| Matrox Electronics Systems G200eR2                                          | 1        | 2.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2.22%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 1        | 2.22%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 1        | 2.22%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 2.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.22%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 1        | 2.22%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 2.22%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 2.22%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 1        | 2.22%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 2.22%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.22%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 2.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 13       | 33.33%  |
| 1 x Intel      | 10       | 25.64%  |
| 1 x Matrox     | 5        | 12.82%  |
| 1 x AMD        | 4        | 10.26%  |
| Other          | 2        | 5.13%   |
| Intel + Nvidia | 2        | 5.13%   |
| AMD + Nvidia   | 2        | 5.13%   |
| 1 x ASPEED     | 1        | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 29       | 74.36%  |
| Unknown     | 7        | 17.95%  |
| Proprietary | 3        | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 64.1%   |
| 3.01-4.0   | 5        | 12.82%  |
| 1.01-2.0   | 4        | 10.26%  |
| 7.01-8.0   | 2        | 5.13%   |
| 5.01-6.0   | 2        | 5.13%   |
| 8.01-16.0  | 1        | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 16.67%  |
| Dell                | 6        | 16.67%  |
| Hewlett-Packard     | 4        | 11.11%  |
| AOC                 | 3        | 8.33%   |
| Goldstar            | 2        | 5.56%   |
| Chimei Innolux      | 2        | 5.56%   |
| BenQ                | 2        | 5.56%   |
| Vizio               | 1        | 2.78%   |
| Viotek              | 1        | 2.78%   |
| SAC                 | 1        | 2.78%   |
| Philips             | 1        | 2.78%   |
| Packard Bell        | 1        | 2.78%   |
| ODH                 | 1        | 2.78%   |
| Gigabyte Technology | 1        | 2.78%   |
| GameMax             | 1        | 2.78%   |
| Fujitsu Siemens     | 1        | 2.78%   |
| Eizo                | 1        | 2.78%   |
| ASUSTek Computer    | 1        | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch          | 2        | 5.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch     | 2        | 5.26%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                   | 2        | 5.26%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                   | 2        | 5.26%   |
| Vizio V505-J09 VIZ1039 3840x2160 1096x616mm 49.5-inch               | 1        | 2.63%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                | 1        | 2.63%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch | 1        | 2.63%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 700x400mm 31.7-inch   | 1        | 2.63%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch   | 1        | 2.63%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch   | 1        | 2.63%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch   | 1        | 2.63%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch   | 1        | 2.63%   |
| Samsung Electronics LCD Monitor S24C650                             | 1        | 2.63%   |
| Samsung Electronics C34H89x SAM0E26 3440x1440 797x333mm 34.0-inch   | 1        | 2.63%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch               | 1        | 2.63%   |
| Philips 298P4 PHLC0BE 2560x1080 673x284mm 28.8-inch                 | 1        | 2.63%   |
| Packard Bell Viseo223DX PKB037A 1920x1080 477x268mm 21.5-inch       | 1        | 2.63%   |
| ODH DHI-LM27-L200 ODH2700 1920x1080 590x330mm 26.6-inch             | 1        | 2.63%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 518x324mm 24.1-inch         | 1        | 2.63%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch         | 1        | 2.63%   |
| Goldstar L1919S GSM4AF2 1280x1024 380x300mm 19.1-inch               | 1        | 2.63%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                | 1        | 2.63%   |
| Gigabyte Technology G24F 2 GBT2403 1920x1080 527x296mm 23.8-inch    | 1        | 2.63%   |
| GameMax HDMI-DA GMX0001 1920x540                                    | 1        | 2.63%   |
| Fujitsu Siemens B22W-5 ECO FUS07C4 1680x1050 474x296mm 22.0-inch    | 1        | 2.63%   |
| Eizo EV2460 ENC3129 1920x1080 528x297mm 23.9-inch                   | 1        | 2.63%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                   | 1        | 2.63%   |
| Dell P2217H DELA0D9 1920x1080 476x267mm 21.5-inch                   | 1        | 2.63%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                   | 1        | 2.63%   |
| Dell LCD Monitor U2415 3840x1200                                    | 1        | 2.63%   |
| Dell LCD Monitor DEL0001 1280x1024                                  | 1        | 2.63%   |
| Dell DEL 1908FPBLK DEL4048 1280x1024 376x301mm 19.0-inch            | 1        | 2.63%   |
| ASUSTek Computer PA248QV AUS2400 1920x1200 518x324mm 24.1-inch      | 1        | 2.63%   |
| AOC 2590G4 AOC2590 1920x1080 544x303mm 24.5-inch                    | 1        | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 41.18%  |
| 2560x1440 (QHD)    | 3        | 8.82%   |
| 1920x1200 (WUXGA)  | 3        | 8.82%   |
| 3840x2160 (4K)     | 2        | 5.88%   |
| 1366x768 (WXGA)    | 2        | 5.88%   |
| 1280x1024 (SXGA)   | 2        | 5.88%   |
| 3840x1200          | 1        | 2.94%   |
| 3840x1080          | 1        | 2.94%   |
| 3440x1440          | 1        | 2.94%   |
| 2560x1080          | 1        | 2.94%   |
| 1920x540           | 1        | 2.94%   |
| 1680x1050 (WSXGA+) | 1        | 2.94%   |
| 1360x768           | 1        | 2.94%   |
| Unknown            | 1        | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 9        | 25.71%  |
| 21      | 5        | 14.29%  |
| 23      | 3        | 8.57%   |
| Unknown | 3        | 8.57%   |
| 31      | 2        | 5.71%   |
| 27      | 2        | 5.71%   |
| 15      | 2        | 5.71%   |
| 74      | 1        | 2.86%   |
| 48      | 1        | 2.86%   |
| 34      | 1        | 2.86%   |
| 28      | 1        | 2.86%   |
| 26      | 1        | 2.86%   |
| 25      | 1        | 2.86%   |
| 22      | 1        | 2.86%   |
| 19      | 1        | 2.86%   |
| 18      | 1        | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 15       | 45.45%  |
| 401-500     | 6        | 18.18%  |
| 601-700     | 3        | 9.09%   |
| Unknown     | 3        | 9.09%   |
| 301-350     | 2        | 6.06%   |
| 701-800     | 1        | 3.03%   |
| 351-400     | 1        | 3.03%   |
| 1501-2000   | 1        | 3.03%   |
| 1001-1500   | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 20       | 64.52%  |
| 16/10   | 4        | 12.9%   |
| 5/4     | 2        | 6.45%   |
| 32/9    | 2        | 6.45%   |
| 21/9    | 2        | 6.45%   |
| Unknown | 1        | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 36.36%  |
| 251-300        | 5        | 15.15%  |
| 351-500        | 3        | 9.09%   |
| 301-350        | 3        | 9.09%   |
| Unknown        | 3        | 9.09%   |
| 151-200        | 2        | 6.06%   |
| 101-110        | 2        | 6.06%   |
| More than 1000 | 1        | 3.03%   |
| 141-150        | 1        | 3.03%   |
| 501-1000       | 1        | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 61.76%  |
| 101-120 | 9        | 26.47%  |
| Unknown | 3        | 8.82%   |
| 121-160 | 1        | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 56.41%  |
| 0     | 9        | 23.08%  |
| 2     | 6        | 15.38%  |
| 3     | 2        | 5.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 24       | 43.64%  |
| Realtek Semiconductor | 18       | 32.73%  |
| Broadcom              | 5        | 9.09%   |
| Qualcomm Atheros      | 3        | 5.45%   |
| QLogic                | 1        | 1.82%   |
| Mellanox Technologies | 1        | 1.82%   |
| D-Link                | 1        | 1.82%   |
| Broadcom Limited      | 1        | 1.82%   |
| ASUSTek Computer      | 1        | 1.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12       | 18.46%  |
| Intel 82574L Gigabit Network Connection                                | 6        | 9.23%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 6.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 6.15%   |
| Intel I211 Gigabit Network Connection                                  | 3        | 4.62%   |
| Intel Wireless 8260                                                    | 2        | 3.08%   |
| Intel I350 Gigabit Network Connection                                  | 2        | 3.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.54%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 1        | 1.54%   |
| Realtek 802.11ac NIC                                                   | 1        | 1.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1        | 1.54%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller               | 1        | 1.54%   |
| Mellanox MT27500 Family [ConnectX-3]                                   | 1        | 1.54%   |
| Intel Wireless 7260                                                    | 1        | 1.54%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1        | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1        | 1.54%   |
| Intel Ethernet Controller I226-V                                       | 1        | 1.54%   |
| Intel Ethernet Controller I225-V                                       | 1        | 1.54%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.54%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 1.54%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 1.54%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 1.54%   |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 1.54%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1        | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 1.54%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 1.54%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 1.54%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                     | 1        | 1.54%   |
| D-Link Wireless N Nano USB Adapter                                     | 1        | 1.54%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1        | 1.54%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1        | 1.54%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1        | 1.54%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                       | 1        | 1.54%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1        | 1.54%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 1        | 1.54%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]              | 1        | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 47.06%  |
| Realtek Semiconductor | 3        | 17.65%  |
| Qualcomm Atheros      | 2        | 11.76%  |
| D-Link                | 1        | 5.88%   |
| Broadcom Limited      | 1        | 5.88%   |
| Broadcom              | 1        | 5.88%   |
| ASUSTek Computer      | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wireless 8260                                                  | 2        | 11.76%  |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1        | 5.88%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 5.88%   |
| Realtek 802.11ac NIC                                                 | 1        | 5.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 5.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1        | 5.88%   |
| Intel Wireless 7260                                                  | 1        | 5.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1        | 5.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1        | 5.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 5.88%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1        | 5.88%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 5.88%   |
| D-Link Wireless N Nano USB Adapter                                   | 1        | 5.88%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1        | 5.88%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 1        | 5.88%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]            | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 20       | 46.51%  |
| Realtek Semiconductor | 16       | 37.21%  |
| Broadcom              | 4        | 9.3%    |
| Qualcomm Atheros      | 1        | 2.33%   |
| QLogic                | 1        | 2.33%   |
| Mellanox Technologies | 1        | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12       | 25%     |
| Intel 82574L Gigabit Network Connection                                | 6        | 12.5%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 8.33%   |
| Intel I211 Gigabit Network Connection                                  | 3        | 6.25%   |
| Intel I350 Gigabit Network Connection                                  | 2        | 4.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 2.08%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller               | 1        | 2.08%   |
| Mellanox MT27500 Family [ConnectX-3]                                   | 1        | 2.08%   |
| Intel Ethernet Controller I226-V                                       | 1        | 2.08%   |
| Intel Ethernet Controller I225-V                                       | 1        | 2.08%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 2.08%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 2.08%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 2.08%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 2.08%   |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 2.08%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1        | 2.08%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 2.08%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                     | 1        | 2.08%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1        | 2.08%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1        | 2.08%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1        | 2.08%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                       | 1        | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 38       | 70.37%  |
| WiFi     | 16       | 29.63%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 34       | 85%     |
| WiFi     | 6        | 15%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 17       | 43.59%  |
| 1     | 15       | 38.46%  |
| 3     | 3        | 7.69%   |
| 6     | 2        | 5.13%   |
| 7     | 1        | 2.56%   |
| 4     | 1        | 2.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 79.49%  |
| Yes  | 8        | 20.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 46.67%  |
| ASUSTek Computer                | 2        | 13.33%  |
| Apple                           | 2        | 13.33%  |
| Qualcomm Atheros Communications | 1        | 6.67%   |
| IMC Networks                    | 1        | 6.67%   |
| Cambridge Silicon Radio         | 1        | 6.67%   |
| Broadcom                        | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 2        | 13.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 13.33%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 13.33%  |
| Apple Bluetooth Host Controller                     | 2        | 13.33%  |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.67%   |
| Intel AX210 Bluetooth                               | 1        | 6.67%   |
| Intel AX201 Bluetooth                               | 1        | 6.67%   |
| IMC Networks Bluetooth Radio                        | 1        | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 27       | 45.76%  |
| Nvidia                 | 17       | 28.81%  |
| AMD                    | 10       | 16.95%  |
| M-Audio                | 1        | 1.69%   |
| GN Netcom              | 1        | 1.69%   |
| Creative Technology    | 1        | 1.69%   |
| C-Media Electronics    | 1        | 1.69%   |
| AKAI Professional M.I. | 1        | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 6.25%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 4.69%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 3.13%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 3.13%   |
| Nvidia GF110 High Definition Audio Controller                              | 2        | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 3.13%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 3.13%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 3.13%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 3.13%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 3.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 3.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 3.13%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 3.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 3.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 3.13%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 3.13%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.56%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.56%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.56%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1.56%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.56%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.56%   |
| Nvidia AD104 High Definition Audio Controller                              | 1        | 1.56%   |
| M-Audio AIR HUB                                                            | 1        | 1.56%   |
| Intel Raptor Lake High Definition Audio Controller                         | 1        | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.56%   |
| GN Netcom Jabra EVOLVE LINK                                                | 1        | 1.56%   |
| Creative Technology Sound BlasterX G1                                      | 1        | 1.56%   |
| C-Media Electronics Auna Mic CM900                                         | 1        | 1.56%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.56%   |
| AMD Ryzen HD Audio Controller                                              | 1        | 1.56%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 1        | 1.56%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 1.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Micron Technology   | 4        | 16.67%  |
| Kingston            | 4        | 16.67%  |
| Samsung Electronics | 2        | 8.33%   |
| Crucial             | 2        | 8.33%   |
| Unknown             | 2        | 8.33%   |
| Unknown (0x0C26)    | 1        | 4.17%   |
| Unknown             | 1        | 4.17%   |
| Unigen              | 1        | 4.17%   |
| SK hynix            | 1        | 4.17%   |
| Patriot             | 1        | 4.17%   |
| Hewlett-Packard     | 1        | 4.17%   |
| Corsair             | 1        | 4.17%   |
| AVEXIR              | 1        | 4.17%   |
| Avant               | 1        | 4.17%   |
| A-DATA Technology   | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Unknown                                                       | 2        | 6.67%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                     | 1        | 3.33%   |
| Unknown (0x0C26) RAM TIMETEC-UD4-3200 32GB DIMM DDR4 3200MT/s | 1        | 3.33%   |
| Unigen RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 3.33%   |
| SK hynix RAM HMA84GR7AFR4N-UH 32GB DIMM DDR4 2400MT/s         | 1        | 3.33%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s          | 1        | 3.33%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s          | 1        | 3.33%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s               | 1        | 3.33%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s           | 1        | 3.33%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s            | 1        | 3.33%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2666MT/s            | 1        | 3.33%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2448MT/s            | 1        | 3.33%   |
| Micron RAM 4ATF1G64AZ-3G2F1 8GB DIMM DDR4 3200MT/s            | 1        | 3.33%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s         | 1        | 3.33%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s          | 1        | 3.33%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s                | 1        | 3.33%   |
| Kingston RAM 9965525-018.A00LF 4GB DIMM DDR3 1333MT/s         | 1        | 3.33%   |
| Kingston RAM 9965432-052.A00LF 4GB DIMM DDR3                  | 1        | 3.33%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s         | 1        | 3.33%   |
| Kingston RAM 9905403-892.A00LF 8GB DIMM DDR3 1333MT/s         | 1        | 3.33%   |
| HP RAM 669239-081 8GB DIMM DDR3 1600MT/s                      | 1        | 3.33%   |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s     | 1        | 3.33%   |
| Crucial RAM BL16G32C16U4B.M16FE 16GB DIMM DDR4 3466MT/s       | 1        | 3.33%   |
| Corsair RAM CMK8GX4M1E3200C16 8GB DIMM DDR4 3200MT/s          | 1        | 3.33%   |
| Corsair RAM CMK16GX4M1E3200C16 16GB DIMM DDR4 3200MT/s        | 1        | 3.33%   |
| AVEXIR RAM DDR4-2400 CL16 8GB 8GB DIMM DDR4 2400MT/s          | 1        | 3.33%   |
| AVEXIR RAM DDR4-2400 CL16 4GB 4GB DIMM DDR4 2400MT/s          | 1        | 3.33%   |
| Avant RAM J644GU44J2320NQ 32GB SODIMM DDR4 3200MT/s           | 1        | 3.33%   |
| A-DATA RAM AX4U32008G16A-BT60 8GB DIMM DDR4 2666MT/s          | 1        | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 13       | 59.09%  |
| DDR3 | 8        | 36.36%  |
| DRAM | 1        | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 95.24%  |
| SODIMM | 1        | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 11       | 44%     |
| 4096  | 6        | 24%     |
| 16384 | 4        | 16%     |
| 32768 | 3        | 12%     |
| 1024  | 1        | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 5        | 21.74%  |
| 3200    | 4        | 17.39%  |
| 2666    | 3        | 13.04%  |
| 2400    | 3        | 13.04%  |
| 3466    | 2        | 8.7%    |
| 1600    | 2        | 8.7%    |
| 2934    | 1        | 4.35%   |
| 2600    | 1        | 4.35%   |
| 2448    | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Samsung ML-1660 Series | 1        | 100%    |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Microdia            | 2        | 40%     |
| Samsung Electronics | 1        | 20%     |
| OPPO Electronics    | 1        | 20%     |
| Logitech            | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Microdia Webcam Vitade AF               | 2        | 40%     |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 20%     |
| OPPO OnePlus 13R                        | 1        | 20%     |
| Logitech Webcam C270                    | 1        | 20%     |

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
| 0     | 24       | 61.54%  |
| 1     | 8        | 20.51%  |
| 2     | 6        | 15.38%  |
| 3     | 1        | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6        | 28.57%  |
| Unassigned class         | 5        | 23.81%  |
| Net/wireless             | 4        | 19.05%  |
| Communication controller | 3        | 14.29%  |
| Firewire controller      | 2        | 9.52%   |
| Bluetooth                | 1        | 4.76%   |

