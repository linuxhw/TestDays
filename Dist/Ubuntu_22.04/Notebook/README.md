Ubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

Total: 70

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron N5110              | [606eb17f56](https://linux-hardware.org/?probe=606eb17f56) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [6b0cd44dbb](https://linux-hardware.org/?probe=6b0cd44dbb) | Apr 01, 2022 |
| Alienware     | M11x                        | [f83c01bb34](https://linux-hardware.org/?probe=f83c01bb34) | Apr 01, 2022 |
| Avell High... | A70 MOB                     | [9e095642f0](https://linux-hardware.org/?probe=9e095642f0) | Apr 01, 2022 |
| Dell          | Inspiron 3501               | [a14dde61dc](https://linux-hardware.org/?probe=a14dde61dc) | Apr 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [858142c2ab](https://linux-hardware.org/?probe=858142c2ab) | Apr 01, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [ceee79344c](https://linux-hardware.org/?probe=ceee79344c) | Mar 31, 2022 |
| HUAWEI        | CREM-WXX9                   | [83b60423e1](https://linux-hardware.org/?probe=83b60423e1) | Mar 30, 2022 |
| HP            | 250 G4                      | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| HUAWEI        | CREM-WXX9                   | [4626f2aeab](https://linux-hardware.org/?probe=4626f2aeab) | Mar 29, 2022 |
| MSI           | GP76 Leopard 11UG           | [93a6b587c2](https://linux-hardware.org/?probe=93a6b587c2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [30c09eec3b](https://linux-hardware.org/?probe=30c09eec3b) | Mar 28, 2022 |
| HUAWEI        | CREM-WXX9                   | [dbdd71e8b8](https://linux-hardware.org/?probe=dbdd71e8b8) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | [ecf7b98552](https://linux-hardware.org/?probe=ecf7b98552) | Mar 28, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e93a8600c](https://linux-hardware.org/?probe=0e93a8600c) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| HUAWEI        | MACH-WX9                    | [64e505d8d7](https://linux-hardware.org/?probe=64e505d8d7) | Mar 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [01e83234d9](https://linux-hardware.org/?probe=01e83234d9) | Mar 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [4fb374e78b](https://linux-hardware.org/?probe=4fb374e78b) | Mar 25, 2022 |
| HP            | EliteBook 840 G3            | [f06216a521](https://linux-hardware.org/?probe=f06216a521) | Mar 24, 2022 |
| HP            | Pavilion x2 Detachable      | [a82a2739a8](https://linux-hardware.org/?probe=a82a2739a8) | Mar 22, 2022 |
| Lenovo        | Z50-70 20354                | [b03762a80b](https://linux-hardware.org/?probe=b03762a80b) | Mar 22, 2022 |
| Framework     | Laptop                      | [b8fcafa943](https://linux-hardware.org/?probe=b8fcafa943) | Mar 20, 2022 |
| GPU Compan... | GWTC116-2                   | [3c0450f79e](https://linux-hardware.org/?probe=3c0450f79e) | Mar 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [1c22760a82](https://linux-hardware.org/?probe=1c22760a82) | Mar 12, 2022 |
| MSI           | Creator Z16 A11UET          | [1804e5eb77](https://linux-hardware.org/?probe=1804e5eb77) | Mar 09, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [9fd12bdd29](https://linux-hardware.org/?probe=9fd12bdd29) | Mar 06, 2022 |
| HUAWEI        | BOHB-WAX9                   | [915ca09de4](https://linux-hardware.org/?probe=915ca09de4) | Mar 05, 2022 |
| Toshiba       | Satellite C70D-A            | [c7dfd52f76](https://linux-hardware.org/?probe=c7dfd52f76) | Mar 05, 2022 |
| HP            | ZBook 15 G5                 | [f86a14c16d](https://linux-hardware.org/?probe=f86a14c16d) | Mar 05, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [206f3a7c01](https://linux-hardware.org/?probe=206f3a7c01) | Mar 02, 2022 |
| HP            | Presario CQ42               | [de34294599](https://linux-hardware.org/?probe=de34294599) | Feb 27, 2022 |
| Shanghai Z... | ZXE CRB                     | [7fe4a3390b](https://linux-hardware.org/?probe=7fe4a3390b) | Feb 25, 2022 |
| Timi          | TM1709                      | [16e699bea8](https://linux-hardware.org/?probe=16e699bea8) | Feb 25, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [076c8f6e01](https://linux-hardware.org/?probe=076c8f6e01) | Feb 23, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [85c09f63f0](https://linux-hardware.org/?probe=85c09f63f0) | Feb 23, 2022 |
| Acer          | Aspire A517-52              | [52976ad94b](https://linux-hardware.org/?probe=52976ad94b) | Feb 23, 2022 |
| MSI           | Stealth GS66 12UHS          | [bb8ef51c23](https://linux-hardware.org/?probe=bb8ef51c23) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [da103e44c5](https://linux-hardware.org/?probe=da103e44c5) | Feb 17, 2022 |
| HP            | 620                         | [bd89b469e4](https://linux-hardware.org/?probe=bd89b469e4) | Feb 14, 2022 |
| HP            | Pavilion 15                 | [9246e37578](https://linux-hardware.org/?probe=9246e37578) | Feb 09, 2022 |
| ASUSTek       | K52Je                       | [e1010983cf](https://linux-hardware.org/?probe=e1010983cf) | Feb 09, 2022 |
| Dell          | Latitude 3330               | [c3b39f74b4](https://linux-hardware.org/?probe=c3b39f74b4) | Jan 31, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [0a04b2d1b1](https://linux-hardware.org/?probe=0a04b2d1b1) | Jan 31, 2022 |
| HP            | 15                          | [81961b52a9](https://linux-hardware.org/?probe=81961b52a9) | Jan 29, 2022 |
| HP            | ProBook 445 G7              | [bceca55120](https://linux-hardware.org/?probe=bceca55120) | Jan 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [2de98fb4d8](https://linux-hardware.org/?probe=2de98fb4d8) | Jan 22, 2022 |
| HP            | ProBook 650 G5              | [111cb6822e](https://linux-hardware.org/?probe=111cb6822e) | Jan 21, 2022 |
| HP            | Pavilion Laptop 14-dv1xx... | [e092fc4b26](https://linux-hardware.org/?probe=e092fc4b26) | Jan 20, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [245123d0a8](https://linux-hardware.org/?probe=245123d0a8) | Jan 20, 2022 |
| Dell          | Latitude E6510              | [c0d3a6c31a](https://linux-hardware.org/?probe=c0d3a6c31a) | Jan 16, 2022 |
| Google        | Kefka                       | [e62fa3eea6](https://linux-hardware.org/?probe=e62fa3eea6) | Jan 10, 2022 |
| Timi          | RedmiBook Pro 15S           | [034079628f](https://linux-hardware.org/?probe=034079628f) | Jan 07, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | [ac0e3dfe29](https://linux-hardware.org/?probe=ac0e3dfe29) | Jan 07, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [666b0b18f5](https://linux-hardware.org/?probe=666b0b18f5) | Dec 30, 2021 |
| MSI           | GT73VR 6RE                  | [0f41e5dd07](https://linux-hardware.org/?probe=0f41e5dd07) | Dec 28, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [be79b3cd82](https://linux-hardware.org/?probe=be79b3cd82) | Dec 26, 2021 |
| Lenovo        | Flex 2-15 20405             | [ccc85b0783](https://linux-hardware.org/?probe=ccc85b0783) | Dec 13, 2021 |
| MSI           | Modern 15 A11MU             | [34b31c53cd](https://linux-hardware.org/?probe=34b31c53cd) | Dec 07, 2021 |
| Toshiba       | PORTEGE Z10T-A              | [5257d76a92](https://linux-hardware.org/?probe=5257d76a92) | Dec 05, 2021 |
| HP            | Laptop 15s-fq1xxx           | [f219ee63ff](https://linux-hardware.org/?probe=f219ee63ff) | Nov 30, 2021 |
| HP            | Laptop 15s-fq1xxx           | [3199d159a4](https://linux-hardware.org/?probe=3199d159a4) | Nov 30, 2021 |
| Lenovo        | Flex 2-15 20405             | [d191e3f97f](https://linux-hardware.org/?probe=d191e3f97f) | Nov 22, 2021 |
| Lenovo        | Flex 2-15 20405             | [6381b11078](https://linux-hardware.org/?probe=6381b11078) | Nov 22, 2021 |
| ASUSTek       | X58L                        | [c3df58b13b](https://linux-hardware.org/?probe=c3df58b13b) | Nov 10, 2021 |
| ASUSTek       | X58L                        | [e1425f037e](https://linux-hardware.org/?probe=e1425f037e) | Nov 10, 2021 |
| ASUSTek       | X58L                        | [f64ba3a9e4](https://linux-hardware.org/?probe=f64ba3a9e4) | Nov 10, 2021 |
| Dell          | Inspiron 1464               | [26f50eb4a8](https://linux-hardware.org/?probe=26f50eb4a8) | Nov 06, 2021 |
| Dell          | Inspiron 11 - 3147          | [6b1a282c17](https://linux-hardware.org/?probe=6b1a282c17) | Nov 05, 2021 |
| Dell          | Inspiron 1464               | [4063779d5a](https://linux-hardware.org/?probe=4063779d5a) | Nov 01, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.15.0-23-generic           | 12        | 22.22%  |
| 5.15.0-18-generic           | 12        | 22.22%  |
| 5.15.0-17-generic           | 7         | 12.96%  |
| 5.13.0-19-generic           | 5         | 9.26%   |
| 5.15.0-22-generic           | 4         | 7.41%   |
| 5.17.0-051700-generic       | 2         | 3.7%    |
| 5.17.0-051700rc5-lowlatency | 1         | 1.85%   |
| 5.16.0-051600-generic       | 1         | 1.85%   |
| 5.15.6-051506-generic       | 1         | 1.85%   |
| 5.15.17-xanmod2             | 1         | 1.85%   |
| 5.15.15-76051515-generic    | 1         | 1.85%   |
| 5.15.12-051512-generic      | 1         | 1.85%   |
| 5.15.11-051511-generic      | 1         | 1.85%   |
| 5.15.10-051510-generic      | 1         | 1.85%   |
| 5.15.0-14-generic           | 1         | 1.85%   |
| 5.15.0-13-generic           | 1         | 1.85%   |
| 5.15.0-12-generic           | 1         | 1.85%   |
| 5.15.0-11-generic           | 1         | 1.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 38        | 71.7%   |
| 5.13.0  | 5         | 9.43%   |
| 5.17.0  | 3         | 5.66%   |
| 5.16.0  | 1         | 1.89%   |
| 5.15.6  | 1         | 1.89%   |
| 5.15.17 | 1         | 1.89%   |
| 5.15.15 | 1         | 1.89%   |
| 5.15.12 | 1         | 1.89%   |
| 5.15.11 | 1         | 1.89%   |
| 5.15.10 | 1         | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 44        | 83.02%  |
| 5.13    | 5         | 9.43%   |
| 5.17    | 3         | 5.66%   |
| 5.16    | 1         | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 53        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 46        | 85.19%  |
| Unknown           | 5         | 9.26%   |
| Yaru:ubuntu:GNOME | 1         | 1.85%   |
| GNUstep           | 1         | 1.85%   |
| Cinnamon          | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 30        | 55.56%  |
| X11     | 19        | 35.19%  |
| Tty     | 4         | 7.41%   |
| Unknown | 1         | 1.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 44        | 83.02%  |
| Unknown | 7         | 13.21%  |
| LightDM | 1         | 1.89%   |
| GDM     | 1         | 1.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 27        | 50.94%  |
| en_IN   | 6         | 11.32%  |
| de_DE   | 3         | 5.66%   |
| ru_RU   | 2         | 3.77%   |
| pt_BR   | 2         | 3.77%   |
| fr_FR   | 2         | 3.77%   |
| en_GB   | 2         | 3.77%   |
| zh_CN   | 1         | 1.89%   |
| pl_PL   | 1         | 1.89%   |
| it_IT   | 1         | 1.89%   |
| hu_HU   | 1         | 1.89%   |
| en_SG   | 1         | 1.89%   |
| en_IL   | 1         | 1.89%   |
| en_CA   | 1         | 1.89%   |
| de_IT   | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 29        | 54.72%  |
| EFI  | 24        | 45.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 50        | 92.59%  |
| Zfs     | 2         | 3.7%    |
| Overlay | 1         | 1.85%   |
| Btrfs   | 1         | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 50.94%  |
| GPT     | 23        | 43.4%   |
| MBR     | 3         | 5.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 86.79%  |
| Yes       | 7         | 13.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 50.94%  |
| Yes       | 26        | 49.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 14        | 26.42%  |
| Lenovo                         | 8         | 15.09%  |
| ASUSTek Computer               | 7         | 13.21%  |
| Dell                           | 6         | 11.32%  |
| MSI                            | 5         | 9.43%   |
| HUAWEI                         | 3         | 5.66%   |
| Toshiba                        | 2         | 3.77%   |
| Timi                           | 1         | 1.89%   |
| Shanghai Zhaoxin Semiconductor | 1         | 1.89%   |
| GPU Company                    | 1         | 1.89%   |
| Google                         | 1         | 1.89%   |
| Framework                      | 1         | 1.89%   |
| Avell High Performance         | 1         | 1.89%   |
| Alienware                      | 1         | 1.89%   |
| Acer                           | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba Satellite C70D-A                          | 1         | 1.89%   |
| Toshiba PORTEGE Z10T-A                            | 1         | 1.89%   |
| Timi TM1709                                       | 1         | 1.89%   |
| Shanghai Zhaoxin ZXE CRB                          | 1         | 1.89%   |
| MSI Stealth GS66 12UHS                            | 1         | 1.89%   |
| MSI Modern 15 A11MU                               | 1         | 1.89%   |
| MSI GT73VR 6RE                                    | 1         | 1.89%   |
| MSI GP76 Leopard 11UG                             | 1         | 1.89%   |
| MSI Creator Z16 A11UET                            | 1         | 1.89%   |
| Lenovo Z50-70 20354                               | 1         | 1.89%   |
| Lenovo ThinkPad T14s Gen 2a 20XF004WUS            | 1         | 1.89%   |
| Lenovo ThinkPad E15 Gen 2 20TES2H500              | 1         | 1.89%   |
| Lenovo ThinkBook 15 G3 ACL 21A4                   | 1         | 1.89%   |
| Lenovo Legion 7 16ACHg6 82N6                      | 1         | 1.89%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                  | 1         | 1.89%   |
| Lenovo IdeaPad 5 14ITL05 82FE                     | 1         | 1.89%   |
| Lenovo Flex 2-15 20405                            | 1         | 1.89%   |
| HUAWEI MACH-WX9                                   | 1         | 1.89%   |
| HUAWEI CREM-WXX9                                  | 1         | 1.89%   |
| HUAWEI BOHB-WAX9                                  | 1         | 1.89%   |
| HP ZBook Power 15.6 inch G8 Mobile Workstation PC | 1         | 1.89%   |
| HP ZBook 15 G5                                    | 1         | 1.89%   |
| HP ProBook 650 G5                                 | 1         | 1.89%   |
| HP ProBook 445 G7                                 | 1         | 1.89%   |
| HP Presario CQ42                                  | 1         | 1.89%   |
| HP Pavilion x2 Detachable                         | 1         | 1.89%   |
| HP Pavilion Laptop 14-dv1xxx                      | 1         | 1.89%   |
| HP Pavilion 15                                    | 1         | 1.89%   |
| HP Laptop 15s-fq1xxx                              | 1         | 1.89%   |
| HP ENVY Laptop 13-ad1xx                           | 1         | 1.89%   |
| HP EliteBook 840 G3                               | 1         | 1.89%   |
| HP 620                                            | 1         | 1.89%   |
| HP 250 G4                                         | 1         | 1.89%   |
| HP 15                                             | 1         | 1.89%   |
| GPU Company GWTC116-2                             | 1         | 1.89%   |
| Google Kefka                                      | 1         | 1.89%   |
| Framework Laptop                                  | 1         | 1.89%   |
| Dell Latitude E6510                               | 1         | 1.89%   |
| Dell Latitude 3330                                | 1         | 1.89%   |
| Dell Inspiron N5110                               | 1         | 1.89%   |
| Dell Inspiron 3501                                | 1         | 1.89%   |
| Dell Inspiron 1464                                | 1         | 1.89%   |
| Dell Inspiron 11 - 3147                           | 1         | 1.89%   |
| Avell High Performance A70 MOB                    | 1         | 1.89%   |
| ASUS X58L                                         | 1         | 1.89%   |
| ASUS ROG Zephyrus M16 GU603ZW_GU603ZW             | 1         | 1.89%   |
| ASUS ROG Zephyrus M16 GU603HE_GU603HE             | 1         | 1.89%   |
| ASUS ROG Zephyrus G15 GA502IU_GA502IU             | 1         | 1.89%   |
| ASUS ROG Zephyrus G14 GA401IH_GA401IH             | 1         | 1.89%   |
| ASUS K52Je                                        | 1         | 1.89%   |
| ASUS ASUS TUF Gaming F17 FX706HEB_FX706HEB        | 1         | 1.89%   |
| Alienware M11x                                    | 1         | 1.89%   |
| Acer Aspire A517-52                               | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Inspiron              | 4         | 7.55%   |
| ASUS ROG                   | 4         | 7.55%   |
| HP Pavilion                | 3         | 5.66%   |
| Lenovo ThinkPad            | 2         | 3.77%   |
| Lenovo IdeaPad             | 2         | 3.77%   |
| HP ZBook                   | 2         | 3.77%   |
| HP ProBook                 | 2         | 3.77%   |
| Dell Latitude              | 2         | 3.77%   |
| Toshiba Satellite          | 1         | 1.89%   |
| Toshiba PORTEGE            | 1         | 1.89%   |
| Timi TM1709                | 1         | 1.89%   |
| Shanghai Zhaoxin ZXE       | 1         | 1.89%   |
| MSI Stealth                | 1         | 1.89%   |
| MSI Modern                 | 1         | 1.89%   |
| MSI GT73VR                 | 1         | 1.89%   |
| MSI GP76                   | 1         | 1.89%   |
| MSI Creator                | 1         | 1.89%   |
| Lenovo Z50-70              | 1         | 1.89%   |
| Lenovo ThinkBook           | 1         | 1.89%   |
| Lenovo Legion              | 1         | 1.89%   |
| Lenovo Flex                | 1         | 1.89%   |
| HUAWEI MACH-WX9            | 1         | 1.89%   |
| HUAWEI CREM-WXX9           | 1         | 1.89%   |
| HUAWEI BOHB-WAX9           | 1         | 1.89%   |
| HP Presario                | 1         | 1.89%   |
| HP Laptop                  | 1         | 1.89%   |
| HP ENVY                    | 1         | 1.89%   |
| HP EliteBook               | 1         | 1.89%   |
| HP 620                     | 1         | 1.89%   |
| HP 250                     | 1         | 1.89%   |
| HP 15                      | 1         | 1.89%   |
| GPU Company GWTC116-2      | 1         | 1.89%   |
| Google Kefka               | 1         | 1.89%   |
| Framework Laptop           | 1         | 1.89%   |
| Avell High Performance A70 | 1         | 1.89%   |
| ASUS X58L                  | 1         | 1.89%   |
| ASUS K52Je                 | 1         | 1.89%   |
| ASUS ASUS                  | 1         | 1.89%   |
| Alienware M11x             | 1         | 1.89%   |
| Acer Aspire                | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 18        | 33.96%  |
| 2020 | 7         | 13.21%  |
| 2010 | 6         | 11.32%  |
| 2013 | 5         | 9.43%   |
| 2018 | 4         | 7.55%   |
| 2019 | 3         | 5.66%   |
| 2014 | 3         | 5.66%   |
| 2015 | 2         | 3.77%   |
| 2022 | 1         | 1.89%   |
| 2017 | 1         | 1.89%   |
| 2016 | 1         | 1.89%   |
| 2011 | 1         | 1.89%   |
| 2008 | 1         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 53        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 45        | 84.91%  |
| Enabled  | 8         | 15.09%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 98.11%  |
| Yes  | 1         | 1.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 12        | 22.64%  |
| 16.01-24.0  | 9         | 16.98%  |
| 32.01-64.0  | 8         | 15.09%  |
| 3.01-4.0    | 8         | 15.09%  |
| 8.01-16.0   | 7         | 13.21%  |
| 24.01-32.0  | 3         | 5.66%   |
| 2.01-3.0    | 2         | 3.77%   |
| 64.01-256.0 | 2         | 3.77%   |
| 1.01-2.0    | 2         | 3.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 30.19%  |
| 2.01-3.0   | 14        | 26.42%  |
| 1.01-2.0   | 12        | 22.64%  |
| 3.01-4.0   | 5         | 9.43%   |
| 8.01-16.0  | 2         | 3.77%   |
| 0.01-0.5   | 2         | 3.77%   |
| 24.01-32.0 | 1         | 1.89%   |
| 0.51-1.0   | 1         | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 73.58%  |
| 2      | 12        | 22.64%  |
| 3      | 2         | 3.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 73.58%  |
| Yes       | 14        | 26.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 73.58%  |
| No        | 14        | 26.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 83.33%  |
| No        | 9         | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 15.09%  |
| India       | 7         | 13.21%  |
| Germany     | 4         | 7.55%   |
| France      | 4         | 7.55%   |
| Poland      | 3         | 5.66%   |
| Italy       | 3         | 5.66%   |
| China       | 3         | 5.66%   |
| Taiwan      | 2         | 3.77%   |
| Russia      | 2         | 3.77%   |
| Brazil      | 2         | 3.77%   |
| UK          | 1         | 1.89%   |
| Thailand    | 1         | 1.89%   |
| Spain       | 1         | 1.89%   |
| Slovenia    | 1         | 1.89%   |
| Singapore   | 1         | 1.89%   |
| Romania     | 1         | 1.89%   |
| Netherlands | 1         | 1.89%   |
| Myanmar     | 1         | 1.89%   |
| Mexico      | 1         | 1.89%   |
| Israel      | 1         | 1.89%   |
| Hungary     | 1         | 1.89%   |
| Egypt       | 1         | 1.89%   |
| Colombia    | 1         | 1.89%   |
| Canada      | 1         | 1.89%   |
| Argentina   | 1         | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Moses Lake               | 2         | 3.77%   |
| Kunming                  | 2         | 3.77%   |
| Chennai                  | 2         | 3.77%   |
| Chandigarh               | 2         | 3.77%   |
| Boeschepe                | 2         | 3.77%   |
| Worms                    | 1         | 1.89%   |
| Warsaw                   | 1         | 1.89%   |
| Wake Forest              | 1         | 1.89%   |
| Tubarao                  | 1         | 1.89%   |
| The Hague                | 1         | 1.89%   |
| Tel Aviv                 | 1         | 1.89%   |
| Taoyuan District         | 1         | 1.89%   |
| Taipei                   | 1         | 1.89%   |
| St Petersburg            | 1         | 1.89%   |
| Singapore                | 1         | 1.89%   |
| Siegen                   | 1         | 1.89%   |
| Seward                   | 1         | 1.89%   |
| San Francisco            | 1         | 1.89%   |
| Richland Center          | 1         | 1.89%   |
| Pune                     | 1         | 1.89%   |
| Porto Alegre             | 1         | 1.89%   |
| Ploieşti                | 1         | 1.89%   |
| Paris                    | 1         | 1.89%   |
| Papun                    | 1         | 1.89%   |
| Palermo                  | 1         | 1.89%   |
| Palau-solita i Plegamans | 1         | 1.89%   |
| Orehova Vas              | 1         | 1.89%   |
| Mountain Grove           | 1         | 1.89%   |
| Moscow                   | 1         | 1.89%   |
| Marnaz                   | 1         | 1.89%   |
| Mariposa                 | 1         | 1.89%   |
| Ludhiana                 | 1         | 1.89%   |
| Legionowo                | 1         | 1.89%   |
| Khlong Luang             | 1         | 1.89%   |
| Hyderabad                | 1         | 1.89%   |
| Henderson                | 1         | 1.89%   |
| Grandview                | 1         | 1.89%   |
| Glasgow                  | 1         | 1.89%   |
| Gdansk                   | 1         | 1.89%   |
| Ensenada                 | 1         | 1.89%   |
| Düsseldorf              | 1         | 1.89%   |
| Dresden                  | 1         | 1.89%   |
| Collepietra              | 1         | 1.89%   |
| Cartagena                | 1         | 1.89%   |
| Cairo                    | 1         | 1.89%   |
| Budapest                 | 1         | 1.89%   |
| Brughiere                | 1         | 1.89%   |
| Beijing                  | 1         | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 20     | 27.42%  |
| WDC                 | 9         | 11     | 14.52%  |
| Seagate             | 8         | 8      | 12.9%   |
| Unknown             | 6         | 7      | 9.68%   |
| Kingston            | 3         | 3      | 4.84%   |
| Intel               | 3         | 3      | 4.84%   |
| Toshiba             | 2         | 2      | 3.23%   |
| SK Hynix            | 2         | 2      | 3.23%   |
| SanDisk             | 2         | 2      | 3.23%   |
| KIOXIA              | 2         | 2      | 3.23%   |
| PNY                 | 1         | 1      | 1.61%   |
| PLEXTOR             | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 2      | 1.61%   |
| LITEON              | 1         | 1      | 1.61%   |
| KLEVV               | 1         | 1      | 1.61%   |
| Hitachi             | 1         | 1      | 1.61%   |
| China               | 1         | 1      | 1.61%   |
| ADATA Technology    | 1         | 2      | 1.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST9500420AS 500GB              | 2         | 3.08%   |
| Samsung NVMe SSD Drive 512GB           | 2         | 3.08%   |
| Samsung NVMe SSD Drive 256GB           | 2         | 3.08%   |
| Intel NVMe SSD Drive 512GB             | 2         | 3.08%   |
| WDC WDS100T1X0E-00AFY0 1TB             | 1         | 1.54%   |
| WDC WDBNCE0010PNC 1TB SSD              | 1         | 1.54%   |
| WDC WD3200BPVT-75JJ5T0 320GB           | 1         | 1.54%   |
| WDC WD10SPCX-24HWST1 1TB               | 1         | 1.54%   |
| WDC WD10JPVX-60JC3T0 1TB               | 1         | 1.54%   |
| WDC PC SN810 SDCPNRZ-2T00-1032 2TB     | 1         | 1.54%   |
| WDC PC SN730 SDBPNTY-512G              | 1         | 1.54%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB   | 1         | 1.54%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB   | 1         | 1.54%   |
| Unknown SD/MMC/MS PRO 32GB             | 1         | 1.54%   |
| Unknown SC128  128GB                   | 1         | 1.54%   |
| Unknown NVMe SSD Drive 512GB           | 1         | 1.54%   |
| Unknown MMC Card  32GB                 | 1         | 1.54%   |
| Unknown MMC Card  16GB                 | 1         | 1.54%   |
| Unknown Biwin  64GB                    | 1         | 1.54%   |
| Toshiba MQ01ABD100M 1TB                | 1         | 1.54%   |
| Toshiba KXG50ZNV512G 512GB             | 1         | 1.54%   |
| SK Hynix SKHynix_HFS001TDE9X084N 1TB   | 1         | 1.54%   |
| SK Hynix SKHynix_HFM256GD3HX015N 256GB | 1         | 1.54%   |
| Seagate ST9320423AS 320GB              | 1         | 1.54%   |
| Seagate ST9320325AS 320GB              | 1         | 1.54%   |
| Seagate ST500LT012-1DG142 500GB        | 1         | 1.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 1         | 1.54%   |
| Seagate ST320LM001 HN-M320MBB 320GB    | 1         | 1.54%   |
| Seagate ST1000LX015-1U7172 1TB         | 1         | 1.54%   |
| SanDisk SSD PLUS 240 GB                | 1         | 1.54%   |
| Sandisk NVMe SSD Drive 1024GB          | 1         | 1.54%   |
| Samsung SSD 860 EVO 1TB                | 1         | 1.54%   |
| Samsung SSD 850 EVO 500GB              | 1         | 1.54%   |
| Samsung SSD 750 EVO 250GB              | 1         | 1.54%   |
| Samsung NVMe SSD Drive 2TB             | 1         | 1.54%   |
| Samsung NVMe SSD Drive 1024GB          | 1         | 1.54%   |
| Samsung MZVLQ256HAJD-000H1 256GB       | 1         | 1.54%   |
| Samsung MZVLB512HAJQ-000H1 512GB       | 1         | 1.54%   |
| Samsung MZVLB1T0HBLR-000L2 1TB         | 1         | 1.54%   |
| Samsung MZVL21T0HCLR-00B00 1TB         | 1         | 1.54%   |
| Samsung MZNLN128HAHQ-00000 128GB SSD   | 1         | 1.54%   |
| Samsung MZMTE256HMHP-00005 256GB SSD   | 1         | 1.54%   |
| Samsung MZALQ512HALU-000L2 512GB       | 1         | 1.54%   |
| Samsung MZALQ256HAJD-000L1 256GB       | 1         | 1.54%   |
| Samsung HM501II 500GB                  | 1         | 1.54%   |
| Samsung HM160HI 160GB                  | 1         | 1.54%   |
| PNY CS900 240GB SSD                    | 1         | 1.54%   |
| PLEXTOR PX-512M5Pro 512GB SSD          | 1         | 1.54%   |
| Micron NVMe SSD Drive 1024GB           | 1         | 1.54%   |
| Micron 3400_MTFDKBA1T0TFH 1TB          | 1         | 1.54%   |
| LITEON CV8-8E128-HP 128GB SSD          | 1         | 1.54%   |
| KLEVV NEO N400 SSD 240GB               | 1         | 1.54%   |
| KIOXIA NVMe SSD Drive 512GB            | 1         | 1.54%   |
| KIOXIA NVMe SSD Drive 256GB            | 1         | 1.54%   |
| Kingston SA2000M81000G 1TB             | 1         | 1.54%   |
| Kingston OM8PCP3512F-AI1 512GB         | 1         | 1.54%   |
| Kingston NVMe SSD Drive 512GB          | 1         | 1.54%   |
| Intel SSDPEKNU512GZ 512GB              | 1         | 1.54%   |
| Hitachi HTS545016B9A300 160GB          | 1         | 1.54%   |
| China 256GB SSD                        | 1         | 1.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 50%     |
| WDC                 | 3         | 4      | 18.75%  |
| Samsung Electronics | 2         | 2      | 12.5%   |
| Unknown             | 1         | 1      | 6.25%   |
| Toshiba             | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 41.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| PNY                 | 1         | 1      | 8.33%   |
| PLEXTOR             | 1         | 1      | 8.33%   |
| LITEON              | 1         | 1      | 8.33%   |
| KLEVV               | 1         | 1      | 8.33%   |
| China               | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 29        | 36     | 49.15%  |
| HDD  | 15        | 17     | 25.42%  |
| SSD  | 11        | 12     | 18.64%  |
| MMC  | 4         | 5      | 6.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 29        | 36     | 48.33%  |
| SATA | 26        | 28     | 43.33%  |
| MMC  | 4         | 5      | 6.67%   |
| SAS  | 1         | 1      | 1.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 21     | 74.07%  |
| 0.51-1.0   | 7         | 8      | 25.93%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 17        | 31.48%  |
| 251-500    | 16        | 29.63%  |
| 501-1000   | 7         | 12.96%  |
| 1-20       | 5         | 9.26%   |
| 51-100     | 4         | 7.41%   |
| 1001-2000  | 3         | 5.56%   |
| 21-50      | 1         | 1.85%   |
| Unknown    | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 15        | 27.78%  |
| 21-50    | 13        | 24.07%  |
| 51-100   | 11        | 20.37%  |
| 101-250  | 10        | 18.52%  |
| 251-500  | 2         | 3.7%    |
| 501-1000 | 2         | 3.7%    |
| Unknown  | 1         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 16.67%  |
| Seagate ST9500420AS 500GB           | 1         | 1      | 16.67%  |
| Seagate ST9320325AS 320GB           | 1         | 1      | 16.67%  |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 16.67%  |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 16.67%  |
| LITEON CV8-8E128-HP 128GB SSD       | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 50%     |
| WDC                 | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| LITEON              | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 60%     |
| WDC                 | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 83.33%  |
| SSD  | 1         | 1      | 16.67%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 30        | 39     | 53.57%  |
| Works    | 20        | 25     | 35.71%  |
| Malfunc  | 6         | 6      | 10.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 33        | 46.48%  |
| Samsung Electronics          | 12        | 16.9%   |
| AMD                          | 8         | 11.27%  |
| Sandisk                      | 6         | 8.45%   |
| Kingston Technology Company  | 3         | 4.23%   |
| SK Hynix                     | 2         | 2.82%   |
| KIOXIA                       | 2         | 2.82%   |
| Zhaoxin                      | 1         | 1.41%   |
| Toshiba America Info Systems | 1         | 1.41%   |
| Shenzhen Longsys Electronics | 1         | 1.41%   |
| Micron Technology            | 1         | 1.41%   |
| ADATA Technology             | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 10.53%  |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 7.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 6.58%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 5.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 3.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 3.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 3.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 3.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 3.95%   |
| SK Hynix Gold P31 SSD                                                            | 2         | 2.63%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 2.63%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.63%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 2.63%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 2.63%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 2.63%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 2.63%   |
| Intel Non-Volatile memory controller                                             | 2         | 2.63%   |
| Zhaoxin ZX-100/ZX-200/ZX-E StorX AHCI Controller                                 | 1         | 1.32%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.32%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                      | 1         | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.32%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.32%   |
| Micron Non-Volatile memory controller                                            | 1         | 1.32%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 1.32%   |
| Intel SSD 660P Series                                                            | 1         | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 1.32%   |
| AMD FCH IDE Controller                                                           | 1         | 1.32%   |
| ADATA Non-Volatile memory controller                                             | 1         | 1.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 32        | 43.84%  |
| NVMe | 29        | 39.73%  |
| RAID | 9         | 12.33%  |
| IDE  | 3         | 4.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 42        | 79.25%  |
| AMD          | 10        | 18.87%  |
| CentaurHauls | 1         | 1.89%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 4         | 7.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 3         | 5.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz              | 2         | 3.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 2         | 3.77%   |
| AMD Ryzen 7 4800HS with Radeon Graphics        | 2         | 3.77%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz         | 1         | 1.89%   |
| Intel Pentium 3558U @ 1.70GHz                  | 1         | 1.89%   |
| Intel Genuine CPU U7300 @ 1.30GHz              | 1         | 1.89%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1         | 1.89%   |
| Intel Core i7-8665U CPU @ 1.90GHz              | 1         | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 1.89%   |
| Intel Core i7-6820HK CPU @ 2.70GHz             | 1         | 1.89%   |
| Intel Core i7-4510U CPU @ 2.00GHz              | 1         | 1.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 1         | 1.89%   |
| Intel Core i5-4220Y CPU @ 1.60GHz              | 1         | 1.89%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 1         | 1.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 1         | 1.89%   |
| Intel Core i5 CPU M 560 @ 2.67GHz              | 1         | 1.89%   |
| Intel Core i5 CPU M 520 @ 2.40GHz              | 1         | 1.89%   |
| Intel Core i3-4005U CPU @ 1.70GHz              | 1         | 1.89%   |
| Intel Core i3-3217U CPU @ 1.80GHz              | 1         | 1.89%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 1         | 1.89%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz             | 1         | 1.89%   |
| Intel Core i3 CPU M 370 @ 2.40GHz              | 1         | 1.89%   |
| Intel Core i3 CPU M 350 @ 2.27GHz              | 1         | 1.89%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz           | 1         | 1.89%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 1         | 1.89%   |
| Intel Celeron CPU N3060 @ 1.60GHz              | 1         | 1.89%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 1         | 1.89%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz              | 1         | 1.89%   |
| Intel 12th Gen Core i9-12900H                  | 1         | 1.89%   |
| Intel 12th Gen Core i7-12700H                  | 1         | 1.89%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz        | 1         | 1.89%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz        | 1         | 1.89%   |
| Intel 11th Gen Core i5-1155G7 @ 2.50GHz        | 1         | 1.89%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz        | 1         | 1.89%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 1         | 1.89%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 1         | 1.89%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics     | 1         | 1.89%   |
| AMD Ryzen 7 5800U with Radeon Graphics         | 1         | 1.89%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 1         | 1.89%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 1         | 1.89%   |
| AMD Ryzen 5 4500U with Radeon Graphics         | 1         | 1.89%   |
| AMD A4-5000 APU with Radeon HD Graphics        | 1         | 1.89%   |
| AMD A10-5745M APU with Radeon HD Graphics      | 1         | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Other              | 16        | 30.19%  |
| Intel Core i5      | 8         | 15.09%  |
| Intel Core i3      | 6         | 11.32%  |
| Intel Core i7      | 5         | 9.43%   |
| AMD Ryzen 7        | 4         | 7.55%   |
| Intel Celeron      | 3         | 5.66%   |
| AMD Ryzen 5        | 2         | 3.77%   |
| Intel Pentium Dual | 1         | 1.89%   |
| Intel Pentium      | 1         | 1.89%   |
| Intel Genuine      | 1         | 1.89%   |
| Intel Core 2 Duo   | 1         | 1.89%   |
| Intel Atom         | 1         | 1.89%   |
| AMD Ryzen 9        | 1         | 1.89%   |
| AMD Ryzen 7 PRO    | 1         | 1.89%   |
| AMD A4             | 1         | 1.89%   |
| AMD A10            | 1         | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 20        | 37.74%  |
| 4      | 16        | 30.19%  |
| 8      | 11        | 20.75%  |
| 6      | 4         | 7.55%   |
| 14     | 2         | 3.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 42        | 79.25%  |
| 1      | 11        | 20.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 53        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 48.15%  |
| 0x806ea    | 3         | 5.56%   |
| 0x806c1    | 3         | 5.56%   |
| 0x0a50000c | 3         | 5.56%   |
| 0x906a3    | 2         | 3.7%    |
| 0x806d1    | 2         | 3.7%    |
| 0x40651    | 2         | 3.7%    |
| 0x20655    | 2         | 3.7%    |
| 0x906ea    | 1         | 1.85%   |
| 0x806ec    | 1         | 1.85%   |
| 0x806c2    | 1         | 1.85%   |
| 0x706e5    | 1         | 1.85%   |
| 0x706a8    | 1         | 1.85%   |
| 0x6fd      | 1         | 1.85%   |
| 0x306a9    | 1         | 1.85%   |
| 0x1067a    | 1         | 1.85%   |
| 0x08608103 | 1         | 1.85%   |
| 0x08600104 | 1         | 1.85%   |
| 0x06001119 | 1         | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| TigerLake        | 7         | 13.21%  |
| KabyLake         | 6         | 11.32%  |
| Unknown          | 6         | 11.32%  |
| Haswell          | 5         | 9.43%   |
| Zen 3            | 4         | 7.55%   |
| Westmere         | 4         | 7.55%   |
| Zen 2            | 3         | 5.66%   |
| Silvermont       | 3         | 5.66%   |
| Icelake          | 3         | 5.66%   |
| Skylake          | 2         | 3.77%   |
| Penryn           | 2         | 3.77%   |
| Alderlake Hybrid | 2         | 3.77%   |
| SandyBridge      | 1         | 1.89%   |
| Piledriver       | 1         | 1.89%   |
| Jaguar           | 1         | 1.89%   |
| IvyBridge        | 1         | 1.89%   |
| Goldmont plus    | 1         | 1.89%   |
| Core             | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 37        | 53.62%  |
| Nvidia  | 18        | 26.09%  |
| AMD     | 13        | 18.84%  |
| Zhaoxin | 1         | 1.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 10%     |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 8.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 5.71%   |
| AMD Cezanne                                                                              | 4         | 5.71%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.29%   |
| AMD Renoir                                                                               | 3         | 4.29%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 2.86%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 2.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 2.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.86%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 2.86%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1         | 1.43%   |
| Nvidia TU117M                                                                            | 1         | 1.43%   |
| Nvidia TU117GLM [T600 Mobile]                                                            | 1         | 1.43%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.43%   |
| Nvidia GT215M [GeForce GT 335M]                                                          | 1         | 1.43%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.43%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 1.43%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 1.43%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.43%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 1.43%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.43%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                            | 1         | 1.43%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                               | 1         | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.43%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.43%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 1.43%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.43%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.43%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 1         | 1.43%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 1.43%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.43%   |
| AMD Lucienne                                                                             | 1         | 1.43%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 1.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 45.28%  |
| Intel + Nvidia | 12        | 22.64%  |
| 1 x AMD        | 9         | 16.98%  |
| 1 x Nvidia     | 3         | 5.66%   |
| AMD + Nvidia   | 3         | 5.66%   |
| 1 x Zhaoxin    | 1         | 1.89%   |
| Intel + AMD    | 1         | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 42        | 79.25%  |
| Proprietary | 10        | 18.87%  |
| Unknown     | 1         | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 75.47%  |
| 3.01-4.0   | 4         | 7.55%   |
| 1.01-2.0   | 3         | 5.66%   |
| 0.01-0.5   | 3         | 5.66%   |
| 0.51-1.0   | 2         | 3.77%   |
| 7.01-8.0   | 1         | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 13        | 22.41%  |
| BOE                 | 12        | 20.69%  |
| Samsung Electronics | 8         | 13.79%  |
| Chimei Innolux      | 5         | 8.62%   |
| LG Display          | 4         | 6.9%    |
| Dell                | 3         | 5.17%   |
| CSO                 | 2         | 3.45%   |
| AOC                 | 2         | 3.45%   |
| Sharp               | 1         | 1.72%   |
| PANDA               | 1         | 1.72%   |
| OEM                 | 1         | 1.72%   |
| Microstep           | 1         | 1.72%   |
| JDI                 | 1         | 1.72%   |
| InfoVision          | 1         | 1.72%   |
| HUAWEI              | 1         | 1.72%   |
| Hewlett-Packard     | 1         | 1.72%   |
| BenQ                | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 256x144mm 11.6-inch  | 2         | 3.45%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch  | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC3842 1366x768 309x174mm 14.0-inch  | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch  | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1         | 1.72%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.72%   |
| OEM 22_LCD_TV OEM3700 1920x540                                        | 1         | 1.72%   |
| Microstep LCD Monitor Optix AG32CQ                                    | 1         | 1.72%   |
| LG Display LCD Monitor LGD0671 1920x1080 382x215mm 17.3-inch          | 1         | 1.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 1.72%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch           | 1         | 1.72%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 1         | 1.72%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 1.72%   |
| InfoVision LCD Monitor IVO8C5F 1920x1080 309x174mm 14.0-inch          | 1         | 1.72%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                  | 1         | 1.72%   |
| Hewlett-Packard W2071d HWP299C 1600x900 443x249mm 20.0-inch           | 1         | 1.72%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                    | 1         | 1.72%   |
| Dell S2240L DELD053 1920x1080 476x267mm 21.5-inch                     | 1         | 1.72%   |
| Dell E178FP DELA027 1280x1024 338x270mm 17.0-inch                     | 1         | 1.72%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                 | 1         | 1.72%   |
| CSO LCD Monitor CSO1407 3840x2160 309x174mm 14.0-inch                 | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch      | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 1.72%   |
| BOE LCD Monitor BOE0A5D 1366x768 256x144mm 11.6-inch                  | 1         | 1.72%   |
| BOE LCD Monitor BOE09D0 1920x1080 309x174mm 14.0-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE07C5 1920x1080 344x194mm 15.5-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE070E 1920x1080 294x165mm 13.3-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 1         | 1.72%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                     | 1         | 1.72%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUOBF99 2560x1600 344x215mm 16.0-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUOA68B 1920x1080 344x194mm 15.5-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO8294 1920x1080 382x215mm 17.3-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO35EC 1366x768 344x193mm 15.5-inch         | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO24ED 1920x1080 344x193mm 15.5-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO18D4 1280x800 216x135mm 10.0-inch         | 1         | 1.72%   |
| AU Optronics LCD Monitor 6400x2160                                    | 1         | 1.72%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 1         | 1.72%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1         | 1.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 24        | 41.38%  |
| 1366x768 (WXGA)  | 14        | 24.14%  |
| 3840x2160 (4K)   | 4         | 6.9%    |
| 2560x1600        | 3         | 5.17%   |
| 2560x1440 (QHD)  | 2         | 3.45%   |
| 1600x900 (HD+)   | 2         | 3.45%   |
| 6400x2160        | 1         | 1.72%   |
| 3440x1440        | 1         | 1.72%   |
| 3000x2000        | 1         | 1.72%   |
| 2520x1680        | 1         | 1.72%   |
| 2256x1504        | 1         | 1.72%   |
| 1920x540         | 1         | 1.72%   |
| 1280x800 (WXGA)  | 1         | 1.72%   |
| 1280x1024 (SXGA) | 1         | 1.72%   |
| Unknown          | 1         | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 21        | 36.84%  |
| 14      | 7         | 12.28%  |
| 17      | 5         | 8.77%   |
| 13      | 5         | 8.77%   |
| 16      | 4         | 7.02%   |
| 27      | 3         | 5.26%   |
| 11      | 3         | 5.26%   |
| 84      | 1         | 1.75%   |
| 54      | 1         | 1.75%   |
| 34      | 1         | 1.75%   |
| 33      | 1         | 1.75%   |
| 24      | 1         | 1.75%   |
| 21      | 1         | 1.75%   |
| 20      | 1         | 1.75%   |
| 10      | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 55.36%  |
| 201-300     | 8         | 14.29%  |
| 351-400     | 6         | 10.71%  |
| 501-600     | 4         | 7.14%   |
| 701-800     | 2         | 3.57%   |
| 401-500     | 2         | 3.57%   |
| 1501-2000   | 1         | 1.79%   |
| 1001-1500   | 1         | 1.79%   |
| Unknown     | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 42        | 80.77%  |
| 16/10   | 4         | 7.69%   |
| 3/2     | 3         | 5.77%   |
| 5/4     | 1         | 1.92%   |
| 21/9    | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 36.84%  |
| 81-90          | 10        | 17.54%  |
| 121-130        | 4         | 7.02%   |
| 111-120        | 4         | 7.02%   |
| 51-60          | 3         | 5.26%   |
| 301-350        | 3         | 5.26%   |
| More than 1000 | 2         | 3.51%   |
| 71-80          | 2         | 3.51%   |
| 351-500        | 2         | 3.51%   |
| 151-200        | 2         | 3.51%   |
| 41-50          | 1         | 1.75%   |
| 201-250        | 1         | 1.75%   |
| 141-150        | 1         | 1.75%   |
| Unknown        | 1         | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 39.29%  |
| 101-120       | 11        | 19.64%  |
| 51-100        | 10        | 17.86%  |
| 161-240       | 9         | 16.07%  |
| More than 240 | 2         | 3.57%   |
| 1-50          | 1         | 1.79%   |
| Unknown       | 1         | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 38        | 70.37%  |
| 2     | 11        | 20.37%  |
| 0     | 5         | 9.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 33        | 39.29%  |
| Intel                 | 28        | 33.33%  |
| Qualcomm Atheros      | 10        | 11.9%   |
| Broadcom              | 4         | 4.76%   |
| Ralink                | 2         | 2.38%   |
| MEDIATEK              | 2         | 2.38%   |
| Sierra Wireless       | 1         | 1.19%   |
| Qualcomm              | 1         | 1.19%   |
| JMicron Technology    | 1         | 1.19%   |
| Broadcom Limited      | 1         | 1.19%   |
| ASIX Electronics      | 1         | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 11.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 7.37%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 5.26%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 3.16%   |
| Intel Wireless 7265                                               | 3         | 3.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 3.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.11%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 2.11%   |
| Realtek Realtek Ethernet controller                               | 2         | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 2.11%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 2.11%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 2.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 2.11%   |
| Sierra Wireless EM7305                                            | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.05%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1         | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.05%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.05%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.05%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.05%   |
| Qualcomm Atheros QCNFA765                                         | 1         | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.05%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.05%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.05%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.05%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.05%   |
| Intel Wireless 8260                                               | 1         | 1.05%   |
| Intel Wireless 7260                                               | 1         | 1.05%   |
| Intel Wireless 3165                                               | 1         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.05%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.05%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 1         | 1.05%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 48.15%  |
| Realtek Semiconductor | 9         | 16.67%  |
| Qualcomm Atheros      | 8         | 14.81%  |
| Broadcom              | 4         | 7.41%   |
| Ralink                | 2         | 3.7%    |
| MEDIATEK              | 2         | 3.7%    |
| Sierra Wireless       | 1         | 1.85%   |
| Qualcomm              | 1         | 1.85%   |
| Broadcom Limited      | 1         | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 5         | 9.09%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 9.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 5.45%   |
| Intel Wireless 7265                                            | 3         | 5.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 5.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.64%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 3.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 3.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.64%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 3.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 3.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 3.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 3.64%   |
| Sierra Wireless EM7305                                         | 1         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.82%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 1.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.82%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.82%   |
| Qualcomm Atheros QCNFA765                                      | 1         | 1.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.82%   |
| Intel Wireless 8265 / 8275                                     | 1         | 1.82%   |
| Intel Wireless 8260                                            | 1         | 1.82%   |
| Intel Wireless 7260                                            | 1         | 1.82%   |
| Intel Wireless 3165                                            | 1         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.82%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 1.82%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 70%     |
| Intel                 | 7         | 17.5%   |
| Qualcomm Atheros      | 3         | 7.5%    |
| JMicron Technology    | 1         | 2.5%    |
| ASIX Electronics      | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 27.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 17.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 7.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 7.5%    |
| Realtek Realtek Ethernet controller                               | 2         | 5%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.5%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 2.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.5%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection I218-V                                  | 1         | 2.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (14) I219-V                             | 1         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.5%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 56.99%  |
| Ethernet | 40        | 43.01%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 66.2%   |
| Ethernet | 24        | 33.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 36        | 67.92%  |
| 1     | 16        | 30.19%  |
| 0     | 1         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 73.58%  |
| Yes  | 14        | 26.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 57.78%  |
| Qualcomm Atheros Communications | 6         | 13.33%  |
| Realtek Semiconductor           | 4         | 8.89%   |
| IMC Networks                    | 2         | 4.44%   |
| Realtek                         | 1         | 2.22%   |
| Ralink Technology               | 1         | 2.22%   |
| Ralink                          | 1         | 2.22%   |
| Foxconn / Hon Hai               | 1         | 2.22%   |
| Dell                            | 1         | 2.22%   |
| Cambridge Silicon Radio         | 1         | 2.22%   |
| Broadcom                        | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 15.56%  |
| Intel AX201 Bluetooth                               | 5         | 11.11%  |
| Intel AX200 Bluetooth                               | 5         | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 8.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 6.67%   |
| Intel AX210 Bluetooth                               | 3         | 6.67%   |
| Realtek Bluetooth Radio                             | 2         | 4.44%   |
| Intel Bluetooth Device                              | 2         | 4.44%   |
| IMC Networks Wireless_Device                        | 2         | 4.44%   |
| Realtek RTL8723B Bluetooth                          | 1         | 2.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.22%   |
| Realtek Bluetooth Radio                             | 1         | 2.22%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 2.22%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.22%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.22%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.22%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.22%   |
| Dell Wireless 365 Bluetooth                         | 1         | 2.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.22%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 41        | 59.42%  |
| Nvidia              | 13        | 18.84%  |
| AMD                 | 12        | 17.39%  |
| Zhaoxin             | 1         | 1.45%   |
| Creative Technology | 1         | 1.45%   |
| Corsair             | 1         | 1.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 9.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 8.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 8.33%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 6         | 7.14%   |
| Nvidia Audio device                                                                               | 5         | 5.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 5.95%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 5.95%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 4.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 4.76%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 3.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.38%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.38%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 1.19%   |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                                         | 1         | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.19%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.19%   |
| Creative Technology Sound Blaster Premium HD [SBX]                                                | 1         | 1.19%   |
| Corsair HS80 RGB Wireless Gaming Receiver                                                         | 1         | 1.19%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.19%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.19%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.19%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 35.71%  |
| SK Hynix            | 7         | 16.67%  |
| Micron Technology   | 6         | 14.29%  |
| Kingston            | 4         | 9.52%   |
| Ramaxel Technology  | 2         | 4.76%   |
| Crucial             | 2         | 4.76%   |
| Unknown (ABCD)      | 1         | 2.38%   |
| Unknown             | 1         | 2.38%   |
| Shenzhen WODPOSIT   | 1         | 2.38%   |
| GOODRAM             | 1         | 2.38%   |
| ASint Technology    | 1         | 2.38%   |
| A-DATA Technology   | 1         | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 2         | 4.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 4.55%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM 4800MT/s                 | 2         | 4.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 2.27%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 2.27%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 2.27%   |
| SK Hynix RAM Module 2GB DDR3 1600MT/s                               | 1         | 2.27%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.27%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s                   | 1         | 2.27%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 2.27%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 2.27%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 2.27%   |
| SK Hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 2.27%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s               | 1         | 2.27%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 1         | 2.27%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 2.27%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 2.27%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 2.27%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 2.27%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 2.27%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 2.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 1         | 2.27%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s        | 1         | 2.27%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s                | 1         | 2.27%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s             | 1         | 2.27%   |
| Ramaxel RAM RMSA3260NA78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 1         | 2.27%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s                  | 1         | 2.27%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 1         | 2.27%   |
| Micron RAM MT40A1G16RC-062E:B 8GB Row Of Chips DDR4 3200MT/s        | 1         | 2.27%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 1         | 2.27%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 2.27%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 1         | 2.27%   |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s                | 1         | 2.27%   |
| Kingston RAM 9905700-095.A00G 16GB SODIMM DDR4 3200MT/s             | 1         | 2.27%   |
| Kingston RAM 9905700-046.A00G 16GB SODIMM DDR4 3200MT/s             | 1         | 2.27%   |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s              | 1         | 2.27%   |
| GOODRAM RAM GR1333S364L9/4G 4GB SODIMM DDR3 1333MT/s                | 1         | 2.27%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s           | 1         | 2.27%   |
| Crucial RAM CT16G4SFD832A.M16FR 16GB SODIMM DDR4 3200MT/s           | 1         | 2.27%   |
| ASint RAM SSZ3128M8-EAEEF 2GB SODIMM DDR3 1067MT/s                  | 1         | 2.27%   |
| A-DATA RAM Module 32GB SODIMM DDR4 3200MT/s                         | 1         | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 19        | 54.29%  |
| DDR3    | 8         | 22.86%  |
| SDRAM   | 2         | 5.71%   |
| LPDDR3  | 2         | 5.71%   |
| Unknown | 2         | 5.71%   |
| LPDDR4  | 1         | 2.86%   |
| DDR2    | 1         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 82.35%  |
| Row Of Chips | 5         | 14.71%  |
| Unknown      | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 13        | 33.33%  |
| 4096  | 9         | 23.08%  |
| 16384 | 7         | 17.95%  |
| 2048  | 6         | 15.38%  |
| 32768 | 3         | 7.69%   |
| 1024  | 1         | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 14        | 37.84%  |
| 1600  | 6         | 16.22%  |
| 2667  | 4         | 10.81%  |
| 4800  | 2         | 5.41%   |
| 4199  | 2         | 5.41%   |
| 2400  | 2         | 5.41%   |
| 2666  | 1         | 2.7%    |
| 2133  | 1         | 2.7%    |
| 1867  | 1         | 2.7%    |
| 1334  | 1         | 2.7%    |
| 1333  | 1         | 2.7%    |
| 1067  | 1         | 2.7%    |
| 667   | 1         | 2.7%    |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 23.91%  |
| Microdia                               | 5         | 10.87%  |
| IMC Networks                           | 5         | 10.87%  |
| Realtek Semiconductor                  | 4         | 8.7%    |
| Acer                                   | 4         | 8.7%    |
| Syntek                                 | 3         | 6.52%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.52%   |
| USB Camera                             | 1         | 2.17%   |
| Suyin                                  | 1         | 2.17%   |
| Sunplus Innovation Technology          | 1         | 2.17%   |
| Sonix Technology                       | 1         | 2.17%   |
| ShineTech                              | 1         | 2.17%   |
| Ricoh                                  | 1         | 2.17%   |
| Quanta                                 | 1         | 2.17%   |
| Luxvisions Innotech Limited            | 1         | 2.17%   |
| Lite-On Technology                     | 1         | 2.17%   |
| DJKANA1BIFZTDM                         | 1         | 2.17%   |
| Creative Technology                    | 1         | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony HP HD Camera                                         | 4         | 8.51%   |
| Syntek Lenovo EasyCamera                                     | 2         | 4.26%   |
| Microdia Integrated_Webcam_HD                                | 2         | 4.26%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 2         | 4.26%   |
| Chicony TOSHIBA Web Camera - HD                              | 2         | 4.26%   |
| Chicony Integrated Camera                                    | 2         | 4.26%   |
| Acer HD Camera                                               | 2         | 4.26%   |
| USB Camera USB Camera                                        | 1         | 2.13%   |
| Syntek Integrated Camera                                     | 1         | 2.13%   |
| Suyin HP Webcam-101                                          | 1         | 2.13%   |
| Sunplus Dell HD Webcam                                       | 1         | 2.13%   |
| Sonix USB2.0 HD UVC WebCam                                   | 1         | 2.13%   |
| ShineTech HD Camera                                          | 1         | 2.13%   |
| Ricoh HD Webcam                                              | 1         | 2.13%   |
| Realtek Laptop Camera                                        | 1         | 2.13%   |
| Realtek Integrated Webcam                                    | 1         | 2.13%   |
| Realtek HP Wide Vision HD Camera                             | 1         | 2.13%   |
| Realtek HP "Truevision HD" laptop camera                     | 1         | 2.13%   |
| Quanta HD User Facing                                        | 1         | 2.13%   |
| Microdia Webcam Vitade AF                                    | 1         | 2.13%   |
| Microdia Laptop_Integrated_Webcam_1.3M                       | 1         | 2.13%   |
| Microdia 1.3 MPixel Integrated Webcam                        | 1         | 2.13%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 1         | 2.13%   |
| Lite-On HP HD Camera                                         | 1         | 2.13%   |
| IMC Networks Integrated Webcam                               | 1         | 2.13%   |
| IMC Networks Integrated Camera                               | 1         | 2.13%   |
| IMC Networks HD Camera                                       | 1         | 2.13%   |
| DJKANA1BIFZTDM HP Wide Vision HD Camera                      | 1         | 2.13%   |
| Creative Live! Cam Sync 1080p V2                             | 1         | 2.13%   |
| Chicony TOSHIBA Web Camera - 3M                              | 1         | 2.13%   |
| Chicony HP Webcam                                            | 1         | 2.13%   |
| Chicony HP Truevision HD camera                              | 1         | 2.13%   |
| Chicony HD Webcam                                            | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera             | 1         | 2.13%   |
| Acer Integrated Camera                                       | 1         | 2.13%   |
| Acer HD Webcam                                               | 1         | 2.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 40%     |
| Synaptics                  | 3         | 30%     |
| Validity Sensors           | 2         | 20%     |
| Elan Microelectronics      | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 40%     |
| Unknown                                                                    | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 10%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 10%     |
| Elan ELAN:ARM-M4                                                           | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 31        | 58.49%  |
| 1     | 16        | 30.19%  |
| 2     | 6         | 11.32%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 37.04%  |
| Graphics card         | 9         | 33.33%  |
| Sound                 | 2         | 7.41%   |
| Camera                | 2         | 7.41%   |
| Net/wireless          | 1         | 3.7%    |
| Multimedia controller | 1         | 3.7%    |
| Chipcard              | 1         | 3.7%    |
| Bluetooth             | 1         | 3.7%    |

