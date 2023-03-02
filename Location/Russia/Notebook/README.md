Linux in Russia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Russia.

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

Total: 17518

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | AOHAPPY2                    | [9bbd271b36](https://linux-hardware.org/?probe=9bbd271b36) | Feb 28, 2023 |
| Dell          | G15 5511                    | [1859d13517](https://linux-hardware.org/?probe=1859d13517) | Feb 28, 2023 |
| Clevo         | NL41MU2                     | [29df87f87f](https://linux-hardware.org/?probe=29df87f87f) | Feb 28, 2023 |
| HP            | 255 G2                      | [10397efd1b](https://linux-hardware.org/?probe=10397efd1b) | Feb 28, 2023 |
| Acer          | Aspire A315-59              | [9a897f5d7c](https://linux-hardware.org/?probe=9a897f5d7c) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | [3d003c6d17](https://linux-hardware.org/?probe=3d003c6d17) | Feb 28, 2023 |
| Sony          | VPCZ21Z9R                   | [4d3f0c27cd](https://linux-hardware.org/?probe=4d3f0c27cd) | Feb 28, 2023 |
| Acer          | Aspire A515-45G             | [5f8c1e2d90](https://linux-hardware.org/?probe=5f8c1e2d90) | Feb 28, 2023 |
| HP            | ProBook 430 G1              | [fa75658ee0](https://linux-hardware.org/?probe=fa75658ee0) | Feb 28, 2023 |
| Fujitsu       | LIFEBOOK E744               | [e331c5e257](https://linux-hardware.org/?probe=e331c5e257) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | [e888e1330d](https://linux-hardware.org/?probe=e888e1330d) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | [18fdb45ec1](https://linux-hardware.org/?probe=18fdb45ec1) | Feb 27, 2023 |
| HUAWEI        | BOM-WXX9                    | [43a5dbf393](https://linux-hardware.org/?probe=43a5dbf393) | Feb 27, 2023 |
| Clevo         | NL41MU2                     | [b91dfc602e](https://linux-hardware.org/?probe=b91dfc602e) | Feb 27, 2023 |
| Timi          | RedmiBook Pro 15S           | [109a8e15c4](https://linux-hardware.org/?probe=109a8e15c4) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b116afe451](https://linux-hardware.org/?probe=b116afe451) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d7e55bb97e](https://linux-hardware.org/?probe=d7e55bb97e) | Feb 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7936e7db49](https://linux-hardware.org/?probe=7936e7db49) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| Acer          | Aspire 3690                 | [c93af7d4eb](https://linux-hardware.org/?probe=c93af7d4eb) | Feb 27, 2023 |
| Acer          | Aspire 3690                 | [b119bda1a6](https://linux-hardware.org/?probe=b119bda1a6) | Feb 27, 2023 |
| Sony          | VPCSB2L1R                   | [6ed9bd210d](https://linux-hardware.org/?probe=6ed9bd210d) | Feb 26, 2023 |
| Apple         | MacBookAir7,1               | [2986fb12e2](https://linux-hardware.org/?probe=2986fb12e2) | Feb 26, 2023 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [4c9bfc239a](https://linux-hardware.org/?probe=4c9bfc239a) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [8d8e5bc41d](https://linux-hardware.org/?probe=8d8e5bc41d) | Feb 26, 2023 |
| HP            | 255 G3                      | [49dccf5753](https://linux-hardware.org/?probe=49dccf5753) | Feb 26, 2023 |
| HP            | ProBook 430 G1              | [1354e0b47e](https://linux-hardware.org/?probe=1354e0b47e) | Feb 26, 2023 |
| Acer          | AOHAPPY2                    | [830a1212b7](https://linux-hardware.org/?probe=830a1212b7) | Feb 26, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [da19f23a14](https://linux-hardware.org/?probe=da19f23a14) | Feb 26, 2023 |
| Apple         | MacBookAir7,1               | [05c92ac080](https://linux-hardware.org/?probe=05c92ac080) | Feb 26, 2023 |
| Acer          | Extensa 2519                | [b80f0bc182](https://linux-hardware.org/?probe=b80f0bc182) | Feb 26, 2023 |
| Acer          | Extensa 2519                | [3ee3fea5eb](https://linux-hardware.org/?probe=3ee3fea5eb) | Feb 26, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [848e43f7c3](https://linux-hardware.org/?probe=848e43f7c3) | Feb 26, 2023 |
| Lenovo        | ThinkPad E490 20N8000XRT    | [b9e64d9f86](https://linux-hardware.org/?probe=b9e64d9f86) | Feb 26, 2023 |
| eMachines     | Rhine V1.42                 | [c0c7b48991](https://linux-hardware.org/?probe=c0c7b48991) | Feb 26, 2023 |
| eMachines     | eME728                      | [2331984fc8](https://linux-hardware.org/?probe=2331984fc8) | Feb 26, 2023 |
| Sony          | VPCZ12V9R                   | [3014067c24](https://linux-hardware.org/?probe=3014067c24) | Feb 26, 2023 |
| realme        | RMNBXXXX                    | [6ea10cb77a](https://linux-hardware.org/?probe=6ea10cb77a) | Feb 26, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [7d7953a826](https://linux-hardware.org/?probe=7d7953a826) | Feb 26, 2023 |
| Acer          | Aspire A715-42G             | [c7ef2b6e58](https://linux-hardware.org/?probe=c7ef2b6e58) | Feb 25, 2023 |
| Dell          | Vostro 3501                 | [ed459712f6](https://linux-hardware.org/?probe=ed459712f6) | Feb 25, 2023 |
| Dell          | Latitude 5511               | [4402838fb3](https://linux-hardware.org/?probe=4402838fb3) | Feb 25, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [c5cdb97c5b](https://linux-hardware.org/?probe=c5cdb97c5b) | Feb 25, 2023 |
| HUAWEI        | MACH-WX9                    | [52924074db](https://linux-hardware.org/?probe=52924074db) | Feb 25, 2023 |
| ASUSTek       | N53SM                       | [6606121f31](https://linux-hardware.org/?probe=6606121f31) | Feb 25, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [976a29944a](https://linux-hardware.org/?probe=976a29944a) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a8a2fc9d83](https://linux-hardware.org/?probe=a8a2fc9d83) | Feb 24, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [5ad40efe5c](https://linux-hardware.org/?probe=5ad40efe5c) | Feb 24, 2023 |
| Lenovo        | G50-70 20351                | [8fa16a1dec](https://linux-hardware.org/?probe=8fa16a1dec) | Feb 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | [8a573735cb](https://linux-hardware.org/?probe=8a573735cb) | Feb 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9c0b9ff47a](https://linux-hardware.org/?probe=9c0b9ff47a) | Feb 24, 2023 |
| Samsung       | N150P                       | [662488621d](https://linux-hardware.org/?probe=662488621d) | Feb 24, 2023 |
| Toshiba       | Satellite U300              | [d5973ad69a](https://linux-hardware.org/?probe=d5973ad69a) | Feb 24, 2023 |
| Dell          | G5 5587                     | [1f43871064](https://linux-hardware.org/?probe=1f43871064) | Feb 24, 2023 |
| HP            | ProBook 4545s               | [0f56422e2d](https://linux-hardware.org/?probe=0f56422e2d) | Feb 24, 2023 |
| HUAWEI        | MACH-WX9                    | [fd61d34d74](https://linux-hardware.org/?probe=fd61d34d74) | Feb 23, 2023 |
| Acer          | Aspire ES1-132              | [386da062e2](https://linux-hardware.org/?probe=386da062e2) | Feb 23, 2023 |
| Acer          | AOHAPPY2                    | [a7a5e4b46c](https://linux-hardware.org/?probe=a7a5e4b46c) | Feb 23, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e76bd912f8](https://linux-hardware.org/?probe=e76bd912f8) | Feb 23, 2023 |
| HP            | ProBook 440 G7              | [224a9e7278](https://linux-hardware.org/?probe=224a9e7278) | Feb 23, 2023 |
| HP            | ProBook 440 G7              | [618e46eb82](https://linux-hardware.org/?probe=618e46eb82) | Feb 23, 2023 |
| Dell          | Latitude 7410               | [dfa449b870](https://linux-hardware.org/?probe=dfa449b870) | Feb 23, 2023 |
| ASUSTek       | X541SA                      | [59a1b07ad5](https://linux-hardware.org/?probe=59a1b07ad5) | Feb 23, 2023 |
| Valve         | Jupiter                     | [ed92b67969](https://linux-hardware.org/?probe=ed92b67969) | Feb 22, 2023 |
| 3Logic Gro... | Graviton N15i-K2            | [564ecd80d9](https://linux-hardware.org/?probe=564ecd80d9) | Feb 22, 2023 |
| MSI           | GF63 Thin 9RCX              | [87a9510543](https://linux-hardware.org/?probe=87a9510543) | Feb 22, 2023 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [25c5125cd9](https://linux-hardware.org/?probe=25c5125cd9) | Feb 22, 2023 |
| Acer          | Aspire V3-771               | [c56e36cd0e](https://linux-hardware.org/?probe=c56e36cd0e) | Feb 22, 2023 |
| HP            | ProBook 640 G5              | [e90b71c2fd](https://linux-hardware.org/?probe=e90b71c2fd) | Feb 22, 2023 |
| Kraftway      | ACCORD                      | [8fe15f2f2b](https://linux-hardware.org/?probe=8fe15f2f2b) | Feb 22, 2023 |
| Lenovo        | ThinkPad T520 4242NS9       | [6e2e5c8285](https://linux-hardware.org/?probe=6e2e5c8285) | Feb 22, 2023 |
| Acer          | Aspire ES1-533              | [4a7563bd8e](https://linux-hardware.org/?probe=4a7563bd8e) | Feb 22, 2023 |
| Toshiba       | Satellite A300D             | [fd0d9d5ba1](https://linux-hardware.org/?probe=fd0d9d5ba1) | Feb 22, 2023 |
| Chuwi         | CoreBook XPro               | [c1f8c947d4](https://linux-hardware.org/?probe=c1f8c947d4) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [0e9172bdd5](https://linux-hardware.org/?probe=0e9172bdd5) | Feb 21, 2023 |
| HUAWEI        | CREM-WXX9                   | [643d79fd46](https://linux-hardware.org/?probe=643d79fd46) | Feb 21, 2023 |
| ASUSTek       | X551CAP                     | [1ed860d561](https://linux-hardware.org/?probe=1ed860d561) | Feb 21, 2023 |
| ASUSTek       | X556UQ                      | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [adc356a0a8](https://linux-hardware.org/?probe=adc356a0a8) | Feb 21, 2023 |
| Acer          | Aspire 7736                 | [479496a645](https://linux-hardware.org/?probe=479496a645) | Feb 21, 2023 |
| Acer          | Aspire V5-552PG             | [6030cc4d8a](https://linux-hardware.org/?probe=6030cc4d8a) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [21c2630c57](https://linux-hardware.org/?probe=21c2630c57) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a0faf74325](https://linux-hardware.org/?probe=a0faf74325) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d51436d679](https://linux-hardware.org/?probe=d51436d679) | Feb 21, 2023 |
| Gigabyte      | AORUS 17 XE4                | [b674e3e1e0](https://linux-hardware.org/?probe=b674e3e1e0) | Feb 21, 2023 |
| HUAWEI        | MRGF-XX                     | [1c61370063](https://linux-hardware.org/?probe=1c61370063) | Feb 21, 2023 |
| HP            | ProBook 430 G1              | [1505165a73](https://linux-hardware.org/?probe=1505165a73) | Feb 20, 2023 |
| ASUSTek       | TP300UA                     | [22ff7f5827](https://linux-hardware.org/?probe=22ff7f5827) | Feb 20, 2023 |
| HP            | Pavilion Notebook           | [caff81fa5f](https://linux-hardware.org/?probe=caff81fa5f) | Feb 20, 2023 |
| Apple         | MacBookAir7,1               | [5002433b97](https://linux-hardware.org/?probe=5002433b97) | Feb 20, 2023 |
| Samsung       | N102                        | [736977f523](https://linux-hardware.org/?probe=736977f523) | Feb 20, 2023 |
| Acer          | Extensa 2520G               | [823c5829a9](https://linux-hardware.org/?probe=823c5829a9) | Feb 20, 2023 |
| ASUSTek       | GL703VD                     | [5b0cf6bef1](https://linux-hardware.org/?probe=5b0cf6bef1) | Feb 20, 2023 |
| Haier         | A1410ED                     | [0188ad4a9b](https://linux-hardware.org/?probe=0188ad4a9b) | Feb 20, 2023 |
| Haier         | A1410ED                     | [0551c42cf8](https://linux-hardware.org/?probe=0551c42cf8) | Feb 20, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [e008fd489b](https://linux-hardware.org/?probe=e008fd489b) | Feb 20, 2023 |
| Alienware     | 17                          | [848d5cd7e9](https://linux-hardware.org/?probe=848d5cd7e9) | Feb 20, 2023 |
| DNS           | MB40IA1                     | [9aaf027f52](https://linux-hardware.org/?probe=9aaf027f52) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [c0032d4f0b](https://linux-hardware.org/?probe=c0032d4f0b) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [b1d168b6ce](https://linux-hardware.org/?probe=b1d168b6ce) | Feb 19, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [aa5d23bc20](https://linux-hardware.org/?probe=aa5d23bc20) | Feb 19, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [28e6263489](https://linux-hardware.org/?probe=28e6263489) | Feb 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b27447bfa3](https://linux-hardware.org/?probe=b27447bfa3) | Feb 19, 2023 |
| HP            | Laptop 15s-eq1xxx           | [188489240c](https://linux-hardware.org/?probe=188489240c) | Feb 19, 2023 |
| ASUSTek       | M51Sn                       | [999f32a65f](https://linux-hardware.org/?probe=999f32a65f) | Feb 18, 2023 |
| Lenovo        | B590 20208                  | [59810216a8](https://linux-hardware.org/?probe=59810216a8) | Feb 18, 2023 |
| Lenovo        | Flex 2-14 20404             | [1fc2c6c2f5](https://linux-hardware.org/?probe=1fc2c6c2f5) | Feb 18, 2023 |
| HP            | Notebook                    | [3eff638ead](https://linux-hardware.org/?probe=3eff638ead) | Feb 18, 2023 |
| HUAWEI        | BOM-WXX9                    | [6234395029](https://linux-hardware.org/?probe=6234395029) | Feb 18, 2023 |
| Samsung       | R519/R719                   | [17524cf177](https://linux-hardware.org/?probe=17524cf177) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [f8dd8a7ee9](https://linux-hardware.org/?probe=f8dd8a7ee9) | Feb 18, 2023 |
| Acer          | TravelMate B118-M           | [f70df82711](https://linux-hardware.org/?probe=f70df82711) | Feb 18, 2023 |
| Acer          | Aspire A315-21              | [fe42379585](https://linux-hardware.org/?probe=fe42379585) | Feb 18, 2023 |
| Acer          | AOHAPPY2                    | [1f71a1ad75](https://linux-hardware.org/?probe=1f71a1ad75) | Feb 18, 2023 |
| Unknown       | Unknown                     | [ec840e7d97](https://linux-hardware.org/?probe=ec840e7d97) | Feb 18, 2023 |
| itel Mobil... | SPIRIT 2                    | [8c370ddf38](https://linux-hardware.org/?probe=8c370ddf38) | Feb 17, 2023 |
| Acer          | Aspire 5920G                | [f9000d049e](https://linux-hardware.org/?probe=f9000d049e) | Feb 17, 2023 |
| MSI           | Modern 14 B5M               | [d951f389f3](https://linux-hardware.org/?probe=d951f389f3) | Feb 17, 2023 |
| ASUSTek       | K53SC                       | [df5351b94d](https://linux-hardware.org/?probe=df5351b94d) | Feb 17, 2023 |
| Dell          | Inspiron 5555               | [2051d9e516](https://linux-hardware.org/?probe=2051d9e516) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | [10e9491ee4](https://linux-hardware.org/?probe=10e9491ee4) | Feb 17, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9187251796](https://linux-hardware.org/?probe=9187251796) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | [a3b352975c](https://linux-hardware.org/?probe=a3b352975c) | Feb 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [4d9144193f](https://linux-hardware.org/?probe=4d9144193f) | Feb 17, 2023 |
| Samsung       | R519/R719                   | [1dc4bc1b72](https://linux-hardware.org/?probe=1dc4bc1b72) | Feb 17, 2023 |
| ASUSTek       | X555QG                      | [75924d49a1](https://linux-hardware.org/?probe=75924d49a1) | Feb 16, 2023 |
| HONOR         | BMH-WCX9                    | [c113bd50f3](https://linux-hardware.org/?probe=c113bd50f3) | Feb 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [650a873a5a](https://linux-hardware.org/?probe=650a873a5a) | Feb 16, 2023 |
| Unknown       | Unknown                     | [7d36f8eee5](https://linux-hardware.org/?probe=7d36f8eee5) | Feb 16, 2023 |
| Timi          | RedmiBook Pro 14S           | [5c807c8516](https://linux-hardware.org/?probe=5c807c8516) | Feb 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4b78132251](https://linux-hardware.org/?probe=4b78132251) | Feb 16, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [9de0373acc](https://linux-hardware.org/?probe=9de0373acc) | Feb 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [b30708ce75](https://linux-hardware.org/?probe=b30708ce75) | Feb 15, 2023 |
| ASUSTek       | 1011PX                      | [f0f2625313](https://linux-hardware.org/?probe=f0f2625313) | Feb 15, 2023 |
| HUAWEI        | WRT-WX9                     | [13866e78a2](https://linux-hardware.org/?probe=13866e78a2) | Feb 15, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [b3d3904cef](https://linux-hardware.org/?probe=b3d3904cef) | Feb 15, 2023 |
| Clevo         | NL41MU2                     | [d15806c6c2](https://linux-hardware.org/?probe=d15806c6c2) | Feb 15, 2023 |
| Toshiba       | Satellite U300              | [3925a92635](https://linux-hardware.org/?probe=3925a92635) | Feb 15, 2023 |
| ASUSTek       | K53U                        | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [138839541a](https://linux-hardware.org/?probe=138839541a) | Feb 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [9606f5546e](https://linux-hardware.org/?probe=9606f5546e) | Feb 15, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [e2720c14b7](https://linux-hardware.org/?probe=e2720c14b7) | Feb 15, 2023 |
| HP            | Laptop 15-dw3xxx            | [5dbb939c28](https://linux-hardware.org/?probe=5dbb939c28) | Feb 15, 2023 |
| MSI           | Katana GF66 11SC            | [58fc28f34c](https://linux-hardware.org/?probe=58fc28f34c) | Feb 15, 2023 |
| ASUSTek       | UL30A                       | [90114a4fe4](https://linux-hardware.org/?probe=90114a4fe4) | Feb 14, 2023 |
| HP            | ProBook 440 G7              | [bc4811db07](https://linux-hardware.org/?probe=bc4811db07) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| Valve         | Jupiter                     | [0c496bbe9d](https://linux-hardware.org/?probe=0c496bbe9d) | Feb 14, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [1ebc6ae882](https://linux-hardware.org/?probe=1ebc6ae882) | Feb 14, 2023 |
| Dell          | G3 3579                     | [35c8b69b8c](https://linux-hardware.org/?probe=35c8b69b8c) | Feb 14, 2023 |
| Clevo         | NL41MU2                     | [516a173dcb](https://linux-hardware.org/?probe=516a173dcb) | Feb 14, 2023 |
| ICL           | RAYbook Si1512              | [d1565e917f](https://linux-hardware.org/?probe=d1565e917f) | Feb 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a3b0220b10](https://linux-hardware.org/?probe=a3b0220b10) | Feb 14, 2023 |
| ICL           | RAYbook Si1512              | [aba6ac482b](https://linux-hardware.org/?probe=aba6ac482b) | Feb 14, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [488e3928c6](https://linux-hardware.org/?probe=488e3928c6) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [ac71e5b8ef](https://linux-hardware.org/?probe=ac71e5b8ef) | Feb 14, 2023 |
| Fujitsu       | LIFEBOOK A512               | [92cac1a802](https://linux-hardware.org/?probe=92cac1a802) | Feb 13, 2023 |
| ASUSTek       | GL703VD                     | [409d6e3cb3](https://linux-hardware.org/?probe=409d6e3cb3) | Feb 13, 2023 |
| Unknown       | X133                        | [537237c180](https://linux-hardware.org/?probe=537237c180) | Feb 13, 2023 |
| Acer          | Aspire E5-771G              | [d1abb191dd](https://linux-hardware.org/?probe=d1abb191dd) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [2809288f6f](https://linux-hardware.org/?probe=2809288f6f) | Feb 13, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [c72c5cf640](https://linux-hardware.org/?probe=c72c5cf640) | Feb 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f701208fd4](https://linux-hardware.org/?probe=f701208fd4) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [56ecf82de8](https://linux-hardware.org/?probe=56ecf82de8) | Feb 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [55a63c3dce](https://linux-hardware.org/?probe=55a63c3dce) | Feb 13, 2023 |
| Dell          | Latitude 7490               | [c3f07cbb13](https://linux-hardware.org/?probe=c3f07cbb13) | Feb 13, 2023 |
| ASUSTek       | X556UQ                      | [b2f1a951a1](https://linux-hardware.org/?probe=b2f1a951a1) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [95af064bd1](https://linux-hardware.org/?probe=95af064bd1) | Feb 13, 2023 |
| ASUSTek       | 1011PX                      | [570fd77e58](https://linux-hardware.org/?probe=570fd77e58) | Feb 13, 2023 |
| HP            | ProBook 6470b               | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [3f25b64868](https://linux-hardware.org/?probe=3f25b64868) | Feb 13, 2023 |
| ASUSTek       | X205TA                      | [dfc9ada1af](https://linux-hardware.org/?probe=dfc9ada1af) | Feb 13, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0560a363b8](https://linux-hardware.org/?probe=0560a363b8) | Feb 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [cde8e637d2](https://linux-hardware.org/?probe=cde8e637d2) | Feb 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [a3ac4db738](https://linux-hardware.org/?probe=a3ac4db738) | Feb 12, 2023 |
| Sony          | VPCX11Z6R                   | [ad87a45a26](https://linux-hardware.org/?probe=ad87a45a26) | Feb 12, 2023 |
| HUAWEI        | MRGF-XX                     | [eb1a1cd25b](https://linux-hardware.org/?probe=eb1a1cd25b) | Feb 12, 2023 |
| Haier         | A1410ED                     | [5c90c9c566](https://linux-hardware.org/?probe=5c90c9c566) | Feb 12, 2023 |
| HP            | ProBook 430 G1              | [8d414de313](https://linux-hardware.org/?probe=8d414de313) | Feb 12, 2023 |
| ASUSTek       | N61Jv                       | [4b94eea923](https://linux-hardware.org/?probe=4b94eea923) | Feb 12, 2023 |
| ASUSTek       | N61Jv                       | [15b41bf352](https://linux-hardware.org/?probe=15b41bf352) | Feb 12, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [8f74caf33e](https://linux-hardware.org/?probe=8f74caf33e) | Feb 12, 2023 |
| Lenovo        | G505 20240                  | [eeda09fb13](https://linux-hardware.org/?probe=eeda09fb13) | Feb 12, 2023 |
| ASUSTek       | UX31LA                      | [289ceedf30](https://linux-hardware.org/?probe=289ceedf30) | Feb 12, 2023 |
| ASUSTek       | UX31LA                      | [2c6fb8e625](https://linux-hardware.org/?probe=2c6fb8e625) | Feb 12, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [da4802f871](https://linux-hardware.org/?probe=da4802f871) | Feb 12, 2023 |
| Sony          | SVE14A2V1RWI                | [09509862be](https://linux-hardware.org/?probe=09509862be) | Feb 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [b54b603772](https://linux-hardware.org/?probe=b54b603772) | Feb 12, 2023 |
| Chuwi         | CoreBook X                  | [faf97ec5ac](https://linux-hardware.org/?probe=faf97ec5ac) | Feb 12, 2023 |
| MSI           | Modern 14 B11MOU            | [547c8e5750](https://linux-hardware.org/?probe=547c8e5750) | Feb 12, 2023 |
| Unknown       | Unknown                     | [e28dc371df](https://linux-hardware.org/?probe=e28dc371df) | Feb 12, 2023 |
| Haier         | GG1500A                     | [4c4598157f](https://linux-hardware.org/?probe=4c4598157f) | Feb 12, 2023 |
| Acer          | Aspire 5742G                | [b090683ed1](https://linux-hardware.org/?probe=b090683ed1) | Feb 12, 2023 |
| ASUSTek       | 1025C                       | [a5ae0e6be9](https://linux-hardware.org/?probe=a5ae0e6be9) | Feb 11, 2023 |
| Unknown       | Unknown                     | [e0fd4c1db9](https://linux-hardware.org/?probe=e0fd4c1db9) | Feb 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [b8e6f8a4a9](https://linux-hardware.org/?probe=b8e6f8a4a9) | Feb 11, 2023 |
| HP            | Laptop 15-dw3xxx            | [04f66764c7](https://linux-hardware.org/?probe=04f66764c7) | Feb 11, 2023 |
| HP            | Laptop 14s-dq0xxx           | [2a6b583e08](https://linux-hardware.org/?probe=2a6b583e08) | Feb 11, 2023 |
| MSI           | Alpha 15 A3DDK              | [fc04f9445d](https://linux-hardware.org/?probe=fc04f9445d) | Feb 11, 2023 |
| HP            | Pavilion dv7                | [2f694f36cc](https://linux-hardware.org/?probe=2f694f36cc) | Feb 10, 2023 |
| IBM           | ThinkPad T41 23731HG        | [3f4c1d8c96](https://linux-hardware.org/?probe=3f4c1d8c96) | Feb 10, 2023 |
| ASUSTek       | X75VC                       | [7ae38b7947](https://linux-hardware.org/?probe=7ae38b7947) | Feb 10, 2023 |
| Lenovo        | G70-80 80FF                 | [ade67f432f](https://linux-hardware.org/?probe=ade67f432f) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [09073fcfc8](https://linux-hardware.org/?probe=09073fcfc8) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e2661330b8](https://linux-hardware.org/?probe=e2661330b8) | Feb 10, 2023 |
| HP            | G62                         | [8bc9454fb1](https://linux-hardware.org/?probe=8bc9454fb1) | Feb 10, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5e82ed12a7](https://linux-hardware.org/?probe=5e82ed12a7) | Feb 10, 2023 |
| Valve         | Jupiter                     | [96e636e3b3](https://linux-hardware.org/?probe=96e636e3b3) | Feb 09, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [5da4717c82](https://linux-hardware.org/?probe=5da4717c82) | Feb 09, 2023 |
| Acer          | Aspire V3-771               | [5e29ff0071](https://linux-hardware.org/?probe=5e29ff0071) | Feb 09, 2023 |
| Apple         | MacBook10,1                 | [1d29cd0c56](https://linux-hardware.org/?probe=1d29cd0c56) | Feb 09, 2023 |
| HP            | ENVY 15                     | [ff7562cd96](https://linux-hardware.org/?probe=ff7562cd96) | Feb 09, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [d0f9bc7752](https://linux-hardware.org/?probe=d0f9bc7752) | Feb 09, 2023 |
| Valve         | Jupiter                     | [ce0bad32f4](https://linux-hardware.org/?probe=ce0bad32f4) | Feb 09, 2023 |
| Acer          | Aspire A315-59              | [78d55087bb](https://linux-hardware.org/?probe=78d55087bb) | Feb 08, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [95f88cc4d8](https://linux-hardware.org/?probe=95f88cc4d8) | Feb 08, 2023 |
| HP            | Laptop 15-dw3xxx            | [6a29b69b32](https://linux-hardware.org/?probe=6a29b69b32) | Feb 08, 2023 |
| Notebook      | W65_67SJ                    | [6f4b26218a](https://linux-hardware.org/?probe=6f4b26218a) | Feb 08, 2023 |
| Lenovo        | G50-80 80E5                 | [ea138517da](https://linux-hardware.org/?probe=ea138517da) | Feb 08, 2023 |
| Notebook      | W65_67SJ                    | [1736d50901](https://linux-hardware.org/?probe=1736d50901) | Feb 08, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [3e0851346e](https://linux-hardware.org/?probe=3e0851346e) | Feb 08, 2023 |
| Samsung       | R519/R719                   | [b67d6600ae](https://linux-hardware.org/?probe=b67d6600ae) | Feb 08, 2023 |
| Infinix       | INBOOK X2 GEN11             | [afcd0ead29](https://linux-hardware.org/?probe=afcd0ead29) | Feb 08, 2023 |
| Infinix       | INBOOK X2 GEN11             | [45686da556](https://linux-hardware.org/?probe=45686da556) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [bc2ea675c8](https://linux-hardware.org/?probe=bc2ea675c8) | Feb 08, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [cd84a3ed54](https://linux-hardware.org/?probe=cd84a3ed54) | Feb 08, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [5872694b2c](https://linux-hardware.org/?probe=5872694b2c) | Feb 08, 2023 |
| Toshiba       | Satellite L450              | [5a16ded274](https://linux-hardware.org/?probe=5a16ded274) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c3fd4be797](https://linux-hardware.org/?probe=c3fd4be797) | Feb 08, 2023 |
| Acer          | Aspire A517-51              | [ab27353a60](https://linux-hardware.org/?probe=ab27353a60) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [e58b6f75be](https://linux-hardware.org/?probe=e58b6f75be) | Feb 07, 2023 |
| Dell          | Inspiron 5575               | [1620065d9c](https://linux-hardware.org/?probe=1620065d9c) | Feb 07, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2a21f87922](https://linux-hardware.org/?probe=2a21f87922) | Feb 07, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d3b63de821](https://linux-hardware.org/?probe=d3b63de821) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | [325806b7cc](https://linux-hardware.org/?probe=325806b7cc) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | [870a2912c9](https://linux-hardware.org/?probe=870a2912c9) | Feb 07, 2023 |
| THUNDEROBO... | 911 Plus                    | [63fe672aa8](https://linux-hardware.org/?probe=63fe672aa8) | Feb 07, 2023 |
| Acer          | Aspire E1-570G              | [079f741109](https://linux-hardware.org/?probe=079f741109) | Feb 07, 2023 |
| ASUSTek       | X556UQ                      | [8521058f7c](https://linux-hardware.org/?probe=8521058f7c) | Feb 07, 2023 |
| ASUSTek       | X75VC                       | [d383aec031](https://linux-hardware.org/?probe=d383aec031) | Feb 06, 2023 |
| HUAWEI        | KLVD-WXX9                   | [83d8c56a17](https://linux-hardware.org/?probe=83d8c56a17) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a2172caf56](https://linux-hardware.org/?probe=a2172caf56) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [77faeb6b52](https://linux-hardware.org/?probe=77faeb6b52) | Feb 06, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | [8fb9d5ae65](https://linux-hardware.org/?probe=8fb9d5ae65) | Feb 06, 2023 |
| HONOR         | NBR-WAX9                    | [89ff251118](https://linux-hardware.org/?probe=89ff251118) | Feb 06, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | [ced0a536d0](https://linux-hardware.org/?probe=ced0a536d0) | Feb 06, 2023 |
| Acer          | Aspire E5-573G              | [b0c2be9f04](https://linux-hardware.org/?probe=b0c2be9f04) | Feb 06, 2023 |
| Irbis         | NB143                       | [ab3b895f6e](https://linux-hardware.org/?probe=ab3b895f6e) | Feb 06, 2023 |
| HONOR         | NBR-WAX9                    | [b045a54f0b](https://linux-hardware.org/?probe=b045a54f0b) | Feb 06, 2023 |
| Machcreato... | 14                          | [2fd1f39db5](https://linux-hardware.org/?probe=2fd1f39db5) | Feb 06, 2023 |
| MSI           | Alpha 15 B5EEK              | [47f300cd75](https://linux-hardware.org/?probe=47f300cd75) | Feb 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ebbbcf807a](https://linux-hardware.org/?probe=ebbbcf807a) | Feb 06, 2023 |
| ASUSTek       | X751LD                      | [12d5592082](https://linux-hardware.org/?probe=12d5592082) | Feb 06, 2023 |
| HP            | Pavilion 15                 | [eb37d7677c](https://linux-hardware.org/?probe=eb37d7677c) | Feb 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [bb0481d7a8](https://linux-hardware.org/?probe=bb0481d7a8) | Feb 06, 2023 |
| Aquarius      | NS585                       | [e9deef3f9e](https://linux-hardware.org/?probe=e9deef3f9e) | Feb 06, 2023 |
| HP            | Laptop 17-by3xxx            | [07ea9d3c2f](https://linux-hardware.org/?probe=07ea9d3c2f) | Feb 06, 2023 |
| Dell          | Inspiron N5110              | [9d66ef100a](https://linux-hardware.org/?probe=9d66ef100a) | Feb 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [24a06b8c0c](https://linux-hardware.org/?probe=24a06b8c0c) | Feb 05, 2023 |
| THUNDEROBO... | 911 Plus                    | [bae8523a8a](https://linux-hardware.org/?probe=bae8523a8a) | Feb 05, 2023 |
| Sony          | VPCY11M1R                   | [2de520036a](https://linux-hardware.org/?probe=2de520036a) | Feb 05, 2023 |
| Toshiba       | Satellite A300              | [d9e6b637ca](https://linux-hardware.org/?probe=d9e6b637ca) | Feb 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [69b76f313e](https://linux-hardware.org/?probe=69b76f313e) | Feb 05, 2023 |
| Unknown       | Unknown                     | [a1d5804885](https://linux-hardware.org/?probe=a1d5804885) | Feb 05, 2023 |
| Unknown       | Unknown                     | [73ace1ae6c](https://linux-hardware.org/?probe=73ace1ae6c) | Feb 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5829f2d4a3](https://linux-hardware.org/?probe=5829f2d4a3) | Feb 05, 2023 |
| ASUSTek       | X751LD                      | [13948b75ae](https://linux-hardware.org/?probe=13948b75ae) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [01d18f739c](https://linux-hardware.org/?probe=01d18f739c) | Feb 04, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [3301121a5c](https://linux-hardware.org/?probe=3301121a5c) | Feb 04, 2023 |
| Timi          | A34S                        | [97aed45fe2](https://linux-hardware.org/?probe=97aed45fe2) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | [38cdc2564e](https://linux-hardware.org/?probe=38cdc2564e) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | [8c2a91c204](https://linux-hardware.org/?probe=8c2a91c204) | Feb 04, 2023 |
| Apple         | MacBookPro8,2               | [b5cf758a2a](https://linux-hardware.org/?probe=b5cf758a2a) | Feb 04, 2023 |
| MSI           | Alpha 15 B5EEK              | [b95575866c](https://linux-hardware.org/?probe=b95575866c) | Feb 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b71a6e4da9](https://linux-hardware.org/?probe=b71a6e4da9) | Feb 04, 2023 |
| Timi          | A34S                        | [55208c4210](https://linux-hardware.org/?probe=55208c4210) | Feb 04, 2023 |
| Lenovo        | ThinkPad E490 20N8005TRT    | [d9aca3e679](https://linux-hardware.org/?probe=d9aca3e679) | Feb 04, 2023 |
| ASUSTek       | K52JT                       | [fa36e91793](https://linux-hardware.org/?probe=fa36e91793) | Feb 04, 2023 |
| Acer          | AO756                       | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| Dell          | Inspiron N5040              | [fc65b60f9b](https://linux-hardware.org/?probe=fc65b60f9b) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [fa1e255519](https://linux-hardware.org/?probe=fa1e255519) | Feb 03, 2023 |
| Haier         | GG1500A                     | [b54ce000d3](https://linux-hardware.org/?probe=b54ce000d3) | Feb 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [d7fff6982b](https://linux-hardware.org/?probe=d7fff6982b) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [ada6dd2b76](https://linux-hardware.org/?probe=ada6dd2b76) | Feb 03, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [4608209d2d](https://linux-hardware.org/?probe=4608209d2d) | Feb 03, 2023 |
| MSI           | GP60 2OD                    | [5c91f4e591](https://linux-hardware.org/?probe=5c91f4e591) | Feb 03, 2023 |
| Acer          | Aspire A715-42G             | [0a29f42fab](https://linux-hardware.org/?probe=0a29f42fab) | Feb 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [c26575b761](https://linux-hardware.org/?probe=c26575b761) | Feb 03, 2023 |
| ASUSTek       | UL30A                       | [11885376b2](https://linux-hardware.org/?probe=11885376b2) | Feb 03, 2023 |
| MSI           | GP60 2OD                    | [6820f98769](https://linux-hardware.org/?probe=6820f98769) | Feb 03, 2023 |
| Aquarius      | NS585                       | [7e944d88b3](https://linux-hardware.org/?probe=7e944d88b3) | Feb 03, 2023 |
| Acer          | Aspire 8935G                | [44ab3ebac0](https://linux-hardware.org/?probe=44ab3ebac0) | Feb 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2f2c8adb0c](https://linux-hardware.org/?probe=2f2c8adb0c) | Feb 02, 2023 |
| GPD           | G1619-04                    | [958fa49a0e](https://linux-hardware.org/?probe=958fa49a0e) | Feb 02, 2023 |
| Unknown       | Unknown                     | [473e2a88ed](https://linux-hardware.org/?probe=473e2a88ed) | Feb 02, 2023 |
| Unknown       | Unknown                     | [fcf96d41f6](https://linux-hardware.org/?probe=fcf96d41f6) | Feb 02, 2023 |
| Acer          | Swift SF314-52              | [62ead89718](https://linux-hardware.org/?probe=62ead89718) | Feb 02, 2023 |
| Lenovo        | B590 20206                  | [13608ab0e1](https://linux-hardware.org/?probe=13608ab0e1) | Feb 02, 2023 |
| Lenovo        | G700 20251                  | [2eb468b1b9](https://linux-hardware.org/?probe=2eb468b1b9) | Feb 02, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e49b22de8a](https://linux-hardware.org/?probe=e49b22de8a) | Feb 02, 2023 |
| Acer          | TravelMate P633-M           | [b9bb5f3746](https://linux-hardware.org/?probe=b9bb5f3746) | Feb 02, 2023 |
| ASUSTek       | K50IJ                       | [044d301912](https://linux-hardware.org/?probe=044d301912) | Feb 02, 2023 |
| Unknown       | Unknown                     | [477c99e664](https://linux-hardware.org/?probe=477c99e664) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [159a453649](https://linux-hardware.org/?probe=159a453649) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0538afb301](https://linux-hardware.org/?probe=0538afb301) | Feb 02, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [81e773eade](https://linux-hardware.org/?probe=81e773eade) | Feb 02, 2023 |
| MSI           | MS-N0E1 Ver                 | [9c4dcef9c6](https://linux-hardware.org/?probe=9c4dcef9c6) | Feb 01, 2023 |
| Lenovo        | ThinkPad T490 20N2000LRT    | [aaaf227faf](https://linux-hardware.org/?probe=aaaf227faf) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [eaaf15f3f6](https://linux-hardware.org/?probe=eaaf15f3f6) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [ee219f2f82](https://linux-hardware.org/?probe=ee219f2f82) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [af2f6edc6f](https://linux-hardware.org/?probe=af2f6edc6f) | Feb 01, 2023 |
| ASUSTek       | N552VW                      | [1ebeeec517](https://linux-hardware.org/?probe=1ebeeec517) | Feb 01, 2023 |
| Dell          | Inspiron 5748               | [7ee6505f8d](https://linux-hardware.org/?probe=7ee6505f8d) | Feb 01, 2023 |
| Acer          | Nitro AN515-52              | [86156a3b50](https://linux-hardware.org/?probe=86156a3b50) | Jan 31, 2023 |
| Acer          | Aspire E1-522               | [af61a3d9c8](https://linux-hardware.org/?probe=af61a3d9c8) | Jan 31, 2023 |
| Dell          | Inspiron 5748               | [ecbd4ac8b6](https://linux-hardware.org/?probe=ecbd4ac8b6) | Jan 31, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [7758d7c535](https://linux-hardware.org/?probe=7758d7c535) | Jan 31, 2023 |
| Aquarius      | Cmp NS685U                  | [b067e76e64](https://linux-hardware.org/?probe=b067e76e64) | Jan 31, 2023 |
| Clevo         | NL41MU2                     | [95dac05397](https://linux-hardware.org/?probe=95dac05397) | Jan 31, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [396877a008](https://linux-hardware.org/?probe=396877a008) | Jan 31, 2023 |
| Lenovo        | ThinkPad T410 2518BPG       | [011f53deaa](https://linux-hardware.org/?probe=011f53deaa) | Jan 31, 2023 |
| ASUSTek       | N53Ta                       | [30131c7409](https://linux-hardware.org/?probe=30131c7409) | Jan 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9fd1916420](https://linux-hardware.org/?probe=9fd1916420) | Jan 31, 2023 |
| ASUSTek       | 1011PX                      | [204706229b](https://linux-hardware.org/?probe=204706229b) | Jan 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [318f007db6](https://linux-hardware.org/?probe=318f007db6) | Jan 31, 2023 |
| Acer          | Aspire A517-51              | [cb65ba4ce5](https://linux-hardware.org/?probe=cb65ba4ce5) | Jan 31, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [5201a076f6](https://linux-hardware.org/?probe=5201a076f6) | Jan 30, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [c44c077d1e](https://linux-hardware.org/?probe=c44c077d1e) | Jan 30, 2023 |
| ASUSTek       | X55VD                       | [4120c1019c](https://linux-hardware.org/?probe=4120c1019c) | Jan 30, 2023 |
| MSI           | GL75 Leopard 10SCSR         | [8e30762127](https://linux-hardware.org/?probe=8e30762127) | Jan 30, 2023 |
| HP            | ProBook 4720s               | [b6edbaeae1](https://linux-hardware.org/?probe=b6edbaeae1) | Jan 30, 2023 |
| Infinix       | INBOOK X2 GEN11             | [d826805d37](https://linux-hardware.org/?probe=d826805d37) | Jan 30, 2023 |
| Lenovo        | Z50-70 20354                | [54f6c27c09](https://linux-hardware.org/?probe=54f6c27c09) | Jan 30, 2023 |
| HP            | Pavilion g6                 | [d25ed40cf3](https://linux-hardware.org/?probe=d25ed40cf3) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8a324e4189](https://linux-hardware.org/?probe=8a324e4189) | Jan 30, 2023 |
| HP            | Pavilion dv6                | [0966ae419c](https://linux-hardware.org/?probe=0966ae419c) | Jan 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d800b8a4b9](https://linux-hardware.org/?probe=d800b8a4b9) | Jan 30, 2023 |
| ASUSTek       | 1011PX                      | [7359bcfbfb](https://linux-hardware.org/?probe=7359bcfbfb) | Jan 29, 2023 |
| Sony          | PCG-Z1VA(UC)                | [db4f48132e](https://linux-hardware.org/?probe=db4f48132e) | Jan 29, 2023 |
| Acer          | Nitro AN515-52              | [c8c73a9f67](https://linux-hardware.org/?probe=c8c73a9f67) | Jan 29, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [e3d7c03a2e](https://linux-hardware.org/?probe=e3d7c03a2e) | Jan 29, 2023 |
| Sony          | VPCSB11FX                   | [7659c1ba93](https://linux-hardware.org/?probe=7659c1ba93) | Jan 29, 2023 |
| Unknown       | Unknown                     | [23d04579d4](https://linux-hardware.org/?probe=23d04579d4) | Jan 29, 2023 |
| TECNO         | MEGABOOK T1                 | [db0e6c89b4](https://linux-hardware.org/?probe=db0e6c89b4) | Jan 29, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | [93e0f40842](https://linux-hardware.org/?probe=93e0f40842) | Jan 29, 2023 |
| Acer          | Aspire 3810T                | [a7b93a7119](https://linux-hardware.org/?probe=a7b93a7119) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [87502e1eb2](https://linux-hardware.org/?probe=87502e1eb2) | Jan 29, 2023 |
| Acer          | Nitro AN515-52              | [2fb747792d](https://linux-hardware.org/?probe=2fb747792d) | Jan 29, 2023 |
| HP            | Notebook                    | [d38e078368](https://linux-hardware.org/?probe=d38e078368) | Jan 28, 2023 |
| ASUSTek       | X550MJ                      | [51fd1f6c24](https://linux-hardware.org/?probe=51fd1f6c24) | Jan 28, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [7e6cf30d81](https://linux-hardware.org/?probe=7e6cf30d81) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [85e23fef85](https://linux-hardware.org/?probe=85e23fef85) | Jan 28, 2023 |
| ASUSTek       | ET2321I                     | [dbb162975e](https://linux-hardware.org/?probe=dbb162975e) | Jan 28, 2023 |
| Lenovo        | ThinkPad T450s 20BWS23W0... | [41c82dbadb](https://linux-hardware.org/?probe=41c82dbadb) | Jan 27, 2023 |
| Unknown       | Unknown                     | [b4270378b4](https://linux-hardware.org/?probe=b4270378b4) | Jan 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [376c580dcb](https://linux-hardware.org/?probe=376c580dcb) | Jan 27, 2023 |
| ASUSTek       | N56VJ                       | [6ad6470149](https://linux-hardware.org/?probe=6ad6470149) | Jan 27, 2023 |
| HONOR         | BMH-WCX9                    | [882bb3b505](https://linux-hardware.org/?probe=882bb3b505) | Jan 27, 2023 |
| MSI           | Prestige 14Evo A12M         | [17f4098b36](https://linux-hardware.org/?probe=17f4098b36) | Jan 27, 2023 |
| HP            | ProBook 445 G7              | [d0b5bf560a](https://linux-hardware.org/?probe=d0b5bf560a) | Jan 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [acbaa4516c](https://linux-hardware.org/?probe=acbaa4516c) | Jan 27, 2023 |
| Acer          | Aspire 3810T                | [c77f7df143](https://linux-hardware.org/?probe=c77f7df143) | Jan 27, 2023 |
| Clevo         | M770SUA                     | [3a19bae169](https://linux-hardware.org/?probe=3a19bae169) | Jan 27, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [ff67a5eb33](https://linux-hardware.org/?probe=ff67a5eb33) | Jan 27, 2023 |
| Clevo         | NL41MU2                     | [86e493728f](https://linux-hardware.org/?probe=86e493728f) | Jan 27, 2023 |
| MSI           | Prestige 14Evo A12M         | [3638a1774c](https://linux-hardware.org/?probe=3638a1774c) | Jan 27, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [ecd1e46811](https://linux-hardware.org/?probe=ecd1e46811) | Jan 27, 2023 |
| Lenovo        | G480 20156                  | [9e09139dbc](https://linux-hardware.org/?probe=9e09139dbc) | Jan 26, 2023 |
| ASUSTek       | 1201N                       | [ddc52a086f](https://linux-hardware.org/?probe=ddc52a086f) | Jan 26, 2023 |
| Acer          | Nitro AN515-52              | [02dffce8d7](https://linux-hardware.org/?probe=02dffce8d7) | Jan 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6290f61a46](https://linux-hardware.org/?probe=6290f61a46) | Jan 26, 2023 |
| HONOR         | HLYL-WXX9                   | [00c90b28ca](https://linux-hardware.org/?probe=00c90b28ca) | Jan 26, 2023 |
| Unknown       | Unknown                     | [6ac74fad2b](https://linux-hardware.org/?probe=6ac74fad2b) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [4a3c63f3f0](https://linux-hardware.org/?probe=4a3c63f3f0) | Jan 26, 2023 |
| Infinix       | INBOOK X2 GEN11             | [ee7b9f5fd0](https://linux-hardware.org/?probe=ee7b9f5fd0) | Jan 26, 2023 |
| Clevo         | M815P                       | [cfc5f6689f](https://linux-hardware.org/?probe=cfc5f6689f) | Jan 25, 2023 |
| HP            | EliteBook 840 G4            | [ee6e7a2924](https://linux-hardware.org/?probe=ee6e7a2924) | Jan 25, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [b89ee82de7](https://linux-hardware.org/?probe=b89ee82de7) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [ef947d32a1](https://linux-hardware.org/?probe=ef947d32a1) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [d0a3780add](https://linux-hardware.org/?probe=d0a3780add) | Jan 25, 2023 |
| Lenovo        | V310-15IKB 80T3             | [fe11977488](https://linux-hardware.org/?probe=fe11977488) | Jan 25, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [702b3c77fc](https://linux-hardware.org/?probe=702b3c77fc) | Jan 25, 2023 |
| HP            | Laptop 15-bw0xx             | [c2867457c2](https://linux-hardware.org/?probe=c2867457c2) | Jan 25, 2023 |
| MSI           | GL63 8RC                    | [138e8de541](https://linux-hardware.org/?probe=138e8de541) | Jan 25, 2023 |
| Lenovo        | V310-15IKB 80T3             | [d56d0b1732](https://linux-hardware.org/?probe=d56d0b1732) | Jan 25, 2023 |
| Acer          | Aspire A315-59              | [33292253d0](https://linux-hardware.org/?probe=33292253d0) | Jan 25, 2023 |
| Acer          | Extensa 2540                | [af5b1ea485](https://linux-hardware.org/?probe=af5b1ea485) | Jan 25, 2023 |
| Clevo         | NL41MU2                     | [82e558cf16](https://linux-hardware.org/?probe=82e558cf16) | Jan 25, 2023 |
| Acer          | Aspire 5742G                | [e7afbd79e9](https://linux-hardware.org/?probe=e7afbd79e9) | Jan 24, 2023 |
| realme        | CloudProXXXX                | [520d929687](https://linux-hardware.org/?probe=520d929687) | Jan 24, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [186aef8e0c](https://linux-hardware.org/?probe=186aef8e0c) | Jan 24, 2023 |
| Clevo         | NL41MU2                     | [831e02a268](https://linux-hardware.org/?probe=831e02a268) | Jan 24, 2023 |
| ASUSTek       | A9T                         | [3e313bb71a](https://linux-hardware.org/?probe=3e313bb71a) | Jan 24, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | [3b1ce8fc77](https://linux-hardware.org/?probe=3b1ce8fc77) | Jan 24, 2023 |
| ASUSTek       | A9T                         | [8ed103fd24](https://linux-hardware.org/?probe=8ed103fd24) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [3fb25133ec](https://linux-hardware.org/?probe=3fb25133ec) | Jan 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [56a9b7ad32](https://linux-hardware.org/?probe=56a9b7ad32) | Jan 24, 2023 |
| HUAWEI        | BDZ-WXX9                    | [21f0949826](https://linux-hardware.org/?probe=21f0949826) | Jan 24, 2023 |
| Lenovo        | B560                        | [b474faa82b](https://linux-hardware.org/?probe=b474faa82b) | Jan 23, 2023 |
| ASUSTek       | X51L                        | [b482dc649b](https://linux-hardware.org/?probe=b482dc649b) | Jan 23, 2023 |
| Notebook      | W65_67SH                    | [f80b7fddba](https://linux-hardware.org/?probe=f80b7fddba) | Jan 23, 2023 |
| Lenovo        | ThinkPad X121e 3055A18      | [97ef868fa0](https://linux-hardware.org/?probe=97ef868fa0) | Jan 23, 2023 |
| Lenovo        | ThinkPad X121e 3055A18      | [780e3b2071](https://linux-hardware.org/?probe=780e3b2071) | Jan 23, 2023 |
| realme        | CloudProXXXX                | [e5cbb75254](https://linux-hardware.org/?probe=e5cbb75254) | Jan 23, 2023 |
| HP            | ProBook 6470b               | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [7b3107564a](https://linux-hardware.org/?probe=7b3107564a) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [6b370a283e](https://linux-hardware.org/?probe=6b370a283e) | Jan 23, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [18fdd7a490](https://linux-hardware.org/?probe=18fdd7a490) | Jan 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [5648fbf4a0](https://linux-hardware.org/?probe=5648fbf4a0) | Jan 23, 2023 |
| Valve         | Jupiter                     | [f1553073f5](https://linux-hardware.org/?probe=f1553073f5) | Jan 23, 2023 |
| Samsung       | NC10                        | [6bd13301d9](https://linux-hardware.org/?probe=6bd13301d9) | Jan 22, 2023 |
| HONOR         | NBR-WAX9                    | [cee0f1ccd5](https://linux-hardware.org/?probe=cee0f1ccd5) | Jan 22, 2023 |
| HP            | ProBook 5330m               | [989327864b](https://linux-hardware.org/?probe=989327864b) | Jan 22, 2023 |
| HUAWEI        | HVY-WXX9                    | [e0b75953b9](https://linux-hardware.org/?probe=e0b75953b9) | Jan 22, 2023 |
| ASUSTek       | N56VJ                       | [167dae47d7](https://linux-hardware.org/?probe=167dae47d7) | Jan 22, 2023 |
| Acer          | Aspire E1-530G              | [b4f6567b3f](https://linux-hardware.org/?probe=b4f6567b3f) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 20RD0019RT     | [282161cc92](https://linux-hardware.org/?probe=282161cc92) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 20RD0019RT     | [8d235b1b8d](https://linux-hardware.org/?probe=8d235b1b8d) | Jan 22, 2023 |
| Timi          | TM1701                      | [bec2d3a691](https://linux-hardware.org/?probe=bec2d3a691) | Jan 22, 2023 |
| Lenovo        | ThinkPad L430 2466DS2       | [8be9a889b7](https://linux-hardware.org/?probe=8be9a889b7) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [15b2f3fc5e](https://linux-hardware.org/?probe=15b2f3fc5e) | Jan 22, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d63d494c6](https://linux-hardware.org/?probe=7d63d494c6) | Jan 21, 2023 |
| Samsung       | RV408/RV508                 | [0d5c4881c1](https://linux-hardware.org/?probe=0d5c4881c1) | Jan 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [adeb24c41e](https://linux-hardware.org/?probe=adeb24c41e) | Jan 21, 2023 |
| Acer          | Aspire A515-45G             | [df633f4583](https://linux-hardware.org/?probe=df633f4583) | Jan 21, 2023 |
| Valve         | Jupiter                     | [c464fc36a9](https://linux-hardware.org/?probe=c464fc36a9) | Jan 21, 2023 |
| Toshiba       | Satellite P200              | [cdc37dfe5e](https://linux-hardware.org/?probe=cdc37dfe5e) | Jan 20, 2023 |
| Lenovo        | G505 20240                  | [c591d80181](https://linux-hardware.org/?probe=c591d80181) | Jan 20, 2023 |
| Sony          | VGN-FJ3SR_B                 | [4dc8b8d09d](https://linux-hardware.org/?probe=4dc8b8d09d) | Jan 20, 2023 |
| Lenovo        | B450                        | [96b87672bf](https://linux-hardware.org/?probe=96b87672bf) | Jan 20, 2023 |
| Acer          | Aspire A315-42G             | [ed4c536efa](https://linux-hardware.org/?probe=ed4c536efa) | Jan 20, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [459b2e28d0](https://linux-hardware.org/?probe=459b2e28d0) | Jan 20, 2023 |
| Lenovo        | V130-15IKB 81HN             | [a74a5b3b7b](https://linux-hardware.org/?probe=a74a5b3b7b) | Jan 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8472d89767](https://linux-hardware.org/?probe=8472d89767) | Jan 20, 2023 |
| Acer          | Nitro AN515-52              | [9abd51692e](https://linux-hardware.org/?probe=9abd51692e) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [e04a896c6a](https://linux-hardware.org/?probe=e04a896c6a) | Jan 20, 2023 |
| Blackview     | AceBook 1                   | [ea4db42aa8](https://linux-hardware.org/?probe=ea4db42aa8) | Jan 19, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7d95709d81](https://linux-hardware.org/?probe=7d95709d81) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [20749dc72f](https://linux-hardware.org/?probe=20749dc72f) | Jan 19, 2023 |
| Acer          | Aspire E5-573G              | [cfe663eeb9](https://linux-hardware.org/?probe=cfe663eeb9) | Jan 19, 2023 |
| Notebook      | W65_67SJ                    | [8628d6f752](https://linux-hardware.org/?probe=8628d6f752) | Jan 18, 2023 |
| HP            | ProBook 440 G4              | [43b8eec1e2](https://linux-hardware.org/?probe=43b8eec1e2) | Jan 18, 2023 |
| Chuwi         | HeroBook Pro                | [42bf8b9a0d](https://linux-hardware.org/?probe=42bf8b9a0d) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [82eea2cc7b](https://linux-hardware.org/?probe=82eea2cc7b) | Jan 18, 2023 |
| HP            | ProBook 640 G5              | [095355c9fc](https://linux-hardware.org/?probe=095355c9fc) | Jan 18, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [d27ca45841](https://linux-hardware.org/?probe=d27ca45841) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C660          | [02a6db2951](https://linux-hardware.org/?probe=02a6db2951) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C660          | [a9de8742d5](https://linux-hardware.org/?probe=a9de8742d5) | Jan 17, 2023 |
| Clevo         | NL41MU2                     | [c1c0617217](https://linux-hardware.org/?probe=c1c0617217) | Jan 17, 2023 |
| Acer          | Aspire A315-59              | [469c40ec75](https://linux-hardware.org/?probe=469c40ec75) | Jan 17, 2023 |
| HP            | Laptop 15s-eq1xxx           | [62fc20fe3e](https://linux-hardware.org/?probe=62fc20fe3e) | Jan 17, 2023 |
| HP            | Notebook                    | [a998060574](https://linux-hardware.org/?probe=a998060574) | Jan 17, 2023 |
| Lenovo        | Flex 2-14 20404             | [bdfe91e3c9](https://linux-hardware.org/?probe=bdfe91e3c9) | Jan 17, 2023 |
| Acer          | Nitro AN515-52              | [4507d2f32d](https://linux-hardware.org/?probe=4507d2f32d) | Jan 17, 2023 |
| Acer          | Aspire V3-571G              | [84bce1ebbb](https://linux-hardware.org/?probe=84bce1ebbb) | Jan 17, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [a5ddfa16b9](https://linux-hardware.org/?probe=a5ddfa16b9) | Jan 17, 2023 |
| Acer          | Aspire A315-58              | [7a697f398d](https://linux-hardware.org/?probe=7a697f398d) | Jan 17, 2023 |
| HP            | Laptop 15s-eq1xxx           | [9e3506397c](https://linux-hardware.org/?probe=9e3506397c) | Jan 17, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [13962de59b](https://linux-hardware.org/?probe=13962de59b) | Jan 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [4db3b47f5a](https://linux-hardware.org/?probe=4db3b47f5a) | Jan 16, 2023 |
| Lenovo        | G500 20236                  | [37891c1ea9](https://linux-hardware.org/?probe=37891c1ea9) | Jan 16, 2023 |
| Aquarius      | AQNS685V4                   | [1f0cd980d8](https://linux-hardware.org/?probe=1f0cd980d8) | Jan 16, 2023 |
| ASUSTek       | P43E                        | [2685c35f77](https://linux-hardware.org/?probe=2685c35f77) | Jan 16, 2023 |
| HP            | Laptop 15-db0xxx            | [363f8daa52](https://linux-hardware.org/?probe=363f8daa52) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e1aa5d3186](https://linux-hardware.org/?probe=e1aa5d3186) | Jan 16, 2023 |
| Acer          | Aspire 5625G                | [244d8473fc](https://linux-hardware.org/?probe=244d8473fc) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Unknown       | Unknown                     | [84f591bd6b](https://linux-hardware.org/?probe=84f591bd6b) | Jan 16, 2023 |
| HP            | Notebook                    | [219540f0f7](https://linux-hardware.org/?probe=219540f0f7) | Jan 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2ec1685227](https://linux-hardware.org/?probe=2ec1685227) | Jan 15, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [21c91371cc](https://linux-hardware.org/?probe=21c91371cc) | Jan 15, 2023 |
| Acer          | Aspire V3-772G              | [832efe11f1](https://linux-hardware.org/?probe=832efe11f1) | Jan 15, 2023 |
| eMachines     | eME442                      | [9de636b72e](https://linux-hardware.org/?probe=9de636b72e) | Jan 15, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [63449ba8a3](https://linux-hardware.org/?probe=63449ba8a3) | Jan 15, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [847fab84ee](https://linux-hardware.org/?probe=847fab84ee) | Jan 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bf4ea0ba42](https://linux-hardware.org/?probe=bf4ea0ba42) | Jan 15, 2023 |
| Kraftway      | ACCORD                      | [63039ae17f](https://linux-hardware.org/?probe=63039ae17f) | Jan 15, 2023 |
| Acer          | Aspire A515-43              | [cefbe7ee6e](https://linux-hardware.org/?probe=cefbe7ee6e) | Jan 15, 2023 |
| HP            | ProBook 455 G1              | [8fbd7eb667](https://linux-hardware.org/?probe=8fbd7eb667) | Jan 15, 2023 |
| HP            | 15                          | [6df03629da](https://linux-hardware.org/?probe=6df03629da) | Jan 15, 2023 |
| Toshiba       | Satellite L300              | [282e0e478f](https://linux-hardware.org/?probe=282e0e478f) | Jan 15, 2023 |
| HP            | Pavilion dv6                | [60f339781c](https://linux-hardware.org/?probe=60f339781c) | Jan 14, 2023 |
| HP            | Laptop 15s-eq2xxx           | [52b5182480](https://linux-hardware.org/?probe=52b5182480) | Jan 14, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | [576a509224](https://linux-hardware.org/?probe=576a509224) | Jan 14, 2023 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | [17487f7b28](https://linux-hardware.org/?probe=17487f7b28) | Jan 14, 2023 |
| MSI           | GE62 6QF                    | [5ac082fab9](https://linux-hardware.org/?probe=5ac082fab9) | Jan 14, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | [fd3560384c](https://linux-hardware.org/?probe=fd3560384c) | Jan 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [efffe2d61b](https://linux-hardware.org/?probe=efffe2d61b) | Jan 14, 2023 |
| HP            | Mini 110-3700               | [564cb84405](https://linux-hardware.org/?probe=564cb84405) | Jan 14, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [23f6f87501](https://linux-hardware.org/?probe=23f6f87501) | Jan 14, 2023 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | [a02f812ef3](https://linux-hardware.org/?probe=a02f812ef3) | Jan 14, 2023 |
| Dell          | Inspiron ME051              | [853b489238](https://linux-hardware.org/?probe=853b489238) | Jan 14, 2023 |
| Dell          | Inspiron ME051              | [e806b368b7](https://linux-hardware.org/?probe=e806b368b7) | Jan 14, 2023 |
| Timi          | Redmi Book Pro 14S          | [911075716c](https://linux-hardware.org/?probe=911075716c) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [810b2daeef](https://linux-hardware.org/?probe=810b2daeef) | Jan 13, 2023 |
| Unknown       | Unknown                     | [ce69bfd81b](https://linux-hardware.org/?probe=ce69bfd81b) | Jan 13, 2023 |
| Lenovo        | B560                        | [e5a272b9c1](https://linux-hardware.org/?probe=e5a272b9c1) | Jan 13, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [fbb327effe](https://linux-hardware.org/?probe=fbb327effe) | Jan 12, 2023 |
| Valve         | Jupiter                     | [599dc8d4af](https://linux-hardware.org/?probe=599dc8d4af) | Jan 12, 2023 |
| HP            | Laptop 14s-dq3xxx           | [19be6bae3d](https://linux-hardware.org/?probe=19be6bae3d) | Jan 12, 2023 |
| Dell          | Inspiron 3521               | [694d5be301](https://linux-hardware.org/?probe=694d5be301) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [2316d5dc8b](https://linux-hardware.org/?probe=2316d5dc8b) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c551a35ec7](https://linux-hardware.org/?probe=c551a35ec7) | Jan 12, 2023 |
| DEPO Compu... | DPC156                      | [1cf9823b87](https://linux-hardware.org/?probe=1cf9823b87) | Jan 12, 2023 |
| Acer          | Aspire A315-41G             | [2bfe8a0134](https://linux-hardware.org/?probe=2bfe8a0134) | Jan 12, 2023 |
| Lenovo        | ThinkPad T440p 20AW005BG... | [4e5eb618a2](https://linux-hardware.org/?probe=4e5eb618a2) | Jan 12, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [e607ba7fc4](https://linux-hardware.org/?probe=e607ba7fc4) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [f4d63c1053](https://linux-hardware.org/?probe=f4d63c1053) | Jan 12, 2023 |
| Unknown       | Unknown                     | [5f6b66b79b](https://linux-hardware.org/?probe=5f6b66b79b) | Jan 12, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | [fa0060843c](https://linux-hardware.org/?probe=fa0060843c) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | [2a4a915d05](https://linux-hardware.org/?probe=2a4a915d05) | Jan 11, 2023 |
| HUAWEI        | KLVL-WXXW                   | [1270cfda4e](https://linux-hardware.org/?probe=1270cfda4e) | Jan 11, 2023 |
| Valve         | Jupiter                     | [7e8a3b18b7](https://linux-hardware.org/?probe=7e8a3b18b7) | Jan 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [03b88e9443](https://linux-hardware.org/?probe=03b88e9443) | Jan 11, 2023 |
| Valve         | Jupiter                     | [8955775398](https://linux-hardware.org/?probe=8955775398) | Jan 11, 2023 |
| Acer          | Aspire A315-59              | [a436e3e89f](https://linux-hardware.org/?probe=a436e3e89f) | Jan 11, 2023 |
| Unknown       | Unknown                     | [45ea0a8983](https://linux-hardware.org/?probe=45ea0a8983) | Jan 11, 2023 |
| ASUSTek       | T200TAC                     | [5f39b8c967](https://linux-hardware.org/?probe=5f39b8c967) | Jan 11, 2023 |
| Intel         | Jasper Lake Client Platf... | [3000408196](https://linux-hardware.org/?probe=3000408196) | Jan 11, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [5c4331e8b9](https://linux-hardware.org/?probe=5c4331e8b9) | Jan 11, 2023 |
| Lenovo        | ThinkPad Edge E330 33544... | [d6464d2317](https://linux-hardware.org/?probe=d6464d2317) | Jan 11, 2023 |
| HONOR         | NMH-WCX9                    | [a67f1ee7b0](https://linux-hardware.org/?probe=a67f1ee7b0) | Jan 11, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [a5ea710efd](https://linux-hardware.org/?probe=a5ea710efd) | Jan 11, 2023 |
| Acer          | Aspire ES1-512              | [9d614553aa](https://linux-hardware.org/?probe=9d614553aa) | Jan 11, 2023 |
| Timi          | RedmiBook Pro 15S           | [4eaa490031](https://linux-hardware.org/?probe=4eaa490031) | Jan 11, 2023 |
| MSI           | GP60 2OD                    | [dbd191a73b](https://linux-hardware.org/?probe=dbd191a73b) | Jan 11, 2023 |
| Infinix       | INBOOK X2                   | [11aac46bdc](https://linux-hardware.org/?probe=11aac46bdc) | Jan 10, 2023 |
| Aquarius      | NS585                       | [6fbcdf4d2f](https://linux-hardware.org/?probe=6fbcdf4d2f) | Jan 10, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [8d567b585a](https://linux-hardware.org/?probe=8d567b585a) | Jan 10, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [c4de77365a](https://linux-hardware.org/?probe=c4de77365a) | Jan 10, 2023 |
| MSI           | GE70 2PL                    | [57907f4005](https://linux-hardware.org/?probe=57907f4005) | Jan 10, 2023 |
| Aquarius      | NS585                       | [2d37eb6524](https://linux-hardware.org/?probe=2d37eb6524) | Jan 10, 2023 |
| Lenovo        | ThinkPad E14 20RA0011RT     | [2f2e1a45df](https://linux-hardware.org/?probe=2f2e1a45df) | Jan 10, 2023 |
| ICL           | RAYbook Si1512              | [df6c349ed9](https://linux-hardware.org/?probe=df6c349ed9) | Jan 10, 2023 |
| HUAWEI        | HVY-WXX9                    | [8c86504bdd](https://linux-hardware.org/?probe=8c86504bdd) | Jan 10, 2023 |
| HUAWEI        | HVY-WXX9                    | [ea97a4c5bd](https://linux-hardware.org/?probe=ea97a4c5bd) | Jan 10, 2023 |
| HUAWEI        | KLVD-WXX9                   | [c457f69728](https://linux-hardware.org/?probe=c457f69728) | Jan 10, 2023 |
| HP            | Unknown                     | [63d24f2719](https://linux-hardware.org/?probe=63d24f2719) | Jan 10, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [acab6ec02e](https://linux-hardware.org/?probe=acab6ec02e) | Jan 10, 2023 |
| Acer          | Aspire V3-331               | [b1f637177e](https://linux-hardware.org/?probe=b1f637177e) | Jan 10, 2023 |
| Acer          | Aspire 5733Z                | [87c8f3902d](https://linux-hardware.org/?probe=87c8f3902d) | Jan 10, 2023 |
| ASUSTek       | FX503VD                     | [c3a958527e](https://linux-hardware.org/?probe=c3a958527e) | Jan 10, 2023 |
| HP            | ProBook 4520s               | [8e1eba4ad4](https://linux-hardware.org/?probe=8e1eba4ad4) | Jan 09, 2023 |
| Lenovo        | S10-3                       | [ea711c1ded](https://linux-hardware.org/?probe=ea711c1ded) | Jan 09, 2023 |
| Samsung       | RV420/RV520/RV720           | [c0697ead47](https://linux-hardware.org/?probe=c0697ead47) | Jan 09, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [930ac46758](https://linux-hardware.org/?probe=930ac46758) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b994b522e6](https://linux-hardware.org/?probe=b994b522e6) | Jan 09, 2023 |
| Acer          | Aspire 5755G                | [f6ecd5ed6e](https://linux-hardware.org/?probe=f6ecd5ed6e) | Jan 09, 2023 |
| ASUSTek       | K54L                        | [88b71478e6](https://linux-hardware.org/?probe=88b71478e6) | Jan 09, 2023 |
| ASUSTek       | K61IC                       | [c593968311](https://linux-hardware.org/?probe=c593968311) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1829eed17a](https://linux-hardware.org/?probe=1829eed17a) | Jan 09, 2023 |
| MSI           | GV72 8RD                    | [5fa5d4ef58](https://linux-hardware.org/?probe=5fa5d4ef58) | Jan 09, 2023 |
| MSI           | Modern 14 B11MOU            | [0db2c1a27c](https://linux-hardware.org/?probe=0db2c1a27c) | Jan 09, 2023 |
| Acer          | TravelMate P278-M           | [6b2be0a8cc](https://linux-hardware.org/?probe=6b2be0a8cc) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e85e91a7f2](https://linux-hardware.org/?probe=e85e91a7f2) | Jan 09, 2023 |
| ASUSTek       | K95VB                       | [f42992ef2a](https://linux-hardware.org/?probe=f42992ef2a) | Jan 09, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [71bd754745](https://linux-hardware.org/?probe=71bd754745) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [364cc4a06d](https://linux-hardware.org/?probe=364cc4a06d) | Jan 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [4e7429ebbf](https://linux-hardware.org/?probe=4e7429ebbf) | Jan 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b6e56e8d87](https://linux-hardware.org/?probe=b6e56e8d87) | Jan 08, 2023 |
| Acer          | Aspire ES1-311              | [6f857b7e85](https://linux-hardware.org/?probe=6f857b7e85) | Jan 08, 2023 |
| Infinix       | INBOOK X2 GEN11             | [a899026279](https://linux-hardware.org/?probe=a899026279) | Jan 08, 2023 |
| Jumper        | EZpad                       | [b42f4266ff](https://linux-hardware.org/?probe=b42f4266ff) | Jan 08, 2023 |
| Notebook      | W65_67SH                    | [09761dd51c](https://linux-hardware.org/?probe=09761dd51c) | Jan 08, 2023 |
| ASUSTek       | X541UVK                     | [50e9caee7f](https://linux-hardware.org/?probe=50e9caee7f) | Jan 08, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [66ba6bf6d3](https://linux-hardware.org/?probe=66ba6bf6d3) | Jan 08, 2023 |
| Dell          | Inspiron 3793               | [67be2bc16f](https://linux-hardware.org/?probe=67be2bc16f) | Jan 08, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [7a02a3b48b](https://linux-hardware.org/?probe=7a02a3b48b) | Jan 08, 2023 |
| Dell          | Latitude 5490               | [8fd07b1457](https://linux-hardware.org/?probe=8fd07b1457) | Jan 08, 2023 |
| HUAWEI        | BOM-WXX9                    | [21fcd391f1](https://linux-hardware.org/?probe=21fcd391f1) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [d32518b04e](https://linux-hardware.org/?probe=d32518b04e) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [5936a203cc](https://linux-hardware.org/?probe=5936a203cc) | Jan 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7b3bed98d](https://linux-hardware.org/?probe=d7b3bed98d) | Jan 08, 2023 |
| ASUSTek       | 1003HAG                     | [0b411dbd38](https://linux-hardware.org/?probe=0b411dbd38) | Jan 08, 2023 |
| Digma         | Pro Fortis M DN15P3-8CXN... | [077fd44029](https://linux-hardware.org/?probe=077fd44029) | Jan 08, 2023 |
| Lenovo        | B590 20208                  | [e082e7aece](https://linux-hardware.org/?probe=e082e7aece) | Jan 07, 2023 |
| Acer          | Aspire ES1-572              | [dbbd130a08](https://linux-hardware.org/?probe=dbbd130a08) | Jan 07, 2023 |
| Intel         | Jasper Lake Client Platf... | [24fef9e401](https://linux-hardware.org/?probe=24fef9e401) | Jan 07, 2023 |
| Acer          | Aspire V3-551G              | [adfe7169cc](https://linux-hardware.org/?probe=adfe7169cc) | Jan 07, 2023 |
| Acer          | Nitro AN515-54              | [0336238a86](https://linux-hardware.org/?probe=0336238a86) | Jan 07, 2023 |
| ASUSTek       | 1003HAG                     | [eb8e81a088](https://linux-hardware.org/?probe=eb8e81a088) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | [57ec88a87b](https://linux-hardware.org/?probe=57ec88a87b) | Jan 07, 2023 |
| Lenovo        | ThinkPad E590 20NB001BGE    | [44d45b8178](https://linux-hardware.org/?probe=44d45b8178) | Jan 06, 2023 |
| Sony          | SVS1512U1RW                 | [c5de402a7c](https://linux-hardware.org/?probe=c5de402a7c) | Jan 06, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAA... | [7892dbaa3d](https://linux-hardware.org/?probe=7892dbaa3d) | Jan 06, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [9655429e71](https://linux-hardware.org/?probe=9655429e71) | Jan 06, 2023 |
| HP            | Compaq 515                  | [6cc60c3d13](https://linux-hardware.org/?probe=6cc60c3d13) | Jan 06, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Acer          | Nitro AN515-44              | [1b36fc58ae](https://linux-hardware.org/?probe=1b36fc58ae) | Jan 05, 2023 |
| Chuwi         | CoreBook X                  | [bf8c10bdca](https://linux-hardware.org/?probe=bf8c10bdca) | Jan 05, 2023 |
| Dell          | G7 7790                     | [ffaafd92cf](https://linux-hardware.org/?probe=ffaafd92cf) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [2cb5d2f306](https://linux-hardware.org/?probe=2cb5d2f306) | Jan 05, 2023 |
| Maibenben     | MaiBook M                   | [6b475a50fc](https://linux-hardware.org/?probe=6b475a50fc) | Jan 05, 2023 |
| Acer          | Extensa 2540                | [4442f2c14a](https://linux-hardware.org/?probe=4442f2c14a) | Jan 05, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [729add189b](https://linux-hardware.org/?probe=729add189b) | Jan 05, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c2df57a53f](https://linux-hardware.org/?probe=c2df57a53f) | Jan 05, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [5be962cfea](https://linux-hardware.org/?probe=5be962cfea) | Jan 05, 2023 |
| HP            | ProBook 640 G1              | [e3fd4121a2](https://linux-hardware.org/?probe=e3fd4121a2) | Jan 04, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [343d0f4c48](https://linux-hardware.org/?probe=343d0f4c48) | Jan 04, 2023 |
| Acer          | Extensa 2540                | [ec8b49d7b0](https://linux-hardware.org/?probe=ec8b49d7b0) | Jan 04, 2023 |
| HUAWEI        | BOM-WXX9                    | [f4631a1285](https://linux-hardware.org/?probe=f4631a1285) | Jan 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [e06b51ae0a](https://linux-hardware.org/?probe=e06b51ae0a) | Jan 04, 2023 |
| Acer          | Aspire A515-51G             | [628e5fab6a](https://linux-hardware.org/?probe=628e5fab6a) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [272d23ec5d](https://linux-hardware.org/?probe=272d23ec5d) | Jan 04, 2023 |
| Acer          | Swift SF114-32              | [50315135d2](https://linux-hardware.org/?probe=50315135d2) | Jan 04, 2023 |
| Acer          | Aspire A315-59              | [c166af4a6a](https://linux-hardware.org/?probe=c166af4a6a) | Jan 04, 2023 |
| Infinix       | INBOOK X2 GEN11             | [0cef66e1f2](https://linux-hardware.org/?probe=0cef66e1f2) | Jan 04, 2023 |
| Acer          | Aspire A315-59              | [427a19e69c](https://linux-hardware.org/?probe=427a19e69c) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [ed8c1ab25e](https://linux-hardware.org/?probe=ed8c1ab25e) | Jan 04, 2023 |
| HP            | Pavilion 15                 | [9cf74b665b](https://linux-hardware.org/?probe=9cf74b665b) | Jan 04, 2023 |
| HP            | Pavilion 15                 | [c33e367298](https://linux-hardware.org/?probe=c33e367298) | Jan 04, 2023 |
| Dell          | Inspiron 1525               | [c3c074f183](https://linux-hardware.org/?probe=c3c074f183) | Jan 03, 2023 |
| ASUSTek       | X510UNR                     | [5ac1da09ba](https://linux-hardware.org/?probe=5ac1da09ba) | Jan 03, 2023 |
| Acer          | Aspire 5738                 | [aa99474aec](https://linux-hardware.org/?probe=aa99474aec) | Jan 03, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ac3df6f289](https://linux-hardware.org/?probe=ac3df6f289) | Jan 03, 2023 |
| Dell          | Inspiron 7577               | [437194cbc0](https://linux-hardware.org/?probe=437194cbc0) | Jan 03, 2023 |
| Unknown       | Unknown                     | [dba4431951](https://linux-hardware.org/?probe=dba4431951) | Jan 03, 2023 |
| Clevo         | M815P                       | [7f1503c5e6](https://linux-hardware.org/?probe=7f1503c5e6) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | [d788f444ff](https://linux-hardware.org/?probe=d788f444ff) | Jan 03, 2023 |
| Gigabyte      | G5 KD                       | [b86543e8cf](https://linux-hardware.org/?probe=b86543e8cf) | Jan 03, 2023 |
| Acer          | Aspire 5349                 | [b482fc96ea](https://linux-hardware.org/?probe=b482fc96ea) | Jan 03, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [63a14c970b](https://linux-hardware.org/?probe=63a14c970b) | Jan 03, 2023 |
| HUAWEI        | BOD-WXX9                    | [34ce85079c](https://linux-hardware.org/?probe=34ce85079c) | Jan 03, 2023 |
| HUAWEI        | BOD-WXX9                    | [69dd532d74](https://linux-hardware.org/?probe=69dd532d74) | Jan 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8eef31a350](https://linux-hardware.org/?probe=8eef31a350) | Jan 03, 2023 |
| Dell          | Latitude 7410               | [3dadd543f1](https://linux-hardware.org/?probe=3dadd543f1) | Jan 03, 2023 |
| MSI           | Raider GE76 12UGS           | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAA... | [3f6f3dd3fe](https://linux-hardware.org/?probe=3f6f3dd3fe) | Jan 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4842e4b3e5](https://linux-hardware.org/?probe=4842e4b3e5) | Jan 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [70c50fe035](https://linux-hardware.org/?probe=70c50fe035) | Jan 02, 2023 |
| Clevo         | M815P                       | [034cecc238](https://linux-hardware.org/?probe=034cecc238) | Jan 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a959b07b66](https://linux-hardware.org/?probe=a959b07b66) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [8d4934bc09](https://linux-hardware.org/?probe=8d4934bc09) | Jan 02, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [daeb060f32](https://linux-hardware.org/?probe=daeb060f32) | Jan 02, 2023 |
| Unknown       | Unknown                     | [e4608bbed6](https://linux-hardware.org/?probe=e4608bbed6) | Jan 02, 2023 |
| Acer          | Aspire A315-59              | [f84116ec07](https://linux-hardware.org/?probe=f84116ec07) | Jan 01, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [fbf89f7693](https://linux-hardware.org/?probe=fbf89f7693) | Jan 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5a95ae3186](https://linux-hardware.org/?probe=5a95ae3186) | Jan 01, 2023 |
| Fujitsu       | LIFEBOOK U749               | [c09072c09f](https://linux-hardware.org/?probe=c09072c09f) | Jan 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [322cf5484d](https://linux-hardware.org/?probe=322cf5484d) | Dec 31, 2022 |
| ASUSTek       | X540YA                      | [37ef421251](https://linux-hardware.org/?probe=37ef421251) | Dec 31, 2022 |
| Lenovo        | G780 20138                  | [896aeb4e20](https://linux-hardware.org/?probe=896aeb4e20) | Dec 31, 2022 |
| Dell          | Inspiron 15-3552            | [e8b804ddd5](https://linux-hardware.org/?probe=e8b804ddd5) | Dec 31, 2022 |
| Valve         | Jupiter                     | [61cb7375d1](https://linux-hardware.org/?probe=61cb7375d1) | Dec 31, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | [14b589709d](https://linux-hardware.org/?probe=14b589709d) | Dec 31, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [f7ed4a6609](https://linux-hardware.org/?probe=f7ed4a6609) | Dec 30, 2022 |
| Timi          | A35S                        | [c62c9ae956](https://linux-hardware.org/?probe=c62c9ae956) | Dec 30, 2022 |
| HP            | Pavilion g6                 | [6f29ccd86e](https://linux-hardware.org/?probe=6f29ccd86e) | Dec 30, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [5b5e0e4535](https://linux-hardware.org/?probe=5b5e0e4535) | Dec 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5710b93654](https://linux-hardware.org/?probe=5710b93654) | Dec 30, 2022 |
| Dell          | Inspiron 5490               | [c8a80649d2](https://linux-hardware.org/?probe=c8a80649d2) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2d63537d23](https://linux-hardware.org/?probe=2d63537d23) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [41da11b027](https://linux-hardware.org/?probe=41da11b027) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [954fdfcd25](https://linux-hardware.org/?probe=954fdfcd25) | Dec 30, 2022 |
| Unknown       | Unknown                     | [b74128543f](https://linux-hardware.org/?probe=b74128543f) | Dec 29, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [3f4178001d](https://linux-hardware.org/?probe=3f4178001d) | Dec 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [6c836dde26](https://linux-hardware.org/?probe=6c836dde26) | Dec 29, 2022 |
| MACHCREATO... | AB                          | [52a6beb872](https://linux-hardware.org/?probe=52a6beb872) | Dec 29, 2022 |
| Timi          | RedmiBook Pro 15S           | [42640b7b6e](https://linux-hardware.org/?probe=42640b7b6e) | Dec 29, 2022 |
| Timi          | RedmiBook Pro 15S           | [16c240a462](https://linux-hardware.org/?probe=16c240a462) | Dec 29, 2022 |
| Prestigio     | PSB141C04CGH                | [591f91b689](https://linux-hardware.org/?probe=591f91b689) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [3c627bc707](https://linux-hardware.org/?probe=3c627bc707) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [b246257695](https://linux-hardware.org/?probe=b246257695) | Dec 29, 2022 |
| HUAWEI        | BOM-WXX9                    | [fb1d454bc2](https://linux-hardware.org/?probe=fb1d454bc2) | Dec 29, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [83acd419e0](https://linux-hardware.org/?probe=83acd419e0) | Dec 29, 2022 |
| HUAWEI        | BOM-WXX9                    | [62010fe267](https://linux-hardware.org/?probe=62010fe267) | Dec 29, 2022 |
| ASUSTek       | N551JM                      | [932615a484](https://linux-hardware.org/?probe=932615a484) | Dec 29, 2022 |
| ASUSTek       | K40IN                       | [1b4a2d0604](https://linux-hardware.org/?probe=1b4a2d0604) | Dec 29, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a05251fd39](https://linux-hardware.org/?probe=a05251fd39) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [fe79eba13b](https://linux-hardware.org/?probe=fe79eba13b) | Dec 29, 2022 |
| Aquarius      | NS685U R11                  | [d99ae12a0c](https://linux-hardware.org/?probe=d99ae12a0c) | Dec 29, 2022 |
| Lenovo        | V560                        | [f937de4c61](https://linux-hardware.org/?probe=f937de4c61) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Lenovo        | V14-IIL 82C4                | [221e9b9fd6](https://linux-hardware.org/?probe=221e9b9fd6) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Clevo         | NL41MU2                     | [6aaaf2e570](https://linux-hardware.org/?probe=6aaaf2e570) | Dec 28, 2022 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | [0852995abb](https://linux-hardware.org/?probe=0852995abb) | Dec 28, 2022 |
| DEPO Compu... | DPC156                      | [b49fe3beb3](https://linux-hardware.org/?probe=b49fe3beb3) | Dec 28, 2022 |
| HUAWEI        | HLYL-WXX9                   | [790b3dcdde](https://linux-hardware.org/?probe=790b3dcdde) | Dec 28, 2022 |
| Lenovo        | ThinkPad T430 23448AG       | [00ba06cfd1](https://linux-hardware.org/?probe=00ba06cfd1) | Dec 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e36e85614e](https://linux-hardware.org/?probe=e36e85614e) | Dec 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [b62b4d2134](https://linux-hardware.org/?probe=b62b4d2134) | Dec 27, 2022 |
| MSI           | GL63 8RC                    | [0b973e252f](https://linux-hardware.org/?probe=0b973e252f) | Dec 27, 2022 |
| Toshiba       | Satellite U300              | [88861461c8](https://linux-hardware.org/?probe=88861461c8) | Dec 27, 2022 |
| Lenovo        | ThinkPad T430 23448AG       | [a570034bbc](https://linux-hardware.org/?probe=a570034bbc) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [942fbb1ccb](https://linux-hardware.org/?probe=942fbb1ccb) | Dec 27, 2022 |
| HP            | Compaq Presario CQ50        | [802e160a5a](https://linux-hardware.org/?probe=802e160a5a) | Dec 27, 2022 |
| Lenovo        | V14-IIL 82C4                | [2b7f53c989](https://linux-hardware.org/?probe=2b7f53c989) | Dec 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [155c738d10](https://linux-hardware.org/?probe=155c738d10) | Dec 27, 2022 |
| ASUSTek       | K43E                        | [530e44f9c6](https://linux-hardware.org/?probe=530e44f9c6) | Dec 27, 2022 |
| Unknown       | Unknown                     | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [4d7e3586e2](https://linux-hardware.org/?probe=4d7e3586e2) | Dec 27, 2022 |
| MACHENIKE     | Machcreator-16              | [682c068af0](https://linux-hardware.org/?probe=682c068af0) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [0c71831ff4](https://linux-hardware.org/?probe=0c71831ff4) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [50c31f6b47](https://linux-hardware.org/?probe=50c31f6b47) | Dec 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [292ef79b8a](https://linux-hardware.org/?probe=292ef79b8a) | Dec 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [cedce58f23](https://linux-hardware.org/?probe=cedce58f23) | Dec 27, 2022 |
| HONOR         | BMH-WCX9                    | [815525e6d2](https://linux-hardware.org/?probe=815525e6d2) | Dec 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0e063e5fd5](https://linux-hardware.org/?probe=0e063e5fd5) | Dec 27, 2022 |
| Gigabyte      | i1520N                      | [4f94938d1b](https://linux-hardware.org/?probe=4f94938d1b) | Dec 27, 2022 |
| MSI           | Modern 14 B4MW              | [17bd139f0c](https://linux-hardware.org/?probe=17bd139f0c) | Dec 26, 2022 |
| Digma         | CITI E401 ET4007EW          | [252a51f201](https://linux-hardware.org/?probe=252a51f201) | Dec 26, 2022 |
| Timi          | A18R                        | [83f858038d](https://linux-hardware.org/?probe=83f858038d) | Dec 26, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [0a5cad12c2](https://linux-hardware.org/?probe=0a5cad12c2) | Dec 26, 2022 |
| ASUSTek       | N56VZ                       | [1ba62f0fab](https://linux-hardware.org/?probe=1ba62f0fab) | Dec 26, 2022 |
| Dell          | G5 5590                     | [43fbc3b36d](https://linux-hardware.org/?probe=43fbc3b36d) | Dec 26, 2022 |
| Clevo         | NL41MU2                     | [190bb1537d](https://linux-hardware.org/?probe=190bb1537d) | Dec 26, 2022 |
| Clevo         | NL41MU2                     | [0574ad6c44](https://linux-hardware.org/?probe=0574ad6c44) | Dec 26, 2022 |
| HUAWEI        | NBD-WXX9                    | [713b103493](https://linux-hardware.org/?probe=713b103493) | Dec 25, 2022 |
| HP            | 470 G8 Notebook PC          | [6d77c48324](https://linux-hardware.org/?probe=6d77c48324) | Dec 25, 2022 |
| Acer          | Acadia V1.45                | [2d98a8cef2](https://linux-hardware.org/?probe=2d98a8cef2) | Dec 25, 2022 |
| Unknown       | Unknown                     | [8f4d031a78](https://linux-hardware.org/?probe=8f4d031a78) | Dec 25, 2022 |
| LTD Delovo... | 15Y                         | [286aa3fb96](https://linux-hardware.org/?probe=286aa3fb96) | Dec 25, 2022 |
| Pegatron      | C15B                        | [f838b3f22c](https://linux-hardware.org/?probe=f838b3f22c) | Dec 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [649291f277](https://linux-hardware.org/?probe=649291f277) | Dec 25, 2022 |
| Acer          | Nitro AN515-52              | [1571f74238](https://linux-hardware.org/?probe=1571f74238) | Dec 25, 2022 |
| Unknown       | Unknown                     | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| ASUSTek       | X551CAP                     | [3442037418](https://linux-hardware.org/?probe=3442037418) | Dec 25, 2022 |
| ASUSTek       | M51Tr                       | [dffa412a98](https://linux-hardware.org/?probe=dffa412a98) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [ea09a6daa8](https://linux-hardware.org/?probe=ea09a6daa8) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [45737153e4](https://linux-hardware.org/?probe=45737153e4) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| Dell          | G7 7790                     | [da767d5fd4](https://linux-hardware.org/?probe=da767d5fd4) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Acer          | Aspire V3-551G              | [6adf185edf](https://linux-hardware.org/?probe=6adf185edf) | Dec 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [8c835888d6](https://linux-hardware.org/?probe=8c835888d6) | Dec 24, 2022 |
| HP            | EliteBook Folio 1040 G3     | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Acer          | Aspire A315-21G             | [435933801a](https://linux-hardware.org/?probe=435933801a) | Dec 24, 2022 |
| HP            | Notebook                    | [10dfda9549](https://linux-hardware.org/?probe=10dfda9549) | Dec 24, 2022 |
| Toshiba       | Satellite C55-A             | [02a3f1cf18](https://linux-hardware.org/?probe=02a3f1cf18) | Dec 24, 2022 |
| Acer          | Aspire VX5-591G             | [f2e0369ba1](https://linux-hardware.org/?probe=f2e0369ba1) | Dec 24, 2022 |
| Dell          | Vostro 5490                 | [f694fa24c8](https://linux-hardware.org/?probe=f694fa24c8) | Dec 23, 2022 |
| Lenovo        | G505s 20255                 | [2a0fc9ecc3](https://linux-hardware.org/?probe=2a0fc9ecc3) | Dec 23, 2022 |
| Intel         | ChiefRiver                  | [a23ea2e43e](https://linux-hardware.org/?probe=a23ea2e43e) | Dec 23, 2022 |
| Clevo         | NL41MU2                     | [f9b6dc975b](https://linux-hardware.org/?probe=f9b6dc975b) | Dec 23, 2022 |
| Unknown       | Unknown                     | [5e4cb87810](https://linux-hardware.org/?probe=5e4cb87810) | Dec 23, 2022 |
| HP            | Laptop 15-db0xxx            | [3e269dcad0](https://linux-hardware.org/?probe=3e269dcad0) | Dec 23, 2022 |
| Dell          | Inspiron 5490               | [1c424b5f55](https://linux-hardware.org/?probe=1c424b5f55) | Dec 23, 2022 |
| HP            | Laptop 15-db0xxx            | [27f289cf57](https://linux-hardware.org/?probe=27f289cf57) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [5ce0dacccf](https://linux-hardware.org/?probe=5ce0dacccf) | Dec 23, 2022 |
| Unknown       | Unknown                     | [c9637c2acf](https://linux-hardware.org/?probe=c9637c2acf) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [451f22ab12](https://linux-hardware.org/?probe=451f22ab12) | Dec 22, 2022 |
| ASUSTek       | M51Vr                       | [ffc48a52ea](https://linux-hardware.org/?probe=ffc48a52ea) | Dec 22, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [672c320794](https://linux-hardware.org/?probe=672c320794) | Dec 22, 2022 |
| HP            | G62                         | [00b47da7dc](https://linux-hardware.org/?probe=00b47da7dc) | Dec 22, 2022 |
| Lenovo        | G700 20251                  | [1a8f388366](https://linux-hardware.org/?probe=1a8f388366) | Dec 22, 2022 |
| Toshiba       | Satellite A300              | [8981102ebe](https://linux-hardware.org/?probe=8981102ebe) | Dec 22, 2022 |
| HP            | ProBook 440 G4              | [c93f96de9e](https://linux-hardware.org/?probe=c93f96de9e) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [677cb5b0b3](https://linux-hardware.org/?probe=677cb5b0b3) | Dec 22, 2022 |
| HP            | ProBook 440 G6              | [ad317dc4fd](https://linux-hardware.org/?probe=ad317dc4fd) | Dec 22, 2022 |
| Lenovo        | ThinkPad E490 20N80019RT    | [87746a4f6c](https://linux-hardware.org/?probe=87746a4f6c) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [5f132c928b](https://linux-hardware.org/?probe=5f132c928b) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [95b8e650ce](https://linux-hardware.org/?probe=95b8e650ce) | Dec 21, 2022 |
| Lenovo        | G700 20251                  | [afac6a5bfa](https://linux-hardware.org/?probe=afac6a5bfa) | Dec 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [5262e622da](https://linux-hardware.org/?probe=5262e622da) | Dec 21, 2022 |
| MSI           | Alpha 15 B5EEK              | [d6e55e247a](https://linux-hardware.org/?probe=d6e55e247a) | Dec 21, 2022 |
| HP            | EliteBook Folio 1040 G3     | [3d89cf5c71](https://linux-hardware.org/?probe=3d89cf5c71) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [cc485cc076](https://linux-hardware.org/?probe=cc485cc076) | Dec 21, 2022 |
| eMachines     | E525                        | [8368666118](https://linux-hardware.org/?probe=8368666118) | Dec 21, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [127d74a6ea](https://linux-hardware.org/?probe=127d74a6ea) | Dec 21, 2022 |
| ASUSTek       | X555SJ                      | [c580c82fe2](https://linux-hardware.org/?probe=c580c82fe2) | Dec 21, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [1f1c718c61](https://linux-hardware.org/?probe=1f1c718c61) | Dec 21, 2022 |
| Lenovo        | G700 20251                  | [ba8b12c87e](https://linux-hardware.org/?probe=ba8b12c87e) | Dec 21, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c56023ff15](https://linux-hardware.org/?probe=c56023ff15) | Dec 21, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [7fe5232b14](https://linux-hardware.org/?probe=7fe5232b14) | Dec 20, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [bbfea042cd](https://linux-hardware.org/?probe=bbfea042cd) | Dec 20, 2022 |
| ASUSTek       | X550VC                      | [5d5f66f67a](https://linux-hardware.org/?probe=5d5f66f67a) | Dec 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [a7364cab6e](https://linux-hardware.org/?probe=a7364cab6e) | Dec 20, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [011d3e746d](https://linux-hardware.org/?probe=011d3e746d) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [593cdd8cf6](https://linux-hardware.org/?probe=593cdd8cf6) | Dec 19, 2022 |
| MSI           | CreatorPro Z17 A12UKST      | [6b97aacdf0](https://linux-hardware.org/?probe=6b97aacdf0) | Dec 19, 2022 |
| Dell          | Latitude 7320               | [25546304f0](https://linux-hardware.org/?probe=25546304f0) | Dec 19, 2022 |
| Dell          | Latitude 7320               | [ad474d946a](https://linux-hardware.org/?probe=ad474d946a) | Dec 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [ebf2594631](https://linux-hardware.org/?probe=ebf2594631) | Dec 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [714d2a6dea](https://linux-hardware.org/?probe=714d2a6dea) | Dec 19, 2022 |
| Irbis         | NB264                       | [4bb5935a41](https://linux-hardware.org/?probe=4bb5935a41) | Dec 19, 2022 |
| Irbis         | NB264                       | [1209e6c899](https://linux-hardware.org/?probe=1209e6c899) | Dec 19, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a5a207a46d](https://linux-hardware.org/?probe=a5a207a46d) | Dec 19, 2022 |
| Timi          | RedmiBook Pro 15S           | [6a2ea2cc50](https://linux-hardware.org/?probe=6a2ea2cc50) | Dec 18, 2022 |
| Timi          | RedmiBook Pro 15S           | [a1ccdb589e](https://linux-hardware.org/?probe=a1ccdb589e) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [4c1ad2ea2e](https://linux-hardware.org/?probe=4c1ad2ea2e) | Dec 18, 2022 |
| MSI           | X460/X460DX                 | [6fff37a8a5](https://linux-hardware.org/?probe=6fff37a8a5) | Dec 18, 2022 |
| MSI           | X460/X460DX                 | [71ca32ac12](https://linux-hardware.org/?probe=71ca32ac12) | Dec 18, 2022 |
| Acer          | Nitro AN515-56              | [cac9892365](https://linux-hardware.org/?probe=cac9892365) | Dec 18, 2022 |
| Kraftway      | ACCORD                      | [34360d84a8](https://linux-hardware.org/?probe=34360d84a8) | Dec 18, 2022 |
| eMachines     | E525                        | [2a0aeb50bf](https://linux-hardware.org/?probe=2a0aeb50bf) | Dec 18, 2022 |
| Pegatron      | C15B                        | [865b882e8a](https://linux-hardware.org/?probe=865b882e8a) | Dec 18, 2022 |
| Kraftway      | ACCORD                      | [a199d930ff](https://linux-hardware.org/?probe=a199d930ff) | Dec 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [23b255ed61](https://linux-hardware.org/?probe=23b255ed61) | Dec 18, 2022 |
| Acer          | AO533                       | [1639951fe5](https://linux-hardware.org/?probe=1639951fe5) | Dec 18, 2022 |
| ASUSTek       | K55A                        | [6129e825d9](https://linux-hardware.org/?probe=6129e825d9) | Dec 18, 2022 |
| ASUSTek       | 1201N                       | [214a7002b9](https://linux-hardware.org/?probe=214a7002b9) | Dec 18, 2022 |
| Dell          | Inspiron 15-3552            | [0dc1961e62](https://linux-hardware.org/?probe=0dc1961e62) | Dec 18, 2022 |
| Aquarius      | Pro, Std, Elt Series        | [59b7fca136](https://linux-hardware.org/?probe=59b7fca136) | Dec 18, 2022 |
| HP            | Pavilion g7                 | [6a1a042504](https://linux-hardware.org/?probe=6a1a042504) | Dec 18, 2022 |
| ASUSTek       | X555UJ                      | [94a9979dd8](https://linux-hardware.org/?probe=94a9979dd8) | Dec 18, 2022 |
| HP            | Pavilion g7                 | [465a08d81a](https://linux-hardware.org/?probe=465a08d81a) | Dec 18, 2022 |
| ASUSTek       | N551JM                      | [e02ba85a63](https://linux-hardware.org/?probe=e02ba85a63) | Dec 18, 2022 |
| Lenovo        | G580 20157                  | [c6cce8ff6d](https://linux-hardware.org/?probe=c6cce8ff6d) | Dec 18, 2022 |
| Dell          | Inspiron 1525               | [216bedab36](https://linux-hardware.org/?probe=216bedab36) | Dec 18, 2022 |
| Prestigio     | PSB141C04CGH                | [60f02a4cb4](https://linux-hardware.org/?probe=60f02a4cb4) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [f047451b08](https://linux-hardware.org/?probe=f047451b08) | Dec 17, 2022 |
| ICL           | RAYbook Si1511              | [9994b3ec08](https://linux-hardware.org/?probe=9994b3ec08) | Dec 17, 2022 |
| Gigabyte      | G5 KE                       | [9ff3d65e35](https://linux-hardware.org/?probe=9ff3d65e35) | Dec 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1fe7ad453e](https://linux-hardware.org/?probe=1fe7ad453e) | Dec 17, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [c04b0805ad](https://linux-hardware.org/?probe=c04b0805ad) | Dec 17, 2022 |
| GPD           | G1619-04                    | [0859fa80c8](https://linux-hardware.org/?probe=0859fa80c8) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [645e7245d4](https://linux-hardware.org/?probe=645e7245d4) | Dec 17, 2022 |
| Acer          | Aspire ES1-521              | [4f4f04579a](https://linux-hardware.org/?probe=4f4f04579a) | Dec 17, 2022 |
| Maibenben     | MaiBook M                   | [a216b90cac](https://linux-hardware.org/?probe=a216b90cac) | Dec 17, 2022 |
| Apple         | MacBook4,1                  | [26bb5af1a4](https://linux-hardware.org/?probe=26bb5af1a4) | Dec 16, 2022 |
| Lenovo        | ThinkPad X200s 7466A17      | [1831439f56](https://linux-hardware.org/?probe=1831439f56) | Dec 16, 2022 |
| ASUSTek       | X550CC                      | [045064bd18](https://linux-hardware.org/?probe=045064bd18) | Dec 16, 2022 |
| Acer          | Aspire V5-571G              | [575a61802b](https://linux-hardware.org/?probe=575a61802b) | Dec 16, 2022 |
| 3Logic Gro... | Graviton N15i               | [9d85f624db](https://linux-hardware.org/?probe=9d85f624db) | Dec 16, 2022 |
| Dell          | Vostro 5590                 | [3735674d3f](https://linux-hardware.org/?probe=3735674d3f) | Dec 16, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [a04f7471b9](https://linux-hardware.org/?probe=a04f7471b9) | Dec 16, 2022 |
| Lenovo        | ThinkPad L430 246429G       | [acb9efe70f](https://linux-hardware.org/?probe=acb9efe70f) | Dec 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [66d31fc2c8](https://linux-hardware.org/?probe=66d31fc2c8) | Dec 16, 2022 |
| Shanghai Z... | ZXE CRB                     | [20ce0a7f23](https://linux-hardware.org/?probe=20ce0a7f23) | Dec 16, 2022 |
| HUAWEI        | NBM-WXX9                    | [a9f5b0866f](https://linux-hardware.org/?probe=a9f5b0866f) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | [302dc680df](https://linux-hardware.org/?probe=302dc680df) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | [d289646ec3](https://linux-hardware.org/?probe=d289646ec3) | Dec 16, 2022 |
| Machcreato... | 14                          | [8b69842953](https://linux-hardware.org/?probe=8b69842953) | Dec 15, 2022 |
| Lenovo        | B590 20206                  | [b2b98c19da](https://linux-hardware.org/?probe=b2b98c19da) | Dec 15, 2022 |
| Irbis         | NB264                       | [14764ec4e5](https://linux-hardware.org/?probe=14764ec4e5) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | [ca39e55353](https://linux-hardware.org/?probe=ca39e55353) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [b8cc280665](https://linux-hardware.org/?probe=b8cc280665) | Dec 15, 2022 |
| ASUSTek       | K40IJ                       | [191b6ded65](https://linux-hardware.org/?probe=191b6ded65) | Dec 15, 2022 |
| Unknown       | Unknown                     | [24bebac773](https://linux-hardware.org/?probe=24bebac773) | Dec 15, 2022 |
| Lenovo        | G700 20251                  | [f72bd71975](https://linux-hardware.org/?probe=f72bd71975) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1dd0f2a71f](https://linux-hardware.org/?probe=1dd0f2a71f) | Dec 15, 2022 |
| Unknown       | Unknown                     | [643cb41a84](https://linux-hardware.org/?probe=643cb41a84) | Dec 15, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [e6b439e36e](https://linux-hardware.org/?probe=e6b439e36e) | Dec 15, 2022 |
| Dell          | Inspiron 5370               | [dd8f3feae5](https://linux-hardware.org/?probe=dd8f3feae5) | Dec 15, 2022 |
| Lenovo        | B50-70 20384                | [82edcc6c08](https://linux-hardware.org/?probe=82edcc6c08) | Dec 15, 2022 |
| Irbis         | NB264                       | [d137aad605](https://linux-hardware.org/?probe=d137aad605) | Dec 14, 2022 |
| Digma         | EVE 11 C421Y ES1067EW       | [458afe13df](https://linux-hardware.org/?probe=458afe13df) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c84a4ee6f2](https://linux-hardware.org/?probe=c84a4ee6f2) | Dec 14, 2022 |
| ECS           | CMPC                        | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| ASUSTek       | F7Z                         | [3c42714822](https://linux-hardware.org/?probe=3c42714822) | Dec 14, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7040d4353c](https://linux-hardware.org/?probe=7040d4353c) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [d8d72f23e6](https://linux-hardware.org/?probe=d8d72f23e6) | Dec 14, 2022 |
| ASUSTek       | N73SV                       | [7b729a3a7c](https://linux-hardware.org/?probe=7b729a3a7c) | Dec 14, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [1457c2669d](https://linux-hardware.org/?probe=1457c2669d) | Dec 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c476fb8f49](https://linux-hardware.org/?probe=c476fb8f49) | Dec 13, 2022 |
| Dell          | Inspiron 1525               | [5a88d1f0e3](https://linux-hardware.org/?probe=5a88d1f0e3) | Dec 13, 2022 |
| Acer          | Aspire 5720                 | [5940b07034](https://linux-hardware.org/?probe=5940b07034) | Dec 13, 2022 |
| Pegatron      | C17A                        | [adde308568](https://linux-hardware.org/?probe=adde308568) | Dec 13, 2022 |
| ASUSTek       | N73SV                       | [c696bac1dd](https://linux-hardware.org/?probe=c696bac1dd) | Dec 13, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [5d00840ad3](https://linux-hardware.org/?probe=5d00840ad3) | Dec 13, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b479704ea5](https://linux-hardware.org/?probe=b479704ea5) | Dec 13, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [d01e578aa0](https://linux-hardware.org/?probe=d01e578aa0) | Dec 13, 2022 |
| Sony          | VPCEJ1L1R                   | [25ab3e0119](https://linux-hardware.org/?probe=25ab3e0119) | Dec 13, 2022 |
| Valve         | Jupiter                     | [008a4d9a91](https://linux-hardware.org/?probe=008a4d9a91) | Dec 13, 2022 |
| MSI           | GF65 Thin 10UE              | [ff4ab808c0](https://linux-hardware.org/?probe=ff4ab808c0) | Dec 13, 2022 |
| Clevo         | M7x0K                       | [08ce94ab11](https://linux-hardware.org/?probe=08ce94ab11) | Dec 13, 2022 |
| GPD           | G1619-04                    | [d263576c0f](https://linux-hardware.org/?probe=d263576c0f) | Dec 12, 2022 |
| Lenovo        | V14-IIL 82C4                | [8c4853dba7](https://linux-hardware.org/?probe=8c4853dba7) | Dec 12, 2022 |
| Lenovo        | ThinkPad T440s 20AQ004EU... | [8d04dfe3a5](https://linux-hardware.org/?probe=8d04dfe3a5) | Dec 12, 2022 |
| Timi          | TM1701                      | [ab22ee1055](https://linux-hardware.org/?probe=ab22ee1055) | Dec 12, 2022 |
| Lenovo        | ThinkPad T460 20FMS1GR17    | [2d90485ea0](https://linux-hardware.org/?probe=2d90485ea0) | Dec 12, 2022 |
| Sony          | SVE1111M1RW                 | [bc29721da9](https://linux-hardware.org/?probe=bc29721da9) | Dec 12, 2022 |
| Acer          | Aspire 5740                 | [5b35ba45a3](https://linux-hardware.org/?probe=5b35ba45a3) | Dec 12, 2022 |
| Lenovo        | IdeaPad Z580                | [4784b53f14](https://linux-hardware.org/?probe=4784b53f14) | Dec 12, 2022 |
| Acer          | Aspire A515-44              | [965817e5f0](https://linux-hardware.org/?probe=965817e5f0) | Dec 11, 2022 |
| Acer          | Aspire A315-42G             | [1d93c8b401](https://linux-hardware.org/?probe=1d93c8b401) | Dec 11, 2022 |
| Toshiba       | Satellite A300              | [211e44e5d2](https://linux-hardware.org/?probe=211e44e5d2) | Dec 11, 2022 |
| Sony          | VPCEB3D4R                   | [5f85b7c516](https://linux-hardware.org/?probe=5f85b7c516) | Dec 11, 2022 |
| Lenovo        | G770 20089                  | [f6f1441538](https://linux-hardware.org/?probe=f6f1441538) | Dec 11, 2022 |
| MSI           | Modern 14 B11MOU            | [ec8ac9bbd7](https://linux-hardware.org/?probe=ec8ac9bbd7) | Dec 11, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [c90a3cb8c2](https://linux-hardware.org/?probe=c90a3cb8c2) | Dec 11, 2022 |
| Acer          | Aspire E5-571G              | [5ddea1e0e0](https://linux-hardware.org/?probe=5ddea1e0e0) | Dec 11, 2022 |
| ASUSTek       | UL30A                       | [f24e02511f](https://linux-hardware.org/?probe=f24e02511f) | Dec 11, 2022 |
| Notebook      | WA50SRQ                     | [da74211ac6](https://linux-hardware.org/?probe=da74211ac6) | Dec 11, 2022 |
| Lenovo        | G700 20251                  | [0400a58c53](https://linux-hardware.org/?probe=0400a58c53) | Dec 11, 2022 |
| HP            | Laptop 15-bw0xx             | [5f885c41a0](https://linux-hardware.org/?probe=5f885c41a0) | Dec 11, 2022 |
| Samsung       | SQ45/Q70C/P200              | [4a96589cf5](https://linux-hardware.org/?probe=4a96589cf5) | Dec 11, 2022 |
| ASUSTek       | N75SF                       | [4d1916b6ca](https://linux-hardware.org/?probe=4d1916b6ca) | Dec 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [b56d83f25b](https://linux-hardware.org/?probe=b56d83f25b) | Dec 10, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [6cedae9702](https://linux-hardware.org/?probe=6cedae9702) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bb4615bd96](https://linux-hardware.org/?probe=bb4615bd96) | Dec 10, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [92d1403bdf](https://linux-hardware.org/?probe=92d1403bdf) | Dec 10, 2022 |
| Samsung       | RC530/RC730                 | [4b7783525a](https://linux-hardware.org/?probe=4b7783525a) | Dec 10, 2022 |
| Acer          | Aspire E1-571G              | [344383d85d](https://linux-hardware.org/?probe=344383d85d) | Dec 10, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fa13871cf9](https://linux-hardware.org/?probe=fa13871cf9) | Dec 10, 2022 |
| Lenovo        | V15-IGL 82C3                | [ec71643183](https://linux-hardware.org/?probe=ec71643183) | Dec 09, 2022 |
| Lenovo        | V15-IGL 82C3                | [aa2fd0b3bc](https://linux-hardware.org/?probe=aa2fd0b3bc) | Dec 09, 2022 |
| Pegatron      | C17A                        | [2437a88730](https://linux-hardware.org/?probe=2437a88730) | Dec 09, 2022 |
| MSI           | Modern 15 B12M              | [b5f43a3075](https://linux-hardware.org/?probe=b5f43a3075) | Dec 09, 2022 |
| HP            | Laptop 14s-dq1xxx           | [6af7fadd72](https://linux-hardware.org/?probe=6af7fadd72) | Dec 09, 2022 |
| HP            | Laptop 14s-dq1xxx           | [7e1510d6c6](https://linux-hardware.org/?probe=7e1510d6c6) | Dec 09, 2022 |
| MSI           | GP66 Leopard 11UG           | [daffbd93fb](https://linux-hardware.org/?probe=daffbd93fb) | Dec 09, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [311f47baef](https://linux-hardware.org/?probe=311f47baef) | Dec 09, 2022 |
| Gigabyte      | AORUS 15G KC                | [91e987df99](https://linux-hardware.org/?probe=91e987df99) | Dec 09, 2022 |
| ASUSTek       | UX310UQK                    | [c4a573e93c](https://linux-hardware.org/?probe=c4a573e93c) | Dec 08, 2022 |
| Acer          | Aspire F5-571G              | [dedd56f0fe](https://linux-hardware.org/?probe=dedd56f0fe) | Dec 08, 2022 |
| Lenovo        | B590 20206                  | [969ca94bb7](https://linux-hardware.org/?probe=969ca94bb7) | Dec 08, 2022 |
| Timi          | Redmi Book Pro 14 2022      | [e7813eb1b3](https://linux-hardware.org/?probe=e7813eb1b3) | Dec 08, 2022 |
| ASUSTek       | K42F                        | [ee90271b2d](https://linux-hardware.org/?probe=ee90271b2d) | Dec 08, 2022 |
| ASUSTek       | N750JV                      | [e06c6025f3](https://linux-hardware.org/?probe=e06c6025f3) | Dec 08, 2022 |
| Dell          | Vostro 14 5410              | [af22c1db61](https://linux-hardware.org/?probe=af22c1db61) | Dec 08, 2022 |
| Apple         | MacBookAir6,2               | [65bc0e828c](https://linux-hardware.org/?probe=65bc0e828c) | Dec 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | [79a0f9e73a](https://linux-hardware.org/?probe=79a0f9e73a) | Dec 08, 2022 |
| Packard Be... | DOT S                       | [753f17a658](https://linux-hardware.org/?probe=753f17a658) | Dec 08, 2022 |
| Acer          | Aspire A315-34              | [85794e606c](https://linux-hardware.org/?probe=85794e606c) | Dec 08, 2022 |
| MSI           | Modern 14 B11MOU            | [426e23829e](https://linux-hardware.org/?probe=426e23829e) | Dec 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | [c1cd524970](https://linux-hardware.org/?probe=c1cd524970) | Dec 08, 2022 |
| Dell          | Inspiron 3721               | [3bfc5892fe](https://linux-hardware.org/?probe=3bfc5892fe) | Dec 08, 2022 |
| Apple         | MacBook7,1                  | [317fdfd70b](https://linux-hardware.org/?probe=317fdfd70b) | Dec 08, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c6d0984a2c](https://linux-hardware.org/?probe=c6d0984a2c) | Dec 08, 2022 |
| ASUSTek       | U24E                        | [e8bdc6be97](https://linux-hardware.org/?probe=e8bdc6be97) | Dec 08, 2022 |
| Aquarius      | NS685U R11                  | [c0dff8c525](https://linux-hardware.org/?probe=c0dff8c525) | Dec 08, 2022 |
| MSI           | Modern 14 B11MOU            | [49e70cf65f](https://linux-hardware.org/?probe=49e70cf65f) | Dec 07, 2022 |
| Dell          | Inspiron 3137               | [2f74d45567](https://linux-hardware.org/?probe=2f74d45567) | Dec 07, 2022 |
| Unknown       | Y116                        | [204f1465c7](https://linux-hardware.org/?probe=204f1465c7) | Dec 07, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [cd83a085ba](https://linux-hardware.org/?probe=cd83a085ba) | Dec 07, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fd694a5ddd](https://linux-hardware.org/?probe=fd694a5ddd) | Dec 07, 2022 |
| HP            | ENVY 17                     | [a19d90a89f](https://linux-hardware.org/?probe=a19d90a89f) | Dec 07, 2022 |
| HP            | EliteBook 8540p             | [1c0ff5bf47](https://linux-hardware.org/?probe=1c0ff5bf47) | Dec 07, 2022 |
| HP            | EliteBook 8540p             | [9cf475f84e](https://linux-hardware.org/?probe=9cf475f84e) | Dec 07, 2022 |
| Pegatron      | C17A                        | [5fc3c61389](https://linux-hardware.org/?probe=5fc3c61389) | Dec 07, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [619fd919a1](https://linux-hardware.org/?probe=619fd919a1) | Dec 07, 2022 |
| ASUSTek       | K53SV                       | [a745b1ead9](https://linux-hardware.org/?probe=a745b1ead9) | Dec 07, 2022 |
| Clevo         | P150HMx                     | [f1500b1665](https://linux-hardware.org/?probe=f1500b1665) | Dec 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [ceae9dc7d5](https://linux-hardware.org/?probe=ceae9dc7d5) | Dec 06, 2022 |
| Acer          | Extensa 5220                | [30ca0c3efa](https://linux-hardware.org/?probe=30ca0c3efa) | Dec 06, 2022 |
| HONOR         | BBR-WAX9                    | [d7d701ca15](https://linux-hardware.org/?probe=d7d701ca15) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | [0613a1c41e](https://linux-hardware.org/?probe=0613a1c41e) | Dec 06, 2022 |
| MSI           | Pulse GL66 12UEK            | [ea01a2005e](https://linux-hardware.org/?probe=ea01a2005e) | Dec 06, 2022 |
| HP            | Laptop 17-ak0xx             | [9fb5c9d094](https://linux-hardware.org/?probe=9fb5c9d094) | Dec 06, 2022 |
| HP            | ENVY 17                     | [569f7b0e9f](https://linux-hardware.org/?probe=569f7b0e9f) | Dec 06, 2022 |
| HP            | Pavilion 15                 | [eb3caff76e](https://linux-hardware.org/?probe=eb3caff76e) | Dec 06, 2022 |
| ICL           | RAYbook Si1512              | [b8c52ae5cb](https://linux-hardware.org/?probe=b8c52ae5cb) | Dec 06, 2022 |
| HP            | ProBook 440 G5              | [7f9c0a0974](https://linux-hardware.org/?probe=7f9c0a0974) | Dec 06, 2022 |
| MSI           | Pulse GL66 12UEK            | [4438c9636c](https://linux-hardware.org/?probe=4438c9636c) | Dec 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [12e33b1925](https://linux-hardware.org/?probe=12e33b1925) | Dec 06, 2022 |
| HP            | ProBook 650 G1              | [d080bb3fe0](https://linux-hardware.org/?probe=d080bb3fe0) | Dec 05, 2022 |
| HP            | ProBook 650 G1              | [8e3bfa4f20](https://linux-hardware.org/?probe=8e3bfa4f20) | Dec 05, 2022 |
| Gigabyte      | U24                         | [dbe62c503d](https://linux-hardware.org/?probe=dbe62c503d) | Dec 05, 2022 |
| Apple         | MacBookPro9,2               | [5827ea2fa5](https://linux-hardware.org/?probe=5827ea2fa5) | Dec 05, 2022 |
| HONOR         | BOHK-WAX9X                  | [543eb800d7](https://linux-hardware.org/?probe=543eb800d7) | Dec 05, 2022 |
| Apple         | MacBookPro9,2               | [7f8dcdb666](https://linux-hardware.org/?probe=7f8dcdb666) | Dec 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [0cd3371014](https://linux-hardware.org/?probe=0cd3371014) | Dec 05, 2022 |
| Dell          | Inspiron 3521               | [44f8fe348a](https://linux-hardware.org/?probe=44f8fe348a) | Dec 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d512bff9cc](https://linux-hardware.org/?probe=d512bff9cc) | Dec 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [fef748b3f4](https://linux-hardware.org/?probe=fef748b3f4) | Dec 04, 2022 |
| MSI           | Sword 15 A12UE              | [32df733b5e](https://linux-hardware.org/?probe=32df733b5e) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| Lenovo        | ThinkPad L420 7854RP1       | [3216e34b2e](https://linux-hardware.org/?probe=3216e34b2e) | Dec 04, 2022 |
| ASUSTek       | P43E                        | [c21502af00](https://linux-hardware.org/?probe=c21502af00) | Dec 04, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [3ee55cc441](https://linux-hardware.org/?probe=3ee55cc441) | Dec 04, 2022 |
| Acer          | Nitro AN515-43              | [f18907cee0](https://linux-hardware.org/?probe=f18907cee0) | Dec 04, 2022 |
| ASUSTek       | K42F                        | [05ddce411d](https://linux-hardware.org/?probe=05ddce411d) | Dec 04, 2022 |
| HP            | ProBook 440 G5              | [a8e17ad39c](https://linux-hardware.org/?probe=a8e17ad39c) | Dec 04, 2022 |
| ASUSTek       | X550CC                      | [be693e121b](https://linux-hardware.org/?probe=be693e121b) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [c795306dd2](https://linux-hardware.org/?probe=c795306dd2) | Dec 03, 2022 |
| HP            | ProBook 430 G2              | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| Pegatron      | A15W8                       | [f33c1aea21](https://linux-hardware.org/?probe=f33c1aea21) | Dec 03, 2022 |
| Unknown       | Unknown                     | [40917baf56](https://linux-hardware.org/?probe=40917baf56) | Dec 03, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [91bffab1ae](https://linux-hardware.org/?probe=91bffab1ae) | Dec 03, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [795327c2b7](https://linux-hardware.org/?probe=795327c2b7) | Dec 03, 2022 |
| HONOR         | NMH-WCX9                    | [3f107d24d1](https://linux-hardware.org/?probe=3f107d24d1) | Dec 03, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6cb73d5a1c](https://linux-hardware.org/?probe=6cb73d5a1c) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [77651c30c5](https://linux-hardware.org/?probe=77651c30c5) | Dec 03, 2022 |
| ASUSTek       | X541UJ                      | [898b49da7f](https://linux-hardware.org/?probe=898b49da7f) | Dec 03, 2022 |
| ASUSTek       | N750JV                      | [0fc50d63c4](https://linux-hardware.org/?probe=0fc50d63c4) | Dec 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e16c372c9c](https://linux-hardware.org/?probe=e16c372c9c) | Dec 02, 2022 |
| ASUSTek       | X550CL                      | [8a2aad437e](https://linux-hardware.org/?probe=8a2aad437e) | Dec 02, 2022 |
| Lenovo        | B590 20208                  | [367c0f8907](https://linux-hardware.org/?probe=367c0f8907) | Dec 02, 2022 |
| MSI           | GE72 6QC                    | [8411668d4d](https://linux-hardware.org/?probe=8411668d4d) | Dec 02, 2022 |
| Acer          | Aspire 5951G                | [0b1e900a8c](https://linux-hardware.org/?probe=0b1e900a8c) | Dec 02, 2022 |
| Aquarius      | NS585                       | [bbd3bd3ca6](https://linux-hardware.org/?probe=bbd3bd3ca6) | Dec 02, 2022 |
| HP            | 635                         | [cf79165440](https://linux-hardware.org/?probe=cf79165440) | Dec 02, 2022 |
| Aquarius      | NS585                       | [50222418e5](https://linux-hardware.org/?probe=50222418e5) | Dec 02, 2022 |
| Aquarius      | NS585                       | [d55d40681f](https://linux-hardware.org/?probe=d55d40681f) | Dec 02, 2022 |
| Aquarius      | NS585                       | [9013a1cce6](https://linux-hardware.org/?probe=9013a1cce6) | Dec 02, 2022 |
| Acer          | Aspire V5-572G              | [638e9873a7](https://linux-hardware.org/?probe=638e9873a7) | Dec 02, 2022 |
| Acer          | Aspire V5-572G              | [711acef394](https://linux-hardware.org/?probe=711acef394) | Dec 02, 2022 |
| Unknown       | Y116                        | [5686455162](https://linux-hardware.org/?probe=5686455162) | Dec 02, 2022 |
| Unknown       | Y116                        | [5050c40509](https://linux-hardware.org/?probe=5050c40509) | Dec 02, 2022 |
| Acer          | Swift SF314-510G            | [b66322960d](https://linux-hardware.org/?probe=b66322960d) | Dec 02, 2022 |
| Samsung       | R410                        | [7c2a18f2cc](https://linux-hardware.org/?probe=7c2a18f2cc) | Dec 01, 2022 |
| Acer          | Aspire V3-571G              | [bbb0c707bb](https://linux-hardware.org/?probe=bbb0c707bb) | Dec 01, 2022 |
| Acer          | Aspire V3-771               | [38dfcb79d5](https://linux-hardware.org/?probe=38dfcb79d5) | Dec 01, 2022 |
| Acer          | Aspire 3830TG               | [8bb246cbaa](https://linux-hardware.org/?probe=8bb246cbaa) | Dec 01, 2022 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [79261239c1](https://linux-hardware.org/?probe=79261239c1) | Dec 01, 2022 |
| Acer          | Aspire 3830TG               | [46bcb20e26](https://linux-hardware.org/?probe=46bcb20e26) | Dec 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d57de89542](https://linux-hardware.org/?probe=d57de89542) | Dec 01, 2022 |
| Acer          | Aspire E1-570G              | [b41442c5a1](https://linux-hardware.org/?probe=b41442c5a1) | Dec 01, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [a8156db955](https://linux-hardware.org/?probe=a8156db955) | Dec 01, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [0128a48982](https://linux-hardware.org/?probe=0128a48982) | Dec 01, 2022 |
| Acer          | Aspire 5336                 | [65be105c02](https://linux-hardware.org/?probe=65be105c02) | Dec 01, 2022 |
| Unknown       | Unknown                     | [dceef2a9d5](https://linux-hardware.org/?probe=dceef2a9d5) | Dec 01, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ROSA R10         | 1493      | 11.55%  |
| ROSA R11         | 1442      | 11.15%  |
| ROSA R8.1        | 1042      | 8.06%   |
| ROSA R8          | 919       | 7.11%   |
| ROSA R9          | 845       | 6.54%   |
| ROSA R11.1       | 769       | 5.95%   |
| ROSA 12.2        | 769       | 5.95%   |
| Ubuntu 20.04     | 474       | 3.67%   |
| ROSA 12.3        | 265       | 2.05%   |
| Ubuntu 18.04     | 255       | 1.97%   |
| Debian 11        | 252       | 1.95%   |
| OpenMandriva 4.2 | 159       | 1.23%   |
| Ubuntu 22.04     | 155       | 1.2%    |
| ROSA 12.1        | 111       | 0.86%   |
| KDE neon 20.04   | 104       | 0.8%    |
| Arch             | 98        | 0.76%   |
| Arch Rolling     | 95        | 0.73%   |
| OpenMandriva 4.3 | 92        | 0.71%   |
| Fedora 36        | 91        | 0.7%    |
| Linux Mint 19.3  | 84        | 0.65%   |
| Manjaro          | 80        | 0.62%   |
| Fedora 37        | 77        | 0.6%    |
| Fedora 35        | 71        | 0.55%   |
| Linux Mint 20.3  | 68        | 0.53%   |
| Linux Mint 20.1  | 68        | 0.53%   |
| Debian 10        | 60        | 0.46%   |
| Linux Mint 19.1  | 59        | 0.46%   |
| Linux Mint 18.3  | 59        | 0.46%   |
| Kubuntu 20.04    | 59        | 0.46%   |
| Fedora 34        | 57        | 0.44%   |
| Linux Mint 20    | 56        | 0.43%   |
| Linux Mint 19.2  | 55        | 0.43%   |
| Kometa P10       | 54        | 0.42%   |
| Ubuntu 21.10     | 52        | 0.4%    |
| Linux Mint 20.2  | 49        | 0.38%   |
| Xubuntu 18.04    | 47        | 0.36%   |
| Ubuntu 19.10     | 46        | 0.36%   |
| Linux Mint 21    | 45        | 0.35%   |
| ROSA 12          | 44        | 0.34%   |
| Red OS 7.3.1     | 44        | 0.34%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| ROSA          | 6650      | 57.66%  |
| Ubuntu        | 1123      | 9.74%   |
| Linux Mint    | 587       | 5.09%   |
| Fedora        | 373       | 3.23%   |
| Debian        | 352       | 3.05%   |
| Manjaro       | 323       | 2.8%    |
| OpenMandriva  | 311       | 2.7%    |
| Endless       | 214       | 1.86%   |
| ALT Linux     | 193       | 1.67%   |
| Arch          | 183       | 1.59%   |
| Kubuntu       | 138       | 1.2%    |
| KDE neon      | 133       | 1.15%   |
| Xubuntu       | 116       | 1.01%   |
| Pop!_OS       | 85        | 0.74%   |
| Red OS        | 76        | 0.66%   |
| Gentoo        | 56        | 0.49%   |
| Elementary    | 52        | 0.45%   |
| Kali          | 51        | 0.44%   |
| RED           | 46        | 0.4%    |
| openSUSE      | 44        | 0.38%   |
| Lubuntu       | 38        | 0.33%   |
| LMDE          | 35        | 0.3%    |
| Zorin         | 33        | 0.29%   |
| Clear Linux   | 31        | 0.27%   |
| Ubuntu MATE   | 30        | 0.26%   |
| Ubuntu Unity  | 24        | 0.21%   |
| ArcoLinux     | 20        | 0.17%   |
| SteamOS       | 14        | 0.12%   |
| CentOS        | 13        | 0.11%   |
| Astra Linux   | 13        | 0.11%   |
| Artix         | 13        | 0.11%   |
| Ubuntu Budgie | 12        | 0.1%    |
| RELS          | 11        | 0.1%    |
| Parrot        | 11        | 0.1%    |
| MX            | 11        | 0.1%    |
| EndeavourOS   | 10        | 0.09%   |
| Calculate     | 8         | 0.07%   |
| Void Linux    | 7         | 0.06%   |
| Devuan        | 6         | 0.05%   |
| BlackPanther  | 6         | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.10.74-generic-2rosa2021.1-x86_64  | 648       | 4.66%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 620       | 4.46%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 620       | 4.46%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 585       | 4.21%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 349       | 2.51%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 278       | 2%      |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 275       | 1.98%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 236       | 1.7%    |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 218       | 1.57%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 200       | 1.44%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 175       | 1.26%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 175       | 1.26%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 174       | 1.25%   |
| 4.15.0-desktop-45.1rosa-i586        | 172       | 1.24%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 169       | 1.21%   |
| 5.10.14-desktop-1omv4002            | 154       | 1.11%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 147       | 1.06%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 146       | 1.05%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 146       | 1.05%   |
| 5.4.32-generic-2rosa-x86_64         | 145       | 1.04%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 138       | 0.99%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 135       | 0.97%   |
| 5.4.83-generic-2rosa-x86_64         | 129       | 0.93%   |
| 5.10.0-7-amd64                      | 110       | 0.79%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 107       | 0.77%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 106       | 0.76%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 96        | 0.69%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 96        | 0.69%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 90        | 0.65%   |
| 5.16.7-desktop-1omv4003             | 85        | 0.61%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 82        | 0.59%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 78        | 0.56%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 73        | 0.52%   |
| 5.4.0-42-generic                    | 71        | 0.51%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 69        | 0.5%    |
| 5.4.32-generic-2rosa-i586           | 61        | 0.44%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 59        | 0.42%   |
| 4.9.41-nrj-desktop-1rosa-i586       | 58        | 0.42%   |
| 4.1.38-nrj-desktop-1rosa-x86_64     | 56        | 0.4%    |
| 4.9.155-nrj-desktop-1rosa-i586      | 54        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 1884      | 14%     |
| 4.9.60   | 820       | 6.09%   |
| 4.9.20   | 762       | 5.66%   |
| 5.4.0    | 703       | 5.23%   |
| 5.10.74  | 680       | 5.05%   |
| 4.1.34   | 497       | 3.69%   |
| 4.1.38   | 394       | 2.93%   |
| 4.9.9    | 374       | 2.78%   |
| 4.9.124  | 357       | 2.65%   |
| 5.15.0   | 336       | 2.5%    |
| 4.1.25   | 327       | 2.43%   |
| 5.10.0   | 299       | 2.22%   |
| 5.3.0    | 251       | 1.87%   |
| 4.9.41   | 235       | 1.75%   |
| 4.9.76   | 230       | 1.71%   |
| 5.11.0   | 209       | 1.55%   |
| 4.9.155  | 207       | 1.54%   |
| 5.4.32   | 206       | 1.53%   |
| 5.8.0    | 203       | 1.51%   |
| 5.13.0   | 191       | 1.42%   |
| 5.4.83   | 172       | 1.28%   |
| 5.0.0    | 170       | 1.26%   |
| 5.10.14  | 157       | 1.17%   |
| 5.10.118 | 153       | 1.14%   |
| 4.9.95   | 124       | 0.92%   |
| 5.15.75  | 101       | 0.75%   |
| 4.18.0   | 95        | 0.71%   |
| 4.13.0   | 93        | 0.69%   |
| 5.16.7   | 87        | 0.65%   |
| 4.9.111  | 81        | 0.6%    |
| 5.15.79  | 77        | 0.57%   |
| 4.19.0   | 72        | 0.54%   |
| 4.9.87   | 58        | 0.43%   |
| 5.19.0   | 55        | 0.41%   |
| 4.9.14   | 44        | 0.33%   |
| 5.10.71  | 43        | 0.32%   |
| 6.1.1    | 40        | 0.3%    |
| 5.17.11  | 39        | 0.29%   |
| 5.10.102 | 37        | 0.28%   |
| 4.1.15   | 37        | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 2896      | 22.88%  |
| 4.15    | 1899      | 15%     |
| 5.10    | 1547      | 12.22%  |
| 5.4     | 1211      | 9.57%   |
| 4.1     | 1200      | 9.48%   |
| 5.15    | 814       | 6.43%   |
| 5.3     | 291       | 2.3%    |
| 5.11    | 276       | 2.18%   |
| 5.8     | 263       | 2.08%   |
| 5.13    | 251       | 1.98%   |
| 5.0     | 178       | 1.41%   |
| 5.16    | 158       | 1.25%   |
| 6.0     | 135       | 1.07%   |
| 6.1     | 126       | 1%      |
| 5.17    | 125       | 0.99%   |
| 5.18    | 117       | 0.92%   |
| 5.19    | 114       | 0.9%    |
| 4.19    | 112       | 0.88%   |
| 4.18    | 110       | 0.87%   |
| 4.13    | 109       | 0.86%   |
| 5.14    | 91        | 0.72%   |
| 5.6     | 88        | 0.7%    |
| 5.9     | 69        | 0.55%   |
| 4.4     | 50        | 0.4%    |
| 4.16    | 50        | 0.4%    |
| 5.7     | 49        | 0.39%   |
| 5.12    | 48        | 0.38%   |
| 5.5     | 41        | 0.32%   |
| 4.8     | 37        | 0.29%   |
| 4.10    | 35        | 0.28%   |
| 3.14    | 20        | 0.16%   |
| 4.14    | 19        | 0.15%   |
| 5.2     | 18        | 0.14%   |
| 3.10    | 16        | 0.13%   |
| 4.17    | 14        | 0.11%   |
| 4.12    | 13        | 0.1%    |
| 5.1     | 12        | 0.09%   |
| 4.11    | 12        | 0.09%   |
| 4.7     | 9         | 0.07%   |
| 3.16    | 7         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 9725      | 85.45%  |
| i686    | 1650      | 14.5%   |
| armv7l  | 4         | 0.04%   |
| ppc     | 1         | 0.01%   |
| aarch64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| KDE4               | 4144      | 34.43%  |
| KDE5               | 3025      | 25.13%  |
| GNOME              | 2150      | 17.86%  |
| Unknown            | 690       | 5.73%   |
| XFCE               | 456       | 3.79%   |
| LXQt               | 386       | 3.21%   |
| MATE               | 310       | 2.58%   |
| Cinnamon           | 248       | 2.06%   |
| X-Cinnamon         | 236       | 1.96%   |
| KDE                | 165       | 1.37%   |
| Pantheon           | 49        | 0.41%   |
| i3                 | 32        | 0.27%   |
| LXDE               | 28        | 0.23%   |
| Unity              | 24        | 0.2%    |
| Budgie             | 20        | 0.17%   |
| GNOME Flashback    | 16        | 0.13%   |
| sway               | 11        | 0.09%   |
| fly                | 9         | 0.07%   |
| Deepin             | 6         | 0.05%   |
| DWM                | 4         | 0.03%   |
| awesome            | 4         | 0.03%   |
| Trinity            | 3         | 0.02%   |
| openbox            | 3         | 0.02%   |
| icewm              | 3         | 0.02%   |
| GNOME Classic      | 3         | 0.02%   |
| xmonad             | 2         | 0.02%   |
| fluxbox            | 2         | 0.02%   |
| qtile              | 1         | 0.01%   |
| pantheon-non-gnome | 1         | 0.01%   |
| none+i3            | 1         | 0.01%   |
| Lumina             | 1         | 0.01%   |
| Lubuntu            | 1         | 0.01%   |
| lightdm-xsession   | 1         | 0.01%   |
| Enlightenment      | 1         | 0.01%   |
| bspwm              | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 9437      | 81.8%   |
| Wayland | 1625      | 14.09%  |
| Unknown | 399       | 3.46%   |
| Tty     | 75        | 0.65%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDM     | 4163      | 34.71%  |
| SDDM    | 3127      | 26.07%  |
| Unknown | 2023      | 16.87%  |
| GDM     | 1339      | 11.16%  |
| LightDM | 555       | 4.63%   |
| TDM     | 433       | 3.61%   |
| GDM3    | 292       | 2.43%   |
| MDM     | 21        | 0.18%   |
| XDM     | 17        | 0.14%   |
| SLiM    | 8         | 0.07%   |
| FLY-DM  | 5         | 0.04%   |
| NODM    | 3         | 0.03%   |
| Ly      | 3         | 0.03%   |
| GREETD  | 3         | 0.03%   |
| LXDM    | 2         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 5800      | 49.6%   |
| ru_RU       | 4546      | 38.87%  |
| en_US       | 1160      | 9.92%   |
| C           | 64        | 0.55%   |
| en_GB       | 51        | 0.44%   |
| ru_RU.UTF_8 | 19        | 0.16%   |
| ru_UA       | 8         | 0.07%   |
| zh_CN       | 4         | 0.03%   |
| POSIX       | 4         | 0.03%   |
| en_AG       | 4         | 0.03%   |
| C.UTF8      | 4         | 0.03%   |
| en_CA       | 3         | 0.03%   |
| de_DE       | 3         | 0.03%   |
| uk_UA       | 2         | 0.02%   |
| tr_TR       | 2         | 0.02%   |
| it_IT       | 2         | 0.02%   |
| fr_FR       | 2         | 0.02%   |
| es_ES       | 2         | 0.02%   |
| cv_RU       | 2         | 0.02%   |
| ba_RU       | 2         | 0.02%   |
| tt_RU       | 1         | 0.01%   |
| ru_RU.UTF8  | 1         | 0.01%   |
| pt_BR       | 1         | 0.01%   |
| myv_RU      | 1         | 0.01%   |
| ja_JP       | 1         | 0.01%   |
| en_NZ       | 1         | 0.01%   |
| en_GB.utf-8 | 1         | 0.01%   |
| en_DK       | 1         | 0.01%   |
| en_AU       | 1         | 0.01%   |
| en-US       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 6697      | 58.35%  |
| EFI  | 4781      | 41.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 7014      | 58.98%  |
| Unknown  | 3579      | 30.09%  |
| Btrfs    | 644       | 5.41%   |
| Overlay  | 496       | 4.17%   |
| Xfs      | 56        | 0.47%   |
| Zfs      | 24        | 0.2%    |
| Ext3     | 21        | 0.18%   |
| Ext2     | 20        | 0.17%   |
| Aufs     | 16        | 0.13%   |
| F2fs     | 9         | 0.08%   |
| Tmpfs    | 4         | 0.03%   |
| Rootfs   | 3         | 0.03%   |
| Reiserfs | 3         | 0.03%   |
| XXXXXXX  | 1         | 0.01%   |
| XXXXX    | 1         | 0.01%   |
| Ufs      | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 4489      | 37.82%  |
| GPT     | 3928      | 33.09%  |
| Unknown | 3453      | 29.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 10272     | 88.86%  |
| Yes       | 1288      | 11.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 8486      | 72.62%  |
| Yes       | 3200      | 27.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 2063      | 18.33%  |
| ASUSTek Computer    | 2006      | 17.82%  |
| Hewlett-Packard     | 1649      | 14.65%  |
| Acer                | 1574      | 13.99%  |
| Dell                | 804       | 7.14%   |
| Samsung Electronics | 641       | 5.7%    |
| Toshiba             | 283       | 2.51%   |
| MSI                 | 278       | 2.47%   |
| Sony                | 260       | 2.31%   |
| Packard Bell        | 170       | 1.51%   |
| HUAWEI              | 170       | 1.51%   |
| eMachines           | 112       | 1%      |
| Unknown             | 92        | 0.82%   |
| Clevo               | 87        | 0.77%   |
| Apple               | 87        | 0.77%   |
| Timi                | 76        | 0.68%   |
| Aquarius            | 73        | 0.65%   |
| Notebook            | 72        | 0.64%   |
| Pegatron            | 58        | 0.52%   |
| Fujitsu Siemens     | 42        | 0.37%   |
| Digma               | 40        | 0.36%   |
| DNS                 | 39        | 0.35%   |
| Fujitsu             | 38        | 0.34%   |
| Intel               | 35        | 0.31%   |
| HONOR               | 32        | 0.28%   |
| Irbis               | 29        | 0.26%   |
| DEXP                | 28        | 0.25%   |
| Quanta              | 27        | 0.24%   |
| Prestigio           | 25        | 0.22%   |
| ICL                 | 23        | 0.2%    |
| Chuwi               | 19        | 0.17%   |
| Gigabyte Technology | 18        | 0.16%   |
| Maibenben           | 16        | 0.14%   |
| Haier               | 14        | 0.12%   |
| Valve               | 13        | 0.12%   |
| Insyde              | 13        | 0.12%   |
| 3Logic Group        | 13        | 0.12%   |
| Panasonic           | 10        | 0.09%   |
| Infomash            | 10        | 0.09%   |
| LG Electronics      | 9         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 160       | 1.42%   |
| HP Pavilion g6                             | 123       | 1.09%   |
| HP Notebook                                | 79        | 0.7%    |
| HP Pavilion dv6                            | 76        | 0.68%   |
| HP Laptop 15-bw0xx                         | 75        | 0.67%   |
| Acer Aspire V3-571G                        | 57        | 0.51%   |
| Lenovo G570 20079                          | 52        | 0.46%   |
| Aquarius NS585                             | 46        | 0.41%   |
| Lenovo B570e HuronRiver Platform           | 44        | 0.39%   |
| HP Pavilion dv7                            | 41        | 0.36%   |
| Lenovo B590 20206                          | 40        | 0.36%   |
| Packard Bell EasyNote TE11HC               | 38        | 0.34%   |
| HP Pavilion 15                             | 38        | 0.34%   |
| Lenovo G50-45 80E3                         | 36        | 0.32%   |
| Lenovo B590 20208                          | 36        | 0.32%   |
| HUAWEI NBLK-WAX9X                          | 34        | 0.3%    |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 32        | 0.28%   |
| Lenovo G500 20236                          | 32        | 0.28%   |
| Lenovo G50-30 80G0                         | 32        | 0.28%   |
| HP Pavilion g7                             | 32        | 0.28%   |
| Toshiba Satellite C660                     | 31        | 0.28%   |
| Lenovo B560                                | 31        | 0.28%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 31        | 0.28%   |
| Dell Inspiron N5110                        | 30        | 0.27%   |
| Acer Aspire 5750G                          | 30        | 0.27%   |
| Lenovo G580 20150                          | 29        | 0.26%   |
| Lenovo G580 20157                          | 28        | 0.25%   |
| ASUS K50IJ                                 | 28        | 0.25%   |
| Acer Aspire E1-571G                        | 28        | 0.25%   |
| Acer Aspire 5742G                          | 28        | 0.25%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 27        | 0.24%   |
| Samsung 300E4C/300E5C/300E7C               | 26        | 0.23%   |
| Dell Inspiron 3521                         | 26        | 0.23%   |
| ASUS X550CC                                | 26        | 0.23%   |
| Lenovo IdeaPad 110-15ACL 80TJ              | 24        | 0.21%   |
| ASUS X101CH                                | 24        | 0.21%   |
| Lenovo G505s 20255                         | 23        | 0.2%    |
| HP Pavilion Notebook                       | 23        | 0.2%    |
| HP 15                                      | 23        | 0.2%    |
| Dell Inspiron 3542                         | 23        | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1079      | 9.59%   |
| Lenovo IdeaPad        | 610       | 5.42%   |
| HP Pavilion           | 486       | 4.32%   |
| Lenovo ThinkPad       | 439       | 3.9%    |
| Dell Inspiron         | 403       | 3.58%   |
| ASUS VivoBook         | 283       | 2.51%   |
| HP Laptop             | 282       | 2.51%   |
| Toshiba Satellite     | 263       | 2.34%   |
| HP ProBook            | 242       | 2.15%   |
| Unknown               | 160       | 1.42%   |
| Dell Latitude         | 158       | 1.4%    |
| Packard Bell EasyNote | 149       | 1.32%   |
| Acer Extensa          | 145       | 1.29%   |
| Dell Vostro           | 106       | 0.94%   |
| HP Compaq             | 97        | 0.86%   |
| Acer TravelMate       | 89        | 0.79%   |
| HP EliteBook          | 82        | 0.73%   |
| HP Notebook           | 80        | 0.71%   |
| Lenovo G580           | 76        | 0.68%   |
| Lenovo B590           | 76        | 0.68%   |
| Lenovo ThinkBook      | 64        | 0.57%   |
| Lenovo G570           | 53        | 0.47%   |
| HP 250                | 52        | 0.46%   |
| Acer Nitro            | 51        | 0.45%   |
| Acer Swift            | 49        | 0.44%   |
| Aquarius NS585        | 46        | 0.41%   |
| HP ENVY               | 45        | 0.4%    |
| Lenovo B570e          | 44        | 0.39%   |
| Samsung 300V3A        | 43        | 0.38%   |
| Dell XPS              | 43        | 0.38%   |
| Samsung 355V4C        | 42        | 0.37%   |
| Notebook W65          | 40        | 0.36%   |
| Lenovo Legion         | 40        | 0.36%   |
| Lenovo G50-45         | 38        | 0.34%   |
| ASUS ZenBook          | 38        | 0.34%   |
| Fujitsu LIFEBOOK      | 37        | 0.33%   |
| ASUS TUF              | 36        | 0.32%   |
| ASUS ROG              | 36        | 0.32%   |
| HP 255                | 35        | 0.31%   |
| HUAWEI NBLK-WAX9X     | 34        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 1442      | 12.81%  |
| 2012    | 1322      | 11.75%  |
| 2010    | 975       | 8.66%   |
| 2013    | 827       | 7.35%   |
| 2019    | 744       | 6.61%   |
| 2018    | 658       | 5.85%   |
| 2017    | 626       | 5.56%   |
| 2009    | 600       | 5.33%   |
| 2008    | 591       | 5.25%   |
| 2020    | 580       | 5.15%   |
| 2014    | 553       | 4.91%   |
| 2021    | 497       | 4.42%   |
| 2015    | 487       | 4.33%   |
| 2016    | 486       | 4.32%   |
| 2007    | 430       | 3.82%   |
| 2006    | 189       | 1.68%   |
| 2022    | 169       | 1.5%    |
| 2005    | 51        | 0.45%   |
| Unknown | 13        | 0.12%   |
| 2004    | 11        | 0.1%    |
| 2003    | 2         | 0.02%   |
| 2001    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 11254     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 10818     | 95.6%   |
| Enabled  | 498       | 4.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 11238     | 99.86%  |
| Yes  | 16        | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 3355      | 29.03%  |
| 4.01-8.0    | 3127      | 27.05%  |
| 8.01-16.0   | 1535      | 13.28%  |
| 1.01-2.0    | 1414      | 12.23%  |
| 16.01-24.0  | 839       | 7.26%   |
| 2.01-3.0    | 764       | 6.61%   |
| 0.51-1.0    | 258       | 2.23%   |
| 32.01-64.0  | 185       | 1.6%    |
| 24.01-32.0  | 51        | 0.44%   |
| 64.01-256.0 | 16        | 0.14%   |
| 0.01-0.5    | 12        | 0.1%    |
| Unknown     | 3         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 4911      | 38.71%  |
| 0.51-1.0   | 3879      | 30.57%  |
| 2.01-3.0   | 1835      | 14.46%  |
| 3.01-4.0   | 804       | 6.34%   |
| 4.01-8.0   | 767       | 6.05%   |
| 0.01-0.5   | 288       | 2.27%   |
| 8.01-16.0  | 173       | 1.36%   |
| 16.01-24.0 | 14        | 0.11%   |
| Unknown    | 9         | 0.07%   |
| 24.01-32.0 | 7         | 0.06%   |
| 32.01-64.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 8923      | 77.09%  |
| 2       | 2316      | 20.01%  |
| 3       | 237       | 2.05%   |
| 0       | 81        | 0.7%    |
| 4       | 12        | 0.1%    |
| 5       | 5         | 0.04%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6002      | 52.64%  |
| Yes       | 5400      | 47.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 9775      | 86.72%  |
| No        | 1497      | 13.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 11022     | 97.83%  |
| No        | 245       | 2.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7951      | 69.62%  |
| No        | 3470      | 30.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 11254     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 2441      | 20.15%  |
| St Petersburg    | 1094      | 9.03%   |
| Krasnodar        | 369       | 3.05%   |
| Novosibirsk      | 368       | 3.04%   |
| Pecherskoye      | 337       | 2.78%   |
| Voronezh         | 322       | 2.66%   |
| Yekaterinburg    | 320       | 2.64%   |
| Nizhniy Novgorod | 233       | 1.92%   |
| Samara           | 217       | 1.79%   |
| Perm             | 202       | 1.67%   |
| Chelyabinsk      | 198       | 1.63%   |
| Rostov-on-Don    | 187       | 1.54%   |
| Kazan’         | 149       | 1.23%   |
| Krasnoyarsk      | 141       | 1.16%   |
| Saratov          | 131       | 1.08%   |
| Ufa              | 127       | 1.05%   |
| Omsk             | 109       | 0.9%    |
| Khabarovsk       | 103       | 0.85%   |
| Tyumen           | 97        | 0.8%    |
| Vladivostok      | 96        | 0.79%   |
| Barnaul          | 96        | 0.79%   |
| Volgograd        | 95        | 0.78%   |
| Irkutsk          | 87        | 0.72%   |
| Kaliningrad      | 86        | 0.71%   |
| Yaroslavl        | 84        | 0.69%   |
| Stavropol        | 79        | 0.65%   |
| Kirov            | 75        | 0.62%   |
| Tula             | 69        | 0.57%   |
| Tver             | 66        | 0.54%   |
| Ryazan           | 66        | 0.54%   |
| Kemerovo         | 66        | 0.54%   |
| Ulyanovsk        | 65        | 0.54%   |
| Belgorod         | 65        | 0.54%   |
| Tomsk            | 61        | 0.5%    |
| Surgut           | 61        | 0.5%    |
| Penza            | 56        | 0.46%   |
| Izhevsk          | 54        | 0.45%   |
| Ivanovo          | 54        | 0.45%   |
| Astrakhan        | 54        | 0.45%   |
| Novokuznetsk     | 51        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2539      | 3380   | 18.41%  |
| Seagate             | 2163      | 2827   | 15.69%  |
| Toshiba             | 1370      | 1746   | 9.94%   |
| Samsung Electronics | 1252      | 1673   | 9.08%   |
| Hitachi             | 936       | 1216   | 6.79%   |
| Kingston            | 705       | 862    | 5.11%   |
| Unknown             | 561       | 717    | 4.07%   |
| HGST                | 542       | 753    | 3.93%   |
| SanDisk             | 417       | 542    | 3.02%   |
| SK hynix            | 347       | 447    | 2.52%   |
| Intel               | 298       | 381    | 2.16%   |
| A-DATA Technology   | 236       | 369    | 1.71%   |
| China               | 202       | 262    | 1.46%   |
| Micron Technology   | 150       | 188    | 1.09%   |
| Fujitsu             | 136       | 164    | 0.99%   |
| SPCC                | 113       | 160    | 0.82%   |
| Crucial             | 111       | 138    | 0.8%    |
| Smartbuy            | 90        | 104    | 0.65%   |
| OCZ                 | 86        | 102    | 0.62%   |
| KIOXIA              | 85        | 102    | 0.62%   |
| Apacer              | 85        | 101    | 0.62%   |
| Plextor             | 79        | 101    | 0.57%   |
| KingSpec            | 79        | 98     | 0.57%   |
| Transcend           | 77        | 101    | 0.56%   |
| HUAWEI              | 69        | 77     | 0.5%    |
| Phison              | 51        | 57     | 0.37%   |
| AMD                 | 44        | 50     | 0.32%   |
| Patriot             | 42        | 48     | 0.3%    |
| Apple               | 42        | 54     | 0.3%    |
| Netac               | 35        | 47     | 0.25%   |
| GOODRAM             | 33        | 36     | 0.24%   |
| Unknown             | 33        | 36     | 0.24%   |
| Silicon Motion      | 32        | 41     | 0.23%   |
| KingDian            | 31        | 44     | 0.22%   |
| Gigabyte Technology | 30        | 34     | 0.22%   |
| Corsair             | 30        | 38     | 0.22%   |
| JMicron Technology  | 28        | 29     | 0.2%    |
| BIWIN               | 27        | 28     | 0.2%    |
| LITEON              | 25        | 31     | 0.18%   |
| Phison Electronics  | 22        | 26     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB               | 253       | 1.79%   |
| Seagate ST500LT012-1DG142 500GB        | 250       | 1.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 242       | 1.71%   |
| Seagate ST9500325AS 500GB              | 200       | 1.42%   |
| Seagate ST1000LM035-1RK172 1TB         | 166       | 1.18%   |
| Seagate ST9320325AS 320GB              | 158       | 1.12%   |
| HGST HTS545050A7E680 500GB             | 146       | 1.03%   |
| Toshiba MQ01ABD100 1TB                 | 127       | 0.9%    |
| Toshiba MQ04ABF100 1TB                 | 108       | 0.76%   |
| Hitachi HTS543232A7A384 320GB          | 103       | 0.73%   |
| Seagate ST500LT012-9WS142 500GB        | 99        | 0.7%    |
| Seagate ST9250315AS 250GB              | 92        | 0.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 91        | 0.64%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 89        | 0.63%   |
| Seagate ST320LT020-9YG142 320GB        | 89        | 0.63%   |
| HGST HTS545050A7E380 500GB             | 89        | 0.63%   |
| Kingston SA400S37240G 240GB SSD        | 88        | 0.62%   |
| Kingston SA400S37120G 120GB SSD        | 88        | 0.62%   |
| Hitachi HTS547550A9E384 500GB          | 84        | 0.59%   |
| Hitachi HTS545025B9A300 250GB          | 84        | 0.59%   |
| HGST HTS541010A9E680 1TB               | 84        | 0.59%   |
| HGST HTS721010A9E630 1TB               | 78        | 0.55%   |
| WDC WD3200BPVT-22JJ5T0 320GB           | 77        | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB               | 76        | 0.54%   |
| Hitachi HTS547575A9E384 752GB          | 74        | 0.52%   |
| WDC WD5000LPCX-21VHAT0 500GB           | 70        | 0.5%    |
| Kingston SV300S37A120G 120GB SSD       | 68        | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 66        | 0.47%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 64        | 0.45%   |
| Toshiba MQ01ABD075 752GB               | 59        | 0.42%   |
| Toshiba MQ01ABD050 500GB               | 57        | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 56        | 0.4%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 55        | 0.39%   |
| Samsung HM321HI 320GB                  | 54        | 0.38%   |
| Hitachi HTS545050A7E380 500GB          | 53        | 0.38%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 52        | 0.37%   |
| Seagate ST1000LM048-2E7172 1TB         | 50        | 0.35%   |
| Samsung SSD 860 EVO 250GB              | 50        | 0.35%   |
| Hitachi HTS545032B9A300 320GB          | 50        | 0.35%   |
| A-DATA SU800 512GB SSD                 | 50        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2152      | 2810   | 29.14%  |
| WDC                 | 2123      | 2845   | 28.74%  |
| Toshiba             | 1213      | 1547   | 16.42%  |
| Hitachi             | 936       | 1216   | 12.67%  |
| HGST                | 542       | 753    | 7.34%   |
| Samsung Electronics | 226       | 272    | 3.06%   |
| Fujitsu             | 135       | 163    | 1.83%   |
| Unknown             | 18        | 24     | 0.24%   |
| JMicron Technology  | 16        | 17     | 0.22%   |
| IBM/Hitachi         | 6         | 6      | 0.08%   |
| Apple               | 4         | 4      | 0.05%   |
| HGST HTS            | 3         | 3      | 0.04%   |
| KESU                | 2         | 2      | 0.03%   |
| ZALMAN              | 1         | 1      | 0.01%   |
| WD MediaMax         | 1         | 2      | 0.01%   |
| SILICONMOTION       | 1         | 1      | 0.01%   |
| QNAP                | 1         | 2      | 0.01%   |
| PHD 3.0             | 1         | 1      | 0.01%   |
| OEM                 | 1         | 2      | 0.01%   |
| MARSHAL             | 1         | 1      | 0.01%   |
| IBM                 | 1         | 1      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 562       | 687    | 15.58%  |
| Samsung Electronics | 535       | 714    | 14.83%  |
| SanDisk             | 259       | 347    | 7.18%   |
| WDC                 | 248       | 288    | 6.87%   |
| A-DATA Technology   | 207       | 333    | 5.74%   |
| China               | 202       | 262    | 5.6%    |
| SPCC                | 111       | 158    | 3.08%   |
| Intel               | 107       | 140    | 2.97%   |
| Crucial             | 106       | 132    | 2.94%   |
| Smartbuy            | 87        | 101    | 2.41%   |
| OCZ                 | 86        | 102    | 2.38%   |
| Plextor             | 79        | 101    | 2.19%   |
| KingSpec            | 79        | 98     | 2.19%   |
| SK hynix            | 77        | 96     | 2.13%   |
| Apacer              | 75        | 90     | 2.08%   |
| Transcend           | 74        | 95     | 2.05%   |
| Toshiba             | 67        | 85     | 1.86%   |
| Micron Technology   | 58        | 86     | 1.61%   |
| Patriot             | 42        | 48     | 1.16%   |
| AMD                 | 42        | 47     | 1.16%   |
| GOODRAM             | 33        | 36     | 0.91%   |
| Apple               | 31        | 37     | 0.86%   |
| KingDian            | 30        | 43     | 0.83%   |
| Netac               | 29        | 37     | 0.8%    |
| Corsair             | 28        | 36     | 0.78%   |
| LITEON              | 21        | 27     | 0.58%   |
| LITEONIT            | 20        | 34     | 0.55%   |
| Unknown             | 16        | 18     | 0.44%   |
| XrayDisk            | 14        | 17     | 0.39%   |
| Gigabyte Technology | 14        | 16     | 0.39%   |
| Londisk             | 13        | 16     | 0.36%   |
| Kingmax             | 12        | 24     | 0.33%   |
| TO Exter            | 10        | 11     | 0.28%   |
| KingFast            | 10        | 12     | 0.28%   |
| Zheino              | 9         | 11     | 0.25%   |
| Hewlett-Packard     | 9         | 14     | 0.25%   |
| Team                | 8         | 10     | 0.22%   |
| Foxline             | 7         | 7      | 0.19%   |
| FORESEE             | 7         | 7      | 0.19%   |
| ShiJi               | 6         | 6      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 7103      | 9675   | 53.75%  |
| SSD     | 3385      | 4647   | 25.61%  |
| NVMe    | 1976      | 2626   | 14.95%  |
| MMC     | 574       | 749    | 4.34%   |
| Unknown | 178       | 194    | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 9348      | 14168  | 76.66%  |
| NVMe | 1967      | 2611   | 16.13%  |
| MMC  | 574       | 749    | 4.71%   |
| SAS  | 305       | 363    | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7746      | 11127  | 77.41%  |
| 0.51-1.0   | 2174      | 3080   | 21.72%  |
| 1.01-2.0   | 74        | 93     | 0.74%   |
| 4.01-10.0  | 7         | 16     | 0.07%   |
| 3.01-4.0   | 4         | 4      | 0.04%   |
| 2.01-3.0   | 1         | 1      | 0.01%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 3629      | 29.51%  |
| 251-500        | 3212      | 26.12%  |
| 1-20           | 1384      | 11.25%  |
| 501-1000       | 1297      | 10.55%  |
| 51-100         | 1127      | 9.16%   |
| 21-50          | 882       | 7.17%   |
| 1001-2000      | 405       | 3.29%   |
| Unknown        | 253       | 2.06%   |
| 2001-3000      | 76        | 0.62%   |
| More than 3000 | 34        | 0.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 7227      | 57.46%  |
| 21-50          | 1698      | 13.5%   |
| 101-250        | 1212      | 9.64%   |
| 51-100         | 1131      | 8.99%   |
| 251-500        | 655       | 5.21%   |
| 501-1000       | 295       | 2.35%   |
| Unknown        | 253       | 2.01%   |
| 1001-2000      | 83        | 0.66%   |
| 2001-3000      | 12        | 0.1%    |
| More than 3000 | 10        | 0.08%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 135       | 186    | 4.61%   |
| Seagate ST500LT012-9WS142 500GB     | 90        | 108    | 3.07%   |
| Seagate ST9320325AS 320GB           | 87        | 111    | 2.97%   |
| HGST HTS545050A7E680 500GB          | 73        | 107    | 2.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 70        | 84     | 2.39%   |
| Seagate ST9250315AS 250GB           | 64        | 80     | 2.18%   |
| Seagate ST500LT012-1DG142 500GB     | 64        | 78     | 2.18%   |
| Seagate ST320LT020-9YG142 320GB     | 54        | 79     | 1.84%   |
| HGST HTS545050A7E380 500GB          | 45        | 71     | 1.54%   |
| Hitachi HTS545025B9A300 250GB       | 42        | 50     | 1.43%   |
| Hitachi HTS543232A7A384 320GB       | 40        | 46     | 1.36%   |
| Seagate ST320LT012-9WS14C 320GB     | 38        | 51     | 1.3%    |
| Hitachi HTS547550A9E384 500GB       | 35        | 48     | 1.19%   |
| Hitachi HTS547575A9E384 752GB       | 34        | 47     | 1.16%   |
| Toshiba MQ01ABD050 500GB            | 29        | 36     | 0.99%   |
| Toshiba MQ01ABF050 500GB            | 28        | 36     | 0.96%   |
| Hitachi HTS541612J9SA00 120GB       | 28        | 38     | 0.96%   |
| Hitachi HTS541680J9SA00 80GB        | 25        | 29     | 0.85%   |
| Toshiba MK3265GSX 320GB             | 24        | 30     | 0.82%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 24        | 28     | 0.82%   |
| Seagate ST9500420AS 500GB           | 23        | 36     | 0.78%   |
| HGST HTS541010A9E680 1TB            | 23        | 37     | 0.78%   |
| Samsung Electronics HM160HI 160GB   | 22        | 24     | 0.75%   |
| Hitachi HTS545032B9A300 320GB       | 22        | 28     | 0.75%   |
| Hitachi HTS545050A7E380 500GB       | 21        | 31     | 0.72%   |
| Toshiba MQ01ABD100 1TB              | 19        | 26     | 0.65%   |
| Hitachi HTS545050B9A300 500GB       | 19        | 25     | 0.65%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 18        | 19     | 0.61%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 18        | 24     | 0.61%   |
| Hitachi HTS542512K9SA00 120GB       | 18        | 23     | 0.61%   |
| Samsung Electronics HM321HI 320GB   | 16        | 21     | 0.55%   |
| Hitachi HTS542516K9SA00 160GB       | 16        | 26     | 0.55%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 15        | 18     | 0.51%   |
| WDC WD2500BEVT-22A23T0 250GB        | 15        | 18     | 0.51%   |
| Toshiba MQ01ABD075 752GB            | 15        | 20     | 0.51%   |
| Toshiba MK3259GSXP 320GB            | 15        | 25     | 0.51%   |
| Seagate ST9160821AS 160GB           | 15        | 17     | 0.51%   |
| Samsung Electronics HM250HI 250GB   | 15        | 17     | 0.51%   |
| Hitachi HTS542525K9SA00 250GB       | 15        | 20     | 0.51%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 14        | 15     | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 885       | 1129   | 30.35%  |
| Hitachi                      | 506       | 639    | 17.35%  |
| WDC                          | 464       | 609    | 15.91%  |
| Toshiba                      | 417       | 534    | 14.3%   |
| HGST                         | 181       | 269    | 6.21%   |
| Samsung Electronics          | 118       | 139    | 4.05%   |
| Kingston                     | 45        | 55     | 1.54%   |
| Fujitsu                      | 42        | 58     | 1.44%   |
| SanDisk                      | 40        | 49     | 1.37%   |
| SK hynix                     | 22        | 30     | 0.75%   |
| Intel                        | 20        | 32     | 0.69%   |
| A-DATA Technology            | 19        | 25     | 0.65%   |
| OCZ                          | 15        | 15     | 0.51%   |
| China                        | 14        | 20     | 0.48%   |
| KingSpec                     | 11        | 12     | 0.38%   |
| SPCC                         | 10        | 11     | 0.34%   |
| Crucial                      | 10        | 13     | 0.34%   |
| LITEON                       | 9         | 10     | 0.31%   |
| Micron Technology            | 8         | 14     | 0.27%   |
| Corsair                      | 8         | 8      | 0.27%   |
| Plextor                      | 7         | 9      | 0.24%   |
| LITEONIT                     | 6         | 12     | 0.21%   |
| IBM/Hitachi                  | 5         | 5      | 0.17%   |
| AMD                          | 5         | 7      | 0.17%   |
| Transcend                    | 3         | 3      | 0.1%    |
| Smartbuy                     | 3         | 3      | 0.1%    |
| Kingmax                      | 3         | 3      | 0.1%    |
| KingDian                     | 3         | 6      | 0.1%    |
| Apple                        | 3         | 3      | 0.1%    |
| Unknown                      | 3         | 4      | 0.1%    |
| Team                         | 2         | 2      | 0.07%   |
| SSSTC                        | 2         | 2      | 0.07%   |
| OCZ-VERTEX3                  | 2         | 2      | 0.07%   |
| Netac                        | 2         | 3      | 0.07%   |
| Mushkin                      | 2         | 2      | 0.07%   |
| HGST HTS                     | 2         | 2      | 0.07%   |
| Zheino                       | 1         | 1      | 0.03%   |
| XrayDisk                     | 1         | 1      | 0.03%   |
| Unknown                      | 1         | 1      | 0.03%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 885       | 1129   | 34.32%  |
| Hitachi             | 506       | 639    | 19.62%  |
| WDC                 | 444       | 589    | 17.22%  |
| Toshiba             | 414       | 531    | 16.05%  |
| HGST                | 181       | 269    | 7.02%   |
| Samsung Electronics | 99        | 119    | 3.84%   |
| Fujitsu             | 42        | 58     | 1.63%   |
| IBM/Hitachi         | 5         | 5      | 0.19%   |
| HGST HTS            | 2         | 2      | 0.08%   |
| MARSHAL             | 1         | 1      | 0.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2546      | 3342   | 88.37%  |
| SSD  | 319       | 399    | 11.07%  |
| NVMe | 16        | 19     | 0.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-22ZCT0 160GB        | 4         | 5      | 4.26%   |
| Seagate ST9500325AS 500GB          | 4         | 4      | 4.26%   |
| Samsung Electronics HM321HI 320GB  | 4         | 5      | 4.26%   |
| HGST HTS721010A9E630 1TB           | 4         | 5      | 4.26%   |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 3.19%   |
| Seagate ST9320325AS 320GB          | 3         | 3      | 3.19%   |
| HGST HTS545050A7E680 500GB         | 3         | 3      | 3.19%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 2         | 2      | 2.13%   |
| WDC WD1600BEVS-22RST0 160GB        | 2         | 2      | 2.13%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 2.13%   |
| Toshiba MK6465GSX 640GB            | 2         | 2      | 2.13%   |
| Toshiba MK3259GSXP 320GB           | 2         | 2      | 2.13%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 2.13%   |
| Samsung Electronics HM160HI 160GB  | 2         | 2      | 2.13%   |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 2.13%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 3      | 2.13%   |
| Hitachi HTS543225A7A384 250GB      | 2         | 3      | 2.13%   |
| HGST HTS541010A9E680 1TB           | 2         | 2      | 2.13%   |
| WDC WD800BEVS-22RST0 80GB          | 1         | 1      | 1.06%   |
| WDC WD7500BPVT-22HXZT3 752GB       | 1         | 1      | 1.06%   |
| WDC WD7500BPVT-22HXZT1 752GB       | 1         | 1      | 1.06%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB   | 1         | 1      | 1.06%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BPVT-80HXZT1 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BPVT-24HXZT3 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BEVT-35ZAT0 500GB        | 1         | 1      | 1.06%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 1      | 1.06%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 1.06%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 1.06%   |
| WDC WD3200BEVS-0 320GB             | 1         | 1      | 1.06%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-35A23T0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-22ZCT0 250GB        | 1         | 1      | 1.06%   |
| WDC WD1600BEVT-75ZCT2 160GB        | 1         | 1      | 1.06%   |
| WDC WD1200BEVS-07LAT0 120GB        | 1         | 1      | 1.06%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 1.06%   |
| Toshiba MK8037GSX 80GB             | 1         | 1      | 1.06%   |
| Toshiba MK8025GAL 80GB             | 1         | 2      | 1.06%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 28     | 28.72%  |
| Toshiba             | 16        | 18     | 17.02%  |
| Seagate             | 16        | 18     | 17.02%  |
| Samsung Electronics | 14        | 15     | 14.89%  |
| HGST                | 11        | 13     | 11.7%   |
| Hitachi             | 8         | 10     | 8.51%   |
| Fujitsu             | 1         | 1      | 1.06%   |
| Apple               | 1         | 2      | 1.06%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 6706      | 10026  | 54.12%  |
| Malfunc  | 2843      | 3760   | 22.94%  |
| Detected | 2747      | 3999   | 22.17%  |
| Failed   | 94        | 105    | 0.76%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8108      | 65.75%  |
| AMD                              | 2066      | 16.75%  |
| Samsung Electronics              | 537       | 4.35%   |
| SanDisk                          | 307       | 2.49%   |
| SK hynix                         | 256       | 2.08%   |
| Kingston Technology Company      | 148       | 1.2%    |
| Nvidia                           | 119       | 0.96%   |
| Phison Electronics               | 107       | 0.87%   |
| Toshiba America Info Systems     | 96        | 0.78%   |
| KIOXIA                           | 94        | 0.76%   |
| Micron Technology                | 92        | 0.75%   |
| Silicon Integrated Systems [SiS] | 75        | 0.61%   |
| Union Memory (Shenzhen)          | 55        | 0.45%   |
| Silicon Motion                   | 46        | 0.37%   |
| Solid State Storage Technology   | 36        | 0.29%   |
| JMicron Technology               | 32        | 0.26%   |
| ADATA Technology                 | 27        | 0.22%   |
| Realtek Semiconductor            | 23        | 0.19%   |
| INNOGRIT                         | 20        | 0.16%   |
| Shenzhen Longsys Electronics     | 16        | 0.13%   |
| VIA Technologies                 | 12        | 0.1%    |
| Micron/Crucial Technology        | 7         | 0.06%   |
| Lite-On Technology               | 7         | 0.06%   |
| Lenovo                           | 6         | 0.05%   |
| Apple                            | 6         | 0.05%   |
| Yangtze Memory Technologies      | 5         | 0.04%   |
| ASMedia Technology               | 5         | 0.04%   |
| O2 Micro                         | 4         | 0.03%   |
| Netac Technology                 | 4         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.02%   |
| Marvell Technology Group         | 3         | 0.02%   |
| Zhaoxin                          | 2         | 0.02%   |
| Silicon Image                    | 2         | 0.02%   |
| Seagate Technology               | 2         | 0.02%   |
| Unknown                          | 2         | 0.02%   |
| ULi Electronics                  | 1         | 0.01%   |
| Transcend                        | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 1410      | 10.34%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1300      | 9.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 907       | 6.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 639       | 4.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 514       | 3.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 496       | 3.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 418       | 3.07%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 393       | 2.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 367       | 2.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 311       | 2.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 305       | 2.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 295       | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 245       | 1.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 240       | 1.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 232       | 1.7%    |
| Samsung NVMe SSD Controller 980                                                  | 208       | 1.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 195       | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 174       | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 171       | 1.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 163       | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 156       | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 142       | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                            | 123       | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 118       | 0.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 113       | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 112       | 0.82%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 111       | 0.81%   |
| Intel Volume Management Device NVMe RAID Controller                              | 109       | 0.8%    |
| AMD SB600 IDE                                                                    | 108       | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 107       | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 106       | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 104       | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                              | 103       | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 93        | 0.68%   |
| Micron Non-Volatile memory controller                                            | 92        | 0.67%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 90        | 0.66%   |
| Intel SSD 660P Series                                                            | 89        | 0.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 88        | 0.65%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 87        | 0.64%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 87        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 9107      | 69.76%  |
| NVMe | 1989      | 15.24%  |
| IDE  | 1534      | 11.75%  |
| RAID | 424       | 3.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 8807      | 78.24%  |
| AMD          | 2437      | 21.65%  |
| CentaurHauls | 5         | 0.04%   |
| ARM          | 4         | 0.04%   |
| Unknown      | 2         | 0.02%   |
| PowerBook5,6 | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 157       | 1.39%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 143       | 1.27%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 141       | 1.25%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 140       | 1.24%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 128       | 1.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 126       | 1.12%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 122       | 1.08%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 114       | 1.01%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 108       | 0.96%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 107       | 0.95%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 106       | 0.94%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 101       | 0.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 99        | 0.88%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 98        | 0.87%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 98        | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 97        | 0.86%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 97        | 0.86%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 92        | 0.81%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 89        | 0.79%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 87        | 0.77%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 86        | 0.76%   |
| AMD E-450 APU with Radeon HD Graphics         | 85        | 0.75%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 81        | 0.72%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 78        | 0.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 78        | 0.69%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 76        | 0.67%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 76        | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 75        | 0.66%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 72        | 0.64%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 71        | 0.63%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 67        | 0.59%   |
| AMD A10-4600M APU with Radeon HD Graphics     | 67        | 0.59%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 66        | 0.58%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 64        | 0.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 63        | 0.56%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 62        | 0.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 61        | 0.54%   |
| Intel Atom CPU N570 @ 1.66GHz                 | 60        | 0.53%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 59        | 0.52%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 58        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2154      | 19.09%  |
| Intel Core i3                  | 1473      | 13.05%  |
| Intel Core i7                  | 1098      | 9.73%   |
| Intel Celeron                  | 850       | 7.53%   |
| Intel Pentium                  | 808       | 7.16%   |
| Intel Atom                     | 696       | 6.17%   |
| Intel Core 2 Duo               | 610       | 5.41%   |
| AMD Ryzen 5                    | 414       | 3.67%   |
| Other                          | 375       | 3.32%   |
| AMD A6                         | 239       | 2.12%   |
| Intel Pentium Dual-Core        | 199       | 1.76%   |
| AMD Ryzen 7                    | 198       | 1.75%   |
| AMD A8                         | 163       | 1.44%   |
| AMD A4                         | 161       | 1.43%   |
| AMD A10                        | 150       | 1.33%   |
| AMD E                          | 147       | 1.3%    |
| AMD E1                         | 117       | 1.04%   |
| AMD Ryzen 3                    | 110       | 0.97%   |
| Intel Genuine                  | 103       | 0.91%   |
| Intel Pentium Dual             | 98        | 0.87%   |
| AMD E2                         | 96        | 0.85%   |
| Intel Core 2                   | 93        | 0.82%   |
| Intel Celeron M                | 73        | 0.65%   |
| AMD Phenom II                  | 70        | 0.62%   |
| Intel Celeron Dual-Core        | 69        | 0.61%   |
| AMD Turion 64 X2 Mobile        | 67        | 0.59%   |
| Intel Pentium Silver           | 65        | 0.58%   |
| Intel Pentium M                | 57        | 0.51%   |
| AMD Athlon                     | 41        | 0.36%   |
| AMD C-60                       | 36        | 0.32%   |
| AMD Athlon II                  | 34        | 0.3%    |
| AMD Athlon X2                  | 27        | 0.24%   |
| AMD Turion II Dual-Core        | 25        | 0.22%   |
| AMD Ryzen 9                    | 25        | 0.22%   |
| AMD Athlon 64 X2               | 25        | 0.22%   |
| AMD Turion X2 Dual-Core Mobile | 23        | 0.2%    |
| AMD C-50                       | 21        | 0.19%   |
| AMD Ryzen 7 PRO                | 20        | 0.18%   |
| Intel Core Duo                 | 19        | 0.17%   |
| AMD Athlon II Dual-Core        | 18        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 6912      | 61.02%  |
| 4       | 2755      | 24.32%  |
| 1       | 693       | 6.12%   |
| 6       | 386       | 3.41%   |
| Unknown | 287       | 2.53%   |
| 8       | 239       | 2.11%   |
| 3       | 25        | 0.22%   |
| 14      | 15        | 0.13%   |
| 12      | 10        | 0.09%   |
| 10      | 4         | 0.04%   |
| 192     | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 11240     | 99.81%  |
| Unknown | 15        | 0.13%   |
| 2       | 4         | 0.04%   |
| 4       | 2         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 6415      | 56.53%  |
| 1       | 4645      | 40.93%  |
| Unknown | 287       | 2.53%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 10773     | 95.56%  |
| 32-bit         | 370       | 3.28%   |
| Unknown        | 129       | 1.14%   |
| 64-bit         | 2         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 1271      | 11.07%  |
| Unknown    | 1035      | 9.01%   |
| 0x306a9    | 1028      | 8.95%   |
| 0x1067a    | 466       | 4.06%   |
| 0x20655    | 449       | 3.91%   |
| 0x6fd      | 334       | 2.91%   |
| 0x106ca    | 303       | 2.64%   |
| 0x40651    | 298       | 2.59%   |
| 0x806ec    | 291       | 2.53%   |
| 0x806ea    | 274       | 2.39%   |
| 0x30678    | 268       | 2.33%   |
| 0x406e3    | 237       | 2.06%   |
| 0x306c3    | 236       | 2.05%   |
| 0x806e9    | 213       | 1.85%   |
| 0x806c1    | 198       | 1.72%   |
| 0x906ea    | 186       | 1.62%   |
| 0x06001119 | 175       | 1.52%   |
| 0x306d4    | 172       | 1.5%    |
| 0x05000119 | 170       | 1.48%   |
| 0x406c4    | 168       | 1.46%   |
| 0x08108109 | 159       | 1.38%   |
| 0x10676    | 155       | 1.35%   |
| 0x07030105 | 151       | 1.31%   |
| 0x20652    | 143       | 1.24%   |
| 0x03000027 | 140       | 1.22%   |
| 0x06006705 | 138       | 1.2%    |
| 0x010000c8 | 129       | 1.12%   |
| 0x30661    | 120       | 1.04%   |
| 0x08108102 | 116       | 1.01%   |
| 0x106c2    | 115       | 1%      |
| 0x406c3    | 108       | 0.94%   |
| 0x10661    | 104       | 0.91%   |
| 0x506c9    | 95        | 0.83%   |
| 0x0a50000c | 90        | 0.78%   |
| 0x706a1    | 89        | 0.77%   |
| 0x706e5    | 86        | 0.75%   |
| 0x08600106 | 84        | 0.73%   |
| 0x6e8      | 78        | 0.68%   |
| 0x906e9    | 75        | 0.65%   |
| 0x6f6      | 75        | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 1332      | 11.81%  |
| KabyLake         | 1302      | 11.54%  |
| IvyBridge        | 1080      | 9.57%   |
| Penryn           | 633       | 5.61%   |
| Core             | 625       | 5.54%   |
| Westmere         | 616       | 5.46%   |
| Silvermont       | 597       | 5.29%   |
| Haswell          | 589       | 5.22%   |
| Bonnell          | 520       | 4.61%   |
| Skylake          | 306       | 2.71%   |
| Zen+             | 291       | 2.58%   |
| Excavator        | 268       | 2.38%   |
| Unknown          | 263       | 2.33%   |
| Bobcat           | 251       | 2.22%   |
| TigerLake        | 240       | 2.13%   |
| Zen 2            | 206       | 1.83%   |
| Piledriver       | 202       | 1.79%   |
| Puma             | 196       | 1.74%   |
| Broadwell        | 190       | 1.68%   |
| K10              | 188       | 1.67%   |
| P6               | 179       | 1.59%   |
| Goldmont plus    | 158       | 1.4%    |
| K10 Llano        | 157       | 1.39%   |
| K8 Hammer        | 143       | 1.27%   |
| Zen 3            | 123       | 1.09%   |
| Icelake          | 119       | 1.05%   |
| Goldmont         | 112       | 0.99%   |
| Jaguar           | 92        | 0.82%   |
| CometLake        | 79        | 0.7%    |
| Zen              | 70        | 0.62%   |
| K8 & K10 hybrid  | 69        | 0.61%   |
| Alderlake Hybrid | 26        | 0.23%   |
| Nehalem          | 23        | 0.2%    |
| Tremont          | 16        | 0.14%   |
| Steamroller      | 15        | 0.13%   |
| NetBurst         | 5         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7566      | 52.15%  |
| AMD                              | 3564      | 24.56%  |
| Nvidia                           | 3333      | 22.97%  |
| Silicon Integrated Systems [SiS] | 33        | 0.23%   |
| VIA Technologies                 | 9         | 0.06%   |
| Zhaoxin                          | 2         | 0.01%   |
| ATI Technologies                 | 2         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1195      | 7.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1050      | 6.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 338       | 2.17%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 336       | 2.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 324       | 2.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 318       | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 304       | 1.95%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 303       | 1.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 301       | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 293       | 1.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 246       | 1.58%   |
| Intel UHD Graphics 620                                                                   | 236       | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 233       | 1.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 233       | 1.5%    |
| Intel HD Graphics 620                                                                    | 227       | 1.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 218       | 1.4%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 217       | 1.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 207       | 1.33%   |
| AMD Renoir                                                                               | 205       | 1.32%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 204       | 1.31%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 203       | 1.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 200       | 1.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 190       | 1.22%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 187       | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 176       | 1.13%   |
| Intel HD Graphics 5500                                                                   | 155       | 1%      |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 152       | 0.98%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 150       | 0.96%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 138       | 0.89%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 123       | 0.79%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 121       | 0.78%   |
| AMD Lucienne                                                                             | 117       | 0.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 113       | 0.73%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 111       | 0.71%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 108       | 0.69%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 105       | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 104       | 0.67%   |
| Nvidia GM108M [GeForce 840M]                                                             | 104       | 0.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 101       | 0.65%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 101       | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 4476      | 39.63%  |
| Intel + Nvidia     | 2545      | 22.53%  |
| 1 x AMD            | 2264      | 20.04%  |
| 1 x Nvidia         | 635       | 5.62%   |
| 2 x AMD            | 594       | 5.26%   |
| Intel + AMD        | 558       | 4.94%   |
| AMD + Nvidia       | 154       | 1.36%   |
| 1 x SiS            | 33        | 0.29%   |
| Other              | 15        | 0.13%   |
| 1 x VIA            | 9         | 0.08%   |
| 2 x Intel          | 6         | 0.05%   |
| 2 x Nvidia         | 3         | 0.03%   |
| 1 x Zhaoxin        | 2         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 9961      | 86.61%  |
| Proprietary | 990       | 8.61%   |
| Unknown     | 550       | 4.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3971      | 33.83%  |
| 1.01-2.0   | 3269      | 27.85%  |
| 0.01-0.5   | 2821      | 24.04%  |
| 0.51-1.0   | 897       | 7.64%   |
| 3.01-4.0   | 675       | 5.75%   |
| 5.01-6.0   | 60        | 0.51%   |
| 7.01-8.0   | 22        | 0.19%   |
| 2.01-3.0   | 19        | 0.16%   |
| 8.01-16.0  | 3         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 2459      | 21.41%  |
| LG Display              | 1784      | 15.54%  |
| Samsung Electronics     | 1550      | 13.5%   |
| Chimei Innolux          | 1327      | 11.56%  |
| BOE                     | 1298      | 11.3%   |
| Chi Mei Optoelectronics | 788       | 6.86%   |
| LG Philips              | 221       | 1.92%   |
| Lenovo                  | 188       | 1.64%   |
| HannStar                | 174       | 1.52%   |
| PANDA                   | 137       | 1.19%   |
| Goldstar                | 121       | 1.05%   |
| Dell                    | 115       | 1%      |
| CPT                     | 115       | 1%      |
| InfoVision              | 113       | 0.98%   |
| BenQ                    | 98        | 0.85%   |
| Sharp                   | 93        | 0.81%   |
| Apple                   | 93        | 0.81%   |
| Acer                    | 83        | 0.72%   |
| Philips                 | 64        | 0.56%   |
| Sony                    | 59        | 0.51%   |
| AOC                     | 57        | 0.5%    |
| Hewlett-Packard         | 48        | 0.42%   |
| Ancor Communications    | 45        | 0.39%   |
| ViewSonic               | 40        | 0.35%   |
| Iiyama                  | 32        | 0.28%   |
| CSO                     | 32        | 0.28%   |
| InnoLux Display         | 30        | 0.26%   |
| Quanta Display          | 26        | 0.23%   |
| NEC Computers           | 24        | 0.21%   |
| Toshiba                 | 23        | 0.2%    |
| TMX                     | 22        | 0.19%   |
| Panasonic               | 11        | 0.1%    |
| Nvidia                  | 11        | 0.1%    |
| Unknown                 | 10        | 0.09%   |
| ASUSTek Computer        | 10        | 0.09%   |
| Valve                   | 8         | 0.07%   |
| S2-Tek                  | 8         | 0.07%   |
| JDI                     | 8         | 0.07%   |
| MiTAC                   | 7         | 0.06%   |
| Mi                      | 7         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 227       | 1.96%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 194       | 1.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 163       | 1.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 153       | 1.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 149       | 1.29%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 106       | 0.92%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 100       | 0.87%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 99        | 0.86%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 91        | 0.79%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 88        | 0.76%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 86        | 0.74%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 84        | 0.73%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 75        | 0.65%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 73        | 0.63%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 71        | 0.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 70        | 0.61%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 69        | 0.6%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 67        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 66        | 0.57%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 66        | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 65        | 0.56%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 63        | 0.55%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 62        | 0.54%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 59        | 0.51%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 59        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 56        | 0.48%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 55        | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 52        | 0.45%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 51        | 0.44%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 51        | 0.44%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 50        | 0.43%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 49        | 0.42%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch               | 49        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 49        | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 46        | 0.4%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 43        | 0.37%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 42        | 0.36%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 42        | 0.36%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch               | 41        | 0.35%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 40        | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4753      | 42.51%  |
| 1920x1080 (FHD)    | 3403      | 30.44%  |
| 1600x900 (HD+)     | 758       | 6.78%   |
| 1280x800 (WXGA)    | 757       | 6.77%   |
| 1024x600           | 376       | 3.36%   |
| 1440x900 (WXGA+)   | 173       | 1.55%   |
| 3840x2160 (4K)     | 158       | 1.41%   |
| 1280x1024 (SXGA)   | 122       | 1.09%   |
| 1920x1200 (WUXGA)  | 116       | 1.04%   |
| 2560x1440 (QHD)    | 97        | 0.87%   |
| 1680x1050 (WSXGA+) | 83        | 0.74%   |
| 2560x1600          | 48        | 0.43%   |
| 2160x1440          | 44        | 0.39%   |
| 1024x768 (XGA)     | 35        | 0.31%   |
| 2880x1800          | 27        | 0.24%   |
| 1360x768           | 18        | 0.16%   |
| 1280x720 (HD)      | 18        | 0.16%   |
| 2560x1080          | 16        | 0.14%   |
| 2288x1287          | 15        | 0.13%   |
| 3440x1440          | 14        | 0.13%   |
| 1680x945           | 14        | 0.13%   |
| 800x1280           | 13        | 0.12%   |
| 3200x2000          | 13        | 0.12%   |
| 3000x2000          | 11        | 0.1%    |
| 2520x1680          | 9         | 0.08%   |
| 1400x1050          | 9         | 0.08%   |
| 3840x2400          | 7         | 0.06%   |
| 3200x1800 (QHD+)   | 7         | 0.06%   |
| 1600x1200          | 7         | 0.06%   |
| Unknown            | 6         | 0.05%   |
| 3456x2160          | 5         | 0.04%   |
| 2240x1400          | 5         | 0.04%   |
| 1920x540           | 5         | 0.04%   |
| 1024x576           | 5         | 0.04%   |
| 2880x1620          | 4         | 0.04%   |
| 2256x1504          | 4         | 0.04%   |
| 3120x2080          | 3         | 0.03%   |
| 2736x1824          | 3         | 0.03%   |
| 1280x768           | 2         | 0.02%   |
| 1152x864           | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 6551      | 57.08%  |
| 17      | 1034      | 9.01%   |
| 13      | 936       | 8.16%   |
| 14      | 881       | 7.68%   |
| 10      | 382       | 3.33%   |
| 11      | 235       | 2.05%   |
| 12      | 203       | 1.77%   |
| 24      | 193       | 1.68%   |
| 23      | 167       | 1.46%   |
| 21      | 141       | 1.23%   |
| 27      | 129       | 1.12%   |
| 19      | 90        | 0.78%   |
| 16      | 89        | 0.78%   |
| 18      | 82        | 0.71%   |
| Unknown | 54        | 0.47%   |
| 20      | 34        | 0.3%    |
| 31      | 32        | 0.28%   |
| 22      | 31        | 0.27%   |
| 34      | 30        | 0.26%   |
| 8       | 23        | 0.2%    |
| 40      | 19        | 0.17%   |
| 32      | 17        | 0.15%   |
| 52      | 16        | 0.14%   |
| 54      | 15        | 0.13%   |
| 26      | 12        | 0.1%    |
| 42      | 9         | 0.08%   |
| 84      | 8         | 0.07%   |
| 72      | 8         | 0.07%   |
| 7       | 8         | 0.07%   |
| 142     | 6         | 0.05%   |
| 25      | 5         | 0.04%   |
| 48      | 4         | 0.03%   |
| 46      | 4         | 0.03%   |
| 28      | 4         | 0.03%   |
| 36      | 3         | 0.03%   |
| 9       | 3         | 0.03%   |
| 65      | 2         | 0.02%   |
| 50      | 2         | 0.02%   |
| 37      | 2         | 0.02%   |
| 29      | 2         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 7764      | 68.02%  |
| 201-300        | 1337      | 11.71%  |
| 351-400        | 1233      | 10.8%   |
| 501-600        | 484       | 4.24%   |
| 401-500        | 313       | 2.74%   |
| Unknown        | 54        | 0.47%   |
| 701-800        | 51        | 0.45%   |
| 1001-1500      | 46        | 0.4%    |
| 601-700        | 44        | 0.39%   |
| 101-200        | 23        | 0.2%    |
| 801-900        | 21        | 0.18%   |
| 1501-2000      | 18        | 0.16%   |
| 901-1000       | 12        | 0.11%   |
| 1-100          | 8         | 0.07%   |
| More than 2000 | 7         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 9227      | 85.25%  |
| 16/10   | 1237      | 11.43%  |
| 5/4     | 106       | 0.98%   |
| 3/2     | 97        | 0.9%    |
| 4/3     | 74        | 0.68%   |
| 21/9    | 34        | 0.31%   |
| Unknown | 22        | 0.2%    |
| 0.67    | 8         | 0.07%   |
| 1.00    | 6         | 0.06%   |
| 6/5     | 5         | 0.05%   |
| 0.62    | 5         | 0.05%   |
| 3.73    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 6543      | 57.02%  |
| 81-90          | 1391      | 12.12%  |
| 121-130        | 800       | 6.97%   |
| 201-250        | 448       | 3.9%    |
| 71-80          | 415       | 3.62%   |
| 41-50          | 385       | 3.36%   |
| 51-60          | 235       | 2.05%   |
| 131-140        | 190       | 1.66%   |
| 61-70          | 185       | 1.61%   |
| 151-200        | 163       | 1.42%   |
| 301-350        | 137       | 1.19%   |
| 141-150        | 120       | 1.05%   |
| 91-100         | 89        | 0.78%   |
| 351-500        | 86        | 0.75%   |
| More than 1000 | 66        | 0.58%   |
| 251-300        | 55        | 0.48%   |
| Unknown        | 54        | 0.47%   |
| 111-120        | 43        | 0.37%   |
| 501-1000       | 39        | 0.34%   |
| 1-40           | 31        | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 5173      | 45.65%  |
| 121-160       | 3408      | 30.08%  |
| 51-100        | 2116      | 18.67%  |
| 161-240       | 386       | 3.41%   |
| More than 240 | 122       | 1.08%   |
| 1-50          | 72        | 0.64%   |
| Unknown       | 54        | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 10161     | 88.72%  |
| 2     | 922       | 8.05%   |
| 0     | 330       | 2.88%   |
| 3     | 40        | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 6569      | 34.64%  |
| Qualcomm Atheros                       | 4630      | 24.42%  |
| Intel                                  | 3324      | 17.53%  |
| Broadcom                               | 1793      | 9.46%   |
| Marvell Technology Group               | 463       | 2.44%   |
| Broadcom Limited                       | 427       | 2.25%   |
| Ralink                                 | 340       | 1.79%   |
| Huawei Technologies                    | 210       | 1.11%   |
| MediaTek                               | 171       | 0.9%    |
| JMicron Technology                     | 113       | 0.6%    |
| Attansic Technology                    | 106       | 0.56%   |
| TP-Link                                | 79        | 0.42%   |
| Ralink Technology                      | 72        | 0.38%   |
| Xiaomi                                 | 67        | 0.35%   |
| Nvidia                                 | 65        | 0.34%   |
| Silicon Integrated Systems [SiS]       | 48        | 0.25%   |
| Samsung Electronics                    | 44        | 0.23%   |
| ZTE WCDMA Technologies MSM             | 34        | 0.18%   |
| D-Link                                 | 31        | 0.16%   |
| Qualcomm                               | 29        | 0.15%   |
| ASUSTek Computer                       | 27        | 0.14%   |
| Ericsson Business Mobile Networks      | 24        | 0.13%   |
| Hewlett-Packard                        | 22        | 0.12%   |
| Qualcomm Atheros Communications        | 21        | 0.11%   |
| Gemtek                                 | 20        | 0.11%   |
| ASIX Electronics                       | 20        | 0.11%   |
| Sierra Wireless                        | 19        | 0.1%    |
| Dell                                   | 16        | 0.08%   |
| Lenovo                                 | 13        | 0.07%   |
| Vimtron Electronics                    | 12        | 0.06%   |
| Fibocom                                | 12        | 0.06%   |
| VIA Technologies                       | 8         | 0.04%   |
| HTC (High Tech Computer)               | 7         | 0.04%   |
| HMD Global                             | 7         | 0.04%   |
| T & A Mobile Phones                    | 6         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 6         | 0.03%   |
| ICS Advent                             | 6         | 0.03%   |
| D-Link System                          | 6         | 0.03%   |
| Apple                                  | 6         | 0.03%   |
| NTmore                                 | 5         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 3935      | 17.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1605      | 7.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1347      | 6.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 749       | 3.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 599       | 2.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 562       | 2.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 474       | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 399       | 1.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 335       | 1.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 321       | 1.47%   |
| Broadcom BCM43142 802.11b/g/n                                           | 298       | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 295       | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 262       | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 260       | 1.19%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 232       | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 204       | 0.93%   |
| Intel Wireless 8265 / 8275                                              | 203       | 0.93%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 190       | 0.87%   |
| Intel Wi-Fi 6 AX201                                                     | 188       | 0.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 186       | 0.85%   |
| Intel Wi-Fi 6 AX200                                                     | 180       | 0.82%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 179       | 0.82%   |
| Intel Wireless 7265                                                     | 171       | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 171       | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 157       | 0.72%   |
| Intel WiFi Link 5100                                                    | 148       | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 147       | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 139       | 0.64%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 136       | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 133       | 0.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 133       | 0.61%   |
| Intel Wireless 3165                                                     | 129       | 0.59%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 127       | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 126       | 0.58%   |
| Intel Wireless 7260                                                     | 123       | 0.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 123       | 0.56%   |
| Intel Centrino Wireless-N 130                                           | 122       | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 121       | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 119       | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 115       | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Qualcomm Atheros                  | 3987      | 35.15%  |
| Intel                             | 3201      | 28.22%  |
| Realtek Semiconductor             | 1921      | 16.94%  |
| Broadcom                          | 1285      | 11.33%  |
| Ralink                            | 340       | 3%      |
| Broadcom Limited                  | 226       | 1.99%   |
| MediaTek                          | 112       | 0.99%   |
| Ralink Technology                 | 72        | 0.63%   |
| TP-Link                           | 52        | 0.46%   |
| ASUSTek Computer                  | 25        | 0.22%   |
| Qualcomm Atheros Communications   | 21        | 0.19%   |
| Sierra Wireless                   | 19        | 0.17%   |
| D-Link                            | 16        | 0.14%   |
| Fibocom                           | 12        | 0.11%   |
| Dell                              | 9         | 0.08%   |
| Qualcomm                          | 7         | 0.06%   |
| D-Link System                     | 6         | 0.05%   |
| Ericsson Business Mobile Networks | 4         | 0.04%   |
| Tenda                             | 3         | 0.03%   |
| Micro Star International          | 3         | 0.03%   |
| Mercucys                          | 3         | 0.03%   |
| Hewlett-Packard                   | 3         | 0.03%   |
| Edimax Technology                 | 3         | 0.03%   |
| Xiaomi                            | 2         | 0.02%   |
| Fujitsu Siemens Computers         | 2         | 0.02%   |
| ZyXEL Communications              | 1         | 0.01%   |
| Wacom                             | 1         | 0.01%   |
| Quectel Wireless Solutions        | 1         | 0.01%   |
| Qcom                              | 1         | 0.01%   |
| NetGear                           | 1         | 0.01%   |
| Microsoft                         | 1         | 0.01%   |
| Linksys                           | 1         | 0.01%   |
| ASUSTek Computer (wrong ID)       | 1         | 0.01%   |
| Askey Computer                    | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1347      | 11.83%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 749       | 6.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 599       | 5.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 562       | 4.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 474       | 4.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 399       | 3.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 335       | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 321       | 2.82%   |
| Broadcom BCM43142 802.11b/g/n                                           | 298       | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 295       | 2.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 262       | 2.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 204       | 1.79%   |
| Intel Wireless 8265 / 8275                                              | 203       | 1.78%   |
| Intel Wi-Fi 6 AX201                                                     | 188       | 1.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 186       | 1.63%   |
| Intel Wi-Fi 6 AX200                                                     | 180       | 1.58%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 179       | 1.57%   |
| Intel Wireless 7265                                                     | 171       | 1.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 171       | 1.5%    |
| Intel WiFi Link 5100                                                    | 148       | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 147       | 1.29%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 136       | 1.19%   |
| Intel Wireless 3165                                                     | 129       | 1.13%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 127       | 1.12%   |
| Intel Wireless 7260                                                     | 123       | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 123       | 1.08%   |
| Intel Centrino Wireless-N 130                                           | 122       | 1.07%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 121       | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 102       | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 101       | 0.89%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 97        | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 91        | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 85        | 0.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 84        | 0.74%   |
| Intel Centrino Wireless-N 2230                                          | 83        | 0.73%   |
| Intel WiMAX/WiFi Link 5150                                              | 81        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 77        | 0.68%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 73        | 0.64%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 73        | 0.64%   |
| Intel Centrino Advanced-N 6235                                          | 63        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 5835      | 57.27%  |
| Qualcomm Atheros                       | 1363      | 13.38%  |
| Intel                                  | 826       | 8.11%   |
| Broadcom                               | 675       | 6.62%   |
| Marvell Technology Group               | 463       | 4.54%   |
| Broadcom Limited                       | 210       | 2.06%   |
| JMicron Technology                     | 113       | 1.11%   |
| Attansic Technology                    | 106       | 1.04%   |
| Xiaomi                                 | 65        | 0.64%   |
| Nvidia                                 | 64        | 0.63%   |
| Huawei Technologies                    | 64        | 0.63%   |
| MediaTek                               | 57        | 0.56%   |
| Silicon Integrated Systems [SiS]       | 47        | 0.46%   |
| Samsung Electronics                    | 44        | 0.43%   |
| ZTE WCDMA Technologies MSM             | 34        | 0.33%   |
| TP-Link                                | 27        | 0.26%   |
| Qualcomm                               | 22        | 0.22%   |
| Gemtek                                 | 20        | 0.2%    |
| ASIX Electronics                       | 20        | 0.2%    |
| D-Link                                 | 15        | 0.15%   |
| Lenovo                                 | 13        | 0.13%   |
| Vimtron Electronics                    | 12        | 0.12%   |
| VIA Technologies                       | 8         | 0.08%   |
| HTC (High Tech Computer)               | 7         | 0.07%   |
| HMD Global                             | 7         | 0.07%   |
| Hewlett-Packard                        | 7         | 0.07%   |
| ICS Advent                             | 6         | 0.06%   |
| Apple                                  | 6         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.05%   |
| NTmore                                 | 5         | 0.05%   |
| T & A Mobile Phones                    | 4         | 0.04%   |
| GCT Semiconductor                      | 4         | 0.04%   |
| DisplayLink                            | 4         | 0.04%   |
| Android                                | 4         | 0.04%   |
| OPPO                                   | 3         | 0.03%   |
| LG Electronics                         | 3         | 0.03%   |
| ASUSTek Computer                       | 3         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.02%   |
| Motorola PCS                           | 2         | 0.02%   |
| Google                                 | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3935      | 38.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1605      | 15.7%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 260       | 2.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 232       | 2.27%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 190       | 1.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 157       | 1.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 139       | 1.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 133       | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 133       | 1.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 126       | 1.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 119       | 1.16%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 115       | 1.12%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 108       | 1.06%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 106       | 1.04%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 103       | 1.01%   |
| Intel WiMAX Connection 2400m                                                   | 96        | 0.94%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 93        | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 85        | 0.83%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 77        | 0.75%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 77        | 0.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 76        | 0.74%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 68        | 0.67%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 60        | 0.59%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 57        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 56        | 0.55%   |
| Intel Ethernet Connection (6) I219-V                                           | 56        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 51        | 0.5%    |
| Intel 82577LM Gigabit Network Connection                                       | 50        | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 48        | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 46        | 0.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 46        | 0.45%   |
| Intel Ethernet Connection (13) I219-V                                          | 46        | 0.45%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 45        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 45        | 0.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 41        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 38        | 0.37%   |
| Intel Ethernet Connection (4) I219-V                                           | 38        | 0.37%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 36        | 0.35%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 35        | 0.34%   |
| Intel Ethernet Connection (10) I219-V                                          | 33        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 11018     | 52.39%  |
| Ethernet | 9748      | 46.35%  |
| Modem    | 256       | 1.22%   |
| Unknown  | 10        | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 9020      | 77.5%   |
| Ethernet | 2614      | 22.46%  |
| Modem    | 4         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 9324      | 82.7%   |
| 1     | 1708      | 15.15%  |
| 0     | 223       | 1.98%   |
| 3     | 19        | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 11097     | 98.2%   |
| Yes  | 203       | 1.8%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2120      | 26.39%  |
| Qualcomm Atheros Communications | 1155      | 14.38%  |
| Realtek Semiconductor           | 1026      | 12.77%  |
| IMC Networks                    | 653       | 8.13%   |
| Broadcom                        | 604       | 7.52%   |
| Lite-On Technology              | 594       | 7.4%    |
| Foxconn / Hon Hai               | 499       | 6.21%   |
| Ralink                          | 186       | 2.32%   |
| ASUSTek Computer                | 178       | 2.22%   |
| Foxconn International           | 146       | 1.82%   |
| Toshiba                         | 141       | 1.76%   |
| Realtek                         | 119       | 1.48%   |
| Hewlett-Packard                 | 115       | 1.43%   |
| Cambridge Silicon Radio         | 115       | 1.43%   |
| Dell                            | 107       | 1.33%   |
| Apple                           | 81        | 1.01%   |
| Alps Electric                   | 63        | 0.78%   |
| Ralink Technology               | 37        | 0.46%   |
| Chicony Electronics             | 23        | 0.29%   |
| MediaTek                        | 21        | 0.26%   |
| Opticis                         | 12        | 0.15%   |
| Micro Star International        | 10        | 0.12%   |
| Askey Computer                  | 7         | 0.09%   |
| USI                             | 5         | 0.06%   |
| Taiyo Yuden                     | 4         | 0.05%   |
| Integrated System Solution      | 3         | 0.04%   |
| Samsung Electronics             | 2         | 0.02%   |
| Qcom                            | 2         | 0.02%   |
| TP-Link                         | 1         | 0.01%   |
| Syntek                          | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| Unknown                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 716       | 8.91%   |
| Realtek Bluetooth Radio                                                             | 552       | 6.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 424       | 5.28%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 348       | 4.33%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 342       | 4.26%   |
| Intel AX201 Bluetooth                                                               | 339       | 4.22%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 260       | 3.24%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 244       | 3.04%   |
| IMC Networks Bluetooth Radio                                                        | 197       | 2.45%   |
| Ralink RT3290 Bluetooth                                                             | 186       | 2.31%   |
| Intel AX200 Bluetooth                                                               | 180       | 2.24%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 163       | 2.03%   |
| IMC Networks Bluetooth Device                                                       | 161       | 2%      |
| Lite-On Atheros AR3012 Bluetooth                                                    | 154       | 1.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 151       | 1.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 146       | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 144       | 1.79%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 144       | 1.79%   |
| Lite-On Bluetooth Device                                                            | 139       | 1.73%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 126       | 1.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 115       | 1.43%   |
| Realtek 802.11ac WLAN Adapter                                                       | 113       | 1.41%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 107       | 1.33%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 103       | 1.28%   |
| Realtek RTL8723B Bluetooth                                                          | 102       | 1.27%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 99        | 1.23%   |
| Broadcom BCM2045 Bluetooth                                                          | 77        | 0.96%   |
| Qualcomm Atheros Bluetooth                                                          | 72        | 0.9%    |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 66        | 0.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 61        | 0.76%   |
| Broadcom HP Portable Valentine                                                      | 61        | 0.76%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 59        | 0.73%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 56        | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 54        | 0.67%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 53        | 0.66%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 53        | 0.66%   |
| Toshiba Integrated Bluetooth HCI                                                    | 52        | 0.65%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 51        | 0.63%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 51        | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 48        | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 8439      | 65.94%  |
| AMD                                          | 2901      | 22.67%  |
| Nvidia                                       | 1059      | 8.27%   |
| Silicon Integrated Systems [SiS]             | 75        | 0.59%   |
| C-Media Electronics                          | 67        | 0.52%   |
| Logitech                                     | 22        | 0.17%   |
| Creative Technology                          | 20        | 0.16%   |
| Realtek Semiconductor                        | 16        | 0.13%   |
| JMTek                                        | 13        | 0.1%    |
| VIA Technologies                             | 12        | 0.09%   |
| Texas Instruments                            | 10        | 0.08%   |
| Plantronics                                  | 10        | 0.08%   |
| Lenovo                                       | 9         | 0.07%   |
| Generalplus Technology                       | 8         | 0.06%   |
| Promethean Limited                           | 7         | 0.05%   |
| GN Netcom                                    | 7         | 0.05%   |
| Samson Technologies                          | 6         | 0.05%   |
| Focusrite-Novation                           | 6         | 0.05%   |
| ASUSTek Computer                             | 6         | 0.05%   |
| Yamaha                                       | 5         | 0.04%   |
| SteelSeries ApS                              | 5         | 0.04%   |
| DSEA A/S                                     | 5         | 0.04%   |
| A4Tech                                       | 5         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 4         | 0.03%   |
| Razer USA                                    | 4         | 0.03%   |
| Hewlett-Packard                              | 3         | 0.02%   |
| GYROCOM C&C                                  | 3         | 0.02%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.02%   |
| Zhaoxin                                      | 2         | 0.02%   |
| XMOS                                         | 2         | 0.02%   |
| SAVITECH                                     | 2         | 0.02%   |
| Samsung Electronics                          | 2         | 0.02%   |
| Roland                                       | 2         | 0.02%   |
| Microsoft                                    | 2         | 0.02%   |
| M-Audio                                      | 2         | 0.02%   |
| Kingston Technology                          | 2         | 0.02%   |
| Harman                                       | 2         | 0.02%   |
| Google                                       | 2         | 0.02%   |
| ESI Audiotechnik                             | 2         | 0.02%   |
| Elite Silicon                                | 2         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1430      | 9.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 976       | 6.23%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 785       | 5.01%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 773       | 4.93%   |
| AMD FCH Azalia Controller                                                                         | 728       | 4.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 704       | 4.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 637       | 4.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 575       | 3.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 574       | 3.66%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 414       | 2.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 382       | 2.44%   |
| AMD Kabini HDMI/DP Audio                                                                          | 350       | 2.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 335       | 2.14%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 325       | 2.07%   |
| Intel 8 Series HD Audio Controller                                                                | 325       | 2.07%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 270       | 1.72%   |
| Intel Cannon Lake PCH cAVS                                                                        | 266       | 1.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 266       | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 250       | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 246       | 1.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 244       | 1.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 240       | 1.53%   |
| AMD High Definition Audio Controller                                                              | 217       | 1.38%   |
| AMD Wrestler HDMI Audio                                                                           | 216       | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 210       | 1.34%   |
| AMD Trinity HDMI Audio Controller                                                                 | 204       | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 202       | 1.29%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 193       | 1.23%   |
| Intel Broadwell-U Audio Controller                                                                | 190       | 1.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 187       | 1.19%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 164       | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 157       | 1%      |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 157       | 1%      |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 134       | 0.85%   |
| Nvidia High Definition Audio Controller                                                           | 131       | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 112       | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 109       | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 93        | 0.59%   |
| Intel CM238 HD Audio Controller                                                                   | 88        | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 87        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 2641      | 23.22%  |
| SK hynix              | 2194      | 19.29%  |
| Unknown               | 1451      | 12.76%  |
| Kingston              | 1281      | 11.26%  |
| Micron Technology     | 919       | 8.08%   |
| Elpida                | 446       | 3.92%   |
| Nanya Technology      | 372       | 3.27%   |
| Ramaxel Technology    | 337       | 2.96%   |
| A-DATA Technology     | 306       | 2.69%   |
| Crucial               | 301       | 2.65%   |
| AMD                   | 131       | 1.15%   |
| ASint Technology      | 120       | 1.06%   |
| Corsair               | 88        | 0.77%   |
| Patriot               | 86        | 0.76%   |
| Unknown (ABCD)        | 79        | 0.69%   |
| 48spaces              | 76        | 0.67%   |
| Goldkey               | 75        | 0.66%   |
| SHARETRONIC           | 52        | 0.46%   |
| Foxline               | 39        | 0.34%   |
| Transcend             | 35        | 0.31%   |
| GOODRAM               | 29        | 0.26%   |
| Apacer                | 29        | 0.26%   |
| Qimonda               | 28        | 0.25%   |
| Kllisre               | 24        | 0.21%   |
| Unknown               | 24        | 0.21%   |
| Unifosa               | 23        | 0.2%    |
| ACPI Digital          | 20        | 0.18%   |
| Qumo                  | 17        | 0.15%   |
| Toshiba               | 16        | 0.14%   |
| Silicon Power         | 13        | 0.11%   |
| ChangXin Memory       | 8         | 0.07%   |
| Kingmax Semiconductor | 7         | 0.06%   |
| Kingmax               | 7         | 0.06%   |
| Unknown (08AE)        | 3         | 0.03%   |
| SGS/Thomson           | 3         | 0.03%   |
| MLLSE                 | 3         | 0.03%   |
| KingTiger             | 3         | 0.03%   |
| Infineon              | 3         | 0.03%   |
| Hexon                 | 3         | 0.03%   |
| Atermiter             | 3         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 216       | 1.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 147       | 1.19%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 142       | 1.15%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                     | 132       | 1.07%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 130       | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                     | 130       | 1.06%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 120       | 0.97%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 120       | 0.97%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 119       | 0.97%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 109       | 0.88%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 106       | 0.86%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 103       | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 95        | 0.77%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 94        | 0.76%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                             | 88        | 0.71%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                     | 88        | 0.71%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 87        | 0.71%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 87        | 0.71%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                     | 86        | 0.7%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 78        | 0.63%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                         | 77        | 0.63%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 75        | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                     | 71        | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 69        | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 67        | 0.54%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                     | 63        | 0.51%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 63        | 0.51%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                      | 63        | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                    | 60        | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                             | 58        | 0.47%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 58        | 0.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 56        | 0.45%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 54        | 0.44%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 53        | 0.43%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 53        | 0.43%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 52        | 0.42%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 52        | 0.42%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s                     | 51        | 0.41%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                    | 50        | 0.41%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4096MB SODIMM DDR3 1334MT/s                   | 50        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 5030      | 52.79%  |
| DDR4    | 2254      | 23.66%  |
| DDR2    | 1067      | 11.2%   |
| SDRAM   | 501       | 5.26%   |
| LPDDR4  | 227       | 2.38%   |
| Unknown | 128       | 1.34%   |
| DDR     | 126       | 1.32%   |
| DRAM    | 97        | 1.02%   |
| LPDDR3  | 80        | 0.84%   |
| LPDDR5  | 10        | 0.1%    |
| DDR5    | 7         | 0.07%   |
| SRAM    | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 8858      | 94.98%  |
| Row Of Chips | 350       | 3.75%   |
| DIMM         | 89        | 0.95%   |
| Chip         | 21        | 0.23%   |
| Unknown      | 8         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 4242      | 38.87%  |
| 2048    | 3054      | 27.98%  |
| 8192    | 2064      | 18.91%  |
| 1024    | 1002      | 9.18%   |
| 16384   | 363       | 3.33%   |
| 512     | 133       | 1.22%   |
| 32768   | 32        | 0.29%   |
| 256     | 15        | 0.14%   |
| Unknown | 5         | 0.05%   |
| 1536    | 3         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 3030      | 28.56%  |
| 1334    | 1287      | 12.13%  |
| 2667    | 1139      | 10.73%  |
| 1333    | 799       | 7.53%   |
| 3200    | 742       | 6.99%   |
| 667     | 652       | 6.14%   |
| Unknown | 621       | 5.85%   |
| 2400    | 517       | 4.87%   |
| 4199    | 276       | 2.6%    |
| 800     | 248       | 2.34%   |
| 1067    | 241       | 2.27%   |
| 2133    | 231       | 2.18%   |
| 533     | 150       | 1.41%   |
| 3266    | 130       | 1.23%   |
| 2048    | 102       | 0.96%   |
| 1066    | 99        | 0.93%   |
| 975     | 61        | 0.57%   |
| 1867    | 54        | 0.51%   |
| 333     | 42        | 0.4%    |
| 400     | 26        | 0.25%   |
| 4267    | 24        | 0.23%   |
| 1639    | 20        | 0.19%   |
| 1866    | 18        | 0.17%   |
| 8400    | 16        | 0.15%   |
| 3733    | 16        | 0.15%   |
| 4266    | 15        | 0.14%   |
| 6400    | 10        | 0.09%   |
| 4800    | 9         | 0.08%   |
| 2933    | 8         | 0.08%   |
| 65535   | 3         | 0.03%   |
| 2666    | 3         | 0.03%   |
| 1776    | 3         | 0.03%   |
| 266     | 3         | 0.03%   |
| 200     | 3         | 0.03%   |
| 100     | 3         | 0.03%   |
| 1       | 3         | 0.03%   |
| 2800    | 2         | 0.02%   |
| 2267    | 2         | 0.02%   |
| 1596    | 1         | 0.01%   |
| 888     | 1         | 0.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 58        | 27.62%  |
| Canon                  | 41        | 19.52%  |
| Samsung Electronics    | 34        | 16.19%  |
| Seiko Epson            | 21        | 10%     |
| Brother Industries     | 16        | 7.62%   |
| Panasonic (Matsushita) | 12        | 5.71%   |
| Xerox                  | 10        | 4.76%   |
| Ricoh                  | 6         | 2.86%   |
| Pantum                 | 5         | 2.38%   |
| Kyocera                | 3         | 1.43%   |
| Xiaomi                 | 1         | 0.48%   |
| Prolific Technology    | 1         | 0.48%   |
| NXP Semiconductors     | 1         | 0.48%   |
| Lexmark International  | 1         | 0.48%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                             | 9         | 4.27%   |
| Samsung SCX-4200 series                                      | 6         | 2.84%   |
| Panasonic (Matsushita) KX-MB1500RU                           | 6         | 2.84%   |
| Samsung SCX-3200 Series                                      | 5         | 2.37%   |
| Panasonic (Matsushita) KX-MB2030 Multifunction Laser Printer | 5         | 2.37%   |
| HP LaserJet P1102                                            | 5         | 2.37%   |
| Xerox B205                                                   | 4         | 1.9%    |
| Samsung SCX-3400 Series                                      | 4         | 1.9%    |
| Samsung ML-1210 Printer                                      | 4         | 1.9%    |
| Samsung M2020 Series                                         | 4         | 1.9%    |
| HP LaserJet 1200                                             | 4         | 1.9%    |
| Canon PIXMA MG2500 Series                                    | 4         | 1.9%    |
| Brother HL-1110 series                                       | 4         | 1.9%    |
| Seiko Epson L210 Series                                      | 3         | 1.42%   |
| Seiko Epson L200 Series                                      | 3         | 1.42%   |
| HP LaserJet 1018                                             | 3         | 1.42%   |
| Canon MF4010 series                                          | 3         | 1.42%   |
| Canon LBP7010C/7018C                                         | 3         | 1.42%   |
| Canon LBP3010/LBP3018/LBP3050                                | 3         | 1.42%   |
| Canon LaserShot LBP-1120 Printer                             | 3         | 1.42%   |
| Canon G1000 series                                           | 3         | 1.42%   |
| Xerox Phaser 3020                                            | 2         | 0.95%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                        | 2         | 0.95%   |
| Seiko Epson Printer                                          | 2         | 0.95%   |
| Seiko Epson L132 Series                                      | 2         | 0.95%   |
| Seiko Epson L120 Series                                      | 2         | 0.95%   |
| Samsung ML-1865                                              | 2         | 0.95%   |
| Samsung ML-1640 Series Laser Printer                         | 2         | 0.95%   |
| Samsung M2070 Series                                         | 2         | 0.95%   |
| Ricoh SP 150SUw                                              | 2         | 0.95%   |
| Pantum M6500 series                                          | 2         | 0.95%   |
| Kyocera FS-1120MFP                                           | 2         | 0.95%   |
| HP LaserJet Professional P1102w                              | 2         | 0.95%   |
| HP LaserJet 1320                                             | 2         | 0.95%   |
| HP LaserJet 1022                                             | 2         | 0.95%   |
| HP DeskJet 5440                                              | 2         | 0.95%   |
| HP DeskJet 4530 series                                       | 2         | 0.95%   |
| HP DeskJet 2300 series                                       | 2         | 0.95%   |
| HP DeskJet 2130 series                                       | 2         | 0.95%   |
| Canon LBP6020                                                | 2         | 0.95%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Seiko Epson                 | 14        | 33.33%  |
| Canon                       | 10        | 23.81%  |
| Hewlett-Packard             | 8         | 19.05%  |
| Mustek Systems              | 4         | 9.52%   |
| Ultima Electronics          | 2         | 4.76%   |
| KYE Systems (Mouse Systems) | 2         | 4.76%   |
| Acer Peripherals (now BenQ) | 2         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 5         | 11.9%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 4.76%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 2         | 4.76%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2         | 4.76%   |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 4.76%   |
| HP ScanJet 3770                                                                       | 2         | 4.76%   |
| HP ScanJet 2400c                                                                      | 2         | 4.76%   |
| HP Scanjet 200                                                                        | 2         | 4.76%   |
| Canon CanoScan LIDE 25                                                                | 2         | 4.76%   |
| Canon CanoScan LiDE 120                                                               | 2         | 4.76%   |
| Canon CanoScan LiDE 110                                                               | 2         | 4.76%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 2.38%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.38%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 2.38%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 1         | 2.38%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 1         | 2.38%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 1         | 2.38%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 1         | 2.38%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4                                          | 1         | 2.38%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE                                   | 1         | 2.38%   |
| HP ScanJet G4010                                                                      | 1         | 2.38%   |
| HP Scanjet 300                                                                        | 1         | 2.38%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1         | 2.38%   |
| Canon CanoScan LiDE 70                                                                | 1         | 2.38%   |
| Canon CanoScan LiDE 220                                                               | 1         | 2.38%   |
| Canon CanoScan 4400F                                                                  | 1         | 2.38%   |
| Acer Peripherals (now BenQ) Benq 5150/5250                                            | 1         | 2.38%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 1         | 2.38%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2548      | 25.79%  |
| IMC Networks                           | 1196      | 12.1%   |
| Acer                                   | 909       | 9.2%    |
| Realtek Semiconductor                  | 687       | 6.95%   |
| Suyin                                  | 623       | 6.31%   |
| Microdia                               | 511       | 5.17%   |
| Sunplus Innovation Technology          | 457       | 4.63%   |
| Silicon Motion                         | 398       | 4.03%   |
| Quanta                                 | 387       | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 361       | 3.65%   |
| Syntek                                 | 307       | 3.11%   |
| Alcor Micro                            | 280       | 2.83%   |
| Z-Star Microelectronics                | 155       | 1.57%   |
| Lite-On Technology                     | 117       | 1.18%   |
| Ricoh                                  | 115       | 1.16%   |
| ALi                                    | 102       | 1.03%   |
| Apple                                  | 98        | 0.99%   |
| DigiTech                               | 81        | 0.82%   |
| Luxvisions Innotech Limited            | 65        | 0.66%   |
| Logitech                               | 59        | 0.6%    |
| Lenovo                                 | 38        | 0.38%   |
| Samsung Electronics                    | 33        | 0.33%   |
| Primax Electronics                     | 31        | 0.31%   |
| Bison Electronics                      | 29        | 0.29%   |
| Sonix Technology                       | 27        | 0.27%   |
| DLEQNA19IFK6G2                         | 27        | 0.27%   |
| Importek                               | 21        | 0.21%   |
| icSpring                               | 20        | 0.2%    |
| Sunplus Technology                     | 17        | 0.17%   |
| Unknown                                | 15        | 0.15%   |
| Y Media                                | 14        | 0.14%   |
| OmniVision Technologies                | 14        | 0.14%   |
| SunplusIT                              | 12        | 0.12%   |
| GEMBIRD                                | 12        | 0.12%   |
| USB Camera CS                          | 9         | 0.09%   |
| Image Processor                        | 9         | 0.09%   |
| Genesys Logic                          | 8         | 0.08%   |
| Pixart Imaging                         | 7         | 0.07%   |
| Nebraska Furniture Mart                | 6         | 0.06%   |
| Microsoft                              | 5         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                | 279       | 2.82%   |
| Chicony Integrated Camera                        | 240       | 2.42%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 239       | 2.41%   |
| Chicony Lenovo EasyCamera                        | 214       | 2.16%   |
| Acer Lenovo Integrated Webcam                    | 200       | 2.02%   |
| IMC Networks USB2.0 HD UVC WebCam                | 173       | 1.75%   |
| Acer BisonCam, NB Pro                            | 152       | 1.54%   |
| Sunplus HD WebCam                                | 147       | 1.49%   |
| Microdia Integrated_Webcam_HD                    | 145       | 1.47%   |
| Acer Lenovo EasyCamera                           | 139       | 1.4%    |
| IMC Networks UVC VGA Webcam                      | 137       | 1.38%   |
| IMC Networks Integrated Camera                   | 135       | 1.36%   |
| Chicony USB2.0 HD UVC WebCam                     | 128       | 1.29%   |
| Chicony USB 2.0 Camera                           | 117       | 1.18%   |
| Realtek Integrated_Webcam_HD                     | 107       | 1.08%   |
| Chicony HP Webcam                                | 101       | 1.02%   |
| Acer Integrated Camera                           | 100       | 1.01%   |
| Realtek Lenovo EasyCamera                        | 94        | 0.95%   |
| Chicony VGA Webcam                               | 94        | 0.95%   |
| Quanta VGA WebCam                                | 90        | 0.91%   |
| Chicony USB2.0 VGA UVC WebCam                    | 87        | 0.88%   |
| Alcor Micro Asus Integrated Webcam               | 86        | 0.87%   |
| Silicon Motion WebCam SC-0311139N                | 83        | 0.84%   |
| Syntek Integrated Camera                         | 82        | 0.83%   |
| Syntek Lenovo EasyCamera                         | 78        | 0.79%   |
| IMC Networks Integrated Webcam                   | 76        | 0.77%   |
| Realtek USB Camera                               | 75        | 0.76%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 74        | 0.75%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 74        | 0.75%   |
| DigiTech USB 2.0 PC Camera                       | 73        | 0.74%   |
| Chicony HP Truevision HD                         | 71        | 0.72%   |
| ALi Gateway Webcam                               | 70        | 0.71%   |
| Alcor Micro USB Camera                           | 67        | 0.68%   |
| IMC Networks HD Camera                           | 66        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 64        | 0.65%   |
| Chicony EasyCamera                               | 63        | 0.64%   |
| Sunplus Integrated_Webcam_HD                     | 62        | 0.63%   |
| Silicon Motion WebCam SCB-1100N                  | 61        | 0.62%   |
| Suyin 1.3M HD WebCam                             | 60        | 0.61%   |
| Sunplus ASUS Webcam                              | 59        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 422       | 33.28%  |
| Shenzhen Goodix Technology         | 214       | 16.88%  |
| Synaptics                          | 178       | 14.04%  |
| AuthenTec                          | 130       | 10.25%  |
| Upek                               | 109       | 8.6%    |
| LighTuning Technology              | 91        | 7.18%   |
| Elan Microelectronics              | 83        | 6.55%   |
| STMicroelectronics                 | 32        | 2.52%   |
| Focal-systems.Corp                 | 7         | 0.55%   |
| Samsung Electronics                | 1         | 0.08%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 169       | 13.33%  |
| Validity Sensors Fingerprint scanner                                       | 98        | 7.73%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 91        | 7.18%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 86        | 6.78%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 72        | 5.68%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 57        | 4.5%    |
| Elan ELAN:Fingerprint                                                      | 54        | 4.26%   |
| LighTuning Fingerprint Reader                                              | 43        | 3.39%   |
| AuthenTec AES1600                                                          | 41        | 3.23%   |
| Shenzhen Goodix Fingerprint Reader                                         | 39        | 3.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 32        | 2.52%   |
| STMicroelectronics Fingerprint Reader                                      | 32        | 2.52%   |
| Unknown                                                                    | 32        | 2.52%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 31        | 2.44%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 31        | 2.44%   |
| AuthenTec AES2810                                                          | 27        | 2.13%   |
| Validity Sensors VFS491                                                    | 26        | 2.05%   |
| Elan ELAN:ARM-M4                                                           | 26        | 2.05%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 24        | 1.89%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 22        | 1.74%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 20        | 1.58%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 19        | 1.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 1.5%    |
| Upek TCS5B Fingerprint sensor                                              | 18        | 1.42%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 18        | 1.42%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 17        | 1.34%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 14        | 1.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 14        | 1.1%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 0.95%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 0.95%   |
| Synaptics  WBDI                                                            | 10        | 0.79%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 0.71%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 0.63%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 8         | 0.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 0.55%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 7         | 0.55%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 0.47%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.39%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.32%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.24%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 94        | 37.3%   |
| Broadcom                  | 81        | 32.14%  |
| Upek                      | 24        | 9.52%   |
| O2 Micro                  | 21        | 8.33%   |
| Lenovo                    | 16        | 6.35%   |
| Gemalto (was Gemplus)     | 4         | 1.59%   |
| Aladdin Knowledge Systems | 4         | 1.59%   |
| Yubico.com                | 3         | 1.19%   |
| Aktiv                     | 3         | 1.19%   |
| Microchip Technology      | 1         | 0.4%    |
| Aladdin R.D.              | 1         | 0.4%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 92        | 36.51%  |
| Broadcom BCM5880 Secure Applications Processor                               | 33        | 13.1%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 9.52%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 7.14%   |
| Broadcom 5880                                                                | 18        | 7.14%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.35%   |
| Broadcom 58200                                                               | 16        | 6.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 5.56%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 1.59%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 3         | 1.19%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.19%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.19%   |
| Aktiv Rutoken lite                                                           | 3         | 1.19%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.4%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.4%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.4%    |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.4%    |
| Aladdin R.D. JaCarta                                                         | 1         | 0.4%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 7904      | 67.55%  |
| 1     | 3002      | 25.66%  |
| 2     | 661       | 5.65%   |
| 3     | 110       | 0.94%   |
| 4     | 17        | 0.15%   |
| 5     | 4         | 0.03%   |
| 6     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1589      | 36.46%  |
| Fingerprint reader       | 1263      | 28.98%  |
| Net/wireless             | 414       | 9.5%    |
| Bluetooth                | 251       | 5.76%   |
| Chipcard                 | 224       | 5.14%   |
| Multimedia controller    | 215       | 4.93%   |
| Camera                   | 110       | 2.52%   |
| Communication controller | 79        | 1.81%   |
| Flash memory             | 60        | 1.38%   |
| Storage                  | 59        | 1.35%   |
| Card reader              | 27        | 0.62%   |
| Sound                    | 21        | 0.48%   |
| Net/ethernet             | 16        | 0.37%   |
| Modem                    | 13        | 0.3%    |
| Dvb card                 | 5         | 0.11%   |
| Network                  | 4         | 0.09%   |
| Storage/ide              | 3         | 0.07%   |
| Firewire controller      | 2         | 0.05%   |
| Wireless                 | 1         | 0.02%   |
| Unclassified device      | 1         | 0.02%   |
| Storage/raid             | 1         | 0.02%   |

