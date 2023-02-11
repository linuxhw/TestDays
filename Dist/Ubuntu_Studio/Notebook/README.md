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

Total: 77

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 735 G6            | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| ASUSTek       | K53U                        | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
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
| Ubuntu Studio 20.04 | 38        | 59.38%  |
| Ubuntu Studio 22.04 | 13        | 20.31%  |
| Ubuntu Studio 21.10 | 3         | 4.69%   |
| Ubuntu Studio 21.04 | 3         | 4.69%   |
| Ubuntu Studio 20.10 | 3         | 4.69%   |
| Ubuntu Studio 18.04 | 2         | 3.13%   |
| Ubuntu Studio 22.10 | 1         | 1.56%   |
| Ubuntu Studio 19.10 | 1         | 1.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 64        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-52-lowlatency     | 3         | 4.55%   |
| 5.15.0-56-lowlatency    | 3         | 4.55%   |
| 5.15.0-47-lowlatency    | 3         | 4.55%   |
| 5.13.0-28-lowlatency    | 3         | 4.55%   |
| 5.8.0-55-lowlatency     | 2         | 3.03%   |
| 5.4.0-94-lowlatency     | 2         | 3.03%   |
| 5.4.0-65-lowlatency     | 2         | 3.03%   |
| 5.4.0-45-lowlatency     | 2         | 3.03%   |
| 5.4.0-42-lowlatency     | 2         | 3.03%   |
| 5.15.0-50-lowlatency    | 2         | 3.03%   |
| 5.15.0-48-lowlatency    | 2         | 3.03%   |
| 5.15.0-46-lowlatency    | 2         | 3.03%   |
| 5.13.0-30-lowlatency    | 2         | 3.03%   |
| 5.11.0-34-lowlatency    | 2         | 3.03%   |
| 5.11.0-27-lowlatency    | 2         | 3.03%   |
| 5.8.0-59-lowlatency     | 1         | 1.52%   |
| 5.8.0-50-lowlatency     | 1         | 1.52%   |
| 5.8.0-44-lowlatency     | 1         | 1.52%   |
| 5.8.0-43-lowlatency     | 1         | 1.52%   |
| 5.8.0-34-generic        | 1         | 1.52%   |
| 5.8.0-29-lowlatency     | 1         | 1.52%   |
| 5.8.0-25-lowlatency     | 1         | 1.52%   |
| 5.7.6-050706-lowlatency | 1         | 1.52%   |
| 5.7.6-050706-generic    | 1         | 1.52%   |
| 5.4.0-96-lowlatency     | 1         | 1.52%   |
| 5.4.0-88-lowlatency     | 1         | 1.52%   |
| 5.4.0-52-generic        | 1         | 1.52%   |
| 5.4.0-45-generic        | 1         | 1.52%   |
| 5.4.0-34-lowlatency     | 1         | 1.52%   |
| 5.4.0-26-lowlatency     | 1         | 1.52%   |
| 5.4.0-132-lowlatency    | 1         | 1.52%   |
| 5.4.0-107-lowlatency    | 1         | 1.52%   |
| 5.4.0-100-lowlatency    | 1         | 1.52%   |
| 5.3.0-19-lowlatency     | 1         | 1.52%   |
| 5.19.0-1015-lowlatency  | 1         | 1.52%   |
| 5.15.0-52-lowlatency    | 1         | 1.52%   |
| 5.15.0-40-lowlatency    | 1         | 1.52%   |
| 5.15.0-37-lowlatency    | 1         | 1.52%   |
| 5.15.0-30-lowlatency    | 1         | 1.52%   |
| 5.13.0-30-generic       | 1         | 1.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 31.25%  |
| 5.15.0  | 15        | 23.44%  |
| 5.8.0   | 9         | 14.06%  |
| 5.11.0  | 9         | 14.06%  |
| 5.13.0  | 6         | 9.38%   |
| 4.15.0  | 2         | 3.13%   |
| 5.7.6   | 1         | 1.56%   |
| 5.3.0   | 1         | 1.56%   |
| 5.19.0  | 1         | 1.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 20        | 31.25%  |
| 5.15    | 15        | 23.44%  |
| 5.8     | 9         | 14.06%  |
| 5.11    | 9         | 14.06%  |
| 5.13    | 6         | 9.38%   |
| 4.15    | 2         | 3.13%   |
| 5.7     | 1         | 1.56%   |
| 5.3     | 1         | 1.56%   |
| 5.19    | 1         | 1.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 64        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 37        | 57.81%  |
| KDE5  | 21        | 32.81%  |
| GNOME | 5         | 7.81%   |
| LXQt  | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 61        | 95.31%  |
| Wayland | 3         | 4.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 21        | 32.81%  |
| LightDM | 20        | 31.25%  |
| SDDM    | 17        | 26.56%  |
| GDM     | 5         | 7.81%   |
| LXDM    | 1         | 1.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 27        | 42.19%  |
| fr_FR   | 12        | 18.75%  |
| C       | 4         | 6.25%   |
| pt_BR   | 2         | 3.13%   |
| it_IT   | 2         | 3.13%   |
| es_ES   | 2         | 3.13%   |
| en_CA   | 2         | 3.13%   |
| de_DE   | 2         | 3.13%   |
| Unknown | 2         | 3.13%   |
| ru_RU   | 1         | 1.56%   |
| nl_NL   | 1         | 1.56%   |
| hu_HU   | 1         | 1.56%   |
| es_NI   | 1         | 1.56%   |
| es_CR   | 1         | 1.56%   |
| en_NG   | 1         | 1.56%   |
| en_IE   | 1         | 1.56%   |
| en_GB   | 1         | 1.56%   |
| en_AG   | 1         | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 41        | 64.06%  |
| BIOS | 23        | 35.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 60        | 93.75%  |
| Overlay | 4         | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 44        | 68.75%  |
| MBR  | 20        | 31.25%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 87.5%   |
| Yes       | 8         | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 50%     |
| No        | 32        | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 16        | 25%     |
| Hewlett-Packard        | 11        | 17.19%  |
| Dell                   | 11        | 17.19%  |
| ASUSTek Computer       | 8         | 12.5%   |
| Acer                   | 3         | 4.69%   |
| Toshiba                | 2         | 3.13%   |
| HUAWEI                 | 2         | 3.13%   |
| Apple                  | 2         | 3.13%   |
| Sony                   | 1         | 1.56%   |
| Samsung Electronics    | 1         | 1.56%   |
| Razer                  | 1         | 1.56%   |
| Intel Client Systems   | 1         | 1.56%   |
| Google                 | 1         | 1.56%   |
| Gigabyte Technology    | 1         | 1.56%   |
| Getac                  | 1         | 1.56%   |
| Clevo                  | 1         | 1.56%   |
| Avell High Performance | 1         | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G50-45 80E3                       | 2         | 3.13%   |
| HP Pavilion dv6                          | 2         | 3.13%   |
| Toshiba Satellite L755D                  | 1         | 1.56%   |
| Toshiba Satellite C855                   | 1         | 1.56%   |
| Sony VGN-NS31M_W                         | 1         | 1.56%   |
| Samsung 305V4A/305V5A                    | 1         | 1.56%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 1.56%   |
| Lenovo ThinkPad X230 2333A86             | 1         | 1.56%   |
| Lenovo ThinkPad X230 2325AJG             | 1         | 1.56%   |
| Lenovo ThinkPad X230 23245S1             | 1         | 1.56%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 1         | 1.56%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 1.56%   |
| Lenovo ThinkPad W530 2447IG0             | 1         | 1.56%   |
| Lenovo ThinkPad T520 4243K86             | 1         | 1.56%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.56%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 1.56%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 1.56%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 1.56%   |
| Lenovo IdeaPad 3 15ABA7 82RN             | 1         | 1.56%   |
| Lenovo IdeaPad 3 14ARE05 81W3            | 1         | 1.56%   |
| Lenovo G70-80 80FF                       | 1         | 1.56%   |
| Intel Client Systems LAPBC510            | 1         | 1.56%   |
| HUAWEI KLVL-WXXW                         | 1         | 1.56%   |
| HUAWEI HLYL-WXX9                         | 1         | 1.56%   |
| HP ZBook 15 G3                           | 1         | 1.56%   |
| HP Stream Laptop 14-cb0XX                | 1         | 1.56%   |
| HP Sona                                  | 1         | 1.56%   |
| HP OMEN by Laptop 15-ce0xx               | 1         | 1.56%   |
| HP Notebook                              | 1         | 1.56%   |
| HP Laptop 15s-fq1xxx                     | 1         | 1.56%   |
| HP EliteBook 840 G3                      | 1         | 1.56%   |
| HP EliteBook 735 G6                      | 1         | 1.56%   |
| HP Compaq 8510p                          | 1         | 1.56%   |
| Google Nami                              | 1         | 1.56%   |
| Gigabyte AERO 15-X9                      | 1         | 1.56%   |
| Getac S400G3                             | 1         | 1.56%   |
| Dell XPS 15 9570                         | 1         | 1.56%   |
| Dell Precision M4500                     | 1         | 1.56%   |
| Dell Latitude E7250                      | 1         | 1.56%   |
| Dell Latitude E6530                      | 1         | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 7         | 10.94%  |
| Lenovo IdeaPad                | 5         | 7.81%   |
| Dell Inspiron                 | 5         | 7.81%   |
| Dell Latitude                 | 4         | 6.25%   |
| Toshiba Satellite             | 2         | 3.13%   |
| Lenovo G50-45                 | 2         | 3.13%   |
| HP Pavilion                   | 2         | 3.13%   |
| HP EliteBook                  | 2         | 3.13%   |
| Acer Aspire                   | 2         | 3.13%   |
| Sony VGN-NS31M                | 1         | 1.56%   |
| Samsung 305V4A                | 1         | 1.56%   |
| Razer Blade                   | 1         | 1.56%   |
| Lenovo Legion                 | 1         | 1.56%   |
| Lenovo G70-80                 | 1         | 1.56%   |
| Intel Client Systems LAPBC510 | 1         | 1.56%   |
| HUAWEI KLVL-WXXW              | 1         | 1.56%   |
| HUAWEI HLYL-WXX9              | 1         | 1.56%   |
| HP ZBook                      | 1         | 1.56%   |
| HP Stream                     | 1         | 1.56%   |
| HP Sona                       | 1         | 1.56%   |
| HP OMEN                       | 1         | 1.56%   |
| HP Notebook                   | 1         | 1.56%   |
| HP Laptop                     | 1         | 1.56%   |
| HP Compaq                     | 1         | 1.56%   |
| Google Nami                   | 1         | 1.56%   |
| Gigabyte AERO                 | 1         | 1.56%   |
| Getac S400G3                  | 1         | 1.56%   |
| Dell XPS                      | 1         | 1.56%   |
| Dell Precision                | 1         | 1.56%   |
| Clevo W35                     | 1         | 1.56%   |
| Avell High Performance Avell  | 1         | 1.56%   |
| ASUS X541NA                   | 1         | 1.56%   |
| ASUS VivoBook                 | 1         | 1.56%   |
| ASUS UX305FA                  | 1         | 1.56%   |
| ASUS U56E                     | 1         | 1.56%   |
| ASUS ROG                      | 1         | 1.56%   |
| ASUS K53U                     | 1         | 1.56%   |
| ASUS GL503VD                  | 1         | 1.56%   |
| ASUS ASUS                     | 1         | 1.56%   |
| Apple MacBookPro8             | 1         | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 12.5%   |
| 2012 | 8         | 12.5%   |
| 2014 | 7         | 10.94%  |
| 2019 | 6         | 9.38%   |
| 2011 | 6         | 9.38%   |
| 2021 | 4         | 6.25%   |
| 2018 | 4         | 6.25%   |
| 2017 | 4         | 6.25%   |
| 2016 | 4         | 6.25%   |
| 2008 | 4         | 6.25%   |
| 2015 | 3         | 4.69%   |
| 2010 | 2         | 3.13%   |
| 2007 | 2         | 3.13%   |
| 2022 | 1         | 1.56%   |
| 2009 | 1         | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 64        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 56        | 87.5%   |
| Enabled  | 8         | 12.5%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 62        | 96.88%  |
| Yes  | 2         | 3.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 26        | 40.63%  |
| 16.01-24.0 | 11        | 17.19%  |
| 8.01-16.0  | 11        | 17.19%  |
| 3.01-4.0   | 8         | 12.5%   |
| 32.01-64.0 | 3         | 4.69%   |
| 24.01-32.0 | 2         | 3.13%   |
| 2.01-3.0   | 2         | 3.13%   |
| 1.01-2.0   | 1         | 1.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 25        | 37.88%  |
| 2.01-3.0  | 15        | 22.73%  |
| 3.01-4.0  | 12        | 18.18%  |
| 4.01-8.0  | 11        | 16.67%  |
| 8.01-16.0 | 2         | 3.03%   |
| 0.51-1.0  | 1         | 1.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 47        | 73.44%  |
| 2      | 15        | 23.44%  |
| 0      | 2         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 64.06%  |
| Yes       | 23        | 35.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 81.25%  |
| No        | 12        | 18.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 98.44%  |
| No        | 1         | 1.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 76.56%  |
| No        | 15        | 23.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 18.75%  |
| France      | 11        | 17.19%  |
| Germany     | 6         | 9.38%   |
| Canada      | 4         | 6.25%   |
| Spain       | 3         | 4.69%   |
| Russia      | 3         | 4.69%   |
| Italy       | 3         | 4.69%   |
| UK          | 2         | 3.13%   |
| Netherlands | 2         | 3.13%   |
| Costa Rica  | 2         | 3.13%   |
| Brazil      | 2         | 3.13%   |
| Yemen       | 1         | 1.56%   |
| Turkey      | 1         | 1.56%   |
| Taiwan      | 1         | 1.56%   |
| Poland      | 1         | 1.56%   |
| Norway      | 1         | 1.56%   |
| Nigeria     | 1         | 1.56%   |
| Nicaragua   | 1         | 1.56%   |
| Mexico      | 1         | 1.56%   |
| Ivory Coast | 1         | 1.56%   |
| Indonesia   | 1         | 1.56%   |
| Hungary     | 1         | 1.56%   |
| Finland     | 1         | 1.56%   |
| Bulgaria    | 1         | 1.56%   |
| Austria     | 1         | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Montreal       | 2         | 3.08%   |
| Madrid         | 2         | 3.08%   |
| Groningen      | 2         | 3.08%   |
| Denver         | 2         | 3.08%   |
| Béziers       | 2         | 3.08%   |
| Yekaterinburg  | 1         | 1.54%   |
| Wroclaw        | 1         | 1.54%   |
| Woonsocket     | 1         | 1.54%   |
| Woodland Park  | 1         | 1.54%   |
| Vienna         | 1         | 1.54%   |
| Velleron       | 1         | 1.54%   |
| Turin          | 1         | 1.54%   |
| Tarragona      | 1         | 1.54%   |
| Taipei         | 1         | 1.54%   |
| Sunderland     | 1         | 1.54%   |
| Stuttgart      | 1         | 1.54%   |
| Stabekk        | 1         | 1.54%   |
| Sofia          | 1         | 1.54%   |
| Sleman         | 1         | 1.54%   |
| Seropedica     | 1         | 1.54%   |
| Sanaa          | 1         | 1.54%   |
| San Juan       | 1         | 1.54%   |
| Samara         | 1         | 1.54%   |
| Rio de Janeiro | 1         | 1.54%   |
| Ragusa         | 1         | 1.54%   |
| Portland       | 1         | 1.54%   |
| Port Harcourt  | 1         | 1.54%   |
| Phoenix        | 1         | 1.54%   |
| Nudlingen      | 1         | 1.54%   |
| Moscow         | 1         | 1.54%   |
| Mississauga    | 1         | 1.54%   |
| Mexico City    | 1         | 1.54%   |
| Mannheim       | 1         | 1.54%   |
| Managua        | 1         | 1.54%   |
| Madison        | 1         | 1.54%   |
| Ludwigsburg    | 1         | 1.54%   |
| Lindsay        | 1         | 1.54%   |
| Lille          | 1         | 1.54%   |
| Libourne       | 1         | 1.54%   |
| Kirkland       | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 13        | 13     | 17.57%  |
| WDC                         | 9         | 9      | 12.16%  |
| SanDisk                     | 7         | 7      | 9.46%   |
| Toshiba                     | 6         | 6      | 8.11%   |
| Unknown                     | 4         | 4      | 5.41%   |
| Seagate                     | 4         | 4      | 5.41%   |
| Intel                       | 4         | 6      | 5.41%   |
| SK hynix                    | 3         | 4      | 4.05%   |
| Kingston                    | 3         | 3      | 4.05%   |
| Micron Technology           | 2         | 2      | 2.7%    |
| Hitachi                     | 2         | 2      | 2.7%    |
| Crucial                     | 2         | 2      | 2.7%    |
| Union Memory                | 1         | 1      | 1.35%   |
| UMIS                        | 1         | 1      | 1.35%   |
| Team                        | 1         | 1      | 1.35%   |
| PNY                         | 1         | 1      | 1.35%   |
| Phison                      | 1         | 1      | 1.35%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.35%   |
| KIOXIA                      | 1         | 1      | 1.35%   |
| KingSpec                    | 1         | 1      | 1.35%   |
| JMicron Technology          | 1         | 1      | 1.35%   |
| Inateck                     | 1         | 1      | 1.35%   |
| HGST                        | 1         | 1      | 1.35%   |
| Fujitsu                     | 1         | 1      | 1.35%   |
| China                       | 1         | 1      | 1.35%   |
| BHT                         | 1         | 1      | 1.35%   |
| ASMT                        | 1         | 1      | 1.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 2.67%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 2.67%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 2.67%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 2.67%   |
| Samsung SSD 870 EVO 1TB                   | 2         | 2.67%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 2.67%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 2.67%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 1.33%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 1.33%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 1.33%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 1.33%   |
| WDC WD3200BEKT-60V5T1 320GB               | 1         | 1.33%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 1.33%   |
| WDC WD10JPVT-75A1YT0 1TB                  | 1         | 1.33%   |
| Unknown MMC Card  4GB                     | 1         | 1.33%   |
| Unknown MMC Card  16GB                    | 1         | 1.33%   |
| Unknown DA4128  128GB                     | 1         | 1.33%   |
| Unknown 032G34  32GB                      | 1         | 1.33%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB   | 1         | 1.33%   |
| UMIS RPJTJ256MEE1OWX 256GB                | 1         | 1.33%   |
| Toshiba TR150 240GB SSD                   | 1         | 1.33%   |
| Toshiba MK1637GSX 160GB                   | 1         | 1.33%   |
| Team TM8FP4001T 1TB                       | 1         | 1.33%   |
| SK hynix SKHynix_HFS256GD9TNI-L2A0B 256GB | 1         | 1.33%   |
| Seagate ST9320320AS 320GB                 | 1         | 1.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 1.33%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.33%   |
| Seagate FireCuda 530 ZP4000GM30013 4TB    | 1         | 1.33%   |
| SanDisk SSD PLUS 240GB                    | 1         | 1.33%   |
| SanDisk SD9SN8W128G1002 128GB SSD         | 1         | 1.33%   |
| SanDisk SD8SN8U256G1002 256GB SSD         | 1         | 1.33%   |
| SanDisk SD7SN3Q128G1002 128GB SSD         | 1         | 1.33%   |
| SanDisk Extreme SSD 500GB                 | 1         | 1.33%   |
| SanDisk DF4064  64GB                      | 1         | 1.33%   |
| SanDisk DF4032  32GB                      | 1         | 1.33%   |
| Samsung SSD PM851 mSATA 256GB             | 1         | 1.33%   |
| Samsung SSD 970 PRO 1TB                   | 1         | 1.33%   |
| Samsung SSD 960 PRO 512GB                 | 1         | 1.33%   |
| Samsung SSD 860 EVO 500GB                 | 1         | 1.33%   |
| Samsung PM981 NVMe 1024GB                 | 1         | 1.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 28.57%  |
| Toshiba             | 5         | 5      | 23.81%  |
| Seagate             | 3         | 3      | 14.29%  |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 2      | 9.52%   |
| HGST                | 1         | 1      | 4.76%   |
| Fujitsu             | 1         | 1      | 4.76%   |
| ASMT                | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 28%     |
| SanDisk             | 5         | 5      | 20%     |
| Kingston            | 2         | 2      | 8%      |
| Crucial             | 2         | 2      | 8%      |
| Toshiba             | 1         | 1      | 4%      |
| PNY                 | 1         | 1      | 4%      |
| Micron Technology   | 1         | 1      | 4%      |
| KingSpec            | 1         | 1      | 4%      |
| JMicron Technology  | 1         | 1      | 4%      |
| Intel               | 1         | 1      | 4%      |
| Inateck             | 1         | 1      | 4%      |
| China               | 1         | 1      | 4%      |
| BHT                 | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 23        | 25     | 33.33%  |
| HDD  | 21        | 21     | 30.43%  |
| NVMe | 20        | 25     | 28.99%  |
| MMC  | 5         | 6      | 7.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 42     | 57.35%  |
| NVMe | 20        | 25     | 29.41%  |
| MMC  | 5         | 6      | 7.35%   |
| SAS  | 4         | 4      | 5.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 35     | 75%     |
| 0.51-1.0   | 10        | 10     | 22.73%  |
| 1.01-2.0   | 1         | 1      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 19        | 29.23%  |
| 251-500    | 16        | 24.62%  |
| 501-1000   | 9         | 13.85%  |
| 21-50      | 7         | 10.77%  |
| 51-100     | 7         | 10.77%  |
| 1-20       | 4         | 6.15%   |
| 1001-2000  | 2         | 3.08%   |
| 2001-3000  | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 26        | 39.39%  |
| 21-50     | 12        | 18.18%  |
| 101-250   | 10        | 15.15%  |
| 251-500   | 7         | 10.61%  |
| 51-100    | 6         | 9.09%   |
| 501-1000  | 3         | 4.55%   |
| 1001-2000 | 2         | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 6.25%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 6.25%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 6.25%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 6.25%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 6.25%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 6.25%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 6.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 6.25%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 6.25%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 6.25%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 6.25%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 6.25%   |
| KingSpec P3-256 256GB                               | 1         | 1      | 6.25%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 6.25%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 31.25%  |
| Seagate             | 3         | 3      | 18.75%  |
| Samsung Electronics | 3         | 3      | 18.75%  |
| Toshiba             | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 1      | 6.25%   |
| KingSpec            | 1         | 1      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 41.67%  |
| Seagate             | 3         | 3      | 25%     |
| Samsung Electronics | 2         | 2      | 16.67%  |
| Toshiba             | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 75%     |
| SSD  | 4         | 4      | 25%     |

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
| Works    | 44        | 52     | 64.71%  |
| Malfunc  | 16        | 16     | 23.53%  |
| Detected | 8         | 9      | 11.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 44        | 58.67%  |
| AMD                         | 12        | 16%     |
| Samsung Electronics         | 4         | 5.33%   |
| SK hynix                    | 3         | 4%      |
| SanDisk                     | 3         | 4%      |
| Union Memory (Shenzhen)     | 2         | 2.67%   |
| Phison Electronics          | 2         | 2.67%   |
| Seagate Technology          | 1         | 1.33%   |
| Micron Technology           | 1         | 1.33%   |
| MAXIO Technology (Hangzhou) | 1         | 1.33%   |
| KIOXIA                      | 1         | 1.33%   |
| Kingston Technology Company | 1         | 1.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 12.35%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 7.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 7.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 6.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 6.17%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 3.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.7%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 2.47%   |
| SK hynix BC511                                                                 | 2         | 2.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.47%   |
| Intel Non-Volatile memory controller                                           | 2         | 2.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 2.47%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 1.23%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.23%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.23%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.23%   |
| Micron Non-Volatile memory controller                                          | 1         | 1.23%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 1.23%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.23%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.23%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.23%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.23%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                    | 1         | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.23%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.23%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 45        | 59.21%  |
| NVMe | 20        | 26.32%  |
| RAID | 7         | 9.21%   |
| IDE  | 4         | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 76.56%  |
| AMD    | 15        | 23.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-2450M CPU @ 2.50GHz      | 3         | 4.69%   |
| AMD Ryzen 5 4600H with Radeon Graphics | 3         | 4.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 3.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 2         | 3.13%   |
| Intel Processor 5Y10 CPU @ 0.80GHz     | 1         | 1.56%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.56%   |
| Intel Genuine CPU U2300 @ 1.20GHz      | 1         | 1.56%   |
| Intel Core i9-8950HK CPU @ 2.90GHz     | 1         | 1.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 1.56%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 1         | 1.56%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 1         | 1.56%   |
| Intel Core i7-5600U CPU @ 2.60GHz      | 1         | 1.56%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.56%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz     | 1         | 1.56%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1         | 1.56%   |
| Intel Core i7-3940XM CPU @ 3.00GHz     | 1         | 1.56%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 1         | 1.56%   |
| Intel Core i7-2635QM CPU @ 2.00GHz     | 1         | 1.56%   |
| Intel Core i7-2630QM CPU @ 2.00GHz     | 1         | 1.56%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 1.56%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz      | 1         | 1.56%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 1         | 1.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.56%   |
| Intel Core i5-4310M CPU @ 2.70GHz      | 1         | 1.56%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.56%   |
| Intel Core i5-3340M CPU @ 2.70GHz      | 1         | 1.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 1         | 1.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz      | 1         | 1.56%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 1         | 1.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz     | 1         | 1.56%   |
| Intel Core i5-10300H CPU @ 2.50GHz     | 1         | 1.56%   |
| Intel Core i5 CPU M 460 @ 2.53GHz      | 1         | 1.56%   |
| Intel Core i3-8130U CPU @ 2.20GHz      | 1         | 1.56%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 1         | 1.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz      | 1         | 1.56%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz   | 1         | 1.56%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz   | 1         | 1.56%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz   | 1         | 1.56%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz   | 1         | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 17        | 26.56%  |
| Intel Core i5      | 15        | 23.44%  |
| Intel Core 2 Duo   | 4         | 6.25%   |
| Intel Celeron      | 4         | 6.25%   |
| AMD Ryzen 5        | 4         | 6.25%   |
| Other              | 3         | 4.69%   |
| Intel Core i3      | 3         | 4.69%   |
| AMD Ryzen 7        | 3         | 4.69%   |
| AMD E              | 2         | 3.13%   |
| Intel Pentium Dual | 1         | 1.56%   |
| Intel Genuine      | 1         | 1.56%   |
| Intel Core i9      | 1         | 1.56%   |
| AMD Ryzen 3 PRO    | 1         | 1.56%   |
| AMD Ryzen 3        | 1         | 1.56%   |
| AMD E2             | 1         | 1.56%   |
| AMD E1             | 1         | 1.56%   |
| AMD A6             | 1         | 1.56%   |
| AMD A4             | 1         | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 33        | 51.56%  |
| 4      | 21        | 32.81%  |
| 6      | 7         | 10.94%  |
| 8      | 3         | 4.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 64        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 43        | 67.19%  |
| 1      | 21        | 32.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 64        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 7         | 10.77%  |
| 0x306a9    | 5         | 7.69%   |
| Unknown    | 5         | 7.69%   |
| 0x306d4    | 4         | 6.15%   |
| 0x08600104 | 4         | 6.15%   |
| 0x906ea    | 3         | 4.62%   |
| 0x806ea    | 3         | 4.62%   |
| 0x906e9    | 2         | 3.08%   |
| 0x806c1    | 2         | 3.08%   |
| 0x706e5    | 2         | 3.08%   |
| 0x6fd      | 2         | 3.08%   |
| 0x406e3    | 2         | 3.08%   |
| 0x40651    | 2         | 3.08%   |
| 0x07030105 | 2         | 3.08%   |
| 0xa0652    | 1         | 1.54%   |
| 0x706a1    | 1         | 1.54%   |
| 0x6fb      | 1         | 1.54%   |
| 0x506e3    | 1         | 1.54%   |
| 0x506c9    | 1         | 1.54%   |
| 0x406c4    | 1         | 1.54%   |
| 0x40661    | 1         | 1.54%   |
| 0x306c3    | 1         | 1.54%   |
| 0x106e5    | 1         | 1.54%   |
| 0x1067a    | 1         | 1.54%   |
| 0x10676    | 1         | 1.54%   |
| 0x0a50000c | 1         | 1.54%   |
| 0x08608102 | 1         | 1.54%   |
| 0x08600106 | 1         | 1.54%   |
| 0x08600103 | 1         | 1.54%   |
| 0x08108109 | 1         | 1.54%   |
| 0x07030104 | 1         | 1.54%   |
| 0x0500010d | 1         | 1.54%   |
| 0x05000029 | 1         | 1.54%   |
| 0x03000027 | 1         | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 14.06%  |
| SandyBridge   | 7         | 10.94%  |
| Zen 2         | 6         | 9.38%   |
| IvyBridge     | 5         | 7.81%   |
| Broadwell     | 5         | 7.81%   |
| Haswell       | 4         | 6.25%   |
| Skylake       | 3         | 4.69%   |
| Puma          | 3         | 4.69%   |
| Penryn        | 3         | 4.69%   |
| Core          | 3         | 4.69%   |
| TigerLake     | 2         | 3.13%   |
| IceLake       | 2         | 3.13%   |
| Bobcat        | 2         | 3.13%   |
| Zen+          | 1         | 1.56%   |
| Zen 3         | 1         | 1.56%   |
| Westmere      | 1         | 1.56%   |
| Silvermont    | 1         | 1.56%   |
| Nehalem       | 1         | 1.56%   |
| K10 Llano     | 1         | 1.56%   |
| Goldmont plus | 1         | 1.56%   |
| Goldmont      | 1         | 1.56%   |
| CometLake     | 1         | 1.56%   |
| Unknown       | 1         | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 53.66%  |
| AMD    | 20        | 24.39%  |
| Nvidia | 18        | 21.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 8.33%   |
| AMD Renoir                                                                               | 6         | 7.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.95%   |
| Intel HD Graphics 5500                                                                   | 4         | 4.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 4.76%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.57%   |
| Nvidia TU117M                                                                            | 2         | 2.38%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 2.38%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 2.38%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 2.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.38%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 2.38%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.19%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 1.19%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.19%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 1.19%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 1.19%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 1.19%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.19%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 1.19%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.19%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.19%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.19%   |
| Intel HD Graphics 630                                                                    | 1         | 1.19%   |
| Intel HD Graphics 5300                                                                   | 1         | 1.19%   |
| Intel HD Graphics 530                                                                    | 1         | 1.19%   |
| Intel HD Graphics 500                                                                    | 1         | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.19%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.19%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 45.31%  |
| 1 x AMD        | 14        | 21.88%  |
| Intel + Nvidia | 13        | 20.31%  |
| AMD + Nvidia   | 3         | 4.69%   |
| 1 x Nvidia     | 2         | 3.13%   |
| Intel + AMD    | 2         | 3.13%   |
| 2 x AMD        | 1         | 1.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 59        | 92.19%  |
| Proprietary | 5         | 7.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 56.25%  |
| 0.01-0.5   | 9         | 14.06%  |
| 1.01-2.0   | 7         | 10.94%  |
| 0.51-1.0   | 7         | 10.94%  |
| 3.01-4.0   | 3         | 4.69%   |
| 5.01-6.0   | 2         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 15        | 20.55%  |
| LG Display              | 14        | 19.18%  |
| Samsung Electronics     | 9         | 12.33%  |
| BOE                     | 9         | 12.33%  |
| Chimei Innolux          | 7         | 9.59%   |
| Sharp                   | 2         | 2.74%   |
| Lenovo                  | 2         | 2.74%   |
| Hewlett-Packard         | 2         | 2.74%   |
| Chi Mei Optoelectronics | 2         | 2.74%   |
| Apple                   | 2         | 2.74%   |
| LG Philips              | 1         | 1.37%   |
| Iiyama                  | 1         | 1.37%   |
| Hannspree               | 1         | 1.37%   |
| Dell                    | 1         | 1.37%   |
| CPT                     | 1         | 1.37%   |
| BenQ                    | 1         | 1.37%   |
| Arnos Instruments       | 1         | 1.37%   |
| Ancor Communications    | 1         | 1.37%   |
| Acer                    | 1         | 1.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 2.74%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 2.74%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 2.74%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 2.74%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 2         | 2.74%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                  | 1         | 1.37%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 1.37%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch      | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch    | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch    | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch  | 1         | 1.37%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 1         | 1.37%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch              | 1         | 1.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 1.37%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch              | 1         | 1.37%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 1.37%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch                 | 1         | 1.37%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 1         | 1.37%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                    | 1         | 1.37%   |
| Hewlett-Packard E242 HWP326F 1920x1200 518x324mm 24.1-inch               | 1         | 1.37%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch                | 1         | 1.37%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                     | 1         | 1.37%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                         | 1         | 1.37%   |
| CPT LCD Monitor CPT141F 1280x800 331x207mm 15.4-inch                     | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 1.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 29        | 43.28%  |
| 1366x768 (WXGA)    | 21        | 31.34%  |
| 1600x900 (HD+)     | 5         | 7.46%   |
| 3840x2160 (4K)     | 3         | 4.48%   |
| 1680x1050 (WSXGA+) | 2         | 2.99%   |
| 1280x800 (WXGA)    | 2         | 2.99%   |
| 2880x1800          | 1         | 1.49%   |
| 2560x1440 (QHD)    | 1         | 1.49%   |
| 2160x1440          | 1         | 1.49%   |
| 1920x1200 (WUXGA)  | 1         | 1.49%   |
| 1440x900 (WXGA+)   | 1         | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 38        | 52.05%  |
| 13     | 9         | 12.33%  |
| 14     | 6         | 8.22%   |
| 24     | 5         | 6.85%   |
| 12     | 4         | 5.48%   |
| 27     | 2         | 2.74%   |
| 21     | 2         | 2.74%   |
| 17     | 2         | 2.74%   |
| 84     | 1         | 1.37%   |
| 20     | 1         | 1.37%   |
| 19     | 1         | 1.37%   |
| 18     | 1         | 1.37%   |
| 16     | 1         | 1.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 66.67%  |
| 201-300     | 9         | 12.5%   |
| 501-600     | 6         | 8.33%   |
| 401-500     | 5         | 6.94%   |
| 351-400     | 3         | 4.17%   |
| 1501-2000   | 1         | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 55        | 84.62%  |
| 16/10 | 9         | 13.85%  |
| 3/2   | 1         | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 53.42%  |
| 81-90          | 11        | 15.07%  |
| 71-80          | 4         | 5.48%   |
| 61-70          | 4         | 5.48%   |
| 251-300        | 3         | 4.11%   |
| 201-250        | 3         | 4.11%   |
| 151-200        | 3         | 4.11%   |
| 301-350        | 2         | 2.74%   |
| More than 1000 | 1         | 1.37%   |
| 141-150        | 1         | 1.37%   |
| 131-140        | 1         | 1.37%   |
| 121-130        | 1         | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 30        | 42.25%  |
| 101-120       | 21        | 29.58%  |
| 51-100        | 12        | 16.9%   |
| 161-240       | 7         | 9.86%   |
| More than 240 | 1         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 55        | 83.33%  |
| 2     | 10        | 15.15%  |
| 3     | 1         | 1.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 39        | 38.61%  |
| Realtek Semiconductor             | 35        | 34.65%  |
| Qualcomm Atheros                  | 13        | 12.87%  |
| Broadcom                          | 5         | 4.95%   |
| Ralink                            | 2         | 1.98%   |
| ASIX Electronics                  | 2         | 1.98%   |
| MediaTek                          | 1         | 0.99%   |
| Marvell Technology Group          | 1         | 0.99%   |
| Huawei Technologies               | 1         | 0.99%   |
| Ericsson Business Mobile Networks | 1         | 0.99%   |
| Broadcom Limited                  | 1         | 0.99%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 15.7%   |
| Intel Wireless 7265                                               | 6         | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 3.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 3.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 2.48%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.48%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 2.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 2.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.65%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.65%   |
| Intel Wireless 8260                                               | 2         | 1.65%   |
| Intel Wireless 7260                                               | 2         | 1.65%   |
| Intel WiFi Link 5100                                              | 2         | 1.65%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.65%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.83%   |
| Realtek Realtek Network controller                                | 1         | 0.83%   |
| Realtek 802.11ac NIC                                              | 1         | 0.83%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]  | 1         | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.83%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.83%   |
| MediaTek File-CD Gadget                                           | 1         | 0.83%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.83%   |
| Intel Wireless-AC 9260                                            | 1         | 0.83%   |
| Intel Wireless 3160                                               | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 57.81%  |
| Realtek Semiconductor | 11        | 17.19%  |
| Qualcomm Atheros      | 9         | 14.06%  |
| Broadcom              | 4         | 6.25%   |
| Ralink                | 2         | 3.13%   |
| Broadcom Limited      | 1         | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 6         | 9.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 4         | 6.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 4         | 6.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 3         | 4.62%   |
| Intel Wi-Fi 6 AX200                                              | 3         | 4.62%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 4.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 3         | 4.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 3.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 2         | 3.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 3.08%   |
| Intel Wireless 8265 / 8275                                       | 2         | 3.08%   |
| Intel Wireless 8260                                              | 2         | 3.08%   |
| Intel Wireless 7260                                              | 2         | 3.08%   |
| Intel WiFi Link 5100                                             | 2         | 3.08%   |
| Intel Wi-Fi 6 AX201                                              | 2         | 3.08%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 3.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.54%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1.54%   |
| Realtek Realtek Network controller                               | 1         | 1.54%   |
| Realtek 802.11ac NIC                                             | 1         | 1.54%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1.54%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1         | 1.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 1.54%   |
| Intel Wireless-AC 9260                                           | 1         | 1.54%   |
| Intel Wireless 3160                                              | 1         | 1.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 1.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 1         | 1.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 1         | 1.54%   |
| Intel Centrino Wireless-N 6150                                   | 1         | 1.54%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 1         | 1.54%   |
| Intel Centrino Wireless-N + WiMAX 6150                           | 1         | 1.54%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 1         | 1.54%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                      | 1         | 1.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                   | 1         | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 26        | 48.15%  |
| Intel                    | 17        | 31.48%  |
| Qualcomm Atheros         | 5         | 9.26%   |
| Broadcom                 | 2         | 3.7%    |
| ASIX Electronics         | 2         | 3.7%    |
| MediaTek                 | 1         | 1.85%   |
| Marvell Technology Group | 1         | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 35.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 11.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 9.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.7%    |
| Intel 82567LM Gigabit Network Connection                          | 2         | 3.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 3.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.85%   |
| MediaTek File-CD Gadget                                           | 1         | 1.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.85%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.85%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.85%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.85%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 53.85%  |
| Ethernet | 52        | 44.44%  |
| Modem    | 2         | 1.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 82.09%  |
| Ethernet | 12        | 17.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 48        | 75%     |
| 1     | 16        | 25%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 46        | 71.88%  |
| Yes  | 18        | 28.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 51.02%  |
| Realtek Semiconductor           | 5         | 10.2%   |
| Qualcomm Atheros Communications | 4         | 8.16%   |
| Broadcom                        | 4         | 8.16%   |
| Realtek                         | 2         | 4.08%   |
| Ralink Technology               | 2         | 4.08%   |
| Lite-On Technology              | 2         | 4.08%   |
| Apple                           | 2         | 4.08%   |
| Hewlett-Packard                 | 1         | 2.04%   |
| Foxconn International           | 1         | 2.04%   |
| Dell                            | 1         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 13        | 26.53%  |
| Intel Bluetooth Device                            | 4         | 8.16%   |
| Realtek Bluetooth Radio                           | 3         | 6.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 3         | 6.12%   |
| Intel AX200 Bluetooth                             | 3         | 6.12%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 3         | 6.12%   |
| Realtek Bluetooth Radio                           | 2         | 4.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 4.08%   |
| Lite-On Bluetooth Device                          | 2         | 4.08%   |
| Apple Bluetooth Host Controller                   | 2         | 4.08%   |
| Realtek RTL8723B Bluetooth                        | 1         | 2.04%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 2.04%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 2.04%   |
| Ralink CSR BS8510                                 | 1         | 2.04%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 2.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 2.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 2.04%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 2.04%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 2.04%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 2.04%   |
| Dell Wireless 370 Bluetooth Mini-card             | 1         | 2.04%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 49        | 55.68%  |
| AMD                        | 18        | 20.45%  |
| Nvidia                     | 14        | 15.91%  |
| Yealink Network Technology | 1         | 1.14%   |
| QinHeng Electronics        | 1         | 1.14%   |
| Mackie Designs             | 1         | 1.14%   |
| Logitech                   | 1         | 1.14%   |
| Jieli Technology           | 1         | 1.14%   |
| C-Media Electronics        | 1         | 1.14%   |
| Behringer.......           | 1         | 1.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 7.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 6.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 5.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 4.63%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 4.63%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 3.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 3.7%    |
| AMD FCH Azalia Controller                                                  | 4         | 3.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.78%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 2.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.85%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.85%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.85%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.85%   |
| Yealink Network Technology VoIP Phone                                      | 1         | 0.93%   |
| QinHeng Electronics CH345 MIDI adapter                                     | 1         | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.93%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.93%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.93%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.93%   |
| Mackie Designs BIG KNOB STUDIO+                                            | 1         | 0.93%   |
| Logitech 960 Headset                                                       | 1         | 0.93%   |
| Jieli Technology UACDemoV1.0                                               | 1         | 0.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 32%     |
| SK hynix            | 22        | 29.33%  |
| Micron Technology   | 8         | 10.67%  |
| Kingston            | 7         | 9.33%   |
| Unknown             | 3         | 4%      |
| Ramaxel Technology  | 2         | 2.67%   |
| Nanya Technology    | 2         | 2.67%   |
| Crucial             | 2         | 2.67%   |
| Transcend           | 1         | 1.33%   |
| Timetec             | 1         | 1.33%   |
| G.Skill             | 1         | 1.33%   |
| Corsair             | 1         | 1.33%   |
| Unknown             | 1         | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s    | 3         | 3.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 3.61%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s         | 3         | 3.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.41%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 2.41%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 2.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.41%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 2.41%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s             | 1         | 1.2%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 1.2%    |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 1.2%    |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 1.2%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.2%    |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s              | 1         | 1.2%    |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s        | 1         | 1.2%    |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.2%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.2%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.2%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.2%    |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.2%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.2%    |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 1         | 1.2%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 1         | 1.2%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s   | 1         | 1.2%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 1.2%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.2%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s       | 1         | 1.2%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB DDR4 2400MT/s              | 1         | 1.2%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 1.2%    |
| Samsung RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 1.2%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.2%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 1         | 1.2%    |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s       | 1         | 1.2%    |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 4199MT/s             | 1         | 1.2%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.2%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.2%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 32        | 47.76%  |
| DDR4   | 23        | 34.33%  |
| DDR2   | 5         | 7.46%   |
| SDRAM  | 3         | 4.48%   |
| LPDDR4 | 2         | 2.99%   |
| LPDDR3 | 2         | 2.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 57        | 85.07%  |
| Row Of Chips | 8         | 11.94%  |
| Chip         | 1         | 1.49%   |
| Unknown      | 1         | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 32        | 42.67%  |
| 8192  | 23        | 30.67%  |
| 2048  | 10        | 13.33%  |
| 16384 | 7         | 9.33%   |
| 1024  | 3         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 37.14%  |
| 3200    | 9         | 12.86%  |
| 2667    | 7         | 10%     |
| 1334    | 7         | 10%     |
| 2400    | 4         | 5.71%   |
| 2133    | 4         | 5.71%   |
| 1333    | 3         | 4.29%   |
| 667     | 3         | 4.29%   |
| 4267    | 2         | 2.86%   |
| 4199    | 2         | 2.86%   |
| 1639    | 1         | 1.43%   |
| 800     | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

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
| Chicony Electronics                    | 16        | 29.09%  |
| IMC Networks                           | 7         | 12.73%  |
| Sunplus Innovation Technology          | 5         | 9.09%   |
| Realtek Semiconductor                  | 4         | 7.27%   |
| Microdia                               | 4         | 7.27%   |
| Syntek                                 | 3         | 5.45%   |
| Suyin                                  | 3         | 5.45%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.45%   |
| Quanta                                 | 2         | 3.64%   |
| Acer                                   | 2         | 3.64%   |
| ViewQuest Technologies                 | 1         | 1.82%   |
| Silicon Motion                         | 1         | 1.82%   |
| Ricoh                                  | 1         | 1.82%   |
| Philips (or NXP)                       | 1         | 1.82%   |
| Importek                               | 1         | 1.82%   |
| Apple                                  | 1         | 1.82%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 4         | 7.14%   |
| Syntek Integrated Camera                            | 3         | 5.36%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 5.36%   |
| IMC Networks Integrated Camera                      | 3         | 5.36%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 3.57%   |
| Sunplus HD WebCam                                   | 2         | 3.57%   |
| Realtek Lenovo EasyCamera                           | 2         | 3.57%   |
| Microdia Integrated_Webcam_HD                       | 2         | 3.57%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 3.57%   |
| Chicony HP HD Camera                                | 2         | 3.57%   |
| ViewQuest Ability GABB Webcam                       | 1         | 1.79%   |
| Suyin HP Webcam                                     | 1         | 1.79%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1.79%   |
| Suyin Asus Integrated Webcam                        | 1         | 1.79%   |
| Sunplus Dell HD Webcam                              | 1         | 1.79%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 1.79%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.79%   |
| Realtek VGA WebCam                                  | 1         | 1.79%   |
| Realtek HP Wide Vision HD Camera                    | 1         | 1.79%   |
| Quanta ov9734_techfront_camera                      | 1         | 1.79%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.79%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc]          | 1         | 1.79%   |
| Microdia Sonix Integrated Webcam                    | 1         | 1.79%   |
| Microdia Integrated Webcam HD                       | 1         | 1.79%   |
| Importek TOSHIBA Web Camera - HD                    | 1         | 1.79%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.79%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 1.79%   |
| Chicony Integrated IR Camera                        | 1         | 1.79%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 1.79%   |
| Chicony HP TrueVision HD                            | 1         | 1.79%   |
| Chicony HD Webcam                                   | 1         | 1.79%   |
| Chicony HD User Facing                              | 1         | 1.79%   |
| Chicony CNFA078                                     | 1         | 1.79%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 1.79%   |
| Chicony 4-Port Hub                                  | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 1.79%   |
| Apple FaceTime HD Camera                            | 1         | 1.79%   |
| Acer Lenovo EasyCamera                              | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 30%     |
| Shenzhen Goodix Technology | 3         | 30%     |
| Synaptics                  | 2         | 20%     |
| LighTuning Technology      | 1         | 10%     |
| AuthenTec                  | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                        | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 10%     |
| Validity Sensors Fingerprint scanner                       | 1         | 10%     |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 10%     |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 10%     |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 10%     |

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
| 0     | 36        | 56.25%  |
| 1     | 24        | 37.5%   |
| 2     | 3         | 4.69%   |
| 3     | 1         | 1.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 33.33%  |
| Graphics card         | 8         | 26.67%  |
| Chipcard              | 7         | 23.33%  |
| Net/wireless          | 2         | 6.67%   |
| Multimedia controller | 2         | 6.67%   |
| Camera                | 1         | 3.33%   |

