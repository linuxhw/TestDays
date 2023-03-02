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

Total: 81

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T530 24296HG       | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | TP300UA                     | [22ff7f5827](https://linux-hardware.org/?probe=22ff7f5827) | Feb 20, 2023 |
| Dell          | Latitude 5511               | [05e11b64d6](https://linux-hardware.org/?probe=05e11b64d6) | Feb 09, 2023 |
| Apple         | MacBookPro8,2               | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
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
| Ubuntu Studio 20.04 | 38        | 55.88%  |
| Ubuntu Studio 22.04 | 14        | 20.59%  |
| Ubuntu Studio 22.10 | 4         | 5.88%   |
| Ubuntu Studio 21.10 | 3         | 4.41%   |
| Ubuntu Studio 21.04 | 3         | 4.41%   |
| Ubuntu Studio 20.10 | 3         | 4.41%   |
| Ubuntu Studio 18.04 | 2         | 2.94%   |
| Ubuntu Studio 19.10 | 1         | 1.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 67        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-52-lowlatency     | 3         | 4.29%   |
| 5.15.0-56-lowlatency    | 3         | 4.29%   |
| 5.15.0-47-lowlatency    | 3         | 4.29%   |
| 5.13.0-28-lowlatency    | 3         | 4.29%   |
| 5.8.0-55-lowlatency     | 2         | 2.86%   |
| 5.4.0-94-lowlatency     | 2         | 2.86%   |
| 5.4.0-65-lowlatency     | 2         | 2.86%   |
| 5.4.0-45-lowlatency     | 2         | 2.86%   |
| 5.4.0-42-lowlatency     | 2         | 2.86%   |
| 5.19.0-1015-lowlatency  | 2         | 2.86%   |
| 5.15.0-50-lowlatency    | 2         | 2.86%   |
| 5.15.0-48-lowlatency    | 2         | 2.86%   |
| 5.15.0-46-lowlatency    | 2         | 2.86%   |
| 5.13.0-30-lowlatency    | 2         | 2.86%   |
| 5.11.0-34-lowlatency    | 2         | 2.86%   |
| 5.11.0-27-lowlatency    | 2         | 2.86%   |
| 5.8.0-59-lowlatency     | 1         | 1.43%   |
| 5.8.0-50-lowlatency     | 1         | 1.43%   |
| 5.8.0-44-lowlatency     | 1         | 1.43%   |
| 5.8.0-43-lowlatency     | 1         | 1.43%   |
| 5.8.0-34-generic        | 1         | 1.43%   |
| 5.8.0-29-lowlatency     | 1         | 1.43%   |
| 5.8.0-25-lowlatency     | 1         | 1.43%   |
| 5.7.6-050706-lowlatency | 1         | 1.43%   |
| 5.7.6-050706-generic    | 1         | 1.43%   |
| 5.4.0-96-lowlatency     | 1         | 1.43%   |
| 5.4.0-88-lowlatency     | 1         | 1.43%   |
| 5.4.0-52-generic        | 1         | 1.43%   |
| 5.4.0-45-generic        | 1         | 1.43%   |
| 5.4.0-34-lowlatency     | 1         | 1.43%   |
| 5.4.0-26-lowlatency     | 1         | 1.43%   |
| 5.4.0-132-lowlatency    | 1         | 1.43%   |
| 5.4.0-107-lowlatency    | 1         | 1.43%   |
| 5.4.0-100-lowlatency    | 1         | 1.43%   |
| 5.3.0-19-lowlatency     | 1         | 1.43%   |
| 5.19.0-1017-lowlatency  | 1         | 1.43%   |
| 5.19.0-1007-lowlatency  | 1         | 1.43%   |
| 5.15.0-60-lowlatency    | 1         | 1.43%   |
| 5.15.0-52-lowlatency    | 1         | 1.43%   |
| 5.15.0-40-lowlatency    | 1         | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 29.41%  |
| 5.15.0  | 16        | 23.53%  |
| 5.8.0   | 9         | 13.24%  |
| 5.11.0  | 9         | 13.24%  |
| 5.13.0  | 6         | 8.82%   |
| 5.19.0  | 4         | 5.88%   |
| 4.15.0  | 2         | 2.94%   |
| 5.7.6   | 1         | 1.47%   |
| 5.3.0   | 1         | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 20        | 29.41%  |
| 5.15    | 16        | 23.53%  |
| 5.8     | 9         | 13.24%  |
| 5.11    | 9         | 13.24%  |
| 5.13    | 6         | 8.82%   |
| 5.19    | 4         | 5.88%   |
| 4.15    | 2         | 2.94%   |
| 5.7     | 1         | 1.47%   |
| 5.3     | 1         | 1.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 67        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 37        | 55.22%  |
| KDE5  | 24        | 35.82%  |
| GNOME | 5         | 7.46%   |
| LXQt  | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 64        | 95.52%  |
| Wayland | 3         | 4.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 21        | 31.34%  |
| SDDM    | 20        | 29.85%  |
| LightDM | 20        | 29.85%  |
| GDM     | 5         | 7.46%   |
| LXDM    | 1         | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 28        | 41.18%  |
| fr_FR   | 12        | 17.65%  |
| C       | 4         | 5.88%   |
| ru_RU   | 2         | 2.94%   |
| pt_BR   | 2         | 2.94%   |
| it_IT   | 2         | 2.94%   |
| es_ES   | 2         | 2.94%   |
| en_GB   | 2         | 2.94%   |
| en_CA   | 2         | 2.94%   |
| de_DE   | 2         | 2.94%   |
| Unknown | 2         | 2.94%   |
| nl_NL   | 1         | 1.47%   |
| hu_HU   | 1         | 1.47%   |
| es_NI   | 1         | 1.47%   |
| es_CR   | 1         | 1.47%   |
| en_NG   | 1         | 1.47%   |
| en_IE   | 1         | 1.47%   |
| en_AG   | 1         | 1.47%   |
| de_CH   | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 44        | 65.67%  |
| BIOS | 23        | 34.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 63        | 94.03%  |
| Overlay | 4         | 5.97%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 47        | 70.15%  |
| MBR  | 20        | 29.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 86.76%  |
| Yes       | 9         | 13.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 50.75%  |
| No        | 33        | 49.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 17        | 25.37%  |
| Dell                   | 12        | 17.91%  |
| Hewlett-Packard        | 11        | 16.42%  |
| ASUSTek Computer       | 9         | 13.43%  |
| Acer                   | 3         | 4.48%   |
| Toshiba                | 2         | 2.99%   |
| HUAWEI                 | 2         | 2.99%   |
| Apple                  | 2         | 2.99%   |
| Sony                   | 1         | 1.49%   |
| Samsung Electronics    | 1         | 1.49%   |
| Razer                  | 1         | 1.49%   |
| Intel Client Systems   | 1         | 1.49%   |
| Google                 | 1         | 1.49%   |
| Gigabyte Technology    | 1         | 1.49%   |
| Getac                  | 1         | 1.49%   |
| Clevo                  | 1         | 1.49%   |
| Avell High Performance | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G50-45 80E3                       | 2         | 2.99%   |
| HP Pavilion dv6                          | 2         | 2.99%   |
| Toshiba Satellite L755D                  | 1         | 1.49%   |
| Toshiba Satellite C855                   | 1         | 1.49%   |
| Sony VGN-NS31M_W                         | 1         | 1.49%   |
| Samsung 305V4A/305V5A                    | 1         | 1.49%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 1.49%   |
| Lenovo ThinkPad X230 2333A86             | 1         | 1.49%   |
| Lenovo ThinkPad X230 2325AJG             | 1         | 1.49%   |
| Lenovo ThinkPad X230 23245S1             | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 1.49%   |
| Lenovo ThinkPad W530 2447IG0             | 1         | 1.49%   |
| Lenovo ThinkPad T530 24296HG             | 1         | 1.49%   |
| Lenovo ThinkPad T520 4243K86             | 1         | 1.49%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.49%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 1.49%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 1.49%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 1.49%   |
| Lenovo IdeaPad 3 15ABA7 82RN             | 1         | 1.49%   |
| Lenovo IdeaPad 3 14ARE05 81W3            | 1         | 1.49%   |
| Lenovo G70-80 80FF                       | 1         | 1.49%   |
| Intel Client Systems LAPBC510            | 1         | 1.49%   |
| HUAWEI KLVL-WXXW                         | 1         | 1.49%   |
| HUAWEI HLYL-WXX9                         | 1         | 1.49%   |
| HP ZBook 15 G3                           | 1         | 1.49%   |
| HP Stream Laptop 14-cb0XX                | 1         | 1.49%   |
| HP Sona                                  | 1         | 1.49%   |
| HP OMEN by Laptop 15-ce0xx               | 1         | 1.49%   |
| HP Notebook                              | 1         | 1.49%   |
| HP Laptop 15s-fq1xxx                     | 1         | 1.49%   |
| HP EliteBook 840 G3                      | 1         | 1.49%   |
| HP EliteBook 735 G6                      | 1         | 1.49%   |
| HP Compaq 8510p                          | 1         | 1.49%   |
| Google Nami                              | 1         | 1.49%   |
| Gigabyte AERO 15-X9                      | 1         | 1.49%   |
| Getac S400G3                             | 1         | 1.49%   |
| Dell XPS 15 9570                         | 1         | 1.49%   |
| Dell Precision M4500                     | 1         | 1.49%   |
| Dell Latitude E7250                      | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 8         | 11.94%  |
| Lenovo IdeaPad                | 5         | 7.46%   |
| Dell Latitude                 | 5         | 7.46%   |
| Dell Inspiron                 | 5         | 7.46%   |
| Toshiba Satellite             | 2         | 2.99%   |
| Lenovo G50-45                 | 2         | 2.99%   |
| HP Pavilion                   | 2         | 2.99%   |
| HP EliteBook                  | 2         | 2.99%   |
| Acer Aspire                   | 2         | 2.99%   |
| Sony VGN-NS31M                | 1         | 1.49%   |
| Samsung 305V4A                | 1         | 1.49%   |
| Razer Blade                   | 1         | 1.49%   |
| Lenovo Legion                 | 1         | 1.49%   |
| Lenovo G70-80                 | 1         | 1.49%   |
| Intel Client Systems LAPBC510 | 1         | 1.49%   |
| HUAWEI KLVL-WXXW              | 1         | 1.49%   |
| HUAWEI HLYL-WXX9              | 1         | 1.49%   |
| HP ZBook                      | 1         | 1.49%   |
| HP Stream                     | 1         | 1.49%   |
| HP Sona                       | 1         | 1.49%   |
| HP OMEN                       | 1         | 1.49%   |
| HP Notebook                   | 1         | 1.49%   |
| HP Laptop                     | 1         | 1.49%   |
| HP Compaq                     | 1         | 1.49%   |
| Google Nami                   | 1         | 1.49%   |
| Gigabyte AERO                 | 1         | 1.49%   |
| Getac S400G3                  | 1         | 1.49%   |
| Dell XPS                      | 1         | 1.49%   |
| Dell Precision                | 1         | 1.49%   |
| Clevo W35                     | 1         | 1.49%   |
| Avell High Performance Avell  | 1         | 1.49%   |
| ASUS X541NA                   | 1         | 1.49%   |
| ASUS VivoBook                 | 1         | 1.49%   |
| ASUS UX305FA                  | 1         | 1.49%   |
| ASUS U56E                     | 1         | 1.49%   |
| ASUS TP300UA                  | 1         | 1.49%   |
| ASUS ROG                      | 1         | 1.49%   |
| ASUS K53U                     | 1         | 1.49%   |
| ASUS GL503VD                  | 1         | 1.49%   |
| ASUS ASUS                     | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 9         | 13.43%  |
| 2012 | 9         | 13.43%  |
| 2014 | 7         | 10.45%  |
| 2019 | 6         | 8.96%   |
| 2011 | 6         | 8.96%   |
| 2016 | 5         | 7.46%   |
| 2021 | 4         | 5.97%   |
| 2018 | 4         | 5.97%   |
| 2017 | 4         | 5.97%   |
| 2008 | 4         | 5.97%   |
| 2015 | 3         | 4.48%   |
| 2010 | 2         | 2.99%   |
| 2007 | 2         | 2.99%   |
| 2022 | 1         | 1.49%   |
| 2009 | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 67        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 59        | 88.06%  |
| Enabled  | 8         | 11.94%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 65        | 97.01%  |
| Yes  | 2         | 2.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 27        | 39.71%  |
| 16.01-24.0 | 12        | 17.65%  |
| 8.01-16.0  | 12        | 17.65%  |
| 3.01-4.0   | 8         | 11.76%  |
| 32.01-64.0 | 4         | 5.88%   |
| 24.01-32.0 | 2         | 2.94%   |
| 2.01-3.0   | 2         | 2.94%   |
| 1.01-2.0   | 1         | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 25        | 35.71%  |
| 2.01-3.0  | 18        | 25.71%  |
| 3.01-4.0  | 13        | 18.57%  |
| 4.01-8.0  | 11        | 15.71%  |
| 8.01-16.0 | 2         | 2.86%   |
| 0.51-1.0  | 1         | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 72.06%  |
| 2      | 16        | 23.53%  |
| 0      | 2         | 2.94%   |
| 4      | 1         | 1.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 64.71%  |
| Yes       | 24        | 35.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 80.6%   |
| No        | 13        | 19.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 98.51%  |
| No        | 1         | 1.49%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 77.61%  |
| No        | 15        | 22.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 17.91%  |
| France      | 11        | 16.42%  |
| Germany     | 6         | 8.96%   |
| Russia      | 4         | 5.97%   |
| Canada      | 4         | 5.97%   |
| UK          | 3         | 4.48%   |
| Spain       | 3         | 4.48%   |
| Italy       | 3         | 4.48%   |
| Netherlands | 2         | 2.99%   |
| Costa Rica  | 2         | 2.99%   |
| Brazil      | 2         | 2.99%   |
| Yemen       | 1         | 1.49%   |
| Turkey      | 1         | 1.49%   |
| Taiwan      | 1         | 1.49%   |
| Switzerland | 1         | 1.49%   |
| Poland      | 1         | 1.49%   |
| Norway      | 1         | 1.49%   |
| Nigeria     | 1         | 1.49%   |
| Nicaragua   | 1         | 1.49%   |
| Mexico      | 1         | 1.49%   |
| Ivory Coast | 1         | 1.49%   |
| Indonesia   | 1         | 1.49%   |
| Hungary     | 1         | 1.49%   |
| Finland     | 1         | 1.49%   |
| Bulgaria    | 1         | 1.49%   |
| Austria     | 1         | 1.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Montreal       | 2         | 2.94%   |
| Madrid         | 2         | 2.94%   |
| Groningen      | 2         | 2.94%   |
| Denver         | 2         | 2.94%   |
| Béziers       | 2         | 2.94%   |
| Yekaterinburg  | 1         | 1.47%   |
| Wroclaw        | 1         | 1.47%   |
| Woonsocket     | 1         | 1.47%   |
| Woodland Park  | 1         | 1.47%   |
| Vienna         | 1         | 1.47%   |
| Velleron       | 1         | 1.47%   |
| Turin          | 1         | 1.47%   |
| Tarragona      | 1         | 1.47%   |
| Taipei         | 1         | 1.47%   |
| Sunderland     | 1         | 1.47%   |
| Stuttgart      | 1         | 1.47%   |
| Stabekk        | 1         | 1.47%   |
| St Petersburg  | 1         | 1.47%   |
| Sofia          | 1         | 1.47%   |
| Sleman         | 1         | 1.47%   |
| Seropedica     | 1         | 1.47%   |
| Sanaa          | 1         | 1.47%   |
| San Juan       | 1         | 1.47%   |
| Samara         | 1         | 1.47%   |
| Rio de Janeiro | 1         | 1.47%   |
| Ramsgate       | 1         | 1.47%   |
| Ragusa         | 1         | 1.47%   |
| Portland       | 1         | 1.47%   |
| Port Harcourt  | 1         | 1.47%   |
| Phoenix        | 1         | 1.47%   |
| Nudlingen      | 1         | 1.47%   |
| Moscow         | 1         | 1.47%   |
| Mississauga    | 1         | 1.47%   |
| Mexico City    | 1         | 1.47%   |
| Mannheim       | 1         | 1.47%   |
| Managua        | 1         | 1.47%   |
| Madison        | 1         | 1.47%   |
| Ludwigsburg    | 1         | 1.47%   |
| Lindsay        | 1         | 1.47%   |
| Lille          | 1         | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 14        | 14     | 17.07%  |
| WDC                         | 10        | 10     | 12.2%   |
| SanDisk                     | 7         | 7      | 8.54%   |
| Toshiba                     | 6         | 6      | 7.32%   |
| Unknown                     | 4         | 4      | 4.88%   |
| SK hynix                    | 4         | 5      | 4.88%   |
| Seagate                     | 4         | 4      | 4.88%   |
| Intel                       | 4         | 6      | 4.88%   |
| Kingston                    | 3         | 3      | 3.66%   |
| Phison                      | 2         | 2      | 2.44%   |
| Micron Technology           | 2         | 2      | 2.44%   |
| Hitachi                     | 2         | 2      | 2.44%   |
| Crucial                     | 2         | 2      | 2.44%   |
| Union Memory                | 1         | 1      | 1.22%   |
| UMIS                        | 1         | 1      | 1.22%   |
| Team                        | 1         | 1      | 1.22%   |
| SPCC                        | 1         | 1      | 1.22%   |
| Reeinno                     | 1         | 1      | 1.22%   |
| Realtek                     | 1         | 1      | 1.22%   |
| PNY                         | 1         | 1      | 1.22%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.22%   |
| KIOXIA                      | 1         | 1      | 1.22%   |
| KingSpec                    | 1         | 1      | 1.22%   |
| JMicron Technology          | 1         | 1      | 1.22%   |
| Inateck                     | 1         | 1      | 1.22%   |
| HGST                        | 1         | 1      | 1.22%   |
| Fujitsu                     | 1         | 1      | 1.22%   |
| China                       | 1         | 1      | 1.22%   |
| BHT                         | 1         | 1      | 1.22%   |
| ASMT                        | 1         | 1      | 1.22%   |
| Unknown                     | 1         | 1      | 1.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 2.41%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 2.41%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 2.41%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 2.41%   |
| Samsung SSD 870 EVO 1TB                   | 2         | 2.41%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 2.41%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 2.41%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 1.2%    |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 1.2%    |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 1.2%    |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 1.2%    |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 1.2%    |
| WDC WD3200BEKT-60V5T1 320GB               | 1         | 1.2%    |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 1.2%    |
| WDC WD10JPVT-75A1YT0 1TB                  | 1         | 1.2%    |
| Unknown MMC Card  4GB                     | 1         | 1.2%    |
| Unknown MMC Card  16GB                    | 1         | 1.2%    |
| Unknown DA4128  128GB                     | 1         | 1.2%    |
| Unknown 032G34  32GB                      | 1         | 1.2%    |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB   | 1         | 1.2%    |
| UMIS RPJTJ256MEE1OWX 256GB                | 1         | 1.2%    |
| Toshiba TR150 240GB SSD                   | 1         | 1.2%    |
| Toshiba MK1637GSX 160GB                   | 1         | 1.2%    |
| Team TM8FP4001T 1TB                       | 1         | 1.2%    |
| SPCC Solid State Disk 1TB                 | 1         | 1.2%    |
| SK hynix SKHynix_HFS256GD9TNI-L2A0B 256GB | 1         | 1.2%    |
| SK hynix BC501 NVMe 256GB                 | 1         | 1.2%    |
| Seagate ST9320320AS 320GB                 | 1         | 1.2%    |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 1.2%    |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.2%    |
| Seagate FireCuda 530 ZP4000GM30013 4TB    | 1         | 1.2%    |
| SanDisk SSD PLUS 240GB                    | 1         | 1.2%    |
| SanDisk SD9SN8W128G1002 128GB SSD         | 1         | 1.2%    |
| SanDisk SD8SN8U256G1002 256GB SSD         | 1         | 1.2%    |
| SanDisk SD7SN3Q128G1002 128GB SSD         | 1         | 1.2%    |
| SanDisk Extreme SSD 500GB                 | 1         | 1.2%    |
| SanDisk DF4064  64GB                      | 1         | 1.2%    |
| SanDisk DF4032  32GB                      | 1         | 1.2%    |
| Samsung SSD PM851 mSATA 256GB             | 1         | 1.2%    |
| Samsung SSD 970 PRO 1TB                   | 1         | 1.2%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 27.27%  |
| Toshiba             | 5         | 5      | 22.73%  |
| Seagate             | 3         | 3      | 13.64%  |
| Samsung Electronics | 2         | 2      | 9.09%   |
| Hitachi             | 2         | 2      | 9.09%   |
| JMicron Technology  | 1         | 1      | 4.55%   |
| HGST                | 1         | 1      | 4.55%   |
| Fujitsu             | 1         | 1      | 4.55%   |
| ASMT                | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 28.57%  |
| SanDisk             | 5         | 5      | 17.86%  |
| Kingston            | 2         | 2      | 7.14%   |
| Crucial             | 2         | 2      | 7.14%   |
| WDC                 | 1         | 1      | 3.57%   |
| Toshiba             | 1         | 1      | 3.57%   |
| SPCC                | 1         | 1      | 3.57%   |
| Reeinno             | 1         | 1      | 3.57%   |
| PNY                 | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 1      | 3.57%   |
| KingSpec            | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| Inateck             | 1         | 1      | 3.57%   |
| China               | 1         | 1      | 3.57%   |
| BHT                 | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 24        | 28     | 33.33%  |
| NVMe | 21        | 28     | 29.17%  |
| HDD  | 21        | 22     | 29.17%  |
| MMC  | 6         | 7      | 8.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 46     | 56.16%  |
| NVMe | 21        | 27     | 28.77%  |
| MMC  | 6         | 7      | 8.22%   |
| SAS  | 5         | 5      | 6.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 37     | 72.34%  |
| 0.51-1.0   | 11        | 11     | 23.4%   |
| 2.01-3.0   | 1         | 1      | 2.13%   |
| 1.01-2.0   | 1         | 1      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 21        | 30.43%  |
| 251-500    | 17        | 24.64%  |
| 501-1000   | 10        | 14.49%  |
| 21-50      | 7         | 10.14%  |
| 51-100     | 7         | 10.14%  |
| 1-20       | 4         | 5.8%    |
| 1001-2000  | 2         | 2.9%    |
| 2001-3000  | 1         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 27        | 39.13%  |
| 21-50     | 13        | 18.84%  |
| 101-250   | 10        | 14.49%  |
| 251-500   | 7         | 10.14%  |
| 51-100    | 6         | 8.7%    |
| 501-1000  | 4         | 5.8%    |
| 1001-2000 | 2         | 2.9%    |

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
| Works    | 47        | 59     | 65.28%  |
| Malfunc  | 16        | 16     | 22.22%  |
| Detected | 9         | 10     | 12.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 47        | 58.75%  |
| AMD                         | 12        | 15%     |
| SK hynix                    | 4         | 5%      |
| Samsung Electronics         | 4         | 5%      |
| SanDisk                     | 3         | 3.75%   |
| Phison Electronics          | 3         | 3.75%   |
| Union Memory (Shenzhen)     | 2         | 2.5%    |
| Seagate Technology          | 1         | 1.25%   |
| Micron Technology           | 1         | 1.25%   |
| MAXIO Technology (Hangzhou) | 1         | 1.25%   |
| KIOXIA                      | 1         | 1.25%   |
| Kingston Technology Company | 1         | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 11.63%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 8.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 6.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 5.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 5.81%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 3.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 3.49%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 2.33%   |
| SK hynix BC511                                                                 | 2         | 2.33%   |
| Phison E12 NVMe Controller                                                     | 2         | 2.33%   |
| Intel Non-Volatile memory controller                                           | 2         | 2.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 2.33%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 1.16%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.16%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 1.16%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.16%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.16%   |
| Micron Non-Volatile memory controller                                          | 1         | 1.16%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 1.16%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.16%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.16%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.16%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.16%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                    | 1         | 1.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.16%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.16%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 48        | 60%     |
| NVMe | 21        | 26.25%  |
| RAID | 7         | 8.75%   |
| IDE  | 4         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 77.61%  |
| AMD    | 15        | 22.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-2450M CPU @ 2.50GHz      | 3         | 4.48%   |
| AMD Ryzen 5 4600H with Radeon Graphics | 3         | 4.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 2.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 2         | 2.99%   |
| Intel Processor 5Y10 CPU @ 0.80GHz     | 1         | 1.49%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.49%   |
| Intel Genuine CPU U2300 @ 1.20GHz      | 1         | 1.49%   |
| Intel Core i9-8950HK CPU @ 2.90GHz     | 1         | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 1.49%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 1         | 1.49%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 1         | 1.49%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 1.49%   |
| Intel Core i7-5600U CPU @ 2.60GHz      | 1         | 1.49%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.49%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz     | 1         | 1.49%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1         | 1.49%   |
| Intel Core i7-3940XM CPU @ 3.00GHz     | 1         | 1.49%   |
| Intel Core i7-3630QM CPU @ 2.40GHz     | 1         | 1.49%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 1         | 1.49%   |
| Intel Core i7-2635QM CPU @ 2.00GHz     | 1         | 1.49%   |
| Intel Core i7-2630QM CPU @ 2.00GHz     | 1         | 1.49%   |
| Intel Core i7-10850H CPU @ 2.70GHz     | 1         | 1.49%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 1.49%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz      | 1         | 1.49%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 1         | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.49%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.49%   |
| Intel Core i5-4310M CPU @ 2.70GHz      | 1         | 1.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.49%   |
| Intel Core i5-3340M CPU @ 2.70GHz      | 1         | 1.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 1         | 1.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz      | 1         | 1.49%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 1         | 1.49%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz     | 1         | 1.49%   |
| Intel Core i5-10300H CPU @ 2.50GHz     | 1         | 1.49%   |
| Intel Core i5 CPU M 460 @ 2.53GHz      | 1         | 1.49%   |
| Intel Core i3-8130U CPU @ 2.20GHz      | 1         | 1.49%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 1         | 1.49%   |
| Intel Core i3-5005U CPU @ 2.00GHz      | 1         | 1.49%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz   | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 20        | 29.85%  |
| Intel Core i5      | 15        | 22.39%  |
| Intel Core 2 Duo   | 4         | 5.97%   |
| Intel Celeron      | 4         | 5.97%   |
| AMD Ryzen 5        | 4         | 5.97%   |
| Other              | 3         | 4.48%   |
| Intel Core i3      | 3         | 4.48%   |
| AMD Ryzen 7        | 3         | 4.48%   |
| AMD E              | 2         | 2.99%   |
| Intel Pentium Dual | 1         | 1.49%   |
| Intel Genuine      | 1         | 1.49%   |
| Intel Core i9      | 1         | 1.49%   |
| AMD Ryzen 3 PRO    | 1         | 1.49%   |
| AMD Ryzen 3        | 1         | 1.49%   |
| AMD E2             | 1         | 1.49%   |
| AMD E1             | 1         | 1.49%   |
| AMD A6             | 1         | 1.49%   |
| AMD A4             | 1         | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 34        | 50.75%  |
| 4      | 22        | 32.84%  |
| 6      | 8         | 11.94%  |
| 8      | 3         | 4.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 46        | 68.66%  |
| 1      | 21        | 31.34%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 67        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 7         | 10.29%  |
| 0x306a9    | 6         | 8.82%   |
| Unknown    | 5         | 7.35%   |
| 0x306d4    | 4         | 5.88%   |
| 0x08600104 | 4         | 5.88%   |
| 0x906ea    | 3         | 4.41%   |
| 0x806ea    | 3         | 4.41%   |
| 0x406e3    | 3         | 4.41%   |
| 0xa0652    | 2         | 2.94%   |
| 0x906e9    | 2         | 2.94%   |
| 0x806c1    | 2         | 2.94%   |
| 0x706e5    | 2         | 2.94%   |
| 0x6fd      | 2         | 2.94%   |
| 0x40651    | 2         | 2.94%   |
| 0x07030105 | 2         | 2.94%   |
| 0x706a1    | 1         | 1.47%   |
| 0x6fb      | 1         | 1.47%   |
| 0x506e3    | 1         | 1.47%   |
| 0x506c9    | 1         | 1.47%   |
| 0x406c4    | 1         | 1.47%   |
| 0x40661    | 1         | 1.47%   |
| 0x306c3    | 1         | 1.47%   |
| 0x106e5    | 1         | 1.47%   |
| 0x1067a    | 1         | 1.47%   |
| 0x10676    | 1         | 1.47%   |
| 0x0a50000c | 1         | 1.47%   |
| 0x08608102 | 1         | 1.47%   |
| 0x08600106 | 1         | 1.47%   |
| 0x08600103 | 1         | 1.47%   |
| 0x08108109 | 1         | 1.47%   |
| 0x07030104 | 1         | 1.47%   |
| 0x0500010d | 1         | 1.47%   |
| 0x05000029 | 1         | 1.47%   |
| 0x03000027 | 1         | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 13.43%  |
| SandyBridge   | 7         | 10.45%  |
| Zen 2         | 6         | 8.96%   |
| IvyBridge     | 6         | 8.96%   |
| Broadwell     | 5         | 7.46%   |
| Skylake       | 4         | 5.97%   |
| Haswell       | 4         | 5.97%   |
| Puma          | 3         | 4.48%   |
| Penryn        | 3         | 4.48%   |
| Core          | 3         | 4.48%   |
| TigerLake     | 2         | 2.99%   |
| IceLake       | 2         | 2.99%   |
| CometLake     | 2         | 2.99%   |
| Bobcat        | 2         | 2.99%   |
| Zen+          | 1         | 1.49%   |
| Zen 3         | 1         | 1.49%   |
| Westmere      | 1         | 1.49%   |
| Silvermont    | 1         | 1.49%   |
| Nehalem       | 1         | 1.49%   |
| K10 Llano     | 1         | 1.49%   |
| Goldmont plus | 1         | 1.49%   |
| Goldmont      | 1         | 1.49%   |
| Unknown       | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 54.65%  |
| AMD    | 20        | 23.26%  |
| Nvidia | 19        | 22.09%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 7.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 6.82%   |
| AMD Renoir                                                                               | 6         | 6.82%   |
| Intel HD Graphics 5500                                                                   | 4         | 4.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 4.55%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.41%   |
| Nvidia TU117M                                                                            | 2         | 2.27%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 2.27%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 2.27%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 2.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.27%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 2.27%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.27%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.14%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 1.14%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.14%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.14%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 1.14%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 1.14%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 1.14%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.14%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 1.14%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 1.14%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.14%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.14%   |
| Intel HD Graphics 630                                                                    | 1         | 1.14%   |
| Intel HD Graphics 5300                                                                   | 1         | 1.14%   |
| Intel HD Graphics 530                                                                    | 1         | 1.14%   |
| Intel HD Graphics 500                                                                    | 1         | 1.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 46.27%  |
| Intel + Nvidia | 14        | 20.9%   |
| 1 x AMD        | 14        | 20.9%   |
| AMD + Nvidia   | 3         | 4.48%   |
| 1 x Nvidia     | 2         | 2.99%   |
| Intel + AMD    | 2         | 2.99%   |
| 2 x AMD        | 1         | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 62        | 92.54%  |
| Proprietary | 5         | 7.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 56.72%  |
| 0.01-0.5   | 9         | 13.43%  |
| 0.51-1.0   | 8         | 11.94%  |
| 1.01-2.0   | 7         | 10.45%  |
| 3.01-4.0   | 3         | 4.48%   |
| 5.01-6.0   | 2         | 2.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 15        | 19.48%  |
| LG Display              | 14        | 18.18%  |
| Samsung Electronics     | 9         | 11.69%  |
| Chimei Innolux          | 9         | 11.69%  |
| BOE                     | 9         | 11.69%  |
| Lenovo                  | 3         | 3.9%    |
| Sharp                   | 2         | 2.6%    |
| Hewlett-Packard         | 2         | 2.6%    |
| Chi Mei Optoelectronics | 2         | 2.6%    |
| Apple                   | 2         | 2.6%    |
| LG Philips              | 1         | 1.3%    |
| Iiyama                  | 1         | 1.3%    |
| Hannspree               | 1         | 1.3%    |
| Dell                    | 1         | 1.3%    |
| CPT                     | 1         | 1.3%    |
| BenQ                    | 1         | 1.3%    |
| ASUSTek Computer        | 1         | 1.3%    |
| Arnos Instruments       | 1         | 1.3%    |
| Ancor Communications    | 1         | 1.3%    |
| Acer                    | 1         | 1.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 2         | 2.6%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 2.6%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 2         | 2.6%    |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch         | 2         | 2.6%    |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 2.6%    |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                 | 1         | 1.3%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                 | 1         | 1.3%    |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch     | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch   | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch    | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch    | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch    | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch    | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 1.3%    |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch            | 1         | 1.3%    |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 1.3%    |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch            | 1         | 1.3%    |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch            | 1         | 1.3%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 1.3%    |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch             | 1         | 1.3%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 1.3%    |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch             | 1         | 1.3%    |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch            | 1         | 1.3%    |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch                | 1         | 1.3%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 1.3%    |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                 | 1         | 1.3%    |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                   | 1         | 1.3%    |
| Hewlett-Packard E242 HWP326F 1920x1200 518x324mm 24.1-inch              | 1         | 1.3%    |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch               | 1         | 1.3%    |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                    | 1         | 1.3%    |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                        | 1         | 1.3%    |
| CPT LCD Monitor CPT141F 1280x800 331x207mm 15.4-inch                    | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch         | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 344x193mm 15.5-inch        | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch         | 1         | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 45.71%  |
| 1366x768 (WXGA)    | 21        | 30%     |
| 1600x900 (HD+)     | 5         | 7.14%   |
| 3840x2160 (4K)     | 3         | 4.29%   |
| 1680x1050 (WSXGA+) | 2         | 2.86%   |
| 1280x800 (WXGA)    | 2         | 2.86%   |
| 2880x1800          | 1         | 1.43%   |
| 2560x1440 (QHD)    | 1         | 1.43%   |
| 2160x1440          | 1         | 1.43%   |
| 1920x1200 (WUXGA)  | 1         | 1.43%   |
| 1440x900 (WXGA+)   | 1         | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 40        | 51.95%  |
| 13     | 10        | 12.99%  |
| 14     | 6         | 7.79%   |
| 24     | 5         | 6.49%   |
| 12     | 4         | 5.19%   |
| 27     | 2         | 2.6%    |
| 21     | 2         | 2.6%    |
| 17     | 2         | 2.6%    |
| 84     | 1         | 1.3%    |
| 23     | 1         | 1.3%    |
| 20     | 1         | 1.3%    |
| 19     | 1         | 1.3%    |
| 18     | 1         | 1.3%    |
| 16     | 1         | 1.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 65.79%  |
| 201-300     | 10        | 13.16%  |
| 501-600     | 7         | 9.21%   |
| 401-500     | 5         | 6.58%   |
| 351-400     | 3         | 3.95%   |
| 1501-2000   | 1         | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 58        | 85.29%  |
| 16/10 | 9         | 13.24%  |
| 3/2   | 1         | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 53.25%  |
| 81-90          | 11        | 14.29%  |
| 71-80          | 5         | 6.49%   |
| 61-70          | 4         | 5.19%   |
| 201-250        | 4         | 5.19%   |
| 251-300        | 3         | 3.9%    |
| 151-200        | 3         | 3.9%    |
| 301-350        | 2         | 2.6%    |
| More than 1000 | 1         | 1.3%    |
| 141-150        | 1         | 1.3%    |
| 131-140        | 1         | 1.3%    |
| 121-130        | 1         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 42.67%  |
| 101-120       | 21        | 28%     |
| 51-100        | 13        | 17.33%  |
| 161-240       | 8         | 10.67%  |
| More than 240 | 1         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 57        | 82.61%  |
| 2     | 11        | 15.94%  |
| 3     | 1         | 1.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 42        | 40%     |
| Realtek Semiconductor             | 35        | 33.33%  |
| Qualcomm Atheros                  | 13        | 12.38%  |
| Broadcom                          | 5         | 4.76%   |
| Ralink                            | 2         | 1.9%    |
| Ericsson Business Mobile Networks | 2         | 1.9%    |
| ASIX Electronics                  | 2         | 1.9%    |
| MediaTek                          | 1         | 0.95%   |
| Marvell Technology Group          | 1         | 0.95%   |
| Huawei Technologies               | 1         | 0.95%   |
| Broadcom Limited                  | 1         | 0.95%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 19        | 14.96%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 7         | 5.51%   |
| Intel Wireless 7265                                                | 6         | 4.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 5         | 3.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 5         | 3.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 4         | 3.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 3         | 2.36%   |
| Intel Wireless 8265 / 8275                                         | 3         | 2.36%   |
| Intel Wireless 7260                                                | 3         | 2.36%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 2.36%   |
| Intel Centrino Ultimate-N 6300                                     | 3         | 2.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 3         | 2.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 2         | 1.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 2         | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.57%   |
| Intel Wireless 8260                                                | 2         | 1.57%   |
| Intel WiFi Link 5100                                               | 2         | 1.57%   |
| Intel Wi-Fi 6 AX201                                                | 2         | 1.57%   |
| Intel 82567LM Gigabit Network Connection                           | 2         | 1.57%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                      | 2         | 1.57%   |
| ASIX AX88179 Gigabit Ethernet                                      | 2         | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 1         | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 1         | 0.79%   |
| Realtek Realtek Network controller                                 | 1         | 0.79%   |
| Realtek 802.11ac NIC                                               | 1         | 0.79%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]   | 1         | 0.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller          | 1         | 0.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 1         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                              | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                         | 1         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                      | 1         | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                           | 1         | 0.79%   |
| MediaTek moto e(6) plus                                            | 1         | 0.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller            | 1         | 0.79%   |
| Intel Wireless-AC 9260                                             | 1         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 59.7%   |
| Realtek Semiconductor | 11        | 16.42%  |
| Qualcomm Atheros      | 9         | 13.43%  |
| Broadcom              | 4         | 5.97%   |
| Ralink                | 2         | 2.99%   |
| Broadcom Limited      | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 6         | 8.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 5         | 7.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 4         | 5.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 3         | 4.41%   |
| Intel Wireless 8265 / 8275                                       | 3         | 4.41%   |
| Intel Wireless 7260                                              | 3         | 4.41%   |
| Intel Wi-Fi 6 AX200                                              | 3         | 4.41%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 4.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 3         | 4.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 2         | 2.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 2.94%   |
| Intel Wireless 8260                                              | 2         | 2.94%   |
| Intel WiFi Link 5100                                             | 2         | 2.94%   |
| Intel Wi-Fi 6 AX201                                              | 2         | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 2.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.47%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1.47%   |
| Realtek Realtek Network controller                               | 1         | 1.47%   |
| Realtek 802.11ac NIC                                             | 1         | 1.47%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1         | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 1.47%   |
| Intel Wireless-AC 9260                                           | 1         | 1.47%   |
| Intel Wireless 3160                                              | 1         | 1.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 1         | 1.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 1         | 1.47%   |
| Intel Centrino Wireless-N 6150                                   | 1         | 1.47%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 1         | 1.47%   |
| Intel Centrino Wireless-N + WiMAX 6150                           | 1         | 1.47%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 1         | 1.47%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                      | 1         | 1.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                   | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 26        | 46.43%  |
| Intel                    | 19        | 33.93%  |
| Qualcomm Atheros         | 5         | 8.93%   |
| Broadcom                 | 2         | 3.57%   |
| ASIX Electronics         | 2         | 3.57%   |
| MediaTek                 | 1         | 1.79%   |
| Marvell Technology Group | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 33.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 12.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.57%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 3.57%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 3.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.79%   |
| MediaTek moto e(6) plus                                           | 1         | 1.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.79%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.79%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.79%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.79%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 53.66%  |
| Ethernet | 54        | 43.9%   |
| Modem    | 3         | 2.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 83.1%   |
| Ethernet | 12        | 16.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 50        | 74.63%  |
| 1     | 17        | 25.37%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 71.64%  |
| Yes  | 19        | 28.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 51.92%  |
| Realtek Semiconductor           | 5         | 9.62%   |
| Broadcom                        | 5         | 9.62%   |
| Qualcomm Atheros Communications | 4         | 7.69%   |
| Realtek                         | 2         | 3.85%   |
| Ralink Technology               | 2         | 3.85%   |
| Lite-On Technology              | 2         | 3.85%   |
| Apple                           | 2         | 3.85%   |
| Hewlett-Packard                 | 1         | 1.92%   |
| Foxconn International           | 1         | 1.92%   |
| Dell                            | 1         | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 15        | 28.85%  |
| Intel AX201 Bluetooth                             | 4         | 7.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 4         | 7.69%   |
| Realtek Bluetooth Radio                           | 3         | 5.77%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 3         | 5.77%   |
| Intel AX200 Bluetooth                             | 3         | 5.77%   |
| Realtek 802.11ac WLAN Adapter                     | 2         | 3.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 3.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 3.85%   |
| Apple Bluetooth Host Controller                   | 2         | 3.85%   |
| Realtek RTL8723B Bluetooth                        | 1         | 1.92%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 1.92%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 1.92%   |
| Ralink CSR BS8510                                 | 1         | 1.92%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 1.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 1.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 1.92%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 1.92%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.92%   |
| Dell Wireless 370 Bluetooth Mini-card             | 1         | 1.92%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 52        | 55.32%  |
| AMD                        | 18        | 19.15%  |
| Nvidia                     | 15        | 15.96%  |
| Yealink Network Technology | 1         | 1.06%   |
| Yamaha                     | 1         | 1.06%   |
| QinHeng Electronics        | 1         | 1.06%   |
| Mackie Designs             | 1         | 1.06%   |
| Logitech                   | 1         | 1.06%   |
| Jieli Technology           | 1         | 1.06%   |
| Focusrite-Novation         | 1         | 1.06%   |
| C-Media Electronics        | 1         | 1.06%   |
| Behringer.......           | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 7.02%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 7.02%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 5.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 5.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 4.39%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 4.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 3.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 3.51%   |
| AMD FCH Azalia Controller                                                  | 4         | 3.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.63%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 2.63%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.75%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.75%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.75%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.75%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.75%   |
| Yealink Network Technology VoIP Phone                                      | 1         | 0.88%   |
| Yamaha Steinberg UR242                                                     | 1         | 0.88%   |
| QinHeng Electronics CH345 MIDI adapter                                     | 1         | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.88%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.88%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.88%   |
| Mackie Designs BIG KNOB STUDIO+                                            | 1         | 0.88%   |
| Logitech 960 Headset                                                       | 1         | 0.88%   |
| Jieli Technology UACDemoV1.0                                               | 1         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 32.5%   |
| SK hynix            | 22        | 27.5%   |
| Micron Technology   | 9         | 11.25%  |
| Kingston            | 8         | 10%     |
| Unknown             | 3         | 3.75%   |
| Timetec             | 2         | 2.5%    |
| Ramaxel Technology  | 2         | 2.5%    |
| Nanya Technology    | 2         | 2.5%    |
| Crucial             | 2         | 2.5%    |
| Transcend           | 1         | 1.25%   |
| G.Skill             | 1         | 1.25%   |
| Corsair             | 1         | 1.25%   |
| Unknown             | 1         | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 3         | 3.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 3.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 3.41%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s         | 3         | 3.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.27%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 2.27%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 2.27%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.27%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 2.27%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s             | 1         | 1.14%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 1.14%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 1.14%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s           | 1         | 1.14%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 1.14%   |
| Timetec RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.14%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.14%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s              | 1         | 1.14%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s         | 1         | 1.14%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.14%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.14%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.14%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.14%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.14%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.14%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 1         | 1.14%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s            | 1         | 1.14%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.14%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 1.14%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.14%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s       | 1         | 1.14%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB DDR4 2400MT/s              | 1         | 1.14%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 1.14%   |
| Samsung RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 1.14%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.14%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 1         | 1.14%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s       | 1         | 1.14%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s     | 1         | 1.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 34        | 48.57%  |
| DDR4   | 24        | 34.29%  |
| DDR2   | 5         | 7.14%   |
| SDRAM  | 3         | 4.29%   |
| LPDDR4 | 2         | 2.86%   |
| LPDDR3 | 2         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 85.71%  |
| Row Of Chips | 8         | 11.43%  |
| Chip         | 1         | 1.43%   |
| Unknown      | 1         | 1.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 34        | 42.5%   |
| 8192  | 25        | 31.25%  |
| 2048  | 10        | 12.5%   |
| 16384 | 7         | 8.75%   |
| 1024  | 3         | 3.75%   |
| 32768 | 1         | 1.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 28        | 38.36%  |
| 3200    | 10        | 13.7%   |
| 2667    | 7         | 9.59%   |
| 1334    | 7         | 9.59%   |
| 2400    | 4         | 5.48%   |
| 2133    | 4         | 5.48%   |
| 1333    | 3         | 4.11%   |
| 667     | 3         | 4.11%   |
| 4267    | 2         | 2.74%   |
| 4199    | 2         | 2.74%   |
| 1639    | 1         | 1.37%   |
| 800     | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

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
| Chicony Electronics                    | 17        | 29.82%  |
| IMC Networks                           | 7         | 12.28%  |
| Sunplus Innovation Technology          | 5         | 8.77%   |
| Suyin                                  | 4         | 7.02%   |
| Realtek Semiconductor                  | 4         | 7.02%   |
| Microdia                               | 4         | 7.02%   |
| Syntek                                 | 3         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.26%   |
| Quanta                                 | 2         | 3.51%   |
| Acer                                   | 2         | 3.51%   |
| ViewQuest Technologies                 | 1         | 1.75%   |
| Silicon Motion                         | 1         | 1.75%   |
| Ricoh                                  | 1         | 1.75%   |
| Philips (or NXP)                       | 1         | 1.75%   |
| Importek                               | 1         | 1.75%   |
| Apple                                  | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 4         | 6.9%    |
| Syntek Integrated Camera                            | 3         | 5.17%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 5.17%   |
| IMC Networks Integrated Camera                      | 3         | 5.17%   |
| Chicony Integrated Camera [ThinkPad]                | 3         | 5.17%   |
| Suyin Asus Integrated Webcam                        | 2         | 3.45%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 3.45%   |
| Sunplus HD WebCam                                   | 2         | 3.45%   |
| Realtek Lenovo EasyCamera                           | 2         | 3.45%   |
| Microdia Integrated_Webcam_HD                       | 2         | 3.45%   |
| Chicony HP HD Camera                                | 2         | 3.45%   |
| ViewQuest Ability GABB Webcam                       | 1         | 1.72%   |
| Suyin HP Webcam                                     | 1         | 1.72%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1.72%   |
| Sunplus Dell HD Webcam                              | 1         | 1.72%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 1.72%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.72%   |
| Realtek VGA WebCam                                  | 1         | 1.72%   |
| Realtek HP Wide Vision HD Camera                    | 1         | 1.72%   |
| Quanta ov9734_techfront_camera                      | 1         | 1.72%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.72%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc]          | 1         | 1.72%   |
| Microdia Sonix Integrated Webcam                    | 1         | 1.72%   |
| Microdia Integrated Webcam HD                       | 1         | 1.72%   |
| Importek TOSHIBA Web Camera - HD                    | 1         | 1.72%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.72%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 1.72%   |
| Chicony Integrated IR Camera                        | 1         | 1.72%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 1.72%   |
| Chicony HP TrueVision HD                            | 1         | 1.72%   |
| Chicony HD Webcam                                   | 1         | 1.72%   |
| Chicony HD User Facing                              | 1         | 1.72%   |
| Chicony CNFA078                                     | 1         | 1.72%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 1.72%   |
| Chicony 4-Port Hub                                  | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 1.72%   |
| Apple FaceTime HD Camera                            | 1         | 1.72%   |
| Acer Lenovo EasyCamera                              | 1         | 1.72%   |

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
| Broadcom    | 4         | 44.44%  |
| Upek        | 3         | 33.33%  |
| Lenovo      | 1         | 11.11%  |
| Alcor Micro | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 22.22%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 38        | 56.72%  |
| 1     | 25        | 37.31%  |
| 2     | 3         | 4.48%   |
| 3     | 1         | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 32.26%  |
| Graphics card         | 8         | 25.81%  |
| Chipcard              | 8         | 25.81%  |
| Net/wireless          | 2         | 6.45%   |
| Multimedia controller | 2         | 6.45%   |
| Camera                | 1         | 3.23%   |

