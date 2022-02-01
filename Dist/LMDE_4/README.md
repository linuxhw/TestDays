LMDE 4 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 4.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_4/Desktop/README.md) and [notebooks](/Dist/LMDE_4/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| EVGA          | 131-HE-E095                 | Desktop     | [6d45d47131](https://linux-hardware.org/?probe=6d45d47131) | Jan 31, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [00cd805015](https://linux-hardware.org/?probe=00cd805015) | Jan 23, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [be068c5a3a](https://linux-hardware.org/?probe=be068c5a3a) | Jan 21, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [a988797ac9](https://linux-hardware.org/?probe=a988797ac9) | Jan 16, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [311d594372](https://linux-hardware.org/?probe=311d594372) | Jan 13, 2022 |
| Digma         | EVE 10 C301T ES1043EW       | Tablet      | [4fac8e2cb1](https://linux-hardware.org/?probe=4fac8e2cb1) | Jan 11, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [ea55ac1aab](https://linux-hardware.org/?probe=ea55ac1aab) | Jan 11, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [252df76aa8](https://linux-hardware.org/?probe=252df76aa8) | Jan 10, 2022 |
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
| Wistron       | ProLiant ML110 G5           | Server      | [c3bd5cbae8](https://linux-hardware.org/?probe=c3bd5cbae8) | Dec 27, 2021 |
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
| Intel         | H61                         | Desktop     | [c3f5ace673](https://linux-hardware.org/?probe=c3f5ace673) | Nov 02, 2021 |
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
| HP            | Pavilion dv6                | Notebook    | [b4200dd39c](https://linux-hardware.org/?probe=b4200dd39c) | Oct 13, 2021 |
| Medion        | P6670 MD99960               | Notebook    | [eaa186d207](https://linux-hardware.org/?probe=eaa186d207) | Oct 12, 2021 |
| Medion        | P6670 MD99960               | Notebook    | [d42f345fc5](https://linux-hardware.org/?probe=d42f345fc5) | Oct 12, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [940a27249a](https://linux-hardware.org/?probe=940a27249a) | Oct 12, 2021 |
| HP            | 520                         | Notebook    | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [393852d904](https://linux-hardware.org/?probe=393852d904) | Oct 10, 2021 |
| Dell          | Precision M2800             | Notebook    | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| HUAWEI        | MateBook HZ-W19             | Tablet      | [904decfd32](https://linux-hardware.org/?probe=904decfd32) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [633c289440](https://linux-hardware.org/?probe=633c289440) | Sep 28, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [012056e32d](https://linux-hardware.org/?probe=012056e32d) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [a6d07be7c9](https://linux-hardware.org/?probe=a6d07be7c9) | Sep 27, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [759b25b6a9](https://linux-hardware.org/?probe=759b25b6a9) | Sep 27, 2021 |
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
| ASUSTek       | P5VD2-VM                    | Desktop     | [9bab4b76ff](https://linux-hardware.org/?probe=9bab4b76ff) | Sep 07, 2021 |
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
| Dell          | XPS M1330                   | Notebook    | [f4e126fba9](https://linux-hardware.org/?probe=f4e126fba9) | Aug 28, 2021 |
| ASUSTek       | 1201HA                      | Notebook    | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | Notebook    | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | Notebook    | [7706314dbc](https://linux-hardware.org/?probe=7706314dbc) | Aug 24, 2021 |
| Itautec       | W7655                       | Notebook    | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Itautec       | W7655                       | Notebook    | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| HP            | 14                          | Notebook    | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [c34caa75e2](https://linux-hardware.org/?probe=c34caa75e2) | Aug 23, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [42ca8c45b4](https://linux-hardware.org/?probe=42ca8c45b4) | Aug 22, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [48360885d9](https://linux-hardware.org/?probe=48360885d9) | Aug 22, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [31ed530084](https://linux-hardware.org/?probe=31ed530084) | Aug 22, 2021 |
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
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [322a210197](https://linux-hardware.org/?probe=322a210197) | Aug 05, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [05c1703574](https://linux-hardware.org/?probe=05c1703574) | Aug 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [c930d1c587](https://linux-hardware.org/?probe=c930d1c587) | Aug 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [eb5ff22307](https://linux-hardware.org/?probe=eb5ff22307) | Aug 03, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [faf304d157](https://linux-hardware.org/?probe=faf304d157) | Aug 02, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [2ffa81b543](https://linux-hardware.org/?probe=2ffa81b543) | Aug 01, 2021 |
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
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [eef16a5b8f](https://linux-hardware.org/?probe=eef16a5b8f) | Jul 17, 2021 |
| Dell          | XPS M1330                   | Notebook    | [55de50364d](https://linux-hardware.org/?probe=55de50364d) | Jul 17, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [64d562d6ef](https://linux-hardware.org/?probe=64d562d6ef) | Jul 16, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [ab57bbf3d8](https://linux-hardware.org/?probe=ab57bbf3d8) | Jul 15, 2021 |
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
| Intel         | H61                         | Desktop     | [6b0bdb5986](https://linux-hardware.org/?probe=6b0bdb5986) | Jun 14, 2021 |
| HP            | 0AA8h                       | Desktop     | [9154911bc9](https://linux-hardware.org/?probe=9154911bc9) | Jun 13, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [67bbff8363](https://linux-hardware.org/?probe=67bbff8363) | Jun 11, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [b37374d9f8](https://linux-hardware.org/?probe=b37374d9f8) | Jun 11, 2021 |
| Gateway       | LT40                        | Notebook    | [fe2551cb8b](https://linux-hardware.org/?probe=fe2551cb8b) | Jun 11, 2021 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [699d10613e](https://linux-hardware.org/?probe=699d10613e) | Jun 11, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [f0b9aa22e5](https://linux-hardware.org/?probe=f0b9aa22e5) | Jun 10, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [57f93cbf62](https://linux-hardware.org/?probe=57f93cbf62) | Jun 09, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [4f752689ed](https://linux-hardware.org/?probe=4f752689ed) | Jun 03, 2021 |
| Gateway       | LT40                        | Notebook    | [9defd288c4](https://linux-hardware.org/?probe=9defd288c4) | Jun 01, 2021 |
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
| ASUSTek       | P7F-M                       | Desktop     | [2ad3cb7346](https://linux-hardware.org/?probe=2ad3cb7346) | May 22, 2021 |
| Intel         | H61                         | Desktop     | [dad657a0bc](https://linux-hardware.org/?probe=dad657a0bc) | May 19, 2021 |
| HP            | Pavilion dv6                | Notebook    | [fb309a7f37](https://linux-hardware.org/?probe=fb309a7f37) | May 17, 2021 |
| Foxconn       | 945 7MC Series              | Desktop     | [f4634ec470](https://linux-hardware.org/?probe=f4634ec470) | May 17, 2021 |
| Dell          | 0FM586 A00                  | Desktop     | [8a955d2c5a](https://linux-hardware.org/?probe=8a955d2c5a) | May 16, 2021 |
| Intel         | H61                         | Desktop     | [76574dce75](https://linux-hardware.org/?probe=76574dce75) | May 16, 2021 |
| ASUSTek       | B150M-A                     | Desktop     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [a502e8842e](https://linux-hardware.org/?probe=a502e8842e) | May 12, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | Notebook    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [7023b380c0](https://linux-hardware.org/?probe=7023b380c0) | May 11, 2021 |
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
| ASUSTek       | P5KC                        | Desktop     | [50505c9ede](https://linux-hardware.org/?probe=50505c9ede) | Apr 30, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [b51106e072](https://linux-hardware.org/?probe=b51106e072) | Apr 30, 2021 |
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
| Toshiba       | NI 1403                     | Notebook    | [6587e3e02c](https://linux-hardware.org/?probe=6587e3e02c) | Apr 11, 2021 |
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
| Intel         | H61                         | Desktop     | [724cdd1804](https://linux-hardware.org/?probe=724cdd1804) | Mar 27, 2021 |
| Intel         | H61                         | Desktop     | [d7c3f87e52](https://linux-hardware.org/?probe=d7c3f87e52) | Mar 26, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [6ab1c423db](https://linux-hardware.org/?probe=6ab1c423db) | Mar 25, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [a9c3672597](https://linux-hardware.org/?probe=a9c3672597) | Mar 25, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [3b4565a813](https://linux-hardware.org/?probe=3b4565a813) | Mar 20, 2021 |
| HP            | Unknown                     | Notebook    | [2f594364bb](https://linux-hardware.org/?probe=2f594364bb) | Mar 20, 2021 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| MSI           | MS-6785                     | Desktop     | [303c1ac636](https://linux-hardware.org/?probe=303c1ac636) | Mar 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [06207199fa](https://linux-hardware.org/?probe=06207199fa) | Mar 16, 2021 |
| ASUSTek       | X542UAR                     | Notebook    | [4a2b4a2f3d](https://linux-hardware.org/?probe=4a2b4a2f3d) | Mar 15, 2021 |
| ASUSTek       | X542UAR                     | Notebook    | [824a5703c6](https://linux-hardware.org/?probe=824a5703c6) | Mar 15, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [faee1ed378](https://linux-hardware.org/?probe=faee1ed378) | Mar 13, 2021 |
| Sony          | VGN-FZ140E                  | Notebook    | [1d611ce57d](https://linux-hardware.org/?probe=1d611ce57d) | Mar 13, 2021 |
| Sony          | VGN-FZ140E                  | Notebook    | [3bfba9b2a3](https://linux-hardware.org/?probe=3bfba9b2a3) | Mar 13, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [f8503ecc3b](https://linux-hardware.org/?probe=f8503ecc3b) | Mar 10, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [553bb797b4](https://linux-hardware.org/?probe=553bb797b4) | Mar 09, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | Notebook    | [6ce455b6ab](https://linux-hardware.org/?probe=6ce455b6ab) | Mar 08, 2021 |
| ECS           | A740GM-M                    | Desktop     | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [a8d2e4fa56](https://linux-hardware.org/?probe=a8d2e4fa56) | Mar 07, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [8589da1141](https://linux-hardware.org/?probe=8589da1141) | Mar 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [79e6e8bbfc](https://linux-hardware.org/?probe=79e6e8bbfc) | Mar 06, 2021 |
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
| Dell          | Inspiron 7520               | Notebook    | [6494901310](https://linux-hardware.org/?probe=6494901310) | Feb 24, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [527b138b70](https://linux-hardware.org/?probe=527b138b70) | Feb 22, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| Toshiba       | NI 1403                     | Notebook    | [4e907477e1](https://linux-hardware.org/?probe=4e907477e1) | Feb 21, 2021 |
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
| Toshiba       | NI 1403                     | Notebook    | [509417cf38](https://linux-hardware.org/?probe=509417cf38) | Feb 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [289d2b0685](https://linux-hardware.org/?probe=289d2b0685) | Feb 10, 2021 |
| LG Electro... | X120-G.C7VPG                | Notebook    | [349c20610a](https://linux-hardware.org/?probe=349c20610a) | Feb 10, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [f4995bc45c](https://linux-hardware.org/?probe=f4995bc45c) | Feb 07, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c8e67a7d41](https://linux-hardware.org/?probe=c8e67a7d41) | Feb 07, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [6e605fd64d](https://linux-hardware.org/?probe=6e605fd64d) | Feb 06, 2021 |
| Toshiba       | NI 1403                     | Notebook    | [8dd19e0d5b](https://linux-hardware.org/?probe=8dd19e0d5b) | Feb 06, 2021 |
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
| Toshiba       | NI 1403                     | Notebook    | [c65b4686c1](https://linux-hardware.org/?probe=c65b4686c1) | Jan 16, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [08ac15e868](https://linux-hardware.org/?probe=08ac15e868) | Jan 15, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [d60611163e](https://linux-hardware.org/?probe=d60611163e) | Jan 15, 2021 |
| Matsushita... | CF-19CHB23BE                | Notebook    | [e9fa72450f](https://linux-hardware.org/?probe=e9fa72450f) | Jan 14, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [d0da7a44f7](https://linux-hardware.org/?probe=d0da7a44f7) | Jan 14, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [0826a741c2](https://linux-hardware.org/?probe=0826a741c2) | Jan 13, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [e9f548f926](https://linux-hardware.org/?probe=e9f548f926) | Jan 13, 2021 |
| Alienware     | 06G6JW A00                  | Desktop     | [992089d02a](https://linux-hardware.org/?probe=992089d02a) | Jan 12, 2021 |
| Toshiba       | NI 1403                     | Notebook    | [f2a6c004f5](https://linux-hardware.org/?probe=f2a6c004f5) | Jan 10, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [f894e05226](https://linux-hardware.org/?probe=f894e05226) | Jan 09, 2021 |
| Unknown       | Unknown                     | Notebook    | [89562751d7](https://linux-hardware.org/?probe=89562751d7) | Jan 08, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [51ec8a1510](https://linux-hardware.org/?probe=51ec8a1510) | Jan 06, 2021 |
| ASUSTek       | P5K                         | Desktop     | [22a568db8e](https://linux-hardware.org/?probe=22a568db8e) | Jan 02, 2021 |
| ASUSTek       | P5K                         | Desktop     | [4233bd7b15](https://linux-hardware.org/?probe=4233bd7b15) | Jan 02, 2021 |
| Exper         | E10IL1                      | Notebook    | [8a1f9ff144](https://linux-hardware.org/?probe=8a1f9ff144) | Dec 31, 2020 |
| MSI           | MS-6570                     | Desktop     | [f6bdec1638](https://linux-hardware.org/?probe=f6bdec1638) | Dec 28, 2020 |
| Dell          | Precision M4800             | Notebook    | [10bfd0b228](https://linux-hardware.org/?probe=10bfd0b228) | Dec 27, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [d361c2fd53](https://linux-hardware.org/?probe=d361c2fd53) | Dec 27, 2020 |
| ASUSTek       | K55N                        | Notebook    | [e3edf30a97](https://linux-hardware.org/?probe=e3edf30a97) | Dec 26, 2020 |
| ASUSTek       | K55N                        | Notebook    | [d7630d7410](https://linux-hardware.org/?probe=d7630d7410) | Dec 26, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [95d4d575bf](https://linux-hardware.org/?probe=95d4d575bf) | Dec 26, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [6fd8e6692a](https://linux-hardware.org/?probe=6fd8e6692a) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | Notebook    | [c0f1039074](https://linux-hardware.org/?probe=c0f1039074) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | Notebook    | [5584ad5871](https://linux-hardware.org/?probe=5584ad5871) | Dec 24, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [e3b15b9aab](https://linux-hardware.org/?probe=e3b15b9aab) | Dec 23, 2020 |
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
| Toshiba       | NI 1403                     | Notebook    | [73fff8bebf](https://linux-hardware.org/?probe=73fff8bebf) | Dec 13, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [e1afb118e5](https://linux-hardware.org/?probe=e1afb118e5) | Dec 12, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [e8b1e86c0c](https://linux-hardware.org/?probe=e8b1e86c0c) | Dec 12, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [761cc07d16](https://linux-hardware.org/?probe=761cc07d16) | Dec 11, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [d811cc41d8](https://linux-hardware.org/?probe=d811cc41d8) | Dec 09, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [5a3c92338e](https://linux-hardware.org/?probe=5a3c92338e) | Dec 08, 2020 |
| EVGA          | 131-HE-E095                 | Desktop     | [8fca80343b](https://linux-hardware.org/?probe=8fca80343b) | Dec 08, 2020 |
| HP            | Pavilion ze2000 (EA772AV... | Notebook    | [15284f8c6e](https://linux-hardware.org/?probe=15284f8c6e) | Dec 07, 2020 |
| Dell          | Precision M4600             | Notebook    | [690e349224](https://linux-hardware.org/?probe=690e349224) | Dec 06, 2020 |
| Dell          | Precision M4600             | Notebook    | [f2023ec8ae](https://linux-hardware.org/?probe=f2023ec8ae) | Dec 06, 2020 |
| HP            | 1496                        | Desktop     | [61eeea25ed](https://linux-hardware.org/?probe=61eeea25ed) | Dec 04, 2020 |
| Acer          | Extensa 4620                | Notebook    | [1bda4268f4](https://linux-hardware.org/?probe=1bda4268f4) | Dec 04, 2020 |
| Matsushita... | CF-19CHB23BE                | Notebook    | [26a940a651](https://linux-hardware.org/?probe=26a940a651) | Dec 01, 2020 |
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
| Toshiba       | NI 1403                     | Notebook    | [7c9600b0bb](https://linux-hardware.org/?probe=7c9600b0bb) | Nov 14, 2020 |
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
| Toshiba       | NI 1403                     | Notebook    | [07e61e6f8d](https://linux-hardware.org/?probe=07e61e6f8d) | Nov 02, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [2fe3e165eb](https://linux-hardware.org/?probe=2fe3e165eb) | Oct 31, 2020 |
| Dell          | Latitude E6220              | Notebook    | [b3af9d8439](https://linux-hardware.org/?probe=b3af9d8439) | Oct 30, 2020 |
| Dell          | Latitude E6220              | Notebook    | [7df244c05f](https://linux-hardware.org/?probe=7df244c05f) | Oct 30, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| Dell          | 0DR845                      | Desktop     | [958876c9d6](https://linux-hardware.org/?probe=958876c9d6) | Oct 27, 2020 |
| HP            | 843B                        | Desktop     | [cf9214c9e8](https://linux-hardware.org/?probe=cf9214c9e8) | Oct 25, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [dd6fd8b99c](https://linux-hardware.org/?probe=dd6fd8b99c) | Oct 24, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [da38172964](https://linux-hardware.org/?probe=da38172964) | Oct 24, 2020 |
| Positivo      | DH8BW01                     | All in one  | [b8c805b52b](https://linux-hardware.org/?probe=b8c805b52b) | Oct 23, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [bc2de7b987](https://linux-hardware.org/?probe=bc2de7b987) | Oct 23, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [c637e2732a](https://linux-hardware.org/?probe=c637e2732a) | Oct 22, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [ad50a3e36d](https://linux-hardware.org/?probe=ad50a3e36d) | Oct 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [d5b1adf1cc](https://linux-hardware.org/?probe=d5b1adf1cc) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [c00341fecd](https://linux-hardware.org/?probe=c00341fecd) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [83c0ae72b0](https://linux-hardware.org/?probe=83c0ae72b0) | Oct 21, 2020 |
| Unknown       | Unknown                     | Notebook    | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| MSI           | Z97 GAMING 3                | Desktop     | [d70dc5679f](https://linux-hardware.org/?probe=d70dc5679f) | Oct 15, 2020 |
| ASUSTek       | P7F-M                       | Desktop     | [a931f70b33](https://linux-hardware.org/?probe=a931f70b33) | Oct 14, 2020 |
| ASUSTek       | GL503VM                     | Notebook    | [a6705573f8](https://linux-hardware.org/?probe=a6705573f8) | Oct 11, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [27fe34d7e1](https://linux-hardware.org/?probe=27fe34d7e1) | Oct 09, 2020 |
| Acer          | Aspire 5680                 | Notebook    | [3ef4868294](https://linux-hardware.org/?probe=3ef4868294) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [e63d95d346](https://linux-hardware.org/?probe=e63d95d346) | Oct 07, 2020 |
| HP            | 304Ah                       | Desktop     | [720e05d59c](https://linux-hardware.org/?probe=720e05d59c) | Oct 04, 2020 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | Notebook    | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| HP            | 304Ah                       | Desktop     | [e8bf5f6700](https://linux-hardware.org/?probe=e8bf5f6700) | Oct 04, 2020 |
| Dell          | 0YDJK3 A05                  | Server      | [8ebb392ed7](https://linux-hardware.org/?probe=8ebb392ed7) | Oct 03, 2020 |
| Dell          | 0YDJK3 A05                  | Server      | [825a44fd4e](https://linux-hardware.org/?probe=825a44fd4e) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [ac6a6e6885](https://linux-hardware.org/?probe=ac6a6e6885) | Oct 03, 2020 |
| Unknown       | Unknown                     | Notebook    | [fd16de3c7f](https://linux-hardware.org/?probe=fd16de3c7f) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [7f6ed6799f](https://linux-hardware.org/?probe=7f6ed6799f) | Oct 03, 2020 |
| HP            | 304Ah                       | Desktop     | [298b55e06b](https://linux-hardware.org/?probe=298b55e06b) | Sep 28, 2020 |
| HP            | 304Ah                       | Desktop     | [5a86fa2901](https://linux-hardware.org/?probe=5a86fa2901) | Sep 28, 2020 |
| HP            | 304Ah                       | Desktop     | [e72550a43e](https://linux-hardware.org/?probe=e72550a43e) | Sep 28, 2020 |
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
| Lenovo        | Board                       | All in one  | [03b15c1544](https://linux-hardware.org/?probe=03b15c1544) | Jul 21, 2020 |
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
| Dell          | 0DR845                      | Desktop     | [9d1640a3a7](https://linux-hardware.org/?probe=9d1640a3a7) | Jun 20, 2020 |
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
| HP            | EliteBook 8540w             | Notebook    | [7846423802](https://linux-hardware.org/?probe=7846423802) | May 28, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [b36f5a9ddf](https://linux-hardware.org/?probe=b36f5a9ddf) | May 28, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [7f22ac48a8](https://linux-hardware.org/?probe=7f22ac48a8) | May 26, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [be86e3ea15](https://linux-hardware.org/?probe=be86e3ea15) | May 26, 2020 |
| HP            | Presario CQ61               | Notebook    | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Acer          | Aspire 7551                 | Notebook    | [d9c150f3ee](https://linux-hardware.org/?probe=d9c150f3ee) | May 24, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [aca1fb8ea1](https://linux-hardware.org/?probe=aca1fb8ea1) | May 21, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [ec868da9dd](https://linux-hardware.org/?probe=ec868da9dd) | May 20, 2020 |
| Acer          | Aspire 4830T                | Notebook    | [5494761310](https://linux-hardware.org/?probe=5494761310) | May 20, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [9c46a8ee24](https://linux-hardware.org/?probe=9c46a8ee24) | May 20, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [b7665aa8e1](https://linux-hardware.org/?probe=b7665aa8e1) | May 20, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [6ba5e37491](https://linux-hardware.org/?probe=6ba5e37491) | May 20, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [8e547a1414](https://linux-hardware.org/?probe=8e547a1414) | May 20, 2020 |
| Unknown       | Unknown                     | Desktop     | [cf5fe3dbce](https://linux-hardware.org/?probe=cf5fe3dbce) | May 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [4d4f673fb2](https://linux-hardware.org/?probe=4d4f673fb2) | May 16, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| Dell          | G3 3590                     | Notebook    | [6b37af517b](https://linux-hardware.org/?probe=6b37af517b) | May 12, 2020 |
| Toshiba       | Satellite U300              | Notebook    | [ef95fa82d7](https://linux-hardware.org/?probe=ef95fa82d7) | May 11, 2020 |
| HP            | G61                         | Notebook    | [7393752623](https://linux-hardware.org/?probe=7393752623) | May 11, 2020 |
| ASRock        | B75M R2.0                   | Desktop     | [efd3354b61](https://linux-hardware.org/?probe=efd3354b61) | May 10, 2020 |
| Dell          | Latitude E5570              | Notebook    | [1c8dda10a4](https://linux-hardware.org/?probe=1c8dda10a4) | May 08, 2020 |
| Toshiba       | Satellite U300              | Notebook    | [8859e175ba](https://linux-hardware.org/?probe=8859e175ba) | May 06, 2020 |
| Dell          | Latitude E5570              | Notebook    | [20fc42be1b](https://linux-hardware.org/?probe=20fc42be1b) | May 06, 2020 |
| Dell          | Inspiron N411Z              | Notebook    | [246dd5ce2a](https://linux-hardware.org/?probe=246dd5ce2a) | May 05, 2020 |
| Dell          | Latitude E5570              | Notebook    | [a1b049e54c](https://linux-hardware.org/?probe=a1b049e54c) | May 05, 2020 |
| Toshiba       | Satellite U300              | Notebook    | [3bd62e1a59](https://linux-hardware.org/?probe=3bd62e1a59) | May 05, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [1a79fa9925](https://linux-hardware.org/?probe=1a79fa9925) | May 03, 2020 |
| HP            | Laptop 15-bs2xx             | Notebook    | [6d47f83eac](https://linux-hardware.org/?probe=6d47f83eac) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [154605446a](https://linux-hardware.org/?probe=154605446a) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [e9544d771b](https://linux-hardware.org/?probe=e9544d771b) | May 02, 2020 |
| HP            | G42                         | Notebook    | [be1ea8571f](https://linux-hardware.org/?probe=be1ea8571f) | Apr 28, 2020 |
| Lenovo        | ThinkPad E490 20N80017RT    | Notebook    | [7f84d5a0f2](https://linux-hardware.org/?probe=7f84d5a0f2) | Apr 28, 2020 |
| HP            | G42                         | Notebook    | [e1ec91bd2e](https://linux-hardware.org/?probe=e1ec91bd2e) | Apr 27, 2020 |
| HP            | G42                         | Notebook    | [8ea8320eac](https://linux-hardware.org/?probe=8ea8320eac) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| Acer          | Aspire E1-572               | Notebook    | [e64e2fe71c](https://linux-hardware.org/?probe=e64e2fe71c) | Apr 23, 2020 |
| ASRock        | J4205-ITX                   | Desktop     | [4fc5d5a325](https://linux-hardware.org/?probe=4fc5d5a325) | Apr 22, 2020 |
| ECS           | Nettle2                     | Desktop     | [ababaf523c](https://linux-hardware.org/?probe=ababaf523c) | Apr 19, 2020 |
| Unknown       | Unknown                     | Desktop     | [12c198a6f5](https://linux-hardware.org/?probe=12c198a6f5) | Apr 18, 2020 |
| HP            | Laptop 15-bs2xx             | Notebook    | [477c5d9ffa](https://linux-hardware.org/?probe=477c5d9ffa) | Apr 17, 2020 |
| Positivo      | MOBILE                      | Notebook    | [c7cc7cd357](https://linux-hardware.org/?probe=c7cc7cd357) | Apr 17, 2020 |
| Positivo      | MOBILE                      | Notebook    | [55b84972df](https://linux-hardware.org/?probe=55b84972df) | Apr 17, 2020 |
| Unknown       | Unknown                     | Desktop     | [cc77c3c7c4](https://linux-hardware.org/?probe=cc77c3c7c4) | Apr 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [4d06bdc501](https://linux-hardware.org/?probe=4d06bdc501) | Apr 14, 2020 |
| Unknown       | Unknown                     | Notebook    | [d5bf1ee748](https://linux-hardware.org/?probe=d5bf1ee748) | Apr 14, 2020 |
| Unknown       | Unknown                     | Notebook    | [67167458d8](https://linux-hardware.org/?probe=67167458d8) | Apr 14, 2020 |
| Unknown       | Unknown                     | Desktop     | [5ca6d3f366](https://linux-hardware.org/?probe=5ca6d3f366) | Apr 14, 2020 |
| Unknown       | Unknown                     | Desktop     | [0d1b40e847](https://linux-hardware.org/?probe=0d1b40e847) | Apr 14, 2020 |
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

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 4.19.0-8-amd64       | 44        | 11.03%  |
| 4.19.0-16-amd64      | 41        | 10.28%  |
| 4.19.0-17-amd64      | 40        | 10.03%  |
| 4.19.0-18-amd64      | 35        | 8.77%   |
| 4.19.0-14-amd64      | 33        | 8.27%   |
| 4.19.0-13-amd64      | 30        | 7.52%   |
| 4.19.0-9-amd64       | 29        | 7.27%   |
| 4.19.0-10-amd64      | 21        | 5.26%   |
| 4.19.0-12-amd64      | 20        | 5.01%   |
| 4.19.0-17-686        | 16        | 4.01%   |
| 4.19.0-8-686         | 15        | 3.76%   |
| 4.19.0-16-686        | 14        | 3.51%   |
| 4.19.0-11-amd64      | 11        | 2.76%   |
| 4.19.0-13-686        | 9         | 2.26%   |
| 4.19.0-18-686        | 8         | 2.01%   |
| 4.19.0-14-686        | 6         | 1.5%    |
| 4.19.0-12-686        | 6         | 1.5%    |
| 5.4.0-0.bpo.4-amd64  | 3         | 0.75%   |
| 5.10.0-0.bpo.5-amd64 | 2         | 0.5%    |
| 4.19.0-9-686         | 2         | 0.5%    |
| 5.9.12-davius        | 1         | 0.25%   |
| 5.9.0-0.bpo.5-amd64  | 1         | 0.25%   |
| 5.8.0-3-amd64        | 1         | 0.25%   |
| 5.8.0-0.bpo.2-amd64  | 1         | 0.25%   |
| 5.6.0-2-amd64        | 1         | 0.25%   |
| 5.6.0-2-686-pae      | 1         | 0.25%   |
| 5.6.0-0.bpo.2-amd64  | 1         | 0.25%   |
| 5.4.44-xanmod1       | 1         | 0.25%   |
| 5.15.0-kali2-amd64   | 1         | 0.25%   |
| 5.10.0-7-amd64       | 1         | 0.25%   |
| 5.10.0-0.bpo.3-amd64 | 1         | 0.25%   |
| 4.19.0-14-686-pae    | 1         | 0.25%   |
| 4.19.0-12-rt-amd64   | 1         | 0.25%   |
| 4.19.0-10-686        | 1         | 0.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19.0  | 343       | 95.54%  |
| 5.10.0  | 4         | 1.11%   |
| 5.6.0   | 3         | 0.84%   |
| 5.4.0   | 3         | 0.84%   |
| 5.8.0   | 2         | 0.56%   |
| 5.9.12  | 1         | 0.28%   |
| 5.9.0   | 1         | 0.28%   |
| 5.4.44  | 1         | 0.28%   |
| 5.15.0  | 1         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 343       | 95.54%  |
| 5.4     | 4         | 1.11%   |
| 5.10    | 4         | 1.11%   |
| 5.6     | 3         | 0.84%   |
| 5.9     | 2         | 0.56%   |
| 5.8     | 2         | 0.56%   |
| 5.15    | 1         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 281       | 78.49%  |
| i686   | 77        | 21.51%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 326       | 90.3%   |
| Cinnamon   | 16        | 4.43%   |
| Unknown    | 7         | 1.94%   |
| MATE       | 4         | 1.11%   |
| XFCE       | 2         | 0.55%   |
| LXDE       | 2         | 0.55%   |
| Trinity    | 1         | 0.28%   |
| LXQt       | 1         | 0.28%   |
| KDE        | 1         | 0.28%   |
| GNOME      | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 358       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 322       | 89.69%  |
| TDM     | 20        | 5.57%   |
| LightDM | 15        | 4.18%   |
| GDM3    | 1         | 0.28%   |
| GDM     | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 100       | 27.78%  |
| pt_BR   | 40        | 11.11%  |
| de_DE   | 37        | 10.28%  |
| fr_FR   | 17        | 4.72%   |
| pl_PL   | 16        | 4.44%   |
| ru_RU   | 15        | 4.17%   |
| en_GB   | 15        | 4.17%   |
| it_IT   | 9         | 2.5%    |
| es_AR   | 9         | 2.5%    |
| en_AU   | 9         | 2.5%    |
| es_ES   | 8         | 2.22%   |
| en_CA   | 8         | 2.22%   |
| es_MX   | 6         | 1.67%   |
| de_CH   | 5         | 1.39%   |
| nl_BE   | 4         | 1.11%   |
| sv_SE   | 3         | 0.83%   |
| pt_PT   | 3         | 0.83%   |
| nl_NL   | 3         | 0.83%   |
| ja_JP   | 3         | 0.83%   |
| en_ZA   | 3         | 0.83%   |
| el_GR   | 3         | 0.83%   |
| de_AT   | 3         | 0.83%   |
| bg_BG   | 3         | 0.83%   |
| unm_US  | 2         | 0.56%   |
| uk_UA   | 2         | 0.56%   |
| tr_TR   | 2         | 0.56%   |
| sk_SK   | 2         | 0.56%   |
| hu_HU   | 2         | 0.56%   |
| et_EE   | 2         | 0.56%   |
| es_CL   | 2         | 0.56%   |
| en_PH   | 2         | 0.56%   |
| en_IN   | 2         | 0.56%   |
| cs_CZ   | 2         | 0.56%   |
| ca_ES   | 2         | 0.56%   |
| zh_CN   | 1         | 0.28%   |
| ru_UA   | 1         | 0.28%   |
| ro_RO   | 1         | 0.28%   |
| nb_NO   | 1         | 0.28%   |
| it_CH   | 1         | 0.28%   |
| hr_HR   | 1         | 0.28%   |
| fr_CA   | 1         | 0.28%   |
| fr_BE   | 1         | 0.28%   |
| fi_FI   | 1         | 0.28%   |
| es_UY   | 1         | 0.28%   |
| es_CO   | 1         | 0.28%   |
| en_SG   | 1         | 0.28%   |
| en_NZ   | 1         | 0.28%   |
| da_DK   | 1         | 0.28%   |
| ar_EG   | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 253       | 70.28%  |
| EFI  | 107       | 29.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 344       | 95.82%  |
| Btrfs   | 8         | 2.23%   |
| Tmpfs   | 3         | 0.84%   |
| Unknown | 2         | 0.56%   |
| Overlay | 1         | 0.28%   |
| Ext3    | 1         | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 316       | 87.78%  |
| GPT     | 26        | 7.22%   |
| MBR     | 18        | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 343       | 95.28%  |
| Yes       | 17        | 4.72%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 342       | 95.53%  |
| Yes       | 16        | 4.47%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 56        | 15.64%  |
| ASUSTek Computer               | 55        | 15.36%  |
| Dell                           | 41        | 11.45%  |
| Acer                           | 29        | 8.1%    |
| Lenovo                         | 28        | 7.82%   |
| MSI                            | 19        | 5.31%   |
| Gigabyte Technology            | 18        | 5.03%   |
| Unknown                        | 12        | 3.35%   |
| ASRock                         | 11        | 3.07%   |
| Toshiba                        | 10        | 2.79%   |
| Samsung Electronics            | 7         | 1.96%   |
| Intel                          | 6         | 1.68%   |
| Sony                           | 5         | 1.4%    |
| Positivo                       | 5         | 1.4%    |
| Fujitsu Siemens                | 5         | 1.4%    |
| LG Electronics                 | 4         | 1.12%   |
| ECS                            | 4         | 1.12%   |
| Apple                          | 3         | 0.84%   |
| Semp Toshiba                   | 2         | 0.56%   |
| Pegatron                       | 2         | 0.56%   |
| Packard Bell                   | 2         | 0.56%   |
| OEM                            | 2         | 0.56%   |
| Matsushita Electric Industrial | 2         | 0.56%   |
| Gateway                        | 2         | 0.56%   |
| Fujitsu                        | 2         | 0.56%   |
| EVGA                           | 2         | 0.56%   |
| Biostar                        | 2         | 0.56%   |
| Wistron                        | 1         | 0.28%   |
| TUXEDO                         | 1         | 0.28%   |
| Supermicro                     | 1         | 0.28%   |
| SAELITE                        | 1         | 0.28%   |
| Qbex                           | 1         | 0.28%   |
| PCWare                         | 1         | 0.28%   |
| NEC Computers                  | 1         | 0.28%   |
| Microsoft                      | 1         | 0.28%   |
| Medion                         | 1         | 0.28%   |
| Maibenben                      | 1         | 0.28%   |
| Itautec                        | 1         | 0.28%   |
| IBM                            | 1         | 0.28%   |
| HUAWEI                         | 1         | 0.28%   |
| Google                         | 1         | 0.28%   |
| Foxconn                        | 1         | 0.28%   |
| Exper                          | 1         | 0.28%   |
| Exo                            | 1         | 0.28%   |
| eMachines                      | 1         | 0.28%   |
| Digma                          | 1         | 0.28%   |
| DFI                            | 1         | 0.28%   |
| Alienware                      | 1         | 0.28%   |
| Advent                         | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 17        | 4.75%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 3         | 0.84%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 2         | 0.56%   |
| HP Pavilion dv6                             | 2         | 0.56%   |
| HP EliteBook 8540w                          | 2         | 0.56%   |
| Dell OptiPlex 780                           | 2         | 0.56%   |
| ASUS All Series                             | 2         | 0.56%   |
| Acer Aspire 5735                            | 2         | 0.56%   |
| Acer Aspire 3000                            | 2         | 0.56%   |
| Wistron ProLiant ML110 G5                   | 1         | 0.28%   |
| TUXEDO BC1510 1710                          | 1         | 0.28%   |
| Toshiba Satellite U300                      | 1         | 0.28%   |
| Toshiba Satellite P300                      | 1         | 0.28%   |
| Toshiba Satellite M100                      | 1         | 0.28%   |
| Toshiba Satellite L855                      | 1         | 0.28%   |
| Toshiba Satellite L750                      | 1         | 0.28%   |
| Toshiba Satellite L50-C                     | 1         | 0.28%   |
| Toshiba Satellite C50-A-1DN                 | 1         | 0.28%   |
| Toshiba Satellite A200                      | 1         | 0.28%   |
| Toshiba LX835                               | 1         | 0.28%   |
| Toshiba dynabook Satellite J61 173C/5       | 1         | 0.28%   |
| Supermicro X8DT3                            | 1         | 0.28%   |
| Sony VPCS131FM                              | 1         | 0.28%   |
| Sony VPCP116KG                              | 1         | 0.28%   |
| Sony VGN-FZ140E                             | 1         | 0.28%   |
| Sony VGN-AW41MF_H                           | 1         | 0.28%   |
| Sony SVE1511N1ESI                           | 1         | 0.28%   |
| Semp Toshiba STI                            | 1         | 0.28%   |
| Semp Toshiba NI 1403                        | 1         | 0.28%   |
| Samsung RV413/RV513                         | 1         | 0.28%   |
| Samsung R59/R60/R61                         | 1         | 0.28%   |
| Samsung NC10                                | 1         | 0.28%   |
| Samsung 305U1A                              | 1         | 0.28%   |
| SAELITE ES1AU11                             | 1         | 0.28%   |
| Qbex UDPAIOQBEX01                           | 1         | 0.28%   |
| Positivo W310CZ-T                           | 1         | 0.28%   |
| Positivo POS-EIH61CE                        | 1         | 0.28%   |
| Positivo MOBILE                             | 1         | 0.28%   |
| Positivo H14CU01                            | 1         | 0.28%   |
| Positivo DH8BW01                            | 1         | 0.28%   |
| Pegatron Elite 7300 Series MT               | 1         | 0.28%   |
| Pegatron 520-1188la                         | 1         | 0.28%   |
| PCWare IPMH81G1                             | 1         | 0.28%   |
| Packard Bell EasyNote_NJ66                  | 1         | 0.28%   |
| Packard Bell EasyNote TE69BM                | 1         | 0.28%   |
| OEM 45CMX/45GMX/45CMX-K                     | 1         | 0.28%   |
| NEC Computers IMEDIA S9509                  | 1         | 0.28%   |
| MSI PX714AA-ABH t3040.nl                    | 1         | 0.28%   |
| MSI MS-7C52                                 | 1         | 0.28%   |
| MSI MS-7C51                                 | 1         | 0.28%   |
| MSI MS-7A40                                 | 1         | 0.28%   |
| MSI MS-7918                                 | 1         | 0.28%   |
| MSI MS-7850                                 | 1         | 0.28%   |
| MSI MS-7823                                 | 1         | 0.28%   |
| MSI MS-7817                                 | 1         | 0.28%   |
| MSI MS-7815                                 | 1         | 0.28%   |
| MSI MS-7751                                 | 1         | 0.28%   |
| MSI MS-7383                                 | 1         | 0.28%   |
| MSI MS-7267                                 | 1         | 0.28%   |
| MSI MS-7142                                 | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 25        | 6.98%   |
| Unknown                 | 17        | 4.75%   |
| Lenovo ThinkPad         | 13        | 3.63%   |
| Dell Inspiron           | 13        | 3.63%   |
| HP Pavilion             | 12        | 3.35%   |
| Dell Latitude           | 11        | 3.07%   |
| HP Compaq               | 10        | 2.79%   |
| Toshiba Satellite       | 8         | 2.23%   |
| Dell OptiPlex           | 8         | 2.23%   |
| HP Laptop               | 6         | 1.68%   |
| Lenovo IdeaPad          | 5         | 1.4%    |
| HP EliteBook            | 5         | 1.4%    |
| Dell Precision          | 5         | 1.4%    |
| ASUS PRIME              | 4         | 1.12%   |
| Samsung RV411           | 3         | 0.84%   |
| Fujitsu Siemens ESPRIMO | 3         | 0.84%   |
| Packard Bell EasyNote   | 2         | 0.56%   |
| Lenovo ThinkCentre      | 2         | 0.56%   |
| HP Presario             | 2         | 0.56%   |
| Gigabyte Z390           | 2         | 0.56%   |
| Gigabyte X570           | 2         | 0.56%   |
| ASUS ROG                | 2         | 0.56%   |
| ASUS P5KPL-AM           | 2         | 0.56%   |
| ASUS All                | 2         | 0.56%   |
| Apple MacBookPro5       | 2         | 0.56%   |
| Acer Veriton            | 2         | 0.56%   |
| Wistron ProLiant        | 1         | 0.28%   |
| TUXEDO BC1510           | 1         | 0.28%   |
| Toshiba LX835           | 1         | 0.28%   |
| Toshiba dynabook        | 1         | 0.28%   |
| Supermicro X8DT3        | 1         | 0.28%   |
| Sony VPCS131FM          | 1         | 0.28%   |
| Sony VPCP116KG          | 1         | 0.28%   |
| Sony VGN-FZ140E         | 1         | 0.28%   |
| Sony VGN-AW41MF         | 1         | 0.28%   |
| Sony SVE1511N1ESI       | 1         | 0.28%   |
| Semp Toshiba STI        | 1         | 0.28%   |
| Semp Toshiba NI         | 1         | 0.28%   |
| Samsung RV413           | 1         | 0.28%   |
| Samsung R59             | 1         | 0.28%   |
| Samsung NC10            | 1         | 0.28%   |
| Samsung 305U1A          | 1         | 0.28%   |
| SAELITE ES1AU11         | 1         | 0.28%   |
| Qbex UDPAIOQBEX01       | 1         | 0.28%   |
| Positivo W310CZ-T       | 1         | 0.28%   |
| Positivo POS-EIH61CE    | 1         | 0.28%   |
| Positivo MOBILE         | 1         | 0.28%   |
| Positivo H14CU01        | 1         | 0.28%   |
| Positivo DH8BW01        | 1         | 0.28%   |
| Pegatron Elite          | 1         | 0.28%   |
| Pegatron 520-1188la     | 1         | 0.28%   |
| PCWare IPMH81G1         | 1         | 0.28%   |
| OEM 45CMX               | 1         | 0.28%   |
| NEC Computers IMEDIA    | 1         | 0.28%   |
| MSI PX714AA-ABH         | 1         | 0.28%   |
| MSI MS-7C52             | 1         | 0.28%   |
| MSI MS-7C51             | 1         | 0.28%   |
| MSI MS-7A40             | 1         | 0.28%   |
| MSI MS-7918             | 1         | 0.28%   |
| MSI MS-7850             | 1         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 37        | 10.34%  |
| 2009    | 35        | 9.78%   |
| 2010    | 32        | 8.94%   |
| 2011    | 30        | 8.38%   |
| 2007    | 30        | 8.38%   |
| 2008    | 28        | 7.82%   |
| 2018    | 25        | 6.98%   |
| 2014    | 25        | 6.98%   |
| 2013    | 21        | 5.87%   |
| 2019    | 20        | 5.59%   |
| 2016    | 13        | 3.63%   |
| 2006    | 13        | 3.63%   |
| 2017    | 11        | 3.07%   |
| 2015    | 11        | 3.07%   |
| 2020    | 10        | 2.79%   |
| 2005    | 9         | 2.51%   |
| 2003    | 4         | 1.12%   |
| 2004    | 2         | 0.56%   |
| 2021    | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 204       | 56.98%  |
| Desktop     | 138       | 38.55%  |
| All in one  | 6         | 1.68%   |
| Tablet      | 3         | 0.84%   |
| Convertible | 3         | 0.84%   |
| Server      | 3         | 0.84%   |
| Mini pc     | 1         | 0.28%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 346       | 96.38%  |
| Enabled  | 13        | 3.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 357       | 99.72%  |
| Yes  | 1         | 0.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 102       | 28.18%  |
| 4.01-8.0    | 58        | 16.02%  |
| 8.01-16.0   | 49        | 13.54%  |
| 16.01-24.0  | 47        | 12.98%  |
| 2.01-3.0    | 43        | 11.88%  |
| 1.01-2.0    | 35        | 9.67%   |
| 32.01-64.0  | 12        | 3.31%   |
| 0.51-1.0    | 12        | 3.31%   |
| 24.01-32.0  | 2         | 0.55%   |
| 64.01-256.0 | 2         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 189       | 49.35%  |
| 0.51-1.0  | 70        | 18.28%  |
| 2.01-3.0  | 69        | 18.02%  |
| 3.01-4.0  | 33        | 8.62%   |
| 4.01-8.0  | 16        | 4.18%   |
| 8.01-16.0 | 3         | 0.78%   |
| 0.01-0.5  | 3         | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 223       | 60.76%  |
| 2      | 97        | 26.43%  |
| 3      | 22        | 5.99%   |
| 4      | 10        | 2.72%   |
| 7      | 5         | 1.36%   |
| 0      | 4         | 1.09%   |
| 5      | 3         | 0.82%   |
| 6      | 2         | 0.54%   |
| 8      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 58.95%  |
| No        | 149       | 41.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 342       | 95.53%  |
| No        | 16        | 4.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 268       | 74.24%  |
| No        | 93        | 25.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 209       | 58.22%  |
| Yes       | 150       | 41.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country             | Computers | Percent |
|---------------------|-----------|---------|
| USA                 | 47        | 13.13%  |
| Germany             | 42        | 11.73%  |
| Brazil              | 41        | 11.45%  |
| France              | 16        | 4.47%   |
| UK                  | 14        | 3.91%   |
| Poland              | 14        | 3.91%   |
| Canada              | 12        | 3.35%   |
| Spain               | 11        | 3.07%   |
| Italy               | 11        | 3.07%   |
| Netherlands         | 10        | 2.79%   |
| Russia              | 9         | 2.51%   |
| Bulgaria            | 9         | 2.51%   |
| Australia           | 9         | 2.51%   |
| Argentina           | 9         | 2.51%   |
| Ukraine             | 8         | 2.23%   |
| Mexico              | 7         | 1.96%   |
| Switzerland         | 6         | 1.68%   |
| Austria             | 5         | 1.4%    |
| Portugal            | 4         | 1.12%   |
| Philippines         | 4         | 1.12%   |
| India               | 4         | 1.12%   |
| Greece              | 4         | 1.12%   |
| Belgium             | 4         | 1.12%   |
| Turkey              | 3         | 0.84%   |
| Sweden              | 3         | 0.84%   |
| South Africa        | 3         | 0.84%   |
| Romania             | 3         | 0.84%   |
| Belarus             | 3         | 0.84%   |
| Bahrain             | 3         | 0.84%   |
| Tunisia             | 2         | 0.56%   |
| Luxembourg          | 2         | 0.56%   |
| Japan               | 2         | 0.56%   |
| Indonesia           | 2         | 0.56%   |
| Hungary             | 2         | 0.56%   |
| Finland             | 2         | 0.56%   |
| Estonia             | 2         | 0.56%   |
| Egypt               | 2         | 0.56%   |
| Czechia             | 2         | 0.56%   |
| Croatia             | 2         | 0.56%   |
| China               | 2         | 0.56%   |
| Chile               | 2         | 0.56%   |
| Bangladesh          | 2         | 0.56%   |
| Venezuela           | 1         | 0.28%   |
| Uruguay             | 1         | 0.28%   |
| Trinidad and Tobago | 1         | 0.28%   |
| Slovakia            | 1         | 0.28%   |
| Singapore           | 1         | 0.28%   |
| Serbia              | 1         | 0.28%   |
| Puerto Rico         | 1         | 0.28%   |
| Norway              | 1         | 0.28%   |
| New Zealand         | 1         | 0.28%   |
| Ireland             | 1         | 0.28%   |
| Honduras            | 1         | 0.28%   |
| Dominican Republic  | 1         | 0.28%   |
| Denmark             | 1         | 0.28%   |
| Colombia            | 1         | 0.28%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 6         | 1.59%   |
| Zurich            | 5         | 1.33%   |
| Sofia             | 5         | 1.33%   |
| Poznan            | 4         | 1.06%   |
| Perth             | 4         | 1.06%   |
| Frankfurt am Main | 4         | 1.06%   |
| Wroclaw           | 3         | 0.8%    |
| Seville           | 3         | 0.8%    |
| S??o Paulo        | 3         | 0.8%    |
| Rio de Janeiro    | 3         | 0.8%    |
| Manama            | 3         | 0.8%    |
| Cape Town         | 3         | 0.8%    |
| Athens            | 3         | 0.8%    |
| Warsaw            | 2         | 0.53%   |
| Toronto           | 2         | 0.53%   |
| The Hague         | 2         | 0.53%   |
| São Paulo        | 2         | 0.53%   |
| São Luís        | 2         | 0.53%   |
| Sydney            | 2         | 0.53%   |
| Santa Rosa        | 2         | 0.53%   |
| Rapla             | 2         | 0.53%   |
| Plovdiv           | 2         | 0.53%   |
| Penhold           | 2         | 0.53%   |
| Moscow            | 2         | 0.53%   |
| Montreal          | 2         | 0.53%   |
| Milan             | 2         | 0.53%   |
| Marburg           | 2         | 0.53%   |
| Manila            | 2         | 0.53%   |
| Madrid            | 2         | 0.53%   |
| Kyiv              | 2         | 0.53%   |
| Helsinki          | 2         | 0.53%   |
| Hamburg           | 2         | 0.53%   |
| Goiânia          | 2         | 0.53%   |
| Foz do Iguaçu    | 2         | 0.53%   |
| Florian??polis    | 2         | 0.53%   |
| Dhaka             | 2         | 0.53%   |
| Denver            | 2         | 0.53%   |
| Cologne           | 2         | 0.53%   |
| Buenos Aires      | 2         | 0.53%   |
| Berlin            | 2         | 0.53%   |
| Belo Horizonte    | 2         | 0.53%   |
| Barcelona         | 2         | 0.53%   |
| Angeles City      | 2         | 0.53%   |
| Zhukovskiy        | 1         | 0.27%   |
| Zhongshan         | 1         | 0.27%   |
| Zapopan           | 1         | 0.27%   |
| Zagreb            | 1         | 0.27%   |
| Yokohama          | 1         | 0.27%   |
| Yevpatoriya       | 1         | 0.27%   |
| Yan'anshi         | 1         | 0.27%   |
| Yampil            | 1         | 0.27%   |
| Yalta             | 1         | 0.27%   |
| Wünnenberg       | 1         | 0.27%   |
| Wolfsburg         | 1         | 0.27%   |
| Whittier          | 1         | 0.27%   |
| Wernberg-Koblitz  | 1         | 0.27%   |
| Wellington        | 1         | 0.27%   |
| Weatherford       | 1         | 0.27%   |
| Washington        | 1         | 0.27%   |
| Wankheim          | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 96        | 141    | 19.35%  |
| Seagate             | 81        | 125    | 16.33%  |
| Samsung Electronics | 74        | 97     | 14.92%  |
| Toshiba             | 30        | 38     | 6.05%   |
| Hitachi             | 30        | 33     | 6.05%   |
| Kingston            | 23        | 28     | 4.64%   |
| Unknown             | 20        | 24     | 4.03%   |
| SanDisk             | 16        | 23     | 3.23%   |
| Crucial             | 16        | 20     | 3.23%   |
| Intel               | 10        | 11     | 2.02%   |
| HGST                | 10        | 10     | 2.02%   |
| Phison              | 8         | 10     | 1.61%   |
| Fujitsu             | 7         | 7      | 1.41%   |
| China               | 6         | 6      | 1.21%   |
| A-DATA Technology   | 6         | 6      | 1.21%   |
| SK Hynix            | 5         | 9      | 1.01%   |
| Intenso             | 5         | 6      | 1.01%   |
| Micron Technology   | 4         | 4      | 0.81%   |
| Transcend           | 3         | 3      | 0.6%    |
| OCZ                 | 3         | 4      | 0.6%    |
| MAXTOR              | 3         | 5      | 0.6%    |
| KingSpec            | 3         | 4      | 0.6%    |
| GOODRAM             | 3         | 3      | 0.6%    |
| TCSUNBOW            | 2         | 2      | 0.4%    |
| Patriot             | 2         | 4      | 0.4%    |
| Mushkin             | 2         | 2      | 0.4%    |
| KingDian            | 2         | 4      | 0.4%    |
| IBM/Hitachi         | 2         | 2      | 0.4%    |
| Hewlett-Packard     | 2         | 3      | 0.4%    |
| Gigabyte Technology | 2         | 3      | 0.4%    |
| USB30               | 1         | 2      | 0.2%    |
| Team                | 1         | 2      | 0.2%    |
| Silicon Motion      | 1         | 1      | 0.2%    |
| SABRENT             | 1         | 1      | 0.2%    |
| PNY                 | 1         | 1      | 0.2%    |
| Netac               | 1         | 1      | 0.2%    |
| Kingmax             | 1         | 1      | 0.2%    |
| KESU                | 1         | 2      | 0.2%    |
| JMicron             | 1         | 2      | 0.2%    |
| HUAWEI              | 1         | 1      | 0.2%    |
| HPE                 | 1         | 5      | 0.2%    |
| Hikvision           | 1         | 1      | 0.2%    |
| GALAX               | 1         | 1      | 0.2%    |
| FORESEE             | 1         | 1      | 0.2%    |
| ExcelStor           | 1         | 1      | 0.2%    |
| DREVO               | 1         | 1      | 0.2%    |
| Dogfish             | 1         | 1      | 0.2%    |
| DAS                 | 1         | 4      | 0.2%    |
| CORSAIR             | 1         | 1      | 0.2%    |
| BAITITON            | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB           | 9         | 1.66%   |
| Unknown MMC Card  32GB              | 5         | 0.92%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 0.92%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 4         | 0.74%   |
| Toshiba MQ01ABD100 1TB              | 4         | 0.74%   |
| Toshiba DT01ACA100 1TB              | 4         | 0.74%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 0.74%   |
| Seagate Expansion 1TB               | 4         | 0.74%   |
| Samsung SSD 860 EVO 1TB             | 4         | 0.74%   |
| Samsung SSD 850 EVO 500GB           | 4         | 0.74%   |
| Samsung SSD 850 EVO 250GB           | 4         | 0.74%   |
| Kingston SA400S37120G 120GB SSD     | 4         | 0.74%   |
| Crucial CT240BX500SSD1 240GB        | 4         | 0.74%   |
| WDC WD3200BEVT-60ZCT1 320GB         | 3         | 0.55%   |
| Unknown SD/MMC/MS PRO 128GB         | 3         | 0.55%   |
| Unknown MMC Card  7GB               | 3         | 0.55%   |
| Unknown MMC Card  128GB             | 3         | 0.55%   |
| Seagate ST9500325AS 500GB           | 3         | 0.55%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.55%   |
| Samsung HD322HJ 320GB               | 3         | 0.55%   |
| Samsung HD103SJ 1TB                 | 3         | 0.55%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 3         | 0.55%   |
| Kingston SV300S37A120G 120GB SSD    | 3         | 0.55%   |
| Kingston SA400S37480G 480GB SSD     | 3         | 0.55%   |
| Hitachi HTS545032B9A300 320GB       | 3         | 0.55%   |
| China SATA SSD 120GB                | 3         | 0.55%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2         | 0.37%   |
| WDC WD7500BPVT-75HXZT3 752GB        | 2         | 0.37%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 2         | 0.37%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2         | 0.37%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 0.37%   |
| WDC WD3200AAKS-00L9A0 320GB         | 2         | 0.37%   |
| WDC WD2500BEVT-22ZCT0 250GB         | 2         | 0.37%   |
| WDC WD2500AAKX-753CA1 250GB         | 2         | 0.37%   |
| WDC WD1600AABS-00PRA0 160GB         | 2         | 0.37%   |
| WDC WD1200BEVS-22UST0 120GB         | 2         | 0.37%   |
| WDC WD10EZEX-60WN4A0 1TB            | 2         | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 0.37%   |
| WDC WD10EZEX-08M2NA0 1TB            | 2         | 0.37%   |
| Unknown MMC Card  64GB              | 2         | 0.37%   |
| Unknown MMC Card  16GB              | 2         | 0.37%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.37%   |
| Toshiba MQ01ABD032 320GB            | 2         | 0.37%   |
| Seagate ST9250315AS 250GB           | 2         | 0.37%   |
| Seagate ST9120821AS 120GB           | 2         | 0.37%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 0.37%   |
| Seagate ST2000LX001-1RG174 2TB      | 2         | 0.37%   |
| Seagate ST2000DM001-9YN164 2TB      | 2         | 0.37%   |
| Seagate ST2000DM001-1ER164 2TB      | 2         | 0.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.37%   |
| Sandisk NVMe SSD Drive 256GB        | 2         | 0.37%   |
| Samsung SP0802N 80GB                | 2         | 0.37%   |
| Samsung NVMe SSD Drive 500GB        | 2         | 0.37%   |
| Samsung NVMe SSD Drive 2TB          | 2         | 0.37%   |
| Samsung NVMe SSD Drive 256GB        | 2         | 0.37%   |
| Samsung HD161HJ 160GB               | 2         | 0.37%   |
| Phison NVMe SSD Drive 500GB         | 2         | 0.37%   |
| Phison NVMe SSD Drive 256GB         | 2         | 0.37%   |
| Kingston SV300S37A240G 240GB SSD    | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 86        | 130    | 31.5%   |
| Seagate             | 81        | 125    | 29.67%  |
| Hitachi             | 30        | 33     | 10.99%  |
| Samsung Electronics | 25        | 33     | 9.16%   |
| Toshiba             | 24        | 27     | 8.79%   |
| HGST                | 10        | 10     | 3.66%   |
| Fujitsu             | 7         | 7      | 2.56%   |
| Unknown             | 3         | 3      | 1.1%    |
| MAXTOR              | 3         | 5      | 1.1%    |
| IBM/Hitachi         | 2         | 2      | 0.73%   |
| KESU                | 1         | 2      | 0.37%   |
| HPE                 | 1         | 5      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 52     | 25%     |
| Kingston            | 21        | 26     | 11.93%  |
| Crucial             | 16        | 20     | 9.09%   |
| SanDisk             | 13        | 20     | 7.39%   |
| WDC                 | 10        | 10     | 5.68%   |
| Intel               | 7         | 7      | 3.98%   |
| Toshiba             | 6         | 11     | 3.41%   |
| China               | 6         | 6      | 3.41%   |
| A-DATA Technology   | 6         | 6      | 3.41%   |
| Micron Technology   | 4         | 4      | 2.27%   |
| Intenso             | 4         | 5      | 2.27%   |
| Transcend           | 3         | 3      | 1.7%    |
| OCZ                 | 3         | 4      | 1.7%    |
| GOODRAM             | 3         | 3      | 1.7%    |
| Unknown             | 2         | 2      | 1.14%   |
| TCSUNBOW            | 2         | 2      | 1.14%   |
| SK Hynix            | 2         | 4      | 1.14%   |
| Patriot             | 2         | 4      | 1.14%   |
| KingSpec            | 2         | 3      | 1.14%   |
| KingDian            | 2         | 4      | 1.14%   |
| Hewlett-Packard     | 2         | 3      | 1.14%   |
| Gigabyte Technology | 2         | 3      | 1.14%   |
| USB30               | 1         | 2      | 0.57%   |
| Team                | 1         | 2      | 0.57%   |
| SABRENT             | 1         | 1      | 0.57%   |
| PNY                 | 1         | 1      | 0.57%   |
| Netac               | 1         | 1      | 0.57%   |
| Mushkin             | 1         | 1      | 0.57%   |
| Kingmax             | 1         | 1      | 0.57%   |
| Hikvision           | 1         | 1      | 0.57%   |
| GALAX               | 1         | 1      | 0.57%   |
| FORESEE             | 1         | 1      | 0.57%   |
| DREVO               | 1         | 1      | 0.57%   |
| Dogfish             | 1         | 1      | 0.57%   |
| CORSAIR             | 1         | 1      | 0.57%   |
| BAITITON            | 1         | 1      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 235       | 382    | 54.02%  |
| SSD     | 149       | 218    | 34.25%  |
| NVMe    | 29        | 39     | 6.67%   |
| MMC     | 16        | 19     | 3.68%   |
| Unknown | 6         | 10     | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 336       | 570    | 82.96%  |
| NVMe | 29        | 39     | 7.16%   |
| SAS  | 24        | 40     | 5.93%   |
| MMC  | 16        | 19     | 3.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 287       | 437    | 72.11%  |
| 0.51-1.0   | 81        | 116    | 20.35%  |
| 1.01-2.0   | 19        | 27     | 4.77%   |
| 4.01-10.0  | 5         | 8      | 1.26%   |
| 3.01-4.0   | 4         | 10     | 1.01%   |
| 2.01-3.0   | 2         | 2      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 141       | 38.11%  |
| 251-500        | 82        | 22.16%  |
| 501-1000       | 36        | 9.73%   |
| 51-100         | 33        | 8.92%   |
| 1001-2000      | 25        | 6.76%   |
| More than 3000 | 21        | 5.68%   |
| 21-50          | 19        | 5.14%   |
| 2001-3000      | 10        | 2.7%    |
| 1-20           | 2         | 0.54%   |
| Unknown        | 1         | 0.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 160       | 41.45%  |
| 21-50          | 84        | 21.76%  |
| 101-250        | 42        | 10.88%  |
| 51-100         | 41        | 10.62%  |
| 251-500        | 16        | 4.15%   |
| 501-1000       | 14        | 3.63%   |
| 1001-2000      | 12        | 3.11%   |
| More than 3000 | 9         | 2.33%   |
| 2001-3000      | 7         | 1.81%   |
| Unknown        | 1         | 0.26%   |

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
| Detected | 319       | 596    | 87.88%  |
| Works    | 34        | 62     | 9.37%   |
| Malfunc  | 10        | 10     | 2.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 265       | 65.27%  |
| AMD                              | 56        | 13.79%  |
| Nvidia                           | 17        | 4.19%   |
| Samsung Electronics              | 9         | 2.22%   |
| ASMedia Technology               | 9         | 2.22%   |
| Silicon Integrated Systems [SiS] | 8         | 1.97%   |
| Phison Electronics               | 8         | 1.97%   |
| JMicron Technology               | 8         | 1.97%   |
| VIA Technologies                 | 6         | 1.48%   |
| Sandisk                          | 4         | 0.99%   |
| Marvell Technology Group         | 4         | 0.99%   |
| SK Hynix                         | 3         | 0.74%   |
| Silicon Motion                   | 2         | 0.49%   |
| Kingston Technology Company      | 2         | 0.49%   |
| Broadcom / LSI                   | 2         | 0.49%   |
| Toshiba America Info Systems     | 1         | 0.25%   |
| Silicon Image                    | 1         | 0.25%   |
| LSI Logic / Symbios Logic        | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 30        | 5.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 24        | 4.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 17        | 3.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 2.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 15        | 2.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 15        | 2.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 2.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 2.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13        | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12        | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 10        | 1.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 10        | 1.94%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 10        | 1.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 1.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 10        | 1.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.74%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9         | 1.74%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 7         | 1.36%   |
| Nvidia MCP61 SATA Controller                                                            | 7         | 1.36%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7         | 1.36%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 7         | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 1.36%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 6         | 1.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 1.16%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.16%   |
| Phison E12 NVMe Controller                                                              | 5         | 0.97%   |
| Nvidia MCP61 IDE                                                                        | 5         | 0.97%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 0.97%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5         | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 0.97%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 0.97%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 4         | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4         | 0.78%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                              | 4         | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4         | 0.78%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4         | 0.78%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4         | 0.78%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 4         | 0.78%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3         | 0.58%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.58%   |
| Sandisk Non-Volatile memory controller                                                  | 3         | 0.58%   |
| JMicron JMB368 IDE controller                                                           | 3         | 0.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 0.58%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.58%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3         | 0.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 3         | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.58%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 3         | 0.58%   |
| AMD SB600 IDE                                                                           | 3         | 0.58%   |
| AMD IXP SB4x0 IDE Controller                                                            | 3         | 0.58%   |
| AMD FCH SATA Controller D                                                               | 3         | 0.58%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 250       | 57.87%  |
| IDE  | 127       | 29.4%   |
| NVMe | 30        | 6.94%   |
| RAID | 21        | 4.86%   |
| SAS  | 2         | 0.46%   |
| SCSI | 2         | 0.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 282       | 78.77%  |
| AMD    | 76        | 21.23%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU T6600 @ 2.20GHz         | 5         | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz            | 4         | 1.12%   |
| Intel Core i3-8100 CPU @ 3.60GHz             | 4         | 1.12%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 4         | 1.12%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 4         | 1.12%   |
| Intel Atom CPU N270 @ 1.60GHz                | 4         | 1.12%   |
| Intel Atom CPU N2600 @ 1.60GHz               | 4         | 1.12%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 3         | 0.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 3         | 0.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 3         | 0.84%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 3         | 0.84%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 3         | 0.84%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz         | 3         | 0.84%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz         | 3         | 0.84%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz         | 3         | 0.84%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz         | 3         | 0.84%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 3         | 0.84%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz  | 2         | 0.56%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 2         | 0.56%   |
| Intel Pentium D CPU 2.80GHz                  | 2         | 0.56%   |
| Intel Pentium CPU P6100 @ 2.00GHz            | 2         | 0.56%   |
| Intel Pentium CPU G645 @ 2.90GHz             | 2         | 0.56%   |
| Intel Pentium CPU G2030 @ 3.00GHz            | 2         | 0.56%   |
| Intel Genuine CPU T2300 @ 1.66GHz            | 2         | 0.56%   |
| Intel Genuine CPU T2130 @ 1.86GHz            | 2         | 0.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz            | 2         | 0.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 0.56%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz           | 2         | 0.56%   |
| Intel Core i7-4770K CPU @ 3.50GHz            | 2         | 0.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz           | 2         | 0.56%   |
| Intel Core i7-2600 CPU @ 3.40GHz             | 2         | 0.56%   |
| Intel Core i7 CPU M 620 @ 2.67GHz            | 2         | 0.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz            | 2         | 0.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 0.56%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 2         | 0.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 2         | 0.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 2         | 0.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 2         | 0.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 2         | 0.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz             | 2         | 0.56%   |
| Intel Core i5 CPU 750 @ 2.67GHz              | 2         | 0.56%   |
| Intel Core i5 CPU 650 @ 3.20GHz              | 2         | 0.56%   |
| Intel Core i3-8145U CPU @ 2.10GHz            | 2         | 0.56%   |
| Intel Core i3-8130U CPU @ 2.20GHz            | 2         | 0.56%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 2         | 0.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz            | 2         | 0.56%   |
| Intel Core i3-2370M CPU @ 2.40GHz            | 2         | 0.56%   |
| Intel Core i3-2120 CPU @ 3.30GHz             | 2         | 0.56%   |
| Intel Core i3-2100 CPU @ 3.10GHz             | 2         | 0.56%   |
| Intel Core Duo CPU T2400 @ 1.83GHz           | 2         | 0.56%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz        | 2         | 0.56%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz        | 2         | 0.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz         | 2         | 0.56%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz         | 2         | 0.56%   |
| Intel Core 2 CPU T5600 @ 1.83GHz             | 2         | 0.56%   |
| Intel Celeron N4000 CPU @ 1.10GHz            | 2         | 0.56%   |
| Intel Celeron CPU 900 @ 2.20GHz              | 2         | 0.56%   |
| AMD Sempron Processor 3200+                  | 2         | 0.56%   |
| AMD Sempron Processor 3000+                  | 2         | 0.56%   |
| AMD Ryzen 7 3700X 8-Core Processor           | 2         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 48        | 13.41%  |
| Intel Core i7                  | 47        | 13.13%  |
| Intel Core 2 Duo               | 38        | 10.61%  |
| Intel Core i3                  | 30        | 8.38%   |
| Intel Celeron                  | 24        | 6.7%    |
| Intel Atom                     | 17        | 4.75%   |
| Intel Pentium                  | 15        | 4.19%   |
| Intel Core 2 Quad              | 9         | 2.51%   |
| Intel Xeon                     | 8         | 2.23%   |
| Intel Core 2                   | 8         | 2.23%   |
| AMD Ryzen 5                    | 8         | 2.23%   |
| Intel Pentium Dual-Core        | 7         | 1.96%   |
| Intel Pentium Dual             | 7         | 1.96%   |
| Intel Genuine                  | 7         | 1.96%   |
| Other                          | 6         | 1.68%   |
| AMD Sempron                    | 6         | 1.68%   |
| AMD Ryzen 7                    | 6         | 1.68%   |
| AMD Athlon 64 X2               | 5         | 1.4%    |
| Intel Pentium M                | 4         | 1.12%   |
| AMD FX                         | 4         | 1.12%   |
| AMD A4                         | 4         | 1.12%   |
| Intel Pentium D                | 3         | 0.84%   |
| Intel Pentium 4                | 3         | 0.84%   |
| Intel Core Duo                 | 3         | 0.84%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.84%   |
| AMD Phenom II X4               | 3         | 0.84%   |
| AMD Athlon XP                  | 3         | 0.84%   |
| Intel Core i9                  | 2         | 0.56%   |
| AMD Ryzen 3                    | 2         | 0.56%   |
| AMD Phenom II X6               | 2         | 0.56%   |
| AMD Mobile Sempron             | 2         | 0.56%   |
| AMD E2                         | 2         | 0.56%   |
| AMD E                          | 2         | 0.56%   |
| AMD Athlon II X4               | 2         | 0.56%   |
| AMD Athlon II                  | 2         | 0.56%   |
| AMD Athlon                     | 2         | 0.56%   |
| AMD A8                         | 2         | 0.56%   |
| Intel Mobile Pentium 4         | 1         | 0.28%   |
| Intel Core m5                  | 1         | 0.28%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.28%   |
| AMD Turion 64 Mobile           | 1         | 0.28%   |
| AMD Ryzen 9                    | 1         | 0.28%   |
| AMD Ryzen 5 PRO                | 1         | 0.28%   |
| AMD Phenom II                  | 1         | 0.28%   |
| AMD E1                         | 1         | 0.28%   |
| AMD Athlon Neo                 | 1         | 0.28%   |
| AMD Athlon II X2               | 1         | 0.28%   |
| AMD A6                         | 1         | 0.28%   |
| AMD A10                        | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 201       | 55.99%  |
| 4      | 93        | 25.91%  |
| 1      | 42        | 11.7%   |
| 6      | 9         | 2.51%   |
| 8      | 8         | 2.23%   |
| 12     | 3         | 0.84%   |
| 16     | 1         | 0.28%   |
| 10     | 1         | 0.28%   |
| 3      | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 354       | 98.88%  |
| 2      | 4         | 1.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 198       | 55.31%  |
| 2      | 160       | 44.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 322       | 89.94%  |
| 32-bit         | 36        | 10.06%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 9.67%   |
| 0x1067a    | 31        | 8.56%   |
| 0x206a7    | 29        | 8.01%   |
| 0x306a9    | 23        | 6.35%   |
| 0x306c3    | 17        | 4.7%    |
| 0x6fd      | 15        | 4.14%   |
| 0x20655    | 10        | 2.76%   |
| 0x40651    | 9         | 2.49%   |
| 0x106c2    | 9         | 2.49%   |
| 0x406e3    | 8         | 2.21%   |
| 0x06006705 | 8         | 2.21%   |
| 0x010000c8 | 7         | 1.93%   |
| 0x6f6      | 6         | 1.66%   |
| 0x6ec      | 6         | 1.66%   |
| 0x10676    | 6         | 1.66%   |
| 0x806ea    | 5         | 1.38%   |
| 0x506e3    | 5         | 1.38%   |
| 0x30678    | 5         | 1.38%   |
| 0x30661    | 5         | 1.38%   |
| 0x106e5    | 5         | 1.38%   |
| 0x10677    | 5         | 1.38%   |
| 0x906eb    | 4         | 1.1%    |
| 0x806e9    | 4         | 1.1%    |
| 0x6fb      | 4         | 1.1%    |
| 0x6e8      | 4         | 1.1%    |
| 0x08108109 | 4         | 1.1%    |
| 0xf29      | 3         | 0.83%   |
| 0x906ed    | 3         | 0.83%   |
| 0x906ea    | 3         | 0.83%   |
| 0x806ec    | 3         | 0.83%   |
| 0x806eb    | 3         | 0.83%   |
| 0x306d4    | 3         | 0.83%   |
| 0x20652    | 3         | 0.83%   |
| 0x10661    | 3         | 0.83%   |
| 0x06001119 | 3         | 0.83%   |
| 0xf65      | 2         | 0.55%   |
| 0xf64      | 2         | 0.55%   |
| 0x706a1    | 2         | 0.55%   |
| 0x6f2      | 2         | 0.55%   |
| 0x6d8      | 2         | 0.55%   |
| 0x506c9    | 2         | 0.55%   |
| 0x406c4    | 2         | 0.55%   |
| 0x406c3    | 2         | 0.55%   |
| 0x206c2    | 2         | 0.55%   |
| 0x106ca    | 2         | 0.55%   |
| 0x106a5    | 2         | 0.55%   |
| 0x08701021 | 2         | 0.55%   |
| 0x08200103 | 2         | 0.55%   |
| 0x08108102 | 2         | 0.55%   |
| 0x08101016 | 2         | 0.55%   |
| 0x0800820d | 2         | 0.55%   |
| 0x07030105 | 2         | 0.55%   |
| 0x06000852 | 2         | 0.55%   |
| 0x0600063e | 2         | 0.55%   |
| 0x05000119 | 2         | 0.55%   |
| 0x02000032 | 2         | 0.55%   |
| 0x010000dc | 2         | 0.55%   |
| 0xa0655    | 1         | 0.28%   |
| 0x906e9    | 1         | 0.28%   |
| 0x706a8    | 1         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Penryn          | 45        | 12.57%  |
| SandyBridge     | 34        | 9.5%    |
| Core            | 31        | 8.66%   |
| KabyLake        | 28        | 7.82%   |
| Haswell         | 28        | 7.82%   |
| IvyBridge       | 23        | 6.42%   |
| Bonnell         | 17        | 4.75%   |
| K8 Hammer       | 16        | 4.47%   |
| Westmere        | 15        | 4.19%   |
| P6              | 14        | 3.91%   |
| Skylake         | 13        | 3.63%   |
| K10             | 12        | 3.35%   |
| Silvermont      | 10        | 2.79%   |
| Zen+            | 9         | 2.51%   |
| Zen             | 8         | 2.23%   |
| NetBurst        | 8         | 2.23%   |
| Excavator       | 8         | 2.23%   |
| Nehalem         | 7         | 1.96%   |
| Piledriver      | 5         | 1.4%    |
| Zen 2           | 3         | 0.84%   |
| Puma            | 3         | 0.84%   |
| K6              | 3         | 0.84%   |
| Goldmont plus   | 3         | 0.84%   |
| Broadwell       | 3         | 0.84%   |
| Bobcat          | 3         | 0.84%   |
| K8 & K10 hybrid | 2         | 0.56%   |
| Goldmont        | 2         | 0.56%   |
| Bulldozer       | 2         | 0.56%   |
| Zen 3           | 1         | 0.28%   |
| Jaguar          | 1         | 0.28%   |
| CometLake       | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 189       | 47.37%  |
| Nvidia                           | 109       | 27.32%  |
| AMD                              | 86        | 21.55%  |
| VIA Technologies                 | 5         | 1.25%   |
| Silicon Integrated Systems [SiS] | 5         | 1.25%   |
| Matrox Electronics Systems       | 3         | 0.75%   |
| S3 Graphics                      | 1         | 0.25%   |
| ASPEED Technology                | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 27        | 6.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                           | 14        | 3.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 13        | 3.07%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 12        | 2.83%   |
| Intel Core Processor Integrated Graphics Controller                                        | 10        | 2.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                                 | 8         | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 8         | 1.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 8         | 1.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 8         | 1.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 7         | 1.65%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 6         | 1.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller                | 6         | 1.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                           | 6         | 1.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                        | 6         | 1.42%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 6         | 1.42%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 6         | 1.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 6         | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 6         | 1.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                    | 6         | 1.42%   |
| Intel UHD Graphics 620                                                                     | 5         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 5         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 5         | 1.18%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                  | 5         | 1.18%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                            | 5         | 1.18%   |
| Nvidia GT218 [GeForce 210]                                                                 | 4         | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 4         | 0.94%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 4         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 4         | 0.94%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 4         | 0.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 4         | 0.94%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 3         | 0.71%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 3         | 0.71%   |
| Nvidia GF108M [GeForce GT 525M]                                                            | 3         | 0.71%   |
| Intel HD Graphics 530                                                                      | 3         | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 0.71%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 3         | 0.71%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                           | 3         | 0.71%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                          | 2         | 0.47%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2         | 0.47%   |
| Nvidia TU106 [GeForce RTX 2070]                                                            | 2         | 0.47%   |
| Nvidia GT218M [NVS 3100M]                                                                  | 2         | 0.47%   |
| Nvidia GP107 [GeForce GTX 1050]                                                            | 2         | 0.47%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                        | 2         | 0.47%   |
| Nvidia GP104 [GeForce GTX 1070]                                                            | 2         | 0.47%   |
| Nvidia GM108M [GeForce 940MX]                                                              | 2         | 0.47%   |
| Nvidia GM107M [GeForce GTX 960M]                                                           | 2         | 0.47%   |
| Nvidia GK107M [GeForce GT 750M]                                                            | 2         | 0.47%   |
| Nvidia GK104 [GeForce GTX 760]                                                             | 2         | 0.47%   |
| Nvidia GF119M [NVS 4200M]                                                                  | 2         | 0.47%   |
| Nvidia GF108GLM [Quadro 1000M]                                                             | 2         | 0.47%   |
| Nvidia GF104 [GeForce GTX 460]                                                             | 2         | 0.47%   |
| Nvidia G96CM [GeForce 9600M GT]                                                            | 2         | 0.47%   |
| Nvidia G86 [GeForce 8400 GS]                                                               | 2         | 0.47%   |
| Nvidia C79 [GeForce 9400M]                                                                 | 2         | 0.47%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 2         | 0.47%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                              | 2         | 0.47%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 2         | 0.47%   |
| Intel HD Graphics 620                                                                      | 2         | 0.47%   |
| Intel HD Graphics 5500                                                                     | 2         | 0.47%   |
| Intel HD Graphics 510                                                                      | 2         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 149       | 41.5%   |
| 1 x Nvidia      | 82        | 22.84%  |
| 1 x AMD         | 74        | 20.61%  |
| Intel + Nvidia  | 26        | 7.24%   |
| Intel + AMD     | 8         | 2.23%   |
| 1 x VIA         | 5         | 1.39%   |
| 1 x SiS         | 5         | 1.39%   |
| 2 x AMD         | 4         | 1.11%   |
| 1 x Matrox      | 3         | 0.84%   |
| 2 x Nvidia      | 1         | 0.28%   |
| 1 x S3 Graphics | 1         | 0.28%   |
| 1 x ASPEED      | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 284       | 78.45%  |
| Unknown     | 41        | 11.33%  |
| Proprietary | 37        | 10.22%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 216       | 59.83%  |
| 0.01-0.5   | 58        | 16.07%  |
| 0.51-1.0   | 34        | 9.42%   |
| 1.01-2.0   | 27        | 7.48%   |
| 3.01-4.0   | 12        | 3.32%   |
| 7.01-8.0   | 9         | 2.49%   |
| 2.01-3.0   | 3         | 0.83%   |
| 5.01-6.0   | 2         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 61        | 17.18%  |
| AU Optronics            | 33        | 9.3%    |
| LG Display              | 30        | 8.45%   |
| Goldstar                | 22        | 6.2%    |
| BOE                     | 21        | 5.92%   |
| Chimei Innolux          | 18        | 5.07%   |
| Dell                    | 16        | 4.51%   |
| Acer                    | 15        | 4.23%   |
| Lenovo                  | 10        | 2.82%   |
| Chi Mei Optoelectronics | 10        | 2.82%   |
| Ancor Communications    | 10        | 2.82%   |
| LG Philips              | 8         | 2.25%   |
| BenQ                    | 8         | 2.25%   |
| AOC                     | 8         | 2.25%   |
| Unknown                 | 7         | 1.97%   |
| Philips                 | 7         | 1.97%   |
| Hewlett-Packard         | 7         | 1.97%   |
| Sony                    | 5         | 1.41%   |
| HannStar                | 5         | 1.41%   |
| Apple                   | 4         | 1.13%   |
| Iiyama                  | 3         | 0.85%   |
| Fujitsu Siemens         | 3         | 0.85%   |
| CPT                     | 3         | 0.85%   |
| Toshiba                 | 2         | 0.56%   |
| Sceptre Tech            | 2         | 0.56%   |
| Quanta Display          | 2         | 0.56%   |
| NEC Computers           | 2         | 0.56%   |
| LG Electronics          | 2         | 0.56%   |
| InfoVision              | 2         | 0.56%   |
| Belinea                 | 2         | 0.56%   |
| ___                     | 1         | 0.28%   |
| ViewSonic               | 1         | 0.28%   |
| Vestel                  | 1         | 0.28%   |
| Targa Visionary         | 1         | 0.28%   |
| Seiko/Epson             | 1         | 0.28%   |
| RTK                     | 1         | 0.28%   |
| PANDA                   | 1         | 0.28%   |
| OEM                     | 1         | 0.28%   |
| NCS                     | 1         | 0.28%   |
| MLT                     | 1         | 0.28%   |
| Mitsubishi              | 1         | 0.28%   |
| Microstep               | 1         | 0.28%   |
| Medion                  | 1         | 0.28%   |
| InnoLux Display         | 1         | 0.28%   |
| IBM                     | 1         | 0.28%   |
| Hitachi                 | 1         | 0.28%   |
| eMachines               | 1         | 0.28%   |
| ELSA International      | 1         | 0.28%   |
| Elo Touch               | 1         | 0.28%   |
| ELO                     | 1         | 0.28%   |
| Eizo                    | 1         | 0.28%   |
| DENON                   | 1         | 0.28%   |
| Compal                  | 1         | 0.28%   |
| AUS                     | 1         | 0.28%   |
| ASUSTek Computer        | 1         | 0.28%   |
| AOpen                   | 1         | 0.28%   |
| AGO                     | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.1%    |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 3         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 0.83%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.83%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch      | 2         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.55%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 0.55%   |
| Quanta Display LCD Monitor QDS0025 1024x768 304x228mm 15.0-inch          | 2         | 0.55%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 2         | 0.55%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 2         | 0.55%   |
| HannStar HSD101PFW2A HSD03E9 1024x600 222x125mm 10.0-inch                | 2         | 0.55%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                        | 2         | 0.55%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x174mm 14.0-inch          | 2         | 0.55%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 344x193mm 15.5-inch | 2         | 0.55%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 0.55%   |
| BOE LCD Monitor BOE06F9 1920x1080 344x193mm 15.5-inch                    | 2         | 0.55%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.55%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 2         | 0.55%   |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch                    | 1         | 0.28%   |
| ViewSonic VX2457 VSCB931 1920x1080 520x290mm 23.4-inch                   | 1         | 0.28%   |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                                | 1         | 0.28%   |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                       | 1         | 0.28%   |
| Unknown LCD Monitor XXX AAA                                              | 1         | 0.28%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.28%   |
| Unknown LCD Monitor SAMSUNG                                              | 1         | 0.28%   |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                        | 1         | 0.28%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                                 | 1         | 0.28%   |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch                   | 1         | 0.28%   |
| Toshiba LCD Monitor TV 1920x1080                                         | 1         | 0.28%   |
| Toshiba LCD Monitor TOS508F 1920x1080 509x286mm 23.0-inch                | 1         | 0.28%   |
| Targa Visionary LCD19-4 TARA194 1280x1024 376x301mm 19.0-inch            | 1         | 0.28%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                           | 1         | 0.28%   |
| Sony TV SNY4C03 1920x1080 1063x598mm 48.0-inch                           | 1         | 0.28%   |
| Sony TV SNY1B02 1360x768 1600x900mm 72.3-inch                            | 1         | 0.28%   |
| Sony LCD Monitor TV 3840x1080                                            | 1         | 0.28%   |
| Sony AVAMP SNYF700 1920x540                                              | 1         | 0.28%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 0.28%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                   | 1         | 0.28%   |
| Sceptre Tech F24 SPT0961 1920x1080 480x260mm 21.5-inch                   | 1         | 0.28%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch        | 1         | 0.28%   |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch        | 1         | 0.28%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch      | 1         | 0.28%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 459x296mm 21.5-inch     | 1         | 0.28%   |
| Samsung Electronics SyncMaster SAM034F 1440x900 428x255mm 19.6-inch      | 1         | 0.28%   |
| Samsung Electronics SyncMaster SAM0303 1680x1050 494x320mm 23.2-inch     | 1         | 0.28%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch     | 1         | 0.28%   |
| Samsung Electronics SyncMaster SAM006E 1280x1024 338x270mm 17.0-inch     | 1         | 0.28%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch     | 1         | 0.28%   |
| Samsung Electronics SMS22A200/460 SAM0831 1920x1080 477x268mm 21.5-inch  | 1         | 0.28%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch       | 1         | 0.28%   |
| Samsung Electronics SMB2230H SAM0648 1920x1080                           | 1         | 0.28%   |
| Samsung Electronics SMB2230 SAM063E 1920x1080 477x268mm 21.5-inch        | 1         | 0.28%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch        | 1         | 0.28%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch        | 1         | 0.28%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 118       | 34.1%   |
| 1366x768 (WXGA)    | 82        | 23.7%   |
| 1280x1024 (SXGA)   | 28        | 8.09%   |
| 1280x800 (WXGA)    | 26        | 7.51%   |
| 1600x900 (HD+)     | 17        | 4.91%   |
| 1440x900 (WXGA+)   | 14        | 4.05%   |
| 1680x1050 (WSXGA+) | 12        | 3.47%   |
| 3840x2160 (4K)     | 7         | 2.02%   |
| 1024x600           | 7         | 2.02%   |
| 1920x1200 (WUXGA)  | 6         | 1.73%   |
| 1024x768 (XGA)     | 6         | 1.73%   |
| 1360x768           | 5         | 1.45%   |
| Unknown            | 4         | 1.16%   |
| 3840x1080          | 2         | 0.58%   |
| 3440x1440          | 2         | 0.58%   |
| 2560x1440 (QHD)    | 2         | 0.58%   |
| 7680x2160          | 1         | 0.29%   |
| 4240x1440          | 1         | 0.29%   |
| 2736x1824          | 1         | 0.29%   |
| 2560x1080          | 1         | 0.29%   |
| 1920x540           | 1         | 0.29%   |
| 1600x1200          | 1         | 0.29%   |
| 1400x1050          | 1         | 0.29%   |
| 1280x768           | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 102       | 29.06%  |
| 17      | 27        | 7.69%   |
| Unknown | 26        | 7.41%   |
| 14      | 25        | 7.12%   |
| 21      | 21        | 5.98%   |
| 23      | 19        | 5.41%   |
| 13      | 19        | 5.41%   |
| 24      | 17        | 4.84%   |
| 19      | 17        | 4.84%   |
| 18      | 16        | 4.56%   |
| 27      | 13        | 3.7%    |
| 22      | 7         | 1.99%   |
| 12      | 7         | 1.99%   |
| 10      | 7         | 1.99%   |
| 20      | 6         | 1.71%   |
| 11      | 5         | 1.42%   |
| 31      | 4         | 1.14%   |
| 72      | 3         | 0.85%   |
| 54      | 2         | 0.57%   |
| 48      | 2         | 0.57%   |
| 52      | 1         | 0.28%   |
| 34      | 1         | 0.28%   |
| 33      | 1         | 0.28%   |
| 32      | 1         | 0.28%   |
| 26      | 1         | 0.28%   |
| 16      | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 148       | 42.53%  |
| 401-500     | 58        | 16.67%  |
| 501-600     | 44        | 12.64%  |
| 351-400     | 29        | 8.33%   |
| 201-300     | 27        | 7.76%   |
| Unknown     | 26        | 7.47%   |
| 601-700     | 5         | 1.44%   |
| 1001-1500   | 5         | 1.44%   |
| 701-800     | 3         | 0.86%   |
| 1501-2000   | 3         | 0.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 211       | 63.17%  |
| 16/10   | 58        | 17.37%  |
| 5/4     | 24        | 7.19%   |
| Unknown | 23        | 6.89%   |
| 4/3     | 12        | 3.59%   |
| 3/2     | 3         | 0.9%    |
| 21/9    | 2         | 0.6%    |
| 32/9    | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 102       | 29.06%  |
| 201-250        | 49        | 13.96%  |
| 81-90          | 38        | 10.83%  |
| 151-200        | 35        | 9.97%   |
| 141-150        | 26        | 7.41%   |
| Unknown        | 26        | 7.41%   |
| 301-350        | 14        | 3.99%   |
| 121-130        | 9         | 2.56%   |
| More than 1000 | 7         | 1.99%   |
| 351-500        | 7         | 1.99%   |
| 41-50          | 7         | 1.99%   |
| 251-300        | 7         | 1.99%   |
| 61-70          | 6         | 1.71%   |
| 71-80          | 5         | 1.42%   |
| 51-60          | 5         | 1.42%   |
| 131-140        | 3         | 0.85%   |
| 111-120        | 2         | 0.57%   |
| 91-100         | 2         | 0.57%   |
| 501-1000       | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 139       | 41.12%  |
| 101-120       | 111       | 32.84%  |
| 121-160       | 47        | 13.91%  |
| Unknown       | 26        | 7.69%   |
| 1-50          | 8         | 2.37%   |
| 161-240       | 4         | 1.18%   |
| More than 240 | 3         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 301       | 82.92%  |
| 2     | 40        | 11.02%  |
| 0     | 21        | 5.79%   |
| 3     | 1         | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 207       | 35.57%  |
| Intel                                 | 120       | 20.62%  |
| Qualcomm Atheros                      | 96        | 16.49%  |
| Broadcom                              | 42        | 7.22%   |
| Nvidia                                | 14        | 2.41%   |
| Marvell Technology Group              | 14        | 2.41%   |
| Broadcom Limited                      | 12        | 2.06%   |
| Ralink Technology                     | 9         | 1.55%   |
| Samsung Electronics                   | 7         | 1.2%    |
| Silicon Integrated Systems [SiS]      | 6         | 1.03%   |
| Ralink                                | 6         | 1.03%   |
| VIA Technologies                      | 5         | 0.86%   |
| TP-Link                               | 5         | 0.86%   |
| JMicron Technology                    | 3         | 0.52%   |
| Huawei Technologies                   | 3         | 0.52%   |
| Ericsson Business Mobile Networks     | 3         | 0.52%   |
| Linksys                               | 2         | 0.34%   |
| DisplayLink                           | 2         | 0.34%   |
| AVM                                   | 2         | 0.34%   |
| AMD                                   | 2         | 0.34%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.17%   |
| Xiaomi                                | 1         | 0.17%   |
| ST-Ericsson                           | 1         | 0.17%   |
| Sitecom Europe                        | 1         | 0.17%   |
| Sierra Wireless                       | 1         | 0.17%   |
| NetGear                               | 1         | 0.17%   |
| Microsoft                             | 1         | 0.17%   |
| Mellanox Technologies                 | 1         | 0.17%   |
| MediaTek                              | 1         | 0.17%   |
| Manta                                 | 1         | 0.17%   |
| LSI                                   | 1         | 0.17%   |
| Lenovo                                | 1         | 0.17%   |
| Intersil                              | 1         | 0.17%   |
| Gemtek                                | 1         | 0.17%   |
| Edimax Technology                     | 1         | 0.17%   |
| Dell                                  | 1         | 0.17%   |
| Cisco Aironet Wireless Communications | 1         | 0.17%   |
| Belkin Components                     | 1         | 0.17%   |
| Attansic Technology                   | 1         | 0.17%   |
| ASUSTek Computer                      | 1         | 0.17%   |
| Askey Computer                        | 1         | 0.17%   |
| ADMtek                                | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 125       | 18.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 44        | 6.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 2.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 2.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 12        | 1.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 1.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 1.04%   |
| Nvidia MCP61 Ethernet                                                   | 7         | 1.04%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 6         | 0.89%   |
| Intel WiFi Link 5100                                                    | 6         | 0.89%   |
| Intel I211 Gigabit Network Connection                                   | 6         | 0.89%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 5         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 0.74%   |
| Intel Wireless 7260                                                     | 5         | 0.74%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.74%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.74%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.59%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.59%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 4         | 0.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.59%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                 | 4         | 0.59%   |
| Intel Wireless 8265 / 8275                                              | 4         | 0.59%   |
| Intel Wireless 3160                                                     | 4         | 0.59%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 0.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.59%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.59%   |
| Intel 82573L Gigabit Ethernet Controller                                | 4         | 0.59%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 3         | 0.44%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.44%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 3         | 0.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 3         | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 3         | 0.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 3         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 3         | 0.44%   |
| Intel Wireless 8260                                                     | 3         | 0.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.44%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                        | 3         | 0.44%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express          | 3         | 0.44%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.3%    |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 0.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.3%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.3%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 2         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 80        | 28.17%  |
| Qualcomm Atheros                      | 78        | 27.46%  |
| Realtek Semiconductor                 | 58        | 20.42%  |
| Broadcom                              | 29        | 10.21%  |
| Ralink Technology                     | 9         | 3.17%   |
| Ralink                                | 6         | 2.11%   |
| TP-Link                               | 5         | 1.76%   |
| Broadcom Limited                      | 5         | 1.76%   |
| Linksys                               | 2         | 0.7%    |
| AVM                                   | 2         | 0.7%    |
| Sitecom Europe                        | 1         | 0.35%   |
| Sierra Wireless                       | 1         | 0.35%   |
| NetGear                               | 1         | 0.35%   |
| Microsoft                             | 1         | 0.35%   |
| Marvell Technology Group              | 1         | 0.35%   |
| Edimax Technology                     | 1         | 0.35%   |
| Cisco Aironet Wireless Communications | 1         | 0.35%   |
| Belkin Components                     | 1         | 0.35%   |
| ASUSTek Computer                      | 1         | 0.35%   |
| Askey Computer                        | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 4.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 4.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 4.18%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 4.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 4.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 3.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 2.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 2.44%   |
| Intel WiFi Link 5100                                                    | 6         | 2.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 1.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 1.74%   |
| Intel Wireless 7260                                                     | 5         | 1.74%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.74%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.39%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.39%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.39%   |
| Intel Wireless 3160                                                     | 4         | 1.39%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.05%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 1.05%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 3         | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.05%   |
| Intel Wireless 8260                                                     | 3         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.05%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 1.05%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.7%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.7%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 2         | 0.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.7%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.7%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 2         | 0.7%    |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 2         | 0.7%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.7%    |
| Intel Wireless 7265                                                     | 2         | 0.7%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.7%    |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.7%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.7%    |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 2         | 0.7%    |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.7%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.35%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 1         | 0.35%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.35%   |
| Sitecom Europe RTL8188S WLAN Adapter                                    | 1         | 0.35%   |
| Sierra Wireless MC8305 Modem                                            | 1         | 0.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 186       | 50.96%  |
| Intel                            | 68        | 18.63%  |
| Qualcomm Atheros                 | 28        | 7.67%   |
| Broadcom                         | 17        | 4.66%   |
| Nvidia                           | 14        | 3.84%   |
| Marvell Technology Group         | 13        | 3.56%   |
| Samsung Electronics              | 7         | 1.92%   |
| Broadcom Limited                 | 7         | 1.92%   |
| Silicon Integrated Systems [SiS] | 6         | 1.64%   |
| VIA Technologies                 | 5         | 1.37%   |
| JMicron Technology               | 3         | 0.82%   |
| Huawei Technologies              | 2         | 0.55%   |
| DisplayLink                      | 2         | 0.55%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.27%   |
| Xiaomi                           | 1         | 0.27%   |
| MediaTek                         | 1         | 0.27%   |
| Lenovo                           | 1         | 0.27%   |
| Gemtek                           | 1         | 0.27%   |
| Attansic Technology              | 1         | 0.27%   |
| ADMtek                           | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 125       | 33.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 44        | 11.89%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 12        | 3.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 2.97%   |
| Nvidia MCP61 Ethernet                                                          | 7         | 1.89%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 6         | 1.62%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 1.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 5         | 1.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 5         | 1.35%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1.35%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 4         | 1.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.08%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 4         | 1.08%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.08%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 4         | 1.08%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 3         | 0.81%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 0.81%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 3         | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.81%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3         | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.81%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3         | 0.81%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.54%   |
| Nvidia nForce2 Ethernet Controller                                             | 2         | 0.54%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.54%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 2         | 0.54%   |
| Intel PRO/100 VE Network Connection                                            | 2         | 0.54%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.54%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.54%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 0.54%   |
| Intel 82578DM Gigabit Network Connection                                       | 2         | 0.54%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.54%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.54%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.54%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 2         | 0.54%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile           | 2         | 0.54%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.54%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.54%   |
| ZTE WCDMA MSM Spreadtrum Phone                                                 | 1         | 0.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.27%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.27%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.27%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.27%   |
| MediaTek Le                                                                    | 1         | 0.27%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.27%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.27%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.27%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 342       | 54.46%  |
| WiFi     | 268       | 42.68%  |
| Modem    | 14        | 2.23%   |
| Unknown  | 4         | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 320       | 57.14%  |
| WiFi     | 239       | 42.68%  |
| Modem    | 1         | 0.18%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 229       | 63.97%  |
| 1     | 118       | 32.96%  |
| 3     | 5         | 1.4%    |
| 4     | 4         | 1.12%   |
| 0     | 2         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 314       | 85.56%  |
| Yes  | 53        | 14.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 24.18%  |
| Realtek Semiconductor           | 19        | 12.42%  |
| Broadcom                        | 18        | 11.76%  |
| Qualcomm Atheros Communications | 16        | 10.46%  |
| Cambridge Silicon Radio         | 11        | 7.19%   |
| Hewlett-Packard                 | 8         | 5.23%   |
| Foxconn / Hon Hai               | 8         | 5.23%   |
| Lite-On Technology              | 6         | 3.92%   |
| IMC Networks                    | 5         | 3.27%   |
| Dell                            | 5         | 3.27%   |
| ASUSTek Computer                | 4         | 2.61%   |
| Apple                           | 4         | 2.61%   |
| Toshiba                         | 3         | 1.96%   |
| Taiyo Yuden                     | 1         | 0.65%   |
| Realtek                         | 1         | 0.65%   |
| Ralink Technology               | 1         | 0.65%   |
| Ralink                          | 1         | 0.65%   |
| Qcom                            | 1         | 0.65%   |
| Marvell Semiconductor           | 1         | 0.65%   |
| Foxconn International           | 1         | 0.65%   |
| Askey Computer                  | 1         | 0.65%   |
| Alps Electric                   | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 17        | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 7.19%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 10        | 6.54%   |
| Realtek Bluetooth Radio                                                             | 8         | 5.23%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 4.58%   |
| Intel Bluetooth wireless interface                                                  | 7         | 4.58%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 3.27%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 5         | 3.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 2.61%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 2.61%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.96%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 1.96%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.96%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 1.96%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.31%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.31%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 1.31%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.31%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.31%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.31%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.31%   |
| Broadcom Bluetooth                                                                  | 2         | 1.31%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.31%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.31%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.31%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 2         | 1.31%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.31%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.65%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.65%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.65%   |
| Taiyo Yuden Bluetooth Device(BC04-External)                                         | 1         | 0.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.65%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.65%   |
| Ralink CSR BS8510                                                                   | 1         | 0.65%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.65%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.65%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.65%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.65%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.65%   |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.65%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.65%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.65%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.65%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.65%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.65%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.65%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.65%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.65%   |
| Broadcom HP Bluethunder                                                             | 1         | 0.65%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.65%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.65%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.65%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.65%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.65%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.65%   |
| Askey Bluetooth Device                                                              | 1         | 0.65%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 256       | 55.9%   |
| AMD                              | 78        | 17.03%  |
| Nvidia                           | 75        | 16.38%  |
| C-Media Electronics              | 11        | 2.4%    |
| VIA Technologies                 | 8         | 1.75%   |
| Silicon Integrated Systems [SiS] | 8         | 1.75%   |
| Creative Labs                    | 4         | 0.87%   |
| Logitech                         | 3         | 0.66%   |
| JMTek                            | 2         | 0.44%   |
| GN Netcom                        | 2         | 0.44%   |
| Generalplus Technology           | 2         | 0.44%   |
| Yamaha                           | 1         | 0.22%   |
| Xilinx                           | 1         | 0.22%   |
| Tenx Technology                  | 1         | 0.22%   |
| M-Audio                          | 1         | 0.22%   |
| GYROCOM C&C                      | 1         | 0.22%   |
| Focusrite-Novation               | 1         | 0.22%   |
| Evolution Electronics            | 1         | 0.22%   |
| Dell                             | 1         | 0.22%   |
| Creative Technology              | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 38        | 7.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 31        | 5.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 25        | 4.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 4.58%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 21        | 4.01%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 3.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 17        | 3.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 2.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 2.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 2.1%    |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 11        | 2.1%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.72%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 1.72%   |
| Nvidia High Definition Audio Controller                                                           | 8         | 1.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.53%   |
| AMD High Definition Audio Controller                                                              | 8         | 1.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 1.53%   |
| Nvidia MCP61 High Definition Audio                                                                | 7         | 1.34%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.34%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.15%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 6         | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.15%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.95%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 5         | 0.95%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 0.95%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 4         | 0.76%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 4         | 0.76%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 4         | 0.76%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 4         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.76%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 0.76%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 0.76%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 0.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 0.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.57%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.57%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 3         | 0.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.57%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.57%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 3         | 0.57%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.57%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 2         | 0.38%   |
| Nvidia nForce2 AC97 Audio Controler (MCP)                                                         | 2         | 0.38%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.38%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.38%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 2         | 0.38%   |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 12        | 20.69%  |
| SK Hynix            | 11        | 18.97%  |
| Samsung Electronics | 10        | 17.24%  |
| Kingston            | 7         | 12.07%  |
| Crucial             | 3         | 5.17%   |
| Smart               | 2         | 3.45%   |
| Ramaxel Technology  | 2         | 3.45%   |
| Nanya Technology    | 2         | 3.45%   |
| Micron Technology   | 2         | 3.45%   |
| G.Skill             | 2         | 3.45%   |
| Unknown (ABCD)      | 1         | 1.72%   |
| Transcend           | 1         | 1.72%   |
| PLEXHD              | 1         | 1.72%   |
| Exceleram           | 1         | 1.72%   |
| A-DATA Technology   | 1         | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module SODIMM DDR                                    | 1         | 1.61%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 1.61%   |
| Unknown RAM Module 512MB DIMM 667MT/s                            | 1         | 1.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 1.61%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 1.61%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 1.61%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 1.61%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 1         | 1.61%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                      | 1         | 1.61%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 1.61%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1         | 1.61%   |
| Unknown RAM Module 1024MB DIMM                                   | 1         | 1.61%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR3 2400MT/s | 1         | 1.61%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                | 1         | 1.61%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 1.61%   |
| Smart RAM SH564128FJ8NWRNSQG 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2400MT/s                    | 1         | 1.61%   |
| SK Hynix RAM Module 512MB SODIMM DDR 533MT/s                     | 1         | 1.61%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR 667MT/s          | 1         | 1.61%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 1         | 1.61%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.61%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.61%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.61%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 1         | 1.61%   |
| SK Hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 1.61%   |
| SK Hynix RAM HMP112S6EFR6C-S6 1024MB SODIMM DDR2 800MT/s         | 1         | 1.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.61%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 2667MT/s         | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s        | 1         | 1.61%   |
| Samsung RAM M393B1K70CH0-CH9 8192MB DIMM DDR3 1333MT/s           | 1         | 1.61%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s              | 1         | 1.61%   |
| Samsung RAM K4AAG165WB-MCTD 8192MB SODIMM DDR4 2667MT/s          | 1         | 1.61%   |
| Ramaxel RAM RMSA3260MF68H9F-2666 4096MB SODIMM DDR4 2400MT/s     | 1         | 1.61%   |
| Ramaxel RAM RMN1150EC48D7W-800 1024MB SODIMM DDR2 800MT/s        | 1         | 1.61%   |
| PLEXHD RAM Module 8192MB DIMM DDR3 1333MT/s                      | 1         | 1.61%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s             | 1         | 1.61%   |
| Nanya RAM Module 1024MB SODIMM DDR 533MT/s                       | 1         | 1.61%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s           | 1         | 1.61%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.61%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s                   | 1         | 1.61%   |
| Kingston RAM KHX3600C17D4/16GX 16GB DIMM DDR4 3800MT/s           | 1         | 1.61%   |
| Kingston RAM HP536726-H41-HYA 4096MB DIMM DDR3 1333MT/s          | 1         | 1.61%   |
| Kingston RAM 9905711-016.A00G 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.61%   |
| Kingston RAM 9905700-024.A00G 8GB SODIMM DDR4 2400MT/s           | 1         | 1.61%   |
| Kingston RAM 9905624-059.A00G 8GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| Kingston RAM 9905428-155.A00LF 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.61%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s           | 1         | 1.61%   |
| G.Skill RAM F3-10666CL9-8GBSQ 8192MB SODIMM DDR3 1333MT/s        | 1         | 1.61%   |
| Exceleram RAM E30144A 4096MB DIMM DDR3 800MT/s                   | 1         | 1.61%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.61%   |
| Crucial RAM BLT8G4D26BFT4K.C8FD 8GB DIMM DDR4 2666MT/s           | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 41.51%  |
| DDR4    | 14        | 26.42%  |
| DDR2    | 9         | 16.98%  |
| DDR     | 3         | 5.66%   |
| SDRAM   | 2         | 3.77%   |
| Unknown | 2         | 3.77%   |
| LPDDR4  | 1         | 1.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 31        | 60.78%  |
| DIMM   | 20        | 39.22%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 20        | 35.09%  |
| 4096    | 13        | 22.81%  |
| 2048    | 13        | 22.81%  |
| 1024    | 6         | 10.53%  |
| 16384   | 2         | 3.51%   |
| 512     | 2         | 3.51%   |
| Unknown | 1         | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 23.64%  |
| 2667    | 9         | 16.36%  |
| 1333    | 7         | 12.73%  |
| 800     | 5         | 9.09%   |
| 2400    | 4         | 7.27%   |
| 667     | 3         | 5.45%   |
| Unknown | 3         | 5.45%   |
| 975     | 2         | 3.64%   |
| 533     | 2         | 3.64%   |
| 3800    | 1         | 1.82%   |
| 3500    | 1         | 1.82%   |
| 3266    | 1         | 1.82%   |
| 3200    | 1         | 1.82%   |
| 2666    | 1         | 1.82%   |
| 2048    | 1         | 1.82%   |
| 400     | 1         | 1.82%   |

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
| Chicony Electronics                    | 39        | 21.67%  |
| Sunplus Innovation Technology          | 14        | 7.78%   |
| IMC Networks                           | 14        | 7.78%   |
| Suyin                                  | 12        | 6.67%   |
| Quanta                                 | 12        | 6.67%   |
| Acer                                   | 10        | 5.56%   |
| Realtek Semiconductor                  | 9         | 5%      |
| Microdia                               | 9         | 5%      |
| Silicon Motion                         | 7         | 3.89%   |
| Ricoh                                  | 6         | 3.33%   |
| Logitech                               | 6         | 3.33%   |
| Apple                                  | 6         | 3.33%   |
| Syntek                                 | 5         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.78%   |
| Microsoft                              | 3         | 1.67%   |
| Importek                               | 3         | 1.67%   |
| Z-Star Microelectronics                | 2         | 1.11%   |
| Sunplus Technology                     | 2         | 1.11%   |
| Lite-On Technology                     | 2         | 1.11%   |
| Generalplus Technology                 | 2         | 1.11%   |
| ALi                                    | 2         | 1.11%   |
| Xiongmai                               | 1         | 0.56%   |
| WCM_USB                                | 1         | 0.56%   |
| Service & Quality Technology           | 1         | 0.56%   |
| Samsung Electronics                    | 1         | 0.56%   |
| OmniVision Technologies                | 1         | 0.56%   |
| Nintendo                               | 1         | 0.56%   |
| LG Electronics                         | 1         | 0.56%   |
| Lenovo                                 | 1         | 0.56%   |
| KYE Systems (Mouse Systems)            | 1         | 0.56%   |
| Alcor Micro                            | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Quanta HP Webcam                                 | 5         | 2.76%   |
| Chicony Integrated Camera                        | 5         | 2.76%   |
| Chicony USB 2.0 Camera                           | 4         | 2.21%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 3         | 1.66%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 3         | 1.66%   |
| Realtek USB2.0 VGA UVC WebCam                    | 3         | 1.66%   |
| Logitech Webcam C270                             | 3         | 1.66%   |
| Chicony USB2.0 HD UVC WebCam                     | 3         | 1.66%   |
| Apple iPhone 5/5C/5S/6/SE                        | 3         | 1.66%   |
| Apple Built-in iSight                            | 3         | 1.66%   |
| Acer HD Webcam                                   | 3         | 1.66%   |
| Syntek Sonix USB 2.0 Camera                      | 2         | 1.1%    |
| Suyin HP Truevision HD                           | 2         | 1.1%    |
| Suyin 1.3M HD WebCam                             | 2         | 1.1%    |
| Sunplus Laptop Integrated WebCam HD              | 2         | 1.1%    |
| Silicon Motion WebCam SCB-0385N                  | 2         | 1.1%    |
| Silicon Motion WebCam SC-0311139N                | 2         | 1.1%    |
| Silicon Motion HP Webcam-101                     | 2         | 1.1%    |
| Ricoh Sony Visual Communication Camera           | 2         | 1.1%    |
| Realtek Integrated_Webcam_HD                     | 2         | 1.1%    |
| Quanta VGA WebCam                                | 2         | 1.1%    |
| Quanta HP TrueVision HD Camera                   | 2         | 1.1%    |
| Microsoft LifeCam HD-3000                        | 2         | 1.1%    |
| Microdia Sonix USB 2.0 Camera                    | 2         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_HD             | 2         | 1.1%    |
| Microdia Integrated Webcam HD                    | 2         | 1.1%    |
| Importek TOSHIBA Web Camera - HD                 | 2         | 1.1%    |
| IMC Networks USB2.0 HD UVC WebCam                | 2         | 1.1%    |
| IMC Networks Integrated Camera                   | 2         | 1.1%    |
| IMC Networks EasyCamera                          | 2         | 1.1%    |
| Chicony TOSHIBA Web Camera - HD                  | 2         | 1.1%    |
| Chicony HP Truevision HD camera                  | 2         | 1.1%    |
| Chicony HD WebCam (Acer)                         | 2         | 1.1%    |
| Chicony HD WebCam                                | 2         | 1.1%    |
| Chicony 2.0M UVC Webcam / CNF7129                | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.1%    |
| Acer Lenovo EasyCamera                           | 2         | 1.1%    |
| Z-Star Namuga 1.3M Webcam                        | 1         | 0.55%   |
| Z-Star Lenovo ThinkCentre Web Camera             | 1         | 0.55%   |
| Xiongmai web camera                              | 1         | 0.55%   |
| WCM_USB WEB CAM                                  | 1         | 0.55%   |
| Syntek Integrated Webcam                         | 1         | 0.55%   |
| Syntek Integrated Camera                         | 1         | 0.55%   |
| Syntek HP Webcam                                 | 1         | 0.55%   |
| Suyin HP Webcam                                  | 1         | 0.55%   |
| Suyin HP TrueVision HD Integrated Webcam         | 1         | 0.55%   |
| Suyin HD WebCam                                  | 1         | 0.55%   |
| Suyin HD Video WebCam                            | 1         | 0.55%   |
| Suyin Acer CrystalEye Webcam                     | 1         | 0.55%   |
| Sunplus 1.3M WebCam                              | 1         | 0.55%   |
| Sunplus 1.3M HD WebCam                           | 1         | 0.55%   |
| Sunplus Lenovo EasyCamera                        | 1         | 0.55%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 0.55%   |
| Sunplus Integrated Webcam                        | 1         | 0.55%   |
| Sunplus HP TrueVision HD Camera                  | 1         | 0.55%   |
| Sunplus HD WebCam                                | 1         | 0.55%   |
| Sunplus Full HD webcam                           | 1         | 0.55%   |
| Sunplus Dell HD Webcam                           | 1         | 0.55%   |
| Sunplus Dell E5570 integrated webcam             | 1         | 0.55%   |
| Sunplus Asus Webcam                              | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 9         | 34.62%  |
| AuthenTec             | 8         | 30.77%  |
| STMicroelectronics    | 3         | 11.54%  |
| Synaptics             | 2         | 7.69%   |
| LighTuning Technology | 2         | 7.69%   |
| Upek                  | 1         | 3.85%   |
| Elan Microelectronics | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                  | 3         | 11.54%  |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 7.69%   |
| Validity Sensors VFS301 Fingerprint Reader             | 2         | 7.69%   |
| AuthenTec Fingerprint Sensor                           | 2         | 7.69%   |
| AuthenTec AES2810                                      | 2         | 7.69%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 7.69%   |
| AuthenTec AES1600                                      | 2         | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 3.85%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 3.85%   |
| Validity Sensors VFS491                                | 1         | 3.85%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 3.85%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 3.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 3.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.85%   |
| Elan ELAN:Fingerprint                                  | 1         | 3.85%   |
| Unknown                                                | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 8         | 53.33%  |
| O2 Micro                          | 2         | 13.33%  |
| VASCO Data Security International | 1         | 6.67%   |
| OmniKey                           | 1         | 6.67%   |
| Jing-Mold Enterprise              | 1         | 6.67%   |
| Gemalto (was Gemplus)             | 1         | 6.67%   |
| Alcor Micro                       | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 26.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 13.33%  |
| VASCO Data Security International DIGIPASS 870                               | 1         | 6.67%   |
| OmniKey CardMan 1021                                                         | 1         | 6.67%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 6.67%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 6.67%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 239       | 66.02%  |
| 1     | 93        | 25.69%  |
| 2     | 19        | 5.25%   |
| 3     | 8         | 2.21%   |
| 4     | 2         | 0.55%   |
| 6     | 1         | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 55        | 35.95%  |
| Net/wireless             | 27        | 17.65%  |
| Fingerprint reader       | 26        | 16.99%  |
| Chipcard                 | 12        | 7.84%   |
| Multimedia controller    | 8         | 5.23%   |
| Communication controller | 8         | 5.23%   |
| Storage                  | 6         | 3.92%   |
| Network                  | 2         | 1.31%   |
| Net/ethernet             | 2         | 1.31%   |
| Flash memory             | 2         | 1.31%   |
| Unassigned class         | 1         | 0.65%   |
| Storage/ide              | 1         | 0.65%   |
| Modem                    | 1         | 0.65%   |
| Camera                   | 1         | 0.65%   |
| Bluetooth                | 1         | 0.65%   |

