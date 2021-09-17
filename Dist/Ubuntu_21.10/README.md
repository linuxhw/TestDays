Ubuntu 21.10 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_21.10/Desktop/README.md) and [notebooks](/Dist/Ubuntu_21.10/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=ubuntu-21.10

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B85M-D3H                    | Desktop     | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [77d801bf3c](https://linux-hardware.org/?probe=77d801bf3c) | Sep 15, 2021 |
| HP            | ProBook 455 G6              | Notebook    | [8c5aa4304c](https://linux-hardware.org/?probe=8c5aa4304c) | Sep 14, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [c105819db0](https://linux-hardware.org/?probe=c105819db0) | Sep 13, 2021 |
| HP            | 3032h                       | Desktop     | [3fad749d1a](https://linux-hardware.org/?probe=3fad749d1a) | Sep 12, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [e1c9dadb12](https://linux-hardware.org/?probe=e1c9dadb12) | Sep 12, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [04299c1c72](https://linux-hardware.org/?probe=04299c1c72) | Sep 10, 2021 |
| Lenovo        | G570 20079                  | Notebook    | [070f80905a](https://linux-hardware.org/?probe=070f80905a) | Sep 09, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [ce30239886](https://linux-hardware.org/?probe=ce30239886) | Sep 08, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | Notebook    | [1dcfa059c1](https://linux-hardware.org/?probe=1dcfa059c1) | Sep 07, 2021 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [9036570a3d](https://linux-hardware.org/?probe=9036570a3d) | Sep 07, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [a23d662013](https://linux-hardware.org/?probe=a23d662013) | Sep 06, 2021 |
| Lenovo        | G570 20079                  | Notebook    | [92d47c8db5](https://linux-hardware.org/?probe=92d47c8db5) | Sep 05, 2021 |
| Google        | Nautilus                    | Notebook    | [3b25f1b84a](https://linux-hardware.org/?probe=3b25f1b84a) | Sep 05, 2021 |
| Lenovo        | G570 20079                  | Notebook    | [897adf5520](https://linux-hardware.org/?probe=897adf5520) | Sep 04, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [c080ec772f](https://linux-hardware.org/?probe=c080ec772f) | Sep 03, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [a66a6f00e4](https://linux-hardware.org/?probe=a66a6f00e4) | Sep 03, 2021 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [682d409384](https://linux-hardware.org/?probe=682d409384) | Sep 02, 2021 |
| Dell          | Latitude E6410              | Notebook    | [8b57d50d95](https://linux-hardware.org/?probe=8b57d50d95) | Sep 02, 2021 |
| ASUSTek       | GL753VD                     | Notebook    | [d17c6ba3fc](https://linux-hardware.org/?probe=d17c6ba3fc) | Sep 01, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [30fe8d6bb3](https://linux-hardware.org/?probe=30fe8d6bb3) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [cae806f49d](https://linux-hardware.org/?probe=cae806f49d) | Aug 22, 2021 |
| LG Electro... | 22V280 FAB1                 | All in one  | [b7af19f2f4](https://linux-hardware.org/?probe=b7af19f2f4) | Aug 20, 2021 |
| LG Electro... | 22V280 FAB1                 | All in one  | [f194373e42](https://linux-hardware.org/?probe=f194373e42) | Aug 20, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [1a371ea24e](https://linux-hardware.org/?probe=1a371ea24e) | Aug 16, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [b8aa2e41d5](https://linux-hardware.org/?probe=b8aa2e41d5) | Aug 16, 2021 |
| Fujitsu       | D3400-B2 S26361-D3400-B2    | Desktop     | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [612dda8fba](https://linux-hardware.org/?probe=612dda8fba) | Aug 13, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [1eb6008b88](https://linux-hardware.org/?probe=1eb6008b88) | Aug 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [808cfab06b](https://linux-hardware.org/?probe=808cfab06b) | Aug 12, 2021 |
| Lenovo        | ThinkPad T510 4484A63       | Notebook    | [c1bcb3451f](https://linux-hardware.org/?probe=c1bcb3451f) | Aug 09, 2021 |
| Lenovo        | ThinkPad T510 4484A63       | Notebook    | [4336b50906](https://linux-hardware.org/?probe=4336b50906) | Aug 06, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [912b2a77a2](https://linux-hardware.org/?probe=912b2a77a2) | Aug 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [961031411d](https://linux-hardware.org/?probe=961031411d) | Aug 03, 2021 |
| Lenovo        | ZhaoYang K3-ITL 82E3        | Notebook    | [ee2be4cea9](https://linux-hardware.org/?probe=ee2be4cea9) | Aug 03, 2021 |
| ASUSTek       | GL753VD                     | Notebook    | [eabe6a8723](https://linux-hardware.org/?probe=eabe6a8723) | Jul 31, 2021 |
| Acer          | Aspire 5920                 | Notebook    | [f41defe215](https://linux-hardware.org/?probe=f41defe215) | Jul 31, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| Teclast       | F6 Pro                      | Notebook    | [e28004c24b](https://linux-hardware.org/?probe=e28004c24b) | Jul 27, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [74e4c61bbf](https://linux-hardware.org/?probe=74e4c61bbf) | Jul 23, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [02ad72fb54](https://linux-hardware.org/?probe=02ad72fb54) | Jul 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f5458b4f56](https://linux-hardware.org/?probe=f5458b4f56) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [5ac65f3389](https://linux-hardware.org/?probe=5ac65f3389) | Jul 18, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [85aadf8abd](https://linux-hardware.org/?probe=85aadf8abd) | Jul 16, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [6a69f09403](https://linux-hardware.org/?probe=6a69f09403) | Jul 15, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [b2c80f450e](https://linux-hardware.org/?probe=b2c80f450e) | Jul 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [259908557b](https://linux-hardware.org/?probe=259908557b) | Jun 28, 2021 |
| Positivo      | H14BT58                     | Notebook    | [51b9ba65e0](https://linux-hardware.org/?probe=51b9ba65e0) | Jun 18, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [4befd5f360](https://linux-hardware.org/?probe=4befd5f360) | Jun 04, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [4ee08e92ae](https://linux-hardware.org/?probe=4ee08e92ae) | May 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.13.0-14-generic     | 13        | 38.24%  |
| 5.11.0-20-generic     | 5         | 14.71%  |
| 5.13.0-12-generic     | 2         | 5.88%   |
| 5.11.0-25-generic     | 2         | 5.88%   |
| 5.11.0-18-generic     | 2         | 5.88%   |
| 5.13.6-xanmod2-edge   | 1         | 2.94%   |
| 5.13.4-051304-generic | 1         | 2.94%   |
| 5.13.2-051302-generic | 1         | 2.94%   |
| 5.13.0-16-generic     | 1         | 2.94%   |
| 5.13.0-13-generic     | 1         | 2.94%   |
| 5.13.0-051300-generic | 1         | 2.94%   |
| 5.11.0-31-generic     | 1         | 2.94%   |
| 5.11.0-26-generic     | 1         | 2.94%   |
| 5.11.0-22-generic     | 1         | 2.94%   |
| 5.11.0-16-generic     | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 17        | 51.52%  |
| 5.11.0  | 13        | 39.39%  |
| 5.13.6  | 1         | 3.03%   |
| 5.13.4  | 1         | 3.03%   |
| 5.13.2  | 1         | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 20        | 60.61%  |
| 5.11    | 13        | 39.39%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 32        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 24        | 72.73%  |
| X-Cinnamon      | 3         | 9.09%   |
| Unknown         | 3         | 9.09%   |
| Unity           | 1         | 3.03%   |
| GNOME Flashback | 1         | 3.03%   |
| Cinnamon        | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 19        | 57.58%  |
| X11     | 13        | 39.39%  |
| Tty     | 1         | 3.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 16        | 50%     |
| GDM     | 15        | 46.88%  |
| TDM     | 1         | 3.13%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 9         | 28.13%  |
| en_GB | 7         | 21.88%  |
| fr_FR | 3         | 9.38%   |
| zh_CN | 2         | 6.25%   |
| sv_SE | 2         | 6.25%   |
| pt_BR | 2         | 6.25%   |
| ru_UA | 1         | 3.13%   |
| ru_RU | 1         | 3.13%   |
| ko_KR | 1         | 3.13%   |
| hu_HU | 1         | 3.13%   |
| es_MX | 1         | 3.13%   |
| es_AR | 1         | 3.13%   |
| en_IN | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 17        | 53.13%  |
| EFI  | 15        | 46.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 29        | 90.63%  |
| Btrfs | 2         | 6.25%   |
| Zfs   | 1         | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 15        | 46.88%  |
| Unknown | 15        | 46.88%  |
| MBR     | 2         | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 69.7%   |
| Yes       | 10        | 30.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 17        | 53.13%  |
| Yes       | 15        | 46.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 21.88%  |
| ASUSTek Computer    | 7         | 21.88%  |
| Dell                | 4         | 12.5%   |
| Hewlett-Packard     | 3         | 9.38%   |
| Gigabyte Technology | 2         | 6.25%   |
| Teclast             | 1         | 3.13%   |
| Positivo            | 1         | 3.13%   |
| MSI                 | 1         | 3.13%   |
| LG Electronics      | 1         | 3.13%   |
| Intel               | 1         | 3.13%   |
| Huanan              | 1         | 3.13%   |
| Google              | 1         | 3.13%   |
| Fujitsu             | 1         | 3.13%   |
| Acer                | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Teclast F6 Pro                          | 1         | 3.13%   |
| Positivo H14BT58                        | 1         | 3.13%   |
| MSI MS-7C94                             | 1         | 3.13%   |
| LG 22V280-L.BY31P1                      | 1         | 3.13%   |
| Lenovo ZhaoYang K3-ITL 82E3             | 1         | 3.13%   |
| Lenovo Z50-70 20354                     | 1         | 3.13%   |
| Lenovo V310-14IKB 80T2                  | 1         | 3.13%   |
| Lenovo ThinkPad X201 3626FAG            | 1         | 3.13%   |
| Lenovo ThinkPad T470 20JNS3M500         | 1         | 3.13%   |
| Lenovo ThinkPad T400 2768WGB            | 1         | 3.13%   |
| Lenovo G570 20079                       | 1         | 3.13%   |
| Intel NUC11PAHi5                        | 1         | 3.13%   |
| Huanan X99 F8D V2.2                     | 1         | 3.13%   |
| HP ProBook 455 G6                       | 1         | 3.13%   |
| HP Pavilion Gaming Laptop 15-dk0xxx     | 1         | 3.13%   |
| HP Compaq dc7900 Convertible Minitower  | 1         | 3.13%   |
| Google Nautilus                         | 1         | 3.13%   |
| Gigabyte F2A55M-HD2                     | 1         | 3.13%   |
| Gigabyte B85M-D3H                       | 1         | 3.13%   |
| Fujitsu S1100F                          | 1         | 3.13%   |
| Dell XPS 13 9343                        | 1         | 3.13%   |
| Dell XPS 13 9310                        | 1         | 3.13%   |
| Dell XPS 13 7390                        | 1         | 3.13%   |
| Dell Latitude E6410                     | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN  | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X509DJ_M509DJ  | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X421UAY_M413UA | 1         | 3.13%   |
| ASUS ROG ZENITH II EXTREME              | 1         | 3.13%   |
| ASUS ROG Strix G533QS_G533QS            | 1         | 3.13%   |
| ASUS ROG Strix G533QR_G533QR            | 1         | 3.13%   |
| ASUS GL753VD                            | 1         | 3.13%   |
| Acer Aspire 5920                        | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 3         | 9.38%   |
| Dell XPS            | 3         | 9.38%   |
| ASUS VivoBook       | 3         | 9.38%   |
| ASUS ROG            | 3         | 9.38%   |
| Teclast F6          | 1         | 3.13%   |
| Positivo H14BT58    | 1         | 3.13%   |
| MSI MS-7C94         | 1         | 3.13%   |
| LG 22V280-L.BY31P1  | 1         | 3.13%   |
| Lenovo ZhaoYang     | 1         | 3.13%   |
| Lenovo Z50-70       | 1         | 3.13%   |
| Lenovo V310-14IKB   | 1         | 3.13%   |
| Lenovo G570         | 1         | 3.13%   |
| Intel NUC11PAHi5    | 1         | 3.13%   |
| Huanan X99          | 1         | 3.13%   |
| HP ProBook          | 1         | 3.13%   |
| HP Pavilion         | 1         | 3.13%   |
| HP Compaq           | 1         | 3.13%   |
| Google Nautilus     | 1         | 3.13%   |
| Gigabyte F2A55M-HD2 | 1         | 3.13%   |
| Gigabyte B85M-D3H   | 1         | 3.13%   |
| Fujitsu S1100F      | 1         | 3.13%   |
| Dell Latitude       | 1         | 3.13%   |
| ASUS GL753VD        | 1         | 3.13%   |
| Acer Aspire         | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 11        | 34.38%  |
| 2020 | 6         | 18.75%  |
| 2015 | 3         | 9.38%   |
| 2019 | 2         | 6.25%   |
| 2018 | 2         | 6.25%   |
| 2017 | 2         | 6.25%   |
| 2014 | 1         | 3.13%   |
| 2013 | 1         | 3.13%   |
| 2012 | 1         | 3.13%   |
| 2011 | 1         | 3.13%   |
| 2010 | 1         | 3.13%   |
| 2008 | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 23        | 71.88%  |
| Desktop    | 7         | 21.88%  |
| Mini pc    | 1         | 3.13%   |
| All in one | 1         | 3.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 29        | 90.63%  |
| Enabled  | 3         | 9.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 96.88%  |
| Yes  | 1         | 3.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 33.33%  |
| 8.01-16.0   | 7         | 21.21%  |
| 32.01-64.0  | 5         | 15.15%  |
| 3.01-4.0    | 4         | 12.12%  |
| 64.01-256.0 | 2         | 6.06%   |
| 16.01-24.0  | 2         | 6.06%   |
| 24.01-32.0  | 1         | 3.03%   |
| 1.01-2.0    | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 12        | 35.29%  |
| 4.01-8.0  | 8         | 23.53%  |
| 1.01-2.0  | 8         | 23.53%  |
| 3.01-4.0  | 5         | 14.71%  |
| 8.01-16.0 | 1         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 20        | 62.5%   |
| 2      | 6         | 18.75%  |
| 3      | 3         | 9.38%   |
| 5      | 2         | 6.25%   |
| 4      | 1         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 78.13%  |
| Yes       | 7         | 21.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 75%     |
| No        | 8         | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 84.38%  |
| No        | 5         | 15.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 78.13%  |
| No        | 7         | 21.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| UK          | 5         | 15.63%  |
| USA         | 3         | 9.38%   |
| France      | 3         | 9.38%   |
| Brazil      | 3         | 9.38%   |
| Sweden      | 2         | 6.25%   |
| Germany     | 2         | 6.25%   |
| Ukraine     | 1         | 3.13%   |
| South Korea | 1         | 3.13%   |
| Singapore   | 1         | 3.13%   |
| Russia      | 1         | 3.13%   |
| Malaysia    | 1         | 3.13%   |
| Lithuania   | 1         | 3.13%   |
| India       | 1         | 3.13%   |
| Hungary     | 1         | 3.13%   |
| Finland     | 1         | 3.13%   |
| Czechia     | 1         | 3.13%   |
| Cyprus      | 1         | 3.13%   |
| China       | 1         | 3.13%   |
| Chile       | 1         | 3.13%   |
| Argentina   | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Yongin-si              | 1         | 3.13%   |
| Uppsala                | 1         | 3.13%   |
| Turku                  | 1         | 3.13%   |
| Trivandrum             | 1         | 3.13%   |
| Trakai                 | 1         | 3.13%   |
| Tottenham              | 1         | 3.13%   |
| Toms River             | 1         | 3.13%   |
| Tatab??nya             | 1         | 3.13%   |
| Singapore              | 1         | 3.13%   |
| Shanghai               | 1         | 3.13%   |
| S??o Paulo             | 1         | 3.13%   |
| Santiago               | 1         | 3.13%   |
| Rosario                | 1         | 3.13%   |
| Rio de Janeiro         | 1         | 3.13%   |
| Prague                 | 1         | 3.13%   |
| Petaling Jaya          | 1         | 3.13%   |
| Paris                  | 1         | 3.13%   |
| Osasco                 | 1         | 3.13%   |
| Nizhny Tagil           | 1         | 3.13%   |
| Nicosia                | 1         | 3.13%   |
| Maidstone              | 1         | 3.13%   |
| Lyon                   | 1         | 3.13%   |
| Leiston                | 1         | 3.13%   |
| Kyiv                   | 1         | 3.13%   |
| Helsingborg            | 1         | 3.13%   |
| Haselhorst             | 1         | 3.13%   |
| Glasgow                | 1         | 3.13%   |
| Fellbach               | 1         | 3.13%   |
| Crewe                  | 1         | 3.13%   |
| Charleville-M?�zi??res | 1         | 3.13%   |
| Brooklyn               | 1         | 3.13%   |
| Austin                 | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 17.65%  |
| Samsung Electronics | 9         | 11     | 17.65%  |
| WDC                 | 4         | 4      | 7.84%   |
| Toshiba             | 4         | 4      | 7.84%   |
| Sandisk             | 3         | 4      | 5.88%   |
| Kingston            | 3         | 5      | 5.88%   |
| Unknown             | 2         | 2      | 3.92%   |
| SK Hynix            | 2         | 2      | 3.92%   |
| KIOXIA-EXCERIA      | 2         | 2      | 3.92%   |
| Intel               | 2         | 3      | 3.92%   |
| SPCC                | 1         | 1      | 1.96%   |
| SP                  | 1         | 1      | 1.96%   |
| Silicon Motion      | 1         | 3      | 1.96%   |
| PNY                 | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| LITEON              | 1         | 1      | 1.96%   |
| KingDian            | 1         | 1      | 1.96%   |
| Hitachi             | 1         | 1      | 1.96%   |
| HGST                | 1         | 2      | 1.96%   |
| Hewlett-Packard     | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| SK Hynix HFM001TD3JX013N 1TB             | 2         | 3.7%    |
| Seagate Expansion+ 1TB                   | 2         | 3.7%    |
| KIOXIA-EXCERIA SATA SSD 480GB            | 2         | 3.7%    |
| WDC WDS500G2B0C-00PXH0 500GB             | 1         | 1.85%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 1.85%   |
| WDC WD3200AAJS-56B4A0 320GB              | 1         | 1.85%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1         | 1.85%   |
| Unknown SB64G  64GB                      | 1         | 1.85%   |
| Unknown MMC Card  64GB                   | 1         | 1.85%   |
| Toshiba NVMe SSD Drive 256GB             | 1         | 1.85%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1.85%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1.85%   |
| Toshiba HDWL120 2TB                      | 1         | 1.85%   |
| SPCC Solid State Disk 128GB              | 1         | 1.85%   |
| SP PC60 1TB                              | 1         | 1.85%   |
| Silicon Motion NVMe SSD Drive 256GB      | 1         | 1.85%   |
| Seagate ST9320423AS 320GB                | 1         | 1.85%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1.85%   |
| Seagate ST3250310AS 250GB                | 1         | 1.85%   |
| Seagate ST320DM000-1BD14C 320GB          | 1         | 1.85%   |
| Seagate ST1000DM003-9YN162 1TB           | 1         | 1.85%   |
| Seagate BUP Slim RD 2TB                  | 1         | 1.85%   |
| Seagate BUP Slim BK 2TB                  | 1         | 1.85%   |
| Seagate BarraCuda SSD ZA500CM10002 500GB | 1         | 1.85%   |
| SanDisk SD9SN8W256G1102 256GB SSD        | 1         | 1.85%   |
| SanDisk SD7SB3Q064G 56GB SSD             | 1         | 1.85%   |
| Sandisk NVMe SSD Drive 500GB             | 1         | 1.85%   |
| Samsung SSD 980 PRO 500GB                | 1         | 1.85%   |
| Samsung SSD 980 PRO 2TB                  | 1         | 1.85%   |
| Samsung SSD 970 EVO 500GB                | 1         | 1.85%   |
| Samsung SSD 860 EVO 500GB                | 1         | 1.85%   |
| Samsung SSD 850 EVO 500GB                | 1         | 1.85%   |
| Samsung SSD 650 120GB                    | 1         | 1.85%   |
| Samsung NVMe SSD Drive 512GB             | 1         | 1.85%   |
| Samsung MZVLQ512HALU-00000 512GB         | 1         | 1.85%   |
| Samsung MZALQ512HALU-000L2 512GB         | 1         | 1.85%   |
| Samsung HD103SJ 1TB                      | 1         | 1.85%   |
| PNY CS900 240GB SSD                      | 1         | 1.85%   |
| Micron 2300 NVMe 1024GB                  | 1         | 1.85%   |
| LITEON L8H-256V2G-11 M.2 2280 256GB SSD  | 1         | 1.85%   |
| Kingston SKC300S37A240G 240GB SSD        | 1         | 1.85%   |
| Kingston SHFS37A120G 120GB SSD           | 1         | 1.85%   |
| Kingston SA400S37240G 240GB SSD          | 1         | 1.85%   |
| KingDian N400 240GB SSD                  | 1         | 1.85%   |
| Intel NVMe SSD Drive 512GB               | 1         | 1.85%   |
| Intel HBRPEKNX0101AHO 16GB               | 1         | 1.85%   |
| Intel HBRPEKNX0101AH 256GB               | 1         | 1.85%   |
| Hitachi HTS543212L9SA00 120GB            | 1         | 1.85%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1.85%   |
| HP FB160C4081 160GB                      | 1         | 1.85%   |
| China SATA SSD 240GB                     | 1         | 1.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 9      | 44.44%  |
| WDC                 | 3         | 3      | 16.67%  |
| Toshiba             | 3         | 3      | 16.67%  |
| Samsung Electronics | 1         | 1      | 5.56%   |
| Hitachi             | 1         | 1      | 5.56%   |
| HGST                | 1         | 2      | 5.56%   |
| Hewlett-Packard     | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 18.75%  |
| Kingston            | 3         | 5      | 18.75%  |
| SanDisk             | 2         | 2      | 12.5%   |
| KIOXIA-EXCERIA      | 2         | 2      | 12.5%   |
| SPCC                | 1         | 1      | 6.25%   |
| Seagate             | 1         | 1      | 6.25%   |
| PNY                 | 1         | 1      | 6.25%   |
| LITEON              | 1         | 1      | 6.25%   |
| KingDian            | 1         | 1      | 6.25%   |
| China               | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 15        | 20     | 34.09%  |
| HDD     | 14        | 20     | 31.82%  |
| SSD     | 12        | 18     | 27.27%  |
| MMC     | 2         | 2      | 4.55%   |
| Unknown | 1         | 1      | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 19        | 34     | 47.5%   |
| NVMe | 15        | 20     | 37.5%   |
| SAS  | 4         | 5      | 10%     |
| MMC  | 2         | 2      | 5%      |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 26     | 62.96%  |
| 0.51-1.0   | 6         | 8      | 22.22%  |
| 1.01-2.0   | 4         | 4      | 14.81%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 51-100     | 9         | 27.27%  |
| 101-250    | 8         | 24.24%  |
| 251-500    | 6         | 18.18%  |
| 1001-2000  | 6         | 18.18%  |
| 501-1000   | 2         | 6.06%   |
| 21-50      | 1         | 3.03%   |
| 1-20       | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 8         | 24.24%  |
| 101-250   | 7         | 21.21%  |
| 21-50     | 6         | 18.18%  |
| 51-100    | 5         | 15.15%  |
| 501-1000  | 4         | 12.12%  |
| 251-500   | 2         | 6.06%   |
| 1001-2000 | 1         | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 21        | 38     | 56.76%  |
| Works    | 16        | 23     | 43.24%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 21        | 50%     |
| Samsung Electronics          | 6         | 14.29%  |
| AMD                          | 6         | 14.29%  |
| SK Hynix                     | 2         | 4.76%   |
| Sandisk                      | 2         | 4.76%   |
| Toshiba America Info Systems | 1         | 2.38%   |
| Silicon Motion               | 1         | 2.38%   |
| Micron Technology            | 1         | 2.38%   |
| LSI Logic / Symbios Logic    | 1         | 2.38%   |
| ASMedia Technology           | 1         | 2.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 8.89%   |
| SK Hynix NVMe SSD Controller                                                     | 2         | 4.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 4.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 4.44%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 4.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 4.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 4.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 4.44%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 2.22%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2.22%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.22%   |
| Sandisk Non-Volatile memory controller                                           | 1         | 2.22%   |
| Micron Non-Volatile memory controller                                            | 1         | 2.22%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                   | 1         | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.22%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.22%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 2.22%   |
| Intel SSD 660P Series                                                            | 1         | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.22%   |
| Intel Non-Volatile memory controller                                             | 1         | 2.22%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 2.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 2.22%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1         | 2.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2.22%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1         | 2.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 2.22%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 2.22%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                         | 1         | 2.22%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 2.22%   |
| AMD FCH IDE Controller                                                           | 1         | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 23        | 52.27%  |
| NVMe | 15        | 34.09%  |
| RAID | 3         | 6.82%   |
| IDE  | 2         | 4.55%   |
| SCSI | 1         | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 24        | 75%     |
| AMD    | 8         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core m3-7Y30 CPU @ 1.00GHz                | 2         | 6.25%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 2         | 6.25%   |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 2         | 6.25%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz             | 1         | 3.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 3.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 3.13%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 3.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 3.13%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 1         | 3.13%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1         | 3.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 3.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 3.13%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 3.13%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1         | 3.13%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 3.13%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 1         | 3.13%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 1         | 3.13%   |
| Intel Celeron N4100 CPU @ 1.10GHz               | 1         | 3.13%   |
| Intel Celeron CPU N2807 @ 1.58GHz               | 1         | 3.13%   |
| Intel Celeron CPU B800 @ 1.50GHz                | 1         | 3.13%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 3.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 3.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 3.13%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor  | 1         | 3.13%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 3.13%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1         | 3.13%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 3.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 1         | 3.13%   |
| AMD A4-4000 APU with Radeon HD Graphics         | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 8         | 25%     |
| Intel Core i7          | 4         | 12.5%   |
| Other                  | 3         | 9.38%   |
| Intel Core 2 Duo       | 3         | 9.38%   |
| Intel Celeron          | 3         | 9.38%   |
| AMD Ryzen 5            | 3         | 9.38%   |
| Intel Core m3          | 2         | 6.25%   |
| AMD Ryzen 9            | 2         | 6.25%   |
| Intel Xeon             | 1         | 3.13%   |
| AMD Ryzen Threadripper | 1         | 3.13%   |
| AMD Ryzen 7 PRO        | 1         | 3.13%   |
| AMD A4                 | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 13        | 40.63%  |
| 4      | 12        | 37.5%   |
| 8      | 2         | 6.25%   |
| 6      | 2         | 6.25%   |
| 32     | 1         | 3.13%   |
| 28     | 1         | 3.13%   |
| 1      | 1         | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 96.88%  |
| 2      | 1         | 3.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 24        | 75%     |
| 1      | 8         | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 32        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 50%     |
| 0x806e9    | 3         | 9.38%   |
| 0x806c1    | 3         | 9.38%   |
| 0x906ea    | 1         | 3.13%   |
| 0x906e9    | 1         | 3.13%   |
| 0x806ec    | 1         | 3.13%   |
| 0x806eb    | 1         | 3.13%   |
| 0x306d4    | 1         | 3.13%   |
| 0x206a7    | 1         | 3.13%   |
| 0x20652    | 1         | 3.13%   |
| 0x1067a    | 1         | 3.13%   |
| 0x0a50000b | 1         | 3.13%   |
| 0x08608103 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 25%     |
| Zen 3         | 3         | 9.38%   |
| TigerLake     | 3         | 9.38%   |
| Penryn        | 3         | 9.38%   |
| Westmere      | 2         | 6.25%   |
| Haswell       | 2         | 6.25%   |
| Broadwell     | 2         | 6.25%   |
| Zen+          | 1         | 3.13%   |
| Zen 2         | 1         | 3.13%   |
| Zen           | 1         | 3.13%   |
| Skylake       | 1         | 3.13%   |
| Silvermont    | 1         | 3.13%   |
| SandyBridge   | 1         | 3.13%   |
| Piledriver    | 1         | 3.13%   |
| Goldmont plus | 1         | 3.13%   |
| Unknown       | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 56.41%  |
| Nvidia | 10        | 25.64%  |
| AMD    | 7         | 17.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 7.14%   |
| Intel HD Graphics 630                                                       | 2         | 4.76%   |
| Intel HD Graphics 615                                                       | 2         | 4.76%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 4.76%   |
| AMD Cezanne                                                                 | 2         | 4.76%   |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1         | 2.38%   |
| Nvidia GP108M [GeForce MX230]                                               | 1         | 2.38%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 2.38%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 2.38%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 2.38%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                 | 1         | 2.38%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 2.38%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1         | 2.38%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 2.38%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                    | 1         | 2.38%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 1         | 2.38%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 2.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 1         | 2.38%   |
| Intel HD Graphics 620                                                       | 1         | 2.38%   |
| Intel HD Graphics 5500                                                      | 1         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1         | 2.38%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 2.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 2.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1         | 2.38%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1         | 2.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1         | 2.38%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1         | 2.38%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                | 1         | 2.38%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1         | 2.38%   |
| AMD Picasso                                                                 | 1         | 2.38%   |
| AMD Lucienne                                                                | 1         | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 56.25%  |
| Intel + Nvidia | 4         | 12.5%   |
| 1 x AMD        | 4         | 12.5%   |
| AMD + Nvidia   | 3         | 9.38%   |
| 2 x Nvidia     | 2         | 6.25%   |
| 1 x Nvidia     | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 25        | 78.13%  |
| Proprietary | 6         | 18.75%  |
| Unknown     | 1         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 78.13%  |
| 1.01-2.0   | 4         | 12.5%   |
| 0.01-0.5   | 3         | 9.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 14.29%  |
| Dell                | 4         | 11.43%  |
| Sharp               | 3         | 8.57%   |
| Lenovo              | 3         | 8.57%   |
| Chimei Innolux      | 3         | 8.57%   |
| BOE                 | 3         | 8.57%   |
| Samsung Electronics | 2         | 5.71%   |
| LG Display          | 2         | 5.71%   |
| Acer                | 2         | 5.71%   |
| SKY                 | 1         | 2.86%   |
| RTK                 | 1         | 2.86%   |
| PANDA               | 1         | 2.86%   |
| LG Electronics      | 1         | 2.86%   |
| KDC                 | 1         | 2.86%   |
| InfoVision          | 1         | 2.86%   |
| Goldstar            | 1         | 2.86%   |
| AOC                 | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Acer XV340CK P ACR06F3 3440x1440 800x335mm 34.1-inch                 | 2         | 5.56%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                 | 1         | 2.78%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 2.78%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch              | 1         | 2.78%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch | 1         | 2.78%   |
| RTK LCD Monitor RTK2136 1280x800 473x296mm 22.0-inch                 | 1         | 2.78%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch              | 1         | 2.78%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 1         | 2.78%   |
| LG Electronics LCD Monitor LG ULTRAWIDE                              | 1         | 2.78%   |
| LG Display LCD Monitor LGD05CE 1920x1080 344x194mm 15.5-inch         | 1         | 2.78%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 1         | 2.78%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch             | 1         | 2.78%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch              | 1         | 2.78%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 2.78%   |
| KDC LCD Monitor KDC0001 1920x1200 263x164mm 12.2-inch                | 1         | 2.78%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch         | 1         | 2.78%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1         | 2.78%   |
| Dell UP2516D DEL40E0 2560x1440 550x310mm 24.9-inch                   | 1         | 2.78%   |
| Dell S2721DS DELA19D 2560x1440 597x336mm 27.0-inch                   | 1         | 2.78%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                    | 1         | 2.78%   |
| Dell LCD Monitor P2419H 4480x1080                                    | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch     | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch     | 1         | 2.78%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                | 1         | 2.78%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                | 1         | 2.78%   |
| BOE LCD Monitor BOE05EC 1366x768 309x173mm 13.9-inch                 | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch       | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 2.78%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                     | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 15        | 42.86%  |
| 2560x1440 (QHD)   | 4         | 11.43%  |
| 3440x1440         | 2         | 5.71%   |
| 1920x1200 (WUXGA) | 2         | 5.71%   |
| 1440x900 (WXGA+)  | 2         | 5.71%   |
| 1366x768 (WXGA)   | 2         | 5.71%   |
| 1280x800 (WXGA)   | 2         | 5.71%   |
| 4480x1080         | 1         | 2.86%   |
| 3840x2400         | 1         | 2.86%   |
| 3840x2160 (4K)    | 1         | 2.86%   |
| 3200x1800 (QHD+)  | 1         | 2.86%   |
| 2560x1080         | 1         | 2.86%   |
| Unknown           | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 26.47%  |
| 13      | 8         | 23.53%  |
| 34      | 2         | 5.88%   |
| 27      | 2         | 5.88%   |
| 24      | 2         | 5.88%   |
| 17      | 2         | 5.88%   |
| 14      | 2         | 5.88%   |
| 12      | 2         | 5.88%   |
| 40      | 1         | 2.94%   |
| 25      | 1         | 2.94%   |
| 23      | 1         | 2.94%   |
| 21      | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 42.42%  |
| 201-300     | 7         | 21.21%  |
| 501-600     | 5         | 15.15%  |
| 701-800     | 2         | 6.06%   |
| 351-400     | 2         | 6.06%   |
| 801-900     | 1         | 3.03%   |
| 401-500     | 1         | 3.03%   |
| Unknown     | 1         | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 22        | 66.67%  |
| 16/10   | 7         | 21.21%  |
| 21/9    | 2         | 6.06%   |
| 3/2     | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 26.47%  |
| 81-90          | 5         | 14.71%  |
| 71-80          | 5         | 14.71%  |
| 201-250        | 3         | 8.82%   |
| 61-70          | 2         | 5.88%   |
| 351-500        | 2         | 5.88%   |
| 301-350        | 2         | 5.88%   |
| 251-300        | 2         | 5.88%   |
| 131-140        | 1         | 2.94%   |
| 121-130        | 1         | 2.94%   |
| 501-1000       | 1         | 2.94%   |
| Unknown        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 13        | 39.39%  |
| 101-120       | 7         | 21.21%  |
| 161-240       | 5         | 15.15%  |
| 51-100        | 4         | 12.12%  |
| More than 240 | 2         | 6.06%   |
| 1-50          | 1         | 3.03%   |
| Unknown       | 1         | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 27        | 81.82%  |
| 2     | 5         | 15.15%  |
| 0     | 1         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 18        | 39.13%  |
| Intel                         | 15        | 32.61%  |
| Qualcomm Atheros              | 4         | 8.7%    |
| MEDIATEK                      | 2         | 4.35%   |
| Xiaomi                        | 1         | 2.17%   |
| TP-Link                       | 1         | 2.17%   |
| Qualcomm                      | 1         | 2.17%   |
| OnePlus Technology (Shenzhen) | 1         | 2.17%   |
| Broadcom Limited              | 1         | 2.17%   |
| Broadcom                      | 1         | 2.17%   |
| Aquantia                      | 1         | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 23.64%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 3.64%   |
| MEDIATEK Network controller                                       | 2         | 3.64%   |
| Intel Wireless 7265                                               | 2         | 3.64%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 3.64%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 3.64%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 3.64%   |
| Xiaomi SDM660-MTP _SN:6C524624                                    | 1         | 1.82%   |
| TP-Link Archer T4U ver.3                                          | 1         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.82%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.82%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]       | 1         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.82%   |
| OnePlus (Shenzhen) IN2013                                         | 1         | 1.82%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.82%   |
| Intel Wireless 8260                                               | 1         | 1.82%   |
| Intel Wireless 3165                                               | 1         | 1.82%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 1.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.82%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.82%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.82%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.82%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 1.82%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.82%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.82%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.82%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 1.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 48.15%  |
| Realtek Semiconductor | 5         | 18.52%  |
| Qualcomm Atheros      | 4         | 14.81%  |
| MEDIATEK              | 2         | 7.41%   |
| TP-Link               | 1         | 3.7%    |
| Qualcomm              | 1         | 3.7%    |
| Broadcom Limited      | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 7.41%   |
| MEDIATEK Network controller                                    | 2         | 7.41%   |
| Intel Wireless 7265                                            | 2         | 7.41%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 7.41%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 7.41%   |
| TP-Link Archer T4U ver.3                                       | 1         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.7%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 3.7%    |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]    | 1         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 3.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.7%    |
| Intel Wireless 8265 / 8275                                     | 1         | 3.7%    |
| Intel Wireless 8260                                            | 1         | 3.7%    |
| Intel Wireless 3165                                            | 1         | 3.7%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 3.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 3.7%    |
| Intel Centrino Advanced-N 6200                                 | 1         | 3.7%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 16        | 57.14%  |
| Intel                         | 7         | 25%     |
| Xiaomi                        | 1         | 3.57%   |
| Qualcomm Atheros              | 1         | 3.57%   |
| OnePlus Technology (Shenzhen) | 1         | 3.57%   |
| Broadcom                      | 1         | 3.57%   |
| Aquantia                      | 1         | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 46.43%  |
| Intel 82577LM Gigabit Network Connection                          | 2         | 7.14%   |
| Xiaomi SDM660-MTP _SN:6C524624                                    | 1         | 3.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 3.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 3.57%   |
| OnePlus (Shenzhen) IN2013                                         | 1         | 3.57%   |
| Intel I211 Gigabit Network Connection                             | 1         | 3.57%   |
| Intel Ethernet Controller I225-V                                  | 1         | 3.57%   |
| Intel Ethernet Connection I219-V                                  | 1         | 3.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 3.57%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.57%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.57%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 52.94%  |
| Ethernet | 24        | 47.06%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 63.16%  |
| Ethernet | 14        | 36.84%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 18        | 56.25%  |
| 1     | 13        | 40.63%  |
| 3     | 1         | 3.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 26        | 81.25%  |
| Yes  | 6         | 18.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 40%     |
| Realtek Semiconductor           | 4         | 16%     |
| Qualcomm Atheros Communications | 3         | 12%     |
| IMC Networks                    | 3         | 12%     |
| Cambridge Silicon Radio         | 2         | 8%      |
| Lite-On Technology              | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| Broadcom                        | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 4         | 16%     |
| Intel Bluetooth wireless interface                  | 3         | 12%     |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 8%      |
| Realtek Bluetooth Radio                             | 2         | 8%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 8%      |
| Intel AX200 Bluetooth                               | 2         | 8%      |
| IMC Networks Wireless_Device                        | 2         | 8%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 8%      |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4%      |
| Lite-On Bluetooth Radio                             | 1         | 4%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4%      |
| IMC Networks Bluetooth Radio                        | 1         | 4%      |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 4%      |
| Broadcom BCM20702A0 Bluetooth                       | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 24        | 52.17%  |
| AMD                               | 7         | 15.22%  |
| Nvidia                            | 6         | 13.04%  |
| Elitegroup Computer Systems (ECS) | 2         | 4.35%   |
| XMOS                              | 1         | 2.17%   |
| NXP Semiconductors                | 1         | 2.17%   |
| Logitech                          | 1         | 2.17%   |
| Focusrite-Novation                | 1         | 2.17%   |
| Creative Technology               | 1         | 2.17%   |
| Corsair                           | 1         | 2.17%   |
| ASUSTek Computer                  | 1         | 2.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 5         | 9.09%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 7.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 5.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 5.45%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 3.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.64%   |
| Elitegroup Computer Systems (ECS) FOSTEX USB AUDIO HP-A4                   | 2         | 3.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 3.64%   |
| XMOS HIFI DSD                                                              | 1         | 1.82%   |
| NXP Semiconductors Monitor 09                                              | 1         | 1.82%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.82%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.82%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.82%   |
| Logitech H600 [Wireless Headset]                                           | 1         | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.82%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.82%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.82%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.82%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.82%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.82%   |
| Focusrite-Novation Scarlett 18i20 3rd Gen                                  | 1         | 1.82%   |
| Creative Technology SoundBlaster Audigy 2 NX                               | 1         | 1.82%   |
| Corsair HS70 Pro Wireless Gaming Headset                                   | 1         | 1.82%   |
| ASUSTek Computer USB Audio                                                 | 1         | 1.82%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 1.82%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 33.33%  |
| SK Hynix            | 5         | 20.83%  |
| Micron Technology   | 4         | 16.67%  |
| Unknown             | 2         | 8.33%   |
| Kingston            | 2         | 8.33%   |
| Crucial             | 2         | 8.33%   |
| Elpida              | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 2         | 8.33%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 8.33%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 4.17%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 4.17%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 4.17%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 4.17%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 4.17%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 1         | 4.17%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 4.17%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 4.17%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DIMM DDR4 2667MT/s              | 1         | 4.17%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s              | 1         | 4.17%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 4.17%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 4.17%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 4.17%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 4.17%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 4.17%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s           | 1         | 4.17%   |
| Kingston RAM KF3200C20S4/16GX 16GB SODIMM DDR4 3200MT/s          | 1         | 4.17%   |
| Elpida RAM Module 4GB Row Of Chips LPDDR3 1867MT/s               | 1         | 4.17%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s       | 1         | 4.17%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s            | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 12        | 57.14%  |
| DDR3   | 4         | 19.05%  |
| LPDDR3 | 3         | 14.29%  |
| LPDDR4 | 2         | 9.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 12        | 57.14%  |
| Row Of Chips | 4         | 19.05%  |
| DIMM         | 4         | 19.05%  |
| Chip         | 1         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 7         | 30.43%  |
| 4096  | 7         | 30.43%  |
| 16384 | 4         | 17.39%  |
| 2048  | 4         | 17.39%  |
| 32768 | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 5         | 22.73%  |
| 2667  | 5         | 22.73%  |
| 4267  | 2         | 9.09%   |
| 1867  | 2         | 9.09%   |
| 1600  | 2         | 9.09%   |
| 3733  | 1         | 4.55%   |
| 3600  | 1         | 4.55%   |
| 3400  | 1         | 4.55%   |
| 2133  | 1         | 4.55%   |
| 1334  | 1         | 4.55%   |
| 1067  | 1         | 4.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-3400 Series | 1         | 100%    |

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


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Chicony Electronics | 7         | 30.43%  |
| IMC Networks        | 4         | 17.39%  |
| Microdia            | 3         | 13.04%  |
| Lenovo              | 2         | 8.7%    |
| Syntek              | 1         | 4.35%   |
| Suyin               | 1         | 4.35%   |
| Samsung Electronics | 1         | 4.35%   |
| Ricoh               | 1         | 4.35%   |
| Quanta              | 1         | 4.35%   |
| Alcor Micro         | 1         | 4.35%   |
| Acer                | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD      | 2         | 8.7%    |
| Lenovo Integrated Webcam           | 2         | 8.7%    |
| IMC Networks USB2.0 HD UVC WebCam  | 2         | 8.7%    |
| Syntek Lenovo EasyCamera           | 1         | 4.35%   |
| Suyin Acer CrystalEye Webcam       | 1         | 4.35%   |
| Samsung Galaxy A5 (MTP)            | 1         | 4.35%   |
| Ricoh HD Webcam                    | 1         | 4.35%   |
| Quanta USB2.0 HD UVC WebCam        | 1         | 4.35%   |
| Microdia Integrated Webcam HD      | 1         | 4.35%   |
| IMC Networks USB2.0 VGA UVC WebCam | 1         | 4.35%   |
| IMC Networks Integrated Camera     | 1         | 4.35%   |
| Chicony USB 2.0 Camera             | 1         | 4.35%   |
| Chicony LG HD WebCam               | 1         | 4.35%   |
| Chicony Lenovo EasyCamera          | 1         | 4.35%   |
| Chicony HP Wide Vision HD Camera   | 1         | 4.35%   |
| Chicony HP HD Camera               | 1         | 4.35%   |
| Chicony EasyCamera                 | 1         | 4.35%   |
| Chicony 720p HD Camera             | 1         | 4.35%   |
| Alcor Micro USB 2.0 PC Camera      | 1         | 4.35%   |
| Acer Integrated Camera             | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 16.67%  |
| Upek                       | 1         | 16.67%  |
| Synaptics                  | 1         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |
| Goodix                     | 1         | 16.67%  |
| Elan Microelectronics      | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 16.67%  |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 16.67%  |
| Goodix FingerPrint                                         | 1         | 16.67%  |
| Elan ELAN:Fingerprint                                      | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 1         | 33.33%  |
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
| 0     | 17        | 53.13%  |
| 1     | 13        | 40.63%  |
| 2     | 2         | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 6         | 37.5%   |
| Chipcard           | 3         | 18.75%  |
| Net/wireless       | 2         | 12.5%   |
| Graphics card      | 2         | 12.5%   |
| Unassigned class   | 1         | 6.25%   |
| Sound              | 1         | 6.25%   |
| Bluetooth          | 1         | 6.25%   |

