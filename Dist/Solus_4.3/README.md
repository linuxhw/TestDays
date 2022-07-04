Solus 4.3 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Solus 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Solus_4.3/Desktop/README.md) and [notebooks](/Dist/Solus_4.3/Notebook/README.md).

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

Total: 76

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo     | CRESCENTBAY 31900058 STD    | Desktop     | [f42a689093](https://linux-hardware.org/?probe=f42a689093) | Jun 10, 2022 |
| HP         | ProBook 450 G5              | Notebook    | [c4880f9bab](https://linux-hardware.org/?probe=c4880f9bab) | Jun 02, 2022 |
| HP         | ProBook 455 G8 Notebook ... | Notebook    | [5330a5aa11](https://linux-hardware.org/?probe=5330a5aa11) | Jun 02, 2022 |
| Gigabyte   | Z68AP-D3                    | Desktop     | [90b0bc8a37](https://linux-hardware.org/?probe=90b0bc8a37) | Jun 02, 2022 |
| HP         | ProBook 450 G5              | Notebook    | [7f8acf64cd](https://linux-hardware.org/?probe=7f8acf64cd) | May 31, 2022 |
| HP         | ProBook 450 G5              | Notebook    | [2fbbe84744](https://linux-hardware.org/?probe=2fbbe84744) | May 31, 2022 |
| Google     | Edgar                       | Notebook    | [fef9eeb5db](https://linux-hardware.org/?probe=fef9eeb5db) | May 02, 2022 |
| ASUSTek    | B85M-E                      | Desktop     | [31572b098d](https://linux-hardware.org/?probe=31572b098d) | Apr 24, 2022 |
| ASUSTek    | B85M-E                      | Desktop     | [037b7180fd](https://linux-hardware.org/?probe=037b7180fd) | Apr 23, 2022 |
| Lenovo     | Z50-70 20354                | Notebook    | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | Desktop     | [8e0d54760d](https://linux-hardware.org/?probe=8e0d54760d) | Apr 22, 2022 |
| MSI        | B450M MORTAR                | Desktop     | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| Dell       | XPS 13 7390                 | Notebook    | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Gigabyte   | F2A68HM-H                   | Desktop     | [68eec83e55](https://linux-hardware.org/?probe=68eec83e55) | Apr 15, 2022 |
| Fujitsu    | D3227-A1 S26361-D3227-A1    | Desktop     | [e60647876c](https://linux-hardware.org/?probe=e60647876c) | Apr 13, 2022 |
| ASRock     | B450 Gaming-ITX/ac          | Desktop     | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| ASRock     | H81 Pro BTC R2.0            | Desktop     | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock     | H81 Pro BTC R2.0            | Desktop     | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| Gigabyte   | GA-MA770-UD3                | Desktop     | [18063bba4f](https://linux-hardware.org/?probe=18063bba4f) | Apr 10, 2022 |
| Unknown    | HX90                        | Desktop     | [ab8a381a52](https://linux-hardware.org/?probe=ab8a381a52) | Apr 08, 2022 |
| Unknown    | HX90                        | Desktop     | [a83217f763](https://linux-hardware.org/?probe=a83217f763) | Apr 07, 2022 |
| Unknown    | HX90                        | Desktop     | [fa9981d1bd](https://linux-hardware.org/?probe=fa9981d1bd) | Apr 07, 2022 |
| Lenovo     | ThinkPad T15 Gen 2i 20W4... | Notebook    | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Lenovo     | ThinkPad T15 Gen 2i 20W4... | Notebook    | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Dell       | XPS 13 9380                 | Notebook    | [efc6123d49](https://linux-hardware.org/?probe=efc6123d49) | Mar 06, 2022 |
| Google     | Delbin                      | Notebook    | [fbf8763bd4](https://linux-hardware.org/?probe=fbf8763bd4) | Feb 05, 2022 |
| Acer       | Aspire A315-54              | Notebook    | [5eb9b9e574](https://linux-hardware.org/?probe=5eb9b9e574) | Jan 22, 2022 |
| ASUSTek    | A88X-PRO                    | Desktop     | [fb6f0426c3](https://linux-hardware.org/?probe=fb6f0426c3) | Jan 20, 2022 |
| ASRock     | H81 Pro BTC R2.0            | Desktop     | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock     | H81 Pro BTC R2.0            | Desktop     | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock     | H81 Pro BTC R2.0            | Desktop     | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Acer       | Swift SF114-34              | Notebook    | [15431686d8](https://linux-hardware.org/?probe=15431686d8) | Jan 06, 2022 |
| Toshiba    | TECRA R840                  | Notebook    | [753c7caef6](https://linux-hardware.org/?probe=753c7caef6) | Dec 27, 2021 |
| Dell       | 06X1TJ A00                  | Desktop     | [315e535dd5](https://linux-hardware.org/?probe=315e535dd5) | Dec 21, 2021 |
| Sony       | VPCYB15AB                   | Notebook    | [780ef18db3](https://linux-hardware.org/?probe=780ef18db3) | Dec 13, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | Desktop     | [d65256bf72](https://linux-hardware.org/?probe=d65256bf72) | Dec 12, 2021 |
| Dell       | Latitude 5580               | Notebook    | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Gigabyte   | H110M-DS2V-CF               | Desktop     | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte   | H110M-DS2V-CF               | Desktop     | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MEGA       | G41T-M7 LGT                 | Desktop     | [7238b4cd22](https://linux-hardware.org/?probe=7238b4cd22) | Nov 21, 2021 |
| Gigabyte   | B85M-D3H                    | Desktop     | [7119b7f25b](https://linux-hardware.org/?probe=7119b7f25b) | Nov 19, 2021 |
| Framework  | Laptop                      | Notebook    | [7995a7a4de](https://linux-hardware.org/?probe=7995a7a4de) | Nov 18, 2021 |
| MSI        | B350 TOMAHAWK ARCTIC        | Desktop     | [9cc745f754](https://linux-hardware.org/?probe=9cc745f754) | Nov 16, 2021 |
| Dell       | Latitude E6220              | Notebook    | [09a75055c9](https://linux-hardware.org/?probe=09a75055c9) | Nov 12, 2021 |
| ASRock     | X470 Master SLI             | Desktop     | [7058d85808](https://linux-hardware.org/?probe=7058d85808) | Nov 11, 2021 |
| Framework  | Laptop                      | Notebook    | [72a07a2e81](https://linux-hardware.org/?probe=72a07a2e81) | Nov 11, 2021 |
| HP         | 805F                        | Desktop     | [f7bfb95642](https://linux-hardware.org/?probe=f7bfb95642) | Oct 26, 2021 |
| LattePanda | Alpha                       | Desktop     | [cfe529288b](https://linux-hardware.org/?probe=cfe529288b) | Oct 26, 2021 |
| Biostar    | H61MLV2                     | Desktop     | [118f61b356](https://linux-hardware.org/?probe=118f61b356) | Oct 23, 2021 |
| AZW        | SEi                         | Notebook    | [0e29003348](https://linux-hardware.org/?probe=0e29003348) | Oct 18, 2021 |
| ASUSTek    | VivoBook_ASUSLaptop X509... | Notebook    | [c7f1620c1c](https://linux-hardware.org/?probe=c7f1620c1c) | Oct 05, 2021 |
| HP         | OMEN Laptop 15-en0xxx       | Notebook    | [f19ad7cba2](https://linux-hardware.org/?probe=f19ad7cba2) | Sep 16, 2021 |
| HP         | OMEN Laptop 15-en0xxx       | Notebook    | [1cca1c6ce5](https://linux-hardware.org/?probe=1cca1c6ce5) | Sep 13, 2021 |
| HP         | OMEN Laptop 15-en0xxx       | Notebook    | [888bf75e20](https://linux-hardware.org/?probe=888bf75e20) | Sep 13, 2021 |
| Gigabyte   | GA-78LMT-USB3               | Desktop     | [99c69c213a](https://linux-hardware.org/?probe=99c69c213a) | Sep 05, 2021 |
| Acer       | Nitro AN515-45              | Notebook    | [5bad88330d](https://linux-hardware.org/?probe=5bad88330d) | Sep 01, 2021 |
| ASUSTek    | TUF B450-PRO GAMING         | Desktop     | [f7d38e2f91](https://linux-hardware.org/?probe=f7d38e2f91) | Aug 29, 2021 |
| Dell       | Inspiron 1525               | Notebook    | [3f3cd9c9e2](https://linux-hardware.org/?probe=3f3cd9c9e2) | Aug 25, 2021 |
| Dell       | Inspiron 1525               | Notebook    | [de3cb038ef](https://linux-hardware.org/?probe=de3cb038ef) | Aug 25, 2021 |
| Gigabyte   | P31-ES3G                    | Desktop     | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte   | P31-ES3G                    | Desktop     | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| Acer       | Nitro AN515-45              | Notebook    | [d98d816e7f](https://linux-hardware.org/?probe=d98d816e7f) | Aug 18, 2021 |
| eMachines  | EL1852G                     | Desktop     | [7683cbf5bb](https://linux-hardware.org/?probe=7683cbf5bb) | Aug 16, 2021 |
| eMachines  | EL1852G                     | Desktop     | [86003fc5b7](https://linux-hardware.org/?probe=86003fc5b7) | Aug 15, 2021 |
| Apple      | Mac-B809C3757DA9BB8D iMa... | All in one  | [14f7d2a3c6](https://linux-hardware.org/?probe=14f7d2a3c6) | Aug 15, 2021 |
| Acer       | Nitro AN515-45              | Notebook    | [5320b136ea](https://linux-hardware.org/?probe=5320b136ea) | Aug 12, 2021 |
| Apple      | Mac-B809C3757DA9BB8D iMa... | All in one  | [488ebb20fc](https://linux-hardware.org/?probe=488ebb20fc) | Aug 08, 2021 |
| Dell       | Vostro 15-3568              | Notebook    | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| HP         | ProBook 650 G2              | Notebook    | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Gigabyte   | H81M-S2V                    | Desktop     | [16b2e8c32f](https://linux-hardware.org/?probe=16b2e8c32f) | Aug 06, 2021 |
| Gigabyte   | H81M-S2V                    | Desktop     | [db8fadad17](https://linux-hardware.org/?probe=db8fadad17) | Aug 06, 2021 |
| Dell       | Inspiron 15-3573            | Notebook    | [52916532a3](https://linux-hardware.org/?probe=52916532a3) | Aug 06, 2021 |
| MSI        | B450 GAMING PRO CARBON A... | Desktop     | [b6ae0cb479](https://linux-hardware.org/?probe=b6ae0cb479) | Aug 05, 2021 |
| Gigabyte   | B360M AORUS Gaming 3-CF     | Desktop     | [fc89bec579](https://linux-hardware.org/?probe=fc89bec579) | Jul 16, 2021 |
| Lenovo     | IdeaPad 320-15ISK 80XH      | Notebook    | [75ec31cefd](https://linux-hardware.org/?probe=75ec31cefd) | Jul 16, 2021 |
| Lenovo     | ThinkCentre M71e 3157G6S    | Desktop     | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.15.32-213.current | 8         | 15.69%  |
| 5.14.21-210.current | 7         | 13.73%  |
| 5.14.16-205.current | 6         | 11.76%  |
| 5.13.6-190.current  | 5         | 9.8%    |
| 5.13.12-193.current | 5         | 9.8%    |
| 5.13.1-187.current  | 5         | 9.8%    |
| 5.15.43-215.current | 2         | 3.92%   |
| 5.15.30-212.current | 2         | 3.92%   |
| 5.15.26-211.current | 2         | 3.92%   |
| 5.14.14-202.current | 2         | 3.92%   |
| 5.15.37-214.current | 1         | 1.96%   |
| 5.14.7-198.current  | 1         | 1.96%   |
| 5.14.16-204.current | 1         | 1.96%   |
| 5.14.15-203.current | 1         | 1.96%   |
| 5.14.12-201.current | 1         | 1.96%   |
| 5.13.8-191.current  | 1         | 1.96%   |
| 5.13.15-194.current | 1         | 1.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.32 | 8         | 15.69%  |
| 5.14.21 | 7         | 13.73%  |
| 5.14.16 | 7         | 13.73%  |
| 5.13.6  | 5         | 9.8%    |
| 5.13.12 | 5         | 9.8%    |
| 5.13.1  | 5         | 9.8%    |
| 5.15.43 | 2         | 3.92%   |
| 5.15.30 | 2         | 3.92%   |
| 5.15.26 | 2         | 3.92%   |
| 5.14.14 | 2         | 3.92%   |
| 5.15.37 | 1         | 1.96%   |
| 5.14.7  | 1         | 1.96%   |
| 5.14.15 | 1         | 1.96%   |
| 5.14.12 | 1         | 1.96%   |
| 5.13.8  | 1         | 1.96%   |
| 5.13.15 | 1         | 1.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 19        | 37.25%  |
| 5.13    | 17        | 33.33%  |
| 5.15    | 15        | 29.41%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 50        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Budgie  | 32        | 64%     |
| KDE5    | 5         | 10%     |
| GNOME   | 4         | 8%      |
| Unknown | 4         | 8%      |
| KDE     | 3         | 6%      |
| MATE    | 2         | 4%      |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 49        | 98%     |
| Wayland | 1         | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 74%     |
| LightDM | 8         | 16%     |
| SDDM    | 4         | 8%      |
| GDM     | 1         | 2%      |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 30        | 58.82%  |
| en_GB | 5         | 9.8%    |
| de_DE | 4         | 7.84%   |
| ru_RU | 2         | 3.92%   |
| pt_BR | 2         | 3.92%   |
| fr_FR | 2         | 3.92%   |
| nl_NL | 1         | 1.96%   |
| es_VE | 1         | 1.96%   |
| es_ES | 1         | 1.96%   |
| en_IN | 1         | 1.96%   |
| ar_SA | 1         | 1.96%   |
| ar_EG | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 28        | 54.9%   |
| BIOS | 23        | 45.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 48        | 96%     |
| Xfs   | 1         | 2%      |
| Btrfs | 1         | 2%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 38        | 76%     |
| GPT     | 8         | 16%     |
| MBR     | 4         | 8%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 94.12%  |
| Yes       | 3         | 5.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 80%     |
| Yes       | 10        | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Gigabyte Technology | 8         | 16%     |
| Dell                | 8         | 16%     |
| ASUSTek Computer    | 6         | 12%     |
| Lenovo              | 5         | 10%     |
| MSI                 | 3         | 6%      |
| Hewlett-Packard     | 3         | 6%      |
| Acer                | 3         | 6%      |
| Google              | 2         | 4%      |
| ASRock              | 2         | 4%      |
| Toshiba             | 1         | 2%      |
| Sony                | 1         | 2%      |
| MEGA                | 1         | 2%      |
| Fujitsu             | 1         | 2%      |
| Framework           | 1         | 2%      |
| eMachines           | 1         | 2%      |
| Biostar             | 1         | 2%      |
| AZW                 | 1         | 2%      |
| Apple               | 1         | 2%      |
| Unknown             | 1         | 2%      |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Toshiba TECRA R840                     | 1         | 2%      |
| Sony VPCYB15AB                         | 1         | 2%      |
| MSI MS-7B89                            | 1         | 2%      |
| MSI MS-7B85                            | 1         | 2%      |
| MSI MS-7A34                            | 1         | 2%      |
| MEGA G41T-M7 LGT                       | 1         | 2%      |
| Lenovo Z50-70 20354                    | 1         | 2%      |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW  | 1         | 2%      |
| Lenovo ThinkCentre M71e 3157G6S        | 1         | 2%      |
| Lenovo IdeaPad 320-15ISK 80XH          | 1         | 2%      |
| Lenovo C50-30 F0B1002EFR               | 1         | 2%      |
| HP ProDesk 490 G3 MT Business PC       | 1         | 2%      |
| HP ProBook 450 G5                      | 1         | 2%      |
| HP OMEN Laptop 15-en0xxx               | 1         | 2%      |
| Google Edgar                           | 1         | 2%      |
| Google Delbin                          | 1         | 2%      |
| Gigabyte Z68AP-D3                      | 1         | 2%      |
| Gigabyte P31-ES3G                      | 1         | 2%      |
| Gigabyte H81M-S2V                      | 1         | 2%      |
| Gigabyte H110M-DS2V                    | 1         | 2%      |
| Gigabyte GA-MA770-UD3                  | 1         | 2%      |
| Gigabyte GA-78LMT-USB3 6.0             | 1         | 2%      |
| Gigabyte F2A68HM-H                     | 1         | 2%      |
| Gigabyte B85M-D3H                      | 1         | 2%      |
| Fujitsu CELSIUS W530                   | 1         | 2%      |
| Framework Laptop                       | 1         | 2%      |
| eMachines EL1852G                      | 1         | 2%      |
| Dell XPS 13 9380                       | 1         | 2%      |
| Dell XPS 13 7390                       | 1         | 2%      |
| Dell Vostro 15-3568                    | 1         | 2%      |
| Dell OptiPlex 9020                     | 1         | 2%      |
| Dell Latitude E6220                    | 1         | 2%      |
| Dell Latitude 5580                     | 1         | 2%      |
| Dell Inspiron 1525                     | 1         | 2%      |
| Dell Inspiron 15-3573                  | 1         | 2%      |
| Biostar H61MLV2                        | 1         | 2%      |
| AZW SEi                                | 1         | 2%      |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 1         | 2%      |
| ASUS TUF Gaming X570-PRO               | 1         | 2%      |
| ASUS TUF B450-PRO GAMING               | 1         | 2%      |
| ASUS ROG STRIX B450-F GAMING           | 1         | 2%      |
| ASUS All Series                        | 1         | 2%      |
| ASUS A88X-PRO                          | 1         | 2%      |
| ASRock H81 Pro BTC R2.0                | 1         | 2%      |
| ASRock B450 Gaming-ITX/ac              | 1         | 2%      |
| Apple iMac17,1                         | 1         | 2%      |
| Acer Swift SF114-34                    | 1         | 2%      |
| Acer Nitro AN515-45                    | 1         | 2%      |
| Acer Aspire A315-54                    | 1         | 2%      |
| Unknown                                | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell XPS               | 2         | 4%      |
| Dell Latitude          | 2         | 4%      |
| Dell Inspiron          | 2         | 4%      |
| ASUS TUF               | 2         | 4%      |
| Toshiba TECRA          | 1         | 2%      |
| Sony VPCYB15AB         | 1         | 2%      |
| MSI MS-7B89            | 1         | 2%      |
| MSI MS-7B85            | 1         | 2%      |
| MSI MS-7A34            | 1         | 2%      |
| MEGA G41T-M7           | 1         | 2%      |
| Lenovo Z50-70          | 1         | 2%      |
| Lenovo ThinkPad        | 1         | 2%      |
| Lenovo ThinkCentre     | 1         | 2%      |
| Lenovo IdeaPad         | 1         | 2%      |
| Lenovo C50-30          | 1         | 2%      |
| HP ProDesk             | 1         | 2%      |
| HP ProBook             | 1         | 2%      |
| HP OMEN                | 1         | 2%      |
| Google Edgar           | 1         | 2%      |
| Google Delbin          | 1         | 2%      |
| Gigabyte Z68AP-D3      | 1         | 2%      |
| Gigabyte P31-ES3G      | 1         | 2%      |
| Gigabyte H81M-S2V      | 1         | 2%      |
| Gigabyte H110M-DS2V    | 1         | 2%      |
| Gigabyte GA-MA770-UD3  | 1         | 2%      |
| Gigabyte GA-78LMT-USB3 | 1         | 2%      |
| Gigabyte F2A68HM-H     | 1         | 2%      |
| Gigabyte B85M-D3H      | 1         | 2%      |
| Fujitsu CELSIUS        | 1         | 2%      |
| Framework Laptop       | 1         | 2%      |
| eMachines EL1852G      | 1         | 2%      |
| Dell Vostro            | 1         | 2%      |
| Dell OptiPlex          | 1         | 2%      |
| Biostar H61MLV2        | 1         | 2%      |
| AZW SEi                | 1         | 2%      |
| ASUS VivoBook          | 1         | 2%      |
| ASUS ROG               | 1         | 2%      |
| ASUS All               | 1         | 2%      |
| ASUS A88X-PRO          | 1         | 2%      |
| ASRock H81             | 1         | 2%      |
| ASRock B450            | 1         | 2%      |
| Apple iMac17           | 1         | 2%      |
| Acer Swift             | 1         | 2%      |
| Acer Nitro             | 1         | 2%      |
| Acer Aspire            | 1         | 2%      |
| Unknown                | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 7         | 14%     |
| 2014 | 6         | 12%     |
| 2011 | 6         | 12%     |
| 2021 | 5         | 10%     |
| 2019 | 5         | 10%     |
| 2020 | 4         | 8%      |
| 2017 | 4         | 8%      |
| 2016 | 3         | 6%      |
| 2015 | 3         | 6%      |
| 2008 | 3         | 6%      |
| 2013 | 2         | 4%      |
| 2012 | 1         | 2%      |
| 2010 | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 27        | 54%     |
| Notebook   | 22        | 44%     |
| All in one | 1         | 2%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 50        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 48        | 96%     |
| Yes  | 2         | 4%      |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 11        | 22%     |
| 3.01-4.0   | 10        | 20%     |
| 4.01-8.0   | 9         | 18%     |
| 8.01-16.0  | 9         | 18%     |
| 32.01-64.0 | 7         | 14%     |
| 2.01-3.0   | 2         | 4%      |
| 24.01-32.0 | 1         | 2%      |
| 1.01-2.0   | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 17        | 32.69%  |
| 1.01-2.0  | 15        | 28.85%  |
| 4.01-8.0  | 9         | 17.31%  |
| 3.01-4.0  | 8         | 15.38%  |
| 0.51-1.0  | 2         | 3.85%   |
| 8.01-16.0 | 1         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 52.94%  |
| 2      | 12        | 23.53%  |
| 4      | 7         | 13.73%  |
| 3      | 4         | 7.84%   |
| 5      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 64%     |
| Yes       | 18        | 36%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 86%     |
| No        | 7         | 14%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 68%     |
| No        | 16        | 32%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 62%     |
| No        | 19        | 38%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 11        | 22%     |
| Germany      | 5         | 10%     |
| India        | 4         | 8%      |
| Netherlands  | 3         | 6%      |
| Brazil       | 3         | 6%      |
| UK           | 2         | 4%      |
| Vietnam      | 1         | 2%      |
| Venezuela    | 1         | 2%      |
| Ukraine      | 1         | 2%      |
| Thailand     | 1         | 2%      |
| Switzerland  | 1         | 2%      |
| Sweden       | 1         | 2%      |
| Spain        | 1         | 2%      |
| Saudi Arabia | 1         | 2%      |
| Russia       | 1         | 2%      |
| Poland       | 1         | 2%      |
| Philippines  | 1         | 2%      |
| Norway       | 1         | 2%      |
| Nepal        | 1         | 2%      |
| Kazakhstan   | 1         | 2%      |
| Iran         | 1         | 2%      |
| Guyana       | 1         | 2%      |
| Greece       | 1         | 2%      |
| France       | 1         | 2%      |
| Canada       | 1         | 2%      |
| Belgium      | 1         | 2%      |
| Australia    | 1         | 2%      |
| Albania      | 1         | 2%      |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Yverdon-les-Bains | 1         | 2%      |
| Wendell           | 1         | 2%      |
| Weil am Rhein     | 1         | 2%      |
| Vineland          | 1         | 2%      |
| Vasco da Gama     | 1         | 2%      |
| Toronto           | 1         | 2%      |
| Thessaloniki      | 1         | 2%      |
| Stockholm         | 1         | 2%      |
| Stare Babice      | 1         | 2%      |
| Songkhla          | 1         | 2%      |
| Seville           | 1         | 2%      |
| Severna Park      | 1         | 2%      |
| Red Oak           | 1         | 2%      |
| Portsmouth        | 1         | 2%      |
| Phoenix           | 1         | 2%      |
| Oslo              | 1         | 2%      |
| Orenburg          | 1         | 2%      |
| Ochten            | 1         | 2%      |
| Mohali            | 1         | 2%      |
| Milwaukee         | 1         | 2%      |
| Miami             | 1         | 2%      |
| Melbourne         | 1         | 2%      |
| Lviv              | 1         | 2%      |
| Lipa City         | 1         | 2%      |
| Linter            | 1         | 2%      |
| Lexington         | 1         | 2%      |
| Krefeld           | 1         | 2%      |
| Kolkata           | 1         | 2%      |
| Kathmandu         | 1         | 2%      |
| Ilford            | 1         | 2%      |
| Huntington Park   | 1         | 2%      |
| Hanoi             | 1         | 2%      |
| Hamburg           | 1         | 2%      |
| Groningen         | 1         | 2%      |
| Greenwich         | 1         | 2%      |
| Goiânia          | 1         | 2%      |
| Georgetown        | 1         | 2%      |
| Essen             | 1         | 2%      |
| Durrës           | 1         | 2%      |
| Dammam            | 1         | 2%      |
| Curitiba          | 1         | 2%      |
| Coimbatore        | 1         | 2%      |
| Caracas           | 1         | 2%      |
| Caen              | 1         | 2%      |
| Belo Horizonte    | 1         | 2%      |
| Bad Homburg       | 1         | 2%      |
| Atyrau            | 1         | 2%      |
| Arak              | 1         | 2%      |
| Anacortes         | 1         | 2%      |
| Amsterdam         | 1         | 2%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 24     | 21.69%  |
| Samsung Electronics | 15        | 20     | 18.07%  |
| Seagate             | 8         | 8      | 9.64%   |
| Kingston            | 7         | 9      | 8.43%   |
| Toshiba             | 6         | 6      | 7.23%   |
| SanDisk             | 6         | 7      | 7.23%   |
| SK hynix            | 3         | 3      | 3.61%   |
| Crucial             | 3         | 3      | 3.61%   |
| Unknown             | 2         | 2      | 2.41%   |
| PNY                 | 2         | 2      | 2.41%   |
| Intel               | 2         | 3      | 2.41%   |
| Hitachi             | 2         | 2      | 2.41%   |
| Silicon Motion      | 1         | 1      | 1.2%    |
| Phison              | 1         | 1      | 1.2%    |
| Micron Technology   | 1         | 1      | 1.2%    |
| KIOXIA              | 1         | 1      | 1.2%    |
| Intenso             | 1         | 2      | 1.2%    |
| HFS512GD            | 1         | 1      | 1.2%    |
| China               | 1         | 1      | 1.2%    |
| Apple               | 1         | 1      | 1.2%    |
| Advantech           | 1         | 1      | 1.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB              | 3         | 3.19%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 3         | 3.19%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 3.19%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2         | 2.13%   |
| WDC WD10EZEX-08M2NA0 1TB               | 2         | 2.13%   |
| Toshiba DT01ACA050 500GB               | 2         | 2.13%   |
| SanDisk NVMe SSD Drive 256GB           | 2         | 2.13%   |
| Kingston SA400S37480G 480GB SSD        | 2         | 2.13%   |
| Crucial CT1000P1SSD8 1TB               | 2         | 2.13%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD       | 1         | 1.06%   |
| WDC WD6400AAKS-75A7B2 640GB            | 1         | 1.06%   |
| WDC WD5000AVDS-63U7B1 500GB            | 1         | 1.06%   |
| WDC WD5000AVCS-632DY1 500GB            | 1         | 1.06%   |
| WDC WD5000AAKX-003CA0 500GB            | 1         | 1.06%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 1         | 1.06%   |
| WDC WD3200BEVT-75ZCT2 320GB            | 1         | 1.06%   |
| WDC WD3200AAJS-00YZCA0 320GB           | 1         | 1.06%   |
| WDC WD32 00AAJS-00L7A0 320GB           | 1         | 1.06%   |
| WDC WD3000GLFS-01F8U0 304GB            | 1         | 1.06%   |
| WDC WD2500HHTZ-04N21V1 250GB           | 1         | 1.06%   |
| WDC WD2003FZEX-00Z4SA0 2TB             | 1         | 1.06%   |
| WDC WD2003FZEX-00SRLA0 2TB             | 1         | 1.06%   |
| WDC WD10SPZX-24Z10T0 1TB               | 1         | 1.06%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 1.06%   |
| WDC WD10EZRX-00L4HB0 1TB               | 1         | 1.06%   |
| WDC WD10EADS-00P8B0 1TB                | 1         | 1.06%   |
| WDC WD10EADS-00M2B0 1TB                | 1         | 1.06%   |
| WDC WD1003FBYX-01Y7B0 1TB              | 1         | 1.06%   |
| WDC WD My Passport 25F3 512GB          | 1         | 1.06%   |
| Unknown USB DISK 3.2 1TB               | 1         | 1.06%   |
| Unknown MMC Card  128GB                | 1         | 1.06%   |
| Toshiba XS700 240GB                    | 1         | 1.06%   |
| Toshiba MQ01ABF050 500GB               | 1         | 1.06%   |
| Toshiba KXG60ZNV512G NVMe 512GB        | 1         | 1.06%   |
| Toshiba DT01ACA100 1TB                 | 1         | 1.06%   |
| SK hynix NVMe SSD Drive 500GB          | 1         | 1.06%   |
| SK hynix NVMe SSD Drive 256GB          | 1         | 1.06%   |
| SK hynix NVMe SSD Drive 128GB          | 1         | 1.06%   |
| Silicon Motion NVMe SSD Drive 512GB    | 1         | 1.06%   |
| Seagate ST500DM002-1BD142 500GB        | 1         | 1.06%   |
| Seagate ST4000DM004-2CV104 4TB         | 1         | 1.06%   |
| Seagate ST3320418AS 320GB              | 1         | 1.06%   |
| Seagate ST2000LM007-1R8174 2TB         | 1         | 1.06%   |
| Seagate ST2000DM006-2DM164 2TB         | 1         | 1.06%   |
| Seagate ST2000DM005-2CW102 2TB         | 1         | 1.06%   |
| Seagate ST1000LM049-2GH172 1TB         | 1         | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB         | 1         | 1.06%   |
| SanDisk SDSSDP064G 64GB                | 1         | 1.06%   |
| SanDisk NVMe SSD Drive 1TB             | 1         | 1.06%   |
| SanDisk Extreme SSD 1TB                | 1         | 1.06%   |
| SanDisk Extreme Pro 1TB                | 1         | 1.06%   |
| SanDisk DF4032  32GB                   | 1         | 1.06%   |
| Samsung SSD 870 QVO 2TB                | 1         | 1.06%   |
| Samsung SSD 860 EVO 500GB              | 1         | 1.06%   |
| Samsung SSD 860 EVO 250GB              | 1         | 1.06%   |
| Samsung SSD 860 EVO 1TB                | 1         | 1.06%   |
| Samsung SSD 850 EVO 120GB              | 1         | 1.06%   |
| Samsung SSD 840 PRO Series 256GB       | 1         | 1.06%   |
| Samsung SSD 840 EVO 120GB              | 1         | 1.06%   |
| Samsung NVMe SSD Drive 512GB           | 1         | 1.06%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 22     | 51.52%  |
| Seagate             | 8         | 8      | 24.24%  |
| Toshiba             | 4         | 4      | 12.12%  |
| Hitachi             | 2         | 2      | 6.06%   |
| Samsung Electronics | 1         | 1      | 3.03%   |
| Intenso             | 1         | 2      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 13     | 42.31%  |
| Kingston            | 5         | 7      | 19.23%  |
| SanDisk             | 2         | 2      | 7.69%   |
| PNY                 | 2         | 2      | 7.69%   |
| WDC                 | 1         | 1      | 3.85%   |
| Micron Technology   | 1         | 1      | 3.85%   |
| Crucial             | 1         | 1      | 3.85%   |
| China               | 1         | 1      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |
| Advantech           | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 28        | 39     | 37.84%  |
| NVMe    | 20        | 24     | 27.03%  |
| SSD     | 20        | 30     | 27.03%  |
| Unknown | 4         | 4      | 5.41%   |
| MMC     | 2         | 2      | 2.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 65     | 57.14%  |
| NVMe | 20        | 24     | 31.75%  |
| SAS  | 5         | 8      | 7.94%   |
| MMC  | 2         | 2      | 3.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 40     | 50%     |
| 0.51-1.0   | 17        | 21     | 34%     |
| 1.01-2.0   | 6         | 6      | 12%     |
| 3.01-4.0   | 2         | 2      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 14        | 28%     |
| 101-250        | 13        | 26%     |
| 501-1000       | 10        | 20%     |
| 1001-2000      | 5         | 10%     |
| More than 3000 | 3         | 6%      |
| 21-50          | 3         | 6%      |
| 51-100         | 2         | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 37.25%  |
| 21-50          | 9         | 17.65%  |
| 101-250        | 7         | 13.73%  |
| 501-1000       | 5         | 9.8%    |
| 51-100         | 4         | 7.84%   |
| 251-500        | 3         | 5.88%   |
| 1001-2000      | 3         | 5.88%   |
| More than 3000 | 1         | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Crucial CT1000P1SSD8 1TB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Crucial | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 100%    |

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
| Detected | 41        | 82     | 75.93%  |
| Works    | 12        | 16     | 22.22%  |
| Malfunc  | 1         | 1      | 1.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 28        | 44.44%  |
| AMD                          | 16        | 25.4%   |
| Samsung Electronics          | 5         | 7.94%   |
| SK hynix                     | 3         | 4.76%   |
| SanDisk                      | 3         | 4.76%   |
| Toshiba America Info Systems | 2         | 3.17%   |
| Micron/Crucial Technology    | 2         | 3.17%   |
| Kingston Technology Company  | 2         | 3.17%   |
| Silicon Motion               | 1         | 1.59%   |
| Phison Electronics           | 1         | 1.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10        | 13.51%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 8.11%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 6.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 5.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 4.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 4.05%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 2.7%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 2.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 2.7%    |
| SK hynix PC300 NVMe Solid State Drive 256GB                                             | 1         | 1.35%   |
| SK hynix Gold P31 SSD                                                                   | 1         | 1.35%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 1.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 1.35%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 1.35%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 1.35%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 1.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.35%   |
| Samsung Electronics SATA controller                                                     | 1         | 1.35%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.35%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 1.35%   |
| Kingston Company KC2000 NVMe SSD                                                        | 1         | 1.35%   |
| Intel SSD 660P Series                                                                   | 1         | 1.35%   |
| Intel SSD 600P Series                                                                   | 1         | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 1.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.35%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 1.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 1.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1         | 1.35%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 1.35%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1         | 1.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 58.46%  |
| NVMe | 19        | 29.23%  |
| IDE  | 7         | 10.77%  |
| RAID | 1         | 1.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 34        | 68%     |
| AMD    | 16        | 32%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-2640M CPU @ 2.80GHz               | 2         | 4%      |
| Intel Core i5-4210U CPU @ 1.70GHz               | 2         | 4%      |
| Intel Core i3-4160 CPU @ 3.60GHz                | 2         | 4%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 4%      |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz             | 1         | 2%      |
| Intel Pentium Silver N6000 @ 1.10GHz            | 1         | 2%      |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz     | 1         | 2%      |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2%      |
| Intel Core i7-7820HQ CPU @ 2.90GHz              | 1         | 2%      |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 2%      |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1         | 2%      |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1         | 2%      |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 2%      |
| Intel Core i5-8259U CPU @ 2.30GHz               | 1         | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 2%      |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 2%      |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1         | 2%      |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1         | 2%      |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1         | 2%      |
| Intel Core i5-10210U CPU @ 1.60GHz              | 1         | 2%      |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 2%      |
| Intel Core i3-3210 CPU @ 3.20GHz                | 1         | 2%      |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1         | 2%      |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1         | 2%      |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2%      |
| Intel Celeron CPU G3930 @ 2.90GHz               | 1         | 2%      |
| Intel Celeron CPU E3400 @ 2.60GHz               | 1         | 2%      |
| Intel Celeron CPU 540 @ 1.86GHz                 | 1         | 2%      |
| Intel Atom x5-E8000 CPU @ 1.04GHz               | 1         | 2%      |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 1         | 2%      |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 1         | 2%      |
| AMD Ryzen 7 5800X 8-Core Processor              | 1         | 2%      |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 2%      |
| AMD Ryzen 7 3800X 8-Core Processor              | 1         | 2%      |
| AMD Ryzen 7 3700X 8-Core Processor              | 1         | 2%      |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 1         | 2%      |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 2%      |
| AMD Ryzen 5 5600H with Radeon Graphics          | 1         | 2%      |
| AMD Ryzen 5 3600 6-Core Processor               | 1         | 2%      |
| AMD Ryzen 5 2600X Six-Core Processor            | 1         | 2%      |
| AMD Ryzen 5 2600 Six-Core Processor             | 1         | 2%      |
| AMD Phenom II X4 955 Processor                  | 1         | 2%      |
| AMD FX-6300 Six-Core Processor                  | 1         | 2%      |
| AMD E-350 Processor                             | 1         | 2%      |
| AMD A10-7890K Radeon R7, 12 Compute Cores 4C+8G | 1         | 2%      |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 9         | 18%     |
| Intel Core i7           | 8         | 16%     |
| AMD Ryzen 7             | 6         | 12%     |
| Intel Core i3           | 5         | 10%     |
| Intel Celeron           | 4         | 8%      |
| AMD Ryzen 5             | 4         | 8%      |
| Other                   | 3         | 6%      |
| AMD A10                 | 2         | 4%      |
| Intel Xeon              | 1         | 2%      |
| Intel Pentium Silver    | 1         | 2%      |
| Intel Pentium Dual-Core | 1         | 2%      |
| Intel Core 2 Quad       | 1         | 2%      |
| Intel Atom              | 1         | 2%      |
| AMD Ryzen 9             | 1         | 2%      |
| AMD Phenom II X4        | 1         | 2%      |
| AMD FX                  | 1         | 2%      |
| AMD E                   | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 20        | 40%     |
| 2      | 18        | 36%     |
| 8      | 6         | 12%     |
| 6      | 4         | 8%      |
| 3      | 1         | 2%      |
| 1      | 1         | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 74%     |
| 1      | 13        | 26%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 50        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 6         | 11.76%  |
| 0x206a7    | 4         | 7.84%   |
| Unknown    | 4         | 7.84%   |
| 0x806ec    | 3         | 5.88%   |
| 0x806c1    | 3         | 5.88%   |
| 0x1067a    | 3         | 5.88%   |
| 0x0800820d | 3         | 5.88%   |
| 0x906e9    | 2         | 3.92%   |
| 0x806ea    | 2         | 3.92%   |
| 0x40651    | 2         | 3.92%   |
| 0x0a50000c | 2         | 3.92%   |
| 0x08701021 | 2         | 3.92%   |
| 0x06003106 | 2         | 3.92%   |
| 0x906c0    | 1         | 1.96%   |
| 0x706a1    | 1         | 1.96%   |
| 0x506e3    | 1         | 1.96%   |
| 0x406e3    | 1         | 1.96%   |
| 0x306a9    | 1         | 1.96%   |
| 0x10661    | 1         | 1.96%   |
| 0x0a201204 | 1         | 1.96%   |
| 0x08701013 | 1         | 1.96%   |
| 0x08600106 | 1         | 1.96%   |
| 0x08108109 | 1         | 1.96%   |
| 0x06000852 | 1         | 1.96%   |
| 0x05000029 | 1         | 1.96%   |
| 0x010000c8 | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 16%     |
| Haswell       | 8         | 16%     |
| Zen+          | 4         | 8%      |
| Zen 2         | 4         | 8%      |
| SandyBridge   | 4         | 8%      |
| Zen 3         | 3         | 6%      |
| TigerLake     | 3         | 6%      |
| Skylake       | 3         | 6%      |
| Penryn        | 3         | 6%      |
| Steamroller   | 2         | 4%      |
| Tremont       | 1         | 2%      |
| Silvermont    | 1         | 2%      |
| Piledriver    | 1         | 2%      |
| K10           | 1         | 2%      |
| IvyBridge     | 1         | 2%      |
| Goldmont plus | 1         | 2%      |
| Core          | 1         | 2%      |
| Bobcat        | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 27        | 43.55%  |
| AMD    | 20        | 32.26%  |
| Nvidia | 15        | 24.19%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 4.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 3.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.17%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 3.17%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 3.17%   |
| AMD Cezanne                                                                              | 2         | 3.17%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.59%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 1.59%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 1.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.59%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.59%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.59%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.59%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1         | 1.59%   |
| Nvidia GK104 [GeForce GTX 770]                                                           | 1         | 1.59%   |
| Nvidia GF119 [GeForce 605]                                                               | 1         | 1.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.59%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 1.59%   |
| Nvidia GF106GL [Quadro 2000]                                                             | 1         | 1.59%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.59%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.59%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.59%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.59%   |
| Intel HD Graphics 630                                                                    | 1         | 1.59%   |
| Intel HD Graphics 620                                                                    | 1         | 1.59%   |
| Intel HD Graphics 530                                                                    | 1         | 1.59%   |
| Intel HD Graphics 520                                                                    | 1         | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.59%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.59%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.59%   |
| AMD Vega 20 [Radeon VII]                                                                 | 1         | 1.59%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 1         | 1.59%   |
| AMD Tonga PRO [Radeon R9 285/380]                                                        | 1         | 1.59%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.59%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.59%   |
| AMD Renoir                                                                               | 1         | 1.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.59%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1         | 1.59%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 1         | 1.59%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.59%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1         | 1.59%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.59%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                              | 1         | 1.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 1.59%   |
| AMD Amethyst [Radeon R9 M395/ M395X Mac Edition]                                         | 1         | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 34%     |
| 1 x AMD        | 16        | 32%     |
| 1 x Nvidia     | 8         | 16%     |
| Intel + Nvidia | 5         | 10%     |
| Intel + AMD    | 2         | 4%      |
| AMD + Nvidia   | 2         | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 40        | 80%     |
| Proprietary | 10        | 20%     |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 38%     |
| 1.01-2.0   | 10        | 20%     |
| 0.51-1.0   | 8         | 16%     |
| 5.01-6.0   | 3         | 6%      |
| 3.01-4.0   | 3         | 6%      |
| 0.01-0.5   | 3         | 6%      |
| 7.01-8.0   | 2         | 4%      |
| 8.01-16.0  | 2         | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 7         | 12.07%  |
| Chimei Innolux          | 7         | 12.07%  |
| AOC                     | 7         | 12.07%  |
| Goldstar                | 5         | 8.62%   |
| Dell                    | 3         | 5.17%   |
| BOE                     | 3         | 5.17%   |
| AU Optronics            | 3         | 5.17%   |
| Acer                    | 3         | 5.17%   |
| NEC Computers           | 2         | 3.45%   |
| LG Display              | 2         | 3.45%   |
| Ancor Communications    | 2         | 3.45%   |
| Toshiba                 | 1         | 1.72%   |
| Sharp                   | 1         | 1.72%   |
| Philips                 | 1         | 1.72%   |
| PANDA                   | 1         | 1.72%   |
| Microstep               | 1         | 1.72%   |
| LG Electronics          | 1         | 1.72%   |
| Lenovo                  | 1         | 1.72%   |
| Hewlett-Packard         | 1         | 1.72%   |
| CSO                     | 1         | 1.72%   |
| Chi Mei Optoelectronics | 1         | 1.72%   |
| BenQ                    | 1         | 1.72%   |
| ASUSTek Computer        | 1         | 1.72%   |
| Apple                   | 1         | 1.72%   |
| Unknown                 | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                         | 3         | 4.84%   |
| Toshiba Internal LCD TOS5091 1366x768 309x174mm 14.0-inch                | 1         | 1.61%   |
| Sharp LCD Monitor HDMI 1920x1080                                         | 1         | 1.61%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch     | 1         | 1.61%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch      | 1         | 1.61%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch        | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                       | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 330x210mm 15.4-inch     | 1         | 1.61%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1         | 1.61%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch        | 1         | 1.61%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                    | 1         | 1.61%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 1         | 1.61%   |
| NEC Computers LCD Monitor LCD92VM 1280x1024                              | 1         | 1.61%   |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch               | 1         | 1.61%   |
| Microstep LCD Monitor MSI G241                                           | 1         | 1.61%   |
| LG Electronics LCD Monitor E2241 1920x1080                               | 1         | 1.61%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch             | 1         | 1.61%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                      | 1         | 1.61%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch                | 1         | 1.61%   |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                      | 1         | 1.61%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                      | 1         | 1.61%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 1         | 1.61%   |
| Goldstar E2050 GSM4EAE 1600x900 443x249mm 20.0-inch                      | 1         | 1.61%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                     | 1         | 1.61%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                      | 1         | 1.61%   |
| Dell S3222DGM DELD110 2560x1440 697x392mm 31.5-inch                      | 1         | 1.61%   |
| Dell 1908WFP DELF007 1440x900 408x255mm 18.9-inch                        | 1         | 1.61%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch         | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 1.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 1         | 1.61%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 1.61%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                    | 1         | 1.61%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 1.61%   |
| BenQ LCD Monitor T2200HD 5760x1080                                       | 1         | 1.61%   |
| BenQ LCD Monitor T2200HD                                                 | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch           | 1         | 1.61%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch             | 1         | 1.61%   |
| ASUSTek Computer MG248 AUS24A3 1920x1080 531x299mm 24.0-inch             | 1         | 1.61%   |
| Apple iMac APPAE05 3840x2160 597x336mm 27.0-inch                         | 1         | 1.61%   |
| AOC Q29G2G5 AOC2902 2560x1080 681x287mm 29.1-inch                        | 1         | 1.61%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                          | 1         | 1.61%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                          | 1         | 1.61%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 1         | 1.61%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 1         | 1.61%   |
| Ancor Communications VX228 ACI22C1 1920x1080 476x268mm 21.5-inch         | 1         | 1.61%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 480x270mm 21.7-inch    | 1         | 1.61%   |
| Acer V236HL ACR0350 1920x1080 510x290mm 23.1-inch                        | 1         | 1.61%   |
| Acer V193HQV ACR0133 1366x768 410x230mm 18.5-inch                        | 1         | 1.61%   |
| Acer K242HYL ACR064A 1920x1080 527x296mm 23.8-inch                       | 1         | 1.61%   |
| Unknown                                                                  | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 26        | 45.61%  |
| 1366x768 (WXGA)    | 11        | 19.3%   |
| 3840x2160 (4K)     | 4         | 7.02%   |
| 2560x1440 (QHD)    | 4         | 7.02%   |
| 1280x1024 (SXGA)   | 2         | 3.51%   |
| 5760x1080          | 1         | 1.75%   |
| 2560x1080          | 1         | 1.75%   |
| 2256x1504          | 1         | 1.75%   |
| 1680x1050 (WSXGA+) | 1         | 1.75%   |
| 1600x900 (HD+)     | 1         | 1.75%   |
| 1440x900 (WXGA+)   | 1         | 1.75%   |
| 1360x768           | 1         | 1.75%   |
| 1280x800 (WXGA)    | 1         | 1.75%   |
| 1024x768 (XGA)     | 1         | 1.75%   |
| Unknown            | 1         | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 16        | 28.57%  |
| 24      | 7         | 12.5%   |
| Unknown | 6         | 10.71%  |
| 27      | 4         | 7.14%   |
| 23      | 4         | 7.14%   |
| 21      | 4         | 7.14%   |
| 18      | 4         | 7.14%   |
| 13      | 4         | 7.14%   |
| 31      | 1         | 1.79%   |
| 29      | 1         | 1.79%   |
| 22      | 1         | 1.79%   |
| 20      | 1         | 1.79%   |
| 19      | 1         | 1.79%   |
| 14      | 1         | 1.79%   |
| 11      | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 30.36%  |
| 501-600     | 15        | 26.79%  |
| 401-500     | 10        | 17.86%  |
| Unknown     | 6         | 10.71%  |
| 201-300     | 4         | 7.14%   |
| 601-700     | 2         | 3.57%   |
| 351-400     | 2         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 37        | 69.81%  |
| 16/10   | 6         | 11.32%  |
| Unknown | 6         | 11.32%  |
| 5/4     | 1         | 1.89%   |
| 4/3     | 1         | 1.89%   |
| 3/2     | 1         | 1.89%   |
| 21/9    | 1         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 28.57%  |
| 201-250        | 12        | 21.43%  |
| Unknown        | 6         | 10.71%  |
| 301-350        | 5         | 8.93%   |
| 151-200        | 4         | 7.14%   |
| 81-90          | 3         | 5.36%   |
| 251-300        | 3         | 5.36%   |
| 141-150        | 3         | 5.36%   |
| 71-80          | 2         | 3.57%   |
| 51-60          | 1         | 1.79%   |
| 351-500        | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 22        | 41.51%  |
| 101-120       | 10        | 18.87%  |
| 121-160       | 9         | 16.98%  |
| Unknown       | 6         | 11.32%  |
| 161-240       | 4         | 7.55%   |
| More than 240 | 2         | 3.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 74%     |
| 2     | 11        | 22%     |
| 3     | 2         | 4%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 30        | 41.67%  |
| Intel                    | 20        | 27.78%  |
| Qualcomm Atheros         | 7         | 9.72%   |
| MediaTek                 | 3         | 4.17%   |
| Broadcom                 | 3         | 4.17%   |
| Xiaomi                   | 1         | 1.39%   |
| TP-Link                  | 1         | 1.39%   |
| Ralink Technology        | 1         | 1.39%   |
| Marvell Technology Group | 1         | 1.39%   |
| Linksys                  | 1         | 1.39%   |
| Huawei Technologies      | 1         | 1.39%   |
| Dell                     | 1         | 1.39%   |
| D-Link System            | 1         | 1.39%   |
| Belkin Components        | 1         | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                       | 26        | 30.23%  |
| Intel Wi-Fi 6 AX200                                                                     | 4         | 4.65%   |
| Intel I211 Gigabit Network Connection                                                   | 3         | 3.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 2         | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                              | 2         | 2.33%   |
| Intel Wireless 3165                                                                     | 2         | 2.33%   |
| Intel Wi-Fi 6 AX201                                                                     | 2         | 2.33%   |
| Intel Ethernet Controller I225-V                                                        | 2         | 2.33%   |
| Intel Ethernet Connection I217-LM                                                       | 2         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                   | 2         | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                          | 1         | 1.16%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                         | 1         | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                         | 1         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                | 1         | 1.16%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                | 1         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1         | 1.16%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1         | 1.16%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                                        | 1         | 1.16%   |
| Ralink MT7601U Wireless Adapter                                                         | 1         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 1         | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 1         | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                              | 1         | 1.16%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                | 1         | 1.16%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1         | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                           | 1         | 1.16%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1         | 1.16%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                    | 1         | 1.16%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1         | 1.16%   |
| Intel Wireless-AC 9260                                                                  | 1         | 1.16%   |
| Intel Wireless 8265 / 8275                                                              | 1         | 1.16%   |
| Intel Wireless 7265                                                                     | 1         | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                  | 1         | 1.16%   |
| Intel Wi-Fi 6 AX201 160MHz                                                              | 1         | 1.16%   |
| Intel Ethernet Connection (5) I219-LM                                                   | 1         | 1.16%   |
| Intel Ethernet Connection (13) I219-V                                                   | 1         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                                          | 1         | 1.16%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                           | 1         | 1.16%   |
| Huawei COL-L29                                                                          | 1         | 1.16%   |
| Dell DW5550                                                                             | 1         | 1.16%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1         | 1.16%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                                       | 1         | 1.16%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                             | 1         | 1.16%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1         | 1.16%   |
| Broadcom BCM4311 802.11b/g WLAN                                                         | 1         | 1.16%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1         | 1.16%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 40%     |
| Realtek Semiconductor | 8         | 20%     |
| Qualcomm Atheros      | 6         | 15%     |
| MediaTek              | 3         | 7.5%    |
| Broadcom              | 3         | 7.5%    |
| Ralink Technology     | 1         | 2.5%    |
| Linksys               | 1         | 2.5%    |
| D-Link System         | 1         | 2.5%    |
| Belkin Components     | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 4         | 10%     |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2         | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 2         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                              | 2         | 5%      |
| Intel Wireless 3165                                                                     | 2         | 5%      |
| Intel Wi-Fi 6 AX201                                                                     | 2         | 5%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                         | 1         | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                | 1         | 2.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                | 1         | 2.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1         | 2.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1         | 2.5%    |
| Realtek RTL8187 Wireless Adapter                                                        | 1         | 2.5%    |
| Ralink MT7601U Wireless Adapter                                                         | 1         | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 1         | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 1         | 2.5%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1         | 2.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                           | 1         | 2.5%    |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1         | 2.5%    |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1         | 2.5%    |
| Intel Wireless-AC 9260                                                                  | 1         | 2.5%    |
| Intel Wireless 8265 / 8275                                                              | 1         | 2.5%    |
| Intel Wireless 7265                                                                     | 1         | 2.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                  | 1         | 2.5%    |
| Intel Wi-Fi 6 AX201 160MHz                                                              | 1         | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1         | 2.5%    |
| Intel Centrino Ultimate-N 6300                                                          | 1         | 2.5%    |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                           | 1         | 2.5%    |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1         | 2.5%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                             | 1         | 2.5%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1         | 2.5%    |
| Broadcom BCM4311 802.11b/g WLAN                                                         | 1         | 2.5%    |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 60%     |
| Intel                    | 11        | 24.44%  |
| Qualcomm Atheros         | 2         | 4.44%   |
| Xiaomi                   | 1         | 2.22%   |
| TP-Link                  | 1         | 2.22%   |
| Marvell Technology Group | 1         | 2.22%   |
| Huawei Technologies      | 1         | 2.22%   |
| Broadcom                 | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 57.78%  |
| Intel I211 Gigabit Network Connection                             | 3         | 6.67%   |
| Intel Ethernet Controller I225-V                                  | 2         | 4.44%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.22%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 2.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.22%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.22%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.22%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.22%   |
| Huawei COL-L29                                                    | 1         | 2.22%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 54.43%  |
| WiFi     | 35        | 44.3%   |
| Modem    | 1         | 1.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 50%     |
| Ethernet | 27        | 50%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 28        | 56%     |
| 2     | 22        | 44%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 72%     |
| Yes  | 14        | 28%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 42.42%  |
| Realtek Semiconductor           | 3         | 9.09%   |
| Qualcomm Atheros Communications | 3         | 9.09%   |
| Cambridge Silicon Radio         | 3         | 9.09%   |
| Lite-On Technology              | 2         | 6.06%   |
| Broadcom                        | 2         | 6.06%   |
| MediaTek                        | 1         | 3.03%   |
| IMC Networks                    | 1         | 3.03%   |
| Foxconn / Hon Hai               | 1         | 3.03%   |
| Dell                            | 1         | 3.03%   |
| ASUSTek Computer                | 1         | 3.03%   |
| Apple                           | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 12.12%  |
| Intel AX200 Bluetooth                               | 4         | 12.12%  |
| Intel Bluetooth Device                              | 3         | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 9.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 6.06%   |
| Realtek RTL8821A Bluetooth                          | 1         | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.03%   |
| Realtek Bluetooth Radio                             | 1         | 3.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.03%   |
| MediaTek Wireless_Device                            | 1         | 3.03%   |
| Lite-On Wireless_Device                             | 1         | 3.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 3.03%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.03%   |
| Intel AX210 Bluetooth                               | 1         | 3.03%   |
| IMC Networks Bluetooth Radio                        | 1         | 3.03%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.03%   |
| Dell DW375 Bluetooth Module                         | 1         | 3.03%   |
| Broadcom BCM92045B3 ROM                             | 1         | 3.03%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.03%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.03%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 34        | 45.95%  |
| AMD                 | 20        | 27.03%  |
| Nvidia              | 12        | 16.22%  |
| Blue Microphones    | 2         | 2.7%    |
| Texas Instruments   | 1         | 1.35%   |
| Tenx Technology     | 1         | 1.35%   |
| Samsung Electronics | 1         | 1.35%   |
| Cooler Master       | 1         | 1.35%   |
| Conexant Systems    | 1         | 1.35%   |
| C-Media Electronics | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 5.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 4.3%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 4.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 4.3%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.23%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 3.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 3.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 3.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.15%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.15%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.15%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 2         | 2.15%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                                          | 2         | 2.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 2.15%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 2.15%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.15%   |
| Texas Instruments PCM2904 Audio Codec                                                             | 1         | 1.08%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 1.08%   |
| Samsung Electronics USBC Headset                                                                  | 1         | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.08%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.08%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.08%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.08%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Nvidia Audio device                                                                               | 1         | 1.08%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.08%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.08%   |
| Cooler Master CH321                                                                               | 1         | 1.08%   |
| Conexant Systems Hi-Res Audio                                                                     | 1         | 1.08%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.08%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.08%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                                               | 1         | 1.08%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 1.08%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 1.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 1.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.08%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.08%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 1.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 23.81%  |
| SK hynix            | 3         | 14.29%  |
| Unknown             | 2         | 9.52%   |
| Micron Technology   | 2         | 9.52%   |
| Crucial             | 2         | 9.52%   |
| A-DATA Technology   | 2         | 9.52%   |
| Transcend           | 1         | 4.76%   |
| Team                | 1         | 4.76%   |
| Patriot             | 1         | 4.76%   |
| G.Skill             | 1         | 4.76%   |
| Corsair             | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 4.76%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 4.76%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s                | 1         | 4.76%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 4.76%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 4.76%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 4.76%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 4.76%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 4.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 4.76%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4.76%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 4.76%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 4.76%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s              | 1         | 4.76%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 4.76%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 4.76%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 4.76%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s            | 1         | 4.76%   |
| Crucial RAM BLS8G4D32AESBK.M8FE 8192MB DIMM DDR4 3200MT/s        | 1         | 4.76%   |
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s            | 1         | 4.76%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 4.76%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s                      | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 8         | 44.44%  |
| DDR3   | 4         | 22.22%  |
| LPDDR3 | 3         | 16.67%  |
| LPDDR4 | 1         | 5.56%   |
| DDR2   | 1         | 5.56%   |
| DDR    | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 8         | 47.06%  |
| DIMM         | 6         | 35.29%  |
| Row Of Chips | 3         | 17.65%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 8         | 44.44%  |
| 4096  | 6         | 33.33%  |
| 16384 | 2         | 11.11%  |
| 32768 | 1         | 5.56%   |
| 1024  | 1         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 5         | 26.32%  |
| 2133    | 3         | 15.79%  |
| 2400    | 2         | 10.53%  |
| 1600    | 2         | 10.53%  |
| 1333    | 2         | 10.53%  |
| 4267    | 1         | 5.26%   |
| 2667    | 1         | 5.26%   |
| 1867    | 1         | 5.26%   |
| 667     | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

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
| Logitech                               | 5         | 16.67%  |
| Realtek Semiconductor                  | 4         | 13.33%  |
| Quanta                                 | 4         | 13.33%  |
| Sunplus Innovation Technology          | 2         | 6.67%   |
| Microdia                               | 2         | 6.67%   |
| IMC Networks                           | 2         | 6.67%   |
| Chicony Electronics                    | 2         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.67%   |
| Acer                                   | 2         | 6.67%   |
| MacroSilicon                           | 1         | 3.33%   |
| LG Electronics                         | 1         | 3.33%   |
| Hewlett-Packard                        | 1         | 3.33%   |
| Apple                                  | 1         | 3.33%   |
| A4Tech                                 | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Quanta HD User Facing                                           | 2         | 6.67%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 6.67%   |
| Logitech Webcam C270                                            | 2         | 6.67%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 3.33%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 3.33%   |
| Realtek Laptop Camera                                           | 1         | 3.33%   |
| Realtek Integrated Webcam_HD                                    | 1         | 3.33%   |
| Realtek Integrated Webcam                                       | 1         | 3.33%   |
| Realtek HD WebCam                                               | 1         | 3.33%   |
| Quanta VGA WebCam                                               | 1         | 3.33%   |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 3.33%   |
| MacroSilicon ShadowCast                                         | 1         | 3.33%   |
| Logitech HD Pro Webcam C920                                     | 1         | 3.33%   |
| Logitech C922 Pro Stream Webcam                                 | 1         | 3.33%   |
| Logitech C920 PRO HD Webcam                                     | 1         | 3.33%   |
| LG Optimus (Various Models) MTP Mode                            | 1         | 3.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 3.33%   |
| IMC Networks Integrated Camera                                  | 1         | 3.33%   |
| HP Webcam HD 2300                                               | 1         | 3.33%   |
| Chicony Sony Visual Communication Camera                        | 1         | 3.33%   |
| Chicony EasyCamera                                              | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 3.33%   |
| Apple FaceTime HD Camera (Built-in)                             | 1         | 3.33%   |
| Acer LENOVO LBG 720P CAM                                        | 1         | 3.33%   |
| Acer Lenovo EasyCamera                                          | 1         | 3.33%   |
| A4Tech FHD 1080P PC Camera                                      | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 50%     |
| Synaptics        | 1         | 25%     |
| AuthenTec        | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 25%     |
| Validity Sensors VFS Fingerprint sensor           | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 25%     |
| AuthenTec Fingerprint Sensor                      | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 39        | 78%     |
| 1     | 6         | 12%     |
| 2     | 4         | 8%      |
| 3     | 1         | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 7         | 33.33%  |
| Fingerprint reader    | 4         | 19.05%  |
| Multimedia controller | 3         | 14.29%  |
| Chipcard              | 3         | 14.29%  |
| Unassigned class      | 1         | 4.76%   |
| Storage               | 1         | 4.76%   |
| Graphics card         | 1         | 4.76%   |
| Camera                | 1         | 4.76%   |

