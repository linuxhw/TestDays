Linux in Chile - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Chile.

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

Total: 676

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3501               | [4684b672f6](https://linux-hardware.org/?probe=4684b672f6) | Sep 30, 2022 |
| SK hynix      | HyBook                      | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| Dell          | Inspiron 3501               | [ce2d41ee99](https://linux-hardware.org/?probe=ce2d41ee99) | Sep 30, 2022 |
| Samsung       | R430/P430/R480              | [09795617ab](https://linux-hardware.org/?probe=09795617ab) | Sep 30, 2022 |
| AMI           | Cherry Trail CR             | [58caf99a77](https://linux-hardware.org/?probe=58caf99a77) | Sep 29, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [bd2dea6653](https://linux-hardware.org/?probe=bd2dea6653) | Sep 29, 2022 |
| AMI           | Cherry Trail CR             | [2d55b9b35e](https://linux-hardware.org/?probe=2d55b9b35e) | Sep 28, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [01cf3c6f99](https://linux-hardware.org/?probe=01cf3c6f99) | Sep 26, 2022 |
| HP            | Pavilion 15                 | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [7dc3fbcf76](https://linux-hardware.org/?probe=7dc3fbcf76) | Sep 21, 2022 |
| Dell          | Latitude 7490               | [b8c3a5519a](https://linux-hardware.org/?probe=b8c3a5519a) | Sep 21, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [277daa8d6d](https://linux-hardware.org/?probe=277daa8d6d) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [2ac6776181](https://linux-hardware.org/?probe=2ac6776181) | Sep 13, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6f309073f2](https://linux-hardware.org/?probe=6f309073f2) | Sep 11, 2022 |
| Acer          | Aspire A315-42              | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f19e04efc1](https://linux-hardware.org/?probe=f19e04efc1) | Sep 10, 2022 |
| MSI           | Modern 14 B5M               | [b11b5bcba5](https://linux-hardware.org/?probe=b11b5bcba5) | Sep 09, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | [c1a16c7963](https://linux-hardware.org/?probe=c1a16c7963) | Sep 06, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | [2ae4968612](https://linux-hardware.org/?probe=2ae4968612) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L6S80G00    | [bd599c876c](https://linux-hardware.org/?probe=bd599c876c) | Sep 02, 2022 |
| HP            | Laptop 14-dq2xxx            | [bc4f5f8811](https://linux-hardware.org/?probe=bc4f5f8811) | Aug 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [7169cd34ab](https://linux-hardware.org/?probe=7169cd34ab) | Aug 22, 2022 |
| HP            | Pavilion g4                 | [f8c2fc628e](https://linux-hardware.org/?probe=f8c2fc628e) | Aug 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [59080cc039](https://linux-hardware.org/?probe=59080cc039) | Aug 17, 2022 |
| HP            | Laptop 14-dq2xxx            | [9cefc23bb3](https://linux-hardware.org/?probe=9cefc23bb3) | Aug 17, 2022 |
| Lenovo        | IdeaPad S540-13IML 81XA     | [9ee2e85959](https://linux-hardware.org/?probe=9ee2e85959) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | [fcdd677280](https://linux-hardware.org/?probe=fcdd677280) | Aug 14, 2022 |
| A-DATA Tec... | XENIA 14                    | [51cc14cc1f](https://linux-hardware.org/?probe=51cc14cc1f) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | [eeed6b3d08](https://linux-hardware.org/?probe=eeed6b3d08) | Aug 14, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [818d0c73e8](https://linux-hardware.org/?probe=818d0c73e8) | Aug 12, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [efd4ec3ee7](https://linux-hardware.org/?probe=efd4ec3ee7) | Aug 11, 2022 |
| HP            | TouchSmart tm2              | [541d75d7ee](https://linux-hardware.org/?probe=541d75d7ee) | Aug 11, 2022 |
| HP            | TouchSmart tm2              | [77b260c9f1](https://linux-hardware.org/?probe=77b260c9f1) | Aug 11, 2022 |
| HP            | 240 G3                      | [77225815d2](https://linux-hardware.org/?probe=77225815d2) | Aug 10, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [832967e639](https://linux-hardware.org/?probe=832967e639) | Aug 09, 2022 |
| Google        | Treeya                      | [11f77c6171](https://linux-hardware.org/?probe=11f77c6171) | Aug 08, 2022 |
| Render        | NOTEBOOK Revision A         | [90a540652f](https://linux-hardware.org/?probe=90a540652f) | Aug 06, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [53c997fe1f](https://linux-hardware.org/?probe=53c997fe1f) | Aug 05, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [764d4ebd1b](https://linux-hardware.org/?probe=764d4ebd1b) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [5dab148c3e](https://linux-hardware.org/?probe=5dab148c3e) | Aug 04, 2022 |
| MOTILE        | M141                        | [7cdc678c70](https://linux-hardware.org/?probe=7cdc678c70) | Aug 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Sony          | VPCEA45FL                   | [8079ec1351](https://linux-hardware.org/?probe=8079ec1351) | Jul 29, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a58ae4eb60](https://linux-hardware.org/?probe=a58ae4eb60) | Jul 24, 2022 |
| ASUSTek       | X541NA                      | [51aefa0464](https://linux-hardware.org/?probe=51aefa0464) | Jul 21, 2022 |
| Samsung       | 750XED                      | [546562ffbb](https://linux-hardware.org/?probe=546562ffbb) | Jul 21, 2022 |
| HP            | 245 G2                      | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| Dell          | MXG061                      | [9301162b93](https://linux-hardware.org/?probe=9301162b93) | Jul 18, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | [75cfb6ffa8](https://linux-hardware.org/?probe=75cfb6ffa8) | Jul 17, 2022 |
| HP            | 245 G2                      | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Samsung       | 750XED                      | [eb7c27f7ff](https://linux-hardware.org/?probe=eb7c27f7ff) | Jul 15, 2022 |
| HP            | Pavilion g4                 | [40067cace0](https://linux-hardware.org/?probe=40067cace0) | Jul 14, 2022 |
| HP            | Pavilion g4                 | [26859467e9](https://linux-hardware.org/?probe=26859467e9) | Jul 14, 2022 |
| HP            | Laptop 14-fq0xxx            | [c21113bf90](https://linux-hardware.org/?probe=c21113bf90) | Jul 14, 2022 |
| Lenovo        | ThinkPad P50 20EQA05JCL     | [43f5b3c05d](https://linux-hardware.org/?probe=43f5b3c05d) | Jul 13, 2022 |
| HP            | Notebook                    | [1358a12fdf](https://linux-hardware.org/?probe=1358a12fdf) | Jul 13, 2022 |
| HP            | Pavilion g4                 | [96ba266748](https://linux-hardware.org/?probe=96ba266748) | Jul 11, 2022 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [269ebd1a4d](https://linux-hardware.org/?probe=269ebd1a4d) | Jul 09, 2022 |
| Lenovo        | ThinkPad T61 6457B5S        | [34e97dae1e](https://linux-hardware.org/?probe=34e97dae1e) | Jul 08, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [bcb40b4a21](https://linux-hardware.org/?probe=bcb40b4a21) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c8b9e41a50](https://linux-hardware.org/?probe=c8b9e41a50) | Jul 06, 2022 |
| HP            | Compaq 15                   | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | [5b8770aaf7](https://linux-hardware.org/?probe=5b8770aaf7) | Jun 27, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | [d80f5059d2](https://linux-hardware.org/?probe=d80f5059d2) | Jun 27, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | [89b9650228](https://linux-hardware.org/?probe=89b9650228) | Jun 27, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b56f69ff9c](https://linux-hardware.org/?probe=b56f69ff9c) | Jun 26, 2022 |
| Dell          | Inspiron 3505               | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| Samsung       | 750XED                      | [49322b3456](https://linux-hardware.org/?probe=49322b3456) | Jun 21, 2022 |
| Dell          | XPS 12 9Q23                 | [463461920a](https://linux-hardware.org/?probe=463461920a) | Jun 21, 2022 |
| Packard Be... | EasyNote MH36               | [ecd7a50e8e](https://linux-hardware.org/?probe=ecd7a50e8e) | Jun 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [bbb3795dc2](https://linux-hardware.org/?probe=bbb3795dc2) | Jun 20, 2022 |
| HP            | Laptop 14-ck0xxx            | [234a9c1523](https://linux-hardware.org/?probe=234a9c1523) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cb268bf1ab](https://linux-hardware.org/?probe=cb268bf1ab) | Jun 18, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [7d8683dfac](https://linux-hardware.org/?probe=7d8683dfac) | Jun 16, 2022 |
| Dell          | XPS 12 9Q23                 | [77c4dc4a62](https://linux-hardware.org/?probe=77c4dc4a62) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | [cf08ff4333](https://linux-hardware.org/?probe=cf08ff4333) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | [4b4bd76de7](https://linux-hardware.org/?probe=4b4bd76de7) | Jun 14, 2022 |
| Sony          | VPCM120AL                   | [9eb0e19bd0](https://linux-hardware.org/?probe=9eb0e19bd0) | Jun 13, 2022 |
| HP            | 240 G7                      | [2af5911cf8](https://linux-hardware.org/?probe=2af5911cf8) | Jun 12, 2022 |
| HP            | 240 G7                      | [bf52288eb2](https://linux-hardware.org/?probe=bf52288eb2) | Jun 10, 2022 |
| HP            | EliteBook 840 G5            | [73ba6fe3c0](https://linux-hardware.org/?probe=73ba6fe3c0) | Jun 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [83b786e73a](https://linux-hardware.org/?probe=83b786e73a) | Jun 04, 2022 |
| MSI           | Bravo 15 B5DD               | [d561d8dbdb](https://linux-hardware.org/?probe=d561d8dbdb) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| HP            | EliteBook 2560p             | [4ad762abcb](https://linux-hardware.org/?probe=4ad762abcb) | May 31, 2022 |
| HP            | 240 G7                      | [687546391a](https://linux-hardware.org/?probe=687546391a) | May 23, 2022 |
| Dell          | Inspiron 5459               | [ea99252046](https://linux-hardware.org/?probe=ea99252046) | May 20, 2022 |
| Unknown       | Unknown                     | [834d86e9da](https://linux-hardware.org/?probe=834d86e9da) | May 17, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [be93982cf0](https://linux-hardware.org/?probe=be93982cf0) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [84ae0966e6](https://linux-hardware.org/?probe=84ae0966e6) | May 15, 2022 |
| HP            | EliteBook 840 G3            | [a7fb96d9aa](https://linux-hardware.org/?probe=a7fb96d9aa) | May 13, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [74d92cc46f](https://linux-hardware.org/?probe=74d92cc46f) | May 11, 2022 |
| LG Electro... | 15Z995-U.ARS5U1             | [4efbc907db](https://linux-hardware.org/?probe=4efbc907db) | May 11, 2022 |
| Acer          | Aspire R7-371T              | [207110a3d4](https://linux-hardware.org/?probe=207110a3d4) | May 07, 2022 |
| HP            | EliteBook 2560p             | [c275c52e93](https://linux-hardware.org/?probe=c275c52e93) | May 04, 2022 |
| HP            | EliteBook 2560p             | [799038a9eb](https://linux-hardware.org/?probe=799038a9eb) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| HP            | Pavilion g4                 | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| Lenovo        | ThinkPad T61 7659A39        | [e5c32846e2](https://linux-hardware.org/?probe=e5c32846e2) | Apr 30, 2022 |
| Acer          | Aspire E5-411G              | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| HP            | Pavilion 14                 | [84bde5e223](https://linux-hardware.org/?probe=84bde5e223) | Apr 29, 2022 |
| HP            | Pavilion g4                 | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| Intel         | Unknown                     | [41b673dda8](https://linux-hardware.org/?probe=41b673dda8) | Apr 26, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [6fbbf00053](https://linux-hardware.org/?probe=6fbbf00053) | Apr 23, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [6dac014a49](https://linux-hardware.org/?probe=6dac014a49) | Apr 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [4e2119abc8](https://linux-hardware.org/?probe=4e2119abc8) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d43a69ef63](https://linux-hardware.org/?probe=d43a69ef63) | Apr 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [28897f0c7b](https://linux-hardware.org/?probe=28897f0c7b) | Apr 13, 2022 |
| ASUSTek       | X405UQ                      | [4b63447e77](https://linux-hardware.org/?probe=4b63447e77) | Apr 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [4c367d8a9c](https://linux-hardware.org/?probe=4c367d8a9c) | Apr 08, 2022 |
| Dell          | Vostro A860                 | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4ad9fe021c](https://linux-hardware.org/?probe=4ad9fe021c) | Mar 31, 2022 |
| Dell          | Latitude E5450              | [776f0672a0](https://linux-hardware.org/?probe=776f0672a0) | Mar 23, 2022 |
| Dell          | Latitude E5450              | [fb7f18d5a2](https://linux-hardware.org/?probe=fb7f18d5a2) | Mar 23, 2022 |
| HUAWEI        | KLVL-WXX9                   | [95acb8d0af](https://linux-hardware.org/?probe=95acb8d0af) | Mar 21, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [95c6b15672](https://linux-hardware.org/?probe=95c6b15672) | Mar 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [82cfb46909](https://linux-hardware.org/?probe=82cfb46909) | Mar 13, 2022 |
| Packard Be... | EasyNote MH35               | [66bff1bcfd](https://linux-hardware.org/?probe=66bff1bcfd) | Mar 08, 2022 |
| ASUSTek       | G752VY                      | [379733b3e7](https://linux-hardware.org/?probe=379733b3e7) | Mar 07, 2022 |
| Elife         | series                      | [dddf04aa69](https://linux-hardware.org/?probe=dddf04aa69) | Mar 05, 2022 |
| Elife         | series                      | [979e43c05a](https://linux-hardware.org/?probe=979e43c05a) | Mar 05, 2022 |
| HP            | 2140                        | [6956607bfd](https://linux-hardware.org/?probe=6956607bfd) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2f1bb56767](https://linux-hardware.org/?probe=2f1bb56767) | Feb 28, 2022 |
| Lenovo        | ThinkPad T490 20RXS0VX00    | [8f42f6fd5f](https://linux-hardware.org/?probe=8f42f6fd5f) | Feb 28, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [8dfdb07f98](https://linux-hardware.org/?probe=8dfdb07f98) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Lenovo        | ThinkPad T495 20NJ0004US    | [d8002e9eae](https://linux-hardware.org/?probe=d8002e9eae) | Feb 23, 2022 |
| Google        | Barla                       | [12180ab1ff](https://linux-hardware.org/?probe=12180ab1ff) | Feb 22, 2022 |
| Toshiba       | Satellite L505              | [16e608fb6b](https://linux-hardware.org/?probe=16e608fb6b) | Feb 22, 2022 |
| HP            | ENVY 15                     | [9758bb9b66](https://linux-hardware.org/?probe=9758bb9b66) | Feb 20, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [46021e669f](https://linux-hardware.org/?probe=46021e669f) | Feb 17, 2022 |
| Apple         | MacBookPro11,3              | [4de3659979](https://linux-hardware.org/?probe=4de3659979) | Feb 16, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [c81bbf6c93](https://linux-hardware.org/?probe=c81bbf6c93) | Feb 16, 2022 |
| Apple         | MacBookPro11,3              | [309f440466](https://linux-hardware.org/?probe=309f440466) | Feb 15, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [81f2a365be](https://linux-hardware.org/?probe=81f2a365be) | Feb 13, 2022 |
| HP            | Laptop 15-da0xxx            | [18fa19a4f0](https://linux-hardware.org/?probe=18fa19a4f0) | Feb 10, 2022 |
| HP            | EliteBook 840 G6            | [dae40dba1f](https://linux-hardware.org/?probe=dae40dba1f) | Feb 09, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3060acc083](https://linux-hardware.org/?probe=3060acc083) | Jan 22, 2022 |
| Acer          | Aspire ES1-111M             | [02368f5bb1](https://linux-hardware.org/?probe=02368f5bb1) | Jan 22, 2022 |
| Lenovo        | G400 20235                  | [cba5cda239](https://linux-hardware.org/?probe=cba5cda239) | Jan 21, 2022 |
| HP            | Laptop 15-da1xxx            | [d6706833ff](https://linux-hardware.org/?probe=d6706833ff) | Jan 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [c00dd7c570](https://linux-hardware.org/?probe=c00dd7c570) | Jan 18, 2022 |
| Dell          | Inspiron 3480               | [ca729da91f](https://linux-hardware.org/?probe=ca729da91f) | Jan 16, 2022 |
| Lenovo        | ThinkPad T480 20L6A0UGCL    | [e9dbb29c83](https://linux-hardware.org/?probe=e9dbb29c83) | Jan 16, 2022 |
| Acer          | AOD255E                     | [cf1f3ab0e0](https://linux-hardware.org/?probe=cf1f3ab0e0) | Jan 13, 2022 |
| HP            | Pavilion 15                 | [95f3d87b66](https://linux-hardware.org/?probe=95f3d87b66) | Jan 09, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [edc40344ef](https://linux-hardware.org/?probe=edc40344ef) | Jan 08, 2022 |
| HONOR         | NBR-WAX9                    | [979f80197d](https://linux-hardware.org/?probe=979f80197d) | Jan 07, 2022 |
| Sony          | SVE14A390X                  | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | EliteBook 6930p             | [0346ff374d](https://linux-hardware.org/?probe=0346ff374d) | Dec 26, 2021 |
| Acer          | Aspire E1-531               | [d1d6054fc3](https://linux-hardware.org/?probe=d1d6054fc3) | Dec 22, 2021 |
| Google        | Barla                       | [cfdb4935cd](https://linux-hardware.org/?probe=cfdb4935cd) | Dec 21, 2021 |
| Google        | Barla                       | [0629410759](https://linux-hardware.org/?probe=0629410759) | Dec 21, 2021 |
| HP            | EliteBook 840 G6            | [46dab8c74a](https://linux-hardware.org/?probe=46dab8c74a) | Dec 16, 2021 |
| Samsung       | R510/P510                   | [37a9793570](https://linux-hardware.org/?probe=37a9793570) | Dec 08, 2021 |
| Dell          | Inspiron 14-3467            | [c53e56384e](https://linux-hardware.org/?probe=c53e56384e) | Dec 07, 2021 |
| Samsung       | R510/P510                   | [f55c0c88cc](https://linux-hardware.org/?probe=f55c0c88cc) | Dec 07, 2021 |
| Lenovo        | ThinkPad T460 20FMA03MCL    | [aecb392c83](https://linux-hardware.org/?probe=aecb392c83) | Dec 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [18da52385a](https://linux-hardware.org/?probe=18da52385a) | Dec 04, 2021 |
| Acer          | Swift SF113-31              | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Dell          | Inspiron M5010              | [489679b294](https://linux-hardware.org/?probe=489679b294) | Nov 27, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | [93b6cabcb6](https://linux-hardware.org/?probe=93b6cabcb6) | Nov 25, 2021 |
| HP            | 245 G6                      | [103da5dd76](https://linux-hardware.org/?probe=103da5dd76) | Nov 25, 2021 |
| Acer          | Aspire V5-471P              | [bf3b81cbb6](https://linux-hardware.org/?probe=bf3b81cbb6) | Nov 20, 2021 |
| HP            | 250 G5 Notebook PC          | [befb5b9afe](https://linux-hardware.org/?probe=befb5b9afe) | Nov 18, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [787fc2d581](https://linux-hardware.org/?probe=787fc2d581) | Nov 18, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [d26e2fac89](https://linux-hardware.org/?probe=d26e2fac89) | Nov 17, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [10a3cb9d12](https://linux-hardware.org/?probe=10a3cb9d12) | Nov 15, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | [d0f383a016](https://linux-hardware.org/?probe=d0f383a016) | Nov 13, 2021 |
| Unknown       | Unknown                     | [a61385548e](https://linux-hardware.org/?probe=a61385548e) | Nov 13, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [8b26cea464](https://linux-hardware.org/?probe=8b26cea464) | Nov 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [835c948f68](https://linux-hardware.org/?probe=835c948f68) | Nov 13, 2021 |
| Samsung       | 550P5C/550P7C               | [31bc59dcb9](https://linux-hardware.org/?probe=31bc59dcb9) | Nov 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [ab746b7399](https://linux-hardware.org/?probe=ab746b7399) | Nov 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [258e2f1594](https://linux-hardware.org/?probe=258e2f1594) | Nov 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1dd0c3ba0a](https://linux-hardware.org/?probe=1dd0c3ba0a) | Nov 05, 2021 |
| HP            | 250 G5 Notebook PC          | [d6eff141a3](https://linux-hardware.org/?probe=d6eff141a3) | Nov 04, 2021 |
| Acer          | Aspire ES1-311              | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| Dell          | Vostro 3500                 | [befb41472e](https://linux-hardware.org/?probe=befb41472e) | Oct 23, 2021 |
| Samsung       | 550P5C/550P7C               | [2713972f14](https://linux-hardware.org/?probe=2713972f14) | Oct 22, 2021 |
| HP            | 250 G6 Notebook PC          | [7076268ecc](https://linux-hardware.org/?probe=7076268ecc) | Oct 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f7524634b9](https://linux-hardware.org/?probe=f7524634b9) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | [e51cebc629](https://linux-hardware.org/?probe=e51cebc629) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | [18a1e9d294](https://linux-hardware.org/?probe=18a1e9d294) | Oct 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [06b7518f72](https://linux-hardware.org/?probe=06b7518f72) | Oct 14, 2021 |
| Acer          | Aspire ES1-311              | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | [a0e3e93f48](https://linux-hardware.org/?probe=a0e3e93f48) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | [ad35db71c7](https://linux-hardware.org/?probe=ad35db71c7) | Oct 12, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| HP            | Notebook                    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | Notebook                    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Alienware     | M17xR3                      | [740de1796c](https://linux-hardware.org/?probe=740de1796c) | Oct 05, 2021 |
| Dell          | Inspiron N5110              | [8ea6adfced](https://linux-hardware.org/?probe=8ea6adfced) | Oct 03, 2021 |
| ASUSTek       | X555LB                      | [3af223c792](https://linux-hardware.org/?probe=3af223c792) | Sep 30, 2021 |
| Dell          | G3 3590                     | [519cea3f38](https://linux-hardware.org/?probe=519cea3f38) | Sep 25, 2021 |
| Dell          | G3 3590                     | [bb25c895cf](https://linux-hardware.org/?probe=bb25c895cf) | Sep 25, 2021 |
| ASUSTek       | X302LJ                      | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Acer          | Aspire ES1-572              | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [079bf76915](https://linux-hardware.org/?probe=079bf76915) | Sep 18, 2021 |
| HP            | EliteBook 840 G5            | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Inspiron 5459               | [ef87caa5ba](https://linux-hardware.org/?probe=ef87caa5ba) | Sep 12, 2021 |
| Dell          | Inspiron 5459               | [feea6f3fec](https://linux-hardware.org/?probe=feea6f3fec) | Sep 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [15ed5db330](https://linux-hardware.org/?probe=15ed5db330) | Sep 09, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | [890790d388](https://linux-hardware.org/?probe=890790d388) | Sep 07, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | [341d88eae9](https://linux-hardware.org/?probe=341d88eae9) | Sep 07, 2021 |
| Dell          | Inspiron N5110              | [a8f9c859be](https://linux-hardware.org/?probe=a8f9c859be) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | [3c5b6aa997](https://linux-hardware.org/?probe=3c5b6aa997) | Sep 05, 2021 |
| Acer          | Swift SF314-59              | [f6df33267b](https://linux-hardware.org/?probe=f6df33267b) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | [436287e7dc](https://linux-hardware.org/?probe=436287e7dc) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | [a89f3e4acf](https://linux-hardware.org/?probe=a89f3e4acf) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [93a7aa0485](https://linux-hardware.org/?probe=93a7aa0485) | Aug 31, 2021 |
| Apple         | MacBookPro11,1              | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Toshiba       | Satellite C845D             | [ac992ef3e5](https://linux-hardware.org/?probe=ac992ef3e5) | Aug 29, 2021 |
| Lenovo        | ThinkPad X260 20F5S3J00D    | [eeb6586c28](https://linux-hardware.org/?probe=eeb6586c28) | Aug 26, 2021 |
| Sony          | VGN-NW215T                  | [3b59710f01](https://linux-hardware.org/?probe=3b59710f01) | Aug 25, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [207f0c8966](https://linux-hardware.org/?probe=207f0c8966) | Aug 24, 2021 |
| Acer          | Aspire 7741                 | [849c1fe7e3](https://linux-hardware.org/?probe=849c1fe7e3) | Aug 22, 2021 |
| HP            | ProBook 440 G3              | [80aa412668](https://linux-hardware.org/?probe=80aa412668) | Aug 22, 2021 |
| Lenovo        | V145-15AST 81MT             | [28d8feb60d](https://linux-hardware.org/?probe=28d8feb60d) | Aug 20, 2021 |
| Lenovo        | V145-15AST 81MT             | [f207dc8e9a](https://linux-hardware.org/?probe=f207dc8e9a) | Aug 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [ab27a12603](https://linux-hardware.org/?probe=ab27a12603) | Aug 18, 2021 |
| Dell          | Inspiron 5459               | [b99b48660a](https://linux-hardware.org/?probe=b99b48660a) | Aug 08, 2021 |
| Sony          | SVE14A27CLS                 | [53a5965063](https://linux-hardware.org/?probe=53a5965063) | Aug 07, 2021 |
| HP            | ProBook 640 G1              | [4d0bb591af](https://linux-hardware.org/?probe=4d0bb591af) | Aug 06, 2021 |
| Dell          | G3 3590                     | [16bdb588e1](https://linux-hardware.org/?probe=16bdb588e1) | Aug 05, 2021 |
| Dell          | G3 3590                     | [01a9560f9c](https://linux-hardware.org/?probe=01a9560f9c) | Aug 05, 2021 |
| Packard Be... | EasyNote MH35               | [e053c132dc](https://linux-hardware.org/?probe=e053c132dc) | Aug 02, 2021 |
| Dell          | Inspiron 5459               | [acc597c748](https://linux-hardware.org/?probe=acc597c748) | Aug 02, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2e753f12ce](https://linux-hardware.org/?probe=2e753f12ce) | Jul 28, 2021 |
| Medion        | Unknown                     | [021ba4d5b5](https://linux-hardware.org/?probe=021ba4d5b5) | Jul 25, 2021 |
| Medion        | Unknown                     | [e9c5e99e0b](https://linux-hardware.org/?probe=e9c5e99e0b) | Jul 25, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1d0f458592](https://linux-hardware.org/?probe=1d0f458592) | Jul 23, 2021 |
| Acer          | Swift SF314-42              | [f8812e14cb](https://linux-hardware.org/?probe=f8812e14cb) | Jul 23, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [0d3be70373](https://linux-hardware.org/?probe=0d3be70373) | Jul 20, 2021 |
| HP            | ENVY 15                     | [d2a3149a9a](https://linux-hardware.org/?probe=d2a3149a9a) | Jul 17, 2021 |
| HP            | ProBook 640 G1              | [2db57969aa](https://linux-hardware.org/?probe=2db57969aa) | Jul 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| HP            | Spectre Laptop 13-af0xx     | [bfef4cded0](https://linux-hardware.org/?probe=bfef4cded0) | Jul 09, 2021 |
| Lenovo        | G40-30 80FY                 | [ef9a6d3444](https://linux-hardware.org/?probe=ef9a6d3444) | Jul 08, 2021 |
| HP            | Notebook                    | [3087e92283](https://linux-hardware.org/?probe=3087e92283) | Jun 29, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [48a1dddc38](https://linux-hardware.org/?probe=48a1dddc38) | Jun 27, 2021 |
| ASUSTek       | N551JX                      | [3ef394cafb](https://linux-hardware.org/?probe=3ef394cafb) | Jun 24, 2021 |
| Toshiba       | PORTEGE R705                | [fe7063735e](https://linux-hardware.org/?probe=fe7063735e) | Jun 24, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [9d80703f35](https://linux-hardware.org/?probe=9d80703f35) | Jun 23, 2021 |
| Dell          | Inspiron 5459               | [22f31e0de1](https://linux-hardware.org/?probe=22f31e0de1) | Jun 19, 2021 |
| Toshiba       | PORTEGE R705                | [a53fb9eb09](https://linux-hardware.org/?probe=a53fb9eb09) | Jun 19, 2021 |
| HP            | Notebook                    | [f1263ec1fc](https://linux-hardware.org/?probe=f1263ec1fc) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | [6529cc537c](https://linux-hardware.org/?probe=6529cc537c) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | [2aa173f32b](https://linux-hardware.org/?probe=2aa173f32b) | Jun 12, 2021 |
| Unknown       | Unknown                     | [16d75c0003](https://linux-hardware.org/?probe=16d75c0003) | Jun 11, 2021 |
| Samsung       | 670Z5E                      | [252e20c152](https://linux-hardware.org/?probe=252e20c152) | Jun 11, 2021 |
| Dell          | Inspiron 5567               | [0ffe39ef8d](https://linux-hardware.org/?probe=0ffe39ef8d) | Jun 09, 2021 |
| Sony          | SVE14113ELW                 | [738c72c21c](https://linux-hardware.org/?probe=738c72c21c) | Jun 09, 2021 |
| HP            | ENVY 15                     | [8d7a772e05](https://linux-hardware.org/?probe=8d7a772e05) | Jun 07, 2021 |
| Dell          | Precision 5520              | [199dec46c7](https://linux-hardware.org/?probe=199dec46c7) | Jun 01, 2021 |
| HP            | 1000                        | [21fb6389e7](https://linux-hardware.org/?probe=21fb6389e7) | Jun 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b1500a1319](https://linux-hardware.org/?probe=b1500a1319) | May 28, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [abc55fc46d](https://linux-hardware.org/?probe=abc55fc46d) | May 28, 2021 |
| Personal C... | Iris                        | [835df5c61e](https://linux-hardware.org/?probe=835df5c61e) | May 27, 2021 |
| Toshiba       | PORTEGE R705                | [afd83c5750](https://linux-hardware.org/?probe=afd83c5750) | May 25, 2021 |
| Acer          | Swift SF313-53              | [66e4f1aeff](https://linux-hardware.org/?probe=66e4f1aeff) | May 23, 2021 |
| Unknown       | Unknown                     | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite L45-B             | [544d468137](https://linux-hardware.org/?probe=544d468137) | May 16, 2021 |
| HP            | 435                         | [65bbde1e13](https://linux-hardware.org/?probe=65bbde1e13) | May 16, 2021 |
| HP            | 435                         | [fe5a82cf02](https://linux-hardware.org/?probe=fe5a82cf02) | May 16, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [a98d93888d](https://linux-hardware.org/?probe=a98d93888d) | May 14, 2021 |
| Dell          | Latitude 7490               | [c533165389](https://linux-hardware.org/?probe=c533165389) | May 13, 2021 |
| Samsung       | RF712                       | [a3624b29fa](https://linux-hardware.org/?probe=a3624b29fa) | May 11, 2021 |
| Samsung       | RF712                       | [652fb28adb](https://linux-hardware.org/?probe=652fb28adb) | May 11, 2021 |
| Acer          | Swift SF313-53              | [2e4262cb53](https://linux-hardware.org/?probe=2e4262cb53) | May 11, 2021 |
| Dell          | Inspiron 5567               | [aacf9438d2](https://linux-hardware.org/?probe=aacf9438d2) | May 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [2196430972](https://linux-hardware.org/?probe=2196430972) | May 09, 2021 |
| HP            | EliteBook 840 G6            | [08d59f23ab](https://linux-hardware.org/?probe=08d59f23ab) | May 09, 2021 |
| HP            | 1000                        | [4205750e24](https://linux-hardware.org/?probe=4205750e24) | May 08, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ce41256b96](https://linux-hardware.org/?probe=ce41256b96) | May 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [566133628f](https://linux-hardware.org/?probe=566133628f) | May 07, 2021 |
| Toshiba       | Satellite U505              | [50baa8508f](https://linux-hardware.org/?probe=50baa8508f) | May 05, 2021 |
| Toshiba       | Satellite U505              | [c5785176bd](https://linux-hardware.org/?probe=c5785176bd) | May 05, 2021 |
| Packard Be... | EasyNote TM98               | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| HUAWEI        | WRTB-WXX9                   | [f9ceb7c523](https://linux-hardware.org/?probe=f9ceb7c523) | May 02, 2021 |
| Dell          | Latitude D630               | [40a03f054f](https://linux-hardware.org/?probe=40a03f054f) | May 02, 2021 |
| Acer          | Aspire ES1-431              | [cc8dd98cc6](https://linux-hardware.org/?probe=cc8dd98cc6) | May 01, 2021 |
| HP            | 14                          | [f2874ea965](https://linux-hardware.org/?probe=f2874ea965) | May 01, 2021 |
| HP            | ENVY 17 Leap Motion SE N... | [18b8d3d480](https://linux-hardware.org/?probe=18b8d3d480) | Apr 30, 2021 |
| HP            | Pavilion dm4                | [dd8938cac1](https://linux-hardware.org/?probe=dd8938cac1) | Apr 29, 2021 |
| Dell          | System Inspiron N4110       | [17b9bc8eb3](https://linux-hardware.org/?probe=17b9bc8eb3) | Apr 27, 2021 |
| HP            | ProBook 430 G3              | [c3acaeb030](https://linux-hardware.org/?probe=c3acaeb030) | Apr 26, 2021 |
| HP            | ProBook 430 G3              | [de3298645e](https://linux-hardware.org/?probe=de3298645e) | Apr 26, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8ff356e9be](https://linux-hardware.org/?probe=8ff356e9be) | Apr 25, 2021 |
| Packard Be... | EasyNote_BU45               | [83204d550c](https://linux-hardware.org/?probe=83204d550c) | Apr 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [998919a455](https://linux-hardware.org/?probe=998919a455) | Apr 18, 2021 |
| Dell          | Latitude 7410               | [7792c66c17](https://linux-hardware.org/?probe=7792c66c17) | Apr 15, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [8eeff8c77c](https://linux-hardware.org/?probe=8eeff8c77c) | Apr 13, 2021 |
| Dell          | Latitude 7400               | [41a2361010](https://linux-hardware.org/?probe=41a2361010) | Apr 11, 2021 |
| Acer          | Aspire ES1-431              | [9109f31570](https://linux-hardware.org/?probe=9109f31570) | Apr 10, 2021 |
| Acer          | Aspire ES1-431              | [df53cbed23](https://linux-hardware.org/?probe=df53cbed23) | Apr 10, 2021 |
| Toshiba       | PORTEGE R705                | [dd16cda442](https://linux-hardware.org/?probe=dd16cda442) | Apr 10, 2021 |
| ASUSTek       | N46VB                       | [a425e290d7](https://linux-hardware.org/?probe=a425e290d7) | Apr 09, 2021 |
| Personal C... | Iris                        | [add36a3a7c](https://linux-hardware.org/?probe=add36a3a7c) | Apr 09, 2021 |
| Personal C... | Iris                        | [4ec2ee9e6d](https://linux-hardware.org/?probe=4ec2ee9e6d) | Apr 09, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [adb7fbfc0d](https://linux-hardware.org/?probe=adb7fbfc0d) | Apr 08, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [9b9172e5a7](https://linux-hardware.org/?probe=9b9172e5a7) | Apr 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [3c44770d1a](https://linux-hardware.org/?probe=3c44770d1a) | Apr 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [3a85124409](https://linux-hardware.org/?probe=3a85124409) | Apr 07, 2021 |
| HP            | ENVY Notebook               | [83a0078309](https://linux-hardware.org/?probe=83a0078309) | Apr 06, 2021 |
| Dell          | Inspiron 5459               | [f3b9205a6c](https://linux-hardware.org/?probe=f3b9205a6c) | Apr 06, 2021 |
| Dell          | Inspiron 1545               | [ace9676e8c](https://linux-hardware.org/?probe=ace9676e8c) | Apr 05, 2021 |
| HP            | 15                          | [69d2aa2538](https://linux-hardware.org/?probe=69d2aa2538) | Apr 05, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8d5f33367e](https://linux-hardware.org/?probe=8d5f33367e) | Apr 04, 2021 |
| Lenovo        | IdeaPad Y480                | [d0aeb8aafc](https://linux-hardware.org/?probe=d0aeb8aafc) | Apr 03, 2021 |
| Dell          | Inspiron 3420               | [4d76b6366d](https://linux-hardware.org/?probe=4d76b6366d) | Apr 01, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [742b7afcc8](https://linux-hardware.org/?probe=742b7afcc8) | Apr 01, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [8856c82ed6](https://linux-hardware.org/?probe=8856c82ed6) | Mar 31, 2021 |
| HP            | ENVY 15                     | [31c601923e](https://linux-hardware.org/?probe=31c601923e) | Mar 31, 2021 |
| HP            | ENVY 15                     | [3628d88bc1](https://linux-hardware.org/?probe=3628d88bc1) | Mar 31, 2021 |
| HP            | 250 G4 Notebook PC          | [e3119c3a18](https://linux-hardware.org/?probe=e3119c3a18) | Mar 30, 2021 |
| HP            | 245 G7 Notebook PC          | [3a4703f85d](https://linux-hardware.org/?probe=3a4703f85d) | Mar 27, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [867936010e](https://linux-hardware.org/?probe=867936010e) | Mar 25, 2021 |
| Dell          | Inspiron 14-3467            | [6079a062b3](https://linux-hardware.org/?probe=6079a062b3) | Mar 18, 2021 |
| HP            | 240 G7 Notebook PC          | [669e53f097](https://linux-hardware.org/?probe=669e53f097) | Mar 16, 2021 |
| Dell          | Inspiron 5721               | [0f95174924](https://linux-hardware.org/?probe=0f95174924) | Mar 15, 2021 |
| HP            | Notebook                    | [9c176242dd](https://linux-hardware.org/?probe=9c176242dd) | Mar 14, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [e2e99630ca](https://linux-hardware.org/?probe=e2e99630ca) | Mar 14, 2021 |
| HP            | 15                          | [08b381f369](https://linux-hardware.org/?probe=08b381f369) | Mar 12, 2021 |
| Dell          | Inspiron 14-3467            | [0611d13dff](https://linux-hardware.org/?probe=0611d13dff) | Mar 11, 2021 |
| HP            | ProBook 440 G3              | [fc6181a7c1](https://linux-hardware.org/?probe=fc6181a7c1) | Mar 11, 2021 |
| HP            | ProBook 440 G3              | [38042c5772](https://linux-hardware.org/?probe=38042c5772) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| Acer          | Aspire 5738                 | [a1a9e12988](https://linux-hardware.org/?probe=a1a9e12988) | Mar 07, 2021 |
| MSI           | Stealth 15M A11SEK          | [1187156178](https://linux-hardware.org/?probe=1187156178) | Mar 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell          | Inspiron 14-3467            | [7991d50dfd](https://linux-hardware.org/?probe=7991d50dfd) | Mar 01, 2021 |
| Unknown       | Unknown                     | [e8359056f7](https://linux-hardware.org/?probe=e8359056f7) | Feb 26, 2021 |
| HP            | Pavilion Notebook           | [45dfe3c2b1](https://linux-hardware.org/?probe=45dfe3c2b1) | Feb 24, 2021 |
| Dell          | Vostro V13                  | [f9b40741e7](https://linux-hardware.org/?probe=f9b40741e7) | Feb 19, 2021 |
| Toshiba       | Satellite C845D             | [6a73d1fd72](https://linux-hardware.org/?probe=6a73d1fd72) | Feb 19, 2021 |
| Packard Be... | EasyNote TM85               | [972a7d0f8c](https://linux-hardware.org/?probe=972a7d0f8c) | Feb 17, 2021 |
| ASUSTek       | GL502VMK                    | [54b49d2dc7](https://linux-hardware.org/?probe=54b49d2dc7) | Feb 15, 2021 |
| ASUSTek       | GL502VMK                    | [514a434029](https://linux-hardware.org/?probe=514a434029) | Feb 15, 2021 |
| Dell          | Latitude 3440               | [d2806294ef](https://linux-hardware.org/?probe=d2806294ef) | Feb 13, 2021 |
| Unknown       | Unknown                     | [acd23bb798](https://linux-hardware.org/?probe=acd23bb798) | Feb 13, 2021 |
| Sony          | VPCEG15FL                   | [48a16e8a4a](https://linux-hardware.org/?probe=48a16e8a4a) | Feb 10, 2021 |
| Dell          | System Inspiron N411Z       | [eed8ecb624](https://linux-hardware.org/?probe=eed8ecb624) | Feb 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd F... | [799c301ad6](https://linux-hardware.org/?probe=799c301ad6) | Feb 08, 2021 |
| Dell          | System Inspiron N411Z       | [f6ea43033f](https://linux-hardware.org/?probe=f6ea43033f) | Feb 07, 2021 |
| Toshiba       | Satellite L745              | [01a4eafbb6](https://linux-hardware.org/?probe=01a4eafbb6) | Feb 02, 2021 |
| Toshiba       | Satellite L745              | [9cc5c245d0](https://linux-hardware.org/?probe=9cc5c245d0) | Feb 02, 2021 |
| HP            | 240 G6 Notebook PC          | [2ba1c141b8](https://linux-hardware.org/?probe=2ba1c141b8) | Feb 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [3f400fbc08](https://linux-hardware.org/?probe=3f400fbc08) | Jan 31, 2021 |
| ASUSTek       | UX430UNR                    | [e32eec7802](https://linux-hardware.org/?probe=e32eec7802) | Jan 27, 2021 |
| HP            | EliteBook 2560p             | [8289f3c10b](https://linux-hardware.org/?probe=8289f3c10b) | Jan 24, 2021 |
| HP            | Pavilion 15                 | [b83dc673fd](https://linux-hardware.org/?probe=b83dc673fd) | Jan 23, 2021 |
| HP            | 14                          | [7c1ff6f4a8](https://linux-hardware.org/?probe=7c1ff6f4a8) | Jan 22, 2021 |
| Dell          | Vostro 1520                 | [36392e13b5](https://linux-hardware.org/?probe=36392e13b5) | Jan 22, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [5f648131f5](https://linux-hardware.org/?probe=5f648131f5) | Jan 19, 2021 |
| ASUSTek       | UX310UQK                    | [7006cf4aa0](https://linux-hardware.org/?probe=7006cf4aa0) | Jan 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [4b69e8576c](https://linux-hardware.org/?probe=4b69e8576c) | Jan 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [7ae430600b](https://linux-hardware.org/?probe=7ae430600b) | Jan 07, 2021 |
| HP            | EliteBook 840 G6            | [5d26e74a5d](https://linux-hardware.org/?probe=5d26e74a5d) | Jan 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [1ce6d33d5b](https://linux-hardware.org/?probe=1ce6d33d5b) | Jan 07, 2021 |
| HP            | Notebook                    | [38341a3370](https://linux-hardware.org/?probe=38341a3370) | Jan 06, 2021 |
| HP            | EliteBook 840 G6            | [724662dec7](https://linux-hardware.org/?probe=724662dec7) | Jan 05, 2021 |
| Sony          | SVE14113ELW                 | [695f68585f](https://linux-hardware.org/?probe=695f68585f) | Jan 05, 2021 |
| Sony          | SVE14113ELW                 | [88ef270eb5](https://linux-hardware.org/?probe=88ef270eb5) | Jan 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [019f053a89](https://linux-hardware.org/?probe=019f053a89) | Jan 02, 2021 |
| HP            | Notebook                    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [0a8ed33e62](https://linux-hardware.org/?probe=0a8ed33e62) | Dec 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [9a02f6b2cf](https://linux-hardware.org/?probe=9a02f6b2cf) | Dec 22, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| Acer          | Aspire 5738                 | [ad2cafcbe8](https://linux-hardware.org/?probe=ad2cafcbe8) | Dec 13, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [43e55c9de6](https://linux-hardware.org/?probe=43e55c9de6) | Dec 13, 2020 |
| HP            | EliteBook 840r G4           | [ebc64db4ca](https://linux-hardware.org/?probe=ebc64db4ca) | Dec 12, 2020 |
| Acer          | Aspire 5738                 | [f29c073cfb](https://linux-hardware.org/?probe=f29c073cfb) | Dec 11, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [5bae11079c](https://linux-hardware.org/?probe=5bae11079c) | Dec 09, 2020 |
| Toshiba       | Satellite C645              | [0e17d5e680](https://linux-hardware.org/?probe=0e17d5e680) | Dec 09, 2020 |
| Toshiba       | Satellite C645              | [0fcca906f6](https://linux-hardware.org/?probe=0fcca906f6) | Dec 09, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [d9258de65c](https://linux-hardware.org/?probe=d9258de65c) | Dec 09, 2020 |
| Apple         | MacBookPro9,2               | [7469e3af08](https://linux-hardware.org/?probe=7469e3af08) | Dec 08, 2020 |
| HP            | ProBook 440 G7              | [01b2a334c8](https://linux-hardware.org/?probe=01b2a334c8) | Dec 04, 2020 |
| Lenovo        | IdeaPad Z400 20201          | [9f4318e1fa](https://linux-hardware.org/?probe=9f4318e1fa) | Dec 03, 2020 |
| Lenovo        | K2450 20243                 | [33409ba105](https://linux-hardware.org/?probe=33409ba105) | Dec 03, 2020 |
| Dell          | Latitude E7470              | [ff5ee269cb](https://linux-hardware.org/?probe=ff5ee269cb) | Dec 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [9be5961a82](https://linux-hardware.org/?probe=9be5961a82) | Nov 25, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2ce0bde22b](https://linux-hardware.org/?probe=2ce0bde22b) | Nov 21, 2020 |
| ASUSTek       | X405UA                      | [e27b62e8d8](https://linux-hardware.org/?probe=e27b62e8d8) | Nov 19, 2020 |
| Lenovo        | K2450 20243                 | [4d44042257](https://linux-hardware.org/?probe=4d44042257) | Nov 19, 2020 |
| HP            | EliteBook 840r G4           | [4782db92e6](https://linux-hardware.org/?probe=4782db92e6) | Nov 19, 2020 |
| Lenovo        | IdeaPad S206 20154          | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Lenovo        | G400 20235                  | [7cdfc8df41](https://linux-hardware.org/?probe=7cdfc8df41) | Nov 17, 2020 |
| Lenovo        | G400 20235                  | [9d19c00f4e](https://linux-hardware.org/?probe=9d19c00f4e) | Nov 17, 2020 |
| Positivo      | Mobile                      | [87704474ae](https://linux-hardware.org/?probe=87704474ae) | Nov 12, 2020 |
| HP            | 1000                        | [a79972678b](https://linux-hardware.org/?probe=a79972678b) | Nov 10, 2020 |
| Lenovo        | ThinkPad T400 6474AU5       | [1b3d0a7938](https://linux-hardware.org/?probe=1b3d0a7938) | Nov 09, 2020 |
| HP            | 420                         | [8b2ce5df27](https://linux-hardware.org/?probe=8b2ce5df27) | Nov 09, 2020 |
| Unknown       | Unknown                     | [8651ede6c2](https://linux-hardware.org/?probe=8651ede6c2) | Nov 04, 2020 |
| Dell          | XPS 13 9300                 | [764cabc447](https://linux-hardware.org/?probe=764cabc447) | Nov 03, 2020 |
| HP            | Pavilion dv4                | [80f9a1311e](https://linux-hardware.org/?probe=80f9a1311e) | Oct 30, 2020 |
| Toshiba       | Satellite C45-A             | [bbfec71882](https://linux-hardware.org/?probe=bbfec71882) | Oct 30, 2020 |
| HP            | Laptop 14-cf0xxx            | [5ae192d7e1](https://linux-hardware.org/?probe=5ae192d7e1) | Oct 26, 2020 |
| HP            | Laptop 14-cf0xxx            | [8999670eb2](https://linux-hardware.org/?probe=8999670eb2) | Oct 25, 2020 |
| Acer          | Swift SF314-42              | [628265bca0](https://linux-hardware.org/?probe=628265bca0) | Oct 25, 2020 |
| Lenovo        | IdeaPad S300 20197          | [d03e3dc110](https://linux-hardware.org/?probe=d03e3dc110) | Oct 23, 2020 |
| Dell          | Latitude E6440              | [46a2699a96](https://linux-hardware.org/?probe=46a2699a96) | Oct 21, 2020 |
| Acer          | Swift SF314-42              | [01143e194b](https://linux-hardware.org/?probe=01143e194b) | Oct 20, 2020 |
| ASUSTek       | X555LB                      | [75ba1f9ee4](https://linux-hardware.org/?probe=75ba1f9ee4) | Oct 19, 2020 |
| Acer          | Aspire E1-531               | [78a57e6fb8](https://linux-hardware.org/?probe=78a57e6fb8) | Oct 13, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [63831d979c](https://linux-hardware.org/?probe=63831d979c) | Oct 06, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [887dc701b4](https://linux-hardware.org/?probe=887dc701b4) | Oct 05, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [eed07ba536](https://linux-hardware.org/?probe=eed07ba536) | Oct 05, 2020 |
| Unknown       | Unknown                     | [afc109116d](https://linux-hardware.org/?probe=afc109116d) | Oct 01, 2020 |
| HP            | 530                         | [c330f06c15](https://linux-hardware.org/?probe=c330f06c15) | Sep 30, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ad0d202176](https://linux-hardware.org/?probe=ad0d202176) | Sep 29, 2020 |
| HP            | Pavilion Power Laptop 15... | [6f97a1bc53](https://linux-hardware.org/?probe=6f97a1bc53) | Sep 28, 2020 |
| Lenovo        | ThinkPad T460 20FMS05G4L    | [2934114047](https://linux-hardware.org/?probe=2934114047) | Sep 28, 2020 |
| Dell          | XPS 13 9370                 | [bd632f89ef](https://linux-hardware.org/?probe=bd632f89ef) | Sep 26, 2020 |
| HP            | EliteBook 840r G4           | [2ed34e371e](https://linux-hardware.org/?probe=2ed34e371e) | Sep 26, 2020 |
| Unknown       | Unknown                     | [be59c4d6c4](https://linux-hardware.org/?probe=be59c4d6c4) | Sep 23, 2020 |
| HP            | EliteBook 840 G6            | [42e3c550cb](https://linux-hardware.org/?probe=42e3c550cb) | Sep 22, 2020 |
| ASUSTek       | X556URK                     | [1c0033b367](https://linux-hardware.org/?probe=1c0033b367) | Sep 20, 2020 |
| ASUSTek       | G55VW                       | [8bfec34af2](https://linux-hardware.org/?probe=8bfec34af2) | Sep 20, 2020 |
| HP            | 245 G5 Notebook PC          | [d2e8cd8f97](https://linux-hardware.org/?probe=d2e8cd8f97) | Sep 15, 2020 |
| HP            | 245 G5 Notebook PC          | [da0f03edfc](https://linux-hardware.org/?probe=da0f03edfc) | Sep 14, 2020 |
| Acer          | Aspire 5542                 | [da115e748b](https://linux-hardware.org/?probe=da115e748b) | Sep 14, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [1f5bd64812](https://linux-hardware.org/?probe=1f5bd64812) | Sep 09, 2020 |
| HP            | Pavilion 15                 | [df560484b4](https://linux-hardware.org/?probe=df560484b4) | Sep 09, 2020 |
| Acer          | Nitro AN515-43              | [44782a039e](https://linux-hardware.org/?probe=44782a039e) | Sep 07, 2020 |
| Lenovo        | ThinkPad A485 20MVS0N300    | [6ad17e6cf7](https://linux-hardware.org/?probe=6ad17e6cf7) | Sep 05, 2020 |
| HP            | Notebook                    | [c5d0ec5edb](https://linux-hardware.org/?probe=c5d0ec5edb) | Aug 30, 2020 |
| Acer          | Aspire E1-422               | [a239e53a11](https://linux-hardware.org/?probe=a239e53a11) | Aug 29, 2020 |
| Acer          | Aspire A315-21              | [02f9010c71](https://linux-hardware.org/?probe=02f9010c71) | Aug 26, 2020 |
| HP            | Pavilion Notebook           | [341b0f6231](https://linux-hardware.org/?probe=341b0f6231) | Aug 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [be74487ec4](https://linux-hardware.org/?probe=be74487ec4) | Aug 23, 2020 |
| Acer          | Aspire ES1-111M             | [fcee1a2241](https://linux-hardware.org/?probe=fcee1a2241) | Aug 21, 2020 |
| Acer          | Aspire ES1-111M             | [43f35553ae](https://linux-hardware.org/?probe=43f35553ae) | Aug 21, 2020 |
| HP            | Pavilion 15                 | [d9c1a66672](https://linux-hardware.org/?probe=d9c1a66672) | Aug 20, 2020 |
| HP            | Laptop 15-bs0xx             | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Lenovo        | ThinkPad E420 1141DAS       | [ab579f2102](https://linux-hardware.org/?probe=ab579f2102) | Aug 17, 2020 |
| Lenovo        | ThinkPad E420 1141DAS       | [d4beb495bd](https://linux-hardware.org/?probe=d4beb495bd) | Aug 17, 2020 |
| ASUSTek       | FX503VD                     | [26ce95f067](https://linux-hardware.org/?probe=26ce95f067) | Aug 03, 2020 |
| HP            | Laptop 15-bs0xx             | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| HP            | ProBook 440 G3              | [9a34cb7ec7](https://linux-hardware.org/?probe=9a34cb7ec7) | Jul 28, 2020 |
| Acer          | Aspire ES1-572              | [1db75aee39](https://linux-hardware.org/?probe=1db75aee39) | Jul 27, 2020 |
| Acer          | Aspire R3-431T              | [b3bc6f8d90](https://linux-hardware.org/?probe=b3bc6f8d90) | Jul 24, 2020 |
| HP            | Pavilion 15                 | [7410d46ef8](https://linux-hardware.org/?probe=7410d46ef8) | Jul 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [dbb48c14f0](https://linux-hardware.org/?probe=dbb48c14f0) | Jul 22, 2020 |
| HP            | Notebook                    | [431d1d1482](https://linux-hardware.org/?probe=431d1d1482) | Jul 22, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [3216dbc594](https://linux-hardware.org/?probe=3216dbc594) | Jul 18, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f8c9b50bc3](https://linux-hardware.org/?probe=f8c9b50bc3) | Jul 18, 2020 |
| Sony          | VGN-FW360TJ                 | [8b037cac91](https://linux-hardware.org/?probe=8b037cac91) | Jul 18, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Apple         | MacBookAir7,2               | [f53c9923c4](https://linux-hardware.org/?probe=f53c9923c4) | Jul 11, 2020 |
| HP            | Presario CQ43               | [48fe8649ca](https://linux-hardware.org/?probe=48fe8649ca) | Jul 08, 2020 |
| HP            | Presario CQ43               | [db6a9d6546](https://linux-hardware.org/?probe=db6a9d6546) | Jul 06, 2020 |
| HP            | ProBook 4440s               | [48a7e1a88c](https://linux-hardware.org/?probe=48a7e1a88c) | Jul 05, 2020 |
| Dell          | Inspiron N5110              | [bd30f237dd](https://linux-hardware.org/?probe=bd30f237dd) | Jul 05, 2020 |
| Acer          | Aspire ES1-331              | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| HP            | ProBook 640 G1              | [1a2462dee7](https://linux-hardware.org/?probe=1a2462dee7) | Jul 01, 2020 |
| Toshiba       | PORTEGE R30-A               | [d33d8295b1](https://linux-hardware.org/?probe=d33d8295b1) | Jun 29, 2020 |
| Corporativ... | LX4SI                       | [3a15f8865d](https://linux-hardware.org/?probe=3a15f8865d) | Jun 26, 2020 |
| ASUSTek       | X450LN                      | [347ebd88a5](https://linux-hardware.org/?probe=347ebd88a5) | Jun 25, 2020 |
| ASUSTek       | X450LN                      | [10dd68f147](https://linux-hardware.org/?probe=10dd68f147) | Jun 25, 2020 |
| Corporativ... | LX4SI                       | [f9e67e8a5f](https://linux-hardware.org/?probe=f9e67e8a5f) | Jun 25, 2020 |
| HP            | 240 G6 Notebook PC          | [c43e5357b0](https://linux-hardware.org/?probe=c43e5357b0) | Jun 24, 2020 |
| Packard Be... | DOT S                       | [d2cd9b2728](https://linux-hardware.org/?probe=d2cd9b2728) | Jun 24, 2020 |
| Lenovo        | IdeaPad 500-14ISK 80NS      | [1af5a3043b](https://linux-hardware.org/?probe=1af5a3043b) | Jun 23, 2020 |
| HP            | ProBook 430 G2              | [d988a74820](https://linux-hardware.org/?probe=d988a74820) | Jun 23, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | [0fbefbc62c](https://linux-hardware.org/?probe=0fbefbc62c) | Jun 21, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | [a281f8c305](https://linux-hardware.org/?probe=a281f8c305) | Jun 19, 2020 |
| HP            | 245 G4 Notebook PC          | [4f96cc852f](https://linux-hardware.org/?probe=4f96cc852f) | Jun 18, 2020 |
| HP            | 245 G4 Notebook PC          | [2c0356727d](https://linux-hardware.org/?probe=2c0356727d) | Jun 18, 2020 |
| Dell          | Inspiron 3420               | [5101d0c83c](https://linux-hardware.org/?probe=5101d0c83c) | Jun 17, 2020 |
| Dell          | Inspiron 14-3452            | [c83e4c2dd8](https://linux-hardware.org/?probe=c83e4c2dd8) | Jun 15, 2020 |
| Lenovo        | IdeaPad Z470                | [7167c9a1eb](https://linux-hardware.org/?probe=7167c9a1eb) | Jun 10, 2020 |
| Packard Be... | ENNS11HR                    | [952d5d4772](https://linux-hardware.org/?probe=952d5d4772) | Jun 05, 2020 |
| HP            | ProBook 4440s               | [730e093bc4](https://linux-hardware.org/?probe=730e093bc4) | Jun 05, 2020 |
| Acer          | Aspire V5-132               | [44a89c002a](https://linux-hardware.org/?probe=44a89c002a) | Jun 02, 2020 |
| Acer          | Aspire V5-132               | [5b82f8d7d3](https://linux-hardware.org/?probe=5b82f8d7d3) | Jun 02, 2020 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [fbccea1bb2](https://linux-hardware.org/?probe=fbccea1bb2) | May 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [9a867c7a5b](https://linux-hardware.org/?probe=9a867c7a5b) | May 28, 2020 |
| Dell          | Latitude E7450              | [c3eab25bca](https://linux-hardware.org/?probe=c3eab25bca) | May 28, 2020 |
| Clevo         | W240HU/W250HUQ              | [9fac55b56b](https://linux-hardware.org/?probe=9fac55b56b) | May 28, 2020 |
| Clevo         | W240HU/W250HUQ              | [9403cfc9c4](https://linux-hardware.org/?probe=9403cfc9c4) | May 27, 2020 |
| Clevo         | W240HU/W250HUQ              | [216a9db389](https://linux-hardware.org/?probe=216a9db389) | May 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [38e63a05e2](https://linux-hardware.org/?probe=38e63a05e2) | May 26, 2020 |
| Dell          | Inspiron 14-3452            | [f894499ac3](https://linux-hardware.org/?probe=f894499ac3) | May 26, 2020 |
| HP            | OMEN by Laptop              | [6cea5aa3fd](https://linux-hardware.org/?probe=6cea5aa3fd) | May 26, 2020 |
| HP            | OMEN by Laptop              | [a621749c2d](https://linux-hardware.org/?probe=a621749c2d) | May 26, 2020 |
| Acer          | ES1-111M                    | [53e45e403c](https://linux-hardware.org/?probe=53e45e403c) | May 23, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [fae71925c5](https://linux-hardware.org/?probe=fae71925c5) | May 21, 2020 |
| Acer          | Aspire 4739Z                | [f51ee0fe5a](https://linux-hardware.org/?probe=f51ee0fe5a) | May 20, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [910d27523a](https://linux-hardware.org/?probe=910d27523a) | May 20, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [ffe1142072](https://linux-hardware.org/?probe=ffe1142072) | May 19, 2020 |
| Acer          | Aspire A114-32              | [35ddb37c29](https://linux-hardware.org/?probe=35ddb37c29) | May 17, 2020 |
| Acer          | Aspire E5-551G              | [cda77789ec](https://linux-hardware.org/?probe=cda77789ec) | May 17, 2020 |
| Acer          | Aspire E5-551G              | [ee3ddbe726](https://linux-hardware.org/?probe=ee3ddbe726) | May 17, 2020 |
| Dell          | Latitude E6420              | [46a7b9904a](https://linux-hardware.org/?probe=46a7b9904a) | May 17, 2020 |
| Dell          | Latitude E6420              | [15d9716666](https://linux-hardware.org/?probe=15d9716666) | May 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [55850d2bd2](https://linux-hardware.org/?probe=55850d2bd2) | May 17, 2020 |
| Dell          | Inspiron 14-3452            | [65292593ee](https://linux-hardware.org/?probe=65292593ee) | May 15, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [fd09b801b7](https://linux-hardware.org/?probe=fd09b801b7) | May 14, 2020 |
| HP            | Pavilion Notebook           | [825d07d907](https://linux-hardware.org/?probe=825d07d907) | May 14, 2020 |
| Dell          | Precision 7520              | [bf1d29844b](https://linux-hardware.org/?probe=bf1d29844b) | May 13, 2020 |
| Dell          | Inspiron 1420               | [917741e728](https://linux-hardware.org/?probe=917741e728) | May 13, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [8006d3f65a](https://linux-hardware.org/?probe=8006d3f65a) | May 12, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [9767ed89e1](https://linux-hardware.org/?probe=9767ed89e1) | May 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f15c21aabd](https://linux-hardware.org/?probe=f15c21aabd) | May 11, 2020 |
| Toshiba       | NB505                       | [26eaa80c8a](https://linux-hardware.org/?probe=26eaa80c8a) | May 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [ebf32d4cbf](https://linux-hardware.org/?probe=ebf32d4cbf) | May 08, 2020 |
| ASUSTek       | K50AB                       | [ac598fedba](https://linux-hardware.org/?probe=ac598fedba) | May 06, 2020 |
| ASUSTek       | K50AB                       | [9e3de662ae](https://linux-hardware.org/?probe=9e3de662ae) | May 06, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [3abae5c4a3](https://linux-hardware.org/?probe=3abae5c4a3) | May 05, 2020 |
| HP            | Pavilion Notebook           | [b995e0664a](https://linux-hardware.org/?probe=b995e0664a) | May 03, 2020 |
| HP            | ElitePad 1000 G2            | [40df66d7b8](https://linux-hardware.org/?probe=40df66d7b8) | Apr 29, 2020 |
| Acer          | Aspire E1-531               | [c814274f99](https://linux-hardware.org/?probe=c814274f99) | Apr 27, 2020 |
| HP            | 240 G6 Notebook PC          | [542ddefbc5](https://linux-hardware.org/?probe=542ddefbc5) | Apr 25, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | [3fd8a137d5](https://linux-hardware.org/?probe=3fd8a137d5) | Apr 21, 2020 |
| HP            | 240 G6 Notebook PC          | [e96b3b2ace](https://linux-hardware.org/?probe=e96b3b2ace) | Apr 21, 2020 |
| HP            | 240 G6 Notebook PC          | [5058e946ea](https://linux-hardware.org/?probe=5058e946ea) | Apr 21, 2020 |
| Acer          | Aspire E1-531               | [a7e6d42571](https://linux-hardware.org/?probe=a7e6d42571) | Apr 21, 2020 |
| Acer          | Aspire E1-531               | [384b1e8269](https://linux-hardware.org/?probe=384b1e8269) | Apr 20, 2020 |
| HP            | EliteBook 840 G6            | [57feb728c2](https://linux-hardware.org/?probe=57feb728c2) | Apr 19, 2020 |
| Toshiba       | NB505                       | [174dd8b4cd](https://linux-hardware.org/?probe=174dd8b4cd) | Apr 16, 2020 |
| HP            | ENVY 15                     | [d38936efb2](https://linux-hardware.org/?probe=d38936efb2) | Apr 16, 2020 |
| Toshiba       | NB505                       | [a28c9ef432](https://linux-hardware.org/?probe=a28c9ef432) | Apr 12, 2020 |
| HP            | Pavilion g4                 | [ee7f720be3](https://linux-hardware.org/?probe=ee7f720be3) | Apr 12, 2020 |
| HP            | Pavilion Sleekbook 15       | [309b26e9a7](https://linux-hardware.org/?probe=309b26e9a7) | Apr 12, 2020 |
| HP            | Pavilion Sleekbook 15       | [ca7cea286a](https://linux-hardware.org/?probe=ca7cea286a) | Apr 12, 2020 |
| Toshiba       | PORTEGE Z20t-C              | [9411f4e22a](https://linux-hardware.org/?probe=9411f4e22a) | Apr 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [cf13d07d7d](https://linux-hardware.org/?probe=cf13d07d7d) | Apr 08, 2020 |
| Toshiba       | NB505                       | [c52e8296ad](https://linux-hardware.org/?probe=c52e8296ad) | Apr 06, 2020 |
| HP            | Notebook                    | [60ebb42480](https://linux-hardware.org/?probe=60ebb42480) | Apr 05, 2020 |
| HP            | Notebook                    | [6102146f30](https://linux-hardware.org/?probe=6102146f30) | Apr 04, 2020 |
| Toshiba       | Satellite P745D             | [82c4813a13](https://linux-hardware.org/?probe=82c4813a13) | Apr 02, 2020 |
| Toshiba       | Satellite P745D             | [dd172e55aa](https://linux-hardware.org/?probe=dd172e55aa) | Apr 02, 2020 |
| Toshiba       | Satellite P745D             | [a04d4d7bcb](https://linux-hardware.org/?probe=a04d4d7bcb) | Apr 02, 2020 |
| HP            | 250 G5 Notebook PC          | [ccc351f3a5](https://linux-hardware.org/?probe=ccc351f3a5) | Apr 01, 2020 |
| ASUSTek       | X580VD                      | [e8c7cfc3af](https://linux-hardware.org/?probe=e8c7cfc3af) | Mar 31, 2020 |
| Lenovo        | ThinkPad T410 2537M82       | [7c71cd5a53](https://linux-hardware.org/?probe=7c71cd5a53) | Mar 30, 2020 |
| Samsung       | RF511/RF411/RF711           | [54fd8a8ef3](https://linux-hardware.org/?probe=54fd8a8ef3) | Mar 27, 2020 |
| HP            | Laptop 14-bs0xx             | [872a291771](https://linux-hardware.org/?probe=872a291771) | Mar 26, 2020 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [62d04b32f4](https://linux-hardware.org/?probe=62d04b32f4) | Mar 25, 2020 |
| ASUSTek       | X455LAB                     | [cfe6c04671](https://linux-hardware.org/?probe=cfe6c04671) | Mar 19, 2020 |
| Acer          | Aspire 4332                 | [1ffe28f950](https://linux-hardware.org/?probe=1ffe28f950) | Mar 19, 2020 |
| Acer          | Aspire 4332                 | [4ef79a9f26](https://linux-hardware.org/?probe=4ef79a9f26) | Mar 19, 2020 |
| HP            | EliteBook 840 G6            | [d512b89622](https://linux-hardware.org/?probe=d512b89622) | Mar 13, 2020 |
| Acer          | TravelMate P258-M           | [6275f9d007](https://linux-hardware.org/?probe=6275f9d007) | Feb 22, 2020 |
| Samsung       | 450R4E/450R5E/450R4V/450... | [6e0ef2fa11](https://linux-hardware.org/?probe=6e0ef2fa11) | Feb 22, 2020 |
| Samsung       | 450R4E/450R5E/450R4V/450... | [152883e525](https://linux-hardware.org/?probe=152883e525) | Feb 22, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | [811ba67ee3](https://linux-hardware.org/?probe=811ba67ee3) | Feb 21, 2020 |
| HP            | 245 G5 Notebook PC          | [ecbab8f357](https://linux-hardware.org/?probe=ecbab8f357) | Feb 19, 2020 |
| Samsung       | R540/R580/R780/SA41/E452    | [b72d68e62c](https://linux-hardware.org/?probe=b72d68e62c) | Jan 31, 2020 |
| Sony          | VPCEG20EL                   | [d2ac041c40](https://linux-hardware.org/?probe=d2ac041c40) | Jan 22, 2020 |
| HP            | Presario CQ56               | [cafdaff7c6](https://linux-hardware.org/?probe=cafdaff7c6) | Jan 16, 2020 |
| AMI           | Unknown                     | [4d89af9f9b](https://linux-hardware.org/?probe=4d89af9f9b) | Jan 16, 2020 |
| Acer          | Aspire ES1-111M             | [ba1b65c973](https://linux-hardware.org/?probe=ba1b65c973) | Jan 13, 2020 |
| Acer          | Aspire E3-111               | [87473b8d1c](https://linux-hardware.org/?probe=87473b8d1c) | Jan 07, 2020 |
| Dell          | Latitude E7440              | [de95222539](https://linux-hardware.org/?probe=de95222539) | Dec 28, 2019 |
| Insyde        | CherryTrail                 | [9f7a2725e5](https://linux-hardware.org/?probe=9f7a2725e5) | Dec 07, 2019 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ad5138a45f](https://linux-hardware.org/?probe=ad5138a45f) | Dec 04, 2019 |
| Dell          | Latitude E5470              | [5bf1258e74](https://linux-hardware.org/?probe=5bf1258e74) | Dec 03, 2019 |
| HP            | 245 G5 Notebook PC          | [8c201c4443](https://linux-hardware.org/?probe=8c201c4443) | Nov 30, 2019 |
| ASUSTek       | FX503VD                     | [f5dc0694e1](https://linux-hardware.org/?probe=f5dc0694e1) | Nov 28, 2019 |
| ASUSTek       | X406UAR                     | [a1d52e4665](https://linux-hardware.org/?probe=a1d52e4665) | Nov 25, 2019 |
| ASUSTek       | FX503VD                     | [5f33fb689d](https://linux-hardware.org/?probe=5f33fb689d) | Nov 24, 2019 |
| MSI           | GS65 Stealth 9SF            | [dfb909840b](https://linux-hardware.org/?probe=dfb909840b) | Nov 22, 2019 |
| ASUSTek       | FX503VD                     | [a5ad247bdc](https://linux-hardware.org/?probe=a5ad247bdc) | Nov 21, 2019 |
| ASUSTek       | E402NA                      | [07bf7c4021](https://linux-hardware.org/?probe=07bf7c4021) | Nov 10, 2019 |
| Toshiba       | Satellite L745              | [93ab04c913](https://linux-hardware.org/?probe=93ab04c913) | Nov 07, 2019 |
| Apple         | MacBookAir7,2               | [0e1f45ae13](https://linux-hardware.org/?probe=0e1f45ae13) | Oct 22, 2019 |
| Samsung       | RF511/RF411/RF711           | [3f7beb5458](https://linux-hardware.org/?probe=3f7beb5458) | Oct 20, 2019 |
| ASUSTek       | FX503VD                     | [f95cd75d9e](https://linux-hardware.org/?probe=f95cd75d9e) | Oct 08, 2019 |
| Dell          | Inspiron 5421               | [0403587941](https://linux-hardware.org/?probe=0403587941) | Oct 05, 2019 |
| Dell          | Inspiron 5570               | [3fec0285f1](https://linux-hardware.org/?probe=3fec0285f1) | Oct 05, 2019 |
| HP            | Pavilion 15                 | [c6002f59ca](https://linux-hardware.org/?probe=c6002f59ca) | Oct 02, 2019 |
| OX            | PC-9890166 D0.05T45.18.1... | [75abcb1b69](https://linux-hardware.org/?probe=75abcb1b69) | Sep 29, 2019 |
| OX            | PC-9890166 D0.05T45.18.1... | [9c2460c5e0](https://linux-hardware.org/?probe=9c2460c5e0) | Sep 29, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [5cebf9dcc4](https://linux-hardware.org/?probe=5cebf9dcc4) | Sep 25, 2019 |
| Acer          | Aspire 4736Z                | [a1a9c940fb](https://linux-hardware.org/?probe=a1a9c940fb) | Sep 22, 2019 |
| Sony          | VGN-NR330FE                 | [71126383fe](https://linux-hardware.org/?probe=71126383fe) | Sep 20, 2019 |
| Dell          | Latitude E6420              | [683f31db53](https://linux-hardware.org/?probe=683f31db53) | Sep 19, 2019 |
| HP            | G42                         | [5addde0384](https://linux-hardware.org/?probe=5addde0384) | Sep 15, 2019 |
| HP            | 240 G6 Notebook PC          | [45a420f97b](https://linux-hardware.org/?probe=45a420f97b) | Sep 12, 2019 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [6cbeb4c5dd](https://linux-hardware.org/?probe=6cbeb4c5dd) | Sep 10, 2019 |
| HP            | Unknown                     | [f4e6748e0d](https://linux-hardware.org/?probe=f4e6748e0d) | Sep 06, 2019 |
| Creative V... | C14CT series                | [fe141371eb](https://linux-hardware.org/?probe=fe141371eb) | Sep 04, 2019 |
| HP            | Pavilion Notebook           | [407ab6ce27](https://linux-hardware.org/?probe=407ab6ce27) | Aug 26, 2019 |
| HP            | 240 G6 Notebook PC          | [48697f4bda](https://linux-hardware.org/?probe=48697f4bda) | Aug 22, 2019 |
| OEM           | V40SI2                      | [0ef7e2c60f](https://linux-hardware.org/?probe=0ef7e2c60f) | Aug 22, 2019 |
| ASUSTek       | FX503VD                     | [b4d34b6e82](https://linux-hardware.org/?probe=b4d34b6e82) | Aug 09, 2019 |
| Acer          | Swift SF314-52G             | [39291bfee6](https://linux-hardware.org/?probe=39291bfee6) | Aug 06, 2019 |
| HP            | 240 G6 Notebook PC          | [f82cbc8005](https://linux-hardware.org/?probe=f82cbc8005) | Aug 05, 2019 |
| HP            | Laptop 15-bs0xx             | [f416d66db4](https://linux-hardware.org/?probe=f416d66db4) | Jul 31, 2019 |
| HP            | Laptop 15-bs0xx             | [71e60872ea](https://linux-hardware.org/?probe=71e60872ea) | Jul 31, 2019 |
| HP            | Laptop 15-bw0xx             | [0ab5bf5b1a](https://linux-hardware.org/?probe=0ab5bf5b1a) | Jul 27, 2019 |
| HP            | 240 G6 Notebook PC          | [11487c8b52](https://linux-hardware.org/?probe=11487c8b52) | Jul 26, 2019 |
| HP            | Notebook                    | [8ec780e92f](https://linux-hardware.org/?probe=8ec780e92f) | Jul 18, 2019 |
| Dell          | Inspiron 3437               | [30c4e0f323](https://linux-hardware.org/?probe=30c4e0f323) | Jul 16, 2019 |
| Lenovo        | ThinkPad E420 1141RH3       | [72424367ad](https://linux-hardware.org/?probe=72424367ad) | Jul 07, 2019 |
| Samsung       | R430/P430                   | [ec62fdb035](https://linux-hardware.org/?probe=ec62fdb035) | Jul 04, 2019 |
| Toshiba       | Satellite L515              | [3832002e7f](https://linux-hardware.org/?probe=3832002e7f) | Jul 01, 2019 |
| HP            | 240 G6 Notebook PC          | [e97a9cf2c6](https://linux-hardware.org/?probe=e97a9cf2c6) | Jun 29, 2019 |
| Dell          | Latitude E6420              | [3cf5c7994e](https://linux-hardware.org/?probe=3cf5c7994e) | Jun 24, 2019 |
| Sony          | SVF14325CLW                 | [67abaeea89](https://linux-hardware.org/?probe=67abaeea89) | Jun 20, 2019 |
| HP            | 240 G6 Notebook PC          | [e333e77665](https://linux-hardware.org/?probe=e333e77665) | Jun 18, 2019 |
| Acer          | Aspire E1-422               | [8ba524cf2d](https://linux-hardware.org/?probe=8ba524cf2d) | Jun 14, 2019 |
| ASUSTek       | X302LJ                      | [ca06e39372](https://linux-hardware.org/?probe=ca06e39372) | Jun 11, 2019 |
| ASUSTek       | X302LJ                      | [38ba3bc487](https://linux-hardware.org/?probe=38ba3bc487) | Jun 11, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [872526f7f7](https://linux-hardware.org/?probe=872526f7f7) | Jun 10, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [fcc5af7203](https://linux-hardware.org/?probe=fcc5af7203) | Jun 10, 2019 |
| ASUSTek       | X302LJ                      | [96aa51f787](https://linux-hardware.org/?probe=96aa51f787) | Jun 09, 2019 |
| ASUSTek       | X302LJ                      | [b1c95fbf3d](https://linux-hardware.org/?probe=b1c95fbf3d) | Jun 09, 2019 |
| Apple         | MacBookPro9,2               | [6819d18bc8](https://linux-hardware.org/?probe=6819d18bc8) | Jun 08, 2019 |
| ASUSTek       | FX503VD                     | [b8b7156cd0](https://linux-hardware.org/?probe=b8b7156cd0) | Jun 04, 2019 |
| Lenovo        | ThinkPad T450 20BUS1DH00    | [3686a559e0](https://linux-hardware.org/?probe=3686a559e0) | May 28, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [10159a71f6](https://linux-hardware.org/?probe=10159a71f6) | May 25, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [5e20d7d4e0](https://linux-hardware.org/?probe=5e20d7d4e0) | May 20, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [bc3ec67a48](https://linux-hardware.org/?probe=bc3ec67a48) | May 20, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [329c7ece42](https://linux-hardware.org/?probe=329c7ece42) | May 20, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [1988815ca4](https://linux-hardware.org/?probe=1988815ca4) | May 20, 2019 |
| Dell          | Inspiron M5040              | [6621280c03](https://linux-hardware.org/?probe=6621280c03) | May 14, 2019 |
| HP            | ProBook 5330m               | [79b5425192](https://linux-hardware.org/?probe=79b5425192) | May 11, 2019 |
| HP            | EliteBook 8470p             | [9489581964](https://linux-hardware.org/?probe=9489581964) | May 08, 2019 |
| HP            | EliteBook 8470p             | [55b280af12](https://linux-hardware.org/?probe=55b280af12) | May 07, 2019 |
| Samsung       | RC410/RC510/RC710           | [c780e50507](https://linux-hardware.org/?probe=c780e50507) | May 05, 2019 |
| HP            | Pavilion Notebook           | [2d0e845055](https://linux-hardware.org/?probe=2d0e845055) | May 01, 2019 |
| Dell          | Inspiron M5040              | [bc2495b50a](https://linux-hardware.org/?probe=bc2495b50a) | May 01, 2019 |
| Dell          | Inspiron M5040              | [17879a2dfc](https://linux-hardware.org/?probe=17879a2dfc) | May 01, 2019 |
| HP            | Presario V3000 (GG542LA#... | [e964514e68](https://linux-hardware.org/?probe=e964514e68) | Apr 28, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [37ced39aa5](https://linux-hardware.org/?probe=37ced39aa5) | Apr 23, 2019 |
| Dell          | Inspiron M5040              | [bfc540e551](https://linux-hardware.org/?probe=bfc540e551) | Apr 20, 2019 |
| Dell          | Inspiron M5040              | [6833cf2d42](https://linux-hardware.org/?probe=6833cf2d42) | Apr 20, 2019 |
| HP            | 14                          | [fb281475c9](https://linux-hardware.org/?probe=fb281475c9) | Apr 15, 2019 |
| HP            | 14                          | [178f0eb4e7](https://linux-hardware.org/?probe=178f0eb4e7) | Apr 15, 2019 |
| HP            | ENVY m6                     | [4180a07245](https://linux-hardware.org/?probe=4180a07245) | Apr 13, 2019 |
| HP            | 1000                        | [82d8e28c9e](https://linux-hardware.org/?probe=82d8e28c9e) | Apr 13, 2019 |
| HP            | 1000                        | [445d946c9f](https://linux-hardware.org/?probe=445d946c9f) | Apr 12, 2019 |
| HP            | 240 G6 Notebook PC          | [01b46e3429](https://linux-hardware.org/?probe=01b46e3429) | Apr 10, 2019 |
| Sony          | SVE11115ELB                 | [8cd5213bb6](https://linux-hardware.org/?probe=8cd5213bb6) | Apr 10, 2019 |
| HP            | 240 G6 Notebook PC          | [ca36723635](https://linux-hardware.org/?probe=ca36723635) | Apr 10, 2019 |
| Toshiba       | Satellite L305              | [e39a1f246e](https://linux-hardware.org/?probe=e39a1f246e) | Mar 31, 2019 |
| Acer          | Aspire ES1-433G             | [e667efbc30](https://linux-hardware.org/?probe=e667efbc30) | Mar 24, 2019 |
| HP            | ENVY 14                     | [6c4e6833ab](https://linux-hardware.org/?probe=6c4e6833ab) | Mar 24, 2019 |
| HP            | EliteBook 8530w             | [3f7f390254](https://linux-hardware.org/?probe=3f7f390254) | Mar 24, 2019 |
| Lenovo        | G40-70 20369                | [663bc4d39a](https://linux-hardware.org/?probe=663bc4d39a) | Mar 23, 2019 |
| HP            | Mini 110-1000               | [e718456945](https://linux-hardware.org/?probe=e718456945) | Mar 20, 2019 |
| HP            | Pavilion Sleekbook 14 PC    | [f4b4b7905c](https://linux-hardware.org/?probe=f4b4b7905c) | Mar 13, 2019 |
| Lenovo        | V330-14IKB 81B0             | [d317fbeb81](https://linux-hardware.org/?probe=d317fbeb81) | Mar 11, 2019 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | [bb2ab44009](https://linux-hardware.org/?probe=bb2ab44009) | Feb 26, 2019 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | [fff09a2435](https://linux-hardware.org/?probe=fff09a2435) | Feb 26, 2019 |
| Toshiba       | Satellite L305              | [b8b1e3027d](https://linux-hardware.org/?probe=b8b1e3027d) | Feb 17, 2019 |
| Unknown       | Unknown                     | [e0bb4e4cb4](https://linux-hardware.org/?probe=e0bb4e4cb4) | Jan 14, 2019 |
| Toshiba       | Satellite L305              | [9e67a0eae4](https://linux-hardware.org/?probe=9e67a0eae4) | Dec 22, 2018 |
| HP            | Mini 110-1000               | [69af53ff8e](https://linux-hardware.org/?probe=69af53ff8e) | Dec 21, 2018 |
| HP            | 245 G5 Notebook PC          | [20db28aad6](https://linux-hardware.org/?probe=20db28aad6) | Dec 08, 2018 |
| Dell          | Latitude E6400              | [719eebfabf](https://linux-hardware.org/?probe=719eebfabf) | Nov 20, 2018 |
| Dell          | Latitude E6400              | [99cbd8eb33](https://linux-hardware.org/?probe=99cbd8eb33) | Nov 10, 2018 |
| Dell          | Latitude E6400              | [6078573db4](https://linux-hardware.org/?probe=6078573db4) | Nov 10, 2018 |
| HP            | Laptop 15-da0xxx            | [88bdb4e503](https://linux-hardware.org/?probe=88bdb4e503) | Oct 27, 2018 |
| HP            | Laptop 15-da0xxx            | [19b85d2469](https://linux-hardware.org/?probe=19b85d2469) | Oct 27, 2018 |
| Apple         | MacBookPro9,2               | [ce4d1a0c42](https://linux-hardware.org/?probe=ce4d1a0c42) | Apr 01, 2018 |
| HP            | Pavilion dv4                | [fead4bde0c](https://linux-hardware.org/?probe=fead4bde0c) | Nov 04, 2017 |
| HP            | Pavilion dv4                | [43c72d9707](https://linux-hardware.org/?probe=43c72d9707) | Oct 26, 2017 |
| Dell          | Precision M6400             | [d399313d03](https://linux-hardware.org/?probe=d399313d03) | Oct 24, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Chile/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 70        | 14.34%  |
| Ubuntu 18.04                 | 51        | 10.45%  |
| Debian 10                    | 15        | 3.07%   |
| Ubuntu 19.04                 | 14        | 2.87%   |
| Ubuntu 22.04                 | 13        | 2.66%   |
| Debian 11                    | 12        | 2.46%   |
| OpenMandriva 4.2             | 11        | 2.25%   |
| Arch                         | 11        | 2.25%   |
| OpenMandriva 4.3             | 10        | 2.05%   |
| Fedora 35                    | 10        | 2.05%   |
| Zorin 16                     | 9         | 1.84%   |
| Pop!_OS 20.04                | 9         | 1.84%   |
| Linux Mint 20.1              | 9         | 1.84%   |
| KDE neon 20.04               | 9         | 1.84%   |
| Fedora 34                    | 9         | 1.84%   |
| Zorin 15                     | 8         | 1.64%   |
| Ubuntu 21.10                 | 8         | 1.64%   |
| Ubuntu 20.10                 | 8         | 1.64%   |
| Ubuntu 19.10                 | 8         | 1.64%   |
| Manjaro                      | 8         | 1.64%   |
| Fedora 36                    | 8         | 1.64%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 1.43%   |
| ROSA R10                     | 6         | 1.23%   |
| Fedora 33                    | 6         | 1.23%   |
| Fedora 32                    | 6         | 1.23%   |
| Elementary 6.1               | 6         | 1.23%   |
| Pop!_OS 22.04                | 5         | 1.02%   |
| Linux Mint 19.3              | 5         | 1.02%   |
| Debian Testing               | 5         | 1.02%   |
| Xubuntu 18.04                | 4         | 0.82%   |
| Ubuntu 21.04                 | 4         | 0.82%   |
| Ubuntu 18.10                 | 4         | 0.82%   |
| Linux Mint 20.2              | 4         | 0.82%   |
| Linux Mint 20                | 4         | 0.82%   |
| Linux Mint 19.1              | 4         | 0.82%   |
| ArcoLinux Rolling            | 4         | 0.82%   |
| Arch Rolling                 | 4         | 0.82%   |
| Xubuntu 20.04                | 3         | 0.61%   |
| ROSA R11                     | 3         | 0.61%   |
| Pop!_OS 20.10                | 3         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu            | 179       | 37.84%  |
| Fedora            | 36        | 7.61%   |
| Linux Mint        | 31        | 6.55%   |
| Debian            | 31        | 6.55%   |
| OpenMandriva      | 22        | 4.65%   |
| Pop!_OS           | 21        | 4.44%   |
| Zorin             | 17        | 3.59%   |
| Arch              | 15        | 3.17%   |
| ROSA              | 13        | 2.75%   |
| KDE neon          | 12        | 2.54%   |
| Manjaro           | 10        | 2.11%   |
| Xubuntu           | 9         | 1.9%    |
| Elementary        | 9         | 1.9%    |
| openSUSE          | 7         | 1.48%   |
| Endless           | 6         | 1.27%   |
| Lubuntu           | 5         | 1.06%   |
| Ubuntu MATE       | 4         | 0.85%   |
| ArcoLinux         | 4         | 0.85%   |
| Ubuntu Budgie     | 3         | 0.63%   |
| LMDE              | 3         | 0.63%   |
| Kubuntu           | 3         | 0.63%   |
| Deepin            | 3         | 0.63%   |
| Clear Linux       | 3         | 0.63%   |
| Ultramarine Linux | 2         | 0.42%   |
| Ubuntu Unity      | 2         | 0.42%   |
| Solus             | 2         | 0.42%   |
| Kali              | 2         | 0.42%   |
| Gentoo            | 2         | 0.42%   |
| CentOS            | 2         | 0.42%   |
| Sparky            | 1         | 0.21%   |
| Slackware         | 1         | 0.21%   |
| RHEL              | 1         | 0.21%   |
| Reborn OS         | 1         | 0.21%   |
| Parrot            | 1         | 0.21%   |
| Nobara            | 1         | 0.21%   |
| MX                | 1         | 0.21%   |
| LinuxFX           | 1         | 0.21%   |
| Linux Lite        | 1         | 0.21%   |
| GNOME OS          | 1         | 0.21%   |
| Feren OS          | 1         | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 10        | 1.91%   |
| 5.10.14-desktop-1omv4002        | 10        | 1.91%   |
| 5.4.0-58-generic                | 8         | 1.53%   |
| 5.8.0-48-generic                | 6         | 1.15%   |
| 5.4.0-56-generic                | 6         | 1.15%   |
| 5.4.0-48-generic                | 6         | 1.15%   |
| 5.4.0-42-generic                | 6         | 1.15%   |
| 5.4.0-26-generic                | 6         | 1.15%   |
| 5.11.0-37-generic               | 6         | 1.15%   |
| 5.8.0-50-generic                | 5         | 0.95%   |
| 5.3.0-46-generic                | 5         | 0.95%   |
| 5.11.0-27-generic               | 5         | 0.95%   |
| 5.0.0-23-generic                | 5         | 0.95%   |
| 4.18.0-15-generic               | 5         | 0.95%   |
| 5.4.0-72-generic                | 4         | 0.76%   |
| 5.4.0-47-generic                | 4         | 0.76%   |
| 5.4.0-37-generic                | 4         | 0.76%   |
| 5.3.0-42-generic                | 4         | 0.76%   |
| 5.15.0-46-generic               | 4         | 0.76%   |
| 5.15.0-43-generic               | 4         | 0.76%   |
| 5.13.0-30-generic               | 4         | 0.76%   |
| 5.0.0-32-generic                | 4         | 0.76%   |
| 5.0.0-29-generic                | 4         | 0.76%   |
| 5.0.0-27-generic                | 4         | 0.76%   |
| 5.0.0-13-generic                | 4         | 0.76%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 4         | 0.76%   |
| 4.19.0-12-amd64                 | 4         | 0.76%   |
| 4.15.0-20-generic               | 4         | 0.76%   |
| 5.8.0-55-generic                | 3         | 0.57%   |
| 5.8.0-43-generic                | 3         | 0.57%   |
| 5.4.0-7634-generic              | 3         | 0.57%   |
| 5.4.0-73-generic                | 3         | 0.57%   |
| 5.4.0-66-generic                | 3         | 0.57%   |
| 5.4.0-53-generic                | 3         | 0.57%   |
| 5.4.0-52-generic                | 3         | 0.57%   |
| 5.4.0-29-generic                | 3         | 0.57%   |
| 5.4.0-28-generic                | 3         | 0.57%   |
| 5.3.0-53-generic                | 3         | 0.57%   |
| 5.3.0-51-generic                | 3         | 0.57%   |
| 5.3.0-23-generic                | 3         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 101       | 20.24%  |
| 5.11.0  | 33        | 6.61%   |
| 5.0.0   | 33        | 6.61%   |
| 5.8.0   | 32        | 6.41%   |
| 5.3.0   | 26        | 5.21%   |
| 5.15.0  | 24        | 4.81%   |
| 4.15.0  | 24        | 4.81%   |
| 5.13.0  | 18        | 3.61%   |
| 4.18.0  | 17        | 3.41%   |
| 5.10.0  | 15        | 3.01%   |
| 4.19.0  | 12        | 2.4%    |
| 5.16.7  | 10        | 2%      |
| 5.10.14 | 10        | 2%      |
| 5.14.0  | 8         | 1.6%    |
| 4.9.60  | 5         | 1%      |
| 5.19.0  | 3         | 0.6%    |
| 5.17.4  | 3         | 0.6%    |
| 5.17.13 | 3         | 0.6%    |
| 4.4.0   | 3         | 0.6%    |
| 5.9.0   | 2         | 0.4%    |
| 5.8.12  | 2         | 0.4%    |
| 5.6.0   | 2         | 0.4%    |
| 5.5.0   | 2         | 0.4%    |
| 5.19.2  | 2         | 0.4%    |
| 5.18.1  | 2         | 0.4%    |
| 5.17.5  | 2         | 0.4%    |
| 5.17.3  | 2         | 0.4%    |
| 5.16.18 | 2         | 0.4%    |
| 5.13.19 | 2         | 0.4%    |
| 5.13.13 | 2         | 0.4%    |
| 5.12.11 | 2         | 0.4%    |
| 5.11.6  | 2         | 0.4%    |
| 5.11.12 | 2         | 0.4%    |
| 5.11.11 | 2         | 0.4%    |
| 5.11.10 | 2         | 0.4%    |
| 5.10.9  | 2         | 0.4%    |
| 4.9.124 | 2         | 0.4%    |
| 5.9.9   | 1         | 0.2%    |
| 5.9.8   | 1         | 0.2%    |
| 5.9.6   | 1         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 106       | 21.37%  |
| 5.11    | 44        | 8.87%   |
| 5.10    | 41        | 8.27%   |
| 5.0     | 36        | 7.26%   |
| 5.8     | 35        | 7.06%   |
| 5.15    | 28        | 5.65%   |
| 5.3     | 27        | 5.44%   |
| 5.13    | 24        | 4.84%   |
| 4.15    | 24        | 4.84%   |
| 5.16    | 19        | 3.83%   |
| 4.18    | 18        | 3.63%   |
| 5.17    | 14        | 2.82%   |
| 4.19    | 12        | 2.42%   |
| 5.14    | 11        | 2.22%   |
| 5.19    | 9         | 1.81%   |
| 4.9     | 9         | 1.81%   |
| 5.12    | 8         | 1.61%   |
| 5.9     | 7         | 1.41%   |
| 5.5     | 5         | 1.01%   |
| 5.18    | 5         | 1.01%   |
| 5.6     | 4         | 0.81%   |
| 4.4     | 4         | 0.81%   |
| 5.1     | 3         | 0.6%    |
| 4.13    | 1         | 0.2%    |
| 3.10    | 1         | 0.2%    |
| Unknown | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 447       | 96.34%  |
| i686    | 16        | 3.45%   |
| Unknown | 1         | 0.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 218       | 45.61%  |
| Unknown         | 72        | 15.06%  |
| KDE5            | 52        | 10.88%  |
| XFCE            | 29        | 6.07%   |
| X-Cinnamon      | 26        | 5.44%   |
| KDE             | 16        | 3.35%   |
| MATE            | 10        | 2.09%   |
| Pantheon        | 9         | 1.88%   |
| KDE4            | 9         | 1.88%   |
| i3              | 7         | 1.46%   |
| Budgie          | 7         | 1.46%   |
| Cinnamon        | 5         | 1.05%   |
| LXQt            | 4         | 0.84%   |
| Deepin          | 3         | 0.63%   |
| Unity           | 2         | 0.42%   |
| qtile           | 2         | 0.42%   |
| GNOME Flashback | 2         | 0.42%   |
| Trinity         | 1         | 0.21%   |
| LXDE            | 1         | 0.21%   |
| icewm           | 1         | 0.21%   |
| bspwm           | 1         | 0.21%   |
| awesome         | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 369       | 77.85%  |
| Wayland | 64        | 13.5%   |
| Unknown | 37        | 7.81%   |
| Tty     | 4         | 0.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 289       | 60.84%  |
| GDM     | 59        | 12.42%  |
| SDDM    | 47        | 9.89%   |
| LightDM | 25        | 5.26%   |
| GDM3    | 24        | 5.05%   |
| TDM     | 18        | 3.79%   |
| KDM     | 9         | 1.89%   |
| XDM     | 3         | 0.63%   |
| SLIMSKI | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_CL      | 255       | 54.14%  |
| en_US      | 85        | 18.05%  |
| Unknown    | 74        | 15.71%  |
| es_ES      | 28        | 5.94%   |
| es_MX      | 6         | 1.27%   |
| C          | 6         | 1.27%   |
| en_GB      | 4         | 0.85%   |
| fr_FR      | 2         | 0.42%   |
| es_BO      | 2         | 0.42%   |
| es_AR      | 2         | 0.42%   |
| en_CA      | 2         | 0.42%   |
| ru_RU      | 1         | 0.21%   |
| es_VE      | 1         | 0.21%   |
| es_CO      | 1         | 0.21%   |
| es_CL.UTF8 | 1         | 0.21%   |
| de_DE      | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 254       | 54.51%  |
| BIOS | 212       | 45.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 378       | 80.08%  |
| Btrfs   | 35        | 7.42%   |
| Unknown | 33        | 6.99%   |
| Overlay | 20        | 4.24%   |
| Xfs     | 5         | 1.06%   |
| Zfs     | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 315       | 66.46%  |
| GPT     | 124       | 26.16%  |
| MBR     | 35        | 7.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 431       | 92.09%  |
| Yes       | 37        | 7.91%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 349       | 73.78%  |
| Yes       | 124       | 26.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Hewlett-Packard           | 133       | 28.73%  |
| Lenovo                    | 84        | 18.14%  |
| Dell                      | 52        | 11.23%  |
| ASUSTek Computer          | 50        | 10.8%   |
| Acer                      | 40        | 8.64%   |
| Samsung Electronics       | 24        | 5.18%   |
| Toshiba                   | 16        | 3.46%   |
| Sony                      | 12        | 2.59%   |
| Packard Bell              | 8         | 1.73%   |
| Apple                     | 7         | 1.51%   |
| Unknown                   | 6         | 1.3%    |
| HUAWEI                    | 5         | 1.08%   |
| MSI                       | 4         | 0.86%   |
| Google                    | 2         | 0.43%   |
| AMI                       | 2         | 0.43%   |
| SK hynix                  | 1         | 0.22%   |
| Render                    | 1         | 0.22%   |
| Positivo                  | 1         | 0.22%   |
| Personal Computer Factory | 1         | 0.22%   |
| OX                        | 1         | 0.22%   |
| OEM                       | 1         | 0.22%   |
| MOTILE                    | 1         | 0.22%   |
| Medion                    | 1         | 0.22%   |
| LG Electronics            | 1         | 0.22%   |
| Intel                     | 1         | 0.22%   |
| Insyde                    | 1         | 0.22%   |
| HONOR                     | 1         | 0.22%   |
| Elife                     | 1         | 0.22%   |
| Creative Vision           | 1         | 0.22%   |
| Corporativo Lanix         | 1         | 0.22%   |
| Clevo                     | 1         | 0.22%   |
| Alienware                 | 1         | 0.22%   |
| A-DATA Technology         | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                           | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| HP Notebook                                    | 10        | 2.16%   |
| Unknown                                        | 10        | 2.16%   |
| HP Pavilion Notebook                           | 6         | 1.3%    |
| HP 240 G6 Notebook PC                          | 6         | 1.3%    |
| HP Pavilion 15                                 | 5         | 1.08%   |
| HP ENVY 15                                     | 4         | 0.86%   |
| Lenovo Legion Y530-15ICH 81FV                  | 3         | 0.65%   |
| HP ProBook 440 G3                              | 3         | 0.65%   |
| HP Pavilion Laptop 15-eh0xxx                   | 3         | 0.65%   |
| HP Pavilion g4                                 | 3         | 0.65%   |
| HP EliteBook 840 G6                            | 3         | 0.65%   |
| HP EliteBook 2560p                             | 3         | 0.65%   |
| HP 14                                          | 3         | 0.65%   |
| HP 1000                                        | 3         | 0.65%   |
| Dell Latitude E6420                            | 3         | 0.65%   |
| Dell Inspiron 14-3467                          | 3         | 0.65%   |
| Apple MacBookPro9,2                            | 3         | 0.65%   |
| Acer Aspire ES1-111M                           | 3         | 0.65%   |
| Toshiba Satellite L745                         | 2         | 0.43%   |
| Toshiba Satellite C845D                        | 2         | 0.43%   |
| Samsung RF511/RF411/RF711                      | 2         | 0.43%   |
| Samsung 750XED                                 | 2         | 0.43%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV | 2         | 0.43%   |
| Packard Bell EasyNote MH35                     | 2         | 0.43%   |
| Lenovo Y520-15IKBN 80WK                        | 2         | 0.43%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY           | 2         | 0.43%   |
| Lenovo IdeaPad 720S-14IKB 80XC                 | 2         | 0.43%   |
| Lenovo IdeaPad 330S-15ARR 81FB                 | 2         | 0.43%   |
| Lenovo IdeaPad 320-15ABR 80XS                  | 2         | 0.43%   |
| Lenovo G400 20235                              | 2         | 0.43%   |
| HUAWEI BOHK-WAX9X                              | 2         | 0.43%   |
| HP ProBook 640 G1                              | 2         | 0.43%   |
| HP Pavilion Laptop 15-cw1xxx                   | 2         | 0.43%   |
| HP Pavilion Laptop 15-cw0xxx                   | 2         | 0.43%   |
| HP Pavilion dv4                                | 2         | 0.43%   |
| HP Laptop 15-da0xxx                            | 2         | 0.43%   |
| HP Laptop 15-bs0xx                             | 2         | 0.43%   |
| HP ENVY 17 Leap Motion SE NB PC                | 2         | 0.43%   |
| HP EliteBook 840 G5                            | 2         | 0.43%   |
| HP 250 G5 Notebook PC                          | 2         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 35        | 7.56%   |
| HP Pavilion           | 33        | 7.13%   |
| Lenovo IdeaPad        | 31        | 6.7%    |
| Acer Aspire           | 30        | 6.48%   |
| Dell Inspiron         | 23        | 4.97%   |
| HP EliteBook          | 15        | 3.24%   |
| Dell Latitude         | 15        | 3.24%   |
| Toshiba Satellite     | 12        | 2.59%   |
| ASUS VivoBook         | 12        | 2.59%   |
| HP Laptop             | 11        | 2.38%   |
| HP ProBook            | 10        | 2.16%   |
| HP Notebook           | 10        | 2.16%   |
| HP ENVY               | 10        | 2.16%   |
| Unknown               | 10        | 2.16%   |
| HP 240                | 9         | 1.94%   |
| Packard Bell EasyNote | 6         | 1.3%    |
| HP 245                | 6         | 1.3%    |
| Acer Swift            | 6         | 1.3%    |
| Lenovo Legion         | 5         | 1.08%   |
| ASUS ZenBook          | 5         | 1.08%   |
| ASUS TUF              | 5         | 1.08%   |
| HP 250                | 4         | 0.86%   |
| Dell Vostro           | 4         | 0.86%   |
| ASUS ASUS             | 4         | 0.86%   |
| Toshiba PORTEGE       | 3         | 0.65%   |
| Samsung 300E5EV       | 3         | 0.65%   |
| HP Presario           | 3         | 0.65%   |
| HP 14                 | 3         | 0.65%   |
| HP 1000               | 3         | 0.65%   |
| Dell XPS              | 3         | 0.65%   |
| Dell Precision        | 3         | 0.65%   |
| Apple MacBookPro9     | 3         | 0.65%   |
| Samsung RF511         | 2         | 0.43%   |
| Samsung R430          | 2         | 0.43%   |
| Samsung 750XED        | 2         | 0.43%   |
| Lenovo Y520-15IKBN    | 2         | 0.43%   |
| Lenovo G400           | 2         | 0.43%   |
| HUAWEI BOHK-WAX9X     | 2         | 0.43%   |
| HP Compaq             | 2         | 0.43%   |
| HP 15                 | 2         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 55        | 11.88%  |
| 2011 | 43        | 9.29%   |
| 2019 | 42        | 9.07%   |
| 2020 | 39        | 8.42%   |
| 2018 | 39        | 8.42%   |
| 2013 | 39        | 8.42%   |
| 2012 | 33        | 7.13%   |
| 2015 | 32        | 6.91%   |
| 2016 | 28        | 6.05%   |
| 2014 | 28        | 6.05%   |
| 2010 | 23        | 4.97%   |
| 2021 | 17        | 3.67%   |
| 2009 | 16        | 3.46%   |
| 2008 | 14        | 3.02%   |
| 2007 | 10        | 2.16%   |
| 2022 | 4         | 0.86%   |
| 2006 | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 463       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 412       | 88.22%  |
| Enabled  | 55        | 11.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 461       | 99.57%  |
| Yes  | 2         | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 148       | 31.69%  |
| 3.01-4.0    | 117       | 25.05%  |
| 8.01-16.0   | 83        | 17.77%  |
| 16.01-24.0  | 56        | 11.99%  |
| 1.01-2.0    | 28        | 6%      |
| 32.01-64.0  | 14        | 3%      |
| 2.01-3.0    | 11        | 2.36%   |
| 24.01-32.0  | 6         | 1.28%   |
| 0.51-1.0    | 2         | 0.43%   |
| 64.01-256.0 | 1         | 0.21%   |
| Unknown     | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 183       | 36.38%  |
| 2.01-3.0   | 121       | 24.06%  |
| 3.01-4.0   | 79        | 15.71%  |
| 4.01-8.0   | 66        | 13.12%  |
| 0.51-1.0   | 37        | 7.36%   |
| 8.01-16.0  | 12        | 2.39%   |
| 0.01-0.5   | 3         | 0.6%    |
| 24.01-32.0 | 1         | 0.2%    |
| Unknown    | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 369       | 78.85%  |
| 2      | 88        | 18.8%   |
| 3      | 7         | 1.5%    |
| 0      | 4         | 0.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 311       | 67.03%  |
| Yes       | 153       | 32.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 391       | 84.45%  |
| No        | 72        | 15.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 456       | 98.49%  |
| No        | 7         | 1.51%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 355       | 76.02%  |
| No        | 112       | 23.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Chile   | 463       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Santiago            | 132       | 27.39%  |
| Viña del Mar       | 26        | 5.39%   |
| Puente Alto         | 21        | 4.36%   |
| Maipu               | 18        | 3.73%   |
| Las Condes          | 18        | 3.73%   |
| Concepción         | 15        | 3.11%   |
| Temuco              | 12        | 2.49%   |
| San Miguel          | 12        | 2.49%   |
| Providencia         | 12        | 2.49%   |
| Nunoa               | 12        | 2.49%   |
| La Florida          | 12        | 2.49%   |
| La Serena           | 10        | 2.07%   |
| Valdivia            | 9         | 1.87%   |
| Port Montt          | 7         | 1.45%   |
| Iquique             | 7         | 1.45%   |
| Coronel             | 7         | 1.45%   |
| Quilpué            | 6         | 1.24%   |
| Antofagasta         | 6         | 1.24%   |
| Rancagua            | 5         | 1.04%   |
| Valparaíso         | 4         | 0.83%   |
| Talcahuano          | 4         | 0.83%   |
| San Bernardo        | 4         | 0.83%   |
| Osorno              | 4         | 0.83%   |
| Los Ángeles        | 4         | 0.83%   |
| La Reina            | 4         | 0.83%   |
| Independencia       | 4         | 0.83%   |
| Curicó             | 4         | 0.83%   |
| Coquimbo            | 4         | 0.83%   |
| Copiapó            | 4         | 0.83%   |
| Villa Alemana       | 3         | 0.62%   |
| San Pedro de la Paz | 3         | 0.62%   |
| Quilicura           | 3         | 0.62%   |
| Punta Arenas        | 3         | 0.62%   |
| Penalolen           | 3         | 0.62%   |
| Melipilla           | 3         | 0.62%   |
| Macul               | 3         | 0.62%   |
| Los Andes           | 3         | 0.62%   |
| La Calera           | 3         | 0.62%   |
| Colina              | 3         | 0.62%   |
| Vitacura            | 2         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 98        | 121    | 18.28%  |
| Seagate                     | 61        | 79     | 11.38%  |
| Toshiba                     | 55        | 63     | 10.26%  |
| Samsung Electronics         | 54        | 65     | 10.07%  |
| Kingston                    | 42        | 53     | 7.84%   |
| Crucial                     | 36        | 39     | 6.72%   |
| Unknown                     | 29        | 36     | 5.41%   |
| HGST                        | 26        | 26     | 4.85%   |
| Hitachi                     | 24        | 25     | 4.48%   |
| SanDisk                     | 23        | 24     | 4.29%   |
| SK hynix                    | 17        | 18     | 3.17%   |
| Intel                       | 13        | 22     | 2.43%   |
| Apple                       | 6         | 6      | 1.12%   |
| Micron Technology           | 5         | 6      | 0.93%   |
| KingSpec                    | 5         | 12     | 0.93%   |
| China                       | 4         | 5      | 0.75%   |
| LITEON                      | 3         | 3      | 0.56%   |
| KIOXIA                      | 3         | 4      | 0.56%   |
| JMicron Technology          | 3         | 3      | 0.56%   |
| SSSTC                       | 2         | 2      | 0.37%   |
| Micron/Crucial Technology   | 2         | 2      | 0.37%   |
| Corsair                     | 2         | 2      | 0.37%   |
| A-DATA Technology           | 2         | 4      | 0.37%   |
| XPG                         | 1         | 1      | 0.19%   |
| Wdxsky                      | 1         | 1      | 0.19%   |
| WALRAM                      | 1         | 1      | 0.19%   |
| Vaseky                      | 1         | 1      | 0.19%   |
| UMIS                        | 1         | 1      | 0.19%   |
| Phison                      | 1         | 1      | 0.19%   |
| Netac                       | 1         | 1      | 0.19%   |
| Mass                        | 1         | 1      | 0.19%   |
| LITEONIT                    | 1         | 1      | 0.19%   |
| Lexar                       | 1         | 5      | 0.19%   |
| Kingston Technology Company | 1         | 1      | 0.19%   |
| KingDian                    | 1         | 2      | 0.19%   |
| HUAWEI                      | 1         | 1      | 0.19%   |
| HS-SSD-E100N                | 1         | 1      | 0.19%   |
| Hewlett-Packard             | 1         | 1      | 0.19%   |
| Gigabyte Technology         | 1         | 1      | 0.19%   |
| Fujitsu                     | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB            | 12        | 2.15%   |
| Seagate ST1000LM035-1RK172 1TB      | 12        | 2.15%   |
| Toshiba MQ01ABD100 1TB              | 8         | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 8         | 1.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 7         | 1.25%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 7         | 1.25%   |
| Samsung NVMe SSD Drive 512GB        | 7         | 1.25%   |
| Kingston SA400S37480G 480GB SSD     | 7         | 1.25%   |
| Kingston SA400S37240G 240GB SSD     | 7         | 1.25%   |
| HGST HTS545050A7E680 500GB          | 7         | 1.25%   |
| Crucial CT240BX500SSD1 240GB        | 7         | 1.25%   |
| Unknown MMC Card  64GB              | 6         | 1.07%   |
| Unknown MMC Card  32GB              | 6         | 1.07%   |
| Toshiba MQ04ABF100 1TB              | 6         | 1.07%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 6         | 1.07%   |
| Crucial CT480BX500SSD1 480GB        | 6         | 1.07%   |
| Crucial CT120BX500SSD1 120GB        | 6         | 1.07%   |
| Toshiba MQ01ABD075 752GB            | 5         | 0.89%   |
| Seagate ST9500325AS 500GB           | 5         | 0.89%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 0.89%   |
| Kingston SNVS500G 500GB             | 5         | 0.89%   |
| HGST HTS541010A9E680 1TB            | 5         | 0.89%   |
| WDC WD10SPZX-60Z10T0 1TB            | 4         | 0.72%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 0.72%   |
| SanDisk NVMe SSD Drive 500GB        | 4         | 0.72%   |
| Samsung NVMe SSD Drive 1024GB       | 4         | 0.72%   |
| Samsung HN-M500MBB 500GB            | 4         | 0.72%   |
| Intel NVMe SSD Drive 512GB          | 4         | 0.72%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 0.72%   |
| HGST HTS541010B7E610 1TB            | 4         | 0.72%   |
| Crucial CT120BX300SSD1 120GB        | 4         | 0.72%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 3         | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 0.54%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 3         | 0.54%   |
| WDC WD5000LPCX-21VHAT0 500GB        | 3         | 0.54%   |
| WDC WD2500LPVX-22V0TT0 250GB        | 3         | 0.54%   |
| WDC WD10SPZX-75Z10T2 1TB            | 3         | 0.54%   |
| WDC WD10SPZX-24Z10 1TB              | 3         | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 0.54%   |
| Unknown MMC Card  128GB             | 3         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 67        | 77     | 27.92%  |
| Seagate             | 61        | 79     | 25.42%  |
| Toshiba             | 49        | 54     | 20.42%  |
| HGST                | 26        | 26     | 10.83%  |
| Hitachi             | 24        | 25     | 10%     |
| Samsung Electronics | 8         | 10     | 3.33%   |
| Unknown             | 2         | 2      | 0.83%   |
| Apple               | 2         | 2      | 0.83%   |
| Fujitsu             | 1         | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 36        | 39     | 21.69%  |
| WDC                 | 30        | 39     | 18.07%  |
| Kingston            | 30        | 39     | 18.07%  |
| Samsung Electronics | 20        | 21     | 12.05%  |
| SanDisk             | 13        | 14     | 7.83%   |
| KingSpec            | 5         | 12     | 3.01%   |
| China               | 4         | 5      | 2.41%   |
| Apple               | 4         | 4      | 2.41%   |
| Toshiba             | 2         | 5      | 1.2%    |
| SK hynix            | 2         | 2      | 1.2%    |
| LITEON              | 2         | 2      | 1.2%    |
| Intel               | 2         | 3      | 1.2%    |
| Corsair             | 2         | 2      | 1.2%    |
| A-DATA Technology   | 2         | 4      | 1.2%    |
| Wdxsky              | 1         | 1      | 0.6%    |
| Vaseky              | 1         | 1      | 0.6%    |
| Netac               | 1         | 1      | 0.6%    |
| Micron Technology   | 1         | 1      | 0.6%    |
| LITEONIT            | 1         | 1      | 0.6%    |
| Lexar               | 1         | 5      | 0.6%    |
| KingDian            | 1         | 2      | 0.6%    |
| Hewlett-Packard     | 1         | 1      | 0.6%    |
| Gigabyte Technology | 1         | 1      | 0.6%    |
| FORESEE             | 1         | 2      | 0.6%    |
| Faspeed             | 1         | 1      | 0.6%    |
| Unknown             | 1         | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 237       | 276    | 45.4%   |
| SSD     | 158       | 209    | 30.27%  |
| NVMe    | 95        | 123    | 18.2%   |
| MMC     | 27        | 34     | 5.17%   |
| Unknown | 5         | 5      | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 368       | 482    | 74.04%  |
| NVMe | 93        | 121    | 18.71%  |
| MMC  | 27        | 34     | 5.43%   |
| SAS  | 9         | 10     | 1.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 262       | 335    | 68.59%  |
| 0.51-1.0   | 116       | 146    | 30.37%  |
| 1.01-2.0   | 4         | 4      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 155       | 32.16%  |
| 101-250        | 144       | 29.88%  |
| 501-1000       | 74        | 15.35%  |
| 1-20           | 31        | 6.43%   |
| 51-100         | 25        | 5.19%   |
| 21-50          | 21        | 4.36%   |
| 1001-2000      | 18        | 3.73%   |
| Unknown        | 9         | 1.87%   |
| 2001-3000      | 3         | 0.62%   |
| More than 3000 | 2         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 208       | 41.77%  |
| 21-50     | 94        | 18.88%  |
| 101-250   | 64        | 12.85%  |
| 51-100    | 64        | 12.85%  |
| 251-500   | 40        | 8.03%   |
| 501-1000  | 17        | 3.41%   |
| Unknown   | 9         | 1.81%   |
| 1001-2000 | 2         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB          | 3         | 3      | 8.57%   |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 5.71%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 5.71%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 1      | 2.86%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD    | 1         | 1      | 2.86%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 2.86%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 2.86%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 2.86%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 2.86%   |
| Vaseky V820/1TB 1024GB              | 1         | 1      | 2.86%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 2.86%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 2.86%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 2.86%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 2.86%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 5      | 2.86%   |
| LITEON CV8-8E128-HP 128GB SSD       | 1         | 1      | 2.86%   |
| Kingston SVP200S3120G 120GB SSD     | 1         | 1      | 2.86%   |
| Hitachi HTS722016K9A300 160GB       | 1         | 1      | 2.86%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 2      | 2.86%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 2.86%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 2.86%   |
| Hitachi HTS543232L9A300 320GB       | 1         | 1      | 2.86%   |
| HGST HTS725032A7E630 320GB          | 1         | 1      | 2.86%   |
| HGST HTS545050A7E660 500GB          | 1         | 1      | 2.86%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 2.86%   |
| HGST HTS541075A9E680 752GB          | 1         | 1      | 2.86%   |
| HGST HTS541010B7E610 1TB            | 1         | 1      | 2.86%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 2.86%   |
| Faspeed H5-500G SSD                 | 1         | 1      | 2.86%   |
| Crucial CT480M500SSD1 480GB         | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| HGST     | 9         | 9      | 25.71%  |
| Seagate  | 7         | 11     | 20%     |
| WDC      | 6         | 6      | 17.14%  |
| Hitachi  | 5         | 6      | 14.29%  |
| Toshiba  | 3         | 3      | 8.57%   |
| Vaseky   | 1         | 1      | 2.86%   |
| LITEON   | 1         | 1      | 2.86%   |
| Kingston | 1         | 1      | 2.86%   |
| Faspeed  | 1         | 1      | 2.86%   |
| Crucial  | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 9         | 9      | 32.14%  |
| Seagate | 7         | 11     | 25%     |
| Hitachi | 5         | 6      | 17.86%  |
| WDC     | 4         | 4      | 14.29%  |
| Toshiba | 3         | 3      | 10.71%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 33     | 80%     |
| SSD  | 7         | 7      | 20%     |

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
| Detected | 320       | 437    | 65.98%  |
| Works    | 130       | 170    | 26.8%   |
| Malfunc  | 35        | 40     | 7.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 313       | 63.23%  |
| AMD                              | 81        | 16.36%  |
| Samsung Electronics              | 32        | 6.46%   |
| SK hynix                         | 15        | 3.03%   |
| SanDisk                          | 15        | 3.03%   |
| Kingston Technology Company      | 13        | 2.63%   |
| Toshiba America Info Systems     | 4         | 0.81%   |
| Silicon Integrated Systems [SiS] | 4         | 0.81%   |
| Micron Technology                | 4         | 0.81%   |
| KIOXIA                           | 3         | 0.61%   |
| Solid State Storage Technology   | 2         | 0.4%    |
| Nvidia                           | 2         | 0.4%    |
| Micron/Crucial Technology        | 2         | 0.4%    |
| ADATA Technology                 | 2         | 0.4%    |
| Union Memory (Shenzhen)          | 1         | 0.2%    |
| Phison Electronics               | 1         | 0.2%    |
| Lite-On Technology               | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 70        | 13.28%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 56        | 10.63%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 36        | 6.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 25        | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 20        | 3.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 19        | 3.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 17        | 3.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 16        | 3.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 13        | 2.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 12        | 2.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 11        | 2.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 9         | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 9         | 1.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 8         | 1.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 8         | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 7         | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 7         | 1.33%   |
| Samsung NVMe SSD Controller 980                                                        | 6         | 1.14%   |
| Kingston Company Company Non-Volatile memory controller                                | 6         | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.14%   |
| SK hynix Non-Volatile memory controller                                                | 5         | 0.95%   |
| SK hynix Gold P31 SSD                                                                  | 5         | 0.95%   |
| SK hynix BC511                                                                         | 5         | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 0.95%   |
| Intel Non-Volatile memory controller                                                   | 5         | 0.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 5         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 5         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 5         | 0.95%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 5         | 0.95%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 4         | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 0.76%   |
| Micron Non-Volatile memory controller                                                  | 4         | 0.76%   |
| Intel SSD 660P Series                                                                  | 4         | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 4         | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 4         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 4         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.76%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 3         | 0.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 3         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 341       | 67.66%  |
| NVMe | 94        | 18.65%  |
| RAID | 35        | 6.94%   |
| IDE  | 34        | 6.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 358       | 77.32%  |
| AMD    | 105       | 22.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 2.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 2.16%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 1.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.3%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 6         | 1.3%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 1.3%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 5         | 1.08%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 1.08%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 1.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.08%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 1.08%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 5         | 1.08%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 4         | 0.86%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 4         | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.86%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 4         | 0.86%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 0.86%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 3         | 0.65%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.65%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.65%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 3         | 0.65%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.65%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.65%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.65%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.65%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 0.65%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.65%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 3         | 0.65%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.65%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 3         | 0.65%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 3         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 100       | 21.6%   |
| Intel Core i7           | 79        | 17.06%  |
| Intel Core i3           | 47        | 10.15%  |
| Intel Celeron           | 38        | 8.21%   |
| Intel Pentium           | 23        | 4.97%   |
| Intel Atom              | 17        | 3.67%   |
| AMD Ryzen 5             | 17        | 3.67%   |
| Other                   | 14        | 3.02%   |
| Intel Core 2 Duo        | 14        | 3.02%   |
| AMD Ryzen 7             | 11        | 2.38%   |
| AMD A10                 | 11        | 2.38%   |
| AMD Ryzen 3             | 9         | 1.94%   |
| Intel Pentium Dual-Core | 8         | 1.73%   |
| AMD A8                  | 8         | 1.73%   |
| AMD E2                  | 6         | 1.3%    |
| AMD E1                  | 6         | 1.3%    |
| AMD A6                  | 6         | 1.3%    |
| Intel Pentium Dual      | 5         | 1.08%   |
| AMD E                   | 4         | 0.86%   |
| AMD A4                  | 4         | 0.86%   |
| AMD A12                 | 4         | 0.86%   |
| Intel Genuine           | 3         | 0.65%   |
| Intel Celeron Dual-Core | 3         | 0.65%   |
| AMD Turion II Dual-Core | 3         | 0.65%   |
| Intel Pentium Silver    | 2         | 0.43%   |
| Intel Core i9           | 2         | 0.43%   |
| AMD Ryzen 7 PRO         | 2         | 0.43%   |
| AMD Ryzen 5 PRO         | 2         | 0.43%   |
| AMD Mobile Sempron      | 2         | 0.43%   |
| AMD C-60                | 2         | 0.43%   |
| AMD Athlon II           | 2         | 0.43%   |
| Intel Xeon              | 1         | 0.22%   |
| Intel Core m5           | 1         | 0.22%   |
| Intel Core Duo          | 1         | 0.22%   |
| Intel Core 2 Extreme    | 1         | 0.22%   |
| Intel Core 2            | 1         | 0.22%   |
| AMD Ryzen 9             | 1         | 0.22%   |
| AMD C-50                | 1         | 0.22%   |
| AMD Athlon X2           | 1         | 0.22%   |
| AMD Athlon              | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 278       | 59.91%  |
| 4       | 148       | 31.9%   |
| 8       | 13        | 2.8%    |
| 6       | 10        | 2.16%   |
| 1       | 8         | 1.72%   |
| Unknown | 5         | 1.08%   |
| 10      | 2         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 461       | 99.57%  |
| 4       | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 296       | 63.79%  |
| 1       | 163       | 35.13%  |
| Unknown | 5         | 1.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 445       | 95.7%   |
| Unknown        | 10        | 2.15%   |
| 64-bit         | 5         | 1.08%   |
| 32-bit         | 5         | 1.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 16.45%  |
| 0x206a7    | 30        | 6.41%   |
| 0x406e3    | 28        | 5.98%   |
| 0x306a9    | 22        | 4.7%    |
| 0x40651    | 18        | 3.85%   |
| 0x806e9    | 17        | 3.63%   |
| 0x1067a    | 16        | 3.42%   |
| 0x806ec    | 15        | 3.21%   |
| 0x30678    | 14        | 2.99%   |
| 0x806ea    | 12        | 2.56%   |
| 0x20655    | 12        | 2.56%   |
| 0x906ea    | 11        | 2.35%   |
| 0x306d4    | 10        | 2.14%   |
| 0x05000119 | 9         | 1.92%   |
| 0x906e9    | 8         | 1.71%   |
| 0x6fd      | 8         | 1.71%   |
| 0x406c4    | 8         | 1.71%   |
| 0x806c1    | 7         | 1.5%    |
| 0x306c3    | 7         | 1.5%    |
| 0x08108109 | 7         | 1.5%    |
| 0x08108102 | 7         | 1.5%    |
| 0x406c3    | 6         | 1.28%   |
| 0x0a50000c | 6         | 1.28%   |
| 0x08600106 | 6         | 1.28%   |
| 0x0810100b | 6         | 1.28%   |
| 0xa0652    | 5         | 1.07%   |
| 0x706a1    | 5         | 1.07%   |
| 0x506c9    | 5         | 1.07%   |
| 0x106ca    | 5         | 1.07%   |
| 0x0700010f | 5         | 1.07%   |
| 0x706e5    | 4         | 0.85%   |
| 0x706a8    | 4         | 0.85%   |
| 0x10676    | 4         | 0.85%   |
| 0x07030106 | 4         | 0.85%   |
| 0x07030105 | 4         | 0.85%   |
| 0x06006705 | 4         | 0.85%   |
| 0x06001119 | 4         | 0.85%   |
| 0x506e3    | 3         | 0.64%   |
| 0x106c2    | 3         | 0.64%   |
| 0x906c0    | 2         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 86        | 18.57%  |
| SandyBridge      | 38        | 8.21%   |
| Skylake          | 35        | 7.56%   |
| Silvermont       | 30        | 6.48%   |
| Haswell          | 30        | 6.48%   |
| IvyBridge        | 26        | 5.62%   |
| Penryn           | 24        | 5.18%   |
| Westmere         | 17        | 3.67%   |
| Zen+             | 16        | 3.46%   |
| Excavator        | 15        | 3.24%   |
| Zen 2            | 12        | 2.59%   |
| Broadwell        | 12        | 2.59%   |
| Bobcat           | 12        | 2.59%   |
| TigerLake        | 10        | 2.16%   |
| Core             | 10        | 2.16%   |
| Puma             | 9         | 1.94%   |
| Goldmont plus    | 9         | 1.94%   |
| Bonnell          | 9         | 1.94%   |
| Zen              | 7         | 1.51%   |
| Piledriver       | 7         | 1.51%   |
| Jaguar           | 7         | 1.51%   |
| Zen 3            | 6         | 1.3%    |
| CometLake        | 6         | 1.3%    |
| K10              | 5         | 1.08%   |
| Goldmont         | 5         | 1.08%   |
| IceLake          | 4         | 0.86%   |
| Unknown          | 4         | 0.86%   |
| K10 Llano        | 3         | 0.65%   |
| Tremont          | 2         | 0.43%   |
| P6               | 2         | 0.43%   |
| K8 Hammer        | 2         | 0.43%   |
| Steamroller      | 1         | 0.22%   |
| K8 & K10 hybrid  | 1         | 0.22%   |
| Alderlake Hybrid | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 334       | 59.22%  |
| AMD                              | 127       | 22.52%  |
| Nvidia                           | 98        | 17.38%  |
| Silicon Integrated Systems [SiS] | 4         | 0.71%   |
| ATI Technologies                 | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 36        | 6.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 26        | 4.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 4.19%   |
| Intel HD Graphics 620                                                                    | 21        | 3.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 3.35%   |
| Intel UHD Graphics 620                                                                   | 17        | 2.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 2.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 2.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 2.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 15        | 2.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 2.18%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 13        | 2.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 2.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.01%   |
| AMD Renoir                                                                               | 12        | 2.01%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 1.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 1.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.51%   |
| Intel HD Graphics 630                                                                    | 8         | 1.34%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.34%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 8         | 1.34%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 1.17%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 1.17%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.01%   |
| AMD Cezanne                                                                              | 6         | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.84%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.84%   |
| Intel HD Graphics 510                                                                    | 5         | 0.84%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 0.84%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 5         | 0.84%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.67%   |
| Nvidia TU117M                                                                            | 4         | 0.67%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 242       | 52.27%  |
| 1 x AMD        | 77        | 16.63%  |
| Intel + Nvidia | 73        | 15.77%  |
| 2 x AMD        | 23        | 4.97%   |
| Intel + AMD    | 19        | 4.1%    |
| 1 x Nvidia     | 16        | 3.46%   |
| AMD + Nvidia   | 9         | 1.94%   |
| 1 x SiS        | 4         | 0.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 399       | 85.81%  |
| Proprietary | 47        | 10.11%  |
| Unknown     | 19        | 4.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 280       | 59.7%   |
| 0.01-0.5   | 73        | 15.57%  |
| 1.01-2.0   | 61        | 13.01%  |
| 0.51-1.0   | 27        | 5.76%   |
| 3.01-4.0   | 23        | 4.9%    |
| 5.01-6.0   | 2         | 0.43%   |
| 2.01-3.0   | 2         | 0.43%   |
| 7.01-8.0   | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 97        | 18.83%  |
| BOE                     | 89        | 17.28%  |
| Samsung Electronics     | 73        | 14.17%  |
| Chimei Innolux          | 72        | 13.98%  |
| LG Display              | 65        | 12.62%  |
| Goldstar                | 15        | 2.91%   |
| Lenovo                  | 10        | 1.94%   |
| Chi Mei Optoelectronics | 8         | 1.55%   |
| PANDA                   | 7         | 1.36%   |
| InfoVision              | 7         | 1.36%   |
| Apple                   | 7         | 1.36%   |
| ViewSonic               | 6         | 1.17%   |
| Sony                    | 5         | 0.97%   |
| Sharp                   | 5         | 0.97%   |
| AOC                     | 5         | 0.97%   |
| Envision                | 4         | 0.78%   |
| Dell                    | 4         | 0.78%   |
| Unknown                 | 3         | 0.58%   |
| SAC                     | 3         | 0.58%   |
| LG Philips              | 3         | 0.58%   |
| CSO                     | 3         | 0.58%   |
| ASUSTek Computer        | 3         | 0.58%   |
| LGD                     | 2         | 0.39%   |
| InnoLux Display         | 2         | 0.39%   |
| Hewlett-Packard         | 2         | 0.39%   |
| CPT                     | 2         | 0.39%   |
| Ancor Communications    | 2         | 0.39%   |
| Acer                    | 2         | 0.39%   |
| ___                     | 1         | 0.19%   |
| STA                     | 1         | 0.19%   |
| SLD                     | 1         | 0.19%   |
| SGT                     | 1         | 0.19%   |
| NCS                     | 1         | 0.19%   |
| MSI                     | 1         | 0.19%   |
| Hitachi                 | 1         | 0.19%   |
| HannStar                | 1         | 0.19%   |
| ELD                     | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 9         | 1.73%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 5         | 0.96%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 5         | 0.96%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 5         | 0.96%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 5         | 0.96%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 5         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch | 4         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 4         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 4         | 0.77%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 4         | 0.77%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 4         | 0.77%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 4         | 0.77%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 4         | 0.77%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 3         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch | 3         | 0.58%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 3         | 0.58%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 3         | 0.58%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 3         | 0.58%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 3         | 0.58%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 3         | 0.58%   |
| Envision L32W931 EPI2009 1360x768 696x392mm 31.4-inch                | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch      | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 3         | 0.58%   |
| BOE LCD Monitor BOE0920 1366x768 344x194mm 15.5-inch                 | 3         | 0.58%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 3         | 0.58%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 3         | 0.58%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 3         | 0.58%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 3         | 0.58%   |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                 | 3         | 0.58%   |
| BOE LCD Monitor BOE0602 1366x768 344x193mm 15.5-inch                 | 3         | 0.58%   |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                 | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch        | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 3         | 0.58%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 3         | 0.58%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 2         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 244       | 49.59%  |
| 1920x1080 (FHD)    | 141       | 28.66%  |
| 1600x900 (HD+)     | 20        | 4.07%   |
| 1280x800 (WXGA)    | 17        | 3.46%   |
| 1360x768           | 11        | 2.24%   |
| 3840x2160 (4K)     | 10        | 2.03%   |
| 1440x900 (WXGA+)   | 7         | 1.42%   |
| 1920x1200 (WUXGA)  | 5         | 1.02%   |
| 1280x1024 (SXGA)   | 5         | 1.02%   |
| 2560x1600          | 4         | 0.81%   |
| 1680x1050 (WSXGA+) | 4         | 0.81%   |
| 1024x600           | 4         | 0.81%   |
| 3840x1100          | 2         | 0.41%   |
| 3440x1440          | 2         | 0.41%   |
| 2560x1080          | 2         | 0.41%   |
| 2160x1440          | 2         | 0.41%   |
| 1024x576           | 2         | 0.41%   |
| Unknown            | 2         | 0.41%   |
| 5440x1800          | 1         | 0.2%    |
| 3840x2400          | 1         | 0.2%    |
| 3286x1080          | 1         | 0.2%    |
| 2560x1440 (QHD)    | 1         | 0.2%    |
| 2288x1287          | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1680x945           | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 154       | 29.73%  |
| 13      | 121       | 23.36%  |
| 14      | 109       | 21.04%  |
| 23      | 20        | 3.86%   |
| 17      | 14        | 2.7%    |
| 21      | 13        | 2.51%   |
| 12      | 9         | 1.74%   |
| 11      | 9         | 1.74%   |
| 24      | 8         | 1.54%   |
| 10      | 8         | 1.54%   |
| 19      | 7         | 1.35%   |
| Unknown | 7         | 1.35%   |
| 31      | 6         | 1.16%   |
| 27      | 6         | 1.16%   |
| 72      | 4         | 0.77%   |
| 34      | 4         | 0.77%   |
| 20      | 3         | 0.58%   |
| 18      | 3         | 0.58%   |
| 54      | 2         | 0.39%   |
| 48      | 2         | 0.39%   |
| 32      | 2         | 0.39%   |
| 22      | 2         | 0.39%   |
| 16      | 2         | 0.39%   |
| 142     | 1         | 0.19%   |
| 84      | 1         | 0.19%   |
| 43      | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 348       | 67.97%  |
| 201-300        | 59        | 11.52%  |
| 501-600        | 32        | 6.25%   |
| 401-500        | 23        | 4.49%   |
| 351-400        | 19        | 3.71%   |
| 601-700        | 7         | 1.37%   |
| Unknown        | 7         | 1.37%   |
| 701-800        | 6         | 1.17%   |
| 1501-2000      | 5         | 0.98%   |
| 1001-1500      | 4         | 0.78%   |
| More than 2000 | 1         | 0.2%    |
| 901-1000       | 1         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 389       | 86.06%  |
| 16/10   | 42        | 9.29%   |
| 5/4     | 5         | 1.11%   |
| 21/9    | 4         | 0.88%   |
| Unknown | 4         | 0.88%   |
| 4/3     | 2         | 0.44%   |
| 3/2     | 2         | 0.44%   |
| 3.40    | 2         | 0.44%   |
| 1.96    | 1         | 0.22%   |
| 1.00    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 198       | 38.3%   |
| 101-110        | 152       | 29.4%   |
| 201-250        | 36        | 6.96%   |
| 71-80          | 30        | 5.8%    |
| 151-200        | 14        | 2.71%   |
| 351-500        | 12        | 2.32%   |
| 51-60          | 11        | 2.13%   |
| 121-130        | 10        | 1.93%   |
| More than 1000 | 9         | 1.74%   |
| 61-70          | 8         | 1.55%   |
| 41-50          | 8         | 1.55%   |
| Unknown        | 7         | 1.35%   |
| 301-350        | 6         | 1.16%   |
| 141-150        | 5         | 0.97%   |
| 111-120        | 3         | 0.58%   |
| 251-300        | 2         | 0.39%   |
| 131-140        | 2         | 0.39%   |
| 501-1000       | 2         | 0.39%   |
| 91-100         | 2         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 258       | 50.39%  |
| 121-160       | 134       | 26.17%  |
| 51-100        | 71        | 13.87%  |
| 161-240       | 21        | 4.1%    |
| 1-50          | 15        | 2.93%   |
| Unknown       | 7         | 1.37%   |
| More than 240 | 6         | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 370       | 78.39%  |
| 2     | 76        | 16.1%   |
| 0     | 18        | 3.81%   |
| 3     | 8         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 293       | 39.54%  |
| Intel                            | 173       | 23.35%  |
| Qualcomm Atheros                 | 123       | 16.6%   |
| Broadcom                         | 50        | 6.75%   |
| Ralink                           | 16        | 2.16%   |
| Marvell Technology Group         | 10        | 1.35%   |
| Huawei Technologies              | 10        | 1.35%   |
| Broadcom Limited                 | 9         | 1.21%   |
| TP-Link                          | 8         | 1.08%   |
| Ralink Technology                | 7         | 0.94%   |
| Samsung Electronics              | 5         | 0.67%   |
| MediaTek                         | 5         | 0.67%   |
| Xiaomi                           | 4         | 0.54%   |
| Silicon Integrated Systems [SiS] | 4         | 0.54%   |
| Qualcomm Atheros Communications  | 4         | 0.54%   |
| JMicron Technology               | 4         | 0.54%   |
| ICS Advent                       | 3         | 0.4%    |
| Nvidia                           | 2         | 0.27%   |
| D-Link                           | 2         | 0.27%   |
| Qcom                             | 1         | 0.13%   |
| Microsoft                        | 1         | 0.13%   |
| Microchip Technology             | 1         | 0.13%   |
| Hewlett-Packard                  | 1         | 0.13%   |
| DisplayLink                      | 1         | 0.13%   |
| D-Link System                    | 1         | 0.13%   |
| ASUSTek Computer                 | 1         | 0.13%   |
| Arduino SA                       | 1         | 0.13%   |
| Apple                            | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 165       | 18.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 88        | 9.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 24        | 2.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 2.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 21        | 2.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 2.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 2.13%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 15        | 1.68%   |
| Intel Wireless 8265 / 8275                                              | 15        | 1.68%   |
| Intel Wireless 8260                                                     | 15        | 1.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 1.57%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 1.34%   |
| Intel Wireless 7260                                                     | 11        | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 10        | 1.12%   |
| Intel Wireless 7265                                                     | 10        | 1.12%   |
| Intel Ethernet Connection I219-LM                                       | 9         | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 0.89%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.89%   |
| Huawei YAL-L21                                                          | 8         | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.78%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.78%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 6         | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.67%   |
| Intel Ethernet Connection (4) I219-V                                    | 6         | 0.67%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 5         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 168       | 34.71%  |
| Realtek Semiconductor           | 111       | 22.93%  |
| Qualcomm Atheros                | 110       | 22.73%  |
| Broadcom                        | 41        | 8.47%   |
| Ralink                          | 16        | 3.31%   |
| Broadcom Limited                | 8         | 1.65%   |
| TP-Link                         | 7         | 1.45%   |
| Ralink Technology               | 7         | 1.45%   |
| MediaTek                        | 5         | 1.03%   |
| Qualcomm Atheros Communications | 4         | 0.83%   |
| Samsung Electronics             | 1         | 0.21%   |
| Qcom                            | 1         | 0.21%   |
| Microsoft                       | 1         | 0.21%   |
| Hewlett-Packard                 | 1         | 0.21%   |
| D-Link System                   | 1         | 0.21%   |
| D-Link                          | 1         | 0.21%   |
| ASUSTek Computer                | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 5.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 24        | 4.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 4.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 21        | 4.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 4.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 3.91%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 15        | 3.09%   |
| Intel Wireless 8265 / 8275                                              | 15        | 3.09%   |
| Intel Wireless 8260                                                     | 15        | 3.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 2.88%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 2.47%   |
| Intel Wireless 7260                                                     | 11        | 2.26%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.06%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 10        | 2.06%   |
| Intel Wireless 7265                                                     | 10        | 2.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 1.44%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 1.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.23%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 1.03%   |
| Intel Wireless 3165                                                     | 5         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.03%   |
| TP-Link 802.11ac WLAN Adapter                                           | 4         | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.82%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.82%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.82%   |
| Intel Wireless 3160                                                     | 4         | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 263       | 64.78%  |
| Intel                            | 58        | 14.29%  |
| Qualcomm Atheros                 | 24        | 5.91%   |
| Broadcom                         | 15        | 3.69%   |
| Marvell Technology Group         | 10        | 2.46%   |
| Huawei Technologies              | 9         | 2.22%   |
| Xiaomi                           | 4         | 0.99%   |
| Silicon Integrated Systems [SiS] | 4         | 0.99%   |
| Samsung Electronics              | 4         | 0.99%   |
| JMicron Technology               | 4         | 0.99%   |
| ICS Advent                       | 3         | 0.74%   |
| Nvidia                           | 2         | 0.49%   |
| TP-Link                          | 1         | 0.25%   |
| Microchip Technology             | 1         | 0.25%   |
| DisplayLink                      | 1         | 0.25%   |
| D-Link                           | 1         | 0.25%   |
| Broadcom Limited                 | 1         | 0.25%   |
| Apple                            | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 165       | 40.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 88        | 21.67%  |
| Intel Ethernet Connection I219-LM                                 | 9         | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.97%   |
| Huawei YAL-L21                                                    | 8         | 1.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 1.48%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 1.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.23%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 1.23%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 4         | 0.99%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.99%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.99%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.74%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.74%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.74%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.49%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.49%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.49%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.49%   |
| ICS Advent 10/100M LAN                                            | 2         | 0.49%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.49%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.25%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 456       | 53.71%  |
| Ethernet | 391       | 46.05%  |
| Modem    | 2         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 380       | 78.84%  |
| Ethernet | 102       | 21.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 356       | 76.89%  |
| 1     | 94        | 20.3%   |
| 0     | 8         | 1.73%   |
| 3     | 5         | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 433       | 93.12%  |
| Yes  | 32        | 6.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 131       | 36.49%  |
| Realtek Semiconductor           | 67        | 18.66%  |
| Qualcomm Atheros Communications | 37        | 10.31%  |
| Broadcom                        | 26        | 7.24%   |
| IMC Networks                    | 21        | 5.85%   |
| Lite-On Technology              | 20        | 5.57%   |
| Foxconn / Hon Hai               | 12        | 3.34%   |
| Ralink                          | 8         | 2.23%   |
| Dell                            | 7         | 1.95%   |
| Apple                           | 7         | 1.95%   |
| Realtek                         | 5         | 1.39%   |
| Hewlett-Packard                 | 4         | 1.11%   |
| Toshiba                         | 3         | 0.84%   |
| Ralink Technology               | 3         | 0.84%   |
| Foxconn International           | 2         | 0.56%   |
| Cambridge Silicon Radio         | 2         | 0.56%   |
| ASUSTek Computer                | 2         | 0.56%   |
| MediaTek                        | 1         | 0.28%   |
| Alps Electric                   | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 61        | 16.99%  |
| Realtek Bluetooth Radio                                                             | 38        | 10.58%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 28        | 7.8%    |
| Intel AX201 Bluetooth                                                               | 21        | 5.85%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 18        | 5.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 4.46%   |
| Intel AX200 Bluetooth                                                               | 12        | 3.34%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 9         | 2.51%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 2.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 2.23%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 8         | 2.23%   |
| IMC Networks Bluetooth Radio                                                        | 8         | 2.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 1.95%   |
| IMC Networks Bluetooth Device                                                       | 7         | 1.95%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 6         | 1.67%   |
| Realtek Bluetooth Radio                                                             | 5         | 1.39%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 1.39%   |
| Lite-On Bluetooth Device                                                            | 5         | 1.39%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 1.11%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 4         | 1.11%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.84%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 3         | 0.84%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 0.84%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.84%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 3         | 0.84%   |
| Dell Wireless 365 Bluetooth                                                         | 3         | 0.84%   |
| Broadcom HP Portable Bumble Bee                                                     | 3         | 0.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.56%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 2         | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.56%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.56%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.56%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.56%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 345       | 66.35%  |
| AMD                              | 109       | 20.96%  |
| Nvidia                           | 40        | 7.69%   |
| C-Media Electronics              | 5         | 0.96%   |
| Silicon Integrated Systems [SiS] | 4         | 0.77%   |
| Logitech                         | 3         | 0.58%   |
| Generalplus Technology           | 2         | 0.38%   |
| Shenzhen Riitek Technology       | 1         | 0.19%   |
| Plantronics                      | 1         | 0.19%   |
| Pixart Imaging                   | 1         | 0.19%   |
| Microsoft                        | 1         | 0.19%   |
| Lenovo                           | 1         | 0.19%   |
| Kingston Technology              | 1         | 0.19%   |
| Focusrite-Novation               | 1         | 0.19%   |
| ESS Technology                   | 1         | 0.19%   |
| DigiTech                         | 1         | 0.19%   |
| Creative Technology              | 1         | 0.19%   |
| Apple                            | 1         | 0.19%   |
| Unknown                          | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 71        | 10.91%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 42        | 6.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 39        | 5.99%   |
| AMD FCH Azalia Controller                                                                         | 34        | 5.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 3.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 24        | 3.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 23        | 3.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 2.92%   |
| Intel 8 Series HD Audio Controller                                                                | 19        | 2.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 17        | 2.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 2.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 2.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 2%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 1.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.84%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 1.84%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 1.54%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 1.54%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 1.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 1.38%   |
| AMD Wrestler HDMI Audio                                                                           | 9         | 1.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.08%   |
| AMD Trinity HDMI Audio Controller                                                                 | 7         | 1.08%   |
| AMD High Definition Audio Controller                                                              | 7         | 1.08%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 0.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.77%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 0.77%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 0.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.61%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.46%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 94        | 33.22%  |
| SK hynix            | 55        | 19.43%  |
| Micron Technology   | 40        | 14.13%  |
| Crucial             | 27        | 9.54%   |
| Kingston            | 24        | 8.48%   |
| Ramaxel Technology  | 12        | 4.24%   |
| Unknown             | 11        | 3.89%   |
| A-DATA Technology   | 4         | 1.41%   |
| Nanya Technology    | 2         | 0.71%   |
| G.Skill             | 2         | 0.71%   |
| Corsair             | 2         | 0.71%   |
| Unknown (ABCD)      | 1         | 0.35%   |
| Unknown (090E)      | 1         | 0.35%   |
| Unknown (08C8)      | 1         | 0.35%   |
| Smart               | 1         | 0.35%   |
| PNY                 | 1         | 0.35%   |
| Kllisre             | 1         | 0.35%   |
| Elpida              | 1         | 0.35%   |
| ASint Technology    | 1         | 0.35%   |
| 48spaces            | 1         | 0.35%   |
| Unknown             | 1         | 0.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 3.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 5         | 1.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 1.69%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 1.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.35%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 1.35%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 4         | 1.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.01%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 1.01%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.01%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 3         | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.01%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.01%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.01%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 3         | 1.01%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 3         | 1.01%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 1.01%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 3         | 1.01%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s          | 3         | 1.01%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 2         | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2         | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.68%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.68%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.68%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.68%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.68%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.68%   |
| Samsung RAM K4U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s     | 2         | 0.68%   |
| Samsung RAM 16HTF25664HY-667E1 4096MB SODIMM DDR2 800MT/s        | 2         | 0.68%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.68%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 102       | 46.58%  |
| DDR3   | 83        | 37.9%   |
| LPDDR4 | 11        | 5.02%   |
| LPDDR3 | 9         | 4.11%   |
| DDR2   | 8         | 3.65%   |
| SDRAM  | 5         | 2.28%   |
| RAM    | 1         | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 194       | 90.65%  |
| Row Of Chips | 18        | 8.41%   |
| DIMM         | 1         | 0.47%   |
| Unknown      | 1         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 108       | 44.26%  |
| 8192  | 85        | 34.84%  |
| 2048  | 24        | 9.84%   |
| 16384 | 23        | 9.43%   |
| 1024  | 3         | 1.23%   |
| 64    | 1         | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 65        | 25.9%   |
| 2667    | 52        | 20.72%  |
| 3200    | 32        | 12.75%  |
| 2400    | 25        | 9.96%   |
| 2133    | 18        | 7.17%   |
| 1334    | 11        | 4.38%   |
| 3266    | 9         | 3.59%   |
| 1333    | 7         | 2.79%   |
| 667     | 6         | 2.39%   |
| 4267    | 4         | 1.59%   |
| 800     | 4         | 1.59%   |
| 4199    | 3         | 1.2%    |
| Unknown | 3         | 1.2%    |
| 4266    | 2         | 0.8%    |
| 2048    | 2         | 0.8%    |
| 1867    | 2         | 0.8%    |
| 1067    | 2         | 0.8%    |
| 8400    | 1         | 0.4%    |
| 975     | 1         | 0.4%    |
| 933     | 1         | 0.4%    |
| 533     | 1         | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Brother HL-1200 series | 1         | 50%     |
| Brother DCP-1600       | 1         | 50%     |

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
| Chicony Electronics                    | 102       | 23.5%   |
| IMC Networks                           | 53        | 12.21%  |
| Realtek Semiconductor                  | 35        | 8.06%   |
| Microdia                               | 31        | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 7.14%   |
| Sunplus Innovation Technology          | 26        | 5.99%   |
| Acer                                   | 24        | 5.53%   |
| Suyin                                  | 18        | 4.15%   |
| Lite-On Technology                     | 18        | 4.15%   |
| Silicon Motion                         | 15        | 3.46%   |
| Quanta                                 | 15        | 3.46%   |
| Apple                                  | 7         | 1.61%   |
| Syntek                                 | 6         | 1.38%   |
| Luxvisions Innotech Limited            | 5         | 1.15%   |
| Z-Star Microelectronics                | 4         | 0.92%   |
| Ricoh                                  | 4         | 0.92%   |
| Importek                               | 4         | 0.92%   |
| Samsung Electronics                    | 3         | 0.69%   |
| Logitech                               | 3         | 0.69%   |
| Alcor Micro                            | 3         | 0.69%   |
| SunplusIT                              | 2         | 0.46%   |
| Sonix Technology                       | 2         | 0.46%   |
| Lenovo                                 | 2         | 0.46%   |
| Leap Motion                            | 2         | 0.46%   |
| KYE Systems (Mouse Systems)            | 2         | 0.46%   |
| Foxconn / Hon Hai                      | 2         | 0.46%   |
| DigiTech                               | 2         | 0.46%   |
| ALi                                    | 2         | 0.46%   |
| USB Camera CS                          | 1         | 0.23%   |
| Sunplus Technology                     | 1         | 0.23%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.23%   |
| Ruision                                | 1         | 0.23%   |
| OmniVision Technologies                | 1         | 0.23%   |
| Microsoft                              | 1         | 0.23%   |
| Intel                                  | 1         | 0.23%   |
| Huawei Technologies                    | 1         | 0.23%   |
| Generalplus Technology                 | 1         | 0.23%   |
| GEMBIRD                                | 1         | 0.23%   |
| ARC International                      | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 21        | 4.82%   |
| Chicony Integrated Camera                                       | 12        | 2.75%   |
| Chicony HD Webcam                                               | 11        | 2.52%   |
| IMC Networks Integrated Camera                                  | 10        | 2.29%   |
| Realtek Integrated_Webcam_HD                                    | 7         | 1.61%   |
| Realtek HP Truevision HD                                        | 7         | 1.61%   |
| Lite-On Integrated Camera                                       | 7         | 1.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 7         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 7         | 1.61%   |
| Suyin HP TrueVision HD                                          | 6         | 1.38%   |
| Chicony HP Webcam                                               | 6         | 1.38%   |
| Chicony EasyCamera                                              | 6         | 1.38%   |
| Acer Integrated Camera                                          | 6         | 1.38%   |
| Sunplus HP TrueVision HD Camera                                 | 5         | 1.15%   |
| Microdia Integrated_Webcam_HD                                   | 5         | 1.15%   |
| Microdia HP Webcam                                              | 5         | 1.15%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 5         | 1.15%   |
| Chicony HP Truevision HD camera                                 | 5         | 1.15%   |
| Chicony HP Truevision HD                                        | 5         | 1.15%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 5         | 1.15%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD         | 5         | 1.15%   |
| Sunplus Laptop Integrated WebCam HD                             | 4         | 0.92%   |
| Silicon Motion WebCam SCB-1100N                                 | 4         | 0.92%   |
| Realtek USB Camera                                              | 4         | 0.92%   |
| Realtek HP "Truevision HD" laptop camera                        | 4         | 0.92%   |
| Quanta HP TrueVision HD Camera                                  | 4         | 0.92%   |
| Lite-On HP Wide Vision HD Camera                                | 4         | 0.92%   |
| Chicony VGA Webcam                                              | 4         | 0.92%   |
| Chicony HP Wide Vision HD Camera                                | 4         | 0.92%   |
| Chicony HP HD Camera                                            | 4         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 4         | 0.92%   |
| Acer EasyCamera                                                 | 4         | 0.92%   |
| Syntek Integrated Camera                                        | 3         | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 3         | 0.69%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 3         | 0.69%   |
| Sunplus Integrated_Webcam_HD                                    | 3         | 0.69%   |
| Sunplus HD WebCam                                               | 3         | 0.69%   |
| Samsung Galaxy A5 (MTP)                                         | 3         | 0.69%   |
| Quanta VGA WebCam                                               | 3         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 30        | 45.45%  |
| Synaptics                  | 16        | 24.24%  |
| Shenzhen Goodix Technology | 5         | 7.58%   |
| AuthenTec                  | 4         | 6.06%   |
| Upek                       | 3         | 4.55%   |
| Elan Microelectronics      | 3         | 4.55%   |
| STMicroelectronics         | 2         | 3.03%   |
| LighTuning Technology      | 2         | 3.03%   |
| Focal-systems.Corp         | 1         | 1.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 10.61%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 6.06%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 6.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 4.55%   |
| Synaptics  WBDI                                                            | 3         | 4.55%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.55%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 4.55%   |
| AuthenTec AES2810                                                          | 3         | 4.55%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.03%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 3.03%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.03%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.03%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.52%   |
| Validity Sensors VFS491                                                    | 1         | 1.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.52%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.52%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.52%   |
| AuthenTec AES1600                                                          | 1         | 1.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 14        | 82.35%  |
| O2 Micro | 2         | 11.76%  |
| Upek     | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 29.41%  |
| Broadcom 5880                                                                | 5         | 29.41%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 17.65%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.88%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.88%   |
| Broadcom 58200                                                               | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 313       | 66.88%  |
| 1     | 127       | 27.14%  |
| 2     | 26        | 5.56%   |
| 5     | 1         | 0.21%   |
| 4     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 66        | 36.67%  |
| Graphics card            | 36        | 20%     |
| Net/wireless             | 26        | 14.44%  |
| Chipcard                 | 16        | 8.89%   |
| Bluetooth                | 11        | 6.11%   |
| Multimedia controller    | 9         | 5%      |
| Storage                  | 4         | 2.22%   |
| Communication controller | 4         | 2.22%   |
| Sound                    | 2         | 1.11%   |
| Net/ethernet             | 2         | 1.11%   |
| Card reader              | 2         | 1.11%   |
| Camera                   | 2         | 1.11%   |

