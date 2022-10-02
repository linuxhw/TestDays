Ubuntu Studio - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Studio.

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

Total: 68

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [5bfc8f0a7d](https://linux-hardware.org/?probe=5bfc8f0a7d) | Sep 30, 2022 |
| HP            | ZBook 15 G3                 | [2dc3febd4d](https://linux-hardware.org/?probe=2dc3febd4d) | Sep 24, 2022 |
| ASUSTek       | GL503VD                     | [b1d97f239e](https://linux-hardware.org/?probe=b1d97f239e) | Sep 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | [de37b9cf96](https://linux-hardware.org/?probe=de37b9cf96) | Sep 13, 2022 |
| Gigabyte      | AERO 15-X9                  | [d6d8f577e0](https://linux-hardware.org/?probe=d6d8f577e0) | Sep 12, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a23b4a8cd4](https://linux-hardware.org/?probe=a23b4a8cd4) | Aug 27, 2022 |
| HP            | G62                         | [3c4aab40ae](https://linux-hardware.org/?probe=3c4aab40ae) | Jul 20, 2022 |
| Apple         | MacBookPro11,5              | [25e69108df](https://linux-hardware.org/?probe=25e69108df) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [4ed102b3fa](https://linux-hardware.org/?probe=4ed102b3fa) | Jun 15, 2022 |
| Getac         | S400G3                      | [56cc8b4c1a](https://linux-hardware.org/?probe=56cc8b4c1a) | May 16, 2022 |
| Acer          | Aspire A114-32              | [3c048f588e](https://linux-hardware.org/?probe=3c048f588e) | Apr 12, 2022 |
| Dell          | XPS 15 9570                 | [3f8fe40793](https://linux-hardware.org/?probe=3f8fe40793) | Mar 08, 2022 |
| Dell          | Inspiron N5110              | [4206238fce](https://linux-hardware.org/?probe=4206238fce) | Mar 01, 2022 |
| HP            | Sona                        | [4fcab0b3b7](https://linux-hardware.org/?probe=4fcab0b3b7) | Feb 24, 2022 |
| HP            | Sona                        | [d0b3189e0f](https://linux-hardware.org/?probe=d0b3189e0f) | Feb 24, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Google        | Nami                        | [5f1ba9ab72](https://linux-hardware.org/?probe=5f1ba9ab72) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [feb1c1d6a2](https://linux-hardware.org/?probe=feb1c1d6a2) | Feb 10, 2022 |
| Samsung       | 305V4A/305V5A               | [5a1bf3cb9e](https://linux-hardware.org/?probe=5a1bf3cb9e) | Feb 04, 2022 |
| HP            | EliteBook 840 G3            | [fe9fed2a45](https://linux-hardware.org/?probe=fe9fed2a45) | Jan 26, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | [5ccce1fb71](https://linux-hardware.org/?probe=5ccce1fb71) | Jan 21, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | [91adda5a0e](https://linux-hardware.org/?probe=91adda5a0e) | Jan 21, 2022 |
| Clevo         | W35_37ET                    | [f8858fd0c3](https://linux-hardware.org/?probe=f8858fd0c3) | Jan 20, 2022 |
| Dell          | Inspiron 7348               | [b479441fe2](https://linux-hardware.org/?probe=b479441fe2) | Jan 15, 2022 |
| Dell          | Inspiron 3501               | [e071d4f83a](https://linux-hardware.org/?probe=e071d4f83a) | Jan 02, 2022 |
| Toshiba       | Satellite C855              | [7914ab9929](https://linux-hardware.org/?probe=7914ab9929) | Dec 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| Razer         | Blade Stealth 13 Late 20... | [22033e7185](https://linux-hardware.org/?probe=22033e7185) | Oct 05, 2021 |
| Toshiba       | Satellite L755D             | [aca989dcc4](https://linux-hardware.org/?probe=aca989dcc4) | Sep 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [7725289d30](https://linux-hardware.org/?probe=7725289d30) | Sep 17, 2021 |
| ASUSTek       | UX305FA                     | [91b4275b9b](https://linux-hardware.org/?probe=91b4275b9b) | Aug 25, 2021 |
| HUAWEI        | HLYL-WXX9                   | [35e6393ea4](https://linux-hardware.org/?probe=35e6393ea4) | Aug 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [9d8c462df3](https://linux-hardware.org/?probe=9d8c462df3) | Jul 20, 2021 |
| HP            | Pavilion dv6                | [089a39fe70](https://linux-hardware.org/?probe=089a39fe70) | Jul 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [64c8a86c5b](https://linux-hardware.org/?probe=64c8a86c5b) | Jun 19, 2021 |
| Intel Clie... | LAPBC510                    | [06421d0916](https://linux-hardware.org/?probe=06421d0916) | Jun 15, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [f88f0c3680](https://linux-hardware.org/?probe=f88f0c3680) | Jun 14, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | [749002b5ad](https://linux-hardware.org/?probe=749002b5ad) | Apr 20, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | [aec24cb317](https://linux-hardware.org/?probe=aec24cb317) | Apr 20, 2021 |
| Dell          | Precision M4500             | [8c35250407](https://linux-hardware.org/?probe=8c35250407) | Apr 17, 2021 |
| ASUSTek       | X541NA                      | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| HP            | Pavilion dv6                | [369f0a0cdb](https://linux-hardware.org/?probe=369f0a0cdb) | Mar 12, 2021 |
| Lenovo        | G50-45 80E3                 | [e4fb438978](https://linux-hardware.org/?probe=e4fb438978) | Feb 24, 2021 |
| Sony          | VGN-NS31M_W                 | [dcc1660569](https://linux-hardware.org/?probe=dcc1660569) | Feb 17, 2021 |
| ASUSTek       | U56E                        | [eba46128ee](https://linux-hardware.org/?probe=eba46128ee) | Jan 04, 2021 |
| Dell          | Inspiron 3543               | [1b1044cc21](https://linux-hardware.org/?probe=1b1044cc21) | Nov 28, 2020 |
| Dell          | Latitude E6530              | [3d606b3078](https://linux-hardware.org/?probe=3d606b3078) | Nov 09, 2020 |
| Dell          | Latitude E7250              | [d5e2f8b706](https://linux-hardware.org/?probe=d5e2f8b706) | Nov 01, 2020 |
| Acer          | ASPIRE1420P_MSFT            | [5185b46abc](https://linux-hardware.org/?probe=5185b46abc) | Oct 31, 2020 |
| Avell High... | Avell G1555 MUV / A62 MU... | [c2994bb093](https://linux-hardware.org/?probe=c2994bb093) | Sep 18, 2020 |
| Dell          | Inspiron 1520               | [e00620b124](https://linux-hardware.org/?probe=e00620b124) | Sep 06, 2020 |
| HP            | Laptop 15s-fq1xxx           | [57d3d832f5](https://linux-hardware.org/?probe=57d3d832f5) | Sep 04, 2020 |
| Dell          | Latitude E4300              | [3e0fb2e03f](https://linux-hardware.org/?probe=3e0fb2e03f) | Sep 03, 2020 |
| HP            | Compaq 8510p                | [2ea87d13f0](https://linux-hardware.org/?probe=2ea87d13f0) | Aug 26, 2020 |
| ASUSTek       | 1001P                       | [d4f13322ac](https://linux-hardware.org/?probe=d4f13322ac) | Aug 19, 2020 |
| ASUSTek       | 1001P                       | [92e2a05f2d](https://linux-hardware.org/?probe=92e2a05f2d) | Aug 13, 2020 |
| ASUSTek       | 1001P                       | [0ae5a1aab2](https://linux-hardware.org/?probe=0ae5a1aab2) | Aug 13, 2020 |
| Dell          | Inspiron 5566               | [3162979c2e](https://linux-hardware.org/?probe=3162979c2e) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a253e286bf](https://linux-hardware.org/?probe=a253e286bf) | Jul 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c2c3727c6a](https://linux-hardware.org/?probe=c2c3727c6a) | Jun 30, 2020 |
| HP            | Notebook                    | [e406d5cf9e](https://linux-hardware.org/?probe=e406d5cf9e) | Jun 02, 2020 |
| Lenovo        | ThinkPad W530 2447IG0       | [f7125d9a17](https://linux-hardware.org/?probe=f7125d9a17) | Mar 19, 2020 |
| Lenovo        | ThinkPad X230 23245S1       | [047f29b7c7](https://linux-hardware.org/?probe=047f29b7c7) | Nov 01, 2019 |
| Lenovo        | G50-45 80E3                 | [ebbf8cd8d4](https://linux-hardware.org/?probe=ebbf8cd8d4) | May 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu Studio 20.04 | 36        | 63.16%  |
| Ubuntu Studio 22.04 | 9         | 15.79%  |
| Ubuntu Studio 21.10 | 3         | 5.26%   |
| Ubuntu Studio 21.04 | 3         | 5.26%   |
| Ubuntu Studio 20.10 | 3         | 5.26%   |
| Ubuntu Studio 18.04 | 2         | 3.51%   |
| Ubuntu Studio 19.10 | 1         | 1.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 57        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-52-lowlatency     | 3         | 5.17%   |
| 5.15.0-47-lowlatency    | 3         | 5.17%   |
| 5.13.0-28-lowlatency    | 3         | 5.17%   |
| 5.8.0-55-lowlatency     | 2         | 3.45%   |
| 5.4.0-94-lowlatency     | 2         | 3.45%   |
| 5.4.0-65-lowlatency     | 2         | 3.45%   |
| 5.4.0-45-lowlatency     | 2         | 3.45%   |
| 5.4.0-42-lowlatency     | 2         | 3.45%   |
| 5.15.0-48-lowlatency    | 2         | 3.45%   |
| 5.15.0-46-lowlatency    | 2         | 3.45%   |
| 5.13.0-30-lowlatency    | 2         | 3.45%   |
| 5.11.0-34-lowlatency    | 2         | 3.45%   |
| 5.11.0-27-lowlatency    | 2         | 3.45%   |
| 5.8.0-59-lowlatency     | 1         | 1.72%   |
| 5.8.0-50-lowlatency     | 1         | 1.72%   |
| 5.8.0-44-lowlatency     | 1         | 1.72%   |
| 5.8.0-43-lowlatency     | 1         | 1.72%   |
| 5.8.0-34-generic        | 1         | 1.72%   |
| 5.8.0-29-lowlatency     | 1         | 1.72%   |
| 5.8.0-25-lowlatency     | 1         | 1.72%   |
| 5.7.6-050706-lowlatency | 1         | 1.72%   |
| 5.7.6-050706-generic    | 1         | 1.72%   |
| 5.4.0-96-lowlatency     | 1         | 1.72%   |
| 5.4.0-88-lowlatency     | 1         | 1.72%   |
| 5.4.0-52-generic        | 1         | 1.72%   |
| 5.4.0-45-generic        | 1         | 1.72%   |
| 5.4.0-34-lowlatency     | 1         | 1.72%   |
| 5.4.0-26-lowlatency     | 1         | 1.72%   |
| 5.4.0-107-lowlatency    | 1         | 1.72%   |
| 5.4.0-100-lowlatency    | 1         | 1.72%   |
| 5.3.0-19-lowlatency     | 1         | 1.72%   |
| 5.15.0-40-lowlatency    | 1         | 1.72%   |
| 5.15.0-37-lowlatency    | 1         | 1.72%   |
| 5.15.0-30-lowlatency    | 1         | 1.72%   |
| 5.13.0-30-generic       | 1         | 1.72%   |
| 5.11.0-41-lowlatency    | 1         | 1.72%   |
| 5.11.0-36-lowlatency    | 1         | 1.72%   |
| 5.11.0-25-lowlatency    | 1         | 1.72%   |
| 5.11.0-22-lowlatency    | 1         | 1.72%   |
| 5.11.0-16-lowlatency    | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 33.33%  |
| 5.15.0  | 10        | 17.54%  |
| 5.8.0   | 9         | 15.79%  |
| 5.11.0  | 9         | 15.79%  |
| 5.13.0  | 6         | 10.53%  |
| 4.15.0  | 2         | 3.51%   |
| 5.7.6   | 1         | 1.75%   |
| 5.3.0   | 1         | 1.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 33.33%  |
| 5.15    | 10        | 17.54%  |
| 5.8     | 9         | 15.79%  |
| 5.11    | 9         | 15.79%  |
| 5.13    | 6         | 10.53%  |
| 4.15    | 2         | 3.51%   |
| 5.7     | 1         | 1.75%   |
| 5.3     | 1         | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 57        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 35        | 61.4%   |
| KDE5  | 16        | 28.07%  |
| GNOME | 5         | 8.77%   |
| LXQt  | 1         | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 54        | 94.74%  |
| Wayland | 3         | 5.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 21        | 36.84%  |
| LightDM | 17        | 29.82%  |
| SDDM    | 13        | 22.81%  |
| GDM     | 5         | 8.77%   |
| LXDM    | 1         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 26        | 45.61%  |
| fr_FR   | 9         | 15.79%  |
| C       | 4         | 7.02%   |
| pt_BR   | 2         | 3.51%   |
| it_IT   | 2         | 3.51%   |
| en_CA   | 2         | 3.51%   |
| de_DE   | 2         | 3.51%   |
| Unknown | 2         | 3.51%   |
| ru_RU   | 1         | 1.75%   |
| hu_HU   | 1         | 1.75%   |
| es_NI   | 1         | 1.75%   |
| es_ES   | 1         | 1.75%   |
| es_CR   | 1         | 1.75%   |
| en_NG   | 1         | 1.75%   |
| en_IE   | 1         | 1.75%   |
| en_AG   | 1         | 1.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 37        | 64.91%  |
| BIOS | 20        | 35.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 53        | 92.98%  |
| Overlay | 4         | 7.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 40        | 70.18%  |
| MBR  | 17        | 29.82%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 85.96%  |
| Yes       | 8         | 14.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 50.88%  |
| No        | 28        | 49.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 14        | 24.56%  |
| Hewlett-Packard        | 10        | 17.54%  |
| Dell                   | 10        | 17.54%  |
| ASUSTek Computer       | 7         | 12.28%  |
| Toshiba                | 2         | 3.51%   |
| HUAWEI                 | 2         | 3.51%   |
| Acer                   | 2         | 3.51%   |
| Sony                   | 1         | 1.75%   |
| Samsung Electronics    | 1         | 1.75%   |
| Razer                  | 1         | 1.75%   |
| Intel Client Systems   | 1         | 1.75%   |
| Google                 | 1         | 1.75%   |
| Gigabyte Technology    | 1         | 1.75%   |
| Getac                  | 1         | 1.75%   |
| Clevo                  | 1         | 1.75%   |
| Avell High Performance | 1         | 1.75%   |
| Apple                  | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G50-45 80E3                       | 2         | 3.51%   |
| HP Pavilion dv6                          | 2         | 3.51%   |
| Toshiba Satellite L755D                  | 1         | 1.75%   |
| Toshiba Satellite C855                   | 1         | 1.75%   |
| Sony VGN-NS31M_W                         | 1         | 1.75%   |
| Samsung 305V4A/305V5A                    | 1         | 1.75%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 1.75%   |
| Lenovo ThinkPad X230 2325AJG             | 1         | 1.75%   |
| Lenovo ThinkPad X230 23245S1             | 1         | 1.75%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 1         | 1.75%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 1.75%   |
| Lenovo ThinkPad W530 2447IG0             | 1         | 1.75%   |
| Lenovo ThinkPad T520 4243K86             | 1         | 1.75%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.75%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 1.75%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 1.75%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 1.75%   |
| Lenovo IdeaPad 3 15ABA7 82RN             | 1         | 1.75%   |
| Lenovo IdeaPad 3 14ARE05 81W3            | 1         | 1.75%   |
| Intel Client Systems LAPBC510            | 1         | 1.75%   |
| HUAWEI KLVL-WXXW                         | 1         | 1.75%   |
| HUAWEI HLYL-WXX9                         | 1         | 1.75%   |
| HP ZBook 15 G3                           | 1         | 1.75%   |
| HP Stream Laptop 14-cb0XX                | 1         | 1.75%   |
| HP Sona                                  | 1         | 1.75%   |
| HP OMEN by Laptop 15-ce0xx               | 1         | 1.75%   |
| HP Notebook                              | 1         | 1.75%   |
| HP Laptop 15s-fq1xxx                     | 1         | 1.75%   |
| HP EliteBook 840 G3                      | 1         | 1.75%   |
| HP Compaq 8510p                          | 1         | 1.75%   |
| Google Nami                              | 1         | 1.75%   |
| Gigabyte AERO 15-X9                      | 1         | 1.75%   |
| Getac S400G3                             | 1         | 1.75%   |
| Dell XPS 15 9570                         | 1         | 1.75%   |
| Dell Precision M4500                     | 1         | 1.75%   |
| Dell Latitude E7250                      | 1         | 1.75%   |
| Dell Latitude E6530                      | 1         | 1.75%   |
| Dell Latitude E4300                      | 1         | 1.75%   |
| Dell Inspiron N5110                      | 1         | 1.75%   |
| Dell Inspiron 7348                       | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 6         | 10.53%  |
| Lenovo IdeaPad                | 5         | 8.77%   |
| Dell Inspiron                 | 5         | 8.77%   |
| Dell Latitude                 | 3         | 5.26%   |
| Toshiba Satellite             | 2         | 3.51%   |
| Lenovo G50-45                 | 2         | 3.51%   |
| HP Pavilion                   | 2         | 3.51%   |
| Sony VGN-NS31M                | 1         | 1.75%   |
| Samsung 305V4A                | 1         | 1.75%   |
| Razer Blade                   | 1         | 1.75%   |
| Lenovo Legion                 | 1         | 1.75%   |
| Intel Client Systems LAPBC510 | 1         | 1.75%   |
| HUAWEI KLVL-WXXW              | 1         | 1.75%   |
| HUAWEI HLYL-WXX9              | 1         | 1.75%   |
| HP ZBook                      | 1         | 1.75%   |
| HP Stream                     | 1         | 1.75%   |
| HP Sona                       | 1         | 1.75%   |
| HP OMEN                       | 1         | 1.75%   |
| HP Notebook                   | 1         | 1.75%   |
| HP Laptop                     | 1         | 1.75%   |
| HP EliteBook                  | 1         | 1.75%   |
| HP Compaq                     | 1         | 1.75%   |
| Google Nami                   | 1         | 1.75%   |
| Gigabyte AERO                 | 1         | 1.75%   |
| Getac S400G3                  | 1         | 1.75%   |
| Dell XPS                      | 1         | 1.75%   |
| Dell Precision                | 1         | 1.75%   |
| Clevo W35                     | 1         | 1.75%   |
| Avell High Performance Avell  | 1         | 1.75%   |
| ASUS X541NA                   | 1         | 1.75%   |
| ASUS VivoBook                 | 1         | 1.75%   |
| ASUS UX305FA                  | 1         | 1.75%   |
| ASUS U56E                     | 1         | 1.75%   |
| ASUS ROG                      | 1         | 1.75%   |
| ASUS GL503VD                  | 1         | 1.75%   |
| ASUS ASUS                     | 1         | 1.75%   |
| Apple MacBookPro11            | 1         | 1.75%   |
| Acer ASPIRE1420P              | 1         | 1.75%   |
| Acer Aspire                   | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 14.04%  |
| 2014 | 7         | 12.28%  |
| 2012 | 6         | 10.53%  |
| 2019 | 5         | 8.77%   |
| 2011 | 5         | 8.77%   |
| 2021 | 4         | 7.02%   |
| 2018 | 4         | 7.02%   |
| 2017 | 4         | 7.02%   |
| 2016 | 4         | 7.02%   |
| 2008 | 3         | 5.26%   |
| 2010 | 2         | 3.51%   |
| 2007 | 2         | 3.51%   |
| 2022 | 1         | 1.75%   |
| 2015 | 1         | 1.75%   |
| 2009 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 57        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 50        | 87.72%  |
| Enabled  | 7         | 12.28%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 55        | 96.49%  |
| Yes  | 2         | 3.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 25        | 43.86%  |
| 16.01-24.0 | 10        | 17.54%  |
| 3.01-4.0   | 7         | 12.28%  |
| 8.01-16.0  | 7         | 12.28%  |
| 32.01-64.0 | 3         | 5.26%   |
| 24.01-32.0 | 2         | 3.51%   |
| 2.01-3.0   | 2         | 3.51%   |
| 1.01-2.0   | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 24        | 41.38%  |
| 2.01-3.0  | 13        | 22.41%  |
| 3.01-4.0  | 10        | 17.24%  |
| 4.01-8.0  | 8         | 13.79%  |
| 8.01-16.0 | 2         | 3.45%   |
| 0.51-1.0  | 1         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 41        | 71.93%  |
| 2      | 14        | 24.56%  |
| 0      | 2         | 3.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 70.18%  |
| Yes       | 17        | 29.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 78.95%  |
| No        | 12        | 21.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 98.25%  |
| No        | 1         | 1.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 77.19%  |
| No        | 13        | 22.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| USA        | 12        | 21.05%  |
| France     | 9         | 15.79%  |
| Germany    | 6         | 10.53%  |
| Canada     | 4         | 7.02%   |
| Russia     | 3         | 5.26%   |
| Italy      | 3         | 5.26%   |
| UK         | 2         | 3.51%   |
| Costa Rica | 2         | 3.51%   |
| Brazil     | 2         | 3.51%   |
| Yemen      | 1         | 1.75%   |
| Turkey     | 1         | 1.75%   |
| Taiwan     | 1         | 1.75%   |
| Spain      | 1         | 1.75%   |
| Poland     | 1         | 1.75%   |
| Norway     | 1         | 1.75%   |
| Nigeria    | 1         | 1.75%   |
| Nicaragua  | 1         | 1.75%   |
| Mexico     | 1         | 1.75%   |
| Indonesia  | 1         | 1.75%   |
| Hungary    | 1         | 1.75%   |
| Finland    | 1         | 1.75%   |
| Bulgaria   | 1         | 1.75%   |
| Austria    | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montreal               | 2         | 3.51%   |
| Denver                 | 2         | 3.51%   |
| Béziers               | 2         | 3.51%   |
| Yekaterinburg          | 1         | 1.75%   |
| Wroclaw                | 1         | 1.75%   |
| Woonsocket             | 1         | 1.75%   |
| Woodland Park          | 1         | 1.75%   |
| Vienna                 | 1         | 1.75%   |
| Velleron               | 1         | 1.75%   |
| Turin                  | 1         | 1.75%   |
| Taipei                 | 1         | 1.75%   |
| Sunderland             | 1         | 1.75%   |
| Stuttgart              | 1         | 1.75%   |
| Stabekk                | 1         | 1.75%   |
| Sofia                  | 1         | 1.75%   |
| Sleman                 | 1         | 1.75%   |
| Seropedica             | 1         | 1.75%   |
| Sanaa                  | 1         | 1.75%   |
| San Juan               | 1         | 1.75%   |
| Samara                 | 1         | 1.75%   |
| Rio de Janeiro         | 1         | 1.75%   |
| Ragusa                 | 1         | 1.75%   |
| Portland               | 1         | 1.75%   |
| Port Harcourt          | 1         | 1.75%   |
| Phoenix                | 1         | 1.75%   |
| Nudlingen              | 1         | 1.75%   |
| Moscow                 | 1         | 1.75%   |
| Mississauga            | 1         | 1.75%   |
| Mexico City            | 1         | 1.75%   |
| Managua                | 1         | 1.75%   |
| Madrid                 | 1         | 1.75%   |
| Madison                | 1         | 1.75%   |
| Ludwigsburg            | 1         | 1.75%   |
| Lindsay                | 1         | 1.75%   |
| Lille                  | 1         | 1.75%   |
| Kirkland               | 1         | 1.75%   |
| Istanbul               | 1         | 1.75%   |
| Illkirch-Graffenstaden | 1         | 1.75%   |
| Helsinki               | 1         | 1.75%   |
| Hamburg                | 1         | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 12     | 18.18%  |
| WDC                 | 8         | 8      | 12.12%  |
| SanDisk             | 7         | 7      | 10.61%  |
| Toshiba             | 5         | 5      | 7.58%   |
| Unknown             | 4         | 4      | 6.06%   |
| Intel               | 4         | 5      | 6.06%   |
| SK hynix            | 3         | 4      | 4.55%   |
| Seagate             | 3         | 3      | 4.55%   |
| Kingston            | 3         | 3      | 4.55%   |
| Micron Technology   | 2         | 2      | 3.03%   |
| Hitachi             | 2         | 2      | 3.03%   |
| Union Memory        | 1         | 1      | 1.52%   |
| UMIS                | 1         | 1      | 1.52%   |
| Team                | 1         | 1      | 1.52%   |
| Phison              | 1         | 1      | 1.52%   |
| KIOXIA              | 1         | 1      | 1.52%   |
| KingSpec            | 1         | 1      | 1.52%   |
| JMicron Technology  | 1         | 1      | 1.52%   |
| Inateck             | 1         | 1      | 1.52%   |
| HGST                | 1         | 1      | 1.52%   |
| Fujitsu             | 1         | 1      | 1.52%   |
| Crucial             | 1         | 1      | 1.52%   |
| BHT                 | 1         | 1      | 1.52%   |
| ASMT                | 1         | 1      | 1.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 2.99%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 2.99%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 2.99%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 2.99%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 2.99%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 1.49%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 1.49%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 1.49%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 1.49%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 1.49%   |
| WDC WD10JPVT-75A1YT0 1TB                  | 1         | 1.49%   |
| Unknown MMC Card  4GB                     | 1         | 1.49%   |
| Unknown MMC Card  16GB                    | 1         | 1.49%   |
| Unknown DA4128  128GB                     | 1         | 1.49%   |
| Unknown 032G34  32GB                      | 1         | 1.49%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB   | 1         | 1.49%   |
| UMIS RPJTJ256MEE1OWX 256GB                | 1         | 1.49%   |
| Toshiba TR150 240GB SSD                   | 1         | 1.49%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1.49%   |
| Toshiba MK1637GSX 160GB                   | 1         | 1.49%   |
| Team TM8FP4001T 1TB                       | 1         | 1.49%   |
| SK hynix SKHynix_HFS256GD9TNI-L2A0B 256GB | 1         | 1.49%   |
| Seagate ST9320320AS 320GB                 | 1         | 1.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 1.49%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.49%   |
| SanDisk SSD PLUS 240GB                    | 1         | 1.49%   |
| SanDisk SD9SN8W128G1002 128GB SSD         | 1         | 1.49%   |
| SanDisk SD8SN8U256G1002 256GB SSD         | 1         | 1.49%   |
| SanDisk SD7SN3Q128G1002 128GB SSD         | 1         | 1.49%   |
| SanDisk Extreme SSD 500GB                 | 1         | 1.49%   |
| SanDisk DF4064  64GB                      | 1         | 1.49%   |
| SanDisk DF4032  32GB                      | 1         | 1.49%   |
| Samsung SSD PM851 mSATA 256GB             | 1         | 1.49%   |
| Samsung SSD 970 PRO 1TB                   | 1         | 1.49%   |
| Samsung SSD 960 PRO 512GB                 | 1         | 1.49%   |
| Samsung SSD 870 EVO 1TB                   | 1         | 1.49%   |
| Samsung SSD 860 EVO 500GB                 | 1         | 1.49%   |
| Samsung PM981 NVMe 1024GB                 | 1         | 1.49%   |
| Samsung MZVLB512HBJQ-00000 512GB          | 1         | 1.49%   |
| Samsung MZ7TY256HDHP-000L7 256GB SSD      | 1         | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 25%     |
| Toshiba             | 4         | 4      | 20%     |
| Seagate             | 3         | 3      | 15%     |
| Samsung Electronics | 2         | 2      | 10%     |
| Hitachi             | 2         | 2      | 10%     |
| Inateck             | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |
| Fujitsu             | 1         | 1      | 5%      |
| ASMT                | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 31.58%  |
| SanDisk             | 5         | 5      | 26.32%  |
| Kingston            | 2         | 2      | 10.53%  |
| Toshiba             | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| KingSpec            | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| Crucial             | 1         | 1      | 5.26%   |
| BHT                 | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 20        | 23     | 32.26%  |
| HDD  | 20        | 20     | 32.26%  |
| SSD  | 17        | 19     | 27.42%  |
| MMC  | 5         | 6      | 8.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 36     | 54.1%   |
| NVMe | 19        | 22     | 31.15%  |
| MMC  | 5         | 6      | 8.2%    |
| SAS  | 4         | 4      | 6.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 32     | 81.08%  |
| 0.51-1.0   | 6         | 6      | 16.22%  |
| 3.01-4.0   | 1         | 1      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 18        | 31.58%  |
| 251-500    | 13        | 22.81%  |
| 501-1000   | 7         | 12.28%  |
| 51-100     | 7         | 12.28%  |
| 21-50      | 6         | 10.53%  |
| 1-20       | 4         | 7.02%   |
| 2001-3000  | 1         | 1.75%   |
| 1001-2000  | 1         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 26        | 44.83%  |
| 21-50     | 9         | 15.52%  |
| 101-250   | 9         | 15.52%  |
| 51-100    | 6         | 10.34%  |
| 251-500   | 3         | 5.17%   |
| 501-1000  | 3         | 5.17%   |
| 1001-2000 | 2         | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 6.67%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 6.67%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 6.67%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 6.67%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 6.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 6.67%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 6.67%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 6.67%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 6.67%   |
| KingSpec P3-256 256GB                               | 1         | 1      | 6.67%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 6.67%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 26.67%  |
| Seagate             | 3         | 3      | 20%     |
| Samsung Electronics | 3         | 3      | 20%     |
| Toshiba             | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| KingSpec            | 1         | 1      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 36.36%  |
| Seagate             | 3         | 3      | 27.27%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| Toshiba             | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 73.33%  |
| SSD  | 4         | 4      | 26.67%  |

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
| Works    | 38        | 44     | 62.3%   |
| Malfunc  | 15        | 15     | 24.59%  |
| Detected | 8         | 9      | 13.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 39        | 58.21%  |
| AMD                         | 11        | 16.42%  |
| Samsung Electronics         | 4         | 5.97%   |
| SK hynix                    | 3         | 4.48%   |
| SanDisk                     | 3         | 4.48%   |
| Union Memory (Shenzhen)     | 2         | 2.99%   |
| Phison Electronics          | 2         | 2.99%   |
| Micron Technology           | 1         | 1.49%   |
| KIOXIA                      | 1         | 1.49%   |
| Kingston Technology Company | 1         | 1.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 13.89%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 6.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 6.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 5.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 4.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 4.17%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 2.78%   |
| SK hynix BC511                                                                 | 2         | 2.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.78%   |
| Intel Non-Volatile memory controller                                           | 2         | 2.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.78%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.39%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.39%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.39%   |
| Micron Non-Volatile memory controller                                          | 1         | 1.39%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.39%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.39%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.39%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.39%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.39%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                    | 1         | 1.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.39%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.39%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.39%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 40        | 58.82%  |
| NVMe | 19        | 27.94%  |
| RAID | 6         | 8.82%   |
| IDE  | 3         | 4.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 77.19%  |
| AMD    | 13        | 22.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 5.26%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 5.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 3.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 3.51%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 1.75%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 1.75%   |
| Intel Genuine CPU U2300 @ 1.20GHz       | 1         | 1.75%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.75%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 1.75%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.75%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.75%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.75%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz      | 1         | 1.75%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 1.75%   |
| Intel Core i7-3940XM CPU @ 3.00GHz      | 1         | 1.75%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 1.75%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 1         | 1.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 1         | 1.75%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 1         | 1.75%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 1         | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.75%   |
| Intel Core i5-4310M CPU @ 2.70GHz       | 1         | 1.75%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 1.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.75%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 1         | 1.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 1         | 1.75%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 1         | 1.75%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 1         | 1.75%   |
| Intel Core i3-8130U CPU @ 2.20GHz       | 1         | 1.75%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 1         | 1.75%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz    | 1         | 1.75%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz    | 1         | 1.75%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz    | 1         | 1.75%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 1         | 1.75%   |
| Intel Celeron CPU N3450 @ 1.10GHz       | 1         | 1.75%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 1         | 1.75%   |
| Intel Celeron CPU 847 @ 1.10GHz         | 1         | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 16        | 28.07%  |
| Intel Core i5      | 13        | 22.81%  |
| Intel Celeron      | 4         | 7.02%   |
| AMD Ryzen 5        | 4         | 7.02%   |
| Other              | 3         | 5.26%   |
| Intel Core 2 Duo   | 3         | 5.26%   |
| AMD Ryzen 7        | 3         | 5.26%   |
| Intel Core i3      | 2         | 3.51%   |
| Intel Pentium Dual | 1         | 1.75%   |
| Intel Genuine      | 1         | 1.75%   |
| Intel Core i9      | 1         | 1.75%   |
| AMD Ryzen 3        | 1         | 1.75%   |
| AMD E2             | 1         | 1.75%   |
| AMD E1             | 1         | 1.75%   |
| AMD E              | 1         | 1.75%   |
| AMD A6             | 1         | 1.75%   |
| AMD A4             | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 28        | 49.12%  |
| 4      | 19        | 33.33%  |
| 6      | 7         | 12.28%  |
| 8      | 3         | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 39        | 68.42%  |
| 1      | 18        | 31.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 6         | 10.53%  |
| 0x306a9    | 4         | 7.02%   |
| 0x08600104 | 4         | 7.02%   |
| Unknown    | 4         | 7.02%   |
| 0x906ea    | 3         | 5.26%   |
| 0x806ea    | 3         | 5.26%   |
| 0x306d4    | 3         | 5.26%   |
| 0x906e9    | 2         | 3.51%   |
| 0x806c1    | 2         | 3.51%   |
| 0x706e5    | 2         | 3.51%   |
| 0x6fd      | 2         | 3.51%   |
| 0x406e3    | 2         | 3.51%   |
| 0x07030105 | 2         | 3.51%   |
| 0xa0652    | 1         | 1.75%   |
| 0x706a1    | 1         | 1.75%   |
| 0x6fb      | 1         | 1.75%   |
| 0x506e3    | 1         | 1.75%   |
| 0x506c9    | 1         | 1.75%   |
| 0x406c4    | 1         | 1.75%   |
| 0x40661    | 1         | 1.75%   |
| 0x40651    | 1         | 1.75%   |
| 0x306c3    | 1         | 1.75%   |
| 0x106e5    | 1         | 1.75%   |
| 0x1067a    | 1         | 1.75%   |
| 0x0a50000c | 1         | 1.75%   |
| 0x08608102 | 1         | 1.75%   |
| 0x08600106 | 1         | 1.75%   |
| 0x08600103 | 1         | 1.75%   |
| 0x07030104 | 1         | 1.75%   |
| 0x05000029 | 1         | 1.75%   |
| 0x03000027 | 1         | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 15.79%  |
| Zen 2         | 6         | 10.53%  |
| SandyBridge   | 6         | 10.53%  |
| IvyBridge     | 4         | 7.02%   |
| Broadwell     | 4         | 7.02%   |
| Skylake       | 3         | 5.26%   |
| Puma          | 3         | 5.26%   |
| Haswell       | 3         | 5.26%   |
| Core          | 3         | 5.26%   |
| TigerLake     | 2         | 3.51%   |
| Penryn        | 2         | 3.51%   |
| IceLake       | 2         | 3.51%   |
| Zen 3         | 1         | 1.75%   |
| Westmere      | 1         | 1.75%   |
| Silvermont    | 1         | 1.75%   |
| Nehalem       | 1         | 1.75%   |
| K10 Llano     | 1         | 1.75%   |
| Goldmont plus | 1         | 1.75%   |
| Goldmont      | 1         | 1.75%   |
| CometLake     | 1         | 1.75%   |
| Bobcat        | 1         | 1.75%   |
| Unknown       | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 54.17%  |
| AMD    | 17        | 23.61%  |
| Nvidia | 16        | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 8.11%   |
| AMD Renoir                                                                               | 6         | 8.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 5.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 5.41%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.05%   |
| Intel HD Graphics 5500                                                                   | 3         | 4.05%   |
| Nvidia TU117M                                                                            | 2         | 2.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 2.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.35%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 1.35%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.35%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 1.35%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 1.35%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 1.35%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.35%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 1.35%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.35%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.35%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.35%   |
| Intel HD Graphics 630                                                                    | 1         | 1.35%   |
| Intel HD Graphics 5300                                                                   | 1         | 1.35%   |
| Intel HD Graphics 530                                                                    | 1         | 1.35%   |
| Intel HD Graphics 500                                                                    | 1         | 1.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.35%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.35%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.35%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 1.35%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.35%   |
| AMD Sumo [Radeon HD 6480G]                                                               | 1         | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 47.37%  |
| 1 x AMD        | 12        | 21.05%  |
| Intel + Nvidia | 11        | 19.3%   |
| AMD + Nvidia   | 3         | 5.26%   |
| 1 x Nvidia     | 2         | 3.51%   |
| 2 x AMD        | 1         | 1.75%   |
| Intel + AMD    | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 52        | 91.23%  |
| Proprietary | 5         | 8.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 57.89%  |
| 0.01-0.5   | 8         | 14.04%  |
| 0.51-1.0   | 7         | 12.28%  |
| 1.01-2.0   | 4         | 7.02%   |
| 3.01-4.0   | 3         | 5.26%   |
| 5.01-6.0   | 2         | 3.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 13        | 20%     |
| AU Optronics            | 13        | 20%     |
| BOE                     | 9         | 13.85%  |
| Samsung Electronics     | 8         | 12.31%  |
| Chimei Innolux          | 6         | 9.23%   |
| Sharp                   | 2         | 3.08%   |
| Lenovo                  | 2         | 3.08%   |
| LG Philips              | 1         | 1.54%   |
| Iiyama                  | 1         | 1.54%   |
| Hewlett-Packard         | 1         | 1.54%   |
| Hannspree               | 1         | 1.54%   |
| Dell                    | 1         | 1.54%   |
| CPT                     | 1         | 1.54%   |
| Chi Mei Optoelectronics | 1         | 1.54%   |
| BenQ                    | 1         | 1.54%   |
| Arnos Instruments       | 1         | 1.54%   |
| Apple                   | 1         | 1.54%   |
| Ancor Communications    | 1         | 1.54%   |
| Acer                    | 1         | 1.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 2         | 3.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 3.08%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 3.08%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 3.08%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 2         | 3.08%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                  | 1         | 1.54%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 1.54%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch      | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch     | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 310x170mm 13.9-inch     | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch     | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch    | 1         | 1.54%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch             | 1         | 1.54%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 1.54%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 1.54%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 1         | 1.54%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch              | 1         | 1.54%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 1.54%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch              | 1         | 1.54%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 1.54%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch                 | 1         | 1.54%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 1         | 1.54%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                    | 1         | 1.54%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch                | 1         | 1.54%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                     | 1         | 1.54%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                         | 1         | 1.54%   |
| CPT LCD Monitor CPT141F 1280x800 331x207mm 15.4-inch                     | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 1.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1         | 1.54%   |
| BOE LCD Monitor BOE09CC 1920x1080 344x194mm 15.5-inch                    | 1         | 1.54%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                    | 1         | 1.54%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 1         | 1.54%   |
| BOE LCD Monitor BOE08C2 1920x1080 344x194mm 15.5-inch                    | 1         | 1.54%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 1         | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 46.67%  |
| 1366x768 (WXGA)    | 18        | 30%     |
| 1600x900 (HD+)     | 4         | 6.67%   |
| 3840x2160 (4K)     | 3         | 5%      |
| 1280x800 (WXGA)    | 2         | 3.33%   |
| 2880x1800          | 1         | 1.67%   |
| 2560x1440 (QHD)    | 1         | 1.67%   |
| 2160x1440          | 1         | 1.67%   |
| 1680x1050 (WSXGA+) | 1         | 1.67%   |
| 1440x900 (WXGA+)   | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 35        | 53.85%  |
| 13     | 8         | 12.31%  |
| 14     | 6         | 9.23%   |
| 24     | 4         | 6.15%   |
| 12     | 3         | 4.62%   |
| 27     | 2         | 3.08%   |
| 21     | 2         | 3.08%   |
| 84     | 1         | 1.54%   |
| 20     | 1         | 1.54%   |
| 19     | 1         | 1.54%   |
| 18     | 1         | 1.54%   |
| 16     | 1         | 1.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 45        | 70.31%  |
| 201-300     | 7         | 10.94%  |
| 501-600     | 5         | 7.81%   |
| 401-500     | 5         | 7.81%   |
| 351-400     | 1         | 1.56%   |
| 1501-2000   | 1         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 50        | 87.72%  |
| 16/10 | 6         | 10.53%  |
| 3/2   | 1         | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 55.38%  |
| 81-90          | 11        | 16.92%  |
| 71-80          | 3         | 4.62%   |
| 61-70          | 3         | 4.62%   |
| 201-250        | 3         | 4.62%   |
| 151-200        | 3         | 4.62%   |
| 301-350        | 2         | 3.08%   |
| 251-300        | 2         | 3.08%   |
| More than 1000 | 1         | 1.54%   |
| 141-150        | 1         | 1.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 42.86%  |
| 101-120       | 19        | 30.16%  |
| 51-100        | 10        | 15.87%  |
| 161-240       | 6         | 9.52%   |
| More than 240 | 1         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 48        | 82.76%  |
| 2     | 9         | 15.52%  |
| 3     | 1         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 35        | 39.33%  |
| Realtek Semiconductor             | 30        | 33.71%  |
| Qualcomm Atheros                  | 11        | 12.36%  |
| Broadcom                          | 4         | 4.49%   |
| Ralink                            | 2         | 2.25%   |
| ASIX Electronics                  | 2         | 2.25%   |
| MediaTek                          | 1         | 1.12%   |
| Marvell Technology Group          | 1         | 1.12%   |
| Huawei Technologies               | 1         | 1.12%   |
| Ericsson Business Mobile Networks | 1         | 1.12%   |
| Broadcom Limited                  | 1         | 1.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 14.15%  |
| Intel Wireless 7265                                               | 6         | 5.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 3.77%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.83%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 2.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 2.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.89%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.89%   |
| Intel Wireless 8260                                               | 2         | 1.89%   |
| Intel Wireless 7260                                               | 2         | 1.89%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.89%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.94%   |
| Realtek Realtek Network controller                                | 1         | 0.94%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]  | 1         | 0.94%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.94%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.94%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.94%   |
| MediaTek Nokia 5.1 Plus                                           | 1         | 0.94%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.94%   |
| Intel WiFi Link 5100                                              | 1         | 0.94%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 0.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 0.94%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.94%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 58.93%  |
| Realtek Semiconductor | 10        | 17.86%  |
| Qualcomm Atheros      | 7         | 12.5%   |
| Broadcom              | 3         | 5.36%   |
| Ralink                | 2         | 3.57%   |
| Broadcom Limited      | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 6         | 10.53%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 4         | 7.02%   |
| Intel Wi-Fi 6 AX200                                              | 3         | 5.26%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 5.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 3         | 5.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 3         | 5.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 3.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 3.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 2         | 3.51%   |
| Intel Wireless 8265 / 8275                                       | 2         | 3.51%   |
| Intel Wireless 8260                                              | 2         | 3.51%   |
| Intel Wireless 7260                                              | 2         | 3.51%   |
| Intel Wi-Fi 6 AX201                                              | 2         | 3.51%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 3.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.75%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1.75%   |
| Realtek Realtek Network controller                               | 1         | 1.75%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 1         | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 1.75%   |
| Intel WiFi Link 5100                                             | 1         | 1.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 1         | 1.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 1         | 1.75%   |
| Intel Centrino Wireless-N 6150                                   | 1         | 1.75%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 1         | 1.75%   |
| Intel Centrino Wireless-N + WiMAX 6150                           | 1         | 1.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 1         | 1.75%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                      | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 46.81%  |
| Intel                    | 15        | 31.91%  |
| Qualcomm Atheros         | 5         | 10.64%  |
| ASIX Electronics         | 2         | 4.26%   |
| MediaTek                 | 1         | 2.13%   |
| Marvell Technology Group | 1         | 2.13%   |
| Broadcom                 | 1         | 2.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 31.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 10.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 10.64%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 4.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.13%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.13%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.13%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.13%   |
| MediaTek Nokia 5.1 Plus                                           | 1         | 2.13%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 2.13%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.13%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.13%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.13%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.13%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 2.13%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.13%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.13%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.13%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.13%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 2.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 54.37%  |
| Ethernet | 45        | 43.69%  |
| Modem    | 2         | 1.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 83.05%  |
| Ethernet | 10        | 16.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 41        | 71.93%  |
| 1     | 16        | 28.07%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 43        | 75.44%  |
| Yes  | 14        | 24.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 52.27%  |
| Realtek Semiconductor           | 5         | 11.36%  |
| Qualcomm Atheros Communications | 4         | 9.09%   |
| Broadcom                        | 4         | 9.09%   |
| Realtek                         | 2         | 4.55%   |
| Ralink Technology               | 2         | 4.55%   |
| Lite-On Technology              | 1         | 2.27%   |
| Hewlett-Packard                 | 1         | 2.27%   |
| Foxconn International           | 1         | 2.27%   |
| Apple                           | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 12        | 27.27%  |
| Intel AX201 Bluetooth                             | 4         | 9.09%   |
| Realtek Bluetooth Radio                           | 3         | 6.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 3         | 6.82%   |
| Intel AX200 Bluetooth                             | 3         | 6.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 3         | 6.82%   |
| Realtek Bluetooth Radio                           | 2         | 4.55%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 4.55%   |
| Realtek RTL8723B Bluetooth                        | 1         | 2.27%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 2.27%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 2.27%   |
| Ralink CSR BS8510                                 | 1         | 2.27%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 2.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 2.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 2.27%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 2.27%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 2.27%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 2.27%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 2.27%   |
| Apple Bluetooth Host Controller                   | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 44        | 56.41%  |
| AMD                        | 15        | 19.23%  |
| Nvidia                     | 12        | 15.38%  |
| Yealink Network Technology | 1         | 1.28%   |
| QinHeng Electronics        | 1         | 1.28%   |
| Mackie Designs             | 1         | 1.28%   |
| Logitech                   | 1         | 1.28%   |
| C-Media Electronics        | 1         | 1.28%   |
| BR25                       | 1         | 1.28%   |
| Behringer.......           | 1         | 1.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 7.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 6.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 6.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 5.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 4.26%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 4.26%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 4.26%   |
| AMD FCH Azalia Controller                                                                         | 4         | 4.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 3.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.19%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 3.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.13%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.13%   |
| Yealink Network Technology VoIP Phone                                                             | 1         | 1.06%   |
| QinHeng Electronics CH345 MIDI adapter                                                            | 1         | 1.06%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.06%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.06%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Mackie Designs BIG KNOB STUDIO+                                                                   | 1         | 1.06%   |
| Logitech 960 Headset                                                                              | 1         | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.06%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.06%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 1.06%   |
| BR25 UACDemoV1.0                                                                                  | 1         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 21        | 30.88%  |
| Samsung Electronics | 21        | 30.88%  |
| Micron Technology   | 8         | 11.76%  |
| Kingston            | 7         | 10.29%  |
| Unknown             | 3         | 4.41%   |
| Ramaxel Technology  | 2         | 2.94%   |
| Nanya Technology    | 2         | 2.94%   |
| Crucial             | 2         | 2.94%   |
| Transcend           | 1         | 1.47%   |
| Corsair             | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 3         | 4.05%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s         | 3         | 4.05%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 2.7%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 2.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.7%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 2.7%    |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s             | 1         | 1.35%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 1.35%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 1.35%   |
| Transcend RAM TS1GSK64W6H 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.35%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.35%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s              | 1         | 1.35%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s        | 1         | 1.35%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.35%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.35%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.35%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.35%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.35%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s    | 1         | 1.35%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM 1334MT/s            | 1         | 1.35%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 1         | 1.35%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.35%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 1.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.35%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s       | 1         | 1.35%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB DDR4 2400MT/s              | 1         | 1.35%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 1.35%   |
| Samsung RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 1         | 1.35%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s       | 1         | 1.35%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 4199MT/s             | 1         | 1.35%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.35%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.35%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.35%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s  | 1         | 1.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 27        | 45%     |
| DDR4   | 22        | 36.67%  |
| DDR2   | 4         | 6.67%   |
| SDRAM  | 3         | 5%      |
| LPDDR4 | 2         | 3.33%   |
| LPDDR3 | 2         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 83.33%  |
| Row Of Chips | 8         | 13.33%  |
| Chip         | 1         | 1.67%   |
| Unknown      | 1         | 1.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 27        | 40.3%   |
| 8192  | 20        | 29.85%  |
| 2048  | 10        | 14.93%  |
| 16384 | 7         | 10.45%  |
| 1024  | 3         | 4.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 21        | 33.87%  |
| 3200    | 9         | 14.52%  |
| 2667    | 7         | 11.29%  |
| 1334    | 7         | 11.29%  |
| 2133    | 4         | 6.45%   |
| 2400    | 3         | 4.84%   |
| 667     | 3         | 4.84%   |
| 4267    | 2         | 3.23%   |
| 4199    | 2         | 3.23%   |
| 1333    | 2         | 3.23%   |
| 1639    | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1022 | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 4200F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 27.08%  |
| IMC Networks                           | 7         | 14.58%  |
| Sunplus Innovation Technology          | 4         | 8.33%   |
| Syntek                                 | 3         | 6.25%   |
| Suyin                                  | 3         | 6.25%   |
| Realtek Semiconductor                  | 3         | 6.25%   |
| Microdia                               | 3         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.25%   |
| Quanta                                 | 2         | 4.17%   |
| Acer                                   | 2         | 4.17%   |
| ViewQuest Technologies                 | 1         | 2.08%   |
| Silicon Motion                         | 1         | 2.08%   |
| Ricoh                                  | 1         | 2.08%   |
| Philips (or NXP)                       | 1         | 2.08%   |
| Importek                               | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 3         | 6.12%   |
| Microdia Integrated_Webcam_HD                       | 3         | 6.12%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 6.12%   |
| IMC Networks Integrated Camera                      | 3         | 6.12%   |
| Chicony Integrated Camera                           | 3         | 6.12%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 4.08%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 4.08%   |
| ViewQuest Ability GABB Webcam                       | 1         | 2.04%   |
| Suyin HP Webcam                                     | 1         | 2.04%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 2.04%   |
| Suyin Asus Integrated Webcam                        | 1         | 2.04%   |
| Sunplus HD WebCam                                   | 1         | 2.04%   |
| Sunplus Dell HD Webcam                              | 1         | 2.04%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 2.04%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 2.04%   |
| Realtek VGA WebCam                                  | 1         | 2.04%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.04%   |
| Realtek HP Wide Vision HD Camera                    | 1         | 2.04%   |
| Quanta ov9734_techfront_camera                      | 1         | 2.04%   |
| Quanta HP TrueVision HD Camera                      | 1         | 2.04%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc]          | 1         | 2.04%   |
| Importek TOSHIBA Web Camera - HD                    | 1         | 2.04%   |
| IMC Networks UVC VGA Webcam                         | 1         | 2.04%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 2.04%   |
| Chicony Integrated IR Camera                        | 1         | 2.04%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 2.04%   |
| Chicony HP TrueVision HD                            | 1         | 2.04%   |
| Chicony HP HD Camera                                | 1         | 2.04%   |
| Chicony HD Webcam                                   | 1         | 2.04%   |
| Chicony HD User Facing                              | 1         | 2.04%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 2.04%   |
| Chicony 4-Port Hub                                  | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 2.04%   |
| Acer Lenovo EasyCamera                              | 1         | 2.04%   |
| Acer BisonCam, NB Pro                               | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 33.33%  |
| Shenzhen Goodix Technology | 3         | 33.33%  |
| Synaptics                  | 1         | 11.11%  |
| LighTuning Technology      | 1         | 11.11%  |
| AuthenTec                  | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device              | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader       | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor     | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner             | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader               | 1         | 11.11%  |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 11.11%  |
| AuthenTec AES2501 Fingerprint Sensor             | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 42.86%  |
| Upek        | 2         | 28.57%  |
| Lenovo      | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 28.57%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 32        | 56.14%  |
| 1     | 22        | 38.6%   |
| 2     | 2         | 3.51%   |
| 3     | 1         | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 34.62%  |
| Graphics card         | 7         | 26.92%  |
| Chipcard              | 6         | 23.08%  |
| Multimedia controller | 2         | 7.69%   |
| Net/wireless          | 1         | 3.85%   |
| Camera                | 1         | 3.85%   |

