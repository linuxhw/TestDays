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

Total: 95

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ab3c1508f9](https://linux-hardware.org/?probe=ab3c1508f9) | Aug 30, 2023 |
| Toshiba       | Satellite A505              | [a7b1465809](https://linux-hardware.org/?probe=a7b1465809) | Aug 25, 2023 |
| Acer          | Nitro AN515-55              | [191aa2a04f](https://linux-hardware.org/?probe=191aa2a04f) | Aug 04, 2023 |
| Toshiba       | Satellite L505              | [bab52bec2c](https://linux-hardware.org/?probe=bab52bec2c) | Aug 04, 2023 |
| win elemen... | MoreFine S500+              | [d3718d1a8d](https://linux-hardware.org/?probe=d3718d1a8d) | Jul 16, 2023 |
| ASUSTek       | G73Jh                       | [60e43d39b2](https://linux-hardware.org/?probe=60e43d39b2) | Jul 10, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV03     | [c2a4d4d2c0](https://linux-hardware.org/?probe=c2a4d4d2c0) | Jun 17, 2023 |
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
| Ubuntu Studio 20.04 | 38        | 46.34%  |
| Ubuntu Studio 22.04 | 23        | 28.05%  |
| Ubuntu Studio 23.04 | 5         | 6.1%    |
| Ubuntu Studio 22.10 | 4         | 4.88%   |
| Ubuntu Studio 21.10 | 3         | 3.66%   |
| Ubuntu Studio 21.04 | 3         | 3.66%   |
| Ubuntu Studio 20.10 | 3         | 3.66%   |
| Ubuntu Studio 18.04 | 2         | 2.44%   |
| Ubuntu Studio 19.10 | 1         | 1.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 81        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.0-1003-lowlatency   | 3         | 3.57%   |
| 5.4.0-52-lowlatency     | 3         | 3.57%   |
| 5.15.0-56-lowlatency    | 3         | 3.57%   |
| 5.15.0-47-lowlatency    | 3         | 3.57%   |
| 5.13.0-28-lowlatency    | 3         | 3.57%   |
| 6.2.0-1009-lowlatency   | 2         | 2.38%   |
| 5.8.0-55-lowlatency     | 2         | 2.38%   |
| 5.4.0-94-lowlatency     | 2         | 2.38%   |
| 5.4.0-65-lowlatency     | 2         | 2.38%   |
| 5.4.0-45-lowlatency     | 2         | 2.38%   |
| 5.4.0-42-lowlatency     | 2         | 2.38%   |
| 5.19.0-1015-lowlatency  | 2         | 2.38%   |
| 5.15.0-67-lowlatency    | 2         | 2.38%   |
| 5.15.0-50-lowlatency    | 2         | 2.38%   |
| 5.15.0-48-lowlatency    | 2         | 2.38%   |
| 5.15.0-46-lowlatency    | 2         | 2.38%   |
| 5.13.0-30-lowlatency    | 2         | 2.38%   |
| 5.11.0-34-lowlatency    | 2         | 2.38%   |
| 5.11.0-27-lowlatency    | 2         | 2.38%   |
| 6.2.8-x64v3-xanmod1     | 1         | 1.19%   |
| 6.2.0-1008-lowlatency   | 1         | 1.19%   |
| 5.8.0-59-lowlatency     | 1         | 1.19%   |
| 5.8.0-50-lowlatency     | 1         | 1.19%   |
| 5.8.0-44-lowlatency     | 1         | 1.19%   |
| 5.8.0-43-lowlatency     | 1         | 1.19%   |
| 5.8.0-34-generic        | 1         | 1.19%   |
| 5.8.0-29-lowlatency     | 1         | 1.19%   |
| 5.8.0-25-lowlatency     | 1         | 1.19%   |
| 5.7.6-050706-lowlatency | 1         | 1.19%   |
| 5.7.6-050706-generic    | 1         | 1.19%   |
| 5.4.0-96-lowlatency     | 1         | 1.19%   |
| 5.4.0-88-lowlatency     | 1         | 1.19%   |
| 5.4.0-52-generic        | 1         | 1.19%   |
| 5.4.0-45-generic        | 1         | 1.19%   |
| 5.4.0-34-lowlatency     | 1         | 1.19%   |
| 5.4.0-26-lowlatency     | 1         | 1.19%   |
| 5.4.0-132-lowlatency    | 1         | 1.19%   |
| 5.4.0-107-lowlatency    | 1         | 1.19%   |
| 5.4.0-100-lowlatency    | 1         | 1.19%   |
| 5.3.0-19-lowlatency     | 1         | 1.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 21        | 25.61%  |
| 5.4.0   | 20        | 24.39%  |
| 5.8.0   | 9         | 10.98%  |
| 5.11.0  | 9         | 10.98%  |
| 6.2.0   | 6         | 7.32%   |
| 5.19.0  | 6         | 7.32%   |
| 5.13.0  | 6         | 7.32%   |
| 4.15.0  | 2         | 2.44%   |
| 6.2.8   | 1         | 1.22%   |
| 5.7.6   | 1         | 1.22%   |
| 5.3.0   | 1         | 1.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 21        | 25.61%  |
| 5.4     | 20        | 24.39%  |
| 5.8     | 9         | 10.98%  |
| 5.11    | 9         | 10.98%  |
| 6.2     | 7         | 8.54%   |
| 5.19    | 6         | 7.32%   |
| 5.13    | 6         | 7.32%   |
| 4.15    | 2         | 2.44%   |
| 5.7     | 1         | 1.22%   |
| 5.3     | 1         | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 81        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| KDE5  | 38        | 46.91%  |
| XFCE  | 37        | 45.68%  |
| GNOME | 5         | 6.17%   |
| LXQt  | 1         | 1.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 77        | 95.06%  |
| Wayland | 4         | 4.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 33        | 40.74%  |
| TDM     | 21        | 25.93%  |
| LightDM | 21        | 25.93%  |
| GDM     | 5         | 6.17%   |
| LXDM    | 1         | 1.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 34        | 41.46%  |
| fr_FR   | 14        | 17.07%  |
| C       | 4         | 4.88%   |
| ru_RU   | 3         | 3.66%   |
| en_GB   | 3         | 3.66%   |
| de_DE   | 3         | 3.66%   |
| pt_BR   | 2         | 2.44%   |
| it_IT   | 2         | 2.44%   |
| es_ES   | 2         | 2.44%   |
| en_CA   | 2         | 2.44%   |
| Unknown | 2         | 2.44%   |
| nl_NL   | 1         | 1.22%   |
| hu_HU   | 1         | 1.22%   |
| es_NI   | 1         | 1.22%   |
| es_MX   | 1         | 1.22%   |
| es_CR   | 1         | 1.22%   |
| es_AR   | 1         | 1.22%   |
| en_NG   | 1         | 1.22%   |
| en_IE   | 1         | 1.22%   |
| en_AU   | 1         | 1.22%   |
| en_AG   | 1         | 1.22%   |
| de_CH   | 1         | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 55        | 67.9%   |
| BIOS | 26        | 32.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 77        | 95.06%  |
| Overlay | 4         | 4.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 58        | 71.6%   |
| MBR  | 23        | 28.4%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 87.8%   |
| Yes       | 10        | 12.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 50.62%  |
| Yes       | 40        | 49.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 21        | 25.93%  |
| Hewlett-Packard        | 13        | 16.05%  |
| Dell                   | 12        | 14.81%  |
| ASUSTek Computer       | 11        | 13.58%  |
| Toshiba                | 4         | 4.94%   |
| Acer                   | 4         | 4.94%   |
| HUAWEI                 | 2         | 2.47%   |
| Apple                  | 2         | 2.47%   |
| win element            | 1         | 1.23%   |
| Sony                   | 1         | 1.23%   |
| Samsung Electronics    | 1         | 1.23%   |
| Razer                  | 1         | 1.23%   |
| Intel Client Systems   | 1         | 1.23%   |
| GPU Company            | 1         | 1.23%   |
| Google                 | 1         | 1.23%   |
| Gigabyte Technology    | 1         | 1.23%   |
| Getac                  | 1         | 1.23%   |
| COM1                   | 1         | 1.23%   |
| Clevo                  | 1         | 1.23%   |
| Avell High Performance | 1         | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G50-45 80E3                       | 2         | 2.47%   |
| HP Pavilion dv6                          | 2         | 2.47%   |
| win element MoreFine S500+               | 1         | 1.23%   |
| Toshiba Satellite L755D                  | 1         | 1.23%   |
| Toshiba Satellite L505                   | 1         | 1.23%   |
| Toshiba Satellite C855                   | 1         | 1.23%   |
| Toshiba Satellite A505                   | 1         | 1.23%   |
| Sony VGN-NS31M_W                         | 1         | 1.23%   |
| Samsung 305V4A/305V5A                    | 1         | 1.23%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 1.23%   |
| Lenovo ThinkPad X250 20CL001LMB          | 1         | 1.23%   |
| Lenovo ThinkPad X230 2333A86             | 1         | 1.23%   |
| Lenovo ThinkPad X230 2325AJG             | 1         | 1.23%   |
| Lenovo ThinkPad X230 23245S1             | 1         | 1.23%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 1         | 1.23%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 1.23%   |
| Lenovo ThinkPad W530 2447IG0             | 1         | 1.23%   |
| Lenovo ThinkPad T530 24296HG             | 1         | 1.23%   |
| Lenovo ThinkPad T520 4243K86             | 1         | 1.23%   |
| Lenovo ThinkPad P50 20EQS0VV03           | 1         | 1.23%   |
| Lenovo ThinkPad L460 20FVS3JK00          | 1         | 1.23%   |
| Lenovo ThinkPad E14 Gen 3 20Y70073GE     | 1         | 1.23%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.23%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 1.23%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 1.23%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 1.23%   |
| Lenovo IdeaPad 3 15ABA7 82RN             | 1         | 1.23%   |
| Lenovo IdeaPad 3 14ARE05 81W3            | 1         | 1.23%   |
| Lenovo G70-80 80FF                       | 1         | 1.23%   |
| Intel Client Systems LAPBC510            | 1         | 1.23%   |
| HUAWEI KLVL-WXXW                         | 1         | 1.23%   |
| HUAWEI HLYL-WXX9                         | 1         | 1.23%   |
| HP ZBook 15 G3                           | 1         | 1.23%   |
| HP Stream Laptop 14-cb0XX                | 1         | 1.23%   |
| HP Sona                                  | 1         | 1.23%   |
| HP Pavilion dv8                          | 1         | 1.23%   |
| HP OMEN by Laptop 15-ce0xx               | 1         | 1.23%   |
| HP Notebook                              | 1         | 1.23%   |
| HP Laptop 15s-fq1xxx                     | 1         | 1.23%   |
| HP EliteBook 840 G3                      | 1         | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 12        | 14.81%  |
| Lenovo IdeaPad                | 5         | 6.17%   |
| Dell Latitude                 | 5         | 6.17%   |
| Dell Inspiron                 | 5         | 6.17%   |
| Toshiba Satellite             | 4         | 4.94%   |
| HP Pavilion                   | 3         | 3.7%    |
| HP EliteBook                  | 3         | 3.7%    |
| Lenovo G50-45                 | 2         | 2.47%   |
| ASUS VivoBook                 | 2         | 2.47%   |
| Acer Aspire                   | 2         | 2.47%   |
| win element MoreFine          | 1         | 1.23%   |
| Sony VGN-NS31M                | 1         | 1.23%   |
| Samsung 305V4A                | 1         | 1.23%   |
| Razer Blade                   | 1         | 1.23%   |
| Lenovo Legion                 | 1         | 1.23%   |
| Lenovo G70-80                 | 1         | 1.23%   |
| Intel Client Systems LAPBC510 | 1         | 1.23%   |
| HUAWEI KLVL-WXXW              | 1         | 1.23%   |
| HUAWEI HLYL-WXX9              | 1         | 1.23%   |
| HP ZBook                      | 1         | 1.23%   |
| HP Stream                     | 1         | 1.23%   |
| HP Sona                       | 1         | 1.23%   |
| HP OMEN                       | 1         | 1.23%   |
| HP Notebook                   | 1         | 1.23%   |
| HP Laptop                     | 1         | 1.23%   |
| HP Compaq                     | 1         | 1.23%   |
| GPU Company GWNR71517         | 1         | 1.23%   |
| Google Nami                   | 1         | 1.23%   |
| Gigabyte AERO                 | 1         | 1.23%   |
| Getac S400G3                  | 1         | 1.23%   |
| Dell XPS                      | 1         | 1.23%   |
| Dell Precision                | 1         | 1.23%   |
| COM1 NBINF-X5-9G5             | 1         | 1.23%   |
| Clevo W35                     | 1         | 1.23%   |
| Avell High Performance Avell  | 1         | 1.23%   |
| ASUS X541NA                   | 1         | 1.23%   |
| ASUS UX305FA                  | 1         | 1.23%   |
| ASUS U56E                     | 1         | 1.23%   |
| ASUS TP300UA                  | 1         | 1.23%   |
| ASUS ROG                      | 1         | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 10        | 12.35%  |
| 2012 | 9         | 11.11%  |
| 2021 | 7         | 8.64%   |
| 2019 | 7         | 8.64%   |
| 2016 | 7         | 8.64%   |
| 2014 | 7         | 8.64%   |
| 2011 | 6         | 7.41%   |
| 2015 | 5         | 6.17%   |
| 2018 | 4         | 4.94%   |
| 2017 | 4         | 4.94%   |
| 2009 | 4         | 4.94%   |
| 2008 | 4         | 4.94%   |
| 2010 | 3         | 3.7%    |
| 2022 | 2         | 2.47%   |
| 2007 | 2         | 2.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 81        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 72        | 88.89%  |
| Enabled  | 9         | 11.11%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 79        | 97.53%  |
| Yes  | 2         | 2.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 35        | 42.68%  |
| 8.01-16.0  | 15        | 18.29%  |
| 16.01-24.0 | 12        | 14.63%  |
| 3.01-4.0   | 9         | 10.98%  |
| 32.01-64.0 | 6         | 7.32%   |
| 24.01-32.0 | 2         | 2.44%   |
| 2.01-3.0   | 2         | 2.44%   |
| 1.01-2.0   | 1         | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 29        | 34.52%  |
| 2.01-3.0  | 21        | 25%     |
| 3.01-4.0  | 16        | 19.05%  |
| 4.01-8.0  | 15        | 17.86%  |
| 8.01-16.0 | 2         | 2.38%   |
| 0.51-1.0  | 1         | 1.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 56        | 68.29%  |
| 2      | 23        | 28.05%  |
| 0      | 2         | 2.44%   |
| 4      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 65.85%  |
| Yes       | 28        | 34.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 82.72%  |
| No        | 14        | 17.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 98.77%  |
| No        | 1         | 1.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 76.54%  |
| No        | 19        | 23.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 18        | 22.22%  |
| France       | 12        | 14.81%  |
| Germany      | 7         | 8.64%   |
| Russia       | 5         | 6.17%   |
| Canada       | 4         | 4.94%   |
| UK           | 3         | 3.7%    |
| Spain        | 3         | 3.7%    |
| Italy        | 3         | 3.7%    |
| Netherlands  | 2         | 2.47%   |
| Ivory Coast  | 2         | 2.47%   |
| Costa Rica   | 2         | 2.47%   |
| Brazil       | 2         | 2.47%   |
| Yemen        | 1         | 1.23%   |
| Turkey       | 1         | 1.23%   |
| Taiwan       | 1         | 1.23%   |
| Switzerland  | 1         | 1.23%   |
| South Africa | 1         | 1.23%   |
| Poland       | 1         | 1.23%   |
| Peru         | 1         | 1.23%   |
| Norway       | 1         | 1.23%   |
| Nigeria      | 1         | 1.23%   |
| Nicaragua    | 1         | 1.23%   |
| Mexico       | 1         | 1.23%   |
| Indonesia    | 1         | 1.23%   |
| Hungary      | 1         | 1.23%   |
| Finland      | 1         | 1.23%   |
| Bulgaria     | 1         | 1.23%   |
| Austria      | 1         | 1.23%   |
| Australia    | 1         | 1.23%   |
| Argentina    | 1         | 1.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Montreal           | 2         | 2.44%   |
| Madrid             | 2         | 2.44%   |
| Hamburg            | 2         | 2.44%   |
| Groningen          | 2         | 2.44%   |
| Denver             | 2         | 2.44%   |
| Béziers           | 2         | 2.44%   |
| Abidjan            | 2         | 2.44%   |
| Yonkers            | 1         | 1.22%   |
| Yekaterinburg      | 1         | 1.22%   |
| Wroclaw            | 1         | 1.22%   |
| Woonsocket         | 1         | 1.22%   |
| Woodland Park      | 1         | 1.22%   |
| Warner Robins      | 1         | 1.22%   |
| Vienna             | 1         | 1.22%   |
| Velleron           | 1         | 1.22%   |
| Turin              | 1         | 1.22%   |
| Toulouse           | 1         | 1.22%   |
| Tarragona          | 1         | 1.22%   |
| Taipei             | 1         | 1.22%   |
| Sunderland         | 1         | 1.22%   |
| Stuttgart          | 1         | 1.22%   |
| Stabekk            | 1         | 1.22%   |
| St Petersburg      | 1         | 1.22%   |
| Sofia              | 1         | 1.22%   |
| Sleman             | 1         | 1.22%   |
| Seropedica         | 1         | 1.22%   |
| Sanaa              | 1         | 1.22%   |
| San Juan           | 1         | 1.22%   |
| San Francisco      | 1         | 1.22%   |
| Samara             | 1         | 1.22%   |
| Rio de Janeiro     | 1         | 1.22%   |
| Ragusa             | 1         | 1.22%   |
| Portland           | 1         | 1.22%   |
| Port Harcourt      | 1         | 1.22%   |
| Phoenix            | 1         | 1.22%   |
| Paso de los Libres | 1         | 1.22%   |
| Nudlingen          | 1         | 1.22%   |
| North Las Vegas    | 1         | 1.22%   |
| Moscow             | 1         | 1.22%   |
| Mississauga        | 1         | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 15        | 16     | 15%     |
| Samsung Electronics         | 14        | 14     | 14%     |
| Toshiba                     | 7         | 7      | 7%      |
| SanDisk                     | 7         | 7      | 7%      |
| SK hynix                    | 5         | 6      | 5%      |
| Seagate                     | 5         | 5      | 5%      |
| Intel                       | 5         | 7      | 5%      |
| Unknown                     | 4         | 4      | 4%      |
| Micron Technology           | 3         | 3      | 3%      |
| Kingston                    | 3         | 3      | 3%      |
| Hitachi                     | 3         | 3      | 3%      |
| PNY                         | 2         | 2      | 2%      |
| Phison                      | 2         | 2      | 2%      |
| KIOXIA                      | 2         | 2      | 2%      |
| Crucial                     | 2         | 2      | 2%      |
| China                       | 2         | 2      | 2%      |
| XPG                         | 1         | 1      | 1%      |
| Wibtek                      | 1         | 1      | 1%      |
| Union Memory                | 1         | 1      | 1%      |
| UMIS                        | 1         | 1      | 1%      |
| Team                        | 1         | 1      | 1%      |
| SPCC                        | 1         | 1      | 1%      |
| Reeinno                     | 1         | 1      | 1%      |
| Realtek                     | 1         | 1      | 1%      |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1%      |
| KingSpec                    | 1         | 1      | 1%      |
| JMicron Technology          | 1         | 1      | 1%      |
| Inateck                     | 1         | 1      | 1%      |
| HGST                        | 1         | 1      | 1%      |
| Fujitsu                     | 1         | 1      | 1%      |
| Dogfish                     | 1         | 1      | 1%      |
| BHT                         | 1         | 1      | 1%      |
| ASMT                        | 1         | 1      | 1%      |
| A-DATA Technology           | 1         | 2      | 1%      |
| Unknown                     | 1         | 1      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 1.96%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.96%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 1.96%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 1.96%   |
| Samsung SSD 870 EVO 1TB                   | 2         | 1.96%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 1.96%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 1.96%   |
| China SSD 1TB                             | 2         | 1.96%   |
| XPG GAMMIX S7 1TB                         | 1         | 0.98%   |
| Wibtek W800S 512GB SSD                    | 1         | 0.98%   |
| WDC WDS100T2G0A-00JH30 1TB SSD            | 1         | 0.98%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 0.98%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.98%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.98%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 0.98%   |
| WDC WD5000BEKT-60KA9T0 500GB              | 1         | 0.98%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 0.98%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 0.98%   |
| WDC WD3200BEKT-60V5T1 320GB               | 1         | 0.98%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 0.98%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 0.98%   |
| WDC WD10JPVT-75A1YT0 1TB                  | 1         | 0.98%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB      | 1         | 0.98%   |
| Unknown MMC Card  4GB                     | 1         | 0.98%   |
| Unknown MMC Card  16GB                    | 1         | 0.98%   |
| Unknown DA4128  128GB                     | 1         | 0.98%   |
| Unknown 032G34  32GB                      | 1         | 0.98%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB   | 1         | 0.98%   |
| UMIS RPJTJ256MEE1OWX 256GB                | 1         | 0.98%   |
| Toshiba TR150 240GB SSD                   | 1         | 0.98%   |
| Toshiba MK1637GSX 160GB                   | 1         | 0.98%   |
| Toshiba HDWL110 1TB                       | 1         | 0.98%   |
| Team TM8FP4001T 1TB                       | 1         | 0.98%   |
| SPCC Solid State Disk 1TB                 | 1         | 0.98%   |
| SK hynix SKHynix_HFS256GD9TNI-L2A0B 256GB | 1         | 0.98%   |
| SK hynix SC401 SATA 256GB SSD             | 1         | 0.98%   |
| SK hynix BC501 NVMe 256GB                 | 1         | 0.98%   |
| Seagate ST9500420AS 500GB                 | 1         | 0.98%   |
| Seagate ST9320320AS 320GB                 | 1         | 0.98%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 32.14%  |
| Toshiba             | 6         | 6      | 21.43%  |
| Seagate             | 4         | 4      | 14.29%  |
| Hitachi             | 3         | 3      | 10.71%  |
| Samsung Electronics | 2         | 2      | 7.14%   |
| Inateck             | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |
| ASMT                | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 22.86%  |
| SanDisk             | 5         | 5      | 14.29%  |
| WDC                 | 2         | 2      | 5.71%   |
| PNY                 | 2         | 2      | 5.71%   |
| Micron Technology   | 2         | 2      | 5.71%   |
| Kingston            | 2         | 2      | 5.71%   |
| Crucial             | 2         | 2      | 5.71%   |
| China               | 2         | 2      | 5.71%   |
| Wibtek              | 1         | 1      | 2.86%   |
| Toshiba             | 1         | 1      | 2.86%   |
| SPCC                | 1         | 1      | 2.86%   |
| SK hynix            | 1         | 1      | 2.86%   |
| Reeinno             | 1         | 1      | 2.86%   |
| KingSpec            | 1         | 1      | 2.86%   |
| JMicron Technology  | 1         | 1      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |
| Dogfish             | 1         | 1      | 2.86%   |
| BHT                 | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 30        | 35     | 33.33%  |
| HDD  | 28        | 29     | 31.11%  |
| NVMe | 26        | 34     | 28.89%  |
| MMC  | 6         | 7      | 6.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 52        | 60     | 58.43%  |
| NVMe | 26        | 33     | 29.21%  |
| MMC  | 6         | 7      | 6.74%   |
| SAS  | 5         | 5      | 5.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 44     | 67.8%   |
| 0.51-1.0   | 17        | 18     | 28.81%  |
| 3.01-4.0   | 1         | 1      | 1.69%   |
| 1.01-2.0   | 1         | 1      | 1.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 24        | 28.92%  |
| 251-500    | 20        | 24.1%   |
| 501-1000   | 13        | 15.66%  |
| 21-50      | 7         | 8.43%   |
| 1001-2000  | 7         | 8.43%   |
| 51-100     | 7         | 8.43%   |
| 1-20       | 4         | 4.82%   |
| 2001-3000  | 1         | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 31        | 37.35%  |
| 21-50     | 16        | 19.28%  |
| 101-250   | 13        | 15.66%  |
| 251-500   | 7         | 8.43%   |
| 501-1000  | 7         | 8.43%   |
| 51-100    | 7         | 8.43%   |
| 1001-2000 | 2         | 2.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 5.56%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 5.56%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 5.56%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 5.56%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 5.56%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 5.56%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 5.56%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 5.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 5.56%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 5.56%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 5.56%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 5.56%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 5.56%   |
| KingSpec P3-256 256GB SSD                           | 1         | 1      | 5.56%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 5.56%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 5.56%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 27.78%  |
| Seagate             | 4         | 4      | 22.22%  |
| Samsung Electronics | 3         | 3      | 16.67%  |
| Hitachi             | 2         | 2      | 11.11%  |
| Toshiba             | 1         | 1      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| KingSpec            | 1         | 1      | 5.56%   |
| Intel               | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 35.71%  |
| Seagate             | 4         | 4      | 28.57%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| Hitachi             | 2         | 2      | 14.29%  |
| Toshiba             | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 77.78%  |
| SSD  | 4         | 4      | 22.22%  |

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
| Works    | 60        | 77     | 68.97%  |
| Malfunc  | 18        | 18     | 20.69%  |
| Detected | 9         | 10     | 10.34%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 57        | 58.76%  |
| AMD                          | 15        | 15.46%  |
| SK hynix                     | 4         | 4.12%   |
| SanDisk                      | 4         | 4.12%   |
| Samsung Electronics          | 4         | 4.12%   |
| Phison Electronics           | 3         | 3.09%   |
| Union Memory (Shenzhen)      | 2         | 2.06%   |
| Toshiba America Info Systems | 1         | 1.03%   |
| Seagate Technology           | 1         | 1.03%   |
| Realtek Semiconductor        | 1         | 1.03%   |
| Micron Technology            | 1         | 1.03%   |
| MAXIO Technology (Hangzhou)  | 1         | 1.03%   |
| KIOXIA                       | 1         | 1.03%   |
| Kingston Technology Company  | 1         | 1.03%   |
| ADATA Technology             | 1         | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 13        | 12.5%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 8         | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 6.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 6         | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 4.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 4         | 3.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 3         | 2.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3         | 2.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 3         | 2.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 2.88%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                         | 2         | 1.92%   |
| SK hynix BC511 NVMe SSD                                                       | 2         | 1.92%   |
| Phison E12 NVMe Controller                                                    | 2         | 1.92%   |
| Intel SSD 670p Series [Keystone Harbor]                                       | 2         | 1.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 1.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 2         | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 2         | 1.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2         | 1.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 1         | 0.96%   |
| SK hynix PC611 NVMe Solid State Drive                                         | 1         | 0.96%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 1         | 0.96%   |
| Seagate FireCuda 530 SSD                                                      | 1         | 0.96%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                         | 1         | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 0.96%   |
| Realtek RTS5763DL NVMe SSD Controller                                         | 1         | 0.96%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 0.96%   |
| Micron 2200S NVMe SSD [Cassandra]                                             | 1         | 0.96%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                  | 1         | 0.96%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 1         | 0.96%   |
| Kingston Company A2000 NVMe SSD                                               | 1         | 0.96%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 0.96%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                              | 1         | 0.96%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]            | 1         | 0.96%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                   | 1         | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 59        | 60.2%   |
| NVMe | 26        | 26.53%  |
| RAID | 9         | 9.18%   |
| IDE  | 4         | 4.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 76.54%  |
| AMD    | 19        | 23.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-2450M CPU @ 2.50GHz      | 3         | 3.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics | 3         | 3.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 2.47%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 2         | 2.47%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 2         | 2.47%   |
| Intel Core i7-5600U CPU @ 2.60GHz      | 2         | 2.47%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 2         | 2.47%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz      | 2         | 2.47%   |
| Intel Core i5-10300H CPU @ 2.50GHz     | 2         | 2.47%   |
| AMD Ryzen 7 5825U with Radeon Graphics | 2         | 2.47%   |
| AMD Ryzen 5 5500U with Radeon Graphics | 2         | 2.47%   |
| Intel Processor 5Y10 CPU @ 0.80GHz     | 1         | 1.23%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.23%   |
| Intel Genuine CPU U2300 @ 1.20GHz      | 1         | 1.23%   |
| Intel Core i9-8950HK CPU @ 2.90GHz     | 1         | 1.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz      | 1         | 1.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 1.23%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 1         | 1.23%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 1.23%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.23%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz     | 1         | 1.23%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1         | 1.23%   |
| Intel Core i7-3940XM CPU @ 3.00GHz     | 1         | 1.23%   |
| Intel Core i7-3630QM CPU @ 2.40GHz     | 1         | 1.23%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 1         | 1.23%   |
| Intel Core i7-2635QM CPU @ 2.00GHz     | 1         | 1.23%   |
| Intel Core i7-2630QM CPU @ 2.00GHz     | 1         | 1.23%   |
| Intel Core i7-10850H CPU @ 2.70GHz     | 1         | 1.23%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz      | 1         | 1.23%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 1         | 1.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 1         | 1.23%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.23%   |
| Intel Core i5-4310M CPU @ 2.70GHz      | 1         | 1.23%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.23%   |
| Intel Core i5-3340M CPU @ 2.70GHz      | 1         | 1.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 1         | 1.23%   |
| Intel Core i5-3230M CPU @ 2.60GHz      | 1         | 1.23%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 1         | 1.23%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz     | 1         | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 26        | 32.1%   |
| Intel Core i5      | 17        | 20.99%  |
| Intel Core 2 Duo   | 5         | 6.17%   |
| AMD Ryzen 7        | 5         | 6.17%   |
| AMD Ryzen 5        | 5         | 6.17%   |
| Other              | 4         | 4.94%   |
| Intel Core i3      | 4         | 4.94%   |
| Intel Celeron      | 4         | 4.94%   |
| AMD E              | 2         | 2.47%   |
| Intel Pentium Dual | 1         | 1.23%   |
| Intel Genuine      | 1         | 1.23%   |
| Intel Core i9      | 1         | 1.23%   |
| AMD Ryzen 3 PRO    | 1         | 1.23%   |
| AMD Ryzen 3        | 1         | 1.23%   |
| AMD E2             | 1         | 1.23%   |
| AMD E1             | 1         | 1.23%   |
| AMD A6             | 1         | 1.23%   |
| AMD A4             | 1         | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 39        | 48.15%  |
| 4      | 28        | 34.57%  |
| 6      | 10        | 12.35%  |
| 8      | 4         | 4.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 81        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 59        | 72.84%  |
| 1      | 22        | 27.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 81        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 12.2%   |
| 0x206a7    | 7         | 8.54%   |
| 0x306a9    | 6         | 7.32%   |
| 0x306d4    | 5         | 6.1%    |
| 0x906ea    | 4         | 4.88%   |
| 0x08600104 | 4         | 4.88%   |
| 0xa0652    | 3         | 3.66%   |
| 0x806ea    | 3         | 3.66%   |
| 0x706e5    | 3         | 3.66%   |
| 0x406e3    | 3         | 3.66%   |
| 0x906e9    | 2         | 2.44%   |
| 0x806c1    | 2         | 2.44%   |
| 0x6fd      | 2         | 2.44%   |
| 0x40651    | 2         | 2.44%   |
| 0x106e5    | 2         | 2.44%   |
| 0x0a50000c | 2         | 2.44%   |
| 0x08108109 | 2         | 2.44%   |
| 0x07030105 | 2         | 2.44%   |
| 0x706a1    | 1         | 1.22%   |
| 0x6fb      | 1         | 1.22%   |
| 0x506e3    | 1         | 1.22%   |
| 0x506c9    | 1         | 1.22%   |
| 0x406c4    | 1         | 1.22%   |
| 0x40661    | 1         | 1.22%   |
| 0x306c3    | 1         | 1.22%   |
| 0x1067a    | 1         | 1.22%   |
| 0x10676    | 1         | 1.22%   |
| 0x08608103 | 1         | 1.22%   |
| 0x08608102 | 1         | 1.22%   |
| 0x08600106 | 1         | 1.22%   |
| 0x08600103 | 1         | 1.22%   |
| 0x07030104 | 1         | 1.22%   |
| 0x06006110 | 1         | 1.22%   |
| 0x0500010d | 1         | 1.22%   |
| 0x05000029 | 1         | 1.22%   |
| 0x03000027 | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 12.35%  |
| SandyBridge   | 7         | 8.64%   |
| Zen 2         | 6         | 7.41%   |
| Skylake       | 6         | 7.41%   |
| IvyBridge     | 6         | 7.41%   |
| Broadwell     | 6         | 7.41%   |
| Penryn        | 4         | 4.94%   |
| Haswell       | 4         | 4.94%   |
| Puma          | 3         | 3.7%    |
| Nehalem       | 3         | 3.7%    |
| IceLake       | 3         | 3.7%    |
| Core          | 3         | 3.7%    |
| CometLake     | 3         | 3.7%    |
| Zen+          | 2         | 2.47%   |
| Zen 3         | 2         | 2.47%   |
| Westmere      | 2         | 2.47%   |
| TigerLake     | 2         | 2.47%   |
| Bobcat        | 2         | 2.47%   |
| Unknown       | 2         | 2.47%   |
| Silvermont    | 1         | 1.23%   |
| K10 Llano     | 1         | 1.23%   |
| Goldmont plus | 1         | 1.23%   |
| Goldmont      | 1         | 1.23%   |
| Excavator     | 1         | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 52.94%  |
| AMD    | 25        | 24.51%  |
| Nvidia | 23        | 22.55%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 7         | 6.73%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 5.77%   |
| AMD Renoir                                                                | 6         | 5.77%   |
| Intel HD Graphics 5500                                                    | 5         | 4.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 5         | 4.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 3.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 3.85%   |
| Nvidia TU117M                                                             | 3         | 2.88%   |
| Intel UHD Graphics 620                                                    | 3         | 2.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 2.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.92%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.92%   |
| Nvidia GK208BM [GeForce 920M]                                             | 2         | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.92%   |
| Intel Iris Plus Graphics G7                                               | 2         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.92%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.92%   |
| AMD Wrestler [Radeon HD 6310]                                             | 2         | 1.92%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.92%   |
| AMD Lucienne                                                              | 2         | 1.92%   |
| AMD Barcelo                                                               | 2         | 1.92%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.96%   |
| Nvidia GT216M [GeForce GT 230M]                                           | 1         | 0.96%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 1         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.96%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 0.96%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 0.96%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.96%   |
| Nvidia GK107M [GeForce GTX 660M]                                          | 1         | 0.96%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 0.96%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 0.96%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 0.96%   |
| Nvidia GF108M [GeForce GT 525M]                                           | 1         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 0.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 0.96%   |
| Intel HD Graphics 630                                                     | 1         | 0.96%   |
| Intel HD Graphics 5300                                                    | 1         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 44.44%  |
| 1 x AMD        | 19        | 23.46%  |
| Intel + Nvidia | 16        | 19.75%  |
| 1 x Nvidia     | 4         | 4.94%   |
| AMD + Nvidia   | 3         | 3.7%    |
| Intel + AMD    | 2         | 2.47%   |
| 2 x AMD        | 1         | 1.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 76        | 93.83%  |
| Proprietary | 5         | 6.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 54.32%  |
| 0.01-0.5   | 12        | 14.81%  |
| 0.51-1.0   | 10        | 12.35%  |
| 1.01-2.0   | 8         | 9.88%   |
| 3.01-4.0   | 5         | 6.17%   |
| 5.01-6.0   | 2         | 2.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 19        | 20%     |
| AU Optronics            | 15        | 15.79%  |
| BOE                     | 12        | 12.63%  |
| Samsung Electronics     | 11        | 11.58%  |
| Chimei Innolux          | 11        | 11.58%  |
| Lenovo                  | 3         | 3.16%   |
| Hewlett-Packard         | 3         | 3.16%   |
| Sharp                   | 2         | 2.11%   |
| Dell                    | 2         | 2.11%   |
| Chi Mei Optoelectronics | 2         | 2.11%   |
| Apple                   | 2         | 2.11%   |
| Ancor Communications    | 2         | 2.11%   |
| Philips                 | 1         | 1.05%   |
| LG Philips              | 1         | 1.05%   |
| Iiyama                  | 1         | 1.05%   |
| HannStar                | 1         | 1.05%   |
| Hannspree               | 1         | 1.05%   |
| Goldstar                | 1         | 1.05%   |
| CPT                     | 1         | 1.05%   |
| BenQ                    | 1         | 1.05%   |
| ASUSTek Computer        | 1         | 1.05%   |
| Arnos Instruments       | 1         | 1.05%   |
| Acer                    | 1         | 1.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 2.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 2.08%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 2.08%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 2.08%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 2.08%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 1.04%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 1.04%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch | 1         | 1.04%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 1.04%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 1.04%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch              | 1         | 1.04%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 1.04%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch               | 1         | 1.04%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 1         | 1.04%   |
| Hewlett-Packard E242 HWP326F 1920x1200 518x324mm 24.1-inch            | 1         | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 42        | 49.41%  |
| 1366x768 (WXGA)    | 24        | 28.24%  |
| 1600x900 (HD+)     | 5         | 5.88%   |
| 3840x2160 (4K)     | 4         | 4.71%   |
| 1680x1050 (WSXGA+) | 2         | 2.35%   |
| 1280x800 (WXGA)    | 2         | 2.35%   |
| 3440x1440          | 1         | 1.18%   |
| 2880x1800          | 1         | 1.18%   |
| 2560x1440 (QHD)    | 1         | 1.18%   |
| 2160x1440          | 1         | 1.18%   |
| 1920x1200 (WUXGA)  | 1         | 1.18%   |
| 1440x900 (WXGA+)   | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 47        | 49.47%  |
| 13     | 11        | 11.58%  |
| 14     | 8         | 8.42%   |
| 24     | 6         | 6.32%   |
| 12     | 5         | 5.26%   |
| 27     | 3         | 3.16%   |
| 17     | 3         | 3.16%   |
| 23     | 2         | 2.11%   |
| 21     | 2         | 2.11%   |
| 19     | 2         | 2.11%   |
| 18     | 2         | 2.11%   |
| 84     | 1         | 1.05%   |
| 34     | 1         | 1.05%   |
| 20     | 1         | 1.05%   |
| 16     | 1         | 1.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 59        | 63.44%  |
| 201-300     | 11        | 11.83%  |
| 501-600     | 9         | 9.68%   |
| 401-500     | 7         | 7.53%   |
| 351-400     | 5         | 5.38%   |
| 701-800     | 1         | 1.08%   |
| 1501-2000   | 1         | 1.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 71        | 85.54%  |
| 16/10 | 10        | 12.05%  |
| 3/2   | 1         | 1.2%    |
| 21/9  | 1         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 48        | 51.06%  |
| 81-90          | 14        | 14.89%  |
| 71-80          | 5         | 5.32%   |
| 61-70          | 5         | 5.32%   |
| 201-250        | 5         | 5.32%   |
| 151-200        | 4         | 4.26%   |
| 301-350        | 3         | 3.19%   |
| 251-300        | 3         | 3.19%   |
| 141-150        | 2         | 2.13%   |
| 121-130        | 2         | 2.13%   |
| More than 1000 | 1         | 1.06%   |
| 351-500        | 1         | 1.06%   |
| 131-140        | 1         | 1.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 42        | 45.65%  |
| 101-120       | 25        | 27.17%  |
| 51-100        | 15        | 16.3%   |
| 161-240       | 9         | 9.78%   |
| More than 240 | 1         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 67        | 80.72%  |
| 2     | 14        | 16.87%  |
| 3     | 2         | 2.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 50        | 39.37%  |
| Realtek Semiconductor             | 44        | 34.65%  |
| Qualcomm Atheros                  | 14        | 11.02%  |
| Broadcom                          | 6         | 4.72%   |
| ASIX Electronics                  | 3         | 2.36%   |
| Ralink                            | 2         | 1.57%   |
| MediaTek                          | 2         | 1.57%   |
| Ericsson Business Mobile Networks | 2         | 1.57%   |
| Motorola PCS                      | 1         | 0.79%   |
| Marvell Technology Group          | 1         | 0.79%   |
| Huawei Technologies               | 1         | 0.79%   |
| Broadcom Limited                  | 1         | 0.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 23        | 14.56%  |
| Intel Wireless 7265                                                | 8         | 5.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 7         | 4.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 7         | 4.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 5         | 3.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 5         | 3.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 4         | 2.53%   |
| Intel Wireless 8260                                                | 4         | 2.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 4         | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 3         | 1.9%    |
| Intel Wireless 8265 / 8275                                         | 3         | 1.9%    |
| Intel Wireless 7260                                                | 3         | 1.9%    |
| Intel WiFi Link 5100                                               | 3         | 1.9%    |
| Intel Wi-Fi 6 AX200                                                | 3         | 1.9%    |
| Intel Centrino Ultimate-N 6300                                     | 3         | 1.9%    |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 1.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 2         | 1.27%   |
| Realtek 802.11ac NIC                                               | 2         | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                           | 2         | 1.27%   |
| Intel Wi-Fi 6 AX201                                                | 2         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                              | 2         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                              | 2         | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 2         | 1.27%   |
| Intel 82567LM Gigabit Network Connection                           | 2         | 1.27%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                      | 2         | 1.27%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller        | 1         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 1         | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                        | 1         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 1         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                  | 1         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                   | 1         | 0.63%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]   | 1         | 0.63%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller          | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 59.26%  |
| Realtek Semiconductor | 15        | 18.52%  |
| Qualcomm Atheros      | 10        | 12.35%  |
| Broadcom              | 4         | 4.94%   |
| Ralink                | 2         | 2.47%   |
| MediaTek              | 1         | 1.23%   |
| Broadcom Limited      | 1         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 8         | 9.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 5         | 6.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 5         | 6.1%    |
| Intel Wireless 8260                                              | 4         | 4.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 4         | 4.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 3         | 3.66%   |
| Intel Wireless 8265 / 8275                                       | 3         | 3.66%   |
| Intel Wireless 7260                                              | 3         | 3.66%   |
| Intel WiFi Link 5100                                             | 3         | 3.66%   |
| Intel Wi-Fi 6 AX200                                              | 3         | 3.66%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 3.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 2.44%   |
| Realtek 802.11ac NIC                                             | 2         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 2         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 2.44%   |
| Intel Wi-Fi 6 AX201                                              | 2         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 2         | 2.44%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 2.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller      | 1         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 1         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.22%   |
| Realtek RTL8191SEvB Wireless LAN Controller                      | 1         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1.22%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1.22%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1         | 1.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 1         | 1.22%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                          | 1         | 1.22%   |
| Intel Wireless-AC 9260                                           | 1         | 1.22%   |
| Intel Wireless 3160                                              | 1         | 1.22%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 1.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 1         | 1.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 1.22%   |
| Intel Centrino Wireless-N 6150                                   | 1         | 1.22%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 1         | 1.22%   |
| Intel Centrino Wireless-N + WiMAX 6150                           | 1         | 1.22%   |
| Intel Centrino Advanced-N 6200                                   | 1         | 1.22%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 48.57%  |
| Intel                    | 22        | 31.43%  |
| Qualcomm Atheros         | 6         | 8.57%   |
| Broadcom                 | 3         | 4.29%   |
| ASIX Electronics         | 3         | 4.29%   |
| MediaTek                 | 1         | 1.43%   |
| Marvell Technology Group | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 31.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 9.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 9.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 5.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 4.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.78%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 2.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.39%   |
| MediaTek moto g22                                                 | 1         | 1.39%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.39%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.39%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.39%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.39%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.39%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.39%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.39%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 1.39%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 52.98%  |
| Ethernet | 67        | 44.37%  |
| Modem    | 3         | 1.99%   |
| Unknown  | 1         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 71        | 82.56%  |
| Ethernet | 15        | 17.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 61        | 75.31%  |
| 1     | 18        | 22.22%  |
| 3     | 1         | 1.23%   |
| 0     | 1         | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 72.84%  |
| Yes  | 22        | 27.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 51.61%  |
| Realtek Semiconductor           | 6         | 9.68%   |
| Broadcom                        | 5         | 8.06%   |
| Qualcomm Atheros Communications | 4         | 6.45%   |
| Realtek                         | 2         | 3.23%   |
| Ralink Technology               | 2         | 3.23%   |
| Lite-On Technology              | 2         | 3.23%   |
| Hewlett-Packard                 | 2         | 3.23%   |
| Apple                           | 2         | 3.23%   |
| MediaTek                        | 1         | 1.61%   |
| IMC Networks                    | 1         | 1.61%   |
| Foxconn International           | 1         | 1.61%   |
| Dell                            | 1         | 1.61%   |
| ASUSTek Computer                | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 18        | 29.03%  |
| Realtek Bluetooth Radio                           | 5         | 8.06%   |
| Intel AX201 Bluetooth                             | 5         | 8.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 4         | 6.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 4         | 6.45%   |
| Intel AX200 Bluetooth                             | 3         | 4.84%   |
| Realtek 802.11ac WLAN Adapter                     | 2         | 3.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 3.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 3.23%   |
| Apple Bluetooth Host Controller                   | 2         | 3.23%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 1.61%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 1.61%   |
| Ralink CSR BS8510                                 | 1         | 1.61%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 1.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 1.61%   |
| MediaTek Wireless_Device                          | 1         | 1.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 1.61%   |
| IMC Networks Bluetooth Radio                      | 1         | 1.61%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 1.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 1.61%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.61%   |
| Dell Wireless 370 Bluetooth Mini-card             | 1         | 1.61%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 1.61%   |
| ASUS BT-270 Bluetooth Adapter                     | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 62        | 53.91%  |
| AMD                        | 23        | 20%     |
| Nvidia                     | 19        | 16.52%  |
| Yealink Network Technology | 1         | 0.87%   |
| Yamaha                     | 1         | 0.87%   |
| QinHeng Electronics        | 1         | 0.87%   |
| Mackie Designs             | 1         | 0.87%   |
| Logitech                   | 1         | 0.87%   |
| Jieli Technology           | 1         | 0.87%   |
| Focusrite-Novation         | 1         | 0.87%   |
| Dell                       | 1         | 0.87%   |
| C-Media Electronics        | 1         | 0.87%   |
| Behringer.......           | 1         | 0.87%   |
| ASUSTek Computer           | 1         | 0.87%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 7.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 5.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 5.71%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 5%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 4.29%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 4.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 3.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 3.57%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 2.86%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 2.14%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 2.14%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.43%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 1.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.43%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.43%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.43%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.43%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.43%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.43%   |
| Yealink Network Technology VoIP Phone                                      | 1         | 0.71%   |
| Yamaha Steinberg UR242                                                     | 1         | 0.71%   |
| QinHeng Electronics CH345 MIDI adapter                                     | 1         | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.71%   |
| Mackie Designs BIG KNOB STUDIO+                                            | 1         | 0.71%   |
| Logitech 960 Headset                                                       | 1         | 0.71%   |
| Jieli Technology UACDemoV1.0                                               | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 30.53%  |
| SK hynix            | 25        | 26.32%  |
| Micron Technology   | 12        | 12.63%  |
| Kingston            | 10        | 10.53%  |
| Unknown             | 3         | 3.16%   |
| Ramaxel Technology  | 3         | 3.16%   |
| Crucial             | 3         | 3.16%   |
| Timetec             | 2         | 2.11%   |
| Nanya Technology    | 2         | 2.11%   |
| Transcend           | 1         | 1.05%   |
| Patriot             | 1         | 1.05%   |
| G.Skill             | 1         | 1.05%   |
| Corsair             | 1         | 1.05%   |
| A-DATA Technology   | 1         | 1.05%   |
| Unknown             | 1         | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 3         | 2.91%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 2.91%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 2.91%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s         | 3         | 2.91%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 2         | 1.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.94%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 1.94%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 1.94%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.94%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 1.94%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 1.94%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s             | 1         | 0.97%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 0.97%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.97%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 0.97%   |
| Timetec RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.97%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 0.97%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s              | 1         | 0.97%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s         | 1         | 0.97%   |
| SK hynix RAM HMT451S6DFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s    | 1         | 0.97%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 1         | 0.97%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 0.97%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 0.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 0.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 0.97%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s       | 1         | 0.97%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB DDR4 2400MT/s              | 1         | 0.97%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.97%   |
| Samsung RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.97%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 0.97%   |
| Samsung RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 0.97%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 40        | 48.19%  |
| DDR4   | 31        | 37.35%  |
| DDR2   | 5         | 6.02%   |
| SDRAM  | 3         | 3.61%   |
| LPDDR4 | 2         | 2.41%   |
| LPDDR3 | 2         | 2.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 87.95%  |
| Row Of Chips | 8         | 9.64%   |
| Chip         | 1         | 1.2%    |
| Unknown      | 1         | 1.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 35        | 36.84%  |
| 8192  | 34        | 35.79%  |
| 2048  | 12        | 12.63%  |
| 16384 | 9         | 9.47%   |
| 1024  | 3         | 3.16%   |
| 32768 | 2         | 2.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 35.23%  |
| 3200    | 13        | 14.77%  |
| 2667    | 11        | 12.5%   |
| 1334    | 8         | 9.09%   |
| 2400    | 6         | 6.82%   |
| 2133    | 4         | 4.55%   |
| 1333    | 4         | 4.55%   |
| 667     | 3         | 3.41%   |
| 4267    | 2         | 2.27%   |
| 4199    | 2         | 2.27%   |
| 1639    | 1         | 1.14%   |
| 1067    | 1         | 1.14%   |
| 800     | 1         | 1.14%   |
| Unknown | 1         | 1.14%   |

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
| Chicony Electronics                    | 21        | 28.77%  |
| IMC Networks                           | 8         | 10.96%  |
| Suyin                                  | 6         | 8.22%   |
| Sunplus Innovation Technology          | 5         | 6.85%   |
| Realtek Semiconductor                  | 4         | 5.48%   |
| Microdia                               | 4         | 5.48%   |
| Syntek                                 | 3         | 4.11%   |
| Quanta                                 | 3         | 4.11%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.11%   |
| Lite-On Technology                     | 2         | 2.74%   |
| Acer                                   | 2         | 2.74%   |
| ViewQuest Technologies                 | 1         | 1.37%   |
| Sonix Technology                       | 1         | 1.37%   |
| Silicon Motion                         | 1         | 1.37%   |
| Ricoh                                  | 1         | 1.37%   |
| Razer USA                              | 1         | 1.37%   |
| Philips (or NXP)                       | 1         | 1.37%   |
| Logitech                               | 1         | 1.37%   |
| Importek                               | 1         | 1.37%   |
| HRY                                    | 1         | 1.37%   |
| Dell                                   | 1         | 1.37%   |
| Bison Electronics                      | 1         | 1.37%   |
| Apple                                  | 1         | 1.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Chicony Integrated Camera                  | 5         | 6.76%   |
| IMC Networks Integrated Camera             | 4         | 5.41%   |
| Syntek Integrated Camera                   | 3         | 4.05%   |
| IMC Networks USB2.0 HD UVC WebCam          | 3         | 4.05%   |
| Chicony Integrated Camera [ThinkPad]       | 3         | 4.05%   |
| Suyin USB 2.0 Camera                       | 2         | 2.7%    |
| Suyin Asus Integrated Webcam               | 2         | 2.7%    |
| Sunplus Integrated_Webcam_HD               | 2         | 2.7%    |
| Sunplus HD WebCam                          | 2         | 2.7%    |
| Realtek Lenovo EasyCamera                  | 2         | 2.7%    |
| Microdia Integrated_Webcam_HD              | 2         | 2.7%    |
| Chicony HP HD Camera                       | 2         | 2.7%    |
| Chicony HD Webcam                          | 2         | 2.7%    |
| Chicony HD User Facing                     | 2         | 2.7%    |
| ViewQuest Ability GABB Webcam              | 1         | 1.35%   |
| Suyin HP Webcam                            | 1         | 1.35%   |
| Suyin HP TrueVision HD Integrated Webcam   | 1         | 1.35%   |
| Sunplus Dell HD Webcam                     | 1         | 1.35%   |
| Sonix USB2.0 HD UVC WebCam                 | 1         | 1.35%   |
| Silicon Motion WebCam SCB-1100N            | 1         | 1.35%   |
| Ricoh Sony Vaio Integrated Webcam          | 1         | 1.35%   |
| Realtek VGA WebCam                         | 1         | 1.35%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.35%   |
| Razer USA Gaming Webcam [Kiyo]             | 1         | 1.35%   |
| Quanta ov9734_techfront_camera             | 1         | 1.35%   |
| Quanta HP Webcam                           | 1         | 1.35%   |
| Quanta HP TrueVision HD Camera             | 1         | 1.35%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc] | 1         | 1.35%   |
| Microdia Sonix Integrated Webcam           | 1         | 1.35%   |
| Microdia Integrated Webcam HD              | 1         | 1.35%   |
| Logitech C922 Pro Stream Webcam            | 1         | 1.35%   |
| Lite-On Integrated Camera                  | 1         | 1.35%   |
| Lite-On HP HD Camera                       | 1         | 1.35%   |
| Importek TOSHIBA Web Camera - HD           | 1         | 1.35%   |
| IMC Networks UVC VGA Webcam                | 1         | 1.35%   |
| HRY USB Camera                             | 1         | 1.35%   |
| Dell Integrated_Webcam_5M_IR               | 1         | 1.35%   |
| Chicony USB2.0 2.0M UVC WebCam             | 1         | 1.35%   |
| Chicony Lenovo Integrated Camera (0.3MP)   | 1         | 1.35%   |
| Chicony Integrated IR Camera               | 1         | 1.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 50%     |
| Shenzhen Goodix Technology | 3         | 18.75%  |
| Synaptics                  | 2         | 12.5%   |
| LighTuning Technology      | 1         | 6.25%   |
| Focal-systems.Corp         | 1         | 6.25%   |
| AuthenTec                  | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 2         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 12.5%   |
| Shenzhen Goodix  Fingerprint Device               | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 6.25%   |
| Validity Sensors VFS301 Fingerprint Reader        | 1         | 6.25%   |
| Validity Sensors Fingerprint scanner              | 1         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 6.25%   |
| Synaptics Fingerprint reader [HP G6]              | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 6.25%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 6.25%   |
| Focal-systems.Corp FT9201Fingerprint.             | 1         | 6.25%   |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 6.25%   |

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
| 0     | 44        | 54.32%  |
| 1     | 32        | 39.51%  |
| 2     | 4         | 4.94%   |
| 3     | 1         | 1.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 16        | 40%     |
| Graphics card         | 9         | 22.5%   |
| Chipcard              | 9         | 22.5%   |
| Net/wireless          | 2         | 5%      |
| Multimedia controller | 2         | 5%      |
| Camera                | 2         | 5%      |

