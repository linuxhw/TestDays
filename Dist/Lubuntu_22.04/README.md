Lubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Lubuntu_22.04/Notebook/README.md).

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

Total: 138

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | Notebook    | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | Notebook    | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | Desktop     | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Dell          | 0R849J A00                  | Desktop     | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| ASUSTek       | UX360CAK                    | Convertible | [015df11bc4](https://linux-hardware.org/?probe=015df11bc4) | Sep 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c45724d6d3](https://linux-hardware.org/?probe=c45724d6d3) | Sep 20, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2f9ab4273a](https://linux-hardware.org/?probe=2f9ab4273a) | Sep 20, 2022 |
| Gateway       | NE46R                       | Notebook    | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | Notebook    | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Dell          | 0J584C A00                  | Desktop     | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | Notebook    | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | Notebook    | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| OEM           | Unknown                     | Notebook    | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 8768 A                      | Desktop     | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | Desktop     | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | Desktop     | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | Notebook    | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| Dell          | 0X8582                      | Desktop     | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| Sony          | VPCEB15FM                   | Notebook    | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | Desktop     | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | Desktop     | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| HP            | 1495                        | Desktop     | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| HP            | 1495                        | Desktop     | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Gateway       | Sonic-C                     | Notebook    | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| Dell          | Latitude XT                 | Notebook    | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Intel         | W7650                       | Notebook    | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63ccee44b1](https://linux-hardware.org/?probe=63ccee44b1) | May 28, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | Notebook    | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.0-43-generic           | 14        | 12.17%  |
| 5.15.0-47-generic           | 10        | 8.7%    |
| 5.15.0-30-generic           | 10        | 8.7%    |
| 5.15.0-25-generic           | 10        | 8.7%    |
| 5.15.0-46-generic           | 9         | 7.83%   |
| 5.15.0-27-generic           | 9         | 7.83%   |
| 5.15.0-41-generic           | 8         | 6.96%   |
| 5.15.0-48-generic           | 6         | 5.22%   |
| 5.15.0-40-generic           | 6         | 5.22%   |
| 5.15.0-50-generic           | 5         | 4.35%   |
| 5.15.0-39-generic           | 4         | 3.48%   |
| 5.15.0-35-generic           | 4         | 3.48%   |
| 5.15.0-33-generic           | 4         | 3.48%   |
| 5.15.0-52-generic           | 2         | 1.74%   |
| 5.15.0-37-generic           | 2         | 1.74%   |
| 5.15.0-23-generic           | 2         | 1.74%   |
| 5.15.0-18-generic           | 2         | 1.74%   |
| 5.19.8-xanmod1              | 1         | 0.87%   |
| 5.19.11-ux360cak            | 1         | 0.87%   |
| 5.19.0-16.2-liquorix-amd64  | 1         | 0.87%   |
| 5.19.0-051900-generic       | 1         | 0.87%   |
| 5.18.0-051800-generic       | 1         | 0.87%   |
| 5.15.0-41-lowlatency        | 1         | 0.87%   |
| 5.15.0-362206031516-generic | 1         | 0.87%   |
| 5.15.0-28-generic           | 1         | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 106       | 95.5%   |
| 5.19.0  | 2         | 1.8%    |
| 5.19.8  | 1         | 0.9%    |
| 5.19.11 | 1         | 0.9%    |
| 5.18.0  | 1         | 0.9%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 106       | 95.5%   |
| 5.19    | 4         | 3.6%    |
| 5.18    | 1         | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 108       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 105       | 97.22%  |
| LXDE       | 2         | 1.85%   |
| X-Cinnamon | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 104       | 95.41%  |
| Tty         | 3         | 2.75%   |
| Wayland     | 1         | 0.92%   |
| Unspecified | 1         | 0.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 97        | 89.81%  |
| Unknown | 5         | 4.63%   |
| LightDM | 3         | 2.78%   |
| XDM     | 1         | 0.93%   |
| SLiM    | 1         | 0.93%   |
| LXDM    | 1         | 0.93%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 31        | 28.44%  |
| fr_FR | 9         | 8.26%   |
| de_DE | 8         | 7.34%   |
| it_IT | 7         | 6.42%   |
| en_GB | 7         | 6.42%   |
| C     | 7         | 6.42%   |
| pt_BR | 6         | 5.5%    |
| pl_PL | 4         | 3.67%   |
| es_CR | 4         | 3.67%   |
| nl_BE | 3         | 2.75%   |
| es_AR | 3         | 2.75%   |
| en_AG | 3         | 2.75%   |
| es_MX | 2         | 1.83%   |
| en_CA | 2         | 1.83%   |
| en_AU | 2         | 1.83%   |
| el_GR | 2         | 1.83%   |
| sv_SE | 1         | 0.92%   |
| ru_UA | 1         | 0.92%   |
| ja_JP | 1         | 0.92%   |
| fi_FI | 1         | 0.92%   |
| es_ES | 1         | 0.92%   |
| es_CL | 1         | 0.92%   |
| en_ZA | 1         | 0.92%   |
| en_PH | 1         | 0.92%   |
| cv_RU | 1         | 0.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 74        | 67.89%  |
| EFI  | 35        | 32.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 99        | 90.83%  |
| Overlay | 7         | 6.42%   |
| Btrfs   | 2         | 1.83%   |
| Ext2    | 1         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 42        | 38.53%  |
| Unknown | 42        | 38.53%  |
| MBR     | 25        | 22.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 87.16%  |
| Yes       | 14        | 12.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 72.48%  |
| Yes       | 30        | 27.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 18        | 16.67%  |
| Lenovo              | 17        | 15.74%  |
| Hewlett-Packard     | 11        | 10.19%  |
| ASUSTek Computer    | 9         | 8.33%   |
| MSI                 | 5         | 4.63%   |
| Google              | 5         | 4.63%   |
| Acer                | 5         | 4.63%   |
| Unknown             | 5         | 4.63%   |
| AMI                 | 4         | 3.7%    |
| Sony                | 3         | 2.78%   |
| Gigabyte Technology | 3         | 2.78%   |
| Fujitsu             | 3         | 2.78%   |
| ASRock              | 3         | 2.78%   |
| Apple               | 3         | 2.78%   |
| Mediacom            | 2         | 1.85%   |
| Gateway             | 2         | 1.85%   |
| ZOTAC               | 1         | 0.93%   |
| Toshiba             | 1         | 0.93%   |
| Prestigio           | 1         | 0.93%   |
| Pegatron            | 1         | 0.93%   |
| Packard Bell        | 1         | 0.93%   |
| OEM                 | 1         | 0.93%   |
| Kiano               | 1         | 0.93%   |
| Intel               | 1         | 0.93%   |
| IFSA                | 1         | 0.93%   |
| Chuwi               | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 6         | 5.56%   |
| Mediacom WinPad 11,6 FullHD- WPU11       | 2         | 1.85%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 2         | 1.85%   |
| Dell Dimension 9100                      | 2         | 1.85%   |
| Apple MacBookPro8,1                      | 2         | 1.85%   |
| ZOTAC NM10                               | 1         | 0.93%   |
| Toshiba Satellite L40                    | 1         | 0.93%   |
| Sony VPCEB15FM                           | 1         | 0.93%   |
| Sony VGN-SZ71WN_C                        | 1         | 0.93%   |
| Sony SVE14A2V1EW                         | 1         | 0.93%   |
| Prestigio PSB141C01BFH                   | 1         | 0.93%   |
| Pegatron AY748AA-ABA p6320y              | 1         | 0.93%   |
| Packard Bell EasyNote TS44HR             | 1         | 0.93%   |
| MSI MS-7D09                              | 1         | 0.93%   |
| MSI MS-7C37                              | 1         | 0.93%   |
| MSI MS-7B86                              | 1         | 0.93%   |
| MSI MS-7978                              | 1         | 0.93%   |
| MSI MS-7641                              | 1         | 0.93%   |
| Lenovo Z70-80 80FG                       | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0WE02 | 1         | 0.93%   |
| Lenovo ThinkPad T430 2342A19             | 1         | 0.93%   |
| Lenovo ThinkPad T410 2537CS0             | 1         | 0.93%   |
| Lenovo ThinkPad SL510 2847CXG            | 1         | 0.93%   |
| Lenovo ThinkPad E550 20DF00CUFR          | 1         | 0.93%   |
| Lenovo ThinkCentre M83 10ANCTO1WW        | 1         | 0.93%   |
| Lenovo ThinkCentre M600 10KGS09S00       | 1         | 0.93%   |
| Lenovo MIIX 310-10ICR 80SG               | 1         | 0.93%   |
| Lenovo IdeaPad S145-15IGM 81MX           | 1         | 0.93%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 1         | 0.93%   |
| Lenovo IdeaPad 330-15IKB Touch 81DJ      | 1         | 0.93%   |
| Lenovo G50-70 20351                      | 1         | 0.93%   |
| Lenovo G50-30 80G0                       | 1         | 0.93%   |
| Lenovo B590 20208                        | 1         | 0.93%   |
| Kiano SlimNote 14.1                      | 1         | 0.93%   |
| Intel Infoway                            | 1         | 0.93%   |
| IFSA Positivo BGH                        | 1         | 0.93%   |
| HP Z400 Workstation                      | 1         | 0.93%   |
| HP Slim Desktop S01-pF1xxx               | 1         | 0.93%   |
| HP ProBook 640 G1                        | 1         | 0.93%   |
| HP ProBook 4730s                         | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Unknown                | 6         | 5.56%   |
| Lenovo ThinkPad        | 5         | 4.63%   |
| Lenovo IdeaPad         | 5         | 4.63%   |
| Acer Aspire            | 4         | 3.7%    |
| HP Pavilion            | 3         | 2.78%   |
| Dell OptiPlex          | 3         | 2.78%   |
| Dell Latitude          | 3         | 2.78%   |
| Mediacom WinPad        | 2         | 1.85%   |
| Lenovo ThinkCentre     | 2         | 1.85%   |
| HP ProBook             | 2         | 1.85%   |
| Fujitsu LIFEBOOK       | 2         | 1.85%   |
| Dell XPS               | 2         | 1.85%   |
| Dell Vostro            | 2         | 1.85%   |
| Dell Studio            | 2         | 1.85%   |
| Dell Precision         | 2         | 1.85%   |
| Dell Dimension         | 2         | 1.85%   |
| ASUS PRIME             | 2         | 1.85%   |
| Apple MacBookPro8      | 2         | 1.85%   |
| ZOTAC NM10             | 1         | 0.93%   |
| Toshiba Satellite      | 1         | 0.93%   |
| Sony VPCEB15FM         | 1         | 0.93%   |
| Sony VGN-SZ71WN        | 1         | 0.93%   |
| Sony SVE14A2V1EW       | 1         | 0.93%   |
| Prestigio PSB141C01BFH | 1         | 0.93%   |
| Pegatron AY748AA-ABA   | 1         | 0.93%   |
| Packard Bell EasyNote  | 1         | 0.93%   |
| MSI MS-7D09            | 1         | 0.93%   |
| MSI MS-7C37            | 1         | 0.93%   |
| MSI MS-7B86            | 1         | 0.93%   |
| MSI MS-7978            | 1         | 0.93%   |
| MSI MS-7641            | 1         | 0.93%   |
| Lenovo Z70-80          | 1         | 0.93%   |
| Lenovo MIIX            | 1         | 0.93%   |
| Lenovo G50-70          | 1         | 0.93%   |
| Lenovo G50-30          | 1         | 0.93%   |
| Lenovo B590            | 1         | 0.93%   |
| Kiano SlimNote         | 1         | 0.93%   |
| Intel Infoway          | 1         | 0.93%   |
| IFSA Positivo          | 1         | 0.93%   |
| HP Z400                | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 11        | 10.19%  |
| 2013 | 9         | 8.33%   |
| 2012 | 9         | 8.33%   |
| 2019 | 8         | 7.41%   |
| 2017 | 8         | 7.41%   |
| 2015 | 8         | 7.41%   |
| 2014 | 8         | 7.41%   |
| 2008 | 8         | 7.41%   |
| 2016 | 7         | 6.48%   |
| 2021 | 6         | 5.56%   |
| 2010 | 6         | 5.56%   |
| 2007 | 5         | 4.63%   |
| 2022 | 4         | 3.7%    |
| 2020 | 4         | 3.7%    |
| 2009 | 4         | 3.7%    |
| 2006 | 2         | 1.85%   |
| 2018 | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 65        | 60.19%  |
| Desktop     | 38        | 35.19%  |
| Tablet      | 2         | 1.85%   |
| Mini pc     | 2         | 1.85%   |
| Convertible | 1         | 0.93%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 105       | 97.22%  |
| Enabled  | 3         | 2.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 103       | 95.37%  |
| Yes  | 5         | 4.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 38        | 34.86%  |
| 4.01-8.0    | 24        | 22.02%  |
| 1.01-2.0    | 13        | 11.93%  |
| 8.01-16.0   | 11        | 10.09%  |
| 16.01-24.0  | 10        | 9.17%   |
| 32.01-64.0  | 5         | 4.59%   |
| 2.01-3.0    | 5         | 4.59%   |
| 0.51-1.0    | 2         | 1.83%   |
| 64.01-256.0 | 1         | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 50        | 45.45%  |
| 0.51-1.0 | 32        | 29.09%  |
| 2.01-3.0 | 19        | 17.27%  |
| 4.01-8.0 | 5         | 4.55%   |
| 3.01-4.0 | 4         | 3.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 78        | 72.22%  |
| 2      | 24        | 22.22%  |
| 0      | 2         | 1.85%   |
| 7      | 1         | 0.93%   |
| 6      | 1         | 0.93%   |
| 5      | 1         | 0.93%   |
| 3      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 57.41%  |
| Yes       | 46        | 42.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 81.48%  |
| No        | 20        | 18.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 73.15%  |
| No        | 29        | 26.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 50%     |
| No        | 54        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 21        | 19.44%  |
| Germany      | 9         | 8.33%   |
| France       | 9         | 8.33%   |
| Italy        | 7         | 6.48%   |
| Brazil       | 7         | 6.48%   |
| UK           | 5         | 4.63%   |
| Poland       | 5         | 4.63%   |
| Costa Rica   | 4         | 3.7%    |
| Belgium      | 4         | 3.7%    |
| Argentina    | 3         | 2.78%   |
| Vietnam      | 2         | 1.85%   |
| Ukraine      | 2         | 1.85%   |
| Sweden       | 2         | 1.85%   |
| Spain        | 2         | 1.85%   |
| Russia       | 2         | 1.85%   |
| Mexico       | 2         | 1.85%   |
| Hungary      | 2         | 1.85%   |
| Greece       | 2         | 1.85%   |
| Canada       | 2         | 1.85%   |
| Australia    | 2         | 1.85%   |
| Turkey       | 1         | 0.93%   |
| South Africa | 1         | 0.93%   |
| Saudi Arabia | 1         | 0.93%   |
| Romania      | 1         | 0.93%   |
| Portugal     | 1         | 0.93%   |
| Philippines  | 1         | 0.93%   |
| Netherlands  | 1         | 0.93%   |
| Latvia       | 1         | 0.93%   |
| Kenya        | 1         | 0.93%   |
| Japan        | 1         | 0.93%   |
| Indonesia    | 1         | 0.93%   |
| Finland      | 1         | 0.93%   |
| Chile        | 1         | 0.93%   |
| Bulgaria     | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 4         | 3.7%    |
| Heredia          | 4         | 3.7%    |
| Sarospatak       | 2         | 1.85%   |
| Porto Alegre     | 2         | 1.85%   |
| Novo Gama        | 2         | 1.85%   |
| Melbourne        | 2         | 1.85%   |
| Largo            | 2         | 1.85%   |
| Kyiv             | 2         | 1.85%   |
| Yoshkar-Ola      | 1         | 0.93%   |
| Yorkville        | 1         | 0.93%   |
| Wolfhagen        | 1         | 0.93%   |
| Wetteren         | 1         | 0.93%   |
| Washington       | 1         | 0.93%   |
| Warsaw           | 1         | 0.93%   |
| Volzhskiy        | 1         | 0.93%   |
| Varna            | 1         | 0.93%   |
| Valentigney      | 1         | 0.93%   |
| Valencia         | 1         | 0.93%   |
| Tychy            | 1         | 0.93%   |
| Thessaloniki     | 1         | 0.93%   |
| Taylorsville     | 1         | 0.93%   |
| Tandil           | 1         | 0.93%   |
| Surabaya         | 1         | 0.93%   |
| Stuttgart        | 1         | 0.93%   |
| Strzyzow         | 1         | 0.93%   |
| Stockholm        | 1         | 0.93%   |
| Southampton      | 1         | 0.93%   |
| South Burlington | 1         | 0.93%   |
| Sonico           | 1         | 0.93%   |
| Sao Paulo        | 1         | 0.93%   |
| Santiago         | 1         | 0.93%   |
| Roswell          | 1         | 0.93%   |
| Rossano Veneto   | 1         | 0.93%   |
| Riyadh           | 1         | 0.93%   |
| Rio de Janeiro   | 1         | 0.93%   |
| Richmond         | 1         | 0.93%   |
| Resistencia      | 1         | 0.93%   |
| Quezon City      | 1         | 0.93%   |
| Pretoria         | 1         | 0.93%   |
| Pontypool        | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 19     | 13.64%  |
| Unknown             | 17        | 25     | 12.88%  |
| WDC                 | 15        | 19     | 11.36%  |
| Toshiba             | 11        | 12     | 8.33%   |
| Samsung Electronics | 10        | 14     | 7.58%   |
| Hitachi             | 9         | 10     | 6.82%   |
| SanDisk             | 7         | 7      | 5.3%    |
| Kingston            | 6         | 7      | 4.55%   |
| Crucial             | 3         | 3      | 2.27%   |
| Apacer              | 3         | 3      | 2.27%   |
| SPCC                | 2         | 3      | 1.52%   |
| Micron Technology   | 2         | 2      | 1.52%   |
| Intel               | 2         | 2      | 1.52%   |
| HGST                | 2         | 2      | 1.52%   |
| WD MediaMax         | 1         | 1      | 0.76%   |
| W800S               | 1         | 1      | 0.76%   |
| UMIS                | 1         | 1      | 0.76%   |
| Transcend           | 1         | 1      | 0.76%   |
| TO Exter            | 1         | 1      | 0.76%   |
| T-FORCE             | 1         | 1      | 0.76%   |
| SK hynix            | 1         | 1      | 0.76%   |
| RSH-319             | 1         | 1      | 0.76%   |
| Rogueware           | 1         | 1      | 0.76%   |
| Patriot             | 1         | 1      | 0.76%   |
| Maxtor              | 1         | 1      | 0.76%   |
| LITEONIT            | 1         | 1      | 0.76%   |
| Leqixiang           | 1         | 1      | 0.76%   |
| Lenovo              | 1         | 1      | 0.76%   |
| Kston               | 1         | 2      | 0.76%   |
| KINGPOWER           | 1         | 1      | 0.76%   |
| HUSKY               | 1         | 1      | 0.76%   |
| HGST HUS            | 1         | 2      | 0.76%   |
| Gigabyte Technology | 1         | 1      | 0.76%   |
| Fujitsu             | 1         | 1      | 0.76%   |
| External            | 1         | 1      | 0.76%   |
| Apricorn            | 1         | 1      | 0.76%   |
| Apple               | 1         | 2      | 0.76%   |
| A-DATA Technology   | 1         | 1      | 0.76%   |
| 2.5"                | 1         | 2      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 3         | 2.05%   |
| Unknown SD/MMC/MS PRO 1TB            | 2         | 1.37%   |
| Unknown NCard  32GB                  | 2         | 1.37%   |
| Unknown MMC64G  64GB                 | 2         | 1.37%   |
| Unknown MMC Card  64GB               | 2         | 1.37%   |
| Unknown DA4032  32GB                 | 2         | 1.37%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.37%   |
| Toshiba DT01ACA100 1TB               | 2         | 1.37%   |
| SPCC Solid State Disk 120GB          | 2         | 1.37%   |
| Seagate ST9500325AS 500GB            | 2         | 1.37%   |
| Seagate ST3120213AS 120GB            | 2         | 1.37%   |
| SanDisk DF4032  32GB                 | 2         | 1.37%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 1.37%   |
| Apacer 16GB SATA Flash Drive SSD     | 2         | 1.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.68%   |
| WDC WDS500G2B0A 500GB SSD            | 1         | 0.68%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.68%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.68%   |
| WDC WD800BB-00CAA1 80GB              | 1         | 0.68%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.68%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1         | 0.68%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.68%   |
| WDC WD3200BPVT-00HXZT3 320GB         | 1         | 0.68%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.68%   |
| WDC WD30EZRZ-00GXCB0 3TB             | 1         | 0.68%   |
| WDC WD2500AAJS-07M0A0 250GB          | 1         | 0.68%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.68%   |
| WDC WD20EZBX-00AYRA0 2TB             | 1         | 0.68%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.68%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.68%   |
| WDC WD10EZRZ-00Z5HB0 1TB             | 1         | 0.68%   |
| WDC WD10EURX-63C57Y0 1TB             | 1         | 0.68%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.68%   |
| WD MediaMax WL250GSA872 250GB        | 1         | 0.68%   |
| W800S 256GB SSD                      | 1         | 0.68%   |
| Unknown SF64G  64GB                  | 1         | 0.68%   |
| Unknown SD  32GB                     | 1         | 0.68%   |
| Unknown SC64G  64GB                  | 1         | 0.68%   |
| Unknown MMC Card  32GB               | 1         | 0.68%   |
| Unknown MBG4GC  32GB                 | 1         | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 18     | 29.03%  |
| WDC                 | 12        | 14     | 19.35%  |
| Toshiba             | 10        | 11     | 16.13%  |
| Hitachi             | 9         | 10     | 14.52%  |
| Samsung Electronics | 3         | 6      | 4.84%   |
| Unknown             | 2         | 2      | 3.23%   |
| HGST                | 2         | 2      | 3.23%   |
| WD MediaMax         | 1         | 1      | 1.61%   |
| RSH-319             | 1         | 1      | 1.61%   |
| Maxtor              | 1         | 1      | 1.61%   |
| Fujitsu             | 1         | 1      | 1.61%   |
| External            | 1         | 1      | 1.61%   |
| Apricorn            | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 15.56%  |
| Kingston            | 5         | 6      | 11.11%  |
| WDC                 | 3         | 3      | 6.67%   |
| SanDisk             | 3         | 3      | 6.67%   |
| Crucial             | 3         | 3      | 6.67%   |
| Apacer              | 3         | 3      | 6.67%   |
| SPCC                | 2         | 3      | 4.44%   |
| Micron Technology   | 2         | 2      | 4.44%   |
| Intel               | 2         | 2      | 4.44%   |
| W800S               | 1         | 1      | 2.22%   |
| Transcend           | 1         | 1      | 2.22%   |
| Toshiba             | 1         | 1      | 2.22%   |
| TO Exter            | 1         | 1      | 2.22%   |
| Rogueware           | 1         | 1      | 2.22%   |
| Patriot             | 1         | 1      | 2.22%   |
| LITEONIT            | 1         | 1      | 2.22%   |
| Leqixiang           | 1         | 1      | 2.22%   |
| Lenovo              | 1         | 1      | 2.22%   |
| Kston               | 1         | 2      | 2.22%   |
| KINGPOWER           | 1         | 1      | 2.22%   |
| HUSKY               | 1         | 1      | 2.22%   |
| Gigabyte Technology | 1         | 1      | 2.22%   |
| A-DATA Technology   | 1         | 1      | 2.22%   |
| 2.5"                | 1         | 2      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 51        | 69     | 41.46%  |
| SSD     | 44        | 49     | 35.77%  |
| MMC     | 20        | 27     | 16.26%  |
| NVMe    | 7         | 9      | 5.69%   |
| Unknown | 1         | 3      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 83        | 113    | 72.17%  |
| MMC  | 20        | 27     | 17.39%  |
| NVMe | 7         | 9      | 6.09%   |
| SAS  | 5         | 8      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 69        | 85     | 70.41%  |
| 0.51-1.0   | 20        | 22     | 20.41%  |
| 1.01-2.0   | 4         | 5      | 4.08%   |
| 2.01-3.0   | 3         | 4      | 3.06%   |
| 3.01-4.0   | 2         | 2      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 31.19%  |
| 251-500        | 25        | 22.94%  |
| 21-50          | 12        | 11.01%  |
| 1-20           | 12        | 11.01%  |
| 51-100         | 11        | 10.09%  |
| 501-1000       | 6         | 5.5%    |
| 2001-3000      | 4         | 3.67%   |
| More than 3000 | 2         | 1.83%   |
| 1001-2000      | 2         | 1.83%   |
| Unknown        | 1         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 61        | 55.96%  |
| 21-50          | 23        | 21.1%   |
| 101-250        | 8         | 7.34%   |
| 51-100         | 6         | 5.5%    |
| 251-500        | 3         | 2.75%   |
| 501-1000       | 3         | 2.75%   |
| 1001-2000      | 2         | 1.83%   |
| More than 3000 | 1         | 0.92%   |
| 2001-3000      | 1         | 0.92%   |
| Unknown        | 1         | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                 | 2         | 2      | 11.11%  |
| Apacer 16GB SATA Flash Drive SSD          | 2         | 2      | 11.11%  |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 5.56%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 1      | 5.56%   |
| Toshiba MK6465GSX 640GB                   | 1         | 1      | 5.56%   |
| Seagate ST9320325AS 320GB                 | 1         | 1      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 5.56%   |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 1      | 5.56%   |
| Seagate ST320LT020-9YG142 320GB           | 1         | 1      | 5.56%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1      | 5.56%   |
| Samsung Electronics HM121HI 120GB         | 1         | 4      | 5.56%   |
| Micron Technology MTFDDAV256TBN 256GB SSD | 1         | 1      | 5.56%   |
| Hitachi HTS545050A7E380 500GB             | 1         | 1      | 5.56%   |
| Fujitsu MHY2120BH 120GB                   | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 44.44%  |
| Toshiba             | 3         | 3      | 16.67%  |
| Apacer              | 2         | 2      | 11.11%  |
| WDC                 | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 4      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| Hitachi             | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 53.33%  |
| Toshiba             | 3         | 3      | 20%     |
| WDC                 | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 4      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |
| Fujitsu             | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 83.33%  |
| SSD  | 3         | 3      | 16.67%  |

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
| Detected | 62        | 96     | 56.36%  |
| Works    | 30        | 40     | 27.27%  |
| Malfunc  | 18        | 21     | 16.36%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 72        | 70.59%  |
| AMD                         | 16        | 15.69%  |
| Nvidia                      | 4         | 3.92%   |
| SanDisk                     | 2         | 1.96%   |
| Union Memory (Shenzhen)     | 1         | 0.98%   |
| SK hynix                    | 1         | 0.98%   |
| Seagate Technology          | 1         | 0.98%   |
| Samsung Electronics         | 1         | 0.98%   |
| Marvell Technology Group    | 1         | 0.98%   |
| Kingston Technology Company | 1         | 0.98%   |
| JMicron Technology          | 1         | 0.98%   |
| ASMedia Technology          | 1         | 0.98%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 8.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 6.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5         | 4.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 4.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 4.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 3.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 3.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 3.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 2.42%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 2.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 2.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 2.42%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 2.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 1.61%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.81%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.81%   |
| Seagate FireCuda 520 SSD                                                         | 1         | 0.81%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.81%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.81%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.81%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.81%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.81%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                     | 1         | 0.81%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.81%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.81%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1         | 0.81%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.81%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 0.81%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1         | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.81%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 76        | 70.37%  |
| IDE  | 22        | 20.37%  |
| NVMe | 6         | 5.56%   |
| RAID | 4         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 90        | 83.33%  |
| AMD    | 18        | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 3.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 3.7%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 3         | 2.78%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 1.85%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 1.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.85%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.85%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.85%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.85%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 1.85%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 1.85%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.93%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz           | 1         | 0.93%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.93%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.93%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.93%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.93%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.93%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.93%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.93%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.93%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.93%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 1         | 0.93%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 1         | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.93%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 1         | 0.93%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.93%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1         | 0.93%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.93%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 0.93%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 20        | 18.52%  |
| Intel Celeron      | 18        | 16.67%  |
| Intel Atom         | 12        | 11.11%  |
| Intel Core 2 Duo   | 11        | 10.19%  |
| Intel Core i7      | 8         | 7.41%   |
| Intel Core i3      | 8         | 7.41%   |
| Intel Pentium      | 3         | 2.78%   |
| AMD A6             | 3         | 2.78%   |
| Intel Xeon         | 2         | 1.85%   |
| Intel Pentium D    | 2         | 1.85%   |
| Intel Core 2 Quad  | 2         | 1.85%   |
| AMD Ryzen 7        | 2         | 1.85%   |
| AMD Ryzen 5        | 2         | 1.85%   |
| AMD FX             | 2         | 1.85%   |
| AMD Athlon 64 X2   | 2         | 1.85%   |
| Intel Pentium Dual | 1         | 0.93%   |
| Intel Core m3      | 1         | 0.93%   |
| Intel Core i9      | 1         | 0.93%   |
| Intel Core 2       | 1         | 0.93%   |
| AMD Ryzen 9        | 1         | 0.93%   |
| AMD Phenom II X4   | 1         | 0.93%   |
| AMD G              | 1         | 0.93%   |
| AMD E1             | 1         | 0.93%   |
| AMD E              | 1         | 0.93%   |
| AMD A8             | 1         | 0.93%   |
| AMD A4             | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 62        | 57.41%  |
| 4      | 34        | 31.48%  |
| 1      | 4         | 3.7%    |
| 8      | 3         | 2.78%   |
| 6      | 2         | 1.85%   |
| 3      | 2         | 1.85%   |
| 10     | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 108       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 65        | 60.19%  |
| 2      | 43        | 39.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 108       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 39.81%  |
| 0x406c4    | 7         | 6.48%   |
| 0x206a7    | 6         | 5.56%   |
| 0x306a9    | 5         | 4.63%   |
| 0x406c3    | 3         | 2.78%   |
| 0x40651    | 3         | 2.78%   |
| 0x306c3    | 3         | 2.78%   |
| 0x1067a    | 3         | 2.78%   |
| 0x806e9    | 2         | 1.85%   |
| 0x706a8    | 2         | 1.85%   |
| 0x6fd      | 2         | 1.85%   |
| 0x506e3    | 2         | 1.85%   |
| 0x20655    | 2         | 1.85%   |
| 0x106ca    | 2         | 1.85%   |
| 0x06006705 | 2         | 1.85%   |
| 0xa0653    | 1         | 0.93%   |
| 0x906ed    | 1         | 0.93%   |
| 0x906c0    | 1         | 0.93%   |
| 0x806ec    | 1         | 0.93%   |
| 0x806ea    | 1         | 0.93%   |
| 0x706a1    | 1         | 0.93%   |
| 0x6fb      | 1         | 0.93%   |
| 0x6fa      | 1         | 0.93%   |
| 0x6f6      | 1         | 0.93%   |
| 0x506c9    | 1         | 0.93%   |
| 0x30679    | 1         | 0.93%   |
| 0x30678    | 1         | 0.93%   |
| 0x106a5    | 1         | 0.93%   |
| 0x0a50000c | 1         | 0.93%   |
| 0x0a201009 | 1         | 0.93%   |
| 0x08001138 | 1         | 0.93%   |
| 0x0700010f | 1         | 0.93%   |
| 0x06001119 | 1         | 0.93%   |
| 0x06001116 | 1         | 0.93%   |
| 0x06000852 | 1         | 0.93%   |
| 0x05000119 | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 20        | 18.52%  |
| SandyBridge   | 9         | 8.33%   |
| IvyBridge     | 9         | 8.33%   |
| Haswell       | 9         | 8.33%   |
| Penryn        | 8         | 7.41%   |
| Core          | 7         | 6.48%   |
| Goldmont plus | 6         | 5.56%   |
| KabyLake      | 5         | 4.63%   |
| Piledriver    | 4         | 3.7%    |
| Skylake       | 3         | 2.78%   |
| Zen+          | 2         | 1.85%   |
| Zen 3         | 2         | 1.85%   |
| Westmere      | 2         | 1.85%   |
| NetBurst      | 2         | 1.85%   |
| Nehalem       | 2         | 1.85%   |
| K8 Hammer     | 2         | 1.85%   |
| Excavator     | 2         | 1.85%   |
| CometLake     | 2         | 1.85%   |
| Broadwell     | 2         | 1.85%   |
| Bonnell       | 2         | 1.85%   |
| Bobcat        | 2         | 1.85%   |
| Zen           | 1         | 0.93%   |
| Tremont       | 1         | 0.93%   |
| K10 Llano     | 1         | 0.93%   |
| K10           | 1         | 0.93%   |
| Jaguar        | 1         | 0.93%   |
| Goldmont      | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 72        | 62.07%  |
| AMD    | 24        | 20.69%  |
| Nvidia | 20        | 17.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 12%     |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 6.4%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 5.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 4.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 4%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 4%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 3.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 3.2%    |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.6%    |
| Intel HD Graphics 5500                                                                   | 2         | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.6%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.6%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 1.6%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.6%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.6%    |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 1.6%    |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2         | 1.6%    |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2         | 1.6%    |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1         | 0.8%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.8%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.8%    |
| Nvidia GT218 [ION]                                                                       | 1         | 0.8%    |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.8%    |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.8%    |
| Nvidia GM200GL [Tesla M40]                                                               | 1         | 0.8%    |
| Nvidia GM200GL [Quadro M6000]                                                            | 1         | 0.8%    |
| Nvidia GM107GL [Quadro K2200]                                                            | 1         | 0.8%    |
| Nvidia GK208B [GeForce GT 720]                                                           | 1         | 0.8%    |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.8%    |
| Nvidia GK106GL [Quadro K4000]                                                            | 1         | 0.8%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.8%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 1         | 0.8%    |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1         | 0.8%    |
| Nvidia G86 [Quadro NVS 290]                                                              | 1         | 0.8%    |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 0.8%    |
| Nvidia C78 [GeForce 9100]                                                                | 1         | 0.8%    |
| Nvidia C77 [GeForce 8200]                                                                | 1         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 63        | 58.33%  |
| 1 x Nvidia         | 16        | 14.81%  |
| 1 x AMD            | 15        | 13.89%  |
| 2 x AMD            | 4         | 3.7%    |
| Intel + AMD        | 4         | 3.7%    |
| Other              | 2         | 1.85%   |
| Intel + Nvidia     | 2         | 1.85%   |
| Intel + 2 x Nvidia | 1         | 0.93%   |
| AMD + Nvidia       | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 100       | 92.59%  |
| Proprietary | 7         | 6.48%   |
| Unknown     | 1         | 0.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 80.56%  |
| 0.01-0.5   | 9         | 8.33%   |
| 7.01-8.0   | 3         | 2.78%   |
| 1.01-2.0   | 3         | 2.78%   |
| 2.01-3.0   | 2         | 1.85%   |
| 0.51-1.0   | 2         | 1.85%   |
| 3.01-4.0   | 1         | 0.93%   |
| 8.01-16.0  | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 14        | 13.46%  |
| LG Display           | 13        | 12.5%   |
| Samsung Electronics  | 12        | 11.54%  |
| Chimei Innolux       | 12        | 11.54%  |
| Hewlett-Packard      | 6         | 5.77%   |
| BOE                  | 6         | 5.77%   |
| Goldstar             | 4         | 3.85%   |
| Dell                 | 4         | 3.85%   |
| Apple                | 4         | 3.85%   |
| Ancor Communications | 3         | 2.88%   |
| Acer                 | 3         | 2.88%   |
| Sharp                | 2         | 1.92%   |
| Philips              | 2         | 1.92%   |
| Lenovo               | 2         | 1.92%   |
| CPT                  | 2         | 1.92%   |
| BenQ                 | 2         | 1.92%   |
| ViewSonic            | 1         | 0.96%   |
| Unknown              | 1         | 0.96%   |
| Toshiba              | 1         | 0.96%   |
| Sony                 | 1         | 0.96%   |
| SNC                  | 1         | 0.96%   |
| Sampo                | 1         | 0.96%   |
| MSI                  | 1         | 0.96%   |
| LG Philips           | 1         | 0.96%   |
| LG Electronics       | 1         | 0.96%   |
| JVC                  | 1         | 0.96%   |
| JDI                  | 1         | 0.96%   |
| HannStar             | 1         | 0.96%   |
| Eizo                 | 1         | 0.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 3         | 2.86%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 1.9%    |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 1.9%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 1.9%    |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 0.95%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1         | 0.95%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 0.95%   |
| Sony TV SNY9C01 1920x1080                                             | 1         | 0.95%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 1         | 0.95%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.95%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch              | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch  | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.95%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1         | 0.95%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch  | 1         | 0.95%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch    | 1         | 0.95%   |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                         | 1         | 0.95%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 1         | 0.95%   |
| Philips 191EL PHLC050 1366x768 410x230mm 18.5-inch                    | 1         | 0.95%   |
| MSI MAG272CQR MSI3CA6 2560x1440 598x336mm 27.0-inch                   | 1         | 0.95%   |
| LG Philips LCD Monitor LPLEC00 1280x800 331x207mm 15.4-inch           | 1         | 0.95%   |
| LG Electronics LCD Monitor E2241 1920x1080                            | 1         | 0.95%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x174mm 14.0-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 0.95%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 38        | 38%     |
| 1920x1080 (FHD)    | 23        | 23%     |
| 1280x800 (WXGA)    | 10        | 10%     |
| 1600x900 (HD+)     | 8         | 8%      |
| 1680x1050 (WSXGA+) | 5         | 5%      |
| 2560x1440 (QHD)    | 3         | 3%      |
| 1280x1024 (SXGA)   | 3         | 3%      |
| 800x600            | 1         | 1%      |
| 3200x1800 (QHD+)   | 1         | 1%      |
| 3000x2000          | 1         | 1%      |
| 2560x1600          | 1         | 1%      |
| 2560x1080          | 1         | 1%      |
| 2160x1440          | 1         | 1%      |
| 1528x1222          | 1         | 1%      |
| 1440x900 (WXGA+)   | 1         | 1%      |
| 1360x768           | 1         | 1%      |
| 1280x720 (HD)      | 1         | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 22        | 21.36%  |
| 13      | 14        | 13.59%  |
| 14      | 11        | 10.68%  |
| 11      | 7         | 6.8%    |
| 23      | 6         | 5.83%   |
| 18      | 5         | 4.85%   |
| 17      | 5         | 4.85%   |
| 22      | 4         | 3.88%   |
| 20      | 4         | 3.88%   |
| 19      | 4         | 3.88%   |
| 27      | 3         | 2.91%   |
| 24      | 3         | 2.91%   |
| 21      | 3         | 2.91%   |
| Unknown | 3         | 2.91%   |
| 72      | 1         | 0.97%   |
| 49      | 1         | 0.97%   |
| 43      | 1         | 0.97%   |
| 28      | 1         | 0.97%   |
| 16      | 1         | 0.97%   |
| 12      | 1         | 0.97%   |
| 10      | 1         | 0.97%   |
| 9       | 1         | 0.97%   |
| 8       | 1         | 0.97%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 37.86%  |
| 401-500     | 19        | 18.45%  |
| 201-300     | 18        | 17.48%  |
| 501-600     | 12        | 11.65%  |
| 351-400     | 6         | 5.83%   |
| Unknown     | 3         | 2.91%   |
| 101-200     | 2         | 1.94%   |
| 601-700     | 1         | 0.97%   |
| 1501-2000   | 1         | 0.97%   |
| 1001-1500   | 1         | 0.97%   |
| 901-1000    | 1         | 0.97%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 70        | 72.16%  |
| 16/10   | 17        | 17.53%  |
| 4/3     | 3         | 3.09%   |
| 5/4     | 2         | 2.06%   |
| 3/2     | 2         | 2.06%   |
| Unknown | 2         | 2.06%   |
| 21/9    | 1         | 1.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 22        | 21.57%  |
| 101-110        | 21        | 20.59%  |
| 201-250        | 14        | 13.73%  |
| 151-200        | 8         | 7.84%   |
| 51-60          | 7         | 6.86%   |
| 141-150        | 6         | 5.88%   |
| 121-130        | 4         | 3.92%   |
| 71-80          | 3         | 2.94%   |
| 301-350        | 3         | 2.94%   |
| Unknown        | 3         | 2.94%   |
| More than 1000 | 2         | 1.96%   |
| 41-50          | 2         | 1.96%   |
| 251-300        | 2         | 1.96%   |
| 61-70          | 1         | 0.98%   |
| 1-40           | 1         | 0.98%   |
| 131-140        | 1         | 0.98%   |
| 111-120        | 1         | 0.98%   |
| 501-1000       | 1         | 0.98%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 39        | 38.61%  |
| 51-100        | 33        | 32.67%  |
| 121-160       | 16        | 15.84%  |
| 161-240       | 5         | 4.95%   |
| 1-50          | 3         | 2.97%   |
| Unknown       | 3         | 2.97%   |
| More than 240 | 2         | 1.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 97        | 89.81%  |
| 2     | 8         | 7.41%   |
| 0     | 2         | 1.85%   |
| 3     | 1         | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 49        | 32.24%  |
| Intel                           | 42        | 27.63%  |
| Qualcomm Atheros                | 22        | 14.47%  |
| Broadcom                        | 11        | 7.24%   |
| TP-Link                         | 4         | 2.63%   |
| Samsung Electronics             | 4         | 2.63%   |
| Marvell Technology Group        | 4         | 2.63%   |
| Nvidia                          | 3         | 1.97%   |
| Broadcom Limited                | 3         | 1.97%   |
| Qualcomm Atheros Communications | 2         | 1.32%   |
| Trident Microsystems            | 1         | 0.66%   |
| Sierra Wireless                 | 1         | 0.66%   |
| Ralink Technology               | 1         | 0.66%   |
| Qualcomm                        | 1         | 0.66%   |
| Microsoft                       | 1         | 0.66%   |
| MediaTek                        | 1         | 0.66%   |
| ICS Advent                      | 1         | 0.66%   |
| Belkin Components               | 1         | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 30        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 8         | 4.44%   |
| Intel Wireless 7260                                                 | 5         | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 5         | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 4         | 2.22%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 3         | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 3         | 1.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3         | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 3         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 3         | 1.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 3         | 1.67%   |
| Intel Wireless 7265                                                 | 3         | 1.67%   |
| Intel Ethernet Controller I225-V                                    | 3         | 1.67%   |
| Intel Centrino Wireless-N 2230                                      | 3         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2         | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 2         | 1.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2         | 1.11%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 2         | 1.11%   |
| Nvidia MCP77 Ethernet                                               | 2         | 1.11%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller             | 2         | 1.11%   |
| Intel Wireless 8260                                                 | 2         | 1.11%   |
| Intel Wireless 3160                                                 | 2         | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 2         | 1.11%   |
| Intel NM10/ICH7 Family LAN Controller                               | 2         | 1.11%   |
| Intel Ethernet Connection I218-LM                                   | 2         | 1.11%   |
| Intel Ethernet Connection I217-LM                                   | 2         | 1.11%   |
| Intel Centrino Advanced-N 6235                                      | 2         | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 1.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 2         | 1.11%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                     | 2         | 1.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 2         | 1.11%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2         | 1.11%   |
| Trident Microsystems 4DWave DX                                      | 1         | 0.56%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1         | 0.56%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1         | 0.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1         | 0.56%   |
| TP-Link 802.11ac NIC                                                | 1         | 0.56%   |
| Sierra Wireless EM7305 Modem                                        | 1         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 36.9%   |
| Qualcomm Atheros                | 20        | 23.81%  |
| Realtek Semiconductor           | 15        | 17.86%  |
| Broadcom                        | 6         | 7.14%   |
| TP-Link                         | 3         | 3.57%   |
| Qualcomm Atheros Communications | 2         | 2.38%   |
| Broadcom Limited                | 2         | 2.38%   |
| Sierra Wireless                 | 1         | 1.19%   |
| Ralink Technology               | 1         | 1.19%   |
| Microsoft                       | 1         | 1.19%   |
| MediaTek                        | 1         | 1.19%   |
| Belkin Components               | 1         | 1.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                     | 5         | 5.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 4.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 3.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 3.57%   |
| Intel Wireless 7265                                                     | 3         | 3.57%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 3.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.38%   |
| Intel Wireless 8260                                                     | 2         | 2.38%   |
| Intel Wireless 3160                                                     | 2         | 2.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 2.38%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 2.38%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.38%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 2         | 2.38%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 1.19%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.19%   |
| TP-Link 802.11ac NIC                                                    | 1         | 1.19%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 1.19%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.19%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.19%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                 | 1         | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.19%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.19%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.19%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.19%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 1.19%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter         | 1         | 1.19%   |
| Qualcomm Atheros UB94                                                   | 1         | 1.19%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.19%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.19%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 1.19%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 44        | 46.32%  |
| Intel                    | 22        | 23.16%  |
| Broadcom                 | 8         | 8.42%   |
| Qualcomm Atheros         | 5         | 5.26%   |
| Samsung Electronics      | 4         | 4.21%   |
| Marvell Technology Group | 4         | 4.21%   |
| Nvidia                   | 3         | 3.16%   |
| Trident Microsystems     | 1         | 1.05%   |
| TP-Link                  | 1         | 1.05%   |
| Qualcomm                 | 1         | 1.05%   |
| ICS Advent               | 1         | 1.05%   |
| Broadcom Limited         | 1         | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30        | 31.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 5.21%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 3.13%   |
| Intel Ethernet Controller I225-V                                               | 3         | 3.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 2.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 2.08%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 2.08%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 2.08%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 2         | 2.08%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 2.08%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 2.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 2.08%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.08%   |
| Trident Microsystems 4DWave DX                                                 | 1         | 1.04%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.04%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.04%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.04%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 1.04%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.04%   |
| Qualcomm Mobile Router                                                         | 1         | 1.04%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.04%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 1.04%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.04%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 1.04%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 1.04%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.04%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.04%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 1.04%   |
| Intel 82567LF-2 Gigabit Network Connection                                     | 1         | 1.04%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 1.04%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 1.04%   |
| Broadcom NetXtreme BCM5756ME Gigabit Ethernet PCI Express                      | 1         | 1.04%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 87        | 52.41%  |
| WiFi     | 79        | 47.59%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 55.66%  |
| Ethernet | 47        | 44.34%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 52        | 48.15%  |
| 1     | 43        | 39.81%  |
| 0     | 10        | 9.26%   |
| 3     | 2         | 1.85%   |
| 4     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 72.48%  |
| Yes  | 30        | 27.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 38.89%  |
| Realtek Semiconductor           | 8         | 14.81%  |
| Qualcomm Atheros Communications | 6         | 11.11%  |
| IMC Networks                    | 3         | 5.56%   |
| Foxconn / Hon Hai               | 3         | 5.56%   |
| Dell                            | 3         | 5.56%   |
| Broadcom                        | 3         | 5.56%   |
| Apple                           | 3         | 5.56%   |
| Syntek                          | 1         | 1.85%   |
| MediaTek                        | 1         | 1.85%   |
| Logitech                        | 1         | 1.85%   |
| Alps Electric                   | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 14        | 25.93%  |
| Realtek Bluetooth Radio                                                             | 4         | 7.41%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 7.41%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 5.56%   |
| Apple Bluetooth Host Controller                                                     | 3         | 5.56%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 3.7%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 3.7%    |
| IMC Networks Bluetooth Device                                                       | 2         | 3.7%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 3.7%    |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 1.85%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 1.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.85%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.85%   |
| MediaTek Wireless_Device                                                            | 1         | 1.85%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 1.85%   |
| Intel AX200 Bluetooth                                                               | 1         | 1.85%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 1.85%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.85%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 1.85%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 1.85%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.85%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.85%   |
| Alps Electric Bluetooth Adapter                                                     | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 79        | 63.2%   |
| AMD                                          | 20        | 16%     |
| Nvidia                                       | 17        | 13.6%   |
| C-Media Electronics                          | 2         | 1.6%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.8%    |
| Razer USA                                    | 1         | 0.8%    |
| Logitech                                     | 1         | 0.8%    |
| JMTek                                        | 1         | 0.8%    |
| Ensoniq                                      | 1         | 0.8%    |
| Creative Labs                                | 1         | 0.8%    |
| ASUSTek Computer                             | 1         | 0.8%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 7.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 6.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 5.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 4.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.38%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.7%    |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 4         | 2.7%    |
| AMD FCH Azalia Controller                                                                         | 4         | 2.7%    |
| Nvidia High Definition Audio Controller                                                           | 3         | 2.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 2.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 2.03%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 1.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.35%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.35%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.35%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.35%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.35%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.35%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.35%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 0.68%   |
| Razer USA Razer Kraken X USB                                                                      | 1         | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.68%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.68%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.68%   |
| Nvidia GM200 High Definition Audio                                                                | 1         | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 14        | 17.72%  |
| SK hynix            | 14        | 17.72%  |
| Samsung Electronics | 14        | 17.72%  |
| Micron Technology   | 11        | 13.92%  |
| Kingston            | 5         | 6.33%   |
| Elpida              | 4         | 5.06%   |
| Corsair             | 4         | 5.06%   |
| Nanya Technology    | 3         | 3.8%    |
| Smart               | 2         | 2.53%   |
| Unknown             | 2         | 2.53%   |
| Unknown (ABCD)      | 1         | 1.27%   |
| Ramaxel Technology  | 1         | 1.27%   |
| Novatech            | 1         | 1.27%   |
| HMD                 | 1         | 1.27%   |
| G.Skill             | 1         | 1.27%   |
| A-DATA Technology   | 1         | 1.27%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 3.45%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 2.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 2.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 2.3%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.3%    |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 2.3%    |
| Unknown                                                          | 2         | 2.3%    |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.15%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.15%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 1.15%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 1.15%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 1.15%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.15%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.15%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s         | 1         | 1.15%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.15%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 1.15%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.15%   |
| SK hynix RAM HT5SMRAP 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.15%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s          | 1         | 1.15%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 1         | 1.15%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.15%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s              | 1         | 1.15%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                     | 1         | 1.15%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.15%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5674EB0-YK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.15%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.15%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 37        | 54.41%  |
| DDR4    | 16        | 23.53%  |
| DDR2    | 6         | 8.82%   |
| LPDDR4  | 3         | 4.41%   |
| LPDDR3  | 3         | 4.41%   |
| SDRAM   | 2         | 2.94%   |
| Unknown | 1         | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 69.12%  |
| DIMM         | 14        | 20.59%  |
| Row Of Chips | 4         | 5.88%   |
| Unknown      | 3         | 4.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 29        | 36.25%  |
| 2048  | 26        | 32.5%   |
| 8192  | 14        | 17.5%   |
| 16384 | 5         | 6.25%   |
| 1024  | 4         | 5%      |
| 32768 | 1         | 1.25%   |
| 512   | 1         | 1.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 23        | 31.94%  |
| 1333    | 9         | 12.5%   |
| 3200    | 5         | 6.94%   |
| 2667    | 4         | 5.56%   |
| 667     | 4         | 5.56%   |
| 2400    | 3         | 4.17%   |
| 1334    | 3         | 4.17%   |
| 1066    | 3         | 4.17%   |
| Unknown | 3         | 4.17%   |
| 2133    | 2         | 2.78%   |
| 1867    | 2         | 2.78%   |
| 1866    | 2         | 2.78%   |
| 1067    | 2         | 2.78%   |
| 4199    | 1         | 1.39%   |
| 3600    | 1         | 1.39%   |
| 3400    | 1         | 1.39%   |
| 3266    | 1         | 1.39%   |
| 2800    | 1         | 1.39%   |
| 2048    | 1         | 1.39%   |
| 975     | 1         | 1.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 300 | 1         | 100%    |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 15        | 25%     |
| Microdia                               | 8         | 13.33%  |
| Realtek Semiconductor                  | 5         | 8.33%   |
| Sunplus Innovation Technology          | 4         | 6.67%   |
| Syntek                                 | 3         | 5%      |
| IMC Networks                           | 3         | 5%      |
| Apple                                  | 3         | 5%      |
| Alcor Micro                            | 3         | 5%      |
| Quanta                                 | 2         | 3.33%   |
| Logitech                               | 2         | 3.33%   |
| Lenovo                                 | 2         | 3.33%   |
| Suyin                                  | 1         | 1.67%   |
| Silicon Motion                         | 1         | 1.67%   |
| Ricoh                                  | 1         | 1.67%   |
| Pixart Imaging                         | 1         | 1.67%   |
| Microsoft                              | 1         | 1.67%   |
| Cubeternet                             | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.67%   |
| AVerMedia Technologies                 | 1         | 1.67%   |
| ALi                                    | 1         | 1.67%   |
| Acer                                   | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 8.2%    |
| Sunplus HD WebCam                                   | 2         | 3.28%   |
| Microdia Integrated Webcam                          | 2         | 3.28%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 3.28%   |
| Chicony HD WebCam                                   | 2         | 3.28%   |
| Chicony EasyCamera                                  | 2         | 3.28%   |
| Apple FaceTime HD Camera                            | 2         | 3.28%   |
| Alcor Micro HD Webcam                               | 2         | 3.28%   |
| Syntek USB2.0 Camera                                | 1         | 1.64%   |
| Syntek USB Camera Device                            | 1         | 1.64%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.64%   |
| Suyin 1.3M HD WebCam                                | 1         | 1.64%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.64%   |
| Sunplus Asus Webcam                                 | 1         | 1.64%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 1.64%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 1.64%   |
| Realtek USB Camera                                  | 1         | 1.64%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.64%   |
| Realtek Integrated_Webcam_HD                        | 1         | 1.64%   |
| Realtek Integrated Webcam HD                        | 1         | 1.64%   |
| Realtek EasyCamera                                  | 1         | 1.64%   |
| Quanta HP Webcam                                    | 1         | 1.64%   |
| Quanta Chromebook HD Camera                         | 1         | 1.64%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                | 1         | 1.64%   |
| Microsoft LifeCam VX-800                            | 1         | 1.64%   |
| Microdia Webcam Vitade AF                           | 1         | 1.64%   |
| Microdia Webcam                                     | 1         | 1.64%   |
| Microdia Lenovo EasyCamera                          | 1         | 1.64%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.64%   |
| Microdia HP Webcam-50                               | 1         | 1.64%   |
| Microdia 1.3 MPixel Integrated Webcam               | 1         | 1.64%   |
| Logitech Webcam C270                                | 1         | 1.64%   |
| Logitech HD Webcam C615                             | 1         | 1.64%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.64%   |
| Lenovo Integrated Webcam                            | 1         | 1.64%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.64%   |
| Cubeternet GL-UPC822 UVC WebCam                     | 1         | 1.64%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.64%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.64%   |
| Chicony HP Webcam                                   | 1         | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 41.67%  |
| Upek                  | 3         | 25%     |
| STMicroelectronics    | 2         | 16.67%  |
| Elan Microelectronics | 1         | 8.33%   |
| AuthenTec             | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 25%     |
| STMicroelectronics Fingerprint Reader                  | 2         | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 8.33%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 8.33%   |
| Elan ELAN:Fingerprint                                  | 1         | 8.33%   |
| AuthenTec AES2810                                      | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 50%     |
| O2 Micro | 1         | 25%     |
| Cherry   | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Broadcom 5880                               | 2         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader        | 1         | 25%     |
| Cherry SmartCard Reader Keyboard KC 1000 SC | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 89        | 81.65%  |
| 1     | 20        | 18.35%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 12        | 60%     |
| Net/wireless       | 3         | 15%     |
| Chipcard           | 3         | 15%     |
| Graphics card      | 1         | 5%      |
| Bluetooth          | 1         | 5%      |

