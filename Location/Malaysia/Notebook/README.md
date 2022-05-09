Linux in Malaysia - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Malaysia.

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

Total: 234

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T480 20L6S1RN00    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Acer          | Aspire 4349                 | [f34555b3d6](https://linux-hardware.org/?probe=f34555b3d6) | Apr 30, 2022 |
| Acer          | Nitro AN515-45              | [c4456aaa4f](https://linux-hardware.org/?probe=c4456aaa4f) | Apr 19, 2022 |
| ILLEGEAR      | ROGUE                       | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Gigabyte      | G5 KC                       | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Apple         | MacBookPro5,5               | [9ddd1338d3](https://linux-hardware.org/?probe=9ddd1338d3) | Apr 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [6cd967267b](https://linux-hardware.org/?probe=6cd967267b) | Mar 31, 2022 |
| Dell          | Latitude D630               | [d9e3d65314](https://linux-hardware.org/?probe=d9e3d65314) | Mar 24, 2022 |
| HUAWEI        | WRT-WX9                     | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| Dell          | Inspiron 15 5501            | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Dell          | Precision 7730              | [9e9710e890](https://linux-hardware.org/?probe=9e9710e890) | Mar 08, 2022 |
| Dell          | Inspiron 5537               | [747515703c](https://linux-hardware.org/?probe=747515703c) | Jan 25, 2022 |
| ASUSTek       | GL553VD                     | [5d1c8ba7f2](https://linux-hardware.org/?probe=5d1c8ba7f2) | Jan 18, 2022 |
| Dell          | Precision 5550              | [6b866b7c2f](https://linux-hardware.org/?probe=6b866b7c2f) | Jan 18, 2022 |
| HONOR         | HLYL-WXX9                   | [7e0ee3374e](https://linux-hardware.org/?probe=7e0ee3374e) | Jan 16, 2022 |
| MSI           | GT70 2OC/2OD                | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| Dell          | Latitude 7490               | [4ac5151ac0](https://linux-hardware.org/?probe=4ac5151ac0) | Dec 29, 2021 |
| MSI           | GT70 2OC/2OD                | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| MSI           | GL62M 7RDX                  | [3f8cb0706d](https://linux-hardware.org/?probe=3f8cb0706d) | Dec 27, 2021 |
| Apple         | MacBookPro8,1               | [9fe5f60531](https://linux-hardware.org/?probe=9fe5f60531) | Dec 26, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Acer          | E3-112M-C6BV                | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| MSI           | Modern 14 B5M               | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| Dell          | Latitude E6520              | [faf1be45ae](https://linux-hardware.org/?probe=faf1be45ae) | Dec 03, 2021 |
| Dell          | Latitude E6520              | [16b69bfefc](https://linux-hardware.org/?probe=16b69bfefc) | Dec 01, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | [644d197332](https://linux-hardware.org/?probe=644d197332) | Nov 17, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | [bece194d5a](https://linux-hardware.org/?probe=bece194d5a) | Nov 17, 2021 |
| Unknown       | Unknown                     | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| ASUSTek       | T200TA                      | [1f55c83774](https://linux-hardware.org/?probe=1f55c83774) | Nov 04, 2021 |
| Lenovo        | U310                        | [986ba47618](https://linux-hardware.org/?probe=986ba47618) | Oct 24, 2021 |
| Lenovo        | U310                        | [c74a07756c](https://linux-hardware.org/?probe=c74a07756c) | Oct 24, 2021 |
| Acer          | Aspire 4752                 | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | Notebook                    | [2761140513](https://linux-hardware.org/?probe=2761140513) | Oct 14, 2021 |
| Dell          | Inspiron 3537               | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Acer          | Nitro AN515-45              | [09b2cd1736](https://linux-hardware.org/?probe=09b2cd1736) | Oct 06, 2021 |
| ASUSTek       | GL553VD                     | [07b1aa0f24](https://linux-hardware.org/?probe=07b1aa0f24) | Sep 27, 2021 |
| ASUSTek       | GL553VD                     | [2cdb257de7](https://linux-hardware.org/?probe=2cdb257de7) | Sep 27, 2021 |
| HP            | Notebook                    | [32d9b71796](https://linux-hardware.org/?probe=32d9b71796) | Sep 25, 2021 |
| Apple         | MacBookAir3,2               | [17c3d61831](https://linux-hardware.org/?probe=17c3d61831) | Sep 21, 2021 |
| Acer          | Nitro AN515-45              | [1292424ff8](https://linux-hardware.org/?probe=1292424ff8) | Sep 17, 2021 |
| ASUSTek       | X556UR                      | [7441498212](https://linux-hardware.org/?probe=7441498212) | Sep 14, 2021 |
| ASUSTek       | X550LC                      | [930ad79fe0](https://linux-hardware.org/?probe=930ad79fe0) | Sep 08, 2021 |
| HP            | EliteBook 8470p             | [9c46f65e1d](https://linux-hardware.org/?probe=9c46f65e1d) | Sep 06, 2021 |
| Toshiba       | dynabook Satellite B552/... | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| HP            | ENVY 4                      | [b61e9946e0](https://linux-hardware.org/?probe=b61e9946e0) | Sep 04, 2021 |
| HP            | Notebook                    | [7b28a98a35](https://linux-hardware.org/?probe=7b28a98a35) | Sep 01, 2021 |
| HP            | Notebook                    | [7fada0ab8c](https://linux-hardware.org/?probe=7fada0ab8c) | Sep 01, 2021 |
| Lenovo        | G400s VILG1                 | [20d6b25fd3](https://linux-hardware.org/?probe=20d6b25fd3) | Aug 29, 2021 |
| HP            | Notebook                    | [4028a5fb73](https://linux-hardware.org/?probe=4028a5fb73) | Aug 21, 2021 |
| Acer          | Nitro AN515-45              | [1083b28f53](https://linux-hardware.org/?probe=1083b28f53) | Aug 20, 2021 |
| Apple         | MacBookAir3,2               | [e359985b75](https://linux-hardware.org/?probe=e359985b75) | Aug 14, 2021 |
| ASUSTek       | K43SD                       | [bb82d97c94](https://linux-hardware.org/?probe=bb82d97c94) | Aug 10, 2021 |
| ASUSTek       | K43SD                       | [38abf3b8e9](https://linux-hardware.org/?probe=38abf3b8e9) | Aug 10, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | [b10f021bef](https://linux-hardware.org/?probe=b10f021bef) | Aug 01, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | [ded860ce52](https://linux-hardware.org/?probe=ded860ce52) | Jul 27, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | [4cf28c3600](https://linux-hardware.org/?probe=4cf28c3600) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| HP            | Notebook                    | [458741e8e2](https://linux-hardware.org/?probe=458741e8e2) | Jul 23, 2021 |
| HP            | Pavilion 14                 | [0556a517ff](https://linux-hardware.org/?probe=0556a517ff) | Jul 23, 2021 |
| HP            | EliteBook 8470p             | [fe43d29e0e](https://linux-hardware.org/?probe=fe43d29e0e) | Jul 22, 2021 |
| ASUSTek       | K43SA                       | [3c81cd98ac](https://linux-hardware.org/?probe=3c81cd98ac) | Jul 21, 2021 |
| Dell          | Inspiron 1018               | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| ASUSTek       | K43SA                       | [3da0ea28fa](https://linux-hardware.org/?probe=3da0ea28fa) | Jul 20, 2021 |
| HP            | Notebook                    | [2dc686eca0](https://linux-hardware.org/?probe=2dc686eca0) | Jul 15, 2021 |
| HP            | EliteBook 8470p             | [9ffbb5bc79](https://linux-hardware.org/?probe=9ffbb5bc79) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | [0e8b29c721](https://linux-hardware.org/?probe=0e8b29c721) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | [da8679ccca](https://linux-hardware.org/?probe=da8679ccca) | Jul 14, 2021 |
| HP            | Notebook                    | [83b65f2c8e](https://linux-hardware.org/?probe=83b65f2c8e) | Jul 11, 2021 |
| HP            | Compaq 6530b (VA036PA#UU... | [ac0b6b96cc](https://linux-hardware.org/?probe=ac0b6b96cc) | Jul 11, 2021 |
| ASUSTek       | X556UR                      | [477a92a37e](https://linux-hardware.org/?probe=477a92a37e) | Jul 11, 2021 |
| HP            | Notebook                    | [2f040042a3](https://linux-hardware.org/?probe=2f040042a3) | Jul 10, 2021 |
| ASUSTek       | X556UR                      | [4e555accb1](https://linux-hardware.org/?probe=4e555accb1) | Jul 08, 2021 |
| Acer          | Nitro AN515-45              | [416014c8b8](https://linux-hardware.org/?probe=416014c8b8) | Jul 07, 2021 |
| Acer          | Nitro AN515-45              | [a630867e0a](https://linux-hardware.org/?probe=a630867e0a) | Jul 06, 2021 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | [e1a02c3dcb](https://linux-hardware.org/?probe=e1a02c3dcb) | Jul 04, 2021 |
| Acer          | Nitro AN515-45              | [939fe39f71](https://linux-hardware.org/?probe=939fe39f71) | Jul 01, 2021 |
| Acer          | Nitro AN515-45              | [44c1472c85](https://linux-hardware.org/?probe=44c1472c85) | Jun 30, 2021 |
| AZW           | GT-R                        | [feaf90902f](https://linux-hardware.org/?probe=feaf90902f) | Jun 28, 2021 |
| Acer          | Nitro AN515-45              | [de1dbcbd7f](https://linux-hardware.org/?probe=de1dbcbd7f) | Jun 27, 2021 |
| Acer          | Nitro AN515-45              | [ddb8152ea4](https://linux-hardware.org/?probe=ddb8152ea4) | Jun 27, 2021 |
| Lenovo        | ThinkPad X201 3626RZ4       | [737819a617](https://linux-hardware.org/?probe=737819a617) | Jun 22, 2021 |
| HP            | Notebook                    | [0f663cf796](https://linux-hardware.org/?probe=0f663cf796) | Jun 20, 2021 |
| Acer          | Aspire A515-41G             | [9a397ba3b9](https://linux-hardware.org/?probe=9a397ba3b9) | Jun 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [b0ded1652a](https://linux-hardware.org/?probe=b0ded1652a) | Jun 12, 2021 |
| Apple         | MacBookPro8,1               | [e4a2d2d3c9](https://linux-hardware.org/?probe=e4a2d2d3c9) | Jun 06, 2021 |
| Dell          | Inspiron 5548               | [49a2755ccd](https://linux-hardware.org/?probe=49a2755ccd) | May 31, 2021 |
| Lenovo        | ThinkPad X120e 0611CTO      | [72608b2ea0](https://linux-hardware.org/?probe=72608b2ea0) | May 27, 2021 |
| Dell          | Inspiron 3443               | [1a314f201b](https://linux-hardware.org/?probe=1a314f201b) | May 26, 2021 |
| HP            | Notebook                    | [a075cb3a8d](https://linux-hardware.org/?probe=a075cb3a8d) | May 24, 2021 |
| HP            | Pavilion dv6                | [021e17aa96](https://linux-hardware.org/?probe=021e17aa96) | May 19, 2021 |
| HP            | Pavilion dv6                | [19e796b32f](https://linux-hardware.org/?probe=19e796b32f) | May 19, 2021 |
| HP            | Pavilion dv6                | [71f7778600](https://linux-hardware.org/?probe=71f7778600) | May 13, 2021 |
| HP            | Pavilion dv6                | [f8469a424b](https://linux-hardware.org/?probe=f8469a424b) | May 13, 2021 |
| ASUSTek       | K45VD                       | [67e6985b08](https://linux-hardware.org/?probe=67e6985b08) | May 02, 2021 |
| ASUSTek       | K45VD                       | [8624f1c148](https://linux-hardware.org/?probe=8624f1c148) | Apr 30, 2021 |
| System76      | Galago Pro                  | [e712e1fadc](https://linux-hardware.org/?probe=e712e1fadc) | Apr 21, 2021 |
| Dell          | XPS L412Z                   | [e383c24416](https://linux-hardware.org/?probe=e383c24416) | Apr 01, 2021 |
| Dell          | Inspiron 1564               | [006be2bbab](https://linux-hardware.org/?probe=006be2bbab) | Mar 22, 2021 |
| HP            | Pavilion dv6                | [1a6bdfe860](https://linux-hardware.org/?probe=1a6bdfe860) | Mar 22, 2021 |
| Dell          | Inspiron 5548               | [7a17fa61d9](https://linux-hardware.org/?probe=7a17fa61d9) | Mar 17, 2021 |
| HP            | Compaq Presario CQ40        | [d476794634](https://linux-hardware.org/?probe=d476794634) | Mar 16, 2021 |
| Sony          | VPCEA42EG                   | [e49095cfef](https://linux-hardware.org/?probe=e49095cfef) | Mar 09, 2021 |
| ASUSTek       | S550CM                      | [5ac3e9de20](https://linux-hardware.org/?probe=5ac3e9de20) | Mar 08, 2021 |
| ASUSTek       | K43SD                       | [597b4f88b9](https://linux-hardware.org/?probe=597b4f88b9) | Mar 08, 2021 |
| HP            | Presario CQ43               | [4f9c0e744c](https://linux-hardware.org/?probe=4f9c0e744c) | Feb 28, 2021 |
| Timi          | RedmiBook 14 II             | [082f8fd3e5](https://linux-hardware.org/?probe=082f8fd3e5) | Feb 27, 2021 |
| Timi          | RedmiBook 14 II             | [1555ed8743](https://linux-hardware.org/?probe=1555ed8743) | Feb 27, 2021 |
| HP            | Pavilion dv6                | [4f82ee745a](https://linux-hardware.org/?probe=4f82ee745a) | Feb 25, 2021 |
| HP            | Presario CQ43               | [e6e7199511](https://linux-hardware.org/?probe=e6e7199511) | Feb 22, 2021 |
| ASUSTek       | X456UF                      | [f69a109f5c](https://linux-hardware.org/?probe=f69a109f5c) | Feb 14, 2021 |
| HP            | G42                         | [7e1ebb9cf3](https://linux-hardware.org/?probe=7e1ebb9cf3) | Feb 13, 2021 |
| Dell          | Inspiron 1420               | [6c0820678b](https://linux-hardware.org/?probe=6c0820678b) | Feb 13, 2021 |
| HP            | Pavilion dv6                | [92518dacfe](https://linux-hardware.org/?probe=92518dacfe) | Feb 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4f8464acc9](https://linux-hardware.org/?probe=4f8464acc9) | Feb 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [aa40d0ff2b](https://linux-hardware.org/?probe=aa40d0ff2b) | Feb 04, 2021 |
| Dell          | Latitude E6440              | [31faebfa48](https://linux-hardware.org/?probe=31faebfa48) | Jan 23, 2021 |
| Dell          | Latitude 3440               | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| MSI           | Prestige 15 A10SC           | [353fb07166](https://linux-hardware.org/?probe=353fb07166) | Jan 20, 2021 |
| HP            | G42                         | [b4a8c3727b](https://linux-hardware.org/?probe=b4a8c3727b) | Jan 13, 2021 |
| HP            | Notebook                    | [6bb93d5d1d](https://linux-hardware.org/?probe=6bb93d5d1d) | Jan 03, 2021 |
| HP            | Presario CQ43               | [d410f07eef](https://linux-hardware.org/?probe=d410f07eef) | Jan 03, 2021 |
| HP            | Presario CQ43               | [15ba146bfe](https://linux-hardware.org/?probe=15ba146bfe) | Jan 03, 2021 |
| HP            | Pavilion g4                 | [c495b342b0](https://linux-hardware.org/?probe=c495b342b0) | Dec 30, 2020 |
| ASUSTek       | TP500LN                     | [36ae52e7d3](https://linux-hardware.org/?probe=36ae52e7d3) | Dec 27, 2020 |
| HP            | EliteBook 840 G2            | [41d76fb580](https://linux-hardware.org/?probe=41d76fb580) | Dec 17, 2020 |
| Lenovo        | Yoga 500-15IBD 80N6         | [9af064ae47](https://linux-hardware.org/?probe=9af064ae47) | Dec 16, 2020 |
| HP            | Laptop 15s-eq0xxx           | [967bb7f4d6](https://linux-hardware.org/?probe=967bb7f4d6) | Nov 30, 2020 |
| Dell          | XPS 15 7590                 | [151262b7a2](https://linux-hardware.org/?probe=151262b7a2) | Nov 26, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [eecae3dcbf](https://linux-hardware.org/?probe=eecae3dcbf) | Nov 26, 2020 |
| Dell          | G3 3590                     | [d76accb676](https://linux-hardware.org/?probe=d76accb676) | Nov 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [db8eeca79f](https://linux-hardware.org/?probe=db8eeca79f) | Nov 15, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [f617d36143](https://linux-hardware.org/?probe=f617d36143) | Nov 12, 2020 |
| Acer          | TM4750                      | [8380f08a89](https://linux-hardware.org/?probe=8380f08a89) | Nov 07, 2020 |
| HP            | Compaq Presario CQ60        | [4c1052e401](https://linux-hardware.org/?probe=4c1052e401) | Nov 06, 2020 |
| Dell          | G3 3590                     | [b2a86aaf94](https://linux-hardware.org/?probe=b2a86aaf94) | Nov 04, 2020 |
| Dell          | Latitude E6530              | [50772450d3](https://linux-hardware.org/?probe=50772450d3) | Nov 04, 2020 |
| Dell          | Inspiron N5110              | [1a5aef928b](https://linux-hardware.org/?probe=1a5aef928b) | Nov 01, 2020 |
| Acer          | Aspire V3-571G              | [adc51544ee](https://linux-hardware.org/?probe=adc51544ee) | Oct 29, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Acer          | TM4750                      | [2f46c4d024](https://linux-hardware.org/?probe=2f46c4d024) | Oct 27, 2020 |
| Acer          | TM4750                      | [29124f29f8](https://linux-hardware.org/?probe=29124f29f8) | Oct 23, 2020 |
| Dell          | G3 3590                     | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| Sony          | VGN-Z27GN_X                 | [a9230212d3](https://linux-hardware.org/?probe=a9230212d3) | Oct 03, 2020 |
| Unknown       | Unknown                     | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| ASUSTek       | K45VD                       | [80297bebea](https://linux-hardware.org/?probe=80297bebea) | Sep 17, 2020 |
| ASUSTek       | K45VD                       | [7b45816731](https://linux-hardware.org/?probe=7b45816731) | Sep 17, 2020 |
| HP            | Pavilion dv6                | [f48a018bbb](https://linux-hardware.org/?probe=f48a018bbb) | Sep 16, 2020 |
| ASUSTek       | K45VD                       | [5eaf26f820](https://linux-hardware.org/?probe=5eaf26f820) | Sep 15, 2020 |
| ASUSTek       | K45VD                       | [4e3ee75e9b](https://linux-hardware.org/?probe=4e3ee75e9b) | Sep 15, 2020 |
| Lenovo        | G50-70 20351                | [f7f932b330](https://linux-hardware.org/?probe=f7f932b330) | Sep 14, 2020 |
| Acer          | Aspire ES1-420              | [730ae12528](https://linux-hardware.org/?probe=730ae12528) | Sep 10, 2020 |
| Acer          | Aspire E5-575G              | [828c695fab](https://linux-hardware.org/?probe=828c695fab) | Sep 06, 2020 |
| HP            | Pavilion dv6                | [48368c8caa](https://linux-hardware.org/?probe=48368c8caa) | Sep 05, 2020 |
| HP            | Pavilion dv6                | [47c4b0fdaa](https://linux-hardware.org/?probe=47c4b0fdaa) | Sep 03, 2020 |
| ASUSTek       | VivoBook S15 X530UN         | [64e65fe674](https://linux-hardware.org/?probe=64e65fe674) | Aug 11, 2020 |
| HP            | Presario CQ43               | [df780756ee](https://linux-hardware.org/?probe=df780756ee) | Jul 31, 2020 |
| HP            | Presario CQ43               | [102ab797a7](https://linux-hardware.org/?probe=102ab797a7) | Jul 31, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [c85ae35bff](https://linux-hardware.org/?probe=c85ae35bff) | Jul 25, 2020 |
| Dell          | Latitude 7480               | [7fa880215f](https://linux-hardware.org/?probe=7fa880215f) | Jul 21, 2020 |
| Fujitsu       | LIFEBOOK LH531              | [d45acf2543](https://linux-hardware.org/?probe=d45acf2543) | Jul 18, 2020 |
| Fujitsu       | LIFEBOOK LH531              | [4b144fb616](https://linux-hardware.org/?probe=4b144fb616) | Jul 14, 2020 |
| Dell          | XPS 15 7590                 | [f5ff1447a7](https://linux-hardware.org/?probe=f5ff1447a7) | Jul 08, 2020 |
| ILLEGEAR      | RAVEN SE                    | [0aa18d5241](https://linux-hardware.org/?probe=0aa18d5241) | Jul 05, 2020 |
| Dell          | Latitude E6440              | [521818b099](https://linux-hardware.org/?probe=521818b099) | Jul 02, 2020 |
| Acer          | Aspire 4738                 | [519a7577c0](https://linux-hardware.org/?probe=519a7577c0) | Jun 28, 2020 |
| Acer          | Aspire 4730Z                | [0cd3f983c9](https://linux-hardware.org/?probe=0cd3f983c9) | Jun 26, 2020 |
| Acer          | Aspire 4730Z                | [bad4de6363](https://linux-hardware.org/?probe=bad4de6363) | Jun 26, 2020 |
| Dell          | Latitude E6440              | [1ffde1aa78](https://linux-hardware.org/?probe=1ffde1aa78) | Jun 24, 2020 |
| HP            | Pavilion dv6                | [4833031b9b](https://linux-hardware.org/?probe=4833031b9b) | Jun 23, 2020 |
| Dell          | Venue 11 Pro 5130           | [0a15b3f355](https://linux-hardware.org/?probe=0a15b3f355) | Jun 18, 2020 |
| ASUSTek       | G551JM                      | [3ab69ab51e](https://linux-hardware.org/?probe=3ab69ab51e) | Jun 10, 2020 |
| HP            | 14                          | [5a36b38b50](https://linux-hardware.org/?probe=5a36b38b50) | Jun 07, 2020 |
| Fujitsu       | LIFEBOOK S761               | [7d4e0682de](https://linux-hardware.org/?probe=7d4e0682de) | Jun 07, 2020 |
| HP            | EliteBook 8470p             | [b335d617f7](https://linux-hardware.org/?probe=b335d617f7) | May 26, 2020 |
| Sony          | VPCSB26FG                   | [1882c535de](https://linux-hardware.org/?probe=1882c535de) | May 21, 2020 |
| HP            | EliteBook 8470p             | [5dfd93efc3](https://linux-hardware.org/?probe=5dfd93efc3) | May 19, 2020 |
| HP            | EliteBook 8470p             | [57312d97cc](https://linux-hardware.org/?probe=57312d97cc) | May 19, 2020 |
| HP            | EliteBook 8470p             | [445fc4fef9](https://linux-hardware.org/?probe=445fc4fef9) | May 19, 2020 |
| SNS Networ... | JOI Book 150                | [3d61c3722c](https://linux-hardware.org/?probe=3d61c3722c) | May 11, 2020 |
| Sony          | VPCSB26FG                   | [f92d9768ce](https://linux-hardware.org/?probe=f92d9768ce) | May 07, 2020 |
| Sony          | VPCSB26FG                   | [b119ccc5f2](https://linux-hardware.org/?probe=b119ccc5f2) | May 07, 2020 |
| HP            | 14                          | [c0318bc179](https://linux-hardware.org/?probe=c0318bc179) | Apr 30, 2020 |
| BUSH          | Windows tablet              | [a25abad9de](https://linux-hardware.org/?probe=a25abad9de) | Apr 18, 2020 |
| HP            | EliteBook 8460p             | [9c68002e3d](https://linux-hardware.org/?probe=9c68002e3d) | Apr 13, 2020 |
| Acer          | TM4750                      | [bedf724360](https://linux-hardware.org/?probe=bedf724360) | Mar 11, 2020 |
| Acer          | TM4750                      | [db9b7453f2](https://linux-hardware.org/?probe=db9b7453f2) | Mar 11, 2020 |
| Acer          | TM4750                      | [69bbe5f0ee](https://linux-hardware.org/?probe=69bbe5f0ee) | Mar 11, 2020 |
| Dell          | Inspiron 1464               | [d6a38ddcea](https://linux-hardware.org/?probe=d6a38ddcea) | Mar 08, 2020 |
| Acer          | Aspire 4736Z                | [a6e2ff9c02](https://linux-hardware.org/?probe=a6e2ff9c02) | Feb 15, 2020 |
| HP            | ProBook 645 G1              | [18fb680615](https://linux-hardware.org/?probe=18fb680615) | Feb 04, 2020 |
| Apple         | MacBookPro8,2               | [5ab23205d8](https://linux-hardware.org/?probe=5ab23205d8) | Jan 21, 2020 |
| Apple         | MacBookPro8,2               | [1b04478121](https://linux-hardware.org/?probe=1b04478121) | Jan 14, 2020 |
| Unknown       | LapBook Pro                 | [f9d248ac7c](https://linux-hardware.org/?probe=f9d248ac7c) | Jan 03, 2020 |
| HP            | Laptop 15-bs0xx             | [3b64de1ec8](https://linux-hardware.org/?probe=3b64de1ec8) | Dec 31, 2019 |
| HP            | Laptop 15-bs0xx             | [31643f4ace](https://linux-hardware.org/?probe=31643f4ace) | Dec 31, 2019 |
| Lenovo        | G500s 20245                 | [82346138d0](https://linux-hardware.org/?probe=82346138d0) | Dec 30, 2019 |
| HP            | ProBook 4545s               | [66e278f8a6](https://linux-hardware.org/?probe=66e278f8a6) | Dec 29, 2019 |
| HP            | ProBook 4545s               | [8e9df5d49d](https://linux-hardware.org/?probe=8e9df5d49d) | Dec 29, 2019 |
| HP            | ProBook 4545s               | [7c1a6a786f](https://linux-hardware.org/?probe=7c1a6a786f) | Dec 29, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [f4689330d7](https://linux-hardware.org/?probe=f4689330d7) | Dec 14, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [d651477524](https://linux-hardware.org/?probe=d651477524) | Dec 14, 2019 |
| Dell          | Vostro V130                 | [ca716fdbad](https://linux-hardware.org/?probe=ca716fdbad) | Nov 09, 2019 |
| Dell          | Vostro V130                 | [0ba8558483](https://linux-hardware.org/?probe=0ba8558483) | Nov 08, 2019 |
| Acer          | Swift SF314-55G             | [8526e89541](https://linux-hardware.org/?probe=8526e89541) | Oct 16, 2019 |
| ASUSTek       | X456URK                     | [03b7432783](https://linux-hardware.org/?probe=03b7432783) | Oct 10, 2019 |
| HP            | ZBook 15                    | [f9aaccbfe0](https://linux-hardware.org/?probe=f9aaccbfe0) | Sep 06, 2019 |
| Dell          | Latitude E7440              | [04bd492077](https://linux-hardware.org/?probe=04bd492077) | Sep 06, 2019 |
| MSI           | GP70 2PE                    | [ae117eb491](https://linux-hardware.org/?probe=ae117eb491) | Sep 03, 2019 |
| MSI           | GP70 2PE                    | [3d8ad628fc](https://linux-hardware.org/?probe=3d8ad628fc) | Aug 31, 2019 |
| MSI           | GP70 2PE                    | [5970f3ca8b](https://linux-hardware.org/?probe=5970f3ca8b) | Aug 16, 2019 |
| MSI           | GP70 2PE                    | [3442bbe40c](https://linux-hardware.org/?probe=3442bbe40c) | Aug 05, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [f8d49fa793](https://linux-hardware.org/?probe=f8d49fa793) | Aug 03, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [46b9ff1fff](https://linux-hardware.org/?probe=46b9ff1fff) | Aug 03, 2019 |
| ASUSTek       | X450CP                      | [2931234c98](https://linux-hardware.org/?probe=2931234c98) | May 02, 2019 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [c7b00947af](https://linux-hardware.org/?probe=c7b00947af) | Apr 30, 2019 |
| HP            | EliteBook 8440p             | [35e3cab7fd](https://linux-hardware.org/?probe=35e3cab7fd) | Apr 24, 2019 |
| HP            | Laptop 15-bs0xx             | [3783735e9b](https://linux-hardware.org/?probe=3783735e9b) | Apr 23, 2019 |
| HP            | Laptop 15-bs0xx             | [672cf7aa7f](https://linux-hardware.org/?probe=672cf7aa7f) | Apr 20, 2019 |
| ASUSTek       | X550DP                      | [5202aae85e](https://linux-hardware.org/?probe=5202aae85e) | Feb 26, 2019 |
| ASUSTek       | X101H                       | [bfa018d76d](https://linux-hardware.org/?probe=bfa018d76d) | Jan 21, 2019 |
| ASUSTek       | X550DP                      | [9a6eb3277e](https://linux-hardware.org/?probe=9a6eb3277e) | Dec 18, 2018 |
| ASUSTek       | X550DP                      | [50574f0f32](https://linux-hardware.org/?probe=50574f0f32) | Dec 18, 2018 |
| ASUSTek       | X550DP                      | [a92a9fcc74](https://linux-hardware.org/?probe=a92a9fcc74) | Dec 18, 2018 |
| ASUSTek       | X550DP                      | [323f6e2eeb](https://linux-hardware.org/?probe=323f6e2eeb) | Dec 17, 2018 |
| Dell          | XPS L521X                   | [3f3c8f2571](https://linux-hardware.org/?probe=3f3c8f2571) | Nov 25, 2018 |
| Dell          | Latitude E6520              | [166d529d12](https://linux-hardware.org/?probe=166d529d12) | Nov 12, 2018 |
| Dell          | XPS L412Z                   | [8381b26177](https://linux-hardware.org/?probe=8381b26177) | Jan 27, 2017 |
| Dell          | XPS L412Z                   | [799ee32fce](https://linux-hardware.org/?probe=799ee32fce) | Jan 21, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 27        | 17.31%  |
| Ubuntu 18.04        | 12        | 7.69%   |
| Pop!_OS 20.10       | 8         | 5.13%   |
| Pop!_OS 21.04       | 6         | 3.85%   |
| Ubuntu 16.04        | 5         | 3.21%   |
| OpenMandriva 4.2    | 5         | 3.21%   |
| KDE neon 20.04      | 5         | 3.21%   |
| Fedora 33           | 4         | 2.56%   |
| Ubuntu 21.04        | 3         | 1.92%   |
| Ubuntu 19.04        | 3         | 1.92%   |
| OpenMandriva 4.50   | 3         | 1.92%   |
| Linux Mint 20.2     | 3         | 1.92%   |
| Linux Mint 19.3     | 3         | 1.92%   |
| Fedora 34           | 3         | 1.92%   |
| ArcoLinux Rolling   | 3         | 1.92%   |
| Arch                | 3         | 1.92%   |
| Zorin 16            | 2         | 1.28%   |
| Zorin 15            | 2         | 1.28%   |
| Ubuntu 20.10        | 2         | 1.28%   |
| Ubuntu 19.10        | 2         | 1.28%   |
| Pop!_OS 20.04       | 2         | 1.28%   |
| Manjaro             | 2         | 1.28%   |
| Lubuntu 18.04       | 2         | 1.28%   |
| Linux Mint 20.1     | 2         | 1.28%   |
| Fedora 35           | 2         | 1.28%   |
| EndeavourOS Rolling | 2         | 1.28%   |
| Elementary 5.1.7    | 2         | 1.28%   |
| Arch Rolling        | 2         | 1.28%   |
| Zorin 12            | 1         | 0.64%   |
| Xubuntu 19.10       | 1         | 0.64%   |
| Xero Rolling        | 1         | 0.64%   |
| Ubuntu MATE 20.04   | 1         | 0.64%   |
| Ubuntu Budgie 21.10 | 1         | 0.64%   |
| Ubuntu Budgie 20.04 | 1         | 0.64%   |
| Ubuntu 21.10        | 1         | 0.64%   |
| ROSA R8             | 1         | 0.64%   |
| Rocky Linux 8.4     | 1         | 0.64%   |
| Pop!_OS 21.10       | 1         | 0.64%   |
| Peppermint 10       | 1         | 0.64%   |
| MX 21               | 1         | 0.64%   |
| Manjaro 21.0.7      | 1         | 0.64%   |
| Manjaro 21.0.5      | 1         | 0.64%   |
| Manjaro 20.2.1      | 1         | 0.64%   |
| Manjaro 20.1.1      | 1         | 0.64%   |
| Manjaro 20.0.3      | 1         | 0.64%   |
| Lubuntu 19.10       | 1         | 0.64%   |
| LMDE 5              | 1         | 0.64%   |
| Linux Mint 18.3     | 1         | 0.64%   |
| Kubuntu 19.10       | 1         | 0.64%   |
| Kali 2020.4         | 1         | 0.64%   |
| Kali 2020.3         | 1         | 0.64%   |
| Kali 2020.2         | 1         | 0.64%   |
| Kali 2020.1         | 1         | 0.64%   |
| Fedora 32           | 1         | 0.64%   |
| Endless 3.9.5       | 1         | 0.64%   |
| Endless 3.8.0       | 1         | 0.64%   |
| Endless 3.7.6       | 1         | 0.64%   |
| Endless 3.6.4       | 1         | 0.64%   |
| Endless 3.5.0       | 1         | 0.64%   |
| Elementary 6        | 1         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 54        | 36.49%  |
| Pop!_OS       | 15        | 10.14%  |
| Fedora        | 9         | 6.08%   |
| OpenMandriva  | 8         | 5.41%   |
| Linux Mint    | 8         | 5.41%   |
| Manjaro       | 6         | 4.05%   |
| Zorin         | 5         | 3.38%   |
| KDE neon      | 5         | 3.38%   |
| Endless       | 5         | 3.38%   |
| Arch          | 5         | 3.38%   |
| Elementary    | 4         | 2.7%    |
| Lubuntu       | 3         | 2.03%   |
| ArcoLinux     | 3         | 2.03%   |
| Ubuntu Budgie | 2         | 1.35%   |
| Kali          | 2         | 1.35%   |
| EndeavourOS   | 2         | 1.35%   |
| Xubuntu       | 1         | 0.68%   |
| Xero          | 1         | 0.68%   |
| Ubuntu MATE   | 1         | 0.68%   |
| ROSA          | 1         | 0.68%   |
| Rocky Linux   | 1         | 0.68%   |
| Peppermint    | 1         | 0.68%   |
| MX            | 1         | 0.68%   |
| LMDE          | 1         | 0.68%   |
| Kubuntu       | 1         | 0.68%   |
| Debian        | 1         | 0.68%   |
| CentOS        | 1         | 0.68%   |
| BuildRoot     | 1         | 0.68%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.11.0-7620-generic       | 5         | 2.98%   |
| 5.10.14-desktop-1omv4002  | 4         | 2.38%   |
| 5.0.0-37-generic          | 4         | 2.38%   |
| 5.8.0-7642-generic        | 3         | 1.79%   |
| 5.4.0-58-generic          | 3         | 1.79%   |
| 5.4.0-54-generic          | 3         | 1.79%   |
| 5.4.0-42-generic          | 3         | 1.79%   |
| 5.12.4-desktop-1omv4050   | 3         | 1.79%   |
| 5.11.0-46-generic         | 3         | 1.79%   |
| 5.0.0-23-generic          | 3         | 1.79%   |
| 4.15.0-45-generic         | 3         | 1.79%   |
| 5.8.0-7630-generic        | 2         | 1.19%   |
| 5.8.0-45-generic          | 2         | 1.19%   |
| 5.4.0-89-generic          | 2         | 1.19%   |
| 5.4.0-64-generic          | 2         | 1.19%   |
| 5.4.0-52-generic          | 2         | 1.19%   |
| 5.3.0-51-generic          | 2         | 1.19%   |
| 5.13.0-7614-generic       | 2         | 1.19%   |
| 5.13.0-22-generic         | 2         | 1.19%   |
| 5.11.0-7614-generic       | 2         | 1.19%   |
| 5.11.0-40-generic         | 2         | 1.19%   |
| 5.11.0-27-generic         | 2         | 1.19%   |
| 5.10.79-1-lts             | 2         | 1.19%   |
| 5.10.13-200.fc33.x86_64   | 2         | 1.19%   |
| 5.10.0-13-amd64           | 2         | 1.19%   |
| 5.0.0-25-generic          | 2         | 1.19%   |
| 4.15.0-72-generic         | 2         | 1.19%   |
| 5.9.1-1.el8.elrepo.x86_64 | 1         | 0.6%    |
| 5.9.0-kali1-amd64         | 1         | 0.6%    |
| 5.9.0-050900-generic      | 1         | 0.6%    |
| 5.8.8-arch1-1             | 1         | 0.6%    |
| 5.8.6-arch1-1             | 1         | 0.6%    |
| 5.8.4-200.fc32.x86_64     | 1         | 0.6%    |
| 5.8.17-300.fc33.x86_64    | 1         | 0.6%    |
| 5.8.16-300.fc33.x86_64    | 1         | 0.6%    |
| 5.8.11-1-MANJARO          | 1         | 0.6%    |
| 5.8.10-17-tkg-upds        | 1         | 0.6%    |
| 5.8.0-kali3-amd64         | 1         | 0.6%    |
| 5.8.0-7625-generic        | 1         | 0.6%    |
| 5.8.0-63-generic          | 1         | 0.6%    |
| 5.8.0-55-generic          | 1         | 0.6%    |
| 5.8.0-43-generic          | 1         | 0.6%    |
| 5.8.0-38-generic          | 1         | 0.6%    |
| 5.8.0-34-generic          | 1         | 0.6%    |
| 5.8.0-29-generic          | 1         | 0.6%    |
| 5.8.0-14-generic          | 1         | 0.6%    |
| 5.7.7-arch1-1             | 1         | 0.6%    |
| 5.7.0-kali1-amd64         | 1         | 0.6%    |
| 5.6.16-1-MANJARO          | 1         | 0.6%    |
| 5.4.0-kali4-amd64         | 1         | 0.6%    |
| 5.4.0-91-generic          | 1         | 0.6%    |
| 5.4.0-86-generic          | 1         | 0.6%    |
| 5.4.0-7642-generic        | 1         | 0.6%    |
| 5.4.0-7634-generic        | 1         | 0.6%    |
| 5.4.0-74-generic          | 1         | 0.6%    |
| 5.4.0-72-generic          | 1         | 0.6%    |
| 5.4.0-60-generic          | 1         | 0.6%    |
| 5.4.0-53-generic          | 1         | 0.6%    |
| 5.4.0-51-generic          | 1         | 0.6%    |
| 5.4.0-48-generic          | 1         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 18.87%  |
| 5.11.0  | 17        | 10.69%  |
| 5.8.0   | 15        | 9.43%   |
| 4.15.0  | 12        | 7.55%   |
| 5.0.0   | 10        | 6.29%   |
| 5.3.0   | 9         | 5.66%   |
| 5.13.0  | 8         | 5.03%   |
| 5.10.14 | 4         | 2.52%   |
| 4.18.0  | 4         | 2.52%   |
| 5.16.15 | 3         | 1.89%   |
| 5.12.4  | 3         | 1.89%   |
| 5.10.0  | 3         | 1.89%   |
| 5.9.0   | 2         | 1.26%   |
| 5.12.9  | 2         | 1.26%   |
| 5.10.79 | 2         | 1.26%   |
| 5.10.13 | 2         | 1.26%   |
| 5.9.1   | 1         | 0.63%   |
| 5.8.8   | 1         | 0.63%   |
| 5.8.6   | 1         | 0.63%   |
| 5.8.4   | 1         | 0.63%   |
| 5.8.17  | 1         | 0.63%   |
| 5.8.16  | 1         | 0.63%   |
| 5.8.11  | 1         | 0.63%   |
| 5.8.10  | 1         | 0.63%   |
| 5.7.7   | 1         | 0.63%   |
| 5.7.0   | 1         | 0.63%   |
| 5.6.16  | 1         | 0.63%   |
| 5.17.1  | 1         | 0.63%   |
| 5.15.11 | 1         | 0.63%   |
| 5.14.3  | 1         | 0.63%   |
| 5.14.18 | 1         | 0.63%   |
| 5.14.12 | 1         | 0.63%   |
| 5.14.10 | 1         | 0.63%   |
| 5.14.0  | 1         | 0.63%   |
| 5.13.13 | 1         | 0.63%   |
| 5.12.14 | 1         | 0.63%   |
| 5.12.13 | 1         | 0.63%   |
| 5.11.18 | 1         | 0.63%   |
| 5.11.12 | 1         | 0.63%   |
| 5.11.1  | 1         | 0.63%   |
| 5.10.60 | 1         | 0.63%   |
| 5.10.49 | 1         | 0.63%   |
| 5.10.42 | 1         | 0.63%   |
| 5.10.36 | 1         | 0.63%   |
| 5.10.23 | 1         | 0.63%   |
| 5.10.19 | 1         | 0.63%   |
| 4.4.0   | 1         | 0.63%   |
| 4.10.0  | 1         | 0.63%   |
| 4.1.34  | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 19.23%  |
| 5.8     | 22        | 14.1%   |
| 5.11    | 20        | 12.82%  |
| 5.10    | 14        | 8.97%   |
| 4.15    | 12        | 7.69%   |
| 5.0     | 10        | 6.41%   |
| 5.3     | 9         | 5.77%   |
| 5.13    | 9         | 5.77%   |
| 5.12    | 7         | 4.49%   |
| 5.14    | 5         | 3.21%   |
| 4.18    | 4         | 2.56%   |
| 5.9     | 3         | 1.92%   |
| 5.16    | 3         | 1.92%   |
| 5.7     | 2         | 1.28%   |
| 5.6     | 1         | 0.64%   |
| 5.17    | 1         | 0.64%   |
| 5.15    | 1         | 0.64%   |
| 4.4     | 1         | 0.64%   |
| 4.10    | 1         | 0.64%   |
| 4.1     | 1         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 137       | 97.86%  |
| i686   | 3         | 2.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 67        | 45.27%  |
| Unknown    | 22        | 14.86%  |
| KDE5       | 21        | 14.19%  |
| XFCE       | 10        | 6.76%   |
| KDE        | 7         | 4.73%   |
| X-Cinnamon | 6         | 4.05%   |
| Pantheon   | 4         | 2.7%    |
| MATE       | 4         | 2.7%    |
| Unity      | 2         | 1.35%   |
| Budgie     | 2         | 1.35%   |
| Peppermint | 1         | 0.68%   |
| LXQt       | 1         | 0.68%   |
| LXDE       | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 120       | 81.08%  |
| Wayland | 16        | 10.81%  |
| Unknown | 9         | 6.08%   |
| Tty     | 3         | 2.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 92        | 63.89%  |
| SDDM    | 22        | 15.28%  |
| GDM     | 15        | 10.42%  |
| GDM3    | 7         | 4.86%   |
| LightDM | 6         | 4.17%   |
| TDM     | 2         | 1.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 109       | 76.76%  |
| Unknown | 17        | 11.97%  |
| en_GB   | 8         | 5.63%   |
| en_SG   | 3         | 2.11%   |
| ms_MY   | 1         | 0.7%    |
| ja_JP   | 1         | 0.7%    |
| id_ID   | 1         | 0.7%    |
| en_MY   | 1         | 0.7%    |
| C       | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 76        | 53.9%   |
| EFI  | 65        | 46.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 121       | 84.03%  |
| Btrfs   | 8         | 5.56%   |
| Overlay | 6         | 4.17%   |
| Unknown | 5         | 3.47%   |
| Xfs     | 2         | 1.39%   |
| Zfs     | 1         | 0.69%   |
| Ext2    | 1         | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 97        | 67.83%  |
| GPT     | 28        | 19.58%  |
| MBR     | 18        | 12.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 123       | 86.01%  |
| Yes       | 20        | 13.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 69.93%  |
| Yes       | 43        | 30.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 30        | 21.43%  |
| Hewlett-Packard     | 29        | 20.71%  |
| ASUSTek Computer    | 22        | 15.71%  |
| Lenovo              | 17        | 12.14%  |
| Acer                | 13        | 9.29%   |
| MSI                 | 5         | 3.57%   |
| Apple               | 5         | 3.57%   |
| Sony                | 3         | 2.14%   |
| Unknown             | 3         | 2.14%   |
| ILLEGEAR            | 2         | 1.43%   |
| Fujitsu             | 2         | 1.43%   |
| Toshiba             | 1         | 0.71%   |
| Timi                | 1         | 0.71%   |
| System76            | 1         | 0.71%   |
| SNS Network (M)     | 1         | 0.71%   |
| HUAWEI              | 1         | 0.71%   |
| HONOR               | 1         | 0.71%   |
| Gigabyte Technology | 1         | 0.71%   |
| BUSH                | 1         | 0.71%   |
| AZW                 | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Notebook                           | 4         | 2.86%   |
| Unknown                               | 3         | 2.14%   |
| HP Pavilion dv6                       | 2         | 1.43%   |
| HP Laptop 15-bs0xx                    | 2         | 1.43%   |
| HP EliteBook 8470p                    | 2         | 1.43%   |
| Dell XPS 15 7590                      | 2         | 1.43%   |
| Dell Latitude E6520                   | 2         | 1.43%   |
| Dell Latitude E6440                   | 2         | 1.43%   |
| ASUS K45VD                            | 2         | 1.43%   |
| ASUS K43SD                            | 2         | 1.43%   |
| Apple MacBookPro8,1                   | 2         | 1.43%   |
| Toshiba dynabook Satellite B552/H     | 1         | 0.71%   |
| Timi RedmiBook 14 II                  | 1         | 0.71%   |
| System76 Galago Pro                   | 1         | 0.71%   |
| Sony VPCSB26FG                        | 1         | 0.71%   |
| Sony VPCEA42EG                        | 1         | 0.71%   |
| Sony VGN-Z27GN_X                      | 1         | 0.71%   |
| SNS Network (M) JOI Book 150          | 1         | 0.71%   |
| MSI Prestige 15 A10SC                 | 1         | 0.71%   |
| MSI Modern 14 B5M                     | 1         | 0.71%   |
| MSI GT70 2OC/2OD                      | 1         | 0.71%   |
| MSI GP70 2PE                          | 1         | 0.71%   |
| MSI GL62M 7RDX                        | 1         | 0.71%   |
| Lenovo Yoga 500-15IBD 80N6            | 1         | 0.71%   |
| Lenovo XiaoXinAir 14+ ACN 2021 82L7   | 1         | 0.71%   |
| Lenovo U310                           | 1         | 0.71%   |
| Lenovo ThinkPad X220 42912WA          | 1         | 0.71%   |
| Lenovo ThinkPad X201 3626RZ4          | 1         | 0.71%   |
| Lenovo ThinkPad X201 3323LWA          | 1         | 0.71%   |
| Lenovo ThinkPad X131e 33682YU         | 1         | 0.71%   |
| Lenovo ThinkPad X120e 0611CTO         | 1         | 0.71%   |
| Lenovo ThinkPad T480 20L6S1RN00       | 1         | 0.71%   |
| Lenovo ThinkPad T460 20FMA0J6MY       | 1         | 0.71%   |
| Lenovo ThinkPad L15 Gen 2a 20X7CTO1WW | 1         | 0.71%   |
| Lenovo ThinkPad E590 20NBS03S00       | 1         | 0.71%   |
| Lenovo IdeaPad S540-14API 81NH        | 1         | 0.71%   |
| Lenovo IdeaPad S340-14API 81NB        | 1         | 0.71%   |
| Lenovo G500s 20245                    | 1         | 0.71%   |
| Lenovo G50-70 20351                   | 1         | 0.71%   |
| Lenovo G400s VILG1                    | 1         | 0.71%   |
| ILLEGEAR ROGUE                        | 1         | 0.71%   |
| ILLEGEAR RAVEN SE                     | 1         | 0.71%   |
| HUAWEI WRT-WX9                        | 1         | 0.71%   |
| HONOR HLYL-WXX9                       | 1         | 0.71%   |
| HP ZBook 15                           | 1         | 0.71%   |
| HP ProBook 645 G1                     | 1         | 0.71%   |
| HP ProBook 4545s                      | 1         | 0.71%   |
| HP Presario CQ43                      | 1         | 0.71%   |
| HP Pavilion Laptop 14-ce3xxx          | 1         | 0.71%   |
| HP Pavilion Gaming Laptop 15-dk0xxx   | 1         | 0.71%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 1         | 0.71%   |
| HP Pavilion g4                        | 1         | 0.71%   |
| HP Pavilion 14                        | 1         | 0.71%   |
| HP Laptop 15s-eq0xxx                  | 1         | 0.71%   |
| HP G42                                | 1         | 0.71%   |
| HP ENVY 4                             | 1         | 0.71%   |
| HP EliteBook 8460p                    | 1         | 0.71%   |
| HP EliteBook 8440p                    | 1         | 0.71%   |
| HP EliteBook 840 G2                   | 1         | 0.71%   |
| HP Compaq Presario CQ60               | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell Inspiron       | 11        | 7.86%   |
| Dell Latitude       | 10        | 7.14%   |
| Lenovo ThinkPad     | 9         | 6.43%   |
| Acer Aspire         | 9         | 6.43%   |
| HP Pavilion         | 7         | 5%      |
| HP EliteBook        | 5         | 3.57%   |
| HP Notebook         | 4         | 2.86%   |
| Dell XPS            | 4         | 2.86%   |
| HP Laptop           | 3         | 2.14%   |
| HP Compaq           | 3         | 2.14%   |
| Apple MacBookPro8   | 3         | 2.14%   |
| Unknown             | 3         | 2.14%   |
| Lenovo IdeaPad      | 2         | 1.43%   |
| HP ProBook          | 2         | 1.43%   |
| Fujitsu LIFEBOOK    | 2         | 1.43%   |
| Dell Precision      | 2         | 1.43%   |
| ASUS VivoBook       | 2         | 1.43%   |
| ASUS K45VD          | 2         | 1.43%   |
| ASUS K43SD          | 2         | 1.43%   |
| Toshiba dynabook    | 1         | 0.71%   |
| Timi RedmiBook      | 1         | 0.71%   |
| System76 Galago     | 1         | 0.71%   |
| Sony VPCSB26FG      | 1         | 0.71%   |
| Sony VPCEA42EG      | 1         | 0.71%   |
| Sony VGN-Z27GN      | 1         | 0.71%   |
| SNS Network (M) JOI | 1         | 0.71%   |
| MSI Prestige        | 1         | 0.71%   |
| MSI Modern          | 1         | 0.71%   |
| MSI GT70            | 1         | 0.71%   |
| MSI GP70            | 1         | 0.71%   |
| MSI GL62M           | 1         | 0.71%   |
| Lenovo Yoga         | 1         | 0.71%   |
| Lenovo XiaoXinAir   | 1         | 0.71%   |
| Lenovo U310         | 1         | 0.71%   |
| Lenovo G500s        | 1         | 0.71%   |
| Lenovo G50-70       | 1         | 0.71%   |
| Lenovo G400s        | 1         | 0.71%   |
| ILLEGEAR ROGUE      | 1         | 0.71%   |
| ILLEGEAR RAVEN      | 1         | 0.71%   |
| HUAWEI WRT-WX9      | 1         | 0.71%   |
| HONOR HLYL-WXX9     | 1         | 0.71%   |
| HP ZBook            | 1         | 0.71%   |
| HP Presario         | 1         | 0.71%   |
| HP G42              | 1         | 0.71%   |
| HP ENVY             | 1         | 0.71%   |
| HP 14               | 1         | 0.71%   |
| Gigabyte G5         | 1         | 0.71%   |
| Dell Vostro         | 1         | 0.71%   |
| Dell Venue          | 1         | 0.71%   |
| Dell G3             | 1         | 0.71%   |
| BUSH Windows        | 1         | 0.71%   |
| AZW GT-R            | 1         | 0.71%   |
| ASUS ZenBook        | 1         | 0.71%   |
| ASUS X556UR         | 1         | 0.71%   |
| ASUS X550LC         | 1         | 0.71%   |
| ASUS X550DP         | 1         | 0.71%   |
| ASUS X456URK        | 1         | 0.71%   |
| ASUS X456UF         | 1         | 0.71%   |
| ASUS X450CP         | 1         | 0.71%   |
| ASUS X101H          | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 23        | 16.43%  |
| 2013 | 19        | 13.57%  |
| 2019 | 15        | 10.71%  |
| 2010 | 10        | 7.14%   |
| 2020 | 9         | 6.43%   |
| 2018 | 9         | 6.43%   |
| 2015 | 9         | 6.43%   |
| 2012 | 9         | 6.43%   |
| 2021 | 8         | 5.71%   |
| 2017 | 7         | 5%      |
| 2014 | 6         | 4.29%   |
| 2009 | 5         | 3.57%   |
| 2008 | 5         | 3.57%   |
| 2016 | 4         | 2.86%   |
| 2007 | 2         | 1.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 140       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 129       | 92.14%  |
| Enabled  | 11        | 7.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 139       | 99.29%  |
| Yes  | 1         | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 40        | 28.37%  |
| 3.01-4.0    | 35        | 24.82%  |
| 8.01-16.0   | 32        | 22.7%   |
| 16.01-24.0  | 15        | 10.64%  |
| 1.01-2.0    | 7         | 4.96%   |
| 32.01-64.0  | 6         | 4.26%   |
| 2.01-3.0    | 2         | 1.42%   |
| 0.51-1.0    | 2         | 1.42%   |
| 24.01-32.0  | 1         | 0.71%   |
| 64.01-256.0 | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 57        | 36.31%  |
| 2.01-3.0  | 40        | 25.48%  |
| 3.01-4.0  | 26        | 16.56%  |
| 4.01-8.0  | 16        | 10.19%  |
| 0.51-1.0  | 15        | 9.55%   |
| 8.01-16.0 | 3         | 1.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 98        | 69.01%  |
| 2      | 42        | 29.58%  |
| 4      | 1         | 0.7%    |
| 3      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 57.14%  |
| Yes       | 60        | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 85%     |
| No        | 21        | 15%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 96.43%  |
| No        | 5         | 3.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 82.98%  |
| No        | 24        | 17.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Malaysia | 140       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 60        | 39.47%  |
| Petaling Jaya          | 26        | 17.11%  |
| Johor Bahru            | 9         | 5.92%   |
| Shah Alam              | 7         | 4.61%   |
| Kota Kinabalu          | 7         | 4.61%   |
| Skudai                 | 3         | 1.97%   |
| Kuala Terengganu       | 3         | 1.97%   |
| Ipoh                   | 3         | 1.97%   |
| Sungai Petani          | 2         | 1.32%   |
| Sungai Buloh           | 2         | 1.32%   |
| Subang Jaya            | 2         | 1.32%   |
| Seri Kembangan         | 2         | 1.32%   |
| Seremban               | 2         | 1.32%   |
| Puchong Batu Dua Belas | 2         | 1.32%   |
| Malacca                | 2         | 1.32%   |
| Kajang                 | 2         | 1.32%   |
| Teluk Intan            | 1         | 0.66%   |
| Rawang                 | 1         | 0.66%   |
| Pasir Gudang           | 1         | 0.66%   |
| Marabu                 | 1         | 0.66%   |
| Long Seridan           | 1         | 0.66%   |
| Kulai                  | 1         | 0.66%   |
| Kuching                | 1         | 0.66%   |
| Kuantan                | 1         | 0.66%   |
| Kota Bharu             | 1         | 0.66%   |
| Kampung Baharu Nilai   | 1         | 0.66%   |
| Kampar                 | 1         | 0.66%   |
| Dengkil                | 1         | 0.66%   |
| Cyberjaya              | 1         | 0.66%   |
| Cheras                 | 1         | 0.66%   |
| Butterworth            | 1         | 0.66%   |
| Bukit Mertajam         | 1         | 0.66%   |
| Bayan Lepas            | 1         | 0.66%   |
| Batu Caves             | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 37     | 17.98%  |
| WDC                 | 20        | 26     | 11.24%  |
| Toshiba             | 19        | 24     | 10.67%  |
| Samsung Electronics | 15        | 24     | 8.43%   |
| Kingston            | 14        | 15     | 7.87%   |
| HGST                | 12        | 15     | 6.74%   |
| Unknown             | 11        | 17     | 6.18%   |
| Sandisk             | 10        | 15     | 5.62%   |
| A-DATA Technology   | 5         | 5      | 2.81%   |
| Micron Technology   | 4         | 4      | 2.25%   |
| Hitachi             | 4         | 8      | 2.25%   |
| Transcend           | 3         | 3      | 1.69%   |
| Intel               | 3         | 3      | 1.69%   |
| China               | 3         | 3      | 1.69%   |
| SPCC                | 2         | 3      | 1.12%   |
| Phison              | 2         | 3      | 1.12%   |
| Patriot             | 2         | 2      | 1.12%   |
| KIOXIA              | 2         | 2      | 1.12%   |
| Apacer              | 2         | 2      | 1.12%   |
| winstar             | 1         | 1      | 0.56%   |
| Verbatim            | 1         | 1      | 0.56%   |
| SK Hynix            | 1         | 1      | 0.56%   |
| Silicon Motion      | 1         | 1      | 0.56%   |
| PNY                 | 1         | 1      | 0.56%   |
| Netac               | 1         | 1      | 0.56%   |
| Morebeck-S100       | 1         | 1      | 0.56%   |
| LS                  | 1         | 1      | 0.56%   |
| Fujitsu             | 1         | 1      | 0.56%   |
| Crucial             | 1         | 1      | 0.56%   |
| Colorful            | 1         | 1      | 0.56%   |
| Apple               | 1         | 2      | 0.56%   |
| AGI                 | 1         | 2      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 4         | 2.19%   |
| HGST HTS545050A7E680 500GB           | 4         | 2.19%   |
| Toshiba MQ04ABF100 1TB               | 3         | 1.64%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.64%   |
| Seagate ST9320325AS 320GB            | 3         | 1.64%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.64%   |
| Sandisk NVMe SSD Drive 512GB         | 3         | 1.64%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 1.09%   |
| WDC PC SN730 NVMe 1024GB             | 2         | 1.09%   |
| Unknown MMC Card  64GB               | 2         | 1.09%   |
| Unknown MMC Card  128GB              | 2         | 1.09%   |
| Toshiba MK5065GSXF 500GB             | 2         | 1.09%   |
| Seagate ST9750420AS 752GB            | 2         | 1.09%   |
| Seagate ST9500325AS 500GB            | 2         | 1.09%   |
| Seagate ST500LM000-1EJ162 500GB      | 2         | 1.09%   |
| Seagate ST320LT020-9YG142 320GB      | 2         | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.09%   |
| SanDisk SSD PLUS 240GB               | 2         | 1.09%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.09%   |
| Samsung NVMe SSD Drive 512GB         | 2         | 1.09%   |
| Micron 1100 SATA 512GB SSD           | 2         | 1.09%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 1.09%   |
| Intel NVMe SSD Drive 512GB           | 2         | 1.09%   |
| Hitachi HTS723232A7A364 320GB        | 2         | 1.09%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.09%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.09%   |
| HGST HTS541010A9E680 1TB             | 2         | 1.09%   |
| A-DATA SU650 240GB SSD               | 2         | 1.09%   |
| winstar 120GB                        | 1         | 0.55%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.55%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD     | 1         | 0.55%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 0.55%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.55%   |
| WDC WD5000BPVT-75HXZT3 500GB         | 1         | 0.55%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.55%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.55%   |
| WDC WD5000BPVT-16HXZT3 500GB         | 1         | 0.55%   |
| WDC WD5000BPVT-00HXZT1 500GB         | 1         | 0.55%   |
| WDC WD5000BPKT-75PK4T0 500GB         | 1         | 0.55%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 1         | 0.55%   |
| WDC WD1600BEVT-60ZCT0 160GB          | 1         | 0.55%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.55%   |
| WDC WD10JPVT-75A1YT0 1TB             | 1         | 0.55%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 1         | 0.55%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB | 1         | 0.55%   |
| Verbatim Vi550 S3 SSD 128GB          | 1         | 0.55%   |
| Unknown SD32G  32GB                  | 1         | 0.55%   |
| Unknown SD08G  8GB                   | 1         | 0.55%   |
| Unknown SB32G  32GB                  | 1         | 0.55%   |
| Unknown SB128  128GB                 | 1         | 0.55%   |
| Unknown SA08G  7GB                   | 1         | 0.55%   |
| Unknown NVMe SSD Drive 256GB         | 1         | 0.55%   |
| Unknown MMC Card  7GB                | 1         | 0.55%   |
| Transcend TS256GMSA230S 256GB SSD    | 1         | 0.55%   |
| Transcend TS1GSDOM22V 1GB SSD        | 1         | 0.55%   |
| Transcend TS128GSSD370 128GB         | 1         | 0.55%   |
| Toshiba THNSNF128GMCS 128GB SSD      | 1         | 0.55%   |
| Toshiba NVMe SSD Drive 512GB         | 1         | 0.55%   |
| Toshiba MQ01ABF050M 500GB            | 1         | 0.55%   |
| Toshiba MQ01ABD050 500GB             | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 36     | 38.75%  |
| Toshiba             | 17        | 21     | 21.25%  |
| WDC                 | 14        | 20     | 17.5%   |
| HGST                | 12        | 15     | 15%     |
| Hitachi             | 4         | 8      | 5%      |
| Samsung Electronics | 1         | 3      | 1.25%   |
| Fujitsu             | 1         | 1      | 1.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 10     | 17.86%  |
| Samsung Electronics | 9         | 16     | 16.07%  |
| SanDisk             | 7         | 7      | 12.5%   |
| A-DATA Technology   | 4         | 4      | 7.14%   |
| Transcend           | 3         | 3      | 5.36%   |
| Micron Technology   | 3         | 3      | 5.36%   |
| China               | 3         | 3      | 5.36%   |
| WDC                 | 2         | 2      | 3.57%   |
| SPCC                | 2         | 3      | 3.57%   |
| Patriot             | 2         | 2      | 3.57%   |
| Apacer              | 2         | 2      | 3.57%   |
| Verbatim            | 1         | 1      | 1.79%   |
| Toshiba             | 1         | 1      | 1.79%   |
| PNY                 | 1         | 1      | 1.79%   |
| Netac               | 1         | 1      | 1.79%   |
| LS                  | 1         | 1      | 1.79%   |
| Intel               | 1         | 1      | 1.79%   |
| Crucial             | 1         | 1      | 1.79%   |
| Colorful            | 1         | 1      | 1.79%   |
| Apple               | 1         | 2      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 78        | 104    | 46.71%  |
| SSD     | 51        | 65     | 30.54%  |
| NVMe    | 24        | 36     | 14.37%  |
| MMC     | 10        | 16     | 5.99%   |
| Unknown | 4         | 5      | 2.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 117       | 170    | 75.48%  |
| NVMe | 24        | 36     | 15.48%  |
| MMC  | 10        | 16     | 6.45%   |
| SAS  | 4         | 4      | 2.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 115    | 68.5%   |
| 0.51-1.0   | 40        | 54     | 31.5%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 51        | 34%     |
| 101-250        | 40        | 26.67%  |
| 501-1000       | 20        | 13.33%  |
| 1-20           | 11        | 7.33%   |
| 51-100         | 10        | 6.67%   |
| 21-50          | 8         | 5.33%   |
| 1001-2000      | 4         | 2.67%   |
| Unknown        | 4         | 2.67%   |
| More than 3000 | 1         | 0.67%   |
| 2001-3000      | 1         | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 66        | 42.86%  |
| 21-50     | 29        | 18.83%  |
| 101-250   | 20        | 12.99%  |
| 51-100    | 16        | 10.39%  |
| 251-500   | 14        | 9.09%   |
| 501-1000  | 4         | 2.6%    |
| Unknown   | 4         | 2.6%    |
| 1001-2000 | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Notebooks | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                   | 2         | 2      | 11.76%  |
| WDC WD5000BPVT-00HXZT1 500GB                | 1         | 1      | 5.88%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1      | 5.88%   |
| WDC WD10JPVT-75A1YT0 1TB                    | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 5.88%   |
| Toshiba MK5065GSX 500GB                     | 1         | 1      | 5.88%   |
| Toshiba MK1059GSMP 1TB                      | 1         | 1      | 5.88%   |
| SPCC Solid State Disk 256GB                 | 1         | 1      | 5.88%   |
| Seagate ST9750420AS 752GB                   | 1         | 1      | 5.88%   |
| Seagate ST9250315AS 250GB                   | 1         | 1      | 5.88%   |
| Samsung Electronics SSD PM830 2.5 7mm 512GB | 1         | 1      | 5.88%   |
| Micron Technology 1100 SATA 512GB SSD       | 1         | 1      | 5.88%   |
| Hitachi HTS723232A7A364 320GB               | 1         | 1      | 5.88%   |
| Hitachi HTS547575A9E384 752GB               | 1         | 3      | 5.88%   |
| HGST HTS541075A9E680 752GB                  | 1         | 1      | 5.88%   |
| HGST HTS541010A9E680 1TB                    | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 23.53%  |
| WDC                 | 3         | 3      | 17.65%  |
| Toshiba             | 3         | 3      | 17.65%  |
| Hitachi             | 2         | 4      | 11.76%  |
| HGST                | 2         | 2      | 11.76%  |
| SPCC                | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 28.57%  |
| WDC     | 3         | 3      | 21.43%  |
| Toshiba | 3         | 3      | 21.43%  |
| Hitachi | 2         | 4      | 14.29%  |
| HGST    | 2         | 2      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 16     | 81.25%  |
| SSD  | 3         | 3      | 18.75%  |

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
| Detected | 100       | 163    | 67.11%  |
| Works    | 34        | 44     | 22.82%  |
| Malfunc  | 15        | 19     | 10.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 107       | 71.33%  |
| AMD                          | 14        | 9.33%   |
| Sandisk                      | 7         | 4.67%   |
| Samsung Electronics          | 5         | 3.33%   |
| Kingston Technology Company  | 4         | 2.67%   |
| Nvidia                       | 3         | 2%      |
| Phison Electronics           | 2         | 1.33%   |
| KIOXIA                       | 2         | 1.33%   |
| Toshiba America Info Systems | 1         | 0.67%   |
| SK Hynix                     | 1         | 0.67%   |
| Silicon Motion               | 1         | 0.67%   |
| Micron Technology            | 1         | 0.67%   |
| ASMedia Technology           | 1         | 0.67%   |
| ADATA Technology             | 1         | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 19        | 12.18%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 9.62%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 13        | 8.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 7.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 6.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 4.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 3.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 3.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 3.21%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 2.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.92%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 1.28%   |
| Kingston Company KC2000 NVMe SSD                                                 | 2         | 1.28%   |
| Intel SSD 660P Series                                                            | 2         | 1.28%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.28%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.28%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 0.64%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.64%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.64%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.64%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.64%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.64%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.64%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.64%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.64%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.64%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.64%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.64%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.64%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.64%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.64%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                               | 1         | 0.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.64%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile       | 1         | 0.64%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.64%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 0.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.64%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.64%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.64%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 106       | 72.11%  |
| NVMe | 24        | 16.33%  |
| RAID | 10        | 6.8%    |
| IDE  | 7         | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 118       | 84.29%  |
| AMD    | 22        | 15.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 3.55%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 2.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.13%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.13%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 2.13%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 2.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.13%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 1.42%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.42%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.42%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 1.42%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 1.42%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.42%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.42%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.42%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 2         | 1.42%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 1.42%   |
| Intel Core i3-2367M CPU @ 1.40GHz             | 2         | 1.42%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.42%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.42%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 1.42%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 2         | 1.42%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.42%   |
| AMD A6-5350M APU with Radeon HD Graphics      | 2         | 1.42%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.71%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.71%   |
| Intel Pentium CPU B970 @ 2.30GHz              | 1         | 0.71%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.71%   |
| Intel Pentium 3558U @ 1.70GHz                 | 1         | 0.71%   |
| Intel Genuine CPU T1700 @ 1.83GHz             | 1         | 0.71%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.71%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.71%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.71%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.71%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.71%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.71%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.71%   |
| Intel Core i7-4610M CPU @ 3.00GHz             | 1         | 0.71%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.71%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.71%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.71%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 0.71%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.71%   |
| Intel Core i7-3517U CPU @ 1.90GHz             | 1         | 0.71%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 1         | 0.71%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.71%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.71%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 1         | 0.71%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.71%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.71%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 0.71%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.71%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.71%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.71%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.71%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 30.5%   |
| Intel Core i7           | 35        | 24.82%  |
| Intel Core i3           | 14        | 9.93%   |
| AMD Ryzen 5             | 10        | 7.09%   |
| Intel Core 2 Duo        | 6         | 4.26%   |
| Intel Celeron           | 5         | 3.55%   |
| Intel Atom              | 5         | 3.55%   |
| Intel Pentium Dual-Core | 3         | 2.13%   |
| Intel Pentium           | 3         | 2.13%   |
| AMD A6                  | 3         | 2.13%   |
| Other                   | 2         | 1.42%   |
| AMD Ryzen 7 PRO         | 2         | 1.42%   |
| AMD A4                  | 2         | 1.42%   |
| Intel Xeon              | 1         | 0.71%   |
| Intel Genuine           | 1         | 0.71%   |
| Intel Core i9           | 1         | 0.71%   |
| AMD Ryzen 7             | 1         | 0.71%   |
| AMD E                   | 1         | 0.71%   |
| AMD Athlon              | 1         | 0.71%   |
| AMD A12                 | 1         | 0.71%   |
| AMD A10                 | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 78        | 55.71%  |
| 4      | 40        | 28.57%  |
| 6      | 15        | 10.71%  |
| 1      | 5         | 3.57%   |
| 8      | 2         | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 140       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 115       | 81.56%  |
| 1      | 26        | 18.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 138       | 97.87%  |
| Unknown        | 3         | 2.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 18.06%  |
| 0x206a7    | 16        | 11.11%  |
| 0x306a9    | 11        | 7.64%   |
| 0x906ea    | 7         | 4.86%   |
| 0x40651    | 7         | 4.86%   |
| 0x306c3    | 7         | 4.86%   |
| 0x406e3    | 6         | 4.17%   |
| 0x806e9    | 5         | 3.47%   |
| 0x20655    | 5         | 3.47%   |
| 0x306d4    | 4         | 2.78%   |
| 0x20652    | 4         | 2.78%   |
| 0x1067a    | 4         | 2.78%   |
| 0x06001119 | 4         | 2.78%   |
| 0xa0652    | 3         | 2.08%   |
| 0x806eb    | 2         | 1.39%   |
| 0x806ea    | 2         | 1.39%   |
| 0x706e5    | 2         | 1.39%   |
| 0x706a1    | 2         | 1.39%   |
| 0x30678    | 2         | 1.39%   |
| 0x106ca    | 2         | 1.39%   |
| 0x08600104 | 2         | 1.39%   |
| 0x08108102 | 2         | 1.39%   |
| 0x0700010f | 2         | 1.39%   |
| 0xa0660    | 1         | 0.69%   |
| 0x906e9    | 1         | 0.69%   |
| 0x806ec    | 1         | 0.69%   |
| 0x806d1    | 1         | 0.69%   |
| 0x6fd      | 1         | 0.69%   |
| 0x6fb      | 1         | 0.69%   |
| 0x406c4    | 1         | 0.69%   |
| 0x406c3    | 1         | 0.69%   |
| 0x10676    | 1         | 0.69%   |
| 0x0a50000c | 1         | 0.69%   |
| 0x0a50000b | 1         | 0.69%   |
| 0x08608103 | 1         | 0.69%   |
| 0x08600106 | 1         | 0.69%   |
| 0x08108109 | 1         | 0.69%   |
| 0x08101016 | 1         | 0.69%   |
| 0x06006118 | 1         | 0.69%   |
| 0x05000028 | 1         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 22        | 15.71%  |
| KabyLake        | 20        | 14.29%  |
| IvyBridge       | 15        | 10.71%  |
| Haswell         | 15        | 10.71%  |
| Westmere        | 9         | 6.43%   |
| Penryn          | 7         | 5%      |
| Skylake         | 6         | 4.29%   |
| Zen+            | 5         | 3.57%   |
| Silvermont      | 5         | 3.57%   |
| Piledriver      | 4         | 2.86%   |
| CometLake       | 4         | 2.86%   |
| Broadwell       | 4         | 2.86%   |
| Zen 3           | 3         | 2.14%   |
| Zen 2           | 3         | 2.14%   |
| IceLake         | 3         | 2.14%   |
| Core            | 3         | 2.14%   |
| Jaguar          | 2         | 1.43%   |
| Goldmont plus   | 2         | 1.43%   |
| Bonnell         | 2         | 1.43%   |
| Zen             | 1         | 0.71%   |
| TigerLake       | 1         | 0.71%   |
| K8 & K10 hybrid | 1         | 0.71%   |
| Excavator       | 1         | 0.71%   |
| Bobcat          | 1         | 0.71%   |
| Unknown         | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 111       | 55.22%  |
| Nvidia | 52        | 25.87%  |
| AMD    | 38        | 18.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 10.19%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 7.28%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 9         | 4.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 3.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 3.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 3.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.91%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 2.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.91%   |
| Intel HD Graphics 620                                                                    | 5         | 2.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.94%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.94%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 1.46%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 3         | 1.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.46%   |
| AMD Renoir                                                                               | 3         | 1.46%   |
| AMD Cezanne                                                                              | 3         | 1.46%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.97%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.97%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.97%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.97%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.97%   |
| Intel HD Graphics 630                                                                    | 2         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.97%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.97%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 2         | 0.97%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.97%   |
| AMD Richland [Radeon HD 8450G]                                                           | 2         | 0.97%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.97%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.49%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.49%   |
| Nvidia TU117M                                                                            | 1         | 0.49%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.49%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.49%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.49%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.49%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.49%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.49%   |
| Nvidia GP104GLM [Quadro P5200 Mobile]                                                    | 1         | 0.49%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 1         | 0.49%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.49%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.49%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.49%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 0.49%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.49%   |
| Nvidia GK104M [GeForce GTX 780M]                                                         | 1         | 0.49%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.49%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.49%   |
| Nvidia GF108M [GeForce 610M]                                                             | 1         | 0.49%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.49%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.49%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.49%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 0.49%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 37.59%  |
| Intel + Nvidia | 44        | 31.21%  |
| 1 x AMD        | 18        | 12.77%  |
| Intel + AMD    | 14        | 9.93%   |
| 1 x Nvidia     | 5         | 3.55%   |
| 2 x AMD        | 4         | 2.84%   |
| AMD + Nvidia   | 3         | 2.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 108       | 76.6%   |
| Proprietary | 31        | 21.99%  |
| Unknown     | 2         | 1.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 49.31%  |
| 1.01-2.0   | 33        | 22.92%  |
| 0.01-0.5   | 16        | 11.11%  |
| 3.01-4.0   | 15        | 10.42%  |
| 0.51-1.0   | 8         | 5.56%   |
| 5.01-6.0   | 1         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 34        | 22.22%  |
| Chimei Innolux          | 24        | 15.69%  |
| BOE                     | 19        | 12.42%  |
| LG Display              | 18        | 11.76%  |
| Samsung Electronics     | 16        | 10.46%  |
| Dell                    | 7         | 4.58%   |
| Sharp                   | 5         | 3.27%   |
| Chi Mei Optoelectronics | 4         | 2.61%   |
| Apple                   | 4         | 2.61%   |
| Lenovo                  | 3         | 1.96%   |
| Acer                    | 3         | 1.96%   |
| InnoLux Display         | 2         | 1.31%   |
| Hewlett-Packard         | 2         | 1.31%   |
| ViewSonic               | 1         | 0.65%   |
| Unknown                 | 1         | 0.65%   |
| Toshiba                 | 1         | 0.65%   |
| Sony                    | 1         | 0.65%   |
| Philips                 | 1         | 0.65%   |
| PANDA                   | 1         | 0.65%   |
| Panasonic               | 1         | 0.65%   |
| LG Philips              | 1         | 0.65%   |
| InfoVision              | 1         | 0.65%   |
| EXP                     | 1         | 0.65%   |
| Armaggeddon             | 1         | 0.65%   |
| Ancor Communications    | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 3         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch      | 2         | 1.31%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 2         | 1.31%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 2         | 1.31%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch          | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch           | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch           | 2         | 1.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.31%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch             | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch             | 2         | 1.31%   |
| ViewSonic V3D231 Series VSC4C29 1920x1080 510x290mm 23.1-inch             | 1         | 0.65%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1600x900               | 1         | 0.65%   |
| Toshiba TV TSB010B 1920x1080 926x523mm 41.9-inch                          | 1         | 0.65%   |
| Sony TV SNY0902 1360x768                                                  | 1         | 0.65%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                   | 1         | 0.65%   |
| Sharp LCD SHP10C9 1920x540                                                | 1         | 0.65%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 1         | 0.65%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 1         | 0.65%   |
| Sharp HDMI SHP10A1 1360x768 700x390mm 31.5-inch                           | 1         | 0.65%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch         | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch      | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch      | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch      | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch      | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3354 1600x900 382x215mm 17.3-inch      | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch      | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch     | 1         | 0.65%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 1         | 0.65%   |
| Philips PHL 241V8 PHLC212 1920x1080 527x296mm 23.8-inch                   | 1         | 0.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 1         | 0.65%   |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                        | 1         | 0.65%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch              | 1         | 0.65%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD03DF 1366x768 344x194mm 15.5-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD03B3 1366x768 309x174mm 14.0-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD0327 1366x768 309x174mm 14.0-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD0311 1366x768 293x165mm 13.2-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch              | 1         | 0.65%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 1         | 0.65%   |
| LG Display LCD Monitor LGD02B2 1366x768 310x174mm 14.0-inch               | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 68        | 46.58%  |
| 1920x1080 (FHD)   | 54        | 36.99%  |
| 1280x800 (WXGA)   | 8         | 5.48%   |
| 1600x900 (HD+)    | 4         | 2.74%   |
| 3840x2160 (4K)    | 2         | 1.37%   |
| 2560x1440 (QHD)   | 2         | 1.37%   |
| 2560x1080         | 1         | 0.68%   |
| 2240x1400         | 1         | 0.68%   |
| 2160x1440         | 1         | 0.68%   |
| 1920x540          | 1         | 0.68%   |
| 1920x1200 (WUXGA) | 1         | 0.68%   |
| 1440x900 (WXGA+)  | 1         | 0.68%   |
| 1360x768          | 1         | 0.68%   |
| 1024x600          | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 54        | 35.29%  |
| 14      | 33        | 21.57%  |
| 13      | 26        | 16.99%  |
| 23      | 8         | 5.23%   |
| 17      | 5         | 3.27%   |
| 11      | 4         | 2.61%   |
| 24      | 3         | 1.96%   |
| 21      | 3         | 1.96%   |
| 12      | 3         | 1.96%   |
| 72      | 2         | 1.31%   |
| Unknown | 2         | 1.31%   |
| 84      | 1         | 0.65%   |
| 52      | 1         | 0.65%   |
| 31      | 1         | 0.65%   |
| 28      | 1         | 0.65%   |
| 27      | 1         | 0.65%   |
| 25      | 1         | 0.65%   |
| 19      | 1         | 0.65%   |
| 18      | 1         | 0.65%   |
| 16      | 1         | 0.65%   |
| 10      | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 105       | 68.63%  |
| 201-300     | 15        | 9.8%    |
| 501-600     | 12        | 7.84%   |
| 351-400     | 7         | 4.58%   |
| 401-500     | 6         | 3.92%   |
| 1501-2000   | 3         | 1.96%   |
| 601-700     | 2         | 1.31%   |
| Unknown     | 2         | 1.31%   |
| 1001-1500   | 1         | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 118       | 88.72%  |
| 16/10   | 9         | 6.77%   |
| 3/2     | 3         | 2.26%   |
| 32/9    | 1         | 0.75%   |
| 21/9    | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 55        | 35.95%  |
| 81-90          | 54        | 35.29%  |
| 201-250        | 12        | 7.84%   |
| 71-80          | 5         | 3.27%   |
| 121-130        | 5         | 3.27%   |
| More than 1000 | 4         | 2.61%   |
| 51-60          | 4         | 2.61%   |
| 61-70          | 3         | 1.96%   |
| 151-200        | 3         | 1.96%   |
| 251-300        | 2         | 1.31%   |
| Unknown        | 2         | 1.31%   |
| 351-500        | 1         | 0.65%   |
| 41-50          | 1         | 0.65%   |
| 301-350        | 1         | 0.65%   |
| 141-150        | 1         | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 69        | 46%     |
| 121-160       | 54        | 36%     |
| 51-100        | 18        | 12%     |
| 1-50          | 4         | 2.67%   |
| 161-240       | 2         | 1.33%   |
| Unknown       | 2         | 1.33%   |
| More than 240 | 1         | 0.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 116       | 81.69%  |
| 2     | 23        | 16.2%   |
| 0     | 3         | 2.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 77        | 32.91%  |
| Intel                    | 62        | 26.5%   |
| Qualcomm Atheros         | 44        | 18.8%   |
| Broadcom                 | 16        | 6.84%   |
| TP-Link                  | 5         | 2.14%   |
| Ralink                   | 4         | 1.71%   |
| MEDIATEK                 | 4         | 1.71%   |
| Broadcom Limited         | 4         | 1.71%   |
| Ralink Technology        | 3         | 1.28%   |
| Huawei Technologies      | 3         | 1.28%   |
| Xiaomi                   | 2         | 0.85%   |
| Nvidia                   | 2         | 0.85%   |
| OPPO Electronics         | 1         | 0.43%   |
| Marvell Technology Group | 1         | 0.43%   |
| Hewlett-Packard          | 1         | 0.43%   |
| DisplayLink              | 1         | 0.43%   |
| D-Link                   | 1         | 0.43%   |
| Attansic Technology      | 1         | 0.43%   |
| ASUSTek Computer         | 1         | 0.43%   |
| ASIX Electronics         | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 16.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 6.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.88%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 2.16%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.44%   |
| TP-Link 802.11n NIC                                               | 3         | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.08%   |
| Realtek 802.11ac NIC                                              | 3         | 1.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.08%   |
| Intel Wireless 7260                                               | 3         | 1.08%   |
| Intel Wireless 3160                                               | 3         | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.08%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 1.08%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.08%   |
| Huawei JNY-LX1                                                    | 3         | 1.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.08%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.72%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.72%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.72%   |
| Intel Wireless-AC 9260                                            | 2         | 0.72%   |
| Intel Wireless 7265                                               | 2         | 0.72%   |
| Intel Wireless 3165                                               | 2         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.72%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.72%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.72%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.72%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.36%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                           | 1         | 0.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.36%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.36%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 40%     |
| Qualcomm Atheros      | 37        | 24.67%  |
| Realtek Semiconductor | 21        | 14%     |
| Broadcom              | 11        | 7.33%   |
| TP-Link               | 5         | 3.33%   |
| Ralink                | 4         | 2.67%   |
| MEDIATEK              | 4         | 2.67%   |
| Ralink Technology     | 3         | 2%      |
| Broadcom Limited      | 3         | 2%      |
| D-Link                | 1         | 0.67%   |
| ASUSTek Computer      | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 8         | 5.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 8         | 5.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 8         | 5.26%   |
| Intel Wi-Fi 6 AX200                                              | 6         | 3.95%   |
| Intel Wireless 8265 / 8275                                       | 5         | 3.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 5         | 3.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 4         | 2.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)   | 4         | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 4         | 2.63%   |
| TP-Link 802.11n NIC                                              | 3         | 1.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 3         | 1.97%   |
| Realtek 802.11ac NIC                                             | 3         | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 3         | 1.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                 | 3         | 1.97%   |
| Intel Wireless 7260                                              | 3         | 1.97%   |
| Intel Wireless 3160                                              | 3         | 1.97%   |
| Intel Centrino Wireless-N 2230                                   | 3         | 1.97%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 1.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                   | 3         | 1.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 2         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 2         | 1.32%   |
| Realtek RTL8723DE Wireless Network Adapter                       | 2         | 1.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                           | 2         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 1.32%   |
| Ralink MT7601U Wireless Adapter                                  | 2         | 1.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                        | 2         | 1.32%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 2         | 1.32%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter    | 2         | 1.32%   |
| Intel Wireless-AC 9260                                           | 2         | 1.32%   |
| Intel Wireless 7265                                              | 2         | 1.32%   |
| Intel Wireless 3165                                              | 2         | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 2         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 2         | 1.32%   |
| Intel Centrino Advanced-N 6235                                   | 2         | 1.32%   |
| Intel Centrino Advanced-N 6200                                   | 2         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                         | 2         | 1.32%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 2         | 1.32%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                | 2         | 1.32%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                          | 1         | 0.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                     | 1         | 0.66%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                       | 1         | 0.66%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter            | 1         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 1         | 0.66%   |
| Ralink RT2870/RT3070 Wireless Adapter                            | 1         | 0.66%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 0.66%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                        | 1         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 1         | 0.66%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                          | 1         | 0.66%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter              | 1         | 0.66%   |
| Intel Wireless 8260                                              | 1         | 0.66%   |
| Intel WiFi Link 5100                                             | 1         | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                           | 1         | 0.66%   |
| Intel Wi-Fi 6 AX201                                              | 1         | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                   | 1         | 0.66%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection          | 1         | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 1         | 0.66%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 1         | 0.66%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                     | 1         | 0.66%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                    | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 69        | 55.65%  |
| Intel                    | 23        | 18.55%  |
| Qualcomm Atheros         | 11        | 8.87%   |
| Broadcom                 | 8         | 6.45%   |
| Huawei Technologies      | 3         | 2.42%   |
| Xiaomi                   | 2         | 1.61%   |
| Nvidia                   | 2         | 1.61%   |
| OPPO Electronics         | 1         | 0.81%   |
| Marvell Technology Group | 1         | 0.81%   |
| DisplayLink              | 1         | 0.81%   |
| Broadcom Limited         | 1         | 0.81%   |
| Attansic Technology      | 1         | 0.81%   |
| ASIX Electronics         | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 47        | 37.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 18        | 14.4%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 6.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 2.4%    |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.4%    |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 2.4%    |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 2.4%    |
| Huawei JNY-LX1                                                                 | 3         | 2.4%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 2.4%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 2.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 1.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.8%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.8%    |
| OPPO SDM665-IDP _SN:18689828                                                   | 1         | 0.8%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.8%    |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.8%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.8%    |
| Intel Ethernet Connection I219-V                                               | 1         | 0.8%    |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.8%    |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 1         | 0.8%    |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.8%    |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.8%    |
| DisplayLink Dell Universal Dock D6000                                          | 1         | 0.8%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 1         | 0.8%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 0.8%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 0.8%    |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 1         | 0.8%    |
| ASIX AX88772B                                                                  | 1         | 0.8%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 52.94%  |
| Ethernet | 119       | 46.67%  |
| Modem    | 1         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 121       | 65.41%  |
| Ethernet | 64        | 34.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 109       | 77.86%  |
| 1     | 26        | 18.57%  |
| 0     | 4         | 2.86%   |
| 3     | 1         | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 74.31%  |
| Yes  | 37        | 25.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 34.45%  |
| Qualcomm Atheros Communications | 12        | 10.08%  |
| Broadcom                        | 11        | 9.24%   |
| Realtek Semiconductor           | 10        | 8.4%    |
| Foxconn / Hon Hai               | 9         | 7.56%   |
| IMC Networks                    | 8         | 6.72%   |
| Lite-On Technology              | 7         | 5.88%   |
| Apple                           | 5         | 4.2%    |
| Hewlett-Packard                 | 3         | 2.52%   |
| Dell                            | 3         | 2.52%   |
| Realtek                         | 2         | 1.68%   |
| Ralink                          | 2         | 1.68%   |
| MediaTek                        | 2         | 1.68%   |
| Ralink Technology               | 1         | 0.84%   |
| Cambridge Silicon Radio         | 1         | 0.84%   |
| Askey Computer                  | 1         | 0.84%   |
| Alps Electric                   | 1         | 0.84%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 15        | 12.61%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 5.88%   |
| Realtek Bluetooth Radio                                                             | 6         | 5.04%   |
| Intel AX200 Bluetooth                                                               | 6         | 5.04%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 3.36%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 3.36%   |
| Intel AX201 Bluetooth                                                               | 4         | 3.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 3.36%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 3.36%   |
| Apple Bluetooth Host Controller                                                     | 4         | 3.36%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 2.52%   |
| Realtek 802.11n WLAN Adapter                                                        | 2         | 1.68%   |
| Realtek Bluetooth Radio                                                             | 2         | 1.68%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.68%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 1.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.68%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 1.68%   |
| Intel Bluetooth Device                                                              | 2         | 1.68%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.68%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.68%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.68%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.68%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 1.68%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.68%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.84%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.84%   |
| Ralink CSR BS8510                                                                   | 1         | 0.84%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.84%   |
| MediaTek Wireless_Device                                                            | 1         | 0.84%   |
| MediaTek BT                                                                         | 1         | 0.84%   |
| Lite-On Wireless_Device                                                             | 1         | 0.84%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.84%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.84%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.84%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.84%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.84%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.84%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.84%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.84%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.84%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 1         | 0.84%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.84%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.84%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.84%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.84%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.84%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.84%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.84%   |
| Askey Bluetooth Device                                                              | 1         | 0.84%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.84%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 113       | 67.26%  |
| AMD                    | 24        | 14.29%  |
| Nvidia                 | 22        | 13.1%   |
| C-Media Electronics    | 3         | 1.79%   |
| Samsung Electronics    | 2         | 1.19%   |
| Realtek Semiconductor  | 1         | 0.6%    |
| Plantronics            | 1         | 0.6%    |
| MVSILICON.INC.         | 1         | 0.6%    |
| Generalplus Technology | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 9.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 8.29%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 6.34%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 6.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 4.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 3.9%    |
| Intel 8 Series HD Audio Controller                                                                | 8         | 3.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 3.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.93%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.95%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.95%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.95%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.46%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.46%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.46%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.98%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.98%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.98%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.98%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.98%   |
| Samsung Electronics USBC Headset                                                                  | 1         | 0.49%   |
| Samsung Electronics USB C Earphones                                                               | 1         | 0.49%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.49%   |
| Plantronics C320-M                                                                                | 1         | 0.49%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.49%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.49%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.49%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.49%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.49%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.49%   |
| Nvidia Audio device                                                                               | 1         | 0.49%   |
| MVSILICON.INC. EDIFIER Sound To Go+                                                               | 1         | 0.49%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.49%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.49%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.49%   |
| Generalplus Technology Usb Audio Device                                                           | 1         | 0.49%   |
| C-Media Electronics Redragon Gaming Headset                                                       | 1         | 0.49%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.49%   |
| C-Media Electronics Audio Adapter                                                                 | 1         | 0.49%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.49%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.49%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.49%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.49%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 27.71%  |
| Kingston            | 18        | 21.69%  |
| SK Hynix            | 14        | 16.87%  |
| Micron Technology   | 7         | 8.43%   |
| Nanya Technology    | 6         | 7.23%   |
| Ramaxel Technology  | 4         | 4.82%   |
| A-DATA Technology   | 3         | 3.61%   |
| Crucial             | 2         | 2.41%   |
| Unknown (ABCD)      | 1         | 1.2%    |
| Unknown             | 1         | 1.2%    |
| Silicon Power       | 1         | 1.2%    |
| Kingmax             | 1         | 1.2%    |
| Elpida              | 1         | 1.2%    |
| Apacer              | 1         | 1.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 4         | 4.71%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4096MB SODIMM DDR3 1334MT/s             | 3         | 3.53%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 2.35%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 2         | 2.35%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 2.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 2.35%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 2         | 2.35%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.18%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 1.18%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.18%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.18%   |
| SK Hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1333MT/s              | 1         | 1.18%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s             | 1         | 1.18%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 1.18%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.18%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 1.18%   |
| SK Hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.18%   |
| Silicon Power RAM SP004GBSFU213N02 4GB SODIMM DDR4 2133MT/s         | 1         | 1.18%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s            | 1         | 1.18%   |
| Samsung RAM M471B5273DH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.18%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.18%   |
| Samsung RAM M471B2873EH1-CF8 1GB SODIMM DDR3 1067MT/s               | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 1.18%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.18%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.18%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.18%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.18%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.18%   |
| Samsung RAM M04GD08P1600C10 4096MB SODIMM DDR3 800MT/s              | 1         | 1.18%   |
| Samsung RAM 8G3200CL22 8192MB SODIMM DDR4 3200MT/s                  | 1         | 1.18%   |
| Samsung RAM 4D34373142353237 4GB SODIMM DDR3 1333MT/s               | 1         | 1.18%   |
| Samsung RAM 4D34373142323837 1GB SODIMM DDR3 1333MT/s               | 1         | 1.18%   |
| Samsung RAM 16G3200CL22 16GB SODIMM DDR4 3200MT/s                   | 1         | 1.18%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 1.18%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 1.18%   |
| Ramaxel RAM RMT3010KC58E8F1333 2GB SODIMM DDR3 1334MT/s             | 1         | 1.18%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s             | 1         | 1.18%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s                | 1         | 1.18%   |
| Nanya RAM NT2GC64B8HC0NS-BE 2GB SODIMM DDR3 1067MT/s                | 1         | 1.18%   |
| Nanya RAM M2S4G64CB8HG5N-CG 4GB SODIMM DDR3 1334MT/s                | 1         | 1.18%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 1         | 1.18%   |
| Micron RAM 8ATF51264HZ-2G1A1 4GB SODIMM DDR4 2133MT/s               | 1         | 1.18%   |
| Micron RAM 8ATF1G64HZ-2G3H1R 8GB SODIMM DDR4 2400MT/s               | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s               | 1         | 1.18%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.18%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 1         | 1.18%   |
| Kingston RAM Module 4096MB SODIMM DDR3 1333MT/s                     | 1         | 1.18%   |
| Kingston RAM Module 2GB SODIMM DDR 800MT/s                          | 1         | 1.18%   |
| Kingston RAM KNWMX1-HYA 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.18%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s             | 1         | 1.18%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s               | 1         | 1.18%   |
| Kingston RAM HP16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s               | 1         | 1.18%   |
| Kingston RAM 99U5624-001.A00G 8GB SODIMM DDR4 2400MT/s              | 1         | 1.18%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s             | 1         | 1.18%   |
| Kingston RAM 99U5428-082.A00LF 8GB SODIMM DDR3 1600MT/s             | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 34        | 54.84%  |
| DDR4   | 25        | 40.32%  |
| LPDDR4 | 1         | 1.61%   |
| LPDDR3 | 1         | 1.61%   |
| DDR    | 1         | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 98.39%  |
| Row Of Chips | 1         | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 36        | 50.7%   |
| 8192  | 17        | 23.94%  |
| 16384 | 7         | 9.86%   |
| 2048  | 6         | 8.45%   |
| 1024  | 3         | 4.23%   |
| 32768 | 2         | 2.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 20        | 27.78%  |
| 2667    | 13        | 18.06%  |
| 1334    | 12        | 16.67%  |
| 3200    | 8         | 11.11%  |
| 2400    | 4         | 5.56%   |
| 2133    | 4         | 5.56%   |
| 1333    | 4         | 5.56%   |
| 1067    | 3         | 4.17%   |
| 800     | 2         | 2.78%   |
| 3266    | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 66.67%  |
| Canon       | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson L210 Series    | 1         | 33.33%  |
| Seiko Epson ET-2710 Series | 1         | 33.33%  |
| Canon E410 series          | 1         | 33.33%  |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 23        | 19.01%  |
| Microdia                               | 14        | 11.57%  |
| Realtek Semiconductor                  | 12        | 9.92%   |
| IMC Networks                           | 12        | 9.92%   |
| Suyin                                  | 11        | 9.09%   |
| Acer                                   | 9         | 7.44%   |
| Sunplus Innovation Technology          | 8         | 6.61%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.96%   |
| Apple                                  | 5         | 4.13%   |
| Alcor Micro                            | 4         | 3.31%   |
| Quanta                                 | 3         | 2.48%   |
| Syntek                                 | 2         | 1.65%   |
| Lite-On Technology                     | 2         | 1.65%   |
| Generalplus Technology                 | 2         | 1.65%   |
| USB Camera                             | 1         | 0.83%   |
| Samsung Electronics                    | 1         | 0.83%   |
| Ricoh                                  | 1         | 0.83%   |
| Primax Electronics                     | 1         | 0.83%   |
| OmniVision Technologies                | 1         | 0.83%   |
| Luxvisions Innotech Limited            | 1         | 0.83%   |
| Logitech                               | 1         | 0.83%   |
| Lenovo                                 | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 4         | 3.31%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 3.31%   |
| Sunplus Integrated_Webcam_HD                            | 3         | 2.48%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 3         | 2.48%   |
| Chicony USB2.0 VGA UVC WebCam                           | 3         | 2.48%   |
| Chicony USB2.0 HD UVC WebCam                            | 3         | 2.48%   |
| Chicony HP HD Webcam                                    | 3         | 2.48%   |
| Chicony HD WebCam                                       | 3         | 2.48%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 2.48%   |
| Apple FaceTime HD Camera                                | 3         | 2.48%   |
| Acer Lenovo Integrated Webcam                           | 3         | 2.48%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 2         | 1.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 1.65%   |
| Suyin 1.3M HD WebCam                                    | 2         | 1.65%   |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 1.65%   |
| Realtek USB Camera                                      | 2         | 1.65%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.65%   |
| Realtek HD WebCam                                       | 2         | 1.65%   |
| Microdia USB 2.0 Camera                                 | 2         | 1.65%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.65%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.65%   |
| Chicony Integrated Camera                               | 2         | 1.65%   |
| Alcor Micro Asus Integrated Webcam                      | 2         | 1.65%   |
| Acer BisonCam,NB Pro                                    | 2         | 1.65%   |
| USB Camera USB Camera                                   | 1         | 0.83%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.83%   |
| Syntek Laptop_Integrated_Webcam_1.3M                    | 1         | 0.83%   |
| Suyin Webcam-101                                        | 1         | 0.83%   |
| Suyin WebCam                                            | 1         | 0.83%   |
| Suyin Integrated Webcam                                 | 1         | 0.83%   |
| Suyin HP Webcam-101                                     | 1         | 0.83%   |
| Suyin HP TrueVision HD                                  | 1         | 0.83%   |
| Sunplus Laptop Integrated Webcam HD                     | 1         | 0.83%   |
| Sunplus Laptop Integrated Webcam FHD                    | 1         | 0.83%   |
| Sunplus Dell HD Webcam                                  | 1         | 0.83%   |
| Samsung Galaxy A5 (MTP)                                 | 1         | 0.83%   |
| Ricoh Sony Vaio Integrated Webcam                       | 1         | 0.83%   |
| Realtek USB2.0 HD UVC WebCam                            | 1         | 0.83%   |
| Realtek USB HD Webcam                                   | 1         | 0.83%   |
| Realtek Lenovo EasyCamera                               | 1         | 0.83%   |
| Realtek Integrated Webcam_HD                            | 1         | 0.83%   |
| Realtek HP Truevision HD                                | 1         | 0.83%   |
| Realtek Acer 640 x 480 laptop camera                    | 1         | 0.83%   |
| Quanta HP Wide Vision HD Camera                         | 1         | 0.83%   |
| Quanta HP TrueVision HD Camera                          | 1         | 0.83%   |
| Quanta HD User Facing                                   | 1         | 0.83%   |
| Primax HP HD Webcam [Fixed]                             | 1         | 0.83%   |
| OmniVision OV2640 Webcam                                | 1         | 0.83%   |
| Microdia Webcam Vitade AF                               | 1         | 0.83%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam          | 1         | 0.83%   |
| Microdia Laptop_Integrated_Webcam_1.3M                  | 1         | 0.83%   |
| Microdia Integrated Webcam                              | 1         | 0.83%   |
| Microdia Dell Integrated HD Webcam                      | 1         | 0.83%   |
| Microdia 1.3 MPixel Integrated Webcam                   | 1         | 0.83%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 1         | 0.83%   |
| Logitech HD Webcam C615                                 | 1         | 0.83%   |
| Lite-On Integrated Camera                               | 1         | 0.83%   |
| Lite-On HP Wide Vision HD Camera                        | 1         | 0.83%   |
| Lenovo Integrated Webcam                                | 1         | 0.83%   |
| IMC Networks UVC VGA Webcam                             | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 30%     |
| Shenzhen Goodix Technology | 4         | 20%     |
| Upek                       | 2         | 10%     |
| Synaptics                  | 2         | 10%     |
| Elan Microelectronics      | 2         | 10%     |
| AuthenTec                  | 2         | 10%     |
| LighTuning Technology      | 1         | 5%      |
| Focal-systems.Corp         | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                     | 3         | 15%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS491                                | 1         | 5%      |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5%      |
| Validity Sensors Fingerprint scanner                   | 1         | 5%      |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 5%      |
| Shenzhen Goodix FingerPrint                            | 1         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5%      |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 5%      |
| Elan ELAN:Fingerprint                                  | 1         | 5%      |
| Elan ELAN:ARM-M4                                       | 1         | 5%      |
| AuthenTec Fingerprint Sensor                           | 1         | 5%      |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 5%      |
| Unknown                                                | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 66.67%  |
| O2 Micro    | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 33.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 99        | 69.72%  |
| 1     | 36        | 25.35%  |
| 2     | 7         | 4.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 20        | 42.55%  |
| Net/wireless          | 8         | 17.02%  |
| Graphics card         | 6         | 12.77%  |
| Chipcard              | 4         | 8.51%   |
| Multimedia controller | 3         | 6.38%   |
| Bluetooth             | 3         | 6.38%   |
| Storage               | 2         | 4.26%   |
| Card reader           | 1         | 2.13%   |

