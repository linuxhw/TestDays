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

Total: 113

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6420              | [f4dcc8c239](https://linux-hardware.org/?probe=f4dcc8c239) | Jan 26, 2024 |
| Acer          | Aspire A317-53              | [efa0303d01](https://linux-hardware.org/?probe=efa0303d01) | Jan 24, 2024 |
| Dell          | Inspiron 3482               | [bbcb062420](https://linux-hardware.org/?probe=bbcb062420) | Dec 29, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [0c55b9f3e3](https://linux-hardware.org/?probe=0c55b9f3e3) | Dec 28, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [9197fe40a7](https://linux-hardware.org/?probe=9197fe40a7) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [e36502092e](https://linux-hardware.org/?probe=e36502092e) | Dec 27, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [b000376310](https://linux-hardware.org/?probe=b000376310) | Dec 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ff3773b480](https://linux-hardware.org/?probe=ff3773b480) | Dec 26, 2023 |
| HP            | EliteBook 850 G3            | [1265cfb294](https://linux-hardware.org/?probe=1265cfb294) | Dec 21, 2023 |
| HP            | EliteBook 850 G3            | [6067c56124](https://linux-hardware.org/?probe=6067c56124) | Dec 19, 2023 |
| HP            | EliteBook 640 14 inch G9... | [51b0a49d02](https://linux-hardware.org/?probe=51b0a49d02) | Nov 27, 2023 |
| Dell          | System XPS L502X            | [33f54ee5dc](https://linux-hardware.org/?probe=33f54ee5dc) | Nov 16, 2023 |
| HP            | ZBook 17 G5                 | [4377844e75](https://linux-hardware.org/?probe=4377844e75) | Nov 02, 2023 |
| Lenovo        | ZIWB2                       | [9e6bd45db9](https://linux-hardware.org/?probe=9e6bd45db9) | Oct 29, 2023 |
| Lenovo        | ZIWB2                       | [2537a6e7b9](https://linux-hardware.org/?probe=2537a6e7b9) | Oct 26, 2023 |
| Lenovo        | ThinkPad T480 20L50101US    | [c6913c1b75](https://linux-hardware.org/?probe=c6913c1b75) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | [188b107eb5](https://linux-hardware.org/?probe=188b107eb5) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bab5438645](https://linux-hardware.org/?probe=bab5438645) | Sep 22, 2023 |
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
| Ubuntu Studio 20.04 | 39        | 41.05%  |
| Ubuntu Studio 22.04 | 32        | 33.68%  |
| Ubuntu Studio 23.04 | 6         | 6.32%   |
| Ubuntu Studio 22.10 | 4         | 4.21%   |
| Ubuntu Studio 21.10 | 3         | 3.16%   |
| Ubuntu Studio 21.04 | 3         | 3.16%   |
| Ubuntu Studio 20.10 | 3         | 3.16%   |
| Ubuntu Studio 23.10 | 2         | 2.11%   |
| Ubuntu Studio 18.04 | 2         | 2.11%   |
| Ubuntu Studio 19.10 | 1         | 1.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 94        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.0-1009-lowlatency   | 3         | 3.06%   |
| 6.2.0-1003-lowlatency   | 3         | 3.06%   |
| 5.4.0-52-lowlatency     | 3         | 3.06%   |
| 5.15.0-56-lowlatency    | 3         | 3.06%   |
| 5.15.0-47-lowlatency    | 3         | 3.06%   |
| 5.13.0-28-lowlatency    | 3         | 3.06%   |
| 6.2.0-1018-lowlatency   | 2         | 2.04%   |
| 5.8.0-55-lowlatency     | 2         | 2.04%   |
| 5.4.0-94-lowlatency     | 2         | 2.04%   |
| 5.4.0-65-lowlatency     | 2         | 2.04%   |
| 5.4.0-45-lowlatency     | 2         | 2.04%   |
| 5.4.0-42-lowlatency     | 2         | 2.04%   |
| 5.19.0-1015-lowlatency  | 2         | 2.04%   |
| 5.15.0-67-lowlatency    | 2         | 2.04%   |
| 5.15.0-50-lowlatency    | 2         | 2.04%   |
| 5.15.0-48-lowlatency    | 2         | 2.04%   |
| 5.15.0-46-lowlatency    | 2         | 2.04%   |
| 5.13.0-30-lowlatency    | 2         | 2.04%   |
| 5.11.0-34-lowlatency    | 2         | 2.04%   |
| 5.11.0-27-lowlatency    | 2         | 2.04%   |
| 6.5.0-17-lowlatency     | 1         | 1.02%   |
| 6.5.0-15-lowlatency     | 1         | 1.02%   |
| 6.5.0-13-lowlatency     | 1         | 1.02%   |
| 6.5.0-10-lowlatency     | 1         | 1.02%   |
| 6.2.8-x64v3-xanmod1     | 1         | 1.02%   |
| 6.2.0-1017-lowlatency   | 1         | 1.02%   |
| 6.2.0-1016-lowlatency   | 1         | 1.02%   |
| 6.2.0-1014-lowlatency   | 1         | 1.02%   |
| 6.2.0-1008-lowlatency   | 1         | 1.02%   |
| 5.8.0-59-lowlatency     | 1         | 1.02%   |
| 5.8.0-50-lowlatency     | 1         | 1.02%   |
| 5.8.0-44-lowlatency     | 1         | 1.02%   |
| 5.8.0-43-lowlatency     | 1         | 1.02%   |
| 5.8.0-34-generic        | 1         | 1.02%   |
| 5.8.0-29-lowlatency     | 1         | 1.02%   |
| 5.8.0-25-lowlatency     | 1         | 1.02%   |
| 5.7.6-050706-lowlatency | 1         | 1.02%   |
| 5.7.6-050706-generic    | 1         | 1.02%   |
| 5.4.0-96-lowlatency     | 1         | 1.02%   |
| 5.4.0-88-lowlatency     | 1         | 1.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 24        | 25.26%  |
| 5.4.0   | 20        | 21.05%  |
| 6.2.0   | 12        | 12.63%  |
| 5.8.0   | 9         | 9.47%   |
| 5.11.0  | 9         | 9.47%   |
| 5.19.0  | 6         | 6.32%   |
| 5.13.0  | 6         | 6.32%   |
| 6.5.0   | 4         | 4.21%   |
| 4.15.0  | 2         | 2.11%   |
| 6.2.8   | 1         | 1.05%   |
| 5.7.6   | 1         | 1.05%   |
| 5.3.0   | 1         | 1.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 24        | 25.26%  |
| 5.4     | 20        | 21.05%  |
| 6.2     | 13        | 13.68%  |
| 5.8     | 9         | 9.47%   |
| 5.11    | 9         | 9.47%   |
| 5.19    | 6         | 6.32%   |
| 5.13    | 6         | 6.32%   |
| 6.5     | 4         | 4.21%   |
| 4.15    | 2         | 2.11%   |
| 5.7     | 1         | 1.05%   |
| 5.3     | 1         | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 94        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| KDE5  | 49        | 52.13%  |
| XFCE  | 38        | 40.43%  |
| GNOME | 6         | 6.38%   |
| LXQt  | 1         | 1.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 89        | 94.68%  |
| Wayland | 5         | 5.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 44        | 46.81%  |
| LightDM | 23        | 24.47%  |
| TDM     | 21        | 22.34%  |
| GDM     | 5         | 5.32%   |
| LXDM    | 1         | 1.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 37        | 38.95%  |
| fr_FR   | 15        | 15.79%  |
| en_GB   | 5         | 5.26%   |
| ru_RU   | 4         | 4.21%   |
| de_DE   | 4         | 4.21%   |
| C       | 4         | 4.21%   |
| es_ES   | 3         | 3.16%   |
| en_CA   | 3         | 3.16%   |
| pt_BR   | 2         | 2.11%   |
| it_IT   | 2         | 2.11%   |
| hu_HU   | 2         | 2.11%   |
| es_MX   | 2         | 2.11%   |
| en_IE   | 2         | 2.11%   |
| Unknown | 2         | 2.11%   |
| nl_NL   | 1         | 1.05%   |
| es_NI   | 1         | 1.05%   |
| es_CR   | 1         | 1.05%   |
| es_AR   | 1         | 1.05%   |
| en_NG   | 1         | 1.05%   |
| en_AU   | 1         | 1.05%   |
| en_AG   | 1         | 1.05%   |
| de_CH   | 1         | 1.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 65        | 69.15%  |
| BIOS | 29        | 30.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 90        | 95.74%  |
| Overlay | 4         | 4.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 69        | 73.4%   |
| MBR  | 25        | 26.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 85        | 89.47%  |
| Yes       | 10        | 10.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 53.19%  |
| Yes       | 44        | 46.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 25        | 26.6%   |
| Hewlett-Packard        | 16        | 17.02%  |
| Dell                   | 15        | 15.96%  |
| ASUSTek Computer       | 12        | 12.77%  |
| Acer                   | 5         | 5.32%   |
| Toshiba                | 4         | 4.26%   |
| Apple                  | 3         | 3.19%   |
| HUAWEI                 | 2         | 2.13%   |
| win element            | 1         | 1.06%   |
| Sony                   | 1         | 1.06%   |
| Samsung Electronics    | 1         | 1.06%   |
| Razer                  | 1         | 1.06%   |
| Intel Client Systems   | 1         | 1.06%   |
| GPU Company            | 1         | 1.06%   |
| Google                 | 1         | 1.06%   |
| Gigabyte Technology    | 1         | 1.06%   |
| Getac                  | 1         | 1.06%   |
| COM1                   | 1         | 1.06%   |
| Clevo                  | 1         | 1.06%   |
| Avell High Performance | 1         | 1.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G50-45 80E3                       | 2         | 2.13%   |
| HP Pavilion dv6                          | 2         | 2.13%   |
| win element MoreFine S500+               | 1         | 1.06%   |
| Toshiba Satellite L755D                  | 1         | 1.06%   |
| Toshiba Satellite L505                   | 1         | 1.06%   |
| Toshiba Satellite C855                   | 1         | 1.06%   |
| Toshiba Satellite A505                   | 1         | 1.06%   |
| Sony VGN-NS31M_W                         | 1         | 1.06%   |
| Samsung 305V4A/305V5A                    | 1         | 1.06%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 1.06%   |
| Lenovo ZIWB2                             | 1         | 1.06%   |
| Lenovo ThinkPad X250 20CL001LMB          | 1         | 1.06%   |
| Lenovo ThinkPad X230 2333A86             | 1         | 1.06%   |
| Lenovo ThinkPad X230 2325AJG             | 1         | 1.06%   |
| Lenovo ThinkPad X230 23245S1             | 1         | 1.06%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 1         | 1.06%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 1.06%   |
| Lenovo ThinkPad W530 2447IG0             | 1         | 1.06%   |
| Lenovo ThinkPad T530 24296HG             | 1         | 1.06%   |
| Lenovo ThinkPad T520 4243K86             | 1         | 1.06%   |
| Lenovo ThinkPad T480 20L50101US          | 1         | 1.06%   |
| Lenovo ThinkPad P50 20EQS0VV03           | 1         | 1.06%   |
| Lenovo ThinkPad L460 20FVS3JK00          | 1         | 1.06%   |
| Lenovo ThinkPad E14 Gen 3 20Y70073GE     | 1         | 1.06%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.06%   |
| Lenovo Legion 5 15ARH05 82B5             | 1         | 1.06%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 1.06%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 1.06%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 1.06%   |
| Lenovo IdeaPad 300-17ISK 80QH            | 1         | 1.06%   |
| Lenovo IdeaPad 3 15ABA7 82RN             | 1         | 1.06%   |
| Lenovo IdeaPad 3 14ARE05 81W3            | 1         | 1.06%   |
| Lenovo G70-80 80FF                       | 1         | 1.06%   |
| Intel Client Systems LAPBC510            | 1         | 1.06%   |
| HUAWEI KLVL-WXXW                         | 1         | 1.06%   |
| HUAWEI HLYL-WXX9                         | 1         | 1.06%   |
| HP ZBook 17 G5                           | 1         | 1.06%   |
| HP ZBook 15 G3                           | 1         | 1.06%   |
| HP Stream Laptop 14-cb0XX                | 1         | 1.06%   |
| HP Sona                                  | 1         | 1.06%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 13        | 13.83%  |
| Lenovo IdeaPad                | 6         | 6.38%   |
| Dell Latitude                 | 6         | 6.38%   |
| Dell Inspiron                 | 6         | 6.38%   |
| HP EliteBook                  | 5         | 5.32%   |
| Toshiba Satellite             | 4         | 4.26%   |
| HP Pavilion                   | 3         | 3.19%   |
| Acer Aspire                   | 3         | 3.19%   |
| Lenovo Legion                 | 2         | 2.13%   |
| Lenovo G50-45                 | 2         | 2.13%   |
| HP ZBook                      | 2         | 2.13%   |
| ASUS VivoBook                 | 2         | 2.13%   |
| ASUS ASUS                     | 2         | 2.13%   |
| win element MoreFine          | 1         | 1.06%   |
| Sony VGN-NS31M                | 1         | 1.06%   |
| Samsung 305V4A                | 1         | 1.06%   |
| Razer Blade                   | 1         | 1.06%   |
| Lenovo ZIWB2                  | 1         | 1.06%   |
| Lenovo G70-80                 | 1         | 1.06%   |
| Intel Client Systems LAPBC510 | 1         | 1.06%   |
| HUAWEI KLVL-WXXW              | 1         | 1.06%   |
| HUAWEI HLYL-WXX9              | 1         | 1.06%   |
| HP Stream                     | 1         | 1.06%   |
| HP Sona                       | 1         | 1.06%   |
| HP OMEN                       | 1         | 1.06%   |
| HP Notebook                   | 1         | 1.06%   |
| HP Laptop                     | 1         | 1.06%   |
| HP Compaq                     | 1         | 1.06%   |
| GPU Company GWNR71517         | 1         | 1.06%   |
| Google Nami                   | 1         | 1.06%   |
| Gigabyte AERO                 | 1         | 1.06%   |
| Getac S400G3                  | 1         | 1.06%   |
| Dell XPS                      | 1         | 1.06%   |
| Dell System                   | 1         | 1.06%   |
| Dell Precision                | 1         | 1.06%   |
| COM1 NBINF-X5-9G5             | 1         | 1.06%   |
| Clevo W35                     | 1         | 1.06%   |
| Avell High Performance Avell  | 1         | 1.06%   |
| ASUS X541NA                   | 1         | 1.06%   |
| ASUS UX305FA                  | 1         | 1.06%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 12        | 12.77%  |
| 2021 | 9         | 9.57%   |
| 2016 | 8         | 8.51%   |
| 2014 | 8         | 8.51%   |
| 2011 | 8         | 8.51%   |
| 2019 | 7         | 7.45%   |
| 2012 | 7         | 7.45%   |
| 2008 | 7         | 7.45%   |
| 2018 | 6         | 6.38%   |
| 2015 | 6         | 6.38%   |
| 2017 | 4         | 4.26%   |
| 2009 | 4         | 4.26%   |
| 2022 | 3         | 3.19%   |
| 2010 | 3         | 3.19%   |
| 2007 | 2         | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 94        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 84        | 89.36%  |
| Enabled  | 10        | 10.64%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 92        | 97.87%  |
| Yes  | 2         | 2.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 39        | 41.05%  |
| 8.01-16.0  | 19        | 20%     |
| 16.01-24.0 | 13        | 13.68%  |
| 3.01-4.0   | 10        | 10.53%  |
| 32.01-64.0 | 8         | 8.42%   |
| 24.01-32.0 | 3         | 3.16%   |
| 2.01-3.0   | 2         | 2.11%   |
| 1.01-2.0   | 1         | 1.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 31        | 31.96%  |
| 2.01-3.0  | 25        | 25.77%  |
| 3.01-4.0  | 19        | 19.59%  |
| 4.01-8.0  | 17        | 17.53%  |
| 8.01-16.0 | 4         | 4.12%   |
| 0.51-1.0  | 1         | 1.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 68        | 71.58%  |
| 2      | 24        | 25.26%  |
| 0      | 2         | 2.11%   |
| 4      | 1         | 1.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 65.26%  |
| Yes       | 33        | 34.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 83.16%  |
| No        | 16        | 16.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 98.94%  |
| No        | 1         | 1.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 78.72%  |
| No        | 20        | 21.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 20        | 21.28%  |
| France       | 13        | 13.83%  |
| Germany      | 8         | 8.51%   |
| Russia       | 5         | 5.32%   |
| Canada       | 5         | 5.32%   |
| UK           | 4         | 4.26%   |
| Spain        | 4         | 4.26%   |
| Italy        | 3         | 3.19%   |
| Brazil       | 3         | 3.19%   |
| Norway       | 2         | 2.13%   |
| Netherlands  | 2         | 2.13%   |
| Mexico       | 2         | 2.13%   |
| Ivory Coast  | 2         | 2.13%   |
| Hungary      | 2         | 2.13%   |
| Costa Rica   | 2         | 2.13%   |
| Yemen        | 1         | 1.06%   |
| Turkey       | 1         | 1.06%   |
| Taiwan       | 1         | 1.06%   |
| Switzerland  | 1         | 1.06%   |
| South Africa | 1         | 1.06%   |
| Poland       | 1         | 1.06%   |
| Peru         | 1         | 1.06%   |
| Nigeria      | 1         | 1.06%   |
| Nicaragua    | 1         | 1.06%   |
| Ireland      | 1         | 1.06%   |
| Indonesia    | 1         | 1.06%   |
| Finland      | 1         | 1.06%   |
| Bulgaria     | 1         | 1.06%   |
| Belgium      | 1         | 1.06%   |
| Austria      | 1         | 1.06%   |
| Australia    | 1         | 1.06%   |
| Argentina    | 1         | 1.06%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Montreal       | 2         | 2.11%   |
| Madrid         | 2         | 2.11%   |
| Hamburg        | 2         | 2.11%   |
| Groningen      | 2         | 2.11%   |
| Denver         | 2         | 2.11%   |
| Budapest       | 2         | 2.11%   |
| Béziers       | 2         | 2.11%   |
| Abidjan        | 2         | 2.11%   |
| Zele           | 1         | 1.05%   |
| Yonkers        | 1         | 1.05%   |
| Yekaterinburg  | 1         | 1.05%   |
| Wroclaw        | 1         | 1.05%   |
| Woonsocket     | 1         | 1.05%   |
| Woodland Park  | 1         | 1.05%   |
| Warner Robins  | 1         | 1.05%   |
| Vienna         | 1         | 1.05%   |
| Verdal         | 1         | 1.05%   |
| Velleron       | 1         | 1.05%   |
| Turin          | 1         | 1.05%   |
| Toulouse       | 1         | 1.05%   |
| Toronto        | 1         | 1.05%   |
| Tarragona      | 1         | 1.05%   |
| Taipei         | 1         | 1.05%   |
| Sunderland     | 1         | 1.05%   |
| Stuttgart      | 1         | 1.05%   |
| Stabekk        | 1         | 1.05%   |
| St Petersburg  | 1         | 1.05%   |
| Sofia          | 1         | 1.05%   |
| Sleman         | 1         | 1.05%   |
| Seropedica     | 1         | 1.05%   |
| Santo André   | 1         | 1.05%   |
| Sanaa          | 1         | 1.05%   |
| San Juan       | 1         | 1.05%   |
| San Francisco  | 1         | 1.05%   |
| Samara         | 1         | 1.05%   |
| Rio de Janeiro | 1         | 1.05%   |
| Ragusa         | 1         | 1.05%   |
| Portland       | 1         | 1.05%   |
| Port Orange    | 1         | 1.05%   |
| Port Harcourt  | 1         | 1.05%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 17        | 17     | 14.91%  |
| WDC                         | 16        | 17     | 14.04%  |
| SK hynix                    | 9         | 10     | 7.89%   |
| Toshiba                     | 7         | 7      | 6.14%   |
| Seagate                     | 7         | 7      | 6.14%   |
| SanDisk                     | 7         | 7      | 6.14%   |
| Intel                       | 6         | 9      | 5.26%   |
| Unknown                     | 4         | 4      | 3.51%   |
| Micron Technology           | 3         | 3      | 2.63%   |
| Kingston                    | 3         | 3      | 2.63%   |
| Hitachi                     | 3         | 3      | 2.63%   |
| UMIS                        | 2         | 2      | 1.75%   |
| PNY                         | 2         | 2      | 1.75%   |
| Phison                      | 2         | 2      | 1.75%   |
| KIOXIA                      | 2         | 2      | 1.75%   |
| Crucial                     | 2         | 2      | 1.75%   |
| China                       | 2         | 2      | 1.75%   |
| XPG                         | 1         | 1      | 0.88%   |
| Wibtek                      | 1         | 1      | 0.88%   |
| Union Memory                | 1         | 1      | 0.88%   |
| Team                        | 1         | 1      | 0.88%   |
| SPCC                        | 1         | 1      | 0.88%   |
| Reeinno                     | 1         | 1      | 0.88%   |
| Realtek                     | 1         | 1      | 0.88%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.88%   |
| Lexar                       | 1         | 1      | 0.88%   |
| Kingston Technology Company | 1         | 1      | 0.88%   |
| KingSpec                    | 1         | 1      | 0.88%   |
| JMicron Technology          | 1         | 1      | 0.88%   |
| Inateck                     | 1         | 1      | 0.88%   |
| HGST                        | 1         | 1      | 0.88%   |
| Fujitsu                     | 1         | 1      | 0.88%   |
| Dogfish                     | 1         | 1      | 0.88%   |
| BHT                         | 1         | 1      | 0.88%   |
| ASMT                        | 1         | 1      | 0.88%   |
| A-DATA Technology           | 1         | 2      | 0.88%   |
| Unknown                     | 1         | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 1.71%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.71%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 1.71%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 1.71%   |
| Samsung SSD 870 EVO 1TB                   | 2         | 1.71%   |
| Samsung SSD 860 EVO 500GB                 | 2         | 1.71%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 1.71%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 1.71%   |
| China SSD 1TB                             | 2         | 1.71%   |
| XPG GAMMIX S7 1TB                         | 1         | 0.85%   |
| Wibtek W800S 512GB SSD                    | 1         | 0.85%   |
| WDC WDS100T2G0A-00JH30 1TB SSD            | 1         | 0.85%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 0.85%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.85%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.85%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 0.85%   |
| WDC WD5000BEKT-60KA9T0 500GB              | 1         | 0.85%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 0.85%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 0.85%   |
| WDC WD3200BEKT-60V5T1 320GB               | 1         | 0.85%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 0.85%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 0.85%   |
| WDC WD10JPVT-75A1YT0 1TB                  | 1         | 0.85%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB      | 1         | 0.85%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB      | 1         | 0.85%   |
| Unknown MMC Card  4GB                     | 1         | 0.85%   |
| Unknown MMC Card  16GB                    | 1         | 0.85%   |
| Unknown DA4128  128GB                     | 1         | 0.85%   |
| Unknown 032G34  32GB                      | 1         | 0.85%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB   | 1         | 0.85%   |
| UMIS RPJTJ256MEE1OWX 256GB                | 1         | 0.85%   |
| UMIS RPITJ512VME2OWD 512GB                | 1         | 0.85%   |
| Toshiba TR150 240GB SSD                   | 1         | 0.85%   |
| Toshiba MK1637GSX 160GB                   | 1         | 0.85%   |
| Toshiba HDWL110 1TB                       | 1         | 0.85%   |
| Team TM8FP4001T 1TB                       | 1         | 0.85%   |
| SPCC Solid State Disk 1TB                 | 1         | 0.85%   |
| SK hynix SKHynix_HFS256GD9TNI-L2A0B 256GB | 1         | 0.85%   |
| SK hynix SC401 SATA 256GB SSD             | 1         | 0.85%   |
| SK hynix SC308 SATA 256GB SSD             | 1         | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 29.03%  |
| Toshiba             | 6         | 6      | 19.35%  |
| Seagate             | 6         | 6      | 19.35%  |
| Hitachi             | 3         | 3      | 9.68%   |
| Samsung Electronics | 2         | 2      | 6.45%   |
| JMicron Technology  | 1         | 1      | 3.23%   |
| Inateck             | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |
| Fujitsu             | 1         | 1      | 3.23%   |
| ASMT                | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 10     | 26.32%  |
| SanDisk             | 5         | 5      | 13.16%  |
| WDC                 | 2         | 2      | 5.26%   |
| SK hynix            | 2         | 2      | 5.26%   |
| PNY                 | 2         | 2      | 5.26%   |
| Micron Technology   | 2         | 2      | 5.26%   |
| Kingston            | 2         | 2      | 5.26%   |
| Crucial             | 2         | 2      | 5.26%   |
| China               | 2         | 2      | 5.26%   |
| Wibtek              | 1         | 1      | 2.63%   |
| Toshiba             | 1         | 1      | 2.63%   |
| SPCC                | 1         | 1      | 2.63%   |
| Reeinno             | 1         | 1      | 2.63%   |
| Lexar               | 1         | 1      | 2.63%   |
| KingSpec            | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| Dogfish             | 1         | 1      | 2.63%   |
| BHT                 | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 33        | 43     | 32.35%  |
| SSD  | 33        | 38     | 32.35%  |
| HDD  | 30        | 32     | 29.41%  |
| MMC  | 6         | 7      | 5.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 58        | 66     | 56.86%  |
| NVMe | 33        | 42     | 32.35%  |
| MMC  | 6         | 7      | 5.88%   |
| SAS  | 5         | 5      | 4.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 47        | 51     | 71.21%  |
| 0.51-1.0   | 19        | 19     | 28.79%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 28        | 29.17%  |
| 251-500    | 26        | 27.08%  |
| 501-1000   | 15        | 15.63%  |
| 51-100     | 8         | 8.33%   |
| 21-50      | 7         | 7.29%   |
| 1001-2000  | 7         | 7.29%   |
| 1-20       | 4         | 4.17%   |
| 2001-3000  | 1         | 1.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 36        | 37.5%   |
| 101-250   | 17        | 17.71%  |
| 21-50     | 16        | 16.67%  |
| 51-100    | 9         | 9.38%   |
| 251-500   | 8         | 8.33%   |
| 501-1000  | 8         | 8.33%   |
| 1001-2000 | 2         | 2.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 5.26%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 5.26%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 5.26%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 5.26%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 5.26%   |
| UMIS RPITJ512VME2OWD 512GB                          | 1         | 1      | 5.26%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 5.26%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 5.26%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 5.26%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 5.26%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 5.26%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 5.26%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 5.26%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 5.26%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 5.26%   |
| KingSpec P3-256 256GB SSD                           | 1         | 1      | 5.26%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 5.26%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 5.26%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 26.32%  |
| Seagate             | 4         | 4      | 21.05%  |
| Samsung Electronics | 3         | 3      | 15.79%  |
| Hitachi             | 2         | 2      | 10.53%  |
| UMIS                | 1         | 1      | 5.26%   |
| Toshiba             | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| KingSpec            | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |

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
| HDD  | 14        | 14     | 73.68%  |
| SSD  | 4         | 4      | 21.05%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Works    | 72        | 91     | 72%     |
| Malfunc  | 19        | 19     | 19%     |
| Detected | 9         | 10     | 9%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 67        | 58.26%  |
| AMD                          | 16        | 13.91%  |
| SK hynix                     | 7         | 6.09%   |
| SanDisk                      | 5         | 4.35%   |
| Samsung Electronics          | 5         | 4.35%   |
| Union Memory (Shenzhen)      | 3         | 2.61%   |
| Phison Electronics           | 3         | 2.61%   |
| Kingston Technology Company  | 2         | 1.74%   |
| Toshiba America Info Systems | 1         | 0.87%   |
| Seagate Technology           | 1         | 0.87%   |
| Realtek Semiconductor        | 1         | 0.87%   |
| Micron Technology            | 1         | 0.87%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.87%   |
| KIOXIA                       | 1         | 0.87%   |
| ADATA Technology             | 1         | 0.87%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 14        | 11.38%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 10        | 8.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 8         | 6.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 6         | 4.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 6         | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 6         | 4.88%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                     | 3         | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3         | 2.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 3         | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 3         | 2.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 2.44%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                         | 2         | 1.63%   |
| SK hynix BC511 NVMe SSD                                                       | 2         | 1.63%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 2         | 1.63%   |
| Phison E12 NVMe Controller                                                    | 2         | 1.63%   |
| Intel Volume Management Device NVMe RAID Controller                           | 2         | 1.63%   |
| Intel Tiger Lake-LP SATA Controller                                           | 2         | 1.63%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                              | 2         | 1.63%   |
| Intel SSD 670p Series [Keystone Harbor]                                       | 2         | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 1.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 1.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 1.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 2         | 1.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 2         | 1.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2         | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2         | 1.63%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                         | 1         | 0.81%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 1         | 0.81%   |
| SK hynix PC611 NVMe Solid State Drive                                         | 1         | 0.81%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                   | 1         | 0.81%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                             | 1         | 0.81%   |
| Seagate FireCuda 530 SSD                                                      | 1         | 0.81%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                         | 1         | 0.81%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                         | 1         | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 0.81%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 1         | 0.81%   |
| Realtek RTS5762 NVMe SSD Controller                                           | 1         | 0.81%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                           | 1         | 0.81%   |
| Micron 2200S NVMe SSD [Cassandra]                                             | 1         | 0.81%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                      | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 67        | 57.76%  |
| NVMe | 33        | 28.45%  |
| RAID | 12        | 10.34%  |
| IDE  | 4         | 3.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 73        | 77.66%  |
| AMD    | 21        | 22.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics | 4         | 4.26%   |
| Intel Core i5-2450M CPU @ 2.50GHz      | 3         | 3.19%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 2.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 2         | 2.13%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 2         | 2.13%   |
| Intel Core i7-5600U CPU @ 2.60GHz      | 2         | 2.13%   |
| Intel Core i7-2630QM CPU @ 2.00GHz     | 2         | 2.13%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 2         | 2.13%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz      | 2         | 2.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 2         | 2.13%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 2         | 2.13%   |
| Intel Core i5-10300H CPU @ 2.50GHz     | 2         | 2.13%   |
| Intel Celeron N4000 CPU @ 1.10GHz      | 2         | 2.13%   |
| AMD Ryzen 7 5825U with Radeon Graphics | 2         | 2.13%   |
| AMD Ryzen 5 5500U with Radeon Graphics | 2         | 2.13%   |
| Intel Processor 5Y10 CPU @ 0.80GHz     | 1         | 1.06%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.06%   |
| Intel Genuine CPU U2300 @ 1.20GHz      | 1         | 1.06%   |
| Intel Core i9-8950HK CPU @ 2.90GHz     | 1         | 1.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz      | 1         | 1.06%   |
| Intel Core i7-8850H CPU @ 2.60GHz      | 1         | 1.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 1.06%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 1         | 1.06%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 1.06%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.06%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz     | 1         | 1.06%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1         | 1.06%   |
| Intel Core i7-3940XM CPU @ 3.00GHz     | 1         | 1.06%   |
| Intel Core i7-3630QM CPU @ 2.40GHz     | 1         | 1.06%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 1         | 1.06%   |
| Intel Core i7-2635QM CPU @ 2.00GHz     | 1         | 1.06%   |
| Intel Core i7-10850H CPU @ 2.70GHz     | 1         | 1.06%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz      | 1         | 1.06%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 1         | 1.06%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 1         | 1.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.06%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.06%   |
| Intel Core i5-4310M CPU @ 2.70GHz      | 1         | 1.06%   |
| Intel Core i5-4210U CPU @ 1.70GHz      | 1         | 1.06%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.06%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 28        | 29.79%  |
| Intel Core i5      | 22        | 23.4%   |
| Other              | 6         | 6.38%   |
| AMD Ryzen 7        | 6         | 6.38%   |
| AMD Ryzen 5        | 6         | 6.38%   |
| Intel Core i3      | 5         | 5.32%   |
| Intel Core 2 Duo   | 5         | 5.32%   |
| Intel Celeron      | 5         | 5.32%   |
| AMD E              | 2         | 2.13%   |
| Intel Pentium Dual | 1         | 1.06%   |
| Intel Genuine      | 1         | 1.06%   |
| Intel Core i9      | 1         | 1.06%   |
| AMD Ryzen 3 PRO    | 1         | 1.06%   |
| AMD Ryzen 3        | 1         | 1.06%   |
| AMD E2             | 1         | 1.06%   |
| AMD E1             | 1         | 1.06%   |
| AMD A6             | 1         | 1.06%   |
| AMD A4             | 1         | 1.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 46        | 48.94%  |
| 4      | 30        | 31.91%  |
| 6      | 12        | 12.77%  |
| 8      | 5         | 5.32%   |
| 10     | 1         | 1.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 94        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 71        | 75.53%  |
| 1      | 23        | 24.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 94        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 21.88%  |
| 0x206a7    | 7         | 7.29%   |
| 0x306a9    | 6         | 6.25%   |
| 0x306d4    | 5         | 5.21%   |
| 0x906ea    | 4         | 4.17%   |
| 0x08600104 | 4         | 4.17%   |
| 0xa0652    | 3         | 3.13%   |
| 0x806ea    | 3         | 3.13%   |
| 0x706e5    | 3         | 3.13%   |
| 0x406e3    | 3         | 3.13%   |
| 0x40651    | 3         | 3.13%   |
| 0x0a50000c | 3         | 3.13%   |
| 0x906e9    | 2         | 2.08%   |
| 0x806c1    | 2         | 2.08%   |
| 0x6fd      | 2         | 2.08%   |
| 0x106e5    | 2         | 2.08%   |
| 0x08600106 | 2         | 2.08%   |
| 0x08108109 | 2         | 2.08%   |
| 0x07030105 | 2         | 2.08%   |
| 0x706a1    | 1         | 1.04%   |
| 0x6fb      | 1         | 1.04%   |
| 0x506e3    | 1         | 1.04%   |
| 0x506c9    | 1         | 1.04%   |
| 0x406c4    | 1         | 1.04%   |
| 0x40661    | 1         | 1.04%   |
| 0x306c3    | 1         | 1.04%   |
| 0x1067a    | 1         | 1.04%   |
| 0x10676    | 1         | 1.04%   |
| 0x08608103 | 1         | 1.04%   |
| 0x08608102 | 1         | 1.04%   |
| 0x08600103 | 1         | 1.04%   |
| 0x07030104 | 1         | 1.04%   |
| 0x06006110 | 1         | 1.04%   |
| 0x0500010d | 1         | 1.04%   |
| 0x05000029 | 1         | 1.04%   |
| 0x03000027 | 1         | 1.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 12        | 12.77%  |
| SandyBridge      | 9         | 9.57%   |
| Skylake          | 8         | 8.51%   |
| Zen 2            | 7         | 7.45%   |
| IvyBridge        | 7         | 7.45%   |
| Broadwell        | 6         | 6.38%   |
| Haswell          | 5         | 5.32%   |
| Penryn           | 4         | 4.26%   |
| Zen 3            | 3         | 3.19%   |
| TigerLake        | 3         | 3.19%   |
| Puma             | 3         | 3.19%   |
| Nehalem          | 3         | 3.19%   |
| IceLake          | 3         | 3.19%   |
| Core             | 3         | 3.19%   |
| CometLake        | 3         | 3.19%   |
| Zen+             | 2         | 2.13%   |
| Westmere         | 2         | 2.13%   |
| Goldmont plus    | 2         | 2.13%   |
| Bobcat           | 2         | 2.13%   |
| Unknown          | 2         | 2.13%   |
| Silvermont       | 1         | 1.06%   |
| K10 Llano        | 1         | 1.06%   |
| Goldmont         | 1         | 1.06%   |
| Excavator        | 1         | 1.06%   |
| Alderlake Hybrid | 1         | 1.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 54.17%  |
| Nvidia | 28        | 23.33%  |
| AMD    | 27        | 22.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 9         | 7.38%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 5.74%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 7         | 5.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 4.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 4.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 5         | 4.1%    |
| Intel HD Graphics 5500                                                    | 5         | 4.1%    |
| Intel UHD Graphics 620                                                    | 4         | 3.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.46%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 2.46%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.64%   |
| Nvidia GK208BM [GeForce 920M]                                             | 2         | 1.64%   |
| Nvidia GF108M [GeForce GT 525M]                                           | 2         | 1.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.64%   |
| Intel Iris Plus Graphics G7                                               | 2         | 1.64%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.64%   |
| AMD Wrestler [Radeon HD 6310]                                             | 2         | 1.64%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.64%   |
| AMD Lucienne                                                              | 2         | 1.64%   |
| AMD Barcelo                                                               | 2         | 1.64%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.82%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.82%   |
| Nvidia GT216M [GeForce GT 230M]                                           | 1         | 0.82%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 1         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.82%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 0.82%   |
| Nvidia GP104GLM [Quadro P5200 Mobile]                                     | 1         | 0.82%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 0.82%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.82%   |
| Nvidia GK107M [GeForce GTX 660M]                                          | 1         | 0.82%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 0.82%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 0.82%   |
| Nvidia GF119M [NVS 4200M]                                                 | 1         | 0.82%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 0.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.82%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 1         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 46.81%  |
| Intel + Nvidia | 19        | 20.21%  |
| 1 x AMD        | 19        | 20.21%  |
| AMD + Nvidia   | 5         | 5.32%   |
| 1 x Nvidia     | 4         | 4.26%   |
| Intel + AMD    | 2         | 2.13%   |
| 2 x AMD        | 1         | 1.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 87        | 92.55%  |
| Proprietary | 7         | 7.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 55.32%  |
| 0.01-0.5   | 14        | 14.89%  |
| 0.51-1.0   | 11        | 11.7%   |
| 1.01-2.0   | 8         | 8.51%   |
| 3.01-4.0   | 5         | 5.32%   |
| 5.01-6.0   | 3         | 3.19%   |
| 8.01-16.0  | 1         | 1.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 18.35%  |
| LG Display              | 19        | 17.43%  |
| BOE                     | 15        | 13.76%  |
| Samsung Electronics     | 13        | 11.93%  |
| Chimei Innolux          | 13        | 11.93%  |
| Lenovo                  | 3         | 2.75%   |
| Hewlett-Packard         | 3         | 2.75%   |
| Dell                    | 3         | 2.75%   |
| Apple                   | 3         | 2.75%   |
| Sharp                   | 2         | 1.83%   |
| Chi Mei Optoelectronics | 2         | 1.83%   |
| Ancor Communications    | 2         | 1.83%   |
| Philips                 | 1         | 0.92%   |
| LG Philips              | 1         | 0.92%   |
| Iiyama                  | 1         | 0.92%   |
| HannStar                | 1         | 0.92%   |
| Hannspree               | 1         | 0.92%   |
| Goldstar                | 1         | 0.92%   |
| CPT                     | 1         | 0.92%   |
| BenQ                    | 1         | 0.92%   |
| ASUSTek Computer        | 1         | 0.92%   |
| Arnos Instruments       | 1         | 0.92%   |
| Acer                    | 1         | 0.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.82%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 1.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.82%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 1.82%   |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch                 | 2         | 1.82%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.82%   |
| AU Optronics LCD Monitor AUO229E 1600x900 382x214mm 17.2-inch         | 2         | 1.82%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.91%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.91%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 344x194mm 15.5-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch | 1         | 0.91%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 0.91%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.91%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch           | 1         | 0.91%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 0.91%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch              | 1         | 0.91%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 0.91%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 1         | 0.91%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 50        | 51.02%  |
| 1366x768 (WXGA)    | 28        | 28.57%  |
| 1600x900 (HD+)     | 5         | 5.1%    |
| 3840x2160 (4K)     | 4         | 4.08%   |
| 1280x800 (WXGA)    | 3         | 3.06%   |
| 1680x1050 (WSXGA+) | 2         | 2.04%   |
| 3440x1440          | 1         | 1.02%   |
| 2880x1800          | 1         | 1.02%   |
| 2560x1440 (QHD)    | 1         | 1.02%   |
| 2160x1440          | 1         | 1.02%   |
| 1920x1200 (WUXGA)  | 1         | 1.02%   |
| 1440x900 (WXGA+)   | 1         | 1.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 52        | 47.71%  |
| 13     | 14        | 12.84%  |
| 17     | 8         | 7.34%   |
| 14     | 8         | 7.34%   |
| 24     | 6         | 5.5%    |
| 12     | 5         | 4.59%   |
| 27     | 3         | 2.75%   |
| 23     | 2         | 1.83%   |
| 21     | 2         | 1.83%   |
| 19     | 2         | 1.83%   |
| 18     | 2         | 1.83%   |
| 84     | 1         | 0.92%   |
| 40     | 1         | 0.92%   |
| 34     | 1         | 0.92%   |
| 20     | 1         | 0.92%   |
| 16     | 1         | 0.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 64        | 59.81%  |
| 351-400     | 12        | 11.21%  |
| 201-300     | 12        | 11.21%  |
| 501-600     | 9         | 8.41%   |
| 401-500     | 7         | 6.54%   |
| 801-900     | 1         | 0.93%   |
| 701-800     | 1         | 0.93%   |
| 1501-2000   | 1         | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 83        | 86.46%  |
| 16/10 | 11        | 11.46%  |
| 3/2   | 1         | 1.04%   |
| 21/9  | 1         | 1.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 49.07%  |
| 81-90          | 17        | 15.74%  |
| 121-130        | 7         | 6.48%   |
| 71-80          | 5         | 4.63%   |
| 61-70          | 5         | 4.63%   |
| 201-250        | 5         | 4.63%   |
| 151-200        | 4         | 3.7%    |
| 301-350        | 3         | 2.78%   |
| 251-300        | 3         | 2.78%   |
| 141-150        | 2         | 1.85%   |
| More than 1000 | 1         | 0.93%   |
| 351-500        | 1         | 0.93%   |
| 131-140        | 1         | 0.93%   |
| 501-1000       | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 48        | 45.28%  |
| 101-120       | 30        | 28.3%   |
| 51-100        | 18        | 16.98%  |
| 161-240       | 9         | 8.49%   |
| More than 240 | 1         | 0.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 79        | 82.29%  |
| 2     | 15        | 15.63%  |
| 3     | 2         | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 59        | 39.07%  |
| Realtek Semiconductor             | 51        | 33.77%  |
| Qualcomm Atheros                  | 15        | 9.93%   |
| Broadcom                          | 7         | 4.64%   |
| Ralink                            | 3         | 1.99%   |
| MediaTek                          | 3         | 1.99%   |
| ASIX Electronics                  | 3         | 1.99%   |
| Ericsson Business Mobile Networks | 2         | 1.32%   |
| Motorola PCS                      | 1         | 0.66%   |
| Marvell Technology Group          | 1         | 0.66%   |
| ICS Advent                        | 1         | 0.66%   |
| Huawei Technologies               | 1         | 0.66%   |
| Hewlett-Packard                   | 1         | 0.66%   |
| DisplayLink                       | 1         | 0.66%   |
| Dell                              | 1         | 0.66%   |
| Broadcom Limited                  | 1         | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 29        | 15.43%  |
| Intel Wireless 7265                                                    | 8         | 4.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 4.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 3.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 3.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 2.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 2.66%   |
| Intel Wireless 8260                                                    | 5         | 2.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 2.66%   |
| Intel Wireless 8265 / 8275                                             | 4         | 2.13%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 1.6%    |
| Intel Wireless 7260                                                    | 3         | 1.6%    |
| Intel WiFi Link 5100                                                   | 3         | 1.6%    |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.6%    |
| Intel Centrino Ultimate-N 6300                                         | 3         | 1.6%    |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 1.06%   |
| Realtek 802.11ac NIC                                                   | 2         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 1.06%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 1.06%   |
| Intel Wireless 3160                                                    | 2         | 1.06%   |
| Intel Ethernet Connection I219-V                                       | 2         | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.06%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.06%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module     | 2         | 1.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.06%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 2         | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 1.06%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.53%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1         | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.53%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 57        | 60.64%  |
| Realtek Semiconductor | 15        | 15.96%  |
| Qualcomm Atheros      | 11        | 11.7%   |
| Broadcom              | 5         | 5.32%   |
| Ralink                | 3         | 3.19%   |
| MediaTek              | 2         | 2.13%   |
| Broadcom Limited      | 1         | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 8         | 8.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 6         | 6.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 5         | 5.26%   |
| Intel Wireless 8260                                              | 5         | 5.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 5         | 5.26%   |
| Intel Wireless 8265 / 8275                                       | 4         | 4.21%   |
| Intel Wi-Fi 6 AX200                                              | 4         | 4.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 3         | 3.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 3         | 3.16%   |
| Intel Wireless 7260                                              | 3         | 3.16%   |
| Intel WiFi Link 5100                                             | 3         | 3.16%   |
| Intel Wi-Fi 6 AX201                                              | 3         | 3.16%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 3.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 2.11%   |
| Realtek 802.11ac NIC                                             | 2         | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 2.11%   |
| Intel Wireless 3160                                              | 2         | 2.11%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 2         | 2.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                   | 2         | 2.11%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 2.11%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller      | 1         | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.05%   |
| Realtek RTL8191SEvB Wireless LAN Controller                      | 1         | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1.05%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.05%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1         | 1.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 1         | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                          | 1         | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter    | 1         | 1.05%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]          | 1         | 1.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 1.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 1         | 1.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                  | 1         | 1.05%   |
| Intel Centrino Wireless-N 6150                                   | 1         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 41        | 47.67%  |
| Intel                    | 27        | 31.4%   |
| Qualcomm Atheros         | 6         | 6.98%   |
| Broadcom                 | 4         | 4.65%   |
| ASIX Electronics         | 3         | 3.49%   |
| MediaTek                 | 1         | 1.16%   |
| Marvell Technology Group | 1         | 1.16%   |
| ICS Advent               | 1         | 1.16%   |
| Hewlett-Packard          | 1         | 1.16%   |
| DisplayLink              | 1         | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 29        | 32.95%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 7.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 5.68%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 3.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 2.27%   |
| Intel Ethernet Connection I219-V                                       | 2         | 2.27%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 2.27%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 2.27%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 2.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 2.27%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.14%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.14%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.14%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.14%   |
| MediaTek File-CD Gadget                                                | 1         | 1.14%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.14%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.14%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.14%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 1.14%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.14%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.14%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 1.14%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.14%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.14%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 1         | 1.14%   |
| HP lt4120 Snapdragon X5 LTE                                            | 1         | 1.14%   |
| DisplayLink HP Port Replicator (Composite Device)                      | 1         | 1.14%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1         | 1.14%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 1         | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 93        | 52.54%  |
| Ethernet | 79        | 44.63%  |
| Modem    | 4         | 2.26%   |
| Unknown  | 1         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 80%     |
| Ethernet | 20        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 73        | 77.66%  |
| 1     | 19        | 20.21%  |
| 3     | 1         | 1.06%   |
| 0     | 1         | 1.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 67        | 71.28%  |
| Yes  | 27        | 28.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 52.7%   |
| Realtek Semiconductor           | 6         | 8.11%   |
| Qualcomm Atheros Communications | 5         | 6.76%   |
| Broadcom                        | 5         | 6.76%   |
| Apple                           | 3         | 4.05%   |
| Realtek                         | 2         | 2.7%    |
| Ralink Technology               | 2         | 2.7%    |
| Lite-On Technology              | 2         | 2.7%    |
| IMC Networks                    | 2         | 2.7%    |
| Hewlett-Packard                 | 2         | 2.7%    |
| Dell                            | 2         | 2.7%    |
| Ralink                          | 1         | 1.35%   |
| MediaTek                        | 1         | 1.35%   |
| Foxconn International           | 1         | 1.35%   |
| ASUSTek Computer                | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 21        | 28.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 6         | 8.11%   |
| Intel AX201 Bluetooth                             | 5         | 6.76%   |
| Realtek Bluetooth Radio                           | 4         | 5.41%   |
| Intel AX200 Bluetooth                             | 4         | 5.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 4         | 5.41%   |
| Realtek Bluetooth Radio                           | 2         | 2.7%    |
| Qualcomm Atheros  Bluetooth Device                | 2         | 2.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 2.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 2.7%    |
| Intel Bluetooth Device                            | 2         | 2.7%    |
| Apple Bluetooth Host Controller                   | 2         | 2.7%    |
| Realtek RTL8723B Bluetooth                        | 1         | 1.35%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 1.35%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 1.35%   |
| Ralink CSR BS8510                                 | 1         | 1.35%   |
| Ralink RT3290 Bluetooth                           | 1         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 1.35%   |
| MediaTek Wireless_Device                          | 1         | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1.35%   |
| IMC Networks Wireless_Device                      | 1         | 1.35%   |
| IMC Networks Bluetooth Radio                      | 1         | 1.35%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 1.35%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 1.35%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.35%   |
| Dell Wireless 370 Bluetooth Mini-card             | 1         | 1.35%   |
| Dell DW375 Bluetooth Module                       | 1         | 1.35%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 1.35%   |
| ASUS BT-270 Bluetooth Adapter                     | 1         | 1.35%   |
| Apple Bluetooth USB Host Controller               | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 73        | 54.48%  |
| AMD                        | 25        | 18.66%  |
| Nvidia                     | 24        | 17.91%  |
| Yealink Network Technology | 1         | 0.75%   |
| Yamaha                     | 1         | 0.75%   |
| QinHeng Electronics        | 1         | 0.75%   |
| Mackie Designs             | 1         | 0.75%   |
| Logitech                   | 1         | 0.75%   |
| Lenovo                     | 1         | 0.75%   |
| Focusrite-Novation         | 1         | 0.75%   |
| Dell                       | 1         | 0.75%   |
| C-Media Electronics        | 1         | 0.75%   |
| BR23                       | 1         | 0.75%   |
| Behringer.......           | 1         | 0.75%   |
| ASUSTek Computer           | 1         | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 8.07%   |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 6.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 5.59%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 5.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 4.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 3.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 3.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.73%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 3.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 3.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 3.11%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 2.48%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.48%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.86%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.86%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.86%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.24%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 1.24%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.24%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.24%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.24%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.24%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.24%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.24%   |
| Yealink Network Technology VoIP Phone                                      | 1         | 0.62%   |
| Yamaha Steinberg UR242                                                     | 1         | 0.62%   |
| QinHeng Electronics CH345 MIDI adapter                                     | 1         | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.62%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.62%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 30.7%   |
| SK hynix            | 31        | 27.19%  |
| Micron Technology   | 14        | 12.28%  |
| Kingston            | 13        | 11.4%   |
| Ramaxel Technology  | 4         | 3.51%   |
| Unknown             | 3         | 2.63%   |
| Crucial             | 3         | 2.63%   |
| Timetec             | 2         | 1.75%   |
| Nanya Technology    | 2         | 1.75%   |
| Transcend           | 1         | 0.88%   |
| Patriot             | 1         | 0.88%   |
| G.Skill             | 1         | 0.88%   |
| Elpida              | 1         | 0.88%   |
| Corsair             | 1         | 0.88%   |
| A-DATA Technology   | 1         | 0.88%   |
| Unknown             | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 3.28%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s         | 4         | 3.28%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 2.46%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 3         | 2.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 2.46%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 2         | 1.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.64%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 1.64%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 1.64%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 1.64%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 1.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 1.64%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 1.64%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s             | 1         | 0.82%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 0.82%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.82%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s           | 1         | 0.82%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 0.82%   |
| Timetec RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.82%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 0.82%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s              | 1         | 0.82%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s         | 1         | 0.82%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.82%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.82%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.82%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.82%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 1         | 0.82%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 1         | 0.82%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 0.82%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 0.82%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 0.82%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB DDR4 2400MT/s              | 1         | 0.82%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2400MT/s    | 1         | 0.82%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 0.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 45        | 46.88%  |
| DDR4   | 39        | 40.63%  |
| DDR2   | 5         | 5.21%   |
| SDRAM  | 3         | 3.13%   |
| LPDDR4 | 2         | 2.08%   |
| LPDDR3 | 2         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 89.58%  |
| Row Of Chips | 8         | 8.33%   |
| Chip         | 1         | 1.04%   |
| Unknown      | 1         | 1.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 41        | 37.27%  |
| 4096  | 40        | 36.36%  |
| 16384 | 12        | 10.91%  |
| 2048  | 12        | 10.91%  |
| 1024  | 3         | 2.73%   |
| 32768 | 2         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 36        | 34.95%  |
| 3200    | 17        | 16.5%   |
| 2667    | 14        | 13.59%  |
| 1334    | 9         | 8.74%   |
| 2400    | 7         | 6.8%    |
| 2133    | 5         | 4.85%   |
| 1333    | 4         | 3.88%   |
| 667     | 3         | 2.91%   |
| 4267    | 2         | 1.94%   |
| 4199    | 2         | 1.94%   |
| 1639    | 1         | 0.97%   |
| 1067    | 1         | 0.97%   |
| 800     | 1         | 0.97%   |
| Unknown | 1         | 0.97%   |

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
| Chicony Electronics                    | 23        | 27.06%  |
| IMC Networks                           | 9         | 10.59%  |
| Suyin                                  | 6         | 7.06%   |
| Realtek Semiconductor                  | 6         | 7.06%   |
| Sunplus Innovation Technology          | 5         | 5.88%   |
| Quanta                                 | 5         | 5.88%   |
| Microdia                               | 4         | 4.71%   |
| Syntek                                 | 3         | 3.53%   |
| Lite-On Technology                     | 3         | 3.53%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.53%   |
| Sonix Technology                       | 2         | 2.35%   |
| Bison Electronics                      | 2         | 2.35%   |
| Apple                                  | 2         | 2.35%   |
| Acer                                   | 2         | 2.35%   |
| ViewQuest Technologies                 | 1         | 1.18%   |
| Silicon Motion                         | 1         | 1.18%   |
| Ricoh                                  | 1         | 1.18%   |
| Razer USA                              | 1         | 1.18%   |
| Philips (or NXP)                       | 1         | 1.18%   |
| Luxvisions Innotech Limited            | 1         | 1.18%   |
| Logitech                               | 1         | 1.18%   |
| Importek                               | 1         | 1.18%   |
| HRY                                    | 1         | 1.18%   |
| Dell                                   | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Chicony Integrated Camera                  | 6         | 6.98%   |
| IMC Networks Integrated Camera             | 4         | 4.65%   |
| Syntek Integrated Camera                   | 3         | 3.49%   |
| Realtek Lenovo EasyCamera                  | 3         | 3.49%   |
| IMC Networks USB2.0 HD UVC WebCam          | 3         | 3.49%   |
| Chicony Integrated Camera [ThinkPad]       | 3         | 3.49%   |
| Chicony HD User Facing                     | 3         | 3.49%   |
| Suyin USB 2.0 Camera                       | 2         | 2.33%   |
| Suyin Asus Integrated Webcam               | 2         | 2.33%   |
| Sunplus Integrated_Webcam_HD               | 2         | 2.33%   |
| Sunplus HD WebCam                          | 2         | 2.33%   |
| Sonix USB2.0 HD UVC WebCam                 | 2         | 2.33%   |
| Microdia Integrated_Webcam_HD              | 2         | 2.33%   |
| Chicony HP HD Camera                       | 2         | 2.33%   |
| Chicony HD Webcam                          | 2         | 2.33%   |
| Apple FaceTime HD Camera                   | 2         | 2.33%   |
| ViewQuest Ability GABB Webcam              | 1         | 1.16%   |
| Suyin HP Webcam                            | 1         | 1.16%   |
| Suyin HP TrueVision HD Integrated Webcam   | 1         | 1.16%   |
| Sunplus Dell HD Webcam                     | 1         | 1.16%   |
| Silicon Motion WebCam SCB-1100N            | 1         | 1.16%   |
| Ricoh Sony Vaio Integrated Webcam          | 1         | 1.16%   |
| Realtek VGA WebCam                         | 1         | 1.16%   |
| Realtek Integrated_Webcam_HD               | 1         | 1.16%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.16%   |
| Razer USA Gaming Webcam [Kiyo]             | 1         | 1.16%   |
| Quanta ov9734_techfront_camera             | 1         | 1.16%   |
| Quanta Laptop_Integrated_Webcam_2HDM       | 1         | 1.16%   |
| Quanta HP Webcam                           | 1         | 1.16%   |
| Quanta HP TrueVision HD Camera             | 1         | 1.16%   |
| Quanta HP HD Camera                        | 1         | 1.16%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc] | 1         | 1.16%   |
| Microdia Sonix Integrated Webcam           | 1         | 1.16%   |
| Microdia Integrated Webcam HD              | 1         | 1.16%   |
| Luxvisions Innotech Limited HP HD Camera   | 1         | 1.16%   |
| Logitech C922 Pro Stream Webcam            | 1         | 1.16%   |
| Lite-On Integrated Camera                  | 1         | 1.16%   |
| Lite-On HP HD Webcam                       | 1         | 1.16%   |
| Lite-On HP HD Camera                       | 1         | 1.16%   |
| Importek TOSHIBA Web Camera - HD           | 1         | 1.16%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 47.06%  |
| Synaptics                  | 3         | 17.65%  |
| Shenzhen Goodix Technology | 3         | 17.65%  |
| LighTuning Technology      | 1         | 5.88%   |
| Focal-systems.Corp         | 1         | 5.88%   |
| AuthenTec                  | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 2         | 11.76%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 11.76%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 2         | 11.76%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 11.76%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 5.88%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 5.88%   |
| Validity Sensors VFS301 Fingerprint Reader        | 1         | 5.88%   |
| Validity Sensors Fingerprint scanner              | 1         | 5.88%   |
| Synaptics Fingerprint reader [HP G6]              | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 5.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 5.88%   |
| Focal-systems.Corp FT9201Fingerprint.Ì         | 1         | 5.88%   |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Broadcom            | 5         | 41.67%  |
| Upek                | 3         | 25%     |
| Alcor Micro         | 2         | 16.67%  |
| Lenovo              | 1         | 8.33%   |
| Chicony Electronics | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 53        | 56.38%  |
| 1     | 35        | 37.23%  |
| 2     | 5         | 5.32%   |
| 3     | 1         | 1.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 17        | 37.78%  |
| Chipcard              | 10        | 22.22%  |
| Graphics card         | 8         | 17.78%  |
| Net/wireless          | 3         | 6.67%   |
| Multimedia controller | 2         | 4.44%   |
| Camera                | 2         | 4.44%   |
| Storage               | 1         | 2.22%   |
| Card reader           | 1         | 2.22%   |
| Bluetooth             | 1         | 2.22%   |

