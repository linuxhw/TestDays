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

Total: 55

| Vendor     | Model                 | Probe                                                      | Date         |
|------------|-----------------------|------------------------------------------------------------|--------------|
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
| Feren OS 20.04   | 18       | 54.55%  |
| Feren OS 18.04   | 13       | 39.39%  |
| Feren OS 2018.10 | 2        | 6.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Feren OS | 32       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.3.0-46-generic           | 4        | 11.11%  |
| 5.11.0-37-generic          | 3        | 8.33%   |
| 5.8.0-53-generic           | 2        | 5.56%   |
| 5.0.0-37-generic           | 2        | 5.56%   |
| 5.8.0-55-generic           | 1        | 2.78%   |
| 5.8.0-48-generic           | 1        | 2.78%   |
| 5.8.0-44-generic           | 1        | 2.78%   |
| 5.8.0-40-generic           | 1        | 2.78%   |
| 5.8.0-36-generic           | 1        | 2.78%   |
| 5.8.0-29-generic           | 1        | 2.78%   |
| 5.4.66-xanmod1             | 1        | 2.78%   |
| 5.4.0-77-generic           | 1        | 2.78%   |
| 5.4.0-74-generic           | 1        | 2.78%   |
| 5.4.0-72-generic           | 1        | 2.78%   |
| 5.4.0-54-generic           | 1        | 2.78%   |
| 5.4.0-52-generic           | 1        | 2.78%   |
| 5.4.0-47-generic           | 1        | 2.78%   |
| 5.4.0-37-generic           | 1        | 2.78%   |
| 5.4.0-31-generic           | 1        | 2.78%   |
| 5.3.0-59-generic           | 1        | 2.78%   |
| 5.3.0-40-generic           | 1        | 2.78%   |
| 5.3.0-28-generic           | 1        | 2.78%   |
| 5.15.0-15.1-liquorix-amd64 | 1        | 2.78%   |
| 5.13.0-37-generic          | 1        | 2.78%   |
| 5.11.0-27-generic          | 1        | 2.78%   |
| 5.11.0-25-generic          | 1        | 2.78%   |
| 4.15.0-48-generic          | 1        | 2.78%   |
| 4.15.0-43-generic          | 1        | 2.78%   |
| 4.15.0-42-generic          | 1        | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.0   | 8        | 24.24%  |
| 5.3.0   | 7        | 21.21%  |
| 5.4.0   | 6        | 18.18%  |
| 5.11.0  | 4        | 12.12%  |
| 4.15.0  | 3        | 9.09%   |
| 5.0.0   | 2        | 6.06%   |
| 5.4.66  | 1        | 3.03%   |
| 5.15.0  | 1        | 3.03%   |
| 5.13.0  | 1        | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8     | 8        | 25%     |
| 5.3     | 7        | 21.88%  |
| 5.4     | 6        | 18.75%  |
| 5.11    | 4        | 12.5%   |
| 4.15    | 3        | 9.38%   |
| 5.0     | 2        | 6.25%   |
| 5.15    | 1        | 3.13%   |
| 5.13    | 1        | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 32       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE        | 20       | 58.82%  |
| KDE5       | 7        | 20.59%  |
| Unknown    | 4        | 11.76%  |
| X-Cinnamon | 2        | 5.88%   |
| GNOME      | 1        | 2.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 32       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 90.63%  |
| TDM     | 2        | 6.25%   |
| LightDM | 1        | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 7        | 21.21%  |
| en_GB   | 6        | 18.18%  |
| en_AU   | 4        | 12.12%  |
| de_DE   | 3        | 9.09%   |
| Unknown | 3        | 9.09%   |
| pt_BR   | 2        | 6.06%   |
| pt_PT   | 1        | 3.03%   |
| nl_BE   | 1        | 3.03%   |
| it_IT   | 1        | 3.03%   |
| es_VE   | 1        | 3.03%   |
| es_PE   | 1        | 3.03%   |
| es_HN   | 1        | 3.03%   |
| en_IE   | 1        | 3.03%   |
| en_CA   | 1        | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 16       | 50%     |
| EFI  | 16       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 27       | 81.82%  |
| Btrfs   | 3        | 9.09%   |
| Unknown | 3        | 9.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 90.91%  |
| GPT     | 3        | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 93.75%  |
| Yes       | 2        | 6.25%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 28.13%  |
| MSI                 | 5        | 15.63%  |
| Gigabyte Technology | 3        | 9.38%   |
| Dell                | 3        | 9.38%   |
| ASRock              | 3        | 9.38%   |
| Pegatron            | 2        | 6.25%   |
| Wortmann AG         | 1        | 3.13%   |
| PCWare              | 1        | 3.13%   |
| Medion              | 1        | 3.13%   |
| Lenovo              | 1        | 3.13%   |
| Hewlett-Packard     | 1        | 3.13%   |
| Foxconn             | 1        | 3.13%   |
| Acer                | 1        | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS PRIME Z370-A               | 2        | 6.25%   |
| ASUS All Series                 | 2        | 6.25%   |
| Wortmann AG TERRA_PC            | 1        | 3.13%   |
| Pegatron p7-1030                | 1        | 3.13%   |
| Pegatron AY691AA-ABA p6367c     | 1        | 3.13%   |
| PCWare IPMH81G1                 | 1        | 3.13%   |
| MSI MS-7C37                     | 1        | 3.13%   |
| MSI MS-7B89                     | 1        | 3.13%   |
| MSI MS-7788                     | 1        | 3.13%   |
| MSI C Series                    | 1        | 3.13%   |
| MSI 700-216                     | 1        | 3.13%   |
| Medion H61H2-LM3                | 1        | 3.13%   |
| Lenovo ThinkCentre M72z 3548B2S | 1        | 3.13%   |
| HP Pavilion Desktop PC 570-p0xx | 1        | 3.13%   |
| Gigabyte GA-78LMT-USB3 R2       | 1        | 3.13%   |
| Gigabyte F2A68HM-DS2            | 1        | 3.13%   |
| Gigabyte EX58-UD5               | 1        | 3.13%   |
| Foxconn Pro3500 Series          | 1        | 3.13%   |
| Dell OptiPlex GX620             | 1        | 3.13%   |
| Dell OptiPlex 780               | 1        | 3.13%   |
| Dell OptiPlex 360               | 1        | 3.13%   |
| ASUS TUF Gaming X570-PLUS       | 1        | 3.13%   |
| ASUS STRIKER II FORMULA         | 1        | 3.13%   |
| ASUS PRIME H410M-E              | 1        | 3.13%   |
| ASUS PRIME B450M-A              | 1        | 3.13%   |
| ASUS PRIME B350-PLUS            | 1        | 3.13%   |
| ASRock Z68 Pro3                 | 1        | 3.13%   |
| ASRock H61M-VS                  | 1        | 3.13%   |
| ASRock B75 Pro3-M               | 1        | 3.13%   |
| Acer Predator G5910             | 1        | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 5        | 15.63%  |
| Dell OptiPlex          | 3        | 9.38%   |
| ASUS All               | 2        | 6.25%   |
| Wortmann AG TERRA      | 1        | 3.13%   |
| Pegatron p7-1030       | 1        | 3.13%   |
| Pegatron AY691AA-ABA   | 1        | 3.13%   |
| PCWare IPMH81G1        | 1        | 3.13%   |
| MSI MS-7C37            | 1        | 3.13%   |
| MSI MS-7B89            | 1        | 3.13%   |
| MSI MS-7788            | 1        | 3.13%   |
| MSI C                  | 1        | 3.13%   |
| MSI 700-216            | 1        | 3.13%   |
| Medion H61H2-LM3       | 1        | 3.13%   |
| Lenovo ThinkCentre     | 1        | 3.13%   |
| HP Pavilion            | 1        | 3.13%   |
| Gigabyte GA-78LMT-USB3 | 1        | 3.13%   |
| Gigabyte F2A68HM-DS2   | 1        | 3.13%   |
| Gigabyte EX58-UD5      | 1        | 3.13%   |
| Foxconn Pro3500        | 1        | 3.13%   |
| ASUS TUF               | 1        | 3.13%   |
| ASUS STRIKER           | 1        | 3.13%   |
| ASRock Z68             | 1        | 3.13%   |
| ASRock H61M-VS         | 1        | 3.13%   |
| ASRock B75             | 1        | 3.13%   |
| Acer Predator          | 1        | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2017 | 5        | 15.63%  |
| 2011 | 5        | 15.63%  |
| 2013 | 4        | 12.5%   |
| 2012 | 4        | 12.5%   |
| 2019 | 3        | 9.38%   |
| 2014 | 3        | 9.38%   |
| 2018 | 2        | 6.25%   |
| 2009 | 2        | 6.25%   |
| 2008 | 2        | 6.25%   |
| 2020 | 1        | 3.13%   |
| 2006 | 1        | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 32       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 32       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 8        | 24.24%  |
| 4.01-8.0    | 7        | 21.21%  |
| 32.01-64.0  | 6        | 18.18%  |
| 3.01-4.0    | 5        | 15.15%  |
| 16.01-24.0  | 4        | 12.12%  |
| 24.01-32.0  | 1        | 3.03%   |
| 64.01-256.0 | 1        | 3.03%   |
| 1.01-2.0    | 1        | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 15       | 44.12%  |
| 2.01-3.0 | 10       | 29.41%  |
| 4.01-8.0 | 4        | 11.76%  |
| 3.01-4.0 | 4        | 11.76%  |
| 0.51-1.0 | 1        | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 41.18%  |
| 3      | 8        | 23.53%  |
| 2      | 8        | 23.53%  |
| 4      | 3        | 8.82%   |
| 5      | 1        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 53.13%  |
| Yes       | 15       | 46.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 32       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 59.38%  |
| Yes       | 13       | 40.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 75.76%  |
| Yes       | 8        | 24.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 21.88%  |
| Australia   | 5        | 15.63%  |
| Germany     | 4        | 12.5%   |
| UK          | 2        | 6.25%   |
| Brazil      | 2        | 6.25%   |
| Venezuela   | 1        | 3.13%   |
| Switzerland | 1        | 3.13%   |
| Portugal    | 1        | 3.13%   |
| Peru        | 1        | 3.13%   |
| Norway      | 1        | 3.13%   |
| Jordan      | 1        | 3.13%   |
| Italy       | 1        | 3.13%   |
| Ireland     | 1        | 3.13%   |
| Honduras    | 1        | 3.13%   |
| Canada      | 1        | 3.13%   |
| Belgium     | 1        | 3.13%   |
| Argentina   | 1        | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Richmond       | 2        | 5.88%   |
| Melbourne      | 2        | 5.88%   |
| Tegucigalpa    | 1        | 2.94%   |
| Stavanger      | 1        | 2.94%   |
| Sligo          | 1        | 2.94%   |
| Seattle        | 1        | 2.94%   |
| Schleusingen   | 1        | 2.94%   |
| Sao Jose       | 1        | 2.94%   |
| Sankt Augustin | 1        | 2.94%   |
| Recklinghausen | 1        | 2.94%   |
| Oudenaarde     | 1        | 2.94%   |
| Oberwil-Lieli  | 1        | 2.94%   |
| New York       | 1        | 2.94%   |
| Naples         | 1        | 2.94%   |
| Macaé         | 1        | 2.94%   |
| Los Angeles    | 1        | 2.94%   |
| Lima           | 1        | 2.94%   |
| Hummeltal      | 1        | 2.94%   |
| Hobart         | 1        | 2.94%   |
| Glasgow        | 1        | 2.94%   |
| Funchal        | 1        | 2.94%   |
| Fort St. John  | 1        | 2.94%   |
| Edinburg       | 1        | 2.94%   |
| Caracas        | 1        | 2.94%   |
| Buenos Aires   | 1        | 2.94%   |
| Bridgwater     | 1        | 2.94%   |
| Bellport       | 1        | 2.94%   |
| Bellflower     | 1        | 2.94%   |
| Barletta       | 1        | 2.94%   |
| Barinas        | 1        | 2.94%   |
| Bakersfield    | 1        | 2.94%   |
| Amman          | 1        | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 16       | 25     | 30.77%  |
| Seagate                   | 12       | 18     | 23.08%  |
| Samsung Electronics       | 5        | 8      | 9.62%   |
| Kingston                  | 4        | 10     | 7.69%   |
| Hitachi                   | 4        | 5      | 7.69%   |
| Toshiba                   | 3        | 3      | 5.77%   |
| Verbatim                  | 1        | 1      | 1.92%   |
| Unknown                   | 1        | 1      | 1.92%   |
| Sandisk                   | 1        | 2      | 1.92%   |
| Realtek Semiconductor     | 1        | 1      | 1.92%   |
| PNY                       | 1        | 1      | 1.92%   |
| Micron/Crucial Technology | 1        | 1      | 1.92%   |
| Intel                     | 1        | 1      | 1.92%   |
| Crucial                   | 1        | 1      | 1.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST4000LM016-1N2170 4TB     | 2        | 3.45%   |
| Samsung HD103SJ 1TB                | 2        | 3.45%   |
| Kingston SA400S37480G 480GB SSD    | 2        | 3.45%   |
| Hitachi HDS721010CLA332 1TB        | 2        | 3.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 1.72%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 1        | 1.72%   |
| WDC WD80EFBX-68AZZN0 8TB           | 1        | 1.72%   |
| WDC WD6400AAKS-00A7B2 640GB        | 1        | 1.72%   |
| WDC WD5000BPKT-60PK4T0 500GB       | 1        | 1.72%   |
| WDC WD5000AAVS-00G9B1 500GB        | 1        | 1.72%   |
| WDC WD5000AAKS-65A7B2 500GB        | 1        | 1.72%   |
| WDC WD5000AAKS-00A7B2 500GB        | 1        | 1.72%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1        | 1.72%   |
| WDC WD30EZRX-00D8PB0 3TB           | 1        | 1.72%   |
| WDC WD2500AAKX-75U6AA0 250GB       | 1        | 1.72%   |
| WDC WD1600AAJS-00L7A0 160GB        | 1        | 1.72%   |
| WDC WD10PURX-78E5EY0 1TB           | 1        | 1.72%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1        | 1.72%   |
| WDC WD10EZEX-60WN4A0 1TB           | 1        | 1.72%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1        | 1.72%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 1.72%   |
| WDC WD10EZEX-00WN4A0 1TB           | 1        | 1.72%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 1.72%   |
| WDC WD10EURX-83UY4Y0 1TB           | 1        | 1.72%   |
| Verbatim Vi550 S3 SSD 256GB        | 1        | 1.72%   |
| Unknown SD/MMC/MS PRO 999GB        | 1        | 1.72%   |
| Toshiba THNSNJ256GCST 256GB SSD    | 1        | 1.72%   |
| Toshiba MK3275GSX 320GB            | 1        | 1.72%   |
| Toshiba DT01ACA100 1TB             | 1        | 1.72%   |
| Seagate ST500DM005 HD502HJ 500GB   | 1        | 1.72%   |
| Seagate ST3500630NS 500GB          | 1        | 1.72%   |
| Seagate ST3500418AS 500GB          | 1        | 1.72%   |
| Seagate ST3320418AS 320GB          | 1        | 1.72%   |
| Seagate ST31000528AS 1TB           | 1        | 1.72%   |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 1.72%   |
| Seagate ST2000DM001-9YN164 2TB     | 1        | 1.72%   |
| Seagate ST2000DM001-1CH164 2TB     | 1        | 1.72%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1.72%   |
| Seagate ST1000DM003-9YN162 1TB     | 1        | 1.72%   |
| Sandisk NVMe SSD Drive 1TB         | 1        | 1.72%   |
| Samsung SSD 970 EVO 500GB          | 1        | 1.72%   |
| Samsung SSD 860 QVO 1TB            | 1        | 1.72%   |
| Samsung SSD 840 EVO 500GB          | 1        | 1.72%   |
| Samsung SSD 840 EVO 250GB          | 1        | 1.72%   |
| Realtek NVMe SSD Drive 512GB       | 1        | 1.72%   |
| PNY SSD2SC120G3LC709B104-495 120GB | 1        | 1.72%   |
| Micron/Crucial NVMe SSD Drive 1TB  | 1        | 1.72%   |
| Kingston SV300S37A240G 240GB SSD   | 1        | 1.72%   |
| Kingston SA400S37960G 960GB SSD    | 1        | 1.72%   |
| Kingston SA400S37120G 120GB SSD    | 1        | 1.72%   |
| Intel SSDSC2BW180A3L 180GB         | 1        | 1.72%   |
| Hitachi HUA723020ALA640 2TB        | 1        | 1.72%   |
| Hitachi HDT721010SLA360 1TB        | 1        | 1.72%   |
| Crucial CT120BX500SSD1 120GB       | 1        | 1.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 23     | 41.67%  |
| Seagate             | 12       | 18     | 33.33%  |
| Hitachi             | 4        | 5      | 11.11%  |
| Toshiba             | 2        | 2      | 5.56%   |
| Samsung Electronics | 2        | 3      | 5.56%   |
| Unknown             | 1        | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 4        | 10     | 28.57%  |
| Samsung Electronics | 3        | 4      | 21.43%  |
| WDC                 | 2        | 2      | 14.29%  |
| Verbatim            | 1        | 1      | 7.14%   |
| Toshiba             | 1        | 1      | 7.14%   |
| PNY                 | 1        | 1      | 7.14%   |
| Intel               | 1        | 1      | 7.14%   |
| Crucial             | 1        | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 30       | 52     | 63.83%  |
| SSD  | 13       | 21     | 27.66%  |
| NVMe | 4        | 5      | 8.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 32       | 72     | 86.49%  |
| NVMe | 4        | 5      | 10.81%  |
| SAS  | 1        | 1      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 19       | 31     | 42.22%  |
| 0.51-1.0   | 17       | 28     | 37.78%  |
| 1.01-2.0   | 4        | 5      | 8.89%   |
| 3.01-4.0   | 2        | 6      | 4.44%   |
| 2.01-3.0   | 2        | 2      | 4.44%   |
| 4.01-10.0  | 1        | 1      | 2.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 11       | 31.43%  |
| 251-500        | 7        | 20%     |
| 501-1000       | 7        | 20%     |
| More than 3000 | 4        | 11.43%  |
| 2001-3000      | 3        | 8.57%   |
| 101-250        | 3        | 8.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 251-500   | 9        | 25.71%  |
| 1-20      | 7        | 20%     |
| 21-50     | 5        | 14.29%  |
| 101-250   | 5        | 14.29%  |
| 501-1000  | 5        | 14.29%  |
| 51-100    | 3        | 8.57%   |
| 1001-2000 | 1        | 2.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD5000AAVS-00G9B1 500GB | 1        | 1      | 50%     |
| Seagate ST3500418AS 500GB   | 1        | 1      | 50%     |

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
| HDD  | 1        | 2      | 100%    |

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
| Detected | 30       | 69     | 88.24%  |
| Works    | 3        | 7      | 8.82%   |
| Malfunc  | 1        | 2      | 2.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 22       | 53.66%  |
| AMD                       | 9        | 21.95%  |
| Samsung Electronics       | 3        | 7.32%   |
| ASMedia Technology        | 2        | 4.88%   |
| Sandisk                   | 1        | 2.44%   |
| Realtek Semiconductor     | 1        | 2.44%   |
| Nvidia                    | 1        | 2.44%   |
| Micron/Crucial Technology | 1        | 2.44%   |
| JMicron Technology        | 1        | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 10.71%  |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 7.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 5.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 5.36%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 3.57%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 3.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 3.57%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 3.57%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 3.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 3.57%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 3.57%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 1.79%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 1.79%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 1.79%   |
| Nvidia MCP55 IDE                                                                        | 1        | 1.79%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 1.79%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.79%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.79%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 1.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.79%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.79%   |
| AMD RS690 PCI to PCI Bridge (PCI Express Port 2)                                        | 1        | 1.79%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.79%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 22       | 53.66%  |
| IDE  | 12       | 29.27%  |
| NVMe | 6        | 14.63%  |
| RAID | 1        | 2.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 23       | 71.88%  |
| AMD    | 9        | 28.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 6.25%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 2        | 6.25%   |
| Intel Pentium D CPU 3.00GHz                    | 1        | 3.13%   |
| Intel Pentium CPU G630 @ 2.70GHz               | 1        | 3.13%   |
| Intel Pentium CPU G3250 @ 3.20GHz              | 1        | 3.13%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 1        | 3.13%   |
| Intel Core i7-3770S CPU @ 3.10GHz              | 1        | 3.13%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1        | 3.13%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 3.13%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 3.13%   |
| Intel Core i7 CPU 920 @ 2.67GHz                | 1        | 3.13%   |
| Intel Core i5-9400F CPU @ 2.90GHz              | 1        | 3.13%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1        | 3.13%   |
| Intel Core i5-3330 CPU @ 3.00GHz               | 1        | 3.13%   |
| Intel Core i3-3240 CPU @ 3.40GHz               | 1        | 3.13%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz          | 1        | 3.13%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1        | 3.13%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 3.13%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz           | 1        | 3.13%   |
| Intel Celeron CPU G1840 @ 2.80GHz              | 1        | 3.13%   |
| Intel Celeron CPU 1007U @ 1.50GHz              | 1        | 3.13%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 3.13%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 3.13%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 3.13%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 1        | 3.13%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 1        | 3.13%   |
| AMD FX-8350 Eight-Core Processor               | 1        | 3.13%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G  | 1        | 3.13%   |
| AMD A8-7650K Radeon R7, 10 Compute Cores 4C+6G | 1        | 3.13%   |
| AMD A10-6700 APU with Radeon HD Graphics       | 1        | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i7     | 8        | 25%     |
| Intel Core i5     | 3        | 9.38%   |
| Intel Core i3     | 3        | 9.38%   |
| Intel Core 2 Quad | 3        | 9.38%   |
| Intel Pentium     | 2        | 6.25%   |
| Intel Celeron     | 2        | 6.25%   |
| AMD Ryzen 7       | 2        | 6.25%   |
| AMD Ryzen 5       | 2        | 6.25%   |
| AMD A8            | 2        | 6.25%   |
| Intel Pentium D   | 1        | 3.13%   |
| Intel Core 2 Duo  | 1        | 3.13%   |
| AMD Ryzen 9       | 1        | 3.13%   |
| AMD FX            | 1        | 3.13%   |
| AMD A10           | 1        | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 12       | 37.5%   |
| 2      | 12       | 37.5%   |
| 6      | 4        | 12.5%   |
| 8      | 3        | 9.38%   |
| 12     | 1        | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 62.5%   |
| 1      | 12       | 37.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 29       | 90.63%  |
| Unknown        | 3        | 9.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 5        | 15.63%  |
| 0x206a7    | 4        | 12.5%   |
| 0x906ea    | 3        | 9.38%   |
| 0x306c3    | 3        | 9.38%   |
| 0x1067a    | 3        | 9.38%   |
| 0x0800820d | 2        | 6.25%   |
| 0xf62      | 1        | 3.13%   |
| 0xa0655    | 1        | 3.13%   |
| 0x6fb      | 1        | 3.13%   |
| 0x106a5    | 1        | 3.13%   |
| 0x08701021 | 1        | 3.13%   |
| 0x0810100b | 1        | 3.13%   |
| 0x08001138 | 1        | 3.13%   |
| 0x0600611a | 1        | 3.13%   |
| 0x06003104 | 1        | 3.13%   |
| 0x06001119 | 1        | 3.13%   |
| 0x06000852 | 1        | 3.13%   |
| Unknown    | 1        | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 5        | 15.63%  |
| IvyBridge   | 5        | 15.63%  |
| Penryn      | 3        | 9.38%   |
| KabyLake    | 3        | 9.38%   |
| Haswell     | 3        | 9.38%   |
| Zen+        | 2        | 6.25%   |
| Zen         | 2        | 6.25%   |
| Piledriver  | 2        | 6.25%   |
| Zen 2       | 1        | 3.13%   |
| Steamroller | 1        | 3.13%   |
| NetBurst    | 1        | 3.13%   |
| Nehalem     | 1        | 3.13%   |
| Excavator   | 1        | 3.13%   |
| Core        | 1        | 3.13%   |
| CometLake   | 1        | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 41.18%  |
| Nvidia | 12       | 35.29%  |
| AMD    | 8        | 23.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 5.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 5.88%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 5.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 5.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 5.88%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.94%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.94%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 2.94%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 2.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 2.94%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 2.94%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 2.94%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 2.94%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 2.94%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 2.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.94%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 2.94%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.94%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 2.94%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 1        | 2.94%   |
| AMD Richland [Radeon HD 8670D]                                              | 1        | 2.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.94%   |
| AMD Navi 14 [Radeon Pro W5500]                                              | 1        | 2.94%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 2.94%   |
| AMD Barts XT [Radeon HD 6870]                                               | 1        | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 12       | 37.5%   |
| 1 x Nvidia     | 11       | 34.38%  |
| 1 x AMD        | 8        | 25%     |
| Intel + Nvidia | 1        | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 22       | 64.71%  |
| Proprietary | 10       | 29.41%  |
| Unknown     | 2        | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 39.39%  |
| 0.51-1.0   | 6        | 18.18%  |
| 1.01-2.0   | 5        | 15.15%  |
| 7.01-8.0   | 4        | 12.12%  |
| 3.01-4.0   | 2        | 6.06%   |
| 0.01-0.5   | 2        | 6.06%   |
| 5.01-6.0   | 1        | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 5        | 16.13%  |
| Acer                    | 4        | 12.9%   |
| Lenovo                  | 3        | 9.68%   |
| Dell                    | 3        | 9.68%   |
| Hewlett-Packard         | 2        | 6.45%   |
| AOC                     | 2        | 6.45%   |
| Vestel                  | 1        | 3.23%   |
| Unknown                 | 1        | 3.23%   |
| Sceptre Tech            | 1        | 3.23%   |
| Philips                 | 1        | 3.23%   |
| Onkyo                   | 1        | 3.23%   |
| Medion                  | 1        | 3.23%   |
| LG Electronics          | 1        | 3.23%   |
| Lenovo Group Limited    | 1        | 3.23%   |
| Insignia                | 1        | 3.23%   |
| Goldstar                | 1        | 3.23%   |
| Chi Mei Optoelectronics | 1        | 3.23%   |
| Ancor Communications    | 1        | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vestel LCD Monitor 32W_LCD_TV 1920x1080                               | 1        | 2.94%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 2.94%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch        | 1        | 2.94%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch     | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 890x500mm 40.2-inch | 1        | 2.94%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 1        | 2.94%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 2.94%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch     | 1        | 2.94%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 2.94%   |
| Philips PHL 328E9Q PHLC180 1920x1080 698x393mm 31.5-inch              | 1        | 2.94%   |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                  | 1        | 2.94%   |
| Medion MD 20094 MED3610 1920x1200 550x344mm 25.5-inch                 | 1        | 2.94%   |
| LG Electronics LCD Monitor MP59HT 1920x1080                           | 1        | 2.94%   |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                 | 1        | 2.94%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                  | 1        | 2.94%   |
| Lenovo H61 LEN520B 1600x900 410x230mm 18.5-inch                       | 1        | 2.94%   |
| Lenovo Group Limited LCD Monitor L24q-10 2560x1440                    | 1        | 2.94%   |
| Insignia NS-24EM51A14 BBYBB24 1920x1080 531x299mm 24.0-inch           | 1        | 2.94%   |
| Hewlett-Packard ZR22w HWP2867 1920x1080 475x267mm 21.5-inch           | 1        | 2.94%   |
| Hewlett-Packard LCD Monitor ZR22w 3840x1080                           | 1        | 2.94%   |
| Hewlett-Packard 2509 HWP283A 1920x1080 553x311mm 25.0-inch            | 1        | 2.94%   |
| Goldstar E2242 GSM58BE 1920x1080 480x270mm 21.7-inch                  | 1        | 2.94%   |
| Dell UP3017 DEL40FA 2560x1600 641x401mm 29.8-inch                     | 1        | 2.94%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1        | 2.94%   |
| Dell SP1908FP DEL4030 1280x1024 376x301mm 19.0-inch                   | 1        | 2.94%   |
| Chi Mei Optoelectronics LCD Monitor CMC 19AW 1440x900                 | 1        | 2.94%   |
| AOC LM522 AOCA522 1024x768 304x228mm 15.0-inch                        | 1        | 2.94%   |
| AOC LCD Monitor 1943W 1366x768                                        | 1        | 2.94%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 1        | 2.94%   |
| Acer VG270U ACR06C9 2560x1440 597x336mm 27.0-inch                     | 1        | 2.94%   |
| Acer V273HL ACR02D0 1920x1080 598x336mm 27.0-inch                     | 1        | 2.94%   |
| Acer S242HL ACR0216 1920x1080 531x299mm 24.0-inch                     | 1        | 2.94%   |
| Acer LCD Monitor VG270U 2560x1440                                     | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 14       | 46.67%  |
| 2560x1440 (QHD)   | 3        | 10%     |
| 3840x2160 (4K)    | 2        | 6.67%   |
| 1366x768 (WXGA)   | 2        | 6.67%   |
| 1280x1024 (SXGA)  | 2        | 6.67%   |
| 3840x1080         | 1        | 3.33%   |
| 2560x1600         | 1        | 3.33%   |
| 1920x1200 (WUXGA) | 1        | 3.33%   |
| 1600x900 (HD+)    | 1        | 3.33%   |
| 1440x900 (WXGA+)  | 1        | 3.33%   |
| 1024x768 (XGA)    | 1        | 3.33%   |
| Unknown           | 1        | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 22.58%  |
| 27      | 5        | 16.13%  |
| 24      | 4        | 12.9%   |
| 31      | 2        | 6.45%   |
| 25      | 2        | 6.45%   |
| 21      | 2        | 6.45%   |
| 54      | 1        | 3.23%   |
| 49      | 1        | 3.23%   |
| 32      | 1        | 3.23%   |
| 29      | 1        | 3.23%   |
| 23      | 1        | 3.23%   |
| 19      | 1        | 3.23%   |
| 18      | 1        | 3.23%   |
| 17      | 1        | 3.23%   |
| 15      | 1        | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 12       | 38.71%  |
| Unknown     | 7        | 22.58%  |
| 601-700     | 3        | 9.68%   |
| 401-500     | 3        | 9.68%   |
| 301-350     | 2        | 6.45%   |
| 1001-1500   | 2        | 6.45%   |
| 701-800     | 1        | 3.23%   |
| 351-400     | 1        | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 17       | 56.67%  |
| Unknown | 7        | 23.33%  |
| 16/10   | 3        | 10%     |
| 5/4     | 2        | 6.67%   |
| 4/3     | 1        | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 7        | 22.58%  |
| 201-250        | 6        | 19.35%  |
| 301-350        | 5        | 16.13%  |
| 351-500        | 4        | 12.9%   |
| 251-300        | 3        | 9.68%   |
| More than 1000 | 2        | 6.45%   |
| 141-150        | 2        | 6.45%   |
| 151-200        | 1        | 3.23%   |
| 101-110        | 1        | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 51.61%  |
| Unknown | 7        | 22.58%  |
| 101-120 | 4        | 12.9%   |
| 1-50    | 2        | 6.45%   |
| 121-160 | 2        | 6.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 81.82%  |
| 2     | 4        | 12.12%  |
| 0     | 2        | 6.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 22       | 51.16%  |
| Intel                           | 6        | 13.95%  |
| Ralink                          | 2        | 4.65%   |
| Qualcomm Atheros                | 2        | 4.65%   |
| Linksys                         | 2        | 4.65%   |
| Broadcom                        | 2        | 4.65%   |
| TP-Link                         | 1        | 2.33%   |
| Ralink Technology               | 1        | 2.33%   |
| Qualcomm Atheros Communications | 1        | 2.33%   |
| Nvidia                          | 1        | 2.33%   |
| NetGear                         | 1        | 2.33%   |
| Edimax Technology               | 1        | 2.33%   |
| D-Link                          | 1        | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                        | Desktops | Percent |
|------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller            | 21       | 43.75%  |
| Intel Ethernet Connection (2) I219-V                                         | 2        | 4.17%   |
| TP-Link 802.11ac WLAN Adapter                                                | 1        | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                     | 1        | 2.08%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                       | 1        | 2.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                   | 1        | 2.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                        | 1        | 2.08%   |
| Ralink RT2501/RT2573 Wireless Adapter                                        | 1        | 2.08%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                    | 1        | 2.08%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                         | 1        | 2.08%   |
| Qualcomm Atheros AR9271 802.11n                                              | 1        | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                             | 1        | 2.08%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                     | 1        | 2.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                   | 1        | 2.08%   |
| Nvidia MCP55 Ethernet                                                        | 1        | 2.08%   |
| NetGear A6210                                                                | 1        | 2.08%   |
| Linksys WUSB6300 V2                                                          | 1        | 2.08%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]       | 1        | 2.08%   |
| Intel Ethernet Connection (7) I219-V                                         | 1        | 2.08%   |
| Intel Centrino Wireless-N 2230                                               | 1        | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                              | 1        | 2.08%   |
| Intel 82579V Gigabit Network Connection                                      | 1        | 2.08%   |
| Intel 82567LM-3 Gigabit Network Connection                                   | 1        | 2.08%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                     | 1        | 2.08%   |
| D-Link DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.B2) [Ralink RT5572] | 1        | 2.08%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                      | 1        | 2.08%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                              | 1        | 2.08%   |

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
| TP-Link 802.11ac WLAN Adapter                                                | 1        | 6.25%   |
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
| Realtek Semiconductor | 22       | 68.75%  |
| Intel                 | 5        | 15.63%  |
| Qualcomm Atheros      | 2        | 6.25%   |
| Broadcom              | 2        | 6.25%   |
| Nvidia                | 1        | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 65.63%  |
| Intel Ethernet Connection (2) I219-V                              | 2        | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 3.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 3.13%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 3.13%   |
| Nvidia MCP55 Ethernet                                             | 1        | 3.13%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 3.13%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 3.13%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 3.13%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 3.13%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 71.11%  |
| WiFi     | 13       | 28.89%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 75.76%  |
| WiFi     | 8        | 24.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 75%     |
| 2     | 8        | 25%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 87.5%   |
| Yes  | 4        | 12.5%   |

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
| Intel               | 22       | 44%     |
| Nvidia              | 12       | 24%     |
| AMD                 | 11       | 22%     |
| C-Media Electronics | 2        | 4%      |
| Razer USA           | 1        | 2%      |
| Logitech            | 1        | 2%      |
| Creative Labs       | 1        | 2%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 14.04%  |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 5.26%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 5.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 5.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 5.26%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 3.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 3.51%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 3.51%   |
| AMD FCH Azalia Controller                                                  | 2        | 3.51%   |
| Razer USA Nommo Chroma                                                     | 1        | 1.75%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.75%   |
| Nvidia MCP55 High Definition Audio                                         | 1        | 1.75%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.75%   |
| Logitech Headset H390                                                      | 1        | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.75%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.75%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.75%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1        | 1.75%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1.75%   |
| C-Media Electronics TONOR TC30 Audio Device                                | 1        | 1.75%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.75%   |
| C-Media Electronics Audio Adapter                                          | 1        | 1.75%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 1.75%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.75%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1        | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.75%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 1.75%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 1.75%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 1.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.75%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 1        | 1.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 1        | 14.29%  |
| Samsung Electronics | 1        | 14.29%  |
| Nanya Technology    | 1        | 14.29%  |
| Kingston            | 1        | 14.29%  |
| Hewlett-Packard     | 1        | 14.29%  |
| Crucial             | 1        | 14.29%  |
| A-DATA Technology   | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1400MT/s            | 1        | 12.5%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s     | 1        | 12.5%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 12.5%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s   | 1        | 12.5%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s  | 1        | 12.5%   |
| HP RAM 7EH65AA# 16384MB DIMM DDR4 2666MT/s              | 1        | 12.5%   |
| Crucial RAM CT8G4DFD8213.C16FBR2 8GB DIMM DDR4 2133MT/s | 1        | 12.5%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3000MT/s             | 1        | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 3        | 50%     |
| DDR3 | 2        | 33.33%  |
| DDR2 | 1        | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 6        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 2        | 33.33%  |
| 4096  | 2        | 33.33%  |
| 8192  | 1        | 16.67%  |
| 2048  | 1        | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3000  | 1        | 12.5%   |
| 2666  | 1        | 12.5%   |
| 2400  | 1        | 12.5%   |
| 2133  | 1        | 12.5%   |
| 2048  | 1        | 12.5%   |
| 2000  | 1        | 12.5%   |
| 1600  | 1        | 12.5%   |
| 1400  | 1        | 12.5%   |

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


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Z-Star Integrated Camera               | 1        | 10%     |
| Novatek J1455                          | 1        | 10%     |
| Microsoft LifeCam VX-5000              | 1        | 10%     |
| Microsoft LifeCam VX-500 [1357]        | 1        | 10%     |
| Logitech Webcam C270                   | 1        | 10%     |
| Logitech QuickCam Communicate MP/S5500 | 1        | 10%     |
| Huawei UVC Camera                      | 1        | 10%     |
| Generalplus 808 Camera                 | 1        | 10%     |
| Cubeternet GL-UPC822 UVC WebCam        | 1        | 10%     |
| ARC International Camera               | 1        | 10%     |

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
| BIT4ID            | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Mako Technologies SZZCS-ZCS80 | 1        | 50%     |
| BIT4ID miniLector EVO         | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 26       | 78.79%  |
| 1     | 6        | 18.18%  |
| 2     | 1        | 3.03%   |

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

