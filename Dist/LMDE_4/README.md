LMDE 4 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 4.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_4/Desktop/README.md) and [notebooks](/Dist/LMDE_4/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 608

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire 3000                 | Notebook    | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c62874f456](https://linux-hardware.org/?probe=c62874f456) | Oct 04, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [7a7717e793](https://linux-hardware.org/?probe=7a7717e793) | Sep 21, 2022 |
| ASRock        | G41M-S3                     | Desktop     | [2cdcaebd43](https://linux-hardware.org/?probe=2cdcaebd43) | Sep 10, 2022 |
| HP            | Notebook                    | Notebook    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
| ASUSTek       | P5B                         | Desktop     | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
| ASUSTek       | P5QL PRO                    | Desktop     | [9ea782b1d2](https://linux-hardware.org/?probe=9ea782b1d2) | May 08, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [2a3b9ad6cf](https://linux-hardware.org/?probe=2a3b9ad6cf) | Apr 24, 2022 |
| Acer          | AOD270                      | Notebook    | [b53cedd40c](https://linux-hardware.org/?probe=b53cedd40c) | Apr 23, 2022 |
| Foxconn       | Cinema Series FAB           | Desktop     | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [6fbd04d8fd](https://linux-hardware.org/?probe=6fbd04d8fd) | Apr 11, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [eb751efc1f](https://linux-hardware.org/?probe=eb751efc1f) | Apr 09, 2022 |
| ASUSTek       | 901                         | Notebook    | [d118ee90d5](https://linux-hardware.org/?probe=d118ee90d5) | Apr 01, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [9113320f2f](https://linux-hardware.org/?probe=9113320f2f) | Mar 31, 2022 |
| Acer          | EG43M                       | Desktop     | [28b4dd5236](https://linux-hardware.org/?probe=28b4dd5236) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [d02cab0935](https://linux-hardware.org/?probe=d02cab0935) | Mar 30, 2022 |
| Dell          | Latitude D620               | Notebook    | [172cd26e35](https://linux-hardware.org/?probe=172cd26e35) | Mar 26, 2022 |
| HP            | ProBook 6465b               | Notebook    | [2e1792442b](https://linux-hardware.org/?probe=2e1792442b) | Mar 24, 2022 |
| HP            | ProBook 6465b               | Notebook    | [51a296abf8](https://linux-hardware.org/?probe=51a296abf8) | Mar 24, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [346857be22](https://linux-hardware.org/?probe=346857be22) | Mar 24, 2022 |
| ASUSTek       | P4P800                      | Desktop     | [0cb6a89491](https://linux-hardware.org/?probe=0cb6a89491) | Mar 19, 2022 |
| HP            | 0AA8h                       | Desktop     | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| Acer          | TravelMate 420              | Notebook    | [13cae0e399](https://linux-hardware.org/?probe=13cae0e399) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [b1ca65b3e0](https://linux-hardware.org/?probe=b1ca65b3e0) | Mar 08, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Dell          | Latitude D620               | Notebook    | [d4e50f40f3](https://linux-hardware.org/?probe=d4e50f40f3) | Mar 06, 2022 |
| HP            | ENVY 6                      | Notebook    | [23f60a7428](https://linux-hardware.org/?probe=23f60a7428) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [d163816373](https://linux-hardware.org/?probe=d163816373) | Mar 02, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [6b6c4bd7b7](https://linux-hardware.org/?probe=6b6c4bd7b7) | Feb 28, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [544979fc4f](https://linux-hardware.org/?probe=544979fc4f) | Feb 27, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | Notebook    | [4bd308dadf](https://linux-hardware.org/?probe=4bd308dadf) | Feb 26, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | Notebook    | [ec2491adc1](https://linux-hardware.org/?probe=ec2491adc1) | Feb 26, 2022 |
| Dell          | 0HR330                      | Desktop     | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell          | 0HR330                      | Desktop     | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| HP            | 0AA8h                       | Desktop     | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [a0d52488b2](https://linux-hardware.org/?probe=a0d52488b2) | Feb 22, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [74009233c2](https://linux-hardware.org/?probe=74009233c2) | Feb 19, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [e2ab1c19df](https://linux-hardware.org/?probe=e2ab1c19df) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | Notebook    | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| EVOO          | EVC141-12                   | Notebook    | [25710a76b8](https://linux-hardware.org/?probe=25710a76b8) | Feb 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0731118682](https://linux-hardware.org/?probe=0731118682) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5026ea812a](https://linux-hardware.org/?probe=5026ea812a) | Feb 15, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [bf2672168d](https://linux-hardware.org/?probe=bf2672168d) | Feb 14, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [bcbb1884aa](https://linux-hardware.org/?probe=bcbb1884aa) | Feb 13, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| ASUSTek       | 901                         | Notebook    | [27a497fdf8](https://linux-hardware.org/?probe=27a497fdf8) | Feb 04, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [e6091c93a9](https://linux-hardware.org/?probe=e6091c93a9) | Feb 02, 2022 |
| EVGA          | 131-HE-E095                 | Desktop     | [6d45d47131](https://linux-hardware.org/?probe=6d45d47131) | Jan 31, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [00cd805015](https://linux-hardware.org/?probe=00cd805015) | Jan 23, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [be068c5a3a](https://linux-hardware.org/?probe=be068c5a3a) | Jan 21, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [a988797ac9](https://linux-hardware.org/?probe=a988797ac9) | Jan 16, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [311d594372](https://linux-hardware.org/?probe=311d594372) | Jan 13, 2022 |
| Digma         | EVE 10 C301T ES1043EW       | Tablet      | [4fac8e2cb1](https://linux-hardware.org/?probe=4fac8e2cb1) | Jan 11, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [ea55ac1aab](https://linux-hardware.org/?probe=ea55ac1aab) | Jan 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [33457cde11](https://linux-hardware.org/?probe=33457cde11) | Jan 09, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [9fdbf19ebf](https://linux-hardware.org/?probe=9fdbf19ebf) | Jan 09, 2022 |
| Google        | Falco                       | Notebook    | [f450676688](https://linux-hardware.org/?probe=f450676688) | Jan 09, 2022 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [1d55cceee4](https://linux-hardware.org/?probe=1d55cceee4) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [43b421ad06](https://linux-hardware.org/?probe=43b421ad06) | Jan 08, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [bfcf287c09](https://linux-hardware.org/?probe=bfcf287c09) | Jan 08, 2022 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | Notebook    | [675eb28882](https://linux-hardware.org/?probe=675eb28882) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | Notebook    | [203577c78f](https://linux-hardware.org/?probe=203577c78f) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [41e93113b5](https://linux-hardware.org/?probe=41e93113b5) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [c977f6d6af](https://linux-hardware.org/?probe=c977f6d6af) | Jan 05, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [61978f9418](https://linux-hardware.org/?probe=61978f9418) | Jan 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [9d4bddea4d](https://linux-hardware.org/?probe=9d4bddea4d) | Jan 03, 2022 |
| OEM           | Unknown                     | Desktop     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [1ba0b3e854](https://linux-hardware.org/?probe=1ba0b3e854) | Jan 01, 2022 |
| Unknown       | K7VM2                       | Desktop     | [06f13210ad](https://linux-hardware.org/?probe=06f13210ad) | Dec 29, 2021 |
| Unknown       | K7VM2                       | Desktop     | [be785b672c](https://linux-hardware.org/?probe=be785b672c) | Dec 29, 2021 |
| Wistron       | ProLiant ML110 G5           | Server      | [8526295a2f](https://linux-hardware.org/?probe=8526295a2f) | Dec 27, 2021 |
| Advent        | Monza T100                  | Notebook    | [7355d1ae53](https://linux-hardware.org/?probe=7355d1ae53) | Dec 23, 2021 |
| Acer          | Aspire V5-573G              | Notebook    | [4c03d73b65](https://linux-hardware.org/?probe=4c03d73b65) | Dec 18, 2021 |
| HP            | Pavilion 14                 | Notebook    | [be9e6368e4](https://linux-hardware.org/?probe=be9e6368e4) | Dec 17, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [b2f24124da](https://linux-hardware.org/?probe=b2f24124da) | Dec 14, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [c4ed088328](https://linux-hardware.org/?probe=c4ed088328) | Dec 14, 2021 |
| HP            | 2AE3                        | Desktop     | [fb02077f16](https://linux-hardware.org/?probe=fb02077f16) | Dec 14, 2021 |
| HP            | 2AE3                        | Desktop     | [18efa559b9](https://linux-hardware.org/?probe=18efa559b9) | Dec 14, 2021 |
| ECS           | G41T-M7                     | Desktop     | [5a8641a9aa](https://linux-hardware.org/?probe=5a8641a9aa) | Dec 13, 2021 |
| Sony          | VPCP116KG                   | Notebook    | [237c9f66e1](https://linux-hardware.org/?probe=237c9f66e1) | Dec 13, 2021 |
| Fujitsu       | STYLISTIC Q550              | Notebook    | [e5d7b73e7f](https://linux-hardware.org/?probe=e5d7b73e7f) | Dec 12, 2021 |
| Fujitsu       | STYLISTIC Q550              | Notebook    | [8138236f20](https://linux-hardware.org/?probe=8138236f20) | Dec 12, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [43ff865e00](https://linux-hardware.org/?probe=43ff865e00) | Nov 28, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5300296119](https://linux-hardware.org/?probe=5300296119) | Nov 27, 2021 |
| Acer          | RS880M05                    | Desktop     | [2ce9c25975](https://linux-hardware.org/?probe=2ce9c25975) | Nov 25, 2021 |
| NEC Comput... | GA-8I945PM                  | Desktop     | [3d3711b8cc](https://linux-hardware.org/?probe=3d3711b8cc) | Nov 22, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [bb0a461d82](https://linux-hardware.org/?probe=bb0a461d82) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [024686087f](https://linux-hardware.org/?probe=024686087f) | Nov 20, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [b4b709eb1b](https://linux-hardware.org/?probe=b4b709eb1b) | Nov 18, 2021 |
| Samsung       | 305U1A                      | Notebook    | [c602ad4903](https://linux-hardware.org/?probe=c602ad4903) | Nov 18, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [18236d5a16](https://linux-hardware.org/?probe=18236d5a16) | Nov 18, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [86d2f89f59](https://linux-hardware.org/?probe=86d2f89f59) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [dad287d5a1](https://linux-hardware.org/?probe=dad287d5a1) | Nov 11, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [5a9ebbcad0](https://linux-hardware.org/?probe=5a9ebbcad0) | Nov 09, 2021 |
| Intel         | H61                         | Desktop     | [51f383b050](https://linux-hardware.org/?probe=51f383b050) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| Dell          | Latitude D630               | Notebook    | [ac9f57ab8f](https://linux-hardware.org/?probe=ac9f57ab8f) | Nov 02, 2021 |
| HP            | 843C                        | Desktop     | [e7df8fecdd](https://linux-hardware.org/?probe=e7df8fecdd) | Oct 30, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [f0983027ee](https://linux-hardware.org/?probe=f0983027ee) | Oct 26, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | Desktop     | [48187accde](https://linux-hardware.org/?probe=48187accde) | Oct 21, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [5b965ea234](https://linux-hardware.org/?probe=5b965ea234) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [3a5976d4eb](https://linux-hardware.org/?probe=3a5976d4eb) | Oct 17, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [f1fcb9d1db](https://linux-hardware.org/?probe=f1fcb9d1db) | Oct 17, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | Desktop     | [a1820d8f0c](https://linux-hardware.org/?probe=a1820d8f0c) | Oct 17, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [138df954cb](https://linux-hardware.org/?probe=138df954cb) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [dabe5d459a](https://linux-hardware.org/?probe=dabe5d459a) | Oct 15, 2021 |
| Acer          | Swift SF515-51T             | Notebook    | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| Medion        | P6670 MD99960               | Notebook    | [eaa186d207](https://linux-hardware.org/?probe=eaa186d207) | Oct 12, 2021 |
| Medion        | P6670 MD99960               | Notebook    | [d42f345fc5](https://linux-hardware.org/?probe=d42f345fc5) | Oct 12, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [940a27249a](https://linux-hardware.org/?probe=940a27249a) | Oct 12, 2021 |
| HP            | 520                         | Notebook    | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| Dell          | Precision M2800             | Notebook    | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| HUAWEI        | MateBook HZ-W19             | Tablet      | [904decfd32](https://linux-hardware.org/?probe=904decfd32) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [633c289440](https://linux-hardware.org/?probe=633c289440) | Sep 28, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [012056e32d](https://linux-hardware.org/?probe=012056e32d) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [a6d07be7c9](https://linux-hardware.org/?probe=a6d07be7c9) | Sep 27, 2021 |
| Biostar       | G41D3C                      | Desktop     | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [d5625a9406](https://linux-hardware.org/?probe=d5625a9406) | Sep 24, 2021 |
| Sony          | VPCS131FM                   | Notebook    | [b5bba0e07f](https://linux-hardware.org/?probe=b5bba0e07f) | Sep 22, 2021 |
| Sony          | VPCS131FM                   | Notebook    | [54923e2372](https://linux-hardware.org/?probe=54923e2372) | Sep 22, 2021 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [9c0ade7c9c](https://linux-hardware.org/?probe=9c0ade7c9c) | Sep 20, 2021 |
| Qbex          | UDPAIOQBEX01                | Notebook    | [34c385cfe4](https://linux-hardware.org/?probe=34c385cfe4) | Sep 13, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [9eec34a3f2](https://linux-hardware.org/?probe=9eec34a3f2) | Sep 13, 2021 |
| Acer          | Aspire 4320                 | Notebook    | [fae514c059](https://linux-hardware.org/?probe=fae514c059) | Sep 12, 2021 |
| Foxconn       | 945 7MC Series              | Desktop     | [623cb095f2](https://linux-hardware.org/?probe=623cb095f2) | Sep 12, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [3c335b37fa](https://linux-hardware.org/?probe=3c335b37fa) | Sep 10, 2021 |
| IBM           | ThinkPad T41 23737JY        | Notebook    | [86cf78a3cf](https://linux-hardware.org/?probe=86cf78a3cf) | Sep 09, 2021 |
| ASUSTek       | UN62                        | Desktop     | [0702f80222](https://linux-hardware.org/?probe=0702f80222) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [10052076e0](https://linux-hardware.org/?probe=10052076e0) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [8a0df29327](https://linux-hardware.org/?probe=8a0df29327) | Sep 09, 2021 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [844d7b2492](https://linux-hardware.org/?probe=844d7b2492) | Sep 09, 2021 |
| Matsushita... | CF-19DDGZXVM                | Notebook    | [6f54a42d76](https://linux-hardware.org/?probe=6f54a42d76) | Sep 08, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [305d566f57](https://linux-hardware.org/?probe=305d566f57) | Sep 07, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [d1773b3e3d](https://linux-hardware.org/?probe=d1773b3e3d) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [5d2cc7f4ca](https://linux-hardware.org/?probe=5d2cc7f4ca) | Sep 06, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [7122e4bd16](https://linux-hardware.org/?probe=7122e4bd16) | Sep 04, 2021 |
| Gigabyte      | M52LT-D3P                   | Desktop     | [09cbb5b50e](https://linux-hardware.org/?probe=09cbb5b50e) | Sep 03, 2021 |
| Gigabyte      | M52LT-D3P                   | Desktop     | [949b2062ea](https://linux-hardware.org/?probe=949b2062ea) | Sep 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Dell          | XPS M1330                   | Notebook    | [9dbd1f4ad9](https://linux-hardware.org/?probe=9dbd1f4ad9) | Aug 28, 2021 |
| ASUSTek       | 1201HA                      | Notebook    | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | Notebook    | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | Notebook    | [7706314dbc](https://linux-hardware.org/?probe=7706314dbc) | Aug 24, 2021 |
| Itautec       | W7655                       | Notebook    | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Itautec       | W7655                       | Notebook    | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| HP            | 14                          | Notebook    | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [c34caa75e2](https://linux-hardware.org/?probe=c34caa75e2) | Aug 23, 2021 |
| ASUSTek       | M51Sn                       | Notebook    | [5acb8c28ad](https://linux-hardware.org/?probe=5acb8c28ad) | Aug 21, 2021 |
| MSI           | MS-7142                     | Desktop     | [2700c74bd9](https://linux-hardware.org/?probe=2700c74bd9) | Aug 21, 2021 |
| MSI           | MS-7142                     | Desktop     | [18ae0c1bb3](https://linux-hardware.org/?probe=18ae0c1bb3) | Aug 21, 2021 |
| Packard Be... | EasyNote_NJ66               | Notebook    | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| HP            | 0AA8h                       | Desktop     | [d9a8fd3722](https://linux-hardware.org/?probe=d9a8fd3722) | Aug 15, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| ASUSTek       | A7N8X-LA                    | Desktop     | [0e9fd81caf](https://linux-hardware.org/?probe=0e9fd81caf) | Aug 11, 2021 |
| ASUSTek       | A7N8X-LA                    | Desktop     | [f14c99bbce](https://linux-hardware.org/?probe=f14c99bbce) | Aug 11, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [b937ce5e88](https://linux-hardware.org/?probe=b937ce5e88) | Aug 10, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [cff87306ab](https://linux-hardware.org/?probe=cff87306ab) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [16bec20604](https://linux-hardware.org/?probe=16bec20604) | Aug 06, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | Desktop     | [a1768aa578](https://linux-hardware.org/?probe=a1768aa578) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | Desktop     | [52aa712b0c](https://linux-hardware.org/?probe=52aa712b0c) | Aug 05, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [05c1703574](https://linux-hardware.org/?probe=05c1703574) | Aug 03, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [faf304d157](https://linux-hardware.org/?probe=faf304d157) | Aug 02, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [53ee243536](https://linux-hardware.org/?probe=53ee243536) | Aug 01, 2021 |
| OEM           | 45CMX/45GMX/45CMX-K         | Desktop     | [65d8eb687e](https://linux-hardware.org/?probe=65d8eb687e) | Jul 30, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [eafe3a403f](https://linux-hardware.org/?probe=eafe3a403f) | Jul 30, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [33a6186148](https://linux-hardware.org/?probe=33a6186148) | Jul 30, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [354b3bf7c6](https://linux-hardware.org/?probe=354b3bf7c6) | Jul 30, 2021 |
| ASUSTek       | 1201NL                      | Notebook    | [1ff8ed5a66](https://linux-hardware.org/?probe=1ff8ed5a66) | Jul 29, 2021 |
| ASUSTek       | 1201NL                      | Notebook    | [78fb5dfca9](https://linux-hardware.org/?probe=78fb5dfca9) | Jul 29, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [5ea0d9d644](https://linux-hardware.org/?probe=5ea0d9d644) | Jul 29, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| Intel         | BTC-T37                     | Desktop     | [bb5051b598](https://linux-hardware.org/?probe=bb5051b598) | Jul 27, 2021 |
| ASRock        | FM2A85X Extreme4-M          | Desktop     | [aa0030f094](https://linux-hardware.org/?probe=aa0030f094) | Jul 26, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [763cb39ac0](https://linux-hardware.org/?probe=763cb39ac0) | Jul 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [10ca362cf0](https://linux-hardware.org/?probe=10ca362cf0) | Jul 19, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| Dell          | XPS M1330                   | Notebook    | [55de50364d](https://linux-hardware.org/?probe=55de50364d) | Jul 17, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [64d562d6ef](https://linux-hardware.org/?probe=64d562d6ef) | Jul 16, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | Notebook    | [a3f3785bc1](https://linux-hardware.org/?probe=a3f3785bc1) | Jul 15, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [3007b813c6](https://linux-hardware.org/?probe=3007b813c6) | Jul 13, 2021 |
| Dell          | Latitude E5520              | Notebook    | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [5cfa1dcb4f](https://linux-hardware.org/?probe=5cfa1dcb4f) | Jul 12, 2021 |
| Fujitsu Si... | AMILO Pa 2510               | Notebook    | [a4303cc0cf](https://linux-hardware.org/?probe=a4303cc0cf) | Jul 12, 2021 |
| Qbex          | UDPAIOQBEX01                | Notebook    | [9b96573429](https://linux-hardware.org/?probe=9b96573429) | Jul 11, 2021 |
| Dell          | Inspiron 1526               | Notebook    | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| ASUSTek       | M6Ne                        | Notebook    | [ae1c7d3df6](https://linux-hardware.org/?probe=ae1c7d3df6) | Jul 11, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [fbc1ae17b4](https://linux-hardware.org/?probe=fbc1ae17b4) | Jul 10, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [e9bbf0622c](https://linux-hardware.org/?probe=e9bbf0622c) | Jul 10, 2021 |
| HP            | Laptop 14-df0xxx            | Notebook    | [ce0ac9c2fe](https://linux-hardware.org/?probe=ce0ac9c2fe) | Jul 10, 2021 |
| MSI           | H81M-E34                    | Desktop     | [14c2f8a49d](https://linux-hardware.org/?probe=14c2f8a49d) | Jul 05, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [9d356e787a](https://linux-hardware.org/?probe=9d356e787a) | Jul 01, 2021 |
| Samsung       | R59/R60/R61                 | Notebook    | [c0f5798a5b](https://linux-hardware.org/?probe=c0f5798a5b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [f9a80b7b6b](https://linux-hardware.org/?probe=f9a80b7b6b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [c7ddbbda0a](https://linux-hardware.org/?probe=c7ddbbda0a) | Jun 27, 2021 |
| Lenovo        | ThinkPad X100e 28762FP      | Notebook    | [95661d2e39](https://linux-hardware.org/?probe=95661d2e39) | Jun 27, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [d0c68c57a8](https://linux-hardware.org/?probe=d0c68c57a8) | Jun 26, 2021 |
| Samsung       | RV413/RV513                 | Notebook    | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Gateway       | M675                        | Notebook    | [ebdf5aa678](https://linux-hardware.org/?probe=ebdf5aa678) | Jun 25, 2021 |
| Acer          | Aspire one                  | Notebook    | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| HP            | 0A98h                       | Desktop     | [40990f73a5](https://linux-hardware.org/?probe=40990f73a5) | Jun 22, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | Notebook    | [b96ab4b06e](https://linux-hardware.org/?probe=b96ab4b06e) | Jun 18, 2021 |
| HP            | 0AA8h                       | Desktop     | [43103b39a5](https://linux-hardware.org/?probe=43103b39a5) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | Notebook    | [9072bce23d](https://linux-hardware.org/?probe=9072bce23d) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | Notebook    | [b557ccbf94](https://linux-hardware.org/?probe=b557ccbf94) | Jun 17, 2021 |
| Dell          | Latitude E6410              | Notebook    | [bd3a2db03c](https://linux-hardware.org/?probe=bd3a2db03c) | Jun 16, 2021 |
| HP            | Notebook                    | Notebook    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| HP            | 0AA8h                       | Desktop     | [9154911bc9](https://linux-hardware.org/?probe=9154911bc9) | Jun 13, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [67bbff8363](https://linux-hardware.org/?probe=67bbff8363) | Jun 11, 2021 |
| Gateway       | LT40                        | Notebook    | [fe2551cb8b](https://linux-hardware.org/?probe=fe2551cb8b) | Jun 11, 2021 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [699d10613e](https://linux-hardware.org/?probe=699d10613e) | Jun 11, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [4f752689ed](https://linux-hardware.org/?probe=4f752689ed) | Jun 03, 2021 |
| Gateway       | LT40                        | Notebook    | [6a966fe471](https://linux-hardware.org/?probe=6a966fe471) | Jun 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [3e408e9ead](https://linux-hardware.org/?probe=3e408e9ead) | May 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [39b2780acf](https://linux-hardware.org/?probe=39b2780acf) | May 31, 2021 |
| Dell          | 0HY9JP A01                  | Desktop     | [3f6ddbd81d](https://linux-hardware.org/?probe=3f6ddbd81d) | May 30, 2021 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [7d2b37e6e1](https://linux-hardware.org/?probe=7d2b37e6e1) | May 29, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [adc801308b](https://linux-hardware.org/?probe=adc801308b) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [d03d2796a0](https://linux-hardware.org/?probe=d03d2796a0) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [200072e2a7](https://linux-hardware.org/?probe=200072e2a7) | May 29, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [47f6c3e962](https://linux-hardware.org/?probe=47f6c3e962) | May 28, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | Desktop     | [cd3697bd15](https://linux-hardware.org/?probe=cd3697bd15) | May 25, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | Desktop     | [7c520b0d6e](https://linux-hardware.org/?probe=7c520b0d6e) | May 25, 2021 |
| ASUSTek       | X555UJ                      | Notebook    | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [55d981b2ed](https://linux-hardware.org/?probe=55d981b2ed) | May 23, 2021 |
| Intel         | H61                         | Desktop     | [1954634de4](https://linux-hardware.org/?probe=1954634de4) | May 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [fb309a7f37](https://linux-hardware.org/?probe=fb309a7f37) | May 17, 2021 |
| Foxconn       | 945 7MC Series              | Desktop     | [f4634ec470](https://linux-hardware.org/?probe=f4634ec470) | May 17, 2021 |
| Dell          | 0FM586 A00                  | Desktop     | [8a955d2c5a](https://linux-hardware.org/?probe=8a955d2c5a) | May 16, 2021 |
| ASUSTek       | B150M-A                     | Desktop     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [a502e8842e](https://linux-hardware.org/?probe=a502e8842e) | May 12, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | Notebook    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [4f117c46f3](https://linux-hardware.org/?probe=4f117c46f3) | May 09, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [3c0a297ede](https://linux-hardware.org/?probe=3c0a297ede) | May 08, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [2c91167099](https://linux-hardware.org/?probe=2c91167099) | May 07, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [c0b2f54ba4](https://linux-hardware.org/?probe=c0b2f54ba4) | May 07, 2021 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [0fd87c485e](https://linux-hardware.org/?probe=0fd87c485e) | May 07, 2021 |
| HP            | 530                         | Notebook    | [e94b7216d1](https://linux-hardware.org/?probe=e94b7216d1) | May 06, 2021 |
| HP            | 530                         | Notebook    | [8e3d65488a](https://linux-hardware.org/?probe=8e3d65488a) | May 06, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [38e06153e9](https://linux-hardware.org/?probe=38e06153e9) | May 04, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [3a72f19dd7](https://linux-hardware.org/?probe=3a72f19dd7) | May 01, 2021 |
| Toshiba       | dynabook Satellite J61 1... | Notebook    | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [46b0bab7d8](https://linux-hardware.org/?probe=46b0bab7d8) | Apr 27, 2021 |
| Lenovo        | ThinkPad X60 1706AA7        | Notebook    | [34a54e1198](https://linux-hardware.org/?probe=34a54e1198) | Apr 27, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | Notebook    | [66346c1594](https://linux-hardware.org/?probe=66346c1594) | Apr 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [e45a412c3d](https://linux-hardware.org/?probe=e45a412c3d) | Apr 26, 2021 |
| Unknown       | Phitronics N68C-M           | Desktop     | [3076a5bae3](https://linux-hardware.org/?probe=3076a5bae3) | Apr 24, 2021 |
| Unknown       | Phitronics N68C-M           | Desktop     | [d3a56832d9](https://linux-hardware.org/?probe=d3a56832d9) | Apr 23, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [f961a0339b](https://linux-hardware.org/?probe=f961a0339b) | Apr 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [662a781c83](https://linux-hardware.org/?probe=662a781c83) | Apr 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [edf38b6c4a](https://linux-hardware.org/?probe=edf38b6c4a) | Apr 21, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b243c0380f](https://linux-hardware.org/?probe=b243c0380f) | Apr 21, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [761a9ce0e9](https://linux-hardware.org/?probe=761a9ce0e9) | Apr 21, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [8ab143ec6b](https://linux-hardware.org/?probe=8ab143ec6b) | Apr 20, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [2813977a91](https://linux-hardware.org/?probe=2813977a91) | Apr 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d6c3daff43](https://linux-hardware.org/?probe=d6c3daff43) | Apr 19, 2021 |
| HP            | Pavilion dv7                | Notebook    | [0c3668cad6](https://linux-hardware.org/?probe=0c3668cad6) | Apr 19, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [fb3b69b074](https://linux-hardware.org/?probe=fb3b69b074) | Apr 18, 2021 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [47deff8a39](https://linux-hardware.org/?probe=47deff8a39) | Apr 17, 2021 |
| Toshiba       | NI 1403                     | Notebook    | [a3789d1a53](https://linux-hardware.org/?probe=a3789d1a53) | Apr 15, 2021 |
| HP            | Pavilion dv5                | Notebook    | [2df1512442](https://linux-hardware.org/?probe=2df1512442) | Apr 12, 2021 |
| HP            | Pavilion dv5                | Notebook    | [963a9c98df](https://linux-hardware.org/?probe=963a9c98df) | Apr 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [16d03cb92f](https://linux-hardware.org/?probe=16d03cb92f) | Apr 12, 2021 |
| Dell          | 0KP561                      | Desktop     | [3579bff9c4](https://linux-hardware.org/?probe=3579bff9c4) | Apr 08, 2021 |
| DFI           | LP BI P45-T2S Elite         | Desktop     | [01f0babd70](https://linux-hardware.org/?probe=01f0babd70) | Apr 08, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [c1b96ff3fa](https://linux-hardware.org/?probe=c1b96ff3fa) | Apr 04, 2021 |
| Pegatron      | 2ADC                        | Desktop     | [e4bfddb8d9](https://linux-hardware.org/?probe=e4bfddb8d9) | Apr 04, 2021 |
| MSI           | MS-7267                     | Desktop     | [d16e8a4364](https://linux-hardware.org/?probe=d16e8a4364) | Apr 03, 2021 |
| Supermicro    | X8DT3                       | Server      | [f645c4227c](https://linux-hardware.org/?probe=f645c4227c) | Apr 02, 2021 |
| LG Electro... | X300-L.CR31B1               | Notebook    | [728ce1cec3](https://linux-hardware.org/?probe=728ce1cec3) | Apr 02, 2021 |
| HP            | Mini 210-1100               | Notebook    | [4b8539128d](https://linux-hardware.org/?probe=4b8539128d) | Apr 01, 2021 |
| HP            | Mini 210-1100               | Notebook    | [a2a1a61099](https://linux-hardware.org/?probe=a2a1a61099) | Apr 01, 2021 |
| LG Electro... | X300-L.CR31B1               | Notebook    | [2dee5439bd](https://linux-hardware.org/?probe=2dee5439bd) | Apr 01, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | Notebook    | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| HP            | Unknown                     | Notebook    | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| Intel         | H61                         | Desktop     | [d7c3f87e52](https://linux-hardware.org/?probe=d7c3f87e52) | Mar 26, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [6ab1c423db](https://linux-hardware.org/?probe=6ab1c423db) | Mar 25, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [a9c3672597](https://linux-hardware.org/?probe=a9c3672597) | Mar 25, 2021 |
| HP            | Unknown                     | Notebook    | [2f594364bb](https://linux-hardware.org/?probe=2f594364bb) | Mar 20, 2021 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| MSI           | MS-6785                     | Desktop     | [303c1ac636](https://linux-hardware.org/?probe=303c1ac636) | Mar 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [06207199fa](https://linux-hardware.org/?probe=06207199fa) | Mar 16, 2021 |
| ASUSTek       | X542UAR                     | Notebook    | [4a2b4a2f3d](https://linux-hardware.org/?probe=4a2b4a2f3d) | Mar 15, 2021 |
| ASUSTek       | X542UAR                     | Notebook    | [824a5703c6](https://linux-hardware.org/?probe=824a5703c6) | Mar 15, 2021 |
| Sony          | VGN-FZ140E                  | Notebook    | [1d611ce57d](https://linux-hardware.org/?probe=1d611ce57d) | Mar 13, 2021 |
| Sony          | VGN-FZ140E                  | Notebook    | [3bfba9b2a3](https://linux-hardware.org/?probe=3bfba9b2a3) | Mar 13, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [f8503ecc3b](https://linux-hardware.org/?probe=f8503ecc3b) | Mar 10, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [553bb797b4](https://linux-hardware.org/?probe=553bb797b4) | Mar 09, 2021 |
| ECS           | A740GM-M                    | Desktop     | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [a8d2e4fa56](https://linux-hardware.org/?probe=a8d2e4fa56) | Mar 07, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [8589da1141](https://linux-hardware.org/?probe=8589da1141) | Mar 06, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [79e6e8bbfc](https://linux-hardware.org/?probe=79e6e8bbfc) | Mar 06, 2021 |
| Lenovo        | ThinkPad T400 64741EG       | Notebook    | [1d54256d1d](https://linux-hardware.org/?probe=1d54256d1d) | Mar 04, 2021 |
| ASRock        | G31M-GS                     | Desktop     | [ea6fbcd94e](https://linux-hardware.org/?probe=ea6fbcd94e) | Mar 02, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [fba2e0f27a](https://linux-hardware.org/?probe=fba2e0f27a) | Mar 01, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [65e004cebd](https://linux-hardware.org/?probe=65e004cebd) | Mar 01, 2021 |
| HP            | Compaq nx7400 (EY294ET#A... | Notebook    | [b253d7d3fa](https://linux-hardware.org/?probe=b253d7d3fa) | Mar 01, 2021 |
| Acer          | EG43LMK                     | Desktop     | [249967a21a](https://linux-hardware.org/?probe=249967a21a) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [0ca0e1f04f](https://linux-hardware.org/?probe=0ca0e1f04f) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [0dcf8f701e](https://linux-hardware.org/?probe=0dcf8f701e) | Feb 27, 2021 |
| Samsung       | NC10                        | Notebook    | [968b0bf5ba](https://linux-hardware.org/?probe=968b0bf5ba) | Feb 26, 2021 |
| HP            | Pavilion dv6                | Notebook    | [1baf6f6c70](https://linux-hardware.org/?probe=1baf6f6c70) | Feb 26, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [b0a6138136](https://linux-hardware.org/?probe=b0a6138136) | Feb 25, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [527b138b70](https://linux-hardware.org/?probe=527b138b70) | Feb 22, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Acer          | Aspire 6930ZG               | Notebook    | [5e2260251a](https://linux-hardware.org/?probe=5e2260251a) | Feb 19, 2021 |
| Acer          | EG43LMK                     | Desktop     | [1c1fdf43c0](https://linux-hardware.org/?probe=1c1fdf43c0) | Feb 17, 2021 |
| Google        | Gnawty                      | Notebook    | [f2d007d3b0](https://linux-hardware.org/?probe=f2d007d3b0) | Feb 16, 2021 |
| Google        | Gnawty                      | Notebook    | [cf74012060](https://linux-hardware.org/?probe=cf74012060) | Feb 16, 2021 |
| Google        | Gnawty                      | Notebook    | [802daa9713](https://linux-hardware.org/?probe=802daa9713) | Feb 16, 2021 |
| MSI           | MS-7267                     | Desktop     | [6bf114a22f](https://linux-hardware.org/?probe=6bf114a22f) | Feb 15, 2021 |
| MSI           | MS-7267                     | Desktop     | [78e4d03c89](https://linux-hardware.org/?probe=78e4d03c89) | Feb 15, 2021 |
| Dell          | Latitude E6520              | Notebook    | [132c1f74fc](https://linux-hardware.org/?probe=132c1f74fc) | Feb 14, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [4b2befb0d2](https://linux-hardware.org/?probe=4b2befb0d2) | Feb 14, 2021 |
| Notebook      | WID2010                     | Notebook    | [289d2b0685](https://linux-hardware.org/?probe=289d2b0685) | Feb 10, 2021 |
| LG Electro... | X120-G.C7VPG                | Notebook    | [349c20610a](https://linux-hardware.org/?probe=349c20610a) | Feb 10, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [f4995bc45c](https://linux-hardware.org/?probe=f4995bc45c) | Feb 07, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c8e67a7d41](https://linux-hardware.org/?probe=c8e67a7d41) | Feb 07, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [6e605fd64d](https://linux-hardware.org/?probe=6e605fd64d) | Feb 06, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [ec667e7b35](https://linux-hardware.org/?probe=ec667e7b35) | Feb 05, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [b71d20e5de](https://linux-hardware.org/?probe=b71d20e5de) | Feb 05, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [3adb6d9dc1](https://linux-hardware.org/?probe=3adb6d9dc1) | Feb 05, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [26e90cd431](https://linux-hardware.org/?probe=26e90cd431) | Feb 02, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [61a1c29323](https://linux-hardware.org/?probe=61a1c29323) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [05c23c4247](https://linux-hardware.org/?probe=05c23c4247) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [8c45cfc073](https://linux-hardware.org/?probe=8c45cfc073) | Feb 02, 2021 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [47324765ec](https://linux-hardware.org/?probe=47324765ec) | Feb 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [94d77e9dd0](https://linux-hardware.org/?probe=94d77e9dd0) | Feb 02, 2021 |
| Maibenben     | XiaoMai5                    | Notebook    | [bd1f26e401](https://linux-hardware.org/?probe=bd1f26e401) | Feb 01, 2021 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [9761a3446c](https://linux-hardware.org/?probe=9761a3446c) | Jan 30, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [9c930ede42](https://linux-hardware.org/?probe=9c930ede42) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | Notebook    | [b5e359a765](https://linux-hardware.org/?probe=b5e359a765) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | Notebook    | [701f078d13](https://linux-hardware.org/?probe=701f078d13) | Jan 28, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e5bc80f882](https://linux-hardware.org/?probe=e5bc80f882) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [4845dac1e6](https://linux-hardware.org/?probe=4845dac1e6) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f86be88365](https://linux-hardware.org/?probe=f86be88365) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [e6066c8531](https://linux-hardware.org/?probe=e6066c8531) | Jan 26, 2021 |
| ASUSTek       | F5N                         | Notebook    | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Sony          | SVE1511N1ESI                | Notebook    | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | Notebook    | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [d04b2d493f](https://linux-hardware.org/?probe=d04b2d493f) | Jan 20, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [08ac15e868](https://linux-hardware.org/?probe=08ac15e868) | Jan 15, 2021 |
| Matsushita... | CF-19CHB23BE                | Notebook    | [e9fa72450f](https://linux-hardware.org/?probe=e9fa72450f) | Jan 14, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [d0da7a44f7](https://linux-hardware.org/?probe=d0da7a44f7) | Jan 14, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [0826a741c2](https://linux-hardware.org/?probe=0826a741c2) | Jan 13, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [e9f548f926](https://linux-hardware.org/?probe=e9f548f926) | Jan 13, 2021 |
| Alienware     | 06G6JW A00                  | Desktop     | [992089d02a](https://linux-hardware.org/?probe=992089d02a) | Jan 12, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [f894e05226](https://linux-hardware.org/?probe=f894e05226) | Jan 09, 2021 |
| Acer          | AOD270                      | Notebook    | [89562751d7](https://linux-hardware.org/?probe=89562751d7) | Jan 08, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [51ec8a1510](https://linux-hardware.org/?probe=51ec8a1510) | Jan 06, 2021 |
| ASUSTek       | P5K                         | Desktop     | [22a568db8e](https://linux-hardware.org/?probe=22a568db8e) | Jan 02, 2021 |
| ASUSTek       | P5K                         | Desktop     | [4233bd7b15](https://linux-hardware.org/?probe=4233bd7b15) | Jan 02, 2021 |
| Exper         | E10IL1                      | Notebook    | [8a1f9ff144](https://linux-hardware.org/?probe=8a1f9ff144) | Dec 31, 2020 |
| MSI           | MS-6570                     | Desktop     | [f6bdec1638](https://linux-hardware.org/?probe=f6bdec1638) | Dec 28, 2020 |
| Dell          | Precision M4800             | Notebook    | [10bfd0b228](https://linux-hardware.org/?probe=10bfd0b228) | Dec 27, 2020 |
| ASUSTek       | K55N                        | Notebook    | [e3edf30a97](https://linux-hardware.org/?probe=e3edf30a97) | Dec 26, 2020 |
| ASUSTek       | K55N                        | Notebook    | [d7630d7410](https://linux-hardware.org/?probe=d7630d7410) | Dec 26, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [95d4d575bf](https://linux-hardware.org/?probe=95d4d575bf) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | Notebook    | [c0f1039074](https://linux-hardware.org/?probe=c0f1039074) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | Notebook    | [5584ad5871](https://linux-hardware.org/?probe=5584ad5871) | Dec 24, 2020 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [5db0b2dedf](https://linux-hardware.org/?probe=5db0b2dedf) | Dec 23, 2020 |
| MSI           | MS-7541                     | Desktop     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | Desktop     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | Notebook    | [0b958b270d](https://linux-hardware.org/?probe=0b958b270d) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | Notebook    | [94d64e448f](https://linux-hardware.org/?probe=94d64e448f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [d1a973f77f](https://linux-hardware.org/?probe=d1a973f77f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [a9ece8f5d0](https://linux-hardware.org/?probe=a9ece8f5d0) | Dec 21, 2020 |
| Lenovo        | Gardenia CRB                | All in one  | [53b3108cb8](https://linux-hardware.org/?probe=53b3108cb8) | Dec 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [7f143b3e74](https://linux-hardware.org/?probe=7f143b3e74) | Dec 20, 2020 |
| Unknown       | Unknown                     | Notebook    | [64b25942e1](https://linux-hardware.org/?probe=64b25942e1) | Dec 20, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [192f91ada6](https://linux-hardware.org/?probe=192f91ada6) | Dec 19, 2020 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [862b159eb2](https://linux-hardware.org/?probe=862b159eb2) | Dec 19, 2020 |
| Toshiba       | STI 910123                  | Desktop     | [f9f7a69232](https://linux-hardware.org/?probe=f9f7a69232) | Dec 18, 2020 |
| Toshiba       | STI 910123                  | Desktop     | [ae79e069f3](https://linux-hardware.org/?probe=ae79e069f3) | Dec 18, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | Desktop     | [fdc26c9f6d](https://linux-hardware.org/?probe=fdc26c9f6d) | Dec 18, 2020 |
| Exo           | Unknown                     | Notebook    | [a6c445344b](https://linux-hardware.org/?probe=a6c445344b) | Dec 17, 2020 |
| ASUSTek       | P8B75-V                     | Desktop     | [edb814f54a](https://linux-hardware.org/?probe=edb814f54a) | Dec 15, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [1b627fe180](https://linux-hardware.org/?probe=1b627fe180) | Dec 15, 2020 |
| Acer          | Aspire one                  | Notebook    | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [dc7e6d3f5d](https://linux-hardware.org/?probe=dc7e6d3f5d) | Dec 14, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [5b78a6b7ee](https://linux-hardware.org/?probe=5b78a6b7ee) | Dec 13, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [e1afb118e5](https://linux-hardware.org/?probe=e1afb118e5) | Dec 12, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [5a3c92338e](https://linux-hardware.org/?probe=5a3c92338e) | Dec 08, 2020 |
| EVGA          | 131-HE-E095                 | Desktop     | [8fca80343b](https://linux-hardware.org/?probe=8fca80343b) | Dec 08, 2020 |
| HP            | Pavilion ze2000 (EA772AV... | Notebook    | [15284f8c6e](https://linux-hardware.org/?probe=15284f8c6e) | Dec 07, 2020 |
| Dell          | Precision M4600             | Notebook    | [690e349224](https://linux-hardware.org/?probe=690e349224) | Dec 06, 2020 |
| Dell          | Precision M4600             | Notebook    | [f2023ec8ae](https://linux-hardware.org/?probe=f2023ec8ae) | Dec 06, 2020 |
| HP            | 1496                        | Desktop     | [61eeea25ed](https://linux-hardware.org/?probe=61eeea25ed) | Dec 04, 2020 |
| Acer          | Extensa 4620                | Notebook    | [1bda4268f4](https://linux-hardware.org/?probe=1bda4268f4) | Dec 04, 2020 |
| Dell          | 0XPDFK A01                  | Desktop     | [02ffa180c8](https://linux-hardware.org/?probe=02ffa180c8) | Nov 30, 2020 |
| ASRock        | X370 Taichi                 | Desktop     | [a229c68d0e](https://linux-hardware.org/?probe=a229c68d0e) | Nov 27, 2020 |
| Gigabyte      | 945GM-S2                    | Desktop     | [1bbf0f874b](https://linux-hardware.org/?probe=1bbf0f874b) | Nov 26, 2020 |
| MSI           | B85M-G43                    | Desktop     | [dee4fcacb7](https://linux-hardware.org/?probe=dee4fcacb7) | Nov 26, 2020 |
| Matsushita... | CF-19CHB23BE                | Notebook    | [a81d111827](https://linux-hardware.org/?probe=a81d111827) | Nov 25, 2020 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [1c5cc4c12e](https://linux-hardware.org/?probe=1c5cc4c12e) | Nov 25, 2020 |
| Dell          | 0F6X5P A00                  | Desktop     | [458d498ed4](https://linux-hardware.org/?probe=458d498ed4) | Nov 24, 2020 |
| ASUSTek       | X550VX                      | Notebook    | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [18d99f9e4f](https://linux-hardware.org/?probe=18d99f9e4f) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [c17dc0982c](https://linux-hardware.org/?probe=c17dc0982c) | Nov 22, 2020 |
| Lenovo        | ThinkPad T60p 8742C4G       | Notebook    | [9d369e30fd](https://linux-hardware.org/?probe=9d369e30fd) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | Notebook    | [dbac4eb570](https://linux-hardware.org/?probe=dbac4eb570) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | Notebook    | [b070b2d112](https://linux-hardware.org/?probe=b070b2d112) | Nov 18, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [c9f4c7eefd](https://linux-hardware.org/?probe=c9f4c7eefd) | Nov 16, 2020 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [c03bf04e1e](https://linux-hardware.org/?probe=c03bf04e1e) | Nov 15, 2020 |
| HP            | Unknown                     | Notebook    | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | N90SC                       | Notebook    | [219009d9ea](https://linux-hardware.org/?probe=219009d9ea) | Nov 13, 2020 |
| ASUSTek       | N90SC                       | Notebook    | [1b802fbae0](https://linux-hardware.org/?probe=1b802fbae0) | Nov 13, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| Lenovo        | ThinkPad T420s 4174EK3      | Notebook    | [256f53a883](https://linux-hardware.org/?probe=256f53a883) | Nov 08, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [3863a67ce4](https://linux-hardware.org/?probe=3863a67ce4) | Nov 07, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [80c240fcef](https://linux-hardware.org/?probe=80c240fcef) | Nov 07, 2020 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [ac476c2272](https://linux-hardware.org/?probe=ac476c2272) | Nov 05, 2020 |
| Dell          | Latitude 5400               | Notebook    | [014e9b7e76](https://linux-hardware.org/?probe=014e9b7e76) | Nov 04, 2020 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [ab7e244449](https://linux-hardware.org/?probe=ab7e244449) | Nov 03, 2020 |
| HP            | Compaq 8510p                | Notebook    | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [2fe3e165eb](https://linux-hardware.org/?probe=2fe3e165eb) | Oct 31, 2020 |
| Dell          | Latitude E6220              | Notebook    | [b3af9d8439](https://linux-hardware.org/?probe=b3af9d8439) | Oct 30, 2020 |
| Dell          | Latitude E6220              | Notebook    | [7df244c05f](https://linux-hardware.org/?probe=7df244c05f) | Oct 30, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| Dell          | 0DR845                      | Desktop     | [958876c9d6](https://linux-hardware.org/?probe=958876c9d6) | Oct 27, 2020 |
| HP            | 843B                        | Desktop     | [cf9214c9e8](https://linux-hardware.org/?probe=cf9214c9e8) | Oct 25, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [dd6fd8b99c](https://linux-hardware.org/?probe=dd6fd8b99c) | Oct 24, 2020 |
| Positivo      | DH8BW01                     | All in one  | [b8c805b52b](https://linux-hardware.org/?probe=b8c805b52b) | Oct 23, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [bc2de7b987](https://linux-hardware.org/?probe=bc2de7b987) | Oct 23, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [c637e2732a](https://linux-hardware.org/?probe=c637e2732a) | Oct 22, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [ad50a3e36d](https://linux-hardware.org/?probe=ad50a3e36d) | Oct 22, 2020 |
| Gigabyte      | G33M-S2                     | Desktop     | [d5b1adf1cc](https://linux-hardware.org/?probe=d5b1adf1cc) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [c00341fecd](https://linux-hardware.org/?probe=c00341fecd) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [83c0ae72b0](https://linux-hardware.org/?probe=83c0ae72b0) | Oct 21, 2020 |
| Unknown       | Unknown                     | Notebook    | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| MSI           | Z97 GAMING 3                | Desktop     | [d70dc5679f](https://linux-hardware.org/?probe=d70dc5679f) | Oct 15, 2020 |
| ASUSTek       | P7F-M                       | Desktop     | [a931f70b33](https://linux-hardware.org/?probe=a931f70b33) | Oct 14, 2020 |
| ASUSTek       | GL503VM                     | Notebook    | [a6705573f8](https://linux-hardware.org/?probe=a6705573f8) | Oct 11, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [27fe34d7e1](https://linux-hardware.org/?probe=27fe34d7e1) | Oct 09, 2020 |
| Acer          | Aspire 5680                 | Notebook    | [3ef4868294](https://linux-hardware.org/?probe=3ef4868294) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| HP            | 304Ah                       | Desktop     | [720e05d59c](https://linux-hardware.org/?probe=720e05d59c) | Oct 04, 2020 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | Notebook    | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| HP            | 304Ah                       | Desktop     | [e8bf5f6700](https://linux-hardware.org/?probe=e8bf5f6700) | Oct 04, 2020 |
| Dell          | 0YDJK3 A05                  | Server      | [8ebb392ed7](https://linux-hardware.org/?probe=8ebb392ed7) | Oct 03, 2020 |
| Dell          | 0YDJK3 A05                  | Server      | [825a44fd4e](https://linux-hardware.org/?probe=825a44fd4e) | Oct 03, 2020 |
| Unknown       | Unknown                     | Notebook    | [fd16de3c7f](https://linux-hardware.org/?probe=fd16de3c7f) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [7f6ed6799f](https://linux-hardware.org/?probe=7f6ed6799f) | Oct 03, 2020 |
| HP            | 304Ah                       | Desktop     | [11dc9e4238](https://linux-hardware.org/?probe=11dc9e4238) | Sep 28, 2020 |
| Positivo      | H14CU01                     | Notebook    | [3a0013a489](https://linux-hardware.org/?probe=3a0013a489) | Sep 28, 2020 |
| Positivo      | H14CU01                     | Notebook    | [e0d8261056](https://linux-hardware.org/?probe=e0d8261056) | Sep 28, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [a93a422684](https://linux-hardware.org/?probe=a93a422684) | Sep 23, 2020 |
| HP            | TouchSmart tm2              | Notebook    | [1a91d6cc06](https://linux-hardware.org/?probe=1a91d6cc06) | Sep 22, 2020 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [2def8c0128](https://linux-hardware.org/?probe=2def8c0128) | Sep 19, 2020 |
| ASUSTek       | GL503VM                     | Notebook    | [349cf8d805](https://linux-hardware.org/?probe=349cf8d805) | Sep 17, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [d2f6023c70](https://linux-hardware.org/?probe=d2f6023c70) | Sep 17, 2020 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [694576f25f](https://linux-hardware.org/?probe=694576f25f) | Sep 14, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [401a915579](https://linux-hardware.org/?probe=401a915579) | Sep 10, 2020 |
| Fujitsu       | LIFEBOOK A556/G             | Notebook    | [9484700de9](https://linux-hardware.org/?probe=9484700de9) | Sep 10, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [b200995d98](https://linux-hardware.org/?probe=b200995d98) | Sep 08, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [afcf5f7b56](https://linux-hardware.org/?probe=afcf5f7b56) | Sep 08, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | Desktop     | [e5260021d2](https://linux-hardware.org/?probe=e5260021d2) | Sep 06, 2020 |
| MSI           | FX610                       | Notebook    | [61fe175928](https://linux-hardware.org/?probe=61fe175928) | Sep 04, 2020 |
| Intel         | NUC7i7BNB J31145-309        | Mini pc     | [4b3e5c5cf9](https://linux-hardware.org/?probe=4b3e5c5cf9) | Sep 03, 2020 |
| Dell          | 0DR845                      | Desktop     | [f9dfefaf63](https://linux-hardware.org/?probe=f9dfefaf63) | Aug 31, 2020 |
| Gigabyte      | EP45C-DS3R                  | Desktop     | [3baa06afa2](https://linux-hardware.org/?probe=3baa06afa2) | Aug 24, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [2f541fa7c6](https://linux-hardware.org/?probe=2f541fa7c6) | Aug 23, 2020 |
| HP            | EliteBook 2540p             | Notebook    | [682d1b7a8c](https://linux-hardware.org/?probe=682d1b7a8c) | Aug 22, 2020 |
| Acer          | Extensa 4620                | Notebook    | [9421ec33ce](https://linux-hardware.org/?probe=9421ec33ce) | Aug 18, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Acer          | Extensa 4620                | Notebook    | [a7701181d6](https://linux-hardware.org/?probe=a7701181d6) | Aug 17, 2020 |
| ECS           | KAM1-I                      | Desktop     | [cef51c9cd7](https://linux-hardware.org/?probe=cef51c9cd7) | Aug 15, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| MSI           | D2414 S26361-D2414-A10      | Desktop     | [a0ea23eae8](https://linux-hardware.org/?probe=a0ea23eae8) | Aug 10, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2a8cc9f92c](https://linux-hardware.org/?probe=2a8cc9f92c) | Aug 04, 2020 |
| Unknown       | P4M800Pro-8237              | Desktop     | [e632211d18](https://linux-hardware.org/?probe=e632211d18) | Aug 04, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [05331a0b70](https://linux-hardware.org/?probe=05331a0b70) | Aug 04, 2020 |
| Intel         | DG33FB AAD81072-309         | Desktop     | [217bfd48bd](https://linux-hardware.org/?probe=217bfd48bd) | Aug 04, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| Dell          | 0DR845                      | Desktop     | [a70d949ebc](https://linux-hardware.org/?probe=a70d949ebc) | Jul 30, 2020 |
| Lenovo        | ThinkCentre M90z 2471W18    | All in one  | [03b15c1544](https://linux-hardware.org/?probe=03b15c1544) | Jul 21, 2020 |
| Positivo      | W310CZ-T                    | Notebook    | [0a1a913ef9](https://linux-hardware.org/?probe=0a1a913ef9) | Jul 19, 2020 |
| Acer          | Aspire 1640                 | Notebook    | [187a648c68](https://linux-hardware.org/?probe=187a648c68) | Jul 16, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [4af42f19bb](https://linux-hardware.org/?probe=4af42f19bb) | Jul 14, 2020 |
| Lenovo        | ThinkPad T61 6457W9X        | Notebook    | [ccd11debcb](https://linux-hardware.org/?probe=ccd11debcb) | Jul 11, 2020 |
| HP            | 3396                        | Desktop     | [53167bce1a](https://linux-hardware.org/?probe=53167bce1a) | Jul 09, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [ea27ca7285](https://linux-hardware.org/?probe=ea27ca7285) | Jul 01, 2020 |
| ASUSTek       | E402SA                      | Notebook    | [46b87025ae](https://linux-hardware.org/?probe=46b87025ae) | Jul 01, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [1f45c104e4](https://linux-hardware.org/?probe=1f45c104e4) | Jun 26, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [5613253a47](https://linux-hardware.org/?probe=5613253a47) | Jun 26, 2020 |
| ASUSTek       | G11DF                       | Desktop     | [73ddfc32aa](https://linux-hardware.org/?probe=73ddfc32aa) | Jun 23, 2020 |
| ASUSTek       | G11DF                       | Desktop     | [497ebd9b60](https://linux-hardware.org/?probe=497ebd9b60) | Jun 23, 2020 |
| Toshiba       | All In One PC MP            | All in one  | [b2175e7054](https://linux-hardware.org/?probe=b2175e7054) | Jun 21, 2020 |
| Biostar       | NF61S-M2A                   | Desktop     | [c071fa24d8](https://linux-hardware.org/?probe=c071fa24d8) | Jun 21, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dc82478114](https://linux-hardware.org/?probe=dc82478114) | Jun 21, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a2c192906d](https://linux-hardware.org/?probe=a2c192906d) | Jun 21, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [8c0a32e7f4](https://linux-hardware.org/?probe=8c0a32e7f4) | Jun 19, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [8ed5aa8505](https://linux-hardware.org/?probe=8ed5aa8505) | Jun 19, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | Notebook    | [012f3cadc0](https://linux-hardware.org/?probe=012f3cadc0) | Jun 16, 2020 |
| ASUSTek       | K50C                        | Notebook    | [1d98006287](https://linux-hardware.org/?probe=1d98006287) | Jun 15, 2020 |
| ASUSTek       | K50C                        | Notebook    | [141d18f0ca](https://linux-hardware.org/?probe=141d18f0ca) | Jun 15, 2020 |
| HP            | 350 G2                      | Notebook    | [ac2b06957f](https://linux-hardware.org/?probe=ac2b06957f) | Jun 11, 2020 |
| PCWare        | IPMH81G1                    | Desktop     | [416c3e2997](https://linux-hardware.org/?probe=416c3e2997) | Jun 07, 2020 |
| Toshiba       | All In One PC MP            | All in one  | [7a08b12375](https://linux-hardware.org/?probe=7a08b12375) | Jun 04, 2020 |
| ASUSTek       | 1005PX                      | Notebook    | [8d5b0aa8df](https://linux-hardware.org/?probe=8d5b0aa8df) | Jun 03, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [aebb17da40](https://linux-hardware.org/?probe=aebb17da40) | Jun 01, 2020 |
| Sony          | VGN-AW41MF_H                | Notebook    | [baf800f176](https://linux-hardware.org/?probe=baf800f176) | May 29, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [f4679ca184](https://linux-hardware.org/?probe=f4679ca184) | May 29, 2020 |
| HP            | 8430 1000                   | All in one  | [c05bc25888](https://linux-hardware.org/?probe=c05bc25888) | May 29, 2020 |
| HP            | 8430 1000                   | All in one  | [f7df6a95b7](https://linux-hardware.org/?probe=f7df6a95b7) | May 29, 2020 |
| Dell          | 0DR845                      | Desktop     | [4b8a511c08](https://linux-hardware.org/?probe=4b8a511c08) | May 29, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [4fb041418f](https://linux-hardware.org/?probe=4fb041418f) | May 29, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [b36f5a9ddf](https://linux-hardware.org/?probe=b36f5a9ddf) | May 28, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [7f22ac48a8](https://linux-hardware.org/?probe=7f22ac48a8) | May 26, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [be86e3ea15](https://linux-hardware.org/?probe=be86e3ea15) | May 26, 2020 |
| HP            | Presario CQ61               | Notebook    | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Acer          | Aspire 7551                 | Notebook    | [d9c150f3ee](https://linux-hardware.org/?probe=d9c150f3ee) | May 24, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [aca1fb8ea1](https://linux-hardware.org/?probe=aca1fb8ea1) | May 21, 2020 |
| Acer          | Aspire 4830T                | Notebook    | [5494761310](https://linux-hardware.org/?probe=5494761310) | May 20, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [9c46a8ee24](https://linux-hardware.org/?probe=9c46a8ee24) | May 20, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [b7665aa8e1](https://linux-hardware.org/?probe=b7665aa8e1) | May 20, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [8e547a1414](https://linux-hardware.org/?probe=8e547a1414) | May 20, 2020 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [cf5fe3dbce](https://linux-hardware.org/?probe=cf5fe3dbce) | May 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [4d4f673fb2](https://linux-hardware.org/?probe=4d4f673fb2) | May 16, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| Dell          | G3 3590                     | Notebook    | [6b37af517b](https://linux-hardware.org/?probe=6b37af517b) | May 12, 2020 |
| Toshiba       | Satellite U300              | Notebook    | [ef95fa82d7](https://linux-hardware.org/?probe=ef95fa82d7) | May 11, 2020 |
| HP            | G61                         | Notebook    | [7393752623](https://linux-hardware.org/?probe=7393752623) | May 11, 2020 |
| ASRock        | B75M R2.0                   | Desktop     | [efd3354b61](https://linux-hardware.org/?probe=efd3354b61) | May 10, 2020 |
| Dell          | Latitude E5570              | Notebook    | [1c8dda10a4](https://linux-hardware.org/?probe=1c8dda10a4) | May 08, 2020 |
| Dell          | Latitude E5570              | Notebook    | [20fc42be1b](https://linux-hardware.org/?probe=20fc42be1b) | May 06, 2020 |
| Dell          | System Inspiron N411Z       | Notebook    | [246dd5ce2a](https://linux-hardware.org/?probe=246dd5ce2a) | May 05, 2020 |
| Dell          | Latitude E5570              | Notebook    | [a1b049e54c](https://linux-hardware.org/?probe=a1b049e54c) | May 05, 2020 |
| Toshiba       | Satellite U300              | Notebook    | [3bd62e1a59](https://linux-hardware.org/?probe=3bd62e1a59) | May 05, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [1a79fa9925](https://linux-hardware.org/?probe=1a79fa9925) | May 03, 2020 |
| HP            | Laptop 15-bs2xx             | Notebook    | [6d47f83eac](https://linux-hardware.org/?probe=6d47f83eac) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [154605446a](https://linux-hardware.org/?probe=154605446a) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [e9544d771b](https://linux-hardware.org/?probe=e9544d771b) | May 02, 2020 |
| HP            | G42                         | Notebook    | [be1ea8571f](https://linux-hardware.org/?probe=be1ea8571f) | Apr 28, 2020 |
| Lenovo        | ThinkPad E490 20N80017RT    | Notebook    | [7f84d5a0f2](https://linux-hardware.org/?probe=7f84d5a0f2) | Apr 28, 2020 |
| HP            | G42                         | Notebook    | [8ea8320eac](https://linux-hardware.org/?probe=8ea8320eac) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| Acer          | Aspire E1-572               | Notebook    | [e64e2fe71c](https://linux-hardware.org/?probe=e64e2fe71c) | Apr 23, 2020 |
| ASRock        | J4205-ITX                   | Desktop     | [4fc5d5a325](https://linux-hardware.org/?probe=4fc5d5a325) | Apr 22, 2020 |
| ECS           | Nettle2                     | Desktop     | [ababaf523c](https://linux-hardware.org/?probe=ababaf523c) | Apr 19, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [12c198a6f5](https://linux-hardware.org/?probe=12c198a6f5) | Apr 18, 2020 |
| HP            | Laptop 15-bs2xx             | Notebook    | [477c5d9ffa](https://linux-hardware.org/?probe=477c5d9ffa) | Apr 17, 2020 |
| Positivo      | Mobile                      | Notebook    | [c7cc7cd357](https://linux-hardware.org/?probe=c7cc7cd357) | Apr 17, 2020 |
| Positivo      | Mobile                      | Notebook    | [55b84972df](https://linux-hardware.org/?probe=55b84972df) | Apr 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [4d06bdc501](https://linux-hardware.org/?probe=4d06bdc501) | Apr 14, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [67167458d8](https://linux-hardware.org/?probe=67167458d8) | Apr 14, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [0d1b40e847](https://linux-hardware.org/?probe=0d1b40e847) | Apr 14, 2020 |
| Acer          | Aspire E1-572               | Notebook    | [941e12751c](https://linux-hardware.org/?probe=941e12751c) | Apr 14, 2020 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [3cc8e9e496](https://linux-hardware.org/?probe=3cc8e9e496) | Apr 12, 2020 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [8822c3378d](https://linux-hardware.org/?probe=8822c3378d) | Apr 12, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| HP            | 8526 MVB, A                 | Desktop     | [30e90998e1](https://linux-hardware.org/?probe=30e90998e1) | Apr 08, 2020 |
| Dell          | Latitude E6510              | Notebook    | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [93b28f5a7c](https://linux-hardware.org/?probe=93b28f5a7c) | Apr 03, 2020 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [3251d5e710](https://linux-hardware.org/?probe=3251d5e710) | Apr 03, 2020 |
| Dell          | Latitude D610               | Notebook    | [44901c9eb2](https://linux-hardware.org/?probe=44901c9eb2) | Mar 30, 2020 |
| Dell          | Latitude D610               | Notebook    | [5bfecb6e64](https://linux-hardware.org/?probe=5bfecb6e64) | Mar 30, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [e710551f70](https://linux-hardware.org/?probe=e710551f70) | Mar 29, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [336b94c4dc](https://linux-hardware.org/?probe=336b94c4dc) | Mar 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b660991573](https://linux-hardware.org/?probe=b660991573) | Mar 29, 2020 |
| MSI           | G31M2                       | Desktop     | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
| Acer          | Aspire TC-605               | Desktop     | [495fffaa63](https://linux-hardware.org/?probe=495fffaa63) | Mar 26, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [fb006f397c](https://linux-hardware.org/?probe=fb006f397c) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | Desktop     | [5c7e0a86df](https://linux-hardware.org/?probe=5c7e0a86df) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | Desktop     | [c6a5cf98ee](https://linux-hardware.org/?probe=c6a5cf98ee) | Mar 24, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [0c52aebe31](https://linux-hardware.org/?probe=0c52aebe31) | Mar 23, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [5055c4067a](https://linux-hardware.org/?probe=5055c4067a) | Mar 20, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/LMDE_4/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 4.19.0-8-amd64       | 45        | 10.44%  |
| 4.19.0-18-amd64      | 45        | 10.44%  |
| 4.19.0-17-amd64      | 41        | 9.51%   |
| 4.19.0-16-amd64      | 40        | 9.28%   |
| 4.19.0-14-amd64      | 31        | 7.19%   |
| 4.19.0-13-amd64      | 30        | 6.96%   |
| 4.19.0-9-amd64       | 29        | 6.73%   |
| 4.19.0-10-amd64      | 20        | 4.64%   |
| 4.19.0-12-amd64      | 19        | 4.41%   |
| 4.19.0-8-686         | 17        | 3.94%   |
| 4.19.0-17-686        | 17        | 3.94%   |
| 4.19.0-16-686        | 14        | 3.25%   |
| 4.19.0-18-686        | 12        | 2.78%   |
| 4.19.0-11-amd64      | 11        | 2.55%   |
| 4.19.0-13-686        | 9         | 2.09%   |
| 4.19.0-14-686        | 6         | 1.39%   |
| 4.19.0-12-686        | 6         | 1.39%   |
| 4.19.0-19-686        | 5         | 1.16%   |
| 5.4.0-0.bpo.4-amd64  | 3         | 0.7%    |
| 4.19.0-20-amd64      | 3         | 0.7%    |
| 5.15.59-xanmod1      | 2         | 0.46%   |
| 5.10.0-0.bpo.5-amd64 | 2         | 0.46%   |
| 4.19.0-9-686         | 2         | 0.46%   |
| 4.19.0-21-amd64      | 2         | 0.46%   |
| 5.9.12-davius        | 1         | 0.23%   |
| 5.9.0-0.bpo.5-amd64  | 1         | 0.23%   |
| 5.8.0-3-amd64        | 1         | 0.23%   |
| 5.8.0-0.bpo.2-amd64  | 1         | 0.23%   |
| 5.6.0-2-amd64        | 1         | 0.23%   |
| 5.6.0-2-686-pae      | 1         | 0.23%   |
| 5.6.0-0.bpo.2-amd64  | 1         | 0.23%   |
| 5.4.44-xanmod1       | 1         | 0.23%   |
| 5.15.64-xanmod1      | 1         | 0.23%   |
| 5.15.56-xanmod1      | 1         | 0.23%   |
| 5.15.0-kali2-amd64   | 1         | 0.23%   |
| 5.10.0-7-amd64       | 1         | 0.23%   |
| 5.10.0-0.bpo.9-amd64 | 1         | 0.23%   |
| 5.10.0-0.bpo.3-amd64 | 1         | 0.23%   |
| 4.19.0-21-686        | 1         | 0.23%   |
| 4.19.0-20-686        | 1         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19.0  | 369       | 94.62%  |
| 5.10.0  | 5         | 1.28%   |
| 5.6.0   | 3         | 0.77%   |
| 5.4.0   | 3         | 0.77%   |
| 5.8.0   | 2         | 0.51%   |
| 5.15.59 | 2         | 0.51%   |
| 5.9.12  | 1         | 0.26%   |
| 5.9.0   | 1         | 0.26%   |
| 5.4.44  | 1         | 0.26%   |
| 5.15.64 | 1         | 0.26%   |
| 5.15.56 | 1         | 0.26%   |
| 5.15.0  | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 369       | 94.86%  |
| 5.10    | 5         | 1.29%   |
| 5.4     | 4         | 1.03%   |
| 5.15    | 4         | 1.03%   |
| 5.6     | 3         | 0.77%   |
| 5.9     | 2         | 0.51%   |
| 5.8     | 2         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 299       | 77.26%  |
| i686   | 88        | 22.74%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 354       | 90.31%  |
| Cinnamon   | 17        | 4.34%   |
| Unknown    | 7         | 1.79%   |
| MATE       | 6         | 1.53%   |
| XFCE       | 2         | 0.51%   |
| LXDE       | 2         | 0.51%   |
| Trinity    | 1         | 0.26%   |
| LXQt       | 1         | 0.26%   |
| KDE        | 1         | 0.26%   |
| GNOME      | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 387       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 347       | 89.43%  |
| TDM     | 20        | 5.15%   |
| LightDM | 19        | 4.9%    |
| GDM3    | 1         | 0.26%   |
| GDM     | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 110       | 28.21%  |
| pt_BR  | 41        | 10.51%  |
| de_DE  | 41        | 10.51%  |
| ru_RU  | 18        | 4.62%   |
| fr_FR  | 17        | 4.36%   |
| en_GB  | 17        | 4.36%   |
| pl_PL  | 16        | 4.1%    |
| it_IT  | 11        | 2.82%   |
| es_ES  | 11        | 2.82%   |
| es_AR  | 9         | 2.31%   |
| en_CA  | 9         | 2.31%   |
| en_AU  | 9         | 2.31%   |
| es_MX  | 6         | 1.54%   |
| de_CH  | 5         | 1.28%   |
| nl_BE  | 4         | 1.03%   |
| el_GR  | 4         | 1.03%   |
| sv_SE  | 3         | 0.77%   |
| pt_PT  | 3         | 0.77%   |
| nl_NL  | 3         | 0.77%   |
| ja_JP  | 3         | 0.77%   |
| en_ZA  | 3         | 0.77%   |
| de_AT  | 3         | 0.77%   |
| cs_CZ  | 3         | 0.77%   |
| bg_BG  | 3         | 0.77%   |
| unm_US | 2         | 0.51%   |
| uk_UA  | 2         | 0.51%   |
| tr_TR  | 2         | 0.51%   |
| sk_SK  | 2         | 0.51%   |
| hu_HU  | 2         | 0.51%   |
| et_EE  | 2         | 0.51%   |
| es_EC  | 2         | 0.51%   |
| es_CL  | 2         | 0.51%   |
| en_PH  | 2         | 0.51%   |
| en_IN  | 2         | 0.51%   |
| ca_ES  | 2         | 0.51%   |
| zh_CN  | 1         | 0.26%   |
| ru_UA  | 1         | 0.26%   |
| ro_RO  | 1         | 0.26%   |
| nb_NO  | 1         | 0.26%   |
| it_CH  | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 275       | 70.69%  |
| EFI  | 114       | 29.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 373       | 96.13%  |
| Btrfs   | 8         | 2.06%   |
| Tmpfs   | 3         | 0.77%   |
| Unknown | 2         | 0.52%   |
| Overlay | 1         | 0.26%   |
| Ext3    | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 342       | 87.92%  |
| GPT     | 28        | 7.2%    |
| MBR     | 19        | 4.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 371       | 95.37%  |
| Yes       | 18        | 4.63%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 370       | 95.61%  |
| Yes       | 17        | 4.39%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 63        | 16.28%  |
| ASUSTek Computer               | 62        | 16.02%  |
| Dell                           | 43        | 11.11%  |
| Acer                           | 34        | 8.79%   |
| Lenovo                         | 32        | 8.27%   |
| Gigabyte Technology            | 21        | 5.43%   |
| MSI                            | 20        | 5.17%   |
| ASRock                         | 12        | 3.1%    |
| Toshiba                        | 10        | 2.58%   |
| Samsung Electronics            | 7         | 1.81%   |
| Unknown                        | 7         | 1.81%   |
| Intel                          | 6         | 1.55%   |
| Fujitsu Siemens                | 6         | 1.55%   |
| Sony                           | 5         | 1.29%   |
| Positivo                       | 5         | 1.29%   |
| LG Electronics                 | 4         | 1.03%   |
| ECS                            | 4         | 1.03%   |
| Apple                          | 3         | 0.78%   |
| Semp Toshiba                   | 2         | 0.52%   |
| Pegatron                       | 2         | 0.52%   |
| Packard Bell                   | 2         | 0.52%   |
| OEM                            | 2         | 0.52%   |
| Matsushita Electric Industrial | 2         | 0.52%   |
| Gateway                        | 2         | 0.52%   |
| Fujitsu                        | 2         | 0.52%   |
| Foxconn                        | 2         | 0.52%   |
| EVGA                           | 2         | 0.52%   |
| Biostar                        | 2         | 0.52%   |
| Wistron                        | 1         | 0.26%   |
| TUXEDO                         | 1         | 0.26%   |
| Supermicro                     | 1         | 0.26%   |
| SAELITE                        | 1         | 0.26%   |
| Qbex                           | 1         | 0.26%   |
| PCWare                         | 1         | 0.26%   |
| Notebook                       | 1         | 0.26%   |
| NEC Computers                  | 1         | 0.26%   |
| Microsoft                      | 1         | 0.26%   |
| Medion                         | 1         | 0.26%   |
| Maibenben                      | 1         | 0.26%   |
| Itautec                        | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 12        | 3.1%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 3         | 0.78%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 2         | 0.52%   |
| HP Pavilion dv6                             | 2         | 0.52%   |
| HP Notebook                                 | 2         | 0.52%   |
| HP EliteBook 8540w                          | 2         | 0.52%   |
| Dell OptiPlex 780                           | 2         | 0.52%   |
| ASUS X101CH                                 | 2         | 0.52%   |
| ASUS All Series                             | 2         | 0.52%   |
| Acer Aspire 5735                            | 2         | 0.52%   |
| Acer Aspire 3000                            | 2         | 0.52%   |
| Acer AOD270                                 | 2         | 0.52%   |
| Wistron ProLiant ML110 G5                   | 1         | 0.26%   |
| TUXEDO BC1510 1710                          | 1         | 0.26%   |
| Toshiba Satellite U300                      | 1         | 0.26%   |
| Toshiba Satellite P300                      | 1         | 0.26%   |
| Toshiba Satellite M100                      | 1         | 0.26%   |
| Toshiba Satellite L855                      | 1         | 0.26%   |
| Toshiba Satellite L750                      | 1         | 0.26%   |
| Toshiba Satellite L50-C                     | 1         | 0.26%   |
| Toshiba Satellite C50-A-1DN                 | 1         | 0.26%   |
| Toshiba Satellite A200                      | 1         | 0.26%   |
| Toshiba LX835                               | 1         | 0.26%   |
| Toshiba dynabook Satellite J61 173C/5       | 1         | 0.26%   |
| Supermicro X8DT3                            | 1         | 0.26%   |
| Sony VPCS131FM                              | 1         | 0.26%   |
| Sony VPCP116KG                              | 1         | 0.26%   |
| Sony VGN-FZ140E                             | 1         | 0.26%   |
| Sony VGN-AW41MF_H                           | 1         | 0.26%   |
| Sony SVE1511N1ESI                           | 1         | 0.26%   |
| Semp Toshiba STI                            | 1         | 0.26%   |
| Semp Toshiba NI 1403                        | 1         | 0.26%   |
| Samsung RV413/RV513                         | 1         | 0.26%   |
| Samsung R59/R60/R61                         | 1         | 0.26%   |
| Samsung NC10                                | 1         | 0.26%   |
| Samsung 305U1A                              | 1         | 0.26%   |
| SAELITE ES1AU11                             | 1         | 0.26%   |
| Qbex UDPAIOQBEX01                           | 1         | 0.26%   |
| Positivo W310CZ-T                           | 1         | 0.26%   |
| Positivo POS-EIH61CE                        | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 26        | 6.72%   |
| Lenovo ThinkPad         | 14        | 3.62%   |
| HP Pavilion             | 12        | 3.1%    |
| Dell Latitude           | 12        | 3.1%    |
| Dell Inspiron           | 12        | 3.1%    |
| Unknown                 | 12        | 3.1%    |
| HP Compaq               | 11        | 2.84%   |
| HP Laptop               | 9         | 2.33%   |
| Dell OptiPlex           | 9         | 2.33%   |
| Toshiba Satellite       | 8         | 2.07%   |
| Lenovo IdeaPad          | 7         | 1.81%   |
| HP EliteBook            | 5         | 1.29%   |
| Dell Precision          | 5         | 1.29%   |
| ASUS PRIME              | 4         | 1.03%   |
| Samsung RV411           | 3         | 0.78%   |
| Gigabyte X570           | 3         | 0.78%   |
| Fujitsu Siemens ESPRIMO | 3         | 0.78%   |
| Packard Bell EasyNote   | 2         | 0.52%   |
| Lenovo ThinkCentre      | 2         | 0.52%   |
| HP ProBook              | 2         | 0.52%   |
| HP Presario             | 2         | 0.52%   |
| HP Notebook             | 2         | 0.52%   |
| Gigabyte Z390           | 2         | 0.52%   |
| Dell System             | 2         | 0.52%   |
| ASUS X101CH             | 2         | 0.52%   |
| ASUS ROG                | 2         | 0.52%   |
| ASUS P5KPL-AM           | 2         | 0.52%   |
| ASUS All                | 2         | 0.52%   |
| Apple MacBookPro5       | 2         | 0.52%   |
| Acer Veriton            | 2         | 0.52%   |
| Acer Swift              | 2         | 0.52%   |
| Acer AOD270             | 2         | 0.52%   |
| Wistron ProLiant        | 1         | 0.26%   |
| TUXEDO BC1510           | 1         | 0.26%   |
| Toshiba LX835           | 1         | 0.26%   |
| Toshiba dynabook        | 1         | 0.26%   |
| Supermicro X8DT3        | 1         | 0.26%   |
| Sony VPCS131FM          | 1         | 0.26%   |
| Sony VPCP116KG          | 1         | 0.26%   |
| Sony VGN-FZ140E         | 1         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 40        | 10.34%  |
| 2009    | 38        | 9.82%   |
| 2011    | 33        | 8.53%   |
| 2010    | 32        | 8.27%   |
| 2007    | 32        | 8.27%   |
| 2018    | 29        | 7.49%   |
| 2008    | 29        | 7.49%   |
| 2014    | 25        | 6.46%   |
| 2013    | 23        | 5.94%   |
| 2019    | 20        | 5.17%   |
| 2006    | 16        | 4.13%   |
| 2016    | 13        | 3.36%   |
| 2020    | 12        | 3.1%    |
| 2017    | 12        | 3.1%    |
| 2015    | 12        | 3.1%    |
| 2005    | 10        | 2.58%   |
| 2003    | 5         | 1.29%   |
| 2021    | 2         | 0.52%   |
| 2004    | 2         | 0.52%   |
| 2002    | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 223       | 57.62%  |
| Desktop     | 148       | 38.24%  |
| All in one  | 6         | 1.55%   |
| Tablet      | 3         | 0.78%   |
| Convertible | 3         | 0.78%   |
| Server      | 3         | 0.78%   |
| Mini pc     | 1         | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 375       | 96.4%   |
| Enabled  | 14        | 3.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 386       | 99.74%  |
| Yes  | 1         | 0.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 107       | 27.37%  |
| 4.01-8.0    | 61        | 15.6%   |
| 8.01-16.0   | 55        | 14.07%  |
| 2.01-3.0    | 52        | 13.3%   |
| 16.01-24.0  | 50        | 12.79%  |
| 1.01-2.0    | 35        | 8.95%   |
| 0.51-1.0    | 14        | 3.58%   |
| 32.01-64.0  | 13        | 3.32%   |
| 24.01-32.0  | 2         | 0.51%   |
| 64.01-256.0 | 2         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 207       | 49.88%  |
| 0.51-1.0  | 76        | 18.31%  |
| 2.01-3.0  | 73        | 17.59%  |
| 3.01-4.0  | 38        | 9.16%   |
| 4.01-8.0  | 15        | 3.61%   |
| 8.01-16.0 | 3         | 0.72%   |
| 0.01-0.5  | 3         | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 241       | 60.55%  |
| 2      | 104       | 26.13%  |
| 3      | 24        | 6.03%   |
| 4      | 13        | 3.27%   |
| 7      | 5         | 1.26%   |
| 0      | 5         | 1.26%   |
| 5      | 3         | 0.75%   |
| 6      | 2         | 0.5%    |
| 8      | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 231       | 58.78%  |
| No        | 162       | 41.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 369       | 95.35%  |
| No        | 18        | 4.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 291       | 74.23%  |
| No        | 101       | 25.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 227       | 58.51%  |
| Yes       | 161       | 41.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 50        | 12.92%  |
| Germany      | 46        | 11.89%  |
| Brazil       | 42        | 10.85%  |
| France       | 17        | 4.39%   |
| UK           | 14        | 3.62%   |
| Russia       | 14        | 3.62%   |
| Poland       | 14        | 3.62%   |
| Canada       | 13        | 3.36%   |
| Italy        | 12        | 3.1%    |
| Spain        | 11        | 2.84%   |
| Netherlands  | 11        | 2.84%   |
| Bulgaria     | 9         | 2.33%   |
| Australia    | 9         | 2.33%   |
| Argentina    | 9         | 2.33%   |
| Ukraine      | 8         | 2.07%   |
| Switzerland  | 7         | 1.81%   |
| Mexico       | 7         | 1.81%   |
| Greece       | 5         | 1.29%   |
| Austria      | 5         | 1.29%   |
| Turkey       | 4         | 1.03%   |
| Portugal     | 4         | 1.03%   |
| Philippines  | 4         | 1.03%   |
| India        | 4         | 1.03%   |
| Ecuador      | 4         | 1.03%   |
| Belgium      | 4         | 1.03%   |
| Sweden       | 3         | 0.78%   |
| South Africa | 3         | 0.78%   |
| Romania      | 3         | 0.78%   |
| Indonesia    | 3         | 0.78%   |
| Czechia      | 3         | 0.78%   |
| Belarus      | 3         | 0.78%   |
| Bahrain      | 3         | 0.78%   |
| Tunisia      | 2         | 0.52%   |
| Puerto Rico  | 2         | 0.52%   |
| Luxembourg   | 2         | 0.52%   |
| Japan        | 2         | 0.52%   |
| Hungary      | 2         | 0.52%   |
| Finland      | 2         | 0.52%   |
| Estonia      | 2         | 0.52%   |
| Egypt        | 2         | 0.52%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 5         | 1.22%   |
| Sofia             | 4         | 0.98%   |
| Poznan            | 4         | 0.98%   |
| Perth             | 4         | 0.98%   |
| Paris             | 4         | 0.98%   |
| Athens            | 4         | 0.98%   |
| Wroclaw           | 3         | 0.73%   |
| Wohlen            | 3         | 0.73%   |
| St Petersburg     | 3         | 0.73%   |
| Seville           | 3         | 0.73%   |
| Rio de Janeiro    | 3         | 0.73%   |
| Manama            | 3         | 0.73%   |
| Hamburg           | 3         | 0.73%   |
| Guayaquil         | 3         | 0.73%   |
| Frankfurt am Main | 3         | 0.73%   |
| Florianópolis    | 3         | 0.73%   |
| Zurich            | 2         | 0.49%   |
| Warsaw            | 2         | 0.49%   |
| Victoria          | 2         | 0.49%   |
| The Hague         | 2         | 0.49%   |
| Stuttgart         | 2         | 0.49%   |
| Stockholm         | 2         | 0.49%   |
| Sao Luís         | 2         | 0.49%   |
| Santa Rosa        | 2         | 0.49%   |
| Rho               | 2         | 0.49%   |
| Rapla             | 2         | 0.49%   |
| Pokrovske         | 2         | 0.49%   |
| Plovdiv           | 2         | 0.49%   |
| Oxford            | 2         | 0.49%   |
| Moscow            | 2         | 0.49%   |
| Montreal          | 2         | 0.49%   |
| Milan             | 2         | 0.49%   |
| Marburg           | 2         | 0.49%   |
| Kazanlak          | 2         | 0.49%   |
| Karlsruhe         | 2         | 0.49%   |
| Helsinki          | 2         | 0.49%   |
| Glasgow           | 2         | 0.49%   |
| Foz do Iguaçu    | 2         | 0.49%   |
| Duisburg          | 2         | 0.49%   |
| Dhaka             | 2         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 104       | 151    | 19.29%  |
| Seagate             | 86        | 131    | 15.96%  |
| Samsung Electronics | 78        | 101    | 14.47%  |
| Toshiba             | 33        | 40     | 6.12%   |
| Hitachi             | 31        | 34     | 5.75%   |
| Kingston            | 26        | 31     | 4.82%   |
| Unknown             | 22        | 25     | 4.08%   |
| SanDisk             | 18        | 25     | 3.34%   |
| Crucial             | 17        | 21     | 3.15%   |
| Intel               | 11        | 12     | 2.04%   |
| HGST                | 11        | 12     | 2.04%   |
| Phison              | 8         | 10     | 1.48%   |
| Fujitsu             | 8         | 8      | 1.48%   |
| A-DATA Technology   | 8         | 8      | 1.48%   |
| China               | 7         | 7      | 1.3%    |
| SK hynix            | 5         | 7      | 0.93%   |
| Intenso             | 5         | 6      | 0.93%   |
| Transcend           | 4         | 5      | 0.74%   |
| Micron Technology   | 4         | 4      | 0.74%   |
| Patriot             | 3         | 4      | 0.56%   |
| OCZ                 | 3         | 5      | 0.56%   |
| Maxtor              | 3         | 5      | 0.56%   |
| KingSpec            | 3         | 4      | 0.56%   |
| KingDian            | 3         | 4      | 0.56%   |
| GOODRAM             | 3         | 3      | 0.56%   |
| Gigabyte Technology | 3         | 4      | 0.56%   |
| TCSUNBOW            | 2         | 2      | 0.37%   |
| Mushkin             | 2         | 2      | 0.37%   |
| IBM/Hitachi         | 2         | 2      | 0.37%   |
| Hewlett-Packard     | 2         | 3      | 0.37%   |
| CT500MX5            | 2         | 2      | 0.37%   |
| USB30               | 1         | 2      | 0.19%   |
| Team                | 1         | 2      | 0.19%   |
| Silicon Motion      | 1         | 1      | 0.19%   |
| SABRENT             | 1         | 1      | 0.19%   |
| PNY                 | 1         | 1      | 0.19%   |
| Netac               | 1         | 1      | 0.19%   |
| Kingmax             | 1         | 1      | 0.19%   |
| KESU                | 1         | 2      | 0.19%   |
| JMicron Technology  | 1         | 2      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 9         | 1.53%   |
| Unknown MMC Card  32GB               | 5         | 0.85%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 0.85%   |
| Kingston SA400S37240G 240GB SSD      | 5         | 0.85%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 4         | 0.68%   |
| Unknown MMC Card  7GB                | 4         | 0.68%   |
| Toshiba MQ01ABD100 1TB               | 4         | 0.68%   |
| Toshiba DT01ACA100 1TB               | 4         | 0.68%   |
| Seagate ST1000DM010-2EP102 1TB       | 4         | 0.68%   |
| Seagate Expansion 4TB                | 4         | 0.68%   |
| Samsung SSD 860 EVO 1TB              | 4         | 0.68%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.68%   |
| Samsung SSD 850 EVO 250GB            | 4         | 0.68%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.68%   |
| Kingston SA400S37120G 120GB SSD      | 4         | 0.68%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.68%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.51%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 3         | 0.51%   |
| Unknown SD/MMC/MS PRO 64GB           | 3         | 0.51%   |
| Unknown MMC Card  128GB              | 3         | 0.51%   |
| Toshiba MQ01ABF050 500GB             | 3         | 0.51%   |
| Seagate ST9500325AS 500GB            | 3         | 0.51%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.51%   |
| Samsung HD322HJ 320GB                | 3         | 0.51%   |
| Samsung HD161HJ 160GB                | 3         | 0.51%   |
| Samsung HD103SJ 1TB                  | 3         | 0.51%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 3         | 0.51%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 0.51%   |
| Hitachi HTS545032B9A300 320GB        | 3         | 0.51%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 3         | 0.51%   |
| China SATA SSD 120GB                 | 3         | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.34%   |
| WDC WD7500BPVT-75HXZT3 752GB         | 2         | 0.34%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 2         | 0.34%   |
| WDC WD5000AAKX-00U6AA0 500GB         | 2         | 0.34%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 0.34%   |
| WDC WD3200AAKS-00L9A0 320GB          | 2         | 0.34%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 2         | 0.34%   |
| WDC WD2500AAKX-753CA1 250GB          | 2         | 0.34%   |
| WDC WD1600AABS-00PRA0 160GB          | 2         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 92        | 137    | 31.51%  |
| Seagate             | 85        | 129    | 29.11%  |
| Hitachi             | 31        | 34     | 10.62%  |
| Toshiba             | 27        | 30     | 9.25%   |
| Samsung Electronics | 26        | 34     | 8.9%    |
| HGST                | 11        | 12     | 3.77%   |
| Fujitsu             | 8         | 8      | 2.74%   |
| Unknown             | 3         | 3      | 1.03%   |
| Maxtor              | 3         | 5      | 1.03%   |
| IBM/Hitachi         | 2         | 2      | 0.68%   |
| KESU                | 1         | 2      | 0.34%   |
| HPE                 | 1         | 4      | 0.34%   |
| ExcelStor           | 1         | 1      | 0.34%   |
| DAS                 | 1         | 4      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 53     | 23.2%   |
| Kingston            | 24        | 29     | 12.37%  |
| Crucial             | 17        | 21     | 8.76%   |
| SanDisk             | 15        | 22     | 7.73%   |
| WDC                 | 12        | 12     | 6.19%   |
| A-DATA Technology   | 8         | 8      | 4.12%   |
| Intel               | 7         | 7      | 3.61%   |
| Toshiba             | 6         | 10     | 3.09%   |
| China               | 6         | 6      | 3.09%   |
| Transcend           | 4         | 5      | 2.06%   |
| Micron Technology   | 4         | 4      | 2.06%   |
| Intenso             | 4         | 5      | 2.06%   |
| Patriot             | 3         | 4      | 1.55%   |
| OCZ                 | 3         | 5      | 1.55%   |
| KingDian            | 3         | 4      | 1.55%   |
| GOODRAM             | 3         | 3      | 1.55%   |
| Gigabyte Technology | 3         | 4      | 1.55%   |
| Unknown             | 2         | 2      | 1.03%   |
| TCSUNBOW            | 2         | 2      | 1.03%   |
| SK hynix            | 2         | 3      | 1.03%   |
| KingSpec            | 2         | 2      | 1.03%   |
| Hewlett-Packard     | 2         | 3      | 1.03%   |
| CT500MX5            | 2         | 2      | 1.03%   |
| USB30               | 1         | 2      | 0.52%   |
| Team                | 1         | 2      | 0.52%   |
| PNY                 | 1         | 1      | 0.52%   |
| Netac               | 1         | 1      | 0.52%   |
| Mushkin             | 1         | 1      | 0.52%   |
| Kingmax             | 1         | 1      | 0.52%   |
| Hikvision           | 1         | 1      | 0.52%   |
| GALAX               | 1         | 1      | 0.52%   |
| FORESEE             | 1         | 1      | 0.52%   |
| Drevo               | 1         | 2      | 0.52%   |
| Dogfish             | 1         | 1      | 0.52%   |
| Corsair             | 1         | 1      | 0.52%   |
| BIWIN               | 1         | 1      | 0.52%   |
| BAITITON            | 1         | 1      | 0.52%   |
| ASUS-PHISON         | 1         | 2      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 253       | 405    | 53.38%  |
| SSD     | 164       | 235    | 34.6%   |
| NVMe    | 33        | 43     | 6.96%   |
| MMC     | 18        | 20     | 3.8%    |
| Unknown | 6         | 9      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 361       | 607    | 82.23%  |
| NVMe | 32        | 42     | 7.29%   |
| SAS  | 28        | 43     | 6.38%   |
| MMC  | 18        | 20     | 4.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 309       | 470    | 71.86%  |
| 0.51-1.0   | 85        | 117    | 19.77%  |
| 1.01-2.0   | 20        | 29     | 4.65%   |
| 3.01-4.0   | 9         | 14     | 2.09%   |
| 4.01-10.0  | 5         | 8      | 1.16%   |
| 2.01-3.0   | 2         | 2      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 151       | 37.94%  |
| 251-500        | 89        | 22.36%  |
| 501-1000       | 41        | 10.3%   |
| 51-100         | 36        | 9.05%   |
| 1001-2000      | 28        | 7.04%   |
| More than 3000 | 21        | 5.28%   |
| 21-50          | 19        | 4.77%   |
| 2001-3000      | 10        | 2.51%   |
| 1-20           | 2         | 0.5%    |
| Unknown        | 1         | 0.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 171       | 41.2%   |
| 21-50          | 95        | 22.89%  |
| 51-100         | 45        | 10.84%  |
| 101-250        | 43        | 10.36%  |
| 251-500        | 18        | 4.34%   |
| 501-1000       | 15        | 3.61%   |
| 1001-2000      | 12        | 2.89%   |
| More than 3000 | 8         | 1.93%   |
| 2001-3000      | 7         | 1.69%   |
| Unknown        | 1         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate STM9120817AS 120GB          | 1         | 1      | 10%     |
| Seagate ST9640423AS 640GB           | 1         | 1      | 10%     |
| Seagate ST9120821AS 120GB           | 1         | 1      | 10%     |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 10%     |
| Samsung Electronics MP0402H 40GB    | 1         | 1      | 10%     |
| Samsung Electronics HM500JI 500GB   | 1         | 1      | 10%     |
| Samsung Electronics HD103SJ 1TB     | 1         | 1      | 10%     |
| Kingston SV300S37A120G 120GB SSD    | 1         | 1      | 10%     |
| Fujitsu MHZ2080BJ FFS G2 80GB       | 1         | 1      | 10%     |
| Crucial M4-CT256M4SSD2 256GB        | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 30%     |
| Samsung Electronics | 3         | 3      | 30%     |
| SanDisk             | 1         | 1      | 10%     |
| Kingston            | 1         | 1      | 10%     |
| Fujitsu             | 1         | 1      | 10%     |
| Crucial             | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 42.86%  |
| Samsung Electronics | 3         | 3      | 42.86%  |
| Fujitsu             | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 70%     |
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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 344       | 631    | 87.76%  |
| Works    | 38        | 71     | 9.69%   |
| Malfunc  | 10        | 10     | 2.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 288       | 65.31%  |
| AMD                              | 61        | 13.83%  |
| Nvidia                           | 17        | 3.85%   |
| Samsung Electronics              | 11        | 2.49%   |
| JMicron Technology               | 9         | 2.04%   |
| ASMedia Technology               | 9         | 2.04%   |
| Silicon Integrated Systems [SiS] | 8         | 1.81%   |
| Phison Electronics               | 8         | 1.81%   |
| VIA Technologies                 | 7         | 1.59%   |
| SanDisk                          | 5         | 1.13%   |
| Marvell Technology Group         | 5         | 1.13%   |
| SK hynix                         | 3         | 0.68%   |
| Silicon Motion                   | 2         | 0.45%   |
| Silicon Image                    | 2         | 0.45%   |
| Kingston Technology Company      | 2         | 0.45%   |
| Broadcom / LSI                   | 2         | 0.45%   |
| Toshiba America Info Systems     | 1         | 0.23%   |
| LSI Logic / Symbios Logic        | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 5.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 24        | 4.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 3.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 17        | 3.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 2.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 15        | 2.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 13        | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 13        | 2.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12        | 2.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 10        | 1.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 10        | 1.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 10        | 1.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 10        | 1.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 10        | 1.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 9         | 1.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 1.6%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 9         | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8         | 1.43%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 7         | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 1.25%   |
| Nvidia MCP61 SATA Controller                                                   | 7         | 1.25%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 7         | 1.25%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 6         | 1.07%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 6         | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 6         | 1.07%   |
| Phison E12 NVMe Controller                                                     | 5         | 0.89%   |
| Nvidia MCP61 IDE                                                               | 5         | 0.89%   |
| JMicron JMB363 SATA/IDE Controller                                             | 5         | 0.89%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 0.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 0.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 5         | 0.89%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 5         | 0.89%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 5         | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 0.89%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 0.89%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 4         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 267       | 57.05%  |
| IDE  | 139       | 29.7%   |
| NVMe | 33        | 7.05%   |
| RAID | 25        | 5.34%   |
| SAS  | 2         | 0.43%   |
| SCSI | 2         | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 306       | 79.07%  |
| AMD    | 81        | 20.93%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz               | 6         | 1.55%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz         | 5         | 1.29%   |
| Intel Atom CPU N270 @ 1.60GHz                | 5         | 1.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 4         | 1.03%   |
| Intel Core i3-8100 CPU @ 3.60GHz             | 4         | 1.03%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 4         | 1.03%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 4         | 1.03%   |
| Intel Genuine CPU T2300 @ 1.66GHz            | 3         | 0.78%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 3         | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 3         | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 3         | 0.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 3         | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 3         | 0.78%   |
| Intel Core i3-8130U CPU @ 2.20GHz            | 3         | 0.78%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 3         | 0.78%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz         | 3         | 0.78%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz         | 3         | 0.78%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz         | 3         | 0.78%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz         | 3         | 0.78%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz         | 3         | 0.78%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 3         | 0.78%   |
| Intel Pentium M processor 2.00GHz            | 2         | 0.52%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz  | 2         | 0.52%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 2         | 0.52%   |
| Intel Pentium D CPU 2.80GHz                  | 2         | 0.52%   |
| Intel Pentium CPU P6100 @ 2.00GHz            | 2         | 0.52%   |
| Intel Pentium CPU G645 @ 2.90GHz             | 2         | 0.52%   |
| Intel Pentium CPU G2030 @ 3.00GHz            | 2         | 0.52%   |
| Intel Pentium 4 CPU 2.80GHz                  | 2         | 0.52%   |
| Intel Genuine CPU T2130 @ 1.86GHz            | 2         | 0.52%   |
| Intel Core i7-8700K CPU @ 3.70GHz            | 2         | 0.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 2         | 0.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 0.52%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz           | 2         | 0.52%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz           | 2         | 0.52%   |
| Intel Core i7-4770K CPU @ 3.50GHz            | 2         | 0.52%   |
| Intel Core i7-2670QM CPU @ 2.20GHz           | 2         | 0.52%   |
| Intel Core i7-2600 CPU @ 3.40GHz             | 2         | 0.52%   |
| Intel Core i7 CPU M 620 @ 2.67GHz            | 2         | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz            | 2         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 51        | 13.18%  |
| Intel Core i7                  | 50        | 12.92%  |
| Intel Core 2 Duo               | 41        | 10.59%  |
| Intel Core i3                  | 34        | 8.79%   |
| Intel Celeron                  | 25        | 6.46%   |
| Intel Atom                     | 21        | 5.43%   |
| Intel Pentium                  | 15        | 3.88%   |
| AMD Ryzen 5                    | 11        | 2.84%   |
| Intel Xeon                     | 9         | 2.33%   |
| Intel Core 2 Quad              | 9         | 2.33%   |
| Intel Core 2                   | 9         | 2.33%   |
| Intel Genuine                  | 8         | 2.07%   |
| Intel Pentium Dual-Core        | 7         | 1.81%   |
| Intel Pentium Dual             | 7         | 1.81%   |
| Other                          | 6         | 1.55%   |
| AMD Sempron                    | 6         | 1.55%   |
| AMD Ryzen 7                    | 6         | 1.55%   |
| Intel Pentium M                | 5         | 1.29%   |
| Intel Pentium 4                | 5         | 1.29%   |
| AMD Athlon 64 X2               | 5         | 1.29%   |
| AMD A4                         | 5         | 1.29%   |
| AMD FX                         | 4         | 1.03%   |
| Intel Pentium D                | 3         | 0.78%   |
| Intel Core Duo                 | 3         | 0.78%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.78%   |
| AMD Phenom II X4               | 3         | 0.78%   |
| AMD Athlon XP                  | 3         | 0.78%   |
| Intel Core i9                  | 2         | 0.52%   |
| AMD Ryzen 3                    | 2         | 0.52%   |
| AMD Phenom II X6               | 2         | 0.52%   |
| AMD Mobile Sempron             | 2         | 0.52%   |
| AMD E2                         | 2         | 0.52%   |
| AMD E                          | 2         | 0.52%   |
| AMD Athlon II X4               | 2         | 0.52%   |
| AMD Athlon II                  | 2         | 0.52%   |
| AMD Athlon                     | 2         | 0.52%   |
| AMD A8                         | 2         | 0.52%   |
| Intel Mobile Pentium 4         | 1         | 0.26%   |
| Intel Core m5                  | 1         | 0.26%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 219       | 56.44%  |
| 4      | 97        | 25%     |
| 1      | 46        | 11.86%  |
| 6      | 12        | 3.09%   |
| 8      | 8         | 2.06%   |
| 12     | 3         | 0.77%   |
| 16     | 1         | 0.26%   |
| 10     | 1         | 0.26%   |
| 3      | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 383       | 98.97%  |
| 2      | 4         | 1.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 209       | 54.01%  |
| 2      | 178       | 45.99%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 344       | 88.89%  |
| 32-bit         | 43        | 11.11%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 9.69%   |
| 0x1067a    | 32        | 8.16%   |
| 0x206a7    | 30        | 7.65%   |
| 0x306a9    | 25        | 6.38%   |
| 0x306c3    | 18        | 4.59%   |
| 0x6fd      | 15        | 3.83%   |
| 0x20655    | 10        | 2.55%   |
| 0x106c2    | 10        | 2.55%   |
| 0x406e3    | 9         | 2.3%    |
| 0x40651    | 9         | 2.3%    |
| 0x806ea    | 8         | 2.04%   |
| 0x30661    | 8         | 2.04%   |
| 0x06006705 | 8         | 2.04%   |
| 0x6f6      | 7         | 1.79%   |
| 0x010000c8 | 7         | 1.79%   |
| 0x6fb      | 6         | 1.53%   |
| 0x6ec      | 6         | 1.53%   |
| 0x10676    | 6         | 1.53%   |
| 0x6e8      | 5         | 1.28%   |
| 0x506e3    | 5         | 1.28%   |
| 0x30678    | 5         | 1.28%   |
| 0x106e5    | 5         | 1.28%   |
| 0x10677    | 5         | 1.28%   |
| 0xf29      | 4         | 1.02%   |
| 0x906eb    | 4         | 1.02%   |
| 0x806e9    | 4         | 1.02%   |
| 0x306d4    | 4         | 1.02%   |
| 0x08108109 | 4         | 1.02%   |
| 0x906ed    | 3         | 0.77%   |
| 0x906ea    | 3         | 0.77%   |
| 0x806ec    | 3         | 0.77%   |
| 0x806eb    | 3         | 0.77%   |
| 0x6d8      | 3         | 0.77%   |
| 0x20652    | 3         | 0.77%   |
| 0x10661    | 3         | 0.77%   |
| 0x08108102 | 3         | 0.77%   |
| 0x06001119 | 3         | 0.77%   |
| 0xf65      | 2         | 0.51%   |
| 0xf64      | 2         | 0.51%   |
| 0x706a1    | 2         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Penryn          | 46        | 11.89%  |
| SandyBridge     | 35        | 9.04%   |
| Core            | 35        | 9.04%   |
| KabyLake        | 31        | 8.01%   |
| Haswell         | 29        | 7.49%   |
| IvyBridge       | 25        | 6.46%   |
| Bonnell         | 21        | 5.43%   |
| P6              | 16        | 4.13%   |
| K8 Hammer       | 16        | 4.13%   |
| Westmere        | 15        | 3.88%   |
| Skylake         | 14        | 3.62%   |
| K10             | 13        | 3.36%   |
| Zen+            | 10        | 2.58%   |
| Silvermont      | 10        | 2.58%   |
| NetBurst        | 10        | 2.58%   |
| Zen             | 8         | 2.07%   |
| Excavator       | 8         | 2.07%   |
| Nehalem         | 7         | 1.81%   |
| Piledriver      | 5         | 1.29%   |
| Broadwell       | 5         | 1.29%   |
| Zen 2           | 4         | 1.03%   |
| Puma            | 3         | 0.78%   |
| K6              | 3         | 0.78%   |
| Goldmont plus   | 3         | 0.78%   |
| Bobcat          | 3         | 0.78%   |
| Zen 3           | 2         | 0.52%   |
| K8 & K10 hybrid | 2         | 0.52%   |
| Goldmont        | 2         | 0.52%   |
| Bulldozer       | 2         | 0.52%   |
| K10 Llano       | 1         | 0.26%   |
| Jaguar          | 1         | 0.26%   |
| IceLake         | 1         | 0.26%   |
| CometLake       | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 206       | 47.69%  |
| Nvidia                           | 117       | 27.08%  |
| AMD                              | 93        | 21.53%  |
| VIA Technologies                 | 5         | 1.16%   |
| Silicon Integrated Systems [SiS] | 5         | 1.16%   |
| Matrox Electronics Systems       | 4         | 0.93%   |
| S3 Graphics                      | 1         | 0.23%   |
| ASPEED Technology                | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 6.1%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 3.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 14        | 3.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 2.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 1.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.74%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.74%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 8         | 1.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 1.74%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 7         | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.53%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 7         | 1.53%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 7         | 1.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 1.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.31%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.09%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.87%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 4         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.87%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4         | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.87%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 3         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.65%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 3         | 0.65%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 0.65%   |
| Intel HD Graphics 5500                                                                   | 3         | 0.65%   |
| Intel HD Graphics 530                                                                    | 3         | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.65%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 3         | 0.65%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 3         | 0.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 162       | 41.75%  |
| 1 x Nvidia      | 87        | 22.42%  |
| 1 x AMD         | 80        | 20.62%  |
| Intel + Nvidia  | 29        | 7.47%   |
| Intel + AMD     | 9         | 2.32%   |
| 1 x VIA         | 5         | 1.29%   |
| 1 x SiS         | 5         | 1.29%   |
| 2 x AMD         | 4         | 1.03%   |
| 1 x Matrox      | 4         | 1.03%   |
| 2 x Nvidia      | 1         | 0.26%   |
| 1 x S3 Graphics | 1         | 0.26%   |
| 1 x ASPEED      | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 309       | 79.23%  |
| Unknown     | 44        | 11.28%  |
| Proprietary | 37        | 9.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 233       | 59.9%   |
| 0.01-0.5   | 61        | 15.68%  |
| 0.51-1.0   | 36        | 9.25%   |
| 1.01-2.0   | 31        | 7.97%   |
| 3.01-4.0   | 13        | 3.34%   |
| 7.01-8.0   | 10        | 2.57%   |
| 2.01-3.0   | 3         | 0.77%   |
| 5.01-6.0   | 2         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 62        | 16.15%  |
| AU Optronics            | 38        | 9.9%    |
| LG Display              | 31        | 8.07%   |
| BOE                     | 25        | 6.51%   |
| Goldstar                | 22        | 5.73%   |
| Chimei Innolux          | 21        | 5.47%   |
| Dell                    | 17        | 4.43%   |
| Acer                    | 17        | 4.43%   |
| Lenovo                  | 11        | 2.86%   |
| Chi Mei Optoelectronics | 11        | 2.86%   |
| AOC                     | 11        | 2.86%   |
| BenQ                    | 10        | 2.6%    |
| Ancor Communications    | 10        | 2.6%    |
| LG Philips              | 8         | 2.08%   |
| Hewlett-Packard         | 8         | 2.08%   |
| Unknown                 | 7         | 1.82%   |
| Philips                 | 7         | 1.82%   |
| HannStar                | 6         | 1.56%   |
| Sony                    | 5         | 1.3%    |
| Fujitsu Siemens         | 4         | 1.04%   |
| Apple                   | 4         | 1.04%   |
| Iiyama                  | 3         | 0.78%   |
| CPT                     | 3         | 0.78%   |
| Toshiba                 | 2         | 0.52%   |
| Sceptre Tech            | 2         | 0.52%   |
| Quanta Display          | 2         | 0.52%   |
| NEC Computers           | 2         | 0.52%   |
| LG Electronics          | 2         | 0.52%   |
| InfoVision              | 2         | 0.52%   |
| eMachines               | 2         | 0.52%   |
| Belinea                 | 2         | 0.52%   |
| ___                     | 1         | 0.26%   |
| ViewSonic               | 1         | 0.26%   |
| Vestel                  | 1         | 0.26%   |
| Targa Visionary         | 1         | 0.26%   |
| Seiko/Epson             | 1         | 0.26%   |
| RTK                     | 1         | 0.26%   |
| PANDA                   | 1         | 0.26%   |
| Panasonic               | 1         | 0.26%   |
| OEM                     | 1         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.02%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 3         | 0.77%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 3         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 0.77%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.77%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch      | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 0.51%   |
| Quanta Display LCD Monitor QDS0025 1024x768 304x228mm 15.0-inch          | 2         | 0.51%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 2         | 0.51%   |
| HannStar HSD101PFW4A HSD03ED 1024x600 223x125mm 10.1-inch                | 2         | 0.51%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 2         | 0.51%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                        | 2         | 0.51%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 344x193mm 15.5-inch | 2         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 2         | 0.51%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 0.51%   |
| BOE LCD Monitor BOE06F9 1920x1080 344x193mm 15.5-inch                    | 2         | 0.51%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.51%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 2         | 0.51%   |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                            | 2         | 0.51%   |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch                    | 1         | 0.26%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 1         | 0.26%   |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                                | 1         | 0.26%   |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                       | 1         | 0.26%   |
| Unknown LCD Monitor XXX AAA                                              | 1         | 0.26%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.26%   |
| Unknown LCD Monitor SAMSUNG                                              | 1         | 0.26%   |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                        | 1         | 0.26%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                                 | 1         | 0.26%   |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch                   | 1         | 0.26%   |
| Toshiba LCD Monitor TV 1920x1080                                         | 1         | 0.26%   |
| Toshiba LCD Monitor TOS508F 1920x1080 477x268mm 21.5-inch                | 1         | 0.26%   |
| Targa Visionary LCD19-4 TARA194 1280x1024 376x301mm 19.0-inch            | 1         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 124       | 33.16%  |
| 1366x768 (WXGA)    | 91        | 24.33%  |
| 1280x1024 (SXGA)   | 32        | 8.56%   |
| 1280x800 (WXGA)    | 27        | 7.22%   |
| 1600x900 (HD+)     | 18        | 4.81%   |
| 1440x900 (WXGA+)   | 14        | 3.74%   |
| 1680x1050 (WSXGA+) | 13        | 3.48%   |
| 1024x600           | 11        | 2.94%   |
| 3840x2160 (4K)     | 9         | 2.41%   |
| 1920x1200 (WUXGA)  | 6         | 1.6%    |
| 1024x768 (XGA)     | 6         | 1.6%    |
| 1360x768           | 5         | 1.34%   |
| Unknown            | 4         | 1.07%   |
| 3840x1080          | 2         | 0.53%   |
| 3440x1440          | 2         | 0.53%   |
| 2560x1440 (QHD)    | 2         | 0.53%   |
| 7680x2160          | 1         | 0.27%   |
| 4240x1440          | 1         | 0.27%   |
| 2736x1824          | 1         | 0.27%   |
| 2560x1080          | 1         | 0.27%   |
| 1920x540           | 1         | 0.27%   |
| 1600x1200          | 1         | 0.27%   |
| 1400x1050          | 1         | 0.27%   |
| 1280x768           | 1         | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 107       | 28.23%  |
| 17      | 29        | 7.65%   |
| 14      | 28        | 7.39%   |
| Unknown | 27        | 7.12%   |
| 13      | 23        | 6.07%   |
| 21      | 22        | 5.8%    |
| 23      | 21        | 5.54%   |
| 19      | 19        | 5.01%   |
| 24      | 17        | 4.49%   |
| 18      | 17        | 4.49%   |
| 27      | 13        | 3.43%   |
| 10      | 10        | 2.64%   |
| 20      | 8         | 2.11%   |
| 22      | 7         | 1.85%   |
| 12      | 7         | 1.85%   |
| 11      | 5         | 1.32%   |
| 31      | 4         | 1.06%   |
| 72      | 3         | 0.79%   |
| 54      | 2         | 0.53%   |
| 48      | 2         | 0.53%   |
| 34      | 2         | 0.53%   |
| 52      | 1         | 0.26%   |
| 33      | 1         | 0.26%   |
| 32      | 1         | 0.26%   |
| 26      | 1         | 0.26%   |
| 16      | 1         | 0.26%   |
| 8       | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 160       | 42.67%  |
| 401-500     | 61        | 16.27%  |
| 501-600     | 46        | 12.27%  |
| 351-400     | 32        | 8.53%   |
| 201-300     | 31        | 8.27%   |
| Unknown     | 27        | 7.2%    |
| 601-700     | 5         | 1.33%   |
| 1001-1500   | 5         | 1.33%   |
| 701-800     | 4         | 1.07%   |
| 1501-2000   | 3         | 0.8%    |
| 101-200     | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 232       | 64.27%  |
| 16/10   | 59        | 16.34%  |
| 5/4     | 28        | 7.76%   |
| Unknown | 24        | 6.65%   |
| 4/3     | 12        | 3.32%   |
| 3/2     | 3         | 0.83%   |
| 21/9    | 2         | 0.55%   |
| 32/9    | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 107       | 28.23%  |
| 201-250        | 53        | 13.98%  |
| 81-90          | 44        | 11.61%  |
| 151-200        | 38        | 10.03%  |
| 141-150        | 28        | 7.39%   |
| Unknown        | 27        | 7.12%   |
| 301-350        | 14        | 3.69%   |
| 41-50          | 10        | 2.64%   |
| 121-130        | 10        | 2.64%   |
| More than 1000 | 7         | 1.85%   |
| 351-500        | 7         | 1.85%   |
| 251-300        | 7         | 1.85%   |
| 71-80          | 6         | 1.58%   |
| 61-70          | 6         | 1.58%   |
| 51-60          | 5         | 1.32%   |
| 131-140        | 3         | 0.79%   |
| 111-120        | 2         | 0.53%   |
| 501-1000       | 2         | 0.53%   |
| 91-100         | 2         | 0.53%   |
| 1-40           | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 147       | 40.16%  |
| 101-120       | 124       | 33.88%  |
| 121-160       | 50        | 13.66%  |
| Unknown       | 27        | 7.38%   |
| 1-50          | 9         | 2.46%   |
| 161-240       | 5         | 1.37%   |
| More than 240 | 4         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 327       | 83.21%  |
| 2     | 43        | 10.94%  |
| 0     | 22        | 5.6%    |
| 3     | 1         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 224       | 35.73%  |
| Intel                                 | 130       | 20.73%  |
| Qualcomm Atheros                      | 100       | 15.95%  |
| Broadcom                              | 48        | 7.66%   |
| Nvidia                                | 14        | 2.23%   |
| Marvell Technology Group              | 14        | 2.23%   |
| Ralink Technology                     | 12        | 1.91%   |
| Broadcom Limited                      | 12        | 1.91%   |
| Samsung Electronics                   | 7         | 1.12%   |
| Ralink                                | 7         | 1.12%   |
| Silicon Integrated Systems [SiS]      | 6         | 0.96%   |
| VIA Technologies                      | 5         | 0.8%    |
| TP-Link                               | 5         | 0.8%    |
| JMicron Technology                    | 3         | 0.48%   |
| Huawei Technologies                   | 3         | 0.48%   |
| Ericsson Business Mobile Networks     | 3         | 0.48%   |
| MediaTek                              | 2         | 0.32%   |
| Linksys                               | 2         | 0.32%   |
| DisplayLink                           | 2         | 0.32%   |
| AVM                                   | 2         | 0.32%   |
| Attansic Technology                   | 2         | 0.32%   |
| ASUSTek Computer                      | 2         | 0.32%   |
| AMD                                   | 2         | 0.32%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.16%   |
| Xiaomi                                | 1         | 0.16%   |
| ST-Ericsson                           | 1         | 0.16%   |
| Sitecom Europe                        | 1         | 0.16%   |
| Sierra Wireless                       | 1         | 0.16%   |
| NetGear                               | 1         | 0.16%   |
| Microsoft                             | 1         | 0.16%   |
| Mellanox Technologies                 | 1         | 0.16%   |
| Manta                                 | 1         | 0.16%   |
| LSI                                   | 1         | 0.16%   |
| Lenovo                                | 1         | 0.16%   |
| Intersil                              | 1         | 0.16%   |
| Gemtek                                | 1         | 0.16%   |
| Edimax Technology                     | 1         | 0.16%   |
| Dell                                  | 1         | 0.16%   |
| Cisco Aironet Wireless Communications | 1         | 0.16%   |
| Belkin Components                     | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 134       | 18.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 48        | 6.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 2.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 1.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 12        | 1.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 1.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 1.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.1%    |
| Nvidia MCP61 Ethernet                                                   | 7         | 0.96%   |
| Intel I211 Gigabit Network Connection                                   | 7         | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 6         | 0.82%   |
| Intel Wireless 7260                                                     | 6         | 0.82%   |
| Intel WiFi Link 5100                                                    | 6         | 0.82%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 5         | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.69%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 5         | 0.69%   |
| Intel Wireless 8265 / 8275                                              | 5         | 0.69%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 0.69%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.69%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.69%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.55%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 4         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.55%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                 | 4         | 0.55%   |
| Intel Wireless 3160                                                     | 4         | 0.55%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.55%   |
| Intel 82573L Gigabit Ethernet Controller                                | 4         | 0.55%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 3         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 86        | 27.92%  |
| Qualcomm Atheros                      | 80        | 25.97%  |
| Realtek Semiconductor                 | 64        | 20.78%  |
| Broadcom                              | 33        | 10.71%  |
| Ralink Technology                     | 12        | 3.9%    |
| Ralink                                | 7         | 2.27%   |
| TP-Link                               | 5         | 1.62%   |
| Broadcom Limited                      | 5         | 1.62%   |
| Linksys                               | 2         | 0.65%   |
| AVM                                   | 2         | 0.65%   |
| ASUSTek Computer                      | 2         | 0.65%   |
| Sitecom Europe                        | 1         | 0.32%   |
| Sierra Wireless                       | 1         | 0.32%   |
| NetGear                               | 1         | 0.32%   |
| Microsoft                             | 1         | 0.32%   |
| MediaTek                              | 1         | 0.32%   |
| Marvell Technology Group              | 1         | 0.32%   |
| Edimax Technology                     | 1         | 0.32%   |
| Cisco Aironet Wireless Communications | 1         | 0.32%   |
| Belkin Components                     | 1         | 0.32%   |
| Askey Computer                        | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 4.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 4.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 4.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 3.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 3.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 3.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.56%   |
| Intel Wireless 7260                                                     | 6         | 1.92%   |
| Intel WiFi Link 5100                                                    | 6         | 1.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 1.6%    |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 1.6%    |
| Intel Wireless 8265 / 8275                                              | 5         | 1.6%    |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.6%    |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.6%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.28%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.28%   |
| Intel Wireless 3160                                                     | 4         | 1.28%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.96%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.96%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 3         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.96%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 3         | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.96%   |
| Intel Wireless 8260                                                     | 3         | 0.96%   |
| Intel Wireless 7265                                                     | 3         | 0.96%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.96%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.96%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.96%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.96%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 201       | 51.15%  |
| Intel                            | 74        | 18.83%  |
| Qualcomm Atheros                 | 30        | 7.63%   |
| Broadcom                         | 20        | 5.09%   |
| Nvidia                           | 14        | 3.56%   |
| Marvell Technology Group         | 13        | 3.31%   |
| Samsung Electronics              | 7         | 1.78%   |
| Broadcom Limited                 | 7         | 1.78%   |
| Silicon Integrated Systems [SiS] | 6         | 1.53%   |
| VIA Technologies                 | 5         | 1.27%   |
| JMicron Technology               | 3         | 0.76%   |
| Huawei Technologies              | 2         | 0.51%   |
| DisplayLink                      | 2         | 0.51%   |
| Attansic Technology              | 2         | 0.51%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.25%   |
| Xiaomi                           | 1         | 0.25%   |
| MediaTek                         | 1         | 0.25%   |
| Lenovo                           | 1         | 0.25%   |
| Gemtek                           | 1         | 0.25%   |
| ADMtek                           | 1         | 0.25%   |
| 3Com                             | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 134       | 33.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 48        | 12.06%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 3.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.76%   |
| Nvidia MCP61 Ethernet                                             | 7         | 1.76%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.76%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 1.51%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 5         | 1.26%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 1.26%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 1.26%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.26%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.26%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4         | 1.01%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 1.01%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 4         | 1.01%   |
| Intel 82573L Gigabit Ethernet Controller                          | 4         | 1.01%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 3         | 0.75%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.75%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3         | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.75%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3         | 0.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.75%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 3         | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.5%    |
| Nvidia nForce2 Ethernet Controller                                | 2         | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 2         | 0.5%    |
| Nvidia MCP67 Ethernet                                             | 2         | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.5%    |
| Intel PRO/100 VE Network Connection                               | 2         | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 2         | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.5%    |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.5%    |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 369       | 54.34%  |
| WiFi     | 291       | 42.86%  |
| Modem    | 15        | 2.21%   |
| Unknown  | 4         | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 212       | 53.67%  |
| Ethernet | 183       | 46.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 244       | 63.05%  |
| 1     | 131       | 33.85%  |
| 3     | 6         | 1.55%   |
| 4     | 4         | 1.03%   |
| 0     | 2         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 333       | 83.88%  |
| Yes  | 64        | 16.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 25.61%  |
| Realtek Semiconductor           | 22        | 13.41%  |
| Broadcom                        | 18        | 10.98%  |
| Qualcomm Atheros Communications | 16        | 9.76%   |
| Cambridge Silicon Radio         | 11        | 6.71%   |
| Foxconn / Hon Hai               | 9         | 5.49%   |
| Hewlett-Packard                 | 8         | 4.88%   |
| Lite-On Technology              | 6         | 3.66%   |
| IMC Networks                    | 5         | 3.05%   |
| Dell                            | 5         | 3.05%   |
| ASUSTek Computer                | 5         | 3.05%   |
| Apple                           | 4         | 2.44%   |
| Toshiba                         | 3         | 1.83%   |
| Taiyo Yuden                     | 1         | 0.61%   |
| Realtek                         | 1         | 0.61%   |
| Ralink Technology               | 1         | 0.61%   |
| Ralink                          | 1         | 0.61%   |
| Qcom                            | 1         | 0.61%   |
| MediaTek                        | 1         | 0.61%   |
| Marvell Semiconductor           | 1         | 0.61%   |
| Foxconn International           | 1         | 0.61%   |
| Askey Computer                  | 1         | 0.61%   |
| Alps Electric                   | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 21        | 12.8%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 13        | 7.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 6.71%   |
| Realtek Bluetooth Radio                                                             | 9         | 5.49%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 4.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 3.05%   |
| Intel AX200 Bluetooth                                                               | 5         | 3.05%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 5         | 3.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 2.44%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 2.44%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 2.44%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.83%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 1.83%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.83%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 1.83%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.22%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 1.22%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.22%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.22%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.22%   |
| Foxconn / Hon Hai Acer Module                                                       | 2         | 1.22%   |
| Broadcom Bluetooth                                                                  | 2         | 1.22%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.22%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.22%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 2         | 1.22%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.22%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.61%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.61%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.61%   |
| Taiyo Yuden Bluetooth Device(BC04-External)                                         | 1         | 0.61%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.61%   |
| Ralink CSR BS8510                                                                   | 1         | 0.61%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.61%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.61%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.61%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 279       | 55.8%   |
| AMD                              | 85        | 17%     |
| Nvidia                           | 82        | 16.4%   |
| C-Media Electronics              | 11        | 2.2%    |
| VIA Technologies                 | 9         | 1.8%    |
| Silicon Integrated Systems [SiS] | 8         | 1.6%    |
| Generalplus Technology           | 4         | 0.8%    |
| Creative Labs                    | 4         | 0.8%    |
| Logitech                         | 3         | 0.6%    |
| GN Netcom                        | 3         | 0.6%    |
| Tenx Technology                  | 2         | 0.4%    |
| JMTek                            | 2         | 0.4%    |
| Yamaha                           | 1         | 0.2%    |
| Xilinx                           | 1         | 0.2%    |
| M-Audio                          | 1         | 0.2%    |
| GYROCOM C&C                      | 1         | 0.2%    |
| Focusrite-Novation               | 1         | 0.2%    |
| Evolution Electronics            | 1         | 0.2%    |
| Dell                             | 1         | 0.2%    |
| Creative Technology              | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 43        | 7.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 32        | 5.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 26        | 4.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 26        | 4.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 22        | 3.85%   |
| Intel Sunrise Point-LP HD Audio                                            | 21        | 3.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 17        | 2.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 2.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 13        | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 2.27%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 2.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 10        | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 1.57%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 1.57%   |
| Nvidia High Definition Audio Controller                                    | 8         | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 1.4%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 8         | 1.4%    |
| AMD High Definition Audio Controller                                       | 8         | 1.4%    |
| AMD FCH Azalia Controller                                                  | 8         | 1.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 1.4%    |
| Nvidia MCP61 High Definition Audio                                         | 7         | 1.22%   |
| Nvidia GM206 High Definition Audio Controller                              | 7         | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6         | 1.05%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 6         | 1.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.87%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 5         | 0.87%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 0.87%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 5         | 0.87%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 4         | 0.7%    |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 4         | 0.7%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 4         | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.7%    |
| Nvidia GK104 HDMI Audio Controller                                         | 4         | 0.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 0.7%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 4         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 13        | 20.97%  |
| SK hynix            | 12        | 19.35%  |
| Samsung Electronics | 11        | 17.74%  |
| Kingston            | 8         | 12.9%   |
| Crucial             | 3         | 4.84%   |
| Smart               | 2         | 3.23%   |
| Ramaxel Technology  | 2         | 3.23%   |
| Nanya Technology    | 2         | 3.23%   |
| Micron Technology   | 2         | 3.23%   |
| G.Skill             | 2         | 3.23%   |
| Unknown (ABCD)      | 1         | 1.61%   |
| Transcend           | 1         | 1.61%   |
| PLEXHD              | 1         | 1.61%   |
| Exceleram           | 1         | 1.61%   |
| A-DATA Technology   | 1         | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 3.03%   |
| Unknown RAM Module SODIMM DDR                                    | 1         | 1.52%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 1.52%   |
| Unknown RAM Module 512MB DIMM 667MT/s                            | 1         | 1.52%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.52%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 1.52%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 1.52%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 1.52%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 1         | 1.52%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                      | 1         | 1.52%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 1.52%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1         | 1.52%   |
| Unknown RAM Module 1024MB DIMM                                   | 1         | 1.52%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s               | 1         | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.52%   |
| Transcend RAM JM800QSU-2G 2048MB SODIMM DDR2 975MT/s             | 1         | 1.52%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s                    | 1         | 1.52%   |
| SK hynix RAM Module 512MB SODIMM DDR 533MT/s                     | 1         | 1.52%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 1.52%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.52%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.52%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.52%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.52%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.52%   |
| SK hynix RAM HMP125S6EFR8C-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.52%   |
| SK hynix RAM HMP112S6EFR6C-S6 1024MB SODIMM DDR 800MT/s          | 1         | 1.52%   |
| SK hynix RAM HMA851S6DJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.52%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.52%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 39.29%  |
| DDR4    | 17        | 30.36%  |
| DDR2    | 9         | 16.07%  |
| DDR     | 3         | 5.36%   |
| SDRAM   | 2         | 3.57%   |
| Unknown | 2         | 3.57%   |
| LPDDR4  | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 32        | 59.26%  |
| DIMM   | 22        | 40.74%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 23        | 38.33%  |
| 4096    | 13        | 21.67%  |
| 2048    | 13        | 21.67%  |
| 1024    | 6         | 10%     |
| 16384   | 2         | 3.33%   |
| 512     | 2         | 3.33%   |
| Unknown | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 22.03%  |
| 2667    | 10        | 16.95%  |
| 1333    | 7         | 11.86%  |
| 2400    | 5         | 8.47%   |
| 800     | 5         | 8.47%   |
| 667     | 3         | 5.08%   |
| Unknown | 3         | 5.08%   |
| 3266    | 2         | 3.39%   |
| 975     | 2         | 3.39%   |
| 533     | 2         | 3.39%   |
| 4266    | 1         | 1.69%   |
| 3800    | 1         | 1.69%   |
| 3500    | 1         | 1.69%   |
| 3200    | 1         | 1.69%   |
| 2666    | 1         | 1.69%   |
| 2048    | 1         | 1.69%   |
| 400     | 1         | 1.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 46.15%  |
| Samsung Electronics | 2         | 15.38%  |
| Brother Industries  | 2         | 15.38%  |
| Seiko Epson         | 1         | 7.69%   |
| Ricoh               | 1         | 7.69%   |
| Canon               | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-3100 Series | 1         | 7.69%   |
| Samsung SCX-3400 Series    | 1         | 7.69%   |
| Samsung ML-1670 Series     | 1         | 7.69%   |
| Ricoh SP C260SFNw          | 1         | 7.69%   |
| HP LaserJet P1006          | 1         | 7.69%   |
| HP LaserJet 3050           | 1         | 7.69%   |
| HP DeskJet F4200 series    | 1         | 7.69%   |
| HP DeskJet 2700 series     | 1         | 7.69%   |
| HP Deskjet 2540 series     | 1         | 7.69%   |
| HP Deskjet 1050 J410       | 1         | 7.69%   |
| Canon iP4200               | 1         | 7.69%   |
| Brother MFC-L2685DW        | 1         | 7.69%   |
| Brother HL-L2300D series   | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 33.33%  |
| HP ScanJet 3800c                              | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 42        | 21.32%  |
| IMC Networks                           | 17        | 8.63%   |
| Sunplus Innovation Technology          | 15        | 7.61%   |
| Suyin                                  | 14        | 7.11%   |
| Quanta                                 | 13        | 6.6%    |
| Acer                                   | 13        | 6.6%    |
| Realtek Semiconductor                  | 9         | 4.57%   |
| Microdia                               | 9         | 4.57%   |
| Silicon Motion                         | 7         | 3.55%   |
| Logitech                               | 7         | 3.55%   |
| Ricoh                                  | 6         | 3.05%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.05%   |
| Apple                                  | 6         | 3.05%   |
| Syntek                                 | 5         | 2.54%   |
| Z-Star Microelectronics                | 3         | 1.52%   |
| Microsoft                              | 3         | 1.52%   |
| Importek                               | 3         | 1.52%   |
| Sunplus Technology                     | 2         | 1.02%   |
| Lite-On Technology                     | 2         | 1.02%   |
| Generalplus Technology                 | 2         | 1.02%   |
| ALi                                    | 2         | 1.02%   |
| Xiongmai                               | 1         | 0.51%   |
| WCM_USB                                | 1         | 0.51%   |
| Service & Quality Technology           | 1         | 0.51%   |
| Samsung Electronics                    | 1         | 0.51%   |
| OmniVision Technologies                | 1         | 0.51%   |
| Nintendo                               | 1         | 0.51%   |
| MacroSilicon                           | 1         | 0.51%   |
| LG Electronics                         | 1         | 0.51%   |
| Lenovo                                 | 1         | 0.51%   |
| KYE Systems (Mouse Systems)            | 1         | 0.51%   |
| Alcor Micro                            | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Quanta HP Webcam                                 | 6         | 3.03%   |
| Chicony Integrated Camera                        | 5         | 2.53%   |
| Logitech Webcam C270                             | 4         | 2.02%   |
| Chicony USB2.0 HD UVC WebCam                     | 4         | 2.02%   |
| Chicony USB 2.0 Camera                           | 4         | 2.02%   |
| Suyin HP TrueVision HD                           | 3         | 1.52%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 3         | 1.52%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 3         | 1.52%   |
| Realtek USB2.0 VGA UVC WebCam                    | 3         | 1.52%   |
| Chicony HD WebCam                                | 3         | 1.52%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 3         | 1.52%   |
| Apple iPhone5/5C/5S/6                            | 3         | 1.52%   |
| Apple Built-in iSight                            | 3         | 1.52%   |
| Acer USB Camera                                  | 3         | 1.52%   |
| Acer Lenovo EasyCamera                           | 3         | 1.52%   |
| Syntek Sonix USB 2.0 Camera                      | 2         | 1.01%   |
| Suyin 1.3M HD WebCam                             | 2         | 1.01%   |
| Sunplus Laptop Integrated WebCam HD              | 2         | 1.01%   |
| Sunplus HP TrueVision HD Camera                  | 2         | 1.01%   |
| Silicon Motion WebCam SCB-0385N                  | 2         | 1.01%   |
| Silicon Motion WebCam SC-0311139N                | 2         | 1.01%   |
| Silicon Motion HP Webcam-101                     | 2         | 1.01%   |
| Ricoh Sony Visual Communication Camera           | 2         | 1.01%   |
| Realtek Integrated_Webcam_HD                     | 2         | 1.01%   |
| Quanta VGA WebCam                                | 2         | 1.01%   |
| Quanta HP TrueVision HD Camera                   | 2         | 1.01%   |
| Microsoft LifeCam HD-3000                        | 2         | 1.01%   |
| Microdia Sonix USB 2.0 Camera                    | 2         | 1.01%   |
| Microdia Integrated Webcam HD                    | 2         | 1.01%   |
| Importek TOSHIBA Web Camera - HD                 | 2         | 1.01%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 1.01%   |
| IMC Networks USB2.0 HD UVC WebCam                | 2         | 1.01%   |
| IMC Networks USB Camera                          | 2         | 1.01%   |
| IMC Networks USB 2.0 UVC VGA WebCam              | 2         | 1.01%   |
| IMC Networks Integrated Camera                   | 2         | 1.01%   |
| IMC Networks EasyCamera                          | 2         | 1.01%   |
| Chicony TOSHIBA Web Camera - HD                  | 2         | 1.01%   |
| Chicony HP Truevision HD camera                  | 2         | 1.01%   |
| Chicony HD WebCam (Acer)                         | 2         | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.01%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 9         | 32.14%  |
| AuthenTec             | 8         | 28.57%  |
| STMicroelectronics    | 3         | 10.71%  |
| LighTuning Technology | 3         | 10.71%  |
| Synaptics             | 2         | 7.14%   |
| Elan Microelectronics | 2         | 7.14%   |
| Upek                  | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                  | 3         | 10.71%  |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 7.14%   |
| Validity Sensors VFS301 Fingerprint Reader             | 2         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 7.14%   |
| Elan ELAN:Fingerprint                                  | 2         | 7.14%   |
| AuthenTec Fingerprint Sensor                           | 2         | 7.14%   |
| AuthenTec AES2810                                      | 2         | 7.14%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 7.14%   |
| AuthenTec AES1600                                      | 2         | 7.14%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 3.57%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 3.57%   |
| Validity Sensors VFS491                                | 1         | 3.57%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 3.57%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 3.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 3.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 3.57%   |
| Unknown                                                | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 8         | 50%     |
| O2 Micro                          | 3         | 18.75%  |
| VASCO Data Security International | 1         | 6.25%   |
| OmniKey                           | 1         | 6.25%   |
| Jing-Mold Enterprise              | 1         | 6.25%   |
| Gemalto (was Gemplus)             | 1         | 6.25%   |
| Alcor Micro                       | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 18.75%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 12.5%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 6.25%   |
| OmniKey CardMan 1021                                                         | 1         | 6.25%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 6.25%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 6.25%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 6.25%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 257       | 65.56%  |
| 1     | 101       | 25.77%  |
| 2     | 21        | 5.36%   |
| 3     | 10        | 2.55%   |
| 4     | 2         | 0.51%   |
| 6     | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 62        | 36.05%  |
| Net/wireless             | 33        | 19.19%  |
| Fingerprint reader       | 28        | 16.28%  |
| Chipcard                 | 13        | 7.56%   |
| Multimedia controller    | 9         | 5.23%   |
| Communication controller | 8         | 4.65%   |
| Storage                  | 6         | 3.49%   |
| Network                  | 3         | 1.74%   |
| Unassigned class         | 2         | 1.16%   |
| Net/ethernet             | 2         | 1.16%   |
| Flash memory             | 2         | 1.16%   |
| Storage/ide              | 1         | 0.58%   |
| Modem                    | 1         | 0.58%   |
| Camera                   | 1         | 0.58%   |
| Bluetooth                | 1         | 0.58%   |

