Linux in Lithuania - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Lithuania.

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

Total: 314

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | L140CU                      | [e24f4b285d](https://linux-hardware.org/?probe=e24f4b285d) | Mar 29, 2023 |
| Notebook      | L140CU                      | [b1b0a5fc03](https://linux-hardware.org/?probe=b1b0a5fc03) | Mar 29, 2023 |
| ASUSTek       | T100HAN                     | [c1f3b9658c](https://linux-hardware.org/?probe=c1f3b9658c) | Mar 26, 2023 |
| ASUSTek       | T100HAN                     | [3f74c992e7](https://linux-hardware.org/?probe=3f74c992e7) | Mar 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [644c9b9e55](https://linux-hardware.org/?probe=644c9b9e55) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [06bd07f367](https://linux-hardware.org/?probe=06bd07f367) | Mar 21, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [ba879b76da](https://linux-hardware.org/?probe=ba879b76da) | Mar 19, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [547559d982](https://linux-hardware.org/?probe=547559d982) | Mar 19, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| ASUSTek       | N550JK                      | [6b93d4a171](https://linux-hardware.org/?probe=6b93d4a171) | Mar 17, 2023 |
| MSI           | GT72 2PE                    | [0483315836](https://linux-hardware.org/?probe=0483315836) | Mar 16, 2023 |
| ASUSTek       | N61Jq                       | [706eca5e8a](https://linux-hardware.org/?probe=706eca5e8a) | Mar 15, 2023 |
| ASUSTek       | T100HAN                     | [b4046bce15](https://linux-hardware.org/?probe=b4046bce15) | Mar 10, 2023 |
| HP            | Compaq Presario CQ60        | [cbdc8bcd6a](https://linux-hardware.org/?probe=cbdc8bcd6a) | Mar 06, 2023 |
| MSI           | GS66 Stealth 10UE           | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| MSI           | GS66 Stealth 10UE           | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| HP            | EliteBook 2540p             | [bf037f7503](https://linux-hardware.org/?probe=bf037f7503) | Feb 21, 2023 |
| Apple         | MacBookPro11,5              | [7933746ce1](https://linux-hardware.org/?probe=7933746ce1) | Feb 17, 2023 |
| MSI           | GS66 Stealth 10UE           | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [8ba717ec45](https://linux-hardware.org/?probe=8ba717ec45) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| HP            | EliteBook 2540p             | [f03240c746](https://linux-hardware.org/?probe=f03240c746) | Jan 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [a3a0a3a505](https://linux-hardware.org/?probe=a3a0a3a505) | Jan 25, 2023 |
| ASUSTek       | GL552VX                     | [d196ac82e2](https://linux-hardware.org/?probe=d196ac82e2) | Jan 23, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [bd51c2a953](https://linux-hardware.org/?probe=bd51c2a953) | Jan 20, 2023 |
| MSI           | GP70 2PE                    | [697974aa68](https://linux-hardware.org/?probe=697974aa68) | Jan 08, 2023 |
| HP            | ProBook 450 G0              | [e7af660f1a](https://linux-hardware.org/?probe=e7af660f1a) | Jan 05, 2023 |
| HP            | 250 G7 Notebook PC          | [ec6b0e70a2](https://linux-hardware.org/?probe=ec6b0e70a2) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [658e730bd3](https://linux-hardware.org/?probe=658e730bd3) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [7a6ba7238f](https://linux-hardware.org/?probe=7a6ba7238f) | Dec 08, 2022 |
| Dell          | Vostro 5502                 | [862097a47c](https://linux-hardware.org/?probe=862097a47c) | Dec 05, 2022 |
| ASUSTek       | X550CL                      | [06c7fdf5c9](https://linux-hardware.org/?probe=06c7fdf5c9) | Nov 26, 2022 |
| HP            | EliteBook 8470p             | [b7ff70b9b2](https://linux-hardware.org/?probe=b7ff70b9b2) | Nov 14, 2022 |
| HP            | EliteBook 8470p             | [f6bfbc00ba](https://linux-hardware.org/?probe=f6bfbc00ba) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| HP            | EliteBook 8470p             | [bdca860f08](https://linux-hardware.org/?probe=bdca860f08) | Nov 06, 2022 |
| MSI           | Bravo 15 A4DDR              | [8598cf3c36](https://linux-hardware.org/?probe=8598cf3c36) | Nov 04, 2022 |
| Acer          | Aspire 5750G                | [496a16216c](https://linux-hardware.org/?probe=496a16216c) | Nov 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [b374c2dff6](https://linux-hardware.org/?probe=b374c2dff6) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| Dell          | G3 3579                     | [2191706dd0](https://linux-hardware.org/?probe=2191706dd0) | Oct 11, 2022 |
| Dell          | G3 3579                     | [7f20851840](https://linux-hardware.org/?probe=7f20851840) | Oct 10, 2022 |
| HP            | EliteBook 850 G3            | [7bbcf621e1](https://linux-hardware.org/?probe=7bbcf621e1) | Sep 20, 2022 |
| ASUSTek       | X540LA                      | [3ba0635033](https://linux-hardware.org/?probe=3ba0635033) | Sep 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d8505e212b](https://linux-hardware.org/?probe=d8505e212b) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8e366d7e21](https://linux-hardware.org/?probe=8e366d7e21) | Sep 02, 2022 |
| HP            | ProBook 440 G3              | [e51d4ae241](https://linux-hardware.org/?probe=e51d4ae241) | Aug 20, 2022 |
| Lenovo        | ThinkPad T590 20N4004EMH    | [42d130e184](https://linux-hardware.org/?probe=42d130e184) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5967f639c3](https://linux-hardware.org/?probe=5967f639c3) | Aug 16, 2022 |
| MSI           | MS-16F1                     | [0a28da4f53](https://linux-hardware.org/?probe=0a28da4f53) | Aug 12, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [f3a7c88015](https://linux-hardware.org/?probe=f3a7c88015) | Aug 11, 2022 |
| Lenovo        | ThinkPad T430s 2356LNG      | [255560d675](https://linux-hardware.org/?probe=255560d675) | Aug 06, 2022 |
| HP            | Compaq Presario CQ60        | [06fe56588b](https://linux-hardware.org/?probe=06fe56588b) | Jul 27, 2022 |
| eMachines     | eME443                      | [9197e8ef17](https://linux-hardware.org/?probe=9197e8ef17) | Jul 11, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [f23b75e3ca](https://linux-hardware.org/?probe=f23b75e3ca) | Jun 19, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [8f2740e70e](https://linux-hardware.org/?probe=8f2740e70e) | Jun 18, 2022 |
| Panasonic     | CF-52VDA131M                | [aa40370193](https://linux-hardware.org/?probe=aa40370193) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| Dell          | Latitude E5570              | [310aadd79a](https://linux-hardware.org/?probe=310aadd79a) | May 24, 2022 |
| Alienware     | 17                          | [b30786ba0e](https://linux-hardware.org/?probe=b30786ba0e) | May 10, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [3e171a4858](https://linux-hardware.org/?probe=3e171a4858) | May 09, 2022 |
| Lenovo        | G500 20236                  | [8439c948ec](https://linux-hardware.org/?probe=8439c948ec) | May 06, 2022 |
| Dell          | Inspiron 7720               | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| Dell          | XPS 15 9510                 | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [96fc510369](https://linux-hardware.org/?probe=96fc510369) | Apr 29, 2022 |
| Dell          | Latitude 5401               | [d115db916d](https://linux-hardware.org/?probe=d115db916d) | Apr 23, 2022 |
| Dell          | Latitude 5401               | [c9f380ea26](https://linux-hardware.org/?probe=c9f380ea26) | Apr 23, 2022 |
| ASUSTek       | X55A                        | [9188b40f88](https://linux-hardware.org/?probe=9188b40f88) | Apr 23, 2022 |
| Dell          | Vostro 3580                 | [0ec442c0be](https://linux-hardware.org/?probe=0ec442c0be) | Mar 28, 2022 |
| ASUSTek       | X55A                        | [9b02d587bf](https://linux-hardware.org/?probe=9b02d587bf) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [c3ffdf7791](https://linux-hardware.org/?probe=c3ffdf7791) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [77b0be92c8](https://linux-hardware.org/?probe=77b0be92c8) | Mar 17, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5d0113f42d](https://linux-hardware.org/?probe=5d0113f42d) | Mar 16, 2022 |
| HP            | ProBook 455 G1              | [c6ad6edf70](https://linux-hardware.org/?probe=c6ad6edf70) | Mar 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4b0c952d9b](https://linux-hardware.org/?probe=4b0c952d9b) | Mar 09, 2022 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [12a1b54a3a](https://linux-hardware.org/?probe=12a1b54a3a) | Feb 16, 2022 |
| ASUSTek       | X55A                        | [dbbb7b1213](https://linux-hardware.org/?probe=dbbb7b1213) | Feb 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [a7d1f29451](https://linux-hardware.org/?probe=a7d1f29451) | Jan 31, 2022 |
| Jumper        | EZbook                      | [4fa449c0ce](https://linux-hardware.org/?probe=4fa449c0ce) | Jan 27, 2022 |
| HP            | ProBook 450 G1              | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Lenovo        | Flex 2-15 20405             | [8f6a587ed3](https://linux-hardware.org/?probe=8f6a587ed3) | Jan 20, 2022 |
| ASUSTek       | N53SV                       | [a5b43fd8b4](https://linux-hardware.org/?probe=a5b43fd8b4) | Jan 05, 2022 |
| HP            | Laptop 14s-fq1xxx           | [8e0b4fec6c](https://linux-hardware.org/?probe=8e0b4fec6c) | Dec 26, 2021 |
| Acer          | Aspire A515-56              | [113924cdba](https://linux-hardware.org/?probe=113924cdba) | Dec 12, 2021 |
| ASUSTek       | N53SV                       | [557bb216fc](https://linux-hardware.org/?probe=557bb216fc) | Nov 20, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad L440 20ASA10P00    | [3119a05196](https://linux-hardware.org/?probe=3119a05196) | Nov 15, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [b455b4457c](https://linux-hardware.org/?probe=b455b4457c) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| ASUSTek       | X55A                        | [a55961748f](https://linux-hardware.org/?probe=a55961748f) | Nov 10, 2021 |
| ASUSTek       | X55A                        | [8c59513ced](https://linux-hardware.org/?probe=8c59513ced) | Nov 10, 2021 |
| ASUSTek       | K52F                        | [f90cbb4d26](https://linux-hardware.org/?probe=f90cbb4d26) | Nov 04, 2021 |
| ASUSTek       | N73SV                       | [997a879973](https://linux-hardware.org/?probe=997a879973) | Oct 29, 2021 |
| HUAWEI        | MACHD-WXX9                  | [1876547e8e](https://linux-hardware.org/?probe=1876547e8e) | Oct 25, 2021 |
| HUAWEI        | MACHD-WXX9                  | [078863a9b7](https://linux-hardware.org/?probe=078863a9b7) | Oct 25, 2021 |
| Toshiba       | Satellite C50D-A-13G        | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| Dell          | Inspiron 15-3567            | [5db12e2534](https://linux-hardware.org/?probe=5db12e2534) | Oct 02, 2021 |
| Alienware     | 17                          | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Dell          | XPS 15 9500                 | [239dced9a1](https://linux-hardware.org/?probe=239dced9a1) | Sep 19, 2021 |
| HUAWEI        | MACHD-WXX9                  | [4db5d51b06](https://linux-hardware.org/?probe=4db5d51b06) | Sep 17, 2021 |
| HP            | 250 G4                      | [6c66581e62](https://linux-hardware.org/?probe=6c66581e62) | Sep 06, 2021 |
| HP            | 250 G4                      | [619fff9116](https://linux-hardware.org/?probe=619fff9116) | Sep 04, 2021 |
| ASUSTek       | X551CAP                     | [626023b280](https://linux-hardware.org/?probe=626023b280) | Aug 24, 2021 |
| ASUSTek       | X551CAP                     | [9e64453373](https://linux-hardware.org/?probe=9e64453373) | Aug 23, 2021 |
| Acer          | Aspire 5750G                | [c358dfd2e6](https://linux-hardware.org/?probe=c358dfd2e6) | Aug 18, 2021 |
| HP            | Pavilion dv7                | [640a5fb2b3](https://linux-hardware.org/?probe=640a5fb2b3) | Aug 13, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5d33b12497](https://linux-hardware.org/?probe=5d33b12497) | Aug 13, 2021 |
| HP            | EliteBook 8440p             | [80cb2748cf](https://linux-hardware.org/?probe=80cb2748cf) | Aug 02, 2021 |
| HP            | 250 G4                      | [bd80a8cdf0](https://linux-hardware.org/?probe=bd80a8cdf0) | Aug 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [4752d9cb90](https://linux-hardware.org/?probe=4752d9cb90) | Aug 01, 2021 |
| Alienware     | 17                          | [9d281e3351](https://linux-hardware.org/?probe=9d281e3351) | Jun 16, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [45b678cc45](https://linux-hardware.org/?probe=45b678cc45) | Jun 07, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [dab115ff9f](https://linux-hardware.org/?probe=dab115ff9f) | Jun 07, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [63b5d9a81a](https://linux-hardware.org/?probe=63b5d9a81a) | Jun 05, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [56308999d2](https://linux-hardware.org/?probe=56308999d2) | Jun 05, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [20b885e70c](https://linux-hardware.org/?probe=20b885e70c) | Jun 01, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [74979cf76a](https://linux-hardware.org/?probe=74979cf76a) | Jun 01, 2021 |
| ASUSTek       | K52F                        | [92db46133f](https://linux-hardware.org/?probe=92db46133f) | May 24, 2021 |
| Dell          | Precision M4700             | [1d14e22fbd](https://linux-hardware.org/?probe=1d14e22fbd) | May 22, 2021 |
| Dell          | Inspiron 5579               | [83c30b9084](https://linux-hardware.org/?probe=83c30b9084) | May 15, 2021 |
| ASUSTek       | UX430UAR                    | [84b8a6331d](https://linux-hardware.org/?probe=84b8a6331d) | May 08, 2021 |
| Unknown       | Unknown                     | [50d2466e84](https://linux-hardware.org/?probe=50d2466e84) | May 06, 2021 |
| Unknown       | Unknown                     | [410d40ca5f](https://linux-hardware.org/?probe=410d40ca5f) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [49aad4b320](https://linux-hardware.org/?probe=49aad4b320) | May 04, 2021 |
| Lenovo        | ThinkPad P53 20QN0034MH     | [bcb2272cf0](https://linux-hardware.org/?probe=bcb2272cf0) | Apr 25, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [26133ce35a](https://linux-hardware.org/?probe=26133ce35a) | Apr 24, 2021 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [1e30c2850c](https://linux-hardware.org/?probe=1e30c2850c) | Apr 09, 2021 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [faca4e4038](https://linux-hardware.org/?probe=faca4e4038) | Apr 08, 2021 |
| Acer          | Aspire A515-56              | [1bdc8a756f](https://linux-hardware.org/?probe=1bdc8a756f) | Mar 17, 2021 |
| ASUSTek       | K50C                        | [4ccd0463c4](https://linux-hardware.org/?probe=4ccd0463c4) | Mar 17, 2021 |
| Lenovo        | ThinkPad T480 20L50002MH    | [554173e0d7](https://linux-hardware.org/?probe=554173e0d7) | Mar 17, 2021 |
| ASUSTek       | K50C                        | [65941d7354](https://linux-hardware.org/?probe=65941d7354) | Mar 17, 2021 |
| Dell          | Latitude E5530 non-vPro     | [530ac66726](https://linux-hardware.org/?probe=530ac66726) | Mar 17, 2021 |
| Dell          | Latitude 7380               | [43510cebc1](https://linux-hardware.org/?probe=43510cebc1) | Mar 13, 2021 |
| Lenovo        | ThinkPad W530 243852U       | [15c953bc70](https://linux-hardware.org/?probe=15c953bc70) | Mar 09, 2021 |
| Dell          | Inspiron 5758               | [f371afba83](https://linux-hardware.org/?probe=f371afba83) | Feb 27, 2021 |
| Dell          | Inspiron 5570               | [d36796da44](https://linux-hardware.org/?probe=d36796da44) | Feb 27, 2021 |
| Lenovo        | ThinkPad T430 2347EV8       | [3bf5967320](https://linux-hardware.org/?probe=3bf5967320) | Feb 19, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a398ccbc3d](https://linux-hardware.org/?probe=a398ccbc3d) | Jan 31, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XN0... | [f25ec6b2f3](https://linux-hardware.org/?probe=f25ec6b2f3) | Jan 31, 2021 |
| Acer          | Extensa 5220                | [20ea0cd55c](https://linux-hardware.org/?probe=20ea0cd55c) | Jan 23, 2021 |
| Acer          | Extensa 5220                | [9fe95abf63](https://linux-hardware.org/?probe=9fe95abf63) | Jan 23, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [b7b3175352](https://linux-hardware.org/?probe=b7b3175352) | Jan 14, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [ed7d9bff15](https://linux-hardware.org/?probe=ed7d9bff15) | Jan 13, 2021 |
| Acer          | Aspire 5750G                | [91885a7829](https://linux-hardware.org/?probe=91885a7829) | Jan 05, 2021 |
| Acer          | Aspire 5750G                | [34198a369d](https://linux-hardware.org/?probe=34198a369d) | Dec 26, 2020 |
| HP            | EliteBook 855 G7 Noteboo... | [f4ab3e4295](https://linux-hardware.org/?probe=f4ab3e4295) | Dec 26, 2020 |
| Acer          | Aspire 1410                 | [3ff80e7b33](https://linux-hardware.org/?probe=3ff80e7b33) | Dec 26, 2020 |
| ASUSTek       | X510UNR                     | [44990d7fc0](https://linux-hardware.org/?probe=44990d7fc0) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | [e6e91c5ea2](https://linux-hardware.org/?probe=e6e91c5ea2) | Dec 16, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [5b56323f14](https://linux-hardware.org/?probe=5b56323f14) | Dec 15, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [2c7c774492](https://linux-hardware.org/?probe=2c7c774492) | Dec 15, 2020 |
| Toshiba       | Satellite L855              | [48d0f1a04c](https://linux-hardware.org/?probe=48d0f1a04c) | Dec 08, 2020 |
| Dell          | Latitude E7470              | [3c76403f27](https://linux-hardware.org/?probe=3c76403f27) | Dec 01, 2020 |
| Packard Be... | EasyNote TE11HC             | [a58e43a971](https://linux-hardware.org/?probe=a58e43a971) | Nov 20, 2020 |
| Packard Be... | EasyNote TE11HC             | [374504e0bd](https://linux-hardware.org/?probe=374504e0bd) | Nov 20, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [1310e54c33](https://linux-hardware.org/?probe=1310e54c33) | Nov 20, 2020 |
| ASUSTek       | X510UNR                     | [fb41abdfb1](https://linux-hardware.org/?probe=fb41abdfb1) | Nov 13, 2020 |
| Alienware     | 17                          | [59fdbdd4d7](https://linux-hardware.org/?probe=59fdbdd4d7) | Nov 11, 2020 |
| ASUSTek       | GL553VD                     | [86837daf1c](https://linux-hardware.org/?probe=86837daf1c) | Nov 10, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cf2cbcbe72](https://linux-hardware.org/?probe=cf2cbcbe72) | Nov 05, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [39dcf2485b](https://linux-hardware.org/?probe=39dcf2485b) | Nov 03, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | [f507c9b3e5](https://linux-hardware.org/?probe=f507c9b3e5) | Oct 25, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1b2dd49d08](https://linux-hardware.org/?probe=1b2dd49d08) | Oct 20, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [b3e5017b13](https://linux-hardware.org/?probe=b3e5017b13) | Oct 20, 2020 |
| Dell          | Inspiron 7577               | [09fbf70f49](https://linux-hardware.org/?probe=09fbf70f49) | Oct 16, 2020 |
| HP            | ProBook 450 G1              | [c69e6488fd](https://linux-hardware.org/?probe=c69e6488fd) | Oct 14, 2020 |
| Dell          | G5 5587                     | [ba6fbeb10c](https://linux-hardware.org/?probe=ba6fbeb10c) | Oct 09, 2020 |
| Dell          | G5 5587                     | [8b28232f32](https://linux-hardware.org/?probe=8b28232f32) | Oct 09, 2020 |
| HP            | ProBook 4720s               | [a882fdd653](https://linux-hardware.org/?probe=a882fdd653) | Oct 02, 2020 |
| ASUSTek       | N56VZ                       | [d4d74a6e34](https://linux-hardware.org/?probe=d4d74a6e34) | Sep 29, 2020 |
| ASUSTek       | K52JT                       | [2acb54cb0d](https://linux-hardware.org/?probe=2acb54cb0d) | Sep 28, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [87092c4768](https://linux-hardware.org/?probe=87092c4768) | Sep 21, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [48825acdce](https://linux-hardware.org/?probe=48825acdce) | Sep 18, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [aef0cb23ec](https://linux-hardware.org/?probe=aef0cb23ec) | Sep 16, 2020 |
| HP            | ProBook 450 G6              | [6fffc9928f](https://linux-hardware.org/?probe=6fffc9928f) | Sep 10, 2020 |
| HP            | ProBook 450 G6              | [7465caa486](https://linux-hardware.org/?probe=7465caa486) | Sep 10, 2020 |
| Lenovo        | ThinkPad T460s 20F90058M... | [352f3932b4](https://linux-hardware.org/?probe=352f3932b4) | Sep 09, 2020 |
| Dell          | Latitude 5491               | [06d4120fc1](https://linux-hardware.org/?probe=06d4120fc1) | Sep 08, 2020 |
| Lenovo        | ThinkPad L440 20ASS10F00    | [cb6b544787](https://linux-hardware.org/?probe=cb6b544787) | Sep 04, 2020 |
| Timi          | TM1701                      | [4c01fca357](https://linux-hardware.org/?probe=4c01fca357) | Aug 25, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [d053bf3f76](https://linux-hardware.org/?probe=d053bf3f76) | Aug 18, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [2551496802](https://linux-hardware.org/?probe=2551496802) | Aug 18, 2020 |
| Dell          | XPS M1330                   | [4a907eebb9](https://linux-hardware.org/?probe=4a907eebb9) | Aug 02, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [a52cd7499e](https://linux-hardware.org/?probe=a52cd7499e) | Jul 28, 2020 |
| Acer          | Swift SF314-54G             | [a4948f0d33](https://linux-hardware.org/?probe=a4948f0d33) | Jul 24, 2020 |
| Acer          | Swift SF314-54G             | [cd250d0e7b](https://linux-hardware.org/?probe=cd250d0e7b) | Jul 24, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | [810f713a78](https://linux-hardware.org/?probe=810f713a78) | Jul 24, 2020 |
| HP            | Pavilion dv6                | [4c09684767](https://linux-hardware.org/?probe=4c09684767) | Jul 23, 2020 |
| ASUSTek       | N71Ja                       | [db78759a1a](https://linux-hardware.org/?probe=db78759a1a) | Jul 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [0fb6ac937d](https://linux-hardware.org/?probe=0fb6ac937d) | Jul 06, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [fc16d36603](https://linux-hardware.org/?probe=fc16d36603) | Jul 03, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [9c1c6b6919](https://linux-hardware.org/?probe=9c1c6b6919) | Jun 30, 2020 |
| Dell          | XPS 15 7590                 | [78351d2937](https://linux-hardware.org/?probe=78351d2937) | Jun 22, 2020 |
| Lenovo        | ThinkPad L460 20FU0007MH    | [27a87ca264](https://linux-hardware.org/?probe=27a87ca264) | Jun 18, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [9c0419884f](https://linux-hardware.org/?probe=9c0419884f) | Jun 17, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | [ed27c7aa81](https://linux-hardware.org/?probe=ed27c7aa81) | Jun 10, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | [574368a188](https://linux-hardware.org/?probe=574368a188) | Jun 09, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [ebac9eaefe](https://linux-hardware.org/?probe=ebac9eaefe) | Jun 02, 2020 |
| HP            | EliteBook 8440p             | [cc3e01ff0f](https://linux-hardware.org/?probe=cc3e01ff0f) | May 29, 2020 |
| Lenovo        | Y50-70 20378                | [85443edb8d](https://linux-hardware.org/?probe=85443edb8d) | May 22, 2020 |
| Dell          | Inspiron 1520               | [368e9f53e5](https://linux-hardware.org/?probe=368e9f53e5) | May 22, 2020 |
| Samsung       | RC530/RC730                 | [7e180f5fd2](https://linux-hardware.org/?probe=7e180f5fd2) | May 21, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [04ed3686b1](https://linux-hardware.org/?probe=04ed3686b1) | May 19, 2020 |
| ASUSTek       | X51RL                       | [afee28a69b](https://linux-hardware.org/?probe=afee28a69b) | May 16, 2020 |
| HP            | EliteBook 8440p             | [5856d8fd4a](https://linux-hardware.org/?probe=5856d8fd4a) | Apr 30, 2020 |
| Lenovo        | ThinkPad Edge E320 12985... | [e4a1ece1ec](https://linux-hardware.org/?probe=e4a1ece1ec) | Apr 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [70daf3ad77](https://linux-hardware.org/?probe=70daf3ad77) | Apr 20, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [c4b061e0f5](https://linux-hardware.org/?probe=c4b061e0f5) | Apr 19, 2020 |
| Lenovo        | V130-15IGM 81HL             | [11251407bd](https://linux-hardware.org/?probe=11251407bd) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | [37f223475f](https://linux-hardware.org/?probe=37f223475f) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | [21a5c2580f](https://linux-hardware.org/?probe=21a5c2580f) | Apr 10, 2020 |
| ASUSTek       | M50SA                       | [a7381b478e](https://linux-hardware.org/?probe=a7381b478e) | Apr 10, 2020 |
| Dell          | Inspiron 3542               | [38086a42be](https://linux-hardware.org/?probe=38086a42be) | Apr 01, 2020 |
| Dell          | Inspiron 3542               | [2246b94acb](https://linux-hardware.org/?probe=2246b94acb) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | [0552ab024f](https://linux-hardware.org/?probe=0552ab024f) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | [0fd03337ad](https://linux-hardware.org/?probe=0fd03337ad) | Mar 29, 2020 |
| Acer          | Aspire 5733                 | [055f9887c3](https://linux-hardware.org/?probe=055f9887c3) | Mar 29, 2020 |
| Lenovo        | G550 20023                  | [0e9b1fb324](https://linux-hardware.org/?probe=0e9b1fb324) | Mar 29, 2020 |
| HP            | 630                         | [fc76abe01b](https://linux-hardware.org/?probe=fc76abe01b) | Mar 29, 2020 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [23a0bdb230](https://linux-hardware.org/?probe=23a0bdb230) | Mar 19, 2020 |
| ASUSTek       | K43E                        | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |
| ASUSTek       | K53E                        | [8729f56cdc](https://linux-hardware.org/?probe=8729f56cdc) | Mar 07, 2020 |
| ASUSTek       | K53SV                       | [3b537b4a10](https://linux-hardware.org/?probe=3b537b4a10) | Mar 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f08088a64d](https://linux-hardware.org/?probe=f08088a64d) | Feb 20, 2020 |
| HP            | ProBook 4740s               | [4d4d26ef02](https://linux-hardware.org/?probe=4d4d26ef02) | Feb 03, 2020 |
| Lenovo        | ThinkPad E590 20NB0065MH    | [e895371f73](https://linux-hardware.org/?probe=e895371f73) | Feb 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [226b976601](https://linux-hardware.org/?probe=226b976601) | Jan 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6973864306](https://linux-hardware.org/?probe=6973864306) | Jan 25, 2020 |
| Acer          | Aspire V3-772               | [17005306cd](https://linux-hardware.org/?probe=17005306cd) | Jan 24, 2020 |
| ASUSTek       | K52JT                       | [4335a97dd6](https://linux-hardware.org/?probe=4335a97dd6) | Jan 24, 2020 |
| Dell          | G3 3579                     | [56f84db06b](https://linux-hardware.org/?probe=56f84db06b) | Jan 22, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | [f22d44d39f](https://linux-hardware.org/?probe=f22d44d39f) | Jan 22, 2020 |
| Panasonic     | CF-52WEBBYDE                | [0d21ee7063](https://linux-hardware.org/?probe=0d21ee7063) | Jan 17, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [cf8ada0ad0](https://linux-hardware.org/?probe=cf8ada0ad0) | Jan 16, 2020 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | [f57bc0120b](https://linux-hardware.org/?probe=f57bc0120b) | Jan 15, 2020 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | [4ea8d503ae](https://linux-hardware.org/?probe=4ea8d503ae) | Dec 13, 2019 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | [a298251c28](https://linux-hardware.org/?probe=a298251c28) | Dec 13, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [5b4aff6fe8](https://linux-hardware.org/?probe=5b4aff6fe8) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [abeaa01348](https://linux-hardware.org/?probe=abeaa01348) | Dec 03, 2019 |
| HP            | EliteBook 856               | [80cf2af707](https://linux-hardware.org/?probe=80cf2af707) | Nov 22, 2019 |
| HP            | Pavilion dv6                | [6f6270eb8e](https://linux-hardware.org/?probe=6f6270eb8e) | Nov 16, 2019 |
| HP            | Pavilion dv6                | [c08e4bac64](https://linux-hardware.org/?probe=c08e4bac64) | Nov 16, 2019 |
| HP            | EliteBook 8460p             | [56a12d5f20](https://linux-hardware.org/?probe=56a12d5f20) | Nov 09, 2019 |
| Acer          | AOD260                      | [a911172500](https://linux-hardware.org/?probe=a911172500) | Nov 09, 2019 |
| Sony          | VGN-C260E                   | [c623de88ee](https://linux-hardware.org/?probe=c623de88ee) | Oct 24, 2019 |
| Lenovo        | G505s 20255                 | [36deb3b32d](https://linux-hardware.org/?probe=36deb3b32d) | Oct 13, 2019 |
| HP            | Pavilion dv6                | [c2264e7abd](https://linux-hardware.org/?probe=c2264e7abd) | Oct 11, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | [77b1afae40](https://linux-hardware.org/?probe=77b1afae40) | Oct 09, 2019 |
| ASUSTek       | K53SV                       | [61f7ec13d8](https://linux-hardware.org/?probe=61f7ec13d8) | Sep 19, 2019 |
| ASUSTek       | K53E                        | [71fd2610fe](https://linux-hardware.org/?probe=71fd2610fe) | Sep 15, 2019 |
| ASUSTek       | K53E                        | [e435064ad7](https://linux-hardware.org/?probe=e435064ad7) | Sep 15, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [3baafefb84](https://linux-hardware.org/?probe=3baafefb84) | Aug 27, 2019 |
| Prestigio     | PSB141C02                   | [3e96d56c17](https://linux-hardware.org/?probe=3e96d56c17) | Aug 25, 2019 |
| ASUSTek       | K53E                        | [c1811b7ec3](https://linux-hardware.org/?probe=c1811b7ec3) | Aug 23, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | [15419d9561](https://linux-hardware.org/?probe=15419d9561) | Aug 20, 2019 |
| HP            | Laptop 15-bw0xx             | [7653d7fa4d](https://linux-hardware.org/?probe=7653d7fa4d) | Jul 29, 2019 |
| Lenovo        | G550 20023                  | [601d53f9eb](https://linux-hardware.org/?probe=601d53f9eb) | Jul 23, 2019 |
| Lenovo        | ThinkPad R500 27327KG       | [c8b31c9d99](https://linux-hardware.org/?probe=c8b31c9d99) | Jun 04, 2019 |
| Dell          | Inspiron N5010              | [23d8e1dd30](https://linux-hardware.org/?probe=23d8e1dd30) | May 31, 2019 |
| Acer          | TravelMate 5740G            | [0d4611c952](https://linux-hardware.org/?probe=0d4611c952) | May 25, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [be887070fe](https://linux-hardware.org/?probe=be887070fe) | May 17, 2019 |
| Toshiba       | Satellite C50D-A-13G        | [c39268dff8](https://linux-hardware.org/?probe=c39268dff8) | May 13, 2019 |
| Toshiba       | Satellite C50D-A-13G        | [e0d133befc](https://linux-hardware.org/?probe=e0d133befc) | May 13, 2019 |
| HP            | ProBook 6555b               | [598fc6c1ca](https://linux-hardware.org/?probe=598fc6c1ca) | May 13, 2019 |
| HP            | ProBook 4540s               | [2e61bfe1be](https://linux-hardware.org/?probe=2e61bfe1be) | Apr 28, 2019 |
| HP            | ProBook 4540s               | [8d460232a9](https://linux-hardware.org/?probe=8d460232a9) | Apr 28, 2019 |
| Dell          | Inspiron 5737               | [2c7d308e3a](https://linux-hardware.org/?probe=2c7d308e3a) | Apr 26, 2019 |
| Dell          | Inspiron 5737               | [dcf03f780e](https://linux-hardware.org/?probe=dcf03f780e) | Apr 26, 2019 |
| Acer          | TravelMate 5740G            | [6b69828c13](https://linux-hardware.org/?probe=6b69828c13) | Apr 07, 2019 |
| Sony          | VPCZ1390S                   | [eb4e58c4d9](https://linux-hardware.org/?probe=eb4e58c4d9) | Mar 05, 2019 |
| Sony          | VPCZ1390S                   | [8995c67e48](https://linux-hardware.org/?probe=8995c67e48) | Mar 05, 2019 |
| Lenovo        | ThinkPad X230 2325AEG       | [2b8bcfe576](https://linux-hardware.org/?probe=2b8bcfe576) | Feb 19, 2019 |
| ASUSTek       | X550LB                      | [992697103b](https://linux-hardware.org/?probe=992697103b) | Jan 18, 2019 |
| ASUSTek       | X550LB                      | [5228ac3dbc](https://linux-hardware.org/?probe=5228ac3dbc) | Jan 18, 2019 |
| Lenovo        | ThinkPad L440 20ASA10P00    | [dffa2ed3ef](https://linux-hardware.org/?probe=dffa2ed3ef) | Dec 20, 2018 |
| Lenovo        | ThinkPad L440 20ASA10P00    | [e192353344](https://linux-hardware.org/?probe=e192353344) | Dec 20, 2018 |
| Lenovo        | G550 20023                  | [54fd0e13d2](https://linux-hardware.org/?probe=54fd0e13d2) | Oct 29, 2018 |
| Lenovo        | G550 20023                  | [3011864d4b](https://linux-hardware.org/?probe=3011864d4b) | Oct 25, 2018 |
| ASUSTek       | K53E                        | [0e63193763](https://linux-hardware.org/?probe=0e63193763) | Oct 21, 2018 |
| ASUSTek       | K53E                        | [8a053e30bf](https://linux-hardware.org/?probe=8a053e30bf) | Sep 30, 2018 |
| ASUSTek       | K53E                        | [8e1eab57d7](https://linux-hardware.org/?probe=8e1eab57d7) | Sep 03, 2018 |
| ASUSTek       | 1225B                       | [fb333d2cde](https://linux-hardware.org/?probe=fb333d2cde) | Aug 23, 2018 |
| ASUSTek       | K53E                        | [8ebafe3965](https://linux-hardware.org/?probe=8ebafe3965) | Aug 04, 2018 |
| ASUSTek       | K53E                        | [58b632622d](https://linux-hardware.org/?probe=58b632622d) | Apr 15, 2018 |
| ASUSTek       | X555LN                      | [9760e114b0](https://linux-hardware.org/?probe=9760e114b0) | Apr 07, 2018 |
| ASUSTek       | X555LN                      | [c3f232766b](https://linux-hardware.org/?probe=c3f232766b) | Apr 07, 2018 |
| ASUSTek       | K53SV                       | [e3e865dedf](https://linux-hardware.org/?probe=e3e865dedf) | Apr 06, 2018 |
| ASUSTek       | K53SV                       | [041cd61823](https://linux-hardware.org/?probe=041cd61823) | Dec 14, 2017 |
| Acer          | Aspire 5610Z                | [c79786fae0](https://linux-hardware.org/?probe=c79786fae0) | Dec 12, 2017 |
| Dell          | Inspiron 3537               | [0cb8d57f73](https://linux-hardware.org/?probe=0cb8d57f73) | Sep 25, 2017 |
| ASUSTek       | M50Vc                       | [9224093b58](https://linux-hardware.org/?probe=9224093b58) | Aug 22, 2017 |
| ASUSTek       | K53SV                       | [366e5e884c](https://linux-hardware.org/?probe=366e5e884c) | Jun 23, 2017 |
| Lenovo        | B50-10 80QR                 | [0ba3b01a3b](https://linux-hardware.org/?probe=0ba3b01a3b) | May 17, 2017 |
| Lenovo        | B50-10 80QR                 | [0a9d97b358](https://linux-hardware.org/?probe=0a9d97b358) | Apr 11, 2017 |
| Dell          | Precision M4600             | [2a09c39637](https://linux-hardware.org/?probe=2a09c39637) | Mar 15, 2017 |
| Dell          | Precision M4600             | [c9a115e18c](https://linux-hardware.org/?probe=c9a115e18c) | Mar 15, 2017 |
| Acer          | Aspire ES1-711              | [0f7625ddc4](https://linux-hardware.org/?probe=0f7625ddc4) | Mar 10, 2017 |
| Acer          | Aspire ES1-711              | [64cea7b4eb](https://linux-hardware.org/?probe=64cea7b4eb) | Mar 10, 2017 |
| Dell          | Precision M4600             | [e851921cd7](https://linux-hardware.org/?probe=e851921cd7) | Oct 24, 2016 |
| Dell          | Latitude E6440              | [ea1b5da2e7](https://linux-hardware.org/?probe=ea1b5da2e7) | Dec 07, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 25        | 11.26%  |
| Ubuntu 18.04       | 19        | 8.56%   |
| Arch Rolling       | 10        | 4.5%    |
| Ubuntu 22.04       | 7         | 3.15%   |
| Ubuntu 19.04       | 5         | 2.25%   |
| ROSA R11           | 5         | 2.25%   |
| Pop!_OS 21.04      | 5         | 2.25%   |
| OpenMandriva 4.3   | 5         | 2.25%   |
| Zorin 16           | 4         | 1.8%    |
| Xubuntu 20.04      | 4         | 1.8%    |
| ROSA R9            | 4         | 1.8%    |
| ROSA R8.1          | 4         | 1.8%    |
| ROSA R10           | 4         | 1.8%    |
| Pop!_OS 20.04      | 4         | 1.8%    |
| OpenMandriva 4.2   | 4         | 1.8%    |
| Linux Mint 21.1    | 4         | 1.8%    |
| Linux Mint 20      | 4         | 1.8%    |
| KDE neon 20.04     | 4         | 1.8%    |
| Arch               | 4         | 1.8%    |
| Xubuntu 19.10      | 3         | 1.35%   |
| ROSA R11.1         | 3         | 1.35%   |
| Linux Mint 20.1    | 3         | 1.35%   |
| Kubuntu 22.04      | 3         | 1.35%   |
| Fedora 36          | 3         | 1.35%   |
| Debian 10          | 3         | 1.35%   |
| ArcoLinux Rolling  | 3         | 1.35%   |
| Zorin 15           | 2         | 0.9%    |
| Ubuntu 20.10       | 2         | 0.9%    |
| Ubuntu 19.10       | 2         | 0.9%    |
| Ubuntu 16.04       | 2         | 0.9%    |
| RED X3             | 2         | 0.9%    |
| Pop!_OS 22.04      | 2         | 0.9%    |
| Pop!_OS 21.10      | 2         | 0.9%    |
| Manjaro 20.2.1     | 2         | 0.9%    |
| Manjaro 20.2       | 2         | 0.9%    |
| Linux Mint 19.2    | 2         | 0.9%    |
| Fedora 37          | 2         | 0.9%    |
| Fedora 34          | 2         | 0.9%    |
| Xubuntu 18.04      | 1         | 0.45%   |
| Ubuntu Unity 21.04 | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 63        | 30.58%  |
| ROSA         | 15        | 7.28%   |
| Linux Mint   | 15        | 7.28%   |
| Pop!_OS      | 14        | 6.8%    |
| Arch         | 13        | 6.31%   |
| OpenMandriva | 10        | 4.85%   |
| Manjaro      | 10        | 4.85%   |
| Fedora       | 10        | 4.85%   |
| Zorin        | 6         | 2.91%   |
| Xubuntu      | 6         | 2.91%   |
| KDE neon     | 6         | 2.91%   |
| Debian       | 5         | 2.43%   |
| Kubuntu      | 4         | 1.94%   |
| Gentoo       | 4         | 1.94%   |
| Lubuntu      | 3         | 1.46%   |
| Endless      | 3         | 1.46%   |
| ArcoLinux    | 3         | 1.46%   |
| Ubuntu Unity | 2         | 0.97%   |
| Ubuntu MATE  | 2         | 0.97%   |
| RED          | 2         | 0.97%   |
| openSUSE     | 2         | 0.97%   |
| RHEL         | 1         | 0.49%   |
| Peppermint   | 1         | 0.49%   |
| LMDE         | 1         | 0.49%   |
| EndeavourOS  | 1         | 0.49%   |
| Elementary   | 1         | 0.49%   |
| Drauger OS   | 1         | 0.49%   |
| CentOS       | 1         | 0.49%   |
| Artix        | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.4.0-42-generic                    | 5         | 2.08%   |
| 5.13.0-40-generic                   | 5         | 2.08%   |
| 5.16.7-desktop-1omv4003             | 4         | 1.67%   |
| 5.10.14-desktop-1omv4002            | 4         | 1.67%   |
| 5.4.0-48-generic                    | 3         | 1.25%   |
| 5.4.0-47-generic                    | 3         | 1.25%   |
| 5.3.0-26-generic                    | 3         | 1.25%   |
| 5.15.0-56-generic                   | 3         | 1.25%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 3         | 1.25%   |
| 4.15.0-91-generic                   | 3         | 1.25%   |
| 5.8.0-44-generic                    | 2         | 0.83%   |
| 5.4.0-7634-generic                  | 2         | 0.83%   |
| 5.4.0-73-generic                    | 2         | 0.83%   |
| 5.4.0-66-generic                    | 2         | 0.83%   |
| 5.4.0-52-generic                    | 2         | 0.83%   |
| 5.4.0-31-generic                    | 2         | 0.83%   |
| 5.3.0-28-generic                    | 2         | 0.83%   |
| 5.15.0-67-generic                   | 2         | 0.83%   |
| 5.15.0-50-generic                   | 2         | 0.83%   |
| 5.15.0-43-generic                   | 2         | 0.83%   |
| 5.13.0-35-generic                   | 2         | 0.83%   |
| 5.11.0-7633-generic                 | 2         | 0.83%   |
| 5.0.0-37-generic                    | 2         | 0.83%   |
| 5.0.0-25-generic                    | 2         | 0.83%   |
| 4.4.16-nrj-desktop-1rosa-x86_64     | 2         | 0.83%   |
| 4.15.0-desktop-60.7rosa-i586        | 2         | 0.83%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 2         | 0.83%   |
| 4.15.0-29-generic                   | 2         | 0.83%   |
| 6.2.7-gentoo-dist                   | 1         | 0.42%   |
| 6.2.7-200.fc37.x86_64               | 1         | 0.42%   |
| 6.2.6-zen1-1-zen                    | 1         | 0.42%   |
| 6.2.2-desktop-1omv2390              | 1         | 0.42%   |
| 6.2.1-gentoo-x86_64                 | 1         | 0.42%   |
| 6.1.7-200.fc37.x86_64               | 1         | 0.42%   |
| 6.1.6-1-default                     | 1         | 0.42%   |
| 6.1.19-1-lts                        | 1         | 0.42%   |
| 6.1.11-200.fc37.x86_64              | 1         | 0.42%   |
| 6.1.10-gentoo-x86_64                | 1         | 0.42%   |
| 6.1.1-desktop-1omv2290              | 1         | 0.42%   |
| 6.1.0-1004-oem                      | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 35        | 15.56%  |
| 4.15.0  | 20        | 8.89%   |
| 5.15.0  | 15        | 6.67%   |
| 5.3.0   | 13        | 5.78%   |
| 5.13.0  | 10        | 4.44%   |
| 5.0.0   | 10        | 4.44%   |
| 5.8.0   | 9         | 4%      |
| 5.11.0  | 6         | 2.67%   |
| 5.16.7  | 5         | 2.22%   |
| 5.19.0  | 4         | 1.78%   |
| 5.10.14 | 4         | 1.78%   |
| 4.18.0  | 4         | 1.78%   |
| 4.9.41  | 3         | 1.33%   |
| 6.2.7   | 2         | 0.89%   |
| 5.8.18  | 2         | 0.89%   |
| 5.8.11  | 2         | 0.89%   |
| 5.4.13  | 2         | 0.89%   |
| 5.17.5  | 2         | 0.89%   |
| 5.10.16 | 2         | 0.89%   |
| 5.10.0  | 2         | 0.89%   |
| 4.9.9   | 2         | 0.89%   |
| 4.9.60  | 2         | 0.89%   |
| 4.9.20  | 2         | 0.89%   |
| 4.4.16  | 2         | 0.89%   |
| 4.19.0  | 2         | 0.89%   |
| 6.2.6   | 1         | 0.44%   |
| 6.2.2   | 1         | 0.44%   |
| 6.2.1   | 1         | 0.44%   |
| 6.1.7   | 1         | 0.44%   |
| 6.1.6   | 1         | 0.44%   |
| 6.1.19  | 1         | 0.44%   |
| 6.1.11  | 1         | 0.44%   |
| 6.1.10  | 1         | 0.44%   |
| 6.1.1   | 1         | 0.44%   |
| 6.1.0   | 1         | 0.44%   |
| 6.0.6   | 1         | 0.44%   |
| 6.0.0   | 1         | 0.44%   |
| 5.9.3   | 1         | 0.44%   |
| 5.9.16  | 1         | 0.44%   |
| 5.9.14  | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 42        | 19%     |
| 5.15    | 22        | 9.95%   |
| 4.15    | 20        | 9.05%   |
| 5.8     | 14        | 6.33%   |
| 5.3     | 13        | 5.88%   |
| 5.10    | 13        | 5.88%   |
| 5.13    | 12        | 5.43%   |
| 5.0     | 11        | 4.98%   |
| 4.9     | 11        | 4.98%   |
| 5.16    | 8         | 3.62%   |
| 5.11    | 8         | 3.62%   |
| 6.1     | 6         | 2.71%   |
| 5.19    | 6         | 2.71%   |
| 6.2     | 5         | 2.26%   |
| 5.17    | 4         | 1.81%   |
| 5.12    | 4         | 1.81%   |
| 4.18    | 4         | 1.81%   |
| 5.9     | 3         | 1.36%   |
| 4.4     | 3         | 1.36%   |
| 6.0     | 2         | 0.9%    |
| 5.6     | 2         | 0.9%    |
| 4.19    | 2         | 0.9%    |
| 5.7     | 1         | 0.45%   |
| 5.18    | 1         | 0.45%   |
| 5.14    | 1         | 0.45%   |
| 4.14    | 1         | 0.45%   |
| 4.1     | 1         | 0.45%   |
| 3.16    | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 182       | 94.3%   |
| i686   | 11        | 5.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 80        | 38.83%  |
| KDE5            | 34        | 16.5%   |
| Unknown         | 24        | 11.65%  |
| XFCE            | 15        | 7.28%   |
| X-Cinnamon      | 14        | 6.8%    |
| KDE4            | 13        | 6.31%   |
| KDE             | 5         | 2.43%   |
| LXQt            | 4         | 1.94%   |
| Unity           | 3         | 1.46%   |
| MATE            | 3         | 1.46%   |
| GNOME Flashback | 2         | 0.97%   |
| awesome         | 2         | 0.97%   |
| Pantheon        | 1         | 0.49%   |
| LXDE            | 1         | 0.49%   |
| Enlightenment   | 1         | 0.49%   |
| dwm             | 1         | 0.49%   |
| Deepin          | 1         | 0.49%   |
| Cinnamon        | 1         | 0.49%   |
| Budgie          | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 155       | 77.5%   |
| Wayland | 27        | 13.5%   |
| Unknown | 11        | 5.5%    |
| Tty     | 7         | 3.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 97        | 47.78%  |
| SDDM    | 30        | 14.78%  |
| GDM     | 27        | 13.3%   |
| LightDM | 15        | 7.39%   |
| GDM3    | 13        | 6.4%    |
| KDM     | 12        | 5.91%   |
| TDM     | 8         | 3.94%   |
| XDM     | 1         | 0.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 114       | 57%     |
| Unknown | 37        | 18.5%   |
| lt_LT   | 31        | 15.5%   |
| ru_RU   | 6         | 3%      |
| en_GB   | 6         | 3%      |
| C       | 3         | 1.5%    |
| en_AU   | 2         | 1%      |
| nl_NL   | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 103       | 52.28%  |
| BIOS | 94        | 47.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 149       | 75.25%  |
| Btrfs   | 16        | 8.08%   |
| Unknown | 16        | 8.08%   |
| Overlay | 11        | 5.56%   |
| Xfs     | 4         | 2.02%   |
| Zfs     | 1         | 0.51%   |
| ExX4    | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 105       | 52.76%  |
| GPT     | 74        | 37.19%  |
| MBR     | 20        | 10.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 173       | 88.27%  |
| Yes       | 23        | 11.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 155       | 79.08%  |
| Yes       | 41        | 20.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 60        | 31.41%  |
| ASUSTek Computer    | 39        | 20.42%  |
| Hewlett-Packard     | 28        | 14.66%  |
| Dell                | 28        | 14.66%  |
| Acer                | 11        | 5.76%   |
| MSI                 | 5         | 2.62%   |
| Samsung Electronics | 3         | 1.57%   |
| Toshiba             | 2         | 1.05%   |
| Sony                | 2         | 1.05%   |
| Panasonic           | 2         | 1.05%   |
| Timi                | 1         | 0.52%   |
| Prestigio           | 1         | 0.52%   |
| Packard Bell        | 1         | 0.52%   |
| Notebook            | 1         | 0.52%   |
| Jumper              | 1         | 0.52%   |
| HUAWEI              | 1         | 0.52%   |
| Fujitsu Siemens     | 1         | 0.52%   |
| eMachines           | 1         | 0.52%   |
| Apple               | 1         | 0.52%   |
| Alienware           | 1         | 0.52%   |
| Unknown             | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo ThinkPad T490 20N3000KMH                       | 2         | 1.05%   |
| Lenovo Legion Y530-15ICH 81FV                         | 2         | 1.05%   |
| Lenovo IdeaPad Y700-15ISK 80NV                        | 2         | 1.05%   |
| Lenovo G550 20023                                     | 2         | 1.05%   |
| HP EliteBook 8460p                                    | 2         | 1.05%   |
| ASUS K53E                                             | 2         | 1.05%   |
| Toshiba Satellite L855                                | 1         | 0.52%   |
| Toshiba Satellite C50D-A-13G                          | 1         | 0.52%   |
| Timi TM1701                                           | 1         | 0.52%   |
| Sony VPCZ1390S                                        | 1         | 0.52%   |
| Sony VGN-C260E                                        | 1         | 0.52%   |
| Samsung RC530/RC730                                   | 1         | 0.52%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.52%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.52%   |
| Prestigio PSB141C02                                   | 1         | 0.52%   |
| Panasonic CF-52WEBBYDE                                | 1         | 0.52%   |
| Panasonic CF-52VDA131M                                | 1         | 0.52%   |
| Packard Bell EasyNote TE11HC                          | 1         | 0.52%   |
| Notebook L140CU                                       | 1         | 0.52%   |
| MSI MS-16F1                                           | 1         | 0.52%   |
| MSI GT72 2PE                                          | 1         | 0.52%   |
| MSI GS66 Stealth 10UE                                 | 1         | 0.52%   |
| MSI GP70 2PE                                          | 1         | 0.52%   |
| MSI Bravo 15 A4DDR                                    | 1         | 0.52%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.52%   |
| Lenovo Yoga Creator 7 15IMH05 82DS                    | 1         | 0.52%   |
| Lenovo Y50-70 20378                                   | 1         | 0.52%   |
| Lenovo V130-15IGM 81HL                                | 1         | 0.52%   |
| Lenovo ThinkPad X270 W10DG 20K5S02K00                 | 1         | 0.52%   |
| Lenovo ThinkPad X230 2325AEG                          | 1         | 0.52%   |
| Lenovo ThinkPad X1 Nano Gen 1 20UN0060MH              | 1         | 0.52%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006KPB              | 1         | 0.52%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS03800              | 1         | 0.52%   |
| Lenovo ThinkPad W530 243852U                          | 1         | 0.52%   |
| Lenovo ThinkPad T60 1951FDG                           | 1         | 0.52%   |
| Lenovo ThinkPad T590 20N4004EMH                       | 1         | 0.52%   |
| Lenovo ThinkPad T500 2241W8Q                          | 1         | 0.52%   |
| Lenovo ThinkPad T480 20L50002MH                       | 1         | 0.52%   |
| Lenovo ThinkPad T460s 20F90058MH                      | 1         | 0.52%   |
| Lenovo ThinkPad T440p 20AWS4XN00                      | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 37        | 19.37%  |
| HP ProBook             | 11        | 5.76%   |
| Dell Inspiron          | 11        | 5.76%   |
| HP EliteBook           | 9         | 4.71%   |
| Lenovo IdeaPad         | 8         | 4.19%   |
| Dell Latitude          | 7         | 3.66%   |
| Acer Aspire            | 7         | 3.66%   |
| ASUS VivoBook          | 5         | 2.62%   |
| Lenovo Legion          | 4         | 2.09%   |
| Dell XPS               | 4         | 2.09%   |
| Toshiba Satellite      | 2         | 1.05%   |
| Lenovo Yoga            | 2         | 1.05%   |
| Lenovo G550            | 2         | 1.05%   |
| HP Pavilion            | 2         | 1.05%   |
| HP Laptop              | 2         | 1.05%   |
| HP 250                 | 2         | 1.05%   |
| Dell Vostro            | 2         | 1.05%   |
| Dell Precision         | 2         | 1.05%   |
| ASUS ZenBook           | 2         | 1.05%   |
| ASUS TUF               | 2         | 1.05%   |
| ASUS K53E              | 2         | 1.05%   |
| Timi TM1701            | 1         | 0.52%   |
| Sony VPCZ1390S         | 1         | 0.52%   |
| Sony VGN-C260E         | 1         | 0.52%   |
| Samsung RC530          | 1         | 0.52%   |
| Samsung 530U3C         | 1         | 0.52%   |
| Samsung 300E5EV        | 1         | 0.52%   |
| Prestigio PSB141C02    | 1         | 0.52%   |
| Panasonic CF-52WEBBYDE | 1         | 0.52%   |
| Panasonic CF-52VDA131M | 1         | 0.52%   |
| Packard Bell EasyNote  | 1         | 0.52%   |
| Notebook L140CU        | 1         | 0.52%   |
| MSI MS-16F1            | 1         | 0.52%   |
| MSI GT72               | 1         | 0.52%   |
| MSI GS66               | 1         | 0.52%   |
| MSI GP70               | 1         | 0.52%   |
| MSI Bravo              | 1         | 0.52%   |
| Lenovo Y50-70          | 1         | 0.52%   |
| Lenovo V130-15IGM      | 1         | 0.52%   |
| Lenovo ThinkBook       | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 18        | 9.42%   |
| 2020 | 17        | 8.9%    |
| 2018 | 17        | 8.9%    |
| 2019 | 16        | 8.38%   |
| 2013 | 16        | 8.38%   |
| 2014 | 15        | 7.85%   |
| 2012 | 14        | 7.33%   |
| 2021 | 12        | 6.28%   |
| 2017 | 11        | 5.76%   |
| 2015 | 11        | 5.76%   |
| 2010 | 11        | 5.76%   |
| 2016 | 9         | 4.71%   |
| 2008 | 8         | 4.19%   |
| 2022 | 4         | 2.09%   |
| 2009 | 4         | 2.09%   |
| 2006 | 4         | 2.09%   |
| 2007 | 3         | 1.57%   |
| 2004 | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 191       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 174       | 90.16%  |
| Enabled  | 19        | 9.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 191       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 48        | 24.74%  |
| 4.01-8.0   | 45        | 23.2%   |
| 3.01-4.0   | 42        | 21.65%  |
| 8.01-16.0  | 34        | 17.53%  |
| 32.01-64.0 | 9         | 4.64%   |
| 1.01-2.0   | 9         | 4.64%   |
| 2.01-3.0   | 3         | 1.55%   |
| 24.01-32.0 | 2         | 1.03%   |
| 0.51-1.0   | 2         | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 69        | 31.22%  |
| 2.01-3.0  | 57        | 25.79%  |
| 4.01-8.0  | 36        | 16.29%  |
| 3.01-4.0  | 26        | 11.76%  |
| 0.51-1.0  | 19        | 8.6%    |
| 8.01-16.0 | 12        | 5.43%   |
| 0.01-0.5  | 2         | 0.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 142       | 72.45%  |
| 2      | 50        | 25.51%  |
| 3      | 4         | 2.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 118       | 60.82%  |
| Yes       | 76        | 39.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 84.38%  |
| No        | 30        | 15.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 98.95%  |
| No        | 2         | 1.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 76.14%  |
| No        | 47        | 23.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Lithuania | 191       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Vilnius      | 106       | 52.22%  |
| Kaunas       | 31        | 15.27%  |
| Šiauliai    | 12        | 5.91%   |
| Klaipėda    | 11        | 5.42%   |
| Alytus       | 5         | 2.46%   |
| Panevezys    | 4         | 1.97%   |
| Mažeikiai   | 4         | 1.97%   |
| Jonava       | 3         | 1.48%   |
| Utena        | 2         | 0.99%   |
| Palanga      | 2         | 0.99%   |
| Kėdainiai   | 2         | 0.99%   |
| Želva       | 1         | 0.49%   |
| Visaginas    | 1         | 0.49%   |
| Vėžaičiai | 1         | 0.49%   |
| Ukmerge      | 1         | 0.49%   |
| Trakai       | 1         | 0.49%   |
| Telšiai     | 1         | 0.49%   |
| Tauragė     | 1         | 0.49%   |
| Šilalė     | 1         | 0.49%   |
| Serdokai     | 1         | 0.49%   |
| Šeduva      | 1         | 0.49%   |
| Rokiškis    | 1         | 0.49%   |
| Plungė      | 1         | 0.49%   |
| Pasvalys     | 1         | 0.49%   |
| Molėtai     | 1         | 0.49%   |
| Mauruciai    | 1         | 0.49%   |
| Marijampolė | 1         | 0.49%   |
| Maneikiai    | 1         | 0.49%   |
| Karkliniai   | 1         | 0.49%   |
| Gargždai    | 1         | 0.49%   |
| Anykščiai  | 1         | 0.49%   |
| Agluonenai   | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 38        | 56     | 15.77%  |
| Seagate                 | 28        | 37     | 11.62%  |
| WDC                     | 24        | 34     | 9.96%   |
| Toshiba                 | 24        | 32     | 9.96%   |
| Kingston                | 19        | 24     | 7.88%   |
| SanDisk                 | 14        | 15     | 5.81%   |
| Intel                   | 13        | 15     | 5.39%   |
| Hitachi                 | 10        | 17     | 4.15%   |
| SK hynix                | 9         | 9      | 3.73%   |
| A-DATA Technology       | 8         | 8      | 3.32%   |
| Patriot                 | 7         | 8      | 2.9%    |
| HGST                    | 7         | 8      | 2.9%    |
| Unknown                 | 6         | 20     | 2.49%   |
| Crucial                 | 6         | 7      | 2.49%   |
| Micron Technology       | 3         | 3      | 1.24%   |
| China                   | 3         | 5      | 1.24%   |
| KingSpec                | 2         | 2      | 0.83%   |
| ASMT                    | 2         | 2      | 0.83%   |
| Apacer                  | 2         | 2      | 0.83%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.41%   |
| Union Memory            | 1         | 1      | 0.41%   |
| Team                    | 1         | 1      | 0.41%   |
| Plextor                 | 1         | 1      | 0.41%   |
| Phison Electronics      | 1         | 2      | 0.41%   |
| OCZ                     | 1         | 1      | 0.41%   |
| Netac NV                | 1         | 1      | 0.41%   |
| LITEONIT                | 1         | 1      | 0.41%   |
| LITEON                  | 1         | 2      | 0.41%   |
| KIOXIA                  | 1         | 1      | 0.41%   |
| GOODRAM                 | 1         | 1      | 0.41%   |
| Fujitsu                 | 1         | 1      | 0.41%   |
| FORESEE                 | 1         | 1      | 0.41%   |
| Dahua                   | 1         | 2      | 0.41%   |
| Corsair                 | 1         | 1      | 0.41%   |
| Apple                   | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 1.98%   |
| SanDisk NVMe SSD Drive 256GB                        | 5         | 1.98%   |
| Kingston SV300S37A120G 120GB SSD                    | 5         | 1.98%   |
| Intel NVMe SSD Drive 512GB                          | 5         | 1.98%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 1.19%   |
| Toshiba BG3 NVMe SSD Controller 512GB               | 3         | 1.19%   |
| Seagate ST9500325AS 500GB                           | 3         | 1.19%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 1.19%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 1.19%   |
| Samsung SSD 850 EVO 250GB                           | 3         | 1.19%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 1.19%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 1.19%   |
| HGST HTS541010A9E680 1TB                            | 3         | 1.19%   |
| Unknown MMC Card  64GB                              | 2         | 0.79%   |
| Toshiba NVMe SSD Drive 512GB                        | 2         | 0.79%   |
| Toshiba NVMe SSD Drive 256GB                        | 2         | 0.79%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.79%   |
| Toshiba HDWL110 1TB                                 | 2         | 0.79%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 2         | 0.79%   |
| Seagate ST9160821AS 160GB                           | 2         | 0.79%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 0.79%   |
| SanDisk X400 M.2 2280 256GB SSD                     | 2         | 0.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2         | 0.79%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                      | 2         | 0.79%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.79%   |
| Intel NVMe SSD Drive 32GB                           | 2         | 0.79%   |
| Intel NVMe SSD Drive 256GB                          | 2         | 0.79%   |
| Hitachi HTS545025B9A300 250GB                       | 2         | 0.79%   |
| HGST HTS721010A9E630 1TB                            | 2         | 0.79%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 0.79%   |
| China SATA SSD 120GB                                | 2         | 0.79%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1         | 0.4%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.4%    |
| WDC WDS100T2B0C-00PXH0 1TB                          | 1         | 0.4%    |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 0.4%    |
| WDC WD7500BPVX-22JC3T0 752GB                        | 1         | 0.4%    |
| WDC WD7500BPKT-75PK4T0 752GB                        | 1         | 0.4%    |
| WDC WD6400BPVT-22HXZT1 640GB                        | 1         | 0.4%    |
| WDC WD5000BPVT-80HXZT3 500GB                        | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 37     | 37.84%  |
| WDC                 | 15        | 22     | 20.27%  |
| Hitachi             | 10        | 17     | 13.51%  |
| Toshiba             | 9         | 12     | 12.16%  |
| HGST                | 7         | 8      | 9.46%   |
| Samsung Electronics | 2         | 3      | 2.7%    |
| Unknown             | 1         | 1      | 1.35%   |
| Fujitsu             | 1         | 1      | 1.35%   |
| ASMT                | 1         | 1      | 1.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 18        | 23     | 19.35%  |
| Samsung Electronics | 17        | 28     | 18.28%  |
| SanDisk             | 7         | 8      | 7.53%   |
| Patriot             | 7         | 8      | 7.53%   |
| A-DATA Technology   | 7         | 7      | 7.53%   |
| Toshiba             | 5         | 7      | 5.38%   |
| Crucial             | 5         | 5      | 5.38%   |
| WDC                 | 3         | 6      | 3.23%   |
| SK hynix            | 3         | 3      | 3.23%   |
| Intel               | 3         | 3      | 3.23%   |
| China               | 3         | 5      | 3.23%   |
| KingSpec            | 2         | 2      | 2.15%   |
| Apacer              | 2         | 2      | 2.15%   |
| Team                | 1         | 1      | 1.08%   |
| Plextor             | 1         | 1      | 1.08%   |
| OCZ                 | 1         | 1      | 1.08%   |
| LITEONIT            | 1         | 1      | 1.08%   |
| LITEON              | 1         | 2      | 1.08%   |
| GOODRAM             | 1         | 1      | 1.08%   |
| FORESEE             | 1         | 1      | 1.08%   |
| Dahua               | 1         | 2      | 1.08%   |
| Corsair             | 1         | 1      | 1.08%   |
| ASMT                | 1         | 1      | 1.08%   |
| Apple               | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 85        | 120    | 37.44%  |
| HDD  | 72        | 102    | 31.72%  |
| NVMe | 64        | 80     | 28.19%  |
| MMC  | 6         | 21     | 2.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 131       | 214    | 62.98%  |
| NVMe | 63        | 79     | 30.29%  |
| SAS  | 8         | 9      | 3.85%   |
| MMC  | 6         | 21     | 2.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 113       | 172    | 73.86%  |
| 0.51-1.0   | 39        | 49     | 25.49%  |
| 1.01-2.0   | 1         | 1      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 72        | 34.45%  |
| 251-500    | 53        | 25.36%  |
| 501-1000   | 26        | 12.44%  |
| 1-20       | 14        | 6.7%    |
| 51-100     | 14        | 6.7%    |
| 21-50      | 13        | 6.22%   |
| 1001-2000  | 8         | 3.83%   |
| Unknown    | 7         | 3.35%   |
| 2001-3000  | 2         | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 92        | 42.4%   |
| 21-50     | 34        | 15.67%  |
| 101-250   | 32        | 14.75%  |
| 51-100    | 29        | 13.36%  |
| 251-500   | 17        | 7.83%   |
| Unknown   | 7         | 3.23%   |
| 501-1000  | 4         | 1.84%   |
| 1001-2000 | 2         | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVX-60JC3T0 752GB             | 1         | 1      | 6.25%   |
| WDC WD6400BPVT-22HXZT1 640GB             | 1         | 2      | 6.25%   |
| Toshiba MK1652GSX 160GB                  | 1         | 2      | 6.25%   |
| SK hynix HFS256G39TND-N210A 256GB SSD    | 1         | 1      | 6.25%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 1         | 1      | 6.25%   |
| Seagate ST9640320AS 640GB                | 1         | 2      | 6.25%   |
| Samsung Electronics SSD 850 EVO 250GB    | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 840 Series 500GB | 1         | 2      | 6.25%   |
| Samsung Electronics HM641JI 640GB        | 1         | 1      | 6.25%   |
| Plextor PX-128M6M 128GB SSD              | 1         | 1      | 6.25%   |
| Hitachi HTS545050KTA300 500GB            | 1         | 1      | 6.25%   |
| Hitachi HTS545032B9A300 320GB            | 1         | 1      | 6.25%   |
| Hitachi HTS545025B9A300 250GB            | 1         | 1      | 6.25%   |
| HGST HTS725050A7E630 500GB               | 1         | 1      | 6.25%   |
| HGST HTS541010A9E680 1TB                 | 1         | 2      | 6.25%   |
| A-DATA Technology SX900 128GB SSD        | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 18.75%  |
| Hitachi             | 3         | 3      | 18.75%  |
| WDC                 | 2         | 3      | 12.5%   |
| SK hynix            | 2         | 2      | 12.5%   |
| HGST                | 2         | 3      | 12.5%   |
| Toshiba             | 1         | 2      | 6.25%   |
| Seagate             | 1         | 2      | 6.25%   |
| Plextor             | 1         | 1      | 6.25%   |
| A-DATA Technology   | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 3         | 3      | 30%     |
| WDC                 | 2         | 3      | 20%     |
| HGST                | 2         | 3      | 20%     |
| Toshiba             | 1         | 2      | 10%     |
| Seagate             | 1         | 2      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 14     | 62.5%   |
| SSD  | 5         | 6      | 31.25%  |
| NVMe | 1         | 1      | 6.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Hitachi HTS541010A9E680 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 114       | 186    | 55.61%  |
| Works    | 74        | 115    | 36.1%   |
| Malfunc  | 16        | 21     | 7.8%    |
| Failed   | 1         | 1      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 143       | 65.6%   |
| Samsung Electronics              | 20        | 9.17%   |
| AMD                              | 15        | 6.88%   |
| Toshiba America Info Systems     | 11        | 5.05%   |
| SanDisk                          | 10        | 4.59%   |
| SK hynix                         | 6         | 2.75%   |
| Micron Technology                | 3         | 1.38%   |
| Union Memory (Shenzhen)          | 2         | 0.92%   |
| Silicon Integrated Systems [SiS] | 1         | 0.46%   |
| Phison Electronics               | 1         | 0.46%   |
| Nvidia                           | 1         | 0.46%   |
| Micron/Crucial Technology        | 1         | 0.46%   |
| KIOXIA                           | 1         | 0.46%   |
| Kingston Technology Company      | 1         | 0.46%   |
| JMicron Technology               | 1         | 0.46%   |
| ADATA Technology                 | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 8.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 6.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 4.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 4.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 4.26%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 4.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 3.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 2.98%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 2.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 2.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 2.55%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 5         | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 2.13%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.7%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 1.7%    |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.7%    |
| Intel SSD 660P Series                                                          | 4         | 1.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.28%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.28%   |
| Micron NVMe Storage Controller                                                 | 3         | 1.28%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.28%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 3         | 1.28%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.28%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.85%   |
| SanDisk NVMe Controller                                                        | 2         | 0.85%   |
| Intel NVMe Controller                                                          | 2         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 0.85%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 127       | 57.73%  |
| NVMe | 63        | 28.64%  |
| RAID | 15        | 6.82%   |
| IDE  | 15        | 6.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 164       | 85.86%  |
| AMD    | 27        | 14.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz           | 6         | 3.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 4         | 2.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 2.08%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 4         | 2.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 4         | 2.08%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 4         | 2.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 4         | 2.08%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 2.08%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 3         | 1.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 3         | 1.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 1.56%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 1.56%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 3         | 1.56%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.56%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.04%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 2         | 1.04%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 2         | 1.04%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 1.04%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 2         | 1.04%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 1.04%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 1.04%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 2         | 1.04%   |
| Intel Core i7 CPU M 640 @ 2.80GHz           | 2         | 1.04%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 2         | 1.04%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 2         | 1.04%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.04%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 1.04%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 1.04%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.04%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.04%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.04%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 2         | 1.04%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.04%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 2         | 1.04%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz        | 2         | 1.04%   |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 2         | 1.04%   |
| Intel Celeron CPU B830 @ 1.80GHz            | 2         | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.04%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 2         | 1.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 52        | 27.23%  |
| Intel Core i5           | 46        | 24.08%  |
| Intel Core i3           | 24        | 12.57%  |
| Intel Celeron           | 9         | 4.71%   |
| AMD Ryzen 7             | 9         | 4.71%   |
| Other                   | 8         | 4.19%   |
| Intel Core 2 Duo        | 7         | 3.66%   |
| AMD Ryzen 5             | 7         | 3.66%   |
| Intel Pentium Dual-Core | 3         | 1.57%   |
| Intel Pentium           | 3         | 1.57%   |
| Intel Core i9           | 3         | 1.57%   |
| Intel Core 2            | 3         | 1.57%   |
| Intel Genuine           | 2         | 1.05%   |
| Intel Atom              | 2         | 1.05%   |
| AMD Ryzen 7 PRO         | 2         | 1.05%   |
| AMD Phenom II           | 2         | 1.05%   |
| AMD A8                  | 2         | 1.05%   |
| Intel Pentium Silver    | 1         | 0.52%   |
| Intel Core m7           | 1         | 0.52%   |
| AMD Sempron             | 1         | 0.52%   |
| AMD E                   | 1         | 0.52%   |
| AMD C-60                | 1         | 0.52%   |
| AMD A6                  | 1         | 0.52%   |
| AMD A10                 | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 90        | 46.63%  |
| 4       | 70        | 36.27%  |
| 8       | 14        | 7.25%   |
| 6       | 14        | 7.25%   |
| 1       | 3         | 1.55%   |
| Unknown | 2         | 1.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 191       | 99.48%  |
| Unknown | 1         | 0.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 147       | 76.56%  |
| 1       | 43        | 22.4%   |
| Unknown | 2         | 1.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 189       | 98.95%  |
| 32-bit         | 1         | 0.52%   |
| Unknown        | 1         | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 20.5%   |
| 0x306a9    | 19        | 9.5%    |
| 0x206a7    | 15        | 7.5%    |
| 0x806ea    | 10        | 5%      |
| 0x306c3    | 10        | 5%      |
| 0x406e3    | 7         | 3.5%    |
| 0x20655    | 7         | 3.5%    |
| 0x806c1    | 6         | 3%      |
| 0x40651    | 6         | 3%      |
| 0x1067a    | 6         | 3%      |
| 0x906ea    | 5         | 2.5%    |
| 0x806ec    | 5         | 2.5%    |
| 0x506e3    | 4         | 2%      |
| 0x306d4    | 4         | 2%      |
| 0xa0652    | 3         | 1.5%    |
| 0x806eb    | 3         | 1.5%    |
| 0x0a50000c | 3         | 1.5%    |
| 0x906ed    | 2         | 1%      |
| 0x906e9    | 2         | 1%      |
| 0x706a1    | 2         | 1%      |
| 0x6fd      | 2         | 1%      |
| 0x6f2      | 2         | 1%      |
| 0x30678    | 2         | 1%      |
| 0x20652    | 2         | 1%      |
| 0x10676    | 2         | 1%      |
| 0x0a404101 | 2         | 1%      |
| 0x08608103 | 2         | 1%      |
| 0x08108102 | 2         | 1%      |
| 0x05000119 | 2         | 1%      |
| 0x010000c8 | 2         | 1%      |
| 0x806e9    | 1         | 0.5%    |
| 0x706e5    | 1         | 0.5%    |
| 0x6fa      | 1         | 0.5%    |
| 0x6f6      | 1         | 0.5%    |
| 0x6ec      | 1         | 0.5%    |
| 0x506c9    | 1         | 0.5%    |
| 0x406c3    | 1         | 0.5%    |
| 0x106e5    | 1         | 0.5%    |
| 0x106ca    | 1         | 0.5%    |
| 0x10661    | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 36        | 18.85%  |
| IvyBridge       | 20        | 10.47%  |
| Haswell         | 20        | 10.47%  |
| SandyBridge     | 17        | 8.9%    |
| Skylake         | 13        | 6.81%   |
| Westmere        | 10        | 5.24%   |
| Penryn          | 8         | 4.19%   |
| TigerLake       | 7         | 3.66%   |
| Core            | 7         | 3.66%   |
| Zen 3           | 6         | 3.14%   |
| Zen 2           | 6         | 3.14%   |
| CometLake       | 6         | 3.14%   |
| Unknown         | 6         | 3.14%   |
| Broadwell       | 5         | 2.62%   |
| Goldmont plus   | 4         | 2.09%   |
| Silvermont      | 3         | 1.57%   |
| Zen+            | 2         | 1.05%   |
| Piledriver      | 2         | 1.05%   |
| Nehalem         | 2         | 1.05%   |
| K10             | 2         | 1.05%   |
| Goldmont        | 2         | 1.05%   |
| Bobcat          | 2         | 1.05%   |
| K8 & K10 hybrid | 1         | 0.52%   |
| Jaguar          | 1         | 0.52%   |
| IceLake         | 1         | 0.52%   |
| Excavator       | 1         | 0.52%   |
| Bonnell         | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 143       | 57.66%  |
| Nvidia                           | 56        | 22.58%  |
| AMD                              | 48        | 19.35%  |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 17        | 6.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 14        | 5.38%   |
| Intel UHD Graphics 620                                                        | 11        | 4.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 11        | 4.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 10        | 3.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 8         | 3.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 2.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 2.69%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 2.31%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 5         | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 1.92%   |
| Intel HD Graphics 5500                                                        | 5         | 1.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 5         | 1.92%   |
| AMD Renoir                                                                    | 5         | 1.92%   |
| Nvidia GP108M [GeForce MX150]                                                 | 4         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 1.54%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 1.54%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 4         | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 4         | 1.54%   |
| Intel HD Graphics 530                                                         | 4         | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 1.54%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                              | 4         | 1.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.15%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 3         | 1.15%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 0.77%   |
| Nvidia GP108M [GeForce MX330]                                                 | 2         | 0.77%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 0.77%   |
| Nvidia GM108M [GeForce 840M]                                                  | 2         | 0.77%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 0.77%   |
| Nvidia GK107M [GeForce GT 650M]                                               | 2         | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 2         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 0.77%   |
| Intel HD Graphics 630                                                         | 2         | 0.77%   |
| Intel HD Graphics 500                                                         | 2         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 0.77%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                               | 2         | 0.77%   |
| AMD Trinity [Radeon HD 7640G]                                                 | 2         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 87        | 45.31%  |
| Intel + Nvidia | 46        | 23.96%  |
| 1 x AMD        | 31        | 16.15%  |
| 1 x Nvidia     | 10        | 5.21%   |
| Intel + AMD    | 10        | 5.21%   |
| 2 x AMD        | 6         | 3.13%   |
| 1 x SiS        | 1         | 0.52%   |
| AMD + Nvidia   | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 166       | 84.69%  |
| Proprietary | 27        | 13.78%  |
| Unknown     | 3         | 1.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 107       | 53.77%  |
| 1.01-2.0   | 40        | 20.1%   |
| 0.01-0.5   | 22        | 11.06%  |
| 0.51-1.0   | 12        | 6.03%   |
| 3.01-4.0   | 11        | 5.53%   |
| 5.01-6.0   | 5         | 2.51%   |
| 7.01-8.0   | 1         | 0.5%    |
| 2.01-3.0   | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 45        | 20.18%  |
| AU Optronics            | 44        | 19.73%  |
| Samsung Electronics     | 22        | 9.87%   |
| Chimei Innolux          | 22        | 9.87%   |
| BOE                     | 21        | 9.42%   |
| Dell                    | 13        | 5.83%   |
| Lenovo                  | 12        | 5.38%   |
| Chi Mei Optoelectronics | 10        | 4.48%   |
| PANDA                   | 4         | 1.79%   |
| Goldstar                | 4         | 1.79%   |
| Sony                    | 3         | 1.35%   |
| Sharp                   | 3         | 1.35%   |
| Philips                 | 3         | 1.35%   |
| CSO                     | 2         | 0.9%    |
| Unknown (AAA)           | 1         | 0.45%   |
| Toshiba                 | 1         | 0.45%   |
| MStar                   | 1         | 0.45%   |
| LGD                     | 1         | 0.45%   |
| LG Philips              | 1         | 0.45%   |
| KDC                     | 1         | 0.45%   |
| JDI                     | 1         | 0.45%   |
| InfoVision              | 1         | 0.45%   |
| Iiyama                  | 1         | 0.45%   |
| IBM                     | 1         | 0.45%   |
| Hewlett-Packard         | 1         | 0.45%   |
| HannStar                | 1         | 0.45%   |
| ASUSTek Computer        | 1         | 0.45%   |
| Apple                   | 1         | 0.45%   |
| AOC                     | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 1.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.79%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 3         | 1.34%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                     | 3         | 1.34%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 1.34%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 1.34%   |
| Sony LCD Monitor MS_9005 1920x1200 331x207mm 15.4-inch                   | 2         | 0.89%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.89%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.89%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.89%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.89%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 2         | 0.89%   |
| Dell P2719H DEL4184 1920x1080 600x340mm 27.2-inch                        | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.89%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch           | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.89%   |
| Unknown (AAA) HDTV AAA0001 1360x768 575x323mm 26.0-inch                  | 1         | 0.45%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch                 | 1         | 0.45%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.45%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.45%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                  | 1         | 0.45%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.45%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch        | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0351 1680x1050 459x296mm 21.5-inch     | 1         | 0.45%   |
| Samsung Electronics S24D391 SAM0B87 1920x1080 521x293mm 23.5-inch        | 1         | 0.45%   |
| Samsung Electronics S24C450 SAM09CB 1920x1080 531x299mm 24.0-inch        | 1         | 0.45%   |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch        | 1         | 0.45%   |
| Samsung Electronics LS27A600N SAM716E 2560x1440 597x337mm 27.0-inch      | 1         | 0.45%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 527x296mm 23.8-inch      | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4258 1024x768 286x214mm 14.1-inch     | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 98        | 48.04%  |
| 1366x768 (WXGA)    | 48        | 23.53%  |
| 1600x900 (HD+)     | 15        | 7.35%   |
| 3840x2160 (4K)     | 10        | 4.9%    |
| 2560x1440 (QHD)    | 7         | 3.43%   |
| 1280x800 (WXGA)    | 6         | 2.94%   |
| 1920x1200 (WUXGA)  | 4         | 1.96%   |
| 3840x2400          | 2         | 0.98%   |
| 3440x1440          | 2         | 0.98%   |
| 2880x1800          | 2         | 0.98%   |
| 2560x1600          | 2         | 0.98%   |
| 1680x1050 (WSXGA+) | 2         | 0.98%   |
| 3000x2000          | 1         | 0.49%   |
| 2560x1080          | 1         | 0.49%   |
| 2160x1440          | 1         | 0.49%   |
| 1440x900 (WXGA+)   | 1         | 0.49%   |
| 1024x768 (XGA)     | 1         | 0.49%   |
| 1024x600           | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 109       | 49.1%   |
| 14      | 23        | 10.36%  |
| 13      | 23        | 10.36%  |
| 17      | 13        | 5.86%   |
| 24      | 11        | 4.95%   |
| 27      | 10        | 4.5%    |
| 23      | 8         | 3.6%    |
| 12      | 7         | 3.15%   |
| 21      | 4         | 1.8%    |
| 34      | 2         | 0.9%    |
| 16      | 2         | 0.9%    |
| 84      | 1         | 0.45%   |
| 72      | 1         | 0.45%   |
| 52      | 1         | 0.45%   |
| 40      | 1         | 0.45%   |
| 31      | 1         | 0.45%   |
| 29      | 1         | 0.45%   |
| 25      | 1         | 0.45%   |
| 11      | 1         | 0.45%   |
| 10      | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 146       | 66.06%  |
| 501-600     | 27        | 12.22%  |
| 201-300     | 17        | 7.69%   |
| 351-400     | 16        | 7.24%   |
| 601-700     | 4         | 1.81%   |
| 401-500     | 4         | 1.81%   |
| 701-800     | 2         | 0.9%    |
| 1501-2000   | 2         | 0.9%    |
| 801-900     | 1         | 0.45%   |
| 1001-1500   | 1         | 0.45%   |
| Unknown     | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 160       | 86.02%  |
| 16/10   | 20        | 10.75%  |
| 3/2     | 2         | 1.08%   |
| 21/9    | 2         | 1.08%   |
| 4/3     | 1         | 0.54%   |
| Unknown | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 107       | 48.42%  |
| 81-90          | 40        | 18.1%   |
| 201-250        | 21        | 9.5%    |
| 121-130        | 12        | 5.43%   |
| 301-350        | 10        | 4.52%   |
| 61-70          | 7         | 3.17%   |
| 71-80          | 5         | 2.26%   |
| 351-500        | 4         | 1.81%   |
| More than 1000 | 3         | 1.36%   |
| 111-120        | 3         | 1.36%   |
| 251-300        | 2         | 0.9%    |
| 91-100         | 2         | 0.9%    |
| 51-60          | 1         | 0.45%   |
| 41-50          | 1         | 0.45%   |
| 131-140        | 1         | 0.45%   |
| 501-1000       | 1         | 0.45%   |
| Unknown        | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 99        | 45.83%  |
| 101-120       | 53        | 24.54%  |
| 51-100        | 41        | 18.98%  |
| 161-240       | 14        | 6.48%   |
| More than 240 | 6         | 2.78%   |
| 1-50          | 2         | 0.93%   |
| Unknown       | 1         | 0.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 151       | 78.24%  |
| 2     | 34        | 17.62%  |
| 0     | 5         | 2.59%   |
| 3     | 3         | 1.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 103       | 33.88%  |
| Realtek Semiconductor             | 86        | 28.29%  |
| Qualcomm Atheros                  | 53        | 17.43%  |
| Broadcom                          | 22        | 7.24%   |
| MediaTek                          | 5         | 1.64%   |
| Ralink                            | 4         | 1.32%   |
| Marvell Technology Group          | 4         | 1.32%   |
| Lenovo                            | 4         | 1.32%   |
| Broadcom Limited                  | 3         | 0.99%   |
| Sierra Wireless                   | 2         | 0.66%   |
| JMicron Technology                | 2         | 0.66%   |
| Fibocom                           | 2         | 0.66%   |
| Ericsson Business Mobile Networks | 2         | 0.66%   |
| Dell                              | 2         | 0.66%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.33%   |
| TP-Link                           | 1         | 0.33%   |
| Ralink Technology                 | 1         | 0.33%   |
| Qualcomm Atheros Communications   | 1         | 0.33%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.33%   |
| Nvidia                            | 1         | 0.33%   |
| MOBILE                            | 1         | 0.33%   |
| Hewlett-Packard                   | 1         | 0.33%   |
| D-Link                            | 1         | 0.33%   |
| ASIX Electronics                  | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 57        | 15.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 16        | 4.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 3.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 12        | 3.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 2.65%   |
| Intel Wireless 8265 / 8275                                              | 10        | 2.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 9         | 2.39%   |
| Intel Wireless 8260                                                     | 9         | 2.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.12%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 2.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 2.12%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 1.33%   |
| Intel Wireless 7260                                                     | 5         | 1.33%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.06%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.06%   |
| Intel Wireless 7265                                                     | 4         | 1.06%   |
| Intel Ethernet Connection I219-LM                                       | 4         | 1.06%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.8%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 3         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 3         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.8%    |
| Intel Wireless 3165                                                     | 3         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                                   | 3         | 0.8%    |
| Intel Ethernet Connection (6) I219-V                                    | 3         | 0.8%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.8%    |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 101       | 50.5%   |
| Qualcomm Atheros                | 46        | 23%     |
| Broadcom                        | 17        | 8.5%    |
| Realtek Semiconductor           | 16        | 8%      |
| MediaTek                        | 5         | 2.5%    |
| Ralink                          | 4         | 2%      |
| Sierra Wireless                 | 2         | 1%      |
| Fibocom                         | 2         | 1%      |
| Dell                            | 2         | 1%      |
| TP-Link                         | 1         | 0.5%    |
| Ralink Technology               | 1         | 0.5%    |
| Qualcomm Atheros Communications | 1         | 0.5%    |
| D-Link                          | 1         | 0.5%    |
| Broadcom Limited                | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 7%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 5%      |
| Intel Wireless 8265 / 8275                                              | 10        | 5%      |
| Intel Wireless 8260                                                     | 9         | 4.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 4%      |
| Intel Wi-Fi 6 AX200                                                     | 8         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 4%      |
| Intel Wi-Fi 6 AX201                                                     | 6         | 3%      |
| Intel Wireless 7260                                                     | 5         | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2%      |
| Intel Wireless 7265                                                     | 4         | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.5%    |
| Intel Wireless 3165                                                     | 3         | 1.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.5%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.5%    |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.5%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1%      |
| Intel Wireless-AC 9260                                                  | 2         | 1%      |
| Intel Wireless 3160                                                     | 2         | 1%      |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1%      |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1%      |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1%      |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 2         | 1%      |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 2         | 1%      |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1%      |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 81        | 47.93%  |
| Intel                         | 41        | 24.26%  |
| Qualcomm Atheros              | 20        | 11.83%  |
| Broadcom                      | 10        | 5.92%   |
| Marvell Technology Group      | 4         | 2.37%   |
| Lenovo                        | 4         | 2.37%   |
| JMicron Technology            | 2         | 1.18%   |
| Broadcom Limited              | 2         | 1.18%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.59%   |
| OnePlus Technology (Shenzhen) | 1         | 0.59%   |
| Nvidia                        | 1         | 0.59%   |
| MOBILE                        | 1         | 0.59%   |
| ASIX Electronics              | 1         | 0.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 57        | 32.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 16        | 9.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 6.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 5.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 2.87%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 2.3%    |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 2.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 1.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 1.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 1.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 1.72%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3         | 1.72%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 1.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.15%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.15%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 1.15%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 1.15%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.15%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.15%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.15%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 2         | 1.15%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.15%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 1.15%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 1.15%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                                  | 1         | 0.57%   |
| Realtek USB 10/100 LAN                                                         | 1         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.57%   |
| OnePlus (Shenzhen) Android                                                     | 1         | 0.57%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.57%   |
| MOBILE                                                                         | 1         | 0.57%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.57%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.57%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.57%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]                    | 1         | 0.57%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                            | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 189       | 53.39%  |
| Ethernet | 162       | 45.76%  |
| Modem    | 3         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 157       | 74.41%  |
| Ethernet | 54        | 25.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 152       | 79.58%  |
| 1     | 35        | 18.32%  |
| 0     | 3         | 1.57%   |
| 3     | 1         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 191       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 69        | 45.1%   |
| Qualcomm Atheros Communications | 21        | 13.73%  |
| IMC Networks                    | 13        | 8.5%    |
| Broadcom                        | 13        | 8.5%    |
| Realtek Semiconductor           | 9         | 5.88%   |
| Foxconn / Hon Hai               | 6         | 3.92%   |
| Ralink                          | 4         | 2.61%   |
| Cambridge Silicon Radio         | 4         | 2.61%   |
| ASUSTek Computer                | 4         | 2.61%   |
| Dell                            | 3         | 1.96%   |
| Toshiba                         | 2         | 1.31%   |
| Hewlett-Packard                 | 2         | 1.31%   |
| Taiyo Yuden                     | 1         | 0.65%   |
| Lite-On Technology              | 1         | 0.65%   |
| Apple                           | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 30        | 19.61%  |
| Intel AX201 Bluetooth                                                               | 16        | 10.46%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 6.54%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 4.58%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 7         | 4.58%   |
| Intel AX200 Bluetooth                                                               | 7         | 4.58%   |
| Realtek Bluetooth Radio                                                             | 6         | 3.92%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 2.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 2.61%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 2.61%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.96%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.96%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.96%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.31%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.31%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.31%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.31%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 1.31%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.31%   |
| Broadcom BCM2046 Bluetooth Device                                                   | 2         | 1.31%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.31%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 2         | 1.31%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.65%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.65%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                                             | 1         | 0.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.65%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.65%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.65%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.65%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.65%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.65%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.65%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.65%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]                              | 1         | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.65%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 161       | 67.36%  |
| AMD                              | 39        | 16.32%  |
| Nvidia                           | 27        | 11.3%   |
| Lenovo                           | 4         | 1.67%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Realtek Semiconductor            | 1         | 0.42%   |
| Microsoft                        | 1         | 0.42%   |
| Hewlett-Packard                  | 1         | 0.42%   |
| GN Netcom                        | 1         | 0.42%   |
| DSEA A/S                         | 1         | 0.42%   |
| Creative Technology              | 1         | 0.42%   |
| C-Media Electronics              | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 22        | 7.69%   |
| Intel Sunrise Point-LP HD Audio                                            | 21        | 7.34%   |
| AMD Family 17h/19h HD Audio Controller                                     | 18        | 6.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15        | 5.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 4.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 4.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 3.85%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 3.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 3.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 2.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 2.45%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 2.45%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 2.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 2.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.75%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.4%    |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 1.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.4%    |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.05%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 1.05%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.05%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.7%    |
| Nvidia GF106 High Definition Audio Controller                              | 2         | 0.7%    |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 2         | 0.7%    |
| Intel CM238 HD Audio Controller                                            | 2         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.7%    |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.7%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 0.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 0.7%    |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 32.06%  |
| SK hynix            | 25        | 19.08%  |
| Kingston            | 18        | 13.74%  |
| Micron Technology   | 15        | 11.45%  |
| Crucial             | 6         | 4.58%   |
| Ramaxel Technology  | 5         | 3.82%   |
| Unknown             | 4         | 3.05%   |
| Elpida              | 4         | 3.05%   |
| Nanya Technology    | 3         | 2.29%   |
| Patriot             | 2         | 1.53%   |
| A-DATA Technology   | 2         | 1.53%   |
| Unknown (ABCD)      | 1         | 0.76%   |
| Lexar               | 1         | 0.76%   |
| G.Skill             | 1         | 0.76%   |
| Corsair             | 1         | 0.76%   |
| Unknown             | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 2.16%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 2.16%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.16%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.44%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 1.44%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 1.44%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.44%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.44%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 1.44%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s            | 2         | 1.44%   |
| Kingston RAM MSI16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s           | 2         | 1.44%   |
| Elpida RAM EBJ41UF8BDU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 1.44%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.72%   |
| Unknown RAM Module 1GB SODIMM DDR2 333MT/s                       | 1         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.72%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 0.72%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 1         | 0.72%   |
| SK hynix RAM HYMP512S64BP8-Y5 1GB SODIMM DDR 667MT/s             | 1         | 0.72%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 0.72%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.72%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s           | 1         | 0.72%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.72%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.72%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.72%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.72%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 49        | 44.55%  |
| DDR4   | 43        | 39.09%  |
| LPDDR3 | 6         | 5.45%   |
| DDR2   | 5         | 4.55%   |
| LPDDR4 | 4         | 3.64%   |
| LPDDR5 | 1         | 0.91%   |
| DRAM   | 1         | 0.91%   |
| DDR5   | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 103       | 92.79%  |
| Row Of Chips | 8         | 7.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 43        | 36.75%  |
| 4096  | 42        | 35.9%   |
| 16384 | 18        | 15.38%  |
| 2048  | 9         | 7.69%   |
| 1024  | 4         | 3.42%   |
| 32768 | 1         | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 35        | 29.66%  |
| 2667    | 26        | 22.03%  |
| 3200    | 21        | 17.8%   |
| 1334    | 8         | 6.78%   |
| 2133    | 5         | 4.24%   |
| 1333    | 5         | 4.24%   |
| 1867    | 4         | 3.39%   |
| 667     | 3         | 2.54%   |
| 2400    | 2         | 1.69%   |
| 1067    | 2         | 1.69%   |
| 6400    | 1         | 0.85%   |
| 4800    | 1         | 0.85%   |
| 4267    | 1         | 0.85%   |
| 3266    | 1         | 0.85%   |
| 800     | 1         | 0.85%   |
| 333     | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 39        | 23.08%  |
| IMC Networks                           | 33        | 19.53%  |
| Microdia                               | 14        | 8.28%   |
| Sunplus Innovation Technology          | 13        | 7.69%   |
| Acer                                   | 11        | 6.51%   |
| Realtek Semiconductor                  | 10        | 5.92%   |
| Suyin                                  | 8         | 4.73%   |
| Luxvisions Innotech Limited            | 6         | 3.55%   |
| Syntek                                 | 5         | 2.96%   |
| Alcor Micro                            | 5         | 2.96%   |
| Silicon Motion                         | 3         | 1.78%   |
| Quanta                                 | 3         | 1.78%   |
| Lite-On Technology                     | 3         | 1.78%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.78%   |
| OmniVision Technologies                | 2         | 1.18%   |
| Bison Electronics                      | 2         | 1.18%   |
| Sonix Technology                       | 1         | 0.59%   |
| Ricoh                                  | 1         | 0.59%   |
| Primax Electronics                     | 1         | 0.59%   |
| Lenovo                                 | 1         | 0.59%   |
| Intel                                  | 1         | 0.59%   |
| Importek                               | 1         | 0.59%   |
| DigiTech                               | 1         | 0.59%   |
| Apple                                  | 1         | 0.59%   |
| ALi                                    | 1         | 0.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 14        | 8.28%   |
| IMC Networks USB2.0 HD UVC WebCam                | 9         | 5.33%   |
| IMC Networks Integrated Camera                   | 9         | 5.33%   |
| Microdia Integrated_Webcam_HD                    | 7         | 4.14%   |
| Acer Integrated Camera                           | 4         | 2.37%   |
| Syntek Lenovo EasyCamera                         | 3         | 1.78%   |
| Sunplus Integrated_Webcam_HD                     | 3         | 1.78%   |
| Sunplus HP HD Webcam [Fixed]                     | 3         | 1.78%   |
| Luxvisions Innotech Limited HP HD Camera         | 3         | 1.78%   |
| IMC Networks UVC VGA Webcam                      | 3         | 1.78%   |
| IMC Networks 2M Integrated Webcam                | 3         | 1.78%   |
| Chicony USB2.0 HD UVC WebCam                     | 3         | 1.78%   |
| Suyin HP Webcam                                  | 2         | 1.18%   |
| Sunplus HD WebCam                                | 2         | 1.18%   |
| Sunplus Asus Webcam                              | 2         | 1.18%   |
| Silicon Motion Lenovo EasyCamera                 | 2         | 1.18%   |
| Realtek Integrated_Webcam_HD                     | 2         | 1.18%   |
| Microdia Integrated Webcam                       | 2         | 1.18%   |
| Lite-On Integrated Camera                        | 2         | 1.18%   |
| IMC Networks VGA UVC WebCam                      | 2         | 1.18%   |
| Chicony Webcam                                   | 2         | 1.18%   |
| Chicony USB2.0 0.3M UVC WebCam                   | 2         | 1.18%   |
| Chicony HP Webcam [2 MP Macro]                   | 2         | 1.18%   |
| Chicony HP Laptop Integrated Webcam [2 MP Fixed] | 2         | 1.18%   |
| Chicony HP HD Webcam                             | 2         | 1.18%   |
| Chicony HP HD Camera                             | 2         | 1.18%   |
| Alcor Micro USB 2.0 Camera                       | 2         | 1.18%   |
| Alcor Micro Asus Integrated Webcam               | 2         | 1.18%   |
| Acer SunplusIT Integrated Camera                 | 2         | 1.18%   |
| Syntek Sonix USB 2.0 Camera                      | 1         | 0.59%   |
| Syntek Integrated Camera                         | 1         | 0.59%   |
| Suyin WebCam                                     | 1         | 0.59%   |
| Suyin Laptop_Integrated_Webcam_HD                | 1         | 0.59%   |
| Suyin Integrated Camera                          | 1         | 0.59%   |
| Suyin HP TrueVision HD Integrated Webcam         | 1         | 0.59%   |
| Suyin Acer/Lenovo Webcam [CN0316]                | 1         | 0.59%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.59%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 0.59%   |
| Sunplus Integrated_Webcam_FHD                    | 1         | 0.59%   |
| Sunplus Integrated Camera                        | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 16        | 38.1%   |
| Validity Sensors           | 11        | 26.19%  |
| Shenzhen Goodix Technology | 4         | 9.52%   |
| Elan Microelectronics      | 4         | 9.52%   |
| AuthenTec                  | 4         | 9.52%   |
| STMicroelectronics         | 2         | 4.76%   |
| LighTuning Technology      | 1         | 2.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 9         | 21.43%  |
| Validity Sensors VFS471 Fingerprint Reader                 | 3         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 7.14%   |
| Elan ELAN:Fingerprint                                      | 3         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 4.76%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 4.76%   |
| STMicroelectronics Fingerprint Reader                      | 2         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 4.76%   |
| AuthenTec AES2810                                          | 2         | 4.76%   |
| AuthenTec AES1600                                          | 2         | 4.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 2.38%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 2.38%   |
| Validity Sensors VFS491                                    | 1         | 2.38%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.38%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.38%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.38%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 2.38%   |
| Shenzhen Goodix FingerPrint                                | 1         | 2.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 2.38%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 12        | 60%     |
| Broadcom              | 5         | 25%     |
| Gemalto (was Gemplus) | 2         | 10%     |
| Upek                  | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 60%     |
| Broadcom 5880                                                                | 2         | 10%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 5%      |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5%      |
| Broadcom 58200                                                               | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 113       | 57.36%  |
| 1     | 59        | 29.95%  |
| 2     | 19        | 9.64%   |
| 3     | 5         | 2.54%   |
| 4     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 40        | 35.4%   |
| Graphics card            | 22        | 19.47%  |
| Chipcard                 | 19        | 16.81%  |
| Net/wireless             | 8         | 7.08%   |
| Multimedia controller    | 6         | 5.31%   |
| Bluetooth                | 5         | 4.42%   |
| Camera                   | 4         | 3.54%   |
| Communication controller | 3         | 2.65%   |
| Storage/raid             | 1         | 0.88%   |
| Storage                  | 1         | 0.88%   |
| Sound                    | 1         | 0.88%   |
| Net/ethernet             | 1         | 0.88%   |
| Flash memory             | 1         | 0.88%   |
| Card reader              | 1         | 0.88%   |

