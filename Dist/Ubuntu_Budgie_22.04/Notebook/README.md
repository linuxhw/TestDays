Ubuntu Budgie 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 67

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO        | InfinityBook S 15 Gen6      | [ee44dc2539](https://linux-hardware.org/?probe=ee44dc2539) | Jan 27, 2023 |
| HP            | ProBook 450 G7              | [1d507a3cdc](https://linux-hardware.org/?probe=1d507a3cdc) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [7bf2d60c0b](https://linux-hardware.org/?probe=7bf2d60c0b) | Jan 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| Dell          | Inspiron 5566               | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Dell          | XPS 13 9310                 | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| TUXEDO        | Aura 15 Gen1                | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | Latitude E5420              | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| AXIOO         | Slimbook 13                 | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Lenovo        | G500 20236                  | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Google        | Rabbid                      | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Lenovo        | G500 20236                  | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Dell          | Inspiron 3793               | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| HP            | EliteBook 840 G3            | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Acer          | Aspire E5-573G              | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| HP            | ElitePad 1000 G2            | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| MSI           | GL62 6QF                    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| Dell          | Inspiron 5570               | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Chuwi         | HeroBook Pro                | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| Apple         | MacBookPro5,4               | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| MSI           | Modern 15 A10M              | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Apple         | MacBookPro9,2               | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| ASUSTek       | T200TAC                     | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-27-generic     | 7         | 12.28%  |
| 5.15.0-50-generic     | 5         | 8.77%   |
| 5.15.0-48-generic     | 5         | 8.77%   |
| 5.15.0-52-generic     | 4         | 7.02%   |
| 5.15.0-53-generic     | 3         | 5.26%   |
| 5.15.0-40-generic     | 3         | 5.26%   |
| 5.15.0-39-generic     | 3         | 5.26%   |
| 5.15.0-30-generic     | 3         | 5.26%   |
| 5.15.0-56-generic     | 2         | 3.51%   |
| 5.15.0-47-generic     | 2         | 3.51%   |
| 5.15.0-46-generic     | 2         | 3.51%   |
| 5.15.0-33-generic     | 2         | 3.51%   |
| 5.15.0-25-generic     | 2         | 3.51%   |
| 5.19.0-051900-generic | 1         | 1.75%   |
| 5.15.0-58-generic     | 1         | 1.75%   |
| 5.15.0-52-lowlatency  | 1         | 1.75%   |
| 5.15.0-43-generic     | 1         | 1.75%   |
| 5.15.0-41-generic     | 1         | 1.75%   |
| 5.15.0-35-generic     | 1         | 1.75%   |
| 5.15.0-18-generic     | 1         | 1.75%   |
| 5.15.0-10058-tuxedo   | 1         | 1.75%   |
| 5.15.0-10056-tuxedo   | 1         | 1.75%   |
| 5.15.0-10052-tuxedo   | 1         | 1.75%   |
| 5.15.0-10047-tuxedo   | 1         | 1.75%   |
| 5.15.0-10041-tuxedo   | 1         | 1.75%   |
| 5.13.0-35-generic     | 1         | 1.75%   |
| 5.13.0-19-generic     | 1         | 1.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 51        | 94.44%  |
| 5.13.0  | 2         | 3.7%    |
| 5.19.0  | 1         | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 51        | 94.44%  |
| 5.13    | 2         | 3.7%    |
| 5.19    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 54        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 51        | 94.44%  |
| GNOME  | 3         | 5.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 52        | 96.3%   |
| Wayland | 2         | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 38        | 70.37%  |
| Unknown | 10        | 18.52%  |
| GDM3    | 6         | 11.11%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 16        | 29.63%  |
| de_DE | 8         | 14.81%  |
| fr_FR | 7         | 12.96%  |
| pt_BR | 5         | 9.26%   |
| ru_RU | 2         | 3.7%    |
| hu_HU | 2         | 3.7%    |
| en_GB | 2         | 3.7%    |
| en_CA | 2         | 3.7%    |
| mt_MT | 1         | 1.85%   |
| it_IT | 1         | 1.85%   |
| fr_BE | 1         | 1.85%   |
| es_PE | 1         | 1.85%   |
| es_MX | 1         | 1.85%   |
| es_EC | 1         | 1.85%   |
| es_CL | 1         | 1.85%   |
| en_IE | 1         | 1.85%   |
| cs_CZ | 1         | 1.85%   |
| C     | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 32        | 59.26%  |
| EFI  | 22        | 40.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 50        | 92.59%  |
| Overlay | 2         | 3.7%    |
| Xfs     | 1         | 1.85%   |
| Btrfs   | 1         | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 32        | 59.26%  |
| Unknown | 19        | 35.19%  |
| MBR     | 3         | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 81.48%  |
| Yes       | 10        | 18.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 72.73%  |
| Yes       | 15        | 27.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 13        | 24.07%  |
| Dell                   | 9         | 16.67%  |
| Hewlett-Packard        | 7         | 12.96%  |
| TUXEDO                 | 5         | 9.26%   |
| ASUSTek Computer       | 5         | 9.26%   |
| Apple                  | 3         | 5.56%   |
| MSI                    | 2         | 3.7%    |
| Google                 | 2         | 3.7%    |
| Toshiba                | 1         | 1.85%   |
| Timi                   | 1         | 1.85%   |
| Razer                  | 1         | 1.85%   |
| Digibras               | 1         | 1.85%   |
| Chuwi                  | 1         | 1.85%   |
| AXIOO                  | 1         | 1.85%   |
| Avell High Performance | 1         | 1.85%   |
| Acer                   | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1.85%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 1.85%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 1.85%   |
| TUXEDO Book BA1510                                   | 1         | 1.85%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.85%   |
| Toshiba Satellite A505                               | 1         | 1.85%   |
| Timi TM1604                                          | 1         | 1.85%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.85%   |
| MSI Modern 15 A10M                                   | 1         | 1.85%   |
| MSI GL62 6QF                                         | 1         | 1.85%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1.85%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.85%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.85%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.85%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.85%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.85%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1.85%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.85%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.85%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.85%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.85%   |
| Lenovo G500 20236                                    | 1         | 1.85%   |
| Lenovo G50-45 80E3                                   | 1         | 1.85%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1.85%   |
| HP ProBook 450 G7                                    | 1         | 1.85%   |
| HP ProBook 445 G7                                    | 1         | 1.85%   |
| HP Pavilion g6                                       | 1         | 1.85%   |
| HP ENVY 17                                           | 1         | 1.85%   |
| HP ElitePad 1000 G2                                  | 1         | 1.85%   |
| HP EliteBook 840 G3                                  | 1         | 1.85%   |
| Google Rabbid                                        | 1         | 1.85%   |
| Google Boten                                         | 1         | 1.85%   |
| Digibras NH4CU03                                     | 1         | 1.85%   |
| Dell XPS 13 9360                                     | 1         | 1.85%   |
| Dell XPS 13 9310                                     | 1         | 1.85%   |
| Dell Vostro 15 5510                                  | 1         | 1.85%   |
| Dell Precision 5560                                  | 1         | 1.85%   |
| Dell Latitude E6410                                  | 1         | 1.85%   |
| Dell Latitude E5420                                  | 1         | 1.85%   |
| Dell Inspiron 5570                                   | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 5         | 9.26%   |
| Lenovo IdeaPad              | 4         | 7.41%   |
| HP ProBook                  | 3         | 5.56%   |
| Dell Inspiron               | 3         | 5.56%   |
| TUXEDO Book                 | 2         | 3.7%    |
| Dell XPS                    | 2         | 3.7%    |
| Dell Latitude               | 2         | 3.7%    |
| ASUS VivoBook               | 2         | 3.7%    |
| TUXEDO Polaris              | 1         | 1.85%   |
| TUXEDO InfinityBook         | 1         | 1.85%   |
| TUXEDO Aura                 | 1         | 1.85%   |
| Toshiba Satellite           | 1         | 1.85%   |
| Timi TM1604                 | 1         | 1.85%   |
| Razer Blade                 | 1         | 1.85%   |
| MSI Modern                  | 1         | 1.85%   |
| MSI GL62                    | 1         | 1.85%   |
| Lenovo V15                  | 1         | 1.85%   |
| Lenovo Legion               | 1         | 1.85%   |
| Lenovo G500                 | 1         | 1.85%   |
| Lenovo G50-45               | 1         | 1.85%   |
| HP Pavilion                 | 1         | 1.85%   |
| HP ENVY                     | 1         | 1.85%   |
| HP ElitePad                 | 1         | 1.85%   |
| HP EliteBook                | 1         | 1.85%   |
| Google Rabbid               | 1         | 1.85%   |
| Google Boten                | 1         | 1.85%   |
| Digibras NH4CU03            | 1         | 1.85%   |
| Dell Vostro                 | 1         | 1.85%   |
| Dell Precision              | 1         | 1.85%   |
| Chuwi HeroBook              | 1         | 1.85%   |
| AXIOO Slimbook              | 1         | 1.85%   |
| Avell High Performance B.ON | 1         | 1.85%   |
| ASUS ZenBook                | 1         | 1.85%   |
| ASUS X205TA                 | 1         | 1.85%   |
| ASUS T200TAC                | 1         | 1.85%   |
| Apple MacBookPro9           | 1         | 1.85%   |
| Apple MacBookPro8           | 1         | 1.85%   |
| Apple MacBookPro5           | 1         | 1.85%   |
| Acer Aspire                 | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 11        | 20.37%  |
| 2020 | 9         | 16.67%  |
| 2019 | 6         | 11.11%  |
| 2018 | 4         | 7.41%   |
| 2016 | 4         | 7.41%   |
| 2014 | 4         | 7.41%   |
| 2013 | 3         | 5.56%   |
| 2011 | 3         | 5.56%   |
| 2017 | 2         | 3.7%    |
| 2010 | 2         | 3.7%    |
| 2009 | 2         | 3.7%    |
| 2022 | 1         | 1.85%   |
| 2015 | 1         | 1.85%   |
| 2012 | 1         | 1.85%   |
| 2008 | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 54        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 49        | 90.74%  |
| Enabled  | 5         | 9.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 96.3%   |
| Yes  | 2         | 3.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 17        | 31.48%  |
| 16.01-24.0  | 15        | 27.78%  |
| 3.01-4.0    | 7         | 12.96%  |
| 8.01-16.0   | 7         | 12.96%  |
| 32.01-64.0  | 5         | 9.26%   |
| 64.01-256.0 | 2         | 3.7%    |
| 1.01-2.0    | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 18        | 32.73%  |
| 4.01-8.0   | 14        | 25.45%  |
| 2.01-3.0   | 14        | 25.45%  |
| 3.01-4.0   | 4         | 7.27%   |
| 8.01-16.0  | 4         | 7.27%   |
| 24.01-32.0 | 1         | 1.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 70.91%  |
| 2      | 14        | 25.45%  |
| 3      | 2         | 3.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 85.19%  |
| Yes       | 8         | 14.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 74.07%  |
| No        | 14        | 25.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 96.3%   |
| No        | 2         | 3.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 85.19%  |
| No        | 8         | 14.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 8         | 14.81%  |
| Germany            | 8         | 14.81%  |
| France             | 7         | 12.96%  |
| Brazil             | 5         | 9.26%   |
| Hungary            | 2         | 3.7%    |
| Canada             | 2         | 3.7%    |
| Sweden             | 1         | 1.85%   |
| Slovenia           | 1         | 1.85%   |
| Russia             | 1         | 1.85%   |
| Romania            | 1         | 1.85%   |
| Poland             | 1         | 1.85%   |
| Peru               | 1         | 1.85%   |
| Mexico             | 1         | 1.85%   |
| Malta              | 1         | 1.85%   |
| Italy              | 1         | 1.85%   |
| Ireland            | 1         | 1.85%   |
| Indonesia          | 1         | 1.85%   |
| Greece             | 1         | 1.85%   |
| Ghana              | 1         | 1.85%   |
| Ecuador            | 1         | 1.85%   |
| Dominican Republic | 1         | 1.85%   |
| Czechia            | 1         | 1.85%   |
| Chile              | 1         | 1.85%   |
| Cabo Verde         | 1         | 1.85%   |
| Belgium            | 1         | 1.85%   |
| Belarus            | 1         | 1.85%   |
| Austria            | 1         | 1.85%   |
| Algeria            | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Budapest              | 2         | 3.7%    |
| Wertheim am Main      | 1         | 1.85%   |
| Weisswasser           | 1         | 1.85%   |
| Weilheim              | 1         | 1.85%   |
| Warsaw                | 1         | 1.85%   |
| Vienna                | 1         | 1.85%   |
| Victoria              | 1         | 1.85%   |
| Targu Frumos          | 1         | 1.85%   |
| Tarakan               | 1         | 1.85%   |
| Sunnyvale             | 1         | 1.85%   |
| St Petersburg         | 1         | 1.85%   |
| Siegen                | 1         | 1.85%   |
| Sétif                | 1         | 1.85%   |
| Seelze                | 1         | 1.85%   |
| Sao Paulo             | 1         | 1.85%   |
| Sao Bernardo do Campo | 1         | 1.85%   |
| Santo Domingo Este    | 1         | 1.85%   |
| Santiago              | 1         | 1.85%   |
| Saint-Gilles          | 1         | 1.85%   |
| Recife                | 1         | 1.85%   |
| Queens                | 1         | 1.85%   |
| Puebla City           | 1         | 1.85%   |
| Praia                 | 1         | 1.85%   |
| Postojna              | 1         | 1.85%   |
| Ostrava               | 1         | 1.85%   |
| Orvault               | 1         | 1.85%   |
| Nuremberg             | 1         | 1.85%   |
| Monza                 | 1         | 1.85%   |
| Mishawaka             | 1         | 1.85%   |
| Massaranduba          | 1         | 1.85%   |
| Lund                  | 1         | 1.85%   |
| Lima                  | 1         | 1.85%   |
| Lille                 | 1         | 1.85%   |
| Leominster            | 1         | 1.85%   |
| Le Mee-sur-Seine      | 1         | 1.85%   |
| Laval                 | 1         | 1.85%   |
| Kassel                | 1         | 1.85%   |
| Fontenay-sous-Bois    | 1         | 1.85%   |
| Dublin                | 1         | 1.85%   |
| DeQuincy              | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 15        | 16     | 21.43%  |
| Unknown                        | 7         | 7      | 10%     |
| Toshiba                        | 6         | 7      | 8.57%   |
| Crucial                        | 5         | 6      | 7.14%   |
| WDC                            | 4         | 5      | 5.71%   |
| SK hynix                       | 4         | 4      | 5.71%   |
| Seagate                        | 3         | 3      | 4.29%   |
| Micron Technology              | 3         | 3      | 4.29%   |
| Kingston                       | 2         | 2      | 2.86%   |
| JMicron Technology             | 2         | 2      | 2.86%   |
| Intel                          | 2         | 2      | 2.86%   |
| China                          | 2         | 3      | 2.86%   |
| VISIPRO                        | 1         | 1      | 1.43%   |
| Union Memory                   | 1         | 1      | 1.43%   |
| TO Exter                       | 1         | 1      | 1.43%   |
| SPCC                           | 1         | 1      | 1.43%   |
| Solid State Storage Technology | 1         | 1      | 1.43%   |
| Realtek Semiconductor          | 1         | 1      | 1.43%   |
| Phison Electronics             | 1         | 1      | 1.43%   |
| OWC                            | 1         | 1      | 1.43%   |
| Netac                          | 1         | 1      | 1.43%   |
| KIOXIA                         | 1         | 1      | 1.43%   |
| Hewlett-Packard                | 1         | 1      | 1.43%   |
| Corsair                        | 1         | 2      | 1.43%   |
| Apple                          | 1         | 1      | 1.43%   |
| A-DATA Technology              | 1         | 1      | 1.43%   |
| Unknown                        | 1         | 1      | 1.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 2.82%   |
| Unknown SD64G  64GB                                 | 2         | 2.82%   |
| Samsung SSD 980 PRO 2TB                             | 2         | 2.82%   |
| Samsung SSD 980 500GB                               | 2         | 2.82%   |
| Samsung SSD 860 EVO M.2 500GB                       | 2         | 2.82%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 2         | 2.82%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 1.41%   |
| WDC PC SN730 NVMe 256GB                             | 1         | 1.41%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 1.41%   |
| VISIPRO SSD 256GB                                   | 1         | 1.41%   |
| Unknown SL128  128GB                                | 1         | 1.41%   |
| Unknown SA16G  16GB                                 | 1         | 1.41%   |
| Unknown NCard  4GB                                  | 1         | 1.41%   |
| Unknown MMC128  128GB                               | 1         | 1.41%   |
| Unknown MMC Card  64GB                              | 1         | 1.41%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD              | 1         | 1.41%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 1         | 1.41%   |
| Toshiba TR150 480GB SSD                             | 1         | 1.41%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1.41%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 1.41%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                   | 1         | 1.41%   |
| Toshiba KBG30ZMT256G 256GB                          | 1         | 1.41%   |
| TO Exter nal USB 3.0 500GB                          | 1         | 1.41%   |
| SPCC Solid State Disk 120GB                         | 1         | 1.41%   |
| Solid State Storage NVMe CA6-8D1024 1024GB          | 1         | 1.41%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB           | 1         | 1.41%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB                | 1         | 1.41%   |
| SK hynix HCG8e  64GB                                | 1         | 1.41%   |
| SK hynix HBG4e  32GB                                | 1         | 1.41%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1.41%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.41%   |
| Samsung SSD 860 EVO M.2 250GB                       | 1         | 1.41%   |
| Samsung SSD 860 EVO 500GB                           | 1         | 1.41%   |
| Samsung SSD 850 EVO 500GB                           | 1         | 1.41%   |
| Samsung SSD 850 EVO 250GB                           | 1         | 1.41%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 1         | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 1         | 1.41%   |
| Samsung HM320II 320GB                               | 1         | 1.41%   |
| Realtek NVMe SSD Drive 512GB                        | 1         | 1.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 37.5%   |
| Seagate             | 3         | 3      | 37.5%   |
| Toshiba             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 22.22%  |
| Crucial             | 5         | 6      | 18.52%  |
| Micron Technology   | 2         | 2      | 7.41%   |
| China               | 2         | 3      | 7.41%   |
| VISIPRO             | 1         | 1      | 3.7%    |
| Union Memory        | 1         | 1      | 3.7%    |
| Toshiba             | 1         | 1      | 3.7%    |
| TO Exter            | 1         | 1      | 3.7%    |
| SPCC                | 1         | 1      | 3.7%    |
| OWC                 | 1         | 1      | 3.7%    |
| Netac               | 1         | 1      | 3.7%    |
| JMicron Technology  | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| Hewlett-Packard     | 1         | 1      | 3.7%    |
| Corsair             | 1         | 2      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 24        | 27     | 37.5%   |
| SSD     | 23        | 30     | 35.94%  |
| MMC     | 8         | 10     | 12.5%   |
| HDD     | 8         | 8      | 12.5%   |
| Unknown | 1         | 1      | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 36     | 45.16%  |
| NVMe | 24        | 27     | 38.71%  |
| MMC  | 8         | 10     | 12.9%   |
| SAS  | 2         | 3      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 30     | 75%     |
| 0.51-1.0   | 5         | 5      | 15.63%  |
| 1.01-2.0   | 3         | 3      | 9.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 20        | 37.04%  |
| 101-250        | 17        | 31.48%  |
| 51-100         | 6         | 11.11%  |
| 21-50          | 3         | 5.56%   |
| 1001-2000      | 3         | 5.56%   |
| 501-1000       | 3         | 5.56%   |
| More than 3000 | 1         | 1.85%   |
| 1-20           | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 15        | 27.27%  |
| 21-50     | 13        | 23.64%  |
| 101-250   | 11        | 20%     |
| 51-100    | 8         | 14.55%  |
| 251-500   | 5         | 9.09%   |
| 501-1000  | 2         | 3.64%   |
| 1001-2000 | 1         | 1.82%   |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 33        | 43     | 57.89%  |
| Works    | 24        | 33     | 42.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 33        | 51.56%  |
| Samsung Electronics            | 8         | 12.5%   |
| AMD                            | 6         | 9.38%   |
| Toshiba America Info Systems   | 3         | 4.69%   |
| SK hynix                       | 2         | 3.13%   |
| SanDisk                        | 2         | 3.13%   |
| KIOXIA                         | 2         | 3.13%   |
| Kingston Technology Company    | 2         | 3.13%   |
| Solid State Storage Technology | 1         | 1.56%   |
| Realtek Semiconductor          | 1         | 1.56%   |
| Phison Electronics             | 1         | 1.56%   |
| Nvidia                         | 1         | 1.56%   |
| Micron Technology              | 1         | 1.56%   |
| ADATA Technology               | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 6         | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 5         | 7.58%   |
| Samsung NVMe SSD Controller 980                                              | 4         | 6.06%   |
| Intel Volume Management Device NVMe RAID Controller                          | 3         | 4.55%   |
| Intel Comet Lake SATA AHCI Controller                                        | 3         | 4.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 4.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 4.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 3.03%   |
| KIOXIA NVMe SSD Controller BG4                                               | 2         | 3.03%   |
| Intel Tiger Lake-LP SATA Controller                                          | 2         | 3.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 3.03%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 1.52%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 1.52%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 1.52%   |
| Solid State Storage Non-Volatile memory controller                           | 1         | 1.52%   |
| SK hynix Non-Volatile memory controller                                      | 1         | 1.52%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 1         | 1.52%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 1.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.52%   |
| Realtek Realtek Non-Volatile memory controller                               | 1         | 1.52%   |
| Phison NVMe Storage Controller                                               | 1         | 1.52%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 1.52%   |
| Micron Non-Volatile memory controller                                        | 1         | 1.52%   |
| Kingston Company Company Non-Volatile memory controller                      | 1         | 1.52%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 1.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 1.52%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 1         | 1.52%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 1         | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 1.52%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                         | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 1.52%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                  | 1         | 1.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 36        | 56.25%  |
| NVMe | 24        | 37.5%   |
| RAID | 3         | 4.69%   |
| IDE  | 1         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 46        | 85.19%  |
| AMD    | 8         | 14.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 7.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 3.7%    |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 3.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 3.7%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 3.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.7%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.85%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.85%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.85%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.85%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.85%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.85%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.85%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 1.85%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 1.85%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 1         | 1.85%   |
| Intel Celeron N4500 @ 1.10GHz                 | 1         | 1.85%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.85%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 1         | 1.85%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz       | 1         | 1.85%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 14        | 25.93%  |
| Other                | 9         | 16.67%  |
| Intel Core i7        | 8         | 14.81%  |
| Intel Celeron        | 4         | 7.41%   |
| AMD Ryzen 5          | 4         | 7.41%   |
| Intel Core i3        | 3         | 5.56%   |
| Intel Atom           | 3         | 5.56%   |
| Intel Core 2 Duo     | 2         | 3.7%    |
| AMD Ryzen 7          | 2         | 3.7%    |
| Intel Pentium Silver | 1         | 1.85%   |
| Intel Pentium        | 1         | 1.85%   |
| Intel Core i9        | 1         | 1.85%   |
| AMD Ryzen 3          | 1         | 1.85%   |
| AMD A8               | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 25        | 46.3%   |
| 2      | 20        | 37.04%  |
| 8      | 5         | 9.26%   |
| 6      | 3         | 5.56%   |
| 10     | 1         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 54        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 39        | 72.22%  |
| 1      | 15        | 27.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 53.7%   |
| 0x206a7    | 3         | 5.56%   |
| 0x08600106 | 3         | 5.56%   |
| 0x806ec    | 2         | 3.7%    |
| 0x806c1    | 2         | 3.7%    |
| 0x706a8    | 2         | 3.7%    |
| 0x08108102 | 2         | 3.7%    |
| 0x906ea    | 1         | 1.85%   |
| 0x806eb    | 1         | 1.85%   |
| 0x806d1    | 1         | 1.85%   |
| 0x506c9    | 1         | 1.85%   |
| 0x40651    | 1         | 1.85%   |
| 0x306d4    | 1         | 1.85%   |
| 0x30678    | 1         | 1.85%   |
| 0x20655    | 1         | 1.85%   |
| 0x106e5    | 1         | 1.85%   |
| 0x0a50000c | 1         | 1.85%   |
| 0x07030104 | 1         | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 20.37%  |
| TigerLake     | 6         | 11.11%  |
| Unknown       | 4         | 7.41%   |
| Zen 2         | 3         | 5.56%   |
| Skylake       | 3         | 5.56%   |
| Silvermont    | 3         | 5.56%   |
| SandyBridge   | 3         | 5.56%   |
| IvyBridge     | 3         | 5.56%   |
| Goldmont plus | 3         | 5.56%   |
| Zen+          | 2         | 3.7%    |
| Penryn        | 2         | 3.7%    |
| IceLake       | 2         | 3.7%    |
| Haswell       | 2         | 3.7%    |
| Zen 3         | 1         | 1.85%   |
| Westmere      | 1         | 1.85%   |
| Puma          | 1         | 1.85%   |
| Nehalem       | 1         | 1.85%   |
| Goldmont      | 1         | 1.85%   |
| CometLake     | 1         | 1.85%   |
| Broadwell     | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 64.18%  |
| Nvidia | 14        | 20.9%   |
| AMD    | 10        | 14.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 8.82%   |
| Intel UHD Graphics 620                                                                | 4         | 5.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 4.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 4.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 3         | 4.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 4.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 4.41%   |
| AMD Renoir                                                                            | 3         | 4.41%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 2.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 2.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 2.94%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                                | 1         | 1.47%   |
| Nvidia GT218M [GeForce 310M]                                                          | 1         | 1.47%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 1.47%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 1.47%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 1.47%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.47%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 1.47%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.47%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 1.47%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 1.47%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                    | 1         | 1.47%   |
| Nvidia C79 [GeForce 9400M]                                                            | 1         | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.47%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                           | 1         | 1.47%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.47%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 1.47%   |
| Intel Iris Plus Graphics G7                                                           | 1         | 1.47%   |
| Intel HD Graphics 620                                                                 | 1         | 1.47%   |
| Intel HD Graphics 5500                                                                | 1         | 1.47%   |
| Intel HD Graphics 530                                                                 | 1         | 1.47%   |
| Intel HD Graphics 500                                                                 | 1         | 1.47%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.47%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 1.47%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.47%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 1         | 1.47%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 30        | 55.56%  |
| Intel + Nvidia | 10        | 18.52%  |
| 1 x AMD        | 6         | 11.11%  |
| 1 x Nvidia     | 3         | 5.56%   |
| Intel + AMD    | 2         | 3.7%    |
| Other          | 1         | 1.85%   |
| 2 x AMD        | 1         | 1.85%   |
| AMD + Nvidia   | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 85.19%  |
| Proprietary | 7         | 12.96%  |
| Unknown     | 1         | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 81.48%  |
| 1.01-2.0   | 4         | 7.41%   |
| 0.01-0.5   | 3         | 5.56%   |
| 0.51-1.0   | 2         | 3.7%    |
| 7.01-8.0   | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 15        | 24.59%  |
| Chimei Innolux          | 14        | 22.95%  |
| Samsung Electronics     | 8         | 13.11%  |
| LG Display              | 5         | 8.2%    |
| AU Optronics            | 5         | 8.2%    |
| Sharp                   | 3         | 4.92%   |
| Apple                   | 3         | 4.92%   |
| Goldstar                | 2         | 3.28%   |
| Unknown (AAA)           | 1         | 1.64%   |
| Philips                 | 1         | 1.64%   |
| MStar                   | 1         | 1.64%   |
| Lenovo                  | 1         | 1.64%   |
| IBM                     | 1         | 1.64%   |
| Chi Mei Optoelectronics | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 3.28%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch                 | 1         | 1.64%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                  | 1         | 1.64%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 1.64%   |
| Sharp LCD Monitor SHP1447 1920x1080 290x170mm 13.2-inch                  | 1         | 1.64%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch     | 1         | 1.64%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch      | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch    | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch    | 1         | 1.64%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                  | 1         | 1.64%   |
| MStar LCD TV MST9000 1360x768                                            | 1         | 1.64%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch              | 1         | 1.64%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch                 | 1         | 1.64%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                    | 1         | 1.64%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 1         | 1.64%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN13B0 2560x1600 286x178mm 13.3-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1138 1366x768 256x144mm 11.6-inch          | 1         | 1.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.64%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                    | 1         | 1.64%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                    | 1         | 1.64%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                    | 1         | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 39.29%  |
| 1366x768 (WXGA)    | 15        | 26.79%  |
| 2560x1440 (QHD)    | 3         | 5.36%   |
| 1600x900 (HD+)     | 3         | 5.36%   |
| 1280x800 (WXGA)    | 3         | 5.36%   |
| 1920x1200 (WUXGA)  | 2         | 3.57%   |
| 1680x1050 (WSXGA+) | 2         | 3.57%   |
| 3840x2160 (4K)     | 1         | 1.79%   |
| 3456x2160          | 1         | 1.79%   |
| 2880x1800          | 1         | 1.79%   |
| 2560x1600          | 1         | 1.79%   |
| 1440x900 (WXGA+)   | 1         | 1.79%   |
| 1360x768           | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 25        | 40.98%  |
| 13      | 12        | 19.67%  |
| 14      | 6         | 9.84%   |
| 17      | 4         | 6.56%   |
| 11      | 3         | 4.92%   |
| 40      | 2         | 3.28%   |
| 27      | 2         | 3.28%   |
| 60      | 1         | 1.64%   |
| 31      | 1         | 1.64%   |
| 24      | 1         | 1.64%   |
| 23      | 1         | 1.64%   |
| 21      | 1         | 1.64%   |
| 10      | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 59.02%  |
| 201-300     | 10        | 16.39%  |
| 351-400     | 5         | 8.2%    |
| 501-600     | 3         | 4.92%   |
| 801-900     | 2         | 3.28%   |
| 401-500     | 2         | 3.28%   |
| 601-700     | 1         | 1.64%   |
| 1001-1500   | 1         | 1.64%   |
| Unknown     | 1         | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 79.63%  |
| 16/10 | 10        | 18.52%  |
| 3/2   | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 40.98%  |
| 81-90          | 15        | 24.59%  |
| 121-130        | 4         | 6.56%   |
| 71-80          | 3         | 4.92%   |
| 51-60          | 3         | 4.92%   |
| 201-250        | 3         | 4.92%   |
| 301-350        | 2         | 3.28%   |
| 501-1000       | 2         | 3.28%   |
| More than 1000 | 1         | 1.64%   |
| 351-500        | 1         | 1.64%   |
| 41-50          | 1         | 1.64%   |
| Unknown        | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 42.62%  |
| 101-120       | 16        | 26.23%  |
| 161-240       | 7         | 11.48%  |
| 51-100        | 5         | 8.2%    |
| More than 240 | 3         | 4.92%   |
| 1-50          | 3         | 4.92%   |
| Unknown       | 1         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 45        | 81.82%  |
| 2     | 9         | 16.36%  |
| 0     | 1         | 1.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 31        | 36.9%   |
| Intel                 | 28        | 33.33%  |
| Qualcomm Atheros      | 10        | 11.9%   |
| Broadcom              | 6         | 7.14%   |
| MediaTek              | 2         | 2.38%   |
| Hewlett-Packard       | 2         | 2.38%   |
| ASIX Electronics      | 2         | 2.38%   |
| Nvidia                | 1         | 1.19%   |
| Huawei Technologies   | 1         | 1.19%   |
| Broadcom Limited      | 1         | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 16        | 16.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 5.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 5.1%    |
| Intel Wi-Fi 6 AX201                                                     | 5         | 5.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 4.08%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 3.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.04%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.04%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 2.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.04%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.04%   |
| ASIX AX88179 Gigabit Ethernet                                           | 2         | 2.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.02%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.02%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 1.02%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 1.02%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.02%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.02%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.02%   |
| Intel Wireless 8260                                                     | 1         | 1.02%   |
| Intel Wireless 7265                                                     | 1         | 1.02%   |
| Intel Wireless 7260                                                     | 1         | 1.02%   |
| Intel Wireless 3165                                                     | 1         | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.02%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.02%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 1.02%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1         | 1.02%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 50%     |
| Realtek Semiconductor | 10        | 18.52%  |
| Qualcomm Atheros      | 8         | 14.81%  |
| Broadcom              | 6         | 11.11%  |
| MediaTek              | 2         | 3.7%    |
| Hewlett-Packard       | 1         | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 5         | 9.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 7.41%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 7.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 5.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 5.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 3.7%    |
| Intel Wireless 8265 / 8275                                              | 2         | 3.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 3.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 3.7%    |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 3.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.85%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.85%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.85%   |
| Intel Wireless 8260                                                     | 1         | 1.85%   |
| Intel Wireless 7265                                                     | 1         | 1.85%   |
| Intel Wireless 7260                                                     | 1         | 1.85%   |
| Intel Wireless 3165                                                     | 1         | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.85%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.85%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 66.67%  |
| Intel                 | 5         | 11.9%   |
| Qualcomm Atheros      | 2         | 4.76%   |
| Broadcom              | 2         | 4.76%   |
| ASIX Electronics      | 2         | 4.76%   |
| Nvidia                | 1         | 2.38%   |
| Hewlett-Packard       | 1         | 2.38%   |
| Broadcom Limited      | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 37.21%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 11.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.63%  |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 4.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 4.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.33%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 2.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.33%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.33%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.33%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.33%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.33%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.33%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 2.33%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 55.91%  |
| Ethernet | 40        | 43.01%  |
| Modem    | 1         | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 81.82%  |
| Ethernet | 10        | 18.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 34        | 62.96%  |
| 1     | 16        | 29.63%  |
| 0     | 4         | 7.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 62.5%   |
| Yes  | 21        | 37.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 52.17%  |
| Realtek Semiconductor           | 5         | 10.87%  |
| Qualcomm Atheros Communications | 5         | 10.87%  |
| Broadcom                        | 3         | 6.52%   |
| Apple                           | 3         | 6.52%   |
| IMC Networks                    | 2         | 4.35%   |
| Dell                            | 2         | 4.35%   |
| Unknown                         | 1         | 2.17%   |
| Foxconn International           | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                             | 9         | 19.57%  |
| Intel Bluetooth wireless interface                 | 7         | 15.22%  |
| Realtek Bluetooth Radio                            | 4         | 8.7%    |
| Qualcomm Atheros  Bluetooth Device                 | 4         | 8.7%    |
| Intel AX200 Bluetooth                              | 4         | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 4.35%   |
| Dell DW375 Bluetooth Module                        | 2         | 4.35%   |
| Apple Bluetooth Host Controller                    | 2         | 4.35%   |
| Unknown Bluetooth Device                           | 1         | 2.17%   |
| Realtek RTL8723B Bluetooth                         | 1         | 2.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 2.17%   |
| Intel AX210 Bluetooth                              | 1         | 2.17%   |
| IMC Networks Wireless_Device                       | 1         | 2.17%   |
| IMC Networks Bluetooth Radio                       | 1         | 2.17%   |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 2.17%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 2.17%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 2.17%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 2.17%   |
| Apple Bluetooth USB Host Controller                | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 42        | 70%     |
| AMD                  | 8         | 13.33%  |
| Nvidia               | 7         | 11.67%  |
| Plantronics          | 1         | 1.67%   |
| Logitech             | 1         | 1.67%   |
| LINE TECH INDUSTRIAL | 1         | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 9.86%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 9.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 8.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 7.04%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 4.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 4.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 4.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 4.23%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 2.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.82%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.82%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 1.41%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.41%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.41%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.41%   |
| Logitech PRO X                                                             | 1         | 1.41%   |
| LINE TECH INDUSTRIAL YTL HEADSET                                           | 1         | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.41%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.41%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.41%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.41%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.41%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 33.33%  |
| SK hynix            | 9         | 23.08%  |
| Kingston            | 5         | 12.82%  |
| Unknown (ABCD)      | 2         | 5.13%   |
| Ramaxel Technology  | 2         | 5.13%   |
| Micron Technology   | 2         | 5.13%   |
| Unknown             | 1         | 2.56%   |
| Teikon              | 1         | 2.56%   |
| fef5                | 1         | 2.56%   |
| Elpida              | 1         | 2.56%   |
| 8945000080AD        | 1         | 2.56%   |
| Unknown             | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 4.88%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 4.88%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 2.44%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 2.44%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.44%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 2.44%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 2.44%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 2.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.44%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.44%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 2.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 1         | 2.44%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.44%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 2.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.44%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.44%   |
| Samsung RAM M471A1K44BM0-CRC 8192MB SODIMM DDR4 2400MT/s         | 1         | 2.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.44%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB 2400MT/s                         | 1         | 2.44%   |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 2.44%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 2.44%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 1         | 2.44%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.44%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.44%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 2.44%   |
| Kingston RAM 9905703-008.A00G 16GB SODIMM DDR4 2667MT/s          | 1         | 2.44%   |
| Kingston RAM 9905700-084.A00G 16GB SODIMM DDR4 3200MT/s          | 1         | 2.44%   |
| Kingston RAM 9905624-059.A00G 8192MB SODIMM DDR4 2667MT/s        | 1         | 2.44%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 2.44%   |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                            | 1         | 2.44%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 1         | 2.44%   |
| 8945000080AD RAM GKE800SO102408-2400 8GB SODIMM DDR4 2400MT/s    | 1         | 2.44%   |
| Unknown                                                          | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 19        | 59.38%  |
| DDR3    | 8         | 25%     |
| LPDDR4  | 4         | 12.5%   |
| Unknown | 1         | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 87.5%   |
| Row Of Chips | 2         | 6.25%   |
| Chip         | 1         | 3.13%   |
| Unknown      | 1         | 3.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 16        | 48.48%  |
| 4096  | 7         | 21.21%  |
| 16384 | 5         | 15.15%  |
| 32768 | 2         | 6.06%   |
| 2048  | 2         | 6.06%   |
| 1024  | 1         | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 9         | 26.47%  |
| 2667  | 7         | 20.59%  |
| 2400  | 6         | 17.65%  |
| 1600  | 5         | 14.71%  |
| 4267  | 1         | 2.94%   |
| 3266  | 1         | 2.94%   |
| 2133  | 1         | 2.94%   |
| 1334  | 1         | 2.94%   |
| 1333  | 1         | 2.94%   |
| 1067  | 1         | 2.94%   |
| 1066  | 1         | 2.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1320 | 1         | 50%     |
| Canon LiDE 400   | 1         | 50%     |

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
| Chicony Electronics                    | 12        | 27.27%  |
| IMC Networks                           | 6         | 13.64%  |
| Realtek Semiconductor                  | 4         | 9.09%   |
| Acer                                   | 4         | 9.09%   |
| Syntek                                 | 3         | 6.82%   |
| Sunplus Innovation Technology          | 3         | 6.82%   |
| Apple                                  | 3         | 6.82%   |
| Microdia                               | 2         | 4.55%   |
| Luxvisions Innotech Limited            | 2         | 4.55%   |
| Quanta                                 | 1         | 2.27%   |
| Polycom                                | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.27%   |
| Alcor Micro                            | 1         | 2.27%   |
| Unknown                                | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 3         | 6.82%   |
| Syntek Integrated Camera                                                   | 2         | 4.55%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 4.55%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 4.55%   |
| Chicony USB2.0 Camera                                                      | 2         | 4.55%   |
| Chicony Integrated Camera                                                  | 2         | 4.55%   |
| Chicony HD Webcam                                                          | 2         | 4.55%   |
| Apple FaceTime HD Camera                                                   | 2         | 4.55%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 4.55%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 2.27%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 2.27%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.27%   |
| Sunplus HD WebCam                                                          | 1         | 2.27%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 2.27%   |
| Realtek Integrated Webcam                                                  | 1         | 2.27%   |
| Quanta USB2.0 HD UVC WebCam                                                | 1         | 2.27%   |
| Polycom Poly Studio P5 webcam                                              | 1         | 2.27%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.27%   |
| Microdia Integrated Webcam HD                                              | 1         | 2.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 2.27%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 2.27%   |
| IMC Networks Integrated RGB Camera                                         | 1         | 2.27%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 1         | 2.27%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 2.27%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 2.27%   |
| Chicony HP Truevision HD camera                                            | 1         | 2.27%   |
| Chicony HP Integrated Webcam                                               | 1         | 2.27%   |
| Chicony HP HD Camera                                                       | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.27%   |
| Apple Built-in iSight                                                      | 1         | 2.27%   |
| Alcor Micro USB Camera                                                     | 1         | 2.27%   |
| Acer Integrated Camera                                                     | 1         | 2.27%   |
| Acer EasyCamera                                                            | 1         | 2.27%   |
| Unknown                                                                    | 1         | 2.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 36.36%  |
| Shenzhen Goodix Technology | 4         | 36.36%  |
| Validity Sensors           | 2         | 18.18%  |
| Elan Microelectronics      | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                       | 2         | 18.18%  |
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 9.09%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 9.09%   |
| Shenzhen Goodix FingerPrint                               | 1         | 9.09%   |
| Elan ELAN:Fingerprint                                     | 1         | 9.09%   |
| Unknown                                                   | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 33        | 61.11%  |
| 1     | 15        | 27.78%  |
| 2     | 4         | 7.41%   |
| 6     | 1         | 1.85%   |
| 3     | 1         | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 35.71%  |
| Net/wireless             | 4         | 14.29%  |
| Graphics card            | 3         | 10.71%  |
| Communication controller | 3         | 10.71%  |
| Sound                    | 2         | 7.14%   |
| Chipcard                 | 2         | 7.14%   |
| Camera                   | 2         | 7.14%   |
| Multimedia controller    | 1         | 3.57%   |
| Bluetooth                | 1         | 3.57%   |

