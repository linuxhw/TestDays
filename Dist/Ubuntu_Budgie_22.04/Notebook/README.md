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

Total: 55

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-27-generic     | 7         | 14.58%  |
| 5.15.0-50-generic     | 5         | 10.42%  |
| 5.15.0-48-generic     | 5         | 10.42%  |
| 5.15.0-52-generic     | 3         | 6.25%   |
| 5.15.0-40-generic     | 3         | 6.25%   |
| 5.15.0-39-generic     | 3         | 6.25%   |
| 5.15.0-30-generic     | 3         | 6.25%   |
| 5.15.0-47-generic     | 2         | 4.17%   |
| 5.15.0-46-generic     | 2         | 4.17%   |
| 5.15.0-33-generic     | 2         | 4.17%   |
| 5.15.0-25-generic     | 2         | 4.17%   |
| 5.19.0-051900-generic | 1         | 2.08%   |
| 5.15.0-52-lowlatency  | 1         | 2.08%   |
| 5.15.0-43-generic     | 1         | 2.08%   |
| 5.15.0-41-generic     | 1         | 2.08%   |
| 5.15.0-35-generic     | 1         | 2.08%   |
| 5.15.0-18-generic     | 1         | 2.08%   |
| 5.15.0-10052-tuxedo   | 1         | 2.08%   |
| 5.15.0-10047-tuxedo   | 1         | 2.08%   |
| 5.15.0-10041-tuxedo   | 1         | 2.08%   |
| 5.13.0-35-generic     | 1         | 2.08%   |
| 5.13.0-19-generic     | 1         | 2.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 43        | 93.48%  |
| 5.13.0  | 2         | 4.35%   |
| 5.19.0  | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 43        | 93.48%  |
| 5.13    | 2         | 4.35%   |
| 5.19    | 1         | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 46        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 44        | 95.65%  |
| GNOME  | 2         | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 44        | 95.65%  |
| Wayland | 2         | 4.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 31        | 67.39%  |
| Unknown | 10        | 21.74%  |
| GDM3    | 5         | 10.87%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 15        | 32.61%  |
| fr_FR | 7         | 15.22%  |
| de_DE | 6         | 13.04%  |
| pt_BR | 4         | 8.7%    |
| hu_HU | 2         | 4.35%   |
| en_CA | 2         | 4.35%   |
| ru_RU | 1         | 2.17%   |
| it_IT | 1         | 2.17%   |
| fr_BE | 1         | 2.17%   |
| es_PE | 1         | 2.17%   |
| es_MX | 1         | 2.17%   |
| es_EC | 1         | 2.17%   |
| es_CL | 1         | 2.17%   |
| en_IE | 1         | 2.17%   |
| en_GB | 1         | 2.17%   |
| C     | 1         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 28        | 60.87%  |
| EFI  | 18        | 39.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 42        | 91.3%   |
| Overlay | 2         | 4.35%   |
| Xfs     | 1         | 2.17%   |
| Btrfs   | 1         | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 24        | 52.17%  |
| Unknown | 19        | 41.3%   |
| MBR     | 3         | 6.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 84.78%  |
| Yes       | 7         | 15.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 76.6%   |
| Yes       | 11        | 23.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 11        | 23.91%  |
| Dell                   | 7         | 15.22%  |
| Hewlett-Packard        | 5         | 10.87%  |
| ASUSTek Computer       | 5         | 10.87%  |
| TUXEDO                 | 3         | 6.52%   |
| Apple                  | 3         | 6.52%   |
| MSI                    | 2         | 4.35%   |
| Google                 | 2         | 4.35%   |
| Toshiba                | 1         | 2.17%   |
| Timi                   | 1         | 2.17%   |
| Razer                  | 1         | 2.17%   |
| Digibras               | 1         | 2.17%   |
| Chuwi                  | 1         | 2.17%   |
| AXIOO                  | 1         | 2.17%   |
| Avell High Performance | 1         | 2.17%   |
| Acer                   | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Book XUX7 Gen11                               | 1         | 2.17%   |
| TUXEDO Book BA1510                                   | 1         | 2.17%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 2.17%   |
| Toshiba Satellite A505                               | 1         | 2.17%   |
| Timi TM1604                                          | 1         | 2.17%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 2.17%   |
| MSI Modern 15 A10M                                   | 1         | 2.17%   |
| MSI GL62 6QF                                         | 1         | 2.17%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 2.17%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 2.17%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 2.17%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 2.17%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 2.17%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 2.17%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 2.17%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 2.17%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 2.17%   |
| Lenovo G500 20236                                    | 1         | 2.17%   |
| Lenovo G50-45 80E3                                   | 1         | 2.17%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 2.17%   |
| HP Pavilion g6                                       | 1         | 2.17%   |
| HP ENVY 17                                           | 1         | 2.17%   |
| HP ElitePad 1000 G2                                  | 1         | 2.17%   |
| HP EliteBook 840 G3                                  | 1         | 2.17%   |
| Google Rabbid                                        | 1         | 2.17%   |
| Google Boten                                         | 1         | 2.17%   |
| Digibras NH4CU03                                     | 1         | 2.17%   |
| Dell XPS 13 9360                                     | 1         | 2.17%   |
| Dell Vostro 15 5510                                  | 1         | 2.17%   |
| Dell Precision 5560                                  | 1         | 2.17%   |
| Dell Latitude E6410                                  | 1         | 2.17%   |
| Dell Latitude E5420                                  | 1         | 2.17%   |
| Dell Inspiron 5570                                   | 1         | 2.17%   |
| Dell Inspiron 3793                                   | 1         | 2.17%   |
| Chuwi HeroBook Pro                                   | 1         | 2.17%   |
| AXIOO Slimbook 13                                    | 1         | 2.17%   |
| Avell High Performance B.ON                          | 1         | 2.17%   |
| ASUS ZenBook UX533FD_UX533FD                         | 1         | 2.17%   |
| ASUS X205TA                                          | 1         | 2.17%   |
| ASUS VivoBook_ASUSLaptop X705MAR_X705MA              | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 5         | 10.87%  |
| Lenovo IdeaPad              | 4         | 8.7%    |
| TUXEDO Book                 | 2         | 4.35%   |
| Dell Latitude               | 2         | 4.35%   |
| Dell Inspiron               | 2         | 4.35%   |
| ASUS VivoBook               | 2         | 4.35%   |
| TUXEDO Aura                 | 1         | 2.17%   |
| Toshiba Satellite           | 1         | 2.17%   |
| Timi TM1604                 | 1         | 2.17%   |
| Razer Blade                 | 1         | 2.17%   |
| MSI Modern                  | 1         | 2.17%   |
| MSI GL62                    | 1         | 2.17%   |
| Lenovo G500                 | 1         | 2.17%   |
| Lenovo G50-45               | 1         | 2.17%   |
| HP ProBook                  | 1         | 2.17%   |
| HP Pavilion                 | 1         | 2.17%   |
| HP ENVY                     | 1         | 2.17%   |
| HP ElitePad                 | 1         | 2.17%   |
| HP EliteBook                | 1         | 2.17%   |
| Google Rabbid               | 1         | 2.17%   |
| Google Boten                | 1         | 2.17%   |
| Digibras NH4CU03            | 1         | 2.17%   |
| Dell XPS                    | 1         | 2.17%   |
| Dell Vostro                 | 1         | 2.17%   |
| Dell Precision              | 1         | 2.17%   |
| Chuwi HeroBook              | 1         | 2.17%   |
| AXIOO Slimbook              | 1         | 2.17%   |
| Avell High Performance B.ON | 1         | 2.17%   |
| ASUS ZenBook                | 1         | 2.17%   |
| ASUS X205TA                 | 1         | 2.17%   |
| ASUS T200TAC                | 1         | 2.17%   |
| Apple MacBookPro9           | 1         | 2.17%   |
| Apple MacBookPro8           | 1         | 2.17%   |
| Apple MacBookPro5           | 1         | 2.17%   |
| Acer Aspire                 | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 9         | 19.57%  |
| 2020 | 6         | 13.04%  |
| 2019 | 5         | 10.87%  |
| 2014 | 4         | 8.7%    |
| 2018 | 3         | 6.52%   |
| 2016 | 3         | 6.52%   |
| 2013 | 3         | 6.52%   |
| 2011 | 3         | 6.52%   |
| 2017 | 2         | 4.35%   |
| 2010 | 2         | 4.35%   |
| 2009 | 2         | 4.35%   |
| 2022 | 1         | 2.17%   |
| 2015 | 1         | 2.17%   |
| 2012 | 1         | 2.17%   |
| 2008 | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 46        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 44        | 95.65%  |
| Enabled  | 2         | 4.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 44        | 95.65%  |
| Yes  | 2         | 4.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 34.78%  |
| 16.01-24.0  | 12        | 26.09%  |
| 3.01-4.0    | 7         | 15.22%  |
| 8.01-16.0   | 6         | 13.04%  |
| 32.01-64.0  | 2         | 4.35%   |
| 64.01-256.0 | 2         | 4.35%   |
| 1.01-2.0    | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 18        | 39.13%  |
| 2.01-3.0   | 12        | 26.09%  |
| 4.01-8.0   | 10        | 21.74%  |
| 3.01-4.0   | 3         | 6.52%   |
| 8.01-16.0  | 2         | 4.35%   |
| 24.01-32.0 | 1         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 32        | 68.09%  |
| 2      | 13        | 27.66%  |
| 3      | 2         | 4.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 82.61%  |
| Yes       | 8         | 17.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 71.74%  |
| No        | 13        | 28.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 95.65%  |
| No        | 2         | 4.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 82.61%  |
| No        | 8         | 17.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 8         | 17.39%  |
| France             | 7         | 15.22%  |
| Germany            | 6         | 13.04%  |
| Brazil             | 4         | 8.7%    |
| Hungary            | 2         | 4.35%   |
| Canada             | 2         | 4.35%   |
| Sweden             | 1         | 2.17%   |
| Slovenia           | 1         | 2.17%   |
| Russia             | 1         | 2.17%   |
| Peru               | 1         | 2.17%   |
| Mexico             | 1         | 2.17%   |
| Italy              | 1         | 2.17%   |
| Ireland            | 1         | 2.17%   |
| Indonesia          | 1         | 2.17%   |
| Greece             | 1         | 2.17%   |
| Ghana              | 1         | 2.17%   |
| Ecuador            | 1         | 2.17%   |
| Dominican Republic | 1         | 2.17%   |
| Chile              | 1         | 2.17%   |
| Cabo Verde         | 1         | 2.17%   |
| Belgium            | 1         | 2.17%   |
| Austria            | 1         | 2.17%   |
| Algeria            | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Budapest              | 2         | 4.35%   |
| Wertheim am Main      | 1         | 2.17%   |
| Vienna                | 1         | 2.17%   |
| Victoria              | 1         | 2.17%   |
| Tarakan               | 1         | 2.17%   |
| Sunnyvale             | 1         | 2.17%   |
| St Petersburg         | 1         | 2.17%   |
| Siegen                | 1         | 2.17%   |
| Sétif                | 1         | 2.17%   |
| Seelze                | 1         | 2.17%   |
| Sao Paulo             | 1         | 2.17%   |
| Sao Bernardo do Campo | 1         | 2.17%   |
| Santo Domingo Este    | 1         | 2.17%   |
| Santiago              | 1         | 2.17%   |
| Saint-Gilles          | 1         | 2.17%   |
| Queens                | 1         | 2.17%   |
| Puebla City           | 1         | 2.17%   |
| Praia                 | 1         | 2.17%   |
| Postojna              | 1         | 2.17%   |
| Orvault               | 1         | 2.17%   |
| Nuremberg             | 1         | 2.17%   |
| Monza                 | 1         | 2.17%   |
| Mishawaka             | 1         | 2.17%   |
| Massaranduba          | 1         | 2.17%   |
| Lund                  | 1         | 2.17%   |
| Lima                  | 1         | 2.17%   |
| Lille                 | 1         | 2.17%   |
| Leominster            | 1         | 2.17%   |
| Le Mee-sur-Seine      | 1         | 2.17%   |
| Laval                 | 1         | 2.17%   |
| Kassel                | 1         | 2.17%   |
| Fontenay-sous-Bois    | 1         | 2.17%   |
| Dublin                | 1         | 2.17%   |
| DeQuincy              | 1         | 2.17%   |
| Cuenca                | 1         | 2.17%   |
| Crastes               | 1         | 2.17%   |
| Charlotte             | 1         | 2.17%   |
| Cagny                 | 1         | 2.17%   |
| Brasília             | 1         | 2.17%   |
| Berlin                | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 10        | 11     | 16.39%  |
| Unknown                        | 7         | 7      | 11.48%  |
| Crucial                        | 5         | 6      | 8.2%    |
| Toshiba                        | 4         | 4      | 6.56%   |
| SK hynix                       | 4         | 4      | 6.56%   |
| WDC                            | 3         | 4      | 4.92%   |
| Seagate                        | 3         | 3      | 4.92%   |
| Micron Technology              | 3         | 3      | 4.92%   |
| Kingston                       | 2         | 2      | 3.28%   |
| JMicron Technology             | 2         | 2      | 3.28%   |
| Intel                          | 2         | 2      | 3.28%   |
| China                          | 2         | 3      | 3.28%   |
| VISIPRO                        | 1         | 1      | 1.64%   |
| Union Memory                   | 1         | 1      | 1.64%   |
| TO Exter                       | 1         | 1      | 1.64%   |
| SPCC                           | 1         | 1      | 1.64%   |
| Solid State Storage Technology | 1         | 1      | 1.64%   |
| Realtek Semiconductor          | 1         | 1      | 1.64%   |
| OWC                            | 1         | 1      | 1.64%   |
| Netac                          | 1         | 1      | 1.64%   |
| KIOXIA                         | 1         | 1      | 1.64%   |
| Hewlett-Packard                | 1         | 1      | 1.64%   |
| Corsair                        | 1         | 2      | 1.64%   |
| Apple                          | 1         | 1      | 1.64%   |
| A-DATA Technology              | 1         | 1      | 1.64%   |
| Unknown                        | 1         | 1      | 1.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 3.23%   |
| Unknown SD64G  64GB                                 | 2         | 3.23%   |
| WDC PC SN730 NVMe 256GB                             | 1         | 1.61%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 1.61%   |
| VISIPRO SSD 256GB                                   | 1         | 1.61%   |
| Unknown SL128  128GB                                | 1         | 1.61%   |
| Unknown SA16G  16GB                                 | 1         | 1.61%   |
| Unknown NCard  4GB                                  | 1         | 1.61%   |
| Unknown MMC128  128GB                               | 1         | 1.61%   |
| Unknown MMC Card  64GB                              | 1         | 1.61%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD              | 1         | 1.61%   |
| Toshiba TR150 480GB SSD                             | 1         | 1.61%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 1.61%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                   | 1         | 1.61%   |
| Toshiba KBG30ZMT256G 256GB                          | 1         | 1.61%   |
| TO Exter nal USB 3.0 1TB                            | 1         | 1.61%   |
| SPCC Solid State Disk 120GB                         | 1         | 1.61%   |
| Solid State Storage NVMe CA6-8D1024 1024GB          | 1         | 1.61%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB           | 1         | 1.61%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB                | 1         | 1.61%   |
| SK hynix HCG8e  64GB                                | 1         | 1.61%   |
| SK hynix HBG4e  32GB                                | 1         | 1.61%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1.61%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.61%   |
| Samsung SSD 980 PRO 2TB                             | 1         | 1.61%   |
| Samsung SSD 980 500GB                               | 1         | 1.61%   |
| Samsung SSD 860 EVO M.2 500GB                       | 1         | 1.61%   |
| Samsung SSD 860 EVO M.2 250GB                       | 1         | 1.61%   |
| Samsung SSD 860 EVO 500GB                           | 1         | 1.61%   |
| Samsung SSD 850 EVO 500GB                           | 1         | 1.61%   |
| Samsung SSD 850 EVO 250GB                           | 1         | 1.61%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 1         | 1.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 1         | 1.61%   |
| Samsung HM320II 320GB                               | 1         | 1.61%   |
| Realtek NVMe SSD Drive 512GB                        | 1         | 1.61%   |
| OWC Mercury Electra 3G SSD                          | 1         | 1.61%   |
| Netac SSD 256GB                                     | 1         | 1.61%   |
| Micron MTFDDAV256TBN-1AR1ZABHA 256GB SSD            | 1         | 1.61%   |
| Micron 2300 NVMe 512GB                              | 1         | 1.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 50%     |
| WDC                 | 2         | 2      | 33.33%  |
| Samsung Electronics | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 20%     |
| Crucial             | 5         | 6      | 20%     |
| Micron Technology   | 2         | 2      | 8%      |
| China               | 2         | 3      | 8%      |
| VISIPRO             | 1         | 1      | 4%      |
| Union Memory        | 1         | 1      | 4%      |
| Toshiba             | 1         | 1      | 4%      |
| TO Exter            | 1         | 1      | 4%      |
| SPCC                | 1         | 1      | 4%      |
| OWC                 | 1         | 1      | 4%      |
| Netac               | 1         | 1      | 4%      |
| Intel               | 1         | 1      | 4%      |
| Hewlett-Packard     | 1         | 1      | 4%      |
| Corsair             | 1         | 2      | 4%      |
| Apple               | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 22        | 28     | 40%     |
| NVMe    | 18        | 21     | 32.73%  |
| MMC     | 8         | 10     | 14.55%  |
| HDD     | 6         | 6      | 10.91%  |
| Unknown | 1         | 1      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 33     | 47.17%  |
| NVMe | 18        | 20     | 33.96%  |
| MMC  | 8         | 10     | 15.09%  |
| SAS  | 2         | 3      | 3.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 26     | 73.33%  |
| 0.51-1.0   | 5         | 5      | 16.67%  |
| 1.01-2.0   | 3         | 3      | 10%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 36.96%  |
| 251-500        | 14        | 30.43%  |
| 51-100         | 6         | 13.04%  |
| 501-1000       | 3         | 6.52%   |
| 21-50          | 2         | 4.35%   |
| 1001-2000      | 2         | 4.35%   |
| More than 3000 | 1         | 2.17%   |
| 1-20           | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 14        | 30.43%  |
| 21-50     | 12        | 26.09%  |
| 51-100    | 8         | 17.39%  |
| 101-250   | 7         | 15.22%  |
| 251-500   | 3         | 6.52%   |
| 1001-2000 | 1         | 2.17%   |
| 501-1000  | 1         | 2.17%   |

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
| Detected | 29        | 39     | 59.18%  |
| Works    | 20        | 27     | 40.82%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 27        | 54%     |
| Samsung Electronics            | 4         | 8%      |
| AMD                            | 4         | 8%      |
| Toshiba America Info Systems   | 2         | 4%      |
| SK hynix                       | 2         | 4%      |
| SanDisk                        | 2         | 4%      |
| KIOXIA                         | 2         | 4%      |
| Kingston Technology Company    | 2         | 4%      |
| Solid State Storage Technology | 1         | 2%      |
| Realtek Semiconductor          | 1         | 2%      |
| Nvidia                         | 1         | 2%      |
| Micron Technology              | 1         | 2%      |
| ADATA Technology               | 1         | 2%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 7.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 5.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 5.77%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 3.85%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 3.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 3.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 3.85%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.92%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 1.92%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 1.92%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 1.92%   |
| SK hynix Gold P31 SSD                                                            | 1         | 1.92%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 1.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.92%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.92%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 1.92%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.92%   |
| Micron Non-Volatile memory controller                                            | 1         | 1.92%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 1.92%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.92%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.92%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 1.92%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 1.92%   |
| ADATA Non-Volatile memory controller                                             | 1         | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 29        | 58%     |
| NVMe | 18        | 36%     |
| RAID | 2         | 4%      |
| IDE  | 1         | 2%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 40        | 86.96%  |
| AMD    | 6         | 13.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 6.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 4.35%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 4.35%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 4.35%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 4.35%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 2.17%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 2.17%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 2.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.17%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 2.17%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 2.17%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 2.17%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 2.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.17%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 2.17%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 2.17%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 2.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 2.17%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 2.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.17%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 2.17%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.17%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 2.17%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 2.17%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 1         | 2.17%   |
| Intel Celeron N4500 @ 1.10GHz                 | 1         | 2.17%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 2.17%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 1         | 2.17%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 1         | 2.17%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 2.17%   |
| Intel 11th Gen Core i5-11320H @ 3.20GHz       | 1         | 2.17%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 2.17%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 14        | 30.43%  |
| Other                | 6         | 13.04%  |
| Intel Core i7        | 6         | 13.04%  |
| Intel Celeron        | 4         | 8.7%    |
| Intel Atom           | 3         | 6.52%   |
| AMD Ryzen 5          | 3         | 6.52%   |
| Intel Core i3        | 2         | 4.35%   |
| Intel Core 2 Duo     | 2         | 4.35%   |
| AMD Ryzen 7          | 2         | 4.35%   |
| Intel Pentium Silver | 1         | 2.17%   |
| Intel Pentium        | 1         | 2.17%   |
| Intel Core i9        | 1         | 2.17%   |
| AMD A8               | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 21        | 45.65%  |
| 2      | 19        | 41.3%   |
| 8      | 4         | 8.7%    |
| 10     | 1         | 2.17%   |
| 6      | 1         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 46        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 69.57%  |
| 1      | 14        | 30.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 52.17%  |
| 0x206a7    | 3         | 6.52%   |
| 0x806c1    | 2         | 4.35%   |
| 0x706a8    | 2         | 4.35%   |
| 0x08600106 | 2         | 4.35%   |
| 0x08108102 | 2         | 4.35%   |
| 0x806ec    | 1         | 2.17%   |
| 0x806eb    | 1         | 2.17%   |
| 0x806d1    | 1         | 2.17%   |
| 0x506c9    | 1         | 2.17%   |
| 0x40651    | 1         | 2.17%   |
| 0x306d4    | 1         | 2.17%   |
| 0x30678    | 1         | 2.17%   |
| 0x20655    | 1         | 2.17%   |
| 0x106e5    | 1         | 2.17%   |
| 0x0a50000c | 1         | 2.17%   |
| 0x07030104 | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 19.57%  |
| TigerLake     | 4         | 8.7%    |
| Silvermont    | 3         | 6.52%   |
| SandyBridge   | 3         | 6.52%   |
| IvyBridge     | 3         | 6.52%   |
| Goldmont plus | 3         | 6.52%   |
| Zen+          | 2         | 4.35%   |
| Zen 2         | 2         | 4.35%   |
| Skylake       | 2         | 4.35%   |
| Penryn        | 2         | 4.35%   |
| IceLake       | 2         | 4.35%   |
| Haswell       | 2         | 4.35%   |
| Unknown       | 2         | 4.35%   |
| Zen 3         | 1         | 2.17%   |
| Westmere      | 1         | 2.17%   |
| Puma          | 1         | 2.17%   |
| Nehalem       | 1         | 2.17%   |
| Goldmont      | 1         | 2.17%   |
| CometLake     | 1         | 2.17%   |
| Broadwell     | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 64.91%  |
| Nvidia | 12        | 21.05%  |
| AMD    | 8         | 14.04%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 4         | 6.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 4         | 6.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 3         | 5.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 5.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 5.17%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 3.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 3.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 3.45%   |
| AMD Renoir                                                                            | 2         | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.45%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                                | 1         | 1.72%   |
| Nvidia GT218M [GeForce 310M]                                                          | 1         | 1.72%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 1.72%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.72%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 1.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.72%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 1.72%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 1.72%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                    | 1         | 1.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 1.72%   |
| Nvidia C79 [GeForce 9400M]                                                            | 1         | 1.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 1         | 1.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.72%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 1.72%   |
| Intel Iris Plus Graphics G7                                                           | 1         | 1.72%   |
| Intel HD Graphics 620                                                                 | 1         | 1.72%   |
| Intel HD Graphics 5500                                                                | 1         | 1.72%   |
| Intel HD Graphics 530                                                                 | 1         | 1.72%   |
| Intel HD Graphics 500                                                                 | 1         | 1.72%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.72%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                         | 1         | 1.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.72%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 1         | 1.72%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 1.72%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 1         | 1.72%   |
| AMD Cezanne                                                                           | 1         | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 56.52%  |
| Intel + Nvidia | 8         | 17.39%  |
| 1 x AMD        | 4         | 8.7%    |
| 1 x Nvidia     | 3         | 6.52%   |
| Intel + AMD    | 2         | 4.35%   |
| Other          | 1         | 2.17%   |
| 2 x AMD        | 1         | 2.17%   |
| AMD + Nvidia   | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 39        | 84.78%  |
| Proprietary | 6         | 13.04%  |
| Unknown     | 1         | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 80.43%  |
| 1.01-2.0   | 4         | 8.7%    |
| 0.51-1.0   | 2         | 4.35%   |
| 0.01-0.5   | 2         | 4.35%   |
| 7.01-8.0   | 1         | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 14        | 27.45%  |
| BOE                     | 9         | 17.65%  |
| Samsung Electronics     | 5         | 9.8%    |
| AU Optronics            | 5         | 9.8%    |
| LG Display              | 4         | 7.84%   |
| Sharp                   | 3         | 5.88%   |
| Apple                   | 3         | 5.88%   |
| Goldstar                | 2         | 3.92%   |
| Unknown (AAA)           | 1         | 1.96%   |
| Philips                 | 1         | 1.96%   |
| MStar                   | 1         | 1.96%   |
| Lenovo                  | 1         | 1.96%   |
| IBM                     | 1         | 1.96%   |
| Chi Mei Optoelectronics | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 3.92%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch                 | 1         | 1.96%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                  | 1         | 1.96%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 1.96%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 1         | 1.96%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SAM0C3C 1360x768 609x347mm 27.6-inch     | 1         | 1.96%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                  | 1         | 1.96%   |
| MStar LCD TV MST9000 1360x768                                            | 1         | 1.96%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch              | 1         | 1.96%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch                 | 1         | 1.96%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                    | 1         | 1.96%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 1         | 1.96%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN13B0 2560x1600 286x178mm 13.3-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1138 1366x768 256x144mm 11.6-inch          | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.96%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 35.42%  |
| 1366x768 (WXGA)    | 14        | 29.17%  |
| 1600x900 (HD+)     | 3         | 6.25%   |
| 1280x800 (WXGA)    | 3         | 6.25%   |
| 2560x1440 (QHD)    | 2         | 4.17%   |
| 1920x1200 (WUXGA)  | 2         | 4.17%   |
| 1680x1050 (WSXGA+) | 2         | 4.17%   |
| 3840x2160 (4K)     | 1         | 2.08%   |
| 2880x1800          | 1         | 2.08%   |
| 2560x1600          | 1         | 2.08%   |
| 1440x900 (WXGA+)   | 1         | 2.08%   |
| 1360x768           | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 19        | 37.25%  |
| 13      | 11        | 21.57%  |
| 14      | 5         | 9.8%    |
| 17      | 4         | 7.84%   |
| 11      | 3         | 5.88%   |
| 40      | 2         | 3.92%   |
| 27      | 2         | 3.92%   |
| 31      | 1         | 1.96%   |
| 23      | 1         | 1.96%   |
| 21      | 1         | 1.96%   |
| 10      | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 56.86%  |
| 201-300     | 9         | 17.65%  |
| 351-400     | 5         | 9.8%    |
| 801-900     | 2         | 3.92%   |
| 501-600     | 2         | 3.92%   |
| 401-500     | 2         | 3.92%   |
| 601-700     | 1         | 1.96%   |
| Unknown     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 36        | 78.26%  |
| 16/10 | 9         | 19.57%  |
| 3/2   | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 37.25%  |
| 81-90          | 13        | 25.49%  |
| 121-130        | 4         | 7.84%   |
| 71-80          | 3         | 5.88%   |
| 51-60          | 3         | 5.88%   |
| 301-350        | 2         | 3.92%   |
| 201-250        | 2         | 3.92%   |
| 501-1000       | 2         | 3.92%   |
| 351-500        | 1         | 1.96%   |
| 41-50          | 1         | 1.96%   |
| Unknown        | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 21        | 41.18%  |
| 101-120       | 15        | 29.41%  |
| 161-240       | 6         | 11.76%  |
| 51-100        | 4         | 7.84%   |
| More than 240 | 2         | 3.92%   |
| 1-50          | 2         | 3.92%   |
| Unknown       | 1         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 38        | 82.61%  |
| 2     | 7         | 15.22%  |
| 0     | 1         | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 34.29%  |
| Intel                 | 23        | 32.86%  |
| Qualcomm Atheros      | 9         | 12.86%  |
| Broadcom              | 6         | 8.57%   |
| MediaTek              | 2         | 2.86%   |
| Hewlett-Packard       | 2         | 2.86%   |
| Nvidia                | 1         | 1.43%   |
| Huawei Technologies   | 1         | 1.43%   |
| Broadcom Limited      | 1         | 1.43%   |
| ASIX Electronics      | 1         | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 11        | 13.75%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 5%      |
| Intel Wi-Fi 6 AX201                                                     | 4         | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.75%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 3.75%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 2.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.25%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 1.25%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 1.25%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.25%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 1.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.25%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.25%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.25%   |
| Intel Wireless 8260                                                     | 1         | 1.25%   |
| Intel Wireless 7265                                                     | 1         | 1.25%   |
| Intel Wireless 7260                                                     | 1         | 1.25%   |
| Intel Wireless 3165                                                     | 1         | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.25%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.25%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 1.25%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.25%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 48.89%  |
| Realtek Semiconductor | 7         | 15.56%  |
| Qualcomm Atheros      | 7         | 15.56%  |
| Broadcom              | 6         | 13.33%  |
| MediaTek              | 2         | 4.44%   |
| Hewlett-Packard       | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 8.89%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 8.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 6.67%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 6.67%   |
| Intel Wireless 8265 / 8275                                              | 2         | 4.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 4.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 4.44%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 4.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.22%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 2.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 2.22%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 2.22%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 2.22%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 2.22%   |
| Intel Wireless 8260                                                     | 1         | 2.22%   |
| Intel Wireless 7265                                                     | 1         | 2.22%   |
| Intel Wireless 7260                                                     | 1         | 2.22%   |
| Intel Wireless 3165                                                     | 1         | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 2.22%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 2.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.22%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 2.22%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 2.22%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 61.76%  |
| Intel                 | 5         | 14.71%  |
| Qualcomm Atheros      | 2         | 5.88%   |
| Broadcom              | 2         | 5.88%   |
| Nvidia                | 1         | 2.94%   |
| Hewlett-Packard       | 1         | 2.94%   |
| Broadcom Limited      | 1         | 2.94%   |
| ASIX Electronics      | 1         | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 32.35%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 11.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 11.76%  |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 5.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.94%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 2.94%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.94%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.94%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.94%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.94%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.94%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.94%   |
| HP HP lt4120 Snapdragon X5 LTE                                    | 1         | 2.94%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 2.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 56.41%  |
| Ethernet | 33        | 42.31%  |
| Modem    | 1         | 1.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 86.96%  |
| Ethernet | 6         | 13.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 27        | 58.7%   |
| 1     | 15        | 32.61%  |
| 0     | 4         | 8.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 63.83%  |
| Yes  | 17        | 36.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 50%     |
| Qualcomm Atheros Communications | 4         | 10.53%  |
| Realtek Semiconductor           | 3         | 7.89%   |
| Broadcom                        | 3         | 7.89%   |
| Apple                           | 3         | 7.89%   |
| IMC Networks                    | 2         | 5.26%   |
| Dell                            | 2         | 5.26%   |
| Unknown                         | 1         | 2.63%   |
| Foxconn International           | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 6         | 15.79%  |
| Intel AX201 Bluetooth                              | 6         | 15.79%  |
| Qualcomm Atheros  Bluetooth Device                 | 3         | 7.89%   |
| Intel AX200 Bluetooth                              | 3         | 7.89%   |
| Realtek Bluetooth Radio                            | 2         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 5.26%   |
| Dell DW375 Bluetooth Module                        | 2         | 5.26%   |
| Apple Bluetooth Host Controller                    | 2         | 5.26%   |
| Unknown Bluetooth Device                           | 1         | 2.63%   |
| Realtek RTL8723B Bluetooth                         | 1         | 2.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 2.63%   |
| Intel AX210 Bluetooth                              | 1         | 2.63%   |
| IMC Networks Wireless_Device                       | 1         | 2.63%   |
| IMC Networks Bluetooth Radio                       | 1         | 2.63%   |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 2.63%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 2.63%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 2.63%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 2.63%   |
| Apple Bluetooth USB Host Controller                | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 36        | 76.6%   |
| AMD    | 6         | 12.77%  |
| Nvidia | 5         | 10.64%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 10.71%  |
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 8.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 7.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 5.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 5.36%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 5.36%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.57%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 3.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 3.57%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 3.57%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.79%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.79%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.79%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.79%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.79%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.79%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.79%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.79%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 9         | 28.13%  |
| Samsung Electronics | 9         | 28.13%  |
| Kingston            | 3         | 9.38%   |
| Unknown (ABCD)      | 2         | 6.25%   |
| Ramaxel Technology  | 2         | 6.25%   |
| Micron Technology   | 2         | 6.25%   |
| Unknown             | 1         | 3.13%   |
| Teikon              | 1         | 3.13%   |
| fef5                | 1         | 3.13%   |
| Elpida              | 1         | 3.13%   |
| Unknown             | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 5.88%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 2.94%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 2.94%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.94%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 2.94%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 2.94%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.94%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.94%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 2.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.94%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.94%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 2.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.94%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.94%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 2.94%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.94%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 2.94%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.94%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.94%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 2.94%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 2.94%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 2.94%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.94%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.94%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 2.94%   |
| Kingston RAM 9905624-059.A00G 8GB SODIMM DDR4 2667MT/s           | 1         | 2.94%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 2.94%   |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                            | 1         | 2.94%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 1         | 2.94%   |
| Unknown                                                          | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 14        | 51.85%  |
| DDR3    | 8         | 29.63%  |
| LPDDR4  | 4         | 14.81%  |
| Unknown | 1         | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 85.19%  |
| Row Of Chips | 2         | 7.41%   |
| Chip         | 1         | 3.7%    |
| Unknown      | 1         | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 12        | 44.44%  |
| 4096  | 9         | 33.33%  |
| 16384 | 2         | 7.41%   |
| 2048  | 2         | 7.41%   |
| 32768 | 1         | 3.7%    |
| 1024  | 1         | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 6         | 21.43%  |
| 2667  | 5         | 17.86%  |
| 2400  | 5         | 17.86%  |
| 1600  | 5         | 17.86%  |
| 4267  | 1         | 3.57%   |
| 3266  | 1         | 3.57%   |
| 2133  | 1         | 3.57%   |
| 1334  | 1         | 3.57%   |
| 1333  | 1         | 3.57%   |
| 1067  | 1         | 3.57%   |
| 1066  | 1         | 3.57%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 10        | 27.78%  |
| IMC Networks                  | 6         | 16.67%  |
| Syntek                        | 3         | 8.33%   |
| Sunplus Innovation Technology | 3         | 8.33%   |
| Realtek Semiconductor         | 3         | 8.33%   |
| Apple                         | 3         | 8.33%   |
| Acer                          | 2         | 5.56%   |
| Quanta                        | 1         | 2.78%   |
| Polycom                       | 1         | 2.78%   |
| Microdia                      | 1         | 2.78%   |
| Luxvisions Innotech Limited   | 1         | 2.78%   |
| Alcor Micro                   | 1         | 2.78%   |
| Unknown                       | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera           | 3         | 8.33%   |
| Syntek Integrated Camera                 | 2         | 5.56%   |
| Chicony Integrated Camera                | 2         | 5.56%   |
| Apple FaceTime HD Camera                 | 2         | 5.56%   |
| Syntek Lenovo EasyCamera                 | 1         | 2.78%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 2.78%   |
| Sunplus Integrated_Webcam_HD             | 1         | 2.78%   |
| Sunplus HD WebCam                        | 1         | 2.78%   |
| Realtek Lenovo EasyCamera                | 1         | 2.78%   |
| Realtek Integrated_Webcam_HD             | 1         | 2.78%   |
| Realtek Integrated Webcam                | 1         | 2.78%   |
| Quanta USB2.0 HD UVC WebCam              | 1         | 2.78%   |
| Polycom Poly Studio P5 webcam            | 1         | 2.78%   |
| Microdia Integrated Webcam HD            | 1         | 2.78%   |
| Luxvisions Innotech Limited HP HD Camera | 1         | 2.78%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 1         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 2.78%   |
| IMC Networks Integrated RGB Camera       | 1         | 2.78%   |
| Chicony XiaoMi USB 2.0 Webcam            | 1         | 2.78%   |
| Chicony USB2.0 VGA UVC WebCam            | 1         | 2.78%   |
| Chicony USB2.0 UVC WebCam                | 1         | 2.78%   |
| Chicony USB2.0 Camera                    | 1         | 2.78%   |
| Chicony HP Truevision HD camera          | 1         | 2.78%   |
| Chicony HP Integrated Webcam             | 1         | 2.78%   |
| Chicony HP HD Camera                     | 1         | 2.78%   |
| Chicony HD Webcam                        | 1         | 2.78%   |
| Apple Built-in iSight                    | 1         | 2.78%   |
| Alcor Micro USB 2.0 WebCamera            | 1         | 2.78%   |
| Acer SunplusIT Integrated Camera         | 1         | 2.78%   |
| Acer EasyCamera                          | 1         | 2.78%   |
| Unknown                                  | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 33.33%  |
| Shenzhen Goodix Technology | 3         | 33.33%  |
| Validity Sensors           | 2         | 22.22%  |
| Elan Microelectronics      | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device               | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 11.11%  |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                | 1         | 11.11%  |
| Elan ELAN:Fingerprint                             | 1         | 11.11%  |
| Unknown                                           | 1         | 11.11%  |

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
| 0     | 30        | 65.22%  |
| 1     | 11        | 23.91%  |
| 2     | 3         | 6.52%   |
| 6     | 1         | 2.17%   |
| 3     | 1         | 2.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 36.36%  |
| Net/wireless             | 3         | 13.64%  |
| Sound                    | 2         | 9.09%   |
| Graphics card            | 2         | 9.09%   |
| Chipcard                 | 2         | 9.09%   |
| Camera                   | 2         | 9.09%   |
| Multimedia controller    | 1         | 4.55%   |
| Communication controller | 1         | 4.55%   |
| Bluetooth                | 1         | 4.55%   |

