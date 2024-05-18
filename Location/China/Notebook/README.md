Linux in China - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in China.

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

Total: 1390

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T480 20L5A023HK    | [ff78bb7112](https://linux-hardware.org/?probe=ff78bb7112) | May 07, 2024 |
| Lenovo        | XiaoXin-15IIL 2020 81YL     | [b95cda619a](https://linux-hardware.org/?probe=b95cda619a) | May 06, 2024 |
| Apple         | MacBookPro8,1               | [2487a975e8](https://linux-hardware.org/?probe=2487a975e8) | May 06, 2024 |
| ASUSTek       | X450CC                      | [1085d5cad5](https://linux-hardware.org/?probe=1085d5cad5) | May 05, 2024 |
| Unknown       | Unknown                     | [ce0eb6aa57](https://linux-hardware.org/?probe=ce0eb6aa57) | May 05, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [db370ffb35](https://linux-hardware.org/?probe=db370ffb35) | May 05, 2024 |
| Apple         | MacBookPro8,1               | [54ecba24d6](https://linux-hardware.org/?probe=54ecba24d6) | May 04, 2024 |
| METAPHYUNI    | MetawillBook03              | [d5af716feb](https://linux-hardware.org/?probe=d5af716feb) | May 04, 2024 |
| Apple         | MacBookPro5,5               | [2ddfed1c8a](https://linux-hardware.org/?probe=2ddfed1c8a) | May 01, 2024 |
| Timi          | RedmiBook Pro 14S           | [a330c6b15e](https://linux-hardware.org/?probe=a330c6b15e) | Apr 28, 2024 |
| Haier         | N1406W                      | [1c70c3d8b2](https://linux-hardware.org/?probe=1c70c3d8b2) | Apr 26, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | [5e4ee36b4a](https://linux-hardware.org/?probe=5e4ee36b4a) | Apr 25, 2024 |
| MECHREVO      | WUJIE14XA                   | [c43bb34bc6](https://linux-hardware.org/?probe=c43bb34bc6) | Apr 23, 2024 |
| MECHREVO      | WUJIE14XA                   | [2b34ae91ef](https://linux-hardware.org/?probe=2b34ae91ef) | Apr 22, 2024 |
| Ruijie        | RG-Rain305E                 | [48f650b68e](https://linux-hardware.org/?probe=48f650b68e) | Apr 19, 2024 |
| Unknown       | X133                        | [b12f5e7b59](https://linux-hardware.org/?probe=b12f5e7b59) | Apr 18, 2024 |
| Lenovo        | ZHAOYANG E43                | [1192eac8f1](https://linux-hardware.org/?probe=1192eac8f1) | Apr 17, 2024 |
| HUAWEI        | NbDE-WXX9                   | [ae3aece643](https://linux-hardware.org/?probe=ae3aece643) | Apr 16, 2024 |
| Dell          | Inspiron 14 5420            | [6ae28bdf30](https://linux-hardware.org/?probe=6ae28bdf30) | Apr 14, 2024 |
| HUAWEI        | KLVL-WXX9                   | [cbeae24a2b](https://linux-hardware.org/?probe=cbeae24a2b) | Apr 12, 2024 |
| Lenovo        | ThinkBook 16 G6+ AHP 21L... | [52de364ea7](https://linux-hardware.org/?probe=52de364ea7) | Apr 11, 2024 |
| Dell          | Latitude E6440              | [727e37c03c](https://linux-hardware.org/?probe=727e37c03c) | Apr 10, 2024 |
| GITSTAR       | GDC-1461                    | [fcb625bfff](https://linux-hardware.org/?probe=fcb625bfff) | Apr 10, 2024 |
| Acer          | Swift SFX14-41G             | [47966edb56](https://linux-hardware.org/?probe=47966edb56) | Apr 09, 2024 |
| HUAWEI        | KLVL-WXX9                   | [d1451542a0](https://linux-hardware.org/?probe=d1451542a0) | Apr 08, 2024 |
| HUAWEI        | HKD-WXX                     | [a1e39d45ea](https://linux-hardware.org/?probe=a1e39d45ea) | Apr 07, 2024 |
| Lenovo        | ThinkPad X390 20Q00039CD    | [9e8475784d](https://linux-hardware.org/?probe=9e8475784d) | Apr 05, 2024 |
| Lenovo        | G40-80 80E4                 | [76642434b9](https://linux-hardware.org/?probe=76642434b9) | Apr 05, 2024 |
| HP            | EliteBook 8730w             | [342f90f8c1](https://linux-hardware.org/?probe=342f90f8c1) | Apr 05, 2024 |
| HP            | EliteBook 8730w             | [b4c4b71cdb](https://linux-hardware.org/?probe=b4c4b71cdb) | Apr 05, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [e759ee33bf](https://linux-hardware.org/?probe=e759ee33bf) | Apr 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [d0c6efef85](https://linux-hardware.org/?probe=d0c6efef85) | Apr 03, 2024 |
| Dell          | Vostro 5590                 | [9046f24617](https://linux-hardware.org/?probe=9046f24617) | Apr 03, 2024 |
| MECHREVO      | Code01 Ver2.0               | [559e9886b1](https://linux-hardware.org/?probe=559e9886b1) | Mar 31, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [5eccb2015c](https://linux-hardware.org/?probe=5eccb2015c) | Mar 29, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5ae20a11dc](https://linux-hardware.org/?probe=5ae20a11dc) | Mar 29, 2024 |
| Toshiba       | Satellite L700              | [d2073d2786](https://linux-hardware.org/?probe=d2073d2786) | Mar 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [aeb6dba24f](https://linux-hardware.org/?probe=aeb6dba24f) | Mar 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9641d580da](https://linux-hardware.org/?probe=9641d580da) | Mar 28, 2024 |
| Unknown       | sun8i                       | [ffd31fc8c2](https://linux-hardware.org/?probe=ffd31fc8c2) | Mar 28, 2024 |
| Lenovo        | V14-ARE 82DQ                | [f7e010a048](https://linux-hardware.org/?probe=f7e010a048) | Mar 27, 2024 |
| Lenovo        | IdeaPad Y410P 20216         | [40a6b1e81c](https://linux-hardware.org/?probe=40a6b1e81c) | Mar 23, 2024 |
| Lenovo        | IdeaPad Y410P 20216         | [75974a7deb](https://linux-hardware.org/?probe=75974a7deb) | Mar 23, 2024 |
| Shanghai Z... | ZXE CRB                     | [9046eff55a](https://linux-hardware.org/?probe=9046eff55a) | Mar 22, 2024 |
| HONOR         | HYM-WXX                     | [2d11f15773](https://linux-hardware.org/?probe=2d11f15773) | Mar 22, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TAA... | [de970e3adc](https://linux-hardware.org/?probe=de970e3adc) | Mar 21, 2024 |
| HONOR         | GLO-GXXX                    | [aa0a3c2273](https://linux-hardware.org/?probe=aa0a3c2273) | Mar 19, 2024 |
| HONOR         | GLO-GXXX                    | [e6fbe7ffad](https://linux-hardware.org/?probe=e6fbe7ffad) | Mar 19, 2024 |
| Lenovo        | YangTian S550-14-API 82B... | [d91083aa5c](https://linux-hardware.org/?probe=d91083aa5c) | Mar 19, 2024 |
| Lenovo        | ThinkPad L490 20Q6A2MYCD    | [171ff29e85](https://linux-hardware.org/?probe=171ff29e85) | Mar 19, 2024 |
| Lenovo        | ThinkPad L490 20Q6A2MYCD    | [1fe1956a79](https://linux-hardware.org/?probe=1fe1956a79) | Mar 19, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C11... | [043dcda6e9](https://linux-hardware.org/?probe=043dcda6e9) | Mar 18, 2024 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [1df66c1a5d](https://linux-hardware.org/?probe=1df66c1a5d) | Mar 18, 2024 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [4b3021b1db](https://linux-hardware.org/?probe=4b3021b1db) | Mar 17, 2024 |
| Valve         | Galileo                     | [94545cd73f](https://linux-hardware.org/?probe=94545cd73f) | Mar 16, 2024 |
| Shanghai Z... | ZXE CRB                     | [18b2050901](https://linux-hardware.org/?probe=18b2050901) | Mar 14, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | [91890298e9](https://linux-hardware.org/?probe=91890298e9) | Mar 14, 2024 |
| Insyde        | BayTrail                    | [89d859d241](https://linux-hardware.org/?probe=89d859d241) | Mar 14, 2024 |
| Acer          | S50-54                      | [9fcc7996c7](https://linux-hardware.org/?probe=9fcc7996c7) | Mar 12, 2024 |
| Lenovo        | KaiTian N80z G1d            | [cf81d4918a](https://linux-hardware.org/?probe=cf81d4918a) | Mar 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [9d9bbf3378](https://linux-hardware.org/?probe=9d9bbf3378) | Mar 11, 2024 |
| Lenovo        | XiaoXinPro 14 AHP9 83D3     | [fe15e50e85](https://linux-hardware.org/?probe=fe15e50e85) | Mar 09, 2024 |
| Lenovo        | ZHAOYANG K4e-IML 81VQ       | [748726f682](https://linux-hardware.org/?probe=748726f682) | Mar 09, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [201df141f4](https://linux-hardware.org/?probe=201df141f4) | Mar 07, 2024 |
| Acer          | S50-54                      | [70296abf24](https://linux-hardware.org/?probe=70296abf24) | Mar 07, 2024 |
| Lenovo        | Unknown                     | [32588f809f](https://linux-hardware.org/?probe=32588f809f) | Mar 07, 2024 |
| Timi          | RedmiBook Pro 15S           | [402f19be59](https://linux-hardware.org/?probe=402f19be59) | Mar 02, 2024 |
| HONOR         | NMH-WCX9                    | [80f1759519](https://linux-hardware.org/?probe=80f1759519) | Mar 02, 2024 |
| HONOR         | NMH-WCX9                    | [bd909cfa51](https://linux-hardware.org/?probe=bd909cfa51) | Mar 02, 2024 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [56d3aefd4b](https://linux-hardware.org/?probe=56d3aefd4b) | Mar 01, 2024 |
| Timi          | TM1612                      | [8805cb7e87](https://linux-hardware.org/?probe=8805cb7e87) | Mar 01, 2024 |
| HP            | Laptop 15g-dr0xxx           | [8ac7be2322](https://linux-hardware.org/?probe=8ac7be2322) | Feb 29, 2024 |
| HP            | Laptop 15g-dr0xxx           | [c57a0747d5](https://linux-hardware.org/?probe=c57a0747d5) | Feb 29, 2024 |
| MECHREVO      | JiguangPro Series GM6PQ7... | [3d3ce46c84](https://linux-hardware.org/?probe=3d3ce46c84) | Feb 29, 2024 |
| Lenovo        | ThinkPad E14 20RA003CCD     | [c8cbfa128f](https://linux-hardware.org/?probe=c8cbfa128f) | Feb 29, 2024 |
| Anbernic      | Win600                      | [309a79c0c5](https://linux-hardware.org/?probe=309a79c0c5) | Feb 28, 2024 |
| Intel         | H81U                        | [80fbd74068](https://linux-hardware.org/?probe=80fbd74068) | Feb 25, 2024 |
| Acer          | TravelMate P249-G2-M        | [09fc7e1bb9](https://linux-hardware.org/?probe=09fc7e1bb9) | Feb 24, 2024 |
| Lenovo        | ThinkPad E450c 20EH0001C... | [75c5905fab](https://linux-hardware.org/?probe=75c5905fab) | Feb 21, 2024 |
| XIAOMI        | Redmi Book 16 2024 (Gen1... | [aa280685df](https://linux-hardware.org/?probe=aa280685df) | Feb 21, 2024 |
| Dell          | Inspiron 16 Plus 7630       | [a98e400993](https://linux-hardware.org/?probe=a98e400993) | Feb 19, 2024 |
| Acer          | Swift SF314-512             | [8bc80a2f94](https://linux-hardware.org/?probe=8bc80a2f94) | Feb 18, 2024 |
| XIAOMI        | Redmi Book 16 2024 (Gen1... | [48959e4424](https://linux-hardware.org/?probe=48959e4424) | Feb 17, 2024 |
| MECHREVO      | WUJIE14 PRO                 | [343f712c04](https://linux-hardware.org/?probe=343f712c04) | Feb 17, 2024 |
| Acer          | Predator PH317-56           | [dc130d91e8](https://linux-hardware.org/?probe=dc130d91e8) | Feb 17, 2024 |
| MSI           | Alpha 17 C7VG               | [c6580a01b8](https://linux-hardware.org/?probe=c6580a01b8) | Feb 13, 2024 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [6f6961026c](https://linux-hardware.org/?probe=6f6961026c) | Feb 13, 2024 |
| Lenovo        | ThinkPad E550 20DFA06NCD    | [7858b1e150](https://linux-hardware.org/?probe=7858b1e150) | Feb 12, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [41dcbdad69](https://linux-hardware.org/?probe=41dcbdad69) | Feb 09, 2024 |
| Lenovo        | Reserver for OEM 2OAVZ08... | [19855922a9](https://linux-hardware.org/?probe=19855922a9) | Feb 09, 2024 |
| HP            | Victus by Gaming Laptop ... | [3b920b7ddd](https://linux-hardware.org/?probe=3b920b7ddd) | Feb 08, 2024 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [cd4c156951](https://linux-hardware.org/?probe=cd4c156951) | Feb 08, 2024 |
| Valve         | Jupiter                     | [85375b8312](https://linux-hardware.org/?probe=85375b8312) | Feb 07, 2024 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | [66c0cc51e3](https://linux-hardware.org/?probe=66c0cc51e3) | Feb 06, 2024 |
| Unknown       | Unknown                     | [7f23752859](https://linux-hardware.org/?probe=7f23752859) | Feb 06, 2024 |
| Lenovo        | Legion R70002021 82JW       | [292593aa58](https://linux-hardware.org/?probe=292593aa58) | Feb 05, 2024 |
| Lenovo        | ThinkPad E480 20KN001ACD    | [43827bde86](https://linux-hardware.org/?probe=43827bde86) | Feb 05, 2024 |
| Apple         | MacBookPro11,2              | [1466cd2d4f](https://linux-hardware.org/?probe=1466cd2d4f) | Feb 04, 2024 |
| XIAOMI        | Redmi Book 16 2024 (Gen1... | [517ddc9a76](https://linux-hardware.org/?probe=517ddc9a76) | Feb 03, 2024 |
| MECHREVO      | S1 Pro Series               | [ba68410f96](https://linux-hardware.org/?probe=ba68410f96) | Feb 02, 2024 |
| MECHREVO      | WUJIE14 PRO                 | [5e58868dbf](https://linux-hardware.org/?probe=5e58868dbf) | Jan 30, 2024 |
| Lenovo        | G40-45 80E1                 | [1e01df8e73](https://linux-hardware.org/?probe=1e01df8e73) | Jan 27, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TDA... | [6456dc0020](https://linux-hardware.org/?probe=6456dc0020) | Jan 26, 2024 |
| Dell          | Inspiron 5557               | [e331563298](https://linux-hardware.org/?probe=e331563298) | Jan 22, 2024 |
| HP            | ProBook 455R G6             | [59026d385f](https://linux-hardware.org/?probe=59026d385f) | Jan 21, 2024 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [bfbba978c3](https://linux-hardware.org/?probe=bfbba978c3) | Jan 16, 2024 |
| Dell          | Inspiron 5557               | [938a3ee950](https://linux-hardware.org/?probe=938a3ee950) | Jan 16, 2024 |
| Dell          | Vostro 5470                 | [21f78f0847](https://linux-hardware.org/?probe=21f78f0847) | Jan 16, 2024 |
| HP            | ProBook 450 15.6 inch G1... | [54ed51acbb](https://linux-hardware.org/?probe=54ed51acbb) | Jan 15, 2024 |
| Acer          | Swift SFX14-41G             | [947678b939](https://linux-hardware.org/?probe=947678b939) | Jan 15, 2024 |
| Timi          | TM1612                      | [89ef61c3ee](https://linux-hardware.org/?probe=89ef61c3ee) | Jan 14, 2024 |
| MECHREVO      | S1 Pro Series               | [419dfc25b2](https://linux-hardware.org/?probe=419dfc25b2) | Jan 08, 2024 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [1188890272](https://linux-hardware.org/?probe=1188890272) | Jan 07, 2024 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [cb8f846b0f](https://linux-hardware.org/?probe=cb8f846b0f) | Jan 07, 2024 |
| Dell          | Inspiron 5493               | [eb9b8edc2c](https://linux-hardware.org/?probe=eb9b8edc2c) | Jan 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [98da18a6c0](https://linux-hardware.org/?probe=98da18a6c0) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2602d65d52](https://linux-hardware.org/?probe=2602d65d52) | Jan 06, 2024 |
| MECHREVO      | S1 Pro Series               | [da21c08192](https://linux-hardware.org/?probe=da21c08192) | Jan 06, 2024 |
| KUU           | Andes II                    | [512394ef85](https://linux-hardware.org/?probe=512394ef85) | Jan 04, 2024 |
| Timi          | TM1709                      | [79d0628d57](https://linux-hardware.org/?probe=79d0628d57) | Jan 03, 2024 |
| Timi          | TM1709                      | [b934e033e4](https://linux-hardware.org/?probe=b934e033e4) | Jan 03, 2024 |
| MECHREVO      | S2 Air Series PF4NU1F       | [08703baf6e](https://linux-hardware.org/?probe=08703baf6e) | Jan 03, 2024 |
| Valve         | Jupiter                     | [b3ada6c407](https://linux-hardware.org/?probe=b3ada6c407) | Jan 02, 2024 |
| Lenovo        | Legion Y7000P2020H 82AX     | [59d5eb147b](https://linux-hardware.org/?probe=59d5eb147b) | Jan 01, 2024 |
| Timi          | A34R                        | [d72018ec19](https://linux-hardware.org/?probe=d72018ec19) | Dec 29, 2023 |
| Google        | Dratini                     | [a81971bf37](https://linux-hardware.org/?probe=a81971bf37) | Dec 28, 2023 |
| Dell          | Vostro 5470                 | [25e05316e9](https://linux-hardware.org/?probe=25e05316e9) | Dec 28, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [151f072ac9](https://linux-hardware.org/?probe=151f072ac9) | Dec 27, 2023 |
| GITSTAR       | GDC-1461                    | [398e4f42e4](https://linux-hardware.org/?probe=398e4f42e4) | Dec 26, 2023 |
| Dell          | Vostro 5470                 | [76b6b08744](https://linux-hardware.org/?probe=76b6b08744) | Dec 26, 2023 |
| MECHREVO      | S2 Air Series PF4NU1F       | [edb1d110e2](https://linux-hardware.org/?probe=edb1d110e2) | Dec 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f47caaa0e1](https://linux-hardware.org/?probe=f47caaa0e1) | Dec 25, 2023 |
| Lenovo        | ThinkPad W530 2436CT0       | [7f8be52856](https://linux-hardware.org/?probe=7f8be52856) | Dec 24, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [2394204218](https://linux-hardware.org/?probe=2394204218) | Dec 24, 2023 |
| GITSTAR       | GDC-1461                    | [5412cf0f39](https://linux-hardware.org/?probe=5412cf0f39) | Dec 23, 2023 |
| Timi          | TM1612                      | [cf4f859193](https://linux-hardware.org/?probe=cf4f859193) | Dec 23, 2023 |
| Lenovo        | ThinkPad Edge E431 62771... | [e6f38cb85e](https://linux-hardware.org/?probe=e6f38cb85e) | Dec 22, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [4e4e1e2329](https://linux-hardware.org/?probe=4e4e1e2329) | Dec 21, 2023 |
| Timi          | TM1612                      | [38a41877ef](https://linux-hardware.org/?probe=38a41877ef) | Dec 19, 2023 |
| Sony          | SVD1321L2EW                 | [b753425d70](https://linux-hardware.org/?probe=b753425d70) | Dec 17, 2023 |
| Apple         | MacBookPro16,1              | [f04605f94c](https://linux-hardware.org/?probe=f04605f94c) | Dec 17, 2023 |
| HUAWEI        | RLEFG-XX                    | [d47423dd6f](https://linux-hardware.org/?probe=d47423dd6f) | Dec 11, 2023 |
| MECHREVO      | Kuangshi16Pro Series GM6... | [e551d0d31e](https://linux-hardware.org/?probe=e551d0d31e) | Dec 11, 2023 |
| ASUSTek       | K55DR                       | [a869089d9a](https://linux-hardware.org/?probe=a869089d9a) | Dec 09, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [e9ddadffad](https://linux-hardware.org/?probe=e9ddadffad) | Dec 07, 2023 |
| HUAWEI        | CREM-WXX9                   | [cf753bfc89](https://linux-hardware.org/?probe=cf753bfc89) | Dec 05, 2023 |
| ASUSTek       | K55DR                       | [a13beb506c](https://linux-hardware.org/?probe=a13beb506c) | Dec 05, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | [0964d78171](https://linux-hardware.org/?probe=0964d78171) | Dec 04, 2023 |
| Timi          | RedmiBook 14-APCS           | [468a017a07](https://linux-hardware.org/?probe=468a017a07) | Dec 04, 2023 |
| Lenovo        | ThinkPad X220 4291OL3       | [d07f89fdd6](https://linux-hardware.org/?probe=d07f89fdd6) | Dec 02, 2023 |
| Dell          | Precision 7750              | [1edebf75b2](https://linux-hardware.org/?probe=1edebf75b2) | Nov 30, 2023 |
| Notebook      | P7xxTM                      | [d1a0cf0f45](https://linux-hardware.org/?probe=d1a0cf0f45) | Nov 28, 2023 |
| GITSTAR       | GDC-1461                    | [26a9582fb3](https://linux-hardware.org/?probe=26a9582fb3) | Nov 28, 2023 |
| Shanghai Z... | ZXE CRB                     | [db0496034a](https://linux-hardware.org/?probe=db0496034a) | Nov 28, 2023 |
| Valve         | Jupiter                     | [d2e56a6b92](https://linux-hardware.org/?probe=d2e56a6b92) | Nov 27, 2023 |
| Google        | Terra                       | [b21072bf0e](https://linux-hardware.org/?probe=b21072bf0e) | Nov 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [97e207d679](https://linux-hardware.org/?probe=97e207d679) | Nov 27, 2023 |
| Lenovo        | ThinkPad X200 7458PN6       | [e37f4ef1d4](https://linux-hardware.org/?probe=e37f4ef1d4) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [4ce52b15f5](https://linux-hardware.org/?probe=4ce52b15f5) | Nov 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | [c45c9df0f9](https://linux-hardware.org/?probe=c45c9df0f9) | Nov 24, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | [4065934176](https://linux-hardware.org/?probe=4065934176) | Nov 22, 2023 |
| Lenovo        | Legion R7000P ARH7 82RE     | [0ae39d9390](https://linux-hardware.org/?probe=0ae39d9390) | Nov 20, 2023 |
| MACHENIKE     | L16W                        | [7c881a79a6](https://linux-hardware.org/?probe=7c881a79a6) | Nov 19, 2023 |
| ASUSTek       | S300CA                      | [0d1a79b878](https://linux-hardware.org/?probe=0d1a79b878) | Nov 18, 2023 |
| Timi          | RedmiBook 14-APCS           | [8337bc9061](https://linux-hardware.org/?probe=8337bc9061) | Nov 17, 2023 |
| HONOR         | HYM-WXX                     | [8fd3066986](https://linux-hardware.org/?probe=8fd3066986) | Nov 16, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [6de33389c6](https://linux-hardware.org/?probe=6de33389c6) | Nov 16, 2023 |
| Lenovo        | XiaoXinPro 16 IRH8 83AQ     | [1eb15d0477](https://linux-hardware.org/?probe=1eb15d0477) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [5d3a796122](https://linux-hardware.org/?probe=5d3a796122) | Nov 14, 2023 |
| HP            | ZHAN 66 Pro G2 Notebook ... | [f93402c5f5](https://linux-hardware.org/?probe=f93402c5f5) | Nov 14, 2023 |
| Timi          | TM1612                      | [3f53f3ed81](https://linux-hardware.org/?probe=3f53f3ed81) | Nov 13, 2023 |
| Timi          | TM1612                      | [e8b2659a5f](https://linux-hardware.org/?probe=e8b2659a5f) | Nov 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [671a836d23](https://linux-hardware.org/?probe=671a836d23) | Nov 10, 2023 |
| ASUSTek       | TX300CA                     | [b6176e4138](https://linux-hardware.org/?probe=b6176e4138) | Nov 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [54b91fa265](https://linux-hardware.org/?probe=54b91fa265) | Nov 08, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [ec440eff42](https://linux-hardware.org/?probe=ec440eff42) | Nov 08, 2023 |
| GITSTAR       | GDC-1461                    | [4139b9476a](https://linux-hardware.org/?probe=4139b9476a) | Nov 07, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX95D... | [050ecd56d1](https://linux-hardware.org/?probe=050ecd56d1) | Nov 06, 2023 |
| MECHREVO      | Code 01 Series PF5NU1G      | [767c3ff7fa](https://linux-hardware.org/?probe=767c3ff7fa) | Nov 05, 2023 |
| Lenovo        | XiaoXinPro 14 IRH8 83AL     | [de5461c78b](https://linux-hardware.org/?probe=de5461c78b) | Nov 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [b0487db7bf](https://linux-hardware.org/?probe=b0487db7bf) | Nov 04, 2023 |
| Timi          | TM1612                      | [f4284a928a](https://linux-hardware.org/?probe=f4284a928a) | Nov 04, 2023 |
| ASUSTek       | X205TA                      | [b29e9ebfbe](https://linux-hardware.org/?probe=b29e9ebfbe) | Nov 03, 2023 |
| HP            | ZHAN 66 Pro A 14 G3         | [249f2a954a](https://linux-hardware.org/?probe=249f2a954a) | Nov 02, 2023 |
| Dell          | Vostro 5590                 | [300630cf8c](https://linux-hardware.org/?probe=300630cf8c) | Nov 01, 2023 |
| HUAWEI        | KLVL-WXXW                   | [672304cacd](https://linux-hardware.org/?probe=672304cacd) | Oct 29, 2023 |
| GITSTAR       | GDC-1461                    | [ece71c7e63](https://linux-hardware.org/?probe=ece71c7e63) | Oct 29, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [d6486c4e50](https://linux-hardware.org/?probe=d6486c4e50) | Oct 27, 2023 |
| Timi          | TM1612                      | [067b75cd11](https://linux-hardware.org/?probe=067b75cd11) | Oct 27, 2023 |
| HUAWEI        | NBM-WXX9                    | [9444fd16a7](https://linux-hardware.org/?probe=9444fd16a7) | Oct 26, 2023 |
| GITSTAR       | GDC-1461                    | [dbde4628a1](https://linux-hardware.org/?probe=dbde4628a1) | Oct 25, 2023 |
| Shanghai Z... | ZXE CRB                     | [35b07b6e34](https://linux-hardware.org/?probe=35b07b6e34) | Oct 25, 2023 |
| WUYING        | NS01-4BGXG                  | [5c999216df](https://linux-hardware.org/?probe=5c999216df) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming FX505GT          | [a5fde2a0ed](https://linux-hardware.org/?probe=a5fde2a0ed) | Oct 24, 2023 |
| Timi          | A34S                        | [56c5c23ce9](https://linux-hardware.org/?probe=56c5c23ce9) | Oct 23, 2023 |
| Lenovo        | Unknown                     | [8681ebe19c](https://linux-hardware.org/?probe=8681ebe19c) | Oct 22, 2023 |
| Lenovo        | ThinkBook 16p Gen 3 21EK    | [f96d0ccdef](https://linux-hardware.org/?probe=f96d0ccdef) | Oct 21, 2023 |
| Dell          | Precision 7680              | [70f6453d4c](https://linux-hardware.org/?probe=70f6453d4c) | Oct 18, 2023 |
| GITSTAR       | GDC-1461                    | [120e7ba365](https://linux-hardware.org/?probe=120e7ba365) | Oct 15, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a55a8998ea](https://linux-hardware.org/?probe=a55a8998ea) | Oct 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a9438a93a7](https://linux-hardware.org/?probe=a9438a93a7) | Oct 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [5584acb2f0](https://linux-hardware.org/?probe=5584acb2f0) | Oct 14, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | [14103b4b6a](https://linux-hardware.org/?probe=14103b4b6a) | Oct 14, 2023 |
| HASEE Comp... | CV15S                       | [3bb0d698b5](https://linux-hardware.org/?probe=3bb0d698b5) | Oct 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8be373f42f](https://linux-hardware.org/?probe=8be373f42f) | Oct 14, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [c221b8e1e6](https://linux-hardware.org/?probe=c221b8e1e6) | Oct 12, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [39e3632f1f](https://linux-hardware.org/?probe=39e3632f1f) | Oct 11, 2023 |
| Timi          | TM1612                      | [e8c807e4c6](https://linux-hardware.org/?probe=e8c807e4c6) | Oct 11, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [b1b0f03790](https://linux-hardware.org/?probe=b1b0f03790) | Oct 11, 2023 |
| Timi          | TM1612                      | [e853046494](https://linux-hardware.org/?probe=e853046494) | Oct 10, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [6e8b2311e4](https://linux-hardware.org/?probe=6e8b2311e4) | Oct 09, 2023 |
| Timi          | RedmiBook Air 13            | [63ea7be36f](https://linux-hardware.org/?probe=63ea7be36f) | Oct 07, 2023 |
| HONOR         | FRI-HXX                     | [fd2a01c055](https://linux-hardware.org/?probe=fd2a01c055) | Oct 06, 2023 |
| Dell          | Vostro 3350                 | [1034a53a9d](https://linux-hardware.org/?probe=1034a53a9d) | Sep 30, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2d31a3d858](https://linux-hardware.org/?probe=2d31a3d858) | Sep 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [49090587ce](https://linux-hardware.org/?probe=49090587ce) | Sep 28, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [124f7a0f29](https://linux-hardware.org/?probe=124f7a0f29) | Sep 26, 2023 |
| Dell          | Vostro 3350                 | [8bb6c19a73](https://linux-hardware.org/?probe=8bb6c19a73) | Sep 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [1af364233f](https://linux-hardware.org/?probe=1af364233f) | Sep 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3bb5a0e5a0](https://linux-hardware.org/?probe=3bb5a0e5a0) | Sep 22, 2023 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [454afdd117](https://linux-hardware.org/?probe=454afdd117) | Sep 21, 2023 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [a020038e27](https://linux-hardware.org/?probe=a020038e27) | Sep 21, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [94e8c710d5](https://linux-hardware.org/?probe=94e8c710d5) | Sep 20, 2023 |
| HP            | EliteBook 865 16 inch G9... | [5cab8957eb](https://linux-hardware.org/?probe=5cab8957eb) | Sep 18, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [290f6c66d1](https://linux-hardware.org/?probe=290f6c66d1) | Sep 17, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | [20d35c7482](https://linux-hardware.org/?probe=20d35c7482) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | [3306655fb2](https://linux-hardware.org/?probe=3306655fb2) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | [75a8af42cd](https://linux-hardware.org/?probe=75a8af42cd) | Sep 17, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [f74d2ae164](https://linux-hardware.org/?probe=f74d2ae164) | Sep 16, 2023 |
| Lenovo        | Legion R9000X2021R 82K8     | [de832cd47a](https://linux-hardware.org/?probe=de832cd47a) | Sep 16, 2023 |
| Lenovo        | ThinkPad T530 235927C       | [85c9a93599](https://linux-hardware.org/?probe=85c9a93599) | Sep 15, 2023 |
| Lenovo        | ThinkPad E470 20H1A0A3CD    | [f71a427eaf](https://linux-hardware.org/?probe=f71a427eaf) | Sep 13, 2023 |
| Lenovo        | ThinkPad E470 20H1A0A3CD    | [1f5e019771](https://linux-hardware.org/?probe=1f5e019771) | Sep 13, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | [53961bd222](https://linux-hardware.org/?probe=53961bd222) | Sep 12, 2023 |
| HP            | EliteBook 845 14 inch G1... | [b409947c26](https://linux-hardware.org/?probe=b409947c26) | Sep 11, 2023 |
| Timi          | Redmi G 2022                | [320bbb4e83](https://linux-hardware.org/?probe=320bbb4e83) | Sep 10, 2023 |
| Timi          | Redmi G 2022                | [534003f1ab](https://linux-hardware.org/?probe=534003f1ab) | Sep 10, 2023 |
| HP            | EliteBook 845 14 inch G1... | [f7f7964c03](https://linux-hardware.org/?probe=f7f7964c03) | Sep 09, 2023 |
| ASUSTek       | ROG Strix G733PY_G733PY     | [d5c5247f67](https://linux-hardware.org/?probe=d5c5247f67) | Sep 09, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [0d1c562190](https://linux-hardware.org/?probe=0d1c562190) | Sep 08, 2023 |
| Lenovo        | ZhaoYangN4620Z 20A0Z037K... | [1a6a64e046](https://linux-hardware.org/?probe=1a6a64e046) | Sep 08, 2023 |
| HP            | EliteBook 865 16 inch G9... | [872f12f24c](https://linux-hardware.org/?probe=872f12f24c) | Sep 08, 2023 |
| Acer          | Swift SF514-55T             | [35816546f8](https://linux-hardware.org/?probe=35816546f8) | Sep 08, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [9ebc45f613](https://linux-hardware.org/?probe=9ebc45f613) | Sep 07, 2023 |
| HP            | EliteBook 845 14 inch G1... | [6459a498c5](https://linux-hardware.org/?probe=6459a498c5) | Sep 07, 2023 |
| HP            | EliteBook 845 14 inch G1... | [c57f9232a2](https://linux-hardware.org/?probe=c57f9232a2) | Sep 05, 2023 |
| ASUSTek       | S400CA                      | [453335f199](https://linux-hardware.org/?probe=453335f199) | Sep 04, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [b3e23f1718](https://linux-hardware.org/?probe=b3e23f1718) | Sep 04, 2023 |
| HP            | EliteBook 845 14 inch G1... | [8b11ecfd36](https://linux-hardware.org/?probe=8b11ecfd36) | Sep 04, 2023 |
| Notebook      | NK50S5_SZ                   | [f0718be353](https://linux-hardware.org/?probe=f0718be353) | Sep 03, 2023 |
| Apple         | MacBookPro11,1              | [edca0e0264](https://linux-hardware.org/?probe=edca0e0264) | Sep 02, 2023 |
| Lenovo        | IdeaPad Z370                | [5c21431c9d](https://linux-hardware.org/?probe=5c21431c9d) | Sep 01, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [0eeb1276f0](https://linux-hardware.org/?probe=0eeb1276f0) | Aug 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dfb8d0f76b](https://linux-hardware.org/?probe=dfb8d0f76b) | Aug 28, 2023 |
| ASUSTek       | X542BP                      | [58cc535a58](https://linux-hardware.org/?probe=58cc535a58) | Aug 26, 2023 |
| HP            | EliteBook 845 14 inch G1... | [ac607e5597](https://linux-hardware.org/?probe=ac607e5597) | Aug 25, 2023 |
| MECHREVO      | Code01 Ver2.0               | [f5f6d366a1](https://linux-hardware.org/?probe=f5f6d366a1) | Aug 24, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [4b21c7c00f](https://linux-hardware.org/?probe=4b21c7c00f) | Aug 24, 2023 |
| Lenovo        | IdeaPad Z485 20151          | [599346f806](https://linux-hardware.org/?probe=599346f806) | Aug 23, 2023 |
| Dell          | Latitude E6400              | [d3bc465020](https://linux-hardware.org/?probe=d3bc465020) | Aug 23, 2023 |
| Google        | Nami                        | [db2c6bfb0a](https://linux-hardware.org/?probe=db2c6bfb0a) | Aug 23, 2023 |
| Dell          | Latitude E6400              | [a1b816015e](https://linux-hardware.org/?probe=a1b816015e) | Aug 23, 2023 |
| Google        | Nami                        | [69d8c7bfb8](https://linux-hardware.org/?probe=69d8c7bfb8) | Aug 22, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | [ae599c9d4b](https://linux-hardware.org/?probe=ae599c9d4b) | Aug 22, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | [b156da40ac](https://linux-hardware.org/?probe=b156da40ac) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | [8b4709e684](https://linux-hardware.org/?probe=8b4709e684) | Aug 20, 2023 |
| Dell          | XPS 15 9500                 | [006d138f62](https://linux-hardware.org/?probe=006d138f62) | Aug 19, 2023 |
| Timi          | RedmiBook Pro 15S           | [3223b9a4bb](https://linux-hardware.org/?probe=3223b9a4bb) | Aug 19, 2023 |
| HUAWEI        | FRD-WX9                     | [678a3a9328](https://linux-hardware.org/?probe=678a3a9328) | Aug 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [b8ceea98b8](https://linux-hardware.org/?probe=b8ceea98b8) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Dell          | Latitude 5420               | [4656cc9656](https://linux-hardware.org/?probe=4656cc9656) | Aug 17, 2023 |
| ASUSTek       | K54HR                       | [14ea4148dc](https://linux-hardware.org/?probe=14ea4148dc) | Aug 17, 2023 |
| HUAWEI        | WRT-WX9                     | [39a98650a3](https://linux-hardware.org/?probe=39a98650a3) | Aug 16, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [253750d7f8](https://linux-hardware.org/?probe=253750d7f8) | Aug 15, 2023 |
| MSI           | Z790 GAMING WIFI            | [95e340d91b](https://linux-hardware.org/?probe=95e340d91b) | Aug 14, 2023 |
| Acer          | Nitro AN515-58              | [871c589fb9](https://linux-hardware.org/?probe=871c589fb9) | Aug 13, 2023 |
| Dell          | Inspiron 5537               | [d978d063e8](https://linux-hardware.org/?probe=d978d063e8) | Aug 13, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [a6212b25ea](https://linux-hardware.org/?probe=a6212b25ea) | Aug 13, 2023 |
| Jumper        | EZpad                       | [5fa2e934c3](https://linux-hardware.org/?probe=5fa2e934c3) | Aug 11, 2023 |
| Unknown       | Unknown                     | [a064a2d5fd](https://linux-hardware.org/?probe=a064a2d5fd) | Aug 11, 2023 |
| HUAWEI        | KLVD-WXX9                   | [19cadaab1b](https://linux-hardware.org/?probe=19cadaab1b) | Aug 10, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [f4dd9cbbbd](https://linux-hardware.org/?probe=f4dd9cbbbd) | Aug 10, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [385c88301b](https://linux-hardware.org/?probe=385c88301b) | Aug 10, 2023 |
| Apple         | MacBookPro12,1              | [4a1def29d3](https://linux-hardware.org/?probe=4a1def29d3) | Aug 09, 2023 |
| Timi          | RedmiBook 14-APCS           | [d8939be040](https://linux-hardware.org/?probe=d8939be040) | Aug 06, 2023 |
| Timi          | RedmiBook 14-APCS           | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| Acer          | Swift SF314-512             | [ca109297da](https://linux-hardware.org/?probe=ca109297da) | Aug 05, 2023 |
| HP            | ZHAN 99 Mobile Workstati... | [b3422c4e37](https://linux-hardware.org/?probe=b3422c4e37) | Aug 04, 2023 |
| Shanghai Z... | ZXE CRB                     | [2d4fc6f4ce](https://linux-hardware.org/?probe=2d4fc6f4ce) | Aug 03, 2023 |
| HUAWEI        | KPR-WX9                     | [8918c544fe](https://linux-hardware.org/?probe=8918c544fe) | Aug 01, 2023 |
| MECHREVO      | WUJIE 14                    | [e6c48375f0](https://linux-hardware.org/?probe=e6c48375f0) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [216622d3d0](https://linux-hardware.org/?probe=216622d3d0) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [96f70f73b1](https://linux-hardware.org/?probe=96f70f73b1) | Jul 28, 2023 |
| MECHREVO      | WUJIE 14                    | [89b0f29570](https://linux-hardware.org/?probe=89b0f29570) | Jul 28, 2023 |
| Google        | Atlas                       | [c3f0326575](https://linux-hardware.org/?probe=c3f0326575) | Jul 28, 2023 |
| HUAWEI        | KPR-WX9                     | [2231e66b3d](https://linux-hardware.org/?probe=2231e66b3d) | Jul 26, 2023 |
| Dell          | Latitude E6400              | [a9333607eb](https://linux-hardware.org/?probe=a9333607eb) | Jul 26, 2023 |
| HONOR         | NBLK-WAX9X                  | [1081b2e480](https://linux-hardware.org/?probe=1081b2e480) | Jul 26, 2023 |
| HONOR         | NBLK-WAX9X                  | [9919413d6e](https://linux-hardware.org/?probe=9919413d6e) | Jul 25, 2023 |
| HUAWEI        | KPRC-WX0                    | [b8c39bfcff](https://linux-hardware.org/?probe=b8c39bfcff) | Jul 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d957d5efe0](https://linux-hardware.org/?probe=d957d5efe0) | Jul 22, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [45065697ac](https://linux-hardware.org/?probe=45065697ac) | Jul 22, 2023 |
| Lenovo        | B50-45 20388                | [54b4137669](https://linux-hardware.org/?probe=54b4137669) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [50e78d6df5](https://linux-hardware.org/?probe=50e78d6df5) | Jul 18, 2023 |
| Shenzhen P... | MOMO8W_P806                 | [fef8b63a34](https://linux-hardware.org/?probe=fef8b63a34) | Jul 17, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [899c1452e4](https://linux-hardware.org/?probe=899c1452e4) | Jul 16, 2023 |
| HP            | ZBook Power 15.6 inch G1... | [c2042a2e0e](https://linux-hardware.org/?probe=c2042a2e0e) | Jul 15, 2023 |
| Lenovo        | ThinkPad T61 6465CTO        | [fcf6ce5b9e](https://linux-hardware.org/?probe=fcf6ce5b9e) | Jul 13, 2023 |
| HUAWEI        | QingYun L420 KLVV-W5821     | [e3227788f6](https://linux-hardware.org/?probe=e3227788f6) | Jul 08, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [733b12f6a4](https://linux-hardware.org/?probe=733b12f6a4) | Jul 07, 2023 |
| Lenovo        | Legion R9000P2021 82JS      | [0376dd3cbd](https://linux-hardware.org/?probe=0376dd3cbd) | Jul 07, 2023 |
| MECHREVO      | Jiaolong Series MRID6       | [c9ee671981](https://linux-hardware.org/?probe=c9ee671981) | Jul 06, 2023 |
| Lenovo        | B590 20208                  | [4ce9143c78](https://linux-hardware.org/?probe=4ce9143c78) | Jul 05, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [d990795943](https://linux-hardware.org/?probe=d990795943) | Jul 05, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [0ba3c7bad7](https://linux-hardware.org/?probe=0ba3c7bad7) | Jul 05, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [6e2dff39cc](https://linux-hardware.org/?probe=6e2dff39cc) | Jul 05, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [fc1c7254b3](https://linux-hardware.org/?probe=fc1c7254b3) | Jul 04, 2023 |
| Acer          | Aspire E1-470G              | [db4125a1c5](https://linux-hardware.org/?probe=db4125a1c5) | Jul 04, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [7fee63007e](https://linux-hardware.org/?probe=7fee63007e) | Jul 02, 2023 |
| Lenovo        | ThinkBook 16 G5+ ARP 21J... | [211f5e5cf1](https://linux-hardware.org/?probe=211f5e5cf1) | Jul 02, 2023 |
| Dell          | G3 3590                     | [5c7312fed9](https://linux-hardware.org/?probe=5c7312fed9) | Jun 30, 2023 |
| HP            | ProBook 440 G3              | [98a588f9ff](https://linux-hardware.org/?probe=98a588f9ff) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [9814b54843](https://linux-hardware.org/?probe=9814b54843) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [5b82e1dd39](https://linux-hardware.org/?probe=5b82e1dd39) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [80b6536a46](https://linux-hardware.org/?probe=80b6536a46) | Jun 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | [6615a04065](https://linux-hardware.org/?probe=6615a04065) | Jun 28, 2023 |
| HP            | EliteBook 835 13 inch G1... | [e43818af40](https://linux-hardware.org/?probe=e43818af40) | Jun 26, 2023 |
| Valve         | Jupiter                     | [5115b6e139](https://linux-hardware.org/?probe=5115b6e139) | Jun 26, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [9dbf9f98a6](https://linux-hardware.org/?probe=9dbf9f98a6) | Jun 26, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | [ebfe7d469a](https://linux-hardware.org/?probe=ebfe7d469a) | Jun 24, 2023 |
| HONOR         | GLO-GXXX                    | [0e22fb1d65](https://linux-hardware.org/?probe=0e22fb1d65) | Jun 24, 2023 |
| Valve         | Jupiter                     | [a373e679ae](https://linux-hardware.org/?probe=a373e679ae) | Jun 23, 2023 |
| HASEE Comp... | NH5x_NH7x_HHx_HJx_HKx       | [2c0be5d314](https://linux-hardware.org/?probe=2c0be5d314) | Jun 19, 2023 |
| Timi          | A34R                        | [da4d787d75](https://linux-hardware.org/?probe=da4d787d75) | Jun 19, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [c454cb2cf0](https://linux-hardware.org/?probe=c454cb2cf0) | Jun 18, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [bfa70344e3](https://linux-hardware.org/?probe=bfa70344e3) | Jun 16, 2023 |
| HONOR         | NMH-WCX9                    | [ec1b8c4ef4](https://linux-hardware.org/?probe=ec1b8c4ef4) | Jun 16, 2023 |
| Timi          | TM1612                      | [7ec35d1268](https://linux-hardware.org/?probe=7ec35d1268) | Jun 16, 2023 |
| ASUSTek       | S400CA                      | [d512f1865e](https://linux-hardware.org/?probe=d512f1865e) | Jun 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [675f082570](https://linux-hardware.org/?probe=675f082570) | Jun 12, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [fc0318992c](https://linux-hardware.org/?probe=fc0318992c) | Jun 12, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [272de7ad6b](https://linux-hardware.org/?probe=272de7ad6b) | Jun 11, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [a165849009](https://linux-hardware.org/?probe=a165849009) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [05c07442a3](https://linux-hardware.org/?probe=05c07442a3) | Jun 09, 2023 |
| WOOKING       | X16                         | [aa543651fc](https://linux-hardware.org/?probe=aa543651fc) | Jun 08, 2023 |
| HONOR         | HYM-WXX                     | [964cd10c8e](https://linux-hardware.org/?probe=964cd10c8e) | Jun 05, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [f8f07099c7](https://linux-hardware.org/?probe=f8f07099c7) | Jun 05, 2023 |
| Lenovo        | Legion R70002021 82JW       | [f4e7c7034f](https://linux-hardware.org/?probe=f4e7c7034f) | Jun 05, 2023 |
| Toshiba       | WT8-A                       | [01e8918ef6](https://linux-hardware.org/?probe=01e8918ef6) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | [4dc30f1c10](https://linux-hardware.org/?probe=4dc30f1c10) | Jun 04, 2023 |
| GPD           | G1619-04                    | [fcc919c1c2](https://linux-hardware.org/?probe=fcc919c1c2) | Jun 03, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [ab7c62da47](https://linux-hardware.org/?probe=ab7c62da47) | Jun 02, 2023 |
| Dell          | Inspiron 5468               | [b16aeda09e](https://linux-hardware.org/?probe=b16aeda09e) | Jun 02, 2023 |
| IPASON        | P3                          | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [d21f59bea5](https://linux-hardware.org/?probe=d21f59bea5) | May 31, 2023 |
| Lenovo        | ZhaoYangN4620Z 20A0Z037K... | [7e07cca977](https://linux-hardware.org/?probe=7e07cca977) | May 31, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [202bf4f657](https://linux-hardware.org/?probe=202bf4f657) | May 29, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [bb60c42e07](https://linux-hardware.org/?probe=bb60c42e07) | May 29, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [f4de9c8a5f](https://linux-hardware.org/?probe=f4de9c8a5f) | May 26, 2023 |
| Lenovo        | ThinkPad X200 74574AC       | [e770387a34](https://linux-hardware.org/?probe=e770387a34) | May 25, 2023 |
| Acer          | Swift SF314-71              | [00979b3baa](https://linux-hardware.org/?probe=00979b3baa) | May 24, 2023 |
| Acer          | Swift SF314-71              | [84d9f5a2cc](https://linux-hardware.org/?probe=84d9f5a2cc) | May 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | [4c3c861f80](https://linux-hardware.org/?probe=4c3c861f80) | May 23, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [a2986e9b7a](https://linux-hardware.org/?probe=a2986e9b7a) | May 23, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | [c4040a0905](https://linux-hardware.org/?probe=c4040a0905) | May 23, 2023 |
| Timi          | RedmiBook 14-APCS           | [04d3c59d2c](https://linux-hardware.org/?probe=04d3c59d2c) | May 22, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [cf1d4ac757](https://linux-hardware.org/?probe=cf1d4ac757) | May 18, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [4d1cd4ec12](https://linux-hardware.org/?probe=4d1cd4ec12) | May 17, 2023 |
| Toshiba       | Satellite C805D             | [21ee852978](https://linux-hardware.org/?probe=21ee852978) | May 16, 2023 |
| ASUSTek       | K55DR                       | [e4f7010e78](https://linux-hardware.org/?probe=e4f7010e78) | May 13, 2023 |
| ASUSTek       | K55DR                       | [0d4d8571bf](https://linux-hardware.org/?probe=0d4d8571bf) | May 13, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [d615a9b90f](https://linux-hardware.org/?probe=d615a9b90f) | May 08, 2023 |
| Quanta        | TWH                         | [724b4d7343](https://linux-hardware.org/?probe=724b4d7343) | May 06, 2023 |
| Lenovo        | IdeaPad Y480 20131          | [d625664bee](https://linux-hardware.org/?probe=d625664bee) | May 06, 2023 |
| Shanghai Z... | ZXE CRB                     | [d63ef842c1](https://linux-hardware.org/?probe=d63ef842c1) | May 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5f4447aa45](https://linux-hardware.org/?probe=5f4447aa45) | May 05, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [1dacd7233b](https://linux-hardware.org/?probe=1dacd7233b) | May 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ab21408c4c](https://linux-hardware.org/?probe=ab21408c4c) | May 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | [528ba302c0](https://linux-hardware.org/?probe=528ba302c0) | May 02, 2023 |
| Quanta        | TWH                         | [e760482286](https://linux-hardware.org/?probe=e760482286) | May 02, 2023 |
| MECHREVO      | WUJIE16 Pro                 | [c19e8370e5](https://linux-hardware.org/?probe=c19e8370e5) | May 02, 2023 |
| Timi          | TM1612                      | [3c06f7495e](https://linux-hardware.org/?probe=3c06f7495e) | May 01, 2023 |
| Dell          | Vostro 5468                 | [93eb16d30d](https://linux-hardware.org/?probe=93eb16d30d) | Apr 30, 2023 |
| Lenovo        | Legion Y7000 81FW           | [b1e6130b77](https://linux-hardware.org/?probe=b1e6130b77) | Apr 28, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4fb9a937f3](https://linux-hardware.org/?probe=4fb9a937f3) | Apr 27, 2023 |
| Timi          | TM1612                      | [f3127f0186](https://linux-hardware.org/?probe=f3127f0186) | Apr 27, 2023 |
| Shanghai Z... | ZXE CRB                     | [298d51ae78](https://linux-hardware.org/?probe=298d51ae78) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [aa23589794](https://linux-hardware.org/?probe=aa23589794) | Apr 23, 2023 |
| Unknown       | BXTH265BC                   | [37293a672b](https://linux-hardware.org/?probe=37293a672b) | Apr 21, 2023 |
| Timi          | A34R                        | [310e4d7b63](https://linux-hardware.org/?probe=310e4d7b63) | Apr 20, 2023 |
| MECHREVO      | Code10-7CC6U                | [0964cd2b26](https://linux-hardware.org/?probe=0964cd2b26) | Apr 20, 2023 |
| MECHREVO      | Code10-7CC6U                | [5ddc83a95c](https://linux-hardware.org/?probe=5ddc83a95c) | Apr 20, 2023 |
| HONOR         | HYM-WXX                     | [49d7cdd068](https://linux-hardware.org/?probe=49d7cdd068) | Apr 18, 2023 |
| Timi          | TM1612                      | [7be723d412](https://linux-hardware.org/?probe=7be723d412) | Apr 16, 2023 |
| HP            | ZHAN 99 Mobile Workstati... | [3dcc7ab043](https://linux-hardware.org/?probe=3dcc7ab043) | Apr 12, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [6bec4cb4a8](https://linux-hardware.org/?probe=6bec4cb4a8) | Apr 12, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [8d4288ca33](https://linux-hardware.org/?probe=8d4288ca33) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3358152092](https://linux-hardware.org/?probe=3358152092) | Apr 06, 2023 |
| Timi          | RedmiBook Pro 15            | [4eb4d46bfc](https://linux-hardware.org/?probe=4eb4d46bfc) | Apr 05, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [a85a9274d5](https://linux-hardware.org/?probe=a85a9274d5) | Apr 03, 2023 |
| HASEE Comp... | CV15S                       | [6c31986832](https://linux-hardware.org/?probe=6c31986832) | Apr 03, 2023 |
| HASEE Comp... | CV15S                       | [47c3d8f7b6](https://linux-hardware.org/?probe=47c3d8f7b6) | Apr 03, 2023 |
| Intel         | H81U                        | [43d7179dc3](https://linux-hardware.org/?probe=43d7179dc3) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [da1e07f122](https://linux-hardware.org/?probe=da1e07f122) | Mar 30, 2023 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [eb153b5f5d](https://linux-hardware.org/?probe=eb153b5f5d) | Mar 29, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| Shanghai Z... | ZXE CRB                     | [aafbb2815f](https://linux-hardware.org/?probe=aafbb2815f) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [300fe5d1b2](https://linux-hardware.org/?probe=300fe5d1b2) | Mar 24, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [8291e7598a](https://linux-hardware.org/?probe=8291e7598a) | Mar 24, 2023 |
| Shanghai Z... | ZXE CRB                     | [7f98044a04](https://linux-hardware.org/?probe=7f98044a04) | Mar 24, 2023 |
| Timi          | TM1613                      | [3016a40df3](https://linux-hardware.org/?probe=3016a40df3) | Mar 23, 2023 |
| Timi          | TM1613                      | [ddbc83a8d3](https://linux-hardware.org/?probe=ddbc83a8d3) | Mar 23, 2023 |
| Lenovo        | ThinkPad X230s 20AHS0070... | [9d86eaf558](https://linux-hardware.org/?probe=9d86eaf558) | Mar 21, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [f980742ab8](https://linux-hardware.org/?probe=f980742ab8) | Mar 16, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [eac2f2ae40](https://linux-hardware.org/?probe=eac2f2ae40) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d9d4f5649a](https://linux-hardware.org/?probe=d9d4f5649a) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [70de894994](https://linux-hardware.org/?probe=70de894994) | Mar 13, 2023 |
| GPD           | G1621-02                    | [21394d0975](https://linux-hardware.org/?probe=21394d0975) | Mar 12, 2023 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [bcbf6544cd](https://linux-hardware.org/?probe=bcbf6544cd) | Mar 11, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [4ffe64e472](https://linux-hardware.org/?probe=4ffe64e472) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | [49130084c4](https://linux-hardware.org/?probe=49130084c4) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | [a6091bc2e2](https://linux-hardware.org/?probe=a6091bc2e2) | Mar 11, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CMA... | [f15426402c](https://linux-hardware.org/?probe=f15426402c) | Mar 09, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [30d91acf27](https://linux-hardware.org/?probe=30d91acf27) | Mar 07, 2023 |
| GPD           | P2 MAX                      | [d73c7b9146](https://linux-hardware.org/?probe=d73c7b9146) | Mar 07, 2023 |
| Lenovo        | Unknown                     | [2ae9263125](https://linux-hardware.org/?probe=2ae9263125) | Mar 06, 2023 |
| Shanghai Z... | ZXE CRB                     | [bb68a61939](https://linux-hardware.org/?probe=bb68a61939) | Mar 05, 2023 |
| Lenovo        | ThinkPad 11e 20D9S00C00     | [dbae54f9d4](https://linux-hardware.org/?probe=dbae54f9d4) | Mar 04, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | [ade006d016](https://linux-hardware.org/?probe=ade006d016) | Feb 24, 2023 |
| Lenovo        | KaiTian N70z G1d            | [cbc8e4e008](https://linux-hardware.org/?probe=cbc8e4e008) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [028814b990](https://linux-hardware.org/?probe=028814b990) | Feb 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cc10e54ab9](https://linux-hardware.org/?probe=cc10e54ab9) | Feb 20, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [c4ec00ef99](https://linux-hardware.org/?probe=c4ec00ef99) | Feb 17, 2023 |
| Acer          | Aspire 5540                 | [ce25cbe4f9](https://linux-hardware.org/?probe=ce25cbe4f9) | Feb 17, 2023 |
| Lenovo        | ThinkPad E460 20ETA00CCD    | [cb29661ee9](https://linux-hardware.org/?probe=cb29661ee9) | Feb 16, 2023 |
| Lenovo        | ThinkPad E460 20ETA00CCD    | [158769574f](https://linux-hardware.org/?probe=158769574f) | Feb 16, 2023 |
| HP            | 1000                        | [57de0f3103](https://linux-hardware.org/?probe=57de0f3103) | Feb 15, 2023 |
| Timi          | RedmiBook Pro 15S           | [991db4f096](https://linux-hardware.org/?probe=991db4f096) | Feb 14, 2023 |
| Timi          | RedmiBook Pro 15S           | [6a952f7024](https://linux-hardware.org/?probe=6a952f7024) | Feb 13, 2023 |
| Lenovo        | ThinkPad X220 4290CTO       | [1e9debee03](https://linux-hardware.org/?probe=1e9debee03) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | [e8ba753fae](https://linux-hardware.org/?probe=e8ba753fae) | Feb 13, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| Lenovo        | XiaoXinPro 14ACH 2021 82... | [29326a6340](https://linux-hardware.org/?probe=29326a6340) | Feb 11, 2023 |
| Unknown       | Unknown                     | [770938dc90](https://linux-hardware.org/?probe=770938dc90) | Feb 10, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [a127a79277](https://linux-hardware.org/?probe=a127a79277) | Feb 07, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [af8a076192](https://linux-hardware.org/?probe=af8a076192) | Feb 03, 2023 |
| Alienware     | x17 R2                      | [474a70c148](https://linux-hardware.org/?probe=474a70c148) | Feb 03, 2023 |
| Valve         | Jupiter                     | [13077754a1](https://linux-hardware.org/?probe=13077754a1) | Feb 02, 2023 |
| Timi          | A34R                        | [18ab422614](https://linux-hardware.org/?probe=18ab422614) | Jan 31, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [dd9e1146ff](https://linux-hardware.org/?probe=dd9e1146ff) | Jan 31, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | [a7ef98ea02](https://linux-hardware.org/?probe=a7ef98ea02) | Jan 30, 2023 |
| Apple         | MacBookPro16,1              | [06f297243d](https://linux-hardware.org/?probe=06f297243d) | Jan 28, 2023 |
| MECHREVO      | Code10-7CC6U                | [86e769b2a3](https://linux-hardware.org/?probe=86e769b2a3) | Jan 27, 2023 |
| Lenovo        | ThinkPad E495 20NEA00ACD    | [70dad952b2](https://linux-hardware.org/?probe=70dad952b2) | Jan 26, 2023 |
| Valve         | Jupiter                     | [68dcd57886](https://linux-hardware.org/?probe=68dcd57886) | Jan 19, 2023 |
| Valve         | Jupiter                     | [e9ac3c25b8](https://linux-hardware.org/?probe=e9ac3c25b8) | Jan 19, 2023 |
| Lenovo        | Legion R70002021 82JW       | [5e5628739f](https://linux-hardware.org/?probe=5e5628739f) | Jan 16, 2023 |
| Apple         | MacBookPro15,1              | [8382d0f8eb](https://linux-hardware.org/?probe=8382d0f8eb) | Jan 16, 2023 |
| Apple         | MacBookPro15,1              | [314c5ba951](https://linux-hardware.org/?probe=314c5ba951) | Jan 16, 2023 |
| Valve         | Jupiter                     | [53b2d510d6](https://linux-hardware.org/?probe=53b2d510d6) | Jan 14, 2023 |
| Acer          | Aspire 4750                 | [c05f45c326](https://linux-hardware.org/?probe=c05f45c326) | Jan 14, 2023 |
| Lenovo        | Unknown                     | [9bfcd0f555](https://linux-hardware.org/?probe=9bfcd0f555) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming FX505GM_FX86F... | [5ab0bf0018](https://linux-hardware.org/?probe=5ab0bf0018) | Jan 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [cef6a9db45](https://linux-hardware.org/?probe=cef6a9db45) | Jan 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [8defa5d641](https://linux-hardware.org/?probe=8defa5d641) | Jan 05, 2023 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [b54f312c7d](https://linux-hardware.org/?probe=b54f312c7d) | Jan 05, 2023 |
| Lenovo        | ThinkPad T430u 33519LC      | [87af3fa7f0](https://linux-hardware.org/?probe=87af3fa7f0) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480s 20L7A00HH... | [801c1bad94](https://linux-hardware.org/?probe=801c1bad94) | Jan 02, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | [a22f1e75b3](https://linux-hardware.org/?probe=a22f1e75b3) | Jan 01, 2023 |
| Lenovo        | ThinkPad Edge E545 20B2S... | [c83f51d7d9](https://linux-hardware.org/?probe=c83f51d7d9) | Dec 31, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3980... | [43783d2dda](https://linux-hardware.org/?probe=43783d2dda) | Dec 29, 2022 |
| Timi          | TM1612                      | [3e7f998f8d](https://linux-hardware.org/?probe=3e7f998f8d) | Dec 21, 2022 |
| Lenovo        | ThinkPad T460s 20F9A02PC... | [da548ee1cb](https://linux-hardware.org/?probe=da548ee1cb) | Dec 21, 2022 |
| Timi          | TM1612                      | [0400dd08c6](https://linux-hardware.org/?probe=0400dd08c6) | Dec 20, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [c4170b9ea3](https://linux-hardware.org/?probe=c4170b9ea3) | Dec 20, 2022 |
| Timi          | TM1612                      | [12efe96e3b](https://linux-hardware.org/?probe=12efe96e3b) | Dec 20, 2022 |
| Timi          | TM1612                      | [428430456f](https://linux-hardware.org/?probe=428430456f) | Dec 20, 2022 |
| ASUSTek       | X555LD                      | [d1d5c6a19e](https://linux-hardware.org/?probe=d1d5c6a19e) | Dec 19, 2022 |
| MECHREVO      | Code01 Ver2.0               | [e4ba0262b4](https://linux-hardware.org/?probe=e4ba0262b4) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | [1a9c49eb4f](https://linux-hardware.org/?probe=1a9c49eb4f) | Dec 16, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [559c3f32f8](https://linux-hardware.org/?probe=559c3f32f8) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [eb0d410f64](https://linux-hardware.org/?probe=eb0d410f64) | Dec 12, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [7541ce9ac6](https://linux-hardware.org/?probe=7541ce9ac6) | Dec 11, 2022 |
| HUAWEI        | BOHB-WAX9                   | [ebdb63b56f](https://linux-hardware.org/?probe=ebdb63b56f) | Dec 10, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [247beb66fb](https://linux-hardware.org/?probe=247beb66fb) | Dec 10, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2534d396c6](https://linux-hardware.org/?probe=2534d396c6) | Dec 10, 2022 |
| HUAWEI        | BOHB-WAX9                   | [573736f441](https://linux-hardware.org/?probe=573736f441) | Dec 10, 2022 |
| Lenovo        | ThinkPad Z61t 9441MY4       | [9ddc30d9b9](https://linux-hardware.org/?probe=9ddc30d9b9) | Dec 07, 2022 |
| Acer          | Swift SF314-512             | [b2aac5194c](https://linux-hardware.org/?probe=b2aac5194c) | Dec 06, 2022 |
| Unknown       | Unknown                     | [8032977c84](https://linux-hardware.org/?probe=8032977c84) | Dec 05, 2022 |
| Lenovo        | ThinkPad neo 14 21DN0009... | [80c8d84387](https://linux-hardware.org/?probe=80c8d84387) | Dec 05, 2022 |
| HP            | ZHAN 66 Pro 14 inch G5 N... | [b2b5c92aeb](https://linux-hardware.org/?probe=b2b5c92aeb) | Dec 04, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [9fec7bdfdc](https://linux-hardware.org/?probe=9fec7bdfdc) | Dec 04, 2022 |
| MECHREVO      | X3 Series GK7CP6R           | [7990b26bbf](https://linux-hardware.org/?probe=7990b26bbf) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f93dd5ad2d](https://linux-hardware.org/?probe=f93dd5ad2d) | Dec 03, 2022 |
| Shanghai Z... | ZXE CRB                     | [85e1d9b8bc](https://linux-hardware.org/?probe=85e1d9b8bc) | Dec 03, 2022 |
| Shanghai Z... | ZXE CRB                     | [2cef9980e6](https://linux-hardware.org/?probe=2cef9980e6) | Dec 03, 2022 |
| Valve         | Jupiter                     | [1fdf6ffce7](https://linux-hardware.org/?probe=1fdf6ffce7) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | [40111c09eb](https://linux-hardware.org/?probe=40111c09eb) | Dec 01, 2022 |
| Dell          | Vostro 3480                 | [bf353a87c5](https://linux-hardware.org/?probe=bf353a87c5) | Dec 01, 2022 |
| Intel         | H81U                        | [87a1cceaae](https://linux-hardware.org/?probe=87a1cceaae) | Nov 29, 2022 |
| Valve         | Jupiter                     | [f0d9943604](https://linux-hardware.org/?probe=f0d9943604) | Nov 28, 2022 |
| SmbiosType... | SmbiosType1_SystemProduc... | [fc54a7e10e](https://linux-hardware.org/?probe=fc54a7e10e) | Nov 27, 2022 |
| Lenovo        | ThinkPad Z61t 9441MY4       | [e24f9d12e5](https://linux-hardware.org/?probe=e24f9d12e5) | Nov 25, 2022 |
| Dell          | Inspiron 5488               | [32b350c3f6](https://linux-hardware.org/?probe=32b350c3f6) | Nov 25, 2022 |
| Shanghai Z... | ZXE CRB                     | [8a27b5d8b3](https://linux-hardware.org/?probe=8a27b5d8b3) | Nov 24, 2022 |
| Razer         | Blade 15 Advanced Model ... | [60732590be](https://linux-hardware.org/?probe=60732590be) | Nov 24, 2022 |
| Sony          | SVD1321L2EW                 | [2fcc5aa10a](https://linux-hardware.org/?probe=2fcc5aa10a) | Nov 23, 2022 |
| Lenovo        | G470 20078                  | [55f47f2c19](https://linux-hardware.org/?probe=55f47f2c19) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [1104a26017](https://linux-hardware.org/?probe=1104a26017) | Nov 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [346303c711](https://linux-hardware.org/?probe=346303c711) | Nov 14, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [2e29461f3b](https://linux-hardware.org/?probe=2e29461f3b) | Nov 13, 2022 |
| Lenovo        | XiaoXinPro 14ACH 2021 82... | [d74b37eebb](https://linux-hardware.org/?probe=d74b37eebb) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0A... | [016d7c275d](https://linux-hardware.org/?probe=016d7c275d) | Nov 13, 2022 |
| Timi          | Redmi G 2022                | [86f8128511](https://linux-hardware.org/?probe=86f8128511) | Nov 12, 2022 |
| GreatWall     | TN140A2                     | [4bc596cd45](https://linux-hardware.org/?probe=4bc596cd45) | Nov 10, 2022 |
| Acer          | Nitro AN515-58              | [9f4cb2a547](https://linux-hardware.org/?probe=9f4cb2a547) | Nov 09, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [e5abd4f928](https://linux-hardware.org/?probe=e5abd4f928) | Nov 06, 2022 |
| Acer          | Aspire V3-572G              | [77f939bab4](https://linux-hardware.org/?probe=77f939bab4) | Nov 05, 2022 |
| Clevo         | Modified by dsanke          | [b0c6c10d48](https://linux-hardware.org/?probe=b0c6c10d48) | Nov 05, 2022 |
| COLORFUL      | X15 XS 22                   | [38bc70c9b2](https://linux-hardware.org/?probe=38bc70c9b2) | Nov 04, 2022 |
| COLORFUL      | X15 XS 22                   | [342a90f101](https://linux-hardware.org/?probe=342a90f101) | Nov 04, 2022 |
| Lenovo        | Legion Y9000X IAH7 82TF     | [73ba8f75b7](https://linux-hardware.org/?probe=73ba8f75b7) | Nov 04, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [dda5d2dd10](https://linux-hardware.org/?probe=dda5d2dd10) | Nov 03, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [c0f68304d1](https://linux-hardware.org/?probe=c0f68304d1) | Nov 03, 2022 |
| GPD           | P3 MAX                      | [8b198da775](https://linux-hardware.org/?probe=8b198da775) | Nov 02, 2022 |
| GPD           | P3 MAX                      | [aea8f8bb50](https://linux-hardware.org/?probe=aea8f8bb50) | Nov 02, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [dbacfbd3b0](https://linux-hardware.org/?probe=dbacfbd3b0) | Nov 02, 2022 |
| Shanghai Z... | ZXE CRB                     | [a0029fb797](https://linux-hardware.org/?probe=a0029fb797) | Nov 02, 2022 |
| Notebook      | P65xHP                      | [68d40fd2c7](https://linux-hardware.org/?probe=68d40fd2c7) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [48c0ef6251](https://linux-hardware.org/?probe=48c0ef6251) | Nov 02, 2022 |
| Acer          | Swift SF314-512             | [4c80b212c6](https://linux-hardware.org/?probe=4c80b212c6) | Nov 01, 2022 |
| Acer          | Swift SF314-512             | [4e92800709](https://linux-hardware.org/?probe=4e92800709) | Nov 01, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [1cc623c804](https://linux-hardware.org/?probe=1cc623c804) | Nov 01, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [0dde1fbb38](https://linux-hardware.org/?probe=0dde1fbb38) | Oct 28, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [8cf64e81cd](https://linux-hardware.org/?probe=8cf64e81cd) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [806e4d754d](https://linux-hardware.org/?probe=806e4d754d) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [d6ccf0a2d8](https://linux-hardware.org/?probe=d6ccf0a2d8) | Oct 28, 2022 |
| THTF          | CR F860-T1                  | [9f0a52783f](https://linux-hardware.org/?probe=9f0a52783f) | Oct 27, 2022 |
| THTF          | CR F860-T1                  | [0e20f4f61a](https://linux-hardware.org/?probe=0e20f4f61a) | Oct 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [a66d2944a8](https://linux-hardware.org/?probe=a66d2944a8) | Oct 18, 2022 |
| Valve         | Jupiter                     | [0a198cb541](https://linux-hardware.org/?probe=0a198cb541) | Oct 18, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [f5eec71426](https://linux-hardware.org/?probe=f5eec71426) | Oct 18, 2022 |
| Shanghai Z... | ZXE CRB                     | [8ce5134a88](https://linux-hardware.org/?probe=8ce5134a88) | Oct 17, 2022 |
| MECHREVO      | Code01 Ver2.0               | [5fbae9cfcf](https://linux-hardware.org/?probe=5fbae9cfcf) | Oct 17, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [d49a7e728d](https://linux-hardware.org/?probe=d49a7e728d) | Oct 17, 2022 |
| Dell          | Vostro 3400                 | [156e3942e5](https://linux-hardware.org/?probe=156e3942e5) | Oct 16, 2022 |
| Dell          | Vostro 3400                 | [f9c2c298c4](https://linux-hardware.org/?probe=f9c2c298c4) | Oct 14, 2022 |
| Dell          | XPS 15 9570                 | [07b0072cfb](https://linux-hardware.org/?probe=07b0072cfb) | Oct 14, 2022 |
| Unknown       | Unknown                     | [2fa12ac832](https://linux-hardware.org/?probe=2fa12ac832) | Oct 13, 2022 |
| HP            | EliteBook 865 16 inch G9... | [b4a34edd03](https://linux-hardware.org/?probe=b4a34edd03) | Oct 11, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [04cb107be2](https://linux-hardware.org/?probe=04cb107be2) | Oct 11, 2022 |
| HUAWEI        | KLVC-WXX9                   | [bf283ab356](https://linux-hardware.org/?probe=bf283ab356) | Oct 11, 2022 |
| Intel Clie... | LAPBC710                    | [42b7bc6ee4](https://linux-hardware.org/?probe=42b7bc6ee4) | Oct 10, 2022 |
| Intel Clie... | LAPBC710                    | [bacb30816f](https://linux-hardware.org/?probe=bacb30816f) | Oct 07, 2022 |
| ASUSTek       | ProArt Studiobook H7600Z... | [5db7aac5d3](https://linux-hardware.org/?probe=5db7aac5d3) | Oct 07, 2022 |
| Timi          | RedmiBook Pro 15S           | [108ff1fbdd](https://linux-hardware.org/?probe=108ff1fbdd) | Oct 07, 2022 |
| HUAWEI        | L410 KLVU-WDU0              | [00edb23106](https://linux-hardware.org/?probe=00edb23106) | Oct 07, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | [8a49ad19f4](https://linux-hardware.org/?probe=8a49ad19f4) | Oct 06, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | [27d780177e](https://linux-hardware.org/?probe=27d780177e) | Oct 05, 2022 |
| Acer          | S50-54                      | [7680195105](https://linux-hardware.org/?probe=7680195105) | Oct 04, 2022 |
| GPD           | G1621-02                    | [1f88eb2bec](https://linux-hardware.org/?probe=1f88eb2bec) | Oct 03, 2022 |
| Acer          | S50-54                      | [a7ff4f9792](https://linux-hardware.org/?probe=a7ff4f9792) | Oct 02, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [703687bcd7](https://linux-hardware.org/?probe=703687bcd7) | Sep 30, 2022 |
| Lenovo        | Legion R70002021 82JW       | [b12e5d06a3](https://linux-hardware.org/?probe=b12e5d06a3) | Sep 28, 2022 |
| Timi          | TM1612                      | [ad37b74e1e](https://linux-hardware.org/?probe=ad37b74e1e) | Sep 27, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2A... | [ce132fc63e](https://linux-hardware.org/?probe=ce132fc63e) | Sep 27, 2022 |
| Timi          | TM1612                      | [a7c23ad10b](https://linux-hardware.org/?probe=a7c23ad10b) | Sep 26, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | [5cff3798b0](https://linux-hardware.org/?probe=5cff3798b0) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | [b32a413aa9](https://linux-hardware.org/?probe=b32a413aa9) | Sep 25, 2022 |
| MECHREVO      | Code01 Ver2.0               | [18246c5a9e](https://linux-hardware.org/?probe=18246c5a9e) | Sep 25, 2022 |
| NEC Comput... | PC-VK25LCZDM                | [97ab1f723e](https://linux-hardware.org/?probe=97ab1f723e) | Sep 23, 2022 |
| Mbenben       | Mai II                      | [2cfb10385b](https://linux-hardware.org/?probe=2cfb10385b) | Sep 22, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [c1edc96aa7](https://linux-hardware.org/?probe=c1edc96aa7) | Sep 21, 2022 |
| Timi          | TM1612                      | [3d9866e9ff](https://linux-hardware.org/?probe=3d9866e9ff) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | [b84e8d2682](https://linux-hardware.org/?probe=b84e8d2682) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | [4779dfc2b0](https://linux-hardware.org/?probe=4779dfc2b0) | Sep 20, 2022 |
| GreatWall     | Unknown                     | [12ee24a7c7](https://linux-hardware.org/?probe=12ee24a7c7) | Sep 20, 2022 |
| GreatWall     | TN140A2                     | [2c4ddb8e4b](https://linux-hardware.org/?probe=2c4ddb8e4b) | Sep 20, 2022 |
| Lenovo        | ThinkPad SL400 2743AQC      | [beb74c65cc](https://linux-hardware.org/?probe=beb74c65cc) | Sep 19, 2022 |
| Lenovo        | ThinkPad E480 20KNA040CD    | [8cd233ffbb](https://linux-hardware.org/?probe=8cd233ffbb) | Sep 19, 2022 |
| Unknown       | Unknown                     | [fab82ec455](https://linux-hardware.org/?probe=fab82ec455) | Sep 18, 2022 |
| Lenovo        | Legion Y9000X IAH7 82TF     | [3b63a75571](https://linux-hardware.org/?probe=3b63a75571) | Sep 16, 2022 |
| Dell          | XPS 13 9360                 | [750bf03293](https://linux-hardware.org/?probe=750bf03293) | Sep 14, 2022 |
| Timi          | TM1604                      | [80f52c9545](https://linux-hardware.org/?probe=80f52c9545) | Sep 14, 2022 |
| Timi          | Mi Laptop Air 12.5          | [d666daaeb2](https://linux-hardware.org/?probe=d666daaeb2) | Sep 13, 2022 |
| Samsung       | 800G5M/800G5W               | [ad3cd5381f](https://linux-hardware.org/?probe=ad3cd5381f) | Sep 13, 2022 |
| Shanghai Z... | ZXE CRB                     | [9f244f4236](https://linux-hardware.org/?probe=9f244f4236) | Sep 12, 2022 |
| MECHREVO      | Code01 Ver2.0               | [c55fd8d477](https://linux-hardware.org/?probe=c55fd8d477) | Sep 11, 2022 |
| HP            | EliteBook 830 G6            | [697d152bcc](https://linux-hardware.org/?probe=697d152bcc) | Sep 11, 2022 |
| Dell          | Precision 3571              | [d9939fbfd4](https://linux-hardware.org/?probe=d9939fbfd4) | Sep 05, 2022 |
| Timi          | TM1709                      | [2fb5436031](https://linux-hardware.org/?probe=2fb5436031) | Sep 04, 2022 |
| win elemen... | MoreFine S500+              | [d02a951b89](https://linux-hardware.org/?probe=d02a951b89) | Sep 04, 2022 |
| Lenovo        | ThinkPad E450 20DCA087CD    | [26928f83da](https://linux-hardware.org/?probe=26928f83da) | Sep 04, 2022 |
| MECHREVO      | Code01 Ver2.0               | [6456a1b04f](https://linux-hardware.org/?probe=6456a1b04f) | Sep 02, 2022 |
| win elemen... | MoreFine S500+              | [5a51c31ac9](https://linux-hardware.org/?probe=5a51c31ac9) | Aug 29, 2022 |
| BBEN          | G16                         | [6b0b170e1c](https://linux-hardware.org/?probe=6b0b170e1c) | Aug 28, 2022 |
| BBEN          | G16                         | [66fc9bd46b](https://linux-hardware.org/?probe=66fc9bd46b) | Aug 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2KU0... | [6500c142f5](https://linux-hardware.org/?probe=6500c142f5) | Aug 27, 2022 |
| Dell          | Precision 7720              | [7fafc0e50b](https://linux-hardware.org/?probe=7fafc0e50b) | Aug 26, 2022 |
| Apple         | MacBookPro16,2              | [3c6266b13d](https://linux-hardware.org/?probe=3c6266b13d) | Aug 23, 2022 |
| Acer          | Nitro AN515-45              | [c0372aaa91](https://linux-hardware.org/?probe=c0372aaa91) | Aug 22, 2022 |
| Acer          | Nitro AN515-45              | [be6beefb03](https://linux-hardware.org/?probe=be6beefb03) | Aug 22, 2022 |
| BBEN          | G16                         | [f9768aedb9](https://linux-hardware.org/?probe=f9768aedb9) | Aug 21, 2022 |
| BBEN          | G16                         | [d491f08ce0](https://linux-hardware.org/?probe=d491f08ce0) | Aug 21, 2022 |
| HP            | EliteBook 845 14 inch G9... | [ee6f495403](https://linux-hardware.org/?probe=ee6f495403) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | [289850f128](https://linux-hardware.org/?probe=289850f128) | Aug 13, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [b1498c810e](https://linux-hardware.org/?probe=b1498c810e) | Aug 12, 2022 |
| Timi          | TM1709                      | [26b592f734](https://linux-hardware.org/?probe=26b592f734) | Aug 11, 2022 |
| Shanghai Z... | ZXE CRB                     | [9ac3c0b157](https://linux-hardware.org/?probe=9ac3c0b157) | Aug 09, 2022 |
| Lenovo        | Legion R70002021 82JW       | [949598482f](https://linux-hardware.org/?probe=949598482f) | Aug 07, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [054c0beb4f](https://linux-hardware.org/?probe=054c0beb4f) | Aug 07, 2022 |
| Lenovo        | Legion R70002021 82JW       | [7a3c7a2886](https://linux-hardware.org/?probe=7a3c7a2886) | Aug 04, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [28eaeed6dd](https://linux-hardware.org/?probe=28eaeed6dd) | Aug 04, 2022 |
| Lenovo        | ThinkPad E470c 20H3A000C... | [047888752c](https://linux-hardware.org/?probe=047888752c) | Aug 04, 2022 |
| Google        | Dratini                     | [e61c92a95b](https://linux-hardware.org/?probe=e61c92a95b) | Aug 04, 2022 |
| Notebook      | NH5xAx                      | [7716e60398](https://linux-hardware.org/?probe=7716e60398) | Aug 03, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | [563bd9cecd](https://linux-hardware.org/?probe=563bd9cecd) | Aug 02, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | [88a326be83](https://linux-hardware.org/?probe=88a326be83) | Jul 28, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [2ed7d049e7](https://linux-hardware.org/?probe=2ed7d049e7) | Jul 27, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| Timi          | Mi Laptop Air 12.5          | [52764ae22f](https://linux-hardware.org/?probe=52764ae22f) | Jul 26, 2022 |
| Intel Clie... | LAPKC71F                    | [baf09f6525](https://linux-hardware.org/?probe=baf09f6525) | Jul 24, 2022 |
| HUAWEI        | CREM-WXX9                   | [5e4ca4abd6](https://linux-hardware.org/?probe=5e4ca4abd6) | Jul 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [3428364c49](https://linux-hardware.org/?probe=3428364c49) | Jul 22, 2022 |
| Dell          | Latitude E7440              | [d5ca3d7f7e](https://linux-hardware.org/?probe=d5ca3d7f7e) | Jul 22, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [1a0ea0050f](https://linux-hardware.org/?probe=1a0ea0050f) | Jul 22, 2022 |
| METAPHYUNI    | MetamechBook                | [169a9a0636](https://linux-hardware.org/?probe=169a9a0636) | Jul 21, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [d101f95ac2](https://linux-hardware.org/?probe=d101f95ac2) | Jul 20, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | [cafc6119f3](https://linux-hardware.org/?probe=cafc6119f3) | Jul 18, 2022 |
| Intel Clie... | LAPKC71F                    | [f2bfdb1f13](https://linux-hardware.org/?probe=f2bfdb1f13) | Jul 17, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [321c1a6e7a](https://linux-hardware.org/?probe=321c1a6e7a) | Jul 17, 2022 |
| Dell          | Vostro 5620                 | [92c267f273](https://linux-hardware.org/?probe=92c267f273) | Jul 15, 2022 |
| Dell          | Vostro 5620                 | [845432a1d3](https://linux-hardware.org/?probe=845432a1d3) | Jul 15, 2022 |
| Lenovo        | V470 HuronRiver Platform    | [021fb24a0a](https://linux-hardware.org/?probe=021fb24a0a) | Jul 14, 2022 |
| Lenovo        | V470 HuronRiver Platform    | [f3b112e72a](https://linux-hardware.org/?probe=f3b112e72a) | Jul 14, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | [4d636c74d3](https://linux-hardware.org/?probe=4d636c74d3) | Jul 14, 2022 |
| Intel Clie... | LAPKC71F                    | [3ae3afeece](https://linux-hardware.org/?probe=3ae3afeece) | Jul 13, 2022 |
| Fujitsu       | FMVNP7HER                   | [e87161bce7](https://linux-hardware.org/?probe=e87161bce7) | Jul 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [179ad71f6a](https://linux-hardware.org/?probe=179ad71f6a) | Jul 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [7cfc308ed6](https://linux-hardware.org/?probe=7cfc308ed6) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | [f67a64f833](https://linux-hardware.org/?probe=f67a64f833) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | [5bdfb575ae](https://linux-hardware.org/?probe=5bdfb575ae) | Jul 07, 2022 |
| Apple         | MacBookPro12,1              | [62fb099dfd](https://linux-hardware.org/?probe=62fb099dfd) | Jul 07, 2022 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [ad60f0abf2](https://linux-hardware.org/?probe=ad60f0abf2) | Jul 04, 2022 |
| Dell          | Vostro 3549                 | [d23ff685fc](https://linux-hardware.org/?probe=d23ff685fc) | Jul 03, 2022 |
| HP            | EliteBook 2560p             | [c1e5d91a40](https://linux-hardware.org/?probe=c1e5d91a40) | Jul 02, 2022 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [4b2106c800](https://linux-hardware.org/?probe=4b2106c800) | Jun 29, 2022 |
| Intel Clie... | LAPKC71F                    | [1a50f7c080](https://linux-hardware.org/?probe=1a50f7c080) | Jun 27, 2022 |
| Dell          | Precision 3541              | [816c91b81b](https://linux-hardware.org/?probe=816c91b81b) | Jun 25, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [eaf51fc79f](https://linux-hardware.org/?probe=eaf51fc79f) | Jun 24, 2022 |
| IPASON        | SMN86A                      | [834382148b](https://linux-hardware.org/?probe=834382148b) | Jun 21, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [8b520f803c](https://linux-hardware.org/?probe=8b520f803c) | Jun 21, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [385b65c320](https://linux-hardware.org/?probe=385b65c320) | Jun 19, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [fb120ddb6d](https://linux-hardware.org/?probe=fb120ddb6d) | Jun 19, 2022 |
| HUAWEI        | KPR-WX9                     | [4c08060155](https://linux-hardware.org/?probe=4c08060155) | Jun 18, 2022 |
| ASUSTek       | S550CM                      | [43ddcf21fb](https://linux-hardware.org/?probe=43ddcf21fb) | Jun 17, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [8d56f09226](https://linux-hardware.org/?probe=8d56f09226) | Jun 17, 2022 |
| HP            | EliteBook 2170p             | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| Clevo         | P7xxTM(1)                   | [48afb16c13](https://linux-hardware.org/?probe=48afb16c13) | Jun 16, 2022 |
| Timi          | TM1701                      | [e57d1ac956](https://linux-hardware.org/?probe=e57d1ac956) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [d77ce7a3f7](https://linux-hardware.org/?probe=d77ce7a3f7) | Jun 13, 2022 |
| Timi          | A7S                         | [a43809f0a8](https://linux-hardware.org/?probe=a43809f0a8) | Jun 12, 2022 |
| Acer          | Aspire T5000                | [38e164657d](https://linux-hardware.org/?probe=38e164657d) | Jun 11, 2022 |
| HP            | OMEN by Laptop              | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [6d46a6107c](https://linux-hardware.org/?probe=6d46a6107c) | Jun 06, 2022 |
| Acer          | Nitro AN515-57              | [ecef8fb98e](https://linux-hardware.org/?probe=ecef8fb98e) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [5f55de3d8e](https://linux-hardware.org/?probe=5f55de3d8e) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [db08be8e6c](https://linux-hardware.org/?probe=db08be8e6c) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [818930c012](https://linux-hardware.org/?probe=818930c012) | Jun 04, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [ee8d9751b0](https://linux-hardware.org/?probe=ee8d9751b0) | Jun 01, 2022 |
| HP            | ProBook 455 15.6 inch G9... | [d4698d909e](https://linux-hardware.org/?probe=d4698d909e) | May 31, 2022 |
| Acer          | Aspire T5000                | [7bdeb5fb3b](https://linux-hardware.org/?probe=7bdeb5fb3b) | May 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5e77f9d2f9](https://linux-hardware.org/?probe=5e77f9d2f9) | May 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [114a036605](https://linux-hardware.org/?probe=114a036605) | May 28, 2022 |
| Apple         | MacBookPro15,2              | [c0fe1740e0](https://linux-hardware.org/?probe=c0fe1740e0) | May 25, 2022 |
| Dell          | Latitude 5300               | [b2e8f91f15](https://linux-hardware.org/?probe=b2e8f91f15) | May 24, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [f2c3a907b7](https://linux-hardware.org/?probe=f2c3a907b7) | May 24, 2022 |
| Dell          | Latitude 3490               | [36a2ce11ef](https://linux-hardware.org/?probe=36a2ce11ef) | May 22, 2022 |
| Google        | Atlas                       | [d9406ed20d](https://linux-hardware.org/?probe=d9406ed20d) | May 21, 2022 |
| Apple         | MacBookPro16,1              | [a60048a58a](https://linux-hardware.org/?probe=a60048a58a) | May 19, 2022 |
| Lenovo        | IdeaPad U430p 20269         | [bcf848458f](https://linux-hardware.org/?probe=bcf848458f) | May 18, 2022 |
| Apple         | MacBookPro16,1              | [e5c6c46d14](https://linux-hardware.org/?probe=e5c6c46d14) | May 18, 2022 |
| MECHREVO      | X10Ti-S Series GM7MPHS      | [3af043f369](https://linux-hardware.org/?probe=3af043f369) | May 17, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [2b7a0725f0](https://linux-hardware.org/?probe=2b7a0725f0) | May 14, 2022 |
| Lenovo        | ThinkPad S2 5th Gen 20R7... | [a4ba7cbcfa](https://linux-hardware.org/?probe=a4ba7cbcfa) | May 13, 2022 |
| Google        | Atlas                       | [ae85df2f65](https://linux-hardware.org/?probe=ae85df2f65) | May 12, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [b0db2e2b60](https://linux-hardware.org/?probe=b0db2e2b60) | May 11, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [f62715aee5](https://linux-hardware.org/?probe=f62715aee5) | May 11, 2022 |
| Clevo         | P7xxTM(1)                   | [fdebb20557](https://linux-hardware.org/?probe=fdebb20557) | May 10, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | [428f653301](https://linux-hardware.org/?probe=428f653301) | May 05, 2022 |
| Timi          | Redmi G                     | [a2738a4d6e](https://linux-hardware.org/?probe=a2738a4d6e) | May 05, 2022 |
| Dell          | Latitude 7420               | [7fd2239abb](https://linux-hardware.org/?probe=7fd2239abb) | May 05, 2022 |
| Google        | Atlas                       | [dce87f3691](https://linux-hardware.org/?probe=dce87f3691) | May 05, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [6103e540b9](https://linux-hardware.org/?probe=6103e540b9) | May 04, 2022 |
| Dell          | Latitude 5300               | [fa0246b764](https://linux-hardware.org/?probe=fa0246b764) | May 04, 2022 |
| Dell          | Precision 3541              | [feaee0b7ff](https://linux-hardware.org/?probe=feaee0b7ff) | May 04, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [b812cd9eb1](https://linux-hardware.org/?probe=b812cd9eb1) | May 04, 2022 |
| Lenovo        | IdeaPad Y470 20090          | [690c12e995](https://linux-hardware.org/?probe=690c12e995) | May 03, 2022 |
| HP            | G42                         | [6ee2b19fc7](https://linux-hardware.org/?probe=6ee2b19fc7) | May 01, 2022 |
| HP            | G42                         | [731ba8d968](https://linux-hardware.org/?probe=731ba8d968) | May 01, 2022 |
| HP            | G42                         | [e23740df6e](https://linux-hardware.org/?probe=e23740df6e) | Apr 30, 2022 |
| HP            | G42                         | [f6ca4559f5](https://linux-hardware.org/?probe=f6ca4559f5) | Apr 30, 2022 |
| Dell          | Inspiron 7400               | [0c0af6919d](https://linux-hardware.org/?probe=0c0af6919d) | Apr 29, 2022 |
| Dell          | Inspiron 7400               | [8e5289a5e7](https://linux-hardware.org/?probe=8e5289a5e7) | Apr 28, 2022 |
| HUAWEI        | NBM-WXX9                    | [4f15ab06cc](https://linux-hardware.org/?probe=4f15ab06cc) | Apr 28, 2022 |
| Lenovo        | AILZx                       | [efa15d667f](https://linux-hardware.org/?probe=efa15d667f) | Apr 26, 2022 |
| Timi          | RedmiBook Pro 15S           | [07ccc93cd4](https://linux-hardware.org/?probe=07ccc93cd4) | Apr 25, 2022 |
| Timi          | TM1612                      | [9e6b6f4737](https://linux-hardware.org/?probe=9e6b6f4737) | Apr 24, 2022 |
| GreatWall     | TN140A2                     | [69043361cf](https://linux-hardware.org/?probe=69043361cf) | Apr 24, 2022 |
| Dell          | Latitude 5290               | [e373cb6fa1](https://linux-hardware.org/?probe=e373cb6fa1) | Apr 23, 2022 |
| Lenovo        | Legion Y7000 81FW           | [c56c469d4f](https://linux-hardware.org/?probe=c56c469d4f) | Apr 21, 2022 |
| Acer          | Swift SF314-512             | [d7e77fd856](https://linux-hardware.org/?probe=d7e77fd856) | Apr 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5f78518f42](https://linux-hardware.org/?probe=5f78518f42) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [3faf048414](https://linux-hardware.org/?probe=3faf048414) | Apr 18, 2022 |
| Shanghai Z... | ZXE CRB                     | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| Apple         | MacBookPro12,1              | [3c5f232016](https://linux-hardware.org/?probe=3c5f232016) | Apr 17, 2022 |
| Timi          | RedmiBook Pro 15S           | [e29970db9c](https://linux-hardware.org/?probe=e29970db9c) | Apr 16, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [7e346154a5](https://linux-hardware.org/?probe=7e346154a5) | Apr 16, 2022 |
| Timi          | A34                         | [ff24fc7e19](https://linux-hardware.org/?probe=ff24fc7e19) | Apr 15, 2022 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [2394088db1](https://linux-hardware.org/?probe=2394088db1) | Apr 14, 2022 |
| HONOR         | NBD-WXX9                    | [090560f0c5](https://linux-hardware.org/?probe=090560f0c5) | Apr 12, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [a86b688768](https://linux-hardware.org/?probe=a86b688768) | Apr 11, 2022 |
| Lenovo        | XiaoXin Air 13IML 81WV      | [c5ae7c810d](https://linux-hardware.org/?probe=c5ae7c810d) | Apr 09, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [e8e6eefea7](https://linux-hardware.org/?probe=e8e6eefea7) | Apr 09, 2022 |
| HP            | OMEN by Laptop 17-ck1xxx    | [10654de5c8](https://linux-hardware.org/?probe=10654de5c8) | Apr 08, 2022 |
| HP            | OMEN by Laptop 17-ck1xxx    | [60cd34cb85](https://linux-hardware.org/?probe=60cd34cb85) | Apr 07, 2022 |
| Lenovo        | ThinkPad S2 5th Gen 20R7... | [4e1cbba139](https://linux-hardware.org/?probe=4e1cbba139) | Apr 07, 2022 |
| Timi          | TM1701                      | [e2930f3884](https://linux-hardware.org/?probe=e2930f3884) | Apr 06, 2022 |
| IPASON        | MaxBook P1                  | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| Lenovo        | ThinkPad L470 20J5A240CD    | [2c7d1c1f02](https://linux-hardware.org/?probe=2c7d1c1f02) | Apr 04, 2022 |
| Timi          | RedmiBook Pro 15S           | [9c1fd6c304](https://linux-hardware.org/?probe=9c1fd6c304) | Apr 04, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [f1f8a33de1](https://linux-hardware.org/?probe=f1f8a33de1) | Apr 03, 2022 |
| Gigabyte      | P65                         | [28a10c32cf](https://linux-hardware.org/?probe=28a10c32cf) | Apr 02, 2022 |
| MECHREVO      | X10 Pro Series GM7TG8S      | [eceb9b69ed](https://linux-hardware.org/?probe=eceb9b69ed) | Apr 01, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [802940c8ef](https://linux-hardware.org/?probe=802940c8ef) | Mar 30, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [51f7153768](https://linux-hardware.org/?probe=51f7153768) | Mar 30, 2022 |
| Gigabyte      | AERO 15WV8                  | [8fdae867c0](https://linux-hardware.org/?probe=8fdae867c0) | Mar 30, 2022 |
| Unknown       | X133                        | [996dfaa50f](https://linux-hardware.org/?probe=996dfaa50f) | Mar 28, 2022 |
| Lenovo        | ThinkPad R400 2784A48       | [f760bbcc2f](https://linux-hardware.org/?probe=f760bbcc2f) | Mar 27, 2022 |
| Lenovo        | ThinkPad R400 2784A48       | [b7093f8912](https://linux-hardware.org/?probe=b7093f8912) | Mar 27, 2022 |
| Acer          | Swift SF314-510G            | [a105ea5158](https://linux-hardware.org/?probe=a105ea5158) | Mar 27, 2022 |
| Lenovo        | ThinkPad A485 20MU0007CD    | [1e231d6b08](https://linux-hardware.org/?probe=1e231d6b08) | Mar 26, 2022 |
| Timi          | A7S                         | [c39211692e](https://linux-hardware.org/?probe=c39211692e) | Mar 25, 2022 |
| Timi          | Mi Laptop Pro 15            | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4A... | [a257719dcf](https://linux-hardware.org/?probe=a257719dcf) | Mar 23, 2022 |
| HUAWEI        | FRD-WX9                     | [e027a60ac6](https://linux-hardware.org/?probe=e027a60ac6) | Mar 23, 2022 |
| IBM           | Unknown                     | [2bcbb8a946](https://linux-hardware.org/?probe=2bcbb8a946) | Mar 21, 2022 |
| Lenovo        | ThinkPad P53 20QQA004CD     | [c99fae499f](https://linux-hardware.org/?probe=c99fae499f) | Mar 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [ee813d0051](https://linux-hardware.org/?probe=ee813d0051) | Mar 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [6adea9d280](https://linux-hardware.org/?probe=6adea9d280) | Mar 19, 2022 |
| Timi          | RedmiBook Pro 15S           | [c06992ac2b](https://linux-hardware.org/?probe=c06992ac2b) | Mar 18, 2022 |
| Notebook      | NH5xAx                      | [cddad9e5c8](https://linux-hardware.org/?probe=cddad9e5c8) | Mar 17, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | [7e92a522e9](https://linux-hardware.org/?probe=7e92a522e9) | Mar 16, 2022 |
| Dell          | Vostro 3401                 | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| IPASON        | MaxBook P1                  | [70a5dc4f94](https://linux-hardware.org/?probe=70a5dc4f94) | Mar 12, 2022 |
| IPASON        | MaxBook P1                  | [8fdeae3b33](https://linux-hardware.org/?probe=8fdeae3b33) | Mar 12, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | [9c61029e1f](https://linux-hardware.org/?probe=9c61029e1f) | Mar 11, 2022 |
| Lenovo        | G580 20150                  | [1f84b1e42d](https://linux-hardware.org/?probe=1f84b1e42d) | Mar 11, 2022 |
| Samsung       | 500R5L/501R5L/500R5P/550... | [8d792e6db0](https://linux-hardware.org/?probe=8d792e6db0) | Mar 09, 2022 |
| Timi          | RedmiBook Air 13            | [cb1fd6a511](https://linux-hardware.org/?probe=cb1fd6a511) | Mar 08, 2022 |
| Toshiba       | Satellite C850-C008         | [d18b844729](https://linux-hardware.org/?probe=d18b844729) | Mar 07, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [e1da80ec6f](https://linux-hardware.org/?probe=e1da80ec6f) | Mar 05, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [c697a91a8e](https://linux-hardware.org/?probe=c697a91a8e) | Mar 02, 2022 |
| Dell          | Latitude 7285               | [8d3fe46d72](https://linux-hardware.org/?probe=8d3fe46d72) | Mar 01, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [f2fb3da876](https://linux-hardware.org/?probe=f2fb3da876) | Mar 01, 2022 |
| Shanghai Z... | ZXE CRB                     | [7fe4a3390b](https://linux-hardware.org/?probe=7fe4a3390b) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | TM1709                      | [16e699bea8](https://linux-hardware.org/?probe=16e699bea8) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| LG Electro... | 16Z90P-G.AA56C              | [f4b91cfb92](https://linux-hardware.org/?probe=f4b91cfb92) | Feb 22, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [5c3eba73d5](https://linux-hardware.org/?probe=5c3eba73d5) | Feb 20, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [215889b22b](https://linux-hardware.org/?probe=215889b22b) | Feb 19, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [b91f497b74](https://linux-hardware.org/?probe=b91f497b74) | Feb 19, 2022 |
| Lenovo        | XiaoXinPro 14IHU 2021 82... | [d994752dc6](https://linux-hardware.org/?probe=d994752dc6) | Feb 15, 2022 |
| MSI           | WT72 2OM                    | [e266645b4a](https://linux-hardware.org/?probe=e266645b4a) | Feb 14, 2022 |
| Dell          | System Inspiron N4110       | [695b7bb3dd](https://linux-hardware.org/?probe=695b7bb3dd) | Feb 14, 2022 |
| Unknown       | Unknown                     | [fa14786b94](https://linux-hardware.org/?probe=fa14786b94) | Feb 13, 2022 |
| Acer          | Swift SF314-510G            | [6c4dbc81d8](https://linux-hardware.org/?probe=6c4dbc81d8) | Feb 12, 2022 |
| Dell          | Inspiron 7472               | [62bdd11635](https://linux-hardware.org/?probe=62bdd11635) | Feb 11, 2022 |
| Dell          | G7 7500                     | [61f4625e4c](https://linux-hardware.org/?probe=61f4625e4c) | Feb 11, 2022 |
| Lenovo        | ThinkPad T61p 64608VU       | [73fddf3dcc](https://linux-hardware.org/?probe=73fddf3dcc) | Feb 10, 2022 |
| Lenovo        | ThinkPad X230 2324A14       | [502457cef5](https://linux-hardware.org/?probe=502457cef5) | Feb 09, 2022 |
| Lenovo        | ThinkPad X61 76733NJ        | [42dec79e1d](https://linux-hardware.org/?probe=42dec79e1d) | Feb 08, 2022 |
| MSI           | GS66 Stealth 10UH           | [a154ac8369](https://linux-hardware.org/?probe=a154ac8369) | Feb 08, 2022 |
| Lenovo        | Unknown                     | [8f315e1abe](https://linux-hardware.org/?probe=8f315e1abe) | Feb 07, 2022 |
| HUAWEI        | KLV-WX9                     | [80eec7db33](https://linux-hardware.org/?probe=80eec7db33) | Feb 07, 2022 |
| Lenovo        | Unknown                     | [bf281646d9](https://linux-hardware.org/?probe=bf281646d9) | Feb 07, 2022 |
| Dell          | Inspiron 3476               | [468adecdcc](https://linux-hardware.org/?probe=468adecdcc) | Feb 05, 2022 |
| Lenovo        | ThinkPad E450 20DCA07JCD    | [ce693a499b](https://linux-hardware.org/?probe=ce693a499b) | Feb 05, 2022 |
| Timi          | TM1612                      | [fe85c2d733](https://linux-hardware.org/?probe=fe85c2d733) | Feb 05, 2022 |
| Synology      | DS216+                      | [f4d851d128](https://linux-hardware.org/?probe=f4d851d128) | Feb 04, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | [5802ec7cbc](https://linux-hardware.org/?probe=5802ec7cbc) | Jan 30, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | [d2d9c64d63](https://linux-hardware.org/?probe=d2d9c64d63) | Jan 30, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | [fb18e68215](https://linux-hardware.org/?probe=fb18e68215) | Jan 22, 2022 |
| Timi          | A7S                         | [9c419e0bab](https://linux-hardware.org/?probe=9c419e0bab) | Jan 20, 2022 |
| Acer          | Aspire V5-471G              | [7c07d2e27d](https://linux-hardware.org/?probe=7c07d2e27d) | Jan 19, 2022 |
| Timi          | Mi Laptop Pro 15            | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [51d6b35ddf](https://linux-hardware.org/?probe=51d6b35ddf) | Jan 17, 2022 |
| Lenovo        | ThinkPad T470 20HDA022CD    | [3b3eeaa6b7](https://linux-hardware.org/?probe=3b3eeaa6b7) | Jan 14, 2022 |
| Synology      | DS216+                      | [8650ca59f1](https://linux-hardware.org/?probe=8650ca59f1) | Jan 10, 2022 |
| Dell          | Latitude E6400              | [ba6b82b98b](https://linux-hardware.org/?probe=ba6b82b98b) | Jan 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [45d678095f](https://linux-hardware.org/?probe=45d678095f) | Jan 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [666b0b18f5](https://linux-hardware.org/?probe=666b0b18f5) | Dec 30, 2021 |
| Lenovo        | V310-14ISK 80SX             | [ad94c90825](https://linux-hardware.org/?probe=ad94c90825) | Dec 29, 2021 |
| Samsung       | 500R5L/501R5L/500R5P/550... | [1f24ba261b](https://linux-hardware.org/?probe=1f24ba261b) | Dec 27, 2021 |
| Google        | Akemi                       | [295fd594af](https://linux-hardware.org/?probe=295fd594af) | Dec 27, 2021 |
| HP            | EliteBook 8470w             | [87c1cb1da7](https://linux-hardware.org/?probe=87c1cb1da7) | Dec 23, 2021 |
| Lenovo        | Legion Y7000 81FW           | [a7cc31a69f](https://linux-hardware.org/?probe=a7cc31a69f) | Dec 22, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [fabd656de1](https://linux-hardware.org/?probe=fabd656de1) | Dec 21, 2021 |
| Acer          | Aspire 4752                 | [e3c15cfedb](https://linux-hardware.org/?probe=e3c15cfedb) | Dec 14, 2021 |
| Acer          | Aspire 4752                 | [5559a99303](https://linux-hardware.org/?probe=5559a99303) | Dec 14, 2021 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [c029d9c42b](https://linux-hardware.org/?probe=c029d9c42b) | Dec 14, 2021 |
| HP            | ProBook 440 G6              | [bf19b30902](https://linux-hardware.org/?probe=bf19b30902) | Dec 13, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | [bd4021ec3d](https://linux-hardware.org/?probe=bd4021ec3d) | Dec 11, 2021 |
| Insyde        | CherryTrail                 | [1525831810](https://linux-hardware.org/?probe=1525831810) | Dec 11, 2021 |
| Lenovo        | Legion Y9000X 2020 81YY     | [acd0b9c831](https://linux-hardware.org/?probe=acd0b9c831) | Dec 11, 2021 |
| HASEE Comp... | E400                        | [32bee165ba](https://linux-hardware.org/?probe=32bee165ba) | Dec 11, 2021 |
| HP            | ProBook 440 G6              | [8c952bfc3d](https://linux-hardware.org/?probe=8c952bfc3d) | Dec 11, 2021 |
| Fujitsu       | FMVNQ8P9                    | [fe3a7ec790](https://linux-hardware.org/?probe=fe3a7ec790) | Dec 10, 2021 |
| Fujitsu       | FMVNQ8P9                    | [c6f3827cb1](https://linux-hardware.org/?probe=c6f3827cb1) | Dec 09, 2021 |
| Fujitsu       | FMVNQ8P9                    | [04ca55ea2b](https://linux-hardware.org/?probe=04ca55ea2b) | Dec 09, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | [801df46937](https://linux-hardware.org/?probe=801df46937) | Dec 07, 2021 |
| Lenovo        | B41-80 80LG                 | [96e84134f0](https://linux-hardware.org/?probe=96e84134f0) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [63dade9d7b](https://linux-hardware.org/?probe=63dade9d7b) | Dec 01, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [8e84498214](https://linux-hardware.org/?probe=8e84498214) | Nov 30, 2021 |
| Lenovo        | Unknown                     | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| Timi          | A7S                         | [625bafd45f](https://linux-hardware.org/?probe=625bafd45f) | Nov 27, 2021 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [109d14527f](https://linux-hardware.org/?probe=109d14527f) | Nov 27, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [27a4935e65](https://linux-hardware.org/?probe=27a4935e65) | Nov 26, 2021 |
| Jemper        | EZPAD WS_reserve            | [de173db361](https://linux-hardware.org/?probe=de173db361) | Nov 25, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | [7734a8d28c](https://linux-hardware.org/?probe=7734a8d28c) | Nov 18, 2021 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [69c06885de](https://linux-hardware.org/?probe=69c06885de) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [6da7601574](https://linux-hardware.org/?probe=6da7601574) | Nov 18, 2021 |
| Lenovo        | ThinkPad T430 2347G61       | [12ee1cee2b](https://linux-hardware.org/?probe=12ee1cee2b) | Nov 16, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [8c23aaf339](https://linux-hardware.org/?probe=8c23aaf339) | Nov 15, 2021 |
| MSI           | Delta 15 A5EFK              | [bc348014b5](https://linux-hardware.org/?probe=bc348014b5) | Nov 13, 2021 |
| Lenovo        | Legion R7000P2021H 82JU     | [19ffbfb846](https://linux-hardware.org/?probe=19ffbfb846) | Nov 13, 2021 |
| Dell          | Inspiron 7447               | [4ca16063da](https://linux-hardware.org/?probe=4ca16063da) | Nov 12, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [00e34bc46e](https://linux-hardware.org/?probe=00e34bc46e) | Nov 11, 2021 |
| Jumper        | EZbook                      | [f1391c1f4b](https://linux-hardware.org/?probe=f1391c1f4b) | Nov 10, 2021 |
| Dell          | Inspiron 7472               | [2508fadf63](https://linux-hardware.org/?probe=2508fadf63) | Nov 10, 2021 |
| Dell          | XPS 15 9570                 | [67670eea60](https://linux-hardware.org/?probe=67670eea60) | Nov 07, 2021 |
| Dell          | G15 5515                    | [1e5e0ab274](https://linux-hardware.org/?probe=1e5e0ab274) | Nov 06, 2021 |
| Google        | Akemi                       | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [17339fe912](https://linux-hardware.org/?probe=17339fe912) | Nov 03, 2021 |
| Notebook      | NH5xAx                      | [7aa37239c1](https://linux-hardware.org/?probe=7aa37239c1) | Nov 03, 2021 |
| Dell          | XPS 13 9343                 | [0d89b6423c](https://linux-hardware.org/?probe=0d89b6423c) | Oct 31, 2021 |
| Timi          | A34R                        | [f5385d6b10](https://linux-hardware.org/?probe=f5385d6b10) | Oct 31, 2021 |
| Acer          | Aspire 4752                 | [8a74691ba9](https://linux-hardware.org/?probe=8a74691ba9) | Oct 30, 2021 |
| Dell          | G3 3500                     | [a2d09beb8d](https://linux-hardware.org/?probe=a2d09beb8d) | Oct 25, 2021 |
| Toshiba       | dynabook Satellite T772/... | [070723f36c](https://linux-hardware.org/?probe=070723f36c) | Oct 24, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [2815629b34](https://linux-hardware.org/?probe=2815629b34) | Oct 21, 2021 |
| HUAWEI        | HLYL-WXX9                   | [9f2d69e4c4](https://linux-hardware.org/?probe=9f2d69e4c4) | Oct 20, 2021 |
| Dell          | G3 3500                     | [ec734562a6](https://linux-hardware.org/?probe=ec734562a6) | Oct 19, 2021 |
| Timi          | A34                         | [e2fbec93e6](https://linux-hardware.org/?probe=e2fbec93e6) | Oct 17, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20T2A... | [0c261084db](https://linux-hardware.org/?probe=0c261084db) | Oct 16, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [00196d9727](https://linux-hardware.org/?probe=00196d9727) | Oct 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [4aa5287a00](https://linux-hardware.org/?probe=4aa5287a00) | Oct 15, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [050314f62a](https://linux-hardware.org/?probe=050314f62a) | Oct 13, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [d2b877508b](https://linux-hardware.org/?probe=d2b877508b) | Oct 13, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [d3fdfb0745](https://linux-hardware.org/?probe=d3fdfb0745) | Oct 13, 2021 |
| Acer          | Swift SF314-42              | [bce3e39f4c](https://linux-hardware.org/?probe=bce3e39f4c) | Oct 10, 2021 |
| Acer          | Swift SF314-42              | [1c4fbe0fa4](https://linux-hardware.org/?probe=1c4fbe0fa4) | Oct 10, 2021 |
| HP            | 520                         | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| HP            | ZHAN 66 Pro G1              | [a1a1c41c6a](https://linux-hardware.org/?probe=a1a1c41c6a) | Oct 09, 2021 |
| Notebook      | NH5xAx                      | [d63fd746be](https://linux-hardware.org/?probe=d63fd746be) | Oct 09, 2021 |
| HP            | ZHAN 66 Pro G1              | [fcc291e2f1](https://linux-hardware.org/?probe=fcc291e2f1) | Oct 08, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [cbb2ea622b](https://linux-hardware.org/?probe=cbb2ea622b) | Oct 07, 2021 |
| HP            | ZHAN 66 Pro 15 G3           | [0f58e969f6](https://linux-hardware.org/?probe=0f58e969f6) | Oct 03, 2021 |
| Timi          | Mi Laptop Pro 15            | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| Timi          | TM1613                      | [f6bb688e77](https://linux-hardware.org/?probe=f6bb688e77) | Sep 29, 2021 |
| Lenovo        | Legion Y7000 2020 82AV      | [64d71e1177](https://linux-hardware.org/?probe=64d71e1177) | Sep 29, 2021 |
| Timi          | Mi Laptop Pro 15            | [de13c8f3fa](https://linux-hardware.org/?probe=de13c8f3fa) | Sep 29, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [1b471b415d](https://linux-hardware.org/?probe=1b471b415d) | Sep 29, 2021 |
| Lenovo        | G510 20238                  | [5f5ae3035b](https://linux-hardware.org/?probe=5f5ae3035b) | Sep 29, 2021 |
| Lenovo        | XiaoXinAir 14ALC 2021 82... | [df352fba0f](https://linux-hardware.org/?probe=df352fba0f) | Sep 27, 2021 |
| Acer          | Nitro AN515-52              | [bb17541aae](https://linux-hardware.org/?probe=bb17541aae) | Sep 26, 2021 |
| Terrans Fo... | AMD                         | [db4b9e36ab](https://linux-hardware.org/?probe=db4b9e36ab) | Sep 26, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [01362b36bf](https://linux-hardware.org/?probe=01362b36bf) | Sep 24, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | [be9156bd20](https://linux-hardware.org/?probe=be9156bd20) | Sep 24, 2021 |
| Lenovo        | XiaoXin-15IWL 2019 81QS     | [f726b13948](https://linux-hardware.org/?probe=f726b13948) | Sep 22, 2021 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | [0a99b9ac87](https://linux-hardware.org/?probe=0a99b9ac87) | Sep 22, 2021 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | [ea86578390](https://linux-hardware.org/?probe=ea86578390) | Sep 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QTA0... | [9a59e3a4f1](https://linux-hardware.org/?probe=9a59e3a4f1) | Sep 20, 2021 |
| Lenovo        | ThinkPad P53 20QQA004CD     | [50b6533131](https://linux-hardware.org/?probe=50b6533131) | Sep 20, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | [18cbc8a35f](https://linux-hardware.org/?probe=18cbc8a35f) | Sep 18, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | [5debd35710](https://linux-hardware.org/?probe=5debd35710) | Sep 18, 2021 |
| GXNOVA Com... | GX2                         | [ab148b2b4e](https://linux-hardware.org/?probe=ab148b2b4e) | Sep 14, 2021 |
| Notebook      | P65xHP                      | [12a7ec2b86](https://linux-hardware.org/?probe=12a7ec2b86) | Sep 14, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAA... | [ebcb7d7982](https://linux-hardware.org/?probe=ebcb7d7982) | Sep 14, 2021 |
| HP            | 431                         | [c2510d05b4](https://linux-hardware.org/?probe=c2510d05b4) | Sep 12, 2021 |
| HP            | 431                         | [d19b47e4d8](https://linux-hardware.org/?probe=d19b47e4d8) | Sep 12, 2021 |
| Sony          | SVT11215CGW                 | [0e12747ab1](https://linux-hardware.org/?probe=0e12747ab1) | Sep 12, 2021 |
| HP            | EliteBook 840 G5            | [35ee0ea8e4](https://linux-hardware.org/?probe=35ee0ea8e4) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2a4adea555](https://linux-hardware.org/?probe=2a4adea555) | Sep 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [025d2a8ddb](https://linux-hardware.org/?probe=025d2a8ddb) | Sep 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [9bbf3f2d82](https://linux-hardware.org/?probe=9bbf3f2d82) | Sep 05, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [3758bf5026](https://linux-hardware.org/?probe=3758bf5026) | Sep 01, 2021 |
| Timi          | TM1613                      | [f25eeca060](https://linux-hardware.org/?probe=f25eeca060) | Sep 01, 2021 |
| Dell          | Latitude E6530              | [5996acf813](https://linux-hardware.org/?probe=5996acf813) | Aug 31, 2021 |
| GPD           | G1618-03                    | [d680dd4360](https://linux-hardware.org/?probe=d680dd4360) | Aug 31, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| HUAWEI        | KPL-W0X                     | [27b23ba02b](https://linux-hardware.org/?probe=27b23ba02b) | Aug 29, 2021 |
| HP            | EliteBook 840 G3            | [8625d6f2f1](https://linux-hardware.org/?probe=8625d6f2f1) | Aug 28, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| Lenovo        | ThinkPad X220 429044C       | [20057996af](https://linux-hardware.org/?probe=20057996af) | Aug 27, 2021 |
| Dell          | XPS 13 9305                 | [08b5160307](https://linux-hardware.org/?probe=08b5160307) | Aug 27, 2021 |
| Lenovo        | K4450 20229                 | [70e7af9fae](https://linux-hardware.org/?probe=70e7af9fae) | Aug 26, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [4563619600](https://linux-hardware.org/?probe=4563619600) | Aug 25, 2021 |
| Lenovo        | K4450 20229                 | [e1c019df72](https://linux-hardware.org/?probe=e1c019df72) | Aug 24, 2021 |
| Lenovo        | ThinkPad E455 20DEA027CD    | [8edb3642cb](https://linux-hardware.org/?probe=8edb3642cb) | Aug 22, 2021 |
| Timi          | TM1612                      | [485caf5846](https://linux-hardware.org/?probe=485caf5846) | Aug 20, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [321cf3c58f](https://linux-hardware.org/?probe=321cf3c58f) | Aug 18, 2021 |
| Acer          | Nitro AN515-57              | [3c18d3a700](https://linux-hardware.org/?probe=3c18d3a700) | Aug 17, 2021 |
| Alienware     | m17                         | [5fdd4a64a3](https://linux-hardware.org/?probe=5fdd4a64a3) | Aug 17, 2021 |
| Lenovo        | Legion R9000K2021H 82N6     | [048b8332cc](https://linux-hardware.org/?probe=048b8332cc) | Aug 13, 2021 |
| Lenovo        | ThinkPad L430 2466EY7       | [b93128f327](https://linux-hardware.org/?probe=b93128f327) | Aug 12, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5e1cc5b229](https://linux-hardware.org/?probe=5e1cc5b229) | Aug 11, 2021 |
| MSI           | GP66 Leopard 11UG           | [98a65d0b3b](https://linux-hardware.org/?probe=98a65d0b3b) | Aug 10, 2021 |
| ASUSTek       | FX503VD                     | [7c2b153867](https://linux-hardware.org/?probe=7c2b153867) | Aug 08, 2021 |
| Fujitsu       | LIFEBOOK V1020              | [8eff816347](https://linux-hardware.org/?probe=8eff816347) | Aug 08, 2021 |
| Dell          | Latitude 5290 2-in-1        | [293b45eded](https://linux-hardware.org/?probe=293b45eded) | Aug 07, 2021 |
| GPD           | G1618-03                    | [25a0b540aa](https://linux-hardware.org/?probe=25a0b540aa) | Aug 07, 2021 |
| Dell          | Inspiron 11-3168            | [67552d79ac](https://linux-hardware.org/?probe=67552d79ac) | Aug 05, 2021 |
| Lenovo        | ZHAOYANG K3-ITL 82E3        | [ee2be4cea9](https://linux-hardware.org/?probe=ee2be4cea9) | Aug 03, 2021 |
| Apple         | MacBookPro16,1              | [124425a1ed](https://linux-hardware.org/?probe=124425a1ed) | Jul 28, 2021 |
| MSI           | GT62VR 7RE                  | [5f02658195](https://linux-hardware.org/?probe=5f02658195) | Jul 27, 2021 |
| Dell          | Latitude 7390 2-in-1        | [e411a84d3c](https://linux-hardware.org/?probe=e411a84d3c) | Jul 26, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | [1722982c29](https://linux-hardware.org/?probe=1722982c29) | Jul 26, 2021 |
| Apple         | MacBookPro11,1              | [e4d71ee9a8](https://linux-hardware.org/?probe=e4d71ee9a8) | Jul 24, 2021 |
| Intel         | Corbett Park CRB Revisio... | [17f1a1e73e](https://linux-hardware.org/?probe=17f1a1e73e) | Jul 21, 2021 |
| Lenovo        | Legion R70002020 82B6       | [d620ec97eb](https://linux-hardware.org/?probe=d620ec97eb) | Jul 21, 2021 |
| Lenovo        | G50-70m 20423               | [0b1a40c724](https://linux-hardware.org/?probe=0b1a40c724) | Jul 21, 2021 |
| Lenovo        | ThinkPad X230 23257Y1       | [f282cf1244](https://linux-hardware.org/?probe=f282cf1244) | Jul 18, 2021 |
| Toshiba       | NB300                       | [03b62f85cb](https://linux-hardware.org/?probe=03b62f85cb) | Jul 15, 2021 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [dd73dac900](https://linux-hardware.org/?probe=dd73dac900) | Jul 15, 2021 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | [d563d62b5f](https://linux-hardware.org/?probe=d563d62b5f) | Jul 14, 2021 |
| Dell          | XPS 13 9305                 | [60c8b3011a](https://linux-hardware.org/?probe=60c8b3011a) | Jul 12, 2021 |
| HASEE Comp... | Computer                    | [641cab4c92](https://linux-hardware.org/?probe=641cab4c92) | Jul 11, 2021 |
| Clevo         | P7xxTM(1)                   | [98eeef735f](https://linux-hardware.org/?probe=98eeef735f) | Jul 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [9d18d07e36](https://linux-hardware.org/?probe=9d18d07e36) | Jul 06, 2021 |
| HUAWEI        | HLYL-WXX9                   | [26b5b9e3d3](https://linux-hardware.org/?probe=26b5b9e3d3) | Jul 06, 2021 |
| ASUSTek       | VivoBook S14 X411UF         | [f5a3e8f307](https://linux-hardware.org/?probe=f5a3e8f307) | Jul 06, 2021 |
| Acer          | Swift SF314-42              | [d90c6cbf04](https://linux-hardware.org/?probe=d90c6cbf04) | Jul 04, 2021 |
| Lenovo        | ZHAOYANG CF4620Z-A123 59... | [6f716961de](https://linux-hardware.org/?probe=6f716961de) | Jun 29, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [279dea011e](https://linux-hardware.org/?probe=279dea011e) | Jun 28, 2021 |
| Terrans Fo... | X511                        | [7c131d9b3c](https://linux-hardware.org/?probe=7c131d9b3c) | Jun 27, 2021 |
| HUAWEI        | HN-WX9X                     | [c9180096a8](https://linux-hardware.org/?probe=c9180096a8) | Jun 26, 2021 |
| Toshiba       | Satellite C600              | [2be9935e22](https://linux-hardware.org/?probe=2be9935e22) | Jun 25, 2021 |
| Dell          | G7 7500                     | [fc4a38d0b1](https://linux-hardware.org/?probe=fc4a38d0b1) | Jun 23, 2021 |
| Apple         | MacBookAir5,2               | [6c83856ca5](https://linux-hardware.org/?probe=6c83856ca5) | Jun 22, 2021 |
| Toshiba       | Satellite C850-C008         | [91fc03f063](https://linux-hardware.org/?probe=91fc03f063) | Jun 21, 2021 |
| Timi          | TM1612                      | [c4fb55cbfd](https://linux-hardware.org/?probe=c4fb55cbfd) | Jun 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [f1200f8ad1](https://linux-hardware.org/?probe=f1200f8ad1) | Jun 20, 2021 |
| Timi          | TM1612                      | [dcb999a722](https://linux-hardware.org/?probe=dcb999a722) | Jun 20, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [4373344c26](https://linux-hardware.org/?probe=4373344c26) | Jun 20, 2021 |
| HUAWEI        | KLVL-WXX9                   | [43ef80b625](https://linux-hardware.org/?probe=43ef80b625) | Jun 19, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [439593d28e](https://linux-hardware.org/?probe=439593d28e) | Jun 19, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [45b203fa1d](https://linux-hardware.org/?probe=45b203fa1d) | Jun 19, 2021 |
| MSI           | GS66 Stealth 10SFS          | [7535868db2](https://linux-hardware.org/?probe=7535868db2) | Jun 18, 2021 |
| Dell          | Inspiron 3576               | [c9a19ce57f](https://linux-hardware.org/?probe=c9a19ce57f) | Jun 18, 2021 |
| MSI           | GS66 Stealth 10SFS          | [c095a4437c](https://linux-hardware.org/?probe=c095a4437c) | Jun 17, 2021 |
| Hampoo        | Cherry Trail CR V300        | [344ff5676f](https://linux-hardware.org/?probe=344ff5676f) | Jun 16, 2021 |
| Lenovo        | Legion Y9000K 2019 SE 81... | [374ace3f30](https://linux-hardware.org/?probe=374ace3f30) | Jun 15, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [54128eb7cf](https://linux-hardware.org/?probe=54128eb7cf) | Jun 13, 2021 |
| HP            | Pavilion 15                 | [9e0e3015c3](https://linux-hardware.org/?probe=9e0e3015c3) | Jun 13, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [c178189191](https://linux-hardware.org/?probe=c178189191) | Jun 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [8834a1f44c](https://linux-hardware.org/?probe=8834a1f44c) | Jun 11, 2021 |
| Acer          | Swift SF314-42              | [41d143b254](https://linux-hardware.org/?probe=41d143b254) | Jun 09, 2021 |
| Dell          | XPS 13 9370                 | [c8937f439d](https://linux-hardware.org/?probe=c8937f439d) | Jun 09, 2021 |
| HUAWEI        | HLY-WX9XX                   | [72f511586b](https://linux-hardware.org/?probe=72f511586b) | Jun 09, 2021 |
| HASEE Comp... | CW67S                       | [3012373a54](https://linux-hardware.org/?probe=3012373a54) | Jun 08, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [efb0b681f0](https://linux-hardware.org/?probe=efb0b681f0) | Jun 05, 2021 |
| Timi          | TM1612                      | [40318f2d95](https://linux-hardware.org/?probe=40318f2d95) | Jun 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [173f1c74f4](https://linux-hardware.org/?probe=173f1c74f4) | Jun 04, 2021 |
| Lenovo        | ThinkPad X230 23257Y1       | [d507dfaef3](https://linux-hardware.org/?probe=d507dfaef3) | Jun 02, 2021 |
| HP            | ProBook 430 G3              | [7a11677611](https://linux-hardware.org/?probe=7a11677611) | Jun 01, 2021 |
| Lenovo        | ZHAOYANG K29 20186          | [f02d15e805](https://linux-hardware.org/?probe=f02d15e805) | May 31, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [b6047b1557](https://linux-hardware.org/?probe=b6047b1557) | May 31, 2021 |
| Toshiba       | Satellite U800W             | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| HUAWEI        | KPR-WX9                     | [9c73a8d7d6](https://linux-hardware.org/?probe=9c73a8d7d6) | May 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [83d261308f](https://linux-hardware.org/?probe=83d261308f) | May 26, 2021 |
| Dell          | Latitude E6440              | [c4842eda94](https://linux-hardware.org/?probe=c4842eda94) | May 24, 2021 |
| Acer          | Swift SF314-42              | [5dca660f7e](https://linux-hardware.org/?probe=5dca660f7e) | May 22, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | [c9e7ae41ba](https://linux-hardware.org/?probe=c9e7ae41ba) | May 21, 2021 |
| Lenovo        | ThinkPad X220 4290BB8       | [e147d7b57e](https://linux-hardware.org/?probe=e147d7b57e) | May 21, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [72904aba23](https://linux-hardware.org/?probe=72904aba23) | May 20, 2021 |
| HUAWEI        | MACH-WX9                    | [6331748487](https://linux-hardware.org/?probe=6331748487) | May 20, 2021 |
| ASUSTek       | UX302LA                     | [c04c98c26f](https://linux-hardware.org/?probe=c04c98c26f) | May 19, 2021 |
| HP            | Laptop 14s-fr0xxx           | [ee4105df76](https://linux-hardware.org/?probe=ee4105df76) | May 18, 2021 |
| MSI           | GS60 6QE                    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/China/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 105       | 10.21%  |
| Ubuntu 22.04                 | 91        | 8.85%   |
| Ubuntu 18.04                 | 74        | 7.2%    |
| Arch Rolling                 | 67        | 6.52%   |
| Debian 11                    | 36        | 3.5%    |
| Arch                         | 29        | 2.82%   |
| Debian 12                    | 24        | 2.33%   |
| Kylin V10                    | 23        | 2.24%   |
| Manjaro                      | 20        | 1.95%   |
| openSUSE Tumbleweed-XXXXXXXX | 18        | 1.75%   |
| Gentoo 2.8                   | 15        | 1.46%   |
| OpenMandriva 4.2             | 14        | 1.36%   |
| OpenMandriva 4.3             | 13        | 1.26%   |
| ArcoLinux Rolling            | 13        | 1.26%   |
| UOS 20                       | 12        | 1.17%   |
| Debian 10                    | 12        | 1.17%   |
| KDE neon 20.04               | 11        | 1.07%   |
| Gentoo 2.7                   | 10        | 0.97%   |
| Fedora 38                    | 10        | 0.97%   |
| Ubuntu 23.04                 | 9         | 0.88%   |
| Ubuntu 21.10                 | 9         | 0.88%   |
| Ubuntu 19.04                 | 9         | 0.88%   |
| Linux Mint 20.1              | 9         | 0.88%   |
| Fedora 39                    | 9         | 0.88%   |
| Fedora 33                    | 9         | 0.88%   |
| Xero Rolling                 | 8         | 0.78%   |
| Ubuntu 22.10                 | 8         | 0.78%   |
| Debian Testing               | 8         | 0.78%   |
| Ubuntu 23.10                 | 7         | 0.68%   |
| Linux Mint 20                | 7         | 0.68%   |
| Gentoo 2.6                   | 7         | 0.68%   |
| Fedora 35                    | 7         | 0.68%   |
| Ubuntu 19.10                 | 6         | 0.58%   |
| ROSA R10                     | 6         | 0.58%   |
| Linux Mint 20.3              | 6         | 0.58%   |
| Kubuntu 22.04                | 6         | 0.58%   |
| Fedora 37                    | 6         | 0.58%   |
| Deepin 23                    | 6         | 0.58%   |
| Ubuntu 24.04                 | 5         | 0.49%   |
| Ubuntu 21.04                 | 5         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 324       | 32.83%  |
| Arch         | 95        | 9.63%   |
| Debian       | 82        | 8.31%   |
| Manjaro      | 62        | 6.28%   |
| Fedora       | 58        | 5.88%   |
| OpenMandriva | 40        | 4.05%   |
| Gentoo       | 39        | 3.95%   |
| Linux Mint   | 32        | 3.24%   |
| Deepin       | 27        | 2.74%   |
| Kylin        | 25        | 2.53%   |
| openSUSE     | 22        | 2.23%   |
| Kubuntu      | 18        | 1.82%   |
| SteamOS      | 13        | 1.32%   |
| Pop!_OS      | 13        | 1.32%   |
| ArcoLinux    | 13        | 1.32%   |
| KDE neon     | 12        | 1.22%   |
| Kali         | 12        | 1.22%   |
| CentOS       | 11        | 1.11%   |
| Atz          | 11        | 1.11%   |
| Xero         | 8         | 0.81%   |
| ROSA         | 8         | 0.81%   |
| Xubuntu      | 6         | 0.61%   |
| Elementary   | 5         | 0.51%   |
| Zorin        | 4         | 0.41%   |
| Ubuntu Unity | 4         | 0.41%   |
| Ubuntu MATE  | 3         | 0.3%    |
| NixOS        | 3         | 0.3%    |
| LMDE         | 3         | 0.3%    |
| Guix         | 3         | 0.3%    |
| Clear Linux  | 3         | 0.3%    |
| BlackPanther | 3         | 0.3%    |
| Trisquel     | 2         | 0.2%    |
| Solus        | 2         | 0.2%    |
| MX           | 2         | 0.2%    |
| Lubuntu      | 2         | 0.2%    |
| Garuda Linux | 2         | 0.2%    |
| EndeavourOS  | 2         | 0.2%    |
| Ubuntu Kylin | 1         | 0.1%    |
| Slackware    | 1         | 0.1%    |
| Rocky Linux  | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 13        | 1.17%   |
| 5.16.7-desktop-1omv4003  | 12        | 1.08%   |
| 6.2.0-26-generic         | 11        | 0.99%   |
| 6.1.0-13-amd64           | 11        | 0.99%   |
| 5.4.0-42-generic         | 11        | 0.99%   |
| 5.10.0-8-amd64           | 9         | 0.81%   |
| 6.2.0-32-generic         | 7         | 0.63%   |
| 5.19.0-46-generic        | 6         | 0.54%   |
| 5.19.0-41-generic        | 6         | 0.54%   |
| 5.19.0-35-generic        | 6         | 0.54%   |
| 5.13.0-30-generic        | 6         | 0.54%   |
| 4.18.0-25-generic        | 6         | 0.54%   |
| 6.2.0-39-generic         | 5         | 0.45%   |
| 6.1.0-9-amd64            | 5         | 0.45%   |
| 5.19.0-26-generic        | 5         | 0.45%   |
| 5.19.0-23-generic        | 5         | 0.45%   |
| 5.15.0-53-generic        | 5         | 0.45%   |
| 5.15.0-46-generic        | 5         | 0.45%   |
| 5.15.0-43-generic        | 5         | 0.45%   |
| 5.13.0-valve36-1-neptune | 5         | 0.45%   |
| 5.13.0-35-generic        | 5         | 0.45%   |
| 6.5.0-25-generic         | 4         | 0.36%   |
| 6.5.0-14-generic         | 4         | 0.36%   |
| 6.4.11-desktop-1omv2390  | 4         | 0.36%   |
| 6.1.32-amd64-desktop-hwe | 4         | 0.36%   |
| 6.1.0-18-amd64           | 4         | 0.36%   |
| 5.8.0-55-generic         | 4         | 0.36%   |
| 5.4.0-53-generic         | 4         | 0.36%   |
| 5.4.0-48-generic         | 4         | 0.36%   |
| 5.4.0-33-generic         | 4         | 0.36%   |
| 5.4.0-29-generic         | 4         | 0.36%   |
| 5.4.0-107-generic        | 4         | 0.36%   |
| 5.3.0-46-generic         | 4         | 0.36%   |
| 5.15.0-67-generic        | 4         | 0.36%   |
| 5.15.0-41-generic        | 4         | 0.36%   |
| 5.15.0-25-generic        | 4         | 0.36%   |
| 5.15.0-2-amd64           | 4         | 0.36%   |
| 5.13.0-40-generic        | 4         | 0.36%   |
| 5.13.0-28-generic        | 4         | 0.36%   |
| 5.11.0-36-generic        | 4         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 87        | 8.18%   |
| 5.15.0  | 68        | 6.39%   |
| 5.10.0  | 55        | 5.17%   |
| 5.13.0  | 40        | 3.76%   |
| 5.19.0  | 36        | 3.38%   |
| 6.2.0   | 35        | 3.29%   |
| 5.11.0  | 33        | 3.1%    |
| 6.1.0   | 32        | 3.01%   |
| 6.5.0   | 27        | 2.54%   |
| 5.8.0   | 27        | 2.54%   |
| 4.15.0  | 27        | 2.54%   |
| 4.18.0  | 25        | 2.35%   |
| 5.3.0   | 23        | 2.16%   |
| 5.0.0   | 17        | 1.6%    |
| 4.19.0  | 14        | 1.32%   |
| 5.16.7  | 13        | 1.22%   |
| 5.10.14 | 13        | 1.22%   |
| 6.4.11  | 8         | 0.75%   |
| 5.14.0  | 7         | 0.66%   |
| 6.6.9   | 6         | 0.56%   |
| 6.8.0   | 5         | 0.47%   |
| 6.5.3   | 5         | 0.47%   |
| 6.0.0   | 5         | 0.47%   |
| 5.6.14  | 5         | 0.47%   |
| 5.4.18  | 5         | 0.47%   |
| 6.3.5   | 4         | 0.38%   |
| 6.3.3   | 4         | 0.38%   |
| 6.2.9   | 4         | 0.38%   |
| 6.2.6   | 4         | 0.38%   |
| 6.1.52  | 4         | 0.38%   |
| 6.1.32  | 4         | 0.38%   |
| 6.0.7   | 4         | 0.38%   |
| 6.0.6   | 4         | 0.38%   |
| 5.9.16  | 4         | 0.38%   |
| 5.6.0   | 4         | 0.38%   |
| 5.18.12 | 4         | 0.38%   |
| 5.17.5  | 4         | 0.38%   |
| 5.16.0  | 4         | 0.38%   |
| 5.10.41 | 4         | 0.38%   |
| 5.10.27 | 4         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 111       | 10.53%  |
| 5.15    | 110       | 10.44%  |
| 5.10    | 96        | 9.11%   |
| 6.1     | 62        | 5.88%   |
| 6.2     | 51        | 4.84%   |
| 6.5     | 47        | 4.46%   |
| 5.13    | 46        | 4.36%   |
| 5.11    | 46        | 4.36%   |
| 5.19    | 45        | 4.27%   |
| 5.8     | 40        | 3.8%    |
| 5.3     | 30        | 2.85%   |
| 6.6     | 29        | 2.75%   |
| 4.18    | 27        | 2.56%   |
| 4.15    | 27        | 2.56%   |
| 6.4     | 24        | 2.28%   |
| 6.0     | 24        | 2.28%   |
| 5.16    | 24        | 2.28%   |
| 5.18    | 23        | 2.18%   |
| 5.14    | 21        | 1.99%   |
| 5.0     | 19        | 1.8%    |
| 4.19    | 19        | 1.8%    |
| 6.3     | 18        | 1.71%   |
| 5.17    | 16        | 1.52%   |
| 6.7     | 15        | 1.42%   |
| 5.6     | 13        | 1.23%   |
| 5.9     | 11        | 1.04%   |
| 6.8     | 10        | 0.95%   |
| 5.12    | 10        | 0.95%   |
| 5.7     | 8         | 0.76%   |
| 5.5     | 6         | 0.57%   |
| 4.9     | 6         | 0.57%   |
| 3.10    | 5         | 0.47%   |
| 5.1     | 3         | 0.28%   |
| 4.14    | 2         | 0.19%   |
| 5.2     | 1         | 0.09%   |
| 4.6     | 1         | 0.09%   |
| 4.20    | 1         | 0.09%   |
| 4.17    | 1         | 0.09%   |
| 4.13    | 1         | 0.09%   |
| 4.12    | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 939       | 97.91%  |
| i686    | 9         | 0.94%   |
| aarch64 | 9         | 0.94%   |
| armv7l  | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 440       | 44.31%  |
| KDE5            | 205       | 20.64%  |
| Unknown         | 103       | 10.37%  |
| XFCE            | 66        | 6.65%   |
| X-Cinnamon      | 33        | 3.32%   |
| KDE             | 27        | 2.72%   |
| Deepin          | 23        | 2.32%   |
| i3              | 17        | 1.71%   |
| MATE            | 15        | 1.51%   |
| UKUI            | 7         | 0.7%    |
| Pantheon        | 5         | 0.5%    |
| LXDE            | 5         | 0.5%    |
| Hyprland        | 5         | 0.5%    |
| Cinnamon        | 5         | 0.5%    |
| Budgie          | 5         | 0.5%    |
| KDE6            | 4         | 0.4%    |
| KDE4            | 4         | 0.4%    |
| GNOME Flashback | 4         | 0.4%    |
| DDE             | 4         | 0.4%    |
| Unity           | 3         | 0.3%    |
| LXQt            | 3         | 0.3%    |
| GNUstep         | 2         | 0.2%    |
| GNOME Classic   | 2         | 0.2%    |
| xmonad          | 1         | 0.1%    |
| sway            | 1         | 0.1%    |
| qtile           | 1         | 0.1%    |
| DWM             | 1         | 0.1%    |
| chadwm          | 1         | 0.1%    |
| bspwm           | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 672       | 68.29%  |
| Wayland | 224       | 22.76%  |
| Unknown | 56        | 5.69%   |
| Tty     | 32        | 3.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 337       | 34.25%  |
| GDM3    | 176       | 17.89%  |
| SDDM    | 175       | 17.78%  |
| GDM     | 140       | 14.23%  |
| LightDM | 114       | 11.59%  |
| TDM     | 35        | 3.56%   |
| XDM     | 2         | 0.2%    |
| KDM     | 2         | 0.2%    |
| SLiM    | 1         | 0.1%    |
| LY-DM   | 1         | 0.1%    |
| LXDM    | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| zh_CN       | 474       | 48.67%  |
| en_US       | 348       | 35.73%  |
| Unknown     | 94        | 9.65%   |
| C           | 15        | 1.54%   |
| en_HK       | 10        | 1.03%   |
| en_GB       | 9         | 0.92%   |
| C.UTF8      | 5         | 0.51%   |
| mn_CN       | 4         | 0.41%   |
| fr_FR       | 2         | 0.21%   |
| en_AU       | 2         | 0.21%   |
| zh_SG       | 1         | 0.1%    |
| th_TH       | 1         | 0.1%    |
| ru_RU       | 1         | 0.1%    |
| pt_PT       | 1         | 0.1%    |
| POSIX       | 1         | 0.1%    |
| ja_JP       | 1         | 0.1%    |
| en_ZA       | 1         | 0.1%    |
| en_US.UTF8  | 1         | 0.1%    |
| en_US,UTF-8 | 1         | 0.1%    |
| de_DE       | 1         | 0.1%    |
| .en_US      | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 679       | 70.07%  |
| BIOS | 290       | 29.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 707       | 72.51%  |
| Btrfs   | 139       | 14.26%  |
| Tmpfs   | 37        | 3.79%   |
| Overlay | 35        | 3.59%   |
| Xfs     | 32        | 3.28%   |
| Unknown | 17        | 1.74%   |
| F2fs    | 4         | 0.41%   |
| Zfs     | 3         | 0.31%   |
| XXXXXXX | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 612       | 63.03%  |
| Unknown | 304       | 31.31%  |
| MBR     | 55        | 5.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 858       | 87.91%  |
| Yes       | 118       | 12.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 545       | 56.36%  |
| Yes       | 422       | 43.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 328       | 34.24%  |
| Dell                           | 99        | 10.33%  |
| Hewlett-Packard                | 96        | 10.02%  |
| HUAWEI                         | 61        | 6.37%   |
| ASUSTek Computer               | 59        | 6.16%   |
| Timi                           | 48        | 5.01%   |
| Acer                           | 38        | 3.97%   |
| MECHREVO                       | 22        | 2.3%    |
| Apple                          | 18        | 1.88%   |
| HASEE Computer                 | 15        | 1.57%   |
| Unknown                        | 15        | 1.57%   |
| MSI                            | 14        | 1.46%   |
| Valve                          | 12        | 1.25%   |
| Toshiba                        | 10        | 1.04%   |
| HONOR                          | 9         | 0.94%   |
| Sony                           | 8         | 0.84%   |
| GPD                            | 8         | 0.84%   |
| Google                         | 8         | 0.84%   |
| Notebook                       | 6         | 0.63%   |
| XIAOMI                         | 5         | 0.52%   |
| Samsung Electronics            | 5         | 0.52%   |
| Intel Client Systems           | 4         | 0.42%   |
| Intel                          | 4         | 0.42%   |
| GreatWall                      | 4         | 0.42%   |
| Fujitsu                        | 4         | 0.42%   |
| Shanghai Zhaoxin Semiconductor | 3         | 0.31%   |
| Razer                          | 3         | 0.31%   |
| Jumper                         | 3         | 0.31%   |
| IPASON                         | 3         | 0.31%   |
| Insyde                         | 3         | 0.31%   |
| Alienware                      | 3         | 0.31%   |
| win element                    | 2         | 0.21%   |
| Terrans Force                  | 2         | 0.21%   |
| SmbiosType1_SystemManufacturer | 2         | 0.21%   |
| METAPHYUNI                     | 2         | 0.21%   |
| LG Electronics                 | 2         | 0.21%   |
| Gigabyte Technology            | 2         | 0.21%   |
| Clevo                          | 2         | 0.21%   |
| WUYING                         | 1         | 0.1%    |
| WOOKING                        | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 24        | 2.51%   |
| Valve Jupiter                           | 11        | 1.15%   |
| Lenovo Legion R9000P2021H 82JQ          | 10        | 1.04%   |
| HUAWEI HLY-WX9XX                        | 8         | 0.84%   |
| Timi RedmiBook Pro 15S                  | 6         | 0.63%   |
| Timi TM1701                             | 5         | 0.52%   |
| Lenovo Legion Y7000 81FW                | 5         | 0.52%   |
| Lenovo Legion R7000 2020 82B6           | 5         | 0.52%   |
| Timi TM1709                             | 4         | 0.42%   |
| Lenovo XiaoXinPro-13IML 2019 81XB       | 4         | 0.42%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM       | 4         | 0.42%   |
| Lenovo XiaoXin-15ARE 2020 81YR          | 4         | 0.42%   |
| Lenovo ThinkBook 15p Gen 2 21B1         | 4         | 0.42%   |
| Lenovo ThinkBook 14 G2 ITL 20VD         | 4         | 0.42%   |
| HUAWEI NBLK-WAX9X                       | 4         | 0.42%   |
| HUAWEI KPRC-WX0                         | 4         | 0.42%   |
| HUAWEI BOHK-WAX9X                       | 4         | 0.42%   |
| Dell XPS 15 9570                        | 4         | 0.42%   |
| Apple MacBookPro16,1                    | 4         | 0.42%   |
| Acer Swift SF314-512                    | 4         | 0.42%   |
| Timi TM1613                             | 3         | 0.31%   |
| Timi RedmiBook 14-APCS                  | 3         | 0.31%   |
| Timi RedmiBook 14 II                    | 3         | 0.31%   |
| Shanghai Zhaoxin ZXE CRB                | 3         | 0.31%   |
| Lenovo ZHAOYANG K4e-ITL 82F8            | 3         | 0.31%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN       | 3         | 0.31%   |
| Lenovo ThinkBook 14p Gen 2 20YN         | 3         | 0.31%   |
| Lenovo ThinkBook 14 G4+ IAP 21CX        | 3         | 0.31%   |
| Lenovo ThinkBook 14 G3 ACL 21A2         | 3         | 0.31%   |
| Intel H81U                              | 3         | 0.31%   |
| Intel Client Systems LAPKC71F           | 3         | 0.31%   |
| HUAWEI WRT-WX9                          | 3         | 0.31%   |
| HUAWEI KPR-WX9                          | 3         | 0.31%   |
| HUAWEI KPL-W0X                          | 3         | 0.31%   |
| HUAWEI KLVL-WXX9                        | 3         | 0.31%   |
| HONOR HYM-WXX                           | 3         | 0.31%   |
| HP ZHAN 66 Pro A 14 G3                  | 3         | 0.31%   |
| HP OMEN by Gaming Laptop 16-k0xxx       | 3         | 0.31%   |
| HP ENVY Laptop 13-ad1xx                 | 3         | 0.31%   |
| HP EliteBook 845 14 inch G9 Notebook PC | 3         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 142       | 14.82%  |
| Lenovo Legion           | 47        | 4.91%   |
| Dell Inspiron           | 34        | 3.55%   |
| Lenovo ThinkBook        | 30        | 3.13%   |
| HP EliteBook            | 24        | 2.51%   |
| Unknown                 | 24        | 2.51%   |
| Dell Latitude           | 22        | 2.3%    |
| HP OMEN                 | 20        | 2.09%   |
| Lenovo IdeaPad          | 17        | 1.77%   |
| HP ZHAN                 | 17        | 1.77%   |
| Timi RedmiBook          | 16        | 1.67%   |
| Lenovo ZHAOYANG         | 15        | 1.57%   |
| Acer Aspire             | 15        | 1.57%   |
| Dell XPS                | 13        | 1.36%   |
| ASUS ROG                | 13        | 1.36%   |
| Acer Swift              | 13        | 1.36%   |
| Dell Precision          | 12        | 1.25%   |
| Valve Jupiter           | 11        | 1.15%   |
| HP ProBook              | 11        | 1.15%   |
| Lenovo XiaoXinPro       | 10        | 1.04%   |
| Dell Vostro             | 10        | 1.04%   |
| HUAWEI HLY-WX9XX        | 8         | 0.84%   |
| Lenovo Yoga             | 7         | 0.73%   |
| HP Pavilion             | 7         | 0.73%   |
| ASUS VivoBook           | 7         | 0.73%   |
| Toshiba Satellite       | 6         | 0.63%   |
| Lenovo XiaoXin          | 6         | 0.63%   |
| ASUS ASUS               | 6         | 0.63%   |
| Acer Nitro              | 6         | 0.63%   |
| XIAOMI Redmi            | 5         | 0.52%   |
| Timi TM1701             | 5         | 0.52%   |
| Timi Redmi              | 5         | 0.52%   |
| HP ENVY                 | 5         | 0.52%   |
| ASUS TUF                | 5         | 0.52%   |
| Apple MacBookPro16      | 5         | 0.52%   |
| Timi TM1709             | 4         | 0.42%   |
| Lenovo XiaoXinPro-13IML | 4         | 0.42%   |
| Lenovo XiaoXinPro-13ARE | 4         | 0.42%   |
| Lenovo XiaoXin-15ARE    | 4         | 0.42%   |
| HUAWEI NBLK-WAX9X       | 4         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 148       | 15.45%  |
| 2020    | 124       | 12.94%  |
| 2019    | 108       | 11.27%  |
| 2022    | 103       | 10.75%  |
| 2018    | 77        | 8.04%   |
| 2023    | 55        | 5.74%   |
| 2017    | 52        | 5.43%   |
| 2014    | 44        | 4.59%   |
| 2013    | 43        | 4.49%   |
| 2016    | 40        | 4.18%   |
| 2012    | 39        | 4.07%   |
| 2011    | 38        | 3.97%   |
| 2015    | 33        | 3.44%   |
| 2008    | 20        | 2.09%   |
| 2010    | 8         | 0.84%   |
| 2009    | 8         | 0.84%   |
| 2007    | 7         | 0.73%   |
| 2024    | 6         | 0.63%   |
| 2006    | 3         | 0.31%   |
| Unknown | 2         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 958       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 866       | 89.56%  |
| Enabled  | 101       | 10.44%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 948       | 98.96%  |
| Yes  | 10        | 1.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 256       | 26.26%  |
| 16.01-24.0  | 237       | 24.31%  |
| 4.01-8.0    | 203       | 20.82%  |
| 32.01-64.0  | 101       | 10.36%  |
| 3.01-4.0    | 99        | 10.15%  |
| 24.01-32.0  | 33        | 3.38%   |
| 1.01-2.0    | 20        | 2.05%   |
| 64.01-256.0 | 19        | 1.95%   |
| 0.51-1.0    | 5         | 0.51%   |
| 0.01-0.5    | 1         | 0.1%    |
| Unknown     | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 268       | 25.6%   |
| 1.01-2.0   | 250       | 23.88%  |
| 4.01-8.0   | 213       | 20.34%  |
| 3.01-4.0   | 178       | 17%     |
| 8.01-16.0  | 64        | 6.11%   |
| 0.51-1.0   | 50        | 4.78%   |
| 0.01-0.5   | 15        | 1.43%   |
| 16.01-24.0 | 3         | 0.29%   |
| Unknown    | 3         | 0.29%   |
| 24.01-32.0 | 2         | 0.19%   |
| 32.01-64.0 | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 608       | 62.75%  |
| 2      | 308       | 31.79%  |
| 3      | 43        | 4.44%   |
| 4      | 7         | 0.72%   |
| 0      | 3         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 864       | 89.81%  |
| Yes       | 98        | 10.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 688       | 71.44%  |
| No        | 275       | 28.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 930       | 97.08%  |
| No        | 28        | 2.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 824       | 85.74%  |
| No        | 137       | 14.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| China   | 958       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Beijing          | 164       | 16%     |
| Shanghai         | 93        | 9.07%   |
| Shenzhen         | 74        | 7.22%   |
| Guangzhou        | 70        | 6.83%   |
| Hangzhou         | 39        | 3.8%    |
| Chengdu          | 36        | 3.51%   |
| Wuhan            | 26        | 2.54%   |
| Nanjing          | 24        | 2.34%   |
| Jinrongjie       | 22        | 2.15%   |
| Xi'an            | 20        | 1.95%   |
| Tianjin          | 17        | 1.66%   |
| Changsha         | 16        | 1.56%   |
| Zhengzhou        | 15        | 1.46%   |
| Chongqing        | 15        | 1.46%   |
| Dongguan         | 14        | 1.37%   |
| Kunming          | 12        | 1.17%   |
| Hefei            | 12        | 1.17%   |
| Shenyang         | 11        | 1.07%   |
| Nanning          | 11        | 1.07%   |
| Suzhou           | 10        | 0.98%   |
| Fuzhou           | 10        | 0.98%   |
| Dalian           | 10        | 0.98%   |
| Qingdao          | 9         | 0.88%   |
| Huangpu          | 9         | 0.88%   |
| Xuhui            | 8         | 0.78%   |
| Jinan            | 8         | 0.78%   |
| Foshan           | 8         | 0.78%   |
| Haidian          | 7         | 0.68%   |
| Changchun        | 7         | 0.68%   |
| Xiamen           | 6         | 0.59%   |
| Taiyuan          | 6         | 0.59%   |
| Pudong           | 6         | 0.59%   |
| Jianshui         | 5         | 0.49%   |
| Hohhot           | 5         | 0.49%   |
| Guiyang          | 5         | 0.49%   |
| Yangzhou         | 4         | 0.39%   |
| Xining           | 4         | 0.39%   |
| Xicheng District | 4         | 0.39%   |
| Shijiazhuang     | 4         | 0.39%   |
| Ningbo           | 4         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 271       | 356    | 20.45%  |
| WDC                          | 124       | 149    | 9.36%   |
| Sandisk                      | 99        | 114    | 7.47%   |
| Seagate                      | 91        | 107    | 6.87%   |
| SK hynix                     | 71        | 90     | 5.36%   |
| Toshiba                      | 69        | 78     | 5.21%   |
| Unknown                      | 50        | 58     | 3.77%   |
| Micron Technology            | 40        | 46     | 3.02%   |
| Intel                        | 35        | 48     | 2.64%   |
| Kingston                     | 29        | 34     | 2.19%   |
| HGST                         | 28        | 32     | 2.11%   |
| KIOXIA                       | 26        | 34     | 1.96%   |
| Yangtze Memory Technologies  | 21        | 25     | 1.58%   |
| Plextor                      | 17        | 19     | 1.28%   |
| Lenovo                       | 16        | 21     | 1.21%   |
| Crucial                      | 16        | 20     | 1.21%   |
| MAXIO Technology (Hangzhou)  | 14        | 16     | 1.06%   |
| LITEON                       | 14        | 16     | 1.06%   |
| Apple                        | 14        | 14     | 1.06%   |
| Hitachi                      | 13        | 18     | 0.98%   |
| Unknown                      | 13        | 13     | 0.98%   |
| Phison                       | 12        | 14     | 0.91%   |
| Phison Electronics           | 11        | 11     | 0.83%   |
| Silicon Motion               | 9         | 9      | 0.68%   |
| JMicron Technology           | 9         | 7      | 0.68%   |
| China                        | 9         | 19     | 0.68%   |
| A-DATA Technology            | 9         | 12     | 0.68%   |
| ZHITAI                       | 7         | 7      | 0.53%   |
| Hewlett-Packard              | 7         | 8      | 0.53%   |
| Transcend                    | 6         | 7      | 0.45%   |
| Kingchuxing                  | 6         | 8      | 0.45%   |
| Fanxiang                     | 6         | 6      | 0.45%   |
| Teclast                      | 5         | 5      | 0.38%   |
| KIOXIA-EXCERIA               | 5         | 8      | 0.38%   |
| Kingston Technology Company  | 5         | 5      | 0.38%   |
| KINGBANK                     | 5         | 8      | 0.38%   |
| Fujitsu                      | 5         | 5      | 0.38%   |
| External                     | 5         | 7      | 0.38%   |
| Colorful                     | 5         | 6      | 0.38%   |
| Shenzhen Longsys Electronics | 4         | 4      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 23        | 1.66%   |
| Samsung NVMe SSD Drive 512GB                       | 20        | 1.44%   |
| SanDisk NVMe SSD Drive 512GB                       | 17        | 1.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 17        | 1.23%   |
| Seagate ST1000LM035-1RK172 1TB                     | 16        | 1.15%   |
| Samsung MZVLB512HBJQ-000L2 512GB                   | 14        | 1.01%   |
| HGST HTS721010A9E630 1TB                           | 14        | 1.01%   |
| Unknown                                            | 13        | 0.94%   |
| Seagate ST1000LM048-2E7172 1TB                     | 12        | 0.87%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB             | 11        | 0.79%   |
| Seagate ST500LT012-1DG142 500GB                    | 11        | 0.79%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 11        | 0.79%   |
| Samsung SSD 980 1TB                                | 11        | 0.79%   |
| SK hynix NVMe SSD Drive 512GB                      | 10        | 0.72%   |
| Samsung MZVLB512HAJQ-00000 512GB                   | 10        | 0.72%   |
| Samsung NVMe SSD Drive 1024GB                      | 9         | 0.65%   |
| HGST HTS725050A7E630 500GB                         | 9         | 0.65%   |
| Toshiba MQ01ABD100 1TB                             | 8         | 0.58%   |
| Seagate ST2000LM007-1R8174 2TB                     | 8         | 0.58%   |
| SanDisk NVMe SSD Drive 1TB                         | 8         | 0.58%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 8         | 0.58%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 8         | 0.58%   |
| Yangtze Memory ZHITAI TiPlus5000 1TB               | 7         | 0.51%   |
| Seagate ST500LM021-1KJ152 500GB                    | 7         | 0.51%   |
| Sandisk WD Black SN850 512GB                       | 7         | 0.51%   |
| KIOXIA KBG40ZNV512G 512GB                          | 7         | 0.51%   |
| WDC WD10SPZX-22Z10T1 1TB                           | 6         | 0.43%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB               | 6         | 0.43%   |
| Unknown MMC Card  64GB                             | 6         | 0.43%   |
| Samsung SSD 860 EVO 500GB                          | 6         | 0.43%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 6         | 0.43%   |
| Plextor PX-128M6S 128GB SSD                        | 6         | 0.43%   |
| Micron 2450_MTFDKBA512TFK 512GB                    | 6         | 0.43%   |
| JMicron Generic 320GB                              | 6         | 0.43%   |
| WDC WDS100T2B0C-00PXH0 1TB                         | 5         | 0.36%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 5         | 0.36%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB          | 5         | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 5         | 0.36%   |
| Sandisk WD PC SN740 SDDPTQD-1T00 1024GB            | 5         | 0.36%   |
| Samsung NVMe SSD Drive 1TB                         | 5         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 91        | 106    | 38.08%  |
| WDC                 | 67        | 79     | 28.03%  |
| HGST                | 28        | 32     | 11.72%  |
| Toshiba             | 21        | 27     | 8.79%   |
| Hitachi             | 13        | 18     | 5.44%   |
| JMicron Technology  | 6         | 6      | 2.51%   |
| Samsung Electronics | 5         | 6      | 2.09%   |
| Fujitsu             | 5         | 5      | 2.09%   |
| TO Exter            | 1         | 1      | 0.42%   |
| HGST HTS            | 1         | 1      | 0.42%   |
| ACASIS              | 1         | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 66        | 88     | 20.12%  |
| SanDisk             | 24        | 26     | 7.32%   |
| Kingston            | 19        | 23     | 5.79%   |
| Toshiba             | 17        | 18     | 5.18%   |
| Plextor             | 15        | 17     | 4.57%   |
| LITEON              | 13        | 15     | 3.96%   |
| Lenovo              | 12        | 15     | 3.66%   |
| Crucial             | 11        | 15     | 3.35%   |
| WDC                 | 10        | 10     | 3.05%   |
| China               | 9         | 19     | 2.74%   |
| Micron Technology   | 8         | 9      | 2.44%   |
| SK hynix            | 7         | 7      | 2.13%   |
| Apple               | 7         | 7      | 2.13%   |
| A-DATA Technology   | 7         | 10     | 2.13%   |
| Unknown             | 7         | 7      | 2.13%   |
| Transcend           | 5         | 6      | 1.52%   |
| Teclast             | 5         | 5      | 1.52%   |
| Kingchuxing         | 5         | 7      | 1.52%   |
| Intel               | 5         | 5      | 1.52%   |
| External            | 5         | 7      | 1.52%   |
| Netac               | 4         | 4      | 1.22%   |
| LITEONIT            | 4         | 4      | 1.22%   |
| GLOWAY              | 4         | 4      | 1.22%   |
| GALAX               | 4         | 4      | 1.22%   |
| ZHITAI              | 3         | 3      | 0.91%   |
| Phison              | 3         | 4      | 0.91%   |
| KingSpec            | 3         | 3      | 0.91%   |
| Colorful            | 3         | 3      | 0.91%   |
| MaiChai             | 2         | 3      | 0.61%   |
| Lexar               | 2         | 2      | 0.61%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.61%   |
| Galaxy              | 2         | 2      | 0.61%   |
| FORESEE             | 2         | 2      | 0.61%   |
| Fanxiang            | 2         | 2      | 0.61%   |
| ASMT                | 2         | 2      | 0.61%   |
| XSJ-X100-256GB      | 1         | 1      | 0.3%    |
| Xinsujie            | 1         | 1      | 0.3%    |
| WDC WDS1            | 1         | 1      | 0.3%    |
| Unknown             | 1         | 1      | 0.3%    |
| UNIC2               | 1         | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 594       | 837    | 49.5%   |
| SSD     | 294       | 396    | 24.5%   |
| HDD     | 230       | 282    | 19.17%  |
| MMC     | 48        | 55     | 4%      |
| Unknown | 34        | 37     | 2.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 594       | 830    | 52.01%  |
| SATA | 431       | 644    | 37.74%  |
| SAS  | 69        | 78     | 6.04%   |
| MMC  | 48        | 55     | 4.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 319       | 435    | 62.18%  |
| 0.51-1.0   | 160       | 198    | 31.19%  |
| 1.01-2.0   | 28        | 36     | 5.46%   |
| 3.01-4.0   | 5         | 7      | 0.97%   |
| 10.01-20.0 | 1         | 2      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 275       | 27.53%  |
| 101-250        | 222       | 22.22%  |
| 501-1000       | 171       | 17.12%  |
| 1001-2000      | 86        | 8.61%   |
| 51-100         | 85        | 8.51%   |
| 1-20           | 52        | 5.21%   |
| More than 3000 | 35        | 3.5%    |
| 21-50          | 33        | 3.3%    |
| 2001-3000      | 26        | 2.6%    |
| Unknown        | 14        | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 359       | 34.85%  |
| 21-50          | 181       | 17.57%  |
| 101-250        | 149       | 14.47%  |
| 51-100         | 119       | 11.55%  |
| 251-500        | 104       | 10.1%   |
| 501-1000       | 59        | 5.73%   |
| 1001-2000      | 28        | 2.72%   |
| Unknown        | 14        | 1.36%   |
| More than 3000 | 10        | 0.97%   |
| 2001-3000      | 7         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                   | 4         | 4      | 7.84%   |
| Toshiba MQ04ABF100 1TB                       | 2         | 2      | 3.92%   |
| Toshiba MQ01ABF050 500GB                     | 2         | 2      | 3.92%   |
| Seagate ST500LT012-1DG142 500GB              | 2         | 2      | 3.92%   |
| Seagate ST500LM021-1KJ152 500GB              | 2         | 2      | 3.92%   |
| Seagate ST1000LM048-2E7172 1TB               | 2         | 2      | 3.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 3.92%   |
| HGST HTS721010A9E630 1TB                     | 2         | 2      | 3.92%   |
| WDC WD5000LPCX-24C6HT0 500GB                 | 1         | 1      | 1.96%   |
| WDC WD10SPZX-60Z10T0 1TB                     | 1         | 1      | 1.96%   |
| WDC WD10 JPVX-75JC3T0 1TB                    | 1         | 1      | 1.96%   |
| Union Memory UMIS RPITJ512PED2OWX 512GB      | 1         | 1      | 1.96%   |
| Toshiba MK3259GSXP 320GB                     | 1         | 1      | 1.96%   |
| Toshiba MK2555GSX 250GB                      | 1         | 1      | 1.96%   |
| Teclast 120GB S500 SSD                       | 1         | 1      | 1.96%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 1.96%   |
| Seagate ST750LM028-1KK162 752GB              | 1         | 1      | 1.96%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 2      | 1.96%   |
| Seagate ST320LT009-9WC142 320GB              | 1         | 1      | 1.96%   |
| SanDisk SSD U100 128GB                       | 1         | 1      | 1.96%   |
| SanDisk SD9SN8W-256G-1006 256GB SSD          | 1         | 1      | 1.96%   |
| Samsung Electronics MZVLW512HMJP-00000 512GB | 1         | 1      | 1.96%   |
| Plextor PX-128M6S 128GB SSD                  | 1         | 1      | 1.96%   |
| NT-512 2280 512GB SSD                        | 1         | 1      | 1.96%   |
| Netac SSD 120GB                              | 1         | 1      | 1.96%   |
| Lenovo SSD SL700 120G                        | 1         | 1      | 1.96%   |
| Kingston RBUSNS8180S3256GJ 256GB SSD         | 1         | 1      | 1.96%   |
| Intel SSDPEKKF256G7H 256GB                   | 1         | 1      | 1.96%   |
| HS-SSD-C160 SSD 1024G                        | 1         | 1      | 1.96%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 1.96%   |
| Hitachi HTS545050B9A300 500GB                | 1         | 1      | 1.96%   |
| Hitachi HTS541060G9SA00 64GB                 | 1         | 1      | 1.96%   |
| Hitachi HTS541040G9AT00 40GB                 | 1         | 1      | 1.96%   |
| HGST HTS545050A7E680 500GB                   | 1         | 1      | 1.96%   |
| GLOWAY STK240GS3-S7 240GB SSD                | 1         | 1      | 1.96%   |
| Fujitsu MHZ2250BH G2 250GB                   | 1         | 1      | 1.96%   |
| Fujitsu MHV2100BH PL 100GB                   | 1         | 1      | 1.96%   |
| Crucial M4-CT128M4SSD1 128GB                 | 1         | 1      | 1.96%   |
| Crucial CT240M500SSD1 240GB                  | 1         | 1      | 1.96%   |
| A-DATA Technology SP900 128GB SSD            | 1         | 2      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 23.53%  |
| HGST                | 7         | 7      | 13.73%  |
| Toshiba             | 6         | 6      | 11.76%  |
| Hitachi             | 4         | 4      | 7.84%   |
| WDC                 | 3         | 3      | 5.88%   |
| SanDisk             | 2         | 2      | 3.92%   |
| Fujitsu             | 2         | 2      | 3.92%   |
| Crucial             | 2         | 2      | 3.92%   |
| A-DATA Technology   | 2         | 3      | 3.92%   |
| Union Memory        | 1         | 1      | 1.96%   |
| Teclast             | 1         | 1      | 1.96%   |
| Samsung Electronics | 1         | 1      | 1.96%   |
| Plextor             | 1         | 1      | 1.96%   |
| NT-512              | 1         | 1      | 1.96%   |
| Netac               | 1         | 1      | 1.96%   |
| Lenovo              | 1         | 1      | 1.96%   |
| Kingston            | 1         | 1      | 1.96%   |
| Intel               | 1         | 1      | 1.96%   |
| HS-SSD-C160         | 1         | 1      | 1.96%   |
| GLOWAY              | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 13     | 35.29%  |
| HGST    | 7         | 7      | 20.59%  |
| Toshiba | 6         | 6      | 17.65%  |
| Hitachi | 4         | 4      | 11.76%  |
| WDC     | 3         | 3      | 8.82%   |
| Fujitsu | 2         | 2      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 35     | 66.67%  |
| SSD  | 14        | 15     | 27.45%  |
| NVMe | 3         | 3      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB  | 1         | 1      | 33.33%  |
| Samsung Electronics HS06THB 64GB | 1         | 1      | 33.33%  |
| Phison ESO128GTLC9-E8C-2 128GB   | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 66.67%  |
| Phison              | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 527       | 852    | 51.17%  |
| Detected | 449       | 699    | 43.59%  |
| Malfunc  | 51        | 53     | 4.95%   |
| Failed   | 3         | 3      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 482       | 38.16%  |
| Samsung Electronics                     | 217       | 17.18%  |
| SanDisk                                 | 122       | 9.66%   |
| AMD                                     | 112       | 8.87%   |
| SK hynix                                | 63        | 4.99%   |
| Micron Technology                       | 32        | 2.53%   |
| KIOXIA                                  | 31        | 2.45%   |
| Toshiba America Info Systems            | 30        | 2.38%   |
| Yangtze Memory Technologies             | 27        | 2.14%   |
| Phison Electronics                      | 22        | 1.74%   |
| MAXIO Technology (Hangzhou)             | 21        | 1.66%   |
| Silicon Motion                          | 18        | 1.43%   |
| Kingston Technology Company             | 15        | 1.19%   |
| Biwin Storage Technology                | 8         | 0.63%   |
| Shenzhen Longsys Electronics            | 7         | 0.55%   |
| Micron/Crucial Technology               | 7         | 0.55%   |
| Apple                                   | 7         | 0.55%   |
| Solid State Storage Technology          | 6         | 0.48%   |
| Zhaoxin                                 | 4         | 0.32%   |
| Marvell Technology Group                | 4         | 0.32%   |
| ADATA Technology                        | 4         | 0.32%   |
| Shenzhen Unionmemory Information System | 3         | 0.24%   |
| O2 Micro                                | 3         | 0.24%   |
| INNOGRIT                                | 3         | 0.24%   |
| Union Memory (Shenzhen)                 | 2         | 0.16%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.16%   |
| Lite-On Technology                      | 2         | 0.16%   |
| Hefei DATANG Storage Technology         | 2         | 0.16%   |
| Seagate Technology                      | 1         | 0.08%   |
| Realtek Semiconductor                   | 1         | 0.08%   |
| Nvidia                                  | 1         | 0.08%   |
| Lenovo                                  | 1         | 0.08%   |
| JMicron Technology                      | 1         | 0.08%   |
| ASMedia Technology                      | 1         | 0.08%   |
| Unknown                                 | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 109       | 8.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 104       | 7.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 74        | 5.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 49        | 3.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 44        | 3.32%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 39        | 2.95%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 34        | 2.57%   |
| Intel Volume Management Device NVMe RAID Controller                            | 33        | 2.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 33        | 2.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 31        | 2.34%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 30        | 2.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 27        | 2.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 27        | 2.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 1.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 22        | 1.66%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 21        | 1.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 19        | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 18        | 1.36%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 16        | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 16        | 1.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 14        | 1.06%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 13        | 0.98%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 13        | 0.98%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 13        | 0.98%   |
| Intel SSD 660P Series                                                          | 13        | 0.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 13        | 0.98%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 12        | 0.91%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 12        | 0.91%   |
| Yangtze Memory ZHITAI TiPro5000 NVMe SSD                                       | 11        | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 11        | 0.83%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 11        | 0.83%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                       | 11        | 0.83%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 11        | 0.83%   |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 0.76%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 10        | 0.76%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 10        | 0.76%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 9         | 0.68%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 9         | 0.68%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 8         | 0.6%    |
| Phison E12 NVMe Controller                                                     | 8         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 596       | 49.09%  |
| SATA | 525       | 43.25%  |
| RAID | 67        | 5.52%   |
| IDE  | 26        | 2.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 680       | 70.98%  |
| AMD          | 259       | 27.04%  |
| CentaurHauls | 9         | 0.94%   |
| Phytium      | 7         | 0.73%   |
| ARM          | 3         | 0.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics         | 44        | 4.59%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 26        | 2.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 23        | 2.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz              | 22        | 2.3%    |
| Intel 12th Gen Core i7-12700H                  | 20        | 2.09%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 20        | 2.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 18        | 1.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 17        | 1.77%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 15        | 1.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 15        | 1.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 15        | 1.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 14        | 1.46%   |
| AMD Ryzen 7 6800H with Radeon Graphics         | 14        | 1.46%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 14        | 1.46%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 13        | 1.36%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 12        | 1.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 11        | 1.15%   |
| AMD Custom APU 0405                            | 11        | 1.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 10        | 1.04%   |
| Intel 12th Gen Core i5-1240P                   | 10        | 1.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 9         | 0.94%   |
| Intel Core i5-8300H CPU @ 2.30GHz              | 9         | 0.94%   |
| Intel Core i5-5200U CPU @ 2.20GHz              | 9         | 0.94%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 8         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 8         | 0.84%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx  | 8         | 0.84%   |
| Intel Core i5-4200U CPU @ 1.60GHz              | 7         | 0.73%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 7         | 0.73%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 7         | 0.73%   |
| AMD Ryzen 5 4600U with Radeon Graphics         | 7         | 0.73%   |
| AMD Ryzen 5 4600H with Radeon Graphics         | 7         | 0.73%   |
| AMD Ryzen 5 4500U with Radeon Graphics         | 7         | 0.73%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 6         | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 6         | 0.63%   |
| Intel Core i3-2350M CPU @ 2.30GHz              | 6         | 0.63%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics     | 6         | 0.63%   |
| AMD Ryzen 7 4800U with Radeon Graphics         | 6         | 0.63%   |
| Intel Core i7-3630QM CPU @ 2.40GHz             | 5         | 0.52%   |
| Intel Core i7-10875H CPU @ 2.30GHz             | 5         | 0.52%   |
| Intel Core i7-10710U CPU @ 1.10GHz             | 5         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 214       | 22.34%  |
| Intel Core i7           | 183       | 19.1%   |
| Other                   | 169       | 17.64%  |
| AMD Ryzen 7             | 113       | 11.8%   |
| AMD Ryzen 5             | 68        | 7.1%    |
| Intel Core i3           | 44        | 4.59%   |
| Intel Core 2 Duo        | 20        | 2.09%   |
| Intel Celeron           | 20        | 2.09%   |
| Intel Atom              | 18        | 1.88%   |
| AMD Ryzen 9             | 17        | 1.77%   |
| AMD Ryzen 7 PRO         | 15        | 1.57%   |
| Intel Xeon              | 7         | 0.73%   |
| Intel Pentium           | 7         | 0.73%   |
| AMD A6                  | 7         | 0.73%   |
| Intel Core i9           | 6         | 0.63%   |
| Intel Core m3           | 5         | 0.52%   |
| AMD Ryzen 5 PRO         | 5         | 0.52%   |
| AMD A10                 | 5         | 0.52%   |
| AMD A8                  | 4         | 0.42%   |
| Intel Pentium Dual      | 3         | 0.31%   |
| Intel Core              | 3         | 0.31%   |
| AMD E2                  | 3         | 0.31%   |
| Intel Pentium Silver    | 2         | 0.21%   |
| Intel Genuine           | 2         | 0.21%   |
| Intel Core M            | 2         | 0.21%   |
| Intel Core 2            | 2         | 0.21%   |
| AMD Ryzen 3             | 2         | 0.21%   |
| AMD E                   | 2         | 0.21%   |
| AMD Athlon              | 2         | 0.21%   |
| AMD A4                  | 2         | 0.21%   |
| Intel Pentium M         | 1         | 0.1%    |
| Intel Core Duo          | 1         | 0.1%    |
| Intel Celeron Dual-Core | 1         | 0.1%    |
| ARM ARMv7               | 1         | 0.1%    |
| AMD Quad-Core           | 1         | 0.1%    |
| AMD C-50                | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 346       | 36.04%  |
| 2       | 264       | 27.5%   |
| 8       | 163       | 16.98%  |
| 6       | 103       | 10.73%  |
| 14      | 34        | 3.54%   |
| 12      | 26        | 2.71%   |
| 16      | 9         | 0.94%   |
| 1       | 7         | 0.73%   |
| 10      | 6         | 0.63%   |
| 20      | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 956       | 99.69%  |
| 3       | 2         | 0.21%   |
| Unknown | 1         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 819       | 85.22%  |
| 1       | 141       | 14.67%  |
| Unknown | 1         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 948       | 98.85%  |
| Unknown        | 6         | 0.63%   |
| 32-bit         | 5         | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 301       | 30.47%  |
| 0x0a50000c | 41        | 4.15%   |
| 0x906ea    | 40        | 4.05%   |
| 0x806ec    | 36        | 3.64%   |
| 0x306a9    | 35        | 3.54%   |
| 0x806ea    | 33        | 3.34%   |
| 0x806c1    | 29        | 2.94%   |
| 0x08600106 | 29        | 2.94%   |
| 0x806e9    | 26        | 2.63%   |
| 0x206a7    | 26        | 2.63%   |
| 0x906a3    | 23        | 2.33%   |
| 0x40651    | 23        | 2.33%   |
| 0x406e3    | 20        | 2.02%   |
| 0x306d4    | 20        | 2.02%   |
| 0x08108102 | 18        | 1.82%   |
| 0x0a404102 | 16        | 1.62%   |
| 0x506e3    | 15        | 1.52%   |
| 0xa0652    | 14        | 1.42%   |
| 0x306c3    | 14        | 1.42%   |
| 0x08108109 | 14        | 1.42%   |
| 0x08600104 | 13        | 1.32%   |
| 0x906e9    | 12        | 1.21%   |
| 0x806d1    | 12        | 1.21%   |
| 0x1067a    | 9         | 0.91%   |
| 0x0a704103 | 9         | 0.91%   |
| 0x30678    | 8         | 0.81%   |
| 0x0a404101 | 7         | 0.71%   |
| 0x08600103 | 7         | 0.71%   |
| 0x806eb    | 6         | 0.61%   |
| 0x706e5    | 6         | 0.61%   |
| 0xb06a2    | 5         | 0.51%   |
| 0xa0660    | 5         | 0.51%   |
| 0x906ed    | 5         | 0.51%   |
| 0x706a1    | 5         | 0.51%   |
| 0x0a601203 | 5         | 0.51%   |
| 0x0a50000b | 5         | 0.51%   |
| 0x08608103 | 5         | 0.51%   |
| 0x806c2    | 4         | 0.4%    |
| 0x6fd      | 4         | 0.4%    |
| 0x406c3    | 4         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 218       | 22.73%  |
| Unknown          | 117       | 12.2%   |
| Zen 3            | 62        | 6.47%   |
| Zen 2            | 59        | 6.15%   |
| TigerLake        | 56        | 5.84%   |
| Haswell          | 54        | 5.63%   |
| IvyBridge        | 51        | 5.32%   |
| Alderlake Hybrid | 45        | 4.69%   |
| Skylake          | 43        | 4.48%   |
| Zen+             | 36        | 3.75%   |
| SandyBridge      | 36        | 3.75%   |
| CometLake        | 29        | 3.02%   |
| Broadwell        | 24        | 2.5%    |
| Icelake          | 23        | 2.4%    |
| Silvermont       | 20        | 2.09%   |
| Penryn           | 19        | 1.98%   |
| Zen              | 8         | 0.83%   |
| Goldmont plus    | 7         | 0.73%   |
| Core             | 7         | 0.73%   |
| Westmere         | 5         | 0.52%   |
| Piledriver       | 5         | 0.52%   |
| Puma             | 4         | 0.42%   |
| Goldmont         | 4         | 0.42%   |
| Excavator        | 4         | 0.42%   |
| Bonnell          | 4         | 0.42%   |
| Tremont          | 3         | 0.31%   |
| Steamroller      | 3         | 0.31%   |
| P6               | 3         | 0.31%   |
| Jaguar           | 3         | 0.31%   |
| Bobcat           | 3         | 0.31%   |
| Nehalem          | 2         | 0.21%   |
| K10 Llano        | 2         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 620       | 47.04%  |
| Nvidia                           | 376       | 28.53%  |
| AMD                              | 311       | 23.6%   |
| Zhaoxin                          | 9         | 0.68%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |
| Nanjing Ruixinview Technology    | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 55        | 4.08%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 53        | 3.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 49        | 3.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 48        | 3.56%   |
| Intel UHD Graphics 620                                                                   | 46        | 3.41%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 40        | 2.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 2.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 37        | 2.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 36        | 2.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 32        | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 29        | 2.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 29        | 2.15%   |
| AMD Rembrandt [Radeon 680M]                                                              | 29        | 2.15%   |
| Intel HD Graphics 620                                                                    | 28        | 2.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 1.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 25        | 1.86%   |
| Nvidia GP108M [GeForce MX250]                                                            | 21        | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 1.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 1.48%   |
| Nvidia GP108M [GeForce MX150]                                                            | 18        | 1.34%   |
| Intel HD Graphics 5500                                                                   | 17        | 1.26%   |
| Nvidia TU117M [GeForce MX450]                                                            | 15        | 1.11%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 15        | 1.11%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 1.04%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 13        | 0.97%   |
| Intel HD Graphics 630                                                                    | 12        | 0.89%   |
| Intel HD Graphics 530                                                                    | 12        | 0.89%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 12        | 0.89%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 11        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 0.82%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 11        | 0.82%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 0.82%   |
| AMD Phoenix1                                                                             | 11        | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 0.74%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 10        | 0.74%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 10        | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.67%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 9         | 0.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 305       | 31.67%  |
| Intel + Nvidia                    | 268       | 27.83%  |
| 1 x AMD                           | 192       | 19.94%  |
| 1 x Nvidia                        | 61        | 6.33%   |
| AMD + Nvidia                      | 51        | 5.3%    |
| Intel + AMD                       | 48        | 4.98%   |
| 2 x AMD                           | 19        | 1.97%   |
| 1 x Zhaoxin                       | 9         | 0.93%   |
| 2 x Intel                         | 5         | 0.52%   |
| Other                             | 3         | 0.31%   |
| 1 x SiS                           | 1         | 0.1%    |
| 1 x Nanjing Ruixinview Technology | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 720       | 74%     |
| Proprietary | 197       | 20.25%  |
| Unknown     | 56        | 5.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 550       | 56.01%  |
| 1.01-2.0   | 135       | 13.75%  |
| 0.01-0.5   | 108       | 11%     |
| 3.01-4.0   | 65        | 6.62%   |
| 0.51-1.0   | 64        | 6.52%   |
| 5.01-6.0   | 35        | 3.56%   |
| 7.01-8.0   | 19        | 1.93%   |
| 8.01-16.0  | 3         | 0.31%   |
| 2.01-3.0   | 2         | 0.2%    |
| 16.01-24.0 | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 185       | 18.05%  |
| AU Optronics            | 161       | 15.71%  |
| Chimei Innolux          | 130       | 12.68%  |
| LG Display              | 120       | 11.71%  |
| CSO                     | 53        | 5.17%   |
| Samsung Electronics     | 46        | 4.49%   |
| Sharp                   | 38        | 3.71%   |
| Lenovo                  | 28        | 2.73%   |
| Dell                    | 26        | 2.54%   |
| AOC                     | 23        | 2.24%   |
| PANDA                   | 20        | 1.95%   |
| TMX                     | 19        | 1.85%   |
| Apple                   | 17        | 1.66%   |
| Philips                 | 14        | 1.37%   |
| InfoVision              | 13        | 1.27%   |
| Valve                   | 10        | 0.98%   |
| Goldstar                | 9         | 0.88%   |
| RTK                     | 8         | 0.78%   |
| Hewlett-Packard         | 7         | 0.68%   |
| Chi Mei Optoelectronics | 7         | 0.68%   |
| Mi                      | 6         | 0.59%   |
| SGT                     | 5         | 0.49%   |
| BenQ                    | 5         | 0.49%   |
| Panasonic               | 4         | 0.39%   |
| JDI                     | 4         | 0.39%   |
| IPS                     | 4         | 0.39%   |
| TMA                     | 3         | 0.29%   |
| LGD                     | 3         | 0.29%   |
| BOE Technology Group    | 3         | 0.29%   |
| Xiaomi                  | 2         | 0.2%    |
| ViewSonic               | 2         | 0.2%    |
| Sony                    | 2         | 0.2%    |
| LG Philips              | 2         | 0.2%    |
| InnoLux Display         | 2         | 0.2%    |
| HKC                     | 2         | 0.2%    |
| ASUSTek Computer        | 2         | 0.2%    |
| Analogix                | 2         | 0.2%    |
| AML                     | 2         | 0.2%    |
| Acer                    | 2         | 0.2%    |
| WST                     | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch | 18        | 1.74%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch              | 9         | 0.87%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch            | 9         | 0.87%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch            | 9         | 0.87%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch | 8         | 0.78%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch            | 7         | 0.68%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch            | 7         | 0.68%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch            | 7         | 0.68%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch   | 7         | 0.68%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch   | 7         | 0.68%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch    | 7         | 0.68%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch          | 6         | 0.58%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch          | 6         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch | 6         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch | 6         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch | 6         | 0.58%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch            | 6         | 0.58%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch     | 5         | 0.48%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch     | 5         | 0.48%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch      | 5         | 0.48%   |
| CSO LCD Monitor CSO076D 2560x1600 286x179mm 13.3-inch            | 5         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 355x199mm 16.0-inch | 5         | 0.48%   |
| BOE LCD Monitor BOE098E 1920x1080 344x194mm 15.5-inch            | 5         | 0.48%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch            | 5         | 0.48%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch    | 5         | 0.48%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch          | 4         | 0.39%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch          | 4         | 0.39%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch     | 4         | 0.39%   |
| LG Display LCD Monitor LGD0619 1920x1080 309x174mm 14.0-inch     | 4         | 0.39%   |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch     | 4         | 0.39%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch      | 4         | 0.39%   |
| InfoVision LCD Monitor IVO061F 1920x1080 309x174mm 14.0-inch     | 4         | 0.39%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch            | 4         | 0.39%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch | 4         | 0.39%   |
| BOE LCD Monitor BOE092E 1920x1080 310x173mm 14.0-inch            | 4         | 0.39%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch            | 4         | 0.39%   |
| AU Optronics LCD Monitor AUOC391 2880x1800 301x188mm 14.0-inch   | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO45ED 1920x1080 344x193mm 15.5-inch   | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch   | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch   | 4         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 456       | 47.11%  |
| 1366x768 (WXGA)    | 150       | 15.5%   |
| 2560x1600          | 73        | 7.54%   |
| 2560x1440 (QHD)    | 62        | 6.4%    |
| 3840x2160 (4K)     | 53        | 5.48%   |
| 2880x1800          | 26        | 2.69%   |
| 1920x1200 (WUXGA)  | 21        | 2.17%   |
| 2160x1440          | 15        | 1.55%   |
| 1280x800 (WXGA)    | 14        | 1.45%   |
| 3200x2000          | 13        | 1.34%   |
| 800x1280           | 12        | 1.24%   |
| 1600x900 (HD+)     | 11        | 1.14%   |
| 1440x900 (WXGA+)   | 9         | 0.93%   |
| 2240x1400          | 7         | 0.72%   |
| 3072x1920          | 6         | 0.62%   |
| 3840x2400          | 5         | 0.52%   |
| 2520x1680          | 5         | 0.52%   |
| 1680x1050 (WSXGA+) | 5         | 0.52%   |
| 3440x1440          | 3         | 0.31%   |
| 3000x2000          | 3         | 0.31%   |
| 2560x1080          | 2         | 0.21%   |
| 2256x1504          | 2         | 0.21%   |
| 1024x600           | 2         | 0.21%   |
| 3840x1080          | 1         | 0.1%    |
| 3200x1800 (QHD+)   | 1         | 0.1%    |
| 2880x1920          | 1         | 0.1%    |
| 2880x1620          | 1         | 0.1%    |
| 2160x1350          | 1         | 0.1%    |
| 1920x540           | 1         | 0.1%    |
| 1920x1280          | 1         | 0.1%    |
| 1792x768           | 1         | 0.1%    |
| 1600x2560          | 1         | 0.1%    |
| 1400x1050          | 1         | 0.1%    |
| 1280x1024 (SXGA)   | 1         | 0.1%    |
| 1024x768 (XGA)     | 1         | 0.1%    |
| Unknown            | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 278       | 27.2%   |
| 14      | 208       | 20.35%  |
| 13      | 202       | 19.77%  |
| 16      | 81        | 7.93%   |
| 24      | 43        | 4.21%   |
| 27      | 40        | 3.91%   |
| 17      | 33        | 3.23%   |
| 12      | 31        | 3.03%   |
| 23      | 29        | 2.84%   |
| Unknown | 14        | 1.37%   |
| 7       | 10        | 0.98%   |
| 21      | 7         | 0.68%   |
| 11      | 7         | 0.68%   |
| 40      | 6         | 0.59%   |
| 34      | 4         | 0.39%   |
| 22      | 4         | 0.39%   |
| 31      | 3         | 0.29%   |
| 19      | 3         | 0.29%   |
| 18      | 3         | 0.29%   |
| 65      | 2         | 0.2%    |
| 10      | 2         | 0.2%    |
| 3       | 2         | 0.2%    |
| 63      | 1         | 0.1%    |
| 57      | 1         | 0.1%    |
| 52      | 1         | 0.1%    |
| 43      | 1         | 0.1%    |
| 36      | 1         | 0.1%    |
| 32      | 1         | 0.1%    |
| 26      | 1         | 0.1%    |
| 25      | 1         | 0.1%    |
| 20      | 1         | 0.1%    |
| 8       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 628       | 61.63%  |
| 201-300     | 153       | 15.01%  |
| 501-600     | 106       | 10.4%   |
| 351-400     | 59        | 5.79%   |
| 401-500     | 18        | 1.77%   |
| Unknown     | 14        | 1.37%   |
| 1-100       | 12        | 1.18%   |
| 601-700     | 10        | 0.98%   |
| 701-800     | 7         | 0.69%   |
| 801-900     | 6         | 0.59%   |
| 1001-1500   | 4         | 0.39%   |
| 101-200     | 1         | 0.1%    |
| 901-1000    | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 667       | 73.22%  |
| 16/10   | 177       | 19.43%  |
| 3/2     | 30        | 3.29%   |
| Unknown | 13        | 1.43%   |
| 0.67    | 9         | 0.99%   |
| 21/9    | 5         | 0.55%   |
| 4/3     | 4         | 0.44%   |
| 6/5     | 2         | 0.22%   |
| 0.62    | 2         | 0.22%   |
| 5/4     | 1         | 0.11%   |
| 0.56    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 324       | 31.73%  |
| 101-110        | 285       | 27.91%  |
| 71-80          | 82        | 8.03%   |
| 201-250        | 72        | 7.05%   |
| 111-120        | 68        | 6.66%   |
| 301-350        | 41        | 4.02%   |
| 121-130        | 31        | 3.04%   |
| 61-70          | 28        | 2.74%   |
| Unknown        | 14        | 1.37%   |
| 1-40           | 13        | 1.27%   |
| 91-100         | 11        | 1.08%   |
| 151-200        | 10        | 0.98%   |
| 351-500        | 8         | 0.78%   |
| 251-300        | 8         | 0.78%   |
| 501-1000       | 8         | 0.78%   |
| 51-60          | 7         | 0.69%   |
| More than 1000 | 5         | 0.49%   |
| 141-150        | 3         | 0.29%   |
| 41-50          | 2         | 0.2%    |
| 131-140        | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 429       | 42.64%  |
| 161-240       | 219       | 21.77%  |
| 101-120       | 161       | 16%     |
| 51-100        | 106       | 10.54%  |
| More than 240 | 73        | 7.26%   |
| Unknown       | 14        | 1.39%   |
| 1-50          | 4         | 0.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 761       | 78.05%  |
| 2     | 148       | 15.18%  |
| 0     | 60        | 6.15%   |
| 3     | 6         | 0.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 577       | 39.25%  |
| Realtek Semiconductor                  | 526       | 35.78%  |
| Qualcomm Atheros                       | 136       | 9.25%   |
| MediaTek                               | 46        | 3.13%   |
| Broadcom                               | 40        | 2.72%   |
| ASIX Electronics                       | 25        | 1.7%    |
| Broadcom Limited                       | 22        | 1.5%    |
| Huawei Technologies                    | 15        | 1.02%   |
| Qualcomm                               | 14        | 0.95%   |
| Xiaomi                                 | 10        | 0.68%   |
| Ralink                                 | 6         | 0.41%   |
| Quectel Wireless Solutions             | 6         | 0.41%   |
| OPPO Electronics                       | 5         | 0.34%   |
| Ralink Technology                      | 4         | 0.27%   |
| TP-Link                                | 3         | 0.2%    |
| Marvell Technology Group               | 3         | 0.2%    |
| ICS Advent                             | 3         | 0.2%    |
| ZTE WCDMA Technologies MSM             | 2         | 0.14%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.14%   |
| Sierra Wireless                        | 2         | 0.14%   |
| Microsoft                              | 2         | 0.14%   |
| DisplayLink                            | 2         | 0.14%   |
| Dell                                   | 2         | 0.14%   |
| Unknown                                | 2         | 0.14%   |
| Wilocity                               | 1         | 0.07%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.07%   |
| ST-Ericsson                            | 1         | 0.07%   |
| Shenzhen Goodix Technology             | 1         | 0.07%   |
| Samsung Electronics                    | 1         | 0.07%   |
| Qualcomm Technologies                  | 1         | 0.07%   |
| Qualcomm Atheros Communications        | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.07%   |
| Nvidia                                 | 1         | 0.07%   |
| Meizu                                  | 1         | 0.07%   |
| Lenovo                                 | 1         | 0.07%   |
| Hewlett-Packard                        | 1         | 0.07%   |
| Attansic Technology                    | 1         | 0.07%   |
| Apple                                  | 1         | 0.07%   |
| Android                                | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 320       | 18.85%  |
| Intel Wi-Fi 6 AX200                                                    | 75        | 4.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 64        | 3.77%   |
| Intel Wireless 8265 / 8275                                             | 48        | 2.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 45        | 2.65%   |
| Intel Wi-Fi 6 AX201                                                    | 42        | 2.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 41        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 2.24%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 35        | 2.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 31        | 1.83%   |
| Intel Wireless 7265                                                    | 30        | 1.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 29        | 1.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 27        | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 23        | 1.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 23        | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 21        | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 20        | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 1.12%   |
| Intel Wireless 7260                                                    | 19        | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19        | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 18        | 1.06%   |
| Intel Wireless 3165                                                    | 17        | 1%      |
| ASIX AX88179 Gigabit Ethernet                                          | 17        | 1%      |
| Intel Wireless 8260                                                    | 16        | 0.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 14        | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 13        | 0.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 13        | 0.77%   |
| Intel Ethernet Connection (4) I219-V                                   | 13        | 0.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 12        | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 12        | 0.71%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 12        | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 12        | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 12        | 0.71%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 11        | 0.65%   |
| Huawei VTR-L09                                                         | 11        | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 10        | 0.59%   |
| Intel Ethernet Connection (16) I219-V                                  | 10        | 0.59%   |
| Intel 82567LM Gigabit Network Connection                               | 10        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 9         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 550       | 56.94%  |
| Realtek Semiconductor           | 165       | 17.08%  |
| Qualcomm Atheros                | 110       | 11.39%  |
| MediaTek                        | 46        | 4.76%   |
| Broadcom                        | 34        | 3.52%   |
| Broadcom Limited                | 15        | 1.55%   |
| Qualcomm                        | 12        | 1.24%   |
| Ralink                          | 6         | 0.62%   |
| Quectel Wireless Solutions      | 6         | 0.62%   |
| Ralink Technology               | 4         | 0.41%   |
| Xiaomi                          | 3         | 0.31%   |
| TP-Link                         | 3         | 0.31%   |
| Sierra Wireless                 | 2         | 0.21%   |
| Microsoft                       | 2         | 0.21%   |
| Dell                            | 2         | 0.21%   |
| Unknown                         | 2         | 0.21%   |
| Wilocity                        | 1         | 0.1%    |
| Qualcomm Technologies           | 1         | 0.1%    |
| Qualcomm Atheros Communications | 1         | 0.1%    |
| Hewlett-Packard                 | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 75        | 7.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 64        | 6.59%   |
| Intel Wireless 8265 / 8275                                     | 48        | 4.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 45        | 4.63%   |
| Intel Wi-Fi 6 AX201                                            | 42        | 4.33%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 35        | 3.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 31        | 3.19%   |
| Intel Wireless 7265                                            | 30        | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 29        | 2.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 27        | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 2.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21        | 2.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 20        | 2.06%   |
| Intel Wireless 7260                                            | 19        | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19        | 1.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 18        | 1.85%   |
| Intel Wireless 3165                                            | 17        | 1.75%   |
| Intel Wireless 8260                                            | 16        | 1.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 14        | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13        | 1.34%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 13        | 1.34%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 12        | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 12        | 1.24%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 12        | 1.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 1.24%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 11        | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 9         | 0.93%   |
| Intel Wireless 3160                                            | 9         | 0.93%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 9         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 8         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 8         | 0.82%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 8         | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 0.72%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter             | 7         | 0.72%   |
| Quectel Wireless Solutions Quectel EM05-CE                     | 6         | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 0.62%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 429       | 60.68%  |
| Intel                                  | 156       | 22.07%  |
| Qualcomm Atheros                       | 38        | 5.37%   |
| ASIX Electronics                       | 25        | 3.54%   |
| Huawei Technologies                    | 11        | 1.56%   |
| Broadcom                               | 9         | 1.27%   |
| Xiaomi                                 | 7         | 0.99%   |
| Broadcom Limited                       | 7         | 0.99%   |
| OPPO Electronics                       | 5         | 0.71%   |
| Marvell Technology Group               | 3         | 0.42%   |
| ICS Advent                             | 3         | 0.42%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.28%   |
| DisplayLink                            | 2         | 0.28%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.14%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.14%   |
| Samsung Electronics                    | 1         | 0.14%   |
| Qualcomm                               | 1         | 0.14%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.14%   |
| Nvidia                                 | 1         | 0.14%   |
| Lenovo                                 | 1         | 0.14%   |
| Attansic Technology                    | 1         | 0.14%   |
| Apple                                  | 1         | 0.14%   |
| Android                                | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 320       | 44.63%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 41        | 5.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 5.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23        | 3.21%   |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 2.65%   |
| ASIX AX88179 Gigabit Ethernet                                          | 17        | 2.37%   |
| Intel Ethernet Connection (4) I219-V                                   | 13        | 1.81%   |
| Huawei VTR-L09                                                         | 11        | 1.53%   |
| Intel Ethernet Connection (16) I219-V                                  | 10        | 1.39%   |
| Intel 82567LM Gigabit Network Connection                               | 10        | 1.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 8         | 1.12%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 8         | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                                  | 7         | 0.98%   |
| Intel Ethernet Connection (13) I219-V                                  | 7         | 0.98%   |
| Intel Ethernet Connection (10) I219-V                                  | 7         | 0.98%   |
| ASIX AX88772B                                                          | 7         | 0.98%   |
| Realtek Killer E2600 GbE Controller                                    | 6         | 0.84%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 0.7%    |
| Intel Ethernet Controller I225-V                                       | 5         | 0.7%    |
| Intel Ethernet Connection I217-LM                                      | 5         | 0.7%    |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 4         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 4         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.42%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 3         | 0.42%   |
| Intel Ethernet Connection I219-V                                       | 3         | 0.42%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.42%   |
| Intel Ethernet Connection (3) I218-V                                   | 3         | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.42%   |
| Intel 82566MM Gigabit Network Connection                               | 3         | 0.42%   |
| ICS Advent 10/100M LAN                                                 | 3         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 929       | 57.45%  |
| Ethernet | 678       | 41.93%  |
| Unknown  | 6         | 0.37%   |
| Modem    | 4         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 749       | 76.35%  |
| Ethernet | 232       | 23.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 587       | 61.21%  |
| 1     | 339       | 35.35%  |
| 0     | 20        | 2.09%   |
| 3     | 12        | 1.25%   |
| 6     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 784       | 79.92%  |
| Yes  | 197       | 20.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 484       | 58.52%  |
| Realtek Semiconductor           | 80        | 9.67%   |
| Qualcomm Atheros Communications | 55        | 6.65%   |
| Foxconn / Hon Hai               | 44        | 5.32%   |
| IMC Networks                    | 35        | 4.23%   |
| Realtek                         | 30        | 3.63%   |
| Broadcom                        | 28        | 3.39%   |
| Lite-On Technology              | 15        | 1.81%   |
| Apple                           | 12        | 1.45%   |
| MediaTek                        | 9         | 1.09%   |
| Opticis                         | 6         | 0.73%   |
| Dell                            | 5         | 0.6%    |
| Ralink                          | 4         | 0.48%   |
| Hewlett-Packard                 | 4         | 0.48%   |
| Foxconn International           | 4         | 0.48%   |
| Cambridge Silicon Radio         | 4         | 0.48%   |
| Taiyo Yuden                     | 2         | 0.24%   |
| Alps Electric                   | 2         | 0.24%   |
| USI                             | 1         | 0.12%   |
| Toshiba                         | 1         | 0.12%   |
| SINO WEALTH                     | 1         | 0.12%   |
| ASUSTek Computer                | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 109       | 13.18%  |
| Intel Bluetooth wireless interface                  | 76        | 9.19%   |
| Intel AX200 Bluetooth                               | 72        | 8.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 70        | 8.46%   |
| Realtek Bluetooth Radio                             | 62        | 7.5%    |
| Intel Bluetooth Device                              | 59        | 7.13%   |
| Intel AX211 Bluetooth                               | 41        | 4.96%   |
| Qualcomm Atheros  Bluetooth Device                  | 35        | 4.23%   |
| Intel AX210 Bluetooth                               | 32        | 3.87%   |
| Realtek Bluetooth Radio                             | 30        | 3.63%   |
| IMC Networks Bluetooth Radio                        | 21        | 2.54%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 1.69%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 1.45%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 1.45%   |
| Realtek RTL8723B Bluetooth                          | 9         | 1.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 9         | 1.09%   |
| MediaTek Wireless_Device                            | 9         | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 1.09%   |
| Apple Bluetooth Host Controller                     | 9         | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 0.97%   |
| IMC Networks Wireless_Device                        | 8         | 0.97%   |
| Lite-On Bluetooth Device                            | 7         | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 7         | 0.85%   |
| Opticis Bluetooth Radio                             | 6         | 0.73%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 6         | 0.73%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 6         | 0.73%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.6%    |
| IMC Networks Bluetooth Device                       | 5         | 0.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.6%    |
| Ralink RT3290 Bluetooth                             | 4         | 0.48%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 0.48%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 0.36%   |
| Taiyo Yuden Bluetooth Device                        | 2         | 0.24%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.24%   |
| Lite-On Wireless_Device                             | 2         | 0.24%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]         | 2         | 0.24%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.24%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 656       | 55.59%  |
| AMD                                          | 278       | 23.56%  |
| Nvidia                                       | 197       | 16.69%  |
| Zhaoxin                                      | 9         | 0.76%   |
| Apple                                        | 7         | 0.59%   |
| C-Media Electronics                          | 4         | 0.34%   |
| Huawei Technologies                          | 3         | 0.25%   |
| Generalplus Technology                       | 3         | 0.25%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.17%   |
| Yamaha                                       | 2         | 0.17%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.17%   |
| Realtek Semiconductor                        | 2         | 0.17%   |
| BY EDIFIER                                   | 2         | 0.17%   |
| XMOS                                         | 1         | 0.08%   |
| Specialix                                    | 1         | 0.08%   |
| SoundPlus Technology                         | 1         | 0.08%   |
| Samsung Electronics                          | 1         | 0.08%   |
| Razer USA                                    | 1         | 0.08%   |
| OPPO Electronics                             | 1         | 0.08%   |
| JMTek                                        | 1         | 0.08%   |
| Focusrite-Novation                           | 1         | 0.08%   |
| EDIFIER                                      | 1         | 0.08%   |
| Conexant Systems                             | 1         | 0.08%   |
| Cambridge Silicon Radio                      | 1         | 0.08%   |
| BR25                                         | 1         | 0.08%   |
| ACTIONS                                      | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                     | Notebooks | Percent |
|-------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                    | 219       | 14.87%  |
| Intel Sunrise Point-LP HD Audio                                                           | 111       | 7.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                        | 94        | 6.38%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                     | 57        | 3.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                               | 56        | 3.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                       | 53        | 3.6%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                   | 50        | 3.39%   |
| Intel Cannon Lake PCH cAVS                                                                | 49        | 3.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                       | 43        | 2.92%   |
| Nvidia GA106 High Definition Audio Controller                                             | 35        | 2.38%   |
| Nvidia Audio device                                                                       | 35        | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                                              | 35        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                | 34        | 2.31%   |
| Intel Haswell-ULT HD Audio Controller                                                     | 30        | 2.04%   |
| Intel 8 Series HD Audio Controller                                                        | 30        | 2.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                            | 28        | 1.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                    | 28        | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                   | 24        | 1.63%   |
| Intel Broadwell-U Audio Controller                                                        | 24        | 1.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                       | 24        | 1.63%   |
| Intel Comet Lake PCH cAVS                                                                 | 23        | 1.56%   |
| Nvidia TU106 High Definition Audio Controller                                             | 22        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                          | 20        | 1.36%   |
| AMD FCH Azalia Controller                                                                 | 18        | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                           | 17        | 1.15%   |
| Intel Tiger Lake-H HD Audio Controller                                                    | 16        | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                            | 16        | 1.09%   |
| Intel CM238 HD Audio Controller                                                           | 15        | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                                           | 12        | 0.81%   |
| Intel Raptor Lake-P/U/H cAVS                                                              | 11        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                                             | 10        | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                             | 10        | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                                             | 10        | 0.68%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller | 9         | 0.61%   |
| AMD Kabini HDMI/DP Audio                                                                  | 9         | 0.61%   |
| Zhaoxin ZX-E High Definition Audio Controller                                             | 8         | 0.54%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                 | 7         | 0.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                              | 7         | 0.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                  | 7         | 0.48%   |
| Apple Audio Device                                                                        | 7         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 251       | 33.2%   |
| SK hynix                   | 167       | 22.09%  |
| Micron Technology          | 109       | 14.42%  |
| Kingston                   | 68        | 8.99%   |
| Unknown                    | 34        | 4.5%    |
| Crucial                    | 34        | 4.5%    |
| Ramaxel Technology         | 19        | 2.51%   |
| Elpida                     | 9         | 1.19%   |
| A-DATA Technology          | 9         | 1.19%   |
| Unknown (ABCD)             | 7         | 0.93%   |
| Nanya Technology           | 6         | 0.79%   |
| Transcend                  | 4         | 0.53%   |
| Lenovo                     | 4         | 0.53%   |
| Unknown                    | 4         | 0.53%   |
| Unknown (08C8)             | 3         | 0.4%    |
| Shenzhen WODPOSIT          | 3         | 0.4%    |
| KINGBANK                   | 3         | 0.4%    |
| UnilC                      | 2         | 0.26%   |
| Team                       | 2         | 0.26%   |
| Corsair                    | 2         | 0.26%   |
| Apacer                     | 2         | 0.26%   |
| Xi'an UniIC Semiconductors | 1         | 0.13%   |
| Unknown (08B5)             | 1         | 0.13%   |
| SK_Hynix                   | 1         | 0.13%   |
| SHARETRONIC                | 1         | 0.13%   |
| MTASE                      | 1         | 0.13%   |
| Lexar Co Limited           | 1         | 0.13%   |
| KLEVV                      | 1         | 0.13%   |
| Kimtigo                    | 1         | 0.13%   |
| Juhor                      | 1         | 0.13%   |
| Goldkey                    | 1         | 0.13%   |
| G.Skill                    | 1         | 0.13%   |
| Essencore                  | 1         | 0.13%   |
| Asgard                     | 1         | 0.13%   |
| <Unknown>                  | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 24        | 2.97%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 1.36%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 11        | 1.36%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 10        | 1.24%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 1.24%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 1.12%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 9         | 1.12%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 1.12%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.99%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.99%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.87%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 7         | 0.87%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 6         | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 0.74%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 6         | 0.74%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 6         | 0.74%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 6         | 0.74%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 6         | 0.74%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 6         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.62%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 5         | 0.62%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 5         | 0.62%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.62%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 5         | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.62%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM DDR5 4800MT/s          | 5         | 0.62%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.62%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 5         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.5%    |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 4         | 0.5%    |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.5%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.5%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.5%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 354       | 53.72%  |
| DDR3    | 124       | 18.82%  |
| DDR5    | 53        | 8.04%   |
| LPDDR4  | 45        | 6.83%   |
| LPDDR3  | 36        | 5.46%   |
| LPDDR5  | 27        | 4.1%    |
| DDR2    | 9         | 1.37%   |
| SDRAM   | 7         | 1.06%   |
| Unknown | 3         | 0.46%   |
| DDR     | 1         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 489       | 73.42%  |
| Row Of Chips | 165       | 24.77%  |
| Chip         | 6         | 0.9%    |
| DIMM         | 3         | 0.45%   |
| Unknown      | 3         | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 358       | 50.85%  |
| 4096  | 152       | 21.59%  |
| 16384 | 115       | 16.34%  |
| 2048  | 41        | 5.82%   |
| 32768 | 28        | 3.98%   |
| 1024  | 8         | 1.14%   |
| 12288 | 1         | 0.14%   |
| 512   | 1         | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 173       | 25.29%  |
| 2667    | 149       | 21.78%  |
| 1600    | 95        | 13.89%  |
| 4800    | 43        | 6.29%   |
| 2400    | 36        | 5.26%   |
| 2133    | 34        | 4.97%   |
| 4267    | 26        | 3.8%    |
| 6400    | 24        | 3.51%   |
| 1867    | 17        | 2.49%   |
| 1333    | 13        | 1.9%    |
| 1334    | 10        | 1.46%   |
| 5600    | 9         | 1.32%   |
| 1067    | 6         | 0.88%   |
| 667     | 6         | 0.88%   |
| 4266    | 5         | 0.73%   |
| 2666    | 5         | 0.73%   |
| 3733    | 4         | 0.58%   |
| 3266    | 4         | 0.58%   |
| 2048    | 4         | 0.58%   |
| 1066    | 4         | 0.58%   |
| 8400    | 3         | 0.44%   |
| 7500    | 3         | 0.44%   |
| 4199    | 3         | 0.44%   |
| 266     | 2         | 0.29%   |
| Unknown | 2         | 0.29%   |
| 8533    | 1         | 0.15%   |
| 3000    | 1         | 0.15%   |
| 2933    | 1         | 0.15%   |
| 800     | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 60%     |
| Pantum          | 1         | 20%     |
| Canon           | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Pantum P2200W-series      | 1         | 20%     |
| HP Officejet 4500 G510g-m | 1         | 20%     |
| HP LaserJet P1102         | 1         | 20%     |
| HP LaserJet 1020          | 1         | 20%     |
| Canon iP1100 series       | 1         | 20%     |

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
| Chicony Electronics                    | 164       | 20.02%  |
| IMC Networks                           | 139       | 16.97%  |
| Bison Electronics                      | 65        | 7.94%   |
| Microdia                               | 56        | 6.84%   |
| Quanta                                 | 52        | 6.35%   |
| Realtek Semiconductor                  | 49        | 5.98%   |
| Sunplus Innovation Technology          | 47        | 5.74%   |
| Luxvisions Innotech Limited            | 41        | 5.01%   |
| Cheng Uei Precision Industry (Foxlink) | 33        | 4.03%   |
| Syntek                                 | 26        | 3.17%   |
| Acer                                   | 21        | 2.56%   |
| Suyin                                  | 17        | 2.08%   |
| Lite-On Technology                     | 17        | 2.08%   |
| SunplusIT                              | 13        | 1.59%   |
| Apple                                  | 11        | 1.34%   |
| Alcor Micro                            | 10        | 1.22%   |
| Silicon Motion                         | 7         | 0.85%   |
| Lenovo                                 | 6         | 0.73%   |
| Sonix Technology                       | 4         | 0.49%   |
| Ricoh                                  | 4         | 0.49%   |
| icSpring                               | 4         | 0.49%   |
| Logitech                               | 3         | 0.37%   |
| Importek                               | 3         | 0.37%   |
| Z-Star Microelectronics                | 2         | 0.24%   |
| Unknown (0000066029)                   | 2         | 0.24%   |
| ShineTech                              | 2         | 0.24%   |
| Nebraska Furniture Mart                | 2         | 0.24%   |
| GEMBIRD                                | 2         | 0.24%   |
| Y Media                                | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |
| Tripath Technology                     | 1         | 0.12%   |
| SN0002                                 | 1         | 0.12%   |
| ShineOptics                            | 1         | 0.12%   |
| Samsung Electronics                    | 1         | 0.12%   |
| Primax Electronics                     | 1         | 0.12%   |
| Mitsumi                                | 1         | 0.12%   |
| kingcome                               | 1         | 0.12%   |
| Google                                 | 1         | 0.12%   |
| Goodong Industry                       | 1         | 0.12%   |
| Genesys Logic                          | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 73        | 8.88%   |
| IMC Networks Integrated Camera                               | 51        | 6.2%    |
| Microdia Integrated_Webcam_HD                                | 32        | 3.89%   |
| IMC Networks HD Camera                                       | 27        | 3.28%   |
| Bison Integrated Camera                                      | 25        | 3.04%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 21        | 2.55%   |
| Syntek Integrated Camera                                     | 18        | 2.19%   |
| Realtek Integrated_Webcam_HD                                 | 16        | 1.95%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 14        | 1.7%    |
| Luxvisions Innotech Limited Integrated Camera                | 13        | 1.58%   |
| Chicony HD Webcam                                            | 13        | 1.58%   |
| Sunplus XiaoMi USB 2.0 Webcam                                | 12        | 1.46%   |
| IMC Networks ov9734_azurewave_camera                         | 12        | 1.46%   |
| Sunplus Integrated_Webcam_HD                                 | 11        | 1.34%   |
| Luxvisions Innotech Limited Integrated RGB Camera            | 10        | 1.22%   |
| Bison SunplusIT Integrated Camera                            | 10        | 1.22%   |
| Quanta HP HD Camera                                          | 8         | 0.97%   |
| Quanta hm1091_techfront                                      | 8         | 0.97%   |
| Quanta HD User Facing                                        | 8         | 0.97%   |
| Realtek Integrated Webcam                                    | 7         | 0.85%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 7         | 0.85%   |
| Lite-On Integrated Camera                                    | 7         | 0.85%   |
| Chicony XiaoMi USB 2.0 Webcam                                | 7         | 0.85%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                              | 7         | 0.85%   |
| Sunplus HD WebCam                                            | 6         | 0.73%   |
| Quanta ov9734_techfront_camera                               | 6         | 0.73%   |
| IMC Networks Lenovo EasyCamera                               | 6         | 0.73%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 6         | 0.73%   |
| Bison BisonCam,NB Pro                                        | 6         | 0.73%   |
| Acer Integrated Camera                                       | 6         | 0.73%   |
| Syntek Lenovo EasyCamera                                     | 5         | 0.61%   |
| Realtek USB Camera                                           | 5         | 0.61%   |
| Realtek HP Wide Vision HD Camera                             | 5         | 0.61%   |
| Quanta HP Wide Vision HD Camera                              | 5         | 0.61%   |
| Microdia Webcam Vitade AF                                    | 5         | 0.61%   |
| Luxvisions Innotech Limited HP 5MP Camera                    | 5         | 0.61%   |
| Lite-On HP HD Camera                                         | 5         | 0.61%   |
| IMC Networks XHC Camera                                      | 5         | 0.61%   |
| Chicony Integrated Camera (1280x720@30)                      | 5         | 0.61%   |
| Chicony HP Wide Vision HD Camera                             | 5         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 78        | 33.91%  |
| Synaptics                          | 62        | 26.96%  |
| Validity Sensors                   | 50        | 21.74%  |
| Elan Microelectronics              | 14        | 6.09%   |
| Upek                               | 11        | 4.78%   |
| AuthenTec                          | 6         | 2.61%   |
| Focal-systems.Corp                 | 3         | 1.3%    |
| STMicroelectronics                 | 2         | 0.87%   |
| LighTuning Technology              | 2         | 0.87%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.43%   |
| FocalTech                          | 1         | 0.43%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 53        | 23.04%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 11.3%   |
| Shenzhen Goodix Fingerprint Reader                                         | 22        | 9.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 6.09%   |
| Elan ELAN:Fingerprint                                                      | 12        | 5.22%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 4.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 3.48%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 3.04%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 3.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 3.04%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.61%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 2.61%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 2.17%   |
| Synaptics WBDI Device                                                      | 5         | 2.17%   |
| Synaptics UWP WBDI Device                                                  | 4         | 1.74%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 1.74%   |
| AuthenTec AES2810                                                          | 4         | 1.74%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 1.3%    |
| Validity Sensors VFS491                                                    | 3         | 1.3%    |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.3%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 1.3%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.87%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.87%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.87%   |
| Unknown                                                                    | 2         | 0.87%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.43%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.43%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.43%   |
| Synaptics WBDI                                                             | 1         | 0.43%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.43%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.43%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.43%   |
| FocalTech Fingerprint Device                                               | 1         | 0.43%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.43%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 14        | 58.33%  |
| Upek                  | 4         | 16.67%  |
| Clay Logic            | 2         | 8.33%   |
| Alcor Micro           | 2         | 8.33%   |
| Yubico.com            | 1         | 4.17%   |
| Advanced Card Systems | 1         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 5         | 20.83%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 12.5%   |
| Broadcom 58200                                                               | 3         | 12.5%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 8.33%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 4.17%   |
| Advanced Card Systems ACR1581                                                | 1         | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 527       | 53.45%  |
| 1     | 350       | 35.5%   |
| 2     | 85        | 8.62%   |
| 3     | 12        | 1.22%   |
| 4     | 6         | 0.61%   |
| 5     | 4         | 0.41%   |
| 10    | 1         | 0.1%    |
| 8     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 226       | 38.24%  |
| Graphics card            | 152       | 25.72%  |
| Net/wireless             | 49        | 8.29%   |
| Multimedia controller    | 47        | 7.95%   |
| Sound                    | 25        | 4.23%   |
| Camera                   | 22        | 3.72%   |
| Chipcard                 | 20        | 3.38%   |
| Bluetooth                | 16        | 2.71%   |
| Communication controller | 15        | 2.54%   |
| Net/ethernet             | 5         | 0.85%   |
| Card reader              | 4         | 0.68%   |
| Storage                  | 3         | 0.51%   |
| Network                  | 2         | 0.34%   |
| Unassigned class         | 1         | 0.17%   |
| Storage/nvme             | 1         | 0.17%   |
| Storage/ata              | 1         | 0.17%   |
| Modem                    | 1         | 0.17%   |
| Dvb card                 | 1         | 0.17%   |

