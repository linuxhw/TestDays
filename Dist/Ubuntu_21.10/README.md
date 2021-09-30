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
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [b6f82cf92b](https://linux-hardware.org/?probe=b6f82cf92b) | Sep 30, 2021 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [0055a963ef](https://linux-hardware.org/?probe=0055a963ef) | Sep 30, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [8ea8e6afe8](https://linux-hardware.org/?probe=8ea8e6afe8) | Sep 30, 2021 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | Notebook    | [1b81ca9e7a](https://linux-hardware.org/?probe=1b81ca9e7a) | Sep 29, 2021 |
| ASRock        | 990FX Extreme4              | Desktop     | [9c631b51b1](https://linux-hardware.org/?probe=9c631b51b1) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [51b49beb10](https://linux-hardware.org/?probe=51b49beb10) | Sep 28, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [e8749db36a](https://linux-hardware.org/?probe=e8749db36a) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [aa1a6086e7](https://linux-hardware.org/?probe=aa1a6086e7) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [b05cdb0bab](https://linux-hardware.org/?probe=b05cdb0bab) | Sep 26, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [7f7c48cd3e](https://linux-hardware.org/?probe=7f7c48cd3e) | Sep 26, 2021 |
| ASRock        | X399M Taichi                | Desktop     | [eba541c6b9](https://linux-hardware.org/?probe=eba541c6b9) | Sep 25, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [357f7466e6](https://linux-hardware.org/?probe=357f7466e6) | Sep 25, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [fc93efcead](https://linux-hardware.org/?probe=fc93efcead) | Sep 25, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [8a2d72befe](https://linux-hardware.org/?probe=8a2d72befe) | Sep 24, 2021 |
| TUXEDO        | N7x0WU                      | Notebook    | [10f446b51e](https://linux-hardware.org/?probe=10f446b51e) | Sep 24, 2021 |
| ASRock        | Z390M Pro4                  | Desktop     | [138ae00012](https://linux-hardware.org/?probe=138ae00012) | Sep 23, 2021 |
| Dell          | Precision 7710              | Notebook    | [fa8e5cdff5](https://linux-hardware.org/?probe=fa8e5cdff5) | Sep 23, 2021 |
| Acer          | Swift SFX14-41G             | Notebook    | [6b06b9e5dd](https://linux-hardware.org/?probe=6b06b9e5dd) | Sep 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [5b337fdb0a](https://linux-hardware.org/?probe=5b337fdb0a) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [7c806aa7c5](https://linux-hardware.org/?probe=7c806aa7c5) | Sep 19, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [824a26d7e0](https://linux-hardware.org/?probe=824a26d7e0) | Sep 18, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [1fe8420099](https://linux-hardware.org/?probe=1fe8420099) | Sep 17, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [10f08c1bfd](https://linux-hardware.org/?probe=10f08c1bfd) | Sep 17, 2021 |
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


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.13.0-16-generic           | 18        | 33.96%  |
| 5.13.0-14-generic           | 13        | 24.53%  |
| 5.11.0-20-generic           | 5         | 9.43%   |
| 5.13.0-12-generic           | 2         | 3.77%   |
| 5.11.0-25-generic           | 2         | 3.77%   |
| 5.11.0-18-generic           | 2         | 3.77%   |
| 5.14.0-051400rc7-lowlatency | 1         | 1.89%   |
| 5.13.6-xanmod2-edge         | 1         | 1.89%   |
| 5.13.4-051304-generic       | 1         | 1.89%   |
| 5.13.2-051302-generic       | 1         | 1.89%   |
| 5.13.0-17-generic           | 1         | 1.89%   |
| 5.13.0-13-generic           | 1         | 1.89%   |
| 5.13.0-051300-generic       | 1         | 1.89%   |
| 5.11.0-31-generic           | 1         | 1.89%   |
| 5.11.0-26-generic           | 1         | 1.89%   |
| 5.11.0-22-generic           | 1         | 1.89%   |
| 5.11.0-16-generic           | 1         | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 35        | 67.31%  |
| 5.11.0  | 13        | 25%     |
| 5.14.0  | 1         | 1.92%   |
| 5.13.6  | 1         | 1.92%   |
| 5.13.4  | 1         | 1.92%   |
| 5.13.2  | 1         | 1.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 38        | 73.08%  |
| 5.11    | 13        | 25%     |
| 5.14    | 1         | 1.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 51        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 40        | 76.92%  |
| Unknown         | 5         | 9.62%   |
| X-Cinnamon      | 3         | 5.77%   |
| Cinnamon        | 2         | 3.85%   |
| Unity           | 1         | 1.92%   |
| GNOME Flashback | 1         | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 32        | 61.54%  |
| X11     | 17        | 32.69%  |
| Tty     | 2         | 3.85%   |
| Unknown | 1         | 1.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 21        | 41.18%  |
| Unknown | 20        | 39.22%  |
| GDM3    | 9         | 17.65%  |
| TDM     | 1         | 1.96%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 18        | 35.29%  |
| en_GB | 7         | 13.73%  |
| fr_FR | 4         | 7.84%   |
| de_DE | 4         | 7.84%   |
| sv_SE | 3         | 5.88%   |
| zh_CN | 2         | 3.92%   |
| pt_BR | 2         | 3.92%   |
| hu_HU | 2         | 3.92%   |
| es_MX | 2         | 3.92%   |
| en_IN | 2         | 3.92%   |
| ru_UA | 1         | 1.96%   |
| ru_RU | 1         | 1.96%   |
| ko_KR | 1         | 1.96%   |
| es_AR | 1         | 1.96%   |
| en_ZM | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 30        | 58.82%  |
| EFI  | 21        | 41.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 45        | 88.24%  |
| Btrfs | 4         | 7.84%   |
| Zfs   | 2         | 3.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 54.9%   |
| GPT     | 21        | 41.18%  |
| MBR     | 2         | 3.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 75%     |
| Yes       | 13        | 25%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 54.9%   |
| Yes       | 23        | 45.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 9         | 17.65%  |
| ASUSTek Computer    | 9         | 17.65%  |
| Dell                | 7         | 13.73%  |
| Gigabyte Technology | 5         | 9.8%    |
| Hewlett-Packard     | 4         | 7.84%   |
| ASRock              | 3         | 5.88%   |
| Intel               | 2         | 3.92%   |
| Acer                | 2         | 3.92%   |
| TUXEDO              | 1         | 1.96%   |
| Teclast             | 1         | 1.96%   |
| Positivo            | 1         | 1.96%   |
| MSI                 | 1         | 1.96%   |
| Medion              | 1         | 1.96%   |
| LG Electronics      | 1         | 1.96%   |
| Huanan              | 1         | 1.96%   |
| Google              | 1         | 1.96%   |
| Fujitsu             | 1         | 1.96%   |
| Apple               | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad T400 2768WGB            | 2         | 3.92%   |
| TUXEDO N7x0WU                           | 1         | 1.96%   |
| Teclast F6 Pro                          | 1         | 1.96%   |
| Positivo H14BT58                        | 1         | 1.96%   |
| MSI MS-7C94                             | 1         | 1.96%   |
| Medion X87085                           | 1         | 1.96%   |
| LG 22V280-L.BY31P1                      | 1         | 1.96%   |
| Lenovo ZhaoYang K3-ITL 82E3             | 1         | 1.96%   |
| Lenovo Z50-70 20354                     | 1         | 1.96%   |
| Lenovo V310-14IKB 80T2                  | 1         | 1.96%   |
| Lenovo ThinkPad X201 3626FAG            | 1         | 1.96%   |
| Lenovo ThinkPad T470 20JNS3M500         | 1         | 1.96%   |
| Lenovo ThinkPad T15g Gen 1 20URCTO1WW   | 1         | 1.96%   |
| Lenovo G570 20079                       | 1         | 1.96%   |
| Intel NUC11PAHi5                        | 1         | 1.96%   |
| Intel DG41WV AAE90316-103               | 1         | 1.96%   |
| Huanan X99 F8D V2.2                     | 1         | 1.96%   |
| HP ProBook 455 G6                       | 1         | 1.96%   |
| HP Pavilion Laptop 15-cs3xxx            | 1         | 1.96%   |
| HP Pavilion Gaming Laptop 15-dk0xxx     | 1         | 1.96%   |
| HP Compaq dc7900 Convertible Minitower  | 1         | 1.96%   |
| Google Nautilus                         | 1         | 1.96%   |
| Gigabyte H81M-S                         | 1         | 1.96%   |
| Gigabyte H81M-D2V                       | 1         | 1.96%   |
| Gigabyte F2A55M-HD2                     | 1         | 1.96%   |
| Gigabyte B85M-D3H                       | 1         | 1.96%   |
| Gigabyte B550 AORUS ELITE V2            | 1         | 1.96%   |
| Fujitsu S1100F                          | 1         | 1.96%   |
| Dell XPS 13 9343                        | 1         | 1.96%   |
| Dell XPS 13 9310                        | 1         | 1.96%   |
| Dell XPS 13 7390                        | 1         | 1.96%   |
| Dell Vostro 3550                        | 1         | 1.96%   |
| Dell Precision 7710                     | 1         | 1.96%   |
| Dell Latitude E6410                     | 1         | 1.96%   |
| Dell Inspiron 7506 2n1                  | 1         | 1.96%   |
| ASUS VivoBook_ASUSLaptop X580GD_NX580GD | 1         | 1.96%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN  | 1         | 1.96%   |
| ASUS VivoBook_ASUSLaptop X509DJ_M509DJ  | 1         | 1.96%   |
| ASUS VivoBook_ASUSLaptop X421UAY_M413UA | 1         | 1.96%   |
| ASUS ROG ZENITH II EXTREME              | 1         | 1.96%   |
| ASUS ROG Strix G533QS_G533QS            | 1         | 1.96%   |
| ASUS ROG Strix G533QR_G533QR            | 1         | 1.96%   |
| ASUS GL753VD                            | 1         | 1.96%   |
| ASUS A68HM-PLUS                         | 1         | 1.96%   |
| ASRock Z390M Pro4                       | 1         | 1.96%   |
| ASRock X399M Taichi                     | 1         | 1.96%   |
| ASRock 990FX Extreme4                   | 1         | 1.96%   |
| Apple MacBookPro8,1                     | 1         | 1.96%   |
| Acer Swift SFX14-41G                    | 1         | 1.96%   |
| Acer Aspire 5920                        | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 5         | 9.8%    |
| ASUS VivoBook       | 4         | 7.84%   |
| Dell XPS            | 3         | 5.88%   |
| ASUS ROG            | 3         | 5.88%   |
| HP Pavilion         | 2         | 3.92%   |
| TUXEDO N7x0WU       | 1         | 1.96%   |
| Teclast F6          | 1         | 1.96%   |
| Positivo H14BT58    | 1         | 1.96%   |
| MSI MS-7C94         | 1         | 1.96%   |
| Medion X87085       | 1         | 1.96%   |
| LG 22V280-L.BY31P1  | 1         | 1.96%   |
| Lenovo ZhaoYang     | 1         | 1.96%   |
| Lenovo Z50-70       | 1         | 1.96%   |
| Lenovo V310-14IKB   | 1         | 1.96%   |
| Lenovo G570         | 1         | 1.96%   |
| Intel NUC11PAHi5    | 1         | 1.96%   |
| Intel DG41WV        | 1         | 1.96%   |
| Huanan X99          | 1         | 1.96%   |
| HP ProBook          | 1         | 1.96%   |
| HP Compaq           | 1         | 1.96%   |
| Google Nautilus     | 1         | 1.96%   |
| Gigabyte H81M-S     | 1         | 1.96%   |
| Gigabyte H81M-D2V   | 1         | 1.96%   |
| Gigabyte F2A55M-HD2 | 1         | 1.96%   |
| Gigabyte B85M-D3H   | 1         | 1.96%   |
| Gigabyte B550       | 1         | 1.96%   |
| Fujitsu S1100F      | 1         | 1.96%   |
| Dell Vostro         | 1         | 1.96%   |
| Dell Precision      | 1         | 1.96%   |
| Dell Latitude       | 1         | 1.96%   |
| Dell Inspiron       | 1         | 1.96%   |
| ASUS GL753VD        | 1         | 1.96%   |
| ASUS A68HM-PLUS     | 1         | 1.96%   |
| ASRock Z390M        | 1         | 1.96%   |
| ASRock X399M        | 1         | 1.96%   |
| ASRock 990FX        | 1         | 1.96%   |
| Apple MacBookPro8   | 1         | 1.96%   |
| Acer Swift          | 1         | 1.96%   |
| Acer Aspire         | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 17        | 33.33%  |
| 2020 | 7         | 13.73%  |
| 2019 | 5         | 9.8%    |
| 2015 | 5         | 9.8%    |
| 2014 | 4         | 7.84%   |
| 2018 | 3         | 5.88%   |
| 2017 | 2         | 3.92%   |
| 2012 | 2         | 3.92%   |
| 2010 | 2         | 3.92%   |
| 2016 | 1         | 1.96%   |
| 2013 | 1         | 1.96%   |
| 2011 | 1         | 1.96%   |
| 2008 | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 32        | 62.75%  |
| Desktop     | 16        | 31.37%  |
| Convertible | 1         | 1.96%   |
| Mini pc     | 1         | 1.96%   |
| All in one  | 1         | 1.96%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 47        | 92.16%  |
| Enabled  | 4         | 7.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 50        | 98.04%  |
| Yes  | 1         | 1.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 30.77%  |
| 8.01-16.0   | 10        | 19.23%  |
| 3.01-4.0    | 8         | 15.38%  |
| 16.01-24.0  | 6         | 11.54%  |
| 32.01-64.0  | 5         | 9.62%   |
| 64.01-256.0 | 4         | 7.69%   |
| 24.01-32.0  | 2         | 3.85%   |
| 1.01-2.0    | 1         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 16        | 30.19%  |
| 1.01-2.0  | 16        | 30.19%  |
| 4.01-8.0  | 13        | 24.53%  |
| 3.01-4.0  | 5         | 9.43%   |
| 8.01-16.0 | 3         | 5.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 58.82%  |
| 2      | 11        | 21.57%  |
| 3      | 5         | 9.8%    |
| 5      | 3         | 5.88%   |
| 6      | 1         | 1.96%   |
| 4      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 68.63%  |
| Yes       | 16        | 31.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 82.35%  |
| No        | 9         | 17.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 74.51%  |
| No        | 13        | 25.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 68.63%  |
| No        | 16        | 31.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 7         | 13.73%  |
| USA         | 6         | 11.76%  |
| UK          | 5         | 9.8%    |
| France      | 4         | 7.84%   |
| Sweden      | 3         | 5.88%   |
| Brazil      | 3         | 5.88%   |
| Ukraine     | 2         | 3.92%   |
| India       | 2         | 3.92%   |
| Hungary     | 2         | 3.92%   |
| Chile       | 2         | 3.92%   |
| Zambia      | 1         | 1.96%   |
| South Korea | 1         | 1.96%   |
| Singapore   | 1         | 1.96%   |
| Russia      | 1         | 1.96%   |
| Poland      | 1         | 1.96%   |
| Malaysia    | 1         | 1.96%   |
| Lithuania   | 1         | 1.96%   |
| Italy       | 1         | 1.96%   |
| Finland     | 1         | 1.96%   |
| Denmark     | 1         | 1.96%   |
| Czechia     | 1         | 1.96%   |
| Cyprus      | 1         | 1.96%   |
| China       | 1         | 1.96%   |
| Canada      | 1         | 1.96%   |
| Argentina   | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Wittlich               | 4         | 7.84%   |
| Tatab??nya             | 2         | 3.92%   |
| Yongin-si              | 1         | 1.96%   |
| Whitethorn             | 1         | 1.96%   |
| Warsaw                 | 1         | 1.96%   |
| Uppsala                | 1         | 1.96%   |
| Turku                  | 1         | 1.96%   |
| Trivandrum             | 1         | 1.96%   |
| Trakai                 | 1         | 1.96%   |
| Tottenham              | 1         | 1.96%   |
| Toms River             | 1         | 1.96%   |
| Stockholm              | 1         | 1.96%   |
| Singapore              | 1         | 1.96%   |
| Shanghai               | 1         | 1.96%   |
| S??o Paulo             | 1         | 1.96%   |
| Santiago               | 1         | 1.96%   |
| Rosario                | 1         | 1.96%   |
| Rio de Janeiro         | 1         | 1.96%   |
| Rennes                 | 1         | 1.96%   |
| Prague                 | 1         | 1.96%   |
| Pitrufquen             | 1         | 1.96%   |
| Petaling Jaya          | 1         | 1.96%   |
| Paris                  | 1         | 1.96%   |
| Osasco                 | 1         | 1.96%   |
| Oleksandriya           | 1         | 1.96%   |
| Nizhny Tagil           | 1         | 1.96%   |
| Nicosia                | 1         | 1.96%   |
| Montreal               | 1         | 1.96%   |
| Marion                 | 1         | 1.96%   |
| Maidstone              | 1         | 1.96%   |
| Lyon                   | 1         | 1.96%   |
| Lusaka                 | 1         | 1.96%   |
| Leiston                | 1         | 1.96%   |
| Kyiv                   | 1         | 1.96%   |
| Helsingborg            | 1         | 1.96%   |
| Haselhorst             | 1         | 1.96%   |
| Glasgow                | 1         | 1.96%   |
| Fellbach               | 1         | 1.96%   |
| Esbjerg                | 1         | 1.96%   |
| Dallas                 | 1         | 1.96%   |
| Crewe                  | 1         | 1.96%   |
| Ciampino               | 1         | 1.96%   |
| Chennai                | 1         | 1.96%   |
| Charleville-M?�zi??res | 1         | 1.96%   |
| Brooklyn               | 1         | 1.96%   |
| Bad Wildungen          | 1         | 1.96%   |
| Austin                 | 1         | 1.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 21     | 21.25%  |
| Seagate             | 11        | 12     | 13.75%  |
| WDC                 | 8         | 12     | 10%     |
| Toshiba             | 5         | 6      | 6.25%   |
| SanDisk             | 5         | 6      | 6.25%   |
| Intel               | 5         | 7      | 6.25%   |
| SK Hynix            | 4         | 4      | 5%      |
| Kingston            | 3         | 5      | 3.75%   |
| Unknown             | 2         | 2      | 2.5%    |
| SPCC                | 2         | 2      | 2.5%    |
| PNY                 | 2         | 2      | 2.5%    |
| KIOXIA-EXCERIA      | 2         | 2      | 2.5%    |
| Hitachi             | 2         | 2      | 2.5%    |
| Crucial             | 2         | 3      | 2.5%    |
| SP                  | 1         | 1      | 1.25%   |
| Silicon Motion      | 1         | 3      | 1.25%   |
| Phison              | 1         | 1      | 1.25%   |
| Micron Technology   | 1         | 1      | 1.25%   |
| LITEON              | 1         | 1      | 1.25%   |
| KingDian            | 1         | 1      | 1.25%   |
| HGST                | 1         | 2      | 1.25%   |
| Hewlett-Packard     | 1         | 1      | 1.25%   |
| GOODRAM             | 1         | 2      | 1.25%   |
| China               | 1         | 1      | 1.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| SPCC Solid State Disk 128GB              | 2         | 2.3%    |
| SK Hynix HFM001TD3JX013N 1TB             | 2         | 2.3%    |
| Seagate Expansion 5TB                    | 2         | 2.3%    |
| Samsung SSD 870 EVO 250GB                | 2         | 2.3%    |
| Samsung SSD 850 EVO 120GB                | 2         | 2.3%    |
| KIOXIA-EXCERIA SATA SSD 480GB            | 2         | 2.3%    |
| WDC WDS500G2B0C-00PXH0 500GB             | 1         | 1.15%   |
| WDC WD80EZAZ-11TDBA0 8TB                 | 1         | 1.15%   |
| WDC WD7500BPKT-75PK4T0 752GB             | 1         | 1.15%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 1.15%   |
| WDC WD3200AAKS-00V6A0 320GB              | 1         | 1.15%   |
| WDC WD3200AAJS-56B4A0 320GB              | 1         | 1.15%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1         | 1.15%   |
| WDC WD10EZEX-00MFCA0 1TB                 | 1         | 1.15%   |
| Unknown SB64G  64GB                      | 1         | 1.15%   |
| Unknown MMC Card  64GB                   | 1         | 1.15%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1.15%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1.15%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD      | 1         | 1.15%   |
| Toshiba HDWL120 2TB                      | 1         | 1.15%   |
| Toshiba HDWD240 4TB                      | 1         | 1.15%   |
| SP PC60 1TB                              | 1         | 1.15%   |
| SK Hynix NVMe SSD Drive 512GB            | 1         | 1.15%   |
| SK Hynix HFM512GD3JX016N 512GB           | 1         | 1.15%   |
| Silicon Motion NVMe SSD Drive 256GB      | 1         | 1.15%   |
| Seagate ST9750420AS 752GB                | 1         | 1.15%   |
| Seagate ST9320423AS 320GB                | 1         | 1.15%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1.15%   |
| Seagate ST3250310AS 250GB                | 1         | 1.15%   |
| Seagate ST320DM000-1BD14C 320GB          | 1         | 1.15%   |
| Seagate ST1000DM003-9YN162 1TB           | 1         | 1.15%   |
| Seagate BUP Slim RD 2TB                  | 1         | 1.15%   |
| Seagate BUP Slim Mac SL 2TB              | 1         | 1.15%   |
| Seagate BUP Slim BK 1TB                  | 1         | 1.15%   |
| Seagate BarraCuda SSD ZA500CM10002 500GB | 1         | 1.15%   |
| SanDisk Ultra II 480GB SSD               | 1         | 1.15%   |
| SanDisk SD9SN8W256G1102 256GB SSD        | 1         | 1.15%   |
| SanDisk SD8SNAT256G1002 256GB SSD        | 1         | 1.15%   |
| SanDisk SD7SB3Q064G 56GB SSD             | 1         | 1.15%   |
| Sandisk NVMe SSD Drive 500GB             | 1         | 1.15%   |
| Samsung SSD 980 PRO 500GB                | 1         | 1.15%   |
| Samsung SSD 980 PRO 2TB                  | 1         | 1.15%   |
| Samsung SSD 970 EVO 500GB                | 1         | 1.15%   |
| Samsung SSD 860 EVO 500GB                | 1         | 1.15%   |
| Samsung SSD 860 EVO 1TB                  | 1         | 1.15%   |
| Samsung SSD 850 PRO 256GB                | 1         | 1.15%   |
| Samsung SSD 850 EVO 500GB                | 1         | 1.15%   |
| Samsung SSD 650 120GB                    | 1         | 1.15%   |
| Samsung NVMe SSD Drive 512GB             | 1         | 1.15%   |
| Samsung NVMe SSD Drive 250GB             | 1         | 1.15%   |
| Samsung NVMe SSD Drive 1024GB            | 1         | 1.15%   |
| Samsung MZVPW256HEGL-000H1 256GB         | 1         | 1.15%   |
| Samsung MZVLQ512HALU-00000 512GB         | 1         | 1.15%   |
| Samsung MZALQ512HALU-000L2 512GB         | 1         | 1.15%   |
| Samsung HD320KJ 320GB                    | 1         | 1.15%   |
| Samsung HD103SJ 1TB                      | 1         | 1.15%   |
| PNY CS900 240GB SSD                      | 1         | 1.15%   |
| PNY CS1030 1TB SSD                       | 1         | 1.15%   |
| Phison NVMe SSD Drive 1024GB             | 1         | 1.15%   |
| Micron 2300 NVMe 1024GB                  | 1         | 1.15%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 37.04%  |
| WDC                 | 7         | 11     | 25.93%  |
| Toshiba             | 4         | 5      | 14.81%  |
| Samsung Electronics | 2         | 2      | 7.41%   |
| Hitachi             | 2         | 2      | 7.41%   |
| HGST                | 1         | 2      | 3.7%    |
| Hewlett-Packard     | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 30.77%  |
| SanDisk             | 4         | 4      | 15.38%  |
| Kingston            | 3         | 5      | 11.54%  |
| SPCC                | 2         | 2      | 7.69%   |
| KIOXIA-EXCERIA      | 2         | 2      | 7.69%   |
| Crucial             | 2         | 3      | 7.69%   |
| Seagate             | 1         | 1      | 3.85%   |
| PNY                 | 1         | 1      | 3.85%   |
| LITEON              | 1         | 1      | 3.85%   |
| KingDian            | 1         | 1      | 3.85%   |
| China               | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 25        | 33     | 34.72%  |
| SSD     | 22        | 30     | 30.56%  |
| HDD     | 22        | 34     | 30.56%  |
| MMC     | 2         | 2      | 2.78%   |
| Unknown | 1         | 1      | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 59     | 50.77%  |
| NVMe | 25        | 33     | 38.46%  |
| SAS  | 5         | 6      | 7.69%   |
| MMC  | 2         | 2      | 3.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 39     | 61.36%  |
| 0.51-1.0   | 9         | 12     | 20.45%  |
| 1.01-2.0   | 4         | 4      | 9.09%   |
| 4.01-10.0  | 3         | 7      | 6.82%   |
| 3.01-4.0   | 1         | 2      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 30.77%  |
| 251-500    | 9         | 17.31%  |
| 51-100     | 9         | 17.31%  |
| 501-1000   | 7         | 13.46%  |
| 1001-2000  | 6         | 11.54%  |
| 1-20       | 3         | 5.77%   |
| 21-50      | 1         | 1.92%   |
| 2001-3000  | 1         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 14        | 26.92%  |
| 21-50     | 11        | 21.15%  |
| 101-250   | 11        | 21.15%  |
| 501-1000  | 6         | 11.54%  |
| 51-100    | 6         | 11.54%  |
| 251-500   | 2         | 3.85%   |
| 2001-3000 | 1         | 1.92%   |
| 1001-2000 | 1         | 1.92%   |

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
| Detected | 34        | 58     | 59.65%  |
| Works    | 23        | 42     | 40.35%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 35        | 49.3%   |
| AMD                          | 11        | 15.49%  |
| Samsung Electronics          | 9         | 12.68%  |
| SK Hynix                     | 4         | 5.63%   |
| Silicon Motion               | 2         | 2.82%   |
| Sandisk                      | 2         | 2.82%   |
| Phison Electronics           | 2         | 2.82%   |
| Toshiba America Info Systems | 1         | 1.41%   |
| Shenzhen Longsys Electronics | 1         | 1.41%   |
| Micron Technology            | 1         | 1.41%   |
| Marvell Technology Group     | 1         | 1.41%   |
| LSI Logic / Symbios Logic    | 1         | 1.41%   |
| ASMedia Technology           | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 8.97%   |
| SK Hynix Gold P31 SSD                                                            | 3         | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 3.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 3.85%   |
| Intel Non-Volatile memory controller                                             | 3         | 3.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 3.85%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 2.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 2.56%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.56%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 2.56%   |
| Intel SSD 660P Series                                                            | 2         | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 2.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 2.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.56%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                         | 2         | 2.56%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.28%   |
| SK Hynix PC300 NVMe Solid State Drive 512GB                                      | 1         | 1.28%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                 | 1         | 1.28%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.28%   |
| Sandisk Non-Volatile memory controller                                           | 1         | 1.28%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 1.28%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.28%   |
| Micron Non-Volatile memory controller                                            | 1         | 1.28%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                          | 1         | 1.28%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                   | 1         | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.28%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.28%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1         | 1.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.28%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1         | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.28%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.28%   |
| AMD X399 Series Chipset SATA Controller                                          | 1         | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.28%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 1.28%   |
| AMD FCH IDE Controller                                                           | 1         | 1.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 52.05%  |
| NVMe | 25        | 34.25%  |
| RAID | 5         | 6.85%   |
| IDE  | 4         | 5.48%   |
| SCSI | 1         | 1.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 38        | 74.51%  |
| AMD    | 13        | 25.49%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core m3-7Y30 CPU @ 1.00GHz                | 2         | 3.92%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 2         | 3.92%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 2         | 3.92%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 2         | 3.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 3.92%   |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 2         | 3.92%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz             | 1         | 1.96%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz     | 1         | 1.96%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1         | 1.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 1.96%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1         | 1.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 1.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 1.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.96%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 1.96%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 1.96%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 1         | 1.96%   |
| Intel Core i7-10875H CPU @ 2.30GHz              | 1         | 1.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 1.96%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 1         | 1.96%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1         | 1.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 1.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 1.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 1.96%   |
| Intel Core i5-2415M CPU @ 2.30GHz               | 1         | 1.96%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 1.96%   |
| Intel Core i3-4150 CPU @ 3.50GHz                | 1         | 1.96%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 1.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 1         | 1.96%   |
| Intel Celeron N4100 CPU @ 1.10GHz               | 1         | 1.96%   |
| Intel Celeron CPU N2807 @ 1.58GHz               | 1         | 1.96%   |
| Intel Celeron CPU B800 @ 1.50GHz                | 1         | 1.96%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 1.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 1.96%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor  | 1         | 1.96%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor  | 1         | 1.96%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 1.96%   |
| AMD Ryzen 7 5800U with Radeon Graphics          | 1         | 1.96%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 1         | 1.96%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1         | 1.96%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 1.96%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 1         | 1.96%   |
| AMD FX-6100 Six-Core Processor                  | 1         | 1.96%   |
| AMD A8-6600K APU with Radeon HD Graphics        | 1         | 1.96%   |
| AMD A4-4000 APU with Radeon HD Graphics         | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 11        | 21.57%  |
| Intel Core i5           | 11        | 21.57%  |
| Other                   | 4         | 7.84%   |
| Intel Core 2 Duo        | 4         | 7.84%   |
| Intel Celeron           | 3         | 5.88%   |
| AMD Ryzen 5             | 3         | 5.88%   |
| Intel Core m3           | 2         | 3.92%   |
| AMD Ryzen Threadripper  | 2         | 3.92%   |
| AMD Ryzen 9             | 2         | 3.92%   |
| AMD Ryzen 7             | 2         | 3.92%   |
| Intel Xeon              | 1         | 1.96%   |
| Intel Pentium Dual-Core | 1         | 1.96%   |
| Intel Core i3           | 1         | 1.96%   |
| AMD Ryzen 7 PRO         | 1         | 1.96%   |
| AMD FX                  | 1         | 1.96%   |
| AMD A8                  | 1         | 1.96%   |
| AMD A4                  | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 19        | 37.25%  |
| 4      | 17        | 33.33%  |
| 8      | 6         | 11.76%  |
| 6      | 4         | 7.84%   |
| 32     | 1         | 1.96%   |
| 28     | 1         | 1.96%   |
| 12     | 1         | 1.96%   |
| 3      | 1         | 1.96%   |
| 1      | 1         | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 98.04%  |
| 2      | 1         | 1.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 39        | 76.47%  |
| 1      | 12        | 23.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 54.9%   |
| 0x806c1    | 4         | 7.84%   |
| 0x906ea    | 3         | 5.88%   |
| 0x806e9    | 3         | 5.88%   |
| 0x1067a    | 2         | 3.92%   |
| 0xa0652    | 1         | 1.96%   |
| 0x906e9    | 1         | 1.96%   |
| 0x806ec    | 1         | 1.96%   |
| 0x806eb    | 1         | 1.96%   |
| 0x706e5    | 1         | 1.96%   |
| 0x306d4    | 1         | 1.96%   |
| 0x206a7    | 1         | 1.96%   |
| 0x20652    | 1         | 1.96%   |
| 0x0a50000b | 1         | 1.96%   |
| 0x08608103 | 1         | 1.96%   |
| 0x08001137 | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 23.53%  |
| Zen 3         | 5         | 9.8%    |
| Penryn        | 5         | 9.8%    |
| TigerLake     | 4         | 7.84%   |
| Haswell       | 4         | 7.84%   |
| SandyBridge   | 3         | 5.88%   |
| Zen           | 2         | 3.92%   |
| Westmere      | 2         | 3.92%   |
| Skylake       | 2         | 3.92%   |
| Piledriver    | 2         | 3.92%   |
| Broadwell     | 2         | 3.92%   |
| Zen+          | 1         | 1.96%   |
| Zen 2         | 1         | 1.96%   |
| Silvermont    | 1         | 1.96%   |
| IceLake       | 1         | 1.96%   |
| Goldmont plus | 1         | 1.96%   |
| CometLake     | 1         | 1.96%   |
| Bulldozer     | 1         | 1.96%   |
| Unknown       | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 50.77%  |
| Nvidia | 18        | 27.69%  |
| AMD    | 14        | 21.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 5.8%    |
| AMD Cezanne                                                                 | 4         | 5.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 4.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.9%    |
| Intel HD Graphics 630                                                       | 2         | 2.9%    |
| Intel HD Graphics 615                                                       | 2         | 2.9%    |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 2.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 2         | 2.9%    |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                | 2         | 2.9%    |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                       | 1         | 1.45%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1         | 1.45%   |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1         | 1.45%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1         | 1.45%   |
| Nvidia GP108M [GeForce MX230]                                               | 1         | 1.45%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 1.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                 | 1         | 1.45%   |
| Nvidia GM204GLM [Quadro M4000M]                                             | 1         | 1.45%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 1.45%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1         | 1.45%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 1.45%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1         | 1.45%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 1         | 1.45%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                    | 1         | 1.45%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 1         | 1.45%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1         | 1.45%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1         | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.45%   |
| Intel UHD Graphics 620                                                      | 1         | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 1         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 1         | 1.45%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 1         | 1.45%   |
| Intel HD Graphics 620                                                       | 1         | 1.45%   |
| Intel HD Graphics 5500                                                      | 1         | 1.45%   |
| Intel HD Graphics 530                                                       | 1         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1         | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 1.45%   |
| Intel DG1 [Iris Xe MAX Graphics]                                            | 1         | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 1         | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1         | 1.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1         | 1.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1         | 1.45%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                      | 1         | 1.45%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1         | 1.45%   |
| AMD Richland [Radeon HD 8570D]                                              | 1         | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1         | 1.45%   |
| AMD Picasso                                                                 | 1         | 1.45%   |
| AMD Lucienne                                                                | 1         | 1.45%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1         | 1.45%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1         | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 43.14%  |
| Intel + Nvidia | 9         | 17.65%  |
| 1 x AMD        | 9         | 17.65%  |
| AMD + Nvidia   | 4         | 7.84%   |
| 1 x Nvidia     | 3         | 5.88%   |
| 2 x Nvidia     | 2         | 3.92%   |
| 2 x Intel      | 1         | 1.96%   |
| Intel + AMD    | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 41        | 80.39%  |
| Proprietary | 9         | 17.65%  |
| Unknown     | 1         | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 80.39%  |
| 1.01-2.0   | 5         | 9.8%    |
| 0.01-0.5   | 4         | 7.84%   |
| 7.01-8.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 6         | 10.34%  |
| AU Optronics            | 6         | 10.34%  |
| Lenovo                  | 5         | 8.62%   |
| Dell                    | 5         | 8.62%   |
| Chimei Innolux          | 5         | 8.62%   |
| BOE                     | 4         | 6.9%    |
| Sharp                   | 3         | 5.17%   |
| LG Display              | 3         | 5.17%   |
| PANDA                   | 2         | 3.45%   |
| BenQ                    | 2         | 3.45%   |
| AOC                     | 2         | 3.45%   |
| Acer                    | 2         | 3.45%   |
| SKY                     | 1         | 1.72%   |
| RTK                     | 1         | 1.72%   |
| RRR                     | 1         | 1.72%   |
| Packard Bell            | 1         | 1.72%   |
| MStar                   | 1         | 1.72%   |
| LG Electronics          | 1         | 1.72%   |
| KDC                     | 1         | 1.72%   |
| InfoVision              | 1         | 1.72%   |
| Goldstar                | 1         | 1.72%   |
| CSO                     | 1         | 1.72%   |
| Chi Mei Optoelectronics | 1         | 1.72%   |
| ASUSTek Computer        | 1         | 1.72%   |
| Apple                   | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                  | 2         | 3.33%   |
| BenQ GL2580 BNQ78E5 1920x1080 544x303mm 24.5-inch                        | 2         | 3.33%   |
| Acer XV340CK P ACR06F3 3440x1440 800x335mm 34.1-inch                     | 2         | 3.33%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                     | 1         | 1.67%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                  | 1         | 1.67%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 1         | 1.67%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 1         | 1.67%   |
| Samsung Electronics U24E590 SAM0CD2 3840x2160 521x293mm 23.5-inch        | 1         | 1.67%   |
| Samsung Electronics SMS19A450 SAM0848 1280x1024 376x301mm 19.0-inch      | 1         | 1.67%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch    | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch     | 1         | 1.67%   |
| RTK LCD Monitor RTK2136 1280x800 473x296mm 22.0-inch                     | 1         | 1.67%   |
| RRR K3A8F HDMI RRR1730 1920x1080 300x260mm 15.6-inch                     | 1         | 1.67%   |
| PANDA LCD Monitor NCP003B 1920x1080 344x194mm 15.5-inch                  | 1         | 1.67%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 1         | 1.67%   |
| Packard Bell Viseo 160W PKB00D0 1366x768 344x193mm 15.5-inch             | 1         | 1.67%   |
| MStar TV_MONITOR MST0030 1440x900 1150x650mm 52.0-inch                   | 1         | 1.67%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                        | 1         | 1.67%   |
| LG Electronics LCD Monitor LG ULTRAWIDE                                  | 1         | 1.67%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD05CE 1920x1080 344x194mm 15.5-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch             | 1         | 1.67%   |
| Lenovo P27q-20 LEN61EA 2560x1440 609x349mm 27.6-inch                     | 1         | 1.67%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                 | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.67%   |
| KDC LCD Monitor KDC0001 1920x1200 263x164mm 12.2-inch                    | 1         | 1.67%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch             | 1         | 1.67%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 1         | 1.67%   |
| Dell UP2516D DEL40E0 2560x1440 550x310mm 24.9-inch                       | 1         | 1.67%   |
| Dell S2721DS DELA19D 2560x1440 597x336mm 27.0-inch                       | 1         | 1.67%   |
| Dell S2721DGF DEL41DB 2560x1440 597x336mm 27.0-inch                      | 1         | 1.67%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                      | 1         | 1.67%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                        | 1         | 1.67%   |
| Dell LCD Monitor P2419H 4480x1080                                        | 1         | 1.67%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch         | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 1.67%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE05EC 1366x768 309x173mm 13.9-inch                     | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch           | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO35EB 3840x2160 344x193mm 15.5-inch           | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 1         | 1.67%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch             | 1         | 1.67%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 1         | 1.67%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                         | 1         | 1.67%   |
| AOC 2050 AOC2050 1600x900 443x249mm 20.0-inch                            | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 23        | 41.07%  |
| 3840x2160 (4K)    | 6         | 10.71%  |
| 2560x1440 (QHD)   | 6         | 10.71%  |
| 1366x768 (WXGA)   | 4         | 7.14%   |
| 1440x900 (WXGA+)  | 3         | 5.36%   |
| 1280x800 (WXGA)   | 3         | 5.36%   |
| 3440x1440         | 2         | 3.57%   |
| 1920x1200 (WUXGA) | 2         | 3.57%   |
| 4480x1080         | 1         | 1.79%   |
| 3840x2400         | 1         | 1.79%   |
| 3200x1800 (QHD+)  | 1         | 1.79%   |
| 2560x1080         | 1         | 1.79%   |
| 1600x900 (HD+)    | 1         | 1.79%   |
| 1280x1024 (SXGA)  | 1         | 1.79%   |
| Unknown           | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 27.78%  |
| 13      | 10        | 18.52%  |
| 24      | 5         | 9.26%   |
| 27      | 4         | 7.41%   |
| 17      | 4         | 7.41%   |
| 14      | 3         | 5.56%   |
| 34      | 2         | 3.7%    |
| 23      | 2         | 3.7%    |
| 12      | 2         | 3.7%    |
| 52      | 1         | 1.85%   |
| 40      | 1         | 1.85%   |
| 25      | 1         | 1.85%   |
| 21      | 1         | 1.85%   |
| 20      | 1         | 1.85%   |
| 19      | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 40%     |
| 501-600     | 10        | 18.18%  |
| 201-300     | 9         | 16.36%  |
| 351-400     | 5         | 9.09%   |
| 701-800     | 2         | 3.64%   |
| 601-700     | 2         | 3.64%   |
| 401-500     | 2         | 3.64%   |
| 801-900     | 1         | 1.82%   |
| 1001-1500   | 1         | 1.82%   |
| Unknown     | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 38        | 71.7%   |
| 16/10   | 9         | 16.98%  |
| 21/9    | 2         | 3.77%   |
| 6/5     | 1         | 1.89%   |
| 5/4     | 1         | 1.89%   |
| 3/2     | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 27.27%  |
| 81-90          | 8         | 14.55%  |
| 71-80          | 5         | 9.09%   |
| 201-250        | 5         | 9.09%   |
| 301-350        | 4         | 7.27%   |
| 251-300        | 4         | 7.27%   |
| 121-130        | 4         | 7.27%   |
| 61-70          | 2         | 3.64%   |
| 351-500        | 2         | 3.64%   |
| 151-200        | 2         | 3.64%   |
| More than 1000 | 1         | 1.82%   |
| 131-140        | 1         | 1.82%   |
| 501-1000       | 1         | 1.82%   |
| Unknown        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 21        | 37.5%   |
| 101-120       | 12        | 21.43%  |
| 51-100        | 10        | 17.86%  |
| 161-240       | 6         | 10.71%  |
| More than 240 | 4         | 7.14%   |
| 1-50          | 2         | 3.57%   |
| Unknown       | 1         | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 43        | 82.69%  |
| 2     | 6         | 11.54%  |
| 3     | 2         | 3.85%   |
| 0     | 1         | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 29        | 40.28%  |
| Intel                         | 25        | 34.72%  |
| Qualcomm Atheros              | 4         | 5.56%   |
| Broadcom                      | 4         | 5.56%   |
| MEDIATEK                      | 3         | 4.17%   |
| Aquantia                      | 2         | 2.78%   |
| Xiaomi                        | 1         | 1.39%   |
| TP-Link                       | 1         | 1.39%   |
| Qualcomm                      | 1         | 1.39%   |
| OnePlus Technology (Shenzhen) | 1         | 1.39%   |
| Broadcom Limited              | 1         | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 25.58%  |
| MEDIATEK Network controller                                       | 3         | 3.49%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 3.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.33%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.33%   |
| Intel Wireless 8260                                               | 2         | 2.33%   |
| Intel Wireless 7265                                               | 2         | 2.33%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 2.33%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 2.33%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.33%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.16%   |
| TP-Link Archer T4U ver.3                                          | 1         | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.16%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.16%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]       | 1         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.16%   |
| OnePlus (Shenzhen) IN2013                                         | 1         | 1.16%   |
| Intel Wireless 3165                                               | 1         | 1.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.16%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.16%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.16%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.16%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 1.16%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.16%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.16%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.16%   |
| Broadcom Network controller                                       | 1         | 1.16%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.16%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1         | 1.16%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 1.16%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 1.16%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.16%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.16%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 55.26%  |
| Realtek Semiconductor | 5         | 13.16%  |
| Qualcomm Atheros      | 4         | 10.53%  |
| MEDIATEK              | 3         | 7.89%   |
| Broadcom              | 2         | 5.26%   |
| TP-Link               | 1         | 2.63%   |
| Qualcomm              | 1         | 2.63%   |
| Broadcom Limited      | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| MEDIATEK Network controller                                    | 3         | 7.89%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 7.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 5.26%   |
| Intel Wireless 8265 / 8275                                     | 2         | 5.26%   |
| Intel Wireless 8260                                            | 2         | 5.26%   |
| Intel Wireless 7265                                            | 2         | 5.26%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 5.26%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 5.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 5.26%   |
| TP-Link Archer T4U ver.3                                       | 1         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.63%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.63%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]    | 1         | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.63%   |
| Intel Wireless 3165                                            | 1         | 2.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 2.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 2.63%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 2.63%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.63%   |
| Broadcom Network controller                                    | 1         | 2.63%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 2.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 27        | 57.45%  |
| Intel                         | 12        | 25.53%  |
| Broadcom                      | 3         | 6.38%   |
| Aquantia                      | 2         | 4.26%   |
| Xiaomi                        | 1         | 2.13%   |
| Qualcomm Atheros              | 1         | 2.13%   |
| OnePlus Technology (Shenzhen) | 1         | 2.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 45.83%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 4.17%   |
| Intel I211 Gigabit Network Connection                             | 2         | 4.17%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 4.17%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 4.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 2.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.08%   |
| OnePlus (Shenzhen) IN2013                                         | 1         | 2.08%   |
| Intel Ethernet Controller I225-V                                  | 1         | 2.08%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.08%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.08%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.08%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1         | 2.08%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 2.08%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 42        | 52.5%   |
| WiFi     | 38        | 47.5%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 56.67%  |
| Ethernet | 26        | 43.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 27        | 52.94%  |
| 1     | 21        | 41.18%  |
| 3     | 2         | 3.92%   |
| 5     | 1         | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 76.47%  |
| Yes  | 12        | 23.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 50%     |
| Realtek Semiconductor           | 4         | 11.76%  |
| Qualcomm Atheros Communications | 3         | 8.82%   |
| IMC Networks                    | 3         | 8.82%   |
| Lite-On Technology              | 2         | 5.88%   |
| Cambridge Silicon Radio         | 2         | 5.88%   |
| Foxconn / Hon Hai               | 1         | 2.94%   |
| Broadcom                        | 1         | 2.94%   |
| Apple                           | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 10        | 29.41%  |
| Intel Bluetooth wireless interface                  | 4         | 11.76%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 5.88%   |
| Realtek Bluetooth Radio                             | 2         | 5.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 5.88%   |
| Intel AX200 Bluetooth                               | 2         | 5.88%   |
| IMC Networks Wireless_Device                        | 2         | 5.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.94%   |
| Lite-On Wireless_Device                             | 1         | 2.94%   |
| Lite-On Bluetooth Radio                             | 1         | 2.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.94%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.94%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 2.94%   |
| Broadcom BCM20702A0 Bluetooth                       | 1         | 2.94%   |
| Apple Bluetooth Host Controller                     | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 38        | 51.35%  |
| AMD                               | 12        | 16.22%  |
| Nvidia                            | 11        | 14.86%  |
| Elitegroup Computer Systems (ECS) | 2         | 2.7%    |
| XMOS                              | 1         | 1.35%   |
| Texas Instruments                 | 1         | 1.35%   |
| Satechi                           | 1         | 1.35%   |
| NXP Semiconductors                | 1         | 1.35%   |
| Logitech                          | 1         | 1.35%   |
| GN Netcom                         | 1         | 1.35%   |
| Focusrite-Novation                | 1         | 1.35%   |
| Creative Technology               | 1         | 1.35%   |
| Corsair                           | 1         | 1.35%   |
| C-Media Electronics               | 1         | 1.35%   |
| ASUSTek Computer                  | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 7         | 7.78%   |
| Intel Sunrise Point-LP HD Audio                                                   | 5         | 5.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5         | 5.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 4         | 4.44%   |
| Intel Cannon Lake PCH cAVS                                                        | 4         | 4.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3         | 3.33%   |
| Nvidia TU104 HD Audio Controller                                                  | 2         | 2.22%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 2.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2         | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2         | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 2.22%   |
| Elitegroup Computer Systems (ECS) FOSTEX USB AUDIO HP-A4                          | 2         | 2.22%   |
| AMD Trinity HDMI Audio Controller                                                 | 2         | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 2.22%   |
| AMD FCH Azalia Controller                                                         | 2         | 2.22%   |
| XMOS HIFI DSD                                                                     | 1         | 1.11%   |
| Texas Instruments PCM2906C Audio CODEC                                            | 1         | 1.11%   |
| Satechi Audio & PD Adapter                                                        | 1         | 1.11%   |
| NXP Semiconductors Monitor 09                                                     | 1         | 1.11%   |
| Nvidia High Definition Audio Controller                                           | 1         | 1.11%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1         | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1         | 1.11%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1         | 1.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 1.11%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 1.11%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 1.11%   |
| Nvidia GA102 High Definition Audio Controller                                     | 1         | 1.11%   |
| Logitech H600 [Wireless Headset]                                                  | 1         | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1         | 1.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1         | 1.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1         | 1.11%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 1.11%   |
| Intel Comet Lake PCH cAVS                                                         | 1         | 1.11%   |
| Intel CM238 HD Audio Controller                                                   | 1         | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1         | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 1         | 1.11%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 1         | 1.11%   |
| Intel Broadwell-U Audio Controller                                                | 1         | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 1.11%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1         | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 1         | 1.11%   |
| Intel 8 Series HD Audio Controller                                                | 1         | 1.11%   |
| GN Netcom Jabra EVOLVE Link MS                                                    | 1         | 1.11%   |
| Focusrite-Novation Scarlett 18i20 3rd Gen                                         | 1         | 1.11%   |
| Creative Technology SoundBlaster Audigy 2 NX                                      | 1         | 1.11%   |
| Corsair HS70 Pro Wireless Gaming Headset                                          | 1         | 1.11%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 1         | 1.11%   |
| ASUSTek Computer USB Audio                                                        | 1         | 1.11%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 1.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 1.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 1.11%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.11%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1         | 1.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 34.38%  |
| SK Hynix            | 6         | 18.75%  |
| Micron Technology   | 4         | 12.5%   |
| Unknown             | 3         | 9.38%   |
| Kingston            | 3         | 9.38%   |
| Crucial             | 2         | 6.25%   |
| Team                | 1         | 3.13%   |
| Ramaxel Technology  | 1         | 3.13%   |
| Elpida              | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 2         | 6.25%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s            | 2         | 6.25%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s           | 2         | 6.25%   |
| Unknown RAM UBE3D4AA-MGCR 8192MB Row Of Chips LPDDR4 4267MT/s       | 1         | 3.13%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                           | 1         | 3.13%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 3.13%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s                  | 1         | 3.13%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s                | 1         | 3.13%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s          | 1         | 3.13%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 3.13%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s            | 1         | 3.13%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 1         | 3.13%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 3.13%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DIMM DDR4 2667MT/s                 | 1         | 3.13%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s                 | 1         | 3.13%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s              | 1         | 3.13%   |
| Ramaxel RAM RMSA3260NA78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s      | 1         | 3.13%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 1         | 3.13%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s             | 1         | 3.13%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s           | 1         | 3.13%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s              | 1         | 3.13%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s                | 1         | 3.13%   |
| Kingston RAM KF3200C20S4/16GX 16GB SODIMM DDR4 3200MT/s             | 1         | 3.13%   |
| Elpida RAM Module 4GB Row Of Chips LPDDR3 1867MT/s                  | 1         | 3.13%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s          | 1         | 3.13%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s               | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 17        | 58.62%  |
| DDR3   | 5         | 17.24%  |
| LPDDR4 | 4         | 13.79%  |
| LPDDR3 | 3         | 10.34%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 17        | 58.62%  |
| DIMM         | 6         | 20.69%  |
| Row Of Chips | 5         | 17.24%  |
| Chip         | 1         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 11        | 35.48%  |
| 4096  | 7         | 22.58%  |
| 16384 | 6         | 19.35%  |
| 2048  | 5         | 16.13%  |
| 32768 | 2         | 6.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 7         | 23.33%  |
| 3200  | 6         | 20%     |
| 4267  | 3         | 10%     |
| 1867  | 2         | 6.67%   |
| 1600  | 2         | 6.67%   |
| 1067  | 2         | 6.67%   |
| 4266  | 1         | 3.33%   |
| 3733  | 1         | 3.33%   |
| 3600  | 1         | 3.33%   |
| 3533  | 1         | 3.33%   |
| 3400  | 1         | 3.33%   |
| 3000  | 1         | 3.33%   |
| 2133  | 1         | 3.33%   |
| 1334  | 1         | 3.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung M283x Series    | 2         | 66.67%  |
| Samsung SCX-3400 Series | 1         | 33.33%  |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 8         | 22.86%  |
| IMC Networks                  | 6         | 17.14%  |
| Quanta                        | 3         | 8.57%   |
| Microdia                      | 3         | 8.57%   |
| Lenovo                        | 3         | 8.57%   |
| Ricoh                         | 2         | 5.71%   |
| Logitech                      | 2         | 5.71%   |
| Syntek                        | 1         | 2.86%   |
| Suyin                         | 1         | 2.86%   |
| Sunplus Innovation Technology | 1         | 2.86%   |
| Samsung Electronics           | 1         | 2.86%   |
| Realtek Semiconductor         | 1         | 2.86%   |
| Apple                         | 1         | 2.86%   |
| Alcor Micro                   | 1         | 2.86%   |
| Acer                          | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo Integrated Webcam                | 3         | 8.57%   |
| IMC Networks USB2.0 HD UVC WebCam       | 3         | 8.57%   |
| Microdia Integrated_Webcam_HD           | 2         | 5.71%   |
| Logitech Webcam C930e                   | 2         | 5.71%   |
| IMC Networks Integrated Camera          | 2         | 5.71%   |
| Syntek Lenovo EasyCamera                | 1         | 2.86%   |
| Suyin Acer CrystalEye Webcam            | 1         | 2.86%   |
| Sunplus Integrated_Webcam_HD            | 1         | 2.86%   |
| Samsung Galaxy series, misc. (MTP mode) | 1         | 2.86%   |
| Ricoh Integrated Webcam                 | 1         | 2.86%   |
| Ricoh HD Webcam                         | 1         | 2.86%   |
| Realtek Integrated_Webcam_HD            | 1         | 2.86%   |
| Quanta USB2.0 HD UVC WebCam             | 1         | 2.86%   |
| Quanta HP Wide Vision HD Camera         | 1         | 2.86%   |
| Quanta HD User Facing                   | 1         | 2.86%   |
| Microdia Integrated Webcam HD           | 1         | 2.86%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 1         | 2.86%   |
| Chicony USB2.0 Camera                   | 1         | 2.86%   |
| Chicony USB 2.0 Camera                  | 1         | 2.86%   |
| Chicony LG HD WebCam                    | 1         | 2.86%   |
| Chicony Lenovo EasyCamera               | 1         | 2.86%   |
| Chicony HP Wide Vision HD Camera        | 1         | 2.86%   |
| Chicony HP HD Camera                    | 1         | 2.86%   |
| Chicony EasyCamera                      | 1         | 2.86%   |
| Chicony 720p HD Camera                  | 1         | 2.86%   |
| Apple FaceTime HD Camera                | 1         | 2.86%   |
| Alcor Micro USB 2.0 PC Camera           | 1         | 2.86%   |
| Acer Integrated Camera                  | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 2         | 28.57%  |
| Shenzhen Goodix Technology | 2         | 28.57%  |
| Validity Sensors           | 1         | 14.29%  |
| Upek                       | 1         | 14.29%  |
| Elan Microelectronics      | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 14.29%  |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 14.29%  |
| Shenzhen Goodix FingerPrint                                | 1         | 14.29%  |
| Elan ELAN:Fingerprint                                      | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 2         | 40%     |
| Broadcom    | 2         | 40%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |
| Broadcom 5880                                  | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 31        | 60.78%  |
| 1     | 17        | 33.33%  |
| 2     | 3         | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 7         | 31.82%  |
| Graphics card      | 5         | 22.73%  |
| Chipcard           | 5         | 22.73%  |
| Net/wireless       | 2         | 9.09%   |
| Unassigned class   | 1         | 4.55%   |
| Sound              | 1         | 4.55%   |
| Bluetooth          | 1         | 4.55%   |

