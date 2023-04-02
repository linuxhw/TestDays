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

Total: 84

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3ce456f3c8](https://linux-hardware.org/?probe=3ce456f3c8) | Mar 25, 2023 |
| Lenovo        | ThinkPad X250 20CL001LMB    | [d78880e600](https://linux-hardware.org/?probe=d78880e600) | Mar 17, 2023 |
| HP            | Pavilion dv8                | [105a616a39](https://linux-hardware.org/?probe=105a616a39) | Mar 14, 2023 |
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
| Ubuntu Studio 20.04 | 38        | 53.52%  |
| Ubuntu Studio 22.04 | 17        | 23.94%  |
| Ubuntu Studio 22.10 | 4         | 5.63%   |
| Ubuntu Studio 21.10 | 3         | 4.23%   |
| Ubuntu Studio 21.04 | 3         | 4.23%   |
| Ubuntu Studio 20.10 | 3         | 4.23%   |
| Ubuntu Studio 18.04 | 2         | 2.82%   |
| Ubuntu Studio 19.10 | 1         | 1.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 70        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-52-lowlatency     | 3         | 4.11%   |
| 5.15.0-56-lowlatency    | 3         | 4.11%   |
| 5.15.0-47-lowlatency    | 3         | 4.11%   |
| 5.13.0-28-lowlatency    | 3         | 4.11%   |
| 5.8.0-55-lowlatency     | 2         | 2.74%   |
| 5.4.0-94-lowlatency     | 2         | 2.74%   |
| 5.4.0-65-lowlatency     | 2         | 2.74%   |
| 5.4.0-45-lowlatency     | 2         | 2.74%   |
| 5.4.0-42-lowlatency     | 2         | 2.74%   |
| 5.19.0-1015-lowlatency  | 2         | 2.74%   |
| 5.15.0-67-lowlatency    | 2         | 2.74%   |
| 5.15.0-50-lowlatency    | 2         | 2.74%   |
| 5.15.0-48-lowlatency    | 2         | 2.74%   |
| 5.15.0-46-lowlatency    | 2         | 2.74%   |
| 5.13.0-30-lowlatency    | 2         | 2.74%   |
| 5.11.0-34-lowlatency    | 2         | 2.74%   |
| 5.11.0-27-lowlatency    | 2         | 2.74%   |
| 6.2.8-x64v3-xanmod1     | 1         | 1.37%   |
| 5.8.0-59-lowlatency     | 1         | 1.37%   |
| 5.8.0-50-lowlatency     | 1         | 1.37%   |
| 5.8.0-44-lowlatency     | 1         | 1.37%   |
| 5.8.0-43-lowlatency     | 1         | 1.37%   |
| 5.8.0-34-generic        | 1         | 1.37%   |
| 5.8.0-29-lowlatency     | 1         | 1.37%   |
| 5.8.0-25-lowlatency     | 1         | 1.37%   |
| 5.7.6-050706-lowlatency | 1         | 1.37%   |
| 5.7.6-050706-generic    | 1         | 1.37%   |
| 5.4.0-96-lowlatency     | 1         | 1.37%   |
| 5.4.0-88-lowlatency     | 1         | 1.37%   |
| 5.4.0-52-generic        | 1         | 1.37%   |
| 5.4.0-45-generic        | 1         | 1.37%   |
| 5.4.0-34-lowlatency     | 1         | 1.37%   |
| 5.4.0-26-lowlatency     | 1         | 1.37%   |
| 5.4.0-132-lowlatency    | 1         | 1.37%   |
| 5.4.0-107-lowlatency    | 1         | 1.37%   |
| 5.4.0-100-lowlatency    | 1         | 1.37%   |
| 5.3.0-19-lowlatency     | 1         | 1.37%   |
| 5.19.0-1017-lowlatency  | 1         | 1.37%   |
| 5.19.0-1007-lowlatency  | 1         | 1.37%   |
| 5.15.0-60-lowlatency    | 1         | 1.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 28.17%  |
| 5.15.0  | 18        | 25.35%  |
| 5.8.0   | 9         | 12.68%  |
| 5.11.0  | 9         | 12.68%  |
| 5.13.0  | 6         | 8.45%   |
| 5.19.0  | 4         | 5.63%   |
| 4.15.0  | 2         | 2.82%   |
| 6.2.8   | 1         | 1.41%   |
| 5.7.6   | 1         | 1.41%   |
| 5.3.0   | 1         | 1.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 20        | 28.17%  |
| 5.15    | 18        | 25.35%  |
| 5.8     | 9         | 12.68%  |
| 5.11    | 9         | 12.68%  |
| 5.13    | 6         | 8.45%   |
| 5.19    | 4         | 5.63%   |
| 4.15    | 2         | 2.82%   |
| 6.2     | 1         | 1.41%   |
| 5.7     | 1         | 1.41%   |
| 5.3     | 1         | 1.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 70        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 37        | 52.86%  |
| KDE5  | 27        | 38.57%  |
| GNOME | 5         | 7.14%   |
| LXQt  | 1         | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 67        | 95.71%  |
| Wayland | 3         | 4.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 22        | 31.43%  |
| TDM     | 21        | 30%     |
| LightDM | 21        | 30%     |
| GDM     | 5         | 7.14%   |
| LXDM    | 1         | 1.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 29        | 40.85%  |
| fr_FR   | 13        | 18.31%  |
| C       | 4         | 5.63%   |
| de_DE   | 3         | 4.23%   |
| ru_RU   | 2         | 2.82%   |
| pt_BR   | 2         | 2.82%   |
| it_IT   | 2         | 2.82%   |
| es_ES   | 2         | 2.82%   |
| en_GB   | 2         | 2.82%   |
| en_CA   | 2         | 2.82%   |
| Unknown | 2         | 2.82%   |
| nl_NL   | 1         | 1.41%   |
| hu_HU   | 1         | 1.41%   |
| es_NI   | 1         | 1.41%   |
| es_CR   | 1         | 1.41%   |
| en_NG   | 1         | 1.41%   |
| en_IE   | 1         | 1.41%   |
| en_AG   | 1         | 1.41%   |
| de_CH   | 1         | 1.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 46        | 65.71%  |
| BIOS | 24        | 34.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 66        | 94.29%  |
| Overlay | 4         | 5.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 49        | 70%     |
| MBR  | 21        | 30%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 87.32%  |
| Yes       | 9         | 12.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 52.86%  |
| No        | 33        | 47.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 19        | 27.14%  |
| Hewlett-Packard        | 12        | 17.14%  |
| Dell                   | 12        | 17.14%  |
| ASUSTek Computer       | 9         | 12.86%  |
| Acer                   | 3         | 4.29%   |
| Toshiba                | 2         | 2.86%   |
| HUAWEI                 | 2         | 2.86%   |
| Apple                  | 2         | 2.86%   |
| Sony                   | 1         | 1.43%   |
| Samsung Electronics    | 1         | 1.43%   |
| Razer                  | 1         | 1.43%   |
| Intel Client Systems   | 1         | 1.43%   |
| Google                 | 1         | 1.43%   |
| Gigabyte Technology    | 1         | 1.43%   |
| Getac                  | 1         | 1.43%   |
| Clevo                  | 1         | 1.43%   |
| Avell High Performance | 1         | 1.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G50-45 80E3                       | 2         | 2.86%   |
| HP Pavilion dv6                          | 2         | 2.86%   |
| Toshiba Satellite L755D                  | 1         | 1.43%   |
| Toshiba Satellite C855                   | 1         | 1.43%   |
| Sony VGN-NS31M_W                         | 1         | 1.43%   |
| Samsung 305V4A/305V5A                    | 1         | 1.43%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 1.43%   |
| Lenovo ThinkPad X250 20CL001LMB          | 1         | 1.43%   |
| Lenovo ThinkPad X230 2333A86             | 1         | 1.43%   |
| Lenovo ThinkPad X230 2325AJG             | 1         | 1.43%   |
| Lenovo ThinkPad X230 23245S1             | 1         | 1.43%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 1         | 1.43%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 1.43%   |
| Lenovo ThinkPad W530 2447IG0             | 1         | 1.43%   |
| Lenovo ThinkPad T530 24296HG             | 1         | 1.43%   |
| Lenovo ThinkPad T520 4243K86             | 1         | 1.43%   |
| Lenovo ThinkPad E14 Gen 3 20Y70073GE     | 1         | 1.43%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.43%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 1.43%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 1.43%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 1.43%   |
| Lenovo IdeaPad 3 15ABA7 82RN             | 1         | 1.43%   |
| Lenovo IdeaPad 3 14ARE05 81W3            | 1         | 1.43%   |
| Lenovo G70-80 80FF                       | 1         | 1.43%   |
| Intel Client Systems LAPBC510            | 1         | 1.43%   |
| HUAWEI KLVL-WXXW                         | 1         | 1.43%   |
| HUAWEI HLYL-WXX9                         | 1         | 1.43%   |
| HP ZBook 15 G3                           | 1         | 1.43%   |
| HP Stream Laptop 14-cb0XX                | 1         | 1.43%   |
| HP Sona                                  | 1         | 1.43%   |
| HP Pavilion dv8                          | 1         | 1.43%   |
| HP OMEN by Laptop 15-ce0xx               | 1         | 1.43%   |
| HP Notebook                              | 1         | 1.43%   |
| HP Laptop 15s-fq1xxx                     | 1         | 1.43%   |
| HP EliteBook 840 G3                      | 1         | 1.43%   |
| HP EliteBook 735 G6                      | 1         | 1.43%   |
| HP Compaq 8510p                          | 1         | 1.43%   |
| Google Nami                              | 1         | 1.43%   |
| Gigabyte AERO 15-X9                      | 1         | 1.43%   |
| Getac S400G3                             | 1         | 1.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 10        | 14.29%  |
| Lenovo IdeaPad                | 5         | 7.14%   |
| Dell Latitude                 | 5         | 7.14%   |
| Dell Inspiron                 | 5         | 7.14%   |
| HP Pavilion                   | 3         | 4.29%   |
| Toshiba Satellite             | 2         | 2.86%   |
| Lenovo G50-45                 | 2         | 2.86%   |
| HP EliteBook                  | 2         | 2.86%   |
| Acer Aspire                   | 2         | 2.86%   |
| Sony VGN-NS31M                | 1         | 1.43%   |
| Samsung 305V4A                | 1         | 1.43%   |
| Razer Blade                   | 1         | 1.43%   |
| Lenovo Legion                 | 1         | 1.43%   |
| Lenovo G70-80                 | 1         | 1.43%   |
| Intel Client Systems LAPBC510 | 1         | 1.43%   |
| HUAWEI KLVL-WXXW              | 1         | 1.43%   |
| HUAWEI HLYL-WXX9              | 1         | 1.43%   |
| HP ZBook                      | 1         | 1.43%   |
| HP Stream                     | 1         | 1.43%   |
| HP Sona                       | 1         | 1.43%   |
| HP OMEN                       | 1         | 1.43%   |
| HP Notebook                   | 1         | 1.43%   |
| HP Laptop                     | 1         | 1.43%   |
| HP Compaq                     | 1         | 1.43%   |
| Google Nami                   | 1         | 1.43%   |
| Gigabyte AERO                 | 1         | 1.43%   |
| Getac S400G3                  | 1         | 1.43%   |
| Dell XPS                      | 1         | 1.43%   |
| Dell Precision                | 1         | 1.43%   |
| Clevo W35                     | 1         | 1.43%   |
| Avell High Performance Avell  | 1         | 1.43%   |
| ASUS X541NA                   | 1         | 1.43%   |
| ASUS VivoBook                 | 1         | 1.43%   |
| ASUS UX305FA                  | 1         | 1.43%   |
| ASUS U56E                     | 1         | 1.43%   |
| ASUS TP300UA                  | 1         | 1.43%   |
| ASUS ROG                      | 1         | 1.43%   |
| ASUS K53U                     | 1         | 1.43%   |
| ASUS GL503VD                  | 1         | 1.43%   |
| ASUS ASUS                     | 1         | 1.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 9         | 12.86%  |
| 2012 | 9         | 12.86%  |
| 2014 | 7         | 10%     |
| 2019 | 6         | 8.57%   |
| 2011 | 6         | 8.57%   |
| 2021 | 5         | 7.14%   |
| 2016 | 5         | 7.14%   |
| 2018 | 4         | 5.71%   |
| 2017 | 4         | 5.71%   |
| 2015 | 4         | 5.71%   |
| 2008 | 4         | 5.71%   |
| 2010 | 2         | 2.86%   |
| 2009 | 2         | 2.86%   |
| 2007 | 2         | 2.86%   |
| 2022 | 1         | 1.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 70        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 62        | 88.57%  |
| Enabled  | 8         | 11.43%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 68        | 97.14%  |
| Yes  | 2         | 2.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 29        | 40.85%  |
| 8.01-16.0  | 13        | 18.31%  |
| 16.01-24.0 | 12        | 16.9%   |
| 3.01-4.0   | 8         | 11.27%  |
| 32.01-64.0 | 4         | 5.63%   |
| 24.01-32.0 | 2         | 2.82%   |
| 2.01-3.0   | 2         | 2.82%   |
| 1.01-2.0   | 1         | 1.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 27        | 36.99%  |
| 2.01-3.0  | 18        | 24.66%  |
| 3.01-4.0  | 14        | 19.18%  |
| 4.01-8.0  | 11        | 15.07%  |
| 8.01-16.0 | 2         | 2.74%   |
| 0.51-1.0  | 1         | 1.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 70.42%  |
| 2      | 18        | 25.35%  |
| 0      | 2         | 2.82%   |
| 4      | 1         | 1.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 64.79%  |
| Yes       | 25        | 35.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 81.43%  |
| No        | 13        | 18.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 98.57%  |
| No        | 1         | 1.43%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 78.57%  |
| No        | 15        | 21.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 13        | 18.57%  |
| France      | 12        | 17.14%  |
| Germany     | 7         | 10%     |
| Russia      | 4         | 5.71%   |
| Canada      | 4         | 5.71%   |
| UK          | 3         | 4.29%   |
| Spain       | 3         | 4.29%   |
| Italy       | 3         | 4.29%   |
| Netherlands | 2         | 2.86%   |
| Costa Rica  | 2         | 2.86%   |
| Brazil      | 2         | 2.86%   |
| Yemen       | 1         | 1.43%   |
| Turkey      | 1         | 1.43%   |
| Taiwan      | 1         | 1.43%   |
| Switzerland | 1         | 1.43%   |
| Poland      | 1         | 1.43%   |
| Norway      | 1         | 1.43%   |
| Nigeria     | 1         | 1.43%   |
| Nicaragua   | 1         | 1.43%   |
| Mexico      | 1         | 1.43%   |
| Ivory Coast | 1         | 1.43%   |
| Indonesia   | 1         | 1.43%   |
| Hungary     | 1         | 1.43%   |
| Finland     | 1         | 1.43%   |
| Bulgaria    | 1         | 1.43%   |
| Austria     | 1         | 1.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Montreal       | 2         | 2.82%   |
| Madrid         | 2         | 2.82%   |
| Groningen      | 2         | 2.82%   |
| Denver         | 2         | 2.82%   |
| Béziers       | 2         | 2.82%   |
| Yonkers        | 1         | 1.41%   |
| Yekaterinburg  | 1         | 1.41%   |
| Wroclaw        | 1         | 1.41%   |
| Woonsocket     | 1         | 1.41%   |
| Woodland Park  | 1         | 1.41%   |
| Vienna         | 1         | 1.41%   |
| Velleron       | 1         | 1.41%   |
| Turin          | 1         | 1.41%   |
| Tarragona      | 1         | 1.41%   |
| Taipei         | 1         | 1.41%   |
| Sunderland     | 1         | 1.41%   |
| Stuttgart      | 1         | 1.41%   |
| Stabekk        | 1         | 1.41%   |
| St Petersburg  | 1         | 1.41%   |
| Sofia          | 1         | 1.41%   |
| Sleman         | 1         | 1.41%   |
| Seropedica     | 1         | 1.41%   |
| Sanaa          | 1         | 1.41%   |
| San Juan       | 1         | 1.41%   |
| Samara         | 1         | 1.41%   |
| Roubaix        | 1         | 1.41%   |
| Rio de Janeiro | 1         | 1.41%   |
| Ramsgate       | 1         | 1.41%   |
| Ragusa         | 1         | 1.41%   |
| Portland       | 1         | 1.41%   |
| Port Harcourt  | 1         | 1.41%   |
| Phoenix        | 1         | 1.41%   |
| Nudlingen      | 1         | 1.41%   |
| Moscow         | 1         | 1.41%   |
| Mississauga    | 1         | 1.41%   |
| Mexico City    | 1         | 1.41%   |
| Mannheim       | 1         | 1.41%   |
| Managua        | 1         | 1.41%   |
| Madison        | 1         | 1.41%   |
| Ludwigsburg    | 1         | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 14        | 14     | 16.28%  |
| WDC                         | 12        | 13     | 13.95%  |
| SanDisk                     | 7         | 7      | 8.14%   |
| Toshiba                     | 6         | 6      | 6.98%   |
| Unknown                     | 4         | 4      | 4.65%   |
| SK hynix                    | 4         | 5      | 4.65%   |
| Seagate                     | 4         | 4      | 4.65%   |
| Intel                       | 4         | 6      | 4.65%   |
| Kingston                    | 3         | 3      | 3.49%   |
| Phison                      | 2         | 2      | 2.33%   |
| Micron Technology           | 2         | 2      | 2.33%   |
| Hitachi                     | 2         | 2      | 2.33%   |
| Crucial                     | 2         | 2      | 2.33%   |
| China                       | 2         | 2      | 2.33%   |
| Union Memory                | 1         | 1      | 1.16%   |
| UMIS                        | 1         | 1      | 1.16%   |
| Team                        | 1         | 1      | 1.16%   |
| SPCC                        | 1         | 1      | 1.16%   |
| Reeinno                     | 1         | 1      | 1.16%   |
| Realtek                     | 1         | 1      | 1.16%   |
| PNY                         | 1         | 1      | 1.16%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.16%   |
| KIOXIA                      | 1         | 1      | 1.16%   |
| KingSpec                    | 1         | 1      | 1.16%   |
| JMicron Technology          | 1         | 1      | 1.16%   |
| Inateck                     | 1         | 1      | 1.16%   |
| HGST                        | 1         | 1      | 1.16%   |
| Fujitsu                     | 1         | 1      | 1.16%   |
| Dogfish                     | 1         | 1      | 1.16%   |
| BHT                         | 1         | 1      | 1.16%   |
| ASMT                        | 1         | 1      | 1.16%   |
| Unknown                     | 1         | 1      | 1.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 2.3%    |
| Toshiba MQ04ABF100 1TB                    | 2         | 2.3%    |
| Toshiba MQ01ABD100 1TB                    | 2         | 2.3%    |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 2.3%    |
| Samsung SSD 870 EVO 1TB                   | 2         | 2.3%    |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 2.3%    |
| Kingston SA400S37240G 240GB SSD           | 2         | 2.3%    |
| China SSD 1TB                             | 2         | 2.3%    |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 1.15%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 1.15%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 1.15%   |
| WDC WD5000BEKT-60KA9T0 500GB              | 1         | 1.15%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 1.15%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 1.15%   |
| WDC WD3200BEKT-60V5T1 320GB               | 1         | 1.15%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 1.15%   |
| WDC WD10JPVT-75A1YT0 1TB                  | 1         | 1.15%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB      | 1         | 1.15%   |
| Unknown MMC Card  4GB                     | 1         | 1.15%   |
| Unknown MMC Card  16GB                    | 1         | 1.15%   |
| Unknown DA4128  128GB                     | 1         | 1.15%   |
| Unknown 032G34  32GB                      | 1         | 1.15%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB   | 1         | 1.15%   |
| UMIS RPJTJ256MEE1OWX 256GB                | 1         | 1.15%   |
| Toshiba TR150 240GB SSD                   | 1         | 1.15%   |
| Toshiba MK1637GSX 160GB                   | 1         | 1.15%   |
| Team TM8FP4001T 1TB                       | 1         | 1.15%   |
| SPCC Solid State Disk 1TB                 | 1         | 1.15%   |
| SK hynix SKHynix_HFS256GD9TNI-L2A0B 256GB | 1         | 1.15%   |
| SK hynix BC501 NVMe 256GB                 | 1         | 1.15%   |
| Seagate ST9320320AS 320GB                 | 1         | 1.15%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 1.15%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.15%   |
| Seagate FireCuda 530 ZP4000GM30013 4TB    | 1         | 1.15%   |
| SanDisk SSD PLUS 240GB                    | 1         | 1.15%   |
| SanDisk SD9SN8W128G1002 128GB SSD         | 1         | 1.15%   |
| SanDisk SD8SN8U256G1002 256GB SSD         | 1         | 1.15%   |
| SanDisk SD7SN3Q128G1002 128GB SSD         | 1         | 1.15%   |
| SanDisk Extreme SSD 500GB                 | 1         | 1.15%   |
| SanDisk DF4064  64GB                      | 1         | 1.15%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 31.82%  |
| Toshiba             | 5         | 5      | 22.73%  |
| Seagate             | 3         | 3      | 13.64%  |
| Samsung Electronics | 2         | 2      | 9.09%   |
| Hitachi             | 2         | 2      | 9.09%   |
| HGST                | 1         | 1      | 4.55%   |
| Fujitsu             | 1         | 1      | 4.55%   |
| ASMT                | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 25.81%  |
| SanDisk             | 5         | 5      | 16.13%  |
| Kingston            | 2         | 2      | 6.45%   |
| Crucial             | 2         | 2      | 6.45%   |
| China               | 2         | 2      | 6.45%   |
| WDC                 | 1         | 1      | 3.23%   |
| Toshiba             | 1         | 1      | 3.23%   |
| SPCC                | 1         | 1      | 3.23%   |
| Reeinno             | 1         | 1      | 3.23%   |
| PNY                 | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| KingSpec            | 1         | 1      | 3.23%   |
| JMicron Technology  | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| Inateck             | 1         | 1      | 3.23%   |
| Dogfish             | 1         | 1      | 3.23%   |
| BHT                 | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 26        | 31     | 34.21%  |
| NVMe | 22        | 29     | 28.95%  |
| HDD  | 22        | 23     | 28.95%  |
| MMC  | 6         | 7      | 7.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 50     | 56.58%  |
| NVMe | 22        | 28     | 28.95%  |
| MMC  | 6         | 7      | 7.89%   |
| SAS  | 5         | 5      | 6.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 41     | 74%     |
| 0.51-1.0   | 12        | 12     | 24%     |
| 1.01-2.0   | 1         | 1      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 22        | 30.56%  |
| 251-500    | 17        | 23.61%  |
| 501-1000   | 11        | 15.28%  |
| 21-50      | 7         | 9.72%   |
| 51-100     | 7         | 9.72%   |
| 1-20       | 4         | 5.56%   |
| 1001-2000  | 3         | 4.17%   |
| 2001-3000  | 1         | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 27        | 37.5%   |
| 21-50     | 15        | 20.83%  |
| 101-250   | 10        | 13.89%  |
| 251-500   | 7         | 9.72%   |
| 51-100    | 6         | 8.33%   |
| 501-1000  | 5         | 6.94%   |
| 1001-2000 | 2         | 2.78%   |

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
| KingSpec P3-256 256GB SSD                           | 1         | 1      | 6.25%   |
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
| Works    | 50        | 64     | 66.67%  |
| Malfunc  | 16        | 16     | 21.33%  |
| Detected | 9         | 10     | 12%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 49        | 59.04%  |
| AMD                         | 12        | 14.46%  |
| SK hynix                    | 4         | 4.82%   |
| SanDisk                     | 4         | 4.82%   |
| Samsung Electronics         | 4         | 4.82%   |
| Phison Electronics          | 3         | 3.61%   |
| Union Memory (Shenzhen)     | 2         | 2.41%   |
| Seagate Technology          | 1         | 1.2%    |
| Micron Technology           | 1         | 1.2%    |
| MAXIO Technology (Hangzhou) | 1         | 1.2%    |
| KIOXIA                      | 1         | 1.2%    |
| Kingston Technology Company | 1         | 1.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 10        | 11.24%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 7.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 6         | 6.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 6         | 6.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 5.62%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 3         | 3.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3         | 3.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 3         | 3.37%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 2         | 2.25%   |
| SK hynix BC511                                                                | 2         | 2.25%   |
| Phison E12 NVMe Controller                                                    | 2         | 2.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 2         | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 2         | 2.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 2.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 2         | 2.25%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2         | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2         | 2.25%   |
| SK hynix Non-Volatile memory controller                                       | 1         | 1.12%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 1         | 1.12%   |
| Seagate FireCuda 530 SSD                                                      | 1         | 1.12%   |
| SanDisk NVMe Controller                                                       | 1         | 1.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 1.12%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 1.12%   |
| Micron NVMe Storage Controller                                                | 1         | 1.12%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                  | 1         | 1.12%   |
| KIOXIA NVMe SSD Controller BG4                                                | 1         | 1.12%   |
| Kingston Company A2000 NVMe SSD                                               | 1         | 1.12%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 1.12%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 1.12%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 1         | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.12%   |
| Intel NVMe Controller                                                         | 1         | 1.12%   |
| Intel Non-Volatile memory controller                                          | 1         | 1.12%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                   | 1         | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 1.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 1.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                  | 1         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 1.12%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 50        | 60.24%  |
| NVMe | 22        | 26.51%  |
| RAID | 7         | 8.43%   |
| IDE  | 4         | 4.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 77.14%  |
| AMD    | 16        | 22.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-2450M CPU @ 2.50GHz      | 3         | 4.29%   |
| AMD Ryzen 5 4600H with Radeon Graphics | 3         | 4.29%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 2.86%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 2         | 2.86%   |
| Intel Core i7-5600U CPU @ 2.60GHz      | 2         | 2.86%   |
| AMD Ryzen 5 5500U with Radeon Graphics | 2         | 2.86%   |
| Intel Processor 5Y10 CPU @ 0.80GHz     | 1         | 1.43%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.43%   |
| Intel Genuine CPU U2300 @ 1.20GHz      | 1         | 1.43%   |
| Intel Core i9-8950HK CPU @ 2.90GHz     | 1         | 1.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 1.43%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 1         | 1.43%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 1         | 1.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 1.43%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.43%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz     | 1         | 1.43%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1         | 1.43%   |
| Intel Core i7-3940XM CPU @ 3.00GHz     | 1         | 1.43%   |
| Intel Core i7-3630QM CPU @ 2.40GHz     | 1         | 1.43%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 1         | 1.43%   |
| Intel Core i7-2635QM CPU @ 2.00GHz     | 1         | 1.43%   |
| Intel Core i7-2630QM CPU @ 2.00GHz     | 1         | 1.43%   |
| Intel Core i7-10850H CPU @ 2.70GHz     | 1         | 1.43%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 1.43%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz      | 1         | 1.43%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz      | 1         | 1.43%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 1         | 1.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.43%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.43%   |
| Intel Core i5-4310M CPU @ 2.70GHz      | 1         | 1.43%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.43%   |
| Intel Core i5-3340M CPU @ 2.70GHz      | 1         | 1.43%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 1         | 1.43%   |
| Intel Core i5-3230M CPU @ 2.60GHz      | 1         | 1.43%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 1         | 1.43%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz     | 1         | 1.43%   |
| Intel Core i5-10300H CPU @ 2.50GHz     | 1         | 1.43%   |
| Intel Core i5 CPU M 460 @ 2.53GHz      | 1         | 1.43%   |
| Intel Core i3-8130U CPU @ 2.20GHz      | 1         | 1.43%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 1         | 1.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 22        | 31.43%  |
| Intel Core i5      | 15        | 21.43%  |
| AMD Ryzen 5        | 5         | 7.14%   |
| Intel Core 2 Duo   | 4         | 5.71%   |
| Intel Celeron      | 4         | 5.71%   |
| Other              | 3         | 4.29%   |
| Intel Core i3      | 3         | 4.29%   |
| AMD Ryzen 7        | 3         | 4.29%   |
| AMD E              | 2         | 2.86%   |
| Intel Pentium Dual | 1         | 1.43%   |
| Intel Genuine      | 1         | 1.43%   |
| Intel Core i9      | 1         | 1.43%   |
| AMD Ryzen 3 PRO    | 1         | 1.43%   |
| AMD Ryzen 3        | 1         | 1.43%   |
| AMD E2             | 1         | 1.43%   |
| AMD E1             | 1         | 1.43%   |
| AMD A6             | 1         | 1.43%   |
| AMD A4             | 1         | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 35        | 50%     |
| 4      | 23        | 32.86%  |
| 6      | 9         | 12.86%  |
| 8      | 3         | 4.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 70        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 70%     |
| 1      | 21        | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 70        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 7         | 9.86%   |
| 0x306a9    | 6         | 8.45%   |
| 0x306d4    | 5         | 7.04%   |
| Unknown    | 5         | 7.04%   |
| 0x08600104 | 4         | 5.63%   |
| 0x906ea    | 3         | 4.23%   |
| 0x806ea    | 3         | 4.23%   |
| 0x406e3    | 3         | 4.23%   |
| 0xa0652    | 2         | 2.82%   |
| 0x906e9    | 2         | 2.82%   |
| 0x806c1    | 2         | 2.82%   |
| 0x706e5    | 2         | 2.82%   |
| 0x6fd      | 2         | 2.82%   |
| 0x40651    | 2         | 2.82%   |
| 0x106e5    | 2         | 2.82%   |
| 0x07030105 | 2         | 2.82%   |
| 0x706a1    | 1         | 1.41%   |
| 0x6fb      | 1         | 1.41%   |
| 0x506e3    | 1         | 1.41%   |
| 0x506c9    | 1         | 1.41%   |
| 0x406c4    | 1         | 1.41%   |
| 0x40661    | 1         | 1.41%   |
| 0x306c3    | 1         | 1.41%   |
| 0x1067a    | 1         | 1.41%   |
| 0x10676    | 1         | 1.41%   |
| 0x0a50000c | 1         | 1.41%   |
| 0x08608103 | 1         | 1.41%   |
| 0x08608102 | 1         | 1.41%   |
| 0x08600106 | 1         | 1.41%   |
| 0x08600103 | 1         | 1.41%   |
| 0x08108109 | 1         | 1.41%   |
| 0x07030104 | 1         | 1.41%   |
| 0x0500010d | 1         | 1.41%   |
| 0x05000029 | 1         | 1.41%   |
| 0x03000027 | 1         | 1.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 12.86%  |
| SandyBridge   | 7         | 10%     |
| Zen 2         | 6         | 8.57%   |
| IvyBridge     | 6         | 8.57%   |
| Broadwell     | 6         | 8.57%   |
| Skylake       | 4         | 5.71%   |
| Haswell       | 4         | 5.71%   |
| Puma          | 3         | 4.29%   |
| Penryn        | 3         | 4.29%   |
| Core          | 3         | 4.29%   |
| TigerLake     | 2         | 2.86%   |
| Nehalem       | 2         | 2.86%   |
| IceLake       | 2         | 2.86%   |
| CometLake     | 2         | 2.86%   |
| Bobcat        | 2         | 2.86%   |
| Unknown       | 2         | 2.86%   |
| Zen+          | 1         | 1.43%   |
| Zen 3         | 1         | 1.43%   |
| Westmere      | 1         | 1.43%   |
| Silvermont    | 1         | 1.43%   |
| K10 Llano     | 1         | 1.43%   |
| Goldmont plus | 1         | 1.43%   |
| Goldmont      | 1         | 1.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 48        | 53.93%  |
| AMD    | 21        | 23.6%   |
| Nvidia | 20        | 22.47%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 7         | 7.69%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 6.59%   |
| AMD Renoir                                                                | 6         | 6.59%   |
| Intel HD Graphics 5500                                                    | 5         | 5.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 4.4%    |
| Intel UHD Graphics 620                                                    | 3         | 3.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 3.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 3.3%    |
| Nvidia TU117M                                                             | 2         | 2.2%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 2.2%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 2.2%    |
| Nvidia GK208BM [GeForce 920M]                                             | 2         | 2.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 2.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 2.2%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 2.2%    |
| AMD Wrestler [Radeon HD 6310]                                             | 2         | 2.2%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 2.2%    |
| AMD Lucienne                                                              | 2         | 2.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.1%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 1.1%    |
| Nvidia GT216M [GeForce GT 230M]                                           | 1         | 1.1%    |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 1         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.1%    |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 1.1%    |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 1.1%    |
| Nvidia GK107M [GeForce GTX 660M]                                          | 1         | 1.1%    |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 1.1%    |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 1.1%    |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.1%    |
| Nvidia GF108M [GeForce GT 525M]                                           | 1         | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 1.1%    |
| Intel Iris Plus Graphics G7                                               | 1         | 1.1%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.1%    |
| Intel HD Graphics 630                                                     | 1         | 1.1%    |
| Intel HD Graphics 5300                                                    | 1         | 1.1%    |
| Intel HD Graphics 530                                                     | 1         | 1.1%    |
| Intel HD Graphics 500                                                     | 1         | 1.1%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.1%    |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.1%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 45.71%  |
| 1 x AMD        | 15        | 21.43%  |
| Intel + Nvidia | 14        | 20%     |
| 1 x Nvidia     | 3         | 4.29%   |
| AMD + Nvidia   | 3         | 4.29%   |
| Intel + AMD    | 2         | 2.86%   |
| 2 x AMD        | 1         | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 65        | 92.86%  |
| Proprietary | 5         | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 55.71%  |
| 0.51-1.0   | 10        | 14.29%  |
| 0.01-0.5   | 9         | 12.86%  |
| 1.01-2.0   | 7         | 10%     |
| 3.01-4.0   | 3         | 4.29%   |
| 5.01-6.0   | 2         | 2.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 16        | 20%     |
| AU Optronics            | 15        | 18.75%  |
| Samsung Electronics     | 10        | 12.5%   |
| Chimei Innolux          | 9         | 11.25%  |
| BOE                     | 9         | 11.25%  |
| Lenovo                  | 3         | 3.75%   |
| Sharp                   | 2         | 2.5%    |
| Hewlett-Packard         | 2         | 2.5%    |
| Chi Mei Optoelectronics | 2         | 2.5%    |
| Apple                   | 2         | 2.5%    |
| LG Philips              | 1         | 1.25%   |
| Iiyama                  | 1         | 1.25%   |
| Hannspree               | 1         | 1.25%   |
| Dell                    | 1         | 1.25%   |
| CPT                     | 1         | 1.25%   |
| BenQ                    | 1         | 1.25%   |
| ASUSTek Computer        | 1         | 1.25%   |
| Arnos Instruments       | 1         | 1.25%   |
| Ancor Communications    | 1         | 1.25%   |
| Acer                    | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 2         | 2.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 2.5%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 2         | 2.5%    |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch         | 2         | 2.5%    |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 2.5%    |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                 | 1         | 1.25%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                 | 1         | 1.25%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch     | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch    | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch    | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch    | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch    | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 344x194mm 15.5-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 1.25%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 1.25%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch             | 1         | 1.25%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch             | 1         | 1.25%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 1.25%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch             | 1         | 1.25%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch            | 1         | 1.25%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch                | 1         | 1.25%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 1.25%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                 | 1         | 1.25%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                   | 1         | 1.25%   |
| Hewlett-Packard E242 HWP326F 1920x1080 518x324mm 24.1-inch              | 1         | 1.25%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch               | 1         | 1.25%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                    | 1         | 1.25%   |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                        | 1         | 1.25%   |
| CPT LCD Monitor CPT141F 1280x800 331x207mm 15.4-inch                    | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch         | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 1         | 1.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 34        | 46.58%  |
| 1366x768 (WXGA)    | 22        | 30.14%  |
| 1600x900 (HD+)     | 5         | 6.85%   |
| 3840x2160 (4K)     | 3         | 4.11%   |
| 1680x1050 (WSXGA+) | 2         | 2.74%   |
| 1280x800 (WXGA)    | 2         | 2.74%   |
| 2880x1800          | 1         | 1.37%   |
| 2560x1440 (QHD)    | 1         | 1.37%   |
| 2160x1440          | 1         | 1.37%   |
| 1920x1200 (WUXGA)  | 1         | 1.37%   |
| 1440x900 (WXGA+)   | 1         | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 40        | 50%     |
| 13     | 10        | 12.5%   |
| 14     | 7         | 8.75%   |
| 24     | 5         | 6.25%   |
| 12     | 5         | 6.25%   |
| 27     | 2         | 2.5%    |
| 21     | 2         | 2.5%    |
| 18     | 2         | 2.5%    |
| 17     | 2         | 2.5%    |
| 84     | 1         | 1.25%   |
| 23     | 1         | 1.25%   |
| 20     | 1         | 1.25%   |
| 19     | 1         | 1.25%   |
| 16     | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 64.56%  |
| 201-300     | 11        | 13.92%  |
| 501-600     | 7         | 8.86%   |
| 401-500     | 6         | 7.59%   |
| 351-400     | 3         | 3.8%    |
| 1501-2000   | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 61        | 85.92%  |
| 16/10 | 9         | 12.68%  |
| 3/2   | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 51.25%  |
| 81-90          | 12        | 15%     |
| 71-80          | 5         | 6.25%   |
| 61-70          | 5         | 6.25%   |
| 201-250        | 4         | 5%      |
| 251-300        | 3         | 3.75%   |
| 151-200        | 3         | 3.75%   |
| 301-350        | 2         | 2.5%    |
| 141-150        | 2         | 2.5%    |
| More than 1000 | 1         | 1.25%   |
| 131-140        | 1         | 1.25%   |
| 121-130        | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 43.59%  |
| 101-120       | 22        | 28.21%  |
| 51-100        | 13        | 16.67%  |
| 161-240       | 8         | 10.26%  |
| More than 240 | 1         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 60        | 83.33%  |
| 2     | 11        | 15.28%  |
| 3     | 1         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 44        | 40%     |
| Realtek Semiconductor             | 37        | 33.64%  |
| Qualcomm Atheros                  | 13        | 11.82%  |
| Broadcom                          | 5         | 4.55%   |
| ASIX Electronics                  | 3         | 2.73%   |
| Ralink                            | 2         | 1.82%   |
| Ericsson Business Mobile Networks | 2         | 1.82%   |
| MediaTek                          | 1         | 0.91%   |
| Marvell Technology Group          | 1         | 0.91%   |
| Huawei Technologies               | 1         | 0.91%   |
| Broadcom Limited                  | 1         | 0.91%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 21        | 15.67%  |
| Intel Wireless 7265                                                | 7         | 5.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 7         | 5.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 5         | 3.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 5         | 3.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 5         | 3.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 3         | 2.24%   |
| Intel Wireless 8265 / 8275                                         | 3         | 2.24%   |
| Intel Wireless 7260                                                | 3         | 2.24%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 2.24%   |
| Intel Centrino Ultimate-N 6300                                     | 3         | 2.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 3         | 2.24%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 2.24%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 2         | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 2         | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.49%   |
| Intel Wireless 8260                                                | 2         | 1.49%   |
| Intel WiFi Link 5100                                               | 2         | 1.49%   |
| Intel Wi-Fi 6 AX201                                                | 2         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                              | 2         | 1.49%   |
| Intel 82567LM Gigabit Network Connection                           | 2         | 1.49%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.49%   |
| Broadcom BCM43142 802.11b/g/n                                      | 2         | 1.49%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller        | 1         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 1         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek 802.11ac NIC                                               | 1         | 0.75%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]   | 1         | 0.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller          | 1         | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 1         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                              | 1         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                         | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                      | 1         | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                           | 1         | 0.75%   |
| MediaTek U318AA                                                    | 1         | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller            | 1         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 42        | 60%     |
| Realtek Semiconductor | 12        | 17.14%  |
| Qualcomm Atheros      | 9         | 12.86%  |
| Broadcom              | 4         | 5.71%   |
| Ralink                | 2         | 2.86%   |
| Broadcom Limited      | 1         | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 7         | 9.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 5         | 7.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 5         | 7.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 3         | 4.23%   |
| Intel Wireless 8265 / 8275                                       | 3         | 4.23%   |
| Intel Wireless 7260                                              | 3         | 4.23%   |
| Intel Wi-Fi 6 AX200                                              | 3         | 4.23%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 4.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 3         | 4.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 2         | 2.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 2.82%   |
| Intel Wireless 8260                                              | 2         | 2.82%   |
| Intel WiFi Link 5100                                             | 2         | 2.82%   |
| Intel Wi-Fi 6 AX201                                              | 2         | 2.82%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 2.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller      | 1         | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.41%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1.41%   |
| Realtek 802.11ac NIC                                             | 1         | 1.41%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1         | 1.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 1.41%   |
| Intel Wireless-AC 9260                                           | 1         | 1.41%   |
| Intel Wireless 3160                                              | 1         | 1.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 1.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 1         | 1.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 1         | 1.41%   |
| Intel Centrino Wireless-N 6150                                   | 1         | 1.41%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 1         | 1.41%   |
| Intel Centrino Wireless-N + WiMAX 6150                           | 1         | 1.41%   |
| Intel Centrino Advanced-N 6200                                   | 1         | 1.41%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 1         | 1.41%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                      | 1         | 1.41%   |
| Broadcom BCM4331 802.11a/b/g/n                                   | 1         | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 28        | 46.67%  |
| Intel                    | 20        | 33.33%  |
| Qualcomm Atheros         | 5         | 8.33%   |
| ASIX Electronics         | 3         | 5%      |
| Broadcom                 | 2         | 3.33%   |
| MediaTek                 | 1         | 1.67%   |
| Marvell Technology Group | 1         | 1.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 35%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 11.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.33%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 3.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.67%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.67%   |
| MediaTek U318AA                                                   | 1         | 1.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.67%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.67%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.67%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.67%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.67%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.67%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 53.49%  |
| Ethernet | 57        | 44.19%  |
| Modem    | 3         | 2.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 83.78%  |
| Ethernet | 12        | 16.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 53        | 75.71%  |
| 1     | 17        | 24.29%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 71.43%  |
| Yes  | 20        | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 50.91%  |
| Realtek Semiconductor           | 6         | 10.91%  |
| Broadcom                        | 5         | 9.09%   |
| Qualcomm Atheros Communications | 4         | 7.27%   |
| Realtek                         | 2         | 3.64%   |
| Ralink Technology               | 2         | 3.64%   |
| Lite-On Technology              | 2         | 3.64%   |
| Hewlett-Packard                 | 2         | 3.64%   |
| Apple                           | 2         | 3.64%   |
| Foxconn International           | 1         | 1.82%   |
| Dell                            | 1         | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 16        | 29.09%  |
| Realtek Bluetooth Radio                           | 4         | 7.27%   |
| Intel AX201 Bluetooth                             | 4         | 7.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 4         | 7.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 3         | 5.45%   |
| Intel AX200 Bluetooth                             | 3         | 5.45%   |
| Realtek Bluetooth Radio                           | 2         | 3.64%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 3.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 3.64%   |
| Apple Bluetooth Host Controller                   | 2         | 3.64%   |
| Realtek RTL8723B Bluetooth                        | 1         | 1.82%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 1.82%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 1.82%   |
| Ralink CSR BS8510                                 | 1         | 1.82%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 1.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 1.82%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 1.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 1.82%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.82%   |
| Dell Wireless 370 Bluetooth Mini-card             | 1         | 1.82%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 54        | 55.1%   |
| AMD                        | 19        | 19.39%  |
| Nvidia                     | 16        | 16.33%  |
| Yealink Network Technology | 1         | 1.02%   |
| Yamaha                     | 1         | 1.02%   |
| QinHeng Electronics        | 1         | 1.02%   |
| Mackie Designs             | 1         | 1.02%   |
| Logitech                   | 1         | 1.02%   |
| Focusrite-Novation         | 1         | 1.02%   |
| C-Media Electronics        | 1         | 1.02%   |
| BR36                       | 1         | 1.02%   |
| Behringer.......           | 1         | 1.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 7.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 6.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 5.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 5%      |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 5%      |
| Intel Broadwell-U Audio Controller                                         | 6         | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 3.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 3.33%   |
| AMD FCH Azalia Controller                                                  | 4         | 3.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.5%    |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 2.5%    |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.67%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.67%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.67%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.67%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.67%   |
| Yealink Network Technology VoIP Phone                                      | 1         | 0.83%   |
| Yamaha Steinberg UR242                                                     | 1         | 0.83%   |
| QinHeng Electronics CH345 MIDI adapter                                     | 1         | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.83%   |
| Mackie Designs BIG KNOB STUDIO+                                            | 1         | 0.83%   |
| Logitech 960 Headset                                                       | 1         | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 32.53%  |
| SK hynix            | 24        | 28.92%  |
| Micron Technology   | 9         | 10.84%  |
| Kingston            | 8         | 9.64%   |
| Unknown             | 3         | 3.61%   |
| Timetec             | 2         | 2.41%   |
| Ramaxel Technology  | 2         | 2.41%   |
| Nanya Technology    | 2         | 2.41%   |
| Crucial             | 2         | 2.41%   |
| Transcend           | 1         | 1.2%    |
| G.Skill             | 1         | 1.2%    |
| Corsair             | 1         | 1.2%    |
| Unknown             | 1         | 1.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 3         | 3.3%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 3.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 3.3%    |
| Kingston RAM LV32D4S2S8HD-8 8192MB SODIMM DDR4 3200MT/s      | 3         | 3.3%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 2.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.2%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 2.2%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 2.2%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.2%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 2.2%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 2.2%    |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s             | 1         | 1.1%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 1.1%    |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 1.1%    |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s           | 1         | 1.1%    |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 1.1%    |
| Timetec RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.1%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.1%    |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s              | 1         | 1.1%    |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s         | 1         | 1.1%    |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s    | 1         | 1.1%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.1%    |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 1         | 1.1%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s   | 1         | 1.1%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 1.1%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.1%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.1%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s       | 1         | 1.1%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB DDR4 2400MT/s              | 1         | 1.1%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 1.1%    |
| Samsung RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 1.1%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.1%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 1         | 1.1%    |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s       | 1         | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 36        | 49.32%  |
| DDR4   | 25        | 34.25%  |
| DDR2   | 5         | 6.85%   |
| SDRAM  | 3         | 4.11%   |
| LPDDR4 | 2         | 2.74%   |
| LPDDR3 | 2         | 2.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 63        | 86.3%   |
| Row Of Chips | 8         | 10.96%  |
| Chip         | 1         | 1.37%   |
| Unknown      | 1         | 1.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 35        | 42.17%  |
| 8192  | 27        | 32.53%  |
| 2048  | 10        | 12.05%  |
| 16384 | 7         | 8.43%   |
| 1024  | 3         | 3.61%   |
| 32768 | 1         | 1.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 29        | 38.16%  |
| 3200    | 11        | 14.47%  |
| 1334    | 8         | 10.53%  |
| 2667    | 7         | 9.21%   |
| 2400    | 4         | 5.26%   |
| 2133    | 4         | 5.26%   |
| 1333    | 3         | 3.95%   |
| 667     | 3         | 3.95%   |
| 4267    | 2         | 2.63%   |
| 4199    | 2         | 2.63%   |
| 1639    | 1         | 1.32%   |
| 800     | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

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
| Chicony Electronics                    | 17        | 28.33%  |
| IMC Networks                           | 8         | 13.33%  |
| Sunplus Innovation Technology          | 5         | 8.33%   |
| Suyin                                  | 4         | 6.67%   |
| Realtek Semiconductor                  | 4         | 6.67%   |
| Microdia                               | 4         | 6.67%   |
| Syntek                                 | 3         | 5%      |
| Quanta                                 | 3         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5%      |
| Acer                                   | 2         | 3.33%   |
| ViewQuest Technologies                 | 1         | 1.67%   |
| Silicon Motion                         | 1         | 1.67%   |
| Ricoh                                  | 1         | 1.67%   |
| Philips (or NXP)                       | 1         | 1.67%   |
| Lite-On Technology                     | 1         | 1.67%   |
| Importek                               | 1         | 1.67%   |
| Apple                                  | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 4         | 6.56%   |
| Chicony Integrated Camera                           | 4         | 6.56%   |
| Syntek Integrated Camera                            | 3         | 4.92%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 4.92%   |
| Chicony Integrated Camera [ThinkPad]                | 3         | 4.92%   |
| Suyin Asus Integrated Webcam                        | 2         | 3.28%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 3.28%   |
| Sunplus HD WebCam                                   | 2         | 3.28%   |
| Realtek Lenovo EasyCamera                           | 2         | 3.28%   |
| Microdia Integrated_Webcam_HD                       | 2         | 3.28%   |
| Chicony HP HD Camera                                | 2         | 3.28%   |
| ViewQuest Ability GABB Webcam                       | 1         | 1.64%   |
| Suyin HP Webcam                                     | 1         | 1.64%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1.64%   |
| Sunplus Dell HD Webcam                              | 1         | 1.64%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 1.64%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.64%   |
| Realtek VGA WebCam                                  | 1         | 1.64%   |
| Realtek HP Wide Vision HD Camera                    | 1         | 1.64%   |
| Quanta ov9734_techfront_camera                      | 1         | 1.64%   |
| Quanta HP Webcam                                    | 1         | 1.64%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.64%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc]          | 1         | 1.64%   |
| Microdia Sonix Integrated Webcam                    | 1         | 1.64%   |
| Microdia Integrated Webcam HD                       | 1         | 1.64%   |
| Lite-On Integrated Camera                           | 1         | 1.64%   |
| Importek TOSHIBA Web Camera - HD                    | 1         | 1.64%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.64%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 1.64%   |
| Chicony Integrated IR Camera                        | 1         | 1.64%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 1.64%   |
| Chicony HP TrueVision HD                            | 1         | 1.64%   |
| Chicony HD Webcam                                   | 1         | 1.64%   |
| Chicony HD User Facing                              | 1         | 1.64%   |
| Chicony CNFA078                                     | 1         | 1.64%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 1.64%   |
| Chicony 4-Port Hub                                  | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 41.67%  |
| Shenzhen Goodix Technology | 3         | 25%     |
| Synaptics                  | 2         | 16.67%  |
| LighTuning Technology      | 1         | 8.33%   |
| AuthenTec                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 16.67%  |
| Shenzhen Goodix  Fingerprint Device                        | 2         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 8.33%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner                       | 1         | 8.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 8.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 8.33%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 8.33%   |

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
| 0     | 38        | 54.29%  |
| 1     | 27        | 38.57%  |
| 2     | 4         | 5.71%   |
| 3     | 1         | 1.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 12        | 34.29%  |
| Graphics card         | 9         | 25.71%  |
| Chipcard              | 8         | 22.86%  |
| Net/wireless          | 2         | 5.71%   |
| Multimedia controller | 2         | 5.71%   |
| Camera                | 2         | 5.71%   |

