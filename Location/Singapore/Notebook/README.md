Linux in Singapore - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Singapore.

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

Total: 462

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro9,2               | [319272bf03](https://linux-hardware.org/?probe=319272bf03) | Jan 01, 2025 |
| Apple         | MacBookPro9,2               | [c7b700cc18](https://linux-hardware.org/?probe=c7b700cc18) | Dec 26, 2024 |
| Dell          | Inspiron 1525               | [cd4f5695b9](https://linux-hardware.org/?probe=cd4f5695b9) | Dec 22, 2024 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | [78598d0f36](https://linux-hardware.org/?probe=78598d0f36) | Dec 21, 2024 |
| Dell          | Latitude E6500              | [f173d0af82](https://linux-hardware.org/?probe=f173d0af82) | Dec 19, 2024 |
| Apple         | MacBookPro9,2               | [ac5dad0554](https://linux-hardware.org/?probe=ac5dad0554) | Dec 15, 2024 |
| MECHREVO      | WUJIE14XA                   | [cb76a6f8c5](https://linux-hardware.org/?probe=cb76a6f8c5) | Dec 13, 2024 |
| HP            | Pavilion Laptop 15-cc1xx    | [8f790073ab](https://linux-hardware.org/?probe=8f790073ab) | Dec 07, 2024 |
| Dell          | Latitude E6440              | [595f6a32d7](https://linux-hardware.org/?probe=595f6a32d7) | Dec 04, 2024 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [ded958606e](https://linux-hardware.org/?probe=ded958606e) | Dec 02, 2024 |
| Apple         | MacBookPro14,1              | [c725b25dfc](https://linux-hardware.org/?probe=c725b25dfc) | Nov 11, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [89f9b8697e](https://linux-hardware.org/?probe=89f9b8697e) | Oct 29, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [50608db984](https://linux-hardware.org/?probe=50608db984) | Oct 23, 2024 |
| Dell          | Latitude E6440              | [8755de9d32](https://linux-hardware.org/?probe=8755de9d32) | Oct 17, 2024 |
| Dell          | Latitude E6440              | [a632b6e574](https://linux-hardware.org/?probe=a632b6e574) | Oct 14, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [32eb262404](https://linux-hardware.org/?probe=32eb262404) | Oct 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [57602cd2d9](https://linux-hardware.org/?probe=57602cd2d9) | Oct 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [010be6e7fb](https://linux-hardware.org/?probe=010be6e7fb) | Sep 30, 2024 |
| Alienware     | m18 R2                      | [51332eaf8a](https://linux-hardware.org/?probe=51332eaf8a) | Sep 27, 2024 |
| MicroByte     | ezbook                      | [5b878e7b72](https://linux-hardware.org/?probe=5b878e7b72) | Sep 24, 2024 |
| MicroByte     | ezbook                      | [79104622de](https://linux-hardware.org/?probe=79104622de) | Sep 24, 2024 |
| Acer          | Swift SF314-57G             | [4becd67ee7](https://linux-hardware.org/?probe=4becd67ee7) | Sep 21, 2024 |
| Lenovo        | G40-45 80E1                 | [5e7135c91f](https://linux-hardware.org/?probe=5e7135c91f) | Sep 16, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [5b6c362951](https://linux-hardware.org/?probe=5b6c362951) | Sep 09, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [a13cb84209](https://linux-hardware.org/?probe=a13cb84209) | Sep 04, 2024 |
| Lenovo        | Legion S7 16IAH7 82TF       | [615190ebfe](https://linux-hardware.org/?probe=615190ebfe) | Sep 03, 2024 |
| Lenovo        | Legion S7 16IAH7 82TF       | [f846cf875c](https://linux-hardware.org/?probe=f846cf875c) | Sep 02, 2024 |
| HUAWEI        | MACHD-WXX9                  | [87961c091a](https://linux-hardware.org/?probe=87961c091a) | Aug 15, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [e3308aee33](https://linux-hardware.org/?probe=e3308aee33) | Aug 11, 2024 |
| Dell          | Latitude 7400               | [5a1203ee67](https://linux-hardware.org/?probe=5a1203ee67) | Aug 11, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [5fd9dd8b45](https://linux-hardware.org/?probe=5fd9dd8b45) | Aug 10, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [48b67b8342](https://linux-hardware.org/?probe=48b67b8342) | Aug 10, 2024 |
| Unknown       | Alder Lake N                | [c1fc9502d2](https://linux-hardware.org/?probe=c1fc9502d2) | Aug 03, 2024 |
| Unknown       | Alder Lake N                | [827d3a9aad](https://linux-hardware.org/?probe=827d3a9aad) | Aug 03, 2024 |
| Apple         | MacBookPro11,5              | [9167682d99](https://linux-hardware.org/?probe=9167682d99) | Aug 01, 2024 |
| Dell          | Latitude 3320               | [7eb3fdd1da](https://linux-hardware.org/?probe=7eb3fdd1da) | Jun 24, 2024 |
| Dell          | Latitude 3320               | [c5072f72e6](https://linux-hardware.org/?probe=c5072f72e6) | Jun 20, 2024 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | [dbb3d92cc6](https://linux-hardware.org/?probe=dbb3d92cc6) | Jun 17, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [d3a402bdca](https://linux-hardware.org/?probe=d3a402bdca) | Jun 12, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [30840e7e74](https://linux-hardware.org/?probe=30840e7e74) | Jun 11, 2024 |
| ASUSTek       | ZenBook UX481FLY_UX481FL    | [7d0530d329](https://linux-hardware.org/?probe=7d0530d329) | Jun 07, 2024 |
| Chuwi         | MiniBook X                  | [2bc0868e88](https://linux-hardware.org/?probe=2bc0868e88) | May 26, 2024 |
| Dell          | Latitude 7400               | [ede288f63c](https://linux-hardware.org/?probe=ede288f63c) | May 26, 2024 |
| HUAWEI        | MACHD-WXX9                  | [53c26896f2](https://linux-hardware.org/?probe=53c26896f2) | May 25, 2024 |
| MECHREVO      | WUJIE14 PRO                 | [5eef345507](https://linux-hardware.org/?probe=5eef345507) | May 24, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [b957b23e2d](https://linux-hardware.org/?probe=b957b23e2d) | May 21, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [bd0c6454d1](https://linux-hardware.org/?probe=bd0c6454d1) | May 21, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [6a7d29fe24](https://linux-hardware.org/?probe=6a7d29fe24) | Apr 15, 2024 |
| Valve         | Jupiter                     | [1cd9cc4807](https://linux-hardware.org/?probe=1cd9cc4807) | Apr 07, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [927e58d8ee](https://linux-hardware.org/?probe=927e58d8ee) | Mar 31, 2024 |
| Dell          | Latitude 7400               | [19bc09a2fb](https://linux-hardware.org/?probe=19bc09a2fb) | Mar 31, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | [3cf788c2ee](https://linux-hardware.org/?probe=3cf788c2ee) | Mar 24, 2024 |
| Dell          | Latitude 7400               | [6cc8d0a55c](https://linux-hardware.org/?probe=6cc8d0a55c) | Mar 01, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [d9a64479f5](https://linux-hardware.org/?probe=d9a64479f5) | Mar 01, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [c91afbe38c](https://linux-hardware.org/?probe=c91afbe38c) | Mar 01, 2024 |
| Valve         | Jupiter                     | [fc900c86f1](https://linux-hardware.org/?probe=fc900c86f1) | Feb 18, 2024 |
| Acer          | Aspire 4750                 | [bc24c666de](https://linux-hardware.org/?probe=bc24c666de) | Feb 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5eb2b65d31](https://linux-hardware.org/?probe=5eb2b65d31) | Feb 13, 2024 |
| Lenovo        | ThinkPad X230 23256N6       | [6f6d39cf77](https://linux-hardware.org/?probe=6f6d39cf77) | Feb 12, 2024 |
| Dell          | Latitude E7250              | [24ea631399](https://linux-hardware.org/?probe=24ea631399) | Jan 31, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [2ab9e19a09](https://linux-hardware.org/?probe=2ab9e19a09) | Jan 22, 2024 |
| MECHREVO      | WUJIE 14                    | [70a728ef39](https://linux-hardware.org/?probe=70a728ef39) | Jan 17, 2024 |
| System76      | Oryx Pro                    | [db771e1a08](https://linux-hardware.org/?probe=db771e1a08) | Jan 16, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [65ec7304a9](https://linux-hardware.org/?probe=65ec7304a9) | Jan 09, 2024 |
| HUAWEI        | CREM-WXX9                   | [29104c358b](https://linux-hardware.org/?probe=29104c358b) | Jan 07, 2024 |
| MECHREVO      | JiguangE Series GM5AR0E     | [dcaf044fe4](https://linux-hardware.org/?probe=dcaf044fe4) | Jan 05, 2024 |
| Apple         | MacBookPro11,5              | [4987fb1cb9](https://linux-hardware.org/?probe=4987fb1cb9) | Dec 30, 2023 |
| Lenovo        | Legion Y7000 81FW           | [f67367aa62](https://linux-hardware.org/?probe=f67367aa62) | Dec 23, 2023 |
| Dell          | Latitude 5440               | [bd5e743ebb](https://linux-hardware.org/?probe=bd5e743ebb) | Dec 21, 2023 |
| Valve         | Jupiter                     | [b746c80979](https://linux-hardware.org/?probe=b746c80979) | Dec 13, 2023 |
| ASUSTek       | X202E                       | [3d45a17e7f](https://linux-hardware.org/?probe=3d45a17e7f) | Dec 11, 2023 |
| MSI           | Prestige 15 A10SC           | [b1c3e47458](https://linux-hardware.org/?probe=b1c3e47458) | Dec 07, 2023 |
| Acer          | Swift SFE16-42              | [f61134a2d0](https://linux-hardware.org/?probe=f61134a2d0) | Dec 04, 2023 |
| Dell          | XPS 13 9300                 | [68ba1c0162](https://linux-hardware.org/?probe=68ba1c0162) | Nov 26, 2023 |
| Dell          | XPS 15 9570                 | [8e243668e7](https://linux-hardware.org/?probe=8e243668e7) | Nov 26, 2023 |
| Acer          | Swift SFE16-42              | [6b2a075d5a](https://linux-hardware.org/?probe=6b2a075d5a) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX95D... | [0a24a8ef6d](https://linux-hardware.org/?probe=0a24a8ef6d) | Nov 24, 2023 |
| Apple         | MacBookPro11,1              | [2018ab1ad9](https://linux-hardware.org/?probe=2018ab1ad9) | Nov 19, 2023 |
| Valve         | Jupiter                     | [31a965ca9d](https://linux-hardware.org/?probe=31a965ca9d) | Nov 14, 2023 |
| Timi          | RedmiBook 15                | [5f0d169445](https://linux-hardware.org/?probe=5f0d169445) | Nov 12, 2023 |
| ASUSTek       | K401UB                      | [3bc894aa34](https://linux-hardware.org/?probe=3bc894aa34) | Nov 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [d690fa8f27](https://linux-hardware.org/?probe=d690fa8f27) | Oct 29, 2023 |
| ASUSTek       | UX310UQK                    | [9c8029cd07](https://linux-hardware.org/?probe=9c8029cd07) | Oct 17, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire 5750                 | [89dc9a349f](https://linux-hardware.org/?probe=89dc9a349f) | Sep 26, 2023 |
| HP            | EliteBook 725 G4            | [1ef194c5fd](https://linux-hardware.org/?probe=1ef194c5fd) | Sep 22, 2023 |
| EUROCOM       | RAPTOR X17                  | [bbd769440e](https://linux-hardware.org/?probe=bbd769440e) | Sep 21, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [fb5af8d0d8](https://linux-hardware.org/?probe=fb5af8d0d8) | Sep 19, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [c75315410e](https://linux-hardware.org/?probe=c75315410e) | Sep 19, 2023 |
| EUROCOM       | RAPTOR X17                  | [15e2ca1220](https://linux-hardware.org/?probe=15e2ca1220) | Sep 19, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [a32457e14d](https://linux-hardware.org/?probe=a32457e14d) | Sep 15, 2023 |
| Dell          | Latitude 7280               | [ecca4887d5](https://linux-hardware.org/?probe=ecca4887d5) | Sep 15, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [032cd70e81](https://linux-hardware.org/?probe=032cd70e81) | Sep 15, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [938cec3228](https://linux-hardware.org/?probe=938cec3228) | Sep 09, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [235e80247e](https://linux-hardware.org/?probe=235e80247e) | Sep 05, 2023 |
| ASUSTek       | K401UB                      | [14a7bf0f59](https://linux-hardware.org/?probe=14a7bf0f59) | Aug 28, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| MSI           | GP66 Leopard 10UE           | [54eaec1cae](https://linux-hardware.org/?probe=54eaec1cae) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [70062471e2](https://linux-hardware.org/?probe=70062471e2) | Aug 19, 2023 |
| Acer          | Aspire A514-55              | [98ebe4bf9a](https://linux-hardware.org/?probe=98ebe4bf9a) | Aug 19, 2023 |
| Acer          | Aspire A514-55              | [cace7d6efb](https://linux-hardware.org/?probe=cace7d6efb) | Aug 18, 2023 |
| MSI           | GP66 Leopard 10UE           | [9f6cf770d1](https://linux-hardware.org/?probe=9f6cf770d1) | Aug 18, 2023 |
| Beelink       | Gemini X                    | [d5c4e54794](https://linux-hardware.org/?probe=d5c4e54794) | Aug 14, 2023 |
| Beelink       | Gemini X                    | [1610652627](https://linux-hardware.org/?probe=1610652627) | Aug 14, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [dfc4d46266](https://linux-hardware.org/?probe=dfc4d46266) | Aug 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [8511f4c245](https://linux-hardware.org/?probe=8511f4c245) | Aug 05, 2023 |
| Dell          | Inspiron 14-3462            | [9300232981](https://linux-hardware.org/?probe=9300232981) | Aug 05, 2023 |
| Lenovo        | ThinkPad X250 20CL0007SG    | [f30d61c851](https://linux-hardware.org/?probe=f30d61c851) | Aug 01, 2023 |
| Apple         | MacBookPro12,1              | [5bc4bf8334](https://linux-hardware.org/?probe=5bc4bf8334) | Jul 28, 2023 |
| Apple         | MacBookPro11,5              | [57e295e5cf](https://linux-hardware.org/?probe=57e295e5cf) | Jul 27, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [78560cbf59](https://linux-hardware.org/?probe=78560cbf59) | Jul 24, 2023 |
| ASUSTek       | K46CB                       | [144d523bf1](https://linux-hardware.org/?probe=144d523bf1) | Jul 18, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [dfe9381867](https://linux-hardware.org/?probe=dfe9381867) | Jul 14, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [b50c5ad983](https://linux-hardware.org/?probe=b50c5ad983) | Jul 06, 2023 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [e141746297](https://linux-hardware.org/?probe=e141746297) | Jul 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [d94ad2e231](https://linux-hardware.org/?probe=d94ad2e231) | Jun 28, 2023 |
| Lenovo        | Legion R7000P2021 82JW      | [df59b5e8b7](https://linux-hardware.org/?probe=df59b5e8b7) | Jun 19, 2023 |
| Dell          | Precision 5520              | [8d5ec720c1](https://linux-hardware.org/?probe=8d5ec720c1) | Jun 19, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Sony          | SVE11116FGW                 | [4c34707bef](https://linux-hardware.org/?probe=4c34707bef) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | [a048cbcdeb](https://linux-hardware.org/?probe=a048cbcdeb) | Jun 13, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [e28e041a5c](https://linux-hardware.org/?probe=e28e041a5c) | Jun 02, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [dcba8dc683](https://linux-hardware.org/?probe=dcba8dc683) | Jun 02, 2023 |
| Dell          | Latitude 7400               | [ef9ef10e4e](https://linux-hardware.org/?probe=ef9ef10e4e) | Jun 02, 2023 |
| Lenovo        | Yoga Slim 7 proX 14ARH7 ... | [684751d3db](https://linux-hardware.org/?probe=684751d3db) | May 26, 2023 |
| Acer          | Aspire 4750                 | [704221c10c](https://linux-hardware.org/?probe=704221c10c) | May 21, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [d6933984d7](https://linux-hardware.org/?probe=d6933984d7) | May 10, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [6beb57f72d](https://linux-hardware.org/?probe=6beb57f72d) | May 10, 2023 |
| Unknown       | AG958                       | [70aa4b6cf2](https://linux-hardware.org/?probe=70aa4b6cf2) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [9355511511](https://linux-hardware.org/?probe=9355511511) | May 07, 2023 |
| Acer          | Swift SF314-57G             | [6fd79b811f](https://linux-hardware.org/?probe=6fd79b811f) | Apr 28, 2023 |
| Dell          | XPS 13 7390                 | [318ea8ad1e](https://linux-hardware.org/?probe=318ea8ad1e) | Apr 27, 2023 |
| Dell          | Inspiron 15 5510            | [c8f22361f6](https://linux-hardware.org/?probe=c8f22361f6) | Apr 24, 2023 |
| AZW           | GT-R                        | [c37dabb7a7](https://linux-hardware.org/?probe=c37dabb7a7) | Apr 15, 2023 |
| Dell          | Latitude 7400               | [0f917420a1](https://linux-hardware.org/?probe=0f917420a1) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [c518902ba7](https://linux-hardware.org/?probe=c518902ba7) | Apr 13, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [7eee4a859e](https://linux-hardware.org/?probe=7eee4a859e) | Apr 12, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [874513db8d](https://linux-hardware.org/?probe=874513db8d) | Apr 12, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| ASUSTek       | X45A                        | [a0401520d5](https://linux-hardware.org/?probe=a0401520d5) | Mar 27, 2023 |
| ASUSTek       | X45A                        | [dbe8e77436](https://linux-hardware.org/?probe=dbe8e77436) | Mar 27, 2023 |
| ASUSTek       | X45A                        | [675de376da](https://linux-hardware.org/?probe=675de376da) | Mar 27, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | [92208949d5](https://linux-hardware.org/?probe=92208949d5) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [aa71c25dba](https://linux-hardware.org/?probe=aa71c25dba) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | [9b38c9668e](https://linux-hardware.org/?probe=9b38c9668e) | Mar 10, 2023 |
| Dell          | XPS 13 9310                 | [037f2e4a2d](https://linux-hardware.org/?probe=037f2e4a2d) | Mar 10, 2023 |
| Dell          | Inspiron 3468               | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| HUAWEI        | MACHC-WAX9                  | [69a8710cbb](https://linux-hardware.org/?probe=69a8710cbb) | Feb 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | [db5d2b956a](https://linux-hardware.org/?probe=db5d2b956a) | Feb 18, 2023 |
| MSI           | GE62VR 6RF                  | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Acer          | Aspire V5-132               | [7f74397112](https://linux-hardware.org/?probe=7f74397112) | Jan 24, 2023 |
| ASUSTek       | K45VM                       | [7fef453cdb](https://linux-hardware.org/?probe=7fef453cdb) | Jan 23, 2023 |
| Acer          | Aspire ES1-432              | [4a81caf8b2](https://linux-hardware.org/?probe=4a81caf8b2) | Jan 18, 2023 |
| Acer          | Aspire 5750G                | [d696233b84](https://linux-hardware.org/?probe=d696233b84) | Jan 18, 2023 |
| Dell          | Latitude 7390               | [cc5d8632f5](https://linux-hardware.org/?probe=cc5d8632f5) | Jan 13, 2023 |
| Dell          | Latitude 7390               | [a8ee39edc5](https://linux-hardware.org/?probe=a8ee39edc5) | Jan 13, 2023 |
| Unknown       | Unknown                     | [ae506ac561](https://linux-hardware.org/?probe=ae506ac561) | Jan 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | [3e870855db](https://linux-hardware.org/?probe=3e870855db) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [14273d90fd](https://linux-hardware.org/?probe=14273d90fd) | Jan 08, 2023 |
| ASUSTek       | X555LAB                     | [3af1bc02b8](https://linux-hardware.org/?probe=3af1bc02b8) | Jan 05, 2023 |
| ASUSTek       | X555LAB                     | [0a1360a7dc](https://linux-hardware.org/?probe=0a1360a7dc) | Jan 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| Dell          | Inspiron 1420               | [fe6a8714da](https://linux-hardware.org/?probe=fe6a8714da) | Dec 31, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| ASUSTek       | K45VM                       | [ee344993aa](https://linux-hardware.org/?probe=ee344993aa) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | [cc9fb3fd05](https://linux-hardware.org/?probe=cc9fb3fd05) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [51f520d152](https://linux-hardware.org/?probe=51f520d152) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [d5171f9491](https://linux-hardware.org/?probe=d5171f9491) | Dec 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [615d3e1599](https://linux-hardware.org/?probe=615d3e1599) | Dec 14, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [52546b1dd0](https://linux-hardware.org/?probe=52546b1dd0) | Dec 10, 2022 |
| HP            | ZBook 15                    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [61f6e057e6](https://linux-hardware.org/?probe=61f6e057e6) | Nov 17, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| Dell          | Precision 3571              | [039ece6391](https://linux-hardware.org/?probe=039ece6391) | Nov 10, 2022 |
| Google        | Atlas                       | [77922a522d](https://linux-hardware.org/?probe=77922a522d) | Nov 09, 2022 |
| Google        | Atlas                       | [829fcb8f6a](https://linux-hardware.org/?probe=829fcb8f6a) | Nov 09, 2022 |
| Dell          | Precision 3571              | [d305848533](https://linux-hardware.org/?probe=d305848533) | Nov 08, 2022 |
| Dell          | Precision 3571              | [681a655e1c](https://linux-hardware.org/?probe=681a655e1c) | Nov 08, 2022 |
| Dell          | Precision 3571              | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| Dell          | Precision 3571              | [9da55445b0](https://linux-hardware.org/?probe=9da55445b0) | Nov 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [0a0922ed82](https://linux-hardware.org/?probe=0a0922ed82) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [52701ec9f4](https://linux-hardware.org/?probe=52701ec9f4) | Oct 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1dc7719a4d](https://linux-hardware.org/?probe=1dc7719a4d) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [18893915f3](https://linux-hardware.org/?probe=18893915f3) | Oct 17, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [d67006c592](https://linux-hardware.org/?probe=d67006c592) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [5ace2d0c1f](https://linux-hardware.org/?probe=5ace2d0c1f) | Oct 06, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [3338607f1a](https://linux-hardware.org/?probe=3338607f1a) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| MSI           | Modern 14 B5M               | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | [855ad327a4](https://linux-hardware.org/?probe=855ad327a4) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | [829ec8aac1](https://linux-hardware.org/?probe=829ec8aac1) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | [93680a7429](https://linux-hardware.org/?probe=93680a7429) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | [ae5fd894b6](https://linux-hardware.org/?probe=ae5fd894b6) | Sep 25, 2022 |
| Lenovo        | Legion R9000K2021H 82N6     | [d739547049](https://linux-hardware.org/?probe=d739547049) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | [0f698c857c](https://linux-hardware.org/?probe=0f698c857c) | Sep 16, 2022 |
| Dell          | Precision 3561              | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Dell          | Latitude 3320               | [1ab9888966](https://linux-hardware.org/?probe=1ab9888966) | Sep 09, 2022 |
| MSI           | Pulse GL66 11UGK            | [db7f9099f2](https://linux-hardware.org/?probe=db7f9099f2) | Sep 05, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [814c094769](https://linux-hardware.org/?probe=814c094769) | Sep 01, 2022 |
| Timi          | Redmi Book Pro 14 2022      | [3f61df6540](https://linux-hardware.org/?probe=3f61df6540) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | [c94e06f68f](https://linux-hardware.org/?probe=c94e06f68f) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | [7be66c9d4c](https://linux-hardware.org/?probe=7be66c9d4c) | Aug 25, 2022 |
| Acer          | Aspire V5-471PG             | [c91dcf26c8](https://linux-hardware.org/?probe=c91dcf26c8) | Aug 14, 2022 |
| Dell          | Latitude 3320               | [b8e1190875](https://linux-hardware.org/?probe=b8e1190875) | Aug 14, 2022 |
| Dell          | Latitude 3320               | [f489cd4f21](https://linux-hardware.org/?probe=f489cd4f21) | Aug 14, 2022 |
| Timi          | TM1701                      | [dc4d12ca83](https://linux-hardware.org/?probe=dc4d12ca83) | Aug 14, 2022 |
| Acer          | Aspire V5-471PG             | [5c2d9bf35f](https://linux-hardware.org/?probe=5c2d9bf35f) | Aug 13, 2022 |
| Dell          | G15 5520                    | [07feaad5d2](https://linux-hardware.org/?probe=07feaad5d2) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [5931b46fe1](https://linux-hardware.org/?probe=5931b46fe1) | Aug 10, 2022 |
| Dell          | Latitude 3320               | [b99f237d17](https://linux-hardware.org/?probe=b99f237d17) | Aug 09, 2022 |
| Acer          | Aspire A315-41              | [6a9c811ea3](https://linux-hardware.org/?probe=6a9c811ea3) | Aug 07, 2022 |
| HP            | ZBook 15v G5                | [b08d670a98](https://linux-hardware.org/?probe=b08d670a98) | Jul 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| Acer          | Aspire A315-41              | [366f3c9611](https://linux-hardware.org/?probe=366f3c9611) | Jul 14, 2022 |
| Acer          | Aspire A315-41              | [27f2c99f99](https://linux-hardware.org/?probe=27f2c99f99) | Jul 14, 2022 |
| Sony          | SVF1531V8CW                 | [bebf2fb162](https://linux-hardware.org/?probe=bebf2fb162) | Jul 13, 2022 |
| Dell          | Latitude 3120               | [361c9c4fa3](https://linux-hardware.org/?probe=361c9c4fa3) | Jul 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [e91c32dba7](https://linux-hardware.org/?probe=e91c32dba7) | Jun 25, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [c434fdda77](https://linux-hardware.org/?probe=c434fdda77) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [6941a8232a](https://linux-hardware.org/?probe=6941a8232a) | Jun 17, 2022 |
| ASUSTek       | GL552VW                     | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| Sony          | VPCCA15FG                   | [d155f5ee52](https://linux-hardware.org/?probe=d155f5ee52) | Jun 08, 2022 |
| Dell          | Inspiron 13 5310            | [70eccb19d4](https://linux-hardware.org/?probe=70eccb19d4) | Jun 01, 2022 |
| Lenovo        | 14w 81MQS02H00              | [e31087bfa9](https://linux-hardware.org/?probe=e31087bfa9) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f1f75187e1](https://linux-hardware.org/?probe=f1f75187e1) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | [8fd4bc6a6d](https://linux-hardware.org/?probe=8fd4bc6a6d) | May 15, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | [0906d694b9](https://linux-hardware.org/?probe=0906d694b9) | May 15, 2022 |
| Dell          | XPS 13 7390                 | [8deb85f8e2](https://linux-hardware.org/?probe=8deb85f8e2) | May 03, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [3a7cd290f6](https://linux-hardware.org/?probe=3a7cd290f6) | Apr 30, 2022 |
| Dell          | Latitude 3120               | [c6b9dfe36e](https://linux-hardware.org/?probe=c6b9dfe36e) | Apr 18, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [7fe8e51699](https://linux-hardware.org/?probe=7fe8e51699) | Apr 13, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | [8e602bc358](https://linux-hardware.org/?probe=8e602bc358) | Apr 07, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | [7309102f77](https://linux-hardware.org/?probe=7309102f77) | Apr 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [ceee79344c](https://linux-hardware.org/?probe=ceee79344c) | Mar 31, 2022 |
| Acer          | Swift SF314-54G             | [615009b8ee](https://linux-hardware.org/?probe=615009b8ee) | Mar 23, 2022 |
| Acer          | Aspire VN7-592G             | [f4d3207c6d](https://linux-hardware.org/?probe=f4d3207c6d) | Mar 22, 2022 |
| AMI           | Intel                       | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d7f14afdd4](https://linux-hardware.org/?probe=d7f14afdd4) | Feb 26, 2022 |
| Dell          | Inspiron 3501               | [a8c8bdd208](https://linux-hardware.org/?probe=a8c8bdd208) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [fbb2caeacf](https://linux-hardware.org/?probe=fbb2caeacf) | Feb 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [c5acc050e4](https://linux-hardware.org/?probe=c5acc050e4) | Feb 19, 2022 |
| Dell          | Precision 7560              | [811983afdd](https://linux-hardware.org/?probe=811983afdd) | Feb 17, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| ASUSTek       | N501JW                      | [55550ca825](https://linux-hardware.org/?probe=55550ca825) | Feb 13, 2022 |
| COPELION I... | ZX Series                   | [764c80257b](https://linux-hardware.org/?probe=764c80257b) | Feb 12, 2022 |
| COPELION I... | ZX Series                   | [958dcebefa](https://linux-hardware.org/?probe=958dcebefa) | Feb 12, 2022 |
| Dell          | Latitude E5450              | [b426feb1d9](https://linux-hardware.org/?probe=b426feb1d9) | Feb 11, 2022 |
| Acer          | Predator G9-792             | [a01c295f77](https://linux-hardware.org/?probe=a01c295f77) | Feb 09, 2022 |
| Acer          | Predator G9-792             | [c030ff8b96](https://linux-hardware.org/?probe=c030ff8b96) | Feb 09, 2022 |
| Dell          | Latitude E7250              | [a7ba3830f7](https://linux-hardware.org/?probe=a7ba3830f7) | Feb 07, 2022 |
| Dell          | Inspiron 15 5510            | [3dbd4103ce](https://linux-hardware.org/?probe=3dbd4103ce) | Feb 06, 2022 |
| ASUSTek       | K45VM                       | [5cb4dcfe48](https://linux-hardware.org/?probe=5cb4dcfe48) | Jan 29, 2022 |
| ASUSTek       | K45VM                       | [39cac76612](https://linux-hardware.org/?probe=39cac76612) | Jan 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [a172ae51cf](https://linux-hardware.org/?probe=a172ae51cf) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [efbe19b07b](https://linux-hardware.org/?probe=efbe19b07b) | Jan 20, 2022 |
| ASUSTek       | N501JW                      | [af9aaff7ee](https://linux-hardware.org/?probe=af9aaff7ee) | Jan 05, 2022 |
| Apple         | MacBookPro7,1               | [9f745065df](https://linux-hardware.org/?probe=9f745065df) | Dec 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [aae3ae242f](https://linux-hardware.org/?probe=aae3ae242f) | Dec 21, 2021 |
| Apple         | MacBookAir3,1               | [ef12425b00](https://linux-hardware.org/?probe=ef12425b00) | Dec 19, 2021 |
| Apple         | MacBookPro7,1               | [b92a9a109f](https://linux-hardware.org/?probe=b92a9a109f) | Dec 18, 2021 |
| Dell          | Inspiron 5580               | [29d56d5a5e](https://linux-hardware.org/?probe=29d56d5a5e) | Dec 06, 2021 |
| ASUSTek       | K501UX                      | [3f9b547c57](https://linux-hardware.org/?probe=3f9b547c57) | Dec 04, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8876123555](https://linux-hardware.org/?probe=8876123555) | Nov 26, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [97e66fa893](https://linux-hardware.org/?probe=97e66fa893) | Nov 09, 2021 |
| Dell          | XPS 15 9570                 | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [4b9f5aed33](https://linux-hardware.org/?probe=4b9f5aed33) | Nov 01, 2021 |
| Dell          | XPS 15 9510                 | [9ad082f18e](https://linux-hardware.org/?probe=9ad082f18e) | Nov 01, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7ad1f07edb](https://linux-hardware.org/?probe=7ad1f07edb) | Oct 21, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5ac27f4e29](https://linux-hardware.org/?probe=5ac27f4e29) | Oct 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6e2173f8b4](https://linux-hardware.org/?probe=6e2173f8b4) | Sep 30, 2021 |
| ASUSTek       | UX32LA                      | [9763fb0928](https://linux-hardware.org/?probe=9763fb0928) | Sep 25, 2021 |
| ASUSTek       | UX32LA                      | [e97b7fce6b](https://linux-hardware.org/?probe=e97b7fce6b) | Sep 25, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Acer          | Aspire 6935                 | [fc440eee50](https://linux-hardware.org/?probe=fc440eee50) | Sep 12, 2021 |
| Acer          | Aspire 6935                 | [24cfb86539](https://linux-hardware.org/?probe=24cfb86539) | Sep 12, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [b7ff195931](https://linux-hardware.org/?probe=b7ff195931) | Sep 02, 2021 |
| Dell          | Precision 7560              | [75c607555e](https://linux-hardware.org/?probe=75c607555e) | Aug 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [a613776a9c](https://linux-hardware.org/?probe=a613776a9c) | Aug 18, 2021 |
| Acer          | Nitro AN515-43              | [d0952296d7](https://linux-hardware.org/?probe=d0952296d7) | Aug 17, 2021 |
| Dell          | Inspiron 7370               | [b702f17a07](https://linux-hardware.org/?probe=b702f17a07) | Aug 17, 2021 |
| Acer          | Swift SF314-57G             | [a5f10ae10b](https://linux-hardware.org/?probe=a5f10ae10b) | Aug 17, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | [978dbea880](https://linux-hardware.org/?probe=978dbea880) | Jul 27, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | [e3c0726e19](https://linux-hardware.org/?probe=e3c0726e19) | Jul 27, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [e74f010570](https://linux-hardware.org/?probe=e74f010570) | Jul 26, 2021 |
| Toshiba       | PORTEGE R930                | [6141314610](https://linux-hardware.org/?probe=6141314610) | Jul 22, 2021 |
| ASUSTek       | K45VM                       | [6d08e71c4e](https://linux-hardware.org/?probe=6d08e71c4e) | Jul 07, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f4778083d9](https://linux-hardware.org/?probe=f4778083d9) | Jul 02, 2021 |
| Acer          | Swift SF314-41G             | [fe5e126da1](https://linux-hardware.org/?probe=fe5e126da1) | Jul 01, 2021 |
| Acer          | Aspire one                  | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| Sony          | VPCSB36FG                   | [c834499816](https://linux-hardware.org/?probe=c834499816) | Jun 10, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [650e1b9bf5](https://linux-hardware.org/?probe=650e1b9bf5) | Jun 05, 2021 |
| Dell          | Latitude 7490               | [879fc7a838](https://linux-hardware.org/?probe=879fc7a838) | May 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [920ef637b1](https://linux-hardware.org/?probe=920ef637b1) | May 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | [c9c9d02ede](https://linux-hardware.org/?probe=c9c9d02ede) | May 20, 2021 |
| Sony          | VPCSB36FG                   | [828a8ac75d](https://linux-hardware.org/?probe=828a8ac75d) | May 18, 2021 |
| Dell          | XPS 15 9500                 | [ffa207ed1e](https://linux-hardware.org/?probe=ffa207ed1e) | May 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c17ba8c1a6](https://linux-hardware.org/?probe=c17ba8c1a6) | May 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | [e26f3c0f44](https://linux-hardware.org/?probe=e26f3c0f44) | Mar 29, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | [e4c813c694](https://linux-hardware.org/?probe=e4c813c694) | Mar 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ce138f71dd](https://linux-hardware.org/?probe=ce138f71dd) | Mar 15, 2021 |
| Toshiba       | PORTEGE R930                | [6e5981a1c8](https://linux-hardware.org/?probe=6e5981a1c8) | Mar 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [81b4d6916d](https://linux-hardware.org/?probe=81b4d6916d) | Mar 11, 2021 |
| Acer          | Swift SF314-56G             | [46ff93e8b8](https://linux-hardware.org/?probe=46ff93e8b8) | Mar 09, 2021 |
| Acer          | Swift SF314-56G             | [98a5817785](https://linux-hardware.org/?probe=98a5817785) | Mar 09, 2021 |
| Acer          | Aspire A515-51G             | [820e208bca](https://linux-hardware.org/?probe=820e208bca) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | [d8b4e607e1](https://linux-hardware.org/?probe=d8b4e607e1) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | [eca0e7f55f](https://linux-hardware.org/?probe=eca0e7f55f) | Mar 02, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [eb33727eff](https://linux-hardware.org/?probe=eb33727eff) | Feb 18, 2021 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [b2795c1a02](https://linux-hardware.org/?probe=b2795c1a02) | Feb 13, 2021 |
| Acer          | Swift SF314-56G             | [e67e7f24e8](https://linux-hardware.org/?probe=e67e7f24e8) | Feb 11, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | [cbb8e959b4](https://linux-hardware.org/?probe=cbb8e959b4) | Feb 05, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | [a8f5211aee](https://linux-hardware.org/?probe=a8f5211aee) | Feb 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [f4505630e3](https://linux-hardware.org/?probe=f4505630e3) | Feb 03, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | [0e5eeb215d](https://linux-hardware.org/?probe=0e5eeb215d) | Jan 28, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | [15d05a517c](https://linux-hardware.org/?probe=15d05a517c) | Jan 23, 2021 |
| Notebook      | P65_P67SE                   | [1b4cd968fd](https://linux-hardware.org/?probe=1b4cd968fd) | Jan 22, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [08990229db](https://linux-hardware.org/?probe=08990229db) | Jan 17, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [dc6edb4a25](https://linux-hardware.org/?probe=dc6edb4a25) | Jan 14, 2021 |
| Dell          | G3 3500                     | [27386ee67b](https://linux-hardware.org/?probe=27386ee67b) | Jan 12, 2021 |
| Lenovo        | ThinkPad E14 20RA0058VA     | [3c08ce49f5](https://linux-hardware.org/?probe=3c08ce49f5) | Jan 08, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [4b19f38fcd](https://linux-hardware.org/?probe=4b19f38fcd) | Jan 02, 2021 |
| Samsung       | RF510/RF410/RF710           | [3f041f4b71](https://linux-hardware.org/?probe=3f041f4b71) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [c30d1c7374](https://linux-hardware.org/?probe=c30d1c7374) | Dec 31, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [ccd41dd67e](https://linux-hardware.org/?probe=ccd41dd67e) | Dec 28, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [2fd914ada2](https://linux-hardware.org/?probe=2fd914ada2) | Dec 25, 2020 |
| Acer          | Aspire one                  | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| Lenovo        | ThinkPad T400 2768CJ6       | [1d878eeb02](https://linux-hardware.org/?probe=1d878eeb02) | Dec 10, 2020 |
| HP            | ProBook 440 G4              | [e28bcb99e5](https://linux-hardware.org/?probe=e28bcb99e5) | Dec 07, 2020 |
| ASUSTek       | K45VM                       | [9dedb35f93](https://linux-hardware.org/?probe=9dedb35f93) | Dec 04, 2020 |
| Aftershock    | N15_N17RF1                  | [09b42b449a](https://linux-hardware.org/?probe=09b42b449a) | Nov 27, 2020 |
| Dell          | Precision 7530              | [6ea3afdb4a](https://linux-hardware.org/?probe=6ea3afdb4a) | Nov 26, 2020 |
| Samsung       | RF510/RF410/RF710           | [1250c7dfbe](https://linux-hardware.org/?probe=1250c7dfbe) | Nov 25, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | [cc79643d27](https://linux-hardware.org/?probe=cc79643d27) | Nov 22, 2020 |
| Dell          | Latitude 7400               | [3154149e40](https://linux-hardware.org/?probe=3154149e40) | Nov 21, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [93678477d7](https://linux-hardware.org/?probe=93678477d7) | Nov 20, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | [c0ab31022d](https://linux-hardware.org/?probe=c0ab31022d) | Nov 20, 2020 |
| Dell          | Inspiron 5379               | [63815d0103](https://linux-hardware.org/?probe=63815d0103) | Nov 15, 2020 |
| Fujitsu       | LIFEBOOK SH561              | [759718c54b](https://linux-hardware.org/?probe=759718c54b) | Nov 10, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | [f3f5326846](https://linux-hardware.org/?probe=f3f5326846) | Nov 08, 2020 |
| Dell          | Inspiron 3421               | [e08c38affc](https://linux-hardware.org/?probe=e08c38affc) | Nov 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [14cf318590](https://linux-hardware.org/?probe=14cf318590) | Oct 29, 2020 |
| Acer          | Swift SF314-54              | [35aa366265](https://linux-hardware.org/?probe=35aa366265) | Oct 18, 2020 |
| Acer          | ConceptD CN715-71           | [8396c1d9e6](https://linux-hardware.org/?probe=8396c1d9e6) | Oct 13, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [b47f8da412](https://linux-hardware.org/?probe=b47f8da412) | Oct 09, 2020 |
| HP            | Compaq 6510b                | [cf190a85ea](https://linux-hardware.org/?probe=cf190a85ea) | Oct 08, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [05ef194f79](https://linux-hardware.org/?probe=05ef194f79) | Sep 28, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | [78566669f0](https://linux-hardware.org/?probe=78566669f0) | Sep 27, 2020 |
| ASUSTek       | T300LA                      | [9ca4cba592](https://linux-hardware.org/?probe=9ca4cba592) | Sep 27, 2020 |
| Dell          | Inspiron 3476               | [021351472c](https://linux-hardware.org/?probe=021351472c) | Sep 26, 2020 |
| HP            | Compaq 6510b                | [9b9a4b4614](https://linux-hardware.org/?probe=9b9a4b4614) | Sep 22, 2020 |
| HP            | Compaq 6510b                | [3487aab3a6](https://linux-hardware.org/?probe=3487aab3a6) | Sep 20, 2020 |
| HP            | Compaq 6510b                | [b7382d2141](https://linux-hardware.org/?probe=b7382d2141) | Sep 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [4a4a01267c](https://linux-hardware.org/?probe=4a4a01267c) | Sep 18, 2020 |
| ASUSTek       | UX305CA                     | [dc9532c57b](https://linux-hardware.org/?probe=dc9532c57b) | Sep 12, 2020 |
| Samsung       | 305U1A                      | [9949d76953](https://linux-hardware.org/?probe=9949d76953) | Sep 09, 2020 |
| Samsung       | 305U1A                      | [9dbf37ad63](https://linux-hardware.org/?probe=9dbf37ad63) | Sep 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [cab06cdbd7](https://linux-hardware.org/?probe=cab06cdbd7) | Sep 07, 2020 |
| Acer          | Aspire A515-51G             | [c9d6ce6954](https://linux-hardware.org/?probe=c9d6ce6954) | Sep 05, 2020 |
| Aftershock    | N8xxEP6                     | [d8e9d4edfd](https://linux-hardware.org/?probe=d8e9d4edfd) | Sep 04, 2020 |
| Dell          | Precision 7530              | [91306b715e](https://linux-hardware.org/?probe=91306b715e) | Sep 03, 2020 |
| Aftershock    | N15_N17RF1                  | [e3e85f51cc](https://linux-hardware.org/?probe=e3e85f51cc) | Sep 03, 2020 |
| Dell          | Latitude 5400               | [498b1be7bd](https://linux-hardware.org/?probe=498b1be7bd) | Sep 02, 2020 |
| Toshiba       | PORTEGE R930                | [64ba8fde9d](https://linux-hardware.org/?probe=64ba8fde9d) | Aug 31, 2020 |
| Toshiba       | PORTEGE R930                | [b37b0d860d](https://linux-hardware.org/?probe=b37b0d860d) | Aug 31, 2020 |
| Lenovo        | Yoga 3 14 80JH              | [3623866056](https://linux-hardware.org/?probe=3623866056) | Aug 28, 2020 |
| HP            | Compaq 6510b                | [7db74443d5](https://linux-hardware.org/?probe=7db74443d5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | [20f281e6e5](https://linux-hardware.org/?probe=20f281e6e5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | [2791e33d53](https://linux-hardware.org/?probe=2791e33d53) | Aug 24, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | [8bc9e504d7](https://linux-hardware.org/?probe=8bc9e504d7) | Aug 13, 2020 |
| Toshiba       | PORTEGE R930                | [9f944b581d](https://linux-hardware.org/?probe=9f944b581d) | Aug 09, 2020 |
| Sony          | VGN-CR32G_W                 | [faf8f6a6fa](https://linux-hardware.org/?probe=faf8f6a6fa) | Aug 08, 2020 |
| Sony          | VGN-CR32G_W                 | [421ed7dcba](https://linux-hardware.org/?probe=421ed7dcba) | Aug 08, 2020 |
| MECHREVO      | Code 01 Series PF5NU1G      | [4dffd28998](https://linux-hardware.org/?probe=4dffd28998) | Aug 07, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | [4319315cd0](https://linux-hardware.org/?probe=4319315cd0) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [b6111e69ca](https://linux-hardware.org/?probe=b6111e69ca) | Jul 19, 2020 |
| HP            | Pavilion Sleekbook 14 PC    | [b554a2c8ec](https://linux-hardware.org/?probe=b554a2c8ec) | Jul 14, 2020 |
| HP            | Pavilion dv6000 (GF659EA... | [84a4ec9209](https://linux-hardware.org/?probe=84a4ec9209) | Jul 09, 2020 |
| HP            | EliteBook 725 G4            | [941e94f528](https://linux-hardware.org/?probe=941e94f528) | Jul 09, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU27    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Dell          | XPS 13 9370                 | [e794850de2](https://linux-hardware.org/?probe=e794850de2) | Jul 05, 2020 |
| HP            | EliteBook 725 G4            | [b3e1336d2f](https://linux-hardware.org/?probe=b3e1336d2f) | Jul 04, 2020 |
| Acer          | Swift SF514-54GT            | [a5b63702a2](https://linux-hardware.org/?probe=a5b63702a2) | Jul 03, 2020 |
| Lenovo        | ThinkPad T420s 417429U      | [8d9ec3fd6e](https://linux-hardware.org/?probe=8d9ec3fd6e) | Jun 27, 2020 |
| ASUSTek       | UX305CA                     | [7b35a1c840](https://linux-hardware.org/?probe=7b35a1c840) | Jun 26, 2020 |
| Toshiba       | PORTEGE Z10t-A              | [dd0834c2dd](https://linux-hardware.org/?probe=dd0834c2dd) | Jun 23, 2020 |
| Lenovo        | IdeaPad U460 20056          | [31c7edc616](https://linux-hardware.org/?probe=31c7edc616) | Jun 17, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | [4add01698f](https://linux-hardware.org/?probe=4add01698f) | Jun 14, 2020 |
| Dell          | Latitude E7440              | [1664235765](https://linux-hardware.org/?probe=1664235765) | Jun 03, 2020 |
| Dell          | Latitude E7440              | [d71cf3dba2](https://linux-hardware.org/?probe=d71cf3dba2) | Jun 03, 2020 |
| Lenovo        | G550 2958                   | [a8c4b1a8cf](https://linux-hardware.org/?probe=a8c4b1a8cf) | Jun 01, 2020 |
| Lenovo        | ThinkPad L460 20FUCTO1WW    | [da2a23020c](https://linux-hardware.org/?probe=da2a23020c) | May 21, 2020 |
| Dell          | XPS 15 7590                 | [c91cd5679c](https://linux-hardware.org/?probe=c91cd5679c) | May 19, 2020 |
| Dell          | XPS 13 9360                 | [10e8823c6b](https://linux-hardware.org/?probe=10e8823c6b) | May 17, 2020 |
| Lenovo        | G550 2958                   | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Lenovo        | G550 2958                   | [cfd6e82a6f](https://linux-hardware.org/?probe=cfd6e82a6f) | May 11, 2020 |
| Acer          | Predator PH315-52           | [7adb1a873c](https://linux-hardware.org/?probe=7adb1a873c) | May 04, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | [09817eac19](https://linux-hardware.org/?probe=09817eac19) | May 01, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| ASUSTek       | T300LA                      | [c173e838c3](https://linux-hardware.org/?probe=c173e838c3) | Apr 26, 2020 |
| ASUSTek       | T300LA                      | [6311e7f4b5](https://linux-hardware.org/?probe=6311e7f4b5) | Apr 26, 2020 |
| Apple         | MacBookPro8,1               | [42636a47b1](https://linux-hardware.org/?probe=42636a47b1) | Apr 26, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | [a9cd8ef28f](https://linux-hardware.org/?probe=a9cd8ef28f) | Apr 22, 2020 |
| Acer          | Prespa1                     | [791259386e](https://linux-hardware.org/?probe=791259386e) | Apr 16, 2020 |
| Lenovo        | B50-30 20382                | [57b8f867a1](https://linux-hardware.org/?probe=57b8f867a1) | Apr 09, 2020 |
| Acer          | Aspire E5-473G              | [17f3a0e473](https://linux-hardware.org/?probe=17f3a0e473) | Apr 08, 2020 |
| Apple         | MacBookPro8,1               | [429fde3ebd](https://linux-hardware.org/?probe=429fde3ebd) | Apr 02, 2020 |
| Dell          | Latitude E6410              | [920a80dc90](https://linux-hardware.org/?probe=920a80dc90) | Mar 31, 2020 |
| Apple         | MacBookPro11,4              | [3c9bd63848](https://linux-hardware.org/?probe=3c9bd63848) | Mar 30, 2020 |
| Acer          | ConceptD CN715-71           | [2a99d0f76b](https://linux-hardware.org/?probe=2a99d0f76b) | Mar 28, 2020 |
| Acer          | ConceptD CN715-71           | [93d970f678](https://linux-hardware.org/?probe=93d970f678) | Mar 24, 2020 |
| Samsung       | RF510/RF410/RF710           | [daa4d098dc](https://linux-hardware.org/?probe=daa4d098dc) | Mar 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th E... | [b913bc5cc5](https://linux-hardware.org/?probe=b913bc5cc5) | Feb 18, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [819116ee69](https://linux-hardware.org/?probe=819116ee69) | Feb 16, 2020 |
| Acer          | ConceptD CN715-71           | [93c40180a2](https://linux-hardware.org/?probe=93c40180a2) | Feb 11, 2020 |
| Acer          | ConceptD CN715-71           | [f6c3a576c2](https://linux-hardware.org/?probe=f6c3a576c2) | Feb 11, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [627909b9e5](https://linux-hardware.org/?probe=627909b9e5) | Feb 04, 2020 |
| Dell          | Inspiron 7591               | [b33d5cddc5](https://linux-hardware.org/?probe=b33d5cddc5) | Jan 25, 2020 |
| ASUSTek       | U24E                        | [563b794d8a](https://linux-hardware.org/?probe=563b794d8a) | Dec 23, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | [011ab343ef](https://linux-hardware.org/?probe=011ab343ef) | Dec 22, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | [bb9da61133](https://linux-hardware.org/?probe=bb9da61133) | Dec 21, 2019 |
| Acer          | ConceptD CN715-71           | [54109739eb](https://linux-hardware.org/?probe=54109739eb) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | [5d75e45350](https://linux-hardware.org/?probe=5d75e45350) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | [fb27c8cabb](https://linux-hardware.org/?probe=fb27c8cabb) | Dec 20, 2019 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [adec400398](https://linux-hardware.org/?probe=adec400398) | Dec 19, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [86221df903](https://linux-hardware.org/?probe=86221df903) | Nov 30, 2019 |
| HP            | ZBook Studio G5             | [87503b1263](https://linux-hardware.org/?probe=87503b1263) | Aug 22, 2019 |
| ASUSTek       | X406UAR                     | [5e3ebad239](https://linux-hardware.org/?probe=5e3ebad239) | Jul 05, 2019 |
| Apple         | MacBookPro9,2               | [1d4494ee1f](https://linux-hardware.org/?probe=1d4494ee1f) | Jul 03, 2019 |
| Lenovo        | S20-30 20421                | [5c27867f6e](https://linux-hardware.org/?probe=5c27867f6e) | Jun 26, 2019 |
| Dell          | Inspiron 13-5378            | [f938ce631a](https://linux-hardware.org/?probe=f938ce631a) | Jun 17, 2019 |
| Dell          | Inspiron 13-5378            | [5e33156c57](https://linux-hardware.org/?probe=5e33156c57) | Jun 17, 2019 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0ab22425ea](https://linux-hardware.org/?probe=0ab22425ea) | May 28, 2019 |
| Apple         | MacBookPro11,5              | [ab95788992](https://linux-hardware.org/?probe=ab95788992) | May 18, 2019 |
| ASUSTek       | S500CA                      | [c0218275f7](https://linux-hardware.org/?probe=c0218275f7) | Apr 28, 2019 |
| Acer          | AO751h                      | [0ee57513c5](https://linux-hardware.org/?probe=0ee57513c5) | Apr 07, 2019 |
| MSI           | GE63VR 7RE                  | [635226b290](https://linux-hardware.org/?probe=635226b290) | May 31, 2018 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [ecd2f8138f](https://linux-hardware.org/?probe=ecd2f8138f) | Dec 27, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 48        | 15.19%  |
| Ubuntu 22.04                 | 26        | 8.23%   |
| Ubuntu 18.04                 | 19        | 6.01%   |
| Arch Rolling                 | 12        | 3.8%    |
| Fedora 33                    | 10        | 3.16%   |
| Pop!_OS 22.04                | 9         | 2.85%   |
| Fedora 38                    | 6         | 1.9%    |
| Pop!_OS 20.04                | 5         | 1.58%   |
| Debian 12                    | 5         | 1.58%   |
| Debian                       | 5         | 1.58%   |
| Arch                         | 5         | 1.58%   |
| Zorin 16                     | 4         | 1.27%   |
| OpenMandriva 23.01           | 4         | 1.27%   |
| Linux Mint 21                | 4         | 1.27%   |
| Fedora 40                    | 4         | 1.27%   |
| Fedora 39                    | 4         | 1.27%   |
| Fedora 37                    | 4         | 1.27%   |
| EndeavourOS Rolling          | 4         | 1.27%   |
| Debian Testing               | 4         | 1.27%   |
| Debian 11                    | 4         | 1.27%   |
| ArcoLinux Rolling            | 4         | 1.27%   |
| Xubuntu 20.04                | 3         | 0.95%   |
| Ubuntu 24.04                 | 3         | 0.95%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.95%   |
| Linux Mint 21.2              | 3         | 0.95%   |
| Linux Mint 21.1              | 3         | 0.95%   |
| Linux Mint 20                | 3         | 0.95%   |
| Kubuntu 22.04                | 3         | 0.95%   |
| KDE neon 22.04               | 3         | 0.95%   |
| Fedora 41                    | 3         | 0.95%   |
| Fedora 36                    | 3         | 0.95%   |
| Fedora 32                    | 3         | 0.95%   |
| Elementary 6.1               | 3         | 0.95%   |
| Zorin 17                     | 2         | 0.63%   |
| Zorin 15                     | 2         | 0.63%   |
| Ubuntu 24.10                 | 2         | 0.63%   |
| Ubuntu 21.10                 | 2         | 0.63%   |
| SteamOS 3.5.7                | 2         | 0.63%   |
| OpenMandriva 4.3             | 2         | 0.63%   |
| OpenMandriva 24.07           | 2         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 104       | 35.62%  |
| Fedora        | 29        | 9.93%   |
| Debian        | 18        | 6.16%   |
| Pop!_OS       | 17        | 5.82%   |
| Arch          | 16        | 5.48%   |
| OpenMandriva  | 15        | 5.14%   |
| Linux Mint    | 15        | 5.14%   |
| Zorin         | 8         | 2.74%   |
| Manjaro       | 7         | 2.4%    |
| Kubuntu       | 7         | 2.4%    |
| KDE neon      | 5         | 1.71%   |
| ArcoLinux     | 5         | 1.71%   |
| Xubuntu       | 4         | 1.37%   |
| EndeavourOS   | 4         | 1.37%   |
| openSUSE      | 3         | 1.03%   |
| NixOS         | 3         | 1.03%   |
| Lubuntu       | 3         | 1.03%   |
| Elementary    | 3         | 1.03%   |
| Ubuntu Unity  | 2         | 0.68%   |
| Ubuntu Budgie | 2         | 0.68%   |
| SteamOS       | 2         | 0.68%   |
| ROSA          | 2         | 0.68%   |
| RHEL          | 2         | 0.68%   |
| Kali          | 2         | 0.68%   |
| Gentoo        | 2         | 0.68%   |
| Garuda Linux  | 2         | 0.68%   |
| Endless       | 2         | 0.68%   |
| Deepin        | 2         | 0.68%   |
| Clear Linux   | 2         | 0.68%   |
| Solus         | 1         | 0.34%   |
| Q4OS          | 1         | 0.34%   |
| MX            | 1         | 0.34%   |
| LMDE          | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.15.0-56-generic          | 6         | 1.65%   |
| 5.4.0-48-generic           | 5         | 1.37%   |
| 5.15.0-46-generic          | 5         | 1.37%   |
| 6.2.0-39-generic           | 4         | 1.1%    |
| 6.1.1-desktop-1omv2290     | 4         | 1.1%    |
| 5.9.8-200.fc33.x86_64      | 4         | 1.1%    |
| 5.4.0-42-generic           | 4         | 1.1%    |
| 5.4.0-40-generic           | 4         | 1.1%    |
| 5.3.0-62-generic           | 4         | 1.1%    |
| 5.11.0-43-generic          | 4         | 1.1%    |
| 6.8.0-45-generic           | 3         | 0.82%   |
| 6.8.0-0.rc6.49.fc40.x86_64 | 3         | 0.82%   |
| 6.2.15-300.fc38.x86_64     | 3         | 0.82%   |
| 6.2.0-26-generic           | 3         | 0.82%   |
| 5.4.0-65-generic           | 3         | 0.82%   |
| 5.4.0-52-generic           | 3         | 0.82%   |
| 5.4.0-47-generic           | 3         | 0.82%   |
| 5.4.0-37-generic           | 3         | 0.82%   |
| 5.4.0-29-generic           | 3         | 0.82%   |
| 5.15.0-41-generic          | 3         | 0.82%   |
| 5.13.0-28-generic          | 3         | 0.82%   |
| 5.11.0-38-generic          | 3         | 0.82%   |
| 6.9.3-76060903-generic     | 2         | 0.55%   |
| 6.8.9-300.fc40.x86_64      | 2         | 0.55%   |
| 6.8.12-amd64               | 2         | 0.55%   |
| 6.8.0-49-generic           | 2         | 0.55%   |
| 6.5.12-300.fc39.x86_64     | 2         | 0.55%   |
| 6.4.6-76060406-generic     | 2         | 0.55%   |
| 6.3.8-200.fc38.x86_64      | 2         | 0.55%   |
| 6.3.5-desktop-3omv2390     | 2         | 0.55%   |
| 6.2.6-desktop-1omv2390     | 2         | 0.55%   |
| 6.2.10-300.fc38.x86_64     | 2         | 0.55%   |
| 6.2.0-32-generic           | 2         | 0.55%   |
| 6.2.0-20-generic           | 2         | 0.55%   |
| 6.11.0-9-generic           | 2         | 0.55%   |
| 6.10.3-200.fc40.x86_64     | 2         | 0.55%   |
| 6.10.0-desktop-1omv2490    | 2         | 0.55%   |
| 6.1.52-valve9-1-neptune-61 | 2         | 0.55%   |
| 6.1.14-200.fc37.x86_64     | 2         | 0.55%   |
| 6.0.6-76060006-generic     | 2         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 10.98%  |
| 5.15.0  | 35        | 10.12%  |
| 5.11.0  | 13        | 3.76%   |
| 6.2.0   | 12        | 3.47%   |
| 6.8.0   | 11        | 3.18%   |
| 5.8.0   | 11        | 3.18%   |
| 5.13.0  | 11        | 3.18%   |
| 5.19.0  | 8         | 2.31%   |
| 5.3.0   | 7         | 2.02%   |
| 4.18.0  | 7         | 2.02%   |
| 4.15.0  | 7         | 2.02%   |
| 6.1.0   | 6         | 1.73%   |
| 5.18.0  | 6         | 1.73%   |
| 5.10.0  | 5         | 1.45%   |
| 6.1.1   | 4         | 1.16%   |
| 5.9.8   | 4         | 1.16%   |
| 5.0.0   | 4         | 1.16%   |
| 6.9.3   | 3         | 0.87%   |
| 6.8.9   | 3         | 0.87%   |
| 6.5.0   | 3         | 0.87%   |
| 6.3.8   | 3         | 0.87%   |
| 6.3.5   | 3         | 0.87%   |
| 6.2.15  | 3         | 0.87%   |
| 6.2.10  | 3         | 0.87%   |
| 6.11.0  | 3         | 0.87%   |
| 6.8.12  | 2         | 0.58%   |
| 6.8.10  | 2         | 0.58%   |
| 6.6.7   | 2         | 0.58%   |
| 6.6.1   | 2         | 0.58%   |
| 6.5.12  | 2         | 0.58%   |
| 6.4.6   | 2         | 0.58%   |
| 6.2.6   | 2         | 0.58%   |
| 6.10.3  | 2         | 0.58%   |
| 6.10.0  | 2         | 0.58%   |
| 6.1.52  | 2         | 0.58%   |
| 6.1.14  | 2         | 0.58%   |
| 6.0.7   | 2         | 0.58%   |
| 6.0.6   | 2         | 0.58%   |
| 6.0.0   | 2         | 0.58%   |
| 5.4.5   | 2         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 45        | 13.6%   |
| 5.15    | 41        | 12.39%  |
| 6.2     | 18        | 5.44%   |
| 5.8     | 17        | 5.14%   |
| 5.13    | 17        | 5.14%   |
| 6.8     | 16        | 4.83%   |
| 6.1     | 15        | 4.53%   |
| 5.11    | 14        | 4.23%   |
| 6.6     | 11        | 3.32%   |
| 5.19    | 11        | 3.32%   |
| 5.10    | 11        | 3.32%   |
| 5.18    | 10        | 3.02%   |
| 6.0     | 8         | 2.42%   |
| 6.5     | 7         | 2.11%   |
| 6.3     | 7         | 2.11%   |
| 5.9     | 7         | 2.11%   |
| 5.3     | 7         | 2.11%   |
| 4.18    | 7         | 2.11%   |
| 4.15    | 7         | 2.11%   |
| 6.4     | 6         | 1.81%   |
| 5.16    | 6         | 1.81%   |
| 6.9     | 5         | 1.51%   |
| 5.0     | 5         | 1.51%   |
| 6.11    | 4         | 1.21%   |
| 6.10    | 4         | 1.21%   |
| 5.6     | 4         | 1.21%   |
| 5.17    | 4         | 1.21%   |
| 5.12    | 4         | 1.21%   |
| 4.19    | 3         | 0.91%   |
| 6.12    | 2         | 0.6%    |
| 5.5     | 2         | 0.6%    |
| 6.7     | 1         | 0.3%    |
| 5.7     | 1         | 0.3%    |
| 5.14    | 1         | 0.3%    |
| 4.4     | 1         | 0.3%    |
| 4.16    | 1         | 0.3%    |
| 3.10    | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 280       | 99.29%  |
| i686   | 2         | 0.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 163       | 54.88%  |
| KDE5            | 46        | 15.49%  |
| Unknown         | 25        | 8.42%   |
| X-Cinnamon      | 16        | 5.39%   |
| XFCE            | 10        | 3.37%   |
| LXQt            | 6         | 2.02%   |
| KDE6            | 6         | 2.02%   |
| KDE             | 6         | 2.02%   |
| Cinnamon        | 4         | 1.35%   |
| Pantheon        | 3         | 1.01%   |
| Unity           | 2         | 0.67%   |
| i3              | 2         | 0.67%   |
| Budgie          | 2         | 0.67%   |
| MATE            | 1         | 0.34%   |
| KDE4            | 1         | 0.34%   |
| Hyprland        | 1         | 0.34%   |
| GNOME Flashback | 1         | 0.34%   |
| GNOME Classic   | 1         | 0.34%   |
| Deepin          | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 192       | 65.31%  |
| Wayland | 78        | 26.53%  |
| Unknown | 15        | 5.1%    |
| Tty     | 9         | 3.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 119       | 40.61%  |
| GDM3    | 56        | 19.11%  |
| GDM     | 46        | 15.7%   |
| SDDM    | 45        | 15.36%  |
| LightDM | 22        | 7.51%   |
| TDM     | 4         | 1.37%   |
| KDM     | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 117       | 39.66%  |
| en_SG      | 114       | 38.64%  |
| Unknown    | 17        | 5.76%   |
| zh_CN      | 14        | 4.75%   |
| C          | 7         | 2.37%   |
| en_IN      | 6         | 2.03%   |
| en_GB      | 6         | 2.03%   |
| en_PH      | 3         | 1.02%   |
| de_DE      | 3         | 1.02%   |
| id_ID      | 2         | 0.68%   |
| en_AU      | 2         | 0.68%   |
| zh_SG      | 1         | 0.34%   |
| zh_CN.UTF8 | 1         | 0.34%   |
| ru_UA      | 1         | 0.34%   |
| en_IE      | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 196       | 68.29%  |
| BIOS | 91        | 31.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 217       | 75.35%  |
| Btrfs   | 34        | 11.81%  |
| Overlay | 15        | 5.21%   |
| Tmpfs   | 10        | 3.47%   |
| Unknown | 6         | 2.08%   |
| Xfs     | 4         | 1.39%   |
| Zfs     | 2         | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 154       | 54.04%  |
| Unknown | 122       | 42.81%  |
| MBR     | 9         | 3.16%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 256       | 88.58%  |
| Yes       | 33        | 11.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 173       | 60.07%  |
| Yes       | 115       | 39.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 74        | 26.24%  |
| Dell                   | 54        | 19.15%  |
| ASUSTek Computer       | 46        | 16.31%  |
| Acer                   | 31        | 10.99%  |
| Hewlett-Packard        | 13        | 4.61%   |
| Apple                  | 13        | 4.61%   |
| MSI                    | 6         | 2.13%   |
| Sony                   | 5         | 1.77%   |
| MECHREVO               | 5         | 1.77%   |
| HUAWEI                 | 4         | 1.42%   |
| Timi                   | 3         | 1.06%   |
| Unknown                | 3         | 1.06%   |
| Valve                  | 2         | 0.71%   |
| Toshiba                | 2         | 0.71%   |
| Samsung Electronics    | 2         | 0.71%   |
| Fujitsu                | 2         | 0.71%   |
| Foxconn                | 2         | 0.71%   |
| Aftershock             | 2         | 0.71%   |
| TUXEDO                 | 1         | 0.35%   |
| System76               | 1         | 0.35%   |
| Razer                  | 1         | 0.35%   |
| Notebook               | 1         | 0.35%   |
| MicroByte              | 1         | 0.35%   |
| Google                 | 1         | 0.35%   |
| EUROCOM                | 1         | 0.35%   |
| COPELION INTERNATIONAL | 1         | 0.35%   |
| Chuwi                  | 1         | 0.35%   |
| Beelink                | 1         | 0.35%   |
| AZW                    | 1         | 0.35%   |
| AMI                    | 1         | 0.35%   |
| Alienware              | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Dell Inspiron 15 5510                                 | 3         | 1.06%   |
| Acer Swift SF314-57G                                  | 3         | 1.06%   |
| Unknown                                               | 3         | 1.06%   |
| Valve Jupiter                                         | 2         | 0.71%   |
| Lenovo ThinkPad X220 42911H8                          | 2         | 0.71%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                      | 2         | 0.71%   |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 0.71%   |
| Lenovo IdeaPad 100-14IBY 80MH                         | 2         | 0.71%   |
| HUAWEI MACHD-WXX9                                     | 2         | 0.71%   |
| HP Compaq 6510b                                       | 2         | 0.71%   |
| Foxconn Kangaroo Mobile Desktop                       | 2         | 0.71%   |
| Dell XPS 13 9310                                      | 2         | 0.71%   |
| Dell XPS 13 7390                                      | 2         | 0.71%   |
| Dell Latitude E7250                                   | 2         | 0.71%   |
| Dell Latitude 3320                                    | 2         | 0.71%   |
| Dell Latitude 3120                                    | 2         | 0.71%   |
| Dell Inspiron 1525                                    | 2         | 0.71%   |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC              | 2         | 0.71%   |
| ASUS T300LA                                           | 2         | 0.71%   |
| ASUS K45VM                                            | 2         | 0.71%   |
| Apple MacBookPro9,2                                   | 2         | 0.71%   |
| Apple MacBookPro8,1                                   | 2         | 0.71%   |
| Apple MacBookPro11,5                                  | 2         | 0.71%   |
| Acer ConceptD CN715-71                                | 2         | 0.71%   |
| TUXEDO Stellaris Intel Gen5                           | 1         | 0.35%   |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.35%   |
| Toshiba PORTEGE R930                                  | 1         | 0.35%   |
| Timi TM1701                                           | 1         | 0.35%   |
| Timi RedmiBook 15                                     | 1         | 0.35%   |
| Timi Redmi Book Pro 14 2022                           | 1         | 0.35%   |
| System76 Oryx Pro                                     | 1         | 0.35%   |
| Sony VPCSB36FG                                        | 1         | 0.35%   |
| Sony VPCCA15FG                                        | 1         | 0.35%   |
| Sony VGN-CR32G_W                                      | 1         | 0.35%   |
| Sony SVF1531V8CW                                      | 1         | 0.35%   |
| Sony SVE11116FGW                                      | 1         | 0.35%   |
| Samsung RF510/RF410/RF710                             | 1         | 0.35%   |
| Samsung 305U1A                                        | 1         | 0.35%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.35%   |
| Notebook P65_P67SE                                    | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 37        | 13.12%  |
| Dell Inspiron      | 19        | 6.74%   |
| Dell Latitude      | 17        | 6.03%   |
| Acer Aspire        | 15        | 5.32%   |
| Lenovo IdeaPad     | 14        | 4.96%   |
| ASUS VivoBook      | 14        | 4.96%   |
| Dell XPS           | 11        | 3.9%    |
| Lenovo Legion      | 10        | 3.55%   |
| Acer Swift         | 10        | 3.55%   |
| Lenovo Yoga        | 6         | 2.13%   |
| ASUS ZenBook       | 6         | 2.13%   |
| Dell Precision     | 5         | 1.77%   |
| ASUS ASUS          | 5         | 1.77%   |
| Apple MacBookPro11 | 5         | 1.77%   |
| HP Pavilion        | 4         | 1.42%   |
| HP ZBook           | 3         | 1.06%   |
| HP EliteBook       | 3         | 1.06%   |
| Unknown            | 3         | 1.06%   |
| Valve Jupiter      | 2         | 0.71%   |
| Toshiba PORTEGE    | 2         | 0.71%   |
| Lenovo ThinkBook   | 2         | 0.71%   |
| HUAWEI MACHD-WXX9  | 2         | 0.71%   |
| HP Compaq          | 2         | 0.71%   |
| Fujitsu LIFEBOOK   | 2         | 0.71%   |
| Foxconn Kangaroo   | 2         | 0.71%   |
| ASUS TUF           | 2         | 0.71%   |
| ASUS T300LA        | 2         | 0.71%   |
| ASUS ROG           | 2         | 0.71%   |
| ASUS K45VM         | 2         | 0.71%   |
| Apple MacBookPro9  | 2         | 0.71%   |
| Apple MacBookPro8  | 2         | 0.71%   |
| Acer Predator      | 2         | 0.71%   |
| Acer ConceptD      | 2         | 0.71%   |
| TUXEDO Stellaris   | 1         | 0.35%   |
| Timi TM1701        | 1         | 0.35%   |
| Timi RedmiBook     | 1         | 0.35%   |
| Timi Redmi         | 1         | 0.35%   |
| System76 Oryx      | 1         | 0.35%   |
| Sony VPCSB36FG     | 1         | 0.35%   |
| Sony VPCCA15FG     | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 40        | 14.18%  |
| 2019 | 33        | 11.7%   |
| 2020 | 26        | 9.22%   |
| 2018 | 24        | 8.51%   |
| 2022 | 21        | 7.45%   |
| 2011 | 18        | 6.38%   |
| 2017 | 15        | 5.32%   |
| 2023 | 14        | 4.96%   |
| 2015 | 14        | 4.96%   |
| 2014 | 13        | 4.61%   |
| 2012 | 13        | 4.61%   |
| 2016 | 12        | 4.26%   |
| 2013 | 11        | 3.9%    |
| 2008 | 9         | 3.19%   |
| 2024 | 6         | 2.13%   |
| 2010 | 5         | 1.77%   |
| 2007 | 5         | 1.77%   |
| 2009 | 3         | 1.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 282       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 239       | 84.15%  |
| Enabled  | 45        | 15.85%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 280       | 99.29%  |
| Yes  | 2         | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 75        | 26.13%  |
| 4.01-8.0    | 68        | 23.69%  |
| 8.01-16.0   | 48        | 16.72%  |
| 3.01-4.0    | 38        | 13.24%  |
| 32.01-64.0  | 33        | 11.5%   |
| 24.01-32.0  | 8         | 2.79%   |
| 1.01-2.0    | 8         | 2.79%   |
| 64.01-256.0 | 6         | 2.09%   |
| 2.01-3.0    | 3         | 1.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 80        | 24.32%  |
| 2.01-3.0   | 79        | 24.01%  |
| 4.01-8.0   | 72        | 21.88%  |
| 3.01-4.0   | 56        | 17.02%  |
| 8.01-16.0  | 24        | 7.29%   |
| 0.51-1.0   | 12        | 3.65%   |
| 24.01-32.0 | 2         | 0.61%   |
| 16.01-24.0 | 2         | 0.61%   |
| 0.01-0.5   | 2         | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 205       | 70.21%  |
| 2      | 71        | 24.32%  |
| 3      | 13        | 4.45%   |
| 0      | 2         | 0.68%   |
| 4      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 238       | 84.1%   |
| Yes       | 45        | 15.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 64.08%  |
| No        | 102       | 35.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 271       | 96.1%   |
| No        | 11        | 3.9%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 242       | 84.32%  |
| No        | 45        | 15.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Singapore | 282       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Singapore            | 274       | 96.82%  |
| Jurong West          | 4         | 1.41%   |
| Yio Chu Kang         | 1         | 0.35%   |
| Sembawang Estate     | 1         | 0.35%   |
| Queenstown Estate    | 1         | 0.35%   |
| Kampong Ulu Jurong   | 1         | 0.35%   |
| Bukit Batok New Town | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 65        | 114    | 17.57%  |
| SanDisk                     | 34        | 48     | 9.19%   |
| WDC                         | 30        | 54     | 8.11%   |
| SK hynix                    | 26        | 29     | 7.03%   |
| Unknown                     | 23        | 36     | 6.22%   |
| Seagate                     | 23        | 30     | 6.22%   |
| Toshiba                     | 20        | 29     | 5.41%   |
| Micron Technology           | 15        | 17     | 4.05%   |
| Intel                       | 15        | 17     | 4.05%   |
| HGST                        | 10        | 15     | 2.7%    |
| Hitachi                     | 9         | 9      | 2.43%   |
| KIOXIA                      | 8         | 8      | 2.16%   |
| Apple                       | 7         | 8      | 1.89%   |
| Kingston                    | 6         | 7      | 1.62%   |
| Crucial                     | 6         | 6      | 1.62%   |
| Phison                      | 4         | 6      | 1.08%   |
| External                    | 4         | 4      | 1.08%   |
| China                       | 4         | 4      | 1.08%   |
| YMTC                        | 3         | 4      | 0.81%   |
| Yangtze Memory Technologies | 3         | 3      | 0.81%   |
| Transcend                   | 3         | 4      | 0.81%   |
| Silicon Motion              | 3         | 5      | 0.81%   |
| JMicron Technology          | 3         | 6      | 0.81%   |
| UMIS                        | 2         | 3      | 0.54%   |
| SPCC                        | 2         | 2      | 0.54%   |
| Phison Electronics          | 2         | 2      | 0.54%   |
| Patriot                     | 2         | 2      | 0.54%   |
| Micron/Crucial Technology   | 2         | 2      | 0.54%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.54%   |
| LITEON                      | 2         | 3      | 0.54%   |
| Lexar                       | 2         | 2      | 0.54%   |
| Lenovo                      | 2         | 2      | 0.54%   |
| Hewlett-Packard             | 2         | 3      | 0.54%   |
| FORESEE                     | 2         | 2      | 0.54%   |
| ACASIS                      | 2         | 2      | 0.54%   |
| A-DATA Technology           | 2         | 2      | 0.54%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.27%   |
| TO Exter                    | 1         | 1      | 0.27%   |
| Team                        | 1         | 1      | 0.27%   |
| SSK                         | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 7         | 1.81%   |
| Unknown MMC Card  64GB                                | 5         | 1.3%    |
| Toshiba MQ04ABF100 1TB                                | 5         | 1.3%    |
| Samsung NVMe SSD Drive 1024GB                         | 4         | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 4         | 1.04%   |
| HGST HTS721010A9E630 1TB                              | 4         | 1.04%   |
| External USB3.0 1TB                                   | 4         | 1.04%   |
| Unknown MMC Card  128GB                               | 3         | 0.78%   |
| Toshiba MQ01ABD100 1TB                                | 3         | 0.78%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                  | 3         | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 3         | 0.78%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 3         | 0.78%   |
| SanDisk NVMe SSD Drive 512GB                          | 3         | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 3         | 0.78%   |
| JMicron Generic 500GB                                 | 3         | 0.78%   |
| Intel SSD 660P Series 1024GB                          | 3         | 0.78%   |
| WDC WDS500G2X0C-00L350 500GB                          | 2         | 0.52%   |
| WDC WDS100T2X0C-00L350 1TB                            | 2         | 0.52%   |
| WDC WD7500BPVT-80HXZT3 752GB                          | 2         | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB                          | 2         | 0.52%   |
| WDC WD10SPZX-21Z10T0 1TB                              | 2         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB                              | 2         | 0.52%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                    | 2         | 0.52%   |
| WDC PC SN720 SED SDAQNTW-1T00 1TB                     | 2         | 0.52%   |
| Unknown NVMe SSD Drive 512GB                          | 2         | 0.52%   |
| Unknown NVMe SSD Drive 1024GB                         | 2         | 0.52%   |
| Unknown MMC Card  32GB                                | 2         | 0.52%   |
| Unknown MMC Card  256GB                               | 2         | 0.52%   |
| Toshiba MQ01ABF050 500GB                              | 2         | 0.52%   |
| Toshiba MK5055GSX 500GB                               | 2         | 0.52%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB                | 2         | 0.52%   |
| SK hynix SKHynix_HFS001TEJ9X115N 1TB                  | 2         | 0.52%   |
| SK hynix HFM512GDJTNG-8310A 512GB                     | 2         | 0.52%   |
| SK hynix HFM001TD3JX013N 1024GB                       | 2         | 0.52%   |
| Seagate ST1000LM049-2GH172 1TB                        | 2         | 0.52%   |
| Seagate Expansion 1TB                                 | 2         | 0.52%   |
| Sandisk WD_BLACK SN850X 1000GB                        | 2         | 0.52%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 2         | 0.52%   |
| SanDisk SSD PLUS 480GB                                | 2         | 0.52%   |
| SanDisk SSD PLUS 240GB                                | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 27     | 25%     |
| Toshiba             | 16        | 24     | 19.05%  |
| WDC                 | 15        | 20     | 17.86%  |
| HGST                | 10        | 15     | 11.9%   |
| Hitachi             | 9         | 9      | 10.71%  |
| External            | 4         | 4      | 4.76%   |
| JMicron Technology  | 3         | 6      | 3.57%   |
| Unknown             | 1         | 2      | 1.19%   |
| TO Exter            | 1         | 1      | 1.19%   |
| Samsung Electronics | 1         | 3      | 1.19%   |
| SAGE                | 1         | 1      | 1.19%   |
| Fujitsu             | 1         | 1      | 1.19%   |
| Apple               | 1         | 1      | 1.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 68     | 31.58%  |
| SanDisk             | 16        | 26     | 16.84%  |
| Micron Technology   | 5         | 6      | 5.26%   |
| Apple               | 5         | 5      | 5.26%   |
| SK hynix            | 4         | 4      | 4.21%   |
| Crucial             | 4         | 4      | 4.21%   |
| China               | 4         | 4      | 4.21%   |
| Transcend           | 3         | 4      | 3.16%   |
| WDC                 | 2         | 3      | 2.11%   |
| SPCC                | 2         | 2      | 2.11%   |
| Patriot             | 2         | 2      | 2.11%   |
| LITEON              | 2         | 3      | 2.11%   |
| Kingston            | 2         | 3      | 2.11%   |
| FORESEE             | 2         | 2      | 2.11%   |
| Toshiba             | 1         | 1      | 1.05%   |
| Ramos Technology    | 1         | 2      | 1.05%   |
| ORICO               | 1         | 1      | 1.05%   |
| OCZ                 | 1         | 1      | 1.05%   |
| LT                  | 1         | 2      | 1.05%   |
| Lexar               | 1         | 1      | 1.05%   |
| LALAK               | 1         | 1      | 1.05%   |
| Hewlett-Packard     | 1         | 2      | 1.05%   |
| Haizhide            | 1         | 1      | 1.05%   |
| GALAX               | 1         | 1      | 1.05%   |
| CT1000MX            | 1         | 2      | 1.05%   |
| Unknown             | 1         | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 154       | 224    | 45.29%  |
| SSD     | 88        | 152    | 25.88%  |
| HDD     | 78        | 114    | 22.94%  |
| MMC     | 17        | 26     | 5%      |
| Unknown | 3         | 3      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 153       | 218    | 46.93%  |
| SATA | 137       | 245    | 42.02%  |
| SAS  | 19        | 30     | 5.83%   |
| MMC  | 17        | 26     | 5.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 106       | 179    | 63.86%  |
| 0.51-1.0   | 52        | 77     | 31.33%  |
| 1.01-2.0   | 8         | 10     | 4.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 79        | 26.25%  |
| 251-500        | 70        | 23.26%  |
| 501-1000       | 55        | 18.27%  |
| 1001-2000      | 28        | 9.3%    |
| 51-100         | 21        | 6.98%   |
| 1-20           | 18        | 5.98%   |
| More than 3000 | 9         | 2.99%   |
| 21-50          | 9         | 2.99%   |
| Unknown        | 7         | 2.33%   |
| 2001-3000      | 5         | 1.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 106       | 34.3%   |
| 21-50          | 59        | 19.09%  |
| 101-250        | 46        | 14.89%  |
| 51-100         | 33        | 10.68%  |
| 251-500        | 28        | 9.06%   |
| 501-1000       | 19        | 6.15%   |
| Unknown        | 7         | 2.27%   |
| 1001-2000      | 6         | 1.94%   |
| More than 3000 | 2         | 0.65%   |
| 2001-3000      | 2         | 0.65%   |
| 0              | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 10%     |
| WDC WD5000BPVT-16HXZT1 500GB       | 1         | 1      | 10%     |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 2      | 10%     |
| SK hynix SC210 2.5 7MM 128GB SSD   | 1         | 1      | 10%     |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 10%     |
| Seagate ST1000LM024 HN-M 1TB       | 1         | 1      | 10%     |
| SanDisk SSD U100 24GB              | 1         | 1      | 10%     |
| Hitachi HTS545032B9A300 320GB      | 1         | 1      | 10%     |
| Hitachi HTS541010A9E680 1TB        | 1         | 1      | 10%     |
| China SSD 128GB                    | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 3         | 4      | 30%     |
| Seagate  | 2         | 2      | 20%     |
| Hitachi  | 2         | 2      | 20%     |
| SK hynix | 1         | 1      | 10%     |
| SanDisk  | 1         | 1      | 10%     |
| China    | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 4      | 42.86%  |
| Seagate | 2         | 2      | 28.57%  |
| Hitachi | 2         | 2      | 28.57%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 8      | 70%     |
| SSD  | 3         | 3      | 30%     |

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
| Detected | 158       | 260    | 52.49%  |
| Works    | 133       | 248    | 44.19%  |
| Malfunc  | 10        | 11     | 3.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 161       | 46.4%   |
| Samsung Electronics                     | 38        | 10.95%  |
| SanDisk                                 | 30        | 8.65%   |
| AMD                                     | 26        | 7.49%   |
| SK hynix                                | 22        | 6.34%   |
| Micron Technology                       | 10        | 2.88%   |
| KIOXIA                                  | 7         | 2.02%   |
| Phison Electronics                      | 6         | 1.73%   |
| Yangtze Memory Technologies             | 5         | 1.44%   |
| Toshiba America Info Systems            | 5         | 1.44%   |
| Silicon Motion                          | 4         | 1.15%   |
| Micron/Crucial Technology               | 4         | 1.15%   |
| Kingston Technology Company             | 4         | 1.15%   |
| ADATA Technology                        | 4         | 1.15%   |
| Shenzhen Longsys Electronics            | 3         | 0.86%   |
| Nvidia                                  | 3         | 0.86%   |
| Union Memory (Shenzhen)                 | 2         | 0.58%   |
| Seagate Technology                      | 2         | 0.58%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.58%   |
| Lenovo                                  | 2         | 0.58%   |
| Transcend                               | 1         | 0.29%   |
| Shenzhen Unionmemory Information System | 1         | 0.29%   |
| Marvell Technology Group                | 1         | 0.29%   |
| INNOGRIT                                | 1         | 0.29%   |
| ASMedia Technology                      | 1         | 0.29%   |
| Apple                                   | 1         | 0.29%   |
| Unknown                                 | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 25        | 6.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 21        | 5.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 4.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 4.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 4.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 3.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 3.03%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 10        | 2.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 2.75%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 8         | 2.2%    |
| Intel SSD 660P Series                                                          | 8         | 2.2%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 1.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 1.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.93%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 6         | 1.65%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 6         | 1.65%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 1.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 1.38%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 1.38%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 1.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.38%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 4         | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4         | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.1%    |
| Yangtze Memory PC300 NVMe SSD (DRAM-less)                                      | 3         | 0.83%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 3         | 0.83%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.83%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 3         | 0.83%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.83%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 0.83%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 0.83%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 0.83%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 3         | 0.83%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.83%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 155       | 44.8%   |
| NVMe | 154       | 44.51%  |
| RAID | 27        | 7.8%    |
| IDE  | 10        | 2.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 224       | 79.43%  |
| AMD    | 58        | 20.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 3.55%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 3.55%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 3.19%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 2.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.77%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 1.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.77%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 1.77%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 1.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.42%   |
| Intel 12th Gen Core i7-12700H                 | 4         | 1.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.06%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.06%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 1.06%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 1.06%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.06%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz       | 3         | 1.06%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 1.06%   |
| AMD Ryzen 7 8845HS w/ Radeon 780M Graphics    | 3         | 1.06%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.06%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.06%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 0.71%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.71%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.71%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.71%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 2         | 0.71%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.71%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 2         | 0.71%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.71%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.71%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.71%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.71%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 77        | 27.3%   |
| Intel Core i5           | 53        | 18.79%  |
| Other                   | 46        | 16.31%  |
| AMD Ryzen 7             | 23        | 8.16%   |
| Intel Celeron           | 14        | 4.96%   |
| AMD Ryzen 5             | 13        | 4.61%   |
| Intel Core 2 Duo        | 11        | 3.9%    |
| Intel Core i3           | 6         | 2.13%   |
| AMD Ryzen 7 PRO         | 5         | 1.77%   |
| Intel Xeon              | 4         | 1.42%   |
| Intel Pentium Silver    | 4         | 1.42%   |
| Intel Atom              | 4         | 1.42%   |
| Intel Core i9           | 3         | 1.06%   |
| AMD Ryzen 9             | 3         | 1.06%   |
| Intel Pentium Dual      | 2         | 0.71%   |
| Intel Core m3           | 2         | 0.71%   |
| AMD Ryzen 3             | 2         | 0.71%   |
| Intel Core 2            | 1         | 0.35%   |
| Intel Core              | 1         | 0.35%   |
| AMD Turion 64 X2 Mobile | 1         | 0.35%   |
| AMD Ryzen 5 PRO         | 1         | 0.35%   |
| AMD PRO A10             | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |
| AMD E1                  | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD A8                  | 1         | 0.35%   |
| AMD A6                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 103       | 36.52%  |
| 2      | 98        | 34.75%  |
| 8      | 40        | 14.18%  |
| 6      | 21        | 7.45%   |
| 14     | 9         | 3.19%   |
| 10     | 5         | 1.77%   |
| 24     | 3         | 1.06%   |
| 1      | 2         | 0.71%   |
| 12     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 282       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 230       | 80.7%   |
| 1      | 55        | 19.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 279       | 98.94%  |
| 32-bit         | 2         | 0.71%   |
| Unknown        | 1         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 101       | 34.12%  |
| 0x806ea    | 14        | 4.73%   |
| 0x806ec    | 13        | 4.39%   |
| 0x206a7    | 13        | 4.39%   |
| 0x306a9    | 12        | 4.05%   |
| 0x0a50000c | 11        | 3.72%   |
| 0x906ea    | 10        | 3.38%   |
| 0x806c1    | 9         | 3.04%   |
| 0x40651    | 7         | 2.36%   |
| 0x806e9    | 6         | 2.03%   |
| 0x306d4    | 6         | 2.03%   |
| 0x806eb    | 5         | 1.69%   |
| 0x6fd      | 5         | 1.69%   |
| 0x806d1    | 4         | 1.35%   |
| 0x506e3    | 4         | 1.35%   |
| 0x406e3    | 4         | 1.35%   |
| 0x1067a    | 4         | 1.35%   |
| 0x08108109 | 4         | 1.35%   |
| 0xa0652    | 3         | 1.01%   |
| 0x806c2    | 3         | 1.01%   |
| 0x706e5    | 3         | 1.01%   |
| 0x706a1    | 3         | 1.01%   |
| 0x40661    | 3         | 1.01%   |
| 0x306c3    | 3         | 1.01%   |
| 0x20655    | 3         | 1.01%   |
| 0x0a404102 | 3         | 1.01%   |
| 0x08600106 | 3         | 1.01%   |
| 0x906e9    | 2         | 0.68%   |
| 0x906c0    | 2         | 0.68%   |
| 0x906a3    | 2         | 0.68%   |
| 0x706a8    | 2         | 0.68%   |
| 0x406c3    | 2         | 0.68%   |
| 0x30678    | 2         | 0.68%   |
| 0x106c2    | 2         | 0.68%   |
| 0x0a404101 | 2         | 0.68%   |
| 0x08600103 | 2         | 0.68%   |
| 0x08108102 | 2         | 0.68%   |
| 0x06006705 | 2         | 0.68%   |
| 0xb06a2    | 1         | 0.34%   |
| 0xb0671    | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 65        | 23.05%  |
| Unknown          | 28        | 9.93%   |
| TigerLake        | 19        | 6.74%   |
| Haswell          | 17        | 6.03%   |
| SandyBridge      | 16        | 5.67%   |
| Zen 3            | 15        | 5.32%   |
| IvyBridge        | 15        | 5.32%   |
| Skylake          | 12        | 4.26%   |
| Alderlake Hybrid | 10        | 3.55%   |
| Zen+             | 9         | 3.19%   |
| Icelake          | 9         | 3.19%   |
| Zen 2            | 8         | 2.84%   |
| Broadwell        | 8         | 2.84%   |
| Penryn           | 7         | 2.48%   |
| Goldmont plus    | 7         | 2.48%   |
| Core             | 7         | 2.48%   |
| Silvermont       | 6         | 2.13%   |
| CometLake        | 6         | 2.13%   |
| Westmere         | 3         | 1.06%   |
| Excavator        | 3         | 1.06%   |
| Tremont          | 2         | 0.71%   |
| Goldmont         | 2         | 0.71%   |
| Bonnell          | 2         | 0.71%   |
| Bobcat           | 2         | 0.71%   |
| Puma             | 1         | 0.35%   |
| K8 Hammer        | 1         | 0.35%   |
| Jaguar           | 1         | 0.35%   |
| Gracemont        | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 211       | 55.24%  |
| Nvidia | 108       | 28.27%  |
| AMD    | 63        | 16.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 18        | 4.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 17        | 4.3%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 15        | 3.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 15        | 3.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 12        | 3.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 11        | 2.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 10        | 2.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 10        | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 9         | 2.28%   |
| Intel HD Graphics 620                                                     | 8         | 2.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 8         | 2.03%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 8         | 2.03%   |
| AMD Rembrandt [Radeon 680M]                                               | 8         | 2.03%   |
| Nvidia GP108BM [GeForce MX250]                                            | 7         | 1.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 7         | 1.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 6         | 1.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 6         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 6         | 1.52%   |
| Intel HD Graphics 5500                                                    | 6         | 1.52%   |
| Nvidia GP108M [GeForce MX150]                                             | 5         | 1.27%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 5         | 1.27%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 5         | 1.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 5         | 1.27%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 4         | 1.01%   |
| Intel Iris Plus Graphics G7                                               | 4         | 1.01%   |
| Intel HD Graphics 530                                                     | 4         | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 4         | 1.01%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 4         | 1.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 0.76%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 3         | 0.76%   |
| Nvidia GM108M [GeForce 940M]                                              | 3         | 0.76%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 3         | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 3         | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 3         | 0.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 0.76%   |
| Intel Raptor Lake-S UHD Graphics                                          | 3         | 0.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 0.76%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                     | 3         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 122       | 43.11%  |
| Intel + Nvidia | 80        | 28.27%  |
| 1 x AMD        | 38        | 13.43%  |
| 1 x Nvidia     | 17        | 6.01%   |
| AMD + Nvidia   | 12        | 4.24%   |
| Intel + AMD    | 8         | 2.83%   |
| 2 x AMD        | 5         | 1.77%   |
| 2 x Intel      | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 216       | 75%     |
| Proprietary | 64        | 22.22%  |
| Unknown     | 8         | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 201       | 68.14%  |
| 1.01-2.0   | 32        | 10.85%  |
| 0.01-0.5   | 24        | 8.14%   |
| 3.01-4.0   | 18        | 6.1%    |
| 0.51-1.0   | 8         | 2.71%   |
| 7.01-8.0   | 5         | 1.69%   |
| 5.01-6.0   | 5         | 1.69%   |
| 2.01-3.0   | 1         | 0.34%   |
| 8.01-16.0  | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 72        | 22.09%  |
| BOE                     | 44        | 13.5%   |
| Samsung Electronics     | 37        | 11.35%  |
| LG Display              | 34        | 10.43%  |
| Chimei Innolux          | 31        | 9.51%   |
| Dell                    | 17        | 5.21%   |
| Apple                   | 13        | 3.99%   |
| Sharp                   | 12        | 3.68%   |
| Philips                 | 8         | 2.45%   |
| CSO                     | 8         | 2.45%   |
| Acer                    | 7         | 2.15%   |
| Lenovo                  | 4         | 1.23%   |
| InfoVision              | 4         | 1.23%   |
| Goldstar                | 4         | 1.23%   |
| PANDA                   | 3         | 0.92%   |
| Hewlett-Packard         | 3         | 0.92%   |
| Valve                   | 2         | 0.61%   |
| TMX                     | 2         | 0.61%   |
| TMA                     | 2         | 0.61%   |
| Mi                      | 2         | 0.61%   |
| LG Philips              | 2         | 0.61%   |
| ViewSonic               | 1         | 0.31%   |
| Toshiba                 | 1         | 0.31%   |
| Tianma XM               | 1         | 0.31%   |
| Sony                    | 1         | 0.31%   |
| JDI                     | 1         | 0.31%   |
| EXP                     | 1         | 0.31%   |
| DMS                     | 1         | 0.31%   |
| DENON                   | 1         | 0.31%   |
| CVT                     | 1         | 0.31%   |
| CPT                     | 1         | 0.31%   |
| Chi Mei Optoelectronics | 1         | 0.31%   |
| BenQ                    | 1         | 0.31%   |
| ASUSTek Computer        | 1         | 0.31%   |
| AOC                     | 1         | 0.31%   |
| Ancor Communications    | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 1.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 4         | 1.22%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.91%   |
| Hewlett-Packard 23er HWP331E 1920x1080 509x286mm 23.0-inch            | 3         | 0.91%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 3         | 0.91%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                     | 3         | 0.91%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch        | 3         | 0.91%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.61%   |
| TMA TL140ADXP24-0 TMA2004 2880x1800 300x190mm 14.0-inch               | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 2         | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.61%   |
| Philips 227E4QH PHLC0AA 1920x1080 477x268mm 21.5-inch                 | 2         | 0.61%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 2         | 0.61%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch      | 2         | 0.61%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.61%   |
| BOE LCD Monitor BOE09B6 2560x1600 345x215mm 16.0-inch                 | 2         | 0.61%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                 | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO3892 1920x1080 344x194mm 15.5-inch        | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO343C 1366x768 309x173mm 13.9-inch         | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch        | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO2B99 1920x1080 293x165mm 13.2-inch        | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch         | 2         | 0.61%   |
| Apple Color LCD APPA02F 2880x1800 331x207mm 15.4-inch                 | 2         | 0.61%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 2         | 0.61%   |
| ViewSonic VX2478-2 VSC2F34 2560x1440 527x296mm 23.8-inch              | 1         | 0.3%    |
| Toshiba LCD TV LCD0030 1920x1080 708x398mm 32.0-inch                  | 1         | 0.3%    |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch               | 1         | 0.3%    |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch               | 1         | 0.3%    |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 1         | 0.3%    |
| Sony BW8 MS_9001 2560x1600                                            | 1         | 0.3%    |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 1         | 0.3%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 141       | 46.69%  |
| 1366x768 (WXGA)    | 50        | 16.56%  |
| 3840x2160 (4K)     | 14        | 4.64%   |
| 2560x1600          | 14        | 4.64%   |
| 2560x1440 (QHD)    | 14        | 4.64%   |
| 2880x1800          | 13        | 4.3%    |
| 1280x800 (WXGA)    | 12        | 3.97%   |
| 1920x1200 (WUXGA)  | 11        | 3.64%   |
| 3840x2400          | 4         | 1.32%   |
| 3440x1440          | 4         | 1.32%   |
| 3072x1920          | 3         | 0.99%   |
| 3000x2000          | 3         | 0.99%   |
| 1440x900 (WXGA+)   | 3         | 0.99%   |
| 800x1280           | 2         | 0.66%   |
| 3200x1800 (QHD+)   | 2         | 0.66%   |
| 2240x1400          | 2         | 0.66%   |
| 1600x900 (HD+)     | 2         | 0.66%   |
| 1360x768           | 2         | 0.66%   |
| 2520x1680          | 1         | 0.33%   |
| 2048x1280          | 1         | 0.33%   |
| 1920x515           | 1         | 0.33%   |
| 1680x1050 (WSXGA+) | 1         | 0.33%   |
| 1280x1024 (SXGA)   | 1         | 0.33%   |
| 1024x600           | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 83        | 25.54%  |
| 13      | 71        | 21.85%  |
| 14      | 59        | 18.15%  |
| 16      | 16        | 4.92%   |
| 27      | 14        | 4.31%   |
| 23      | 13        | 4%      |
| 12      | 13        | 4%      |
| 24      | 11        | 3.38%   |
| 11      | 10        | 3.08%   |
| 21      | 8         | 2.46%   |
| 34      | 3         | 0.92%   |
| 19      | 3         | 0.92%   |
| 18      | 3         | 0.92%   |
| 17      | 3         | 0.92%   |
| 32      | 2         | 0.62%   |
| 31      | 2         | 0.62%   |
| 7       | 2         | 0.62%   |
| Unknown | 2         | 0.62%   |
| 65      | 1         | 0.31%   |
| 54      | 1         | 0.31%   |
| 52      | 1         | 0.31%   |
| 40      | 1         | 0.31%   |
| 35      | 1         | 0.31%   |
| 10      | 1         | 0.31%   |
| 8       | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 182       | 56.52%  |
| 201-300     | 66        | 20.5%   |
| 501-600     | 36        | 11.18%  |
| 401-500     | 12        | 3.73%   |
| 351-400     | 9         | 2.8%    |
| 701-800     | 5         | 1.55%   |
| 1001-1500   | 3         | 0.93%   |
| 801-900     | 2         | 0.62%   |
| 601-700     | 2         | 0.62%   |
| 1-100       | 2         | 0.62%   |
| Unknown     | 2         | 0.62%   |
| 101-200     | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 210       | 73.68%  |
| 16/10 | 60        | 21.05%  |
| 3/2   | 6         | 2.11%   |
| 21/9  | 4         | 1.4%    |
| 0.67  | 2         | 0.7%    |
| 5/4   | 1         | 0.35%   |
| 3.73  | 1         | 0.35%   |
| 0.62  | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 98        | 30.53%  |
| 101-110        | 82        | 25.55%  |
| 71-80          | 28        | 8.72%   |
| 201-250        | 27        | 8.41%   |
| 111-120        | 16        | 4.98%   |
| 301-350        | 14        | 4.36%   |
| 61-70          | 13        | 4.05%   |
| 51-60          | 10        | 3.12%   |
| 351-500        | 8         | 2.49%   |
| 151-200        | 4         | 1.25%   |
| 91-100         | 4         | 1.25%   |
| More than 1000 | 3         | 0.93%   |
| 1-40           | 3         | 0.93%   |
| 141-150        | 3         | 0.93%   |
| 121-130        | 2         | 0.62%   |
| Unknown        | 2         | 0.62%   |
| 41-50          | 1         | 0.31%   |
| 251-300        | 1         | 0.31%   |
| 131-140        | 1         | 0.31%   |
| 501-1000       | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 130       | 41.4%   |
| 161-240       | 56        | 17.83%  |
| 101-120       | 53        | 16.88%  |
| 51-100        | 42        | 13.38%  |
| More than 240 | 27        | 8.6%    |
| 1-50          | 4         | 1.27%   |
| Unknown       | 2         | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 228       | 77.82%  |
| 2     | 53        | 18.09%  |
| 0     | 9         | 3.07%   |
| 3     | 3         | 1.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 169       | 41.94%  |
| Realtek Semiconductor                  | 107       | 26.55%  |
| Qualcomm Atheros                       | 49        | 12.16%  |
| Broadcom                               | 24        | 5.96%   |
| MediaTek                               | 15        | 3.72%   |
| ASIX Electronics                       | 10        | 2.48%   |
| Marvell Technology Group               | 4         | 0.99%   |
| Broadcom Limited                       | 4         | 0.99%   |
| Ralink Technology                      | 3         | 0.74%   |
| Qualcomm                               | 3         | 0.74%   |
| Sierra Wireless                        | 2         | 0.5%    |
| Suzhou Motorcomm Electronic Technology | 1         | 0.25%   |
| Samsung Electronics                    | 1         | 0.25%   |
| Ralink                                 | 1         | 0.25%   |
| Nvidia                                 | 1         | 0.25%   |
| MosChip Semiconductor                  | 1         | 0.25%   |
| Linksys                                | 1         | 0.25%   |
| Lenovo                                 | 1         | 0.25%   |
| Hewlett-Packard                        | 1         | 0.25%   |
| Google                                 | 1         | 0.25%   |
| Edimax Technology                      | 1         | 0.25%   |
| Dell                                   | 1         | 0.25%   |
| D-Link                                 | 1         | 0.25%   |
| Apple                                  | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 61        | 12.79%  |
| Intel Wi-Fi 6 AX200                                                    | 20        | 4.19%   |
| Intel Wi-Fi 6 AX201                                                    | 18        | 3.77%   |
| Intel Wireless 7265                                                    | 15        | 3.14%   |
| Intel Wireless 8265 / 8275                                             | 13        | 2.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 12        | 2.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 2.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 2.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 10        | 2.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 9         | 1.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 1.89%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 1.89%   |
| Intel Wireless 7260                                                    | 8         | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 8         | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 8         | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 1.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 6         | 1.26%   |
| Intel Wireless 3165                                                    | 6         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 1.05%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 5         | 1.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 5         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.84%   |
| Intel Wireless 8260                                                    | 4         | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 0.84%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.84%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 4         | 0.84%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 4         | 0.84%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 3         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.63%   |
| Realtek 802.11ac NIC                                                   | 3         | 0.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 3         | 0.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 165       | 58.3%   |
| Qualcomm Atheros      | 44        | 15.55%  |
| Realtek Semiconductor | 28        | 9.89%   |
| Broadcom              | 17        | 6.01%   |
| MediaTek              | 13        | 4.59%   |
| Ralink Technology     | 3         | 1.06%   |
| Qualcomm              | 3         | 1.06%   |
| Broadcom Limited      | 3         | 1.06%   |
| Sierra Wireless       | 2         | 0.71%   |
| Ralink                | 1         | 0.35%   |
| Hewlett-Packard       | 1         | 0.35%   |
| Edimax Technology     | 1         | 0.35%   |
| Dell                  | 1         | 0.35%   |
| D-Link                | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 20        | 7.02%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 6.32%   |
| Intel Wireless 7265                                                     | 15        | 5.26%   |
| Intel Wireless 8265 / 8275                                              | 13        | 4.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 4.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 3.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 3.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 3.16%   |
| Intel Wireless 7260                                                     | 8         | 2.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 2.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 2.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 2.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 2.11%   |
| Intel Wireless 3165                                                     | 6         | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.75%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 5         | 1.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.4%    |
| Intel Wireless 8260                                                     | 4         | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.4%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 4         | 1.4%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 1.4%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.05%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 1.05%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.05%   |
| Sierra Wireless EM7455                                                  | 2         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.7%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 2         | 0.7%    |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 90        | 47.37%  |
| Intel                                  | 52        | 27.37%  |
| Broadcom                               | 12        | 6.32%   |
| Qualcomm Atheros                       | 11        | 5.79%   |
| ASIX Electronics                       | 10        | 5.26%   |
| Marvell Technology Group               | 4         | 2.11%   |
| MediaTek                               | 2         | 1.05%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.53%   |
| Samsung Electronics                    | 1         | 0.53%   |
| Nvidia                                 | 1         | 0.53%   |
| MosChip Semiconductor                  | 1         | 0.53%   |
| Linksys                                | 1         | 0.53%   |
| Lenovo                                 | 1         | 0.53%   |
| Google                                 | 1         | 0.53%   |
| Broadcom Limited                       | 1         | 0.53%   |
| Apple                                  | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 61        | 31.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 5.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 5.21%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 4.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 3.65%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 3.13%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 2.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1.56%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.56%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.56%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.56%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 1.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.04%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 1.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 1.04%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 1.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 1.04%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 1.04%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.04%   |
| Intel Ethernet Connection (14) I219-LM                                 | 2         | 1.04%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 1.04%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 1.04%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 1.04%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.52%   |
| Realtek Realtek Ethernet controller                                    | 1         | 0.52%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.52%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.52%   |
| Nvidia MCP51 Ethernet Controller                                       | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 271       | 59.82%  |
| Ethernet | 182       | 40.18%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 242       | 80.13%  |
| Ethernet | 60        | 19.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 149       | 52.65%  |
| 1     | 128       | 45.23%  |
| 3     | 3         | 1.06%   |
| 0     | 3         | 1.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 259       | 91.52%  |
| Yes  | 24        | 8.48%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 141       | 57.79%  |
| IMC Networks                    | 18        | 7.38%   |
| Qualcomm Atheros Communications | 16        | 6.56%   |
| Foxconn / Hon Hai               | 14        | 5.74%   |
| Lite-On Technology              | 11        | 4.51%   |
| Apple                           | 11        | 4.51%   |
| Broadcom                        | 9         | 3.69%   |
| Realtek Semiconductor           | 8         | 3.28%   |
| MediaTek                        | 3         | 1.23%   |
| USI                             | 2         | 0.82%   |
| Chicony Electronics             | 2         | 0.82%   |
| Cambridge Silicon Radio         | 2         | 0.82%   |
| Toshiba                         | 1         | 0.41%   |
| Realtek                         | 1         | 0.41%   |
| Ralink Technology               | 1         | 0.41%   |
| Foxconn International           | 1         | 0.41%   |
| Dell                            | 1         | 0.41%   |
| Askey Computer                  | 1         | 0.41%   |
| Alps Electric                   | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 42        | 17.21%  |
| Intel AX201 Bluetooth                               | 40        | 16.39%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 9.43%   |
| Intel AX200 Bluetooth                               | 18        | 7.38%   |
| Intel AX211 Bluetooth                               | 10        | 4.1%    |
| Apple Bluetooth Host Controller                     | 8         | 3.28%   |
| Realtek Bluetooth Radio                             | 7         | 2.87%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.87%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 2.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 2.05%   |
| IMC Networks Wireless_Device                        | 5         | 2.05%   |
| IMC Networks Bluetooth Device                       | 5         | 2.05%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.64%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.64%   |
| MediaTek Wireless_Device                            | 3         | 1.23%   |
| Lite-On Atheros Bluetooth                           | 3         | 1.23%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.23%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 1.23%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.23%   |
| USI Bluetooth Device                                | 2         | 0.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.82%   |
| Lite-On Bluetooth Radio                             | 2         | 0.82%   |
| Lite-On Bluetooth Device                            | 2         | 0.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.82%   |
| Intel Bluetooth Device                              | 2         | 0.82%   |
| Intel AX210 Bluetooth                               | 2         | 0.82%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 2         | 0.82%   |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 0.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.82%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.82%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.41%   |
| Realtek Bluetooth Radio                             | 1         | 0.41%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.41%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.41%   |
| Lite-On Wireless_Device                             | 1         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 219       | 62.57%  |
| AMD                   | 59        | 16.86%  |
| Nvidia                | 53        | 15.14%  |
| Plantronics           | 2         | 0.57%   |
| Lenovo                | 2         | 0.57%   |
| Kingston Technology   | 2         | 0.57%   |
| Apple                 | 2         | 0.57%   |
| Tenx Technology       | 1         | 0.29%   |
| Sennheiser electronic | 1         | 0.29%   |
| SAVITECH              | 1         | 0.29%   |
| Razer USA             | 1         | 0.29%   |
| Logitech              | 1         | 0.29%   |
| Jieli Technology      | 1         | 0.29%   |
| JBL                   | 1         | 0.29%   |
| GN Netcom             | 1         | 0.29%   |
| Cooler Master         | 1         | 0.29%   |
| Conexant Systems      | 1         | 0.29%   |
| ASUSTek Computer      | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 48        | 11.35%  |
| Intel Sunrise Point-LP HD Audio                                            | 35        | 8.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 4.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19        | 4.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 3.78%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 16        | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15        | 3.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 3.31%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 2.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 2.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 2.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 1.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 1.89%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 1.89%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 1.89%   |
| Nvidia GA106 High Definition Audio Controller                              | 7         | 1.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 1.65%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.18%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.18%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.18%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.95%   |
| Nvidia TU104 HD Audio Controller                                           | 4         | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.95%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 4         | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.71%   |
| Nvidia GA107 High Definition Audio Controller                              | 3         | 0.71%   |
| Nvidia AD107 High Definition Audio Controller                              | 3         | 0.71%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3         | 0.71%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 0.71%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 0.71%   |
| AMD FCH Azalia Controller                                                  | 3         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 58        | 28.29%  |
| Samsung Electronics | 50        | 24.39%  |
| Micron Technology   | 32        | 15.61%  |
| Kingston            | 14        | 6.83%   |
| Crucial             | 13        | 6.34%   |
| Unknown             | 11        | 5.37%   |
| Ramaxel Technology  | 5         | 2.44%   |
| Unknown (ABCD)      | 3         | 1.46%   |
| Transcend           | 3         | 1.46%   |
| A-DATA Technology   | 3         | 1.46%   |
| Nanya Technology    | 2         | 0.98%   |
| Elpida              | 2         | 0.98%   |
| V-GeN               | 1         | 0.49%   |
| Team                | 1         | 0.49%   |
| Super Talent        | 1         | 0.49%   |
| Patriot             | 1         | 0.49%   |
| Lexar               | 1         | 0.49%   |
| Corsair             | 1         | 0.49%   |
| Carry               | 1         | 0.49%   |
| ASint Technology    | 1         | 0.49%   |
| Unknown             | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 2.33%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 1.86%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                 | 3         | 1.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s    | 3         | 1.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 1.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.4%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 1.4%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 3         | 1.4%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 1.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 1.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 1.4%    |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.93%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 2         | 0.93%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.93%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.93%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 0.93%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 0.93%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 0.93%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.93%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s    | 2         | 0.93%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 2         | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.93%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s            | 2         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 0.93%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 0.93%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.93%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 2         | 0.93%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.93%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s                | 2         | 0.93%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 0.93%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.93%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s              | 2         | 0.93%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.93%   |
| V-GeN RAM D3R4GS16B8R 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 8GB SODIMM DDR3 800MT/s                          | 1         | 0.47%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 1         | 0.47%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 77        | 45.29%  |
| DDR3   | 42        | 24.71%  |
| LPDDR4 | 15        | 8.82%   |
| LPDDR3 | 13        | 7.65%   |
| LPDDR5 | 12        | 7.06%   |
| DDR5   | 9         | 5.29%   |
| SDRAM  | 1         | 0.59%   |
| DDR2   | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 134       | 78.36%  |
| Row Of Chips | 34        | 19.88%  |
| Chip         | 2         | 1.17%   |
| Unknown      | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 82        | 42.93%  |
| 4096  | 47        | 24.61%  |
| 16384 | 36        | 18.85%  |
| 32768 | 12        | 6.28%   |
| 2048  | 10        | 5.24%   |
| 1024  | 3         | 1.57%   |
| 3072  | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 40        | 21.39%  |
| 2667    | 33        | 17.65%  |
| 1600    | 33        | 17.65%  |
| 2133    | 11        | 5.88%   |
| 4267    | 10        | 5.35%   |
| 2400    | 10        | 5.35%   |
| 6400    | 7         | 3.74%   |
| 4800    | 6         | 3.21%   |
| 1334    | 6         | 3.21%   |
| 1333    | 6         | 3.21%   |
| 5600    | 5         | 2.67%   |
| 7500    | 4         | 2.14%   |
| 1867    | 3         | 1.6%    |
| 8400    | 2         | 1.07%   |
| 3266    | 2         | 1.07%   |
| 1067    | 2         | 1.07%   |
| Unknown | 2         | 1.07%   |
| 8533    | 1         | 0.53%   |
| 4199    | 1         | 0.53%   |
| 1200    | 1         | 0.53%   |
| 800     | 1         | 0.53%   |
| 667     | 1         | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Brother DCP-L2535DW series | 1         | 100%    |

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
| Chicony Electronics                    | 59        | 23.89%  |
| IMC Networks                           | 38        | 15.38%  |
| Microdia                               | 32        | 12.96%  |
| Realtek Semiconductor                  | 20        | 8.1%    |
| Sunplus Innovation Technology          | 14        | 5.67%   |
| Bison Electronics                      | 14        | 5.67%   |
| Syntek                                 | 8         | 3.24%   |
| Suyin                                  | 7         | 2.83%   |
| Samsung Electronics                    | 5         | 2.02%   |
| Lite-On Technology                     | 5         | 2.02%   |
| Apple                                  | 5         | 2.02%   |
| Acer                                   | 4         | 1.62%   |
| Shinetech                              | 3         | 1.21%   |
| Quanta                                 | 3         | 1.21%   |
| OmniVision Technologies                | 3         | 1.21%   |
| Luxvisions Innotech Limited            | 3         | 1.21%   |
| Logitech                               | 3         | 1.21%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.21%   |
| SunplusIT                              | 2         | 0.81%   |
| Sonix Technology                       | 2         | 0.81%   |
| Silicon Motion                         | 2         | 0.81%   |
| Ricoh                                  | 2         | 0.81%   |
| Alcor Micro                            | 2         | 0.81%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.4%    |
| OnePlus Technology (Shenzhen)          | 1         | 0.4%    |
| Magic Control Technology               | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| kingcome                               | 1         | 0.4%    |
| Intel                                  | 1         | 0.4%    |
| HYGD-220831-A                          | 1         | 0.4%    |
| Unknown                                | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 20        | 8.03%   |
| Chicony Integrated Camera                        | 13        | 5.22%   |
| IMC Networks Integrated Camera                   | 11        | 4.42%   |
| Chicony HD WebCam                                | 11        | 4.42%   |
| IMC Networks USB2.0 HD UVC WebCam                | 10        | 4.02%   |
| Realtek Integrated_Webcam_HD                     | 8         | 3.21%   |
| Sunplus Integrated_Webcam_HD                     | 7         | 2.81%   |
| Syntek Integrated Camera                         | 6         | 2.41%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 6         | 2.41%   |
| Samsung Galaxy series, misc. (MTP mode)          | 5         | 2.01%   |
| IMC Networks USB2.0 HD IR UVC WebCam             | 5         | 2.01%   |
| Bison Integrated Camera                          | 5         | 2.01%   |
| Lite-On Integrated Camera                        | 4         | 1.61%   |
| Chicony USB2.0 Camera                            | 4         | 1.61%   |
| Chicony HP HD Camera                             | 4         | 1.61%   |
| Apple FaceTime HD Camera                         | 4         | 1.61%   |
| OmniVision OV2640 Webcam                         | 3         | 1.2%    |
| Luxvisions Innotech Limited Integrated Camera    | 3         | 1.2%    |
| Chicony Lenovo Integrated Camera (0.3MP)         | 3         | 1.2%    |
| Chicony HP Wide Vision HD Camera                 | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 3         | 1.2%    |
| Bison HD Webcam                                  | 3         | 1.2%    |
| Acer Integrated Camera                           | 3         | 1.2%    |
| Syntek Lenovo EasyCamera                         | 2         | 0.8%    |
| Shinetech ASUS FHD webcam                        | 2         | 0.8%    |
| Realtek Integrated Webcam_HD                     | 2         | 0.8%    |
| Realtek Asus 2.0 USB Webcam                      | 2         | 0.8%    |
| Microdia USB 2.0 Camera                          | 2         | 0.8%    |
| Microdia Sonix USB 2.0 Camera                    | 2         | 0.8%    |
| Microdia Integrated_Webcam_FHD                   | 2         | 0.8%    |
| Microdia Integrated Webcam                       | 2         | 0.8%    |
| Microdia Integrated Camera                       | 2         | 0.8%    |
| IMC Networks Lenovo EasyCamera                   | 2         | 0.8%    |
| Chicony VGA Webcam                               | 2         | 0.8%    |
| Chicony USB2.0 VGA UVC WebCam                    | 2         | 0.8%    |
| Chicony USB2.0 HD UVC WebCam                     | 2         | 0.8%    |
| Chicony Integrated Camera [ThinkPad]             | 2         | 0.8%    |
| Chicony HD User Facing                           | 2         | 0.8%    |
| Bison Lenovo EasyCamera                          | 2         | 0.8%    |
| Bison BisonCam, NB Pro                           | 2         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 17        | 25.37%  |
| Validity Sensors                   | 13        | 19.4%   |
| Shenzhen Goodix Technology         | 9         | 13.43%  |
| LighTuning Technology              | 8         | 11.94%  |
| Upek                               | 6         | 8.96%   |
| Elan Microelectronics              | 6         | 8.96%   |
| AuthenTec                          | 6         | 8.96%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.49%   |
| Focal-systems.Corp                 | 1         | 1.49%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 13.43%  |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 11.94%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 8.96%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 5.97%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 5.97%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 5.97%   |
| Elan ELAN:Fingerprint                                                      | 4         | 5.97%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.48%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 4.48%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.99%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.99%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.99%   |
| AuthenTec AES2810                                                          | 2         | 2.99%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.99%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.49%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.49%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.49%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.49%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.49%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.49%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.49%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 1.49%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.49%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.49%   |
| Unknown                                                                    | 1         | 1.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 80%     |
| Alcor Micro | 2         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 4         | 40%     |
| Broadcom BCM5880 Secure Applications Processor | 3         | 30%     |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 20%     |
| Broadcom 5880                                  | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 167       | 56.23%  |
| 1     | 97        | 32.66%  |
| 2     | 28        | 9.43%   |
| 3     | 3         | 1.01%   |
| 5     | 1         | 0.34%   |
| 4     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 62        | 37.58%  |
| Graphics card            | 42        | 25.45%  |
| Net/wireless             | 16        | 9.7%    |
| Multimedia controller    | 12        | 7.27%   |
| Chipcard                 | 9         | 5.45%   |
| Camera                   | 8         | 4.85%   |
| Communication controller | 6         | 3.64%   |
| Net/ethernet             | 4         | 2.42%   |
| Bluetooth                | 2         | 1.21%   |
| Wireless                 | 1         | 0.61%   |
| Storage/raid             | 1         | 0.61%   |
| Sound                    | 1         | 0.61%   |
| Firewire controller      | 1         | 0.61%   |

