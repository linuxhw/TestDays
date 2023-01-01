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

Total: 64

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-27-generic     | 7         | 12.73%  |
| 5.15.0-50-generic     | 5         | 9.09%   |
| 5.15.0-48-generic     | 5         | 9.09%   |
| 5.15.0-52-generic     | 4         | 7.27%   |
| 5.15.0-53-generic     | 3         | 5.45%   |
| 5.15.0-40-generic     | 3         | 5.45%   |
| 5.15.0-39-generic     | 3         | 5.45%   |
| 5.15.0-30-generic     | 3         | 5.45%   |
| 5.15.0-56-generic     | 2         | 3.64%   |
| 5.15.0-47-generic     | 2         | 3.64%   |
| 5.15.0-46-generic     | 2         | 3.64%   |
| 5.15.0-33-generic     | 2         | 3.64%   |
| 5.15.0-25-generic     | 2         | 3.64%   |
| 5.19.0-051900-generic | 1         | 1.82%   |
| 5.15.0-52-lowlatency  | 1         | 1.82%   |
| 5.15.0-43-generic     | 1         | 1.82%   |
| 5.15.0-41-generic     | 1         | 1.82%   |
| 5.15.0-35-generic     | 1         | 1.82%   |
| 5.15.0-18-generic     | 1         | 1.82%   |
| 5.15.0-10056-tuxedo   | 1         | 1.82%   |
| 5.15.0-10052-tuxedo   | 1         | 1.82%   |
| 5.15.0-10047-tuxedo   | 1         | 1.82%   |
| 5.15.0-10041-tuxedo   | 1         | 1.82%   |
| 5.13.0-35-generic     | 1         | 1.82%   |
| 5.13.0-19-generic     | 1         | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 49        | 94.23%  |
| 5.13.0  | 2         | 3.85%   |
| 5.19.0  | 1         | 1.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 49        | 94.23%  |
| 5.13    | 2         | 3.85%   |
| 5.19    | 1         | 1.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 52        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 49        | 94.23%  |
| GNOME  | 3         | 5.77%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 50        | 96.15%  |
| Wayland | 2         | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 36        | 69.23%  |
| Unknown | 10        | 19.23%  |
| GDM3    | 6         | 11.54%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 16        | 30.77%  |
| fr_FR | 7         | 13.46%  |
| de_DE | 7         | 13.46%  |
| pt_BR | 5         | 9.62%   |
| ru_RU | 2         | 3.85%   |
| hu_HU | 2         | 3.85%   |
| en_GB | 2         | 3.85%   |
| en_CA | 2         | 3.85%   |
| it_IT | 1         | 1.92%   |
| fr_BE | 1         | 1.92%   |
| es_PE | 1         | 1.92%   |
| es_MX | 1         | 1.92%   |
| es_EC | 1         | 1.92%   |
| es_CL | 1         | 1.92%   |
| en_IE | 1         | 1.92%   |
| cs_CZ | 1         | 1.92%   |
| C     | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 31        | 59.62%  |
| EFI  | 21        | 40.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 48        | 92.31%  |
| Overlay | 2         | 3.85%   |
| Xfs     | 1         | 1.92%   |
| Btrfs   | 1         | 1.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 30        | 57.69%  |
| Unknown | 19        | 36.54%  |
| MBR     | 3         | 5.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 80.77%  |
| Yes       | 10        | 19.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 71.7%   |
| Yes       | 15        | 28.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 13        | 25%     |
| Dell                   | 9         | 17.31%  |
| Hewlett-Packard        | 6         | 11.54%  |
| ASUSTek Computer       | 5         | 9.62%   |
| TUXEDO                 | 4         | 7.69%   |
| Apple                  | 3         | 5.77%   |
| MSI                    | 2         | 3.85%   |
| Google                 | 2         | 3.85%   |
| Toshiba                | 1         | 1.92%   |
| Timi                   | 1         | 1.92%   |
| Razer                  | 1         | 1.92%   |
| Digibras               | 1         | 1.92%   |
| Chuwi                  | 1         | 1.92%   |
| AXIOO                  | 1         | 1.92%   |
| Avell High Performance | 1         | 1.92%   |
| Acer                   | 1         | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1.92%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 1.92%   |
| TUXEDO Book BA1510                                   | 1         | 1.92%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.92%   |
| Toshiba Satellite A505                               | 1         | 1.92%   |
| Timi TM1604                                          | 1         | 1.92%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.92%   |
| MSI Modern 15 A10M                                   | 1         | 1.92%   |
| MSI GL62 6QF                                         | 1         | 1.92%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1.92%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.92%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.92%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.92%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.92%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.92%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1.92%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.92%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.92%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.92%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.92%   |
| Lenovo G500 20236                                    | 1         | 1.92%   |
| Lenovo G50-45 80E3                                   | 1         | 1.92%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1.92%   |
| HP ProBook 445 G7                                    | 1         | 1.92%   |
| HP Pavilion g6                                       | 1         | 1.92%   |
| HP ENVY 17                                           | 1         | 1.92%   |
| HP ElitePad 1000 G2                                  | 1         | 1.92%   |
| HP EliteBook 840 G3                                  | 1         | 1.92%   |
| Google Rabbid                                        | 1         | 1.92%   |
| Google Boten                                         | 1         | 1.92%   |
| Digibras NH4CU03                                     | 1         | 1.92%   |
| Dell XPS 13 9360                                     | 1         | 1.92%   |
| Dell XPS 13 9310                                     | 1         | 1.92%   |
| Dell Vostro 15 5510                                  | 1         | 1.92%   |
| Dell Precision 5560                                  | 1         | 1.92%   |
| Dell Latitude E6410                                  | 1         | 1.92%   |
| Dell Latitude E5420                                  | 1         | 1.92%   |
| Dell Inspiron 5570                                   | 1         | 1.92%   |
| Dell Inspiron 5566                                   | 1         | 1.92%   |
| Dell Inspiron 3793                                   | 1         | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 5         | 9.62%   |
| Lenovo IdeaPad              | 4         | 7.69%   |
| Dell Inspiron               | 3         | 5.77%   |
| TUXEDO Book                 | 2         | 3.85%   |
| HP ProBook                  | 2         | 3.85%   |
| Dell XPS                    | 2         | 3.85%   |
| Dell Latitude               | 2         | 3.85%   |
| ASUS VivoBook               | 2         | 3.85%   |
| TUXEDO Polaris              | 1         | 1.92%   |
| TUXEDO Aura                 | 1         | 1.92%   |
| Toshiba Satellite           | 1         | 1.92%   |
| Timi TM1604                 | 1         | 1.92%   |
| Razer Blade                 | 1         | 1.92%   |
| MSI Modern                  | 1         | 1.92%   |
| MSI GL62                    | 1         | 1.92%   |
| Lenovo V15                  | 1         | 1.92%   |
| Lenovo Legion               | 1         | 1.92%   |
| Lenovo G500                 | 1         | 1.92%   |
| Lenovo G50-45               | 1         | 1.92%   |
| HP Pavilion                 | 1         | 1.92%   |
| HP ENVY                     | 1         | 1.92%   |
| HP ElitePad                 | 1         | 1.92%   |
| HP EliteBook                | 1         | 1.92%   |
| Google Rabbid               | 1         | 1.92%   |
| Google Boten                | 1         | 1.92%   |
| Digibras NH4CU03            | 1         | 1.92%   |
| Dell Vostro                 | 1         | 1.92%   |
| Dell Precision              | 1         | 1.92%   |
| Chuwi HeroBook              | 1         | 1.92%   |
| AXIOO Slimbook              | 1         | 1.92%   |
| Avell High Performance B.ON | 1         | 1.92%   |
| ASUS ZenBook                | 1         | 1.92%   |
| ASUS X205TA                 | 1         | 1.92%   |
| ASUS T200TAC                | 1         | 1.92%   |
| Apple MacBookPro9           | 1         | 1.92%   |
| Apple MacBookPro8           | 1         | 1.92%   |
| Apple MacBookPro5           | 1         | 1.92%   |
| Acer Aspire                 | 1         | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 11        | 21.15%  |
| 2020 | 8         | 15.38%  |
| 2019 | 5         | 9.62%   |
| 2018 | 4         | 7.69%   |
| 2016 | 4         | 7.69%   |
| 2014 | 4         | 7.69%   |
| 2013 | 3         | 5.77%   |
| 2011 | 3         | 5.77%   |
| 2017 | 2         | 3.85%   |
| 2010 | 2         | 3.85%   |
| 2009 | 2         | 3.85%   |
| 2022 | 1         | 1.92%   |
| 2015 | 1         | 1.92%   |
| 2012 | 1         | 1.92%   |
| 2008 | 1         | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 52        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 48        | 92.31%  |
| Enabled  | 4         | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 96.15%  |
| Yes  | 2         | 3.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 17        | 32.69%  |
| 16.01-24.0  | 13        | 25%     |
| 3.01-4.0    | 7         | 13.46%  |
| 8.01-16.0   | 7         | 13.46%  |
| 32.01-64.0  | 5         | 9.62%   |
| 64.01-256.0 | 2         | 3.85%   |
| 1.01-2.0    | 1         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 18        | 33.96%  |
| 2.01-3.0   | 14        | 26.42%  |
| 4.01-8.0   | 13        | 24.53%  |
| 3.01-4.0   | 4         | 7.55%   |
| 8.01-16.0  | 3         | 5.66%   |
| 24.01-32.0 | 1         | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 69.81%  |
| 2      | 14        | 26.42%  |
| 3      | 2         | 3.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 84.62%  |
| Yes       | 8         | 15.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 73.08%  |
| No        | 14        | 26.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 96.15%  |
| No        | 2         | 3.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 84.62%  |
| No        | 8         | 15.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 8         | 15.38%  |
| Germany            | 7         | 13.46%  |
| France             | 7         | 13.46%  |
| Brazil             | 5         | 9.62%   |
| Hungary            | 2         | 3.85%   |
| Canada             | 2         | 3.85%   |
| Sweden             | 1         | 1.92%   |
| Slovenia           | 1         | 1.92%   |
| Russia             | 1         | 1.92%   |
| Romania            | 1         | 1.92%   |
| Poland             | 1         | 1.92%   |
| Peru               | 1         | 1.92%   |
| Mexico             | 1         | 1.92%   |
| Italy              | 1         | 1.92%   |
| Ireland            | 1         | 1.92%   |
| Indonesia          | 1         | 1.92%   |
| Greece             | 1         | 1.92%   |
| Ghana              | 1         | 1.92%   |
| Ecuador            | 1         | 1.92%   |
| Dominican Republic | 1         | 1.92%   |
| Czechia            | 1         | 1.92%   |
| Chile              | 1         | 1.92%   |
| Cabo Verde         | 1         | 1.92%   |
| Belgium            | 1         | 1.92%   |
| Belarus            | 1         | 1.92%   |
| Austria            | 1         | 1.92%   |
| Algeria            | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Budapest              | 2         | 3.85%   |
| Wertheim am Main      | 1         | 1.92%   |
| Weisswasser           | 1         | 1.92%   |
| Warsaw                | 1         | 1.92%   |
| Vienna                | 1         | 1.92%   |
| Victoria              | 1         | 1.92%   |
| Targu Frumos          | 1         | 1.92%   |
| Tarakan               | 1         | 1.92%   |
| Sunnyvale             | 1         | 1.92%   |
| St Petersburg         | 1         | 1.92%   |
| Siegen                | 1         | 1.92%   |
| Sétif                | 1         | 1.92%   |
| Seelze                | 1         | 1.92%   |
| Sao Paulo             | 1         | 1.92%   |
| Sao Bernardo do Campo | 1         | 1.92%   |
| Santo Domingo Este    | 1         | 1.92%   |
| Santiago              | 1         | 1.92%   |
| Saint-Gilles          | 1         | 1.92%   |
| Recife                | 1         | 1.92%   |
| Queens                | 1         | 1.92%   |
| Puebla City           | 1         | 1.92%   |
| Praia                 | 1         | 1.92%   |
| Postojna              | 1         | 1.92%   |
| Ostrava               | 1         | 1.92%   |
| Orvault               | 1         | 1.92%   |
| Nuremberg             | 1         | 1.92%   |
| Monza                 | 1         | 1.92%   |
| Mishawaka             | 1         | 1.92%   |
| Massaranduba          | 1         | 1.92%   |
| Lund                  | 1         | 1.92%   |
| Lima                  | 1         | 1.92%   |
| Lille                 | 1         | 1.92%   |
| Leominster            | 1         | 1.92%   |
| Le Mee-sur-Seine      | 1         | 1.92%   |
| Laval                 | 1         | 1.92%   |
| Kassel                | 1         | 1.92%   |
| Fontenay-sous-Bois    | 1         | 1.92%   |
| Dublin                | 1         | 1.92%   |
| DeQuincy              | 1         | 1.92%   |
| Cuenca                | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 13        | 14     | 19.12%  |
| Unknown                        | 7         | 7      | 10.29%  |
| Toshiba                        | 6         | 7      | 8.82%   |
| Crucial                        | 5         | 6      | 7.35%   |
| WDC                            | 4         | 5      | 5.88%   |
| SK hynix                       | 4         | 4      | 5.88%   |
| Seagate                        | 3         | 3      | 4.41%   |
| Micron Technology              | 3         | 3      | 4.41%   |
| Kingston                       | 2         | 2      | 2.94%   |
| JMicron Technology             | 2         | 2      | 2.94%   |
| Intel                          | 2         | 2      | 2.94%   |
| China                          | 2         | 3      | 2.94%   |
| VISIPRO                        | 1         | 1      | 1.47%   |
| Union Memory                   | 1         | 1      | 1.47%   |
| TO Exter                       | 1         | 1      | 1.47%   |
| SPCC                           | 1         | 1      | 1.47%   |
| Solid State Storage Technology | 1         | 1      | 1.47%   |
| Realtek Semiconductor          | 1         | 1      | 1.47%   |
| Phison Electronics             | 1         | 1      | 1.47%   |
| OWC                            | 1         | 1      | 1.47%   |
| Netac                          | 1         | 1      | 1.47%   |
| KIOXIA                         | 1         | 1      | 1.47%   |
| Hewlett-Packard                | 1         | 1      | 1.47%   |
| Corsair                        | 1         | 2      | 1.47%   |
| Apple                          | 1         | 1      | 1.47%   |
| A-DATA Technology              | 1         | 1      | 1.47%   |
| Unknown                        | 1         | 1      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 2.9%    |
| Unknown SD64G  64GB                                 | 2         | 2.9%    |
| Samsung SSD 980 PRO 2TB                             | 2         | 2.9%    |
| Samsung SSD 980 500GB                               | 2         | 2.9%    |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 1.45%   |
| WDC PC SN730 NVMe 256GB                             | 1         | 1.45%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 1.45%   |
| VISIPRO SSD 256GB                                   | 1         | 1.45%   |
| Unknown SL128  128GB                                | 1         | 1.45%   |
| Unknown SA16G  16GB                                 | 1         | 1.45%   |
| Unknown NCard  4GB                                  | 1         | 1.45%   |
| Unknown MMC128  128GB                               | 1         | 1.45%   |
| Unknown MMC Card  64GB                              | 1         | 1.45%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD              | 1         | 1.45%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 1         | 1.45%   |
| Toshiba TR150 480GB SSD                             | 1         | 1.45%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1.45%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 1.45%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                   | 1         | 1.45%   |
| Toshiba KBG30ZMT256G 256GB                          | 1         | 1.45%   |
| TO Exter nal USB 3.0 512GB                          | 1         | 1.45%   |
| SPCC Solid State Disk 120GB                         | 1         | 1.45%   |
| Solid State Storage NVMe CA6-8D1024 1024GB          | 1         | 1.45%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB           | 1         | 1.45%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB                | 1         | 1.45%   |
| SK hynix HCG8e  64GB                                | 1         | 1.45%   |
| SK hynix HBG4e  32GB                                | 1         | 1.45%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1.45%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.45%   |
| Samsung SSD 860 EVO M.2 500GB                       | 1         | 1.45%   |
| Samsung SSD 860 EVO M.2 250GB                       | 1         | 1.45%   |
| Samsung SSD 860 EVO 500GB                           | 1         | 1.45%   |
| Samsung SSD 850 EVO 500GB                           | 1         | 1.45%   |
| Samsung SSD 850 EVO 250GB                           | 1         | 1.45%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 1         | 1.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 1         | 1.45%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 1         | 1.45%   |
| Samsung HM320II 320GB                               | 1         | 1.45%   |
| Realtek NVMe SSD Drive 512GB                        | 1         | 1.45%   |

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
| Samsung Electronics | 5         | 5      | 19.23%  |
| Crucial             | 5         | 6      | 19.23%  |
| Micron Technology   | 2         | 2      | 7.69%   |
| China               | 2         | 3      | 7.69%   |
| VISIPRO             | 1         | 1      | 3.85%   |
| Union Memory        | 1         | 1      | 3.85%   |
| Toshiba             | 1         | 1      | 3.85%   |
| TO Exter            | 1         | 1      | 3.85%   |
| SPCC                | 1         | 1      | 3.85%   |
| OWC                 | 1         | 1      | 3.85%   |
| Netac               | 1         | 1      | 3.85%   |
| JMicron Technology  | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |
| Corsair             | 1         | 2      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 23        | 26     | 37.1%   |
| SSD     | 22        | 29     | 35.48%  |
| MMC     | 8         | 10     | 12.9%   |
| HDD     | 8         | 8      | 12.9%   |
| Unknown | 1         | 1      | 1.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 27        | 35     | 45%     |
| NVMe | 23        | 26     | 38.33%  |
| MMC  | 8         | 10     | 13.33%  |
| SAS  | 2         | 3      | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 28     | 71.88%  |
| 0.51-1.0   | 6         | 6      | 18.75%  |
| 1.01-2.0   | 3         | 3      | 9.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 18        | 34.62%  |
| 101-250        | 17        | 32.69%  |
| 51-100         | 6         | 11.54%  |
| 21-50          | 3         | 5.77%   |
| 1001-2000      | 3         | 5.77%   |
| 501-1000       | 3         | 5.77%   |
| More than 3000 | 1         | 1.92%   |
| 1-20           | 1         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 15        | 28.3%   |
| 21-50     | 13        | 24.53%  |
| 101-250   | 10        | 18.87%  |
| 51-100    | 8         | 15.09%  |
| 251-500   | 4         | 7.55%   |
| 501-1000  | 2         | 3.77%   |
| 1001-2000 | 1         | 1.89%   |

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
| Detected | 32        | 42     | 58.18%  |
| Works    | 23        | 32     | 41.82%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 31        | 50.82%  |
| Samsung Electronics            | 7         | 11.48%  |
| AMD                            | 6         | 9.84%   |
| Toshiba America Info Systems   | 3         | 4.92%   |
| SK hynix                       | 2         | 3.28%   |
| SanDisk                        | 2         | 3.28%   |
| KIOXIA                         | 2         | 3.28%   |
| Kingston Technology Company    | 2         | 3.28%   |
| Solid State Storage Technology | 1         | 1.64%   |
| Realtek Semiconductor          | 1         | 1.64%   |
| Phison Electronics             | 1         | 1.64%   |
| Nvidia                         | 1         | 1.64%   |
| Micron Technology              | 1         | 1.64%   |
| ADATA Technology               | 1         | 1.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 6         | 9.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 5         | 7.94%   |
| Samsung NVMe SSD Controller 980                                              | 3         | 4.76%   |
| Intel Volume Management Device NVMe RAID Controller                          | 3         | 4.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 4.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 4.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 3.17%   |
| KIOXIA NVMe SSD Controller BG4                                               | 2         | 3.17%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 3.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 3.17%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 1.59%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 1.59%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 1.59%   |
| Solid State Storage Non-Volatile memory controller                           | 1         | 1.59%   |
| SK hynix Non-Volatile memory controller                                      | 1         | 1.59%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 1         | 1.59%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 1.59%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 1.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 1.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.59%   |
| Realtek Realtek Non-Volatile memory controller                               | 1         | 1.59%   |
| Phison NVMe Storage Controller                                               | 1         | 1.59%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 1.59%   |
| Micron Non-Volatile memory controller                                        | 1         | 1.59%   |
| Kingston Company Company Non-Volatile memory controller                      | 1         | 1.59%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 1.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 1.59%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 1.59%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 1         | 1.59%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.59%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 1         | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 1.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                         | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 1.59%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                  | 1         | 1.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 34        | 55.74%  |
| NVMe | 23        | 37.7%   |
| RAID | 3         | 4.92%   |
| IDE  | 1         | 1.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 84.62%  |
| AMD    | 8         | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 5.77%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.85%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 3.85%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 3.85%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 3.85%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 3.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.85%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.92%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.92%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.92%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.92%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.92%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.92%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.92%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.92%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.92%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.92%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 1.92%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.92%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.92%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.92%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.92%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 1.92%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 1.92%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 1         | 1.92%   |
| Intel Celeron N4500 @ 1.10GHz                 | 1         | 1.92%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.92%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 1         | 1.92%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz       | 1         | 1.92%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 1         | 1.92%   |
| Intel 11th Gen Core i5-11320H @ 3.20GHz       | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 14        | 26.92%  |
| Other                | 8         | 15.38%  |
| Intel Core i7        | 7         | 13.46%  |
| Intel Celeron        | 4         | 7.69%   |
| AMD Ryzen 5          | 4         | 7.69%   |
| Intel Core i3        | 3         | 5.77%   |
| Intel Atom           | 3         | 5.77%   |
| Intel Core 2 Duo     | 2         | 3.85%   |
| AMD Ryzen 7          | 2         | 3.85%   |
| Intel Pentium Silver | 1         | 1.92%   |
| Intel Pentium        | 1         | 1.92%   |
| Intel Core i9        | 1         | 1.92%   |
| AMD Ryzen 3          | 1         | 1.92%   |
| AMD A8               | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 23        | 44.23%  |
| 2      | 20        | 38.46%  |
| 8      | 5         | 9.62%   |
| 6      | 3         | 5.77%   |
| 10     | 1         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 37        | 71.15%  |
| 1      | 15        | 28.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 52        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 53.85%  |
| 0x206a7    | 3         | 5.77%   |
| 0x08600106 | 3         | 5.77%   |
| 0x806c1    | 2         | 3.85%   |
| 0x706a8    | 2         | 3.85%   |
| 0x08108102 | 2         | 3.85%   |
| 0x906ea    | 1         | 1.92%   |
| 0x806ec    | 1         | 1.92%   |
| 0x806eb    | 1         | 1.92%   |
| 0x806d1    | 1         | 1.92%   |
| 0x506c9    | 1         | 1.92%   |
| 0x40651    | 1         | 1.92%   |
| 0x306d4    | 1         | 1.92%   |
| 0x30678    | 1         | 1.92%   |
| 0x20655    | 1         | 1.92%   |
| 0x106e5    | 1         | 1.92%   |
| 0x0a50000c | 1         | 1.92%   |
| 0x07030104 | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 19.23%  |
| TigerLake     | 5         | 9.62%   |
| Unknown       | 4         | 7.69%   |
| Zen 2         | 3         | 5.77%   |
| Skylake       | 3         | 5.77%   |
| Silvermont    | 3         | 5.77%   |
| SandyBridge   | 3         | 5.77%   |
| IvyBridge     | 3         | 5.77%   |
| Goldmont plus | 3         | 5.77%   |
| Zen+          | 2         | 3.85%   |
| Penryn        | 2         | 3.85%   |
| IceLake       | 2         | 3.85%   |
| Haswell       | 2         | 3.85%   |
| Zen 3         | 1         | 1.92%   |
| Westmere      | 1         | 1.92%   |
| Puma          | 1         | 1.92%   |
| Nehalem       | 1         | 1.92%   |
| Goldmont      | 1         | 1.92%   |
| CometLake     | 1         | 1.92%   |
| Broadwell     | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 63.08%  |
| Nvidia | 14        | 21.54%  |
| AMD    | 10        | 15.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 5         | 7.58%   |
| Intel UHD Graphics 620                                                                | 4         | 6.06%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 4.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 3         | 4.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 4.55%   |
| AMD Renoir                                                                            | 3         | 4.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 3.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 3.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.03%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                                | 1         | 1.52%   |
| Nvidia GT218M [GeForce 310M]                                                          | 1         | 1.52%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 1.52%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.52%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 1.52%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.52%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 1.52%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 1.52%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                    | 1         | 1.52%   |
| Nvidia C79 [GeForce 9400M]                                                            | 1         | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.52%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                           | 1         | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.52%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 1.52%   |
| Intel Iris Plus Graphics G7                                                           | 1         | 1.52%   |
| Intel HD Graphics 620                                                                 | 1         | 1.52%   |
| Intel HD Graphics 5500                                                                | 1         | 1.52%   |
| Intel HD Graphics 530                                                                 | 1         | 1.52%   |
| Intel HD Graphics 500                                                                 | 1         | 1.52%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 1.52%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.52%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 1         | 1.52%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 53.85%  |
| Intel + Nvidia | 10        | 19.23%  |
| 1 x AMD        | 6         | 11.54%  |
| 1 x Nvidia     | 3         | 5.77%   |
| Intel + AMD    | 2         | 3.85%   |
| Other          | 1         | 1.92%   |
| 2 x AMD        | 1         | 1.92%   |
| AMD + Nvidia   | 1         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 44        | 84.62%  |
| Proprietary | 7         | 13.46%  |
| Unknown     | 1         | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 80.77%  |
| 1.01-2.0   | 4         | 7.69%   |
| 0.01-0.5   | 3         | 5.77%   |
| 0.51-1.0   | 2         | 3.85%   |
| 7.01-8.0   | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 14        | 24.14%  |
| BOE                     | 13        | 22.41%  |
| Samsung Electronics     | 7         | 12.07%  |
| LG Display              | 5         | 8.62%   |
| AU Optronics            | 5         | 8.62%   |
| Sharp                   | 3         | 5.17%   |
| Apple                   | 3         | 5.17%   |
| Goldstar                | 2         | 3.45%   |
| Unknown (AAA)           | 1         | 1.72%   |
| Philips                 | 1         | 1.72%   |
| MStar                   | 1         | 1.72%   |
| Lenovo                  | 1         | 1.72%   |
| IBM                     | 1         | 1.72%   |
| Chi Mei Optoelectronics | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 3.45%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch                 | 1         | 1.72%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                  | 1         | 1.72%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 1.72%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 1         | 1.72%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch     | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch    | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch     | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch   | 1         | 1.72%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                  | 1         | 1.72%   |
| MStar LCD TV MST9000 1360x768                                            | 1         | 1.72%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch             | 1         | 1.72%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 1.72%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 1         | 1.72%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch              | 1         | 1.72%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch              | 1         | 1.72%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch                 | 1         | 1.72%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                    | 1         | 1.72%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 1         | 1.72%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN13B0 2560x1600 290x180mm 13.4-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1138 1366x768 256x144mm 11.6-inch          | 1         | 1.72%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.72%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                    | 1         | 1.72%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                    | 1         | 1.72%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                    | 1         | 1.72%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 1         | 1.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 37.04%  |
| 1366x768 (WXGA)    | 15        | 27.78%  |
| 2560x1440 (QHD)    | 3         | 5.56%   |
| 1600x900 (HD+)     | 3         | 5.56%   |
| 1280x800 (WXGA)    | 3         | 5.56%   |
| 1920x1200 (WUXGA)  | 2         | 3.7%    |
| 1680x1050 (WSXGA+) | 2         | 3.7%    |
| 3840x2160 (4K)     | 1         | 1.85%   |
| 3456x2160          | 1         | 1.85%   |
| 2880x1800          | 1         | 1.85%   |
| 2560x1600          | 1         | 1.85%   |
| 1440x900 (WXGA+)   | 1         | 1.85%   |
| 1360x768           | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 23        | 39.66%  |
| 13      | 12        | 20.69%  |
| 14      | 6         | 10.34%  |
| 17      | 4         | 6.9%    |
| 11      | 3         | 5.17%   |
| 40      | 2         | 3.45%   |
| 27      | 2         | 3.45%   |
| 60      | 1         | 1.72%   |
| 31      | 1         | 1.72%   |
| 23      | 1         | 1.72%   |
| 21      | 1         | 1.72%   |
| 10      | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 34        | 58.62%  |
| 201-300     | 10        | 17.24%  |
| 351-400     | 5         | 8.62%   |
| 801-900     | 2         | 3.45%   |
| 501-600     | 2         | 3.45%   |
| 401-500     | 2         | 3.45%   |
| 601-700     | 1         | 1.72%   |
| 1001-1500   | 1         | 1.72%   |
| Unknown     | 1         | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 41        | 78.85%  |
| 16/10 | 10        | 19.23%  |
| 3/2   | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 39.66%  |
| 81-90          | 15        | 25.86%  |
| 121-130        | 4         | 6.9%    |
| 71-80          | 3         | 5.17%   |
| 51-60          | 3         | 5.17%   |
| 301-350        | 2         | 3.45%   |
| 201-250        | 2         | 3.45%   |
| 501-1000       | 2         | 3.45%   |
| More than 1000 | 1         | 1.72%   |
| 351-500        | 1         | 1.72%   |
| 41-50          | 1         | 1.72%   |
| Unknown        | 1         | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 24        | 41.38%  |
| 101-120       | 16        | 27.59%  |
| 161-240       | 7         | 12.07%  |
| 51-100        | 4         | 6.9%    |
| More than 240 | 3         | 5.17%   |
| 1-50          | 3         | 5.17%   |
| Unknown       | 1         | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 44        | 83.02%  |
| 2     | 8         | 15.09%  |
| 0     | 1         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 29        | 36.71%  |
| Intel                 | 26        | 32.91%  |
| Qualcomm Atheros      | 10        | 12.66%  |
| Broadcom              | 6         | 7.59%   |
| MediaTek              | 2         | 2.53%   |
| Hewlett-Packard       | 2         | 2.53%   |
| Nvidia                | 1         | 1.27%   |
| Huawei Technologies   | 1         | 1.27%   |
| Broadcom Limited      | 1         | 1.27%   |
| ASIX Electronics      | 1         | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 14        | 15.05%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 5.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 5.38%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 5.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 4.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.23%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 3.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.15%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 2.15%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.15%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.08%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 1.08%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 1.08%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 1.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.08%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.08%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.08%   |
| Intel Wireless 8260                                                     | 1         | 1.08%   |
| Intel Wireless 7265                                                     | 1         | 1.08%   |
| Intel Wireless 7260                                                     | 1         | 1.08%   |
| Intel Wireless 3165                                                     | 1         | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.08%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 1.08%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1         | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 48.08%  |
| Realtek Semiconductor | 10        | 19.23%  |
| Qualcomm Atheros      | 8         | 15.38%  |
| Broadcom              | 6         | 11.54%  |
| MediaTek              | 2         | 3.85%   |
| Hewlett-Packard       | 1         | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 5         | 9.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 7.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 5.77%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 5.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 3.85%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 3.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 3.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 3.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 3.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.92%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.92%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.92%   |
| Intel Wireless 8260                                                     | 1         | 1.92%   |
| Intel Wireless 7265                                                     | 1         | 1.92%   |
| Intel Wireless 7260                                                     | 1         | 1.92%   |
| Intel Wireless 3165                                                     | 1         | 1.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.92%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.92%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.92%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.92%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 26        | 66.67%  |
| Intel                 | 5         | 12.82%  |
| Qualcomm Atheros      | 2         | 5.13%   |
| Broadcom              | 2         | 5.13%   |
| Nvidia                | 1         | 2.56%   |
| Hewlett-Packard       | 1         | 2.56%   |
| Broadcom Limited      | 1         | 2.56%   |
| ASIX Electronics      | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 35%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 12.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 12.5%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 5%      |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.5%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 2.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.5%    |
| Nvidia MCP79 Ethernet                                             | 1         | 2.5%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.5%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.5%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.5%    |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 2.5%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 2.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 50        | 56.18%  |
| Ethernet | 38        | 42.7%   |
| Modem    | 1         | 1.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 82.69%  |
| Ethernet | 9         | 17.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 32        | 61.54%  |
| 1     | 16        | 30.77%  |
| 0     | 4         | 7.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 34        | 62.96%  |
| Yes  | 20        | 37.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 50%     |
| Realtek Semiconductor           | 5         | 11.36%  |
| Qualcomm Atheros Communications | 5         | 11.36%  |
| Broadcom                        | 3         | 6.82%   |
| Apple                           | 3         | 6.82%   |
| IMC Networks                    | 2         | 4.55%   |
| Dell                            | 2         | 4.55%   |
| Unknown                         | 1         | 2.27%   |
| Foxconn International           | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                              | 8         | 18.18%  |
| Intel Bluetooth wireless interface                 | 7         | 15.91%  |
| Realtek Bluetooth Radio                            | 4         | 9.09%   |
| Qualcomm Atheros  Bluetooth Device                 | 4         | 9.09%   |
| Intel AX200 Bluetooth                              | 3         | 6.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 4.55%   |
| Dell DW375 Bluetooth Module                        | 2         | 4.55%   |
| Apple Bluetooth Host Controller                    | 2         | 4.55%   |
| Unknown Bluetooth Device                           | 1         | 2.27%   |
| Realtek RTL8723B Bluetooth                         | 1         | 2.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 2.27%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 2.27%   |
| Intel AX210 Bluetooth                              | 1         | 2.27%   |
| IMC Networks Wireless_Device                       | 1         | 2.27%   |
| IMC Networks Bluetooth Radio                       | 1         | 2.27%   |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 2.27%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 2.27%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 2.27%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 2.27%   |
| Apple Bluetooth USB Host Controller                | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 40        | 70.18%  |
| AMD                  | 8         | 14.04%  |
| Nvidia               | 7         | 12.28%  |
| Plantronics          | 1         | 1.75%   |
| LINE TECH INDUSTRIAL | 1         | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 10.29%  |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 10.29%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 7.35%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 7.35%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 4.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 4.41%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.94%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.94%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 1.47%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.47%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.47%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.47%   |
| LINE TECH INDUSTRIAL YTL HEADSET                                           | 1         | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.47%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.47%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.47%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.47%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.47%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 31.58%  |
| SK hynix            | 9         | 23.68%  |
| Kingston            | 5         | 13.16%  |
| Unknown (ABCD)      | 2         | 5.26%   |
| Ramaxel Technology  | 2         | 5.26%   |
| Micron Technology   | 2         | 5.26%   |
| Unknown             | 1         | 2.63%   |
| Teikon              | 1         | 2.63%   |
| fef5                | 1         | 2.63%   |
| Elpida              | 1         | 2.63%   |
| 8945000080AD        | 1         | 2.63%   |
| Unknown             | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 5%      |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 5%      |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 2.5%    |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 2.5%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.5%    |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 2.5%    |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 2.5%    |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.5%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.5%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 2.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.5%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.5%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 2.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.5%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.5%    |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.5%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.5%    |
| Samsung RAM M471A1K44BM0-CRC 8192MB SODIMM DDR4 2400MT/s         | 1         | 2.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.5%    |
| Samsung RAM K4F8E304HB-MGCJ 1GB 2400MT/s                         | 1         | 2.5%    |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 2.5%    |
| Ramaxel RAM RMSA3270ME86H9F-2666 4096MB SODIMM DDR4 2667MT/s     | 1         | 2.5%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 2.5%    |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.5%    |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 2.5%    |
| Kingston RAM 9905703-008.A00G 16GB SODIMM DDR4 2667MT/s          | 1         | 2.5%    |
| Kingston RAM 9905700-084.A00G 16GB SODIMM DDR4 3200MT/s          | 1         | 2.5%    |
| Kingston RAM 9905624-059.A00G 8GB SODIMM DDR4 2667MT/s           | 1         | 2.5%    |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 2.5%    |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                            | 1         | 2.5%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 1         | 2.5%    |
| 8945000080AD RAM GKE800SO102408-2400 8GB SODIMM DDR4 2400MT/s    | 1         | 2.5%    |
| Unknown                                                          | 1         | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 18        | 58.06%  |
| DDR3    | 8         | 25.81%  |
| LPDDR4  | 4         | 12.9%   |
| Unknown | 1         | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 87.1%   |
| Row Of Chips | 2         | 6.45%   |
| Chip         | 1         | 3.23%   |
| Unknown      | 1         | 3.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 16        | 50%     |
| 4096  | 7         | 21.88%  |
| 16384 | 4         | 12.5%   |
| 32768 | 2         | 6.25%   |
| 2048  | 2         | 6.25%   |
| 1024  | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 9         | 27.27%  |
| 2667  | 6         | 18.18%  |
| 2400  | 6         | 18.18%  |
| 1600  | 5         | 15.15%  |
| 4267  | 1         | 3.03%   |
| 3266  | 1         | 3.03%   |
| 2133  | 1         | 3.03%   |
| 1334  | 1         | 3.03%   |
| 1333  | 1         | 3.03%   |
| 1067  | 1         | 3.03%   |
| 1066  | 1         | 3.03%   |

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
| Chicony Electronics                    | 11        | 26.19%  |
| IMC Networks                           | 6         | 14.29%  |
| Realtek Semiconductor                  | 4         | 9.52%   |
| Acer                                   | 4         | 9.52%   |
| Syntek                                 | 3         | 7.14%   |
| Sunplus Innovation Technology          | 3         | 7.14%   |
| Apple                                  | 3         | 7.14%   |
| Microdia                               | 2         | 4.76%   |
| Quanta                                 | 1         | 2.38%   |
| Polycom                                | 1         | 2.38%   |
| DJJHFA1BIF5595                         | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.38%   |
| Alcor Micro                            | 1         | 2.38%   |
| Unknown                                | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 3         | 7.14%   |
| Syntek Integrated Camera                                                   | 2         | 4.76%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 4.76%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 4.76%   |
| Chicony Integrated Camera                                                  | 2         | 4.76%   |
| Chicony HD Webcam                                                          | 2         | 4.76%   |
| Apple FaceTime HD Camera                                                   | 2         | 4.76%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 4.76%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 2.38%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 2.38%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.38%   |
| Sunplus HD WebCam                                                          | 1         | 2.38%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 2.38%   |
| Realtek Integrated Webcam                                                  | 1         | 2.38%   |
| Quanta USB2.0 HD UVC WebCam                                                | 1         | 2.38%   |
| Polycom Poly Studio P5 webcam                                              | 1         | 2.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 2.38%   |
| IMC Networks Integrated RGB Camera                                         | 1         | 2.38%   |
| DJJHFA1BIF5595 HP HD Camera                                                | 1         | 2.38%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 1         | 2.38%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 2.38%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 2.38%   |
| Chicony USB2.0 Camera                                                      | 1         | 2.38%   |
| Chicony HP Truevision HD camera                                            | 1         | 2.38%   |
| Chicony HP Integrated Webcam                                               | 1         | 2.38%   |
| Chicony HP HD Camera                                                       | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.38%   |
| Apple Built-in iSight                                                      | 1         | 2.38%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 2.38%   |
| Acer Integrated Camera                                                     | 1         | 2.38%   |
| Acer EasyCamera                                                            | 1         | 2.38%   |
| Unknown                                                                    | 1         | 2.38%   |

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


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device               | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 10%     |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                | 1         | 10%     |
| Shenzhen Goodix FingerPrint                       | 1         | 10%     |
| Elan ELAN:Fingerprint                             | 1         | 10%     |
| Unknown                                           | 1         | 10%     |

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
| 0     | 33        | 63.46%  |
| 1     | 12        | 23.08%  |
| 2     | 5         | 9.62%   |
| 6     | 1         | 1.92%   |
| 3     | 1         | 1.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 33.33%  |
| Net/wireless             | 4         | 14.81%  |
| Graphics card            | 4         | 14.81%  |
| Sound                    | 2         | 7.41%   |
| Communication controller | 2         | 7.41%   |
| Chipcard                 | 2         | 7.41%   |
| Camera                   | 2         | 7.41%   |
| Multimedia controller    | 1         | 3.7%    |
| Bluetooth                | 1         | 3.7%    |

