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

Total: 75

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro8,2               | [3d8320e362](https://linux-hardware.org/?probe=3d8320e362) | Dec 25, 2022 |
| Acer          | Aspire E5-573G              | [ec1e8e146a](https://linux-hardware.org/?probe=ec1e8e146a) | Dec 10, 2022 |
| Dell          | Latitude E6500              | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| Lenovo        | G70-80 80FF                 | [022ce8e2c8](https://linux-hardware.org/?probe=022ce8e2c8) | Nov 29, 2022 |
| Gigabyte      | AERO 15-X9                  | [1d490bb7d1](https://linux-hardware.org/?probe=1d490bb7d1) | Nov 11, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | [55771f0c33](https://linux-hardware.org/?probe=55771f0c33) | Oct 18, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | [7e0028c2fa](https://linux-hardware.org/?probe=7e0028c2fa) | Oct 18, 2022 |
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
| Ubuntu Studio 20.04 | 38        | 61.29%  |
| Ubuntu Studio 22.04 | 12        | 19.35%  |
| Ubuntu Studio 21.10 | 3         | 4.84%   |
| Ubuntu Studio 21.04 | 3         | 4.84%   |
| Ubuntu Studio 20.10 | 3         | 4.84%   |
| Ubuntu Studio 18.04 | 2         | 3.23%   |
| Ubuntu Studio 19.10 | 1         | 1.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 62        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-52-lowlatency     | 3         | 4.69%   |
| 5.15.0-56-lowlatency    | 3         | 4.69%   |
| 5.15.0-47-lowlatency    | 3         | 4.69%   |
| 5.13.0-28-lowlatency    | 3         | 4.69%   |
| 5.8.0-55-lowlatency     | 2         | 3.13%   |
| 5.4.0-94-lowlatency     | 2         | 3.13%   |
| 5.4.0-65-lowlatency     | 2         | 3.13%   |
| 5.4.0-45-lowlatency     | 2         | 3.13%   |
| 5.4.0-42-lowlatency     | 2         | 3.13%   |
| 5.15.0-48-lowlatency    | 2         | 3.13%   |
| 5.15.0-46-lowlatency    | 2         | 3.13%   |
| 5.13.0-30-lowlatency    | 2         | 3.13%   |
| 5.11.0-34-lowlatency    | 2         | 3.13%   |
| 5.11.0-27-lowlatency    | 2         | 3.13%   |
| 5.8.0-59-lowlatency     | 1         | 1.56%   |
| 5.8.0-50-lowlatency     | 1         | 1.56%   |
| 5.8.0-44-lowlatency     | 1         | 1.56%   |
| 5.8.0-43-lowlatency     | 1         | 1.56%   |
| 5.8.0-34-generic        | 1         | 1.56%   |
| 5.8.0-29-lowlatency     | 1         | 1.56%   |
| 5.8.0-25-lowlatency     | 1         | 1.56%   |
| 5.7.6-050706-lowlatency | 1         | 1.56%   |
| 5.7.6-050706-generic    | 1         | 1.56%   |
| 5.4.0-96-lowlatency     | 1         | 1.56%   |
| 5.4.0-88-lowlatency     | 1         | 1.56%   |
| 5.4.0-52-generic        | 1         | 1.56%   |
| 5.4.0-45-generic        | 1         | 1.56%   |
| 5.4.0-34-lowlatency     | 1         | 1.56%   |
| 5.4.0-26-lowlatency     | 1         | 1.56%   |
| 5.4.0-132-lowlatency    | 1         | 1.56%   |
| 5.4.0-107-lowlatency    | 1         | 1.56%   |
| 5.4.0-100-lowlatency    | 1         | 1.56%   |
| 5.3.0-19-lowlatency     | 1         | 1.56%   |
| 5.15.0-52-lowlatency    | 1         | 1.56%   |
| 5.15.0-50-lowlatency    | 1         | 1.56%   |
| 5.15.0-40-lowlatency    | 1         | 1.56%   |
| 5.15.0-37-lowlatency    | 1         | 1.56%   |
| 5.15.0-30-lowlatency    | 1         | 1.56%   |
| 5.13.0-30-generic       | 1         | 1.56%   |
| 5.11.0-41-lowlatency    | 1         | 1.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 32.26%  |
| 5.15.0  | 14        | 22.58%  |
| 5.8.0   | 9         | 14.52%  |
| 5.11.0  | 9         | 14.52%  |
| 5.13.0  | 6         | 9.68%   |
| 4.15.0  | 2         | 3.23%   |
| 5.7.6   | 1         | 1.61%   |
| 5.3.0   | 1         | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 20        | 32.26%  |
| 5.15    | 14        | 22.58%  |
| 5.8     | 9         | 14.52%  |
| 5.11    | 9         | 14.52%  |
| 5.13    | 6         | 9.68%   |
| 4.15    | 2         | 3.23%   |
| 5.7     | 1         | 1.61%   |
| 5.3     | 1         | 1.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 62        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 37        | 59.68%  |
| KDE5  | 19        | 30.65%  |
| GNOME | 5         | 8.06%   |
| LXQt  | 1         | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 59        | 95.16%  |
| Wayland | 3         | 4.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 21        | 33.87%  |
| LightDM | 19        | 30.65%  |
| SDDM    | 16        | 25.81%  |
| GDM     | 5         | 8.06%   |
| LXDM    | 1         | 1.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 26        | 41.94%  |
| fr_FR   | 12        | 19.35%  |
| C       | 4         | 6.45%   |
| pt_BR   | 2         | 3.23%   |
| it_IT   | 2         | 3.23%   |
| es_ES   | 2         | 3.23%   |
| en_CA   | 2         | 3.23%   |
| de_DE   | 2         | 3.23%   |
| Unknown | 2         | 3.23%   |
| ru_RU   | 1         | 1.61%   |
| nl_NL   | 1         | 1.61%   |
| hu_HU   | 1         | 1.61%   |
| es_NI   | 1         | 1.61%   |
| es_CR   | 1         | 1.61%   |
| en_NG   | 1         | 1.61%   |
| en_IE   | 1         | 1.61%   |
| en_AG   | 1         | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 40        | 64.52%  |
| BIOS | 22        | 35.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 58        | 93.55%  |
| Overlay | 4         | 6.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 43        | 69.35%  |
| MBR  | 19        | 30.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 87.1%   |
| Yes       | 8         | 12.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 50%     |
| No        | 31        | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 16        | 25.81%  |
| Dell                   | 11        | 17.74%  |
| Hewlett-Packard        | 10        | 16.13%  |
| ASUSTek Computer       | 7         | 11.29%  |
| Acer                   | 3         | 4.84%   |
| Toshiba                | 2         | 3.23%   |
| HUAWEI                 | 2         | 3.23%   |
| Apple                  | 2         | 3.23%   |
| Sony                   | 1         | 1.61%   |
| Samsung Electronics    | 1         | 1.61%   |
| Razer                  | 1         | 1.61%   |
| Intel Client Systems   | 1         | 1.61%   |
| Google                 | 1         | 1.61%   |
| Gigabyte Technology    | 1         | 1.61%   |
| Getac                  | 1         | 1.61%   |
| Clevo                  | 1         | 1.61%   |
| Avell High Performance | 1         | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G50-45 80E3                       | 2         | 3.23%   |
| HP Pavilion dv6                          | 2         | 3.23%   |
| Toshiba Satellite L755D                  | 1         | 1.61%   |
| Toshiba Satellite C855                   | 1         | 1.61%   |
| Sony VGN-NS31M_W                         | 1         | 1.61%   |
| Samsung 305V4A/305V5A                    | 1         | 1.61%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 1.61%   |
| Lenovo ThinkPad X230 2333A86             | 1         | 1.61%   |
| Lenovo ThinkPad X230 2325AJG             | 1         | 1.61%   |
| Lenovo ThinkPad X230 23245S1             | 1         | 1.61%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 1         | 1.61%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 1.61%   |
| Lenovo ThinkPad W530 2447IG0             | 1         | 1.61%   |
| Lenovo ThinkPad T520 4243K86             | 1         | 1.61%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.61%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 1.61%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 1.61%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 1.61%   |
| Lenovo IdeaPad 3 15ABA7 82RN             | 1         | 1.61%   |
| Lenovo IdeaPad 3 14ARE05 81W3            | 1         | 1.61%   |
| Lenovo G70-80 80FF                       | 1         | 1.61%   |
| Intel Client Systems LAPBC510            | 1         | 1.61%   |
| HUAWEI KLVL-WXXW                         | 1         | 1.61%   |
| HUAWEI HLYL-WXX9                         | 1         | 1.61%   |
| HP ZBook 15 G3                           | 1         | 1.61%   |
| HP Stream Laptop 14-cb0XX                | 1         | 1.61%   |
| HP Sona                                  | 1         | 1.61%   |
| HP OMEN by Laptop 15-ce0xx               | 1         | 1.61%   |
| HP Notebook                              | 1         | 1.61%   |
| HP Laptop 15s-fq1xxx                     | 1         | 1.61%   |
| HP EliteBook 840 G3                      | 1         | 1.61%   |
| HP Compaq 8510p                          | 1         | 1.61%   |
| Google Nami                              | 1         | 1.61%   |
| Gigabyte AERO 15-X9                      | 1         | 1.61%   |
| Getac S400G3                             | 1         | 1.61%   |
| Dell XPS 15 9570                         | 1         | 1.61%   |
| Dell Precision M4500                     | 1         | 1.61%   |
| Dell Latitude E7250                      | 1         | 1.61%   |
| Dell Latitude E6530                      | 1         | 1.61%   |
| Dell Latitude E6500                      | 1         | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 7         | 11.29%  |
| Lenovo IdeaPad                | 5         | 8.06%   |
| Dell Inspiron                 | 5         | 8.06%   |
| Dell Latitude                 | 4         | 6.45%   |
| Toshiba Satellite             | 2         | 3.23%   |
| Lenovo G50-45                 | 2         | 3.23%   |
| HP Pavilion                   | 2         | 3.23%   |
| Acer Aspire                   | 2         | 3.23%   |
| Sony VGN-NS31M                | 1         | 1.61%   |
| Samsung 305V4A                | 1         | 1.61%   |
| Razer Blade                   | 1         | 1.61%   |
| Lenovo Legion                 | 1         | 1.61%   |
| Lenovo G70-80                 | 1         | 1.61%   |
| Intel Client Systems LAPBC510 | 1         | 1.61%   |
| HUAWEI KLVL-WXXW              | 1         | 1.61%   |
| HUAWEI HLYL-WXX9              | 1         | 1.61%   |
| HP ZBook                      | 1         | 1.61%   |
| HP Stream                     | 1         | 1.61%   |
| HP Sona                       | 1         | 1.61%   |
| HP OMEN                       | 1         | 1.61%   |
| HP Notebook                   | 1         | 1.61%   |
| HP Laptop                     | 1         | 1.61%   |
| HP EliteBook                  | 1         | 1.61%   |
| HP Compaq                     | 1         | 1.61%   |
| Google Nami                   | 1         | 1.61%   |
| Gigabyte AERO                 | 1         | 1.61%   |
| Getac S400G3                  | 1         | 1.61%   |
| Dell XPS                      | 1         | 1.61%   |
| Dell Precision                | 1         | 1.61%   |
| Clevo W35                     | 1         | 1.61%   |
| Avell High Performance Avell  | 1         | 1.61%   |
| ASUS X541NA                   | 1         | 1.61%   |
| ASUS VivoBook                 | 1         | 1.61%   |
| ASUS UX305FA                  | 1         | 1.61%   |
| ASUS U56E                     | 1         | 1.61%   |
| ASUS ROG                      | 1         | 1.61%   |
| ASUS GL503VD                  | 1         | 1.61%   |
| ASUS ASUS                     | 1         | 1.61%   |
| Apple MacBookPro8             | 1         | 1.61%   |
| Apple MacBookPro11            | 1         | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 12.9%   |
| 2012 | 8         | 12.9%   |
| 2014 | 7         | 11.29%  |
| 2019 | 5         | 8.06%   |
| 2011 | 5         | 8.06%   |
| 2021 | 4         | 6.45%   |
| 2018 | 4         | 6.45%   |
| 2017 | 4         | 6.45%   |
| 2016 | 4         | 6.45%   |
| 2008 | 4         | 6.45%   |
| 2015 | 3         | 4.84%   |
| 2010 | 2         | 3.23%   |
| 2007 | 2         | 3.23%   |
| 2022 | 1         | 1.61%   |
| 2009 | 1         | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 62        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 55        | 88.71%  |
| Enabled  | 7         | 11.29%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 60        | 96.77%  |
| Yes  | 2         | 3.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 25        | 40.32%  |
| 16.01-24.0 | 11        | 17.74%  |
| 8.01-16.0  | 10        | 16.13%  |
| 3.01-4.0   | 8         | 12.9%   |
| 32.01-64.0 | 3         | 4.84%   |
| 24.01-32.0 | 2         | 3.23%   |
| 2.01-3.0   | 2         | 3.23%   |
| 1.01-2.0   | 1         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 25        | 39.06%  |
| 2.01-3.0  | 15        | 23.44%  |
| 3.01-4.0  | 11        | 17.19%  |
| 4.01-8.0  | 10        | 15.63%  |
| 8.01-16.0 | 2         | 3.13%   |
| 0.51-1.0  | 1         | 1.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 46        | 74.19%  |
| 2      | 14        | 22.58%  |
| 0      | 2         | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 64.52%  |
| Yes       | 22        | 35.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 80.65%  |
| No        | 12        | 19.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 98.39%  |
| No        | 1         | 1.61%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 77.42%  |
| No        | 14        | 22.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 19.35%  |
| France      | 11        | 17.74%  |
| Germany     | 6         | 9.68%   |
| Canada      | 4         | 6.45%   |
| Russia      | 3         | 4.84%   |
| Italy       | 3         | 4.84%   |
| UK          | 2         | 3.23%   |
| Spain       | 2         | 3.23%   |
| Costa Rica  | 2         | 3.23%   |
| Brazil      | 2         | 3.23%   |
| Yemen       | 1         | 1.61%   |
| Turkey      | 1         | 1.61%   |
| Taiwan      | 1         | 1.61%   |
| Poland      | 1         | 1.61%   |
| Norway      | 1         | 1.61%   |
| Nigeria     | 1         | 1.61%   |
| Nicaragua   | 1         | 1.61%   |
| Netherlands | 1         | 1.61%   |
| Mexico      | 1         | 1.61%   |
| Ivory Coast | 1         | 1.61%   |
| Indonesia   | 1         | 1.61%   |
| Hungary     | 1         | 1.61%   |
| Finland     | 1         | 1.61%   |
| Bulgaria    | 1         | 1.61%   |
| Austria     | 1         | 1.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montreal               | 2         | 3.17%   |
| Madrid                 | 2         | 3.17%   |
| Denver                 | 2         | 3.17%   |
| Béziers               | 2         | 3.17%   |
| Yekaterinburg          | 1         | 1.59%   |
| Wroclaw                | 1         | 1.59%   |
| Woonsocket             | 1         | 1.59%   |
| Woodland Park          | 1         | 1.59%   |
| Vienna                 | 1         | 1.59%   |
| Velleron               | 1         | 1.59%   |
| Turin                  | 1         | 1.59%   |
| Taipei                 | 1         | 1.59%   |
| Sunderland             | 1         | 1.59%   |
| Stuttgart              | 1         | 1.59%   |
| Stabekk                | 1         | 1.59%   |
| Sofia                  | 1         | 1.59%   |
| Sleman                 | 1         | 1.59%   |
| Seropedica             | 1         | 1.59%   |
| Sanaa                  | 1         | 1.59%   |
| San Juan               | 1         | 1.59%   |
| Samara                 | 1         | 1.59%   |
| Rio de Janeiro         | 1         | 1.59%   |
| Ragusa                 | 1         | 1.59%   |
| Portland               | 1         | 1.59%   |
| Port Harcourt          | 1         | 1.59%   |
| Phoenix                | 1         | 1.59%   |
| Nudlingen              | 1         | 1.59%   |
| Moscow                 | 1         | 1.59%   |
| Mississauga            | 1         | 1.59%   |
| Mexico City            | 1         | 1.59%   |
| Mannheim               | 1         | 1.59%   |
| Managua                | 1         | 1.59%   |
| Madison                | 1         | 1.59%   |
| Ludwigsburg            | 1         | 1.59%   |
| Lindsay                | 1         | 1.59%   |
| Lille                  | 1         | 1.59%   |
| Libourne               | 1         | 1.59%   |
| Kirkland               | 1         | 1.59%   |
| Istanbul               | 1         | 1.59%   |
| Illkirch-Graffenstaden | 1         | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 13     | 18.06%  |
| WDC                 | 8         | 8      | 11.11%  |
| SanDisk             | 7         | 7      | 9.72%   |
| Toshiba             | 6         | 6      | 8.33%   |
| Unknown             | 4         | 4      | 5.56%   |
| Seagate             | 4         | 4      | 5.56%   |
| Intel               | 4         | 6      | 5.56%   |
| SK hynix            | 3         | 4      | 4.17%   |
| Kingston            | 3         | 3      | 4.17%   |
| Micron Technology   | 2         | 2      | 2.78%   |
| Hitachi             | 2         | 2      | 2.78%   |
| Crucial             | 2         | 2      | 2.78%   |
| Union Memory        | 1         | 1      | 1.39%   |
| UMIS                | 1         | 1      | 1.39%   |
| Team                | 1         | 1      | 1.39%   |
| PNY                 | 1         | 1      | 1.39%   |
| Phison              | 1         | 1      | 1.39%   |
| KIOXIA              | 1         | 1      | 1.39%   |
| KingSpec            | 1         | 1      | 1.39%   |
| JMicron Technology  | 1         | 1      | 1.39%   |
| Inateck             | 1         | 1      | 1.39%   |
| HGST                | 1         | 1      | 1.39%   |
| Fujitsu             | 1         | 1      | 1.39%   |
| China               | 1         | 1      | 1.39%   |
| BHT                 | 1         | 1      | 1.39%   |
| ASMT                | 1         | 1      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 2.74%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 2.74%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 2.74%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 2.74%   |
| Samsung SSD 870 EVO 1TB                   | 2         | 2.74%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 2.74%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 2.74%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 1.37%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 1.37%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 1.37%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 1.37%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 1.37%   |
| WDC WD10JPVT-75A1YT0 1TB                  | 1         | 1.37%   |
| Unknown MMC Card  4GB                     | 1         | 1.37%   |
| Unknown MMC Card  16GB                    | 1         | 1.37%   |
| Unknown DA4128  128GB                     | 1         | 1.37%   |
| Unknown 032G34  32GB                      | 1         | 1.37%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB   | 1         | 1.37%   |
| UMIS RPJTJ256MEE1OWX 256GB                | 1         | 1.37%   |
| Toshiba TR150 240GB SSD                   | 1         | 1.37%   |
| Toshiba MK1637GSX 160GB                   | 1         | 1.37%   |
| Team TM8FP4001T 1TB                       | 1         | 1.37%   |
| SK hynix SKHynix_HFS256GD9TNI-L2A0B 256GB | 1         | 1.37%   |
| Seagate ST9320320AS 320GB                 | 1         | 1.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 1.37%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.37%   |
| Seagate FireCuda 530 ZP4000GM30013 4TB    | 1         | 1.37%   |
| SanDisk SSD PLUS 240GB                    | 1         | 1.37%   |
| SanDisk SD9SN8W128G1002 128GB SSD         | 1         | 1.37%   |
| SanDisk SD8SN8U256G1002 256GB SSD         | 1         | 1.37%   |
| SanDisk SD7SN3Q128G1002 128GB SSD         | 1         | 1.37%   |
| SanDisk Extreme SSD 500GB                 | 1         | 1.37%   |
| SanDisk DF4064  64GB                      | 1         | 1.37%   |
| SanDisk DF4032  32GB                      | 1         | 1.37%   |
| Samsung SSD PM851 mSATA 256GB             | 1         | 1.37%   |
| Samsung SSD 970 PRO 1TB                   | 1         | 1.37%   |
| Samsung SSD 960 PRO 512GB                 | 1         | 1.37%   |
| Samsung SSD 860 EVO 500GB                 | 1         | 1.37%   |
| Samsung PM981 NVMe 1024GB                 | 1         | 1.37%   |
| Samsung MZVLB512HBJQ-00000 512GB          | 1         | 1.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 23.81%  |
| Toshiba             | 5         | 5      | 23.81%  |
| Seagate             | 3         | 3      | 14.29%  |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 2      | 9.52%   |
| Inateck             | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Fujitsu             | 1         | 1      | 4.76%   |
| ASMT                | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 29.17%  |
| SanDisk             | 5         | 5      | 20.83%  |
| Kingston            | 2         | 2      | 8.33%   |
| Crucial             | 2         | 2      | 8.33%   |
| Toshiba             | 1         | 1      | 4.17%   |
| PNY                 | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| KingSpec            | 1         | 1      | 4.17%   |
| JMicron Technology  | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| China               | 1         | 1      | 4.17%   |
| BHT                 | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 22        | 24     | 32.84%  |
| HDD  | 21        | 21     | 31.34%  |
| NVMe | 19        | 24     | 28.36%  |
| MMC  | 5         | 6      | 7.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 41     | 57.58%  |
| NVMe | 19        | 24     | 28.79%  |
| MMC  | 5         | 6      | 7.58%   |
| SAS  | 4         | 4      | 6.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 35     | 76.74%  |
| 0.51-1.0   | 8         | 8      | 18.6%   |
| 3.01-4.0   | 1         | 1      | 2.33%   |
| 1.01-2.0   | 1         | 1      | 2.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 19        | 30.16%  |
| 251-500    | 15        | 23.81%  |
| 501-1000   | 9         | 14.29%  |
| 51-100     | 7         | 11.11%  |
| 21-50      | 6         | 9.52%   |
| 1-20       | 4         | 6.35%   |
| 1001-2000  | 2         | 3.17%   |
| 2001-3000  | 1         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 26        | 40.63%  |
| 21-50     | 11        | 17.19%  |
| 101-250   | 10        | 15.63%  |
| 251-500   | 6         | 9.38%   |
| 51-100    | 6         | 9.38%   |
| 501-1000  | 3         | 4.69%   |
| 1001-2000 | 2         | 3.13%   |

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
| Works    | 43        | 51     | 65.15%  |
| Malfunc  | 15        | 15     | 22.73%  |
| Detected | 8         | 9      | 12.12%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 44        | 60.27%  |
| AMD                         | 11        | 15.07%  |
| Samsung Electronics         | 4         | 5.48%   |
| SK hynix                    | 3         | 4.11%   |
| SanDisk                     | 3         | 4.11%   |
| Union Memory (Shenzhen)     | 2         | 2.74%   |
| Phison Electronics          | 2         | 2.74%   |
| Seagate Technology          | 1         | 1.37%   |
| Micron Technology           | 1         | 1.37%   |
| KIOXIA                      | 1         | 1.37%   |
| Kingston Technology Company | 1         | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 12.82%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 7.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 6.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 6.41%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.85%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 2.56%   |
| SK hynix BC511                                                                 | 2         | 2.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.56%   |
| Intel Non-Volatile memory controller                                           | 2         | 2.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.56%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 1.28%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.28%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.28%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.28%   |
| Micron Non-Volatile memory controller                                          | 1         | 1.28%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.28%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.28%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.28%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.28%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                    | 1         | 1.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.28%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.28%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.28%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 44        | 60.27%  |
| NVMe | 19        | 26.03%  |
| RAID | 7         | 9.59%   |
| IDE  | 3         | 4.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 79.03%  |
| AMD    | 13        | 20.97%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-2450M CPU @ 2.50GHz      | 3         | 4.84%   |
| AMD Ryzen 5 4600H with Radeon Graphics | 3         | 4.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 3.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 2         | 3.23%   |
| Intel Processor 5Y10 CPU @ 0.80GHz     | 1         | 1.61%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.61%   |
| Intel Genuine CPU U2300 @ 1.20GHz      | 1         | 1.61%   |
| Intel Core i9-8950HK CPU @ 2.90GHz     | 1         | 1.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 1.61%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 1         | 1.61%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 1         | 1.61%   |
| Intel Core i7-5600U CPU @ 2.60GHz      | 1         | 1.61%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.61%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz     | 1         | 1.61%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1         | 1.61%   |
| Intel Core i7-3940XM CPU @ 3.00GHz     | 1         | 1.61%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 1         | 1.61%   |
| Intel Core i7-2635QM CPU @ 2.00GHz     | 1         | 1.61%   |
| Intel Core i7-2630QM CPU @ 2.00GHz     | 1         | 1.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 1.61%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz      | 1         | 1.61%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 1         | 1.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.61%   |
| Intel Core i5-4310M CPU @ 2.70GHz      | 1         | 1.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.61%   |
| Intel Core i5-3340M CPU @ 2.70GHz      | 1         | 1.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 1         | 1.61%   |
| Intel Core i5-3230M CPU @ 2.60GHz      | 1         | 1.61%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 1         | 1.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz     | 1         | 1.61%   |
| Intel Core i5-10300H CPU @ 2.50GHz     | 1         | 1.61%   |
| Intel Core i5 CPU M 460 @ 2.53GHz      | 1         | 1.61%   |
| Intel Core i3-8130U CPU @ 2.20GHz      | 1         | 1.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 1         | 1.61%   |
| Intel Core i3-5005U CPU @ 2.00GHz      | 1         | 1.61%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz   | 1         | 1.61%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz   | 1         | 1.61%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz   | 1         | 1.61%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz   | 1         | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 17        | 27.42%  |
| Intel Core i5      | 15        | 24.19%  |
| Intel Core 2 Duo   | 4         | 6.45%   |
| Intel Celeron      | 4         | 6.45%   |
| AMD Ryzen 5        | 4         | 6.45%   |
| Other              | 3         | 4.84%   |
| Intel Core i3      | 3         | 4.84%   |
| AMD Ryzen 7        | 3         | 4.84%   |
| Intel Pentium Dual | 1         | 1.61%   |
| Intel Genuine      | 1         | 1.61%   |
| Intel Core i9      | 1         | 1.61%   |
| AMD Ryzen 3        | 1         | 1.61%   |
| AMD E2             | 1         | 1.61%   |
| AMD E1             | 1         | 1.61%   |
| AMD E              | 1         | 1.61%   |
| AMD A6             | 1         | 1.61%   |
| AMD A4             | 1         | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 51.61%  |
| 4      | 20        | 32.26%  |
| 6      | 7         | 11.29%  |
| 8      | 3         | 4.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 62        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 43        | 69.35%  |
| 1      | 19        | 30.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 62        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 7         | 11.11%  |
| 0x306a9    | 5         | 7.94%   |
| Unknown    | 5         | 7.94%   |
| 0x306d4    | 4         | 6.35%   |
| 0x08600104 | 4         | 6.35%   |
| 0x906ea    | 3         | 4.76%   |
| 0x806ea    | 3         | 4.76%   |
| 0x906e9    | 2         | 3.17%   |
| 0x806c1    | 2         | 3.17%   |
| 0x706e5    | 2         | 3.17%   |
| 0x6fd      | 2         | 3.17%   |
| 0x406e3    | 2         | 3.17%   |
| 0x40651    | 2         | 3.17%   |
| 0x07030105 | 2         | 3.17%   |
| 0xa0652    | 1         | 1.59%   |
| 0x706a1    | 1         | 1.59%   |
| 0x6fb      | 1         | 1.59%   |
| 0x506e3    | 1         | 1.59%   |
| 0x506c9    | 1         | 1.59%   |
| 0x406c4    | 1         | 1.59%   |
| 0x40661    | 1         | 1.59%   |
| 0x306c3    | 1         | 1.59%   |
| 0x106e5    | 1         | 1.59%   |
| 0x1067a    | 1         | 1.59%   |
| 0x10676    | 1         | 1.59%   |
| 0x0a50000c | 1         | 1.59%   |
| 0x08608102 | 1         | 1.59%   |
| 0x08600106 | 1         | 1.59%   |
| 0x08600103 | 1         | 1.59%   |
| 0x07030104 | 1         | 1.59%   |
| 0x05000029 | 1         | 1.59%   |
| 0x03000027 | 1         | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 14.52%  |
| SandyBridge   | 7         | 11.29%  |
| Zen 2         | 6         | 9.68%   |
| IvyBridge     | 5         | 8.06%   |
| Broadwell     | 5         | 8.06%   |
| Haswell       | 4         | 6.45%   |
| Skylake       | 3         | 4.84%   |
| Puma          | 3         | 4.84%   |
| Penryn        | 3         | 4.84%   |
| Core          | 3         | 4.84%   |
| TigerLake     | 2         | 3.23%   |
| IceLake       | 2         | 3.23%   |
| Zen 3         | 1         | 1.61%   |
| Westmere      | 1         | 1.61%   |
| Silvermont    | 1         | 1.61%   |
| Nehalem       | 1         | 1.61%   |
| K10 Llano     | 1         | 1.61%   |
| Goldmont plus | 1         | 1.61%   |
| Goldmont      | 1         | 1.61%   |
| CometLake     | 1         | 1.61%   |
| Bobcat        | 1         | 1.61%   |
| Unknown       | 1         | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 55%     |
| Nvidia | 18        | 22.5%   |
| AMD    | 18        | 22.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 8.54%   |
| AMD Renoir                                                                               | 6         | 7.32%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 6.1%    |
| Intel HD Graphics 5500                                                                   | 4         | 4.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 4.88%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.66%   |
| Nvidia TU117M                                                                            | 2         | 2.44%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 2.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 2.44%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 2.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.44%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.22%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 1.22%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.22%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 1.22%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 1.22%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 1.22%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.22%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 1.22%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.22%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.22%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.22%   |
| Intel HD Graphics 630                                                                    | 1         | 1.22%   |
| Intel HD Graphics 5300                                                                   | 1         | 1.22%   |
| Intel HD Graphics 530                                                                    | 1         | 1.22%   |
| Intel HD Graphics 500                                                                    | 1         | 1.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.22%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.22%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 46.77%  |
| Intel + Nvidia | 13        | 20.97%  |
| 1 x AMD        | 12        | 19.35%  |
| AMD + Nvidia   | 3         | 4.84%   |
| 1 x Nvidia     | 2         | 3.23%   |
| Intel + AMD    | 2         | 3.23%   |
| 2 x AMD        | 1         | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 57        | 91.94%  |
| Proprietary | 5         | 8.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 56.45%  |
| 0.01-0.5   | 9         | 14.52%  |
| 0.51-1.0   | 7         | 11.29%  |
| 1.01-2.0   | 6         | 9.68%   |
| 3.01-4.0   | 3         | 4.84%   |
| 5.01-6.0   | 2         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 14        | 19.72%  |
| AU Optronics            | 14        | 19.72%  |
| Samsung Electronics     | 9         | 12.68%  |
| BOE                     | 9         | 12.68%  |
| Chimei Innolux          | 7         | 9.86%   |
| Sharp                   | 2         | 2.82%   |
| Lenovo                  | 2         | 2.82%   |
| Hewlett-Packard         | 2         | 2.82%   |
| Apple                   | 2         | 2.82%   |
| LG Philips              | 1         | 1.41%   |
| Iiyama                  | 1         | 1.41%   |
| Hannspree               | 1         | 1.41%   |
| Dell                    | 1         | 1.41%   |
| CPT                     | 1         | 1.41%   |
| Chi Mei Optoelectronics | 1         | 1.41%   |
| BenQ                    | 1         | 1.41%   |
| Arnos Instruments       | 1         | 1.41%   |
| Ancor Communications    | 1         | 1.41%   |
| Acer                    | 1         | 1.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 2.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 2.82%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 2.82%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 2.82%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 2         | 2.82%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                  | 1         | 1.41%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 1.41%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch      | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch  | 1         | 1.41%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 1.41%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 600x340mm 27.2-inch                 | 1         | 1.41%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 1         | 1.41%   |
| Iiyama PLE2483H IVM6113 1920x1080 530x300mm 24.0-inch                    | 1         | 1.41%   |
| Hewlett-Packard E242 HWP326F 1920x1200 520x320mm 24.0-inch               | 1         | 1.41%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch                | 1         | 1.41%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                     | 1         | 1.41%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                         | 1         | 1.41%   |
| CPT LCD Monitor CPT141F 1280x800 331x207mm 15.4-inch                     | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 1.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1         | 1.41%   |
| BOE LCD Monitor BOE09CC 1920x1080 344x194mm 15.5-inch                    | 1         | 1.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 43.08%  |
| 1366x768 (WXGA)    | 20        | 30.77%  |
| 1600x900 (HD+)     | 5         | 7.69%   |
| 3840x2160 (4K)     | 3         | 4.62%   |
| 1680x1050 (WSXGA+) | 2         | 3.08%   |
| 1280x800 (WXGA)    | 2         | 3.08%   |
| 2880x1800          | 1         | 1.54%   |
| 2560x1440 (QHD)    | 1         | 1.54%   |
| 2160x1440          | 1         | 1.54%   |
| 1920x1200 (WUXGA)  | 1         | 1.54%   |
| 1440x900 (WXGA+)   | 1         | 1.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 37        | 52.11%  |
| 13     | 8         | 11.27%  |
| 14     | 6         | 8.45%   |
| 24     | 5         | 7.04%   |
| 12     | 4         | 5.63%   |
| 27     | 2         | 2.82%   |
| 21     | 2         | 2.82%   |
| 17     | 2         | 2.82%   |
| 84     | 1         | 1.41%   |
| 20     | 1         | 1.41%   |
| 19     | 1         | 1.41%   |
| 18     | 1         | 1.41%   |
| 16     | 1         | 1.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 67.14%  |
| 201-300     | 8         | 11.43%  |
| 501-600     | 6         | 8.57%   |
| 401-500     | 5         | 7.14%   |
| 351-400     | 3         | 4.29%   |
| 1501-2000   | 1         | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 53        | 84.13%  |
| 16/10 | 9         | 14.29%  |
| 3/2   | 1         | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 53.52%  |
| 81-90          | 11        | 15.49%  |
| 61-70          | 4         | 5.63%   |
| 71-80          | 3         | 4.23%   |
| 251-300        | 3         | 4.23%   |
| 201-250        | 3         | 4.23%   |
| 151-200        | 3         | 4.23%   |
| 301-350        | 2         | 2.82%   |
| More than 1000 | 1         | 1.41%   |
| 141-150        | 1         | 1.41%   |
| 131-140        | 1         | 1.41%   |
| 121-130        | 1         | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 30        | 43.48%  |
| 101-120       | 21        | 30.43%  |
| 51-100        | 11        | 15.94%  |
| 161-240       | 6         | 8.7%    |
| More than 240 | 1         | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 53        | 82.81%  |
| 2     | 10        | 15.63%  |
| 3     | 1         | 1.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 38        | 39.18%  |
| Realtek Semiconductor             | 33        | 34.02%  |
| Qualcomm Atheros                  | 12        | 12.37%  |
| Broadcom                          | 5         | 5.15%   |
| Ralink                            | 2         | 2.06%   |
| ASIX Electronics                  | 2         | 2.06%   |
| MediaTek                          | 1         | 1.03%   |
| Marvell Technology Group          | 1         | 1.03%   |
| Huawei Technologies               | 1         | 1.03%   |
| Ericsson Business Mobile Networks | 1         | 1.03%   |
| Broadcom Limited                  | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 14.53%  |
| Intel Wireless 7265                                               | 6         | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 5.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 3.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 3.42%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.56%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 2.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 1.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.71%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.71%   |
| Intel Wireless 8260                                               | 2         | 1.71%   |
| Intel Wireless 7260                                               | 2         | 1.71%   |
| Intel WiFi Link 5100                                              | 2         | 1.71%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.71%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.71%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.85%   |
| Realtek Realtek Network controller                                | 1         | 0.85%   |
| Realtek 802.11ac NIC                                              | 1         | 0.85%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]  | 1         | 0.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.85%   |
| MediaTek Infinix NOTE 11                                          | 1         | 0.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.85%   |
| Intel Wireless 3160                                               | 1         | 0.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 58.06%  |
| Realtek Semiconductor | 11        | 17.74%  |
| Qualcomm Atheros      | 8         | 12.9%   |
| Broadcom              | 4         | 6.45%   |
| Ralink                | 2         | 3.23%   |
| Broadcom Limited      | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 6         | 9.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 4         | 6.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 4         | 6.35%   |
| Intel Wi-Fi 6 AX200                                              | 3         | 4.76%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 4.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 3         | 4.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 2         | 3.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 2         | 3.17%   |
| Intel Wireless 8265 / 8275                                       | 2         | 3.17%   |
| Intel Wireless 8260                                              | 2         | 3.17%   |
| Intel Wireless 7260                                              | 2         | 3.17%   |
| Intel WiFi Link 5100                                             | 2         | 3.17%   |
| Intel Wi-Fi 6 AX201                                              | 2         | 3.17%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 3.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.59%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1.59%   |
| Realtek Realtek Network controller                               | 1         | 1.59%   |
| Realtek 802.11ac NIC                                             | 1         | 1.59%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1.59%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1         | 1.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 1.59%   |
| Intel Wireless 3160                                              | 1         | 1.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 1.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 1         | 1.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 1         | 1.59%   |
| Intel Centrino Wireless-N 6150                                   | 1         | 1.59%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 1         | 1.59%   |
| Intel Centrino Wireless-N + WiMAX 6150                           | 1         | 1.59%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 1         | 1.59%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                      | 1         | 1.59%   |
| Broadcom BCM4331 802.11a/b/g/n                                   | 1         | 1.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 24        | 46.15%  |
| Intel                    | 17        | 32.69%  |
| Qualcomm Atheros         | 5         | 9.62%   |
| Broadcom                 | 2         | 3.85%   |
| ASIX Electronics         | 2         | 3.85%   |
| MediaTek                 | 1         | 1.92%   |
| Marvell Technology Group | 1         | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 32.69%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 11.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 9.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.85%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 3.85%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 3.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.92%   |
| MediaTek Infinix NOTE 11                                          | 1         | 1.92%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.92%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.92%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.92%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.92%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.92%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.92%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.92%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 53.98%  |
| Ethernet | 50        | 44.25%  |
| Modem    | 2         | 1.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 82.81%  |
| Ethernet | 11        | 17.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 46        | 74.19%  |
| 1     | 16        | 25.81%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 72.58%  |
| Yes  | 17        | 27.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 50%     |
| Realtek Semiconductor           | 5         | 10.42%  |
| Qualcomm Atheros Communications | 4         | 8.33%   |
| Broadcom                        | 4         | 8.33%   |
| Realtek                         | 2         | 4.17%   |
| Ralink Technology               | 2         | 4.17%   |
| Lite-On Technology              | 2         | 4.17%   |
| Apple                           | 2         | 4.17%   |
| Hewlett-Packard                 | 1         | 2.08%   |
| Foxconn International           | 1         | 2.08%   |
| Dell                            | 1         | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 13        | 27.08%  |
| Intel AX201 Bluetooth                             | 4         | 8.33%   |
| Realtek Bluetooth Radio                           | 3         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 3         | 6.25%   |
| Intel AX200 Bluetooth                             | 3         | 6.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 3         | 6.25%   |
| Realtek Bluetooth Radio                           | 2         | 4.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 4.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 4.17%   |
| Apple Bluetooth Host Controller                   | 2         | 4.17%   |
| Realtek RTL8723B Bluetooth                        | 1         | 2.08%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 2.08%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 2.08%   |
| Ralink CSR BS8510                                 | 1         | 2.08%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 2.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 2.08%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 2.08%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 2.08%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 2.08%   |
| Dell Wireless 370 Bluetooth Mini-card             | 1         | 2.08%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 49        | 56.98%  |
| AMD                        | 16        | 18.6%   |
| Nvidia                     | 14        | 16.28%  |
| Yealink Network Technology | 1         | 1.16%   |
| QinHeng Electronics        | 1         | 1.16%   |
| Mackie Designs             | 1         | 1.16%   |
| Logitech                   | 1         | 1.16%   |
| C-Media Electronics        | 1         | 1.16%   |
| BR25                       | 1         | 1.16%   |
| Behringer.......           | 1         | 1.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 6.73%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 6.73%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 5.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 4.81%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 4.81%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 4.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 3.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 3.85%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.88%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.92%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.92%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.92%   |
| Yealink Network Technology VoIP Phone                                                             | 1         | 0.96%   |
| QinHeng Electronics CH345 MIDI adapter                                                            | 1         | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.96%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.96%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.96%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.96%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.96%   |
| Mackie Designs BIG KNOB STUDIO+                                                                   | 1         | 0.96%   |
| Logitech 960 Headset                                                                              | 1         | 0.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.96%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 32.88%  |
| SK hynix            | 21        | 28.77%  |
| Micron Technology   | 8         | 10.96%  |
| Kingston            | 7         | 9.59%   |
| Unknown             | 3         | 4.11%   |
| Ramaxel Technology  | 2         | 2.74%   |
| Nanya Technology    | 2         | 2.74%   |
| Crucial             | 2         | 2.74%   |
| Transcend           | 1         | 1.37%   |
| Timetec             | 1         | 1.37%   |
| Corsair             | 1         | 1.37%   |
| Unknown             | 1         | 1.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 3         | 3.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 3.75%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s         | 3         | 3.75%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 2.5%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 2.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.5%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 2.5%    |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s             | 1         | 1.25%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 1.25%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 1.25%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 1.25%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.25%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s              | 1         | 1.25%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s        | 1         | 1.25%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 1.25%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.25%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s       | 1         | 1.25%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB DDR4 2400MT/s              | 1         | 1.25%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 1.25%   |
| Samsung RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 1.25%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.25%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 1         | 1.25%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s       | 1         | 1.25%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s        | 1         | 1.25%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 1         | 1.25%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.25%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 31        | 47.69%  |
| DDR4   | 22        | 33.85%  |
| DDR2   | 5         | 7.69%   |
| SDRAM  | 3         | 4.62%   |
| LPDDR4 | 2         | 3.08%   |
| LPDDR3 | 2         | 3.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 84.62%  |
| Row Of Chips | 8         | 12.31%  |
| Chip         | 1         | 1.54%   |
| Unknown      | 1         | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 31        | 42.47%  |
| 8192  | 22        | 30.14%  |
| 2048  | 10        | 13.7%   |
| 16384 | 7         | 9.59%   |
| 1024  | 3         | 4.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 25        | 37.31%  |
| 3200    | 9         | 13.43%  |
| 2667    | 7         | 10.45%  |
| 1334    | 7         | 10.45%  |
| 2133    | 4         | 5.97%   |
| 2400    | 3         | 4.48%   |
| 667     | 3         | 4.48%   |
| 4267    | 2         | 2.99%   |
| 4199    | 2         | 2.99%   |
| 1333    | 2         | 2.99%   |
| 1639    | 1         | 1.49%   |
| 800     | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

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
| Chicony Electronics                    | 14        | 26.42%  |
| IMC Networks                           | 7         | 13.21%  |
| Sunplus Innovation Technology          | 5         | 9.43%   |
| Realtek Semiconductor                  | 4         | 7.55%   |
| Microdia                               | 4         | 7.55%   |
| Syntek                                 | 3         | 5.66%   |
| Suyin                                  | 3         | 5.66%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.66%   |
| Quanta                                 | 2         | 3.77%   |
| Acer                                   | 2         | 3.77%   |
| ViewQuest Technologies                 | 1         | 1.89%   |
| Silicon Motion                         | 1         | 1.89%   |
| Ricoh                                  | 1         | 1.89%   |
| Philips (or NXP)                       | 1         | 1.89%   |
| Importek                               | 1         | 1.89%   |
| Apple                                  | 1         | 1.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 4         | 7.41%   |
| Syntek Integrated Camera                            | 3         | 5.56%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 5.56%   |
| IMC Networks Integrated Camera                      | 3         | 5.56%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 3.7%    |
| Sunplus HD WebCam                                   | 2         | 3.7%    |
| Realtek Lenovo EasyCamera                           | 2         | 3.7%    |
| Microdia Integrated_Webcam_HD                       | 2         | 3.7%    |
| Chicony Integrated Camera [ThinkPad]                | 2         | 3.7%    |
| ViewQuest Ability GABB Webcam                       | 1         | 1.85%   |
| Suyin HP Webcam                                     | 1         | 1.85%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1.85%   |
| Suyin Asus Integrated Webcam                        | 1         | 1.85%   |
| Sunplus Dell HD Webcam                              | 1         | 1.85%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 1.85%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.85%   |
| Realtek VGA WebCam                                  | 1         | 1.85%   |
| Realtek HP Wide Vision HD Camera                    | 1         | 1.85%   |
| Quanta ov9734_techfront_camera                      | 1         | 1.85%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.85%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc]          | 1         | 1.85%   |
| Microdia Sonix Integrated Webcam                    | 1         | 1.85%   |
| Microdia Integrated Webcam HD                       | 1         | 1.85%   |
| Importek TOSHIBA Web Camera - HD                    | 1         | 1.85%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.85%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 1.85%   |
| Chicony Integrated IR Camera                        | 1         | 1.85%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 1.85%   |
| Chicony HP TrueVision HD                            | 1         | 1.85%   |
| Chicony HP HD Camera                                | 1         | 1.85%   |
| Chicony HD Webcam                                   | 1         | 1.85%   |
| Chicony HD User Facing                              | 1         | 1.85%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 1.85%   |
| Chicony 4-Port Hub                                  | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 1.85%   |
| Apple FaceTime HD Camera                            | 1         | 1.85%   |
| Acer Lenovo EasyCamera                              | 1         | 1.85%   |
| Acer BisonCam, NB Pro                               | 1         | 1.85%   |

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
| Broadcom    | 4         | 50%     |
| Upek        | 2         | 25%     |
| Lenovo      | 1         | 12.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 25%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 35        | 56.45%  |
| 1     | 24        | 38.71%  |
| 2     | 2         | 3.23%   |
| 3     | 1         | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 32.14%  |
| Graphics card         | 7         | 25%     |
| Chipcard              | 7         | 25%     |
| Net/wireless          | 2         | 7.14%   |
| Multimedia controller | 2         | 7.14%   |
| Camera                | 1         | 3.57%   |

