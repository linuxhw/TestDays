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

Total: 145

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Prestige 13 AI+ Evo A2VM... | [e0ef8014cc](https://linux-hardware.org/?probe=e0ef8014cc) | Dec 31, 2024 |
| ASUSTek       | N750JV                      | [39dd282ac2](https://linux-hardware.org/?probe=39dd282ac2) | Dec 26, 2024 |
| Unknown       | Unknown                     | [ee3d394ad4](https://linux-hardware.org/?probe=ee3d394ad4) | Dec 22, 2024 |
| HP            | ProBook 640 G2              | [9e14504376](https://linux-hardware.org/?probe=9e14504376) | Dec 02, 2024 |
| HP            | EliteBook 840 G3            | [a1c6d79081](https://linux-hardware.org/?probe=a1c6d79081) | Oct 23, 2024 |
| Sony          | VPCCB3C5E                   | [32c8a0fd43](https://linux-hardware.org/?probe=32c8a0fd43) | Oct 23, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [8132169207](https://linux-hardware.org/?probe=8132169207) | Oct 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [d875e5f8df](https://linux-hardware.org/?probe=d875e5f8df) | Oct 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [ffd8af5438](https://linux-hardware.org/?probe=ffd8af5438) | Sep 25, 2024 |
| Apple         | MacBookPro12,1              | [ce7cf8209e](https://linux-hardware.org/?probe=ce7cf8209e) | Aug 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [7d197b82ba](https://linux-hardware.org/?probe=7d197b82ba) | Aug 29, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b6ee09c245](https://linux-hardware.org/?probe=b6ee09c245) | Aug 14, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [53a28ccde0](https://linux-hardware.org/?probe=53a28ccde0) | Aug 14, 2024 |
| Lenovo        | ThinkPad T450s 20BWS0X00... | [a6f146c7b7](https://linux-hardware.org/?probe=a6f146c7b7) | Aug 09, 2024 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [0b60161050](https://linux-hardware.org/?probe=0b60161050) | Jul 24, 2024 |
| Dell          | Precision 5520              | [d7b6062639](https://linux-hardware.org/?probe=d7b6062639) | Jul 21, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [a3ffc85576](https://linux-hardware.org/?probe=a3ffc85576) | Jun 21, 2024 |
| Lenovo        | IdeaPad Slim 3 16IAH8 83... | [ae3b8db2e7](https://linux-hardware.org/?probe=ae3b8db2e7) | Jun 18, 2024 |
| Lenovo        | ThinkPad T420 4236A38       | [eec5a148c0](https://linux-hardware.org/?probe=eec5a148c0) | Jun 14, 2024 |
| Lenovo        | ThinkPad T420 4236A38       | [fb0d42ccdd](https://linux-hardware.org/?probe=fb0d42ccdd) | Jun 13, 2024 |
| Dell          | Latitude 3450               | [c7b7155c10](https://linux-hardware.org/?probe=c7b7155c10) | Jun 03, 2024 |
| HP            | Pavilion dv6                | [1d8af97b78](https://linux-hardware.org/?probe=1d8af97b78) | May 15, 2024 |
| Acer          | Aspire ES1-571              | [87a9fcc5ab](https://linux-hardware.org/?probe=87a9fcc5ab) | May 12, 2024 |
| Acer          | Nitro AN16-41               | [4ccd0953dd](https://linux-hardware.org/?probe=4ccd0953dd) | May 09, 2024 |
| Gigabyte      | AERO 15-X9                  | [a62c895461](https://linux-hardware.org/?probe=a62c895461) | Apr 26, 2024 |
| Gigabyte      | AERO 15-X9                  | [25245adc43](https://linux-hardware.org/?probe=25245adc43) | Apr 26, 2024 |
| Samsung       | 730QCJ/730QCR               | [0d6a3363b8](https://linux-hardware.org/?probe=0d6a3363b8) | Apr 15, 2024 |
| Acer          | Aspire A317-53              | [ddd85b18e6](https://linux-hardware.org/?probe=ddd85b18e6) | Apr 04, 2024 |
| HP            | Pavilion 15                 | [520fd1241e](https://linux-hardware.org/?probe=520fd1241e) | Mar 14, 2024 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | [cf518d2630](https://linux-hardware.org/?probe=cf518d2630) | Mar 10, 2024 |
| MSI           | Alpha 15 A4DEK              | [bf844ef78f](https://linux-hardware.org/?probe=bf844ef78f) | Mar 09, 2024 |
| Lenovo        | ThinkPad L540 20AV004VGE    | [05d6a4d686](https://linux-hardware.org/?probe=05d6a4d686) | Feb 03, 2024 |
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
| Ubuntu Studio 20.04 | 40        | 33.06%  |
| Ubuntu Studio 22.04 | 38        | 31.4%   |
| Ubuntu Studio 24.04 | 16        | 13.22%  |
| Ubuntu Studio 23.04 | 6         | 4.96%   |
| Ubuntu Studio 23.10 | 4         | 3.31%   |
| Ubuntu Studio 22.10 | 4         | 3.31%   |
| Ubuntu Studio 21.10 | 3         | 2.48%   |
| Ubuntu Studio 21.04 | 3         | 2.48%   |
| Ubuntu Studio 20.10 | 3         | 2.48%   |
| Ubuntu Studio 18.04 | 2         | 1.65%   |
| Ubuntu Studio 24.10 | 1         | 0.83%   |
| Ubuntu Studio 19.10 | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 119       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.8.0-31-lowlatency    | 6         | 4.76%   |
| 6.2.0-1009-lowlatency  | 3         | 2.38%   |
| 6.2.0-1003-lowlatency  | 3         | 2.38%   |
| 5.4.0-52-lowlatency    | 3         | 2.38%   |
| 5.15.0-56-lowlatency   | 3         | 2.38%   |
| 5.15.0-47-lowlatency   | 3         | 2.38%   |
| 5.13.0-28-lowlatency   | 3         | 2.38%   |
| 6.8.0-47-lowlatency    | 2         | 1.59%   |
| 6.8.0-45-lowlatency    | 2         | 1.59%   |
| 6.8.0-41-lowlatency    | 2         | 1.59%   |
| 6.5.0-27-lowlatency    | 2         | 1.59%   |
| 6.5.0-25-lowlatency    | 2         | 1.59%   |
| 6.5.0-15-lowlatency    | 2         | 1.59%   |
| 6.2.0-1018-lowlatency  | 2         | 1.59%   |
| 5.8.0-55-lowlatency    | 2         | 1.59%   |
| 5.4.0-94-lowlatency    | 2         | 1.59%   |
| 5.4.0-65-lowlatency    | 2         | 1.59%   |
| 5.4.0-45-lowlatency    | 2         | 1.59%   |
| 5.4.0-42-lowlatency    | 2         | 1.59%   |
| 5.19.0-1015-lowlatency | 2         | 1.59%   |
| 5.15.0-67-lowlatency   | 2         | 1.59%   |
| 5.15.0-50-lowlatency   | 2         | 1.59%   |
| 5.15.0-48-lowlatency   | 2         | 1.59%   |
| 5.15.0-46-lowlatency   | 2         | 1.59%   |
| 5.13.0-30-lowlatency   | 2         | 1.59%   |
| 5.11.0-34-lowlatency   | 2         | 1.59%   |
| 5.11.0-27-lowlatency   | 2         | 1.59%   |
| 6.8.0-50-lowlatency    | 1         | 0.79%   |
| 6.8.0-49-generic       | 1         | 0.79%   |
| 6.8.0-40-lowlatency    | 1         | 0.79%   |
| 6.8.0-39-lowlatency    | 1         | 0.79%   |
| 6.8.0-38-lowlatency    | 1         | 0.79%   |
| 6.8.0-35-lowlatency    | 1         | 0.79%   |
| 6.5.0-28-lowlatency    | 1         | 0.79%   |
| 6.5.0-17-lowlatency    | 1         | 0.79%   |
| 6.5.0-13-lowlatency    | 1         | 0.79%   |
| 6.5.0-10-lowlatency    | 1         | 0.79%   |
| 6.2.8-x64v3-xanmod1    | 1         | 0.79%   |
| 6.2.0-1017-lowlatency  | 1         | 0.79%   |
| 6.2.0-1016-lowlatency  | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 27        | 22.31%  |
| 5.4.0   | 20        | 16.53%  |
| 6.8.0   | 17        | 14.05%  |
| 6.2.0   | 12        | 9.92%   |
| 6.5.0   | 9         | 7.44%   |
| 5.8.0   | 9         | 7.44%   |
| 5.11.0  | 9         | 7.44%   |
| 5.19.0  | 6         | 4.96%   |
| 5.13.0  | 6         | 4.96%   |
| 4.15.0  | 2         | 1.65%   |
| 6.2.8   | 1         | 0.83%   |
| 6.11.0  | 1         | 0.83%   |
| 5.7.6   | 1         | 0.83%   |
| 5.3.0   | 1         | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 27        | 22.31%  |
| 5.4     | 20        | 16.53%  |
| 6.8     | 17        | 14.05%  |
| 6.2     | 13        | 10.74%  |
| 6.5     | 9         | 7.44%   |
| 5.8     | 9         | 7.44%   |
| 5.11    | 9         | 7.44%   |
| 5.19    | 6         | 4.96%   |
| 5.13    | 6         | 4.96%   |
| 4.15    | 2         | 1.65%   |
| 6.11    | 1         | 0.83%   |
| 5.7     | 1         | 0.83%   |
| 5.3     | 1         | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 119       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| KDE5  | 70        | 58.82%  |
| XFCE  | 39        | 32.77%  |
| GNOME | 8         | 6.72%   |
| LXQt  | 1         | 0.84%   |
| KDE6  | 1         | 0.84%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 109       | 91.6%   |
| Wayland | 10        | 8.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 66        | 55.46%  |
| LightDM | 26        | 21.85%  |
| TDM     | 21        | 17.65%  |
| GDM     | 5         | 4.2%    |
| LXDM    | 1         | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 53        | 44.17%  |
| fr_FR   | 18        | 15%     |
| en_GB   | 6         | 5%      |
| ru_RU   | 5         | 4.17%   |
| de_DE   | 5         | 4.17%   |
| C       | 5         | 4.17%   |
| es_ES   | 4         | 3.33%   |
| it_IT   | 3         | 2.5%    |
| en_CA   | 3         | 2.5%    |
| pt_BR   | 2         | 1.67%   |
| hu_HU   | 2         | 1.67%   |
| es_MX   | 2         | 1.67%   |
| en_IE   | 2         | 1.67%   |
| Unknown | 2         | 1.67%   |
| nl_NL   | 1         | 0.83%   |
| es_NI   | 1         | 0.83%   |
| es_CR   | 1         | 0.83%   |
| es_AR   | 1         | 0.83%   |
| en_NG   | 1         | 0.83%   |
| en_AU   | 1         | 0.83%   |
| en_AG   | 1         | 0.83%   |
| de_CH   | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 84        | 70.59%  |
| BIOS | 35        | 29.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 112       | 94.12%  |
| Overlay | 6         | 5.04%   |
| Ext3    | 1         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 91        | 76.47%  |
| MBR  | 28        | 23.53%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 107       | 88.43%  |
| Yes       | 14        | 11.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 55.46%  |
| Yes       | 53        | 44.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 33        | 27.73%  |
| Hewlett-Packard        | 20        | 16.81%  |
| Dell                   | 17        | 14.29%  |
| ASUSTek Computer       | 14        | 11.76%  |
| Acer                   | 7         | 5.88%   |
| Toshiba                | 4         | 3.36%   |
| Apple                  | 4         | 3.36%   |
| Sony                   | 2         | 1.68%   |
| Samsung Electronics    | 2         | 1.68%   |
| MSI                    | 2         | 1.68%   |
| HUAWEI                 | 2         | 1.68%   |
| win element            | 1         | 0.84%   |
| Razer                  | 1         | 0.84%   |
| Intel Client Systems   | 1         | 0.84%   |
| GPU Company            | 1         | 0.84%   |
| Google                 | 1         | 0.84%   |
| Gigabyte Technology    | 1         | 0.84%   |
| Getac                  | 1         | 0.84%   |
| COM1                   | 1         | 0.84%   |
| Clevo                  | 1         | 0.84%   |
| Avell High Performance | 1         | 0.84%   |
| ARDOR GAMING           | 1         | 0.84%   |
| Unknown                | 1         | 0.84%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP Pavilion dv6                          | 3         | 2.52%   |
| Lenovo G50-45 80E3                       | 2         | 1.68%   |
| HP EliteBook 840 G3                      | 2         | 1.68%   |
| win element MoreFine S500+               | 1         | 0.84%   |
| Toshiba Satellite L755D                  | 1         | 0.84%   |
| Toshiba Satellite L505                   | 1         | 0.84%   |
| Toshiba Satellite C855                   | 1         | 0.84%   |
| Toshiba Satellite A505                   | 1         | 0.84%   |
| Sony VPCCB3C5E                           | 1         | 0.84%   |
| Sony VGN-NS31M_W                         | 1         | 0.84%   |
| Samsung 730QCJ/730QCR                    | 1         | 0.84%   |
| Samsung 305V4A/305V5A                    | 1         | 0.84%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 0.84%   |
| MSI Prestige 13 AI+ Evo A2VMG            | 1         | 0.84%   |
| MSI Alpha 15 A4DEK                       | 1         | 0.84%   |
| Lenovo ZIWB2                             | 1         | 0.84%   |
| Lenovo ThinkPad X250 20CL001LMB          | 1         | 0.84%   |
| Lenovo ThinkPad X230 2333A86             | 1         | 0.84%   |
| Lenovo ThinkPad X230 2325AJG             | 1         | 0.84%   |
| Lenovo ThinkPad X230 23245S1             | 1         | 0.84%   |
| Lenovo ThinkPad X13 Gen 1 20UGS28900     | 1         | 0.84%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 1         | 0.84%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0ET00 | 1         | 0.84%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 0.84%   |
| Lenovo ThinkPad W530 2447IG0             | 1         | 0.84%   |
| Lenovo ThinkPad T530 24296HG             | 1         | 0.84%   |
| Lenovo ThinkPad T520 4243K86             | 1         | 0.84%   |
| Lenovo ThinkPad T480 20L50101US          | 1         | 0.84%   |
| Lenovo ThinkPad T450s 20BWS0X000         | 1         | 0.84%   |
| Lenovo ThinkPad T420 4236A38             | 1         | 0.84%   |
| Lenovo ThinkPad P50 20EQS0VV03           | 1         | 0.84%   |
| Lenovo ThinkPad L540 20AV004VGE          | 1         | 0.84%   |
| Lenovo ThinkPad L460 20FVS3JK00          | 1         | 0.84%   |
| Lenovo ThinkPad E14 Gen 3 20Y70073GE     | 1         | 0.84%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 0.84%   |
| Lenovo Legion 5 15ARH05 82B5             | 1         | 0.84%   |
| Lenovo IdeaPad Slim 3 16IAH8 83ES        | 1         | 0.84%   |
| Lenovo IdeaPad S145-14IWL 81MU           | 1         | 0.84%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 0.84%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 18        | 15.13%  |
| Lenovo IdeaPad                | 9         | 7.56%   |
| Dell Latitude                 | 7         | 5.88%   |
| HP EliteBook                  | 6         | 5.04%   |
| Dell Inspiron                 | 6         | 5.04%   |
| HP Pavilion                   | 5         | 4.2%    |
| Toshiba Satellite             | 4         | 3.36%   |
| Acer Aspire                   | 4         | 3.36%   |
| ASUS ASUS                     | 3         | 2.52%   |
| Lenovo Legion                 | 2         | 1.68%   |
| Lenovo G50-45                 | 2         | 1.68%   |
| HP ZBook                      | 2         | 1.68%   |
| Dell Precision                | 2         | 1.68%   |
| ASUS VivoBook                 | 2         | 1.68%   |
| Acer Nitro                    | 2         | 1.68%   |
| win element MoreFine          | 1         | 0.84%   |
| Sony VPCCB3C5E                | 1         | 0.84%   |
| Sony VGN-NS31M                | 1         | 0.84%   |
| Samsung 730QCJ                | 1         | 0.84%   |
| Samsung 305V4A                | 1         | 0.84%   |
| Razer Blade                   | 1         | 0.84%   |
| MSI Prestige                  | 1         | 0.84%   |
| MSI Alpha                     | 1         | 0.84%   |
| Lenovo ZIWB2                  | 1         | 0.84%   |
| Lenovo G70-80                 | 1         | 0.84%   |
| Intel Client Systems LAPBC510 | 1         | 0.84%   |
| HUAWEI KLVL-WXXW              | 1         | 0.84%   |
| HUAWEI HLYL-WXX9              | 1         | 0.84%   |
| HP Stream                     | 1         | 0.84%   |
| HP Sona                       | 1         | 0.84%   |
| HP ProBook                    | 1         | 0.84%   |
| HP OMEN                       | 1         | 0.84%   |
| HP Notebook                   | 1         | 0.84%   |
| HP Laptop                     | 1         | 0.84%   |
| HP Compaq                     | 1         | 0.84%   |
| GPU Company GWNR71517         | 1         | 0.84%   |
| Google Nami                   | 1         | 0.84%   |
| Gigabyte AERO                 | 1         | 0.84%   |
| Getac S400G3                  | 1         | 0.84%   |
| Dell XPS                      | 1         | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 15        | 12.61%  |
| 2014 | 11        | 9.24%   |
| 2021 | 10        | 8.4%    |
| 2016 | 10        | 8.4%    |
| 2011 | 10        | 8.4%    |
| 2015 | 9         | 7.56%   |
| 2019 | 8         | 6.72%   |
| 2012 | 8         | 6.72%   |
| 2008 | 8         | 6.72%   |
| 2018 | 6         | 5.04%   |
| 2017 | 5         | 4.2%    |
| 2022 | 4         | 3.36%   |
| 2009 | 4         | 3.36%   |
| 2013 | 3         | 2.52%   |
| 2010 | 3         | 2.52%   |
| 2023 | 2         | 1.68%   |
| 2007 | 2         | 1.68%   |
| 2024 | 1         | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 119       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 105       | 88.24%  |
| Enabled  | 14        | 11.76%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 117       | 98.32%  |
| Yes  | 2         | 1.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 49        | 40.5%   |
| 8.01-16.0  | 22        | 18.18%  |
| 16.01-24.0 | 20        | 16.53%  |
| 3.01-4.0   | 12        | 9.92%   |
| 32.01-64.0 | 11        | 9.09%   |
| 24.01-32.0 | 4         | 3.31%   |
| 2.01-3.0   | 2         | 1.65%   |
| 1.01-2.0   | 1         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 35        | 28.69%  |
| 1.01-2.0  | 33        | 27.05%  |
| 3.01-4.0  | 26        | 21.31%  |
| 4.01-8.0  | 21        | 17.21%  |
| 8.01-16.0 | 6         | 4.92%   |
| 0.51-1.0  | 1         | 0.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 86        | 71.07%  |
| 2      | 30        | 24.79%  |
| 3      | 2         | 1.65%   |
| 0      | 2         | 1.65%   |
| 4      | 1         | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 66.67%  |
| Yes       | 40        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 82.5%   |
| No        | 21        | 17.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 98.32%  |
| No        | 2         | 1.68%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 80.67%  |
| No        | 23        | 19.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 28        | 23.53%  |
| France       | 16        | 13.45%  |
| Germany      | 11        | 9.24%   |
| Canada       | 7         | 5.88%   |
| Russia       | 6         | 5.04%   |
| Italy        | 5         | 4.2%    |
| UK           | 4         | 3.36%   |
| Spain        | 4         | 3.36%   |
| Mexico       | 3         | 2.52%   |
| Brazil       | 3         | 2.52%   |
| Switzerland  | 2         | 1.68%   |
| Norway       | 2         | 1.68%   |
| Netherlands  | 2         | 1.68%   |
| Ivory Coast  | 2         | 1.68%   |
| Hungary      | 2         | 1.68%   |
| Costa Rica   | 2         | 1.68%   |
| Australia    | 2         | 1.68%   |
| Yemen        | 1         | 0.84%   |
| Turkey       | 1         | 0.84%   |
| Taiwan       | 1         | 0.84%   |
| Sweden       | 1         | 0.84%   |
| Sri Lanka    | 1         | 0.84%   |
| South Africa | 1         | 0.84%   |
| Poland       | 1         | 0.84%   |
| Peru         | 1         | 0.84%   |
| Nigeria      | 1         | 0.84%   |
| Nicaragua    | 1         | 0.84%   |
| Ireland      | 1         | 0.84%   |
| Indonesia    | 1         | 0.84%   |
| Finland      | 1         | 0.84%   |
| Denmark      | 1         | 0.84%   |
| Bulgaria     | 1         | 0.84%   |
| Belgium      | 1         | 0.84%   |
| Austria      | 1         | 0.84%   |
| Argentina    | 1         | 0.84%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Montreal      | 3         | 2.46%   |
| Toronto       | 2         | 1.64%   |
| Munich        | 2         | 1.64%   |
| Madrid        | 2         | 1.64%   |
| Hamburg       | 2         | 1.64%   |
| Groningen     | 2         | 1.64%   |
| Denver        | 2         | 1.64%   |
| Budapest      | 2         | 1.64%   |
| Béziers      | 2         | 1.64%   |
| Abidjan       | 2         | 1.64%   |
| Zele          | 1         | 0.82%   |
| Yonkers       | 1         | 0.82%   |
| Yekaterinburg | 1         | 0.82%   |
| Wroclaw       | 1         | 0.82%   |
| Woonsocket    | 1         | 0.82%   |
| Woodland Park | 1         | 0.82%   |
| Warner Robins | 1         | 0.82%   |
| Vienna        | 1         | 0.82%   |
| Viborg        | 1         | 0.82%   |
| Verdal        | 1         | 0.82%   |
| Velleron      | 1         | 0.82%   |
| Turin         | 1         | 0.82%   |
| Toulouse      | 1         | 0.82%   |
| Toluca        | 1         | 0.82%   |
| Tarragona     | 1         | 0.82%   |
| Taipei        | 1         | 0.82%   |
| Sydney        | 1         | 0.82%   |
| Sunderland    | 1         | 0.82%   |
| Stuttgart     | 1         | 0.82%   |
| Stockholm     | 1         | 0.82%   |
| Stabekk       | 1         | 0.82%   |
| St Petersburg | 1         | 0.82%   |
| Sofia         | 1         | 0.82%   |
| Sleman        | 1         | 0.82%   |
| Seropedica    | 1         | 0.82%   |
| Santo André  | 1         | 0.82%   |
| Sanaa         | 1         | 0.82%   |
| San Juan      | 1         | 0.82%   |
| San Francisco | 1         | 0.82%   |
| San Clemente  | 1         | 0.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 24        | 24     | 16.11%  |
| WDC                         | 18        | 19     | 12.08%  |
| SK hynix                    | 11        | 13     | 7.38%   |
| Seagate                     | 10        | 11     | 6.71%   |
| Toshiba                     | 8         | 8      | 5.37%   |
| SanDisk                     | 8         | 8      | 5.37%   |
| Intel                       | 6         | 11     | 4.03%   |
| Hitachi                     | 6         | 6      | 4.03%   |
| Micron Technology           | 5         | 5      | 3.36%   |
| Unknown                     | 4         | 4      | 2.68%   |
| Kingston                    | 4         | 4      | 2.68%   |
| PNY                         | 3         | 3      | 2.01%   |
| Crucial                     | 3         | 3      | 2.01%   |
| Unknown                     | 3         | 3      | 2.01%   |
| UMIS                        | 2         | 2      | 1.34%   |
| Phison                      | 2         | 2      | 1.34%   |
| KIOXIA                      | 2         | 2      | 1.34%   |
| China                       | 2         | 2      | 1.34%   |
| XrayDisk                    | 1         | 1      | 0.67%   |
| XPG                         | 1         | 1      | 0.67%   |
| Wibtek                      | 1         | 1      | 0.67%   |
| USB                         | 1         | 1      | 0.67%   |
| Union Memory                | 1         | 1      | 0.67%   |
| Team                        | 1         | 1      | 0.67%   |
| SSSTC                       | 1         | 1      | 0.67%   |
| SPCC                        | 1         | 1      | 0.67%   |
| Silicon Motion              | 1         | 1      | 0.67%   |
| Reeinno                     | 1         | 1      | 0.67%   |
| Realtek                     | 1         | 1      | 0.67%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.67%   |
| LITEONIT                    | 1         | 1      | 0.67%   |
| LITEON                      | 1         | 1      | 0.67%   |
| Lexar                       | 1         | 1      | 0.67%   |
| Kingston Technology Company | 1         | 2      | 0.67%   |
| KingSpec                    | 1         | 1      | 0.67%   |
| JMicron Technology          | 1         | 1      | 0.67%   |
| Inateck                     | 1         | 1      | 0.67%   |
| HGST                        | 1         | 1      | 0.67%   |
| Fujitsu                     | 1         | 1      | 0.67%   |
| Fanxiang                    | 1         | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 1.96%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 2         | 1.31%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 1.31%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.31%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 1.31%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 1.31%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 1.31%   |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 1.31%   |
| Samsung SSD 870 EVO 1TB                   | 2         | 1.31%   |
| Samsung SSD 860 EVO 500GB                 | 2         | 1.31%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 1.31%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 1.31%   |
| China SSD 1TB                             | 2         | 1.31%   |
| XrayDisk 1TB SSD                          | 1         | 0.65%   |
| XPG GAMMIX S7 1TB                         | 1         | 0.65%   |
| Wibtek W800S 512GB SSD                    | 1         | 0.65%   |
| WDC WDS100T2G0A-00JH30 1TB SSD            | 1         | 0.65%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 0.65%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.65%   |
| WDC WD7500BPKT-80PK4T0 752GB              | 1         | 0.65%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.65%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 0.65%   |
| WDC WD5000BEKT-60KA9T0 500GB              | 1         | 0.65%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 0.65%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 0.65%   |
| WDC WD3200BEKT-60V5T1 320GB               | 1         | 0.65%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 0.65%   |
| WDC WD10JPVT-75A1YT0 1TB                  | 1         | 0.65%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB      | 1         | 0.65%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB      | 1         | 0.65%   |
| USB SanDisk 3.2Gen1 250GB                 | 1         | 0.65%   |
| Unknown MMC Card  4GB                     | 1         | 0.65%   |
| Unknown MMC Card  16GB                    | 1         | 0.65%   |
| Unknown DA4128  128GB                     | 1         | 0.65%   |
| Unknown 032G34  32GB                      | 1         | 0.65%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB   | 1         | 0.65%   |
| UMIS RPJTJ256MEE1OWX 256GB                | 1         | 0.65%   |
| UMIS RPITJ512VME2OWD 512GB                | 1         | 0.65%   |
| Toshiba TR150 240GB SSD                   | 1         | 0.65%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 12     | 26.83%  |
| Seagate             | 9         | 9      | 21.95%  |
| Toshiba             | 7         | 7      | 17.07%  |
| Hitachi             | 6         | 6      | 14.63%  |
| Samsung Electronics | 2         | 2      | 4.88%   |
| JMicron Technology  | 1         | 1      | 2.44%   |
| Inateck             | 1         | 1      | 2.44%   |
| HGST                | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 1      | 2.44%   |
| External            | 1         | 1      | 2.44%   |
| ASMT                | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 12     | 24.49%  |
| SanDisk             | 5         | 5      | 10.2%   |
| SK hynix            | 4         | 5      | 8.16%   |
| PNY                 | 3         | 3      | 6.12%   |
| Kingston            | 3         | 3      | 6.12%   |
| WDC                 | 2         | 2      | 4.08%   |
| Micron Technology   | 2         | 2      | 4.08%   |
| Crucial             | 2         | 2      | 4.08%   |
| China               | 2         | 2      | 4.08%   |
| XrayDisk            | 1         | 1      | 2.04%   |
| Wibtek              | 1         | 1      | 2.04%   |
| Toshiba             | 1         | 1      | 2.04%   |
| SPCC                | 1         | 1      | 2.04%   |
| Reeinno             | 1         | 1      | 2.04%   |
| LITEONIT            | 1         | 1      | 2.04%   |
| LITEON              | 1         | 1      | 2.04%   |
| Lexar               | 1         | 1      | 2.04%   |
| KingSpec            | 1         | 1      | 2.04%   |
| Intel               | 1         | 1      | 2.04%   |
| Fanxiang            | 1         | 1      | 2.04%   |
| Dogfish             | 1         | 1      | 2.04%   |
| BHT                 | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 44        | 58     | 32.59%  |
| SSD     | 43        | 50     | 31.85%  |
| HDD     | 39        | 42     | 28.89%  |
| MMC     | 8         | 9      | 5.93%   |
| Unknown | 1         | 1      | 0.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 76        | 87     | 56.3%   |
| NVMe | 44        | 57     | 32.59%  |
| MMC  | 8         | 9      | 5.93%   |
| SAS  | 7         | 7      | 5.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 59        | 64     | 69.41%  |
| 0.51-1.0   | 24        | 26     | 28.24%  |
| 10.01-20.0 | 1         | 1      | 1.18%   |
| 1.01-2.0   | 1         | 1      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 36        | 29.27%  |
| 251-500    | 34        | 27.64%  |
| 501-1000   | 20        | 16.26%  |
| 1001-2000  | 11        | 8.94%   |
| 51-100     | 9         | 7.32%   |
| 21-50      | 8         | 6.5%    |
| 1-20       | 4         | 3.25%   |
| 2001-3000  | 1         | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 41        | 33.61%  |
| 21-50     | 25        | 20.49%  |
| 101-250   | 19        | 15.57%  |
| 251-500   | 13        | 10.66%  |
| 51-100    | 13        | 10.66%  |
| 501-1000  | 9         | 7.38%   |
| 1001-2000 | 2         | 1.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 4.35%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 4.35%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 4.35%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 4.35%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 4.35%   |
| UMIS RPITJ512VME2OWD 512GB                          | 1         | 1      | 4.35%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 4.35%   |
| SSSTC CL1-4D512 512GB                               | 1         | 1      | 4.35%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 1         | 2      | 4.35%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 4.35%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 4.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 4.35%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 4.35%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 4.35%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 4.35%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 4.35%   |
| KingSpec P3-256 256GB                               | 1         | 1      | 4.35%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 4.35%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 4.35%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 4.35%   |
| Hitachi HTS547564A9E384 640GB                       | 1         | 1      | 4.35%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 21.74%  |
| Seagate             | 4         | 4      | 17.39%  |
| Hitachi             | 4         | 4      | 17.39%  |
| Samsung Electronics | 3         | 3      | 13.04%  |
| UMIS                | 1         | 1      | 4.35%   |
| Toshiba             | 1         | 1      | 4.35%   |
| SSSTC               | 1         | 1      | 4.35%   |
| SK hynix            | 1         | 2      | 4.35%   |
| Micron Technology   | 1         | 1      | 4.35%   |
| KingSpec            | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 31.25%  |
| Seagate             | 4         | 4      | 25%     |
| Hitachi             | 4         | 4      | 25%     |
| Samsung Electronics | 2         | 2      | 12.5%   |
| Toshiba             | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 69.57%  |
| SSD  | 5         | 6      | 21.74%  |
| NVMe | 2         | 2      | 8.7%    |

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
| Works    | 92        | 121    | 72.44%  |
| Malfunc  | 23        | 24     | 18.11%  |
| Detected | 12        | 15     | 9.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 82        | 56.16%  |
| AMD                            | 20        | 13.7%   |
| Samsung Electronics            | 11        | 7.53%   |
| SK hynix                       | 7         | 4.79%   |
| SanDisk                        | 6         | 4.11%   |
| Union Memory (Shenzhen)        | 3         | 2.05%   |
| Phison Electronics             | 3         | 2.05%   |
| Micron Technology              | 3         | 2.05%   |
| Kingston Technology Company    | 2         | 1.37%   |
| Toshiba America Info Systems   | 1         | 0.68%   |
| Solid State Storage Technology | 1         | 0.68%   |
| Silicon Motion                 | 1         | 0.68%   |
| Seagate Technology             | 1         | 0.68%   |
| Realtek Semiconductor          | 1         | 0.68%   |
| Micron/Crucial Technology      | 1         | 0.68%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.68%   |
| KIOXIA                         | 1         | 0.68%   |
| ADATA Technology               | 1         | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18        | 11.61%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 6.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 5.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 5.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 5.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 5.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 3.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.58%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3         | 1.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.94%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 2         | 1.29%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 1.29%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 1.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.29%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 1.29%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.29%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.29%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 1.29%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 1.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.29%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.29%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                          | 1         | 0.65%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.65%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.65%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 0.65%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.65%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 1         | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 0.65%   |
| Seagate E18 PCIe SSD                                                           | 1         | 0.65%   |
| Sandisk WD PC SN5000S M.2 2280 NVMe SSD (DRAM-less)                            | 1         | 0.65%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.65%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 87        | 58.78%  |
| NVMe | 44        | 29.73%  |
| RAID | 12        | 8.11%   |
| IDE  | 5         | 3.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 92        | 77.31%  |
| AMD    | 27        | 22.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics | 4         | 3.36%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 3         | 2.52%   |
| Intel Core i7-5600U CPU @ 2.60GHz      | 3         | 2.52%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 3         | 2.52%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 3         | 2.52%   |
| Intel Core i5-2450M CPU @ 2.50GHz      | 3         | 2.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 1.68%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 2         | 1.68%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 2         | 1.68%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 2         | 1.68%   |
| Intel Core i7-2630QM CPU @ 2.00GHz     | 2         | 1.68%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz      | 2         | 1.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 2         | 1.68%   |
| Intel Core i5-10300H CPU @ 2.50GHz     | 2         | 1.68%   |
| Intel Core i3-5005U CPU @ 2.00GHz      | 2         | 1.68%   |
| Intel Celeron N4000 CPU @ 1.10GHz      | 2         | 1.68%   |
| AMD Ryzen 7 5825U with Radeon Graphics | 2         | 1.68%   |
| AMD Ryzen 5 5500U with Radeon Graphics | 2         | 1.68%   |
| Intel Processor 5Y10 CPU @ 0.80GHz     | 1         | 0.84%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 0.84%   |
| Intel Pentium CPU 5405U @ 2.30GHz      | 1         | 0.84%   |
| Intel Genuine CPU U2300 @ 1.20GHz      | 1         | 0.84%   |
| Intel Core Ultra 9 288V                | 1         | 0.84%   |
| Intel Core i9-8950HK CPU @ 2.90GHz     | 1         | 0.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz      | 1         | 0.84%   |
| Intel Core i7-8850H CPU @ 2.60GHz      | 1         | 0.84%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 0.84%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 0.84%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 0.84%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz     | 1         | 0.84%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz     | 1         | 0.84%   |
| Intel Core i7-3940XM CPU @ 3.00GHz     | 1         | 0.84%   |
| Intel Core i7-3630QM CPU @ 2.40GHz     | 1         | 0.84%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 1         | 0.84%   |
| Intel Core i7-2640M CPU @ 2.80GHz      | 1         | 0.84%   |
| Intel Core i7-2635QM CPU @ 2.00GHz     | 1         | 0.84%   |
| Intel Core i7-10850H CPU @ 2.70GHz     | 1         | 0.84%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz      | 1         | 0.84%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 1         | 0.84%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 1         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 35        | 29.41%  |
| Intel Core i5      | 28        | 23.53%  |
| Other              | 8         | 6.72%   |
| AMD Ryzen 7        | 7         | 5.88%   |
| AMD Ryzen 5        | 7         | 5.88%   |
| Intel Core i3      | 6         | 5.04%   |
| Intel Celeron      | 6         | 5.04%   |
| Intel Core 2 Duo   | 5         | 4.2%    |
| AMD Ryzen 3        | 2         | 1.68%   |
| AMD E              | 2         | 1.68%   |
| AMD A8             | 2         | 1.68%   |
| Intel Pentium Dual | 1         | 0.84%   |
| Intel Pentium      | 1         | 0.84%   |
| Intel Genuine      | 1         | 0.84%   |
| Intel Core i9      | 1         | 0.84%   |
| Intel Core         | 1         | 0.84%   |
| AMD Ryzen 5 PRO    | 1         | 0.84%   |
| AMD Ryzen 3 PRO    | 1         | 0.84%   |
| AMD E2             | 1         | 0.84%   |
| AMD E1             | 1         | 0.84%   |
| AMD A6             | 1         | 0.84%   |
| AMD A4             | 1         | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 59        | 49.58%  |
| 4      | 36        | 30.25%  |
| 6      | 14        | 11.76%  |
| 8      | 8         | 6.72%   |
| 12     | 1         | 0.84%   |
| 10     | 1         | 0.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 119       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 92        | 77.31%  |
| 1      | 27        | 22.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 119       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 33.88%  |
| 0x206a7    | 7         | 5.79%   |
| 0x306d4    | 6         | 4.96%   |
| 0x306a9    | 6         | 4.96%   |
| 0x08600104 | 5         | 4.13%   |
| 0x906ea    | 4         | 3.31%   |
| 0xa0652    | 3         | 2.48%   |
| 0x806ea    | 3         | 2.48%   |
| 0x706e5    | 3         | 2.48%   |
| 0x406e3    | 3         | 2.48%   |
| 0x40651    | 3         | 2.48%   |
| 0x0a50000c | 3         | 2.48%   |
| 0x906e9    | 2         | 1.65%   |
| 0x806c1    | 2         | 1.65%   |
| 0x6fd      | 2         | 1.65%   |
| 0x106e5    | 2         | 1.65%   |
| 0x08600106 | 2         | 1.65%   |
| 0x08108109 | 2         | 1.65%   |
| 0x07030105 | 2         | 1.65%   |
| 0x806ec    | 1         | 0.83%   |
| 0x706a1    | 1         | 0.83%   |
| 0x6fb      | 1         | 0.83%   |
| 0x506e3    | 1         | 0.83%   |
| 0x506c9    | 1         | 0.83%   |
| 0x406c4    | 1         | 0.83%   |
| 0x40661    | 1         | 0.83%   |
| 0x306c3    | 1         | 0.83%   |
| 0x1067a    | 1         | 0.83%   |
| 0x10676    | 1         | 0.83%   |
| 0x0a704101 | 1         | 0.83%   |
| 0x08608103 | 1         | 0.83%   |
| 0x08608102 | 1         | 0.83%   |
| 0x08600103 | 1         | 0.83%   |
| 0x07030106 | 1         | 0.83%   |
| 0x07030104 | 1         | 0.83%   |
| 0x06006110 | 1         | 0.83%   |
| 0x0500010d | 1         | 0.83%   |
| 0x05000029 | 1         | 0.83%   |
| 0x03000027 | 1         | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 15        | 12.61%  |
| SandyBridge      | 11        | 9.24%   |
| Skylake          | 10        | 8.4%    |
| Haswell          | 10        | 8.4%    |
| Zen 2            | 9         | 7.56%   |
| Broadwell        | 9         | 7.56%   |
| IvyBridge        | 7         | 5.88%   |
| Puma             | 4         | 3.36%   |
| Penryn           | 4         | 3.36%   |
| IceLake          | 4         | 3.36%   |
| Zen+             | 3         | 2.52%   |
| Zen 3            | 3         | 2.52%   |
| TigerLake        | 3         | 2.52%   |
| Nehalem          | 3         | 2.52%   |
| Core             | 3         | 2.52%   |
| CometLake        | 3         | 2.52%   |
| Alderlake Hybrid | 3         | 2.52%   |
| Unknown          | 3         | 2.52%   |
| Westmere         | 2         | 1.68%   |
| K10 Llano        | 2         | 1.68%   |
| Goldmont plus    | 2         | 1.68%   |
| Bobcat           | 2         | 1.68%   |
| Silvermont       | 1         | 0.84%   |
| Lunarlake Hybrid | 1         | 0.84%   |
| Goldmont         | 1         | 0.84%   |
| Excavator        | 1         | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 84        | 56%     |
| AMD    | 34        | 22.67%  |
| Nvidia | 32        | 21.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 11        | 7.14%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 9         | 5.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 8         | 5.19%   |
| Intel HD Graphics 5500                                                    | 7         | 4.55%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 3.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 3.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 5         | 3.25%   |
| Intel UHD Graphics 620                                                    | 4         | 2.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 2.6%    |
| Intel Iris Plus Graphics G7                                               | 3         | 1.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 1.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 1.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 1.95%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.3%    |
| Nvidia GK208BM [GeForce 920M]                                             | 2         | 1.3%    |
| Nvidia GF108M [GeForce GT 525M]                                           | 2         | 1.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.3%    |
| Intel HD Graphics 630                                                     | 2         | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.3%    |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.3%    |
| AMD Wrestler [Radeon HD 6310]                                             | 2         | 1.3%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 1.3%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.3%    |
| AMD Lucienne                                                              | 2         | 1.3%    |
| AMD Barcelo                                                               | 2         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.65%   |
| Nvidia GT216M [GeForce GT 230M]                                           | 1         | 0.65%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.65%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 0.65%   |
| Nvidia GP104GLM [Quadro P5200 Mobile]                                     | 1         | 0.65%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 0.65%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                     | 1         | 0.65%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.65%   |
| Nvidia GK107M [GeForce GTX 660M]                                          | 1         | 0.65%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 1         | 0.65%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 59        | 49.58%  |
| Intel + Nvidia | 22        | 18.49%  |
| 1 x AMD        | 22        | 18.49%  |
| AMD + Nvidia   | 6         | 5.04%   |
| 1 x Nvidia     | 4         | 3.36%   |
| 2 x AMD        | 3         | 2.52%   |
| Intel + AMD    | 3         | 2.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 107       | 89.92%  |
| Proprietary | 10        | 8.4%    |
| Unknown     | 2         | 1.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 57.98%  |
| 0.01-0.5   | 16        | 13.45%  |
| 0.51-1.0   | 14        | 11.76%  |
| 1.01-2.0   | 8         | 6.72%   |
| 3.01-4.0   | 7         | 5.88%   |
| 5.01-6.0   | 4         | 3.36%   |
| 8.01-16.0  | 1         | 0.84%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 20.14%  |
| LG Display              | 22        | 15.83%  |
| BOE                     | 19        | 13.67%  |
| Chimei Innolux          | 17        | 12.23%  |
| Samsung Electronics     | 16        | 11.51%  |
| Lenovo                  | 4         | 2.88%   |
| Apple                   | 4         | 2.88%   |
| Sharp                   | 3         | 2.16%   |
| Hewlett-Packard         | 3         | 2.16%   |
| Goldstar                | 3         | 2.16%   |
| Dell                    | 3         | 2.16%   |
| BenQ                    | 3         | 2.16%   |
| Chi Mei Optoelectronics | 2         | 1.44%   |
| ASUSTek Computer        | 2         | 1.44%   |
| Ancor Communications    | 2         | 1.44%   |
| Philips                 | 1         | 0.72%   |
| LG Philips              | 1         | 0.72%   |
| Iiyama                  | 1         | 0.72%   |
| HannStar                | 1         | 0.72%   |
| Hannspree               | 1         | 0.72%   |
| CPT                     | 1         | 0.72%   |
| Arnos Instruments       | 1         | 0.72%   |
| Acer                    | 1         | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.13%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 2         | 1.42%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 1.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.42%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.42%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 1.42%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 1.42%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.42%   |
| AU Optronics LCD Monitor AUO229E 1600x900 382x214mm 17.2-inch         | 2         | 1.42%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 2         | 1.42%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC41A8 2880x1800 286x179mm 13.3-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch | 1         | 0.71%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 0.71%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.71%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD04F0 2560x1440 310x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 63        | 50%     |
| 1366x768 (WXGA)    | 35        | 27.78%  |
| 3840x2160 (4K)     | 6         | 4.76%   |
| 1600x900 (HD+)     | 5         | 3.97%   |
| 1920x1200 (WUXGA)  | 3         | 2.38%   |
| 1680x1050 (WSXGA+) | 3         | 2.38%   |
| 1280x800 (WXGA)    | 3         | 2.38%   |
| 2880x1800          | 2         | 1.59%   |
| 2560x1440 (QHD)    | 2         | 1.59%   |
| 3440x1440          | 1         | 0.79%   |
| 2560x1600          | 1         | 0.79%   |
| 2160x1440          | 1         | 0.79%   |
| 1440x900 (WXGA+)   | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 61        | 43.88%  |
| 13     | 21        | 15.11%  |
| 14     | 12        | 8.63%   |
| 17     | 9         | 6.47%   |
| 24     | 7         | 5.04%   |
| 12     | 5         | 3.6%    |
| 27     | 4         | 2.88%   |
| 21     | 4         | 2.88%   |
| 16     | 3         | 2.16%   |
| 31     | 2         | 1.44%   |
| 23     | 2         | 1.44%   |
| 19     | 2         | 1.44%   |
| 18     | 2         | 1.44%   |
| 84     | 1         | 0.72%   |
| 40     | 1         | 0.72%   |
| 34     | 1         | 0.72%   |
| 22     | 1         | 0.72%   |
| 20     | 1         | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 82        | 59.85%  |
| 201-300     | 16        | 11.68%  |
| 351-400     | 13        | 9.49%   |
| 501-600     | 11        | 8.03%   |
| 401-500     | 10        | 7.3%    |
| 601-700     | 2         | 1.46%   |
| 801-900     | 1         | 0.73%   |
| 701-800     | 1         | 0.73%   |
| 1501-2000   | 1         | 0.73%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 104       | 85.25%  |
| 16/10 | 16        | 13.11%  |
| 3/2   | 1         | 0.82%   |
| 21/9  | 1         | 0.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 62        | 45.26%  |
| 81-90          | 25        | 18.25%  |
| 71-80          | 8         | 5.84%   |
| 201-250        | 8         | 5.84%   |
| 121-130        | 8         | 5.84%   |
| 61-70          | 5         | 3.65%   |
| 301-350        | 4         | 2.92%   |
| 151-200        | 4         | 2.92%   |
| 351-500        | 3         | 2.19%   |
| 251-300        | 3         | 2.19%   |
| 141-150        | 2         | 1.46%   |
| 111-120        | 2         | 1.46%   |
| More than 1000 | 1         | 0.73%   |
| 131-140        | 1         | 0.73%   |
| 501-1000       | 1         | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 60        | 44.44%  |
| 101-120       | 39        | 28.89%  |
| 51-100        | 21        | 15.56%  |
| 161-240       | 13        | 9.63%   |
| More than 240 | 2         | 1.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 100       | 82.64%  |
| 2     | 18        | 14.88%  |
| 3     | 3         | 2.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 74        | 38.34%  |
| Realtek Semiconductor             | 63        | 32.64%  |
| Qualcomm Atheros                  | 19        | 9.84%   |
| Broadcom                          | 8         | 4.15%   |
| Ralink                            | 4         | 2.07%   |
| MediaTek                          | 4         | 2.07%   |
| ASIX Electronics                  | 3         | 1.55%   |
| Lenovo                            | 2         | 1.04%   |
| Ericsson Business Mobile Networks | 2         | 1.04%   |
| Broadcom Limited                  | 2         | 1.04%   |
| Xiaomi                            | 1         | 0.52%   |
| Sierra Wireless                   | 1         | 0.52%   |
| Samsung Electronics               | 1         | 0.52%   |
| Ralink Technology                 | 1         | 0.52%   |
| Motorola PCS                      | 1         | 0.52%   |
| Marvell Technology Group          | 1         | 0.52%   |
| ICS Advent                        | 1         | 0.52%   |
| Huawei Technologies               | 1         | 0.52%   |
| Hewlett-Packard                   | 1         | 0.52%   |
| Google                            | 1         | 0.52%   |
| DisplayLink                       | 1         | 0.52%   |
| Dell                              | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 38        | 15.97%  |
| Intel Wireless 7265                                                    | 10        | 4.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 3.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 3.36%   |
| Intel Wireless 8260                                                    | 7         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 7         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 2.52%   |
| Intel Wi-Fi 6 AX200                                                    | 6         | 2.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 2.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 2.1%    |
| Intel Wireless 7260                                                    | 5         | 2.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 2.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 1.68%   |
| Intel Wireless 8265 / 8275                                             | 4         | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 1.26%   |
| Intel WiFi Link 5100                                                   | 3         | 1.26%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.26%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.26%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 1.26%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 1.26%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 0.84%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.84%   |
| Realtek 802.11ac NIC                                                   | 2         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.84%   |
| Intel Wireless 3160                                                    | 2         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.84%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.84%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.84%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 0.84%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module     | 2         | 0.84%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.84%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 2         | 0.84%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 2         | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 71        | 59.17%  |
| Realtek Semiconductor | 17        | 14.17%  |
| Qualcomm Atheros      | 15        | 12.5%   |
| Broadcom              | 6         | 5%      |
| Ralink                | 4         | 3.33%   |
| MediaTek              | 3         | 2.5%    |
| Broadcom Limited      | 2         | 1.67%   |
| Sierra Wireless       | 1         | 0.83%   |
| Ralink Technology     | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 10        | 8.26%   |
| Intel Wireless 8260                                              | 7         | 5.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 7         | 5.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 6         | 4.96%   |
| Intel Wi-Fi 6 AX200                                              | 6         | 4.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 5         | 4.13%   |
| Intel Wireless 7260                                              | 5         | 4.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 5         | 4.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 4         | 3.31%   |
| Intel Wireless 8265 / 8275                                       | 4         | 3.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 3         | 2.48%   |
| Intel WiFi Link 5100                                             | 3         | 2.48%   |
| Intel Wi-Fi 6 AX201                                              | 3         | 2.48%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 2.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 2         | 1.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 1.65%   |
| Realtek 802.11ac NIC                                             | 2         | 1.65%   |
| Intel Wireless 3160                                              | 2         | 1.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 2         | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 2         | 1.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                 | 2         | 1.65%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                      | 2         | 1.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                   | 2         | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 1.65%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                    | 1         | 0.83%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller      | 1         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 1         | 0.83%   |
| Realtek RTL8191SEvB Wireless LAN Controller                      | 1         | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                            | 1         | 0.83%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 0.83%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                        | 1         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                        | 1         | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 1         | 0.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter    | 1         | 0.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                          | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 52        | 47.27%  |
| Intel                    | 34        | 30.91%  |
| Qualcomm Atheros         | 7         | 6.36%   |
| Broadcom                 | 4         | 3.64%   |
| ASIX Electronics         | 3         | 2.73%   |
| Lenovo                   | 2         | 1.82%   |
| Xiaomi                   | 1         | 0.91%   |
| Samsung Electronics      | 1         | 0.91%   |
| Motorola PCS             | 1         | 0.91%   |
| MediaTek                 | 1         | 0.91%   |
| Marvell Technology Group | 1         | 0.91%   |
| ICS Advent               | 1         | 0.91%   |
| Hewlett-Packard          | 1         | 0.91%   |
| DisplayLink              | 1         | 0.91%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 38        | 33.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 8.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 7.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 4.46%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 2.68%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 2.68%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 2.68%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 1.79%   |
| Intel Ethernet Connection I219-V                                       | 2         | 1.79%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.79%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.79%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.89%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.89%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.89%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.89%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.89%   |
| Motorola PCS moto g play - 2023                                        | 1         | 0.89%   |
| MediaTek Infinix SMART 5                                               | 1         | 0.89%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.89%   |
| Lenovo ThinkPad Lan                                                    | 1         | 0.89%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]            | 1         | 0.89%   |
| Intel Wi-Fi 6E AX231 160MHz                                            | 1         | 0.89%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.89%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.89%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 0.89%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.89%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 0.89%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 0.89%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.89%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 0.89%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 1         | 0.89%   |
| HP HP lt4120 Snapdragon X5 LTE                                         | 1         | 0.89%   |
| DisplayLink HP Port Replicator (Composite Device)                      | 1         | 0.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 117       | 52.94%  |
| Ethernet | 99        | 44.8%   |
| Modem    | 5         | 2.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 77.69%  |
| Ethernet | 29        | 22.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 91        | 76.47%  |
| 1     | 26        | 21.85%  |
| 3     | 1         | 0.84%   |
| 0     | 1         | 0.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 69.17%  |
| Yes  | 37        | 30.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 53.61%  |
| Realtek Semiconductor           | 8         | 8.25%   |
| Qualcomm Atheros Communications | 6         | 6.19%   |
| Broadcom                        | 6         | 6.19%   |
| IMC Networks                    | 4         | 4.12%   |
| Apple                           | 4         | 4.12%   |
| Realtek                         | 2         | 2.06%   |
| Ralink Technology               | 2         | 2.06%   |
| Lite-On Technology              | 2         | 2.06%   |
| Hewlett-Packard                 | 2         | 2.06%   |
| Foxconn / Hon Hai               | 2         | 2.06%   |
| Dell                            | 2         | 2.06%   |
| Ralink                          | 1         | 1.03%   |
| MediaTek                        | 1         | 1.03%   |
| Foxconn International           | 1         | 1.03%   |
| Cambridge Silicon Radio         | 1         | 1.03%   |
| ASUSTek Computer                | 1         | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 27        | 27.84%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 8.25%   |
| Intel AX201 Bluetooth                               | 6         | 6.19%   |
| Intel AX200 Bluetooth                               | 6         | 6.19%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 4.12%   |
| Realtek Bluetooth Radio                             | 3         | 3.09%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 3.09%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.09%   |
| Apple Bluetooth Host Controller                     | 3         | 3.09%   |
| Realtek Bluetooth Radio                             | 2         | 2.06%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.06%   |
| Intel AX211 Bluetooth                               | 2         | 2.06%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.03%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.03%   |
| Ralink CSR BS8510                                   | 1         | 1.03%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.03%   |
| MediaTek Wireless_Device                            | 1         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.03%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.03%   |
| Intel Bluetooth Device                              | 1         | 1.03%   |
| IMC Networks Wireless_Device                        | 1         | 1.03%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.03%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.03%   |
| IMC Networks Bluetooth Device                       | 1         | 1.03%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.03%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.03%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.03%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.03%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 1.03%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.03%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.03%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.03%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.03%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 92        | 55.42%  |
| AMD                                  | 31        | 18.67%  |
| Nvidia                               | 25        | 15.06%  |
| Mackie Designs                       | 2         | 1.2%    |
| C-Media Electronics                  | 2         | 1.2%    |
| Yealink Network Technology           | 1         | 0.6%    |
| Yamaha                               | 1         | 0.6%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.6%    |
| Realtek Semiconductor                | 1         | 0.6%    |
| QinHeng Electronics                  | 1         | 0.6%    |
| Plantronics                          | 1         | 0.6%    |
| Logitech                             | 1         | 0.6%    |
| Lenovo                               | 1         | 0.6%    |
| Jieli Technology                     | 1         | 0.6%    |
| Focusrite-Novation                   | 1         | 0.6%    |
| Dell                                 | 1         | 0.6%    |
| Behringer.......                     | 1         | 0.6%    |
| BEHRINGER International              | 1         | 0.6%    |
| ASUSTek Computer                     | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 17        | 8.25%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 5.83%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 4.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 4.37%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 4.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 4.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 4.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 2.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.91%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 2.91%   |
| AMD FCH Azalia Controller                                                  | 6         | 2.91%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.43%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 2.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.46%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.46%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.46%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.46%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.97%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 0.97%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.97%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 2         | 0.97%   |
| Yealink Network Technology VoIP Phone                                      | 1         | 0.49%   |
| Yamaha Steinberg UR242                                                     | 1         | 0.49%   |
| Thesycon Systemsoftware & Consulting Audio Interface                       | 1         | 0.49%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.49%   |
| QinHeng Electronics CH345 MIDI adapter                                     | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 47        | 32.64%  |
| SK hynix            | 38        | 26.39%  |
| Micron Technology   | 18        | 12.5%   |
| Kingston            | 15        | 10.42%  |
| Unknown             | 4         | 2.78%   |
| Ramaxel Technology  | 4         | 2.78%   |
| Crucial             | 4         | 2.78%   |
| Transcend           | 2         | 1.39%   |
| Timetec             | 2         | 1.39%   |
| Nanya Technology    | 2         | 1.39%   |
| Elpida              | 2         | 1.39%   |
| Patriot             | 1         | 0.69%   |
| G.Skill             | 1         | 0.69%   |
| CSX                 | 1         | 0.69%   |
| Corsair             | 1         | 0.69%   |
| A-DATA Technology   | 1         | 0.69%   |
| Unknown             | 1         | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 6         | 3.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 4         | 2.6%    |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s      | 4         | 2.6%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s              | 3         | 1.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 3         | 1.95%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s    | 3         | 1.95%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 3         | 1.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.3%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.3%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 2         | 1.3%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 2         | 1.3%    |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s    | 2         | 1.3%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s     | 2         | 1.3%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 1.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 1.3%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s    | 2         | 1.3%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 2         | 1.3%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 2         | 1.3%    |
| Unknown RAM Module 4GB SODIMM DDR3                        | 1         | 0.65%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s          | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 1         | 0.65%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s        | 1         | 0.65%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s     | 1         | 0.65%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.65%   |
| Timetec RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 0.65%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 0.65%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s           | 1         | 0.65%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s     | 1         | 0.65%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 0.65%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 1         | 0.65%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 1         | 0.65%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s    | 1         | 0.65%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s | 1         | 0.65%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s     | 1         | 0.65%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s   | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 56        | 45.9%   |
| DDR4   | 51        | 41.8%   |
| DDR2   | 5         | 4.1%    |
| SDRAM  | 3         | 2.46%   |
| LPDDR5 | 2         | 1.64%   |
| LPDDR4 | 2         | 1.64%   |
| LPDDR3 | 2         | 1.64%   |
| DDR5   | 1         | 0.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 107       | 87.7%   |
| Row Of Chips | 11        | 9.02%   |
| Chip         | 2         | 1.64%   |
| Unknown      | 2         | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 60        | 42.55%  |
| 4096  | 47        | 33.33%  |
| 16384 | 15        | 10.64%  |
| 2048  | 13        | 9.22%   |
| 32768 | 3         | 2.13%   |
| 1024  | 3         | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 39        | 30.23%  |
| 3200    | 21        | 16.28%  |
| 2667    | 21        | 16.28%  |
| 1334    | 11        | 8.53%   |
| 2400    | 9         | 6.98%   |
| 2133    | 7         | 5.43%   |
| 1333    | 5         | 3.88%   |
| 667     | 3         | 2.33%   |
| 4267    | 2         | 1.55%   |
| 4199    | 2         | 1.55%   |
| Unknown | 2         | 1.55%   |
| 8533    | 1         | 0.78%   |
| 6400    | 1         | 0.78%   |
| 5600    | 1         | 0.78%   |
| 1867    | 1         | 0.78%   |
| 1639    | 1         | 0.78%   |
| 1067    | 1         | 0.78%   |
| 800     | 1         | 0.78%   |

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
| Chicony Electronics                    | 26        | 24.3%   |
| IMC Networks                           | 10        | 9.35%   |
| Realtek Semiconductor                  | 8         | 7.48%   |
| Suyin                                  | 7         | 6.54%   |
| Bison Electronics                      | 7         | 6.54%   |
| Sunplus Innovation Technology          | 6         | 5.61%   |
| Lite-On Technology                     | 6         | 5.61%   |
| Syntek                                 | 5         | 4.67%   |
| Quanta                                 | 5         | 4.67%   |
| Microdia                               | 5         | 4.67%   |
| Sonix Technology                       | 3         | 2.8%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.8%    |
| Ricoh                                  | 2         | 1.87%   |
| Apple                                  | 2         | 1.87%   |
| ViewQuest Technologies                 | 1         | 0.93%   |
| Silicon Motion                         | 1         | 0.93%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.93%   |
| Razer USA                              | 1         | 0.93%   |
| Philips (or NXP)                       | 1         | 0.93%   |
| Microsoft                              | 1         | 0.93%   |
| Luxvisions Innotech Limited            | 1         | 0.93%   |
| Logitech                               | 1         | 0.93%   |
| Importek                               | 1         | 0.93%   |
| HRY                                    | 1         | 0.93%   |
| Dell                                   | 1         | 0.93%   |
| Acer                                   | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Chicony integrated camera                       | 7         | 6.48%   |
| Syntek Integrated Camera                        | 5         | 4.63%   |
| IMC Networks Integrated Camera                  | 4         | 3.7%    |
| Bison Integrated Camera                         | 4         | 3.7%    |
| Sunplus Integrated_Webcam_HD                    | 3         | 2.78%   |
| Sonix USB2.0 HD UVC WebCam                      | 3         | 2.78%   |
| Realtek Lenovo EasyCamera                       | 3         | 2.78%   |
| Microdia Integrated_Webcam_HD                   | 3         | 2.78%   |
| Lite-On Integrated Camera                       | 3         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam               | 3         | 2.78%   |
| Chicony Integrated Camera [ThinkPad]            | 3         | 2.78%   |
| Chicony HD Webcam                               | 3         | 2.78%   |
| Chicony HD User Facing                          | 3         | 2.78%   |
| Suyin USB 2.0 Camera                            | 2         | 1.85%   |
| Suyin Asus Integrated Webcam                    | 2         | 1.85%   |
| Sunplus HD WebCam                               | 2         | 1.85%   |
| Lite-On HP HD Webcam                            | 2         | 1.85%   |
| Chicony HP HD Camera                            | 2         | 1.85%   |
| Apple FaceTime HD Camera                        | 2         | 1.85%   |
| ViewQuest Ability GABB Webcam                   | 1         | 0.93%   |
| Suyin HP Webcam                                 | 1         | 0.93%   |
| Suyin HP TrueVision HD Integrated Webcam        | 1         | 0.93%   |
| Suyin HP TrueVision HD                          | 1         | 0.93%   |
| Sunplus Dell HD Webcam                          | 1         | 0.93%   |
| Silicon Motion WebCam SCB-1100N                 | 1         | 0.93%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera | 1         | 0.93%   |
| Ricoh USB2.0 Camera                             | 1         | 0.93%   |
| Ricoh Sony Vaio Integrated Webcam               | 1         | 0.93%   |
| Realtek VGA WebCam                              | 1         | 0.93%   |
| Realtek Integrated_Webcam_HD                    | 1         | 0.93%   |
| Realtek HP Wide Vision HD Camera                | 1         | 0.93%   |
| Realtek HP "Truevision HD" laptop camera        | 1         | 0.93%   |
| Realtek Acer 640 x 480 laptop camera            | 1         | 0.93%   |
| Razer USA Gaming Webcam [Kiyo]                  | 1         | 0.93%   |
| Quanta ov9734_techfront_camera                  | 1         | 0.93%   |
| Quanta Laptop_Integrated_Webcam_2HDM            | 1         | 0.93%   |
| Quanta HP Webcam                                | 1         | 0.93%   |
| Quanta HP TrueVision HD Camera                  | 1         | 0.93%   |
| Quanta HP HD Camera                             | 1         | 0.93%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc]      | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 54.17%  |
| Synaptics                  | 4         | 16.67%  |
| Shenzhen Goodix Technology | 3         | 12.5%   |
| Samsung Electronics        | 1         | 4.17%   |
| LighTuning Technology      | 1         | 4.17%   |
| Focal-systems.Corp         | 1         | 4.17%   |
| AuthenTec                  | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 4         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader        | 3         | 12.5%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 2         | 8.33%   |
| Validity Sensors Fingerprint scanner              | 2         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 2         | 8.33%   |
| Shenzhen Goodix  Fingerprint Device               | 2         | 8.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 4.17%   |
| Validity Sensors VFS301 Fingerprint Reader        | 1         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 4.17%   |
| Synaptics Fingerprint reader [HP G6]              | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 4.17%   |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 4.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 4.17%   |
| Focal-systems.Corp FT9201Fingerprint.Ì         | 1         | 4.17%   |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 4.17%   |

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
| 0     | 70        | 58.82%  |
| 1     | 41        | 34.45%  |
| 2     | 7         | 5.88%   |
| 3     | 1         | 0.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 43.64%  |
| Chipcard                 | 10        | 18.18%  |
| Graphics card            | 8         | 14.55%  |
| Net/wireless             | 3         | 5.45%   |
| Multimedia controller    | 3         | 5.45%   |
| Card reader              | 2         | 3.64%   |
| Camera                   | 2         | 3.64%   |
| Storage                  | 1         | 1.82%   |
| Communication controller | 1         | 1.82%   |
| Bluetooth                | 1         | 1.82%   |

