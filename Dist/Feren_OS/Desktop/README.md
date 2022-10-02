Feren OS - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Feren OS.

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

Total: 59

| Vendor     | Model                 | Probe                                                      | Date         |
|------------|-----------------------|------------------------------------------------------------|--------------|
| ASUSTek    | Z97-A                 | [14fa58515f](https://linux-hardware.org/?probe=14fa58515f) | Aug 13, 2022 |
| Gigabyte   | Z170X-UD3-CF          | [aecc3e1863](https://linux-hardware.org/?probe=aecc3e1863) | Jul 06, 2022 |
| ASUSTek    | PRIME Z270-A          | [0f85d8c023](https://linux-hardware.org/?probe=0f85d8c023) | Jun 19, 2022 |
| ASUSTek    | PRIME Z270-A          | [dd22c99aac](https://linux-hardware.org/?probe=dd22c99aac) | Jun 14, 2022 |
| Gigabyte   | F2A68HM-DS2           | [1fa6bb2d62](https://linux-hardware.org/?probe=1fa6bb2d62) | May 26, 2022 |
| ASRock     | Z68 Pro3              | [4cdd6daf44](https://linux-hardware.org/?probe=4cdd6daf44) | Jan 19, 2022 |
| LattePanda | Alpha                 | [73f961d1b6](https://linux-hardware.org/?probe=73f961d1b6) | Dec 21, 2021 |
| ASUSTek    | PRIME B450M-A         | [1a8d172b1a](https://linux-hardware.org/?probe=1a8d172b1a) | Nov 02, 2021 |
| MSI        | H61M-P20              | [4c9df75eee](https://linux-hardware.org/?probe=4c9df75eee) | Oct 15, 2021 |
| ASUSTek    | PRIME B350-PLUS       | [97dbb56e7f](https://linux-hardware.org/?probe=97dbb56e7f) | Oct 08, 2021 |
| Pegatron   | Eureka3               | [1a6858321a](https://linux-hardware.org/?probe=1a6858321a) | Sep 06, 2021 |
| Pegatron   | Eureka3               | [c68cf534fd](https://linux-hardware.org/?probe=c68cf534fd) | Sep 06, 2021 |
| ASUSTek    | PRIME B450M-A         | [446300d07d](https://linux-hardware.org/?probe=446300d07d) | Aug 04, 2021 |
| ASUSTek    | PRIME H410M-E         | [3758d2a6b8](https://linux-hardware.org/?probe=3758d2a6b8) | Jul 09, 2021 |
| HP         | 82FE 11               | [acabfe917b](https://linux-hardware.org/?probe=acabfe917b) | Jun 22, 2021 |
| ASRock     | H61M-VS               | [cb1c07fa68](https://linux-hardware.org/?probe=cb1c07fa68) | Jun 17, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS  | [56b16c9c71](https://linux-hardware.org/?probe=56b16c9c71) | May 26, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS  | [fdff074ae2](https://linux-hardware.org/?probe=fdff074ae2) | May 21, 2021 |
| MSI        | 2AE0                  | [cdddabf42c](https://linux-hardware.org/?probe=cdddabf42c) | May 19, 2021 |
| ASRock     | H61M-VS               | [9e701873b1](https://linux-hardware.org/?probe=9e701873b1) | May 09, 2021 |
| ASRock     | H61M-VS               | [59a6774cd5](https://linux-hardware.org/?probe=59a6774cd5) | May 09, 2021 |
| Wortmann   | TERRA_PC              | [9224f13a87](https://linux-hardware.org/?probe=9224f13a87) | Apr 09, 2021 |
| Wortmann   | TERRA_PC              | [c107b4f1a1](https://linux-hardware.org/?probe=c107b4f1a1) | Mar 31, 2021 |
| Dell       | 0FH884                | [3f73f703ea](https://linux-hardware.org/?probe=3f73f703ea) | Feb 25, 2021 |
| Dell       | 0FH884                | [9ef7d7ac26](https://linux-hardware.org/?probe=9ef7d7ac26) | Feb 24, 2021 |
| Gigabyte   | EX58-UD5              | [9743cd82ce](https://linux-hardware.org/?probe=9743cd82ce) | Feb 01, 2021 |
| Pegatron   | 2AC2A                 | [c80b26e32c](https://linux-hardware.org/?probe=c80b26e32c) | Jan 21, 2021 |
| ASUSTek    | H87-PLUS              | [563b11dfc7](https://linux-hardware.org/?probe=563b11dfc7) | Nov 27, 2020 |
| ASUSTek    | H87-PLUS              | [7b22071212](https://linux-hardware.org/?probe=7b22071212) | Nov 27, 2020 |
| MSI        | B360M Xtreme          | [68ebbb560b](https://linux-hardware.org/?probe=68ebbb560b) | Nov 20, 2020 |
| MSI        | MPG X570 GAMING PLUS  | [a1f9dad859](https://linux-hardware.org/?probe=a1f9dad859) | Nov 07, 2020 |
| MSI        | MPG X570 GAMING PLUS  | [f78c0034e0](https://linux-hardware.org/?probe=f78c0034e0) | Nov 07, 2020 |
| Acer       | Aspire TC-105         | [954d6d151c](https://linux-hardware.org/?probe=954d6d151c) | Oct 17, 2020 |
| Acer       | Aspire TC-105         | [4897bba76b](https://linux-hardware.org/?probe=4897bba76b) | Oct 17, 2020 |
| ASUSTek    | PRIME H410M-E         | [c64e54f364](https://linux-hardware.org/?probe=c64e54f364) | Sep 20, 2020 |
| ASUSTek    | PRIME H410M-E         | [df8fbe9e18](https://linux-hardware.org/?probe=df8fbe9e18) | Sep 20, 2020 |
| Acer       | Predator G5910        | [7c7e146182](https://linux-hardware.org/?probe=7c7e146182) | Sep 19, 2020 |
| Acer       | Predator G5910        | [bc07c92db3](https://linux-hardware.org/?probe=bc07c92db3) | Sep 10, 2020 |
| ASUSTek    | H81-PLUS              | [0e79ae7820](https://linux-hardware.org/?probe=0e79ae7820) | Jul 16, 2020 |
| ASRock     | B75 Pro3-M            | [83788eaf01](https://linux-hardware.org/?probe=83788eaf01) | Jun 10, 2020 |
| ASUSTek    | H81-PLUS              | [d5ecf72e99](https://linux-hardware.org/?probe=d5ecf72e99) | May 24, 2020 |
| MSI        | B450M MORTAR TITANIUM | [f347a42df8](https://linux-hardware.org/?probe=f347a42df8) | Apr 27, 2020 |
| MSI        | B450M MORTAR TITANIUM | [4037a9fe71](https://linux-hardware.org/?probe=4037a9fe71) | Apr 24, 2020 |
| Gigabyte   | GA-78LMT-USB3 R2 sex  | [208cce85dd](https://linux-hardware.org/?probe=208cce85dd) | Apr 24, 2020 |
| Dell       | 0200DY A03            | [2b2aa48899](https://linux-hardware.org/?probe=2b2aa48899) | Apr 13, 2020 |
| Dell       | 0T656F A01            | [ea7fa24667](https://linux-hardware.org/?probe=ea7fa24667) | Apr 09, 2020 |
| Dell       | 0T656F A01            | [24a2c39ee5](https://linux-hardware.org/?probe=24a2c39ee5) | Apr 09, 2020 |
| Dell       | 0T656F A01            | [84566f9a9b](https://linux-hardware.org/?probe=84566f9a9b) | Apr 09, 2020 |
| Lenovo     | MAHOBAY               | [651d7ac7be](https://linux-hardware.org/?probe=651d7ac7be) | Feb 28, 2020 |
| Lenovo     | MAHOBAY               | [5b33f9565a](https://linux-hardware.org/?probe=5b33f9565a) | Feb 28, 2020 |
| Foxconn    | 2ABF                  | [e2858c8dd1](https://linux-hardware.org/?probe=e2858c8dd1) | Feb 16, 2020 |
| Medion     | H61H2-LM3 V1.0        | [32f60e252b](https://linux-hardware.org/?probe=32f60e252b) | Jan 02, 2020 |
| Medion     | H61H2-LM3 V1.0        | [070631b0f3](https://linux-hardware.org/?probe=070631b0f3) | Dec 31, 2019 |
| PCWare     | IPMH81G1              | [e962036292](https://linux-hardware.org/?probe=e962036292) | Dec 29, 2019 |
| PCWare     | IPMH81G1              | [ffc38dcd04](https://linux-hardware.org/?probe=ffc38dcd04) | Dec 29, 2019 |
| ASUSTek    | PRIME Z370-A          | [6c0faea524](https://linux-hardware.org/?probe=6c0faea524) | Aug 01, 2019 |
| ASUSTek    | STRIKER II FORMULA    | [17ab95ea83](https://linux-hardware.org/?probe=17ab95ea83) | Jan 22, 2019 |
| ASUSTek    | STRIKER II FORMULA    | [a9a4ca4d08](https://linux-hardware.org/?probe=a9a4ca4d08) | Jan 21, 2019 |
| ASUSTek    | PRIME Z370-A          | [6649ff8a00](https://linux-hardware.org/?probe=6649ff8a00) | Dec 14, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Feren OS 20.04   | 21       | 58.33%  |
| Feren OS 18.04   | 13       | 36.11%  |
| Feren OS 2018.10 | 2        | 5.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Feren OS | 35       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.3.0-46-generic           | 4        | 10.26%  |
| 5.11.0-37-generic          | 3        | 7.69%   |
| 5.8.0-53-generic           | 2        | 5.13%   |
| 5.0.0-37-generic           | 2        | 5.13%   |
| 5.8.0-55-generic           | 1        | 2.56%   |
| 5.8.0-48-generic           | 1        | 2.56%   |
| 5.8.0-44-generic           | 1        | 2.56%   |
| 5.8.0-40-generic           | 1        | 2.56%   |
| 5.8.0-36-generic           | 1        | 2.56%   |
| 5.8.0-29-generic           | 1        | 2.56%   |
| 5.4.66-xanmod1             | 1        | 2.56%   |
| 5.4.0-77-generic           | 1        | 2.56%   |
| 5.4.0-74-generic           | 1        | 2.56%   |
| 5.4.0-72-generic           | 1        | 2.56%   |
| 5.4.0-54-generic           | 1        | 2.56%   |
| 5.4.0-52-generic           | 1        | 2.56%   |
| 5.4.0-47-generic           | 1        | 2.56%   |
| 5.4.0-37-generic           | 1        | 2.56%   |
| 5.4.0-31-generic           | 1        | 2.56%   |
| 5.3.0-59-generic           | 1        | 2.56%   |
| 5.3.0-40-generic           | 1        | 2.56%   |
| 5.3.0-28-generic           | 1        | 2.56%   |
| 5.15.0-46-generic          | 1        | 2.56%   |
| 5.15.0-33-generic          | 1        | 2.56%   |
| 5.15.0-15.1-liquorix-amd64 | 1        | 2.56%   |
| 5.13.0-52-generic          | 1        | 2.56%   |
| 5.13.0-37-generic          | 1        | 2.56%   |
| 5.11.0-27-generic          | 1        | 2.56%   |
| 5.11.0-25-generic          | 1        | 2.56%   |
| 4.15.0-48-generic          | 1        | 2.56%   |
| 4.15.0-43-generic          | 1        | 2.56%   |
| 4.15.0-42-generic          | 1        | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.0   | 8        | 22.22%  |
| 5.3.0   | 7        | 19.44%  |
| 5.4.0   | 6        | 16.67%  |
| 5.11.0  | 4        | 11.11%  |
| 5.15.0  | 3        | 8.33%   |
| 4.15.0  | 3        | 8.33%   |
| 5.13.0  | 2        | 5.56%   |
| 5.0.0   | 2        | 5.56%   |
| 5.4.66  | 1        | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8     | 8        | 22.86%  |
| 5.3     | 7        | 20%     |
| 5.4     | 6        | 17.14%  |
| 5.11    | 4        | 11.43%  |
| 5.15    | 3        | 8.57%   |
| 4.15    | 3        | 8.57%   |
| 5.13    | 2        | 5.71%   |
| 5.0     | 2        | 5.71%   |

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


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE        | 20       | 54.05%  |
| KDE5       | 10       | 27.03%  |
| Unknown    | 4        | 10.81%  |
| X-Cinnamon | 2        | 5.41%   |
| GNOME      | 1        | 2.7%    |

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
| Unknown | 30       | 85.71%  |
| LightDM | 3        | 8.57%   |
| TDM     | 2        | 5.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 8        | 22.22%  |
| en_GB   | 7        | 19.44%  |
| en_AU   | 4        | 11.11%  |
| de_DE   | 3        | 8.33%   |
| Unknown | 3        | 8.33%   |
| pt_BR   | 2        | 5.56%   |
| pt_PT   | 1        | 2.78%   |
| nl_BE   | 1        | 2.78%   |
| it_IT   | 1        | 2.78%   |
| es_VE   | 1        | 2.78%   |
| es_PE   | 1        | 2.78%   |
| es_HN   | 1        | 2.78%   |
| en_IE   | 1        | 2.78%   |
| en_CA   | 1        | 2.78%   |
| de_CH   | 1        | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 51.43%  |
| EFI  | 17       | 48.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 29       | 80.56%  |
| Btrfs   | 4        | 11.11%  |
| Unknown | 3        | 8.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 31       | 86.11%  |
| GPT     | 4        | 11.11%  |
| MBR     | 1        | 2.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 97.14%  |
| Yes       | 1        | 2.86%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 91.43%  |
| Yes       | 3        | 8.57%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 31.43%  |
| MSI                 | 5        | 14.29%  |
| Gigabyte Technology | 4        | 11.43%  |
| Dell                | 3        | 8.57%   |
| ASRock              | 3        | 8.57%   |
| Pegatron            | 2        | 5.71%   |
| Wortmann AG         | 1        | 2.86%   |
| PCWare              | 1        | 2.86%   |
| Medion              | 1        | 2.86%   |
| Lenovo              | 1        | 2.86%   |
| Hewlett-Packard     | 1        | 2.86%   |
| Foxconn             | 1        | 2.86%   |
| Acer                | 1        | 2.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 3        | 8.57%   |
| ASUS PRIME Z370-A               | 2        | 5.71%   |
| Wortmann AG TERRA_PC            | 1        | 2.86%   |
| Pegatron p7-1030                | 1        | 2.86%   |
| Pegatron AY691AA-ABA p6367c     | 1        | 2.86%   |
| PCWare IPMH81G1                 | 1        | 2.86%   |
| MSI MS-7C37                     | 1        | 2.86%   |
| MSI MS-7B89                     | 1        | 2.86%   |
| MSI MS-7788                     | 1        | 2.86%   |
| MSI C Series                    | 1        | 2.86%   |
| MSI 700-216                     | 1        | 2.86%   |
| Medion H61H2-LM3                | 1        | 2.86%   |
| Lenovo ThinkCentre M72z 3548B2S | 1        | 2.86%   |
| HP Pavilion Desktop PC 570-p0xx | 1        | 2.86%   |
| Gigabyte Z170X-UD3              | 1        | 2.86%   |
| Gigabyte GA-78LMT-USB3 R2       | 1        | 2.86%   |
| Gigabyte F2A68HM-DS2            | 1        | 2.86%   |
| Gigabyte EX58-UD5               | 1        | 2.86%   |
| Foxconn Pro3500 Series          | 1        | 2.86%   |
| Dell OptiPlex GX620             | 1        | 2.86%   |
| Dell OptiPlex 780               | 1        | 2.86%   |
| Dell OptiPlex 360               | 1        | 2.86%   |
| ASUS TUF Gaming X570-PLUS       | 1        | 2.86%   |
| ASUS STRIKER II FORMULA         | 1        | 2.86%   |
| ASUS PRIME Z270-A               | 1        | 2.86%   |
| ASUS PRIME H410M-E              | 1        | 2.86%   |
| ASUS PRIME B450M-A              | 1        | 2.86%   |
| ASUS PRIME B350-PLUS            | 1        | 2.86%   |
| ASRock Z68 Pro3                 | 1        | 2.86%   |
| ASRock H61M-VS                  | 1        | 2.86%   |
| ASRock B75 Pro3-M               | 1        | 2.86%   |
| Acer Predator G5910             | 1        | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 6        | 17.14%  |
| Dell OptiPlex          | 3        | 8.57%   |
| ASUS All               | 3        | 8.57%   |
| Wortmann AG TERRA      | 1        | 2.86%   |
| Pegatron p7-1030       | 1        | 2.86%   |
| Pegatron AY691AA-ABA   | 1        | 2.86%   |
| PCWare IPMH81G1        | 1        | 2.86%   |
| MSI MS-7C37            | 1        | 2.86%   |
| MSI MS-7B89            | 1        | 2.86%   |
| MSI MS-7788            | 1        | 2.86%   |
| MSI C                  | 1        | 2.86%   |
| MSI 700-216            | 1        | 2.86%   |
| Medion H61H2-LM3       | 1        | 2.86%   |
| Lenovo ThinkCentre     | 1        | 2.86%   |
| HP Pavilion            | 1        | 2.86%   |
| Gigabyte Z170X-UD3     | 1        | 2.86%   |
| Gigabyte GA-78LMT-USB3 | 1        | 2.86%   |
| Gigabyte F2A68HM-DS2   | 1        | 2.86%   |
| Gigabyte EX58-UD5      | 1        | 2.86%   |
| Foxconn Pro3500        | 1        | 2.86%   |
| ASUS TUF               | 1        | 2.86%   |
| ASUS STRIKER           | 1        | 2.86%   |
| ASRock Z68             | 1        | 2.86%   |
| ASRock H61M-VS         | 1        | 2.86%   |
| ASRock B75             | 1        | 2.86%   |
| Acer Predator          | 1        | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2017 | 5        | 14.29%  |
| 2011 | 5        | 14.29%  |
| 2014 | 4        | 11.43%  |
| 2013 | 4        | 11.43%  |
| 2012 | 4        | 11.43%  |
| 2019 | 3        | 8.57%   |
| 2018 | 2        | 5.71%   |
| 2009 | 2        | 5.71%   |
| 2008 | 2        | 5.71%   |
| 2020 | 1        | 2.86%   |
| 2016 | 1        | 2.86%   |
| 2015 | 1        | 2.86%   |
| 2006 | 1        | 2.86%   |

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


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 8        | 22.22%  |
| 4.01-8.0    | 7        | 19.44%  |
| 32.01-64.0  | 7        | 19.44%  |
| 16.01-24.0  | 6        | 16.67%  |
| 3.01-4.0    | 5        | 13.89%  |
| 24.01-32.0  | 1        | 2.78%   |
| 64.01-256.0 | 1        | 2.78%   |
| 1.01-2.0    | 1        | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 16       | 43.24%  |
| 2.01-3.0  | 11       | 29.73%  |
| 4.01-8.0  | 4        | 10.81%  |
| 3.01-4.0  | 4        | 10.81%  |
| 8.01-16.0 | 1        | 2.7%    |
| 0.51-1.0  | 1        | 2.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 43.24%  |
| 3      | 8        | 21.62%  |
| 2      | 8        | 21.62%  |
| 4      | 3        | 8.11%   |
| 7      | 1        | 2.7%    |
| 5      | 1        | 2.7%    |

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
| Yes       | 35       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 62.86%  |
| Yes       | 13       | 37.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 77.78%  |
| Yes       | 8        | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 20%     |
| Australia   | 5        | 14.29%  |
| Germany     | 4        | 11.43%  |
| UK          | 3        | 8.57%   |
| Brazil      | 3        | 8.57%   |
| Switzerland | 2        | 5.71%   |
| Venezuela   | 1        | 2.86%   |
| Portugal    | 1        | 2.86%   |
| Peru        | 1        | 2.86%   |
| Norway      | 1        | 2.86%   |
| Jordan      | 1        | 2.86%   |
| Italy       | 1        | 2.86%   |
| Ireland     | 1        | 2.86%   |
| Honduras    | 1        | 2.86%   |
| Canada      | 1        | 2.86%   |
| Belgium     | 1        | 2.86%   |
| Argentina   | 1        | 2.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Richmond       | 2        | 5.41%   |
| Melbourne      | 2        | 5.41%   |
| Wrexham        | 1        | 2.7%    |
| Winterthur     | 1        | 2.7%    |
| Tegucigalpa    | 1        | 2.7%    |
| Stavanger      | 1        | 2.7%    |
| Sligo          | 1        | 2.7%    |
| Seattle        | 1        | 2.7%    |
| Schleusingen   | 1        | 2.7%    |
| Sao Jose       | 1        | 2.7%    |
| Sankt Augustin | 1        | 2.7%    |
| Recklinghausen | 1        | 2.7%    |
| Oudenaarde     | 1        | 2.7%    |
| Oberwil-Lieli  | 1        | 2.7%    |
| New York       | 1        | 2.7%    |
| Naples         | 1        | 2.7%    |
| Macaé         | 1        | 2.7%    |
| Los Angeles    | 1        | 2.7%    |
| Lima           | 1        | 2.7%    |
| Hummeltal      | 1        | 2.7%    |
| Hobart         | 1        | 2.7%    |
| Glasgow        | 1        | 2.7%    |
| Funchal        | 1        | 2.7%    |
| Fort St. John  | 1        | 2.7%    |
| Edinburg       | 1        | 2.7%    |
| Chapecó       | 1        | 2.7%    |
| Caracas        | 1        | 2.7%    |
| Buenos Aires   | 1        | 2.7%    |
| Bridgwater     | 1        | 2.7%    |
| Bellport       | 1        | 2.7%    |
| Bellflower     | 1        | 2.7%    |
| Barletta       | 1        | 2.7%    |
| Barinas        | 1        | 2.7%    |
| Bakersfield    | 1        | 2.7%    |
| Amman          | 1        | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 17       | 27     | 28.81%  |
| Seagate                   | 13       | 19     | 22.03%  |
| Samsung Electronics       | 6        | 9      | 10.17%  |
| Hitachi                   | 5        | 6      | 8.47%   |
| Toshiba                   | 4        | 5      | 6.78%   |
| Kingston                  | 4        | 10     | 6.78%   |
| SanDisk                   | 2        | 3      | 3.39%   |
| Verbatim                  | 1        | 1      | 1.69%   |
| Unknown                   | 1        | 1      | 1.69%   |
| Realtek Semiconductor     | 1        | 1      | 1.69%   |
| PNY                       | 1        | 1      | 1.69%   |
| Micron/Crucial Technology | 1        | 1      | 1.69%   |
| Intel                     | 1        | 1      | 1.69%   |
| Crucial                   | 1        | 1      | 1.69%   |
| A-DATA Technology         | 1        | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST4000LM016-1N2170 4TB   | 2        | 2.99%   |
| Seagate ST31000528AS 1TB         | 2        | 2.99%   |
| Samsung HD103SJ 1TB              | 2        | 2.99%   |
| Kingston SA400S37480G 480GB SSD  | 2        | 2.99%   |
| Hitachi HDS721010CLA332 1TB      | 2        | 2.99%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 1.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 1.49%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1        | 1.49%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 1.49%   |
| WDC WD80EFBX-68AZZN0 8TB         | 1        | 1.49%   |
| WDC WD6400AAKS-00A7B2 640GB      | 1        | 1.49%   |
| WDC WD5000BPKT-60PK4T0 500GB     | 1        | 1.49%   |
| WDC WD5000AAVS-00G9B1 500GB      | 1        | 1.49%   |
| WDC WD5000AAKS-65A7B2 500GB      | 1        | 1.49%   |
| WDC WD5000AAKS-00A7B2 500GB      | 1        | 1.49%   |
| WDC WD30EZRX-00MMMB0 3TB         | 1        | 1.49%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1        | 1.49%   |
| WDC WD2500AAKX-75U6AA0 250GB     | 1        | 1.49%   |
| WDC WD1600AAJS-00L7A0 160GB      | 1        | 1.49%   |
| WDC WD10PURX-78E5EY0 1TB         | 1        | 1.49%   |
| WDC WD10JPVX-22JC3T0 1TB         | 1        | 1.49%   |
| WDC WD10EZEX-60WN4A0 1TB         | 1        | 1.49%   |
| WDC WD10EZEX-22MFCA0 1TB         | 1        | 1.49%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 1.49%   |
| WDC WD10EZEX-00WN4A0 1TB         | 1        | 1.49%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 1.49%   |
| WDC WD10EURX-83UY4Y0 1TB         | 1        | 1.49%   |
| Verbatim Vi550 S3 SSD 512GB      | 1        | 1.49%   |
| Unknown SD/MMC/MS PRO 2GB        | 1        | 1.49%   |
| Toshiba THNSNJ256GCST 256GB SSD  | 1        | 1.49%   |
| Toshiba MK3275GSX 320GB          | 1        | 1.49%   |
| Toshiba MK1234GSX 120GB          | 1        | 1.49%   |
| Toshiba HDWE140 4TB              | 1        | 1.49%   |
| Toshiba DT01ACA100 1TB           | 1        | 1.49%   |
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1.49%   |
| Seagate ST3500630NS 500GB        | 1        | 1.49%   |
| Seagate ST3500418AS 500GB        | 1        | 1.49%   |
| Seagate ST3320418AS 320GB        | 1        | 1.49%   |
| Seagate ST2000DM008-2FR102 2TB   | 1        | 1.49%   |
| Seagate ST2000DM001-9YN164 2TB   | 1        | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 23     | 38.46%  |
| Seagate             | 13       | 19     | 33.33%  |
| Hitachi             | 5        | 6      | 12.82%  |
| Toshiba             | 3        | 4      | 7.69%   |
| Samsung Electronics | 2        | 3      | 5.13%   |
| Unknown             | 1        | 1      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 22.22%  |
| Kingston            | 4        | 10     | 22.22%  |
| WDC                 | 3        | 3      | 16.67%  |
| Verbatim            | 1        | 1      | 5.56%   |
| Toshiba             | 1        | 1      | 5.56%   |
| SanDisk             | 1        | 1      | 5.56%   |
| PNY                 | 1        | 1      | 5.56%   |
| Intel               | 1        | 1      | 5.56%   |
| Crucial             | 1        | 1      | 5.56%   |
| A-DATA Technology   | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 31       | 56     | 59.62%  |
| SSD  | 16       | 25     | 30.77%  |
| NVMe | 5        | 6      | 9.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 35       | 80     | 85.37%  |
| NVMe | 5        | 6      | 12.2%   |
| SAS  | 1        | 1      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 23       | 36     | 44.23%  |
| 0.51-1.0   | 18       | 29     | 34.62%  |
| 1.01-2.0   | 5        | 6      | 9.62%   |
| 3.01-4.0   | 3        | 7      | 5.77%   |
| 2.01-3.0   | 2        | 2      | 3.85%   |
| 4.01-10.0  | 1        | 1      | 1.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 11       | 28.95%  |
| 251-500        | 9        | 23.68%  |
| 501-1000       | 7        | 18.42%  |
| More than 3000 | 4        | 10.53%  |
| 101-250        | 4        | 10.53%  |
| 2001-3000      | 3        | 7.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 251-500   | 10       | 26.32%  |
| 1-20      | 8        | 21.05%  |
| 101-250   | 6        | 15.79%  |
| 21-50     | 5        | 13.16%  |
| 501-1000  | 5        | 13.16%  |
| 51-100    | 3        | 7.89%   |
| 1001-2000 | 1        | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD5000AAVS-00G9B1 500GB | 1        | 1      | 33.33%  |
| Toshiba MK1234GSX 120GB     | 1        | 1      | 33.33%  |
| Seagate ST3500418AS 500GB   | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Toshiba | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Toshiba | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 3      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Seagate ST31000528AS 1TB | 1        | 1      | 100%    |

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
| Detected | 31       | 70     | 79.49%  |
| Works    | 5        | 13     | 12.82%  |
| Malfunc  | 2        | 3      | 5.13%   |
| Failed   | 1        | 1      | 2.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 25       | 55.56%  |
| AMD                       | 9        | 20%     |
| Samsung Electronics       | 3        | 6.67%   |
| SanDisk                   | 2        | 4.44%   |
| ASMedia Technology        | 2        | 4.44%   |
| Realtek Semiconductor     | 1        | 2.22%   |
| Nvidia                    | 1        | 2.22%   |
| Micron/Crucial Technology | 1        | 2.22%   |
| JMicron Technology        | 1        | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 10%     |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 5%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 5%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 5%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 3.33%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 3.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 3.33%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 3.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 3.33%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 3.33%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 1.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.67%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 1.67%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 1.67%   |
| Nvidia MCP55 IDE                                                                        | 1        | 1.67%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 1.67%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.67%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.67%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.67%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 1.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.67%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.67%   |
| AMD RS690 PCI to PCI Bridge (PCI Express Port 2)                                        | 1        | 1.67%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.67%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 25       | 55.56%  |
| IDE  | 12       | 26.67%  |
| NVMe | 7        | 15.56%  |
| RAID | 1        | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 26       | 74.29%  |
| AMD    | 9        | 25.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 5.71%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 2        | 5.71%   |
| Intel Pentium D CPU 3.00GHz                    | 1        | 2.86%   |
| Intel Pentium CPU G630 @ 2.70GHz               | 1        | 2.86%   |
| Intel Pentium CPU G3250 @ 3.20GHz              | 1        | 2.86%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 2.86%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 2.86%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 1        | 2.86%   |
| Intel Core i7-3770S CPU @ 3.10GHz              | 1        | 2.86%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1        | 2.86%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 2.86%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 2.86%   |
| Intel Core i7 CPU 920 @ 2.67GHz                | 1        | 2.86%   |
| Intel Core i5-9400F CPU @ 2.90GHz              | 1        | 2.86%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 1        | 2.86%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1        | 2.86%   |
| Intel Core i5-3330 CPU @ 3.00GHz               | 1        | 2.86%   |
| Intel Core i3-3240 CPU @ 3.40GHz               | 1        | 2.86%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz          | 1        | 2.86%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1        | 2.86%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 2.86%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz           | 1        | 2.86%   |
| Intel Celeron CPU G1840 @ 2.80GHz              | 1        | 2.86%   |
| Intel Celeron CPU 1007U @ 1.50GHz              | 1        | 2.86%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 2.86%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 2.86%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 2.86%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 1        | 2.86%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 1        | 2.86%   |
| AMD FX-8350 Eight-Core Processor               | 1        | 2.86%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G  | 1        | 2.86%   |
| AMD A8-7650K Radeon R7, 10 Compute Cores 4C+6G | 1        | 2.86%   |
| AMD A10-6700 APU with Radeon HD Graphics       | 1        | 2.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i7     | 10       | 28.57%  |
| Intel Core i5     | 4        | 11.43%  |
| Intel Core i3     | 3        | 8.57%   |
| Intel Core 2 Quad | 3        | 8.57%   |
| Intel Pentium     | 2        | 5.71%   |
| Intel Celeron     | 2        | 5.71%   |
| AMD Ryzen 7       | 2        | 5.71%   |
| AMD Ryzen 5       | 2        | 5.71%   |
| AMD A8            | 2        | 5.71%   |
| Intel Pentium D   | 1        | 2.86%   |
| Intel Core 2 Duo  | 1        | 2.86%   |
| AMD Ryzen 9       | 1        | 2.86%   |
| AMD FX            | 1        | 2.86%   |
| AMD A10           | 1        | 2.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 15       | 42.86%  |
| 2      | 12       | 34.29%  |
| 6      | 4        | 11.43%  |
| 8      | 3        | 8.57%   |
| 12     | 1        | 2.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 62.86%  |
| 1      | 13       | 37.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 32       | 91.43%  |
| Unknown        | 3        | 8.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 5        | 14.29%  |
| 0x306c3    | 4        | 11.43%  |
| 0x206a7    | 4        | 11.43%  |
| 0x906ea    | 3        | 8.57%   |
| 0x1067a    | 3        | 8.57%   |
| 0x0800820d | 2        | 5.71%   |
| 0xf62      | 1        | 2.86%   |
| 0xa0655    | 1        | 2.86%   |
| 0x906e9    | 1        | 2.86%   |
| 0x6fb      | 1        | 2.86%   |
| 0x506e3    | 1        | 2.86%   |
| 0x106a5    | 1        | 2.86%   |
| 0x08701021 | 1        | 2.86%   |
| 0x0810100b | 1        | 2.86%   |
| 0x08001138 | 1        | 2.86%   |
| 0x0600611a | 1        | 2.86%   |
| 0x06003104 | 1        | 2.86%   |
| 0x06001119 | 1        | 2.86%   |
| 0x06000852 | 1        | 2.86%   |
| Unknown    | 1        | 2.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 5        | 14.29%  |
| IvyBridge   | 5        | 14.29%  |
| KabyLake    | 4        | 11.43%  |
| Haswell     | 4        | 11.43%  |
| Penryn      | 3        | 8.57%   |
| Zen+        | 2        | 5.71%   |
| Zen         | 2        | 5.71%   |
| Piledriver  | 2        | 5.71%   |
| Zen 2       | 1        | 2.86%   |
| Steamroller | 1        | 2.86%   |
| Skylake     | 1        | 2.86%   |
| NetBurst    | 1        | 2.86%   |
| Nehalem     | 1        | 2.86%   |
| Excavator   | 1        | 2.86%   |
| Core        | 1        | 2.86%   |
| CometLake   | 1        | 2.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 15       | 40.54%  |
| Intel  | 14       | 37.84%  |
| AMD    | 8        | 21.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 5.41%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 5.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 5.41%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 5.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 5.41%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 5.41%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.7%    |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.7%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 2.7%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 2.7%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 2.7%    |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 2.7%    |
| Nvidia GK107 [NVS 510]                                                      | 1        | 2.7%    |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 2.7%    |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 2.7%    |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 2.7%    |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 2.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 2.7%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 2.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.7%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 2.7%    |
| AMD RV620 LE [Radeon HD 3450]                                               | 1        | 2.7%    |
| AMD Richland [Radeon HD 8670D]                                              | 1        | 2.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.7%    |
| AMD Navi 14 [Radeon Pro W5500]                                              | 1        | 2.7%    |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 2.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 2.7%    |
| AMD Barts XT [Radeon HD 6870]                                               | 1        | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 14       | 40%     |
| 1 x Intel      | 12       | 34.29%  |
| 1 x AMD        | 8        | 22.86%  |
| Intel + Nvidia | 1        | 2.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 23       | 62.16%  |
| Proprietary | 12       | 32.43%  |
| Unknown     | 2        | 5.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 36.11%  |
| 1.01-2.0   | 7        | 19.44%  |
| 0.51-1.0   | 6        | 16.67%  |
| 7.01-8.0   | 4        | 11.11%  |
| 3.01-4.0   | 3        | 8.33%   |
| 0.01-0.5   | 2        | 5.56%   |
| 5.01-6.0   | 1        | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 6        | 17.65%  |
| Dell                    | 4        | 11.76%  |
| Acer                    | 4        | 11.76%  |
| Lenovo                  | 3        | 8.82%   |
| Hewlett-Packard         | 2        | 5.88%   |
| AOC                     | 2        | 5.88%   |
| Vestel                  | 1        | 2.94%   |
| Unknown                 | 1        | 2.94%   |
| Sceptre Tech            | 1        | 2.94%   |
| Philips                 | 1        | 2.94%   |
| Onkyo                   | 1        | 2.94%   |
| Medion                  | 1        | 2.94%   |
| LG Electronics          | 1        | 2.94%   |
| Lenovo Group Limited    | 1        | 2.94%   |
| Insignia                | 1        | 2.94%   |
| Goldstar                | 1        | 2.94%   |
| Chi Mei Optoelectronics | 1        | 2.94%   |
| BenQ                    | 1        | 2.94%   |
| Ancor Communications    | 1        | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Vestel LCD Monitor 32W_LCD_TV 1920x1080                                | 1        | 2.63%   |
| Unknown LCD Monitor SAMSUNG                                            | 1        | 2.63%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch         | 1        | 2.63%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch      | 1        | 2.63%   |
| Samsung Electronics LCD Monitor U28E590 7680x2160                      | 1        | 2.63%   |
| Samsung Electronics LCD Monitor U28E590                                | 1        | 2.63%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch   | 1        | 2.63%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch | 1        | 2.63%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1        | 2.63%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 1        | 2.63%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch      | 1        | 2.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 2.63%   |
| Philips PHL 328E9Q PHLC180 1920x1080 698x393mm 31.5-inch               | 1        | 2.63%   |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                   | 1        | 2.63%   |
| Medion MD 20094 MED3610 1920x1200 550x344mm 25.5-inch                  | 1        | 2.63%   |
| LG Electronics LCD Monitor MP59HT 1920x1080                            | 1        | 2.63%   |
| Lenovo LEN L171 LEN240B 1280x1024 340x270mm 17.1-inch                  | 1        | 2.63%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                   | 1        | 2.63%   |
| Lenovo H61 LEN520B 1600x900 410x230mm 18.5-inch                        | 1        | 2.63%   |
| Lenovo Group Limited LCD Monitor L24q-10 2560x1440                     | 1        | 2.63%   |
| Insignia NS-24EM51A14 BBYBB24 1920x1080 531x299mm 24.0-inch            | 1        | 2.63%   |
| Hewlett-Packard ZR22w HWP2867 1920x1080 475x267mm 21.5-inch            | 1        | 2.63%   |
| Hewlett-Packard LCD Monitor ZR22w 3840x1080                            | 1        | 2.63%   |
| Hewlett-Packard 2509 HWP283A 1920x1080 553x311mm 25.0-inch             | 1        | 2.63%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                   | 1        | 2.63%   |
| Dell UP3017 DEL40FA 2560x1600 640x400mm 29.7-inch                      | 1        | 2.63%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 1        | 2.63%   |
| Dell SP1908FP DEL4030 1280x1024 376x301mm 19.0-inch                    | 1        | 2.63%   |
| Dell S2715H DEL40BB 1920x1080 598x336mm 27.0-inch                      | 1        | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMC 19AW 1440x900                  | 1        | 2.63%   |
| BenQ BL3200 BNQ8017 2560x1440 708x398mm 32.0-inch                      | 1        | 2.63%   |
| AOC LM522 AOCA522 1024x768 304x228mm 15.0-inch                         | 1        | 2.63%   |
| AOC LCD Monitor 1943W 1366x768                                         | 1        | 2.63%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch       | 1        | 2.63%   |
| Acer VG270U ACR06C9 2560x1440 600x340mm 27.2-inch                      | 1        | 2.63%   |
| Acer V273HL ACR02D0 1920x1080 598x336mm 27.0-inch                      | 1        | 2.63%   |
| Acer S242HL ACR0216 1920x1080 531x299mm 24.0-inch                      | 1        | 2.63%   |
| Acer LCD Monitor VG270U 2560x1440                                      | 1        | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 15       | 44.12%  |
| 2560x1440 (QHD)   | 4        | 11.76%  |
| 3840x2160 (4K)    | 2        | 5.88%   |
| 1366x768 (WXGA)   | 2        | 5.88%   |
| 1280x1024 (SXGA)  | 2        | 5.88%   |
| Unknown           | 2        | 5.88%   |
| 7680x2160         | 1        | 2.94%   |
| 3840x1080         | 1        | 2.94%   |
| 2560x1600         | 1        | 2.94%   |
| 1920x1200 (WUXGA) | 1        | 2.94%   |
| 1600x900 (HD+)    | 1        | 2.94%   |
| 1440x900 (WXGA+)  | 1        | 2.94%   |
| 1024x768 (XGA)    | 1        | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 23.53%  |
| 27      | 6        | 17.65%  |
| 24      | 4        | 11.76%  |
| 32      | 2        | 5.88%   |
| 31      | 2        | 5.88%   |
| 25      | 2        | 5.88%   |
| 21      | 2        | 5.88%   |
| 54      | 1        | 2.94%   |
| 49      | 1        | 2.94%   |
| 29      | 1        | 2.94%   |
| 23      | 1        | 2.94%   |
| 19      | 1        | 2.94%   |
| 18      | 1        | 2.94%   |
| 17      | 1        | 2.94%   |
| 15      | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 38.24%  |
| Unknown     | 8        | 23.53%  |
| 601-700     | 3        | 8.82%   |
| 401-500     | 3        | 8.82%   |
| 701-800     | 2        | 5.88%   |
| 301-350     | 2        | 5.88%   |
| 1001-1500   | 2        | 5.88%   |
| 351-400     | 1        | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 57.58%  |
| Unknown | 8        | 24.24%  |
| 16/10   | 3        | 9.09%   |
| 5/4     | 2        | 6.06%   |
| 4/3     | 1        | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 8        | 23.53%  |
| 301-350        | 6        | 17.65%  |
| 201-250        | 6        | 17.65%  |
| 351-500        | 5        | 14.71%  |
| 251-300        | 3        | 8.82%   |
| More than 1000 | 2        | 5.88%   |
| 141-150        | 2        | 5.88%   |
| 151-200        | 1        | 2.94%   |
| 101-110        | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 18       | 52.94%  |
| Unknown | 8        | 23.53%  |
| 101-120 | 4        | 11.76%  |
| 1-50    | 2        | 5.88%   |
| 121-160 | 2        | 5.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 80.56%  |
| 2     | 5        | 13.89%  |
| 0     | 2        | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 22       | 47.83%  |
| Intel                           | 9        | 19.57%  |
| Ralink                          | 2        | 4.35%   |
| Qualcomm Atheros                | 2        | 4.35%   |
| Linksys                         | 2        | 4.35%   |
| Broadcom                        | 2        | 4.35%   |
| TP-Link                         | 1        | 2.17%   |
| Ralink Technology               | 1        | 2.17%   |
| Qualcomm Atheros Communications | 1        | 2.17%   |
| Nvidia                          | 1        | 2.17%   |
| NetGear                         | 1        | 2.17%   |
| Edimax Technology               | 1        | 2.17%   |
| D-Link                          | 1        | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                        | Desktops | Percent |
|------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller            | 21       | 41.18%  |
| Intel Ethernet Connection (2) I219-V                                         | 4        | 7.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                   | 1        | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                     | 1        | 1.96%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                       | 1        | 1.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                   | 1        | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                        | 1        | 1.96%   |
| Ralink RT2501/RT2573 Wireless Adapter                                        | 1        | 1.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                    | 1        | 1.96%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                         | 1        | 1.96%   |
| Qualcomm Atheros AR9271 802.11n                                              | 1        | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                             | 1        | 1.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                     | 1        | 1.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                   | 1        | 1.96%   |
| Nvidia MCP55 Ethernet                                                        | 1        | 1.96%   |
| NetGear A6210                                                                | 1        | 1.96%   |
| Linksys WUSB6300 V2                                                          | 1        | 1.96%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]       | 1        | 1.96%   |
| Intel Ethernet Connection (7) I219-V                                         | 1        | 1.96%   |
| Intel Ethernet Connection (2) I218-V                                         | 1        | 1.96%   |
| Intel Centrino Wireless-N 2230                                               | 1        | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                              | 1        | 1.96%   |
| Intel 82579V Gigabit Network Connection                                      | 1        | 1.96%   |
| Intel 82567LM-3 Gigabit Network Connection                                   | 1        | 1.96%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                     | 1        | 1.96%   |
| D-Link DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.B2) [Ralink RT5572] | 1        | 1.96%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                      | 1        | 1.96%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                              | 1        | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 3        | 18.75%  |
| Ralink                          | 2        | 12.5%   |
| Linksys                         | 2        | 12.5%   |
| Intel                           | 2        | 12.5%   |
| TP-Link                         | 1        | 6.25%   |
| Ralink Technology               | 1        | 6.25%   |
| Qualcomm Atheros Communications | 1        | 6.25%   |
| Qualcomm Atheros                | 1        | 6.25%   |
| NetGear                         | 1        | 6.25%   |
| Edimax Technology               | 1        | 6.25%   |
| D-Link                          | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                        | Desktops | Percent |
|------------------------------------------------------------------------------|----------|---------|
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                   | 1        | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                     | 1        | 6.25%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                       | 1        | 6.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                   | 1        | 6.25%   |
| Ralink RT2501/RT2573 Wireless Adapter                                        | 1        | 6.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                    | 1        | 6.25%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                         | 1        | 6.25%   |
| Qualcomm Atheros AR9271 802.11n                                              | 1        | 6.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                             | 1        | 6.25%   |
| NetGear A6210                                                                | 1        | 6.25%   |
| Linksys WUSB6300 V2                                                          | 1        | 6.25%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]       | 1        | 6.25%   |
| Intel Centrino Wireless-N 2230                                               | 1        | 6.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                              | 1        | 6.25%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                     | 1        | 6.25%   |
| D-Link DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.B2) [Ralink RT5572] | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 62.86%  |
| Intel                 | 8        | 22.86%  |
| Qualcomm Atheros      | 2        | 5.71%   |
| Broadcom              | 2        | 5.71%   |
| Nvidia                | 1        | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 60%     |
| Intel Ethernet Connection (2) I219-V                              | 4        | 11.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 2.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 2.86%   |
| Nvidia MCP55 Ethernet                                             | 1        | 2.86%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.86%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.86%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 2.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.86%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 2.86%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 35       | 72.92%  |
| WiFi     | 13       | 27.08%  |

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
| 1     | 27       | 77.14%  |
| 2     | 8        | 22.86%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 88.57%  |
| Yes  | 4        | 11.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 3        | 37.5%   |
| Intel                   | 2        | 25%     |
| Realtek Semiconductor   | 1        | 12.5%   |
| Ralink                  | 1        | 12.5%   |
| Broadcom                | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 37.5%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 12.5%   |
| Ralink RT3290 Bluetooth                             | 1        | 12.5%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 12.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 12.5%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 25       | 43.1%   |
| Nvidia              | 15       | 25.86%  |
| AMD                 | 11       | 18.97%  |
| C-Media Electronics | 2        | 3.45%   |
| Razer USA           | 1        | 1.72%   |
| Microsoft           | 1        | 1.72%   |
| Logitech            | 1        | 1.72%   |
| Hewlett-Packard     | 1        | 1.72%   |
| Creative Labs       | 1        | 1.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 12.31%  |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 4.62%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 4.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 4.62%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 4.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 4.62%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 3.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 3.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 3.08%   |
| AMD FCH Azalia Controller                                                  | 2        | 3.08%   |
| Razer USA Nommo Chroma                                                     | 1        | 1.54%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.54%   |
| Nvidia MCP55 High Definition Audio                                         | 1        | 1.54%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.54%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.54%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.54%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.54%   |
| Microsoft LifeChat LX-3000 Headset                                         | 1        | 1.54%   |
| Logitech Headset H390                                                      | 1        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.54%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.54%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.54%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.54%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.54%   |
| Hewlett-Packard S101 Speaker Bar                                           | 1        | 1.54%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1.54%   |
| C-Media Electronics USB MICROPHONE                                         | 1        | 1.54%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.54%   |
| C-Media Electronics Audio Adapter                                          | 1        | 1.54%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 1.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 1.54%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.54%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1        | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.54%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 1.54%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 1.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 1        | 11.11%  |
| Samsung Electronics | 1        | 11.11%  |
| Nanya Technology    | 1        | 11.11%  |
| Kingston            | 1        | 11.11%  |
| Hewlett-Packard     | 1        | 11.11%  |
| G.Skill             | 1        | 11.11%  |
| Crucial             | 1        | 11.11%  |
| Corsair             | 1        | 11.11%  |
| A-DATA Technology   | 1        | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1400MT/s            | 1        | 9.09%   |
| Samsung RAM M378B5273CH0-CK0 4096MB DIMM DDR3 2000MT/s  | 1        | 9.09%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 9.09%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s      | 1        | 9.09%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s     | 1        | 9.09%   |
| HP RAM 7EH65AA# 16384MB DIMM DDR4 2666MT/s              | 1        | 9.09%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1867MT/s    | 1        | 9.09%   |
| G.Skill RAM F3-12800CL9-4GBSR 4GB DIMM DDR3 1600MT/s    | 1        | 9.09%   |
| Crucial RAM CT8G4DFD8213.C16FBR2 8GB DIMM DDR4 2133MT/s | 1        | 9.09%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s   | 1        | 9.09%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3000MT/s             | 1        | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 4        | 50%     |
| DDR3 | 3        | 37.5%   |
| DDR2 | 1        | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 8        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 3        | 37.5%   |
| 16384 | 2        | 25%     |
| 8192  | 2        | 25%     |
| 2048  | 1        | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 2        | 18.18%  |
| 3400  | 1        | 9.09%   |
| 3000  | 1        | 9.09%   |
| 2666  | 1        | 9.09%   |
| 2400  | 1        | 9.09%   |
| 2133  | 1        | 9.09%   |
| 2048  | 1        | 9.09%   |
| 2000  | 1        | 9.09%   |
| 1867  | 1        | 9.09%   |
| 1400  | 1        | 9.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 2        | 40%     |
| Star Micronics     | 1        | 20%     |
| Hewlett-Packard    | 1        | 20%     |
| Canon              | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Star Micronics TUP592 (STR_T-001) | 1        | 20%     |
| HP ENVY 5000 series               | 1        | 20%     |
| Canon PIXMA MX490 Series          | 1        | 20%     |
| Brother MFC-L8900CDW series       | 1        | 20%     |
| Brother HL-5370DW series          | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Microsoft                | 2        | 20%     |
| Logitech                 | 2        | 20%     |
| Z-Star Microelectronics  | 1        | 10%     |
| Novatek Microelectronics | 1        | 10%     |
| Huawei Technologies      | 1        | 10%     |
| Generalplus Technology   | 1        | 10%     |
| Cubeternet               | 1        | 10%     |
| ARC International        | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Z-Star Integrated Camera                 | 1        | 10%     |
| Novatek T2S Webcam                       | 1        | 10%     |
| Microsoft LifeCam VX-5000                | 1        | 10%     |
| Microsoft LifeCam VX-500 [1357]          | 1        | 10%     |
| Logitech Webcam C270                     | 1        | 10%     |
| Logitech QuickCam Communicate MP/S5500   | 1        | 10%     |
| Huawei HiCamera                          | 1        | 10%     |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 10%     |
| Cubeternet GL-UPC822 UVC WebCam          | 1        | 10%     |
| ARC International Camera                 | 1        | 10%     |

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


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Mako Technologies | 1        | 50%     |
| Bit4id            | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Mako Technologies SZZCS-ZCS80 | 1        | 50%     |
| Bit4id miniLector EVO         | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 29       | 80.56%  |
| 1     | 6        | 16.67%  |
| 2     | 1        | 2.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 3        | 37.5%   |
| Net/wireless  | 2        | 25%     |
| Sound         | 1        | 12.5%   |
| Chipcard      | 1        | 12.5%   |
| Bluetooth     | 1        | 12.5%   |

