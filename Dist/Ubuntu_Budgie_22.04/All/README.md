Ubuntu Budgie 22.04 - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie_22.04/Notebook/README.md).

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

Total: 70

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6410              | Notebook    | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | Notebook    | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Gigabyte      | B75M-D3P                    | Desktop     | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [19a21d721c](https://linux-hardware.org/?probe=19a21d721c) | Sep 07, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Google        | Rabbid                      | Notebook    | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [81ba48faa1](https://linux-hardware.org/?probe=81ba48faa1) | Aug 20, 2022 |
| Intel         | X79M-S                      | Desktop     | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| HP            | 828A                        | Desktop     | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Biostar       | A960D+V3                    | Desktop     | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | Notebook    | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [b48ce81bfa](https://linux-hardware.org/?probe=b48ce81bfa) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| MSI           | GL62 6QF                    | Notebook    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | Notebook    | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [261466af7b](https://linux-hardware.org/?probe=261466af7b) | Jun 17, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | Notebook    | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| MSI           | Modern 15 A10M              | Notebook    | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| HP            | 1825                        | Desktop     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | Notebook    | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Samsung       | 740U3M                      | Convertible | [4ba9324ca5](https://linux-hardware.org/?probe=4ba9324ca5) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| HP            | 8446                        | All in one  | [b13e626d1a](https://linux-hardware.org/?probe=b13e626d1a) | May 02, 2022 |
| HP            | 8446                        | All in one  | [14d68e146a](https://linux-hardware.org/?probe=14d68e146a) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [77a04d958e](https://linux-hardware.org/?probe=77a04d958e) | Jan 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.15.0-27-generic     | 11        | 18.64%  |
| 5.15.0-30-generic     | 6         | 10.17%  |
| 5.15.0-46-generic     | 5         | 8.47%   |
| 5.15.0-39-generic     | 5         | 8.47%   |
| 5.15.0-33-generic     | 4         | 6.78%   |
| 5.15.0-25-generic     | 4         | 6.78%   |
| 5.15.0-47-generic     | 3         | 5.08%   |
| 5.15.0-43-generic     | 3         | 5.08%   |
| 5.15.0-40-generic     | 3         | 5.08%   |
| 5.15.0-48-generic     | 2         | 3.39%   |
| 5.15.0-41-generic     | 2         | 3.39%   |
| 5.19.0-051900-generic | 1         | 1.69%   |
| 5.17.2-051702-generic | 1         | 1.69%   |
| 5.16.2                | 1         | 1.69%   |
| 5.15.0-47-lowlatency  | 1         | 1.69%   |
| 5.15.0-35-generic     | 1         | 1.69%   |
| 5.15.0-18-generic     | 1         | 1.69%   |
| 5.15.0-10047-tuxedo   | 1         | 1.69%   |
| 5.15.0-10041-tuxedo   | 1         | 1.69%   |
| 5.13.0-44-generic     | 1         | 1.69%   |
| 5.13.0-35-generic     | 1         | 1.69%   |
| 5.13.0-19-generic     | 1         | 1.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 51        | 89.47%  |
| 5.13.0  | 3         | 5.26%   |
| 5.19.0  | 1         | 1.75%   |
| 5.17.2  | 1         | 1.75%   |
| 5.16.2  | 1         | 1.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 51        | 89.47%  |
| 5.13    | 3         | 5.26%   |
| 5.19    | 1         | 1.75%   |
| 5.17    | 1         | 1.75%   |
| 5.16    | 1         | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 57        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 55        | 96.49%  |
| GNOME  | 2         | 3.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 55        | 96.49%  |
| Wayland | 2         | 3.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 38        | 66.67%  |
| Unknown | 12        | 21.05%  |
| GDM3    | 6         | 10.53%  |
| GDM     | 1         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 22        | 38.6%   |
| de_DE | 9         | 15.79%  |
| fr_FR | 7         | 12.28%  |
| pt_BR | 4         | 7.02%   |
| en_GB | 3         | 5.26%   |
| es_MX | 2         | 3.51%   |
| es_ES | 2         | 3.51%   |
| en_CA | 2         | 3.51%   |
| it_IT | 1         | 1.75%   |
| hu_HU | 1         | 1.75%   |
| fr_BE | 1         | 1.75%   |
| es_EC | 1         | 1.75%   |
| en_IE | 1         | 1.75%   |
| C     | 1         | 1.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 34        | 58.62%  |
| EFI  | 24        | 41.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 49        | 85.96%  |
| Overlay | 5         | 8.77%   |
| Btrfs   | 2         | 3.51%   |
| Xfs     | 1         | 1.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 52.63%  |
| GPT     | 25        | 43.86%  |
| MBR     | 2         | 3.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 78.95%  |
| Yes       | 12        | 21.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 70.18%  |
| Yes       | 17        | 29.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 10        | 17.54%  |
| Lenovo                 | 8         | 14.04%  |
| Gigabyte Technology    | 8         | 14.04%  |
| ASUSTek Computer       | 6         | 10.53%  |
| Apple                  | 5         | 8.77%   |
| Dell                   | 4         | 7.02%   |
| MSI                    | 3         | 5.26%   |
| TUXEDO                 | 2         | 3.51%   |
| Intel                  | 2         | 3.51%   |
| Google                 | 2         | 3.51%   |
| Timi                   | 1         | 1.75%   |
| Samsung Electronics    | 1         | 1.75%   |
| Chuwi                  | 1         | 1.75%   |
| Biostar                | 1         | 1.75%   |
| Avell High Performance | 1         | 1.75%   |
| ASRock                 | 1         | 1.75%   |
| Acer                   | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| TUXEDO Book XUX7 Gen11                | 1         | 1.75%   |
| TUXEDO Book BA1510                    | 1         | 1.75%   |
| Timi TM1604                           | 1         | 1.75%   |
| Samsung 740U3M                        | 1         | 1.75%   |
| MSI MS-7A32                           | 1         | 1.75%   |
| MSI Modern 15 A10M                    | 1         | 1.75%   |
| MSI GL62 6QF                          | 1         | 1.75%   |
| Lenovo ThinkPad T500 2242CTO          | 1         | 1.75%   |
| Lenovo ThinkPad T440 20B7S0F100       | 1         | 1.75%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE | 1         | 1.75%   |
| Lenovo IdeaPad S145-14IWL 81MU        | 1         | 1.75%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 1         | 1.75%   |
| Lenovo IdeaPad 330-15IKB 81FE         | 1         | 1.75%   |
| Lenovo G500 20236                     | 1         | 1.75%   |
| Lenovo G50-45 80E3                    | 1         | 1.75%   |
| Intel STK1A32SC                       | 1         | 1.75%   |
| Intel DP55WB AAE64798-206             | 1         | 1.75%   |
| HP Z440 Workstation                   | 1         | 1.75%   |
| HP Spectre x360 Convertible 15t-df100 | 1         | 1.75%   |
| HP ProBook 450 G8 Notebook PC         | 1         | 1.75%   |
| HP Pavilion g6                        | 1         | 1.75%   |
| HP ENVY 17                            | 1         | 1.75%   |
| HP ElitePad 1000 G2                   | 1         | 1.75%   |
| HP EliteDesk 800 G1 DM                | 1         | 1.75%   |
| HP EliteBook 840 G3                   | 1         | 1.75%   |
| HP All-in-One 22-c0xx                 | 1         | 1.75%   |
| HP 750-417c                           | 1         | 1.75%   |
| Google Rabbid                         | 1         | 1.75%   |
| Google Boten                          | 1         | 1.75%   |
| Gigabyte X570S AORUS PRO AX           | 1         | 1.75%   |
| Gigabyte M68MT-S2                     | 1         | 1.75%   |
| Gigabyte GA-890GPA-UD3H               | 1         | 1.75%   |
| Gigabyte F2A78M-HD2                   | 1         | 1.75%   |
| Gigabyte B75M-D3P                     | 1         | 1.75%   |
| Gigabyte B75M-D3H                     | 1         | 1.75%   |
| Gigabyte B550 AORUS ELITE AX V2       | 1         | 1.75%   |
| Gigabyte B450 I AORUS PRO WIFI        | 1         | 1.75%   |
| Dell Latitude E6410                   | 1         | 1.75%   |
| Dell Inspiron 7506 2n1                | 1         | 1.75%   |
| Dell Inspiron 5570                    | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 3         | 5.26%   |
| Lenovo IdeaPad              | 3         | 5.26%   |
| Dell Inspiron               | 3         | 5.26%   |
| TUXEDO Book                 | 2         | 3.51%   |
| ASUS VivoBook               | 2         | 3.51%   |
| Timi TM1604                 | 1         | 1.75%   |
| Samsung 740U3M              | 1         | 1.75%   |
| MSI MS-7A32                 | 1         | 1.75%   |
| MSI Modern                  | 1         | 1.75%   |
| MSI GL62                    | 1         | 1.75%   |
| Lenovo G500                 | 1         | 1.75%   |
| Lenovo G50-45               | 1         | 1.75%   |
| Intel STK1A32SC             | 1         | 1.75%   |
| Intel DP55WB                | 1         | 1.75%   |
| HP Z440                     | 1         | 1.75%   |
| HP Spectre                  | 1         | 1.75%   |
| HP ProBook                  | 1         | 1.75%   |
| HP Pavilion                 | 1         | 1.75%   |
| HP ENVY                     | 1         | 1.75%   |
| HP ElitePad                 | 1         | 1.75%   |
| HP EliteDesk                | 1         | 1.75%   |
| HP EliteBook                | 1         | 1.75%   |
| HP All-in-One               | 1         | 1.75%   |
| HP 750-417c                 | 1         | 1.75%   |
| Google Rabbid               | 1         | 1.75%   |
| Google Boten                | 1         | 1.75%   |
| Gigabyte X570S              | 1         | 1.75%   |
| Gigabyte M68MT-S2           | 1         | 1.75%   |
| Gigabyte GA-890GPA-UD3H     | 1         | 1.75%   |
| Gigabyte F2A78M-HD2         | 1         | 1.75%   |
| Gigabyte B75M-D3P           | 1         | 1.75%   |
| Gigabyte B75M-D3H           | 1         | 1.75%   |
| Gigabyte B550               | 1         | 1.75%   |
| Gigabyte B450               | 1         | 1.75%   |
| Dell Latitude               | 1         | 1.75%   |
| Chuwi HeroBook              | 1         | 1.75%   |
| Biostar A960D+V3            | 1         | 1.75%   |
| Avell High Performance B.ON | 1         | 1.75%   |
| ASUS ZenBook                | 1         | 1.75%   |
| ASUS T200TAC                | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 8         | 14.04%  |
| 2021 | 7         | 12.28%  |
| 2018 | 6         | 10.53%  |
| 2016 | 5         | 8.77%   |
| 2014 | 5         | 8.77%   |
| 2019 | 4         | 7.02%   |
| 2010 | 4         | 7.02%   |
| 2017 | 3         | 5.26%   |
| 2015 | 3         | 5.26%   |
| 2013 | 3         | 5.26%   |
| 2012 | 2         | 3.51%   |
| 2011 | 2         | 3.51%   |
| 2009 | 2         | 3.51%   |
| 2008 | 2         | 3.51%   |
| 2022 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 33        | 57.89%  |
| Desktop     | 18        | 31.58%  |
| Convertible | 3         | 5.26%   |
| All in one  | 2         | 3.51%   |
| Mini pc     | 1         | 1.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 55        | 96.49%  |
| Enabled  | 2         | 3.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 96.49%  |
| Yes  | 2         | 3.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 28.07%  |
| 16.01-24.0  | 16        | 28.07%  |
| 8.01-16.0   | 11        | 19.3%   |
| 3.01-4.0    | 7         | 12.28%  |
| 32.01-64.0  | 4         | 7.02%   |
| 64.01-256.0 | 2         | 3.51%   |
| 1.01-2.0    | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 21        | 36.21%  |
| 2.01-3.0   | 20        | 34.48%  |
| 4.01-8.0   | 11        | 18.97%  |
| 3.01-4.0   | 3         | 5.17%   |
| 8.01-16.0  | 2         | 3.45%   |
| 24.01-32.0 | 1         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 47.37%  |
| 2      | 20        | 35.09%  |
| 3      | 5         | 8.77%   |
| 4      | 3         | 5.26%   |
| 6      | 2         | 3.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 71.93%  |
| Yes       | 16        | 28.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 77.19%  |
| No        | 13        | 22.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 84.21%  |
| No        | 9         | 15.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 70.18%  |
| No        | 17        | 29.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 16        | 28.07%  |
| Germany            | 8         | 14.04%  |
| France             | 5         | 8.77%   |
| Brazil             | 5         | 8.77%   |
| UK                 | 2         | 3.51%   |
| Slovenia           | 2         | 3.51%   |
| Mexico             | 2         | 3.51%   |
| Canada             | 2         | 3.51%   |
| Switzerland        | 1         | 1.75%   |
| Spain              | 1         | 1.75%   |
| Norway             | 1         | 1.75%   |
| Italy              | 1         | 1.75%   |
| Ireland            | 1         | 1.75%   |
| Hungary            | 1         | 1.75%   |
| Greece             | 1         | 1.75%   |
| Ecuador            | 1         | 1.75%   |
| Dominican Republic | 1         | 1.75%   |
| Croatia            | 1         | 1.75%   |
| Cabo Verde         | 1         | 1.75%   |
| Belgium            | 1         | 1.75%   |
| Austria            | 1         | 1.75%   |
| Argentina          | 1         | 1.75%   |
| Algeria            | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Milwaukee             | 2         | 3.51%   |
| West Lafayette        | 1         | 1.75%   |
| Wertheim am Main      | 1         | 1.75%   |
| Walled Lake           | 1         | 1.75%   |
| Vienna                | 1         | 1.75%   |
| Victoria              | 1         | 1.75%   |
| Trondheim             | 1         | 1.75%   |
| Tocantins             | 1         | 1.75%   |
| Tampa                 | 1         | 1.75%   |
| Sétif                | 1         | 1.75%   |
| Seelze                | 1         | 1.75%   |
| Sao Paulo             | 1         | 1.75%   |
| Santo Domingo Este    | 1         | 1.75%   |
| San Luis Potosí City | 1         | 1.75%   |
| Saint-Gilles          | 1         | 1.75%   |
| Rueil-Malmaison       | 1         | 1.75%   |
| Queens                | 1         | 1.75%   |
| Pula                  | 1         | 1.75%   |
| Puebla City           | 1         | 1.75%   |
| Praia                 | 1         | 1.75%   |
| Postojna              | 1         | 1.75%   |
| Nuremberg             | 1         | 1.75%   |
| New York              | 1         | 1.75%   |
| Monza                 | 1         | 1.75%   |
| Mishawaka             | 1         | 1.75%   |
| Massaranduba          | 1         | 1.75%   |
| Maribor               | 1         | 1.75%   |
| Madrid                | 1         | 1.75%   |
| Lille                 | 1         | 1.75%   |
| Leominster            | 1         | 1.75%   |
| Le Mee-sur-Seine      | 1         | 1.75%   |
| Laval                 | 1         | 1.75%   |
| Kirkcaldy             | 1         | 1.75%   |
| Kassel                | 1         | 1.75%   |
| Hamburg               | 1         | 1.75%   |
| Fontenay-sous-Bois    | 1         | 1.75%   |
| Eureka                | 1         | 1.75%   |
| Ennepetal             | 1         | 1.75%   |
| Dublin                | 1         | 1.75%   |
| DeQuincy              | 1         | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 12        | 15     | 12.63%  |
| Seagate               | 10        | 15     | 10.53%  |
| WDC                   | 7         | 9      | 7.37%   |
| Unknown               | 7         | 7      | 7.37%   |
| Crucial               | 6         | 7      | 6.32%   |
| Toshiba               | 5         | 5      | 5.26%   |
| SK hynix              | 4         | 4      | 4.21%   |
| SanDisk               | 4         | 5      | 4.21%   |
| Kingston              | 4         | 5      | 4.21%   |
| Intel                 | 4         | 6      | 4.21%   |
| SPCC                  | 3         | 3      | 3.16%   |
| Micron Technology     | 3         | 3      | 3.16%   |
| JMicron Technology    | 3         | 3      | 3.16%   |
| Phison                | 2         | 2      | 2.11%   |
| OCZ                   | 2         | 2      | 2.11%   |
| China                 | 2         | 2      | 2.11%   |
| A-DATA Technology     | 2         | 2      | 2.11%   |
| Union Memory          | 1         | 1      | 1.05%   |
| Transcend             | 1         | 1      | 1.05%   |
| TO Exter              | 1         | 1      | 1.05%   |
| SABRENT               | 1         | 1      | 1.05%   |
| Realtek Semiconductor | 1         | 1      | 1.05%   |
| OWC                   | 1         | 1      | 1.05%   |
| Netac                 | 1         | 1      | 1.05%   |
| Maxtor                | 1         | 1      | 1.05%   |
| LITEON                | 1         | 1      | 1.05%   |
| HGST                  | 1         | 1      | 1.05%   |
| Hewlett-Packard       | 1         | 1      | 1.05%   |
| Corsair               | 1         | 2      | 1.05%   |
| ASMT109x              | 1         | 1      | 1.05%   |
| Apple                 | 1         | 1      | 1.05%   |
| Unknown               | 1         | 1      | 1.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 1.92%   |
| Unknown SD64G  64GB                    | 2         | 1.92%   |
| Unknown SD/MMC/MS PRO 2GB              | 2         | 1.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 1.92%   |
| SanDisk SDSSDA120G 120GB               | 2         | 1.92%   |
| Samsung NVMe SSD Drive 256GB           | 2         | 1.92%   |
| JMicron Generic 120GB                  | 2         | 1.92%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 1.92%   |
| Crucial CT1000MX500SSD1 1TB            | 2         | 1.92%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.96%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.96%   |
| WDC WD40PURZ-85TTDY0 4TB               | 1         | 0.96%   |
| WDC WD10EARS-00Y5B1 1TB                | 1         | 0.96%   |
| WDC WD10EADS-00M2B0 1TB                | 1         | 0.96%   |
| WDC PC SN730 NVMe 256GB                | 1         | 0.96%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB   | 1         | 0.96%   |
| Unknown SL128  128GB                   | 1         | 0.96%   |
| Unknown SA16G  16GB                    | 1         | 0.96%   |
| Unknown MMC128  128GB                  | 1         | 0.96%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD | 1         | 0.96%   |
| Transcend TS128GMTE110S 128GB          | 1         | 0.96%   |
| Toshiba TR150 480GB SSD                | 1         | 0.96%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 1         | 0.96%   |
| Toshiba HDWD240 4TB                    | 1         | 0.96%   |
| Toshiba HDWD220 2TB                    | 1         | 0.96%   |
| Toshiba DT01ACA100 1TB                 | 1         | 0.96%   |
| TO Exter nal USB 3.0 180GB             | 1         | 0.96%   |
| SPCC Solid State Disk 256GB            | 1         | 0.96%   |
| SPCC Solid State Disk 120GB            | 1         | 0.96%   |
| SPCC M.2 PCIe SSD 256GB                | 1         | 0.96%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB   | 1         | 0.96%   |
| SK hynix SC210 2.5 7MM 128GB SSD       | 1         | 0.96%   |
| SK hynix HCG8e  64GB                   | 1         | 0.96%   |
| SK hynix HBG4e  32GB                   | 1         | 0.96%   |
| Seagate ST9500325AS 500GB              | 1         | 0.96%   |
| Seagate ST500LT012-1DG142 500GB        | 1         | 0.96%   |
| Seagate ST380815AS 80GB                | 1         | 0.96%   |
| Seagate ST3500418AS 500GB              | 1         | 0.96%   |
| Seagate ST3500412AS 500GB              | 1         | 0.96%   |
| Seagate ST3160815AS 160GB              | 1         | 0.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 14     | 40%     |
| WDC                 | 5         | 6      | 20%     |
| Toshiba             | 3         | 3      | 12%     |
| Unknown             | 2         | 2      | 8%      |
| Samsung Electronics | 2         | 3      | 8%      |
| Maxtor              | 1         | 1      | 4%      |
| HGST                | 1         | 1      | 4%      |
| ASMT109x            | 1         | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 17.14%  |
| Crucial             | 6         | 7      | 17.14%  |
| SPCC                | 2         | 2      | 5.71%   |
| SanDisk             | 2         | 2      | 5.71%   |
| Micron Technology   | 2         | 2      | 5.71%   |
| China               | 2         | 2      | 5.71%   |
| WDC                 | 1         | 1      | 2.86%   |
| Union Memory        | 1         | 1      | 2.86%   |
| Toshiba             | 1         | 1      | 2.86%   |
| TO Exter            | 1         | 1      | 2.86%   |
| SK hynix            | 1         | 1      | 2.86%   |
| OWC                 | 1         | 1      | 2.86%   |
| OCZ                 | 1         | 1      | 2.86%   |
| Netac               | 1         | 1      | 2.86%   |
| LITEON              | 1         | 1      | 2.86%   |
| Kingston            | 1         | 2      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |
| Hewlett-Packard     | 1         | 1      | 2.86%   |
| Corsair             | 1         | 2      | 2.86%   |
| Apple               | 1         | 1      | 2.86%   |
| A-DATA Technology   | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 30        | 39     | 38.46%  |
| NVMe    | 22        | 31     | 28.21%  |
| HDD     | 18        | 31     | 23.08%  |
| MMC     | 7         | 9      | 8.97%   |
| Unknown | 1         | 1      | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 66     | 53.33%  |
| NVMe | 21        | 28     | 28%     |
| SAS  | 7         | 8      | 9.33%   |
| MMC  | 7         | 9      | 9.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 48     | 64.29%  |
| 0.51-1.0   | 12        | 13     | 21.43%  |
| 1.01-2.0   | 5         | 6      | 8.93%   |
| 3.01-4.0   | 3         | 3      | 5.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 35.09%  |
| 251-500        | 15        | 26.32%  |
| 51-100         | 7         | 12.28%  |
| 1001-2000      | 4         | 7.02%   |
| 501-1000       | 4         | 7.02%   |
| 1-20           | 3         | 5.26%   |
| More than 3000 | 2         | 3.51%   |
| 21-50          | 2         | 3.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 17        | 29.82%  |
| 21-50     | 15        | 26.32%  |
| 51-100    | 10        | 17.54%  |
| 101-250   | 6         | 10.53%  |
| 251-500   | 4         | 7.02%   |
| 501-1000  | 3         | 5.26%   |
| 2001-3000 | 1         | 1.75%   |
| 1001-2000 | 1         | 1.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 50%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 37        | 70     | 57.81%  |
| Works    | 25        | 39     | 39.06%  |
| Malfunc  | 2         | 2      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 33        | 46.48%  |
| AMD                         | 13        | 18.31%  |
| Samsung Electronics         | 4         | 5.63%   |
| SanDisk                     | 3         | 4.23%   |
| Nvidia                      | 3         | 4.23%   |
| Kingston Technology Company | 3         | 4.23%   |
| Phison Electronics          | 2         | 2.82%   |
| Transcend                   | 1         | 1.41%   |
| SK hynix                    | 1         | 1.41%   |
| Seagate Technology          | 1         | 1.41%   |
| Realtek Semiconductor       | 1         | 1.41%   |
| OCZ Technology Group        | 1         | 1.41%   |
| Micron Technology           | 1         | 1.41%   |
| Marvell Technology Group    | 1         | 1.41%   |
| KIOXIA                      | 1         | 1.41%   |
| JMicron Technology          | 1         | 1.41%   |
| ADATA Technology            | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 9         | 10.98%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 6         | 7.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 3         | 3.66%   |
| Intel Non-Volatile memory controller                                          | 3         | 3.66%   |
| Phison PS5013 E13 NVMe Controller                                             | 2         | 2.44%   |
| Nvidia MCP79 AHCI Controller                                                  | 2         | 2.44%   |
| Intel Volume Management Device NVMe RAID Controller                           | 2         | 2.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 2.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 2         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 2.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                 | 2         | 2.44%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                 | 2         | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 2         | 2.44%   |
| Transcend Non-Volatile memory controller                                      | 1         | 1.22%   |
| SK hynix Gold P31 SSD                                                         | 1         | 1.22%   |
| Seagate Non-Volatile memory controller                                        | 1         | 1.22%   |
| SanDisk WD Blue SN570 NVMe SSD                                                | 1         | 1.22%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 1.22%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 1.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 1.22%   |
| Realtek Realtek Non-Volatile memory controller                                | 1         | 1.22%   |
| OCZ Group RD400/400A SSD                                                      | 1         | 1.22%   |
| Nvidia MCP61 SATA Controller                                                  | 1         | 1.22%   |
| Micron Non-Volatile memory controller                                         | 1         | 1.22%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                  | 1         | 1.22%   |
| KIOXIA NVMe SSD Controller BG4                                                | 1         | 1.22%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 1.22%   |
| Kingston Company OM3PDP3 NVMe SSD                                             | 1         | 1.22%   |
| Kingston Company A2000 NVMe SSD                                               | 1         | 1.22%   |
| JMicron JMB363 SATA/IDE Controller                                            | 1         | 1.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 1         | 1.22%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 1.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.22%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 1         | 1.22%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 1.22%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 1.22%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 1         | 1.22%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                    | 1         | 1.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 41        | 56.16%  |
| NVMe | 21        | 28.77%  |
| IDE  | 7         | 9.59%   |
| RAID | 4         | 5.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 43        | 75.44%  |
| AMD    | 14        | 24.56%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 4         | 7.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 2         | 3.51%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz     | 2         | 3.51%   |
| Intel Atom CPU Z3795 @ 1.60GHz           | 2         | 3.51%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz      | 1         | 1.75%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 1.75%   |
| Intel Pentium CPU 5405U @ 2.30GHz        | 1         | 1.75%   |
| Intel Core i9-10900K CPU @ 3.70GHz       | 1         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 1         | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 1         | 1.75%   |
| Intel Core i7-3610QM CPU @ 2.30GHz       | 1         | 1.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 1         | 1.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 1.75%   |
| Intel Core i7 CPU 860 @ 2.80GHz          | 1         | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 1.75%   |
| Intel Core i5-7360U CPU @ 2.30GHz        | 1         | 1.75%   |
| Intel Core i5-6400 CPU @ 2.70GHz         | 1         | 1.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 1         | 1.75%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz       | 1         | 1.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 1         | 1.75%   |
| Intel Core i5-4590T CPU @ 2.00GHz        | 1         | 1.75%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 1         | 1.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1         | 1.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 1         | 1.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 1.75%   |
| Intel Core i5-2415M CPU @ 2.30GHz        | 1         | 1.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 1         | 1.75%   |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 1         | 1.75%   |
| Intel Core i3-3225 CPU @ 3.30GHz         | 1         | 1.75%   |
| Intel Core i3-10110U CPU @ 2.10GHz       | 1         | 1.75%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz     | 1         | 1.75%   |
| Intel Celeron N4500 @ 1.10GHz            | 1         | 1.75%   |
| Intel Celeron N4020 CPU @ 1.10GHz        | 1         | 1.75%   |
| Intel Celeron G4900T CPU @ 2.90GHz       | 1         | 1.75%   |
| Intel Celeron CPU N3350 @ 1.10GHz        | 1         | 1.75%   |
| Intel Atom x5-Z8330 CPU @ 1.44GHz        | 1         | 1.75%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz   | 1         | 1.75%   |
| AMD Ryzen 9 5900X 12-Core Processor      | 1         | 1.75%   |
| AMD Ryzen 7 5800H with Radeon Graphics   | 1         | 1.75%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 16        | 28.07%  |
| Intel Core i7        | 6         | 10.53%  |
| Other                | 5         | 8.77%   |
| AMD Ryzen 5          | 5         | 8.77%   |
| Intel Celeron        | 4         | 7.02%   |
| Intel Core 2 Duo     | 3         | 5.26%   |
| Intel Atom           | 3         | 5.26%   |
| Intel Core i3        | 2         | 3.51%   |
| Intel Xeon           | 1         | 1.75%   |
| Intel Pentium Silver | 1         | 1.75%   |
| Intel Pentium        | 1         | 1.75%   |
| Intel Core i9        | 1         | 1.75%   |
| AMD Ryzen 9          | 1         | 1.75%   |
| AMD Ryzen 7          | 1         | 1.75%   |
| AMD Phenom II X4     | 1         | 1.75%   |
| AMD FX               | 1         | 1.75%   |
| AMD Athlon II X3     | 1         | 1.75%   |
| AMD Athlon           | 1         | 1.75%   |
| AMD A8               | 1         | 1.75%   |
| AMD A4               | 1         | 1.75%   |
| AMD A10              | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 25        | 43.86%  |
| 2      | 23        | 40.35%  |
| 6      | 4         | 7.02%   |
| 12     | 1         | 1.75%   |
| 10     | 1         | 1.75%   |
| 8      | 1         | 1.75%   |
| 3      | 1         | 1.75%   |
| 1      | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 57        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 38        | 66.67%  |
| 1      | 19        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 53.45%  |
| 0x806c1    | 3         | 5.17%   |
| 0x306a9    | 2         | 3.45%   |
| 0x206a7    | 2         | 3.45%   |
| 0x0a50000c | 2         | 3.45%   |
| 0x08108102 | 2         | 3.45%   |
| 0xa0671    | 1         | 1.72%   |
| 0x906eb    | 1         | 1.72%   |
| 0x806ec    | 1         | 1.72%   |
| 0x806eb    | 1         | 1.72%   |
| 0x706a8    | 1         | 1.72%   |
| 0x506c9    | 1         | 1.72%   |
| 0x406f1    | 1         | 1.72%   |
| 0x406c4    | 1         | 1.72%   |
| 0x40651    | 1         | 1.72%   |
| 0x306d4    | 1         | 1.72%   |
| 0x30678    | 1         | 1.72%   |
| 0x20655    | 1         | 1.72%   |
| 0x1067a    | 1         | 1.72%   |
| 0x08600106 | 1         | 1.72%   |
| 0x07030104 | 1         | 1.72%   |
| 0x06001119 | 1         | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 17.54%  |
| Zen+          | 4         | 7.02%   |
| TigerLake     | 4         | 7.02%   |
| IvyBridge     | 4         | 7.02%   |
| Zen 3         | 3         | 5.26%   |
| Skylake       | 3         | 5.26%   |
| Silvermont    | 3         | 5.26%   |
| Penryn        | 3         | 5.26%   |
| Haswell       | 3         | 5.26%   |
| SandyBridge   | 2         | 3.51%   |
| K10           | 2         | 3.51%   |
| Icelake       | 2         | 3.51%   |
| Goldmont plus | 2         | 3.51%   |
| Broadwell     | 2         | 3.51%   |
| Zen 2         | 1         | 1.75%   |
| Westmere      | 1         | 1.75%   |
| Steamroller   | 1         | 1.75%   |
| Puma          | 1         | 1.75%   |
| Piledriver    | 1         | 1.75%   |
| Nehalem       | 1         | 1.75%   |
| Goldmont      | 1         | 1.75%   |
| CometLake     | 1         | 1.75%   |
| Bulldozer     | 1         | 1.75%   |
| Unknown       | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 37        | 54.41%  |
| Nvidia | 16        | 23.53%  |
| AMD    | 15        | 22.06%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 5.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 4.29%   |
| Intel UHD Graphics 620                                                      | 2         | 2.86%   |
| Intel HD Graphics 620                                                       | 2         | 2.86%   |
| Intel HD Graphics 530                                                       | 2         | 2.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 2.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 2.86%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 2         | 2.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2         | 2.86%   |
| AMD Cezanne                                                                 | 2         | 2.86%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                      | 1         | 1.43%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 1.43%   |
| Nvidia GP108M [GeForce MX230]                                               | 1         | 1.43%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 1.43%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 1.43%   |
| Nvidia GP104GL [Quadro P4000]                                               | 1         | 1.43%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 1.43%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.43%   |
| Nvidia GK208BM [GeForce 920M]                                               | 1         | 1.43%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1         | 1.43%   |
| Nvidia GF110 [GeForce GTX 570]                                              | 1         | 1.43%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 1         | 1.43%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1         | 1.43%   |
| Nvidia C79 [GeForce 9400]                                                   | 1         | 1.43%   |
| Nvidia C79 [GeForce 9400M]                                                  | 1         | 1.43%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1         | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 1.43%   |
| Intel JasperLake [UHD Graphics]                                             | 1         | 1.43%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1         | 1.43%   |
| Intel Iris Plus Graphics G7                                                 | 1         | 1.43%   |
| Intel Iris Plus Graphics 640                                                | 1         | 1.43%   |
| Intel HD Graphics 5500                                                      | 1         | 1.43%   |
| Intel HD Graphics 500                                                       | 1         | 1.43%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1         | 1.43%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 1.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 43.86%  |
| 1 x AMD        | 11        | 19.3%   |
| 1 x Nvidia     | 8         | 14.04%  |
| Intel + Nvidia | 7         | 12.28%  |
| Intel + AMD    | 2         | 3.51%   |
| Other          | 1         | 1.75%   |
| 2 x Intel      | 1         | 1.75%   |
| 2 x AMD        | 1         | 1.75%   |
| AMD + Nvidia   | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 47        | 82.46%  |
| Proprietary | 8         | 14.04%  |
| Unknown     | 2         | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 73.68%  |
| 1.01-2.0   | 6         | 10.53%  |
| 7.01-8.0   | 3         | 5.26%   |
| 0.01-0.5   | 3         | 5.26%   |
| 0.51-1.0   | 2         | 3.51%   |
| 3.01-4.0   | 1         | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 11        | 17.74%  |
| Samsung Electronics     | 10        | 16.13%  |
| BOE                     | 7         | 11.29%  |
| AU Optronics            | 6         | 9.68%   |
| Hewlett-Packard         | 4         | 6.45%   |
| Apple                   | 4         | 6.45%   |
| SANYO                   | 2         | 3.23%   |
| Philips                 | 2         | 3.23%   |
| LG Display              | 2         | 3.23%   |
| Goldstar                | 2         | 3.23%   |
| Vestel Elektronik       | 1         | 1.61%   |
| Unknown (XXX)           | 1         | 1.61%   |
| Unknown (AAA)           | 1         | 1.61%   |
| Sharp                   | 1         | 1.61%   |
| ONN                     | 1         | 1.61%   |
| Lenovo                  | 1         | 1.61%   |
| IBM                     | 1         | 1.61%   |
| Fujitsu Siemens         | 1         | 1.61%   |
| Dell                    | 1         | 1.61%   |
| Chi Mei Optoelectronics | 1         | 1.61%   |
| BenQ                    | 1         | 1.61%   |
| AOC                     | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 3.17%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 1         | 1.59%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1         | 1.59%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch              | 1         | 1.59%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 1.59%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1         | 1.59%   |
| SANYO LCD SAN0A12 1920x540                                            | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch  | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 1         | 1.59%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1         | 1.59%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch     | 1         | 1.59%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 1.59%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 480x270mm 21.7-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 1.59%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1         | 1.59%   |
| Philips PHL 241B7Q PHL0909 1920x1080 530x300mm 24.0-inch              | 1         | 1.59%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch               | 1         | 1.59%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                   | 1         | 1.59%   |
| ONN ONN50 ONN3458 3840x2160 575x323mm 26.0-inch                       | 1         | 1.59%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch           | 1         | 1.59%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch              | 1         | 1.59%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                 | 1         | 1.59%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 1         | 1.59%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1         | 1.59%   |
| Hewlett-Packard ALL-in-One HPN401E 1920x1080 476x268mm 21.5-inch      | 1         | 1.59%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1         | 1.59%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 1.59%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1         | 1.59%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 1         | 1.59%   |
| Dell LCD Monitor 1704FPV 1280x1024                                    | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch      | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 26        | 44.07%  |
| 1366x768 (WXGA)    | 11        | 18.64%  |
| 3840x2160 (4K)     | 5         | 8.47%   |
| 1920x1200 (WUXGA)  | 3         | 5.08%   |
| 1680x1050 (WSXGA+) | 3         | 5.08%   |
| 1280x800 (WXGA)    | 3         | 5.08%   |
| 1920x540           | 2         | 3.39%   |
| 1600x900 (HD+)     | 2         | 3.39%   |
| 2880x1800          | 1         | 1.69%   |
| 2560x1440 (QHD)    | 1         | 1.69%   |
| 1440x900 (WXGA+)   | 1         | 1.69%   |
| 1280x1024 (SXGA)   | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 23.81%  |
| 13      | 8         | 12.7%   |
| 24      | 6         | 9.52%   |
| 27      | 5         | 7.94%   |
| 21      | 5         | 7.94%   |
| 23      | 4         | 6.35%   |
| 17      | 4         | 6.35%   |
| 14      | 4         | 6.35%   |
| 40      | 2         | 3.17%   |
| 11      | 2         | 3.17%   |
| Unknown | 2         | 3.17%   |
| 84      | 1         | 1.59%   |
| 54      | 1         | 1.59%   |
| 33      | 1         | 1.59%   |
| 26      | 1         | 1.59%   |
| 18      | 1         | 1.59%   |
| 10      | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 37.1%   |
| 501-600     | 14        | 22.58%  |
| 401-500     | 7         | 11.29%  |
| 201-300     | 7         | 11.29%  |
| 351-400     | 4         | 6.45%   |
| 801-900     | 2         | 3.23%   |
| Unknown     | 2         | 3.23%   |
| 701-800     | 1         | 1.61%   |
| 1501-2000   | 1         | 1.61%   |
| 1001-1500   | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 44        | 77.19%  |
| 16/10   | 10        | 17.54%  |
| 32/9    | 1         | 1.75%   |
| 3/2     | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 24.59%  |
| 81-90          | 10        | 16.39%  |
| 201-250        | 10        | 16.39%  |
| 301-350        | 5         | 8.2%    |
| 121-130        | 4         | 6.56%   |
| 251-300        | 3         | 4.92%   |
| More than 1000 | 2         | 3.28%   |
| 71-80          | 2         | 3.28%   |
| 51-60          | 2         | 3.28%   |
| 501-1000       | 2         | 3.28%   |
| Unknown        | 2         | 3.28%   |
| 351-500        | 1         | 1.64%   |
| 41-50          | 1         | 1.64%   |
| 151-200        | 1         | 1.64%   |
| 141-150        | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 18        | 29.51%  |
| 101-120       | 16        | 26.23%  |
| 121-160       | 14        | 22.95%  |
| 161-240       | 5         | 8.2%    |
| More than 240 | 4         | 6.56%   |
| 1-50          | 2         | 3.28%   |
| Unknown       | 2         | 3.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 48        | 84.21%  |
| 2     | 8         | 14.04%  |
| 0     | 1         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 36.59%  |
| Realtek Semiconductor | 27        | 32.93%  |
| Broadcom              | 8         | 9.76%   |
| Qualcomm Atheros      | 7         | 8.54%   |
| Nvidia                | 3         | 3.66%   |
| MediaTek              | 3         | 3.66%   |
| Hewlett-Packard       | 2         | 2.44%   |
| Broadcom Limited      | 1         | 1.22%   |
| ASIX Electronics      | 1         | 1.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 16        | 16.84%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 4.21%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 4.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 3.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 3.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 3.16%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 3.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 3.16%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 2.11%   |
| Intel Wireless 8260                                                     | 2         | 2.11%   |
| Intel Wireless 7265                                                     | 2         | 2.11%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 2.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.11%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.11%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.05%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.05%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 1.05%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.05%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 1.05%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.05%   |
| Nvidia MCP61 Ethernet                                                   | 1         | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.05%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.05%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.05%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.05%   |
| Intel Wireless 7260                                                     | 1         | 1.05%   |
| Intel Wireless 3165                                                     | 1         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.05%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.05%   |
| Intel Ethernet Controller I225-V                                        | 1         | 1.05%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 1.05%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.05%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 48.98%  |
| Broadcom              | 8         | 16.33%  |
| Realtek Semiconductor | 7         | 14.29%  |
| Qualcomm Atheros      | 5         | 10.2%   |
| MediaTek              | 3         | 6.12%   |
| Hewlett-Packard       | 1         | 2.04%   |
| Broadcom Limited      | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 8.16%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 8.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 6.12%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 6.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 6.12%   |
| Intel Wireless 8260                                                     | 2         | 4.08%   |
| Intel Wireless 7265                                                     | 2         | 4.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 4.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 4.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 4.08%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.04%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.04%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 2.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 2.04%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 2.04%   |
| Intel Wireless-AC 9260                                                  | 1         | 2.04%   |
| Intel Wireless 8265 / 8275                                              | 1         | 2.04%   |
| Intel Wireless 7260                                                     | 1         | 2.04%   |
| Intel Wireless 3165                                                     | 1         | 2.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 2.04%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 2.04%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 2.04%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 2.04%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 2.04%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 1         | 2.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 2.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 53.33%  |
| Intel                 | 11        | 24.44%  |
| Nvidia                | 3         | 6.67%   |
| Broadcom              | 3         | 6.67%   |
| Qualcomm Atheros      | 2         | 4.44%   |
| Hewlett-Packard       | 1         | 2.22%   |
| ASIX Electronics      | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 34.78%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 6.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 6.52%   |
| Nvidia MCP79 Ethernet                                             | 2         | 4.35%   |
| Intel I211 Gigabit Network Connection                             | 2         | 4.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 4.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.17%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 2.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.17%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.17%   |
| Intel Ethernet Controller I225-V                                  | 1         | 2.17%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 2.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 2.17%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 2.17%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.17%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.17%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 2.17%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.17%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 52.17%  |
| Ethernet | 44        | 47.83%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 65.52%  |
| Ethernet | 20        | 34.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 31        | 54.39%  |
| 1     | 24        | 42.11%  |
| 0     | 2         | 3.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 75.44%  |
| Yes  | 14        | 24.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 50%     |
| Apple                           | 5         | 12.5%   |
| Realtek Semiconductor           | 4         | 10%     |
| Broadcom                        | 3         | 7.5%    |
| Qualcomm Atheros Communications | 2         | 5%      |
| IMC Networks                    | 2         | 5%      |
| Unknown                         | 1         | 2.5%    |
| MediaTek                        | 1         | 2.5%    |
| Foxconn International           | 1         | 2.5%    |
| Dell                            | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 7         | 17.5%   |
| Intel AX201 Bluetooth                              | 4         | 10%     |
| Intel AX200 Bluetooth                              | 3         | 7.5%    |
| Apple Bluetooth USB Host Controller                | 3         | 7.5%    |
| Realtek Bluetooth Radio                            | 2         | 5%      |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 5%      |
| Intel Wireless-AC 3168 Bluetooth                   | 2         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 5%      |
| Apple Bluetooth Host Controller                    | 2         | 5%      |
| Unknown Bluetooth Device                           | 1         | 2.5%    |
| Realtek RTL8723B Bluetooth                         | 1         | 2.5%    |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 2.5%    |
| MediaTek Wireless_Device                           | 1         | 2.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 2.5%    |
| Intel AX210 Bluetooth                              | 1         | 2.5%    |
| IMC Networks Wireless_Device                       | 1         | 2.5%    |
| IMC Networks Bluetooth Radio                       | 1         | 2.5%    |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 2.5%    |
| Dell DW375 Bluetooth Module                        | 1         | 2.5%    |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 2.5%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 2.5%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 59.38%  |
| AMD                   | 15        | 23.44%  |
| Nvidia                | 9         | 14.06%  |
| Realtek Semiconductor | 1         | 1.56%   |
| Plantronics           | 1         | 1.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 7.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 7.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 5.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.06%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 3.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 3.8%    |
| AMD FCH Azalia Controller                                                  | 3         | 3.8%    |
| Nvidia MCP79 High Definition Audio                                         | 2         | 2.53%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.53%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.53%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.53%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.27%   |
| Plantronics Blackwire 5220 Series                                          | 1         | 1.27%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.27%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.27%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.27%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.27%   |
| Nvidia GF110 High Definition Audio Controller                              | 1         | 1.27%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.27%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.27%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.27%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.27%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.27%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.27%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 10        | 27.03%  |
| Samsung Electronics | 10        | 27.03%  |
| Kingston            | 6         | 16.22%  |
| Crucial             | 3         | 8.11%   |
| Unknown (ABCD)      | 1         | 2.7%    |
| Unknown             | 1         | 2.7%    |
| Teikon              | 1         | 2.7%    |
| Micron Technology   | 1         | 2.7%    |
| fef5                | 1         | 2.7%    |
| Elpida              | 1         | 2.7%    |
| Corsair             | 1         | 2.7%    |
| Unknown             | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 5.13%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 2.56%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 2.56%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 2.56%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.56%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 2.56%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 2.56%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 2.56%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 2.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.56%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 2.56%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 2.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 1         | 2.56%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 2.56%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 2.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.56%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 2.56%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.56%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 2.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.56%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 2.56%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB 2400MT/s                         | 1         | 2.56%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.56%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 2.56%   |
| Kingston RAM 9905624-059.A00G 8GB SODIMM DDR4 2667MT/s           | 1         | 2.56%   |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s                | 1         | 2.56%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 2.56%   |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                            | 1         | 2.56%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 1         | 2.56%   |
| Crucial RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 2.56%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s           | 1         | 2.56%   |
| Crucial RAM CT8G4SFD824A.M16FF 8GB SODIMM DDR4 2400MT/s          | 1         | 2.56%   |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s              | 1         | 2.56%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s              | 1         | 2.56%   |
| Unknown                                                          | 1         | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 16        | 48.48%  |
| DDR3    | 10        | 30.3%   |
| LPDDR4  | 5         | 15.15%  |
| SDRAM   | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 19        | 63.33%  |
| DIMM         | 6         | 20%     |
| Row Of Chips | 3         | 10%     |
| Chip         | 1         | 3.33%   |
| Unknown      | 1         | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 14        | 43.75%  |
| 4096  | 9         | 28.13%  |
| 16384 | 4         | 12.5%   |
| 2048  | 3         | 9.38%   |
| 32768 | 1         | 3.13%   |
| 1024  | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 7         | 20.59%  |
| 3200  | 6         | 17.65%  |
| 2667  | 6         | 17.65%  |
| 2400  | 6         | 17.65%  |
| 4267  | 2         | 5.88%   |
| 1067  | 2         | 5.88%   |
| 3266  | 1         | 2.94%   |
| 2133  | 1         | 2.94%   |
| 1334  | 1         | 2.94%   |
| 1333  | 1         | 2.94%   |
| 1066  | 1         | 2.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung ML-1510 Laser Printer | 1         | 33.33%  |
| HP LaserJet 1320              | 1         | 33.33%  |
| Canon LiDE 400                | 1         | 33.33%  |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 27.27%  |
| Realtek Semiconductor                  | 4         | 12.12%  |
| Apple                                  | 4         | 12.12%  |
| Syntek                                 | 3         | 9.09%   |
| IMC Networks                           | 3         | 9.09%   |
| Logitech                               | 2         | 6.06%   |
| Unknown                                | 1         | 3.03%   |
| Sunplus Innovation Technology          | 1         | 3.03%   |
| Samsung Electronics                    | 1         | 3.03%   |
| Quanta                                 | 1         | 3.03%   |
| Luxvisions Innotech Limited            | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.03%   |
| Alcor Micro                            | 1         | 3.03%   |
| Acer                                   | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                       | 2         | 6.06%   |
| Realtek Integrated_Webcam_HD                                   | 2         | 6.06%   |
| Logitech HD Pro Webcam C920                                    | 2         | 6.06%   |
| Chicony Integrated Camera                                      | 2         | 6.06%   |
| Apple FaceTime HD Camera                                       | 2         | 6.06%   |
| Unknown ATIV VGA CAMERA                                        | 1         | 3.03%   |
| Syntek Lenovo EasyCamera                                       | 1         | 3.03%   |
| Sunplus HD WebCam                                              | 1         | 3.03%   |
| Samsung Galaxy A5 (MTP)                                        | 1         | 3.03%   |
| Realtek Lenovo EasyCamera                                      | 1         | 3.03%   |
| Realtek Integrated Webcam                                      | 1         | 3.03%   |
| Quanta USB2.0 HD UVC WebCam                                    | 1         | 3.03%   |
| Luxvisions Innotech Limited HP HD Camera                       | 1         | 3.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 3.03%   |
| IMC Networks Integrated Camera                                 | 1         | 3.03%   |
| Chicony XiaoMi USB 2.0 Webcam                                  | 1         | 3.03%   |
| Chicony USB2.0 Camera                                          | 1         | 3.03%   |
| Chicony HP Wide Vision FHD Camera                              | 1         | 3.03%   |
| Chicony HP Truevision HD camera                                | 1         | 3.03%   |
| Chicony HP Integrated Webcam                                   | 1         | 3.03%   |
| Chicony HP HD Camera                                           | 1         | 3.03%   |
| Chicony HD Webcam                                              | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.03%   |
| Apple FaceTime HD Camera (Built-in)                            | 1         | 3.03%   |
| Apple Built-in iSight                                          | 1         | 3.03%   |
| Alcor Micro SHUNCCM2MP                                         | 1         | 3.03%   |
| Acer EasyCamera                                                | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 42.86%  |
| Validity Sensors           | 2         | 28.57%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |
| Elan Microelectronics      | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 2         | 28.57%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 14.29%  |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device               | 1         | 14.29%  |
| Elan ELAN:Fingerprint                             | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 38        | 66.67%  |
| 1     | 13        | 22.81%  |
| 2     | 3         | 5.26%   |
| 6     | 1         | 1.75%   |
| 4     | 1         | 1.75%   |
| 3     | 1         | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 25.93%  |
| Net/wireless             | 4         | 14.81%  |
| Graphics card            | 4         | 14.81%  |
| Sound                    | 3         | 11.11%  |
| Chipcard                 | 2         | 7.41%   |
| Camera                   | 2         | 7.41%   |
| Unassigned class         | 1         | 3.7%    |
| Net/ethernet             | 1         | 3.7%    |
| Multimedia controller    | 1         | 3.7%    |
| Communication controller | 1         | 3.7%    |
| Bluetooth                | 1         | 3.7%    |

