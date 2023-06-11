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

Total: 88

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 745 G3            | [5a1b8d9fd3](https://linux-hardware.org/?probe=5a1b8d9fd3) | Jun 04, 2023 |
| COM1          | NBINF-X5-9G5                | [33aa60eaa2](https://linux-hardware.org/?probe=33aa60eaa2) | May 22, 2023 |
| Lenovo        | ThinkPad L460 20FVS3JK00    | [c812ee44af](https://linux-hardware.org/?probe=c812ee44af) | May 18, 2023 |
| GPU Compan... | GWNR71517                   | [2743830739](https://linux-hardware.org/?probe=2743830739) | Apr 11, 2023 |
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
| Ubuntu Studio 20.04 | 38        | 50.67%  |
| Ubuntu Studio 22.04 | 19        | 25.33%  |
| Ubuntu Studio 22.10 | 4         | 5.33%   |
| Ubuntu Studio 21.10 | 3         | 4%      |
| Ubuntu Studio 21.04 | 3         | 4%      |
| Ubuntu Studio 20.10 | 3         | 4%      |
| Ubuntu Studio 23.04 | 2         | 2.67%   |
| Ubuntu Studio 18.04 | 2         | 2.67%   |
| Ubuntu Studio 19.10 | 1         | 1.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 74        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-52-lowlatency     | 3         | 3.9%    |
| 5.15.0-56-lowlatency    | 3         | 3.9%    |
| 5.15.0-47-lowlatency    | 3         | 3.9%    |
| 5.13.0-28-lowlatency    | 3         | 3.9%    |
| 6.2.0-1003-lowlatency   | 2         | 2.6%    |
| 5.8.0-55-lowlatency     | 2         | 2.6%    |
| 5.4.0-94-lowlatency     | 2         | 2.6%    |
| 5.4.0-65-lowlatency     | 2         | 2.6%    |
| 5.4.0-45-lowlatency     | 2         | 2.6%    |
| 5.4.0-42-lowlatency     | 2         | 2.6%    |
| 5.19.0-1015-lowlatency  | 2         | 2.6%    |
| 5.15.0-67-lowlatency    | 2         | 2.6%    |
| 5.15.0-50-lowlatency    | 2         | 2.6%    |
| 5.15.0-48-lowlatency    | 2         | 2.6%    |
| 5.15.0-46-lowlatency    | 2         | 2.6%    |
| 5.13.0-30-lowlatency    | 2         | 2.6%    |
| 5.11.0-34-lowlatency    | 2         | 2.6%    |
| 5.11.0-27-lowlatency    | 2         | 2.6%    |
| 6.2.8-x64v3-xanmod1     | 1         | 1.3%    |
| 5.8.0-59-lowlatency     | 1         | 1.3%    |
| 5.8.0-50-lowlatency     | 1         | 1.3%    |
| 5.8.0-44-lowlatency     | 1         | 1.3%    |
| 5.8.0-43-lowlatency     | 1         | 1.3%    |
| 5.8.0-34-generic        | 1         | 1.3%    |
| 5.8.0-29-lowlatency     | 1         | 1.3%    |
| 5.8.0-25-lowlatency     | 1         | 1.3%    |
| 5.7.6-050706-lowlatency | 1         | 1.3%    |
| 5.7.6-050706-generic    | 1         | 1.3%    |
| 5.4.0-96-lowlatency     | 1         | 1.3%    |
| 5.4.0-88-lowlatency     | 1         | 1.3%    |
| 5.4.0-52-generic        | 1         | 1.3%    |
| 5.4.0-45-generic        | 1         | 1.3%    |
| 5.4.0-34-lowlatency     | 1         | 1.3%    |
| 5.4.0-26-lowlatency     | 1         | 1.3%    |
| 5.4.0-132-lowlatency    | 1         | 1.3%    |
| 5.4.0-107-lowlatency    | 1         | 1.3%    |
| 5.4.0-100-lowlatency    | 1         | 1.3%    |
| 5.3.0-19-lowlatency     | 1         | 1.3%    |
| 5.19.0-1024-lowlatency  | 1         | 1.3%    |
| 5.19.0-1017-lowlatency  | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 26.67%  |
| 5.15.0  | 19        | 25.33%  |
| 5.8.0   | 9         | 12%     |
| 5.11.0  | 9         | 12%     |
| 5.13.0  | 6         | 8%      |
| 5.19.0  | 5         | 6.67%   |
| 6.2.0   | 2         | 2.67%   |
| 4.15.0  | 2         | 2.67%   |
| 6.2.8   | 1         | 1.33%   |
| 5.7.6   | 1         | 1.33%   |
| 5.3.0   | 1         | 1.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 20        | 26.67%  |
| 5.15    | 19        | 25.33%  |
| 5.8     | 9         | 12%     |
| 5.11    | 9         | 12%     |
| 5.13    | 6         | 8%      |
| 5.19    | 5         | 6.67%   |
| 6.2     | 3         | 4%      |
| 4.15    | 2         | 2.67%   |
| 5.7     | 1         | 1.33%   |
| 5.3     | 1         | 1.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 74        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 37        | 50%     |
| KDE5  | 31        | 41.89%  |
| GNOME | 5         | 6.76%   |
| LXQt  | 1         | 1.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 71        | 95.95%  |
| Wayland | 3         | 4.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 26        | 35.14%  |
| TDM     | 21        | 28.38%  |
| LightDM | 21        | 28.38%  |
| GDM     | 5         | 6.76%   |
| LXDM    | 1         | 1.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 31        | 41.33%  |
| fr_FR   | 13        | 17.33%  |
| C       | 4         | 5.33%   |
| de_DE   | 3         | 4%      |
| ru_RU   | 2         | 2.67%   |
| pt_BR   | 2         | 2.67%   |
| it_IT   | 2         | 2.67%   |
| es_ES   | 2         | 2.67%   |
| en_GB   | 2         | 2.67%   |
| en_CA   | 2         | 2.67%   |
| Unknown | 2         | 2.67%   |
| nl_NL   | 1         | 1.33%   |
| hu_HU   | 1         | 1.33%   |
| es_NI   | 1         | 1.33%   |
| es_MX   | 1         | 1.33%   |
| es_CR   | 1         | 1.33%   |
| en_NG   | 1         | 1.33%   |
| en_IE   | 1         | 1.33%   |
| en_AU   | 1         | 1.33%   |
| en_AG   | 1         | 1.33%   |
| de_CH   | 1         | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 50        | 67.57%  |
| BIOS | 24        | 32.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 70        | 94.59%  |
| Overlay | 4         | 5.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 53        | 71.62%  |
| MBR  | 21        | 28.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 88%     |
| Yes       | 9         | 12%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 51.35%  |
| No        | 36        | 48.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 20        | 27.03%  |
| Hewlett-Packard        | 13        | 17.57%  |
| Dell                   | 12        | 16.22%  |
| ASUSTek Computer       | 9         | 12.16%  |
| Acer                   | 3         | 4.05%   |
| Toshiba                | 2         | 2.7%    |
| HUAWEI                 | 2         | 2.7%    |
| Apple                  | 2         | 2.7%    |
| Sony                   | 1         | 1.35%   |
| Samsung Electronics    | 1         | 1.35%   |
| Razer                  | 1         | 1.35%   |
| Intel Client Systems   | 1         | 1.35%   |
| GPU Company            | 1         | 1.35%   |
| Google                 | 1         | 1.35%   |
| Gigabyte Technology    | 1         | 1.35%   |
| Getac                  | 1         | 1.35%   |
| COM1                   | 1         | 1.35%   |
| Clevo                  | 1         | 1.35%   |
| Avell High Performance | 1         | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G50-45 80E3                       | 2         | 2.7%    |
| HP Pavilion dv6                          | 2         | 2.7%    |
| Toshiba Satellite L755D                  | 1         | 1.35%   |
| Toshiba Satellite C855                   | 1         | 1.35%   |
| Sony VGN-NS31M_W                         | 1         | 1.35%   |
| Samsung 305V4A/305V5A                    | 1         | 1.35%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 1.35%   |
| Lenovo ThinkPad X250 20CL001LMB          | 1         | 1.35%   |
| Lenovo ThinkPad X230 2333A86             | 1         | 1.35%   |
| Lenovo ThinkPad X230 2325AJG             | 1         | 1.35%   |
| Lenovo ThinkPad X230 23245S1             | 1         | 1.35%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 1         | 1.35%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 1.35%   |
| Lenovo ThinkPad W530 2447IG0             | 1         | 1.35%   |
| Lenovo ThinkPad T530 24296HG             | 1         | 1.35%   |
| Lenovo ThinkPad T520 4243K86             | 1         | 1.35%   |
| Lenovo ThinkPad L460 20FVS3JK00          | 1         | 1.35%   |
| Lenovo ThinkPad E14 Gen 3 20Y70073GE     | 1         | 1.35%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.35%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 1.35%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 1.35%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 1.35%   |
| Lenovo IdeaPad 3 15ABA7 82RN             | 1         | 1.35%   |
| Lenovo IdeaPad 3 14ARE05 81W3            | 1         | 1.35%   |
| Lenovo G70-80 80FF                       | 1         | 1.35%   |
| Intel Client Systems LAPBC510            | 1         | 1.35%   |
| HUAWEI KLVL-WXXW                         | 1         | 1.35%   |
| HUAWEI HLYL-WXX9                         | 1         | 1.35%   |
| HP ZBook 15 G3                           | 1         | 1.35%   |
| HP Stream Laptop 14-cb0XX                | 1         | 1.35%   |
| HP Sona                                  | 1         | 1.35%   |
| HP Pavilion dv8                          | 1         | 1.35%   |
| HP OMEN by Laptop 15-ce0xx               | 1         | 1.35%   |
| HP Notebook                              | 1         | 1.35%   |
| HP Laptop 15s-fq1xxx                     | 1         | 1.35%   |
| HP EliteBook 840 G3                      | 1         | 1.35%   |
| HP EliteBook 745 G3                      | 1         | 1.35%   |
| HP EliteBook 735 G6                      | 1         | 1.35%   |
| HP Compaq 8510p                          | 1         | 1.35%   |
| GPU Company GWNR71517                    | 1         | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 11        | 14.86%  |
| Lenovo IdeaPad                | 5         | 6.76%   |
| Dell Latitude                 | 5         | 6.76%   |
| Dell Inspiron                 | 5         | 6.76%   |
| HP Pavilion                   | 3         | 4.05%   |
| HP EliteBook                  | 3         | 4.05%   |
| Toshiba Satellite             | 2         | 2.7%    |
| Lenovo G50-45                 | 2         | 2.7%    |
| Acer Aspire                   | 2         | 2.7%    |
| Sony VGN-NS31M                | 1         | 1.35%   |
| Samsung 305V4A                | 1         | 1.35%   |
| Razer Blade                   | 1         | 1.35%   |
| Lenovo Legion                 | 1         | 1.35%   |
| Lenovo G70-80                 | 1         | 1.35%   |
| Intel Client Systems LAPBC510 | 1         | 1.35%   |
| HUAWEI KLVL-WXXW              | 1         | 1.35%   |
| HUAWEI HLYL-WXX9              | 1         | 1.35%   |
| HP ZBook                      | 1         | 1.35%   |
| HP Stream                     | 1         | 1.35%   |
| HP Sona                       | 1         | 1.35%   |
| HP OMEN                       | 1         | 1.35%   |
| HP Notebook                   | 1         | 1.35%   |
| HP Laptop                     | 1         | 1.35%   |
| HP Compaq                     | 1         | 1.35%   |
| GPU Company GWNR71517         | 1         | 1.35%   |
| Google Nami                   | 1         | 1.35%   |
| Gigabyte AERO                 | 1         | 1.35%   |
| Getac S400G3                  | 1         | 1.35%   |
| Dell XPS                      | 1         | 1.35%   |
| Dell Precision                | 1         | 1.35%   |
| COM1 NBINF-X5-9G5             | 1         | 1.35%   |
| Clevo W35                     | 1         | 1.35%   |
| Avell High Performance Avell  | 1         | 1.35%   |
| ASUS X541NA                   | 1         | 1.35%   |
| ASUS VivoBook                 | 1         | 1.35%   |
| ASUS UX305FA                  | 1         | 1.35%   |
| ASUS U56E                     | 1         | 1.35%   |
| ASUS TP300UA                  | 1         | 1.35%   |
| ASUS ROG                      | 1         | 1.35%   |
| ASUS K53U                     | 1         | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 9         | 12.16%  |
| 2012 | 9         | 12.16%  |
| 2019 | 7         | 9.46%   |
| 2016 | 7         | 9.46%   |
| 2014 | 7         | 9.46%   |
| 2021 | 6         | 8.11%   |
| 2011 | 6         | 8.11%   |
| 2018 | 4         | 5.41%   |
| 2017 | 4         | 5.41%   |
| 2015 | 4         | 5.41%   |
| 2008 | 4         | 5.41%   |
| 2010 | 2         | 2.7%    |
| 2009 | 2         | 2.7%    |
| 2007 | 2         | 2.7%    |
| 2022 | 1         | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 74        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 66        | 89.19%  |
| Enabled  | 8         | 10.81%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 72        | 97.3%   |
| Yes  | 2         | 2.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 32        | 42.67%  |
| 8.01-16.0  | 13        | 17.33%  |
| 16.01-24.0 | 12        | 16%     |
| 3.01-4.0   | 8         | 10.67%  |
| 32.01-64.0 | 5         | 6.67%   |
| 24.01-32.0 | 2         | 2.67%   |
| 2.01-3.0   | 2         | 2.67%   |
| 1.01-2.0   | 1         | 1.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 28        | 36.36%  |
| 2.01-3.0  | 20        | 25.97%  |
| 3.01-4.0  | 14        | 18.18%  |
| 4.01-8.0  | 12        | 15.58%  |
| 8.01-16.0 | 2         | 2.6%    |
| 0.51-1.0  | 1         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 70.67%  |
| 2      | 19        | 25.33%  |
| 0      | 2         | 2.67%   |
| 4      | 1         | 1.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 66.67%  |
| Yes       | 25        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 81.08%  |
| No        | 14        | 18.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 98.65%  |
| No        | 1         | 1.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 77.03%  |
| No        | 17        | 22.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 15        | 20.27%  |
| France      | 11        | 14.86%  |
| Germany     | 7         | 9.46%   |
| Russia      | 4         | 5.41%   |
| Canada      | 4         | 5.41%   |
| UK          | 3         | 4.05%   |
| Spain       | 3         | 4.05%   |
| Italy       | 3         | 4.05%   |
| Netherlands | 2         | 2.7%    |
| Ivory Coast | 2         | 2.7%    |
| Costa Rica  | 2         | 2.7%    |
| Brazil      | 2         | 2.7%    |
| Yemen       | 1         | 1.35%   |
| Turkey      | 1         | 1.35%   |
| Taiwan      | 1         | 1.35%   |
| Switzerland | 1         | 1.35%   |
| Poland      | 1         | 1.35%   |
| Peru        | 1         | 1.35%   |
| Norway      | 1         | 1.35%   |
| Nigeria     | 1         | 1.35%   |
| Nicaragua   | 1         | 1.35%   |
| Mexico      | 1         | 1.35%   |
| Indonesia   | 1         | 1.35%   |
| Hungary     | 1         | 1.35%   |
| Finland     | 1         | 1.35%   |
| Bulgaria    | 1         | 1.35%   |
| Austria     | 1         | 1.35%   |
| Australia   | 1         | 1.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Montreal       | 2         | 2.67%   |
| Madrid         | 2         | 2.67%   |
| Hamburg        | 2         | 2.67%   |
| Groningen      | 2         | 2.67%   |
| Denver         | 2         | 2.67%   |
| Béziers       | 2         | 2.67%   |
| Abidjan        | 2         | 2.67%   |
| Yonkers        | 1         | 1.33%   |
| Yekaterinburg  | 1         | 1.33%   |
| Wroclaw        | 1         | 1.33%   |
| Woonsocket     | 1         | 1.33%   |
| Woodland Park  | 1         | 1.33%   |
| Warner Robins  | 1         | 1.33%   |
| Vienna         | 1         | 1.33%   |
| Velleron       | 1         | 1.33%   |
| Turin          | 1         | 1.33%   |
| Tarragona      | 1         | 1.33%   |
| Taipei         | 1         | 1.33%   |
| Sunderland     | 1         | 1.33%   |
| Stuttgart      | 1         | 1.33%   |
| Stabekk        | 1         | 1.33%   |
| St Petersburg  | 1         | 1.33%   |
| Sofia          | 1         | 1.33%   |
| Sleman         | 1         | 1.33%   |
| Seropedica     | 1         | 1.33%   |
| Sanaa          | 1         | 1.33%   |
| San Juan       | 1         | 1.33%   |
| Samara         | 1         | 1.33%   |
| Rio de Janeiro | 1         | 1.33%   |
| Ragusa         | 1         | 1.33%   |
| Portland       | 1         | 1.33%   |
| Port Harcourt  | 1         | 1.33%   |
| Phoenix        | 1         | 1.33%   |
| Nudlingen      | 1         | 1.33%   |
| Moscow         | 1         | 1.33%   |
| Mississauga    | 1         | 1.33%   |
| Mexico City    | 1         | 1.33%   |
| Mannheim       | 1         | 1.33%   |
| Managua        | 1         | 1.33%   |
| Madison        | 1         | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 14        | 14     | 15.56%  |
| WDC                         | 13        | 14     | 14.44%  |
| SanDisk                     | 7         | 7      | 7.78%   |
| Toshiba                     | 6         | 6      | 6.67%   |
| Unknown                     | 4         | 4      | 4.44%   |
| SK hynix                    | 4         | 5      | 4.44%   |
| Seagate                     | 4         | 4      | 4.44%   |
| Intel                       | 4         | 6      | 4.44%   |
| Micron Technology           | 3         | 3      | 3.33%   |
| Kingston                    | 3         | 3      | 3.33%   |
| Phison                      | 2         | 2      | 2.22%   |
| Hitachi                     | 2         | 2      | 2.22%   |
| Crucial                     | 2         | 2      | 2.22%   |
| China                       | 2         | 2      | 2.22%   |
| Wibtek                      | 1         | 1      | 1.11%   |
| Union Memory                | 1         | 1      | 1.11%   |
| UMIS                        | 1         | 1      | 1.11%   |
| Team                        | 1         | 1      | 1.11%   |
| SPCC                        | 1         | 1      | 1.11%   |
| Reeinno                     | 1         | 1      | 1.11%   |
| Realtek                     | 1         | 1      | 1.11%   |
| PNY                         | 1         | 1      | 1.11%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.11%   |
| KIOXIA                      | 1         | 1      | 1.11%   |
| KingSpec                    | 1         | 1      | 1.11%   |
| JMicron Technology          | 1         | 1      | 1.11%   |
| Inateck                     | 1         | 1      | 1.11%   |
| HGST                        | 1         | 1      | 1.11%   |
| Fujitsu                     | 1         | 1      | 1.11%   |
| Dogfish                     | 1         | 1      | 1.11%   |
| BHT                         | 1         | 1      | 1.11%   |
| ASMT                        | 1         | 1      | 1.11%   |
| A-DATA Technology           | 1         | 2      | 1.11%   |
| Unknown                     | 1         | 1      | 1.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 2.17%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 2.17%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 2.17%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 2.17%   |
| Samsung SSD 870 EVO 1TB                   | 2         | 2.17%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 2.17%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 2.17%   |
| China SSD 1TB                             | 2         | 2.17%   |
| Wibtek W800S 512GB SSD                    | 1         | 1.09%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 1.09%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 1.09%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 1.09%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 1.09%   |
| WDC WD5000BEKT-60KA9T0 500GB              | 1         | 1.09%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 1.09%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 1.09%   |
| WDC WD3200BEKT-60V5T1 320GB               | 1         | 1.09%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 1.09%   |
| WDC WD10JPVT-75A1YT0 1TB                  | 1         | 1.09%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB      | 1         | 1.09%   |
| Unknown MMC Card  4GB                     | 1         | 1.09%   |
| Unknown MMC Card  16GB                    | 1         | 1.09%   |
| Unknown DA4128  128GB                     | 1         | 1.09%   |
| Unknown 032G34  32GB                      | 1         | 1.09%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB   | 1         | 1.09%   |
| UMIS RPJTJ256MEE1OWX 256GB                | 1         | 1.09%   |
| Toshiba TR150 240GB SSD                   | 1         | 1.09%   |
| Toshiba MK1637GSX 160GB                   | 1         | 1.09%   |
| Team TM8FP4001T 1TB                       | 1         | 1.09%   |
| SPCC Solid State Disk 1TB                 | 1         | 1.09%   |
| SK hynix SKHynix_HFS256GD9TNI-L2A0B 256GB | 1         | 1.09%   |
| SK hynix BC501 NVMe 256GB                 | 1         | 1.09%   |
| Seagate ST9320320AS 320GB                 | 1         | 1.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 1.09%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.09%   |
| Seagate FireCuda 530 ZP4000GM30013 4TB    | 1         | 1.09%   |
| SanDisk SSD PLUS 240GB                    | 1         | 1.09%   |
| SanDisk SD9SN8W128G1002 128GB SSD         | 1         | 1.09%   |
| SanDisk SD8SN8U256G1002 256GB SSD         | 1         | 1.09%   |
| SanDisk SD7SN3Q128G1002 128GB SSD         | 1         | 1.09%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 33.33%  |
| Toshiba             | 5         | 5      | 20.83%  |
| Seagate             | 3         | 3      | 12.5%   |
| Samsung Electronics | 2         | 2      | 8.33%   |
| Hitachi             | 2         | 2      | 8.33%   |
| Inateck             | 1         | 1      | 4.17%   |
| HGST                | 1         | 1      | 4.17%   |
| Fujitsu             | 1         | 1      | 4.17%   |
| ASMT                | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 25%     |
| SanDisk             | 5         | 5      | 15.63%  |
| Micron Technology   | 2         | 2      | 6.25%   |
| Kingston            | 2         | 2      | 6.25%   |
| Crucial             | 2         | 2      | 6.25%   |
| China               | 2         | 2      | 6.25%   |
| Wibtek              | 1         | 1      | 3.13%   |
| WDC                 | 1         | 1      | 3.13%   |
| Toshiba             | 1         | 1      | 3.13%   |
| SPCC                | 1         | 1      | 3.13%   |
| Reeinno             | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| KingSpec            | 1         | 1      | 3.13%   |
| JMicron Technology  | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| Dogfish             | 1         | 1      | 3.13%   |
| BHT                 | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 27        | 32     | 33.75%  |
| HDD  | 24        | 25     | 30%     |
| NVMe | 23        | 31     | 28.75%  |
| MMC  | 6         | 7      | 7.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 53     | 57.5%   |
| NVMe | 23        | 30     | 28.75%  |
| MMC  | 6         | 7      | 7.5%    |
| SAS  | 5         | 5      | 6.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 43     | 73.58%  |
| 0.51-1.0   | 11        | 11     | 20.75%  |
| 1.01-2.0   | 3         | 3      | 5.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 23        | 30.26%  |
| 251-500    | 19        | 25%     |
| 501-1000   | 11        | 14.47%  |
| 21-50      | 7         | 9.21%   |
| 51-100     | 7         | 9.21%   |
| 1001-2000  | 4         | 5.26%   |
| 1-20       | 4         | 5.26%   |
| 2001-3000  | 1         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 30        | 39.47%  |
| 21-50     | 15        | 19.74%  |
| 101-250   | 10        | 13.16%  |
| 251-500   | 7         | 9.21%   |
| 501-1000  | 6         | 7.89%   |
| 51-100    | 6         | 7.89%   |
| 1001-2000 | 2         | 2.63%   |

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
| Works    | 54        | 69     | 68.35%  |
| Malfunc  | 16        | 16     | 20.25%  |
| Detected | 9         | 10     | 11.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 51        | 57.95%  |
| AMD                         | 14        | 15.91%  |
| SK hynix                    | 4         | 4.55%   |
| SanDisk                     | 4         | 4.55%   |
| Samsung Electronics         | 4         | 4.55%   |
| Phison Electronics          | 3         | 3.41%   |
| Union Memory (Shenzhen)     | 2         | 2.27%   |
| Seagate Technology          | 1         | 1.14%   |
| Micron Technology           | 1         | 1.14%   |
| MAXIO Technology (Hangzhou) | 1         | 1.14%   |
| KIOXIA                      | 1         | 1.14%   |
| Kingston Technology Company | 1         | 1.14%   |
| ADATA Technology            | 1         | 1.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 12        | 12.77%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 7.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 6         | 6.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 6         | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 5.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 4         | 4.26%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 3         | 3.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3         | 3.19%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 2         | 2.13%   |
| SK hynix BC511                                                                | 2         | 2.13%   |
| Phison E12 NVMe Controller                                                    | 2         | 2.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 2.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 2         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 2         | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 2         | 2.13%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2         | 2.13%   |
| SK hynix Non-Volatile memory controller                                       | 1         | 1.06%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 1         | 1.06%   |
| Seagate FireCuda 530 SSD                                                      | 1         | 1.06%   |
| SanDisk NVMe Controller                                                       | 1         | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 1.06%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 1.06%   |
| Micron NVMe Storage Controller                                                | 1         | 1.06%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                  | 1         | 1.06%   |
| KIOXIA NVMe SSD Controller BG4                                                | 1         | 1.06%   |
| Kingston Company A2000 NVMe SSD                                               | 1         | 1.06%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 1.06%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 1.06%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 1         | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.06%   |
| Intel NVMe Controller                                                         | 1         | 1.06%   |
| Intel Non-Volatile memory controller                                          | 1         | 1.06%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                   | 1         | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 1.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                  | 1         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 1.06%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 54        | 61.36%  |
| NVMe | 23        | 26.14%  |
| RAID | 7         | 7.95%   |
| IDE  | 4         | 4.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 75.68%  |
| AMD    | 18        | 24.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-2450M CPU @ 2.50GHz      | 3         | 4.05%   |
| AMD Ryzen 5 4600H with Radeon Graphics | 3         | 4.05%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 2.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 2         | 2.7%    |
| Intel Core i7-5600U CPU @ 2.60GHz      | 2         | 2.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics | 2         | 2.7%    |
| Intel Processor 5Y10 CPU @ 0.80GHz     | 1         | 1.35%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.35%   |
| Intel Genuine CPU U2300 @ 1.20GHz      | 1         | 1.35%   |
| Intel Core i9-8950HK CPU @ 2.90GHz     | 1         | 1.35%   |
| Intel Core i7-9750H CPU @ 2.60GHz      | 1         | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 1.35%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 1         | 1.35%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 1         | 1.35%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 1.35%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.35%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz     | 1         | 1.35%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1         | 1.35%   |
| Intel Core i7-3940XM CPU @ 3.00GHz     | 1         | 1.35%   |
| Intel Core i7-3630QM CPU @ 2.40GHz     | 1         | 1.35%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 1         | 1.35%   |
| Intel Core i7-2635QM CPU @ 2.00GHz     | 1         | 1.35%   |
| Intel Core i7-2630QM CPU @ 2.00GHz     | 1         | 1.35%   |
| Intel Core i7-10850H CPU @ 2.70GHz     | 1         | 1.35%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 1.35%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz      | 1         | 1.35%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz      | 1         | 1.35%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 1         | 1.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.35%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 1         | 1.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.35%   |
| Intel Core i5-4310M CPU @ 2.70GHz      | 1         | 1.35%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.35%   |
| Intel Core i5-3340M CPU @ 2.70GHz      | 1         | 1.35%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 1         | 1.35%   |
| Intel Core i5-3230M CPU @ 2.60GHz      | 1         | 1.35%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 1         | 1.35%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz     | 1         | 1.35%   |
| Intel Core i5-10300H CPU @ 2.50GHz     | 1         | 1.35%   |
| Intel Core i5 CPU M 460 @ 2.53GHz      | 1         | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 23        | 31.08%  |
| Intel Core i5      | 16        | 21.62%  |
| AMD Ryzen 5        | 5         | 6.76%   |
| Other              | 4         | 5.41%   |
| Intel Core 2 Duo   | 4         | 5.41%   |
| Intel Celeron      | 4         | 5.41%   |
| AMD Ryzen 7        | 4         | 5.41%   |
| Intel Core i3      | 3         | 4.05%   |
| AMD E              | 2         | 2.7%    |
| Intel Pentium Dual | 1         | 1.35%   |
| Intel Genuine      | 1         | 1.35%   |
| Intel Core i9      | 1         | 1.35%   |
| AMD Ryzen 3 PRO    | 1         | 1.35%   |
| AMD Ryzen 3        | 1         | 1.35%   |
| AMD E2             | 1         | 1.35%   |
| AMD E1             | 1         | 1.35%   |
| AMD A6             | 1         | 1.35%   |
| AMD A4             | 1         | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 37        | 50%     |
| 4      | 24        | 32.43%  |
| 6      | 10        | 13.51%  |
| 8      | 3         | 4.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 74        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 53        | 71.62%  |
| 1      | 21        | 28.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 74        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 7         | 9.33%   |
| 0x306a9    | 6         | 8%      |
| Unknown    | 6         | 8%      |
| 0x306d4    | 5         | 6.67%   |
| 0x906ea    | 4         | 5.33%   |
| 0x08600104 | 4         | 5.33%   |
| 0x806ea    | 3         | 4%      |
| 0x406e3    | 3         | 4%      |
| 0xa0652    | 2         | 2.67%   |
| 0x906e9    | 2         | 2.67%   |
| 0x806c1    | 2         | 2.67%   |
| 0x706e5    | 2         | 2.67%   |
| 0x6fd      | 2         | 2.67%   |
| 0x40651    | 2         | 2.67%   |
| 0x106e5    | 2         | 2.67%   |
| 0x08108109 | 2         | 2.67%   |
| 0x07030105 | 2         | 2.67%   |
| 0x706a1    | 1         | 1.33%   |
| 0x6fb      | 1         | 1.33%   |
| 0x506e3    | 1         | 1.33%   |
| 0x506c9    | 1         | 1.33%   |
| 0x406c4    | 1         | 1.33%   |
| 0x40661    | 1         | 1.33%   |
| 0x306c3    | 1         | 1.33%   |
| 0x1067a    | 1         | 1.33%   |
| 0x10676    | 1         | 1.33%   |
| 0x0a50000c | 1         | 1.33%   |
| 0x08608103 | 1         | 1.33%   |
| 0x08608102 | 1         | 1.33%   |
| 0x08600106 | 1         | 1.33%   |
| 0x08600103 | 1         | 1.33%   |
| 0x07030104 | 1         | 1.33%   |
| 0x06006110 | 1         | 1.33%   |
| 0x0500010d | 1         | 1.33%   |
| 0x05000029 | 1         | 1.33%   |
| 0x03000027 | 1         | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 13.51%  |
| SandyBridge   | 7         | 9.46%   |
| Zen 2         | 6         | 8.11%   |
| IvyBridge     | 6         | 8.11%   |
| Broadwell     | 6         | 8.11%   |
| Skylake       | 5         | 6.76%   |
| Haswell       | 4         | 5.41%   |
| Puma          | 3         | 4.05%   |
| Penryn        | 3         | 4.05%   |
| Core          | 3         | 4.05%   |
| Zen+          | 2         | 2.7%    |
| TigerLake     | 2         | 2.7%    |
| Nehalem       | 2         | 2.7%    |
| IceLake       | 2         | 2.7%    |
| CometLake     | 2         | 2.7%    |
| Bobcat        | 2         | 2.7%    |
| Unknown       | 2         | 2.7%    |
| Zen 3         | 1         | 1.35%   |
| Westmere      | 1         | 1.35%   |
| Silvermont    | 1         | 1.35%   |
| K10 Llano     | 1         | 1.35%   |
| Goldmont plus | 1         | 1.35%   |
| Goldmont      | 1         | 1.35%   |
| Excavator     | 1         | 1.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 50        | 53.19%  |
| AMD    | 23        | 24.47%  |
| Nvidia | 21        | 22.34%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 7         | 7.29%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 6.25%   |
| AMD Renoir                                                                | 6         | 6.25%   |
| Intel HD Graphics 5500                                                    | 5         | 5.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 5         | 5.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 4.17%   |
| Intel UHD Graphics 620                                                    | 3         | 3.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 3.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 2.08%   |
| Nvidia TU117M                                                             | 2         | 2.08%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 2.08%   |
| Nvidia GK208BM [GeForce 920M]                                             | 2         | 2.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 2.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 2.08%   |
| AMD Wrestler [Radeon HD 6310]                                             | 2         | 2.08%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 2.08%   |
| AMD Lucienne                                                              | 2         | 2.08%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 1.04%   |
| Nvidia GT216M [GeForce GT 230M]                                           | 1         | 1.04%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 1         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.04%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 1.04%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 1.04%   |
| Nvidia GK107M [GeForce GTX 660M]                                          | 1         | 1.04%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 1.04%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 1.04%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.04%   |
| Nvidia GF108M [GeForce GT 525M]                                           | 1         | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 1.04%   |
| Intel Iris Plus Graphics G7                                               | 1         | 1.04%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.04%   |
| Intel HD Graphics 630                                                     | 1         | 1.04%   |
| Intel HD Graphics 5300                                                    | 1         | 1.04%   |
| Intel HD Graphics 530                                                     | 1         | 1.04%   |
| Intel HD Graphics 500                                                     | 1         | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 44.59%  |
| 1 x AMD        | 17        | 22.97%  |
| Intel + Nvidia | 15        | 20.27%  |
| 1 x Nvidia     | 3         | 4.05%   |
| AMD + Nvidia   | 3         | 4.05%   |
| Intel + AMD    | 2         | 2.7%    |
| 2 x AMD        | 1         | 1.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 69        | 93.24%  |
| Proprietary | 5         | 6.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 54.05%  |
| 0.01-0.5   | 11        | 14.86%  |
| 0.51-1.0   | 10        | 13.51%  |
| 1.01-2.0   | 7         | 9.46%   |
| 3.01-4.0   | 4         | 5.41%   |
| 5.01-6.0   | 2         | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 17        | 20%     |
| AU Optronics            | 15        | 17.65%  |
| BOE                     | 11        | 12.94%  |
| Samsung Electronics     | 10        | 11.76%  |
| Chimei Innolux          | 10        | 11.76%  |
| Lenovo                  | 3         | 3.53%   |
| Sharp                   | 2         | 2.35%   |
| Hewlett-Packard         | 2         | 2.35%   |
| Chi Mei Optoelectronics | 2         | 2.35%   |
| Apple                   | 2         | 2.35%   |
| Philips                 | 1         | 1.18%   |
| LG Philips              | 1         | 1.18%   |
| Iiyama                  | 1         | 1.18%   |
| Hannspree               | 1         | 1.18%   |
| Dell                    | 1         | 1.18%   |
| CPT                     | 1         | 1.18%   |
| BenQ                    | 1         | 1.18%   |
| ASUSTek Computer        | 1         | 1.18%   |
| Arnos Instruments       | 1         | 1.18%   |
| Ancor Communications    | 1         | 1.18%   |
| Acer                    | 1         | 1.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 2.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 2.35%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 2.35%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 2.35%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 2.35%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 2.35%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 1.18%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 1.18%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch  | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch | 1         | 1.18%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 1.18%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 1.18%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch              | 1         | 1.18%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 1.18%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 1         | 1.18%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 1         | 1.18%   |
| Hewlett-Packard E242 HWP326F 1920x1080 518x324mm 24.1-inch            | 1         | 1.18%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch             | 1         | 1.18%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                  | 1         | 1.18%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 1.18%   |
| CPT LCD Monitor CPT141F 1280x800 331x207mm 15.4-inch                  | 1         | 1.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 49.35%  |
| 1366x768 (WXGA)    | 22        | 28.57%  |
| 1600x900 (HD+)     | 5         | 6.49%   |
| 3840x2160 (4K)     | 3         | 3.9%    |
| 1680x1050 (WSXGA+) | 2         | 2.6%    |
| 1280x800 (WXGA)    | 2         | 2.6%    |
| 2880x1800          | 1         | 1.3%    |
| 2560x1440 (QHD)    | 1         | 1.3%    |
| 2160x1440          | 1         | 1.3%    |
| 1920x1200 (WUXGA)  | 1         | 1.3%    |
| 1440x900 (WXGA+)   | 1         | 1.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 42        | 49.41%  |
| 13     | 11        | 12.94%  |
| 14     | 8         | 9.41%   |
| 24     | 5         | 5.88%   |
| 12     | 5         | 5.88%   |
| 27     | 2         | 2.35%   |
| 21     | 2         | 2.35%   |
| 19     | 2         | 2.35%   |
| 18     | 2         | 2.35%   |
| 17     | 2         | 2.35%   |
| 84     | 1         | 1.18%   |
| 23     | 1         | 1.18%   |
| 20     | 1         | 1.18%   |
| 16     | 1         | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 65.48%  |
| 201-300     | 11        | 13.1%   |
| 501-600     | 7         | 8.33%   |
| 401-500     | 7         | 8.33%   |
| 351-400     | 3         | 3.57%   |
| 1501-2000   | 1         | 1.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 65        | 85.53%  |
| 16/10 | 10        | 13.16%  |
| 3/2   | 1         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 43        | 50.59%  |
| 81-90          | 14        | 16.47%  |
| 71-80          | 5         | 5.88%   |
| 61-70          | 5         | 5.88%   |
| 201-250        | 4         | 4.71%   |
| 151-200        | 4         | 4.71%   |
| 251-300        | 3         | 3.53%   |
| 301-350        | 2         | 2.35%   |
| 141-150        | 2         | 2.35%   |
| More than 1000 | 1         | 1.18%   |
| 131-140        | 1         | 1.18%   |
| 121-130        | 1         | 1.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 38        | 45.78%  |
| 101-120       | 23        | 27.71%  |
| 51-100        | 13        | 15.66%  |
| 161-240       | 8         | 9.64%   |
| More than 240 | 1         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 63        | 82.89%  |
| 2     | 12        | 15.79%  |
| 3     | 1         | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 47        | 40.17%  |
| Realtek Semiconductor             | 39        | 33.33%  |
| Qualcomm Atheros                  | 13        | 11.11%  |
| Broadcom                          | 6         | 5.13%   |
| ASIX Electronics                  | 3         | 2.56%   |
| Ralink                            | 2         | 1.71%   |
| Ericsson Business Mobile Networks | 2         | 1.71%   |
| Motorola PCS                      | 1         | 0.85%   |
| MediaTek                          | 1         | 0.85%   |
| Marvell Technology Group          | 1         | 0.85%   |
| Huawei Technologies               | 1         | 0.85%   |
| Broadcom Limited                  | 1         | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 22        | 15.49%  |
| Intel Wireless 7265                                                | 8         | 5.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 7         | 4.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 5         | 3.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 5         | 3.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 5         | 3.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 4         | 2.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 3         | 2.11%   |
| Intel Wireless 8265 / 8275                                         | 3         | 2.11%   |
| Intel Wireless 8260                                                | 3         | 2.11%   |
| Intel Wireless 7260                                                | 3         | 2.11%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 2.11%   |
| Intel Centrino Ultimate-N 6300                                     | 3         | 2.11%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 2.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 2         | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 2         | 1.41%   |
| Realtek 802.11ac NIC                                               | 2         | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.41%   |
| Intel WiFi Link 5100                                               | 2         | 1.41%   |
| Intel Wi-Fi 6 AX201                                                | 2         | 1.41%   |
| Intel Ethernet Connection (3) I218-LM                              | 2         | 1.41%   |
| Intel 82567LM Gigabit Network Connection                           | 2         | 1.41%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                      | 2         | 1.41%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller        | 1         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 1         | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                         | 1         | 0.7%    |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]   | 1         | 0.7%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller          | 1         | 0.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 1         | 0.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                              | 1         | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                         | 1         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                      | 1         | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                           | 1         | 0.7%    |
| Motorola PCS Moto E (4) Plus                                       | 1         | 0.7%    |
| MediaTek TECNO SPARK 9T                                            | 1         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 60.81%  |
| Realtek Semiconductor | 13        | 17.57%  |
| Qualcomm Atheros      | 9         | 12.16%  |
| Broadcom              | 4         | 5.41%   |
| Ralink                | 2         | 2.7%    |
| Broadcom Limited      | 1         | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 8         | 10.67%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 5         | 6.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 5         | 6.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 4         | 5.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 3         | 4%      |
| Intel Wireless 8265 / 8275                                       | 3         | 4%      |
| Intel Wireless 8260                                              | 3         | 4%      |
| Intel Wireless 7260                                              | 3         | 4%      |
| Intel Wi-Fi 6 AX200                                              | 3         | 4%      |
| Intel Centrino Ultimate-N 6300                                   | 3         | 4%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 2.67%   |
| Realtek 802.11ac NIC                                             | 2         | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 2         | 2.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 2.67%   |
| Intel WiFi Link 5100                                             | 2         | 2.67%   |
| Intel Wi-Fi 6 AX201                                              | 2         | 2.67%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 2.67%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller      | 1         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.33%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1.33%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 1.33%   |
| Intel Wireless-AC 9260                                           | 1         | 1.33%   |
| Intel Wireless 3160                                              | 1         | 1.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 1.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 1         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 1.33%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 1         | 1.33%   |
| Intel Centrino Wireless-N 6150                                   | 1         | 1.33%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 1         | 1.33%   |
| Intel Centrino Wireless-N + WiMAX 6150                           | 1         | 1.33%   |
| Intel Centrino Advanced-N 6200                                   | 1         | 1.33%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 1         | 1.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                      | 1         | 1.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                   | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 46.03%  |
| Intel                    | 21        | 33.33%  |
| Qualcomm Atheros         | 5         | 7.94%   |
| Broadcom                 | 3         | 4.76%   |
| ASIX Electronics         | 3         | 4.76%   |
| MediaTek                 | 1         | 1.59%   |
| Marvell Technology Group | 1         | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 34.92%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 11.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 7.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.17%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 3.17%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.59%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.59%   |
| MediaTek TECNO SPARK 9T                                           | 1         | 1.59%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.59%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.59%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.59%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.59%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.59%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.59%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.59%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.59%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.59%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 1.59%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 53.28%  |
| Ethernet | 60        | 43.8%   |
| Modem    | 3         | 2.19%   |
| Unknown  | 1         | 0.73%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 84.42%  |
| Ethernet | 12        | 15.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 56        | 75.68%  |
| 1     | 17        | 22.97%  |
| 0     | 1         | 1.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 54        | 72.97%  |
| Yes  | 20        | 27.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 52.63%  |
| Realtek Semiconductor           | 6         | 10.53%  |
| Broadcom                        | 5         | 8.77%   |
| Qualcomm Atheros Communications | 4         | 7.02%   |
| Realtek                         | 2         | 3.51%   |
| Ralink Technology               | 2         | 3.51%   |
| Lite-On Technology              | 2         | 3.51%   |
| Hewlett-Packard                 | 2         | 3.51%   |
| Apple                           | 2         | 3.51%   |
| Foxconn International           | 1         | 1.75%   |
| Dell                            | 1         | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 17        | 29.82%  |
| Realtek Bluetooth Radio                           | 4         | 7.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 4         | 7.02%   |
| Intel AX201 Bluetooth                             | 4         | 7.02%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 4         | 7.02%   |
| Intel AX200 Bluetooth                             | 3         | 5.26%   |
| Realtek Bluetooth Radio                           | 2         | 3.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 3.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 3.51%   |
| Apple Bluetooth Host Controller                   | 2         | 3.51%   |
| Realtek RTL8723B Bluetooth                        | 1         | 1.75%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 1.75%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 1.75%   |
| Ralink CSR BS8510                                 | 1         | 1.75%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 1.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 1.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1.75%   |
| Intel Bluetooth Device                            | 1         | 1.75%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 1.75%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 1.75%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.75%   |
| Dell Wireless 370 Bluetooth Mini-card             | 1         | 1.75%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 56        | 54.37%  |
| AMD                        | 21        | 20.39%  |
| Nvidia                     | 17        | 16.5%   |
| Yealink Network Technology | 1         | 0.97%   |
| Yamaha                     | 1         | 0.97%   |
| QinHeng Electronics        | 1         | 0.97%   |
| Mackie Designs             | 1         | 0.97%   |
| Logitech                   | 1         | 0.97%   |
| Focusrite-Novation         | 1         | 0.97%   |
| C-Media Electronics        | 1         | 0.97%   |
| BR23                       | 1         | 0.97%   |
| Behringer.......           | 1         | 0.97%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 7.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 6.3%    |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 5.51%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 5.51%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 4.72%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 4.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 3.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 3.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 3.15%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 3.15%   |
| AMD FCH Azalia Controller                                                  | 4         | 3.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.36%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.57%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 1.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.57%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.57%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.57%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.57%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.57%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.57%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.57%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.57%   |
| Yealink Network Technology VoIP Phone                                      | 1         | 0.79%   |
| Yamaha Steinberg UR242                                                     | 1         | 0.79%   |
| QinHeng Electronics CH345 MIDI adapter                                     | 1         | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.79%   |
| Mackie Designs BIG KNOB STUDIO+                                            | 1         | 0.79%   |
| Logitech 960 Headset                                                       | 1         | 0.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 31.82%  |
| SK hynix            | 24        | 27.27%  |
| Micron Technology   | 10        | 11.36%  |
| Kingston            | 9         | 10.23%  |
| Unknown             | 3         | 3.41%   |
| Ramaxel Technology  | 3         | 3.41%   |
| Timetec             | 2         | 2.27%   |
| Nanya Technology    | 2         | 2.27%   |
| Crucial             | 2         | 2.27%   |
| Transcend           | 1         | 1.14%   |
| G.Skill             | 1         | 1.14%   |
| Corsair             | 1         | 1.14%   |
| A-DATA Technology   | 1         | 1.14%   |
| Unknown             | 1         | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s          | 3         | 3.13%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 3         | 3.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 3         | 3.13%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s            | 3         | 3.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 2.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 2.08%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s          | 2         | 2.08%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s           | 2         | 2.08%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s           | 2         | 2.08%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 2         | 2.08%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 2         | 2.08%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                | 1         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                   | 1         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2                           | 1         | 1.04%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.04%   |
| Timetec RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.04%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 1.04%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s                 | 1         | 1.04%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s            | 1         | 1.04%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.04%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.04%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s       | 1         | 1.04%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.04%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM 1334MT/s            | 1         | 1.04%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s          | 1         | 1.04%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.04%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s    | 1         | 1.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 1.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s | 1         | 1.04%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s          | 1         | 1.04%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB DDR4 2400MT/s                 | 1         | 1.04%   |
| Samsung RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.04%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 1.04%   |
| Samsung RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 1.04%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.04%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s           | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 38        | 49.35%  |
| DDR4   | 27        | 35.06%  |
| DDR2   | 5         | 6.49%   |
| SDRAM  | 3         | 3.9%    |
| LPDDR4 | 2         | 2.6%    |
| LPDDR3 | 2         | 2.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 87.01%  |
| Row Of Chips | 8         | 10.39%  |
| Chip         | 1         | 1.3%    |
| Unknown      | 1         | 1.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 36        | 41.38%  |
| 8192  | 29        | 33.33%  |
| 2048  | 10        | 11.49%  |
| 16384 | 8         | 9.2%    |
| 1024  | 3         | 3.45%   |
| 32768 | 1         | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 38.27%  |
| 3200    | 11        | 13.58%  |
| 2667    | 9         | 11.11%  |
| 1334    | 8         | 9.88%   |
| 2400    | 5         | 6.17%   |
| 2133    | 4         | 4.94%   |
| 1333    | 3         | 3.7%    |
| 667     | 3         | 3.7%    |
| 4267    | 2         | 2.47%   |
| 4199    | 2         | 2.47%   |
| 1639    | 1         | 1.23%   |
| 800     | 1         | 1.23%   |
| Unknown | 1         | 1.23%   |

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
| Chicony Electronics                    | 18        | 27.69%  |
| IMC Networks                           | 8         | 12.31%  |
| Sunplus Innovation Technology          | 5         | 7.69%   |
| Suyin                                  | 4         | 6.15%   |
| Realtek Semiconductor                  | 4         | 6.15%   |
| Microdia                               | 4         | 6.15%   |
| Syntek                                 | 3         | 4.62%   |
| Quanta                                 | 3         | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.62%   |
| Lite-On Technology                     | 2         | 3.08%   |
| Bison Electronics                      | 2         | 3.08%   |
| ViewQuest Technologies                 | 1         | 1.54%   |
| Silicon Motion                         | 1         | 1.54%   |
| Ricoh                                  | 1         | 1.54%   |
| Philips (or NXP)                       | 1         | 1.54%   |
| Logitech                               | 1         | 1.54%   |
| Importek                               | 1         | 1.54%   |
| HRY                                    | 1         | 1.54%   |
| Apple                                  | 1         | 1.54%   |
| Acer                                   | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera             | 4         | 6.06%   |
| Chicony Integrated Camera                  | 4         | 6.06%   |
| Syntek Integrated Camera                   | 3         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam          | 3         | 4.55%   |
| Chicony Integrated Camera [ThinkPad]       | 3         | 4.55%   |
| Suyin Asus Integrated Webcam               | 2         | 3.03%   |
| Sunplus Integrated_Webcam_HD               | 2         | 3.03%   |
| Sunplus HD WebCam                          | 2         | 3.03%   |
| Realtek Lenovo EasyCamera                  | 2         | 3.03%   |
| Microdia Integrated_Webcam_HD              | 2         | 3.03%   |
| Chicony HP HD Camera                       | 2         | 3.03%   |
| Chicony HD Webcam                          | 2         | 3.03%   |
| ViewQuest Ability GABB Webcam              | 1         | 1.52%   |
| Suyin HP Webcam                            | 1         | 1.52%   |
| Suyin HP TrueVision HD Integrated Webcam   | 1         | 1.52%   |
| Sunplus Dell HD Webcam                     | 1         | 1.52%   |
| Silicon Motion WebCam SCB-1100N            | 1         | 1.52%   |
| Ricoh Sony Vaio Integrated Webcam          | 1         | 1.52%   |
| Realtek VGA WebCam                         | 1         | 1.52%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.52%   |
| Quanta ov9734_techfront_camera             | 1         | 1.52%   |
| Quanta HP Webcam                           | 1         | 1.52%   |
| Quanta HP TrueVision HD Camera             | 1         | 1.52%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc] | 1         | 1.52%   |
| Microdia Sonix Integrated Webcam           | 1         | 1.52%   |
| Microdia Integrated Webcam HD              | 1         | 1.52%   |
| Logitech C922 Pro Stream Webcam            | 1         | 1.52%   |
| Lite-On Integrated Camera                  | 1         | 1.52%   |
| Lite-On HP HD Camera                       | 1         | 1.52%   |
| Importek TOSHIBA Web Camera - HD           | 1         | 1.52%   |
| IMC Networks UVC VGA Webcam                | 1         | 1.52%   |
| HRY USB Camera                             | 1         | 1.52%   |
| Chicony Lenovo Integrated Camera (0.3MP)   | 1         | 1.52%   |
| Chicony Integrated IR Camera               | 1         | 1.52%   |
| Chicony HP Wide Vision HD Camera           | 1         | 1.52%   |
| Chicony HP TrueVision HD                   | 1         | 1.52%   |
| Chicony HD User Facing                     | 1         | 1.52%   |
| Chicony CNFA078                            | 1         | 1.52%   |
| Chicony CNF9055 Toshiba Webcam             | 1         | 1.52%   |
| Chicony 4-Port Hub                         | 1         | 1.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 46.67%  |
| Shenzhen Goodix Technology | 3         | 20%     |
| Synaptics                  | 2         | 13.33%  |
| LighTuning Technology      | 1         | 6.67%   |
| Focal-systems.Corp         | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 13.33%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 13.33%  |
| Shenzhen Goodix  Fingerprint Device                        | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 6.67%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                       | 1         | 6.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 6.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 6.67%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 6.67%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 40%     |
| Upek        | 3         | 30%     |
| Alcor Micro | 2         | 20%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 38        | 51.35%  |
| 1     | 31        | 41.89%  |
| 2     | 4         | 5.41%   |
| 3     | 1         | 1.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 38.46%  |
| Graphics card         | 9         | 23.08%  |
| Chipcard              | 9         | 23.08%  |
| Net/wireless          | 2         | 5.13%   |
| Multimedia controller | 2         | 5.13%   |
| Camera                | 2         | 5.13%   |

