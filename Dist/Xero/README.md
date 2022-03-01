Xero - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xero/Desktop/README.md) and [notebooks](/Dist/Xero/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad T460 20FMS1XX00    | Notebook    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell     | Latitude E6430              | Notebook    | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | Notebook    | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | Notebook    | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo   | Legion Y740-15IRHg 81UH     | Notebook    | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| ASUSTek  | P5Q PRO TURBO               | Desktop     | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| Acer     | Aspire A315-58G             | Notebook    | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell     | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| Lenovo   | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| HP       | Laptop 15s-eq0xxx           | Notebook    | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| ASUSTek  | TUF GAMING B550M-PLUS       | Desktop     | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| Lenovo   | Legion Y540-15IRH-PG0 81... | Notebook    | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| HP       | 1906                        | Desktop     | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek  | TUF GAMING X570-PLUS        | Desktop     | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP       | 2179                        | All in one  | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek  | TUF B360M-PLUS GAMING/BR    | Desktop     | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| Dell     | Vostro 3590                 | Notebook    | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| HP       | 2179                        | All in one  | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASUSTek  | ASUS EXPERTBOOK B9400CEA... | Notebook    | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP       | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek  | X510UNR                     | Notebook    | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek  | ASUS EXPERTBOOK B9400CEA... | Notebook    | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [3e4f21099d](https://linux-hardware.org/?probe=3e4f21099d) | Dec 17, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron | D15K                        | Notebook    | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| ASUSTek  | TUF GAMING X570-PLUS        | Desktop     | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek  | PRIME A320M-K               | Desktop     | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| MSI      | GP73 Leopard 8RD            | Notebook    | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer     | Aspire A315-58G             | Notebook    | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer     | Aspire A315-58G             | Notebook    | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo   | ThinkPad W530 24384CU       | Notebook    | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| ASUSTek  | TUF Z390-PLUS GAMING        | Desktop     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI      | Z370 GAMING PLUS            | Desktop     | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Acer     | Aspire A315-58G             | Notebook    | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP       | ENVY Sleekbook 4            | Notebook    | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | Notebook    | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek  | VivoBook_ASUS Laptop E41... | Notebook    | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo   | IdeaPad 5 15ITL05 82FG      | Notebook    | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Dell     | 0XC7MM A01                  | Desktop     | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| Lenovo   | Y520-15IKBN 80WK            | Notebook    | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |
| ASRock   | B450M Pro4                  | Desktop     | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [203afc45fd](https://linux-hardware.org/?probe=203afc45fd) | Aug 29, 2021 |
| Gigabyte | X570 AORUS MASTER           | Desktop     | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer     | FIH57                       | Desktop     | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.16.2-arch1-1               | 3         | 7.14%   |
| 5.16.1-arch1-1               | 3         | 7.14%   |
| 5.14.14-arch1-1              | 3         | 7.14%   |
| 5.16.8-arch1-1               | 2         | 4.76%   |
| 5.14.8-zen1-1-zen            | 2         | 4.76%   |
| 5.16.10-arch1-1              | 1         | 2.38%   |
| 5.15.9-AMD                   | 1         | 2.38%   |
| 5.15.8-zen1-1-zen            | 1         | 2.38%   |
| 5.15.4-arch1-1               | 1         | 2.38%   |
| 5.15.3-zen1-1-zen            | 1         | 2.38%   |
| 5.15.13-arch1-1              | 1         | 2.38%   |
| 5.15.13-AMD                  | 1         | 2.38%   |
| 5.15.12-zen1-1-zen           | 1         | 2.38%   |
| 5.15.12-arch1-1-surface      | 1         | 2.38%   |
| 5.15.12-arch1-1              | 1         | 2.38%   |
| 5.15.11-arch2-1-surface      | 1         | 2.38%   |
| 5.15.11-arch2-1              | 1         | 2.38%   |
| 5.15.10-arch1-1              | 1         | 2.38%   |
| 5.14.9-zen2-1-zen            | 1         | 2.38%   |
| 5.14.8-arch1-1               | 1         | 2.38%   |
| 5.14.16-zen1-1-zen           | 1         | 2.38%   |
| 5.14.16-arch1-2-surface      | 1         | 2.38%   |
| 5.14.16-arch1-1              | 1         | 2.38%   |
| 5.14.15-zen1-1-zen           | 1         | 2.38%   |
| 5.14.14-zen1-1-zen           | 1         | 2.38%   |
| 5.14.12-arch1-1              | 1         | 2.38%   |
| 5.14.11-hardened1-1-hardened | 1         | 2.38%   |
| 5.13.4-zen1-1-zen            | 1         | 2.38%   |
| 5.13.13-AMD                  | 1         | 2.38%   |
| 5.12.5-AMD                   | 1         | 2.38%   |
| 5.11.16-zen1-1-zen           | 1         | 2.38%   |
| 5.10.88-1-lts                | 1         | 2.38%   |
| 5.10.80-1-lts                | 1         | 2.38%   |
| 5.10.71-1-lts                | 1         | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.14 | 4         | 9.52%   |
| 5.16.2  | 3         | 7.14%   |
| 5.16.1  | 3         | 7.14%   |
| 5.15.12 | 3         | 7.14%   |
| 5.14.8  | 3         | 7.14%   |
| 5.14.16 | 3         | 7.14%   |
| 5.16.8  | 2         | 4.76%   |
| 5.15.13 | 2         | 4.76%   |
| 5.15.11 | 2         | 4.76%   |
| 5.16.10 | 1         | 2.38%   |
| 5.15.9  | 1         | 2.38%   |
| 5.15.8  | 1         | 2.38%   |
| 5.15.4  | 1         | 2.38%   |
| 5.15.3  | 1         | 2.38%   |
| 5.15.10 | 1         | 2.38%   |
| 5.14.9  | 1         | 2.38%   |
| 5.14.15 | 1         | 2.38%   |
| 5.14.12 | 1         | 2.38%   |
| 5.14.11 | 1         | 2.38%   |
| 5.13.4  | 1         | 2.38%   |
| 5.13.13 | 1         | 2.38%   |
| 5.12.5  | 1         | 2.38%   |
| 5.11.16 | 1         | 2.38%   |
| 5.10.88 | 1         | 2.38%   |
| 5.10.80 | 1         | 2.38%   |
| 5.10.71 | 1         | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 13        | 32.5%   |
| 5.15    | 11        | 27.5%   |
| 5.16    | 9         | 22.5%   |
| 5.10    | 3         | 7.5%    |
| 5.13    | 2         | 5%      |
| 5.12    | 1         | 2.5%    |
| 5.11    | 1         | 2.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 36        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| KDE5  | 33        | 86.84%  |
| XFCE  | 3         | 7.89%   |
| GNOME | 2         | 5.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 30        | 83.33%  |
| Wayland | 4         | 11.11%  |
| Tty     | 2         | 5.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 21        | 52.5%   |
| LightDM | 12        | 30%     |
| Unknown | 5         | 12.5%   |
| TDM     | 1         | 2.5%    |
| GDM     | 1         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 19        | 51.35%  |
| en_IN | 5         | 13.51%  |
| pl_PL | 3         | 8.11%   |
| C     | 3         | 8.11%   |
| en_AU | 2         | 5.41%   |
| it_IT | 1         | 2.7%    |
| en_IL | 1         | 2.7%    |
| en_GB | 1         | 2.7%    |
| en_CA | 1         | 2.7%    |
| de_AT | 1         | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 25        | 67.57%  |
| BIOS | 12        | 32.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 29        | 76.32%  |
| Ext4    | 6         | 15.79%  |
| Overlay | 3         | 7.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 26        | 70.27%  |
| MBR     | 6         | 16.22%  |
| Unknown | 5         | 13.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 86.84%  |
| Yes       | 5         | 13.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 61.11%  |
| Yes       | 14        | 38.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 11        | 30.56%  |
| Lenovo              | 8         | 22.22%  |
| Hewlett-Packard     | 5         | 13.89%  |
| Dell                | 4         | 11.11%  |
| MSI                 | 2         | 5.56%   |
| ASRock              | 2         | 5.56%   |
| Acer                | 2         | 5.56%   |
| Pegatron            | 1         | 2.78%   |
| Gigabyte Technology | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Pegatron D15K                            | 1         | 2.78%   |
| MSI MS-7B61                              | 1         | 2.78%   |
| MSI GP73 Leopard 8RD                     | 1         | 2.78%   |
| Lenovo Yoga 710-15IKB 80V5               | 1         | 2.78%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 2.78%   |
| Lenovo ThinkPad W530 24384CU             | 1         | 2.78%   |
| Lenovo ThinkPad T460 20FMS1XX00          | 1         | 2.78%   |
| Lenovo Legion Y740-15IRHg 81UH           | 1         | 2.78%   |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 1         | 2.78%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 2.78%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 1         | 2.78%   |
| HP Z230 SFF Workstation                  | 1         | 2.78%   |
| HP ProOne 400 G1 AiO                     | 1         | 2.78%   |
| HP Notebook                              | 1         | 2.78%   |
| HP Laptop 15s-eq0xxx                     | 1         | 2.78%   |
| HP ENVY Sleekbook 4                      | 1         | 2.78%   |
| Gigabyte X570 AORUS MASTER               | 1         | 2.78%   |
| Dell Vostro 3590                         | 1         | 2.78%   |
| Dell Precision T1500                     | 1         | 2.78%   |
| Dell Latitude E6520                      | 1         | 2.78%   |
| Dell Latitude E6430                      | 1         | 2.78%   |
| ASUS X510UNR                             | 1         | 2.78%   |
| ASUS VivoBook_ASUSLaptop X509FJ_X509FJ   | 1         | 2.78%   |
| ASUS VivoBook_ASUS Laptop E410MA_E410MA  | 1         | 2.78%   |
| ASUS TUF Z390-PLUS GAMING                | 1         | 2.78%   |
| ASUS TUF GAMING X570-PLUS                | 1         | 2.78%   |
| ASUS TUF GAMING B550M-PLUS               | 1         | 2.78%   |
| ASUS TUF B360M-PLUS GAMING/BR            | 1         | 2.78%   |
| ASUS PRIME A320M-K                       | 1         | 2.78%   |
| ASUS P5Q PRO TURBO                       | 1         | 2.78%   |
| ASUS ASUS TUF Gaming F15 FX506LU_FX506LU | 1         | 2.78%   |
| ASUS ASUS EXPERTBOOK B9400CEA_B9450CEA   | 1         | 2.78%   |
| ASRock X570 Taichi                       | 1         | 2.78%   |
| ASRock B450M Pro4                        | 1         | 2.78%   |
| Acer Aspire X5950                        | 1         | 2.78%   |
| Acer Aspire A315-58G                     | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS TUF           | 4         | 11.11%  |
| Lenovo Legion      | 3         | 8.33%   |
| Lenovo ThinkPad    | 2         | 5.56%   |
| Dell Latitude      | 2         | 5.56%   |
| ASUS VivoBook      | 2         | 5.56%   |
| ASUS ASUS          | 2         | 5.56%   |
| Acer Aspire        | 2         | 5.56%   |
| Pegatron D15K      | 1         | 2.78%   |
| MSI MS-7B61        | 1         | 2.78%   |
| MSI GP73           | 1         | 2.78%   |
| Lenovo Yoga        | 1         | 2.78%   |
| Lenovo Y520-15IKBN | 1         | 2.78%   |
| Lenovo IdeaPad     | 1         | 2.78%   |
| HP Z230            | 1         | 2.78%   |
| HP ProOne          | 1         | 2.78%   |
| HP Notebook        | 1         | 2.78%   |
| HP Laptop          | 1         | 2.78%   |
| HP ENVY            | 1         | 2.78%   |
| Gigabyte X570      | 1         | 2.78%   |
| Dell Vostro        | 1         | 2.78%   |
| Dell Precision     | 1         | 2.78%   |
| ASUS X510UNR       | 1         | 2.78%   |
| ASUS PRIME         | 1         | 2.78%   |
| ASUS P5Q           | 1         | 2.78%   |
| ASRock X570        | 1         | 2.78%   |
| ASRock B450M       | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 9         | 25%     |
| 2020 | 6         | 16.67%  |
| 2017 | 5         | 13.89%  |
| 2018 | 3         | 8.33%   |
| 2012 | 3         | 8.33%   |
| 2021 | 2         | 5.56%   |
| 2016 | 2         | 5.56%   |
| 2010 | 2         | 5.56%   |
| 2014 | 1         | 2.78%   |
| 2013 | 1         | 2.78%   |
| 2011 | 1         | 2.78%   |
| 2009 | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 21        | 58.33%  |
| Desktop     | 13        | 36.11%  |
| Convertible | 1         | 2.78%   |
| All in one  | 1         | 2.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 36        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 11        | 30.56%  |
| 4.01-8.0   | 9         | 25%     |
| 8.01-16.0  | 7         | 19.44%  |
| 32.01-64.0 | 4         | 11.11%  |
| 3.01-4.0   | 3         | 8.33%   |
| 24.01-32.0 | 2         | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 14        | 33.33%  |
| 4.01-8.0  | 11        | 26.19%  |
| 1.01-2.0  | 8         | 19.05%  |
| 3.01-4.0  | 3         | 7.14%   |
| 8.01-16.0 | 2         | 4.76%   |
| 0.51-1.0  | 2         | 4.76%   |
| 0.01-0.5  | 2         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 19        | 52.78%  |
| 2      | 12        | 33.33%  |
| 3      | 3         | 8.33%   |
| 6      | 2         | 5.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 77.78%  |
| Yes       | 8         | 22.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 83.33%  |
| No        | 6         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 86.11%  |
| No        | 5         | 13.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 72.22%  |
| No        | 10        | 27.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| India                 | 7         | 19.44%  |
| USA                   | 6         | 16.67%  |
| Poland                | 3         | 8.33%   |
| Italy                 | 2         | 5.56%   |
| France                | 2         | 5.56%   |
| Canada                | 2         | 5.56%   |
| Australia             | 2         | 5.56%   |
| Turkey                | 1         | 2.78%   |
| Spain                 | 1         | 2.78%   |
| Portugal              | 1         | 2.78%   |
| Palestinian Territory | 1         | 2.78%   |
| Norway                | 1         | 2.78%   |
| Morocco               | 1         | 2.78%   |
| Lebanon               | 1         | 2.78%   |
| Israel                | 1         | 2.78%   |
| Hungary               | 1         | 2.78%   |
| Greece                | 1         | 2.78%   |
| Brazil                | 1         | 2.78%   |
| Austria               | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Melbourne       | 2         | 5.41%   |
| Zell am See     | 1         | 2.7%    |
| Warsaw          | 1         | 2.7%    |
| Vannes          | 1         | 2.7%    |
| Toronto         | 1         | 2.7%    |
| Tel Aviv        | 1         | 2.7%    |
| Springfield     | 1         | 2.7%    |
| Salt Lake City  | 1         | 2.7%    |
| Ramallah        | 1         | 2.7%    |
| Poznan          | 1         | 2.7%    |
| Passos          | 1         | 2.7%    |
| Panchkula       | 1         | 2.7%    |
| Oslo            | 1         | 2.7%    |
| Mumbai          | 1         | 2.7%    |
| Montreal        | 1         | 2.7%    |
| Madurai         | 1         | 2.7%    |
| Lucknow         | 1         | 2.7%    |
| Longview        | 1         | 2.7%    |
| Lisbon          | 1         | 2.7%    |
| Istanbul        | 1         | 2.7%    |
| Granollers      | 1         | 2.7%    |
| Genoa           | 1         | 2.7%    |
| Gdansk          | 1         | 2.7%    |
| Ernakulam       | 1         | 2.7%    |
| East Malvern    | 1         | 2.7%    |
| Dunkirk         | 1         | 2.7%    |
| Denver          | 1         | 2.7%    |
| Chicago         | 1         | 2.7%    |
| Chennai         | 1         | 2.7%    |
| Casablanca      | 1         | 2.7%    |
| Budapest        | 1         | 2.7%    |
| Bhubaneswar     | 1         | 2.7%    |
| Beirut          | 1         | 2.7%    |
| Bari            | 1         | 2.7%    |
| Athens          | 1         | 2.7%    |
| Aix-en-Provence | 1         | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 12        | 23     | 20.34%  |
| Samsung Electronics       | 9         | 18     | 15.25%  |
| WDC                       | 7         | 9      | 11.86%  |
| Toshiba                   | 3         | 3      | 5.08%   |
| Sandisk                   | 3         | 3      | 5.08%   |
| Kingston                  | 3         | 5      | 5.08%   |
| Phison                    | 2         | 2      | 3.39%   |
| Micron Technology         | 2         | 3      | 3.39%   |
| Intel                     | 2         | 2      | 3.39%   |
| HGST                      | 2         | 2      | 3.39%   |
| XPG                       | 1         | 1      | 1.69%   |
| Unknown                   | 1         | 1      | 1.69%   |
| PNY                       | 1         | 1      | 1.69%   |
| PLEXTOR                   | 1         | 1      | 1.69%   |
| Micron/Crucial Technology | 1         | 1      | 1.69%   |
| LITEON                    | 1         | 1      | 1.69%   |
| KIOXIA                    | 1         | 1      | 1.69%   |
| Hitachi                   | 1         | 1      | 1.69%   |
| GOODRAM                   | 1         | 1      | 1.69%   |
| Crucial                   | 1         | 1      | 1.69%   |
| China                     | 1         | 1      | 1.69%   |
| Apacer                    | 1         | 1      | 1.69%   |
| A-DATA Technology         | 1         | 1      | 1.69%   |
| 2-Power                   | 1         | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Seagate ST1000LM049-2GH172 1TB             | 2         | 2.99%   |
| Seagate ST1000LM048-2E7172 1TB             | 2         | 2.99%   |
| Samsung SSD 970 EVO 1TB                    | 2         | 2.99%   |
| Samsung SSD 860 EVO 1TB                    | 2         | 2.99%   |
| Kingston SA400S37240G 240GB SSD            | 2         | 2.99%   |
| XPG GAMMIX S50 2TB                         | 1         | 1.49%   |
| WDC WDS100T1X0E-00AFY0 1TB                 | 1         | 1.49%   |
| WDC WD800JD-00MSA1 80GB                    | 1         | 1.49%   |
| WDC WD7500BPKT-75PK4T0 752GB               | 1         | 1.49%   |
| WDC WD5000AAKX-60U6AA0 500GB               | 1         | 1.49%   |
| WDC WD2500BEVT-60ZCT1 250GB                | 1         | 1.49%   |
| WDC WD10EZEX-22MFCA0 1TB                   | 1         | 1.49%   |
| WDC WD1002FAEX-00Z3A0 1TB                  | 1         | 1.49%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB       | 1         | 1.49%   |
| Unknown G1J38E  64GB                       | 1         | 1.49%   |
| Toshiba MQ04ABF100 1TB                     | 1         | 1.49%   |
| Toshiba MQ01ABF050M 500GB                  | 1         | 1.49%   |
| Toshiba KBG40ZNT512G MEMORY 512GB          | 1         | 1.49%   |
| Seagate ST9500325AS 500GB                  | 1         | 1.49%   |
| Seagate ST500LT012-9WS142 500GB            | 1         | 1.49%   |
| Seagate ST3500418AS 500GB                  | 1         | 1.49%   |
| Seagate ST250DM000-1BD141 250GB            | 1         | 1.49%   |
| Seagate ST2000DX001-1CM164 2TB             | 1         | 1.49%   |
| Seagate ST2000DM008-2FR102 2TB             | 1         | 1.49%   |
| Seagate ST2000DM006-2DM164 2TB             | 1         | 1.49%   |
| Seagate ST2000DM001-1ER164 2TB             | 1         | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB             | 1         | 1.49%   |
| Seagate ST1000DX001-SSHD-8GB               | 1         | 1.49%   |
| Seagate ST1000DM010-2EP102 1TB             | 1         | 1.49%   |
| Seagate FireCuda 510 SSD ZP1000GM30031 1TB | 1         | 1.49%   |
| Seagate Expansion+ 2TB                     | 1         | 1.49%   |
| SanDisk SDSSDH31024G 1024GB                | 1         | 1.49%   |
| Sandisk NVMe SSD Drive 500GB               | 1         | 1.49%   |
| Sandisk NVMe SSD Drive 256GB               | 1         | 1.49%   |
| Samsung SSD 980 PRO 2TB                    | 1         | 1.49%   |
| Samsung SSD 960 EVO 250GB                  | 1         | 1.49%   |
| Samsung SSD 860 EVO 250GB                  | 1         | 1.49%   |
| Samsung MZVLB1T0HBLR-00000 1TB             | 1         | 1.49%   |
| Samsung MZVLB1T0HALR-000L2 1TB             | 1         | 1.49%   |
| Samsung MZALQ128HBHQ-000L2 128GB           | 1         | 1.49%   |
| Samsung MZ7LF128HCHP-000L1 128GB SSD       | 1         | 1.49%   |
| PNY CS900 500GB SSD                        | 1         | 1.49%   |
| PLEXTOR PX-128M5M 128GB SSD                | 1         | 1.49%   |
| Phison Sabrent 1TB                         | 1         | 1.49%   |
| Phison NVMe SSD Drive 240GB                | 1         | 1.49%   |
| Micron/Crucial NVMe SSD Drive 1TB          | 1         | 1.49%   |
| Micron MTFDHBA1T0TCK 1TB                   | 1         | 1.49%   |
| Micron 2210_MTFDHBA512QFD 512GB            | 1         | 1.49%   |
| LITEON CV3-8D256 256GB SSD                 | 1         | 1.49%   |
| KIOXIA KBG30ZMV256G 256GB                  | 1         | 1.49%   |
| Kingston RBUSNS8154P3256GJ1 256GB          | 1         | 1.49%   |
| Intel SSDPEKNW512G8 512GB                  | 1         | 1.49%   |
| Intel SSDPEKNW010T8 1TB                    | 1         | 1.49%   |
| Hitachi HTS725050A9A364 500GB              | 1         | 1.49%   |
| HGST HTS545050A7E680 500GB                 | 1         | 1.49%   |
| HGST HTS541010A9E680 1TB                   | 1         | 1.49%   |
| GOODRAM SSD 240GB                          | 1         | 1.49%   |
| Crucial M4-CT512M4SSD1 512GB               | 1         | 1.49%   |
| China SATA3 240GB SSD                      | 1         | 1.49%   |
| Apacer AS350 256GB SSD                     | 1         | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 22     | 54.55%  |
| WDC     | 5         | 6      | 22.73%  |
| Toshiba | 2         | 2      | 9.09%   |
| HGST    | 2         | 2      | 9.09%   |
| Hitachi | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 6      | 26.67%  |
| Kingston            | 2         | 3      | 13.33%  |
| SanDisk             | 1         | 1      | 6.67%   |
| PNY                 | 1         | 1      | 6.67%   |
| PLEXTOR             | 1         | 1      | 6.67%   |
| LITEON              | 1         | 1      | 6.67%   |
| GOODRAM             | 1         | 1      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |
| China               | 1         | 1      | 6.67%   |
| Apacer              | 1         | 1      | 6.67%   |
| 2-Power             | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 33     | 37.25%  |
| NVMe | 18        | 32     | 35.29%  |
| SSD  | 13        | 18     | 25.49%  |
| MMC  | 1         | 1      | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26        | 50     | 56.52%  |
| NVMe | 18        | 32     | 39.13%  |
| SAS  | 1         | 1      | 2.17%   |
| MMC  | 1         | 1      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 14        | 19     | 42.42%  |
| 0.01-0.5   | 14        | 24     | 42.42%  |
| 1.01-2.0   | 5         | 8      | 15.15%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1001-2000      | 12        | 30.77%  |
| More than 3000 | 8         | 20.51%  |
| 251-500        | 4         | 10.26%  |
| 501-1000       | 4         | 10.26%  |
| Unknown        | 3         | 7.69%   |
| 2001-3000      | 2         | 5.13%   |
| 1-20           | 2         | 5.13%   |
| 51-100         | 2         | 5.13%   |
| 21-50          | 1         | 2.56%   |
| 101-250        | 1         | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 12        | 29.27%  |
| 51-100         | 10        | 24.39%  |
| 1-20           | 5         | 12.2%   |
| 1001-2000      | 3         | 7.32%   |
| 501-1000       | 3         | 7.32%   |
| Unknown        | 3         | 7.32%   |
| 251-500        | 2         | 4.88%   |
| More than 3000 | 1         | 2.44%   |
| 21-50          | 1         | 2.44%   |
| 2001-3000      | 1         | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB   | 1         | 1      | 11.11%  |
| WDC WD1002FAEX-00Z3A0 1TB      | 1         | 1      | 11.11%  |
| Toshiba MQ01ABF050M 500GB      | 1         | 1      | 11.11%  |
| Seagate ST9500325AS 500GB      | 1         | 1      | 11.11%  |
| Seagate ST2000DM006-2DM164 2TB | 1         | 1      | 11.11%  |
| Seagate ST1000LM049-2GH172 1TB | 1         | 1      | 11.11%  |
| Seagate ST1000LM048-2E7172 1TB | 1         | 1      | 11.11%  |
| Hitachi HTS725050A9A364 500GB  | 1         | 1      | 11.11%  |
| China SATA3 240GB SSD          | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 44.44%  |
| WDC     | 2         | 2      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |
| China   | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| WDC     | 2         | 2      | 25%     |
| Toshiba | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 88.89%  |
| SSD  | 1         | 1      | 11.11%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 29        | 59     | 64.44%  |
| Malfunc  | 9         | 9      | 20%     |
| Detected | 7         | 16     | 15.56%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 29        | 51.79%  |
| AMD                          | 7         | 12.5%   |
| Samsung Electronics          | 6         | 10.71%  |
| Sandisk                      | 3         | 5.36%   |
| Phison Electronics           | 2         | 3.57%   |
| Micron Technology            | 2         | 3.57%   |
| Toshiba America Info Systems | 1         | 1.79%   |
| Seagate Technology           | 1         | 1.79%   |
| Realtek Semiconductor        | 1         | 1.79%   |
| Micron/Crucial Technology    | 1         | 1.79%   |
| KIOXIA                       | 1         | 1.79%   |
| Kingston Technology Company  | 1         | 1.79%   |
| ADATA Technology             | 1         | 1.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 9.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 8.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 6.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 4.92%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 2         | 3.28%   |
| Phison E12 NVMe Controller                                                     | 2         | 3.28%   |
| Micron Non-Volatile memory controller                                          | 2         | 3.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 3.28%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 2         | 3.28%   |
| Intel SSD 660P Series                                                          | 2         | 3.28%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 3.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 3.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 3.28%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 1.64%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 1.64%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.64%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.64%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1         | 1.64%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 1.64%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 1.64%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.64%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                           | 1         | 1.64%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.64%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 1.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.64%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1         | 1.64%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 1         | 1.64%   |
| AMD FCH SATA Controller D                                                      | 1         | 1.64%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.64%   |
| ADATA Non-Volatile memory controller                                           | 1         | 1.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 29        | 53.7%   |
| NVMe | 18        | 33.33%  |
| RAID | 7         | 12.96%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 77.78%  |
| AMD    | 8         | 22.22%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 8.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 5.56%   |
| Intel Genuine CPU 0000 @ 2.10GHz              | 1         | 2.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 2.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 2.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.78%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 2.78%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 2.78%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 2.78%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 1         | 2.78%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1         | 2.78%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1         | 2.78%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 2.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2.78%   |
| Intel Core i5-4670 CPU @ 3.40GHz              | 1         | 2.78%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1         | 2.78%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 2.78%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 2.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.78%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 2.78%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1         | 2.78%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz         | 1         | 2.78%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.78%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 2.78%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 2.78%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 1         | 2.78%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 2.78%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1         | 2.78%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 1         | 2.78%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 1         | 2.78%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 2.78%   |
| AMD Athlon 200GE with Radeon Vega Graphics    | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 11        | 30.56%  |
| Intel Core i5     | 9         | 25%     |
| Other             | 3         | 8.33%   |
| AMD Ryzen 5       | 3         | 8.33%   |
| Intel Core i3     | 2         | 5.56%   |
| AMD Ryzen 7       | 2         | 5.56%   |
| Intel Genuine     | 1         | 2.78%   |
| Intel Core 2 Quad | 1         | 2.78%   |
| Intel Celeron     | 1         | 2.78%   |
| AMD Ryzen 9       | 1         | 2.78%   |
| AMD Ryzen 3       | 1         | 2.78%   |
| AMD Athlon        | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 13        | 36.11%  |
| 2      | 11        | 30.56%  |
| 6      | 7         | 19.44%  |
| 8      | 4         | 11.11%  |
| 12     | 1         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 30        | 81.08%  |
| 1      | 7         | 18.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 18.42%  |
| 0x906ea    | 4         | 10.53%  |
| 0x806e9    | 3         | 7.89%   |
| 0x806c1    | 3         | 7.89%   |
| 0x806ec    | 2         | 5.26%   |
| 0x306c3    | 2         | 5.26%   |
| 0x306a9    | 2         | 5.26%   |
| 0x0a201016 | 2         | 5.26%   |
| 0xa0652    | 1         | 2.63%   |
| 0x906ed    | 1         | 2.63%   |
| 0x906e9    | 1         | 2.63%   |
| 0x706a8    | 1         | 2.63%   |
| 0x406e3    | 1         | 2.63%   |
| 0x206a7    | 1         | 2.63%   |
| 0x20655    | 1         | 2.63%   |
| 0x1067a    | 1         | 2.63%   |
| 0x08701021 | 1         | 2.63%   |
| 0x08701013 | 1         | 2.63%   |
| 0x08600106 | 1         | 2.63%   |
| 0x08108109 | 1         | 2.63%   |
| 0x0810100b | 1         | 2.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 13        | 36.11%  |
| Zen 2         | 3         | 8.33%   |
| TigerLake     | 3         | 8.33%   |
| IvyBridge     | 3         | 8.33%   |
| Zen+          | 2         | 5.56%   |
| Zen 3         | 2         | 5.56%   |
| Haswell       | 2         | 5.56%   |
| Zen           | 1         | 2.78%   |
| Westmere      | 1         | 2.78%   |
| Skylake       | 1         | 2.78%   |
| SandyBridge   | 1         | 2.78%   |
| Penryn        | 1         | 2.78%   |
| Nehalem       | 1         | 2.78%   |
| Goldmont plus | 1         | 2.78%   |
| CometLake     | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 42.31%  |
| Nvidia | 21        | 40.38%  |
| AMD    | 9         | 17.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 3         | 5.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 5.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 5.77%   |
| Nvidia GP104 [GeForce GTX 1080]                                                       | 2         | 3.85%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 3.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 2         | 3.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.92%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 1.92%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 1.92%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 1.92%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 1.92%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 1.92%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 1.92%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 1         | 1.92%   |
| Nvidia GP107M [GeForce MX350]                                                         | 1         | 1.92%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 1.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 1         | 1.92%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 1         | 1.92%   |
| Nvidia GK107 [GeForce GT 740]                                                         | 1         | 1.92%   |
| Nvidia GF119M [NVS 4200M]                                                             | 1         | 1.92%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 1         | 1.92%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                        | 1         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.92%   |
| Intel UHD Graphics 620                                                                | 1         | 1.92%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 1.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 1         | 1.92%   |
| Intel HD Graphics 630                                                                 | 1         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.92%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 1.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 1.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 1         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 1.92%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 1         | 1.92%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                          | 1         | 1.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 1         | 1.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                      | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 13        | 36.11%  |
| 1 x Nvidia     | 8         | 22.22%  |
| 1 x Intel      | 6         | 16.67%  |
| 1 x AMD        | 6         | 16.67%  |
| Intel + AMD    | 3         | 8.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 20        | 54.05%  |
| Proprietary | 16        | 43.24%  |
| Unknown     | 1         | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 56.76%  |
| 1.01-2.0   | 5         | 13.51%  |
| 7.01-8.0   | 4         | 10.81%  |
| 5.01-6.0   | 3         | 8.11%   |
| 0.01-0.5   | 2         | 5.41%   |
| 3.01-4.0   | 1         | 2.7%    |
| 8.01-16.0  | 1         | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 5         | 12.2%   |
| BOE                  | 5         | 12.2%   |
| AU Optronics         | 5         | 12.2%   |
| Samsung Electronics  | 4         | 9.76%   |
| LG Display           | 4         | 9.76%   |
| Hewlett-Packard      | 2         | 4.88%   |
| Goldstar             | 2         | 4.88%   |
| AOC                  | 2         | 4.88%   |
| Sharp                | 1         | 2.44%   |
| Sceptre Tech         | 1         | 2.44%   |
| PANDA                | 1         | 2.44%   |
| Lenovo               | 1         | 2.44%   |
| Kogan                | 1         | 2.44%   |
| KOC                  | 1         | 2.44%   |
| Idek Iiyama          | 1         | 2.44%   |
| Gigabyte Technology  | 1         | 2.44%   |
| ASUSTek Computer     | 1         | 2.44%   |
| Apple                | 1         | 2.44%   |
| Ancor Communications | 1         | 2.44%   |
| Acer                 | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 4.76%   |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch               | 1         | 2.38%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                | 1         | 2.38%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch  | 1         | 2.38%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch   | 1         | 2.38%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1         | 2.38%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch               | 1         | 2.38%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 2.38%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 2.38%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch           | 1         | 2.38%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch           | 1         | 2.38%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 2.38%   |
| Kogan KAMN34FXQULA KGN3400 3440x1440 797x334mm 34.0-inch              | 1         | 2.38%   |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch               | 1         | 2.38%   |
| Idek Iiyama LCD Monitor PL2760Q 2560x1440                             | 1         | 2.38%   |
| Hewlett-Packard E240c HWP327C 1920x1080 510x290mm 23.1-inch           | 1         | 2.38%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1         | 2.38%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 1         | 2.38%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 1         | 2.38%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 2.38%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE083B 1920x1080 344x193mm 15.5-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 1         | 2.38%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUOA48F 1920x1080 309x174mm 14.0-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 1         | 2.38%   |
| ASUSTek Computer VG279QM AUS278F 1920x1080 598x336mm 27.0-inch        | 1         | 2.38%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                 | 1         | 2.38%   |
| AOC 27G2G4 AOC2702 1920x1080 600x340mm 27.2-inch                      | 1         | 2.38%   |
| AOC 2460G5 AOC246A 1920x1080 530x300mm 24.0-inch                      | 1         | 2.38%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 1         | 2.38%   |
| Acer S240HL ACR0289 1920x1080 530x300mm 24.0-inch                     | 1         | 2.38%   |
| Acer G215H ACR0109 1920x1080 477x268mm 21.5-inch                      | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 24        | 61.54%  |
| 2560x1440 (QHD)   | 4         | 10.26%  |
| 3840x2160 (4K)    | 3         | 7.69%   |
| 1366x768 (WXGA)   | 3         | 7.69%   |
| 3440x1440         | 2         | 5.13%   |
| 1920x1200 (WUXGA) | 1         | 2.56%   |
| 1600x900 (HD+)    | 1         | 2.56%   |
| 1280x1024 (SXGA)  | 1         | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 16        | 39.02%  |
| 27      | 5         | 12.2%   |
| 14      | 4         | 9.76%   |
| 21      | 3         | 7.32%   |
| 34      | 2         | 4.88%   |
| 31      | 2         | 4.88%   |
| 24      | 2         | 4.88%   |
| 23      | 2         | 4.88%   |
| 54      | 1         | 2.44%   |
| 18      | 1         | 2.44%   |
| 17      | 1         | 2.44%   |
| 13      | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 51.22%  |
| 501-600     | 8         | 19.51%  |
| 401-500     | 4         | 9.76%   |
| 701-800     | 2         | 4.88%   |
| 601-700     | 2         | 4.88%   |
| 351-400     | 2         | 4.88%   |
| 1001-1500   | 1         | 2.44%   |
| Unknown     | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 31        | 86.11%  |
| 21/9    | 2         | 5.56%   |
| 5/4     | 1         | 2.78%   |
| 16/10   | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 39.02%  |
| 201-250        | 6         | 14.63%  |
| 81-90          | 5         | 12.2%   |
| 301-350        | 5         | 12.2%   |
| 351-500        | 4         | 9.76%   |
| 151-200        | 2         | 4.88%   |
| More than 1000 | 1         | 2.44%   |
| 121-130        | 1         | 2.44%   |
| Unknown        | 1         | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 18        | 48.65%  |
| 101-120       | 8         | 21.62%  |
| 51-100        | 7         | 18.92%  |
| More than 240 | 1         | 2.7%    |
| 1-50          | 1         | 2.7%    |
| 161-240       | 1         | 2.7%    |
| Unknown       | 1         | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 29        | 78.38%  |
| 2     | 6         | 16.22%  |
| 3     | 1         | 2.7%    |
| 0     | 1         | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 47.17%  |
| Realtek Semiconductor | 19        | 35.85%  |
| Qualcomm Atheros      | 3         | 5.66%   |
| Broadcom              | 2         | 3.77%   |
| TP-Link               | 1         | 1.89%   |
| Samsung Electronics   | 1         | 1.89%   |
| Qualcomm              | 1         | 1.89%   |
| Microsoft             | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 14        | 21.54%  |
| Intel Wi-Fi 6 AX200                                                 | 4         | 6.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 4         | 6.15%   |
| Intel Wi-Fi 6 AX201                                                 | 3         | 4.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 3         | 4.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3         | 4.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2         | 3.08%   |
| Realtek RTL8125 2.5GbE Controller                                   | 2         | 3.08%   |
| Intel Wireless-AC 9260                                              | 2         | 3.08%   |
| Intel I211 Gigabit Network Connection                               | 2         | 3.08%   |
| Intel Ethernet Connection (7) I219-V                                | 2         | 3.08%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 1         | 1.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 1         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1         | 1.54%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 1         | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1         | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1         | 1.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1         | 1.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1         | 1.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1         | 1.54%   |
| Qualcomm 8920FT CD-ROM                                              | 1         | 1.54%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 1         | 1.54%   |
| Intel Wireless 8265 / 8275                                          | 1         | 1.54%   |
| Intel Wireless 8260                                                 | 1         | 1.54%   |
| Intel Ethernet Connection I219-V                                    | 1         | 1.54%   |
| Intel Ethernet Connection I217-LM                                   | 1         | 1.54%   |
| Intel Ethernet Connection (2) I219-V                                | 1         | 1.54%   |
| Intel Ethernet Connection (13) I219-V                               | 1         | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 1         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 1         | 1.54%   |
| Intel Centrino Wireless-N 2230                                      | 1         | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 1         | 1.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                     | 1         | 1.54%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 1         | 1.54%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 68.75%  |
| Realtek Semiconductor | 4         | 12.5%   |
| Qualcomm Atheros      | 2         | 6.25%   |
| Broadcom              | 2         | 6.25%   |
| TP-Link               | 1         | 3.13%   |
| Microsoft             | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 4         | 12.5%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 4         | 12.5%   |
| Intel Wi-Fi 6 AX201                                                 | 3         | 9.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 3         | 9.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2         | 6.25%   |
| Intel Wireless-AC 9260                                              | 2         | 6.25%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 1         | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1         | 3.13%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 1         | 3.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1         | 3.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1         | 3.13%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 1         | 3.13%   |
| Intel Wireless 8265 / 8275                                          | 1         | 3.13%   |
| Intel Wireless 8260                                                 | 1         | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 1         | 3.13%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 1         | 3.13%   |
| Intel Centrino Wireless-N 2230                                      | 1         | 3.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 1         | 3.13%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 1         | 3.13%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 51.52%  |
| Intel                 | 11        | 33.33%  |
| Qualcomm Atheros      | 2         | 6.06%   |
| Samsung Electronics   | 1         | 3.03%   |
| Qualcomm              | 1         | 3.03%   |
| Broadcom              | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 42.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 9.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 6.06%   |
| Intel I211 Gigabit Network Connection                             | 2         | 6.06%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 6.06%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.03%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 3.03%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 3.03%   |
| Qualcomm 8920FT CD-ROM                                            | 1         | 3.03%   |
| Intel Ethernet Connection I219-V                                  | 1         | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 3.03%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 3.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 50.82%  |
| Ethernet | 30        | 49.18%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 67.5%   |
| Ethernet | 13        | 32.5%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 23        | 63.89%  |
| 1     | 12        | 33.33%  |
| 3     | 1         | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 83.78%  |
| Yes  | 6         | 16.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 69.23%  |
| Realtek Semiconductor           | 2         | 7.69%   |
| IMC Networks                    | 2         | 7.69%   |
| Broadcom                        | 2         | 7.69%   |
| Qualcomm Atheros Communications | 1         | 3.85%   |
| Dell                            | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Bluetooth Device                        | 8         | 30.77%  |
| Intel AX200 Bluetooth                         | 4         | 15.38%  |
| Intel AX201 Bluetooth                         | 3         | 11.54%  |
| Intel Wireless-AC 9260 Bluetooth Adapter      | 2         | 7.69%   |
| IMC Networks Bluetooth Radio                  | 2         | 7.69%   |
| Realtek  Bluetooth 4.2 Adapter                | 1         | 3.85%   |
| Realtek Bluetooth Radio                       | 1         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device            | 1         | 3.85%   |
| Intel Centrino Bluetooth Wireless Transceiver | 1         | 3.85%   |
| Dell BCM20702A0                               | 1         | 3.85%   |
| Broadcom HP Portable Bumble Bee               | 1         | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0             | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 28        | 45.9%   |
| Nvidia                 | 14        | 22.95%  |
| AMD                    | 9         | 14.75%  |
| Razer USA              | 2         | 3.28%   |
| C-Media Electronics    | 2         | 3.28%   |
| Tenx Technology        | 1         | 1.64%   |
| Plantronics            | 1         | 1.64%   |
| Logitech               | 1         | 1.64%   |
| Hewlett-Packard        | 1         | 1.64%   |
| Generalplus Technology | 1         | 1.64%   |
| Corsair                | 1         | 1.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 7.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 7.35%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 5.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 4.41%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 4.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.94%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.94%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 2.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.94%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 2.94%   |
| Tenx Technology USB AUDIO                                                  | 1         | 1.47%   |
| Razer USA Razer Kraken X USB                                               | 1         | 1.47%   |
| Razer USA Razer Kraken Ultimate                                            | 1         | 1.47%   |
| Plantronics C320-M                                                         | 1         | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.47%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.47%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.47%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.47%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.47%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.47%   |
| Logitech G633 Gaming Headset                                               | 1         | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.47%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.47%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.47%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.47%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.47%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 1.47%   |
| Hewlett-Packard E240C                                                      | 1         | 1.47%   |
| Generalplus Technology USB Audio Device                                    | 1         | 1.47%   |
| Corsair HS60 PRO Surround USB Sound Adapter                                | 1         | 1.47%   |
| C-Media Electronics Schiit Modi Uber                                       | 1         | 1.47%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1         | 1.47%   |
| C-Media Electronics Blue Snowball                                          | 1         | 1.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 25%     |
| SK Hynix            | 9         | 22.5%   |
| Crucial             | 4         | 10%     |
| Micron Technology   | 3         | 7.5%    |
| Kingston            | 3         | 7.5%    |
| G.Skill             | 3         | 7.5%    |
| Unknown             | 2         | 5%      |
| Ramaxel Technology  | 2         | 5%      |
| Unifosa             | 1         | 2.5%    |
| Team                | 1         | 2.5%    |
| PNY                 | 1         | 2.5%    |
| Corsair             | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 2.38%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1         | 2.38%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s              | 1         | 2.38%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s             | 1         | 2.38%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 2.38%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.38%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s      | 1         | 2.38%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.38%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.38%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s   | 1         | 2.38%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 2.38%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s      | 1         | 2.38%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 2.38%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s        | 1         | 2.38%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s      | 1         | 2.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 2.38%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.38%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1         | 2.38%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 1         | 2.38%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s         | 1         | 2.38%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 2.38%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 2.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 2.38%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s       | 1         | 2.38%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s       | 1         | 2.38%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s        | 1         | 2.38%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 1         | 2.38%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2400MT/s            | 1         | 2.38%   |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s | 1         | 2.38%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s          | 1         | 2.38%   |
| Micron RAM 16KTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s            | 1         | 2.38%   |
| Kingston RAM KHYXPX-MID 8GB SODIMM DDR4 2667MT/s               | 1         | 2.38%   |
| Kingston RAM HP16D3LS1KFG/4G 4096MB SODIMM DDR3 1600MT/s       | 1         | 2.38%   |
| Kingston RAM 99U5428-069.A00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2.38%   |
| G.Skill RAM F4-3600C17-8GTZR 8GB DIMM DDR4 3600MT/s            | 1         | 2.38%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s         | 1         | 2.38%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s         | 1         | 2.38%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s        | 1         | 2.38%   |
| Crucial RAM CT4G4DFS824A.C8FHP 4096MB DIMM DDR4 2400MT/s       | 1         | 2.38%   |
| Crucial RAM CT25664BD160B.C8FN 2GB DIMM DDR3 1333MT/s          | 1         | 2.38%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s     | 1         | 2.38%   |
| Corsair RAM CMSO16GX4M2A2133C15 8GB SODIMM DDR4 2667MT/s       | 1         | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 21        | 65.63%  |
| DDR3   | 8         | 25%     |
| SDRAM  | 1         | 3.13%   |
| LPDDR4 | 1         | 3.13%   |
| DDR2   | 1         | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 64.52%  |
| DIMM         | 9         | 29.03%  |
| Row Of Chips | 2         | 6.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 17        | 48.57%  |
| 4096  | 10        | 28.57%  |
| 16384 | 6         | 17.14%  |
| 2048  | 2         | 5.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 11        | 31.43%  |
| 1600  | 7         | 20%     |
| 3200  | 4         | 11.43%  |
| 2400  | 4         | 11.43%  |
| 4400  | 1         | 2.86%   |
| 4267  | 1         | 2.86%   |
| 4199  | 1         | 2.86%   |
| 4133  | 1         | 2.86%   |
| 3600  | 1         | 2.86%   |
| 3266  | 1         | 2.86%   |
| 3067  | 1         | 2.86%   |
| 1333  | 1         | 2.86%   |
| 800   | 1         | 2.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 5         | 20.83%  |
| Chicony Electronics                    | 5         | 20.83%  |
| Acer                                   | 3         | 12.5%   |
| Syntek                                 | 2         | 8.33%   |
| Sunplus Innovation Technology          | 2         | 8.33%   |
| Quanta                                 | 2         | 8.33%   |
| Microdia                               | 2         | 8.33%   |
| Realtek Semiconductor                  | 1         | 4.17%   |
| Lite-On Technology                     | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                   | 3         | 12.5%   |
| Syntek Integrated Camera                                             | 2         | 8.33%   |
| IMC Networks USB2.0 HD UVC WebCam                                    | 2         | 8.33%   |
| Chicony EasyCamera                                                   | 2         | 8.33%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                 | 1         | 4.17%   |
| Sunplus HP Truevision HD                                             | 1         | 4.17%   |
| Realtek Built-In Video Camera                                        | 1         | 4.17%   |
| Quanta HP TrueVision HD Camera                                       | 1         | 4.17%   |
| Quanta HD User Facing                                                | 1         | 4.17%   |
| Microdia Integrated_Webcam_HD                                        | 1         | 4.17%   |
| Microdia Dell Integrated HD Webcam                                   | 1         | 4.17%   |
| Lite-On Integrated Camera                                            | 1         | 4.17%   |
| Chicony Integrated Camera                                            | 1         | 4.17%   |
| Chicony HP Webcam                                                    | 1         | 4.17%   |
| Chicony HP High Definition 1MP Webcam                                | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1         | 4.17%   |
| Acer ThinkPad Integrated Camera                                      | 1         | 4.17%   |
| Acer SunplusIT Integrated Camera                                     | 1         | 4.17%   |
| Acer HD Webcam                                                       | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 50%     |
| Shenzhen Goodix Technology | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI     | 1         | 50%     |
| Shenzhen Goodix  FingerPrint Device | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 66.67%  |
| Upek     | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 2         | 66.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 24        | 64.86%  |
| 1     | 11        | 29.73%  |
| 2     | 2         | 5.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Graphics card      | 3         | 20%     |
| Chipcard           | 3         | 20%     |
| Fingerprint reader | 2         | 13.33%  |
| Camera             | 2         | 13.33%  |
| Bluetooth          | 2         | 13.33%  |
| Storage            | 1         | 6.67%   |
| Network            | 1         | 6.67%   |
| Net/wireless       | 1         | 6.67%   |

